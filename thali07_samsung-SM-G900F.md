#### Test 549702617e2936d_thali07_samsung-SM-G900F Logs


```
--------- beginning of main,
E/LightSensor(  888): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 3, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=1, bp1=1, cp1=3, cpl=3202560
--------- beginning of system
D/AutomaticBrightnessController(  888): mCallbacks.updateBrightness()
D/DisplayPowerController(  888): getFinalBrightness : 8 -> 8
V/GLSActivity( 1714): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/art     ( 1714): Explicit concurrent mark sweep GC freed 29390(1782KB) AllocSpace objects, 12(972KB) LOS objects, 40% free, 17MB/29MB, paused 678us total 36.913ms
E/LightSensor(  888): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 3, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=1, bp1=1, cp1=3, cpl=3202560
D/AutomaticBrightnessController(  888): mCallbacks.updateBrightness()
D/DisplayPowerController(  888): getFinalBrightness : 8 -> 8
I/GLSUser ( 1714): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
I/GLSUser ( 1714): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1714): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1714): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 1714): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/ResourcesManager( 1714): creating new AssetManager and set to /system/app/Books/Books.apk
V/BitmapFactory( 1714): DecodeImagePath(decodeResourceStream3) : res/mipmap-xxhdpi-v4/ic_launcher_play_books.png
V/BitmapFactory( 1714): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
D/SecContentProvider2(  888): uri = 14 selection = getSealedState
D/SecContentProvider2(  888): mCursor = null
D/SecContentProvider2(  888): KnoxCustomManagerService offline: service is not available
D/ApplicationPolicy(  888): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
V/ApplicationPolicy(  888): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
D/StatusBar.NetworkController( 1171): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02012b/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020468/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
D/StatusBar.NetworkController( 1171): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1171): applyOpen
D/StatusBar.NetworkController( 1171): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1171): applyOpen
D/StatusBar.NetworkController( 1171): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1171): applyOpen
D/StatusBar.NetworkController( 1171): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1171): applyOpen
D/StatusBar( 1171): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
I/PhoneStatusBar( 1171): Icon Only
W/GLSActivity( 1714): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1714): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1714): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1714): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1714): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1714): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1714): 	at android.os.Binder.execTransact(Binder.java:446)
D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
D/PanelView( 1171): There is/are notification(s) 
D/PanelView( 1171): There is/are notification(s) 
E/BooksAccountManager( 7687): Authentication error
E/BooksAccountManager( 7687): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 7687): android.accounts.AccountManager.convertErrorToException(AccountManager.java:1893)
E/HttpHelper( 7687): null auth token
I/qtaguid ( 7687): Tagging socket 34 with tag 10000000000{256,0} uid -1, pid: 7687, getuid(): 10082
E/LightSensor(  888): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 3, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=1, bp1=1, cp1=3, cpl=3202560
D/AutomaticBrightnessController(  888): mCallbacks.updateBrightness()
D/DisplayPowerController(  888): getFinalBrightness : 8 -> 8
I/qtaguid ( 7687): Untagging socket 34
W/ApiaryClient( 7687): Error response from books API: {
W/ApiaryClient( 7687):  "error": {
W/ApiaryClient( 7687):   "errors": [
W/ApiaryClient( 7687):    {
W/ApiaryClient( 7687):     "domain": "global",
W/ApiaryClient( 7687):     "reason": "required",
W/ApiaryClient( 7687):     "message": "Login Required",
W/ApiaryClient( 7687):     "locationType": "header",
W/ApiaryClient( 7687):     "location": "Authorization"
W/ApiaryClient( 7687):    }
W/ApiaryClient( 7687):   ],
W/ApiaryClient( 7687):   "code": 401,
W/ApiaryClient( 7687):   "message": "Login Required"
W/ApiaryClient( 7687):  }
W/ApiaryClient( 7687): }
W/ApiaryClient( 7687): errCount = 3: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 7687): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3DS0HXd4TFLU4&nonce=5775538404416240872&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 7687): Headers suppressed
D/ConnectivityService(  888): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/AndroidRuntime( 7741): 
D/AndroidRuntime( 7741): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 7741): CheckJNI is OFF
D/AndroidRuntime( 7741): setted country_code = Germany
D/AndroidRuntime( 7741): setted countryiso_code = DE
D/AndroidRuntime( 7741): setted sales_code = DBT
D/AndroidRuntime( 7741): readGMSProperty: start
D/AndroidRuntime( 7741): readGMSProperty: already setted!!
D/AndroidRuntime( 7741): readGMSProperty: end
D/AndroidRuntime( 7741): addProductProperty: start
D/AutomaticBrightnessController(  888): mCallbacks.updateBrightness()
E/LightSensor(  888): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 3, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=1, bp1=1, cp1=3, cpl=3202560
D/DisplayPowerController(  888): getFinalBrightness : 8 -> 8
E/LightSensor(  888): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
D/AutomaticBrightnessController(  888): mCallbacks.updateBrightness()
D/DisplayPowerController(  888): getFinalBrightness : 8 -> 8
E/AffinityControl( 7741): AffinityControl: registerfunction enter
D/AndroidRuntime( 7741): Calling main entry com.android.commands.am.Am
E/PersonaManagerService(  888): inState():  stateMachine is null !!
V/ApplicationPolicy(  888): isApplicationStateBlocked userId 0 pkgname com.test.thalitest
I/ActivityManager(  888): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
D/ResourcesManager(  888): creating new AssetManager and set to /data/app/com.test.thalitest-1/base.apk
D/CustomFrequencyManagerService(  888): acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1958400  uid : 1000  pid : 888  pkgName : ACTIVITY_RESUME_BOOSTER@6
W/ActivityManager(  888): mDVFSHelper.acquire()
D/FocusedStackFrame(  888): Set to : 0
D/AndroidRuntime( 7741): Shutting down VM
D/Launcher.HomeView( 1465): onPause
D/Launcher( 1465): Launcher::setSystemUiTransparency(): getSystemUiVisibility() after setting  = 40000000
D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
V/TaskCloserActivity( 7285): TaskCloserActivity onReceive() - com.sec.android.intent.action.HOME_PAUSE
E/ActivityManager(  888): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  888): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  888): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  888): checkUser: useridlist=null, currentuser=0
D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
I/SurfaceFlinger(  249): id=14 createSurf (1x1),1 flag=404, Starting com.test.thalitest
D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
E/Zygote  ( 7760): MountEmulatedStorage()
E/Zygote  ( 7760): v2
I/libpersona( 7760): KNOX_SDCARD checking this for 10367
I/libpersona( 7760): KNOX_SDCARD not a persona
I/ActivityManager(  888): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=7760 uid=10367 gids={50367, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
I/SELinux ( 7760): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
I/SELinux ( 7760): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
E/SELinux ( 7760): [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
E/LightSensor(  888): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
D/AutomaticBrightnessController(  888): mCallbacks.updateBrightness()
D/DisplayPowerController(  888): getFinalBrightness : 8 -> 8
D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
D/StatusBarManagerService(  888): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
I/MicrophoneInputStream( 1569): mic_close gfk@2c245b0d
D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
V/AudioPolicyManager(  303): stopInput() input 30
V/AudioPolicyManager(  303): releaseInput() 30
V/AudioPolicyManager(  303): closeInput(30)
I/HotwordRecognitionRnr( 1569): Hotword detection finished
V/audio_hw_primary(  303): in_standby: enter
I/HotwordRecognitionRnr( 1569): Stopping hotword detection.
D/TimaKeyStoreProvider( 7760): TimaSignature is unavailable
D/ActivityThread( 7760): Added TimaKeyStore provider
V/WindowOrientationListener(  888): mSContextAutoRotationListener.getProposedRotation, mbResultFaceDectection: false
V/WindowOrientationListener(  888): mSContextAutoRotationListener.getProposedRotation, Rotation: -1
V/WindowManager(  888): rotationForOrientationLw(orient=-1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false
V/WindowOrientationListener(  888): mSContextAutoRotationListener.getProposedRotation, mbResultFaceDectection: false
V/WindowOrientationListener(  888): mSContextAutoRotationListener.getProposedRotation, Rotation: -1
V/ActivityManager(  888): Display changed displayId=0
D/Launcher.HomeView( 1465): onStop
D/SurfaceWidgetClient$ISurfaceWidgetStub( 2029): [237392/6] Surface widget pause on instance = 1
D/accuweather( 2029): [KK AccuPhone]>>> SWW:239 [0:0] [SWW] onPause : instance = 1
D/accuweather( 2029): [KK AccuPhone]>>> SWW:254 [0:0] onPause : size = 0
D/accuweather( 2029): [KK AccuPhone]>>> SWW:545 [0:0]  unRegisterTTReceiver !! 
D/SurfaceWidgetClient$ISurfaceWidgetStub( 2029): [237392/6] Surface widget visibility changed visibility = false on instance = 1
V/audio_hw_primary(  303): stop_input_stream: enter: usecase(7: audio-record)
V/audio_hw_primary(  303): disable_audio_route: enter: usecase(7)
V/audio_hw_primary(  303): disable_audio_route: reset mixer path: audio-record
D/audio_route(  303): ++++ audio_route_update_mixer ==============
D/audio_route(  303): Setting mixer control: MultiMedia1 Mixer SLIM_0_TX
D/audio_route(  303): Setting mixer control: value: 0
D/audio_route(  303): ------ audio_route_update_mixer ==============
V/audio_hw_primary(  303): disable_audio_route: exit
V/audio_hw_primary(  303): disable_snd_device: snd_device(122: vr-main-mic)
D/audio_route(  303): ++++ audio_route_update_mixer ==============
D/audio_route(  303): Setting mixer control: DEC2 Volume
D/audio_route(  303): Setting mixer control: value: 0
D/audio_route(  303): Setting mixer control: SLIM TX7 MUX, value: 0
D/audio_route(  303): Setting mixer control: AIF1_CAP Mixer SLIM TX7
D/audio_route(  303): Setting mixer control: value: 0
D/audio_route(  303): Setting mixer control: DEC2 MUX, value: 0
D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
D/audio_route(  303): ------ audio_route_update_mixer ==============
V/audio_hw_primary(  303): stop_input_stream: exit: status(0)
V/audio_hw_primary(  303): in_standby: exit:  status(0)
D/SurfaceWidgetView( 1465): destroyHardwareResources():150116021
V/audio_hw_primary(  303): adev_close_input_stream
V/audio_hw_primary(  303): in_standby: enter
V/audio_hw_primary(  303): in_standby: exit:  status(0)
E/audio_hw_primary(  303): adev_close_input_stream, set jack_in to null
V/AudioPolicyManager(  303): releaseInput() exit
D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
D/StatusBarManagerService(  888): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
D/accuweather( 2029): [KK AccuPhone]>>> WR:132 [0:0] onPause
D/accuweather( 2029): [KK AccuPhone]>>> SM:538 [0:0] onPause
D/Launcher( 1465): onTrimMemory. Level: 20
D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/ConnectivityService(  888): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/LockPatternUtilsCache( 1171): value : false
D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
D/SurfaceWidgetView( 1465): destroyHardwareResources():150116021
D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/ResourcesManager( 7760): creating new AssetManager and set to /data/app/com.test.thalitest-1/base.apk
D/LockPatternUtilsCache( 1171): value : false
D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
,E/LightSensor(  888): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
D/AutomaticBrightnessController(  888): mCallbacks.updateBrightness()
D/DisplayPowerController(  888): getFinalBrightness : 8 -> 8
D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
I/WebViewFactory( 7760): Loading com.google.android.webview version 37 (1726107-arm) (code 119201)
D/ResourcesManager( 7760): creating new AssetManager and set to /system/app/WebViewGoogle/WebViewGoogle.apk
D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
I/LibraryLoader( 7760): Loading: webviewchromium
I/LibraryLoader( 7760): Time to load native libraries: 2 ms (timestamps 6446-6448)
I/LibraryLoader( 7760): Expected native library version number "",actual native library version number ""
D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
V/WebViewChromiumFactoryProvider( 7760): Binding Chromium to main looper Looper (main, tid 1) {37042d1d}
I/LibraryLoader( 7760): Expected native library version number "",actual native library version number ""
I/chromium( 7760): [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 7760): Initializing chromium process, renderers=0
W/art     ( 7760): Attempt to remove local handle scope entry from IRT, ignoring
D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
W/chromium( 7760): [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
I/chromium( 7760): [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=35 off=46768 len=2953
I/chromium( 7760): [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:36 off:229524 len:643667
D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
I/Adreno-EGL( 7760): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 7760): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 7760): Build Date: 03/03/15 Tue
I/Adreno-EGL( 7760): Local Branch: LA.BF.1.1_RB1_20150108_025_1077123_1158499
I/Adreno-EGL( 7760): Remote Branch: 
I/Adreno-EGL( 7760): Local Patches: 
I/Adreno-EGL( 7760): Reconstruct Branch: 
D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
W/chromium( 7760): [WARNING:proxy_service.cc(901)] PAC support disabled because there is no system implementation
W/chromium( 7760): [WARNING:data_reduction_proxy_settings.cc(403)] SPDY proxy OFF at startup
W/art     ( 7760): Attempt to remove local handle scope entry from IRT, ignoring
W/AwContents( 7760): onDetachedFromWindow called when already detached. Ignoring
D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
D/SystemWebViewEngine( 7760): CordovaWebView is running on device made by: samsung
D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
E/LightSensor(  888): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
D/AutomaticBrightnessController(  888): mCallbacks.updateBrightness()
D/DisplayPowerController(  888): getFinalBrightness : 8 -> 8
W/art     ( 7760): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 7760): Attempt to remove local handle scope entry from IRT, ignoring
D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
D/StatusBar.NetworkController( 1171): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02012b/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020466/com.android.systemui:drawable/stat_sys_signal_inout mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
D/StatusBar.NetworkController( 1171): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1171): applyOpen
D/StatusBar.NetworkController( 1171): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1171): applyOpen
D/StatusBar.NetworkController( 1171): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1171): applyOpen
D/StatusBar.NetworkController( 1171): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1171): applyOpen
D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
D/Activity( 7760): performCreate Call secproduct feature valuefalse
D/Activity( 7760): performCreate Call debug elastic valuetrue
D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
D/OpenGLRenderer( 7760): Render dirty regions requested: true
D/ActivityManager(  888): post active user change for 0
D/KnoxTimeoutHandler(  888): postActiveUserChange for user 0
D/KnoxTimeoutHandler(  888): handleActiveUserChange for user 0
D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
I/SurfaceFlinger(  249): id=15 createSurf (1x1),1 flag=404, com.test.thalitest/com.test.thalitest.MainActivity
D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
I/OpenGLRenderer( 7760): Initialized EGL, version 1.4
I/OpenGLRenderer( 7760): HWUI protection enabled for context ,  &this =0xa1653060 ,&mEglDisplay = 1 , &mEglConfig = 8 
D/OpenGLRenderer( 7760): Enabling debug mode 0
D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
D/InputMethodManagerService(  888): windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
W/ContextImpl(  888): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.android.server.InputMethodManagerService$6.run:2728 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
E/LightSensor(  888): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
D/AutomaticBrightnessController(  888): mCallbacks.updateBrightness()
D/DisplayPowerController(  888): getFinalBrightness : 8 -> 8
I/ActivityManager(  888): Displayed com.test.thalitest/.MainActivity: +584ms
D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
I/SurfaceFlinger(  249): id=8 Removed com.sec.android.app.launcher/com.android.launcher2.Launcher (4/9)
I/SurfaceFlinger(  249): id=8 Removed com.sec.android.app.launcher/com.android.launcher2.Launcher (-2/9)
D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
E/BooksSync( 7687): Soft error
E/BooksSync( 7687): com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
E/BooksSync( 7687): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3DS0HXd4TFLU4&nonce=5775538404416240872&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
E/BooksSync( 7687): Headers suppressed
E/BooksSync( 7687): 
E/BooksSync( 7687): com.google.android.apps.books.net.HttpHelper.wrapExceptionBasedOnStatus(HttpHelper.java:212)
E/BooksSync( 7687): Sync error
E/BooksSync( 7687): com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
E/BooksSync( 7687): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3DS0HXd4TFLU4&nonce=5775538404416240872&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
E/BooksSync( 7687): Headers suppressed
E/BooksSync( 7687): 
E/BooksSync( 7687): com.google.android.apps.books.net.HttpHelper.wrapExceptionBasedOnStatus(HttpHelper.java:212)
I/BooksSync( 7687): Finished books sync
D/ConnectivityService(  888): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/ActivityManager(  888): Killing 6929:com.sec.android.automotive.drivelink/u0a99 (adj 15): bgCount ##41
D/SyncManager(  888): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 63717, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
D/ConnectivityService(  888): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
D/ConnectivityService(  888): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
I/art     (  888): Explicit concurrent mark sweep GC freed 37432(1963KB) AllocSpace objects, 12(582KB) LOS objects, 30% free, 36MB/52MB, paused 1.364ms total 125.913ms
D/SecContentProvider2(  888): uri = 11 selection = getMyKnoxAdmin
D/SecContentProvider2(  888): mCursor = null
W/ContextImpl(  888): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.android.server.InputMethodManagerService$6.run:2728 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
W/libprocessgroup(  888): failed to open /acct/uid_10099/pid_6929/cgroup.procs: No such file or directory
I/Timeline( 7760): Timeline: Activity_idle id: android.os.BinderProxy@a41e024 time:96893
D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
E/LightSensor(  888): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
D/AutomaticBrightnessController(  888): mCallbacks.updateBrightness()
D/DisplayPowerController(  888): getFinalBrightness : 8 -> 8
D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
D/JsMessageQueue( 7760): Set native->JS mode to OnlineEventsBridgeMode
D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
I/SurfaceFlinger(  249): id=14 Removed Starting com.test.thalitest (7/8)
I/SurfaceFlinger(  249): id=14 Removed Starting com.test.thalitest (-2/8)
D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
I/chromium( 7760): [INFO:SkUtilsArm.cpp(179)] Device supports ARM NEON instructions!
I/chromium( 7760): 
D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
D/CustomFrequencyManagerService(  888): acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1958400  uid : 1000  pid : 888  pkgName : ACTIVITY_RESUME_BOOSTER@10
D/CustomFrequencyManagerService(  888): releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1958400  uid : 1000  pid : 888  tag : ACTIVITY_RESUME_BOOSTER@6
D/CustomFrequencyManagerService(  888): FrequencyrequestList.getNextMaxCPUCoreRequest, index: 0
W/ActivityManager(  888): mDVFSHelper.release()
I/Timeline(  888): Timeline: Activity_windows_visible id: ActivityRecord{bfb5867 u0 com.test.thalitest/.MainActivity t11} time:97047
D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
E/Adreno-ES20( 7760): <check_framebuffer_attachment:854>: Invalid texture format! Returning error!
E/Adreno-ES20( 7760): <check_framebuffer_object_status:1237>: Framebuffer color attachment incomplete. Returning GL_FRAMEBUFFER_INCOMPLETE_ATTACHMENT!
D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
E/LightSensor(  888): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 3, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=1, bp1=1, cp1=3, cpl=3202560
D/AutomaticBrightnessController(  888): mCallbacks.updateBrightness()
D/DisplayPowerController(  888): getFinalBrightness : 8 -> 8
,D/jxcore_app_log( 7760): JniHelper::setJavaVM(0xb4f5c280), pthread_self() = -1358541824
,D/JX-Cordova( 7760): jxcore cordova android initializing
,E/LightSensor(  888): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 3, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=1, bp1=1, cp1=3, cpl=3202560
,D/AutomaticBrightnessController(  888): mCallbacks.updateBrightness()
D/DisplayPowerController(  888): getFinalBrightness : 8 -> 8
,D/CustomFrequencyManagerService(  888): releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1958400  uid : 1000  pid : 888  tag : ACTIVITY_RESUME_BOOSTER@10
,E/SMD     (  289): DCD ON
,I/WifiStateMachine(  888): CMD_RSSI_POLL : calculateWifiScore in!
E/LightSensor(  888): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 3, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=1, bp1=1, cp1=3, cpl=3202560
D/AutomaticBrightnessController(  888): mCallbacks.updateBrightness()
I/WifiStateMachine(  888): CMD_RSSI_POLL : calculateWifiScore out!
D/DisplayPowerController(  888): getFinalBrightness : 8 -> 8
I/WifiStateMachine(  888): CMD_RSSI_POLL : out!
,I/GAV2    ( 7687): Thread[GAThread,5,main]: No campaign data found.
,D/StatusBar.NetworkController( 1171): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02012b/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020464/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
D/StatusBar.NetworkController( 1171): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1171): applyOpen
,D/StatusBar.NetworkController( 1171): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1171): applyOpen
D/StatusBar.NetworkController( 1171): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1171): applyOpen
D/StatusBar.NetworkController( 1171): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1171): applyOpen
,E/LightSensor(  888): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 3, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=1, bp1=1, cp1=3, cpl=3202560
,D/AutomaticBrightnessController(  888): mCallbacks.updateBrightness()
D/DisplayPowerController(  888): getFinalBrightness : 8 -> 8
,E/LightSensor(  888): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 3, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=1, bp1=1, cp1=3, cpl=3202560
,D/AutomaticBrightnessController(  888): mCallbacks.updateBrightness()
D/DisplayPowerController(  888): getFinalBrightness : 8 -> 8
,E/LightSensor(  888): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 3, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=1, bp1=1, cp1=3, cpl=3202560
D/AutomaticBrightnessController(  888): mCallbacks.updateBrightness()
D/DisplayPowerController(  888): getFinalBrightness : 8 -> 8
,E/LightSensor(  888): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 3, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=1, bp1=1, cp1=3, cpl=3202560
D/AutomaticBrightnessController(  888): mCallbacks.updateBrightness()
D/DisplayPowerController(  888): getFinalBrightness : 8 -> 8
,E/LightSensor(  888): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 3, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=1, bp1=1, cp1=3, cpl=3202560
,D/AutomaticBrightnessController(  888): mCallbacks.updateBrightness()
D/DisplayPowerController(  888): getFinalBrightness : 8 -> 8
,E/LightSensor(  888): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 3, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=1, bp1=1, cp1=3, cpl=3202560
,D/AutomaticBrightnessController(  888): mCallbacks.updateBrightness()
D/DisplayPowerController(  888): getFinalBrightness : 8 -> 8
,W/jxcore-log( 7760): Initializing JXcore engine
W/jxcore-log( 7760): JXcore engine is ready
,W/jxcore-log( 7760): Starting JXcore engine
,D/SecurityLogAgent:SEDenialService(  888): Got Modify Event and sending Denial Intent foraudit.log
E/auditd  ( 2180): In denial and Property audit_ondenial is set to 1 
,W/ContextImpl(  888): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.android.server.SEDenialService$AuditFileObserver.onEvent:76 android.os.FileObserver$ObserverThread.onEvent:122 android.os.FileObserver$ObserverThread.observe:-2 android.os.FileObserver$ObserverThread.run:85 
D/SecurityLogAgent:SEDenialService(  888): audit.ondenial set to 0 after sending samsung.intent.action.knox.DENIAL_NOTIFICATION intent
D/SecurityLogAgent( 7490):  SeDenialReceiver : Intent Received : samsung.intent.action.knox.DENIAL_NOTIFICATION
D/SecurityLogAgent( 7490):  SeDenialReceiver : File path = null
,E/LightSensor(  888): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 3, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=1, bp1=1, cp1=3, cpl=3202560
,D/AutomaticBrightnessController(  888): mCallbacks.updateBrightness()
D/DisplayPowerController(  888): getFinalBrightness : 8 -> 8
,W/jxcore-log( 7760): Platform android
W/jxcore-log( 7760): 
,W/jxcore-log( 7760): Process ARCH arm
W/jxcore-log( 7760): 
,D/PowerManagerService(  888): [api] release WakeLock flags=0x10000006 tag=PowerUI.Notification uid=10059 pid=1171 (0x0)
,E/LightSensor(  888): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 3, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=1, bp1=1, cp1=3, cpl=3202560
D/AutomaticBrightnessController(  888): mCallbacks.updateBrightness()
D/DisplayPowerController(  888): getFinalBrightness : 8 -> 8
,E/LightSensor(  888): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 3, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=1, bp1=1, cp1=3, cpl=3202560
D/AutomaticBrightnessController(  888): mCallbacks.updateBrightness()
,D/DisplayPowerController(  888): getFinalBrightness : 8 -> 8
,E/LightSensor(  888): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 3, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=1, bp1=1, cp1=3, cpl=3202560
,D/AutomaticBrightnessController(  888): mCallbacks.updateBrightness()
D/DisplayPowerController(  888): getFinalBrightness : 8 -> 8
,I/jxcore-log( 7760): JXcore Cordova bridge is ready!
I/jxcore-log( 7760): 
,W/jxcore-log( 7760): JXcore engine is started
,E/LightSensor(  888): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 3, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=1, bp1=1, cp1=3, cpl=3202560
,D/AutomaticBrightnessController(  888): mCallbacks.updateBrightness()
,D/DisplayPowerController(  888): getFinalBrightness : 8 -> 8
,I/jxcore-log( 7760): Toggling radios to true
I/jxcore-log( 7760): 
,D/BluetoothAdapter( 7760): enable()
,D/BluetoothAdapter( 7760): enable(): BT is already enabled..!
,D/WifiService(  888): New client listening to asynchronous messages
,I/WifiManager( 7760): packageName : com.test.thalitest
,D/SecContentProvider(  888): uri = 18 selection = isWifiEnabled
,D/SecContentProvider2(  888): uri = 20 selection = isWifiStateChangeAllowed
D/SecContentProvider2(  888): mCursor = null
,D/WifiService(  888): setWifiEnabled: true pid=7760, uid=10367
E/WifiService(  888): Invoking mWifiStateMachine.setWifiEnabled
,W/ActivityManager(  888): Permission Denial: getCurrentUser() from pid=7760, uid=10367 requires android.permission.INTERACT_ACROSS_USERS
,W/WifiService(  888): Failed getting userId using ActivityManagerNative
W/WifiService(  888): java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=7760, uid=10367 requires android.permission.INTERACT_ACROSS_USERS
W/WifiService(  888): 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:22619)
W/WifiService(  888): 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2119)
W/WifiService(  888): 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2107)
W/WifiService(  888): 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:223)
W/WifiService(  888): 	at android.os.Binder.execTransact(Binder.java:446)
,D/SettingsProvider(  888): name = wifi_on
,I/WifiService(  888): disconnect: pid=7760, uid=10367
I/wpa_supplicant( 1287): [wpa_supplicant_ctrl_iface_process] : DISCONNECT
I/jxcore-log( 7760): Radios toggled
I/jxcore-log( 7760): 
,I/jxcore-log( 7760): My device name is: samsung-SM-G900F
I/jxcore-log( 7760): 
,I/wpa_supplicant( 1287): CTRL-EVENT-DISCONNECTED bssid=C0.AA.48 reason=3 locally_generated=1
,I/wpa_supplicant( 1287): wlan0: State: COMPLETED -> DISCONNECTED
,I/wpa_supplicant( 1287): CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=C0.AA.48 SSID=4E47373030
I/wpa_supplicant( 1287): wlan0: State: DISCONNECTED -> DISCONNECTED
,E/WifiStateMachine(  888): WifiStateMachine: Leaving Connected state
,I/wpa_supplicant( 1287): reset timer : RESET_TIMER 0
I/wpa_supplicant( 1287): wlan0: Setting scan request: 0 sec 0 usec
I/wpa_supplicant( 1287): Disconnected - do not scan
I/wpa_supplicant( 1287): wlan0: State: DISCONNECTED -> DISCONNECTED
,E/WifiStateMachine(  888): handleNetworkDisconnect: Stopping DHCP and clearing IP stack:handleNetworkDisconnect - access$11200 - exit - invokeExitMethods
E/WifiStateMachine(  888): handleNetworkDisconnect c0:ff:d4:d3:aa:48 config "NG700"WPA_PSK config.bssid any
E/WifiStateMachine(  888): handleNetworkDisconnect "NG700" nid=0
E/WifiConfigStore(  888): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,E/WifiStateMachine(  888): setSuspendOptimizationsNative: 1 true -want true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - stopDhcp - handleNetworkDisconnect
,D/WifiP2pService(  888): InactiveState{ what=143375 }
,D/WifiP2pService(  888): P2pEnabledState{ what=143375 }
,D/StatusBar.NetworkController( 1171): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02012b/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020464/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
,D/CommandListener(  283): Clearing all IP addresses on wlan0
,V/NativeCrypto( 1714): Read error: ssl=0xaeb4de00: I/O error during system call, Connection timed out
,V/NativeCrypto( 1714): SSL shutdown failed: ssl=0xaeb4de00: I/O error during system call, Broken pipe
,E/WifiStateMachine(  888): setDetailed state, old =CONNECTED and new state=DISCONNECTED hidden=false
,E/ConnectivityService(  888): updateNetworkInfo()
,E/WifiConfigStore(  888): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,D/ConnectivityService(  888): NetworkAgentInfo [WIFI () - 502] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
E/ConnectivityService(  888): updateNetworkInfo()
D/ConnectivityService(  888): ignoring duplicate network state non-change
D/ConnectivityService(  888): NetworkAgentInfo [WIFI () - 502] got DISCONNECTED, was satisfying 2
,I/WifiTrafficPoller(  888): evaluateTrafficStatsPolling
,I/CLocInfoService(  888): External Intent Received android.net.wifi.STATE_CHANGE
,D/StatusBar.NetworkController( 1171): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020498/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020133/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020464/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
,D/StatusBar.NetworkController( 1171): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1171): applyOpen
,D/StatusBar.NetworkController( 1171): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1171): applyOpen
D/StatusBar.NetworkController( 1171): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1171): applyOpen
D/ConnectivityService(  888): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/StatusBar.NetworkController( 1171): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1171): applyOpen
,D/ConnectivityService(  888): reportBadNetwork(NetworkAgentInfo [WIFI () - 502]) by 10012
,E/WifiStateMachine(  888): Start Disconnecting Watchdog 1
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  888): ValidatedState{ when=0 what=532488 arg1=10012 target=com.android.internal.util.StateMachine$SmHandler }
D/ConnectivityService(  888): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  888): DefaultState{ when=-3ms what=532488 arg1=10012 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  888): Forcing reevaluation
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  888): EvaluatingState{ when=0 what=532486 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
I/wpa_supplicant( 1287): wlan0: Setting scan request: 0 sec 0 usec
I/wpa_supplicant( 1287): P2P: Current p2p state = IDLE
I/wpa_supplicant( 1287): wlan0: State: DISCONNECTED -> SCANNING
I/wpa_supplicant( 1287): CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00.00.00 SSID=
I/wpa_supplicant( 1287): First Scan Start
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  888): Validated
,D/ConnectivityService(  888): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/wpa_supplicant( 1287): Scan requested (ret=0) - scan timeout 30 seconds
,E/WifiStateMachine(  888): ConnectModeState: Network connection lost 
,E/WifiStateMachine(  888): handleNetworkDisconnect: Stopping DHCP and clearing IP stack:handleNetworkDisconnect - access$11200 - processMessage - processMsg
,E/WifiStateMachine(  888): setSuspendOptimizationsNative: 1 true -want true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - stopDhcp - handleNetworkDisconnect
,D/WifiP2pService(  888): InactiveState{ what=143375 }
D/WifiP2pService(  888): P2pEnabledState{ what=143375 }
,I/Hs20UtilService( 1304): Starting #6
,I/Hs20UtilService( 1304): Message received 5007
,D/NearbySettings( 1304): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
V/NearbySettings( 1304): DMSUtil.isNetworkConnected - flag-null, state-null
D/ConnectivityService(  888): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/NearbySettings( 1304): DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
D/ConnectivityService(  888): returning getNetworkInfo(networkType - 13) :[type: WIFI_P2P[] - WIFI_P2P, state: UNKNOWN/IDLE, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/NearbySettings( 1304): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 1304): DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
I/NearbySettings( 1304): MountReceiver.onReceive - Set preference state off
,V/NearbySettings( 1304): MountReceiver.mPrefHandler - 7002
,D/StatusBar.NetworkController( 1171): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020498/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020133/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020464/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
,E/LightSensor(  888): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 3, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=1, bp1=1, cp1=3, cpl=3202560
,D/AutomaticBrightnessController(  888): mCallbacks.updateBrightness()
D/DisplayPowerController(  888): getFinalBrightness : 8 -> 8
,D/CommandListener(  283): Clearing all IP addresses on wlan0
D/ConnectivityService(  888): notifyType LOST for NetworkAgentInfo [WIFI () - 502]
D/ConnectivityService(  888): calling update connectivity
D/ConnectivityService(  888):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  888):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
,D/ConnectivityService(  888): sending notification LOST for NetworkRequest [ id=2, legacyType=-1, [] ]
,D/ConnectivityManager.CallbackHandler( 1171): CM callback handler got msg 524292
D/EntConnectivity(  888): Not allowed due to - mEnabled false
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  888): ValidatedState{ when=-2ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  888): DefaultState{ when=-2ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  888): Disconnected - quitting
E/WifiStateMachine(  888): setDetailed state, old =DISCONNECTED and new state=DISCONNECTED hidden=false
,D/WifiStateMachine(  888): updateConfiguredNetworkExpiration - currTime: 1452525635724
D/WifiStateMachine(  888): updateConfiguredNetworkExpiration - AP, "NG700", is not shared AP.
,D/Nat464Xlat(  888): requiresClat: netType=1, connected=false, hasIPv4Address=true
E/WifiStateMachine(  888): SUPPLICANT_STATE_CHANGE_EVENT state=DISCONNECTED -> state= DISCONNECTED debouncing=false
I/WifiTrafficPoller(  888): evaluateTrafficStatsPolling
E/WifiStateMachine(  888): setDetailed state, old =DISCONNECTED and new state=DISCONNECTED hidden=false
D/ConnectivityService(  888): Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  888): sending new Min Network Score(0): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,E/WifiStateMachine(  888): Link configuration changed for netId: -1 old: {LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0} new: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0}
D/CSLegacyTypeTracker(  888): Removing agent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{502}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::ee1f:72ff:fe18:8b78/64,192.168.1.135/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{true} created{true} explicitlySelected{false} }
E/WifiStateMachine(  888): updateLinkProperties nid: -1 state: DISCONNECTED reason: CMD_UPDATE_LINKPROPERTIES
D/CSLegacyTypeTracker(  888): Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 502] isDefaultNetwork=false
I/CLocInfoService(  888): External Intent Received android.net.wifi.STATE_CHANGE
,D/TelephonyNetworkFactory( 1459): Cellular needs Network for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
E/WifiStateMachine(  888): Link configuration changed for netId: -1 old: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576} new: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0}
E/WifiStateMachine(  888): updateLinkProperties nid: -1 state: DISCONNECTED reason: CMD_UPDATE_LINKPROPERTIES
,D/WifiNetworkAgent(  888): NetworkAgent: NetworkAgent channel lost
D/ConnectivityService(  888): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,D/StatusBar.NetworkController( 1171): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020498/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020133/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020464/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
,E/WifiStateMachine(  888): SUPPLICANT_STATE_CHANGE_EVENT state=SCANNING -> state= SCANNING debouncing=false
E/WifiStateMachine(  888): setDetailed state, old =DISCONNECTED and new state=SCANNING hidden=false
,E/WifiStateMachine(  888): setDetailed state send new extra info"NG700"
,D/SecContentProvider2(  888): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2(  888): mCursor = null
,D/ConnectivityService(  888): sendStickyBroadcastDelayed: delayMs=500, action=android.net.conn.CONNECTIVITY_CHANGE
,D/SmartBondingService(  888): SmartBondingReceiver: onReceive action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,V/NetworkStats(  888): updateIfacesLocked()
D/SmartBondingService(  888): EVENT_UPDATE_SB_STATE called / mDisableBySIOP false
,V/NetworkStats(  888): performPollLocked(flags=0x1)
D/NtpTrustedTime(  888): currentTimeMillis() cache hit
D/SmartBondingService(  888): getSBEnabled() enabled =false
D/SmartBondingService(  888): getSBEnabled() enabled =false
D/SmartBondingService(  888): getSBEnabled() enabled =false
D/ConnectivityService(  888): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/StatusBar.NetworkController( 1171): getUpdateDataNetType(): 0
D/StatusBar.NetworkController( 1171): updateDataNetType()
D/StatusBar.NetworkController( 1171): NoService, mRoamingIconId = 0
,D/NetworkStatsFactory(  888): UpdateStatsForKnox
,D/ConnectivityService(  888): returning getNetworkInfo(networkType - 28) :[type: MOBILE_ENT1[] - MOBILE_ENT1, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/NtpTrustedTime(  888): currentTimeMillis() cache hit
,E/ConnectivityService(  888): EVENT_NETWORK_VALIDATED - isLiveNetworkAgent found mismatched netId: null - NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{502}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::ee1f:72ff:fe18:8b78/64,192.168.1.135/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{true} created{true} explicitlySelected{false} }
,V/NetworkStats(  888): performPollLocked() took 6ms
D/SmartBondingService(  888): getNetworkEnabled : wifi : true mobile : true
,D/NtpTrustedTime(  888): currentTimeMillis() cache hit
,D/SecContentProvider2(  888): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2(  888): mCursor = null
,D/NtpTrustedTime(  888): currentTimeMillis() cache hit
D/NtpTrustedTime(  888): currentTimeMillis() cache hit
V/NetworkStats(  888): advisePersistThreshold() given 9223372036854775, clamped to 2097152
D/NtpTrustedTime(  888): currentTimeMillis() cache hit
,D/StatusBar.NetworkController( 1171): updateDataIcon, mDataDirectionIconId = (null) mDataConnected = false
D/StatusBar.NetworkController( 1171): updateTelephonySignalStrength: hasService=false ss=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte
,D/StatusBar.NetworkController( 1171): updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal
,D/NtpTrustedTime(  888): currentTimeMillis() cache hit
D/NtpTrustedTime(  888): currentTimeMillis() cache hit
D/StatusBar.NetworkController( 1171): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020498/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020133/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020464/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
D/StatusBar.NetworkController( 1171): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1171): applyOpen
D/StatusBar.NetworkController( 1171): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1171): applyOpen
D/StatusBar.NetworkController( 1171): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1171): applyOpen
D/StatusBar.NetworkController( 1171): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1171): applyOpen
,I/Hs20UtilService( 1304): Starting #7
,I/Hs20UtilService( 1304): Message received 5007
,D/NearbySettings( 1304): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,V/NearbySettings( 1304): DMSUtil.isNetworkConnected - flag-null, state-null
D/ConnectivityService(  888): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/NearbySettings( 1304): DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
D/ConnectivityService(  888): returning getNetworkInfo(networkType - 13) :[type: WIFI_P2P[] - WIFI_P2P, state: UNKNOWN/IDLE, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/NearbySettings( 1304): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 1304): DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
,I/NearbySettings( 1304): MountReceiver.onReceive - Set preference state off
,V/NearbySettings( 1304): MountReceiver.mPrefHandler - 7002
,D/SSRM:m  (  888): SIOP:: AP = 370, PST = 419, CUR = 300
,D/FileWriteThread_Telephony( 1459): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 1459): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 1459): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 1459): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 1459): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 1459): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 1459): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 1459): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 1459): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 1459): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 1459): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 1459): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 1459): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 1459): FileWriteThread : threadType = 3
,E/LightSensor(  888): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 3, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=1, bp1=1, cp1=3, cpl=3202560
,D/AutomaticBrightnessController(  888): mCallbacks.updateBrightness()
D/DisplayPowerController(  888): getFinalBrightness : 8 -> 8
,V/AlarmManager(  888): waitForAlarm result :4
,E/LightSensor(  888): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 3, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=1, bp1=1, cp1=3, cpl=3202560
,D/AutomaticBrightnessController(  888): mCallbacks.updateBrightness()
D/DisplayPowerController(  888): getFinalBrightness : 8 -> 8
,V/GLSActivity( 1714): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1714): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
,I/GLSUser ( 1714): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1714): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1714): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1714): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/Finsky  ( 6627): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,D/Finsky  ( 6627): [1] 5.onFinished: Installation state replication failed.
D/Finsky  ( 6627): [1] 5.onFinished: Scheduling replication attempt 2.
,E/LightSensor(  888): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 3, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=1, bp1=1, cp1=3, cpl=3202560
,D/AutomaticBrightnessController(  888): mCallbacks.updateBrightness()
D/DisplayPowerController(  888): getFinalBrightness : 8 -> 8
,D/ConnectivityService(  888): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/Tethering(  888): MasterInitialState.processMessage what=3
,D/ConnectivityService(  888): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/ApplicationPolicy(  888): updateDataUsageMap
,D/ConnectivityService(  888): returning getNetworkInfo(networkType - 0) :[type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  888): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/ActivityManager(  888): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  888): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  888): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  888): checkUser: useridlist=null, currentuser=0
,D/accuweather( 2029): [KK AccuPhone]>>> SWW:66 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,D/ConnectivityService(  888): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  888): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  888): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SmartBondingService(  888): SmartBondingReceiver: onReceive action=android.net.conn.CONNECTIVITY_CHANGE
,D/ConnectivityService(  888): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/SmartBondingService(  888): EVENT_UPDATE_SB_STATE called / mDisableBySIOP false
,D/SmartBondingService(  888): getSBEnabled() enabled =false
D/SmartBondingService(  888): getSBEnabled() enabled =false
D/SmartBondingService(  888): getSBEnabled() enabled =false
,E/Zygote  ( 7858): MountEmulatedStorage()
I/libpersona( 7858): KNOX_SDCARD checking this for 1000
E/Zygote  ( 7858): v2
I/libpersona( 7858): KNOX_SDCARD not a persona
,I/CLocInfoService(  888): External Intent Received android.net.conn.CONNECTIVITY_CHANGE
,D/ConnectivityService(  888): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/CLocInfoService(  888): CLoinfo wifi false
I/ActivityManager(  888): Start proc com.sec.pcw.device for broadcast com.sec.pcw.device/.receiver.SYSTEMReceiver: pid=7858 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,W/SLocation(  888): No Active Data Connection
,I/DBG_DM  ( 3767): [com.wssyncmldm.XDMService(1111/IlIlllIIlIlIIIlIlIll)] WiFi network Connected : false
,I/SELinux ( 7858): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,D/ConnectivityService(  888): returning getNetworkInfo(networkType - 7) :[type: BLUETOOTH[] - BLUETOOTH, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SmartBondingService(  888): getNetworkEnabled : wifi : true mobile : true
,I/SELinux ( 7858): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
I/DBG_DM  ( 3767): [com.wssyncmldm.XDMService(1125/lllllIlIlIIIIIIIIlIl)] Bluetooth Data Connected : false
,E/SELinux ( 7858): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 7858): TimaSignature is unavailable
,D/ActivityThread( 7858): Added TimaKeyStore provider
,D/ResourcesManager( 7858): creating new AssetManager and set to /system/priv-app/PCWClientS18/PCWClientS18.apk
,I/PCWCLIENTTRACE_LOG( 7858): DEFAULT_LOGON : true
I/PCWCLIENTTRACE_LOG( 7858): DEFAULT_LOGLEVEL : 3
I/PCWCLIENTTRACE_DMDBOpenHelper( 7858): new DMDBOpenHelper instance
,I/PCWCLIENTTRACE_PushUtil( 7858): SPPPushClient is installed : true
I/PCWCLIENTTRACE_PushUtil( 7858): sales region : global
I/PCWCLIENTTRACE_PushUtil( 7858): getPushTypeList : [SPP, GCM]
I/PCWCLIENTTRACE_SYSTEMReceiver( 7858): [onReceive] - android.net.conn.CONNECTIVITY_CHANGE
,I/PCWCLIENTTRACE_SYSTEMReceiver( 7858): noConnectivity : true
,E/ActivityManager(  888): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  888): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  888): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  888): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 7878): MountEmulatedStorage()
E/Zygote  ( 7878): v2
I/libpersona( 7878): KNOX_SDCARD checking this for 10126
I/libpersona( 7878): KNOX_SDCARD not a persona
,I/ActivityManager(  888): Start proc com.google.android.music:main for broadcast com.google.android.music/.homewidgets.IFLWidgetProvider: pid=7878 uid=10126 gids={50126, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  888): Killing 6992:com.sec.android.provider.logsprovider/u0a20 (adj 15): bgCount ##41
,I/SELinux ( 7878): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
I/SELinux ( 7878): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
E/SELinux ( 7878): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,E/LightSensor(  888): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 3, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=1, bp1=1, cp1=3, cpl=3202560
,D/AutomaticBrightnessController(  888): mCallbacks.updateBrightness()
D/DisplayPowerController(  888): getFinalBrightness : 8 -> 8
,D/TimaKeyStoreProvider( 7878): TimaSignature is unavailable
,D/ActivityThread( 7878): Added TimaKeyStore provider
,D/ResourcesManager( 7878): creating new AssetManager and set to /system/app/Music2/Music2.apk
,E/SMD     (  289): DCD ON
,W/libprocessgroup(  888): failed to open /acct/uid_10020/pid_6992/cgroup.procs: No such file or directory
,I/MusicStore( 7878): Database version: 104
,E/LightSensor(  888): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 3, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=1, bp1=1, cp1=3, cpl=3202560
,D/AutomaticBrightnessController(  888): mCallbacks.updateBrightness()
D/DisplayPowerController(  888): getFinalBrightness : 8 -> 8
,D/ResourcesManager( 7878): creating new AssetManager and set to /data/app/com.google.android.gms-1/base.apk
,W/ResourcesManager( 7878): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 7878): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,V/JNIHelp ( 7878): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
,W/ActivityThread( 7878): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,W/System  ( 7878): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@1f8bdc7f: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 7878): Installed default security provider GmsCore_OpenSSL
,D/AndroidMusic( 7878): GMSCore installation verified
,I/ConfigStore( 7878): Config Database version: 1
,E/Vold    (  248): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.music/files/
W/Vold    (  248): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7878): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.music/files
,I/wpa_supplicant( 1287): nl80211: Received scan results (3 BSSes)
,I/wpa_supplicant( 1287): wlan0: Setting scan request: 8 sec 0 usec
,I/wpa_supplicant( 1287): Trying to associate with C0.AA.48 (SSID='4E47373030' freq=2412 MHz)
I/wpa_supplicant( 1287): wlan0: State: SCANNING -> ASSOCIATING
I/wpa_supplicant( 1287): CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00.00.00 SSID=
,E/WifiStateMachine(  888): [1,452,525,636,761 ms] noteScanEnd no scan source
,E/WifiStateMachine(  888): wifi setScanResults statecom.android.server.wifi.WifiStateMachine$DisconnectedState@220a77a2 sup_state=SCANNING debouncing=false
,E/LightSensor(  888): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 3, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=1, bp1=1, cp1=3, cpl=3202560
,D/AutomaticBrightnessController(  888): mCallbacks.updateBrightness()
D/DisplayPowerController(  888): getFinalBrightness : 8 -> 8
,I/CLocInfoService(  888): External Intent Received android.net.wifi.SCAN_RESULTS
,E/WifiStateMachine(  888): SUPPLICANT_STATE_CHANGE_EVENT state=ASSOCIATING -> state= CONNECTING debouncing=false
E/WifiStateMachine(  888): setDetailed state, old =SCANNING and new state=CONNECTING hidden=false
E/WifiStateMachine(  888): setDetailed state send new extra info0x
,D/SecContentProvider2(  888): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2(  888): mCursor = null
,E/Vold    (  248): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.music/files/
W/Vold    (  248): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7878): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.music/files
,E/Vold    (  248): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.music/files/
W/Vold    (  248): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7878): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.music/files
,D/WifiDisplayAdapter(  888): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,D/WifiDisplayAdapter(  888): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,V/AudioPolicyManager(  303): getOutputsForDevice device 0002 -> 0002
,I/AudioService(  888): getStreamVolume 3 index 70
,I/MediaRouter( 7878): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=7, volumeMax=15, presentationDisplayId=-1, extras=null, providerPackageName=android }
,E/ActivityManager(  888): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  888): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  888): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  888): checkUser: useridlist=null, currentuser=0
,I/wpa_supplicant( 1287): wlan0: State: ASSOCIATING -> ASSOCIATED
I/wpa_supplicant( 1287): CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00.00.00 SSID=4E47373030
,I/wpa_supplicant( 1287): Associated with C0.AA.48
,E/WifiStateMachine(  888): SUPPLICANT_STATE_CHANGE_EVENT state=ASSOCIATED -> state= CONNECTING debouncing=false
E/WifiStateMachine(  888): setDetailed state, old =CONNECTING and new state=CONNECTING hidden=false
,D/SecContentProvider2(  888): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2(  888): mCursor = null
,E/Zygote  ( 7908): MountEmulatedStorage()
E/Zygote  ( 7908): v2
I/libpersona( 7908): KNOX_SDCARD checking this for 1000
I/libpersona( 7908): KNOX_SDCARD not a persona
,I/ActivityManager(  888): Start proc com.sec.android.diagmonagent for broadcast com.sec.android.diagmonagent/.DiagMonRegistrationReceiver: pid=7908 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,I/wpa_supplicant( 1287): wlan0: State: ASSOCIATED -> 4WAY_HANDSHAKE
I/wpa_supplicant( 1287): CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=C0.AA.48 SSID=4E47373030
,E/WifiStateMachine(  888): SUPPLICANT_STATE_CHANGE_EVENT state=FOUR_WAY_HANDSHAKE -> state= AUTHENTICATING debouncing=false
E/WifiStateMachine(  888): setDetailed state, old =CONNECTING and new state=AUTHENTICATING hidden=false
,E/WifiStateMachine(  888): setDetailed state send new extra info"NG700"
,D/SecContentProvider2(  888): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2(  888): mCursor = null
,I/wpa_supplicant( 1287): wlan0: State: 4WAY_HANDSHAKE -> 4WAY_HANDSHAKE
,I/wpa_supplicant( 1287): wlan0: State: 4WAY_HANDSHAKE -> GROUP_HANDSHAKE
I/wpa_supplicant( 1287): CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=C0.AA.48 SSID=4E47373030
,I/wpa_supplicant( 1287): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
I/wpa_supplicant( 1287): wlan0: State: GROUP_HANDSHAKE -> COMPLETED
I/wpa_supplicant( 1287): CTRL-EVENT-CONNECTED - Connection to C0.AA.48 completed (auth) [id=0 id_str=]
,I/wpa_supplicant( 1287): Blacklist: Clear (temp) 
I/wpa_supplicant( 1287): CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=C0.AA.48 SSID=4E47373030
,E/WifiStateMachine(  888): SUPPLICANT_STATE_CHANGE_EVENT state=GROUP_HANDSHAKE -> state= AUTHENTICATING debouncing=false
E/WifiStateMachine(  888): setDetailed state, old =AUTHENTICATING and new state=AUTHENTICATING hidden=false
,E/WifiStateMachine(  888): Network connection established
,D/WifiNative-HAL(  888): callSECApiVoid - ID [50]
,E/WifiStateMachine(  888): setDetailed state, old =AUTHENTICATING and new state=OBTAINING_IPADDR hidden=false
,I/SELinux ( 7908): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
D/WifiDisplayAdapter(  888): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,I/SELinux ( 7908): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 7908): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,E/WifiStateMachine(  888): setDetailed state, old =OBTAINING_IPADDR and new state=CONNECTING hidden=false
,I/CLocInfoService(  888): External Intent Received android.net.wifi.STATE_CHANGE
,D/StatusBar.NetworkController( 1171): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020498/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020133/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020464/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
,D/ConnectivityService(  888): registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{false} explicitlySelected{false} }
,E/WifiStateMachine(  888): L2ConnectedState c0:ff:d4:d3:aa:48 config "NG700"WPA_PSK config.bssid any
,D/ConnectivityService(  888): Got NetworkAgent Messenger
D/ConnectivityService(  888): hsengiv:checkWhatTypeOfNetwork and the value is false
E/ConnectivityService(  888): updateNetworkInfo()
D/ConnectivityService(  888): NetworkAgentInfo [WIFI () - 503] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
,D/ConnectivityService(  888): NetworkAgent connected
E/WifiStateMachine(  888): L2ConnectedState "NG700" nid=0
E/WifiConfigStore(  888): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
D/TimaKeyStoreProvider( 7908): TimaSignature is unavailable
,D/ActivityThread( 7908): Added TimaKeyStore provider
,D/ConnectivityService(  888): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/NetworkMonitor( 7878): type=WIFI subType= reason=null isConnected=false
,E/WifiStateMachine(  888): enter ObtainingIpState netId=0 "NG700"WPA_PSK  roam=0 static=false watchdog= 1
,E/WifiStateMachine(  888): ObtainingIpAddress c0:ff:d4:d3:aa:48 config "NG700"WPA_PSK config.bssid any
E/WifiStateMachine(  888): ObtainingIpAddress "NG700" nid=0
E/WifiConfigStore(  888): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,I/ActivityManager(  888): Killing 7000:com.samsung.android.intelligenceservice/u0a3 (adj 15): bgCount ##41
,D/CommandListener(  283): Setting iface cfg
,E/WifiStateMachine(  888): Start Dhcp Watchdog 2
,D/SecContentProvider2(  888): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2(  888): mCursor = null
,I/WifiStateMachine(  888): CMD_RSSI_POLL : calculateWifiScore in!
,E/WifiStateMachine(  888): calculateWifiScore() report new score 60
,I/WifiStateMachine(  888): calculateWifiScore : sendNetworkScore in!
I/WifiStateMachine(  888): calculateWifiScore : sendNetworkScore out!
I/WifiStateMachine(  888): CMD_RSSI_POLL : calculateWifiScore out!
I/WifiStateMachine(  888): CMD_RSSI_POLL : out!
,E/LightSensor(  888): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 3, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=1, bp1=1, cp1=3, cpl=3202560
,D/AutomaticBrightnessController(  888): mCallbacks.updateBrightness()
D/DisplayPowerController(  888): getFinalBrightness : 8 -> 8
,D/ConnectivityService(  888): updateNetworkScore for NetworkAgentInfo [WIFI () - 503] to 60
E/WifiStateMachine(  888): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576} new: {InterfaceName: wlan0 LinkAddresses: []  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0}
,D/ConnectivityService(  888): Update of LinkProperties for NetworkAgentInfo [WIFI () - 503]; created=false
E/WifiStateMachine(  888): updateLinkProperties nid: 0 state: CONNECTING reason: CMD_UPDATE_LINKPROPERTIES
,D/ResourcesManager( 7908): creating new AssetManager and set to /system/priv-app/DiagMonAgent/DiagMonAgent.apk
,I/DIAGMON_AGENT( 7908): [com.sec.android.diagmonagent.DiagMonAgentApplication(41/onCreate)] myUserId : 0
,I/DIAGMON_AGENT( 7908): [com.diagmondm.db.file.XDB(374/llIlIIIIlIIIIIlIlIII)] 
,W/libprocessgroup(  888): failed to open /acct/uid_10003/pid_7000/cgroup.procs: No such file or directory
,E/WifiStateMachine(  888): setSuspendOptimizationsNative: 1 false -want true stack:setSuspendOptimizationsNative - handlePreDhcpSetup - processMessage - processMsg
E/native  (  888): do suspend false
,D/SecContentProvider2(  888): uri = 20 selection = getPromptCredentialsEnabled
D/WifiP2pService(  888): InactiveState{ what=143375 }
,D/WifiP2pService(  888): P2pEnabledState{ what=143375 }
D/SecContentProvider2(  888): mCursor = null
,I/DIAGMON_AGENT( 7908): [com.sec.android.diagmonagent.DiagMonAgentApplication(61/onCreate)] nStatus : 0
,I/DIAGMON_AGENT( 7908): [com.sec.android.diagmonagent.DiagMonAgentApplication(78/onCreate)] DiagMon DM Application Start !
,I/DIAGMON_AGENT( 7908): [lIIllllllllIlIlIllll(17/llIIIIlllllIIllIIllI)] Receive broadcast: android.net.conn.CONNECTIVITY_CHANGE
,I/DIAGMON_AGENT( 7908): [lIIllllllllIlIlIllll(31/llIIIIlllllIIllIIllI)] Running with RegistrationReceiver
,E/LightSensor(  888): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 3, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=1, bp1=1, cp1=3, cpl=3202560
,D/AutomaticBrightnessController(  888): mCallbacks.updateBrightness()
D/DisplayPowerController(  888): getFinalBrightness : 8 -> 8
,I/FOTA_Client( 7345): [com.sec.android.fotaclient.FotaRegisterReceiver(113/onReceive)] Already device registered...
,I/FOTA_Client( 7345): [com.sec.android.fotaclient.FotaUpdaterReceiver(103/onReceive)] Auto update settings is activated
,I/FOTA_Client( 7345): [lllllllllllIlllllIIl(197/lllIlIlIIIllIIlIllIl)] Polling time is vaild
,I/FOTA_Client( 7345): [com.sec.android.fotaclient.FotaUpdaterReceiver(126/onReceive)] Heartbeat settings is activated.
,I/FOTA_Client( 7345): [llIlIIIIlllIlllllIll(125/llIlIIIIlIIIIIlIlIII)] heartbeat time is vaild
,I/KLMS-2.4.503: ( 7386): KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,I/KLMS-2.4.503: ( 7386): MainReciver(): EventNotificationReciver- method called: AppActivityListner onReceive for Intent Action : android.net.conn.CONNECTIVITY_CHANGE , timestamp: 1452525637222
,I/KLMS-2.4.503: ( 7386): MainReciver(): NETWORK_STATE_CHANGED_ACTION
,D/ConnectivityService(  888): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  888): returning getNetworkInfo(networkType - 0) :[type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/KLMS-2.4.503: ( 7386): KLMSUtility(): isNetworkAvailable() - WIFI : false| MOBILE : false
,I/KLMS-2.4.503: ( 7386): StateImplV2(): networkChangeListener().END
,I/ActivityManager(  888): Killing 7022:com.samsung.android.app.filterinstaller/1000 (adj 15): bgCount ##41
,E/dhcpcd  ( 7936): fopen `/system/etc/dhcpcd/dhcpcd.conf': No such file or directory
,I/SO_AGENT( 7403): [com.sec.android.soagent.RegisterReceiver(98/onReceive)] Network is not available
,E/ActivityManager(  888): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  888): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  888): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  888): checkUser: useridlist=null, currentuser=0
,I/dhcpcd  ( 7936): version 5.5.6 starting
,E/dhcpcd  ( 7936): fopen `/system/etc/dhcpcd/dhcpcd.conf': No such file or directory
,E/Zygote  ( 7938): MountEmulatedStorage()
,E/Zygote  ( 7938): v2
I/libpersona( 7938): KNOX_SDCARD checking this for 1000
I/libpersona( 7938): KNOX_SDCARD not a persona
,I/ActivityManager(  888): Start proc com.policydm for broadcast com.policydm/.XDMBroadcastReceiver: pid=7938 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,E/LightSensor(  888): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 3, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=1, bp1=1, cp1=3, cpl=3202560
,D/AutomaticBrightnessController(  888): mCallbacks.updateBrightness()
D/DisplayPowerController(  888): getFinalBrightness : 8 -> 8
W/libprocessgroup(  888): failed to open /acct/uid_1000/pid_7022/cgroup.procs: No such file or directory
,I/dhcpcd  ( 7936): wlan0: sending IPv6 Router Solicitation
,E/dhcpcd  ( 7936): wlan0: sendmsg: Cannot assign requested address
I/dhcpcd  ( 7936): if(wlan0) info get Success. (MAC : C0.AA.48)
I/dhcpcd  ( 7936): bssid match
,I/dhcpcd  ( 7936): wlan0: rebinding lease of 192.168.1.135
,I/SELinux ( 7938): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 7938): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
E/SELinux ( 7938): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 7938): TimaSignature is unavailable
,D/ActivityThread( 7938): Added TimaKeyStore provider
,D/ResourcesManager( 7938): creating new AssetManager and set to /system/priv-app/SPDClient/SPDClient.apk
,D/ConnectivityService(  888): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  888): returning getNetworkInfo(networkType - 0) :[type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/ActivityManager(  888): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  888): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  888): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  888): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 7969): MountEmulatedStorage()
E/Zygote  ( 7969): v2
I/libpersona( 7969): KNOX_SDCARD checking this for 10038
I/libpersona( 7969): KNOX_SDCARD not a persona
,I/ActivityManager(  888): Start proc com.sec.spp.push for broadcast com.sec.spp.push/.monitor.SystemStateMoniter: pid=7969 uid=10038 gids={50038, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  888): Killing 7040:com.samsung.android.app.watchmanagerstub/u0a112 (adj 15): bgCount ##41
,E/LightSensor(  888): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 3, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=1, bp1=1, cp1=3, cpl=3202560
D/AutomaticBrightnessController(  888): mCallbacks.updateBrightness()
,D/DisplayPowerController(  888): getFinalBrightness : 8 -> 8
,I/SELinux ( 7969): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 7969): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 7969): [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
,D/ConnectivityService(  888): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  888): returning getNetworkInfo(networkType - 0) :[type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/TimaKeyStoreProvider( 7969): TimaSignature is unavailable
,D/ActivityThread( 7969): Added TimaKeyStore provider
,W/libprocessgroup(  888): failed to open /acct/uid_10112/pid_7040/cgroup.procs: No such file or directory
,D/ResourcesManager( 7969): creating new AssetManager and set to /system/priv-app/SPPPushClient_Prod/SPPPushClient_Prod.apk
,E/SPPClientService( 7969): ============PushLog. commonIsShipBuild. stop!
,E/SPPClientService( 7969): [PushClientApplication] Push log off : This is Ship build version
,D/SPPClientService( 7969): PushLog.txt file is not deleted.
,D/SPPClientService( 7969): PushLog.txt file is not deleted.
D/SPPClientService( 7969): ============PushLog. stop!
,E/SPPClientService( 7969): [[SystemStateMoniter]] SystemStateMonitorService : noConnect? : true
,I/SA      ( 6781): [OR] onReceive log=[SA = 2.1.0142 V = 21 HWD = 1920X1080 3.0 dpi = 480  SIZE = 2 LOCALE = en_US CSC = DBT MCC = 0 MNC 0 T = user DEVICE = klte P = kltexx I = LRX21T M = SM-G900F OKLEFT false DIS LRX21T.G900FXXU1BOD3 PSS = 5.219788042639568  ]
,I/SA      ( 6781): [OR] onReceive Intent=[ conn.CONNECTIVITY_CHANGE. networkInfo:[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] networkType:1 inetCondition:0 extraInfo:? noConnectivity:true ]
,I/SA      ( 6781): [OR] == ACTION_CONNECTIVITY_CHANGE ==
,I/SA      ( 6781): [SLFUCHKMGR] constructor called
,I/SA      ( 6781): [TPMU]  strSIMState 	:SIM_STATE_UNKNOWN
I/SA      ( 6781): [OR] == isSIMCardReady false ==
,I/SA      ( 6781): [SCU] == networkStateCheck == false
I/SA      ( 6781): [OR] onReceive END
,E/SPPClientService( 7969): [[SystemStateMonitorService]] No Active Internet
,D/accuweather( 7369): [KK AccuPhone]>>> WC:30 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,D/accuweather( 7369): [KK AccuPhone]>>> UIMEM:106 [0:0] The widget does not exist in idle!!
,E/ActivityManager(  888): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  888): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  888): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  888): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 7988): MountEmulatedStorage()
,E/Zygote  ( 7988): v2
I/libpersona( 7988): KNOX_SDCARD checking this for 1000
I/libpersona( 7988): KNOX_SDCARD not a persona
,I/ActivityManager(  888): Start proc com.sec.knox.bridge for broadcast com.sec.knox.bridge/.knoxusage.KnoxUsageReceiver: pid=7988 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,I/SELinux ( 7988): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
D/AutomaticBrightnessController(  888): mCallbacks.updateBrightness()
E/LightSensor(  888): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 3, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=1, bp1=1, cp1=3, cpl=3202560
D/DisplayPowerController(  888): getFinalBrightness : 8 -> 8
,I/ActivityManager(  888): Killing 7058:com.samsung.android.magazine.service/u0a118 (adj 15): bgCount ##41
,I/SELinux ( 7988): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 7988): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 7988): TimaSignature is unavailable
,D/ActivityThread( 7988): Added TimaKeyStore provider
,D/ResourcesManager( 7988): creating new AssetManager and set to /system/app/Bridge/Bridge.apk
,W/ResourcesManager( 7988): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,I/KnoxUsageLogPro( 7988): KnoxUsageReceiver onReceive :android.net.conn.CONNECTIVITY_CHANGE myUserId=0
,I/KnoxUsageLogPro( 7988): premStatus:2
,I/KnoxUsageLogPro( 7988): isEulaShown : false
,I/KnoxUsageLogPro( 7988): KnoxUsageReceiver onReceive : not Processible, just return
,E/ActivityManager(  888): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  888): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  888): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  888): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 8003): MountEmulatedStorage()
,E/Zygote  ( 8003): v2
I/libpersona( 8003): KNOX_SDCARD checking this for 10086
I/libpersona( 8003): KNOX_SDCARD not a persona
,I/ActivityManager(  888): Start proc com.sec.chaton for broadcast com.sec.chaton/.receiver.NetStateReceiver: pid=8003 uid=10086 gids={50086, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  888): Killing 7089:com.samsung.helphub/1000 (adj 15): bgCount ##41
,I/SELinux ( 8003): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
I/SELinux ( 8003): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
E/SELinux ( 8003): [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
,W/libprocessgroup(  888): failed to open /acct/uid_10118/pid_7058/cgroup.procs: No such file or directory
,D/TimaKeyStoreProvider( 8003): TimaSignature is unavailable
,D/ActivityThread( 8003): Added TimaKeyStore provider
,W/libprocessgroup(  888): failed to open /acct/uid_1000/pid_7089/cgroup.procs: No such file or directory
,D/ResourcesManager( 8003): creating new AssetManager and set to /system/app/ChatON_MARKET/ChatON_MARKET.apk
,W/ResourcesManager( 8003): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,E/LightSensor(  888): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 3, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=1, bp1=1, cp1=3, cpl=3202560
,D/AutomaticBrightnessController(  888): mCallbacks.updateBrightness()
D/DisplayPowerController(  888): getFinalBrightness : 8 -> 8
,D/PushModule( 8003): [PushClientApplication] (main) PushClientApplication.onCreate()
,I/PushModule( 8003): [PushClientApplication] (main) PushModule version: 0.9.01.12
D/PushModule( 8003): [PushClientApplication] (main) Discovered public push client. disable in app push client.
,D/ChatON  ( 8003): [1][isApplicationInstalled] com.android.mms was installed
,W/ContextImpl( 8003): Implicit intents with startService are not safe: Intent { act=com.sec.chaton.push.PUSH_CLIENT_SERVICE_ACTION } android.content.ContextWrapper.startService:533 com.sec.chaton.global.GlobalApplication.onCreate:358 android.app.Instrumentation.callApplicationOnCreate:1020 
,W/ActivityManager(  888): Unable to start service Intent { act=com.sec.chaton.push.PUSH_CLIENT_SERVICE_ACTION } U=0: not found
,D/ChatON  ( 8003): [1][a] ChatONV isn't installed.
D/ChatON  ( 8003): [1][a] ChatONVPlugIn.isAvailable()
,E/ActivityManager(  888): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  888): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  888): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  888): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 8022): MountEmulatedStorage()
,E/Zygote  ( 8022): v2
I/libpersona( 8022): KNOX_SDCARD checking this for 10088
I/libpersona( 8022): KNOX_SDCARD not a persona
,I/ActivityManager(  888): Start proc com.android.chrome for broadcast com.android.chrome/com.google.android.apps.chrome.precache.PrecacheServiceLauncher: pid=8022 uid=10088 gids={50088, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  888): Killing 7127:com.sec.kidsplat.installer/u0a166 (adj 15): bgCount ##41
,I/SELinux ( 8022): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 8022): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 8022): [DEBUG] get_category: variable seinfo: chrome sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 8022): TimaSignature is unavailable
,D/ActivityThread( 8022): Added TimaKeyStore provider
,W/libprocessgroup(  888): failed to open /acct/uid_10166/pid_7127/cgroup.procs: No such file or directory
,D/ResourcesManager( 8022): creating new AssetManager and set to /system/app/Chrome/Chrome.apk
,E/LightSensor(  888): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 3, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=1, bp1=1, cp1=3, cpl=3202560
D/AutomaticBrightnessController(  888): mCallbacks.updateBrightness()
D/DisplayPowerController(  888): getFinalBrightness : 8 -> 8
,I/ActivityManager(  888): Killing 6664:com.google.android.gms:car/u0a12 (adj 15): bgCount ##41
,D/Headlines( 5517): HeadlinesSystemBroadcastReceiver onReceive android.net.conn.CONNECTIVITY_CHANGE
,D/HeadlinesChannelUtil( 5517): getCountryCode(): countryCode = DE
,D/Headlines( 5517): Breath.onStartCommand : com.samsung.android.internal.headlines.UPDATE_WELCOME_CARD flag : 0
,D/HeadlinesCardManager( 5517): updateCategory : HeadlinesCardManager:updateCategory() category size == 0
,D/HeadlinesCardManager( 5517): updateCategory : HeadlinesCardManager:updateCategory() try to query category list
D/Headlines( 5517): queryCategory.  mRequest is not initialized.
D/HeadlinesCardManager( 5517): updateCategory : HeadlinesCardManager:updateCategory() reponse : false
D/HeadlinesCardManager( 5517): requestUpdateNewsWelcomeCard : request update welcome card to content card.
,D/HeadlinesDataCenter( 5517): requestUpdateNewsWelcomeCard !!! no welcome card
E/ActivityManager(  888): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  888): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  888): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  888): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 8041): MountEmulatedStorage()
E/Zygote  ( 8041): v2
I/libpersona( 8041): KNOX_SDCARD checking this for 10128
I/libpersona( 8041): KNOX_SDCARD not a persona
,I/ActivityManager(  888): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=8041 uid=10128 gids={50128, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/dhcpcd  ( 7936): wlan0: acknowledged 192.168.1.135 from 192.168.1.1
,I/art     (  339): Explicit concurrent mark sweep GC freed 8749(371KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 14MB/23MB, paused 275us total 10.859ms
,I/art     (  339): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 14MB/23MB, paused 249us total 7.537ms
,I/art     (  339): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 14MB/23MB, paused 246us total 7.768ms
,I/SELinux ( 8041): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 8041): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 8041): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 8041): TimaSignature is unavailable
,D/ActivityThread( 8041): Added TimaKeyStore provider
,I/dhcpcd  ( 7936): wlan0: leased 192.168.1.135 for 86400 seconds
,E/WifiStateMachine(  888): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: []  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576} new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.135/24,]  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0}
E/WifiStateMachine(  888): updateLinkProperties nid: 0 state: CONNECTING reason: CMD_UPDATE_LINKPROPERTIES v4
D/ConnectivityService(  888): Update of LinkProperties for NetworkAgentInfo [WIFI () - 503]; created=false
,W/libprocessgroup(  888): failed to open /acct/uid_10012/pid_6664/cgroup.procs: No such file or directory
,D/ResourcesManager( 8041): creating new AssetManager and set to /system/app/Newsstand/Newsstand.apk
,E/LightSensor(  888): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 3, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=1, bp1=1, cp1=3, cpl=3202560
,D/AutomaticBrightnessController(  888): mCallbacks.updateBrightness()
D/DisplayPowerController(  888): getFinalBrightness : 8 -> 8
,E/LightSensor(  888): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 3, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=1, bp1=1, cp1=3, cpl=3202560
,D/AutomaticBrightnessController(  888): mCallbacks.updateBrightness()
D/DisplayPowerController(  888): getFinalBrightness : 8 -> 8
,E/Vold    (  248): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  248): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 8041): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache
,E/Vold    (  248): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  248): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 8041): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/files
,E/Vold    (  248): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  248): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 8041): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache
,E/Vold    (  248): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  248): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 8041): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/files
,E/WifiStateMachine(  888): setSuspendOptimizationsNative: 1 true -want true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - processMessage - processMsg
,D/WifiP2pService(  888): InactiveState{ what=143375 }
,D/WifiP2pService(  888): P2pEnabledState{ what=143375 }
,E/WifiStateMachine(  888): WifiStateMachine DHCP successful
,E/WifiStateMachine(  888): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: [192.168.1.135/24,]  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576} new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.135/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0}
,D/ConnectivityService(  888): Update of LinkProperties for NetworkAgentInfo [WIFI () - 503]; created=false
E/WifiStateMachine(  888): updateLinkProperties nid: 0 state: CONNECTING reason: DHCP_SUCCESS v4 v4r v4dns isprov
,D/StatusBar.NetworkController( 1171): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020498/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020133/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020464/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
,E/WifiStateMachine(  888): WifiStateMachine: handleSuccessfulIpConfiguration and no scan results"NG700"WPA_PSK
D/WifiStateMachine(  888): Not connected state, yet.
E/WifiStateMachine(  888): VerifyingLinkState enter
,D/WifiStateMachine(  888): updatePoorNetworkAvoidance - Poor Network Test Enabled / !mIsFmcNetwork : false / true - mPoorNetworkAvoidanceEnabled:disabled
D/WifiStateMachine(  888): updatePoorNetworkDetection - Airplane Mode Off / Mobile Data Enabled / SIM State-Ready / MobilePolicyDataDisabled / !mIsFmcNetwork : 
D/WifiStateMachine(  888): false / true / false / true / true - mPoorNetworkDetectionEnabled: disabled
D/WifiNative-HAL(  888): callSECApiInt - ID [210]
,E/WifiStateMachine(  888): setDetailed state, old =CONNECTING and new state=VERIFYING_POOR_LINK hidden=false
,E/ConnectivityService(  888): updateNetworkInfo()
,D/ConnectivityService(  888): updateLinkProperties: newLp = {InterfaceName: wlan0 LinkAddresses: [192.168.1.135/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}
D/ConnectivityService(  888): Adding iface wlan0 to network 503
,I/CLocInfoService(  888): External Intent Received android.net.wifi.STATE_CHANGE
,D/WifiWatchdogStateMachine(  888): updateDnsLinkProperty: enter
,D/WifiWatchdogStateMachine.DnsPinger(  888): setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.135/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}
D/WifiWatchdogStateMachine.DnsResolver(  888): setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.135/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}
,D/WifiWatchdogStateMachine.SingDnsChecker(  888): setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.135/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}
D/WifiWatchdogStateMachine.CaptivePortalDnsResolver(  888): setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.135/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}
,D/StatusBar.NetworkController( 1171): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020498/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020133/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020464/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
,D/ConnectivityService(  888): Adding Route [fe80::/64 -> :: wlan0] to network 503
,D/ConnectivityService(  888): Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 503
,D/ConnectivityService(  888): Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 503
,E/ConnectivityService(  888): Unexpected mtu value: 0, wlan0
D/ConnectivityService(  888): updateSourceRoutes : add source routing for type : 1
D/ConnectivityService(  888): updateSourceRoutes : add src route for:192.168.1.135
,V/        (  283): QcRouteController
,E/WifiStateMachine(  888): VerifyingLinkState GOOD_LINK_DETECTED: transition to (new) connected (old)captive portal check
,D/WifiStateMachine(  888): Now, connected state.
E/WifiStateMachine(  888): setDetailed state, old =VERIFYING_POOR_LINK and new state=CAPTIVE_PORTAL_CHECK hidden=false
,E/WifiStateMachine(  888): setDetailed state, old =CAPTIVE_PORTAL_CHECK and new state=CONNECTED hidden=false
,I/WifiTrafficPoller(  888): evaluateTrafficStatsPolling
,I/CLocInfoService(  888): External Intent Received android.net.wifi.STATE_CHANGE
,D/StatusBar.NetworkController( 1171): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020498/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020133/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020464/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
,E/WifiStateMachine(  888): Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,I/WifiTrafficPoller(  888): evaluateTrafficStatsPolling
I/WifiTrafficPoller(  888): mBoosterFLAG : 0
I/WifiTrafficPoller(  888): current booster mode : FullMode
,V/        (  283): QcRouteController
,E/WifiStateMachine(  888): ConnectedState Enter  mScreenOn=true scanperiod=20000
,D/StatusBar.NetworkController( 1171): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020498/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020133/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020464/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
,D/WifiNative-HAL(  888): callSECApiVoid - ID [212]
,D/StatusBar.NetworkController( 1171): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02012b/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020466/com.android.systemui:drawable/stat_sys_signal_inout mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
,D/StatusBar.NetworkController( 1171): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1171): applyOpen
,D/StatusBar.NetworkController( 1171): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1171): applyOpen
D/StatusBar.NetworkController( 1171): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1171): applyOpen
D/StatusBar.NetworkController( 1171): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1171): applyOpen
I/CLocInfoService(  888): External Intent Received android.net.wifi.STATE_CHANGE
,I/WifiStateMachine(  888): REQUEST_POWER_SAVE_ON
,I/WebViewFactory( 8041): Loading com.google.android.webview version 37 (1726107-arm) (code 119201)
,D/ResourcesManager( 8041): creating new AssetManager and set to /system/app/WebViewGoogle/WebViewGoogle.apk
,V/        (  283): QcRouteController
,I/LibraryLoader( 8041): Loading: webviewchromium
,I/LibraryLoader( 8041): Time to load native libraries: 8 ms (timestamps 2457-2465)
,I/LibraryLoader( 8041): Expected native library version number "",actual native library version number ""
,V/        (  283): QcRouteController
,V/WebViewChromiumFactoryProvider( 8041): Binding Chromium to main looper Looper (main, tid 1) {3d1f5123}
,I/LibraryLoader( 8041): Expected native library version number "",actual native library version number ""
,I/chromium( 8041): [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
,V/        (  283): QcRouteController
,E/LightSensor(  888): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
D/AutomaticBrightnessController(  888): mCallbacks.updateBrightness()
D/DisplayPowerController(  888): getFinalBrightness : 8 -> 8
,V/        (  283): QcRouteController
,V/        (  283): QcRouteController
,I/BrowserStartupController( 8041): Initializing chromium process, renderers=0
,W/art     ( 8041): Attempt to remove local handle scope entry from IRT, ignoring
,V/        (  283): QcRouteController
,W/chromium( 8041): [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
,I/chromium( 8041): [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=41 off=46768 len=2953
,W/AudioManagerAndroid( 8041): Requires BLUETOOTH permission
I/chromium( 8041): [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:42 off:229524 len:643667
,D/ConnectivityService(  888): Setting Dns servers for network 503 to [/192.168.1.1]
,D/Nat464Xlat(  888): requiresClat: netType=1, connected=false, hasIPv4Address=true
D/ConnectivityService(  888): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 503]
E/ConnectivityService(  888): updateNetworkInfo()
D/ConnectivityService(  888): calling update connectivity
E/ConnectivityService(  888): updateNetworkInfo()
D/ConnectivityService(  888): ignoring duplicate network state non-change
D/ConnectivityService(  888): ignoring duplicate network state non-change
D/ConnectivityService(  888): NetworkAgentInfo [WIFI () - 503] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityService(  888): notifyType PRECHECK for NetworkAgentInfo [WIFI () - 503]
D/ConnectivityService(  888): calling update connectivity
,D/ConnectivityService(  888): rematching NetworkAgentInfo [WIFI () - 503]
D/ConnectivityService(  888):  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityService(  888):   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  888):   checking if request is satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  888): currentScore = 0, newScore = 60
D/ConnectivityService(  888):    accepting network in place of null
D/ConnectivityService(  888): sending new Min Network Score(60): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  888): DefaultState{ when=-2ms what=532481 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  888): Connected
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  888): EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  888): Validated
,D/TelephonyNetworkFactory( 1459): Cellular releasing Network for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,E/CSLegacyTypeTracker(  888): add() : Adding agent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{503}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.135/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{true} explicitlySelected{false} } for legacy network type 1
D/CSLegacyTypeTracker(  888): Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 503] isDefaultNetwork=true
D/ConnectivityService(  888): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,D/ConnectivityService(  888): sendStickyBroadcastDelayed: delayMs=500, action=android.net.conn.CONNECTIVITY_CHANGE
,D/SmartBondingService(  888): SmartBondingReceiver: onReceive action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/ConnectivityService(  888): Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{503}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.135/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{true} explicitlySelected{false} }
D/SmartBondingService(  888): EVENT_UPDATE_SB_STATE called / mDisableBySIOP false
D/SmartBondingService(  888): getSBEnabled() enabled =false
D/SmartBondingService(  888): getSBEnabled() enabled =false
D/SmartBondingService(  888): getSBEnabled() enabled =false
,D/EntConnectivity(  888): Not allowed due to - mEnabled false
D/ConnectivityService(  888): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 503]
D/ConnectivityService(  888): calling update connectivity
,V/NetworkStats(  888): updateIfacesLocked()
D/NtpTrustedTime(  888): currentTimeMillis() cache hit
V/NetworkStats(  888): performPollLocked(flags=0x1)
D/ConnectivityService(  888):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  888):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
D/SmartBondingService(  888): getNetworkEnabled : wifi : true mobile : true
,D/ConnectivityService(  888): sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
D/NetworkStatsFactory(  888): UpdateStatsForKnox
D/ConnectivityService(  888): returning getNetworkInfo(networkType - 28) :[type: MOBILE_ENT1[] - MOBILE_ENT1, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,V/NetworkStats(  888): performPollLocked() took 2ms
D/NtpTrustedTime(  888): currentTimeMillis() cache hit
,D/ConnectivityService(  888): Validated NetworkAgentInfo [WIFI () - 503]
D/ConnectivityService(  888): rematching NetworkAgentInfo [WIFI () - 503]
D/ConnectivityService(  888):  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityManager.CallbackHandler( 1171): CM callback handler got msg 524290
D/ConnectivityService(  888): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  888):   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  888): Network NetworkAgentInfo [WIFI () - 503] was already satisfying request 1. No change.
D/StatusBar.NetworkController( 1171): getUpdateDataNetType(): 0
D/StatusBar.NetworkController( 1171): updateDataNetType()
D/StatusBar.NetworkController( 1171): NoService, mRoamingIconId = 0
D/ConnectivityService(  888): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 503]
,D/ConnectivityService(  888): calling update connectivity
D/ConnectivityService(  888):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  888):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  888): sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
,D/NtpTrustedTime(  888): currentTimeMillis() cache hit
,D/NtpTrustedTime(  888): currentTimeMillis() cache hit
,D/ConnectivityManager.CallbackHandler( 1171): CM callback handler got msg 524290
,D/NtpTrustedTime(  888): currentTimeMillis() cache hit
,D/NtpTrustedTime(  888): currentTimeMillis() cache hit
D/NtpTrustedTime(  888): currentTimeMillis() cache hit
V/NetworkStats(  888): advisePersistThreshold() given 9223372036854775, clamped to 2097152
D/NtpTrustedTime(  888): currentTimeMillis() cache hit
,D/StatusBar.NetworkController( 1171): updateDataIcon, mDataDirectionIconId = (null) mDataConnected = false
D/StatusBar.NetworkController( 1171): updateTelephonySignalStrength: hasService=false ss=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte
D/StatusBar.NetworkController( 1171): updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal
D/StatusBar.NetworkController( 1171): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02012b/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020466/com.android.systemui:drawable/stat_sys_signal_inout mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
D/StatusBar.NetworkController( 1171): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1171): applyOpen
D/StatusBar.NetworkController( 1171): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1171): applyOpen
D/StatusBar.NetworkController( 1171): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1171): applyOpen
D/StatusBar.NetworkController( 1171): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1171): applyOpen
,D/ConnectivityService(  888): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
I/Adreno-EGL( 8041): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 8041): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 8041): Build Date: 03/03/15 Tue
I/Adreno-EGL( 8041): Local Branch: LA.BF.1.1_RB1_20150108_025_1077123_1158499
I/Adreno-EGL( 8041): Remote Branch: 
I/Adreno-EGL( 8041): Local Patches: 
I/Adreno-EGL( 8041): Reconstruct Branch: 
D/ConnectivityService(  888): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/StatusBar.NetworkController( 1171): getUpdateDataNetType(): 0
D/StatusBar.NetworkController( 1171): updateDataNetType()
D/StatusBar.NetworkController( 1171): NoService, mRoamingIconId = 0
D/StatusBar.NetworkController( 1171): updateDataIcon, mDataDirectionIconId = (null) mDataConnected = false
D/StatusBar.NetworkController( 1171): updateTelephonySignalStrength: hasService=false ss=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte
D/StatusBar.NetworkController( 1171): updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal
D/StatusBar.NetworkController( 1171): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02012b/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020466/com.android.systemui:drawable/stat_sys_signal_inout mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
,I/NSApplication( 8041): Starting up...
D/ConnectivityService(  888): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/ConnectivityService(  888): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  888): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  888): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/ActivityManager(  888): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  888): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  888): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  888): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 8140): MountEmulatedStorage()
E/Zygote  ( 8140): v2
I/libpersona( 8140): KNOX_SDCARD checking this for 10138
I/libpersona( 8140): KNOX_SDCARD not a persona
,I/ActivityManager(  888): Start proc com.samsung.android.sconnect for broadcast com.samsung.android.sconnect/.periph.PeriphStartReceiver: pid=8140 uid=10138 gids={50138, 9997, 3002, 3001, 1028, 1015, 3003} abi=armeabi-v7a
,I/ActivityManager(  888): Killing 7143:com.samsung.android.provider.shootingmodeprovider/u0a170 (adj 15): bgCount ##41
,E/LightSensor(  888): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  888): mCallbacks.updateBrightness()
D/DisplayPowerController(  888): getFinalBrightness : 8 -> 8
,I/SELinux ( 8140): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 8140): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 8140): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 8140): TimaSignature is unavailable
,D/ActivityThread( 8140): Added TimaKeyStore provider
,D/ResourcesManager( 8140): creating new AssetManager and set to /system/app/QuickConnect/QuickConnect.apk
,W/ResourcesManager( 8140): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,W/ResourcesManager( 8140): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
W/ResourcesManager( 8140): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,W/libprocessgroup(  888): failed to open /acct/uid_10170/pid_7143/cgroup.procs: No such file or directory
,D/QuickConnect( 8140): PeriphStartReceiver.onReceive - android.net.conn.CONNECTIVITY_CHANGE
,I/QuickConnect( 8140): PeriphStartReceiver.onReceive - USER_OWNER care CONNECTIVITY_ACTION. run P service
,I/QuickConnect( 8140): PeriphStartReceiver.onReceive - no need to start
,E/ActivityManager(  888): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  888): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  888): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  888): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 8155): MountEmulatedStorage()
,E/Zygote  ( 8155): v2
I/libpersona( 8155): KNOX_SDCARD checking this for 10163
I/libpersona( 8155): KNOX_SDCARD not a persona
,I/ActivityManager(  888): Start proc com.android.email for broadcast com.android.email/.EmailConnectivityManager: pid=8155 uid=10163 gids={50163, 9997, 3003, 1028, 1015, 1023, 3002, 3001, 1003} abi=armeabi-v7a
,I/ActivityManager(  888): Killing 5694:com.sec.android.app.samsungapps/u0a40 (adj 15): bgCount ##41
,D/PowerManagerService(  888): [s] UserActivityState : 1 -> 2
D/DisplayPowerController(  888): getFinalBrightness : 1 -> 1
,D/PowerManagerService(  888): [s] DisplayPowerCallbacks : onStateChanged()
,E/LightSensor(  888): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  888): mCallbacks.updateBrightness()
D/DisplayPowerController(  888): getFinalBrightness : 1 -> 1
I/SELinux ( 8155): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 8155): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 8155): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/DisplayPowerController(  888): getFinalBrightness : 1 -> 1
D/lights  (  888): lcd : 1 +
,D/TimaKeyStoreProvider( 8155): TimaSignature is unavailable
,D/ActivityThread( 8155): Added TimaKeyStore provider
,D/lights  (  888): lcd : 1 -
,D/DisplayPowerController(  888): getFinalBrightness : 1 -> 1
,D/ResourcesManager( 8155): creating new AssetManager and set to /system/app/SecEmail_K/SecEmail_K.apk
,W/ResourcesManager( 8155): Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
,W/ResourcesManager( 8155): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 8155): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
,W/ResourcesManager( 8155): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,W/libprocessgroup(  888): failed to open /acct/uid_10040/pid_5694/cgroup.procs: No such file or directory
,D/RCPManagerService(  888): exchangeData() failure , invalid userId
,D/RCPManagerService(  888): exchangeData() failure , invalid userId
,D/RCPManagerService(  888): exchangeData() failure , invalid userId
,E/ActivityManager(  888): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  888): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  888): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  888): checkUser: useridlist=null, currentuser=0
,D/RCPManagerService(  888): exchangeData() failure , invalid userId
,E/Zygote  ( 8178): MountEmulatedStorage()
I/ActivityManager(  888): Start proc com.sec.android.provider.badge for content provider com.sec.android.provider.badge/.BadgeProvider: pid=8178 uid=10078 gids={50078, 9997} abi=armeabi-v7a
,E/Zygote  ( 8178): v2
I/libpersona( 8178): KNOX_SDCARD checking this for 10078
I/libpersona( 8178): KNOX_SDCARD not a persona
,V/BitmapFactory( 8155): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_015.png
,E/LightSensor(  888): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  888): mCallbacks.updateBrightness()
D/DisplayPowerController(  888): getFinalBrightness : 1 -> 1
,D/ConnectivityService(  888): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/ConnectivityService(  888): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/ConnectivityService(  888): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/Tethering(  888): MasterInitialState.processMessage what=3
,D/SmartBondingService(  888): SmartBondingReceiver: onReceive action=android.net.conn.CONNECTIVITY_CHANGE
D/SmartBondingService(  888): SmartBondingReceiver: wifi is connected
D/SmartBondingService(  888): SmartBondingReceiver: wifi ap is not changed
D/ConnectivityService(  888): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/CLocInfoService(  888): External Intent Received android.net.conn.CONNECTIVITY_CHANGE
D/ConnectivityService(  888): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/CLocInfoService(  888): CLocinfo wifi true 
D/ConnectivityService(  888): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SmartBondingService(  888): EVENT_UPDATE_SB_STATE called / mDisableBySIOP false
D/SmartBondingService(  888): getSBEnabled() enabled =false
D/SmartBondingService(  888): getSBEnabled() enabled =false
D/SmartBondingService(  888): getSBEnabled() enabled =false
,D/ConnectivityService(  888): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  888): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  888): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/SELinux ( 8178): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,D/ConnectivityService(  888): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/SELinux ( 8178): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 8178): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,D/SmartBondingService(  888): getNetworkEnabled : wifi : true mobile : true
D/ConnectivityService(  888): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  888): returning getNetworkInfo(networkType - 0) :[type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,V/BitmapFactory( 8155): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_000.png
,D/ConnectivityService(  888): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/ConnectivityService(  888): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  888): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/DBG_DM  ( 3767): [lllllllIlllIIlllIlIl(88/llIIIIlllllIIllIIllI)] WiFi Network is connected
,I/DBG_DM  ( 3767): [com.wssyncmldm.XDMService(1111/IlIlllIIlIlIIIlIlIll)] WiFi network Connected : true
,D/accuweather( 2029): [KK AccuPhone]>>> SWW:66 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,D/ConnectivityService(  888): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  888): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
W/ContextImpl( 2238): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1994 android.content.ContextWrapper.startService:533 com.samsung.SMT.SamsungTTSService.d:-1 com.samsung.SMT.SamsungTTSService.a:-1 com.samsung.SMT.ai.onReceive:-1 
,W/ContextImpl( 2238): Implicit intents with startService are not safe: Intent { act=com.samsung.SMT.UpdateManager.UPDATE_DATA } android.content.ContextWrapper.startService:533 com.samsung.SMT.SamsungTTSService.d:-1 com.samsung.SMT.SamsungTTSService.a:-1 
,D/ConnectivityService(  888): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  888): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  888): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  888): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  888): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  888): returning getNetworkInfo(networkType - 0) :[type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,V/BitmapFactory( 8155): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_015.png
,D/TimaKeyStoreProvider( 8178): TimaSignature is unavailable
,D/ActivityThread( 8178): Added TimaKeyStore provider
,V/BitmapFactory( 8155): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_000.png
,V/BitmapFactory( 8155): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_000.png
,V/BitmapFactory( 8155): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_001.png
,V/BitmapFactory( 8155): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_002.png
,V/BitmapFactory( 8155): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_003.png
,D/RCPManagerService(  888): exchangeData() failure , invalid userId
,D/RCPManagerService(  888): exchangeData() failure , invalid userId
,I/ActivityManager(  888): Killing 7166:com.sec.android.app.videoplayer/u0a54 (adj 15): bgCount ##41
,D/ConnectivityService(  888): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SecurityLogAgent( 7490): KnoxConfiguration : Current State = 1
,D/SecurityLogAgent( 7490): KnoxConfiguration : Current State Mapping Found 
D/SecurityLogAgent( 7490): StateMachine : Current State = 1
,D/ConnectivityService(  888): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/SecurityLogAgent( 7490): StateMachine : Changed Current State = 1
,I/ActivityManager(  888): Killing 4869:com.google.android.gms.wearable/u0a12 (adj 15): bgCount ##41
V/BitmapFactory( 8155): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_004.png
,V/BitmapFactory( 8155): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_005.png
,V/BitmapFactory( 8155): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_006.png
,D/ResourcesManager( 8178): creating new AssetManager and set to /system/app/BadgeProvider/BadgeProvider.apk
,V/BitmapFactory( 8155): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_007.png
,V/BitmapFactory( 8155): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_008.png
,V/BitmapFactory( 8155): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_010.png
,V/BitmapFactory( 8155): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_011.png
,V/BitmapFactory( 8155): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_012.png
,D/SecContentProvider2(  888): uri = 11 selection = getMyKnoxAdmin
D/SecContentProvider2(  888): mCursor = null
,V/BitmapFactory( 8155): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_013.png
,V/BitmapFactory( 8155): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_014.png
,V/BitmapFactory( 8155): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_015.png
,V/BitmapFactory( 8155): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_000.png
V/BitmapFactory( 8155): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_001.png
,I/NetworkMonitor( 7878): type=WIFI subType= reason=null isConnected=true
D/ConnectivityService(  888): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/ConnectivityService(  888): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/ConnectivityService(  888): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  888): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/com.peel.receiver.ConnectivityActionReceiver( 5621): ConnectivityActionReceiver onReceive
,D/com.peel.receiver.ConnectivityActionReceiver( 5621): 
D/com.peel.receiver.ConnectivityActionReceiver( 5621): 
D/com.peel.receiver.ConnectivityActionReceiver( 5621): country_code: Germany -- rom region: GB
D/com.peel.receiver.ConnectivityActionReceiver( 5621): 
D/ConnectivityService(  888): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/ConnectivityService(  888): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/com.peel.receiver.ConnectivityActionReceiver( 5621): 
D/com.peel.receiver.ConnectivityActionReceiver( 5621): 
D/com.peel.receiver.ConnectivityActionReceiver( 5621):  network type WIFI path... network offline: false
D/com.peel.receiver.ConnectivityActionReceiver( 5621): 
D/com.peel.receiver.ConnectivityActionReceiver( 5621): has active network... run services...
D/com.peel.receiver.ConnectivityActionReceiver( 5621): 
D/com.peel.receiver.ConnectivityActionReceiver( 5621): 
D/com.peel.receiver.ConnectivityActionReceiver( 5621): last run: 1452509335763 -- System.currentTimeMillis()-last_run: 16303445
D/com.peel.receiver.ConnectivityActionReceiver( 5621): ... skip 
D/com.peel.receiver.ConnectivityActionReceiver( 5621): ... skip last_72_check
,D/ConnectivityService(  888): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/ActivityManager(  888): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  888): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  888): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  888): checkUser: useridlist=null, currentuser=0
,D/ConnectivityService(  888): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/BadgeProvider( 8178): onCreate
,D/BadgeProvider( 8178): DatabaseHelper
,E/Zygote  ( 8193): MountEmulatedStorage()
E/Zygote  ( 8193): v2
I/libpersona( 8193): KNOX_SDCARD checking this for 10178
I/libpersona( 8193): KNOX_SDCARD not a persona
,V/BitmapFactory( 8155): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_002.png
,V/BitmapFactory( 8155): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_003.png
,V/BitmapFactory( 8155): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_004.png
,V/BitmapFactory( 8155): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_005.png
,I/ActivityManager(  888): Start proc com.samsung.android.service.travel for broadcast com.samsung.android.service.travel/com.samsung.android.travel.bindService.TravelBroadcastReceiver: pid=8193 uid=10178 gids={50178, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,V/BitmapFactory( 8155): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_006.png
,V/BitmapFactory( 8155): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_007.png
,V/BitmapFactory( 8155): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_008.png
,V/BitmapFactory( 8155): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_010.png
,V/BitmapFactory( 8155): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_011.png
,V/BitmapFactory( 8155): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_012.png
,V/BitmapFactory( 8155): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_013.png
,V/BitmapFactory( 8155): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_014.png
,V/BitmapFactory( 8155): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_015.png
,V/BitmapFactory( 8155): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/delete_glance_line.pkm
,V/BitmapFactory( 8155): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/delete_glance_icon_undo.pkm
,V/BitmapFactory( 8155): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/list_icon_calendar_1.pkm
,V/BitmapFactory( 8155): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/email_attach_icon_etc.pkm
,V/BitmapFactory( 8155): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/list_icon_flag.pkm
V/BitmapFactory( 8155): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/list_icon_complate.pkm
,V/BitmapFactory( 8155): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/list_icon_flag_off_white.pkm
,V/BitmapFactory( 8155): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/email_list_attach_icon_star_off.pkm
V/BitmapFactory( 8155): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/email_list_attach_icon_star_on.pkm
,V/BitmapFactory( 8155): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/list_icon_flag_f.pkm
,V/BitmapFactory( 8155): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/list_icon_complate_f.pkm
,I/SELinux ( 8193): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
V/BitmapFactory( 8155): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/list_icon_flag_off_f.pkm
V/BitmapFactory( 8155): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/email_icon_foward.pkm
V/BitmapFactory( 8155): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/email_icon_foward_focus.pkm
V/BitmapFactory( 8155): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/list_icon_reply_forward.pkm
I/SELinux ( 8193): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
V/BitmapFactory( 8155): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/email_icon_reply.pkm
V/BitmapFactory( 8155): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/email_icon_reply_focus.pkm
E/SELinux ( 8193): [DEBUG] get_category: variable seinfo: shared sensitivity: NULL, cateogry: NULL
V/BitmapFactory( 8155): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/list_icon_vip.pkm
V/BitmapFactory( 8155): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/email_list_high_priority.pkm
V/BitmapFactory( 8155): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/email_list_low_priority.pkm
V/BitmapFactory( 8155): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/list_icon_server_draft.pkm
,V/BitmapFactory( 8155): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/list_icon_client_draft.pkm
,V/BitmapFactory( 8155): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/permission.pkm
,V/BitmapFactory( 8155): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/list_icon_voicemail.pkm
,V/BitmapFactory( 8155): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/list_icon_sms.pkm
,V/BitmapFactory( 8155): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/list_icon_sign.pkm
,V/BitmapFactory( 8155): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/list_icon_encryption.pkm
,D/BadgeProvider( 8178): query, [selection] : package='com.android.email' AND class='com.android.email.activity.Welcome' AND extraData='base_extra_badge'
,E/LightSensor(  888): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  888): mCallbacks.updateBrightness()
D/DisplayPowerController(  888): getFinalBrightness : 1 -> 1
,D/TimaKeyStoreProvider( 8193): TimaSignature is unavailable
,D/ActivityThread( 8193): Added TimaKeyStore provider
,D/ResourcesManager( 8193): creating new AssetManager and set to /system/app/TravelService_K/TravelService_K.apk
,D/BadgeProvider( 8178): sendNotify entered. [uri] : content://com.sec.badge/apps/1
D/BadgeProvider( 8178): sendNotify, [notify] : null
D/Launcher.Model( 1465): reloadBadges entered.
D/BadgeProvider( 8178): update, [uri] : content://com.sec.badge/apps/1
,D/BadgeProvider( 8178): update, [BadgeCount] : badgecount=0
D/BadgeProvider( 8178): update, [UpdateCount] : 1
,V/BitmapFactory( 8155): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/tw_expander_open_01_holo_light.pkm
,V/BitmapFactory( 8155): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/tw_expander_close_01_holo_light.pkm
,W/libprocessgroup(  888): failed to open /acct/uid_10054/pid_7166/cgroup.procs: No such file or directory
,W/libprocessgroup(  888): failed to open /acct/uid_10012/pid_4869/cgroup.procs: No such file or directory
,I/ActivityManager(  888): Killing 4991:com.android.defcontainer/u0a5 (adj 15): bgCount ##41
,D/ConnectivityService(  888): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  888): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  888): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  888): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  888): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ChimeraCfgMgr( 2467): Loading module com.google.android.gms.kids from APK com.google.android.gms
,D/ConnectivityService(  888): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  888): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ChimeraCfgMgr( 2467): Loading module com.google.android.gms.kids from APK com.google.android.gms
,E/ActivityManager(  888): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  888): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  888): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  888): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 8210): MountEmulatedStorage()
,E/Zygote  ( 8210): v2
I/libpersona( 8210): KNOX_SDCARD checking this for 10040
I/libpersona( 8210): KNOX_SDCARD not a persona
,I/ActivityManager(  888): Start proc com.sec.android.app.samsungapps for broadcast com.sec.android.app.samsungapps/.networkstatereceiver.NetworkStateReceiver: pid=8210 uid=10040 gids={50040, 9997, 1028, 1015, 3003} abi=armeabi-v7a
,I/SELinux ( 8210): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
D/ConnectivityService(  888): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/SELinux ( 8210): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,W/libprocessgroup(  888): failed to open /acct/uid_10005/pid_4991/cgroup.procs: No such file or directory
E/SELinux ( 8210): [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
,E/SMD     (  289): DCD ON
,D/TimaKeyStoreProvider( 8210): TimaSignature is unavailable
,D/ActivityThread( 8210): Added TimaKeyStore provider
,E/LightSensor(  888): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  888): mCallbacks.updateBrightness()
D/DisplayPowerController(  888): getFinalBrightness : 1 -> 1
,D/StatusBar.NetworkController( 1171): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02012b/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020464/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
D/StatusBar.NetworkController( 1171): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1171): applyOpen
,I/art     (  888): Explicit concurrent mark sweep GC freed 66557(3MB) AllocSpace objects, 5(80KB) LOS objects, 30% free, 36MB/52MB, paused 1.256ms total 83.946ms
,D/StatusBar.NetworkController( 1171): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1171): applyOpen
D/StatusBar.NetworkController( 1171): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1171): applyOpen
D/StatusBar.NetworkController( 1171): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1171): applyOpen
,W/ActivityManager(  888): Unable to start service Intent { cmp=com.android.email/.service.AttachmentDownloadService } U=0: not found
,D/ResourcesManager( 8210): creating new AssetManager and set to /data/app/com.sec.android.app.samsungapps-1/base.apk
,I/GLSUser ( 1714): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: ac2dm
I/GLSUser ( 1714): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> ac2dm without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1714): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1714): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1714): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/BitmapFactory( 1714): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/common_ic_googleplayservices.png
,V/BitmapFactory( 1714): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  888): uri = 14 selection = getSealedState
D/SecContentProvider2(  888): mCursor = null
,D/SecContentProvider2(  888): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  888): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
V/ApplicationPolicy(  888): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/StatusBar( 1171): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,I/PhoneStatusBar( 1171): Icon Only
,D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
D/PanelView( 1171): There is/are notification(s) 
,D/PanelView( 1171): There is/are notification(s) 
,W/Kids    ( 2467): [AccountUtils] Account not ready
W/Kids    ( 2467): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/Kids    ( 2467): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/Kids    ( 2467): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/Kids    ( 2467): 	at com.google.android.gms.auth.p.c(SourceFile:550)
W/Kids    ( 2467): 	at com.google.android.gms.auth.p.b(SourceFile:477)
W/Kids    ( 2467): 	at com.google.android.gms.kids.account.k.d(SourceFile:103)
W/Kids    ( 2467): 	at com.google.android.gms.kids.account.p.a(SourceFile:70)
W/Kids    ( 2467): 	at com.google.android.gms.kids.account.t.a(SourceFile:62)
W/Kids    ( 2467): 	at com.google.android.gms.chimera.f.run(SourceFile:179)
W/Kids    ( 2467): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
W/Kids    ( 2467): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
W/Kids    ( 2467): 	at java.lang.Thread.run(Thread.java:818)
,D/ConnectivityService(  888): NetTransition Wakelock (NetworkAgentInfo [WIFI () - 502] cleared because we found a replacement network
,D/ConnectivityService(  888): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/WaitQueueForNetworkActivate( 8210): notifyNetworkActivated
,E/LightSensor(  888): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  888): mCallbacks.updateBrightness()
D/DisplayPowerController(  888): getFinalBrightness : 1 -> 1
,W/ContextImpl( 8210): Implicit intents with startService are not safe: Intent { act=com.sec.knox.containeragent.service.containermanager.ContainerManagerService } android.content.ContextWrapper.bindService:559 com.sec.knox.containeragent.ContainerManager.<init>:49 com.sec.android.app.samsungapps.vlibrary2.knoxmode.KNOXAPI.<init>:20 
,W/ActivityManager(  888): Unable to start service Intent { act=com.sec.knox.containeragent.service.containermanager.ContainerManagerService } U=0: not found
,D/hcjo    ( 8210): AutoUpdateManager:IDLE:execute
,D/InitializeManagerStateMachine( 8210): execute::IDLE:EXECUTE
,D/InitializeManagerStateMachine( 8210): exit::IDLE
D/InitializeManagerStateMachine( 8210): entry::NETWORK_CHECK
D/ConnectivityService(  888): returning getNetworkInfo(networkType - 0) :[type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  888): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/InitializeManagerStateMachine( 8210): execute::NETWORK_CHECK:NETWORK_STATE_OK
D/InitializeManagerStateMachine( 8210): exit::NETWORK_CHECK
D/InitializeManagerStateMachine( 8210): entry::CHECK_COUNTRY_INFO
D/InitializeManagerStateMachine( 8210): execute::CHECK_COUNTRY_INFO:COUNTRY_INFO_OK
D/InitializeManagerStateMachine( 8210): exit::CHECK_COUNTRY_INFO
D/InitializeManagerStateMachine( 8210): entry::SUCCESS
D/hcjo    ( 8210): AutoUpdateManager:INITCHECK:onInitializeSuccess
I/Hs20UtilService( 1304): Starting #8
,I/Hs20UtilService( 1304): Message received 5007
,D/NearbySettings( 1304): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,V/NearbySettings( 1304): DMSUtil.isNetworkConnected - flag-null, state-null
D/ConnectivityService(  888): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
E/Watchdog(  888): !@Sync 3
I/NearbySettings( 1304): DMSUtil.isNetworkConnected - WIFI: CONNECTED
D/ConnectivityService(  888): returning getNetworkInfo(networkType - 13) :[type: WIFI_P2P[] - WIFI_P2P, state: UNKNOWN/IDLE, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/NearbySettings( 1304): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 1304): DMSUtil.isNetworkConnected - WIFI-true, Hotspot-false, P2P-false, Eth-false
I/NearbySettings( 1304): MountReceiver.onReceive - Keep current state
D/hcjo    ( 8210): AutoUpdateTriggerManager:IDLE:notifyNextTime
D/hcjo    ( 8210): AutoUpdateManager:UPD_CHECK_TIMING:onNoUpdateTime
D/ConnectivityService(  888): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/InitializeManagerStateMachine( 8210): exit::SUCCESS
D/InitializeManagerStateMachine( 8210): entry::IDLE
,I/Hs20UtilService( 1304): Starting #9
,I/Hs20UtilService( 1304): Message received 5007
,I/ActivityManager(  888): Killing 4608:com.sec.android.app.shealth/u0a35 (adj 15): bgCount ##41
,D/NearbySettings( 1304): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
I/NearbySettings( 1304): MountReceiver.onReceive - Keep current state
,I/Hs20UtilService( 1304): Starting #10
,D/NearbySettings( 1304): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
I/Hs20UtilService( 1304): Message received 5007
,V/NearbySettings( 1304): DMSUtil.isNetworkConnected - flag-null, state-null
D/ConnectivityService(  888): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/NearbySettings( 1304): DMSUtil.isNetworkConnected - WIFI: CONNECTED
,D/ConnectivityService(  888): returning getNetworkInfo(networkType - 13) :[type: WIFI_P2P[] - WIFI_P2P, state: UNKNOWN/IDLE, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/NearbySettings( 1304): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 1304): DMSUtil.isNetworkConnected - WIFI-true, Hotspot-false, P2P-false, Eth-false
I/NearbySettings( 1304): MountReceiver.onReceive - Keep current state
,I/Hs20UtilService( 1304): Starting #11
,I/Hs20UtilService( 1304): Message received 5007
,D/NearbySettings( 1304): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,I/NearbySettings( 1304): MountReceiver.onReceive - Keep current state
,I/WifiStateMachine(  888): callSECApi what=220
,D/WifiStateMachine(  888): SEC_COMMAND_ID_GET_FWS_OPEN_AP_CHECK : 0
,E/LightSensor(  888): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  888): mCallbacks.updateBrightness()
D/DisplayPowerController(  888): getFinalBrightness : 1 -> 1
,I/PCWCLIENTTRACE_PushUtil( 7858): SPPPushClient is installed : true
I/PCWCLIENTTRACE_PushUtil( 7858): sales region : global
I/PCWCLIENTTRACE_PushUtil( 7858): getPushTypeList : [SPP, GCM]
I/PCWCLIENTTRACE_SYSTEMReceiver( 7858): [onReceive] - android.net.conn.CONNECTIVITY_CHANGE
,I/SurfaceFlinger(  249): id=16 createSurf (1x1),1 flag=4, Toast
,D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
,D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
,I/DIAGMON_AGENT( 7908): [lIIllllllllIlIlIllll(17/llIIIIlllllIIllIIllI)] Receive broadcast: android.net.conn.CONNECTIVITY_CHANGE
,I/DIAGMON_AGENT( 7908): [lIIllllllllIlIlIllll(31/llIIIIlllllIIllIIllI)] Running with RegistrationReceiver
,D/PowerManagerService(  888): [api] acquire WakeLock flags=0x2000000a tag=WindowManager uid=1000 pid=888
,D/DisplayPowerController(  888): getFinalBrightness : 8 -> 8
,D/PowerManagerService(  888): [s] DisplayPowerCallbacks : onStateChanged()
D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
,W/libprocessgroup(  888): failed to open /acct/uid_10035/pid_4608/cgroup.procs: No such file or directory
,D/lights  (  888): lcd : 8 +
D/DisplayPowerController(  888): getFinalBrightness : 8 -> 8
,D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
,D/lights  (  888): lcd : 8 -
,D/DisplayPowerController(  888): getFinalBrightness : 8 -> 8
,D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
,D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
,D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
,D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
,D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
,I/FOTA_Client( 7345): [com.sec.android.fotaclient.FotaRegisterReceiver(113/onReceive)] Already device registered...
,I/FOTA_Client( 7345): [com.sec.android.fotaclient.FotaUpdaterReceiver(103/onReceive)] Auto update settings is activated
,I/FOTA_Client( 7345): [lllllllllllIlllllIIl(197/lllIlIlIIIllIIlIllIl)] Polling time is vaild
,I/FOTA_Client( 7345): [com.sec.android.fotaclient.FotaUpdaterReceiver(126/onReceive)] Heartbeat settings is activated.
,I/FOTA_Client( 7345): [llIlIIIIlllIlllllIll(125/llIlIIIIlIIIIIlIlIII)] heartbeat time is vaild
,D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
,I/KLMS-2.4.503: ( 7386): KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,I/KLMS-2.4.503: ( 7386): MainReciver(): EventNotificationReciver- method called: AppActivityListner onReceive for Intent Action : android.net.conn.CONNECTIVITY_CHANGE , timestamp: 1452525639944
I/KLMS-2.4.503: ( 7386): MainReciver(): NETWORK_STATE_CHANGED_ACTION
D/ConnectivityService(  888): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  888): returning getNetworkInfo(networkType - 0) :[type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/KLMS-2.4.503: ( 7386): KLMSUtility(): isNetworkAvailable() - WIFI : true| MOBILE : false
I/KLMS-2.4.503: ( 7386): StateImplV2(): networkChangeListener().START
,I/KLMS-2.4.503: ( 7386): NetworkChangeOperations(): uploadRequestLog().START 
,I/KLMS-2.4.503: ( 7386): StateImplV2(): networkChangeListener().END
,D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
,I/WifiStateMachine(  888): CMD_RSSI_POLL : calculateWifiScore in!
,I/WifiStateMachine(  888): CMD_RSSI_POLL : calculateWifiScore out!
I/WifiStateMachine(  888): CMD_RSSI_POLL : out!
D/StatusBar.NetworkController( 1171): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02012b/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020464/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
,I/SO_AGENT( 7403): [com.sec.android.soagent.RegisterReceiver(104/onReceive)] Get Accessory List
,D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
,D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
,D/ConnectivityService(  888): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  888): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/LightSensor(  888): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  888): mCallbacks.updateBrightness()
D/DisplayPowerController(  888): getFinalBrightness : 8 -> 8
,E/SPPClientService( 7969): [[SystemStateMoniter]] SystemStateMonitorService : noConnect? : false
,I/SA      ( 6781): [OR] onReceive log=[SA = 2.1.0142 V = 21 HWD = 1920X1080 3.0 dpi = 480  SIZE = 2 LOCALE = en_US CSC = DBT MCC = 0 MNC 0 T = user DEVICE = klte P = kltexx I = LRX21T M = SM-G900F OKLEFT false DIS LRX21T.G900FXXU1BOD3 PSS = 5.219788042639568  ]
,I/SA      ( 6781): [OR] onReceive Intent=[ conn.CONNECTIVITY_CHANGE. networkInfo:[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] networkType:1 inetCondition:0 extraInfo:? isDefault:true ]
I/SA      ( 6781): [OR] == ACTION_CONNECTIVITY_CHANGE ==
,I/SA      ( 6781): [TPMU]  strSIMState 	:SIM_STATE_UNKNOWN
,I/SA      ( 6781): [OR] == isSIMCardReady false ==
D/ConnectivityService(  888): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/SA      ( 6781): [SCU] == networkStateCheck == true
I/SA      ( 6781): [DM] getCountryCodeFromCSC : DE
I/SA      ( 6781): isChinaCountryCode : false
,I/SA      ( 6781): [SCU] is ChinestModel Data Restricted   : false
I/SA      ( 6781): [OR] == networkStateCheck true ==
,D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1171): value : false
,I/SA      ( 6781): [OR] GetMyCountryZoneTask
,I/SA      ( 6781): [OR] onReceive END
,D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1171): value : false
,D/ConnectivityService(  888): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  888): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/SA      ( 6781): [SRS] prepareGetMyCountryZone
,I/SA      ( 6781): [TPMU]  strSIMState 	:SIM_STATE_UNKNOWN
,D/accuweather( 7369): [KK AccuPhone]>>> WC:30 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,D/accuweather( 7369): [KK AccuPhone]>>> UIMEM:106 [0:0] The widget does not exist in idle!!
,D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
,I/SA      ( 6781): [SSP] query invoked
,I/KnoxUsageLogPro( 7988): KnoxUsageReceiver onReceive :android.net.conn.CONNECTIVITY_CHANGE myUserId=0
I/KnoxUsageLogPro( 7988): premStatus:2
,I/KnoxUsageLogPro( 7988): isEulaShown : false
I/KnoxUsageLogPro( 7988): KnoxUsageReceiver onReceive : not Processible, just return
,I/SA      ( 6781): [TPMU] GetMccFromDB : null
I/SA      ( 6781): [SCU] getMccFromPreferece mcc = 260
,I/SA      ( 6781): [TPM] isNoProxy(default) : true
,D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
,D/Headlines( 5517): HeadlinesSystemBroadcastReceiver onReceive android.net.conn.CONNECTIVITY_CHANGE
,D/HeadlinesChannelUtil( 5517): getCountryCode(): countryCode = DE
,D/Headlines( 5517): Breath.onStartCommand : com.samsung.android.internal.headlines.UPDATE_WELCOME_CARD flag : 0
D/HeadlinesCardManager( 5517): updateCategory : HeadlinesCardManager:updateCategory() category size == 0
D/HeadlinesCardManager( 5517): updateCategory : HeadlinesCardManager:updateCategory() try to query category list
D/Headlines( 5517): queryCategory.  mRequest is not initialized.
D/HeadlinesCardManager( 5517): updateCategory : HeadlinesCardManager:updateCategory() reponse : false
D/HeadlinesCardManager( 5517): requestUpdateNewsWelcomeCard : request update welcome card to content card.
D/HeadlinesDataCenter( 5517): requestUpdateNewsWelcomeCard !!! no welcome card
,D/ConnectivityService(  888): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
,E/File    ( 6781): fail readDirectory() errno=2
,D/ConnectivityService(  888): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  888): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/QuickConnect( 8140): PeriphStartReceiver.onReceive - android.net.conn.CONNECTIVITY_CHANGE
,I/QuickConnect( 8140): PeriphStartReceiver.onReceive - USER_OWNER care CONNECTIVITY_ACTION. run P service
,I/QuickConnect( 8140): PeriphStartReceiver.onReceive - no need to start
,D/ConnectivityService(  888): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  888): returning getNetworkInfo(networkType - 0) :[type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
D/RCPManagerService(  888): exchangeData() failure , invalid userId
,D/RCPManagerService(  888): exchangeData() failure , invalid userId
,D/ConnectivityService(  888): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SecurityLogAgent( 7490): KnoxConfiguration : Current State = 1
D/SecurityLogAgent( 7490): KnoxConfiguration : Current State Mapping Found 
D/SecurityLogAgent( 7490): StateMachine : Current State = 1
D/ConnectivityService(  888): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SecurityLogAgent( 7490): StateMachine : Changed Current State = 1
,D/com.peel.receiver.ConnectivityActionReceiver( 5621): ConnectivityActionReceiver onReceive
D/com.peel.receiver.ConnectivityActionReceiver( 5621): 
D/com.peel.receiver.ConnectivityActionReceiver( 5621): 
D/com.peel.receiver.ConnectivityActionReceiver( 5621): country_code: Germany -- rom region: GB
D/com.peel.receiver.ConnectivityActionReceiver( 5621): 
,D/ConnectivityService(  888): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  888): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/com.peel.receiver.ConnectivityActionReceiver( 5621): 
D/com.peel.receiver.ConnectivityActionReceiver( 5621): 
D/com.peel.receiver.ConnectivityActionReceiver( 5621):  network type WIFI path... network offline: false
D/com.peel.receiver.ConnectivityActionReceiver( 5621): 
D/com.peel.receiver.ConnectivityActionReceiver( 5621): has active network... run services...
D/com.peel.receiver.ConnectivityActionReceiver( 5621): 
D/com.peel.receiver.ConnectivityActionReceiver( 5621): 
D/com.peel.receiver.ConnectivityActionReceiver( 5621): last run: 1452509335763 -- System.currentTimeMillis()-last_run: 16304344
D/com.peel.receiver.ConnectivityActionReceiver( 5621): ... skip 
D/com.peel.receiver.ConnectivityActionReceiver( 5621): ... skip last_72_check
,D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
,D/ConnectivityService(  888): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
,D/ConnectivityService(  888): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  888): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
,D/ConnectivityService(  888): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  888): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
,D/ChimeraCfgMgr( 2467): Loading module com.google.android.gms.kids from APK com.google.android.gms
,D/ConnectivityService(  888): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  888): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ChimeraCfgMgr( 2467): Loading module com.google.android.gms.kids from APK com.google.android.gms
,D/ConnectivityService(  888): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/hcjo    ( 8210): AutoUpdateManager:IDLE:execute
,D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
,E/LightSensor(  888): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
D/AutomaticBrightnessController(  888): mCallbacks.updateBrightness()
D/DisplayPowerController(  888): getFinalBrightness : 8 -> 8
,D/InitializeManagerStateMachine( 8210): execute::IDLE:EXECUTE
D/InitializeManagerStateMachine( 8210): exit::IDLE
D/InitializeManagerStateMachine( 8210): entry::NETWORK_CHECK
,D/ConnectivityService(  888): returning getNetworkInfo(networkType - 0) :[type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  888): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  888): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/InitializeManagerStateMachine( 8210): execute::NETWORK_CHECK:NETWORK_STATE_OK
D/InitializeManagerStateMachine( 8210): exit::NETWORK_CHECK
D/InitializeManagerStateMachine( 8210): entry::CHECK_COUNTRY_INFO
D/InitializeManagerStateMachine( 8210): execute::CHECK_COUNTRY_INFO:COUNTRY_INFO_OK
D/InitializeManagerStateMachine( 8210): exit::CHECK_COUNTRY_INFO
D/InitializeManagerStateMachine( 8210): entry::SUCCESS
D/hcjo    ( 8210): AutoUpdateManager:INITCHECK:onInitializeSuccess
,D/hcjo    ( 8210): AutoUpdateTriggerManager:IDLE:notifyNextTime
D/hcjo    ( 8210): AutoUpdateManager:UPD_CHECK_TIMING:onNoUpdateTime
D/ConnectivityService(  888): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/InitializeManagerStateMachine( 8210): exit::SUCCESS
D/InitializeManagerStateMachine( 8210): entry::IDLE
,D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1171): value : false
,I/GLSUser ( 1714): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: ac2dm
,I/GLSUser ( 1714): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> ac2dm without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1714): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1714): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1714): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
,V/BitmapFactory( 1714): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  888): uri = 14 selection = getSealedState
D/SecContentProvider2(  888): mCursor = null
,D/SecContentProvider2(  888): KnoxCustomManagerService offline: service is not available
,V/AlarmManager(  888): waitForAlarm result :4
,D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
,D/ConnectivityService(  888): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ApplicationPolicy(  888): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy(  888): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,W/Kids    ( 2467): [AccountUtils] Account not ready
W/Kids    ( 2467): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/Kids    ( 2467): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/Kids    ( 2467): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/Kids    ( 2467): 	at com.google.android.gms.auth.p.c(SourceFile:550)
W/Kids    ( 2467): 	at com.google.android.gms.auth.p.b(SourceFile:477)
W/Kids    ( 2467): 	at com.google.android.gms.kids.account.k.d(SourceFile:103)
W/Kids    ( 2467): 	at com.google.android.gms.kids.account.p.a(SourceFile:70)
W/Kids    ( 2467): 	at com.google.android.gms.kids.account.t.a(SourceFile:62)
W/Kids    ( 2467): 	at com.google.android.gms.chimera.f.run(SourceFile:179)
W/Kids    ( 2467): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
W/Kids    ( 2467): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
W/Kids    ( 2467): 	at java.lang.Thread.run(Thread.java:818)
,D/StatusBar( 1171): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,I/PhoneStatusBar( 1171): Icon Only
,D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
D/PanelView( 1171): There is/are notification(s) 
D/PanelView( 1171): There is/are notification(s) 
,D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
,D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
,D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
,D/BatteryService(  888): level:100, scale:100, status:5, health:2, present:true, voltage: 4241, temperature: 283, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  888): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
D/BatteryService(  888): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  888):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
I/MotionRecognitionService(  888): Plugged
I/MotionRecognitionService(  888): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1171): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1171): handleBatteryUpdate
,D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
,D/STATUSBAR-PhoneStatusBar( 1171):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3252): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3252): Disconnected process message: 10
,D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
,D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
,D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
,E/LightSensor(  888): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  888): mCallbacks.updateBrightness()
D/DisplayPowerController(  888): getFinalBrightness : 8 -> 8
,D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
,D/ConnectivityService(  888): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  888): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  888): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
,D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
,D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
,D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
,D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
,D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
,D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
,D/GCM     ( 1714): Connected
,D/ConnectivityService(  888): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  888): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  888): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  888): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  888): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/GCM     ( 1714): Message class com.google.f.a.a.p
,D/ConnectivityService(  888): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  888): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/StatusBar.NetworkController( 1171): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02012b/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020466/com.android.systemui:drawable/stat_sys_signal_inout mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
D/StatusBar.NetworkController( 1171): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1171): applyOpen
,D/StatusBar.NetworkController( 1171): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1171): applyOpen
D/StatusBar.NetworkController( 1171): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1171): applyOpen
D/StatusBar.NetworkController( 1171): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1171): applyOpen
,E/LightSensor(  888): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  888): mCallbacks.updateBrightness()
D/DisplayPowerController(  888): getFinalBrightness : 8 -> 8
,I/SA      ( 6781): [RC New] Execute method=[GET] start
,I/SA      ( 6781): [RC New] Security=[true]
,I/System.out( 6781): Thread-1081(ApacheHTTPLog):Reading from variable values from setDefaultValuesToVariables
,I/System.out( 6781): Thread-1081(ApacheHTTPLog):isShipBuild true
,I/System.out( 6781): Thread-1081(ApacheHTTPLog):SmartBonding Enabling is true, SHIP_BUILD is true, log to file is false, DBG is false
,E/LightSensor(  888): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  888): mCallbacks.updateBrightness()
D/DisplayPowerController(  888): getFinalBrightness : 8 -> 8
,E/LightSensor(  888): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  888): mCallbacks.updateBrightness()
D/DisplayPowerController(  888): getFinalBrightness : 8 -> 8
,E/LightSensor(  888): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  888): mCallbacks.updateBrightness()
D/DisplayPowerController(  888): getFinalBrightness : 8 -> 8
,E/LightSensor(  888): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  888): mCallbacks.updateBrightness()
D/DisplayPowerController(  888): getFinalBrightness : 8 -> 8
,I/SA      ( 6781): [RC New] [v2liruge] api execute + 664
,I/SA      ( 6781): [RC New] executeRequest [v2liruge] httpResponse : HTTP/1.1 200 OK
,I/System.out( 6781): AsyncTask #1 calls detatch()
,I/SA      ( 6781): [ODM] saveOpenData( GEO_IP, PL )
,I/SA      ( 6781): [OCP] update openData : PL
,I/SA      ( 6781): [TPMU] getNetworkMcc : 
,I/SA      ( 6781): [SCU] saveMccToPreferece Start
,I/SA      ( 6781): [SCU] RegionMCC : 260
I/SA      ( 6781): [SSP] query invoked
,I/SA      ( 6781): [TPMU] GetMccFromDB : null
,I/SA      ( 6781): [SCU] getMccFromPreferece mcc = 260
I/SA      ( 6781): [SCU] saveMccToPreferece End
,I/SA      ( 6781): [RC New] executeRequest [v2liruge] end. 729
I/SA      ( 6781): [RC New] Execute end
,I/SA      ( 6781): [OR] GetMyCountryZoneTask mcc = 260
,I/SA      ( 6781): [OR] GetMyCountryZoneTask Success
,E/LightSensor(  888): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  888): mCallbacks.updateBrightness()
,D/DisplayPowerController(  888): getFinalBrightness : 8 -> 8
,I/dhcpcd  ( 7936): wlan0: sending IPv6 Router Solicitation
E/dhcpcd  ( 7936): wlan0: sendmsg: Cannot assign requested address
,E/LightSensor(  888): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  888): mCallbacks.updateBrightness()
D/DisplayPowerController(  888): getFinalBrightness : 8 -> 8
,E/LightSensor(  888): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  888): mCallbacks.updateBrightness()
D/DisplayPowerController(  888): getFinalBrightness : 8 -> 8
,I/WifiStateMachine(  888): REQUEST_POWER_SAVE_ON
,E/WifiStateMachine(  888): CAPTIVE_PORTAL_EVENT_AUTHENTICATED
,E/ActivityManager(  888): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  888): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  888): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  888): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 8255): MountEmulatedStorage()
I/libpersona( 8255): KNOX_SDCARD checking this for 10012
E/Zygote  ( 8255): v2
I/libpersona( 8255): KNOX_SDCARD not a persona
,I/ActivityManager(  888): Start proc com.google.android.gms.wearable for service com.google.android.gms/.wearable.service.WearableService: pid=8255 uid=10012 gids={50012, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 3007} abi=armeabi-v7a
,I/SELinux ( 8255): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
I/SELinux ( 8255): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
E/SELinux ( 8255): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 8255): TimaSignature is unavailable
,D/ActivityThread( 8255): Added TimaKeyStore provider
,E/LightSensor(  888): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  888): mCallbacks.updateBrightness()
D/DisplayPowerController(  888): getFinalBrightness : 8 -> 8
,D/ResourcesManager( 7878): creating new AssetManager and set to /data/app/com.google.android.gms-1/base.apk
,W/ResourcesManager( 7878): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 7878): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,D/ResourcesManager( 8255): creating new AssetManager and set to /data/app/com.google.android.gms-1/base.apk
,I/GHttpClientFactory( 7878): Using the GMSCore's GoogleHttpClient
,W/ResourcesManager( 8255): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,W/ResourcesManager( 8255): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,I/MultiDex( 8255): VM with version 2.1.0 has multidex support
I/MultiDex( 8255): install
I/MultiDex( 8255): VM has multidex support, MultiDex support library is disabled.
,V/JNIHelp ( 8255): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
,I/MusicLeanback( 7878): Conditions not met for autocaching.
I/MusicLeanback( 7878): Stop autocaching.
,E/ActivityThread( 7878): Service com.google.android.music.download.TrackDownloadQueueService has leaked ServiceConnection com.google.android.gms.http.GoogleURLConnectionFactory$1@12fd62d1 that was originally bound here
E/ActivityThread( 7878): android.app.ServiceConnectionLeaked: Service com.google.android.music.download.TrackDownloadQueueService has leaked ServiceConnection com.google.android.gms.http.GoogleURLConnectionFactory$1@12fd62d1 that was originally bound here
E/ActivityThread( 7878): 	at android.app.LoadedApk$ServiceDispatcher.<init>(LoadedApk.java:1134)
E/ActivityThread( 7878): 	at android.app.LoadedApk.getServiceDispatcher(LoadedApk.java:1028)
E/ActivityThread( 7878): 	at android.app.ContextImpl.bindServiceCommon(ContextImpl.java:2085)
E/ActivityThread( 7878): 	at android.app.ContextImpl.bindService(ContextImpl.java:2068)
E/ActivityThread( 7878): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:559)
E/ActivityThread( 7878): 	at com.google.android.gms.http.GoogleURLConnectionFactory.<init>(Unknown Source)
E/ActivityThread( 7878): 	at com.google.android.gms.http.GoogleHttpClient.<init>(Unknown Source)
E/ActivityThread( 7878): 	at com.google.android.gms.http.GoogleHttpClient.<init>(Unknown Source)
E/ActivityThread( 7878): 	at com.google.android.gms.http.GoogleHttpClient.<init>(Unknown Source)
E/ActivityThread( 7878): 	at com.google.android.music.GoogleHttpClientFactory.createGoogleHttpClient(GoogleHttpClientFactory.java:81)
E/ActivityThread( 7878): 	at com.google.android.music.cloudclient.MusicRequest.createHttpClient(MusicRequest.java:110)
E/ActivityThread( 7878): 	at com.google.android.music.cloudclient.MusicRequest.getSharedHttpClient(MusicRequest.java:100)
E/ActivityThread( 7878): 	at com.google.android.music.download.BaseDownloadQueueManager.<init>(BaseDownloadQueueManager.java:110)
E/ActivityThread( 7878): 	at com.google.android.music.download.TrackDownloadQueueManager.<init>(TrackDownloadQueueManager.java:10)
E/ActivityThread( 7878): 	at com.google.android.music.download.TrackDownloadQueueService.onCreate(TrackDownloadQueueService.java:25)
E/ActivityThread( 7878): 	at android.app.ActivityThread.handleCreateService(ActivityThread.java:3100)
E/ActivityThread( 7878): 	at android.app.ActivityThread.access$1900(ActivityThread.java:172)
E/ActivityThread( 7878): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1505)
E/ActivityThread( 7878): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/ActivityThread( 7878): 	at android.os.Looper.loop(Looper.java:145)
E/ActivityThread( 7878): 	at android.app.ActivityThread.main(ActivityThread.java:5832)
E/ActivityThread( 7878): 	at java.lang.reflect.Method.invoke(Native Method)
E/ActivityThread( 7878): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/ActivityThread( 7878): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
E/ActivityThread( 7878): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
,W/ActivityThread( 8255): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
W/System  ( 8255): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@b0ed2b4: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 8255): Installed default security provider GmsCore_OpenSSL
D/GCM     ( 1714): GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
D/AuthorizationBluetoothService( 1714): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
E/LightSensor(  888): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
D/AutomaticBrightnessController(  888): mCallbacks.updateBrightness()
D/DisplayPowerController(  888): getFinalBrightness : 8 -> 8
,V/GmsCoreStatsServiceLauncher( 2467): Received broadcast intent Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.common.stats.GmsCoreStatsServiceLauncher }
,D/WearableService( 8255): callingUid 10012, callindPid: 8255
,D/WearableClient( 7878): WearableClientImpl.onPostInitHandler: done
,E/MDM     ( 2250): [246] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
,D/LocationInitializer( 2467): Restart initialization of location
,D/WearableClient( 7878): WearableClientImpl.onPostInitHandler: done
,D/WearableClient( 7878): WearableClientImpl.onPostInitHandler: done
,D/WearableClient( 7878): WearableClientImpl.onPostInitHandler: done
,E/GmsUtils( 7878): Failed to connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
,E/GmsUtils( 7878): Failed to connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
,V/AlarmManager(  888): waitForAlarm result :8
,E/LightSensor(  888): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  888): mCallbacks.updateBrightness()
D/DisplayPowerController(  888): getFinalBrightness : 8 -> 8
,D/ConnectivityService(  888): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/GLSUser ( 1714): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.googlequicksearchbox, service: oauth2:https://www.googleapis.com/auth/googlenow
,I/GLSUser ( 1714): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/googlenow without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1714): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1714): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1714): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ResourcesManager( 1714): creating new AssetManager and set to /system/priv-app/Velvet/Velvet.apk
,V/BitmapFactory( 1714): DecodeImagePath(decodeResourceStream3) : res/mipmap-xxhdpi-v4/ic_launcher_google_search.png
,V/BitmapFactory( 1714): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  888): uri = 14 selection = getSealedState
,D/SecContentProvider2(  888): mCursor = null
D/SecContentProvider2(  888): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  888): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
V/ApplicationPolicy(  888): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,W/Search.LoginHelper( 1569): User recoverable exception for scope: oauth2:https://www.googleapis.com/auth/googlenow
,D/StatusBar( 1171): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,I/PhoneStatusBar( 1171): Icon Only
D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
D/PanelView( 1171): There is/are notification(s) 
,D/PanelView( 1171): There is/are notification(s) 
,E/SMD     (  289): DCD ON
,E/LightSensor(  888): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  888): mCallbacks.updateBrightness()
D/DisplayPowerController(  888): getFinalBrightness : 8 -> 8
,E/LightSensor(  888): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  888): mCallbacks.updateBrightness()
,D/DisplayPowerController(  888): getFinalBrightness : 8 -> 8
,E/WifiStateMachine(  888): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: [192.168.1.135/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576} new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.135/24,fe80::ee1f:72ff:fe18:8b78/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0}
,D/ConnectivityService(  888): Update of LinkProperties for NetworkAgentInfo [WIFI () - 503]; created=true
,D/ConnectivityService(  888): updateLinkProperties: newLp = {InterfaceName: wlan0 LinkAddresses: [192.168.1.135/24,fe80::ee1f:72ff:fe18:8b78/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}
,D/ConnectivityService(  888): identical MTU - not setting
D/ConnectivityService(  888): updateSourceRoutes : add source routing for type : 1
D/ConnectivityService(  888): updateSourceRoutes : add src route for:fe80::ee1f:72ff:fe18:8b78
,V/        (  283): QcRouteController
,E/WifiStateMachine(  888): updateLinkProperties nid: 0 state: CONNECTED reason: CMD_UPDATE_LINKPROPERTIES v4 v4r v4dns isprov
,D/SmartBondingService(  888): SmartBondingReceiver: onReceive action=android.net.wifi.LINK_CONFIGURATION_CHANGED
,D/ConnectivityService(  888): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SmartBondingService(  888): EVENT_UPDATE_SB_STATE called / mDisableBySIOP false
,D/SmartBondingService(  888): getSBEnabled() enabled =false
D/SmartBondingService(  888): getSBEnabled() enabled =false
,D/SmartBondingService(  888): getSBEnabled() enabled =false
,V/        (  283): QcRouteController
,W/NetworkManagementService(  888): route cmd failed: 
W/NetworkManagementService(  888): com.android.server.NativeDaemonConnector$NativeDaemonFailureException: command '72 route replace src v6 wlan0 fe80::ee1f:72ff:fe18:8b78 2 ::' failed with '400 72 -6 route replace default via :: dev wlan0 scope global table 2: RTNETLINK answers: Invalid argument
W/NetworkManagementService(  888): '
W/NetworkManagementService(  888): 	at com.android.server.NativeDaemonConnector.execute(NativeDaemonConnector.java:438)
W/NetworkManagementService(  888): 	at com.android.server.NativeDaemonConnector.executeForList(NativeDaemonConnector.java:371)
W/NetworkManagementService(  888): 	at com.android.server.NativeDaemonConnector.execute(NativeDaemonConnector.java:336)
W/NetworkManagementService(  888): 	at com.android.server.NativeDaemonConnector.execute(NativeDaemonConnector.java:321)
W/NetworkManagementService(  888): 	at com.android.server.NetworkManagementService.replaceSrcRoute(NetworkManagementService.java:2812)
W/NetworkManagementService(  888): 	at com.android.server.ConnectivityService.updateSourceRoutes(ConnectivityService.java:5478)
W/NetworkManagementService(  888): 	at com.android.server.ConnectivityService.updateLinkProperties(ConnectivityService.java:5305)
W/NetworkManagementService(  888): 	at com.android.server.ConnectivityService.access$1800(ConnectivityService.java:230)
W/NetworkManagementService(  888): 	at com.android.server.ConnectivityService$NetworkStateTrackerHandler.handleMessage(ConnectivityService.java:2324)
W/NetworkManagementService(  888): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/NetworkManagementService(  888): 	at android.os.Looper.loop(Looper.java:145)
W/NetworkManagementService(  888): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,D/Nat464Xlat(  888): requiresClat: netType=1, connected=true, hasIPv4Address=true
D/ConnectivityService(  888): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 503]
D/ConnectivityService(  888): calling update connectivity
,D/ConnectivityService(  888):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,D/ConnectivityService(  888):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
,D/ConnectivityService(  888): sending notification IP_CHANGED for NetworkRequest [ id=2, legacyType=-1, [] ]
,D/ConnectivityManager.CallbackHandler( 1171): CM callback handler got msg 524295
,I/jxcore-log( 7760): Test app app.js loaded
I/jxcore-log( 7760): 
,D/ConnectivityService(  888): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 503]
,D/ConnectivityService(  888): calling update connectivity
D/ConnectivityService(  888):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,D/ConnectivityService(  888):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
,D/ConnectivityService(  888): sending notification IP_CHANGED for NetworkRequest [ id=2, legacyType=-1, [] ]
,D/ConnectivityManager.CallbackHandler( 1171): CM callback handler got msg 524295
,I/chromium( 7760): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,I/Choreographer( 7760): Skipped 437 frames!  The application may be doing too much work on its main thread.
,I/chromium( 7760): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
,E/LightSensor(  888): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  888): mCallbacks.updateBrightness()
D/DisplayPowerController(  888): getFinalBrightness : 8 -> 8
,I/WifiStateMachine(  888): CMD_RSSI_POLL : calculateWifiScore in!
,I/WifiStateMachine(  888): CMD_RSSI_POLL : calculateWifiScore out!
,I/WifiStateMachine(  888): CMD_RSSI_POLL : out!
,D/ConnectivityService(  888): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/LightSensor(  888): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  888): mCallbacks.updateBrightness()
D/DisplayPowerController(  888): getFinalBrightness : 8 -> 8
,D/ConnectivityService(  888): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/LightSensor(  888): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  888): mCallbacks.updateBrightness()
,D/DisplayPowerController(  888): getFinalBrightness : 8 -> 8
,D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
,D/PowerManagerService(  888): [api] [s] userActivity : event: 0 flags: 0 (uid: 1000 pid: 888) eventTime = 107259
,D/PowerManagerService(  888): [s] UserActivityState : 2 -> 1
,D/PowerManagerService(  888): [api] release WakeLock flags=0x2000000a tag=WindowManager uid=1000 pid=888 (0x0)
D/PowerManagerService(  888): [api] applyWakeLockFlagsOnReleaseLocked : userActivityNoUpdateLocked is called : SCREEN_BRIGHT_WAKE_LOCK        'WindowManager' ON_AFTER_RELEASE (uid=1000, pid=888, ws=WorkSource{10059}) (elapsedTime=3473)
,D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1171): value : false
,D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1171): value : false
,D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1171): value : false
,D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1171): value : false
,I/GAV4    ( 8041): Thread[GAThread,5,main]: No campaign data found.
,D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1171): value : false
,E/LightSensor(  888): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  888): mCallbacks.updateBrightness()
D/DisplayPowerController(  888): getFinalBrightness : 8 -> 8
,D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1171): value : false
,D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1171): value : false
,D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1171): value : false
,D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode(),
D/LockPatternUtilsCache( 1171): value : false
,D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1171): value : false
,D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
,D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1171): value : false
,D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1171): value : false
,D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1171): value : false
,D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1171): value : false
,E/LightSensor(  888): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  888): mCallbacks.updateBrightness()
,D/DisplayPowerController(  888): getFinalBrightness : 8 -> 8
,D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
,D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
,D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
,D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
,D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
,D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
,D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
,D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1171): value : false
,D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1171): value : false
,D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1171): value : false
,I/Atfwd_Sendcmd(  360): AtCmdFwd service not ready - Exhausted retry attempts - :6
,I/Atfwd_Daemon(  360): result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
,E/LightSensor(  888): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  888): mCallbacks.updateBrightness()
,D/DisplayPowerController(  888): getFinalBrightness : 8 -> 8
,D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode(),
,D/LockPatternUtilsCache( 1171): value : false
,D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
,D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
,D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
,D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
,D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
,D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
,D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
,I/SurfaceFlinger(  249): id=16 Removed Toast (8/8)
,I/SurfaceFlinger(  249): id=16 Removed Toast (-2/8)
,D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
,D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
,D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
,E/LightSensor(  888): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  888): mCallbacks.updateBrightness()
D/DisplayPowerController(  888): getFinalBrightness : 8 -> 8
,E/LightSensor(  888): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  888): mCallbacks.updateBrightness()
,D/DisplayPowerController(  888): getFinalBrightness : 8 -> 8
,E/LightSensor(  888): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  888): mCallbacks.updateBrightness()
,D/DisplayPowerController(  888): getFinalBrightness : 8 -> 8
,E/LightSensor(  888): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  888): mCallbacks.updateBrightness()
,D/DisplayPowerController(  888): getFinalBrightness : 8 -> 8
,E/LightSensor(  888): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  888): mCallbacks.updateBrightness()
,D/DisplayPowerController(  888): getFinalBrightness : 8 -> 8
,I/PCWCLIENTTRACE_SYSTEMReceiver( 7858): mConnectivityHandler : connected
,E/LightSensor(  888): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
D/AutomaticBrightnessController(  888): mCallbacks.updateBrightness()
D/DisplayPowerController(  888): getFinalBrightness : 8 -> 8
,D/ConnectivityService(  888): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,W/PCWCLIENTTRACE_AccountUtil( 7858): [hasSamungAccount] - No Samsung Account
,I/CSTORAGE( 7858): ================================================
,I/CSTORAGE( 7858):  CSTORAGE_SKM_LIB, v1.0.22, MSM8974|MSM8x26|MSM8x10
I/CSTORAGE( 7858): ================================================
,I/PCWCLIENTTRACE_SecurePreferencesJNI( 7858): [GetString-S]
E/art     ( 7858): No implementation found for java.lang.String com.sec.pcw.device.util.SecurePreferencesJNI.getString() (tried Java_com_sec_pcw_device_util_SecurePreferencesJNI_getString and Java_com_sec_pcw_device_util_SecurePreferencesJNI_getString__)
,W/PCWCLIENTTRACE_SecurePreferencesJNI( 7858): GetString : secure API is not supported!! No implementation found for java.lang.String com.sec.pcw.device.util.SecurePreferencesJNI.getString() (tried Java_com_sec_pcw_device_util_SecurePreferencesJNI_getString and Java_com_sec_pcw_device_util_SecurePreferencesJNI_getString__)
I/PCWCLIENTTRACE_SecurePreferencesJNI( 7858): [GetString-E]
,I/PCWCLIENTTRACE_PushUtil( 7858): SPPPushClient is installed : true
,I/PCWCLIENTTRACE_PushUtil( 7858): sales region : global
I/PCWCLIENTTRACE_PushUtil( 7858): getPushTypeList : [SPP, GCM]
E/PCWCLIENTTRACE_PCWHandler( 7858): [ensureRegistration] - No Samsung account
,E/LightSensor(  888): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  888): mCallbacks.updateBrightness()
,D/DisplayPowerController(  888): getFinalBrightness : 8 -> 8
,E/LightSensor(  888): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  888): mCallbacks.updateBrightness()
,D/DisplayPowerController(  888): getFinalBrightness : 8 -> 8
,E/LightSensor(  888): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  888): mCallbacks.updateBrightness()
,D/DisplayPowerController(  888): getFinalBrightness : 8 -> 8
,E/SMD     (  289): DCD ON
,I/dhcpcd  ( 7936): wlan0: sending IPv6 Router Solicitation
,E/LightSensor(  888): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
D/AutomaticBrightnessController(  888): mCallbacks.updateBrightness()
D/DisplayPowerController(  888): getFinalBrightness : 8 -> 8
,E/LightSensor(  888): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  888): mCallbacks.updateBrightness()
,D/DisplayPowerController(  888): getFinalBrightness : 8 -> 8
,D/SSRM:m  (  888): SIOP:: AP = 410, PST = 418, CUR = 300
,E/LightSensor(  888): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  888): mCallbacks.updateBrightness()
D/DisplayPowerController(  888): getFinalBrightness : 8 -> 8
,I/WifiStateMachine(  888): CMD_RSSI_POLL : calculateWifiScore in!
,I/WifiStateMachine(  888): CMD_RSSI_POLL : calculateWifiScore out!
I/WifiStateMachine(  888): CMD_RSSI_POLL : out!
,E/LightSensor(  888): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  888): mCallbacks.updateBrightness()
,D/DisplayPowerController(  888): getFinalBrightness : 8 -> 8
,E/LightSensor(  888): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  888): mCallbacks.updateBrightness()
,D/DisplayPowerController(  888): getFinalBrightness : 8 -> 8
,E/LightSensor(  888): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  888): mCallbacks.updateBrightness()
,D/DisplayPowerController(  888): getFinalBrightness : 8 -> 8
,E/LightSensor(  888): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  888): mCallbacks.updateBrightness()
,D/DisplayPowerController(  888): getFinalBrightness : 8 -> 8
,E/LightSensor(  888): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  888): mCallbacks.updateBrightness()
,D/DisplayPowerController(  888): getFinalBrightness : 8 -> 8
,E/LightSensor(  888): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  888): mCallbacks.updateBrightness()
,D/DisplayPowerController(  888): getFinalBrightness : 8 -> 8
,E/LightSensor(  888): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  888): mCallbacks.updateBrightness()
,D/DisplayPowerController(  888): getFinalBrightness : 8 -> 8
,I/ActivityManager(  888): Killing 7419:com.samsung.android.scloud.sync/u0a67 (adj 15): bgCount ##41
,W/libprocessgroup(  888): failed to open /acct/uid_10067/pid_7419/cgroup.procs: No such file or directory
,E/LightSensor(  888): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  888): mCallbacks.updateBrightness()
,D/DisplayPowerController(  888): getFinalBrightness : 8 -> 8
,E/LightSensor(  888): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  888): mCallbacks.updateBrightness(),
D/DisplayPowerController(  888): getFinalBrightness : 8 -> 8
,E/LightSensor(  888): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  888): mCallbacks.updateBrightness()
,D/DisplayPowerController(  888): getFinalBrightness : 8 -> 8
,E/LightSensor(  888): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  888): mCallbacks.updateBrightness()
,D/DisplayPowerController(  888): getFinalBrightness : 8 -> 8
,E/LightSensor(  888): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  888): mCallbacks.updateBrightness()
,D/DisplayPowerController(  888): getFinalBrightness : 8 -> 8
,E/LightSensor(  888): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  888): mCallbacks.updateBrightness()
,D/DisplayPowerController(  888): getFinalBrightness : 8 -> 8
,W/ContextImpl(  888): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/LightSensor(  888): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  888): mCallbacks.updateBrightness()
,D/DisplayPowerController(  888): getFinalBrightness : 8 -> 8
E/SMD     (  289): DCD ON
,D/StatusBar.NetworkController( 1171): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02012b/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020464/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
,D/StatusBar.NetworkController( 1171): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1171): applyOpen
,D/StatusBar.NetworkController( 1171): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1171): applyOpen
,D/StatusBar.NetworkController( 1171): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1171): applyOpen
D/StatusBar.NetworkController( 1171): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1171): applyOpen
,E/LightSensor(  888): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  888): mCallbacks.updateBrightness()
D/DisplayPowerController(  888): getFinalBrightness : 8 -> 8
,I/ServiceManager(  360): Waiting for service AtCmdFwd...
,E/LightSensor(  888): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  888): mCallbacks.updateBrightness()
,D/DisplayPowerController(  888): getFinalBrightness : 8 -> 8
,E/LightSensor(  888): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  888): mCallbacks.updateBrightness()
D/DisplayPowerController(  888): getFinalBrightness : 8 -> 8
,I/WifiStateMachine(  888): CMD_RSSI_POLL : calculateWifiScore in!
,I/WifiStateMachine(  888): CMD_RSSI_POLL : calculateWifiScore out!
I/WifiStateMachine(  888): CMD_RSSI_POLL : out!
,E/LightSensor(  888): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  888): mCallbacks.updateBrightness()
,D/DisplayPowerController(  888): getFinalBrightness : 8 -> 8
,E/LightSensor(  888): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  888): mCallbacks.updateBrightness()
,D/DisplayPowerController(  888): getFinalBrightness : 8 -> 8
,I/dhcpcd  ( 7936): wlan0: sending IPv6 Router Solicitation
,E/LightSensor(  888): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,I/dhcpcd  ( 7936): wlan0: no IPv6 Routers available
,D/AutomaticBrightnessController(  888): mCallbacks.updateBrightness()
,D/DisplayPowerController(  888): getFinalBrightness : 8 -> 8
,D/StatusBar.NetworkController( 1171): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02012b/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020466/com.android.systemui:drawable/stat_sys_signal_inout mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
D/StatusBar.NetworkController( 1171): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1171): applyOpen
,D/StatusBar.NetworkController( 1171): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1171): applyOpen
D/StatusBar.NetworkController( 1171): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1171): applyOpen
,D/StatusBar.NetworkController( 1171): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1171): applyOpen
,E/LightSensor(  888): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  888): mCallbacks.updateBrightness()
,D/DisplayPowerController(  888): getFinalBrightness : 8 -> 8
,I/ServiceManager(  360): Waiting for service AtCmdFwd...
,D/PreloadUpdateManagerStateMachine( 8210): execute::IDLE:EXECUTE
,D/PreloadUpdateManagerStateMachine( 8210): exit::IDLE
,D/PreloadUpdateManagerStateMachine( 8210): entry::CHECK_TIMEOUT_FOR_UPDATE
,D/hcjo    ( 8210): AutoUpdateTriggerManager:IDLE:notifyNextTime
,D/PreloadUpdateManagerStateMachine( 8210): execute::CHECK_TIMEOUT_FOR_UPDATE:NO_TIMED_OUT
,D/PreloadUpdateManagerStateMachine( 8210): exit::CHECK_TIMEOUT_FOR_UPDATE
,D/PreloadUpdateManagerStateMachine( 8210): entry::IDLE
,E/LightSensor(  888): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  888): mCallbacks.updateBrightness()
D/DisplayPowerController(  888): getFinalBrightness : 8 -> 8
,E/LightSensor(  888): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  888): mCallbacks.updateBrightness()
,D/DisplayPowerController(  888): getFinalBrightness : 8 -> 8
,D/PreloadUpdateManagerStateMachine( 8210): execute::IDLE:EXECUTE
,D/PreloadUpdateManagerStateMachine( 8210): exit::IDLE
,D/PreloadUpdateManagerStateMachine( 8210): entry::CHECK_TIMEOUT_FOR_UPDATE
,D/hcjo    ( 8210): AutoUpdateTriggerManager:IDLE:notifyNextTime
,D/PreloadUpdateManagerStateMachine( 8210): execute::CHECK_TIMEOUT_FOR_UPDATE:NO_TIMED_OUT
,D/PreloadUpdateManagerStateMachine( 8210): exit::CHECK_TIMEOUT_FOR_UPDATE
D/PreloadUpdateManagerStateMachine( 8210): entry::IDLE
,E/LightSensor(  888): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  888): mCallbacks.updateBrightness()
,D/DisplayPowerController(  888): getFinalBrightness : 8 -> 8
,E/LightSensor(  888): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  888): mCallbacks.updateBrightness()
,D/DisplayPowerController(  888): getFinalBrightness : 8 -> 8
,D/FactoryTest( 6443): Not factory mode
,D/FactoryTest( 6443): Not factory mode. isFactoryMode() returend false
,D/MTPRx   ( 6443): DRIVER_TIME_OUT 60s lapsed
D/MTPRx   ( 6443): still no open session command from host, so toast
,W/ContextImpl( 6443): Calling a method in the system process without a qualified user: android.app.ContextImpl.startActivity:1526 android.content.ContextWrapper.startActivity:337 android.content.ContextWrapper.startActivity:337 com.samsung.android.MtpApplication.MtpReceiver$3.handleMessage:713 android.os.Handler.dispatchMessage:102 
,W/ContextImpl( 6443): Calling a method in the system process without a qualified user: android.app.ContextImpl.startActivity:1538 android.app.ContextImpl.startActivity:1527 android.content.ContextWrapper.startActivity:337 android.content.ContextWrapper.startActivity:337 com.samsung.android.MtpApplication.MtpReceiver$3.handleMessage:713 
,I/Timeline( 6443): Timeline: Activity_launch_request id:com.android.settings time:114488
,E/PersonaManagerService(  888): inState():  stateMachine is null !!
,V/ApplicationPolicy(  888): isApplicationStateBlocked userId 0 pkgname com.android.settings
,I/ActivityManager(  888): START u0 {flg=0x10000000 cmp=com.android.settings/.SettingsReceiverActivity} from uid 1000 on display 0
,D/CustomFrequencyManagerService(  888): acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1958400  uid : 1000  pid : 888  pkgName : ACTIVITY_RESUME_BOOSTER@6
,W/ActivityManager(  888): mDVFSHelper.acquire()
,D/StatusBar.NetworkController( 1171): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02012b/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020464/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
D/StatusBar.NetworkController( 1171): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1171): applyOpen
,D/StatusBar.NetworkController( 1171): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1171): applyOpen
,D/StatusBar.NetworkController( 1171): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1171): applyOpen
,D/StatusBar.NetworkController( 1171): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1171): applyOpen
,E/LightSensor(  888): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  888): mCallbacks.updateBrightness()
D/DisplayPowerController(  888): getFinalBrightness : 8 -> 8
,D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1171): value : false
D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
E/MTPRx   ( 6443): started activity for popup
,D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
,I/SQLiteSecureOpenHelper( 3592): getWritableDatabase(pwd)
I/SQLiteSecureOpenHelper( 3592): getDatabaseLocked(b,b,pwd)...
,D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
,D/ConnectivityService(  888): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1171): value : false
,D/ResourcesManager( 6443): creating new AssetManager and set to /system/priv-app/SecSettings/SecSettings.apk
,W/ResourcesManager( 6443): Asset path '/system/framework/sec_platform_library.jar' does not exist or contains no resources.
,W/ResourcesManager( 6443): Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
W/ResourcesManager( 6443): Asset path '/system/framework/secvisualeffect.jar' does not exist or contains no resources.
W/ResourcesManager( 6443): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 6443): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 6443): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 6443): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,E/SettingsReceiverActivity( 6443): PREF_DONT_ASK_AGAIN : true
,D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1171): value : false
D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
,E/ActivityManager(  888): Invalid thumbnail dimensions: 576x576
,D/InputMethodManagerService(  888): windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,W/InputMethodManagerService(  888): Window already focused, ignoring focus gain of: com.android.internal.view.IInputMethodClient$Stub$Proxy@33332cd8 attribute=null, token = android.os.BinderProxy@203d1647
,I/SQLiteSecureOpenHelper( 3592): getWritableDatabase(pwd)
I/SQLiteSecureOpenHelper( 3592): getDatabaseLocked(b,b,pwd)...
,D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
,V/BitmapFactory( 6443): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_015.png
,V/BitmapFactory( 6443): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_000.png
V/BitmapFactory( 6443): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_015.png
V/BitmapFactory( 6443): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_000.png
,V/BitmapFactory( 6443): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_000.png
,V/BitmapFactory( 6443): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_001.png
,V/BitmapFactory( 6443): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_002.png
,V/BitmapFactory( 6443): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_003.png
,V/BitmapFactory( 6443): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_004.png
,V/BitmapFactory( 6443): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_005.png
,V/BitmapFactory( 6443): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_006.png
,V/BitmapFactory( 6443): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_007.png
,V/BitmapFactory( 6443): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_008.png
,V/BitmapFactory( 6443): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_010.png
,V/BitmapFactory( 6443): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_011.png
,V/BitmapFactory( 6443): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_012.png
,V/BitmapFactory( 6443): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_013.png
,V/BitmapFactory( 6443): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_014.png
,V/BitmapFactory( 6443): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_015.png
,V/BitmapFactory( 6443): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_000.png
,V/BitmapFactory( 6443): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_001.png
,V/BitmapFactory( 6443): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_002.png
,V/BitmapFactory( 6443): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_003.png
,V/BitmapFactory( 6443): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_004.png
,V/BitmapFactory( 6443): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_005.png
,V/BitmapFactory( 6443): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_006.png
,V/BitmapFactory( 6443): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_007.png
,V/BitmapFactory( 6443): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_008.png
,V/BitmapFactory( 6443): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_010.png
,V/BitmapFactory( 6443): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_011.png
,V/BitmapFactory( 6443): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_012.png
,V/BitmapFactory( 6443): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_013.png
,V/BitmapFactory( 6443): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_014.png
,V/BitmapFactory( 6443): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_015.png
,D/SettingsReceiverActivity( 6443): dev.kiessupport is : TRUE
,E/LightSensor(  888): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  888): mCallbacks.updateBrightness()
D/DisplayPowerController(  888): getFinalBrightness : 8 -> 8
,I/ServiceManager(  360): Waiting for service AtCmdFwd...
,D/Activity( 6443): performCreate Call secproduct feature valuefalse
D/Activity( 6443): performCreate Call debug elastic valuetrue
,D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1171): value : false
D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
,D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1171): value : false
D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
,D/ActivityManager(  888): post active user change for 0
D/KnoxTimeoutHandler(  888): postActiveUserChange for user 0
,D/KnoxTimeoutHandler(  888): handleActiveUserChange for user 0
,D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1171): value : false
,D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1171): value : false
D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
,I/Timeline( 7760): Timeline: Activity_idle id: android.os.BinderProxy@a41e024 time:114732
,D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1171): value : false
,E/LightSensor(  888): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  888): mCallbacks.updateBrightness()
D/DisplayPowerController(  888): getFinalBrightness : 8 -> 8
,D/ConnectivityService(  888): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/LightSensor(  888): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  888): mCallbacks.updateBrightness()
D/DisplayPowerController(  888): getFinalBrightness : 8 -> 8
,E/LightSensor(  888): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  888): mCallbacks.updateBrightness()
D/DisplayPowerController(  888): getFinalBrightness : 8 -> 8
,E/SMD     (  289): DCD ON
,E/LightSensor(  888): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  888): mCallbacks.updateBrightness()
D/DisplayPowerController(  888): getFinalBrightness : 8 -> 8
,D/StatusBar.NetworkController( 1171): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02012b/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020466/com.android.systemui:drawable/stat_sys_signal_inout mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
,D/StatusBar.NetworkController( 1171): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1171): applyOpen
,D/StatusBar.NetworkController( 1171): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1171): applyOpen
D/StatusBar.NetworkController( 1171): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1171): applyOpen
D/StatusBar.NetworkController( 1171): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1171): applyOpen
,E/LightSensor(  888): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  888): mCallbacks.updateBrightness()
D/DisplayPowerController(  888): getFinalBrightness : 8 -> 8
,I/ServiceManager(  360): Waiting for service AtCmdFwd...
,E/LightSensor(  888): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  888): mCallbacks.updateBrightness()
D/DisplayPowerController(  888): getFinalBrightness : 8 -> 8
,E/LightSensor(  888): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  888): mCallbacks.updateBrightness()
D/DisplayPowerController(  888): getFinalBrightness : 8 -> 8
,I/WifiStateMachine(  888): CMD_RSSI_POLL : calculateWifiScore in!
,I/WifiStateMachine(  888): CMD_RSSI_POLL : calculateWifiScore out!
I/WifiStateMachine(  888): CMD_RSSI_POLL : out!
,E/LightSensor(  888): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  888): mCallbacks.updateBrightness()
D/DisplayPowerController(  888): getFinalBrightness : 8 -> 8
,E/LightSensor(  888): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  888): mCallbacks.updateBrightness()
D/DisplayPowerController(  888): getFinalBrightness : 8 -> 8
,E/LightSensor(  888): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  888): mCallbacks.updateBrightness()
D/DisplayPowerController(  888): getFinalBrightness : 8 -> 8
,D/StatusBar.NetworkController( 1171): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02012b/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020468/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
,D/StatusBar.NetworkController( 1171): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1171): applyOpen
D/StatusBar.NetworkController( 1171): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1171): applyOpen
D/StatusBar.NetworkController( 1171): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1171): applyOpen
D/StatusBar.NetworkController( 1171): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1171): applyOpen
,E/LightSensor(  888): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  888): mCallbacks.updateBrightness()
D/DisplayPowerController(  888): getFinalBrightness : 8 -> 8
,I/ServiceManager(  360): Waiting for service AtCmdFwd...
,E/LightSensor(  888): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  888): mCallbacks.updateBrightness()
D/DisplayPowerController(  888): getFinalBrightness : 8 -> 8
,E/LightSensor(  888): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  888): mCallbacks.updateBrightness()
D/DisplayPowerController(  888): getFinalBrightness : 8 -> 8
,E/LightSensor(  888): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  888): mCallbacks.updateBrightness()
D/DisplayPowerController(  888): getFinalBrightness : 8 -> 8
,E/LightSensor(  888): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  888): mCallbacks.updateBrightness()
D/DisplayPowerController(  888): getFinalBrightness : 8 -> 8
,D/CustomFrequencyManagerService(  888): releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1958400  uid : 1000  pid : 888  tag : ACTIVITY_RESUME_BOOSTER@6
,W/ActivityManager(  888): mDVFSHelper.release()
,D/CustomFrequencyManagerService(  888): acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1958400  uid : 1000  pid : 888  pkgName : ACTIVITY_RESUME_BOOSTER@10
,D/StatusBar.NetworkController( 1171): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02012b/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020464/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
,D/StatusBar.NetworkController( 1171): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1171): applyOpen
D/StatusBar.NetworkController( 1171): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1171): applyOpen
D/StatusBar.NetworkController( 1171): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1171): applyOpen
D/StatusBar.NetworkController( 1171): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1171): applyOpen
,E/LightSensor(  888): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  888): mCallbacks.updateBrightness()
D/DisplayPowerController(  888): getFinalBrightness : 8 -> 8
,W/Atfwd_Sendcmd(  360): AtCmdFwd service not published, waiting... retryCnt : 1
,E/LightSensor(  888): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  888): mCallbacks.updateBrightness()
D/DisplayPowerController(  888): getFinalBrightness : 8 -> 8
,D/CustomFrequencyManagerService(  888): releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1958400  uid : 1000  pid : 888  tag : ACTIVITY_RESUME_BOOSTER@10
,E/LightSensor(  888): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  888): mCallbacks.updateBrightness()
,D/DisplayPowerController(  888): getFinalBrightness : 8 -> 8
,E/LightSensor(  888): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560,
D/AutomaticBrightnessController(  888): mCallbacks.updateBrightness()
,D/DisplayPowerController(  888): getFinalBrightness : 8 -> 8
,E/LightSensor(  888): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  888): mCallbacks.updateBrightness()
,D/DisplayPowerController(  888): getFinalBrightness : 8 -> 8
,E/SMD     (  289): DCD ON
,E/LightSensor(  888): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  888): mCallbacks.updateBrightness()
,D/DisplayPowerController(  888): getFinalBrightness : 8 -> 8
,D/StatusBar.NetworkController( 1171): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02012b/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020468/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
,D/StatusBar.NetworkController( 1171): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1171): applyOpen
,D/StatusBar.NetworkController( 1171): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1171): applyOpen
D/StatusBar.NetworkController( 1171): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1171): applyOpen
,D/StatusBar.NetworkController( 1171): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1171): applyOpen
,E/LightSensor(  888): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  888): mCallbacks.updateBrightness()
,D/DisplayPowerController(  888): getFinalBrightness : 8 -> 8
,E/LightSensor(  888): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  888): mCallbacks.updateBrightness()
,D/DisplayPowerController(  888): getFinalBrightness : 8 -> 8
,I/ActivityManager(  888): Waited long enough for: ServiceRecord{255f7373 u0 com.samsung.android.app.galaxyfinder/.tag.LocationTagReadyService}
,I/WifiStateMachine(  888): CMD_RSSI_POLL : calculateWifiScore in!
,I/WifiStateMachine(  888): CMD_RSSI_POLL : calculateWifiScore out!
E/LightSensor(  888): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
I/WifiStateMachine(  888): CMD_RSSI_POLL : out!
,D/AutomaticBrightnessController(  888): mCallbacks.updateBrightness()
,D/DisplayPowerController(  888): getFinalBrightness : 8 -> 8
,E/LightSensor(  888): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  888): mCallbacks.updateBrightness()
,D/DisplayPowerController(  888): getFinalBrightness : 8 -> 8
,E/LightSensor(  888): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  888): mCallbacks.updateBrightness()
,D/DisplayPowerController(  888): getFinalBrightness : 8 -> 8
,D/StatusBar.NetworkController( 1171): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02012b/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020464/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
,D/StatusBar.NetworkController( 1171): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1171): applyOpen
,D/StatusBar.NetworkController( 1171): refreshSignalCluster - setNWBoosterIndicators(false)
,E/LightSensor(  888): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  888): mCallbacks.updateBrightness()
,D/DisplayPowerController(  888): getFinalBrightness : 8 -> 8
D/StatusBar.NetworkController( 1171): applyOpen
,D/StatusBar.NetworkController( 1171): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1171): applyOpen
D/StatusBar.NetworkController( 1171): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1171): applyOpen
,E/LightSensor(  888): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  888): mCallbacks.updateBrightness()
D/DisplayPowerController(  888): getFinalBrightness : 8 -> 8
,D/SSRM:m  (  888): SIOP:: AP = 360, PST = 408, CUR = 300
D/X       (  888): broadcastSiopLevelIntent:: currentSiopLevel = -1
,E/ActivityManager(  888): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  888): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  888): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  888): checkUser: useridlist=null, currentuser=0
,D/ContentApp( 1224):  LEVEL : -1
,E/Zygote  ( 8331): MountEmulatedStorage()
,E/Zygote  ( 8331): v2
I/libpersona( 8331): KNOX_SDCARD checking this for 10054
I/libpersona( 8331): KNOX_SDCARD not a persona
I/ActivityManager(  888): Start proc com.sec.android.app.videoplayer for broadcast com.sec.android.app.videoplayer/.videowall.TranscodeReceiver: pid=8331 uid=10054 gids={50054, 9997, 3003, 3002, 1028, 1015, 1023} abi=armeabi-v7a
,I/SELinux ( 8331): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 8331): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 8331): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 8331): TimaSignature is unavailable
,D/ActivityThread( 8331): Added TimaKeyStore provider
,D/ResourcesManager( 8331): creating new AssetManager and set to /system/priv-app/SecVideoPlayer/SecVideoPlayer.apk
,W/ResourcesManager( 8331): Asset path '/system/framework/minimode.jar' does not exist or contains no resources.
,W/ResourcesManager( 8331): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
,W/ResourcesManager( 8331): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
,W/ResourcesManager( 8331): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,W/ResourcesManager( 8331): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
,E/LightSensor(  888): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  888): mCallbacks.updateBrightness()
,D/DisplayPowerController(  888): getFinalBrightness : 8 -> 8
,E/TranscodeReceiver( 8331): onReceive : android.intent.action.CHECK_SIOP_LEVEL
,D/videowall-Global( 8331): core_num = 4
,W/linker  ( 8331): libsthmb.so has text relocations. This is wasting memory and prevents security hardening. Please fix.
,W/linker  ( 8331): libvwengine.so has text relocations. This is wasting memory and prevents security hardening. Please fix.
,D/videowall-Global( 8331): density : 3.0 width : 1080 height : 1920 Raw width : 1080 Raw height : 1920
,D/videowall-Global( 8331): dsp : 1080, swkey : false, Cores : 4, Clock : 0
,D/TranscodeReceiver( 8331):  SIOP_LEVEL: -1
,I/ActivityManager(  888): Killing 7435:com.sec.android.app.clockpackage/u0a91 (adj 15): bgCount ##41
,W/libprocessgroup(  888): failed to open /acct/uid_10091/pid_7435/cgroup.procs: No such file or directory
,E/LightSensor(  888): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  888): mCallbacks.updateBrightness()
D/DisplayPowerController(  888): getFinalBrightness : 8 -> 8
,V/AlarmManager(  888): waitForAlarm result :4
,D/BatteryService(  888): level:100, scale:100, status:5, health:2, present:true, voltage: 4353, temperature: 284, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  888): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
D/BatteryService(  888): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  888):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  888): Plugged
I/MotionRecognitionService(  888): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1171): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1171): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1171):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3252): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3252): Disconnected process message: 10
,E/LightSensor(  888): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  888): mCallbacks.updateBrightness()
D/DisplayPowerController(  888): getFinalBrightness : 8 -> 8
,E/LightSensor(  888): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
D/AutomaticBrightnessController(  888): mCallbacks.updateBrightness()
D/DisplayPowerController(  888): getFinalBrightness : 8 -> 8
,V/GLSActivity( 1714): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/StatusBar.NetworkController( 1171): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02012b/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020466/com.android.systemui:drawable/stat_sys_signal_inout mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
,D/StatusBar.NetworkController( 1171): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1171): applyOpen
,D/StatusBar.NetworkController( 1171): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1171): applyOpen
D/StatusBar.NetworkController( 1171): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1171): applyOpen
,D/StatusBar.NetworkController( 1171): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1171): applyOpen
,I/GLSUser ( 1714): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
,I/GLSUser ( 1714): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1714): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1714): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1714): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/LightSensor(  888): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  888): mCallbacks.updateBrightness()
D/DisplayPowerController(  888): getFinalBrightness : 8 -> 8
,D/Finsky  ( 6627): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,D/Finsky  ( 6627): [1] 5.onFinished: Installation state replication failed.
D/Finsky  ( 6627): [1] 5.onFinished: Scheduling replication attempt 3.
,E/LightSensor(  888): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  888): mCallbacks.updateBrightness()
,D/DisplayPowerController(  888): getFinalBrightness : 8 -> 8
,E/LightSensor(  888): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  888): mCallbacks.updateBrightness()
,D/DisplayPowerController(  888): getFinalBrightness : 8 -> 8
,E/LightSensor(  888): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  888): mCallbacks.updateBrightness()
,D/DisplayPowerController(  888): getFinalBrightness : 8 -> 8
,E/LightSensor(  888): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  888): mCallbacks.updateBrightness()
,D/DisplayPowerController(  888): getFinalBrightness : 8 -> 8
,E/SMD     (  289): DCD ON
,E/LightSensor(  888): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  888): mCallbacks.updateBrightness()
,D/DisplayPowerController(  888): getFinalBrightness : 8 -> 8
,D/StatusBar.NetworkController( 1171): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02012b/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020464/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
,D/StatusBar.NetworkController( 1171): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1171): applyOpen
,D/StatusBar.NetworkController( 1171): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1171): applyOpen
,D/StatusBar.NetworkController( 1171): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1171): applyOpen
,D/StatusBar.NetworkController( 1171): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1171): applyOpen
,E/LightSensor(  888): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  888): mCallbacks.updateBrightness()
,D/DisplayPowerController(  888): getFinalBrightness : 8 -> 8
,E/LightSensor(  888): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  888): mCallbacks.updateBrightness()
,D/DisplayPowerController(  888): getFinalBrightness : 8 -> 8
,I/WifiStateMachine(  888): CMD_RSSI_POLL : calculateWifiScore in!
,I/WifiStateMachine(  888): CMD_RSSI_POLL : calculateWifiScore out!
I/WifiStateMachine(  888): CMD_RSSI_POLL : out!
,E/LightSensor(  888): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  888): mCallbacks.updateBrightness()
,D/DisplayPowerController(  888): getFinalBrightness : 8 -> 8
,V/AlarmManager(  888): waitForAlarm result :4
,E/LightSensor(  888): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  888): mCallbacks.updateBrightness()
,D/DisplayPowerController(  888): getFinalBrightness : 8 -> 8
,D/ConnectivityService(  888): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/LightSensor(  888): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
D/AutomaticBrightnessController(  888): mCallbacks.updateBrightness()
,D/DisplayPowerController(  888): getFinalBrightness : 8 -> 8
,E/LightSensor(  888): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  888): mCallbacks.updateBrightness()
,D/DisplayPowerController(  888): getFinalBrightness : 8 -> 8
,I/ServiceManager(  360): Waiting for service AtCmdFwd...
,E/LightSensor(  888): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  888): mCallbacks.updateBrightness()
,D/DisplayPowerController(  888): getFinalBrightness : 8 -> 8
,E/LightSensor(  888): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  888): mCallbacks.updateBrightness()
,D/DisplayPowerController(  888): getFinalBrightness : 8 -> 8
,E/LightSensor(  888): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  888): mCallbacks.updateBrightness()
,D/DisplayPowerController(  888): getFinalBrightness : 8 -> 8
,E/LightSensor(  888): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  888): mCallbacks.updateBrightness()
D/DisplayPowerController(  888): getFinalBrightness : 8 -> 8
,E/LightSensor(  888): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  888): mCallbacks.updateBrightness()
D/DisplayPowerController(  888): getFinalBrightness : 8 -> 8
,E/LightSensor(  888): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  888): mCallbacks.updateBrightness()
D/DisplayPowerController(  888): getFinalBrightness : 8 -> 8
,I/ServiceManager(  360): Waiting for service AtCmdFwd...
,E/LightSensor(  888): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  888): mCallbacks.updateBrightness()
D/DisplayPowerController(  888): getFinalBrightness : 8 -> 8
,V/AlarmManager(  888): waitForAlarm result :8
,D/KeyguardUpdateMonitor( 1171): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1171): handleTimeUpdate
,D/KeyguardEffectViewController( 1171): onReceive action : android.intent.action.TIME_TICK
,I/KeyguardEffectViewController( 1171): *** don't update sliding image ***
,D/DateView( 1171): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1171): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,E/LightSensor(  888): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  888): mCallbacks.updateBrightness()
D/DisplayPowerController(  888): getFinalBrightness : 8 -> 8
,E/LightSensor(  888): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  888): mCallbacks.updateBrightness()
,D/DisplayPowerController(  888): getFinalBrightness : 8 -> 8
,E/SMD     (  289): DCD ON
,E/LightSensor(  888): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  888): mCallbacks.updateBrightness()
,D/DisplayPowerController(  888): getFinalBrightness : 8 -> 8
,E/LightSensor(  888): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  888): mCallbacks.updateBrightness()
,D/DisplayPowerController(  888): getFinalBrightness : 8 -> 8
,I/ServiceManager(  360): Waiting for service AtCmdFwd...
,E/LightSensor(  888): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  888): mCallbacks.updateBrightness()
,D/DisplayPowerController(  888): getFinalBrightness : 8 -> 8
,E/LightSensor(  888): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  888): mCallbacks.updateBrightness()
,D/DisplayPowerController(  888): getFinalBrightness : 8 -> 8
,I/WifiStateMachine(  888): CMD_RSSI_POLL : calculateWifiScore in!
,I/WifiStateMachine(  888): CMD_RSSI_POLL : calculateWifiScore out!
,I/WifiStateMachine(  888): CMD_RSSI_POLL : out!
,E/LightSensor(  888): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  888): mCallbacks.updateBrightness()
,D/DisplayPowerController(  888): getFinalBrightness : 8 -> 8
,E/LightSensor(  888): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  888): mCallbacks.updateBrightness()
,D/DisplayPowerController(  888): getFinalBrightness : 8 -> 8
,E/LightSensor(  888): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  888): mCallbacks.updateBrightness()
,D/DisplayPowerController(  888): getFinalBrightness : 8 -> 8
,D/StatusBar.NetworkController( 1171): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02012b/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020466/com.android.systemui:drawable/stat_sys_signal_inout mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
,D/StatusBar.NetworkController( 1171): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1171): applyOpen
,D/StatusBar.NetworkController( 1171): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1171): applyOpen
,D/StatusBar.NetworkController( 1171): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1171): applyOpen
D/StatusBar.NetworkController( 1171): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1171): applyOpen
,E/LightSensor(  888): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  888): mCallbacks.updateBrightness()
D/DisplayPowerController(  888): getFinalBrightness : 8 -> 8
,I/ServiceManager(  360): Waiting for service AtCmdFwd...
,E/LightSensor(  888): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  888): mCallbacks.updateBrightness()
,D/DisplayPowerController(  888): getFinalBrightness : 8 -> 8
,E/LightSensor(  888): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  888): mCallbacks.updateBrightness()
D/DisplayPowerController(  888): getFinalBrightness : 8 -> 8
,E/LightSensor(  888): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  888): mCallbacks.updateBrightness()
,D/DisplayPowerController(  888): getFinalBrightness : 8 -> 8
,E/LightSensor(  888): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  888): mCallbacks.updateBrightness()
,D/DisplayPowerController(  888): getFinalBrightness : 8 -> 8
,E/LightSensor(  888): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  888): mCallbacks.updateBrightness()
D/DisplayPowerController(  888): getFinalBrightness : 8 -> 8
,D/StatusBar.NetworkController( 1171): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02012b/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020464/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
,D/StatusBar.NetworkController( 1171): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1171): applyOpen
,D/StatusBar.NetworkController( 1171): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1171): applyOpen
D/StatusBar.NetworkController( 1171): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1171): applyOpen
D/StatusBar.NetworkController( 1171): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1171): applyOpen
,I/ServiceManager(  360): Waiting for service AtCmdFwd...
,E/LightSensor(  888): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  888): mCallbacks.updateBrightness()
,D/DisplayPowerController(  888): getFinalBrightness : 8 -> 8
,E/LightSensor(  888): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  888): mCallbacks.updateBrightness()
,D/DisplayPowerController(  888): getFinalBrightness : 8 -> 8
,E/LightSensor(  888): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  888): mCallbacks.updateBrightness()
,D/DisplayPowerController(  888): getFinalBrightness : 8 -> 8
,E/LightSensor(  888): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  888): mCallbacks.updateBrightness()
,D/DisplayPowerController(  888): getFinalBrightness : 8 -> 8
,E/SMD     (  289): DCD ON
,E/LightSensor(  888): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  888): mCallbacks.updateBrightness()
,D/DisplayPowerController(  888): getFinalBrightness : 8 -> 8
,E/LightSensor(  888): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  888): mCallbacks.updateBrightness()
,D/DisplayPowerController(  888): getFinalBrightness : 8 -> 8
,W/Atfwd_Sendcmd(  360): AtCmdFwd service not published, waiting... retryCnt : 2
,E/LightSensor(  888): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  888): mCallbacks.updateBrightness()
D/DisplayPowerController(  888): getFinalBrightness : 8 -> 8
,E/LightSensor(  888): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  888): mCallbacks.updateBrightness()
D/DisplayPowerController(  888): getFinalBrightness : 8 -> 8
,I/WifiStateMachine(  888): CMD_RSSI_POLL : calculateWifiScore in!
,I/WifiStateMachine(  888): CMD_RSSI_POLL : calculateWifiScore out!
,I/WifiStateMachine(  888): CMD_RSSI_POLL : out!
,E/LightSensor(  888): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  888): mCallbacks.updateBrightness()
,D/DisplayPowerController(  888): getFinalBrightness : 8 -> 8
,E/LightSensor(  888): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  888): mCallbacks.updateBrightness()
D/DisplayPowerController(  888): getFinalBrightness : 8 -> 8
,E/LightSensor(  888): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  888): mCallbacks.updateBrightness()
,D/DisplayPowerController(  888): getFinalBrightness : 8 -> 8
,E/LightSensor(  888): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  888): mCallbacks.updateBrightness()
,D/DisplayPowerController(  888): getFinalBrightness : 8 -> 8
,E/LightSensor(  888): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  888): mCallbacks.updateBrightness()
,D/DisplayPowerController(  888): getFinalBrightness : 8 -> 8
,E/LightSensor(  888): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  888): mCallbacks.updateBrightness()
,D/DisplayPowerController(  888): getFinalBrightness : 8 -> 8
,E/LightSensor(  888): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  888): mCallbacks.updateBrightness()
,D/DisplayPowerController(  888): getFinalBrightness : 8 -> 8
,E/LightSensor(  888): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  888): mCallbacks.updateBrightness()
,D/DisplayPowerController(  888): getFinalBrightness : 8 -> 8
,E/LightSensor(  888): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  888): mCallbacks.updateBrightness()
,D/DisplayPowerController(  888): getFinalBrightness : 8 -> 8
,E/LightSensor(  888): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  888): mCallbacks.updateBrightness()
,D/DisplayPowerController(  888): getFinalBrightness : 8 -> 8
,D/SSRM:m  (  888): SIOP:: AP = 340, PST = 395, CUR = 300
,E/LightSensor(  888): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  888): mCallbacks.updateBrightness()
,D/DisplayPowerController(  888): getFinalBrightness : 8 -> 8
,E/LightSensor(  888): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  888): mCallbacks.updateBrightness()
,D/DisplayPowerController(  888): getFinalBrightness : 8 -> 8
,D/BatteryService(  888): level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 284, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  888): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
D/BatteryService(  888): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  888):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  888): Plugged
I/MotionRecognitionService(  888): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1171): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1171): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1171):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3252): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 3252): Disconnected process message: 10
,D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/LightSensor(  888): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  888): mCallbacks.updateBrightness()
D/DisplayPowerController(  888): getFinalBrightness : 8 -> 8
,E/SMD     (  289): DCD ON
,E/LightSensor(  888): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  888): mCallbacks.updateBrightness()
,D/DisplayPowerController(  888): getFinalBrightness : 8 -> 8
,D/StatusBar.NetworkController( 1171): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02012b/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020466/com.android.systemui:drawable/stat_sys_signal_inout mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
D/StatusBar.NetworkController( 1171): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1171): applyOpen
,D/StatusBar.NetworkController( 1171): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1171): applyOpen
,D/StatusBar.NetworkController( 1171): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1171): applyOpen
,D/StatusBar.NetworkController( 1171): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1171): applyOpen
,E/LightSensor(  888): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  888): mCallbacks.updateBrightness()
,D/DisplayPowerController(  888): getFinalBrightness : 8 -> 8
,E/LightSensor(  888): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  888): mCallbacks.updateBrightness()
,D/DisplayPowerController(  888): getFinalBrightness : 8 -> 8
,E/LightSensor(  888): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  888): mCallbacks.updateBrightness()
,D/DisplayPowerController(  888): getFinalBrightness : 8 -> 8
,I/WifiStateMachine(  888): CMD_RSSI_POLL : calculateWifiScore in!
,I/WifiStateMachine(  888): CMD_RSSI_POLL : calculateWifiScore out!
,I/WifiStateMachine(  888): CMD_RSSI_POLL : out!
,E/LightSensor(  888): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  888): mCallbacks.updateBrightness()
D/DisplayPowerController(  888): getFinalBrightness : 8 -> 8
,D/PowerManagerService(  888): [s] UserActivityState : 1 -> 2
D/DisplayPowerController(  888): getFinalBrightness : 1 -> 1
,D/PowerManagerService(  888): [s] DisplayPowerCallbacks : onStateChanged()
,D/lights  (  888): lcd : 1 +
,D/DisplayPowerController(  888): getFinalBrightness : 1 -> 1
,D/lights  (  888): lcd : 1 -
,D/DisplayPowerController(  888): getFinalBrightness : 1 -> 1
,E/LightSensor(  888): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  888): mCallbacks.updateBrightness()
D/DisplayPowerController(  888): getFinalBrightness : 1 -> 1
,E/LightSensor(  888): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  888): mCallbacks.updateBrightness()
,D/DisplayPowerController(  888): getFinalBrightness : 1 -> 1
,D/StatusBar.NetworkController( 1171): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02012b/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020464/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
,D/StatusBar.NetworkController( 1171): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1171): applyOpen
,D/StatusBar.NetworkController( 1171): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1171): applyOpen
,D/StatusBar.NetworkController( 1171): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1171): applyOpen
,D/StatusBar.NetworkController( 1171): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1171): applyOpen
,E/LightSensor(  888): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  888): mCallbacks.updateBrightness()
,D/DisplayPowerController(  888): getFinalBrightness : 1 -> 1
,E/LightSensor(  888): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  888): mCallbacks.updateBrightness()
,D/DisplayPowerController(  888): getFinalBrightness : 1 -> 1
,E/LightSensor(  888): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  888): mCallbacks.updateBrightness()
D/DisplayPowerController(  888): getFinalBrightness : 1 -> 1
,W/ContextImpl(  888): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/LightSensor(  888): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  888): mCallbacks.updateBrightness()
D/DisplayPowerController(  888): getFinalBrightness : 1 -> 1
,E/LightSensor(  888): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  888): mCallbacks.updateBrightness()
,D/DisplayPowerController(  888): getFinalBrightness : 1 -> 1
,E/LightSensor(  888): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  888): mCallbacks.updateBrightness()
,D/DisplayPowerController(  888): getFinalBrightness : 1 -> 1
,E/LightSensor(  888): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  888): mCallbacks.updateBrightness()
,D/DisplayPowerController(  888): getFinalBrightness : 1 -> 1
,E/LightSensor(  888): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  888): mCallbacks.updateBrightness()
D/DisplayPowerController(  888): getFinalBrightness : 1 -> 1
,E/LightSensor(  888): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  888): mCallbacks.updateBrightness()
,D/DisplayPowerController(  888): getFinalBrightness : 1 -> 1
,E/LightSensor(  888): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,E/SMD     (  289): DCD ON
,D/AutomaticBrightnessController(  888): mCallbacks.updateBrightness()
,D/DisplayPowerController(  888): getFinalBrightness : 1 -> 1
,E/LightSensor(  888): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  888): mCallbacks.updateBrightness()
,D/DisplayPowerController(  888): getFinalBrightness : 1 -> 1
,E/Watchdog(  888): !@Sync 4
,E/LightSensor(  888): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  888): mCallbacks.updateBrightness()
,D/DisplayPowerController(  888): getFinalBrightness : 1 -> 1
,E/LightSensor(  888): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  888): mCallbacks.updateBrightness()
D/DisplayPowerController(  888): getFinalBrightness : 1 -> 1
,E/LightSensor(  888): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  888): mCallbacks.updateBrightness()
,D/DisplayPowerController(  888): getFinalBrightness : 1 -> 1
,I/WifiStateMachine(  888): CMD_RSSI_POLL : calculateWifiScore in!
,I/WifiStateMachine(  888): CMD_RSSI_POLL : calculateWifiScore out!
I/WifiStateMachine(  888): CMD_RSSI_POLL : out!
,E/LightSensor(  888): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  888): mCallbacks.updateBrightness()
D/DisplayPowerController(  888): getFinalBrightness : 1 -> 1
,E/LightSensor(  888): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  888): mCallbacks.updateBrightness()
,D/DisplayPowerController(  888): getFinalBrightness : 1 -> 1
,E/LightSensor(  888): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  888): mCallbacks.updateBrightness()
,D/DisplayPowerController(  888): getFinalBrightness : 1 -> 1
,E/LightSensor(  888): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  888): mCallbacks.updateBrightness()
,D/DisplayPowerController(  888): getFinalBrightness : 1 -> 1
,E/LightSensor(  888): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  888): mCallbacks.updateBrightness()
D/DisplayPowerController(  888): getFinalBrightness : 1 -> 1
,E/LightSensor(  888): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  888): mCallbacks.updateBrightness()
,D/DisplayPowerController(  888): getFinalBrightness : 1 -> 1
,E/LightSensor(  888): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  888): mCallbacks.updateBrightness()
,D/DisplayPowerController(  888): getFinalBrightness : 1 -> 1
,E/LightSensor(  888): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  888): mCallbacks.updateBrightness()
,D/DisplayPowerController(  888): getFinalBrightness : 1 -> 1
,E/LightSensor(  888): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  888): mCallbacks.updateBrightness()
,D/DisplayPowerController(  888): getFinalBrightness : 1 -> 1
,D/StatusBar.NetworkController( 1171): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02012b/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020466/com.android.systemui:drawable/stat_sys_signal_inout mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
D/StatusBar.NetworkController( 1171): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1171): applyOpen
,D/StatusBar.NetworkController( 1171): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1171): applyOpen
D/StatusBar.NetworkController( 1171): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1171): applyOpen
,D/StatusBar.NetworkController( 1171): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1171): applyOpen
,E/LightSensor(  888): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  888): mCallbacks.updateBrightness()
,D/DisplayPowerController(  888): getFinalBrightness : 1 -> 1
,E/LightSensor(  888): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  888): mCallbacks.updateBrightness()
,D/DisplayPowerController(  888): getFinalBrightness : 1 -> 1
,E/LightSensor(  888): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  888): mCallbacks.updateBrightness()
D/DisplayPowerController(  888): getFinalBrightness : 1 -> 1
,E/SMD     (  289): DCD ON
,E/LightSensor(  888): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  888): mCallbacks.updateBrightness()
,D/DisplayPowerController(  888): getFinalBrightness : 1 -> 1
,E/LightSensor(  888): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  888): mCallbacks.updateBrightness()
,D/DisplayPowerController(  888): getFinalBrightness : 1 -> 1
,D/StatusBar.NetworkController( 1171): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02012b/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020464/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
D/StatusBar.NetworkController( 1171): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1171): applyOpen
,D/StatusBar.NetworkController( 1171): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1171): applyOpen
D/StatusBar.NetworkController( 1171): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1171): applyOpen
,D/StatusBar.NetworkController( 1171): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1171): applyOpen
,E/LightSensor(  888): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  888): mCallbacks.updateBrightness()
,D/DisplayPowerController(  888): getFinalBrightness : 1 -> 1
,E/LightSensor(  888): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  888): mCallbacks.updateBrightness()
,D/DisplayPowerController(  888): getFinalBrightness : 1 -> 1
,E/LightSensor(  888): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  888): mCallbacks.updateBrightness()
,D/DisplayPowerController(  888): getFinalBrightness : 1 -> 1
,I/WifiStateMachine(  888): CMD_RSSI_POLL : calculateWifiScore in!
,I/WifiStateMachine(  888): CMD_RSSI_POLL : calculateWifiScore out!
I/WifiStateMachine(  888): CMD_RSSI_POLL : out!
,D/PowerManagerService(  888): [s] UserActivityState : 2 -> 4
,I/PowerManagerService(  888): Nap time (uid 1000)...
I/PowerManagerService(  888): !@[ps] Screen__Off(2) : 
,I/PowerManagerService(  888): Going to sleep due to screen timeout (uid 1000)...
,D/PowerManagerService(  888): [PWL] sb acquire: PowerManagerService.Broadcasts
,D/InputManager-JNI(  888): setDeviceInteractive: 0
,D/PowerManagerService(  888): SecHardwareInterface.setBatteryADC : false
,D/InputManager-JNI(  888): sysfs_write +: /sys/class/input/event2/device/enabled: 0
,D/PowerManagerService(  888): handleSandman : startDream()
,D/InputManager-JNI(  888): sysfs_write +: /sys/class/input/event1/device/enabled: 0
,E/PowerManagerService(  888): handleSandman : startDreaming, but isDreaming false
,I/PowerManagerService(  888): Sleeping (uid 1000)...
,D/InputManager-JNI(  888): sysfs_write -: /sys/class/input/event2/device/enabled: 0
D/PowerManagerService(  888): [s] UserActivityState : 4 -> 0
,D/PowerManagerService(  888): [input device light] setInputDeviceLightOn is called : 0
,D/PowerManagerService(  888): [input device light] handleInputDeviceLightOff
,I/SurfaceFlinger(  249): id=17 createSurf (1080x1920),2 flag=404, ColorFade
,D/InputManager-JNI(  888): sysfs_write -: /sys/class/input/event1/device/enabled: 0
,D/SContextService(  888): 	.unregisterCallback : 1, client=
,D/SContextService(  888): unregisterCallback() : Listener = android.hardware.scontext.SContextService$Listener@287b90c9, Service = Auto Rotation, used = 1
,W/CAE     (  888): unregisterCallback(ContextAwareService.java:199) - [unregi 01] Mutex is locked for AUTO_ROTATION
,V/CAE     (  888): stop(ContextProvider.java:149)
,V/CAE     (  888): clear(AutoRotationRunner.java:182)
,V/CAE     (  888): disable(AutoRotationRunner.java:171)
,I/CAE     (  888): sendCmdToSensorHub(SensorHubCommManager.java:144) - -78, 7, 0, 0,
,D/SensorHubManager(  888): SendSensorHubData: send data = -78, 7, 0, 0
,D/Sensorhubs(  309): sendContextData: -78, 7, 0, 0
,E/LightSensor(  888): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/CAE     (  888): getFaultDetectionResult(AutoRotationRunner.java:195) - true
,I/CAE     (  888): notifyCmdProcessResultObserver(ContextProvider.java:617) - CheckResult = 0, Cause = Success
,D/CAE     (  888): doCommendProcess(ContextAwareService.java:314) - complete notify the operation result.
,I/CAE     (  888): displayUsedCountForService(ContextAwareService.java:406) - totalCnt = 0, serviceCount = 0, subCollectionCount = 0
,D/CAE     (  888): showListenerList(ContextAwareService.java:247) - ===== Context Aware Service List =====
,W/CAE     (  888): unregisterCallback(ContextAwareService.java:234) - [unregi 02] Mutex is unlocked for AUTO_ROTATION
D/SContextService(  888): removeSContextService() : service = Auto Rotation
,D/SContextService(  888): ===== SContext Service List =====
D/SContextManager(  888):   .unregisterListener : listener = com.android.internal.policy.impl.WindowOrientationListener$SContextListenerImpl@29b27915, service=Auto Rotation
,D/KeyguardViewMediator( 1171): onScreenTurnedOff(3)
,I/KeyguardEffectViewController( 1171): *** KeyguardEffectView getInstanceIfExists ***
D/KeyguardEffectViewController( 1171): changeWallpaperByScreenOff()
D/KeyguardViewMediator( 1171): notifyScreenOffLocked
,D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1171): value : false
D/KeyguardViewMediator( 1171): timeout : 5000
,D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1171): value : false
,I/SQLiteSecureOpenHelper( 3592): getWritableDatabase(pwd)
I/SQLiteSecureOpenHelper( 3592): getDatabaseLocked(b,b,pwd)...
,D/DisplayPowerController(  888): ColorFade: onAnimationStart
D/DisplayPowerController(  888): getFinalBrightness : 8 -> 0
D/AutomaticBrightnessController(  888): mCallbacks.updateBrightness()
D/DisplayPowerController(  888): getFinalBrightness : 8 -> 0
,D/KeyguardViewMediator( 1171): setting alarm to turn off keyguard, seq = 2
,D/KeyguardViewMediator( 1171): handleNotifyScreenOff
,D/lights  (  888): lcd : 0 +
D/DisplayPowerController(  888): getFinalBrightness : 8 -> 0
,D/LightsService(  888): [api] [SvcLED] setFlashing :: id = 3, color = 0, mode = 14, onMS = 0, offMS = 0,  (uid: 1000 pid: 888) 
D/LightsService(  888): [SvcLED] setSvcLedStateLocked:: SvcLEDState : 0x0 -> 0x40 | SvcLED(id=3) set On
,D/LightsService(  888): [SvcLED]  onSensorChanged::light value = 0
,D/SensorManager(  888): registerListener :: 6, TMG399X RGB Sensor, 200000, 0,  
,D/SensorManager(  888): unregisterListener ::   
D/BatteryService(  888): turn on LED for fully charged
,I/CAE     (  888): handleMessage(CaPowerManager.java:182) - AP_SLEEP
,I/CAE     (  888): updateApPowerStatus(SensorHubParserProvider.java:421) - AP_SLEEP
I/CAE     (  888): sendCmdToSensorHub(SensorHubCommManager.java:144) - -76, 13, -46, 0,
,D/SensorHubManager(  888): SendSensorHubData: send data = -76, 13, -46, 0
D/Sensorhubs(  309): sendContextData: -76, 13, -46, 0
,D/lights  (  888): lcd : 0 -
D/lights  (  888): led_pattern : 5 +
,I/CAE     (  888): sendCmdToSensorHub(SensorHubCommManager.java:144) - -63, 14, 15, 21, 13,
D/SensorHubManager(  888): SendSensorHubData: send data = -63, 14, 15, 21, 13
,D/Sensorhubs(  309): sendContextData: -63, 14, 15, 21, 13
,D/lights  (  888): led_pattern : 5 -
,D/LightsService(  888): [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=3) maintains its priority right
,D/MotionRecognitionService(  888):   mReceiver.onReceive : ACTION_SCREEN_OFF
,E/MotionRecognitionService(  888):  handler : SCREEN_OFF end 
,E/LightSensor(  888): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  888): mCallbacks.updateBrightness()
D/DisplayPowerController(  888): getFinalBrightness : 8 -> 0
,D/NotificationService(  888): ACTION_SCREEN_OFF
D/LightsService(  888): [api] [SvcLED] setFlashing :: id = 4, color = ffffffff, mode = 12, onMS = 500, offMS = 2000,  (uid: 1000 pid: 888) 
D/LightsService(  888): [SvcLED] setSvcLedStateLocked:: SvcLEDState : 0x40 -> 0x42 | SvcLED(id=4) set On
,D/WifiStateMachine(  888): backgroundScan enabled=false startBackgroundScanIfNeeded:false
E/WifiStateMachine(  888): handleScreenStateChanged Exit: false
,D/LightsService(  888): [SvcLED]  onSensorChanged::light value = 0
,E/WifiStateMachine(  888): setSuspendOptimizationsNative: 4 true -want true stack:setSuspendOptimizationsNative - access$16800 - processMessage - processMsg
,E/WifiStateMachine(  888): setSuspendOptimizationsNative do it 4 true stack:setSuspendOptimizationsNative - access$16800 - processMessage - processMsg
E/native  (  888): do suspend true
,D/SensorManager(  888): registerListener :: 6, TMG399X RGB Sensor, 200000, 0,  
,D/SensorManager(  888): unregisterListener ::   
,D/LightsService(  888): [SvcLED]  setSvcLedLightLocked :: priority changed! SvcLED(id=3) OUT; SvcLED(id=4) IN
,D/audio_hw_primary(  303): adev_set_parameters: enter: screen_state=off
,V/voice   (  303): voice_set_parameters: enter: screen_state=off
V/voice   (  303): voice_set_parameters: exit with code(-2)
V/msm8974_platform(  303): platform_set_parameters: enter: screen_state=off
V/msm8974_platform(  303): platform_set_parameters: exit with code(-2)
D/audio_hw_hfp(  303): audio_extn_hfp_set_parameters: enter
,V/audio_hw_primary(  303): adev_set_parameters: exit
,I/SecExternalDisplayIntents_Java(  888): Intent Recieved ..  -android.intent.action.SCREEN_OFFBroadCast Map value - 18
,D/IpRemoteDisplayController(  888): intent received android.intent.action.SCREEN_OFF
D/IpRemoteDisplayController(  888): Bridge Server is not available
,D/VolumePanel( 1171): mCoverBroadcastReceiver: Screen OFF start
D/VolumePanel( 1171): mCoverBroadcastReceiver : call onDismissSafeVolumeWarning() #1
,D/VolumePanel( 1171): mCoverBroadcastReceiver: Screen OFF end
D/VolumePanel( 1171): mCoverBroadcastReceiver: onReceive() end : intent=Intent { act=android.intent.action.SCREEN_OFF flg=0x50000010 (has extras) }
,D/PersonaManagerService(  888): ACTION_SCREEN_OFF onReceive
,D/PersonaManagerServiceHandler(  888): MSG_ACTION_SCREEN_OFF called
,D/NfcService( 1453): call the applyRotuiing
,D/STATUSBAR-PhoneStatusBar( 1171):      ACTION_SCREEN_OFF is finished!!!! 
,E/StatusBar( 1171): onReceive : Intent.ACTION_SCREEN_OFF
D/Recents_AlternateRecentsComponent( 1171): dismissHelpPopup 
,D/accuweather( 2029): [KK AccuPhone]>>> SWW:66 [0:0] action : androidintentactionSCREEN_OFF
,D/accuweather( 2029): [KK AccuPhone]>>> SWW:467 [0:0] stopRefreshIcon : 1
D/accuweather( 2029): [KK AccuPhone]>>> SWW:364 [0:0] getWeatherRenderer : 1
,D/ConnectivityService(  888): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
,W/ActivityManager(  888): getTasks: caller 10086 does not hold GET_TASKS; limiting output
,W/ActivityManager(  888): getTasks: caller 10086 does not hold GET_TASKS; limiting output
,D/SSRM:m  (  888): SIOP:: AP = 330, PST = 380, CUR = 300
,D/DisplayPowerState(  888): !@ ColorFade entry
,D/DisplayPowerController(  888): ColorFade: onAnimationEnd
,D/PowerManagerService(  888): [PWL] sb release: PowerManagerService.Broadcasts
,D/AutomaticBrightnessController(  888): [DAB] setLightSensorEnabled : Send Update unregisterListener mLightSensor
I/AutomaticBrightnessController(  888): [DAB] fileWriteInt : /sys/class/tcon/tcon/auto_br  value : 0
D/AutomaticBrightnessController(  888): [DAB] setLightSensorEnabled : unregisterListener mLightSensor
,E/LightSensor(  888): Light old sensor_state 8705, new sensor_state : 8193 en : 0
I/AutomaticBrightnessController(  888): [DAB] fileWriteInt : /sys/class/backlight/panel/auto_brightness  value : 0
,D/SensorManager(  888): unregisterListener ::   
E/Sensors (  888): Acc old sensor_state 8193, new sensor_state : 8192 en : 0
,D/SensorManager(  888): unregisterListener ::   
,D/DisplayPowerController(  888): getFinalBrightness : 0 -> 0
,I/DisplayManagerService(  888): Display device changed: DisplayDeviceInfo{"Built-in Screen": 1080 x 1920, 60.0 fps, supportedRefreshRates [60.0], density 480, 422.03 x 424.069 dpi, appVsyncOff 0, presDeadline 17666667, touch INTERNAL, rotation 0, type BUILT_IN, state OFF, FLAG_DEFAULT_DISPLAY, FLAG_ROTATES_WITH_CONTENT, FLAG_SECURE, FLAG_SUPPORTS_PROTECTED_BUFFERS}
D/DisplayPowerController(  888): getFinalBrightness : 0 -> 0
,V/ActivityManager(  888): Display changed displayId=0
D/SurfaceFlinger(  249): Set power mode=0, type=0 flinger=0xb6a62000
D/qdhwcomposer(  249): hwc_blank: Blanking display: 0
,D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
,D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
,D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1171): value : false
D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
,D/StatusBar.NetworkController( 1171): onSignalStrengthsChanged signalStrength=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte level=0
D/StatusBar.NetworkController( 1171): updateTelephonySignalStrength: hasService=false ss=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte
,D/StatusBar.NetworkController( 1171): updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal
D/StatusBar.NetworkController( 1171): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02012b/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020464/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
I/ServiceManager(  360): Waiting for service AtCmdFwd...
,D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
,I/rmt_storage(  278): rmt_storage_connect_cb: clnt_h=0x5 conn_h=0xb6b01090
,I/rmt_storage(  278): rmt_storage_rw_iovec_cb: /boot/modem_fs1: clnt_h=0x1: req_h=0xa msg_id=3: R/W request received
,I/rmt_storage(  278): wakelock acquired: 1, error no: 42
I/rmt_storage(  278): rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1 Unblock worker thread (th_id: -1229455232)
,I/rmt_storage(  278): rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1: req_h=0xa msg_id=3: Bytes written = 1572864
I/rmt_storage(  278): rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1: req_h=0xa msg_id=3: Send response: res=0 err=0
I/rmt_storage(  278): rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1 About to block rmt_storage client thread (th_id: -1229455232) wakelock released: 1, error no: 22
I/rmt_storage(  278): 
,I/rmt_storage(  278): rmt_storage_disconnect_cb: clnt_h=0x0x5 conn_h=0x0xb6b01090
,I/qdhwcomposer(  249): handle_blank_event: dpy:0 panel power state: 0
,D/qdhwcomposer(  249): hwc_blank: Done blanking display: 0
D/SurfaceControl(  888): Excessive delay in setPowerMode(): 258ms
D/PowerManagerService(  888): !@[s] blankAllDisplays() : blankAllDisplaysFromPowerManage
D/MISC PowerHAL(  888): sysfs_write +: /sys/class/power_supply/battery/lcd: 0
,D/MISC PowerHAL(  888): sysfs_write -: /sys/class/power_supply/battery/lcd: 0
,I/QCOM PowerHAL(  888): Got set_interactive hint
,I/PowerManagerService(  888): [PWL] Off : 0s ago
I/PowerManagerService(  888): [PWL]   PowerManagerService.Display: ref count=2
I/PowerManagerService(  888): [PWL]     mDisplayReady : false
D/DisplayPowerController(  888): getFinalBrightness : 0 -> 0
D/PowerManagerService(  888): [s] DisplayPowerCallbacks : onStateChanged()
D/PowerManagerService(  888): [PWL] sb release: PowerManagerService.Display
,I/ServiceManager(  360): Waiting for service AtCmdFwd...
,E/SMD     (  289): DCD ON
,I/ServiceManager(  360): Waiting for service AtCmdFwd...
,V/AlarmManager(  888): waitForAlarm result :4
,I/ServiceManager(  360): Waiting for service AtCmdFwd...
,D/BatteryService(  888): level:100, scale:100, status:5, health:2, present:true, voltage: 4386, temperature: 285, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  888): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  888): stay LED for fully charged
,D/BatteryService(  888): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  888):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1171): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1171): handleBatteryUpdate
,I/MotionRecognitionService(  888): Plugged
,I/MotionRecognitionService(  888): setPowerConnected  = true
,D/STATUSBAR-PhoneStatusBar( 1171):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3252): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3252): Disconnected process message: 10
,D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/EventLogService( 2467): Aggregate from 1452523875377 (log), 1452523875377 (data)
,V/GLSActivity( 1714): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1714): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
I/GLSUser ( 1714): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1714): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1714): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1714): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/Finsky  ( 6627): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,D/Finsky  ( 6627): [1] 5.onFinished: Installation state replication failed.
D/Finsky  ( 6627): [1] 5.onFinished: Scheduling replication attempt 4.
,I/art     (  888): Explicit concurrent mark sweep GC freed 65246(3MB) AllocSpace objects, 19(2MB) LOS objects, 30% free, 36MB/52MB, paused 1.799ms total 163.382ms
,I/ServiceManager(  360): Waiting for service AtCmdFwd...
,E/SMD     (  289): DCD ON
,V/AlarmManager(  888): waitForAlarm result :4
,D/KeyguardViewMediator( 1171): received DELAYED_KEYGUARD_ACTION with seq = 2, mDelayedShowingSequence = 2
,D/PersonaManager( 1171): isKioskContainerExistOnDevice
,D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1171): value : false
,D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1171): value : false
,D/KeyguardViewMediator( 1171): doKeyguard: not showing because lockscreen is off
,W/Atfwd_Sendcmd(  360): AtCmdFwd service not published, waiting... retryCnt : 3
,I/PowerManagerService(  888): [PWL] Off : 5s ago
,E/SMD     (  289): DCD ON
,D/SSRM:m  (  888): SIOP:: AP = 320, PST = 368, CUR = 300,
,E/SMD     (  289): DCD ON
,E/SMD     (  289): DCD ON
,W/ContextImpl(  888): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/PowerManagerService(  888): [PWL] Off : 15s ago
,E/SMD     (  289): DCD ON
,V/AlarmManager(  888): waitForAlarm result :4
,D/ConnectivityService(  888): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  888): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/GLSUser ( 1714): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,I/GLSUser ( 1714): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1714): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1714): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1714): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ResourcesManager( 1714): creating new AssetManager and set to /system/app/PlusOne/PlusOne.apk
,V/BitmapFactory( 1714): DecodeImagePath(decodeResourceStream3) : res/mipmap-xxhdpi-v4/quantum_logo_google_plus_color_44in48.png
,V/BitmapFactory( 1714): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  888): uri = 14 selection = getSealedState
,D/SecContentProvider2(  888): mCursor = null
D/SecContentProvider2(  888): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  888): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy(  888): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,E/HttpOperation( 5282): [kfu{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
E/HttpOperation( 5282): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 5282): 	at kfv.a(PG:65)
E/HttpOperation( 5282): 	at kff.u(PG:385)
E/HttpOperation( 5282): 	at kfb.a(PG:29)
E/HttpOperation( 5282): 	at kff.l(PG:132)
E/HttpOperation( 5282): 	at dsf.a(PG:807)
E/HttpOperation( 5282): 	at fhk.a(PG:1126)
E/HttpOperation( 5282): 	at fhk.a(PG:908)
E/HttpOperation( 5282): 	at fhk.onPerformSync(PG:636)
E/HttpOperation( 5282): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/HttpOperation( 5282): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/HttpOperation( 5282): 	at ihi.a(PG:22)
E/HttpOperation( 5282): 	at kft.a(PG:91)
E/HttpOperation( 5282): 	at kfv.a(PG:62)
E/HttpOperation( 5282): 	... 8 more
E/HttpOperation( 5282): Caused by: gdi: User intervention required. Notification has been pushed.
E/HttpOperation( 5282): 	at gde.c(Unknown Source)
E/HttpOperation( 5282): 	at gde.b(Unknown Source)
E/HttpOperation( 5282): 	at ihi.a(PG:19)
E/HttpOperation( 5282): 	... 10 more
,D/StatusBar( 1171): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,I/PhoneStatusBar( 1171): Icon Only
,D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
D/PanelView( 1171): There is/are notification(s) 
D/PanelView( 1171): There is/are notification(s) 
,I/art     ( 1714): Explicit concurrent mark sweep GC freed 24685(1424KB) AllocSpace objects, 14(1134KB) LOS objects, 39% free, 17MB/29MB, paused 486us total 38.151ms
,I/GLSUser ( 1714): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,I/GLSUser ( 1714): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1714): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1714): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1714): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ResourcesManager( 1714): creating new AssetManager and set to /system/app/PlusOne/PlusOne.apk
,V/BitmapFactory( 1714): DecodeImagePath(decodeResourceStream3) : res/mipmap-xxhdpi-v4/quantum_logo_google_plus_color_44in48.png
,V/BitmapFactory( 1714): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  888): uri = 14 selection = getSealedState
,D/SecContentProvider2(  888): mCursor = null
D/SecContentProvider2(  888): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  888): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy(  888): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/StatusBar( 1171): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,I/PhoneStatusBar( 1171): Icon Only
,D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
D/PanelView( 1171): There is/are notification(s) 
D/PanelView( 1171): There is/are notification(s) 
,E/HttpOperation( 5282): [getmobileexperiments] Unexpected exception
E/HttpOperation( 5282): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 5282): 	at kfv.a(PG:65)
E/HttpOperation( 5282): 	at kff.u(PG:385)
E/HttpOperation( 5282): 	at kfb.a(PG:29)
E/HttpOperation( 5282): 	at kff.l(PG:132)
E/HttpOperation( 5282): 	at ieo.a(PG:43)
E/HttpOperation( 5282): 	at iep.a(PG:93)
E/HttpOperation( 5282): 	at fhn.a(PG:59)
E/HttpOperation( 5282): 	at lex.a(PG:85)
E/HttpOperation( 5282): 	at lex.b(PG:132)
E/HttpOperation( 5282): 	at fhk.a(PG:1146)
E/HttpOperation( 5282): 	at fhk.a(PG:908)
E/HttpOperation( 5282): 	at fhk.onPerformSync(PG:636)
E/HttpOperation( 5282): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/HttpOperation( 5282): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/HttpOperation( 5282): 	at ihi.a(PG:22)
E/HttpOperation( 5282): 	at kft.a(PG:91)
E/HttpOperation( 5282): 	at kfv.a(PG:62)
E/HttpOperation( 5282): 	... 12 more
E/HttpOperation( 5282): Caused by: gdi: User intervention required. Notification has been pushed.
E/HttpOperation( 5282): 	at gde.c(Unknown Source)
E/HttpOperation( 5282): 	at gde.b(Unknown Source)
E/HttpOperation( 5282): 	at ihi.a(PG:19)
E/HttpOperation( 5282): 	... 14 more
,E/ExperimentLoader( 5282): [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 5282): java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 5282): 	at kfv.a(PG:65)
E/ExperimentLoader( 5282): 	at kff.u(PG:385)
E/ExperimentLoader( 5282): 	at kfb.a(PG:29)
E/ExperimentLoader( 5282): 	at kff.l(PG:132)
E/ExperimentLoader( 5282): 	at ieo.a(PG:43)
E/ExperimentLoader( 5282): 	at iep.a(PG:93)
E/ExperimentLoader( 5282): 	at fhn.a(PG:59)
E/ExperimentLoader( 5282): 	at lex.a(PG:85)
E/ExperimentLoader( 5282): 	at lex.b(PG:132)
E/ExperimentLoader( 5282): 	at fhk.a(PG:1146)
E/ExperimentLoader( 5282): 	at fhk.a(PG:908)
E/ExperimentLoader( 5282): 	at fhk.onPerformSync(PG:636)
E/ExperimentLoader( 5282): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/ExperimentLoader( 5282): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/ExperimentLoader( 5282): 	at ihi.a(PG:22)
E/ExperimentLoader( 5282): 	at kft.a(PG:91)
E/ExperimentLoader( 5282): 	at kfv.a(PG:62)
E/ExperimentLoader( 5282): 	... 12 more
E/ExperimentLoader( 5282): Caused by: gdi: User intervention required. Notification has been pushed.
E/ExperimentLoader( 5282): 	at gde.c(Unknown Source)
E/ExperimentLoader( 5282): 	at gde.b(Unknown Source)
E/ExperimentLoader( 5282): 	at ihi.a(PG:19)
E/ExperimentLoader( 5282): 	... 14 more
,I/GLSUser ( 1714): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
I/GLSUser ( 1714): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1714): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1714): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1714): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/BitmapFactory( 1714): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  888): uri = 14 selection = getSealedState
,D/SecContentProvider2(  888): mCursor = null
D/SecContentProvider2(  888): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  888): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy(  888): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/StatusBar( 1171): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,I/PhoneStatusBar( 1171): Icon Only
D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
D/PanelView( 1171): There is/are notification(s) 
D/PanelView( 1171): There is/are notification(s) 
,E/HttpOperation( 5282): [getaccountstatus] Unexpected exception
E/HttpOperation( 5282): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 5282): 	at kfv.a(PG:65)
E/HttpOperation( 5282): 	at kff.u(PG:385)
E/HttpOperation( 5282): 	at kfb.a(PG:29)
E/HttpOperation( 5282): 	at ixd.a(PG:248)
E/HttpOperation( 5282): 	at ixd.b(PG:206)
E/HttpOperation( 5282): 	at ixd.a(PG:175)
E/HttpOperation( 5282): 	at fig.a(PG:78)
E/HttpOperation( 5282): 	at lex.a(PG:85)
E/HttpOperation( 5282): 	at lex.b(PG:132)
E/HttpOperation( 5282): 	at fhk.a(PG:1146)
E/HttpOperation( 5282): 	at fhk.a(PG:908)
E/HttpOperation( 5282): 	at fhk.onPerformSync(PG:636)
E/HttpOperation( 5282): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/HttpOperation( 5282): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/HttpOperation( 5282): 	at ihi.a(PG:22)
E/HttpOperation( 5282): 	at kft.a(PG:91)
E/HttpOperation( 5282): 	at kfv.a(PG:62)
E/HttpOperation( 5282): 	... 12 more
E/HttpOperation( 5282): Caused by: gdi: User intervention required. Notification has been pushed.
E/HttpOperation( 5282): 	at gde.c(Unknown Source)
E/HttpOperation( 5282): 	at gde.b(Unknown Source)
E/HttpOperation( 5282): 	at ihi.a(PG:19)
E/HttpOperation( 5282): 	... 14 more
,E/EsSyncAdapterService( 5282): Sync failure
E/EsSyncAdapterService( 5282): java.io.IOException: Rpc failed
E/EsSyncAdapterService( 5282): 	at ixd.a(PG:348)
E/EsSyncAdapterService( 5282): 	at ixd.a(PG:248)
E/EsSyncAdapterService( 5282): 	at ixd.b(PG:206)
E/EsSyncAdapterService( 5282): 	at ixd.a(PG:175)
E/EsSyncAdapterService( 5282): 	at fig.a(PG:78)
E/EsSyncAdapterService( 5282): 	at lex.a(PG:85)
E/EsSyncAdapterService( 5282): 	at lex.b(PG:132)
E/EsSyncAdapterService( 5282): 	at fhk.a(PG:1146)
E/EsSyncAdapterService( 5282): 	at fhk.a(PG:908)
E/EsSyncAdapterService( 5282): 	at fhk.onPerformSync(PG:636)
E/EsSyncAdapterService( 5282): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/EsSyncAdapterService( 5282): Caused by: java.io.IOException: Cannot obtain authentication token
E/EsSyncAdapterService( 5282): 	at kfv.a(PG:65)
E/EsSyncAdapterService( 5282): 	at kff.u(PG:385)
E/EsSyncAdapterService( 5282): 	at kfb.a(PG:29)
E/EsSyncAdapterService( 5282): 	... 10 more
E/EsSyncAdapterService( 5282): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/EsSyncAdapterService( 5282): 	at ihi.a(PG:22)
E/EsSyncAdapterService( 5282): 	at kft.a(PG:91)
E/EsSyncAdapterService( 5282): 	at kfv.a(PG:62)
E/EsSyncAdapterService( 5282): 	... 12 more
E/EsSyncAdapterService( 5282): Caused by: gdi: User intervention required. Notification has been pushed.
E/EsSyncAdapterService( 5282): 	at gde.c(Unknown Source)
E/EsSyncAdapterService( 5282): 	at gde.b(Unknown Source)
E/EsSyncAdapterService( 5282): 	at ihi.a(PG:19)
E/EsSyncAdapterService( 5282): 	... 14 more
,D/ConnectivityService(  888): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SyncManager(  888): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, SERVER, currentRunTime 156448, reason: 10135, SyncResult: stats [ numIoExceptions: 2]
,D/ConnectivityService(  888): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  888): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SecContentProvider2(  888): uri = 11 selection = getMyKnoxAdmin
D/SecContentProvider2(  888): mCursor = null
,E/SMD     (  289): DCD ON
,E/SQLiteLog( 1714): (10) POSIX Error : 11 SQLite Error : 3850
,I/ServiceManager(  360): Waiting for service AtCmdFwd...
,D/SSRM:m  (  888): SIOP:: AP = 310, PST = 359, CUR = 300
,I/ServiceManager(  360): Waiting for service AtCmdFwd...
,I/ServiceManager(  360): Waiting for service AtCmdFwd...
,E/SMD     (  289): DCD ON
,I/ServiceManager(  360): Waiting for service AtCmdFwd...
,V/AlarmManager(  888): waitForAlarm result :4
,I/ServiceManager(  360): Waiting for service AtCmdFwd...
,V/GLSActivity( 1714): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1714): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure,
I/GLSUser ( 1714): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1714): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1714): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1714): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/Finsky  ( 6627): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,D/Finsky  ( 6627): [1] 5.onFinished: Installation state replication failed.
,D/Finsky  ( 6627): [1] 5.onFinished: Scheduling replication attempt 5.
,W/Atfwd_Sendcmd(  360): AtCmdFwd service not published, waiting... retryCnt : 4
,E/SMD     (  289): DCD ON
,E/Watchdog(  888): !@Sync 5
,E/SMD     (  289): DCD ON
,D/BatteryService(  888): level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 285, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  888): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
D/BatteryService(  888): stay LED for fully charged
D/BatteryService(  888): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  888):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  888): Plugged
I/MotionRecognitionService(  888): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1171): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1171): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1171):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3252): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3252): Disconnected process message: 10
,D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:m  (  888): SIOP:: AP = 310, PST = 350, CUR = 300
,I/PowerManagerService(  888): [PWL] Off : 30s ago
,E/SMD     (  289): DCD ON
,W/ContextImpl(  888): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  289): DCD ON
,E/SMD     (  289): DCD ON
,D/SSRM:m  (  888): SIOP:: AP = 300, PST = 341, CUR = 300
,E/SMD     (  289): DCD ON
,E/SMD     (  289): DCD ON
,V/AlarmManager(  888): waitForAlarm result :4
,D/BatteryService(  888): level:100, scale:100, status:5, health:2, present:true, voltage: 4383, temperature: 285, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  888): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
D/BatteryService(  888): stay LED for fully charged
D/BatteryService(  888): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  888):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  888): Plugged
I/MotionRecognitionService(  888): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1171): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1171): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1171):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/ConnectivityService(  888): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3252): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 3252): Disconnected process message: 10
,D/ConnectivityService(  888): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,V/GLSActivity( 1714): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ConnectivityService(  888): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  888): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/VacuumService( 1714): Vacuum at: now=1452525718408 tag=VacuumService
,I/GoogleURLConnFactory( 1714): Using platform SSLCertificateSocketFactory
,D/ConnectivityService(  888): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/GLSUser ( 1714): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
I/GLSUser ( 1714): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1714): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1714): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1714): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/BitmapFactory( 1714): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/common_ic_googleplayservices.png
,V/BitmapFactory( 1714): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  888): uri = 14 selection = getSealedState
D/SecContentProvider2(  888): mCursor = null
,D/SecContentProvider2(  888): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  888): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy(  888): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/StatusBar( 1171): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,I/PhoneStatusBar( 1171): Icon Only
,D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
D/PanelView( 1171): There is/are notification(s) 
E/Uploader( 1714): Failed to get auth token: User intervention required. Notification has been pushed.
E/Uploader( 1714): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
E/Uploader( 1714): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
E/Uploader( 1714): 	at com.google.android.gms.auth.p.d(SourceFile:599)
E/Uploader( 1714): 	at com.google.android.gms.auth.p.c(SourceFile:550)
E/Uploader( 1714): 	at com.google.android.gms.auth.p.b(SourceFile:477)
E/Uploader( 1714): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:508)
E/Uploader( 1714): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:337)
E/Uploader( 1714): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:263)
E/Uploader( 1714): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:235)
E/Uploader( 1714): 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:125)
E/Uploader( 1714): 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:78)
E/Uploader( 1714): 	at com.google.android.gms.gcm.am.run(SourceFile:135)
,D/PanelView( 1171): There is/are notification(s) 
,I/System.out( 1714): (HTTPLog)-Static: SBServiceAPI: getService class android.os.ServiceManager
,I/System.out( 1714): (HTTPLog)-Static: isShipBuild true
I/System.out( 1714): (HTTPLog)-Thread-206-834058997: SmartBonding Enabling is true, SHIP_BUILD is true, log to file is false, DBG is false
,I/qtaguid ( 1714): Tagging socket 58 with tag 120100000000{4609,0} uid -1, pid: 1714, getuid(): 10012
,I/qtaguid ( 1714): Tagging socket 62 with tag 120100000000{4609,0} uid -1, pid: 1714, getuid(): 10012
,I/ServiceManager(  360): Waiting for service AtCmdFwd...
,W/Uploader( 1714): No account for auth token provided
,I/qtaguid ( 1714): Tagging socket 58 with tag 120100000000{4609,0} uid -1, pid: 1714, getuid(): 10012
,W/Uploader( 1714): No account for auth token provided
,I/qtaguid ( 1714): Tagging socket 58 with tag 120100000000{4609,0} uid -1, pid: 1714, getuid(): 10012
V/GLSActivity( 1714): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1714): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
I/GLSUser ( 1714): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1714): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1714): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1714): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/Uploader( 1714): No account for auth token provided
,I/qtaguid ( 1714): Tagging socket 58 with tag 120100000000{4609,0} uid -1, pid: 1714, getuid(): 10012
,D/Finsky  ( 6627): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
D/Finsky  ( 6627): [1] 5.onFinished: Installation state replication failed.
,D/Finsky  ( 6627): [1] 5.onFinished: Giving up after 6 failures.
,W/Uploader( 1714): No account for auth token provided
,I/qtaguid ( 1714): Tagging socket 58 with tag 120100000000{4609,0} uid -1, pid: 1714, getuid(): 10012
,W/Uploader( 1714):  no longer exists, so no auth token.
,I/qtaguid ( 1714): Tagging socket 58 with tag 120100000000{4609,0} uid -1, pid: 1714, getuid(): 10012
,E/SQLiteLog( 1714): (10) POSIX Error : 11 SQLite Error : 3850
,D/ConnectivityService(  888): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/ServiceManager(  360): Waiting for service AtCmdFwd...
,V/AlarmManager(  888): waitForAlarm result :8
,E/SMD     (  289): DCD ON
,I/ServiceManager(  360): Waiting for service AtCmdFwd...
,I/ServiceManager(  360): Waiting for service AtCmdFwd...
,V/AlarmManager(  888): waitForAlarm result :4
,D/KeyguardUpdateMonitor( 1171): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1171): handleTimeUpdate
,D/KeyguardEffectViewController( 1171): onReceive action : android.intent.action.TIME_TICK
,I/KeyguardEffectViewController( 1171): *** don't update sliding image ***
,D/ConnectivityService(  888): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/DateView( 1171): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1171): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,I/ServiceManager(  360): Waiting for service AtCmdFwd...
,D/ConnectivityService(  888): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/BooksSync( 7687): Starting books sync, d
,D/ConnectivityService(  888): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,V/GLSActivity( 1714): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1714): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
,I/GLSUser ( 1714): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1714): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1714): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1714): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ResourcesManager( 1714): creating new AssetManager and set to /system/app/Books/Books.apk
,V/BitmapFactory( 1714): DecodeImagePath(decodeResourceStream3) : res/mipmap-xxhdpi-v4/ic_launcher_play_books.png
,V/BitmapFactory( 1714): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  888): uri = 14 selection = getSealedState
D/SecContentProvider2(  888): mCursor = null
D/SecContentProvider2(  888): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  888): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy(  888): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,W/GLSActivity( 1714): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1714): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1714): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1714): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1714): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1714): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1714): 	at android.os.Binder.execTransact(Binder.java:446)
,E/BooksAccountManager( 7687): Authentication error
E/BooksAccountManager( 7687): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 7687): android.accounts.AccountManager.convertErrorToException(AccountManager.java:1893)
E/HttpHelper( 7687): null auth token
,I/qtaguid ( 7687): Tagging socket 34 with tag 10000000000{256,0} uid -1, pid: 7687, getuid(): 10082
,D/StatusBar( 1171): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,I/PhoneStatusBar( 1171): Icon Only
D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
D/PanelView( 1171): There is/are notification(s) 
D/PanelView( 1171): There is/are notification(s) 
,I/qtaguid ( 7687): Tagging socket 34 with tag 10000000000{256,0} uid -1, pid: 7687, getuid(): 10082
,I/qtaguid ( 7687): Untagging socket 34
,W/ApiaryClient( 7687): Error response from books API: {
W/ApiaryClient( 7687):  "error": {
W/ApiaryClient( 7687):   "errors": [
W/ApiaryClient( 7687):    {
W/ApiaryClient( 7687):     "domain": "global",
W/ApiaryClient( 7687):     "reason": "required",
W/ApiaryClient( 7687):     "message": "Login Required",
W/ApiaryClient( 7687):     "locationType": "header",
W/ApiaryClient( 7687):     "location": "Authorization"
W/ApiaryClient( 7687):    }
W/ApiaryClient( 7687):   ],
W/ApiaryClient( 7687):   "code": 401,
W/ApiaryClient( 7687):   "message": "Login Required"
W/ApiaryClient( 7687):  }
W/ApiaryClient( 7687): }
,W/ApiaryClient( 7687): errCount = 1: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 7687): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3DS0HXd4TFLU4&nonce=-4889240525093619184&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 7687): Headers suppressed
,D/ConnectivityService(  888): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/SMD     (  289): DCD ON
,W/Atfwd_Sendcmd(  360): AtCmdFwd service not published, waiting... retryCnt : 5
,D/SSRM:m  (  888): SIOP:: AP = 300, PST = 335, CUR = 300
,I/PowerManagerService(  888): [PWL] Off : 50s ago
,I/PowerManagerService(  888): [PWL]   PowerManagerService.WakeLocks: ref count=1
,I/PowerManagerService(  888): [PWL]     mWakeLockSummary : 0x1
,I/PowerManagerService(  888): [PWL]       PARTIAL_WAKE_LOCK              '*sync*/com.google.android.apps.books/com.google/eM_ADDR' (uid=1000, pid=888, ws=WorkSource{10082}) (elapsedTime=1231)
,V/GLSActivity( 1714): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1714): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
,I/GLSUser ( 1714): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1714): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1714): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1714): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/BitmapFactory( 1714): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  888): uri = 14 selection = getSealedState
,D/SecContentProvider2(  888): mCursor = null
D/SecContentProvider2(  888): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  888): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy(  888): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/StatusBar( 1171): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,I/PhoneStatusBar( 1171): Icon Only
,D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
D/PanelView( 1171): There is/are notification(s) 
,D/PanelView( 1171): There is/are notification(s) 
,W/GLSActivity( 1714): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1714): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1714): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1714): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1714): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1714): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1714): 	at android.os.Binder.execTransact(Binder.java:446)
,E/BooksAccountManager( 7687): Authentication error
E/BooksAccountManager( 7687): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 7687): android.accounts.AccountManager.convertErrorToException(AccountManager.java:1893)
,E/HttpHelper( 7687): null auth token
,I/qtaguid ( 7687): Tagging socket 34 with tag 10000000000{256,0} uid -1, pid: 7687, getuid(): 10082
,I/qtaguid ( 7687): Tagging socket 39 with tag 10000000000{256,0} uid -1, pid: 7687, getuid(): 10082
,I/qtaguid ( 7687): Untagging socket 34
,W/ApiaryClient( 7687): Error response from books API: {
W/ApiaryClient( 7687):  "error": {
W/ApiaryClient( 7687):   "errors": [
W/ApiaryClient( 7687):    {
W/ApiaryClient( 7687):     "domain": "global",
W/ApiaryClient( 7687):     "reason": "required",
W/ApiaryClient( 7687):     "message": "Login Required",
W/ApiaryClient( 7687):     "locationType": "header",
W/ApiaryClient( 7687):     "location": "Authorization"
W/ApiaryClient( 7687):    }
W/ApiaryClient( 7687):   ],
W/ApiaryClient( 7687):   "code": 401,
W/ApiaryClient( 7687):   "message": "Login Required"
W/ApiaryClient( 7687):  }
W/ApiaryClient( 7687): }
,W/ApiaryClient( 7687): errCount = 2: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 7687): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3DS0HXd4TFLU4&nonce=-4889240525093619184&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 7687): Headers suppressed
,D/ConnectivityService(  888): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,V/GLSActivity( 1714): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1714): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
,I/GLSUser ( 1714): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1714): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1714): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1714): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/BitmapFactory( 1714): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  888): uri = 14 selection = getSealedState
,D/SecContentProvider2(  888): mCursor = null
D/SecContentProvider2(  888): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  888): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy(  888): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/StatusBar( 1171): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,I/PhoneStatusBar( 1171): Icon Only
,D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
,D/PanelView( 1171): There is/are notification(s) 
D/PanelView( 1171): There is/are notification(s) 
,W/GLSActivity( 1714): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1714): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1714): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1714): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1714): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1714): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1714): 	at android.os.Binder.execTransact(Binder.java:446)
,E/BooksAccountManager( 7687): Authentication error
E/BooksAccountManager( 7687): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 7687): android.accounts.AccountManager.convertErrorToException(AccountManager.java:1893)
,E/HttpHelper( 7687): null auth token
,I/qtaguid ( 7687): Tagging socket 34 with tag 10000000000{256,0} uid -1, pid: 7687, getuid(): 10082
,I/qtaguid ( 7687): Untagging socket 34
,W/ApiaryClient( 7687): Error response from books API: {
W/ApiaryClient( 7687):  "error": {
W/ApiaryClient( 7687):   "errors": [
W/ApiaryClient( 7687):    {
W/ApiaryClient( 7687):     "domain": "global",
W/ApiaryClient( 7687):     "reason": "required",
W/ApiaryClient( 7687):     "message": "Login Required",
W/ApiaryClient( 7687):     "locationType": "header",
W/ApiaryClient( 7687):     "location": "Authorization"
W/ApiaryClient( 7687):    }
W/ApiaryClient( 7687):   ],
W/ApiaryClient( 7687):   "code": 401,
W/ApiaryClient( 7687):   "message": "Login Required"
W/ApiaryClient( 7687):  }
W/ApiaryClient( 7687): }
,W/ApiaryClient( 7687): errCount = 3: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 7687): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3DS0HXd4TFLU4&nonce=-4889240525093619184&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 7687): Headers suppressed
,D/ConnectivityService(  888): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/SMD     (  289): DCD ON
,E/BooksSync( 7687): Soft error
E/BooksSync( 7687): com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
E/BooksSync( 7687): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3DS0HXd4TFLU4&nonce=-4889240525093619184&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
E/BooksSync( 7687): Headers suppressed
E/BooksSync( 7687): 
E/BooksSync( 7687): com.google.android.apps.books.net.HttpHelper.wrapExceptionBasedOnStatus(HttpHelper.java:212)
,E/BooksSync( 7687): Sync error
E/BooksSync( 7687): com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
E/BooksSync( 7687): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3DS0HXd4TFLU4&nonce=-4889240525093619184&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
E/BooksSync( 7687): Headers suppressed
E/BooksSync( 7687): 
E/BooksSync( 7687): com.google.android.apps.books.net.HttpHelper.wrapExceptionBasedOnStatus(HttpHelper.java:212)
,I/BooksSync( 7687): Finished books sync
,D/ConnectivityService(  888): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SyncManager(  888): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 158474, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,D/ConnectivityService(  888): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  888): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/art     (  888): Explicit concurrent mark sweep GC freed 40755(2MB) AllocSpace objects, 24(839KB) LOS objects, 30% free, 36MB/52MB, paused 1.848ms total 166.238ms
,D/ConnectivityService(  888): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/SecContentProvider2(  888): uri = 11 selection = getMyKnoxAdmin
D/SecContentProvider2(  888): mCursor = null
,I/GLSUser ( 1714): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
I/GLSUser ( 1714): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1714): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1714): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1714): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/BitmapFactory( 1714): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  888): uri = 14 selection = getSealedState
D/SecContentProvider2(  888): mCursor = null
D/SecContentProvider2(  888): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  888): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy(  888): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/StatusBar( 1171): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,E/HttpOperation( 5282): [kfu{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
E/HttpOperation( 5282): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 5282): 	at kfv.a(PG:65)
E/HttpOperation( 5282): 	at kff.u(PG:385)
E/HttpOperation( 5282): 	at kfb.a(PG:29)
E/HttpOperation( 5282): 	at kff.l(PG:132)
E/HttpOperation( 5282): 	at dsf.a(PG:807)
E/HttpOperation( 5282): 	at fhk.a(PG:1126)
E/HttpOperation( 5282): 	at fhk.a(PG:908)
E/HttpOperation( 5282): 	at fhk.onPerformSync(PG:636)
E/HttpOperation( 5282): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/HttpOperation( 5282): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/HttpOperation( 5282): 	at ihi.a(PG:22)
E/HttpOperation( 5282): 	at kft.a(PG:91)
E/HttpOperation( 5282): 	at kfv.a(PG:62)
E/HttpOperation( 5282): 	... 8 more
E/HttpOperation( 5282): Caused by: gdi: User intervention required. Notification has been pushed.
E/HttpOperation( 5282): 	at gde.c(Unknown Source)
E/HttpOperation( 5282): 	at gde.b(Unknown Source)
E/HttpOperation( 5282): 	at ihi.a(PG:19)
E/HttpOperation( 5282): 	... 10 more
,I/PhoneStatusBar( 1171): Icon Only
D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
D/PanelView( 1171): There is/are notification(s) 
D/PanelView( 1171): There is/are notification(s) 
,I/GLSUser ( 1714): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
I/GLSUser ( 1714): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1714): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1714): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1714): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/BitmapFactory( 1714): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  888): uri = 14 selection = getSealedState
D/SecContentProvider2(  888): mCursor = null
D/SecContentProvider2(  888): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  888): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
V/ApplicationPolicy(  888): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/StatusBar( 1171): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,I/PhoneStatusBar( 1171): Icon Only
E/HttpOperation( 5282): [getmobileexperiments] Unexpected exception
E/HttpOperation( 5282): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 5282): 	at kfv.a(PG:65)
E/HttpOperation( 5282): 	at kff.u(PG:385)
E/HttpOperation( 5282): 	at kfb.a(PG:29)
E/HttpOperation( 5282): 	at kff.l(PG:132)
E/HttpOperation( 5282): 	at ieo.a(PG:43)
E/HttpOperation( 5282): 	at iep.a(PG:93)
E/HttpOperation( 5282): 	at fhn.a(PG:59)
E/HttpOperation( 5282): 	at lex.a(PG:85)
E/HttpOperation( 5282): 	at lex.b(PG:132)
E/HttpOperation( 5282): 	at fhk.a(PG:1146)
E/HttpOperation( 5282): 	at fhk.a(PG:908)
E/HttpOperation( 5282): 	at fhk.onPerformSync(PG:636)
E/HttpOperation( 5282): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/HttpOperation( 5282): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/HttpOperation( 5282): 	at ihi.a(PG:22)
E/HttpOperation( 5282): 	at kft.a(PG:91)
E/HttpOperation( 5282): 	at kfv.a(PG:62)
E/HttpOperation( 5282): 	... 12 more
E/HttpOperation( 5282): Caused by: gdi: User intervention required. Notification has been pushed.
E/HttpOperation( 5282): 	at gde.c(Unknown Source)
E/HttpOperation( 5282): 	at gde.b(Unknown Source)
E/HttpOperation( 5282): 	at ihi.a(PG:19)
E/HttpOperation( 5282): 	... 14 more
,D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
E/ExperimentLoader( 5282): [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 5282): java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 5282): 	at kfv.a(PG:65)
E/ExperimentLoader( 5282): 	at kff.u(PG:385)
E/ExperimentLoader( 5282): 	at kfb.a(PG:29)
E/ExperimentLoader( 5282): 	at kff.l(PG:132)
E/ExperimentLoader( 5282): 	at ieo.a(PG:43)
E/ExperimentLoader( 5282): 	at iep.a(PG:93)
E/ExperimentLoader( 5282): 	at fhn.a(PG:59)
E/ExperimentLoader( 5282): 	at lex.a(PG:85)
E/ExperimentLoader( 5282): 	at lex.b(PG:132)
E/ExperimentLoader( 5282): 	at fhk.a(PG:1146)
E/ExperimentLoader( 5282): 	at fhk.a(PG:908)
E/ExperimentLoader( 5282): 	at fhk.onPerformSync(PG:636)
E/ExperimentLoader( 5282): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/ExperimentLoader( 5282): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/ExperimentLoader( 5282): 	at ihi.a(PG:22)
E/ExperimentLoader( 5282): 	at kft.a(PG:91)
E/ExperimentLoader( 5282): 	at kfv.a(PG:62)
E/ExperimentLoader( 5282): 	... 12 more
E/ExperimentLoader( 5282): Caused by: gdi: User intervention required. Notification has been pushed.
E/ExperimentLoader( 5282): 	at gde.c(Unknown Source)
E/ExperimentLoader( 5282): 	at gde.b(Unknown Source)
E/ExperimentLoader( 5282): 	at ihi.a(PG:19)
E/ExperimentLoader( 5282): 	... 14 more
D/PanelView( 1171): There is/are notification(s) 
D/PanelView( 1171): There is/are notification(s) 
,I/GLSUser ( 1714): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
I/GLSUser ( 1714): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1714): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1714): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1714): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/BitmapFactory( 1714): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,E/SQLiteLog( 1714): (10) POSIX Error : 11 SQLite Error : 3850
,D/SecContentProvider2(  888): uri = 14 selection = getSealedState
D/SecContentProvider2(  888): mCursor = null
D/SecContentProvider2(  888): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  888): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
V/ApplicationPolicy(  888): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/StatusBar( 1171): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,I/PhoneStatusBar( 1171): Icon Only
D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
D/PanelView( 1171): There is/are notification(s) 
D/PanelView( 1171): There is/are notification(s) 
,E/HttpOperation( 5282): [getaccountstatus] Unexpected exception
E/HttpOperation( 5282): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 5282): 	at kfv.a(PG:65)
E/HttpOperation( 5282): 	at kff.u(PG:385)
E/HttpOperation( 5282): ,	at kfb.a(PG:29)
E/HttpOperation( 5282): 	at ixd.a(PG:248)
E/HttpOperation( 5282): 	at ixd.b(PG:206)
E/HttpOperation( 5282): 	at ixd.a(PG:175)
E/HttpOperation( 5282): 	at fig.a(PG:78)
E/HttpOperation( 5282): 	at lex.a(PG:85)
E/HttpOperation( 5282): 	at lex.b(PG:132)
E/HttpOperation( 5282): 	at fhk.a(PG:1146)
E/HttpOperation( 5282): 	at fhk.a(PG:908)
E/HttpOperation( 5282): 	at fhk.onPerformSync(PG:636)
E/HttpOperation( 5282): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/HttpOperation( 5282): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/HttpOperation( 5282): 	at ihi.a(PG:22)
E/HttpOperation( 5282): 	at kft.a(PG:91)
E/HttpOperation( 5282): 	at kfv.a(PG:62)
E/HttpOperation( 5282): 	... 12 more
E/HttpOperation( 5282): Caused by: gdi: User intervention required. Notification has been pushed.
E/HttpOperation( 5282): 	at gde.c(Unknown Source)
E/HttpOperation( 5282): 	at gde.b(Unknown Source)
E/HttpOperation( 5282): 	at ihi.a(PG:19)
E/HttpOperation( 5282): 	... 14 more
,E/EsSyncAdapterService( 5282): Sync failure
E/EsSyncAdapterService( 5282): java.io.IOException: Rpc failed
E/EsSyncAdapterService( 5282): 	at ixd.a(PG:348)
E/EsSyncAdapterService( 5282): 	at ixd.a(PG:248)
E/EsSyncAdapterService( 5282): 	at ixd.b(PG:206)
E/EsSyncAdapterService( 5282): 	at ixd.a(PG:175)
E/EsSyncAdapterService( 5282): 	at fig.a(PG:78)
E/EsSyncAdapterService( 5282): 	at lex.a(PG:85)
E/EsSyncAdapterService( 5282): 	at lex.b(PG:132)
E/EsSyncAdapterService( 5282): 	at fhk.a(PG:1146)
E/EsSyncAdapterService( 5282): 	at fhk.a(PG:908)
E/EsSyncAdapterService( 5282): 	at fhk.onPerformSync(PG:636)
E/EsSyncAdapterService( 5282): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/EsSyncAdapterService( 5282): Caused by: java.io.IOException: Cannot obtain authentication token
E/EsSyncAdapterService( 5282): 	at kfv.a(PG:65)
E/EsSyncAdapterService( 5282): 	at kff.u(PG:385)
E/EsSyncAdapterService( 5282): 	at kfb.a(PG:29)
E/EsSyncAdapterService( 5282): 	... 10 more
E/EsSyncAdapterService( 5282): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/EsSyncAdapterService( 5282): 	at ihi.a(PG:22)
E/EsSyncAdapterService( 5282): 	at kft.a(PG:91)
E/EsSyncAdapterService( 5282): 	at kfv.a(PG:62)
E/EsSyncAdapterService( 5282): 	... 12 more
E/EsSyncAdapterService( 5282): Caused by: gdi: User intervention required. Notification has been pushed.
E/EsSyncAdapterService( 5282): 	at gde.c(Unknown Source)
E/EsSyncAdapterService( 5282): 	at gde.b(Unknown Source)
E/EsSyncAdapterService( 5282): 	at ihi.a(PG:19)
E/EsSyncAdapterService( 5282): 	... 14 more
,D/ConnectivityService(  888): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SyncManager(  888): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, SERVER, currentRunTime 187151, reason: 10135, SyncResult: stats [ numIoExceptions: 2]
,D/ConnectivityService(  888): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  888): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SecContentProvider2(  888): uri = 11 selection = getMyKnoxAdmin
,D/SecContentProvider2(  888): mCursor = null
,E/SQLiteLog( 1714): (10) POSIX Error : 11 SQLite Error : 3850
,W/ContextImpl(  888): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  289): DCD ON
,E/Watchdog(  888): !@Sync 6
,E/SMD     (  289): DCD ON
,D/SSRM:m  (  888): SIOP:: AP = 300, PST = 328, CUR = 300
,E/SMD     (  289): DCD ON
,D/BatteryService(  888): level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 285, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  888): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  888): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  888):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  888): Plugged
,I/MotionRecognitionService(  888): setPowerConnected  = true
,D/BatteryService(  888): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1171): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1171): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1171):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3252): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3252): Disconnected process message: 10
,D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  289): DCD ON
,E/SMD     (  289): DCD ON
,D/SSRM:m  (  888): SIOP:: AP = 300, PST = 317, CUR = 300
,E/SMD     (  289): DCD ON
,E/SMD     (  289): DCD ON
,W/ContextImpl(  888): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/Atfwd_Sendcmd(  360): AtCmdFwd service not ready - Exhausted retry attempts - :6
I/Atfwd_Daemon(  360): result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,I/PowerManagerService(  888): [PWL] Off : 75s ago
,E/SMD     (  289): DCD ON
,V/AlarmManager(  888): waitForAlarm result :4
,D/ConnectivityService(  888): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/SMD     (  289): DCD ON
,D/SSRM:m  (  888): SIOP:: AP = 300, PST = 311, CUR = 300
,E/SMD     (  289): DCD ON
,I/ServiceManager(  360): Waiting for service AtCmdFwd...
,E/SMD     (  289): DCD ON
,E/Watchdog(  888): !@Sync 7
,I/ServiceManager(  360): Waiting for service AtCmdFwd...
,I/ServiceManager(  360): Waiting for service AtCmdFwd...
,I/ServiceManager(  360): Waiting for service AtCmdFwd...
,E/SMD     (  289): DCD ON
,I/ServiceManager(  360): Waiting for service AtCmdFwd...
,W/Atfwd_Sendcmd(  360): AtCmdFwd service not published, waiting... retryCnt : 1
,D/SSRM:m  (  888): SIOP:: AP = 290, PST = 306, CUR = 300
,E/SMD     (  289): DCD ON
,W/ContextImpl(  888): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  289): DCD ON
,I/ServiceManager(  360): Waiting for service AtCmdFwd...
,I/ServiceManager(  360): Waiting for service AtCmdFwd...
,I/ServiceManager(  360): Waiting for service AtCmdFwd...
,E/SMD     (  289): DCD ON
,I/ServiceManager(  360): Waiting for service AtCmdFwd...
,I/ServiceManager(  360): Waiting for service AtCmdFwd...
,W/Atfwd_Sendcmd(  360): AtCmdFwd service not published, waiting... retryCnt : 2
,D/SSRM:m  (  888): SIOP:: AP = 290, PST = 302, CUR = 300
,E/SMD     (  289): DCD ON
,E/SMD     (  289): DCD ON
,I/PowerManagerService(  888): [PWL] Off : 105s ago
,V/AlarmManager(  888): waitForAlarm result :8
,E/SMD     (  289): DCD ON
,V/AlarmManager(  888): waitForAlarm result :4
,D/KeyguardUpdateMonitor( 1171): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1171): handleTimeUpdate
,D/KeyguardEffectViewController( 1171): onReceive action : android.intent.action.TIME_TICK
,I/KeyguardEffectViewController( 1171): *** don't update sliding image ***
,D/BatteryService(  888): level:100, scale:100, status:5, health:2, present:true, voltage: 4383, temperature: 284, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  888): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
D/BatteryService(  888): stay LED for fully charged
,D/BatteryService(  888): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  888):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  888): Plugged
I/MotionRecognitionService(  888): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1171): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1171): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1171):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3252): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3252): Disconnected process message: 10
,D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/DateView( 1171): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1171): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/ConnectivityService(  888): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  888): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/BooksSync( 7687): Starting books sync, d
,D/ConnectivityService(  888): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,V/GLSActivity( 1714): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1714): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
,I/GLSUser ( 1714): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1714): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1714): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1714): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/SMD     (  289): DCD ON
,V/BitmapFactory( 1714): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  888): uri = 14 selection = getSealedState
,D/SecContentProvider2(  888): mCursor = null
D/SecContentProvider2(  888): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  888): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy(  888): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/StatusBar( 1171): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,I/PhoneStatusBar( 1171): Icon Only
,D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
,D/PanelView( 1171): There is/are notification(s) 
,D/PanelView( 1171): There is/are notification(s) 
,W/GLSActivity( 1714): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1714): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1714): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1714): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1714): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1714): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1714): 	at android.os.Binder.execTransact(Binder.java:446)
,E/BooksAccountManager( 7687): Authentication error
E/BooksAccountManager( 7687): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 7687): android.accounts.AccountManager.convertErrorToException(AccountManager.java:1893)
,E/HttpHelper( 7687): null auth token
,I/qtaguid ( 7687): Tagging socket 34 with tag 10000000000{256,0} uid -1, pid: 7687, getuid(): 10082
,I/qtaguid ( 7687): Untagging socket 34
,W/ApiaryClient( 7687): Error response from books API: {
W/ApiaryClient( 7687):  "error": {
W/ApiaryClient( 7687):   "errors": [
W/ApiaryClient( 7687):    {
W/ApiaryClient( 7687):     "domain": "global",
W/ApiaryClient( 7687):     "reason": "required",
W/ApiaryClient( 7687):     "message": "Login Required",
W/ApiaryClient( 7687):     "locationType": "header",
W/ApiaryClient( 7687):     "location": "Authorization"
W/ApiaryClient( 7687):    }
W/ApiaryClient( 7687):   ],
W/ApiaryClient( 7687):   "code": 401,
W/ApiaryClient( 7687):   "message": "Login Required"
W/ApiaryClient( 7687):  }
W/ApiaryClient( 7687): }
,W/ApiaryClient( 7687): errCount = 1: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 7687): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3DS0HXd4TFLU4&nonce=-6764129987466790599&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 7687): Headers suppressed
,D/ConnectivityService(  888): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/ServiceManager(  360): Waiting for service AtCmdFwd...
,D/SSRM:m  (  888): SIOP:: AP = 290, PST = 299, CUR = 300
,V/GLSActivity( 1714): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1714): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
,I/GLSUser ( 1714): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1714): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1714): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1714): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/BitmapFactory( 1714): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  888): uri = 14 selection = getSealedState
,D/SecContentProvider2(  888): mCursor = null
D/SecContentProvider2(  888): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  888): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy(  888): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/StatusBar( 1171): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,I/PhoneStatusBar( 1171): Icon Only
,D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
D/PanelView( 1171): There is/are notification(s) 
,D/PanelView( 1171): There is/are notification(s) 
,W/GLSActivity( 1714): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1714): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1714): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1714): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1714): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1714): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1714): 	at android.os.Binder.execTransact(Binder.java:446)
,E/BooksAccountManager( 7687): Authentication error
E/BooksAccountManager( 7687): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 7687): android.accounts.AccountManager.convertErrorToException(AccountManager.java:1893)
,E/HttpHelper( 7687): null auth token
,I/qtaguid ( 7687): Tagging socket 34 with tag 10000000000{256,0} uid -1, pid: 7687, getuid(): 10082
,I/ServiceManager(  360): Waiting for service AtCmdFwd...
,I/qtaguid ( 7687): Untagging socket 34
,W/ApiaryClient( 7687): Error response from books API: {
W/ApiaryClient( 7687):  "error": {
W/ApiaryClient( 7687):   "errors": [
W/ApiaryClient( 7687):    {
W/ApiaryClient( 7687):     "domain": "global",
W/ApiaryClient( 7687):     "reason": "required",
W/ApiaryClient( 7687):     "message": "Login Required",
W/ApiaryClient( 7687):     "locationType": "header",
W/ApiaryClient( 7687):     "location": "Authorization"
W/ApiaryClient( 7687):    }
W/ApiaryClient( 7687):   ],
W/ApiaryClient( 7687):   "code": 401,
W/ApiaryClient( 7687):   "message": "Login Required"
W/ApiaryClient( 7687):  }
W/ApiaryClient( 7687): }
,W/ApiaryClient( 7687): errCount = 2: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 7687): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3DS0HXd4TFLU4&nonce=-6764129987466790599&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 7687): Headers suppressed
,D/ConnectivityService(  888): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/ServiceManager(  360): Waiting for service AtCmdFwd...
,V/GLSActivity( 1714): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1714): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
,I/GLSUser ( 1714): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1714): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1714): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1714): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/BitmapFactory( 1714): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  888): uri = 14 selection = getSealedState
,D/SecContentProvider2(  888): mCursor = null
D/SecContentProvider2(  888): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  888): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy(  888): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/StatusBar( 1171): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,I/PhoneStatusBar( 1171): Icon Only
,D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
,D/PanelView( 1171): There is/are notification(s) 
D/PanelView( 1171): There is/are notification(s) 
,W/GLSActivity( 1714): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1714): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1714): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1714): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1714): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1714): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1714): 	at android.os.Binder.execTransact(Binder.java:446)
,E/BooksAccountManager( 7687): Authentication error
E/BooksAccountManager( 7687): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 7687): android.accounts.AccountManager.convertErrorToException(AccountManager.java:1893)
,E/HttpHelper( 7687): null auth token
,I/qtaguid ( 7687): Tagging socket 34 with tag 10000000000{256,0} uid -1, pid: 7687, getuid(): 10082
,I/qtaguid ( 7687): Untagging socket 34
,W/ApiaryClient( 7687): Error response from books API: {
W/ApiaryClient( 7687):  "error": {
W/ApiaryClient( 7687):   "errors": [
W/ApiaryClient( 7687):    {
W/ApiaryClient( 7687):     "domain": "global",
W/ApiaryClient( 7687):     "reason": "required",
W/ApiaryClient( 7687):     "message": "Login Required",
W/ApiaryClient( 7687):     "locationType": "header",
W/ApiaryClient( 7687):     "location": "Authorization"
W/ApiaryClient( 7687):    }
W/ApiaryClient( 7687):   ],
W/ApiaryClient( 7687):   "code": 401,
W/ApiaryClient( 7687):   "message": "Login Required"
W/ApiaryClient( 7687):  }
W/ApiaryClient( 7687): }
,W/ApiaryClient( 7687): errCount = 3: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 7687): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3DS0HXd4TFLU4&nonce=-6764129987466790599&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 7687): Headers suppressed
,D/ConnectivityService(  888): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/SMD     (  289): DCD ON
,I/ServiceManager(  360): Waiting for service AtCmdFwd...
,E/BooksSync( 7687): Soft error
E/BooksSync( 7687): com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
E/BooksSync( 7687): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3DS0HXd4TFLU4&nonce=-6764129987466790599&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
E/BooksSync( 7687): Headers suppressed
E/BooksSync( 7687): 
E/BooksSync( 7687): com.google.android.apps.books.net.HttpHelper.wrapExceptionBasedOnStatus(HttpHelper.java:212)
,E/BooksSync( 7687): Sync error
E/BooksSync( 7687): com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
E/BooksSync( 7687): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3DS0HXd4TFLU4&nonce=-6764129987466790599&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
E/BooksSync( 7687): Headers suppressed
E/BooksSync( 7687): 
E/BooksSync( 7687): com.google.android.apps.books.net.HttpHelper.wrapExceptionBasedOnStatus(HttpHelper.java:212)
,I/BooksSync( 7687): Finished books sync
,D/ConnectivityService(  888): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SyncManager(  888): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 221481, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,D/ConnectivityService(  888): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SecContentProvider2(  888): uri = 11 selection = getMyKnoxAdmin
,D/SecContentProvider2(  888): mCursor = null
,D/ConnectivityService(  888): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/ServiceManager(  360): Waiting for service AtCmdFwd...
,W/ContextImpl(  888): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,W/Atfwd_Sendcmd(  360): AtCmdFwd service not published, waiting... retryCnt : 3
,E/SMD     (  289): DCD ON
,E/Watchdog(  888): !@Sync 8
,E/SMD     (  289): DCD ON
,D/ConnectivityService(  888): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SSRM:m  (  888): SIOP:: AP = 290, PST = 297, CUR = 300
,E/SMD     (  289): DCD ON
,E/SMD     (  289): DCD ON
,E/SMD     (  289): DCD ON
,D/BatteryService(  888): level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 284, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  888): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  888): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  888):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  888): Plugged
,I/MotionRecognitionService(  888): setPowerConnected  = true
,D/BatteryService(  888): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1171): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1171): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1171):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3252): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3252): Disconnected process message: 10
,D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/ServiceManager(  360): Waiting for service AtCmdFwd...
,D/SSRM:m  (  888): SIOP:: AP = 290, PST = 295, CUR = 300
,E/SMD     (  289): DCD ON
,I/ServiceManager(  360): Waiting for service AtCmdFwd...
,I/ServiceManager(  360): Waiting for service AtCmdFwd...
,I/ServiceManager(  360): Waiting for service AtCmdFwd...
,E/SMD     (  289): DCD ON
,I/ServiceManager(  360): Waiting for service AtCmdFwd...
,W/ContextImpl(  888): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,W/Atfwd_Sendcmd(  360): AtCmdFwd service not published, waiting... retryCnt : 4
,E/SMD     (  289): DCD ON
,V/AlarmManager(  888): waitForAlarm result :4
,D/ConnectivityService(  888): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/BatteryService(  888): level:100, scale:100, status:5, health:2, present:true, voltage: 4383, temperature: 284, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  888): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
D/BatteryService(  888): stay LED for fully charged
,D/BatteryService(  888): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  888):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  888): Plugged
I/MotionRecognitionService(  888): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1171): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1171): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1171):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3252): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3252): Disconnected process message: 10
,D/ConnectivityService(  888): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  289): DCD ON
,I/art     ( 1714): Explicit concurrent mark sweep GC freed 50351(2MB) AllocSpace objects, 51(3MB) LOS objects, 40% free, 18MB/30MB, paused 951us total 125.312ms
,I/GLSUser ( 1714): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,I/GLSUser ( 1714): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1714): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1714): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1714): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/ResourcesManager( 1714): creating new AssetManager and set to /system/app/PlusOne/PlusOne.apk
V/BitmapFactory( 1714): DecodeImagePath(decodeResourceStream3) : res/mipmap-xxhdpi-v4/quantum_logo_google_plus_color_44in48.png
V/BitmapFactory( 1714): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  888): uri = 14 selection = getSealedState
,D/SecContentProvider2(  888): mCursor = null
D/SecContentProvider2(  888): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  888): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
V/ApplicationPolicy(  888): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/StatusBar( 1171): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,E/HttpOperation( 5282): [kfu{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
E/HttpOperation( 5282): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 5282): 	at kfv.a(PG:65)
E/HttpOperation( 5282): 	at kff.u(PG:385)
E/HttpOperation( 5282): 	at kfb.a(PG:29)
E/HttpOperation( 5282): 	at kff.l(PG:132)
E/HttpOperation( 5282): 	at dsf.a(PG:807)
E/HttpOperation( 5282): 	at fhk.a(PG:1126)
E/HttpOperation( 5282): 	at fhk.a(PG:908)
E/HttpOperation( 5282): 	at fhk.onPerformSync(PG:636)
E/HttpOperation( 5282): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/HttpOperation( 5282): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/HttpOperation( 5282): 	at ihi.a(PG:22)
E/HttpOperation( 5282): 	at kft.a(PG:91)
E/HttpOperation( 5282): 	at kfv.a(PG:62)
E/HttpOperation( 5282): 	... 8 more
E/HttpOperation( 5282): Caused by: gdi: User intervention required. Notification has been pushed.
E/HttpOperation( 5282): 	at gde.c(Unknown Source)
E/HttpOperation( 5282): 	at gde.b(Unknown Source)
E/HttpOperation( 5282): 	at ihi.a(PG:19)
E/HttpOperation( 5282): 	... 10 more
,I/PhoneStatusBar( 1171): Icon Only
D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
D/PanelView( 1171): There is/are notification(s) 
D/PanelView( 1171): There is/are notification(s) 
,I/GLSUser ( 1714): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
I/GLSUser ( 1714): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1714): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1714): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1714): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/BitmapFactory( 1714): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  888): uri = 14 selection = getSealedState
,D/SecContentProvider2(  888): mCursor = null
,D/SecContentProvider2(  888): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  888): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
V/ApplicationPolicy(  888): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/StatusBar( 1171): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,E/HttpOperation( 5282): [getmobileexperiments] Unexpected exception
E/HttpOperation( 5282): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 5282): 	at kfv.a(PG:65)
E/HttpOperation( 5282): 	at kff.u(PG:385)
E/HttpOperation( 5282): 	at kfb.a(PG:29)
E/HttpOperation( 5282): 	at kff.l(PG:132)
E/HttpOperation( 5282): 	at ieo.a(PG:43)
E/HttpOperation( 5282): 	at iep.a(PG:93)
E/HttpOperation( 5282): 	at fhn.a(PG:59)
E/HttpOperation( 5282): 	at lex.a(PG:85)
E/HttpOperation( 5282): 	at lex.b(PG:132)
E/HttpOperation( 5282): 	at fhk.a(PG:1146)
E/HttpOperation( 5282): 	at fhk.a(PG:908)
E/HttpOperation( 5282): 	at fhk.onPerformSync(PG:636)
E/HttpOperation( 5282): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/HttpOperation( 5282): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/HttpOperation( 5282): 	at ihi.a(PG:22)
E/HttpOperation( 5282): 	at kft.a(PG:91)
E/HttpOperation( 5282): 	at kfv.a(PG:62)
E/HttpOperation( 5282): 	... 12 more
E/HttpOperation( 5282): Caused by: gdi: User intervention required. Notification has been pushed.
E/HttpOperation( 5282): 	at gde.c(Unknown Source)
E/HttpOperation( 5282): 	at gde.b(Unknown Source)
E/HttpOperation( 5282): 	at ihi.a(PG:19)
E/HttpOperation( 5282): 	... 14 more
,E/ExperimentLoader( 5282): [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 5282): java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 5282): 	at kfv.a(PG:65)
E/ExperimentLoader( 5282): 	at kff.u(PG:385)
E/ExperimentLoader( 5282): 	at kfb.a(PG:29)
E/ExperimentLoader( 5282): 	at kff.l(PG:132)
E/ExperimentLoader( 5282): 	at ieo.a(PG:43)
E/ExperimentLoader( 5282): 	at iep.a(PG:93)
E/ExperimentLoader( 5282): 	at fhn.a(PG:59)
E/ExperimentLoader( 5282): 	at lex.a(PG:85)
E/ExperimentLoader( 5282): 	at lex.b(PG:132)
E/ExperimentLoader( 5282): 	at fhk.a(PG:1146)
E/ExperimentLoader( 5282): 	at fhk.a(PG:908)
E/ExperimentLoader( 5282): 	at fhk.onPerformSync(PG:636)
E/ExperimentLoader( 5282): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/ExperimentLoader( 5282): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/ExperimentLoader( 5282): 	at ihi.a(PG:22)
E/ExperimentLoader( 5282): 	at kft.a(PG:91)
E/ExperimentLoader( 5282): 	at kfv.a(PG:62)
E/ExperimentLoader( 5282): 	... 12 more
E/ExperimentLoader( 5282): Caused by: gdi: User intervention required. Notification has been pushed.
E/ExperimentLoader( 5282): 	at gde.c(Unknown Source)
E/ExperimentLoader( 5282): 	at gde.b(Unknown Source)
E/ExperimentLoader( 5282): 	at ihi.a(PG:19)
E/ExperimentLoader( 5282): 	... 14 more
I/PhoneStatusBar( 1171): Icon Only
D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
D/PanelView( 1171): There is/are notification(s) 
D/PanelView( 1171): There is/are notification(s) 
,I/GLSUser ( 1714): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,I/GLSUser ( 1714): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1714): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1714): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1714): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/BitmapFactory( 1714): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  888): uri = 14 selection = getSealedState
D/SecContentProvider2(  888): mCursor = null
,D/SecContentProvider2(  888): KnoxCustomManagerService offline: service is not available
I/PowerManagerService(  888): [PWL] Off : 140s ago
,I/PowerManagerService(  888): [PWL]   PowerManagerService.WakeLocks: ref count=1
I/PowerManagerService(  888): [PWL]     mWakeLockSummary : 0x1
I/PowerManagerService(  888): [PWL]       PARTIAL_WAKE_LOCK              '*sync*/com.google.android.apps.plus.content.EsProvider/com.google/eM_ADDR' (uid=1000, pid=888, ws=WorkSource{10135}) (elapsedTime=757)
,D/ApplicationPolicy(  888): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
V/ApplicationPolicy(  888): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,E/SQLiteLog( 1714): (10) POSIX Error : 11 SQLite Error : 3850
,D/StatusBar( 1171): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,I/PhoneStatusBar( 1171): Icon Only
,D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
,D/PanelView( 1171): There is/are notification(s) 
D/PanelView( 1171): There is/are notification(s) 
,E/HttpOperation( 5282): [getaccountstatus] Unexpected exception
E/HttpOperation( 5282): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 5282): 	at kfv.a(PG:65)
E/HttpOperation( 5282): 	at kff.u(PG:385)
E/HttpOperation( 5282): 	at kfb.a(PG:29)
E/HttpOperation( 5282): 	at ixd.a(PG:248)
E/HttpOperation( 5282): 	at ixd.b(PG:206)
E/HttpOperation( 5282): 	at ixd.a(PG:175)
E/HttpOperation( 5282): 	at fig.a(PG:78)
E/HttpOperation( 5282): 	at lex.a(PG:85)
E/HttpOperation( 5282): 	at lex.b(PG:132)
E/HttpOperation( 5282): 	at fhk.a(PG:1146)
E/HttpOperation( 5282): 	at fhk.a(PG:908)
E/HttpOperation( 5282): 	at fhk.onPerformSync(PG:636)
E/HttpOperation( 5282): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/HttpOperation( 5282): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/HttpOperation( 5282): 	at ihi.a(PG:22)
E/HttpOperation( 5282): 	at kft.a(PG:91)
E/HttpOperation( 5282): 	at kfv.a(PG:62)
E/HttpOperation( 5282): 	... 12 more
E/HttpOperation( 5282): Caused by: gdi: User intervention required. Notification has been pushed.
E/HttpOperation( 5282): 	at gde.c(Unknown Source)
E/HttpOperation( 5282): 	at gde.b(Unknown Source)
E/HttpOperation( 5282): 	at ihi.a(PG:19)
E/HttpOperation( 5282): 	... 14 more
,E/EsSyncAdapterService( 5282): Sync failure
E/EsSyncAdapterService( 5282): java.io.IOException: Rpc failed
E/EsSyncAdapterService( 5282): 	at ixd.a(PG:348)
E/EsSyncAdapterService( 5282): 	at ixd.a(PG:248)
E/EsSyncAdapterService( 5282): 	at ixd.b(PG:206)
E/EsSyncAdapterService( 5282): 	at ixd.a(PG:175)
E/EsSyncAdapterService( 5282): 	at fig.a(PG:78)
E/EsSyncAdapterService( 5282): 	at lex.a(PG:85)
E/EsSyncAdapterService( 5282): 	at lex.b(PG:132)
E/EsSyncAdapterService( 5282): 	at fhk.a(PG:1146)
E/EsSyncAdapterService( 5282): 	at fhk.a(PG:908)
E/EsSyncAdapterService( 5282): 	at fhk.onPerformSync(PG:636)
E/EsSyncAdapterService( 5282): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/EsSyncAdapterService( 5282): Caused by: java.io.IOException: Cannot obtain authentication token
E/EsSyncAdapterService( 5282): 	at kfv.a(PG:65)
E/EsSyncAdapterService( 5282): 	at kff.u(PG:385)
E/EsSyncAdapterService( 5282): 	at kfb.a(PG:29)
E/EsSyncAdapterService( 5282): 	... 10 more
E/EsSyncAdapterService( 5282): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/EsSyncAdapterService( 5282): 	at ihi.a(PG:22)
E/EsSyncAdapterService( 5282): 	at kft.a(PG:91)
E/EsSyncAdapterService( 5282): 	at kfv.a(PG:62)
E/EsSyncAdapterService( 5282): 	... 12 more
E/EsSyncAdapterService( 5282): Caused by: gdi: User intervention required. Notification has been pushed.
E/EsSyncAdapterService( 5282): 	at gde.c(Unknown Source)
E/EsSyncAdapterService( 5282): 	at gde.b(Unknown Source)
E/EsSyncAdapterService( 5282): 	at ihi.a(PG:19)
E/EsSyncAdapterService( 5282): 	... 14 more
,D/ConnectivityService(  888): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SyncManager(  888): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, SERVER, currentRunTime 251958, reason: 10135, SyncResult: stats [ numIoExceptions: 2]
,D/ConnectivityService(  888): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  888): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SecContentProvider2(  888): uri = 11 selection = getMyKnoxAdmin
D/SecContentProvider2(  888): mCursor = null
,D/SSRM:m  (  888): SIOP:: AP = 290, PST = 294, CUR = 300
,E/SQLiteLog( 1714): (10) POSIX Error : 11 SQLite Error : 3850
,E/SMD     (  289): DCD ON
,E/SMD     (  289): DCD ON
,E/Watchdog(  888): !@Sync 9
,E/SMD     (  289): DCD ON
,D/SSRM:m  (  888): SIOP:: AP = 290, PST = 293, CUR = 300
,E/SMD     (  289): DCD ON
,W/ContextImpl(  888): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  289): DCD ON
,I/ServiceManager(  360): Waiting for service AtCmdFwd...
,I/ServiceManager(  360): Waiting for service AtCmdFwd...
,I/ServiceManager(  360): Waiting for service AtCmdFwd...
,E/SMD     (  289): DCD ON
,I/ServiceManager(  360): Waiting for service AtCmdFwd...
,I/ServiceManager(  360): Waiting for service AtCmdFwd...
,W/Atfwd_Sendcmd(  360): AtCmdFwd service not published, waiting... retryCnt : 5
,E/SMD     (  289): DCD ON
,D/SSRM:m  (  888): SIOP:: AP = 290, PST = 292, CUR = 300
,E/SMD     (  289): DCD ON
,V/AlarmManager(  888): waitForAlarm result :8
,E/SMD     (  289): DCD ON
,V/AlarmManager(  888): waitForAlarm result :4
,D/KeyguardUpdateMonitor( 1171): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1171): handleTimeUpdate
,D/KeyguardEffectViewController( 1171): onReceive action : android.intent.action.TIME_TICK
,I/KeyguardEffectViewController( 1171): *** don't update sliding image ***
,E/SMD     (  289): DCD ON
,D/DateView( 1171): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1171): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/ConnectivityService(  888): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SSRM:m  (  888): SIOP:: AP = 290, PST = 291, CUR = 300
,E/SMD     (  289): DCD ON
,D/TimaService(  888): TIMA: TimaService scheduler is intialized. 
,D/TimaService(  888): TimaServiceHandler.handleMessage what =1
,D/TimaService(  888): TIMA: checkEvent, operation: 50000 subject: 10000
,I/TLC_TIMA_PKM_initialize(  888): initializing...
,I/TLC_TIMA_PKM_initialize(  888): root = /firmware/image, root_strlen = 15
,I/TLC_TIMA_PKM_initialize(  888): process = tima_pkm, process_strlen = 8
,I/TZ: qc_tlc_communication(  888): root = /firmware/image, root_len = 15
,I/TZ: qc_tlc_communication(  888): process = tima_pkm, process_strlen = 8
,I/TZ: qc_tlc_communication(  888): aligned max_sendmsg_size = 262208 = 0x40040
,I/TZ: qc_tlc_communication(  888): aligned max_recvmsg_size = 262208 = 0x40040
,I/TZ: qc_tlc_communication(  888): max_message_size = 524416 = 0x80080
,D/QSEECOMAPI: (  888): QSEECom_get_handle sb_length = 0x80080
,D/QSEECOMAPI: (  888): App is not loaded in QSEE
,D/QSEECOMAPI: (  888): Loaded image: APP id = 3
,I/TZ: qc_tlc_communication(  888): TIMA: path = /firmware/image, fname = tima_pkm, tzapp is loaded
,I/TLC_TIMA_PKM_initialize(  888): Trustlet response is completed
,W/ContextImpl(  888): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  289): DCD ON
,E/Watchdog(  888): !@Sync 10
,I/TLC_TIMA_PKM_measure_kernel(  888): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel(  888): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService(  888): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService(  888): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,E/SMD     (  289): DCD ON
,I/PowerManagerService(  888): [PWL] Off : 180s ago
,D/SSRM:m  (  888): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  289): DCD ON
,E/SMD     (  289): DCD ON
,I/Atfwd_Sendcmd(  360): AtCmdFwd service not ready - Exhausted retry attempts - :6
I/Atfwd_Daemon(  360): result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,E/SMD     (  289): DCD ON
,E/SMD     (  289): DCD ON
,D/SSRM:m  (  888): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  289): DCD ON
,W/ContextImpl(  888): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,V/AlarmManager(  888): waitForAlarm result :4
,E/ActivityManager(  888): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  888): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  888): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  888): checkUser: useridlist=null, currentuser=0
,D/BatteryService(  888): level:100, scale:100, status:5, health:2, present:true, voltage: 4383, temperature: 283, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,E/Zygote  ( 8608): MountEmulatedStorage()
,E/Zygote  ( 8608): v2
I/libpersona( 8608): KNOX_SDCARD checking this for 10081
I/libpersona( 8608): KNOX_SDCARD not a persona
,I/ActivityManager(  888): Start proc com.blurb.checkout for broadcast com.blurb.checkout/.RebootReceiver: pid=8608 uid=10081 gids={50081, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,D/BatteryService(  888): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  888): stay LED for fully charged
,D/BatteryService(  888): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  888):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  888): Plugged
I/MotionRecognitionService(  888): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1171): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1171): handleBatteryUpdate
,V/HeadsetService( 3252): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,I/SELinux ( 8608): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 8608): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,D/HeadsetStateMachine( 3252): Disconnected process message: 10
,E/SELinux ( 8608): [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
,D/STATUSBAR-PhoneStatusBar( 1171):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/TimaKeyStoreProvider( 8608): TimaSignature is unavailable
,D/ActivityThread( 8608): Added TimaKeyStore provider
,D/ResourcesManager( 8608): creating new AssetManager and set to /system/app/Blurb/Blurb.apk
,I/ActivityManager(  888): Killing 7451:com.sec.esdk.elm/u0a104 (adj 15): bgCount ##41
,W/libprocessgroup(  888): failed to open /acct/uid_10104/pid_7451/cgroup.procs: No such file or directory
,E/SMD     (  289): DCD ON
,I/ActivityManager(  888): Killing 7188:com.sec.android.widgetapp.SPlannerAppWidget/u0a149 (adj 15): bgCount ##41
,W/libprocessgroup(  888): failed to open /acct/uid_10149/pid_7188/cgroup.procs: No such file or directory,
,I/jxcore-log( 7760): --= Surplus to requirements =--
I/jxcore-log( 7760): 
,I/jxcore-log( 7760): ****TEST TOOK:  ms ****
I/jxcore-log( 7760): 
I/jxcore-log( 7760): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 7760): 
,E/SMD     (  289): DCD ON
,D/AndroidRuntime( 8650): 
D/AndroidRuntime( 8650): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
,D/AndroidRuntime( 8650): CheckJNI is OFF
,D/AndroidRuntime( 8650): setted country_code = Germany
,D/AndroidRuntime( 8650): setted countryiso_code = DE
,D/AndroidRuntime( 8650): setted sales_code = DBT
,D/AndroidRuntime( 8650): readGMSProperty: start
D/AndroidRuntime( 8650): readGMSProperty: already setted!!
D/AndroidRuntime( 8650): readGMSProperty: end
,D/AndroidRuntime( 8650): addProductProperty: start
,V/AlarmManager(  888): waitForAlarm result :4
,D/ConnectivityService(  888): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  888): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/BooksSync( 7687): Starting books sync, d
,D/ConnectivityService(  888): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,V/GLSActivity( 1714): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1714): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
,I/GLSUser ( 1714): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1714): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1714): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1714): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ResourcesManager( 1714): creating new AssetManager and set to /system/app/Books/Books.apk
,V/BitmapFactory( 1714): DecodeImagePath(decodeResourceStream3) : res/mipmap-xxhdpi-v4/ic_launcher_play_books.png
,V/BitmapFactory( 1714): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  888): uri = 14 selection = getSealedState
D/SecContentProvider2(  888): mCursor = null
,D/SecContentProvider2(  888): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  888): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
V/ApplicationPolicy(  888): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,W/GLSActivity( 1714): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1714): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1714): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1714): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1714): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1714): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1714): 	at android.os.Binder.execTransact(Binder.java:446)
,E/BooksAccountManager( 7687): Authentication error
E/BooksAccountManager( 7687): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 7687): android.accounts.AccountManager.convertErrorToException(AccountManager.java:1893)
,E/HttpHelper( 7687): null auth token
,E/AffinityControl( 8650): AffinityControl: registerfunction enter
,D/StatusBar( 1171): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,I/qtaguid ( 7687): Tagging socket 34 with tag 10000000000{256,0} uid -1, pid: 7687, getuid(): 10082
,I/PhoneStatusBar( 1171): Icon Only
,D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1171): value : false
,D/PanelView( 1171): There is/are notification(s) 
D/PanelView( 1171): There is/are notification(s) 
,D/AndroidRuntime( 8650): Calling main entry com.android.commands.pm.Pm
,D/PackageManager(  888): START PACKAGE DELETE: observer{220906162}
D/PackageManager(  888): pkg{<packageName>}
D/PackageManager(  888): user{0}
D/PackageManager(  888): caller{2000}
D/PackageManager(  888): flags{3}
,D/PersonaManagerService(  888): isFromApprovedUnInstaller: uid, userId, appid : 2000 0 2000
D/PersonaManagerService(  888): isFromApprovedUnInstaller: isApproved : true
D/PersonaManagerService(  888): isFromApprovedUnInstaller: isApproved before exit: true
D/PackageManager(  888): deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag3
,D/PackageManager(  888): deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag3
,D/PackageManager(  888): [MSG] DELETE_PACKAGE_AS_USER
,D/PackageManagerService(  888): deletePackage- pkg:com.test.thalitest, edmuserId:0
D/PackageManagerService(  888): deletePackage- pkg:com.test.thalitest, edmuserId:-1
,D/ApplicationPolicy(  888): getApplicationUninstallationEnabled
,D/ApplicationPolicy(  888): getApplicationUninstallationEnabled :  enabled true
,D/PackageManager(  888): !@killApplicatoin: 10367, uninstall pkg
,I/ActivityManager(  888): Force stopping com.test.thalitest appid=10367 user=-1: uninstall pkg
,I/ActivityManager(  888): Killing 7760:com.test.thalitest/u0a367 (adj 0): stop com.test.thalitest
,I/ServiceManager(  360): Waiting for service AtCmdFwd...
,I/ActivityManager(  888):   Force finishing activity ActivityRecord{bfb5867 u0 com.test.thalitest/.MainActivity t11}
,D/FocusedStackFrame(  888): Set to : 0
,D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1171): value : false
,I/SurfaceFlinger(  249): id=15 Removed com.test.thalitest/com.test.thalitest.MainActivity (5/8)
,I/SurfaceFlinger(  249): id=15 Removed com.test.thalitest/com.test.thalitest.MainActivity (-2/8)
D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
,D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
,I/qtaguid ( 7687): Untagging socket 34
,W/ApiaryClient( 7687): Error response from books API: {
W/ApiaryClient( 7687):  "error": {
W/ApiaryClient( 7687):   "errors": [
W/ApiaryClient( 7687):    {
W/ApiaryClient( 7687):     "domain": "global",
W/ApiaryClient( 7687):     "reason": "required",
W/ApiaryClient( 7687):     "message": "Login Required",
W/ApiaryClient( 7687):     "locationType": "header",
W/ApiaryClient( 7687):     "location": "Authorization"
W/ApiaryClient( 7687):    }
W/ApiaryClient( 7687):   ],
W/ApiaryClient( 7687):   "code": 401,
W/ApiaryClient( 7687):   "message": "Login Required"
W/ApiaryClient( 7687):  }
W/ApiaryClient( 7687): }
,W/ApiaryClient( 7687): errCount = 1: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 7687): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3DS0HXd4TFLU4&nonce=1610344782266698187&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 7687): Headers suppressed
,D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
,W/PackageSettings(  888): Skipping PackageSetting{3501d969 com.example.hello/10375} due to missing metadata
,D/ConnectivityService(  888): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/ActivityManager(  888): Force stopping com.test.thalitest appid=10367 user=0: pkg removed
D/ConnectivityService(  888): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/WifiService(  888): Client connection lost with reason: 4
,I/art     ( 1569): Explicit concurrent mark sweep GC freed 6560(527KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 16MB/27MB, paused 547us total 24.274ms
,I/art     ( 4461): Explicit concurrent mark sweep GC freed 4026(225KB) AllocSpace objects, 1(16KB) LOS objects, 40% free, 14MB/24MB, paused 338us total 21.429ms
,D/ResourcesManager(  888): creating new AssetManager and set to /system/priv-app/Velvet/Velvet.apk
,D/ResourcesManager(  888): creating new AssetManager and set to /system/priv-app/InputDevices/InputDevices.apk
,D/ResourcesManager( 1465): creating new AssetManager and set to /system/app/AccuweatherPhone2014_K_LMR_fHD/AccuweatherPhone2014_K_LMR_fHD.apk
,E/SamsungIME( 1830): mOCRHelper is null
,W/ResourcesManager( 1465): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 1465): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 1465): Asset path '/system/framework/sws.jar' does not exist or contains no resources.
,I/InputReader(  888): Reconfiguring input devices.  changes=0x00000010
,D/ResourcesManager( 1465): creating new AssetManager and set to /system/app/SPlannerWidget_OS_UPG/SPlannerWidget_OS_UPG.apk
,W/ResourcesManager( 1465): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 1465): Asset path '/system/framework/sws.jar' does not exist or contains no resources.
,W/GeofencerStateMachine( 2250): Ignoring removeGeofence because network location is disabled.
,D/ResourcesManager(  888): creating new AssetManager and set to /system/app/SamsungIME/SamsungIME.apk
,I/KLMS-2.4.503: ( 7386): KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,I/KLMS-2.4.503: ( 7386): MainReciver(): EventNotificationReciver- method called: AppActivityListner onReceive for Intent Action : android.intent.action.PACKAGE_REMOVED , timestamp: 1452525874036
,I/KLMS-2.4.503: ( 7386): MainReciver(): PACKAGE_REMOVED
,I/KLMS-2.4.503: ( 7386): MainReciver(): REPLACING: false | pkgName: com.test.thalitest
,E/libprocessgroup(  888): failed to kill 1 processes for processgroup 7760
,I/art     (  888): Explicit concurrent mark sweep GC freed 61099(4MB) AllocSpace objects, 60(1610KB) LOS objects, 30% free, 36MB/52MB, paused 5.211ms total 144.832ms
,D/ResourcesManager(  888): creating new AssetManager and set to /data/app/com.google.android.gms-1/base.apk
,I/art     (  888): WaitForGcToComplete blocked for 132.764ms for cause Explicit
,D/ResourcesManager(  888): creating new AssetManager and set to /system/priv-app/SNS/SNS.apk
,D/ResourcesManager(  888): creating new AssetManager and set to /system/priv-app/Samsungservice2_xxhdpi/Samsungservice2_xxhdpi.apk
,D/ResourcesManager(  888): creating new AssetManager and set to /system/app/ChatON_MARKET/ChatON_MARKET.apk
,D/ResourcesManager(  888): creating new AssetManager and set to /system/app/Dropbox/Dropbox.apk
,D/SecContentProvider2(  888): uri = 11 selection = getMyKnoxAdmin
,D/SecContentProvider2(  888): mCursor = null
,D/ResourcesManager(  888): creating new AssetManager and set to /system/app/Gmail2/Gmail2.apk
,E/ActivityManager(  888): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  888): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  888): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  888): checkUser: useridlist=null, currentuser=0
,D/ResourcesManager(  888): creating new AssetManager and set to /system/app/SBrowser/SBrowser.apk
,D/ResourcesManager(  888): creating new AssetManager and set to /system/app/SecEmail_K/SecEmail_K.apk
,E/Zygote  ( 8684): MountEmulatedStorage()
I/libpersona( 8684): KNOX_SDCARD checking this for 10104
E/Zygote  ( 8684): v2
I/libpersona( 8684): KNOX_SDCARD not a persona
,D/ResourcesManager(  888): creating new AssetManager and set to /system/priv-app/Velvet/Velvet.apk
,I/ActivityManager(  888): Start proc com.sec.esdk.elm for broadcast com.sec.esdk.elm/.receiver.MainReceiver: pid=8684 uid=10104 gids={50104, 9997, 3003} abi=armeabi-v7a
,D/ResourcesManager(  888): creating new AssetManager and set to /system/priv-app/GoogleServicesFramework/GoogleServicesFramework.apk
,D/ResourcesManager(  888): creating new AssetManager and set to /system/priv-app/SHealth3_5/SHealth3_5.apk
,I/SELinux ( 8684): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,D/RegisteredServicesCache( 1453): empty dynamic service
,I/SELinux ( 8684): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 8684): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/ResourcesManager(  888): creating new AssetManager and set to /system/priv-app/SecGallery2014/SecGallery2014.apk
,D/ResourcesManager(  888): creating new AssetManager and set to /system/priv-app/sCloudSyncCalendar/sCloudSyncCalendar.apk
,D/ResourcesManager(  888): creating new AssetManager and set to /system/priv-app/sCloudSyncContacts/sCloudSyncContacts.apk
,D/ResourcesManager(  888): creating new AssetManager and set to /system/priv-app/sCloudSyncMemo/sCloudSyncMemo.apk
,D/ResourcesManager(  888): creating new AssetManager and set to /system/priv-app/sCloudSyncSBrowser/sCloudSyncSBrowser.apk
,D/ResourcesManager(  888): creating new AssetManager and set to /system/priv-app/sCloudSyncSNote3/sCloudSyncSNote3.apk
,D/ResourcesManager(  888): creating new AssetManager and set to /system/app/Books/Books.apk
,D/ResourcesManager(  888): creating new AssetManager and set to /system/app/Chrome/Chrome.apk
,D/ResourcesManager(  888): creating new AssetManager and set to /system/app/Drive/Drive.apk
,D/ResourcesManager(  888): creating new AssetManager and set to /system/app/talkback/talkback.apk
,D/ResourcesManager(  888): creating new AssetManager and set to /system/app/EditorsDocs/EditorsDocs.apk
,D/TimaKeyStoreProvider( 8684): TimaSignature is unavailable
,D/ResourcesManager(  888): creating new AssetManager and set to /system/app/GoogleCalendarSyncAdapter/GoogleCalendarSyncAdapter.apk
D/ActivityThread( 8684): Added TimaKeyStore provider
,D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
,D/ResourcesManager(  888): creating new AssetManager and set to /system/app/GoogleContactsSyncAdapter/GoogleContactsSyncAdapter.apk
,D/ResourcesManager(  888): creating new AssetManager and set to /system/app/Music2/Music2.apk
,D/ResourcesManager(  888): creating new AssetManager and set to /system/app/Newsstand/Newsstand.apk
,D/ResourcesManager(  888): creating new AssetManager and set to /system/app/PlusOne/PlusOne.apk
,D/ResourcesManager( 8684): creating new AssetManager and set to /system/app/ELMAgent/ELMAgent.apk
,D/EnterpriseDeviceManagerService(  888): Package has changed for user 0
D/EnterpriseDeviceManagerService(  888): Admin package name: com.google.android.gms
,D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
,D/SurfaceWidgetView( 1465): destroyHardwareResources():150116021
,D/ResourcesManager(  888): creating new AssetManager and set to /system/priv-app/SecContacts/SecContacts.apk
,V/WindowOrientationListener(  888): mSContextAutoRotationListener.getProposedRotation, mbResultFaceDectection: false
V/WindowOrientationListener(  888): mSContextAutoRotationListener.getProposedRotation, Rotation: -1
D/ResourcesManager(  888): creating new AssetManager and set to /system/app/SecExchange/SecExchange.apk
V/WindowManager(  888): rotationForOrientationLw(orient=1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false
V/WindowOrientationListener(  888): mSContextAutoRotationListener.getProposedRotation, mbResultFaceDectection: false
V/WindowOrientationListener(  888): mSContextAutoRotationListener.getProposedRotation, Rotation: -1
,D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
,D/Launcher( 1465): onRestart, Launcher: 477092031
D/ResourcesManager(  888): creating new AssetManager and set to /system/app/Videos/Videos.apk
,D/Launcher( 1465): onStart, Launcher: 477092031
D/Launcher.HomeView( 1465): onStart
,D/SurfaceWidgetClient$ISurfaceWidgetStub( 2029): [237392/6] Surface widget visibility changed visibility = true on instance = 1
,D/SurfaceWidget.Renderer( 2029): [237392/6] SurfaceWidget drawing first frame
,D/elm:14451( 8684): ELMAbstractReceiver.onReceive() : Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.receiver.MainReceiver (has extras) }
,D/elm:14451( 8684): ELMEngine.ELMEngine( context ).
,D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
,W/Resources(  888): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/ResourcesManager(  888): creating new AssetManager and set to /system/priv-app/SecMms_Candy/SecMms_Candy.apk
,I/SurfaceFlinger(  249): id=18 createSurf (1080x1920),1 flag=4, com.sec.android.app.launcher/com.android.launcher2.Launcher
,D/StatusBarManagerService(  888): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
,D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
,D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
,D/StatusBarManagerService(  888): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
,D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
,D/elm:14451( 8684): MDMBridge.setEnterpriseBridge()
,D/InputMethodManagerService(  888): windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,W/InputMethodManagerService(  888): Got RemoteException sending setActive(false) notification to pid 7760 uid 10367
,W/ContextImpl(  888): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.android.server.InputMethodManagerService$6.run:2728 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/elm:14451( 8684): ELMAbstractReceiver : Receive Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) } END.
,E/ActivityManager(  888): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  888): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  888): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  888): checkUser: useridlist=null, currentuser=0
,D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
,D/elm:14451( 8684): ElmAgentService : onCreate()
,D/elm:14451( 8684): ElmAgentService : onHandleIntent() Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) }
,E/Zygote  ( 8704): MountEmulatedStorage()
E/Zygote  ( 8704): v2
I/libpersona( 8704): KNOX_SDCARD checking this for 10017
I/libpersona( 8704): KNOX_SDCARD not a persona
,D/elm:14451( 8684): MainReceiver.listeningToPackageRemoved()
,D/elm:14451( 8684): MDMBridge.getInstance()
D/elm:14451( 8684): MDMBridge.getAllLicenseInfoFromSDK()
,I/ActivityManager(  888): Start proc com.sec.android.service.health for broadcast com.sec.android.service.health/.upgrade.UninstallReceiver: pid=8704 uid=10017 gids={50017, 9997} abi=armeabi-v7a
,D/RCPManagerService(  888): PackageReceiver onReceive()
,I/HarmonyEASService(  888): onReceive : android.intent.action.PACKAGE_REMOVED for 0
,D/KnoxMUMContainerPolicy(  888): mPackageReceiver : action - android.intent.action.PACKAGE_REMOVED
,W/Resources(  888): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/ResourcesManager(  888): creating new AssetManager and set to /system/app/Books/Books.apk
,D/BackupManagerService(  888): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
,I/SELinux ( 8704): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,D/JobSchedulerService(  888): Receieved: android.intent.action.PACKAGE_REMOVED
,I/SELinux ( 8704): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 8704): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,V/EnterpriseBillingPolicy(  888): packageModificationReceiver - onreceive - start - android.intent.action.PACKAGE_REMOVED
,V/EnterpriseBillingPolicy(  888): uID is 10367
V/EnterpriseBillingPolicy(  888): Removed Packageuid is0
V/EnterpriseBillingPolicyStorage(  888): getProfileForApplication - enter
D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
,D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
V/EnterpriseBillingPolicyStorage(  888): getProfileForApplication - exit null
V/EnterpriseBillingPolicy(  888): packageModificationReceiver - onreceive - personal application - profile null
V/EnterpriseBillingPolicy(  888): packageModificationReceiver - onreceive - might be a vpn vendor package 
,V/EnterpriseBillingPolicyStorage(  888): getBillingProfileForVpnEngine - start - com.test.thalitest
V/EnterpriseBillingPolicyStorage(  888): getBillingProfileForVpnEngine - end - null
,D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
,D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
,D/elm:14451( 8684): MDMBridge.getAllLicenseInfoFromSDK()
,D/TaskPersister(  888): removeObsoleteFile: deleting file=11_task.xml
,D/TaskPersister(  888): removeObsoleteFile: deleting file=11_task_thumbnail.png
,D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
,D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
,D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
,D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
,I/art     (  888): Explicit concurrent mark sweep GC freed 12053(571KB) AllocSpace objects, 0(0B) LOS objects, 30% free, 36MB/52MB, paused 16.131ms total 271.845ms
,D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
,I/Timeline(  888): Timeline: Activity_windows_visible id: ActivityRecord{33f9f27a u0 com.sec.android.app.launcher/com.android.launcher2.Launcher t9} time:338331
,D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
,D/ResourcesManager(  888): creating new AssetManager and set to /system/app/EditorsDocs/EditorsDocs.apk
,D/elm:14451( 8684): ElmAgentService : onDestroy().
,D/TimaKeyStoreProvider( 8704): TimaSignature is unavailable
,D/ActivityThread( 8704): Added TimaKeyStore provider
,D/ResourcesManager(  888): creating new AssetManager and set to /system/app/Music2/Music2.apk
,D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
,D/ResourcesManager(  888): creating new AssetManager and set to /system/app/SecEmail_K/SecEmail_K.apk
,D/ResourcesManager( 8704): creating new AssetManager and set to /system/priv-app/HealthService/HealthService.apk
,W/Resources(  888): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/ResourcesManager(  888): creating new AssetManager and set to /system/app/SecMemoDL/SecMemoDL.apk
,W/Resources(  888): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/ResourcesManager(  888): creating new AssetManager and set to /system/app/Videos/Videos.apk
,D/com.sec.android.service.health.upgrade.UninstallReceiver( 8704): onReceive()
I/com.sec.android.service.health.upgrade.UninstallReceiver( 8704): onReceive called  PACKAGE_REMOVED package:com.test.thalitest
D/com.sec.android.service.health.upgrade.UninstallReceiver( 8704): onReceive() : package name is not s health. Return !!!
,I/PCWCLIENTTRACE_PushUtil( 7858): SPPPushClient is installed : true
I/PCWCLIENTTRACE_PushUtil( 7858): sales region : global
I/PCWCLIENTTRACE_PushUtil( 7858): getPushTypeList : [SPP, GCM]
I/PCWCLIENTTRACE_SYSTEMReceiver( 7858): [onReceive] - android.intent.action.PACKAGE_REMOVED
,E/ActivityManager(  888): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  888): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  888): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  888): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 8720): MountEmulatedStorage()
E/Zygote  ( 8720): v2
I/libpersona( 8720): KNOX_SDCARD checking this for 10034
I/libpersona( 8720): KNOX_SDCARD not a persona
,I/ActivityManager(  888): Start proc com.samsung.android.app.galaxyfinder for broadcast com.samsung.android.app.galaxyfinder/.ApplicationStatusReceiver: pid=8720 uid=10034 gids={50034, 9997, 1028, 1015, 3003, 3002} abi=armeabi-v7a
,D/ResourcesManager(  888): creating new AssetManager and set to /system/app/YouTube/YouTube.apk
,I/art     (  339): Explicit concurrent mark sweep GC freed 8705(370KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 14MB/23MB, paused 273us total 13.845ms
,D/ResourcesManager(  888): creating new AssetManager and set to /system/priv-app/SFinder/SFinder.apk
,W/Resources(  888): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources(  888): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/ResourcesManager(  888): creating new AssetManager and set to /system/app/ChatON_MARKET/ChatON_MARKET.apk
D/PackageManager(  888): delete codoeFile: 
,D/PackageManager(  888): result of delete: 1{220906162}
,W/Resources(  888): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager(  888): creating new AssetManager and set to /system/app/Chrome/Chrome.apk
,I/art     (  339): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 14MB/23MB, paused 543us total 8.239ms
,D/ResourcesManager(  888): creating new AssetManager and set to /system/app/Drive/Drive.apk
,D/ResourcesManager(  888): creating new AssetManager and set to /system/app/Dropbox/Dropbox.apk
,I/art     (  339): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 14MB/23MB, paused 254us total 7.994ms
,I/SELinux ( 8720): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,D/ResourcesManager(  888): creating new AssetManager and set to /system/app/InteractiveTutorial/InteractiveTutorial.apk
,I/SELinux ( 8720): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 8720): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/AndroidRuntime( 8650): Shutting down VM
,W/Resources(  888): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/ResourcesManager(  888): creating new AssetManager and set to /system/app/Newsstand/Newsstand.apk
,D/TimaKeyStoreProvider( 8720): TimaSignature is unavailable
,D/ActivityThread( 8720): Added TimaKeyStore provider
,D/ResourcesManager(  888): creating new AssetManager and set to /system/app/PlayGames/PlayGames.apk
,D/ResourcesManager( 8720): creating new AssetManager and set to /system/priv-app/SFinder/SFinder.apk
,D/ResourcesManager(  888): creating new AssetManager and set to /system/app/SPlanner_OS_UPG/SPlanner_OS_UPG.apk
,W/ResourcesManager(  888): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager(  888): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager(  888): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,W/Resources(  888): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/ResourcesManager(  888): creating new AssetManager and set to /system/app/SmartRemote_KL/SmartRemote_KL.apk
,I/FeatureConfig( 8720): init() refresh[false], Select[false], DisplayOrder[false], HelpMenu[false]
,D/ResourcesManager(  888): creating new AssetManager and set to /data/app/de.pizza-1/base.apk
,D/ResourcesManager(  888): creating new AssetManager and set to /data/app/de.kaufda.android-1/base.apk
,D/ResourcesManager(  888): creating new AssetManager and set to /system/priv-app/Velvet/Velvet.apk
,D/ResourcesManager(  888): creating new AssetManager and set to /system/priv-app/SamsungMusic_20/SamsungMusic_20.apk
,W/Resources(  888): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/ResourcesManager(  888): creating new AssetManager and set to /system/priv-app/SecContacts/SecContacts.apk
,W/Resources(  888): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/ResourcesManager(  888): creating new AssetManager and set to /system/priv-app/SecGallery2014/SecGallery2014.apk
,W/Resources(  888): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources(  888): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,D/ResourcesManager(  888): creating new AssetManager and set to /system/priv-app/SecMyFiles2014/SecMyFiles2014.apk
,W/Resources(  888): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/ResourcesManager(  888): creating new AssetManager and set to /system/priv-app/SecVideoPlayer/SecVideoPlayer.apk
,W/Resources(  888): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources(  888): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
D/ResourcesManager(  888): creating new AssetManager and set to /system/priv-app/VoiceNote/VoiceNote.apk
,W/Resources(  888): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources(  888): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
D/ResourcesManager(  888): creating new AssetManager and set to /system/app/SBrowser/SBrowser.apk
,W/Resources(  888): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/UsbSettingsManager(  888): clearDefaults: com.test.thalitest
,I/CrashAnrDetector(  888): onPackageRemoved : com.test.thalitest
,D/ResourcesManager( 8720): creating new AssetManager and set to /system/priv-app/SecMms_Candy/SecMms_Candy.apk
,W/ResourcesManager( 8720): Asset path '/system/framework/minimode.jar' does not exist or contains no resources.
,W/ResourcesManager( 8720): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 8720): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
,W/ResourcesManager( 8720): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 8720): Asset path '/system/framework/imsmanager.jar' does not exist or contains no resources.
,D/ResourcesManager( 8720): creating new AssetManager and set to /system/priv-app/SecSettings/SecSettings.apk
,W/ResourcesManager( 8720): Asset path '/system/framework/sec_platform_library.jar' does not exist or contains no resources.
,W/ResourcesManager( 8720): Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
W/ResourcesManager( 8720): Asset path '/system/framework/secvisualeffect.jar' does not exist or contains no resources.
W/ResourcesManager( 8720): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
,W/ResourcesManager( 8720): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 8720): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 8720): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,D/ResourcesManager( 8720): creating new AssetManager and set to /system/app/ChatON_MARKET/ChatON_MARKET.apk
,W/ResourcesManager( 8720): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,D/ResourcesManager( 8720): creating new AssetManager and set to /system/app/InteractiveTutorial/InteractiveTutorial.apk
,D/ResourcesManager( 8720): creating new AssetManager and set to /system/app/SPlanner_OS_UPG/SPlanner_OS_UPG.apk
,W/ResourcesManager( 8720): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 8720): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 8720): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,D/ResourcesManager( 8720): creating new AssetManager and set to /system/priv-app/SecContacts/SecContacts.apk
,W/ResourcesManager( 8720): Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
W/ResourcesManager( 8720): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 8720): Asset path '/system/framework/imsmanager.jar' does not exist or contains no resources.
,D/ResourcesManager( 8720): creating new AssetManager and set to /system/priv-app/SecGallery2014/SecGallery2014.apk
,W/ResourcesManager( 8720): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 8720): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 8720): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager( 8720): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,W/ResourcesManager( 8720): Asset path '/system/framework/secimaging.jar' does not exist or contains no resources.
W/ResourcesManager( 8720): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
W/ResourcesManager( 8720): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
W/ResourcesManager( 8720): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,D/ResourcesManager( 8720): creating new AssetManager and set to /system/priv-app/SecMyFiles2014/SecMyFiles2014.apk
,W/ResourcesManager( 8720): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 8720): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
,D/ResourcesManager( 8720): creating new AssetManager and set to /system/priv-app/SecVideoPlayer/SecVideoPlayer.apk
,W/ResourcesManager( 8720): Asset path '/system/framework/minimode.jar' does not exist or contains no resources.
W/ResourcesManager( 8720): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 8720): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager( 8720): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 8720): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
,D/ResourcesManager( 8720): creating new AssetManager and set to /system/app/SBrowser/SBrowser.apk
,W/ResourcesManager( 8720): Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
W/ResourcesManager( 8720): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 8720): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,D/ResourcesManager( 8720): creating new AssetManager and set to /system/app/SecEmail_K/SecEmail_K.apk
,W/ResourcesManager( 8720): Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
W/ResourcesManager( 8720): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 8720): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager( 8720): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,D/ResourcesManager( 8720): creating new AssetManager and set to /system/app/SecMemoDL/SecMemoDL.apk
,W/ResourcesManager( 8720): Asset path '/system/framework/secmediarecorder.jar' does not exist or contains no resources.
W/ResourcesManager( 8720): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
,D/ResourcesManager( 8720): creating new AssetManager and set to /system/app/Chrome/Chrome.apk
,D/ResourcesManager( 8720): creating new AssetManager and set to /system/priv-app/SamsungMusic_20/SamsungMusic_20.apk
,W/ResourcesManager( 8720): Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
W/ResourcesManager( 8720): Asset path '/system/framework/secvisualeffect.jar' does not exist or contains no resources.
W/ResourcesManager( 8720): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 8720): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager( 8720): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 8720): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
,D/ResourcesManager( 8720): creating new AssetManager and set to /system/priv-app/VoiceNote/VoiceNote.apk
,W/ResourcesManager( 8720): Asset path '/system/framework/secmediarecorder.jar' does not exist or contains no resources.
W/ResourcesManager( 8720): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,E/ActivityManager(  888): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  888): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  888): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  888): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 8737): MountEmulatedStorage()
,E/Zygote  ( 8737): v2
I/libpersona( 8737): KNOX_SDCARD checking this for 10035
I/libpersona( 8737): KNOX_SDCARD not a persona
,I/ActivityManager(  888): Start proc com.sec.android.app.shealth for broadcast com.sec.android.app.shealth/.receiver.InstalledReceiver: pid=8737 uid=10035 gids={50035, 9997, 3003, 1028, 1015, 3001, 3002} abi=armeabi-v7a
,I/ActivityManager(  888): Killing 7203:com.android.calendar/u0a150 (adj 15): bgCount ##41
,D/SSRM:m  (  888): SIOP:: AP = 290, PST = 290, CUR = 300
,I/SELinux ( 8737): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 8737): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 8737): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 8737): TimaSignature is unavailable
,D/ActivityThread( 8737): Added TimaKeyStore provider
,D/ResourcesManager( 8737): creating new AssetManager and set to /system/priv-app/SHealth3_5/SHealth3_5.apk
,I/ServiceManager(  360): Waiting for service AtCmdFwd...
,W/libprocessgroup(  888): failed to open /acct/uid_10150/pid_7203/cgroup.procs: No such file or directory
,D/SHealthUpgrade(SHealthUpgradeUtil)( 8737): isShealthServiceInstalled() : HealthService is Installed.
,D/SHealthUpgrade(SHealthUpgradeUtil)( 8737): isShealthService2xInstalled() : HEALTH SERVICE is INSTALLED.
D/SHealthUpgrade(SHealthUpgradeUtil)( 8737): isShealthService2xInstalled() : HEALTH SERVICE VERSION = 2.x
,D/SHealthUpgrade(SHealthUpgradeUtil)( 8737): checkState()
D/SHealthUpgrade(SHealthUpgradeUtil)( 8737): checkState() : APP TYPE = Full
,D/SHealthUpgrade(SHealthUpgradeUtil)( 8737): isFitnessWithGearInstalled() : Fitness with Gear isn't Installed.
,D/SHealthUpgrade(SHealthUpgradeUtil)( 8737): isShealthServiceInstalled() : HealthService is Installed.
,D/SHealthUpgrade(SHealthUpgradeUtil)( 8737): isShealthService1xInstalled() : HEALTH SERVICE is INSTALLED.
D/SHealthUpgrade(SHealthUpgradeUtil)( 8737): isShealthService1xInstalled() : HEALTH SERVICE VERSION is NOT 1.x !!!
D/SHealthUpgrade(SHealthUpgradeUtil)( 8737): isShealthService0xInstalled() : HEALTH SERVICE is INSTALLED.
D/SHealthUpgrade(SHealthUpgradeUtil)( 8737): isShealthService0xInstalled() : HEALTH SERVICE VERSION is NOT 0.x !!!
D/SHealthUpgrade(SHealthUpgradeUtil)( 8737): isShealthService2xInstalled() : HEALTH SERVICE is INSTALLED.
D/SHealthUpgrade(SHealthUpgradeUtil)( 8737): isShealthService2xInstalled() : HEALTH SERVICE VERSION = 2.x
,D/SHealthUpgrade(SHealthUpgradeUtil)( 8737): checkState() : =========== UPGRADE_STATE_APP_UPGRADE_DONE ===========
,D/SHealthUpgrade(SHealthUpgradeUtil)( 8737): isShealthServiceInstalled() : HealthService is Installed.
D/SHealthUpgrade(SHealthUpgradeUtil)( 8737): isShealthService2xInstalled() : HEALTH SERVICE is INSTALLED.
D/SHealthUpgrade(SHealthUpgradeUtil)( 8737): isShealthService2xInstalled() : HEALTH SERVICE VERSION = 2.x
,D/SHealthUpgrade(SHealthUpgradeUtil)( 8737): isShealthServiceInstalled() : HealthService is Installed.
D/SHealthUpgrade(SHealthUpgradeUtil)( 8737): isShealthService2xInstalled() : HEALTH SERVICE is INSTALLED.
D/SHealthUpgrade(SHealthUpgradeUtil)( 8737): isShealthService2xInstalled() : HEALTH SERVICE VERSION = 2.x
,D/SHealthUpgrade(SHealthUpgradeUtil)( 8737): isShealthService2xInstalled() : HEALTH SERVICE is INSTALLED.
,D/SHealthUpgrade(SHealthUpgradeUtil)( 8737): isShealthService2xInstalled() : HEALTH SERVICE VERSION = 2.x
,F/libc    ( 8737): Fatal signal 7 (SIGBUS), code 2, fault addr 0x757a312b in tid 8762 (SharedPreferenc)
,E/audit_log( 2180): File locking failed. error= Bad file number
E/audit_log( 2180): File locking failed. error= Bad file number
,V/GLSActivity( 1714): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/EventHub(  888): Removing device '/dev/input/event4' due to inotify event
,I/GLSUser ( 1714): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
,I/GLSUser ( 1714): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1714): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1714): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/ActivityManager(  888): Process com.sec.android.app.shealth (pid 8737)(adj 0) has died(206,505)
,V/GLSActivity( 1714): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,F/libc    ( 7969): Fatal signal 7 (SIGBUS), code 2, fault addr 0x781e51f0 in tid 7969 (om.sec.spp.push)
,F/libc    ( 7969): Unable to open connection to debuggerd: Connection refused
E/audit_log( 2180): File locking failed. error= Bad file number
,V/BitmapFactory( 1714): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  888): uri = 14 selection = getSealedState
D/SecContentProvider2(  888): mCursor = null
,D/SecContentProvider2(  888): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  888): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
V/ApplicationPolicy(  888): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/StatusBar( 1171): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,I/EventHub(  888): Removing device '/dev/input/event5' due to inotify event
,I/PhoneStatusBar( 1171): Icon Only
,D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
D/PanelView( 1171): There is/are notification(s) 
,D/PanelView( 1171): There is/are notification(s) 
,W/FileUtils( 1714): Failed to chmod(/data/data/com.google.android.gms/files): android.system.ErrnoException: chmod failed: EROFS (Read-only file system)
,F/libc    ( 1714): Fatal signal 7 (SIGBUS), code 2, fault addr 0x9d54a74a in tid 6581 (Binder_B)
,F/libc    ( 1714): Unable to open connection to debuggerd: Connection refused
,E/audit_log( 2180): File locking failed. error= Bad file number
,I/Zygote  (  339): Process 8737 exited due to signal (7)
,I/ActivityManager(  888): Process com.sec.spp.push (pid 7969)(adj 0) has died(217,506)
,E/ActivityManager(  888): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  888): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  888): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  888): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 8767): MountEmulatedStorage()
I/libpersona( 8767): KNOX_SDCARD checking this for 10038
E/Zygote  ( 8767): v2
I/libpersona( 8767): KNOX_SDCARD not a persona
,I/ActivityManager(  888): Start proc com.sec.spp.push:RemoteNotiProcess for broadcast com.sec.spp.push/.notisvc.registration.PackageRemovedReceiver: pid=8767 uid=10038 gids={50038, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  888): Process com.google.process.gapps (pid 1714)(adj 1) has died(229,506)
,E/BooksAccountManager( 7687): Authentication error
E/BooksAccountManager( 7687): android.accounts.AuthenticatorException: disconnected
E/BooksAccountManager( 7687): android.accounts.AccountManager.convertErrorToException(AccountManager.java:1893)
,E/HttpHelper( 7687): null auth token
F/libc    (  888): Fatal signal 7 (SIGBUS), code 2, fault addr 0xa03c94bc in tid 1364 (Binder_7)
F/libc    (  888): Unable to open connection to debuggerd: Connection refused
,E/audit_log( 2180): File locking failed. error= Bad file number
,I/qtaguid ( 7687): Tagging socket 34 with tag 10000000000{256,0} uid -1, pid: 7687, getuid(): 10082
,I/Zygote  (  339): Process 7969 exited due to signal (7)
,I/Zygote  (  339): Process 1714 exited due to signal (7)
,I/qtaguid ( 7687): Untagging socket 34
,W/ApiaryClient( 7687): Error response from books API: {
W/ApiaryClient( 7687):  "error": {
W/ApiaryClient( 7687):   "errors": [
W/ApiaryClient( 7687):    {
W/ApiaryClient( 7687):     "domain": "global",
W/ApiaryClient( 7687):     "reason": "required",
W/ApiaryClient( 7687):     "message": "Login Required",
W/ApiaryClient( 7687):     "locationType": "header",
W/ApiaryClient( 7687):     "location": "Authorization"
W/ApiaryClient( 7687):    }
W/ApiaryClient( 7687):   ],
W/ApiaryClient( 7687):   "code": 401,
W/ApiaryClient( 7687):   "message": "Login Required"
W/ApiaryClient( 7687):  }
W/ApiaryClient( 7687): }
W/ApiaryClient( 7687): errCount = 2: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 7687): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3DS0HXd4TFLU4&nonce=1610344782266698187&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 7687): Headers suppressed
,I/SELinux ( 8767): Function: selinux_compare_spd_ram , priority [2] , priority version is VE=SEPF_SM-G900F_5.0_0011
,E/SELinux ( 8767): [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
,I/ServiceManager(  247): service 'sec_analytics' died
,I/ServiceManager(  247): service 'enterprise_policy' died
I/ServiceManager(  247): service 'statusbar' died
I/ServiceManager(  247): service 'clipboard' died
I/ServiceManager(  247): service 'clipboardEx' died
W/AudioFlinger(  303): power manager service died !!!
W/AudioFlinger(  303): power manager service died !!!
I/SurfaceFlinger(  249): restart the boot-animation @ binderDied
W/Sensors ( 1304): sensorservice died [0x9d8212c0]
,I/ServiceManager(  247): service 'network_management' died
I/ServiceManager(  247): service 'ABTPersistenceService' died
I/ServiceManager(  247): service 'textservices' died
I/ServiceManager(  247): service 'network_score' died
I/ServiceManager(  247): service 'netstats' died
I/ServiceManager(  247): service 'netpolicy' died
I/ServiceManager(  247): service 'wifi' died
W/Sensors ( 2250): sensorservice died [0xaf0c3ec0]
I/ServiceManager(  247): service 'msapwifi' died
,I/ServiceManager(  247): service 'wifiscanner' died
I/ServiceManager(  247): service 'rttmanager' died
I/ServiceManager(  247): service 'wifip2p' died
,I/ServiceManager(  247): service 'connectivity' died
I/ServiceManager(  247): service 'sb_service' died
I/ServiceManager(  247): service 'clinfo' died
I/ServiceManager(  247): service 'servicediscovery' died
I/ServiceManager(  247): service 'updatelock' died
I/ServiceManager(  247): service 'notification' died
I/ServiceManager(  247): service 'devicestoragemonitor' died
I/ServiceManager(  247): service 'location' died
I/ServiceManager(  247): service 'country_detector' died
I/ServiceManager(  247): service 'sec_location' died
I/ServiceManager(  247): service 'search' died
I/ServiceManager(  247): service 'dropbox' died
I/ServiceManager(  247): service 'wallpaper' died
I/ServiceManager(  247): service 'audio' died
I/ServiceManager(  247): service 'DockObserver' died
I/ServiceManager(  247): service 'usb' died
I/ServiceManager(  247): service 'serial' died
I/ServiceManager(  247): service 'uimode' died
I/ServiceManager(  247): service 'jobscheduler' died
I/ServiceManager(  247): service 'print' died
I/ServiceManager(  247): service 'restrictions' died
I/ServiceManager(  247): service 'media_session' died
I/ServiceManager(  247): service 'media_router' died
I/ServiceManager(  247): service 'trust' died
I/ServiceManager(  247): service 'fingerprint' died
I/ServiceManager(  247): service 'launcherapps' died
I/ServiceManager(  247): service 'voip' died
I/ServiceManager(  247): service 'media_projection' died
I/ServiceManager(  247): service 'imms' died
I/ServiceManager(  247): service 'backup' died
W/Sensors ( 1171): sensorservice died [0xaf0d20c0]
I/ServiceManager(  247): service 'appwidget' died
I/ServiceManager(  247): service 'voiceinteraction' died
I/ServiceManager(  247): service 'SecExternalDisplayService' died
I/ServiceManager(  247): service 'diskstats' died
I/ServiceManager(  247): service 'spengestureservice' died
I/ServiceManager(  247): service 'quickconnect' died
I/ServiceManager(  247): service 'samplingprofiler' died
I/ServiceManager(  247): service 'commontime_management' died
I/ServiceManager(  247): service 'dreams' died
I/ServiceManager(  247): service 'context_aware' died
I/ServiceManager(  247): service 'scontext' died
I/ServiceManager(  247): service 'barbeam' died
I/ServiceManager(  247): service 'multiwindow_facade' died
I/ServiceManager(  247): service 'window' died
I/ServiceManager(  247): service 'input' died
I/ServiceManager(  247): service 'tactileassist' died
I/ServiceManager(  247): service 'bluetooth_manager' died
I/ServiceManager(  247): service 'bluetooth_secure_mode_manager' died
I/ServiceManager(  247): service 'rcp' died
I/ServiceManager(  247): service 'input_method' died
I/ServiceManager(  247): service 'accessibility' died
I/ServiceManager(  247): service 'motion_recognition' died
I/ServiceManager(  247): service 'cover' died
I/ServiceManager(  247): service 'application_policy' died
,I/ServiceManager(  247): service 'wifi_policy' died
I/ServiceManager(  247): service 'phone_restriction_policy' died
I/ServiceManager(  247): service 'remoteinjection' died
I/ServiceManager(  247): service 'mum_container_policy' died
I/ServiceManager(  247): service 'enterprise_billing_policy' died
I/ServiceManager(  247): service 'knox_timakeystore_policy' died
I/ServiceManager(  247): service 'mount' died
I/ServiceManager(  247): service 'lock_settings' died
I/ServiceManager(  247): service 'device_policy' died
I/ServiceManager(  247): service 'harmony_eas_service' died
I/ServiceManager(  247): service 'sdp' died
I/ServiceManager(  247): service 'log_manager_service' died
I/ServiceManager(  247): service 'hardware' died
I/ServiceManager(  247): service 'telephony.registry' died
I/ServiceManager(  247): service 'batterystats' died
I/ServiceManager(  247): service 'appops' died
I/ServiceManager(  247): service 'power' died
I/ServiceManager(  247): service 'display' died
I/ServiceManager(  247): service 'persona_policy' died
I/ServiceManager(  247): service 'SEAMService' died
I/ServiceManager(  247): service 'persona' died
I/ServiceManager(  247): service 'account' died
I/ServiceManager(  247): service 'content' died
I/ServiceManager(  247): service 'DirEncryptService' died
I/ServiceManager(  247): service 'ReactiveService' died
I/ServiceManager(  247): service 'sedenial' died
I/ServiceManager(  247): service 'vibrator' died
I/ServiceManager(  247): service 'tw_toolbox' died
I/ServiceManager(  247): service 'tima' died
I/ServiceManager(  247): service 'cepproxyks' died
I/ServiceManager(  247): service 'enterprise_license_policy' died
I/ServiceManager(  247): service 'CustomFrequencyManagerService' died
I/ServiceManager(  247): service 'samsung.smartfaceservice' died
I/ServiceManager(  247): service 'consumer_ir' died
I/ServiceManager(  247): service 'alarm' died
I/ServiceManager(  247): service 'gfxinfo' died
I/ServiceManager(  247): service 'user' died
I/ServiceManager(  247): service 'battery' died
I/ServiceManager(  247): service 'scheduling_policy' died
I/ServiceManager(  247): service 'activity' died
I/ServiceManager(  247): service 'permission' died
I/ServiceManager(  247): service 'usagestats' died
I/ServiceManager(  247): service 'webviewupdate' died
I/ServiceManager(  247): service 'entropy' died
I/ServiceManager(  247): service 'package' died
I/ServiceManager(  247): service 'edmnativehelper' died
I/ServiceManager(  247): service 'procstats' died
I/ServiceManager(  247): service 'cpuinfo' died
I/ServiceManager(  247): service 'dbinfo' died
I/ServiceManager(  247): service 'meminfo' died
I/ServiceManager(  247): service 'sensorservice' died
I/ServiceManager(  247): service 'mdm.remotedesktop' died
W/Sensors ( 1447): sensorservice died [0xaf0c0bc0]
W/Sensors ( 7542): sensorservice died [0xaf0fa600]
I/SurfaceFlinger(  249): id=2 Removed FocusedStackFrame (4/8)
I/SurfaceFlinger(  249): id=3 Removed DimLayer (0/7)
I/SurfaceFlinger(  249): id=4 Removed DimLayer (0/6)
I/SurfaceFlinger(  249): id=5 Removed DimLayer (0/5)
I/SurfaceFlinger(  249): id=6 Removed DimLayer (2/4)
I/SurfaceFlinger(  249): id=2 Removed FocusedStackFrame (-2/4)
I/SurfaceFlinger(  249): id=3 Removed DimLayer (-2/4)
I/SurfaceFlinger(  249): id=4 Removed DimLayer (-2/4)
I/SurfaceFlinger(  249): id=5 Removed DimLayer (-2/4)
I/SurfaceFlinger(  249): id=6 Removed DimLayer (-2/4)
W/Sensors ( 2282): sensorservice died [0xaf0c0c00]
I/SurfaceFlinger(  249): id=7 Removed com.android.systemui.ImageWallpaper (0/3)
I/SurfaceFlinger(  249): id=7 Removed com.android.systemui.ImageWallpaper (-2/3)
I/SurfaceFlinger(  249): id=18 Removed com.sec.android.app.launcher/com.android.launcher2.Launcher (0/2)
I/SurfaceFlinger(  249): id=9 Removed StatusBar (0/1)
I/SurfaceFlinger(  249): id=18 Removed com.sec.android.app.launcher/com.android.launcher2.Launcher (-2/1)
I/SurfaceFlinger(  249): id=9 Removed StatusBar (-2/1)
I/SurfaceFlinger(  249): id=17 Removed ColorFade (0/0)
I/SurfaceFlinger(  249): id=17 Removed ColorFade (-2/0)
E/audit_log( 2180): File locking failed. error= Bad file number
W/Sensors ( 1459): sensorservice died [0xaf064380]
E/WifiManager( 1304): Channel connection lost
D/SurfaceFlinger(  249): Set power mode=2, type=0 flinger=0xb6a62000
D/qdhwcomposer(  249): hwc_blank: Unblanking display: 0
E/WifiManager( 2250): Channel connection lost
E/WifiManager( 5621): Channel connection lost
E/WifiManager( 1171): Channel connection lost
E/WifiManager( 1569): Channel connection lost
F/libc    ( 2250): Fatal signal 7 (SIGBUS), code 2, fault addr 0x758b6dd5 in tid 2250 (.gms.persistent)
F/libc    ( 2250): Unable to open connection to debuggerd: Connection refused
E/WifiManager( 1459): Channel connection lost
W/Sensors ( 1465): sensorservice died [0xaf0c33c0]
D/TimaKeyStoreProvider( 8767): TimaSignature is unavailable
D/ActivityThread( 8767): Added TimaKeyStore provider
F/libc    ( 2467): Fatal signal 7 (SIGBUS), code 2, fault addr 0x758b6dd5 in tid 2467 (gle.android.gms)
F/libc    ( 2467): Unable to open connection to debuggerd: Connection refused
E/audit_log( 2180): File locking failed. error= Bad file number
D/AndroidRuntime( 8767): Shutting down VM
E/AndroidRuntime( 8767): FATAL EXCEPTION: main
E/AndroidRuntime( 8767): PID: 8767
E/AndroidRuntime( 8767): java.lang.NullPointerException: Attempt to invoke interface method 'void android.app.IActivityManager.attachApplication(android.app.IApplicationThread)' on a null object reference
E/AndroidRuntime( 8767): 	at android.app.ActivityThread.attach(ActivityThread.java:5545)
E/AndroidRuntime( 8767): 	at android.app.ActivityThread.main(ActivityThread.java:5814)
E/AndroidRuntime( 8767): 	at java.lang.reflect.Method.invoke(Native Method)
E/AndroidRuntime( 8767): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/AndroidRuntime( 8767): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
E/AndroidRuntime( 8767): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
F/libc    ( 8767): Fatal signal 7 (SIGBUS), code 2, fault addr 0x7400ed65 in tid 8767 (re-initialized>)
F/libc    ( 8767): Unable to open connection to debuggerd: Connection refused
E/audit_log( 2180): File locking failed. error= Bad file number
E/BooksSync( 7687): Soft error
E/BooksSync( 7687): com.google.android.apps.books.net.HttpHelper$OfflineIoException: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: Device offline, skipping https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3DS0HXd4TFLU4&nonce=1610344782266698187&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
E/BooksSync( 7687): com.google.android.apps.books.net.HttpHelper.shouldSkipRetry(HttpHelper.java:88)
E/BooksSync( 7687): Sync error
E/BooksSync( 7687): com.google.android.apps.books.net.HttpHelper$OfflineIoException: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: Device offline, skipping https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3DS0HXd4TFLU4&nonce=1610344782266698187&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
E/BooksSync( 7687): com.google.android.apps.books.net.HttpHelper.shouldSkipRetry(HttpHelper.java:88)
I/BooksSync( 7687): Finished books sync
F/libc    ( 7687): Fatal signal 7 (SIGBUS), code 2, fault addr 0x73951c5a in tid 8657 (SyncAdapterThre)
F/libc    ( 7687): Unable to open connection to debuggerd: Connection refused
E/audit_log( 2180): File locking failed. error= Bad file number
,F/libc    ( 6627): Fatal signal 7 (SIGBUS), code 2, fault addr 0x758b6dd5 in tid 6627 (android.vending)
F/libc    ( 6627): Unable to open connection to debuggerd: Connection refused
E/audit_log( 2180): File locking failed. error= Bad file number
I/Zygote  (  339): Process 2250 exited due to signal (7)
I/Zygote  (  339): Process 8767 exited due to signal (7)
,I/Zygote  (  339): Process 6627 exited due to signal (7)
,I/Zygote  (  339): Process 2467 exited due to signal (7)
,I/Zygote  (  339): Process 7687 exited due to signal (7)
,E/installd(  306): eof
E/installd(  306): failed to read size
I/installd(  306): closing connection
,I/qdhwcomposer(  249): handle_blank_event: dpy:0 panel power state: 0
,E/qdexternal(  249): writeHPDOption: file write failed '/sys/devices/virtual/graphics/fb1/hpd'
D/qdhwcomposer(  249): hwc_blank: Done unblanking display: 0
,E/qdhwcomposer(  249): hwc_vsync_control: vsync control failed. Dpy=0, enable=1 : Operation not permitted
E/SurfaceFlinger(  249): eventControl(0, 1) failed Operation not permitted
,I/qdhwcomposer(  249): handle_blank_event: dpy:0 panel power state: 0

```
