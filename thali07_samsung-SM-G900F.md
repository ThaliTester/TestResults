#### Test 549702610b97681_thali07_samsung-SM-G900F Logs


```
--------- beginning of main
W/GLSActivity( 1676): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1676): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1676): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1676): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1676): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1676): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1676): 	at android.os.Binder.execTransact(Binder.java:446)
E/BooksAccountManager( 7369): Authentication error
E/BooksAccountManager( 7369): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 7369): android.accounts.AccountManager.convertErrorToException(AccountManager.java:1893)
E/HttpHelper( 7369): null auth token
I/qtaguid ( 7369): Tagging socket 34 with tag 10000000000{256,0} uid -1, pid: 7369, getuid(): 10082
I/WifiStateMachine(  872): CMD_RSSI_POLL : calculateWifiScore in!
I/WifiStateMachine(  872): CMD_RSSI_POLL : calculateWifiScore out!
I/WifiStateMachine(  872): CMD_RSSI_POLL : out!
E/LightSensor(  872): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
--------- beginning of system
D/AutomaticBrightnessController(  872): mCallbacks.updateBrightness()
D/DisplayPowerController(  872): getFinalBrightness : 8 -> 8
I/qtaguid ( 7369): Untagging socket 34
W/ApiaryClient( 7369): Error response from books API: {
W/ApiaryClient( 7369):  "error": {
W/ApiaryClient( 7369):   "errors": [
W/ApiaryClient( 7369):    {
W/ApiaryClient( 7369):     "domain": "global",
W/ApiaryClient( 7369):     "reason": "required",
W/ApiaryClient( 7369):     "message": "Login Required",
W/ApiaryClient( 7369):     "locationType": "header",
W/ApiaryClient( 7369):     "location": "Authorization"
W/ApiaryClient( 7369):    }
W/ApiaryClient( 7369):   ],
W/ApiaryClient( 7369):   "code": 401,
W/ApiaryClient( 7369):   "message": "Login Required"
W/ApiaryClient( 7369):  }
W/ApiaryClient( 7369): }
W/ApiaryClient( 7369): errCount = 3: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 7369): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3DS0HXd4TFLU4&nonce=2538866350050913216&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 7369): Headers suppressed
D/ConnectivityService(  872): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/LightSensor(  872): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
D/AutomaticBrightnessController(  872): mCallbacks.updateBrightness()
D/DisplayPowerController(  872): getFinalBrightness : 8 -> 8
E/LightSensor(  872): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 3, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=1, bp1=1, cp1=3, cpl=3202560
D/AutomaticBrightnessController(  872): mCallbacks.updateBrightness()
D/DisplayPowerController(  872): getFinalBrightness : 8 -> 8
D/AndroidRuntime( 7416): 
D/AndroidRuntime( 7416): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 7416): CheckJNI is OFF
D/AndroidRuntime( 7416): setted country_code = Germany
D/AndroidRuntime( 7416): setted countryiso_code = DE
D/AndroidRuntime( 7416): setted sales_code = DBT
D/AndroidRuntime( 7416): readGMSProperty: start
D/AndroidRuntime( 7416): readGMSProperty: already setted!!
D/AndroidRuntime( 7416): readGMSProperty: end
D/AndroidRuntime( 7416): addProductProperty: start
E/LightSensor(  872): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 3, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=1, bp1=1, cp1=3, cpl=3202560
D/AutomaticBrightnessController(  872): mCallbacks.updateBrightness()
D/DisplayPowerController(  872): getFinalBrightness : 8 -> 8
E/LightSensor(  872): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
D/AutomaticBrightnessController(  872): mCallbacks.updateBrightness()
D/DisplayPowerController(  872): getFinalBrightness : 8 -> 8
E/AffinityControl( 7416): AffinityControl: registerfunction enter
D/AndroidRuntime( 7416): Calling main entry com.android.commands.am.Am
E/PersonaManagerService(  872): inState():  stateMachine is null !!
V/ApplicationPolicy(  872): isApplicationStateBlocked userId 0 pkgname com.test.thalitest
I/ActivityManager(  872): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
D/ResourcesManager(  872): creating new AssetManager and set to /data/app/com.test.thalitest-1/base.apk
D/CustomFrequencyManagerService(  872): acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1958400  uid : 1000  pid : 872  pkgName : ACTIVITY_RESUME_BOOSTER@6
W/ActivityManager(  872): mDVFSHelper.acquire()
D/FocusedStackFrame(  872): Set to : 0
D/Launcher.HomeView( 1489): onPause
D/Launcher( 1489): Launcher::setSystemUiTransparency(): getSystemUiVisibility() after setting  = 40000000
D/AndroidRuntime( 7416): Shutting down VM
D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
I/SurfaceFlinger(  249): id=14 createSurf (1x1),1 flag=404, Starting com.test.thalitest
V/TaskCloserActivity( 7217): TaskCloserActivity onReceive() - com.sec.android.intent.action.HOME_PAUSE
D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
E/ActivityManager(  872): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  872): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  872): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  872): checkUser: useridlist=null, currentuser=0
E/Zygote  ( 7436): MountEmulatedStorage()
E/Zygote  ( 7436): v2
I/libpersona( 7436): KNOX_SDCARD checking this for 10367
I/libpersona( 7436): KNOX_SDCARD not a persona
D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
I/ActivityManager(  872): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=7436 uid=10367 gids={50367, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
E/LightSensor(  872): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
D/AutomaticBrightnessController(  872): mCallbacks.updateBrightness()
D/DisplayPowerController(  872): getFinalBrightness : 8 -> 8
I/SELinux ( 7436): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
I/SELinux ( 7436): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
E/SELinux ( 7436): [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
D/StatusBarManagerService(  872): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
I/MicrophoneInputStream( 1569): mic_close gfk@3988473f
D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
V/AudioPolicyManager(  285): stopInput() input 29
V/AudioPolicyManager(  285): releaseInput() 29
V/AudioPolicyManager(  285): closeInput(29)
I/HotwordRecognitionRnr( 1569): Stopping hotword detection.
I/HotwordRecognitionRnr( 1569): Hotword detection finished
V/audio_hw_primary(  285): in_standby: enter
D/TimaKeyStoreProvider( 7436): TimaSignature is unavailable
D/ActivityThread( 7436): Added TimaKeyStore provider
V/WindowOrientationListener(  872): mSContextAutoRotationListener.getProposedRotation, mbResultFaceDectection: false
V/WindowOrientationListener(  872): mSContextAutoRotationListener.getProposedRotation, Rotation: -1
V/WindowManager(  872): rotationForOrientationLw(orient=-1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false
V/WindowOrientationListener(  872): mSContextAutoRotationListener.getProposedRotation, mbResultFaceDectection: false
V/WindowOrientationListener(  872): mSContextAutoRotationListener.getProposedRotation, Rotation: -1
V/ActivityManager(  872): Display changed displayId=0
D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
D/Launcher.HomeView( 1489): onStop
D/SurfaceWidgetClient$ISurfaceWidgetStub( 2142): [237392/6] Surface widget pause on instance = 1
D/accuweather( 2142): [KK AccuPhone]>>> SWW:239 [0:0] [SWW] onPause : instance = 1
D/accuweather( 2142): [KK AccuPhone]>>> SWW:254 [0:0] onPause : size = 0
D/accuweather( 2142): [KK AccuPhone]>>> SWW:545 [0:0]  unRegisterTTReceiver !! 
D/SurfaceWidgetClient$ISurfaceWidgetStub( 2142): [237392/6] Surface widget visibility changed visibility = false on instance = 1
D/SurfaceWidgetView( 1489): destroyHardwareResources():254796797
D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
D/StatusBarManagerService(  872): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
V/audio_hw_primary(  285): stop_input_stream: enter: usecase(7: audio-record)
V/audio_hw_primary(  285): disable_audio_route: enter: usecase(7)
V/audio_hw_primary(  285): disable_audio_route: reset mixer path: audio-record
D/audio_route(  285): ++++ audio_route_update_mixer ==============
D/audio_route(  285): Setting mixer control: MultiMedia1 Mixer SLIM_0_TX
D/audio_route(  285): Setting mixer control: value: 0
D/audio_route(  285): ------ audio_route_update_mixer ==============
V/audio_hw_primary(  285): disable_audio_route: exit
V/audio_hw_primary(  285): disable_snd_device: snd_device(122: vr-main-mic)
D/audio_route(  285): ++++ audio_route_update_mixer ==============
D/audio_route(  285): Setting mixer control: DEC2 Volume
D/audio_route(  285): Setting mixer control: value: 0
D/audio_route(  285): Setting mixer control: SLIM TX7 MUX, value: 0
D/audio_route(  285): Setting mixer control: AIF1_CAP Mixer SLIM TX7
D/audio_route(  285): Setting mixer control: value: 0
D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
D/audio_route(  285): Setting mixer control: DEC2 MUX, value: 0
D/ConnectivityService(  872): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/audio_route(  285): ------ audio_route_update_mixer ==============
V/audio_hw_primary(  285): stop_input_stream: exit: status(0)
V/audio_hw_primary(  285): in_standby: exit:  status(0)
V/audio_hw_primary(  285): adev_close_input_stream
V/audio_hw_primary(  285): in_standby: enter
V/audio_hw_primary(  285): in_standby: exit:  status(0)
E/audio_hw_primary(  285): adev_close_input_stream, set jack_in to null
V/AudioPolicyManager(  285): releaseInput() exit
D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
D/accuweather( 2142): [KK AccuPhone]>>> WR:132 [0:0] onPause
D/accuweather( 2142): [KK AccuPhone]>>> SM:538 [0:0] onPause
D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
D/ResourcesManager( 7436): creating new AssetManager and set to /data/app/com.test.thalitest-1/base.apk
D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/Launcher( 1489): onTrimMemory. Level: 20
D/LockPatternUtilsCache( 1168): value : false
D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
E/BooksSync( 7369): Soft error
E/BooksSync( 7369): com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
E/BooksSync( 7369): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3DS0HXd4TFLU4&nonce=2538866350050913216&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
E/BooksSync( 7369): Headers suppressed
E/BooksSync( 7369): 
E/BooksSync( 7369): com.google.android.apps.books.net.HttpHelper.wrapExceptionBasedOnStatus(HttpHelper.java:212)
E/BooksSync( 7369): Sync error
E/BooksSync( 7369): com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
E/BooksSync( 7369): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3DS0HXd4TFLU4&nonce=2538866350050913216&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
E/BooksSync( 7369): Headers suppressed
E/BooksSync( 7369): 
E/BooksSync( 7369): com.google.android.apps.books.net.HttpHelper.wrapExceptionBasedOnStatus(HttpHelper.java:212)
I/BooksSync( 7369): Finished books sync
D/ConnectivityService(  872): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
D/SurfaceWidgetView( 1489): destroyHardwareResources():254796797
D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
I/ActivityManager(  872): Killing 6613:com.sec.knox.knoxsetupwizardclient/1000 (adj 15): bgCount ##41
D/SyncManager(  872): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 65334, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
D/ConnectivityService(  872): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
D/ConnectivityService(  872): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
,E/LightSensor(  872): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
D/AutomaticBrightnessController(  872): mCallbacks.updateBrightness()
D/DisplayPowerController(  872): getFinalBrightness : 8 -> 8
D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
W/libprocessgroup(  872): failed to open /acct/uid_1000/pid_6613/cgroup.procs: No such file or directory
D/SecContentProvider2(  872): uri = 11 selection = getMyKnoxAdmin
D/SecContentProvider2(  872): mCursor = null
D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
I/WebViewFactory( 7436): Loading com.google.android.webview version 37 (1726107-arm) (code 119201)
D/ResourcesManager( 7436): creating new AssetManager and set to /system/app/WebViewGoogle/WebViewGoogle.apk
D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
I/LibraryLoader( 7436): Loading: webviewchromium
I/LibraryLoader( 7436): Time to load native libraries: 1 ms (timestamps 5965-5966)
I/LibraryLoader( 7436): Expected native library version number "",actual native library version number ""
D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
V/WebViewChromiumFactoryProvider( 7436): Binding Chromium to main looper Looper (main, tid 1) {2c222f30}
I/LibraryLoader( 7436): Expected native library version number "",actual native library version number ""
I/chromium( 7436): [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 7436): Initializing chromium process, renderers=0
W/art     ( 7436): Attempt to remove local handle scope entry from IRT, ignoring
W/chromium( 7436): [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
I/chromium( 7436): [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=35 off=46768 len=2953
I/chromium( 7436): [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:36 off:229524 len:643667
D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
I/Adreno-EGL( 7436): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 7436): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 7436): Build Date: 03/03/15 Tue
I/Adreno-EGL( 7436): Local Branch: LA.BF.1.1_RB1_20150108_025_1077123_1158499
I/Adreno-EGL( 7436): Remote Branch: 
I/Adreno-EGL( 7436): Local Patches: 
I/Adreno-EGL( 7436): Reconstruct Branch: 
D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
D/StatusBar.NetworkController( 1168): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02012b/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020464/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
D/StatusBar.NetworkController( 1168): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1168): applyOpen
D/StatusBar.NetworkController( 1168): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1168): applyOpen
D/StatusBar.NetworkController( 1168): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1168): applyOpen
D/StatusBar.NetworkController( 1168): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1168): applyOpen
D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
W/chromium( 7436): [WARNING:proxy_service.cc(901)] PAC support disabled because there is no system implementation
W/chromium( 7436): [WARNING:data_reduction_proxy_settings.cc(403)] SPDY proxy OFF at startup
W/art     ( 7436): Attempt to remove local handle scope entry from IRT, ignoring
E/LightSensor(  872): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
D/AutomaticBrightnessController(  872): mCallbacks.updateBrightness()
D/DisplayPowerController(  872): getFinalBrightness : 8 -> 8
W/AwContents( 7436): onDetachedFromWindow called when already detached. Ignoring
D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
D/SystemWebViewEngine( 7436): CordovaWebView is running on device made by: samsung
D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
W/art     ( 7436): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 7436): Attempt to remove local handle scope entry from IRT, ignoring
D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
D/PowerManagerService(  872): [api] release WakeLock flags=0x10000006 tag=PowerUI.Notification uid=10059 pid=1168 (0x0)
D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
D/Activity( 7436): performCreate Call secproduct feature valuefalse
D/Activity( 7436): performCreate Call debug elastic valuetrue
D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
D/OpenGLRenderer( 7436): Render dirty regions requested: true
D/ActivityManager(  872): post active user change for 0
D/KnoxTimeoutHandler(  872): postActiveUserChange for user 0
D/KnoxTimeoutHandler(  872): handleActiveUserChange for user 0
D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
I/SurfaceFlinger(  249): id=15 createSurf (1x1),1 flag=404, com.test.thalitest/com.test.thalitest.MainActivity
D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
I/OpenGLRenderer( 7436): Initialized EGL, version 1.4
I/OpenGLRenderer( 7436): HWUI protection enabled for context ,  &this =0xa1553060 ,&mEglDisplay = 1 , &mEglConfig = 8 
D/OpenGLRenderer( 7436): Enabling debug mode 0
D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
E/LightSensor(  872): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
D/AutomaticBrightnessController(  872): mCallbacks.updateBrightness()
D/DisplayPowerController(  872): getFinalBrightness : 8 -> 8
D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
I/SurfaceFlinger(  249): id=8 Removed com.sec.android.app.launcher/com.android.launcher2.Launcher (4/9)
I/SurfaceFlinger(  249): id=8 Removed com.sec.android.app.launcher/com.android.launcher2.Launcher (-2/9)
D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
D/InputMethodManagerService(  872): windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
W/ContextImpl(  872): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.android.server.InputMethodManagerService$6.run:2728 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
W/ContextImpl(  872): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.android.server.InputMethodManagerService$6.run:2728 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
I/ActivityManager(  872): Displayed com.test.thalitest/.MainActivity: +636ms
D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
I/Timeline( 7436): Timeline: Activity_idle id: android.os.BinderProxy@295c4063 time:96318
D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
D/JsMessageQueue( 7436): Set native->JS mode to OnlineEventsBridgeMode
E/LightSensor(  872): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
D/AutomaticBrightnessController(  872): mCallbacks.updateBrightness()
D/DisplayPowerController(  872): getFinalBrightness : 8 -> 8
D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
I/chromium( 7436): [INFO:SkUtilsArm.cpp(179)] Device supports ARM NEON instructions!
I/chromium( 7436): 
D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
D/jxcore_app_log( 7436): JniHelper::setJavaVM(0xb4e5c280), pthread_self() = -1259381504
D/JX-Cordova( 7436): jxcore cordova android initializing
D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
I/SurfaceFlinger(  249): id=14 Removed Starting com.test.thalitest (7/8)
I/SurfaceFlinger(  249): id=14 Removed Starting com.test.thalitest (-2/8)
D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
D/CustomFrequencyManagerService(  872): releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1958400  uid : 1000  pid : 872  tag : ACTIVITY_RESUME_BOOSTER@6
W/ActivityManager(  872): mDVFSHelper.release()
I/Timeline(  872): Timeline: Activity_windows_visible id: ActivityRecord{296b5bfa u0 com.test.thalitest/.MainActivity t11} time:96546
D/CustomFrequencyManagerService(  872): acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1958400  uid : 1000  pid : 872  pkgName : ACTIVITY_RESUME_BOOSTER@10
D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
E/LightSensor(  872): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 3, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=1, bp1=1, cp1=3, cpl=3202560
D/AutomaticBrightnessController(  872): mCallbacks.updateBrightness()
D/DisplayPowerController(  872): getFinalBrightness : 8 -> 8
,I/GAV2    ( 7369): Thread[GAThread,5,main]: No campaign data found.
,E/LightSensor(  872): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 3, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=1, bp1=1, cp1=3, cpl=3202560
,D/AutomaticBrightnessController(  872): mCallbacks.updateBrightness()
D/DisplayPowerController(  872): getFinalBrightness : 8 -> 8
,D/CustomFrequencyManagerService(  872): releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1958400  uid : 1000  pid : 872  tag : ACTIVITY_RESUME_BOOSTER@10
,E/LightSensor(  872): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 3, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=1, bp1=1, cp1=3, cpl=3202560
,D/AutomaticBrightnessController(  872): mCallbacks.updateBrightness()
D/DisplayPowerController(  872): getFinalBrightness : 8 -> 8
,D/SSRM:m  (  872): SIOP:: AP = 360, PST = 421, CUR = 300
,E/LightSensor(  872): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 3, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=1, bp1=1, cp1=3, cpl=3202560
,D/AutomaticBrightnessController(  872): mCallbacks.updateBrightness()
D/DisplayPowerController(  872): getFinalBrightness : 8 -> 8
,E/LightSensor(  872): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 3, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=1, bp1=1, cp1=3, cpl=3202560
,D/AutomaticBrightnessController(  872): mCallbacks.updateBrightness()
D/DisplayPowerController(  872): getFinalBrightness : 8 -> 8
,E/LightSensor(  872): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 3, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=1, bp1=1, cp1=3, cpl=3202560
,D/AutomaticBrightnessController(  872): mCallbacks.updateBrightness()
,D/DisplayPowerController(  872): getFinalBrightness : 8 -> 8
,E/SMD     (  279): DCD ON
,E/LightSensor(  872): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 3, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=1, bp1=1, cp1=3, cpl=3202560
,D/AutomaticBrightnessController(  872): mCallbacks.updateBrightness()
D/DisplayPowerController(  872): getFinalBrightness : 8 -> 8
,I/WifiStateMachine(  872): CMD_RSSI_POLL : calculateWifiScore in!
,I/WifiStateMachine(  872): CMD_RSSI_POLL : calculateWifiScore out!
I/WifiStateMachine(  872): CMD_RSSI_POLL : out!
,E/LightSensor(  872): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 3, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=1, bp1=1, cp1=3, cpl=3202560
,D/AutomaticBrightnessController(  872): mCallbacks.updateBrightness()
D/DisplayPowerController(  872): getFinalBrightness : 8 -> 8
,W/jxcore-log( 7436): Initializing JXcore engine
,W/jxcore-log( 7436): JXcore engine is ready
,W/jxcore-log( 7436): Starting JXcore engine
,E/LightSensor(  872): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 3, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=1, bp1=1, cp1=3, cpl=3202560
,D/AutomaticBrightnessController(  872): mCallbacks.updateBrightness()
D/DisplayPowerController(  872): getFinalBrightness : 8 -> 8
,E/auditd  ( 2138): In denial and Property audit_ondenial is set to 1 
,D/SecurityLogAgent:SEDenialService(  872): Got Modify Event and sending Denial Intent foraudit.log
,W/ContextImpl(  872): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.android.server.SEDenialService$AuditFileObserver.onEvent:76 android.os.FileObserver$ObserverThread.onEvent:122 android.os.FileObserver$ObserverThread.observe:-2 android.os.FileObserver$ObserverThread.run:85 
,D/SecurityLogAgent:SEDenialService(  872): audit.ondenial set to 0 after sending samsung.intent.action.knox.DENIAL_NOTIFICATION intent
,E/ActivityManager(  872): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  872): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  872): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  872): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 7500): MountEmulatedStorage()
,E/Zygote  ( 7500): v2
I/libpersona( 7500): KNOX_SDCARD checking this for 1000
I/libpersona( 7500): KNOX_SDCARD not a persona
,I/ActivityManager(  872): Start proc com.samsung.android.securitylogagent for broadcast com.samsung.android.securitylogagent/.receivers.SeDenialReceiver: pid=7500 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,I/SELinux ( 7500): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
I/SELinux ( 7500): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
E/SELinux ( 7500): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 7500): TimaSignature is unavailable
,D/ActivityThread( 7500): Added TimaKeyStore provider
,W/jxcore-log( 7436): Platform android
W/jxcore-log( 7436): 
W/jxcore-log( 7436): Process ARCH arm
W/jxcore-log( 7436): 
,D/ResourcesManager( 7500): creating new AssetManager and set to /system/app/SecurityLogAgent/SecurityLogAgent.apk
,E/LightSensor(  872): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 3, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=1, bp1=1, cp1=3, cpl=3202560
,D/AutomaticBrightnessController(  872): mCallbacks.updateBrightness()
D/DisplayPowerController(  872): getFinalBrightness : 8 -> 8
,D/SecurityLogAgent( 7500):  SeDenialReceiver : Intent Received : samsung.intent.action.knox.DENIAL_NOTIFICATION
,D/SecurityLogAgent( 7500):  SeDenialReceiver : File path = null
,I/ActivityManager(  872): Killing 6733:com.google.android.partnersetup/u0a15 (adj 15): bgCount ##41
,W/libprocessgroup(  872): failed to open /acct/uid_10015/pid_6733/cgroup.procs: No such file or directory
,E/LightSensor(  872): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 3, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=1, bp1=1, cp1=3, cpl=3202560
,D/AutomaticBrightnessController(  872): mCallbacks.updateBrightness()
D/DisplayPowerController(  872): getFinalBrightness : 8 -> 8
,E/LightSensor(  872): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 3, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=1, bp1=1, cp1=3, cpl=3202560
,D/AutomaticBrightnessController(  872): mCallbacks.updateBrightness()
D/DisplayPowerController(  872): getFinalBrightness : 8 -> 8
,E/LightSensor(  872): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 3, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=1, bp1=1, cp1=3, cpl=3202560
,D/AutomaticBrightnessController(  872): mCallbacks.updateBrightness()
,D/DisplayPowerController(  872): getFinalBrightness : 8 -> 8
,I/jxcore-log( 7436): JXcore Cordova bridge is ready!
I/jxcore-log( 7436): 
,W/jxcore-log( 7436): JXcore engine is started
,E/Adreno-ES20( 7436): <check_framebuffer_attachment:854>: Invalid texture format! Returning error!
,E/Adreno-ES20( 7436): <check_framebuffer_object_status:1237>: Framebuffer color attachment incomplete. Returning GL_FRAMEBUFFER_INCOMPLETE_ATTACHMENT!
,I/jxcore-log( 7436): Toggling radios to true
I/jxcore-log( 7436): 
,D/BluetoothAdapter( 7436): enable()
,D/BluetoothAdapter( 7436): enable(): BT is already enabled..!
,D/WifiService(  872): New client listening to asynchronous messages
,I/WifiManager( 7436): packageName : com.test.thalitest
,D/SecContentProvider(  872): uri = 18 selection = isWifiEnabled
,D/SecContentProvider2(  872): uri = 20 selection = isWifiStateChangeAllowed
D/SecContentProvider2(  872): mCursor = null
,D/WifiService(  872): setWifiEnabled: true pid=7436, uid=10367
,E/WifiService(  872): Invoking mWifiStateMachine.setWifiEnabled
,W/ActivityManager(  872): Permission Denial: getCurrentUser() from pid=7436, uid=10367 requires android.permission.INTERACT_ACROSS_USERS
,W/WifiService(  872): Failed getting userId using ActivityManagerNative
W/WifiService(  872): java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=7436, uid=10367 requires android.permission.INTERACT_ACROSS_USERS
W/WifiService(  872): 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:22619)
W/WifiService(  872): 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2119)
W/WifiService(  872): 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2107)
W/WifiService(  872): 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:223)
W/WifiService(  872): 	at android.os.Binder.execTransact(Binder.java:446)
,D/SettingsProvider(  872): name = wifi_on
,I/WifiService(  872): disconnect: pid=7436, uid=10367
,I/wpa_supplicant( 1252): [wpa_supplicant_ctrl_iface_process] : DISCONNECT
I/jxcore-log( 7436): Radios toggled
I/jxcore-log( 7436): 
I/jxcore-log( 7436): My device name is: samsung-SM-G900F
I/jxcore-log( 7436): 
,E/LightSensor(  872): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 3, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=1, bp1=1, cp1=3, cpl=3202560
,D/AutomaticBrightnessController(  872): mCallbacks.updateBrightness()
D/DisplayPowerController(  872): getFinalBrightness : 8 -> 8
,I/wpa_supplicant( 1252): CTRL-EVENT-DISCONNECTED bssid=C0.AA.48 reason=3 locally_generated=1
,I/wpa_supplicant( 1252): wlan0: State: COMPLETED -> DISCONNECTED
,I/wpa_supplicant( 1252): CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=C0.AA.48 SSID=4E47373030
,I/wpa_supplicant( 1252): wlan0: State: DISCONNECTED -> DISCONNECTED
,E/WifiStateMachine(  872): WifiStateMachine: Leaving Connected state
I/wpa_supplicant( 1252): reset timer : RESET_TIMER 0
I/wpa_supplicant( 1252): wlan0: Setting scan request: 0 sec 0 usec
I/wpa_supplicant( 1252): Disconnected - do not scan
I/wpa_supplicant( 1252): wlan0: State: DISCONNECTED -> DISCONNECTED
,E/WifiStateMachine(  872): handleNetworkDisconnect: Stopping DHCP and clearing IP stack:handleNetworkDisconnect - access$11200 - exit - invokeExitMethods
,E/WifiStateMachine(  872): handleNetworkDisconnect c0:ff:d4:d3:aa:48 config "NG700"WPA_PSK config.bssid any
E/WifiStateMachine(  872): handleNetworkDisconnect "NG700" nid=0
E/WifiConfigStore(  872): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,E/WifiStateMachine(  872): setSuspendOptimizationsNative: 1 true -want true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - stopDhcp - handleNetworkDisconnect
,D/WifiP2pService(  872): InactiveState{ what=143375 }
,D/WifiP2pService(  872): P2pEnabledState{ what=143375 }
,D/CommandListener(  272): Clearing all IP addresses on wlan0
,D/StatusBar.NetworkController( 1168): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02012b/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020464/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
,V/AlarmManager(  872): waitForAlarm result :4
,V/NativeCrypto( 1676): Read error: ssl=0xaef2be00: I/O error during system call, Connection timed out
,E/WifiStateMachine(  872): setDetailed state, old =CONNECTED and new state=DISCONNECTED hidden=false
,E/ConnectivityService(  872): updateNetworkInfo()
D/ConnectivityService(  872): NetworkAgentInfo [WIFI () - 502] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
,I/WifiTrafficPoller(  872): evaluateTrafficStatsPolling
,I/CLocInfoService(  872): External Intent Received android.net.wifi.STATE_CHANGE
,D/ConnectivityService(  872): NetworkAgentInfo [WIFI () - 502] got DISCONNECTED, was satisfying 2
,V/NativeCrypto( 1676): SSL shutdown failed: ssl=0xaef2be00: I/O error during system call, Broken pipe
,D/StatusBar.NetworkController( 1168): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020498/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020133/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020464/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
,E/WifiConfigStore(  872): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,D/StatusBar.NetworkController( 1168): refreshSignalCluster - setNWBoosterIndicators(false)
,E/WifiStateMachine(  872): Start Disconnecting Watchdog 1
,I/wpa_supplicant( 1252): wlan0: Setting scan request: 0 sec 0 usec
I/wpa_supplicant( 1252): P2P: Current p2p state = IDLE
I/wpa_supplicant( 1252): wlan0: State: DISCONNECTED -> SCANNING
I/wpa_supplicant( 1252): CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00.00.00 SSID=
I/wpa_supplicant( 1252): First Scan Start
,I/wpa_supplicant( 1252): Scan requested (ret=0) - scan timeout 30 seconds
,D/StatusBar.NetworkController( 1168): applyOpen
,D/StatusBar.NetworkController( 1168): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1168): applyOpen
D/StatusBar.NetworkController( 1168): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1168): applyOpen
D/StatusBar.NetworkController( 1168): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1168): applyOpen
,E/WifiStateMachine(  872): ConnectModeState: Network connection lost 
,E/WifiStateMachine(  872): handleNetworkDisconnect: Stopping DHCP and clearing IP stack:handleNetworkDisconnect - access$11200 - processMessage - processMsg
,E/WifiStateMachine(  872): setSuspendOptimizationsNative: 1 true -want true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - stopDhcp - handleNetworkDisconnect
,D/WifiP2pService(  872): InactiveState{ what=143375 }
,D/WifiP2pService(  872): P2pEnabledState{ what=143375 }
,D/StatusBar.NetworkController( 1168): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020498/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020133/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020464/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
,D/ConnectivityService(  872): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  872): reportBadNetwork(NetworkAgentInfo [WIFI () - 502]) by 10012
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  872): ValidatedState{ when=0 what=532488 arg1=10012 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  872): DefaultState{ when=-2ms what=532488 arg1=10012 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  872): Forcing reevaluation
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  872): EvaluatingState{ when=0 what=532486 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  872): Validated
,D/ConnectivityService(  872): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  872): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/CommandListener(  272): Clearing all IP addresses on wlan0
D/ConnectivityService(  872): notifyType LOST for NetworkAgentInfo [WIFI () - 502]
D/ConnectivityService(  872): calling update connectivity
,D/ConnectivityService(  872):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  872):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  872): sending notification LOST for NetworkRequest [ id=2, legacyType=-1, [] ]
D/Nat464Xlat(  872): requiresClat: netType=1, connected=false, hasIPv4Address=true
D/ConnectivityService(  872): Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  872): sending new Min Network Score(0): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,E/WifiStateMachine(  872): setDetailed state, old =DISCONNECTED and new state=DISCONNECTED hidden=false
D/ConnectivityManager.CallbackHandler( 1168): CM callback handler got msg 524292
,D/CSLegacyTypeTracker(  872): Removing agent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{502}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.135/24,fe80::ee1f:72ff:fe18:8b78/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{true} created{true} explicitlySelected{false} }
D/CSLegacyTypeTracker(  872): Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 502] isDefaultNetwork=false
,D/ConnectivityService(  872): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  872): ValidatedState{ when=-2ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  872): DefaultState{ when=-2ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  872): Disconnected - quitting
D/TelephonyNetworkFactory( 1477): Cellular needs Network for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
I/WifiTrafficPoller(  872): evaluateTrafficStatsPolling
,D/WifiStateMachine(  872): updateConfiguredNetworkExpiration - currTime: 1452294294600
D/WifiStateMachine(  872): updateConfiguredNetworkExpiration - AP, "NG700", is not shared AP.
,D/EntConnectivity(  872): Not allowed due to - mEnabled false
E/WifiStateMachine(  872): SUPPLICANT_STATE_CHANGE_EVENT state=DISCONNECTED -> state= DISCONNECTED debouncing=false
E/WifiStateMachine(  872): setDetailed state, old =DISCONNECTED and new state=DISCONNECTED hidden=false
,I/CLocInfoService(  872): External Intent Received android.net.wifi.STATE_CHANGE
,E/WifiStateMachine(  872): Link configuration changed for netId: -1 old: {LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0} new: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0}
E/WifiStateMachine(  872): updateLinkProperties nid: -1 state: DISCONNECTED reason: CMD_UPDATE_LINKPROPERTIES
,I/Hs20UtilService( 1307): Starting #6
,D/StatusBar.NetworkController( 1168): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020498/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020133/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020464/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
,E/WifiStateMachine(  872): Link configuration changed for netId: -1 old: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576} new: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0}
D/ConnectivityService(  872): sendStickyBroadcastDelayed: delayMs=500, action=android.net.conn.CONNECTIVITY_CHANGE
E/WifiStateMachine(  872): updateLinkProperties nid: -1 state: DISCONNECTED reason: CMD_UPDATE_LINKPROPERTIES
,D/WifiNetworkAgent(  872): NetworkAgent: NetworkAgent channel lost
D/SmartBondingService(  872): SmartBondingReceiver: onReceive action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/SmartBondingService(  872): EVENT_UPDATE_SB_STATE called / mDisableBySIOP false
D/SmartBondingService(  872): getSBEnabled() enabled =false
D/SmartBondingService(  872): getSBEnabled() enabled =false
D/SmartBondingService(  872): getSBEnabled() enabled =false
,V/NetworkStats(  872): updateIfacesLocked()
D/NtpTrustedTime(  872): currentTimeMillis() cache hit
V/NetworkStats(  872): performPollLocked(flags=0x1)
,I/Hs20UtilService( 1307): Message received 5007
E/WifiStateMachine(  872): SUPPLICANT_STATE_CHANGE_EVENT state=SCANNING -> state= SCANNING debouncing=false
E/WifiStateMachine(  872): setDetailed state, old =DISCONNECTED and new state=SCANNING hidden=false
,D/NetworkStatsFactory(  872): UpdateStatsForKnox
E/WifiStateMachine(  872): setDetailed state send new extra info"NG700"
D/ConnectivityService(  872): returning getNetworkInfo(networkType - 28) :[type: MOBILE_ENT1[] - MOBILE_ENT1, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/ConnectivityService(  872): EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
,E/ConnectivityService(  872): EVENT_NETWORK_VALIDATED - isLiveNetworkAgent found mismatched netId: null - NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{502}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.135/24,fe80::ee1f:72ff:fe18:8b78/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{true} created{true} explicitlySelected{false} }
D/SmartBondingService(  872): getNetworkEnabled : wifi : true mobile : true
V/NetworkStats(  872): performPollLocked() took 7ms
D/NtpTrustedTime(  872): currentTimeMillis() cache hit
D/SecContentProvider2(  872): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2(  872): mCursor = null
D/StatusBar.NetworkController( 1168): getUpdateDataNetType(): 0
D/StatusBar.NetworkController( 1168): updateDataNetType()
D/StatusBar.NetworkController( 1168): NoService, mRoamingIconId = 0
,E/LightSensor(  872): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 3, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=1, bp1=1, cp1=3, cpl=3202560
D/AutomaticBrightnessController(  872): mCallbacks.updateBrightness()
D/DisplayPowerController(  872): getFinalBrightness : 8 -> 8
,D/NtpTrustedTime(  872): currentTimeMillis() cache hit
,D/NtpTrustedTime(  872): currentTimeMillis() cache hit
D/NtpTrustedTime(  872): currentTimeMillis() cache hit
,V/NetworkStats(  872): advisePersistThreshold() given 9223372036854775, clamped to 2097152
D/NtpTrustedTime(  872): currentTimeMillis() cache hit
,D/NearbySettings( 1307): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
V/NearbySettings( 1307): DMSUtil.isNetworkConnected - flag-null, state-null
,D/ConnectivityService(  872): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/StatusBar.NetworkController( 1168): updateDataIcon, mDataDirectionIconId = (null) mDataConnected = false
D/NtpTrustedTime(  872): currentTimeMillis() cache hit
D/NtpTrustedTime(  872): currentTimeMillis() cache hit
D/StatusBar.NetworkController( 1168): updateTelephonySignalStrength: hasService=false ss=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte
,D/StatusBar.NetworkController( 1168): updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal
D/StatusBar.NetworkController( 1168): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020498/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020133/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020464/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
,D/StatusBar.NetworkController( 1168): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1168): applyOpen
D/StatusBar.NetworkController( 1168): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1168): applyOpen
D/StatusBar.NetworkController( 1168): refreshSignalCluster - setNWBoosterIndicators(false)
D/SecContentProvider2(  872): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2(  872): mCursor = null
,D/StatusBar.NetworkController( 1168): applyOpen
D/StatusBar.NetworkController( 1168): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1168): applyOpen
,I/NearbySettings( 1307): DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,D/ConnectivityService(  872): returning getNetworkInfo(networkType - 13) :[type: WIFI_P2P[] - WIFI_P2P, state: UNKNOWN/IDLE, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/NearbySettings( 1307): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 1307): DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
I/NearbySettings( 1307): MountReceiver.onReceive - Set preference state off
V/NearbySettings( 1307): MountReceiver.mPrefHandler - 7002
,I/Hs20UtilService( 1307): Starting #7
I/Hs20UtilService( 1307): Message received 5007
,D/NearbySettings( 1307): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,V/NearbySettings( 1307): DMSUtil.isNetworkConnected - flag-null, state-null
D/ConnectivityService(  872): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/NearbySettings( 1307): DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,D/ConnectivityService(  872): returning getNetworkInfo(networkType - 13) :[type: WIFI_P2P[] - WIFI_P2P, state: UNKNOWN/IDLE, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/NearbySettings( 1307): DMSUtil.isNetworkConnected - P2P: IDLE
,I/NearbySettings( 1307): DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
I/NearbySettings( 1307): MountReceiver.onReceive - Set preference state off
V/NearbySettings( 1307): MountReceiver.mPrefHandler - 7002
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
,E/LightSensor(  872): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 3, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=1, bp1=1, cp1=3, cpl=3202560
,D/AutomaticBrightnessController(  872): mCallbacks.updateBrightness()
D/DisplayPowerController(  872): getFinalBrightness : 8 -> 8
,V/GLSActivity( 1676): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1676): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
,I/GLSUser ( 1676): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1676): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1676): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1676): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/Finsky  ( 6658): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,D/Finsky  ( 6658): [1] 5.onFinished: Installation state replication failed.
,D/Finsky  ( 6658): [1] 5.onFinished: Scheduling replication attempt 2.
,E/LightSensor(  872): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 3, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=1, bp1=1, cp1=3, cpl=3202560
D/AutomaticBrightnessController(  872): mCallbacks.updateBrightness()
D/DisplayPowerController(  872): getFinalBrightness : 8 -> 8
,D/ConnectivityService(  872): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,I/ApplicationPolicy(  872): updateDataUsageMap
,D/Tethering(  872): MasterInitialState.processMessage what=3
D/SmartBondingService(  872): SmartBondingReceiver: onReceive action=android.net.conn.CONNECTIVITY_CHANGE
,D/ConnectivityService(  872): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  872): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/SmartBondingService(  872): EVENT_UPDATE_SB_STATE called / mDisableBySIOP false
,D/SmartBondingService(  872): getSBEnabled() enabled =false
I/CLocInfoService(  872): External Intent Received android.net.conn.CONNECTIVITY_CHANGE
D/SmartBondingService(  872): getSBEnabled() enabled =false
D/SmartBondingService(  872): getSBEnabled() enabled =false
D/ConnectivityService(  872): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/CLocInfoService(  872): CLoinfo wifi false
,D/SmartBondingService(  872): getNetworkEnabled : wifi : true mobile : true
,D/ConnectivityService(  872): returning getNetworkInfo(networkType - 0) :[type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  872): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
W/SLocation(  872): No Active Data Connection
,I/PCWCLIENTTRACE_PushUtil( 6771): SPPPushClient is installed : true
,I/PCWCLIENTTRACE_PushUtil( 6771): sales region : global
I/PCWCLIENTTRACE_PushUtil( 6771): getPushTypeList : [SPP, GCM]
I/PCWCLIENTTRACE_SYSTEMReceiver( 6771): [onReceive] - android.net.conn.CONNECTIVITY_CHANGE
,I/PCWCLIENTTRACE_SYSTEMReceiver( 6771): noConnectivity : true
,D/ConnectivityService(  872): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  872): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  872): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
E/ActivityManager(  872): checkUser: useridlist=null, currentuser=0
E/LightSensor(  872): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 3, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=1, bp1=1, cp1=3, cpl=3202560
E/ActivityManager(  872): checkUser: useridlist=null, currentuser=0
D/AutomaticBrightnessController(  872): mCallbacks.updateBrightness()
E/ActivityManager(  872): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  872): checkUser: useridlist=null, currentuser=0
D/DisplayPowerController(  872): getFinalBrightness : 8 -> 8
D/accuweather( 2142): [KK AccuPhone]>>> SWW:66 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
E/Zygote  ( 7563): MountEmulatedStorage()
E/Zygote  ( 7563): v2
I/libpersona( 7563): KNOX_SDCARD checking this for 10126
I/libpersona( 7563): KNOX_SDCARD not a persona
I/ActivityManager(  872): Start proc com.google.android.music:main for broadcast com.google.android.music/.homewidgets.IFLWidgetProvider: pid=7563 uid=10126 gids={50126, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/DBG_DM  ( 3773): [com.wssyncmldm.XDMService(1111/IlIlllIIlIlIIIlIlIll)] WiFi network Connected : false
,I/SELinux ( 7563): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 7563): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,D/ConnectivityService(  872): returning getNetworkInfo(networkType - 7) :[type: BLUETOOTH[] - BLUETOOTH, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/SELinux ( 7563): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,I/DBG_DM  ( 3773): [com.wssyncmldm.XDMService(1125/lllllIlIlIIIIIIIIlIl)] Bluetooth Data Connected : false
,D/TimaKeyStoreProvider( 7563): TimaSignature is unavailable
,D/ActivityThread( 7563): Added TimaKeyStore provider
,D/ResourcesManager( 7563): creating new AssetManager and set to /system/app/Music2/Music2.apk
,E/LightSensor(  872): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 3, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=1, bp1=1, cp1=3, cpl=3202560
,D/AutomaticBrightnessController(  872): mCallbacks.updateBrightness()
D/DisplayPowerController(  872): getFinalBrightness : 8 -> 8
,E/SQLiteLog( 1676): (10) POSIX Error : 11 SQLite Error : 3850
,I/MusicStore( 7563): Database version: 104
,E/LightSensor(  872): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 3, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=1, bp1=1, cp1=3, cpl=3202560
,D/AutomaticBrightnessController(  872): mCallbacks.updateBrightness()
D/DisplayPowerController(  872): getFinalBrightness : 8 -> 8
,D/ResourcesManager( 7563): creating new AssetManager and set to /data/app/com.google.android.gms-1/base.apk
,W/ResourcesManager( 7563): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,W/ResourcesManager( 7563): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,V/JNIHelp ( 7563): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
,I/wpa_supplicant( 1252): nl80211: Received scan results (3 BSSes)
,I/wpa_supplicant( 1252): wlan0: Setting scan request: 8 sec 0 usec
I/wpa_supplicant( 1252): Trying to associate with C0.AA.48 (SSID='4E47373030' freq=2412 MHz)
I/wpa_supplicant( 1252): wlan0: State: SCANNING -> ASSOCIATING
I/wpa_supplicant( 1252): CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00.00.00 SSID=
,E/WifiStateMachine(  872): [1,452,294,295,636 ms] noteScanEnd no scan source
,E/WifiStateMachine(  872): wifi setScanResults statecom.android.server.wifi.WifiStateMachine$DisconnectedState@30dbedc0 sup_state=SCANNING debouncing=false
,I/CLocInfoService(  872): External Intent Received android.net.wifi.SCAN_RESULTS
,D/PowerManagerService(  872): [s] UserActivityState : 1 -> 2
,D/DisplayPowerController(  872): getFinalBrightness : 1 -> 1
D/PowerManagerService(  872): [s] DisplayPowerCallbacks : onStateChanged()
,E/WifiStateMachine(  872): SUPPLICANT_STATE_CHANGE_EVENT state=ASSOCIATING -> state= CONNECTING debouncing=false
,E/WifiStateMachine(  872): setDetailed state, old =SCANNING and new state=CONNECTING hidden=false
E/WifiStateMachine(  872): setDetailed state send new extra info0x
,D/SecContentProvider2(  872): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2(  872): mCursor = null
,W/ActivityThread( 7563): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,W/System  ( 7563): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@997c8fa: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 7563): Installed default security provider GmsCore_OpenSSL
D/AndroidMusic( 7563): GMSCore installation verified
,D/DisplayPowerController(  872): getFinalBrightness : 1 -> 1
,D/lights  (  872): lcd : 1 +
,D/lights  (  872): lcd : 1 -
,D/DisplayPowerController(  872): getFinalBrightness : 1 -> 1
,I/ConfigStore( 7563): Config Database version: 1
,E/LightSensor(  872): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 3, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=1, bp1=1, cp1=3, cpl=3202560
,D/AutomaticBrightnessController(  872): mCallbacks.updateBrightness()
D/DisplayPowerController(  872): getFinalBrightness : 1 -> 1
,E/Vold    (  248): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.music/files/
W/Vold    (  248): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7563): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.music/files
,I/wpa_supplicant( 1252): wlan0: State: ASSOCIATING -> ASSOCIATED
I/wpa_supplicant( 1252): CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00.00.00 SSID=4E47373030
,I/wpa_supplicant( 1252): Associated with C0.AA.48
,E/WifiStateMachine(  872): SUPPLICANT_STATE_CHANGE_EVENT state=ASSOCIATED -> state= CONNECTING debouncing=false
E/WifiStateMachine(  872): setDetailed state, old =CONNECTING and new state=CONNECTING hidden=false
,D/SecContentProvider2(  872): uri = 20 selection = getPromptCredentialsEnabled
,D/SecContentProvider2(  872): mCursor = null
,E/Vold    (  248): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.music/files/
W/Vold    (  248): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7563): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.music/files
,E/Vold    (  248): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.music/files/
W/Vold    (  248): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7563): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.music/files
,I/wpa_supplicant( 1252): wlan0: State: ASSOCIATED -> 4WAY_HANDSHAKE
I/wpa_supplicant( 1252): CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=C0.AA.48 SSID=4E47373030
,E/WifiStateMachine(  872): SUPPLICANT_STATE_CHANGE_EVENT state=FOUR_WAY_HANDSHAKE -> state= AUTHENTICATING debouncing=false
,E/WifiStateMachine(  872): setDetailed state, old =CONNECTING and new state=AUTHENTICATING hidden=false
E/WifiStateMachine(  872): setDetailed state send new extra info"NG700"
,D/SecContentProvider2(  872): uri = 20 selection = getPromptCredentialsEnabled
,D/SecContentProvider2(  872): mCursor = null
,I/wpa_supplicant( 1252): wlan0: State: 4WAY_HANDSHAKE -> 4WAY_HANDSHAKE
,D/WifiDisplayAdapter(  872): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,I/wpa_supplicant( 1252): wlan0: State: 4WAY_HANDSHAKE -> GROUP_HANDSHAKE
I/wpa_supplicant( 1252): CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=C0.AA.48 SSID=4E47373030
E/WifiStateMachine(  872): SUPPLICANT_STATE_CHANGE_EVENT state=GROUP_HANDSHAKE -> state= AUTHENTICATING debouncing=false
,E/WifiStateMachine(  872): setDetailed state, old =AUTHENTICATING and new state=AUTHENTICATING hidden=false
I/wpa_supplicant( 1252): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
I/wpa_supplicant( 1252): wlan0: State: GROUP_HANDSHAKE -> COMPLETED
I/wpa_supplicant( 1252): CTRL-EVENT-CONNECTED - Connection to C0.AA.48 completed (auth) [id=0 id_str=]
,I/wpa_supplicant( 1252): Blacklist: Clear (temp) 
I/wpa_supplicant( 1252): CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=C0.AA.48 SSID=4E47373030
,E/WifiStateMachine(  872): Network connection established
,D/WifiNative-HAL(  872): callSECApiVoid - ID [50]
,E/WifiStateMachine(  872): setDetailed state, old =AUTHENTICATING and new state=OBTAINING_IPADDR hidden=false
,E/WifiStateMachine(  872): setDetailed state, old =OBTAINING_IPADDR and new state=CONNECTING hidden=false
,D/ConnectivityService(  872): registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{false} explicitlySelected{false} }
,D/ConnectivityService(  872): Got NetworkAgent Messenger
D/ConnectivityService(  872): hsengiv:checkWhatTypeOfNetwork and the value is false
E/ConnectivityService(  872): updateNetworkInfo()
,D/ConnectivityService(  872): NetworkAgentInfo [WIFI () - 503] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
E/WifiStateMachine(  872): L2ConnectedState c0:ff:d4:d3:aa:48 config "NG700"WPA_PSK config.bssid any
E/WifiStateMachine(  872): L2ConnectedState "NG700" nid=0
D/WifiDisplayAdapter(  872): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
E/WifiConfigStore(  872): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
D/ConnectivityService(  872): NetworkAgent connected
,I/CLocInfoService(  872): External Intent Received android.net.wifi.STATE_CHANGE
,D/StatusBar.NetworkController( 1168): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020498/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020133/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020464/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
,V/AudioPolicyManager(  285): getOutputsForDevice device 0002 -> 0002
,I/AudioService(  872): getStreamVolume 3 index 70
,I/MediaRouter( 7563): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=7, volumeMax=15, presentationDisplayId=-1, extras=null, providerPackageName=android }
,E/WifiStateMachine(  872): enter ObtainingIpState netId=0 "NG700"WPA_PSK  roam=0 static=false watchdog= 1
E/WifiStateMachine(  872): ObtainingIpAddress c0:ff:d4:d3:aa:48 config "NG700"WPA_PSK config.bssid any
E/WifiStateMachine(  872): ObtainingIpAddress "NG700" nid=0
E/WifiConfigStore(  872): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,E/ActivityManager(  872): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  872): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  872): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  872): checkUser: useridlist=null, currentuser=0
,D/CommandListener(  272): Setting iface cfg
,E/WifiStateMachine(  872): Start Dhcp Watchdog 2
,D/SecContentProvider2(  872): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2(  872): mCursor = null
,E/Zygote  ( 7600): MountEmulatedStorage()
E/Zygote  ( 7600): v2
I/libpersona( 7600): KNOX_SDCARD checking this for 10002
I/libpersona( 7600): KNOX_SDCARD not a persona
,I/ActivityManager(  872): Start proc com.sec.android.cloudagent for broadcast com.sec.android.cloudagent/.detector.DetectorReceiver: pid=7600 uid=10002 gids={50002, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/WifiStateMachine(  872): CMD_RSSI_POLL : calculateWifiScore in!
,E/WifiStateMachine(  872): calculateWifiScore() report new score 60
I/WifiStateMachine(  872): calculateWifiScore : sendNetworkScore in!
I/WifiStateMachine(  872): calculateWifiScore : sendNetworkScore out!
I/WifiStateMachine(  872): CMD_RSSI_POLL : calculateWifiScore out!
I/WifiStateMachine(  872): CMD_RSSI_POLL : out!
,D/ConnectivityService(  872): updateNetworkScore for NetworkAgentInfo [WIFI () - 503] to 60
,E/WifiStateMachine(  872): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576} new: {InterfaceName: wlan0 LinkAddresses: []  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0}
,D/ConnectivityService(  872): Update of LinkProperties for NetworkAgentInfo [WIFI () - 503]; created=false
E/WifiStateMachine(  872): updateLinkProperties nid: 0 state: CONNECTING reason: CMD_UPDATE_LINKPROPERTIES
,I/SELinux ( 7600): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 7600): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 7600): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/WifiDisplayAdapter(  872): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,D/ConnectivityService(  872): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/NetworkMonitor( 7563): type=WIFI subType= reason=null isConnected=false
,D/TimaKeyStoreProvider( 7600): TimaSignature is unavailable
,D/ActivityThread( 7600): Added TimaKeyStore provider
,I/ActivityManager(  872): Killing 6751:com.samsung.groupcast/u0a16 (adj 15): bgCount ##41
,D/ResourcesManager( 7600): creating new AssetManager and set to /system/priv-app/CloudAgent/CloudAgent.apk
,E/LightSensor(  872): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  872): mCallbacks.updateBrightness()
D/DisplayPowerController(  872): getFinalBrightness : 1 -> 1
,E/WifiStateMachine(  872): setSuspendOptimizationsNative: 1 false -want true stack:setSuspendOptimizationsNative - handlePreDhcpSetup - processMessage - processMsg
E/native  (  872): do suspend false
,D/SecContentProvider2(  872): uri = 20 selection = getPromptCredentialsEnabled
D/WifiP2pService(  872): InactiveState{ what=143375 }
D/SecContentProvider2(  872): mCursor = null
D/WifiP2pService(  872): P2pEnabledState{ what=143375 }
,I/ActivityManager(  872): Killing 6532:com.samsung.android.app.galaxyfinder/u0a34 (adj 15): bgCount ##41
,E/ActivityManager(  872): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  872): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  872): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  872): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 7619): MountEmulatedStorage()
,E/Zygote  ( 7619): v2
I/libpersona( 7619): KNOX_SDCARD checking this for 1000
I/libpersona( 7619): KNOX_SDCARD not a persona
,I/ActivityManager(  872): Start proc com.sec.android.diagmonagent for broadcast com.sec.android.diagmonagent/.DiagMonRegistrationReceiver: pid=7619 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,I/SELinux ( 7619): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 7619): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 7619): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,W/libprocessgroup(  872): failed to open /acct/uid_10016/pid_6751/cgroup.procs: No such file or directory
,D/TimaKeyStoreProvider( 7619): TimaSignature is unavailable
,D/ActivityThread( 7619): Added TimaKeyStore provider
,D/ResourcesManager( 7619): creating new AssetManager and set to /system/priv-app/DiagMonAgent/DiagMonAgent.apk
,I/DIAGMON_AGENT( 7619): [com.sec.android.diagmonagent.DiagMonAgentApplication(41/onCreate)] myUserId : 0
,I/DIAGMON_AGENT( 7619): [com.diagmondm.db.file.XDB(374/llIlIIIIlIIIIIlIlIII)] 
,W/libprocessgroup(  872): failed to open /acct/uid_10034/pid_6532/cgroup.procs: No such file or directory
,E/LightSensor(  872): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  872): mCallbacks.updateBrightness()
D/DisplayPowerController(  872): getFinalBrightness : 1 -> 1
,E/SMD     (  279): DCD ON
,E/dhcpcd  ( 7634): fopen `/system/etc/dhcpcd/dhcpcd.conf': No such file or directory
,I/dhcpcd  ( 7634): version 5.5.6 starting
,E/dhcpcd  ( 7634): fopen `/system/etc/dhcpcd/dhcpcd.conf': No such file or directory
,I/DIAGMON_AGENT( 7619): [com.sec.android.diagmonagent.DiagMonAgentApplication(61/onCreate)] nStatus : 0
,I/DIAGMON_AGENT( 7619): [com.sec.android.diagmonagent.DiagMonAgentApplication(78/onCreate)] DiagMon DM Application Start !
,I/DIAGMON_AGENT( 7619): [lIIllllllllIlIlIllll(17/llIIIIlllllIIllIIllI)] Receive broadcast: android.net.conn.CONNECTIVITY_CHANGE
,I/DIAGMON_AGENT( 7619): [lIIllllllllIlIlIllll(31/llIIIIlllllIIllIIllI)] Running with RegistrationReceiver
,I/dhcpcd  ( 7634): wlan0: sending IPv6 Router Solicitation
E/dhcpcd  ( 7634): wlan0: sendmsg: Cannot assign requested address
I/dhcpcd  ( 7634): if(wlan0) info get Success. (MAC : C0.AA.48)
I/dhcpcd  ( 7634): bssid match
,I/dhcpcd  ( 7634): wlan0: rebinding lease of 192.168.1.135
,E/ActivityManager(  872): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  872): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  872): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  872): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 7642): MountEmulatedStorage()
E/Zygote  ( 7642): v2
I/libpersona( 7642): KNOX_SDCARD checking this for 10011
I/libpersona( 7642): KNOX_SDCARD not a persona
,I/ActivityManager(  872): Start proc com.sec.android.fotaclient for content provider com.sec.android.fotaclient/.log.MasterLogProvider: pid=7642 uid=10011 gids={50011, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,E/LightSensor(  872): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
D/AutomaticBrightnessController(  872): mCallbacks.updateBrightness()
D/DisplayPowerController(  872): getFinalBrightness : 1 -> 1
I/dhcpcd  ( 7634): wlan0: acknowledged 192.168.1.135 from 192.168.1.1
,I/SELinux ( 7642): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 7642): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 7642): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 7642): TimaSignature is unavailable
,D/ActivityThread( 7642): Added TimaKeyStore provider
,D/ResourcesManager( 7642): creating new AssetManager and set to /system/priv-app/FotaClient/FotaClient.apk
,I/dhcpcd  ( 7634): wlan0: leased 192.168.1.135 for 86400 seconds
,E/WifiStateMachine(  872): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: []  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576} new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.135/24,]  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0}
,E/WifiStateMachine(  872): updateLinkProperties nid: 0 state: CONNECTING reason: CMD_UPDATE_LINKPROPERTIES v4
,D/ConnectivityService(  872): Update of LinkProperties for NetworkAgentInfo [WIFI () - 503]; created=false
,V/AlarmManager(  872): waitForAlarm result :4
,E/LightSensor(  872): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
D/AutomaticBrightnessController(  872): mCallbacks.updateBrightness()
D/DisplayPowerController(  872): getFinalBrightness : 1 -> 1
,I/ActivityManager(  872): Killing 4673:com.sec.android.app.shealth/u0a35 (adj 15): bgCount ##41
,I/FOTA_Client( 7642): [com.sec.android.fotaclient.FotaRegisterReceiver(113/onReceive)] Already device registered...
,I/FOTA_Client( 7642): [com.sec.android.fotaclient.FotaUpdaterReceiver(103/onReceive)] Auto update settings is activated
,I/FOTA_Client( 7642): [lllllllllllIlllllIIl(197/lllIlIlIIIllIIlIllIl)] Polling time is vaild
,I/FOTA_Client( 7642): [com.sec.android.fotaclient.FotaUpdaterReceiver(126/onReceive)] Heartbeat settings is activated.
,I/FOTA_Client( 7642): [llIlIIIIlllIlllllIll(125/llIlIIIIlIIIIIlIlIII)] heartbeat time is vaild
,E/ActivityManager(  872): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  872): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  872): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  872): checkUser: useridlist=null, currentuser=0
,E/WifiStateMachine(  872): setSuspendOptimizationsNative: 1 true -want true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - processMessage - processMsg
,D/WifiP2pService(  872): InactiveState{ what=143375 }
,E/WifiStateMachine(  872): WifiStateMachine DHCP successful
D/WifiP2pService(  872): P2pEnabledState{ what=143375 }
,E/WifiStateMachine(  872): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: [192.168.1.135/24,]  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576} new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.135/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0}
,D/ConnectivityService(  872): Update of LinkProperties for NetworkAgentInfo [WIFI () - 503]; created=false
E/WifiStateMachine(  872): updateLinkProperties nid: 0 state: CONNECTING reason: DHCP_SUCCESS v4 v4r v4dns isprov
,E/Zygote  ( 7679): MountEmulatedStorage()
,E/Zygote  ( 7679): v2
I/libpersona( 7679): KNOX_SDCARD checking this for 10019
I/libpersona( 7679): KNOX_SDCARD not a persona
,I/ActivityManager(  872): Start proc com.samsung.klmsagent for broadcast com.samsung.klmsagent/.listner.MainReciver: pid=7679 uid=10019 gids={50019, 9997, 3003} abi=armeabi-v7a
,I/ActivityManager(  872): Killing 6787:com.policydm/1000 (adj 15): bgCount ##41
,E/WifiStateMachine(  872): WifiStateMachine: handleSuccessfulIpConfiguration and no scan results"NG700"WPA_PSK
,D/WifiStateMachine(  872): Not connected state, yet.
E/WifiStateMachine(  872): VerifyingLinkState enter
,I/SELinux ( 7679): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
D/WifiStateMachine(  872): updatePoorNetworkAvoidance - Poor Network Test Enabled / !mIsFmcNetwork : false / true - mPoorNetworkAvoidanceEnabled:disabled
D/StatusBar.NetworkController( 1168): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020498/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020133/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020464/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
D/WifiStateMachine(  872): updatePoorNetworkDetection - Airplane Mode Off / Mobile Data Enabled / SIM State-Ready / MobilePolicyDataDisabled / !mIsFmcNetwork : 
D/WifiStateMachine(  872): false / true / false / true / true - mPoorNetworkDetectionEnabled: disabled
D/WifiNative-HAL(  872): callSECApiInt - ID [210]
,I/SELinux ( 7679): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
W/libprocessgroup(  872): failed to open /acct/uid_10035/pid_4673/cgroup.procs: No such file or directory
,E/WifiStateMachine(  872): setDetailed state, old =CONNECTING and new state=VERIFYING_POOR_LINK hidden=false
E/SELinux ( 7679): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,E/ConnectivityService(  872): updateNetworkInfo()
,D/ConnectivityService(  872): updateLinkProperties: newLp = {InterfaceName: wlan0 LinkAddresses: [192.168.1.135/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}
D/ConnectivityService(  872): Adding iface wlan0 to network 503
,I/CLocInfoService(  872): External Intent Received android.net.wifi.STATE_CHANGE
,D/WifiWatchdogStateMachine(  872): updateDnsLinkProperty: enter
,D/WifiWatchdogStateMachine.DnsPinger(  872): setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.135/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}
D/WifiWatchdogStateMachine.DnsResolver(  872): setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.135/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}
,D/WifiWatchdogStateMachine.SingDnsChecker(  872): setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.135/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}
D/WifiWatchdogStateMachine.CaptivePortalDnsResolver(  872): setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.135/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}
,D/StatusBar.NetworkController( 1168): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020498/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020133/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020464/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
,E/WifiStateMachine(  872): VerifyingLinkState GOOD_LINK_DETECTED: transition to (new) connected (old)captive portal check
,E/LightSensor(  872): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
D/AutomaticBrightnessController(  872): mCallbacks.updateBrightness()
D/DisplayPowerController(  872): getFinalBrightness : 1 -> 1
,D/WifiStateMachine(  872): Now, connected state.
E/WifiStateMachine(  872): setDetailed state, old =VERIFYING_POOR_LINK and new state=CAPTIVE_PORTAL_CHECK hidden=false
,E/WifiStateMachine(  872): setDetailed state, old =CAPTIVE_PORTAL_CHECK and new state=CONNECTED hidden=false
,I/WifiTrafficPoller(  872): evaluateTrafficStatsPolling
,D/TimaKeyStoreProvider( 7679): TimaSignature is unavailable
,I/CLocInfoService(  872): External Intent Received android.net.wifi.STATE_CHANGE
D/ActivityThread( 7679): Added TimaKeyStore provider
,D/StatusBar.NetworkController( 1168): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020498/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020133/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020464/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
,E/WifiStateMachine(  872): Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,E/WifiStateMachine(  872): ConnectedState Enter  mScreenOn=true scanperiod=20000
D/ConnectivityService(  872): Adding Route [fe80::/64 -> :: wlan0] to network 503
,D/ConnectivityService(  872): Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 503
,W/libprocessgroup(  872): failed to open /acct/uid_1000/pid_6787/cgroup.procs: No such file or directory
I/WifiTrafficPoller(  872): evaluateTrafficStatsPolling
I/WifiTrafficPoller(  872): mBoosterFLAG : 0
,I/WifiTrafficPoller(  872): current booster mode : FullMode
D/ConnectivityService(  872): Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 503
,D/WifiNative-HAL(  872): callSECApiVoid - ID [212]
,D/StatusBar.NetworkController( 1168): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020498/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020133/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020464/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
E/ConnectivityService(  872): Unexpected mtu value: 0, wlan0
D/ConnectivityService(  872): updateSourceRoutes : add source routing for type : 1
D/ConnectivityService(  872): updateSourceRoutes : add src route for:192.168.1.135
,I/CLocInfoService(  872): External Intent Received android.net.wifi.STATE_CHANGE
,V/        (  272): QcRouteController
I/WifiStateMachine(  872): REQUEST_POWER_SAVE_ON
,D/StatusBar.NetworkController( 1168): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02012b/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020466/com.android.systemui:drawable/stat_sys_signal_inout mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
D/StatusBar.NetworkController( 1168): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1168): applyOpen
,D/StatusBar.NetworkController( 1168): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1168): applyOpen
D/StatusBar.NetworkController( 1168): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1168): applyOpen
D/StatusBar.NetworkController( 1168): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1168): applyOpen
,D/ResourcesManager( 7679): creating new AssetManager and set to /system/priv-app/KLMSAgent/KLMSAgent.apk
,V/        (  272): QcRouteController
,V/        (  272): QcRouteController
,I/KLMS-2.4.503: ( 7679): KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,I/KLMS-2.4.503: ( 7679): MainReciver(): EventNotificationReciver- method called: AppActivityListner onReceive for Intent Action : android.net.conn.CONNECTIVITY_CHANGE , timestamp: 1452294296656
,I/KLMS-2.4.503: ( 7679): MainReciver(): NETWORK_STATE_CHANGED_ACTION
,D/ConnectivityService(  872): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  872): returning getNetworkInfo(networkType - 0) :[type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/KLMS-2.4.503: ( 7679): KLMSUtility(): isNetworkAvailable() - WIFI : false| MOBILE : false
,I/KLMS-2.4.503: ( 7679): StateImplV2(): networkChangeListener().END
,I/ActivityManager(  872): Killing 5180:com.sec.spp.push/u0a38 (adj 15): bgCount ##41
,V/        (  272): QcRouteController
,E/ActivityManager(  872): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  872): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  872): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  872): checkUser: useridlist=null, currentuser=0
,V/        (  272): QcRouteController
,E/Zygote  ( 7706): MountEmulatedStorage()
E/Zygote  ( 7706): v2
I/libpersona( 7706): KNOX_SDCARD checking this for 10037
I/libpersona( 7706): KNOX_SDCARD not a persona
,I/ActivityManager(  872): Start proc com.sec.android.soagent for broadcast com.sec.android.soagent/.RegisterReceiver: pid=7706 uid=10037 gids={50037, 9997, 3003} abi=armeabi-v7a
,V/        (  272): QcRouteController
,V/        (  272): QcRouteController
,V/        (  272): QcRouteController
,I/SELinux ( 7706): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 7706): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 7706): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/ConnectivityService(  872): Setting Dns servers for network 503 to [/192.168.1.1]
,D/Nat464Xlat(  872): requiresClat: netType=1, connected=false, hasIPv4Address=true
D/ConnectivityService(  872): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 503]
E/ConnectivityService(  872): updateNetworkInfo()
D/ConnectivityService(  872): calling update connectivity
E/ConnectivityService(  872): updateNetworkInfo()
D/ConnectivityService(  872): ignoring duplicate network state non-change
D/ConnectivityService(  872): ignoring duplicate network state non-change
D/ConnectivityService(  872): NetworkAgentInfo [WIFI () - 503] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityService(  872): notifyType PRECHECK for NetworkAgentInfo [WIFI () - 503]
D/ConnectivityService(  872): calling update connectivity
D/ConnectivityService(  872): rematching NetworkAgentInfo [WIFI () - 503]
D/ConnectivityService(  872):  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityService(  872):   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  872):   checking if request is satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  872): currentScore = 0, newScore = 60
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  872): DefaultState{ when=0 what=532481 target=com.android.internal.util.StateMachine$SmHandler }
D/ConnectivityService(  872):    accepting network in place of null
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  872): Connected
D/ConnectivityService(  872): sending new Min Network Score(60): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  872): EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  872): Validated
,D/TelephonyNetworkFactory( 1477): Cellular releasing Network for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/CSLegacyTypeTracker(  872): Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 503] isDefaultNetwork=true
E/CSLegacyTypeTracker(  872): add() : Adding agent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{503}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.135/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{true} explicitlySelected{false} } for legacy network type 1
D/ConnectivityService(  872): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,D/ConnectivityService(  872): sendStickyBroadcastDelayed: delayMs=500, action=android.net.conn.CONNECTIVITY_CHANGE
,D/ConnectivityService(  872): Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{503}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.135/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{true} explicitlySelected{false} }
D/SmartBondingService(  872): SmartBondingReceiver: onReceive action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,D/SmartBondingService(  872): EVENT_UPDATE_SB_STATE called / mDisableBySIOP false
D/SmartBondingService(  872): getSBEnabled() enabled =false
D/SmartBondingService(  872): getSBEnabled() enabled =false
D/SmartBondingService(  872): getSBEnabled() enabled =false
D/ConnectivityService(  872): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 503]
D/ConnectivityService(  872): calling update connectivity
D/ConnectivityService(  872):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  872):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  872): sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  872): Validated NetworkAgentInfo [WIFI () - 503]
D/ConnectivityService(  872): rematching NetworkAgentInfo [WIFI () - 503]
D/ConnectivityService(  872):  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityService(  872):   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
D/SmartBondingService(  872): getNetworkEnabled : wifi : true mobile : true
D/ConnectivityService(  872): Network NetworkAgentInfo [WIFI () - 503] was already satisfying request 1. No change.
D/ConnectivityManager.CallbackHandler( 1168): CM callback handler got msg 524290
,D/ConnectivityService(  872): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 503]
D/ConnectivityService(  872): calling update connectivity
D/ConnectivityService(  872):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  872):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
,D/ConnectivityService(  872): sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
V/NetworkStats(  872): updateIfacesLocked()
D/NtpTrustedTime(  872): currentTimeMillis() cache hit
V/NetworkStats(  872): performPollLocked(flags=0x1)
,D/ConnectivityService(  872): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
D/ConnectivityService(  872): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityManager.CallbackHandler( 1168): CM callback handler got msg 524290
D/NetworkStatsFactory(  872): UpdateStatsForKnox
,D/StatusBar.NetworkController( 1168): getUpdateDataNetType(): 0
D/StatusBar.NetworkController( 1168): updateDataNetType()
D/StatusBar.NetworkController( 1168): NoService, mRoamingIconId = 0
,D/NtpTrustedTime(  872): currentTimeMillis() cache hit
,D/StatusBar.NetworkController( 1168): updateDataIcon, mDataDirectionIconId = (null) mDataConnected = false
D/StatusBar.NetworkController( 1168): updateTelephonySignalStrength: hasService=false ss=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte
D/StatusBar.NetworkController( 1168): updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal
,D/StatusBar.NetworkController( 1168): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02012b/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020466/com.android.systemui:drawable/stat_sys_signal_inout mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
D/StatusBar.NetworkController( 1168): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1168): applyOpen
D/StatusBar.NetworkController( 1168): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1168): applyOpen
D/StatusBar.NetworkController( 1168): refreshSignalCluster - setNWBoosterIndicators(false)
D/ConnectivityService(  872): returning getNetworkInfo(networkType - 28) :[type: MOBILE_ENT1[] - MOBILE_ENT1, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/StatusBar.NetworkController( 1168): applyOpen
D/StatusBar.NetworkController( 1168): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1168): applyOpen
D/NtpTrustedTime(  872): currentTimeMillis() cache hit
D/NtpTrustedTime(  872): currentTimeMillis() cache hit
,V/NetworkStats(  872): advisePersistThreshold() given 9223372036854775, clamped to 2097152
D/NtpTrustedTime(  872): currentTimeMillis() cache hit
,W/libprocessgroup(  872): failed to open /acct/uid_10038/pid_5180/cgroup.procs: No such file or directory
,D/ConnectivityService(  872): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/StatusBar.NetworkController( 1168): getUpdateDataNetType(): 0
D/StatusBar.NetworkController( 1168): updateDataNetType()
D/StatusBar.NetworkController( 1168): NoService, mRoamingIconId = 0
,D/StatusBar.NetworkController( 1168): updateDataIcon, mDataDirectionIconId = (null) mDataConnected = false
D/StatusBar.NetworkController( 1168): updateTelephonySignalStrength: hasService=false ss=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte
,D/StatusBar.NetworkController( 1168): updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal
D/StatusBar.NetworkController( 1168): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02012b/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020466/com.android.systemui:drawable/stat_sys_signal_inout mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
,V/NetworkStats(  872): performPollLocked() took 12ms
D/NtpTrustedTime(  872): currentTimeMillis() cache hit
,D/NtpTrustedTime(  872): currentTimeMillis() cache hit
D/NtpTrustedTime(  872): currentTimeMillis() cache hit
,D/TimaKeyStoreProvider( 7706): TimaSignature is unavailable
,D/ActivityThread( 7706): Added TimaKeyStore provider
,D/ResourcesManager( 7706): creating new AssetManager and set to /system/priv-app/SOAgent/SOAgent.apk
,E/LightSensor(  872): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  872): mCallbacks.updateBrightness()
D/DisplayPowerController(  872): getFinalBrightness : 1 -> 1
,I/SO_AGENT( 7706): [com.sec.android.soagent.RegisterReceiver(98/onReceive)] Network is not available
,E/ActivityManager(  872): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  872): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  872): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  872): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 7726): MountEmulatedStorage()
E/Zygote  ( 7726): v2
I/libpersona( 7726): KNOX_SDCARD checking this for 1000
I/libpersona( 7726): KNOX_SDCARD not a persona
,I/ActivityManager(  872): Start proc com.policydm for broadcast com.policydm/.XDMBroadcastReceiver: pid=7726 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,I/ActivityManager(  872): Killing 6043:com.samsung.android.sdk.samsunglink/u0a42 (adj 15): bgCount ##41
,I/SELinux ( 7726): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 7726): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 7726): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 7726): TimaSignature is unavailable
,D/ActivityThread( 7726): Added TimaKeyStore provider
,D/ResourcesManager( 7726): creating new AssetManager and set to /system/priv-app/SPDClient/SPDClient.apk
,W/libprocessgroup(  872): failed to open /acct/uid_10042/pid_6043/cgroup.procs: No such file or directory
,D/ConnectivityService(  872): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/ActivityManager(  872): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  872): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  872): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  872): checkUser: useridlist=null, currentuser=0
,D/BatteryService(  872): level:100, scale:100, status:5, health:2, present:true, voltage: 4248, temperature: 283, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  872): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
D/BatteryService(  872): Sending ACTION_BATTERY_CHANGED.
,E/Zygote  ( 7746): MountEmulatedStorage()
E/Zygote  ( 7746): v2
I/libpersona( 7746): KNOX_SDCARD checking this for 10038
,I/libpersona( 7746): KNOX_SDCARD not a persona
,I/ActivityManager(  872): Start proc com.sec.spp.push for broadcast com.sec.spp.push/.monitor.SystemStateMoniter: pid=7746 uid=10038 gids={50038, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  872): Killing 6807:com.osp.app.signin/u0a45 (adj 15): bgCount ##41
,D/MotionRecognitionService(  872):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
I/MotionRecognitionService(  872): Plugged
I/MotionRecognitionService(  872): setPowerConnected  = true
,E/LightSensor(  872): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  872): mCallbacks.updateBrightness()
D/DisplayPowerController(  872): getFinalBrightness : 1 -> 1
,I/SELinux ( 7746): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,D/KeyguardUpdateMonitor( 1168): received broadcast android.intent.action.BATTERY_CHANGED
I/SELinux ( 7746): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
E/SELinux ( 7746): [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
D/ConnectivityService(  872): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/STATUSBAR-PhoneStatusBar( 1168):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3234): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 3234): Disconnected process message: 10
,D/BatteryMeterView( 1168): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1168): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1168): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/KeyguardUpdateMonitor( 1168): handleBatteryUpdate
,D/TimaKeyStoreProvider( 7746): TimaSignature is unavailable
D/ActivityThread( 7746): Added TimaKeyStore provider
,D/ConnectivityService(  872): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ResourcesManager( 7746): creating new AssetManager and set to /system/priv-app/SPPPushClient_Prod/SPPPushClient_Prod.apk
,W/libprocessgroup(  872): failed to open /acct/uid_10045/pid_6807/cgroup.procs: No such file or directory
,E/SPPClientService( 7746): ============PushLog. commonIsShipBuild. stop!
,E/SPPClientService( 7746): [PushClientApplication] Push log off : This is Ship build version
,D/SPPClientService( 7746): PushLog.txt file is not deleted.
D/SPPClientService( 7746): PushLog.txt file is not deleted.
D/SPPClientService( 7746): ============PushLog. stop!
,E/SPPClientService( 7746): [[SystemStateMoniter]] SystemStateMonitorService : noConnect? : true
,E/ActivityManager(  872): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  872): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  872): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  872): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 7764): MountEmulatedStorage()
,E/Zygote  ( 7764): v2
I/libpersona( 7764): KNOX_SDCARD checking this for 10045
I/libpersona( 7764): KNOX_SDCARD not a persona
,I/ActivityManager(  872): Start proc com.osp.app.signin for broadcast com.osp.app.signin/.OspReceiver: pid=7764 uid=10045 gids={50045, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  872): Killing 6831:com.sec.android.app.myfiles/u0a51 (adj 15): bgCount ##41
I/art     (  307): Explicit concurrent mark sweep GC freed 8728(371KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 14MB/23MB, paused 276us total 10.869ms
,I/art     (  307): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 14MB/23MB, paused 249us total 8.023ms
,I/art     (  307): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 14MB/23MB, paused 248us total 7.919ms
,E/LightSensor(  872): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  872): mCallbacks.updateBrightness()
D/DisplayPowerController(  872): getFinalBrightness : 1 -> 1
,I/SELinux ( 7764): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
I/SELinux ( 7764): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 7764): [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
,E/SPPClientService( 7746): [[SystemStateMonitorService]] No Active Internet
,D/TimaKeyStoreProvider( 7764): TimaSignature is unavailable
,D/ActivityThread( 7764): Added TimaKeyStore provider
,D/ResourcesManager( 7764): creating new AssetManager and set to /system/priv-app/Samsungservice2_xxhdpi/Samsungservice2_xxhdpi.apk
,W/libprocessgroup(  872): failed to open /acct/uid_10051/pid_6831/cgroup.procs: No such file or directory
,I/SA      ( 7764): [SSP] onCreated
,I/SA      ( 7764): [TPM] There is no property file
,I/SA      ( 7764): [SCU] isHaveSA() - false
,I/SA      ( 7764): [TPM] getModelProperty : null
,I/SA      ( 7764): [TPM] getCSCProperty : null
,I/SA      ( 7764): [DM] init START
,I/SA      ( 7764): [DM] This device is not a Vodafone
,W/ResourceType( 7764): Failure getting entry for 0x7f06000f (t=5 e=15) (error -75)
,W/ResourceType( 7764): Failure getting entry for 0x7f060007 (t=5 e=7) (error -75)
W/ResourceType( 7764): Failure getting entry for 0x7f060008 (t=5 e=8) (error -75)
,W/ResourceType( 7764): Failure getting entry for 0x7f06000b (t=5 e=11) (error -75)
W/ResourceType( 7764): Failure getting entry for 0x7f06000c (t=5 e=12) (error -75)
W/ResourceType( 7764): Failure getting entry for 0x7f060001 (t=5 e=1) (error -75)
W/ResourceType( 7764): Failure getting entry for 0x7f060013 (t=5 e=19) (error -75)
W/ResourceType( 7764): No package identifier when getting value for resource number 0x00000000
,W/ResourceType( 7764): Failure getting entry for 0x7f060022 (t=5 e=34) (error -75)
D/ConnectivityService(  872): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
W/ResourceType( 7764): Failure getting entry for 0x7f060023 (t=5 e=35) (error -75)
W/ResourceType( 7764): Failure getting entry for 0x7f060024 (t=5 e=36) (error -75)
,W/ResourceType( 7764): Failure getting entry for 0x7f060025 (t=5 e=37) (error -75)
W/ResourceType( 7764): Failure getting entry for 0x7f060026 (t=5 e=38) (error -75)
,W/ResourceType( 7764): No package identifier when getting value for resource number 0x00000000
D/ConnectivityService(  872): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,W/ResourceType( 7764): Failure getting entry for 0x7f060010 (t=5 e=16) (error -75)
D/ConnectivityService(  872): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  872): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,W/ResourceType( 7764): Failure getting entry for 0x7f060009 (t=5 e=9) (error -75)
,D/Tethering(  872): MasterInitialState.processMessage what=3
W/ResourceType( 7764): Failure getting entry for 0x7f06000a (t=5 e=10) (error -75)
D/SmartBondingService(  872): SmartBondingReceiver: onReceive action=android.net.conn.CONNECTIVITY_CHANGE
D/SmartBondingService(  872): SmartBondingReceiver: wifi is connected
D/SmartBondingService(  872): SmartBondingReceiver: wifi ap is not changed
D/ConnectivityService(  872): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SmartBondingService(  872): EVENT_UPDATE_SB_STATE called / mDisableBySIOP false
W/ResourceType( 7764): Failure getting entry for 0x7f060002 (t=5 e=2) (error -75)
D/SmartBondingService(  872): getSBEnabled() enabled =false
D/SmartBondingService(  872): getSBEnabled() enabled =false
D/SmartBondingService(  872): getSBEnabled() enabled =false
I/CLocInfoService(  872): External Intent Received android.net.conn.CONNECTIVITY_CHANGE
,D/ConnectivityService(  872): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/CLocInfoService(  872): CLocinfo wifi true 
D/ConnectivityService(  872): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
W/ResourceType( 7764): Failure getting entry for 0x7f060014 (t=5 e=20) (error -75)
,W/ResourceType( 7764): Failure getting entry for 0x7f060015 (t=5 e=21) (error -75)
D/SmartBondingService(  872): getNetworkEnabled : wifi : true mobile : true
,D/ConnectivityService(  872): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  872): returning getNetworkInfo(networkType - 0) :[type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  872): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  872): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  872): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  872): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,W/ContextImpl( 2194): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1994 android.content.ContextWrapper.startService:533 com.samsung.SMT.SamsungTTSService.d:-1 com.samsung.SMT.SamsungTTSService.a:-1 com.samsung.SMT.ai.onReceive:-1 
,W/ContextImpl( 2194): Implicit intents with startService are not safe: Intent { act=com.samsung.SMT.UpdateManager.UPDATE_DATA } android.content.ContextWrapper.startService:533 com.samsung.SMT.SamsungTTSService.d:-1 com.samsung.SMT.SamsungTTSService.a:-1 
,D/accuweather( 2142): [KK AccuPhone]>>> SWW:66 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,D/ConnectivityService(  872): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/ConnectivityService(  872): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  872): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/NetworkMonitor( 7563): type=WIFI subType= reason=null isConnected=true
I/SA      ( 7764): [SCU] isHaveSA() - false
,D/ConnectivityService(  872): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/SA      ( 7764): support phone number id : false
D/ConnectivityService(  872): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  872): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/ConnectivityService(  872): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  872): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  872): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  872): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/ConnectivityService(  872): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/ConnectivityService(  872): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/SA      ( 7764): [DM] init END
,I/SA      ( 7764): [OR] onReceive log=[SA = 2.1.0142 V = 21 HWD = 1920X1080 3.0 dpi = 480  SIZE = 2 LOCALE = en_US CSC = DBT MCC = 0 MNC 0 T = user DEVICE = klte P = kltexx I = LRX21T M = SM-G900F OKLEFT false DIS LRX21T.G900FXXU1BOD3 PSS = 5.219788042639568  ]
,I/SA      ( 7764): [OR] onReceive Intent=[ conn.CONNECTIVITY_CHANGE. networkInfo:[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] networkType:1 inetCondition:0 extraInfo:? noConnectivity:true ]
I/SA      ( 7764): [OR] == ACTION_CONNECTIVITY_CHANGE ==
,I/SA      ( 7764): [SLFUCHKMGR] constructor called
,D/ConnectivityService(  872): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/DBG_DM  ( 3773): [lllllllIlllIIlllIlIl(88/llIIIIlllllIIllIIllI)] WiFi Network is connected
,I/DBG_DM  ( 3773): [com.wssyncmldm.XDMService(1111/IlIlllIIlIlIIIlIlIll)] WiFi network Connected : true
,D/ConnectivityService(  872): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  872): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  872): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/SA      ( 7764): [TPMU]  strSIMState 	:SIM_STATE_UNKNOWN
,I/SA      ( 7764): [OR] == isSIMCardReady false ==
,D/ConnectivityService(  872): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/SA      ( 7764): [SCU] == networkStateCheck == true
I/SA      ( 7764): [DM] getCountryCodeFromCSC : DE
I/SA      ( 7764): isChinaCountryCode : false
I/SA      ( 7764): [SCU] is ChinestModel Data Restricted   : false
I/SA      ( 7764): [OR] == networkStateCheck true ==
,I/SA      ( 7764): [OR] GetMyCountryZoneTask
,I/SA      ( 7764): [OR] onReceive END
,I/ActivityManager(  872): Killing 6848:com.sec.android.app.soundalive/u0a58 (adj 15): bgCount ##41
,D/ConnectivityService(  872): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SecContentProvider2(  872): uri = 11 selection = getMyKnoxAdmin
D/SecContentProvider2(  872): mCursor = null
,E/LightSensor(  872): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  872): mCallbacks.updateBrightness()
D/DisplayPowerController(  872): getFinalBrightness : 1 -> 1
,I/SA      ( 7764): [SRS] prepareGetMyCountryZone
,D/accuweather( 7286): [KK AccuPhone]>>> WC:30 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,D/accuweather( 7286): [KK AccuPhone]>>> WC:37 [0:0] oR : create UI manager : start
,D/accuweather( 7286): [KK AccuPhone]>>> UIMEM:90 [0:0] getInstance
D/accuweather( 7286): [KK AccuPhone]>>> UIMEM:78 [0:0] UIManager : create ui manager
,D/accuweather( 7286): [KK AccuPhone]>>> RM:73 [0:0] RefreshManager : create
D/accuweather( 7286): [KK AccuPhone]>>> RM:136 [0:0]  V init 
,I/SA      ( 7764): [TPMU]  strSIMState 	:SIM_STATE_UNKNOWN
,I/SA      ( 7764): [SSP] query invoked
,W/libprocessgroup(  872): failed to open /acct/uid_10058/pid_6848/cgroup.procs: No such file or directory
,I/art     (  872): Explicit concurrent mark sweep GC freed 68131(3MB) AllocSpace objects, 8(258KB) LOS objects, 30% free, 36MB/52MB, paused 1.364ms total 84.095ms
,D/daemonapp( 1335): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,I/SA      ( 7764): [TPMU] GetMccFromDB : null
I/SA      ( 7764): [SCU] getMccFromPreferece mcc = 260
,I/SA      ( 7764): [TPM] isNoProxy(default) : true
,D/accuweather( 7286): [KK AccuPhone]>>> RM:128 [0:0] updateCityList
,D/daemonapp( 1335): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/weatherinfo
,E/File    ( 7764): fail readDirectory() errno=2
,D/accuweather( 7286): [KK AccuPhone]>>> DBH:3354 [0:0] gADWI : count = 0
,D/daemonapp( 1335): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/accuweather( 7286): [KK AccuPhone]>>> UIMEM:106 [0:0] The widget does not exist in idle!!
,D/accuweather( 7286): [KK AccuPhone]>>> UIMEM:106 [0:0] The widget does not exist in idle!!
,E/ActivityManager(  872): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  872): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  872): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  872): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 7792): MountEmulatedStorage()
,E/Zygote  ( 7792): v2
I/libpersona( 7792): KNOX_SDCARD checking this for 1000
I/libpersona( 7792): KNOX_SDCARD not a persona
,I/ActivityManager(  872): Start proc com.sec.knox.bridge for broadcast com.sec.knox.bridge/.knoxusage.KnoxUsageReceiver: pid=7792 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,E/LightSensor(  872): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  872): mCallbacks.updateBrightness()
D/DisplayPowerController(  872): getFinalBrightness : 1 -> 1
,I/SELinux ( 7792): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
I/SELinux ( 7792): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
E/SELinux ( 7792): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 7792): TimaSignature is unavailable
,D/ActivityThread( 7792): Added TimaKeyStore provider
,D/ResourcesManager( 7792): creating new AssetManager and set to /system/app/Bridge/Bridge.apk
,W/ResourcesManager( 7792): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,I/KnoxUsageLogPro( 7792): KnoxUsageReceiver onReceive :android.net.conn.CONNECTIVITY_CHANGE myUserId=0
,I/KnoxUsageLogPro( 7792): premStatus:2
,I/KnoxUsageLogPro( 7792): isEulaShown : false
I/KnoxUsageLogPro( 7792): KnoxUsageReceiver onReceive : not Processible, just return
,E/ActivityManager(  872): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  872): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  872): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  872): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 7807): MountEmulatedStorage()
I/libpersona( 7807): KNOX_SDCARD checking this for 10088
E/Zygote  ( 7807): v2
I/libpersona( 7807): KNOX_SDCARD not a persona
,I/ActivityManager(  872): Start proc com.android.chrome for broadcast com.android.chrome/com.google.android.apps.chrome.precache.PrecacheServiceLauncher: pid=7807 uid=10088 gids={50088, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  872): Killing 6242:com.samsung.android.app.assistantmenu/1000 (adj 15): bgCount ##41
,I/SELinux ( 7807): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,D/StatusBar.NetworkController( 1168): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02012b/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020464/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
D/StatusBar.NetworkController( 1168): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1168): applyOpen
,D/StatusBar.NetworkController( 1168): refreshSignalCluster - setNWBoosterIndicators(false)
I/SELinux ( 7807): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,D/StatusBar.NetworkController( 1168): applyOpen
D/StatusBar.NetworkController( 1168): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1168): applyOpen
E/SELinux ( 7807): [DEBUG] get_category: variable seinfo: chrome sensitivity: NULL, cateogry: NULL
D/StatusBar.NetworkController( 1168): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1168): applyOpen
,E/LightSensor(  872): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  872): mCallbacks.updateBrightness()
D/DisplayPowerController(  872): getFinalBrightness : 1 -> 1
,D/TimaKeyStoreProvider( 7807): TimaSignature is unavailable
,D/ActivityThread( 7807): Added TimaKeyStore provider
,D/ResourcesManager( 7807): creating new AssetManager and set to /system/app/Chrome/Chrome.apk
,W/libprocessgroup(  872): failed to open /acct/uid_1000/pid_6242/cgroup.procs: No such file or directory
,D/ConnectivityService(  872): NetTransition Wakelock (NetworkAgentInfo [WIFI () - 502] cleared because we found a replacement network
,I/ActivityManager(  872): Killing 6874:com.google.android.apps.docs/u0a98 (adj 15): bgCount ##41
,D/Headlines( 5480): HeadlinesSystemBroadcastReceiver onReceive android.net.conn.CONNECTIVITY_CHANGE
,D/HeadlinesChannelUtil( 5480): getCountryCode(): countryCode = DE
,E/ActivityManager(  872): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  872): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  872): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  872): checkUser: useridlist=null, currentuser=0
,D/Headlines( 5480): Breath.onStartCommand : com.samsung.android.internal.headlines.UPDATE_WELCOME_CARD flag : 0
D/HeadlinesCardManager( 5480): updateCategory : HeadlinesCardManager:updateCategory() category size == 0
D/HeadlinesCardManager( 5480): updateCategory : HeadlinesCardManager:updateCategory() try to query category list
D/Headlines( 5480): queryCategory.  mRequest is not initialized.
D/HeadlinesCardManager( 5480): updateCategory : HeadlinesCardManager:updateCategory() reponse : false
D/HeadlinesCardManager( 5480): requestUpdateNewsWelcomeCard : request update welcome card to content card.
,D/HeadlinesDataCenter( 5480): requestUpdateNewsWelcomeCard !!! no welcome card
,E/Zygote  ( 7823): MountEmulatedStorage()
I/libpersona( 7823): KNOX_SDCARD checking this for 10128
E/Zygote  ( 7823): v2
I/libpersona( 7823): KNOX_SDCARD not a persona
,I/ActivityManager(  872): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=7823 uid=10128 gids={50128, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,E/LightSensor(  872): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  872): mCallbacks.updateBrightness()
D/DisplayPowerController(  872): getFinalBrightness : 1 -> 1
,I/SELinux ( 7823): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 7823): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 7823): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 7823): TimaSignature is unavailable
,D/ActivityThread( 7823): Added TimaKeyStore provider
,D/ResourcesManager( 7823): creating new AssetManager and set to /system/app/Newsstand/Newsstand.apk
,I/SA      ( 7764): [RC New] Execute method=[GET] start
,W/libprocessgroup(  872): failed to open /acct/uid_10098/pid_6874/cgroup.procs: No such file or directory
,I/SA      ( 7764): [RC New] Security=[true]
,I/System.out( 7764): Thread-1275(ApacheHTTPLog):Reading from variable values from setDefaultValuesToVariables
,I/System.out( 7764): Thread-1275(ApacheHTTPLog):isShipBuild true
,I/System.out( 7764): Thread-1275(ApacheHTTPLog):SmartBonding Enabling is true, SHIP_BUILD is true, log to file is false, DBG is false
,E/LightSensor(  872): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  872): mCallbacks.updateBrightness()
D/DisplayPowerController(  872): getFinalBrightness : 1 -> 1
,E/Vold    (  248): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  248): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7823): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache
,E/Vold    (  248): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  248): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7823): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/files
,E/Vold    (  248): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  248): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7823): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache
,E/Vold    (  248): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  248): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7823): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/files
,D/ConnectivityService(  872): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/WebViewFactory( 7823): Loading com.google.android.webview version 37 (1726107-arm) (code 119201)
,D/ResourcesManager( 7823): creating new AssetManager and set to /system/app/WebViewGoogle/WebViewGoogle.apk
,I/LibraryLoader( 7823): Loading: webviewchromium
,I/LibraryLoader( 7823): Time to load native libraries: 4 ms (timestamps 2640-2644)
I/LibraryLoader( 7823): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 7823): Binding Chromium to main looper Looper (main, tid 1) {274c771c}
,I/LibraryLoader( 7823): Expected native library version number "",actual native library version number ""
,I/chromium( 7823): [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 7823): Initializing chromium process, renderers=0
,W/art     ( 7823): Attempt to remove local handle scope entry from IRT, ignoring
,W/chromium( 7823): [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
,W/AudioManagerAndroid( 7823): Requires BLUETOOTH permission
I/chromium( 7823): [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=41 off=46768 len=2953
,I/chromium( 7823): [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:42 off:229524 len:643667
,I/Adreno-EGL( 7823): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 7823): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 7823): Build Date: 03/03/15 Tue
I/Adreno-EGL( 7823): Local Branch: LA.BF.1.1_RB1_20150108_025_1077123_1158499
I/Adreno-EGL( 7823): Remote Branch: 
I/Adreno-EGL( 7823): Local Patches: 
I/Adreno-EGL( 7823): Reconstruct Branch: 
,E/LightSensor(  872): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  872): mCallbacks.updateBrightness()
D/DisplayPowerController(  872): getFinalBrightness : 1 -> 1
,I/NSApplication( 7823): Starting up...
,D/ConnectivityService(  872): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  872): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  872): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  872): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/ActivityManager(  872): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  872): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  872): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  872): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 7881): MountEmulatedStorage()
,E/Zygote  ( 7881): v2
I/libpersona( 7881): KNOX_SDCARD checking this for 10138
I/libpersona( 7881): KNOX_SDCARD not a persona
,I/ActivityManager(  872): Start proc com.samsung.android.sconnect for broadcast com.samsung.android.sconnect/.periph.PeriphStartReceiver: pid=7881 uid=10138 gids={50138, 9997, 3002, 3001, 1028, 1015, 3003} abi=armeabi-v7a
,I/ActivityManager(  872): Killing 6930:com.vlingo.midas/u0a33 (adj 15): bgCount ##41
,I/SELinux ( 7881): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
I/SELinux ( 7881): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
E/SELinux ( 7881): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 7881): TimaSignature is unavailable
,D/ActivityThread( 7881): Added TimaKeyStore provider
,D/ResourcesManager( 7881): creating new AssetManager and set to /system/app/QuickConnect/QuickConnect.apk
,W/ResourcesManager( 7881): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,W/ResourcesManager( 7881): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
W/ResourcesManager( 7881): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,E/LightSensor(  872): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  872): mCallbacks.updateBrightness()
D/DisplayPowerController(  872): getFinalBrightness : 1 -> 1
,W/libprocessgroup(  872): failed to open /acct/uid_10033/pid_6930/cgroup.procs: No such file or directory
,D/QuickConnect( 7881): PeriphStartReceiver.onReceive - android.net.conn.CONNECTIVITY_CHANGE
,I/QuickConnect( 7881): PeriphStartReceiver.onReceive - USER_OWNER care CONNECTIVITY_ACTION. run P service
,I/QuickConnect( 7881): PeriphStartReceiver.onReceive - no need to start
,E/ActivityManager(  872): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  872): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  872): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  872): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 7896): MountEmulatedStorage()
,E/Zygote  ( 7896): v2
I/libpersona( 7896): KNOX_SDCARD checking this for 10163
I/libpersona( 7896): KNOX_SDCARD not a persona
,I/ActivityManager(  872): Start proc com.android.email for broadcast com.android.email/.EmailConnectivityManager: pid=7896 uid=10163 gids={50163, 9997, 3003, 1028, 1015, 1023, 3002, 3001, 1003} abi=armeabi-v7a
,I/ActivityManager(  872): Killing 6906:com.sec.android.automotive.drivelink/u0a99 (adj 15): bgCount ##41
,I/SELinux ( 7896): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
I/SELinux ( 7896): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
E/SELinux ( 7896): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 7896): TimaSignature is unavailable
,D/ActivityThread( 7896): Added TimaKeyStore provider
,D/ResourcesManager( 7896): creating new AssetManager and set to /system/app/SecEmail_K/SecEmail_K.apk
,W/ResourcesManager( 7896): Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
,W/ResourcesManager( 7896): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 7896): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
,W/ResourcesManager( 7896): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,W/libprocessgroup(  872): failed to open /acct/uid_10099/pid_6906/cgroup.procs: No such file or directory
,D/RCPManagerService(  872): exchangeData() failure , invalid userId
,D/RCPManagerService(  872): exchangeData() failure , invalid userId
,E/LightSensor(  872): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  872): mCallbacks.updateBrightness()
D/DisplayPowerController(  872): getFinalBrightness : 1 -> 1
D/RCPManagerService(  872): exchangeData() failure , invalid userId
,E/ActivityManager(  872): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  872): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  872): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  872): checkUser: useridlist=null, currentuser=0
,D/RCPManagerService(  872): exchangeData() failure , invalid userId
,E/Zygote  ( 7919): MountEmulatedStorage()
E/Zygote  ( 7919): v2
I/libpersona( 7919): KNOX_SDCARD checking this for 10078
I/libpersona( 7919): KNOX_SDCARD not a persona
,V/BitmapFactory( 7896): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_015.png
,I/ActivityManager(  872): Start proc com.sec.android.provider.badge for content provider com.sec.android.provider.badge/.BadgeProvider: pid=7919 uid=10078 gids={50078, 9997} abi=armeabi-v7a
,I/SELinux ( 7919): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 7919): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,D/StatusBar.NetworkController( 1168): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02012b/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020466/com.android.systemui:drawable/stat_sys_signal_inout mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
D/StatusBar.NetworkController( 1168): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1168): applyOpen
,D/StatusBar.NetworkController( 1168): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1168): applyOpen
D/StatusBar.NetworkController( 1168): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1168): applyOpen
D/StatusBar.NetworkController( 1168): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1168): applyOpen
,E/SELinux ( 7919): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
D/ConnectivityService(  872): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  872): returning getNetworkInfo(networkType - 0) :[type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/RCPManagerService(  872): exchangeData() failure , invalid userId
,D/RCPManagerService(  872): exchangeData() failure , invalid userId
,V/BitmapFactory( 7896): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_000.png
,V/BitmapFactory( 7896): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_015.png
,D/TimaKeyStoreProvider( 7919): TimaSignature is unavailable
,D/ActivityThread( 7919): Added TimaKeyStore provider
,I/ActivityManager(  872): Killing 6968:com.sec.android.provider.logsprovider/u0a20 (adj 15): bgCount ##41
,V/BitmapFactory( 7896): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_000.png
,V/BitmapFactory( 7896): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_000.png
,V/BitmapFactory( 7896): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_001.png
,D/ConnectivityService(  872): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SecurityLogAgent( 7500): KnoxConfiguration : Current State = 1
,D/SecurityLogAgent( 7500): KnoxConfiguration : Current State Mapping Found 
D/SecurityLogAgent( 7500): StateMachine : Current State = 1
,D/ConnectivityService(  872): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,V/BitmapFactory( 7896): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_002.png
,D/SecurityLogAgent( 7500): StateMachine : Changed Current State = 1
,I/ActivityManager(  872): Killing 6982:com.samsung.android.intelligenceservice/u0a3 (adj 15): bgCount ##41
,D/com.peel.receiver.ConnectivityActionReceiver( 5585): ConnectivityActionReceiver onReceive
D/com.peel.receiver.ConnectivityActionReceiver( 5585): 
D/com.peel.receiver.ConnectivityActionReceiver( 5585): 
D/com.peel.receiver.ConnectivityActionReceiver( 5585): country_code: Germany -- rom region: GB
D/com.peel.receiver.ConnectivityActionReceiver( 5585): 
,D/ConnectivityService(  872): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/com.peel.receiver.ConnectivityActionReceiver( 5585): 
D/com.peel.receiver.ConnectivityActionReceiver( 5585): 
D/com.peel.receiver.ConnectivityActionReceiver( 5585):  network type WIFI path... network offline: false
D/com.peel.receiver.ConnectivityActionReceiver( 5585): 
D/com.peel.receiver.ConnectivityActionReceiver( 5585): has active network... run services...
D/ConnectivityService(  872): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/com.peel.receiver.ConnectivityActionReceiver( 5585): 
D/com.peel.receiver.ConnectivityActionReceiver( 5585): 
D/com.peel.receiver.ConnectivityActionReceiver( 5585): last run: 1452283589907 -- System.currentTimeMillis()-last_run: 10708816
D/com.peel.receiver.ConnectivityActionReceiver( 5585): ... skip 
D/com.peel.receiver.ConnectivityActionReceiver( 5585): ... skip last_72_check
,E/ActivityManager(  872): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  872): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  872): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  872): checkUser: useridlist=null, currentuser=0
,V/BitmapFactory( 7896): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_003.png
,E/Zygote  ( 7935): MountEmulatedStorage()
I/libpersona( 7935): KNOX_SDCARD checking this for 10178
E/Zygote  ( 7935): v2
I/libpersona( 7935): KNOX_SDCARD not a persona
,I/ActivityManager(  872): Start proc com.samsung.android.service.travel for broadcast com.samsung.android.service.travel/com.samsung.android.travel.bindService.TravelBroadcastReceiver: pid=7935 uid=10178 gids={50178, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/SA      ( 7764): [RC New] [v2liruge] api execute + 751
,V/BitmapFactory( 7896): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_004.png
,I/SA      ( 7764): [RC New] executeRequest [v2liruge] httpResponse : HTTP/1.1 200 OK
I/System.out( 7764): AsyncTask #1 calls detatch()
,I/SA      ( 7764): [ODM] saveOpenData( GEO_IP, PL )
,V/BitmapFactory( 7896): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_005.png
,V/BitmapFactory( 7896): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_006.png
,V/BitmapFactory( 7896): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_007.png
,V/BitmapFactory( 7896): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_008.png
,V/BitmapFactory( 7896): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_010.png
,V/BitmapFactory( 7896): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_011.png
,V/BitmapFactory( 7896): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_012.png
,V/BitmapFactory( 7896): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_013.png
,V/BitmapFactory( 7896): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_014.png
,V/BitmapFactory( 7896): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_015.png
,E/LightSensor(  872): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
D/AutomaticBrightnessController(  872): mCallbacks.updateBrightness()
D/DisplayPowerController(  872): getFinalBrightness : 1 -> 1
,V/BitmapFactory( 7896): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_000.png
,V/BitmapFactory( 7896): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_001.png
,V/BitmapFactory( 7896): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_002.png
,V/BitmapFactory( 7896): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_003.png
,V/BitmapFactory( 7896): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_004.png
,V/BitmapFactory( 7896): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_005.png
,V/BitmapFactory( 7896): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_006.png
,V/BitmapFactory( 7896): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_007.png
,V/BitmapFactory( 7896): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_008.png
,V/BitmapFactory( 7896): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_010.png
,V/BitmapFactory( 7896): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_011.png
,V/BitmapFactory( 7896): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_012.png
,V/BitmapFactory( 7896): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_013.png
,V/BitmapFactory( 7896): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_014.png
,V/BitmapFactory( 7896): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_015.png
,V/BitmapFactory( 7896): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/delete_glance_line.pkm
,V/BitmapFactory( 7896): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/delete_glance_icon_undo.pkm
,V/BitmapFactory( 7896): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/list_icon_calendar_1.pkm
,V/BitmapFactory( 7896): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/email_attach_icon_etc.pkm
,V/BitmapFactory( 7896): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/list_icon_flag.pkm
V/BitmapFactory( 7896): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/list_icon_complate.pkm
,V/BitmapFactory( 7896): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/list_icon_flag_off_white.pkm
,V/BitmapFactory( 7896): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/email_list_attach_icon_star_off.pkm
V/BitmapFactory( 7896): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/email_list_attach_icon_star_on.pkm
,V/BitmapFactory( 7896): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/list_icon_flag_f.pkm
,V/BitmapFactory( 7896): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/list_icon_complate_f.pkm
V/BitmapFactory( 7896): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/list_icon_flag_off_f.pkm
,V/BitmapFactory( 7896): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/email_icon_foward.pkm
,V/BitmapFactory( 7896): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/email_icon_foward_focus.pkm
V/BitmapFactory( 7896): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/list_icon_reply_forward.pkm
,V/BitmapFactory( 7896): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/email_icon_reply.pkm
V/BitmapFactory( 7896): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/email_icon_reply_focus.pkm
,V/BitmapFactory( 7896): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/list_icon_vip.pkm
,V/BitmapFactory( 7896): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/email_list_high_priority.pkm
V/BitmapFactory( 7896): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/email_list_low_priority.pkm
,V/BitmapFactory( 7896): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/list_icon_server_draft.pkm
,V/BitmapFactory( 7896): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/list_icon_client_draft.pkm
V/BitmapFactory( 7896): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/permission.pkm
,V/BitmapFactory( 7896): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/list_icon_voicemail.pkm
,V/BitmapFactory( 7896): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/list_icon_sms.pkm
V/BitmapFactory( 7896): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/list_icon_sign.pkm
V/BitmapFactory( 7896): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/list_icon_encryption.pkm
,I/SELinux ( 7935): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
I/SELinux ( 7935): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
E/SELinux ( 7935): [DEBUG] get_category: variable seinfo: shared sensitivity: NULL, cateogry: NULL
,D/ResourcesManager( 7919): creating new AssetManager and set to /system/app/BadgeProvider/BadgeProvider.apk
,V/BitmapFactory( 7896): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/tw_expander_open_01_holo_light.pkm
,V/BitmapFactory( 7896): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/tw_expander_close_01_holo_light.pkm
,I/SA      ( 7764): [OCP] update openData : PL
,I/WifiStateMachine(  872): CMD_RSSI_POLL : calculateWifiScore in!
,I/WifiStateMachine(  872): CMD_RSSI_POLL : calculateWifiScore out!
I/WifiStateMachine(  872): CMD_RSSI_POLL : out!
,I/SA      ( 7764): [TPMU] getNetworkMcc : 
,I/SA      ( 7764): [SCU] saveMccToPreferece Start
I/SA      ( 7764): [SCU] RegionMCC : 260
,I/SA      ( 7764): [SSP] query invoked
,D/StatusBar.NetworkController( 1168): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02012b/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020466/com.android.systemui:drawable/stat_sys_signal_inout mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
,D/TimaKeyStoreProvider( 7935): TimaSignature is unavailable
,D/ActivityThread( 7935): Added TimaKeyStore provider
,I/SA      ( 7764): [TPMU] GetMccFromDB : null
I/SA      ( 7764): [SCU] getMccFromPreferece mcc = 260
I/SA      ( 7764): [SCU] saveMccToPreferece End
,I/SA      ( 7764): [RC New] executeRequest [v2liruge] end. 882
I/SA      ( 7764): [RC New] Execute end
,I/SA      ( 7764): [OR] GetMyCountryZoneTask mcc = 260
I/SA      ( 7764): [OR] GetMyCountryZoneTask Success
,W/libprocessgroup(  872): failed to open /acct/uid_10020/pid_6968/cgroup.procs: No such file or directory
W/libprocessgroup(  872): failed to open /acct/uid_10003/pid_6982/cgroup.procs: No such file or directory
,D/BadgeProvider( 7919): onCreate
D/BadgeProvider( 7919): DatabaseHelper
,D/ResourcesManager( 7935): creating new AssetManager and set to /system/app/TravelService_K/TravelService_K.apk
,D/BadgeProvider( 7919): query, [selection] : package='com.android.email' AND class='com.android.email.activity.Welcome' AND extraData='base_extra_badge'
,I/ActivityManager(  872): Killing 6998:com.samsung.android.app.filterinstaller/1000 (adj 15): bgCount ##41
,D/ConnectivityService(  872): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/BadgeProvider( 7919): sendNotify entered. [uri] : content://com.sec.badge/apps/1
D/BadgeProvider( 7919): sendNotify, [notify] : null
D/BadgeProvider( 7919): update, [uri] : content://com.sec.badge/apps/1
D/BadgeProvider( 7919): update, [BadgeCount] : badgecount=0
D/BadgeProvider( 7919): update, [UpdateCount] : 1
,D/Launcher.Model( 1489): reloadBadges entered.
,D/ConnectivityService(  872): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  872): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  872): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  872): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ChimeraCfgMgr( 2462): Loading module com.google.android.gms.kids from APK com.google.android.gms
,D/ConnectivityService(  872): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  872): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ChimeraCfgMgr( 2462): Loading module com.google.android.gms.kids from APK com.google.android.gms
,W/libprocessgroup(  872): failed to open /acct/uid_1000/pid_6998/cgroup.procs: No such file or directory
,D/ConnectivityService(  872): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/WaitQueueForNetworkActivate( 7121): notifyNetworkActivated
,D/ConnectivityService(  872): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/LightSensor(  872): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  872): mCallbacks.updateBrightness()
D/DisplayPowerController(  872): getFinalBrightness : 1 -> 1
,W/ContextImpl( 7121): Implicit intents with startService are not safe: Intent { act=com.sec.knox.containeragent.service.containermanager.ContainerManagerService } android.content.ContextWrapper.bindService:559 com.sec.knox.containeragent.ContainerManager.<init>:49 com.sec.android.app.samsungapps.vlibrary2.knoxmode.KNOXAPI.<init>:20 
,W/ActivityManager(  872): Unable to start service Intent { act=com.sec.knox.containeragent.service.containermanager.ContainerManagerService } U=0: not found
,W/ActivityManager(  872): Unable to start service Intent { cmp=com.android.email/.service.AttachmentDownloadService } U=0: not found
,I/GLSUser ( 1676): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: ac2dm
,I/GLSUser ( 1676): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> ac2dm without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1676): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1676): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1676): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/BitmapFactory( 1676): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/common_ic_googleplayservices.png
,V/BitmapFactory( 1676): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  872): uri = 14 selection = getSealedState
D/SecContentProvider2(  872): mCursor = null
,D/SecContentProvider2(  872): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  872): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
V/ApplicationPolicy(  872): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/StatusBar( 1168): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,W/Kids    ( 2462): [AccountUtils] Account not ready
W/Kids    ( 2462): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/Kids    ( 2462): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/Kids    ( 2462): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/Kids    ( 2462): 	at com.google.android.gms.auth.p.c(SourceFile:550)
W/Kids    ( 2462): 	at com.google.android.gms.auth.p.b(SourceFile:477)
W/Kids    ( 2462): 	at com.google.android.gms.kids.account.k.d(SourceFile:103)
W/Kids    ( 2462): 	at com.google.android.gms.kids.account.p.a(SourceFile:70)
W/Kids    ( 2462): 	at com.google.android.gms.kids.account.t.a(SourceFile:62)
W/Kids    ( 2462): 	at com.google.android.gms.chimera.f.run(SourceFile:179)
W/Kids    ( 2462): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
W/Kids    ( 2462): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
W/Kids    ( 2462): 	at java.lang.Thread.run(Thread.java:818)
,I/PhoneStatusBar( 1168): Icon Only
D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
,D/PanelView( 1168): There is/are notification(s) 
D/PanelView( 1168): There is/are notification(s) 
,D/hcjo    ( 7121): AutoUpdateManager:IDLE:execute
,D/InitializeManagerStateMachine( 7121): execute::IDLE:EXECUTE
,D/InitializeManagerStateMachine( 7121): exit::IDLE
D/InitializeManagerStateMachine( 7121): entry::NETWORK_CHECK
I/Hs20UtilService( 1307): Starting #8
,I/Hs20UtilService( 1307): Message received 5007
,D/ConnectivityService(  872): returning getNetworkInfo(networkType - 0) :[type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/ConnectivityService(  872): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/InitializeManagerStateMachine( 7121): execute::NETWORK_CHECK:NETWORK_STATE_OK
D/InitializeManagerStateMachine( 7121): exit::NETWORK_CHECK
D/InitializeManagerStateMachine( 7121): entry::CHECK_COUNTRY_INFO
D/InitializeManagerStateMachine( 7121): execute::CHECK_COUNTRY_INFO:COUNTRY_INFO_OK
D/InitializeManagerStateMachine( 7121): exit::CHECK_COUNTRY_INFO
,D/InitializeManagerStateMachine( 7121): entry::SUCCESS
D/hcjo    ( 7121): AutoUpdateManager:INITCHECK:onInitializeSuccess
D/NearbySettings( 1307): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
V/NearbySettings( 1307): DMSUtil.isNetworkConnected - flag-null, state-null
,D/ConnectivityService(  872): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/NearbySettings( 1307): DMSUtil.isNetworkConnected - WIFI: CONNECTED
D/ConnectivityService(  872): returning getNetworkInfo(networkType - 13) :[type: WIFI_P2P[] - WIFI_P2P, state: UNKNOWN/IDLE, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/NearbySettings( 1307): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 1307): DMSUtil.isNetworkConnected - WIFI-true, Hotspot-false, P2P-false, Eth-false
I/NearbySettings( 1307): MountReceiver.onReceive - Keep current state
,D/hcjo    ( 7121): AutoUpdateTriggerManager:IDLE:notifyNextTime
,D/hcjo    ( 7121): AutoUpdateManager:UPD_CHECK_TIMING:onNoUpdateTime
D/ConnectivityService(  872): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/InitializeManagerStateMachine( 7121): exit::SUCCESS
,D/ConnectivityService(  872): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/InitializeManagerStateMachine( 7121): entry::IDLE
,I/Hs20UtilService( 1307): Starting #9
,I/Hs20UtilService( 1307): Message received 5007
E/SMD     (  279): DCD ON
,D/NearbySettings( 1307): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,I/NearbySettings( 1307): MountReceiver.onReceive - Keep current state
,I/Hs20UtilService( 1307): Starting #10
,I/Hs20UtilService( 1307): Message received 5007
,D/NearbySettings( 1307): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,V/NearbySettings( 1307): DMSUtil.isNetworkConnected - flag-null, state-null
D/ConnectivityService(  872): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/NearbySettings( 1307): DMSUtil.isNetworkConnected - WIFI: CONNECTED
D/ConnectivityService(  872): returning getNetworkInfo(networkType - 13) :[type: WIFI_P2P[] - WIFI_P2P, state: UNKNOWN/IDLE, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/NearbySettings( 1307): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 1307): DMSUtil.isNetworkConnected - WIFI-true, Hotspot-false, P2P-false, Eth-false
I/NearbySettings( 1307): MountReceiver.onReceive - Keep current state
,E/LightSensor(  872): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  872): mCallbacks.updateBrightness()
D/DisplayPowerController(  872): getFinalBrightness : 1 -> 1
,I/Hs20UtilService( 1307): Starting #11
,I/Hs20UtilService( 1307): Message received 5007
,D/NearbySettings( 1307): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,I/NearbySettings( 1307): MountReceiver.onReceive - Keep current state
,I/WifiStateMachine(  872): callSECApi what=220
D/WifiStateMachine(  872): SEC_COMMAND_ID_GET_FWS_OPEN_AP_CHECK : 0
,I/PCWCLIENTTRACE_PushUtil( 6771): SPPPushClient is installed : true
I/PCWCLIENTTRACE_PushUtil( 6771): sales region : global
I/PCWCLIENTTRACE_PushUtil( 6771): getPushTypeList : [SPP, GCM]
I/PCWCLIENTTRACE_SYSTEMReceiver( 6771): [onReceive] - android.net.conn.CONNECTIVITY_CHANGE
,I/SurfaceFlinger(  249): id=16 createSurf (1x1),1 flag=4, Toast
,D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
,D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
,I/DIAGMON_AGENT( 7619): [lIIllllllllIlIlIllll(17/llIIIIlllllIIllIIllI)] Receive broadcast: android.net.conn.CONNECTIVITY_CHANGE
,I/DIAGMON_AGENT( 7619): [lIIllllllllIlIlIllll(31/llIIIIlllllIIllIIllI)] Running with RegistrationReceiver
,D/PowerManagerService(  872): [api] acquire WakeLock flags=0x2000000a tag=WindowManager uid=1000 pid=872
,D/DisplayPowerController(  872): getFinalBrightness : 8 -> 8
,D/PowerManagerService(  872): [s] DisplayPowerCallbacks : onStateChanged()
,D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
,D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
,D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
,D/lights  (  872): lcd : 6 +
,D/lights  (  872): lcd : 6 -
,D/lights  (  872): lcd : 8 +
D/DisplayPowerController(  872): getFinalBrightness : 8 -> 8
,D/lights  (  872): lcd : 8 -
,D/DisplayPowerController(  872): getFinalBrightness : 8 -> 8
,D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
,D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
,D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
E/Watchdog(  872): !@Sync 3
,I/FOTA_Client( 7642): [com.sec.android.fotaclient.FotaRegisterReceiver(113/onReceive)] Already device registered...
,I/FOTA_Client( 7642): [com.sec.android.fotaclient.FotaUpdaterReceiver(103/onReceive)] Auto update settings is activated
,I/FOTA_Client( 7642): [lllllllllllIlllllIIl(197/lllIlIlIIIllIIlIllIl)] Polling time is vaild
,I/FOTA_Client( 7642): [com.sec.android.fotaclient.FotaUpdaterReceiver(126/onReceive)] Heartbeat settings is activated.
,I/FOTA_Client( 7642): [llIlIIIIlllIlllllIll(125/llIlIIIIlIIIIIlIlIII)] heartbeat time is vaild
,D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
,I/KLMS-2.4.503: ( 7679): KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,I/KLMS-2.4.503: ( 7679): MainReciver(): EventNotificationReciver- method called: AppActivityListner onReceive for Intent Action : android.net.conn.CONNECTIVITY_CHANGE , timestamp: 1452294299229
,I/KLMS-2.4.503: ( 7679): MainReciver(): NETWORK_STATE_CHANGED_ACTION
,D/ConnectivityService(  872): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/ConnectivityService(  872): returning getNetworkInfo(networkType - 0) :[type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/KLMS-2.4.503: ( 7679): KLMSUtility(): isNetworkAvailable() - WIFI : true| MOBILE : false
,I/KLMS-2.4.503: ( 7679): StateImplV2(): networkChangeListener().START
,I/KLMS-2.4.503: ( 7679): NetworkChangeOperations(): uploadRequestLog().START 
,D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
,I/KLMS-2.4.503: ( 7679): StateImplV2(): networkChangeListener().END
,D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1168): value : false
,I/SO_AGENT( 7706): [com.sec.android.soagent.RegisterReceiver(104/onReceive)] Get Accessory List
,D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
,E/LightSensor(  872): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  872): mCallbacks.updateBrightness()
D/DisplayPowerController(  872): getFinalBrightness : 8 -> 8
,D/ConnectivityService(  872): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
,E/SPPClientService( 7746): [[SystemStateMoniter]] SystemStateMonitorService : noConnect? : false
,I/SA      ( 7764): [OR] onReceive log=[SA = 2.1.0142 V = 21 HWD = 1920X1080 3.0 dpi = 480  SIZE = 2 LOCALE = en_US CSC = DBT MCC = 0 MNC 0 T = user DEVICE = klte P = kltexx I = LRX21T M = SM-G900F OKLEFT false DIS LRX21T.G900FXXU1BOD3 PSS = 5.219788042639568  ]
,I/SA      ( 7764): [OR] onReceive Intent=[ conn.CONNECTIVITY_CHANGE. networkInfo:[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] networkType:1 inetCondition:0 extraInfo:? isDefault:true ]
I/SA      ( 7764): [OR] == ACTION_CONNECTIVITY_CHANGE ==
,D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
,I/SA      ( 7764): [TPMU]  strSIMState 	:SIM_STATE_UNKNOWN
I/SA      ( 7764): [OR] == isSIMCardReady false ==
,D/ConnectivityService(  872): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/SA      ( 7764): [SCU] == networkStateCheck == true
I/SA      ( 7764): [DM] getCountryCodeFromCSC : DE
I/SA      ( 7764): isChinaCountryCode : false
I/SA      ( 7764): [SCU] is ChinestModel Data Restricted   : false
I/SA      ( 7764): [OR] == networkStateCheck true ==
I/SA      ( 7764): [OR] GetMyCountryZoneTask
,I/SA      ( 7764): [OR] onReceive END
,D/ConnectivityService(  872): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/SA      ( 7764): [SRS] prepareGetMyCountryZone
,I/SA      ( 7764): [TPMU]  strSIMState 	:SIM_STATE_UNKNOWN
,I/SA      ( 7764): [SSP] query invoked
D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
,D/accuweather( 7286): [KK AccuPhone]>>> WC:30 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,D/accuweather( 7286): [KK AccuPhone]>>> UIMEM:106 [0:0] The widget does not exist in idle!!
,I/KnoxUsageLogPro( 7792): KnoxUsageReceiver onReceive :android.net.conn.CONNECTIVITY_CHANGE myUserId=0
I/KnoxUsageLogPro( 7792): premStatus:2
,I/KnoxUsageLogPro( 7792): isEulaShown : false
I/KnoxUsageLogPro( 7792): KnoxUsageReceiver onReceive : not Processible, just return
,I/SA      ( 7764): [TPMU] GetMccFromDB : null
,I/SA      ( 7764): [SCU] getMccFromPreferece mcc = 260
I/SA      ( 7764): [TPM] isNoProxy(default) : true
I/SA      ( 7764): [RC New] Execute method=[GET] start
,D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
,D/Headlines( 5480): HeadlinesSystemBroadcastReceiver onReceive android.net.conn.CONNECTIVITY_CHANGE
D/HeadlinesChannelUtil( 5480): getCountryCode(): countryCode = DE
,D/Headlines( 5480): Breath.onStartCommand : com.samsung.android.internal.headlines.UPDATE_WELCOME_CARD flag : 0
,D/HeadlinesCardManager( 5480): updateCategory : HeadlinesCardManager:updateCategory() category size == 0
D/HeadlinesCardManager( 5480): updateCategory : HeadlinesCardManager:updateCategory() try to query category list
D/Headlines( 5480): queryCategory.  mRequest is not initialized.
D/HeadlinesCardManager( 5480): updateCategory : HeadlinesCardManager:updateCategory() reponse : false
,D/HeadlinesCardManager( 5480): requestUpdateNewsWelcomeCard : request update welcome card to content card.
D/HeadlinesDataCenter( 5480): requestUpdateNewsWelcomeCard !!! no welcome card
,D/ConnectivityService(  872): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
,D/ConnectivityService(  872): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  872): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/QuickConnect( 7881): PeriphStartReceiver.onReceive - android.net.conn.CONNECTIVITY_CHANGE
,I/QuickConnect( 7881): PeriphStartReceiver.onReceive - USER_OWNER care CONNECTIVITY_ACTION. run P service
,I/QuickConnect( 7881): PeriphStartReceiver.onReceive - no need to start
,D/ConnectivityService(  872): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  872): returning getNetworkInfo(networkType - 0) :[type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
,D/RCPManagerService(  872): exchangeData() failure , invalid userId
,D/RCPManagerService(  872): exchangeData() failure , invalid userId
,D/ConnectivityService(  872): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
,D/SecurityLogAgent( 7500): KnoxConfiguration : Current State = 1
D/SecurityLogAgent( 7500): KnoxConfiguration : Current State Mapping Found 
D/SecurityLogAgent( 7500): StateMachine : Current State = 1
,D/ConnectivityService(  872): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/SecurityLogAgent( 7500): StateMachine : Changed Current State = 1
,D/com.peel.receiver.ConnectivityActionReceiver( 5585): ConnectivityActionReceiver onReceive
D/com.peel.receiver.ConnectivityActionReceiver( 5585): 
D/com.peel.receiver.ConnectivityActionReceiver( 5585): 
D/com.peel.receiver.ConnectivityActionReceiver( 5585): country_code: Germany -- rom region: GB
D/com.peel.receiver.ConnectivityActionReceiver( 5585): 
,D/ConnectivityService(  872): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
,D/ConnectivityService(  872): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/com.peel.receiver.ConnectivityActionReceiver( 5585): 
D/com.peel.receiver.ConnectivityActionReceiver( 5585): 
D/com.peel.receiver.ConnectivityActionReceiver( 5585):  network type WIFI path... network offline: false
D/com.peel.receiver.ConnectivityActionReceiver( 5585): 
D/com.peel.receiver.ConnectivityActionReceiver( 5585): has active network... run services...
D/com.peel.receiver.ConnectivityActionReceiver( 5585): 
D/com.peel.receiver.ConnectivityActionReceiver( 5585): 
D/com.peel.receiver.ConnectivityActionReceiver( 5585): last run: 1452283589907 -- System.currentTimeMillis()-last_run: 10709508
D/com.peel.receiver.ConnectivityActionReceiver( 5585): ... skip 
D/com.peel.receiver.ConnectivityActionReceiver( 5585): ... skip last_72_check
,I/SA      ( 7764): [RC New] Security=[true]
,D/ConnectivityService(  872): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
,D/ConnectivityService(  872): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  872): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  872): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  872): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  872): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
,D/ConnectivityService(  872): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  872): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ChimeraCfgMgr( 2462): Loading module com.google.android.gms.kids from APK com.google.android.gms
,D/ConnectivityService(  872): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  872): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  872): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
,D/ConnectivityService(  872): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/hcjo    ( 7121): AutoUpdateManager:IDLE:execute
,E/LightSensor(  872): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  872): mCallbacks.updateBrightness()
D/DisplayPowerController(  872): getFinalBrightness : 8 -> 8
,D/InitializeManagerStateMachine( 7121): execute::IDLE:EXECUTE
D/InitializeManagerStateMachine( 7121): exit::IDLE
D/InitializeManagerStateMachine( 7121): entry::NETWORK_CHECK
,D/ConnectivityService(  872): returning getNetworkInfo(networkType - 0) :[type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/ConnectivityService(  872): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/InitializeManagerStateMachine( 7121): execute::NETWORK_CHECK:NETWORK_STATE_OK
D/InitializeManagerStateMachine( 7121): exit::NETWORK_CHECK
D/InitializeManagerStateMachine( 7121): entry::CHECK_COUNTRY_INFO
D/InitializeManagerStateMachine( 7121): execute::CHECK_COUNTRY_INFO:COUNTRY_INFO_OK
D/InitializeManagerStateMachine( 7121): exit::CHECK_COUNTRY_INFO
D/InitializeManagerStateMachine( 7121): entry::SUCCESS
D/hcjo    ( 7121): AutoUpdateManager:INITCHECK:onInitializeSuccess
D/hcjo    ( 7121): AutoUpdateTriggerManager:IDLE:notifyNextTime
D/hcjo    ( 7121): AutoUpdateManager:UPD_CHECK_TIMING:onNoUpdateTime
D/ConnectivityService(  872): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/InitializeManagerStateMachine( 7121): exit::SUCCESS
D/InitializeManagerStateMachine( 7121): entry::IDLE
,D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
,I/GLSUser ( 1676): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: ac2dm
,I/GLSUser ( 1676): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> ac2dm without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1676): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1676): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1676): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
,V/BitmapFactory( 1676): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  872): uri = 14 selection = getSealedState
,D/SecContentProvider2(  872): mCursor = null
D/SecContentProvider2(  872): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  872): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
V/ApplicationPolicy(  872): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,W/Kids    ( 2462): [AccountUtils] Account not ready
W/Kids    ( 2462): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/Kids    ( 2462): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/Kids    ( 2462): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/Kids    ( 2462): 	at com.google.android.gms.auth.p.c(SourceFile:550)
W/Kids    ( 2462): 	at com.google.android.gms.auth.p.b(SourceFile:477)
W/Kids    ( 2462): 	at com.google.android.gms.kids.account.k.d(SourceFile:103)
W/Kids    ( 2462): 	at com.google.android.gms.kids.account.p.a(SourceFile:70)
W/Kids    ( 2462): 	at com.google.android.gms.kids.account.t.a(SourceFile:62)
W/Kids    ( 2462): 	at com.google.android.gms.chimera.f.run(SourceFile:179)
W/Kids    ( 2462): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
W/Kids    ( 2462): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
W/Kids    ( 2462): 	at java.lang.Thread.run(Thread.java:818)
,D/StatusBar( 1168): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
,I/PhoneStatusBar( 1168): Icon Only
D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
D/PanelView( 1168): There is/are notification(s) 
,D/PanelView( 1168): There is/are notification(s) 
,D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
,D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1168): value : false
,D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1168): value : false
,D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1168): value : false
,D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1168): value : false
,D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
,D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1168): value : false
,D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1168): value : false
,E/LightSensor(  872): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  872): mCallbacks.updateBrightness()
D/DisplayPowerController(  872): getFinalBrightness : 8 -> 8
,D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1168): value : false
,D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
,D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1168): value : false
,D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1168): value : false
,D/GCM     ( 1676): Connected
,D/ConnectivityService(  872): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  872): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  872): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  872): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1168): value : false
,D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
,D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
,D/ConnectivityService(  872): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/GCM     ( 1676): Message class com.google.f.a.a.p
D/ConnectivityService(  872): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  872): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
,E/LightSensor(  872): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  872): mCallbacks.updateBrightness()
D/DisplayPowerController(  872): getFinalBrightness : 8 -> 8
,I/WifiStateMachine(  872): REQUEST_POWER_SAVE_ON
,E/WifiStateMachine(  872): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: [192.168.1.135/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576} new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.135/24,fe80::ee1f:72ff:fe18:8b78/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0}
,D/ConnectivityService(  872): Update of LinkProperties for NetworkAgentInfo [WIFI () - 503]; created=true
D/ConnectivityService(  872): updateLinkProperties: newLp = {InterfaceName: wlan0 LinkAddresses: [192.168.1.135/24,fe80::ee1f:72ff:fe18:8b78/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}
D/ConnectivityService(  872): identical MTU - not setting
,D/ConnectivityService(  872): updateSourceRoutes : add source routing for type : 1
D/ConnectivityService(  872): updateSourceRoutes : add src route for:fe80::ee1f:72ff:fe18:8b78
V/        (  272): QcRouteController
E/WifiStateMachine(  872): updateLinkProperties nid: 0 state: CONNECTED reason: CMD_UPDATE_LINKPROPERTIES v4 v4r v4dns isprov
,D/SmartBondingService(  872): SmartBondingReceiver: onReceive action=android.net.wifi.LINK_CONFIGURATION_CHANGED
,D/ConnectivityService(  872): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/SmartBondingService(  872): EVENT_UPDATE_SB_STATE called / mDisableBySIOP false
,D/SmartBondingService(  872): getSBEnabled() enabled =false
D/SmartBondingService(  872): getSBEnabled() enabled =false
D/SmartBondingService(  872): getSBEnabled() enabled =false
,V/        (  272): QcRouteController
,W/NetworkManagementService(  872): route cmd failed: 
W/NetworkManagementService(  872): com.android.server.NativeDaemonConnector$NativeDaemonFailureException: command '72 route replace src v6 wlan0 fe80::ee1f:72ff:fe18:8b78 2 ::' failed with '400 72 -6 route replace default via :: dev wlan0 scope global table 2: RTNETLINK answers: Invalid argument
W/NetworkManagementService(  872): '
W/NetworkManagementService(  872): 	at com.android.server.NativeDaemonConnector.execute(NativeDaemonConnector.java:438)
W/NetworkManagementService(  872): 	at com.android.server.NativeDaemonConnector.executeForList(NativeDaemonConnector.java:371)
W/NetworkManagementService(  872): 	at com.android.server.NativeDaemonConnector.execute(NativeDaemonConnector.java:336)
,W/NetworkManagementService(  872): 	at com.android.server.NativeDaemonConnector.execute(NativeDaemonConnector.java:321)
W/NetworkManagementService(  872): 	at com.android.server.NetworkManagementService.replaceSrcRoute(NetworkManagementService.java:2812)
W/NetworkManagementService(  872): 	at com.android.server.ConnectivityService.updateSourceRoutes(ConnectivityService.java:5478)
W/NetworkManagementService(  872): 	at com.android.server.ConnectivityService.updateLinkProperties(ConnectivityService.java:5305)
W/NetworkManagementService(  872): 	at com.android.server.ConnectivityService.access$1800(ConnectivityService.java:230)
W/NetworkManagementService(  872): 	at com.android.server.ConnectivityService$NetworkStateTrackerHandler.handleMessage(ConnectivityService.java:2324)
W/NetworkManagementService(  872): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/NetworkManagementService(  872): 	at android.os.Looper.loop(Looper.java:145)
W/NetworkManagementService(  872): 	at android.os.HandlerThread.run(HandlerThread.java:61)
D/Nat464Xlat(  872): requiresClat: netType=1, connected=true, hasIPv4Address=true
,D/ConnectivityService(  872): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 503]
D/ConnectivityService(  872): calling update connectivity
D/ConnectivityService(  872):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  872):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
,D/ConnectivityService(  872): sending notification IP_CHANGED for NetworkRequest [ id=2, legacyType=-1, [] ]
,D/ConnectivityService(  872): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 503]
D/ConnectivityService(  872): calling update connectivity
D/ConnectivityManager.CallbackHandler( 1168): CM callback handler got msg 524295
D/ConnectivityService(  872):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  872):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
,D/ConnectivityService(  872): sending notification IP_CHANGED for NetworkRequest [ id=2, legacyType=-1, [] ]
,D/ConnectivityManager.CallbackHandler( 1168): CM callback handler got msg 524295
,V/AlarmManager(  872): waitForAlarm result :8
,D/KeyguardUpdateMonitor( 1168): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1168): handleTimeUpdate
,D/KeyguardEffectViewController( 1168): onReceive action : android.intent.action.TIME_TICK
,I/KeyguardEffectViewController( 1168): *** don't update sliding image ***
,E/LightSensor(  872): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  872): mCallbacks.updateBrightness()
D/DisplayPowerController(  872): getFinalBrightness : 8 -> 8
,D/DateView( 1168): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1168): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,E/WifiStateMachine(  872): CAPTIVE_PORTAL_EVENT_AUTHENTICATED
,E/LightSensor(  872): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  872): mCallbacks.updateBrightness()
D/DisplayPowerController(  872): getFinalBrightness : 8 -> 8
,D/ConnectivityService(  872): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/dhcpcd  ( 7634): wlan0: sending IPv6 Router Solicitation
,E/LightSensor(  872): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  872): mCallbacks.updateBrightness()
D/DisplayPowerController(  872): getFinalBrightness : 8 -> 8
,I/SA      ( 7764): [RC New] [v2liruge] api execute + 989
I/SA      ( 7764): [RC New] executeRequest [v2liruge] httpResponse : HTTP/1.1 200 OK
,I/System.out( 7764): AsyncTask #2 calls detatch()
I/SA      ( 7764): [ODM] saveOpenData( GEO_IP, PL )
,I/SA      ( 7764): [OCP] update openData : PL
,I/SA      ( 7764): [TPMU] getNetworkMcc : 
,I/SA      ( 7764): [SCU] saveMccToPreferece Start
I/SA      ( 7764): [SCU] RegionMCC : 260
,I/SA      ( 7764): [SSP] query invoked
,I/SA      ( 7764): [TPMU] GetMccFromDB : null
,I/SA      ( 7764): [SCU] getMccFromPreferece mcc = 260
I/SA      ( 7764): [SCU] saveMccToPreferece End
,I/SA      ( 7764): [RC New] executeRequest [v2liruge] end. 1087
,I/SA      ( 7764): [RC New] Execute end
I/SA      ( 7764): [OR] GetMyCountryZoneTask mcc = 260
I/SA      ( 7764): [OR] GetMyCountryZoneTask Success
,E/LightSensor(  872): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  872): mCallbacks.updateBrightness()
,D/DisplayPowerController(  872): getFinalBrightness : 8 -> 8
,E/LightSensor(  872): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  872): mCallbacks.updateBrightness()
,D/DisplayPowerController(  872): getFinalBrightness : 8 -> 8
,D/WearableService( 4822): callingUid 10012, callindPid: 4822
,D/ResourcesManager( 7563): creating new AssetManager and set to /data/app/com.google.android.gms-1/base.apk
,W/ResourcesManager( 7563): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,W/ResourcesManager( 7563): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,I/GHttpClientFactory( 7563): Using the GMSCore's GoogleHttpClient
,D/WearableClient( 7563): WearableClientImpl.onPostInitHandler: done
,D/WearableClient( 7563): WearableClientImpl.onPostInitHandler: done
,E/LightSensor(  872): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
D/AutomaticBrightnessController(  872): mCallbacks.updateBrightness()
D/DisplayPowerController(  872): getFinalBrightness : 8 -> 8
,D/WearableClient( 7563): WearableClientImpl.onPostInitHandler: done
,D/WearableClient( 7563): WearableClientImpl.onPostInitHandler: done
,E/GmsUtils( 7563): Failed to connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
,E/GmsUtils( 7563): Failed to connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
,I/MusicLeanback( 7563): Conditions not met for autocaching.
,I/MusicLeanback( 7563): Stop autocaching.
,E/ActivityThread( 7563): Service com.google.android.music.download.TrackDownloadQueueService has leaked ServiceConnection com.google.android.gms.http.GoogleURLConnectionFactory$1@123b0e74 that was originally bound here
E/ActivityThread( 7563): android.app.ServiceConnectionLeaked: Service com.google.android.music.download.TrackDownloadQueueService has leaked ServiceConnection com.google.android.gms.http.GoogleURLConnectionFactory$1@123b0e74 that was originally bound here
E/ActivityThread( 7563): 	at android.app.LoadedApk$ServiceDispatcher.<init>(LoadedApk.java:1134)
E/ActivityThread( 7563): 	at android.app.LoadedApk.getServiceDispatcher(LoadedApk.java:1028)
E/ActivityThread( 7563): 	at android.app.ContextImpl.bindServiceCommon(ContextImpl.java:2085)
E/ActivityThread( 7563): 	at android.app.ContextImpl.bindService(ContextImpl.java:2068)
E/ActivityThread( 7563): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:559)
E/ActivityThread( 7563): 	at com.google.android.gms.http.GoogleURLConnectionFactory.<init>(Unknown Source)
E/ActivityThread( 7563): 	at com.google.android.gms.http.GoogleHttpClient.<init>(Unknown Source)
E/ActivityThread( 7563): 	at com.google.android.gms.http.GoogleHttpClient.<init>(Unknown Source)
E/ActivityThread( 7563): 	at com.google.android.gms.http.GoogleHttpClient.<init>(Unknown Source)
E/ActivityThread( 7563): 	at com.google.android.music.GoogleHttpClientFactory.createGoogleHttpClient(GoogleHttpClientFactory.java:81)
E/ActivityThread( 7563): 	at com.google.android.music.cloudclient.MusicRequest.createHttpClient(MusicRequest.java:110)
E/ActivityThread( 7563): 	at com.google.android.music.cloudclient.MusicRequest.getSharedHttpClient(MusicRequest.java:100)
E/ActivityThread( 7563): 	at com.google.android.music.download.BaseDownloadQueueManager.<init>(BaseDownloadQueueManager.java:110)
E/ActivityThread( 7563): 	at com.google.android.music.download.TrackDownloadQueueManager.<init>(TrackDownloadQueueManager.java:10)
E/ActivityThread( 7563): 	at com.google.android.music.download.TrackDownloadQueueService.onCreate(TrackDownloadQueueService.java:25)
E/ActivityThread( 7563): 	at android.app.ActivityThread.handleCreateService(ActivityThread.java:3100)
E/ActivityThread( 7563): 	at android.app.ActivityThread.access$1900(ActivityThread.java:172)
E/ActivityThread( 7563): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1505)
E/ActivityThread( 7563): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/ActivityThread( 7563): 	at android.os.Looper.loop(Looper.java:145)
E/ActivityThread( 7563): 	at android.app.ActivityThread.main(ActivityThread.java:5832)
E/ActivityThread( 7563): 	at java.lang.reflect.Method.invoke(Native Method)
E/ActivityThread( 7563): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/ActivityThread( 7563): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
E/ActivityThread( 7563): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
,E/LightSensor(  872): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  872): mCallbacks.updateBrightness()
D/DisplayPowerController(  872): getFinalBrightness : 8 -> 8
,V/AlarmManager(  872): waitForAlarm result :8
,E/LightSensor(  872): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  872): mCallbacks.updateBrightness()
,D/DisplayPowerController(  872): getFinalBrightness : 8 -> 8
,I/GLSUser ( 1676): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.googlequicksearchbox, service: oauth2:https://www.googleapis.com/auth/googlenow
,I/GLSUser ( 1676): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/googlenow without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1676): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1676): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1676): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ResourcesManager( 1676): creating new AssetManager and set to /system/priv-app/Velvet/Velvet.apk
,V/BitmapFactory( 1676): DecodeImagePath(decodeResourceStream3) : res/mipmap-xxhdpi-v4/ic_launcher_google_search.png
,V/BitmapFactory( 1676): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  872): uri = 14 selection = getSealedState
,D/SecContentProvider2(  872): mCursor = null
D/SecContentProvider2(  872): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  872): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy(  872): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/StatusBar( 1168): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,I/PhoneStatusBar( 1168): Icon Only
D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
D/PanelView( 1168): There is/are notification(s) 
,D/PanelView( 1168): There is/are notification(s) 
,D/ConnectivityService(  872): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,W/Search.LoginHelper( 1569): User recoverable exception for scope: oauth2:https://www.googleapis.com/auth/googlenow
,E/LightSensor(  872): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  872): mCallbacks.updateBrightness()
D/DisplayPowerController(  872): getFinalBrightness : 8 -> 8
,E/LightSensor(  872): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  872): mCallbacks.updateBrightness()
D/DisplayPowerController(  872): getFinalBrightness : 8 -> 8
,D/PowerManagerService(  872): [s] UserActivityState : 2 -> 4
I/PowerManagerService(  872): [PWL] On : 76128 (30001 ms ago)
,I/PowerManagerService(  872): [PWL]  mStayOn: false  mWakeLockSummary & WAKE_LOCK_STAY_AWAKE: 20  mUserActivitySummary: 0x4
I/PowerManagerService(  872): [PWL]  SCREEN_BRIGHT_WAKE_LOCK        'WindowManager' ON_AFTER_RELEASE (uid=1000, pid=872, ws=WorkSource{10059}) (elapsedTime=2482)
,I/jxcore-log( 7436): Test app app.js loaded
I/jxcore-log( 7436): 
,I/Choreographer( 7436): Skipped 436 frames!  The application may be doing too much work on its main thread.
,I/chromium( 7436): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,I/chromium( 7436): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
,E/LightSensor(  872): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  872): mCallbacks.updateBrightness()
,D/DisplayPowerController(  872): getFinalBrightness : 8 -> 8
,I/WifiStateMachine(  872): CMD_RSSI_POLL : calculateWifiScore in!
,I/WifiStateMachine(  872): CMD_RSSI_POLL : calculateWifiScore out!
,I/WifiStateMachine(  872): CMD_RSSI_POLL : out!
,E/LightSensor(  872): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  872): mCallbacks.updateBrightness()
,D/DisplayPowerController(  872): getFinalBrightness : 8 -> 8
,E/SMD     (  279): DCD ON
,E/LightSensor(  872): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  872): mCallbacks.updateBrightness()
D/DisplayPowerController(  872): getFinalBrightness : 8 -> 8
,D/ConnectivityService(  872): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/LightSensor(  872): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  872): mCallbacks.updateBrightness()
D/DisplayPowerController(  872): getFinalBrightness : 8 -> 8
,E/LightSensor(  872): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  872): mCallbacks.updateBrightness()
D/DisplayPowerController(  872): getFinalBrightness : 8 -> 8
,D/SSRM:m  (  872): SIOP:: AP = 410, PST = 420, CUR = 300
,D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1168): value : false
D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
,D/PowerManagerService(  872): [api] [s] userActivity : event: 0 flags: 0 (uid: 1000 pid: 872) eventTime = 107128
,D/PowerManagerService(  872): [s] UserActivityState : 4 -> 1
,D/PowerManagerService(  872): [api] release WakeLock flags=0x2000000a tag=WindowManager uid=1000 pid=872 (0x0)
D/PowerManagerService(  872): [api] applyWakeLockFlagsOnReleaseLocked : userActivityNoUpdateLocked is called : SCREEN_BRIGHT_WAKE_LOCK        'WindowManager' ON_AFTER_RELEASE (uid=1000, pid=872, ws=WorkSource{10059}) (elapsedTime=3484)
,D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1168): value : false
,D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1168): value : false
,D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
,E/LightSensor(  872): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  872): mCallbacks.updateBrightness()
D/DisplayPowerController(  872): getFinalBrightness : 8 -> 8
,D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1168): value : false
,D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
,D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
,D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
,D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
,D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
,D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
,D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
,D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
,D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1168): value : false
,D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1168): value : false
,E/LightSensor(  872): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  872): mCallbacks.updateBrightness()
D/DisplayPowerController(  872): getFinalBrightness : 8 -> 8
,D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1168): value : false
,D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
,D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1168): value : false
,D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1168): value : false
,D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1168): value : false
,D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1168): value : false
,D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1168): value : false
,D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1168): value : false
,D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1168): value : false
,D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1168): value : false
,E/LightSensor(  872): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1168): value : false
D/AutomaticBrightnessController(  872): mCallbacks.updateBrightness()
,D/DisplayPowerController(  872): getFinalBrightness : 8 -> 8
,D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1168): value : false
,I/GAV4    ( 7823): Thread[GAThread,5,main]: No campaign data found.
,D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1168): value : false
,D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1168): value : false
,D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1168): value : false
,D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1168): value : false
,D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1168): value : false
,D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1168): value : false
,D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1168): value : false
,D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1168): value : false
,I/SurfaceFlinger(  249): id=16 Removed Toast (8/8)
,I/SurfaceFlinger(  249): id=16 Removed Toast (-2/8)
,D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
,D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
,D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
,I/Atfwd_Sendcmd(  319): AtCmdFwd service not ready - Exhausted retry attempts - :6
,I/Atfwd_Daemon(  319): result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,E/LightSensor(  872): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  872): mCallbacks.updateBrightness()
,D/DisplayPowerController(  872): getFinalBrightness : 8 -> 8
,E/LightSensor(  872): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  872): mCallbacks.updateBrightness()
,D/DisplayPowerController(  872): getFinalBrightness : 8 -> 8
,E/LightSensor(  872): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  872): mCallbacks.updateBrightness()
D/DisplayPowerController(  872): getFinalBrightness : 8 -> 8
,E/LightSensor(  872): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  872): mCallbacks.updateBrightness()
,D/DisplayPowerController(  872): getFinalBrightness : 8 -> 8
,E/LightSensor(  872): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  872): mCallbacks.updateBrightness()
,D/DisplayPowerController(  872): getFinalBrightness : 8 -> 8
,I/PCWCLIENTTRACE_SYSTEMReceiver( 6771): mConnectivityHandler : connected
,E/LightSensor(  872): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  872): mCallbacks.updateBrightness()
,D/DisplayPowerController(  872): getFinalBrightness : 8 -> 8
,D/ConnectivityService(  872): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,W/PCWCLIENTTRACE_AccountUtil( 6771): [hasSamungAccount] - No Samsung Account
,I/CSTORAGE( 6771): ================================================
,I/CSTORAGE( 6771):  CSTORAGE_SKM_LIB, v1.0.22, MSM8974|MSM8x26|MSM8x10
I/CSTORAGE( 6771): ================================================
I/PCWCLIENTTRACE_SecurePreferencesJNI( 6771): [GetString-S]
,E/art     ( 6771): No implementation found for java.lang.String com.sec.pcw.device.util.SecurePreferencesJNI.getString() (tried Java_com_sec_pcw_device_util_SecurePreferencesJNI_getString and Java_com_sec_pcw_device_util_SecurePreferencesJNI_getString__)
W/PCWCLIENTTRACE_SecurePreferencesJNI( 6771): GetString : secure API is not supported!! No implementation found for java.lang.String com.sec.pcw.device.util.SecurePreferencesJNI.getString() (tried Java_com_sec_pcw_device_util_SecurePreferencesJNI_getString and Java_com_sec_pcw_device_util_SecurePreferencesJNI_getString__)
I/PCWCLIENTTRACE_SecurePreferencesJNI( 6771): [GetString-E]
,I/PCWCLIENTTRACE_PushUtil( 6771): SPPPushClient is installed : true
,I/PCWCLIENTTRACE_PushUtil( 6771): sales region : global
I/PCWCLIENTTRACE_PushUtil( 6771): getPushTypeList : [SPP, GCM]
E/PCWCLIENTTRACE_PCWHandler( 6771): [ensureRegistration] - No Samsung account
,E/LightSensor(  872): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  872): mCallbacks.updateBrightness()
,D/DisplayPowerController(  872): getFinalBrightness : 8 -> 8
,I/dhcpcd  ( 7634): wlan0: sending IPv6 Router Solicitation
,E/LightSensor(  872): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  872): mCallbacks.updateBrightness()
D/DisplayPowerController(  872): getFinalBrightness : 8 -> 8
,E/LightSensor(  872): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  872): mCallbacks.updateBrightness()
D/DisplayPowerController(  872): getFinalBrightness : 8 -> 8
,E/LightSensor(  872): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  872): mCallbacks.updateBrightness()
,D/DisplayPowerController(  872): getFinalBrightness : 8 -> 8
,I/WifiStateMachine(  872): CMD_RSSI_POLL : calculateWifiScore in!
,I/WifiStateMachine(  872): CMD_RSSI_POLL : calculateWifiScore out!
I/WifiStateMachine(  872): CMD_RSSI_POLL : out!
,E/LightSensor(  872): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  872): mCallbacks.updateBrightness()
,D/DisplayPowerController(  872): getFinalBrightness : 8 -> 8
,E/SMD     (  279): DCD ON
,E/LightSensor(  872): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  872): mCallbacks.updateBrightness()
,D/DisplayPowerController(  872): getFinalBrightness : 8 -> 8
,E/LightSensor(  872): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  872): mCallbacks.updateBrightness()
,D/DisplayPowerController(  872): getFinalBrightness : 8 -> 8
,E/LightSensor(  872): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  872): mCallbacks.updateBrightness()
,D/DisplayPowerController(  872): getFinalBrightness : 8 -> 8
,D/StatusBar.NetworkController( 1168): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02012b/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020464/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
,D/StatusBar.NetworkController( 1168): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1168): applyOpen
,D/StatusBar.NetworkController( 1168): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1168): applyOpen
D/StatusBar.NetworkController( 1168): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1168): applyOpen
D/StatusBar.NetworkController( 1168): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1168): applyOpen
,E/LightSensor(  872): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  872): mCallbacks.updateBrightness()
,D/DisplayPowerController(  872): getFinalBrightness : 8 -> 8
,E/LightSensor(  872): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  872): mCallbacks.updateBrightness()
,D/DisplayPowerController(  872): getFinalBrightness : 8 -> 8
,E/LightSensor(  872): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  872): mCallbacks.updateBrightness()
,D/DisplayPowerController(  872): getFinalBrightness : 8 -> 8
,E/LightSensor(  872): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  872): mCallbacks.updateBrightness()
,D/DisplayPowerController(  872): getFinalBrightness : 8 -> 8
,E/LightSensor(  872): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  872): mCallbacks.updateBrightness()
,D/DisplayPowerController(  872): getFinalBrightness : 8 -> 8
,E/LightSensor(  872): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  872): mCallbacks.updateBrightness()
,D/DisplayPowerController(  872): getFinalBrightness : 8 -> 8
,D/StatusBar.NetworkController( 1168): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02012b/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020468/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
,D/StatusBar.NetworkController( 1168): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1168): applyOpen
,D/StatusBar.NetworkController( 1168): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1168): applyOpen
,D/StatusBar.NetworkController( 1168): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1168): applyOpen
,D/StatusBar.NetworkController( 1168): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1168): applyOpen
,E/LightSensor(  872): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  872): mCallbacks.updateBrightness()
,D/DisplayPowerController(  872): getFinalBrightness : 8 -> 8
,E/LightSensor(  872): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  872): mCallbacks.updateBrightness()
D/DisplayPowerController(  872): getFinalBrightness : 8 -> 8
,E/LightSensor(  872): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  872): mCallbacks.updateBrightness()
D/DisplayPowerController(  872): getFinalBrightness : 8 -> 8
,E/LightSensor(  872): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  872): mCallbacks.updateBrightness()
D/DisplayPowerController(  872): getFinalBrightness : 8 -> 8
,W/ContextImpl(  872): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> ,
,E/LightSensor(  872): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  872): mCallbacks.updateBrightness()
D/DisplayPowerController(  872): getFinalBrightness : 8 -> 8
,D/StatusBar.NetworkController( 1168): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02012b/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020466/com.android.systemui:drawable/stat_sys_signal_inout mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
,D/StatusBar.NetworkController( 1168): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1168): applyOpen
,D/StatusBar.NetworkController( 1168): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1168): applyOpen
,D/StatusBar.NetworkController( 1168): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1168): applyOpen
,D/StatusBar.NetworkController( 1168): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1168): applyOpen
,E/LightSensor(  872): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
D/AutomaticBrightnessController(  872): mCallbacks.updateBrightness()
D/DisplayPowerController(  872): getFinalBrightness : 8 -> 8
,I/WifiStateMachine(  872): CMD_RSSI_POLL : calculateWifiScore in!
,I/WifiStateMachine(  872): CMD_RSSI_POLL : calculateWifiScore out!
,I/WifiStateMachine(  872): CMD_RSSI_POLL : out!
,E/LightSensor(  872): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  872): mCallbacks.updateBrightness()
,D/DisplayPowerController(  872): getFinalBrightness : 8 -> 8
,E/LightSensor(  872): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  872): mCallbacks.updateBrightness()
D/DisplayPowerController(  872): getFinalBrightness : 8 -> 8
,E/SMD     (  279): DCD ON
,I/ServiceManager(  319): Waiting for service AtCmdFwd...
,E/LightSensor(  872): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  872): mCallbacks.updateBrightness()
,D/DisplayPowerController(  872): getFinalBrightness : 8 -> 8
,I/dhcpcd  ( 7634): wlan0: sending IPv6 Router Solicitation
,I/dhcpcd  ( 7634): wlan0: no IPv6 Routers available
,E/LightSensor(  872): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  872): mCallbacks.updateBrightness()
,D/DisplayPowerController(  872): getFinalBrightness : 8 -> 8
,E/LightSensor(  872): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  872): mCallbacks.updateBrightness()
D/DisplayPowerController(  872): getFinalBrightness : 8 -> 8
,E/LightSensor(  872): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  872): mCallbacks.updateBrightness()
D/DisplayPowerController(  872): getFinalBrightness : 8 -> 8
,E/LightSensor(  872): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  872): mCallbacks.updateBrightness()
,D/DisplayPowerController(  872): getFinalBrightness : 8 -> 8
,D/PreloadUpdateManagerStateMachine( 7121): execute::IDLE:EXECUTE
,D/PreloadUpdateManagerStateMachine( 7121): exit::IDLE
D/PreloadUpdateManagerStateMachine( 7121): entry::CHECK_TIMEOUT_FOR_UPDATE
,D/hcjo    ( 7121): AutoUpdateTriggerManager:IDLE:setInterval:86400000
,D/hcjo    ( 7121): AutoUpdateTriggerManager:IDLE:notifyNextTime
,D/PreloadUpdateManagerStateMachine( 7121): execute::CHECK_TIMEOUT_FOR_UPDATE:NO_TIMED_OUT
,D/PreloadUpdateManagerStateMachine( 7121): exit::CHECK_TIMEOUT_FOR_UPDATE
D/PreloadUpdateManagerStateMachine( 7121): entry::IDLE
,E/LightSensor(  872): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  872): mCallbacks.updateBrightness()
D/DisplayPowerController(  872): getFinalBrightness : 8 -> 8
,I/ServiceManager(  319): Waiting for service AtCmdFwd...
,E/LightSensor(  872): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  872): mCallbacks.updateBrightness()
,D/DisplayPowerController(  872): getFinalBrightness : 8 -> 8
,D/PreloadUpdateManagerStateMachine( 7121): execute::IDLE:EXECUTE
D/PreloadUpdateManagerStateMachine( 7121): exit::IDLE
,D/PreloadUpdateManagerStateMachine( 7121): entry::CHECK_TIMEOUT_FOR_UPDATE
,D/hcjo    ( 7121): AutoUpdateTriggerManager:IDLE:notifyNextTime
D/PreloadUpdateManagerStateMachine( 7121): execute::CHECK_TIMEOUT_FOR_UPDATE:NO_TIMED_OUT
,D/PreloadUpdateManagerStateMachine( 7121): exit::CHECK_TIMEOUT_FOR_UPDATE
,D/PreloadUpdateManagerStateMachine( 7121): entry::IDLE
,E/LightSensor(  872): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  872): mCallbacks.updateBrightness()
,D/DisplayPowerController(  872): getFinalBrightness : 8 -> 8
,E/LightSensor(  872): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  872): mCallbacks.updateBrightness()
,D/DisplayPowerController(  872): getFinalBrightness : 8 -> 8
,D/StatusBar.NetworkController( 1168): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02012b/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020464/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
,D/StatusBar.NetworkController( 1168): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1168): applyOpen
,D/StatusBar.NetworkController( 1168): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1168): applyOpen
D/StatusBar.NetworkController( 1168): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1168): applyOpen
,D/StatusBar.NetworkController( 1168): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1168): applyOpen
,D/FactoryTest( 6449): Not factory mode
,D/FactoryTest( 6449): Not factory mode. isFactoryMode() returend false
,D/MTPRx   ( 6449): DRIVER_TIME_OUT 60s lapsed
,D/MTPRx   ( 6449): still no open session command from host, so toast
,W/ContextImpl( 6449): Calling a method in the system process without a qualified user: android.app.ContextImpl.startActivity:1526 android.content.ContextWrapper.startActivity:337 android.content.ContextWrapper.startActivity:337 com.samsung.android.MtpApplication.MtpReceiver$3.handleMessage:713 android.os.Handler.dispatchMessage:102 
,W/ContextImpl( 6449): Calling a method in the system process without a qualified user: android.app.ContextImpl.startActivity:1538 android.app.ContextImpl.startActivity:1527 android.content.ContextWrapper.startActivity:337 android.content.ContextWrapper.startActivity:337 com.samsung.android.MtpApplication.MtpReceiver$3.handleMessage:713 
,I/Timeline( 6449): Timeline: Activity_launch_request id:com.android.settings time:114357
,E/PersonaManagerService(  872): inState():  stateMachine is null !!
,V/ApplicationPolicy(  872): isApplicationStateBlocked userId 0 pkgname com.android.settings
,I/ActivityManager(  872): START u0 {flg=0x10000000 cmp=com.android.settings/.SettingsReceiverActivity} from uid 1000 on display 0
,D/CustomFrequencyManagerService(  872): acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1958400  uid : 1000  pid : 872  pkgName : ACTIVITY_RESUME_BOOSTER@6
,W/ActivityManager(  872): mDVFSHelper.acquire()
,E/LightSensor(  872): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  872): mCallbacks.updateBrightness()
D/DisplayPowerController(  872): getFinalBrightness : 8 -> 8
,D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
,I/SQLiteSecureOpenHelper( 3556): getWritableDatabase(pwd)
I/SQLiteSecureOpenHelper( 3556): getDatabaseLocked(b,b,pwd)...
,E/MTPRx   ( 6449): started activity for popup
,D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
,D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
,D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
,D/ConnectivityService(  872): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ResourcesManager( 6449): creating new AssetManager and set to /system/priv-app/SecSettings/SecSettings.apk
,W/ResourcesManager( 6449): Asset path '/system/framework/sec_platform_library.jar' does not exist or contains no resources.
,W/ResourcesManager( 6449): Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
W/ResourcesManager( 6449): Asset path '/system/framework/secvisualeffect.jar' does not exist or contains no resources.
W/ResourcesManager( 6449): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 6449): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 6449): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,W/ResourcesManager( 6449): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,E/SettingsReceiverActivity( 6449): PREF_DONT_ASK_AGAIN : true
,D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
,D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
,E/ActivityManager(  872): Invalid thumbnail dimensions: 576x576
,D/InputMethodManagerService(  872): windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,W/InputMethodManagerService(  872): Window already focused, ignoring focus gain of: com.android.internal.view.IInputMethodClient$Stub$Proxy@30692606 attribute=null, token = android.os.BinderProxy@2b605f5a
,I/SQLiteSecureOpenHelper( 3556): getWritableDatabase(pwd)
,I/SQLiteSecureOpenHelper( 3556): getDatabaseLocked(b,b,pwd)...
,D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
,V/BitmapFactory( 6449): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_015.png
,V/BitmapFactory( 6449): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_000.png
,V/BitmapFactory( 6449): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_015.png
,V/BitmapFactory( 6449): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_000.png
,V/BitmapFactory( 6449): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_000.png
,V/BitmapFactory( 6449): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_001.png
,V/BitmapFactory( 6449): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_002.png
,V/BitmapFactory( 6449): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_003.png
,V/BitmapFactory( 6449): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_004.png
,V/BitmapFactory( 6449): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_005.png
,V/BitmapFactory( 6449): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_006.png
,V/BitmapFactory( 6449): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_007.png
,V/BitmapFactory( 6449): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_008.png
,V/BitmapFactory( 6449): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_010.png
,V/BitmapFactory( 6449): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_011.png
,V/BitmapFactory( 6449): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_012.png
,V/BitmapFactory( 6449): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_013.png
,V/BitmapFactory( 6449): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_014.png
,V/BitmapFactory( 6449): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_015.png
,V/BitmapFactory( 6449): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_000.png
,V/BitmapFactory( 6449): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_001.png
,V/BitmapFactory( 6449): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_002.png
,V/BitmapFactory( 6449): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_003.png
,V/BitmapFactory( 6449): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_004.png
,V/BitmapFactory( 6449): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_005.png
,V/BitmapFactory( 6449): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_006.png
,V/BitmapFactory( 6449): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_007.png
,V/BitmapFactory( 6449): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_008.png
,V/BitmapFactory( 6449): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_010.png
,V/BitmapFactory( 6449): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_011.png
,V/BitmapFactory( 6449): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_012.png
,V/BitmapFactory( 6449): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_013.png
,V/BitmapFactory( 6449): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_014.png
,V/BitmapFactory( 6449): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_015.png
,E/LightSensor(  872): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  872): mCallbacks.updateBrightness()
,D/DisplayPowerController(  872): getFinalBrightness : 8 -> 8
,D/SettingsReceiverActivity( 6449): dev.kiessupport is : TRUE
,D/Activity( 6449): performCreate Call secproduct feature valuefalse
D/Activity( 6449): performCreate Call debug elastic valuetrue
,D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
,D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
,D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
,D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
,D/ActivityManager(  872): post active user change for 0
,D/KnoxTimeoutHandler(  872): postActiveUserChange for user 0
D/KnoxTimeoutHandler(  872): handleActiveUserChange for user 0
,D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
,D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
,D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
,I/Timeline( 7436): Timeline: Activity_idle id: android.os.BinderProxy@295c4063 time:114609
,D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1168): value : false
,E/LightSensor(  872): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  872): mCallbacks.updateBrightness()
D/DisplayPowerController(  872): getFinalBrightness : 8 -> 8
,I/ServiceManager(  319): Waiting for service AtCmdFwd...
,E/LightSensor(  872): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  872): mCallbacks.updateBrightness()
D/DisplayPowerController(  872): getFinalBrightness : 8 -> 8
,D/ConnectivityService(  872): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/LightSensor(  872): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  872): mCallbacks.updateBrightness()
D/DisplayPowerController(  872): getFinalBrightness : 8 -> 8
,D/StatusBar.NetworkController( 1168): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02012b/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020468/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
D/StatusBar.NetworkController( 1168): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1168): applyOpen
,D/StatusBar.NetworkController( 1168): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1168): applyOpen
D/StatusBar.NetworkController( 1168): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1168): applyOpen
D/StatusBar.NetworkController( 1168): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1168): applyOpen
,E/LightSensor(  872): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  872): mCallbacks.updateBrightness()
D/DisplayPowerController(  872): getFinalBrightness : 8 -> 8
,I/WifiStateMachine(  872): CMD_RSSI_POLL : calculateWifiScore in!
,I/WifiStateMachine(  872): CMD_RSSI_POLL : calculateWifiScore out!
I/WifiStateMachine(  872): CMD_RSSI_POLL : out!
,E/LightSensor(  872): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  872): mCallbacks.updateBrightness()
D/DisplayPowerController(  872): getFinalBrightness : 8 -> 8
,E/SMD     (  279): DCD ON
,E/LightSensor(  872): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  872): mCallbacks.updateBrightness()
D/DisplayPowerController(  872): getFinalBrightness : 8 -> 8
,I/ServiceManager(  319): Waiting for service AtCmdFwd...
,E/LightSensor(  872): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  872): mCallbacks.updateBrightness()
D/DisplayPowerController(  872): getFinalBrightness : 8 -> 8
,E/LightSensor(  872): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  872): mCallbacks.updateBrightness()
D/DisplayPowerController(  872): getFinalBrightness : 8 -> 8
,E/LightSensor(  872): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  872): mCallbacks.updateBrightness()
D/DisplayPowerController(  872): getFinalBrightness : 8 -> 8
,E/LightSensor(  872): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  872): mCallbacks.updateBrightness()
D/DisplayPowerController(  872): getFinalBrightness : 8 -> 8
,E/LightSensor(  872): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  872): mCallbacks.updateBrightness()
D/DisplayPowerController(  872): getFinalBrightness : 8 -> 8
,E/LightSensor(  872): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  872): mCallbacks.updateBrightness()
D/DisplayPowerController(  872): getFinalBrightness : 8 -> 8
,I/ServiceManager(  319): Waiting for service AtCmdFwd...
,E/LightSensor(  872): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  872): mCallbacks.updateBrightness()
D/DisplayPowerController(  872): getFinalBrightness : 8 -> 8
,E/LightSensor(  872): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  872): mCallbacks.updateBrightness()
D/DisplayPowerController(  872): getFinalBrightness : 8 -> 8
,D/SSRM:m  (  872): SIOP:: AP = 370, PST = 411, CUR = 300
,D/StatusBar.NetworkController( 1168): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02012b/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020466/com.android.systemui:drawable/stat_sys_signal_inout mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
D/StatusBar.NetworkController( 1168): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1168): applyOpen
,D/StatusBar.NetworkController( 1168): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1168): applyOpen
D/StatusBar.NetworkController( 1168): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1168): applyOpen
D/StatusBar.NetworkController( 1168): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1168): applyOpen
,E/LightSensor(  872): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  872): mCallbacks.updateBrightness()
D/DisplayPowerController(  872): getFinalBrightness : 8 -> 8
,D/CustomFrequencyManagerService(  872): releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1958400  uid : 1000  pid : 872  tag : ACTIVITY_RESUME_BOOSTER@6
,W/ActivityManager(  872): mDVFSHelper.release()
,D/CustomFrequencyManagerService(  872): acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1958400  uid : 1000  pid : 872  pkgName : ACTIVITY_RESUME_BOOSTER@10
,E/LightSensor(  872): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  872): mCallbacks.updateBrightness()
D/DisplayPowerController(  872): getFinalBrightness : 8 -> 8
,E/LightSensor(  872): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  872): mCallbacks.updateBrightness()
D/DisplayPowerController(  872): getFinalBrightness : 8 -> 8
,D/CustomFrequencyManagerService(  872): releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1958400  uid : 1000  pid : 872  tag : ACTIVITY_RESUME_BOOSTER@10
,W/Atfwd_Sendcmd(  319): AtCmdFwd service not published, waiting... retryCnt : 1
,E/LightSensor(  872): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  872): mCallbacks.updateBrightness()
,D/DisplayPowerController(  872): getFinalBrightness : 8 -> 8
,E/LightSensor(  872): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  872): mCallbacks.updateBrightness()
,D/DisplayPowerController(  872): getFinalBrightness : 8 -> 8
,E/LightSensor(  872): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  872): mCallbacks.updateBrightness()
,D/DisplayPowerController(  872): getFinalBrightness : 8 -> 8
,D/StatusBar.NetworkController( 1168): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02012b/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020468/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
D/StatusBar.NetworkController( 1168): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1168): applyOpen
,D/StatusBar.NetworkController( 1168): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1168): applyOpen
D/StatusBar.NetworkController( 1168): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1168): applyOpen
D/StatusBar.NetworkController( 1168): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1168): applyOpen
,E/LightSensor(  872): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  872): mCallbacks.updateBrightness()
,D/DisplayPowerController(  872): getFinalBrightness : 8 -> 8
,I/WifiStateMachine(  872): CMD_RSSI_POLL : calculateWifiScore in!
,I/WifiStateMachine(  872): CMD_RSSI_POLL : calculateWifiScore out!
I/WifiStateMachine(  872): CMD_RSSI_POLL : out!
,E/LightSensor(  872): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  872): mCallbacks.updateBrightness()
D/DisplayPowerController(  872): getFinalBrightness : 8 -> 8
,E/SMD     (  279): DCD ON
,E/LightSensor(  872): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  872): mCallbacks.updateBrightness()
,D/DisplayPowerController(  872): getFinalBrightness : 8 -> 8
,I/ActivityManager(  872): Waited long enough for: ServiceRecord{47de691 u0 com.samsung.android.app.galaxyfinder/.tag.LocationTagReadyService}
,E/LightSensor(  872): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  872): mCallbacks.updateBrightness()
D/DisplayPowerController(  872): getFinalBrightness : 8 -> 8
,E/LightSensor(  872): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  872): mCallbacks.updateBrightness()
,I/art     (  872): Explicit concurrent mark sweep GC freed 47243(2MB) AllocSpace objects, 13(2MB) LOS objects, 30% free, 36MB/52MB, paused 1.615ms total 117.204ms
,D/DisplayPowerController(  872): getFinalBrightness : 8 -> 8
,E/LightSensor(  872): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  872): mCallbacks.updateBrightness()
,D/DisplayPowerController(  872): getFinalBrightness : 8 -> 8
,D/StatusBar.NetworkController( 1168): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02012b/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020464/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
D/StatusBar.NetworkController( 1168): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1168): applyOpen
,D/StatusBar.NetworkController( 1168): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1168): applyOpen
D/StatusBar.NetworkController( 1168): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1168): applyOpen
D/StatusBar.NetworkController( 1168): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1168): applyOpen
,V/AlarmManager(  872): waitForAlarm result :4
,E/LightSensor(  872): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  872): mCallbacks.updateBrightness()
,D/DisplayPowerController(  872): getFinalBrightness : 8 -> 8
,D/BatteryService(  872): level:100, scale:100, status:5, health:2, present:true, voltage: 4381, temperature: 284, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  872): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
D/BatteryService(  872): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  872):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  872): Plugged
I/MotionRecognitionService(  872): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1168): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1168): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1168):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3234): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3234): Disconnected process message: 10
,D/BatteryMeterView( 1168): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1168): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1168): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/LightSensor(  872): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  872): mCallbacks.updateBrightness()
D/DisplayPowerController(  872): getFinalBrightness : 8 -> 8
,E/LightSensor(  872): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  872): mCallbacks.updateBrightness()
,D/DisplayPowerController(  872): getFinalBrightness : 8 -> 8
,E/LightSensor(  872): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  872): mCallbacks.updateBrightness()
,D/DisplayPowerController(  872): getFinalBrightness : 8 -> 8
,V/GLSActivity( 1676): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1676): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
I/GLSUser ( 1676): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1676): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1676): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1676): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/Finsky  ( 6658): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,D/Finsky  ( 6658): [1] 5.onFinished: Installation state replication failed.
,D/Finsky  ( 6658): [1] 5.onFinished: Scheduling replication attempt 3.
,E/LightSensor(  872): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  872): mCallbacks.updateBrightness()
D/DisplayPowerController(  872): getFinalBrightness : 8 -> 8
,D/StatusBar.NetworkController( 1168): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02012b/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020468/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
,D/StatusBar.NetworkController( 1168): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1168): applyOpen
,D/StatusBar.NetworkController( 1168): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1168): applyOpen
,D/StatusBar.NetworkController( 1168): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1168): applyOpen
,D/StatusBar.NetworkController( 1168): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1168): applyOpen
,E/LightSensor(  872): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  872): mCallbacks.updateBrightness()
D/DisplayPowerController(  872): getFinalBrightness : 8 -> 8
,E/LightSensor(  872): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  872): mCallbacks.updateBrightness()
D/DisplayPowerController(  872): getFinalBrightness : 8 -> 8
,E/LightSensor(  872): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  872): mCallbacks.updateBrightness()
,D/DisplayPowerController(  872): getFinalBrightness : 8 -> 8
,E/LightSensor(  872): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  872): mCallbacks.updateBrightness()
D/DisplayPowerController(  872): getFinalBrightness : 8 -> 8
,E/LightSensor(  872): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  872): mCallbacks.updateBrightness()
,D/DisplayPowerController(  872): getFinalBrightness : 8 -> 8
,E/LightSensor(  872): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  872): mCallbacks.updateBrightness()
,D/DisplayPowerController(  872): getFinalBrightness : 8 -> 8
,D/StatusBar.NetworkController( 1168): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02012b/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020464/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
D/StatusBar.NetworkController( 1168): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1168): applyOpen
,D/StatusBar.NetworkController( 1168): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1168): applyOpen
,D/StatusBar.NetworkController( 1168): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1168): applyOpen
,D/StatusBar.NetworkController( 1168): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1168): applyOpen
,V/AlarmManager(  872): waitForAlarm result :4
,E/LightSensor(  872): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  872): mCallbacks.updateBrightness()
D/DisplayPowerController(  872): getFinalBrightness : 8 -> 8
,D/ConnectivityService(  872): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/WifiStateMachine(  872): CMD_RSSI_POLL : calculateWifiScore in!
,I/WifiStateMachine(  872): CMD_RSSI_POLL : calculateWifiScore out!
I/WifiStateMachine(  872): CMD_RSSI_POLL : out!
,E/LightSensor(  872): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  872): mCallbacks.updateBrightness()
,D/DisplayPowerController(  872): getFinalBrightness : 8 -> 8
,E/SMD     (  279): DCD ON
,E/LightSensor(  872): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  872): mCallbacks.updateBrightness()
,D/DisplayPowerController(  872): getFinalBrightness : 8 -> 8
,E/LightSensor(  872): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  872): mCallbacks.updateBrightness()
,D/DisplayPowerController(  872): getFinalBrightness : 8 -> 8
,E/LightSensor(  872): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  872): mCallbacks.updateBrightness()
D/DisplayPowerController(  872): getFinalBrightness : 8 -> 8
,E/LightSensor(  872): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  872): mCallbacks.updateBrightness()
D/DisplayPowerController(  872): getFinalBrightness : 8 -> 8
,D/StatusBar.NetworkController( 1168): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02012b/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020466/com.android.systemui:drawable/stat_sys_signal_inout mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
D/StatusBar.NetworkController( 1168): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1168): applyOpen
,D/StatusBar.NetworkController( 1168): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1168): applyOpen
D/StatusBar.NetworkController( 1168): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1168): applyOpen
,D/StatusBar.NetworkController( 1168): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1168): applyOpen
,E/LightSensor(  872): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  872): mCallbacks.updateBrightness()
,D/DisplayPowerController(  872): getFinalBrightness : 8 -> 8
,E/LightSensor(  872): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  872): mCallbacks.updateBrightness()
,D/DisplayPowerController(  872): getFinalBrightness : 8 -> 8
,I/ServiceManager(  319): Waiting for service AtCmdFwd...
,E/LightSensor(  872): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  872): mCallbacks.updateBrightness()
,D/DisplayPowerController(  872): getFinalBrightness : 8 -> 8
,E/LightSensor(  872): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  872): mCallbacks.updateBrightness()
D/DisplayPowerController(  872): getFinalBrightness : 8 -> 8
,E/LightSensor(  872): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  872): mCallbacks.updateBrightness()
,D/DisplayPowerController(  872): getFinalBrightness : 8 -> 8
,D/StatusBar.NetworkController( 1168): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02012b/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020464/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
,D/StatusBar.NetworkController( 1168): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1168): applyOpen
,D/StatusBar.NetworkController( 1168): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1168): applyOpen
D/StatusBar.NetworkController( 1168): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1168): applyOpen
D/StatusBar.NetworkController( 1168): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1168): applyOpen
,E/LightSensor(  872): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  872): mCallbacks.updateBrightness()
,D/DisplayPowerController(  872): getFinalBrightness : 8 -> 8
,E/LightSensor(  872): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  872): mCallbacks.updateBrightness()
,D/DisplayPowerController(  872): getFinalBrightness : 8 -> 8
,E/LightSensor(  872): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  872): mCallbacks.updateBrightness()
D/DisplayPowerController(  872): getFinalBrightness : 8 -> 8
,I/ServiceManager(  319): Waiting for service AtCmdFwd...
,E/LightSensor(  872): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  872): mCallbacks.updateBrightness()
D/DisplayPowerController(  872): getFinalBrightness : 8 -> 8
,E/LightSensor(  872): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  872): mCallbacks.updateBrightness()
D/DisplayPowerController(  872): getFinalBrightness : 8 -> 8
,E/LightSensor(  872): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  872): mCallbacks.updateBrightness()
D/DisplayPowerController(  872): getFinalBrightness : 8 -> 8
,E/LightSensor(  872): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  872): mCallbacks.updateBrightness()
D/DisplayPowerController(  872): getFinalBrightness : 8 -> 8
,I/WifiStateMachine(  872): CMD_RSSI_POLL : calculateWifiScore in!
,I/WifiStateMachine(  872): CMD_RSSI_POLL : calculateWifiScore out!
I/WifiStateMachine(  872): CMD_RSSI_POLL : out!
,E/SMD     (  279): DCD ON
,E/LightSensor(  872): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  872): mCallbacks.updateBrightness()
D/DisplayPowerController(  872): getFinalBrightness : 8 -> 8
,I/ServiceManager(  319): Waiting for service AtCmdFwd...
,E/LightSensor(  872): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  872): mCallbacks.updateBrightness()
,D/DisplayPowerController(  872): getFinalBrightness : 8 -> 8
,E/LightSensor(  872): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  872): mCallbacks.updateBrightness()
,D/DisplayPowerController(  872): getFinalBrightness : 8 -> 8
,E/LightSensor(  872): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  872): mCallbacks.updateBrightness()
,D/DisplayPowerController(  872): getFinalBrightness : 8 -> 8
,E/LightSensor(  872): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  872): mCallbacks.updateBrightness()
,D/DisplayPowerController(  872): getFinalBrightness : 8 -> 8
,E/LightSensor(  872): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  872): mCallbacks.updateBrightness()
,D/DisplayPowerController(  872): getFinalBrightness : 8 -> 8
,E/LightSensor(  872): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  872): mCallbacks.updateBrightness()
,D/DisplayPowerController(  872): getFinalBrightness : 8 -> 8
,I/ServiceManager(  319): Waiting for service AtCmdFwd...
,E/LightSensor(  872): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  872): mCallbacks.updateBrightness()
,D/DisplayPowerController(  872): getFinalBrightness : 8 -> 8
,E/LightSensor(  872): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  872): mCallbacks.updateBrightness()
,D/DisplayPowerController(  872): getFinalBrightness : 8 -> 8
,E/LightSensor(  872): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  872): mCallbacks.updateBrightness()
D/DisplayPowerController(  872): getFinalBrightness : 8 -> 8
,E/LightSensor(  872): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  872): mCallbacks.updateBrightness()
D/DisplayPowerController(  872): getFinalBrightness : 8 -> 8
,E/LightSensor(  872): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  872): mCallbacks.updateBrightness()
,D/DisplayPowerController(  872): getFinalBrightness : 8 -> 8
,I/ServiceManager(  319): Waiting for service AtCmdFwd...
,E/LightSensor(  872): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  872): mCallbacks.updateBrightness()
D/DisplayPowerController(  872): getFinalBrightness : 8 -> 8
,E/LightSensor(  872): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  872): mCallbacks.updateBrightness()
D/DisplayPowerController(  872): getFinalBrightness : 8 -> 8
,E/LightSensor(  872): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  872): mCallbacks.updateBrightness()
,D/DisplayPowerController(  872): getFinalBrightness : 8 -> 8
,D/SSRM:m  (  872): SIOP:: AP = 340, PST = 398, CUR = 300
,D/X       (  872): broadcastSiopLevelIntent:: currentSiopLevel = -1
,D/ContentApp( 1225):  LEVEL : -1
,E/TranscodeReceiver( 7139): onReceive : android.intent.action.CHECK_SIOP_LEVEL
D/TranscodeReceiver( 7139):  SIOP_LEVEL: -1
,E/LightSensor(  872): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  872): mCallbacks.updateBrightness()
D/DisplayPowerController(  872): getFinalBrightness : 8 -> 8
,D/StatusBar.NetworkController( 1168): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02012b/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020466/com.android.systemui:drawable/stat_sys_signal_inout mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
,D/StatusBar.NetworkController( 1168): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1168): applyOpen
D/StatusBar.NetworkController( 1168): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1168): applyOpen
D/StatusBar.NetworkController( 1168): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1168): applyOpen
,D/StatusBar.NetworkController( 1168): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1168): applyOpen
,E/LightSensor(  872): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  872): mCallbacks.updateBrightness()
,D/DisplayPowerController(  872): getFinalBrightness : 8 -> 8
,I/WifiStateMachine(  872): CMD_RSSI_POLL : calculateWifiScore in!
,I/WifiStateMachine(  872): CMD_RSSI_POLL : calculateWifiScore out!
I/WifiStateMachine(  872): CMD_RSSI_POLL : out!
,E/SMD     (  279): DCD ON
,E/LightSensor(  872): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  872): mCallbacks.updateBrightness()
,D/DisplayPowerController(  872): getFinalBrightness : 8 -> 8
,W/Atfwd_Sendcmd(  319): AtCmdFwd service not published, waiting... retryCnt : 2
,E/LightSensor(  872): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  872): mCallbacks.updateBrightness()
,D/DisplayPowerController(  872): getFinalBrightness : 8 -> 8
,E/LightSensor(  872): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  872): mCallbacks.updateBrightness()
,D/DisplayPowerController(  872): getFinalBrightness : 8 -> 8
,E/LightSensor(  872): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  872): mCallbacks.updateBrightness()
,D/DisplayPowerController(  872): getFinalBrightness : 8 -> 8
,D/StatusBar.NetworkController( 1168): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02012b/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020464/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
,D/StatusBar.NetworkController( 1168): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1168): applyOpen
,D/StatusBar.NetworkController( 1168): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1168): applyOpen
D/StatusBar.NetworkController( 1168): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1168): applyOpen
D/StatusBar.NetworkController( 1168): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1168): applyOpen
,E/LightSensor(  872): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  872): mCallbacks.updateBrightness()
D/DisplayPowerController(  872): getFinalBrightness : 8 -> 8
,E/LightSensor(  872): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  872): mCallbacks.updateBrightness()
,D/DisplayPowerController(  872): getFinalBrightness : 8 -> 8
,E/LightSensor(  872): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  872): mCallbacks.updateBrightness()
,D/DisplayPowerController(  872): getFinalBrightness : 8 -> 8
,E/LightSensor(  872): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  872): mCallbacks.updateBrightness()
,D/DisplayPowerController(  872): getFinalBrightness : 8 -> 8
,E/LightSensor(  872): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  872): mCallbacks.updateBrightness()
,D/DisplayPowerController(  872): getFinalBrightness : 8 -> 8
,E/LightSensor(  872): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  872): mCallbacks.updateBrightness()
,D/DisplayPowerController(  872): getFinalBrightness : 8 -> 8
,E/LightSensor(  872): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  872): mCallbacks.updateBrightness()
,D/DisplayPowerController(  872): getFinalBrightness : 8 -> 8
,D/BatteryService(  872): level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 284, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
D/BatteryService(  872): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
D/BatteryService(  872): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  872):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
I/MotionRecognitionService(  872): Plugged
I/MotionRecognitionService(  872): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1168): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1168): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1168):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3234): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3234): Disconnected process message: 10
,D/BatteryMeterView( 1168): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1168): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1168): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/LightSensor(  872): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  872): mCallbacks.updateBrightness()
D/DisplayPowerController(  872): getFinalBrightness : 8 -> 8
,E/LightSensor(  872): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  872): mCallbacks.updateBrightness()
,D/DisplayPowerController(  872): getFinalBrightness : 8 -> 8
,E/LightSensor(  872): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  872): mCallbacks.updateBrightness()
,D/DisplayPowerController(  872): getFinalBrightness : 8 -> 8
,E/LightSensor(  872): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  872): mCallbacks.updateBrightness()
,D/DisplayPowerController(  872): getFinalBrightness : 8 -> 8
,E/LightSensor(  872): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  872): mCallbacks.updateBrightness()
D/DisplayPowerController(  872): getFinalBrightness : 8 -> 8
,I/WifiStateMachine(  872): CMD_RSSI_POLL : calculateWifiScore in!
,E/LightSensor(  872): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  872): mCallbacks.updateBrightness()
D/DisplayPowerController(  872): getFinalBrightness : 8 -> 8
,I/WifiStateMachine(  872): CMD_RSSI_POLL : calculateWifiScore out!
I/WifiStateMachine(  872): CMD_RSSI_POLL : out!
,E/SMD     (  279): DCD ON
,E/LightSensor(  872): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  872): mCallbacks.updateBrightness()
D/DisplayPowerController(  872): getFinalBrightness : 8 -> 8
,E/LightSensor(  872): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  872): mCallbacks.updateBrightness()
,D/DisplayPowerController(  872): getFinalBrightness : 8 -> 8
,E/LightSensor(  872): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  872): mCallbacks.updateBrightness()
,D/DisplayPowerController(  872): getFinalBrightness : 8 -> 8
,D/PowerManagerService(  872): [s] UserActivityState : 1 -> 2
,D/DisplayPowerController(  872): getFinalBrightness : 1 -> 1
,D/PowerManagerService(  872): [s] DisplayPowerCallbacks : onStateChanged()
,D/lights  (  872): lcd : 3 +
,D/lights  (  872): lcd : 3 -
,D/lights  (  872): lcd : 1 +
D/DisplayPowerController(  872): getFinalBrightness : 1 -> 1
,D/lights  (  872): lcd : 1 -
,D/DisplayPowerController(  872): getFinalBrightness : 1 -> 1
,E/LightSensor(  872): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  872): mCallbacks.updateBrightness()
D/DisplayPowerController(  872): getFinalBrightness : 1 -> 1
,E/LightSensor(  872): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  872): mCallbacks.updateBrightness()
,D/DisplayPowerController(  872): getFinalBrightness : 1 -> 1
,E/LightSensor(  872): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  872): mCallbacks.updateBrightness()
D/DisplayPowerController(  872): getFinalBrightness : 1 -> 1
,E/LightSensor(  872): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
D/AutomaticBrightnessController(  872): mCallbacks.updateBrightness()
D/DisplayPowerController(  872): getFinalBrightness : 1 -> 1
,W/ContextImpl(  872): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/LightSensor(  872): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  872): mCallbacks.updateBrightness()
,D/DisplayPowerController(  872): getFinalBrightness : 1 -> 1
,E/LightSensor(  872): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  872): mCallbacks.updateBrightness()
,D/DisplayPowerController(  872): getFinalBrightness : 1 -> 1
,E/LightSensor(  872): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  872): mCallbacks.updateBrightness()
,D/DisplayPowerController(  872): getFinalBrightness : 1 -> 1
,D/StatusBar.NetworkController( 1168): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02012b/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020466/com.android.systemui:drawable/stat_sys_signal_inout mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
D/StatusBar.NetworkController( 1168): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1168): applyOpen
,D/StatusBar.NetworkController( 1168): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1168): applyOpen
,D/StatusBar.NetworkController( 1168): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1168): applyOpen
D/StatusBar.NetworkController( 1168): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1168): applyOpen
,E/LightSensor(  872): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  872): mCallbacks.updateBrightness()
,D/DisplayPowerController(  872): getFinalBrightness : 1 -> 1
,E/LightSensor(  872): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  872): mCallbacks.updateBrightness()
,D/DisplayPowerController(  872): getFinalBrightness : 1 -> 1
,E/LightSensor(  872): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  872): mCallbacks.updateBrightness()
D/DisplayPowerController(  872): getFinalBrightness : 1 -> 1
,E/LightSensor(  872): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  872): mCallbacks.updateBrightness()
,D/DisplayPowerController(  872): getFinalBrightness : 1 -> 1
,E/LightSensor(  872): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  872): mCallbacks.updateBrightness()
,D/DisplayPowerController(  872): getFinalBrightness : 1 -> 1
,E/LightSensor(  872): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  872): mCallbacks.updateBrightness()
,D/DisplayPowerController(  872): getFinalBrightness : 1 -> 1
,D/StatusBar.NetworkController( 1168): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02012b/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020464/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
,D/StatusBar.NetworkController( 1168): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1168): applyOpen
,D/StatusBar.NetworkController( 1168): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1168): applyOpen
,D/StatusBar.NetworkController( 1168): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1168): applyOpen
,D/StatusBar.NetworkController( 1168): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1168): applyOpen
,I/WifiStateMachine(  872): CMD_RSSI_POLL : calculateWifiScore in!
,I/WifiStateMachine(  872): CMD_RSSI_POLL : calculateWifiScore out!
,I/WifiStateMachine(  872): CMD_RSSI_POLL : out!
,E/LightSensor(  872): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  872): mCallbacks.updateBrightness()
E/SMD     (  279): DCD ON
,D/DisplayPowerController(  872): getFinalBrightness : 1 -> 1
,E/Watchdog(  872): !@Sync 4
,E/LightSensor(  872): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  872): mCallbacks.updateBrightness()
,D/DisplayPowerController(  872): getFinalBrightness : 1 -> 1
,E/LightSensor(  872): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  872): mCallbacks.updateBrightness()
,D/DisplayPowerController(  872): getFinalBrightness : 1 -> 1
,E/LightSensor(  872): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  872): mCallbacks.updateBrightness()
,D/DisplayPowerController(  872): getFinalBrightness : 1 -> 1
,E/LightSensor(  872): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  872): mCallbacks.updateBrightness()
,D/DisplayPowerController(  872): getFinalBrightness : 1 -> 1
,E/LightSensor(  872): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  872): mCallbacks.updateBrightness()
,D/DisplayPowerController(  872): getFinalBrightness : 1 -> 1
,E/LightSensor(  872): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  872): mCallbacks.updateBrightness()
,D/DisplayPowerController(  872): getFinalBrightness : 1 -> 1
,E/LightSensor(  872): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  872): mCallbacks.updateBrightness()
,D/DisplayPowerController(  872): getFinalBrightness : 1 -> 1
,E/LightSensor(  872): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  872): mCallbacks.updateBrightness()
,D/DisplayPowerController(  872): getFinalBrightness : 1 -> 1
,E/LightSensor(  872): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  872): mCallbacks.updateBrightness()
,D/DisplayPowerController(  872): getFinalBrightness : 1 -> 1
,E/LightSensor(  872): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  872): mCallbacks.updateBrightness()
,D/DisplayPowerController(  872): getFinalBrightness : 1 -> 1
,E/LightSensor(  872): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  872): mCallbacks.updateBrightness()
D/DisplayPowerController(  872): getFinalBrightness : 1 -> 1
,I/art     ( 1676): Explicit concurrent mark sweep GC freed 31346(1901KB) AllocSpace objects, 22(1782KB) LOS objects, 40% free, 17MB/29MB, paused 681us total 41.873ms
,E/LightSensor(  872): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  872): mCallbacks.updateBrightness()
,D/DisplayPowerController(  872): getFinalBrightness : 1 -> 1
,E/LightSensor(  872): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  872): mCallbacks.updateBrightness()
,D/DisplayPowerController(  872): getFinalBrightness : 1 -> 1
,E/LightSensor(  872): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  872): mCallbacks.updateBrightness()
D/DisplayPowerController(  872): getFinalBrightness : 1 -> 1
,E/LightSensor(  872): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  872): mCallbacks.updateBrightness()
,D/DisplayPowerController(  872): getFinalBrightness : 1 -> 1
,D/StatusBar.NetworkController( 1168): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02012b/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020468/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
,E/LightSensor(  872): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  872): mCallbacks.updateBrightness()
,D/DisplayPowerController(  872): getFinalBrightness : 1 -> 1
,D/StatusBar.NetworkController( 1168): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1168): applyOpen
,D/StatusBar.NetworkController( 1168): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1168): applyOpen
,D/StatusBar.NetworkController( 1168): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1168): applyOpen
D/StatusBar.NetworkController( 1168): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1168): applyOpen
,E/SMD     (  279): DCD ON
,I/WifiStateMachine(  872): CMD_RSSI_POLL : calculateWifiScore in!
,I/WifiStateMachine(  872): CMD_RSSI_POLL : calculateWifiScore out!
,I/WifiStateMachine(  872): CMD_RSSI_POLL : out!
,E/LightSensor(  872): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  872): mCallbacks.updateBrightness()
D/DisplayPowerController(  872): getFinalBrightness : 1 -> 1
,E/LightSensor(  872): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  872): mCallbacks.updateBrightness()
,D/DisplayPowerController(  872): getFinalBrightness : 1 -> 1
,E/LightSensor(  872): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  872): mCallbacks.updateBrightness()
,D/DisplayPowerController(  872): getFinalBrightness : 1 -> 1
,D/PowerManagerService(  872): [s] UserActivityState : 2 -> 4
,I/PowerManagerService(  872): Nap time (uid 1000)...
,I/PowerManagerService(  872): !@[ps] Screen__Off(2) : 
I/PowerManagerService(  872): Going to sleep due to screen timeout (uid 1000)...
,D/PowerManagerService(  872): [PWL] sb acquire: PowerManagerService.Broadcasts
,D/PowerManagerService(  872): SecHardwareInterface.setBatteryADC : false
D/InputManager-JNI(  872): setDeviceInteractive: 0
,D/PowerManagerService(  872): handleSandman : startDream()
,D/InputManager-JNI(  872): sysfs_write +: /sys/class/input/event2/device/enabled: 0
,E/PowerManagerService(  872): handleSandman : startDreaming, but isDreaming false
,I/PowerManagerService(  872): Sleeping (uid 1000)...
,D/PowerManagerService(  872): [s] UserActivityState : 4 -> 0
,D/PowerManagerService(  872): [input device light] setInputDeviceLightOn is called : 0
,D/PowerManagerService(  872): [input device light] handleInputDeviceLightOff
,I/SurfaceFlinger(  249): id=17 createSurf (1080x1920),2 flag=404, ColorFade
,D/InputManager-JNI(  872): sysfs_write +: /sys/class/input/event1/device/enabled: 0
,D/InputManager-JNI(  872): sysfs_write -: /sys/class/input/event2/device/enabled: 0
,E/LightSensor(  872): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/InputManager-JNI(  872): sysfs_write -: /sys/class/input/event1/device/enabled: 0
,D/SContextService(  872): 	.unregisterCallback : 1, client=
,D/SContextService(  872): unregisterCallback() : Listener = android.hardware.scontext.SContextService$Listener@1df672f7, Service = Auto Rotation, used = 1
,W/CAE     (  872): unregisterCallback(ContextAwareService.java:199) - [unregi 01] Mutex is locked for AUTO_ROTATION
,V/CAE     (  872): stop(ContextProvider.java:149)
,V/CAE     (  872): clear(AutoRotationRunner.java:182)
,V/CAE     (  872): disable(AutoRotationRunner.java:171)
,I/CAE     (  872): sendCmdToSensorHub(SensorHubCommManager.java:144) - -78, 7, 0, 0,
,D/SensorHubManager(  872): SendSensorHubData: send data = -78, 7, 0, 0
,D/Sensorhubs(  293): sendContextData: -78, 7, 0, 0
,D/CAE     (  872): getFaultDetectionResult(AutoRotationRunner.java:195) - true
,I/CAE     (  872): notifyCmdProcessResultObserver(ContextProvider.java:617) - CheckResult = 0, Cause = Success
,D/SSRM:m  (  872): SIOP:: AP = 330, PST = 383, CUR = 300
,D/CAE     (  872): doCommendProcess(ContextAwareService.java:314) - complete notify the operation result.
,I/CAE     (  872): displayUsedCountForService(ContextAwareService.java:406) - totalCnt = 0, serviceCount = 0, subCollectionCount = 0
,D/CAE     (  872): showListenerList(ContextAwareService.java:247) - ===== Context Aware Service List =====
,W/CAE     (  872): unregisterCallback(ContextAwareService.java:234) - [unregi 02] Mutex is unlocked for AUTO_ROTATION
,D/SContextService(  872): removeSContextService() : service = Auto Rotation
,D/SContextService(  872): ===== SContext Service List =====
D/SContextManager(  872):   .unregisterListener : listener = com.android.internal.policy.impl.WindowOrientationListener$SContextListenerImpl@18d8fb7a, service=Auto Rotation
,D/KeyguardViewMediator( 1168): onScreenTurnedOff(3)
I/KeyguardEffectViewController( 1168): *** KeyguardEffectView getInstanceIfExists ***
D/KeyguardEffectViewController( 1168): changeWallpaperByScreenOff()
D/KeyguardViewMediator( 1168): notifyScreenOffLocked
,D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
D/KeyguardViewMediator( 1168): timeout : 5000
,D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
,I/SQLiteSecureOpenHelper( 3556): getWritableDatabase(pwd)
I/SQLiteSecureOpenHelper( 3556): getDatabaseLocked(b,b,pwd)...
,D/DisplayPowerController(  872): ColorFade: onAnimationStart
D/DisplayPowerController(  872): getFinalBrightness : 8 -> 0
,D/AutomaticBrightnessController(  872): mCallbacks.updateBrightness()
D/DisplayPowerController(  872): getFinalBrightness : 8 -> 0
,D/DisplayPowerController(  872): getFinalBrightness : 8 -> 0
D/lights  (  872): lcd : 0 +
,D/KeyguardViewMediator( 1168): setting alarm to turn off keyguard, seq = 2
D/KeyguardViewMediator( 1168): handleNotifyScreenOff
,D/lights  (  872): lcd : 0 -
,D/LightsService(  872): [api] [SvcLED] setFlashing :: id = 3, color = 0, mode = 14, onMS = 0, offMS = 0,  (uid: 1000 pid: 872) 
D/LightsService(  872): [SvcLED] setSvcLedStateLocked:: SvcLEDState : 0x0 -> 0x40 | SvcLED(id=3) set On
,D/LightsService(  872): [SvcLED]  onSensorChanged::light value = 0
,D/SensorManager(  872): registerListener :: 6, TMG399X RGB Sensor, 200000, 0,  
D/BatteryService(  872): turn on LED for fully charged
,D/SensorManager(  872): unregisterListener ::   
D/lights  (  872): led_pattern : 5 +
,D/lights  (  872): led_pattern : 5 -
D/LightsService(  872): [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=3) maintains its priority right
,I/CAE     (  872): handleMessage(CaPowerManager.java:182) - AP_SLEEP
,I/CAE     (  872): updateApPowerStatus(SensorHubParserProvider.java:421) - AP_SLEEP
I/CAE     (  872): sendCmdToSensorHub(SensorHubCommManager.java:144) - -76, 13, -46, 0,
D/SensorHubManager(  872): SendSensorHubData: send data = -76, 13, -46, 0
,D/Sensorhubs(  293): sendContextData: -76, 13, -46, 0
,I/CAE     (  872): sendCmdToSensorHub(SensorHubCommManager.java:144) - -63, 14, 23, 5, 32,
D/SensorHubManager(  872): SendSensorHubData: send data = -63, 14, 23, 5, 32
,D/Sensorhubs(  293): sendContextData: -63, 14, 23, 5, 32
,E/LightSensor(  872): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  872): mCallbacks.updateBrightness()
D/DisplayPowerController(  872): getFinalBrightness : 8 -> 0
,D/MotionRecognitionService(  872):   mReceiver.onReceive : ACTION_SCREEN_OFF
,E/MotionRecognitionService(  872):  handler : SCREEN_OFF end 
,D/NotificationService(  872): ACTION_SCREEN_OFF
,D/LightsService(  872): [api] [SvcLED] setFlashing :: id = 4, color = ffffffff, mode = 12, onMS = 500, offMS = 2000,  (uid: 1000 pid: 872) 
D/LightsService(  872): [SvcLED] setSvcLedStateLocked:: SvcLEDState : 0x40 -> 0x42 | SvcLED(id=4) set On
,D/LightsService(  872): [SvcLED]  onSensorChanged::light value = 0
,D/WifiStateMachine(  872): backgroundScan enabled=false startBackgroundScanIfNeeded:false
E/WifiStateMachine(  872): handleScreenStateChanged Exit: false
,E/WifiStateMachine(  872): setSuspendOptimizationsNative: 4 true -want true stack:setSuspendOptimizationsNative - access$16800 - processMessage - processMsg
,E/WifiStateMachine(  872): setSuspendOptimizationsNative do it 4 true stack:setSuspendOptimizationsNative - access$16800 - processMessage - processMsg
E/native  (  872): do suspend true
,D/SensorManager(  872): registerListener :: 6, TMG399X RGB Sensor, 200000, 0,  
,D/SensorManager(  872): unregisterListener ::   
D/LightsService(  872): [SvcLED]  setSvcLedLightLocked :: priority changed! SvcLED(id=3) OUT; SvcLED(id=4) IN
,D/audio_hw_primary(  285): adev_set_parameters: enter: screen_state=off
,V/voice   (  285): voice_set_parameters: enter: screen_state=off
V/voice   (  285): voice_set_parameters: exit with code(-2)
V/msm8974_platform(  285): platform_set_parameters: enter: screen_state=off
V/msm8974_platform(  285): platform_set_parameters: exit with code(-2)
,D/audio_hw_hfp(  285): audio_extn_hfp_set_parameters: enter
V/audio_hw_primary(  285): adev_set_parameters: exit
,I/SecExternalDisplayIntents_Java(  872): Intent Recieved ..  -android.intent.action.SCREEN_OFFBroadCast Map value - 18
,D/IpRemoteDisplayController(  872): intent received android.intent.action.SCREEN_OFF
D/IpRemoteDisplayController(  872): Bridge Server is not available
,D/VolumePanel( 1168): mCoverBroadcastReceiver: Screen OFF start
,D/VolumePanel( 1168): mCoverBroadcastReceiver : call onDismissSafeVolumeWarning() #1
,D/VolumePanel( 1168): mCoverBroadcastReceiver: Screen OFF end
D/VolumePanel( 1168): mCoverBroadcastReceiver: onReceive() end : intent=Intent { act=android.intent.action.SCREEN_OFF flg=0x50000010 (has extras) }
,D/PersonaManagerService(  872): ACTION_SCREEN_OFF onReceive
,D/PersonaManagerServiceHandler(  872): MSG_ACTION_SCREEN_OFF called
,D/NfcService( 1459): call the applyRotuiing
,D/STATUSBAR-PhoneStatusBar( 1168):      ACTION_SCREEN_OFF is finished!!!! 
,E/StatusBar( 1168): onReceive : Intent.ACTION_SCREEN_OFF
D/Recents_AlternateRecentsComponent( 1168): dismissHelpPopup 
,D/accuweather( 2142): [KK AccuPhone]>>> SWW:66 [0:0] action : androidintentactionSCREEN_OFF
,D/accuweather( 2142): [KK AccuPhone]>>> SWW:467 [0:0] stopRefreshIcon : 1
,D/accuweather( 2142): [KK AccuPhone]>>> SWW:364 [0:0] getWeatherRenderer : 1
,D/ConnectivityService(  872): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
,D/DisplayPowerState(  872): !@ ColorFade entry
D/DisplayPowerController(  872): ColorFade: onAnimationEnd
,D/AutomaticBrightnessController(  872): [DAB] setLightSensorEnabled : Send Update unregisterListener mLightSensor
I/AutomaticBrightnessController(  872): [DAB] fileWriteInt : /sys/class/tcon/tcon/auto_br  value : 0
,I/AutomaticBrightnessController(  872): [DAB] fileWriteInt : /sys/class/backlight/panel/auto_brightness  value : 0
D/AutomaticBrightnessController(  872): [DAB] setLightSensorEnabled : unregisterListener mLightSensor
E/LightSensor(  872): Light old sensor_state 8705, new sensor_state : 8193 en : 0
,W/ActivityManager(  872): getTasks: caller 10086 does not hold GET_TASKS; limiting output
,W/ActivityManager(  872): getTasks: caller 10086 does not hold GET_TASKS; limiting output
,D/PowerManagerService(  872): [PWL] sb release: PowerManagerService.Broadcasts
,D/SensorManager(  872): unregisterListener ::   
E/Sensors (  872): Acc old sensor_state 8193, new sensor_state : 8192 en : 0
,D/SensorManager(  872): unregisterListener ::   
,D/SSRM:m  (  872): SIOP:: AP = 330, PST = 372, CUR = 300
,D/DisplayPowerController(  872): getFinalBrightness : 0 -> 0
,I/DisplayManagerService(  872): Display device changed: DisplayDeviceInfo{"Built-in Screen": 1080 x 1920, 60.0 fps, supportedRefreshRates [60.0], density 480, 422.03 x 424.069 dpi, appVsyncOff 0, presDeadline 17666667, touch INTERNAL, rotation 0, type BUILT_IN, state OFF, FLAG_DEFAULT_DISPLAY, FLAG_ROTATES_WITH_CONTENT, FLAG_SECURE, FLAG_SUPPORTS_PROTECTED_BUFFERS}
,D/SurfaceFlinger(  249): Set power mode=0, type=0 flinger=0xb6a62000
D/qdhwcomposer(  249): hwc_blank: Blanking display: 0
V/ActivityManager(  872): Display changed displayId=0
,D/DisplayPowerController(  872): getFinalBrightness : 0 -> 0
,D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
,D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
,D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1168): value : false
,D/StatusBar.NetworkController( 1168): onSignalStrengthsChanged signalStrength=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte level=0
,D/StatusBar.NetworkController( 1168): updateTelephonySignalStrength: hasService=false ss=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte
D/StatusBar.NetworkController( 1168): updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal
D/StatusBar.NetworkController( 1168): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02012b/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020468/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
,D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
,I/rmt_storage(  268): rmt_storage_connect_cb: clnt_h=0x5 conn_h=0xb6b01090
I/rmt_storage(  268): rmt_storage_rw_iovec_cb: /boot/modem_fs1: clnt_h=0x1: req_h=0xa msg_id=3: R/W request received
I/rmt_storage(  268): wakelock acquired: 1, error no: 42
I/rmt_storage(  268): rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1 Unblock worker thread (th_id: -1229455232)
,I/rmt_storage(  268): rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1: req_h=0xa msg_id=3: Bytes written = 1572864
I/rmt_storage(  268): rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1: req_h=0xa msg_id=3: Send response: res=0 err=0
I/rmt_storage(  268): rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1 About to block rmt_storage client thread (th_id: -1229455232) wakelock released: 1, error no: 22
I/rmt_storage(  268): 
,I/rmt_storage(  268): rmt_storage_disconnect_cb: clnt_h=0x0x5 conn_h=0x0xb6b01090
,I/ServiceManager(  319): Waiting for service AtCmdFwd...
,D/qdhwcomposer(  249): hwc_blank: Done blanking display: 0
D/SurfaceControl(  872): Excessive delay in setPowerMode(): 254ms
D/PowerManagerService(  872): !@[s] blankAllDisplays() : blankAllDisplaysFromPowerManage
D/MISC PowerHAL(  872): sysfs_write +: /sys/class/power_supply/battery/lcd: 0
D/MISC PowerHAL(  872): sysfs_write -: /sys/class/power_supply/battery/lcd: 0
,I/qdhwcomposer(  249): handle_blank_event: dpy:0 panel power state: 0
,I/QCOM PowerHAL(  872): Got set_interactive hint
,I/PowerManagerService(  872): [PWL] Off : 0s ago,
I/PowerManagerService(  872): [PWL]   PowerManagerService.Display: ref count=2
,I/PowerManagerService(  872): [PWL]     mDisplayReady : false
D/DisplayPowerController(  872): getFinalBrightness : 0 -> 0
,D/PowerManagerService(  872): [s] DisplayPowerCallbacks : onStateChanged()
,D/PowerManagerService(  872): [PWL] sb release: PowerManagerService.Display
,I/ServiceManager(  319): Waiting for service AtCmdFwd...,
,E/SMD     (  279): DCD ON
,I/ServiceManager(  319): Waiting for service AtCmdFwd...
,V/AlarmManager(  872): waitForAlarm result :4
,D/BatteryService(  872): level:100, scale:100, status:5, health:2, present:true, voltage: 4386, temperature: 285, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  872): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  872): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  872):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  872): Plugged
,I/MotionRecognitionService(  872): setPowerConnected  = true
,D/BatteryService(  872): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1168): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1168): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1168):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3234): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3234): Disconnected process message: 10
,D/BatteryMeterView( 1168): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1168): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1168): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/GLSActivity( 1676): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1676): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
,I/GLSUser ( 1676): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1676): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1676): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1676): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/Finsky  ( 6658): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,D/Finsky  ( 6658): [1] 5.onFinished: Installation state replication failed.
,D/Finsky  ( 6658): [1] 5.onFinished: Scheduling replication attempt 4.
,I/ServiceManager(  319): Waiting for service AtCmdFwd...
,I/ServiceManager(  319): Waiting for service AtCmdFwd...
,V/AlarmManager(  872): waitForAlarm result :4
,D/KeyguardViewMediator( 1168): received DELAYED_KEYGUARD_ACTION with seq = 2, mDelayedShowingSequence = 2
,D/PersonaManager( 1168): isKioskContainerExistOnDevice
,D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1168): value : false
,D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1168): value : false
,D/KeyguardViewMediator( 1168): doKeyguard: not showing because lockscreen is off
,E/SMD     (  279): DCD ON
,W/Atfwd_Sendcmd(  319): AtCmdFwd service not published, waiting... retryCnt : 3
,I/PowerManagerService(  872): [PWL] Off : 5s ago
,E/SMD     (  279): DCD ON
,D/SSRM:m  (  872): SIOP:: AP = 320, PST = 363, CUR = 300
,E/ActivityManager(  872): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  872): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  872): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  872): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 8134): MountEmulatedStorage()
,E/Zygote  ( 8134): v2
I/libpersona( 8134): KNOX_SDCARD checking this for 10038
I/libpersona( 8134): KNOX_SDCARD not a persona
,I/ActivityManager(  872): Start proc com.sec.spp.push:RemoteDlcProcess for broadcast com.sec.spp.push/.dlc.util.DlcRegiReceiver: pid=8134 uid=10038 gids={50038, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/SELinux ( 8134): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 8134): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 8134): [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 8134): TimaSignature is unavailable
,D/ActivityThread( 8134): Added TimaKeyStore provider
,D/ResourcesManager( 8134): creating new AssetManager and set to /system/priv-app/SPPPushClient_Prod/SPPPushClient_Prod.apk
,E/SMD     (  279): DCD ON
E/SPPClientService( 8134): ============PushLog. commonIsShipBuild. stop!
E/SPPClientService( 8134): [PushClientApplication] Push log off : This is Ship build version
,D/SPPClientService( 8134): PushLog.txt file is not deleted.
,D/SPPClientService( 8134): PushLog.txt file is not deleted.
D/SPPClientService( 8134): ============PushLog. stop!
,I/ActivityManager(  872): Killing 7018:com.samsung.android.app.watchmanagerstub/u0a112 (adj 15): bgCount ##41
,W/libprocessgroup(  872): failed to open /acct/uid_10112/pid_7018/cgroup.procs: No such file or directory
,E/SMD     (  279): DCD ON
,W/ContextImpl(  872): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/PowerManagerService(  872): [PWL] Off : 15s ago
,V/AlarmManager(  872): waitForAlarm result :4
,D/ConnectivityService(  872): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/BatteryService(  872): level:100, scale:100, status:5, health:2, present:true, voltage: 4383, temperature: 285, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  872): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  872): stay LED for fully charged
,D/BatteryService(  872): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  872):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  872): Plugged
,I/MotionRecognitionService(  872): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1168): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1168): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1168):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3234): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3234): Disconnected process message: 10
,D/BatteryMeterView( 1168): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1168): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1168): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/ConnectivityService(  872): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/GLSUser ( 1676): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,I/GLSUser ( 1676): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1676): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1676): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1676): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ResourcesManager( 1676): creating new AssetManager and set to /system/app/PlusOne/PlusOne.apk
,V/BitmapFactory( 1676): DecodeImagePath(decodeResourceStream3) : res/mipmap-xxhdpi-v4/quantum_logo_google_plus_color_44in48.png
,V/BitmapFactory( 1676): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  872): uri = 14 selection = getSealedState
,D/SecContentProvider2(  872): mCursor = null
,D/SecContentProvider2(  872): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  872): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
V/ApplicationPolicy(  872): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/StatusBar( 1168): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,I/PhoneStatusBar( 1168): Icon Only
D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
D/PanelView( 1168): There is/are notification(s) 
,D/PanelView( 1168): There is/are notification(s) 
,E/HttpOperation( 6628): [kfu{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
E/HttpOperation( 6628): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 6628): 	at kfv.a(PG:65)
E/HttpOperation( 6628): 	at kff.u(PG:385)
E/HttpOperation( 6628): 	at kfb.a(PG:29)
E/HttpOperation( 6628): 	at kff.l(PG:132)
E/HttpOperation( 6628): 	at dsf.a(PG:807)
E/HttpOperation( 6628): 	at fhk.a(PG:1126)
E/HttpOperation( 6628): 	at fhk.a(PG:908)
E/HttpOperation( 6628): 	at fhk.onPerformSync(PG:636)
E/HttpOperation( 6628): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/HttpOperation( 6628): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/HttpOperation( 6628): 	at ihi.a(PG:22)
E/HttpOperation( 6628): 	at kft.a(PG:91)
E/HttpOperation( 6628): 	at kfv.a(PG:62)
E/HttpOperation( 6628): 	... 8 more
E/HttpOperation( 6628): Caused by: gdi: User intervention required. Notification has been pushed.
E/HttpOperation( 6628): 	at gde.c(Unknown Source)
E/HttpOperation( 6628): 	at gde.b(Unknown Source)
E/HttpOperation( 6628): 	at ihi.a(PG:19)
E/HttpOperation( 6628): 	... 10 more
,I/GLSUser ( 1676): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
I/GLSUser ( 1676): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1676): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1676): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1676): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/BitmapFactory( 1676): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  872): uri = 14 selection = getSealedState
,D/SecContentProvider2(  872): mCursor = null
,D/SecContentProvider2(  872): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  872): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
V/ApplicationPolicy(  872): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/StatusBar( 1168): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,E/HttpOperation( 6628): [getmobileexperiments] Unexpected exception
E/HttpOperation( 6628): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 6628): 	at kfv.a(PG:65)
E/HttpOperation( 6628): 	at kff.u(PG:385)
E/HttpOperation( 6628): 	at kfb.a(PG:29)
E/HttpOperation( 6628): 	at kff.l(PG:132)
E/HttpOperation( 6628): 	at ieo.a(PG:43)
E/HttpOperation( 6628): 	at iep.a(PG:93)
E/HttpOperation( 6628): 	at fhn.a(PG:59)
E/HttpOperation( 6628): 	at lex.a(PG:85)
E/HttpOperation( 6628): 	at lex.b(PG:132)
E/HttpOperation( 6628): 	at fhk.a(PG:1146)
E/HttpOperation( 6628): 	at fhk.a(PG:908)
E/HttpOperation( 6628): 	at fhk.onPerformSync(PG:636)
E/HttpOperation( 6628): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/HttpOperation( 6628): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/HttpOperation( 6628): 	at ihi.a(PG:22)
E/HttpOperation( 6628): 	at kft.a(PG:91)
E/HttpOperation( 6628): 	at kfv.a(PG:62)
E/HttpOperation( 6628): 	... 12 more
E/HttpOperation( 6628): Caused by: gdi: User intervention required. Notification has been pushed.
E/HttpOperation( 6628): 	at gde.c(Unknown Source)
E/HttpOperation( 6628): 	at gde.b(Unknown Source)
E/HttpOperation( 6628): 	at ihi.a(PG:19)
E/HttpOperation( 6628): 	... 14 more
,E/ExperimentLoader( 6628): [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 6628): java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 6628): 	at kfv.a(PG:65)
E/ExperimentLoader( 6628): 	at kff.u(PG:385)
E/ExperimentLoader( 6628): 	at kfb.a(PG:29)
E/ExperimentLoader( 6628): 	at kff.l(PG:132)
E/ExperimentLoader( 6628): 	at ieo.a(PG:43)
E/ExperimentLoader( 6628): 	at iep.a(PG:93)
E/ExperimentLoader( 6628): 	at fhn.a(PG:59)
E/ExperimentLoader( 6628): 	at lex.a(PG:85)
E/ExperimentLoader( 6628): 	at lex.b(PG:132)
E/ExperimentLoader( 6628): 	at fhk.a(PG:1146)
E/ExperimentLoader( 6628): 	at fhk.a(PG:908)
E/ExperimentLoader( 6628): 	at fhk.onPerformSync(PG:636)
E/ExperimentLoader( 6628): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/ExperimentLoader( 6628): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/ExperimentLoader( 6628): 	at ihi.a(PG:22)
E/ExperimentLoader( 6628): 	at kft.a(PG:91)
E/ExperimentLoader( 6628): 	at kfv.a(PG:62)
E/ExperimentLoader( 6628): 	... 12 more
E/ExperimentLoader( 6628): Caused by: gdi: User intervention required. Notification has been pushed.
E/ExperimentLoader( 6628): 	at gde.c(Unknown Source)
E/ExperimentLoader( 6628): 	at gde.b(Unknown Source)
E/ExperimentLoader( 6628): 	at ihi.a(PG:19)
E/ExperimentLoader( 6628): 	... 14 more
,I/PhoneStatusBar( 1168): Icon Only
,D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1168): value : false
,D/PanelView( 1168): There is/are notification(s) 
,D/PanelView( 1168): There is/are notification(s) 
,E/SQLiteLog( 1676): (10) POSIX Error : 11 SQLite Error : 3850
,I/GLSUser ( 1676): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,I/GLSUser ( 1676): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1676): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1676): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1676): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/BitmapFactory( 1676): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  872): uri = 14 selection = getSealedState
D/SecContentProvider2(  872): mCursor = null
,D/SecContentProvider2(  872): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  872): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
V/ApplicationPolicy(  872): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/StatusBar( 1168): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,E/HttpOperation( 6628): [getaccountstatus] Unexpected exception
E/HttpOperation( 6628): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 6628): 	at kfv.a(PG:65)
E/HttpOperation( 6628): 	at kff.u(PG:385)
E/HttpOperation( 6628): 	at kfb.a(PG:29)
E/HttpOperation( 6628): 	at ixd.a(PG:248)
E/HttpOperation( 6628): 	at ixd.b(PG:206)
E/HttpOperation( 6628): 	at ixd.a(PG:175)
E/HttpOperation( 6628): 	at fig.a(PG:78)
E/HttpOperation( 6628): 	at lex.a(PG:85)
E/HttpOperation( 6628): 	at lex.b(PG:132)
E/HttpOperation( 6628): 	at fhk.a(PG:1146)
E/HttpOperation( 6628): 	at fhk.a(PG:908)
E/HttpOperation( 6628): 	at fhk.onPerformSync(PG:636)
E/HttpOperation( 6628): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/HttpOperation( 6628): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/HttpOperation( 6628): 	at ihi.a(PG:22)
E/HttpOperation( 6628): 	at kft.a(PG:91)
E/HttpOperation( 6628): 	at kfv.a(PG:62)
E/HttpOperation( 6628): 	... 12 more
E/HttpOperation( 6628): Caused by: gdi: User intervention required. Notification has been pushed.
E/HttpOperation( 6628): 	at gde.c(Unknown Source)
E/HttpOperation( 6628): 	at gde.b(Unknown Source)
E/HttpOperation( 6628): 	at ihi.a(PG:19)
E/HttpOperation( 6628): 	... 14 more
,E/EsSyncAdapterService( 6628): Sync failure
E/EsSyncAdapterService( 6628): java.io.IOException: Rpc failed
E/EsSyncAdapterService( 6628): 	at ixd.a(PG:348)
E/EsSyncAdapterService( 6628): 	at ixd.a(PG:248)
E/EsSyncAdapterService( 6628): 	at ixd.b(PG:206)
E/EsSyncAdapterService( 6628): 	at ixd.a(PG:175)
E/EsSyncAdapterService( 6628): 	at fig.a(PG:78)
E/EsSyncAdapterService( 6628): 	at lex.a(PG:85)
E/EsSyncAdapterService( 6628): 	at lex.b(PG:132)
E/EsSyncAdapterService( 6628): 	at fhk.a(PG:1146)
E/EsSyncAdapterService( 6628): 	at fhk.a(PG:908)
E/EsSyncAdapterService( 6628): 	at fhk.onPerformSync(PG:636)
E/EsSyncAdapterService( 6628): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/EsSyncAdapterService( 6628): Caused by: java.io.IOException: Cannot obtain authentication token
E/EsSyncAdapterService( 6628): 	at kfv.a(PG:65)
E/EsSyncAdapterService( 6628): 	at kff.u(PG:385)
E/EsSyncAdapterService( 6628): 	at kfb.a(PG:29)
E/EsSyncAdapterService( 6628): 	... 10 more
E/EsSyncAdapterService( 6628): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/EsSyncAdapterService( 6628): 	at ihi.a(PG:22)
E/EsSyncAdapterService( 6628): 	at kft.a(PG:91)
E/EsSyncAdapterService( 6628): 	at kfv.a(PG:62)
E/EsSyncAdapterService( 6628): 	... 12 more
E/EsSyncAdapterService( 6628): Caused by: gdi: User intervention required. Notification has been pushed.
E/EsSyncAdapterService( 6628): 	at gde.c(Unknown Source)
E/EsSyncAdapterService( 6628): 	at gde.b(Unknown Source)
E/EsSyncAdapterService( 6628): 	at ihi.a(PG:19)
E/EsSyncAdapterService( 6628): 	... 14 more
,I/PhoneStatusBar( 1168): Icon Only
D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
D/PanelView( 1168): There is/are notification(s) 
,D/PanelView( 1168): There is/are notification(s) 
,D/ConnectivityService(  872): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SyncManager(  872): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, PERIODIC, currentRunTime 153001, reason: Periodic, SyncResult: stats [ numIoExceptions: 2]
,D/ConnectivityService(  872): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  872): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SecContentProvider2(  872): uri = 11 selection = getMyKnoxAdmin
,D/SecContentProvider2(  872): mCursor = null
,E/SQLiteLog( 1676): (10) POSIX Error : 11 SQLite Error : 3850
,E/SMD     (  279): DCD ON
,E/SMD     (  279): DCD ON
,D/SSRM:m  (  872): SIOP:: AP = 310, PST = 353, CUR = 300
,I/ServiceManager(  319): Waiting for service AtCmdFwd...
,I/ServiceManager(  319): Waiting for service AtCmdFwd...
,I/ServiceManager(  319): Waiting for service AtCmdFwd...
,V/AlarmManager(  872): waitForAlarm result :4
,E/SMD     (  279): DCD ON
,I/ServiceManager(  319): Waiting for service AtCmdFwd...
,V/GLSActivity( 1676): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1676): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
,I/GLSUser ( 1676): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1676): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1676): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1676): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/Finsky  ( 6658): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,D/Finsky  ( 6658): [1] 5.onFinished: Installation state replication failed.
D/Finsky  ( 6658): [1] 5.onFinished: Scheduling replication attempt 5.
,I/ServiceManager(  319): Waiting for service AtCmdFwd...
,W/Atfwd_Sendcmd(  319): AtCmdFwd service not published, waiting... retryCnt : 4
,E/SMD     (  279): DCD ON
,E/Watchdog(  872): !@Sync 5
,V/AlarmManager(  872): waitForAlarm result :8
,D/BatteryService(  872): level:100, scale:100, status:5, health:2, present:true, voltage: 4386, temperature: 285, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  872): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  872): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  872):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  872): Plugged
,I/MotionRecognitionService(  872): setPowerConnected  = true
,D/BatteryService(  872): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1168): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1168): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1168):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3234): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3234): Disconnected process message: 10
,D/BatteryMeterView( 1168): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1168): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1168): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  279): DCD ON
,D/SSRM:m  (  872): SIOP:: AP = 310, PST = 344, CUR = 300
,I/PowerManagerService(  872): [PWL] Off : 30s ago
,E/SMD     (  279): DCD ON
,W/ContextImpl(  872): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  279): DCD ON
,E/SMD     (  279): DCD ON
,D/SSRM:m  (  872): SIOP:: AP = 300, PST = 338, CUR = 300
,E/SMD     (  279): DCD ON
,V/AlarmManager(  872): waitForAlarm result :4
,D/KeyguardUpdateMonitor( 1168): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1168): handleTimeUpdate
,D/KeyguardEffectViewController( 1168): onReceive action : android.intent.action.TIME_TICK
,I/KeyguardEffectViewController( 1168): *** don't update sliding image ***
,D/BatteryService(  872): level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 285, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  872): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
D/BatteryService(  872): stay LED for fully charged
,D/ConnectivityService(  872): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/BatteryService(  872): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  872):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
I/MotionRecognitionService(  872): Plugged
I/MotionRecognitionService(  872): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1168): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1168): handleBatteryUpdate
,V/HeadsetService( 3234): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 3234): Disconnected process message: 10
,D/STATUSBAR-PhoneStatusBar( 1168):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
D/BatteryMeterView( 1168): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/ConnectivityService(  872): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/BatteryMeterView( 1168): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1168): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/DateView( 1168): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1168): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,V/GLSActivity( 1676): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ConnectivityService(  872): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  872): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/VacuumService( 1676): Vacuum at: now=1452294376951 tag=VacuumService
,I/GoogleURLConnFactory( 1676): Using platform SSLCertificateSocketFactory
,D/ConnectivityService(  872): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/GLSUser ( 1676): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
I/GLSUser ( 1676): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1676): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1676): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1676): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/BitmapFactory( 1676): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/common_ic_googleplayservices.png
,V/BitmapFactory( 1676): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  872): uri = 14 selection = getSealedState
D/SecContentProvider2(  872): mCursor = null
,D/SecContentProvider2(  872): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  872): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
V/ApplicationPolicy(  872): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/StatusBar( 1168): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,I/PhoneStatusBar( 1168): Icon Only
D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
D/PanelView( 1168): There is/are notification(s) 
D/PanelView( 1168): There is/are notification(s) 
E/Uploader( 1676): Failed to get auth token: User intervention required. Notification has been pushed.
E/Uploader( 1676): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
E/Uploader( 1676): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
E/Uploader( 1676): 	at com.google.android.gms.auth.p.d(SourceFile:599)
E/Uploader( 1676): 	at com.google.android.gms.auth.p.c(SourceFile:550)
E/Uploader( 1676): 	at com.google.android.gms.auth.p.b(SourceFile:477)
E/Uploader( 1676): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:508)
E/Uploader( 1676): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:337)
E/Uploader( 1676): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:263)
E/Uploader( 1676): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:235)
E/Uploader( 1676): 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:125)
E/Uploader( 1676): 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:78)
E/Uploader( 1676): 	at com.google.android.gms.gcm.am.run(SourceFile:135)
,E/SMD     (  279): DCD ON
,I/System.out( 1676): (HTTPLog)-Static: SBServiceAPI: getService class android.os.ServiceManager
,I/System.out( 1676): (HTTPLog)-Static: isShipBuild true
I/System.out( 1676): (HTTPLog)-Thread-200-435089370: SmartBonding Enabling is true, SHIP_BUILD is true, log to file is false, DBG is false
,I/qtaguid ( 1676): Tagging socket 56 with tag 120100000000{4609,0} uid -1, pid: 1676, getuid(): 10012
,I/qtaguid ( 1676): Tagging socket 62 with tag 120100000000{4609,0} uid -1, pid: 1676, getuid(): 10012
,V/GLSActivity( 1676): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1676): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
I/GLSUser ( 1676): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1676): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1676): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1676): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/Finsky  ( 6658): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,D/Finsky  ( 6658): [1] 5.onFinished: Installation state replication failed.
,D/Finsky  ( 6658): [1] 5.onFinished: Giving up after 6 failures.
,W/Uploader( 1676): No account for auth token provided
,I/qtaguid ( 1676): Tagging socket 56 with tag 120100000000{4609,0} uid -1, pid: 1676, getuid(): 10012
,W/Uploader( 1676): No account for auth token provided
,I/qtaguid ( 1676): Tagging socket 56 with tag 120100000000{4609,0} uid -1, pid: 1676, getuid(): 10012
,W/Uploader( 1676): No account for auth token provided
,I/qtaguid ( 1676): Tagging socket 56 with tag 120100000000{4609,0} uid -1, pid: 1676, getuid(): 10012
,W/Uploader( 1676): No account for auth token provided
,I/qtaguid ( 1676): Tagging socket 56 with tag 120100000000{4609,0} uid -1, pid: 1676, getuid(): 10012
,W/Uploader( 1676):  no longer exists, so no auth token.
,I/qtaguid ( 1676): Tagging socket 56 with tag 120100000000{4609,0} uid -1, pid: 1676, getuid(): 10012
,E/SQLiteLog( 1676): (10) POSIX Error : 11 SQLite Error : 3850
,D/ConnectivityService(  872): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/ServiceManager(  319): Waiting for service AtCmdFwd...
,V/AlarmManager(  872): waitForAlarm result :4
,D/ConnectivityService(  872): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  872): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/BooksSync( 7369): Starting books sync, d
,D/ConnectivityService(  872): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,V/GLSActivity( 1676): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1676): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
,I/GLSUser ( 1676): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1676): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1676): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1676): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ResourcesManager( 1676): creating new AssetManager and set to /system/app/Books/Books.apk
,V/BitmapFactory( 1676): DecodeImagePath(decodeResourceStream3) : res/mipmap-xxhdpi-v4/ic_launcher_play_books.png
,V/BitmapFactory( 1676): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  872): uri = 14 selection = getSealedState
,D/SecContentProvider2(  872): mCursor = null
D/SecContentProvider2(  872): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  872): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy(  872): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/StatusBar( 1168): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,I/PhoneStatusBar( 1168): Icon Only
,D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
D/PanelView( 1168): There is/are notification(s) 
D/PanelView( 1168): There is/are notification(s) 
,W/GLSActivity( 1676): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1676): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1676): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1676): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1676): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1676): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1676): 	at android.os.Binder.execTransact(Binder.java:446)
,E/BooksAccountManager( 7369): Authentication error
E/BooksAccountManager( 7369): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 7369): android.accounts.AccountManager.convertErrorToException(AccountManager.java:1893)
,E/HttpHelper( 7369): null auth token
,I/qtaguid ( 7369): Tagging socket 34 with tag 10000000000{256,0} uid -1, pid: 7369, getuid(): 10082
,I/qtaguid ( 7369): Tagging socket 34 with tag 10000000000{256,0} uid -1, pid: 7369, getuid(): 10082
,I/qtaguid ( 7369): Untagging socket 34
,W/ApiaryClient( 7369): Error response from books API: {
W/ApiaryClient( 7369):  "error": {
W/ApiaryClient( 7369):   "errors": [
W/ApiaryClient( 7369):    {
W/ApiaryClient( 7369):     "domain": "global",
W/ApiaryClient( 7369):     "reason": "required",
W/ApiaryClient( 7369):     "message": "Login Required",
W/ApiaryClient( 7369):     "locationType": "header",
W/ApiaryClient( 7369):     "location": "Authorization"
W/ApiaryClient( 7369):    }
W/ApiaryClient( 7369):   ],
W/ApiaryClient( 7369):   "code": 401,
W/ApiaryClient( 7369):   "message": "Login Required"
W/ApiaryClient( 7369):  }
W/ApiaryClient( 7369): }
,W/ApiaryClient( 7369): errCount = 1: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 7369): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3DS0HXd4TFLU4&nonce=8307471020774478128&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 7369): Headers suppressed
,D/ConnectivityService(  872): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/ServiceManager(  319): Waiting for service AtCmdFwd...
,E/SMD     (  279): DCD ON
,V/GLSActivity( 1676): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1676): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
,I/GLSUser ( 1676): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1676): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1676): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/ServiceManager(  319): Waiting for service AtCmdFwd...
,V/GLSActivity( 1676): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/BitmapFactory( 1676): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  872): uri = 14 selection = getSealedState
,D/SecContentProvider2(  872): mCursor = null
D/SecContentProvider2(  872): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  872): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy(  872): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/StatusBar( 1168): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,I/PhoneStatusBar( 1168): Icon Only
,D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1168): value : false
D/PanelView( 1168): There is/are notification(s) 
,D/PanelView( 1168): There is/are notification(s) 
,W/GLSActivity( 1676): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1676): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1676): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1676): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1676): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1676): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1676): 	at android.os.Binder.execTransact(Binder.java:446)
,E/BooksAccountManager( 7369): Authentication error
E/BooksAccountManager( 7369): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 7369): android.accounts.AccountManager.convertErrorToException(AccountManager.java:1893)
E/HttpHelper( 7369): null auth token
,I/qtaguid ( 7369): Tagging socket 34 with tag 10000000000{256,0} uid -1, pid: 7369, getuid(): 10082
,I/qtaguid ( 7369): Tagging socket 39 with tag 10000000000{256,0} uid -1, pid: 7369, getuid(): 10082
,I/qtaguid ( 7369): Untagging socket 34
,W/ApiaryClient( 7369): Error response from books API: {
W/ApiaryClient( 7369):  "error": {
W/ApiaryClient( 7369):   "errors": [
W/ApiaryClient( 7369):    {
W/ApiaryClient( 7369):     "domain": "global",
W/ApiaryClient( 7369):     "reason": "required",
W/ApiaryClient( 7369):     "message": "Login Required",
W/ApiaryClient( 7369):     "locationType": "header",
W/ApiaryClient( 7369):     "location": "Authorization"
W/ApiaryClient( 7369):    }
W/ApiaryClient( 7369):   ],
W/ApiaryClient( 7369):   "code": 401,
W/ApiaryClient( 7369):   "message": "Login Required"
W/ApiaryClient( 7369):  }
W/ApiaryClient( 7369): }
,W/ApiaryClient( 7369): errCount = 2: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 7369): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3DS0HXd4TFLU4&nonce=8307471020774478128&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 7369): Headers suppressed
,D/ConnectivityService(  872): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/ServiceManager(  319): Waiting for service AtCmdFwd...
,V/GLSActivity( 1676): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1676): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
,I/GLSUser ( 1676): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1676): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1676): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1676): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/BitmapFactory( 1676): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  872): uri = 14 selection = getSealedState
,D/SecContentProvider2(  872): mCursor = null
D/SecContentProvider2(  872): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  872): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy(  872): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,W/GLSActivity( 1676): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1676): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1676): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1676): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1676): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1676): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1676): 	at android.os.Binder.execTransact(Binder.java:446)
,E/BooksAccountManager( 7369): Authentication error
E/BooksAccountManager( 7369): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 7369): android.accounts.AccountManager.convertErrorToException(AccountManager.java:1893)
,D/StatusBar( 1168): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,E/HttpHelper( 7369): null auth token
,I/qtaguid ( 7369): Tagging socket 34 with tag 10000000000{256,0} uid -1, pid: 7369, getuid(): 10082
,I/PhoneStatusBar( 1168): Icon Only
D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
D/PanelView( 1168): There is/are notification(s) 
D/PanelView( 1168): There is/are notification(s) 
,I/qtaguid ( 7369): Untagging socket 34
,W/ApiaryClient( 7369): Error response from books API: {
W/ApiaryClient( 7369):  "error": {
W/ApiaryClient( 7369):   "errors": [
W/ApiaryClient( 7369):    {
W/ApiaryClient( 7369):     "domain": "global",
W/ApiaryClient( 7369):     "reason": "required",
W/ApiaryClient( 7369):     "message": "Login Required",
W/ApiaryClient( 7369):     "locationType": "header",
W/ApiaryClient( 7369):     "location": "Authorization"
W/ApiaryClient( 7369):    }
W/ApiaryClient( 7369):   ],
W/ApiaryClient( 7369):   "code": 401,
W/ApiaryClient( 7369):   "message": "Login Required"
W/ApiaryClient( 7369):  }
W/ApiaryClient( 7369): }
,W/ApiaryClient( 7369): errCount = 3: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 7369): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3DS0HXd4TFLU4&nonce=8307471020774478128&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 7369): Headers suppressed
,D/ConnectivityService(  872): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/ServiceManager(  319): Waiting for service AtCmdFwd...
,E/BooksSync( 7369): Soft error
E/BooksSync( 7369): com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
E/BooksSync( 7369): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3DS0HXd4TFLU4&nonce=8307471020774478128&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
E/BooksSync( 7369): Headers suppressed
E/BooksSync( 7369): 
E/BooksSync( 7369): com.google.android.apps.books.net.HttpHelper.wrapExceptionBasedOnStatus(HttpHelper.java:212)
,E/BooksSync( 7369): Sync error
E/BooksSync( 7369): com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
E/BooksSync( 7369): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3DS0HXd4TFLU4&nonce=8307471020774478128&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
E/BooksSync( 7369): Headers suppressed
E/BooksSync( 7369): 
E/BooksSync( 7369): com.google.android.apps.books.net.HttpHelper.wrapExceptionBasedOnStatus(HttpHelper.java:212)
,I/BooksSync( 7369): Finished books sync
,D/ConnectivityService(  872): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SyncManager(  872): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 160080, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,D/ConnectivityService(  872): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  872): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/art     (  872): Explicit concurrent mark sweep GC freed 62568(3MB) AllocSpace objects, 29(919KB) LOS objects, 30% free, 36MB/52MB, paused 3.879ms total 136.744ms
,D/SecContentProvider2(  872): uri = 11 selection = getMyKnoxAdmin
,D/SecContentProvider2(  872): mCursor = null
,D/ConnectivityService(  872): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/SMD     (  279): DCD ON
,I/GLSUser ( 1676): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,I/GLSUser ( 1676): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1676): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1676): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1676): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/BitmapFactory( 1676): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  872): uri = 14 selection = getSealedState
,D/SecContentProvider2(  872): mCursor = null
D/SecContentProvider2(  872): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  872): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
V/ApplicationPolicy(  872): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/StatusBar( 1168): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,I/PhoneStatusBar( 1168): Icon Only
,D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
D/PanelView( 1168): There is/are notification(s) 
,D/PanelView( 1168): There is/are notification(s) 
,E/HttpOperation( 6628): [kfu{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
E/HttpOperation( 6628): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 6628): 	at kfv.a(PG:65)
E/HttpOperation( 6628): 	at kff.u(PG:385)
E/HttpOperation( 6628): 	at kfb.a(PG:29)
E/HttpOperation( 6628): 	at kff.l(PG:132)
E/HttpOperation( 6628): 	at dsf.a(PG:807)
E/HttpOperation( 6628): 	at fhk.a(PG:1126)
E/HttpOperation( 6628): 	at fhk.a(PG:908)
E/HttpOperation( 6628): 	at fhk.onPerformSync(PG:636)
E/HttpOperation( 6628): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/HttpOperation( 6628): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/HttpOperation( 6628): 	at ihi.a(PG:22)
E/HttpOperation( 6628): 	at kft.a(PG:91)
E/HttpOperation( 6628): 	at kfv.a(PG:62)
E/HttpOperation( 6628): 	... 8 more
E/HttpOperation( 6628): Caused by: gdi: User intervention required. Notification has been pushed.
E/HttpOperation( 6628): 	at gde.c(Unknown Source)
E/HttpOperation( 6628): 	at gde.b(Unknown Source)
E/HttpOperation( 6628): 	at ihi.a(PG:19)
E/HttpOperation( 6628): 	... 10 more
,I/GLSUser ( 1676): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
I/GLSUser ( 1676): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1676): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1676): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1676): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/Atfwd_Sendcmd(  319): AtCmdFwd service not published, waiting... retryCnt : 5
,D/SSRM:m  (  872): SIOP:: AP = 300, PST = 332, CUR = 300
,V/BitmapFactory( 1676): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  872): uri = 14 selection = getSealedState
,D/SecContentProvider2(  872): mCursor = null
D/SecContentProvider2(  872): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  872): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy(  872): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,I/PowerManagerService(  872): [PWL] Off : 50s ago
I/PowerManagerService(  872): [PWL]   PowerManagerService.WakeLocks: ref count=1
I/PowerManagerService(  872): [PWL]     mWakeLockSummary : 0x1
I/PowerManagerService(  872): [PWL]       PARTIAL_WAKE_LOCK              '*sync*/com.google.android.apps.plus.content.EsProvider/com.google/eM_ADDR' (uid=1000, pid=872, ws=WorkSource{10135}) (elapsedTime=392)
,D/StatusBar( 1168): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,E/HttpOperation( 6628): [getmobileexperiments] Unexpected exception
E/HttpOperation( 6628): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 6628): 	at kfv.a(PG:65)
E/HttpOperation( 6628): 	at kff.u(PG:385)
E/HttpOperation( 6628): 	at kfb.a(PG:29)
E/HttpOperation( 6628): 	at kff.l(PG:132)
E/HttpOperation( 6628): 	at ieo.a(PG:43)
E/HttpOperation( 6628): 	at iep.a(PG:93)
E/HttpOperation( 6628): 	at fhn.a(PG:59)
E/HttpOperation( 6628): 	at lex.a(PG:85)
E/HttpOperation( 6628): 	at lex.b(PG:132)
E/HttpOperation( 6628): 	at fhk.a(PG:1146)
E/HttpOperation( 6628): 	at fhk.a(PG:908)
E/HttpOperation( 6628): 	at fhk.onPerformSync(PG:636)
E/HttpOperation( 6628): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/HttpOperation( 6628): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/HttpOperation( 6628): 	at ihi.a(PG:22)
E/HttpOperation( 6628): 	at kft.a(PG:91)
E/HttpOperation( 6628): 	at kfv.a(PG:62)
E/HttpOperation( 6628): 	... 12 more
E/HttpOperation( 6628): Caused by: gdi: User intervention required. Notification has been pushed.
E/HttpOperation( 6628): 	at gde.c(Unknown Source)
E/HttpOperation( 6628): 	at gde.b(Unknown Source)
E/HttpOperation( 6628): 	at ihi.a(PG:19)
E/HttpOperation( 6628): 	... 14 more
,I/PhoneStatusBar( 1168): Icon Only
D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
D/PanelView( 1168): There is/are notification(s) 
D/PanelView( 1168): There is/are notification(s) 
E/ExperimentLoader( 6628): [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 6628): java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 6628): 	at kfv.a(PG:65)
E/ExperimentLoader( 6628): 	at kff.u(PG:385)
E/ExperimentLoader( 6628): 	at kfb.a(PG:29)
E/ExperimentLoader( 6628): 	at kff.l(PG:132)
E/ExperimentLoader( 6628): 	at ieo.a(PG:43)
E/ExperimentLoader( 6628): 	at iep.a(PG:93)
E/ExperimentLoader( 6628): 	at fhn.a(PG:59)
E/ExperimentLoader( 6628): 	at lex.a(PG:85)
E/ExperimentLoader( 6628): 	at lex.b(PG:132)
E/ExperimentLoader( 6628): 	at fhk.a(PG:1146)
E/ExperimentLoader( 6628): 	at fhk.a(PG:908)
E/ExperimentLoader( 6628): 	at fhk.onPerformSync(PG:636)
E/ExperimentLoader( 6628): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/ExperimentLoader( 6628): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/ExperimentLoader( 6628): 	at ihi.a(PG:22)
E/ExperimentLoader( 6628): 	at kft.a(PG:91)
E/ExperimentLoader( 6628): 	at kfv.a(PG:62)
E/ExperimentLoader( 6628): 	... 12 more
E/ExperimentLoader( 6628): Caused by: gdi: User intervention required. Notification has been pushed.
E/ExperimentLoader( 6628): 	at gde.c(Unknown Source)
E/ExperimentLoader( 6628): 	at gde.b(Unknown Source)
E/ExperimentLoader( 6628): 	at ihi.a(PG:19)
E/ExperimentLoader( 6628): 	... 14 more
,I/GLSUser ( 1676): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,I/GLSUser ( 1676): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1676): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1676): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1676): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/BitmapFactory( 1676): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  872): uri = 14 selection = getSealedState
D/SecContentProvider2(  872): mCursor = null
,D/SecContentProvider2(  872): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  872): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
V/ApplicationPolicy(  872): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/StatusBar( 1168): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,E/HttpOperation( 6628): [getaccountstatus] Unexpected exception
E/HttpOperation( 6628): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 6628): 	at kfv.a(PG:65)
E/HttpOperation( 6628): 	at kff.u(PG:385)
E/HttpOperation( 6628): 	at kfb.a(PG:29)
E/HttpOperation( 6628): 	at ixd.a(PG:248)
E/HttpOperation( 6628): 	at ixd.b(PG:206)
E/HttpOperation( 6628): 	at ixd.a(PG:175)
E/HttpOperation( 6628): 	at fig.a(PG:78)
E/HttpOperation( 6628): 	at lex.a(PG:85)
E/HttpOperation( 6628): 	at lex.b(PG:132)
E/HttpOperation( 6628): 	at fhk.a(PG:1146)
E/HttpOperation( 6628): 	at fhk.a(PG:908)
E/HttpOperation( 6628): 	at fhk.onPerformSync(PG:636)
E/HttpOperation( 6628): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/HttpOperation( 6628): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/HttpOperation( 6628): 	at ihi.a(PG:22)
E/HttpOperation( 6628): 	at kft.a(PG:91)
E/HttpOperation( 6628): 	at kfv.a(PG:62)
E/HttpOperation( 6628): 	... 12 more
E/HttpOperation( 6628): Caused by: gdi: User intervention required. Notification has been pushed.
E/HttpOperation( 6628): 	at gde.c(Unknown Source)
E/HttpOperation( 6628): 	at gde.b(Unknown Source)
E/HttpOperation( 6628): 	at ihi.a(PG:19)
E/HttpOperation( 6628): 	... 14 more
,E/EsSyncAdapterService( 6628): Sync failure
E/EsSyncAdapterService( 6628): java.io.IOException: Rpc failed
E/EsSyncAdapterService( 6628): 	at ixd.a(PG:348)
E/EsSyncAdapterService( 6628): 	at ixd.a(PG:248)
E/EsSyncAdapterService( 6628): 	at ixd.b(PG:206)
E/EsSyncAdapterService( 6628): 	at ixd.a(PG:175)
E/EsSyncAdapterService( 6628): 	at fig.a(PG:78)
E/EsSyncAdapterService( 6628): 	at lex.a(PG:85)
E/EsSyncAdapterService( 6628): 	at lex.b(PG:132)
E/EsSyncAdapterService( 6628): 	at fhk.a(PG:1146)
E/EsSyncAdapterService( 6628): 	at fhk.a(PG:908)
E/EsSyncAdapterService( 6628): 	at fhk.onPerformSync(PG:636)
E/EsSyncAdapterService( 6628): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/EsSyncAdapterService( 6628): Caused by: java.io.IOException: Cannot obtain authentication token
E/EsSyncAdapterService( 6628): 	at kfv.a(PG:65)
E/EsSyncAdapterService( 6628): 	at kff.u(PG:385)
E/EsSyncAdapterService( 6628): 	at kfb.a(PG:29)
E/EsSyncAdapterService( 6628): 	... 10 more
E/EsSyncAdapterService( 6628): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/EsSyncAdapterService( 6628): 	at ihi.a(PG:22)
E/EsSyncAdapterService( 6628): 	at kft.a(PG:91)
E/EsSyncAdapterService( 6628): 	at kfv.a(PG:62)
E/EsSyncAdapterService( 6628): 	... 12 more
E/EsSyncAdapterService( 6628): Caused by: gdi: User intervention required. Notification has been pushed.
E/EsSyncAdapterService( 6628): 	at gde.c(Unknown Source)
E/EsSyncAdapterService( 6628): 	at gde.b(Unknown Source)
E/EsSyncAdapterService( 6628): 	at ihi.a(PG:19)
E/EsSyncAdapterService( 6628): 	... 14 more
,I/PhoneStatusBar( 1168): Icon Only
D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
D/PanelView( 1168): There is/are notification(s) 
D/PanelView( 1168): There is/are notification(s) 
,D/ConnectivityService(  872): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SyncManager(  872): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, PERIODIC, currentRunTime 185345, reason: Periodic, SyncResult: stats [ numIoExceptions: 2]
,D/ConnectivityService(  872): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  872): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SecContentProvider2(  872): uri = 11 selection = getMyKnoxAdmin
D/SecContentProvider2(  872): mCursor = null
,E/SQLiteLog( 1676): (10) POSIX Error : 11 SQLite Error : 3850
,E/SMD     (  279): DCD ON
,D/BatteryService(  872): level:100, scale:100, status:5, health:2, present:true, voltage: 4386, temperature: 285, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  872): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  872): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  872):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  872): Plugged
,I/MotionRecognitionService(  872): setPowerConnected  = true
,D/BatteryService(  872): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1168): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1168): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1168):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3234): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3234): Disconnected process message: 10
,D/BatteryMeterView( 1168): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1168): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1168): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,W/ContextImpl(  872): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  279): DCD ON
,E/Watchdog(  872): !@Sync 6
,E/SMD     (  279): DCD ON
,D/SSRM:m  (  872): SIOP:: AP = 300, PST = 321, CUR = 300
,E/SMD     (  279): DCD ON
,D/BatteryService(  872): level:100, scale:100, status:5, health:2, present:true, voltage: 4382, temperature: 285, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  872): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  872): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  872):   mReceiver.onReceive : ACTION_BATTERY_CHANGED,
I/MotionRecognitionService(  872): Plugged
,I/MotionRecognitionService(  872): setPowerConnected  = true
,D/BatteryService(  872): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1168): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1168): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1168):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3234): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3234): Disconnected process message: 10
,D/BatteryMeterView( 1168): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1168): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1168): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  279): DCD ON
,E/SMD     (  279): DCD ON
,D/SSRM:m  (  872): SIOP:: AP = 300, PST = 314, CUR = 300
,E/SMD     (  279): DCD ON
,E/SMD     (  279): DCD ON
,W/ContextImpl(  872): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/Atfwd_Sendcmd(  319): AtCmdFwd service not ready - Exhausted retry attempts - :6
I/Atfwd_Daemon(  319): result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,I/PowerManagerService(  872): [PWL] Off : 75s ago
,V/AlarmManager(  872): waitForAlarm result :4
,D/ConnectivityService(  872): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/BatteryService(  872): level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 285, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  872): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
D/BatteryService(  872): stay LED for fully charged
,D/BatteryService(  872): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  872):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  872): Plugged
I/MotionRecognitionService(  872): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1168): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1168): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1168):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3234): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3234): Disconnected process message: 10
,D/BatteryMeterView( 1168): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1168): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1168): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  279): DCD ON
,E/SMD     (  279): DCD ON
,D/SSRM:m  (  872): SIOP:: AP = 300, PST = 310, CUR = 300
,E/SMD     (  279): DCD ON
,I/ServiceManager(  319): Waiting for service AtCmdFwd...
,E/SMD     (  279): DCD ON
,E/Watchdog(  872): !@Sync 7
,I/ServiceManager(  319): Waiting for service AtCmdFwd...
,V/AlarmManager(  872): waitForAlarm result :8
,I/ServiceManager(  319): Waiting for service AtCmdFwd...
,I/ServiceManager(  319): Waiting for service AtCmdFwd...
,E/SMD     (  279): DCD ON
,I/ServiceManager(  319): Waiting for service AtCmdFwd...
,W/Atfwd_Sendcmd(  319): AtCmdFwd service not published, waiting... retryCnt : 1
,D/SSRM:m  (  872): SIOP:: AP = 290, PST = 306, CUR = 300
,E/SMD     (  279): DCD ON
,W/ContextImpl(  872): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  279): DCD ON
,I/ServiceManager(  319): Waiting for service AtCmdFwd...
,I/ServiceManager(  319): Waiting for service AtCmdFwd...
,I/ServiceManager(  319): Waiting for service AtCmdFwd...
,E/SMD     (  279): DCD ON
,I/ServiceManager(  319): Waiting for service AtCmdFwd...
,I/ServiceManager(  319): Waiting for service AtCmdFwd...
,W/Atfwd_Sendcmd(  319): AtCmdFwd service not published, waiting... retryCnt : 2
,D/SSRM:m  (  872): SIOP:: AP = 290, PST = 302, CUR = 300
,E/SMD     (  279): DCD ON
,E/SMD     (  279): DCD ON
,I/PowerManagerService(  872): [PWL] Off : 105s ago
,V/AlarmManager(  872): waitForAlarm result :4
,D/KeyguardUpdateMonitor( 1168): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1168): handleTimeUpdate
,D/KeyguardEffectViewController( 1168): onReceive action : android.intent.action.TIME_TICK
,I/KeyguardEffectViewController( 1168): *** don't update sliding image ***
,D/BatteryService(  872): level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 284, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  872): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  872): stay LED for fully charged
,D/BatteryService(  872): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  872):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  872): Plugged
,I/MotionRecognitionService(  872): setPowerConnected  = true
,V/HeadsetService( 3234): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3234): Disconnected process message: 10
,D/KeyguardUpdateMonitor( 1168): received broadcast android.intent.action.BATTERY_CHANGED
,D/STATUSBAR-PhoneStatusBar( 1168):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1168): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1168): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1168): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/KeyguardUpdateMonitor( 1168): handleBatteryUpdate
,D/DateView( 1168): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1168): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/ConnectivityService(  872): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  872): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/BooksSync( 7369): Starting books sync, d
,D/ConnectivityService(  872): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,V/GLSActivity( 1676): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/art     ( 1676): Explicit concurrent mark sweep GC freed 60064(3MB) AllocSpace objects, 60(4MB) LOS objects, 39% free, 18MB/30MB, paused 881us total 107.488ms
,I/GLSUser ( 1676): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
I/GLSUser ( 1676): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1676): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1676): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1676): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ResourcesManager( 1676): creating new AssetManager and set to /system/app/Books/Books.apk
,V/BitmapFactory( 1676): DecodeImagePath(decodeResourceStream3) : res/mipmap-xxhdpi-v4/ic_launcher_play_books.png
,V/BitmapFactory( 1676): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  872): uri = 14 selection = getSealedState
D/SecContentProvider2(  872): mCursor = null
,D/SecContentProvider2(  872): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  872): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
V/ApplicationPolicy(  872): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,W/GLSActivity( 1676): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1676): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1676): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1676): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1676): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1676): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1676): 	at android.os.Binder.execTransact(Binder.java:446)
,E/BooksAccountManager( 7369): Authentication error
E/BooksAccountManager( 7369): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 7369): android.accounts.AccountManager.convertErrorToException(AccountManager.java:1893)
E/HttpHelper( 7369): null auth token
,I/qtaguid ( 7369): Tagging socket 34 with tag 10000000000{256,0} uid -1, pid: 7369, getuid(): 10082
,D/StatusBar( 1168): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,I/PhoneStatusBar( 1168): Icon Only
,D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
,D/PanelView( 1168): There is/are notification(s) 
,D/PanelView( 1168): There is/are notification(s) 
,I/qtaguid ( 7369): Untagging socket 34
,W/ApiaryClient( 7369): Error response from books API: {
W/ApiaryClient( 7369):  "error": {
W/ApiaryClient( 7369):   "errors": [
W/ApiaryClient( 7369):    {
W/ApiaryClient( 7369):     "domain": "global",
W/ApiaryClient( 7369):     "reason": "required",
W/ApiaryClient( 7369):     "message": "Login Required",
W/ApiaryClient( 7369):     "locationType": "header",
W/ApiaryClient( 7369):     "location": "Authorization"
W/ApiaryClient( 7369):    }
W/ApiaryClient( 7369):   ],
W/ApiaryClient( 7369):   "code": 401,
W/ApiaryClient( 7369):   "message": "Login Required"
W/ApiaryClient( 7369):  }
W/ApiaryClient( 7369): }
,W/ApiaryClient( 7369): errCount = 1: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 7369): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3DS0HXd4TFLU4&nonce=5771758525787256508&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 7369): Headers suppressed
,D/ConnectivityService(  872): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/SMD     (  279): DCD ON,
,V/GLSActivity( 1676): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1676): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
,I/GLSUser ( 1676): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1676): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1676): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1676): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/BitmapFactory( 1676): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  872): uri = 14 selection = getSealedState
,D/SecContentProvider2(  872): mCursor = null
D/SecContentProvider2(  872): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  872): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy(  872): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/StatusBar( 1168): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,I/PhoneStatusBar( 1168): Icon Only
,D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
D/PanelView( 1168): There is/are notification(s) 
,D/PanelView( 1168): There is/are notification(s) 
,W/GLSActivity( 1676): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1676): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1676): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1676): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1676): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1676): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1676): 	at android.os.Binder.execTransact(Binder.java:446)
,E/BooksAccountManager( 7369): Authentication error
E/BooksAccountManager( 7369): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 7369): android.accounts.AccountManager.convertErrorToException(AccountManager.java:1893)
,E/HttpHelper( 7369): null auth token
,I/qtaguid ( 7369): Tagging socket 34 with tag 10000000000{256,0} uid -1, pid: 7369, getuid(): 10082
,I/qtaguid ( 7369): Untagging socket 34
,W/ApiaryClient( 7369): Error response from books API: {
W/ApiaryClient( 7369):  "error": {
W/ApiaryClient( 7369):   "errors": [
W/ApiaryClient( 7369):    {
W/ApiaryClient( 7369):     "domain": "global",
W/ApiaryClient( 7369):     "reason": "required",
W/ApiaryClient( 7369):     "message": "Login Required",
W/ApiaryClient( 7369):     "locationType": "header",
W/ApiaryClient( 7369):     "location": "Authorization"
W/ApiaryClient( 7369):    }
W/ApiaryClient( 7369):   ],
W/ApiaryClient( 7369):   "code": 401,
W/ApiaryClient( 7369):   "message": "Login Required"
W/ApiaryClient( 7369):  }
W/ApiaryClient( 7369): }
,W/ApiaryClient( 7369): errCount = 2: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 7369): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3DS0HXd4TFLU4&nonce=5771758525787256508&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 7369): Headers suppressed
,D/ConnectivityService(  872): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,V/GLSActivity( 1676): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1676): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
,I/GLSUser ( 1676): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1676): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1676): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1676): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/BitmapFactory( 1676): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  872): uri = 14 selection = getSealedState
,D/SecContentProvider2(  872): mCursor = null
D/SecContentProvider2(  872): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  872): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy(  872): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/StatusBar( 1168): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,I/PhoneStatusBar( 1168): Icon Only
,D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
D/PanelView( 1168): There is/are notification(s) 
,D/PanelView( 1168): There is/are notification(s) 
,W/GLSActivity( 1676): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1676): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1676): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1676): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1676): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1676): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1676): 	at android.os.Binder.execTransact(Binder.java:446)
,E/BooksAccountManager( 7369): Authentication error
E/BooksAccountManager( 7369): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 7369): android.accounts.AccountManager.convertErrorToException(AccountManager.java:1893)
,E/HttpHelper( 7369): null auth token
,I/qtaguid ( 7369): Tagging socket 34 with tag 10000000000{256,0} uid -1, pid: 7369, getuid(): 10082
,I/qtaguid ( 7369): Untagging socket 34
,W/ApiaryClient( 7369): Error response from books API: {
W/ApiaryClient( 7369):  "error": {
W/ApiaryClient( 7369):   "errors": [
W/ApiaryClient( 7369):    {
W/ApiaryClient( 7369):     "domain": "global",
W/ApiaryClient( 7369):     "reason": "required",
W/ApiaryClient( 7369):     "message": "Login Required",
W/ApiaryClient( 7369):     "locationType": "header",
W/ApiaryClient( 7369):     "location": "Authorization"
W/ApiaryClient( 7369):    }
W/ApiaryClient( 7369):   ],
W/ApiaryClient( 7369):   "code": 401,
W/ApiaryClient( 7369):   "message": "Login Required"
W/ApiaryClient( 7369):  }
W/ApiaryClient( 7369): }
,W/ApiaryClient( 7369): errCount = 3: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 7369): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3DS0HXd4TFLU4&nonce=5771758525787256508&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 7369): Headers suppressed
,D/ConnectivityService(  872): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/BooksSync( 7369): Soft error
E/BooksSync( 7369): com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
E/BooksSync( 7369): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3DS0HXd4TFLU4&nonce=5771758525787256508&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
E/BooksSync( 7369): Headers suppressed
E/BooksSync( 7369): 
E/BooksSync( 7369): com.google.android.apps.books.net.HttpHelper.wrapExceptionBasedOnStatus(HttpHelper.java:212)
,E/BooksSync( 7369): Sync error
E/BooksSync( 7369): com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
E/BooksSync( 7369): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3DS0HXd4TFLU4&nonce=5771758525787256508&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
E/BooksSync( 7369): Headers suppressed
E/BooksSync( 7369): 
E/BooksSync( 7369): com.google.android.apps.books.net.HttpHelper.wrapExceptionBasedOnStatus(HttpHelper.java:212)
,I/BooksSync( 7369): Finished books sync
,D/ConnectivityService(  872): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SyncManager(  872): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 218219, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,D/ConnectivityService(  872): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/SMD     (  279): DCD ON
,D/SecContentProvider2(  872): uri = 11 selection = getMyKnoxAdmin
,D/SecContentProvider2(  872): mCursor = null
,D/ConnectivityService(  872): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/ServiceManager(  319): Waiting for service AtCmdFwd...
,D/SSRM:m  (  872): SIOP:: AP = 290, PST = 299, CUR = 300
,I/ServiceManager(  319): Waiting for service AtCmdFwd...
,I/ServiceManager(  319): Waiting for service AtCmdFwd...
,E/SMD     (  279): DCD ON
,I/ServiceManager(  319): Waiting for service AtCmdFwd...
,I/ServiceManager(  319): Waiting for service AtCmdFwd...
,W/ContextImpl(  872): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,W/Atfwd_Sendcmd(  319): AtCmdFwd service not published, waiting... retryCnt : 3
,D/BatteryService(  872): level:100, scale:100, status:5, health:2, present:true, voltage: 4386, temperature: 284, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  872): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  872): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  872):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  872): Plugged
,D/BatteryService(  872): stay LED for fully charged
,I/MotionRecognitionService(  872): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1168): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1168): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1168):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3234): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3234): Disconnected process message: 10
,D/BatteryMeterView( 1168): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1168): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1168): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  279): DCD ON
,E/Watchdog(  872): !@Sync 8
,D/ConnectivityService(  872): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/SMD     (  279): DCD ON
,D/SSRM:m  (  872): SIOP:: AP = 290, PST = 297, CUR = 300
,E/SMD     (  279): DCD ON
,E/SMD     (  279): DCD ON
,D/BatteryService(  872): level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 284, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  872): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  872): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  872):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  872): Plugged
,I/MotionRecognitionService(  872): setPowerConnected  = true
,D/BatteryService(  872): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1168): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1168): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1168):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1168): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1168): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1168): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3234): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3234): Disconnected process message: 10
,E/SMD     (  279): DCD ON
,I/ServiceManager(  319): Waiting for service AtCmdFwd...
,D/SSRM:m  (  872): SIOP:: AP = 290, PST = 295, CUR = 300
,E/SMD     (  279): DCD ON
,I/ServiceManager(  319): Waiting for service AtCmdFwd...
,I/ServiceManager(  319): Waiting for service AtCmdFwd...
,I/ServiceManager(  319): Waiting for service AtCmdFwd...
,E/SMD     (  279): DCD ON
,I/ServiceManager(  319): Waiting for service AtCmdFwd...
,W/ContextImpl(  872): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,W/Atfwd_Sendcmd(  319): AtCmdFwd service not published, waiting... retryCnt : 4
,V/AlarmManager(  872): waitForAlarm result :4
,D/ConnectivityService(  872): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  872): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/GLSUser ( 1676): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
I/GLSUser ( 1676): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1676): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1676): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1676): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ResourcesManager( 1676): creating new AssetManager and set to /system/app/PlusOne/PlusOne.apk
,V/BitmapFactory( 1676): DecodeImagePath(decodeResourceStream3) : res/mipmap-xxhdpi-v4/quantum_logo_google_plus_color_44in48.png
,V/BitmapFactory( 1676): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  872): uri = 14 selection = getSealedState
,D/SecContentProvider2(  872): mCursor = null
D/SecContentProvider2(  872): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  872): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
V/ApplicationPolicy(  872): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/StatusBar( 1168): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,I/PhoneStatusBar( 1168): Icon Only
D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
D/PanelView( 1168): There is/are notification(s) 
D/PanelView( 1168): There is/are notification(s) 
,E/HttpOperation( 6628): [kfu{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
E/HttpOperation( 6628): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 6628): 	at kfv.a(PG:65)
E/HttpOperation( 6628): 	at kff.u(PG:385)
E/HttpOperation( 6628): 	at kfb.a(PG:29)
E/HttpOperation( 6628): 	at kff.l(PG:132)
E/HttpOperation( 6628): 	at dsf.a(PG:807)
E/HttpOperation( 6628): 	at fhk.a(PG:1126)
E/HttpOperation( 6628): 	at fhk.a(PG:908)
E/HttpOperation( 6628): 	at fhk.onPerformSync(PG:636)
E/HttpOperation( 6628): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/HttpOperation( 6628): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/HttpOperation( 6628): 	at ihi.a(PG:22)
E/HttpOperation( 6628): 	at kft.a(PG:91)
E/HttpOperation( 6628): 	at kfv.a(PG:62)
E/HttpOperation( 6628): 	... 8 more
E/HttpOperation( 6628): Caused by: gdi: User intervention required. Notification has been pushed.
E/HttpOperation( 6628): 	at gde.c(Unknown Source)
E/HttpOperation( 6628): 	at gde.b(Unknown Source)
E/HttpOperation( 6628): 	at ihi.a(PG:19)
E/HttpOperation( 6628): 	... 10 more
,I/GLSUser ( 1676): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
I/GLSUser ( 1676): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1676): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1676): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1676): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/BitmapFactory( 1676): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  872): uri = 14 selection = getSealedState
D/SecContentProvider2(  872): mCursor = null
,D/SecContentProvider2(  872): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  872): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
V/ApplicationPolicy(  872): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/StatusBar( 1168): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,I/PhoneStatusBar( 1168): Icon Only
D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
D/PanelView( 1168): There is/are notification(s) 
D/PanelView( 1168): There is/are notification(s) 
,E/HttpOperation( 6628): [getmobileexperiments] Unexpected exception
E/HttpOperation( 6628): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 6628): 	at kfv.a(PG:65)
E/HttpOperation( 6628): 	at kff.u(PG:385)
E/HttpOperation( 6628): 	at kfb.a(PG:29)
E/HttpOperation( 6628): 	at kff.l(PG:132)
E/HttpOperation( 6628): 	at ieo.a(PG:43)
E/HttpOperation( 6628): 	at iep.a(PG:93)
E/HttpOperation( 6628): 	at fhn.a(PG:59)
E/HttpOperation( 6628): 	at lex.a(PG:85)
E/HttpOperation( 6628): 	at lex.b(PG:132)
E/HttpOperation( 6628): 	at fhk.a(PG:1146)
E/HttpOperation( 6628): 	at fhk.a(PG:908)
E/HttpOperation( 6628): 	at fhk.onPerformSync(PG:636)
E/HttpOperation( 6628): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/HttpOperation( 6628): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/HttpOperation( 6628): 	at ihi.a(PG:22)
E/HttpOperation( 6628): 	at kft.a(PG:91)
E/HttpOperation( 6628): 	at kfv.a(PG:62)
E/HttpOperation( 6628): 	... 12 more
E/HttpOperation( 6628): Caused by: gdi: User intervention required. Notification has been pushed.
E/HttpOperation( 6628): 	at gde.c(Unknown Source)
E/HttpOperation( 6628): 	at gde.b(Unknown Source)
E/HttpOperation( 6628): 	at ihi.a(PG:19)
E/HttpOperation( 6628): 	... 14 more
,E/ExperimentLoader( 6628): [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 6628): java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 6628): 	at kfv.a(PG:65)
E/ExperimentLoader( 6628): 	at kff.u(PG:385)
E/ExperimentLoader( 6628): 	at kfb.a(PG:29)
E/ExperimentLoader( 6628): 	at kff.l(PG:132)
E/ExperimentLoader( 6628): 	at ieo.a(PG:43)
E/ExperimentLoader( 6628): 	at iep.a(PG:93)
E/ExperimentLoader( 6628): 	at fhn.a(PG:59)
E/ExperimentLoader( 6628): 	at lex.a(PG:85)
E/ExperimentLoader( 6628): 	at lex.b(PG:132)
E/ExperimentLoader( 6628): 	at fhk.a(PG:1146)
E/ExperimentLoader( 6628): 	at fhk.a(PG:908)
E/ExperimentLoader( 6628): 	at fhk.onPerformSync(PG:636)
E/ExperimentLoader( 6628): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/ExperimentLoader( 6628): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/ExperimentLoader( 6628): 	at ihi.a(PG:22)
E/ExperimentLoader( 6628): 	at kft.a(PG:91)
E/ExperimentLoader( 6628): 	at kfv.a(PG:62)
E/ExperimentLoader( 6628): 	... 12 more
E/ExperimentLoader( 6628): Caused by: gdi: User intervention required. Notification has been pushed.
E/ExperimentLoader( 6628): 	at gde.c(Unknown Source)
E/ExperimentLoader( 6628): 	at gde.b(Unknown Source)
E/ExperimentLoader( 6628): 	at ihi.a(PG:19)
E/ExperimentLoader( 6628): 	... 14 more
,I/GLSUser ( 1676): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,I/GLSUser ( 1676): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1676): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1676): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1676): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/BitmapFactory( 1676): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  872): uri = 14 selection = getSealedState
D/SecContentProvider2(  872): mCursor = null
,D/SecContentProvider2(  872): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  872): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
V/ApplicationPolicy(  872): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,E/SQLiteLog( 1676): (10) POSIX Error : 11 SQLite Error : 3850
,D/StatusBar( 1168): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
E/HttpOperation( 6628): [getaccountstatus] Unexpected exception
E/HttpOperation( 6628): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 6628): 	at kfv.a(PG:65)
E/HttpOperation( 6628): 	at kff.u(PG:385)
E/HttpOperation( 6628): 	at kfb.a(PG:29)
E/HttpOperation( 6628): 	at ixd.a(PG:248)
E/HttpOperation( 6628): 	at ixd.b(PG:206)
E/HttpOperation( 6628): 	at ixd.a(PG:175)
E/HttpOperation( 6628): 	at fig.a(PG:78)
E/HttpOperation( 6628): 	at lex.a(PG:85)
E/HttpOperation( 6628): 	at lex.b(PG:132)
E/HttpOperation( 6628): 	at fhk.a(PG:1146)
E/HttpOperation( 6628): 	at fhk.a(PG:908)
E/HttpOperation( 6628): 	at fhk.onPerformSync(PG:636)
E/HttpOperation( 6628): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/HttpOperation( 6628): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/HttpOperation( 6628): 	at ihi.a(PG:22)
E/HttpOperation( 6628): 	at kft.a(PG:91)
E/HttpOperation( 6628): 	at kfv.a(PG:62)
E/HttpOperation( 6628): 	... 12 more
E/HttpOperation( 6628): Caused by: gdi: User intervention required. Notification has been pushed.
E/HttpOperation( 6628): 	at gde.c(Unknown Source)
E/HttpOperation( 6628): 	at gde.b(Unknown Source)
E/HttpOperation( 6628): 	at ihi.a(PG:19)
E/HttpOperation( 6628): 	... 14 more
,E/EsSyncAdapterService( 6628): Sync failure
E/EsSyncAdapterService( 6628): java.io.IOException: Rpc failed
E/EsSyncAdapterService( 6628): 	at ixd.a(PG:348)
E/EsSyncAdapterService( 6628): 	at ixd.a(PG:248)
E/EsSyncAdapterService( 6628): 	at ixd.b(PG:206)
E/EsSyncAdapterService( 6628): 	at ixd.a(PG:175)
E/EsSyncAdapterService( 6628): 	at fig.a(PG:78)
E/EsSyncAdapterService( 6628): 	at lex.a(PG:85)
E/EsSyncAdapterService( 6628): 	at lex.b(PG:132)
E/EsSyncAdapterService( 6628): 	at fhk.a(PG:1146)
E/EsSyncAdapterService( 6628): 	at fhk.a(PG:908)
E/EsSyncAdapterService( 6628): 	at fhk.onPerformSync(PG:636)
E/EsSyncAdapterService( 6628): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/EsSyncAdapterService( 6628): Caused by: java.io.IOException: Cannot obtain authentication token
E/EsSyncAdapterService( 6628): 	at kfv.a(PG:65)
E/EsSyncAdapterService( 6628): 	at kff.u(PG:385)
E/EsSyncAdapterService( 6628): 	at kfb.a(PG:29)
E/EsSyncAdapterService( 6628): 	... 10 more
E/EsSyncAdapterService( 6628): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/EsSyncAdapterService( 6628): 	at ihi.a(PG:22)
E/EsSyncAdapterService( 6628): 	at kft.a(PG:91)
E/EsSyncAdapterService( 6628): 	at kfv.a(PG:62)
E/EsSyncAdapterService( 6628): 	... 12 more
E/EsSyncAdapterService( 6628): Caused by: gdi: User intervention required. Notification has been pushed.
E/EsSyncAdapterService( 6628): 	at gde.c(Unknown Source)
E/EsSyncAdapterService( 6628): 	at gde.b(Unknown Source)
E/EsSyncAdapterService( 6628): 	at ihi.a(PG:19)
E/EsSyncAdapterService( 6628): 	... 14 more
D/ConnectivityService(  872): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/PhoneStatusBar( 1168): Icon Only
D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
D/PanelView( 1168): There is/are notification(s) 
D/PanelView( 1168): There is/are notification(s) 
,D/SyncManager(  872): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, PERIODIC, currentRunTime 250872, reason: Periodic, SyncResult: stats [ numIoExceptions: 2]
D/ConnectivityService(  872): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  872): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SecContentProvider2(  872): uri = 11 selection = getMyKnoxAdmin
D/SecContentProvider2(  872): mCursor = null
,E/SMD     (  279): DCD ON
,E/SQLiteLog( 1676): (10) POSIX Error : 11 SQLite Error : 3850
,E/SMD     (  279): DCD ON
,I/PowerManagerService(  872): [PWL] Off : 140s ago
,D/SSRM:m  (  872): SIOP:: AP = 290, PST = 294, CUR = 300
,E/SMD     (  279): DCD ON,
,E/SMD     (  279): DCD ON
,E/Watchdog(  872): !@Sync 9
,V/AlarmManager(  872): waitForAlarm result :8
,E/SMD     (  279): DCD ON
,D/SSRM:m  (  872): SIOP:: AP = 290, PST = 293, CUR = 300
,E/SMD     (  279): DCD ON
,W/ContextImpl(  872): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  279): DCD ON
,I/ServiceManager(  319): Waiting for service AtCmdFwd...
,I/ServiceManager(  319): Waiting for service AtCmdFwd...
,I/ServiceManager(  319): Waiting for service AtCmdFwd...
,E/SMD     (  279): DCD ON
,I/ServiceManager(  319): Waiting for service AtCmdFwd...
,I/ServiceManager(  319): Waiting for service AtCmdFwd...
,W/Atfwd_Sendcmd(  319): AtCmdFwd service not published, waiting... retryCnt : 5
,D/SSRM:m  (  872): SIOP:: AP = 290, PST = 292, CUR = 300
,E/SMD     (  279): DCD ON
,E/SMD     (  279): DCD ON
,V/AlarmManager(  872): waitForAlarm result :4
,D/KeyguardUpdateMonitor( 1168): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1168): handleTimeUpdate
,D/KeyguardEffectViewController( 1168): onReceive action : android.intent.action.TIME_TICK
,I/KeyguardEffectViewController( 1168): *** don't update sliding image ***
,D/BatteryService(  872): level:100, scale:100, status:5, health:2, present:true, voltage: 4383, temperature: 284, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  872): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
D/BatteryService(  872): stay LED for fully charged
,D/BatteryService(  872): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1168): received broadcast android.intent.action.BATTERY_CHANGED
,D/STATUSBAR-PhoneStatusBar( 1168):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/MotionRecognitionService(  872):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  872): Plugged
I/MotionRecognitionService(  872): setPowerConnected  = true
,V/HeadsetService( 3234): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3234): Disconnected process message: 10
,D/BatteryMeterView( 1168): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/KeyguardUpdateMonitor( 1168): handleBatteryUpdate
D/BatteryMeterView( 1168): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1168): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/DateView( 1168): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1168): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/ConnectivityService(  872): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/SMD     (  279): DCD ON
,E/SMD     (  279): DCD ON
,D/SSRM:m  (  872): SIOP:: AP = 290, PST = 291, CUR = 300
,E/SMD     (  279): DCD ON
,D/TimaService(  872): TIMA: TimaService scheduler is intialized. 
,D/TimaService(  872): TimaServiceHandler.handleMessage what =1
,D/TimaService(  872): TIMA: checkEvent, operation: 50000 subject: 10000
,I/TLC_TIMA_PKM_initialize(  872): initializing...
,I/TLC_TIMA_PKM_initialize(  872): root = /firmware/image, root_strlen = 15
,I/TLC_TIMA_PKM_initialize(  872): process = tima_pkm, process_strlen = 8
,I/TZ: qc_tlc_communication(  872): root = /firmware/image, root_len = 15
,I/TZ: qc_tlc_communication(  872): process = tima_pkm, process_strlen = 8
,I/TZ: qc_tlc_communication(  872): aligned max_sendmsg_size = 262208 = 0x40040
,I/TZ: qc_tlc_communication(  872): aligned max_recvmsg_size = 262208 = 0x40040
,I/TZ: qc_tlc_communication(  872): max_message_size = 524416 = 0x80080
,D/QSEECOMAPI: (  872): QSEECom_get_handle sb_length = 0x80080
,D/QSEECOMAPI: (  872): App is not loaded in QSEE
,D/QSEECOMAPI: (  872): Loaded image: APP id = 2
,I/TZ: qc_tlc_communication(  872): TIMA: path = /firmware/image, fname = tima_pkm, tzapp is loaded
,I/TLC_TIMA_PKM_initialize(  872): Trustlet response is completed
,W/ContextImpl(  872): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/jxcore-log( 7436): --= Surplus to requirements =--
I/jxcore-log( 7436): 
,I/jxcore-log( 7436): ****TEST TOOK:  ms ****
I/jxcore-log( 7436): 
,I/jxcore-log( 7436): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 7436): 
,E/SMD     (  279): DCD ON
,E/Watchdog(  872): !@Sync 10
,D/AndroidRuntime( 8368): 
D/AndroidRuntime( 8368): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
,D/AndroidRuntime( 8368): CheckJNI is OFF
,D/AndroidRuntime( 8368): setted country_code = Germany
,D/AndroidRuntime( 8368): setted countryiso_code = DE
,D/AndroidRuntime( 8368): setted sales_code = DBT
D/AndroidRuntime( 8368): readGMSProperty: start
D/AndroidRuntime( 8368): readGMSProperty: already setted!!
,D/AndroidRuntime( 8368): readGMSProperty: end
D/AndroidRuntime( 8368): addProductProperty: start
,D/BatteryService(  872): level:100, scale:100, status:5, health:2, present:true, voltage: 4377, temperature: 284, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  872): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
D/BatteryService(  872): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  872): stay LED for fully charged
,D/MotionRecognitionService(  872):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
I/MotionRecognitionService(  872): Plugged
I/MotionRecognitionService(  872): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1168): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1168): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1168):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
V/HeadsetService( 3234): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED,
D/HeadsetStateMachine( 3234): Disconnected process message: 10
,D/BatteryMeterView( 1168): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1168): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1168): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/TLC_TIMA_PKM_measure_kernel(  872): TIMA: response_id = 3
I/TLC_TIMA_PKM_measure_kernel(  872): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService(  872): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService(  872): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,E/AffinityControl( 8368): AffinityControl: registerfunction enter
,D/AndroidRuntime( 8368): Calling main entry com.android.commands.pm.Pm
,D/PackageManager(  872): START PACKAGE DELETE: observer{810723942}
D/PackageManager(  872): pkg{<packageName>}
D/PackageManager(  872): user{0}
D/PackageManager(  872): caller{2000}
D/PackageManager(  872): flags{3}
D/PersonaManagerService(  872): isFromApprovedUnInstaller: uid, userId, appid : 2000 0 2000
D/PersonaManagerService(  872): isFromApprovedUnInstaller: isApproved : true
D/PersonaManagerService(  872): isFromApprovedUnInstaller: isApproved before exit: true
D/PackageManager(  872): deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag3
D/PackageManager(  872): deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag3
,D/PackageManager(  872): [MSG] DELETE_PACKAGE_AS_USER
,D/PackageManagerService(  872): deletePackage- pkg:com.test.thalitest, edmuserId:0
D/PackageManagerService(  872): deletePackage- pkg:com.test.thalitest, edmuserId:-1
,D/ApplicationPolicy(  872): getApplicationUninstallationEnabled
,D/ApplicationPolicy(  872): getApplicationUninstallationEnabled :  enabled true
,D/PackageManager(  872): !@killApplicatoin: 10367, uninstall pkg
,I/ActivityManager(  872): Force stopping com.test.thalitest appid=10367 user=-1: uninstall pkg
,I/ActivityManager(  872): Killing 7436:com.test.thalitest/u0a367 (adj 0): stop com.test.thalitest
,I/ActivityManager(  872):   Force finishing activity ActivityRecord{296b5bfa u0 com.test.thalitest/.MainActivity t11}
,D/FocusedStackFrame(  872): Set to : 0
,D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
,D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
,D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
,I/SurfaceFlinger(  249): id=15 Removed com.test.thalitest/com.test.thalitest.MainActivity (5/8)
,I/SurfaceFlinger(  249): id=15 Removed com.test.thalitest/com.test.thalitest.MainActivity (-2/8)
D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1168): value : false
,D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
,D/WifiService(  872): Client connection lost with reason: 4
,W/PackageSettings(  872): Skipping PackageSetting{19d099ec com.example.hello/10375} due to missing metadata
,I/ActivityManager(  872): Force stopping com.test.thalitest appid=10367 user=0: pkg removed
,D/ConnectivityService(  872): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/art     ( 1569): Explicit concurrent mark sweep GC freed 10368(695KB) AllocSpace objects, 1(39KB) LOS objects, 39% free, 16MB/27MB, paused 431us total 36.844ms
,I/art     ( 4526): Explicit concurrent mark sweep GC freed 4026(225KB) AllocSpace objects, 1(16KB) LOS objects, 40% free, 14MB/24MB, paused 324us total 48.055ms
,D/ResourcesManager(  872): creating new AssetManager and set to /system/priv-app/InputDevices/InputDevices.apk
,I/InputReader(  872): Reconfiguring input devices.  changes=0x00000010
,D/ResourcesManager( 1489): creating new AssetManager and set to /system/app/AccuweatherPhone2014_K_LMR_fHD/AccuweatherPhone2014_K_LMR_fHD.apk
,W/ResourcesManager( 1489): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 1489): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 1489): Asset path '/system/framework/sws.jar' does not exist or contains no resources.
,E/libprocessgroup(  872): failed to kill 1 processes for processgroup 7436
,D/ResourcesManager( 1489): creating new AssetManager and set to /system/app/SPlannerWidget_OS_UPG/SPlannerWidget_OS_UPG.apk
,W/ResourcesManager( 1489): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,E/SamsungIME( 1866): mOCRHelper is null
W/ResourcesManager( 1489): Asset path '/system/framework/sws.jar' does not exist or contains no resources.
,W/GeofencerStateMachine( 2209): Ignoring removeGeofence because network location is disabled.
,I/KLMS-2.4.503: ( 7679): KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,I/KLMS-2.4.503: ( 7679): MainReciver(): EventNotificationReciver- method called: AppActivityListner onReceive for Intent Action : android.intent.action.PACKAGE_REMOVED , timestamp: 1452294509983
,I/KLMS-2.4.503: ( 7679): MainReciver(): PACKAGE_REMOVED
,I/KLMS-2.4.503: ( 7679): MainReciver(): REPLACING: false | pkgName: com.test.thalitest
,D/ResourcesManager(  872): creating new AssetManager and set to /system/priv-app/Velvet/Velvet.apk
,D/ResourcesManager(  872): creating new AssetManager and set to /system/app/SamsungIME/SamsungIME.apk
,I/art     (  872): Explicit concurrent mark sweep GC freed 58773(3MB) AllocSpace objects, 56(1481KB) LOS objects, 30% free, 36MB/52MB, paused 1.668ms total 177.702ms
,I/art     (  872): WaitForGcToComplete blocked for 18.062ms for cause Explicit
,D/ResourcesManager(  872): creating new AssetManager and set to /data/app/com.google.android.gms-1/base.apk
,D/ResourcesManager(  872): creating new AssetManager and set to /system/priv-app/SNS/SNS.apk
,D/ResourcesManager(  872): creating new AssetManager and set to /system/priv-app/Samsungservice2_xxhdpi/Samsungservice2_xxhdpi.apk
,D/ResourcesManager(  872): creating new AssetManager and set to /system/app/ChatON_MARKET/ChatON_MARKET.apk
,D/ResourcesManager(  872): creating new AssetManager and set to /system/app/Dropbox/Dropbox.apk
,D/ResourcesManager(  872): creating new AssetManager and set to /system/app/Gmail2/Gmail2.apk
,E/ActivityManager(  872): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  872): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  872): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  872): checkUser: useridlist=null, currentuser=0
,D/ResourcesManager(  872): creating new AssetManager and set to /system/app/talkback/talkback.apk
,D/SecContentProvider2(  872): uri = 11 selection = getMyKnoxAdmin
D/SecContentProvider2(  872): mCursor = null
,E/Zygote  ( 8399): MountEmulatedStorage()
E/Zygote  ( 8399): v2
I/libpersona( 8399): KNOX_SDCARD checking this for 10104
I/libpersona( 8399): KNOX_SDCARD not a persona
,I/ActivityManager(  872): Start proc com.sec.esdk.elm for broadcast com.sec.esdk.elm/.receiver.MainReceiver: pid=8399 uid=10104 gids={50104, 9997, 3003} abi=armeabi-v7a
,D/ResourcesManager(  872): creating new AssetManager and set to /system/app/SBrowser/SBrowser.apk
,D/ResourcesManager(  872): creating new AssetManager and set to /system/app/SecEmail_K/SecEmail_K.apk
,D/ResourcesManager(  872): creating new AssetManager and set to /system/priv-app/GoogleServicesFramework/GoogleServicesFramework.apk
,I/SELinux ( 8399): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,D/RegisteredServicesCache( 1459): empty dynamic service
,I/SELinux ( 8399): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 8399): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/ResourcesManager(  872): creating new AssetManager and set to /system/priv-app/SHealth3_5/SHealth3_5.apk
,D/ResourcesManager(  872): creating new AssetManager and set to /system/priv-app/SecGallery2014/SecGallery2014.apk
,D/EnterpriseDeviceManagerService(  872): Package has changed for user 0
D/TimaKeyStoreProvider( 8399): TimaSignature is unavailable
,D/ActivityThread( 8399): Added TimaKeyStore provider
,D/ResourcesManager(  872): creating new AssetManager and set to /system/priv-app/sCloudSyncCalendar/sCloudSyncCalendar.apk
D/EnterpriseDeviceManagerService(  872): Admin package name: com.google.android.gms
,D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
,D/ResourcesManager(  872): creating new AssetManager and set to /system/priv-app/sCloudSyncContacts/sCloudSyncContacts.apk
,D/ResourcesManager(  872): creating new AssetManager and set to /system/priv-app/sCloudSyncMemo/sCloudSyncMemo.apk
,D/ResourcesManager(  872): creating new AssetManager and set to /system/priv-app/sCloudSyncSBrowser/sCloudSyncSBrowser.apk
,D/ResourcesManager(  872): creating new AssetManager and set to /system/priv-app/sCloudSyncSNote3/sCloudSyncSNote3.apk
,D/ResourcesManager(  872): creating new AssetManager and set to /system/app/Books/Books.apk
,D/ResourcesManager(  872): creating new AssetManager and set to /system/app/Chrome/Chrome.apk
,D/ResourcesManager(  872): creating new AssetManager and set to /system/app/Drive/Drive.apk
,D/ResourcesManager(  872): creating new AssetManager and set to /system/priv-app/SecContacts/SecContacts.apk
,D/ResourcesManager(  872): creating new AssetManager and set to /system/app/EditorsDocs/EditorsDocs.apk
,D/SurfaceWidgetView( 1489): destroyHardwareResources():254796797
D/ResourcesManager( 8399): creating new AssetManager and set to /system/app/ELMAgent/ELMAgent.apk
,D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
,V/WindowOrientationListener(  872): mSContextAutoRotationListener.getProposedRotation, mbResultFaceDectection: false
V/WindowOrientationListener(  872): mSContextAutoRotationListener.getProposedRotation, Rotation: -1
V/WindowManager(  872): rotationForOrientationLw(orient=1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false
V/WindowOrientationListener(  872): mSContextAutoRotationListener.getProposedRotation, mbResultFaceDectection: false
V/WindowOrientationListener(  872): mSContextAutoRotationListener.getProposedRotation, Rotation: -1
,D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
,D/Launcher( 1489): onRestart, Launcher: 715674170
,D/Launcher( 1489): onStart, Launcher: 715674170
D/Launcher.HomeView( 1489): onStart
,W/Resources(  872): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager(  872): creating new AssetManager and set to /system/priv-app/SecMms_Candy/SecMms_Candy.apk
,D/ResourcesManager(  872): creating new AssetManager and set to /system/app/GoogleCalendarSyncAdapter/GoogleCalendarSyncAdapter.apk
,D/SurfaceWidgetClient$ISurfaceWidgetStub( 2142): [237392/6] Surface widget visibility changed visibility = true on instance = 1
,D/SurfaceWidget.Renderer( 2142): [237392/6] SurfaceWidget drawing first frame
,D/ResourcesManager(  872): creating new AssetManager and set to /system/app/GoogleContactsSyncAdapter/GoogleContactsSyncAdapter.apk
,D/ResourcesManager(  872): creating new AssetManager and set to /system/app/Music2/Music2.apk
,D/ResourcesManager(  872): creating new AssetManager and set to /system/app/Newsstand/Newsstand.apk
,W/Resources(  872): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/ResourcesManager(  872): creating new AssetManager and set to /system/app/PlusOne/PlusOne.apk
,D/elm:14451( 8399): ELMAbstractReceiver.onReceive() : Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.receiver.MainReceiver (has extras) }
,D/elm:14451( 8399): ELMEngine.ELMEngine( context ).
,D/elm:14451( 8399): MDMBridge.setEnterpriseBridge()
,D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
,I/SurfaceFlinger(  249): id=18 createSurf (1080x1920),1 flag=4, com.sec.android.app.launcher/com.android.launcher2.Launcher
,D/StatusBarManagerService(  872): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
,D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1168): value : false
,D/ResourcesManager(  872): creating new AssetManager and set to /system/app/SecExchange/SecExchange.apk
,D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
,D/StatusBarManagerService(  872): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
D/LockPatternUtilsCache( 1168): value : false
,D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
,D/elm:14451( 8399): ELMAbstractReceiver : Receive Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) } END.
,D/ResourcesManager(  872): creating new AssetManager and set to /system/app/Videos/Videos.apk
,E/ActivityManager(  872): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  872): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  872): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  872): checkUser: useridlist=null, currentuser=0
,D/InputMethodManagerService(  872): windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,D/elm:14451( 8399): ElmAgentService : onCreate()
,D/elm:14451( 8399): ElmAgentService : onHandleIntent() Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) }
D/elm:14451( 8399): MainReceiver.listeningToPackageRemoved()
,E/Zygote  ( 8418): MountEmulatedStorage()
D/elm:14451( 8399): MDMBridge.getInstance()
I/libpersona( 8418): KNOX_SDCARD checking this for 10017
E/Zygote  ( 8418): v2
I/libpersona( 8418): KNOX_SDCARD not a persona
D/elm:14451( 8399): MDMBridge.getAllLicenseInfoFromSDK()
,W/ContextImpl(  872): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.android.server.InputMethodManagerService$6.run:2728 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
W/InputMethodManagerService(  872): Got RemoteException sending setActive(false) notification to pid 7436 uid 10367
,I/ActivityManager(  872): Start proc com.sec.android.service.health for broadcast com.sec.android.service.health/.upgrade.UninstallReceiver: pid=8418 uid=10017 gids={50017, 9997} abi=armeabi-v7a
,W/Resources(  872): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/ResourcesManager(  872): creating new AssetManager and set to /system/app/SecMemoDL/SecMemoDL.apk
,W/Resources(  872): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/ResourcesManager(  872): creating new AssetManager and set to /system/app/YouTube/YouTube.apk
,D/RCPManagerService(  872): PackageReceiver onReceive()
I/HarmonyEASService(  872): onReceive : android.intent.action.PACKAGE_REMOVED for 0
,I/SELinux ( 8418): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
,I/SELinux ( 8418): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 8418): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/elm:14451( 8399): MDMBridge.getAllLicenseInfoFromSDK()
,D/KnoxMUMContainerPolicy(  872): mPackageReceiver : action - android.intent.action.PACKAGE_REMOVED
,D/BackupManagerService(  872): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
,D/JobSchedulerService(  872): Receieved: android.intent.action.PACKAGE_REMOVED
,D/ResourcesManager(  872): creating new AssetManager and set to /system/priv-app/SFinder/SFinder.apk
,D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
,D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
,D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
,D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
V/EnterpriseBillingPolicy(  872): packageModificationReceiver - onreceive - start - android.intent.action.PACKAGE_REMOVED
V/EnterpriseBillingPolicy(  872): uID is 10367
,V/EnterpriseBillingPolicy(  872): Removed Packageuid is0
V/EnterpriseBillingPolicyStorage(  872): getProfileForApplication - enter
D/TimaKeyStoreProvider( 8418): TimaSignature is unavailable
,D/ActivityThread( 8418): Added TimaKeyStore provider
,D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
,V/EnterpriseBillingPolicyStorage(  872): getProfileForApplication - exit null
D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
V/EnterpriseBillingPolicy(  872): packageModificationReceiver - onreceive - personal application - profile null
V/EnterpriseBillingPolicy(  872): packageModificationReceiver - onreceive - might be a vpn vendor package 
V/EnterpriseBillingPolicyStorage(  872): getBillingProfileForVpnEngine - start - com.test.thalitest
,V/EnterpriseBillingPolicyStorage(  872): getBillingProfileForVpnEngine - end - null
,D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
,D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
,W/Resources(  872): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
,W/Resources(  872): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager(  872): creating new AssetManager and set to /system/app/ChatON_MARKET/ChatON_MARKET.apk
,D/elm:14451( 8399): ElmAgentService : onDestroy().
,I/Timeline(  872): Timeline: Activity_windows_visible id: ActivityRecord{2b8f4a58 u0 com.sec.android.app.launcher/com.android.launcher2.Launcher t9} time:314812
D/TaskPersister(  872): removeObsoleteFile: deleting file=11_task.xml
D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
,D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
D/TaskPersister(  872): removeObsoleteFile: deleting file=11_task_thumbnail.png
,W/Resources(  872): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/ResourcesManager(  872): creating new AssetManager and set to /system/app/Chrome/Chrome.apk
,I/ActivityManager(  872): Killing 7034:com.samsung.android.magazine.service/u0a118 (adj 15): bgCount ##41
,D/ResourcesManager( 8418): creating new AssetManager and set to /system/priv-app/HealthService/HealthService.apk
,D/ResourcesManager(  872): creating new AssetManager and set to /system/app/Drive/Drive.apk
,I/art     (  872): Explicit concurrent mark sweep GC freed 12248(586KB) AllocSpace objects, 0(0B) LOS objects, 30% free, 36MB/52MB, paused 6.879ms total 277.955ms
,D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
,D/ResourcesManager(  872): creating new AssetManager and set to /system/app/Dropbox/Dropbox.apk
,D/com.sec.android.service.health.upgrade.UninstallReceiver( 8418): onReceive()
I/com.sec.android.service.health.upgrade.UninstallReceiver( 8418): onReceive called  PACKAGE_REMOVED package:com.test.thalitest
D/com.sec.android.service.health.upgrade.UninstallReceiver( 8418): onReceive() : package name is not s health. Return !!!
,D/ResourcesManager(  872): creating new AssetManager and set to /system/app/EditorsDocs/EditorsDocs.apk
,D/ResourcesManager(  872): creating new AssetManager and set to /system/app/InteractiveTutorial/InteractiveTutorial.apk
,I/PCWCLIENTTRACE_PushUtil( 6771): SPPPushClient is installed : true
,I/PCWCLIENTTRACE_PushUtil( 6771): sales region : global
I/PCWCLIENTTRACE_PushUtil( 6771): getPushTypeList : [SPP, GCM]
I/PCWCLIENTTRACE_SYSTEMReceiver( 6771): [onReceive] - android.intent.action.PACKAGE_REMOVED
,E/ActivityManager(  872): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  872): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  872): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  872): checkUser: useridlist=null, currentuser=0
,W/Resources(  872): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/ResourcesManager(  872): creating new AssetManager and set to /system/app/Newsstand/Newsstand.apk
,E/Zygote  ( 8435): MountEmulatedStorage()
E/Zygote  ( 8435): v2
I/libpersona( 8435): KNOX_SDCARD checking this for 10034
I/libpersona( 8435): KNOX_SDCARD not a persona
,I/ActivityManager(  872): Start proc com.samsung.android.app.galaxyfinder for broadcast com.samsung.android.app.galaxyfinder/.ApplicationStatusReceiver: pid=8435 uid=10034 gids={50034, 9997, 1028, 1015, 3003, 3002} abi=armeabi-v7a
,I/ActivityManager(  872): Killing 7051:com.samsung.helphub/1000 (adj 15): bgCount ##41
,D/ResourcesManager(  872): creating new AssetManager and set to /system/app/PlayGames/PlayGames.apk
,I/SELinux ( 8435): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,W/libprocessgroup(  872): failed to open /acct/uid_10118/pid_7034/cgroup.procs: No such file or directory
,I/SELinux ( 8435): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 8435): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/art     (  307): Explicit concurrent mark sweep GC freed 8713(370KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 14MB/23MB, paused 301us total 19.044ms
,D/ResourcesManager(  872): creating new AssetManager and set to /system/app/SPlanner_OS_UPG/SPlanner_OS_UPG.apk
,I/art     (  307): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 14MB/23MB, paused 246us total 7.852ms
,D/TimaKeyStoreProvider( 8435): TimaSignature is unavailable
,D/ActivityThread( 8435): Added TimaKeyStore provider
,W/ResourcesManager(  872): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
,W/ResourcesManager(  872): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,W/ResourcesManager(  872): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,I/art     (  307): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 14MB/23MB, paused 260us total 8.309ms
,D/ResourcesManager( 8435): creating new AssetManager and set to /system/priv-app/SFinder/SFinder.apk
,W/Resources(  872): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/ResourcesManager(  872): creating new AssetManager and set to /system/app/SmartRemote_KL/SmartRemote_KL.apk
,D/PackageManager(  872): delete codoeFile: 
,D/PackageManager(  872): result of delete: 1{810723942}
W/libprocessgroup(  872): failed to open /acct/uid_1000/pid_7051/cgroup.procs: No such file or directory
,D/ResourcesManager(  872): creating new AssetManager and set to /system/app/Videos/Videos.apk
,I/FeatureConfig( 8435): init() refresh[false], Select[false], DisplayOrder[false], HelpMenu[false]
,D/AndroidRuntime( 8368): Shutting down VM
,D/ResourcesManager(  872): creating new AssetManager and set to /system/app/YouTube/YouTube.apk
,D/ResourcesManager(  872): creating new AssetManager and set to /data/app/de.pizza-1/base.apk
,D/ResourcesManager(  872): creating new AssetManager and set to /data/app/de.kaufda.android-1/base.apk
,D/ResourcesManager(  872): creating new AssetManager and set to /system/priv-app/Velvet/Velvet.apk
,D/ResourcesManager(  872): creating new AssetManager and set to /system/priv-app/SamsungMusic_20/SamsungMusic_20.apk
,W/Resources(  872): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/ResourcesManager(  872): creating new AssetManager and set to /system/priv-app/SecContacts/SecContacts.apk
,W/Resources(  872): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/ResourcesManager(  872): creating new AssetManager and set to /system/priv-app/SecGallery2014/SecGallery2014.apk
,W/Resources(  872): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources(  872): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
D/ResourcesManager(  872): creating new AssetManager and set to /system/priv-app/SecMyFiles2014/SecMyFiles2014.apk
,W/Resources(  872): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/ResourcesManager(  872): creating new AssetManager and set to /system/priv-app/SecVideoPlayer/SecVideoPlayer.apk
,W/Resources(  872): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources(  872): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
D/ResourcesManager(  872): creating new AssetManager and set to /system/priv-app/VoiceNote/VoiceNote.apk
,W/Resources(  872): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources(  872): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
D/ResourcesManager(  872): creating new AssetManager and set to /system/app/SBrowser/SBrowser.apk
,W/Resources(  872): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/UsbSettingsManager(  872): clearDefaults: com.test.thalitest
,I/CrashAnrDetector(  872): onPackageRemoved : com.test.thalitest
,D/ResourcesManager( 8435): creating new AssetManager and set to /system/priv-app/SecMms_Candy/SecMms_Candy.apk
,W/ResourcesManager( 8435): Asset path '/system/framework/minimode.jar' does not exist or contains no resources.
,W/ResourcesManager( 8435): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 8435): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
,W/ResourcesManager( 8435): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 8435): Asset path '/system/framework/imsmanager.jar' does not exist or contains no resources.
,D/ResourcesManager( 8435): creating new AssetManager and set to /system/priv-app/SecSettings/SecSettings.apk
,W/ResourcesManager( 8435): Asset path '/system/framework/sec_platform_library.jar' does not exist or contains no resources.
,W/ResourcesManager( 8435): Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
W/ResourcesManager( 8435): Asset path '/system/framework/secvisualeffect.jar' does not exist or contains no resources.
W/ResourcesManager( 8435): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
,W/ResourcesManager( 8435): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 8435): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 8435): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,D/ResourcesManager( 8435): creating new AssetManager and set to /system/app/ChatON_MARKET/ChatON_MARKET.apk
,W/ResourcesManager( 8435): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,D/ResourcesManager( 8435): creating new AssetManager and set to /system/app/InteractiveTutorial/InteractiveTutorial.apk
,D/ResourcesManager( 8435): creating new AssetManager and set to /system/app/SPlanner_OS_UPG/SPlanner_OS_UPG.apk
,W/ResourcesManager( 8435): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
,W/ResourcesManager( 8435): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 8435): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,D/ResourcesManager( 8435): creating new AssetManager and set to /system/priv-app/SecContacts/SecContacts.apk
,W/ResourcesManager( 8435): Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
,W/ResourcesManager( 8435): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 8435): Asset path '/system/framework/imsmanager.jar' does not exist or contains no resources.
,D/ResourcesManager( 8435): creating new AssetManager and set to /system/priv-app/SecGallery2014/SecGallery2014.apk
,W/ResourcesManager( 8435): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
,W/ResourcesManager( 8435): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 8435): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager( 8435): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,W/ResourcesManager( 8435): Asset path '/system/framework/secimaging.jar' does not exist or contains no resources.
W/ResourcesManager( 8435): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
W/ResourcesManager( 8435): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
,W/ResourcesManager( 8435): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,D/ResourcesManager( 8435): creating new AssetManager and set to /system/priv-app/SecMyFiles2014/SecMyFiles2014.apk
,W/ResourcesManager( 8435): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,W/ResourcesManager( 8435): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
,D/ResourcesManager( 8435): creating new AssetManager and set to /system/priv-app/SecVideoPlayer/SecVideoPlayer.apk
,W/ResourcesManager( 8435): Asset path '/system/framework/minimode.jar' does not exist or contains no resources.
,W/ResourcesManager( 8435): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 8435): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager( 8435): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 8435): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
,D/ResourcesManager( 8435): creating new AssetManager and set to /system/app/SBrowser/SBrowser.apk
,W/ResourcesManager( 8435): Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
,W/ResourcesManager( 8435): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 8435): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,D/ResourcesManager( 8435): creating new AssetManager and set to /system/app/SecEmail_K/SecEmail_K.apk
,W/ResourcesManager( 8435): Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
,W/ResourcesManager( 8435): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 8435): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager( 8435): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,D/ResourcesManager( 8435): creating new AssetManager and set to /system/app/SecMemoDL/SecMemoDL.apk
,W/ResourcesManager( 8435): Asset path '/system/framework/secmediarecorder.jar' does not exist or contains no resources.
,W/ResourcesManager( 8435): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
,D/ResourcesManager( 8435): creating new AssetManager and set to /system/app/Chrome/Chrome.apk
,D/ResourcesManager( 8435): creating new AssetManager and set to /system/priv-app/SamsungMusic_20/SamsungMusic_20.apk
,W/ResourcesManager( 8435): Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
,W/ResourcesManager( 8435): Asset path '/system/framework/secvisualeffect.jar' does not exist or contains no resources.
W/ResourcesManager( 8435): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 8435): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager( 8435): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,W/ResourcesManager( 8435): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
,D/ResourcesManager( 8435): creating new AssetManager and set to /system/priv-app/VoiceNote/VoiceNote.apk
,W/ResourcesManager( 8435): Asset path '/system/framework/secmediarecorder.jar' does not exist or contains no resources.
,W/ResourcesManager( 8435): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,E/ActivityManager(  872): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  872): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  872): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  872): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 8452): MountEmulatedStorage()
E/Zygote  ( 8452): v2
I/libpersona( 8452): KNOX_SDCARD checking this for 10035
I/libpersona( 8452): KNOX_SDCARD not a persona
,I/ActivityManager(  872): Start proc com.sec.android.app.shealth for broadcast com.sec.android.app.shealth/.receiver.InstalledReceiver: pid=8452 uid=10035 gids={50035, 9997, 3003, 1028, 1015, 3001, 3002} abi=armeabi-v7a
,I/ActivityManager(  872): Killing 7087:com.sec.kidsplat.installer/u0a166 (adj 15): bgCount ##41
,I/SELinux ( 8452): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 8452): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 8452): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,W/libprocessgroup(  872): failed to open /acct/uid_10166/pid_7087/cgroup.procs: No such file or directory
,D/TimaKeyStoreProvider( 8452): TimaSignature is unavailable
,D/ActivityThread( 8452): Added TimaKeyStore provider
,D/ResourcesManager( 8452): creating new AssetManager and set to /system/priv-app/SHealth3_5/SHealth3_5.apk
,F/libc    ( 8452): Fatal signal 7 (SIGBUS), code 2, fault addr 0x797c21bf in tid 8472 (AsyncTask #1)
,E/audit_log( 2138): File locking failed. error= Bad file number
E/audit_log( 2138): File locking failed. error= Bad file number
,I/EventHub(  872): Removing device '/dev/input/event4' due to inotify event
,I/EventHub(  872): Removing device '/dev/input/event5' due to inotify event
,I/EventHub(  872): Removing device '/dev/input/event6' due to inotify event
,I/EventHub(  872): Removing device '/dev/input/event7' due to inotify event
,I/EventHub(  872): Removing device '/dev/input/event8' due to inotify event
,I/EventHub(  872): Removing device '/dev/input/event9' due to inotify event
,I/EventHub(  872): Removing device '/dev/input/event10' due to inotify event
,I/EventHub(  872): Removing device '/dev/input/event11' due to inotify event
,I/qdhwcomposer(  249): handle_blank_event: dpy:0 panel power state: 0

```
