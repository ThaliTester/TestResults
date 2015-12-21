#### Test 506502781c2754f_thali07_samsung-SM-G900F Logs


```
--------- beginning of main
,E/LightSensor(  918): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
--------- beginning of system
D/AutomaticBrightnessController(  918): mCallbacks.updateBrightness()
D/DisplayPowerController(  918): getFinalBrightness : 8 -> 8
E/LightSensor(  918): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
D/AutomaticBrightnessController(  918): mCallbacks.updateBrightness()
D/DisplayPowerController(  918): getFinalBrightness : 8 -> 8
E/SMD     (  280): DCD ON
E/LightSensor(  918): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
D/AutomaticBrightnessController(  918): mCallbacks.updateBrightness()
D/DisplayPowerController(  918): getFinalBrightness : 8 -> 8
D/AndroidRuntime( 7394): 
D/AndroidRuntime( 7394): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
V/GLSActivity( 1739): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/AndroidRuntime( 7394): CheckJNI is OFF
D/AndroidRuntime( 7394): setted country_code = Germany
D/AndroidRuntime( 7394): setted countryiso_code = DE
D/AndroidRuntime( 7394): setted sales_code = DBT
D/AndroidRuntime( 7394): readGMSProperty: start
D/AndroidRuntime( 7394): readGMSProperty: already setted!!
D/AndroidRuntime( 7394): readGMSProperty: end
D/AndroidRuntime( 7394): addProductProperty: start
I/GLSUser ( 1739): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
I/GLSUser ( 1739): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1739): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1739): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 1739): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
E/LightSensor(  918): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
D/AutomaticBrightnessController(  918): mCallbacks.updateBrightness()
D/DisplayPowerController(  918): getFinalBrightness : 8 -> 8
I/art     ( 1739): Explicit concurrent mark sweep GC freed 30578(1859KB) AllocSpace objects, 12(972KB) LOS objects, 39% free, 17MB/29MB, paused 809us total 35.488ms
D/ResourcesManager( 1739): creating new AssetManager and set to /system/app/Books/Books.apk
V/BitmapFactory( 1739): DecodeImagePath(decodeResourceStream3) : res/mipmap-xxhdpi-v4/ic_launcher_play_books.png
V/BitmapFactory( 1739): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
D/SecContentProvider2(  918): uri = 14 selection = getSealedState
D/SecContentProvider2(  918): mCursor = null
D/SecContentProvider2(  918): KnoxCustomManagerService offline: service is not available
D/ApplicationPolicy(  918): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
V/ApplicationPolicy(  918): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
D/StatusBar( 1173): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
I/PhoneStatusBar( 1173): Icon Only
D/LockPatternUtilsCache( 1173): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1173): value : false
D/PanelView( 1173): There is/are notification(s) 
D/PanelView( 1173): There is/are notification(s) 
W/GLSActivity( 1739): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1739): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1739): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1739): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1739): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1739): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1739): 	at android.os.Binder.execTransact(Binder.java:446)
E/BooksAccountManager( 7348): Authentication error
E/BooksAccountManager( 7348): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 7348): android.accounts.AccountManager.convertErrorToException(AccountManager.java:1893)
E/HttpHelper( 7348): null auth token
I/qtaguid ( 7348): Tagging socket 34 with tag 10000000000{256,0} uid -1, pid: 7348, getuid(): 10082
D/StatusBar.NetworkController( 1173): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02012b/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020464/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
D/StatusBar.NetworkController( 1173): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1173): applyOpen
D/StatusBar.NetworkController( 1173): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1173): applyOpen
D/StatusBar.NetworkController( 1173): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1173): applyOpen
D/StatusBar.NetworkController( 1173): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1173): applyOpen
E/AffinityControl( 7394): AffinityControl: registerfunction enter
I/WifiStateMachine(  918): CMD_RSSI_POLL : calculateWifiScore in!
I/WifiStateMachine(  918): CMD_RSSI_POLL : calculateWifiScore out!
I/WifiStateMachine(  918): CMD_RSSI_POLL : out!
D/AndroidRuntime( 7394): Calling main entry com.android.commands.am.Am
I/qtaguid ( 7348): Untagging socket 34
W/ApiaryClient( 7348): Error response from books API: {
W/ApiaryClient( 7348):  "error": {
W/ApiaryClient( 7348):   "errors": [
W/ApiaryClient( 7348):    {
W/ApiaryClient( 7348):     "domain": "global",
W/ApiaryClient( 7348):     "reason": "required",
W/ApiaryClient( 7348):     "message": "Login Required",
W/ApiaryClient( 7348):     "locationType": "header",
W/ApiaryClient( 7348):     "location": "Authorization"
W/ApiaryClient( 7348):    }
W/ApiaryClient( 7348):   ],
W/ApiaryClient( 7348):   "code": 401,
W/ApiaryClient( 7348):   "message": "Login Required"
W/ApiaryClient( 7348):  }
W/ApiaryClient( 7348): }
W/ApiaryClient( 7348): errCount = 3: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 7348): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3DS0HXd4TFLU4&nonce=-5073401260082810871&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 7348): Headers suppressed
D/ConnectivityService(  918): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
E/PersonaManagerService(  918): inState():  stateMachine is null !!
V/ApplicationPolicy(  918): isApplicationStateBlocked userId 0 pkgname com.test.thalitest
I/ActivityManager(  918): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
D/ResourcesManager(  918): creating new AssetManager and set to /data/app/com.test.thalitest-1/base.apk
E/LightSensor(  918): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
D/AutomaticBrightnessController(  918): mCallbacks.updateBrightness()
D/DisplayPowerController(  918): getFinalBrightness : 8 -> 8
D/CustomFrequencyManagerService(  918): acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1958400  uid : 1000  pid : 918  pkgName : ACTIVITY_RESUME_BOOSTER@6
W/ActivityManager(  918): mDVFSHelper.acquire()
D/FocusedStackFrame(  918): Set to : 0
D/Launcher.HomeView( 1490): onPause
D/Launcher( 1490): Launcher::setSystemUiTransparency(): getSystemUiVisibility() after setting  = 40000000
D/LockPatternUtilsCache( 1173): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1173): value : false
D/AndroidRuntime( 7394): Shutting down VM
D/LockPatternUtilsCache( 1173): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1173): value : false
V/TaskCloserActivity( 7183): TaskCloserActivity onReceive() - com.sec.android.intent.action.HOME_PAUSE
D/LockPatternUtilsCache( 1173): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1173): value : false
E/ActivityManager(  918): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  918): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  918): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  918): checkUser: useridlist=null, currentuser=0
I/SurfaceFlinger(  249): id=14 createSurf (1x1),1 flag=404, Starting com.test.thalitest
D/LockPatternUtilsCache( 1173): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1173): value : false
D/LockPatternUtilsCache( 1173): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1173): value : false
E/Zygote  ( 7416): MountEmulatedStorage()
E/Zygote  ( 7416): v2
I/libpersona( 7416): KNOX_SDCARD checking this for 10367
I/libpersona( 7416): KNOX_SDCARD not a persona
I/ActivityManager(  918): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=7416 uid=10367 gids={50367, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
I/SELinux ( 7416): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
I/SELinux ( 7416): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
E/SELinux ( 7416): [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
D/LockPatternUtilsCache( 1173): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1173): value : false
D/LockPatternUtilsCache( 1173): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1173): value : false
D/LockPatternUtilsCache( 1173): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1173): value : false
D/LockPatternUtilsCache( 1173): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1173): value : false
D/StatusBarManagerService(  918): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
D/LockPatternUtilsCache( 1173): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1173): value : false
D/LockPatternUtilsCache( 1173): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1173): value : false
D/LockPatternUtilsCache( 1173): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1173): value : false
I/MicrophoneInputStream( 1587): mic_close gfk@37231c37
D/TimaKeyStoreProvider( 7416): TimaSignature is unavailable
D/ActivityThread( 7416): Added TimaKeyStore provider
V/AudioPolicyManager(  288): stopInput() input 29
V/AudioPolicyManager(  288): releaseInput() 29
V/AudioPolicyManager(  288): closeInput(29)
I/HotwordRecognitionRnr( 1587): Hotword detection finished
I/HotwordRecognitionRnr( 1587): Stopping hotword detection.
V/audio_hw_primary(  288): in_standby: enter
D/LockPatternUtilsCache( 1173): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1173): value : false
D/LockPatternUtilsCache( 1173): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1173): value : false
V/WindowOrientationListener(  918): mSContextAutoRotationListener.getProposedRotation, mbResultFaceDectection: false
V/WindowOrientationListener(  918): mSContextAutoRotationListener.getProposedRotation, Rotation: -1
V/WindowManager(  918): rotationForOrientationLw(orient=-1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false
V/WindowOrientationListener(  918): mSContextAutoRotationListener.getProposedRotation, mbResultFaceDectection: false
V/WindowOrientationListener(  918): mSContextAutoRotationListener.getProposedRotation, Rotation: -1
V/ActivityManager(  918): Display changed displayId=0
D/Launcher.HomeView( 1490): onStop
D/SurfaceWidgetClient$ISurfaceWidgetStub( 1970): [237392/6] Surface widget pause on instance = 1
D/accuweather( 1970): [KK AccuPhone]>>> SWW:239 [0:0] [SWW] onPause : instance = 1
D/accuweather( 1970): [KK AccuPhone]>>> SWW:254 [0:0] onPause : size = 0
D/accuweather( 1970): [KK AccuPhone]>>> SWW:545 [0:0]  unRegisterTTReceiver !! 
D/SurfaceWidgetClient$ISurfaceWidgetStub( 1970): [237392/6] Surface widget visibility changed visibility = false on instance = 1
D/SurfaceWidgetView( 1490): destroyHardwareResources():485063349
D/LockPatternUtilsCache( 1173): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1173): value : false
D/LockPatternUtilsCache( 1173): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1173): value : false
V/audio_hw_primary(  288): stop_input_stream: enter: usecase(7: audio-record)
V/audio_hw_primary(  288): disable_audio_route: enter: usecase(7)
V/audio_hw_primary(  288): disable_audio_route: reset mixer path: audio-record
D/audio_route(  288): ++++ audio_route_update_mixer ==============
D/LockPatternUtilsCache( 1173): getCarrierLockPlusMode()
D/audio_route(  288): Setting mixer control: MultiMedia1 Mixer SLIM_0_TX
D/audio_route(  288): Setting mixer control: value: 0
D/LockPatternUtilsCache( 1173): value : false
D/LockPatternUtilsCache( 1173): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1173): value : false
D/audio_route(  288): ------ audio_route_update_mixer ==============
V/audio_hw_primary(  288): disable_audio_route: exit
V/audio_hw_primary(  288): disable_snd_device: snd_device(122: vr-main-mic)
D/audio_route(  288): ++++ audio_route_update_mixer ==============
D/audio_route(  288): Setting mixer control: DEC2 Volume
D/audio_route(  288): Setting mixer control: value: 0
D/audio_route(  288): Setting mixer control: SLIM TX7 MUX, value: 0
D/StatusBarManagerService(  918): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
D/audio_route(  288): Setting mixer control: AIF1_CAP Mixer SLIM TX7
D/audio_route(  288): Setting mixer control: value: 0
D/audio_route(  288): Setting mixer control: DEC2 MUX, value: 0
D/LockPatternUtilsCache( 1173): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1173): value : false
D/LockPatternUtilsCache( 1173): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1173): value : false
D/audio_route(  288): ------ audio_route_update_mixer ==============
V/audio_hw_primary(  288): stop_input_stream: exit: status(0)
V/audio_hw_primary(  288): in_standby: exit:  status(0)
V/audio_hw_primary(  288): adev_close_input_stream
V/audio_hw_primary(  288): in_standby: enter
V/audio_hw_primary(  288): in_standby: exit:  status(0)
E/audio_hw_primary(  288): adev_close_input_stream, set jack_in to null
V/AudioPolicyManager(  288): releaseInput() exit
D/LockPatternUtilsCache( 1173): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1173): value : false
D/LockPatternUtilsCache( 1173): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1173): value : false
D/LockPatternUtilsCache( 1173): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1173): value : false
D/accuweather( 1970): [KK AccuPhone]>>> WR:132 [0:0] onPause
D/accuweather( 1970): [KK AccuPhone]>>> SM:538 [0:0] onPause
D/ConnectivityService(  918): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/Launcher( 1490): onTrimMemory. Level: 20
D/ResourcesManager( 7416): creating new AssetManager and set to /data/app/com.test.thalitest-1/base.apk
D/LockPatternUtilsCache( 1173): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1173): value : false
D/SurfaceWidgetView( 1490): destroyHardwareResources():485063349
D/LockPatternUtilsCache( 1173): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1173): value : false
D/LockPatternUtilsCache( 1173): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1173): value : false
D/LockPatternUtilsCache( 1173): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1173): value : false
D/LockPatternUtilsCache( 1173): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1173): value : false
D/LockPatternUtilsCache( 1173): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1173): value : false
D/LockPatternUtilsCache( 1173): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1173): value : false
D/LockPatternUtilsCache( 1173): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1173): value : false
D/LockPatternUtilsCache( 1173): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1173): value : false
D/LockPatternUtilsCache( 1173): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1173): value : false
E/LightSensor(  918): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
D/AutomaticBrightnessController(  918): mCallbacks.updateBrightness()
D/DisplayPowerController(  918): getFinalBrightness : 8 -> 8
D/LockPatternUtilsCache( 1173): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1173): value : false
D/LockPatternUtilsCache( 1173): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1173): value : false
D/LockPatternUtilsCache( 1173): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1173): value : false
,D/LockPatternUtilsCache( 1173): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1173): value : false
D/LockPatternUtilsCache( 1173): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1173): value : false
I/WebViewFactory( 7416): Loading com.google.android.webview version 37 (1726107-arm) (code 119201)
D/ResourcesManager( 7416): creating new AssetManager and set to /system/app/WebViewGoogle/WebViewGoogle.apk
I/LibraryLoader( 7416): Loading: webviewchromium
D/LockPatternUtilsCache( 1173): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1173): value : false
I/LibraryLoader( 7416): Time to load native libraries: 2 ms (timestamps 5362-5364)
I/LibraryLoader( 7416): Expected native library version number "",actual native library version number ""
V/WebViewChromiumFactoryProvider( 7416): Binding Chromium to main looper Looper (main, tid 1) {33bd0d63}
I/LibraryLoader( 7416): Expected native library version number "",actual native library version number ""
I/chromium( 7416): [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
D/LockPatternUtilsCache( 1173): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1173): value : false
I/BrowserStartupController( 7416): Initializing chromium process, renderers=0
W/art     ( 7416): Attempt to remove local handle scope entry from IRT, ignoring
W/chromium( 7416): [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
I/chromium( 7416): [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=35 off=46768 len=2953
I/chromium( 7416): [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:36 off:229524 len:643667
D/LockPatternUtilsCache( 1173): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1173): value : false
I/Adreno-EGL( 7416): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 7416): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 7416): Build Date: 03/03/15 Tue
I/Adreno-EGL( 7416): Local Branch: LA.BF.1.1_RB1_20150108_025_1077123_1158499
I/Adreno-EGL( 7416): Remote Branch: 
I/Adreno-EGL( 7416): Local Patches: 
I/Adreno-EGL( 7416): Reconstruct Branch: 
D/LockPatternUtilsCache( 1173): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1173): value : false
D/LockPatternUtilsCache( 1173): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1173): value : false
W/chromium( 7416): [WARNING:proxy_service.cc(901)] PAC support disabled because there is no system implementation
W/chromium( 7416): [WARNING:data_reduction_proxy_settings.cc(403)] SPDY proxy OFF at startup
E/LightSensor(  918): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
D/AutomaticBrightnessController(  918): mCallbacks.updateBrightness()
D/DisplayPowerController(  918): getFinalBrightness : 8 -> 8
D/LockPatternUtilsCache( 1173): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1173): value : false
W/art     ( 7416): Attempt to remove local handle scope entry from IRT, ignoring
W/AwContents( 7416): onDetachedFromWindow called when already detached. Ignoring
D/LockPatternUtilsCache( 1173): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1173): value : false
D/SystemWebViewEngine( 7416): CordovaWebView is running on device made by: samsung
D/LockPatternUtilsCache( 1173): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1173): value : false
W/art     ( 7416): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 7416): Attempt to remove local handle scope entry from IRT, ignoring
D/LockPatternUtilsCache( 1173): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1173): value : false
D/LockPatternUtilsCache( 1173): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1173): value : false
D/LockPatternUtilsCache( 1173): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1173): value : false
D/LockPatternUtilsCache( 1173): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1173): value : false
D/LockPatternUtilsCache( 1173): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1173): value : false
D/Activity( 7416): performCreate Call secproduct feature valuefalse
D/Activity( 7416): performCreate Call debug elastic valuetrue
D/OpenGLRenderer( 7416): Render dirty regions requested: true
D/ActivityManager(  918): post active user change for 0
D/KnoxTimeoutHandler(  918): postActiveUserChange for user 0
D/KnoxTimeoutHandler(  918): handleActiveUserChange for user 0
D/LockPatternUtilsCache( 1173): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1173): value : false
D/LockPatternUtilsCache( 1173): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1173): value : false
D/LockPatternUtilsCache( 1173): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1173): value : false
I/SurfaceFlinger(  249): id=15 createSurf (1x1),1 flag=404, com.test.thalitest/com.test.thalitest.MainActivity
D/LockPatternUtilsCache( 1173): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1173): value : false
D/LockPatternUtilsCache( 1173): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1173): value : false
D/LockPatternUtilsCache( 1173): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1173): value : false
D/LockPatternUtilsCache( 1173): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1173): value : false
D/LockPatternUtilsCache( 1173): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1173): value : false
I/OpenGLRenderer( 7416): Initialized EGL, version 1.4
I/OpenGLRenderer( 7416): HWUI protection enabled for context ,  &this =0xa1553060 ,&mEglDisplay = 1 , &mEglConfig = 8 
D/OpenGLRenderer( 7416): Enabling debug mode 0
D/LockPatternUtilsCache( 1173): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1173): value : false
E/LightSensor(  918): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
D/AutomaticBrightnessController(  918): mCallbacks.updateBrightness()
D/DisplayPowerController(  918): getFinalBrightness : 8 -> 8
D/LockPatternUtilsCache( 1173): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1173): value : false
D/LockPatternUtilsCache( 1173): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1173): value : false
D/LockPatternUtilsCache( 1173): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1173): value : false
D/InputMethodManagerService(  918): windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
D/LockPatternUtilsCache( 1173): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1173): value : false
W/ContextImpl(  918): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.android.server.InputMethodManagerService$6.run:2728 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
W/ContextImpl(  918): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.android.server.InputMethodManagerService$6.run:2728 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
I/ActivityManager(  918): Displayed com.test.thalitest/.MainActivity: +564ms
D/LockPatternUtilsCache( 1173): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1173): value : false
D/LockPatternUtilsCache( 1173): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1173): value : false
D/LockPatternUtilsCache( 1173): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1173): value : false
I/SurfaceFlinger(  249): id=8 Removed com.sec.android.app.launcher/com.android.launcher2.Launcher (4/9)
I/SurfaceFlinger(  249): id=8 Removed com.sec.android.app.launcher/com.android.launcher2.Launcher (-2/9)
D/LockPatternUtilsCache( 1173): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1173): value : false
D/LockPatternUtilsCache( 1173): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1173): value : false
D/LockPatternUtilsCache( 1173): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1173): value : false
D/LockPatternUtilsCache( 1173): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1173): value : false
D/LockPatternUtilsCache( 1173): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1173): value : false
D/LockPatternUtilsCache( 1173): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1173): value : false
D/LockPatternUtilsCache( 1173): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1173): value : false
D/LockPatternUtilsCache( 1173): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1173): value : false
I/art     (  918): Explicit concurrent mark sweep GC freed 32794(1711KB) AllocSpace objects, 11(566KB) LOS objects, 30% free, 36MB/52MB, paused 1.317ms total 115.202ms
D/LockPatternUtilsCache( 1173): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1173): value : false
I/Timeline( 7416): Timeline: Activity_idle id: android.os.BinderProxy@2f3a4142 time:95786
D/LockPatternUtilsCache( 1173): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1173): value : false
E/LightSensor(  918): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
D/AutomaticBrightnessController(  918): mCallbacks.updateBrightness()
D/DisplayPowerController(  918): getFinalBrightness : 8 -> 8
D/LockPatternUtilsCache( 1173): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1173): value : false
D/LockPatternUtilsCache( 1173): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1173): value : false
D/LockPatternUtilsCache( 1173): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1173): value : false
D/LockPatternUtilsCache( 1173): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1173): value : false
D/JsMessageQueue( 7416): Set native->JS mode to OnlineEventsBridgeMode
D/LockPatternUtilsCache( 1173): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1173): value : false
D/LockPatternUtilsCache( 1173): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1173): value : false
D/LockPatternUtilsCache( 1173): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1173): value : false
I/SurfaceFlinger(  249): id=14 Removed Starting com.test.thalitest (7/8)
I/SurfaceFlinger(  249): id=14 Removed Starting com.test.thalitest (-2/8)
D/LockPatternUtilsCache( 1173): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1173): value : false
D/LockPatternUtilsCache( 1173): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1173): value : false
D/LockPatternUtilsCache( 1173): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1173): value : false
D/LockPatternUtilsCache( 1173): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1173): value : false
D/LockPatternUtilsCache( 1173): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1173): value : false
D/LockPatternUtilsCache( 1173): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1173): value : false
D/LockPatternUtilsCache( 1173): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1173): value : false
D/CustomFrequencyManagerService(  918): releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1958400  uid : 1000  pid : 918  tag : ACTIVITY_RESUME_BOOSTER@6
W/ActivityManager(  918): mDVFSHelper.release()
D/CustomFrequencyManagerService(  918): acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1958400  uid : 1000  pid : 918  pkgName : ACTIVITY_RESUME_BOOSTER@10
I/Timeline(  918): Timeline: Activity_windows_visible id: ActivityRecord{28af92b5 u0 com.test.thalitest/.MainActivity t11} time:95973
D/LockPatternUtilsCache( 1173): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1173): value : false
D/LockPatternUtilsCache( 1173): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1173): value : false
D/LockPatternUtilsCache( 1173): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1173): value : false
D/LockPatternUtilsCache( 1173): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1173): value : false
E/LightSensor(  918): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 3, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=1, bp1=1, cp1=3, cpl=3202560
D/AutomaticBrightnessController(  918): mCallbacks.updateBrightness()
D/DisplayPowerController(  918): getFinalBrightness : 8 -> 8
D/LockPatternUtilsCache( 1173): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1173): value : false
D/LockPatternUtilsCache( 1173): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1173): value : false
D/LockPatternUtilsCache( 1173): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1173): value : false
D/jxcore_app_log( 7416): JniHelper::setJavaVM(0xb4e5c280), pthread_self() = -1358533504
D/JX-Cordova( 7416): jxcore cordova android initializing
D/LockPatternUtilsCache( 1173): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1173): value : false
D/StatusBar.NetworkController( 1173): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02012b/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020466/com.android.systemui:drawable/stat_sys_signal_inout mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
D/StatusBar.NetworkController( 1173): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1173): applyOpen
D/StatusBar.NetworkController( 1173): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1173): applyOpen
D/StatusBar.NetworkController( 1173): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1173): applyOpen
D/StatusBar.NetworkController( 1173): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1173): applyOpen
E/BooksSync( 7348): Soft error
E/BooksSync( 7348): com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
E/BooksSync( 7348): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3DS0HXd4TFLU4&nonce=-5073401260082810871&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
E/BooksSync( 7348): Headers suppressed
E/BooksSync( 7348): 
E/BooksSync( 7348): com.google.android.apps.books.net.HttpHelper.wrapExceptionBasedOnStatus(HttpHelper.java:212)
E/BooksSync( 7348): Sync error
E/BooksSync( 7348): com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
E/BooksSync( 7348): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3DS0HXd4TFLU4&nonce=-5073401260082810871&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
E/BooksSync( 7348): Headers suppressed
E/BooksSync( 7348): 
E/BooksSync( 7348): com.google.android.apps.books.net.HttpHelper.wrapExceptionBasedOnStatus(HttpHelper.java:212)
I/BooksSync( 7348): Finished books sync
D/ConnectivityService(  918): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/SyncManager(  918): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 66028, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
I/ActivityManager(  918): Killing 6691:com.google.android.partnersetup/u0a15 (adj 15): bgCount ##41
D/ConnectivityService(  918): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/ConnectivityService(  918): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SecContentProvider2(  918): uri = 11 selection = getMyKnoxAdmin
,D/SecContentProvider2(  918): mCursor = null
,W/libprocessgroup(  918): failed to open /acct/uid_10015/pid_6691/cgroup.procs: No such file or directory
,E/LightSensor(  918): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 3, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=1, bp1=1, cp1=3, cpl=3202560
,D/AutomaticBrightnessController(  918): mCallbacks.updateBrightness()
D/DisplayPowerController(  918): getFinalBrightness : 8 -> 8
,D/CustomFrequencyManagerService(  918): releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1958400  uid : 1000  pid : 918  tag : ACTIVITY_RESUME_BOOSTER@10
,E/LightSensor(  918): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
D/AutomaticBrightnessController(  918): mCallbacks.updateBrightness()
,D/DisplayPowerController(  918): getFinalBrightness : 8 -> 8
,D/PowerManagerService(  918): [api] release WakeLock flags=0x10000006 tag=PowerUI.Notification uid=10059 pid=1173 (0x0)
,E/LightSensor(  918): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  918): mCallbacks.updateBrightness()
D/DisplayPowerController(  918): getFinalBrightness : 8 -> 8
,E/LightSensor(  918): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
D/AutomaticBrightnessController(  918): mCallbacks.updateBrightness()
D/DisplayPowerController(  918): getFinalBrightness : 8 -> 8
,E/LightSensor(  918): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  918): mCallbacks.updateBrightness()
D/DisplayPowerController(  918): getFinalBrightness : 8 -> 8
,I/GAV2    ( 7348): Thread[GAThread,5,main]: No campaign data found.
,D/StatusBar.NetworkController( 1173): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02012b/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020468/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
,D/StatusBar.NetworkController( 1173): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1173): applyOpen
,D/StatusBar.NetworkController( 1173): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1173): applyOpen
D/StatusBar.NetworkController( 1173): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1173): applyOpen
,D/StatusBar.NetworkController( 1173): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1173): applyOpen
,E/LightSensor(  918): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  918): mCallbacks.updateBrightness()
D/DisplayPowerController(  918): getFinalBrightness : 8 -> 8
,E/LightSensor(  918): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  918): mCallbacks.updateBrightness()
D/DisplayPowerController(  918): getFinalBrightness : 8 -> 8
,D/SSRM:m  (  918): SIOP:: AP = 390, PST = 436, CUR = 300
,W/jxcore-log( 7416): Initializing JXcore engine
W/jxcore-log( 7416): JXcore engine is ready
,W/jxcore-log( 7416): Starting JXcore engine
,E/auditd  ( 2055): In denial and Property audit_ondenial is set to 1 
,D/SecurityLogAgent:SEDenialService(  918): Got Modify Event and sending Denial Intent foraudit.log
,W/ContextImpl(  918): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.android.server.SEDenialService$AuditFileObserver.onEvent:76 android.os.FileObserver$ObserverThread.onEvent:122 android.os.FileObserver$ObserverThread.observe:-2 android.os.FileObserver$ObserverThread.run:85 
,D/SecurityLogAgent:SEDenialService(  918): audit.ondenial set to 0 after sending samsung.intent.action.knox.DENIAL_NOTIFICATION intent
,E/ActivityManager(  918): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  918): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  918): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  918): checkUser: useridlist=null, currentuser=0
,I/ActivityManager(  918): Start proc com.samsung.android.securitylogagent for broadcast com.samsung.android.securitylogagent/.receivers.SeDenialReceiver: pid=7477 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,E/Zygote  ( 7477): MountEmulatedStorage()
E/Zygote  ( 7477): v2
I/libpersona( 7477): KNOX_SDCARD checking this for 1000
I/libpersona( 7477): KNOX_SDCARD not a persona
,I/SELinux ( 7477): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
I/SELinux ( 7477): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
E/SELinux ( 7477): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,E/LightSensor(  918): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  918): mCallbacks.updateBrightness()
D/DisplayPowerController(  918): getFinalBrightness : 8 -> 8
,D/TimaKeyStoreProvider( 7477): TimaSignature is unavailable
,D/ActivityThread( 7477): Added TimaKeyStore provider
,D/ResourcesManager( 7477): creating new AssetManager and set to /system/app/SecurityLogAgent/SecurityLogAgent.apk
,D/SecurityLogAgent( 7477):  SeDenialReceiver : Intent Received : samsung.intent.action.knox.DENIAL_NOTIFICATION
,D/SecurityLogAgent( 7477):  SeDenialReceiver : File path = null
I/ActivityManager(  918): Killing 6712:com.samsung.groupcast/u0a16 (adj 15): bgCount ##41
,W/jxcore-log( 7416): Platform android
W/jxcore-log( 7416): 
W/jxcore-log( 7416): Process ARCH arm
W/jxcore-log( 7416): 
,W/libprocessgroup(  918): failed to open /acct/uid_10016/pid_6712/cgroup.procs: No such file or directory
,E/SMD     (  280): DCD ON
,E/LightSensor(  918): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  918): mCallbacks.updateBrightness()
D/DisplayPowerController(  918): getFinalBrightness : 8 -> 8
,E/LightSensor(  918): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  918): mCallbacks.updateBrightness()
,D/DisplayPowerController(  918): getFinalBrightness : 8 -> 8
,E/LightSensor(  918): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  918): mCallbacks.updateBrightness()
,D/DisplayPowerController(  918): getFinalBrightness : 8 -> 8
,D/StatusBar.NetworkController( 1173): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02012b/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020464/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
D/StatusBar.NetworkController( 1173): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1173): applyOpen
,D/StatusBar.NetworkController( 1173): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1173): applyOpen
D/StatusBar.NetworkController( 1173): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1173): applyOpen
D/StatusBar.NetworkController( 1173): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1173): applyOpen
,I/WifiStateMachine(  918): CMD_RSSI_POLL : calculateWifiScore in!
,I/WifiStateMachine(  918): CMD_RSSI_POLL : calculateWifiScore out!
I/WifiStateMachine(  918): CMD_RSSI_POLL : out!
,I/jxcore-log( 7416): JXcore Cordova bridge is ready!
I/jxcore-log( 7416): 
,W/jxcore-log( 7416): JXcore engine is started
,E/Adreno-ES20( 7416): <check_framebuffer_attachment:854>: Invalid texture format! Returning error!
E/Adreno-ES20( 7416): <check_framebuffer_object_status:1237>: Framebuffer color attachment incomplete. Returning GL_FRAMEBUFFER_INCOMPLETE_ATTACHMENT!
,E/LightSensor(  918): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  918): mCallbacks.updateBrightness()
D/DisplayPowerController(  918): getFinalBrightness : 8 -> 8
,E/LightSensor(  918): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  918): mCallbacks.updateBrightness()
D/DisplayPowerController(  918): getFinalBrightness : 8 -> 8
,E/LightSensor(  918): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  918): mCallbacks.updateBrightness()
,D/DisplayPowerController(  918): getFinalBrightness : 8 -> 8
,E/LightSensor(  918): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  918): mCallbacks.updateBrightness()
D/DisplayPowerController(  918): getFinalBrightness : 8 -> 8
,E/LightSensor(  918): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  918): mCallbacks.updateBrightness()
D/DisplayPowerController(  918): getFinalBrightness : 8 -> 8
,E/LightSensor(  918): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  918): mCallbacks.updateBrightness()
,D/DisplayPowerController(  918): getFinalBrightness : 8 -> 8
,I/jxcore-log( 7416): Toggling radios to true
I/jxcore-log( 7416): 
,D/BluetoothAdapter( 7416): enable()
,D/BluetoothAdapter( 7416): enable(): BT is already enabled..!
,D/WifiService(  918): New client listening to asynchronous messages
,I/WifiManager( 7416): packageName : com.test.thalitest
,D/SecContentProvider(  918): uri = 18 selection = isWifiEnabled
,D/SecContentProvider2(  918): uri = 20 selection = isWifiStateChangeAllowed
D/SecContentProvider2(  918): mCursor = null
,D/WifiService(  918): setWifiEnabled: true pid=7416, uid=10367
,E/WifiService(  918): Invoking mWifiStateMachine.setWifiEnabled
W/ActivityManager(  918): Permission Denial: getCurrentUser() from pid=7416, uid=10367 requires android.permission.INTERACT_ACROSS_USERS
,W/WifiService(  918): Failed getting userId using ActivityManagerNative
W/WifiService(  918): java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=7416, uid=10367 requires android.permission.INTERACT_ACROSS_USERS
W/WifiService(  918): 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:22619)
W/WifiService(  918): 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2119)
W/WifiService(  918): 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2107)
W/WifiService(  918): 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:223)
W/WifiService(  918): 	at android.os.Binder.execTransact(Binder.java:446)
,D/SettingsProvider(  918): name = wifi_on
,I/WifiService(  918): disconnect: pid=7416, uid=10367
,I/wpa_supplicant( 1293): [wpa_supplicant_ctrl_iface_process] : DISCONNECT
,I/jxcore-log( 7416): Radios toggled
I/jxcore-log( 7416): 
,I/jxcore-log( 7416): Got Device Bluetooth address: B0:C5:59:3F:75:69
I/jxcore-log( 7416): 
,I/jxcore-log( 7416): Perf Test app loaded loaded
I/jxcore-log( 7416): 
,E/LightSensor(  918): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
D/AutomaticBrightnessController(  918): mCallbacks.updateBrightness()
D/DisplayPowerController(  918): getFinalBrightness : 8 -> 8
,I/jxcore-log( 7416): check test folder
I/jxcore-log( 7416): 
,I/jxcore-log( 7416): found test : ./testFindPeers.js
I/jxcore-log( 7416): 
,I/wpa_supplicant( 1293): CTRL-EVENT-DISCONNECTED bssid=C0.AA.48 reason=3 locally_generated=1
,I/wpa_supplicant( 1293): wlan0: State: COMPLETED -> DISCONNECTED
,I/wpa_supplicant( 1293): CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=C0.AA.48 SSID=4E47373030
I/wpa_supplicant( 1293): wlan0: State: DISCONNECTED -> DISCONNECTED
,E/WifiStateMachine(  918): WifiStateMachine: Leaving Connected state
I/wpa_supplicant( 1293): reset timer : RESET_TIMER 0
I/wpa_supplicant( 1293): wlan0: Setting scan request: 0 sec 0 usec
I/wpa_supplicant( 1293): Disconnected - do not scan
I/wpa_supplicant( 1293): wlan0: State: DISCONNECTED -> DISCONNECTED
,E/WifiStateMachine(  918): handleNetworkDisconnect: Stopping DHCP and clearing IP stack:handleNetworkDisconnect - access$11200 - exit - invokeExitMethods
E/WifiStateMachine(  918): handleNetworkDisconnect c0:ff:d4:d3:aa:48 config "NG700"WPA_PSK config.bssid any
E/WifiStateMachine(  918): handleNetworkDisconnect "NG700" nid=0
E/WifiConfigStore(  918): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,E/WifiStateMachine(  918): setSuspendOptimizationsNative: 1 true -want true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - stopDhcp - handleNetworkDisconnect
,D/WifiP2pService(  918): InactiveState{ what=143375 }
,D/WifiP2pService(  918): P2pEnabledState{ what=143375 }
,V/AlarmManager(  918): waitForAlarm result :4
D/CommandListener(  274): Clearing all IP addresses on wlan0
,D/StatusBar.NetworkController( 1173): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02012b/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020464/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
,V/NativeCrypto( 1739): Read error: ssl=0xaf281e00: I/O error during system call, Connection timed out
,I/jxcore-log( 7416): found test : ./testSendData.js
I/jxcore-log( 7416): 
,V/NativeCrypto( 1739): SSL shutdown failed: ssl=0xaf281e00: I/O error during system call, Broken pipe
,D/ConnectivityService(  918): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  918): reportBadNetwork(NetworkAgentInfo [WIFI () - 502]) by 10012
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  918): ValidatedState{ when=0 what=532488 arg1=10012 target=com.android.internal.util.StateMachine$SmHandler }
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  918): DefaultState{ when=-1ms what=532488 arg1=10012 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  918): Forcing reevaluation
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  918): EvaluatingState{ when=0 what=532486 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  918): Validated
D/ConnectivityService(  918): Validated NetworkAgentInfo [WIFI () - 502]
D/ConnectivityService(  918): rematching NetworkAgentInfo [WIFI () - 502]
,D/ConnectivityService(  918):  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityService(  918):   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  918): Network NetworkAgentInfo [WIFI () - 502] was already satisfying request 1. No change.
D/ConnectivityService(  918): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 502]
D/ConnectivityService(  918): calling update connectivity
,D/ConnectivityService(  918):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  918):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  918): sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
,D/ConnectivityManager.CallbackHandler( 1173): CM callback handler got msg 524290
,D/ConnectivityService(  918): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  918): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/WifiStateMachine(  918): setDetailed state, old =CONNECTED and new state=DISCONNECTED hidden=false
,E/ConnectivityService(  918): updateNetworkInfo()
D/ConnectivityService(  918): NetworkAgentInfo [WIFI () - 502] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
,D/ConnectivityService(  918): NetworkAgentInfo [WIFI () - 502] got DISCONNECTED, was satisfying 2
,I/WifiTrafficPoller(  918): evaluateTrafficStatsPolling
,E/WifiConfigStore(  918): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,I/CLocInfoService(  918): External Intent Received android.net.wifi.STATE_CHANGE
,E/WifiStateMachine(  918): Start Disconnecting Watchdog 1
,D/StatusBar.NetworkController( 1173): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020498/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020133/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020464/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
D/StatusBar.NetworkController( 1173): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1173): applyOpen
D/StatusBar.NetworkController( 1173): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1173): applyOpen
D/StatusBar.NetworkController( 1173): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1173): applyOpen
,D/StatusBar.NetworkController( 1173): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1173): applyOpen
,I/wpa_supplicant( 1293): wlan0: Setting scan request: 0 sec 0 usec
I/wpa_supplicant( 1293): P2P: Current p2p state = IDLE
I/wpa_supplicant( 1293): wlan0: State: DISCONNECTED -> SCANNING
I/wpa_supplicant( 1293): CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00.00.00 SSID=
I/wpa_supplicant( 1293): First Scan Start
,E/WifiStateMachine(  918): ConnectModeState: Network connection lost 
I/wpa_supplicant( 1293): Scan requested (ret=0) - scan timeout 30 seconds
,E/WifiStateMachine(  918): handleNetworkDisconnect: Stopping DHCP and clearing IP stack:handleNetworkDisconnect - access$11200 - processMessage - processMsg
,E/WifiStateMachine(  918): setSuspendOptimizationsNative: 1 true -want true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - stopDhcp - handleNetworkDisconnect
D/WifiP2pService(  918): InactiveState{ what=143375 }
,D/WifiP2pService(  918): P2pEnabledState{ what=143375 }
,D/StatusBar.NetworkController( 1173): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020498/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020133/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020464/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
,I/Hs20UtilService( 1301): Starting #6
,I/Hs20UtilService( 1301): Message received 5007
,D/NearbySettings( 1301): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,V/NearbySettings( 1301): DMSUtil.isNetworkConnected - flag-null, state-null
D/ConnectivityService(  918): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/NearbySettings( 1301): DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,D/ConnectivityService(  918): returning getNetworkInfo(networkType - 13) :[type: WIFI_P2P[] - WIFI_P2P, state: UNKNOWN/IDLE, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/NearbySettings( 1301): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 1301): DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
,I/NearbySettings( 1301): MountReceiver.onReceive - Set preference state off
V/NearbySettings( 1301): MountReceiver.mPrefHandler - 7002
,I/jxcore-log( 7416): found test : ./testSendData2.js
I/jxcore-log( 7416): 
,E/jxcore  ( 7416): Error!: unlabeled break must be inside loop or switch
E/jxcore  ( 7416): Stack: [{"_fileName":"module.js","_functionName":"Module.prototype._compile","_lineNumber":"567","_columnNumber":"25","_msg":"    at Module.prototype._compile@module.js:567:25"},{"_fileName":"module.js","_functionName":"Module._extensions[\".js\"]","_lineNumber":"627","_columnNumber":"1","_msg":"    at Module._extensions[\".js\"]@module.js:627:1"},{"_fileName":"module.js","_functionName":"Module.prototype.load","_lineNumber":"418","_columnNumber":"7","_msg":"    at Module.prototype.load@module.js:418:7"},{"_fileName":"module.js","_functionName":"Module._load","_lineNumber":"382","_columnNumber":"5","_msg":"    at Module._load@module.js:382:5"},{"_fileName":"module.js","_functionName":"Module.prototype.require","_lineNumber":"453","_columnNumber":"10","_msg":"    at Module.prototype.require@module.js:453:10"},{"_fileName":"module.js","_functionName":"require","_lineNumber":"471","_columnNumber":"12","_msg":"    at require@module.js:471:12"},{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/perf_tests/PerfTestFrameworkClient.js","_functionName":"TestFrameworkClient/<","_lineNumber":"86","_columnNumber":"30","_msg":"    at TestFrameworkClient/<@/data/data/com.test.thalitest/files/www/jxcore/perf_tests/PerfTestFrameworkClient.js:86:30"},{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/perf_tests/PerfTestFrameworkClient.js","_functionName":"TestFrameworkClient","_lineNumber":"82","_columnNumber":"1","_msg":"    at TestFrameworkClient@/data/data/com.test.thalitest/files/www/jxcore/perf_tests/PerfTestFrameworkClient.js:82:1"},{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/app.js","_functionName":"","_lineNumber":"74","_columnNumber":"21","_msg":"    at @/data/data/com.test.thalitest/files/www/jxcore/app.js:74:21"}]
,I/Choreographer( 7416): Skipped 71 frames!  The application may be doing too much work on its main thread.
,D/CommandListener(  274): Clearing all IP addresses on wlan0
,D/ConnectivityService(  918): notifyType LOST for NetworkAgentInfo [WIFI () - 502]
D/ConnectivityService(  918): calling update connectivity
,D/ConnectivityService(  918):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,E/WifiStateMachine(  918): setDetailed state, old =DISCONNECTED and new state=DISCONNECTED hidden=false
D/ConnectivityService(  918):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  918): sending notification LOST for NetworkRequest [ id=2, legacyType=-1, [] ]
D/Nat464Xlat(  918): requiresClat: netType=1, connected=false, hasIPv4Address=true
,D/EntConnectivity(  918): Not allowed due to - mEnabled false
I/chromium( 7416): [INFO:SkUtilsArm.cpp(179)] Device supports ARM NEON instructions!
I/chromium( 7416): 
D/WifiStateMachine(  918): updateConfiguredNetworkExpiration - currTime: 1450657961411
D/WifiStateMachine(  918): updateConfiguredNetworkExpiration - AP, "NG700", is not shared AP.
D/ConnectivityService(  918): Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  918): sending new Min Network Score(0): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
I/WifiTrafficPoller(  918): evaluateTrafficStatsPolling
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  918): ValidatedState{ when=-3ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/TelephonyNetworkFactory( 1476): Cellular needs Network for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  918): DefaultState{ when=-3ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  918): Disconnected - quitting
,E/WifiStateMachine(  918): SUPPLICANT_STATE_CHANGE_EVENT state=DISCONNECTED -> state= DISCONNECTED debouncing=false
,E/WifiStateMachine(  918): setDetailed state, old =DISCONNECTED and new state=DISCONNECTED hidden=false
,D/ConnectivityManager.CallbackHandler( 1173): CM callback handler got msg 524292
D/CSLegacyTypeTracker(  918): Removing agent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{502}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.135/24,fe80::ee1f:72ff:fe18:8b78/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{true} created{true} explicitlySelected{false} }
D/CSLegacyTypeTracker(  918): Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 502] isDefaultNetwork=false
,D/ConnectivityService(  918): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,E/WifiStateMachine(  918): Link configuration changed for netId: -1 old: {LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0} new: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0}
,E/WifiStateMachine(  918): updateLinkProperties nid: -1 state: DISCONNECTED reason: CMD_UPDATE_LINKPROPERTIES
I/CLocInfoService(  918): External Intent Received android.net.wifi.STATE_CHANGE
E/WifiStateMachine(  918): Link configuration changed for netId: -1 old: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576} new: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0}
E/WifiStateMachine(  918): updateLinkProperties nid: -1 state: DISCONNECTED reason: CMD_UPDATE_LINKPROPERTIES
D/WifiNetworkAgent(  918): NetworkAgent: NetworkAgent channel lost
,E/WifiStateMachine(  918): SUPPLICANT_STATE_CHANGE_EVENT state=SCANNING -> state= SCANNING debouncing=false
,D/StatusBar.NetworkController( 1173): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020498/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020133/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020464/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
E/WifiStateMachine(  918): setDetailed state, old =DISCONNECTED and new state=SCANNING hidden=false
E/WifiStateMachine(  918): setDetailed state send new extra info"NG700"
,E/LightSensor(  918): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  918): mCallbacks.updateBrightness()
D/DisplayPowerController(  918): getFinalBrightness : 8 -> 8
D/ConnectivityService(  918): sendStickyBroadcastDelayed: delayMs=500, action=android.net.conn.CONNECTIVITY_CHANGE
,D/SmartBondingService(  918): SmartBondingReceiver: onReceive action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/SmartBondingService(  918): EVENT_UPDATE_SB_STATE called / mDisableBySIOP false
D/SmartBondingService(  918): getSBEnabled() enabled =false
D/SmartBondingService(  918): getSBEnabled() enabled =false
D/SmartBondingService(  918): getSBEnabled() enabled =false
D/SmartBondingService(  918): getNetworkEnabled : wifi : true mobile : true
V/NetworkStats(  918): updateIfacesLocked()
D/NtpTrustedTime(  918): currentTimeMillis() cache hit
V/NetworkStats(  918): performPollLocked(flags=0x1)
D/NetworkStatsFactory(  918): UpdateStatsForKnox
D/ConnectivityService(  918): returning getNetworkInfo(networkType - 28) :[type: MOBILE_ENT1[] - MOBILE_ENT1, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/SecContentProvider2(  918): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2(  918): mCursor = null
E/ConnectivityService(  918): EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
D/NtpTrustedTime(  918): currentTimeMillis() cache hit
I/chromium( 7416): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
V/NetworkStats(  918): performPollLocked() took 6ms
D/NtpTrustedTime(  918): currentTimeMillis() cache hit
D/NtpTrustedTime(  918): currentTimeMillis() cache hit
D/NtpTrustedTime(  918): currentTimeMillis() cache hit
V/NetworkStats(  918): advisePersistThreshold() given 9223372036854775, clamped to 2097152
D/NtpTrustedTime(  918): currentTimeMillis() cache hit
D/StatusBar.NetworkController( 1173): getUpdateDataNetType(): 0
D/StatusBar.NetworkController( 1173): updateDataNetType()
D/StatusBar.NetworkController( 1173): NoService, mRoamingIconId = 0
D/StatusBar.NetworkController( 1173): updateDataIcon, mDataDirectionIconId = (null) mDataConnected = false
D/StatusBar.NetworkController( 1173): updateTelephonySignalStrength: hasService=false ss=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte
D/StatusBar.NetworkController( 1173): updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal
D/StatusBar.NetworkController( 1173): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020498/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020133/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020464/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
D/StatusBar.NetworkController( 1173): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1173): applyOpen
D/NtpTrustedTime(  918): currentTimeMillis() cache hit
D/NtpTrustedTime(  918): currentTimeMillis() cache hit
D/StatusBar.NetworkController( 1173): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1173): applyOpen
D/StatusBar.NetworkController( 1173): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1173): applyOpen
D/StatusBar.NetworkController( 1173): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1173): applyOpen
,D/SecContentProvider2(  918): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2(  918): mCursor = null
I/chromium( 7416): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
I/Hs20UtilService( 1301): Starting #7
I/Hs20UtilService( 1301): Message received 5007
D/NearbySettings( 1301): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
V/NearbySettings( 1301): DMSUtil.isNetworkConnected - flag-null, state-null
D/ConnectivityService(  918): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/NearbySettings( 1301): DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
D/ConnectivityService(  918): returning getNetworkInfo(networkType - 13) :[type: WIFI_P2P[] - WIFI_P2P, state: UNKNOWN/IDLE, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/NearbySettings( 1301): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 1301): DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
I/NearbySettings( 1301): MountReceiver.onReceive - Set preference state off
V/NearbySettings( 1301): MountReceiver.mPrefHandler - 7002
,D/FileWriteThread_Telephony( 1476): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 1476): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 1476): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 1476): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 1476): FileWriteThread : threadType = 3
D/FileWriteThread_Telephony( 1476): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 1476): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 1476): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 1476): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 1476): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 1476): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 1476): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 1476): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 1476): FileWriteThread : threadType = 3
,E/LightSensor(  918): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  918): mCallbacks.updateBrightness()
D/DisplayPowerController(  918): getFinalBrightness : 8 -> 8
,V/GLSActivity( 1739): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1739): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
I/GLSUser ( 1739): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1739): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1739): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1739): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/Finsky  ( 6619): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,D/Finsky  ( 6619): [1] 5.onFinished: Installation state replication failed.
D/Finsky  ( 6619): [1] 5.onFinished: Scheduling replication attempt 2.
,E/LightSensor(  918): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
D/AutomaticBrightnessController(  918): mCallbacks.updateBrightness()
D/DisplayPowerController(  918): getFinalBrightness : 8 -> 8
,D/ConnectivityService(  918): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,I/ApplicationPolicy(  918): updateDataUsageMap
,D/ConnectivityService(  918): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  918): returning getNetworkInfo(networkType - 0) :[type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/Tethering(  918): MasterInitialState.processMessage what=3
,D/SmartBondingService(  918): SmartBondingReceiver: onReceive action=android.net.conn.CONNECTIVITY_CHANGE
D/ConnectivityService(  918): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  918): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  918): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/SmartBondingService(  918): EVENT_UPDATE_SB_STATE called / mDisableBySIOP false
I/CLocInfoService(  918): External Intent Received android.net.conn.CONNECTIVITY_CHANGE
D/SmartBondingService(  918): getSBEnabled() enabled =false
D/SmartBondingService(  918): getSBEnabled() enabled =false
D/SmartBondingService(  918): getSBEnabled() enabled =false
,D/ConnectivityService(  918): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/CLocInfoService(  918): CLoinfo wifi false
,D/accuweather( 1970): [KK AccuPhone]>>> SWW:66 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,W/SLocation(  918): No Active Data Connection
,D/ConnectivityService(  918): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SmartBondingService(  918): getNetworkEnabled : wifi : true mobile : true
,D/ConnectivityService(  918): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/PCWCLIENTTRACE_PushUtil( 6728): SPPPushClient is installed : true
I/PCWCLIENTTRACE_PushUtil( 6728): sales region : global
I/PCWCLIENTTRACE_PushUtil( 6728): getPushTypeList : [SPP, GCM]
,I/PCWCLIENTTRACE_SYSTEMReceiver( 6728): [onReceive] - android.net.conn.CONNECTIVITY_CHANGE
,I/PCWCLIENTTRACE_SYSTEMReceiver( 6728): noConnectivity : true
,I/DBG_DM  ( 3786): [com.wssyncmldm.XDMService(1111/IlIlllIIlIlIIIlIlIll)] WiFi network Connected : false
,D/ConnectivityService(  918): returning getNetworkInfo(networkType - 7) :[type: BLUETOOTH[] - BLUETOOTH, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/DBG_DM  ( 3786): [com.wssyncmldm.XDMService(1125/lllllIlIlIIIIIIIIlIl)] Bluetooth Data Connected : false
E/LightSensor(  918): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
D/AutomaticBrightnessController(  918): mCallbacks.updateBrightness()
,D/DisplayPowerController(  918): getFinalBrightness : 8 -> 8
,E/ActivityManager(  918): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  918): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  918): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  918): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 7528): MountEmulatedStorage()
,E/Zygote  ( 7528): v2
I/libpersona( 7528): KNOX_SDCARD checking this for 10126
I/libpersona( 7528): KNOX_SDCARD not a persona
,I/ActivityManager(  918): Start proc com.google.android.music:main for broadcast com.google.android.music/.homewidgets.IFLWidgetProvider: pid=7528 uid=10126 gids={50126, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/SELinux ( 7528): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 7528): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 7528): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 7528): TimaSignature is unavailable
,D/ActivityThread( 7528): Added TimaKeyStore provider
,D/ResourcesManager( 7528): creating new AssetManager and set to /system/app/Music2/Music2.apk
,I/MusicStore( 7528): Database version: 104
,E/LightSensor(  918): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  918): mCallbacks.updateBrightness()
D/DisplayPowerController(  918): getFinalBrightness : 8 -> 8
,D/ResourcesManager( 7528): creating new AssetManager and set to /data/app/com.google.android.gms-1/base.apk
,W/ResourcesManager( 7528): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,W/ResourcesManager( 7528): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,V/JNIHelp ( 7528): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
,W/ActivityThread( 7528): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,W/System  ( 7528): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@1064d095: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
,I/ProviderInstaller( 7528): Installed default security provider GmsCore_OpenSSL
D/AndroidMusic( 7528): GMSCore installation verified
,E/LightSensor(  918): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  918): mCallbacks.updateBrightness()
D/DisplayPowerController(  918): getFinalBrightness : 8 -> 8
,I/ConfigStore( 7528): Config Database version: 1
,E/Vold    (  248): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.music/files/
W/Vold    (  248): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7528): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.music/files
,E/Vold    (  248): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.music/files/
W/Vold    (  248): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7528): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.music/files
,E/Vold    (  248): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.music/files/
,W/Vold    (  248): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7528): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.music/files
,D/WifiDisplayAdapter(  918): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,D/WifiDisplayAdapter(  918): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,V/AudioPolicyManager(  288): getOutputsForDevice device 0002 -> 0002
,I/AudioService(  918): getStreamVolume 3 index 70
,I/MediaRouter( 7528): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=7, volumeMax=15, presentationDisplayId=-1, extras=null, providerPackageName=android }
,E/ActivityManager(  918): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  918): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  918): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  918): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 7556): MountEmulatedStorage()
,E/Zygote  ( 7556): v2
I/libpersona( 7556): KNOX_SDCARD checking this for 10002
I/libpersona( 7556): KNOX_SDCARD not a persona
,I/ActivityManager(  918): Start proc com.sec.android.cloudagent for broadcast com.sec.android.cloudagent/.detector.DetectorReceiver: pid=7556 uid=10002 gids={50002, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/wpa_supplicant( 1293): nl80211: Received scan results (2 BSSes)
I/wpa_supplicant( 1293): wlan0: Setting scan request: 8 sec 0 usec
,I/wpa_supplicant( 1293): Trying to associate with C0.AA.48 (SSID='4E47373030' freq=2412 MHz)
I/wpa_supplicant( 1293): wlan0: State: SCANNING -> ASSOCIATING
I/wpa_supplicant( 1293): CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00.00.00 SSID=
,E/WifiStateMachine(  918): [1,450,657,962,447 ms] noteScanEnd no scan source
,E/WifiStateMachine(  918): wifi setScanResults statecom.android.server.wifi.WifiStateMachine$DisconnectedState@3c8c8033 sup_state=SCANNING debouncing=false
,I/SELinux ( 7556): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 7556): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 7556): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,E/WifiStateMachine(  918): SUPPLICANT_STATE_CHANGE_EVENT state=ASSOCIATING -> state= CONNECTING debouncing=false
,I/CLocInfoService(  918): External Intent Received android.net.wifi.SCAN_RESULTS
,E/WifiStateMachine(  918): setDetailed state, old =SCANNING and new state=CONNECTING hidden=false
E/WifiStateMachine(  918): setDetailed state send new extra info0x
,D/SecContentProvider2(  918): uri = 20 selection = getPromptCredentialsEnabled
,D/SecContentProvider2(  918): mCursor = null
,D/PowerManagerService(  918): [s] UserActivityState : 1 -> 2
D/DisplayPowerController(  918): getFinalBrightness : 1 -> 1
,D/PowerManagerService(  918): [s] DisplayPowerCallbacks : onStateChanged()
,D/lights  (  918): lcd : 4 +
,D/lights  (  918): lcd : 4 -
,D/TimaKeyStoreProvider( 7556): TimaSignature is unavailable
,D/ActivityThread( 7556): Added TimaKeyStore provider
,D/WifiDisplayAdapter(  918): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,D/DisplayPowerController(  918): getFinalBrightness : 1 -> 1
,D/lights  (  918): lcd : 1 +
,D/lights  (  918): lcd : 1 -
,D/DisplayPowerController(  918): getFinalBrightness : 1 -> 1
,D/ConnectivityService(  918): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ResourcesManager( 7556): creating new AssetManager and set to /system/priv-app/CloudAgent/CloudAgent.apk
,I/NetworkMonitor( 7528): type=WIFI subType= reason=null isConnected=false
,I/ActivityManager(  918): Killing 6490:com.samsung.android.app.galaxyfinder/u0a34 (adj 15): bgCount ##41
,E/LightSensor(  918): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  918): mCallbacks.updateBrightness()
D/DisplayPowerController(  918): getFinalBrightness : 1 -> 1
,I/wpa_supplicant( 1293): wlan0: State: ASSOCIATING -> ASSOCIATED
I/wpa_supplicant( 1293): CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00.00.00 SSID=4E47373030
,I/wpa_supplicant( 1293): Associated with C0.AA.48
,W/libprocessgroup(  918): failed to open /acct/uid_10034/pid_6490/cgroup.procs: No such file or directory
,E/WifiStateMachine(  918): SUPPLICANT_STATE_CHANGE_EVENT state=ASSOCIATED -> state= CONNECTING debouncing=false
E/WifiStateMachine(  918): setDetailed state, old =CONNECTING and new state=CONNECTING hidden=false
,D/SecContentProvider2(  918): uri = 20 selection = getPromptCredentialsEnabled
,D/SecContentProvider2(  918): mCursor = null
,I/ActivityManager(  918): Killing 4717:com.sec.android.app.shealth/u0a35 (adj 15): bgCount ##41
,E/ActivityManager(  918): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  918): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  918): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  918): checkUser: useridlist=null, currentuser=0
,I/wpa_supplicant( 1293): wlan0: State: ASSOCIATED -> 4WAY_HANDSHAKE
I/wpa_supplicant( 1293): CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=C0.AA.48 SSID=4E47373030
,E/WifiStateMachine(  918): SUPPLICANT_STATE_CHANGE_EVENT state=FOUR_WAY_HANDSHAKE -> state= AUTHENTICATING debouncing=false
E/WifiStateMachine(  918): setDetailed state, old =CONNECTING and new state=AUTHENTICATING hidden=false
E/WifiStateMachine(  918): setDetailed state send new extra info"NG700"
E/Zygote  ( 7587): MountEmulatedStorage()
E/Zygote  ( 7587): v2
I/libpersona( 7587): KNOX_SDCARD checking this for 1000
I/libpersona( 7587): KNOX_SDCARD not a persona
,D/SecContentProvider2(  918): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2(  918): mCursor = null
,I/ActivityManager(  918): Start proc com.sec.android.diagmonagent for broadcast com.sec.android.diagmonagent/.DiagMonRegistrationReceiver: pid=7587 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,I/wpa_supplicant( 1293): wlan0: State: 4WAY_HANDSHAKE -> 4WAY_HANDSHAKE
,I/wpa_supplicant( 1293): wlan0: State: 4WAY_HANDSHAKE -> GROUP_HANDSHAKE
I/wpa_supplicant( 1293): CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=C0.AA.48 SSID=4E47373030
,I/wpa_supplicant( 1293): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
I/wpa_supplicant( 1293): wlan0: State: GROUP_HANDSHAKE -> COMPLETED
E/WifiStateMachine(  918): SUPPLICANT_STATE_CHANGE_EVENT state=GROUP_HANDSHAKE -> state= AUTHENTICATING debouncing=false
E/WifiStateMachine(  918): setDetailed state, old =AUTHENTICATING and new state=AUTHENTICATING hidden=false
I/wpa_supplicant( 1293): CTRL-EVENT-CONNECTED - Connection to C0.AA.48 completed (auth) [id=0 id_str=]
,I/wpa_supplicant( 1293): Blacklist: Clear (temp) 
I/wpa_supplicant( 1293): CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=C0.AA.48 SSID=4E47373030
,D/SecContentProvider2(  918): uri = 20 selection = getPromptCredentialsEnabled
,D/SecContentProvider2(  918): mCursor = null
,E/WifiStateMachine(  918): Network connection established
,D/WifiNative-HAL(  918): callSECApiVoid - ID [50]
I/SELinux ( 7587): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
E/WifiStateMachine(  918): setDetailed state, old =AUTHENTICATING and new state=OBTAINING_IPADDR hidden=false
E/WifiStateMachine(  918): setDetailed state, old =OBTAINING_IPADDR and new state=CONNECTING hidden=false
,I/SELinux ( 7587): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 7587): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
D/ConnectivityService(  918): registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{false} explicitlySelected{false} }
,E/WifiStateMachine(  918): L2ConnectedState c0:ff:d4:d3:aa:48 config "NG700"WPA_PSK config.bssid any
E/WifiStateMachine(  918): L2ConnectedState "NG700" nid=0
E/WifiConfigStore(  918): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
D/ConnectivityService(  918): Got NetworkAgent Messenger
D/ConnectivityService(  918): hsengiv:checkWhatTypeOfNetwork and the value is false
E/ConnectivityService(  918): updateNetworkInfo()
D/ConnectivityService(  918): NetworkAgentInfo [WIFI () - 503] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityService(  918): NetworkAgent connected
,I/CLocInfoService(  918): External Intent Received android.net.wifi.STATE_CHANGE
,D/StatusBar.NetworkController( 1173): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020498/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020133/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020464/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
,E/WifiStateMachine(  918): enter ObtainingIpState netId=0 "NG700"WPA_PSK  roam=0 static=false watchdog= 1
E/WifiStateMachine(  918): ObtainingIpAddress c0:ff:d4:d3:aa:48 config "NG700"WPA_PSK config.bssid any
E/WifiStateMachine(  918): ObtainingIpAddress "NG700" nid=0
E/WifiConfigStore(  918): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,D/TimaKeyStoreProvider( 7587): TimaSignature is unavailable
,D/ActivityThread( 7587): Added TimaKeyStore provider
,D/CommandListener(  274): Setting iface cfg
,E/WifiStateMachine(  918): Start Dhcp Watchdog 2
W/libprocessgroup(  918): failed to open /acct/uid_10035/pid_4717/cgroup.procs: No such file or directory
,I/WifiStateMachine(  918): CMD_RSSI_POLL : calculateWifiScore in!
,E/WifiStateMachine(  918): calculateWifiScore() report new score 60
I/WifiStateMachine(  918): calculateWifiScore : sendNetworkScore in!
I/WifiStateMachine(  918): calculateWifiScore : sendNetworkScore out!
I/WifiStateMachine(  918): CMD_RSSI_POLL : calculateWifiScore out!
I/WifiStateMachine(  918): CMD_RSSI_POLL : out!
,D/ConnectivityService(  918): updateNetworkScore for NetworkAgentInfo [WIFI () - 503] to 60
,E/WifiStateMachine(  918): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576} new: {InterfaceName: wlan0 LinkAddresses: []  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0}
,E/WifiStateMachine(  918): updateLinkProperties nid: 0 state: CONNECTING reason: CMD_UPDATE_LINKPROPERTIES
D/ConnectivityService(  918): Update of LinkProperties for NetworkAgentInfo [WIFI () - 503]; created=false
,D/ResourcesManager( 7587): creating new AssetManager and set to /system/priv-app/DiagMonAgent/DiagMonAgent.apk
,E/SMD     (  280): DCD ON
,I/DIAGMON_AGENT( 7587): [com.sec.android.diagmonagent.DiagMonAgentApplication(41/onCreate)] myUserId : 0
,I/DIAGMON_AGENT( 7587): [com.diagmondm.db.file.XDB(374/llIlIIIIlIIIIIlIlIII)] 
,E/LightSensor(  918): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  918): mCallbacks.updateBrightness()
D/DisplayPowerController(  918): getFinalBrightness : 1 -> 1
,E/WifiStateMachine(  918): setSuspendOptimizationsNative: 1 false -want true stack:setSuspendOptimizationsNative - handlePreDhcpSetup - processMessage - processMsg
E/native  (  918): do suspend false
,D/SecContentProvider2(  918): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2(  918): mCursor = null
,D/WifiP2pService(  918): InactiveState{ what=143375 }
D/WifiP2pService(  918): P2pEnabledState{ what=143375 }
,I/DIAGMON_AGENT( 7587): [com.sec.android.diagmonagent.DiagMonAgentApplication(61/onCreate)] nStatus : 0
,I/DIAGMON_AGENT( 7587): [com.sec.android.diagmonagent.DiagMonAgentApplication(78/onCreate)] DiagMon DM Application Start !
,I/DIAGMON_AGENT( 7587): [lIIllllllllIlIlIllll(17/llIIIIlllllIIllIIllI)] Receive broadcast: android.net.conn.CONNECTIVITY_CHANGE
,I/DIAGMON_AGENT( 7587): [lIIllllllllIlIlIllll(31/llIIIIlllllIIllIIllI)] Running with RegistrationReceiver
,E/ActivityManager(  918): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  918): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  918): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  918): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 7605): MountEmulatedStorage()
,E/Zygote  ( 7605): v2
I/libpersona( 7605): KNOX_SDCARD checking this for 10011
I/libpersona( 7605): KNOX_SDCARD not a persona
,I/ActivityManager(  918): Start proc com.sec.android.fotaclient for content provider com.sec.android.fotaclient/.log.MasterLogProvider: pid=7605 uid=10011 gids={50011, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/SELinux ( 7605): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 7605): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 7605): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 7605): TimaSignature is unavailable
,D/ActivityThread( 7605): Added TimaKeyStore provider
,D/ResourcesManager( 7605): creating new AssetManager and set to /system/priv-app/FotaClient/FotaClient.apk
,E/LightSensor(  918): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  918): mCallbacks.updateBrightness()
D/DisplayPowerController(  918): getFinalBrightness : 1 -> 1
,I/ActivityManager(  918): Killing 6747:com.policydm/1000 (adj 15): bgCount ##41
,I/FOTA_Client( 7605): [com.sec.android.fotaclient.FotaRegisterReceiver(113/onReceive)] Already device registered...
,I/FOTA_Client( 7605): [com.sec.android.fotaclient.FotaUpdaterReceiver(103/onReceive)] Auto update settings is activated
,E/dhcpcd  ( 7623): fopen `/system/etc/dhcpcd/dhcpcd.conf': No such file or directory
I/FOTA_Client( 7605): [lllllllllllIlllllIIl(197/lllIlIlIIIllIIlIllIl)] Polling time is vaild
,I/FOTA_Client( 7605): [com.sec.android.fotaclient.FotaUpdaterReceiver(126/onReceive)] Heartbeat settings is activated.
,I/dhcpcd  ( 7623): version 5.5.6 starting
,I/FOTA_Client( 7605): [llIlIIIIlllIlllllIll(125/llIlIIIIlIIIIIlIlIII)] heartbeat time is vaild
,E/dhcpcd  ( 7623): fopen `/system/etc/dhcpcd/dhcpcd.conf': No such file or directory
,E/ActivityManager(  918): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  918): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  918): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  918): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 7629): MountEmulatedStorage()
E/Zygote  ( 7629): v2
I/libpersona( 7629): KNOX_SDCARD checking this for 10019
I/libpersona( 7629): KNOX_SDCARD not a persona
,I/ActivityManager(  918): Start proc com.samsung.klmsagent for broadcast com.samsung.klmsagent/.listner.MainReciver: pid=7629 uid=10019 gids={50019, 9997, 3003} abi=armeabi-v7a
,I/ActivityManager(  918): Killing 5202:com.sec.spp.push/u0a38 (adj 15): bgCount ##41
,I/dhcpcd  ( 7623): wlan0: sending IPv6 Router Solicitation
E/dhcpcd  ( 7623): wlan0: sendmsg: Cannot assign requested address
I/dhcpcd  ( 7623): if(wlan0) info get Success. (MAC : C0.AA.48)
,I/dhcpcd  ( 7623): bssid match
,I/dhcpcd  ( 7623): wlan0: rebinding lease of 192.168.1.135
,I/SELinux ( 7629): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,W/libprocessgroup(  918): failed to open /acct/uid_1000/pid_6747/cgroup.procs: No such file or directory
,I/SELinux ( 7629): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 7629): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 7629): TimaSignature is unavailable
,D/ActivityThread( 7629): Added TimaKeyStore provider
,W/libprocessgroup(  918): failed to open /acct/uid_10038/pid_5202/cgroup.procs: No such file or directory
,D/ResourcesManager( 7629): creating new AssetManager and set to /system/priv-app/KLMSAgent/KLMSAgent.apk
,I/KLMS-2.4.503: ( 7629): KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,I/KLMS-2.4.503: ( 7629): MainReciver(): EventNotificationReciver- method called: AppActivityListner onReceive for Intent Action : android.net.conn.CONNECTIVITY_CHANGE , timestamp: 1450657963021
,I/KLMS-2.4.503: ( 7629): MainReciver(): NETWORK_STATE_CHANGED_ACTION
,D/ConnectivityService(  918): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  918): returning getNetworkInfo(networkType - 0) :[type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/KLMS-2.4.503: ( 7629): KLMSUtility(): isNetworkAvailable() - WIFI : false| MOBILE : false
,I/KLMS-2.4.503: ( 7629): StateImplV2(): networkChangeListener().END
,I/ActivityManager(  918): Killing 6004:com.samsung.android.sdk.samsunglink/u0a42 (adj 15): bgCount ##41
,E/ActivityManager(  918): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  918): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  918): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  918): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 7646): MountEmulatedStorage()
,E/Zygote  ( 7646): v2
I/libpersona( 7646): KNOX_SDCARD checking this for 10037
I/libpersona( 7646): KNOX_SDCARD not a persona
,E/LightSensor(  918): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  918): mCallbacks.updateBrightness()
D/DisplayPowerController(  918): getFinalBrightness : 1 -> 1
,I/ActivityManager(  918): Start proc com.sec.android.soagent for broadcast com.sec.android.soagent/.RegisterReceiver: pid=7646 uid=10037 gids={50037, 9997, 3003} abi=armeabi-v7a
,I/SELinux ( 7646): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
I/SELinux ( 7646): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 7646): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 7646): TimaSignature is unavailable
,D/ActivityThread( 7646): Added TimaKeyStore provider
,D/ResourcesManager( 7646): creating new AssetManager and set to /system/priv-app/SOAgent/SOAgent.apk
,W/libprocessgroup(  918): failed to open /acct/uid_10042/pid_6004/cgroup.procs: No such file or directory
,I/SO_AGENT( 7646): [com.sec.android.soagent.RegisterReceiver(98/onReceive)] Network is not available
,E/ActivityManager(  918): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  918): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  918): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  918): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 7661): MountEmulatedStorage()
,E/Zygote  ( 7661): v2
I/libpersona( 7661): KNOX_SDCARD checking this for 1000
I/libpersona( 7661): KNOX_SDCARD not a persona
,I/ActivityManager(  918): Start proc com.policydm for broadcast com.policydm/.XDMBroadcastReceiver: pid=7661 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,I/ActivityManager(  918): Killing 6769:com.osp.app.signin/u0a45 (adj 15): bgCount ##41
,I/SELinux ( 7661): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 7661): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 7661): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 7661): TimaSignature is unavailable
,D/ActivityThread( 7661): Added TimaKeyStore provider
,D/ResourcesManager( 7661): creating new AssetManager and set to /system/priv-app/SPDClient/SPDClient.apk
,W/libprocessgroup(  918): failed to open /acct/uid_10045/pid_6769/cgroup.procs: No such file or directory
,D/ConnectivityService(  918): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  918): returning getNetworkInfo(networkType - 0) :[type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/ActivityManager(  918): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  918): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  918): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  918): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 7681): MountEmulatedStorage()
I/libpersona( 7681): KNOX_SDCARD checking this for 10038
E/Zygote  ( 7681): v2
I/libpersona( 7681): KNOX_SDCARD not a persona
,I/ActivityManager(  918): Start proc com.sec.spp.push for broadcast com.sec.spp.push/.monitor.SystemStateMoniter: pid=7681 uid=10038 gids={50038, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  918): Killing 6791:com.sec.android.app.myfiles/u0a51 (adj 15): bgCount ##41
,E/LightSensor(  918): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  918): mCallbacks.updateBrightness()
D/DisplayPowerController(  918): getFinalBrightness : 1 -> 1
,I/art     (  313): Explicit concurrent mark sweep GC freed 8748(372KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 14MB/23MB, paused 322us total 11.361ms
,I/art     (  313): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 14MB/23MB, paused 251us total 8.339ms
,I/SELinux ( 7681): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/art     (  313): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 14MB/23MB, paused 785us total 8.833ms
,I/SELinux ( 7681): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 7681): [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
,D/ConnectivityService(  918): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  918): returning getNetworkInfo(networkType - 0) :[type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,W/libprocessgroup(  918): failed to open /acct/uid_10051/pid_6791/cgroup.procs: No such file or directory
,D/TimaKeyStoreProvider( 7681): TimaSignature is unavailable
,D/ActivityThread( 7681): Added TimaKeyStore provider
,D/ResourcesManager( 7681): creating new AssetManager and set to /system/priv-app/SPPPushClient_Prod/SPPPushClient_Prod.apk
,E/SPPClientService( 7681): ============PushLog. commonIsShipBuild. stop!
,E/SPPClientService( 7681): [PushClientApplication] Push log off : This is Ship build version
,D/SPPClientService( 7681): PushLog.txt file is not deleted.
,D/SPPClientService( 7681): PushLog.txt file is not deleted.
D/SPPClientService( 7681): ============PushLog. stop!
,E/SPPClientService( 7681): [[SystemStateMoniter]] SystemStateMonitorService : noConnect? : true
,E/ActivityManager(  918): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  918): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  918): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  918): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 7698): MountEmulatedStorage()
E/Zygote  ( 7698): v2
I/libpersona( 7698): KNOX_SDCARD checking this for 10045
I/libpersona( 7698): KNOX_SDCARD not a persona
,I/ActivityManager(  918): Start proc com.osp.app.signin for broadcast com.osp.app.signin/.OspReceiver: pid=7698 uid=10045 gids={50045, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  918): Killing 6810:com.sec.android.app.soundalive/u0a58 (adj 15): bgCount ##41
,I/SELinux ( 7698): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 7698): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 7698): [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
,E/SPPClientService( 7681): [[SystemStateMonitorService]] No Active Internet
,D/TimaKeyStoreProvider( 7698): TimaSignature is unavailable
,D/ActivityThread( 7698): Added TimaKeyStore provider
,W/libprocessgroup(  918): failed to open /acct/uid_10058/pid_6810/cgroup.procs: No such file or directory
,D/ResourcesManager( 7698): creating new AssetManager and set to /system/priv-app/Samsungservice2_xxhdpi/Samsungservice2_xxhdpi.apk
,E/LightSensor(  918): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  918): mCallbacks.updateBrightness()
D/DisplayPowerController(  918): getFinalBrightness : 1 -> 1
,I/SA      ( 7698): [SSP] onCreated
,I/SA      ( 7698): [TPM] There is no property file
,I/SA      ( 7698): [SCU] isHaveSA() - false
,I/SA      ( 7698): [TPM] getModelProperty : null
I/SA      ( 7698): [TPM] getCSCProperty : null
,I/SA      ( 7698): [DM] init START
,I/SA      ( 7698): [DM] This device is not a Vodafone
,W/ResourceType( 7698): Failure getting entry for 0x7f06000f (t=5 e=15) (error -75)
,W/ResourceType( 7698): Failure getting entry for 0x7f060007 (t=5 e=7) (error -75)
W/ResourceType( 7698): Failure getting entry for 0x7f060008 (t=5 e=8) (error -75)
,W/ResourceType( 7698): Failure getting entry for 0x7f06000b (t=5 e=11) (error -75)
W/ResourceType( 7698): Failure getting entry for 0x7f06000c (t=5 e=12) (error -75)
,W/ResourceType( 7698): Failure getting entry for 0x7f060001 (t=5 e=1) (error -75)
W/ResourceType( 7698): Failure getting entry for 0x7f060013 (t=5 e=19) (error -75)
,W/ResourceType( 7698): No package identifier when getting value for resource number 0x00000000
,W/ResourceType( 7698): Failure getting entry for 0x7f060022 (t=5 e=34) (error -75)
W/ResourceType( 7698): Failure getting entry for 0x7f060023 (t=5 e=35) (error -75)
,W/ResourceType( 7698): Failure getting entry for 0x7f060024 (t=5 e=36) (error -75)
W/ResourceType( 7698): Failure getting entry for 0x7f060025 (t=5 e=37) (error -75)
,W/ResourceType( 7698): Failure getting entry for 0x7f060026 (t=5 e=38) (error -75)
W/ResourceType( 7698): No package identifier when getting value for resource number 0x00000000
,W/ResourceType( 7698): Failure getting entry for 0x7f060010 (t=5 e=16) (error -75)
,W/ResourceType( 7698): Failure getting entry for 0x7f060009 (t=5 e=9) (error -75)
W/ResourceType( 7698): Failure getting entry for 0x7f06000a (t=5 e=10) (error -75)
W/ResourceType( 7698): Failure getting entry for 0x7f060002 (t=5 e=2) (error -75)
,W/ResourceType( 7698): Failure getting entry for 0x7f060014 (t=5 e=20) (error -75)
W/ResourceType( 7698): Failure getting entry for 0x7f060015 (t=5 e=21) (error -75)
,I/SA      ( 7698): [SCU] isHaveSA() - false
I/SA      ( 7698): support phone number id : false
,I/SA      ( 7698): [DM] init END
I/SA      ( 7698): [OR] onReceive log=[SA = 2.1.0142 V = 21 HWD = 1920X1080 3.0 dpi = 480  SIZE = 2 LOCALE = en_US CSC = DBT MCC = 0 MNC 0 T = user DEVICE = klte P = kltexx I = LRX21T M = SM-G900F OKLEFT false DIS LRX21T.G900FXXU1BOD3 PSS = 5.219788042639568  ]
,I/SA      ( 7698): [OR] onReceive Intent=[ conn.CONNECTIVITY_CHANGE. networkInfo:[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] networkType:1 inetCondition:0 extraInfo:? noConnectivity:true ]
I/SA      ( 7698): [OR] == ACTION_CONNECTIVITY_CHANGE ==
,I/SA      ( 7698): [SLFUCHKMGR] constructor called
,I/SA      ( 7698): [TPMU]  strSIMState 	:SIM_STATE_UNKNOWN
I/SA      ( 7698): [OR] == isSIMCardReady false ==
,I/SA      ( 7698): [SCU] == networkStateCheck == false
I/SA      ( 7698): [OR] onReceive END
,I/ActivityManager(  918): Killing 6212:com.samsung.android.app.assistantmenu/1000 (adj 15): bgCount ##41
,D/accuweather( 7264): [KK AccuPhone]>>> WC:30 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,D/accuweather( 7264): [KK AccuPhone]>>> WC:37 [0:0] oR : create UI manager : start
,D/accuweather( 7264): [KK AccuPhone]>>> UIMEM:90 [0:0] getInstance
D/accuweather( 7264): [KK AccuPhone]>>> UIMEM:78 [0:0] UIManager : create ui manager
,D/accuweather( 7264): [KK AccuPhone]>>> RM:73 [0:0] RefreshManager : create
D/accuweather( 7264): [KK AccuPhone]>>> RM:136 [0:0]  V init 
,D/daemonapp( 1331): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,W/libprocessgroup(  918): failed to open /acct/uid_1000/pid_6212/cgroup.procs: No such file or directory
,D/accuweather( 7264): [KK AccuPhone]>>> RM:128 [0:0] updateCityList
,D/daemonapp( 1331): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/weatherinfo
,D/accuweather( 7264): [KK AccuPhone]>>> DBH:3354 [0:0] gADWI : count = 0
,D/daemonapp( 1331): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/accuweather( 7264): [KK AccuPhone]>>> UIMEM:106 [0:0] The widget does not exist in idle!!
,D/accuweather( 7264): [KK AccuPhone]>>> UIMEM:106 [0:0] The widget does not exist in idle!!
,E/ActivityManager(  918): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  918): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  918): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  918): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 7719): MountEmulatedStorage()
E/Zygote  ( 7719): v2
I/libpersona( 7719): KNOX_SDCARD checking this for 1000
I/libpersona( 7719): KNOX_SDCARD not a persona
,I/ActivityManager(  918): Start proc com.sec.knox.bridge for broadcast com.sec.knox.bridge/.knoxusage.KnoxUsageReceiver: pid=7719 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,I/SELinux ( 7719): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
I/SELinux ( 7719): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
E/SELinux ( 7719): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 7719): TimaSignature is unavailable
,D/ActivityThread( 7719): Added TimaKeyStore provider
,D/ResourcesManager( 7719): creating new AssetManager and set to /system/app/Bridge/Bridge.apk
,W/ResourcesManager( 7719): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,I/KnoxUsageLogPro( 7719): KnoxUsageReceiver onReceive :android.net.conn.CONNECTIVITY_CHANGE myUserId=0
,I/KnoxUsageLogPro( 7719): premStatus:2
,I/KnoxUsageLogPro( 7719): isEulaShown : false
I/KnoxUsageLogPro( 7719): KnoxUsageReceiver onReceive : not Processible, just return
,E/ActivityManager(  918): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  918): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  918): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  918): checkUser: useridlist=null, currentuser=0
,E/LightSensor(  918): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  918): mCallbacks.updateBrightness()
D/DisplayPowerController(  918): getFinalBrightness : 1 -> 1
,E/Zygote  ( 7734): MountEmulatedStorage()
,E/Zygote  ( 7734): v2
I/libpersona( 7734): KNOX_SDCARD checking this for 10088
I/libpersona( 7734): KNOX_SDCARD not a persona
,I/ActivityManager(  918): Start proc com.android.chrome for broadcast com.android.chrome/com.google.android.apps.chrome.precache.PrecacheServiceLauncher: pid=7734 uid=10088 gids={50088, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  918): Killing 6830:com.google.android.apps.docs/u0a98 (adj 15): bgCount ##41
,I/SELinux ( 7734): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 7734): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 7734): [DEBUG] get_category: variable seinfo: chrome sensitivity: NULL, cateogry: NULL
,W/libprocessgroup(  918): failed to open /acct/uid_10098/pid_6830/cgroup.procs: No such file or directory
,D/TimaKeyStoreProvider( 7734): TimaSignature is unavailable
,D/ActivityThread( 7734): Added TimaKeyStore provider
,D/ResourcesManager( 7734): creating new AssetManager and set to /system/app/Chrome/Chrome.apk
,E/LightSensor(  918): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
D/AutomaticBrightnessController(  918): mCallbacks.updateBrightness()
D/DisplayPowerController(  918): getFinalBrightness : 1 -> 1
,I/ActivityManager(  918): Killing 6887:com.vlingo.midas/u0a33 (adj 15): bgCount ##41
,D/Headlines( 5454): HeadlinesSystemBroadcastReceiver onReceive android.net.conn.CONNECTIVITY_CHANGE
,D/HeadlinesChannelUtil( 5454): getCountryCode(): countryCode = DE
,E/ActivityManager(  918): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  918): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  918): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  918): checkUser: useridlist=null, currentuser=0
D/Headlines( 5454): Breath.onStartCommand : com.samsung.android.internal.headlines.UPDATE_WELCOME_CARD flag : 0
D/HeadlinesCardManager( 5454): updateCategory : HeadlinesCardManager:updateCategory() category size == 0
D/HeadlinesCardManager( 5454): updateCategory : HeadlinesCardManager:updateCategory() try to query category list
D/Headlines( 5454): queryCategory.  mRequest is not initialized.
D/HeadlinesCardManager( 5454): updateCategory : HeadlinesCardManager:updateCategory() reponse : false
D/HeadlinesCardManager( 5454): requestUpdateNewsWelcomeCard : request update welcome card to content card.
D/HeadlinesDataCenter( 5454): requestUpdateNewsWelcomeCard !!! no welcome card
,E/Zygote  ( 7753): MountEmulatedStorage()
I/libpersona( 7753): KNOX_SDCARD checking this for 10128
E/Zygote  ( 7753): v2
I/libpersona( 7753): KNOX_SDCARD not a persona
,I/ActivityManager(  918): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=7753 uid=10128 gids={50128, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/SELinux ( 7753): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
I/SELinux ( 7753): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
E/SELinux ( 7753): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 7753): TimaSignature is unavailable
,D/ActivityThread( 7753): Added TimaKeyStore provider
,W/libprocessgroup(  918): failed to open /acct/uid_10033/pid_6887/cgroup.procs: No such file or directory
,D/ResourcesManager( 7753): creating new AssetManager and set to /system/app/Newsstand/Newsstand.apk
,E/LightSensor(  918): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  918): mCallbacks.updateBrightness()
D/DisplayPowerController(  918): getFinalBrightness : 1 -> 1
,E/Vold    (  248): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  248): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7753): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache
,E/Vold    (  248): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  248): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7753): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/files
,E/Vold    (  248): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  248): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7753): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache
,E/Vold    (  248): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  248): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7753): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/files
,I/dhcpcd  ( 7623): wlan0: acknowledged 192.168.1.135 from 192.168.1.1
,I/WebViewFactory( 7753): Loading com.google.android.webview version 37 (1726107-arm) (code 119201)
,D/ResourcesManager( 7753): creating new AssetManager and set to /system/app/WebViewGoogle/WebViewGoogle.apk
,I/LibraryLoader( 7753): Loading: webviewchromium
,I/LibraryLoader( 7753): Time to load native libraries: 4 ms (timestamps 2050-2054)
,I/LibraryLoader( 7753): Expected native library version number "",actual native library version number ""
,I/dhcpcd  ( 7623): wlan0: leased 192.168.1.135 for 86400 seconds
,V/WebViewChromiumFactoryProvider( 7753): Binding Chromium to main looper Looper (main, tid 1) {1c4c0fd9}
,E/WifiStateMachine(  918): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: []  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576} new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.135/24,]  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0}
D/ConnectivityService(  918): Update of LinkProperties for NetworkAgentInfo [WIFI () - 503]; created=false
E/WifiStateMachine(  918): updateLinkProperties nid: 0 state: CONNECTING reason: CMD_UPDATE_LINKPROPERTIES v4
,I/LibraryLoader( 7753): Expected native library version number "",actual native library version number ""
,I/chromium( 7753): [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
,E/LightSensor(  918): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  918): mCallbacks.updateBrightness()
,D/DisplayPowerController(  918): getFinalBrightness : 1 -> 1
,I/BrowserStartupController( 7753): Initializing chromium process, renderers=0
,W/art     ( 7753): Attempt to remove local handle scope entry from IRT, ignoring
,W/chromium( 7753): [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
,I/chromium( 7753): [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=41 off=46768 len=2953
I/chromium( 7753): [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:42 off:229524 len:643667
,W/AudioManagerAndroid( 7753): Requires BLUETOOTH permission
,I/Adreno-EGL( 7753): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 7753): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 7753): Build Date: 03/03/15 Tue
I/Adreno-EGL( 7753): Local Branch: LA.BF.1.1_RB1_20150108_025_1077123_1158499
I/Adreno-EGL( 7753): Remote Branch: 
I/Adreno-EGL( 7753): Local Patches: 
I/Adreno-EGL( 7753): Reconstruct Branch: 
,I/NSApplication( 7753): Starting up...
,E/ActivityManager(  918): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  918): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  918): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  918): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 7833): MountEmulatedStorage()
E/Zygote  ( 7833): v2
I/libpersona( 7833): KNOX_SDCARD checking this for 10138
I/libpersona( 7833): KNOX_SDCARD not a persona
,I/ActivityManager(  918): Start proc com.samsung.android.sconnect for broadcast com.samsung.android.sconnect/.periph.PeriphStartReceiver: pid=7833 uid=10138 gids={50138, 9997, 3002, 3001, 1028, 1015, 3003} abi=armeabi-v7a
,I/ActivityManager(  918): Killing 6863:com.sec.android.automotive.drivelink/u0a99 (adj 15): bgCount ##41
,E/LightSensor(  918): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  918): mCallbacks.updateBrightness()
D/DisplayPowerController(  918): getFinalBrightness : 1 -> 1
,E/WifiStateMachine(  918): setSuspendOptimizationsNative: 1 true -want true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - processMessage - processMsg
,D/WifiP2pService(  918): InactiveState{ what=143375 }
D/WifiP2pService(  918): P2pEnabledState{ what=143375 }
,E/WifiStateMachine(  918): WifiStateMachine DHCP successful
,E/WifiStateMachine(  918): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: [192.168.1.135/24,]  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576} new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.135/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0}
,D/ConnectivityService(  918): Update of LinkProperties for NetworkAgentInfo [WIFI () - 503]; created=false
E/WifiStateMachine(  918): updateLinkProperties nid: 0 state: CONNECTING reason: DHCP_SUCCESS v4 v4r v4dns isprov
,E/WifiStateMachine(  918): WifiStateMachine: handleSuccessfulIpConfiguration and no scan results"NG700"WPA_PSK
,D/WifiStateMachine(  918): Not connected state, yet.
E/WifiStateMachine(  918): VerifyingLinkState enter
,I/SELinux ( 7833): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 7833): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
D/StatusBar.NetworkController( 1173): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020498/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020133/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020464/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
,E/SELinux ( 7833): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/WifiStateMachine(  918): updatePoorNetworkAvoidance - Poor Network Test Enabled / !mIsFmcNetwork : false / true - mPoorNetworkAvoidanceEnabled:disabled
,D/WifiStateMachine(  918): updatePoorNetworkDetection - Airplane Mode Off / Mobile Data Enabled / SIM State-Ready / MobilePolicyDataDisabled / !mIsFmcNetwork : 
D/WifiStateMachine(  918): false / true / false / true / true - mPoorNetworkDetectionEnabled: disabled
D/WifiNative-HAL(  918): callSECApiInt - ID [210]
,E/WifiStateMachine(  918): setDetailed state, old =CONNECTING and new state=VERIFYING_POOR_LINK hidden=false
E/ConnectivityService(  918): updateNetworkInfo()
,I/CLocInfoService(  918): External Intent Received android.net.wifi.STATE_CHANGE
,D/WifiWatchdogStateMachine(  918): updateDnsLinkProperty: enter
,D/ConnectivityService(  918): updateLinkProperties: newLp = {InterfaceName: wlan0 LinkAddresses: [192.168.1.135/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}
D/WifiWatchdogStateMachine.DnsPinger(  918): setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.135/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}
D/ConnectivityService(  918): Adding iface wlan0 to network 503
,D/WifiWatchdogStateMachine.DnsResolver(  918): setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.135/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}
D/WifiWatchdogStateMachine.SingDnsChecker(  918): setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.135/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}
,D/WifiWatchdogStateMachine.CaptivePortalDnsResolver(  918): setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.135/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}
,D/StatusBar.NetworkController( 1173): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020498/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020133/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020464/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
,E/WifiStateMachine(  918): VerifyingLinkState GOOD_LINK_DETECTED: transition to (new) connected (old)captive portal check
,W/libprocessgroup(  918): failed to open /acct/uid_10099/pid_6863/cgroup.procs: No such file or directory
,D/WifiStateMachine(  918): Now, connected state.
E/WifiStateMachine(  918): setDetailed state, old =VERIFYING_POOR_LINK and new state=CAPTIVE_PORTAL_CHECK hidden=false
,E/WifiStateMachine(  918): setDetailed state, old =CAPTIVE_PORTAL_CHECK and new state=CONNECTED hidden=false
,E/WifiStateMachine(  918): Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,I/WifiTrafficPoller(  918): evaluateTrafficStatsPolling
,I/CLocInfoService(  918): External Intent Received android.net.wifi.STATE_CHANGE
,D/TimaKeyStoreProvider( 7833): TimaSignature is unavailable
,D/StatusBar.NetworkController( 1173): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020498/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020133/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020464/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
D/ActivityThread( 7833): Added TimaKeyStore provider
,I/WifiTrafficPoller(  918): evaluateTrafficStatsPolling
,I/WifiTrafficPoller(  918): mBoosterFLAG : 0
,I/WifiTrafficPoller(  918): current booster mode : FullMode
D/WifiNative-HAL(  918): callSECApiVoid - ID [212]
,E/WifiStateMachine(  918): ConnectedState Enter  mScreenOn=true scanperiod=20000
D/ConnectivityService(  918): Adding Route [fe80::/64 -> :: wlan0] to network 503
,D/ConnectivityService(  918): Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 503
,D/ConnectivityService(  918): Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 503
,E/ConnectivityService(  918): Unexpected mtu value: 0, wlan0
D/ConnectivityService(  918): updateSourceRoutes : add source routing for type : 1
D/ConnectivityService(  918): updateSourceRoutes : add src route for:192.168.1.135
,V/        (  274): QcRouteController
,D/StatusBar.NetworkController( 1173): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02012b/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020464/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
D/StatusBar.NetworkController( 1173): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1173): applyOpen
D/StatusBar.NetworkController( 1173): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1173): applyOpen
D/StatusBar.NetworkController( 1173): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1173): applyOpen
D/StatusBar.NetworkController( 1173): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1173): applyOpen
,I/CLocInfoService(  918): External Intent Received android.net.wifi.STATE_CHANGE
,I/WifiStateMachine(  918): REQUEST_POWER_SAVE_ON
,V/        (  274): QcRouteController
,V/        (  274): QcRouteController
,D/StatusBar.NetworkController( 1173): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02012b/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020466/com.android.systemui:drawable/stat_sys_signal_inout mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
D/StatusBar.NetworkController( 1173): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1173): applyOpen
D/StatusBar.NetworkController( 1173): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1173): applyOpen
D/StatusBar.NetworkController( 1173): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1173): applyOpen
D/StatusBar.NetworkController( 1173): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1173): applyOpen
,D/ResourcesManager( 7833): creating new AssetManager and set to /system/app/QuickConnect/QuickConnect.apk
,V/        (  274): QcRouteController
,W/ResourcesManager( 7833): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,W/ResourcesManager( 7833): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
,W/ResourcesManager( 7833): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,V/        (  274): QcRouteController
,V/        (  274): QcRouteController
,V/        (  274): QcRouteController
,V/        (  274): QcRouteController
,D/QuickConnect( 7833): PeriphStartReceiver.onReceive - android.net.conn.CONNECTIVITY_CHANGE
,I/QuickConnect( 7833): PeriphStartReceiver.onReceive - USER_OWNER care CONNECTIVITY_ACTION. run P service
,I/QuickConnect( 7833): PeriphStartReceiver.onReceive - no need to start
,E/ActivityManager(  918): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  918): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  918): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  918): checkUser: useridlist=null, currentuser=0
,D/ConnectivityService(  918): Setting Dns servers for network 503 to [/192.168.1.1]
,E/Zygote  ( 7866): MountEmulatedStorage()
E/Zygote  ( 7866): v2
I/libpersona( 7866): KNOX_SDCARD checking this for 10163
I/libpersona( 7866): KNOX_SDCARD not a persona
,I/ActivityManager(  918): Start proc com.android.email for broadcast com.android.email/.EmailConnectivityManager: pid=7866 uid=10163 gids={50163, 9997, 3003, 1028, 1015, 1023, 3002, 3001, 1003} abi=armeabi-v7a
,I/ActivityManager(  918): Killing 6933:com.samsung.android.intelligenceservice/u0a3 (adj 15): bgCount ##41
,D/Nat464Xlat(  918): requiresClat: netType=1, connected=false, hasIPv4Address=true
D/ConnectivityService(  918): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 503]
E/ConnectivityService(  918): updateNetworkInfo()
D/ConnectivityService(  918): calling update connectivity
E/ConnectivityService(  918): updateNetworkInfo()
D/ConnectivityService(  918): ignoring duplicate network state non-change
D/ConnectivityService(  918): ignoring duplicate network state non-change
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  918): DefaultState{ when=0 what=532481 target=com.android.internal.util.StateMachine$SmHandler }
D/ConnectivityService(  918): NetworkAgentInfo [WIFI () - 503] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  918): Connected
D/ConnectivityService(  918): notifyType PRECHECK for NetworkAgentInfo [WIFI () - 503]
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  918): EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
D/ConnectivityService(  918): calling update connectivity
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  918): Validated
D/ConnectivityService(  918): rematching NetworkAgentInfo [WIFI () - 503]
D/ConnectivityService(  918):  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityService(  918):   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  918):   checking if request is satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  918): currentScore = 0, newScore = 60
D/ConnectivityService(  918):    accepting network in place of null
D/ConnectivityService(  918): sending new Min Network Score(60): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,E/CSLegacyTypeTracker(  918): add() : Adding agent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{503}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.135/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{true} explicitlySelected{false} } for legacy network type 1
D/CSLegacyTypeTracker(  918): Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 503] isDefaultNetwork=true
D/ConnectivityService(  918): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
E/LightSensor(  918): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
D/AutomaticBrightnessController(  918): mCallbacks.updateBrightness()
D/ConnectivityService(  918): sendStickyBroadcastDelayed: delayMs=500, action=android.net.conn.CONNECTIVITY_CHANGE
D/DisplayPowerController(  918): getFinalBrightness : 1 -> 1
D/ConnectivityService(  918): Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{503}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.135/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{true} explicitlySelected{false} }
D/NtpTrustedTime(  918): currentTimeMillis() cache hit
D/SmartBondingService(  918): SmartBondingReceiver: onReceive action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/NetworkStatsFactory(  918): UpdateStatsForKnox
D/SmartBondingService(  918): EVENT_UPDATE_SB_STATE called / mDisableBySIOP false
D/SmartBondingService(  918): getSBEnabled() enabled =false
D/SmartBondingService(  918): getSBEnabled() enabled =false
D/SmartBondingService(  918): getSBEnabled() enabled =false
V/NetworkStats(  918): updateIfacesLocked()
V/NetworkStats(  918): performPollLocked(flags=0x1)
D/ConnectivityService(  918): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 503]
D/ConnectivityService(  918): calling update connectivity
D/ConnectivityService(  918):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  918):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  918): sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  918): returning getNetworkInfo(networkType - 28) :[type: MOBILE_ENT1[] - MOBILE_ENT1, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/ConnectivityService(  918): Validated NetworkAgentInfo [WIFI () - 503]
D/ConnectivityService(  918): rematching NetworkAgentInfo [WIFI () - 503]
D/ConnectivityService(  918):  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityService(  918):   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  918): Network NetworkAgentInfo [WIFI () - 503] was already satisfying request 1. No change.
D/ConnectivityService(  918): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 503]
D/ConnectivityService(  918): calling update connectivity
D/ConnectivityService(  918):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  918):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  918): sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  918): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
D/NtpTrustedTime(  918): currentTimeMillis() cache hit
V/NetworkStats(  918): performPollLocked() took 3ms
I/SELinux ( 7866): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
D/TelephonyNetworkFactory( 1476): Cellular releasing Network for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
I/SELinux ( 7866): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
E/SELinux ( 7866): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
D/SmartBondingService(  918): getNetworkEnabled : wifi : true mobile : true
D/NtpTrustedTime(  918): currentTimeMillis() cache hit
D/NtpTrustedTime(  918): currentTimeMillis() cache hit
V/NetworkStats(  918): advisePersistThreshold() given 9223372036854775, clamped to 2097152
D/NtpTrustedTime(  918): currentTimeMillis() cache hit
D/NtpTrustedTime(  918): currentTimeMillis() cache hit
D/NtpTrustedTime(  918): currentTimeMillis() cache hit
D/NtpTrustedTime(  918): currentTimeMillis() cache hit
D/ConnectivityService(  918): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/StatusBar.NetworkController( 1173): getUpdateDataNetType(): 0
D/StatusBar.NetworkController( 1173): updateDataNetType()
,D/StatusBar.NetworkController( 1173): NoService, mRoamingIconId = 0
D/ConnectivityManager.CallbackHandler( 1173): CM callback handler got msg 524290
D/ConnectivityManager.CallbackHandler( 1173): CM callback handler got msg 524290
D/StatusBar.NetworkController( 1173): updateDataIcon, mDataDirectionIconId = (null) mDataConnected = false
D/StatusBar.NetworkController( 1173): updateTelephonySignalStrength: hasService=false ss=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte
D/StatusBar.NetworkController( 1173): updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal
D/StatusBar.NetworkController( 1173): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02012b/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020466/com.android.systemui:drawable/stat_sys_signal_inout mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
D/StatusBar.NetworkController( 1173): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1173): applyOpen
D/StatusBar.NetworkController( 1173): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1173): applyOpen
D/StatusBar.NetworkController( 1173): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1173): applyOpen
D/StatusBar.NetworkController( 1173): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1173): applyOpen
D/ConnectivityService(  918): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/StatusBar.NetworkController( 1173): getUpdateDataNetType(): 0
D/StatusBar.NetworkController( 1173): updateDataNetType()
D/StatusBar.NetworkController( 1173): NoService, mRoamingIconId = 0
D/TimaKeyStoreProvider( 7866): TimaSignature is unavailable
D/StatusBar.NetworkController( 1173): updateDataIcon, mDataDirectionIconId = (null) mDataConnected = false
D/StatusBar.NetworkController( 1173): updateTelephonySignalStrength: hasService=false ss=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte
D/StatusBar.NetworkController( 1173): updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal
D/StatusBar.NetworkController( 1173): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02012b/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020466/com.android.systemui:drawable/stat_sys_signal_inout mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
D/ActivityThread( 7866): Added TimaKeyStore provider
W/libprocessgroup(  918): failed to open /acct/uid_10003/pid_6933/cgroup.procs: No such file or directory
D/ResourcesManager( 7866): creating new AssetManager and set to /system/app/SecEmail_K/SecEmail_K.apk
W/ResourcesManager( 7866): Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
W/ResourcesManager( 7866): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 7866): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager( 7866): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,D/RCPManagerService(  918): exchangeData() failure , invalid userId
,D/RCPManagerService(  918): exchangeData() failure , invalid userId
,D/RCPManagerService(  918): exchangeData() failure , invalid userId
,E/ActivityManager(  918): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  918): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  918): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  918): checkUser: useridlist=null, currentuser=0
,D/RCPManagerService(  918): exchangeData() failure , invalid userId
,E/Zygote  ( 7888): MountEmulatedStorage()
,E/Zygote  ( 7888): v2
I/libpersona( 7888): KNOX_SDCARD checking this for 10078
I/libpersona( 7888): KNOX_SDCARD not a persona
,I/ActivityManager(  918): Start proc com.sec.android.provider.badge for content provider com.sec.android.provider.badge/.BadgeProvider: pid=7888 uid=10078 gids={50078, 9997} abi=armeabi-v7a
,V/BitmapFactory( 7866): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_015.png
,I/SELinux ( 7888): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 7888): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 7888): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,V/BitmapFactory( 7866): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_000.png
,V/BitmapFactory( 7866): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_015.png
,E/LightSensor(  918): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  918): mCallbacks.updateBrightness()
D/DisplayPowerController(  918): getFinalBrightness : 1 -> 1
,D/ConnectivityService(  918): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  918): returning getNetworkInfo(networkType - 0) :[type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/RCPManagerService(  918): exchangeData() failure , invalid userId
,V/BitmapFactory( 7866): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_000.png
,V/BitmapFactory( 7866): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_000.png
,D/RCPManagerService(  918): exchangeData() failure , invalid userId
,D/TimaKeyStoreProvider( 7888): TimaSignature is unavailable
,D/ActivityThread( 7888): Added TimaKeyStore provider
,I/ActivityManager(  918): Killing 6927:com.sec.android.provider.logsprovider/u0a20 (adj 15): bgCount ##41
,V/BitmapFactory( 7866): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_001.png
,V/BitmapFactory( 7866): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_002.png
,V/BitmapFactory( 7866): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_003.png
,V/BitmapFactory( 7866): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_004.png
,V/BitmapFactory( 7866): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_005.png
,D/ResourcesManager( 7888): creating new AssetManager and set to /system/app/BadgeProvider/BadgeProvider.apk
V/BitmapFactory( 7866): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_006.png
,V/BitmapFactory( 7866): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_007.png
,V/BitmapFactory( 7866): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_008.png
,V/BitmapFactory( 7866): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_010.png
,D/ConnectivityService(  918): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
V/BitmapFactory( 7866): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_011.png
,V/BitmapFactory( 7866): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_012.png
,D/SecurityLogAgent( 7477): KnoxConfiguration : Current State = 1
D/SecurityLogAgent( 7477): KnoxConfiguration : Current State Mapping Found 
D/SecurityLogAgent( 7477): StateMachine : Current State = 1
,V/BitmapFactory( 7866): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_013.png
,D/ConnectivityService(  918): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
V/BitmapFactory( 7866): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_014.png
,V/BitmapFactory( 7866): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_015.png
,V/BitmapFactory( 7866): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_000.png
D/SecurityLogAgent( 7477): StateMachine : Changed Current State = 1
,I/ActivityManager(  918): Killing 6964:com.samsung.android.app.filterinstaller/1000 (adj 15): bgCount ##41
,V/BitmapFactory( 7866): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_001.png
,D/BadgeProvider( 7888): onCreate
,D/BadgeProvider( 7888): DatabaseHelper
,V/BitmapFactory( 7866): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_002.png
,V/BitmapFactory( 7866): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_003.png
,V/BitmapFactory( 7866): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_004.png
D/com.peel.receiver.ConnectivityActionReceiver( 5557): ConnectivityActionReceiver onReceive
D/com.peel.receiver.ConnectivityActionReceiver( 5557): 
D/com.peel.receiver.ConnectivityActionReceiver( 5557): 
D/com.peel.receiver.ConnectivityActionReceiver( 5557): country_code: Germany -- rom region: GB
D/com.peel.receiver.ConnectivityActionReceiver( 5557): 
,V/BitmapFactory( 7866): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_005.png
,D/ConnectivityService(  918): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  918): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/com.peel.receiver.ConnectivityActionReceiver( 5557): 
D/com.peel.receiver.ConnectivityActionReceiver( 5557): 
D/com.peel.receiver.ConnectivityActionReceiver( 5557):  network type WIFI path... network offline: false
D/com.peel.receiver.ConnectivityActionReceiver( 5557): 
D/com.peel.receiver.ConnectivityActionReceiver( 5557): has active network... run services...
D/com.peel.receiver.ConnectivityActionReceiver( 5557): 
D/com.peel.receiver.ConnectivityActionReceiver( 5557): 
D/com.peel.receiver.ConnectivityActionReceiver( 5557): last run: 1450652956514 -- System.currentTimeMillis()-last_run: 5008217
D/com.peel.receiver.ConnectivityActionReceiver( 5557): ... skip 
D/com.peel.receiver.ConnectivityActionReceiver( 5557): ... skip last_72_check
,E/ActivityManager(  918): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  918): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  918): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  918): checkUser: useridlist=null, currentuser=0
,V/BitmapFactory( 7866): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_006.png
,V/BitmapFactory( 7866): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_007.png
,V/BitmapFactory( 7866): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_008.png
,E/Zygote  ( 7910): MountEmulatedStorage()
E/Zygote  ( 7910): v2
I/libpersona( 7910): KNOX_SDCARD checking this for 10178
I/libpersona( 7910): KNOX_SDCARD not a persona
,V/BitmapFactory( 7866): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_010.png
,V/BitmapFactory( 7866): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_011.png
I/ActivityManager(  918): Start proc com.samsung.android.service.travel for broadcast com.samsung.android.service.travel/com.samsung.android.travel.bindService.TravelBroadcastReceiver: pid=7910 uid=10178 gids={50178, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,V/BitmapFactory( 7866): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_012.png
,V/BitmapFactory( 7866): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_013.png
,V/BitmapFactory( 7866): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_014.png
,V/BitmapFactory( 7866): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_015.png
,V/BitmapFactory( 7866): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/delete_glance_line.pkm
,V/BitmapFactory( 7866): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/delete_glance_icon_undo.pkm
,I/SELinux ( 7910): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 7910): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 7910): [DEBUG] get_category: variable seinfo: shared sensitivity: NULL, cateogry: NULL
,V/BitmapFactory( 7866): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/list_icon_calendar_1.pkm
,V/BitmapFactory( 7866): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/email_attach_icon_etc.pkm
,V/BitmapFactory( 7866): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/list_icon_flag.pkm
,V/BitmapFactory( 7866): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/list_icon_complate.pkm
V/BitmapFactory( 7866): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/list_icon_flag_off_white.pkm
,V/BitmapFactory( 7866): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/email_list_attach_icon_star_off.pkm
,V/BitmapFactory( 7866): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/email_list_attach_icon_star_on.pkm
,V/BitmapFactory( 7866): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/list_icon_flag_f.pkm
,V/BitmapFactory( 7866): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/list_icon_complate_f.pkm
,V/BitmapFactory( 7866): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/list_icon_flag_off_f.pkm
,V/BitmapFactory( 7866): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/email_icon_foward.pkm
,V/BitmapFactory( 7866): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/email_icon_foward_focus.pkm
,V/BitmapFactory( 7866): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/list_icon_reply_forward.pkm
,V/BitmapFactory( 7866): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/email_icon_reply.pkm
,V/BitmapFactory( 7866): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/email_icon_reply_focus.pkm
,V/BitmapFactory( 7866): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/list_icon_vip.pkm
,V/BitmapFactory( 7866): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/email_list_high_priority.pkm
,V/BitmapFactory( 7866): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/email_list_low_priority.pkm
,V/BitmapFactory( 7866): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/list_icon_server_draft.pkm
,V/BitmapFactory( 7866): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/list_icon_client_draft.pkm
,V/BitmapFactory( 7866): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/permission.pkm
,D/TimaKeyStoreProvider( 7910): TimaSignature is unavailable
W/libprocessgroup(  918): failed to open /acct/uid_10020/pid_6927/cgroup.procs: No such file or directory
D/ActivityThread( 7910): Added TimaKeyStore provider
,W/libprocessgroup(  918): failed to open /acct/uid_1000/pid_6964/cgroup.procs: No such file or directory
,V/BitmapFactory( 7866): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/list_icon_voicemail.pkm
,V/BitmapFactory( 7866): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/list_icon_sms.pkm
,V/BitmapFactory( 7866): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/list_icon_sign.pkm
,V/BitmapFactory( 7866): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/list_icon_encryption.pkm
,D/ResourcesManager( 7910): creating new AssetManager and set to /system/app/TravelService_K/TravelService_K.apk
,I/art     (  918): Explicit concurrent mark sweep GC freed 62588(3MB) AllocSpace objects, 6(96KB) LOS objects, 30% free, 36MB/52MB, paused 1.506ms total 99.631ms
,V/BitmapFactory( 7866): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/tw_expander_open_01_holo_light.pkm
,V/BitmapFactory( 7866): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/tw_expander_close_01_holo_light.pkm
,D/BadgeProvider( 7888): query, [selection] : package='com.android.email' AND class='com.android.email.activity.Welcome' AND extraData='base_extra_badge'
,E/LightSensor(  918): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  918): mCallbacks.updateBrightness()
D/DisplayPowerController(  918): getFinalBrightness : 1 -> 1
,D/BadgeProvider( 7888): sendNotify entered. [uri] : content://com.sec.badge/apps/1
D/BadgeProvider( 7888): sendNotify, [notify] : null
D/BadgeProvider( 7888): update, [uri] : content://com.sec.badge/apps/1
D/BadgeProvider( 7888): update, [BadgeCount] : badgecount=0
D/BadgeProvider( 7888): update, [UpdateCount] : 1
,D/ConnectivityService(  918): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/Launcher.Model( 1490): reloadBadges entered.
,D/ConnectivityService(  918): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  918): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  918): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  918): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ChimeraCfgMgr( 2454): Loading module com.google.android.gms.kids from APK com.google.android.gms
,D/ConnectivityService(  918): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  918): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ChimeraCfgMgr( 2454): Loading module com.google.android.gms.kids from APK com.google.android.gms
,D/ConnectivityService(  918): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  918): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/WaitQueueForNetworkActivate( 7097): notifyNetworkActivated
,I/GLSUser ( 1739): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: ac2dm
,I/GLSUser ( 1739): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> ac2dm without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1739): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1739): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,W/ActivityManager(  918): Unable to start service Intent { cmp=com.android.email/.service.AttachmentDownloadService } U=0: not found
,V/GLSActivity( 1739): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ContextImpl( 7097): Implicit intents with startService are not safe: Intent { act=com.sec.knox.containeragent.service.containermanager.ContainerManagerService } android.content.ContextWrapper.bindService:559 com.sec.knox.containeragent.ContainerManager.<init>:49 com.sec.android.app.samsungapps.vlibrary2.knoxmode.KNOXAPI.<init>:20 
,W/ActivityManager(  918): Unable to start service Intent { act=com.sec.knox.containeragent.service.containermanager.ContainerManagerService } U=0: not found
,V/BitmapFactory( 1739): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/common_ic_googleplayservices.png
,V/BitmapFactory( 1739): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  918): uri = 14 selection = getSealedState
D/SecContentProvider2(  918): mCursor = null
,D/SecContentProvider2(  918): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  918): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
V/ApplicationPolicy(  918): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,W/Kids    ( 2454): [AccountUtils] Account not ready
W/Kids    ( 2454): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/Kids    ( 2454): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/Kids    ( 2454): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/Kids    ( 2454): 	at com.google.android.gms.auth.p.c(SourceFile:550)
W/Kids    ( 2454): 	at com.google.android.gms.auth.p.b(SourceFile:477)
W/Kids    ( 2454): 	at com.google.android.gms.kids.account.k.d(SourceFile:103)
W/Kids    ( 2454): 	at com.google.android.gms.kids.account.p.a(SourceFile:70)
W/Kids    ( 2454): 	at com.google.android.gms.kids.account.t.a(SourceFile:62)
W/Kids    ( 2454): 	at com.google.android.gms.chimera.f.run(SourceFile:179)
W/Kids    ( 2454): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
W/Kids    ( 2454): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
W/Kids    ( 2454): 	at java.lang.Thread.run(Thread.java:818)
,D/StatusBar( 1173): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,I/PhoneStatusBar( 1173): Icon Only
,D/LockPatternUtilsCache( 1173): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1173): value : false
D/PanelView( 1173): There is/are notification(s) 
D/PanelView( 1173): There is/are notification(s) 
,D/ConnectivityService(  918): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/ConnectivityService(  918): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  918): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/Tethering(  918): MasterInitialState.processMessage what=3
D/SmartBondingService(  918): SmartBondingReceiver: onReceive action=android.net.conn.CONNECTIVITY_CHANGE
,D/SmartBondingService(  918): SmartBondingReceiver: wifi is connected
D/SmartBondingService(  918): SmartBondingReceiver: wifi ap is not changed
D/ConnectivityService(  918): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/ConnectivityService(  918): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/SmartBondingService(  918): EVENT_UPDATE_SB_STATE called / mDisableBySIOP false
D/SmartBondingService(  918): getSBEnabled() enabled =false
D/SmartBondingService(  918): getSBEnabled() enabled =false
,D/SmartBondingService(  918): getSBEnabled() enabled =false
,I/CLocInfoService(  918): External Intent Received android.net.conn.CONNECTIVITY_CHANGE
,D/ConnectivityService(  918): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/CLocInfoService(  918): CLocinfo wifi true 
D/ConnectivityService(  918): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  918): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/SmartBondingService(  918): getNetworkEnabled : wifi : true mobile : true
,D/accuweather( 1970): [KK AccuPhone]>>> SWW:66 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,D/ConnectivityService(  918): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  918): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/ConnectivityService(  918): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  918): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  918): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  918): returning getNetworkInfo(networkType - 0) :[type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  918): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/DBG_DM  ( 3786): [lllllllIlllIIlllIlIl(88/llIIIIlllllIIllIIllI)] WiFi Network is connected
,I/DBG_DM  ( 3786): [com.wssyncmldm.XDMService(1111/IlIlllIIlIlIIIlIlIll)] WiFi network Connected : true
,W/ContextImpl( 2086): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1994 android.content.ContextWrapper.startService:533 com.samsung.SMT.SamsungTTSService.d:-1 com.samsung.SMT.SamsungTTSService.a:-1 com.samsung.SMT.ai.onReceive:-1 
,D/ConnectivityService(  918): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/ConnectivityService(  918): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  918): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
W/ContextImpl( 2086): Implicit intents with startService are not safe: Intent { act=com.samsung.SMT.UpdateManager.UPDATE_DATA } android.content.ContextWrapper.startService:533 com.samsung.SMT.SamsungTTSService.d:-1 com.samsung.SMT.SamsungTTSService.a:-1 
D/ConnectivityService(  918): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/ConnectivityService(  918): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  918): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/NetworkMonitor( 7528): type=WIFI subType= reason=null isConnected=true
,D/ConnectivityService(  918): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  918): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/ConnectivityService(  918): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/LightSensor(  918): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  918): mCallbacks.updateBrightness()
D/DisplayPowerController(  918): getFinalBrightness : 1 -> 1
,D/ConnectivityService(  918): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  918): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SecContentProvider2(  918): uri = 11 selection = getMyKnoxAdmin
D/SecContentProvider2(  918): mCursor = null
,D/hcjo    ( 7097): AutoUpdateManager:IDLE:execute
,I/Hs20UtilService( 1301): Starting #8
,I/Hs20UtilService( 1301): Message received 5007
,D/InitializeManagerStateMachine( 7097): execute::IDLE:EXECUTE
D/InitializeManagerStateMachine( 7097): exit::IDLE
D/InitializeManagerStateMachine( 7097): entry::NETWORK_CHECK
,D/NearbySettings( 1301): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
V/NearbySettings( 1301): DMSUtil.isNetworkConnected - flag-null, state-null
,D/ConnectivityService(  918): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/NearbySettings( 1301): DMSUtil.isNetworkConnected - WIFI: CONNECTED
D/ConnectivityService(  918): returning getNetworkInfo(networkType - 0) :[type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/ConnectivityService(  918): returning getNetworkInfo(networkType - 13) :[type: WIFI_P2P[] - WIFI_P2P, state: UNKNOWN/IDLE, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  918): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/InitializeManagerStateMachine( 7097): execute::NETWORK_CHECK:NETWORK_STATE_OK
I/NearbySettings( 1301): DMSUtil.isNetworkConnected - P2P: IDLE
D/InitializeManagerStateMachine( 7097): exit::NETWORK_CHECK
I/NearbySettings( 1301): DMSUtil.isNetworkConnected - WIFI-true, Hotspot-false, P2P-false, Eth-false
D/InitializeManagerStateMachine( 7097): entry::CHECK_COUNTRY_INFO
I/NearbySettings( 1301): MountReceiver.onReceive - Keep current state
D/InitializeManagerStateMachine( 7097): execute::CHECK_COUNTRY_INFO:COUNTRY_INFO_OK
D/InitializeManagerStateMachine( 7097): exit::CHECK_COUNTRY_INFO
D/InitializeManagerStateMachine( 7097): entry::SUCCESS
D/hcjo    ( 7097): AutoUpdateManager:INITCHECK:onInitializeSuccess
,D/hcjo    ( 7097): AutoUpdateTriggerManager:IDLE:notifyNextTime
,D/hcjo    ( 7097): AutoUpdateManager:UPD_CHECK_TIMING:onNoUpdateTime
D/ConnectivityService(  918): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/Hs20UtilService( 1301): Starting #9
I/Hs20UtilService( 1301): Message received 5007
,D/InitializeManagerStateMachine( 7097): exit::SUCCESS
D/InitializeManagerStateMachine( 7097): entry::IDLE
D/NearbySettings( 1301): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,I/NearbySettings( 1301): MountReceiver.onReceive - Keep current state
,I/Hs20UtilService( 1301): Starting #10
,I/Hs20UtilService( 1301): Message received 5007
,D/NearbySettings( 1301): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,V/NearbySettings( 1301): DMSUtil.isNetworkConnected - flag-null, state-null
D/ConnectivityService(  918): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/NearbySettings( 1301): DMSUtil.isNetworkConnected - WIFI: CONNECTED
D/ConnectivityService(  918): returning getNetworkInfo(networkType - 13) :[type: WIFI_P2P[] - WIFI_P2P, state: UNKNOWN/IDLE, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/NearbySettings( 1301): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 1301): DMSUtil.isNetworkConnected - WIFI-true, Hotspot-false, P2P-false, Eth-false
I/NearbySettings( 1301): MountReceiver.onReceive - Keep current state
,I/Hs20UtilService( 1301): Starting #11
,I/Hs20UtilService( 1301): Message received 5007
,D/NearbySettings( 1301): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,I/NearbySettings( 1301): MountReceiver.onReceive - Keep current state
,I/WifiStateMachine(  918): callSECApi what=220
D/WifiStateMachine(  918): SEC_COMMAND_ID_GET_FWS_OPEN_AP_CHECK : 0
,I/PCWCLIENTTRACE_PushUtil( 6728): SPPPushClient is installed : true
I/PCWCLIENTTRACE_PushUtil( 6728): sales region : global
I/PCWCLIENTTRACE_PushUtil( 6728): getPushTypeList : [SPP, GCM]
I/PCWCLIENTTRACE_SYSTEMReceiver( 6728): [onReceive] - android.net.conn.CONNECTIVITY_CHANGE
,I/SurfaceFlinger(  249): id=16 createSurf (1x1),1 flag=4, Toast
,I/DIAGMON_AGENT( 7587): [lIIllllllllIlIlIllll(17/llIIIIlllllIIllIIllI)] Receive broadcast: android.net.conn.CONNECTIVITY_CHANGE
D/LockPatternUtilsCache( 1173): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1173): value : false
I/DIAGMON_AGENT( 7587): [lIIllllllllIlIlIllll(31/llIIIIlllllIIllIIllI)] Running with RegistrationReceiver
D/LockPatternUtilsCache( 1173): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1173): value : false
,D/LockPatternUtilsCache( 1173): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1173): value : false
,D/PowerManagerService(  918): [api] acquire WakeLock flags=0x2000000a tag=WindowManager uid=1000 pid=918
,D/DisplayPowerController(  918): getFinalBrightness : 8 -> 8
,D/PowerManagerService(  918): [s] DisplayPowerCallbacks : onStateChanged()
,D/LockPatternUtilsCache( 1173): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1173): value : false
,D/LockPatternUtilsCache( 1173): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1173): value : false
D/LockPatternUtilsCache( 1173): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1173): value : false
,D/DisplayPowerController(  918): getFinalBrightness : 8 -> 8
,D/lights  (  918): lcd : 8 +
D/LockPatternUtilsCache( 1173): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1173): value : false
,D/LockPatternUtilsCache( 1173): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1173): value : false
,D/LockPatternUtilsCache( 1173): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1173): value : false
D/LockPatternUtilsCache( 1173): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1173): value : false
,D/lights  (  918): lcd : 8 -
,D/DisplayPowerController(  918): getFinalBrightness : 8 -> 8
,D/LockPatternUtilsCache( 1173): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1173): value : false,
D/LockPatternUtilsCache( 1173): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1173): value : false
D/LockPatternUtilsCache( 1173): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1173): value : false
D/LockPatternUtilsCache( 1173): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1173): value : false
E/LightSensor(  918): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
D/AutomaticBrightnessController(  918): mCallbacks.updateBrightness()
D/DisplayPowerController(  918): getFinalBrightness : 8 -> 8
,I/FOTA_Client( 7605): [com.sec.android.fotaclient.FotaRegisterReceiver(113/onReceive)] Already device registered...
,D/LockPatternUtilsCache( 1173): getCarrierLockPlusMode(),
D/LockPatternUtilsCache( 1173): value : false
I/FOTA_Client( 7605): [com.sec.android.fotaclient.FotaUpdaterReceiver(103/onReceive)] Auto update settings is activated
,I/FOTA_Client( 7605): [lllllllllllIlllllIIl(197/lllIlIlIIIllIIlIllIl)] Polling time is vaild
,I/FOTA_Client( 7605): [com.sec.android.fotaclient.FotaUpdaterReceiver(126/onReceive)] Heartbeat settings is activated.
,I/FOTA_Client( 7605): [llIlIIIIlllIlllllIll(125/llIlIIIIlIIIIIlIlIII)] heartbeat time is vaild
,I/KLMS-2.4.503: ( 7629): KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,I/KLMS-2.4.503: ( 7629): MainReciver(): EventNotificationReciver- method called: AppActivityListner onReceive for Intent Action : android.net.conn.CONNECTIVITY_CHANGE , timestamp: 1450657965228
,I/KLMS-2.4.503: ( 7629): MainReciver(): NETWORK_STATE_CHANGED_ACTION
,D/ConnectivityService(  918): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/ConnectivityService(  918): returning getNetworkInfo(networkType - 0) :[type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/KLMS-2.4.503: ( 7629): KLMSUtility(): isNetworkAvailable() - WIFI : true| MOBILE : false
,D/LockPatternUtilsCache( 1173): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1173): value : false
,I/KLMS-2.4.503: ( 7629): StateImplV2(): networkChangeListener().START
,I/KLMS-2.4.503: ( 7629): NetworkChangeOperations(): uploadRequestLog().START 
,I/KLMS-2.4.503: ( 7629): StateImplV2(): networkChangeListener().END
,D/LockPatternUtilsCache( 1173): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1173): value : false
,I/SO_AGENT( 7646): [com.sec.android.soagent.RegisterReceiver(104/onReceive)] Get Accessory List
,D/LockPatternUtilsCache( 1173): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1173): value : false
,D/LockPatternUtilsCache( 1173): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1173): value : false
,D/ConnectivityService(  918): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  918): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/SPPClientService( 7681): [[SystemStateMoniter]] SystemStateMonitorService : noConnect? : false
,I/SA      ( 7698): [OR] onReceive log=[SA = 2.1.0142 V = 21 HWD = 1920X1080 3.0 dpi = 480  SIZE = 2 LOCALE = en_US CSC = DBT MCC = 0 MNC 0 T = user DEVICE = klte P = kltexx I = LRX21T M = SM-G900F OKLEFT false DIS LRX21T.G900FXXU1BOD3 PSS = 5.219788042639568  ]
,I/SA      ( 7698): [OR] onReceive Intent=[ conn.CONNECTIVITY_CHANGE. networkInfo:[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] networkType:1 inetCondition:0 extraInfo:? isDefault:true ]
I/SA      ( 7698): [OR] == ACTION_CONNECTIVITY_CHANGE ==
,I/SA      ( 7698): [TPMU]  strSIMState 	:SIM_STATE_UNKNOWN
,I/SA      ( 7698): [OR] == isSIMCardReady false ==
D/ConnectivityService(  918): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/SA      ( 7698): [SCU] == networkStateCheck == true
,D/LockPatternUtilsCache( 1173): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1173): value : false
,I/SA      ( 7698): [DM] getCountryCodeFromCSC : DE
I/SA      ( 7698): isChinaCountryCode : false
I/SA      ( 7698): [SCU] is ChinestModel Data Restricted   : false
I/SA      ( 7698): [OR] == networkStateCheck true ==
,D/ConnectivityService(  918): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/LockPatternUtilsCache( 1173): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1173): value : false
,I/SA      ( 7698): [OR] GetMyCountryZoneTask
,I/SA      ( 7698): [OR] onReceive END
,I/SA      ( 7698): [SRS] prepareGetMyCountryZone
,I/SA      ( 7698): [TPMU]  strSIMState 	:SIM_STATE_UNKNOWN
,I/SA      ( 7698): [SSP] query invoked
,D/ConnectivityService(  918): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/LockPatternUtilsCache( 1173): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1173): value : false
,I/SA      ( 7698): [TPMU] GetMccFromDB : null
I/SA      ( 7698): [SCU] getMccFromPreferece mcc = 260
I/SA      ( 7698): [TPM] isNoProxy(default) : true
,D/accuweather( 7264): [KK AccuPhone]>>> WC:30 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,D/accuweather( 7264): [KK AccuPhone]>>> UIMEM:106 [0:0] The widget does not exist in idle!!
,D/LockPatternUtilsCache( 1173): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1173): value : false
,I/KnoxUsageLogPro( 7719): KnoxUsageReceiver onReceive :android.net.conn.CONNECTIVITY_CHANGE myUserId=0
I/KnoxUsageLogPro( 7719): premStatus:2
,I/KnoxUsageLogPro( 7719): isEulaShown : false
I/KnoxUsageLogPro( 7719): KnoxUsageReceiver onReceive : not Processible, just return
,E/WifiStateMachine(  918): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: [192.168.1.135/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576} new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.135/24,fe80::ee1f:72ff:fe18:8b78/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0}
E/WifiStateMachine(  918): updateLinkProperties nid: 0 state: CONNECTED reason: CMD_UPDATE_LINKPROPERTIES v4 v4r v4dns isprov
,D/ConnectivityService(  918): Update of LinkProperties for NetworkAgentInfo [WIFI () - 503]; created=true
,D/ConnectivityService(  918): updateLinkProperties: newLp = {InterfaceName: wlan0 LinkAddresses: [192.168.1.135/24,fe80::ee1f:72ff:fe18:8b78/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}
D/ConnectivityService(  918): identical MTU - not setting
D/ConnectivityService(  918): updateSourceRoutes : add source routing for type : 1
D/ConnectivityService(  918): updateSourceRoutes : add src route for:fe80::ee1f:72ff:fe18:8b78
,V/        (  274): QcRouteController
,D/LockPatternUtilsCache( 1173): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1173): value : false
,E/File    ( 7698): fail readDirectory() errno=2
,D/SmartBondingService(  918): SmartBondingReceiver: onReceive action=android.net.wifi.LINK_CONFIGURATION_CHANGED
D/ConnectivityService(  918): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SmartBondingService(  918): EVENT_UPDATE_SB_STATE called / mDisableBySIOP false
D/SmartBondingService(  918): getSBEnabled() enabled =false
D/SmartBondingService(  918): getSBEnabled() enabled =false
D/SmartBondingService(  918): getSBEnabled() enabled =false
,D/Headlines( 5454): HeadlinesSystemBroadcastReceiver onReceive android.net.conn.CONNECTIVITY_CHANGE
,D/HeadlinesChannelUtil( 5454): getCountryCode(): countryCode = DE
,D/Headlines( 5454): Breath.onStartCommand : com.samsung.android.internal.headlines.UPDATE_WELCOME_CARD flag : 0
,D/HeadlinesCardManager( 5454): updateCategory : HeadlinesCardManager:updateCategory() category size == 0
D/HeadlinesCardManager( 5454): updateCategory : HeadlinesCardManager:updateCategory() try to query category list
D/Headlines( 5454): queryCategory.  mRequest is not initialized.
D/HeadlinesCardManager( 5454): updateCategory : HeadlinesCardManager:updateCategory() reponse : false
D/HeadlinesCardManager( 5454): requestUpdateNewsWelcomeCard : request update welcome card to content card.
,V/        (  274): QcRouteController
D/HeadlinesDataCenter( 5454): requestUpdateNewsWelcomeCard !!! no welcome card
,E/LightSensor(  918): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  918): mCallbacks.updateBrightness()
D/DisplayPowerController(  918): getFinalBrightness : 8 -> 8
D/ConnectivityService(  918): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,W/NetworkManagementService(  918): route cmd failed: 
W/NetworkManagementService(  918): com.android.server.NativeDaemonConnector$NativeDaemonFailureException: command '72 route replace src v6 wlan0 fe80::ee1f:72ff:fe18:8b78 2 ::' failed with '400 72 -6 route replace default via :: dev wlan0 scope global table 2: RTNETLINK answers: Invalid argument
W/NetworkManagementService(  918): '
W/NetworkManagementService(  918): 	at com.android.server.NativeDaemonConnector.execute(NativeDaemonConnector.java:438)
W/NetworkManagementService(  918): 	at com.android.server.NativeDaemonConnector.executeForList(NativeDaemonConnector.java:371)
W/NetworkManagementService(  918): 	at com.android.server.NativeDaemonConnector.execute(NativeDaemonConnector.java:336)
W/NetworkManagementService(  918): 	at com.android.server.NativeDaemonConnector.execute(NativeDaemonConnector.java:321)
W/NetworkManagementService(  918): 	at com.android.server.NetworkManagementService.replaceSrcRoute(NetworkManagementService.java:2812)
W/NetworkManagementService(  918): 	at com.android.server.ConnectivityService.updateSourceRoutes(ConnectivityService.java:5478)
W/NetworkManagementService(  918): 	at com.android.server.ConnectivityService.updateLinkProperties(ConnectivityService.java:5305)
W/NetworkManagementService(  918): 	at com.android.server.ConnectivityService.access$1800(ConnectivityService.java:230)
W/NetworkManagementService(  918): 	at com.android.server.ConnectivityService$NetworkStateTrackerHandler.handleMessage(ConnectivityService.java:2324)
W/NetworkManagementService(  918): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/NetworkManagementService(  918): 	at android.os.Looper.loop(Looper.java:145)
W/NetworkManagementService(  918): 	at android.os.HandlerThread.run(HandlerThread.java:61)
D/Nat464Xlat(  918): requiresClat: netType=1, connected=true, hasIPv4Address=true
D/ConnectivityService(  918): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 503]
D/ConnectivityService(  918): calling update connectivity
D/ConnectivityService(  918):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  918):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  918): sending notification IP_CHANGED for NetworkRequest [ id=2, legacyType=-1, [] ]
,D/ConnectivityService(  918): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 503]
,D/ConnectivityService(  918): calling update connectivity
D/ConnectivityService(  918):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,D/ConnectivityService(  918):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityManager.CallbackHandler( 1173): CM callback handler got msg 524295
D/LockPatternUtilsCache( 1173): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1173): value : false
,D/ConnectivityService(  918): sending notification IP_CHANGED for NetworkRequest [ id=2, legacyType=-1, [] ]
,D/ConnectivityManager.CallbackHandler( 1173): CM callback handler got msg 524295
,D/ConnectivityService(  918): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  918): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/QuickConnect( 7833): PeriphStartReceiver.onReceive - android.net.conn.CONNECTIVITY_CHANGE
,I/QuickConnect( 7833): PeriphStartReceiver.onReceive - USER_OWNER care CONNECTIVITY_ACTION. run P service
I/QuickConnect( 7833): PeriphStartReceiver.onReceive - no need to start
,D/LockPatternUtilsCache( 1173): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1173): value : false
,D/ConnectivityService(  918): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  918): returning getNetworkInfo(networkType - 0) :[type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/RCPManagerService(  918): exchangeData() failure , invalid userId
,D/RCPManagerService(  918): exchangeData() failure , invalid userId
,D/ConnectivityService(  918): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SecurityLogAgent( 7477): KnoxConfiguration : Current State = 1
D/SecurityLogAgent( 7477): KnoxConfiguration : Current State Mapping Found 
D/SecurityLogAgent( 7477): StateMachine : Current State = 1
,D/ConnectivityService(  918): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/LockPatternUtilsCache( 1173): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1173): value : false
,D/SecurityLogAgent( 7477): StateMachine : Changed Current State = 1
,D/com.peel.receiver.ConnectivityActionReceiver( 5557): ConnectivityActionReceiver onReceive
D/com.peel.receiver.ConnectivityActionReceiver( 5557): 
D/com.peel.receiver.ConnectivityActionReceiver( 5557): 
D/com.peel.receiver.ConnectivityActionReceiver( 5557): country_code: Germany -- rom region: GB
D/com.peel.receiver.ConnectivityActionReceiver( 5557): 
,D/ConnectivityService(  918): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  918): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/com.peel.receiver.ConnectivityActionReceiver( 5557): 
D/com.peel.receiver.ConnectivityActionReceiver( 5557): 
D/com.peel.receiver.ConnectivityActionReceiver( 5557):  network type WIFI path... network offline: false
D/com.peel.receiver.ConnectivityActionReceiver( 5557): 
D/com.peel.receiver.ConnectivityActionReceiver( 5557): has active network... run services...
D/com.peel.receiver.ConnectivityActionReceiver( 5557): 
D/com.peel.receiver.ConnectivityActionReceiver( 5557): 
D/com.peel.receiver.ConnectivityActionReceiver( 5557): last run: 1450652956514 -- System.currentTimeMillis()-last_run: 5008909
D/com.peel.receiver.ConnectivityActionReceiver( 5557): ... skip 
D/com.peel.receiver.ConnectivityActionReceiver( 5557): ... skip last_72_check
,D/LockPatternUtilsCache( 1173): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1173): value : false
,D/ConnectivityService(  918): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  918): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  918): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/LockPatternUtilsCache( 1173): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1173): value : false
,D/ConnectivityService(  918): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  918): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/LockPatternUtilsCache( 1173): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1173): value : false
,D/ConnectivityService(  918): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ChimeraCfgMgr( 2454): Loading module com.google.android.gms.kids from APK com.google.android.gms
,D/ConnectivityService(  918): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/LockPatternUtilsCache( 1173): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1173): value : false
,D/ConnectivityService(  918): NetTransition Wakelock (NetworkAgentInfo [WIFI () - 502] cleared because we found a replacement network
,D/ConnectivityService(  918): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/hcjo    ( 7097): AutoUpdateManager:IDLE:execute
,D/InitializeManagerStateMachine( 7097): execute::IDLE:EXECUTE
,D/InitializeManagerStateMachine( 7097): exit::IDLE
D/InitializeManagerStateMachine( 7097): entry::NETWORK_CHECK
D/ConnectivityService(  918): returning getNetworkInfo(networkType - 0) :[type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  918): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/InitializeManagerStateMachine( 7097): execute::NETWORK_CHECK:NETWORK_STATE_OK
D/InitializeManagerStateMachine( 7097): exit::NETWORK_CHECK
D/InitializeManagerStateMachine( 7097): entry::CHECK_COUNTRY_INFO
D/InitializeManagerStateMachine( 7097): execute::CHECK_COUNTRY_INFO:COUNTRY_INFO_OK
D/InitializeManagerStateMachine( 7097): exit::CHECK_COUNTRY_INFO
D/InitializeManagerStateMachine( 7097): entry::SUCCESS
D/hcjo    ( 7097): AutoUpdateManager:INITCHECK:onInitializeSuccess
D/ChimeraCfgMgr( 2454): Loading module com.google.android.gms.kids from APK com.google.android.gms
,D/hcjo    ( 7097): AutoUpdateTriggerManager:IDLE:notifyNextTime
D/hcjo    ( 7097): AutoUpdateManager:UPD_CHECK_TIMING:onNoUpdateTime
,D/ConnectivityService(  918): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/InitializeManagerStateMachine( 7097): exit::SUCCESS
,D/InitializeManagerStateMachine( 7097): entry::IDLE
,D/LockPatternUtilsCache( 1173): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1173): value : false
,D/ConnectivityService(  918): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/LockPatternUtilsCache( 1173): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1173): value : false
,I/GLSUser ( 1739): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: ac2dm
,I/GLSUser ( 1739): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> ac2dm without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1739): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1739): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1739): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/LockPatternUtilsCache( 1173): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1173): value : false
V/BitmapFactory( 1739): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  918): uri = 14 selection = getSealedState
,D/SecContentProvider2(  918): mCursor = null
D/SecContentProvider2(  918): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  918): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
V/ApplicationPolicy(  918): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,W/Kids    ( 2454): [AccountUtils] Account not ready
W/Kids    ( 2454): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/Kids    ( 2454): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/Kids    ( 2454): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/Kids    ( 2454): 	at com.google.android.gms.auth.p.c(SourceFile:550)
W/Kids    ( 2454): 	at com.google.android.gms.auth.p.b(SourceFile:477)
W/Kids    ( 2454): 	at com.google.android.gms.kids.account.k.d(SourceFile:103)
W/Kids    ( 2454): 	at com.google.android.gms.kids.account.p.a(SourceFile:70)
W/Kids    ( 2454): 	at com.google.android.gms.kids.account.t.a(SourceFile:62)
W/Kids    ( 2454): 	at com.google.android.gms.chimera.f.run(SourceFile:179)
W/Kids    ( 2454): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
W/Kids    ( 2454): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
W/Kids    ( 2454): 	at java.lang.Thread.run(Thread.java:818)
,D/StatusBar( 1173): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,I/PhoneStatusBar( 1173): Icon Only
D/LockPatternUtilsCache( 1173): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1173): value : false
D/PanelView( 1173): There is/are notification(s) 
,D/PanelView( 1173): There is/are notification(s) 
,D/LockPatternUtilsCache( 1173): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1173): value : false
,E/LightSensor(  918): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  918): mCallbacks.updateBrightness()
D/DisplayPowerController(  918): getFinalBrightness : 8 -> 8
,D/LockPatternUtilsCache( 1173): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1173): value : false
,D/LockPatternUtilsCache( 1173): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1173): value : false
,D/LockPatternUtilsCache( 1173): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1173): value : false
,D/LockPatternUtilsCache( 1173): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1173): value : false
,I/WifiStateMachine(  918): CMD_RSSI_POLL : calculateWifiScore in!
,I/WifiStateMachine(  918): CMD_RSSI_POLL : calculateWifiScore out!
,I/WifiStateMachine(  918): CMD_RSSI_POLL : out!
,D/StatusBar.NetworkController( 1173): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02012b/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020466/com.android.systemui:drawable/stat_sys_signal_inout mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
,E/SMD     (  280): DCD ON
,D/LockPatternUtilsCache( 1173): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1173): value : false
,D/LockPatternUtilsCache( 1173): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1173): value : false
,D/LockPatternUtilsCache( 1173): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1173): value : false
,D/LockPatternUtilsCache( 1173): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1173): value : false
,D/LockPatternUtilsCache( 1173): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1173): value : false
,D/LockPatternUtilsCache( 1173): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1173): value : false
,D/LockPatternUtilsCache( 1173): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1173): value : false
,D/LockPatternUtilsCache( 1173): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1173): value : false
D/LockPatternUtilsCache( 1173): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1173): value : false
,D/LockPatternUtilsCache( 1173): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1173): value : false
,E/LightSensor(  918): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  918): mCallbacks.updateBrightness()
D/DisplayPowerController(  918): getFinalBrightness : 8 -> 8
,E/Watchdog(  918): !@Sync 3
,I/SA      ( 7698): [RC New] Execute method=[GET] start
,I/SA      ( 7698): [RC New] Security=[true]
,I/System.out( 7698): Thread-1280(ApacheHTTPLog):Reading from variable values from setDefaultValuesToVariables
,I/System.out( 7698): Thread-1280(ApacheHTTPLog):isShipBuild true
,I/System.out( 7698): Thread-1280(ApacheHTTPLog):SmartBonding Enabling is true, SHIP_BUILD is true, log to file is false, DBG is false
,E/LightSensor(  918): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
D/AutomaticBrightnessController(  918): mCallbacks.updateBrightness()
D/DisplayPowerController(  918): getFinalBrightness : 8 -> 8
,I/ActivityManager(  918): Killing 6989:com.samsung.android.app.watchmanagerstub/u0a112 (adj 15): bgCount ##41
,W/libprocessgroup(  918): failed to open /acct/uid_10112/pid_6989/cgroup.procs: No such file or directory
,E/LightSensor(  918): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  918): mCallbacks.updateBrightness()
D/DisplayPowerController(  918): getFinalBrightness : 8 -> 8
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7416): setDiscoveryMode: Mode set to BLE
,I/jxcore-log( 7416): BLE supported!!
I/jxcore-log( 7416): 
E/LightSensor(  918): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  918): mCallbacks.updateBrightness()
D/DisplayPowerController(  918): getFinalBrightness : 8 -> 8
,E/LightSensor(  918): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
D/AutomaticBrightnessController(  918): mCallbacks.updateBrightness()
D/DisplayPowerController(  918): getFinalBrightness : 8 -> 8
,E/LightSensor(  918): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
D/AutomaticBrightnessController(  918): mCallbacks.updateBrightness()
D/DisplayPowerController(  918): getFinalBrightness : 8 -> 8
,I/SA      ( 7698): [RC New] [v2liruge] api execute + 903
,I/SA      ( 7698): [RC New] executeRequest [v2liruge] httpResponse : HTTP/1.1 200 OK
,I/System.out( 7698): AsyncTask #1 calls detatch()
,E/LightSensor(  918): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  918): mCallbacks.updateBrightness()
D/DisplayPowerController(  918): getFinalBrightness : 8 -> 8
V/AlarmManager(  918): waitForAlarm result :4
,I/SA      ( 7698): [ODM] saveOpenData( GEO_IP, PL )
,D/ConnectivityService(  918): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/SA      ( 7698): [OCP] update openData : PL
,I/SA      ( 7698): [TPMU] getNetworkMcc : 
,I/SA      ( 7698): [SCU] saveMccToPreferece Start
,I/SA      ( 7698): [SCU] RegionMCC : 260
I/SA      ( 7698): [SSP] query invoked
,I/SA      ( 7698): [TPMU] GetMccFromDB : null
,I/SA      ( 7698): [SCU] getMccFromPreferece mcc = 260
I/SA      ( 7698): [SCU] saveMccToPreferece End
,I/SA      ( 7698): [RC New] executeRequest [v2liruge] end. 1012
,I/SA      ( 7698): [RC New] Execute end
I/SA      ( 7698): [OR] GetMyCountryZoneTask mcc = 260
I/SA      ( 7698): [OR] GetMyCountryZoneTask Success
,D/BatteryService(  918): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 297, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  918): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
D/BatteryService(  918): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  918):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
I/MotionRecognitionService(  918): Plugged
I/MotionRecognitionService(  918): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1173): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1173): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1173):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1173): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1173): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3229): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3229): Disconnected process message: 10
,D/BatteryMeterView( 1173): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/ConnectivityService(  918): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  918): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  918): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/LightSensor(  918): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  918): mCallbacks.updateBrightness()
,D/DisplayPowerController(  918): getFinalBrightness : 8 -> 8
,I/dhcpcd  ( 7623): wlan0: sending IPv6 Router Solicitation
,D/GCM     ( 1739): Connected
,D/ConnectivityService(  918): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  918): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  918): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/ConnectivityService(  918): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  918): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/GCM     ( 1739): Message class com.google.f.a.a.p
,D/ConnectivityService(  918): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  918): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/LightSensor(  918): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  918): mCallbacks.updateBrightness()
D/DisplayPowerController(  918): getFinalBrightness : 8 -> 8
,V/AlarmManager(  918): waitForAlarm result :8
,D/ConnectivityService(  918): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/GLSUser ( 1739): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.googlequicksearchbox, service: oauth2:https://www.googleapis.com/auth/googlenow
I/GLSUser ( 1739): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/googlenow without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1739): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1739): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1739): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/LightSensor(  918): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/ResourcesManager( 1739): creating new AssetManager and set to /system/priv-app/Velvet/Velvet.apk
D/AutomaticBrightnessController(  918): mCallbacks.updateBrightness()
D/DisplayPowerController(  918): getFinalBrightness : 8 -> 8
,V/BitmapFactory( 1739): DecodeImagePath(decodeResourceStream3) : res/mipmap-xxhdpi-v4/ic_launcher_google_search.png
,V/BitmapFactory( 1739): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  918): uri = 14 selection = getSealedState
,D/SecContentProvider2(  918): mCursor = null
D/SecContentProvider2(  918): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  918): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy(  918): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/StatusBar( 1173): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,I/PhoneStatusBar( 1173): Icon Only
,D/LockPatternUtilsCache( 1173): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1173): value : false
D/PanelView( 1173): There is/are notification(s) 
,D/PanelView( 1173): There is/are notification(s) 
,W/Search.LoginHelper( 1587): User recoverable exception for scope: oauth2:https://www.googleapis.com/auth/googlenow
,D/WearableService( 4711): callingUid 10012, callindPid: 4711
,D/ResourcesManager( 7528): creating new AssetManager and set to /data/app/com.google.android.gms-1/base.apk
,W/ResourcesManager( 7528): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 7528): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,I/GHttpClientFactory( 7528): Using the GMSCore's GoogleHttpClient
,D/WearableClient( 7528): WearableClientImpl.onPostInitHandler: done
,D/WearableClient( 7528): WearableClientImpl.onPostInitHandler: done
,D/WearableClient( 7528): WearableClientImpl.onPostInitHandler: done
,E/GmsUtils( 7528): Failed to connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
,D/WearableClient( 7528): WearableClientImpl.onPostInitHandler: done
,E/GmsUtils( 7528): Failed to connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
,E/LightSensor(  918): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  918): mCallbacks.updateBrightness()
D/DisplayPowerController(  918): getFinalBrightness : 8 -> 8
,I/MusicLeanback( 7528): Conditions not met for autocaching.
I/MusicLeanback( 7528): Stop autocaching.
,E/ActivityThread( 7528): Service com.google.android.music.download.TrackDownloadQueueService has leaked ServiceConnection com.google.android.gms.http.GoogleURLConnectionFactory$1@37231c37 that was originally bound here
E/ActivityThread( 7528): android.app.ServiceConnectionLeaked: Service com.google.android.music.download.TrackDownloadQueueService has leaked ServiceConnection com.google.android.gms.http.GoogleURLConnectionFactory$1@37231c37 that was originally bound here
E/ActivityThread( 7528): 	at android.app.LoadedApk$ServiceDispatcher.<init>(LoadedApk.java:1134)
E/ActivityThread( 7528): 	at android.app.LoadedApk.getServiceDispatcher(LoadedApk.java:1028)
E/ActivityThread( 7528): 	at android.app.ContextImpl.bindServiceCommon(ContextImpl.java:2085)
E/ActivityThread( 7528): 	at android.app.ContextImpl.bindService(ContextImpl.java:2068)
E/ActivityThread( 7528): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:559)
E/ActivityThread( 7528): 	at com.google.android.gms.http.GoogleURLConnectionFactory.<init>(Unknown Source)
E/ActivityThread( 7528): 	at com.google.android.gms.http.GoogleHttpClient.<init>(Unknown Source)
E/ActivityThread( 7528): 	at com.google.android.gms.http.GoogleHttpClient.<init>(Unknown Source)
E/ActivityThread( 7528): 	at com.google.android.gms.http.GoogleHttpClient.<init>(Unknown Source)
E/ActivityThread( 7528): 	at com.google.android.music.GoogleHttpClientFactory.createGoogleHttpClient(GoogleHttpClientFactory.java:81)
E/ActivityThread( 7528): 	at com.google.android.music.cloudclient.MusicRequest.createHttpClient(MusicRequest.java:110)
E/ActivityThread( 7528): 	at com.google.android.music.cloudclient.MusicRequest.getSharedHttpClient(MusicRequest.java:100)
E/ActivityThread( 7528): 	at com.google.android.music.download.BaseDownloadQueueManager.<init>(BaseDownloadQueueManager.java:110)
E/ActivityThread( 7528): 	at com.google.android.music.download.TrackDownloadQueueManager.<init>(TrackDownloadQueueManager.java:10)
E/ActivityThread( 7528): 	at com.google.android.music.download.TrackDownloadQueueService.onCreate(TrackDownloadQueueService.java:25)
E/ActivityThread( 7528): 	at android.app.ActivityThread.handleCreateService(ActivityThread.java:3100)
E/ActivityThread( 7528): 	at android.app.ActivityThread.access$1900(ActivityThread.java:172)
E/ActivityThread( 7528): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1505)
E/ActivityThread( 7528): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/ActivityThread( 7528): 	at android.os.Looper.loop(Looper.java:145)
E/ActivityThread( 7528): 	at android.app.ActivityThread.main(ActivityThread.java:5832)
E/ActivityThread( 7528): 	at java.lang.reflect.Method.invoke(Native Method)
E/ActivityThread( 7528): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/ActivityThread( 7528): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
E/ActivityThread( 7528): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
,I/WifiStateMachine(  918): REQUEST_POWER_SAVE_ON
,E/LightSensor(  918): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
D/AutomaticBrightnessController(  918): mCallbacks.updateBrightness()
D/DisplayPowerController(  918): getFinalBrightness : 8 -> 8
,E/WifiStateMachine(  918): CAPTIVE_PORTAL_EVENT_AUTHENTICATED
,E/LightSensor(  918): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  918): mCallbacks.updateBrightness()
,D/DisplayPowerController(  918): getFinalBrightness : 8 -> 8
,E/LightSensor(  918): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  918): mCallbacks.updateBrightness()
,D/DisplayPowerController(  918): getFinalBrightness : 8 -> 8
,E/LightSensor(  918): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  918): mCallbacks.updateBrightness()
,D/DisplayPowerController(  918): getFinalBrightness : 8 -> 8
,D/ConnectivityService(  918): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/LightSensor(  918): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  918): mCallbacks.updateBrightness()
D/DisplayPowerController(  918): getFinalBrightness : 8 -> 8
,D/PowerManagerService(  918): [s] UserActivityState : 2 -> 4
I/PowerManagerService(  918): [PWL] On : 76432 (30000 ms ago)
I/PowerManagerService(  918): [PWL]  mStayOn: false  mWakeLockSummary & WAKE_LOCK_STAY_AWAKE: 20  mUserActivitySummary: 0x4
I/PowerManagerService(  918): [PWL]  SCREEN_BRIGHT_WAKE_LOCK        'WindowManager' ON_AFTER_RELEASE (uid=1000, pid=918, ws=WorkSource{10059}) (elapsedTime=3302)
,D/ConnectivityService(  918): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/LightSensor(  918): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  918): mCallbacks.updateBrightness()
,D/DisplayPowerController(  918): getFinalBrightness : 8 -> 8
,E/SMD     (  280): DCD ON
,D/LockPatternUtilsCache( 1173): getCarrierLockPlusMode(),
D/LockPatternUtilsCache( 1173): value : false
,I/WifiStateMachine(  918): CMD_RSSI_POLL : calculateWifiScore in!
,I/WifiStateMachine(  918): CMD_RSSI_POLL : calculateWifiScore out!
,D/LockPatternUtilsCache( 1173): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1173): value : false
,I/WifiStateMachine(  918): CMD_RSSI_POLL : out!
,D/PowerManagerService(  918): [api] [s] userActivity : event: 0 flags: 0 (uid: 1000 pid: 918) eventTime = 106618
,D/PowerManagerService(  918): [s] UserActivityState : 4 -> 1
,D/PowerManagerService(  918): [api] release WakeLock flags=0x2000000a tag=WindowManager uid=1000 pid=918 (0x0)
D/PowerManagerService(  918): [api] applyWakeLockFlagsOnReleaseLocked : userActivityNoUpdateLocked is called : SCREEN_BRIGHT_WAKE_LOCK        'WindowManager' ON_AFTER_RELEASE (uid=1000, pid=918, ws=WorkSource{10059}) (elapsedTime=3489)
,D/LockPatternUtilsCache( 1173): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1173): value : false
,D/LockPatternUtilsCache( 1173): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1173): value : false
,D/LockPatternUtilsCache( 1173): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1173): value : false
,D/LockPatternUtilsCache( 1173): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1173): value : false
,D/LockPatternUtilsCache( 1173): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1173): value : false
,D/LockPatternUtilsCache( 1173): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1173): value : false
,D/LockPatternUtilsCache( 1173): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1173): value : false
,D/LockPatternUtilsCache( 1173): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1173): value : false
,E/LightSensor(  918): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  918): mCallbacks.updateBrightness()
,D/DisplayPowerController(  918): getFinalBrightness : 8 -> 8
,D/LockPatternUtilsCache( 1173): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1173): value : false
,D/LockPatternUtilsCache( 1173): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1173): value : false
,D/LockPatternUtilsCache( 1173): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1173): value : false
,D/LockPatternUtilsCache( 1173): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1173): value : false
,D/LockPatternUtilsCache( 1173): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1173): value : false
,D/LockPatternUtilsCache( 1173): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1173): value : false
,D/LockPatternUtilsCache( 1173): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1173): value : false
,D/LockPatternUtilsCache( 1173): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1173): value : false
,D/LockPatternUtilsCache( 1173): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1173): value : false
,D/LockPatternUtilsCache( 1173): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1173): value : false
,E/LightSensor(  918): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  918): mCallbacks.updateBrightness()
,D/DisplayPowerController(  918): getFinalBrightness : 8 -> 8
,D/LockPatternUtilsCache( 1173): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1173): value : false
,I/GAV4    ( 7753): Thread[GAThread,5,main]: No campaign data found.
,D/LockPatternUtilsCache( 1173): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1173): value : false
,D/LockPatternUtilsCache( 1173): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1173): value : false
,D/LockPatternUtilsCache( 1173): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1173): value : false
,D/LockPatternUtilsCache( 1173): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1173): value : false
,D/LockPatternUtilsCache( 1173): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1173): value : false
,D/LockPatternUtilsCache( 1173): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1173): value : false
,D/LockPatternUtilsCache( 1173): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1173): value : false
,D/LockPatternUtilsCache( 1173): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1173): value : false
,D/LockPatternUtilsCache( 1173): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1173): value : false
,E/LightSensor(  918): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
D/LockPatternUtilsCache( 1173): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1173): value : false
,D/AutomaticBrightnessController(  918): mCallbacks.updateBrightness()
D/DisplayPowerController(  918): getFinalBrightness : 8 -> 8
,D/LockPatternUtilsCache( 1173): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1173): value : false
,D/LockPatternUtilsCache( 1173): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1173): value : false
,D/LockPatternUtilsCache( 1173): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1173): value : false
D/LockPatternUtilsCache( 1173): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1173): value : false
,I/SurfaceFlinger(  249): id=16 Removed Toast (8/8)
,D/LockPatternUtilsCache( 1173): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1173): value : false
,D/LockPatternUtilsCache( 1173): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1173): value : false
,D/LockPatternUtilsCache( 1173): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1173): value : false
,D/SSRM:m  (  918): SIOP:: AP = 410, PST = 433, CUR = 300
,E/LightSensor(  918): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  918): mCallbacks.updateBrightness()
D/DisplayPowerController(  918): getFinalBrightness : 8 -> 8
,E/LightSensor(  918): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  918): mCallbacks.updateBrightness()
,D/DisplayPowerController(  918): getFinalBrightness : 8 -> 8
,E/LightSensor(  918): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  918): mCallbacks.updateBrightness()
,D/DisplayPowerController(  918): getFinalBrightness : 8 -> 8
,E/LightSensor(  918): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  918): mCallbacks.updateBrightness()
,D/DisplayPowerController(  918): getFinalBrightness : 8 -> 8
,I/Atfwd_Sendcmd(  323): AtCmdFwd service not ready - Exhausted retry attempts - :6
,I/Atfwd_Daemon(  323): result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,E/LightSensor(  918): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  918): mCallbacks.updateBrightness()
D/DisplayPowerController(  918): getFinalBrightness : 8 -> 8
,I/PCWCLIENTTRACE_SYSTEMReceiver( 6728): mConnectivityHandler : connected
,D/ConnectivityService(  918): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,W/PCWCLIENTTRACE_AccountUtil( 6728): [hasSamungAccount] - No Samsung Account
,E/LightSensor(  918): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  918): mCallbacks.updateBrightness()
D/DisplayPowerController(  918): getFinalBrightness : 8 -> 8
,I/CSTORAGE( 6728): ================================================
I/CSTORAGE( 6728):  CSTORAGE_SKM_LIB, v1.0.22, MSM8974|MSM8x26|MSM8x10
I/CSTORAGE( 6728): ================================================
I/PCWCLIENTTRACE_SecurePreferencesJNI( 6728): [GetString-S]
E/art     ( 6728): No implementation found for java.lang.String com.sec.pcw.device.util.SecurePreferencesJNI.getString() (tried Java_com_sec_pcw_device_util_SecurePreferencesJNI_getString and Java_com_sec_pcw_device_util_SecurePreferencesJNI_getString__)
W/PCWCLIENTTRACE_SecurePreferencesJNI( 6728): GetString : secure API is not supported!! No implementation found for java.lang.String com.sec.pcw.device.util.SecurePreferencesJNI.getString() (tried Java_com_sec_pcw_device_util_SecurePreferencesJNI_getString and Java_com_sec_pcw_device_util_SecurePreferencesJNI_getString__)
I/PCWCLIENTTRACE_SecurePreferencesJNI( 6728): [GetString-E]
,I/PCWCLIENTTRACE_PushUtil( 6728): SPPPushClient is installed : true
,I/PCWCLIENTTRACE_PushUtil( 6728): sales region : global
I/PCWCLIENTTRACE_PushUtil( 6728): getPushTypeList : [SPP, GCM]
E/PCWCLIENTTRACE_PCWHandler( 6728): [ensureRegistration] - No Samsung account
,D/StatusBar.NetworkController( 1173): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02012b/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020464/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
D/StatusBar.NetworkController( 1173): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1173): applyOpen
,E/LightSensor(  918): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  918): mCallbacks.updateBrightness()
,D/DisplayPowerController(  918): getFinalBrightness : 8 -> 8
,D/StatusBar.NetworkController( 1173): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1173): applyOpen
,D/StatusBar.NetworkController( 1173): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1173): applyOpen
D/StatusBar.NetworkController( 1173): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1173): applyOpen
,E/LightSensor(  918): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  918): mCallbacks.updateBrightness()
,D/DisplayPowerController(  918): getFinalBrightness : 8 -> 8
,E/LightSensor(  918): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  918): mCallbacks.updateBrightness()
,D/DisplayPowerController(  918): getFinalBrightness : 8 -> 8
,E/LightSensor(  918): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  918): mCallbacks.updateBrightness()
,D/DisplayPowerController(  918): getFinalBrightness : 8 -> 8
,E/LightSensor(  918): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  918): mCallbacks.updateBrightness()
,D/DisplayPowerController(  918): getFinalBrightness : 8 -> 8
,I/dhcpcd  ( 7623): wlan0: sending IPv6 Router Solicitation
,E/LightSensor(  918): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  918): mCallbacks.updateBrightness()
,D/DisplayPowerController(  918): getFinalBrightness : 8 -> 8
,D/StatusBar.NetworkController( 1173): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02012b/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020466/com.android.systemui:drawable/stat_sys_signal_inout mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
D/StatusBar.NetworkController( 1173): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1173): applyOpen
,D/StatusBar.NetworkController( 1173): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1173): applyOpen
D/StatusBar.NetworkController( 1173): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1173): applyOpen
,D/StatusBar.NetworkController( 1173): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1173): applyOpen
,E/LightSensor(  918): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  918): mCallbacks.updateBrightness()
,D/DisplayPowerController(  918): getFinalBrightness : 8 -> 8
,E/SMD     (  280): DCD ON
,E/LightSensor(  918): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  918): mCallbacks.updateBrightness()
,D/DisplayPowerController(  918): getFinalBrightness : 8 -> 8
,I/WifiStateMachine(  918): CMD_RSSI_POLL : calculateWifiScore in!
,I/WifiStateMachine(  918): CMD_RSSI_POLL : calculateWifiScore out!
I/WifiStateMachine(  918): CMD_RSSI_POLL : out!
,E/LightSensor(  918): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  918): mCallbacks.updateBrightness()
D/DisplayPowerController(  918): getFinalBrightness : 8 -> 8
,E/LightSensor(  918): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  918): mCallbacks.updateBrightness()
D/DisplayPowerController(  918): getFinalBrightness : 8 -> 8
,E/LightSensor(  918): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  918): mCallbacks.updateBrightness()
,D/DisplayPowerController(  918): getFinalBrightness : 8 -> 8
,E/LightSensor(  918): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  918): mCallbacks.updateBrightness()
,D/DisplayPowerController(  918): getFinalBrightness : 8 -> 8
,D/StatusBar.NetworkController( 1173): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02012b/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020464/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
,D/StatusBar.NetworkController( 1173): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1173): applyOpen
,D/StatusBar.NetworkController( 1173): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1173): applyOpen
D/StatusBar.NetworkController( 1173): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1173): applyOpen
,D/StatusBar.NetworkController( 1173): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1173): applyOpen
,E/LightSensor(  918): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  918): mCallbacks.updateBrightness()
,D/DisplayPowerController(  918): getFinalBrightness : 8 -> 8
,E/LightSensor(  918): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  918): mCallbacks.updateBrightness()
,D/DisplayPowerController(  918): getFinalBrightness : 8 -> 8
,E/LightSensor(  918): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  918): mCallbacks.updateBrightness()
,D/DisplayPowerController(  918): getFinalBrightness : 8 -> 8
,E/LightSensor(  918): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  918): mCallbacks.updateBrightness()
,D/DisplayPowerController(  918): getFinalBrightness : 8 -> 8
,E/LightSensor(  918): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  918): mCallbacks.updateBrightness()
,D/DisplayPowerController(  918): getFinalBrightness : 8 -> 8
,E/LightSensor(  918): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  918): mCallbacks.updateBrightness()
D/DisplayPowerController(  918): getFinalBrightness : 8 -> 8
,E/LightSensor(  918): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  918): mCallbacks.updateBrightness()
,D/DisplayPowerController(  918): getFinalBrightness : 8 -> 8
,E/LightSensor(  918): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  918): mCallbacks.updateBrightness()
,D/DisplayPowerController(  918): getFinalBrightness : 8 -> 8
,E/LightSensor(  918): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  918): mCallbacks.updateBrightness()
,D/DisplayPowerController(  918): getFinalBrightness : 8 -> 8
,E/LightSensor(  918): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  918): mCallbacks.updateBrightness()
,D/DisplayPowerController(  918): getFinalBrightness : 8 -> 8
,E/LightSensor(  918): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  918): mCallbacks.updateBrightness()
,D/DisplayPowerController(  918): getFinalBrightness : 8 -> 8
,W/ContextImpl(  918): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/LightSensor(  918): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  918): mCallbacks.updateBrightness()
,D/DisplayPowerController(  918): getFinalBrightness : 8 -> 8
,E/SMD     (  280): DCD ON
,I/WifiStateMachine(  918): CMD_RSSI_POLL : calculateWifiScore in!
,I/WifiStateMachine(  918): CMD_RSSI_POLL : calculateWifiScore out!
I/WifiStateMachine(  918): CMD_RSSI_POLL : out!
,E/LightSensor(  918): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  918): mCallbacks.updateBrightness()
,D/DisplayPowerController(  918): getFinalBrightness : 8 -> 8
,I/ServiceManager(  323): Waiting for service AtCmdFwd...
,E/LightSensor(  918): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  918): mCallbacks.updateBrightness()
,D/DisplayPowerController(  918): getFinalBrightness : 8 -> 8
,E/LightSensor(  918): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  918): mCallbacks.updateBrightness()
,D/DisplayPowerController(  918): getFinalBrightness : 8 -> 8
,D/PreloadUpdateManagerStateMachine( 7097): execute::IDLE:EXECUTE
D/PreloadUpdateManagerStateMachine( 7097): exit::IDLE
D/PreloadUpdateManagerStateMachine( 7097): entry::CHECK_TIMEOUT_FOR_UPDATE
,D/hcjo    ( 7097): AutoUpdateTriggerManager:IDLE:setInterval:86400000
,D/hcjo    ( 7097): AutoUpdateTriggerManager:IDLE:notifyNextTime
D/PreloadUpdateManagerStateMachine( 7097): execute::CHECK_TIMEOUT_FOR_UPDATE:NO_TIMED_OUT
,D/PreloadUpdateManagerStateMachine( 7097): exit::CHECK_TIMEOUT_FOR_UPDATE
D/PreloadUpdateManagerStateMachine( 7097): entry::IDLE
,I/dhcpcd  ( 7623): wlan0: sending IPv6 Router Solicitation
,I/dhcpcd  ( 7623): wlan0: no IPv6 Routers available
,E/LightSensor(  918): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  918): mCallbacks.updateBrightness()
D/DisplayPowerController(  918): getFinalBrightness : 8 -> 8
,E/LightSensor(  918): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  918): mCallbacks.updateBrightness()
,D/DisplayPowerController(  918): getFinalBrightness : 8 -> 8
,D/StatusBar.NetworkController( 1173): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02012b/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020466/com.android.systemui:drawable/stat_sys_signal_inout mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
,D/StatusBar.NetworkController( 1173): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1173): applyOpen
,D/StatusBar.NetworkController( 1173): refreshSignalCluster - setNWBoosterIndicators(false),
D/StatusBar.NetworkController( 1173): applyOpen
D/StatusBar.NetworkController( 1173): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1173): applyOpen
D/StatusBar.NetworkController( 1173): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1173): applyOpen
,D/PreloadUpdateManagerStateMachine( 7097): execute::IDLE:EXECUTE
D/PreloadUpdateManagerStateMachine( 7097): exit::IDLE
D/PreloadUpdateManagerStateMachine( 7097): entry::CHECK_TIMEOUT_FOR_UPDATE
,D/hcjo    ( 7097): AutoUpdateTriggerManager:IDLE:notifyNextTime
,D/PreloadUpdateManagerStateMachine( 7097): execute::CHECK_TIMEOUT_FOR_UPDATE:NO_TIMED_OUT
,D/PreloadUpdateManagerStateMachine( 7097): exit::CHECK_TIMEOUT_FOR_UPDATE
D/PreloadUpdateManagerStateMachine( 7097): entry::IDLE
,E/LightSensor(  918): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  918): mCallbacks.updateBrightness()
,D/DisplayPowerController(  918): getFinalBrightness : 8 -> 8
,E/LightSensor(  918): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  918): mCallbacks.updateBrightness()
,D/DisplayPowerController(  918): getFinalBrightness : 8 -> 8
,I/ServiceManager(  323): Waiting for service AtCmdFwd...
,E/LightSensor(  918): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  918): mCallbacks.updateBrightness()
D/DisplayPowerController(  918): getFinalBrightness : 8 -> 8
,E/LightSensor(  918): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  918): mCallbacks.updateBrightness()
,D/DisplayPowerController(  918): getFinalBrightness : 8 -> 8
,E/LightSensor(  918): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  918): mCallbacks.updateBrightness()
,D/DisplayPowerController(  918): getFinalBrightness : 8 -> 8
,D/StatusBar.NetworkController( 1173): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02012b/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020464/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
D/StatusBar.NetworkController( 1173): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1173): applyOpen
,D/StatusBar.NetworkController( 1173): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1173): applyOpen
D/StatusBar.NetworkController( 1173): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1173): applyOpen
D/StatusBar.NetworkController( 1173): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1173): applyOpen
,E/LightSensor(  918): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  918): mCallbacks.updateBrightness()
,D/DisplayPowerController(  918): getFinalBrightness : 8 -> 8
,D/FactoryTest( 6413): Not factory mode
D/FactoryTest( 6413): Not factory mode. isFactoryMode() returend false
,D/MTPRx   ( 6413): DRIVER_TIME_OUT 60s lapsed
,D/MTPRx   ( 6413): still no open session command from host, so toast
,W/ContextImpl( 6413): Calling a method in the system process without a qualified user: android.app.ContextImpl.startActivity:1526 android.content.ContextWrapper.startActivity:337 android.content.ContextWrapper.startActivity:337 com.samsung.android.MtpApplication.MtpReceiver$3.handleMessage:713 android.os.Handler.dispatchMessage:102 
,W/ContextImpl( 6413): Calling a method in the system process without a qualified user: android.app.ContextImpl.startActivity:1538 android.app.ContextImpl.startActivity:1527 android.content.ContextWrapper.startActivity:337 android.content.ContextWrapper.startActivity:337 com.samsung.android.MtpApplication.MtpReceiver$3.handleMessage:713 
,I/Timeline( 6413): Timeline: Activity_launch_request id:com.android.settings time:114595
,E/PersonaManagerService(  918): inState():  stateMachine is null !!
,V/ApplicationPolicy(  918): isApplicationStateBlocked userId 0 pkgname com.android.settings
,I/ActivityManager(  918): START u0 {flg=0x10000000 cmp=com.android.settings/.SettingsReceiverActivity} from uid 1000 on display 0
,D/CustomFrequencyManagerService(  918): acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1958400  uid : 1000  pid : 918  pkgName : ACTIVITY_RESUME_BOOSTER@6
,W/ActivityManager(  918): mDVFSHelper.acquire()
,D/LockPatternUtilsCache( 1173): getCarrierLockPlusMode()
,I/SQLiteSecureOpenHelper( 3537): getWritableDatabase(pwd)
I/SQLiteSecureOpenHelper( 3537): getDatabaseLocked(b,b,pwd)...
D/LockPatternUtilsCache( 1173): value : false
,D/LockPatternUtilsCache( 1173): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1173): value : false
,E/MTPRx   ( 6413): started activity for popup
,E/LightSensor(  918): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  918): mCallbacks.updateBrightness()
D/DisplayPowerController(  918): getFinalBrightness : 8 -> 8
,D/LockPatternUtilsCache( 1173): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1173): value : false
D/LockPatternUtilsCache( 1173): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1173): value : false
,D/ConnectivityService(  918): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/LockPatternUtilsCache( 1173): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1173): value : false
,D/ResourcesManager( 6413): creating new AssetManager and set to /system/priv-app/SecSettings/SecSettings.apk
,W/ResourcesManager( 6413): Asset path '/system/framework/sec_platform_library.jar' does not exist or contains no resources.
,W/ResourcesManager( 6413): Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
W/ResourcesManager( 6413): Asset path '/system/framework/secvisualeffect.jar' does not exist or contains no resources.
W/ResourcesManager( 6413): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 6413): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 6413): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 6413): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,E/SettingsReceiverActivity( 6413): PREF_DONT_ASK_AGAIN : true
,D/LockPatternUtilsCache( 1173): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1173): value : false
D/LockPatternUtilsCache( 1173): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1173): value : false
,D/InputMethodManagerService(  918): windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,E/ActivityManager(  918): Invalid thumbnail dimensions: 576x576
,W/InputMethodManagerService(  918): Window already focused, ignoring focus gain of: com.android.internal.view.IInputMethodClient$Stub$Proxy@1886dc18 attribute=null, token = android.os.BinderProxy@3fa08f95
,I/SQLiteSecureOpenHelper( 3537): getWritableDatabase(pwd)
I/SQLiteSecureOpenHelper( 3537): getDatabaseLocked(b,b,pwd)...
,D/LockPatternUtilsCache( 1173): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1173): value : false
,V/BitmapFactory( 6413): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_015.png
,V/BitmapFactory( 6413): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_000.png
,V/BitmapFactory( 6413): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_015.png
,V/BitmapFactory( 6413): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_000.png
,V/BitmapFactory( 6413): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_000.png
,V/BitmapFactory( 6413): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_001.png
,V/BitmapFactory( 6413): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_002.png
,V/BitmapFactory( 6413): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_003.png
,V/BitmapFactory( 6413): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_004.png
,V/BitmapFactory( 6413): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_005.png
V/BitmapFactory( 6413): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_006.png
,V/BitmapFactory( 6413): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_007.png
,V/BitmapFactory( 6413): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_008.png
,V/BitmapFactory( 6413): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_010.png
,V/BitmapFactory( 6413): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_011.png
,V/BitmapFactory( 6413): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_012.png
,V/BitmapFactory( 6413): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_013.png
,V/BitmapFactory( 6413): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_014.png
,V/BitmapFactory( 6413): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_015.png
,V/BitmapFactory( 6413): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_000.png
,V/BitmapFactory( 6413): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_001.png
,V/BitmapFactory( 6413): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_002.png
,V/BitmapFactory( 6413): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_003.png
,V/BitmapFactory( 6413): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_004.png
,V/BitmapFactory( 6413): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_005.png
,V/BitmapFactory( 6413): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_006.png
,V/BitmapFactory( 6413): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_007.png
,V/BitmapFactory( 6413): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_008.png
,V/BitmapFactory( 6413): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_010.png
,V/BitmapFactory( 6413): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_011.png
,V/BitmapFactory( 6413): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_012.png
,V/BitmapFactory( 6413): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_013.png
,V/BitmapFactory( 6413): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_014.png
,V/BitmapFactory( 6413): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_015.png
,D/SettingsReceiverActivity( 6413): dev.kiessupport is : TRUE
,E/LightSensor(  918): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  918): mCallbacks.updateBrightness()
D/DisplayPowerController(  918): getFinalBrightness : 8 -> 8
,D/Activity( 6413): performCreate Call secproduct feature valuefalse
,D/Activity( 6413): performCreate Call debug elastic valuetrue
,D/LockPatternUtilsCache( 1173): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1173): value : false
D/LockPatternUtilsCache( 1173): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1173): value : false
,D/LockPatternUtilsCache( 1173): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1173): value : false
,D/LockPatternUtilsCache( 1173): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1173): value : false
,D/ActivityManager(  918): post active user change for 0
D/KnoxTimeoutHandler(  918): postActiveUserChange for user 0
,D/KnoxTimeoutHandler(  918): handleActiveUserChange for user 0
,D/LockPatternUtilsCache( 1173): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1173): value : false
D/LockPatternUtilsCache( 1173): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1173): value : false
,I/Timeline( 7416): Timeline: Activity_idle id: android.os.BinderProxy@2f3a4142 time:114859
,I/ServiceManager(  323): Waiting for service AtCmdFwd...
,D/LockPatternUtilsCache( 1173): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1173): value : false
,E/LightSensor(  918): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  918): mCallbacks.updateBrightness()
D/DisplayPowerController(  918): getFinalBrightness : 8 -> 8
,D/ConnectivityService(  918): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/LightSensor(  918): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  918): mCallbacks.updateBrightness()
D/DisplayPowerController(  918): getFinalBrightness : 8 -> 8
,E/LightSensor(  918): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  918): mCallbacks.updateBrightness()
D/DisplayPowerController(  918): getFinalBrightness : 8 -> 8
,E/LightSensor(  918): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  918): mCallbacks.updateBrightness()
D/DisplayPowerController(  918): getFinalBrightness : 8 -> 8
,E/SMD     (  280): DCD ON
,I/WifiStateMachine(  918): CMD_RSSI_POLL : calculateWifiScore in!
,I/WifiStateMachine(  918): CMD_RSSI_POLL : calculateWifiScore out!
I/WifiStateMachine(  918): CMD_RSSI_POLL : out!
,E/LightSensor(  918): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  918): mCallbacks.updateBrightness()
D/DisplayPowerController(  918): getFinalBrightness : 8 -> 8
,I/ServiceManager(  323): Waiting for service AtCmdFwd...
,E/LightSensor(  918): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  918): mCallbacks.updateBrightness()
D/DisplayPowerController(  918): getFinalBrightness : 8 -> 8
,E/LightSensor(  918): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  918): mCallbacks.updateBrightness()
D/DisplayPowerController(  918): getFinalBrightness : 8 -> 8
,E/LightSensor(  918): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  918): mCallbacks.updateBrightness()
D/DisplayPowerController(  918): getFinalBrightness : 8 -> 8
,E/LightSensor(  918): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  918): mCallbacks.updateBrightness()
D/DisplayPowerController(  918): getFinalBrightness : 8 -> 8
,E/LightSensor(  918): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  918): mCallbacks.updateBrightness()
D/DisplayPowerController(  918): getFinalBrightness : 8 -> 8
,E/LightSensor(  918): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  918): mCallbacks.updateBrightness()
D/DisplayPowerController(  918): getFinalBrightness : 8 -> 8
,I/ServiceManager(  323): Waiting for service AtCmdFwd...
,E/LightSensor(  918): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  918): mCallbacks.updateBrightness()
D/DisplayPowerController(  918): getFinalBrightness : 8 -> 8
,E/LightSensor(  918): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  918): mCallbacks.updateBrightness()
D/DisplayPowerController(  918): getFinalBrightness : 8 -> 8
,D/SSRM:m  (  918): SIOP:: AP = 370, PST = 423, CUR = 300
,D/X       (  918): broadcastSiopLevelIntent:: currentSiopLevel = 0
,D/ContentApp( 1223):  LEVEL : 0
D/ConnectivityService(  918): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/TranscodeReceiver( 7115): onReceive : android.intent.action.CHECK_SIOP_LEVEL
D/TranscodeReceiver( 7115):  SIOP_LEVEL: 0
,E/LightSensor(  918): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  918): mCallbacks.updateBrightness()
D/DisplayPowerController(  918): getFinalBrightness : 8 -> 8
,D/StatusBar.NetworkController( 1173): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02012b/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020468/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
D/StatusBar.NetworkController( 1173): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1173): applyOpen
,D/StatusBar.NetworkController( 1173): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1173): applyOpen
D/StatusBar.NetworkController( 1173): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1173): applyOpen
D/StatusBar.NetworkController( 1173): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1173): applyOpen
,E/LightSensor(  918): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  918): mCallbacks.updateBrightness()
D/DisplayPowerController(  918): getFinalBrightness : 8 -> 8
,D/CustomFrequencyManagerService(  918): releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1958400  uid : 1000  pid : 918  tag : ACTIVITY_RESUME_BOOSTER@6
,W/ActivityManager(  918): mDVFSHelper.release()
,D/CustomFrequencyManagerService(  918): acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1958400  uid : 1000  pid : 918  pkgName : ACTIVITY_RESUME_BOOSTER@10
,E/LightSensor(  918): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  918): mCallbacks.updateBrightness()
D/DisplayPowerController(  918): getFinalBrightness : 8 -> 8
,W/Atfwd_Sendcmd(  323): AtCmdFwd service not published, waiting... retryCnt : 1
,E/LightSensor(  918): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  918): mCallbacks.updateBrightness()
D/DisplayPowerController(  918): getFinalBrightness : 8 -> 8
,D/CustomFrequencyManagerService(  918): releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1958400  uid : 1000  pid : 918  tag : ACTIVITY_RESUME_BOOSTER@10
,V/AlarmManager(  918): waitForAlarm result :8
,D/KeyguardUpdateMonitor( 1173): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1173): handleTimeUpdate
,D/KeyguardEffectViewController( 1173): onReceive action : android.intent.action.TIME_TICK
,I/KeyguardEffectViewController( 1173): *** don't update sliding image ***
,D/DateView( 1173): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1173): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,E/LightSensor(  918): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  918): mCallbacks.updateBrightness()
D/DisplayPowerController(  918): getFinalBrightness : 8 -> 8
,E/LightSensor(  918): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  918): mCallbacks.updateBrightness()
,D/DisplayPowerController(  918): getFinalBrightness : 8 -> 8
,E/LightSensor(  918): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  918): mCallbacks.updateBrightness()
,D/DisplayPowerController(  918): getFinalBrightness : 8 -> 8
,D/StatusBar.NetworkController( 1173): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02012b/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020464/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
D/StatusBar.NetworkController( 1173): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1173): applyOpen
,D/StatusBar.NetworkController( 1173): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1173): applyOpen
D/StatusBar.NetworkController( 1173): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1173): applyOpen
D/StatusBar.NetworkController( 1173): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1173): applyOpen
,E/SMD     (  280): DCD ON
,E/LightSensor(  918): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  918): mCallbacks.updateBrightness()
D/DisplayPowerController(  918): getFinalBrightness : 8 -> 8
,I/WifiStateMachine(  918): CMD_RSSI_POLL : calculateWifiScore in!
,I/WifiStateMachine(  918): CMD_RSSI_POLL : calculateWifiScore out!
I/WifiStateMachine(  918): CMD_RSSI_POLL : out!
,E/LightSensor(  918): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  918): mCallbacks.updateBrightness()
D/DisplayPowerController(  918): getFinalBrightness : 8 -> 8
,E/LightSensor(  918): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  918): mCallbacks.updateBrightness()
,D/DisplayPowerController(  918): getFinalBrightness : 8 -> 8
,E/LightSensor(  918): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
D/AutomaticBrightnessController(  918): mCallbacks.updateBrightness()
,D/DisplayPowerController(  918): getFinalBrightness : 8 -> 8
,E/LightSensor(  918): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  918): mCallbacks.updateBrightness()
,D/DisplayPowerController(  918): getFinalBrightness : 8 -> 8
,E/LightSensor(  918): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  918): mCallbacks.updateBrightness()
,D/DisplayPowerController(  918): getFinalBrightness : 8 -> 8
,E/LightSensor(  918): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  918): mCallbacks.updateBrightness()
,D/DisplayPowerController(  918): getFinalBrightness : 8 -> 8
,V/AlarmManager(  918): waitForAlarm result :4
,D/BatteryService(  918): level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 297, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  918): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
D/BatteryService(  918): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  918):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  918): Plugged
I/MotionRecognitionService(  918): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1173): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1173): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1173):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1173): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1173): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1173): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3229): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3229): Disconnected process message: 10
,E/LightSensor(  918): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
D/AutomaticBrightnessController(  918): mCallbacks.updateBrightness()
D/DisplayPowerController(  918): getFinalBrightness : 8 -> 8
,E/LightSensor(  918): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  918): mCallbacks.updateBrightness()
D/DisplayPowerController(  918): getFinalBrightness : 8 -> 8
,V/GLSActivity( 1739): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/LightSensor(  918): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  918): mCallbacks.updateBrightness()
D/DisplayPowerController(  918): getFinalBrightness : 8 -> 8
,I/GLSUser ( 1739): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
,I/GLSUser ( 1739): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1739): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1739): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1739): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/Finsky  ( 6619): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,D/Finsky  ( 6619): [1] 5.onFinished: Installation state replication failed.
D/Finsky  ( 6619): [1] 5.onFinished: Scheduling replication attempt 3.
,E/LightSensor(  918): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  918): mCallbacks.updateBrightness()
,D/DisplayPowerController(  918): getFinalBrightness : 8 -> 8
,E/LightSensor(  918): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  918): mCallbacks.updateBrightness()
,D/DisplayPowerController(  918): getFinalBrightness : 8 -> 8
,E/LightSensor(  918): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  918): mCallbacks.updateBrightness()
,D/DisplayPowerController(  918): getFinalBrightness : 8 -> 8
,E/LightSensor(  918): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  918): mCallbacks.updateBrightness()
,D/DisplayPowerController(  918): getFinalBrightness : 8 -> 8
,E/LightSensor(  918): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  918): mCallbacks.updateBrightness()
,D/DisplayPowerController(  918): getFinalBrightness : 8 -> 8
,E/LightSensor(  918): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  918): mCallbacks.updateBrightness()
,D/DisplayPowerController(  918): getFinalBrightness : 8 -> 8
,E/LightSensor(  918): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  918): mCallbacks.updateBrightness()
,D/DisplayPowerController(  918): getFinalBrightness : 8 -> 8
,E/SMD     (  280): DCD ON
,E/LightSensor(  918): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  918): mCallbacks.updateBrightness()
,D/DisplayPowerController(  918): getFinalBrightness : 8 -> 8
,V/AlarmManager(  918): waitForAlarm result :4
,D/ConnectivityService(  918): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/WifiStateMachine(  918): CMD_RSSI_POLL : calculateWifiScore in!
,I/WifiStateMachine(  918): CMD_RSSI_POLL : calculateWifiScore out!
I/WifiStateMachine(  918): CMD_RSSI_POLL : out!
,E/LightSensor(  918): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  918): mCallbacks.updateBrightness()
,D/DisplayPowerController(  918): getFinalBrightness : 8 -> 8
,E/LightSensor(  918): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  918): mCallbacks.updateBrightness()
,D/DisplayPowerController(  918): getFinalBrightness : 8 -> 8
,E/LightSensor(  918): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  918): mCallbacks.updateBrightness()
,D/DisplayPowerController(  918): getFinalBrightness : 8 -> 8
,E/LightSensor(  918): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  918): mCallbacks.updateBrightness()
,D/DisplayPowerController(  918): getFinalBrightness : 8 -> 8
,E/LightSensor(  918): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  918): mCallbacks.updateBrightness()
,D/DisplayPowerController(  918): getFinalBrightness : 8 -> 8
,E/LightSensor(  918): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  918): mCallbacks.updateBrightness()
,D/DisplayPowerController(  918): getFinalBrightness : 8 -> 8
,I/ServiceManager(  323): Waiting for service AtCmdFwd...
,E/LightSensor(  918): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  918): mCallbacks.updateBrightness()
,D/DisplayPowerController(  918): getFinalBrightness : 8 -> 8
,E/LightSensor(  918): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  918): mCallbacks.updateBrightness()
,D/DisplayPowerController(  918): getFinalBrightness : 8 -> 8
,E/LightSensor(  918): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  918): mCallbacks.updateBrightness()
,D/DisplayPowerController(  918): getFinalBrightness : 8 -> 8
,E/LightSensor(  918): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  918): mCallbacks.updateBrightness()
,D/DisplayPowerController(  918): getFinalBrightness : 8 -> 8
,E/LightSensor(  918): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  918): mCallbacks.updateBrightness()
D/DisplayPowerController(  918): getFinalBrightness : 8 -> 8
,E/LightSensor(  918): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  918): mCallbacks.updateBrightness()
,D/DisplayPowerController(  918): getFinalBrightness : 8 -> 8
,I/ServiceManager(  323): Waiting for service AtCmdFwd...
,E/LightSensor(  918): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  918): mCallbacks.updateBrightness()
D/DisplayPowerController(  918): getFinalBrightness : 8 -> 8
,E/LightSensor(  918): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  918): mCallbacks.updateBrightness()
D/DisplayPowerController(  918): getFinalBrightness : 8 -> 8
,E/LightSensor(  918): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  918): mCallbacks.updateBrightness()
D/DisplayPowerController(  918): getFinalBrightness : 8 -> 8
,E/LightSensor(  918): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  918): mCallbacks.updateBrightness()
D/DisplayPowerController(  918): getFinalBrightness : 8 -> 8
,E/SMD     (  280): DCD ON
,E/LightSensor(  918): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  918): mCallbacks.updateBrightness()
D/DisplayPowerController(  918): getFinalBrightness : 8 -> 8
,I/WifiStateMachine(  918): CMD_RSSI_POLL : calculateWifiScore in!
,I/WifiStateMachine(  918): CMD_RSSI_POLL : calculateWifiScore out!
,I/WifiStateMachine(  918): CMD_RSSI_POLL : out!
,I/ServiceManager(  323): Waiting for service AtCmdFwd...
,E/LightSensor(  918): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  918): mCallbacks.updateBrightness()
,D/DisplayPowerController(  918): getFinalBrightness : 8 -> 8,
,E/LightSensor(  918): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  918): mCallbacks.updateBrightness()
D/DisplayPowerController(  918): getFinalBrightness : 8 -> 8
,E/LightSensor(  918): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  918): mCallbacks.updateBrightness()
D/DisplayPowerController(  918): getFinalBrightness : 8 -> 8
,E/LightSensor(  918): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  918): mCallbacks.updateBrightness()
D/DisplayPowerController(  918): getFinalBrightness : 8 -> 8
,E/LightSensor(  918): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  918): mCallbacks.updateBrightness()
D/DisplayPowerController(  918): getFinalBrightness : 8 -> 8
,E/LightSensor(  918): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  918): mCallbacks.updateBrightness()
D/DisplayPowerController(  918): getFinalBrightness : 8 -> 8
,I/ServiceManager(  323): Waiting for service AtCmdFwd...
,E/LightSensor(  918): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  918): mCallbacks.updateBrightness()
,D/DisplayPowerController(  918): getFinalBrightness : 8 -> 8
,E/LightSensor(  918): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  918): mCallbacks.updateBrightness()
D/DisplayPowerController(  918): getFinalBrightness : 8 -> 8
,E/LightSensor(  918): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  918): mCallbacks.updateBrightness()
D/DisplayPowerController(  918): getFinalBrightness : 8 -> 8
,E/LightSensor(  918): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  918): mCallbacks.updateBrightness()
,D/DisplayPowerController(  918): getFinalBrightness : 8 -> 8
,E/LightSensor(  918): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  918): mCallbacks.updateBrightness()
D/DisplayPowerController(  918): getFinalBrightness : 8 -> 8
,E/LightSensor(  918): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  918): mCallbacks.updateBrightness()
D/DisplayPowerController(  918): getFinalBrightness : 8 -> 8
,I/ServiceManager(  323): Waiting for service AtCmdFwd...
,E/LightSensor(  918): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  918): mCallbacks.updateBrightness()
D/DisplayPowerController(  918): getFinalBrightness : 8 -> 8
,E/LightSensor(  918): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  918): mCallbacks.updateBrightness()
D/DisplayPowerController(  918): getFinalBrightness : 8 -> 8
,D/SSRM:m  (  918): SIOP:: AP = 350, PST = 410, CUR = 300
,E/LightSensor(  918): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  918): mCallbacks.updateBrightness()
,D/DisplayPowerController(  918): getFinalBrightness : 8 -> 8
,E/LightSensor(  918): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  918): mCallbacks.updateBrightness()
D/DisplayPowerController(  918): getFinalBrightness : 8 -> 8
,E/SMD     (  280): DCD ON
,E/LightSensor(  918): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  918): mCallbacks.updateBrightness()
D/DisplayPowerController(  918): getFinalBrightness : 8 -> 8
,I/WifiStateMachine(  918): CMD_RSSI_POLL : calculateWifiScore in!
,I/WifiStateMachine(  918): CMD_RSSI_POLL : calculateWifiScore out!
,I/WifiStateMachine(  918): CMD_RSSI_POLL : out!
,W/Atfwd_Sendcmd(  323): AtCmdFwd service not published, waiting... retryCnt : 2
,E/LightSensor(  918): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  918): mCallbacks.updateBrightness()
D/DisplayPowerController(  918): getFinalBrightness : 8 -> 8
,E/LightSensor(  918): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  918): mCallbacks.updateBrightness()
D/DisplayPowerController(  918): getFinalBrightness : 8 -> 8
,E/LightSensor(  918): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  918): mCallbacks.updateBrightness()
,D/DisplayPowerController(  918): getFinalBrightness : 8 -> 8
,E/LightSensor(  918): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  918): mCallbacks.updateBrightness()
,D/DisplayPowerController(  918): getFinalBrightness : 8 -> 8
,E/LightSensor(  918): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  918): mCallbacks.updateBrightness()
D/DisplayPowerController(  918): getFinalBrightness : 8 -> 8
,E/LightSensor(  918): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  918): mCallbacks.updateBrightness()
D/DisplayPowerController(  918): getFinalBrightness : 8 -> 8
,E/LightSensor(  918): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  918): mCallbacks.updateBrightness()
D/DisplayPowerController(  918): getFinalBrightness : 8 -> 8
,E/LightSensor(  918): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  918): mCallbacks.updateBrightness()
,D/DisplayPowerController(  918): getFinalBrightness : 8 -> 8
,E/LightSensor(  918): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  918): mCallbacks.updateBrightness()
,D/DisplayPowerController(  918): getFinalBrightness : 8 -> 8
,E/LightSensor(  918): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  918): mCallbacks.updateBrightness()
D/DisplayPowerController(  918): getFinalBrightness : 8 -> 8
,E/LightSensor(  918): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  918): mCallbacks.updateBrightness()
D/DisplayPowerController(  918): getFinalBrightness : 8 -> 8
,D/BatteryService(  918): level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 298, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  918): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  918): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  918):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  918): Plugged
I/MotionRecognitionService(  918): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1173): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1173): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1173):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1173): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1173): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1173): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3229): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3229): Disconnected process message: 10
,E/LightSensor(  918): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  918): mCallbacks.updateBrightness()
,D/DisplayPowerController(  918): getFinalBrightness : 8 -> 8
,E/LightSensor(  918): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  918): mCallbacks.updateBrightness()
,D/DisplayPowerController(  918): getFinalBrightness : 8 -> 8
,E/LightSensor(  918): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  918): mCallbacks.updateBrightness()
D/DisplayPowerController(  918): getFinalBrightness : 8 -> 8
,E/LightSensor(  918): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  918): mCallbacks.updateBrightness()
,D/DisplayPowerController(  918): getFinalBrightness : 8 -> 8
,E/SMD     (  280): DCD ON
,D/PowerManagerService(  918): [s] UserActivityState : 1 -> 2
,D/DisplayPowerController(  918): getFinalBrightness : 1 -> 1
,D/PowerManagerService(  918): [s] DisplayPowerCallbacks : onStateChanged()
,D/lights  (  918): lcd : 2 +
,E/LightSensor(  918): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  918): mCallbacks.updateBrightness()
,D/DisplayPowerController(  918): getFinalBrightness : 1 -> 1
,D/DisplayPowerController(  918): getFinalBrightness : 1 -> 1
,D/lights  (  918): lcd : 2 -
,D/lights  (  918): lcd : 1 +
,D/lights  (  918): lcd : 1 -
,D/DisplayPowerController(  918): getFinalBrightness : 1 -> 1
,I/WifiStateMachine(  918): CMD_RSSI_POLL : calculateWifiScore in!
E/LightSensor(  918): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  918): mCallbacks.updateBrightness()
D/DisplayPowerController(  918): getFinalBrightness : 1 -> 1
,I/WifiStateMachine(  918): CMD_RSSI_POLL : calculateWifiScore out!
I/WifiStateMachine(  918): CMD_RSSI_POLL : out!
,E/LightSensor(  918): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  918): mCallbacks.updateBrightness()
,D/DisplayPowerController(  918): getFinalBrightness : 1 -> 1
,E/LightSensor(  918): RED : 1, GREEN : 0, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=0, bp1=1, cp1=2, cpl=3202560
,D/AutomaticBrightnessController(  918): mCallbacks.updateBrightness()
,D/DisplayPowerController(  918): getFinalBrightness : 1 -> 1
,E/LightSensor(  918): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  918): mCallbacks.updateBrightness()
,D/DisplayPowerController(  918): getFinalBrightness : 1 -> 1
,E/LightSensor(  918): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  918): mCallbacks.updateBrightness()
,D/DisplayPowerController(  918): getFinalBrightness : 1 -> 1
,E/LightSensor(  918): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  918): mCallbacks.updateBrightness()
,D/DisplayPowerController(  918): getFinalBrightness : 1 -> 1
,E/LightSensor(  918): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  918): mCallbacks.updateBrightness()
,D/DisplayPowerController(  918): getFinalBrightness : 1 -> 1
,E/LightSensor(  918): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  918): mCallbacks.updateBrightness()
,D/DisplayPowerController(  918): getFinalBrightness : 1 -> 1
,E/LightSensor(  918): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  918): mCallbacks.updateBrightness()
,D/DisplayPowerController(  918): getFinalBrightness : 1 -> 1
,W/ContextImpl(  918): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/LightSensor(  918): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  918): mCallbacks.updateBrightness()
,D/DisplayPowerController(  918): getFinalBrightness : 1 -> 1
,D/StatusBar.NetworkController( 1173): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02012b/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020468/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
,D/StatusBar.NetworkController( 1173): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1173): applyOpen
,D/StatusBar.NetworkController( 1173): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1173): applyOpen
D/StatusBar.NetworkController( 1173): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1173): applyOpen
D/StatusBar.NetworkController( 1173): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1173): applyOpen
,E/LightSensor(  918): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  918): mCallbacks.updateBrightness()
,D/DisplayPowerController(  918): getFinalBrightness : 1 -> 1
,E/LightSensor(  918): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  918): mCallbacks.updateBrightness()
,D/DisplayPowerController(  918): getFinalBrightness : 1 -> 1
,E/LightSensor(  918): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  918): mCallbacks.updateBrightness()
,D/DisplayPowerController(  918): getFinalBrightness : 1 -> 1
,E/LightSensor(  918): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  918): mCallbacks.updateBrightness()
,D/DisplayPowerController(  918): getFinalBrightness : 1 -> 1
,E/LightSensor(  918): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  918): mCallbacks.updateBrightness()
,D/DisplayPowerController(  918): getFinalBrightness : 1 -> 1
,E/LightSensor(  918): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  918): mCallbacks.updateBrightness()
,D/DisplayPowerController(  918): getFinalBrightness : 1 -> 1
,E/SMD     (  280): DCD ON
,E/LightSensor(  918): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  918): mCallbacks.updateBrightness()
,D/DisplayPowerController(  918): getFinalBrightness : 1 -> 1
,E/Watchdog(  918): !@Sync 4
,I/WifiStateMachine(  918): CMD_RSSI_POLL : calculateWifiScore in!
,I/WifiStateMachine(  918): CMD_RSSI_POLL : calculateWifiScore out!
,I/WifiStateMachine(  918): CMD_RSSI_POLL : out!
,E/LightSensor(  918): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  918): mCallbacks.updateBrightness()
,D/DisplayPowerController(  918): getFinalBrightness : 1 -> 1
,E/LightSensor(  918): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  918): mCallbacks.updateBrightness()
,D/DisplayPowerController(  918): getFinalBrightness : 1 -> 1
,E/LightSensor(  918): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  918): mCallbacks.updateBrightness()
,D/DisplayPowerController(  918): getFinalBrightness : 1 -> 1
,E/LightSensor(  918): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  918): mCallbacks.updateBrightness()
,D/DisplayPowerController(  918): getFinalBrightness : 1 -> 1
,D/StatusBar.NetworkController( 1173): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02012b/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020464/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
,D/StatusBar.NetworkController( 1173): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1173): applyOpen
,D/StatusBar.NetworkController( 1173): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1173): applyOpen
D/StatusBar.NetworkController( 1173): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1173): applyOpen
D/StatusBar.NetworkController( 1173): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1173): applyOpen
,E/LightSensor(  918): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  918): mCallbacks.updateBrightness()
D/DisplayPowerController(  918): getFinalBrightness : 1 -> 1
,E/LightSensor(  918): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  918): mCallbacks.updateBrightness()
,D/DisplayPowerController(  918): getFinalBrightness : 1 -> 1
,E/LightSensor(  918): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  918): mCallbacks.updateBrightness()
,D/DisplayPowerController(  918): getFinalBrightness : 1 -> 1
,E/LightSensor(  918): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  918): mCallbacks.updateBrightness()
,D/DisplayPowerController(  918): getFinalBrightness : 1 -> 1
,E/LightSensor(  918): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  918): mCallbacks.updateBrightness()
,D/DisplayPowerController(  918): getFinalBrightness : 1 -> 1
,E/LightSensor(  918): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  918): mCallbacks.updateBrightness()
,D/DisplayPowerController(  918): getFinalBrightness : 1 -> 1
,D/StatusBar.NetworkController( 1173): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02012b/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020468/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
D/StatusBar.NetworkController( 1173): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1173): applyOpen
,D/StatusBar.NetworkController( 1173): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1173): applyOpen
D/StatusBar.NetworkController( 1173): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1173): applyOpen
,D/StatusBar.NetworkController( 1173): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1173): applyOpen
,E/LightSensor(  918): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  918): mCallbacks.updateBrightness()
D/DisplayPowerController(  918): getFinalBrightness : 1 -> 1
,E/LightSensor(  918): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  918): mCallbacks.updateBrightness()
D/DisplayPowerController(  918): getFinalBrightness : 1 -> 1
,E/LightSensor(  918): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  918): mCallbacks.updateBrightness()
D/DisplayPowerController(  918): getFinalBrightness : 1 -> 1
,E/LightSensor(  918): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  918): mCallbacks.updateBrightness()
,D/DisplayPowerController(  918): getFinalBrightness : 1 -> 1
,E/LightSensor(  918): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
D/AutomaticBrightnessController(  918): mCallbacks.updateBrightness()
D/DisplayPowerController(  918): getFinalBrightness : 1 -> 1
,E/LightSensor(  918): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
D/AutomaticBrightnessController(  918): mCallbacks.updateBrightness()
D/DisplayPowerController(  918): getFinalBrightness : 1 -> 1
,E/SMD     (  280): DCD ON
,D/PowerManagerService(  918): [s] UserActivityState : 2 -> 4
,I/PowerManagerService(  918): Nap time (uid 1000)...
,I/PowerManagerService(  918): !@[ps] Screen__Off(2) : 
,I/PowerManagerService(  918): Going to sleep due to screen timeout (uid 1000)...
,D/PowerManagerService(  918): [PWL] sb acquire: PowerManagerService.Broadcasts
,D/PowerManagerService(  918): SecHardwareInterface.setBatteryADC : false
,D/InputManager-JNI(  918): setDeviceInteractive: 0
,D/InputManager-JNI(  918): sysfs_write +: /sys/class/input/event1/device/enabled: 0
,D/InputManager-JNI(  918): sysfs_write +: /sys/class/input/event2/device/enabled: 0
D/PowerManagerService(  918): handleSandman : startDream()
,E/PowerManagerService(  918): handleSandman : startDreaming, but isDreaming false
,I/PowerManagerService(  918): Sleeping (uid 1000)...
D/PowerManagerService(  918): [s] UserActivityState : 4 -> 0
D/PowerManagerService(  918): [input device light] setInputDeviceLightOn is called : 0
,D/PowerManagerService(  918): [input device light] handleInputDeviceLightOff
,I/SurfaceFlinger(  249): id=17 createSurf (1080x1920),2 flag=404, ColorFade
,D/InputManager-JNI(  918): sysfs_write -: /sys/class/input/event1/device/enabled: 0
,D/InputManager-JNI(  918): sysfs_write -: /sys/class/input/event2/device/enabled: 0
,D/SContextService(  918): 	.unregisterCallback : 1, client=
D/SContextService(  918): unregisterCallback() : Listener = android.hardware.scontext.SContextService$Listener@365fb388, Service = Auto Rotation, used = 1
,W/CAE     (  918): unregisterCallback(ContextAwareService.java:199) - [unregi 01] Mutex is locked for AUTO_ROTATION
,V/CAE     (  918): stop(ContextProvider.java:149)
,V/CAE     (  918): clear(AutoRotationRunner.java:182)
V/CAE     (  918): disable(AutoRotationRunner.java:171)
,I/CAE     (  918): sendCmdToSensorHub(SensorHubCommManager.java:144) - -78, 7, 0, 0,
D/SensorHubManager(  918): SendSensorHubData: send data = -78, 7, 0, 0
,D/Sensorhubs(  296): sendContextData: -78, 7, 0, 0
,D/CAE     (  918): getFaultDetectionResult(AutoRotationRunner.java:195) - true
,I/CAE     (  918): notifyCmdProcessResultObserver(ContextProvider.java:617) - CheckResult = 0, Cause = Success
,D/CAE     (  918): doCommendProcess(ContextAwareService.java:314) - complete notify the operation result.
,I/CAE     (  918): displayUsedCountForService(ContextAwareService.java:406) - totalCnt = 0, serviceCount = 0, subCollectionCount = 0
D/CAE     (  918): showListenerList(ContextAwareService.java:247) - ===== Context Aware Service List =====
,W/CAE     (  918): unregisterCallback(ContextAwareService.java:234) - [unregi 02] Mutex is unlocked for AUTO_ROTATION
D/SContextService(  918): removeSContextService() : service = Auto Rotation
D/SContextService(  918): ===== SContext Service List =====
D/SContextManager(  918):   .unregisterListener : listener = com.android.internal.policy.impl.WindowOrientationListener$SContextListenerImpl@21e8d943, service=Auto Rotation
,D/KeyguardViewMediator( 1173): onScreenTurnedOff(3)
I/KeyguardEffectViewController( 1173): *** KeyguardEffectView getInstanceIfExists ***
,D/KeyguardEffectViewController( 1173): changeWallpaperByScreenOff()
D/KeyguardViewMediator( 1173): notifyScreenOffLocked
,I/SQLiteSecureOpenHelper( 3537): getWritableDatabase(pwd)
,I/SQLiteSecureOpenHelper( 3537): getDatabaseLocked(b,b,pwd)...
,D/LockPatternUtilsCache( 1173): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1173): value : false
D/KeyguardViewMediator( 1173): timeout : 5000
,D/LockPatternUtilsCache( 1173): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1173): value : false
,E/LightSensor(  918): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/DisplayPowerController(  918): ColorFade: onAnimationStart
D/DisplayPowerController(  918): getFinalBrightness : 8 -> 0
D/AutomaticBrightnessController(  918): mCallbacks.updateBrightness()
,D/DisplayPowerController(  918): getFinalBrightness : 8 -> 0
,D/lights  (  918): lcd : 0 +
,D/DisplayPowerController(  918): getFinalBrightness : 8 -> 0
,D/KeyguardViewMediator( 1173): setting alarm to turn off keyguard, seq = 2
D/KeyguardViewMediator( 1173): handleNotifyScreenOff
,D/lights  (  918): lcd : 0 -
,D/LightsService(  918): [api] [SvcLED] setFlashing :: id = 3, color = 0, mode = 14, onMS = 0, offMS = 0,  (uid: 1000 pid: 918) 
,D/LightsService(  918): [SvcLED] setSvcLedStateLocked:: SvcLEDState : 0x0 -> 0x40 | SvcLED(id=3) set On
,D/LightsService(  918): [SvcLED]  onSensorChanged::light value = 0
,D/SensorManager(  918): registerListener :: 6, TMG399X RGB Sensor, 200000, 0,  
,D/BatteryService(  918): turn on LED for fully charged
,D/SensorManager(  918): unregisterListener ::   
D/lights  (  918): led_pattern : 5 +
,I/CAE     (  918): handleMessage(CaPowerManager.java:182) - AP_SLEEP
,I/CAE     (  918): updateApPowerStatus(SensorHubParserProvider.java:421) - AP_SLEEP
I/CAE     (  918): sendCmdToSensorHub(SensorHubCommManager.java:144) - -76, 13, -46, 0,
D/SensorHubManager(  918): SendSensorHubData: send data = -76, 13, -46, 0
D/Sensorhubs(  296): sendContextData: -76, 13, -46, 0
,D/lights  (  918): led_pattern : 5 -
,D/LightsService(  918): [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=3) maintains its priority right
,I/CAE     (  918): sendCmdToSensorHub(SensorHubCommManager.java:144) - -63, 14, 0, 33, 18,
D/SensorHubManager(  918): SendSensorHubData: send data = -63, 14, 0, 33, 18
,D/Sensorhubs(  296): sendContextData: -63, 14, 0, 33, 18
,D/MotionRecognitionService(  918):   mReceiver.onReceive : ACTION_SCREEN_OFF
,E/MotionRecognitionService(  918):  handler : SCREEN_OFF end 
,D/WifiStateMachine(  918): backgroundScan enabled=false startBackgroundScanIfNeeded:false
E/WifiStateMachine(  918): handleScreenStateChanged Exit: false
,D/NotificationService(  918): ACTION_SCREEN_OFF
,D/LightsService(  918): [api] [SvcLED] setFlashing :: id = 4, color = ffffffff, mode = 12, onMS = 500, offMS = 2000,  (uid: 1000 pid: 918) 
D/LightsService(  918): [SvcLED] setSvcLedStateLocked:: SvcLEDState : 0x40 -> 0x42 | SvcLED(id=4) set On
,D/LightsService(  918): [SvcLED]  onSensorChanged::light value = 0
,E/WifiStateMachine(  918): setSuspendOptimizationsNative: 4 true -want true stack:setSuspendOptimizationsNative - access$16800 - processMessage - processMsg
,E/WifiStateMachine(  918): setSuspendOptimizationsNative do it 4 true stack:setSuspendOptimizationsNative - access$16800 - processMessage - processMsg
E/native  (  918): do suspend true
,D/SensorManager(  918): registerListener :: 6, TMG399X RGB Sensor, 200000, 0,  
,D/SensorManager(  918): unregisterListener ::   
D/LightsService(  918): [SvcLED]  setSvcLedLightLocked :: priority changed! SvcLED(id=3) OUT; SvcLED(id=4) IN
,D/audio_hw_primary(  288): adev_set_parameters: enter: screen_state=off
,V/voice   (  288): voice_set_parameters: enter: screen_state=off
V/voice   (  288): voice_set_parameters: exit with code(-2)
V/msm8974_platform(  288): platform_set_parameters: enter: screen_state=off
V/msm8974_platform(  288): platform_set_parameters: exit with code(-2)
D/audio_hw_hfp(  288): audio_extn_hfp_set_parameters: enter
V/audio_hw_primary(  288): adev_set_parameters: exit
,I/SecExternalDisplayIntents_Java(  918): Intent Recieved ..  -android.intent.action.SCREEN_OFFBroadCast Map value - 18
,D/IpRemoteDisplayController(  918): intent received android.intent.action.SCREEN_OFF
,D/IpRemoteDisplayController(  918): Bridge Server is not available
,D/VolumePanel( 1173): mCoverBroadcastReceiver: Screen OFF start
D/VolumePanel( 1173): mCoverBroadcastReceiver : call onDismissSafeVolumeWarning() #1
,D/VolumePanel( 1173): mCoverBroadcastReceiver: Screen OFF end
D/VolumePanel( 1173): mCoverBroadcastReceiver: onReceive() end : intent=Intent { act=android.intent.action.SCREEN_OFF flg=0x50000010 (has extras) }
,D/PersonaManagerService(  918): ACTION_SCREEN_OFF onReceive
,D/PersonaManagerServiceHandler(  918): MSG_ACTION_SCREEN_OFF called
,D/NfcService( 1470): call the applyRotuiing
,D/STATUSBAR-PhoneStatusBar( 1173):      ACTION_SCREEN_OFF is finished!!!! 
,E/StatusBar( 1173): onReceive : Intent.ACTION_SCREEN_OFF
D/Recents_AlternateRecentsComponent( 1173): dismissHelpPopup 
,D/accuweather( 1970): [KK AccuPhone]>>> SWW:66 [0:0] action : androidintentactionSCREEN_OFF
,D/accuweather( 1970): [KK AccuPhone]>>> SWW:467 [0:0] stopRefreshIcon : 1
D/accuweather( 1970): [KK AccuPhone]>>> SWW:364 [0:0] getWeatherRenderer : 1
,E/LightSensor(  918): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  918): mCallbacks.updateBrightness()
D/DisplayPowerController(  918): getFinalBrightness : 8 -> 0
,D/ConnectivityService(  918): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/LockPatternUtilsCache( 1173): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1173): value : false
,W/ActivityManager(  918): getTasks: caller 10086 does not hold GET_TASKS; limiting output
,W/ActivityManager(  918): getTasks: caller 10086 does not hold GET_TASKS; limiting output
,D/PowerManagerService(  918): [PWL] sb release: PowerManagerService.Broadcasts
,D/DisplayPowerState(  918): !@ ColorFade entry
,D/DisplayPowerController(  918): ColorFade: onAnimationEnd
,D/AutomaticBrightnessController(  918): [DAB] setLightSensorEnabled : Send Update unregisterListener mLightSensor
I/AutomaticBrightnessController(  918): [DAB] fileWriteInt : /sys/class/tcon/tcon/auto_br  value : 0
D/AutomaticBrightnessController(  918): [DAB] setLightSensorEnabled : unregisterListener mLightSensor
E/LightSensor(  918): Light old sensor_state 8705, new sensor_state : 8193 en : 0
I/AutomaticBrightnessController(  918): [DAB] fileWriteInt : /sys/class/backlight/panel/auto_brightness  value : 0
,D/SSRM:m  (  918): SIOP:: AP = 340, PST = 395, CUR = 300
D/X       (  918): broadcastSiopLevelIntent:: currentSiopLevel = -1
,D/SensorManager(  918): unregisterListener ::   
,E/Sensors (  918): Acc old sensor_state 8193, new sensor_state : 8192 en : 0
,D/ContentApp( 1223):  LEVEL : -1
,E/TranscodeReceiver( 7115): onReceive : android.intent.action.CHECK_SIOP_LEVEL
D/TranscodeReceiver( 7115):  SIOP_LEVEL: -1
,D/SensorManager(  918): unregisterListener ::   
,D/DisplayPowerController(  918): getFinalBrightness : 0 -> 0
,D/DisplayPowerController(  918): getFinalBrightness : 0 -> 0
I/DisplayManagerService(  918): Display device changed: DisplayDeviceInfo{"Built-in Screen": 1080 x 1920, 60.0 fps, supportedRefreshRates [60.0], density 480, 422.03 x 424.069 dpi, appVsyncOff 0, presDeadline 17666667, touch INTERNAL, rotation 0, type BUILT_IN, state OFF, FLAG_DEFAULT_DISPLAY, FLAG_ROTATES_WITH_CONTENT, FLAG_SECURE, FLAG_SUPPORTS_PROTECTED_BUFFERS}
D/SurfaceFlinger(  249): Set power mode=0, type=0 flinger=0xb6962000
D/qdhwcomposer(  249): hwc_blank: Blanking display: 0
,V/ActivityManager(  918): Display changed displayId=0
,D/LockPatternUtilsCache( 1173): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1173): value : false
,D/LockPatternUtilsCache( 1173): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1173): value : false
,D/LockPatternUtilsCache( 1173): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1173): value : false
,D/LockPatternUtilsCache( 1173): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1173): value : false
,D/StatusBar.NetworkController( 1173): onSignalStrengthsChanged signalStrength=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte level=0
,D/StatusBar.NetworkController( 1173): updateTelephonySignalStrength: hasService=false ss=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte
D/StatusBar.NetworkController( 1173): updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal
D/StatusBar.NetworkController( 1173): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02012b/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020468/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
,D/LockPatternUtilsCache( 1173): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1173): value : false
,I/rmt_storage(  270): rmt_storage_connect_cb: clnt_h=0x5 conn_h=0xb6b01090
I/rmt_storage(  270): rmt_storage_rw_iovec_cb: /boot/modem_fs1: clnt_h=0x1: req_h=0xa msg_id=3: R/W request received
I/rmt_storage(  270): wakelock acquired: 1, error no: 42
I/rmt_storage(  270): rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1 Unblock worker thread (th_id: -1229455232)
,I/rmt_storage(  270): rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1: req_h=0xa msg_id=3: Bytes written = 1572864
I/rmt_storage(  270): rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1: req_h=0xa msg_id=3: Send response: res=0 err=0
I/rmt_storage(  270): rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1 About to block rmt_storage client thread (th_id: -1229455232) wakelock released: 1, error no: 22
I/rmt_storage(  270): 
,I/rmt_storage(  270): rmt_storage_disconnect_cb: clnt_h=0x0x5 conn_h=0x0xb6b01090
,I/qdhwcomposer(  249): handle_blank_event: dpy:0 panel power state: 0
D/qdhwcomposer(  249): hwc_blank: Done blanking display: 0
,D/SurfaceControl(  918): Excessive delay in setPowerMode(): 258ms
D/PowerManagerService(  918): !@[s] blankAllDisplays() : blankAllDisplaysFromPowerManage
D/MISC PowerHAL(  918): sysfs_write +: /sys/class/power_supply/battery/lcd: 0
D/MISC PowerHAL(  918): sysfs_write -: /sys/class/power_supply/battery/lcd: 0
,I/QCOM PowerHAL(  918): Got set_interactive hint
,I/PowerManagerService(  918): [PWL] Off : 0s ago
I/PowerManagerService(  918): [PWL]   PowerManagerService.Display: ref count=2
I/PowerManagerService(  918): [PWL]     mDisplayReady : false
D/DisplayPowerController(  918): getFinalBrightness : 0 -> 0
D/PowerManagerService(  918): [s] DisplayPowerCallbacks : onStateChanged()
D/PowerManagerService(  918): [PWL] sb release: PowerManagerService.Display
,I/ServiceManager(  323): Waiting for service AtCmdFwd...
,I/ServiceManager(  323): Waiting for service AtCmdFwd...,
,E/SMD     (  280): DCD ON
,I/ServiceManager(  323): Waiting for service AtCmdFwd...
,V/AlarmManager(  918): waitForAlarm result :4
,V/GLSActivity( 1739): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1739): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
,I/GLSUser ( 1739): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1739): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1739): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1739): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/Finsky  ( 6619): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,D/Finsky  ( 6619): [1] 5.onFinished: Installation state replication failed.
D/Finsky  ( 6619): [1] 5.onFinished: Scheduling replication attempt 4.
,I/ServiceManager(  323): Waiting for service AtCmdFwd...
,I/art     (  918): Explicit concurrent mark sweep GC freed 65284(3MB) AllocSpace objects, 20(3MB) LOS objects, 30% free, 36MB/52MB, paused 1.854ms total 180.122ms
,V/AlarmManager(  918): waitForAlarm result :4
,D/KeyguardViewMediator( 1173): received DELAYED_KEYGUARD_ACTION with seq = 2, mDelayedShowingSequence = 2
,D/PersonaManager( 1173): isKioskContainerExistOnDevice
,D/LockPatternUtilsCache( 1173): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1173): value : false
,D/LockPatternUtilsCache( 1173): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1173): value : false
,D/KeyguardViewMediator( 1173): doKeyguard: not showing because lockscreen is off
,I/ServiceManager(  323): Waiting for service AtCmdFwd...
,I/PowerManagerService(  918): [PWL] Off : 5s ago
,E/SMD     (  280): DCD ON
,W/Atfwd_Sendcmd(  323): AtCmdFwd service not published, waiting... retryCnt : 3
,E/SMD     (  280): DCD ON
,D/SSRM:m  (  918): SIOP:: AP = 330, PST = 383, CUR = 300
,E/SMD     (  280): DCD ON
,E/SMD     (  280): DCD ON
,I/PowerManagerService(  918): [PWL] Off : 15s ago
,W/ContextImpl(  918): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  280): DCD ON
,V/AlarmManager(  918): waitForAlarm result :4
,D/ConnectivityService(  918): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/BatteryService(  918): level:100, scale:100, status:5, health:2, present:true, voltage: 4383, temperature: 298, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  918): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
D/BatteryService(  918): stay LED for fully charged
D/BatteryService(  918): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  918):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  918): Plugged
I/MotionRecognitionService(  918): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1173): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1173): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1173):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3229): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3229): Disconnected process message: 10
,D/BatteryMeterView( 1173): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1173): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1173): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/ConnectivityService(  918): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/GLSUser ( 1739): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,I/GLSUser ( 1739): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1739): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1739): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1739): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ResourcesManager( 1739): creating new AssetManager and set to /system/app/PlusOne/PlusOne.apk
,V/BitmapFactory( 1739): DecodeImagePath(decodeResourceStream3) : res/mipmap-xxhdpi-v4/quantum_logo_google_plus_color_44in48.png
,V/BitmapFactory( 1739): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  918): uri = 14 selection = getSealedState
,D/SecContentProvider2(  918): mCursor = null
D/SecContentProvider2(  918): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  918): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
V/ApplicationPolicy(  918): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/StatusBar( 1173): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,I/PhoneStatusBar( 1173): Icon Only
,D/LockPatternUtilsCache( 1173): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1173): value : false
D/PanelView( 1173): There is/are notification(s) 
D/PanelView( 1173): There is/are notification(s) 
,E/HttpOperation( 6592): [kfu{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
E/HttpOperation( 6592): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 6592): 	at kfv.a(PG:65)
E/HttpOperation( 6592): 	at kff.u(PG:385)
E/HttpOperation( 6592): 	at kfb.a(PG:29)
E/HttpOperation( 6592): 	at kff.l(PG:132)
E/HttpOperation( 6592): 	at dsf.a(PG:807)
E/HttpOperation( 6592): 	at fhk.a(PG:1126)
E/HttpOperation( 6592): 	at fhk.a(PG:908)
E/HttpOperation( 6592): 	at fhk.onPerformSync(PG:636)
E/HttpOperation( 6592): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/HttpOperation( 6592): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/HttpOperation( 6592): 	at ihi.a(PG:22)
E/HttpOperation( 6592): 	at kft.a(PG:91)
E/HttpOperation( 6592): 	at kfv.a(PG:62)
E/HttpOperation( 6592): 	... 8 more
E/HttpOperation( 6592): Caused by: gdi: User intervention required. Notification has been pushed.
E/HttpOperation( 6592): 	at gde.c(Unknown Source)
E/HttpOperation( 6592): 	at gde.b(Unknown Source)
E/HttpOperation( 6592): 	at ihi.a(PG:19)
E/HttpOperation( 6592): 	... 10 more
,I/GLSUser ( 1739): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
I/GLSUser ( 1739): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1739): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1739): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1739): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/BitmapFactory( 1739): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  918): uri = 14 selection = getSealedState
D/SecContentProvider2(  918): mCursor = null
D/SecContentProvider2(  918): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  918): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy(  918): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/StatusBar( 1173): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,E/HttpOperation( 6592): [getmobileexperiments] Unexpected exception
E/HttpOperation( 6592): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 6592): 	at kfv.a(PG:65)
E/HttpOperation( 6592): 	at kff.u(PG:385)
E/HttpOperation( 6592): 	at kfb.a(PG:29)
E/HttpOperation( 6592): 	at kff.l(PG:132)
E/HttpOperation( 6592): 	at ieo.a(PG:43)
E/HttpOperation( 6592): 	at iep.a(PG:93)
E/HttpOperation( 6592): 	at fhn.a(PG:59)
E/HttpOperation( 6592): 	at lex.a(PG:85)
E/HttpOperation( 6592): 	at lex.b(PG:132)
E/HttpOperation( 6592): 	at fhk.a(PG:1146)
E/HttpOperation( 6592): 	at fhk.a(PG:908)
E/HttpOperation( 6592): 	at fhk.onPerformSync(PG:636)
E/HttpOperation( 6592): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/HttpOperation( 6592): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/HttpOperation( 6592): 	at ihi.a(PG:22)
E/HttpOperation( 6592): 	at kft.a(PG:91)
E/HttpOperation( 6592): 	at kfv.a(PG:62)
E/HttpOperation( 6592): 	... 12 more
E/HttpOperation( 6592): Caused by: gdi: User intervention required. Notification has been pushed.
E/HttpOperation( 6592): 	at gde.c(Unknown Source)
E/HttpOperation( 6592): 	at gde.b(Unknown Source)
E/HttpOperation( 6592): 	at ihi.a(PG:19)
E/HttpOperation( 6592): 	... 14 more
,E/ExperimentLoader( 6592): [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 6592): java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 6592): 	at kfv.a(PG:65)
E/ExperimentLoader( 6592): 	at kff.u(PG:385)
E/ExperimentLoader( 6592): 	at kfb.a(PG:29)
E/ExperimentLoader( 6592): 	at kff.l(PG:132)
E/ExperimentLoader( 6592): 	at ieo.a(PG:43)
E/ExperimentLoader( 6592): 	at iep.a(PG:93)
E/ExperimentLoader( 6592): 	at fhn.a(PG:59)
E/ExperimentLoader( 6592): 	at lex.a(PG:85)
E/ExperimentLoader( 6592): 	at lex.b(PG:132)
E/ExperimentLoader( 6592): 	at fhk.a(PG:1146)
E/ExperimentLoader( 6592): 	at fhk.a(PG:908)
E/ExperimentLoader( 6592): 	at fhk.onPerformSync(PG:636)
E/ExperimentLoader( 6592): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/ExperimentLoader( 6592): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/ExperimentLoader( 6592): 	at ihi.a(PG:22)
E/ExperimentLoader( 6592): 	at kft.a(PG:91)
E/ExperimentLoader( 6592): 	at kfv.a(PG:62)
E/ExperimentLoader( 6592): 	... 12 more
E/ExperimentLoader( 6592): Caused by: gdi: User intervention required. Notification has been pushed.
E/ExperimentLoader( 6592): 	at gde.c(Unknown Source)
E/ExperimentLoader( 6592): 	at gde.b(Unknown Source)
E/ExperimentLoader( 6592): 	at ihi.a(PG:19)
E/ExperimentLoader( 6592): 	... 14 more
,I/PhoneStatusBar( 1173): Icon Only
D/LockPatternUtilsCache( 1173): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1173): value : false
D/PanelView( 1173): There is/are notification(s) 
,D/PanelView( 1173): There is/are notification(s) 
,I/GLSUser ( 1739): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
I/GLSUser ( 1739): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1739): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1739): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1739): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/BitmapFactory( 1739): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  918): uri = 14 selection = getSealedState
D/SecContentProvider2(  918): mCursor = null
,D/SecContentProvider2(  918): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  918): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
V/ApplicationPolicy(  918): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,E/SQLiteLog( 1739): (10) POSIX Error : 11 SQLite Error : 3850
,D/StatusBar( 1173): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,E/HttpOperation( 6592): [getaccountstatus] Unexpected exception
E/HttpOperation( 6592): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 6592): 	at kfv.a(PG:65)
E/HttpOperation( 6592): 	at kff.u(PG:385)
E/HttpOperation( 6592): 	at kfb.a(PG:29)
E/HttpOperation( 6592): 	at ixd.a(PG:248)
E/HttpOperation( 6592): 	at ixd.b(PG:206)
E/HttpOperation( 6592): 	at ixd.a(PG:175)
E/HttpOperation( 6592): 	at fig.a(PG:78)
E/HttpOperation( 6592): 	at lex.a(PG:85)
E/HttpOperation( 6592): 	at lex.b(PG:132)
E/HttpOperation( 6592): 	at fhk.a(PG:1146)
E/HttpOperation( 6592): 	at fhk.a(PG:908)
E/HttpOperation( 6592): 	at fhk.onPerformSync(PG:636)
E/HttpOperation( 6592): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/HttpOperation( 6592): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/HttpOperation( 6592): 	at ihi.a(PG:22)
E/HttpOperation( 6592): 	at kft.a(PG:91)
E/HttpOperation( 6592): 	at kfv.a(PG:62)
E/HttpOperation( 6592): 	... 12 more
E/HttpOperation( 6592): Caused by: gdi: User intervention required. Notification has been pushed.
E/HttpOperation( 6592): 	at gde.c(Unknown Source)
E/HttpOperation( 6592): 	at gde.b(Unknown Source)
E/HttpOperation( 6592): 	at ihi.a(PG:19)
E/HttpOperation( 6592): 	... 14 more
,I/PhoneStatusBar( 1173): Icon Only
,D/LockPatternUtilsCache( 1173): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1173): value : false
D/PanelView( 1173): There is/are notification(s) 
,D/PanelView( 1173): There is/are notification(s) 
,E/EsSyncAdapterService( 6592): Sync failure
E/EsSyncAdapterService( 6592): java.io.IOException: Rpc failed
E/EsSyncAdapterService( 6592): 	at ixd.a(PG:348)
E/EsSyncAdapterService( 6592): 	at ixd.a(PG:248)
E/EsSyncAdapterService( 6592): 	at ixd.b(PG:206)
E/EsSyncAdapterService( 6592): 	at ixd.a(PG:175)
E/EsSyncAdapterService( 6592): 	at fig.a(PG:78)
E/EsSyncAdapterService( 6592): 	at lex.a(PG:85)
E/EsSyncAdapterService( 6592): 	at lex.b(PG:132)
E/EsSyncAdapterService( 6592): 	at fhk.a(PG:1146)
E/EsSyncAdapterService( 6592): 	at fhk.a(PG:908)
E/EsSyncAdapterService( 6592): 	at fhk.onPerformSync(PG:636)
E/EsSyncAdapterService( 6592): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/EsSyncAdapterService( 6592): Caused by: java.io.IOException: Cannot obtain authentication token
E/EsSyncAdapterService( 6592): 	at kfv.a(PG:65)
E/EsSyncAdapterService( 6592): 	at kff.u(PG:385)
E/EsSyncAdapterService( 6592): 	at kfb.a(PG:29)
E/EsSyncAdapterService( 6592): 	... 10 more
E/EsSyncAdapterService( 6592): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/EsSyncAdapterService( 6592): 	at ihi.a(PG:22)
E/EsSyncAdapterService( 6592): 	at kft.a(PG:91)
E/EsSyncAdapterService( 6592): 	at kfv.a(PG:62)
E/EsSyncAdapterService( 6592): 	... 12 more
E/EsSyncAdapterService( 6592): Caused by: gdi: User intervention required. Notification has been pushed.
E/EsSyncAdapterService( 6592): 	at gde.c(Unknown Source)
E/EsSyncAdapterService( 6592): 	at gde.b(Unknown Source)
E/EsSyncAdapterService( 6592): 	at ihi.a(PG:19)
E/EsSyncAdapterService( 6592): 	... 14 more
,D/ConnectivityService(  918): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SyncManager(  918): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, PERIODIC, currentRunTime 155167, reason: Periodic, SyncResult: stats [ numIoExceptions: 2]
,D/ConnectivityService(  918): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  918): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SecContentProvider2(  918): uri = 11 selection = getMyKnoxAdmin
,D/SecContentProvider2(  918): mCursor = null
,E/SQLiteLog( 1739): (10) POSIX Error : 11 SQLite Error : 3850
,D/SSRM:m  (  918): SIOP:: AP = 320, PST = 373, CUR = 300
,E/SMD     (  280): DCD ON
,I/ServiceManager(  323): Waiting for service AtCmdFwd...
,I/ServiceManager(  323): Waiting for service AtCmdFwd...
,I/ServiceManager(  323): Waiting for service AtCmdFwd...
,E/SMD     (  280): DCD ON,
,V/AlarmManager(  918): waitForAlarm result :4
,I/ServiceManager(  323): Waiting for service AtCmdFwd...
,V/GLSActivity( 1739): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/art     ( 1739): Explicit concurrent mark sweep GC freed 28398(1700KB) AllocSpace objects, 18(1458KB) LOS objects, 40% free, 17MB/29MB, paused 610us total 35.183ms
,I/GLSUser ( 1739): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
,I/GLSUser ( 1739): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1739): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1739): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1739): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/Finsky  ( 6619): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,D/Finsky  ( 6619): [1] 5.onFinished: Installation state replication failed.
D/Finsky  ( 6619): [1] 5.onFinished: Scheduling replication attempt 5.
,I/ServiceManager(  323): Waiting for service AtCmdFwd...
,W/Atfwd_Sendcmd(  323): AtCmdFwd service not published, waiting... retryCnt : 4
,E/SMD     (  280): DCD ON
,E/Watchdog(  918): !@Sync 5
,D/BatteryService(  918): level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 298, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  918): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  918): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  918):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  918): Plugged
,I/MotionRecognitionService(  918): setPowerConnected  = true
,D/BatteryService(  918): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1173): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1173): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1173):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3229): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3229): Disconnected process message: 10
,D/BatteryMeterView( 1173): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1173): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1173): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  280): DCD ON
,D/SSRM:m  (  918): SIOP:: AP = 320, PST = 363, CUR = 300
,I/PowerManagerService(  918): [PWL] Off : 30s ago
,E/SMD     (  280): DCD ON
,W/ContextImpl(  918): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  280): DCD ON
,E/SMD     (  280): DCD ON
,D/SSRM:m  (  918): SIOP:: AP = 310, PST = 353, CUR = 300
,V/AlarmManager(  918): waitForAlarm result :8
,E/SMD     (  280): DCD ON
,V/AlarmManager(  918): waitForAlarm result :4
,D/KeyguardUpdateMonitor( 1173): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1173): handleTimeUpdate
,D/KeyguardEffectViewController( 1173): onReceive action : android.intent.action.TIME_TICK
,I/KeyguardEffectViewController( 1173): *** don't update sliding image ***
,D/BatteryService(  918): level:100, scale:100, status:5, health:2, present:true, voltage: 4386, temperature: 298, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  918): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
D/BatteryService(  918): stay LED for fully charged
,D/BatteryService(  918): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1173): received broadcast android.intent.action.BATTERY_CHANGED
,D/MotionRecognitionService(  918):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  918): Plugged
I/MotionRecognitionService(  918): setPowerConnected  = true
,V/HeadsetService( 3229): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3229): Disconnected process message: 10
,D/STATUSBAR-PhoneStatusBar( 1173):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1173): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1173): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1173): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/KeyguardUpdateMonitor( 1173): handleBatteryUpdate
,D/ConnectivityService(  918): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  918): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/DateView( 1173): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1173): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,V/GLSActivity( 1739): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ConnectivityService(  918): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/SMD     (  280): DCD ON
,I/VacuumService( 1739): Vacuum at: now=1450658043706 tag=VacuumService
,D/ConnectivityService(  918): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/GoogleURLConnFactory( 1739): Using platform SSLCertificateSocketFactory
,D/ConnectivityService(  918): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/GLSUser ( 1739): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
,I/GLSUser ( 1739): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1739): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1739): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1739): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/BitmapFactory( 1739): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/common_ic_googleplayservices.png
,V/BitmapFactory( 1739): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  918): uri = 14 selection = getSealedState
D/SecContentProvider2(  918): mCursor = null
,D/SecContentProvider2(  918): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  918): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
V/ApplicationPolicy(  918): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/StatusBar( 1173): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,E/Uploader( 1739): Failed to get auth token: User intervention required. Notification has been pushed.
E/Uploader( 1739): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
E/Uploader( 1739): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
E/Uploader( 1739): 	at com.google.android.gms.auth.p.d(SourceFile:599)
E/Uploader( 1739): 	at com.google.android.gms.auth.p.c(SourceFile:550)
E/Uploader( 1739): 	at com.google.android.gms.auth.p.b(SourceFile:477)
E/Uploader( 1739): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:508)
E/Uploader( 1739): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:337)
E/Uploader( 1739): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:263)
E/Uploader( 1739): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:235)
E/Uploader( 1739): 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:125)
E/Uploader( 1739): 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:78)
E/Uploader( 1739): 	at com.google.android.gms.gcm.am.run(SourceFile:135)
,I/PhoneStatusBar( 1173): Icon Only
D/LockPatternUtilsCache( 1173): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1173): value : false
D/PanelView( 1173): There is/are notification(s) 
,D/PanelView( 1173): There is/are notification(s) 
,I/System.out( 1739): (HTTPLog)-Static: SBServiceAPI: getService class android.os.ServiceManager
,I/System.out( 1739): (HTTPLog)-Static: isShipBuild true
,I/System.out( 1739): (HTTPLog)-Thread-211-24768479: SmartBonding Enabling is true, SHIP_BUILD is true, log to file is false, DBG is false
,I/qtaguid ( 1739): Tagging socket 57 with tag 120100000000{4609,0} uid -1, pid: 1739, getuid(): 10012
,V/GLSActivity( 1739): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/qtaguid ( 1739): Tagging socket 61 with tag 120100000000{4609,0} uid -1, pid: 1739, getuid(): 10012
,I/GLSUser ( 1739): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
,I/GLSUser ( 1739): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1739): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1739): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1739): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/Finsky  ( 6619): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,D/Finsky  ( 6619): [1] 5.onFinished: Installation state replication failed.
,D/Finsky  ( 6619): [1] 5.onFinished: Giving up after 6 failures.
,W/Uploader( 1739): No account for auth token provided
,I/qtaguid ( 1739): Tagging socket 57 with tag 120100000000{4609,0} uid -1, pid: 1739, getuid(): 10012
,W/Uploader( 1739): No account for auth token provided
,I/qtaguid ( 1739): Tagging socket 57 with tag 120100000000{4609,0} uid -1, pid: 1739, getuid(): 10012
,W/Uploader( 1739): No account for auth token provided
,I/qtaguid ( 1739): Tagging socket 57 with tag 120100000000{4609,0} uid -1, pid: 1739, getuid(): 10012
,W/Uploader( 1739):  no longer exists, so no auth token.
,I/qtaguid ( 1739): Tagging socket 57 with tag 120100000000{4609,0} uid -1, pid: 1739, getuid(): 10012
,D/ConnectivityService(  918): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/ServiceManager(  323): Waiting for service AtCmdFwd...
,E/SQLiteLog( 1739): (10) POSIX Error : 11 SQLite Error : 3850
,I/ServiceManager(  323): Waiting for service AtCmdFwd...
,E/SMD     (  280): DCD ON
,I/ServiceManager(  323): Waiting for service AtCmdFwd...
,V/AlarmManager(  918): waitForAlarm result :4
,D/ConnectivityService(  918): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  918): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/BooksSync( 7348): Starting books sync, d
,D/ConnectivityService(  918): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,V/GLSActivity( 1739): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1739): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
,I/GLSUser ( 1739): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1739): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1739): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1739): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ResourcesManager( 1739): creating new AssetManager and set to /system/app/Books/Books.apk
,V/BitmapFactory( 1739): DecodeImagePath(decodeResourceStream3) : res/mipmap-xxhdpi-v4/ic_launcher_play_books.png
,V/BitmapFactory( 1739): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  918): uri = 14 selection = getSealedState
,D/SecContentProvider2(  918): mCursor = null
D/SecContentProvider2(  918): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  918): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy(  918): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/StatusBar( 1173): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,I/PhoneStatusBar( 1173): Icon Only
,D/LockPatternUtilsCache( 1173): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1173): value : false
D/PanelView( 1173): There is/are notification(s) 
,D/PanelView( 1173): There is/are notification(s) 
,W/GLSActivity( 1739): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1739): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1739): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1739): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1739): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1739): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1739): 	at android.os.Binder.execTransact(Binder.java:446)
,E/BooksAccountManager( 7348): Authentication error
E/BooksAccountManager( 7348): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 7348): android.accounts.AccountManager.convertErrorToException(AccountManager.java:1893)
,E/HttpHelper( 7348): null auth token
,I/qtaguid ( 7348): Tagging socket 34 with tag 10000000000{256,0} uid -1, pid: 7348, getuid(): 10082
,I/qtaguid ( 7348): Tagging socket 34 with tag 10000000000{256,0} uid -1, pid: 7348, getuid(): 10082
,I/qtaguid ( 7348): Untagging socket 34
,W/ApiaryClient( 7348): Error response from books API: {
W/ApiaryClient( 7348):  "error": {
W/ApiaryClient( 7348):   "errors": [
W/ApiaryClient( 7348):    {
W/ApiaryClient( 7348):     "domain": "global",
W/ApiaryClient( 7348):     "reason": "required",
W/ApiaryClient( 7348):     "message": "Login Required",
W/ApiaryClient( 7348):     "locationType": "header",
W/ApiaryClient( 7348):     "location": "Authorization"
W/ApiaryClient( 7348):    }
W/ApiaryClient( 7348):   ],
W/ApiaryClient( 7348):   "code": 401,
W/ApiaryClient( 7348):   "message": "Login Required"
W/ApiaryClient( 7348):  }
W/ApiaryClient( 7348): }
,W/ApiaryClient( 7348): errCount = 1: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 7348): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3DS0HXd4TFLU4&nonce=5212688708416479734&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 7348): Headers suppressed
,D/ConnectivityService(  918): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/ServiceManager(  323): Waiting for service AtCmdFwd...
,V/GLSActivity( 1739): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1739): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
,I/GLSUser ( 1739): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1739): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1739): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1739): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/BitmapFactory( 1739): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,I/ServiceManager(  323): Waiting for service AtCmdFwd...
,D/SecContentProvider2(  918): uri = 14 selection = getSealedState
,D/SecContentProvider2(  918): mCursor = null
D/SecContentProvider2(  918): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  918): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy(  918): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/StatusBar( 1173): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,I/PhoneStatusBar( 1173): Icon Only
,D/LockPatternUtilsCache( 1173): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1173): value : false
D/PanelView( 1173): There is/are notification(s) 
,D/PanelView( 1173): There is/are notification(s) 
,W/GLSActivity( 1739): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1739): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1739): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1739): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1739): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1739): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1739): 	at android.os.Binder.execTransact(Binder.java:446)
,E/BooksAccountManager( 7348): Authentication error
E/BooksAccountManager( 7348): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 7348): android.accounts.AccountManager.convertErrorToException(AccountManager.java:1893)
,E/HttpHelper( 7348): null auth token
,I/qtaguid ( 7348): Tagging socket 34 with tag 10000000000{256,0} uid -1, pid: 7348, getuid(): 10082
,I/qtaguid ( 7348): Tagging socket 39 with tag 10000000000{256,0} uid -1, pid: 7348, getuid(): 10082
,I/qtaguid ( 7348): Untagging socket 34
,W/ApiaryClient( 7348): Error response from books API: {
W/ApiaryClient( 7348):  "error": {
W/ApiaryClient( 7348):   "errors": [
W/ApiaryClient( 7348):    {
W/ApiaryClient( 7348):     "domain": "global",
W/ApiaryClient( 7348):     "reason": "required",
W/ApiaryClient( 7348):     "message": "Login Required",
W/ApiaryClient( 7348):     "locationType": "header",
W/ApiaryClient( 7348):     "location": "Authorization"
W/ApiaryClient( 7348):    }
W/ApiaryClient( 7348):   ],
W/ApiaryClient( 7348):   "code": 401,
W/ApiaryClient( 7348):   "message": "Login Required"
W/ApiaryClient( 7348):  }
W/ApiaryClient( 7348): }
,W/ApiaryClient( 7348): errCount = 2: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 7348): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3DS0HXd4TFLU4&nonce=5212688708416479734&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 7348): Headers suppressed
,D/ConnectivityService(  918): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SSRM:m  (  918): SIOP:: AP = 310, PST = 345, CUR = 300
,I/PowerManagerService(  918): [PWL] Off : 50s ago
,I/PowerManagerService(  918): [PWL]   PowerManagerService.WakeLocks: ref count=1
,I/PowerManagerService(  918): [PWL]     mWakeLockSummary : 0x1
,I/PowerManagerService(  918): [PWL]       PARTIAL_WAKE_LOCK              '*sync*/com.google.android.apps.books/com.google/eM_ADDR' (uid=1000, pid=918, ws=WorkSource{10082}) (elapsedTime=1933),
,E/SMD     (  280): DCD ON
,W/Atfwd_Sendcmd(  323): AtCmdFwd service not published, waiting... retryCnt : 5
,V/GLSActivity( 1739): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1739): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
,I/GLSUser ( 1739): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1739): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1739): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1739): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/BitmapFactory( 1739): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  918): uri = 14 selection = getSealedState
,D/SecContentProvider2(  918): mCursor = null
D/SecContentProvider2(  918): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  918): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy(  918): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/StatusBar( 1173): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,I/PhoneStatusBar( 1173): Icon Only
,D/LockPatternUtilsCache( 1173): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1173): value : false
D/PanelView( 1173): There is/are notification(s) 
,D/PanelView( 1173): There is/are notification(s) 
,W/GLSActivity( 1739): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1739): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1739): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1739): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1739): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1739): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1739): 	at android.os.Binder.execTransact(Binder.java:446)
,E/BooksAccountManager( 7348): Authentication error
E/BooksAccountManager( 7348): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 7348): android.accounts.AccountManager.convertErrorToException(AccountManager.java:1893)
,E/HttpHelper( 7348): null auth token
,I/qtaguid ( 7348): Tagging socket 34 with tag 10000000000{256,0} uid -1, pid: 7348, getuid(): 10082
,I/qtaguid ( 7348): Untagging socket 34
,W/ApiaryClient( 7348): Error response from books API: {
W/ApiaryClient( 7348):  "error": {
W/ApiaryClient( 7348):   "errors": [
W/ApiaryClient( 7348):    {
W/ApiaryClient( 7348):     "domain": "global",
W/ApiaryClient( 7348):     "reason": "required",
W/ApiaryClient( 7348):     "message": "Login Required",
W/ApiaryClient( 7348):     "locationType": "header",
W/ApiaryClient( 7348):     "location": "Authorization"
W/ApiaryClient( 7348):    }
W/ApiaryClient( 7348):   ],
W/ApiaryClient( 7348):   "code": 401,
W/ApiaryClient( 7348):   "message": "Login Required"
W/ApiaryClient( 7348):  }
W/ApiaryClient( 7348): }
,W/ApiaryClient( 7348): errCount = 3: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 7348): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3DS0HXd4TFLU4&nonce=5212688708416479734&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 7348): Headers suppressed
,D/ConnectivityService(  918): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/BooksSync( 7348): Soft error
E/BooksSync( 7348): com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
E/BooksSync( 7348): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3DS0HXd4TFLU4&nonce=5212688708416479734&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
E/BooksSync( 7348): Headers suppressed
E/BooksSync( 7348): 
E/BooksSync( 7348): com.google.android.apps.books.net.HttpHelper.wrapExceptionBasedOnStatus(HttpHelper.java:212)
,E/BooksSync( 7348): Sync error
E/BooksSync( 7348): com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
E/BooksSync( 7348): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3DS0HXd4TFLU4&nonce=5212688708416479734&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
E/BooksSync( 7348): Headers suppressed
E/BooksSync( 7348): 
E/BooksSync( 7348): com.google.android.apps.books.net.HttpHelper.wrapExceptionBasedOnStatus(HttpHelper.java:212)
,I/BooksSync( 7348): Finished books sync
,D/ConnectivityService(  918): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SyncManager(  918): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 161795, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,D/ConnectivityService(  918): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  918): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/art     (  918): Explicit concurrent mark sweep GC freed 40789(2MB) AllocSpace objects, 24(839KB) LOS objects, 30% free, 36MB/52MB, paused 1.602ms total 121.988ms
,D/SecContentProvider2(  918): uri = 11 selection = getMyKnoxAdmin
,D/SecContentProvider2(  918): mCursor = null
,D/ConnectivityService(  918): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/GLSUser ( 1739): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,I/GLSUser ( 1739): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1739): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1739): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1739): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ResourcesManager( 1739): creating new AssetManager and set to /system/app/PlusOne/PlusOne.apk
,V/BitmapFactory( 1739): DecodeImagePath(decodeResourceStream3) : res/mipmap-xxhdpi-v4/quantum_logo_google_plus_color_44in48.png
,V/BitmapFactory( 1739): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  918): uri = 14 selection = getSealedState
D/SecContentProvider2(  918): mCursor = null
,D/SecContentProvider2(  918): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  918): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
V/ApplicationPolicy(  918): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/StatusBar( 1173): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,E/HttpOperation( 6592): [kfu{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
E/HttpOperation( 6592): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 6592): 	at kfv.a(PG:65)
E/HttpOperation( 6592): 	at kff.u(PG:385)
E/HttpOperation( 6592): 	at kfb.a(PG:29)
E/HttpOperation( 6592): 	at kff.l(PG:132)
E/HttpOperation( 6592): 	at dsf.a(PG:807)
E/HttpOperation( 6592): 	at fhk.a(PG:1126)
E/HttpOperation( 6592): 	at fhk.a(PG:908)
E/HttpOperation( 6592): 	at fhk.onPerformSync(PG:636)
E/HttpOperation( 6592): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/HttpOperation( 6592): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/HttpOperation( 6592): 	at ihi.a(PG:22)
E/HttpOperation( 6592): 	at kft.a(PG:91)
E/HttpOperation( 6592): 	at kfv.a(PG:62)
E/HttpOperation( 6592): 	... 8 more
E/HttpOperation( 6592): Caused by: gdi: User intervention required. Notification has been pushed.
E/HttpOperation( 6592): 	at gde.c(Unknown Source)
E/HttpOperation( 6592): 	at gde.b(Unknown Source)
E/HttpOperation( 6592): 	at ihi.a(PG:19)
E/HttpOperation( 6592): 	... 10 more
,I/PhoneStatusBar( 1173): Icon Only
D/LockPatternUtilsCache( 1173): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1173): value : false
D/PanelView( 1173): There is/are notification(s) 
D/PanelView( 1173): There is/are notification(s) 
,I/GLSUser ( 1739): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,I/GLSUser ( 1739): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1739): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1739): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1739): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/BitmapFactory( 1739): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  918): uri = 14 selection = getSealedState
,D/SecContentProvider2(  918): mCursor = null
,D/SecContentProvider2(  918): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  918): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy(  918): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/StatusBar( 1173): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,E/HttpOperation( 6592): [getmobileexperiments] Unexpected exception
E/HttpOperation( 6592): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 6592): 	at kfv.a(PG:65)
E/HttpOperation( 6592): 	at kff.u(PG:385)
E/HttpOperation( 6592): 	at kfb.a(PG:29)
E/HttpOperation( 6592): 	at kff.l(PG:132)
E/HttpOperation( 6592): 	at ieo.a(PG:43)
E/HttpOperation( 6592): 	at iep.a(PG:93)
E/HttpOperation( 6592): 	at fhn.a(PG:59)
E/HttpOperation( 6592): 	at lex.a(PG:85)
E/HttpOperation( 6592): 	at lex.b(PG:132)
E/HttpOperation( 6592): 	at fhk.a(PG:1146)
E/HttpOperation( 6592): 	at fhk.a(PG:908)
E/HttpOperation( 6592): 	at fhk.onPerformSync(PG:636)
E/HttpOperation( 6592): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/HttpOperation( 6592): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/HttpOperation( 6592): 	at ihi.a(PG:22)
E/HttpOperation( 6592): 	at kft.a(PG:91)
E/HttpOperation( 6592): 	at kfv.a(PG:62)
E/HttpOperation( 6592): 	... 12 more
E/HttpOperation( 6592): Caused by: gdi: User intervention required. Notification has been pushed.
E/HttpOperation( 6592): 	at gde.c(Unknown Source)
E/HttpOperation( 6592): 	at gde.b(Unknown Source)
E/HttpOperation( 6592): 	at ihi.a(PG:19)
E/HttpOperation( 6592): 	... 14 more
,E/ExperimentLoader( 6592): [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 6592): java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 6592): 	at kfv.a(PG:65)
E/ExperimentLoader( 6592): 	at kff.u(PG:385)
E/ExperimentLoader( 6592): 	at kfb.a(PG:29)
E/ExperimentLoader( 6592): 	at kff.l(PG:132)
E/ExperimentLoader( 6592): 	at ieo.a(PG:43)
E/ExperimentLoader( 6592): 	at iep.a(PG:93)
E/ExperimentLoader( 6592): 	at fhn.a(PG:59)
E/ExperimentLoader( 6592): 	at lex.a(PG:85)
E/ExperimentLoader( 6592): 	at lex.b(PG:132)
E/ExperimentLoader( 6592): 	at fhk.a(PG:1146)
E/ExperimentLoader( 6592): 	at fhk.a(PG:908)
E/ExperimentLoader( 6592): 	at fhk.onPerformSync(PG:636)
E/ExperimentLoader( 6592): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/ExperimentLoader( 6592): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/ExperimentLoader( 6592): 	at ihi.a(PG:22)
E/ExperimentLoader( 6592): 	at kft.a(PG:91)
E/ExperimentLoader( 6592): 	at kfv.a(PG:62)
E/ExperimentLoader( 6592): 	... 12 more
E/ExperimentLoader( 6592): Caused by: gdi: User intervention required. Notification has been pushed.
E/ExperimentLoader( 6592): 	at gde.c(Unknown Source)
E/ExperimentLoader( 6592): 	at gde.b(Unknown Source)
E/ExperimentLoader( 6592): 	at ihi.a(PG:19)
E/ExperimentLoader( 6592): 	... 14 more
I/PhoneStatusBar( 1173): Icon Only
D/LockPatternUtilsCache( 1173): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1173): value : false
D/PanelView( 1173): There is/are notification(s) 
D/PanelView( 1173): There is/are notification(s) 
,I/GLSUser ( 1739): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,I/GLSUser ( 1739): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1739): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1739): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1739): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/BitmapFactory( 1739): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  918): uri = 14 selection = getSealedState
,D/SecContentProvider2(  918): mCursor = null
,D/SecContentProvider2(  918): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  918): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
V/ApplicationPolicy(  918): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,E/HttpOperation( 6592): [getaccountstatus] Unexpected exception
E/HttpOperation( 6592): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 6592): 	at kfv.a(PG:65)
E/HttpOperation( 6592): 	at kff.u(PG:385)
E/HttpOperation( 6592): 	at kfb.a(PG:29)
E/HttpOperation( 6592): 	at ixd.a(PG:248)
E/HttpOperation( 6592): 	at ixd.b(PG:206)
E/HttpOperation( 6592): 	at ixd.a(PG:175)
E/HttpOperation( 6592): 	at fig.a(PG:78)
E/HttpOperation( 6592): 	at lex.a(PG:85)
E/HttpOperation( 6592): 	at lex.b(PG:132)
E/HttpOperation( 6592): 	at fhk.a(PG:1146)
E/HttpOperation( 6592): 	at fhk.a(PG:908)
E/HttpOperation( 6592): 	at fhk.onPerformSync(PG:636)
E/HttpOperation( 6592): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/HttpOperation( 6592): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/HttpOperation( 6592): 	at ihi.a(PG:22)
E/HttpOperation( 6592): 	at kft.a(PG:91)
E/HttpOperation( 6592): 	at kfv.a(PG:62)
E/HttpOperation( 6592): 	... 12 more
E/HttpOperation( 6592): Caused by: gdi: User intervention required. Notification has been pushed.
E/HttpOperation( 6592): 	at gde.c(Unknown Source)
E/HttpOperation( 6592): 	at gde.b(Unknown Source)
E/HttpOperation( 6592): 	at ihi.a(PG:19)
E/HttpOperation( 6592): 	... 14 more
,E/EsSyncAdapterService( 6592): Sync failure
E/EsSyncAdapterService( 6592): java.io.IOException: Rpc failed
E/EsSyncAdapterService( 6592): 	at ixd.a(PG:348)
E/EsSyncAdapterService( 6592): 	at ixd.a(PG:248)
E/EsSyncAdapterService( 6592): 	at ixd.b(PG:206)
E/EsSyncAdapterService( 6592): 	at ixd.a(PG:175)
E/EsSyncAdapterService( 6592): 	at fig.a(PG:78)
E/EsSyncAdapterService( 6592): 	at lex.a(PG:85)
E/EsSyncAdapterService( 6592): 	at lex.b(PG:132)
E/EsSyncAdapterService( 6592): 	at fhk.a(PG:1146)
E/EsSyncAdapterService( 6592): 	at fhk.a(PG:908)
E/EsSyncAdapterService( 6592): 	at fhk.onPerformSync(PG:636)
E/EsSyncAdapterService( 6592): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/EsSyncAdapterService( 6592): Caused by: java.io.IOException: Cannot obtain authentication token
E/EsSyncAdapterService( 6592): 	at kfv.a(PG:65)
E/EsSyncAdapterService( 6592): 	at kff.u(PG:385)
E/EsSyncAdapterService( 6592): 	at kfb.a(PG:29)
E/EsSyncAdapterService( 6592): 	... 10 more
E/EsSyncAdapterService( 6592): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/EsSyncAdapterService( 6592): 	at ihi.a(PG:22)
E/EsSyncAdapterService( 6592): 	at kft.a(PG:91)
E/EsSyncAdapterService( 6592): 	at kfv.a(PG:62)
E/EsSyncAdapterService( 6592): 	... 12 more
E/EsSyncAdapterService( 6592): Caused by: gdi: User intervention required. Notification has been pushed.
E/EsSyncAdapterService( 6592): 	at gde.c(Unknown Source)
E/EsSyncAdapterService( 6592): 	at gde.b(Unknown Source)
E/EsSyncAdapterService( 6592): 	at ihi.a(PG:19)
E/EsSyncAdapterService( 6592): 	... 14 more
,D/ConnectivityService(  918): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/StatusBar( 1173): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,E/SQLiteLog( 1739): (10) POSIX Error : 11 SQLite Error : 3850
,I/PhoneStatusBar( 1173): Icon Only
,D/LockPatternUtilsCache( 1173): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1173): value : false
D/PanelView( 1173): There is/are notification(s) 
,D/PanelView( 1173): There is/are notification(s) 
,D/SyncManager(  918): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, PERIODIC, currentRunTime 186639, reason: Periodic, SyncResult: stats [ numIoExceptions: 2]
,D/ConnectivityService(  918): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  918): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SecContentProvider2(  918): uri = 11 selection = getMyKnoxAdmin
,D/SecContentProvider2(  918): mCursor = null
,E/SMD     (  280): DCD ON
,D/BatteryService(  918): level:100, scale:100, status:5, health:2, present:true, voltage: 4383, temperature: 298, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  918): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  918): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  918):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  918): Plugged
,I/MotionRecognitionService(  918): setPowerConnected  = true
,D/BatteryService(  918): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1173): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1173): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1173):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3229): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3229): Disconnected process message: 10
,D/BatteryMeterView( 1173): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1173): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1173): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,W/ContextImpl(  918): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  280): DCD ON
,E/Watchdog(  918): !@Sync 6
,E/SMD     (  280): DCD ON
,D/SSRM:m  (  918): SIOP:: AP = 310, PST = 337, CUR = 300
,E/SMD     (  280): DCD ON
,D/BatteryService(  918): level:100, scale:100, status:5, health:2, present:true, voltage: 4383, temperature: 297, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  918): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  918): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  918):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  918): Plugged
,I/MotionRecognitionService(  918): setPowerConnected  = true,
,D/BatteryService(  918): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1173): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1173): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1173):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3229): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3229): Disconnected process message: 10
,D/BatteryMeterView( 1173): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1173): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1173): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  280): DCD ON
,E/SMD     (  280): DCD ON
,D/SSRM:m  (  918): SIOP:: AP = 310, PST = 327, CUR = 300
,E/SMD     (  280): DCD ON
,E/SMD     (  280): DCD ON
,I/PowerManagerService(  918): [PWL] Off : 75s ago
,W/ContextImpl(  918): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/Atfwd_Sendcmd(  323): AtCmdFwd service not ready - Exhausted retry attempts - :6
I/Atfwd_Daemon(  323): result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,E/SMD     (  280): DCD ON
,V/AlarmManager(  918): waitForAlarm result :4
,D/ConnectivityService(  918): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SSRM:m  (  918): SIOP:: AP = 300, PST = 320, CUR = 300
,E/SMD     (  280): DCD ON
,E/SMD     (  280): DCD ON
,I/ServiceManager(  323): Waiting for service AtCmdFwd...
,E/SMD     (  280): DCD ON
,E/Watchdog(  918): !@Sync 7
,I/ServiceManager(  323): Waiting for service AtCmdFwd...
,I/ServiceManager(  323): Waiting for service AtCmdFwd...
,I/ServiceManager(  323): Waiting for service AtCmdFwd...
,E/SMD     (  280): DCD ON
,I/ServiceManager(  323): Waiting for service AtCmdFwd...
,D/SSRM:m  (  918): SIOP:: AP = 300, PST = 315, CUR = 300
,W/Atfwd_Sendcmd(  323): AtCmdFwd service not published, waiting... retryCnt : 1
,E/SMD     (  280): DCD ON
,W/ContextImpl(  918): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  280): DCD ON
,I/ServiceManager(  323): Waiting for service AtCmdFwd...
,I/ServiceManager(  323): Waiting for service AtCmdFwd...
,I/ServiceManager(  323): Waiting for service AtCmdFwd...
,E/SMD     (  280): DCD ON
,I/ServiceManager(  323): Waiting for service AtCmdFwd...
,I/ServiceManager(  323): Waiting for service AtCmdFwd...
,D/SSRM:m  (  918): SIOP:: AP = 300, PST = 311, CUR = 300
,W/Atfwd_Sendcmd(  323): AtCmdFwd service not published, waiting... retryCnt : 2
,V/AlarmManager(  918): waitForAlarm result :8
,E/SMD     (  280): DCD ON
,E/SMD     (  280): DCD ON
,I/PowerManagerService(  918): [PWL] Off : 105s ago
,E/SMD     (  280): DCD ON
,V/AlarmManager(  918): waitForAlarm result :4
,D/KeyguardUpdateMonitor( 1173): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1173): handleTimeUpdate
,D/KeyguardEffectViewController( 1173): onReceive action : android.intent.action.TIME_TICK
,I/KeyguardEffectViewController( 1173): *** don't update sliding image ***
,D/BatteryService(  918): level:100, scale:100, status:5, health:2, present:true, voltage: 4386, temperature: 297, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  918): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
D/BatteryService(  918): stay LED for fully charged
,D/BatteryService(  918): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1173): received broadcast android.intent.action.BATTERY_CHANGED
,D/STATUSBAR-PhoneStatusBar( 1173):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3229): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3229): Disconnected process message: 10
D/MotionRecognitionService(  918):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  918): Plugged
I/MotionRecognitionService(  918): setPowerConnected  = true
,D/BatteryMeterView( 1173): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1173): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1173): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/KeyguardUpdateMonitor( 1173): handleBatteryUpdate
,D/DateView( 1173): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1173): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/ConnectivityService(  918): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  918): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/BooksSync( 7348): Starting books sync, d
,D/ConnectivityService(  918): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,V/GLSActivity( 1739): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1739): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
,I/GLSUser ( 1739): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1739): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1739): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1739): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/BitmapFactory( 1739): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  918): uri = 14 selection = getSealedState
D/SecContentProvider2(  918): mCursor = null
,D/SecContentProvider2(  918): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  918): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy(  918): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,W/GLSActivity( 1739): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1739): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1739): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1739): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1739): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1739): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1739): 	at android.os.Binder.execTransact(Binder.java:446)
,E/BooksAccountManager( 7348): Authentication error
E/BooksAccountManager( 7348): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 7348): android.accounts.AccountManager.convertErrorToException(AccountManager.java:1893)
E/HttpHelper( 7348): null auth token
,I/qtaguid ( 7348): Tagging socket 34 with tag 10000000000{256,0} uid -1, pid: 7348, getuid(): 10082
,D/StatusBar( 1173): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,I/PhoneStatusBar( 1173): Icon Only
D/LockPatternUtilsCache( 1173): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1173): value : false
D/PanelView( 1173): There is/are notification(s) 
,D/PanelView( 1173): There is/are notification(s) 
,I/qtaguid ( 7348): Untagging socket 34
,W/ApiaryClient( 7348): Error response from books API: {
W/ApiaryClient( 7348):  "error": {
W/ApiaryClient( 7348):   "errors": [
W/ApiaryClient( 7348):    {
W/ApiaryClient( 7348):     "domain": "global",
W/ApiaryClient( 7348):     "reason": "required",
W/ApiaryClient( 7348):     "message": "Login Required",
W/ApiaryClient( 7348):     "locationType": "header",
W/ApiaryClient( 7348):     "location": "Authorization"
W/ApiaryClient( 7348):    }
W/ApiaryClient( 7348):   ],
W/ApiaryClient( 7348):   "code": 401,
W/ApiaryClient( 7348):   "message": "Login Required"
W/ApiaryClient( 7348):  }
W/ApiaryClient( 7348): }
,W/ApiaryClient( 7348): errCount = 1: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 7348): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3DS0HXd4TFLU4&nonce=3106276310341955032&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 7348): Headers suppressed
,D/ConnectivityService(  918): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,V/GLSActivity( 1739): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1739): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
,I/GLSUser ( 1739): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1739): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1739): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1739): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/BitmapFactory( 1739): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  918): uri = 14 selection = getSealedState
,D/SecContentProvider2(  918): mCursor = null
D/SecContentProvider2(  918): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  918): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy(  918): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/StatusBar( 1173): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,I/PhoneStatusBar( 1173): Icon Only
,D/LockPatternUtilsCache( 1173): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1173): value : false
D/PanelView( 1173): There is/are notification(s) 
,D/PanelView( 1173): There is/are notification(s) 
,W/GLSActivity( 1739): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1739): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1739): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1739): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1739): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1739): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1739): 	at android.os.Binder.execTransact(Binder.java:446)
,E/BooksAccountManager( 7348): Authentication error
E/BooksAccountManager( 7348): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 7348): android.accounts.AccountManager.convertErrorToException(AccountManager.java:1893)
,E/HttpHelper( 7348): null auth token
,I/qtaguid ( 7348): Tagging socket 34 with tag 10000000000{256,0} uid -1, pid: 7348, getuid(): 10082
,I/qtaguid ( 7348): Untagging socket 34
,W/ApiaryClient( 7348): Error response from books API: {
W/ApiaryClient( 7348):  "error": {
W/ApiaryClient( 7348):   "errors": [
W/ApiaryClient( 7348):    {
W/ApiaryClient( 7348):     "domain": "global",
W/ApiaryClient( 7348):     "reason": "required",
W/ApiaryClient( 7348):     "message": "Login Required",
W/ApiaryClient( 7348):     "locationType": "header",
W/ApiaryClient( 7348):     "location": "Authorization"
W/ApiaryClient( 7348):    }
W/ApiaryClient( 7348):   ],
W/ApiaryClient( 7348):   "code": 401,
W/ApiaryClient( 7348):   "message": "Login Required"
W/ApiaryClient( 7348):  }
W/ApiaryClient( 7348): }
,W/ApiaryClient( 7348): errCount = 2: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 7348): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3DS0HXd4TFLU4&nonce=3106276310341955032&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 7348): Headers suppressed
,D/ConnectivityService(  918): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SSRM:m  (  918): SIOP:: AP = 300, PST = 308, CUR = 300
,E/SMD     (  280): DCD ON
,I/ServiceManager(  323): Waiting for service AtCmdFwd...
,V/GLSActivity( 1739): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1739): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
,I/GLSUser ( 1739): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1739): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1739): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1739): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/BitmapFactory( 1739): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  918): uri = 14 selection = getSealedState
,D/SecContentProvider2(  918): mCursor = null
D/SecContentProvider2(  918): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  918): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy(  918): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/StatusBar( 1173): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,I/PhoneStatusBar( 1173): Icon Only
,D/LockPatternUtilsCache( 1173): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1173): value : false
D/PanelView( 1173): There is/are notification(s) 
,D/PanelView( 1173): There is/are notification(s) 
,W/GLSActivity( 1739): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1739): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1739): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1739): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1739): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1739): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1739): 	at android.os.Binder.execTransact(Binder.java:446)
,E/BooksAccountManager( 7348): Authentication error
E/BooksAccountManager( 7348): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 7348): android.accounts.AccountManager.convertErrorToException(AccountManager.java:1893)
,E/HttpHelper( 7348): null auth token
,I/qtaguid ( 7348): Tagging socket 34 with tag 10000000000{256,0} uid -1, pid: 7348, getuid(): 10082
,I/qtaguid ( 7348): Untagging socket 34
,W/ApiaryClient( 7348): Error response from books API: {
W/ApiaryClient( 7348):  "error": {
W/ApiaryClient( 7348):   "errors": [
W/ApiaryClient( 7348):    {
W/ApiaryClient( 7348):     "domain": "global",
W/ApiaryClient( 7348):     "reason": "required",
W/ApiaryClient( 7348):     "message": "Login Required",
W/ApiaryClient( 7348):     "locationType": "header",
W/ApiaryClient( 7348):     "location": "Authorization"
W/ApiaryClient( 7348):    }
W/ApiaryClient( 7348):   ],
W/ApiaryClient( 7348):   "code": 401,
W/ApiaryClient( 7348):   "message": "Login Required"
W/ApiaryClient( 7348):  }
W/ApiaryClient( 7348): }
,W/ApiaryClient( 7348): errCount = 3: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 7348): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3DS0HXd4TFLU4&nonce=3106276310341955032&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 7348): Headers suppressed
,D/ConnectivityService(  918): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/ServiceManager(  323): Waiting for service AtCmdFwd...
,E/BooksSync( 7348): Soft error
E/BooksSync( 7348): com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
E/BooksSync( 7348): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3DS0HXd4TFLU4&nonce=3106276310341955032&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
E/BooksSync( 7348): Headers suppressed
E/BooksSync( 7348): 
E/BooksSync( 7348): com.google.android.apps.books.net.HttpHelper.wrapExceptionBasedOnStatus(HttpHelper.java:212)
,E/BooksSync( 7348): Sync error
E/BooksSync( 7348): com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
E/BooksSync( 7348): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3DS0HXd4TFLU4&nonce=3106276310341955032&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
E/BooksSync( 7348): Headers suppressed
E/BooksSync( 7348): 
E/BooksSync( 7348): com.google.android.apps.books.net.HttpHelper.wrapExceptionBasedOnStatus(HttpHelper.java:212)
,I/BooksSync( 7348): Finished books sync
,D/ConnectivityService(  918): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SyncManager(  918): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 222185, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,D/ConnectivityService(  918): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SecContentProvider2(  918): uri = 11 selection = getMyKnoxAdmin
,D/SecContentProvider2(  918): mCursor = null
,I/ServiceManager(  323): Waiting for service AtCmdFwd...
,D/ConnectivityService(  918): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/SMD     (  280): DCD ON
,I/ServiceManager(  323): Waiting for service AtCmdFwd...
,I/ServiceManager(  323): Waiting for service AtCmdFwd...
,W/ContextImpl(  918): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,W/Atfwd_Sendcmd(  323): AtCmdFwd service not published, waiting... retryCnt : 3
,E/SMD     (  280): DCD ON
,E/Watchdog(  918): !@Sync 8
,D/BatteryService(  918): level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 296, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  918): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  918): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  918):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  918): Plugged
,I/MotionRecognitionService(  918): setPowerConnected  = true
,D/BatteryService(  918): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1173): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1173): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1173):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3229): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3229): Disconnected process message: 10
,D/BatteryMeterView( 1173): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1173): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1173): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  280): DCD ON
,D/SSRM:m  (  918): SIOP:: AP = 300, PST = 306, CUR = 300
,E/SMD     (  280): DCD ON
,E/SMD     (  280): DCD ON
,D/ConnectivityService(  918): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/SMD     (  280): DCD ON
,D/SSRM:m  (  918): SIOP:: AP = 300, PST = 304, CUR = 300
,I/ServiceManager(  323): Waiting for service AtCmdFwd...
,E/SMD     (  280): DCD ON
,I/ServiceManager(  323): Waiting for service AtCmdFwd...
,I/ServiceManager(  323): Waiting for service AtCmdFwd...
,I/ServiceManager(  323): Waiting for service AtCmdFwd...
,E/SMD     (  280): DCD ON
,I/ServiceManager(  323): Waiting for service AtCmdFwd...
,W/ContextImpl(  918): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,W/Atfwd_Sendcmd(  323): AtCmdFwd service not published, waiting... retryCnt : 4
,E/SMD     (  280): DCD ON
,V/AlarmManager(  918): waitForAlarm result :4
,D/ConnectivityService(  918): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  918): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/GLSUser ( 1739): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,I/GLSUser ( 1739): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1739): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1739): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1739): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/BitmapFactory( 1739): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  918): uri = 14 selection = getSealedState
,D/SecContentProvider2(  918): mCursor = null
D/SecContentProvider2(  918): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  918): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy(  918): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/StatusBar( 1173): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,I/PhoneStatusBar( 1173): Icon Only
,D/LockPatternUtilsCache( 1173): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1173): value : false
D/PanelView( 1173): There is/are notification(s) 
,D/PanelView( 1173): There is/are notification(s) 
,E/HttpOperation( 6592): [kfu{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
E/HttpOperation( 6592): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 6592): 	at kfv.a(PG:65)
E/HttpOperation( 6592): 	at kff.u(PG:385)
E/HttpOperation( 6592): 	at kfb.a(PG:29)
E/HttpOperation( 6592): 	at kff.l(PG:132)
E/HttpOperation( 6592): 	at dsf.a(PG:807)
E/HttpOperation( 6592): 	at fhk.a(PG:1126)
E/HttpOperation( 6592): 	at fhk.a(PG:908)
E/HttpOperation( 6592): 	at fhk.onPerformSync(PG:636)
E/HttpOperation( 6592): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/HttpOperation( 6592): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/HttpOperation( 6592): 	at ihi.a(PG:22)
E/HttpOperation( 6592): 	at kft.a(PG:91)
E/HttpOperation( 6592): 	at kfv.a(PG:62)
E/HttpOperation( 6592): 	... 8 more
E/HttpOperation( 6592): Caused by: gdi: User intervention required. Notification has been pushed.
E/HttpOperation( 6592): 	at gde.c(Unknown Source)
E/HttpOperation( 6592): 	at gde.b(Unknown Source)
E/HttpOperation( 6592): 	at ihi.a(PG:19)
E/HttpOperation( 6592): 	... 10 more
,I/GLSUser ( 1739): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,I/GLSUser ( 1739): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1739): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1739): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1739): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/BitmapFactory( 1739): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  918): uri = 14 selection = getSealedState
,D/SecContentProvider2(  918): mCursor = null
D/SecContentProvider2(  918): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  918): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy(  918): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/StatusBar( 1173): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,I/PhoneStatusBar( 1173): Icon Only
,D/LockPatternUtilsCache( 1173): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1173): value : false
D/PanelView( 1173): There is/are notification(s) 
D/PanelView( 1173): There is/are notification(s) 
,E/HttpOperation( 6592): [getmobileexperiments] Unexpected exception
E/HttpOperation( 6592): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 6592): 	at kfv.a(PG:65)
E/HttpOperation( 6592): 	at kff.u(PG:385)
E/HttpOperation( 6592): 	at kfb.a(PG:29)
E/HttpOperation( 6592): 	at kff.l(PG:132)
E/HttpOperation( 6592): 	at ieo.a(PG:43)
E/HttpOperation( 6592): 	at iep.a(PG:93)
E/HttpOperation( 6592): 	at fhn.a(PG:59)
E/HttpOperation( 6592): 	at lex.a(PG:85)
E/HttpOperation( 6592): 	at lex.b(PG:132)
E/HttpOperation( 6592): 	at fhk.a(PG:1146)
E/HttpOperation( 6592): 	at fhk.a(PG:908)
E/HttpOperation( 6592): 	at fhk.onPerformSync(PG:636)
,E/HttpOperation( 6592): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/HttpOperation( 6592): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/HttpOperation( 6592): 	at ihi.a(PG:22)
E/HttpOperation( 6592): 	at kft.a(PG:91)
E/HttpOperation( 6592): 	at kfv.a(PG:62)
E/HttpOperation( 6592): 	... 12 more
E/HttpOperation( 6592): Caused by: gdi: User intervention required. Notification has been pushed.
E/HttpOperation( 6592): 	at gde.c(Unknown Source)
E/HttpOperation( 6592): 	at gde.b(Unknown Source)
E/HttpOperation( 6592): 	at ihi.a(PG:19)
E/HttpOperation( 6592): 	... 14 more
,E/ExperimentLoader( 6592): [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 6592): java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 6592): 	at kfv.a(PG:65)
E/ExperimentLoader( 6592): 	at kff.u(PG:385)
E/ExperimentLoader( 6592): 	at kfb.a(PG:29)
E/ExperimentLoader( 6592): 	at kff.l(PG:132)
E/ExperimentLoader( 6592): 	at ieo.a(PG:43)
E/ExperimentLoader( 6592): 	at iep.a(PG:93)
E/ExperimentLoader( 6592): 	at fhn.a(PG:59)
E/ExperimentLoader( 6592): 	at lex.a(PG:85)
E/ExperimentLoader( 6592): 	at lex.b(PG:132)
E/ExperimentLoader( 6592): 	at fhk.a(PG:1146)
E/ExperimentLoader( 6592): 	at fhk.a(PG:908)
E/ExperimentLoader( 6592): 	at fhk.onPerformSync(PG:636)
E/ExperimentLoader( 6592): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/ExperimentLoader( 6592): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/ExperimentLoader( 6592): 	at ihi.a(PG:22)
E/ExperimentLoader( 6592): 	at kft.a(PG:91)
E/ExperimentLoader( 6592): 	at kfv.a(PG:62)
E/ExperimentLoader( 6592): 	... 12 more
E/ExperimentLoader( 6592): Caused by: gdi: User intervention required. Notification has been pushed.
E/ExperimentLoader( 6592): 	at gde.c(Unknown Source)
E/ExperimentLoader( 6592): 	at gde.b(Unknown Source)
E/ExperimentLoader( 6592): 	at ihi.a(PG:19)
E/ExperimentLoader( 6592): 	... 14 more
,I/art     ( 1739): Explicit concurrent mark sweep GC freed 49661(2MB) AllocSpace objects, 51(3MB) LOS objects, 39% free, 18MB/30MB, paused 591us total 37.348ms
,I/GLSUser ( 1739): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
I/GLSUser ( 1739): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1739): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1739): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1739): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ResourcesManager( 1739): creating new AssetManager and set to /system/app/PlusOne/PlusOne.apk
,V/BitmapFactory( 1739): DecodeImagePath(decodeResourceStream3) : res/mipmap-xxhdpi-v4/quantum_logo_google_plus_color_44in48.png
,V/BitmapFactory( 1739): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  918): uri = 14 selection = getSealedState
D/SecContentProvider2(  918): mCursor = null
,D/SecContentProvider2(  918): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  918): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
V/ApplicationPolicy(  918): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/StatusBar( 1173): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,I/PhoneStatusBar( 1173): Icon Only
D/LockPatternUtilsCache( 1173): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1173): value : false
D/PanelView( 1173): There is/are notification(s) 
D/PanelView( 1173): There is/are notification(s) 
,E/HttpOperation( 6592): [getaccountstatus] Unexpected exception
E/HttpOperation( 6592): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 6592): 	at kfv.a(PG:65)
E/HttpOperation( 6592): 	at kff.u(PG:385)
E/HttpOperation( 6592): 	at kfb.a(PG:29)
E/HttpOperation( 6592): 	at ixd.a(PG:248)
E/HttpOperation( 6592): 	at ixd.b(PG:206)
E/HttpOperation( 6592): 	at ixd.a(PG:175)
E/HttpOperation( 6592): 	at fig.a(PG:78)
E/HttpOperation( 6592): 	at lex.a(PG:85)
E/HttpOperation( 6592): 	at lex.b(PG:132)
E/HttpOperation( 6592): 	at fhk.a(PG:1146)
E/HttpOperation( 6592): 	at fhk.a(PG:908)
E/HttpOperation( 6592): 	at fhk.onPerformSync(PG:636)
E/HttpOperation( 6592): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/HttpOperation( 6592): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/HttpOperation( 6592): 	at ihi.a(PG:22)
E/HttpOperation( 6592): 	at kft.a(PG:91)
E/HttpOperation( 6592): 	at kfv.a(PG:62)
E/HttpOperation( 6592): 	... 12 more
E/HttpOperation( 6592): Caused by: gdi: User intervention required. Notification has been pushed.
E/HttpOperation( 6592): 	at gde.c(Unknown Source)
E/HttpOperation( 6592): 	at gde.b(Unknown Source)
E/HttpOperation( 6592): 	at ihi.a(PG:19)
E/HttpOperation( 6592): 	... 14 more
E/EsSyncAdapterService( 6592): Sync failure
E/EsSyncAdapterService( 6592): java.io.IOException: Rpc failed
E/EsSyncAdapterService( 6592): 	at ixd.a(PG:348)
E/EsSyncAdapterService( 6592): 	at ixd.a(PG:248)
E/EsSyncAdapterService( 6592): 	at ixd.b(PG:206)
E/EsSyncAdapterService( 6592): 	at ixd.a(PG:175)
E/EsSyncAdapterService( 6592): 	at fig.a(PG:78)
E/EsSyncAdapterService( 6592): 	at lex.a(PG:85)
E/EsSyncAdapterService( 6592): 	at lex.b(PG:132)
E/EsSyncAdapterService( 6592): 	at fhk.a(PG:1146)
E/EsSyncAdapterService( 6592): 	at fhk.a(PG:908)
E/EsSyncAdapterService( 6592): 	at fhk.onPerformSync(PG:636)
E/EsSyncAdapterService( 6592): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/EsSyncAdapterService( 6592): Caused by: java.io.IOException: Cannot obtain authentication token
E/EsSyncAdapterService( 6592): 	at kfv.a(PG:65)
E/EsSyncAdapterService( 6592): 	at kff.u(PG:385)
E/EsSyncAdapterService( 6592): 	at kfb.a(PG:29)
E/EsSyncAdapterService( 6592): 	... 10 more
E/EsSyncAdapterService( 6592): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/EsSyncAdapterService( 6592): 	at ihi.a(PG:22)
E/EsSyncAdapterService( 6592): 	at kft.a(PG:91)
E/EsSyncAdapterService( 6592): 	at kfv.a(PG:62)
E/EsSyncAdapterService( 6592): 	... 12 more
E/EsSyncAdapterService( 6592): Caused by: gdi: User intervention required. Notification has been pushed.
E/EsSyncAdapterService( 6592): 	at gde.c(Unknown Source)
E/EsSyncAdapterService( 6592): 	at gde.b(Unknown Source)
E/EsSyncAdapterService( 6592): 	at ihi.a(PG:19)
E/EsSyncAdapterService( 6592): 	... 14 more
,D/ConnectivityService(  918): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/SyncManager(  918): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, PERIODIC, currentRunTime 251391, reason: Periodic, SyncResult: stats [ numIoExceptions: 2]
D/ConnectivityService(  918): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/ConnectivityService(  918): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SecContentProvider2(  918): uri = 11 selection = getMyKnoxAdmin
,D/SecContentProvider2(  918): mCursor = null
,E/SQLiteLog( 1739): (10) POSIX Error : 11 SQLite Error : 3850
,I/PowerManagerService(  918): [PWL] Off : 140s ago
,E/SMD     (  280): DCD ON
,D/SSRM:m  (  918): SIOP:: AP = 300, PST = 303, CUR = 300
,E/SMD     (  280): DCD ON
,E/SMD     (  280): DCD ON
,E/Watchdog(  918): !@Sync 9
,D/BatteryService(  918): level:100, scale:100, status:5, health:2, present:true, voltage: 4386, temperature: 296, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  918): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  918): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  918):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  918): Plugged
,I/MotionRecognitionService(  918): setPowerConnected  = true
,D/BatteryService(  918): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1173): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1173): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1173):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3229): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3229): Disconnected process message: 10
,D/BatteryMeterView( 1173): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1173): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1173): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  280): DCD ON
,D/SSRM:m  (  918): SIOP:: AP = 300, PST = 302, CUR = 300
,E/SMD     (  280): DCD ON
,W/ContextImpl(  918): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  280): DCD ON
,I/ServiceManager(  323): Waiting for service AtCmdFwd...
,I/ServiceManager(  323): Waiting for service AtCmdFwd...
,I/ServiceManager(  323): Waiting for service AtCmdFwd...
,E/SMD     (  280): DCD ON
,I/ServiceManager(  323): Waiting for service AtCmdFwd...
,I/ServiceManager(  323): Waiting for service AtCmdFwd...
,D/SSRM:m  (  918): SIOP:: AP = 300, PST = 301, CUR = 300
,W/Atfwd_Sendcmd(  323): AtCmdFwd service not published, waiting... retryCnt : 5
,V/AlarmManager(  918): waitForAlarm result :8
,E/SMD     (  280): DCD ON
,E/SMD     (  280): DCD ON
,E/SMD     (  280): DCD ON
,V/AlarmManager(  918): waitForAlarm result :4
,D/KeyguardUpdateMonitor( 1173): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1173): handleTimeUpdate
,D/KeyguardEffectViewController( 1173): onReceive action : android.intent.action.TIME_TICK
,I/KeyguardEffectViewController( 1173): *** don't update sliding image ***
,D/BatteryService(  918): level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 295, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  918): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
D/BatteryService(  918): stay LED for fully charged
,D/BatteryService(  918): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  918):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  918): Plugged
I/MotionRecognitionService(  918): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1173): received broadcast android.intent.action.BATTERY_CHANGED
,D/STATUSBAR-PhoneStatusBar( 1173):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1173): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1173): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1173): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/KeyguardUpdateMonitor( 1173): handleBatteryUpdate
,V/HeadsetService( 3229): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3229): Disconnected process message: 10
,D/DateView( 1173): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1173): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/ConnectivityService(  918): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/SMD     (  280): DCD ON
,D/SSRM:m  (  918): SIOP:: AP = 300, PST = 300, CUR = 300
,E/SMD     (  280): DCD ON
,D/TimaService(  918): TIMA: TimaService scheduler is intialized. 
,D/TimaService(  918): TimaServiceHandler.handleMessage what =1
,D/TimaService(  918): TIMA: checkEvent, operation: 50000 subject: 10000
,I/TLC_TIMA_PKM_initialize(  918): initializing...
,I/TLC_TIMA_PKM_initialize(  918): root = /firmware/image, root_strlen = 15
,I/TLC_TIMA_PKM_initialize(  918): process = tima_pkm, process_strlen = 8
,I/TZ: qc_tlc_communication(  918): root = /firmware/image, root_len = 15
,I/TZ: qc_tlc_communication(  918): process = tima_pkm, process_strlen = 8
,I/TZ: qc_tlc_communication(  918): aligned max_sendmsg_size = 262208 = 0x40040
,I/TZ: qc_tlc_communication(  918): aligned max_recvmsg_size = 262208 = 0x40040
,I/TZ: qc_tlc_communication(  918): max_message_size = 524416 = 0x80080
,D/QSEECOMAPI: (  918): QSEECom_get_handle sb_length = 0x80080
,D/QSEECOMAPI: (  918): App is not loaded in QSEE
,D/QSEECOMAPI: (  918): Loaded image: APP id = 2
,I/TZ: qc_tlc_communication(  918): TIMA: path = /firmware/image, fname = tima_pkm, tzapp is loaded
,I/TLC_TIMA_PKM_initialize(  918): Trustlet response is completed
,W/ContextImpl(  918): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  280): DCD ON
,E/Watchdog(  918): !@Sync 10
,I/TLC_TIMA_PKM_measure_kernel(  918): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel(  918): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService(  918): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService(  918): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,E/SMD     (  280): DCD ON
,I/PowerManagerService(  918): [PWL] Off : 180s ago
,D/SSRM:m  (  918): SIOP:: AP = 300, PST = 300, CUR = 300
,E/SMD     (  280): DCD ON
,E/SMD     (  280): DCD ON
,I/Atfwd_Sendcmd(  323): AtCmdFwd service not ready - Exhausted retry attempts - :6
I/Atfwd_Daemon(  323): result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,E/SMD     (  280): DCD ON
,D/SSRM:m  (  918): SIOP:: AP = 300, PST = 300, CUR = 300
,E/SMD     (  280): DCD ON
,E/SMD     (  280): DCD ON
,W/ContextImpl(  918): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,V/AlarmManager(  918): waitForAlarm result :4
,E/ActivityManager(  918): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  918): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  918): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  918): checkUser: useridlist=null, currentuser=0
,D/BatteryService(  918): level:100, scale:100, status:5, health:2, present:true, voltage: 4383, temperature: 295, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,E/Zygote  ( 8227): MountEmulatedStorage()
,D/BatteryService(  918): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
D/BatteryService(  918): stay LED for fully charged
,E/Zygote  ( 8227): v2
D/BatteryService(  918): Sending ACTION_BATTERY_CHANGED.
,I/ActivityManager(  918): Start proc com.blurb.checkout for broadcast com.blurb.checkout/.RebootReceiver: pid=8227 uid=10081 gids={50081, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/libpersona( 8227): KNOX_SDCARD checking this for 10081
,I/libpersona( 8227): KNOX_SDCARD not a persona
,D/MotionRecognitionService(  918):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  918): Plugged
I/MotionRecognitionService(  918): setPowerConnected  = true
,I/SELinux ( 8227): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 8227): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,D/KeyguardUpdateMonitor( 1173): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1173): handleBatteryUpdate
,E/SELinux ( 8227): [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
,V/HeadsetService( 3229): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3229): Disconnected process message: 10
,D/STATUSBAR-PhoneStatusBar( 1173):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1173): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1173): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1173): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/TimaKeyStoreProvider( 8227): TimaSignature is unavailable
,D/ActivityThread( 8227): Added TimaKeyStore provider
,D/ResourcesManager( 8227): creating new AssetManager and set to /system/app/Blurb/Blurb.apk
,I/ActivityManager(  918): Killing 7004:com.samsung.android.magazine.service/u0a118 (adj 15): bgCount ##41
,W/libprocessgroup(  918): failed to open /acct/uid_10118/pid_7004/cgroup.procs: No such file or directory
,E/SMD     (  280): DCD ON
,V/AlarmManager(  918): waitForAlarm result :4
,D/ConnectivityService(  918): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  918): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/BooksSync( 7348): Starting books sync, d
,D/ConnectivityService(  918): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,V/GLSActivity( 1739): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1739): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
,I/GLSUser ( 1739): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1739): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1739): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1739): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ResourcesManager( 1739): creating new AssetManager and set to /system/app/Books/Books.apk
,V/BitmapFactory( 1739): DecodeImagePath(decodeResourceStream3) : res/mipmap-xxhdpi-v4/ic_launcher_play_books.png
,V/BitmapFactory( 1739): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  918): uri = 14 selection = getSealedState
,D/SecContentProvider2(  918): mCursor = null
D/SecContentProvider2(  918): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  918): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy(  918): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/StatusBar( 1173): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,I/PhoneStatusBar( 1173): Icon Only
,D/LockPatternUtilsCache( 1173): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1173): value : false
D/PanelView( 1173): There is/are notification(s) 
D/PanelView( 1173): There is/are notification(s) 
,W/GLSActivity( 1739): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1739): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1739): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1739): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1739): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1739): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1739): 	at android.os.Binder.execTransact(Binder.java:446)
,E/BooksAccountManager( 7348): Authentication error
E/BooksAccountManager( 7348): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 7348): android.accounts.AccountManager.convertErrorToException(AccountManager.java:1893)
,E/HttpHelper( 7348): null auth token
,I/qtaguid ( 7348): Tagging socket 34 with tag 10000000000{256,0} uid -1, pid: 7348, getuid(): 10082
,I/qtaguid ( 7348): Untagging socket 34
,W/ApiaryClient( 7348): Error response from books API: {
W/ApiaryClient( 7348):  "error": {
W/ApiaryClient( 7348):   "errors": [
W/ApiaryClient( 7348):    {
W/ApiaryClient( 7348):     "domain": "global",
W/ApiaryClient( 7348):     "reason": "required",
W/ApiaryClient( 7348):     "message": "Login Required",
W/ApiaryClient( 7348):     "locationType": "header",
W/ApiaryClient( 7348):     "location": "Authorization"
W/ApiaryClient( 7348):    }
W/ApiaryClient( 7348):   ],
W/ApiaryClient( 7348):   "code": 401,
W/ApiaryClient( 7348):   "message": "Login Required"
W/ApiaryClient( 7348):  }
W/ApiaryClient( 7348): }
,W/ApiaryClient( 7348): errCount = 1: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 7348): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3DS0HXd4TFLU4&nonce=912465304146945625&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 7348): Headers suppressed
,D/ConnectivityService(  918): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,V/GLSActivity( 1739): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1739): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
,I/GLSUser ( 1739): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1739): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1739): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1739): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/BitmapFactory( 1739): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  918): uri = 14 selection = getSealedState
,D/SecContentProvider2(  918): mCursor = null
D/SecContentProvider2(  918): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  918): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy(  918): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/StatusBar( 1173): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,I/PhoneStatusBar( 1173): Icon Only
,D/LockPatternUtilsCache( 1173): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1173): value : false
D/PanelView( 1173): There is/are notification(s) 
,D/PanelView( 1173): There is/are notification(s) 
,W/GLSActivity( 1739): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1739): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1739): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1739): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1739): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1739): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1739): 	at android.os.Binder.execTransact(Binder.java:446)
,E/BooksAccountManager( 7348): Authentication error
E/BooksAccountManager( 7348): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 7348): android.accounts.AccountManager.convertErrorToException(AccountManager.java:1893)
,E/HttpHelper( 7348): null auth token
,I/qtaguid ( 7348): Tagging socket 34 with tag 10000000000{256,0} uid -1, pid: 7348, getuid(): 10082
,E/SMD     (  280): DCD ON
,I/qtaguid ( 7348): Untagging socket 34
,W/ApiaryClient( 7348): Error response from books API: {
W/ApiaryClient( 7348):  "error": {
W/ApiaryClient( 7348):   "errors": [
W/ApiaryClient( 7348):    {
W/ApiaryClient( 7348):     "domain": "global",
W/ApiaryClient( 7348):     "reason": "required",
W/ApiaryClient( 7348):     "message": "Login Required",
W/ApiaryClient( 7348):     "locationType": "header",
W/ApiaryClient( 7348):     "location": "Authorization"
W/ApiaryClient( 7348):    }
W/ApiaryClient( 7348):   ],
W/ApiaryClient( 7348):   "code": 401,
W/ApiaryClient( 7348):   "message": "Login Required"
W/ApiaryClient( 7348):  }
W/ApiaryClient( 7348): }
,W/ApiaryClient( 7348): errCount = 2: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 7348): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3DS0HXd4TFLU4&nonce=912465304146945625&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 7348): Headers suppressed
,D/ConnectivityService(  918): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/ServiceManager(  323): Waiting for service AtCmdFwd...
,D/SSRM:m  (  918): SIOP:: AP = 300, PST = 300, CUR = 300
,V/GLSActivity( 1739): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1739): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
,I/GLSUser ( 1739): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1739): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1739): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1739): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/BitmapFactory( 1739): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  918): uri = 14 selection = getSealedState
,D/SecContentProvider2(  918): mCursor = null
D/SecContentProvider2(  918): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  918): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy(  918): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/StatusBar( 1173): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,I/PhoneStatusBar( 1173): Icon Only
,D/LockPatternUtilsCache( 1173): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1173): value : false
D/PanelView( 1173): There is/are notification(s) 
D/PanelView( 1173): There is/are notification(s) 
,W/GLSActivity( 1739): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1739): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1739): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1739): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1739): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1739): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1739): 	at android.os.Binder.execTransact(Binder.java:446)
,I/ServiceManager(  323): Waiting for service AtCmdFwd...
,E/BooksAccountManager( 7348): Authentication error
E/BooksAccountManager( 7348): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 7348): android.accounts.AccountManager.convertErrorToException(AccountManager.java:1893)
E/HttpHelper( 7348): null auth token
,I/qtaguid ( 7348): Tagging socket 34 with tag 10000000000{256,0} uid -1, pid: 7348, getuid(): 10082
,I/qtaguid ( 7348): Untagging socket 34
,W/ApiaryClient( 7348): Error response from books API: {
W/ApiaryClient( 7348):  "error": {
W/ApiaryClient( 7348):   "errors": [
W/ApiaryClient( 7348):    {
W/ApiaryClient( 7348):     "domain": "global",
W/ApiaryClient( 7348):     "reason": "required",
W/ApiaryClient( 7348):     "message": "Login Required",
W/ApiaryClient( 7348):     "locationType": "header",
W/ApiaryClient( 7348):     "location": "Authorization"
W/ApiaryClient( 7348):    }
W/ApiaryClient( 7348):   ],
W/ApiaryClient( 7348):   "code": 401,
W/ApiaryClient( 7348):   "message": "Login Required"
W/ApiaryClient( 7348):  }
W/ApiaryClient( 7348): }
,W/ApiaryClient( 7348): errCount = 3: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 7348): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3DS0HXd4TFLU4&nonce=912465304146945625&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 7348): Headers suppressed
,D/ConnectivityService(  918): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/ServiceManager(  323): Waiting for service AtCmdFwd...
,E/BooksSync( 7348): Soft error
E/BooksSync( 7348): com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
E/BooksSync( 7348): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3DS0HXd4TFLU4&nonce=912465304146945625&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
E/BooksSync( 7348): Headers suppressed
E/BooksSync( 7348): 
E/BooksSync( 7348): com.google.android.apps.books.net.HttpHelper.wrapExceptionBasedOnStatus(HttpHelper.java:212)
,E/BooksSync( 7348): Sync error
E/BooksSync( 7348): com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
E/BooksSync( 7348): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3DS0HXd4TFLU4&nonce=912465304146945625&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
E/BooksSync( 7348): Headers suppressed
E/BooksSync( 7348): 
E/BooksSync( 7348): com.google.android.apps.books.net.HttpHelper.wrapExceptionBasedOnStatus(HttpHelper.java:212)
,I/BooksSync( 7348): Finished books sync
,D/ConnectivityService(  918): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SyncManager(  918): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 315517, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,D/ConnectivityService(  918): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  918): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/art     (  918): Explicit concurrent mark sweep GC freed 57531(3MB) AllocSpace objects, 62(1772KB) LOS objects, 30% free, 36MB/52MB, paused 2.278ms total 177.909ms
,D/SecContentProvider2(  918): uri = 11 selection = getMyKnoxAdmin
,D/SecContentProvider2(  918): mCursor = null
,E/SMD     (  280): DCD ON
,I/ServiceManager(  323): Waiting for service AtCmdFwd...
,I/ServiceManager(  323): Waiting for service AtCmdFwd...
,W/Atfwd_Sendcmd(  323): AtCmdFwd service not published, waiting... retryCnt : 1
,E/SMD     (  280): DCD ON
,E/Watchdog(  918): !@Sync 11
,D/BatteryService(  918): level:100, scale:100, status:5, health:2, present:true, voltage: 4383, temperature: 294, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  918): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  918): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  918):   mReceiver.onReceive : ACTION_BATTERY_CHANGED,
,I/MotionRecognitionService(  918): Plugged
,I/MotionRecognitionService(  918): setPowerConnected  = true
,D/BatteryService(  918): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1173): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1173): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1173):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3229): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3229): Disconnected process message: 10
,D/BatteryMeterView( 1173): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1173): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1173): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  280): DCD ON
,I/ServiceManager(  323): Waiting for service AtCmdFwd...
,D/SSRM:m  (  918): SIOP:: AP = 300, PST = 300, CUR = 300
,I/ServiceManager(  323): Waiting for service AtCmdFwd...
,E/SMD     (  280): DCD ON
,I/ServiceManager(  323): Waiting for service AtCmdFwd...
,I/ServiceManager(  323): Waiting for service AtCmdFwd...
,I/ServiceManager(  323): Waiting for service AtCmdFwd...
,W/ContextImpl(  918): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  280): DCD ON
,W/Atfwd_Sendcmd(  323): AtCmdFwd service not published, waiting... retryCnt : 2
,D/BatteryService(  918): level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 294, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  918): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  918): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  918):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  918): Plugged
,I/MotionRecognitionService(  918): setPowerConnected  = true
,D/BatteryService(  918): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1173): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1173): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1173):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3229): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3229): Disconnected process message: 10
,D/BatteryMeterView( 1173): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1173): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1173): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  280): DCD ON
,V/GLSActivity( 1739): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1739): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
,I/GLSUser ( 1739): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1739): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1739): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1739): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ResourcesManager( 1739): creating new AssetManager and set to /data/app/com.android.vending-1/base.apk
,V/BitmapFactory( 1739): DecodeImagePath(decodeResourceStream3) : res/mipmap-xxhdpi-v4/ic_launcher_play_store.png
,V/BitmapFactory( 1739): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  918): uri = 14 selection = getSealedState
,D/SecContentProvider2(  918): mCursor = null
D/SecContentProvider2(  918): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  918): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy(  918): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/StatusBar( 1173): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,I/PhoneStatusBar( 1173): Icon Only
,D/LockPatternUtilsCache( 1173): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1173): value : false
D/PanelView( 1173): There is/are notification(s) 
,D/PanelView( 1173): There is/are notification(s) 
,W/GLSActivity( 1739): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1739): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1739): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1739): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1739): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1739): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1739): 	at android.os.Binder.execTransact(Binder.java:446)
,E/PlayEventLogger( 6619): Failed to get auth token: User intervention required. Notification has been pushed.
E/PlayEventLogger( 6619): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/PlayEventLogger( 6619): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1893)
E/PlayEventLogger( 6619): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/PlayEventLogger( 6619): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1736)
E/PlayEventLogger( 6619): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/PlayEventLogger( 6619): 	at android.os.Binder.execTransact(Binder.java:446)
,W/System  ( 6619): Ignoring header User-Agent because its value was null.
I/System.out( 6619): (HTTPLog)-Static: SBServiceAPI: getService class android.os.ServiceManager
I/System.out( 6619): (HTTPLog)-Static: isShipBuild true
I/System.out( 6619): (HTTPLog)-Thread-1093-102539383: SmartBonding Enabling is true, SHIP_BUILD is true, log to file is false, DBG is false
,V/AlarmManager(  918): waitForAlarm result :8,
,D/SSRM:m  (  918): SIOP:: AP = 300, PST = 300, CUR = 300
,E/SMD     (  280): DCD ON
,E/SMD     (  280): DCD ON
,I/PowerManagerService(  918): [PWL] Off : 225s ago
,I/ServiceManager(  323): Waiting for service AtCmdFwd...
,I/ServiceManager(  323): Waiting for service AtCmdFwd...
,E/SMD     (  280): DCD ON
,I/ServiceManager(  323): Waiting for service AtCmdFwd...
,I/ServiceManager(  323): Waiting for service AtCmdFwd...
,V/AlarmManager(  918): waitForAlarm result :4
,D/KeyguardUpdateMonitor( 1173): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1173): handleTimeUpdate
,D/KeyguardEffectViewController( 1173): onReceive action : android.intent.action.TIME_TICK
,I/KeyguardEffectViewController( 1173): *** don't update sliding image ***
,D/BatteryService(  918): level:100, scale:100, status:5, health:2, present:true, voltage: 4386, temperature: 294, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  918): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
D/BatteryService(  918): stay LED for fully charged
,D/BatteryService(  918): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1173): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1173): handleBatteryUpdate
,D/MotionRecognitionService(  918):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,D/STATUSBAR-PhoneStatusBar( 1173):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,I/MotionRecognitionService(  918): Plugged
,I/MotionRecognitionService(  918): setPowerConnected  = true
,D/BatteryMeterView( 1173): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3229): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3229): Disconnected process message: 10
,D/BatteryMeterView( 1173): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1173): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/DateView( 1173): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1173): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/ConnectivityService(  918): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/ServiceManager(  323): Waiting for service AtCmdFwd...
,E/SMD     (  280): DCD ON
,W/Atfwd_Sendcmd(  323): AtCmdFwd service not published, waiting... retryCnt : 3
,D/SSRM:m  (  918): SIOP:: AP = 290, PST = 299, CUR = 300
,E/SMD     (  280): DCD ON
,W/ContextImpl(  918): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  280): DCD ON
,E/Watchdog(  918): !@Sync 12
,D/BatteryService(  918): level:100, scale:100, status:5, health:2, present:true, voltage: 4383, temperature: 294, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  918): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  918): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  918):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  918): Plugged
,I/MotionRecognitionService(  918): setPowerConnected  = true
,D/BatteryService(  918): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1173): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1173): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1173):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3229): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3229): Disconnected process message: 10
,D/BatteryMeterView( 1173): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1173): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1173): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  280): DCD ON
,D/SSRM:m  (  918): SIOP:: AP = 290, PST = 298, CUR = 300
,E/SMD     (  280): DCD ON
,E/SMD     (  280): DCD ON
,I/ServiceManager(  323): Waiting for service AtCmdFwd...
,I/ServiceManager(  323): Waiting for service AtCmdFwd...
,I/ServiceManager(  323): Waiting for service AtCmdFwd...
,E/SMD     (  280): DCD ON
,I/ServiceManager(  323): Waiting for service AtCmdFwd...
,D/BatteryService(  918): level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 294, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  918): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  918): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  918):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  918): Plugged
,I/MotionRecognitionService(  918): setPowerConnected  = true
,D/BatteryService(  918): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1173): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1173): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1173):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3229): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3229): Disconnected process message: 10
,D/BatteryMeterView( 1173): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1173): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1173): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/ServiceManager(  323): Waiting for service AtCmdFwd...
,W/Atfwd_Sendcmd(  323): AtCmdFwd service not published, waiting... retryCnt : 4
,D/SSRM:m  (  918): SIOP:: AP = 290, PST = 297, CUR = 300
,E/SMD     (  280): DCD ON
,E/SMD     (  280): DCD ON
,W/ContextImpl(  918): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  280): DCD ON
,E/SMD     (  280): DCD ON
,D/SSRM:m  (  918): SIOP:: AP = 290, PST = 296, CUR = 300
,V/AlarmManager(  918): waitForAlarm result :4
,D/ConnectivityService(  918): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/BatteryService(  918): level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 293, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  918): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
D/BatteryService(  918): stay LED for fully charged
D/BatteryService(  918): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  918):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  918): Plugged
I/MotionRecognitionService(  918): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1173): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1173): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1173):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3229): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3229): Disconnected process message: 10
,D/BatteryMeterView( 1173): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1173): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1173): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/ConnectivityService(  918): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/GLSUser ( 1739): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,I/GLSUser ( 1739): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1739): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1739): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1739): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/BitmapFactory( 1739): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  918): uri = 14 selection = getSealedState
D/SecContentProvider2(  918): mCursor = null
D/SecContentProvider2(  918): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  918): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
V/ApplicationPolicy(  918): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/StatusBar( 1173): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,I/PhoneStatusBar( 1173): Icon Only
,D/LockPatternUtilsCache( 1173): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1173): value : false
D/PanelView( 1173): There is/are notification(s) 
D/PanelView( 1173): There is/are notification(s) 
,E/HttpOperation( 6592): [kfu{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
E/HttpOperation( 6592): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 6592): 	at kfv.a(PG:65)
E/HttpOperation( 6592): 	at kff.u(PG:385)
E/HttpOperation( 6592): 	at kfb.a(PG:29)
E/HttpOperation( 6592): 	at kff.l(PG:132)
E/HttpOperation( 6592): 	at dsf.a(PG:807)
E/HttpOperation( 6592): 	at fhk.a(PG:1126)
E/HttpOperation( 6592): 	at fhk.a(PG:908)
E/HttpOperation( 6592): 	at fhk.onPerformSync(PG:636)
E/HttpOperation( 6592): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/HttpOperation( 6592): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/HttpOperation( 6592): 	at ihi.a(PG:22)
E/HttpOperation( 6592): 	at kft.a(PG:91)
E/HttpOperation( 6592): 	at kfv.a(PG:62)
E/HttpOperation( 6592): 	... 8 more
E/HttpOperation( 6592): Caused by: gdi: User intervention required. Notification has been pushed.
E/HttpOperation( 6592): 	at gde.c(Unknown Source)
E/HttpOperation( 6592): 	at gde.b(Unknown Source)
E/HttpOperation( 6592): 	at ihi.a(PG:19)
E/HttpOperation( 6592): 	... 10 more
,I/GLSUser ( 1739): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,I/GLSUser ( 1739): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1739): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1739): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1739): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/BitmapFactory( 1739): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  918): uri = 14 selection = getSealedState
D/SecContentProvider2(  918): mCursor = null
,D/SecContentProvider2(  918): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  918): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
V/ApplicationPolicy(  918): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/StatusBar( 1173): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,I/PhoneStatusBar( 1173): Icon Only
E/HttpOperation( 6592): [getmobileexperiments] Unexpected exception
E/HttpOperation( 6592): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 6592): 	at kfv.a(PG:65)
E/HttpOperation( 6592): 	at kff.u(PG:385)
E/HttpOperation( 6592): 	at kfb.a(PG:29)
E/HttpOperation( 6592): 	at kff.l(PG:132)
E/HttpOperation( 6592): 	at ieo.a(PG:43)
E/HttpOperation( 6592): 	at iep.a(PG:93)
E/HttpOperation( 6592): 	at fhn.a(PG:59)
E/HttpOperation( 6592): 	at lex.a(PG:85)
E/HttpOperation( 6592): 	at lex.b(PG:132)
E/HttpOperation( 6592): 	at fhk.a(PG:1146)
E/HttpOperation( 6592): 	at fhk.a(PG:908)
E/HttpOperation( 6592): 	at fhk.onPerformSync(PG:636)
E/HttpOperation( 6592): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/HttpOperation( 6592): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/HttpOperation( 6592): 	at ihi.a(PG:22)
E/HttpOperation( 6592): 	at kft.a(PG:91)
E/HttpOperation( 6592): 	at kfv.a(PG:62)
E/HttpOperation( 6592): 	... 12 more
E/HttpOperation( 6592): Caused by: gdi: User intervention required. Notification has been pushed.
E/HttpOperation( 6592): 	at gde.c(Unknown Source)
E/HttpOperation( 6592): 	at gde.b(Unknown Source)
E/HttpOperation( 6592): 	at ihi.a(PG:19)
E/HttpOperation( 6592): 	... 14 more
D/LockPatternUtilsCache( 1173): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1173): value : false
D/PanelView( 1173): There is/are notification(s) 
D/PanelView( 1173): There is/are notification(s) 
,E/ExperimentLoader( 6592): [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 6592): java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 6592): 	at kfv.a(PG:65)
E/ExperimentLoader( 6592): 	at kff.u(PG:385)
E/ExperimentLoader( 6592): 	at kfb.a(PG:29)
E/ExperimentLoader( 6592): 	at kff.l(PG:132)
E/ExperimentLoader( 6592): 	at ieo.a(PG:43)
E/ExperimentLoader( 6592): 	at iep.a(PG:93)
E/ExperimentLoader( 6592): 	at fhn.a(PG:59)
E/ExperimentLoader( 6592): 	at lex.a(PG:85)
E/ExperimentLoader( 6592): 	at lex.b(PG:132)
E/ExperimentLoader( 6592): 	at fhk.a(PG:1146)
E/ExperimentLoader( 6592): 	at fhk.a(PG:908)
E/ExperimentLoader( 6592): 	at fhk.onPerformSync(PG:636)
E/ExperimentLoader( 6592): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/ExperimentLoader( 6592): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/ExperimentLoader( 6592): 	at ihi.a(PG:22)
E/ExperimentLoader( 6592): 	at kft.a(PG:91)
E/ExperimentLoader( 6592): 	at kfv.a(PG:62)
E/ExperimentLoader( 6592): 	... 12 more
E/ExperimentLoader( 6592): Caused by: gdi: User intervention required. Notification has been pushed.
E/ExperimentLoader( 6592): 	at gde.c(Unknown Source)
E/ExperimentLoader( 6592): 	at gde.b(Unknown Source)
E/ExperimentLoader( 6592): 	at ihi.a(PG:19)
E/ExperimentLoader( 6592): 	... 14 more
,I/GLSUser ( 1739): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,I/GLSUser ( 1739): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1739): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1739): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1739): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/SQLiteLog( 1739): (10) POSIX Error : 11 SQLite Error : 3850
,V/BitmapFactory( 1739): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  918): uri = 14 selection = getSealedState
D/SecContentProvider2(  918): mCursor = null
,D/SecContentProvider2(  918): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  918): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
V/ApplicationPolicy(  918): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/StatusBar( 1173): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,I/PhoneStatusBar( 1173): Icon Only
,D/LockPatternUtilsCache( 1173): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1173): value : false
,D/PanelView( 1173): There is/are notification(s) 
,D/PanelView( 1173): There is/are notification(s) 
,E/HttpOperation( 6592): [getaccountstatus] Unexpected exception
E/HttpOperation( 6592): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 6592): 	at kfv.a(PG:65)
E/HttpOperation( 6592): 	at kff.u(PG:385)
E/HttpOperation( 6592): 	at kfb.a(PG:29)
E/HttpOperation( 6592): 	at ixd.a(PG:248)
E/HttpOperation( 6592): 	at ixd.b(PG:206)
E/HttpOperation( 6592): 	at ixd.a(PG:175)
E/HttpOperation( 6592): 	at fig.a(PG:78)
E/HttpOperation( 6592): 	at lex.a(PG:85)
E/HttpOperation( 6592): 	at lex.b(PG:132)
E/HttpOperation( 6592): 	at fhk.a(PG:1146)
E/HttpOperation( 6592): 	at fhk.a(PG:908)
E/HttpOperation( 6592): 	at fhk.onPerformSync(PG:636)
E/HttpOperation( 6592): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/HttpOperation( 6592): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/HttpOperation( 6592): 	at ihi.a(PG:22)
E/HttpOperation( 6592): 	at kft.a(PG:91)
E/HttpOperation( 6592): 	at kfv.a(PG:62)
E/HttpOperation( 6592): 	... 12 more
E/HttpOperation( 6592): Caused by: gdi: User intervention required. Notification has been pushed.
E/HttpOperation( 6592): 	at gde.c(Unknown Source)
E/HttpOperation( 6592): 	at gde.b(Unknown Source)
E/HttpOperation( 6592): 	at ihi.a(PG:19)
E/HttpOperation( 6592): 	... 14 more
,E/EsSyncAdapterService( 6592): Sync failure
E/EsSyncAdapterService( 6592): java.io.IOException: Rpc failed
E/EsSyncAdapterService( 6592): 	at ixd.a(PG:348)
E/EsSyncAdapterService( 6592): 	at ixd.a(PG:248)
E/EsSyncAdapterService( 6592): 	at ixd.b(PG:206)
E/EsSyncAdapterService( 6592): 	at ixd.a(PG:175)
E/EsSyncAdapterService( 6592): 	at fig.a(PG:78)
E/EsSyncAdapterService( 6592): 	at lex.a(PG:85)
E/EsSyncAdapterService( 6592): 	at lex.b(PG:132)
E/EsSyncAdapterService( 6592): 	at fhk.a(PG:1146)
E/EsSyncAdapterService( 6592): 	at fhk.a(PG:908)
E/EsSyncAdapterService( 6592): 	at fhk.onPerformSync(PG:636)
E/EsSyncAdapterService( 6592): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/EsSyncAdapterService( 6592): Caused by: java.io.IOException: Cannot obtain authentication token
E/EsSyncAdapterService( 6592): 	at kfv.a(PG:65)
E/EsSyncAdapterService( 6592): 	at kff.u(PG:385)
E/EsSyncAdapterService( 6592): 	at kfb.a(PG:29)
E/EsSyncAdapterService( 6592): 	... 10 more
E/EsSyncAdapterService( 6592): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/EsSyncAdapterService( 6592): 	at ihi.a(PG:22)
E/EsSyncAdapterService( 6592): 	at kft.a(PG:91)
E/EsSyncAdapterService( 6592): 	at kfv.a(PG:62)
E/EsSyncAdapterService( 6592): 	... 12 more
E/EsSyncAdapterService( 6592): Caused by: gdi: User intervention required. Notification has been pushed.
E/EsSyncAdapterService( 6592): 	at gde.c(Unknown Source)
E/EsSyncAdapterService( 6592): 	at gde.b(Unknown Source)
E/EsSyncAdapterService( 6592): 	at ihi.a(PG:19)
E/EsSyncAdapterService( 6592): 	... 14 more
,D/ConnectivityService(  918): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SyncManager(  918): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, PERIODIC, currentRunTime 398768, reason: Periodic, SyncResult: stats [ numIoExceptions: 2]
,D/ConnectivityService(  918): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SecContentProvider2(  918): uri = 11 selection = getMyKnoxAdmin
,D/SecContentProvider2(  918): mCursor = null
,D/ConnectivityService(  918): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/SQLiteLog( 1739): (10) POSIX Error : 11 SQLite Error : 3850
,E/SMD     (  280): DCD ON
,E/SMD     (  280): DCD ON
,E/Watchdog(  918): !@Sync 13
,E/SMD     (  280): DCD ON
,I/ServiceManager(  323): Waiting for service AtCmdFwd...
,D/SSRM:m  (  918): SIOP:: AP = 290, PST = 295, CUR = 300
,D/BatteryService(  918): level:100, scale:100, status:5, health:2, present:true, voltage: 4383, temperature: 293, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  918): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  918): Sending ACTION_BATTERY_CHANGED.
,I/ServiceManager(  323): Waiting for service AtCmdFwd...
,D/BatteryService(  918): stay LED for fully charged
,D/MotionRecognitionService(  918):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1173): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1173): handleBatteryUpdate
,I/MotionRecognitionService(  918): Plugged
,I/MotionRecognitionService(  918): setPowerConnected  = true
,D/STATUSBAR-PhoneStatusBar( 1173):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3229): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3229): Disconnected process message: 10
,D/BatteryMeterView( 1173): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1173): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1173): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  280): DCD ON
,I/ServiceManager(  323): Waiting for service AtCmdFwd...
,I/ServiceManager(  323): Waiting for service AtCmdFwd...
,I/ServiceManager(  323): Waiting for service AtCmdFwd...
,I/PowerManagerService(  918): [PWL] Off : 275s ago
,W/ContextImpl(  918): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  280): DCD ON
,W/Atfwd_Sendcmd(  323): AtCmdFwd service not published, waiting... retryCnt : 5
,E/SMD     (  280): DCD ON
,V/AlarmManager(  918): waitForAlarm result :8
,D/SSRM:m  (  918): SIOP:: AP = 290, PST = 294, CUR = 300
,E/SMD     (  280): DCD ON
,E/SMD     (  280): DCD ON
,E/SMD     (  280): DCD ON
,E/SMD     (  280): DCD ON
,D/SSRM:m  (  918): SIOP:: AP = 290, PST = 293, CUR = 300
,V/AlarmManager(  918): waitForAlarm result :4
,D/KeyguardUpdateMonitor( 1173): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1173): handleTimeUpdate
,D/KeyguardEffectViewController( 1173): onReceive action : android.intent.action.TIME_TICK
,I/KeyguardEffectViewController( 1173): *** don't update sliding image ***
,D/ConnectivityService(  918): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/DateView( 1173): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1173): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,E/SMD     (  280): DCD ON
,W/ContextImpl(  918): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  280): DCD ON
,E/Watchdog(  918): !@Sync 14
,E/SMD     (  280): DCD ON
,I/Atfwd_Sendcmd(  323): AtCmdFwd service not ready - Exhausted retry attempts - :6
I/Atfwd_Daemon(  323): result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,D/SSRM:m  (  918): SIOP:: AP = 290, PST = 292, CUR = 300
,D/BatteryService(  918): level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 293, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  918): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  918): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  918):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  918): Plugged
,I/MotionRecognitionService(  918): setPowerConnected  = true
,D/BatteryService(  918): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1173): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1173): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1173):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3229): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3229): Disconnected process message: 10
,D/BatteryMeterView( 1173): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1173): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1173): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  280): DCD ON
,E/SMD     (  280): DCD ON
,E/SMD     (  280): DCD ON
,D/SSRM:m  (  918): SIOP:: AP = 290, PST = 291, CUR = 300
,E/SMD     (  280): DCD ON
,D/BatteryService(  918): level:100, scale:100, status:5, health:2, present:true, voltage: 4383, temperature: 292, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  918): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  918): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  918): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1173): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1173): handleBatteryUpdate
,D/MotionRecognitionService(  918):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  918): Plugged
,I/MotionRecognitionService(  918): setPowerConnected  = true
,D/STATUSBAR-PhoneStatusBar( 1173):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3229): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3229): Disconnected process message: 10
,D/BatteryMeterView( 1173): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1173): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1173): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  280): DCD ON
,W/ContextImpl(  918): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  280): DCD ON
,E/SMD     (  280): DCD ON
,I/ServiceManager(  323): Waiting for service AtCmdFwd...
,D/SSRM:m  (  918): SIOP:: AP = 290, PST = 290, CUR = 300
,I/ServiceManager(  323): Waiting for service AtCmdFwd...
,D/BatteryService(  918): level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 292, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  918): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  918): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  918):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  918): Plugged
,I/MotionRecognitionService(  918): setPowerConnected  = true
,D/BatteryService(  918): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1173): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1173): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1173):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1173): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1173): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1173): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3229): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3229): Disconnected process message: 10
,I/ServiceManager(  323): Waiting for service AtCmdFwd...
,E/SMD     (  280): DCD ON
,I/ServiceManager(  323): Waiting for service AtCmdFwd...
,I/ServiceManager(  323): Waiting for service AtCmdFwd...
,W/Atfwd_Sendcmd(  323): AtCmdFwd service not published, waiting... retryCnt : 1
,E/SMD     (  280): DCD ON
,E/Watchdog(  918): !@Sync 15
,E/SMD     (  280): DCD ON
,I/PowerManagerService(  918): [PWL] Off : 330s ago
,I/ServiceManager(  323): Waiting for service AtCmdFwd...
,D/SSRM:m  (  918): SIOP:: AP = 290, PST = 290, CUR = 300
,I/ServiceManager(  323): Waiting for service AtCmdFwd...
,E/SMD     (  280): DCD ON
,I/ServiceManager(  323): Waiting for service AtCmdFwd...
,I/ServiceManager(  323): Waiting for service AtCmdFwd...
,V/AlarmManager(  918): waitForAlarm result :4
,D/ConnectivityService(  918): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  918): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/BooksSync( 7348): Starting books sync, d
,D/ConnectivityService(  918): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,V/GLSActivity( 1739): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1739): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
,I/GLSUser ( 1739): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1739): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1739): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1739): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/BitmapFactory( 1739): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  918): uri = 14 selection = getSealedState
,D/SecContentProvider2(  918): mCursor = null
D/SecContentProvider2(  918): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  918): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy(  918): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/StatusBar( 1173): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,W/GLSActivity( 1739): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1739): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1739): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1739): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1739): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1739): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1739): 	at android.os.Binder.execTransact(Binder.java:446)
,E/BooksAccountManager( 7348): Authentication error
E/BooksAccountManager( 7348): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 7348): android.accounts.AccountManager.convertErrorToException(AccountManager.java:1893)
E/HttpHelper( 7348): null auth token
,I/PhoneStatusBar( 1173): Icon Only
,D/LockPatternUtilsCache( 1173): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1173): value : false
D/PanelView( 1173): There is/are notification(s) 
D/PanelView( 1173): There is/are notification(s) 
,I/qtaguid ( 7348): Tagging socket 34 with tag 10000000000{256,0} uid -1, pid: 7348, getuid(): 10082
,I/qtaguid ( 7348): Untagging socket 34
,W/ApiaryClient( 7348): Error response from books API: {
W/ApiaryClient( 7348):  "error": {
W/ApiaryClient( 7348):   "errors": [
W/ApiaryClient( 7348):    {
W/ApiaryClient( 7348):     "domain": "global",
W/ApiaryClient( 7348):     "reason": "required",
W/ApiaryClient( 7348):     "message": "Login Required",
W/ApiaryClient( 7348):     "locationType": "header",
W/ApiaryClient( 7348):     "location": "Authorization"
W/ApiaryClient( 7348):    }
W/ApiaryClient( 7348):   ],
W/ApiaryClient( 7348):   "code": 401,
W/ApiaryClient( 7348):   "message": "Login Required"
W/ApiaryClient( 7348):  }
W/ApiaryClient( 7348): }
,W/ApiaryClient( 7348): errCount = 1: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 7348): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3DS0HXd4TFLU4&nonce=8368552296396112616&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 7348): Headers suppressed
,D/ConnectivityService(  918): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/ServiceManager(  323): Waiting for service AtCmdFwd...
,W/ContextImpl(  918): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  280): DCD ON
,V/GLSActivity( 1739): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1739): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
,I/GLSUser ( 1739): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1739): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1739): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1739): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/BitmapFactory( 1739): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  918): uri = 14 selection = getSealedState
,D/SecContentProvider2(  918): mCursor = null
D/SecContentProvider2(  918): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  918): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy(  918): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/StatusBar( 1173): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,I/PhoneStatusBar( 1173): Icon Only
,D/LockPatternUtilsCache( 1173): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1173): value : false
D/PanelView( 1173): There is/are notification(s) 
,D/PanelView( 1173): There is/are notification(s) 
,W/GLSActivity( 1739): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1739): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1739): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1739): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1739): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1739): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1739): 	at android.os.Binder.execTransact(Binder.java:446)
,E/BooksAccountManager( 7348): Authentication error
E/BooksAccountManager( 7348): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 7348): android.accounts.AccountManager.convertErrorToException(AccountManager.java:1893)
,E/HttpHelper( 7348): null auth token
,I/qtaguid ( 7348): Tagging socket 34 with tag 10000000000{256,0} uid -1, pid: 7348, getuid(): 10082
,W/Atfwd_Sendcmd(  323): AtCmdFwd service not published, waiting... retryCnt : 2
,I/qtaguid ( 7348): Untagging socket 34
,W/ApiaryClient( 7348): Error response from books API: {
W/ApiaryClient( 7348):  "error": {
W/ApiaryClient( 7348):   "errors": [
W/ApiaryClient( 7348):    {
W/ApiaryClient( 7348):     "domain": "global",
W/ApiaryClient( 7348):     "reason": "required",
W/ApiaryClient( 7348):     "message": "Login Required",
W/ApiaryClient( 7348):     "locationType": "header",
W/ApiaryClient( 7348):     "location": "Authorization"
W/ApiaryClient( 7348):    }
W/ApiaryClient( 7348):   ],
W/ApiaryClient( 7348):   "code": 401,
W/ApiaryClient( 7348):   "message": "Login Required"
W/ApiaryClient( 7348):  }
W/ApiaryClient( 7348): }
,W/ApiaryClient( 7348): errCount = 2: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 7348): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3DS0HXd4TFLU4&nonce=8368552296396112616&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 7348): Headers suppressed
,D/ConnectivityService(  918): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,V/GLSActivity( 1739): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1739): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
,I/GLSUser ( 1739): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1739): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1739): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1739): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/BitmapFactory( 1739): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  918): uri = 14 selection = getSealedState
,D/SecContentProvider2(  918): mCursor = null
D/SecContentProvider2(  918): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  918): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy(  918): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/StatusBar( 1173): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,I/PhoneStatusBar( 1173): Icon Only
,D/LockPatternUtilsCache( 1173): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1173): value : false
D/PanelView( 1173): There is/are notification(s) 
D/PanelView( 1173): There is/are notification(s) 
,W/GLSActivity( 1739): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1739): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1739): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1739): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1739): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1739): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1739): 	at android.os.Binder.execTransact(Binder.java:446)
,E/BooksAccountManager( 7348): Authentication error
E/BooksAccountManager( 7348): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 7348): android.accounts.AccountManager.convertErrorToException(AccountManager.java:1893)
,E/HttpHelper( 7348): null auth token
,I/qtaguid ( 7348): Tagging socket 34 with tag 10000000000{256,0} uid -1, pid: 7348, getuid(): 10082
,I/qtaguid ( 7348): Untagging socket 34
,W/ApiaryClient( 7348): Error response from books API: {
W/ApiaryClient( 7348):  "error": {
W/ApiaryClient( 7348):   "errors": [
W/ApiaryClient( 7348):    {
W/ApiaryClient( 7348):     "domain": "global",
W/ApiaryClient( 7348):     "reason": "required",
W/ApiaryClient( 7348):     "message": "Login Required",
W/ApiaryClient( 7348):     "locationType": "header",
W/ApiaryClient( 7348):     "location": "Authorization"
W/ApiaryClient( 7348):    }
W/ApiaryClient( 7348):   ],
W/ApiaryClient( 7348):   "code": 401,
W/ApiaryClient( 7348):   "message": "Login Required"
W/ApiaryClient( 7348):  }
W/ApiaryClient( 7348): }
,W/ApiaryClient( 7348): errCount = 3: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 7348): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3DS0HXd4TFLU4&nonce=8368552296396112616&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 7348): Headers suppressed
D/ConnectivityService(  918): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/BooksSync( 7348): Soft error
E/BooksSync( 7348): com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
E/BooksSync( 7348): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3DS0HXd4TFLU4&nonce=8368552296396112616&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
E/BooksSync( 7348): Headers suppressed
E/BooksSync( 7348): 
E/BooksSync( 7348): com.google.android.apps.books.net.HttpHelper.wrapExceptionBasedOnStatus(HttpHelper.java:212)
,E/BooksSync( 7348): Sync error
E/BooksSync( 7348): com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
E/BooksSync( 7348): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3DS0HXd4TFLU4&nonce=8368552296396112616&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
E/BooksSync( 7348): Headers suppressed
E/BooksSync( 7348): 
E/BooksSync( 7348): com.google.android.apps.books.net.HttpHelper.wrapExceptionBasedOnStatus(HttpHelper.java:212)
,I/BooksSync( 7348): Finished books sync
,D/ConnectivityService(  918): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SyncManager(  918): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 471453, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,D/ConnectivityService(  918): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ResourcesManager( 2852): creating new AssetManager and set to /system/app/ChatON_MARKET/ChatON_MARKET.apk
,D/ResourcesManager( 2852): creating new AssetManager and set to /system/app/PlusOne/PlusOne.apk
,D/ConnectivityService(  918): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SecContentProvider2(  918): uri = 11 selection = getMyKnoxAdmin
,D/SecContentProvider2(  918): mCursor = null
,E/SMD     (  280): DCD ON
,V/AlarmManager(  918): waitForAlarm result :8
,D/SSRM:m  (  918): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  280): DCD ON
,D/BatteryService(  918): level:100, scale:100, status:5, health:2, present:true, voltage: 4382, temperature: 292, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  918): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  918): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  918):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  918): Plugged
,I/MotionRecognitionService(  918): setPowerConnected  = true
,D/BatteryService(  918): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1173): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1173): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1173):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3229): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3229): Disconnected process message: 10
,D/BatteryMeterView( 1173): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1173): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1173): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  280): DCD ON
,I/ServiceManager(  323): Waiting for service AtCmdFwd...
,I/bootchecker(  316): bootchecker wake up!!
,I/ServiceManager(  323): Waiting for service AtCmdFwd...
,E/SMD     (  280): DCD ON
,I/ServiceManager(  323): Waiting for service AtCmdFwd...
,I/ServiceManager(  323): Waiting for service AtCmdFwd...
,I/ServiceManager(  323): Waiting for service AtCmdFwd...
,E/SMD     (  280): DCD ON
,W/Atfwd_Sendcmd(  323): AtCmdFwd service not published, waiting... retryCnt : 3
,D/SSRM:m  (  918): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  280): DCD ON
,W/ContextImpl(  918): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  280): DCD ON
,E/Watchdog(  918): !@Sync 16
,E/SMD     (  280): DCD ON
,D/SSRM:m  (  918): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  280): DCD ON
,V/AlarmManager(  918): waitForAlarm result :4
,D/KeyguardUpdateMonitor( 1173): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1173): handleTimeUpdate
,D/KeyguardEffectViewController( 1173): onReceive action : android.intent.action.TIME_TICK
,I/KeyguardEffectViewController( 1173): *** don't update sliding image ***
,D/BatteryService(  918): level:100, scale:100, status:5, health:2, present:true, voltage: 4386, temperature: 291, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  918): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
D/BatteryService(  918): stay LED for fully charged
,D/BatteryService(  918): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  918):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  918): Plugged
,I/MotionRecognitionService(  918): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1173): received broadcast android.intent.action.BATTERY_CHANGED
,D/STATUSBAR-PhoneStatusBar( 1173):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1173): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1173): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1173): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/KeyguardUpdateMonitor( 1173): handleBatteryUpdate
,V/HeadsetService( 3229): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3229): Disconnected process message: 10
,D/DateView( 1173): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1173): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/ConnectivityService(  918): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/SMD     (  280): DCD ON
,I/ServiceManager(  323): Waiting for service AtCmdFwd...
,I/ServiceManager(  323): Waiting for service AtCmdFwd...
,I/ServiceManager(  323): Waiting for service AtCmdFwd...
,E/SMD     (  280): DCD ON
,I/ServiceManager(  323): Waiting for service AtCmdFwd...
,I/ServiceManager(  323): Waiting for service AtCmdFwd...
,W/Atfwd_Sendcmd(  323): AtCmdFwd service not published, waiting... retryCnt : 4
,E/SMD     (  280): DCD ON
,D/SSRM:m  (  918): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  280): DCD ON
,W/ContextImpl(  918): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  280): DCD ON
,E/SMD     (  280): DCD ON
,D/SSRM:m  (  918): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  280): DCD ON
,E/SMD     (  280): DCD ON
,E/Watchdog(  918): !@Sync 17
,E/SMD     (  280): DCD ON
,I/PowerManagerService(  918): [PWL] Off : 390s ago
,I/ServiceManager(  323): Waiting for service AtCmdFwd...
,D/SSRM:m  (  918): SIOP:: AP = 290, PST = 290, CUR = 300
,I/ServiceManager(  323): Waiting for service AtCmdFwd...
,E/SMD     (  280): DCD ON
,I/ServiceManager(  323): Waiting for service AtCmdFwd...
,I/ServiceManager(  323): Waiting for service AtCmdFwd...
,D/BatteryService(  918): level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 291, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  918): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  918): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  918):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  918): Plugged
,I/MotionRecognitionService(  918): setPowerConnected  = true
,D/BatteryService(  918): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1173): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1173): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1173):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3229): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3229): Disconnected process message: 10
,D/BatteryMeterView( 1173): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1173): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1173): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/ServiceManager(  323): Waiting for service AtCmdFwd...
,W/ContextImpl(  918): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  280): DCD ON
,W/Atfwd_Sendcmd(  323): AtCmdFwd service not published, waiting... retryCnt : 5
,E/SMD     (  280): DCD ON
,V/AlarmManager(  918): waitForAlarm result :8
,E/SMD     (  280): DCD ON
,D/SSRM:m  (  918): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  280): DCD ON
,D/BatteryService(  918): level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 290, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  918): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  918): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  918):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  918): Plugged
,I/MotionRecognitionService(  918): setPowerConnected  = true
,D/BatteryService(  918): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1173): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1173): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1173):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3229): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3229): Disconnected process message: 10
,D/BatteryMeterView( 1173): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1173): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1173): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  280): DCD ON
,E/SMD     (  280): DCD ON
,D/SSRM:m  (  918): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  280): DCD ON
,W/ContextImpl(  918): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  280): DCD ON
,E/Watchdog(  918): !@Sync 18
,E/SMD     (  280): DCD ON
,I/Atfwd_Sendcmd(  323): AtCmdFwd service not ready - Exhausted retry attempts - :6
I/Atfwd_Daemon(  323): result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,D/SSRM:m  (  918): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  280): DCD ON
,E/SMD     (  280): DCD ON
,D/ConnectivityService(  918): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/SMD     (  280): DCD ON
,E/SMD     (  280): DCD ON
,D/SSRM:m  (  918): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  280): DCD ON
,W/ContextImpl(  918): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  280): DCD ON
,E/SMD     (  280): DCD ON
,D/SSRM:m  (  918): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  280): DCD ON
,D/BatteryService(  918): level:100, scale:100, status:5, health:2, present:true, voltage: 4383, temperature: 290, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  918): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  918): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  918):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  918): Plugged
,I/MotionRecognitionService(  918): setPowerConnected  = true
,D/BatteryService(  918): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1173): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1173): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1173):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3229): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3229): Disconnected process message: 10
,D/BatteryMeterView( 1173): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1173): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1173): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/Atfwd_Daemon(  323): Stop the daemon....
,E/SMD     (  280): DCD ON
,E/Watchdog(  918): !@Sync 19
,E/SMD     (  280): DCD ON
,D/SSRM:m  (  918): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  280): DCD ON
,I/PowerManagerService(  918): [PWL] Off : 455s ago
,D/BatteryService(  918): level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 290, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  918): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  918): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  918):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  918): Plugged
,I/MotionRecognitionService(  918): setPowerConnected  = true
,D/BatteryService(  918): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1173): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1173): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1173):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3229): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3229): Disconnected process message: 10
,D/BatteryMeterView( 1173): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1173): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1173): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,W/ContextImpl(  918): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  280): DCD ON
,E/SMD     (  280): DCD ON
,E/SMD     (  280): DCD ON
,D/SSRM:m  (  918): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  280): DCD ON
,D/BatteryService(  918): level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 289, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  918): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  918): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  918):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  918): Plugged
,I/MotionRecognitionService(  918): setPowerConnected  = true
,D/BatteryService(  918): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1173): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1173): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1173):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3229): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3229): Disconnected process message: 10
,D/BatteryMeterView( 1173): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1173): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1173): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  280): DCD ON
,E/SMD     (  280): DCD ON
,D/SSRM:m  (  918): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  280): DCD ON
,D/TimaService(  918): TIMA: TimaService scheduler is intialized. 
,D/TimaService(  918): TIMA: checkEvent, operation: 50000 subject: 10000
,D/TimaService(  918): TimaServiceHandler.handleMessage what =1
,W/ContextImpl(  918): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/BatteryService(  918): level:100, scale:100, status:5, health:2, present:true, voltage: 4382, temperature: 289, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  918): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  918): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  918):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  918): Plugged
,D/BatteryService(  918): stay LED for fully charged,
I/MotionRecognitionService(  918): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1173): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1173): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1173):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1173): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1173): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1173): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3229): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3229): Disconnected process message: 10
,E/SMD     (  280): DCD ON
,E/Watchdog(  918): !@Sync 20
,I/TLC_TIMA_PKM_measure_kernel(  918): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel(  918): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService(  918): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService(  918): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,E/SMD     (  280): DCD ON
,D/SSRM:m  (  918): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  280): DCD ON
,D/BatteryService(  918): level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 289, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  918): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  918): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  918):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  918): Plugged
,I/MotionRecognitionService(  918): setPowerConnected  = true
,D/BatteryService(  918): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1173): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1173): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1173):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3229): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3229): Disconnected process message: 10
,D/BatteryMeterView( 1173): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1173): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1173): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  280): DCD ON
,E/SMD     (  280): DCD ON
,E/SMD     (  280): DCD ON
,D/SSRM:m  (  918): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  280): DCD ON
,W/ContextImpl(  918): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  280): DCD ON
,E/SMD     (  280): DCD ON
,D/SSRM:m  (  918): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  280): DCD ON
,E/SMD     (  280): DCD ON
,E/Watchdog(  918): !@Sync 21
,V/AlarmManager(  918): waitForAlarm result :4
,D/KeyguardUpdateMonitor( 1173): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1173): handleTimeUpdate
,D/KeyguardEffectViewController( 1173): onReceive action : android.intent.action.TIME_TICK
,I/KeyguardEffectViewController( 1173): *** don't update sliding image ***
,D/DateView( 1173): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1173): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/ConnectivityService(  918): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  918): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/GLSUser ( 1739): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
I/GLSUser ( 1739): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1739): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1739): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1739): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/BitmapFactory( 1739): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  918): uri = 14 selection = getSealedState
,D/SecContentProvider2(  918): mCursor = null
,D/SecContentProvider2(  918): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  918): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
V/ApplicationPolicy(  918): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/StatusBar( 1173): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,I/PhoneStatusBar( 1173): Icon Only
D/LockPatternUtilsCache( 1173): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1173): value : false
D/PanelView( 1173): There is/are notification(s) 
D/PanelView( 1173): There is/are notification(s) 
,E/HttpOperation( 6592): [kfu{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
E/HttpOperation( 6592): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 6592): 	at kfv.a(PG:65)
E/HttpOperation( 6592): 	at kff.u(PG:385)
E/HttpOperation( 6592): 	at kfb.a(PG:29)
E/HttpOperation( 6592): 	at kff.l(PG:132)
E/HttpOperation( 6592): 	at dsf.a(PG:807)
E/HttpOperation( 6592): 	at fhk.a(PG:1126)
E/HttpOperation( 6592): 	at fhk.a(PG:908)
E/HttpOperation( 6592): 	at fhk.onPerformSync(PG:636)
E/HttpOperation( 6592): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/HttpOperation( 6592): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/HttpOperation( 6592): 	at ihi.a(PG:22)
E/HttpOperation( 6592): 	at kft.a(PG:91)
E/HttpOperation( 6592): 	at kfv.a(PG:62)
E/HttpOperation( 6592): 	... 8 more
E/HttpOperation( 6592): Caused by: gdi: User intervention required. Notification has been pushed.
E/HttpOperation( 6592): 	at gde.c(Unknown Source)
E/HttpOperation( 6592): 	at gde.b(Unknown Source)
E/HttpOperation( 6592): 	at ihi.a(PG:19)
E/HttpOperation( 6592): 	... 10 more
,I/GLSUser ( 1739): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
I/GLSUser ( 1739): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1739): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1739): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1739): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/BitmapFactory( 1739): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  918): uri = 14 selection = getSealedState
D/SecContentProvider2(  918): mCursor = null
D/SecContentProvider2(  918): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  918): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy(  918): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/StatusBar( 1173): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,I/PhoneStatusBar( 1173): Icon Only
D/LockPatternUtilsCache( 1173): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1173): value : false
D/PanelView( 1173): There is/are notification(s) 
D/PanelView( 1173): There is/are notification(s) 
,E/HttpOperation( 6592): [getmobileexperiments] Unexpected exception
E/HttpOperation( 6592): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 6592): 	at kfv.a(PG:65)
E/HttpOperation( 6592): 	at kff.u(PG:385)
E/HttpOperation( 6592): 	at kfb.a(PG:29)
E/HttpOperation( 6592): 	at kff.l(PG:132)
E/HttpOperation( 6592): 	at ieo.a(PG:43)
E/HttpOperation( 6592): 	at iep.a(PG:93)
E/HttpOperation( 6592): 	at fhn.a(PG:59)
E/HttpOperation( 6592): 	at lex.a(PG:85)
E/HttpOperation( 6592): 	at lex.b(PG:132)
E/HttpOperation( 6592): 	at fhk.a(PG:1146)
E/HttpOperation( 6592): 	at fhk.a(PG:908)
E/HttpOperation( 6592): 	at fhk.onPerformSync(PG:636)
E/HttpOperation( 6592): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/HttpOperation( 6592): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/HttpOperation( 6592): 	at ihi.a(PG:22)
E/HttpOperation( 6592): 	at kft.a(PG:91)
E/HttpOperation( 6592): 	at kfv.a(PG:62)
E/HttpOperation( 6592): 	... 12 more
E/HttpOperation( 6592): Caused by: gdi: User intervention required. Notification has been pushed.
E/HttpOperation( 6592): 	at gde.c(Unknown Source)
E/HttpOperation( 6592): 	at gde.b(Unknown Source)
E/HttpOperation( 6592): 	at ihi.a(PG:19)
E/HttpOperation( 6592): 	... 14 more
,E/ExperimentLoader( 6592): [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 6592): java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 6592): 	at kfv.a(PG:65)
E/ExperimentLoader( 6592): 	at kff.u(PG:385)
E/ExperimentLoader( 6592): 	at kfb.a(PG:29)
E/ExperimentLoader( 6592): 	at kff.l(PG:132)
E/ExperimentLoader( 6592): 	at ieo.a(PG:43)
E/ExperimentLoader( 6592): 	at iep.a(PG:93)
E/ExperimentLoader( 6592): 	at fhn.a(PG:59)
E/ExperimentLoader( 6592): 	at lex.a(PG:85)
E/ExperimentLoader( 6592): 	at lex.b(PG:132)
E/ExperimentLoader( 6592): 	at fhk.a(PG:1146)
E/ExperimentLoader( 6592): 	at fhk.a(PG:908)
E/ExperimentLoader( 6592): 	at fhk.onPerformSync(PG:636)
E/ExperimentLoader( 6592): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/ExperimentLoader( 6592): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/ExperimentLoader( 6592): 	at ihi.a(PG:22)
E/ExperimentLoader( 6592): 	at kft.a(PG:91)
E/ExperimentLoader( 6592): 	at kfv.a(PG:62)
E/ExperimentLoader( 6592): 	... 12 more
E/ExperimentLoader( 6592): Caused by: gdi: User intervention required. Notification has been pushed.
E/ExperimentLoader( 6592): 	at gde.c(Unknown Source)
E/ExperimentLoader( 6592): 	at gde.b(Unknown Source)
E/ExperimentLoader( 6592): 	at ihi.a(PG:19)
E/ExperimentLoader( 6592): 	... 14 more
,I/GLSUser ( 1739): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,I/GLSUser ( 1739): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1739): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1739): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1739): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/BitmapFactory( 1739): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  918): uri = 14 selection = getSealedState
,D/SecContentProvider2(  918): mCursor = null
D/SecContentProvider2(  918): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  918): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy(  918): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,E/SQLiteLog( 1739): (10) POSIX Error : 11 SQLite Error : 3850
,D/StatusBar( 1173): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,I/PhoneStatusBar( 1173): Icon Only
,D/LockPatternUtilsCache( 1173): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1173): value : false
D/PanelView( 1173): There is/are notification(s) 
D/PanelView( 1173): There is/are notification(s) 
,E/HttpOperation( 6592): [getaccountstatus] Unexpected exception
E/HttpOperation( 6592): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 6592): 	at kfv.a(PG:65)
E/HttpOperation( 6592): 	at kff.u(PG:385)
E/HttpOperation( 6592): 	at kfb.a(PG:29)
E/HttpOperation( 6592): 	at ixd.a(PG:248)
E/HttpOperation( 6592): 	at ixd.b(PG:206)
E/HttpOperation( 6592): 	at ixd.a(PG:175)
E/HttpOperation( 6592): 	at fig.a(PG:78)
E/HttpOperation( 6592): 	at lex.a(PG:85)
E/HttpOperation( 6592): 	at lex.b(PG:132)
E/HttpOperation( 6592): 	at fhk.a(PG:1146)
E/HttpOperation( 6592): 	at fhk.a(PG:908)
E/HttpOperation( 6592): 	at fhk.onPerformSync(PG:636)
E/HttpOperation( 6592): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/HttpOperation( 6592): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/HttpOperation( 6592): 	at ihi.a(PG:22)
E/HttpOperation( 6592): 	at kft.a(PG:91)
E/HttpOperation( 6592): 	at kfv.a(PG:62)
E/HttpOperation( 6592): 	... 12 more
E/HttpOperation( 6592): Caused by: gdi: User intervention required. Notification has been pushed.
E/HttpOperation( 6592): 	at gde.c(Unknown Source)
E/HttpOperation( 6592): 	at gde.b(Unknown Source)
E/HttpOperation( 6592): 	at ihi.a(PG:19)
E/HttpOperation( 6592): 	... 14 more
,E/EsSyncAdapterService( 6592): Sync failure
E/EsSyncAdapterService( 6592): java.io.IOException: Rpc failed
E/EsSyncAdapterService( 6592): 	at ixd.a(PG:348)
E/EsSyncAdapterService( 6592): 	at ixd.a(PG:248)
E/EsSyncAdapterService( 6592): 	at ixd.b(PG:206)
E/EsSyncAdapterService( 6592): 	at ixd.a(PG:175)
E/EsSyncAdapterService( 6592): 	at fig.a(PG:78)
E/EsSyncAdapterService( 6592): 	at lex.a(PG:85)
E/EsSyncAdapterService( 6592): 	at lex.b(PG:132)
E/EsSyncAdapterService( 6592): 	at fhk.a(PG:1146)
E/EsSyncAdapterService( 6592): 	at fhk.a(PG:908)
E/EsSyncAdapterService( 6592): 	at fhk.onPerformSync(PG:636)
E/EsSyncAdapterService( 6592): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/EsSyncAdapterService( 6592): Caused by: java.io.IOException: Cannot obtain authentication token
E/EsSyncAdapterService( 6592): 	at kfv.a(PG:65)
E/EsSyncAdapterService( 6592): 	at kff.u(PG:385)
E/EsSyncAdapterService( 6592): 	at kfb.a(PG:29)
E/EsSyncAdapterService( 6592): 	... 10 more
E/EsSyncAdapterService( 6592): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/EsSyncAdapterService( 6592): 	at ihi.a(PG:22)
E/EsSyncAdapterService( 6592): 	at kft.a(PG:91)
E/EsSyncAdapterService( 6592): 	at kfv.a(PG:62)
E/EsSyncAdapterService( 6592): 	... 12 more
E/EsSyncAdapterService( 6592): Caused by: gdi: User intervention required. Notification has been pushed.
E/EsSyncAdapterService( 6592): 	at gde.c(Unknown Source)
E/EsSyncAdapterService( 6592): 	at gde.b(Unknown Source)
E/EsSyncAdapterService( 6592): 	at ihi.a(PG:19)
E/EsSyncAdapterService( 6592): 	... 14 more
,D/ConnectivityService(  918): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/SyncManager(  918): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, PERIODIC, currentRunTime 644552, reason: Periodic, SyncResult: stats [ numIoExceptions: 2]
,D/ConnectivityService(  918): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  918): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/art     ( 1739): Explicit concurrent mark sweep GC freed 39854(2MB) AllocSpace objects, 31(2MB) LOS objects, 40% free, 18MB/30MB, paused 1.911ms total 117.332ms
,I/art     (  918): Explicit concurrent mark sweep GC freed 58574(4MB) AllocSpace objects, 104(2MB) LOS objects, 30% free, 36MB/52MB, paused 1.966ms total 133.226ms
D/SecContentProvider2(  918): uri = 11 selection = getMyKnoxAdmin
D/SecContentProvider2(  918): mCursor = null
,E/SQLiteLog( 1739): (10) POSIX Error : 11 SQLite Error : 3850
,E/SMD     (  280): DCD ON
,D/SSRM:m  (  918): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  280): DCD ON
,E/SMD     (  280): DCD ON
,D/BatteryService(  918): level:100, scale:100, status:5, health:2, present:true, voltage: 4383, temperature: 288, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  918): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  918): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  918):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  918): Plugged
,I/MotionRecognitionService(  918): setPowerConnected  = true
,D/BatteryService(  918): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1173): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1173): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1173):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3229): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3229): Disconnected process message: 10
,D/BatteryMeterView( 1173): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1173): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1173): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  280): DCD ON
,V/AlarmManager(  918): waitForAlarm result :8
,E/SMD     (  280): DCD ON
,D/SSRM:m  (  918): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  280): DCD ON
,I/PowerManagerService(  918): [PWL] Off : 525s ago
,D/ConnectivityService(  918): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/SMD     (  280): DCD ON
,E/SMD     (  280): DCD ON
,D/SSRM:m  (  918): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  280): DCD ON
,E/SMD     (  280): DCD ON
,E/Watchdog(  918): !@Sync 22
,V/AlarmManager(  918): waitForAlarm result :4
,D/KeyguardUpdateMonitor( 1173): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1173): handleTimeUpdate
,D/KeyguardEffectViewController( 1173): onReceive action : android.intent.action.TIME_TICK
,I/KeyguardEffectViewController( 1173): *** don't update sliding image ***
,D/ConnectivityService(  918): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/BatteryService(  918): level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 288, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  918): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
D/BatteryService(  918): stay LED for fully charged
D/BatteryService(  918): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  918):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  918): Plugged
I/MotionRecognitionService(  918): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1173): received broadcast android.intent.action.BATTERY_CHANGED
,V/HeadsetService( 3229): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3229): Disconnected process message: 10
,D/STATUSBAR-PhoneStatusBar( 1173):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1173): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1173): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1173): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/KeyguardUpdateMonitor( 1173): handleBatteryUpdate
,D/DateView( 1173): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1173): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,E/SMD     (  280): DCD ON
,D/SSRM:m  (  918): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  280): DCD ON
,E/SMD     (  280): DCD ON
,E/SMD     (  280): DCD ON
,E/SMD     (  280): DCD ON
,D/SSRM:m  (  918): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  280): DCD ON
,E/SMD     (  280): DCD ON
,D/BatteryService(  918): level:100, scale:100, status:5, health:2, present:true, voltage: 4383, temperature: 288, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  918): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  918): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  918):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  918): Plugged
,I/MotionRecognitionService(  918): setPowerConnected  = true
,D/BatteryService(  918): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1173): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1173): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1173):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3229): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3229): Disconnected process message: 10
,D/BatteryMeterView( 1173): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1173): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1173): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  280): DCD ON
,D/SSRM:m  (  918): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  280): DCD ON
,E/SMD     (  280): DCD ON
,E/Watchdog(  918): !@Sync 23
,D/BatteryService(  918): level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 288, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  918): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  918): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  918):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  918): Plugged
,I/MotionRecognitionService(  918): setPowerConnected  = true
,D/BatteryService(  918): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1173): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1173): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1173):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1173): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1173): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1173): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3229): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 3229): Disconnected process message: 10
,E/SMD     (  280): DCD ON
,E/SMD     (  280): DCD ON
,D/SSRM:m  (  918): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  280): DCD ON
,D/BatteryService(  918): level:100, scale:100, status:5, health:2, present:true, voltage: 4382, temperature: 288, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  918): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  918): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  918):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  918): Plugged
,I/MotionRecognitionService(  918): setPowerConnected  = true
,D/BatteryService(  918): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1173): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1173): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1173):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3229): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3229): Disconnected process message: 10
,D/BatteryMeterView( 1173): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1173): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1173): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  280): DCD ON
,V/AlarmManager(  918): waitForAlarm result :8
,E/SMD     (  280): DCD ON
,D/SSRM:m  (  918): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  280): DCD ON
,E/SMD     (  280): DCD ON
,D/BatteryService(  918): level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 287, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  918): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  918): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  918):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,D/BatteryService(  918): stay LED for fully charged
,I/MotionRecognitionService(  918): Plugged
,I/MotionRecognitionService(  918): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1173): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1173): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1173):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3229): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3229): Disconnected process message: 10
,D/BatteryMeterView( 1173): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1173): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1173): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  280): DCD ON
,D/SSRM:m  (  918): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  280): DCD ON
,E/SMD     (  280): DCD ON
,E/Watchdog(  918): !@Sync 24
,E/SMD     (  280): DCD ON
,I/PowerManagerService(  918): [PWL] Off : 600s ago
,V/AlarmManager(  918): waitForAlarm result :4
,D/KeyguardUpdateMonitor( 1173): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1173): handleTimeUpdate
,D/KeyguardEffectViewController( 1173): onReceive action : android.intent.action.TIME_TICK
,I/KeyguardEffectViewController( 1173): *** don't update sliding image ***
,D/BatteryService(  918): level:100, scale:100, status:5, health:2, present:true, voltage: 4383, temperature: 287, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  918): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  918): stay LED for fully charged
,D/BatteryService(  918): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  918):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  918): Plugged
I/MotionRecognitionService(  918): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1173): received broadcast android.intent.action.BATTERY_CHANGED
,V/HeadsetService( 3229): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3229): Disconnected process message: 10
,D/STATUSBAR-PhoneStatusBar( 1173):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1173): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1173): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1173): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/KeyguardUpdateMonitor( 1173): handleBatteryUpdate
,D/DateView( 1173): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/ConnectivityService(  918): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/DateView( 1173): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/ConnectivityService(  918): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/BooksSync( 7348): Starting books sync, d
,D/ConnectivityService(  918): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,V/GLSActivity( 1739): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1739): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
,I/GLSUser ( 1739): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1739): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1739): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1739): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ResourcesManager( 1739): creating new AssetManager and set to /system/app/Books/Books.apk
,V/BitmapFactory( 1739): DecodeImagePath(decodeResourceStream3) : res/mipmap-xxhdpi-v4/ic_launcher_play_books.png
,V/BitmapFactory( 1739): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  918): uri = 14 selection = getSealedState
,D/SecContentProvider2(  918): mCursor = null
,D/SecContentProvider2(  918): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  918): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
V/ApplicationPolicy(  918): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,W/GLSActivity( 1739): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1739): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1739): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1739): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1739): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1739): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1739): 	at android.os.Binder.execTransact(Binder.java:446)
,E/BooksAccountManager( 7348): Authentication error
E/BooksAccountManager( 7348): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 7348): android.accounts.AccountManager.convertErrorToException(AccountManager.java:1893)
E/HttpHelper( 7348): null auth token
,I/qtaguid ( 7348): Tagging socket 34 with tag 10000000000{256,0} uid -1, pid: 7348, getuid(): 10082
,D/StatusBar( 1173): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,I/PhoneStatusBar( 1173): Icon Only
,D/LockPatternUtilsCache( 1173): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1173): value : false
,D/PanelView( 1173): There is/are notification(s) 
,D/PanelView( 1173): There is/are notification(s) 
,I/qtaguid ( 7348): Tagging socket 34 with tag 10000000000{256,0} uid -1, pid: 7348, getuid(): 10082
,I/qtaguid ( 7348): Untagging socket 34
,W/ApiaryClient( 7348): Error response from books API: {
W/ApiaryClient( 7348):  "error": {
W/ApiaryClient( 7348):   "errors": [
W/ApiaryClient( 7348):    {
W/ApiaryClient( 7348):     "domain": "global",
W/ApiaryClient( 7348):     "reason": "required",
W/ApiaryClient( 7348):     "message": "Login Required",
W/ApiaryClient( 7348):     "locationType": "header",
W/ApiaryClient( 7348):     "location": "Authorization"
W/ApiaryClient( 7348):    }
W/ApiaryClient( 7348):   ],
W/ApiaryClient( 7348):   "code": 401,
W/ApiaryClient( 7348):   "message": "Login Required"
W/ApiaryClient( 7348):  }
W/ApiaryClient( 7348): }
,W/ApiaryClient( 7348): errCount = 1: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 7348): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3DS0HXd4TFLU4&nonce=2383797223446866758&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 7348): Headers suppressed
,D/ConnectivityService(  918): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/SMD     (  280): DCD ON
,D/SSRM:m  (  918): SIOP:: AP = 290, PST = 290, CUR = 300
,V/GLSActivity( 1739): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1739): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
,I/GLSUser ( 1739): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1739): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1739): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1739): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/BitmapFactory( 1739): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  918): uri = 14 selection = getSealedState
,D/SecContentProvider2(  918): mCursor = null
D/SecContentProvider2(  918): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  918): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy(  918): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/StatusBar( 1173): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,I/PhoneStatusBar( 1173): Icon Only
,D/LockPatternUtilsCache( 1173): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1173): value : false
D/PanelView( 1173): There is/are notification(s) 
D/PanelView( 1173): There is/are notification(s) 
,W/GLSActivity( 1739): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1739): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1739): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1739): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1739): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1739): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1739): 	at android.os.Binder.execTransact(Binder.java:446)
,E/BooksAccountManager( 7348): Authentication error
E/BooksAccountManager( 7348): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 7348): android.accounts.AccountManager.convertErrorToException(AccountManager.java:1893)
,E/HttpHelper( 7348): null auth token
,I/qtaguid ( 7348): Tagging socket 34 with tag 10000000000{256,0} uid -1, pid: 7348, getuid(): 10082
I/qtaguid ( 7348): Tagging socket 40 with tag 10000000000{256,0} uid -1, pid: 7348, getuid(): 10082
,I/qtaguid ( 7348): Untagging socket 34
,W/ApiaryClient( 7348): Error response from books API: {
W/ApiaryClient( 7348):  "error": {
W/ApiaryClient( 7348):   "errors": [
W/ApiaryClient( 7348):    {
W/ApiaryClient( 7348):     "domain": "global",
W/ApiaryClient( 7348):     "reason": "required",
W/ApiaryClient( 7348):     "message": "Login Required",
W/ApiaryClient( 7348):     "locationType": "header",
W/ApiaryClient( 7348):     "location": "Authorization"
W/ApiaryClient( 7348):    }
W/ApiaryClient( 7348):   ],
W/ApiaryClient( 7348):   "code": 401,
W/ApiaryClient( 7348):   "message": "Login Required"
W/ApiaryClient( 7348):  }
W/ApiaryClient( 7348): }
,W/ApiaryClient( 7348): errCount = 2: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 7348): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3DS0HXd4TFLU4&nonce=2383797223446866758&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 7348): Headers suppressed
,D/ConnectivityService(  918): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,V/GLSActivity( 1739): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1739): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
,I/GLSUser ( 1739): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1739): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1739): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1739): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/BitmapFactory( 1739): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  918): uri = 14 selection = getSealedState
,D/SecContentProvider2(  918): mCursor = null
D/SecContentProvider2(  918): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  918): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy(  918): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/StatusBar( 1173): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,I/PhoneStatusBar( 1173): Icon Only
,D/LockPatternUtilsCache( 1173): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1173): value : false
D/PanelView( 1173): There is/are notification(s) 
D/PanelView( 1173): There is/are notification(s) 
,W/GLSActivity( 1739): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1739): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1739): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1739): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1739): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1739): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1739): 	at android.os.Binder.execTransact(Binder.java:446)
,E/BooksAccountManager( 7348): Authentication error
E/BooksAccountManager( 7348): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 7348): android.accounts.AccountManager.convertErrorToException(AccountManager.java:1893)
,E/HttpHelper( 7348): null auth token
,I/qtaguid ( 7348): Tagging socket 34 with tag 10000000000{256,0} uid -1, pid: 7348, getuid(): 10082
,I/qtaguid ( 7348): Untagging socket 34
,W/ApiaryClient( 7348): Error response from books API: {
W/ApiaryClient( 7348):  "error": {
W/ApiaryClient( 7348):   "errors": [
W/ApiaryClient( 7348):    {
W/ApiaryClient( 7348):     "domain": "global",
W/ApiaryClient( 7348):     "reason": "required",
W/ApiaryClient( 7348):     "message": "Login Required",
W/ApiaryClient( 7348):     "locationType": "header",
W/ApiaryClient( 7348):     "location": "Authorization"
W/ApiaryClient( 7348):    }
W/ApiaryClient( 7348):   ],
W/ApiaryClient( 7348):   "code": 401,
W/ApiaryClient( 7348):   "message": "Login Required"
W/ApiaryClient( 7348):  }
W/ApiaryClient( 7348): }
,W/ApiaryClient( 7348): errCount = 3: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 7348): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3DS0HXd4TFLU4&nonce=2383797223446866758&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 7348): Headers suppressed
,D/ConnectivityService(  918): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/BooksSync( 7348): Soft error
E/BooksSync( 7348): com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
E/BooksSync( 7348): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3DS0HXd4TFLU4&nonce=2383797223446866758&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
E/BooksSync( 7348): Headers suppressed
E/BooksSync( 7348): 
E/BooksSync( 7348): com.google.android.apps.books.net.HttpHelper.wrapExceptionBasedOnStatus(HttpHelper.java:212)
,E/BooksSync( 7348): Sync error
E/BooksSync( 7348): com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
E/BooksSync( 7348): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3DS0HXd4TFLU4&nonce=2383797223446866758&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
E/BooksSync( 7348): Headers suppressed
E/BooksSync( 7348): 
E/BooksSync( 7348): com.google.android.apps.books.net.HttpHelper.wrapExceptionBasedOnStatus(HttpHelper.java:212)
,I/BooksSync( 7348): Finished books sync
,D/ConnectivityService(  918): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SyncManager(  918): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 738278, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,D/ConnectivityService(  918): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SecContentProvider2(  918): uri = 11 selection = getMyKnoxAdmin
,D/SecContentProvider2(  918): mCursor = null
,D/ConnectivityService(  918): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/SMD     (  280): DCD ON
,E/SMD     (  280): DCD ON
,D/BatteryService(  918): level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 287, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  918): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  918): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  918):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  918): Plugged
,I/MotionRecognitionService(  918): setPowerConnected  = true
,D/BatteryService(  918): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1173): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1173): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1173):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1173): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1173): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1173): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3229): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3229): Disconnected process message: 10
,E/SMD     (  280): DCD ON
,D/SSRM:m  (  918): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  280): DCD ON
,E/SMD     (  280): DCD ON
,E/SMD     (  280): DCD ON
,D/SSRM:m  (  918): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  280): DCD ON
,E/SMD     (  280): DCD ON
,E/Watchdog(  918): !@Sync 25
,E/SMD     (  280): DCD ON
,V/AlarmManager(  918): waitForAlarm result :4
,D/ConnectivityService(  918): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/SMD     (  280): DCD ON
,D/SSRM:m  (  918): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  280): DCD ON
,E/SMD     (  280): DCD ON
,V/AlarmManager(  918): waitForAlarm result :8
,D/BatteryService(  918): level:100, scale:100, status:5, health:2, present:true, voltage: 4386, temperature: 287, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  918): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  918): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  918):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  918): Plugged
,I/MotionRecognitionService(  918): setPowerConnected  = true
,D/BatteryService(  918): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1173): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1173): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1173):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3229): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3229): Disconnected process message: 10
,D/BatteryMeterView( 1173): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1173): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1173): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  280): DCD ON
,D/SSRM:m  (  918): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  280): DCD ON
,E/SMD     (  280): DCD ON
,E/SMD     (  280): DCD ON
,D/BatteryService(  918): level:100, scale:100, status:5, health:2, present:true, voltage: 4383, temperature: 286, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  918): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  918): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  918):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  918): Plugged
,I/MotionRecognitionService(  918): setPowerConnected  = true
,D/BatteryService(  918): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1173): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1173): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1173):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3229): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3229): Disconnected process message: 10
,D/BatteryMeterView( 1173): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1173): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1173): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:m  (  918): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  280): DCD ON
,E/SMD     (  280): DCD ON
,E/Watchdog(  918): !@Sync 26
,E/SMD     (  280): DCD ON
,E/SMD     (  280): DCD ON
,D/SSRM:m  (  918): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  280): DCD ON
,E/SMD     (  280): DCD ON
,E/SMD     (  280): DCD ON
,D/BatteryService(  918): level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 286, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  918): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  918): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  918):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  918): Plugged
,D/BatteryService(  918): stay LED for fully charged
,I/MotionRecognitionService(  918): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1173): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1173): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1173):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3229): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3229): Disconnected process message: 10
,D/BatteryMeterView( 1173): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1173): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1173): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:m  (  918): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  280): DCD ON
,E/SMD     (  280): DCD ON
,I/PowerManagerService(  918): [PWL] Off : 680s ago
,E/SMD     (  280): DCD ON
,D/SSRM:m  (  918): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  280): DCD ON
,E/SMD     (  280): DCD ON
,E/Watchdog(  918): !@Sync 27
,E/SMD     (  280): DCD ON
,D/BatteryService(  918): level:100, scale:100, status:5, health:2, present:true, voltage: 4383, temperature: 286, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  918): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  918): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  918):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  918): Plugged
,I/MotionRecognitionService(  918): setPowerConnected  = true
,D/BatteryService(  918): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1173): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1173): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1173):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3229): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3229): Disconnected process message: 10
,D/BatteryMeterView( 1173): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1173): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1173): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  280): DCD ON
,D/SSRM:m  (  918): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  280): DCD ON
,E/SMD     (  280): DCD ON
,E/SMD     (  280): DCD ON
,D/SSRM:m  (  918): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  280): DCD ON
,E/SMD     (  280): DCD ON
,E/SMD     (  280): DCD ON
,D/BatteryService(  918): level:100, scale:100, status:5, health:2, present:true, voltage: 4386, temperature: 286, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  918): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  918): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  918):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  918): Plugged
,I/MotionRecognitionService(  918): setPowerConnected  = true
,D/BatteryService(  918): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1173): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1173): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1173):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3229): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3229): Disconnected process message: 10
,D/BatteryMeterView( 1173): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1173): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1173): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:m  (  918): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  280): DCD ON
,E/SMD     (  280): DCD ON
,E/Watchdog(  918): !@Sync 28
,E/SMD     (  280): DCD ON
,D/BatteryService(  918): level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 285, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  918): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  918): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  918):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  918): Plugged
,I/MotionRecognitionService(  918): setPowerConnected  = true
,D/BatteryService(  918): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1173): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1173): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1173):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3229): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3229): Disconnected process message: 10
,D/BatteryMeterView( 1173): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1173): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1173): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  280): DCD ON
,D/SSRM:m  (  918): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  280): DCD ON
,D/ConnectivityService(  918): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/SMD     (  280): DCD ON
,E/SMD     (  280): DCD ON
,D/BatteryService(  918): level:100, scale:100, status:5, health:2, present:true, voltage: 4386, temperature: 285, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  918): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  918): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  918):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,D/BatteryService(  918): stay LED for fully charged
,I/MotionRecognitionService(  918): Plugged
,I/MotionRecognitionService(  918): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1173): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1173): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1173):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3229): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3229): Disconnected process message: 10
,D/BatteryMeterView( 1173): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1173): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1173): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:m  (  918): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  280): DCD ON
,E/SMD     (  280): DCD ON
,E/SMD     (  280): DCD ON
,D/BatteryService(  918): level:100, scale:100, status:5, health:2, present:true, voltage: 4383, temperature: 285, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  918): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  918): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  918):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  918): Plugged
,I/MotionRecognitionService(  918): setPowerConnected  = true
,D/BatteryService(  918): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1173): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1173): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1173):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3229): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3229): Disconnected process message: 10
,D/BatteryMeterView( 1173): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1173): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1173): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:m  (  918): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  280): DCD ON
,E/SMD     (  280): DCD ON
,E/Watchdog(  918): !@Sync 29
,E/SMD     (  280): DCD ON
,D/BatteryService(  918): level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 285, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  918): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  918): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  918):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  918): Plugged
,D/BatteryService(  918): stay LED for fully charged
,I/MotionRecognitionService(  918): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1173): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1173): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1173):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1173): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1173): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1173): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3229): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3229): Disconnected process message: 10
,E/SMD     (  280): DCD ON
,D/SSRM:m  (  918): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  280): DCD ON
,E/SMD     (  280): DCD ON
,E/SMD     (  280): DCD ON
,D/SSRM:m  (  918): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  280): DCD ON
,I/PowerManagerService(  918): [PWL] Off : 765s ago
,E/SMD     (  280): DCD ON
,E/SMD     (  280): DCD ON
,D/BatteryService(  918): level:100, scale:100, status:5, health:2, present:true, voltage: 4382, temperature: 285, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  918): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  918): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  918):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  918): Plugged
,I/MotionRecognitionService(  918): setPowerConnected  = true
,D/BatteryService(  918): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1173): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1173): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1173):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3229): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3229): Disconnected process message: 10
,D/BatteryMeterView( 1173): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1173): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1173): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:m  (  918): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  280): DCD ON
,D/TimaService(  918): TIMA: TimaService scheduler is intialized. 
,D/TimaService(  918): TIMA: checkEvent, operation: 50000 subject: 10000
,D/TimaService(  918): TimaServiceHandler.handleMessage what =1
,E/SMD     (  280): DCD ON
,E/Watchdog(  918): !@Sync 30
,I/TLC_TIMA_PKM_measure_kernel(  918): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel(  918): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService(  918): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService(  918): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,E/SMD     (  280): DCD ON
,E/SMD     (  280): DCD ON
,D/BatteryService(  918): level:100, scale:100, status:5, health:2, present:true, voltage: 4383, temperature: 285, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  918): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  918): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  918):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  918): Plugged
,I/MotionRecognitionService(  918): setPowerConnected  = true
,D/BatteryService(  918): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1173): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1173): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1173):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3229): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3229): Disconnected process message: 10
,D/BatteryMeterView( 1173): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1173): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1173): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:m  (  918): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  280): DCD ON
,E/SMD     (  280): DCD ON
,E/SMD     (  280): DCD ON
,D/BatteryService(  918): level:100, scale:100, status:5, health:2, present:true, voltage: 4382, temperature: 285, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  918): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  918): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  918):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  918): Plugged
,I/MotionRecognitionService(  918): setPowerConnected  = true
,D/BatteryService(  918): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1173): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1173): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1173):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3229): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3229): Disconnected process message: 10
,D/BatteryMeterView( 1173): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1173): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1173): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:m  (  918): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  280): DCD ON
,E/SMD     (  280): DCD ON
,E/SMD     (  280): DCD ON
,D/BatteryService(  918): level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 285, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  918): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  918): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  918):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  918): Plugged
,I/MotionRecognitionService(  918): setPowerConnected  = true
,D/BatteryService(  918): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1173): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1173): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1173):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1173): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1173): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1173): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3229): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3229): Disconnected process message: 10
,E/SMD     (  280): DCD ON
,D/SSRM:m  (  918): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  280): DCD ON
,E/Watchdog(  918): !@Sync 31
,E/SMD     (  280): DCD ON
,E/SMD     (  280): DCD ON
,D/BatteryService(  918): level:100, scale:100, status:5, health:2, present:true, voltage: 4386, temperature: 284, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  918): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  918): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  918):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  918): Plugged
,I/MotionRecognitionService(  918): setPowerConnected  = true
,D/BatteryService(  918): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1173): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1173): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1173):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3229): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3229): Disconnected process message: 10
,D/BatteryMeterView( 1173): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1173): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1173): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:m  (  918): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  280): DCD ON
,E/SMD     (  280): DCD ON
,E/SMD     (  280): DCD ON
,D/BatteryService(  918): level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 284, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  918): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  918): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  918):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  918): Plugged
,I/MotionRecognitionService(  918): setPowerConnected  = true
,D/BatteryService(  918): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1173): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1173): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1173):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3229): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3229): Disconnected process message: 10
,D/BatteryMeterView( 1173): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1173): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1173): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:m  (  918): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  280): DCD ON
,E/SMD     (  280): DCD ON
,E/SMD     (  280): DCD ON
,D/BatteryService(  918): level:100, scale:100, status:5, health:2, present:true, voltage: 4383, temperature: 284, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  918): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  918): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  918):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  918): Plugged
,I/MotionRecognitionService(  918): setPowerConnected  = true
,D/BatteryService(  918): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1173): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1173): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1173):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1173): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1173): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1173): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3229): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3229): Disconnected process message: 10
,E/SMD     (  280): DCD ON
,D/SSRM:m  (  918): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  280): DCD ON
,E/Watchdog(  918): !@Sync 32
,E/SMD     (  280): DCD ON
,E/SMD     (  280): DCD ON
,D/BatteryService(  918): level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 284, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  918): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  918): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  918):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  918): Plugged
,I/MotionRecognitionService(  918): setPowerConnected  = true
,D/BatteryService(  918): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1173): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1173): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1173):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3229): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3229): Disconnected process message: 10
,D/BatteryMeterView( 1173): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1173): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1173): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:m  (  918): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  280): DCD ON
,E/SMD     (  280): DCD ON
,E/SMD     (  280): DCD ON
,D/BatteryService(  918): level:100, scale:100, status:5, health:2, present:true, voltage: 4383, temperature: 284, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  918): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  918): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  918):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  918): Plugged
,I/MotionRecognitionService(  918): setPowerConnected  = true
,D/BatteryService(  918): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1173): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1173): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1173):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3229): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3229): Disconnected process message: 10
,D/BatteryMeterView( 1173): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1173): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1173): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:m  (  918): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  280): DCD ON
,I/PowerManagerService(  918): [PWL] Off : 855s ago
,E/SMD     (  280): DCD ON
,E/SMD     (  280): DCD ON
,E/SMD     (  280): DCD ON
,D/SSRM:m  (  918): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  280): DCD ON
,E/Watchdog(  918): !@Sync 33
,V/AlarmManager(  918): waitForAlarm result :4
,D/LightsService(  918): [api] onReceive : SvcLEDReceiver re-enables LightSenor and sends MSG_FORCEDSVCLEDTASK
,E/LightSensor(  918): Light old sensor_state 8192, new sensor_state : 8704 en : 1
,D/SensorManager(  918): registerListener :: 6, TMG399X RGB Sensor, 200000, 0,  
,D/KeyguardUpdateMonitor( 1173): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1173): handleTimeUpdate
,D/BatteryService(  918): level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 284, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  918): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
D/BatteryService(  918): stay LED for fully charged
,D/KeyguardEffectViewController( 1173): onReceive action : android.intent.action.TIME_TICK
,I/KeyguardEffectViewController( 1173): *** don't update sliding image ***
,D/BatteryService(  918): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  918):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  918): Plugged
,I/MotionRecognitionService(  918): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1173): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1173): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1173):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3229): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3229): Disconnected process message: 10
,D/BatteryMeterView( 1173): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1173): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1173): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/DateView( 1173): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1173): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,I/EventLogService( 2454): Aggregate from 1450656397668 (log), 1450656397668 (data)
,D/GCM     ( 1739): Message class com.google.f.a.a.i
,D/ConnectivityService(  918): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  918): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/LightSensor(  918): RED : 0, GREEN : 0, BLUE : 0, CLEAR : 1, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/LightsService(  918): [SvcLED]  onSensorChanged::light value = 0
E/LightSensor(  918): Light old sensor_state 8704, new sensor_state : 8192 en : 0
,D/SensorManager(  918): unregisterListener ::   
D/LightsService(  918): [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=4) maintains its priority right
,E/SMD     (  280): DCD ON
,E/SMD     (  280): DCD ON
,D/SSRM:m  (  918): SIOP:: AP = 290, PST = 290, CUR = 300,
,E/SMD     (  280): DCD ON
,D/BatteryService(  918): level:100, scale:100, status:5, health:2, present:true, voltage: 4382, temperature: 284, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  918): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  918): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  918):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  918): Plugged
,I/MotionRecognitionService(  918): setPowerConnected  = true
,D/BatteryService(  918): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1173): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1173): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1173):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3229): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3229): Disconnected process message: 10
,D/BatteryMeterView( 1173): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1173): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1173): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  280): DCD ON
,V/AlarmManager(  918): waitForAlarm result :8
,E/SMD     (  280): DCD ON
,D/SSRM:m  (  918): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  280): DCD ON
,E/SMD     (  280): DCD ON
,D/BatteryService(  918): level:100, scale:100, status:5, health:2, present:true, voltage: 4383, temperature: 284, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  918): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  918): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  918):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  918): Plugged
,I/MotionRecognitionService(  918): setPowerConnected  = true
,D/BatteryService(  918): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1173): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1173): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1173):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3229): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3229): Disconnected process message: 10
,D/BatteryMeterView( 1173): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1173): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1173): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  280): DCD ON
,E/SMD     (  280): DCD ON
,D/SSRM:m  (  918): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  280): DCD ON
,E/Watchdog(  918): !@Sync 34
,D/BatteryService(  918): level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 284, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  918): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  918): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  918):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  918): Plugged
,D/BatteryService(  918): stay LED for fully charged
,I/MotionRecognitionService(  918): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1173): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1173): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1173):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3229): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3229): Disconnected process message: 10
,D/BatteryMeterView( 1173): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1173): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1173): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  280): DCD ON
,E/SMD     (  280): DCD ON
,D/SSRM:m  (  918): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  280): DCD ON
,D/BatteryService(  918): level:100, scale:100, status:5, health:2, present:true, voltage: 4383, temperature: 284, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  918): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  918): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  918):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  918): Plugged
,I/MotionRecognitionService(  918): setPowerConnected  = true
,D/BatteryService(  918): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1173): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1173): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1173):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3229): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3229): Disconnected process message: 10
,D/BatteryMeterView( 1173): ACTION_BATTERY_CHANGED : level:100 status:5 health:2,
D/BatteryMeterView( 1173): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1173): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  280): DCD ON
,E/SMD     (  280): DCD ON
,D/SSRM:m  (  918): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  280): DCD ON
,E/SMD     (  280): DCD ON
,D/BatteryService(  918): level:100, scale:100, status:5, health:2, present:true, voltage: 4383, temperature: 283, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  918): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  918): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  918):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  918): Plugged
,I/MotionRecognitionService(  918): setPowerConnected  = true
,D/BatteryService(  918): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1173): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1173): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1173):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1173): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1173): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1173): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3229): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3229): Disconnected process message: 10
,E/SMD     (  280): DCD ON
,E/SMD     (  280): DCD ON
,D/SSRM:m  (  918): SIOP:: AP = 280, PST = 289, CUR = 300
,E/SMD     (  280): DCD ON
,E/Watchdog(  918): !@Sync 35
,E/SMD     (  280): DCD ON
,E/SMD     (  280): DCD ON
,D/SSRM:m  (  918): SIOP:: AP = 280, PST = 288, CUR = 300
,E/SMD     (  280): DCD ON
,D/BatteryService(  918): level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 283, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  918): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  918): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  918):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  918): Plugged
,I/MotionRecognitionService(  918): setPowerConnected  = true
,D/BatteryService(  918): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1173): received broadcast android.intent.action.BATTERY_CHANGED
,E/SMD     (  280): DCD ON
,D/KeyguardUpdateMonitor( 1173): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1173):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3229): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3229): Disconnected process message: 10
,D/BatteryMeterView( 1173): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1173): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1173): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  280): DCD ON
,D/SSRM:m  (  918): SIOP:: AP = 280, PST = 287, CUR = 300
,E/SMD     (  280): DCD ON
,E/SMD     (  280): DCD ON
,D/BatteryService(  918): level:100, scale:100, status:5, health:2, present:true, voltage: 4382, temperature: 283, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  918): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  918): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  918):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  918): Plugged
,I/MotionRecognitionService(  918): setPowerConnected  = true
,D/BatteryService(  918): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1173): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1173): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1173):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3229): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3229): Disconnected process message: 10
,D/BatteryMeterView( 1173): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1173): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1173): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/PowerManagerService(  918): [PWL] Off : 950s ago
,E/SMD     (  280): DCD ON
,E/SMD     (  280): DCD ON
,D/SSRM:m  (  918): SIOP:: AP = 280, PST = 286, CUR = 300
,E/SMD     (  280): DCD ON
,E/Watchdog(  918): !@Sync 36
,D/BatteryService(  918): level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 283, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  918): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  918): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  918):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  918): Plugged
,I/MotionRecognitionService(  918): setPowerConnected  = true
,D/BatteryService(  918): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1173): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1173): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1173):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3229): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3229): Disconnected process message: 10
,D/BatteryMeterView( 1173): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1173): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1173): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  280): DCD ON
,E/SMD     (  280): DCD ON
,D/SSRM:m  (  918): SIOP:: AP = 280, PST = 285, CUR = 300
,E/SMD     (  280): DCD ON
,E/SMD     (  280): DCD ON
,E/SMD     (  280): DCD ON
,D/SSRM:m  (  918): SIOP:: AP = 270, PST = 283, CUR = 300
,E/SMD     (  280): DCD ON
,E/SMD     (  280): DCD ON
,D/BatteryService(  918): level:100, scale:100, status:5, health:2, present:true, voltage: 4383, temperature: 283, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  918): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  918): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  918):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  918): Plugged
,D/BatteryService(  918): stay LED for fully charged
,I/MotionRecognitionService(  918): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1173): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1173): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1173):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3229): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3229): Disconnected process message: 10
,D/BatteryMeterView( 1173): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1173): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1173): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  280): DCD ON
,E/SMD     (  280): DCD ON
,D/SSRM:m  (  918): SIOP:: AP = 270, PST = 281, CUR = 300
,E/SMD     (  280): DCD ON
,E/Watchdog(  918): !@Sync 37
,E/SMD     (  280): DCD ON
,E/SMD     (  280): DCD ON
,D/SSRM:m  (  918): SIOP:: AP = 270, PST = 279, CUR = 300
,E/SMD     (  280): DCD ON
,V/AlarmManager(  918): waitForAlarm result :4
,D/KeyguardUpdateMonitor( 1173): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1173): handleTimeUpdate
,D/KeyguardEffectViewController( 1173): onReceive action : android.intent.action.TIME_TICK
,I/KeyguardEffectViewController( 1173): *** don't update sliding image ***
,D/BatteryService(  918): level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 283, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  918): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  918): stay LED for fully charged
,D/BatteryService(  918): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  918):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  918): Plugged
I/MotionRecognitionService(  918): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1173): received broadcast android.intent.action.BATTERY_CHANGED
,D/STATUSBAR-PhoneStatusBar( 1173):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1173): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/KeyguardUpdateMonitor( 1173): handleBatteryUpdate
,V/HeadsetService( 3229): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3229): Disconnected process message: 10
,D/BatteryMeterView( 1173): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1173): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/DateView( 1173): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1173): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,E/SMD     (  280): DCD ON
,D/ConnectivityService(  918): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  918): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/GLSUser ( 1739): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,I/GLSUser ( 1739): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1739): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1739): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1739): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ResourcesManager( 1739): creating new AssetManager and set to /system/app/PlusOne/PlusOne.apk
,V/BitmapFactory( 1739): DecodeImagePath(decodeResourceStream3) : res/mipmap-xxhdpi-v4/quantum_logo_google_plus_color_44in48.png
,V/BitmapFactory( 1739): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  918): uri = 14 selection = getSealedState
,D/SecContentProvider2(  918): mCursor = null
,D/SecContentProvider2(  918): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  918): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy(  918): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/StatusBar( 1173): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,I/PhoneStatusBar( 1173): Icon Only
,D/LockPatternUtilsCache( 1173): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1173): value : false
D/PanelView( 1173): There is/are notification(s) 
D/PanelView( 1173): There is/are notification(s) 
,E/HttpOperation( 6592): [kfu{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
E/HttpOperation( 6592): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 6592): 	at kfv.a(PG:65)
E/HttpOperation( 6592): 	at kff.u(PG:385)
E/HttpOperation( 6592): 	at kfb.a(PG:29)
E/HttpOperation( 6592): 	at kff.l(PG:132)
E/HttpOperation( 6592): 	at dsf.a(PG:807)
E/HttpOperation( 6592): 	at fhk.a(PG:1126)
E/HttpOperation( 6592): 	at fhk.a(PG:908)
E/HttpOperation( 6592): 	at fhk.onPerformSync(PG:636)
E/HttpOperation( 6592): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/HttpOperation( 6592): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/HttpOperation( 6592): 	at ihi.a(PG:22)
E/HttpOperation( 6592): 	at kft.a(PG:91)
E/HttpOperation( 6592): 	at kfv.a(PG:62)
E/HttpOperation( 6592): 	... 8 more
E/HttpOperation( 6592): Caused by: gdi: User intervention required. Notification has been pushed.
E/HttpOperation( 6592): 	at gde.c(Unknown Source)
E/HttpOperation( 6592): 	at gde.b(Unknown Source)
E/HttpOperation( 6592): 	at ihi.a(PG:19)
E/HttpOperation( 6592): 	... 10 more
,I/GLSUser ( 1739): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,I/GLSUser ( 1739): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1739): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1739): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1739): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/BitmapFactory( 1739): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  918): uri = 14 selection = getSealedState
,D/SecContentProvider2(  918): mCursor = null
D/SecContentProvider2(  918): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  918): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy(  918): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,E/HttpOperation( 6592): [getmobileexperiments] Unexpected exception
E/HttpOperation( 6592): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 6592): 	at kfv.a(PG:65)
E/HttpOperation( 6592): 	at kff.u(PG:385)
E/HttpOperation( 6592): 	at kfb.a(PG:29)
E/HttpOperation( 6592): 	at kff.l(PG:132)
E/HttpOperation( 6592): 	at ieo.a(PG:43)
E/HttpOperation( 6592): 	at iep.a(PG:93)
E/HttpOperation( 6592): 	at fhn.a(PG:59)
E/HttpOperation( 6592): 	at lex.a(PG:85)
E/HttpOperation( 6592): 	at lex.b(PG:132)
E/HttpOperation( 6592): 	at fhk.a(PG:1146)
E/HttpOperation( 6592): 	at fhk.a(PG:908)
E/HttpOperation( 6592): 	at fhk.onPerformSync(PG:636)
E/HttpOperation( 6592): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/HttpOperation( 6592): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/HttpOperation( 6592): 	at ihi.a(PG:22)
E/HttpOperation( 6592): 	at kft.a(PG:91)
E/HttpOperation( 6592): 	at kfv.a(PG:62)
E/HttpOperation( 6592): 	... 12 more
E/HttpOperation( 6592): Caused by: gdi: User intervention required. Notification has been pushed.
E/HttpOperation( 6592): 	at gde.c(Unknown Source)
E/HttpOperation( 6592): 	at gde.b(Unknown Source)
E/HttpOperation( 6592): 	at ihi.a(PG:19)
E/HttpOperation( 6592): 	... 14 more
,E/ExperimentLoader( 6592): [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 6592): java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 6592): 	at kfv.a(PG:65)
E/ExperimentLoader( 6592): 	at kff.u(PG:385)
E/ExperimentLoader( 6592): 	at kfb.a(PG:29)
E/ExperimentLoader( 6592): 	at kff.l(PG:132)
E/ExperimentLoader( 6592): 	at ieo.a(PG:43)
E/ExperimentLoader( 6592): 	at iep.a(PG:93)
E/ExperimentLoader( 6592): 	at fhn.a(PG:59)
E/ExperimentLoader( 6592): 	at lex.a(PG:85)
E/ExperimentLoader( 6592): 	at lex.b(PG:132)
E/ExperimentLoader( 6592): 	at fhk.a(PG:1146)
E/ExperimentLoader( 6592): 	at fhk.a(PG:908)
E/ExperimentLoader( 6592): 	at fhk.onPerformSync(PG:636)
E/ExperimentLoader( 6592): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/ExperimentLoader( 6592): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/ExperimentLoader( 6592): 	at ihi.a(PG:22)
E/ExperimentLoader( 6592): 	at kft.a(PG:91)
E/ExperimentLoader( 6592): 	at kfv.a(PG:62)
E/ExperimentLoader( 6592): 	... 12 more
E/ExperimentLoader( 6592): Caused by: gdi: User intervention required. Notification has been pushed.
E/ExperimentLoader( 6592): 	at gde.c(Unknown Source)
E/ExperimentLoader( 6592): 	at gde.b(Unknown Source)
E/ExperimentLoader( 6592): 	at ihi.a(PG:19)
E/ExperimentLoader( 6592): 	... 14 more
D/StatusBar( 1173): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
I/PhoneStatusBar( 1173): Icon Only
D/LockPatternUtilsCache( 1173): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1173): value : false
D/PanelView( 1173): There is/are notification(s) 
D/PanelView( 1173): There is/are notification(s) 
,I/GLSUser ( 1739): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
I/GLSUser ( 1739): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1739): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1739): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 1739): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/BitmapFactory( 1739): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  918): uri = 14 selection = getSealedState
D/SecContentProvider2(  918): mCursor = null
,D/SecContentProvider2(  918): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  918): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy(  918): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/StatusBar( 1173): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,I/PhoneStatusBar( 1173): Icon Only
D/LockPatternUtilsCache( 1173): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1173): value : false
D/PanelView( 1173): There is/are notification(s) 
D/PanelView( 1173): There is/are notification(s) 
,E/HttpOperation( 6592): [getaccountstatus] Unexpected exception
E/HttpOperation( 6592): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 6592): 	at kfv.a(PG:65)
E/HttpOperation( 6592): 	at kff.u(PG:385)
E/HttpOperation( 6592): 	at kfb.a(PG:29)
E/HttpOperation( 6592): 	at ixd.a(PG:248)
E/HttpOperation( 6592): 	at ixd.b(PG:206)
E/HttpOperation( 6592): 	at ixd.a(PG:175)
E/HttpOperation( 6592): 	at fig.a(PG:78)
E/HttpOperation( 6592): 	at lex.a(PG:85)
E/HttpOperation( 6592): 	at lex.b(PG:132)
E/HttpOperation( 6592): 	at fhk.a(PG:1146)
E/HttpOperation( 6592): 	at fhk.a(PG:908)
E/HttpOperation( 6592): 	at fhk.onPerformSync(PG:636)
E/HttpOperation( 6592): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/HttpOperation( 6592): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/HttpOperation( 6592): 	at ihi.a(PG:22)
E/HttpOperation( 6592): 	at kft.a(PG:91)
E/HttpOperation( 6592): 	at kfv.a(PG:62)
E/HttpOperation( 6592): 	... 12 more
E/HttpOperation( 6592): Caused by: gdi: User intervention required. Notification has been pushed.
E/HttpOperation( 6592): 	at gde.c(Unknown Source)
E/HttpOperation( 6592): 	at gde.b(Unknown Source)
E/HttpOperation( 6592): 	at ihi.a(PG:19)
E/HttpOperation( 6592): 	... 14 more
E/EsSyncAdapterService( 6592): Sync failure
E/EsSyncAdapterService( 6592): java.io.IOException: Rpc failed
E/EsSyncAdapterService( 6592): 	at ixd.a(PG:348)
E/EsSyncAdapterService( 6592): 	at ixd.a(PG:248)
E/EsSyncAdapterService( 6592): 	at ixd.b(PG:206)
E/EsSyncAdapterService( 6592): 	at ixd.a(PG:175)
E/EsSyncAdapterService( 6592): 	at fig.a(PG:78)
E/EsSyncAdapterService( 6592): 	at lex.a(PG:85)
E/EsSyncAdapterService( 6592): 	at lex.b(PG:132)
E/EsSyncAdapterService( 6592): 	at fhk.a(PG:1146)
E/EsSyncAdapterService( 6592): 	at fhk.a(PG:908)
E/EsSyncAdapterService( 6592): 	at fhk.onPerformSync(PG:636)
E/EsSyncAdapterService( 6592): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/EsSyncAdapterService( 6592): Caused by: java.io.IOException: Cannot obtain authentication token
E/EsSyncAdapterService( 6592): 	at kfv.a(PG:65)
E/EsSyncAdapterService( 6592): 	at kff.u(PG:385)
E/EsSyncAdapterService( 6592): 	at kfb.a(PG:29)
E/EsSyncAdapterService( 6592): 	... 10 more
E/EsSyncAdapterService( 6592): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/EsSyncAdapterService( 6592): 	at ihi.a(PG:22)
E/EsSyncAdapterService( 6592): 	at kft.a(PG:91)
E/EsSyncAdapterService( 6592): 	at kfv.a(PG:62)
E/EsSyncAdapterService( 6592): 	... 12 more
E/EsSyncAdapterService( 6592): Caused by: gdi: User intervention required. Notification has been pushed.
E/EsSyncAdapterService( 6592): 	at gde.c(Unknown Source)
E/EsSyncAdapterService( 6592): 	at gde.b(Unknown Source)
E/EsSyncAdapterService( 6592): 	at ihi.a(PG:19)
E/EsSyncAdapterService( 6592): 	... 14 more
,D/ConnectivityService(  918): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/SyncManager(  918): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, PERIODIC, currentRunTime 1135250, reason: Periodic, SyncResult: stats [ numIoExceptions: 2]
D/ConnectivityService(  918): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/ConnectivityService(  918): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SecContentProvider2(  918): uri = 11 selection = getMyKnoxAdmin
,D/SecContentProvider2(  918): mCursor = null
,E/SQLiteLog( 1739): (10) POSIX Error : 11 SQLite Error : 3850
,V/AlarmManager(  918): waitForAlarm result :8
,E/SMD     (  280): DCD ON
,E/SMD     (  280): DCD ON
,D/SSRM:m  (  918): SIOP:: AP = 290, PST = 279, CUR = 300
,E/SMD     (  280): DCD ON
,D/BatteryService(  918): level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 283, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  918): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  918): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  918):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  918): Plugged
,I/MotionRecognitionService(  918): setPowerConnected  = true
,D/BatteryService(  918): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1173): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1173): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1173):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3229): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3229): Disconnected process message: 10
,D/BatteryMeterView( 1173): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1173): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1173): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  280): DCD ON
,E/SMD     (  280): DCD ON
,D/SSRM:m  (  918): SIOP:: AP = 280, PST = 278, CUR = 300
,E/Watchdog(  918): !@Sync 38
,E/SMD     (  280): DCD ON
,D/BatteryService(  918): level:100, scale:100, status:5, health:2, present:true, voltage: 4383, temperature: 283, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  918): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  918): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  918):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  918): Plugged
,I/MotionRecognitionService(  918): setPowerConnected  = true
,D/BatteryService(  918): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1173): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1173): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1173):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3229): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3229): Disconnected process message: 10
,D/BatteryMeterView( 1173): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1173): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1173): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  280): DCD ON
,E/SMD     (  280): DCD ON
,D/SSRM:m  (  918): SIOP:: AP = 280, PST = 278, CUR = 300
,E/SMD     (  280): DCD ON
,D/ConnectivityService(  918): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/SMD     (  280): DCD ON
,V/AlarmManager(  918): waitForAlarm result :4
,D/KeyguardUpdateMonitor( 1173): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1173): handleTimeUpdate
,D/KeyguardEffectViewController( 1173): onReceive action : android.intent.action.TIME_TICK
,I/KeyguardEffectViewController( 1173): *** don't update sliding image ***
,D/ConnectivityService(  918): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/BatteryService(  918): level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 283, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  918): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
D/BatteryService(  918): stay LED for fully charged
D/BatteryService(  918): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  918):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  918): Plugged
I/MotionRecognitionService(  918): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1173): received broadcast android.intent.action.BATTERY_CHANGED
,V/HeadsetService( 3229): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3229): Disconnected process message: 10
,D/STATUSBAR-PhoneStatusBar( 1173):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1173): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1173): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1173): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/KeyguardUpdateMonitor( 1173): handleBatteryUpdate
,D/DateView( 1173): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1173): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,E/SMD     (  280): DCD ON
,E/SMD     (  280): DCD ON
,D/SSRM:m  (  918): SIOP:: AP = 280, PST = 278, CUR = 300
,E/SMD     (  280): DCD ON
,D/BatteryService(  918): level:100, scale:100, status:5, health:2, present:true, voltage: 4383, temperature: 282, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  918): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  918): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  918):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  918): Plugged
,D/BatteryService(  918): stay LED for fully charged
,I/MotionRecognitionService(  918): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1173): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1173): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1173):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3229): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3229): Disconnected process message: 10
,D/BatteryMeterView( 1173): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1173): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1173): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  280): DCD ON
,E/SMD     (  280): DCD ON
,D/SSRM:m  (  918): SIOP:: AP = 270, PST = 277, CUR = 300
,E/Watchdog(  918): !@Sync 39
,E/SMD     (  280): DCD ON
,E/SMD     (  280): DCD ON
,I/PowerManagerService(  918): [PWL] Off : 1050s ago
,E/SMD     (  280): DCD ON
,D/SSRM:m  (  918): SIOP:: AP = 270, PST = 276, CUR = 300
,E/SMD     (  280): DCD ON
,E/SMD     (  280): DCD ON
,V/AlarmManager(  918): waitForAlarm result :8
,E/SMD     (  280): DCD ON
,E/SMD     (  280): DCD ON
,D/SSRM:m  (  918): SIOP:: AP = 270, PST = 275, CUR = 300
,E/SMD     (  280): DCD ON
,D/BatteryService(  918): level:100, scale:100, status:5, health:2, present:true, voltage: 4386, temperature: 282, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  918): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  918): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  918):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  918): Plugged
,I/MotionRecognitionService(  918): setPowerConnected  = true
,D/BatteryService(  918): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1173): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1173): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1173):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3229): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3229): Disconnected process message: 10
,D/BatteryMeterView( 1173): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1173): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1173): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  280): DCD ON
,E/SMD     (  280): DCD ON
,D/TimaService(  918): TIMA: TimaService scheduler is intialized. 
,D/TimaService(  918): TIMA: checkEvent, operation: 50000 subject: 10000
,D/TimaService(  918): TimaServiceHandler.handleMessage what =1
,I/UsageStatsService(  918): User[0] Flushing usage stats to disk
,I/ApplicationUsage(  918): handleMessage : MSG_UPDATE_USAGE_DB
,I/ApplicationUsage(  918): Updating Usage Statistics in DB @ 1450659073939
,I/ApplicationUsageDb(  918): ::getAppControlDB: Exception to create DB
,W/System.err(  918): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,W/System.err(  918): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
,W/System.err(  918): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateForeGroundUsageDetails(ApplicationUsageDb.java:82)
,W/System.err(  918): 	at com.android.server.enterprise.application.ApplicationUsage.updateForeGroundUsageData(ApplicationUsage.java:271)
W/System.err(  918): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:252)
W/System.err(  918): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
,W/System.err(  918): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  918): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  918): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/ApplicationUsageDb(  918): ::getAppControlDB: Exception to create DB
W/System.err(  918): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  918): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  918): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateForeGroundUsageDetails(ApplicationUsageDb.java:82)
,W/System.err(  918): 	at com.android.server.enterprise.application.ApplicationUsage.updateForeGroundUsageData(ApplicationUsage.java:275)
,W/System.err(  918): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:252)
W/System.err(  918): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  918): 	at android.os.Handler.dispatchMessage(Handler.java:102)
,W/System.err(  918): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  918): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  918): ::getAppControlDB: Exception to create DB
W/System.err(  918): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,W/System.err(  918): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  918): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateForeGroundUsageDetails(ApplicationUsageDb.java:82)
W/System.err(  918): 	at com.android.server.enterprise.application.ApplicationUsage.updateForeGroundUsageData(ApplicationUsage.java:271)
W/System.err(  918): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:252)
,W/System.err(  918): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  918): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  918): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  918): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/ApplicationUsageDb(  918): ::getAppControlDB: Exception to create DB
,W/System.err(  918): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  918): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  918): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateForeGroundUsageDetails(ApplicationUsageDb.java:82)
W/System.err(  918): 	at com.android.server.enterprise.application.ApplicationUsage.updateForeGroundUsageData(ApplicationUsage.java:271)
W/System.err(  918): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:252)
,W/System.err(  918): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  918): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  918): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  918): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  918): ::getAppControlDB: Exception to create DB
,W/System.err(  918): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  918): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  918): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  918): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  918): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  918): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
,W/System.err(  918): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  918): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  918): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  918): ::getAppControlDB: Exception to create DB
W/System.err(  918): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,W/System.err(  918): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
,W/System.err(  918): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  918): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  918): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  918): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  918): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  918): 	at android.os.Looper.loop(Looper.java:145)
,W/System.err(  918): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  918): ::getAppControlDB: Exception to create DB
W/System.err(  918): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  918): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
,W/System.err(  918): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  918): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  918): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  918): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  918): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  918): 	at android.os.Looper.loop(Looper.java:145)
,W/System.err(  918): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  918): ::getAppControlDB: Exception to create DB
W/System.err(  918): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  918): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
,W/System.err(  918): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
,W/System.err(  918): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  918): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  918): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  918): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  918): 	at android.os.Looper.loop(Looper.java:145)
,W/System.err(  918): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  918): ::getAppControlDB: Exception to create DB
W/System.err(  918): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  918): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  918): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
,W/System.err(  918): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  918): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  918): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  918): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  918): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  918): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/ApplicationUsageDb(  918): ::getAppControlDB: Exception to create DB
W/System.err(  918): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  918): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  918): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
,W/System.err(  918): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
,W/System.err(  918): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  918): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
,W/System.err(  918): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  918): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  918): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  918): ::getAppControlDB: Exception to create DB
W/System.err(  918): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,W/System.err(  918): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  918): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  918): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  918): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  918): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  918): 	at android.os.Handler.dispatchMessage(Handler.java:102)
,W/System.err(  918): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  918): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  918): ::getAppControlDB: Exception to create DB
W/System.err(  918): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  918): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
,W/System.err(  918): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  918): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  918): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  918): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  918): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  918): 	at android.os.Looper.loop(Looper.java:145)
,W/System.err(  918): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/ApplicationUsageDb(  918): ::getAppControlDB: Exception to create DB
W/System.err(  918): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  918): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
,W/System.err(  918): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  918): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  918): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  918): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  918): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  918): 	at android.os.Looper.loop(Looper.java:145)
,W/System.err(  918): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  918): ::getAppControlDB: Exception to create DB
W/System.err(  918): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  918): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  918): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
,W/System.err(  918): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:299)
W/System.err(  918): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  918): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  918): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  918): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  918): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  918): ::getAppControlDB: Exception to create DB
W/System.err(  918): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  918): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  918): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  918): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  918): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  918): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  918): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  918): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  918): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  918): ::getAppControlDB: Exception to create DB
W/System.err(  918): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  918): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  918): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  918): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  918): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  918): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  918): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  918): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  918): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  918): ::getAppControlDB: Exception to create DB
W/System.err(  918): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  918): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  918): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  918): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  918): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  918): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  918): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  918): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  918): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  918): ::getAppControlDB: Exception to create DB
W/System.err(  918): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  918): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  918): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  918): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  918): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  918): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  918): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  918): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  918): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  918): ::getAppControlDB: Exception to create DB
W/System.err(  918): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  918): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  918): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  918): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  918): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  918): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  918): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  918): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  918): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  918): ::getAppControlDB: Exception to create DB
W/System.err(  918): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  918): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  918): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  918): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  918): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  918): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  918): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  918): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  918): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  918): ::getAppControlDB: Exception to create DB
W/System.err(  918): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  918): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  918): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  918): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  918): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  918): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  918): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  918): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  918): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  918): ::getAppControlDB: Exception to create DB
W/System.err(  918): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  918): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  918): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  918): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  918): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  918): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  918): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  918): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  918): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  918): ::getAppControlDB: Exception to create DB
W/System.err(  918): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  918): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  918): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  918): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  918): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  918): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  918): 	at android.os.Handler.dispatchMessage(Handler.java:102)
,W/System.err(  918): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  918): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  918): ::getAppControlDB: Exception to create DB
W/System.err(  918): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  918): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  918): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  918): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  918): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  918): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  918): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  918): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  918): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  918): ::getAppControlDB: Exception to create DB
W/System.err(  918): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  918): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  918): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  918): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  918): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  918): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  918): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  918): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  918): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  918): ::getAppControlDB: Exception to create DB
W/System.err(  918): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  918): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  918): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  918): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  918): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  918): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  918): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  918): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  918): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  918): ::getAppControlDB: Exception to create DB
W/System.err(  918): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  918): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  918): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  918): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  918): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  918): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  918): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  918): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  918): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  918): ::getAppControlDB: Exception to create DB
W/System.err(  918): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  918): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  918): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  918): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  918): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  918): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  918): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  918): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  918): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  918): ::getAppControlDB: Exception to create DB
W/System.err(  918): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  918): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  918): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  918): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  918): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  918): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  918): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  918): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  918): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  918): ::getAppControlDB: Exception to create DB
W/System.err(  918): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  918): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  918): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  918): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  918): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  918): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  918): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  918): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  918): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  918): ::getAppControlDB: Exception to create DB
W/System.err(  918): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  918): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  918): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  918): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  918): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  918): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  918): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  918): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  918): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  918): ::getAppControlDB: Exception to create DB
W/System.err(  918): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  918): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  918): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  918): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  918): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  918): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  918): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  918): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  918): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  918): ::getAppControlDB: Exception to create DB
W/System.err(  918): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  918): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  918): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  918): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  918): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  918): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  918): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  918): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  918): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/ApplicationUsageDb(  918): ::getAppControlDB: Exception to create DB
W/System.err(  918): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  918): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  918): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  918): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  918): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  918): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  918): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  918): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  918): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  918): ::getAppControlDB: Exception to create DB
W/System.err(  918): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  918): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  918): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  918): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  918): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  918): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  918): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  918): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  918): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  918): ::getAppControlDB: Exception to create DB
W/System.err(  918): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  918): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  918): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  918): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  918): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  918): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  918): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  918): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  918): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  918): ::getAppControlDB: Exception to create DB
W/System.err(  918): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  918): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  918): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  918): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:299)
W/System.err(  918): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  918): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  918): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  918): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  918): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  918): ::getAppControlDB: Exception to create DB
W/System.err(  918): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  918): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  918): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  918): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  918): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  918): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  918): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  918): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  918): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  918): ::getAppControlDB: Exception to create DB
W/System.err(  918): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  918): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  918): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  918): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:299)
W/System.err(  918): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  918): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  918): 	at android.os.Handler.dispatchMessage(Handler.java:102)
,W/System.err(  918): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  918): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/ApplicationUsageDb(  918): ::getAppControlDB: Exception to create DB
W/System.err(  918): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,W/System.err(  918): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  918): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
,W/System.err(  918): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  918): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
,W/System.err(  918): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  918): 	at android.os.Handler.dispatchMessage(Handler.java:102)
,W/System.err(  918): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  918): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/ApplicationUsageDb(  918): ::getAppControlDB: Exception to create DB
,W/System.err(  918): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  918): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
,W/System.err(  918): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  918): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  918): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  918): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  918): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  918): 	at android.os.Looper.loop(Looper.java:145)
,W/System.err(  918): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  918): ::getAppControlDB: Exception to create DB
W/System.err(  918): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  918): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
,W/System.err(  918): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  918): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  918): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  918): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  918): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  918): 	at android.os.Looper.loop(Looper.java:145)
,W/System.err(  918): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  918): ::getAppControlDB: Exception to create DB
W/System.err(  918): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  918): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  918): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
,W/System.err(  918): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  918): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  918): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  918): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  918): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  918): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  918): ::getAppControlDB: Exception to create DB
W/System.err(  918): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  918): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  918): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  918): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  918): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  918): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  918): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  918): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  918): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  918): ::getAppControlDB: Exception to create DB
W/System.err(  918): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  918): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  918): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  918): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  918): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  918): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  918): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  918): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  918): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  918): ::getAppControlDB: Exception to create DB
W/System.err(  918): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  918): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  918): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  918): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  918): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  918): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  918): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  918): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  918): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  918): ::getAppControlDB: Exception to create DB
W/System.err(  918): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  918): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  918): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  918): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  918): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  918): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  918): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  918): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  918): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  918): ::getAppControlDB: Exception to create DB
W/System.err(  918): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  918): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  918): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  918): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  918): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  918): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  918): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  918): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  918): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  918): ::getAppControlDB: Exception to create DB
W/System.err(  918): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  918): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  918): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  918): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  918): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  918): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  918): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  918): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  918): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  918): ::getAppControlDB: Exception to create DB
W/System.err(  918): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  918): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  918): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  918): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  918): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  918): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  918): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  918): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  918): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  918): ::getAppControlDB: Exception to create DB
W/System.err(  918): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  918): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  918): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  918): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  918): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  918): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  918): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  918): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  918): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  918): ::getAppControlDB: Exception to create DB
W/System.err(  918): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  918): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  918): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  918): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  918): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  918): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  918): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  918): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  918): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  918): ::getAppControlDB: Exception to create DB
W/System.err(  918): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  918): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  918): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  918): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  918): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  918): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  918): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  918): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  918): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  918): ::getAppControlDB: Exception to create DB
W/System.err(  918): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  918): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  918): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  918): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  918): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  918): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  918): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  918): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  918): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  918): ::getAppControlDB: Exception to create DB
W/System.err(  918): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  918): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  918): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  918): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  918): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  918): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  918): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  918): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  918): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  918): ::getAppControlDB: Exception to create DB
W/System.err(  918): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  918): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  918): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  918): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  918): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  918): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  918): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  918): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  918): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  918): ::getAppControlDB: Exception to create DB
W/System.err(  918): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  918): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  918): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  918): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  918): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  918): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  918): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  918): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  918): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  918): ::getAppControlDB: Exception to create DB
W/System.err(  918): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  918): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  918): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  918): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  918): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  918): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  918): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  918): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  918): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  918): ::getAppControlDB: Exception to create DB
W/System.err(  918): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  918): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  918): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  918): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  918): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  918): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  918): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  918): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  918): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/ApplicationUsageDb(  918): ::getAppControlDB: Exception to create DB
W/System.err(  918): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  918): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  918): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  918): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  918): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  918): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  918): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  918): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  918): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  918): ::getAppControlDB: Exception to create DB
W/System.err(  918): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  918): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  918): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  918): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  918): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  918): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  918): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  918): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  918): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsage(  918): Done Updating Usage Statistics in DB @ 1450659074168
,D/SSRM:m  (  918): SIOP:: AP = 270, PST = 275, CUR = 300
,E/Watchdog(  918): !@Sync 40
,E/SMD     (  280): DCD ON
,I/TLC_TIMA_PKM_measure_kernel(  918): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel(  918): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService(  918): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService(  918): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/BatteryService(  918): level:100, scale:100, status:5, health:2, present:true, voltage: 4383, temperature: 282, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  918): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  918): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  918):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  918): Plugged
,I/MotionRecognitionService(  918): setPowerConnected  = true
,D/BatteryService(  918): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1173): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1173): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1173):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3229): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3229): Disconnected process message: 10
,D/BatteryMeterView( 1173): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1173): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1173): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  280): DCD ON
,E/SMD     (  280): DCD ON
,D/SSRM:m  (  918): SIOP:: AP = 290, PST = 277, CUR = 300
,E/SMD     (  280): DCD ON
,E/SMD     (  280): DCD ON
,D/BatteryService(  918): level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 282, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  918): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  918): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  918):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  918): Plugged
,I/MotionRecognitionService(  918): setPowerConnected  = true
,D/BatteryService(  918): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1173): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1173): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1173):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3229): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3229): Disconnected process message: 10
,D/BatteryMeterView( 1173): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1173): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1173): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  280): DCD ON
,E/SMD     (  280): DCD ON
,D/SSRM:m  (  918): SIOP:: AP = 280, PST = 278, CUR = 300
,E/SMD     (  280): DCD ON
,E/SMD     (  280): DCD ON
,E/SMD     (  280): DCD ON
,D/SSRM:m  (  918): SIOP:: AP = 270, PST = 276, CUR = 300
,E/Watchdog(  918): !@Sync 41
,E/SMD     (  280): DCD ON
,D/BatteryService(  918): level:100, scale:100, status:5, health:2, present:true, voltage: 4383, temperature: 282, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  918): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  918): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  918):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  918): Plugged
,I/MotionRecognitionService(  918): setPowerConnected  = true
,D/BatteryService(  918): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1173): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1173): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1173):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1173): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3229): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3229): Disconnected process message: 10
,D/BatteryMeterView( 1173): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1173): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  280): DCD ON
,E/SMD     (  280): DCD ON
,D/SSRM:m  (  918): SIOP:: AP = 270, PST = 275, CUR = 300
,E/SMD     (  280): DCD ON
,E/SMD     (  280): DCD ON
,E/SMD     (  280): DCD ON
,E/SMD     (  280): DCD ON
,D/ConnectivityService(  918): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SSRM:m  (  918): SIOP:: AP = 270, PST = 274, CUR = 300
,E/SMD     (  280): DCD ON
,E/SMD     (  280): DCD ON
,V/AlarmManager(  918): waitForAlarm result :4
,D/KeyguardUpdateMonitor( 1173): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1173): handleTimeUpdate
,D/KeyguardEffectViewController( 1173): onReceive action : android.intent.action.TIME_TICK
,I/KeyguardEffectViewController( 1173): *** don't update sliding image ***
,D/DateView( 1173): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1173): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/ConnectivityService(  918): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  918): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/BooksSync( 7348): Starting books sync, d
,D/ConnectivityService(  918): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,V/GLSActivity( 1739): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1739): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
,I/GLSUser ( 1739): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1739): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1739): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1739): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/BitmapFactory( 1739): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  918): uri = 14 selection = getSealedState
,D/SecContentProvider2(  918): mCursor = null
D/SecContentProvider2(  918): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  918): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy(  918): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,W/GLSActivity( 1739): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1739): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1739): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1739): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1739): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1739): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1739): 	at android.os.Binder.execTransact(Binder.java:446)
,E/BooksAccountManager( 7348): Authentication error
E/BooksAccountManager( 7348): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 7348): android.accounts.AccountManager.convertErrorToException(AccountManager.java:1893)
,E/HttpHelper( 7348): null auth token
,D/StatusBar( 1173): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,I/PhoneStatusBar( 1173): Icon Only
,D/LockPatternUtilsCache( 1173): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1173): value : false
D/PanelView( 1173): There is/are notification(s) 
D/PanelView( 1173): There is/are notification(s) 
,I/qtaguid ( 7348): Tagging socket 34 with tag 10000000000{256,0} uid -1, pid: 7348, getuid(): 10082
,I/qtaguid ( 7348): Untagging socket 34
,W/ApiaryClient( 7348): Error response from books API: {
W/ApiaryClient( 7348):  "error": {
W/ApiaryClient( 7348):   "errors": [
W/ApiaryClient( 7348):    {
W/ApiaryClient( 7348):     "domain": "global",
W/ApiaryClient( 7348):     "reason": "required",
W/ApiaryClient( 7348):     "message": "Login Required",
W/ApiaryClient( 7348):     "locationType": "header",
W/ApiaryClient( 7348):     "location": "Authorization"
W/ApiaryClient( 7348):    }
W/ApiaryClient( 7348):   ],
W/ApiaryClient( 7348):   "code": 401,
W/ApiaryClient( 7348):   "message": "Login Required"
W/ApiaryClient( 7348):  }
W/ApiaryClient( 7348): }
,W/ApiaryClient( 7348): errCount = 1: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 7348): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3DS0HXd4TFLU4&nonce=-1131922796200185489&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 7348): Headers suppressed
,D/ConnectivityService(  918): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,V/GLSActivity( 1739): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1739): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
,I/GLSUser ( 1739): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1739): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1739): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1739): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/BitmapFactory( 1739): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  918): uri = 14 selection = getSealedState
,D/SecContentProvider2(  918): mCursor = null
,D/SecContentProvider2(  918): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  918): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy(  918): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/StatusBar( 1173): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,I/PhoneStatusBar( 1173): Icon Only
,D/LockPatternUtilsCache( 1173): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1173): value : false
,D/PanelView( 1173): There is/are notification(s) 
,D/PanelView( 1173): There is/are notification(s) 
,W/GLSActivity( 1739): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1739): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1739): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1739): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1739): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1739): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1739): 	at android.os.Binder.execTransact(Binder.java:446)
,E/BooksAccountManager( 7348): Authentication error
E/BooksAccountManager( 7348): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 7348): android.accounts.AccountManager.convertErrorToException(AccountManager.java:1893)
,E/HttpHelper( 7348): null auth token
,I/qtaguid ( 7348): Tagging socket 34 with tag 10000000000{256,0} uid -1, pid: 7348, getuid(): 10082
,I/qtaguid ( 7348): Tagging socket 41 with tag 10000000000{256,0} uid -1, pid: 7348, getuid(): 10082
,I/qtaguid ( 7348): Untagging socket 34
,W/ApiaryClient( 7348): Error response from books API: {
W/ApiaryClient( 7348):  "error": {
W/ApiaryClient( 7348):   "errors": [
W/ApiaryClient( 7348):    {
W/ApiaryClient( 7348):     "domain": "global",
W/ApiaryClient( 7348):     "reason": "required",
W/ApiaryClient( 7348):     "message": "Login Required",
W/ApiaryClient( 7348):     "locationType": "header",
W/ApiaryClient( 7348):     "location": "Authorization"
W/ApiaryClient( 7348):    }
W/ApiaryClient( 7348):   ],
W/ApiaryClient( 7348):   "code": 401,
W/ApiaryClient( 7348):   "message": "Login Required"
W/ApiaryClient( 7348):  }
W/ApiaryClient( 7348): }
,W/ApiaryClient( 7348): errCount = 2: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 7348): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3DS0HXd4TFLU4&nonce=-1131922796200185489&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 7348): Headers suppressed
,D/ConnectivityService(  918): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/SMD     (  280): DCD ON
,V/GLSActivity( 1739): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1739): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
,I/GLSUser ( 1739): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1739): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1739): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1739): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/BitmapFactory( 1739): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  918): uri = 14 selection = getSealedState
,D/SecContentProvider2(  918): mCursor = null
D/SecContentProvider2(  918): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  918): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy(  918): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/StatusBar( 1173): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,I/PhoneStatusBar( 1173): Icon Only
,D/LockPatternUtilsCache( 1173): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1173): value : false
D/PanelView( 1173): There is/are notification(s) 
D/PanelView( 1173): There is/are notification(s) 
,W/GLSActivity( 1739): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1739): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1739): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1739): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1739): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1739): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1739): 	at android.os.Binder.execTransact(Binder.java:446)
,E/BooksAccountManager( 7348): Authentication error
E/BooksAccountManager( 7348): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 7348): android.accounts.AccountManager.convertErrorToException(AccountManager.java:1893)
,E/HttpHelper( 7348): null auth token
,I/qtaguid ( 7348): Tagging socket 34 with tag 10000000000{256,0} uid -1, pid: 7348, getuid(): 10082
,I/qtaguid ( 7348): Untagging socket 34
,W/ApiaryClient( 7348): Error response from books API: {
W/ApiaryClient( 7348):  "error": {
W/ApiaryClient( 7348):   "errors": [
W/ApiaryClient( 7348):    {
W/ApiaryClient( 7348):     "domain": "global",
W/ApiaryClient( 7348):     "reason": "required",
W/ApiaryClient( 7348):     "message": "Login Required",
W/ApiaryClient( 7348):     "locationType": "header",
W/ApiaryClient( 7348):     "location": "Authorization"
W/ApiaryClient( 7348):    }
W/ApiaryClient( 7348):   ],
W/ApiaryClient( 7348):   "code": 401,
W/ApiaryClient( 7348):   "message": "Login Required"
W/ApiaryClient( 7348):  }
W/ApiaryClient( 7348): }
,W/ApiaryClient( 7348): errCount = 3: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 7348): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3DS0HXd4TFLU4&nonce=-1131922796200185489&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 7348): Headers suppressed
,D/ConnectivityService(  918): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/BooksSync( 7348): Soft error
E/BooksSync( 7348): com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
E/BooksSync( 7348): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3DS0HXd4TFLU4&nonce=-1131922796200185489&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
E/BooksSync( 7348): Headers suppressed
E/BooksSync( 7348): 
E/BooksSync( 7348): com.google.android.apps.books.net.HttpHelper.wrapExceptionBasedOnStatus(HttpHelper.java:212)
,E/BooksSync( 7348): Sync error
E/BooksSync( 7348): com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
E/BooksSync( 7348): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3DS0HXd4TFLU4&nonce=-1131922796200185489&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
E/BooksSync( 7348): Headers suppressed
E/BooksSync( 7348): 
E/BooksSync( 7348): com.google.android.apps.books.net.HttpHelper.wrapExceptionBasedOnStatus(HttpHelper.java:212)
,I/BooksSync( 7348): Finished books sync
,D/ConnectivityService(  918): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SyncManager(  918): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 1267984, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,D/ConnectivityService(  918): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  918): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/art     (  918): Explicit concurrent mark sweep GC freed 82159(6MB) AllocSpace objects, 203(3MB) LOS objects, 30% free, 36MB/52MB, paused 1.830ms total 171.698ms
D/SecContentProvider2(  918): uri = 11 selection = getMyKnoxAdmin
D/SecContentProvider2(  918): mCursor = null
,D/SSRM:m  (  918): SIOP:: AP = 290, PST = 275, CUR = 300
,E/Watchdog(  918): !@Sync 42
,E/SMD     (  280): DCD ON
,E/SMD     (  280): DCD ON
,E/SMD     (  280): DCD ON
,D/SSRM:m  (  918): SIOP:: AP = 280, PST = 276, CUR = 300
,E/SMD     (  280): DCD ON
,E/SMD     (  280): DCD ON
,E/SMD     (  280): DCD ON
,E/SMD     (  280): DCD ON
,I/PowerManagerService(  918): [PWL] Off : 1155s ago
,D/SSRM:m  (  918): SIOP:: AP = 270, PST = 276, CUR = 300
,E/SMD     (  280): DCD ON
,E/SMD     (  280): DCD ON
,V/AlarmManager(  918): waitForAlarm result :4
,D/ConnectivityService(  918): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/BatteryService(  918): level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 282, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  918): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
D/BatteryService(  918): stay LED for fully charged
,D/BatteryService(  918): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  918):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  918): Plugged
I/MotionRecognitionService(  918): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1173): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1173): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1173):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3229): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3229): Disconnected process message: 10
,D/BatteryMeterView( 1173): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1173): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1173): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  280): DCD ON
,D/SSRM:m  (  918): SIOP:: AP = 270, PST = 276, CUR = 300
,E/Watchdog(  918): !@Sync 43
,E/SMD     (  280): DCD ON
,E/SMD     (  280): DCD ON
,E/SMD     (  280): DCD ON
,D/SSRM:m  (  918): SIOP:: AP = 270, PST = 276, CUR = 300
,E/SMD     (  280): DCD ON
,E/SMD     (  280): DCD ON
,V/AlarmManager(  918): waitForAlarm result :8
,E/SMD     (  280): DCD ON
,E/SMD     (  280): DCD ON
,D/SSRM:m  (  918): SIOP:: AP = 270, PST = 274, CUR = 300
,E/SMD     (  280): DCD ON
,E/SMD     (  280): DCD ON
,E/SMD     (  280): DCD ON
,D/SSRM:m  (  918): SIOP:: AP = 270, PST = 273, CUR = 300
,E/Watchdog(  918): !@Sync 44
,E/SMD     (  280): DCD ON
,E/SMD     (  280): DCD ON
,D/BatteryService(  918): level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 281, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  918): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  918): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  918):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  918): Plugged
,I/MotionRecognitionService(  918): setPowerConnected  = true
,D/BatteryService(  918): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1173): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1173): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1173):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3229): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3229): Disconnected process message: 10
,D/BatteryMeterView( 1173): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1173): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1173): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  280): DCD ON
,E/SMD     (  280): DCD ON
,D/SSRM:m  (  918): SIOP:: AP = 270, PST = 273, CUR = 300
,E/SMD     (  280): DCD ON
,D/BatteryService(  918): level:100, scale:100, status:5, health:2, present:true, voltage: 4383, temperature: 281, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  918): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  918): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  918):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,E/SMD     (  280): DCD ON
,I/MotionRecognitionService(  918): Plugged
,I/MotionRecognitionService(  918): setPowerConnected  = true
,D/BatteryService(  918): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1173): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1173): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1173):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3229): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3229): Disconnected process message: 10
,D/BatteryMeterView( 1173): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1173): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1173): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  280): DCD ON
,D/SSRM:m  (  918): SIOP:: AP = 270, PST = 273, CUR = 300
,E/SMD     (  280): DCD ON
,E/SMD     (  280): DCD ON
,D/BatteryService(  918): level:100, scale:100, status:5, health:2, present:true, voltage: 4386, temperature: 281, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  918): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  918): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  918): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1173): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1173): handleBatteryUpdate
,D/MotionRecognitionService(  918):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  918): Plugged
,I/MotionRecognitionService(  918): setPowerConnected  = true
,D/STATUSBAR-PhoneStatusBar( 1173):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3229): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3229): Disconnected process message: 10
,D/BatteryMeterView( 1173): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1173): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1173): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  280): DCD ON
,D/SSRM:m  (  918): SIOP:: AP = 270, PST = 273, CUR = 300
,E/Watchdog(  918): !@Sync 45
,E/SMD     (  280): DCD ON
,E/SMD     (  280): DCD ON
,D/BatteryService(  918): level:100, scale:100, status:5, health:2, present:true, voltage: 4383, temperature: 281, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  918): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  918): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  918):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  918): Plugged
,I/MotionRecognitionService(  918): setPowerConnected  = true
,D/BatteryService(  918): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1173): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1173): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1173):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1173): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3229): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3229): Disconnected process message: 10
D/BatteryMeterView( 1173): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1173): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  280): DCD ON
,E/SMD     (  280): DCD ON
,D/SSRM:m  (  918): SIOP:: AP = 270, PST = 271, CUR = 300
,E/SMD     (  280): DCD ON
,E/SMD     (  280): DCD ON
,D/BatteryService(  918): level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 281, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  918): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  918): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  918):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,D/BatteryService(  918): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1173): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1173): handleBatteryUpdate
,I/MotionRecognitionService(  918): Plugged
,I/MotionRecognitionService(  918): setPowerConnected  = true
,D/STATUSBAR-PhoneStatusBar( 1173):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3229): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3229): Disconnected process message: 10
,D/BatteryMeterView( 1173): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1173): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1173): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  280): DCD ON
,D/SSRM:m  (  918): SIOP:: AP = 270, PST = 270, CUR = 300
,E/SMD     (  280): DCD ON
,E/SMD     (  280): DCD ON
,D/BatteryService(  918): level:100, scale:100, status:5, health:2, present:true, voltage: 4383, temperature: 281, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  918): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  918): stay LED for fully charged
,D/BatteryService(  918): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1173): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1173): handleBatteryUpdate
,D/MotionRecognitionService(  918):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  918): Plugged
,I/MotionRecognitionService(  918): setPowerConnected  = true
,D/STATUSBAR-PhoneStatusBar( 1173):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3229): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3229): Disconnected process message: 10
,D/BatteryMeterView( 1173): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1173): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1173): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  280): DCD ON
,D/SSRM:m  (  918): SIOP:: AP = 270, PST = 270, CUR = 300
,E/Watchdog(  918): !@Sync 46
,E/SMD     (  280): DCD ON
,E/SMD     (  280): DCD ON
,D/BatteryService(  918): level:100, scale:100, status:5, health:2, present:true, voltage: 4382, temperature: 281, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  918): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  918): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  918):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  918): Plugged
,I/MotionRecognitionService(  918): setPowerConnected  = true
,D/BatteryService(  918): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1173): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1173): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1173):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1173): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1173): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1173): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3229): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3229): Disconnected process message: 10
,E/SMD     (  280): DCD ON
,I/PowerManagerService(  918): [PWL] Off : 1265s ago
,E/SMD     (  280): DCD ON
,D/SSRM:m  (  918): SIOP:: AP = 270, PST = 270, CUR = 300
,E/SMD     (  280): DCD ON
,E/SMD     (  280): DCD ON
,D/BatteryService(  918): level:100, scale:100, status:5, health:2, present:true, voltage: 4383, temperature: 281, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  918): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  918): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  918):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  918): Plugged
,I/MotionRecognitionService(  918): setPowerConnected  = true
,D/BatteryService(  918): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1173): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1173): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1173):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3229): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3229): Disconnected process message: 10
,D/BatteryMeterView( 1173): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1173): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1173): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  280): DCD ON
,D/SSRM:m  (  918): SIOP:: AP = 270, PST = 270, CUR = 300
,E/SMD     (  280): DCD ON
,E/SMD     (  280): DCD ON
,D/BatteryService(  918): level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 281, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  918): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  918): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  918):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  918): Plugged
,I/MotionRecognitionService(  918): setPowerConnected  = true
,D/BatteryService(  918): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1173): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1173): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1173):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3229): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3229): Disconnected process message: 10
,D/BatteryMeterView( 1173): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1173): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1173): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  280): DCD ON
,D/SSRM:m  (  918): SIOP:: AP = 270, PST = 270, CUR = 300
,E/Watchdog(  918): !@Sync 47
,E/SMD     (  280): DCD ON
,E/SMD     (  280): DCD ON
,E/SMD     (  280): DCD ON
,E/SMD     (  280): DCD ON
,D/SSRM:m  (  918): SIOP:: AP = 270, PST = 270, CUR = 300
,E/SMD     (  280): DCD ON
,E/SMD     (  280): DCD ON
,D/BatteryService(  918): level:100, scale:100, status:5, health:2, present:true, voltage: 4386, temperature: 281, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  918): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  918): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  918):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  918): Plugged
,I/MotionRecognitionService(  918): setPowerConnected  = true
,D/BatteryService(  918): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1173): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1173): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1173):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3229): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3229): Disconnected process message: 10
,D/BatteryMeterView( 1173): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1173): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1173): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  280): DCD ON
,D/SSRM:m  (  918): SIOP:: AP = 270, PST = 270, CUR = 300
,E/SMD     (  280): DCD ON
,E/SMD     (  280): DCD ON
,D/BatteryService(  918): level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 281, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  918): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  918): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  918):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  918): Plugged
,I/MotionRecognitionService(  918): setPowerConnected  = true
,D/BatteryService(  918): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1173): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1173): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1173):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3229): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3229): Disconnected process message: 10
,D/BatteryMeterView( 1173): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1173): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1173): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  280): DCD ON
,D/SSRM:m  (  918): SIOP:: AP = 270, PST = 270, CUR = 300
,E/Watchdog(  918): !@Sync 48
,E/SMD     (  280): DCD ON
,E/SMD     (  280): DCD ON
,D/BatteryService(  918): level:100, scale:100, status:5, health:2, present:true, voltage: 4383, temperature: 281, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  918): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  918): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  918):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  918): Plugged
,I/MotionRecognitionService(  918): setPowerConnected  = true
,D/BatteryService(  918): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1173): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1173): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1173):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3229): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3229): Disconnected process message: 10
,D/BatteryMeterView( 1173): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1173): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1173): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  280): DCD ON
,E/SMD     (  280): DCD ON
,D/SSRM:m  (  918): SIOP:: AP = 270, PST = 270, CUR = 300
,D/ConnectivityService(  918): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/SMD     (  280): DCD ON
,E/SMD     (  280): DCD ON
,D/BatteryService(  918): level:100, scale:100, status:5, health:2, present:true, voltage: 4382, temperature: 281, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  918): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  918): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  918):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  918): Plugged
,I/MotionRecognitionService(  918): setPowerConnected  = true
,D/BatteryService(  918): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1173): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1173): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1173):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3229): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3229): Disconnected process message: 10
,D/BatteryMeterView( 1173): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1173): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1173): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  280): DCD ON
,D/SSRM:m  (  918): SIOP:: AP = 270, PST = 270, CUR = 300
,E/SMD     (  280): DCD ON
,E/SMD     (  280): DCD ON
,D/BatteryService(  918): level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 281, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  918): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  918): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  918):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  918): Plugged
,D/BatteryService(  918): stay LED for fully charged
,I/MotionRecognitionService(  918): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1173): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1173): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1173):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3229): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3229): Disconnected process message: 10
,D/BatteryMeterView( 1173): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1173): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1173): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  280): DCD ON
,D/SSRM:m  (  918): SIOP:: AP = 270, PST = 270, CUR = 300
,E/Watchdog(  918): !@Sync 49
,E/SMD     (  280): DCD ON
,E/SMD     (  280): DCD ON
,E/SMD     (  280): DCD ON
,D/BatteryService(  918): level:100, scale:100, status:5, health:2, present:true, voltage: 4382, temperature: 281, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  918): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  918): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  918):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  918): Plugged
,I/MotionRecognitionService(  918): setPowerConnected  = true
,D/BatteryService(  918): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1173): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1173): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1173):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3229): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3229): Disconnected process message: 10
,D/BatteryMeterView( 1173): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1173): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1173): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  280): DCD ON
,D/SSRM:m  (  918): SIOP:: AP = 270, PST = 270, CUR = 300
,E/SMD     (  280): DCD ON
,E/SMD     (  280): DCD ON
,D/BatteryService(  918): level:100, scale:100, status:5, health:2, present:true, voltage: 4383, temperature: 281, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  918): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  918): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  918):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  918): Plugged
,I/MotionRecognitionService(  918): setPowerConnected  = true
,D/BatteryService(  918): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1173): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1173): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1173):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3229): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3229): Disconnected process message: 10
,D/BatteryMeterView( 1173): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1173): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1173): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  280): DCD ON
,D/SSRM:m  (  918): SIOP:: AP = 270, PST = 270, CUR = 300
,E/SMD     (  280): DCD ON
,E/SMD     (  280): DCD ON
,E/SMD     (  280): DCD ON
,D/TimaService(  918): TIMA: TimaService scheduler is intialized. 
,D/TimaService(  918): TIMA: checkEvent, operation: 50000 subject: 10000
,D/TimaService(  918): TimaServiceHandler.handleMessage what =1
,D/SSRM:m  (  918): SIOP:: AP = 270, PST = 270, CUR = 300
,E/Watchdog(  918): !@Sync 50
,E/SMD     (  280): DCD ON
,I/TLC_TIMA_PKM_measure_kernel(  918): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel(  918): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService(  918): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService(  918): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,E/SMD     (  280): DCD ON
,I/PowerManagerService(  918): [PWL] Off : 1380s ago
,E/SMD     (  280): DCD ON
,D/BatteryService(  918): level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 280, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  918): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  918): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  918):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  918): Plugged
,I/MotionRecognitionService(  918): setPowerConnected  = true
,D/BatteryService(  918): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1173): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1173): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1173):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3229): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3229): Disconnected process message: 10
,D/BatteryMeterView( 1173): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1173): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1173): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  280): DCD ON
,D/SSRM:m  (  918): SIOP:: AP = 270, PST = 270, CUR = 300
,E/SMD     (  280): DCD ON
,E/SMD     (  280): DCD ON
,E/SMD     (  280): DCD ON
,D/SSRM:m  (  918): SIOP:: AP = 270, PST = 270, CUR = 300
,E/SMD     (  280): DCD ON
,E/SMD     (  280): DCD ON
,E/SMD     (  280): DCD ON
,E/Watchdog(  918): !@Sync 51
,E/SMD     (  280): DCD ON
,D/SSRM:m  (  918): SIOP:: AP = 270, PST = 270, CUR = 300
,E/SMD     (  280): DCD ON
,E/SMD     (  280): DCD ON
,D/BatteryService(  918): level:100, scale:100, status:5, health:2, present:true, voltage: 4382, temperature: 280, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  918): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  918): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  918):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  918): Plugged
,I/MotionRecognitionService(  918): setPowerConnected  = true
,D/BatteryService(  918): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1173): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1173): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1173):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3229): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3229): Disconnected process message: 10
,D/BatteryMeterView( 1173): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1173): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1173): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  280): DCD ON
,D/SSRM:m  (  918): SIOP:: AP = 270, PST = 270, CUR = 300
,E/SMD     (  280): DCD ON
,E/SMD     (  280): DCD ON
,D/BatteryService(  918): level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 280, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  918): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  918): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  918):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  918): Plugged
,I/MotionRecognitionService(  918): setPowerConnected  = true
,D/BatteryService(  918): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1173): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1173): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1173):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3229): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3229): Disconnected process message: 10
,D/BatteryMeterView( 1173): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1173): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1173): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  280): DCD ON
,D/SSRM:m  (  918): SIOP:: AP = 270, PST = 270, CUR = 300
,E/SMD     (  280): DCD ON
,E/SMD     (  280): DCD ON
,D/BatteryService(  918): level:100, scale:100, status:5, health:2, present:true, voltage: 4382, temperature: 280, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  918): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  918): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  918):   mReceiver.onReceive : ACTION_BATTERY_CHANGED,
,I/MotionRecognitionService(  918): Plugged
,I/MotionRecognitionService(  918): setPowerConnected  = true
,D/BatteryService(  918): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1173): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1173): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1173):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3229): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3229): Disconnected process message: 10
,D/BatteryMeterView( 1173): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1173): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1173): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  280): DCD ON
,E/Watchdog(  918): !@Sync 52
,E/SMD     (  280): DCD ON
,D/SSRM:m  (  918): SIOP:: AP = 270, PST = 270, CUR = 300
,E/SMD     (  280): DCD ON
,E/SMD     (  280): DCD ON
,D/BatteryService(  918): level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 280, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  918): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  918): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  918):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  918): Plugged
,I/MotionRecognitionService(  918): setPowerConnected  = true
,D/BatteryService(  918): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1173): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1173): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1173):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3229): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3229): Disconnected process message: 10
,D/BatteryMeterView( 1173): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1173): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1173): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  280): DCD ON
,D/SSRM:m  (  918): SIOP:: AP = 270, PST = 270, CUR = 300
,E/SMD     (  280): DCD ON
,E/SMD     (  280): DCD ON
,E/SMD     (  280): DCD ON
,D/SSRM:m  (  918): SIOP:: AP = 270, PST = 270, CUR = 300
,E/SMD     (  280): DCD ON
,E/SMD     (  280): DCD ON
,E/SMD     (  280): DCD ON
,E/Watchdog(  918): !@Sync 53
,E/SMD     (  280): DCD ON
,D/SSRM:m  (  918): SIOP:: AP = 270, PST = 270, CUR = 300
,E/SMD     (  280): DCD ON
,E/SMD     (  280): DCD ON
,D/BatteryService(  918): level:100, scale:100, status:5, health:2, present:true, voltage: 4383, temperature: 280, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  918): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  918): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  918):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  918): Plugged
,I/MotionRecognitionService(  918): setPowerConnected  = true
,D/BatteryService(  918): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1173): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1173): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1173):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3229): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3229): Disconnected process message: 10
,D/BatteryMeterView( 1173): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1173): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1173): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  280): DCD ON
,D/SSRM:m  (  918): SIOP:: AP = 270, PST = 270, CUR = 300
,E/SMD     (  280): DCD ON
,E/SMD     (  280): DCD ON
,D/BatteryService(  918): level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 280, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  918): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  918): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  918):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  918): Plugged
,I/MotionRecognitionService(  918): setPowerConnected  = true
,D/BatteryService(  918): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1173): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1173): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1173):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3229): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3229): Disconnected process message: 10
,D/BatteryMeterView( 1173): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1173): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1173): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  280): DCD ON
,D/SSRM:m  (  918): SIOP:: AP = 270, PST = 270, CUR = 300
,E/SMD     (  280): DCD ON
,E/SMD     (  280): DCD ON
,E/SMD     (  280): DCD ON
,D/BatteryService(  918): level:100, scale:100, status:5, health:2, present:true, voltage: 4386, temperature: 280, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  918): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  918): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  918):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  918): Plugged
,D/BatteryService(  918): stay LED for fully charged
,I/MotionRecognitionService(  918): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1173): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1173): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1173):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3229): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3229): Disconnected process message: 10
,D/BatteryMeterView( 1173): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1173): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1173): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog(  918): !@Sync 54
,E/SMD     (  280): DCD ON
,D/SSRM:m  (  918): SIOP:: AP = 270, PST = 270, CUR = 300
,E/SMD     (  280): DCD ON
,I/PowerManagerService(  918): [PWL] Off : 1500s ago
,E/SMD     (  280): DCD ON
,D/BatteryService(  918): level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 280, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  918): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  918): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  918):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  918): Plugged
,I/MotionRecognitionService(  918): setPowerConnected  = true
,D/BatteryService(  918): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1173): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1173): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1173):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3229): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3229): Disconnected process message: 10
,D/BatteryMeterView( 1173): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1173): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1173): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  280): DCD ON
,D/SSRM:m  (  918): SIOP:: AP = 270, PST = 270, CUR = 300
,E/SMD     (  280): DCD ON
,E/SMD     (  280): DCD ON
,E/SMD     (  280): DCD ON
,D/SSRM:m  (  918): SIOP:: AP = 270, PST = 270, CUR = 300
,E/SMD     (  280): DCD ON
,E/SMD     (  280): DCD ON
,E/SMD     (  280): DCD ON
,E/Watchdog(  918): !@Sync 55
,E/SMD     (  280): DCD ON
,D/SSRM:m  (  918): SIOP:: AP = 270, PST = 270, CUR = 300
,E/SMD     (  280): DCD ON
,E/SMD     (  280): DCD ON
,D/BatteryService(  918): level:100, scale:100, status:5, health:2, present:true, voltage: 4383, temperature: 280, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  918): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  918): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  918):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  918): Plugged
,I/MotionRecognitionService(  918): setPowerConnected  = true
,D/BatteryService(  918): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1173): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1173): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1173):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3229): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3229): Disconnected process message: 10
,D/BatteryMeterView( 1173): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1173): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1173): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  280): DCD ON
,D/SSRM:m  (  918): SIOP:: AP = 270, PST = 270, CUR = 300
,E/SMD     (  280): DCD ON
,E/SMD     (  280): DCD ON
,D/BatteryService(  918): level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 280, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  918): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  918): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  918):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  918): Plugged
,I/MotionRecognitionService(  918): setPowerConnected  = true
,D/BatteryService(  918): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1173): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1173): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1173):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3229): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3229): Disconnected process message: 10
,D/BatteryMeterView( 1173): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1173): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1173): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  280): DCD ON
,D/SSRM:m  (  918): SIOP:: AP = 270, PST = 270, CUR = 300
,E/SMD     (  280): DCD ON
,E/SMD     (  280): DCD ON
,E/SMD     (  280): DCD ON
,D/BatteryService(  918): level:100, scale:100, status:5, health:2, present:true, voltage: 4383, temperature: 280, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  918): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  918): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  918):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  918): Plugged
,I/MotionRecognitionService(  918): setPowerConnected  = true
,D/BatteryService(  918): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1173): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1173): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1173):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3229): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3229): Disconnected process message: 10
,D/BatteryMeterView( 1173): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1173): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1173): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog(  918): !@Sync 56
,E/SMD     (  280): DCD ON
,D/SSRM:m  (  918): SIOP:: AP = 270, PST = 270, CUR = 300
,E/SMD     (  280): DCD ON
,E/SMD     (  280): DCD ON
,D/BatteryService(  918): level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 280, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  918): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  918): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  918):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  918): Plugged
,D/BatteryService(  918): stay LED for fully charged
,I/MotionRecognitionService(  918): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1173): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1173): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1173):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3229): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/BatteryMeterView( 1173): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/HeadsetStateMachine( 3229): Disconnected process message: 10
,D/BatteryMeterView( 1173): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1173): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  280): DCD ON
,D/SSRM:m  (  918): SIOP:: AP = 270, PST = 270, CUR = 300
,E/SMD     (  280): DCD ON
,E/SMD     (  280): DCD ON
,E/SMD     (  280): DCD ON
,D/SSRM:m  (  918): SIOP:: AP = 270, PST = 270, CUR = 300
,E/SMD     (  280): DCD ON
,E/SMD     (  280): DCD ON
,E/SMD     (  280): DCD ON
,E/Watchdog(  918): !@Sync 57
,E/SMD     (  280): DCD ON
,D/SSRM:m  (  918): SIOP:: AP = 270, PST = 270, CUR = 300
,E/SMD     (  280): DCD ON
,E/SMD     (  280): DCD ON
,E/SMD     (  280): DCD ON
,D/SSRM:m  (  918): SIOP:: AP = 270, PST = 270, CUR = 300
,E/SMD     (  280): DCD ON
,E/SMD     (  280): DCD ON
,E/SMD     (  280): DCD ON
,D/BatteryService(  918): level:100, scale:100, status:5, health:2, present:true, voltage: 4383, temperature: 280, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  918): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  918): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  918):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  918): Plugged
,I/MotionRecognitionService(  918): setPowerConnected  = true
,D/BatteryService(  918): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1173): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1173): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1173):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3229): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3229): Disconnected process message: 10
,D/BatteryMeterView( 1173): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1173): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1173): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:m  (  918): SIOP:: AP = 270, PST = 270, CUR = 300
,E/SMD     (  280): DCD ON
,E/SMD     (  280): DCD ON
,E/SMD     (  280): DCD ON
,D/BatteryService(  918): level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 280, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  918): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  918): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  918):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  918): Plugged
,I/MotionRecognitionService(  918): setPowerConnected  = true
,D/BatteryService(  918): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1173): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1173): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1173):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3229): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3229): Disconnected process message: 10
,D/BatteryMeterView( 1173): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1173): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1173): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog(  918): !@Sync 58
,E/SMD     (  280): DCD ON
,D/SSRM:m  (  918): SIOP:: AP = 270, PST = 270, CUR = 300
,E/SMD     (  280): DCD ON
,E/SMD     (  280): DCD ON
,D/BatteryService(  918): level:100, scale:100, status:5, health:2, present:true, voltage: 4383, temperature: 279, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  918): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  918): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  918):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  918): Plugged
,I/MotionRecognitionService(  918): setPowerConnected  = true
,D/BatteryService(  918): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1173): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1173): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1173):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3229): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3229): Disconnected process message: 10
,D/BatteryMeterView( 1173): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1173): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1173): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/PowerManagerService(  918): [PWL] Off : 1625s ago
,E/SMD     (  280): DCD ON
,D/ConnectivityService(  918): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SSRM:m  (  918): SIOP:: AP = 270, PST = 270, CUR = 300
,E/SMD     (  280): DCD ON
,E/SMD     (  280): DCD ON
,E/SMD     (  280): DCD ON
,D/BatteryService(  918): level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 279, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  918): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  918): stay LED for fully charged
,D/BatteryService(  918): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1173): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1173): handleBatteryUpdate
,D/MotionRecognitionService(  918):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  918): Plugged
,I/MotionRecognitionService(  918): setPowerConnected  = true
,D/STATUSBAR-PhoneStatusBar( 1173):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3229): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3229): Disconnected process message: 10
,D/BatteryMeterView( 1173): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1173): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1173): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  280): DCD ON
,D/SSRM:m  (  918): SIOP:: AP = 270, PST = 270, CUR = 300
,E/SMD     (  280): DCD ON
,E/SMD     (  280): DCD ON
,E/Watchdog(  918): !@Sync 59
,E/SMD     (  280): DCD ON
,D/SSRM:m  (  918): SIOP:: AP = 270, PST = 270, CUR = 300
,E/SMD     (  280): DCD ON
,E/SMD     (  280): DCD ON
,D/BatteryService(  918): level:100, scale:100, status:5, health:2, present:true, voltage: 4383, temperature: 279, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  918): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  918): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  918):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  918): Plugged
,I/MotionRecognitionService(  918): setPowerConnected  = true
,D/BatteryService(  918): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1173): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1173): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1173):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3229): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3229): Disconnected process message: 10
,D/BatteryMeterView( 1173): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1173): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1173): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  280): DCD ON
,D/SSRM:m  (  918): SIOP:: AP = 270, PST = 270, CUR = 300
,E/SMD     (  280): DCD ON
,E/SMD     (  280): DCD ON
,D/NetworkStatsFactory(  918): UpdateStatsForKnox
,E/SMD     (  280): DCD ON
,D/BatteryService(  918): level:100, scale:100, status:5, health:2, present:true, voltage: 4382, temperature: 279, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  918): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  918): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  918):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  918): Plugged
,D/BatteryService(  918): stay LED for fully charged
,I/MotionRecognitionService(  918): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1173): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1173): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1173):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3229): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3229): Disconnected process message: 10
,D/BatteryMeterView( 1173): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1173): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1173): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  280): DCD ON
,D/SSRM:m  (  918): SIOP:: AP = 270, PST = 270, CUR = 300
,E/SMD     (  280): DCD ON
,E/SMD     (  280): DCD ON
,D/TimaService(  918): TIMA: TimaService scheduler is intialized. 
,D/TimaService(  918): TIMA: checkEvent, operation: 50000 subject: 10000
,D/TimaService(  918): TimaServiceHandler.handleMessage what =1
,D/BatteryService(  918): level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 279, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  918): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  918): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  918):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  918): Plugged
I/MotionRecognitionService(  918): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1173): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1173): handleBatteryUpdate
,D/BatteryService(  918): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1173):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3229): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3229): Disconnected process message: 10
,D/BatteryMeterView( 1173): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1173): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1173): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog(  918): !@Sync 60
,E/SMD     (  280): DCD ON
,I/TLC_TIMA_PKM_measure_kernel(  918): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel(  918): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService(  918): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService(  918): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/SSRM:m  (  918): SIOP:: AP = 270, PST = 270, CUR = 300
,E/SMD     (  280): DCD ON
,E/SMD     (  280): DCD ON
,E/SMD     (  280): DCD ON
,D/SSRM:m  (  918): SIOP:: AP = 270, PST = 270, CUR = 300
,E/SMD     (  280): DCD ON
,E/SMD     (  280): DCD ON
,E/SMD     (  280): DCD ON
,D/BatteryService(  918): level:100, scale:100, status:5, health:2, present:true, voltage: 4382, temperature: 279, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  918): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  918): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  918):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  918): Plugged
,I/MotionRecognitionService(  918): setPowerConnected  = true
,D/BatteryService(  918): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1173): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1173): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1173):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3229): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3229): Disconnected process message: 10
,D/BatteryMeterView( 1173): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1173): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1173): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  280): DCD ON
,D/SSRM:m  (  918): SIOP:: AP = 270, PST = 270, CUR = 300
,E/SMD     (  280): DCD ON
,E/SMD     (  280): DCD ON
,D/BatteryService(  918): level:100, scale:100, status:5, health:2, present:true, voltage: 4383, temperature: 279, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  918): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  918): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  918):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  918): Plugged
,I/MotionRecognitionService(  918): setPowerConnected  = true
,D/BatteryService(  918): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1173): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1173): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1173):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3229): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3229): Disconnected process message: 10
,D/BatteryMeterView( 1173): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1173): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1173): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog(  918): !@Sync 61
,E/SMD     (  280): DCD ON
,D/SSRM:m  (  918): SIOP:: AP = 270, PST = 270, CUR = 300
,E/SMD     (  280): DCD ON
,E/SMD     (  280): DCD ON
,D/BatteryService(  918): level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 279, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  918): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  918): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  918):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  918): Plugged
,I/MotionRecognitionService(  918): setPowerConnected  = true
,E/SMD     (  280): DCD ON
,D/BatteryService(  918): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1173): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1173): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1173):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3229): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3229): Disconnected process message: 10
,D/BatteryMeterView( 1173): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1173): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1173): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:m  (  918): SIOP:: AP = 270, PST = 270, CUR = 300
,E/SMD     (  280): DCD ON
,E/SMD     (  280): DCD ON
,E/SMD     (  280): DCD ON
,D/ConnectivityService(  918): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/SMD     (  280): DCD ON
,D/SSRM:m  (  918): SIOP:: AP = 270, PST = 270, CUR = 300
,E/SMD     (  280): DCD ON
,E/SMD     (  280): DCD ON
,E/Watchdog(  918): !@Sync 62
,E/SMD     (  280): DCD ON
,D/SSRM:m  (  918): SIOP:: AP = 270, PST = 270, CUR = 300
,E/SMD     (  280): DCD ON
,E/SMD     (  280): DCD ON
,E/SMD     (  280): DCD ON
,D/BatteryService(  918): level:100, scale:100, status:5, health:2, present:true, voltage: 4383, temperature: 279, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  918): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  918): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  918):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  918): Plugged
,I/MotionRecognitionService(  918): setPowerConnected  = true
,D/BatteryService(  918): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1173): received broadcast android.intent.action.BATTERY_CHANGED,
D/KeyguardUpdateMonitor( 1173): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1173):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3229): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3229): Disconnected process message: 10
,D/BatteryMeterView( 1173): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1173): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1173): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:m  (  918): SIOP:: AP = 270, PST = 270, CUR = 300
,E/SMD     (  280): DCD ON
,E/SMD     (  280): DCD ON
,E/SMD     (  280): DCD ON
,I/PowerManagerService(  918): [PWL] Off : 1755s ago
,E/SMD     (  280): DCD ON
,D/SSRM:m  (  918): SIOP:: AP = 260, PST = 269, CUR = 300
,E/SMD     (  280): DCD ON
,E/SMD     (  280): DCD ON
,E/Watchdog(  918): !@Sync 63
,E/SMD     (  280): DCD ON
,V/AlarmManager(  918): waitForAlarm result :4
,D/KeyguardUpdateMonitor( 1173): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1173): handleTimeUpdate
,D/KeyguardEffectViewController( 1173): onReceive action : android.intent.action.TIME_TICK
,I/KeyguardEffectViewController( 1173): *** don't update sliding image ***
,I/ActivityManager(  918): Killing 7477:com.samsung.android.securitylogagent/1000 (adj 15): empty for 1802s
,I/ActivityManager(  918): Killing 7866:com.android.email/u0a163 (adj 15): empty for 1802s
,I/ActivityManager(  918): Killing 7833:com.samsung.android.sconnect/u0a138 (adj 15): empty for 1802s
,I/ActivityManager(  918): Killing 7753:com.google.android.apps.magazines/u0a128 (adj 15): empty for 1802s
,I/ActivityManager(  918): Killing 7734:com.android.chrome/u0a88 (adj 15): empty for 1802s
,I/ActivityManager(  918): Killing 6555:com.sec.chaton/u0a86 (adj 15): empty for 1802s
,I/ActivityManager(  918): Killing 7719:com.sec.knox.bridge/1000 (adj 15): empty for 1802s
,I/ActivityManager(  918): Killing 7264:com.sec.android.widgetapp.ap.hero.accuweather/u0a71 (adj 15): empty for 1802s
,I/ActivityManager(  918): Killing 7698:com.osp.app.signin/u0a45 (adj 15): empty for 1802s
,I/ActivityManager(  918): Killing 7661:com.policydm/1000 (adj 15): empty for 1802s
,D/BatteryService(  918): level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 279, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  918): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
D/BatteryService(  918): stay LED for fully charged
,I/ActivityManager(  918): Killing 7646:com.sec.android.soagent/u0a37 (adj 15): empty for 1802s
,I/ActivityManager(  918): Killing 7629:com.samsung.klmsagent/u0a19 (adj 15): empty for 1802s
I/ActivityManager(  918): Killing 7605:com.sec.android.fotaclient/u0a11 (adj 15): empty for 1802s
,I/ActivityManager(  918): Killing 7587:com.sec.android.diagmonagent/1000 (adj 15): empty for 1802s
,I/ActivityManager(  918): Killing 7556:com.sec.android.cloudagent/u0a2 (adj 15): empty for 1802s
,I/ActivityManager(  918): Killing 6728:com.sec.pcw.device/1000 (adj 15): empty for 1802s
,I/ActivityManager(  918): Killing 7888:com.sec.android.provider.badge/u0a78 (adj 15): empty for 1802s
,I/ActivityManager(  918): Killing 7183:com.sec.android.widgetapp.activeapplicationwidget/u0a158 (adj 15): empty for 1810s
,I/ActivityManager(  918): Killing 7316:com.sec.android.app.camera/u0a154 (adj 15): empty for 1828s
,I/ActivityManager(  918): Killing 7298:com.sec.android.GeoLookout/u0a113 (adj 15): empty for 1828s
,I/ActivityManager(  918): Killing 7279:com.sec.android.widgetapp.dualclockdigital/u0a103 (adj 15): empty for 1828s
,I/ActivityManager(  918): Killing 7249:com.sec.android.widgetapp.digitalclock/u0a94 (adj 15): empty for 1828s
,I/ActivityManager(  918): Killing 5644:com.android.mms/u0a50 (adj 15): empty for 1828s
I/ActivityManager(  918): Killing 5960:com.sec.android.gallery3d/u0a48 (adj 15): empty for 1828s
,I/ActivityManager(  918): Killing 5057:com.android.defcontainer/u0a5 (adj 15): empty for 1837s
,I/ActivityManager(  918): Killing 6660:com.google.android.gms:car/u0a12 (adj 15): empty for 1844s
,I/ActivityManager(  918): Killing 7072:com.samsung.android.provider.shootingmodeprovider/u0a170 (adj 15): empty for 1844s
,I/ActivityManager(  918): Killing 7056:com.sec.kidsplat.installer/u0a166 (adj 15): empty for 1844s
,I/ActivityManager(  918): Killing 7020:com.samsung.helphub/1000 (adj 15): empty for 1844s
,D/LightsService(  918): [api] onReceive : SvcLEDReceiver re-enables LightSenor and sends MSG_FORCEDSVCLEDTASK
,E/LightSensor(  918): Light old sensor_state 8192, new sensor_state : 8704 en : 1
,I/ProcessStatsService(  918): Prepared write state in 13ms
,D/SensorManager(  918): registerListener :: 6, TMG399X RGB Sensor, 200000, 0,  
,I/ProcessStatsService(  918): Prepared write state in 8ms
,D/BatteryService(  918): Sending ACTION_BATTERY_CHANGED.
,V/HeadsetService( 3229): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3229): Disconnected process message: 10
,V/NetworkStats(  918): performPollLocked(flags=0x3)
,D/NtpTrustedTime(  918): currentTimeMillis() cache hit
,D/NetworkStatsFactory(  918): UpdateStatsForKnox
D/ConnectivityService(  918): returning getNetworkInfo(networkType - 28) :[type: MOBILE_ENT1[] - MOBILE_ENT1, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/KeyguardUpdateMonitor( 1173): received broadcast android.intent.action.BATTERY_CHANGED
,V/NetworkStats(  918): performPollLocked() took 7ms
,D/STATUSBAR-PhoneStatusBar( 1173):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
D/NtpTrustedTime(  918): currentTimeMillis() cache hit
,D/BatteryMeterView( 1173): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1173): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1173): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/KeyguardUpdateMonitor( 1173): handleBatteryUpdate
,D/MotionRecognitionService(  918):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  918): Plugged
I/MotionRecognitionService(  918): setPowerConnected  = true
D/NtpTrustedTime(  918): currentTimeMillis() cache hit
D/NtpTrustedTime(  918): currentTimeMillis() cache hit
,D/SSRM:m  (  918): SIOP:: AP = 260, PST = 268, CUR = 300
,D/ConnectivityService(  918): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/DateView( 1173): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1173): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,I/GLSUser ( 1739): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: oauth2: email
I/GLSUser ( 1739): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2: email without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1739): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1739): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1739): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ConnectivityService(  918): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/CountryDetector(  918): No listener is left
,E/LightSensor(  918): RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=0, bp1=0, cp1=0, cpl=3202560
,D/LightsService(  918): [SvcLED]  onSensorChanged::light value = 0
E/LightSensor(  918): Light old sensor_state 8704, new sensor_state : 8192 en : 0
,D/SensorManager(  918): unregisterListener ::   
D/LightsService(  918): [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=4) maintains its priority right
,TIME-OUT KILL (timeout was 1800000ms),D/GCM     ( 1739): Message class com.google.f.a.a.i
D/ConnectivityService(  918): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/ConnectivityService(  918): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/ProcessStatsService(  918): Pruning old procstats: /data/system/procstats/state-2015-12-20-04-11-08.bin
D/AndroidRuntime( 8555): 
D/AndroidRuntime( 8555): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 8555): CheckJNI is OFF
D/AndroidRuntime( 8555): setted country_code = Germany
D/AndroidRuntime( 8555): setted countryiso_code = DE
D/AndroidRuntime( 8555): setted sales_code = DBT
D/AndroidRuntime( 8555): readGMSProperty: start
D/AndroidRuntime( 8555): readGMSProperty: already setted!!
D/AndroidRuntime( 8555): readGMSProperty: end
D/AndroidRuntime( 8555): addProductProperty: start
E/SQLiteLog( 1739): (10) POSIX Error : 11 SQLite Error : 3850
W/libprocessgroup(  918): failed to open /acct/uid_10170/pid_7072/cgroup.procs: No such file or directory
W/libprocessgroup(  918): failed to open /acct/uid_10048/pid_5960/cgroup.procs: No such file or directory
W/libprocessgroup(  918): failed to open /acct/uid_1000/pid_6728/cgroup.procs: No such file or directory
W/libprocessgroup(  918): failed to open /acct/uid_1000/pid_7020/cgroup.procs: No such file or directory
W/libprocessgroup(  918): failed to open /acct/uid_1000/pid_7477/cgroup.procs: No such file or directory
W/libprocessgroup(  918): failed to open /acct/uid_10011/pid_7605/cgroup.procs: No such file or directory
W/libprocessgroup(  918): failed to open /acct/uid_10078/pid_7888/cgroup.procs: No such file or directory
W/libprocessgroup(  918): failed to open /acct/uid_1000/pid_7587/cgroup.procs: No such file or directory
W/libprocessgroup(  918): failed to open /acct/uid_10086/pid_6555/cgroup.procs: No such file or directory
W/libprocessgroup(  918): failed to open /acct/uid_10163/pid_7866/cgroup.procs: No such file or directory
W/libprocessgroup(  918): failed to open /acct/uid_10138/pid_7833/cgroup.procs: No such file or directory
W/libprocessgroup(  918): failed to open /acct/uid_10088/pid_7734/cgroup.procs: No such file or directory
W/libprocessgroup(  918): failed to open /acct/uid_10002/pid_7556/cgroup.procs: No such file or directory
W/libprocessgroup(  918): failed to open /acct/uid_10045/pid_7698/cgroup.procs: No such file or directory
W/libprocessgroup(  918): failed to open /acct/uid_10012/pid_6660/cgroup.procs: No such file or directory
W/libprocessgroup(  918): failed to open /acct/uid_10166/pid_7056/cgroup.procs: No such file or directory
W/libprocessgroup(  918): failed to open /acct/uid_10103/pid_7279/cgroup.procs: No such file or directory
W/libprocessgroup(  918): failed to open /acct/uid_10154/pid_7316/cgroup.procs: No such file or directory
W/libprocessgroup(  918): failed to open /acct/uid_10113/pid_7298/cgroup.procs: No such file or directory
W/libprocessgroup(  918): failed to open /acct/uid_10094/pid_7249/cgroup.procs: No such file or directory
W/libprocessgroup(  918): failed to open /acct/uid_10158/pid_7183/cgroup.procs: No such file or directory
W/libprocessgroup(  918): failed to open /acct/uid_10005/pid_5057/cgroup.procs: No such file or directory
W/libprocessgroup(  918): failed to open /acct/uid_10019/pid_7629/cgroup.procs: No such file or directory
W/libprocessgroup(  918): failed to open /acct/uid_10037/pid_7646/cgroup.procs: No such file or directory
W/libprocessgroup(  918): failed to open /acct/uid_1000/pid_7719/cgroup.procs: No such file or directory
W/libprocessgroup(  918): failed to open /acct/uid_1000/pid_7661/cgroup.procs: No such file or directory
W/libprocessgroup(  918): failed to open /acct/uid_10071/pid_7264/cgroup.procs: No such file or directory
W/libprocessgroup(  918): failed to open /acct/uid_10050/pid_5644/cgroup.procs: No such file or directory
W/libprocessgroup(  918): failed to open /acct/uid_10128/pid_7753/cgroup.procs: No such file or directory
E/AffinityControl( 8555): AffinityControl: registerfunction enter
D/AndroidRuntime( 8555): Calling main entry com.android.commands.pm.Pm
D/PackageManager(  918): START PACKAGE DELETE: observer{657007618}
D/PackageManager(  918): pkg{<packageName>}
D/PackageManager(  918): user{0}
D/PackageManager(  918): caller{2000}
D/PackageManager(  918): flags{3}
D/PersonaManagerService(  918): isFromApprovedUnInstaller: uid, userId, appid : 2000 0 2000
D/PersonaManagerService(  918): isFromApprovedUnInstaller: isApproved : true
D/PersonaManagerService(  918): isFromApprovedUnInstaller: isApproved before exit: true
D/PackageManager(  918): deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag3
D/PackageManager(  918): deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag3
D/PackageManager(  918): [MSG] DELETE_PACKAGE_AS_USER
D/PackageManagerService(  918): deletePackage- pkg:com.test.thalitest, edmuserId:0
D/PackageManagerService(  918): deletePackage- pkg:com.test.thalitest, edmuserId:-1
D/ApplicationPolicy(  918): getApplicationUninstallationEnabled
D/ApplicationPolicy(  918): getApplicationUninstallationEnabled :  enabled true
D/PackageManager(  918): !@killApplicatoin: 10367, uninstall pkg
I/ActivityManager(  918): Force stopping com.test.thalitest appid=10367 user=-1: uninstall pkg
I/ActivityManager(  918): Killing 7416:com.test.thalitest/u0a367 (adj 0): stop com.test.thalitest
I/ActivityManager(  918):   Force finishing activity ActivityRecord{28af92b5 u0 com.test.thalitest/.MainActivity t11}
D/FocusedStackFrame(  918): Set to : 0
D/LockPatternUtilsCache( 1173): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1173): value : false
D/LockPatternUtilsCache( 1173): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1173): value : false
D/LockPatternUtilsCache( 1173): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1173): value : false
I/SurfaceFlinger(  249): id=15 Removed com.test.thalitest/com.test.thalitest.MainActivity (5/8)
I/SurfaceFlinger(  249): id=15 Removed com.test.thalitest/com.test.thalitest.MainActivity (-2/8)
D/LockPatternUtilsCache( 1173): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1173): value : false
D/LockPatternUtilsCache( 1173): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1173): value : false
D/WifiService(  918): Client connection lost with reason: 4
W/PackageSettings(  918): Skipping PackageSetting{226db08f com.example.hello/10375} due to missing metadata
D/ConnectivityService(  918): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/ActivityManager(  918): Force stopping com.test.thalitest appid=10367 user=0: pkg removed
I/art     ( 4547): Explicit concurrent mark sweep GC freed 4026(225KB) AllocSpace objects, 1(16KB) LOS objects, 40% free, 14MB/24MB, paused 334us total 28.679ms
I/art     ( 1587): Explicit concurrent mark sweep GC freed 10422(697KB) AllocSpace objects, 1(39KB) LOS objects, 39% free, 16MB/27MB, paused 414us total 24.574ms
D/ResourcesManager(  918): creating new AssetManager and set to /system/priv-app/InputDevices/InputDevices.apk
D/ResourcesManager( 1490): creating new AssetManager and set to /system/app/AccuweatherPhone2014_K_LMR_fHD/AccuweatherPhone2014_K_LMR_fHD.apk
W/ResourcesManager( 1490): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 1490): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 1490): Asset path '/system/framework/sws.jar' does not exist or contains no resources.
D/ResourcesManager(  918): creating new AssetManager and set to /system/priv-app/Velvet/Velvet.apk
W/GeofencerStateMachine( 2108): Ignoring removeGeofence because network location is disabled.
I/InputReader(  918): Reconfiguring input devices.  changes=0x00000010
E/ActivityManager(  918): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  918): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  918): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  918): checkUser: useridlist=null, currentuser=0
E/Zygote  ( 8572): MountEmulatedStorage()
E/Zygote  ( 8572): v2
I/libpersona( 8572): KNOX_SDCARD checking this for 10019
I/libpersona( 8572): KNOX_SDCARD not a persona
I/ActivityManager(  918): Start proc com.samsung.klmsagent for broadcast com.samsung.klmsagent/.listner.MainReciver: pid=8572 uid=10019 gids={50019, 9997, 3003} abi=armeabi-v7a
E/SamsungIME( 1861): mOCRHelper is null
D/ResourcesManager(  918): creating new AssetManager and set to /system/app/SamsungIME/SamsungIME.apk
I/SELinux ( 8572): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
I/SELinux ( 8572): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
D/ResourcesManager( 1490): creating new AssetManager and set to /system/app/SPlannerWidget_OS_UPG/SPlannerWidget_OS_UPG.apk
E/SELinux ( 8572): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
W/ResourcesManager( 1490): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 1490): Asset path '/system/framework/sws.jar' does not exist or contains no resources.
D/TimaKeyStoreProvider( 8572): TimaSignature is unavailable
D/ActivityThread( 8572): Added TimaKeyStore provider
D/LockPatternUtilsCache( 1173): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1173): value : false
D/LockPatternUtilsCache( 1173): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1173): value : false
D/SurfaceWidgetView( 1490): destroyHardwareResources():485063349
V/WindowOrientationListener(  918): mSContextAutoRotationListener.getProposedRotation, mbResultFaceDectection: false
V/WindowOrientationListener(  918): mSContextAutoRotationListener.getProposedRotation, Rotation: -1
V/WindowManager(  918): rotationForOrientationLw(orient=1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false
V/WindowOrientationListener(  918): mSContextAutoRotationListener.getProposedRotation, mbResultFaceDectection: false
V/WindowOrientationListener(  918): mSContextAutoRotationListener.getProposedRotation, Rotation: -1
D/LockPatternUtilsCache( 1173): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1173): value : false
D/Launcher( 1490): onRestart, Launcher: 782354133
D/Launcher( 1490): onStart, Launcher: 782354133
D/Launcher.HomeView( 1490): onStart
D/SurfaceWidgetClient$ISurfaceWidgetStub( 1970): [237392/6] Surface widget visibility changed visibility = true on instance = 1
D/SurfaceWidget.Renderer( 1970): [237392/6] SurfaceWidget drawing first frame
D/LockPatternUtilsCache( 1173): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1173): value : false
I/SurfaceFlinger(  249): id=18 createSurf (1080x1920),1 flag=4, com.sec.android.app.launcher/com.android.launcher2.Launcher
D/StatusBarManagerService(  918): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
D/LockPatternUtilsCache( 1173): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1173): value : false
D/LockPatternUtilsCache( 1173): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1173): value : false
D/StatusBarManagerService(  918): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
D/LockPatternUtilsCache( 1173): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1173): value : false
D/LockPatternUtilsCache( 1173): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1173): value : false
D/ResourcesManager( 8572): creating new AssetManager and set to /system/priv-app/KLMSAgent/KLMSAgent.apk
I/KLMS-2.4.503: ( 8572): KLMSSystemProperties(): getBoolean(): ro.product_ship = true
I/art     (  918): Explicit concurrent mark sweep GC freed 55971(5MB) AllocSpace objects, 202(3MB) LOS objects, 30% free, 36MB/52MB, paused 7.095ms total 238.423ms
D/ResourcesManager(  918): creating new AssetManager and set to /data/app/com.google.android.gms-1/base.apk
I/art     (  918): WaitForGcToComplete blocked for 151.257ms for cause Explicit
I/KLMS-2.4.503: ( 8572): MainReciver(): EventNotificationReciver- method called: AppActivityListner onReceive for Intent Action : android.intent.action.PACKAGE_REMOVED , timestamp: 1450659769042
D/LockPatternUtilsCache( 1173): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1173): value : false
I/KLMS-2.4.503: ( 8572): MainReciver(): PACKAGE_REMOVED
D/SecContentProvider2(  918): uri = 11 selection = getMyKnoxAdmin
D/SecContentProvider2(  918): mCursor = null
D/ResourcesManager(  918): creating new AssetManager and set to /system/priv-app/SNS/SNS.apk
I/KLMS-2.4.503: ( 8572): MainReciver(): REPLACING: false | pkgName: com.test.thalitest
E/SMD     (  280): DCD ON
D/ResourcesManager(  918): creating new AssetManager and set to /system/priv-app/Samsungservice2_xxhdpi/Samsungservice2_xxhdpi.apk
D/ResourcesManager(  918): creating new AssetManager and set to /system/priv-app/Velvet/Velvet.apk
D/ResourcesManager(  918): creating new AssetManager and set to /system/app/ChatON_MARKET/ChatON_MARKET.apk
D/ResourcesManager(  918): creating new AssetManager and set to /system/app/Dropbox/Dropbox.apk
D/RegisteredServicesCache( 1470): empty dynamic service
D/InputMethodManagerService(  918): windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
D/ResourcesManager(  918): creating new AssetManager and set to /system/app/talkback/talkback.apk
W/ContextImpl(  918): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.android.server.InputMethodManagerService$6.run:2728 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
W/InputMethodManagerService(  918): Got RemoteException sending setActive(false) notification to pid 7416 uid 10367
D/ResourcesManager(  918): creating new AssetManager and set to /system/app/Gmail2/Gmail2.apk
D/EnterpriseDeviceManagerService(  918): Package has changed for user 0
D/EnterpriseDeviceManagerService(  918): Admin package name: com.google.android.gms
D/ResourcesManager(  918): creating new AssetManager and set to /system/priv-app/SecContacts/SecContacts.apk
D/ResourcesManager(  918): creating new AssetManager and set to /system/app/SBrowser/SBrowser.apk
E/ActivityManager(  918): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  918): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  918): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  918): checkUser: useridlist=null, currentuser=0
D/ResourcesManager(  918): creating new AssetManager and set to /system/app/SecEmail_K/SecEmail_K.apk
W/Resources(  918): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager(  918): creating new AssetManager and set to /system/priv-app/SecMms_Candy/SecMms_Candy.apk
E/Zygote  ( 8604): MountEmulatedStorage()
E/Zygote  ( 8604): v2
I/libpersona( 8604): KNOX_SDCARD checking this for 10104
I/libpersona( 8604): KNOX_SDCARD not a persona
D/ResourcesManager(  918): creating new AssetManager and set to /system/priv-app/GoogleServicesFramework/GoogleServicesFramework.apk
I/ActivityManager(  918): Start proc com.sec.esdk.elm for broadcast com.sec.esdk.elm/.receiver.MainReceiver: pid=8604 uid=10104 gids={50104, 9997, 3003} abi=armeabi-v7a
I/ActivityManager(  918): Killing 7910:com.samsung.android.service.travel/u0a178 (adj 15): empty for 1803s
I/SELinux ( 8604): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
D/ResourcesManager(  918): creating new AssetManager and set to /system/priv-app/SHealth3_5/SHealth3_5.apk
I/SELinux ( 8604): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
E/SELinux ( 8604): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/art     (  313): Explicit concurrent mark sweep GC freed 8724(370KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 14MB/23MB, paused 282us total 12.024ms
D/LockPatternUtilsCache( 1173): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1173): value : false
D/LockPatternUtilsCache( 1173): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1173): value : false
I/art     (  313): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 14MB/23MB, paused 256us total 8.359ms
D/LockPatternUtilsCache( 1173): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1173): value : false
D/LockPatternUtilsCache( 1173): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1173): value : false
W/Resources(  918): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager(  918): creating new AssetManager and set to /system/app/Books/Books.apk
D/LockPatternUtilsCache( 1173): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1173): value : false
D/LockPatternUtilsCache( 1173): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1173): value : false
I/art     (  313): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 14MB/23MB, paused 262us total 7.903ms
D/LockPatternUtilsCache( 1173): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1173): value : false
D/LockPatternUtilsCache( 1173): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1173): value : false
D/LockPatternUtilsCache( 1173): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1173): value : false
I/Timeline(  918): Timeline: Activity_windows_visible id: ActivityRecord{ba5421 u0 com.sec.android.app.launcher/com.android.launcher2.Launcher t9} time:1907183
D/LockPatternUtilsCache( 1173): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1173): value : false
D/LockPatternUtilsCache( 1173): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1173): value : false
D/TimaKeyStoreProvider( 8604): TimaSignature is unavailable
D/ActivityThread( 8604): Added TimaKeyStore provider
D/ResourcesManager(  918): creating new AssetManager and set to /system/priv-app/SecGallery2014/SecGallery2014.apk
D/LockPatternUtilsCache( 1173): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1173): value : false
D/ResourcesManager(  918): creating new AssetManager and set to /system/priv-app/sCloudSyncCalendar/sCloudSyncCalendar.apk
D/ResourcesManager(  918): creating new AssetManager and set to /system/app/EditorsDocs/EditorsDocs.apk
D/ResourcesManager(  918): creating new AssetManager and set to /system/priv-app/sCloudSyncContacts/sCloudSyncContacts.apk
D/ResourcesManager(  918): creating new AssetManager and set to /system/priv-app/sCloudSyncMemo/sCloudSyncMemo.apk
D/ResourcesManager(  918): creating new AssetManager and set to /system/priv-app/sCloudSyncSBrowser/sCloudSyncSBrowser.apk
D/ResourcesManager( 8604): creating new AssetManager and set to /system/app/ELMAgent/ELMAgent.apk
D/ResourcesManager(  918): creating new AssetManager and set to /system/priv-app/sCloudSyncSNote3/sCloudSyncSNote3.apk
D/ResourcesManager(  918): creating new AssetManager and set to /system/app/Chrome/Chrome.apk
D/ResourcesManager(  918): creating new AssetManager and set to /system/app/Drive/Drive.apk
W/libprocessgroup(  918): failed to open /acct/uid_10178/pid_7910/cgroup.procs: No such file or directory
D/ResourcesManager(  918): creating new AssetManager and set to /system/app/Music2/Music2.apk
D/ResourcesManager(  918): creating new AssetManager and set to /system/app/EditorsDocs/EditorsDocs.apk
D/ResourcesManager(  918): creating new AssetManager and set to /system/app/Gmail2/Gmail2.apk
D/elm:14451( 8604): ELMAbstractReceiver.onReceive() : Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.receiver.MainReceiver (has extras) }
D/elm:14451( 8604): ELMEngine.ELMEngine( context ).
D/elm:14451( 8604): MDMBridge.setEnterpriseBridge()
D/ResourcesManager(  918): creating new AssetManager and set to /system/app/GoogleCalendarSyncAdapter/GoogleCalendarSyncAdapter.apk
D/elm:14451( 8604): ELMAbstractReceiver : Receive Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) } END.
I/art     (  918): Explicit concurrent mark sweep GC freed 12552(572KB) AllocSpace objects, 0(0B) LOS objects, 30% free, 36MB/52MB, paused 2.848ms total 233.417ms
E/ActivityManager(  918): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  918): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  918): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  918): checkUser: useridlist=null, currentuser=0
D/ResourcesManager(  918): creating new AssetManager and set to /system/app/SecEmail_K/SecEmail_K.apk
D/ResourcesManager(  918): creating new AssetManager and set to /system/app/GoogleContactsSyncAdapter/GoogleContactsSyncAdapter.apk
E/Zygote  ( 8620): MountEmulatedStorage()
E/Zygote  ( 8620): v2
I/libpersona( 8620): KNOX_SDCARD checking this for 10017
D/elm:14451( 8604): ElmAgentService : onCreate()
I/libpersona( 8620): KNOX_SDCARD not a persona
D/elm:14451( 8604): ElmAgentService : onHandleIntent() Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) }
D/elm:14451( 8604): MainReceiver.listeningToPackageRemoved()
D/elm:14451( 8604): MDMBridge.getInstance()
D/elm:14451( 8604): MDMBridge.getAllLicenseInfoFromSDK()
I/ActivityManager(  918): Start proc com.sec.android.service.health for broadcast com.sec.android.service.health/.upgrade.UninstallReceiver: pid=8620 uid=10017 gids={50017, 9997} abi=armeabi-v7a
D/ResourcesManager(  918): creating new AssetManager and set to /system/app/Newsstand/Newsstand.apk
D/ResourcesManager(  918): creating new AssetManager and set to /system/app/PlusOne/PlusOne.apk
D/ResourcesManager(  918): creating new AssetManager and set to /system/app/SBrowser/SBrowser.apk
I/SELinux ( 8620): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
I/SELinux ( 8620): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
D/elm:14451( 8604): MDMBridge.getAllLicenseInfoFromSDK()
E/SELinux ( 8620): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
D/elm:14451( 8604): ElmAgentService : onDestroy().
D/TimaKeyStoreProvider( 8620): TimaSignature is unavailable
D/ActivityThread( 8620): Added TimaKeyStore provider
I/ActivityManager(  918): Killing 7528:com.google.android.music:main/u0a126 (adj 15): empty for 1801s
D/ResourcesManager(  918): creating new AssetManager and set to /system/app/SecEmail_K/SecEmail_K.apk
D/ResourcesManager(  918): creating new AssetManager and set to /system/app/SecExchange/SecExchange.apk
D/ResourcesManager( 8620): creating new AssetManager and set to /system/priv-app/HealthService/HealthService.apk
W/Resources(  918): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager(  918): creating new AssetManager and set to /system/app/SecMemoDL/SecMemoDL.apk
D/ResourcesManager(  918): creating new AssetManager and set to /system/app/Videos/Videos.apk
D/ResourcesManager(  918): creating new AssetManager and set to /data/app/com.google.android.gms-1/base.apk
D/RCPManagerService(  918): PackageReceiver onReceive()
I/HarmonyEASService(  918): onReceive : android.intent.action.PACKAGE_REMOVED for 0
D/KnoxMUMContainerPolicy(  918): mPackageReceiver : action - android.intent.action.PACKAGE_REMOVED
D/com.sec.android.service.health.upgrade.UninstallReceiver( 8620): onReceive()
I/com.sec.android.service.health.upgrade.UninstallReceiver( 8620): onReceive called  PACKAGE_REMOVED package:com.test.thalitest
D/com.sec.android.service.health.upgrade.UninstallReceiver( 8620): onReceive() : package name is not s health. Return !!!
E/ActivityManager(  918): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  918): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  918): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  918): checkUser: useridlist=null, currentuser=0
D/BackupManagerService(  918): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
D/JobSchedulerService(  918): Receieved: android.intent.action.PACKAGE_REMOVED
V/EnterpriseBillingPolicy(  918): packageModificationReceiver - onreceive - start - android.intent.action.PACKAGE_REMOVED
V/EnterpriseBillingPolicy(  918): uID is 10367
V/EnterpriseBillingPolicy(  918): Removed Packageuid is0
V/EnterpriseBillingPolicyStorage(  918): getProfileForApplication - enter
V/EnterpriseBillingPolicyStorage(  918): getProfileForApplication - exit null
V/EnterpriseBillingPolicy(  918): packageModificationReceiver - onreceive - personal application - profile null
V/EnterpriseBillingPolicy(  918): packageModificationReceiver - onreceive - might be a vpn vendor package 
V/EnterpriseBillingPolicyStorage(  918): getBillingProfileForVpnEngine - start - com.test.thalitest
W/Resources(  918): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
V/EnterpriseBillingPolicyStorage(  918): getBillingProfileForVpnEngine - end - null
E/Zygote  ( 8636): MountEmulatedStorage()
E/Zygote  ( 8636): v2
I/libpersona( 8636): KNOX_SDCARD checking this for 1000
I/libpersona( 8636): KNOX_SDCARD not a persona
D/ResourcesManager(  918): creating new AssetManager and set to /system/app/YouTube/YouTube.apk
I/ActivityManager(  918): Start proc com.sec.pcw.device for broadcast com.sec.pcw.device/.receiver.SYSTEMReceiver: pid=8636 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
I/ActivityManager(  918): Killing 4711:com.google.android.gms.wearable/u0a12 (adj 15): empty for 1801s
D/TaskPersister(  918): removeObsoleteFile: deleting file=11_task.xml
D/TaskPersister(  918): removeObsoleteFile: deleting file=11_task_thumbnail.png
I/SELinux ( 8636): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
I/SELinux ( 8636): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
D/PackageManager(  918): delete codoeFile: 
E/SELinux ( 8636): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
D/ResourcesManager(  918): creating new AssetManager and set to /system/priv-app/SFinder/SFinder.apk
W/Resources(  918): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources(  918): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager(  918): creating new AssetManager and set to /system/app/ChatON_MARKET/ChatON_MARKET.apk
W/Resources(  918): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager(  918): creating new AssetManager and set to /system/app/Chrome/Chrome.apk
W/libprocessgroup(  918): failed to open /acct/uid_10126/pid_7528/cgroup.procs: No such file or directory
W/libprocessgroup(  918): failed to open /acct/uid_10012/pid_4711/cgroup.procs: No such file or directory
D/PackageManager(  918): result of delete: 1{657007618}
D/ResourcesManager(  918): creating new AssetManager and set to /system/app/Drive/Drive.apk
D/TimaKeyStoreProvider( 8636): TimaSignature is unavailable
D/ActivityThread( 8636): Added TimaKeyStore provider
D/AndroidRuntime( 8555): Shutting down VM
D/ResourcesManager( 8636): creating new AssetManager and set to /system/priv-app/PCWClientS18/PCWClientS18.apk
D/ResourcesManager(  918): creating new AssetManager and set to /system/app/InteractiveTutorial/InteractiveTutorial.apk
W/Resources(  918): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager(  918): creating new AssetManager and set to /system/app/PlayGames/PlayGames.apk
I/PCWCLIENTTRACE_LOG( 8636): DEFAULT_LOGON : true
I/PCWCLIENTTRACE_LOG( 8636): DEFAULT_LOGLEVEL : 3
I/PCWCLIENTTRACE_DMDBOpenHelper( 8636): new DMDBOpenHelper instance
D/ResourcesManager(  918): creating new AssetManager and set to /system/app/SPlanner_OS_UPG/SPlanner_OS_UPG.apk
W/ResourcesManager(  918): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager(  918): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager(  918): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/Resources(  918): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager(  918): creating new AssetManager and set to /system/app/SmartRemote_KL/SmartRemote_KL.apk
I/PCWCLIENTTRACE_PushUtil( 8636): SPPPushClient is installed : true
I/PCWCLIENTTRACE_PushUtil( 8636): sales region : global
I/PCWCLIENTTRACE_PushUtil( 8636): getPushTypeList : [SPP, GCM]
I/PCWCLIENTTRACE_SYSTEMReceiver( 8636): [onReceive] - android.intent.action.PACKAGE_REMOVED
E/ActivityManager(  918): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  918): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  918): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  918): checkUser: useridlist=null, currentuser=0
E/Zygote  ( 8651): MountEmulatedStorage()
E/Zygote  ( 8651): v2
I/libpersona( 8651): KNOX_SDCARD checking this for 10034
D/ResourcesManager(  918): creating new AssetManager and set to /data/app/de.pizza-1/base.apk
I/libpersona( 8651): KNOX_SDCARD not a persona
I/ActivityManager(  918): Start proc com.samsung.android.app.galaxyfinder for broadcast com.samsung.android.app.galaxyfinder/.ApplicationStatusReceiver: pid=8651 uid=10034 gids={50034, 9997, 1028, 1015, 3003, 3002} abi=armeabi-v7a
I/ActivityManager(  918): Killing 7681:com.sec.spp.push/u0a38 (adj 15): empty for 1801s
D/ResourcesManager(  918): creating new AssetManager and set to /data/app/de.kaufda.android-1/base.apk
D/ResourcesManager(  918): creating new AssetManager and set to /system/priv-app/Velvet/Velvet.apk
D/ResourcesManager(  918): creating new AssetManager and set to /system/priv-app/SamsungMusic_20/SamsungMusic_20.apk
W/Resources(  918): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager(  918): creating new AssetManager and set to /system/priv-app/SecContacts/SecContacts.apk
I/SELinux ( 8651): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
I/SELinux ( 8651): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
E/SELinux ( 8651): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
W/Resources(  918): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager(  918): creating new AssetManager and set to /system/priv-app/SecGallery2014/SecGallery2014.apk
W/Resources(  918): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources(  918): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
D/ResourcesManager(  918): creating new AssetManager and set to /system/priv-app/SecMyFiles2014/SecMyFiles2014.apk
W/libprocessgroup(  918): failed to open /acct/uid_10038/pid_7681/cgroup.procs: No such file or directory
D/TimaKeyStoreProvider( 8651): TimaSignature is unavailable

```
