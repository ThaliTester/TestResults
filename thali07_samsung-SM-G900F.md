#### Test 5065027881383b1_thali07_samsung-SM-G900F Logs


```
--------- beginning of main
V/BitmapFactory( 1661): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
D/SecContentProvider2(  839): uri = 14 selection = getSealedState
D/SecContentProvider2(  839): mCursor = null
D/SecContentProvider2(  839): KnoxCustomManagerService offline: service is not available
D/ApplicationPolicy(  839): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
V/ApplicationPolicy(  839): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
D/StatusBar( 1172): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
I/PhoneStatusBar( 1172): Icon Only
D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
D/PanelView( 1172): There is/are notification(s) 
D/PanelView( 1172): There is/are notification(s) 
W/GLSActivity( 1661): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1661): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1661): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1661): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1661): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1661): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1661): 	at android.os.Binder.execTransact(Binder.java:446)
E/BooksAccountManager( 7492): Authentication error
E/BooksAccountManager( 7492): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 7492): android.accounts.AccountManager.convertErrorToException(AccountManager.java:1893)
E/HttpHelper( 7492): null auth token
I/qtaguid ( 7492): Tagging socket 34 with tag 10000000000{256,0} uid -1, pid: 7492, getuid(): 10082
I/qtaguid ( 7492): Tagging socket 38 with tag 10000000000{256,0} uid -1, pid: 7492, getuid(): 10082
,I/qtaguid ( 7492): Untagging socket 34
W/ApiaryClient( 7492): Error response from books API: {
W/ApiaryClient( 7492):  "error": {
W/ApiaryClient( 7492):   "errors": [
W/ApiaryClient( 7492):    {
W/ApiaryClient( 7492):     "domain": "global",
W/ApiaryClient( 7492):     "reason": "required",
W/ApiaryClient( 7492):     "message": "Login Required",
W/ApiaryClient( 7492):     "locationType": "header",
W/ApiaryClient( 7492):     "location": "Authorization"
W/ApiaryClient( 7492):    }
W/ApiaryClient( 7492):   ],
W/ApiaryClient( 7492):   "code": 401,
W/ApiaryClient( 7492):   "message": "Login Required"
W/ApiaryClient( 7492):  }
W/ApiaryClient( 7492): }
W/ApiaryClient( 7492): errCount = 2: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 7492): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3DS0HXd4TFLU4&nonce=2368831443438806055&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 7492): Headers suppressed
--------- beginning of system
D/ConnectivityService(  839): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
E/SMD     (  280): DCD ON
I/WifiStateMachine(  839): CMD_RSSI_POLL : calculateWifiScore in!
I/WifiStateMachine(  839): CMD_RSSI_POLL : calculateWifiScore out!
I/WifiStateMachine(  839): CMD_RSSI_POLL : out!
D/AndroidRuntime( 7543): 
D/AndroidRuntime( 7543): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 7543): CheckJNI is OFF
D/AndroidRuntime( 7543): setted country_code = Germany
D/AndroidRuntime( 7543): setted countryiso_code = DE
D/AndroidRuntime( 7543): setted sales_code = DBT
D/AndroidRuntime( 7543): readGMSProperty: start
D/AndroidRuntime( 7543): readGMSProperty: already setted!!
D/AndroidRuntime( 7543): readGMSProperty: end
D/AndroidRuntime( 7543): addProductProperty: start
E/AffinityControl( 7543): AffinityControl: registerfunction enter
D/AndroidRuntime( 7543): Calling main entry com.android.commands.am.Am
E/PersonaManagerService(  839): inState():  stateMachine is null !!
V/ApplicationPolicy(  839): isApplicationStateBlocked userId 0 pkgname com.test.thalitest
I/ActivityManager(  839): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
D/ResourcesManager(  839): creating new AssetManager and set to /data/app/com.test.thalitest-1/base.apk
D/CustomFrequencyManagerService(  839): acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1958400  uid : 1000  pid : 839  pkgName : ACTIVITY_RESUME_BOOSTER@6
W/ActivityManager(  839): mDVFSHelper.acquire()
D/FocusedStackFrame(  839): Set to : 0
D/Launcher.HomeView( 1487): onPause
D/Launcher( 1487): Launcher::setSystemUiTransparency(): getSystemUiVisibility() after setting  = 40000000
D/AndroidRuntime( 7543): Shutting down VM
I/SurfaceFlinger(  249): id=14 createSurf (1x1),1 flag=404, Starting com.test.thalitest
V/TaskCloserActivity( 7322): TaskCloserActivity onReceive() - com.sec.android.intent.action.HOME_PAUSE
D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
E/ActivityManager(  839): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  839): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  839): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  839): checkUser: useridlist=null, currentuser=0
E/Zygote  ( 7565): MountEmulatedStorage()
E/Zygote  ( 7565): v2
I/libpersona( 7565): KNOX_SDCARD checking this for 10367
I/libpersona( 7565): KNOX_SDCARD not a persona
D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
I/ActivityManager(  839): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=7565 uid=10367 gids={50367, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
I/SELinux ( 7565): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
I/SELinux ( 7565): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
E/SELinux ( 7565): [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
D/StatusBarManagerService(  839): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
V/GLSActivity( 1661): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
I/MicrophoneInputStream( 1554): mic_close gfk@275339cf
D/TimaKeyStoreProvider( 7565): TimaSignature is unavailable
D/ActivityThread( 7565): Added TimaKeyStore provider
V/WindowOrientationListener(  839): mSContextAutoRotationListener.getProposedRotation, mbResultFaceDectection: false
V/WindowOrientationListener(  839): mSContextAutoRotationListener.getProposedRotation, Rotation: -1
V/WindowManager(  839): rotationForOrientationLw(orient=-1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false
V/WindowOrientationListener(  839): mSContextAutoRotationListener.getProposedRotation, mbResultFaceDectection: false
V/WindowOrientationListener(  839): mSContextAutoRotationListener.getProposedRotation, Rotation: -1
V/ActivityManager(  839): Display changed displayId=0
V/AudioPolicyManager(  289): stopInput() input 30
D/Launcher.HomeView( 1487): onStop
V/audio_hw_primary(  289): in_standby: enter
D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
D/SurfaceWidgetClient$ISurfaceWidgetStub( 2115): [237392/6] Surface widget pause on instance = 1
D/accuweather( 2115): [KK AccuPhone]>>> SWW:239 [0:0] [SWW] onPause : instance = 1
D/accuweather( 2115): [KK AccuPhone]>>> SWW:254 [0:0] onPause : size = 0
D/accuweather( 2115): [KK AccuPhone]>>> SWW:545 [0:0]  unRegisterTTReceiver !! 
D/SurfaceWidgetClient$ISurfaceWidgetStub( 2115): [237392/6] Surface widget visibility changed visibility = false on instance = 1
I/HotwordRecognitionRnr( 1554): Hotword detection finished
I/GLSUser ( 1661): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
I/GLSUser ( 1661): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1661): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1661): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
D/StatusBarManagerService(  839): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
I/HotwordRecognitionRnr( 1554): Stopping hotword detection.
D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
D/Launcher( 1487): onTrimMemory. Level: 20
D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
V/GLSActivity( 1661): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/ConnectivityService(  839): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/accuweather( 2115): [KK AccuPhone]>>> WR:132 [0:0] onPause
D/accuweather( 2115): [KK AccuPhone]>>> SM:538 [0:0] onPause
D/SurfaceWidgetView( 1487): destroyHardwareResources():586969685
D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
D/ResourcesManager( 7565): creating new AssetManager and set to /data/app/com.test.thalitest-1/base.apk
D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
V/audio_hw_primary(  289): stop_input_stream: enter: usecase(7: audio-record)
V/audio_hw_primary(  289): disable_audio_route: enter: usecase(7)
V/audio_hw_primary(  289): disable_audio_route: reset mixer path: audio-record
D/audio_route(  289): ++++ audio_route_update_mixer ==============
D/audio_route(  289): Setting mixer control: MultiMedia1 Mixer SLIM_0_TX
D/audio_route(  289): Setting mixer control: value: 0
D/audio_route(  289): ------ audio_route_update_mixer ==============
V/audio_hw_primary(  289): disable_audio_route: exit
V/audio_hw_primary(  289): disable_snd_device: snd_device(122: vr-main-mic)
D/audio_route(  289): ++++ audio_route_update_mixer ==============
D/audio_route(  289): Setting mixer control: DEC2 Volume
D/audio_route(  289): Setting mixer control: value: 0
D/audio_route(  289): Setting mixer control: SLIM TX7 MUX, value: 0
D/audio_route(  289): Setting mixer control: AIF1_CAP Mixer SLIM TX7
D/audio_route(  289): Setting mixer control: value: 0
D/audio_route(  289): Setting mixer control: DEC2 MUX, value: 0
D/audio_route(  289): ------ audio_route_update_mixer ==============
V/audio_hw_primary(  289): stop_input_stream: exit: status(0)
V/audio_hw_primary(  289): in_standby: exit:  status(0)
V/AudioPolicyManager(  289): releaseInput() 30
V/AudioPolicyManager(  289): closeInput(30)
V/audio_hw_primary(  289): adev_close_input_stream
V/audio_hw_primary(  289): in_standby: enter
V/BitmapFactory( 1661): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
V/audio_hw_primary(  289): in_standby: exit:  status(0)
E/audio_hw_primary(  289): adev_close_input_stream, set jack_in to null
V/AudioPolicyManager(  289): releaseInput() exit
D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
D/SecContentProvider2(  839): uri = 14 selection = getSealedState
D/SecContentProvider2(  839): mCursor = null
D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
D/SecContentProvider2(  839): KnoxCustomManagerService offline: service is not available
D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
D/ApplicationPolicy(  839): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
V/ApplicationPolicy(  839): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
D/SurfaceWidgetView( 1487): destroyHardwareResources():586969685
D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
W/GLSActivity( 1661): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1661): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1661): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1661): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1661): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1661): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1661): 	at android.os.Binder.execTransact(Binder.java:446)
D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
D/StatusBar( 1172): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
E/BooksAccountManager( 7492): Authentication error
E/BooksAccountManager( 7492): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 7492): android.accounts.AccountManager.convertErrorToException(AccountManager.java:1893)
E/HttpHelper( 7492): null auth token
D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
I/qtaguid ( 7492): Tagging socket 34 with tag 10000000000{256,0} uid -1, pid: 7492, getuid(): 10082
I/PhoneStatusBar( 1172): Icon Only
D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
D/PanelView( 1172): There is/are notification(s) 
D/PanelView( 1172): There is/are notification(s) 
D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
,D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
I/qtaguid ( 7492): Untagging socket 34
W/ApiaryClient( 7492): Error response from books API: {
W/ApiaryClient( 7492):  "error": {
W/ApiaryClient( 7492):   "errors": [
W/ApiaryClient( 7492):    {
W/ApiaryClient( 7492):     "domain": "global",
W/ApiaryClient( 7492):     "reason": "required",
W/ApiaryClient( 7492):     "message": "Login Required",
W/ApiaryClient( 7492):     "locationType": "header",
W/ApiaryClient( 7492):     "location": "Authorization"
W/ApiaryClient( 7492):    }
W/ApiaryClient( 7492):   ],
W/ApiaryClient( 7492):   "code": 401,
W/ApiaryClient( 7492):   "message": "Login Required"
W/ApiaryClient( 7492):  }
W/ApiaryClient( 7492): }
W/ApiaryClient( 7492): errCount = 3: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 7492): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3DS0HXd4TFLU4&nonce=2368831443438806055&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 7492): Headers suppressed
D/ConnectivityService(  839): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
I/WebViewFactory( 7565): Loading com.google.android.webview version 37 (1726107-arm) (code 119201)
D/ResourcesManager( 7565): creating new AssetManager and set to /system/app/WebViewGoogle/WebViewGoogle.apk
D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
I/LibraryLoader( 7565): Loading: webviewchromium
I/LibraryLoader( 7565): Time to load native libraries: 2 ms (timestamps 5236-5238)
I/LibraryLoader( 7565): Expected native library version number "",actual native library version number ""
D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
V/WebViewChromiumFactoryProvider( 7565): Binding Chromium to main looper Looper (main, tid 1) {3ed69a03}
I/LibraryLoader( 7565): Expected native library version number "",actual native library version number ""
I/chromium( 7565): [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 7565): Initializing chromium process, renderers=0
W/art     ( 7565): Attempt to remove local handle scope entry from IRT, ignoring
W/chromium( 7565): [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
I/chromium( 7565): [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=35 off=46768 len=2953
I/chromium( 7565): [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:36 off:229524 len:643667
D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
I/Adreno-EGL( 7565): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 7565): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 7565): Build Date: 03/03/15 Tue
I/Adreno-EGL( 7565): Local Branch: LA.BF.1.1_RB1_20150108_025_1077123_1158499
I/Adreno-EGL( 7565): Remote Branch: 
I/Adreno-EGL( 7565): Local Patches: 
I/Adreno-EGL( 7565): Reconstruct Branch: 
D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
W/chromium( 7565): [WARNING:proxy_service.cc(901)] PAC support disabled because there is no system implementation
W/chromium( 7565): [WARNING:data_reduction_proxy_settings.cc(403)] SPDY proxy OFF at startup
W/art     ( 7565): Attempt to remove local handle scope entry from IRT, ignoring
W/AwContents( 7565): onDetachedFromWindow called when already detached. Ignoring
D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
D/SystemWebViewEngine( 7565): CordovaWebView is running on device made by: samsung
D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
W/art     ( 7565): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 7565): Attempt to remove local handle scope entry from IRT, ignoring
D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
D/Activity( 7565): performCreate Call secproduct feature valuefalse
D/Activity( 7565): performCreate Call debug elastic valuetrue
D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
D/OpenGLRenderer( 7565): Render dirty regions requested: true
D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
D/ActivityManager(  839): post active user change for 0
D/KnoxTimeoutHandler(  839): postActiveUserChange for user 0
D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/KnoxTimeoutHandler(  839): handleActiveUserChange for user 0
D/LockPatternUtilsCache( 1172): value : false
D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
I/SurfaceFlinger(  249): id=15 createSurf (1x1),1 flag=404, com.test.thalitest/com.test.thalitest.MainActivity
D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
I/OpenGLRenderer( 7565): Initialized EGL, version 1.4
D/LockPatternUtilsCache( 1172): value : false
I/OpenGLRenderer( 7565): HWUI protection enabled for context ,  &this =0xa1553060 ,&mEglDisplay = 1 , &mEglConfig = 8 
D/OpenGLRenderer( 7565): Enabling debug mode 0
D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
I/SurfaceFlinger(  249): id=8 Removed com.sec.android.app.launcher/com.android.launcher2.Launcher (4/9)
I/SurfaceFlinger(  249): id=8 Removed com.sec.android.app.launcher/com.android.launcher2.Launcher (-2/9)
D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
D/InputMethodManagerService(  839): windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
W/ContextImpl(  839): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.android.server.InputMethodManagerService$6.run:2728 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
W/ContextImpl(  839): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.android.server.InputMethodManagerService$6.run:2728 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
I/ActivityManager(  839): Displayed com.test.thalitest/.MainActivity: +636ms
D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
I/art     (  839): Explicit concurrent mark sweep GC freed 43612(2MB) AllocSpace objects, 11(371KB) LOS objects, 30% free, 36MB/52MB, paused 1.244ms total 105.747ms
D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
I/Timeline( 7565): Timeline: Activity_idle id: android.os.BinderProxy@5a2a462 time:95691
D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
D/JsMessageQueue( 7565): Set native->JS mode to OnlineEventsBridgeMode
D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
I/chromium( 7565): [INFO:SkUtilsArm.cpp(179)] Device supports ARM NEON instructions!
I/chromium( 7565): 
D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
I/SurfaceFlinger(  249): id=14 Removed Starting com.test.thalitest (7/8)
I/SurfaceFlinger(  249): id=14 Removed Starting com.test.thalitest (-2/8)
D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
D/CustomFrequencyManagerService(  839): acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1958400  uid : 1000  pid : 839  pkgName : ACTIVITY_RESUME_BOOSTER@10
D/CustomFrequencyManagerService(  839): releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1958400  uid : 1000  pid : 839  tag : ACTIVITY_RESUME_BOOSTER@6
D/CustomFrequencyManagerService(  839): FrequencyrequestList.getNextMaxCPUCoreRequest, index: 0
W/ActivityManager(  839): mDVFSHelper.release()
I/Timeline(  839): Timeline: Activity_windows_visible id: ActivityRecord{18935fce u0 com.test.thalitest/.MainActivity t11} time:95845
D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
E/Adreno-ES20( 7565): <check_framebuffer_attachment:854>: Invalid texture format! Returning error!
E/Adreno-ES20( 7565): <check_framebuffer_object_status:1237>: Framebuffer color attachment incomplete. Returning GL_FRAMEBUFFER_INCOMPLETE_ATTACHMENT!
D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
,D/jxcore_app_log( 7565): JniHelper::setJavaVM(0xb4e5c280), pthread_self() = -1259380864
,D/JX-Cordova( 7565): jxcore cordova android initializing
,D/CustomFrequencyManagerService(  839): releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1958400  uid : 1000  pid : 839  tag : ACTIVITY_RESUME_BOOSTER@10
,E/BooksSync( 7492): Soft error
E/BooksSync( 7492): com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
E/BooksSync( 7492): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3DS0HXd4TFLU4&nonce=2368831443438806055&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
E/BooksSync( 7492): Headers suppressed
E/BooksSync( 7492): 
E/BooksSync( 7492): com.google.android.apps.books.net.HttpHelper.wrapExceptionBasedOnStatus(HttpHelper.java:212)
E/BooksSync( 7492): Sync error
E/BooksSync( 7492): com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
E/BooksSync( 7492): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3DS0HXd4TFLU4&nonce=2368831443438806055&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
E/BooksSync( 7492): Headers suppressed
E/BooksSync( 7492): 
E/BooksSync( 7492): com.google.android.apps.books.net.HttpHelper.wrapExceptionBasedOnStatus(HttpHelper.java:212)
I/BooksSync( 7492): Finished books sync
,D/ConnectivityService(  839): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SyncManager(  839): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 66156, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,D/ConnectivityService(  839): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/ActivityManager(  839): Killing 6562:com.samsung.android.app.galaxyfinder/u0a34 (adj 15): bgCount ##41
,D/SecContentProvider2(  839): uri = 11 selection = getMyKnoxAdmin
,D/SecContentProvider2(  839): mCursor = null
,D/ConnectivityService(  839): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  839): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,W/libprocessgroup(  839): failed to open /acct/uid_10034/pid_6562/cgroup.procs: No such file or directory
,I/GLSUser ( 1661): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
I/GLSUser ( 1661): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1661): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1661): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1661): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/BitmapFactory( 1661): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  839): uri = 14 selection = getSealedState
,D/SecContentProvider2(  839): mCursor = null
D/SecContentProvider2(  839): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  839): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy(  839): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/StatusBar.NetworkController( 1172): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02012b/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020464/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
D/StatusBar.NetworkController( 1172): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1172): applyOpen
,D/StatusBar.NetworkController( 1172): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1172): applyOpen
D/StatusBar.NetworkController( 1172): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1172): applyOpen
D/StatusBar.NetworkController( 1172): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1172): applyOpen
,E/HttpOperation( 6664): [kfu{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
E/HttpOperation( 6664): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 6664): 	at kfv.a(PG:65)
E/HttpOperation( 6664): 	at kff.u(PG:385)
E/HttpOperation( 6664): 	at kfb.a(PG:29)
E/HttpOperation( 6664): 	at kff.l(PG:132)
E/HttpOperation( 6664): 	at dsf.a(PG:807)
E/HttpOperation( 6664): 	at fhk.a(PG:1126)
E/HttpOperation( 6664): 	at fhk.a(PG:908)
E/HttpOperation( 6664): 	at fhk.onPerformSync(PG:636)
E/HttpOperation( 6664): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/HttpOperation( 6664): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/HttpOperation( 6664): 	at ihi.a(PG:22)
E/HttpOperation( 6664): 	at kft.a(PG:91)
E/HttpOperation( 6664): 	at kfv.a(PG:62)
E/HttpOperation( 6664): 	... 8 more
E/HttpOperation( 6664): Caused by: gdi: User intervention required. Notification has been pushed.
E/HttpOperation( 6664): 	at gde.c(Unknown Source)
E/HttpOperation( 6664): 	at gde.b(Unknown Source)
E/HttpOperation( 6664): 	at ihi.a(PG:19)
E/HttpOperation( 6664): 	... 10 more
,D/StatusBar( 1172): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,I/PhoneStatusBar( 1172): Icon Only
D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
D/PanelView( 1172): There is/are notification(s) 
,D/PanelView( 1172): There is/are notification(s) 
,I/GLSUser ( 1661): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,I/GLSUser ( 1661): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1661): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1661): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1661): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/BitmapFactory( 1661): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  839): uri = 14 selection = getSealedState
,D/SecContentProvider2(  839): mCursor = null
D/SecContentProvider2(  839): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  839): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
V/ApplicationPolicy(  839): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
D/StatusBar( 1172): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
E/HttpOperation( 6664): [getmobileexperiments] Unexpected exception
E/HttpOperation( 6664): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 6664): 	at kfv.a(PG:65)
E/HttpOperation( 6664): 	at kff.u(PG:385)
E/HttpOperation( 6664): 	at kfb.a(PG:29)
E/HttpOperation( 6664): 	at kff.l(PG:132)
E/HttpOperation( 6664): 	at ieo.a(PG:43)
E/HttpOperation( 6664): 	at iep.a(PG:93)
E/HttpOperation( 6664): 	at fhn.a(PG:59)
E/HttpOperation( 6664): 	at lex.a(PG:85)
E/HttpOperation( 6664): 	at lex.b(PG:132)
E/HttpOperation( 6664): 	at fhk.a(PG:1146)
E/HttpOperation( 6664): 	at fhk.a(PG:908)
E/HttpOperation( 6664): 	at fhk.onPerformSync(PG:636)
E/HttpOperation( 6664): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/HttpOperation( 6664): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/HttpOperation( 6664): 	at ihi.a(PG:22)
E/HttpOperation( 6664): 	at kft.a(PG:91)
E/HttpOperation( 6664): 	at kfv.a(PG:62)
E/HttpOperation( 6664): 	... 12 more
E/HttpOperation( 6664): Caused by: gdi: User intervention required. Notification has been pushed.
E/HttpOperation( 6664): 	at gde.c(Unknown Source)
E/HttpOperation( 6664): 	at gde.b(Unknown Source)
E/HttpOperation( 6664): 	at ihi.a(PG:19)
E/HttpOperation( 6664): 	... 14 more
E/ExperimentLoader( 6664): [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 6664): java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 6664): 	at kfv.a(PG:65)
E/ExperimentLoader( 6664): 	at kff.u(PG:385)
E/ExperimentLoader( 6664): 	at kfb.a(PG:29)
E/ExperimentLoader( 6664): 	at kff.l(PG:132)
E/ExperimentLoader( 6664): 	at ieo.a(PG:43)
E/ExperimentLoader( 6664): 	at iep.a(PG:93)
E/ExperimentLoader( 6664): 	at fhn.a(PG:59)
E/ExperimentLoader( 6664): 	at lex.a(PG:85)
E/ExperimentLoader( 6664): 	at lex.b(PG:132)
E/ExperimentLoader( 6664): 	at fhk.a(PG:1146)
E/ExperimentLoader( 6664): 	at fhk.a(PG:908)
E/ExperimentLoader( 6664): 	at fhk.onPerformSync(PG:636)
E/ExperimentLoader( 6664): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/ExperimentLoader( 6664): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/ExperimentLoader( 6664): 	at ihi.a(PG:22)
E/ExperimentLoader( 6664): 	at kft.a(PG:91)
E/ExperimentLoader( 6664): 	at kfv.a(PG:62)
E/ExperimentLoader( 6664): 	... 12 more
E/ExperimentLoader( 6664): Caused by: gdi: User intervention required. Notification has been pushed.
E/ExperimentLoader( 6664): 	at gde.c(Unknown Source)
E/ExperimentLoader( 6664): 	at gde.b(Unknown Source)
E/ExperimentLoader( 6664): 	at ihi.a(PG:19)
E/ExperimentLoader( 6664): 	... 14 more
,I/PhoneStatusBar( 1172): Icon Only
D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
D/PanelView( 1172): There is/are notification(s) 
D/PanelView( 1172): There is/are notification(s) 
,I/art     ( 1661): Explicit concurrent mark sweep GC freed 31061(2001KB) AllocSpace objects, 22(1782KB) LOS objects, 40% free, 17MB/29MB, paused 470us total 21.916ms
,I/GLSUser ( 1661): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,I/GLSUser ( 1661): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1661): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1661): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1661): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ResourcesManager( 1661): creating new AssetManager and set to /system/app/PlusOne/PlusOne.apk
,V/BitmapFactory( 1661): DecodeImagePath(decodeResourceStream3) : res/mipmap-xxhdpi-v4/quantum_logo_google_plus_color_44in48.png
,V/BitmapFactory( 1661): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  839): uri = 14 selection = getSealedState
,D/SecContentProvider2(  839): mCursor = null
D/SecContentProvider2(  839): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  839): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
V/ApplicationPolicy(  839): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,E/HttpOperation( 6664): [getaccountstatus] Unexpected exception
E/HttpOperation( 6664): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 6664): 	at kfv.a(PG:65)
E/HttpOperation( 6664): 	at kff.u(PG:385)
E/HttpOperation( 6664): 	at kfb.a(PG:29)
E/HttpOperation( 6664): 	at ixd.a(PG:248)
E/HttpOperation( 6664): 	at ixd.b(PG:206)
E/HttpOperation( 6664): 	at ixd.a(PG:175)
E/HttpOperation( 6664): 	at fig.a(PG:78)
E/HttpOperation( 6664): 	at lex.a(PG:85)
E/HttpOperation( 6664): 	at lex.b(PG:132)
E/HttpOperation( 6664): 	at fhk.a(PG:1146)
E/HttpOperation( 6664): 	at fhk.a(PG:908)
E/HttpOperation( 6664): 	at fhk.onPerformSync(PG:636)
E/HttpOperation( 6664): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/HttpOperation( 6664): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/HttpOperation( 6664): 	at ihi.a(PG:22)
E/HttpOperation( 6664): 	at kft.a(PG:91)
E/HttpOperation( 6664): 	at kfv.a(PG:62)
E/HttpOperation( 6664): 	... 12 more
E/HttpOperation( 6664): Caused by: gdi: User intervention required. Notification has been pushed.
E/HttpOperation( 6664): 	at gde.c(Unknown Source)
E/HttpOperation( 6664): 	at gde.b(Unknown Source)
E/HttpOperation( 6664): 	at ihi.a(PG:19)
E/HttpOperation( 6664): 	... 14 more
,E/EsSyncAdapterService( 6664): Sync failure
E/EsSyncAdapterService( 6664): java.io.IOException: Rpc failed
E/EsSyncAdapterService( 6664): 	at ixd.a(PG:348)
E/EsSyncAdapterService( 6664): 	at ixd.a(PG:248)
E/EsSyncAdapterService( 6664): 	at ixd.b(PG:206)
E/EsSyncAdapterService( 6664): 	at ixd.a(PG:175)
E/EsSyncAdapterService( 6664): 	at fig.a(PG:78)
E/EsSyncAdapterService( 6664): 	at lex.a(PG:85)
E/EsSyncAdapterService( 6664): 	at lex.b(PG:132)
E/EsSyncAdapterService( 6664): 	at fhk.a(PG:1146)
E/EsSyncAdapterService( 6664): 	at fhk.a(PG:908)
E/EsSyncAdapterService( 6664): 	at fhk.onPerformSync(PG:636)
E/EsSyncAdapterService( 6664): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/EsSyncAdapterService( 6664): Caused by: java.io.IOException: Cannot obtain authentication token
E/EsSyncAdapterService( 6664): 	at kfv.a(PG:65)
E/EsSyncAdapterService( 6664): 	at kff.u(PG:385)
E/EsSyncAdapterService( 6664): 	at kfb.a(PG:29)
E/EsSyncAdapterService( 6664): 	... 10 more
E/EsSyncAdapterService( 6664): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/EsSyncAdapterService( 6664): 	at ihi.a(PG:22)
E/EsSyncAdapterService( 6664): 	at kft.a(PG:91)
E/EsSyncAdapterService( 6664): 	at kfv.a(PG:62)
E/EsSyncAdapterService( 6664): 	... 12 more
E/EsSyncAdapterService( 6664): Caused by: gdi: User intervention required. Notification has been pushed.
E/EsSyncAdapterService( 6664): 	at gde.c(Unknown Source)
E/EsSyncAdapterService( 6664): 	at gde.b(Unknown Source)
E/EsSyncAdapterService( 6664): 	at ihi.a(PG:19)
E/EsSyncAdapterService( 6664): 	... 14 more
D/StatusBar( 1172): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,I/PhoneStatusBar( 1172): Icon Only
,D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
D/PanelView( 1172): There is/are notification(s) 
D/PanelView( 1172): There is/are notification(s) 
,D/ConnectivityService(  839): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SyncManager(  839): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, SERVER, currentRunTime 92652, reason: 10135, SyncResult: stats [ numIoExceptions: 2]
,D/ConnectivityService(  839): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  839): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SecContentProvider2(  839): uri = 11 selection = getMyKnoxAdmin
,D/SecContentProvider2(  839): mCursor = null
,I/GAV2    ( 7492): Thread[GAThread,5,main]: No campaign data found.
,E/SQLiteLog( 1661): (10) POSIX Error : 11 SQLite Error : 3850
,E/SMD     (  280): DCD ON
,D/StatusBar.NetworkController( 1172): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02012b/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020468/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
,D/StatusBar.NetworkController( 1172): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1172): applyOpen
,D/StatusBar.NetworkController( 1172): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1172): applyOpen
D/StatusBar.NetworkController( 1172): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1172): applyOpen
D/StatusBar.NetworkController( 1172): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1172): applyOpen
,I/WifiStateMachine(  839): CMD_RSSI_POLL : calculateWifiScore in!
,I/WifiStateMachine(  839): CMD_RSSI_POLL : calculateWifiScore out!
,I/WifiStateMachine(  839): CMD_RSSI_POLL : out!
,W/jxcore-log( 7565): Initializing JXcore engine
,W/jxcore-log( 7565): JXcore engine is ready
,W/jxcore-log( 7565): Starting JXcore engine
,E/auditd  ( 1950): In denial and Property audit_ondenial is set to 1 
,D/SecurityLogAgent:SEDenialService(  839): Got Modify Event and sending Denial Intent foraudit.log
,W/ContextImpl(  839): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.android.server.SEDenialService$AuditFileObserver.onEvent:76 android.os.FileObserver$ObserverThread.onEvent:122 android.os.FileObserver$ObserverThread.observe:-2 android.os.FileObserver$ObserverThread.run:85 
,D/SecurityLogAgent:SEDenialService(  839): audit.ondenial set to 0 after sending samsung.intent.action.knox.DENIAL_NOTIFICATION intent
,E/ActivityManager(  839): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  839): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  839): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  839): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 7631): MountEmulatedStorage()
E/Zygote  ( 7631): v2
I/libpersona( 7631): KNOX_SDCARD checking this for 1000
I/libpersona( 7631): KNOX_SDCARD not a persona
,I/SELinux ( 7631): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
I/SELinux ( 7631): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
E/SELinux ( 7631): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager(  839): Start proc com.samsung.android.securitylogagent for broadcast com.samsung.android.securitylogagent/.receivers.SeDenialReceiver: pid=7631 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,D/TimaKeyStoreProvider( 7631): TimaSignature is unavailable
,D/ActivityThread( 7631): Added TimaKeyStore provider
,W/jxcore-log( 7565): Platform android
W/jxcore-log( 7565): 
W/jxcore-log( 7565): Process ARCH arm
W/jxcore-log( 7565): 
,D/ResourcesManager( 7631): creating new AssetManager and set to /system/app/SecurityLogAgent/SecurityLogAgent.apk
,D/SecurityLogAgent( 7631):  SeDenialReceiver : Intent Received : samsung.intent.action.knox.DENIAL_NOTIFICATION
,D/SecurityLogAgent( 7631):  SeDenialReceiver : File path = null
,I/ActivityManager(  839): Killing 4622:com.sec.android.app.shealth/u0a35 (adj 15): bgCount ##41
,W/libprocessgroup(  839): failed to open /acct/uid_10035/pid_4622/cgroup.procs: No such file or directory
,I/jxcore-log( 7565): JXcore Cordova bridge is ready!
I/jxcore-log( 7565): 
W/jxcore-log( 7565): JXcore engine is started
,D/StatusBar.NetworkController( 1172): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02012b/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020464/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
,D/StatusBar.NetworkController( 1172): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1172): applyOpen
,D/StatusBar.NetworkController( 1172): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1172): applyOpen
,D/StatusBar.NetworkController( 1172): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1172): applyOpen
D/StatusBar.NetworkController( 1172): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1172): applyOpen
,D/PowerManagerService(  839): [api] release WakeLock flags=0x10000006 tag=PowerUI.Notification uid=10059 pid=1172 (0x0)
,I/jxcore-log( 7565): Toggling radios to true
I/jxcore-log( 7565): 
,D/BluetoothAdapter( 7565): enable()
,D/BluetoothAdapter( 7565): enable(): BT is already enabled..!
,D/WifiService(  839): New client listening to asynchronous messages
,I/WifiManager( 7565): packageName : com.test.thalitest
,D/SecContentProvider(  839): uri = 18 selection = isWifiEnabled
,D/SecContentProvider2(  839): uri = 20 selection = isWifiStateChangeAllowed
D/SecContentProvider2(  839): mCursor = null
,D/WifiService(  839): setWifiEnabled: true pid=7565, uid=10367
E/WifiService(  839): Invoking mWifiStateMachine.setWifiEnabled
,W/ActivityManager(  839): Permission Denial: getCurrentUser() from pid=7565, uid=10367 requires android.permission.INTERACT_ACROSS_USERS
,W/WifiService(  839): Failed getting userId using ActivityManagerNative
W/WifiService(  839): java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=7565, uid=10367 requires android.permission.INTERACT_ACROSS_USERS
W/WifiService(  839): 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:22619)
W/WifiService(  839): 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2119)
W/WifiService(  839): 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2107)
W/WifiService(  839): 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:223)
W/WifiService(  839): 	at android.os.Binder.execTransact(Binder.java:446)
,D/SettingsProvider(  839): name = wifi_on
,I/WifiService(  839): disconnect: pid=7565, uid=10367
,I/jxcore-log( 7565): Radios toggled
I/jxcore-log( 7565): 
,I/wpa_supplicant( 1273): [wpa_supplicant_ctrl_iface_process] : DISCONNECT
,I/jxcore-log( 7565): Got Device Bluetooth address: B0:C5:59:3F:75:69
I/jxcore-log( 7565): 
,I/jxcore-log( 7565): Perf Test app loaded loaded
I/jxcore-log( 7565): 
,I/chromium( 7565): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,I/jxcore-log( 7565): check test folder
I/jxcore-log( 7565): 
,I/jxcore-log( 7565): found test : ./testFindPeers.js
I/jxcore-log( 7565): 
,I/wpa_supplicant( 1273): CTRL-EVENT-DISCONNECTED bssid=C0.AA.48 reason=3 locally_generated=1
,I/wpa_supplicant( 1273): wlan0: State: COMPLETED -> DISCONNECTED
,I/wpa_supplicant( 1273): CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=C0.AA.48 SSID=4E47373030
I/wpa_supplicant( 1273): wlan0: State: DISCONNECTED -> DISCONNECTED
,E/WifiStateMachine(  839): WifiStateMachine: Leaving Connected state
,I/wpa_supplicant( 1273): reset timer : RESET_TIMER 0
I/wpa_supplicant( 1273): wlan0: Setting scan request: 0 sec 0 usec
I/wpa_supplicant( 1273): Disconnected - do not scan
I/wpa_supplicant( 1273): wlan0: State: DISCONNECTED -> DISCONNECTED
,E/WifiStateMachine(  839): handleNetworkDisconnect: Stopping DHCP and clearing IP stack:handleNetworkDisconnect - access$11200 - exit - invokeExitMethods
E/WifiStateMachine(  839): handleNetworkDisconnect c0:ff:d4:d3:aa:48 config "NG700"WPA_PSK config.bssid any
,E/WifiStateMachine(  839): handleNetworkDisconnect "NG700" nid=0
E/WifiConfigStore(  839): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,E/WifiStateMachine(  839): setSuspendOptimizationsNative: 1 true -want true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - stopDhcp - handleNetworkDisconnect
,D/WifiP2pService(  839): InactiveState{ what=143375 }
,D/WifiP2pService(  839): P2pEnabledState{ what=143375 }
,D/StatusBar.NetworkController( 1172): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02012b/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020464/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
,V/AlarmManager(  839): waitForAlarm result :4
,I/jxcore-log( 7565): found test : ./testSendData.js
I/jxcore-log( 7565): 
,D/CommandListener(  275): Clearing all IP addresses on wlan0
,V/NativeCrypto( 1661): Read error: ssl=0xad442600: I/O error during system call, Connection timed out
,E/WifiStateMachine(  839): setDetailed state, old =CONNECTED and new state=DISCONNECTED hidden=false
,E/ConnectivityService(  839): updateNetworkInfo()
,D/ConnectivityService(  839): NetworkAgentInfo [WIFI () - 502] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
,D/ConnectivityService(  839): NetworkAgentInfo [WIFI () - 502] got DISCONNECTED, was satisfying 2
,E/WifiConfigStore(  839): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,E/WifiStateMachine(  839): Start Disconnecting Watchdog 1
,I/wpa_supplicant( 1273): wlan0: Setting scan request: 0 sec 0 usec
I/wpa_supplicant( 1273): P2P: Current p2p state = IDLE
I/wpa_supplicant( 1273): wlan0: State: DISCONNECTED -> SCANNING
I/wpa_supplicant( 1273): CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00.00.00 SSID=
I/wpa_supplicant( 1273): First Scan Start
,I/wpa_supplicant( 1273): Scan requested (ret=0) - scan timeout 30 seconds
,E/WifiStateMachine(  839): ConnectModeState: Network connection lost 
,E/WifiStateMachine(  839): handleNetworkDisconnect: Stopping DHCP and clearing IP stack:handleNetworkDisconnect - access$11200 - processMessage - processMsg
,E/WifiStateMachine(  839): setSuspendOptimizationsNative: 1 true -want true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - stopDhcp - handleNetworkDisconnect
,D/WifiP2pService(  839): InactiveState{ what=143375 }
,D/WifiP2pService(  839): P2pEnabledState{ what=143375 }
,I/WifiTrafficPoller(  839): evaluateTrafficStatsPolling
,I/CLocInfoService(  839): External Intent Received android.net.wifi.STATE_CHANGE
,D/StatusBar.NetworkController( 1172): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020498/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020133/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020464/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
,D/StatusBar.NetworkController( 1172): refreshSignalCluster - setNWBoosterIndicators(false)
,V/NativeCrypto( 1661): SSL shutdown failed: ssl=0xad442600: I/O error during system call, Broken pipe
,D/StatusBar.NetworkController( 1172): applyOpen
,D/StatusBar.NetworkController( 1172): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1172): applyOpen
D/StatusBar.NetworkController( 1172): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1172): applyOpen
,D/StatusBar.NetworkController( 1172): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1172): applyOpen
,D/ConnectivityService(  839): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  839): reportBadNetwork(NetworkAgentInfo [WIFI () - 502]) by 10012
,D/StatusBar.NetworkController( 1172): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020498/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020133/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020464/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  839): ValidatedState{ when=-3ms what=532488 arg1=10012 target=com.android.internal.util.StateMachine$SmHandler }
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  839): DefaultState{ when=-4ms what=532488 arg1=10012 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  839): Forcing reevaluation
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  839): EvaluatingState{ when=-1ms what=532486 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  839): Validated
,I/Hs20UtilService( 1306): Starting #6
,D/ConnectivityService(  839): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/ConnectivityService(  839): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/Hs20UtilService( 1306): Message received 5007
,D/NearbySettings( 1306): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,V/NearbySettings( 1306): DMSUtil.isNetworkConnected - flag-null, state-null
,D/ConnectivityService(  839): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/NearbySettings( 1306): DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,D/ConnectivityService(  839): returning getNetworkInfo(networkType - 13) :[type: WIFI_P2P[] - WIFI_P2P, state: UNKNOWN/IDLE, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/NearbySettings( 1306): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 1306): DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
,I/NearbySettings( 1306): MountReceiver.onReceive - Set preference state off
,V/NearbySettings( 1306): MountReceiver.mPrefHandler - 7002
,D/CommandListener(  275): Clearing all IP addresses on wlan0
,E/WifiStateMachine(  839): setDetailed state, old =DISCONNECTED and new state=DISCONNECTED hidden=false
,D/WifiStateMachine(  839): updateConfiguredNetworkExpiration - currTime: 1449752906166
D/WifiStateMachine(  839): updateConfiguredNetworkExpiration - AP, "NG700", is not shared AP.
,E/WifiStateMachine(  839): SUPPLICANT_STATE_CHANGE_EVENT state=DISCONNECTED -> state= DISCONNECTED debouncing=false
E/WifiStateMachine(  839): setDetailed state, old =DISCONNECTED and new state=DISCONNECTED hidden=false
,I/WifiTrafficPoller(  839): evaluateTrafficStatsPolling
,E/WifiStateMachine(  839): Link configuration changed for netId: -1 old: {LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0} new: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0}
E/WifiStateMachine(  839): updateLinkProperties nid: -1 state: DISCONNECTED reason: CMD_UPDATE_LINKPROPERTIES
,E/WifiStateMachine(  839): Link configuration changed for netId: -1 old: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576} new: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0}
E/WifiStateMachine(  839): updateLinkProperties nid: -1 state: DISCONNECTED reason: CMD_UPDATE_LINKPROPERTIES
D/WifiNetworkAgent(  839): NetworkAgent: NetworkAgent channel lost
,E/WifiStateMachine(  839): SUPPLICANT_STATE_CHANGE_EVENT state=SCANNING -> state= SCANNING debouncing=false
E/WifiStateMachine(  839): setDetailed state, old =DISCONNECTED and new state=SCANNING hidden=false
E/WifiStateMachine(  839): setDetailed state send new extra info"NG700"
I/CLocInfoService(  839): External Intent Received android.net.wifi.STATE_CHANGE
,D/ConnectivityService(  839): notifyType LOST for NetworkAgentInfo [WIFI () - 502]
D/ConnectivityService(  839): calling update connectivity
D/ConnectivityService(  839):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/EntConnectivity(  839): Not allowed due to - mEnabled false
D/ConnectivityService(  839):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
,D/ConnectivityService(  839): sending notification LOST for NetworkRequest [ id=2, legacyType=-1, [] ]
,D/SecContentProvider2(  839): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2(  839): mCursor = null
,D/ConnectivityManager.CallbackHandler( 1172): CM callback handler got msg 524292
,D/Nat464Xlat(  839): requiresClat: netType=1, connected=false, hasIPv4Address=true
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  839): ValidatedState{ when=0 what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  839): DefaultState{ when=0 what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  839): Disconnected - quitting
,D/ConnectivityService(  839): Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  839): sending new Min Network Score(0): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,D/TelephonyNetworkFactory( 1466): Cellular needs Network for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,D/CSLegacyTypeTracker(  839): Removing agent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{502}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.135/24,fe80::ee1f:72ff:fe18:8b78/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{true} created{true} explicitlySelected{false} }
,D/CSLegacyTypeTracker(  839): Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 502] isDefaultNetwork=false
,D/StatusBar.NetworkController( 1172): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020498/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020133/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020464/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
,D/ConnectivityService(  839): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,D/SSRM:m  (  839): SIOP:: AP = 400, PST = 439, CUR = 300
,D/ConnectivityService(  839): sendStickyBroadcastDelayed: delayMs=500, action=android.net.conn.CONNECTIVITY_CHANGE
,D/SmartBondingService(  839): SmartBondingReceiver: onReceive action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/SmartBondingService(  839): EVENT_UPDATE_SB_STATE called / mDisableBySIOP false
D/SecContentProvider2(  839): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2(  839): mCursor = null
,D/SmartBondingService(  839): getSBEnabled() enabled =false
D/SmartBondingService(  839): getSBEnabled() enabled =false
D/SmartBondingService(  839): getSBEnabled() enabled =false
,D/ConnectivityService(  839): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
V/NetworkStats(  839): updateIfacesLocked()
D/NtpTrustedTime(  839): currentTimeMillis() cache hit
V/NetworkStats(  839): performPollLocked(flags=0x1)
D/StatusBar.NetworkController( 1172): getUpdateDataNetType(): 0
D/StatusBar.NetworkController( 1172): updateDataNetType()
D/StatusBar.NetworkController( 1172): NoService, mRoamingIconId = 0
,D/SmartBondingService(  839): getNetworkEnabled : wifi : true mobile : true
,D/StatusBar.NetworkController( 1172): updateDataIcon, mDataDirectionIconId = (null) mDataConnected = false
D/StatusBar.NetworkController( 1172): updateTelephonySignalStrength: hasService=false ss=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte
,I/Hs20UtilService( 1306): Starting #7
D/StatusBar.NetworkController( 1172): updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal
I/Hs20UtilService( 1306): Message received 5007
D/StatusBar.NetworkController( 1172): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020498/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020133/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020464/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
D/StatusBar.NetworkController( 1172): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1172): applyOpen
,D/StatusBar.NetworkController( 1172): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1172): applyOpen
D/StatusBar.NetworkController( 1172): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1172): applyOpen
D/StatusBar.NetworkController( 1172): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1172): applyOpen
,D/NtpTrustedTime(  839): currentTimeMillis() cache hit
D/NtpTrustedTime(  839): currentTimeMillis() cache hit
,E/ConnectivityService(  839): EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
,E/ConnectivityService(  839): EVENT_NETWORK_VALIDATED - isLiveNetworkAgent found mismatched netId: null - NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{502}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.135/24,fe80::ee1f:72ff:fe18:8b78/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{true} created{true} explicitlySelected{false} }
D/NtpTrustedTime(  839): currentTimeMillis() cache hit
V/NetworkStats(  839): advisePersistThreshold() given 9223372036854775, clamped to 2097152
D/NtpTrustedTime(  839): currentTimeMillis() cache hit
,D/NearbySettings( 1306): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,V/NearbySettings( 1306): DMSUtil.isNetworkConnected - flag-null, state-null
D/ConnectivityService(  839): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/NetworkStatsFactory(  839): UpdateStatsForKnox
,D/ConnectivityService(  839): returning getNetworkInfo(networkType - 28) :[type: MOBILE_ENT1[] - MOBILE_ENT1, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,V/NetworkStats(  839): performPollLocked() took 21ms
,D/NtpTrustedTime(  839): currentTimeMillis() cache hit
,I/NearbySettings( 1306): DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,D/ConnectivityService(  839): returning getNetworkInfo(networkType - 13) :[type: WIFI_P2P[] - WIFI_P2P, state: UNKNOWN/IDLE, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/NearbySettings( 1306): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 1306): DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
I/NearbySettings( 1306): MountReceiver.onReceive - Set preference state off
V/NearbySettings( 1306): MountReceiver.mPrefHandler - 7002
,D/NtpTrustedTime(  839): currentTimeMillis() cache hit
,D/NtpTrustedTime(  839): currentTimeMillis() cache hit
,I/Choreographer( 7565): Skipped 74 frames!  The application may be doing too much work on its main thread.
,I/chromium( 7565): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
,D/FileWriteThread_Telephony( 1466): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 1466): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 1466): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 1466): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 1466): FileWriteThread : threadType = 3
D/FileWriteThread_Telephony( 1466): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 1466): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 1466): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 1466): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 1466): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 1466): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 1466): FileWriteThread : threadType = 3
D/FileWriteThread_Telephony( 1466): FileWriteThread : threadType = 3
D/FileWriteThread_Telephony( 1466): FileWriteThread : threadType = 3
,V/GLSActivity( 1661): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1661): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
I/GLSUser ( 1661): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1661): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1661): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1661): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/Finsky  ( 6694): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,D/Finsky  ( 6694): [1] 5.onFinished: Installation state replication failed.
D/Finsky  ( 6694): [1] 5.onFinished: Scheduling replication attempt 2.
,D/ConnectivityService(  839): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,I/ApplicationPolicy(  839): updateDataUsageMap
,D/ConnectivityService(  839): returning getNetworkInfo(networkType - 0) :[type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  839): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/ActivityManager(  839): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  839): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  839): checkUser: useridlist=null, currentuser=0
I/SystemBroadcastReceiver( 7177): [#DCM#] [DCM_Performance] onReceive completed in time  1242 microsec. 
E/ActivityManager(  839): checkUser: useridlist=null, currentuser=0
,D/SmartBondingService(  839): SmartBondingReceiver: onReceive action=android.net.conn.CONNECTIVITY_CHANGE
D/ConnectivityService(  839): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/SmartBondingService(  839): EVENT_UPDATE_SB_STATE called / mDisableBySIOP false
,D/SmartBondingService(  839): getSBEnabled() enabled =false
D/SmartBondingService(  839): getSBEnabled() enabled =false
D/SmartBondingService(  839): getSBEnabled() enabled =false
,D/SmartBondingService(  839): getNetworkEnabled : wifi : true mobile : true
I/CLocInfoService(  839): External Intent Received android.net.conn.CONNECTIVITY_CHANGE
D/ConnectivityService(  839): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/CLocInfoService(  839): CLoinfo wifi false
,D/Tethering(  839): MasterInitialState.processMessage what=3
,D/ConnectivityService(  839): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,W/SLocation(  839): No Active Data Connection
,D/ConnectivityService(  839): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  839): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  839): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/NetworkMonitor( 5382): type=WIFI subType= reason=null isConnected=false
,E/Zygote  ( 7692): MountEmulatedStorage()
,E/Zygote  ( 7692): v2
I/libpersona( 7692): KNOX_SDCARD checking this for 1000
I/libpersona( 7692): KNOX_SDCARD not a persona
,I/ActivityManager(  839): Start proc com.sec.pcw.device for broadcast com.sec.pcw.device/.receiver.SYSTEMReceiver: pid=7692 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,I/SystemBroadcastReceiver( 7177): [#DCM#] Calling notifyListeners. 
,I/DBG_DM  ( 3790): [com.wssyncmldm.XDMService(1111/IlIlllIIlIlIIIlIlIll)] WiFi network Connected : false
,I/DCMController( 7177): [#DCM#] onIntentReceived eventid = EVENT_NETWORK_CHANGED
I/DCMController( 7177): [#DCM#] setIsConnectedForExtractors 
,I/SELinux ( 7692): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,D/ConnectivityService(  839): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  839): returning getNetworkInfo(networkType - 7) :[type: BLUETOOTH[] - BLUETOOTH, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/SELinux ( 7692): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 7692): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/DBG_DM  ( 3790): [com.wssyncmldm.XDMService(1125/lllllIlIlIIIIIIIIlIl)] Bluetooth Data Connected : false
,D/accuweather( 2115): [KK AccuPhone]>>> SWW:66 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,D/TimaKeyStoreProvider( 7692): TimaSignature is unavailable
,D/ActivityThread( 7692): Added TimaKeyStore provider
,D/ResourcesManager( 7692): creating new AssetManager and set to /system/priv-app/PCWClientS18/PCWClientS18.apk
,I/PCWCLIENTTRACE_LOG( 7692): DEFAULT_LOGON : true
,I/PCWCLIENTTRACE_LOG( 7692): DEFAULT_LOGLEVEL : 3
,I/PCWCLIENTTRACE_DMDBOpenHelper( 7692): new DMDBOpenHelper instance
,I/PCWCLIENTTRACE_PushUtil( 7692): SPPPushClient is installed : true
I/PCWCLIENTTRACE_PushUtil( 7692): sales region : global
I/PCWCLIENTTRACE_PushUtil( 7692): getPushTypeList : [SPP, GCM]
I/PCWCLIENTTRACE_SYSTEMReceiver( 7692): [onReceive] - android.net.conn.CONNECTIVITY_CHANGE
,I/PCWCLIENTTRACE_SYSTEMReceiver( 7692): noConnectivity : true
,E/ActivityManager(  839): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  839): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  839): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  839): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 7716): MountEmulatedStorage()
E/Zygote  ( 7716): v2
I/libpersona( 7716): KNOX_SDCARD checking this for 10002
I/libpersona( 7716): KNOX_SDCARD not a persona
,I/ActivityManager(  839): Start proc com.sec.android.cloudagent for broadcast com.sec.android.cloudagent/.detector.DetectorReceiver: pid=7716 uid=10002 gids={50002, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  839): Killing 6830:com.policydm/1000 (adj 15): bgCount ##41
,I/SELinux ( 7716): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 7716): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 7716): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 7716): TimaSignature is unavailable
,D/ActivityThread( 7716): Added TimaKeyStore provider
,W/libprocessgroup(  839): failed to open /acct/uid_1000/pid_6830/cgroup.procs: No such file or directory
,D/ResourcesManager( 7716): creating new AssetManager and set to /system/priv-app/CloudAgent/CloudAgent.apk
,I/ActivityManager(  839): Killing 5141:com.sec.spp.push/u0a38 (adj 15): bgCount ##41
,E/ActivityManager(  839): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  839): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  839): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  839): checkUser: useridlist=null, currentuser=0
,E/SMD     (  280): DCD ON
,E/Zygote  ( 7736): MountEmulatedStorage()
E/Zygote  ( 7736): v2
I/libpersona( 7736): KNOX_SDCARD checking this for 1000
I/libpersona( 7736): KNOX_SDCARD not a persona
,I/ActivityManager(  839): Start proc com.sec.android.diagmonagent for broadcast com.sec.android.diagmonagent/.DiagMonRegistrationReceiver: pid=7736 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,I/art     (  326): Explicit concurrent mark sweep GC freed 8744(372KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 14MB/23MB, paused 275us total 12.162ms
,I/SELinux ( 7736): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 7736): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 7736): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/art     (  326): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 14MB/23MB, paused 247us total 10.085ms
,I/art     (  326): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 14MB/23MB, paused 246us total 7.880ms
,D/TimaKeyStoreProvider( 7736): TimaSignature is unavailable
,D/ActivityThread( 7736): Added TimaKeyStore provider
,W/libprocessgroup(  839): failed to open /acct/uid_10038/pid_5141/cgroup.procs: No such file or directory
,D/ResourcesManager( 7736): creating new AssetManager and set to /system/priv-app/DiagMonAgent/DiagMonAgent.apk
,I/DIAGMON_AGENT( 7736): [com.sec.android.diagmonagent.DiagMonAgentApplication(41/onCreate)] myUserId : 0
,I/DIAGMON_AGENT( 7736): [com.diagmondm.db.file.XDB(374/llIlIIIIlIIIIIlIlIII)] 
,I/DIAGMON_AGENT( 7736): [com.sec.android.diagmonagent.DiagMonAgentApplication(61/onCreate)] nStatus : 0
,I/DIAGMON_AGENT( 7736): [com.sec.android.diagmonagent.DiagMonAgentApplication(78/onCreate)] DiagMon DM Application Start !
,I/DIAGMON_AGENT( 7736): [lIIllllllllIlIlIllll(17/llIIIIlllllIIllIIllI)] Receive broadcast: android.net.conn.CONNECTIVITY_CHANGE
,I/DIAGMON_AGENT( 7736): [lIIllllllllIlIlIllll(31/llIIIIlllllIIllIIllI)] Running with RegistrationReceiver
,I/wpa_supplicant( 1273): nl80211: Received scan results (6 BSSes)
I/wpa_supplicant( 1273): wlan0: Setting scan request: 8 sec 0 usec
I/wpa_supplicant( 1273): Trying to associate with C0.AA.48 (SSID='4E47373030' freq=2412 MHz)
I/wpa_supplicant( 1273): wlan0: State: SCANNING -> ASSOCIATING
,I/wpa_supplicant( 1273): CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00.00.00 SSID=
,E/WifiStateMachine(  839): [1,449,752,907,194 ms] noteScanEnd no scan source
,E/WifiStateMachine(  839): wifi setScanResults statecom.android.server.wifi.WifiStateMachine$DisconnectedState@30f3db2f sup_state=SCANNING debouncing=false
,E/WifiStateMachine(  839): SUPPLICANT_STATE_CHANGE_EVENT state=ASSOCIATING -> state= CONNECTING debouncing=false
E/WifiStateMachine(  839): setDetailed state, old =SCANNING and new state=CONNECTING hidden=false
E/WifiStateMachine(  839): setDetailed state send new extra info0x
,I/CLocInfoService(  839): External Intent Received android.net.wifi.SCAN_RESULTS
,D/SecContentProvider2(  839): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2(  839): mCursor = null
,E/ActivityManager(  839): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  839): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  839): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  839): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 7755): MountEmulatedStorage()
E/Zygote  ( 7755): v2
I/libpersona( 7755): KNOX_SDCARD checking this for 10011
I/libpersona( 7755): KNOX_SDCARD not a persona
,I/ActivityManager(  839): Start proc com.sec.android.fotaclient for content provider com.sec.android.fotaclient/.log.MasterLogProvider: pid=7755 uid=10011 gids={50011, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/SELinux ( 7755): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 7755): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 7755): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 7755): TimaSignature is unavailable
,D/ActivityThread( 7755): Added TimaKeyStore provider
,D/ResourcesManager( 7755): creating new AssetManager and set to /system/priv-app/FotaClient/FotaClient.apk
,I/wpa_supplicant( 1273): wlan0: State: ASSOCIATING -> ASSOCIATED
I/wpa_supplicant( 1273): CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00.00.00 SSID=4E47373030
,I/wpa_supplicant( 1273): Associated with C0.AA.48
,E/WifiStateMachine(  839): SUPPLICANT_STATE_CHANGE_EVENT state=ASSOCIATED -> state= CONNECTING debouncing=false
E/WifiStateMachine(  839): setDetailed state, old =CONNECTING and new state=CONNECTING hidden=false
,D/SecContentProvider2(  839): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2(  839): mCursor = null
,I/wpa_supplicant( 1273): wlan0: State: ASSOCIATED -> 4WAY_HANDSHAKE
I/wpa_supplicant( 1273): CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=C0.AA.48 SSID=4E47373030
,E/WifiStateMachine(  839): SUPPLICANT_STATE_CHANGE_EVENT state=FOUR_WAY_HANDSHAKE -> state= AUTHENTICATING debouncing=false
E/WifiStateMachine(  839): setDetailed state, old =CONNECTING and new state=AUTHENTICATING hidden=false
E/WifiStateMachine(  839): setDetailed state send new extra info"NG700"
,D/SecContentProvider2(  839): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2(  839): mCursor = null
,I/ActivityManager(  839): Killing 6073:com.samsung.android.sdk.samsunglink/u0a42 (adj 15): bgCount ##41
,I/wpa_supplicant( 1273): wlan0: State: 4WAY_HANDSHAKE -> 4WAY_HANDSHAKE
,I/wpa_supplicant( 1273): wlan0: State: 4WAY_HANDSHAKE -> GROUP_HANDSHAKE
I/wpa_supplicant( 1273): CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=C0.AA.48 SSID=4E47373030
,I/wpa_supplicant( 1273): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
I/wpa_supplicant( 1273): wlan0: State: GROUP_HANDSHAKE -> COMPLETED
I/wpa_supplicant( 1273): CTRL-EVENT-CONNECTED - Connection to C0.AA.48 completed (auth) [id=0 id_str=]
,I/wpa_supplicant( 1273): Blacklist: Clear (temp) 
I/wpa_supplicant( 1273): CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=C0.AA.48 SSID=4E47373030
,E/WifiStateMachine(  839): SUPPLICANT_STATE_CHANGE_EVENT state=GROUP_HANDSHAKE -> state= AUTHENTICATING debouncing=false
E/WifiStateMachine(  839): setDetailed state, old =AUTHENTICATING and new state=AUTHENTICATING hidden=false
,I/FOTA_Client( 7755): [com.sec.android.fotaclient.FotaRegisterReceiver(113/onReceive)] Already device registered...
,E/WifiStateMachine(  839): Network connection established
D/WifiNative-HAL(  839): callSECApiVoid - ID [50]
,E/WifiStateMachine(  839): setDetailed state, old =AUTHENTICATING and new state=OBTAINING_IPADDR hidden=false
,E/WifiStateMachine(  839): setDetailed state, old =OBTAINING_IPADDR and new state=CONNECTING hidden=false
,I/FOTA_Client( 7755): [com.sec.android.fotaclient.FotaUpdaterReceiver(103/onReceive)] Auto update settings is activated
,D/ConnectivityService(  839): registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{false} explicitlySelected{false} }
E/WifiStateMachine(  839): L2ConnectedState c0:ff:d4:d3:aa:48 config "NG700"WPA_PSK config.bssid any
E/WifiStateMachine(  839): L2ConnectedState "NG700" nid=0
E/WifiConfigStore(  839): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,D/ConnectivityService(  839): Got NetworkAgent Messenger
D/ConnectivityService(  839): hsengiv:checkWhatTypeOfNetwork and the value is false
E/ConnectivityService(  839): updateNetworkInfo()
D/ConnectivityService(  839): NetworkAgentInfo [WIFI () - 503] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityService(  839): NetworkAgent connected
,I/CLocInfoService(  839): External Intent Received android.net.wifi.STATE_CHANGE
,D/StatusBar.NetworkController( 1172): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020498/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020133/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020464/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
,E/WifiStateMachine(  839): enter ObtainingIpState netId=0 "NG700"WPA_PSK  roam=0 static=false watchdog= 1
E/WifiStateMachine(  839): ObtainingIpAddress c0:ff:d4:d3:aa:48 config "NG700"WPA_PSK config.bssid any
E/WifiStateMachine(  839): ObtainingIpAddress "NG700" nid=0
E/WifiConfigStore(  839): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,I/FOTA_Client( 7755): [lllllllllllIlllllIIl(197/lllIlIlIIIllIIlIllIl)] Polling time is vaild
,I/FOTA_Client( 7755): [com.sec.android.fotaclient.FotaUpdaterReceiver(126/onReceive)] Heartbeat settings is activated.
,D/CommandListener(  275): Setting iface cfg
,I/FOTA_Client( 7755): [llIlIIIIlllIlllllIll(125/llIlIIIIlIIIIIlIlIII)] heartbeat time is vaild
,E/WifiStateMachine(  839): Start Dhcp Watchdog 2
,D/SecContentProvider2(  839): uri = 20 selection = getPromptCredentialsEnabled
,D/SecContentProvider2(  839): mCursor = null
,E/ActivityManager(  839): checkUser: useridlist=null, currentuser=0
,I/WifiStateMachine(  839): CMD_RSSI_POLL : calculateWifiScore in!
,E/WifiStateMachine(  839): calculateWifiScore() report new score 60
E/ActivityManager(  839): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  839): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  839): checkUser: useridlist=null, currentuser=0
I/WifiStateMachine(  839): calculateWifiScore : sendNetworkScore in!
I/WifiStateMachine(  839): calculateWifiScore : sendNetworkScore out!
I/WifiStateMachine(  839): CMD_RSSI_POLL : calculateWifiScore out!
I/WifiStateMachine(  839): CMD_RSSI_POLL : out!
D/ConnectivityService(  839): updateNetworkScore for NetworkAgentInfo [WIFI () - 503] to 60
,E/WifiStateMachine(  839): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576} new: {InterfaceName: wlan0 LinkAddresses: []  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0}
,D/ConnectivityService(  839): Update of LinkProperties for NetworkAgentInfo [WIFI () - 503]; created=false
E/WifiStateMachine(  839): updateLinkProperties nid: 0 state: CONNECTING reason: CMD_UPDATE_LINKPROPERTIES
,W/libprocessgroup(  839): failed to open /acct/uid_10042/pid_6073/cgroup.procs: No such file or directory
,E/Zygote  ( 7775): MountEmulatedStorage()
E/Zygote  ( 7775): v2
I/libpersona( 7775): KNOX_SDCARD checking this for 10019
I/libpersona( 7775): KNOX_SDCARD not a persona
,I/ActivityManager(  839): Start proc com.samsung.klmsagent for broadcast com.samsung.klmsagent/.listner.MainReciver: pid=7775 uid=10019 gids={50019, 9997, 3003} abi=armeabi-v7a
,I/ActivityManager(  839): Killing 6850:com.osp.app.signin/u0a45 (adj 15): bgCount ##41
,I/SELinux ( 7775): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 7775): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 7775): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 7775): TimaSignature is unavailable
,D/ActivityThread( 7775): Added TimaKeyStore provider
,D/ResourcesManager( 7775): creating new AssetManager and set to /system/priv-app/KLMSAgent/KLMSAgent.apk
,W/libprocessgroup(  839): failed to open /acct/uid_10045/pid_6850/cgroup.procs: No such file or directory
,I/KLMS-2.4.503: ( 7775): KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,I/KLMS-2.4.503: ( 7775): MainReciver(): EventNotificationReciver- method called: AppActivityListner onReceive for Intent Action : android.net.conn.CONNECTIVITY_CHANGE , timestamp: 1449752907436
,I/KLMS-2.4.503: ( 7775): MainReciver(): NETWORK_STATE_CHANGED_ACTION
,D/ConnectivityService(  839): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  839): returning getNetworkInfo(networkType - 0) :[type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/KLMS-2.4.503: ( 7775): KLMSUtility(): isNetworkAvailable() - WIFI : false| MOBILE : false
I/KLMS-2.4.503: ( 7775): StateImplV2(): networkChangeListener().END
I/ActivityManager(  839): Killing 6871:com.sec.android.app.myfiles/u0a51 (adj 15): bgCount ##41
E/ActivityManager(  839): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  839): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  839): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  839): checkUser: useridlist=null, currentuser=0
,E/WifiStateMachine(  839): setSuspendOptimizationsNative: 1 false -want true stack:setSuspendOptimizationsNative - handlePreDhcpSetup - processMessage - processMsg
,E/native  (  839): do suspend false
,E/Zygote  ( 7791): MountEmulatedStorage()
,E/Zygote  ( 7791): v2
I/libpersona( 7791): KNOX_SDCARD checking this for 10037
I/libpersona( 7791): KNOX_SDCARD not a persona
,I/ActivityManager(  839): Start proc com.sec.android.soagent for broadcast com.sec.android.soagent/.RegisterReceiver: pid=7791 uid=10037 gids={50037, 9997, 3003} abi=armeabi-v7a
,D/SecContentProvider2(  839): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2(  839): mCursor = null
,D/WifiP2pService(  839): InactiveState{ what=143375 }
,D/WifiP2pService(  839): P2pEnabledState{ what=143375 }
,I/SELinux ( 7791): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 7791): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 7791): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,W/libprocessgroup(  839): failed to open /acct/uid_10051/pid_6871/cgroup.procs: No such file or directory
,D/TimaKeyStoreProvider( 7791): TimaSignature is unavailable
,D/ActivityThread( 7791): Added TimaKeyStore provider
,D/ResourcesManager( 7791): creating new AssetManager and set to /system/priv-app/SOAgent/SOAgent.apk
,I/SO_AGENT( 7791): [com.sec.android.soagent.RegisterReceiver(98/onReceive)] Network is not available
,E/ActivityManager(  839): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  839): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  839): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  839): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 7806): MountEmulatedStorage()
E/Zygote  ( 7806): v2
I/libpersona( 7806): KNOX_SDCARD checking this for 1000
I/libpersona( 7806): KNOX_SDCARD not a persona
,I/ActivityManager(  839): Start proc com.policydm for broadcast com.policydm/.XDMBroadcastReceiver: pid=7806 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,I/ActivityManager(  839): Killing 6889:com.sec.android.app.soundalive/u0a58 (adj 15): bgCount ##41
,I/SELinux ( 7806): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 7806): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 7806): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,W/libprocessgroup(  839): failed to open /acct/uid_10058/pid_6889/cgroup.procs: No such file or directory
,D/TimaKeyStoreProvider( 7806): TimaSignature is unavailable
D/ActivityThread( 7806): Added TimaKeyStore provider
,D/ResourcesManager( 7806): creating new AssetManager and set to /system/priv-app/SPDClient/SPDClient.apk
,D/ConnectivityService(  839): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  839): returning getNetworkInfo(networkType - 0) :[type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/ActivityManager(  839): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  839): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  839): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  839): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 7826): MountEmulatedStorage()
,E/Zygote  ( 7826): v2
I/libpersona( 7826): KNOX_SDCARD checking this for 10038
I/libpersona( 7826): KNOX_SDCARD not a persona
,I/ActivityManager(  839): Start proc com.sec.spp.push for broadcast com.sec.spp.push/.monitor.SystemStateMoniter: pid=7826 uid=10038 gids={50038, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  839): Killing 6242:com.samsung.android.app.assistantmenu/1000 (adj 15): bgCount ##41
,I/SELinux ( 7826): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 7826): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 7826): [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 7826): TimaSignature is unavailable
,D/ActivityThread( 7826): Added TimaKeyStore provider
,W/libprocessgroup(  839): failed to open /acct/uid_1000/pid_6242/cgroup.procs: No such file or directory
,E/dhcpcd  ( 7844): fopen `/system/etc/dhcpcd/dhcpcd.conf': No such file or directory
,I/dhcpcd  ( 7844): version 5.5.6 starting
,E/dhcpcd  ( 7844): fopen `/system/etc/dhcpcd/dhcpcd.conf': No such file or directory
,D/ConnectivityService(  839): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  839): returning getNetworkInfo(networkType - 0) :[type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ResourcesManager( 7826): creating new AssetManager and set to /system/priv-app/SPPPushClient_Prod/SPPPushClient_Prod.apk
,E/SPPClientService( 7826): ============PushLog. commonIsShipBuild. stop!
,E/SPPClientService( 7826): [PushClientApplication] Push log off : This is Ship build version
,D/SPPClientService( 7826): PushLog.txt file is not deleted.
,D/SPPClientService( 7826): PushLog.txt file is not deleted.
D/SPPClientService( 7826): ============PushLog. stop!
,I/dhcpcd  ( 7844): wlan0: sending IPv6 Router Solicitation
E/dhcpcd  ( 7844): wlan0: sendmsg: Cannot assign requested address
I/dhcpcd  ( 7844): if(wlan0) info get Success. (MAC : C0.AA.48)
I/dhcpcd  ( 7844): bssid match
,E/SPPClientService( 7826): [[SystemStateMoniter]] SystemStateMonitorService : noConnect? : true
I/dhcpcd  ( 7844): wlan0: rebinding lease of 192.168.1.135
,E/ActivityManager(  839): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  839): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  839): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  839): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 7852): MountEmulatedStorage()
,E/Zygote  ( 7852): v2
I/libpersona( 7852): KNOX_SDCARD checking this for 10045
I/libpersona( 7852): KNOX_SDCARD not a persona
,I/ActivityManager(  839): Start proc com.osp.app.signin for broadcast com.osp.app.signin/.OspReceiver: pid=7852 uid=10045 gids={50045, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  839): Killing 6627:com.sec.chaton/u0a86 (adj 15): bgCount ##41
,I/SELinux ( 7852): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 7852): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 7852): [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
,E/SPPClientService( 7826): [[SystemStateMonitorService]] No Active Internet
,D/TimaKeyStoreProvider( 7852): TimaSignature is unavailable
,D/ActivityThread( 7852): Added TimaKeyStore provider
,W/libprocessgroup(  839): failed to open /acct/uid_10086/pid_6627/cgroup.procs: No such file or directory
,D/ResourcesManager( 7852): creating new AssetManager and set to /system/priv-app/Samsungservice2_xxhdpi/Samsungservice2_xxhdpi.apk
,I/SA      ( 7852): [SSP] onCreated
,I/SA      ( 7852): [TPM] There is no property file
,I/SA      ( 7852): [SCU] isHaveSA() - false
,I/SA      ( 7852): [TPM] getModelProperty : null
I/SA      ( 7852): [TPM] getCSCProperty : null
,I/SA      ( 7852): [DM] init START
,I/SA      ( 7852): [DM] This device is not a Vodafone
,W/ResourceType( 7852): Failure getting entry for 0x7f06000f (t=5 e=15) (error -75)
,W/ResourceType( 7852): Failure getting entry for 0x7f060007 (t=5 e=7) (error -75)
W/ResourceType( 7852): Failure getting entry for 0x7f060008 (t=5 e=8) (error -75)
W/ResourceType( 7852): Failure getting entry for 0x7f06000b (t=5 e=11) (error -75)
W/ResourceType( 7852): Failure getting entry for 0x7f06000c (t=5 e=12) (error -75)
,W/ResourceType( 7852): Failure getting entry for 0x7f060001 (t=5 e=1) (error -75)
W/ResourceType( 7852): Failure getting entry for 0x7f060013 (t=5 e=19) (error -75)
,W/ResourceType( 7852): No package identifier when getting value for resource number 0x00000000
,W/ResourceType( 7852): Failure getting entry for 0x7f060022 (t=5 e=34) (error -75)
W/ResourceType( 7852): Failure getting entry for 0x7f060023 (t=5 e=35) (error -75)
W/ResourceType( 7852): Failure getting entry for 0x7f060024 (t=5 e=36) (error -75)
W/ResourceType( 7852): Failure getting entry for 0x7f060025 (t=5 e=37) (error -75)
,W/ResourceType( 7852): Failure getting entry for 0x7f060026 (t=5 e=38) (error -75)
W/ResourceType( 7852): No package identifier when getting value for resource number 0x00000000
,W/ResourceType( 7852): Failure getting entry for 0x7f060010 (t=5 e=16) (error -75)
W/ResourceType( 7852): Failure getting entry for 0x7f060009 (t=5 e=9) (error -75)
W/ResourceType( 7852): Failure getting entry for 0x7f06000a (t=5 e=10) (error -75)
,W/ResourceType( 7852): Failure getting entry for 0x7f060002 (t=5 e=2) (error -75)
W/ResourceType( 7852): Failure getting entry for 0x7f060014 (t=5 e=20) (error -75)
W/ResourceType( 7852): Failure getting entry for 0x7f060015 (t=5 e=21) (error -75)
,I/SA      ( 7852): [SCU] isHaveSA() - false
I/SA      ( 7852): support phone number id : false
,I/SA      ( 7852): [DM] init END
I/SA      ( 7852): [OR] onReceive log=[SA = 2.1.0142 V = 21 HWD = 1920X1080 3.0 dpi = 480  SIZE = 2 LOCALE = en_US CSC = DBT MCC = 0 MNC 0 T = user DEVICE = klte P = kltexx I = LRX21T M = SM-G900F OKLEFT false DIS LRX21T.G900FXXU1BOD3 PSS = 5.219788042639568  ]
,I/SA      ( 7852): [OR] onReceive Intent=[ conn.CONNECTIVITY_CHANGE. networkInfo:[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] networkType:1 inetCondition:0 extraInfo:? noConnectivity:true ]
I/SA      ( 7852): [OR] == ACTION_CONNECTIVITY_CHANGE ==
,I/SA      ( 7852): [SLFUCHKMGR] constructor called
,I/SA      ( 7852): [TPMU]  strSIMState 	:SIM_STATE_UNKNOWN
I/SA      ( 7852): [OR] == isSIMCardReady false ==
,I/SA      ( 7852): [SCU] == networkStateCheck == false
I/SA      ( 7852): [OR] onReceive END
,I/ActivityManager(  839): Killing 6908:com.google.android.apps.docs/u0a98 (adj 15): bgCount ##41
,D/accuweather( 7399): [KK AccuPhone]>>> WC:30 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,D/accuweather( 7399): [KK AccuPhone]>>> WC:37 [0:0] oR : create UI manager : start
D/accuweather( 7399): [KK AccuPhone]>>> UIMEM:90 [0:0] getInstance
,D/accuweather( 7399): [KK AccuPhone]>>> UIMEM:78 [0:0] UIManager : create ui manager
,D/accuweather( 7399): [KK AccuPhone]>>> RM:73 [0:0] RefreshManager : create
D/accuweather( 7399): [KK AccuPhone]>>> RM:136 [0:0]  V init 
,D/daemonapp( 1328): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/accuweather( 7399): [KK AccuPhone]>>> RM:128 [0:0] updateCityList
,D/daemonapp( 1328): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/weatherinfo
,D/accuweather( 7399): [KK AccuPhone]>>> DBH:3354 [0:0] gADWI : count = 0
,D/daemonapp( 1328): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/accuweather( 7399): [KK AccuPhone]>>> UIMEM:106 [0:0] The widget does not exist in idle!!
,D/accuweather( 7399): [KK AccuPhone]>>> UIMEM:106 [0:0] The widget does not exist in idle!!
,E/ActivityManager(  839): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  839): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  839): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  839): checkUser: useridlist=null, currentuser=0
,W/libprocessgroup(  839): failed to open /acct/uid_10098/pid_6908/cgroup.procs: No such file or directory
,E/Zygote  ( 7873): MountEmulatedStorage()
E/Zygote  ( 7873): v2
I/libpersona( 7873): KNOX_SDCARD checking this for 1000
I/libpersona( 7873): KNOX_SDCARD not a persona
,I/ActivityManager(  839): Start proc com.sec.knox.bridge for broadcast com.sec.knox.bridge/.knoxusage.KnoxUsageReceiver: pid=7873 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,I/SELinux ( 7873): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 7873): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 7873): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 7873): TimaSignature is unavailable
,D/ActivityThread( 7873): Added TimaKeyStore provider
,D/ResourcesManager( 7873): creating new AssetManager and set to /system/app/Bridge/Bridge.apk
,W/ResourcesManager( 7873): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,I/KnoxUsageLogPro( 7873): KnoxUsageReceiver onReceive :android.net.conn.CONNECTIVITY_CHANGE myUserId=0
,I/KnoxUsageLogPro( 7873): premStatus:2
,I/KnoxUsageLogPro( 7873): isEulaShown : false
,I/KnoxUsageLogPro( 7873): KnoxUsageReceiver onReceive : not Processible, just return
,E/ActivityManager(  839): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  839): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  839): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  839): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 7888): MountEmulatedStorage()
,E/Zygote  ( 7888): v2
I/libpersona( 7888): KNOX_SDCARD checking this for 10086
I/libpersona( 7888): KNOX_SDCARD not a persona
,I/ActivityManager(  839): Start proc com.sec.chaton for broadcast com.sec.chaton/.receiver.NetStateReceiver: pid=7888 uid=10086 gids={50086, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  839): Killing 6962:com.vlingo.midas/u0a33 (adj 15): bgCount ##41
,I/SELinux ( 7888): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 7888): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 7888): [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
,V/AlarmManager(  839): waitForAlarm result :4
,W/libprocessgroup(  839): failed to open /acct/uid_10033/pid_6962/cgroup.procs: No such file or directory
,D/TimaKeyStoreProvider( 7888): TimaSignature is unavailable
,D/ActivityThread( 7888): Added TimaKeyStore provider
,D/ResourcesManager( 7888): creating new AssetManager and set to /system/app/ChatON_MARKET/ChatON_MARKET.apk
,W/ResourcesManager( 7888): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,D/BatteryService(  839): level:100, scale:100, status:5, health:2, present:true, voltage: 4296, temperature: 295, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
D/BatteryService(  839): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  839): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  839):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
I/MotionRecognitionService(  839): Plugged
I/MotionRecognitionService(  839): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1172): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1172): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1172):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3231): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 3231): Disconnected process message: 10
,D/PushModule( 7888): [PushClientApplication] (main) PushClientApplication.onCreate()
,I/PushModule( 7888): [PushClientApplication] (main) PushModule version: 0.9.01.12
,D/PushModule( 7888): [PushClientApplication] (main) Discovered public push client. disable in app push client.
,D/ChatON  ( 7888): [1][isApplicationInstalled] com.android.mms was installed
,W/ContextImpl( 7888): Implicit intents with startService are not safe: Intent { act=com.sec.chaton.push.PUSH_CLIENT_SERVICE_ACTION } android.content.ContextWrapper.startService:533 com.sec.chaton.global.GlobalApplication.onCreate:358 android.app.Instrumentation.callApplicationOnCreate:1020 
,W/ActivityManager(  839): Unable to start service Intent { act=com.sec.chaton.push.PUSH_CLIENT_SERVICE_ACTION } U=0: not found
,D/ChatON  ( 7888): [1][a] ChatONV isn't installed.
D/ChatON  ( 7888): [1][a] ChatONVPlugIn.isAvailable()
,E/ActivityManager(  839): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  839): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  839): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  839): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 7907): MountEmulatedStorage()
E/Zygote  ( 7907): v2
I/libpersona( 7907): KNOX_SDCARD checking this for 10088
I/libpersona( 7907): KNOX_SDCARD not a persona
,I/ActivityManager(  839): Start proc com.android.chrome for broadcast com.android.chrome/com.google.android.apps.chrome.precache.PrecacheServiceLauncher: pid=7907 uid=10088 gids={50088, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  839): Killing 6938:com.sec.android.automotive.drivelink/u0a99 (adj 15): bgCount ##41
,I/SELinux ( 7907): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 7907): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 7907): [DEBUG] get_category: variable seinfo: chrome sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 7907): TimaSignature is unavailable
,D/ActivityThread( 7907): Added TimaKeyStore provider
,D/ResourcesManager( 7907): creating new AssetManager and set to /system/app/Chrome/Chrome.apk
,W/libprocessgroup(  839): failed to open /acct/uid_10099/pid_6938/cgroup.procs: No such file or directory
,I/ActivityManager(  839): Killing 7003:com.samsung.android.intelligenceservice/u0a3 (adj 15): bgCount ##41
,D/Headlines( 5524): HeadlinesSystemBroadcastReceiver onReceive android.net.conn.CONNECTIVITY_CHANGE
,D/HeadlinesChannelUtil( 5524): getCountryCode(): countryCode = DE
,E/ActivityManager(  839): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  839): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  839): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  839): checkUser: useridlist=null, currentuser=0
,D/Headlines( 5524): Breath.onStartCommand : com.samsung.android.internal.headlines.UPDATE_WELCOME_CARD flag : 0
D/HeadlinesCardManager( 5524): updateCategory : HeadlinesCardManager:updateCategory() category size == 0
,D/HeadlinesCardManager( 5524): updateCategory : HeadlinesCardManager:updateCategory() try to query category list
D/Headlines( 5524): queryCategory.  mRequest is not initialized.
,D/HeadlinesCardManager( 5524): updateCategory : HeadlinesCardManager:updateCategory() reponse : false
D/HeadlinesCardManager( 5524): requestUpdateNewsWelcomeCard : request update welcome card to content card.
D/HeadlinesDataCenter( 5524): requestUpdateNewsWelcomeCard !!! no welcome card
,E/Zygote  ( 7923): MountEmulatedStorage()
E/Zygote  ( 7923): v2
I/libpersona( 7923): KNOX_SDCARD checking this for 10128
I/libpersona( 7923): KNOX_SDCARD not a persona
,I/ActivityManager(  839): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=7923 uid=10128 gids={50128, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/SELinux ( 7923): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 7923): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 7923): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 7923): TimaSignature is unavailable
,D/ActivityThread( 7923): Added TimaKeyStore provider
,D/ResourcesManager( 7923): creating new AssetManager and set to /system/app/Newsstand/Newsstand.apk
,W/libprocessgroup(  839): failed to open /acct/uid_10003/pid_7003/cgroup.procs: No such file or directory
,E/Vold    (  248): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  248): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7923): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache
,E/Vold    (  248): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  248): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7923): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/files
,E/Vold    (  248): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  248): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7923): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache
,E/Vold    (  248): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  248): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7923): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/files
,I/WebViewFactory( 7923): Loading com.google.android.webview version 37 (1726107-arm) (code 119201)
,D/ResourcesManager( 7923): creating new AssetManager and set to /system/app/WebViewGoogle/WebViewGoogle.apk
,I/LibraryLoader( 7923): Loading: webviewchromium
,I/LibraryLoader( 7923): Time to load native libraries: 4 ms (timestamps 2019-2023)
,I/LibraryLoader( 7923): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 7923): Binding Chromium to main looper Looper (main, tid 1) {9159d79}
,I/LibraryLoader( 7923): Expected native library version number "",actual native library version number ""
,I/chromium( 7923): [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 7923): Initializing chromium process, renderers=0
,W/art     ( 7923): Attempt to remove local handle scope entry from IRT, ignoring
,W/chromium( 7923): [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
,I/chromium( 7923): [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=41 off=46768 len=2953
,I/chromium( 7923): [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:42 off:229524 len:643667
,W/AudioManagerAndroid( 7923): Requires BLUETOOTH permission
,I/Adreno-EGL( 7923): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 7923): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 7923): Build Date: 03/03/15 Tue
I/Adreno-EGL( 7923): Local Branch: LA.BF.1.1_RB1_20150108_025_1077123_1158499
I/Adreno-EGL( 7923): Remote Branch: 
I/Adreno-EGL( 7923): Local Patches: 
I/Adreno-EGL( 7923): Reconstruct Branch: 
,I/NSApplication( 7923): Starting up...
,E/ActivityManager(  839): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  839): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  839): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  839): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 7978): MountEmulatedStorage()
,E/Zygote  ( 7978): v2
I/libpersona( 7978): KNOX_SDCARD checking this for 10138
I/libpersona( 7978): KNOX_SDCARD not a persona
,I/ActivityManager(  839): Start proc com.samsung.android.sconnect for broadcast com.samsung.android.sconnect/.periph.PeriphStartReceiver: pid=7978 uid=10138 gids={50138, 9997, 3002, 3001, 1028, 1015, 3003} abi=armeabi-v7a
,I/ActivityManager(  839): Killing 7009:com.sec.android.provider.logsprovider/u0a20 (adj 15): bgCount ##41
,I/dhcpcd  ( 7844): wlan0: acknowledged 192.168.1.135 from 192.168.1.1
,I/art     (  326): Explicit concurrent mark sweep GC freed 8727(371KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 14MB/23MB, paused 280us total 22.854ms
,I/art     (  326): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 14MB/23MB, paused 250us total 8.632ms
,I/SELinux ( 7978): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
I/SELinux ( 7978): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
E/SELinux ( 7978): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/dhcpcd  ( 7844): wlan0: leased 192.168.1.135 for 86400 seconds
,I/art     (  326): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 14MB/23MB, paused 257us total 13.267ms
,E/WifiStateMachine(  839): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: []  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576} new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.135/24,]  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0}
,E/WifiStateMachine(  839): updateLinkProperties nid: 0 state: CONNECTING reason: CMD_UPDATE_LINKPROPERTIES v4
D/ConnectivityService(  839): Update of LinkProperties for NetworkAgentInfo [WIFI () - 503]; created=false
,W/libprocessgroup(  839): failed to open /acct/uid_10020/pid_7009/cgroup.procs: No such file or directory
,D/TimaKeyStoreProvider( 7978): TimaSignature is unavailable
,D/ActivityThread( 7978): Added TimaKeyStore provider
,D/ResourcesManager( 7978): creating new AssetManager and set to /system/app/QuickConnect/QuickConnect.apk
,W/ResourcesManager( 7978): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,W/ResourcesManager( 7978): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
W/ResourcesManager( 7978): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,D/QuickConnect( 7978): PeriphStartReceiver.onReceive - android.net.conn.CONNECTIVITY_CHANGE
,I/QuickConnect( 7978): PeriphStartReceiver.onReceive - USER_OWNER care CONNECTIVITY_ACTION. run P service
,I/QuickConnect( 7978): PeriphStartReceiver.onReceive - no need to start
,E/ActivityManager(  839): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  839): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  839): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  839): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 8010): MountEmulatedStorage()
I/libpersona( 8010): KNOX_SDCARD checking this for 10163
E/Zygote  ( 8010): v2
I/libpersona( 8010): KNOX_SDCARD not a persona
,I/ActivityManager(  839): Start proc com.android.email for broadcast com.android.email/.EmailConnectivityManager: pid=8010 uid=10163 gids={50163, 9997, 3003, 1028, 1015, 1023, 3002, 3001, 1003} abi=armeabi-v7a
,I/ActivityManager(  839): Killing 7033:com.samsung.android.app.filterinstaller/1000 (adj 15): bgCount ##41
,I/SELinux ( 8010): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 8010): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 8010): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 8010): TimaSignature is unavailable
,D/ActivityThread( 8010): Added TimaKeyStore provider
,W/libprocessgroup(  839): failed to open /acct/uid_1000/pid_7033/cgroup.procs: No such file or directory
,D/ResourcesManager( 8010): creating new AssetManager and set to /system/app/SecEmail_K/SecEmail_K.apk
,W/ResourcesManager( 8010): Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
,W/ResourcesManager( 8010): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,W/ResourcesManager( 8010): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager( 8010): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,E/WifiStateMachine(  839): setSuspendOptimizationsNative: 1 true -want true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - processMessage - processMsg
,D/WifiP2pService(  839): InactiveState{ what=143375 }
,D/WifiP2pService(  839): P2pEnabledState{ what=143375 }
,E/WifiStateMachine(  839): WifiStateMachine DHCP successful
,E/WifiStateMachine(  839): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: [192.168.1.135/24,]  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576} new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.135/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0}
D/ConnectivityService(  839): Update of LinkProperties for NetworkAgentInfo [WIFI () - 503]; created=false
E/WifiStateMachine(  839): updateLinkProperties nid: 0 state: CONNECTING reason: DHCP_SUCCESS v4 v4r v4dns isprov
,E/WifiStateMachine(  839): WifiStateMachine: handleSuccessfulIpConfiguration and no scan results"NG700"WPA_PSK
D/WifiStateMachine(  839): Not connected state, yet.
E/WifiStateMachine(  839): VerifyingLinkState enter
,D/StatusBar.NetworkController( 1172): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020498/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020133/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020464/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
,D/WifiStateMachine(  839): updatePoorNetworkAvoidance - Poor Network Test Enabled / !mIsFmcNetwork : false / true - mPoorNetworkAvoidanceEnabled:disabled
D/WifiStateMachine(  839): updatePoorNetworkDetection - Airplane Mode Off / Mobile Data Enabled / SIM State-Ready / MobilePolicyDataDisabled / !mIsFmcNetwork : 
D/WifiStateMachine(  839): false / true / false / true / true - mPoorNetworkDetectionEnabled: disabled
D/WifiNative-HAL(  839): callSECApiInt - ID [210]
,E/WifiStateMachine(  839): setDetailed state, old =CONNECTING and new state=VERIFYING_POOR_LINK hidden=false
,E/ConnectivityService(  839): updateNetworkInfo()
D/ConnectivityService(  839): updateLinkProperties: newLp = {InterfaceName: wlan0 LinkAddresses: [192.168.1.135/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}
D/ConnectivityService(  839): Adding iface wlan0 to network 503
,D/RCPManagerService(  839): exchangeData() failure , invalid userId
,I/CLocInfoService(  839): External Intent Received android.net.wifi.STATE_CHANGE
,D/WifiWatchdogStateMachine(  839): updateDnsLinkProperty: enter
D/WifiWatchdogStateMachine.DnsPinger(  839): setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.135/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}
,D/WifiWatchdogStateMachine.DnsResolver(  839): setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.135/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}
D/WifiWatchdogStateMachine.SingDnsChecker(  839): setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.135/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}
,D/WifiWatchdogStateMachine.CaptivePortalDnsResolver(  839): setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.135/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}
,D/StatusBar.NetworkController( 1172): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020498/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020133/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020464/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
,E/WifiStateMachine(  839): VerifyingLinkState GOOD_LINK_DETECTED: transition to (new) connected (old)captive portal check
,D/WifiStateMachine(  839): Now, connected state.
E/WifiStateMachine(  839): setDetailed state, old =VERIFYING_POOR_LINK and new state=CAPTIVE_PORTAL_CHECK hidden=false
,E/WifiStateMachine(  839): setDetailed state, old =CAPTIVE_PORTAL_CHECK and new state=CONNECTED hidden=false
,I/WifiTrafficPoller(  839): evaluateTrafficStatsPolling
,I/CLocInfoService(  839): External Intent Received android.net.wifi.STATE_CHANGE
,D/StatusBar.NetworkController( 1172): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020498/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020133/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020464/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
,D/RCPManagerService(  839): exchangeData() failure , invalid userId
D/ConnectivityService(  839): Adding Route [fe80::/64 -> :: wlan0] to network 503
,E/WifiStateMachine(  839): Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,D/ConnectivityService(  839): Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 503
D/RCPManagerService(  839): exchangeData() failure , invalid userId
,D/ConnectivityService(  839): Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 503
,E/ConnectivityService(  839): Unexpected mtu value: 0, wlan0
I/WifiTrafficPoller(  839): evaluateTrafficStatsPolling
I/WifiTrafficPoller(  839): mBoosterFLAG : 0
I/WifiTrafficPoller(  839): current booster mode : FullMode
D/ConnectivityService(  839): updateSourceRoutes : add source routing for type : 1
D/ConnectivityService(  839): updateSourceRoutes : add src route for:192.168.1.135
,V/        (  275): QcRouteController
,E/WifiStateMachine(  839): ConnectedState Enter  mScreenOn=true scanperiod=20000
,D/WifiNative-HAL(  839): callSECApiVoid - ID [212]
,I/CLocInfoService(  839): External Intent Received android.net.wifi.STATE_CHANGE
,I/WifiStateMachine(  839): REQUEST_POWER_SAVE_ON
,D/StatusBar.NetworkController( 1172): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020498/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020133/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020464/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
,D/StatusBar.NetworkController( 1172): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02012b/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020466/com.android.systemui:drawable/stat_sys_signal_inout mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
D/StatusBar.NetworkController( 1172): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1172): applyOpen
D/StatusBar.NetworkController( 1172): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1172): applyOpen
D/StatusBar.NetworkController( 1172): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1172): applyOpen
,D/StatusBar.NetworkController( 1172): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1172): applyOpen
,V/        (  275): QcRouteController
,V/        (  275): QcRouteController
,V/        (  275): QcRouteController
,E/ActivityManager(  839): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  839): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  839): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  839): checkUser: useridlist=null, currentuser=0
,D/RCPManagerService(  839): exchangeData() failure , invalid userId
,E/Zygote  ( 8053): MountEmulatedStorage()
E/Zygote  ( 8053): v2
I/libpersona( 8053): KNOX_SDCARD checking this for 10078
I/libpersona( 8053): KNOX_SDCARD not a persona
,I/ActivityManager(  839): Start proc com.sec.android.provider.badge for content provider com.sec.android.provider.badge/.BadgeProvider: pid=8053 uid=10078 gids={50078, 9997} abi=armeabi-v7a
,V/        (  275): QcRouteController
,V/BitmapFactory( 8010): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_015.png
,I/SELinux ( 8053): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,V/        (  275): QcRouteController
,I/SELinux ( 8053): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
V/        (  275): QcRouteController
,E/SELinux ( 8053): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,V/BitmapFactory( 8010): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_000.png
,D/RCPManagerService(  839): exchangeData() failure , invalid userId
,V/BitmapFactory( 8010): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_015.png
,V/BitmapFactory( 8010): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_000.png
,V/        (  275): QcRouteController
,V/BitmapFactory( 8010): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_000.png
,V/BitmapFactory( 8010): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_001.png
,V/BitmapFactory( 8010): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_002.png
,V/BitmapFactory( 8010): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_003.png
,V/BitmapFactory( 8010): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_004.png
,V/BitmapFactory( 8010): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_005.png
,D/ConnectivityService(  839): Setting Dns servers for network 503 to [/192.168.1.1]
V/BitmapFactory( 8010): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_006.png
D/Nat464Xlat(  839): requiresClat: netType=1, connected=false, hasIPv4Address=true
D/ConnectivityService(  839): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 503]
E/ConnectivityService(  839): updateNetworkInfo()
D/ConnectivityService(  839): calling update connectivity
E/ConnectivityService(  839): updateNetworkInfo()
D/ConnectivityService(  839): ignoring duplicate network state non-change
D/ConnectivityService(  839): ignoring duplicate network state non-change
D/ConnectivityService(  839): NetworkAgentInfo [WIFI () - 503] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityService(  839): notifyType PRECHECK for NetworkAgentInfo [WIFI () - 503]
D/ConnectivityService(  839): calling update connectivity
,D/ConnectivityService(  839): rematching NetworkAgentInfo [WIFI () - 503]
D/ConnectivityService(  839):  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityService(  839):   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  839):   checking if request is satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  839): currentScore = 0, newScore = 60
D/ConnectivityService(  839):    accepting network in place of null
D/ConnectivityService(  839): sending new Min Network Score(60): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,V/BitmapFactory( 8010): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_007.png
D/ConnectivityService(  839): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  839): DefaultState{ when=-2ms what=532481 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  839): Connected
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  839): EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  839): Validated
,V/BitmapFactory( 8010): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_008.png
,E/CSLegacyTypeTracker(  839): add() : Adding agent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{503}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.135/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{true} explicitlySelected{false} } for legacy network type 1
D/CSLegacyTypeTracker(  839): Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 503] isDefaultNetwork=true
D/ConnectivityService(  839): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,V/BitmapFactory( 8010): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_010.png
,V/BitmapFactory( 8010): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_011.png
,D/TelephonyNetworkFactory( 1466): Cellular releasing Network for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,D/ConnectivityService(  839): sendStickyBroadcastDelayed: delayMs=500, action=android.net.conn.CONNECTIVITY_CHANGE
,D/ConnectivityService(  839): Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{503}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.135/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{true} explicitlySelected{false} }
,D/ConnectivityService(  839): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 503]
D/ConnectivityService(  839): calling update connectivity
D/ConnectivityService(  839):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  839):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
,D/ConnectivityService(  839): sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  839): Validated NetworkAgentInfo [WIFI () - 503]
D/ConnectivityManager.CallbackHandler( 1172): CM callback handler got msg 524290
D/ConnectivityService(  839): rematching NetworkAgentInfo [WIFI () - 503]
,D/ConnectivityService(  839):  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityService(  839):   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  839): Network NetworkAgentInfo [WIFI () - 503] was already satisfying request 1. No change.
D/ConnectivityService(  839): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 503]
,D/ConnectivityService(  839): calling update connectivity
D/ConnectivityService(  839):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  839):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
V/BitmapFactory( 8010): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_012.png
,D/ConnectivityService(  839): sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  839): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
D/ConnectivityManager.CallbackHandler( 1172): CM callback handler got msg 524290
,V/BitmapFactory( 8010): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_013.png
,D/ConnectivityService(  839): returning getNetworkInfo(networkType - 0) :[type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SmartBondingService(  839): SmartBondingReceiver: onReceive action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/RCPManagerService(  839): exchangeData() failure , invalid userId
D/SmartBondingService(  839): EVENT_UPDATE_SB_STATE called / mDisableBySIOP false
D/SmartBondingService(  839): getSBEnabled() enabled =false
D/NtpTrustedTime(  839): currentTimeMillis() cache hit
V/NetworkStats(  839): updateIfacesLocked()
V/NetworkStats(  839): performPollLocked(flags=0x1)
,D/SmartBondingService(  839): getSBEnabled() enabled =false
D/SmartBondingService(  839): getSBEnabled() enabled =false
D/NetworkStatsFactory(  839): UpdateStatsForKnox
D/ConnectivityService(  839): returning getNetworkInfo(networkType - 28) :[type: MOBILE_ENT1[] - MOBILE_ENT1, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SmartBondingService(  839): getNetworkEnabled : wifi : true mobile : true
,D/NtpTrustedTime(  839): currentTimeMillis() cache hit
V/BitmapFactory( 8010): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_014.png
,D/NtpTrustedTime(  839): currentTimeMillis() cache hit
D/NtpTrustedTime(  839): currentTimeMillis() cache hit
V/NetworkStats(  839): advisePersistThreshold() given 9223372036854775, clamped to 2097152
D/NtpTrustedTime(  839): currentTimeMillis() cache hit
,V/NetworkStats(  839): performPollLocked() took 4ms
D/NtpTrustedTime(  839): currentTimeMillis() cache hit
D/TimaKeyStoreProvider( 8053): TimaSignature is unavailable
D/ConnectivityService(  839): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
V/BitmapFactory( 8010): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_015.png
,D/StatusBar.NetworkController( 1172): getUpdateDataNetType(): 0
D/StatusBar.NetworkController( 1172): updateDataNetType()
D/StatusBar.NetworkController( 1172): NoService, mRoamingIconId = 0
,D/StatusBar.NetworkController( 1172): updateDataIcon, mDataDirectionIconId = (null) mDataConnected = false
,D/StatusBar.NetworkController( 1172): updateTelephonySignalStrength: hasService=false ss=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte
D/StatusBar.NetworkController( 1172): updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal
D/ActivityThread( 8053): Added TimaKeyStore provider
,D/StatusBar.NetworkController( 1172): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02012b/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020466/com.android.systemui:drawable/stat_sys_signal_inout mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
D/StatusBar.NetworkController( 1172): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1172): applyOpen
D/StatusBar.NetworkController( 1172): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1172): applyOpen
D/StatusBar.NetworkController( 1172): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1172): applyOpen
D/NtpTrustedTime(  839): currentTimeMillis() cache hit
D/NtpTrustedTime(  839): currentTimeMillis() cache hit
D/StatusBar.NetworkController( 1172): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1172): applyOpen
,D/ConnectivityService(  839): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/StatusBar.NetworkController( 1172): getUpdateDataNetType(): 0
D/StatusBar.NetworkController( 1172): updateDataNetType()
D/StatusBar.NetworkController( 1172): NoService, mRoamingIconId = 0
,D/StatusBar.NetworkController( 1172): updateDataIcon, mDataDirectionIconId = (null) mDataConnected = false
D/StatusBar.NetworkController( 1172): updateTelephonySignalStrength: hasService=false ss=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte
,D/StatusBar.NetworkController( 1172): updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal
D/StatusBar.NetworkController( 1172): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02012b/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020466/com.android.systemui:drawable/stat_sys_signal_inout mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
,I/ActivityManager(  839): Killing 7050:com.samsung.android.app.watchmanagerstub/u0a112 (adj 15): bgCount ##41
,V/BitmapFactory( 8010): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_000.png
,V/BitmapFactory( 8010): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_001.png
,V/BitmapFactory( 8010): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_002.png
,V/BitmapFactory( 8010): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_003.png
,V/BitmapFactory( 8010): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_004.png
,V/BitmapFactory( 8010): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_005.png
,V/BitmapFactory( 8010): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_006.png
,D/ConnectivityService(  839): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,V/BitmapFactory( 8010): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_007.png
D/SecurityLogAgent( 7631): KnoxConfiguration : Current State = 1
,D/SecurityLogAgent( 7631): KnoxConfiguration : Current State Mapping Found 
D/SecurityLogAgent( 7631): StateMachine : Current State = 1
,D/ConnectivityService(  839): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
V/BitmapFactory( 8010): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_008.png
,V/BitmapFactory( 8010): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_010.png
,V/BitmapFactory( 8010): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_011.png
,V/BitmapFactory( 8010): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_012.png
,V/BitmapFactory( 8010): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_013.png
,V/BitmapFactory( 8010): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_014.png
,V/BitmapFactory( 8010): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_015.png
,V/BitmapFactory( 8010): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/delete_glance_line.pkm
,V/BitmapFactory( 8010): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/delete_glance_icon_undo.pkm
,V/BitmapFactory( 8010): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/list_icon_calendar_1.pkm
,V/BitmapFactory( 8010): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/email_attach_icon_etc.pkm
V/BitmapFactory( 8010): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/list_icon_flag.pkm
,V/BitmapFactory( 8010): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/list_icon_complate.pkm
V/BitmapFactory( 8010): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/list_icon_flag_off_white.pkm
,V/BitmapFactory( 8010): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/email_list_attach_icon_star_off.pkm
V/BitmapFactory( 8010): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/email_list_attach_icon_star_on.pkm
,V/BitmapFactory( 8010): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/list_icon_flag_f.pkm
,V/BitmapFactory( 8010): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/list_icon_complate_f.pkm
,V/BitmapFactory( 8010): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/list_icon_flag_off_f.pkm
,V/BitmapFactory( 8010): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/email_icon_foward.pkm
V/BitmapFactory( 8010): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/email_icon_foward_focus.pkm
,V/BitmapFactory( 8010): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/list_icon_reply_forward.pkm
,V/BitmapFactory( 8010): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/email_icon_reply.pkm
V/BitmapFactory( 8010): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/email_icon_reply_focus.pkm
,V/BitmapFactory( 8010): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/list_icon_vip.pkm
,V/BitmapFactory( 8010): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/email_list_high_priority.pkm
,V/BitmapFactory( 8010): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/email_list_low_priority.pkm
V/BitmapFactory( 8010): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/list_icon_server_draft.pkm
,V/BitmapFactory( 8010): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/list_icon_client_draft.pkm
,V/BitmapFactory( 8010): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/permission.pkm
,W/libprocessgroup(  839): failed to open /acct/uid_10112/pid_7050/cgroup.procs: No such file or directory
,V/BitmapFactory( 8010): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/list_icon_voicemail.pkm
V/BitmapFactory( 8010): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/list_icon_sms.pkm
,V/BitmapFactory( 8010): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/list_icon_sign.pkm
,V/BitmapFactory( 8010): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/list_icon_encryption.pkm
,V/BitmapFactory( 8010): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/tw_expander_open_01_holo_light.pkm
,V/BitmapFactory( 8010): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/tw_expander_close_01_holo_light.pkm
,I/art     (  839): Explicit concurrent mark sweep GC freed 70138(3MB) AllocSpace objects, 10(355KB) LOS objects, 30% free, 36MB/52MB, paused 1.626ms total 92.363ms
,D/PowerManagerService(  839): [s] UserActivityState : 1 -> 2
D/DisplayPowerController(  839): getFinalBrightness : 15 -> 15
,D/PowerManagerService(  839): [s] DisplayPowerCallbacks : onStateChanged()
,D/SecurityLogAgent( 7631): StateMachine : Changed Current State = 1
,I/ActivityManager(  839): Killing 7068:com.samsung.android.magazine.service/u0a118 (adj 15): bgCount ##41
,D/ResourcesManager( 8053): creating new AssetManager and set to /system/app/BadgeProvider/BadgeProvider.apk
,D/com.peel.receiver.ConnectivityActionReceiver( 5629): ConnectivityActionReceiver onReceive
D/com.peel.receiver.ConnectivityActionReceiver( 5629): 
D/com.peel.receiver.ConnectivityActionReceiver( 5629): 
D/com.peel.receiver.ConnectivityActionReceiver( 5629): country_code: Germany -- rom region: GB
D/com.peel.receiver.ConnectivityActionReceiver( 5629): 
,D/ConnectivityService(  839): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/lights  (  839): lcd : 32 +
,D/ConnectivityService(  839): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/com.peel.receiver.ConnectivityActionReceiver( 5629): 
D/com.peel.receiver.ConnectivityActionReceiver( 5629): 
D/com.peel.receiver.ConnectivityActionReceiver( 5629):  network type WIFI path... network offline: false
D/com.peel.receiver.ConnectivityActionReceiver( 5629): 
D/com.peel.receiver.ConnectivityActionReceiver( 5629): has active network... run services...
D/com.peel.receiver.ConnectivityActionReceiver( 5629): 
D/com.peel.receiver.ConnectivityActionReceiver( 5629): 
D/com.peel.receiver.ConnectivityActionReceiver( 5629): last run: 1449746146708 -- System.currentTimeMillis()-last_run: 6762670
D/com.peel.receiver.ConnectivityActionReceiver( 5629): ... skip 
D/com.peel.receiver.ConnectivityActionReceiver( 5629): ... skip last_72_check
,D/lights  (  839): lcd : 32 -
,E/ActivityManager(  839): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  839): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  839): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  839): checkUser: useridlist=null, currentuser=0
,D/BadgeProvider( 8053): onCreate
,D/BadgeProvider( 8053): DatabaseHelper
,E/Zygote  ( 8075): MountEmulatedStorage()
,E/Zygote  ( 8075): v2
I/libpersona( 8075): KNOX_SDCARD checking this for 10178
I/libpersona( 8075): KNOX_SDCARD not a persona
,D/lights  (  839): lcd : 23 +
,D/lights  (  839): lcd : 23 -
,I/ActivityManager(  839): Start proc com.samsung.android.service.travel for broadcast com.samsung.android.service.travel/com.samsung.android.travel.bindService.TravelBroadcastReceiver: pid=8075 uid=10178 gids={50178, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,D/DisplayPowerController(  839): getFinalBrightness : 15 -> 15
D/lights  (  839): lcd : 15 +
,D/lights  (  839): lcd : 15 -
,D/DisplayPowerController(  839): getFinalBrightness : 15 -> 15
,I/SELinux ( 8075): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 8075): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 8075): [DEBUG] get_category: variable seinfo: shared sensitivity: NULL, cateogry: NULL
,D/BadgeProvider( 8053): query, [selection] : package='com.android.email' AND class='com.android.email.activity.Welcome' AND extraData='base_extra_badge'
,D/BadgeProvider( 8053): sendNotify entered. [uri] : content://com.sec.badge/apps/1
D/BadgeProvider( 8053): sendNotify, [notify] : null
D/BadgeProvider( 8053): update, [uri] : content://com.sec.badge/apps/1
D/BadgeProvider( 8053): update, [BadgeCount] : badgecount=0
D/BadgeProvider( 8053): update, [UpdateCount] : 1
,D/TimaKeyStoreProvider( 8075): TimaSignature is unavailable
,D/ActivityThread( 8075): Added TimaKeyStore provider
,D/Launcher.Model( 1487): reloadBadges entered.
,W/libprocessgroup(  839): failed to open /acct/uid_10118/pid_7068/cgroup.procs: No such file or directory
,D/ResourcesManager( 8075): creating new AssetManager and set to /system/app/TravelService_K/TravelService_K.apk
,W/ActivityManager(  839): Unable to start service Intent { cmp=com.android.email/.service.AttachmentDownloadService } U=0: not found
,I/ActivityManager(  839): Killing 7084:com.samsung.helphub/1000 (adj 15): bgCount ##41
,D/ConnectivityService(  839): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  839): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  839): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  839): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  839): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ChimeraCfgMgr( 2359): Loading module com.google.android.gms.kids from APK com.google.android.gms
,D/ConnectivityService(  839): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  839): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ChimeraCfgMgr( 2359): Loading module com.google.android.gms.kids from APK com.google.android.gms
,W/libprocessgroup(  839): failed to open /acct/uid_1000/pid_7084/cgroup.procs: No such file or directory
,D/ConnectivityService(  839): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  839): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/WaitQueueForNetworkActivate( 7156): notifyNetworkActivated
,I/GLSUser ( 1661): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: ac2dm
,I/GLSUser ( 1661): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> ac2dm without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1661): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1661): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1661): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ContextImpl( 7156): Implicit intents with startService are not safe: Intent { act=com.sec.knox.containeragent.service.containermanager.ContainerManagerService } android.content.ContextWrapper.bindService:559 com.sec.knox.containeragent.ContainerManager.<init>:49 com.sec.android.app.samsungapps.vlibrary2.knoxmode.KNOXAPI.<init>:20 
,W/ActivityManager(  839): Unable to start service Intent { act=com.sec.knox.containeragent.service.containermanager.ContainerManagerService } U=0: not found
,V/BitmapFactory( 1661): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/common_ic_googleplayservices.png
,V/BitmapFactory( 1661): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  839): uri = 14 selection = getSealedState
D/SecContentProvider2(  839): mCursor = null
,D/SecContentProvider2(  839): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  839): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
V/ApplicationPolicy(  839): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,W/Kids    ( 2359): [AccountUtils] Account not ready
W/Kids    ( 2359): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/Kids    ( 2359): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/Kids    ( 2359): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/Kids    ( 2359): 	at com.google.android.gms.auth.p.c(SourceFile:550)
W/Kids    ( 2359): 	at com.google.android.gms.auth.p.b(SourceFile:477)
W/Kids    ( 2359): 	at com.google.android.gms.kids.account.k.d(SourceFile:103)
W/Kids    ( 2359): 	at com.google.android.gms.kids.account.p.a(SourceFile:70)
W/Kids    ( 2359): 	at com.google.android.gms.kids.account.t.a(SourceFile:62)
W/Kids    ( 2359): 	at com.google.android.gms.chimera.f.run(SourceFile:179)
W/Kids    ( 2359): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
W/Kids    ( 2359): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
W/Kids    ( 2359): 	at java.lang.Thread.run(Thread.java:818)
,D/StatusBar( 1172): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,I/PhoneStatusBar( 1172): Icon Only
D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
D/PanelView( 1172): There is/are notification(s) 
,D/PanelView( 1172): There is/are notification(s) 
,I/Hs20UtilService( 1306): Starting #8
I/Hs20UtilService( 1306): Message received 5007
,D/NearbySettings( 1306): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,V/NearbySettings( 1306): DMSUtil.isNetworkConnected - flag-null, state-null
D/ConnectivityService(  839): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/NearbySettings( 1306): DMSUtil.isNetworkConnected - WIFI: CONNECTED
D/hcjo    ( 7156): AutoUpdateManager:IDLE:execute
D/ConnectivityService(  839): returning getNetworkInfo(networkType - 13) :[type: WIFI_P2P[] - WIFI_P2P, state: UNKNOWN/IDLE, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/NearbySettings( 1306): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 1306): DMSUtil.isNetworkConnected - WIFI-true, Hotspot-false, P2P-false, Eth-false
,I/NearbySettings( 1306): MountReceiver.onReceive - Keep current state
,D/InitializeManagerStateMachine( 7156): execute::IDLE:EXECUTE
,D/InitializeManagerStateMachine( 7156): exit::IDLE
D/InitializeManagerStateMachine( 7156): entry::NETWORK_CHECK
,D/ConnectivityService(  839): returning getNetworkInfo(networkType - 0) :[type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/ConnectivityService(  839): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  839): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/InitializeManagerStateMachine( 7156): execute::NETWORK_CHECK:NETWORK_STATE_OK
D/InitializeManagerStateMachine( 7156): exit::NETWORK_CHECK
D/InitializeManagerStateMachine( 7156): entry::CHECK_COUNTRY_INFO
D/InitializeManagerStateMachine( 7156): execute::CHECK_COUNTRY_INFO:COUNTRY_INFO_OK
D/InitializeManagerStateMachine( 7156): exit::CHECK_COUNTRY_INFO
D/InitializeManagerStateMachine( 7156): entry::SUCCESS
D/hcjo    ( 7156): AutoUpdateManager:INITCHECK:onInitializeSuccess
,D/hcjo    ( 7156): AutoUpdateTriggerManager:IDLE:notifyNextTime
D/hcjo    ( 7156): AutoUpdateManager:UPD_CHECK_TIMING:onNoUpdateTime
,I/Hs20UtilService( 1306): Starting #9
D/ConnectivityService(  839): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/InitializeManagerStateMachine( 7156): exit::SUCCESS
D/InitializeManagerStateMachine( 7156): entry::IDLE
,I/Hs20UtilService( 1306): Message received 5007
,D/NearbySettings( 1306): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
I/NearbySettings( 1306): MountReceiver.onReceive - Keep current state
,I/Hs20UtilService( 1306): Starting #10
,I/Hs20UtilService( 1306): Message received 5007
,D/NearbySettings( 1306): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
V/NearbySettings( 1306): DMSUtil.isNetworkConnected - flag-null, state-null
,D/ConnectivityService(  839): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/NearbySettings( 1306): DMSUtil.isNetworkConnected - WIFI: CONNECTED
,D/ConnectivityService(  839): returning getNetworkInfo(networkType - 13) :[type: WIFI_P2P[] - WIFI_P2P, state: UNKNOWN/IDLE, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/NearbySettings( 1306): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 1306): DMSUtil.isNetworkConnected - WIFI-true, Hotspot-false, P2P-false, Eth-false
I/NearbySettings( 1306): MountReceiver.onReceive - Keep current state
,I/Hs20UtilService( 1306): Starting #11
,I/Hs20UtilService( 1306): Message received 5007
,D/NearbySettings( 1306): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,I/NearbySettings( 1306): MountReceiver.onReceive - Keep current state
,I/WifiStateMachine(  839): callSECApi what=220
D/WifiStateMachine(  839): SEC_COMMAND_ID_GET_FWS_OPEN_AP_CHECK : 0
,I/SurfaceFlinger(  249): id=16 createSurf (1x1),1 flag=4, Toast
,D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1172): value : false
D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
,D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
,D/ConnectivityService(  839): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/ConnectivityService(  839): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  839): returning getNetworkInfo(networkType - 0) :[type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/accuweather( 2115): [KK AccuPhone]>>> SWW:66 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,D/ConnectivityService(  839): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/SmartBondingService(  839): SmartBondingReceiver: onReceive action=android.net.conn.CONNECTIVITY_CHANGE
D/Tethering(  839): MasterInitialState.processMessage what=3
,D/SmartBondingService(  839): SmartBondingReceiver: wifi is connected
D/ConnectivityService(  839): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/SmartBondingService(  839): SmartBondingReceiver: wifi ap is not changed
,D/ConnectivityService(  839): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/ConnectivityService(  839): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/CLocInfoService(  839): External Intent Received android.net.conn.CONNECTIVITY_CHANGE
D/ConnectivityService(  839): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/SmartBondingService(  839): EVENT_UPDATE_SB_STATE called / mDisableBySIOP false
I/CLocInfoService(  839): CLocinfo wifi true 
D/SmartBondingService(  839): getSBEnabled() enabled =false
D/SmartBondingService(  839): getSBEnabled() enabled =false
D/SmartBondingService(  839): getSBEnabled() enabled =false
D/ConnectivityService(  839): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/ConnectivityService(  839): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  839): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SmartBondingService(  839): getNetworkEnabled : wifi : true mobile : true
,D/ConnectivityService(  839): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  839): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/ConnectivityService(  839): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
W/ContextImpl( 2023): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1994 android.content.ContextWrapper.startService:533 com.samsung.SMT.SamsungTTSService.d:-1 com.samsung.SMT.SamsungTTSService.a:-1 com.samsung.SMT.ai.onReceive:-1 
,D/PowerManagerService(  839): [api] acquire WakeLock flags=0x2000000a tag=WindowManager uid=1000 pid=839
I/SystemBroadcastReceiver( 7177): [#DCM#] [DCM_Performance] onReceive completed in time  1486 microsec. 
W/ContextImpl( 2023): Implicit intents with startService are not safe: Intent { act=com.samsung.SMT.UpdateManager.UPDATE_DATA } android.content.ContextWrapper.startService:533 com.samsung.SMT.SamsungTTSService.d:-1 com.samsung.SMT.SamsungTTSService.a:-1 
,D/DisplayPowerController(  839): getFinalBrightness : 41 -> 41
I/SystemBroadcastReceiver( 7177): [#DCM#] Calling notifyListeners. 
,D/ConnectivityService(  839): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/DCMController( 7177): [#DCM#] onIntentReceived eventid = EVENT_NETWORK_CHANGED
I/DCMController( 7177): [#DCM#] setIsConnectedForExtractors 
,D/ConnectivityService(  839): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/PowerManagerService(  839): [s] DisplayPowerCallbacks : onStateChanged()
,D/ConnectivityService(  839): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/DatabaseRebuilderTask( 7177): [#DCM#] postDBrebuildIntent rebuildLocation =  true
D/ConnectivityService(  839): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  839): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/NetworkMonitor( 5382): type=WIFI subType= reason=null isConnected=true
,D/lights  (  839): lcd : 18 +
,D/ConnectivityService(  839): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/DBG_DM  ( 3790): [lllllllIlllIIlllIlIl(88/llIIIIlllllIIllIIllI)] WiFi Network is connected
,I/DBG_DM  ( 3790): [com.wssyncmldm.XDMService(1111/IlIlllIIlIlIIIlIlIll)] WiFi network Connected : true
,D/ConnectivityService(  839): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/ConnectivityService(  839): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/LockPatternUtilsCache( 1172): value : false
D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1172): value : false
D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
,D/ConnectivityService(  839): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/PCWCLIENTTRACE_PushUtil( 7692): SPPPushClient is installed : true
I/PCWCLIENTTRACE_PushUtil( 7692): sales region : global
I/PCWCLIENTTRACE_PushUtil( 7692): getPushTypeList : [SPP, GCM]
I/PCWCLIENTTRACE_SYSTEMReceiver( 7692): [onReceive] - android.net.conn.CONNECTIVITY_CHANGE
,D/lights  (  839): lcd : 18 -
,D/ConnectivityService(  839): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/lights  (  839): lcd : 26 +
,D/lights  (  839): lcd : 26 -
,D/ConnectivityService(  839): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  839): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
,D/lights  (  839): lcd : 35 +
,D/lights  (  839): lcd : 35 -
,D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
,D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
,D/ConnectivityService(  839): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/DisplayPowerController(  839): getFinalBrightness : 41 -> 41
,D/lights  (  839): lcd : 41 +
,D/ConnectivityService(  839): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/ConnectivityService(  839): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/LockPatternUtilsCache( 1172): value : false
I/DIAGMON_AGENT( 7736): [lIIllllllllIlIlIllll(17/llIIIIlllllIIllIIllI)] Receive broadcast: android.net.conn.CONNECTIVITY_CHANGE
,I/DIAGMON_AGENT( 7736): [lIIllllllllIlIlIllll(31/llIIIIlllllIIllIIllI)] Running with RegistrationReceiver
,I/FrameworkService( 7177): [#DCM#] onCreate FrameworkService 
,I/FrameworkService( 7177): [#DCM#] onCreate FrameworkService end 
,I/DCMConfig( 7177): [#DCM#] getSuccessState = true
D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
I/FrameworkService( 7177): [#DCM#] onStartCommand(intent= Intent { act=com.samsung.dcm.action.DCM_EXECUTE cmp=com.samsung.dcm/.framework.FrameworkService (has extras) }, startId=1
,I/IntentHandler( 7177): [#DCM#] Intent action= com.samsung.dcm.action.DCM_EXECUTE, startId=1
,D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
,D/lights  (  839): lcd : 41 -
,D/DisplayPowerController(  839): getFinalBrightness : 41 -> 41
,D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1172): value : false
,D/SecContentProvider2(  839): uri = 11 selection = getMyKnoxAdmin
,D/SecContentProvider2(  839): mCursor = null
,D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
,I/SystemUtils( 7177): [#DCM#] LM: false,AM:677437440
,I/DCMThreadPoolExecutor( 7177): [#DCM#] Task being added DatabaseRebuilderTask
,I/DCMThreadPoolExecutor( 7177): [#DCM#] Task com.samsung.dcm.framework.extractormanager.task.DatabaseRebuilderTask@1fe155e3 is submitted
I/FrameworkService( 7177): [#DCM#] [DCM_Performance] onStartCommand completed , startId= 1 in time 34918 mirosec. 
,D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
,I/DatabaseRebuilderTask( 7177): [#DCM#] createLuceneReader done 
,I/DatabaseRebuilderTask( 7177): [#DCM#] resyncLocation   
I/DatabaseRebuilderTask( 7177): [#DCM#] resyncLocation: querying only for documents with deleted = 0 
,I/DatabaseRebuilderTask( 7177): [#DCM#] topDocs hits = 0
I/DatabaseRebuilderTask( 7177): [#DCM#] No of Location data to be added:  0
,I/DatabaseRebuilderTask( 7177): [#DCM#] releaseLuceneReader done 
I/DatabaseRebuilderTask( 7177): [#DCM#] Starting media manager do operation 
I/SystemUtils( 7177): [#DCM#] setHeavySharedPref set as  false
,D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1172): value : false
,I/IntentHandler( 7177): [#DCM#] Stopping service with ids up to  1
,I/DCMThreadPoolExecutor( 7177): [#DCM#] afterExecute FutureTask
,I/DCMController( 7177): [#DCM#] task finished =  com.samsung.dcm.framework.extractormanager.task.DatabaseRebuilderTask@1fe155e3
,I/FOTA_Client( 7755): [com.sec.android.fotaclient.FotaRegisterReceiver(113/onReceive)] Already device registered...
,D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
,I/FOTA_Client( 7755): [com.sec.android.fotaclient.FotaUpdaterReceiver(103/onReceive)] Auto update settings is activated
,I/FOTA_Client( 7755): [lllllllllllIlllllIIl(197/lllIlIlIIIllIIlIllIl)] Polling time is vaild
,I/FOTA_Client( 7755): [com.sec.android.fotaclient.FotaUpdaterReceiver(126/onReceive)] Heartbeat settings is activated.
,I/FOTA_Client( 7755): [llIlIIIIlllIlllllIll(125/llIlIIIIlIIIIIlIlIII)] heartbeat time is vaild
,I/KLMS-2.4.503: ( 7775): KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,I/KLMS-2.4.503: ( 7775): MainReciver(): EventNotificationReciver- method called: AppActivityListner onReceive for Intent Action : android.net.conn.CONNECTIVITY_CHANGE , timestamp: 1449752909912
,I/KLMS-2.4.503: ( 7775): MainReciver(): NETWORK_STATE_CHANGED_ACTION
,D/ConnectivityService(  839): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/ConnectivityService(  839): returning getNetworkInfo(networkType - 0) :[type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/KLMS-2.4.503: ( 7775): KLMSUtility(): isNetworkAvailable() - WIFI : true| MOBILE : false
,I/KLMS-2.4.503: ( 7775): StateImplV2(): networkChangeListener().START
,D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
,I/KLMS-2.4.503: ( 7775): NetworkChangeOperations(): uploadRequestLog().START 
,I/KLMS-2.4.503: ( 7775): StateImplV2(): networkChangeListener().END
,D/GCM     ( 1661): Connected
,D/ConnectivityService(  839): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
,D/ConnectivityService(  839): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  839): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  839): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/SO_AGENT( 7791): [com.sec.android.soagent.RegisterReceiver(104/onReceive)] Get Accessory List
,D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
,D/ConnectivityService(  839): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/GCM     ( 1661): Message class com.google.f.a.a.p
,D/ConnectivityService(  839): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  839): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
,D/ConnectivityService(  839): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  839): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/SPPClientService( 7826): [[SystemStateMoniter]] SystemStateMonitorService : noConnect? : false
,D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
,E/SMD     (  280): DCD ON
,I/SA      ( 7852): [OR] onReceive log=[SA = 2.1.0142 V = 21 HWD = 1920X1080 3.0 dpi = 480  SIZE = 2 LOCALE = en_US CSC = DBT MCC = 0 MNC 0 T = user DEVICE = klte P = kltexx I = LRX21T M = SM-G900F OKLEFT false DIS LRX21T.G900FXXU1BOD3 PSS = 5.219788042639568  ]
,I/SA      ( 7852): [OR] onReceive Intent=[ conn.CONNECTIVITY_CHANGE. networkInfo:[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] networkType:1 inetCondition:0 extraInfo:? isDefault:true ]
I/SA      ( 7852): [OR] == ACTION_CONNECTIVITY_CHANGE ==
,I/SA      ( 7852): [TPMU]  strSIMState 	:SIM_STATE_UNKNOWN
,I/SA      ( 7852): [OR] == isSIMCardReady false ==
D/ConnectivityService(  839): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/SA      ( 7852): [SCU] == networkStateCheck == true
I/SA      ( 7852): [DM] getCountryCodeFromCSC : DE
I/SA      ( 7852): isChinaCountryCode : false
,I/SA      ( 7852): [SCU] is ChinestModel Data Restricted   : false
I/SA      ( 7852): [OR] == networkStateCheck true ==
,D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
,D/ConnectivityService(  839): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/SA      ( 7852): [OR] GetMyCountryZoneTask
,I/SA      ( 7852): [OR] onReceive END
,I/SA      ( 7852): [SRS] prepareGetMyCountryZone
,D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
,D/ConnectivityService(  839): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/SA      ( 7852): [TPMU]  strSIMState 	:SIM_STATE_UNKNOWN
,I/SA      ( 7852): [SSP] query invoked
,I/SA      ( 7852): [TPMU] GetMccFromDB : null
I/SA      ( 7852): [SCU] getMccFromPreferece mcc = 260
,I/SA      ( 7852): [TPM] isNoProxy(default) : true
,D/accuweather( 7399): [KK AccuPhone]>>> WC:30 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,D/accuweather( 7399): [KK AccuPhone]>>> UIMEM:106 [0:0] The widget does not exist in idle!!
,D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
,I/KnoxUsageLogPro( 7873): KnoxUsageReceiver onReceive :android.net.conn.CONNECTIVITY_CHANGE myUserId=0
I/KnoxUsageLogPro( 7873): premStatus:2
,I/KnoxUsageLogPro( 7873): isEulaShown : false
I/KnoxUsageLogPro( 7873): KnoxUsageReceiver onReceive : not Processible, just return
,E/File    ( 7852): fail readDirectory() errno=2
,D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
,D/Headlines( 5524): HeadlinesSystemBroadcastReceiver onReceive android.net.conn.CONNECTIVITY_CHANGE
D/HeadlinesChannelUtil( 5524): getCountryCode(): countryCode = DE
,D/Headlines( 5524): Breath.onStartCommand : com.samsung.android.internal.headlines.UPDATE_WELCOME_CARD flag : 0
D/HeadlinesCardManager( 5524): updateCategory : HeadlinesCardManager:updateCategory() category size == 0
D/HeadlinesCardManager( 5524): updateCategory : HeadlinesCardManager:updateCategory() try to query category list
D/Headlines( 5524): queryCategory.  mRequest is not initialized.
D/HeadlinesCardManager( 5524): updateCategory : HeadlinesCardManager:updateCategory() reponse : false
D/HeadlinesCardManager( 5524): requestUpdateNewsWelcomeCard : request update welcome card to content card.
D/HeadlinesDataCenter( 5524): requestUpdateNewsWelcomeCard !!! no welcome card
,D/ConnectivityService(  839): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/Watchdog(  839): !@Sync 3
,D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
,D/ConnectivityService(  839): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  839): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/QuickConnect( 7978): PeriphStartReceiver.onReceive - android.net.conn.CONNECTIVITY_CHANGE
,I/QuickConnect( 7978): PeriphStartReceiver.onReceive - USER_OWNER care CONNECTIVITY_ACTION. run P service
I/QuickConnect( 7978): PeriphStartReceiver.onReceive - no need to start
,D/ConnectivityService(  839): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  839): returning getNetworkInfo(networkType - 0) :[type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
,D/RCPManagerService(  839): exchangeData() failure , invalid userId
,D/RCPManagerService(  839): exchangeData() failure , invalid userId
,D/ConnectivityService(  839): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SecurityLogAgent( 7631): KnoxConfiguration : Current State = 1
D/SecurityLogAgent( 7631): KnoxConfiguration : Current State Mapping Found 
D/SecurityLogAgent( 7631): StateMachine : Current State = 1
,D/ConnectivityService(  839): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/SecurityLogAgent( 7631): StateMachine : Changed Current State = 1
,D/com.peel.receiver.ConnectivityActionReceiver( 5629): ConnectivityActionReceiver onReceive
D/com.peel.receiver.ConnectivityActionReceiver( 5629): 
D/com.peel.receiver.ConnectivityActionReceiver( 5629): 
D/com.peel.receiver.ConnectivityActionReceiver( 5629): country_code: Germany -- rom region: GB
D/com.peel.receiver.ConnectivityActionReceiver( 5629): 
,D/ConnectivityService(  839): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  839): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/com.peel.receiver.ConnectivityActionReceiver( 5629): 
D/com.peel.receiver.ConnectivityActionReceiver( 5629): 
D/com.peel.receiver.ConnectivityActionReceiver( 5629):  network type WIFI path... network offline: false
D/com.peel.receiver.ConnectivityActionReceiver( 5629): 
D/com.peel.receiver.ConnectivityActionReceiver( 5629): has active network... run services...
D/com.peel.receiver.ConnectivityActionReceiver( 5629): 
D/com.peel.receiver.ConnectivityActionReceiver( 5629): 
D/com.peel.receiver.ConnectivityActionReceiver( 5629): last run: 1449746146708 -- System.currentTimeMillis()-last_run: 6763388
D/com.peel.receiver.ConnectivityActionReceiver( 5629): ... skip 
D/com.peel.receiver.ConnectivityActionReceiver( 5629): ... skip last_72_check
,D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
,D/ConnectivityService(  839): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  839): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  839): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  839): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
,D/ConnectivityService(  839): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  839): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
,D/ChimeraCfgMgr( 2359): Loading module com.google.android.gms.kids from APK com.google.android.gms
,D/ConnectivityService(  839): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  839): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ChimeraCfgMgr( 2359): Loading module com.google.android.gms.kids from APK com.google.android.gms
,D/ConnectivityService(  839): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/hcjo    ( 7156): AutoUpdateManager:IDLE:execute
,D/InitializeManagerStateMachine( 7156): execute::IDLE:EXECUTE
,D/InitializeManagerStateMachine( 7156): exit::IDLE
D/InitializeManagerStateMachine( 7156): entry::NETWORK_CHECK
D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
,D/ConnectivityService(  839): returning getNetworkInfo(networkType - 0) :[type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  839): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/InitializeManagerStateMachine( 7156): execute::NETWORK_CHECK:NETWORK_STATE_OK
D/InitializeManagerStateMachine( 7156): exit::NETWORK_CHECK
D/InitializeManagerStateMachine( 7156): entry::CHECK_COUNTRY_INFO
D/InitializeManagerStateMachine( 7156): execute::CHECK_COUNTRY_INFO:COUNTRY_INFO_OK
D/InitializeManagerStateMachine( 7156): exit::CHECK_COUNTRY_INFO
D/InitializeManagerStateMachine( 7156): entry::SUCCESS
D/hcjo    ( 7156): AutoUpdateManager:INITCHECK:onInitializeSuccess
,D/hcjo    ( 7156): AutoUpdateTriggerManager:IDLE:notifyNextTime
D/hcjo    ( 7156): AutoUpdateManager:UPD_CHECK_TIMING:onNoUpdateTime
,D/ConnectivityService(  839): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/InitializeManagerStateMachine( 7156): exit::SUCCESS
D/InitializeManagerStateMachine( 7156): entry::IDLE
,D/ConnectivityService(  839): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
,I/GLSUser ( 1661): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: ac2dm
,I/GLSUser ( 1661): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> ac2dm without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1661): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1661): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1661): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
,V/BitmapFactory( 1661): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  839): uri = 14 selection = getSealedState
D/SecContentProvider2(  839): mCursor = null
,D/SecContentProvider2(  839): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  839): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
V/ApplicationPolicy(  839): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,W/Kids    ( 2359): [AccountUtils] Account not ready
W/Kids    ( 2359): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/Kids    ( 2359): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/Kids    ( 2359): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/Kids    ( 2359): 	at com.google.android.gms.auth.p.c(SourceFile:550)
W/Kids    ( 2359): 	at com.google.android.gms.auth.p.b(SourceFile:477)
W/Kids    ( 2359): 	at com.google.android.gms.kids.account.k.d(SourceFile:103)
W/Kids    ( 2359): 	at com.google.android.gms.kids.account.p.a(SourceFile:70)
W/Kids    ( 2359): 	at com.google.android.gms.kids.account.t.a(SourceFile:62)
W/Kids    ( 2359): 	at com.google.android.gms.chimera.f.run(SourceFile:179)
W/Kids    ( 2359): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
W/Kids    ( 2359): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
W/Kids    ( 2359): 	at java.lang.Thread.run(Thread.java:818)
,D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
,D/StatusBar( 1172): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,I/PhoneStatusBar( 1172): Icon Only
,D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
D/PanelView( 1172): There is/are notification(s) 
D/PanelView( 1172): There is/are notification(s) 
,D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
,D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1172): value : false
,D/ConnectivityService(  839): NetTransition Wakelock (NetworkAgentInfo [WIFI () - 502] cleared because we found a replacement network
,D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
,D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
,D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
,D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
,D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
,D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
,D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
,D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
,D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
,I/WifiStateMachine(  839): CMD_RSSI_POLL : calculateWifiScore in!
,I/WifiStateMachine(  839): CMD_RSSI_POLL : calculateWifiScore out!
I/WifiStateMachine(  839): CMD_RSSI_POLL : out!
,D/StatusBar.NetworkController( 1172): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02012b/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020466/com.android.systemui:drawable/stat_sys_signal_inout mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
,I/SA      ( 7852): [RC New] Execute method=[GET] start
,I/SA      ( 7852): [RC New] Security=[true]
,I/System.out( 7852): Thread-1305(ApacheHTTPLog):Reading from variable values from setDefaultValuesToVariables
,I/System.out( 7852): Thread-1305(ApacheHTTPLog):isShipBuild true
,I/System.out( 7852): Thread-1305(ApacheHTTPLog):SmartBonding Enabling is true, SHIP_BUILD is true, log to file is false, DBG is false
,I/jxcore-log( 7565): BLE supported!!
I/jxcore-log( 7565): 
,I/SA      ( 7852): [RC New] [v2liruge] api execute + 691
,I/SA      ( 7852): [RC New] executeRequest [v2liruge] httpResponse : HTTP/1.1 200 OK
,I/System.out( 7852): AsyncTask #1 calls detatch()
,I/SA      ( 7852): [ODM] saveOpenData( GEO_IP, PL )
,I/SA      ( 7852): [OCP] update openData : PL
,I/SA      ( 7852): [TPMU] getNetworkMcc : 
,I/SA      ( 7852): [SCU] saveMccToPreferece Start
,I/SA      ( 7852): [SCU] RegionMCC : 260
I/SA      ( 7852): [SSP] query invoked
,I/SA      ( 7852): [TPMU] GetMccFromDB : null
,I/SA      ( 7852): [SCU] getMccFromPreferece mcc = 260
I/SA      ( 7852): [SCU] saveMccToPreferece End
,I/SA      ( 7852): [RC New] executeRequest [v2liruge] end. 774
,I/SA      ( 7852): [RC New] Execute end
I/SA      ( 7852): [OR] GetMyCountryZoneTask mcc = 260
I/SA      ( 7852): [OR] GetMyCountryZoneTask Success
,V/AlarmManager(  839): waitForAlarm result :8
,I/GLSUser ( 1661): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.googlequicksearchbox, service: oauth2:https://www.googleapis.com/auth/googlenow
I/GLSUser ( 1661): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/googlenow without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1661): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1661): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1661): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ConnectivityService(  839): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ResourcesManager( 1661): creating new AssetManager and set to /system/priv-app/Velvet/Velvet.apk
,V/BitmapFactory( 1661): DecodeImagePath(decodeResourceStream3) : res/mipmap-xxhdpi-v4/ic_launcher_google_search.png
,V/BitmapFactory( 1661): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  839): uri = 14 selection = getSealedState
,D/SecContentProvider2(  839): mCursor = null
,D/SecContentProvider2(  839): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  839): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy(  839): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/StatusBar( 1172): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,W/Search.LoginHelper( 1554): User recoverable exception for scope: oauth2:https://www.googleapis.com/auth/googlenow
,I/dhcpcd  ( 7844): wlan0: sending IPv6 Router Solicitation
,E/dhcpcd  ( 7844): wlan0: sendmsg: Cannot assign requested address
,I/PhoneStatusBar( 1172): Icon Only
,D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
D/PanelView( 1172): There is/are notification(s) 
,D/PanelView( 1172): There is/are notification(s) 
,I/WifiStateMachine(  839): REQUEST_POWER_SAVE_ON
,E/WifiStateMachine(  839): CAPTIVE_PORTAL_EVENT_AUTHENTICATED
,E/WifiStateMachine(  839): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: [192.168.1.135/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576} new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.135/24,fe80::ee1f:72ff:fe18:8b78/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0}
E/WifiStateMachine(  839): updateLinkProperties nid: 0 state: CONNECTED reason: CMD_UPDATE_LINKPROPERTIES v4 v4r v4dns isprov
,D/ConnectivityService(  839): Update of LinkProperties for NetworkAgentInfo [WIFI () - 503]; created=true
,D/SmartBondingService(  839): SmartBondingReceiver: onReceive action=android.net.wifi.LINK_CONFIGURATION_CHANGED
D/ConnectivityService(  839): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/SmartBondingService(  839): EVENT_UPDATE_SB_STATE called / mDisableBySIOP false
D/SmartBondingService(  839): getSBEnabled() enabled =false
D/SmartBondingService(  839): getSBEnabled() enabled =false
D/SmartBondingService(  839): getSBEnabled() enabled =false
,D/ConnectivityService(  839): updateLinkProperties: newLp = {InterfaceName: wlan0 LinkAddresses: [192.168.1.135/24,fe80::ee1f:72ff:fe18:8b78/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}
,D/ConnectivityService(  839): identical MTU - not setting
,D/ConnectivityService(  839): updateSourceRoutes : add source routing for type : 1
,D/ConnectivityService(  839): updateSourceRoutes : add src route for:fe80::ee1f:72ff:fe18:8b78
,V/        (  275): QcRouteController
,V/        (  275): QcRouteController
,W/NetworkManagementService(  839): route cmd failed: 
W/NetworkManagementService(  839): com.android.server.NativeDaemonConnector$NativeDaemonFailureException: command '72 route replace src v6 wlan0 fe80::ee1f:72ff:fe18:8b78 2 ::' failed with '400 72 -6 route replace default via :: dev wlan0 scope global table 2: RTNETLINK answers: Invalid argument
W/NetworkManagementService(  839): '
W/NetworkManagementService(  839): 	at com.android.server.NativeDaemonConnector.execute(NativeDaemonConnector.java:438)
W/NetworkManagementService(  839): 	at com.android.server.NativeDaemonConnector.executeForList(NativeDaemonConnector.java:371)
W/NetworkManagementService(  839): 	at com.android.server.NativeDaemonConnector.execute(NativeDaemonConnector.java:336)
W/NetworkManagementService(  839): 	at com.android.server.NativeDaemonConnector.execute(NativeDaemonConnector.java:321)
W/NetworkManagementService(  839): 	at com.android.server.NetworkManagementService.replaceSrcRoute(NetworkManagementService.java:2812)
W/NetworkManagementService(  839): 	at com.android.server.ConnectivityService.updateSourceRoutes(ConnectivityService.java:5478)
W/NetworkManagementService(  839): 	at com.android.server.ConnectivityService.updateLinkProperties(ConnectivityService.java:5305)
W/NetworkManagementService(  839): 	at com.android.server.ConnectivityService.access$1800(ConnectivityService.java:230)
W/NetworkManagementService(  839): 	at com.android.server.ConnectivityService$NetworkStateTrackerHandler.handleMessage(ConnectivityService.java:2324)
W/NetworkManagementService(  839): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/NetworkManagementService(  839): 	at android.os.Looper.loop(Looper.java:145)
W/NetworkManagementService(  839): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,D/Nat464Xlat(  839): requiresClat: netType=1, connected=true, hasIPv4Address=true
D/ConnectivityService(  839): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 503]
D/ConnectivityService(  839): calling update connectivity
,D/ConnectivityService(  839):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  839):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
,D/ConnectivityService(  839): sending notification IP_CHANGED for NetworkRequest [ id=2, legacyType=-1, [] ]
,D/ConnectivityService(  839): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 503]
D/ConnectivityManager.CallbackHandler( 1172): CM callback handler got msg 524295
D/ConnectivityService(  839): calling update connectivity
D/ConnectivityService(  839):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,D/ConnectivityService(  839):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  839): sending notification IP_CHANGED for NetworkRequest [ id=2, legacyType=-1, [] ]
,D/ConnectivityManager.CallbackHandler( 1172): CM callback handler got msg 524295
,E/SMD     (  280): DCD ON
,D/ConnectivityService(  839): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  839): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
,D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
,D/PowerManagerService(  839): [api] [s] userActivity : event: 0 flags: 0 (uid: 1000 pid: 839) eventTime = 106615
,D/PowerManagerService(  839): [s] UserActivityState : 2 -> 1
,D/PowerManagerService(  839): [api] release WakeLock flags=0x2000000a tag=WindowManager uid=1000 pid=839 (0x0)
,D/PowerManagerService(  839): [api] applyWakeLockFlagsOnReleaseLocked : userActivityNoUpdateLocked is called : SCREEN_BRIGHT_WAKE_LOCK        'WindowManager' ON_AFTER_RELEASE (uid=1000, pid=839, ws=WorkSource{10059}) (elapsedTime=3493)
,D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
,D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1172): value : false
,D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
,D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
,D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
,D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
,D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
,D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1172): value : false
,I/WifiStateMachine(  839): CMD_RSSI_POLL : calculateWifiScore in!
,I/WifiStateMachine(  839): CMD_RSSI_POLL : calculateWifiScore out!
,I/WifiStateMachine(  839): CMD_RSSI_POLL : out!
,D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1172): value : false
,D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1172): value : false
,D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1172): value : false
,D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1172): value : false
,D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1172): value : false
,D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1172): value : false
,D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1172): value : false
,D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1172): value : false
,D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1172): value : false
,I/GAV4    ( 7923): Thread[GAThread,5,main]: No campaign data found.
,D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1172): value : false
,D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1172): value : false
,D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
,D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
,D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
,D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
,D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
,D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1172): value : false
,D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
,D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
,D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1172): value : false
,D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1172): value : false
,D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
,D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
,D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1172): value : false
,D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1172): value : false
,D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
,I/SurfaceFlinger(  249): id=16 Removed Toast (8/8)
,I/SurfaceFlinger(  249): id=16 Removed Toast (-2/8)
,D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1172): value : false
,D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1172): value : false
,I/Atfwd_Sendcmd(  341): AtCmdFwd service not ready - Exhausted retry attempts - :6
,I/Atfwd_Daemon(  341): result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,I/PCWCLIENTTRACE_SYSTEMReceiver( 7692): mConnectivityHandler : connected
,D/ConnectivityService(  839): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,W/PCWCLIENTTRACE_AccountUtil( 7692): [hasSamungAccount] - No Samsung Account
,I/CSTORAGE( 7692): ================================================
I/CSTORAGE( 7692):  CSTORAGE_SKM_LIB, v1.0.22, MSM8974|MSM8x26|MSM8x10
I/CSTORAGE( 7692): ================================================
I/PCWCLIENTTRACE_SecurePreferencesJNI( 7692): [GetString-S]
E/art     ( 7692): No implementation found for java.lang.String com.sec.pcw.device.util.SecurePreferencesJNI.getString() (tried Java_com_sec_pcw_device_util_SecurePreferencesJNI_getString and Java_com_sec_pcw_device_util_SecurePreferencesJNI_getString__)
W/PCWCLIENTTRACE_SecurePreferencesJNI( 7692): GetString : secure API is not supported!! No implementation found for java.lang.String com.sec.pcw.device.util.SecurePreferencesJNI.getString() (tried Java_com_sec_pcw_device_util_SecurePreferencesJNI_getString and Java_com_sec_pcw_device_util_SecurePreferencesJNI_getString__)
I/PCWCLIENTTRACE_SecurePreferencesJNI( 7692): [GetString-E]
I/PCWCLIENTTRACE_PushUtil( 7692): SPPPushClient is installed : true
I/PCWCLIENTTRACE_PushUtil( 7692): sales region : global
I/PCWCLIENTTRACE_PushUtil( 7692): getPushTypeList : [SPP, GCM]
E/PCWCLIENTTRACE_PCWHandler( 7692): [ensureRegistration] - No Samsung account
,I/dhcpcd  ( 7844): wlan0: sending IPv6 Router Solicitation
,E/SMD     (  280): DCD ON
,D/SSRM:m  (  839): SIOP:: AP = 400, PST = 435, CUR = 300
,I/WifiStateMachine(  839): CMD_RSSI_POLL : calculateWifiScore in!
,I/WifiStateMachine(  839): CMD_RSSI_POLL : calculateWifiScore out!
I/WifiStateMachine(  839): CMD_RSSI_POLL : out!
,D/StatusBar.NetworkController( 1172): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02012b/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020464/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth,
D/StatusBar.NetworkController( 1172): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1172): applyOpen,
,D/StatusBar.NetworkController( 1172): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1172): applyOpen
D/StatusBar.NetworkController( 1172): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1172): applyOpen
D/StatusBar.NetworkController( 1172): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1172): applyOpen
,W/ContextImpl(  839): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  280): DCD ON
,D/StatusBar.NetworkController( 1172): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02012b/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020466/com.android.systemui:drawable/stat_sys_signal_inout mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
,D/StatusBar.NetworkController( 1172): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1172): applyOpen
,D/StatusBar.NetworkController( 1172): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1172): applyOpen
D/StatusBar.NetworkController( 1172): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1172): applyOpen
D/StatusBar.NetworkController( 1172): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1172): applyOpen
,I/ServiceManager(  341): Waiting for service AtCmdFwd...
,I/WifiStateMachine(  839): CMD_RSSI_POLL : calculateWifiScore in!
,I/WifiStateMachine(  839): CMD_RSSI_POLL : calculateWifiScore out!
,I/WifiStateMachine(  839): CMD_RSSI_POLL : out!
,D/PreloadUpdateManagerStateMachine( 7156): execute::IDLE:EXECUTE
,D/PreloadUpdateManagerStateMachine( 7156): exit::IDLE
D/PreloadUpdateManagerStateMachine( 7156): entry::CHECK_TIMEOUT_FOR_UPDATE
,D/hcjo    ( 7156): AutoUpdateTriggerManager:IDLE:setInterval:86400000
,D/hcjo    ( 7156): AutoUpdateTriggerManager:IDLE:notifyNextTime
,D/PreloadUpdateManagerStateMachine( 7156): execute::CHECK_TIMEOUT_FOR_UPDATE:NO_TIMED_OUT
,D/PreloadUpdateManagerStateMachine( 7156): exit::CHECK_TIMEOUT_FOR_UPDATE
,D/PreloadUpdateManagerStateMachine( 7156): entry::IDLE
,I/dhcpcd  ( 7844): wlan0: sending IPv6 Router Solicitation
,I/dhcpcd  ( 7844): wlan0: no IPv6 Routers available
,D/PreloadUpdateManagerStateMachine( 7156): execute::IDLE:EXECUTE
,D/PreloadUpdateManagerStateMachine( 7156): exit::IDLE
D/PreloadUpdateManagerStateMachine( 7156): entry::CHECK_TIMEOUT_FOR_UPDATE
,D/hcjo    ( 7156): AutoUpdateTriggerManager:IDLE:notifyNextTime
,D/PreloadUpdateManagerStateMachine( 7156): execute::CHECK_TIMEOUT_FOR_UPDATE:NO_TIMED_OUT
,D/PreloadUpdateManagerStateMachine( 7156): exit::CHECK_TIMEOUT_FOR_UPDATE
,D/PreloadUpdateManagerStateMachine( 7156): entry::IDLE
,I/ServiceManager(  341): Waiting for service AtCmdFwd...
,D/StatusBar.NetworkController( 1172): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02012b/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020468/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
D/StatusBar.NetworkController( 1172): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1172): applyOpen
,D/StatusBar.NetworkController( 1172): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1172): applyOpen
D/StatusBar.NetworkController( 1172): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1172): applyOpen
D/StatusBar.NetworkController( 1172): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1172): applyOpen
,I/ServiceManager(  341): Waiting for service AtCmdFwd...
,D/FactoryTest( 6520): Not factory mode
D/FactoryTest( 6520): Not factory mode. isFactoryMode() returend false
,D/MTPRx   ( 6520): DRIVER_TIME_OUT 60s lapsed
D/MTPRx   ( 6520): still no open session command from host, so toast
,W/ContextImpl( 6520): Calling a method in the system process without a qualified user: android.app.ContextImpl.startActivity:1526 android.content.ContextWrapper.startActivity:337 android.content.ContextWrapper.startActivity:337 com.samsung.android.MtpApplication.MtpReceiver$3.handleMessage:713 android.os.Handler.dispatchMessage:102 
,W/ContextImpl( 6520): Calling a method in the system process without a qualified user: android.app.ContextImpl.startActivity:1538 android.app.ContextImpl.startActivity:1527 android.content.ContextWrapper.startActivity:337 android.content.ContextWrapper.startActivity:337 com.samsung.android.MtpApplication.MtpReceiver$3.handleMessage:713 
I/Timeline( 6520): Timeline: Activity_launch_request id:com.android.settings time:114822
,E/PersonaManagerService(  839): inState():  stateMachine is null !!
,V/ApplicationPolicy(  839): isApplicationStateBlocked userId 0 pkgname com.android.settings
,I/ActivityManager(  839): START u0 {flg=0x10000000 cmp=com.android.settings/.SettingsReceiverActivity} from uid 1000 on display 0
,D/CustomFrequencyManagerService(  839): acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1958400  uid : 1000  pid : 839  pkgName : ACTIVITY_RESUME_BOOSTER@6
,W/ActivityManager(  839): mDVFSHelper.acquire()
,D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1172): value : false
E/MTPRx   ( 6520): started activity for popup
D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1172): value : false
,I/SQLiteSecureOpenHelper( 3523): getWritableDatabase(pwd)
I/SQLiteSecureOpenHelper( 3523): getDatabaseLocked(b,b,pwd)...
,D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
,D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
,D/ConnectivityService(  839): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
,D/ResourcesManager( 6520): creating new AssetManager and set to /system/priv-app/SecSettings/SecSettings.apk
,W/ResourcesManager( 6520): Asset path '/system/framework/sec_platform_library.jar' does not exist or contains no resources.
,W/ResourcesManager( 6520): Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
W/ResourcesManager( 6520): Asset path '/system/framework/secvisualeffect.jar' does not exist or contains no resources.
W/ResourcesManager( 6520): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 6520): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 6520): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,W/ResourcesManager( 6520): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,E/SettingsReceiverActivity( 6520): PREF_DONT_ASK_AGAIN : true
,D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
,D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
,E/ActivityManager(  839): Invalid thumbnail dimensions: 576x576
,D/InputMethodManagerService(  839): windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,W/InputMethodManagerService(  839): Window already focused, ignoring focus gain of: com.android.internal.view.IInputMethodClient$Stub$Proxy@2d140c28 attribute=null, token = android.os.BinderProxy@22edb8f4
,I/SQLiteSecureOpenHelper( 3523): getWritableDatabase(pwd)
I/SQLiteSecureOpenHelper( 3523): getDatabaseLocked(b,b,pwd)...
,D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
,V/BitmapFactory( 6520): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_015.png
,V/BitmapFactory( 6520): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_000.png
,V/BitmapFactory( 6520): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_015.png
,V/BitmapFactory( 6520): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_000.png
,V/BitmapFactory( 6520): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_000.png
,V/BitmapFactory( 6520): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_001.png
,V/BitmapFactory( 6520): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_002.png
,V/BitmapFactory( 6520): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_003.png
,V/BitmapFactory( 6520): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_004.png
,V/BitmapFactory( 6520): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_005.png
,V/BitmapFactory( 6520): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_006.png
,V/BitmapFactory( 6520): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_007.png
,V/BitmapFactory( 6520): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_008.png
,V/BitmapFactory( 6520): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_010.png
,V/BitmapFactory( 6520): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_011.png
,V/BitmapFactory( 6520): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_012.png
,V/BitmapFactory( 6520): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_013.png
,V/BitmapFactory( 6520): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_014.png
,V/BitmapFactory( 6520): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_015.png
,V/BitmapFactory( 6520): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_000.png
,V/BitmapFactory( 6520): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_001.png
V/BitmapFactory( 6520): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_002.png
,V/BitmapFactory( 6520): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_003.png
,V/BitmapFactory( 6520): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_004.png
,V/BitmapFactory( 6520): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_005.png
,V/BitmapFactory( 6520): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_006.png
,V/BitmapFactory( 6520): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_007.png
,V/BitmapFactory( 6520): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_008.png
,V/BitmapFactory( 6520): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_010.png
,V/BitmapFactory( 6520): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_011.png
,V/BitmapFactory( 6520): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_012.png
,V/BitmapFactory( 6520): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_013.png
,V/BitmapFactory( 6520): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_014.png
,V/BitmapFactory( 6520): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_015.png
,D/SettingsReceiverActivity( 6520): dev.kiessupport is : TRUE
,D/Activity( 6520): performCreate Call secproduct feature valuefalse
,D/Activity( 6520): performCreate Call debug elastic valuetrue
,D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
,D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
,D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
,D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
,D/ActivityManager(  839): post active user change for 0
D/KnoxTimeoutHandler(  839): postActiveUserChange for user 0
,D/KnoxTimeoutHandler(  839): handleActiveUserChange for user 0
,D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
,D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
,D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
,I/Timeline( 7565): Timeline: Activity_idle id: android.os.BinderProxy@5a2a462 time:115077
,D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
,E/SMD     (  280): DCD ON
,D/ConnectivityService(  839): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/StatusBar.NetworkController( 1172): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02012b/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020464/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
D/StatusBar.NetworkController( 1172): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1172): applyOpen
,D/StatusBar.NetworkController( 1172): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1172): applyOpen
D/StatusBar.NetworkController( 1172): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1172): applyOpen
D/StatusBar.NetworkController( 1172): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1172): applyOpen
,I/ServiceManager(  341): Waiting for service AtCmdFwd...
,I/WifiStateMachine(  839): CMD_RSSI_POLL : calculateWifiScore in!
,I/WifiStateMachine(  839): CMD_RSSI_POLL : calculateWifiScore out!
I/WifiStateMachine(  839): CMD_RSSI_POLL : out!
,D/StatusBar.NetworkController( 1172): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02012b/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020468/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
D/StatusBar.NetworkController( 1172): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1172): applyOpen
,D/StatusBar.NetworkController( 1172): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1172): applyOpen
D/StatusBar.NetworkController( 1172): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1172): applyOpen
D/StatusBar.NetworkController( 1172): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1172): applyOpen
,I/ServiceManager(  341): Waiting for service AtCmdFwd...
,D/StatusBar.NetworkController( 1172): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02012b/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020466/com.android.systemui:drawable/stat_sys_signal_inout mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
D/StatusBar.NetworkController( 1172): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1172): applyOpen
,D/StatusBar.NetworkController( 1172): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1172): applyOpen
D/StatusBar.NetworkController( 1172): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1172): applyOpen
D/StatusBar.NetworkController( 1172): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1172): applyOpen
,W/Atfwd_Sendcmd(  341): AtCmdFwd service not published, waiting... retryCnt : 1
,D/CustomFrequencyManagerService(  839): releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1958400  uid : 1000  pid : 839  tag : ACTIVITY_RESUME_BOOSTER@6
,W/ActivityManager(  839): mDVFSHelper.release()
D/CustomFrequencyManagerService(  839): acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1958400  uid : 1000  pid : 839  pkgName : ACTIVITY_RESUME_BOOSTER@10
,D/CustomFrequencyManagerService(  839): releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1958400  uid : 1000  pid : 839  tag : ACTIVITY_RESUME_BOOSTER@10
,E/SMD     (  280): DCD ON
,D/StatusBar.NetworkController( 1172): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02012b/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020468/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
,D/StatusBar.NetworkController( 1172): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1172): applyOpen
,D/StatusBar.NetworkController( 1172): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1172): applyOpen
,D/StatusBar.NetworkController( 1172): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1172): applyOpen
,D/StatusBar.NetworkController( 1172): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1172): applyOpen
,I/WifiStateMachine(  839): CMD_RSSI_POLL : calculateWifiScore in!
,I/WifiStateMachine(  839): CMD_RSSI_POLL : calculateWifiScore out!
I/WifiStateMachine(  839): CMD_RSSI_POLL : out!
,D/StatusBar.NetworkController( 1172): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02012b/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020464/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
,D/StatusBar.NetworkController( 1172): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1172): applyOpen
,D/StatusBar.NetworkController( 1172): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1172): applyOpen
,D/StatusBar.NetworkController( 1172): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1172): applyOpen
,D/StatusBar.NetworkController( 1172): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1172): applyOpen
,D/SSRM:m  (  839): SIOP:: AP = 370, PST = 424, CUR = 300
,D/X       (  839): broadcastSiopLevelIntent:: currentSiopLevel = 0
,D/ContentApp( 1226):  LEVEL : 0
,D/ConnectivityService(  839): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/SystemBroadcastReceiver( 7177): [#DCM#] [DCM_Performance] onReceive completed in time  9572 microsec. 
,E/TranscodeReceiver( 7239): onReceive : android.intent.action.CHECK_SIOP_LEVEL
D/TranscodeReceiver( 7239):  SIOP_LEVEL: 0
,I/SystemBroadcastReceiver( 7177): [#DCM#] Calling notifyListeners. 
I/DCMPolicyManager( 7177): [#DCM#] onReceive action = EVENT_SIOP
,V/AlarmManager(  839): waitForAlarm result :4
,D/BatteryService(  839): level:100, scale:100, status:5, health:2, present:true, voltage: 4378, temperature: 296, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
D/BatteryService(  839): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  839): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  839):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  839): Plugged
I/MotionRecognitionService(  839): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1172): received broadcast android.intent.action.BATTERY_CHANGED
,D/STATUSBAR-PhoneStatusBar( 1172):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/KeyguardUpdateMonitor( 1172): handleBatteryUpdate
D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3231): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 3231): Disconnected process message: 10
,V/GLSActivity( 1661): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1661): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
I/GLSUser ( 1661): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1661): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1661): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1661): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/Finsky  ( 6694): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,D/Finsky  ( 6694): [1] 5.onFinished: Installation state replication failed.
D/Finsky  ( 6694): [1] 5.onFinished: Scheduling replication attempt 3.
,E/SMD     (  280): DCD ON
,V/AlarmManager(  839): waitForAlarm result :4
,D/ConnectivityService(  839): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/WifiStateMachine(  839): CMD_RSSI_POLL : calculateWifiScore in!
,I/WifiStateMachine(  839): CMD_RSSI_POLL : calculateWifiScore out!
I/WifiStateMachine(  839): CMD_RSSI_POLL : out!
,D/StatusBar.NetworkController( 1172): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02012b/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020466/com.android.systemui:drawable/stat_sys_signal_inout mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
D/StatusBar.NetworkController( 1172): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1172): applyOpen
D/StatusBar.NetworkController( 1172): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1172): applyOpen
D/StatusBar.NetworkController( 1172): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1172): applyOpen
I/ServiceManager(  341): Waiting for service AtCmdFwd...
D/StatusBar.NetworkController( 1172): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1172): applyOpen
,I/ServiceManager(  341): Waiting for service AtCmdFwd...
,D/StatusBar.NetworkController( 1172): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02012b/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020464/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
,D/StatusBar.NetworkController( 1172): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1172): applyOpen
,D/StatusBar.NetworkController( 1172): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1172): applyOpen
D/StatusBar.NetworkController( 1172): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1172): applyOpen
D/StatusBar.NetworkController( 1172): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1172): applyOpen
,E/SMD     (  280): DCD ON
,I/ServiceManager(  341): Waiting for service AtCmdFwd...
,I/WifiStateMachine(  839): CMD_RSSI_POLL : calculateWifiScore in!
,I/WifiStateMachine(  839): CMD_RSSI_POLL : calculateWifiScore out!
I/WifiStateMachine(  839): CMD_RSSI_POLL : out!
,I/ServiceManager(  341): Waiting for service AtCmdFwd...
,I/ServiceManager(  341): Waiting for service AtCmdFwd...
,E/SMD     (  280): DCD ON
,W/Atfwd_Sendcmd(  341): AtCmdFwd service not published, waiting... retryCnt : 2
,D/StatusBar.NetworkController( 1172): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02012b/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020466/com.android.systemui:drawable/stat_sys_signal_inout mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
,D/StatusBar.NetworkController( 1172): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1172): applyOpen
,D/StatusBar.NetworkController( 1172): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1172): applyOpen
,D/StatusBar.NetworkController( 1172): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1172): applyOpen
D/StatusBar.NetworkController( 1172): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1172): applyOpen
,I/WifiStateMachine(  839): CMD_RSSI_POLL : calculateWifiScore in!
,I/WifiStateMachine(  839): CMD_RSSI_POLL : calculateWifiScore out!
,I/WifiStateMachine(  839): CMD_RSSI_POLL : out!
,D/StatusBar.NetworkController( 1172): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02012b/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020464/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
,D/StatusBar.NetworkController( 1172): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1172): applyOpen
,D/StatusBar.NetworkController( 1172): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1172): applyOpen
D/StatusBar.NetworkController( 1172): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1172): applyOpen
D/StatusBar.NetworkController( 1172): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1172): applyOpen
,D/SSRM:m  (  839): SIOP:: AP = 340, PST = 409, CUR = 300
D/X       (  839): broadcastSiopLevelIntent:: currentSiopLevel = -1
,D/ContentApp( 1226):  LEVEL : -1
,E/TranscodeReceiver( 7239): onReceive : android.intent.action.CHECK_SIOP_LEVEL
,D/TranscodeReceiver( 7239):  SIOP_LEVEL: -1
I/SystemBroadcastReceiver( 7177): [#DCM#] [DCM_Performance] onReceive completed in time  12077 microsec. 
I/SystemBroadcastReceiver( 7177): [#DCM#] Calling notifyListeners. 
I/DCMPolicyManager( 7177): [#DCM#] onReceive action = EVENT_SIOP
,D/BatteryService(  839): level:100, scale:100, status:5, health:2, present:true, voltage: 4367, temperature: 297, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
D/BatteryService(  839): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
D/BatteryService(  839): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  839):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
I/MotionRecognitionService(  839): Plugged
I/MotionRecognitionService(  839): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1172): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1172): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1172):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3231): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 3231): Disconnected process message: 10
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  280): DCD ON
,D/PowerManagerService(  839): [s] UserActivityState : 1 -> 2
D/DisplayPowerController(  839): getFinalBrightness : 15 -> 15
,D/PowerManagerService(  839): [s] DisplayPowerCallbacks : onStateChanged()
,D/lights  (  839): lcd : 32 +
,D/lights  (  839): lcd : 32 -
,D/lights  (  839): lcd : 23 +
,D/lights  (  839): lcd : 23 -
,D/lights  (  839): lcd : 15 +
,D/DisplayPowerController(  839): getFinalBrightness : 15 -> 15
,D/lights  (  839): lcd : 15 -
,D/DisplayPowerController(  839): getFinalBrightness : 15 -> 15
,I/WifiStateMachine(  839): CMD_RSSI_POLL : calculateWifiScore in!
,I/WifiStateMachine(  839): CMD_RSSI_POLL : calculateWifiScore out!
,I/WifiStateMachine(  839): CMD_RSSI_POLL : out!
,W/ContextImpl(  839): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/StatusBar.NetworkController( 1172): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02012b/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020466/com.android.systemui:drawable/stat_sys_signal_inout mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
,D/StatusBar.NetworkController( 1172): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1172): applyOpen
,D/StatusBar.NetworkController( 1172): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1172): applyOpen
,D/StatusBar.NetworkController( 1172): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1172): applyOpen
D/StatusBar.NetworkController( 1172): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1172): applyOpen
,E/SMD     (  280): DCD ON
,V/AlarmManager(  839): waitForAlarm result :8
,D/KeyguardUpdateMonitor( 1172): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1172): handleTimeUpdate
,D/KeyguardEffectViewController( 1172): onReceive action : android.intent.action.TIME_TICK
I/KeyguardEffectViewController( 1172): *** don't update sliding image ***
,E/Watchdog(  839): !@Sync 4
,D/DateView( 1172): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1172): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/StatusBar.NetworkController( 1172): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02012b/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020464/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
,D/StatusBar.NetworkController( 1172): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1172): applyOpen
,D/StatusBar.NetworkController( 1172): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1172): applyOpen
D/StatusBar.NetworkController( 1172): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1172): applyOpen
D/StatusBar.NetworkController( 1172): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1172): applyOpen
,I/WifiStateMachine(  839): CMD_RSSI_POLL : calculateWifiScore in!
,I/WifiStateMachine(  839): CMD_RSSI_POLL : calculateWifiScore out!
I/WifiStateMachine(  839): CMD_RSSI_POLL : out!
,E/SMD     (  280): DCD ON
,D/PowerManagerService(  839): [s] UserActivityState : 2 -> 4
,I/PowerManagerService(  839): Nap time (uid 1000)...
,I/PowerManagerService(  839): !@[ps] Screen__Off(2) : 
I/PowerManagerService(  839): Going to sleep due to screen timeout (uid 1000)...
,D/PowerManagerService(  839): [PWL] sb acquire: PowerManagerService.Broadcasts
,D/PowerManagerService(  839): SecHardwareInterface.setBatteryADC : false
D/InputManager-JNI(  839): setDeviceInteractive: 0
,D/PowerManagerService(  839): handleSandman : startDream()
,D/InputManager-JNI(  839): sysfs_write +: /sys/class/input/event1/device/enabled: 0
,E/PowerManagerService(  839): handleSandman : startDreaming, but isDreaming false
D/InputManager-JNI(  839): sysfs_write -: /sys/class/input/event1/device/enabled: 0
,I/PowerManagerService(  839): Sleeping (uid 1000)...
,D/PowerManagerService(  839): [s] UserActivityState : 4 -> 0
,D/PowerManagerService(  839): [input device light] setInputDeviceLightOn is called : 0
,D/PowerManagerService(  839): [input device light] handleInputDeviceLightOff
,D/InputManager-JNI(  839): sysfs_write +: /sys/class/input/event2/device/enabled: 0
,I/SurfaceFlinger(  249): id=17 createSurf (1080x1920),2 flag=404, ColorFade
,D/InputManager-JNI(  839): sysfs_write -: /sys/class/input/event2/device/enabled: 0
,D/SContextService(  839): 	.unregisterCallback : 1, client=
,D/SContextService(  839): unregisterCallback() : Listener = android.hardware.scontext.SContextService$Listener@3e673928, Service = Auto Rotation, used = 1
,W/CAE     (  839): unregisterCallback(ContextAwareService.java:199) - [unregi 01] Mutex is locked for AUTO_ROTATION
,V/CAE     (  839): stop(ContextProvider.java:149)
,V/CAE     (  839): clear(AutoRotationRunner.java:182)
,V/CAE     (  839): disable(AutoRotationRunner.java:171)
,I/CAE     (  839): sendCmdToSensorHub(SensorHubCommManager.java:144) - -78, 7, 0, 0,
D/SensorHubManager(  839): SendSensorHubData: send data = -78, 7, 0, 0
,D/Sensorhubs(  298): sendContextData: -78, 7, 0, 0
,D/CAE     (  839): getFaultDetectionResult(AutoRotationRunner.java:195) - true
,I/CAE     (  839): notifyCmdProcessResultObserver(ContextProvider.java:617) - CheckResult = 0, Cause = Success
,D/CAE     (  839): doCommendProcess(ContextAwareService.java:314) - complete notify the operation result.
,I/CAE     (  839): displayUsedCountForService(ContextAwareService.java:406) - totalCnt = 0, serviceCount = 0, subCollectionCount = 0
,D/CAE     (  839): showListenerList(ContextAwareService.java:247) - ===== Context Aware Service List =====
,W/CAE     (  839): unregisterCallback(ContextAwareService.java:234) - [unregi 02] Mutex is unlocked for AUTO_ROTATION
,D/SContextService(  839): removeSContextService() : service = Auto Rotation
,D/SContextService(  839): ===== SContext Service List =====
D/SContextManager(  839):   .unregisterListener : listener = com.android.internal.policy.impl.WindowOrientationListener$SContextListenerImpl@19a6e4b5, service=Auto Rotation
,D/KeyguardViewMediator( 1172): onScreenTurnedOff(3)
,I/KeyguardEffectViewController( 1172): *** KeyguardEffectView getInstanceIfExists ***
D/KeyguardEffectViewController( 1172): changeWallpaperByScreenOff()
,D/KeyguardViewMediator( 1172): notifyScreenOffLocked
,D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1172): value : false
D/KeyguardViewMediator( 1172): timeout : 5000
,D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1172): value : false
,D/DisplayPowerController(  839): ColorFade: onAnimationStart
,D/DisplayPowerController(  839): getFinalBrightness : 41 -> 0
,D/RampAnimator(  839): mAnimationCallback timeDelta calculate error!! -0.002368127
,D/lights  (  839): lcd : 7 +
,I/SQLiteSecureOpenHelper( 3523): getWritableDatabase(pwd)
I/SQLiteSecureOpenHelper( 3523): getDatabaseLocked(b,b,pwd)...
,D/lights  (  839): lcd : 7 -
,D/lights  (  839): lcd : 0 +
,D/DisplayPowerController(  839): getFinalBrightness : 41 -> 0
,D/KeyguardViewMediator( 1172): setting alarm to turn off keyguard, seq = 2
,D/KeyguardViewMediator( 1172): handleNotifyScreenOff
,D/lights  (  839): lcd : 0 -
,D/StatusBar.NetworkController( 1172): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02012b/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020466/com.android.systemui:drawable/stat_sys_signal_inout mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
D/StatusBar.NetworkController( 1172): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1172): applyOpen
,D/StatusBar.NetworkController( 1172): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1172): applyOpen
D/StatusBar.NetworkController( 1172): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1172): applyOpen
D/StatusBar.NetworkController( 1172): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1172): applyOpen
,D/LightsService(  839): [api] [SvcLED] setFlashing :: id = 3, color = 0, mode = 14, onMS = 0, offMS = 0,  (uid: 1000 pid: 839) 
,D/LightsService(  839): [SvcLED] setSvcLedStateLocked:: SvcLEDState : 0x0 -> 0x40 | SvcLED(id=3) set On
,D/LightsService(  839): [SvcLED]  onSensorChanged::light value = 25
,D/SensorManager(  839): registerListener :: 6, TMG399X RGB Sensor, 200000, 0,  
,D/BatteryService(  839): turn on LED for fully charged
D/SensorManager(  839): unregisterListener ::   
D/lights  (  839): led_pattern : 5 +
,D/lights  (  839): led_pattern : 5 -
D/LightsService(  839): [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=3) maintains its priority right
,I/CAE     (  839): handleMessage(CaPowerManager.java:182) - AP_SLEEP
I/CAE     (  839): updateApPowerStatus(SensorHubParserProvider.java:421) - AP_SLEEP
,I/CAE     (  839): sendCmdToSensorHub(SensorHubCommManager.java:144) - -76, 13, -46, 0,
D/SensorHubManager(  839): SendSensorHubData: send data = -76, 13, -46, 0
D/Sensorhubs(  298): sendContextData: -76, 13, -46, 0
,I/CAE     (  839): sendCmdToSensorHub(SensorHubCommManager.java:144) - -63, 14, 13, 9, 3,
,D/SensorHubManager(  839): SendSensorHubData: send data = -63, 14, 13, 9, 3
D/Sensorhubs(  298): sendContextData: -63, 14, 13, 9, 3
,D/MotionRecognitionService(  839):   mReceiver.onReceive : ACTION_SCREEN_OFF
,E/MotionRecognitionService(  839):  handler : SCREEN_OFF end 
,D/NotificationService(  839): ACTION_SCREEN_OFF
D/LightsService(  839): [api] [SvcLED] setFlashing :: id = 4, color = ffffffff, mode = 12, onMS = 500, offMS = 2000,  (uid: 1000 pid: 839) 
D/LightsService(  839): [SvcLED] setSvcLedStateLocked:: SvcLEDState : 0x40 -> 0x42 | SvcLED(id=4) set On
,D/LightsService(  839): [SvcLED]  onSensorChanged::light value = 25
,D/WifiStateMachine(  839): backgroundScan enabled=false startBackgroundScanIfNeeded:false
E/WifiStateMachine(  839): handleScreenStateChanged Exit: false
,E/WifiStateMachine(  839): setSuspendOptimizationsNative: 4 true -want true stack:setSuspendOptimizationsNative - access$16800 - processMessage - processMsg
,E/WifiStateMachine(  839): setSuspendOptimizationsNative do it 4 true stack:setSuspendOptimizationsNative - access$16800 - processMessage - processMsg
E/native  (  839): do suspend true
,D/SensorManager(  839): registerListener :: 6, TMG399X RGB Sensor, 200000, 0,  
D/SensorManager(  839): unregisterListener ::   
D/LightsService(  839): [SvcLED]  setSvcLedLightLocked :: priority changed! SvcLED(id=3) OUT; SvcLED(id=4) IN
,D/audio_hw_primary(  289): adev_set_parameters: enter: screen_state=off
,V/voice   (  289): voice_set_parameters: enter: screen_state=off
V/voice   (  289): voice_set_parameters: exit with code(-2)
V/msm8974_platform(  289): platform_set_parameters: enter: screen_state=off
V/msm8974_platform(  289): platform_set_parameters: exit with code(-2)
D/audio_hw_hfp(  289): audio_extn_hfp_set_parameters: enter
V/audio_hw_primary(  289): adev_set_parameters: exit
,I/SecExternalDisplayIntents_Java(  839): Intent Recieved ..  -android.intent.action.SCREEN_OFFBroadCast Map value - 18
,D/IpRemoteDisplayController(  839): intent received android.intent.action.SCREEN_OFF
,D/IpRemoteDisplayController(  839): Bridge Server is not available
,D/VolumePanel( 1172): mCoverBroadcastReceiver: Screen OFF start
D/VolumePanel( 1172): mCoverBroadcastReceiver : call onDismissSafeVolumeWarning() #1
,D/VolumePanel( 1172): mCoverBroadcastReceiver: Screen OFF end
D/VolumePanel( 1172): mCoverBroadcastReceiver: onReceive() end : intent=Intent { act=android.intent.action.SCREEN_OFF flg=0x50000010 (has extras) }
,D/PersonaManagerService(  839): ACTION_SCREEN_OFF onReceive
D/PersonaManagerServiceHandler(  839): MSG_ACTION_SCREEN_OFF called
,D/NfcService( 1453): call the applyRotuiing
,D/STATUSBAR-PhoneStatusBar( 1172):      ACTION_SCREEN_OFF is finished!!!! 
,E/StatusBar( 1172): onReceive : Intent.ACTION_SCREEN_OFF
D/Recents_AlternateRecentsComponent( 1172): dismissHelpPopup 
,D/accuweather( 2115): [KK AccuPhone]>>> SWW:66 [0:0] action : androidintentactionSCREEN_OFF
D/accuweather( 2115): [KK AccuPhone]>>> SWW:467 [0:0] stopRefreshIcon : 1
,D/accuweather( 2115): [KK AccuPhone]>>> SWW:364 [0:0] getWeatherRenderer : 1
,D/DisplayPowerState(  839): !@ ColorFade entry
,D/DisplayPowerController(  839): ColorFade: onAnimationEnd
,D/AutomaticBrightnessController(  839): [DAB] setLightSensorEnabled : Send Update unregisterListener mLightSensor
,I/AutomaticBrightnessController(  839): [DAB] fileWriteInt : /sys/class/tcon/tcon/auto_br  value : 0
D/AutomaticBrightnessController(  839): [DAB] setLightSensorEnabled : unregisterListener mLightSensor
E/LightSensor(  839): Light old sensor_state 8705, new sensor_state : 8193 en : 0
I/AutomaticBrightnessController(  839): [DAB] fileWriteInt : /sys/class/backlight/panel/auto_brightness  value : 0
,D/SensorManager(  839): unregisterListener ::   
E/Sensors (  839): Acc old sensor_state 8193, new sensor_state : 8192 en : 0
,D/SensorManager(  839): unregisterListener ::   
,D/ConnectivityService(  839): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
,I/SystemBroadcastReceiver( 7177): [#DCM#] [DCM_Performance] onReceive completed in time  310 microsec. 
D/DisplayPowerController(  839): getFinalBrightness : 0 -> 0
,I/SystemBroadcastReceiver( 7177): [#DCM#] Calling notifyListeners. 
I/DCMPolicyManager( 7177): [#DCM#] onReceive action = EVENT_SCREEN_OFF
D/DisplayPowerController(  839): getFinalBrightness : 0 -> 0
I/DCMController( 7177): [#DCM#] onIntentReceived eventid = EVENT_SCREEN_OFF
,I/DisplayManagerService(  839): Display device changed: DisplayDeviceInfo{"Built-in Screen": 1080 x 1920, 60.0 fps, supportedRefreshRates [60.0], density 480, 422.03 x 424.069 dpi, appVsyncOff 0, presDeadline 17666667, touch INTERNAL, rotation 0, type BUILT_IN, state OFF, FLAG_DEFAULT_DISPLAY, FLAG_ROTATES_WITH_CONTENT, FLAG_SECURE, FLAG_SUPPORTS_PROTECTED_BUFFERS}
D/SurfaceFlinger(  249): Set power mode=0, type=0 flinger=0xb6a62000
D/qdhwcomposer(  249): hwc_blank: Blanking display: 0
,V/ActivityManager(  839): Display changed displayId=0
,D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1172): value : false
,W/ActivityManager(  839): getTasks: caller 10086 does not hold GET_TASKS; limiting output
,D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
,W/ActivityManager(  839): getTasks: caller 10086 does not hold GET_TASKS; limiting output
,D/StatusBar.NetworkController( 1172): onSignalStrengthsChanged signalStrength=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte level=0
D/StatusBar.NetworkController( 1172): updateTelephonySignalStrength: hasService=false ss=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte
D/StatusBar.NetworkController( 1172): updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal
D/StatusBar.NetworkController( 1172): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02012b/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020466/com.android.systemui:drawable/stat_sys_signal_inout mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
,D/PowerManagerService(  839): [PWL] sb release: PowerManagerService.Broadcasts
,D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
,D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
,D/SSRM:m  (  839): SIOP:: AP = 340, PST = 394, CUR = 300
,D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
,I/rmt_storage(  270): rmt_storage_connect_cb: clnt_h=0x5 conn_h=0xb6c01090
,I/rmt_storage(  270): rmt_storage_rw_iovec_cb: /boot/modem_fs1: clnt_h=0x1: req_h=0xa msg_id=3: R/W request received
I/rmt_storage(  270): wakelock acquired: 1, error no: 42
,I/rmt_storage(  270): rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1 Unblock worker thread (th_id: -1228406656)
,I/rmt_storage(  270): rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1: req_h=0xa msg_id=3: Bytes written = 1572864
I/rmt_storage(  270): rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1: req_h=0xa msg_id=3: Send response: res=0 err=0
,I/rmt_storage(  270): rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1 About to block rmt_storage client thread (th_id: -1228406656) wakelock released: 1, error no: 22
I/rmt_storage(  270): 
,I/rmt_storage(  270): rmt_storage_disconnect_cb: clnt_h=0x0x5 conn_h=0x0xb6c01090
,I/qdhwcomposer(  249): handle_blank_event: dpy:0 panel power state: 0
D/qdhwcomposer(  249): hwc_blank: Done blanking display: 0
,D/SurfaceControl(  839): Excessive delay in setPowerMode(): 276ms
D/PowerManagerService(  839): !@[s] blankAllDisplays() : blankAllDisplaysFromPowerManage
D/MISC PowerHAL(  839): sysfs_write +: /sys/class/power_supply/battery/lcd: 0
D/MISC PowerHAL(  839): sysfs_write -: /sys/class/power_supply/battery/lcd: 0
,I/QCOM PowerHAL(  839): Got set_interactive hint
,I/PowerManagerService(  839): [PWL] Off : 0s ago
I/PowerManagerService(  839): [PWL]   PowerManagerService.Display: ref count=2
I/PowerManagerService(  839): [PWL]     mDisplayReady : false
,D/DisplayPowerController(  839): getFinalBrightness : 0 -> 0
D/PowerManagerService(  839): [s] DisplayPowerCallbacks : onStateChanged()
,D/PowerManagerService(  839): [PWL] sb release: PowerManagerService.Display
,I/ServiceManager(  341): Waiting for service AtCmdFwd...
,I/ServiceManager(  341): Waiting for service AtCmdFwd...
,E/SMD     (  280): DCD ON
,I/ServiceManager(  341): Waiting for service AtCmdFwd...
,V/AlarmManager(  839): waitForAlarm result :4
,D/BatteryService(  839): level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 297, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  839): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
D/BatteryService(  839): stay LED for fully charged
D/BatteryService(  839): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  839):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  839): Plugged
I/MotionRecognitionService(  839): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1172): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1172): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1172):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3231): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3231): Disconnected process message: 10
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/GLSActivity( 1661): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1661): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
,I/GLSUser ( 1661): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1661): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1661): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/ServiceManager(  341): Waiting for service AtCmdFwd...
,V/GLSActivity( 1661): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/Finsky  ( 6694): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,D/Finsky  ( 6694): [1] 5.onFinished: Installation state replication failed.
D/Finsky  ( 6694): [1] 5.onFinished: Scheduling replication attempt 4.
,I/ServiceManager(  341): Waiting for service AtCmdFwd...
,V/AlarmManager(  839): waitForAlarm result :4
,D/KeyguardViewMediator( 1172): received DELAYED_KEYGUARD_ACTION with seq = 2, mDelayedShowingSequence = 2
,D/PersonaManager( 1172): isKioskContainerExistOnDevice
,D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1172): value : false
,D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1172): value : false
,D/KeyguardViewMediator( 1172): doKeyguard: not showing because lockscreen is off
,I/PowerManagerService(  839): [PWL] Off : 5s ago
,E/SMD     (  280): DCD ON
,W/Atfwd_Sendcmd(  341): AtCmdFwd service not published, waiting... retryCnt : 3
,E/SMD     (  280): DCD ON
,D/SSRM:m  (  839): SIOP:: AP = 330, PST = 381, CUR = 300,
,E/SMD     (  280): DCD ON
,E/SMD     (  280): DCD ON
,W/ContextImpl(  839): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/PowerManagerService(  839): [PWL] Off : 15s ago
,E/SMD     (  280): DCD ON
,D/SSRM:m  (  839): SIOP:: AP = 320, PST = 371, CUR = 300
,E/SMD     (  280): DCD ON
,I/ServiceManager(  341): Waiting for service AtCmdFwd...
,V/AlarmManager(  839): waitForAlarm result :4
,D/ConnectivityService(  839): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  839): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/GLSUser ( 1661): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,I/GLSUser ( 1661): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1661): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1661): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1661): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/BitmapFactory( 1661): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  839): uri = 14 selection = getSealedState
D/SecContentProvider2(  839): mCursor = null
,D/SecContentProvider2(  839): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  839): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
V/ApplicationPolicy(  839): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,E/HttpOperation( 6664): [kfu{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
E/HttpOperation( 6664): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 6664): 	at kfv.a(PG:65)
E/HttpOperation( 6664): 	at kff.u(PG:385)
E/HttpOperation( 6664): 	at kfb.a(PG:29)
E/HttpOperation( 6664): 	at kff.l(PG:132)
E/HttpOperation( 6664): 	at dsf.a(PG:807)
E/HttpOperation( 6664): 	at fhk.a(PG:1126)
E/HttpOperation( 6664): 	at fhk.a(PG:908)
E/HttpOperation( 6664): 	at fhk.onPerformSync(PG:636)
E/HttpOperation( 6664): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/HttpOperation( 6664): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/HttpOperation( 6664): 	at ihi.a(PG:22)
E/HttpOperation( 6664): 	at kft.a(PG:91)
E/HttpOperation( 6664): 	at kfv.a(PG:62)
E/HttpOperation( 6664): 	... 8 more
E/HttpOperation( 6664): Caused by: gdi: User intervention required. Notification has been pushed.
E/HttpOperation( 6664): 	at gde.c(Unknown Source)
E/HttpOperation( 6664): 	at gde.b(Unknown Source)
E/HttpOperation( 6664): 	at ihi.a(PG:19)
E/HttpOperation( 6664): 	... 10 more
,D/StatusBar( 1172): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,I/PhoneStatusBar( 1172): Icon Only
D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
,D/PanelView( 1172): There is/are notification(s) 
D/PanelView( 1172): There is/are notification(s) 
,I/GLSUser ( 1661): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,I/GLSUser ( 1661): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1661): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1661): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1661): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/BitmapFactory( 1661): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  839): uri = 14 selection = getSealedState
,D/SecContentProvider2(  839): mCursor = null
,D/SecContentProvider2(  839): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  839): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
V/ApplicationPolicy(  839): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/StatusBar( 1172): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,I/PhoneStatusBar( 1172): Icon Only
,D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
D/PanelView( 1172): There is/are notification(s) 
,D/PanelView( 1172): There is/are notification(s) 
,E/HttpOperation( 6664): [getmobileexperiments] Unexpected exception
E/HttpOperation( 6664): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 6664): 	at kfv.a(PG:65)
E/HttpOperation( 6664): 	at kff.u(PG:385)
E/HttpOperation( 6664): 	at kfb.a(PG:29)
E/HttpOperation( 6664): 	at kff.l(PG:132)
E/HttpOperation( 6664): 	at ieo.a(PG:43)
E/HttpOperation( 6664): 	at iep.a(PG:93)
E/HttpOperation( 6664): 	at fhn.a(PG:59)
E/HttpOperation( 6664): 	at lex.a(PG:85)
E/HttpOperation( 6664): 	at lex.b(PG:132)
E/HttpOperation( 6664): 	at fhk.a(PG:1146)
E/HttpOperation( 6664): 	at fhk.a(PG:908)
E/HttpOperation( 6664): 	at fhk.onPerformSync(PG:636)
E/HttpOperation( 6664): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/HttpOperation( 6664): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/HttpOperation( 6664): 	at ihi.a(PG:22)
E/HttpOperation( 6664): 	at kft.a(PG:91)
E/HttpOperation( 6664): 	at kfv.a(PG:62)
E/HttpOperation( 6664): 	... 12 more
E/HttpOperation( 6664): Caused by: gdi: User intervention required. Notification has been pushed.
E/HttpOperation( 6664): 	at gde.c(Unknown Source)
E/HttpOperation( 6664): 	at gde.b(Unknown Source)
E/HttpOperation( 6664): 	at ihi.a(PG:19)
E/HttpOperation( 6664): 	... 14 more
,E/ExperimentLoader( 6664): [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 6664): java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 6664): 	at kfv.a(PG:65)
E/ExperimentLoader( 6664): 	at kff.u(PG:385)
E/ExperimentLoader( 6664): 	at kfb.a(PG:29)
E/ExperimentLoader( 6664): 	at kff.l(PG:132)
E/ExperimentLoader( 6664): 	at ieo.a(PG:43)
E/ExperimentLoader( 6664): 	at iep.a(PG:93)
E/ExperimentLoader( 6664): 	at fhn.a(PG:59)
E/ExperimentLoader( 6664): 	at lex.a(PG:85)
E/ExperimentLoader( 6664): 	at lex.b(PG:132)
E/ExperimentLoader( 6664): 	at fhk.a(PG:1146)
E/ExperimentLoader( 6664): 	at fhk.a(PG:908)
E/ExperimentLoader( 6664): 	at fhk.onPerformSync(PG:636)
E/ExperimentLoader( 6664): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/ExperimentLoader( 6664): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/ExperimentLoader( 6664): 	at ihi.a(PG:22)
E/ExperimentLoader( 6664): 	at kft.a(PG:91)
E/ExperimentLoader( 6664): 	at kfv.a(PG:62)
E/ExperimentLoader( 6664): 	... 12 more
E/ExperimentLoader( 6664): Caused by: gdi: User intervention required. Notification has been pushed.
E/ExperimentLoader( 6664): 	at gde.c(Unknown Source)
E/ExperimentLoader( 6664): 	at gde.b(Unknown Source)
E/ExperimentLoader( 6664): 	at ihi.a(PG:19)
E/ExperimentLoader( 6664): 	... 14 more
,I/ServiceManager(  341): Waiting for service AtCmdFwd...
,E/SQLiteLog( 1661): (10) POSIX Error : 11 SQLite Error : 3850
,I/GLSUser ( 1661): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,I/GLSUser ( 1661): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1661): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1661): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1661): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/BitmapFactory( 1661): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  839): uri = 14 selection = getSealedState
,D/SecContentProvider2(  839): mCursor = null
D/SecContentProvider2(  839): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  839): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
V/ApplicationPolicy(  839): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/StatusBar( 1172): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,I/PhoneStatusBar( 1172): Icon Only
,D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
,D/PanelView( 1172): There is/are notification(s) 
,D/PanelView( 1172): There is/are notification(s) 
,E/HttpOperation( 6664): [getaccountstatus] Unexpected exception
E/HttpOperation( 6664): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 6664): 	at kfv.a(PG:65)
E/HttpOperation( 6664): 	at kff.u(PG:385)
E/HttpOperation( 6664): 	at kfb.a(PG:29)
E/HttpOperation( 6664): 	at ixd.a(PG:248)
E/HttpOperation( 6664): 	at ixd.b(PG:206)
E/HttpOperation( 6664): 	at ixd.a(PG:175)
E/HttpOperation( 6664): 	at fig.a(PG:78)
E/HttpOperation( 6664): 	at lex.a(PG:85)
E/HttpOperation( 6664): 	at lex.b(PG:132)
E/HttpOperation( 6664): 	at fhk.a(PG:1146)
E/HttpOperation( 6664): 	at fhk.a(PG:908)
E/HttpOperation( 6664): 	at fhk.onPerformSync(PG:636)
E/HttpOperation( 6664): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/HttpOperation( 6664): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/HttpOperation( 6664): 	at ihi.a(PG:22)
E/HttpOperation( 6664): 	at kft.a(PG:91)
E/HttpOperation( 6664): 	at kfv.a(PG:62)
E/HttpOperation( 6664): 	... 12 more
E/HttpOperation( 6664): Caused by: gdi: User intervention required. Notification has been pushed.
E/HttpOperation( 6664): 	at gde.c(Unknown Source)
E/HttpOperation( 6664): 	at gde.b(Unknown Source)
E/HttpOperation( 6664): 	at ihi.a(PG:19)
E/HttpOperation( 6664): 	... 14 more
,E/EsSyncAdapterService( 6664): Sync failure
E/EsSyncAdapterService( 6664): java.io.IOException: Rpc failed
E/EsSyncAdapterService( 6664): 	at ixd.a(PG:348)
E/EsSyncAdapterService( 6664): 	at ixd.a(PG:248)
E/EsSyncAdapterService( 6664): 	at ixd.b(PG:206)
E/EsSyncAdapterService( 6664): 	at ixd.a(PG:175)
E/EsSyncAdapterService( 6664): 	at fig.a(PG:78)
E/EsSyncAdapterService( 6664): 	at lex.a(PG:85)
E/EsSyncAdapterService( 6664): 	at lex.b(PG:132)
E/EsSyncAdapterService( 6664): 	at fhk.a(PG:1146)
E/EsSyncAdapterService( 6664): 	at fhk.a(PG:908)
E/EsSyncAdapterService( 6664): 	at fhk.onPerformSync(PG:636)
E/EsSyncAdapterService( 6664): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/EsSyncAdapterService( 6664): Caused by: java.io.IOException: Cannot obtain authentication token
E/EsSyncAdapterService( 6664): 	at kfv.a(PG:65)
E/EsSyncAdapterService( 6664): 	at kff.u(PG:385)
E/EsSyncAdapterService( 6664): 	at kfb.a(PG:29)
E/EsSyncAdapterService( 6664): 	... 10 more
E/EsSyncAdapterService( 6664): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/EsSyncAdapterService( 6664): 	at ihi.a(PG:22)
E/EsSyncAdapterService( 6664): 	at kft.a(PG:91)
E/EsSyncAdapterService( 6664): 	at kfv.a(PG:62)
E/EsSyncAdapterService( 6664): 	... 12 more
E/EsSyncAdapterService( 6664): Caused by: gdi: User intervention required. Notification has been pushed.
E/EsSyncAdapterService( 6664): 	at gde.c(Unknown Source)
E/EsSyncAdapterService( 6664): 	at gde.b(Unknown Source)
E/EsSyncAdapterService( 6664): 	at ihi.a(PG:19)
E/EsSyncAdapterService( 6664): 	... 14 more
,D/ConnectivityService(  839): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SyncManager(  839): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, SERVER, currentRunTime 157979, reason: 10135, SyncResult: stats [ numIoExceptions: 2]
,D/ConnectivityService(  839): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  839): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/art     (  839): Explicit concurrent mark sweep GC freed 75240(4MB) AllocSpace objects, 30(3MB) LOS objects, 30% free, 36MB/52MB, paused 3.852ms total 320.687ms
,D/SecContentProvider2(  839): uri = 11 selection = getMyKnoxAdmin
D/SecContentProvider2(  839): mCursor = null
,E/SQLiteLog( 1661): (10) POSIX Error : 11 SQLite Error : 3850
,I/ServiceManager(  341): Waiting for service AtCmdFwd...
,E/SMD     (  280): DCD ON
,I/ServiceManager(  341): Waiting for service AtCmdFwd...
,V/AlarmManager(  839): waitForAlarm result :4
,V/GLSActivity( 1661): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1661): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
,I/GLSUser ( 1661): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1661): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1661): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1661): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/Finsky  ( 6694): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,D/Finsky  ( 6694): [1] 5.onFinished: Installation state replication failed.
D/Finsky  ( 6694): [1] 5.onFinished: Scheduling replication attempt 5.
,I/ServiceManager(  341): Waiting for service AtCmdFwd...
,W/Atfwd_Sendcmd(  341): AtCmdFwd service not published, waiting... retryCnt : 4
,E/SMD     (  280): DCD ON
,E/Watchdog(  839): !@Sync 5
,E/SMD     (  280): DCD ON
,D/SSRM:m  (  839): SIOP:: AP = 320, PST = 361, CUR = 300
,I/PowerManagerService(  839): [PWL] Off : 30s ago
,D/BatteryService(  839): level:100, scale:100, status:5, health:2, present:true, voltage: 4382, temperature: 297, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  839): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  839): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  839):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  839): Plugged
,I/MotionRecognitionService(  839): setPowerConnected  = true
,D/BatteryService(  839): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1172): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1172): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1172):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3231): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3231): Disconnected process message: 10
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  280): DCD ON
,W/ContextImpl(  839): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  280): DCD ON
,E/SMD     (  280): DCD ON
,D/SSRM:m  (  839): SIOP:: AP = 320, PST = 352, CUR = 300
,E/SMD     (  280): DCD ON
,V/AlarmManager(  839): waitForAlarm result :4
,D/BatteryService(  839): level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 297, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  839): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
D/BatteryService(  839): stay LED for fully charged
D/BatteryService(  839): Sending ACTION_BATTERY_CHANGED.
,D/ConnectivityService(  839): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/MotionRecognitionService(  839):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  839): Plugged
I/MotionRecognitionService(  839): setPowerConnected  = true
,D/ConnectivityService(  839): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/KeyguardUpdateMonitor( 1172): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1172): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1172):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3231): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3231): Disconnected process message: 10
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/GLSActivity( 1661): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/SMD     (  280): DCD ON
,D/ConnectivityService(  839): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  839): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/VacuumService( 1661): Vacuum at: now=1449752988246 tag=VacuumService
,I/GoogleURLConnFactory( 1661): Using platform SSLCertificateSocketFactory
,D/ConnectivityService(  839): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/GLSUser ( 1661): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
,I/GLSUser ( 1661): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1661): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1661): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1661): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/BitmapFactory( 1661): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  839): uri = 14 selection = getSealedState
D/SecContentProvider2(  839): mCursor = null
,D/SecContentProvider2(  839): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  839): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
V/ApplicationPolicy(  839): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/StatusBar( 1172): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,E/Uploader( 1661): Failed to get auth token: User intervention required. Notification has been pushed.
E/Uploader( 1661): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
E/Uploader( 1661): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
E/Uploader( 1661): 	at com.google.android.gms.auth.p.d(SourceFile:599)
E/Uploader( 1661): 	at com.google.android.gms.auth.p.c(SourceFile:550)
E/Uploader( 1661): 	at com.google.android.gms.auth.p.b(SourceFile:477)
E/Uploader( 1661): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:508)
E/Uploader( 1661): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:337)
E/Uploader( 1661): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:263)
E/Uploader( 1661): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:235)
E/Uploader( 1661): 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:125)
E/Uploader( 1661): 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:78)
E/Uploader( 1661): 	at com.google.android.gms.gcm.am.run(SourceFile:135)
,I/PhoneStatusBar( 1172): Icon Only
D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1172): value : false
,D/PanelView( 1172): There is/are notification(s) 
,D/PanelView( 1172): There is/are notification(s) 
,I/System.out( 1661): (HTTPLog)-Static: SBServiceAPI: getService class android.os.ServiceManager
I/System.out( 1661): (HTTPLog)-Static: isShipBuild true
,I/System.out( 1661): (HTTPLog)-Thread-194-86074229: SmartBonding Enabling is true, SHIP_BUILD is true, log to file is false, DBG is false
,I/qtaguid ( 1661): Tagging socket 59 with tag 120100000000{4609,0} uid -1, pid: 1661, getuid(): 10012
,V/GLSActivity( 1661): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/qtaguid ( 1661): Tagging socket 63 with tag 120100000000{4609,0} uid -1, pid: 1661, getuid(): 10012
,I/GLSUser ( 1661): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
,I/GLSUser ( 1661): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1661): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1661): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1661): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/Finsky  ( 6694): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,D/Finsky  ( 6694): [1] 5.onFinished: Installation state replication failed.
,D/Finsky  ( 6694): [1] 5.onFinished: Giving up after 6 failures.
,W/Uploader( 1661): No account for auth token provided
,I/qtaguid ( 1661): Tagging socket 59 with tag 120100000000{4609,0} uid -1, pid: 1661, getuid(): 10012
,W/Uploader( 1661): No account for auth token provided
,I/qtaguid ( 1661): Tagging socket 59 with tag 120100000000{4609,0} uid -1, pid: 1661, getuid(): 10012
,I/ServiceManager(  341): Waiting for service AtCmdFwd...
,W/Uploader( 1661): No account for auth token provided
,I/qtaguid ( 1661): Tagging socket 59 with tag 120100000000{4609,0} uid -1, pid: 1661, getuid(): 10012
,W/Uploader( 1661): No account for auth token provided
,I/qtaguid ( 1661): Tagging socket 59 with tag 120100000000{4609,0} uid -1, pid: 1661, getuid(): 10012
,W/Uploader( 1661):  no longer exists, so no auth token.
,I/qtaguid ( 1661): Tagging socket 59 with tag 120100000000{4609,0} uid -1, pid: 1661, getuid(): 10012
,E/SQLiteLog( 1661): (10) POSIX Error : 11 SQLite Error : 3850
,D/ConnectivityService(  839): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/ServiceManager(  341): Waiting for service AtCmdFwd...
,E/SMD     (  280): DCD ON
,I/ServiceManager(  341): Waiting for service AtCmdFwd...
,I/ServiceManager(  341): Waiting for service AtCmdFwd...
,I/ServiceManager(  341): Waiting for service AtCmdFwd...
,I/PowerManagerService(  839): [PWL] Off : 50s ago
,D/SSRM:m  (  839): SIOP:: AP = 310, PST = 345, CUR = 300
,E/SMD     (  280): DCD ON
,W/Atfwd_Sendcmd(  341): AtCmdFwd service not published, waiting... retryCnt : 5
,V/AlarmManager(  839): waitForAlarm result :4
,D/ConnectivityService(  839): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  839): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/BooksSync( 7492): Starting books sync, d
,D/ConnectivityService(  839): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,V/GLSActivity( 1661): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1661): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
,I/GLSUser ( 1661): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1661): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1661): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1661): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ResourcesManager( 1661): creating new AssetManager and set to /system/app/Books/Books.apk
,V/BitmapFactory( 1661): DecodeImagePath(decodeResourceStream3) : res/mipmap-xxhdpi-v4/ic_launcher_play_books.png
,V/BitmapFactory( 1661): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  839): uri = 14 selection = getSealedState
,D/SecContentProvider2(  839): mCursor = null
D/SecContentProvider2(  839): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  839): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy(  839): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/StatusBar( 1172): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,I/PhoneStatusBar( 1172): Icon Only
,D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
D/PanelView( 1172): There is/are notification(s) 
D/PanelView( 1172): There is/are notification(s) 
,W/GLSActivity( 1661): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1661): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1661): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1661): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1661): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1661): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1661): 	at android.os.Binder.execTransact(Binder.java:446)
,E/BooksAccountManager( 7492): Authentication error
E/BooksAccountManager( 7492): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 7492): android.accounts.AccountManager.convertErrorToException(AccountManager.java:1893)
,E/HttpHelper( 7492): null auth token
,I/qtaguid ( 7492): Tagging socket 34 with tag 10000000000{256,0} uid -1, pid: 7492, getuid(): 10082
,I/qtaguid ( 7492): Tagging socket 34 with tag 10000000000{256,0} uid -1, pid: 7492, getuid(): 10082
,I/qtaguid ( 7492): Untagging socket 34
,W/ApiaryClient( 7492): Error response from books API: {
W/ApiaryClient( 7492):  "error": {
W/ApiaryClient( 7492):   "errors": [
W/ApiaryClient( 7492):    {
W/ApiaryClient( 7492):     "domain": "global",
W/ApiaryClient( 7492):     "reason": "required",
W/ApiaryClient( 7492):     "message": "Login Required",
W/ApiaryClient( 7492):     "locationType": "header",
W/ApiaryClient( 7492):     "location": "Authorization"
W/ApiaryClient( 7492):    }
W/ApiaryClient( 7492):   ],
W/ApiaryClient( 7492):   "code": 401,
W/ApiaryClient( 7492):   "message": "Login Required"
W/ApiaryClient( 7492):  }
W/ApiaryClient( 7492): }
,W/ApiaryClient( 7492): errCount = 1: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 7492): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3DS0HXd4TFLU4&nonce=188454884305616113&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 7492): Headers suppressed
,D/ConnectivityService(  839): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/art     ( 1661): Explicit concurrent mark sweep GC freed 61665(3MB) AllocSpace objects, 55(3MB) LOS objects, 40% free, 18MB/30MB, paused 988us total 104.006ms
,V/GLSActivity( 1661): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1661): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
,I/GLSUser ( 1661): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1661): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1661): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1661): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ResourcesManager( 1661): creating new AssetManager and set to /system/app/Books/Books.apk
,V/BitmapFactory( 1661): DecodeImagePath(decodeResourceStream3) : res/mipmap-xxhdpi-v4/ic_launcher_play_books.png
,V/BitmapFactory( 1661): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  839): uri = 14 selection = getSealedState
D/SecContentProvider2(  839): mCursor = null
,D/SecContentProvider2(  839): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  839): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy(  839): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,W/GLSActivity( 1661): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1661): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1661): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1661): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1661): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1661): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1661): 	at android.os.Binder.execTransact(Binder.java:446)
,E/BooksAccountManager( 7492): Authentication error
E/BooksAccountManager( 7492): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 7492): android.accounts.AccountManager.convertErrorToException(AccountManager.java:1893)
,D/StatusBar( 1172): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
E/HttpHelper( 7492): null auth token
,I/qtaguid ( 7492): Tagging socket 34 with tag 10000000000{256,0} uid -1, pid: 7492, getuid(): 10082
,I/qtaguid ( 7492): Tagging socket 39 with tag 10000000000{256,0} uid -1, pid: 7492, getuid(): 10082
,I/PhoneStatusBar( 1172): Icon Only
,D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
D/PanelView( 1172): There is/are notification(s) 
D/PanelView( 1172): There is/are notification(s) 
,I/qtaguid ( 7492): Untagging socket 34
,W/ApiaryClient( 7492): Error response from books API: {
W/ApiaryClient( 7492):  "error": {
W/ApiaryClient( 7492):   "errors": [
W/ApiaryClient( 7492):    {
W/ApiaryClient( 7492):     "domain": "global",
W/ApiaryClient( 7492):     "reason": "required",
W/ApiaryClient( 7492):     "message": "Login Required",
W/ApiaryClient( 7492):     "locationType": "header",
W/ApiaryClient( 7492):     "location": "Authorization"
W/ApiaryClient( 7492):    }
W/ApiaryClient( 7492):   ],
W/ApiaryClient( 7492):   "code": 401,
W/ApiaryClient( 7492):   "message": "Login Required"
W/ApiaryClient( 7492):  }
W/ApiaryClient( 7492): }
,W/ApiaryClient( 7492): errCount = 2: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 7492): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3DS0HXd4TFLU4&nonce=188454884305616113&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 7492): Headers suppressed
,D/ConnectivityService(  839): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/SMD     (  280): DCD ON
,V/GLSActivity( 1661): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1661): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
,I/GLSUser ( 1661): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1661): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1661): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1661): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/BitmapFactory( 1661): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  839): uri = 14 selection = getSealedState
,D/SecContentProvider2(  839): mCursor = null
D/SecContentProvider2(  839): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  839): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy(  839): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/StatusBar( 1172): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,I/PhoneStatusBar( 1172): Icon Only
,D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
D/PanelView( 1172): There is/are notification(s) 
,D/PanelView( 1172): There is/are notification(s) 
,W/GLSActivity( 1661): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1661): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1661): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1661): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1661): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1661): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1661): 	at android.os.Binder.execTransact(Binder.java:446)
,E/BooksAccountManager( 7492): Authentication error
E/BooksAccountManager( 7492): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 7492): android.accounts.AccountManager.convertErrorToException(AccountManager.java:1893)
,E/HttpHelper( 7492): null auth token
,I/qtaguid ( 7492): Tagging socket 34 with tag 10000000000{256,0} uid -1, pid: 7492, getuid(): 10082
,I/qtaguid ( 7492): Untagging socket 34
,W/ApiaryClient( 7492): Error response from books API: {
W/ApiaryClient( 7492):  "error": {
W/ApiaryClient( 7492):   "errors": [
W/ApiaryClient( 7492):    {
W/ApiaryClient( 7492):     "domain": "global",
W/ApiaryClient( 7492):     "reason": "required",
W/ApiaryClient( 7492):     "message": "Login Required",
W/ApiaryClient( 7492):     "locationType": "header",
W/ApiaryClient( 7492):     "location": "Authorization"
W/ApiaryClient( 7492):    }
W/ApiaryClient( 7492):   ],
W/ApiaryClient( 7492):   "code": 401,
W/ApiaryClient( 7492):   "message": "Login Required"
W/ApiaryClient( 7492):  }
W/ApiaryClient( 7492): }
,W/ApiaryClient( 7492): errCount = 3: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 7492): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3DS0HXd4TFLU4&nonce=188454884305616113&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 7492): Headers suppressed
,D/ConnectivityService(  839): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/BatteryService(  839): level:100, scale:100, status:5, health:2, present:true, voltage: 4386, temperature: 297, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  839): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  839): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  839):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  839): Plugged
,I/MotionRecognitionService(  839): setPowerConnected  = true
,D/BatteryService(  839): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1172): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1172): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1172):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3231): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3231): Disconnected process message: 10
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,W/ContextImpl(  839): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/BooksSync( 7492): Soft error
E/BooksSync( 7492): com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
E/BooksSync( 7492): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3DS0HXd4TFLU4&nonce=188454884305616113&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
E/BooksSync( 7492): Headers suppressed
E/BooksSync( 7492): 
E/BooksSync( 7492): com.google.android.apps.books.net.HttpHelper.wrapExceptionBasedOnStatus(HttpHelper.java:212)
,E/BooksSync( 7492): Sync error
E/BooksSync( 7492): com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
E/BooksSync( 7492): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3DS0HXd4TFLU4&nonce=188454884305616113&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
E/BooksSync( 7492): Headers suppressed
E/BooksSync( 7492): 
E/BooksSync( 7492): com.google.android.apps.books.net.HttpHelper.wrapExceptionBasedOnStatus(HttpHelper.java:212)
,I/BooksSync( 7492): Finished books sync
,D/ConnectivityService(  839): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SyncManager(  839): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 159300, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,D/ConnectivityService(  839): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SecContentProvider2(  839): uri = 11 selection = getMyKnoxAdmin
,D/SecContentProvider2(  839): mCursor = null
,D/ConnectivityService(  839): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  839): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/GLSUser ( 1661): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,I/GLSUser ( 1661): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1661): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1661): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1661): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ResourcesManager( 1661): creating new AssetManager and set to /system/app/PlusOne/PlusOne.apk
,V/BitmapFactory( 1661): DecodeImagePath(decodeResourceStream3) : res/mipmap-xxhdpi-v4/quantum_logo_google_plus_color_44in48.png
,V/BitmapFactory( 1661): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  839): uri = 14 selection = getSealedState
,D/SecContentProvider2(  839): mCursor = null
D/SecContentProvider2(  839): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  839): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy(  839): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/StatusBar( 1172): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,I/PhoneStatusBar( 1172): Icon Only
D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
D/PanelView( 1172): There is/are notification(s) 
D/PanelView( 1172): There is/are notification(s) 
,E/HttpOperation( 6664): [kfu{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
E/HttpOperation( 6664): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 6664): 	at kfv.a(PG:65)
E/HttpOperation( 6664): 	at kff.u(PG:385)
E/HttpOperation( 6664): 	at kfb.a(PG:29)
E/HttpOperation( 6664): 	at kff.l(PG:132)
E/HttpOperation( 6664): 	at dsf.a(PG:807)
E/HttpOperation( 6664): 	at fhk.a(PG:1126)
E/HttpOperation( 6664): 	at fhk.a(PG:908)
E/HttpOperation( 6664): 	at fhk.onPerformSync(PG:636)
E/HttpOperation( 6664): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/HttpOperation( 6664): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/HttpOperation( 6664): 	at ihi.a(PG:22)
E/HttpOperation( 6664): 	at kft.a(PG:91)
E/HttpOperation( 6664): 	at kfv.a(PG:62)
E/HttpOperation( 6664): 	... 8 more
E/HttpOperation( 6664): Caused by: gdi: User intervention required. Notification has been pushed.
E/HttpOperation( 6664): 	at gde.c(Unknown Source)
E/HttpOperation( 6664): 	at gde.b(Unknown Source)
E/HttpOperation( 6664): 	at ihi.a(PG:19)
E/HttpOperation( 6664): 	... 10 more
,I/GLSUser ( 1661): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,I/GLSUser ( 1661): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1661): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1661): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1661): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/BitmapFactory( 1661): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  839): uri = 14 selection = getSealedState
,D/SecContentProvider2(  839): mCursor = null
D/SecContentProvider2(  839): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  839): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
V/ApplicationPolicy(  839): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/StatusBar( 1172): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,I/PhoneStatusBar( 1172): Icon Only
D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
,D/PanelView( 1172): There is/are notification(s) 
D/PanelView( 1172): There is/are notification(s) 
,E/HttpOperation( 6664): [getmobileexperiments] Unexpected exception
E/HttpOperation( 6664): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 6664): 	at kfv.a(PG:65)
E/HttpOperation( 6664): 	at kff.u(PG:385)
E/HttpOperation( 6664): 	at kfb.a(PG:29)
E/HttpOperation( 6664): 	at kff.l(PG:132)
E/HttpOperation( 6664): 	at ieo.a(PG:43)
E/HttpOperation( 6664): 	at iep.a(PG:93)
E/HttpOperation( 6664): 	at fhn.a(PG:59)
E/HttpOperation( 6664): 	at lex.a(PG:85)
E/HttpOperation( 6664): 	at lex.b(PG:132)
E/HttpOperation( 6664): 	at fhk.a(PG:1146)
E/HttpOperation( 6664): 	at fhk.a(PG:908)
E/HttpOperation( 6664): 	at fhk.onPerformSync(PG:636)
E/HttpOperation( 6664): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/HttpOperation( 6664): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/HttpOperation( 6664): 	at ihi.a(PG:22)
E/HttpOperation( 6664): 	at kft.a(PG:91)
E/HttpOperation( 6664): 	at kfv.a(PG:62)
E/HttpOperation( 6664): 	... 12 more
E/HttpOperation( 6664): Caused by: gdi: User intervention required. Notification has been pushed.
E/HttpOperation( 6664): 	at gde.c(Unknown Source)
E/HttpOperation( 6664): 	at gde.b(Unknown Source)
E/HttpOperation( 6664): 	at ihi.a(PG:19)
E/HttpOperation( 6664): 	... 14 more
,E/ExperimentLoader( 6664): [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 6664): java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 6664): 	at kfv.a(PG:65)
E/ExperimentLoader( 6664): 	at kff.u(PG:385)
E/ExperimentLoader( 6664): 	at kfb.a(PG:29)
E/ExperimentLoader( 6664): 	at kff.l(PG:132)
E/ExperimentLoader( 6664): 	at ieo.a(PG:43)
E/ExperimentLoader( 6664): 	at iep.a(PG:93)
E/ExperimentLoader( 6664): 	at fhn.a(PG:59)
E/ExperimentLoader( 6664): 	at lex.a(PG:85)
E/ExperimentLoader( 6664): 	at lex.b(PG:132)
E/ExperimentLoader( 6664): 	at fhk.a(PG:1146)
E/ExperimentLoader( 6664): 	at fhk.a(PG:908)
E/ExperimentLoader( 6664): 	at fhk.onPerformSync(PG:636)
E/ExperimentLoader( 6664): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/ExperimentLoader( 6664): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/ExperimentLoader( 6664): 	at ihi.a(PG:22)
E/ExperimentLoader( 6664): 	at kft.a(PG:91)
E/ExperimentLoader( 6664): 	at kfv.a(PG:62)
E/ExperimentLoader( 6664): 	... 12 more
E/ExperimentLoader( 6664): Caused by: gdi: User intervention required. Notification has been pushed.
E/ExperimentLoader( 6664): 	at gde.c(Unknown Source)
E/ExperimentLoader( 6664): 	at gde.b(Unknown Source)
E/ExperimentLoader( 6664): 	at ihi.a(PG:19)
E/ExperimentLoader( 6664): 	... 14 more
,I/GLSUser ( 1661): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,I/GLSUser ( 1661): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1661): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1661): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1661): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/BitmapFactory( 1661): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  839): uri = 14 selection = getSealedState
,D/SecContentProvider2(  839): mCursor = null
,D/SecContentProvider2(  839): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  839): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
V/ApplicationPolicy(  839): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/StatusBar( 1172): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,E/HttpOperation( 6664): [getaccountstatus] Unexpected exception
E/HttpOperation( 6664): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 6664): 	at kfv.a(PG:65)
E/HttpOperation( 6664): 	at kff.u(PG:385)
E/HttpOperation( 6664): 	at kfb.a(PG:29)
E/HttpOperation( 6664): 	at ixd.a(PG:248)
E/HttpOperation( 6664): 	at ixd.b(PG:206)
E/HttpOperation( 6664): 	at ixd.a(PG:175)
E/HttpOperation( 6664): 	at fig.a(PG:78)
E/HttpOperation( 6664): 	at lex.a(PG:85)
E/HttpOperation( 6664): 	at lex.b(PG:132)
E/HttpOperation( 6664): 	at fhk.a(PG:1146)
E/HttpOperation( 6664): 	at fhk.a(PG:908)
E/HttpOperation( 6664): 	at fhk.onPerformSync(PG:636)
E/HttpOperation( 6664): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/HttpOperation( 6664): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/HttpOperation( 6664): 	at ihi.a(PG:22)
E/HttpOperation( 6664): 	at kft.a(PG:91)
E/HttpOperation( 6664): 	at kfv.a(PG:62)
E/HttpOperation( 6664): 	... 12 more
E/HttpOperation( 6664): Caused by: gdi: User intervention required. Notification has been pushed.
E/HttpOperation( 6664): 	at gde.c(Unknown Source)
E/HttpOperation( 6664): 	at gde.b(Unknown Source)
E/HttpOperation( 6664): 	at ihi.a(PG:19)
E/HttpOperation( 6664): 	... 14 more
,E/EsSyncAdapterService( 6664): Sync failure
E/EsSyncAdapterService( 6664): java.io.IOException: Rpc failed
E/EsSyncAdapterService( 6664): 	at ixd.a(PG:348)
E/EsSyncAdapterService( 6664): 	at ixd.a(PG:248)
E/EsSyncAdapterService( 6664): 	at ixd.b(PG:206)
E/EsSyncAdapterService( 6664): 	at ixd.a(PG:175)
E/EsSyncAdapterService( 6664): 	at fig.a(PG:78)
E/EsSyncAdapterService( 6664): 	at lex.a(PG:85)
E/EsSyncAdapterService( 6664): 	at lex.b(PG:132)
E/EsSyncAdapterService( 6664): 	at fhk.a(PG:1146)
E/EsSyncAdapterService( 6664): 	at fhk.a(PG:908)
E/EsSyncAdapterService( 6664): 	at fhk.onPerformSync(PG:636)
E/EsSyncAdapterService( 6664): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/EsSyncAdapterService( 6664): Caused by: java.io.IOException: Cannot obtain authentication token
E/EsSyncAdapterService( 6664): 	at kfv.a(PG:65)
E/EsSyncAdapterService( 6664): 	at kff.u(PG:385)
E/EsSyncAdapterService( 6664): 	at kfb.a(PG:29)
E/EsSyncAdapterService( 6664): 	... 10 more
E/EsSyncAdapterService( 6664): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/EsSyncAdapterService( 6664): 	at ihi.a(PG:22)
E/EsSyncAdapterService( 6664): 	at kft.a(PG:91)
E/EsSyncAdapterService( 6664): 	at kfv.a(PG:62)
E/EsSyncAdapterService( 6664): 	... 12 more
E/EsSyncAdapterService( 6664): Caused by: gdi: User intervention required. Notification has been pushed.
E/EsSyncAdapterService( 6664): 	at gde.c(Unknown Source)
E/EsSyncAdapterService( 6664): 	at gde.b(Unknown Source)
E/EsSyncAdapterService( 6664): 	at ihi.a(PG:19)
E/EsSyncAdapterService( 6664): 	... 14 more
,D/ConnectivityService(  839): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/PhoneStatusBar( 1172): Icon Only
D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
D/PanelView( 1172): There is/are notification(s) 
D/PanelView( 1172): There is/are notification(s) 
D/SyncManager(  839): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, SERVER, currentRunTime 190596, reason: 10135, SyncResult: stats [ numIoExceptions: 2]
,D/ConnectivityService(  839): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  839): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/art     (  839): Explicit concurrent mark sweep GC freed 37034(1910KB) AllocSpace objects, 18(743KB) LOS objects, 30% free, 36MB/52MB, paused 2.190ms total 243.820ms
D/SecContentProvider2(  839): uri = 11 selection = getMyKnoxAdmin
D/SecContentProvider2(  839): mCursor = null
,V/AlarmManager(  839): waitForAlarm result :8
,E/SMD     (  280): DCD ON
,E/Watchdog(  839): !@Sync 6
,E/SQLiteLog( 1661): (10) POSIX Error : 11 SQLite Error : 3850
,E/SMD     (  280): DCD ON
,D/SSRM:m  (  839): SIOP:: AP = 310, PST = 336, CUR = 300
,E/SMD     (  280): DCD ON,
,D/BatteryService(  839): level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 297, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  839): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  839): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  839):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  839): Plugged
,I/MotionRecognitionService(  839): setPowerConnected  = true
,D/BatteryService(  839): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1172): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1172): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1172):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3231): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3231): Disconnected process message: 10
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  280): DCD ON
,E/SMD     (  280): DCD ON
,D/SSRM:m  (  839): SIOP:: AP = 310, PST = 327, CUR = 300
,E/SMD     (  280): DCD ON
,E/SMD     (  280): DCD ON
,W/ContextImpl(  839): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/PowerManagerService(  839): [PWL] Off : 75s ago
,I/Atfwd_Sendcmd(  341): AtCmdFwd service not ready - Exhausted retry attempts - :6
I/Atfwd_Daemon(  341): result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,E/SMD     (  280): DCD ON
,E/SMD     (  280): DCD ON
,D/SSRM:m  (  839): SIOP:: AP = 310, PST = 321, CUR = 300
,V/AlarmManager(  839): waitForAlarm result :4
,D/KeyguardUpdateMonitor( 1172): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1172): handleTimeUpdate
,D/KeyguardEffectViewController( 1172): onReceive action : android.intent.action.TIME_TICK
,I/KeyguardEffectViewController( 1172): *** don't update sliding image ***
,D/BatteryService(  839): level:100, scale:100, status:5, health:2, present:true, voltage: 4386, temperature: 297, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  839): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  839): stay LED for fully charged
D/BatteryService(  839): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1172): received broadcast android.intent.action.BATTERY_CHANGED
,D/MotionRecognitionService(  839):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  839): Plugged
,I/MotionRecognitionService(  839): setPowerConnected  = true
,D/STATUSBAR-PhoneStatusBar( 1172):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3231): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3231): Disconnected process message: 10
D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/KeyguardUpdateMonitor( 1172): handleBatteryUpdate
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/DateView( 1172): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1172): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/ConnectivityService(  839): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/SMD     (  280): DCD ON
,I/ServiceManager(  341): Waiting for service AtCmdFwd...
,E/SMD     (  280): DCD ON
,E/Watchdog(  839): !@Sync 7
,I/ServiceManager(  341): Waiting for service AtCmdFwd...
,D/ConnectivityService(  839): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/ServiceManager(  341): Waiting for service AtCmdFwd...
,I/ServiceManager(  341): Waiting for service AtCmdFwd...
,E/SMD     (  280): DCD ON
,I/ServiceManager(  341): Waiting for service AtCmdFwd...
,D/SSRM:m  (  839): SIOP:: AP = 300, PST = 317, CUR = 300
,W/Atfwd_Sendcmd(  341): AtCmdFwd service not published, waiting... retryCnt : 1
,E/SMD     (  280): DCD ON
,W/ContextImpl(  839): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  280): DCD ON
,I/ServiceManager(  341): Waiting for service AtCmdFwd...
,I/ServiceManager(  341): Waiting for service AtCmdFwd...
,I/ServiceManager(  341): Waiting for service AtCmdFwd...
,E/SMD     (  280): DCD ON
,I/ServiceManager(  341): Waiting for service AtCmdFwd...
,I/ServiceManager(  341): Waiting for service AtCmdFwd...
,D/SSRM:m  (  839): SIOP:: AP = 300, PST = 313, CUR = 300
,W/Atfwd_Sendcmd(  341): AtCmdFwd service not published, waiting... retryCnt : 2
,E/SMD     (  280): DCD ON
,D/BatteryService(  839): level:100, scale:100, status:5, health:2, present:true, voltage: 4386, temperature: 296, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  839): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  839): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  839):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  839): Plugged
,I/MotionRecognitionService(  839): setPowerConnected  = true
,D/BatteryService(  839): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1172): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1172): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1172):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3231): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3231): Disconnected process message: 10
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  280): DCD ON
,I/PowerManagerService(  839): [PWL] Off : 105s ago
,E/SMD     (  280): DCD ON
,E/SMD     (  280): DCD ON
,D/SSRM:m  (  839): SIOP:: AP = 300, PST = 310, CUR = 300
,I/ServiceManager(  341): Waiting for service AtCmdFwd...
,V/AlarmManager(  839): waitForAlarm result :4
,D/ConnectivityService(  839): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/BatteryService(  839): level:100, scale:100, status:5, health:2, present:true, voltage: 4383, temperature: 296, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  839): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
D/BatteryService(  839): stay LED for fully charged
,D/BatteryService(  839): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  839):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  839): Plugged
I/MotionRecognitionService(  839): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1172): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1172): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1172):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3231): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3231): Disconnected process message: 10
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/ConnectivityService(  839): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/BooksSync( 7492): Starting books sync, d
,D/ConnectivityService(  839): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,V/GLSActivity( 1661): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1661): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
,I/GLSUser ( 1661): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1661): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1661): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1661): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/BitmapFactory( 1661): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,I/ServiceManager(  341): Waiting for service AtCmdFwd...
,D/SecContentProvider2(  839): uri = 14 selection = getSealedState
,D/SecContentProvider2(  839): mCursor = null
D/SecContentProvider2(  839): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  839): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy(  839): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/StatusBar( 1172): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,I/PhoneStatusBar( 1172): Icon Only
,D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
D/PanelView( 1172): There is/are notification(s) 
D/PanelView( 1172): There is/are notification(s) 
,W/GLSActivity( 1661): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1661): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1661): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1661): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1661): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1661): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1661): 	at android.os.Binder.execTransact(Binder.java:446)
,E/BooksAccountManager( 7492): Authentication error
E/BooksAccountManager( 7492): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 7492): android.accounts.AccountManager.convertErrorToException(AccountManager.java:1893)
,E/HttpHelper( 7492): null auth token
,I/qtaguid ( 7492): Tagging socket 34 with tag 10000000000{256,0} uid -1, pid: 7492, getuid(): 10082
,I/qtaguid ( 7492): Untagging socket 34
,W/ApiaryClient( 7492): Error response from books API: {
W/ApiaryClient( 7492):  "error": {
W/ApiaryClient( 7492):   "errors": [
W/ApiaryClient( 7492):    {
W/ApiaryClient( 7492):     "domain": "global",
W/ApiaryClient( 7492):     "reason": "required",
W/ApiaryClient( 7492):     "message": "Login Required",
W/ApiaryClient( 7492):     "locationType": "header",
W/ApiaryClient( 7492):     "location": "Authorization"
W/ApiaryClient( 7492):    }
W/ApiaryClient( 7492):   ],
W/ApiaryClient( 7492):   "code": 401,
W/ApiaryClient( 7492):   "message": "Login Required"
W/ApiaryClient( 7492):  }
W/ApiaryClient( 7492): }
,W/ApiaryClient( 7492): errCount = 1: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 7492): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3DS0HXd4TFLU4&nonce=-3879885778263442404&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 7492): Headers suppressed
,D/ConnectivityService(  839): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/ServiceManager(  341): Waiting for service AtCmdFwd...
,V/GLSActivity( 1661): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1661): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
,I/GLSUser ( 1661): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1661): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1661): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1661): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/BitmapFactory( 1661): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  839): uri = 14 selection = getSealedState
,D/SecContentProvider2(  839): mCursor = null
D/SecContentProvider2(  839): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  839): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy(  839): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/StatusBar( 1172): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,I/PhoneStatusBar( 1172): Icon Only
,D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
D/PanelView( 1172): There is/are notification(s) 
,D/PanelView( 1172): There is/are notification(s) 
,W/GLSActivity( 1661): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1661): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1661): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1661): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1661): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1661): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1661): 	at android.os.Binder.execTransact(Binder.java:446)
,E/BooksAccountManager( 7492): Authentication error
E/BooksAccountManager( 7492): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 7492): android.accounts.AccountManager.convertErrorToException(AccountManager.java:1893)
,E/HttpHelper( 7492): null auth token
,I/qtaguid ( 7492): Tagging socket 34 with tag 10000000000{256,0} uid -1, pid: 7492, getuid(): 10082
,I/qtaguid ( 7492): Untagging socket 34
,W/ApiaryClient( 7492): Error response from books API: {
W/ApiaryClient( 7492):  "error": {
W/ApiaryClient( 7492):   "errors": [
W/ApiaryClient( 7492):    {
W/ApiaryClient( 7492):     "domain": "global",
W/ApiaryClient( 7492):     "reason": "required",
W/ApiaryClient( 7492):     "message": "Login Required",
W/ApiaryClient( 7492):     "locationType": "header",
W/ApiaryClient( 7492):     "location": "Authorization"
W/ApiaryClient( 7492):    }
W/ApiaryClient( 7492):   ],
W/ApiaryClient( 7492):   "code": 401,
W/ApiaryClient( 7492):   "message": "Login Required"
W/ApiaryClient( 7492):  }
W/ApiaryClient( 7492): }
,W/ApiaryClient( 7492): errCount = 2: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 7492): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3DS0HXd4TFLU4&nonce=-3879885778263442404&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 7492): Headers suppressed
,D/ConnectivityService(  839): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/SMD     (  280): DCD ON
,I/ServiceManager(  341): Waiting for service AtCmdFwd...
,V/GLSActivity( 1661): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1661): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
,I/GLSUser ( 1661): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1661): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1661): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1661): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/BitmapFactory( 1661): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  839): uri = 14 selection = getSealedState
,D/SecContentProvider2(  839): mCursor = null
D/SecContentProvider2(  839): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  839): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy(  839): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/StatusBar( 1172): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,I/PhoneStatusBar( 1172): Icon Only
,D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
D/PanelView( 1172): There is/are notification(s) 
,D/PanelView( 1172): There is/are notification(s) 
,W/GLSActivity( 1661): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1661): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1661): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1661): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1661): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1661): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1661): 	at android.os.Binder.execTransact(Binder.java:446)
,E/BooksAccountManager( 7492): Authentication error
E/BooksAccountManager( 7492): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 7492): android.accounts.AccountManager.convertErrorToException(AccountManager.java:1893)
,E/HttpHelper( 7492): null auth token
,I/qtaguid ( 7492): Tagging socket 34 with tag 10000000000{256,0} uid -1, pid: 7492, getuid(): 10082
,I/qtaguid ( 7492): Untagging socket 34
,W/ApiaryClient( 7492): Error response from books API: {
W/ApiaryClient( 7492):  "error": {
W/ApiaryClient( 7492):   "errors": [
W/ApiaryClient( 7492):    {
W/ApiaryClient( 7492):     "domain": "global",
W/ApiaryClient( 7492):     "reason": "required",
W/ApiaryClient( 7492):     "message": "Login Required",
W/ApiaryClient( 7492):     "locationType": "header",
W/ApiaryClient( 7492):     "location": "Authorization"
W/ApiaryClient( 7492):    }
W/ApiaryClient( 7492):   ],
W/ApiaryClient( 7492):   "code": 401,
W/ApiaryClient( 7492):   "message": "Login Required"
W/ApiaryClient( 7492):  }
W/ApiaryClient( 7492): }
,W/ApiaryClient( 7492): errCount = 3: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 7492): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3DS0HXd4TFLU4&nonce=-3879885778263442404&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 7492): Headers suppressed
,D/ConnectivityService(  839): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/ServiceManager(  341): Waiting for service AtCmdFwd...
,W/ContextImpl(  839): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/BooksSync( 7492): Soft error
E/BooksSync( 7492): com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
E/BooksSync( 7492): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3DS0HXd4TFLU4&nonce=-3879885778263442404&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
E/BooksSync( 7492): Headers suppressed
E/BooksSync( 7492): 
E/BooksSync( 7492): com.google.android.apps.books.net.HttpHelper.wrapExceptionBasedOnStatus(HttpHelper.java:212)
,E/BooksSync( 7492): Sync error
E/BooksSync( 7492): com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
E/BooksSync( 7492): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3DS0HXd4TFLU4&nonce=-3879885778263442404&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
E/BooksSync( 7492): Headers suppressed
E/BooksSync( 7492): 
E/BooksSync( 7492): com.google.android.apps.books.net.HttpHelper.wrapExceptionBasedOnStatus(HttpHelper.java:212)
,I/BooksSync( 7492): Finished books sync
,D/ConnectivityService(  839): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SyncManager(  839): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 222835, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,D/ConnectivityService(  839): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SecContentProvider2(  839): uri = 11 selection = getMyKnoxAdmin
,D/SecContentProvider2(  839): mCursor = null
,D/ConnectivityService(  839): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,W/Atfwd_Sendcmd(  341): AtCmdFwd service not published, waiting... retryCnt : 3
,V/AlarmManager(  839): waitForAlarm result :8
,E/SMD     (  280): DCD ON
,E/Watchdog(  839): !@Sync 8
,E/SMD     (  280): DCD ON
,D/SSRM:m  (  839): SIOP:: AP = 300, PST = 308, CUR = 300
,D/BatteryService(  839): level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 296, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  839): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  839): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  839):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  839): Plugged
,I/MotionRecognitionService(  839): setPowerConnected  = true
,D/BatteryService(  839): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1172): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1172): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1172):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3231): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3231): Disconnected process message: 10
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  280): DCD ON
,E/SMD     (  280): DCD ON
,E/SMD     (  280): DCD ON
,I/ServiceManager(  341): Waiting for service AtCmdFwd...
,D/SSRM:m  (  839): SIOP:: AP = 300, PST = 306, CUR = 300
,E/SMD     (  280): DCD ON
,I/ServiceManager(  341): Waiting for service AtCmdFwd...
,I/ServiceManager(  341): Waiting for service AtCmdFwd...
,I/ServiceManager(  341): Waiting for service AtCmdFwd...
,E/SMD     (  280): DCD ON
,I/ServiceManager(  341): Waiting for service AtCmdFwd...
,W/ContextImpl(  839): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,W/Atfwd_Sendcmd(  341): AtCmdFwd service not published, waiting... retryCnt : 4
,E/SMD     (  280): DCD ON
,I/PowerManagerService(  839): [PWL] Off : 140s ago
,E/SMD     (  280): DCD ON
,D/SSRM:m  (  839): SIOP:: AP = 300, PST = 304, CUR = 300
,V/AlarmManager(  839): waitForAlarm result :4
,D/KeyguardUpdateMonitor( 1172): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1172): handleTimeUpdate
,D/KeyguardEffectViewController( 1172): onReceive action : android.intent.action.TIME_TICK
,I/KeyguardEffectViewController( 1172): *** don't update sliding image ***
,D/BatteryService(  839): level:100, scale:100, status:5, health:2, present:true, voltage: 4386, temperature: 296, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  839): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  839): stay LED for fully charged
,D/BatteryService(  839): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  839):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  839): Plugged
,I/MotionRecognitionService(  839): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1172): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1172): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1172):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3231): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3231): Disconnected process message: 10
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/DateView( 1172): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1172): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/ConnectivityService(  839): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  839): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/GLSUser ( 1661): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,I/GLSUser ( 1661): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1661): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1661): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1661): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/BitmapFactory( 1661): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  839): uri = 14 selection = getSealedState
,D/SecContentProvider2(  839): mCursor = null
,D/SecContentProvider2(  839): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  839): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy(  839): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/StatusBar( 1172): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,I/PhoneStatusBar( 1172): Icon Only
,D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
D/PanelView( 1172): There is/are notification(s) 
,D/PanelView( 1172): There is/are notification(s) 
,E/HttpOperation( 6664): [kfu{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
E/HttpOperation( 6664): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 6664): 	at kfv.a(PG:65)
E/HttpOperation( 6664): 	at kff.u(PG:385)
E/HttpOperation( 6664): 	at kfb.a(PG:29)
E/HttpOperation( 6664): 	at kff.l(PG:132)
E/HttpOperation( 6664): 	at dsf.a(PG:807)
E/HttpOperation( 6664): 	at fhk.a(PG:1126)
E/HttpOperation( 6664): 	at fhk.a(PG:908)
E/HttpOperation( 6664): 	at fhk.onPerformSync(PG:636)
E/HttpOperation( 6664): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/HttpOperation( 6664): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/HttpOperation( 6664): 	at ihi.a(PG:22)
E/HttpOperation( 6664): 	at kft.a(PG:91)
E/HttpOperation( 6664): 	at kfv.a(PG:62)
E/HttpOperation( 6664): 	... 8 more
E/HttpOperation( 6664): Caused by: gdi: User intervention required. Notification has been pushed.
E/HttpOperation( 6664): 	at gde.c(Unknown Source)
E/HttpOperation( 6664): 	at gde.b(Unknown Source)
E/HttpOperation( 6664): 	at ihi.a(PG:19)
E/HttpOperation( 6664): 	... 10 more
,I/GLSUser ( 1661): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,I/GLSUser ( 1661): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1661): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1661): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1661): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/BitmapFactory( 1661): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  839): uri = 14 selection = getSealedState
,D/SecContentProvider2(  839): mCursor = null
D/SecContentProvider2(  839): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  839): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy(  839): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/StatusBar( 1172): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,I/PhoneStatusBar( 1172): Icon Only
,D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1172): value : false
D/PanelView( 1172): There is/are notification(s) 
,D/PanelView( 1172): There is/are notification(s) 
,E/HttpOperation( 6664): [getmobileexperiments] Unexpected exception
E/HttpOperation( 6664): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 6664): 	at kfv.a(PG:65)
E/HttpOperation( 6664): 	at kff.u(PG:385)
E/HttpOperation( 6664): 	at kfb.a(PG:29)
E/HttpOperation( 6664): 	at kff.l(PG:132)
E/HttpOperation( 6664): 	at ieo.a(PG:43)
E/HttpOperation( 6664): 	at iep.a(PG:93)
E/HttpOperation( 6664): 	at fhn.a(PG:59)
E/HttpOperation( 6664): 	at lex.a(PG:85)
E/HttpOperation( 6664): 	at lex.b(PG:132)
E/HttpOperation( 6664): 	at fhk.a(PG:1146)
E/HttpOperation( 6664): 	at fhk.a(PG:908)
E/HttpOperation( 6664): 	at fhk.onPerformSync(PG:636)
E/HttpOperation( 6664): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/HttpOperation( 6664): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/HttpOperation( 6664): 	at ihi.a(PG:22)
E/HttpOperation( 6664): 	at kft.a(PG:91)
E/HttpOperation( 6664): 	at kfv.a(PG:62)
E/HttpOperation( 6664): 	... 12 more
E/HttpOperation( 6664): Caused by: gdi: User intervention required. Notification has been pushed.
E/HttpOperation( 6664): 	at gde.c(Unknown Source)
E/HttpOperation( 6664): 	at gde.b(Unknown Source)
E/HttpOperation( 6664): 	at ihi.a(PG:19)
E/HttpOperation( 6664): 	... 14 more
,E/ExperimentLoader( 6664): [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 6664): java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 6664): 	at kfv.a(PG:65)
E/ExperimentLoader( 6664): 	at kff.u(PG:385)
E/ExperimentLoader( 6664): 	at kfb.a(PG:29)
E/ExperimentLoader( 6664): 	at kff.l(PG:132)
E/ExperimentLoader( 6664): 	at ieo.a(PG:43)
E/ExperimentLoader( 6664): 	at iep.a(PG:93)
E/ExperimentLoader( 6664): 	at fhn.a(PG:59)
E/ExperimentLoader( 6664): 	at lex.a(PG:85)
E/ExperimentLoader( 6664): 	at lex.b(PG:132)
E/ExperimentLoader( 6664): 	at fhk.a(PG:1146)
E/ExperimentLoader( 6664): 	at fhk.a(PG:908)
E/ExperimentLoader( 6664): 	at fhk.onPerformSync(PG:636)
E/ExperimentLoader( 6664): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/ExperimentLoader( 6664): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/ExperimentLoader( 6664): 	at ihi.a(PG:22)
E/ExperimentLoader( 6664): 	at kft.a(PG:91)
E/ExperimentLoader( 6664): 	at kfv.a(PG:62)
E/ExperimentLoader( 6664): 	... 12 more
E/ExperimentLoader( 6664): Caused by: gdi: User intervention required. Notification has been pushed.
E/ExperimentLoader( 6664): 	at gde.c(Unknown Source)
E/ExperimentLoader( 6664): 	at gde.b(Unknown Source)
E/ExperimentLoader( 6664): 	at ihi.a(PG:19)
E/ExperimentLoader( 6664): 	... 14 more
,I/GLSUser ( 1661): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
I/GLSUser ( 1661): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1661): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1661): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 1661): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/BitmapFactory( 1661): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  839): uri = 14 selection = getSealedState
,D/SecContentProvider2(  839): mCursor = null
D/SecContentProvider2(  839): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  839): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy(  839): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/StatusBar( 1172): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,I/PhoneStatusBar( 1172): Icon Only
,D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
D/PanelView( 1172): There is/are notification(s) 
,D/PanelView( 1172): There is/are notification(s) 
,E/HttpOperation( 6664): [getaccountstatus] Unexpected exception
E/HttpOperation( 6664): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 6664): 	at kfv.a(PG:65)
E/HttpOperation( 6664): 	at kff.u(PG:385)
E/HttpOperation( 6664): 	at kfb.a(PG:29)
E/HttpOperation( 6664): 	at ixd.a(PG:248)
E/HttpOperation( 6664): 	at ixd.b(PG:206)
E/HttpOperation( 6664): 	at ixd.a(PG:175)
E/HttpOperation( 6664): 	at fig.a(PG:78)
E/HttpOperation( 6664): 	at lex.a(PG:85)
E/HttpOperation( 6664): 	at lex.b(PG:132)
E/HttpOperation( 6664): 	at fhk.a(PG:1146)
E/HttpOperation( 6664): 	at fhk.a(PG:908)
E/HttpOperation( 6664): 	at fhk.onPerformSync(PG:636)
E/HttpOperation( 6664): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/HttpOperation( 6664): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/HttpOperation( 6664): 	at ihi.a(PG:22)
E/HttpOperation( 6664): 	at kft.a(PG:91)
E/HttpOperation( 6664): 	at kfv.a(PG:62)
E/HttpOperation( 6664): 	... 12 more
E/HttpOperation( 6664): Caused by: gdi: User intervention required. Notification has been pushed.
E/HttpOperation( 6664): 	at gde.c(Unknown Source)
E/HttpOperation( 6664): 	at gde.b(Unknown Source)
E/HttpOperation( 6664): 	at ihi.a(PG:19)
E/HttpOperation( 6664): 	... 14 more
,E/EsSyncAdapterService( 6664): Sync failure
E/EsSyncAdapterService( 6664): java.io.IOException: Rpc failed
E/EsSyncAdapterService( 6664): 	at ixd.a(PG:348)
E/EsSyncAdapterService( 6664): 	at ixd.a(PG:248)
E/EsSyncAdapterService( 6664): 	at ixd.b(PG:206)
E/EsSyncAdapterService( 6664): 	at ixd.a(PG:175)
E/EsSyncAdapterService( 6664): 	at fig.a(PG:78)
E/EsSyncAdapterService( 6664): 	at lex.a(PG:85)
E/EsSyncAdapterService( 6664): 	at lex.b(PG:132)
E/EsSyncAdapterService( 6664): 	at fhk.a(PG:1146)
E/EsSyncAdapterService( 6664): 	at fhk.a(PG:908)
E/EsSyncAdapterService( 6664): 	at fhk.onPerformSync(PG:636)
E/EsSyncAdapterService( 6664): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/EsSyncAdapterService( 6664): Caused by: java.io.IOException: Cannot obtain authentication token
E/EsSyncAdapterService( 6664): 	at kfv.a(PG:65)
E/EsSyncAdapterService( 6664): 	at kff.u(PG:385)
E/EsSyncAdapterService( 6664): 	at kfb.a(PG:29)
E/EsSyncAdapterService( 6664): 	... 10 more
E/EsSyncAdapterService( 6664): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/EsSyncAdapterService( 6664): 	at ihi.a(PG:22)
E/EsSyncAdapterService( 6664): 	at kft.a(PG:91)
E/EsSyncAdapterService( 6664): 	at kfv.a(PG:62)
E/EsSyncAdapterService( 6664): 	... 12 more
E/EsSyncAdapterService( 6664): Caused by: gdi: User intervention required. Notification has been pushed.
E/EsSyncAdapterService( 6664): 	at gde.c(Unknown Source)
E/EsSyncAdapterService( 6664): 	at gde.b(Unknown Source)
E/EsSyncAdapterService( 6664): 	at ihi.a(PG:19)
E/EsSyncAdapterService( 6664): 	... 14 more
,D/ConnectivityService(  839): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/SyncManager(  839): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, SERVER, currentRunTime 256349, reason: 10135, SyncResult: stats [ numIoExceptions: 2]
D/ConnectivityService(  839): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  839): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ResourcesManager( 2856): creating new AssetManager and set to /system/app/PlusOne/PlusOne.apk
,D/SecContentProvider2(  839): uri = 11 selection = getMyKnoxAdmin
D/SecContentProvider2(  839): mCursor = null
,E/SQLiteLog( 1661): (10) POSIX Error : 11 SQLite Error : 3850
,E/SMD     (  280): DCD ON
,E/SMD     (  280): DCD ON
,E/Watchdog(  839): !@Sync 9
,E/SMD     (  280): DCD ON
,D/SSRM:m  (  839): SIOP:: AP = 300, PST = 303, CUR = 300
,D/BatteryService(  839): level:100, scale:100, status:5, health:2, present:true, voltage: 4383, temperature: 296, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  839): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  839): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  839):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  839): Plugged
,I/MotionRecognitionService(  839): setPowerConnected  = true
,D/BatteryService(  839): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1172): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1172): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1172):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3231): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3231): Disconnected process message: 10
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  280): DCD ON
,W/ContextImpl(  839): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  280): DCD ON
,I/ServiceManager(  341): Waiting for service AtCmdFwd...
,I/ServiceManager(  341): Waiting for service AtCmdFwd...
,I/ServiceManager(  341): Waiting for service AtCmdFwd...
,E/SMD     (  280): DCD ON
,I/ServiceManager(  341): Waiting for service AtCmdFwd...
,I/ServiceManager(  341): Waiting for service AtCmdFwd...
,W/Atfwd_Sendcmd(  341): AtCmdFwd service not published, waiting... retryCnt : 5
,D/SSRM:m  (  839): SIOP:: AP = 300, PST = 302, CUR = 300
,E/SMD     (  280): DCD ON
,D/BatteryService(  839): level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 295, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  839): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  839): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  839):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  839): Plugged
,I/MotionRecognitionService(  839): setPowerConnected  = true
,D/BatteryService(  839): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1172): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1172): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1172):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3231): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3231): Disconnected process message: 10
,E/SMD     (  280): DCD ON
,E/SMD     (  280): DCD ON
,E/SMD     (  280): DCD ON
,D/SSRM:m  (  839): SIOP:: AP = 300, PST = 301, CUR = 300
,V/AlarmManager(  839): waitForAlarm result :4
,D/ConnectivityService(  839): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/BatteryService(  839): level:100, scale:100, status:5, health:2, present:true, voltage: 4386, temperature: 295, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  839): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  839): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  839):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  839): Plugged
,I/MotionRecognitionService(  839): setPowerConnected  = true
,D/BatteryService(  839): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1172): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1172): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1172):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3231): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3231): Disconnected process message: 10
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  280): DCD ON
,D/TimaService(  839): TIMA: TimaService scheduler is intialized. 
,D/TimaService(  839): TimaServiceHandler.handleMessage what =1
,D/TimaService(  839): TIMA: checkEvent, operation: 50000 subject: 10000
,I/TLC_TIMA_PKM_initialize(  839): initializing...
,I/TLC_TIMA_PKM_initialize(  839): root = /firmware/image, root_strlen = 15
,I/TLC_TIMA_PKM_initialize(  839): process = tima_pkm, process_strlen = 8
,I/TZ: qc_tlc_communication(  839): root = /firmware/image, root_len = 15
,I/TZ: qc_tlc_communication(  839): process = tima_pkm, process_strlen = 8
,I/TZ: qc_tlc_communication(  839): aligned max_sendmsg_size = 262208 = 0x40040
,I/TZ: qc_tlc_communication(  839): aligned max_recvmsg_size = 262208 = 0x40040
,I/TZ: qc_tlc_communication(  839): max_message_size = 524416 = 0x80080
,D/QSEECOMAPI: (  839): QSEECom_get_handle sb_length = 0x80080
,D/QSEECOMAPI: (  839): App is not loaded in QSEE
,D/QSEECOMAPI: (  839): Loaded image: APP id = 2
,I/TZ: qc_tlc_communication(  839): TIMA: path = /firmware/image, fname = tima_pkm, tzapp is loaded
,I/TLC_TIMA_PKM_initialize(  839): Trustlet response is completed
,W/ContextImpl(  839): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,V/AlarmManager(  839): waitForAlarm result :8
,E/SMD     (  280): DCD ON
,E/Watchdog(  839): !@Sync 10
,I/TLC_TIMA_PKM_measure_kernel(  839): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel(  839): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService(  839): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService(  839): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,E/SMD     (  280): DCD ON
,I/PowerManagerService(  839): [PWL] Off : 180s ago
,D/SSRM:m  (  839): SIOP:: AP = 300, PST = 300, CUR = 300
,D/BatteryService(  839): level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 295, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  839): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
D/BatteryService(  839): stay LED for fully charged
D/BatteryService(  839): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  839):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  839): Plugged
I/MotionRecognitionService(  839): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1172): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1172): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1172):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3231): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3231): Disconnected process message: 10
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  280): DCD ON
,E/SMD     (  280): DCD ON
,I/Atfwd_Sendcmd(  341): AtCmdFwd service not ready - Exhausted retry attempts - :6
I/Atfwd_Daemon(  341): result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,E/SMD     (  280): DCD ON
,D/SSRM:m  (  839): SIOP:: AP = 300, PST = 300, CUR = 300
,E/SMD     (  280): DCD ON
,E/SMD     (  280): DCD ON
,W/ContextImpl(  839): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,V/AlarmManager(  839): waitForAlarm result :4
,D/KeyguardUpdateMonitor( 1172): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1172): handleTimeUpdate
,D/KeyguardEffectViewController( 1172): onReceive action : android.intent.action.TIME_TICK
,I/KeyguardEffectViewController( 1172): *** don't update sliding image ***
,E/ActivityManager(  839): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  839): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  839): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  839): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 8402): MountEmulatedStorage()
,E/Zygote  ( 8402): v2
,I/libpersona( 8402): KNOX_SDCARD checking this for 10081
,I/libpersona( 8402): KNOX_SDCARD not a persona
,D/BatteryService(  839): level:100, scale:100, status:5, health:2, present:true, voltage: 4383, temperature: 295, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  839): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,I/ActivityManager(  839): Start proc com.blurb.checkout for broadcast com.blurb.checkout/.RebootReceiver: pid=8402 uid=10081 gids={50081, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,D/BatteryService(  839): stay LED for fully charged
,D/BatteryService(  839): Sending ACTION_BATTERY_CHANGED.
,I/SELinux ( 8402): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
I/SELinux ( 8402): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
E/SELinux ( 8402): [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
,D/MotionRecognitionService(  839):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  839): Plugged
I/MotionRecognitionService(  839): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1172): received broadcast android.intent.action.BATTERY_CHANGED
,V/HeadsetService( 3231): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 3231): Disconnected process message: 10
D/KeyguardUpdateMonitor( 1172): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1172):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/DateView( 1172): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1172): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/TimaKeyStoreProvider( 8402): TimaSignature is unavailable
,D/ActivityThread( 8402): Added TimaKeyStore provider
,D/ResourcesManager( 8402): creating new AssetManager and set to /system/app/Blurb/Blurb.apk
,I/ActivityManager(  839): Killing 7118:com.sec.kidsplat.installer/u0a166 (adj 15): bgCount ##41
,W/libprocessgroup(  839): failed to open /acct/uid_10166/pid_7118/cgroup.procs: No such file or directory
,E/SMD     (  280): DCD ON
,E/SMD     (  280): DCD ON
,I/ServiceManager(  341): Waiting for service AtCmdFwd...
,D/SSRM:m  (  839): SIOP:: AP = 300, PST = 300, CUR = 300
,I/ServiceManager(  341): Waiting for service AtCmdFwd...
,V/AlarmManager(  839): waitForAlarm result :4
,D/ConnectivityService(  839): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  839): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/BooksSync( 7492): Starting books sync, d
,D/ConnectivityService(  839): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,V/GLSActivity( 1661): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1661): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
,I/GLSUser ( 1661): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1661): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1661): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1661): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/BitmapFactory( 1661): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  839): uri = 14 selection = getSealedState
,D/SecContentProvider2(  839): mCursor = null
D/SecContentProvider2(  839): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  839): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy(  839): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/StatusBar( 1172): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,W/GLSActivity( 1661): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1661): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1661): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1661): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1661): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1661): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1661): 	at android.os.Binder.execTransact(Binder.java:446)
,E/BooksAccountManager( 7492): Authentication error
E/BooksAccountManager( 7492): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 7492): android.accounts.AccountManager.convertErrorToException(AccountManager.java:1893)
E/HttpHelper( 7492): null auth token
,I/PhoneStatusBar( 1172): Icon Only
,I/qtaguid ( 7492): Tagging socket 34 with tag 10000000000{256,0} uid -1, pid: 7492, getuid(): 10082
D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
D/PanelView( 1172): There is/are notification(s) 
D/PanelView( 1172): There is/are notification(s) 
,I/qtaguid ( 7492): Untagging socket 34
,W/ApiaryClient( 7492): Error response from books API: {
W/ApiaryClient( 7492):  "error": {
W/ApiaryClient( 7492):   "errors": [
W/ApiaryClient( 7492):    {
W/ApiaryClient( 7492):     "domain": "global",
W/ApiaryClient( 7492):     "reason": "required",
W/ApiaryClient( 7492):     "message": "Login Required",
W/ApiaryClient( 7492):     "locationType": "header",
W/ApiaryClient( 7492):     "location": "Authorization"
W/ApiaryClient( 7492):    }
W/ApiaryClient( 7492):   ],
W/ApiaryClient( 7492):   "code": 401,
W/ApiaryClient( 7492):   "message": "Login Required"
W/ApiaryClient( 7492):  }
W/ApiaryClient( 7492): }
,W/ApiaryClient( 7492): errCount = 1: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 7492): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3DS0HXd4TFLU4&nonce=-3069393255853078249&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 7492): Headers suppressed
,D/ConnectivityService(  839): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/ServiceManager(  341): Waiting for service AtCmdFwd...
,V/GLSActivity( 1661): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1661): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
,I/GLSUser ( 1661): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1661): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1661): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1661): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/BitmapFactory( 1661): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  839): uri = 14 selection = getSealedState
,D/SecContentProvider2(  839): mCursor = null
D/SecContentProvider2(  839): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  839): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy(  839): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/StatusBar( 1172): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,I/PhoneStatusBar( 1172): Icon Only
,D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
,D/PanelView( 1172): There is/are notification(s) 
D/PanelView( 1172): There is/are notification(s) 
,W/GLSActivity( 1661): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1661): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1661): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1661): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1661): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1661): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1661): 	at android.os.Binder.execTransact(Binder.java:446)
,E/BooksAccountManager( 7492): Authentication error
E/BooksAccountManager( 7492): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 7492): android.accounts.AccountManager.convertErrorToException(AccountManager.java:1893)
,E/HttpHelper( 7492): null auth token
,I/qtaguid ( 7492): Tagging socket 34 with tag 10000000000{256,0} uid -1, pid: 7492, getuid(): 10082
,E/SMD     (  280): DCD ON
,I/qtaguid ( 7492): Untagging socket 34
,W/ApiaryClient( 7492): Error response from books API: {
W/ApiaryClient( 7492):  "error": {
W/ApiaryClient( 7492):   "errors": [
W/ApiaryClient( 7492):    {
W/ApiaryClient( 7492):     "domain": "global",
W/ApiaryClient( 7492):     "reason": "required",
W/ApiaryClient( 7492):     "message": "Login Required",
W/ApiaryClient( 7492):     "locationType": "header",
W/ApiaryClient( 7492):     "location": "Authorization"
W/ApiaryClient( 7492):    }
W/ApiaryClient( 7492):   ],
W/ApiaryClient( 7492):   "code": 401,
W/ApiaryClient( 7492):   "message": "Login Required"
W/ApiaryClient( 7492):  }
W/ApiaryClient( 7492): }
,W/ApiaryClient( 7492): errCount = 2: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 7492): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3DS0HXd4TFLU4&nonce=-3069393255853078249&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 7492): Headers suppressed
,D/ConnectivityService(  839): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/ServiceManager(  341): Waiting for service AtCmdFwd...
,V/GLSActivity( 1661): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1661): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
,I/GLSUser ( 1661): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1661): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1661): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1661): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/BitmapFactory( 1661): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  839): uri = 14 selection = getSealedState
,D/SecContentProvider2(  839): mCursor = null
D/SecContentProvider2(  839): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  839): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy(  839): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/StatusBar( 1172): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,I/PhoneStatusBar( 1172): Icon Only
,D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
D/PanelView( 1172): There is/are notification(s) 
,D/PanelView( 1172): There is/are notification(s) 
,W/GLSActivity( 1661): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1661): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1661): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1661): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1661): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1661): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1661): 	at android.os.Binder.execTransact(Binder.java:446)
,E/BooksAccountManager( 7492): Authentication error
E/BooksAccountManager( 7492): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 7492): android.accounts.AccountManager.convertErrorToException(AccountManager.java:1893)
,E/HttpHelper( 7492): null auth token
,I/qtaguid ( 7492): Tagging socket 34 with tag 10000000000{256,0} uid -1, pid: 7492, getuid(): 10082
,I/qtaguid ( 7492): Untagging socket 34
,W/ApiaryClient( 7492): Error response from books API: {
W/ApiaryClient( 7492):  "error": {
W/ApiaryClient( 7492):   "errors": [
W/ApiaryClient( 7492):    {
W/ApiaryClient( 7492):     "domain": "global",
W/ApiaryClient( 7492):     "reason": "required",
W/ApiaryClient( 7492):     "message": "Login Required",
W/ApiaryClient( 7492):     "locationType": "header",
W/ApiaryClient( 7492):     "location": "Authorization"
W/ApiaryClient( 7492):    }
W/ApiaryClient( 7492):   ],
W/ApiaryClient( 7492):   "code": 401,
W/ApiaryClient( 7492):   "message": "Login Required"
W/ApiaryClient( 7492):  }
W/ApiaryClient( 7492): }
,W/ApiaryClient( 7492): errCount = 3: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 7492): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3DS0HXd4TFLU4&nonce=-3069393255853078249&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 7492): Headers suppressed
,D/ConnectivityService(  839): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/ServiceManager(  341): Waiting for service AtCmdFwd...
,E/BooksSync( 7492): Soft error
E/BooksSync( 7492): com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
E/BooksSync( 7492): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3DS0HXd4TFLU4&nonce=-3069393255853078249&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
E/BooksSync( 7492): Headers suppressed
E/BooksSync( 7492): 
E/BooksSync( 7492): com.google.android.apps.books.net.HttpHelper.wrapExceptionBasedOnStatus(HttpHelper.java:212)
,E/BooksSync( 7492): Sync error
E/BooksSync( 7492): com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
E/BooksSync( 7492): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3DS0HXd4TFLU4&nonce=-3069393255853078249&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
E/BooksSync( 7492): Headers suppressed
E/BooksSync( 7492): 
E/BooksSync( 7492): com.google.android.apps.books.net.HttpHelper.wrapExceptionBasedOnStatus(HttpHelper.java:212)
,I/BooksSync( 7492): Finished books sync
,D/ConnectivityService(  839): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,W/Atfwd_Sendcmd(  341): AtCmdFwd service not published, waiting... retryCnt : 1
,D/SyncManager(  839): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 313579, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,D/ConnectivityService(  839): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ResourcesManager( 2856): creating new AssetManager and set to /system/app/ChatON_MARKET/ChatON_MARKET.apk
,D/ResourcesManager( 2856): creating new AssetManager and set to /system/app/PlusOne/PlusOne.apk
,D/ConnectivityService(  839): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/art     (  839): Explicit concurrent mark sweep GC freed 49950(3MB) AllocSpace objects, 58(1513KB) LOS objects, 30% free, 36MB/52MB, paused 1.563ms total 163.500ms
D/SecContentProvider2(  839): uri = 11 selection = getMyKnoxAdmin
D/SecContentProvider2(  839): mCursor = null
,E/SMD     (  280): DCD ON
,E/Watchdog(  839): !@Sync 11
,D/BatteryService(  839): level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 295, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  839): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  839): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  839):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  839): Plugged
,I/MotionRecognitionService(  839): setPowerConnected  = true
,D/BatteryService(  839): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1172): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1172): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1172):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3231): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3231): Disconnected process message: 10
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  280): DCD ON
,I/ServiceManager(  341): Waiting for service AtCmdFwd...
,D/SSRM:m  (  839): SIOP:: AP = 300, PST = 300, CUR = 300
,I/ServiceManager(  341): Waiting for service AtCmdFwd...
,E/SMD     (  280): DCD ON
,I/ServiceManager(  341): Waiting for service AtCmdFwd...
,I/ServiceManager(  341): Waiting for service AtCmdFwd...
,I/ServiceManager(  341): Waiting for service AtCmdFwd...
,W/ContextImpl(  839): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 

```
