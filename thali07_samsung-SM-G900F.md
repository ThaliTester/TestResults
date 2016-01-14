#### Test 55613145c131883_thali07_samsung-SM-G900F Logs


```
--------- beginning of main
,V/GLSActivity( 1670): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/GLSUser ( 1670): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
I/GLSUser ( 1670): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1670): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1670): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 1670): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/BitmapFactory( 1670): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
D/SecContentProvider2(  890): uri = 14 selection = getSealedState
D/SecContentProvider2(  890): mCursor = null
D/SecContentProvider2(  890): KnoxCustomManagerService offline: service is not available
D/ApplicationPolicy(  890): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
V/ApplicationPolicy(  890): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
W/GLSActivity( 1670): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1670): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1670): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1670): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1670): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1670): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1670): 	at android.os.Binder.execTransact(Binder.java:446)
D/StatusBar( 1169): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
I/PhoneStatusBar( 1169): Icon Only
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
D/PanelView( 1169): There is/are notification(s) 
D/PanelView( 1169): There is/are notification(s) 
E/BooksAccountManager( 7396): Authentication error
E/BooksAccountManager( 7396): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 7396): android.accounts.AccountManager.convertErrorToException(AccountManager.java:1893)
E/HttpHelper( 7396): null auth token
I/qtaguid ( 7396): Tagging socket 34 with tag 10000000000{256,0} uid -1, pid: 7396, getuid(): 10082
I/qtaguid ( 7396): Tagging socket 38 with tag 10000000000{256,0} uid -1, pid: 7396, getuid(): 10082
I/qtaguid ( 7396): Untagging socket 34
W/ApiaryClient( 7396): Error response from books API: {
W/ApiaryClient( 7396):  "error": {
W/ApiaryClient( 7396):   "errors": [
W/ApiaryClient( 7396):    {
W/ApiaryClient( 7396):     "domain": "global",
W/ApiaryClient( 7396):     "reason": "required",
W/ApiaryClient( 7396):     "message": "Login Required",
W/ApiaryClient( 7396):     "locationType": "header",
W/ApiaryClient( 7396):     "location": "Authorization"
W/ApiaryClient( 7396):    }
W/ApiaryClient( 7396):   ],
W/ApiaryClient( 7396):   "code": 401,
W/ApiaryClient( 7396):   "message": "Login Required"
W/ApiaryClient( 7396):  }
W/ApiaryClient( 7396): }
W/ApiaryClient( 7396): errCount = 2: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 7396): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3DS0HXd4TFLU4&nonce=8684919974650991427&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 7396): Headers suppressed
--------- beginning of system
D/ConnectivityService(  890): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/AndroidRuntime( 7452): 
D/AndroidRuntime( 7452): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 7452): CheckJNI is OFF
D/AndroidRuntime( 7452): setted country_code = Germany
D/AndroidRuntime( 7452): setted countryiso_code = DE
D/AndroidRuntime( 7452): setted sales_code = DBT
D/AndroidRuntime( 7452): readGMSProperty: start
D/AndroidRuntime( 7452): readGMSProperty: already setted!!
D/AndroidRuntime( 7452): readGMSProperty: end
D/AndroidRuntime( 7452): addProductProperty: start
E/AffinityControl( 7452): AffinityControl: registerfunction enter
D/AndroidRuntime( 7452): Calling main entry com.android.commands.am.Am
E/PersonaManagerService(  890): inState():  stateMachine is null !!
V/ApplicationPolicy(  890): isApplicationStateBlocked userId 0 pkgname com.test.thalitest
D/ResourcesManager(  890): creating new AssetManager and set to /data/app/com.test.thalitest-1/base.apk
I/ActivityManager(  890): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
D/CustomFrequencyManagerService(  890): acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1958400  uid : 1000  pid : 890  pkgName : ACTIVITY_RESUME_BOOSTER@6
W/ActivityManager(  890): mDVFSHelper.acquire()
D/FocusedStackFrame(  890): Set to : 0
D/Launcher.HomeView( 1490): onPause
D/Launcher( 1490): Launcher::setSystemUiTransparency(): getSystemUiVisibility() after setting  = 40000000
D/AndroidRuntime( 7452): Shutting down VM
E/ActivityManager(  890): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  890): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  890): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  890): checkUser: useridlist=null, currentuser=0
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
V/TaskCloserActivity( 7228): TaskCloserActivity onReceive() - com.sec.android.intent.action.HOME_PAUSE
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
I/SurfaceFlinger(  249): id=14 createSurf (1x1),1 flag=404, Starting com.test.thalitest
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
E/Zygote  ( 7474): MountEmulatedStorage()
E/Zygote  ( 7474): v2
I/libpersona( 7474): KNOX_SDCARD checking this for 10200
I/libpersona( 7474): KNOX_SDCARD not a persona
I/ActivityManager(  890): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=7474 uid=10200 gids={50200, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
I/SELinux ( 7474): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
I/SELinux ( 7474): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
E/SELinux ( 7474): [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
D/StatusBarManagerService(  890): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
D/TimaKeyStoreProvider( 7474): TimaSignature is unavailable
D/ActivityThread( 7474): Added TimaKeyStore provider
I/MicrophoneInputStream( 1559): mic_close gfk@36de5478
V/AudioPolicyManager(  285): stopInput() input 29
V/AudioPolicyManager(  285): releaseInput() 29
V/AudioPolicyManager(  285): closeInput(29)
V/WindowOrientationListener(  890): mSContextAutoRotationListener.getProposedRotation, mbResultFaceDectection: false
V/WindowManager(  890): rotationForOrientationLw(orient=-1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false
V/WindowOrientationListener(  890): mSContextAutoRotationListener.getProposedRotation, Rotation: -1
V/WindowOrientationListener(  890): mSContextAutoRotationListener.getProposedRotation, mbResultFaceDectection: false
V/WindowOrientationListener(  890): mSContextAutoRotationListener.getProposedRotation, Rotation: -1
V/audio_hw_primary(  285): in_standby: enter
I/HotwordRecognitionRnr( 1559): Hotword detection finished
I/HotwordRecognitionRnr( 1559): Stopping hotword detection.
V/ActivityManager(  890): Display changed displayId=0
D/Launcher.HomeView( 1490): onStop
D/SurfaceWidgetClient$ISurfaceWidgetStub( 2166): [237392/6] Surface widget pause on instance = 1
D/accuweather( 2166): [KK AccuPhone]>>> SWW:239 [0:0] [SWW] onPause : instance = 1
D/accuweather( 2166): [KK AccuPhone]>>> SWW:254 [0:0] onPause : size = 0
D/accuweather( 2166): [KK AccuPhone]>>> SWW:545 [0:0]  unRegisterTTReceiver !! 
D/SurfaceWidgetClient$ISurfaceWidgetStub( 2166): [237392/6] Surface widget visibility changed visibility = false on instance = 1
D/SurfaceWidgetView( 1490): destroyHardwareResources():373658336
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
D/audio_route(  285): Setting mixer control: DEC2 MUX, value: 0
D/audio_route(  285): ------ audio_route_update_mixer ==============
V/audio_hw_primary(  285): stop_input_stream: exit: status(0)
V/audio_hw_primary(  285): in_standby: exit:  status(0)
V/audio_hw_primary(  285): adev_close_input_stream
V/audio_hw_primary(  285): in_standby: enter
V/audio_hw_primary(  285): in_standby: exit:  status(0)
E/audio_hw_primary(  285): adev_close_input_stream, set jack_in to null
V/AudioPolicyManager(  285): releaseInput() exit
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
D/Launcher( 1490): onTrimMemory. Level: 20
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
D/SurfaceWidgetView( 1490): destroyHardwareResources():373658336
D/StatusBarManagerService(  890): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
D/accuweather( 2166): [KK AccuPhone]>>> WR:132 [0:0] onPause
D/accuweather( 2166): [KK AccuPhone]>>> SM:538 [0:0] onPause
D/ConnectivityService(  890): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
D/ResourcesManager( 7474): creating new AssetManager and set to /data/app/com.test.thalitest-1/base.apk
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
E/SMD     (  277): DCD ON
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
I/WebViewFactory( 7474): Loading com.google.android.webview version 37 (1726107-arm) (code 119201)
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
D/ResourcesManager( 7474): creating new AssetManager and set to /system/app/WebViewGoogle/WebViewGoogle.apk
I/LibraryLoader( 7474): Loading: webviewchromium
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
I/LibraryLoader( 7474): Time to load native libraries: 2 ms (timestamps 4592-4594)
I/LibraryLoader( 7474): Expected native library version number "",actual native library version number ""
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
V/WebViewChromiumFactoryProvider( 7474): Binding Chromium to main looper Looper (main, tid 1) {2e238d68}
I/LibraryLoader( 7474): Expected native library version number "",actual native library version number ""
I/chromium( 7474): [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 7474): Initializing chromium process, renderers=0
W/art     ( 7474): Attempt to remove local handle scope entry from IRT, ignoring
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
W/chromium( 7474): [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
I/chromium( 7474): [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=35 off=46768 len=2953
I/chromium( 7474): [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:36 off:229524 len:643667
I/Adreno-EGL( 7474): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 7474): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 7474): Build Date: 03/03/15 Tue
I/Adreno-EGL( 7474): Local Branch: LA.BF.1.1_RB1_20150108_025_1077123_1158499
I/Adreno-EGL( 7474): Remote Branch: 
I/Adreno-EGL( 7474): Local Patches: 
I/Adreno-EGL( 7474): Reconstruct Branch: 
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
V/GLSActivity( 1670): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
W/chromium( 7474): [WARNING:proxy_service.cc(901)] PAC support disabled because there is no system implementation
W/chromium( 7474): [WARNING:data_reduction_proxy_settings.cc(403)] SPDY proxy OFF at startup
I/GLSUser ( 1670): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
I/GLSUser ( 1670): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1670): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1670): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 1670): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
W/art     ( 7474): Attempt to remove local handle scope entry from IRT, ignoring
W/AwContents( 7474): onDetachedFromWindow called when already detached. Ignoring
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
V/BitmapFactory( 1670): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
D/SecContentProvider2(  890): uri = 14 selection = getSealedState
D/SecContentProvider2(  890): mCursor = null
D/SecContentProvider2(  890): KnoxCustomManagerService offline: service is not available
D/ApplicationPolicy(  890): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
V/ApplicationPolicy(  890): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
D/StatusBar( 1169): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
W/GLSActivity( 1670): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1670): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1670): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1670): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1670): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1670): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1670): 	at android.os.Binder.execTransact(Binder.java:446)
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
E/BooksAccountManager( 7396): Authentication error
E/BooksAccountManager( 7396): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 7396): android.accounts.AccountManager.convertErrorToException(AccountManager.java:1893)
E/HttpHelper( 7396): null auth token
I/PhoneStatusBar( 1169): Icon Only
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
D/PanelView( 1169): There is/are notification(s) 
D/PanelView( 1169): There is/are notification(s) 
I/qtaguid ( 7396): Tagging socket 34 with tag 10000000000{256,0} uid -1, pid: 7396, getuid(): 10082
D/SystemWebViewEngine( 7474): CordovaWebView is running on device made by: samsung
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
W/art     ( 7474): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 7474): Attempt to remove local handle scope entry from IRT, ignoring
D/StatusBar.NetworkController( 1169): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02012b/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020471/com.android.systemui:drawable/stat_sys_signal_out mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
D/StatusBar.NetworkController( 1169): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1169): applyOpen
V/BitmapFactory( 1169): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/stat_sys_signal_out.png
D/StatusBar.NetworkController( 1169): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1169): applyOpen
D/StatusBar.NetworkController( 1169): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1169): applyOpen
D/StatusBar.NetworkController( 1169): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1169): applyOpen
I/WifiStateMachine(  890): CMD_RSSI_POLL : calculateWifiScore in!
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
I/WifiStateMachine(  890): CMD_RSSI_POLL : calculateWifiScore out!
I/WifiStateMachine(  890): CMD_RSSI_POLL : out!
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
I/qtaguid ( 7396): Untagging socket 34
W/ApiaryClient( 7396): Error response from books API: {
W/ApiaryClient( 7396):  "error": {
W/ApiaryClient( 7396):   "errors": [
W/ApiaryClient( 7396):    {
W/ApiaryClient( 7396):     "domain": "global",
W/ApiaryClient( 7396):     "reason": "required",
W/ApiaryClient( 7396):     "message": "Login Required",
W/ApiaryClient( 7396):     "locationType": "header",
W/ApiaryClient( 7396):     "location": "Authorization"
W/ApiaryClient( 7396):    }
W/ApiaryClient( 7396):   ],
W/ApiaryClient( 7396):   "code": 401,
W/ApiaryClient( 7396):   "message": "Login Required"
W/ApiaryClient( 7396):  }
W/ApiaryClient( 7396): }
W/ApiaryClient( 7396): errCount = 3: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 7396): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3DS0HXd4TFLU4&nonce=8684919974650991427&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 7396): Headers suppressed
D/ConnectivityService(  890): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
D/Activity( 7474): performCreate Call secproduct feature valuefalse
D/Activity( 7474): performCreate Call debug elastic valuetrue
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
D/OpenGLRenderer( 7474): Render dirty regions requested: true
D/ActivityManager(  890): post active user change for 0
D/KnoxTimeoutHandler(  890): postActiveUserChange for user 0
D/KnoxTimeoutHandler(  890): handleActiveUserChange for user 0
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
I/SurfaceFlinger(  249): id=15 createSurf (1x1),1 flag=404, com.test.thalitest/com.test.thalitest.MainActivity
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
I/OpenGLRenderer( 7474): Initialized EGL, version 1.4
I/OpenGLRenderer( 7474): HWUI protection enabled for context ,  &this =0xa1653060 ,&mEglDisplay = 1 , &mEglConfig = 8 
D/OpenGLRenderer( 7474): Enabling debug mode 0
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
I/SurfaceFlinger(  249): id=8 Removed com.sec.android.app.launcher/com.android.launcher2.Launcher (4/9)
I/SurfaceFlinger(  249): id=8 Removed com.sec.android.app.launcher/com.android.launcher2.Launcher (-2/9)
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
D/InputMethodManagerService(  890): windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
W/ContextImpl(  890): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.android.server.InputMethodManagerService$6.run:2728 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
W/ContextImpl(  890): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.android.server.InputMethodManagerService$6.run:2728 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
I/ActivityManager(  890): Displayed com.test.thalitest/.MainActivity: +682ms
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
I/Timeline( 7474): Timeline: Activity_idle id: android.os.BinderProxy@7d50a7b time:94982
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
D/JsMessageQueue( 7474): Set native->JS mode to OnlineEventsBridgeMode
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
I/chromium( 7474): [INFO:SkUtilsArm.cpp(179)] Device supports ARM NEON instructions!
I/chromium( 7474): 
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
D/CustomFrequencyManagerService(  890): acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1958400  uid : 1000  pid : 890  pkgName : ACTIVITY_RESUME_BOOSTER@10
D/CustomFrequencyManagerService(  890): releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1958400  uid : 1000  pid : 890  tag : ACTIVITY_RESUME_BOOSTER@6
D/CustomFrequencyManagerService(  890): FrequencyrequestList.getNextMaxCPUCoreRequest, index: 0
W/ActivityManager(  890): mDVFSHelper.release()
I/Timeline(  890): Timeline: Activity_windows_visible id: ActivityRecord{2f372d19 u0 com.test.thalitest/.MainActivity t17} time:95187
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
I/SurfaceFlinger(  249): id=14 Removed Starting com.test.thalitest (7/8)
I/SurfaceFlinger(  249): id=14 Removed Starting com.test.thalitest (-2/8)
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
E/Adreno-ES20( 7474): <check_framebuffer_attachment:854>: Invalid texture format! Returning error!
E/Adreno-ES20( 7474): <check_framebuffer_object_status:1237>: Framebuffer color attachment incomplete. Returning GL_FRAMEBUFFER_INCOMPLETE_ATTACHMENT!
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
,D/jxcore_app_log( 7474): JniHelper::setJavaVM(0xb4f5c280), pthread_self() = -1358540544
,D/JX-Cordova( 7474): jxcore cordova android initializing
,D/CustomFrequencyManagerService(  890): releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1958400  uid : 1000  pid : 890  tag : ACTIVITY_RESUME_BOOSTER@10
,D/StatusBar.NetworkController( 1169): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02012b/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020466/com.android.systemui:drawable/stat_sys_signal_inout mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
D/StatusBar.NetworkController( 1169): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1169): applyOpen
D/StatusBar.NetworkController( 1169): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1169): applyOpen
D/StatusBar.NetworkController( 1169): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1169): applyOpen
D/StatusBar.NetworkController( 1169): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1169): applyOpen
,E/BooksSync( 7396): Soft error
E/BooksSync( 7396): com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
E/BooksSync( 7396): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3DS0HXd4TFLU4&nonce=8684919974650991427&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
E/BooksSync( 7396): Headers suppressed
E/BooksSync( 7396): 
E/BooksSync( 7396): com.google.android.apps.books.net.HttpHelper.wrapExceptionBasedOnStatus(HttpHelper.java:212)
E/BooksSync( 7396): Sync error
E/BooksSync( 7396): com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
E/BooksSync( 7396): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3DS0HXd4TFLU4&nonce=8684919974650991427&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
E/BooksSync( 7396): Headers suppressed
E/BooksSync( 7396): 
E/BooksSync( 7396): com.google.android.apps.books.net.HttpHelper.wrapExceptionBasedOnStatus(HttpHelper.java:212)
I/BooksSync( 7396): Finished books sync
,D/ConnectivityService(  890): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SyncManager(  890): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 64613, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,D/ConnectivityService(  890): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/ActivityManager(  890): Killing 6423:com.samsung.android.app.galaxyfinder/u0a34 (adj 15): bgCount ##41
,D/SecContentProvider2(  890): uri = 11 selection = getMyKnoxAdmin
,D/SecContentProvider2(  890): mCursor = null
,D/ConnectivityService(  890): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,W/libprocessgroup(  890): failed to open /acct/uid_10034/pid_6423/cgroup.procs: No such file or directory
,D/PowerManagerService(  890): [api] release WakeLock flags=0x10000006 tag=PowerUI.Notification uid=10059 pid=1169 (0x0)
,I/GAV2    ( 7396): Thread[GAThread,5,main]: No campaign data found.
,D/StatusBar.NetworkController( 1169): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02012b/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020464/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
,D/StatusBar.NetworkController( 1169): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1169): applyOpen
,D/StatusBar.NetworkController( 1169): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1169): applyOpen
D/StatusBar.NetworkController( 1169): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1169): applyOpen
D/StatusBar.NetworkController( 1169): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1169): applyOpen
,W/jxcore-log( 7474): Initializing JXcore engine
,W/jxcore-log( 7474): JXcore engine is ready
,W/jxcore-log( 7474): Starting JXcore engine
,E/auditd  ( 2005): In denial and Property audit_ondenial is set to 1 
,D/SecurityLogAgent:SEDenialService(  890): Got Modify Event and sending Denial Intent foraudit.log
,W/ContextImpl(  890): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.android.server.SEDenialService$AuditFileObserver.onEvent:76 android.os.FileObserver$ObserverThread.onEvent:122 android.os.FileObserver$ObserverThread.observe:-2 android.os.FileObserver$ObserverThread.run:85 
,E/ActivityManager(  890): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  890): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  890): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  890): checkUser: useridlist=null, currentuser=0
,D/SecurityLogAgent:SEDenialService(  890): audit.ondenial set to 0 after sending samsung.intent.action.knox.DENIAL_NOTIFICATION intent
,E/Zygote  ( 7536): MountEmulatedStorage()
,E/Zygote  ( 7536): v2
I/libpersona( 7536): KNOX_SDCARD checking this for 1000
I/libpersona( 7536): KNOX_SDCARD not a persona
,I/ActivityManager(  890): Start proc com.samsung.android.securitylogagent for broadcast com.samsung.android.securitylogagent/.receivers.SeDenialReceiver: pid=7536 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,I/SELinux ( 7536): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
I/SELinux ( 7536): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
E/SELinux ( 7536): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 7536): TimaSignature is unavailable
,D/ActivityThread( 7536): Added TimaKeyStore provider
,D/ResourcesManager( 7536): creating new AssetManager and set to /system/app/SecurityLogAgent/SecurityLogAgent.apk
,D/SecurityLogAgent( 7536):  SeDenialReceiver : Intent Received : samsung.intent.action.knox.DENIAL_NOTIFICATION
,D/SecurityLogAgent( 7536):  SeDenialReceiver : File path = null
,I/ActivityManager(  890): Killing 4694:com.sec.android.app.shealth/u0a35 (adj 15): bgCount ##41
,W/jxcore-log( 7474): Platform android
W/jxcore-log( 7474): 
W/jxcore-log( 7474): Process ARCH arm
W/jxcore-log( 7474): 
,D/SSRM:m  (  890): SIOP:: AP = 380, PST = 424, CUR = 300
,W/libprocessgroup(  890): failed to open /acct/uid_10035/pid_4694/cgroup.procs: No such file or directory
,V/AlarmManager(  890): waitForAlarm result :4
,E/ActivityManager(  890): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  890): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  890): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  890): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 7559): MountEmulatedStorage()
E/Zygote  ( 7559): v2
I/libpersona( 7559): KNOX_SDCARD checking this for 10179
I/libpersona( 7559): KNOX_SDCARD not a persona
,I/ActivityManager(  890): Start proc com.sec.enterprise.knox.cloudmdm.smdms for broadcast com.sec.enterprise.knox.cloudmdm.smdms/.core.AlarmHandler: pid=7559 uid=10179 gids={50179, 9997, 3003, 3002, 1028, 1015, 3001} abi=armeabi-v7a
,I/SELinux ( 7559): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
I/SELinux ( 7559): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 7559): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 7559): TimaSignature is unavailable
,D/ActivityThread( 7559): Added TimaKeyStore provider
,D/ResourcesManager( 7559): creating new AssetManager and set to /system/app/UniversalMDMClient/UniversalMDMClient.apk
,W/ResourcesManager( 7559): Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
,D/UMC:Core( 7559): onCreate(): 
,D/USER_AGENT( 7559): UMC/1.1.39 (SM-G900F) SAFE-5.3 KNOX-2.3
,D/[SAMSUNG SMARCART NATIVE]( 7559): initialize...
,D/[SAMSUNG SMARCART NATIVE]( 7559): DEBUG: connect to PKCS#11 module: libtlc_tz_ccm.so 
,I/CSTORAGE( 7559): ================================================
,I/CSTORAGE( 7559):  CSTORAGE_SKM_LIB v1.0.8
I/CSTORAGE( 7559): ================================================
,I/TZ_CCM_C_GetFunctionList: ( 7559): TZ_CCM_C_GetFunctionList was called
D/[SAMSUNG SMARCART NATIVE]( 7559): FINISHED: initialize rv:0
,E/SMD     (  277): DCD ON
,D/UMC:SecurityUtils( 7559): Loaded server certificates: 0
,D/UMC:SecurityUtils( 7559): Loaded server certificates: 0
,D/UMC:SecurityUtils( 7559): timaVersion on the device: 3.0
,D/UMC:CloudMDMSecurity( 7559): New Flow
,D/TimaService(  890): TIMA3: in ccmRegisterForDefaultCertificate
D/TimaService(  890): TIMA: in getTimaVersion
I/        (  890): CCM JNI: In ccm_register_for_default_cert
I/        (  890): CCM JNI: In ccm_create_slot
I/TZ_CCM_C_Initialize: (  890): DEBUG_CONTAINER_PROBLEM Enter TZ_CCM_C_Initialize_TLC!
I/TZ_CCM_C_Initialize: (  890): pInitArgs 0x6e13c814 has not called C_Init before.
I/TZ_CCM_C_Initialize: (  890): &ctx = 0x9f8c4c1c
I/TLC_TZ_CCM: (  890): creating new ccm context...
I/TLC_TZ_CCM: (  890): initializing ccm context...
I/TLC_TZ_CCM: (  890): root = /firmware/image, root_strlen = 15
I/TLC_TZ_CCM: (  890): process = tz_ccm, process_strlen = 6
I/TZ: client_server_communication(  890): input max_sendmsg_size = 19420
I/TZ: client_server_communication(  890): input max_recvmsg_size = 19420
I/TZ: client_server_communication(  890): root = /firmware/image, root_len = 15
I/TZ: client_server_communication(  890): process = tz_ccm, process_strlen = 6
I/TZ: client_server_communication(  890): aligned max_sendmsg_size = 19456
I/TZ: client_server_communication(  890): aligned max_recvmsg_size = 19456
I/TZ: client_server_communication(  890): Client_Server_Open was called
I/TZ: client_server_communication(  890): IClientServer::IClientServer()
I/TZ: client_server_communication(  890): BpClientServer::BpClientServer()
I/TZ: client_server_communication(  890): IClientServer::~IClientServer()
,I/TZ_CCM_SERVER( 1078): BnCCM::onTransact(0) 16
I/TZ_CCM_SERVER( 1078): OPENSWCONN
I/TZ_CCM_SERVER( 1078): creating new ccm context...
,I/TZ_CCM_SERVER( 1078): initializing ccm context...
I/TZ_CCM_SERVER( 1078): root = /firmware/image, root_strlen = 15
I/TZ_CCM_SERVER( 1078): process = tz_ccm, process_strlen = 6
I/TZ: qc_tlc_communication( 1078): root = /firmware/image, root_len = 15
I/TZ: qc_tlc_communication( 1078): process = tz_ccm, process_strlen = 6
,I/TZ: qc_tlc_communication( 1078): aligned max_sendmsg_size = 19456 = 0x4c00
I/TZ: qc_tlc_communication( 1078): aligned max_recvmsg_size = 19456 = 0x4c00
I/TZ: qc_tlc_communication( 1078): max_message_size = 38912 = 0x9800
D/QSEECOMAPI: ( 1078): QSEECom_get_handle sb_length = 0x9800
,D/QSEECOMAPI: ( 1078): App is not loaded in QSEE
,D/QSEECOMAPI: ( 1078): Loaded image: APP id = 2
,I/TZ: qc_tlc_communication( 1078): TIMA: path = /firmware/image, fname = tz_ccm, tzapp is loaded
,I/TZ: client_server_communication(  890): OpenSWConn(CCM) is successful
I/TZ: client_server_communication(  890): Client_Server_Open succeeded, serverName = CCM
I/TZ_CCM_C_Initialize: (  890): ctx = 0x9de0ca80, comm = 0x8c477628, sendmsg = 0x911ef000, recvmsg = 0x911f3c00
I/TZ_init: (  890): TZ_init: sending initialization request...
I/TZ: client_server_communication(  890): Cmd id = 2, len = 19456
I/TZ: client_server_communication(  890): Calling Communicate()
I/TZ_CCM_SERVER( 1078): BnCCM::onTransact(2) 16
I/TZ_CCM_SERVER( 1078): COMM
,I/TZ_init: (  890): TZ_init: successful initialization
I/TLC_TZ_COMMON: key_db_init: (  890): Exercising TZ_DB_INIT in TLC
,I/TZ: client_server_communication(  890): Cmd id = 17, len = 19456
I/TZ: client_server_communication(  890): Calling Communicate()
,I/TZ_CCM_SERVER( 1078): BnCCM::onTransact(2) 16
I/TZ_CCM_SERVER( 1078): COMM
,I/TZ_COMMON: tlc_key_db_util: (  890): DB Operation suceeded
I/TLC_TZ_CCM: register for default cert: (  890): Exercising TZ_CCM_register_default_TLC
I/TZ: client_server_communication(  890): Cmd id = 25, len = 19456
I/TZ: client_server_communication(  890): Calling Communicate()
,I/TZ_CCM_SERVER( 1078): BnCCM::onTransact(2) 16
I/TZ_CCM_SERVER( 1078): COMM
,I/TLC_TZ_CCM: register for default cert: (  890): TZ_CCM_register_default_TLC_END: DB file size to update is 0
I/TLC_TZ_CCM: register for default cert: (  890): TZ_CCM_register_default_TLC: Slot ID 0 allocated for cid: 0
I/TZ_CCM_C_Finalize: (  890): DEBUG_CONTAINER_PROBLEM Exercising TZ_CCM_C_Finalize_TLC
I/TZ: client_server_communication(  890): Cmd id = 41, len = 19456
I/TZ: client_server_communication(  890): Calling Communicate()
,I/TZ_CCM_SERVER( 1078): BnCCM::onTransact(2) 16
I/TZ_CCM_SERVER( 1078): COMM
,I/TZ: client_server_communication(  890): Client_Server_Close was called
I/TZ_CCM_SERVER( 1078): BnCCM::onTransact(1) 16
I/TZ_CCM_SERVER( 1078): CLOSESWCONN
D/QSEECOMAPI: ( 1078): QSEECom_dealloc_memory 
D/QSEECOMAPI: ( 1078): QSEECom_shutdown_app, app_id = 2
,I/TZ: client_server_communication(  890): Client_Server_Close succeeded
,D/UMC:CloudMDMSecurity( 7559): ccmRegisterForDefaultCertificate: 0
D/UMC:CloudMDMSecurity( 7559): TIMA service call for password change success!!
,D/UMC:AdminManager( 7559): init - start
,D/UMC:AdminManager( 7559): loadAdmins
,D/UMC:AdminManager( 7559): startPolicyHandlers
,I/UMC:TestPolicyHandler( 7559): Setup is called in testpolicyhandler
,D/UMC:AdminManager( 7559): init - end
,V/UMC:AlarmHandler( 7559): Enter loadList
,I/jxcore-log( 7474): JXcore Cordova bridge is ready!
I/jxcore-log( 7474): 
,W/jxcore-log( 7474): JXcore engine is started
,D/GSLBManager( 7559): migrateStoredUrlFromOldPref
,D/GSLBManager( 7559): migrateStoredUrlFromOldPref : Migration Not Needed
,D/UMC:UMCAdmin( 7559): deactivateUMCAdminIfNotRequired : -1
,E/UMC:Utils( 7559): Admin not found in package com.samsung.knoxpb.mdm
D/UMC:UMCAdmin( 7559): deactivateUMCAdmin : -1
D/UMC:UMCAdmin( 7559): isContainer : 0
,W/LicenseLogService(  890): log() failed
,D/EnterpriseDeviceManagerService(  890): isManagedProfileUser(): userId = 0
,E/UMC:UMCAdmin( 7559): No active admin owned by uid 10179
D/UMC:UMCAdmin( 7559): isContainer : 0
,D/UMC:UMCAdmin( 7559): deactivateUMCAdmin - UMC App Admin deactivated
,V/UMC:AlarmHandler( 7559): onReceive :Intent { flg=0x14 cmp=com.sec.enterprise.knox.cloudmdm.smdms/.core.AlarmHandler (has extras) }
,D/QuickStartReceiver( 7559): Msg Id : 2
D/QuickStartReceiver( 7559): model : SM-G900F
D/QuickStartReceiver( 7559): id : 100
,V/GLSActivity( 1670): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1670): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
,I/GLSUser ( 1670): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1670): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1670): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1670): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/Finsky  ( 6565): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,D/Finsky  ( 6565): [1] 5.onFinished: Installation state replication failed.
D/Finsky  ( 6565): [1] 5.onFinished: Scheduling replication attempt 2.
,I/ActivityManager(  890): Killing 6761:com.policydm/1000 (adj 15): bgCount ##41
,I/jxcore-log( 7474): Toggling radios to true
I/jxcore-log( 7474): 
,D/BluetoothAdapter( 7474): enable()
,D/BluetoothAdapter( 7474): enable(): BT is already enabled..!
,D/WifiService(  890): New client listening to asynchronous messages
,W/libprocessgroup(  890): failed to open /acct/uid_1000/pid_6761/cgroup.procs: No such file or directory,
I/WifiManager( 7474): packageName : com.test.thalitest
,D/SecContentProvider(  890): uri = 18 selection = isWifiEnabled
D/SecContentProvider2(  890): uri = 20 selection = isWifiStateChangeAllowed
D/SecContentProvider2(  890): mCursor = null
,D/WifiService(  890): setWifiEnabled: true pid=7474, uid=10200
E/WifiService(  890): Invoking mWifiStateMachine.setWifiEnabled
W/ActivityManager(  890): Permission Denial: getCurrentUser() from pid=7474, uid=10200 requires android.permission.INTERACT_ACROSS_USERS
,W/WifiService(  890): Failed getting userId using ActivityManagerNative
W/WifiService(  890): java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=7474, uid=10200 requires android.permission.INTERACT_ACROSS_USERS
W/WifiService(  890): 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:22619)
W/WifiService(  890): 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2119)
W/WifiService(  890): 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2107)
W/WifiService(  890): 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:223)
W/WifiService(  890): 	at android.os.Binder.execTransact(Binder.java:446)
,D/SettingsProvider(  890): name = wifi_on
,I/WifiService(  890): disconnect: pid=7474, uid=10200
,I/jxcore-log( 7474): Radios toggled
I/jxcore-log( 7474): 
,I/jxcore-log( 7474): My device name is: samsung-SM-G900F
I/jxcore-log( 7474): 
,I/WifiStateMachine(  890): CMD_RSSI_POLL : calculateWifiScore in!
,I/WifiStateMachine(  890): CMD_RSSI_POLL : calculateWifiScore out!
,I/WifiStateMachine(  890): CMD_RSSI_POLL : out!
,I/wpa_supplicant( 1292): [wpa_supplicant_ctrl_iface_process] : DISCONNECT
,I/wpa_supplicant( 1292): CTRL-EVENT-DISCONNECTED bssid=C0.AA.48 reason=3 locally_generated=1
,I/wpa_supplicant( 1292): wlan0: State: COMPLETED -> DISCONNECTED
,I/wpa_supplicant( 1292): CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=C0.AA.48 SSID=4E47373030
I/wpa_supplicant( 1292): wlan0: State: DISCONNECTED -> DISCONNECTED
,E/WifiStateMachine(  890): WifiStateMachine: Leaving Connected state
,I/wpa_supplicant( 1292): reset timer : RESET_TIMER 0
I/wpa_supplicant( 1292): wlan0: Setting scan request: 0 sec 0 usec
I/wpa_supplicant( 1292): Disconnected - do not scan
I/wpa_supplicant( 1292): wlan0: State: DISCONNECTED -> DISCONNECTED
,E/WifiStateMachine(  890): handleNetworkDisconnect: Stopping DHCP and clearing IP stack:handleNetworkDisconnect - access$11200 - exit - invokeExitMethods
E/WifiStateMachine(  890): handleNetworkDisconnect c0:ff:d4:d3:aa:48 config "NG700"WPA_PSK config.bssid any
E/WifiStateMachine(  890): handleNetworkDisconnect "NG700" nid=0
E/WifiConfigStore(  890): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,E/WifiStateMachine(  890): setSuspendOptimizationsNative: 1 true -want true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - stopDhcp - handleNetworkDisconnect
,D/WifiP2pService(  890): InactiveState{ what=143375 }
D/WifiP2pService(  890): P2pEnabledState{ what=143375 }
,D/StatusBar.NetworkController( 1169): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02012b/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020464/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
,D/CommandListener(  272): Clearing all IP addresses on wlan0
,V/NativeCrypto( 1670): Read error: ssl=0xaf11ba00: I/O error during system call, Connection timed out
,V/NativeCrypto( 1670): SSL shutdown failed: ssl=0xaf11ba00: I/O error during system call, Broken pipe
,E/WifiStateMachine(  890): setDetailed state, old =CONNECTED and new state=DISCONNECTED hidden=false
,E/ConnectivityService(  890): updateNetworkInfo()
,D/ConnectivityService(  890): NetworkAgentInfo [WIFI () - 502] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
E/ConnectivityService(  890): updateNetworkInfo()
,D/ConnectivityService(  890): ignoring duplicate network state non-change
,D/ConnectivityService(  890): NetworkAgentInfo [WIFI () - 502] got DISCONNECTED, was satisfying 2
E/WifiConfigStore(  890): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,D/ConnectivityService(  890): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/WifiTrafficPoller(  890): evaluateTrafficStatsPolling
I/CLocInfoService(  890): External Intent Received android.net.wifi.STATE_CHANGE
,E/WifiStateMachine(  890): Start Disconnecting Watchdog 1
D/ConnectivityService(  890): reportBadNetwork(NetworkAgentInfo [WIFI () - 502]) by 10012
,I/wpa_supplicant( 1292): wlan0: Setting scan request: 0 sec 0 usec
I/wpa_supplicant( 1292): P2P: Current p2p state = IDLE
I/wpa_supplicant( 1292): wlan0: State: DISCONNECTED -> SCANNING
I/wpa_supplicant( 1292): CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00.00.00 SSID=
I/wpa_supplicant( 1292): First Scan Start
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  890): ValidatedState{ when=-1ms what=532488 arg1=10012 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  890): DefaultState{ when=-2ms what=532488 arg1=10012 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  890): Forcing reevaluation
,E/WifiStateMachine(  890): ConnectModeState: Network connection lost 
I/wpa_supplicant( 1292): Scan requested (ret=0) - scan timeout 30 seconds
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  890): EvaluatingState{ when=-2ms what=532486 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  890): Validated
,D/StatusBar.NetworkController( 1169): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020498/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020133/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020464/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
,D/StatusBar.NetworkController( 1169): refreshSignalCluster - setNWBoosterIndicators(false)
E/WifiStateMachine(  890): handleNetworkDisconnect: Stopping DHCP and clearing IP stack:handleNetworkDisconnect - access$11200 - processMessage - processMsg
,D/StatusBar.NetworkController( 1169): applyOpen
D/StatusBar.NetworkController( 1169): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1169): applyOpen
D/StatusBar.NetworkController( 1169): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1169): applyOpen
D/StatusBar.NetworkController( 1169): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1169): applyOpen
,E/WifiStateMachine(  890): setSuspendOptimizationsNative: 1 true -want true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - stopDhcp - handleNetworkDisconnect
D/ConnectivityService(  890): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  890): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/WifiP2pService(  890): InactiveState{ what=143375 }
,D/WifiP2pService(  890): P2pEnabledState{ what=143375 }
,I/Hs20UtilService( 1304): Starting #6
,I/Hs20UtilService( 1304): Message received 5007
,D/NearbySettings( 1304): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,V/NearbySettings( 1304): DMSUtil.isNetworkConnected - flag-null, state-null
D/ConnectivityService(  890): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/NearbySettings( 1304): DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,D/StatusBar.NetworkController( 1169): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020498/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020133/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020464/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
D/ConnectivityService(  890): returning getNetworkInfo(networkType - 13) :[type: WIFI_P2P[] - WIFI_P2P, state: UNKNOWN/IDLE, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/NearbySettings( 1304): DMSUtil.isNetworkConnected - P2P: IDLE
,I/NearbySettings( 1304): DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
I/NearbySettings( 1304): MountReceiver.onReceive - Set preference state off
,V/NearbySettings( 1304): MountReceiver.mPrefHandler - 7002
,D/CommandListener(  272): Clearing all IP addresses on wlan0
,D/ConnectivityService(  890): notifyType LOST for NetworkAgentInfo [WIFI () - 502]
D/ConnectivityService(  890): calling update connectivity
D/ConnectivityService(  890):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/EntConnectivity(  890): Not allowed due to - mEnabled false
D/ConnectivityService(  890):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
,D/ConnectivityService(  890): sending notification LOST for NetworkRequest [ id=2, legacyType=-1, [] ]
D/Nat464Xlat(  890): requiresClat: netType=1, connected=false, hasIPv4Address=true
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  890): ValidatedState{ when=0 what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  890): DefaultState{ when=-1ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  890): Disconnected - quitting
D/ConnectivityManager.CallbackHandler( 1169): CM callback handler got msg 524292
,D/ConnectivityService(  890): Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  890): sending new Min Network Score(0): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,D/CSLegacyTypeTracker(  890): Removing agent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{502}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.135/24,fe80::ee1f:72ff:fe18:8b78/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{true} created{true} explicitlySelected{false} }
D/CSLegacyTypeTracker(  890): Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 502] isDefaultNetwork=false
,D/ConnectivityService(  890): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/TelephonyNetworkFactory( 1475): Cellular needs Network for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,D/ConnectivityService(  890): sendStickyBroadcastDelayed: delayMs=500, action=android.net.conn.CONNECTIVITY_CHANGE
,E/WifiStateMachine(  890): setDetailed state, old =DISCONNECTED and new state=DISCONNECTED hidden=false
,D/SmartBondingService(  890): SmartBondingReceiver: onReceive action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,V/NetworkStats(  890): updateIfacesLocked()
D/NtpTrustedTime(  890): currentTimeMillis() cache hit
V/NetworkStats(  890): performPollLocked(flags=0x1)
,D/SmartBondingService(  890): EVENT_UPDATE_SB_STATE called / mDisableBySIOP false
D/SmartBondingService(  890): getSBEnabled() enabled =false
D/SmartBondingService(  890): getSBEnabled() enabled =false
D/SmartBondingService(  890): getSBEnabled() enabled =false
,E/ConnectivityService(  890): EVENT_NETWORK_VALIDATED - isLiveNetworkAgent found mismatched netId: null - NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{502}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.135/24,fe80::ee1f:72ff:fe18:8b78/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{true} created{true} explicitlySelected{false} }
,D/SmartBondingService(  890): getNetworkEnabled : wifi : true mobile : true
,D/NtpTrustedTime(  890): currentTimeMillis() cache hit
,D/StatusBar.NetworkController( 1169): getUpdateDataNetType(): 0
D/StatusBar.NetworkController( 1169): updateDataNetType()
D/StatusBar.NetworkController( 1169): NoService, mRoamingIconId = 0
,D/NetworkStatsFactory(  890): UpdateStatsForKnox
D/ConnectivityService(  890): returning getNetworkInfo(networkType - 28) :[type: MOBILE_ENT1[] - MOBILE_ENT1, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/NtpTrustedTime(  890): currentTimeMillis() cache hit
D/NtpTrustedTime(  890): currentTimeMillis() cache hit
,V/NetworkStats(  890): advisePersistThreshold() given 9223372036854775, clamped to 2097152
D/NtpTrustedTime(  890): currentTimeMillis() cache hit
,D/StatusBar.NetworkController( 1169): updateDataIcon, mDataDirectionIconId = (null) mDataConnected = false
D/StatusBar.NetworkController( 1169): updateTelephonySignalStrength: hasService=false ss=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte
,D/StatusBar.NetworkController( 1169): updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal
D/StatusBar.NetworkController( 1169): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020498/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020133/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020464/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
D/StatusBar.NetworkController( 1169): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1169): applyOpen
D/StatusBar.NetworkController( 1169): refreshSignalCluster - setNWBoosterIndicators(false)
V/NetworkStats(  890): performPollLocked() took 10ms
D/StatusBar.NetworkController( 1169): applyOpen
D/StatusBar.NetworkController( 1169): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1169): applyOpen
D/StatusBar.NetworkController( 1169): refreshSignalCluster - setNWBoosterIndicators(false)
D/NtpTrustedTime(  890): currentTimeMillis() cache hit
D/StatusBar.NetworkController( 1169): applyOpen
,D/WifiStateMachine(  890): updateConfiguredNetworkExpiration - currTime: 1452773837827
D/WifiStateMachine(  890): updateConfiguredNetworkExpiration - AP, "NG700", is not shared AP.
E/WifiStateMachine(  890): SUPPLICANT_STATE_CHANGE_EVENT state=DISCONNECTED -> state= DISCONNECTED debouncing=false
E/WifiStateMachine(  890): setDetailed state, old =DISCONNECTED and new state=DISCONNECTED hidden=false
D/WifiNetworkAgent(  890): NetworkAgent: NetworkAgent channel lost
I/WifiTrafficPoller(  890): evaluateTrafficStatsPolling
I/CLocInfoService(  890): External Intent Received android.net.wifi.STATE_CHANGE
D/StatusBar.NetworkController( 1169): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020498/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020133/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020464/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
E/WifiStateMachine(  890): SUPPLICANT_STATE_CHANGE_EVENT state=SCANNING -> state= SCANNING debouncing=false
E/WifiStateMachine(  890): setDetailed state, old =DISCONNECTED and new state=SCANNING hidden=false
E/WifiStateMachine(  890): setDetailed state send new extra info"NG700"
D/SecContentProvider2(  890): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2(  890): mCursor = null
D/NtpTrustedTime(  890): currentTimeMillis() cache hit
D/NtpTrustedTime(  890): currentTimeMillis() cache hit
I/Hs20UtilService( 1304): Starting #7
I/Hs20UtilService( 1304): Message received 5007
D/SecContentProvider2(  890): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2(  890): mCursor = null
D/NearbySettings( 1304): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
V/NearbySettings( 1304): DMSUtil.isNetworkConnected - flag-null, state-null
D/ConnectivityService(  890): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/NearbySettings( 1304): DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
D/ConnectivityService(  890): returning getNetworkInfo(networkType - 13) :[type: WIFI_P2P[] - WIFI_P2P, state: UNKNOWN/IDLE, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/NearbySettings( 1304): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 1304): DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
I/NearbySettings( 1304): MountReceiver.onReceive - Set preference state off
V/NearbySettings( 1304): MountReceiver.mPrefHandler - 7002
,D/FileWriteThread_Telephony( 1475): FileWriteThread : threadType = 3
D/FileWriteThread_Telephony( 1475): FileWriteThread : threadType = 3
D/FileWriteThread_Telephony( 1475): FileWriteThread : threadType = 3
D/FileWriteThread_Telephony( 1475): FileWriteThread : threadType = 3
D/FileWriteThread_Telephony( 1475): FileWriteThread : threadType = 3
D/FileWriteThread_Telephony( 1475): FileWriteThread : threadType = 3
D/FileWriteThread_Telephony( 1475): FileWriteThread : threadType = 3
D/FileWriteThread_Telephony( 1475): FileWriteThread : threadType = 3
D/FileWriteThread_Telephony( 1475): FileWriteThread : threadType = 3
D/FileWriteThread_Telephony( 1475): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 1475): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 1475): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 1475): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 1475): FileWriteThread : threadType = 3
,D/ConnectivityService(  890): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,I/ApplicationPolicy(  890): updateDataUsageMap
,D/Tethering(  890): MasterInitialState.processMessage what=3
D/SmartBondingService(  890): SmartBondingReceiver: onReceive action=android.net.conn.CONNECTIVITY_CHANGE
D/ConnectivityService(  890): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/SmartBondingService(  890): EVENT_UPDATE_SB_STATE called / mDisableBySIOP false
D/SmartBondingService(  890): getSBEnabled() enabled =false
D/SmartBondingService(  890): getSBEnabled() enabled =false
D/SmartBondingService(  890): getSBEnabled() enabled =false
I/CLocInfoService(  890): External Intent Received android.net.conn.CONNECTIVITY_CHANGE
D/ConnectivityService(  890): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/CLocInfoService(  890): CLoinfo wifi false
,D/ConnectivityService(  890): returning getNetworkInfo(networkType - 0) :[type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
W/SLocation(  890): No Active Data Connection
I/SystemBroadcastReceiver( 7113): [#DCM#] [DCM_Performance] onReceive completed in time  424 microsec. 
D/ConnectivityService(  890): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/ConnectivityService(  890): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/NetworkMonitor( 5347): type=WIFI subType= reason=null isConnected=false
D/accuweather( 2166): [KK AccuPhone]>>> SWW:66 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
D/ConnectivityService(  890): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/ConnectivityService(  890): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/ConnectivityService(  890): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/ConnectivityService(  890): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/SmartBondingService(  890): getNetworkEnabled : wifi : true mobile : true
E/ActivityManager(  890): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  890): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  890): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  890): checkUser: useridlist=null, currentuser=0
I/SystemBroadcastReceiver( 7113): [#DCM#] Calling notifyListeners. 
I/DCMController( 7113): [#DCM#] onIntentReceived eventid = EVENT_NETWORK_CHANGED
,E/Zygote  ( 7615): MountEmulatedStorage()
E/Zygote  ( 7615): v2
,I/libpersona( 7615): KNOX_SDCARD checking this for 1000
I/libpersona( 7615): KNOX_SDCARD not a persona
,I/ActivityManager(  890): Start proc com.sec.pcw.device for broadcast com.sec.pcw.device/.receiver.SYSTEMReceiver: pid=7615 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,I/DCMController( 7113): [#DCM#] setIsConnectedForExtractors 
,I/DBG_DM  ( 3787): [com.wssyncmldm.XDMService(1111/IlIlllIIlIlIIIlIlIll)] WiFi network Connected : false
,I/SELinux ( 7615): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
D/ConnectivityService(  890): returning getNetworkInfo(networkType - 7) :[type: BLUETOOTH[] - BLUETOOTH, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/SELinux ( 7615): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
E/SELinux ( 7615): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/DBG_DM  ( 3787): [com.wssyncmldm.XDMService(1125/lllllIlIlIIIIIIIIlIl)] Bluetooth Data Connected : false
,D/TimaKeyStoreProvider( 7615): TimaSignature is unavailable
,D/ActivityThread( 7615): Added TimaKeyStore provider
,D/ResourcesManager( 7615): creating new AssetManager and set to /system/priv-app/PCWClientS18/PCWClientS18.apk
,I/PCWCLIENTTRACE_LOG( 7615): DEFAULT_LOGON : true
I/PCWCLIENTTRACE_LOG( 7615): DEFAULT_LOGLEVEL : 3
I/PCWCLIENTTRACE_DMDBOpenHelper( 7615): new DMDBOpenHelper instance
,I/PCWCLIENTTRACE_PushUtil( 7615): SPPPushClient is installed : true
I/PCWCLIENTTRACE_PushUtil( 7615): sales region : global
I/PCWCLIENTTRACE_PushUtil( 7615): getPushTypeList : [SPP, GCM]
I/PCWCLIENTTRACE_SYSTEMReceiver( 7615): [onReceive] - android.net.conn.CONNECTIVITY_CHANGE
,I/PCWCLIENTTRACE_SYSTEMReceiver( 7615): noConnectivity : true
,E/ActivityManager(  890): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  890): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  890): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  890): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 7640): MountEmulatedStorage()
I/libpersona( 7640): KNOX_SDCARD checking this for 10002
E/Zygote  ( 7640): v2
I/libpersona( 7640): KNOX_SDCARD not a persona
,I/ActivityManager(  890): Start proc com.sec.android.cloudagent for broadcast com.sec.android.cloudagent/.detector.DetectorReceiver: pid=7640 uid=10002 gids={50002, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  890): Killing 5235:com.sec.spp.push/u0a38 (adj 15): bgCount ##41
,I/SELinux ( 7640): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 7640): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 7640): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 7640): TimaSignature is unavailable
,D/ActivityThread( 7640): Added TimaKeyStore provider
,D/ResourcesManager( 7640): creating new AssetManager and set to /system/priv-app/CloudAgent/CloudAgent.apk
,W/libprocessgroup(  890): failed to open /acct/uid_10038/pid_5235/cgroup.procs: No such file or directory
,I/ActivityManager(  890): Killing 6051:com.samsung.android.sdk.samsunglink/u0a42 (adj 15): bgCount ##41
,E/ActivityManager(  890): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  890): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  890): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  890): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 7658): MountEmulatedStorage()
,E/Zygote  ( 7658): v2
I/libpersona( 7658): KNOX_SDCARD checking this for 1000
I/libpersona( 7658): KNOX_SDCARD not a persona
,I/ActivityManager(  890): Start proc com.sec.android.diagmonagent for broadcast com.sec.android.diagmonagent/.DiagMonRegistrationReceiver: pid=7658 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,I/SELinux ( 7658): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 7658): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 7658): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 7658): TimaSignature is unavailable
,D/ActivityThread( 7658): Added TimaKeyStore provider
,D/ResourcesManager( 7658): creating new AssetManager and set to /system/priv-app/DiagMonAgent/DiagMonAgent.apk
,W/libprocessgroup(  890): failed to open /acct/uid_10042/pid_6051/cgroup.procs: No such file or directory
,I/DIAGMON_AGENT( 7658): [com.sec.android.diagmonagent.DiagMonAgentApplication(41/onCreate)] myUserId : 0
,I/DIAGMON_AGENT( 7658): [com.diagmondm.db.file.XDB(374/llIlIIIIlIIIIIlIlIII)] 
,I/DIAGMON_AGENT( 7658): [com.sec.android.diagmonagent.DiagMonAgentApplication(61/onCreate)] nStatus : 0
,I/DIAGMON_AGENT( 7658): [com.sec.android.diagmonagent.DiagMonAgentApplication(78/onCreate)] DiagMon DM Application Start !
,I/DIAGMON_AGENT( 7658): [lIIllllllllIlIlIllll(17/llIIIIlllllIIllIIllI)] Receive broadcast: android.net.conn.CONNECTIVITY_CHANGE
,I/DIAGMON_AGENT( 7658): [lIIllllllllIlIlIllll(31/llIIIIlllllIIllIIllI)] Running with RegistrationReceiver
,E/ActivityManager(  890): checkUser: useridlist=null, currentuser=0
,I/wpa_supplicant( 1292): nl80211: Received scan results (5 BSSes)
E/ActivityManager(  890): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  890): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  890): checkUser: useridlist=null, currentuser=0
,I/wpa_supplicant( 1292): wlan0: Setting scan request: 8 sec 0 usec
I/wpa_supplicant( 1292): Trying to associate with C0.AA.48 (SSID='4E47373030' freq=2412 MHz)
I/wpa_supplicant( 1292): wlan0: State: SCANNING -> ASSOCIATING
,I/wpa_supplicant( 1292): CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00.00.00 SSID=
E/WifiStateMachine(  890): [1,452,773,838,860 ms] noteScanEnd no scan source
,E/Zygote  ( 7678): MountEmulatedStorage()
,E/Zygote  ( 7678): v2
I/libpersona( 7678): KNOX_SDCARD checking this for 10011
I/libpersona( 7678): KNOX_SDCARD not a persona
,E/WifiStateMachine(  890): wifi setScanResults statecom.android.server.wifi.WifiStateMachine$DisconnectedState@3488a5f8 sup_state=SCANNING debouncing=false
,I/ActivityManager(  890): Start proc com.sec.android.fotaclient for content provider com.sec.android.fotaclient/.log.MasterLogProvider: pid=7678 uid=10011 gids={50011, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,E/WifiStateMachine(  890): SUPPLICANT_STATE_CHANGE_EVENT state=ASSOCIATING -> state= CONNECTING debouncing=false
E/WifiStateMachine(  890): setDetailed state, old =SCANNING and new state=CONNECTING hidden=false
E/WifiStateMachine(  890): setDetailed state send new extra info0x
D/SecContentProvider2(  890): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2(  890): mCursor = null
,I/SELinux ( 7678): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
I/CLocInfoService(  890): External Intent Received android.net.wifi.SCAN_RESULTS
I/SELinux ( 7678): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 7678): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 7678): TimaSignature is unavailable
,D/ActivityThread( 7678): Added TimaKeyStore provider
,I/wpa_supplicant( 1292): wlan0: State: ASSOCIATING -> ASSOCIATED
I/wpa_supplicant( 1292): CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00.00.00 SSID=4E47373030
E/WifiStateMachine(  890): SUPPLICANT_STATE_CHANGE_EVENT state=ASSOCIATED -> state= CONNECTING debouncing=false
I/wpa_supplicant( 1292): Associated with C0.AA.48
E/WifiStateMachine(  890): setDetailed state, old =CONNECTING and new state=CONNECTING hidden=false
,D/SecContentProvider2(  890): uri = 20 selection = getPromptCredentialsEnabled
,D/SecContentProvider2(  890): mCursor = null
,D/ResourcesManager( 7678): creating new AssetManager and set to /system/priv-app/FotaClient/FotaClient.apk
,I/wpa_supplicant( 1292): wlan0: State: ASSOCIATED -> 4WAY_HANDSHAKE
I/wpa_supplicant( 1292): CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=C0.AA.48 SSID=4E47373030
,E/WifiStateMachine(  890): SUPPLICANT_STATE_CHANGE_EVENT state=FOUR_WAY_HANDSHAKE -> state= AUTHENTICATING debouncing=false
,E/WifiStateMachine(  890): setDetailed state, old =CONNECTING and new state=AUTHENTICATING hidden=false
E/WifiStateMachine(  890): setDetailed state send new extra info"NG700"
,D/SecContentProvider2(  890): uri = 20 selection = getPromptCredentialsEnabled
,D/SecContentProvider2(  890): mCursor = null
,I/wpa_supplicant( 1292): wlan0: State: 4WAY_HANDSHAKE -> 4WAY_HANDSHAKE
,I/wpa_supplicant( 1292): wlan0: State: 4WAY_HANDSHAKE -> GROUP_HANDSHAKE
I/wpa_supplicant( 1292): CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=C0.AA.48 SSID=4E47373030
,E/WifiStateMachine(  890): SUPPLICANT_STATE_CHANGE_EVENT state=GROUP_HANDSHAKE -> state= AUTHENTICATING debouncing=false
E/WifiStateMachine(  890): setDetailed state, old =AUTHENTICATING and new state=AUTHENTICATING hidden=false
,I/wpa_supplicant( 1292): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
I/wpa_supplicant( 1292): wlan0: State: GROUP_HANDSHAKE -> COMPLETED
I/wpa_supplicant( 1292): CTRL-EVENT-CONNECTED - Connection to C0.AA.48 completed (auth) [id=0 id_str=]
I/wpa_supplicant( 1292): Blacklist: Clear (temp) 
I/wpa_supplicant( 1292): CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=C0.AA.48 SSID=4E47373030
,D/SecContentProvider2(  890): uri = 20 selection = getPromptCredentialsEnabled
,D/SecContentProvider2(  890): mCursor = null
,E/WifiStateMachine(  890): Network connection established
,D/WifiNative-HAL(  890): callSECApiVoid - ID [50]
,E/WifiStateMachine(  890): setDetailed state, old =AUTHENTICATING and new state=OBTAINING_IPADDR hidden=false
,E/WifiStateMachine(  890): setDetailed state, old =OBTAINING_IPADDR and new state=CONNECTING hidden=false
,I/CLocInfoService(  890): External Intent Received android.net.wifi.STATE_CHANGE
,D/ConnectivityService(  890): registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{false} explicitlySelected{false} }
E/WifiStateMachine(  890): L2ConnectedState c0:ff:d4:d3:aa:48 config "NG700"WPA_PSK config.bssid any
,D/ConnectivityService(  890): Got NetworkAgent Messenger
D/ConnectivityService(  890): hsengiv:checkWhatTypeOfNetwork and the value is false
E/ConnectivityService(  890): updateNetworkInfo()
D/ConnectivityService(  890): NetworkAgentInfo [WIFI () - 503] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
,D/ConnectivityService(  890): NetworkAgent connected
E/WifiStateMachine(  890): L2ConnectedState "NG700" nid=0
E/WifiConfigStore(  890): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,D/StatusBar.NetworkController( 1169): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020498/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020133/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020464/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
,E/WifiStateMachine(  890): enter ObtainingIpState netId=0 "NG700"WPA_PSK  roam=0 static=false watchdog= 1
E/WifiStateMachine(  890): ObtainingIpAddress c0:ff:d4:d3:aa:48 config "NG700"WPA_PSK config.bssid any
E/WifiStateMachine(  890): ObtainingIpAddress "NG700" nid=0
E/WifiConfigStore(  890): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,D/CommandListener(  272): Setting iface cfg
,E/WifiStateMachine(  890): Start Dhcp Watchdog 2
,I/WifiStateMachine(  890): CMD_RSSI_POLL : calculateWifiScore in!
,E/WifiStateMachine(  890): calculateWifiScore() report new score 60
I/WifiStateMachine(  890): calculateWifiScore : sendNetworkScore in!
I/WifiStateMachine(  890): calculateWifiScore : sendNetworkScore out!
I/WifiStateMachine(  890): CMD_RSSI_POLL : calculateWifiScore out!
I/WifiStateMachine(  890): CMD_RSSI_POLL : out!
,D/ConnectivityService(  890): updateNetworkScore for NetworkAgentInfo [WIFI () - 503] to 60
,E/WifiStateMachine(  890): Link configuration changed for netId: 0 old: {LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576} new: {InterfaceName: wlan0 LinkAddresses: []  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0}
,D/ConnectivityService(  890): Update of LinkProperties for NetworkAgentInfo [WIFI () - 503]; created=false
E/WifiStateMachine(  890): updateLinkProperties nid: 0 state: CONNECTING reason: CMD_UPDATE_LINKPROPERTIES
,I/ActivityManager(  890): Killing 6784:com.osp.app.signin/u0a45 (adj 15): bgCount ##41
,I/FOTA_Client( 7678): [com.sec.android.fotaclient.FotaRegisterReceiver(113/onReceive)] Already device registered...
,I/FOTA_Client( 7678): [com.sec.android.fotaclient.FotaUpdaterReceiver(103/onReceive)] Auto update settings is activated
,I/FOTA_Client( 7678): [lllllllllllIlllllIIl(197/lllIlIlIIIllIIlIllIl)] Polling time is vaild
,I/FOTA_Client( 7678): [com.sec.android.fotaclient.FotaUpdaterReceiver(126/onReceive)] Heartbeat settings is activated.
,I/FOTA_Client( 7678): [llIlIIIIlllIlllllIll(125/llIlIIIIlIIIIIlIlIII)] heartbeat time is vaild
,E/ActivityManager(  890): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  890): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  890): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  890): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 7699): MountEmulatedStorage()
E/Zygote  ( 7699): v2
I/libpersona( 7699): KNOX_SDCARD checking this for 10019
I/libpersona( 7699): KNOX_SDCARD not a persona
,I/ActivityManager(  890): Start proc com.samsung.klmsagent for broadcast com.samsung.klmsagent/.listner.MainReciver: pid=7699 uid=10019 gids={50019, 9997, 3003} abi=armeabi-v7a
,I/ActivityManager(  890): Killing 6805:com.sec.android.app.myfiles/u0a51 (adj 15): bgCount ##41
,I/SELinux ( 7699): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,W/libprocessgroup(  890): failed to open /acct/uid_10045/pid_6784/cgroup.procs: No such file or directory
,I/SELinux ( 7699): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 7699): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,E/WifiStateMachine(  890): setSuspendOptimizationsNative: 1 false -want true stack:setSuspendOptimizationsNative - handlePreDhcpSetup - processMessage - processMsg
E/native  (  890): do suspend false
,D/SecContentProvider2(  890): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2(  890): mCursor = null
,D/WifiP2pService(  890): InactiveState{ what=143375 }
D/WifiP2pService(  890): P2pEnabledState{ what=143375 }
,D/TimaKeyStoreProvider( 7699): TimaSignature is unavailable
,D/ActivityThread( 7699): Added TimaKeyStore provider
,W/libprocessgroup(  890): failed to open /acct/uid_10051/pid_6805/cgroup.procs: No such file or directory
,D/ResourcesManager( 7699): creating new AssetManager and set to /system/priv-app/KLMSAgent/KLMSAgent.apk
,I/KLMS-2.4.503: ( 7699): KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,I/KLMS-2.4.503: ( 7699): MainReciver(): EventNotificationReciver- method called: AppActivityListner onReceive for Intent Action : android.net.conn.CONNECTIVITY_CHANGE , timestamp: 1452773839135
,I/KLMS-2.4.503: ( 7699): MainReciver(): NETWORK_STATE_CHANGED_ACTION
,D/ConnectivityService(  890): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  890): returning getNetworkInfo(networkType - 0) :[type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/KLMS-2.4.503: ( 7699): KLMSUtility(): isNetworkAvailable() - WIFI : false| MOBILE : false
,I/KLMS-2.4.503: ( 7699): StateImplV2(): networkChangeListener().END
,I/ActivityManager(  890): Killing 6822:com.sec.android.app.soundalive/u0a58 (adj 15): bgCount ##41
,E/ActivityManager(  890): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  890): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  890): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  890): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 7715): MountEmulatedStorage()
E/Zygote  ( 7715): v2
I/libpersona( 7715): KNOX_SDCARD checking this for 10037
I/libpersona( 7715): KNOX_SDCARD not a persona
,I/ActivityManager(  890): Start proc com.sec.android.soagent for broadcast com.sec.android.soagent/.RegisterReceiver: pid=7715 uid=10037 gids={50037, 9997, 3003} abi=armeabi-v7a
,I/SELinux ( 7715): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 7715): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 7715): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 7715): TimaSignature is unavailable
,D/ActivityThread( 7715): Added TimaKeyStore provider
,D/ResourcesManager( 7715): creating new AssetManager and set to /system/priv-app/SOAgent/SOAgent.apk
,W/libprocessgroup(  890): failed to open /acct/uid_10058/pid_6822/cgroup.procs: No such file or directory
,I/SO_AGENT( 7715): [com.sec.android.soagent.RegisterReceiver(98/onReceive)] Network is not available
,E/ActivityManager(  890): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  890): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  890): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  890): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 7730): MountEmulatedStorage()
E/Zygote  ( 7730): v2
I/libpersona( 7730): KNOX_SDCARD checking this for 1000
I/libpersona( 7730): KNOX_SDCARD not a persona
,I/ActivityManager(  890): Start proc com.policydm for broadcast com.policydm/.XDMBroadcastReceiver: pid=7730 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,I/ActivityManager(  890): Killing 6244:com.samsung.android.app.assistantmenu/1000 (adj 15): bgCount ##41
,I/art     (  317): Explicit concurrent mark sweep GC freed 8752(372KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 14MB/23MB, paused 272us total 13.466ms
,I/art     (  317): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 14MB/23MB, paused 249us total 7.593ms
,I/SELinux ( 7730): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
I/SELinux ( 7730): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
E/SELinux ( 7730): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/art     (  317): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 14MB/23MB, paused 251us total 8.674ms
,D/TimaKeyStoreProvider( 7730): TimaSignature is unavailable
,D/ActivityThread( 7730): Added TimaKeyStore provider
,E/dhcpcd  ( 7748): fopen `/system/etc/dhcpcd/dhcpcd.conf': No such file or directory
,I/dhcpcd  ( 7748): version 5.5.6 starting
,E/dhcpcd  ( 7748): fopen `/system/etc/dhcpcd/dhcpcd.conf': No such file or directory
,D/ResourcesManager( 7730): creating new AssetManager and set to /system/priv-app/SPDClient/SPDClient.apk
,W/libprocessgroup(  890): failed to open /acct/uid_1000/pid_6244/cgroup.procs: No such file or directory
,I/dhcpcd  ( 7748): wlan0: sending IPv6 Router Solicitation
E/dhcpcd  ( 7748): wlan0: sendmsg: Cannot assign requested address
I/dhcpcd  ( 7748): if(wlan0) info get Success. (MAC : C0.AA.48)
I/dhcpcd  ( 7748): bssid match
,I/dhcpcd  ( 7748): wlan0: rebinding lease of 192.168.1.135
,D/ConnectivityService(  890): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  890): returning getNetworkInfo(networkType - 0) :[type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/ActivityManager(  890): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  890): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  890): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  890): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 7764): MountEmulatedStorage()
E/Zygote  ( 7764): v2
I/libpersona( 7764): KNOX_SDCARD checking this for 10038
I/libpersona( 7764): KNOX_SDCARD not a persona
,I/ActivityManager(  890): Start proc com.sec.spp.push for broadcast com.sec.spp.push/.monitor.SystemStateMoniter: pid=7764 uid=10038 gids={50038, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  890): Killing 6490:com.sec.chaton/u0a86 (adj 15): bgCount ##41
,I/SELinux ( 7764): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
I/SELinux ( 7764): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 7764): [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 7764): TimaSignature is unavailable
,D/ActivityThread( 7764): Added TimaKeyStore provider
,D/ResourcesManager( 7764): creating new AssetManager and set to /system/priv-app/SPPPushClient_Prod/SPPPushClient_Prod.apk
,D/ConnectivityService(  890): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  890): returning getNetworkInfo(networkType - 0) :[type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,W/libprocessgroup(  890): failed to open /acct/uid_10086/pid_6490/cgroup.procs: No such file or directory
,E/SPPClientService( 7764): ============PushLog. commonIsShipBuild. stop!
E/SPPClientService( 7764): [PushClientApplication] Push log off : This is Ship build version
,D/SPPClientService( 7764): PushLog.txt file is not deleted.
D/SPPClientService( 7764): PushLog.txt file is not deleted.
D/SPPClientService( 7764): ============PushLog. stop!
,E/SPPClientService( 7764): [[SystemStateMoniter]] SystemStateMonitorService : noConnect? : true
,E/ActivityManager(  890): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  890): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  890): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  890): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 7782): MountEmulatedStorage()
E/Zygote  ( 7782): v2
I/libpersona( 7782): KNOX_SDCARD checking this for 10045
I/libpersona( 7782): KNOX_SDCARD not a persona
,I/ActivityManager(  890): Start proc com.osp.app.signin for broadcast com.osp.app.signin/.OspReceiver: pid=7782 uid=10045 gids={50045, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  890): Killing 6844:com.google.android.apps.docs/u0a98 (adj 15): bgCount ##41
,I/SELinux ( 7782): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 7782): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 7782): [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
,E/SPPClientService( 7764): [[SystemStateMonitorService]] No Active Internet
,D/TimaKeyStoreProvider( 7782): TimaSignature is unavailable
,D/ActivityThread( 7782): Added TimaKeyStore provider
,D/ResourcesManager( 7782): creating new AssetManager and set to /system/priv-app/Samsungservice2_xxhdpi/Samsungservice2_xxhdpi.apk
,W/libprocessgroup(  890): failed to open /acct/uid_10098/pid_6844/cgroup.procs: No such file or directory
,I/SA      ( 7782): [SSP] onCreated
,I/dhcpcd  ( 7748): wlan0: acknowledged 192.168.1.135 from 192.168.1.1
,I/SA      ( 7782): [TPM] There is no property file
,I/SA      ( 7782): [SCU] isHaveSA() - false
,I/SA      ( 7782): [TPM] getModelProperty : null
,I/SA      ( 7782): [TPM] getCSCProperty : null
,I/SA      ( 7782): [DM] init START
,I/SA      ( 7782): [DM] This device is not a Vodafone
,W/ResourceType( 7782): Failure getting entry for 0x7f06000f (t=5 e=15) (error -75)
,W/ResourceType( 7782): Failure getting entry for 0x7f060007 (t=5 e=7) (error -75)
W/ResourceType( 7782): Failure getting entry for 0x7f060008 (t=5 e=8) (error -75)
W/ResourceType( 7782): Failure getting entry for 0x7f06000b (t=5 e=11) (error -75)
,W/ResourceType( 7782): Failure getting entry for 0x7f06000c (t=5 e=12) (error -75)
W/ResourceType( 7782): Failure getting entry for 0x7f060001 (t=5 e=1) (error -75)
,W/ResourceType( 7782): Failure getting entry for 0x7f060013 (t=5 e=19) (error -75)
,W/ResourceType( 7782): No package identifier when getting value for resource number 0x00000000
,W/ResourceType( 7782): Failure getting entry for 0x7f060022 (t=5 e=34) (error -75)
W/ResourceType( 7782): Failure getting entry for 0x7f060023 (t=5 e=35) (error -75)
,W/ResourceType( 7782): Failure getting entry for 0x7f060024 (t=5 e=36) (error -75)
W/ResourceType( 7782): Failure getting entry for 0x7f060025 (t=5 e=37) (error -75)
W/ResourceType( 7782): Failure getting entry for 0x7f060026 (t=5 e=38) (error -75)
,W/ResourceType( 7782): No package identifier when getting value for resource number 0x00000000
,W/ResourceType( 7782): Failure getting entry for 0x7f060010 (t=5 e=16) (error -75)
,W/ResourceType( 7782): Failure getting entry for 0x7f060009 (t=5 e=9) (error -75)
W/ResourceType( 7782): Failure getting entry for 0x7f06000a (t=5 e=10) (error -75)
W/ResourceType( 7782): Failure getting entry for 0x7f060002 (t=5 e=2) (error -75)
,W/ResourceType( 7782): Failure getting entry for 0x7f060014 (t=5 e=20) (error -75)
W/ResourceType( 7782): Failure getting entry for 0x7f060015 (t=5 e=21) (error -75)
,I/SA      ( 7782): [SCU] isHaveSA() - false
I/SA      ( 7782): support phone number id : false
,I/SA      ( 7782): [DM] init END
I/SA      ( 7782): [OR] onReceive log=[SA = 2.1.0142 V = 21 HWD = 1920X1080 3.0 dpi = 480  SIZE = 2 LOCALE = en_US CSC = DBT MCC = 0 MNC 0 T = user DEVICE = klte P = kltexx I = LRX21T M = SM-G900F OKLEFT false DIS LRX21T.G900FXXU1BOD3 PSS = 5.219788042639568  ]
,I/SA      ( 7782): [OR] onReceive Intent=[ conn.CONNECTIVITY_CHANGE. networkInfo:[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] networkType:1 inetCondition:0 extraInfo:? noConnectivity:true ]
I/SA      ( 7782): [OR] == ACTION_CONNECTIVITY_CHANGE ==
,I/SA      ( 7782): [SLFUCHKMGR] constructor called
,I/SA      ( 7782): [TPMU]  strSIMState 	:SIM_STATE_UNKNOWN
I/SA      ( 7782): [OR] == isSIMCardReady false ==
,I/SA      ( 7782): [SCU] == networkStateCheck == false
I/SA      ( 7782): [OR] onReceive END
,I/ActivityManager(  890): Killing 6898:com.vlingo.midas/u0a33 (adj 15): bgCount ##41
,I/dhcpcd  ( 7748): wlan0: leased 192.168.1.135 for 86400 seconds
,E/WifiStateMachine(  890): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: []  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576} new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.135/24,]  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0}
E/WifiStateMachine(  890): updateLinkProperties nid: 0 state: CONNECTING reason: CMD_UPDATE_LINKPROPERTIES v4
D/ConnectivityService(  890): Update of LinkProperties for NetworkAgentInfo [WIFI () - 503]; created=false
,D/accuweather( 7302): [KK AccuPhone]>>> WC:30 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,D/accuweather( 7302): [KK AccuPhone]>>> WC:37 [0:0] oR : create UI manager : start
,D/accuweather( 7302): [KK AccuPhone]>>> UIMEM:90 [0:0] getInstance
,D/accuweather( 7302): [KK AccuPhone]>>> UIMEM:78 [0:0] UIManager : create ui manager
,D/accuweather( 7302): [KK AccuPhone]>>> RM:73 [0:0] RefreshManager : create
,D/accuweather( 7302): [KK AccuPhone]>>> RM:136 [0:0]  V init 
,D/daemonapp( 1328): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/accuweather( 7302): [KK AccuPhone]>>> RM:128 [0:0] updateCityList
,D/daemonapp( 1328): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/weatherinfo
,D/accuweather( 7302): [KK AccuPhone]>>> DBH:3354 [0:0] gADWI : count = 0
,D/daemonapp( 1328): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/accuweather( 7302): [KK AccuPhone]>>> UIMEM:106 [0:0] The widget does not exist in idle!!
,D/accuweather( 7302): [KK AccuPhone]>>> UIMEM:106 [0:0] The widget does not exist in idle!!
,E/ActivityManager(  890): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  890): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  890): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  890): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 7813): MountEmulatedStorage()
I/libpersona( 7813): KNOX_SDCARD checking this for 1000
E/Zygote  ( 7813): v2
I/libpersona( 7813): KNOX_SDCARD not a persona
,I/ActivityManager(  890): Start proc com.sec.knox.bridge for broadcast com.sec.knox.bridge/.knoxusage.KnoxUsageReceiver: pid=7813 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,I/SELinux ( 7813): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 7813): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 7813): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,W/libprocessgroup(  890): failed to open /acct/uid_10033/pid_6898/cgroup.procs: No such file or directory
,D/TimaKeyStoreProvider( 7813): TimaSignature is unavailable
,D/ActivityThread( 7813): Added TimaKeyStore provider
,D/ResourcesManager( 7813): creating new AssetManager and set to /system/app/Bridge/Bridge.apk
,W/ResourcesManager( 7813): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,I/KnoxUsageLogPro( 7813): KnoxUsageReceiver onReceive :android.net.conn.CONNECTIVITY_CHANGE myUserId=0
,I/KnoxUsageLogPro( 7813): premStatus:2
,I/KnoxUsageLogPro( 7813): isEulaShown : false
,I/KnoxUsageLogPro( 7813): KnoxUsageReceiver onReceive : not Processible, just return
,E/ActivityManager(  890): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  890): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  890): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  890): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 7840): MountEmulatedStorage()
E/Zygote  ( 7840): v2
I/libpersona( 7840): KNOX_SDCARD checking this for 10086
I/libpersona( 7840): KNOX_SDCARD not a persona
,I/ActivityManager(  890): Start proc com.sec.chaton for broadcast com.sec.chaton/.receiver.NetStateReceiver: pid=7840 uid=10086 gids={50086, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  890): Killing 6871:com.sec.android.automotive.drivelink/u0a99 (adj 15): bgCount ##41
,I/SELinux ( 7840): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 7840): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 7840): [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 7840): TimaSignature is unavailable
,D/ActivityThread( 7840): Added TimaKeyStore provider
,D/ResourcesManager( 7840): creating new AssetManager and set to /system/app/ChatON_MARKET/ChatON_MARKET.apk
,W/ResourcesManager( 7840): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,W/libprocessgroup(  890): failed to open /acct/uid_10099/pid_6871/cgroup.procs: No such file or directory
,D/PowerManagerService(  890): [s] UserActivityState : 1 -> 2
,D/DisplayPowerController(  890): getFinalBrightness : 14 -> 14
,D/PowerManagerService(  890): [s] DisplayPowerCallbacks : onStateChanged()
,D/PushModule( 7840): [PushClientApplication] (main) PushClientApplication.onCreate()
,I/PushModule( 7840): [PushClientApplication] (main) PushModule version: 0.9.01.12
,D/PushModule( 7840): [PushClientApplication] (main) Discovered public push client. disable in app push client.
,D/lights  (  890): lcd : 15 +
,D/lights  (  890): lcd : 15 -
,E/WifiStateMachine(  890): setSuspendOptimizationsNative: 1 true -want true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - processMessage - processMsg
D/ChatON  ( 7840): [1][isApplicationInstalled] com.android.mms was installed
,D/WifiP2pService(  890): InactiveState{ what=143375 }
,D/WifiP2pService(  890): P2pEnabledState{ what=143375 }
,E/WifiStateMachine(  890): WifiStateMachine DHCP successful
,E/WifiStateMachine(  890): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: [192.168.1.135/24,]  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576} new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.135/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0}
,E/WifiStateMachine(  890): updateLinkProperties nid: 0 state: CONNECTING reason: DHCP_SUCCESS v4 v4r v4dns isprov
D/ConnectivityService(  890): Update of LinkProperties for NetworkAgentInfo [WIFI () - 503]; created=false
D/lights  (  890): lcd : 14 +
D/DisplayPowerController(  890): getFinalBrightness : 14 -> 14
,E/WifiStateMachine(  890): WifiStateMachine: handleSuccessfulIpConfiguration and no scan results"NG700"WPA_PSK
,D/WifiStateMachine(  890): Not connected state, yet.
,E/WifiStateMachine(  890): VerifyingLinkState enter
D/StatusBar.NetworkController( 1169): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020498/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020133/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020464/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
,D/WifiStateMachine(  890): updatePoorNetworkAvoidance - Poor Network Test Enabled / !mIsFmcNetwork : false / true - mPoorNetworkAvoidanceEnabled:disabled
D/WifiStateMachine(  890): updatePoorNetworkDetection - Airplane Mode Off / Mobile Data Enabled / SIM State-Ready / MobilePolicyDataDisabled / !mIsFmcNetwork : 
D/WifiStateMachine(  890): false / true / false / true / true - mPoorNetworkDetectionEnabled: disabled
,D/WifiNative-HAL(  890): callSECApiInt - ID [210]
E/WifiStateMachine(  890): setDetailed state, old =CONNECTING and new state=VERIFYING_POOR_LINK hidden=false
,E/ConnectivityService(  890): updateNetworkInfo()
,D/lights  (  890): lcd : 14 -
D/ConnectivityService(  890): updateLinkProperties: newLp = {InterfaceName: wlan0 LinkAddresses: [192.168.1.135/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}
D/ConnectivityService(  890): Adding iface wlan0 to network 503
D/DisplayPowerController(  890): getFinalBrightness : 14 -> 14
,I/CLocInfoService(  890): External Intent Received android.net.wifi.STATE_CHANGE
,D/WifiWatchdogStateMachine(  890): updateDnsLinkProperty: enter
,D/WifiWatchdogStateMachine.DnsPinger(  890): setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.135/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}
D/WifiWatchdogStateMachine.DnsResolver(  890): setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.135/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}
D/WifiWatchdogStateMachine.SingDnsChecker(  890): setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.135/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}
,D/WifiWatchdogStateMachine.CaptivePortalDnsResolver(  890): setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.135/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}
,W/ContextImpl( 7840): Implicit intents with startService are not safe: Intent { act=com.sec.chaton.push.PUSH_CLIENT_SERVICE_ACTION } android.content.ContextWrapper.startService:533 com.sec.chaton.global.GlobalApplication.onCreate:358 android.app.Instrumentation.callApplicationOnCreate:1020 
D/StatusBar.NetworkController( 1169): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020498/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020133/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020464/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
,W/ActivityManager(  890): Unable to start service Intent { act=com.sec.chaton.push.PUSH_CLIENT_SERVICE_ACTION } U=0: not found
,E/WifiStateMachine(  890): VerifyingLinkState GOOD_LINK_DETECTED: transition to (new) connected (old)captive portal check
,D/WifiStateMachine(  890): Now, connected state.
E/WifiStateMachine(  890): setDetailed state, old =VERIFYING_POOR_LINK and new state=CAPTIVE_PORTAL_CHECK hidden=false
,E/WifiStateMachine(  890): setDetailed state, old =CAPTIVE_PORTAL_CHECK and new state=CONNECTED hidden=false
,I/WifiTrafficPoller(  890): evaluateTrafficStatsPolling
,I/CLocInfoService(  890): External Intent Received android.net.wifi.STATE_CHANGE
,D/StatusBar.NetworkController( 1169): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020498/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020133/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020464/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
,I/WifiTrafficPoller(  890): evaluateTrafficStatsPolling
,I/WifiTrafficPoller(  890): mBoosterFLAG : 0
I/WifiTrafficPoller(  890): current booster mode : FullMode
D/WifiNative-HAL(  890): callSECApiVoid - ID [212]
,I/CLocInfoService(  890): External Intent Received android.net.wifi.STATE_CHANGE
,D/ConnectivityService(  890): Adding Route [fe80::/64 -> :: wlan0] to network 503
,D/StatusBar.NetworkController( 1169): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020498/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020133/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020464/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
,D/StatusBar.NetworkController( 1169): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02012b/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020466/com.android.systemui:drawable/stat_sys_signal_inout mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
D/StatusBar.NetworkController( 1169): refreshSignalCluster - setNWBoosterIndicators(false)
E/WifiStateMachine(  890): Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,D/ConnectivityService(  890): Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 503
,D/StatusBar.NetworkController( 1169): applyOpen
,D/StatusBar.NetworkController( 1169): refreshSignalCluster - setNWBoosterIndicators(false)
D/ConnectivityService(  890): Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 503
,D/StatusBar.NetworkController( 1169): applyOpen
D/StatusBar.NetworkController( 1169): refreshSignalCluster - setNWBoosterIndicators(false)
E/WifiStateMachine(  890): ConnectedState Enter  mScreenOn=true scanperiod=20000
D/StatusBar.NetworkController( 1169): applyOpen
,D/StatusBar.NetworkController( 1169): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1169): applyOpen
,E/ConnectivityService(  890): Unexpected mtu value: 0, wlan0
I/WifiStateMachine(  890): REQUEST_POWER_SAVE_ON
D/ConnectivityService(  890): updateSourceRoutes : add source routing for type : 1
D/ConnectivityService(  890): updateSourceRoutes : add src route for:192.168.1.135
V/        (  272): QcRouteController
,V/        (  272): QcRouteController
,D/ChatON  ( 7840): [1][a] ChatONV isn't installed.
,D/ChatON  ( 7840): [1][a] ChatONVPlugIn.isAvailable()
,V/        (  272): QcRouteController
,E/ActivityManager(  890): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  890): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  890): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  890): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 7871): MountEmulatedStorage()
I/libpersona( 7871): KNOX_SDCARD checking this for 10088
E/Zygote  ( 7871): v2
I/libpersona( 7871): KNOX_SDCARD not a persona
V/        (  272): QcRouteController
,I/ActivityManager(  890): Start proc com.android.chrome for broadcast com.android.chrome/com.google.android.apps.chrome.precache.PrecacheServiceLauncher: pid=7871 uid=10088 gids={50088, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  890): Killing 6932:com.sec.android.provider.logsprovider/u0a20 (adj 15): bgCount ##41
,V/        (  272): QcRouteController
,V/        (  272): QcRouteController
,V/        (  272): QcRouteController
,I/SELinux ( 7871): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 7871): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 7871): [DEBUG] get_category: variable seinfo: chrome sensitivity: NULL, cateogry: NULL
,V/        (  272): QcRouteController
,D/ConnectivityService(  890): Setting Dns servers for network 503 to [/192.168.1.1]
,D/Nat464Xlat(  890): requiresClat: netType=1, connected=false, hasIPv4Address=true
D/ConnectivityService(  890): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 503]
E/ConnectivityService(  890): updateNetworkInfo()
D/ConnectivityService(  890): calling update connectivity
E/ConnectivityService(  890): updateNetworkInfo()
D/ConnectivityService(  890): ignoring duplicate network state non-change
D/ConnectivityService(  890): ignoring duplicate network state non-change
D/ConnectivityService(  890): NetworkAgentInfo [WIFI () - 503] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityService(  890): notifyType PRECHECK for NetworkAgentInfo [WIFI () - 503]
D/ConnectivityService(  890): calling update connectivity
,D/ConnectivityService(  890): rematching NetworkAgentInfo [WIFI () - 503]
D/ConnectivityService(  890):  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityService(  890):   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  890):   checking if request is satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  890): currentScore = 0, newScore = 60
D/ConnectivityService(  890):    accepting network in place of null
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  890): DefaultState{ when=-4ms what=532481 target=com.android.internal.util.StateMachine$SmHandler }
D/ConnectivityService(  890): sending new Min Network Score(60): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  890): Connected
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  890): EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  890): Validated
,D/TimaKeyStoreProvider( 7871): TimaSignature is unavailable
,E/CSLegacyTypeTracker(  890): add() : Adding agent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{503}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.135/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{true} explicitlySelected{false} } for legacy network type 1
D/CSLegacyTypeTracker(  890): Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 503] isDefaultNetwork=true
D/ConnectivityService(  890): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,W/libprocessgroup(  890): failed to open /acct/uid_10020/pid_6932/cgroup.procs: No such file or directory
,D/ConnectivityService(  890): sendStickyBroadcastDelayed: delayMs=500, action=android.net.conn.CONNECTIVITY_CHANGE
,D/ConnectivityService(  890): Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{503}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.135/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{true} explicitlySelected{false} }
D/TelephonyNetworkFactory( 1475): Cellular releasing Network for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,D/ActivityThread( 7871): Added TimaKeyStore provider
,D/SmartBondingService(  890): SmartBondingReceiver: onReceive action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/ConnectivityService(  890): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 503]
D/ConnectivityService(  890): calling update connectivity
D/SmartBondingService(  890): EVENT_UPDATE_SB_STATE called / mDisableBySIOP false
D/SmartBondingService(  890): getSBEnabled() enabled =false
D/SmartBondingService(  890): getSBEnabled() enabled =false
D/ConnectivityService(  890):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/SmartBondingService(  890): getSBEnabled() enabled =false
D/ConnectivityService(  890):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
,V/NetworkStats(  890): updateIfacesLocked()
D/NtpTrustedTime(  890): currentTimeMillis() cache hit
V/NetworkStats(  890): performPollLocked(flags=0x1)
D/SmartBondingService(  890): getNetworkEnabled : wifi : true mobile : true
D/NetworkStatsFactory(  890): UpdateStatsForKnox
,D/ConnectivityService(  890): sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  890): returning getNetworkInfo(networkType - 28) :[type: MOBILE_ENT1[] - MOBILE_ENT1, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/NtpTrustedTime(  890): currentTimeMillis() cache hit
D/ConnectivityService(  890): Validated NetworkAgentInfo [WIFI () - 503]
,D/ConnectivityService(  890): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/StatusBar.NetworkController( 1169): getUpdateDataNetType(): 0
D/StatusBar.NetworkController( 1169): updateDataNetType()
D/StatusBar.NetworkController( 1169): NoService, mRoamingIconId = 0
D/ConnectivityManager.CallbackHandler( 1169): CM callback handler got msg 524290
D/NtpTrustedTime(  890): currentTimeMillis() cache hit
D/NtpTrustedTime(  890): currentTimeMillis() cache hit
V/NetworkStats(  890): advisePersistThreshold() given 9223372036854775, clamped to 2097152
D/NtpTrustedTime(  890): currentTimeMillis() cache hit
,V/NetworkStats(  890): performPollLocked() took 5ms
,D/ConnectivityService(  890): rematching NetworkAgentInfo [WIFI () - 503]
D/ConnectivityService(  890):  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityService(  890):   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  890): Network NetworkAgentInfo [WIFI () - 503] was already satisfying request 1. No change.
,D/ConnectivityService(  890): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 503]
D/ConnectivityService(  890): calling update connectivity
D/ConnectivityService(  890):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/StatusBar.NetworkController( 1169): updateDataIcon, mDataDirectionIconId = (null) mDataConnected = false
D/StatusBar.NetworkController( 1169): updateTelephonySignalStrength: hasService=false ss=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte
D/NtpTrustedTime(  890): currentTimeMillis() cache hit
D/StatusBar.NetworkController( 1169): updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal
,D/StatusBar.NetworkController( 1169): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02012b/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020466/com.android.systemui:drawable/stat_sys_signal_inout mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
D/StatusBar.NetworkController( 1169): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1169): applyOpen
D/StatusBar.NetworkController( 1169): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1169): applyOpen
D/StatusBar.NetworkController( 1169): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1169): applyOpen
D/StatusBar.NetworkController( 1169): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1169): applyOpen
D/ConnectivityService(  890):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
,D/ConnectivityService(  890): sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
,D/ConnectivityService(  890): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,D/ConnectivityManager.CallbackHandler( 1169): CM callback handler got msg 524290
,D/NtpTrustedTime(  890): currentTimeMillis() cache hit
D/NtpTrustedTime(  890): currentTimeMillis() cache hit
,D/ConnectivityService(  890): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/StatusBar.NetworkController( 1169): getUpdateDataNetType(): 0
D/StatusBar.NetworkController( 1169): updateDataNetType()
D/StatusBar.NetworkController( 1169): NoService, mRoamingIconId = 0
,D/StatusBar.NetworkController( 1169): updateDataIcon, mDataDirectionIconId = (null) mDataConnected = false
D/StatusBar.NetworkController( 1169): updateTelephonySignalStrength: hasService=false ss=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte
,D/StatusBar.NetworkController( 1169): updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal
D/StatusBar.NetworkController( 1169): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02012b/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020466/com.android.systemui:drawable/stat_sys_signal_inout mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
,D/ResourcesManager( 7871): creating new AssetManager and set to /system/app/Chrome/Chrome.apk
,I/ActivityManager(  890): Killing 6944:com.samsung.android.intelligenceservice/u0a3 (adj 15): bgCount ##41
,E/SMD     (  277): DCD ON
,D/Headlines( 5508): HeadlinesSystemBroadcastReceiver onReceive android.net.conn.CONNECTIVITY_CHANGE
,D/HeadlinesChannelUtil( 5508): getCountryCode(): countryCode = DE
,D/Headlines( 5508): Breath.onStartCommand : com.samsung.android.internal.headlines.UPDATE_WELCOME_CARD flag : 0
,D/HeadlinesCardManager( 5508): updateCategory : HeadlinesCardManager:updateCategory() category size == 0
D/HeadlinesCardManager( 5508): updateCategory : HeadlinesCardManager:updateCategory() try to query category list
D/Headlines( 5508): queryCategory.  mRequest is not initialized.
D/HeadlinesCardManager( 5508): updateCategory : HeadlinesCardManager:updateCategory() reponse : false
D/HeadlinesCardManager( 5508): requestUpdateNewsWelcomeCard : request update welcome card to content card.
,D/HeadlinesDataCenter( 5508): requestUpdateNewsWelcomeCard !!! no welcome card
E/ActivityManager(  890): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  890): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  890): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  890): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 7901): MountEmulatedStorage()
E/Zygote  ( 7901): v2
I/libpersona( 7901): KNOX_SDCARD checking this for 10128
I/libpersona( 7901): KNOX_SDCARD not a persona
,I/ActivityManager(  890): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=7901 uid=10128 gids={50128, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/SELinux ( 7901): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 7901): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 7901): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 7901): TimaSignature is unavailable
,D/ActivityThread( 7901): Added TimaKeyStore provider
,D/ResourcesManager( 7901): creating new AssetManager and set to /system/app/Newsstand/Newsstand.apk
,W/libprocessgroup(  890): failed to open /acct/uid_10003/pid_6944/cgroup.procs: No such file or directory
,E/Vold    (  248): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  248): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7901): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache
,E/Vold    (  248): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  248): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7901): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/files
,E/Vold    (  248): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  248): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7901): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache
,E/Vold    (  248): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  248): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7901): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/files
,D/ConnectivityService(  890): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/WebViewFactory( 7901): Loading com.google.android.webview version 37 (1726107-arm) (code 119201)
,D/ResourcesManager( 7901): creating new AssetManager and set to /system/app/WebViewGoogle/WebViewGoogle.apk
,I/LibraryLoader( 7901): Loading: webviewchromium
,I/LibraryLoader( 7901): Time to load native libraries: 4 ms (timestamps 845-849)
,I/LibraryLoader( 7901): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 7901): Binding Chromium to main looper Looper (main, tid 1) {3d6df8d4}
,I/LibraryLoader( 7901): Expected native library version number "",actual native library version number ""
,I/chromium( 7901): [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
,D/ConnectivityService(  890): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/ConnectivityService(  890): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/Tethering(  890): MasterInitialState.processMessage what=3
,D/ConnectivityService(  890): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/SmartBondingService(  890): SmartBondingReceiver: onReceive action=android.net.conn.CONNECTIVITY_CHANGE
D/SmartBondingService(  890): SmartBondingReceiver: wifi is connected
D/SmartBondingService(  890): SmartBondingReceiver: wifi ap is not changed
D/ConnectivityService(  890): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  890): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/SmartBondingService(  890): EVENT_UPDATE_SB_STATE called / mDisableBySIOP false
D/SmartBondingService(  890): getSBEnabled() enabled =false
D/SmartBondingService(  890): getSBEnabled() enabled =false
D/SmartBondingService(  890): getSBEnabled() enabled =false
,I/CLocInfoService(  890): External Intent Received android.net.conn.CONNECTIVITY_CHANGE
D/ConnectivityService(  890): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/CLocInfoService(  890): CLocinfo wifi true 
D/ConnectivityService(  890): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SmartBondingService(  890): getNetworkEnabled : wifi : true mobile : true
,D/ConnectivityService(  890): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/ConnectivityService(  890): returning getNetworkInfo(networkType - 0) :[type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  890): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  890): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/ConnectivityService(  890): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  890): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  890): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/accuweather( 2166): [KK AccuPhone]>>> SWW:66 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,D/ConnectivityService(  890): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  890): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  890): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/DBG_DM  ( 3787): [lllllllIlllIIlllIlIl(88/llIIIIlllllIIllIIllI)] WiFi Network is connected
,I/DBG_DM  ( 3787): [com.wssyncmldm.XDMService(1111/IlIlllIIlIlIIIlIlIll)] WiFi network Connected : true
,D/ConnectivityService(  890): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,W/ContextImpl( 2067): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1994 android.content.ContextWrapper.startService:533 com.samsung.SMT.SamsungTTSService.d:-1 com.samsung.SMT.SamsungTTSService.a:-1 com.samsung.SMT.ai.onReceive:-1 
,W/ContextImpl( 2067): Implicit intents with startService are not safe: Intent { act=com.samsung.SMT.UpdateManager.UPDATE_DATA } android.content.ContextWrapper.startService:533 com.samsung.SMT.SamsungTTSService.d:-1 com.samsung.SMT.SamsungTTSService.a:-1 
,D/ConnectivityService(  890): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  890): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  890): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/SystemBroadcastReceiver( 7113): [#DCM#] [DCM_Performance] onReceive completed in time  1239 microsec. 
,I/SystemBroadcastReceiver( 7113): [#DCM#] Calling notifyListeners. 
,I/DCMController( 7113): [#DCM#] onIntentReceived eventid = EVENT_NETWORK_CHANGED
I/DCMController( 7113): [#DCM#] setIsConnectedForExtractors 
,I/DatabaseRebuilderTask( 7113): [#DCM#] postDBrebuildIntent rebuildLocation =  true
,D/ConnectivityService(  890): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  890): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  890): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  890): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/NetworkMonitor( 5347): type=WIFI subType= reason=null isConnected=true
,I/BrowserStartupController( 7901): Initializing chromium process, renderers=0
,W/art     ( 7901): Attempt to remove local handle scope entry from IRT, ignoring
,I/FrameworkService( 7113): [#DCM#] onCreate FrameworkService 
,I/FrameworkService( 7113): [#DCM#] onCreate FrameworkService end 
I/DCMConfig( 7113): [#DCM#] getSuccessState = true
I/FrameworkService( 7113): [#DCM#] onStartCommand(intent= Intent { act=com.samsung.dcm.action.DCM_EXECUTE cmp=com.samsung.dcm/.framework.FrameworkService (has extras) }, startId=1
,I/IntentHandler( 7113): [#DCM#] Intent action= com.samsung.dcm.action.DCM_EXECUTE, startId=1
,W/chromium( 7901): [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
,I/SystemUtils( 7113): [#DCM#] LM: false,AM:680148992
,I/chromium( 7901): [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=41 off=46768 len=2953
,I/chromium( 7901): [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:42 off:229524 len:643667
,D/ConnectivityService(  890): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,W/AudioManagerAndroid( 7901): Requires BLUETOOTH permission
,D/ConnectivityService(  890): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/Adreno-EGL( 7901): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 7901): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 7901): Build Date: 03/03/15 Tue
I/Adreno-EGL( 7901): Local Branch: LA.BF.1.1_RB1_20150108_025_1077123_1158499
I/Adreno-EGL( 7901): Remote Branch: 
I/Adreno-EGL( 7901): Local Patches: 
I/Adreno-EGL( 7901): Reconstruct Branch: 
,I/art     (  890): Explicit concurrent mark sweep GC freed 67639(3MB) AllocSpace objects, 10(290KB) LOS objects, 30% free, 36MB/52MB, paused 1.339ms total 100.840ms
,D/SecContentProvider2(  890): uri = 11 selection = getMyKnoxAdmin
D/SecContentProvider2(  890): mCursor = null
,I/DCMThreadPoolExecutor( 7113): [#DCM#] Task being added DatabaseRebuilderTask
,I/DCMThreadPoolExecutor( 7113): [#DCM#] Task com.samsung.dcm.framework.extractormanager.task.DatabaseRebuilderTask@bd1dfc8 is submitted
I/FrameworkService( 7113): [#DCM#] [DCM_Performance] onStartCommand completed , startId= 1 in time 104510 mirosec. 
,I/DatabaseRebuilderTask( 7113): [#DCM#] createLuceneReader done 
I/DatabaseRebuilderTask( 7113): [#DCM#] resyncLocation   
I/DatabaseRebuilderTask( 7113): [#DCM#] resyncLocation: querying only for documents with deleted = 0 
,I/NSApplication( 7901): Starting up...
,D/ConnectivityService(  890): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/DatabaseRebuilderTask( 7113): [#DCM#] topDocs hits = 0
,I/DatabaseRebuilderTask( 7113): [#DCM#] No of Location data to be added:  0
I/DatabaseRebuilderTask( 7113): [#DCM#] releaseLuceneReader done 
I/DatabaseRebuilderTask( 7113): [#DCM#] Starting media manager do operation 
I/SystemUtils( 7113): [#DCM#] setHeavySharedPref set as  false
,D/ConnectivityService(  890): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/IntentHandler( 7113): [#DCM#] Stopping service with ids up to  1
,I/DCMThreadPoolExecutor( 7113): [#DCM#] afterExecute FutureTask
I/DCMController( 7113): [#DCM#] task finished =  com.samsung.dcm.framework.extractormanager.task.DatabaseRebuilderTask@bd1dfc8
,D/ConnectivityService(  890): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  890): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/ActivityManager(  890): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  890): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  890): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  890): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 7965): MountEmulatedStorage()
,E/Zygote  ( 7965): v2
I/libpersona( 7965): KNOX_SDCARD checking this for 10138
I/libpersona( 7965): KNOX_SDCARD not a persona
,I/ActivityManager(  890): Start proc com.samsung.android.sconnect for broadcast com.samsung.android.sconnect/.periph.PeriphStartReceiver: pid=7965 uid=10138 gids={50138, 9997, 3002, 3001, 1028, 1015, 3003} abi=armeabi-v7a
,I/ActivityManager(  890): Killing 6967:com.samsung.android.app.filterinstaller/1000 (adj 15): bgCount ##41
,I/SELinux ( 7965): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 7965): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 7965): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 7965): TimaSignature is unavailable
,D/ActivityThread( 7965): Added TimaKeyStore provider
,D/ResourcesManager( 7965): creating new AssetManager and set to /system/app/QuickConnect/QuickConnect.apk
,W/ResourcesManager( 7965): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/libprocessgroup(  890): failed to open /acct/uid_1000/pid_6967/cgroup.procs: No such file or directory
W/ResourcesManager( 7965): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
,W/ResourcesManager( 7965): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,D/QuickConnect( 7965): PeriphStartReceiver.onReceive - android.net.conn.CONNECTIVITY_CHANGE
,I/QuickConnect( 7965): PeriphStartReceiver.onReceive - USER_OWNER care CONNECTIVITY_ACTION. run P service
,I/QuickConnect( 7965): PeriphStartReceiver.onReceive - no need to start
,E/ActivityManager(  890): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  890): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  890): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  890): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 7980): MountEmulatedStorage()
,E/Zygote  ( 7980): v2
I/libpersona( 7980): KNOX_SDCARD checking this for 10163
I/libpersona( 7980): KNOX_SDCARD not a persona
,I/ActivityManager(  890): Start proc com.android.email for broadcast com.android.email/.EmailConnectivityManager: pid=7980 uid=10163 gids={50163, 9997, 3003, 1028, 1015, 1023, 3002, 3001, 1003} abi=armeabi-v7a
,I/ActivityManager(  890): Killing 6983:com.samsung.android.app.watchmanagerstub/u0a112 (adj 15): bgCount ##41
,I/SELinux ( 7980): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 7980): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 7980): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 7980): TimaSignature is unavailable
,D/ActivityThread( 7980): Added TimaKeyStore provider
,D/ResourcesManager( 7980): creating new AssetManager and set to /system/app/SecEmail_K/SecEmail_K.apk
,W/ResourcesManager( 7980): Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
,W/ResourcesManager( 7980): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 7980): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager( 7980): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,W/libprocessgroup(  890): failed to open /acct/uid_10112/pid_6983/cgroup.procs: No such file or directory
,D/RCPManagerService(  890): exchangeData() failure , invalid userId
,D/ConnectivityService(  890): NetTransition Wakelock (NetworkAgentInfo [WIFI () - 502] cleared because we found a replacement network
,D/RCPManagerService(  890): exchangeData() failure , invalid userId
,D/RCPManagerService(  890): exchangeData() failure , invalid userId
,E/ActivityManager(  890): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  890): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  890): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  890): checkUser: useridlist=null, currentuser=0
D/RCPManagerService(  890): exchangeData() failure , invalid userId
,I/ActivityManager(  890): Start proc com.sec.android.provider.badge for content provider com.sec.android.provider.badge/.BadgeProvider: pid=8006 uid=10078 gids={50078, 9997} abi=armeabi-v7a
E/Zygote  ( 8006): MountEmulatedStorage()
E/Zygote  ( 8006): v2
I/libpersona( 8006): KNOX_SDCARD checking this for 10078
I/libpersona( 8006): KNOX_SDCARD not a persona
,V/BitmapFactory( 7980): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_015.png
,I/SELinux ( 8006): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,D/ConnectivityService(  890): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/SELinux ( 8006): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
D/ConnectivityService(  890): returning getNetworkInfo(networkType - 0) :[type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/SELinux ( 8006): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,D/RCPManagerService(  890): exchangeData() failure , invalid userId
,D/RCPManagerService(  890): exchangeData() failure , invalid userId
,V/BitmapFactory( 7980): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_000.png
,D/TimaKeyStoreProvider( 8006): TimaSignature is unavailable
,D/ActivityThread( 8006): Added TimaKeyStore provider
,I/ActivityManager(  890): Killing 7001:com.samsung.android.magazine.service/u0a118 (adj 15): bgCount ##41
,V/BitmapFactory( 7980): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_015.png
,V/BitmapFactory( 7980): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_000.png
,V/BitmapFactory( 7980): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_000.png
V/BitmapFactory( 7980): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_001.png
,V/BitmapFactory( 7980): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_002.png
,V/BitmapFactory( 7980): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_003.png
V/BitmapFactory( 7980): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_004.png
,V/BitmapFactory( 7980): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_005.png
,V/BitmapFactory( 7980): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_006.png
,V/BitmapFactory( 7980): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_007.png
,V/BitmapFactory( 7980): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_008.png
,D/ResourcesManager( 8006): creating new AssetManager and set to /system/app/BadgeProvider/BadgeProvider.apk
,D/ConnectivityService(  890): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SecurityLogAgent( 7536): KnoxConfiguration : Current State = 1
,D/SecurityLogAgent( 7536): KnoxConfiguration : Current State Mapping Found 
D/SecurityLogAgent( 7536): StateMachine : Current State = 1
,V/BitmapFactory( 7980): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_010.png
D/ConnectivityService(  890): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SecurityLogAgent( 7536): StateMachine : Changed Current State = 1
,V/BitmapFactory( 7980): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_011.png
,V/BitmapFactory( 7980): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_012.png
,V/BitmapFactory( 7980): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_013.png
,V/BitmapFactory( 7980): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_014.png
,I/ActivityManager(  890): Killing 7019:com.samsung.helphub/1000 (adj 15): bgCount ##41
,V/BitmapFactory( 7980): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_015.png
,D/BadgeProvider( 8006): onCreate
,D/BadgeProvider( 8006): DatabaseHelper
,D/com.peel.receiver.ConnectivityActionReceiver( 1765): ConnectivityActionReceiver onReceive
D/com.peel.receiver.ConnectivityActionReceiver( 1765): 
D/com.peel.receiver.ConnectivityActionReceiver( 1765): 
D/com.peel.receiver.ConnectivityActionReceiver( 1765): country_code: Germany -- rom region: GB
D/com.peel.receiver.ConnectivityActionReceiver( 1765): 
,V/BitmapFactory( 7980): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_000.png
,D/ConnectivityService(  890): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  890): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/BadgeProvider( 8006): query, [selection] : package='com.android.email' AND class='com.android.email.activity.Welcome' AND extraData='base_extra_badge'
,D/com.peel.receiver.ConnectivityActionReceiver( 1765): 
D/com.peel.receiver.ConnectivityActionReceiver( 1765): 
D/com.peel.receiver.ConnectivityActionReceiver( 1765):  network type WIFI path... network offline: false
D/com.peel.receiver.ConnectivityActionReceiver( 1765): 
,D/com.peel.receiver.ConnectivityActionReceiver( 1765): has active network... run services...
D/com.peel.receiver.ConnectivityActionReceiver( 1765): 
D/com.peel.receiver.ConnectivityActionReceiver( 1765): 
D/com.peel.receiver.ConnectivityActionReceiver( 1765): last run: 1452763840817 -- System.currentTimeMillis()-last_run: 10000660
D/com.peel.receiver.ConnectivityActionReceiver( 1765): ... skip 
D/com.peel.receiver.ConnectivityActionReceiver( 1765): ... skip last_72_check
,E/ActivityManager(  890): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  890): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  890): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  890): checkUser: useridlist=null, currentuser=0
,E/WifiStateMachine(  890): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: [192.168.1.135/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576} new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.135/24,fe80::ee1f:72ff:fe18:8b78/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0}
,D/ConnectivityService(  890): Update of LinkProperties for NetworkAgentInfo [WIFI () - 503]; created=true
D/ConnectivityService(  890): updateLinkProperties: newLp = {InterfaceName: wlan0 LinkAddresses: [192.168.1.135/24,fe80::ee1f:72ff:fe18:8b78/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}
D/ConnectivityService(  890): identical MTU - not setting
,D/ConnectivityService(  890): updateSourceRoutes : add source routing for type : 1
D/ConnectivityService(  890): updateSourceRoutes : add src route for:fe80::ee1f:72ff:fe18:8b78
V/        (  272): QcRouteController
E/WifiStateMachine(  890): updateLinkProperties nid: 0 state: CONNECTED reason: CMD_UPDATE_LINKPROPERTIES v4 v4r v4dns isprov
,E/Zygote  ( 8023): MountEmulatedStorage()
I/libpersona( 8023): KNOX_SDCARD checking this for 10178
E/Zygote  ( 8023): v2
I/libpersona( 8023): KNOX_SDCARD not a persona
,I/ActivityManager(  890): Start proc com.samsung.android.service.travel for broadcast com.samsung.android.service.travel/com.samsung.android.travel.bindService.TravelBroadcastReceiver: pid=8023 uid=10178 gids={50178, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,V/BitmapFactory( 7980): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_001.png
,D/SmartBondingService(  890): SmartBondingReceiver: onReceive action=android.net.wifi.LINK_CONFIGURATION_CHANGED
D/ConnectivityService(  890): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/SmartBondingService(  890): EVENT_UPDATE_SB_STATE called / mDisableBySIOP false
D/SmartBondingService(  890): getSBEnabled() enabled =false
D/SmartBondingService(  890): getSBEnabled() enabled =false
D/SmartBondingService(  890): getSBEnabled() enabled =false
,V/BitmapFactory( 7980): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_002.png
,V/BitmapFactory( 7980): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_003.png
,V/BitmapFactory( 7980): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_004.png
,V/        (  272): QcRouteController
,V/BitmapFactory( 7980): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_005.png
,V/BitmapFactory( 7980): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_006.png
,W/NetworkManagementService(  890): route cmd failed: 
W/NetworkManagementService(  890): com.android.server.NativeDaemonConnector$NativeDaemonFailureException: command '72 route replace src v6 wlan0 fe80::ee1f:72ff:fe18:8b78 2 ::' failed with '400 72 -6 route replace default via :: dev wlan0 scope global table 2: RTNETLINK answers: Invalid argument
W/NetworkManagementService(  890): '
W/NetworkManagementService(  890): 	at com.android.server.NativeDaemonConnector.execute(NativeDaemonConnector.java:438)
W/NetworkManagementService(  890): 	at com.android.server.NativeDaemonConnector.executeForList(NativeDaemonConnector.java:371)
W/NetworkManagementService(  890): 	at com.android.server.NativeDaemonConnector.execute(NativeDaemonConnector.java:336)
W/NetworkManagementService(  890): 	at com.android.server.NativeDaemonConnector.execute(NativeDaemonConnector.java:321)
W/NetworkManagementService(  890): 	at com.android.server.NetworkManagementService.replaceSrcRoute(NetworkManagementService.java:2812)
W/NetworkManagementService(  890): 	at com.android.server.ConnectivityService.updateSourceRoutes(ConnectivityService.java:5478)
W/NetworkManagementService(  890): 	at com.android.server.ConnectivityService.updateLinkProperties(ConnectivityService.java:5305)
W/NetworkManagementService(  890): 	at com.android.server.ConnectivityService.access$1800(ConnectivityService.java:230)
W/NetworkManagementService(  890): 	at com.android.server.ConnectivityService$NetworkStateTrackerHandler.handleMessage(ConnectivityService.java:2324)
W/NetworkManagementService(  890): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/NetworkManagementService(  890): 	at android.os.Looper.loop(Looper.java:145)
W/NetworkManagementService(  890): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,D/Nat464Xlat(  890): requiresClat: netType=1, connected=true, hasIPv4Address=true
D/ConnectivityService(  890): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 503]
D/ConnectivityService(  890): calling update connectivity
D/ConnectivityService(  890):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  890):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
,D/ConnectivityService(  890): sending notification IP_CHANGED for NetworkRequest [ id=2, legacyType=-1, [] ]
,V/BitmapFactory( 7980): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_007.png
D/ConnectivityService(  890): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 503]
,D/ConnectivityService(  890): calling update connectivity
V/BitmapFactory( 7980): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_008.png
D/ConnectivityService(  890):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  890):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
,D/ConnectivityService(  890): sending notification IP_CHANGED for NetworkRequest [ id=2, legacyType=-1, [] ]
,V/BitmapFactory( 7980): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_010.png
,V/BitmapFactory( 7980): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_011.png
,V/BitmapFactory( 7980): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_012.png
,V/BitmapFactory( 7980): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_013.png
,V/BitmapFactory( 7980): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_014.png
,V/BitmapFactory( 7980): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_015.png
,V/BitmapFactory( 7980): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/delete_glance_line.pkm
,I/SELinux ( 8023): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 8023): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 8023): [DEBUG] get_category: variable seinfo: shared sensitivity: NULL, cateogry: NULL
,W/libprocessgroup(  890): failed to open /acct/uid_10118/pid_7001/cgroup.procs: No such file or directory
,D/ConnectivityManager.CallbackHandler( 1169): CM callback handler got msg 524295
,D/ConnectivityManager.CallbackHandler( 1169): CM callback handler got msg 524295
,V/BitmapFactory( 7980): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/delete_glance_icon_undo.pkm
,D/BadgeProvider( 8006): sendNotify entered. [uri] : content://com.sec.badge/apps/1
D/BadgeProvider( 8006): sendNotify, [notify] : null
D/BadgeProvider( 8006): update, [uri] : content://com.sec.badge/apps/1
D/BadgeProvider( 8006): update, [BadgeCount] : badgecount=0
D/Launcher.Model( 1490): reloadBadges entered.
D/BadgeProvider( 8006): update, [UpdateCount] : 1
,D/TimaKeyStoreProvider( 8023): TimaSignature is unavailable
,D/ActivityThread( 8023): Added TimaKeyStore provider
,D/ResourcesManager( 8023): creating new AssetManager and set to /system/app/TravelService_K/TravelService_K.apk
W/libprocessgroup(  890): failed to open /acct/uid_1000/pid_7019/cgroup.procs: No such file or directory
,V/BitmapFactory( 7980): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/list_icon_calendar_1.pkm
,V/BitmapFactory( 7980): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/email_attach_icon_etc.pkm
,V/BitmapFactory( 7980): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/list_icon_flag.pkm
V/BitmapFactory( 7980): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/list_icon_complate.pkm
,V/BitmapFactory( 7980): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/list_icon_flag_off_white.pkm
V/BitmapFactory( 7980): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/email_list_attach_icon_star_off.pkm
,V/BitmapFactory( 7980): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/email_list_attach_icon_star_on.pkm
,V/BitmapFactory( 7980): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/list_icon_flag_f.pkm
,V/BitmapFactory( 7980): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/list_icon_complate_f.pkm
,V/BitmapFactory( 7980): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/list_icon_flag_off_f.pkm
,V/BitmapFactory( 7980): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/email_icon_foward.pkm
,V/BitmapFactory( 7980): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/email_icon_foward_focus.pkm
,V/BitmapFactory( 7980): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/list_icon_reply_forward.pkm
,V/BitmapFactory( 7980): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/email_icon_reply.pkm
,V/BitmapFactory( 7980): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/email_icon_reply_focus.pkm
,V/BitmapFactory( 7980): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/list_icon_vip.pkm
,V/BitmapFactory( 7980): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/email_list_high_priority.pkm
,V/BitmapFactory( 7980): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/email_list_low_priority.pkm
,I/ActivityManager(  890): Killing 7054:com.sec.kidsplat.installer/u0a166 (adj 15): bgCount ##41
,V/BitmapFactory( 7980): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/list_icon_server_draft.pkm
V/BitmapFactory( 7980): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/list_icon_client_draft.pkm
,V/BitmapFactory( 7980): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/permission.pkm
,D/ConnectivityService(  890): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,V/BitmapFactory( 7980): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/list_icon_voicemail.pkm
,V/BitmapFactory( 7980): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/list_icon_sms.pkm
V/BitmapFactory( 7980): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/list_icon_sign.pkm
,V/BitmapFactory( 7980): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/list_icon_encryption.pkm
,D/ConnectivityService(  890): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  890): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  890): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  890): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,V/BitmapFactory( 7980): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/tw_expander_open_01_holo_light.pkm
,V/BitmapFactory( 7980): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/tw_expander_close_01_holo_light.pkm
,D/ChimeraCfgMgr( 2447): Loading module com.google.android.gms.kids from APK com.google.android.gms
,D/ConnectivityService(  890): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  890): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ChimeraCfgMgr( 2447): Loading module com.google.android.gms.kids from APK com.google.android.gms
,D/ConnectivityService(  890): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  890): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/WaitQueueForNetworkActivate( 7089): notifyNetworkActivated
,I/GLSUser ( 1670): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: ac2dm
,I/GLSUser ( 1670): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> ac2dm without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1670): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1670): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1670): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/BitmapFactory( 1670): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/common_ic_googleplayservices.png
,W/libprocessgroup(  890): failed to open /acct/uid_10166/pid_7054/cgroup.procs: No such file or directory
,V/BitmapFactory( 1670): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  890): uri = 14 selection = getSealedState
,D/SecContentProvider2(  890): mCursor = null
,D/SecContentProvider2(  890): KnoxCustomManagerService offline: service is not available
,W/ContextImpl( 7089): Implicit intents with startService are not safe: Intent { act=com.sec.knox.containeragent.service.containermanager.ContainerManagerService } android.content.ContextWrapper.bindService:559 com.sec.knox.containeragent.ContainerManager.<init>:49 com.sec.android.app.samsungapps.vlibrary2.knoxmode.KNOXAPI.<init>:20 
,W/ActivityManager(  890): Unable to start service Intent { act=com.sec.knox.containeragent.service.containermanager.ContainerManagerService } U=0: not found
,D/ApplicationPolicy(  890): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
V/ApplicationPolicy(  890): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,W/Kids    ( 2447): [AccountUtils] Account not ready
W/Kids    ( 2447): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/Kids    ( 2447): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/Kids    ( 2447): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/Kids    ( 2447): 	at com.google.android.gms.auth.p.c(SourceFile:550)
W/Kids    ( 2447): 	at com.google.android.gms.auth.p.b(SourceFile:477)
W/Kids    ( 2447): 	at com.google.android.gms.kids.account.k.d(SourceFile:103)
W/Kids    ( 2447): 	at com.google.android.gms.kids.account.p.a(SourceFile:70)
W/Kids    ( 2447): 	at com.google.android.gms.kids.account.t.a(SourceFile:62)
W/Kids    ( 2447): 	at com.google.android.gms.chimera.f.run(SourceFile:179)
W/Kids    ( 2447): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
W/Kids    ( 2447): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
W/Kids    ( 2447): 	at java.lang.Thread.run(Thread.java:818)
D/StatusBar( 1169): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,I/PhoneStatusBar( 1169): Icon Only
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
D/PanelView( 1169): There is/are notification(s) 
D/PanelView( 1169): There is/are notification(s) 
,W/ActivityManager(  890): Unable to start service Intent { cmp=com.android.email/.service.AttachmentDownloadService } U=0: not found
,D/hcjo    ( 7089): AutoUpdateManager:IDLE:execute
,I/Hs20UtilService( 1304): Starting #8
,I/Hs20UtilService( 1304): Message received 5007
,D/NearbySettings( 1304): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,V/NearbySettings( 1304): DMSUtil.isNetworkConnected - flag-null, state-null
D/ConnectivityService(  890): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/NearbySettings( 1304): DMSUtil.isNetworkConnected - WIFI: CONNECTED
D/ConnectivityService(  890): returning getNetworkInfo(networkType - 13) :[type: WIFI_P2P[] - WIFI_P2P, state: UNKNOWN/IDLE, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/NearbySettings( 1304): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 1304): DMSUtil.isNetworkConnected - WIFI-true, Hotspot-false, P2P-false, Eth-false
I/NearbySettings( 1304): MountReceiver.onReceive - Keep current state
,D/InitializeManagerStateMachine( 7089): execute::IDLE:EXECUTE
D/InitializeManagerStateMachine( 7089): exit::IDLE
D/InitializeManagerStateMachine( 7089): entry::NETWORK_CHECK
,D/ConnectivityService(  890): returning getNetworkInfo(networkType - 0) :[type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/ConnectivityService(  890): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/InitializeManagerStateMachine( 7089): execute::NETWORK_CHECK:NETWORK_STATE_OK
D/InitializeManagerStateMachine( 7089): exit::NETWORK_CHECK
D/InitializeManagerStateMachine( 7089): entry::CHECK_COUNTRY_INFO
D/InitializeManagerStateMachine( 7089): execute::CHECK_COUNTRY_INFO:COUNTRY_INFO_OK
D/InitializeManagerStateMachine( 7089): exit::CHECK_COUNTRY_INFO
D/InitializeManagerStateMachine( 7089): entry::SUCCESS
D/hcjo    ( 7089): AutoUpdateManager:INITCHECK:onInitializeSuccess
,I/Hs20UtilService( 1304): Starting #9
,D/hcjo    ( 7089): AutoUpdateTriggerManager:IDLE:notifyNextTime
D/hcjo    ( 7089): AutoUpdateManager:UPD_CHECK_TIMING:onNoUpdateTime
I/Hs20UtilService( 1304): Message received 5007
D/ConnectivityService(  890): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/InitializeManagerStateMachine( 7089): exit::SUCCESS
D/InitializeManagerStateMachine( 7089): entry::IDLE
,D/NearbySettings( 1304): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,I/NearbySettings( 1304): MountReceiver.onReceive - Keep current state
,I/Hs20UtilService( 1304): Starting #10
,I/Hs20UtilService( 1304): Message received 5007
,D/NearbySettings( 1304): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,V/NearbySettings( 1304): DMSUtil.isNetworkConnected - flag-null, state-null
D/ConnectivityService(  890): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/NearbySettings( 1304): DMSUtil.isNetworkConnected - WIFI: CONNECTED
D/ConnectivityService(  890): returning getNetworkInfo(networkType - 13) :[type: WIFI_P2P[] - WIFI_P2P, state: UNKNOWN/IDLE, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/NearbySettings( 1304): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 1304): DMSUtil.isNetworkConnected - WIFI-true, Hotspot-false, P2P-false, Eth-false
I/NearbySettings( 1304): MountReceiver.onReceive - Keep current state
,I/Hs20UtilService( 1304): Starting #11
,I/Hs20UtilService( 1304): Message received 5007
,D/NearbySettings( 1304): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,I/NearbySettings( 1304): MountReceiver.onReceive - Keep current state
,I/WifiStateMachine(  890): callSECApi what=220
D/WifiStateMachine(  890): SEC_COMMAND_ID_GET_FWS_OPEN_AP_CHECK : 0
,I/PCWCLIENTTRACE_PushUtil( 7615): SPPPushClient is installed : true
I/PCWCLIENTTRACE_PushUtil( 7615): sales region : global
I/PCWCLIENTTRACE_PushUtil( 7615): getPushTypeList : [SPP, GCM]
I/PCWCLIENTTRACE_SYSTEMReceiver( 7615): [onReceive] - android.net.conn.CONNECTIVITY_CHANGE
,I/SurfaceFlinger(  249): id=16 createSurf (1x1),1 flag=4, Toast
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
,I/DIAGMON_AGENT( 7658): [lIIllllllllIlIlIllll(17/llIIIIlllllIIllIIllI)] Receive broadcast: android.net.conn.CONNECTIVITY_CHANGE
D/PowerManagerService(  890): [api] acquire WakeLock flags=0x2000000a tag=WindowManager uid=1000 pid=890
I/DIAGMON_AGENT( 7658): [lIIllllllllIlIlIllll(31/llIIIIlllllIIllIIllI)] Running with RegistrationReceiver
,D/DisplayPowerController(  890): getFinalBrightness : 24 -> 24
,D/PowerManagerService(  890): [s] DisplayPowerCallbacks : onStateChanged()
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
,D/lights  (  890): lcd : 22 +
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1169): value : false
,D/lights  (  890): lcd : 22 -
,D/DisplayPowerController(  890): getFinalBrightness : 24 -> 24
D/lights  (  890): lcd : 24 +
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1169): value : false
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1169): value : false
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
,D/lights  (  890): lcd : 24 -
,D/DisplayPowerController(  890): getFinalBrightness : 24 -> 24
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1169): value : false
,I/FOTA_Client( 7678): [com.sec.android.fotaclient.FotaRegisterReceiver(113/onReceive)] Already device registered...
,I/FOTA_Client( 7678): [com.sec.android.fotaclient.FotaUpdaterReceiver(103/onReceive)] Auto update settings is activated
,I/FOTA_Client( 7678): [lllllllllllIlllllIIl(197/lllIlIlIIIllIIlIllIl)] Polling time is vaild
,I/FOTA_Client( 7678): [com.sec.android.fotaclient.FotaUpdaterReceiver(126/onReceive)] Heartbeat settings is activated.
,I/FOTA_Client( 7678): [llIlIIIIlllIlllllIll(125/llIlIIIIlIIIIIlIlIII)] heartbeat time is vaild
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
,I/KLMS-2.4.503: ( 7699): KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,I/KLMS-2.4.503: ( 7699): MainReciver(): EventNotificationReciver- method called: AppActivityListner onReceive for Intent Action : android.net.conn.CONNECTIVITY_CHANGE , timestamp: 1452773841992
,I/KLMS-2.4.503: ( 7699): MainReciver(): NETWORK_STATE_CHANGED_ACTION
,D/ConnectivityService(  890): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/ConnectivityService(  890): returning getNetworkInfo(networkType - 0) :[type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/KLMS-2.4.503: ( 7699): KLMSUtility(): isNetworkAvailable() - WIFI : true| MOBILE : false
,I/KLMS-2.4.503: ( 7699): StateImplV2(): networkChangeListener().START
,I/KLMS-2.4.503: ( 7699): NetworkChangeOperations(): uploadRequestLog().START 
,I/KLMS-2.4.503: ( 7699): StateImplV2(): networkChangeListener().END
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
,I/SO_AGENT( 7715): [com.sec.android.soagent.RegisterReceiver(104/onReceive)] Get Accessory List
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
,I/WifiStateMachine(  890): CMD_RSSI_POLL : calculateWifiScore in!
,I/WifiStateMachine(  890): CMD_RSSI_POLL : calculateWifiScore out!
I/WifiStateMachine(  890): CMD_RSSI_POLL : out!
,D/StatusBar.NetworkController( 1169): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02012b/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020466/com.android.systemui:drawable/stat_sys_signal_inout mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
,D/ConnectivityService(  890): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  890): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/SPPClientService( 7764): [[SystemStateMoniter]] SystemStateMonitorService : noConnect? : false
,I/SA      ( 7782): [OR] onReceive log=[SA = 2.1.0142 V = 21 HWD = 1920X1080 3.0 dpi = 480  SIZE = 2 LOCALE = en_US CSC = DBT MCC = 0 MNC 0 T = user DEVICE = klte P = kltexx I = LRX21T M = SM-G900F OKLEFT false DIS LRX21T.G900FXXU1BOD3 PSS = 5.219788042639568  ]
,I/SA      ( 7782): [OR] onReceive Intent=[ conn.CONNECTIVITY_CHANGE. networkInfo:[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] networkType:1 inetCondition:0 extraInfo:? isDefault:true ]
I/SA      ( 7782): [OR] == ACTION_CONNECTIVITY_CHANGE ==
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
,I/SA      ( 7782): [TPMU]  strSIMState 	:SIM_STATE_UNKNOWN
,I/SA      ( 7782): [OR] == isSIMCardReady false ==
D/ConnectivityService(  890): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/SA      ( 7782): [SCU] == networkStateCheck == true
I/SA      ( 7782): [DM] getCountryCodeFromCSC : DE
,I/SA      ( 7782): isChinaCountryCode : false
I/SA      ( 7782): [SCU] is ChinestModel Data Restricted   : false
I/SA      ( 7782): [OR] == networkStateCheck true ==
,I/SA      ( 7782): [OR] GetMyCountryZoneTask
,I/SA      ( 7782): [OR] onReceive END
,I/SA      ( 7782): [SRS] prepareGetMyCountryZone
,D/ConnectivityService(  890): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
,D/ConnectivityService(  890): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/accuweather( 7302): [KK AccuPhone]>>> WC:30 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,D/accuweather( 7302): [KK AccuPhone]>>> UIMEM:106 [0:0] The widget does not exist in idle!!
,I/SA      ( 7782): [TPMU]  strSIMState 	:SIM_STATE_UNKNOWN
,I/SA      ( 7782): [SSP] query invoked
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
,I/KnoxUsageLogPro( 7813): KnoxUsageReceiver onReceive :android.net.conn.CONNECTIVITY_CHANGE myUserId=0
,I/KnoxUsageLogPro( 7813): premStatus:2
,I/KnoxUsageLogPro( 7813): isEulaShown : false
,I/KnoxUsageLogPro( 7813): KnoxUsageReceiver onReceive : not Processible, just return
I/SA      ( 7782): [TPMU] GetMccFromDB : null
,I/SA      ( 7782): [SCU] getMccFromPreferece mcc = 260
,I/SA      ( 7782): [TPM] isNoProxy(default) : true
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1169): value : false
,D/Headlines( 5508): HeadlinesSystemBroadcastReceiver onReceive android.net.conn.CONNECTIVITY_CHANGE
,D/HeadlinesChannelUtil( 5508): getCountryCode(): countryCode = DE
,D/Headlines( 5508): Breath.onStartCommand : com.samsung.android.internal.headlines.UPDATE_WELCOME_CARD flag : 0
,D/ConnectivityService(  890): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/HeadlinesCardManager( 5508): updateCategory : HeadlinesCardManager:updateCategory() category size == 0
D/HeadlinesCardManager( 5508): updateCategory : HeadlinesCardManager:updateCategory() try to query category list
D/Headlines( 5508): queryCategory.  mRequest is not initialized.
D/HeadlinesCardManager( 5508): updateCategory : HeadlinesCardManager:updateCategory() reponse : false
D/HeadlinesCardManager( 5508): requestUpdateNewsWelcomeCard : request update welcome card to content card.
D/HeadlinesDataCenter( 5508): requestUpdateNewsWelcomeCard !!! no welcome card
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1169): value : false
,D/ConnectivityService(  890): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  890): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/QuickConnect( 7965): PeriphStartReceiver.onReceive - android.net.conn.CONNECTIVITY_CHANGE
,I/QuickConnect( 7965): PeriphStartReceiver.onReceive - USER_OWNER care CONNECTIVITY_ACTION. run P service
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
I/QuickConnect( 7965): PeriphStartReceiver.onReceive - no need to start
,D/ConnectivityService(  890): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/File    ( 7782): fail readDirectory() errno=2
,D/ConnectivityService(  890): returning getNetworkInfo(networkType - 0) :[type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1169): value : false
,D/RCPManagerService(  890): exchangeData() failure , invalid userId
,D/RCPManagerService(  890): exchangeData() failure , invalid userId
,D/ConnectivityService(  890): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SecurityLogAgent( 7536): KnoxConfiguration : Current State = 1
D/SecurityLogAgent( 7536): KnoxConfiguration : Current State Mapping Found 
D/SecurityLogAgent( 7536): StateMachine : Current State = 1
,D/ConnectivityService(  890): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/SecurityLogAgent( 7536): StateMachine : Changed Current State = 1
,D/com.peel.receiver.ConnectivityActionReceiver( 1765): ConnectivityActionReceiver onReceive
D/com.peel.receiver.ConnectivityActionReceiver( 1765): 
D/com.peel.receiver.ConnectivityActionReceiver( 1765): 
D/com.peel.receiver.ConnectivityActionReceiver( 1765): country_code: Germany -- rom region: GB
D/com.peel.receiver.ConnectivityActionReceiver( 1765): 
,D/ConnectivityService(  890): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  890): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/com.peel.receiver.ConnectivityActionReceiver( 1765): 
D/com.peel.receiver.ConnectivityActionReceiver( 1765): 
D/com.peel.receiver.ConnectivityActionReceiver( 1765):  network type WIFI path... network offline: false
D/com.peel.receiver.ConnectivityActionReceiver( 1765): 
D/com.peel.receiver.ConnectivityActionReceiver( 1765): has active network... run services...
D/com.peel.receiver.ConnectivityActionReceiver( 1765): 
D/com.peel.receiver.ConnectivityActionReceiver( 1765): 
D/com.peel.receiver.ConnectivityActionReceiver( 1765): last run: 1452763840817 -- System.currentTimeMillis()-last_run: 10001372
D/com.peel.receiver.ConnectivityActionReceiver( 1765): ... skip 
D/com.peel.receiver.ConnectivityActionReceiver( 1765): ... skip last_72_check
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1169): value : false
,D/ConnectivityService(  890): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1169): value : false
,D/ConnectivityService(  890): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  890): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1169): value : false
,D/ConnectivityService(  890): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  890): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1169): value : false
,D/ChimeraCfgMgr( 2447): Loading module com.google.android.gms.kids from APK com.google.android.gms
,D/ConnectivityService(  890): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ChimeraCfgMgr( 2447): Loading module com.google.android.gms.kids from APK com.google.android.gms
,D/ConnectivityService(  890): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  890): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1169): value : false
,D/ConnectivityService(  890): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/hcjo    ( 7089): AutoUpdateManager:IDLE:execute
,D/InitializeManagerStateMachine( 7089): execute::IDLE:EXECUTE
D/InitializeManagerStateMachine( 7089): exit::IDLE
D/InitializeManagerStateMachine( 7089): entry::NETWORK_CHECK
,D/ConnectivityService(  890): returning getNetworkInfo(networkType - 0) :[type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  890): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/InitializeManagerStateMachine( 7089): execute::NETWORK_CHECK:NETWORK_STATE_OK
D/InitializeManagerStateMachine( 7089): exit::NETWORK_CHECK
D/InitializeManagerStateMachine( 7089): entry::CHECK_COUNTRY_INFO
D/InitializeManagerStateMachine( 7089): execute::CHECK_COUNTRY_INFO:COUNTRY_INFO_OK
,D/InitializeManagerStateMachine( 7089): exit::CHECK_COUNTRY_INFO
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
,D/InitializeManagerStateMachine( 7089): entry::SUCCESS
D/hcjo    ( 7089): AutoUpdateManager:INITCHECK:onInitializeSuccess
,D/hcjo    ( 7089): AutoUpdateTriggerManager:IDLE:notifyNextTime
,D/hcjo    ( 7089): AutoUpdateManager:UPD_CHECK_TIMING:onNoUpdateTime
D/ConnectivityService(  890): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/InitializeManagerStateMachine( 7089): exit::SUCCESS
D/InitializeManagerStateMachine( 7089): entry::IDLE
,I/GLSUser ( 1670): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: ac2dm
I/GLSUser ( 1670): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> ac2dm without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1670): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1670): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1670): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1169): value : false
,V/BitmapFactory( 1670): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  890): uri = 14 selection = getSealedState
,D/SecContentProvider2(  890): mCursor = null
D/SecContentProvider2(  890): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  890): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy(  890): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1169): value : false
,W/Kids    ( 2447): [AccountUtils] Account not ready
W/Kids    ( 2447): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/Kids    ( 2447): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/Kids    ( 2447): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/Kids    ( 2447): 	at com.google.android.gms.auth.p.c(SourceFile:550)
W/Kids    ( 2447): 	at com.google.android.gms.auth.p.b(SourceFile:477)
W/Kids    ( 2447): 	at com.google.android.gms.kids.account.k.d(SourceFile:103)
W/Kids    ( 2447): 	at com.google.android.gms.kids.account.p.a(SourceFile:70)
W/Kids    ( 2447): 	at com.google.android.gms.kids.account.t.a(SourceFile:62)
W/Kids    ( 2447): 	at com.google.android.gms.chimera.f.run(SourceFile:179)
W/Kids    ( 2447): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
W/Kids    ( 2447): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
W/Kids    ( 2447): 	at java.lang.Thread.run(Thread.java:818)
,D/StatusBar( 1169): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,I/PhoneStatusBar( 1169): Icon Only
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
D/PanelView( 1169): There is/are notification(s) 
,D/PanelView( 1169): There is/are notification(s) 
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1169): value : false
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1169): value : false
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1169): value : false
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1169): value : false
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1169): value : false
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1169): value : false
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1169): value : false
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1169): value : false
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1169): value : false
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1169): value : false
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1169): value : false
,I/SA      ( 7782): [RC New] Execute method=[GET] start
,I/SA      ( 7782): [RC New] Security=[true]
,I/System.out( 7782): Thread-1285(ApacheHTTPLog):Reading from variable values from setDefaultValuesToVariables
,I/System.out( 7782): Thread-1285(ApacheHTTPLog):isShipBuild true
,I/System.out( 7782): Thread-1285(ApacheHTTPLog):SmartBonding Enabling is true, SHIP_BUILD is true, log to file is false, DBG is false
,I/SA      ( 7782): [RC New] [v2liruge] api execute + 618
I/SA      ( 7782): [RC New] executeRequest [v2liruge] httpResponse : HTTP/1.1 200 OK
,I/System.out( 7782): AsyncTask #1 calls detatch()
,I/SA      ( 7782): [ODM] saveOpenData( GEO_IP, PL )
,I/SA      ( 7782): [OCP] update openData : PL
,I/SA      ( 7782): [TPMU] getNetworkMcc : 
,I/SA      ( 7782): [SCU] saveMccToPreferece Start
,I/SA      ( 7782): [SCU] RegionMCC : 260
I/SA      ( 7782): [SSP] query invoked
,I/SA      ( 7782): [TPMU] GetMccFromDB : null
,I/SA      ( 7782): [SCU] getMccFromPreferece mcc = 260
I/SA      ( 7782): [SCU] saveMccToPreferece End
,I/SA      ( 7782): [RC New] executeRequest [v2liruge] end. 676
,I/SA      ( 7782): [RC New] Execute end
,I/SA      ( 7782): [OR] GetMyCountryZoneTask mcc = 260
I/SA      ( 7782): [OR] GetMyCountryZoneTask Success
,E/SMD     (  277): DCD ON
,I/WifiStateMachine(  890): REQUEST_POWER_SAVE_ON
,E/WifiStateMachine(  890): CAPTIVE_PORTAL_EVENT_AUTHENTICATED
,I/dhcpcd  ( 7748): wlan0: sending IPv6 Router Solicitation
,E/Watchdog(  890): !@Sync 3
,V/AlarmManager(  890): waitForAlarm result :8
,D/ConnectivityService(  890): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/GLSUser ( 1670): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.googlequicksearchbox, service: oauth2:https://www.googleapis.com/auth/googlenow
,I/GLSUser ( 1670): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/googlenow without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1670): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1670): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1670): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ResourcesManager( 1670): creating new AssetManager and set to /system/priv-app/Velvet/Velvet.apk
,V/BitmapFactory( 1670): DecodeImagePath(decodeResourceStream3) : res/mipmap-xxhdpi-v4/ic_launcher_google_search.png
,V/BitmapFactory( 1670): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  890): uri = 14 selection = getSealedState
,D/SecContentProvider2(  890): mCursor = null
D/SecContentProvider2(  890): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  890): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy(  890): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/StatusBar( 1169): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,I/PhoneStatusBar( 1169): Icon Only
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
D/PanelView( 1169): There is/are notification(s) 
D/PanelView( 1169): There is/are notification(s) 
,W/Search.LoginHelper( 1559): User recoverable exception for scope: oauth2:https://www.googleapis.com/auth/googlenow
,I/jxcore-log( 7474): Test app app.js loaded
I/jxcore-log( 7474): 
,I/chromium( 7474): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,I/Choreographer( 7474): Skipped 428 frames!  The application may be doing too much work on its main thread.
,I/chromium( 7474): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
,I/WifiStateMachine(  890): CMD_RSSI_POLL : calculateWifiScore in!
,I/WifiStateMachine(  890): CMD_RSSI_POLL : calculateWifiScore out!
I/WifiStateMachine(  890): CMD_RSSI_POLL : out!
,E/SQLiteLog( 1670): (10) POSIX Error : 11 SQLite Error : 3850
,D/ConnectivityService(  890): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  890): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
,D/PowerManagerService(  890): [api] [s] userActivity : event: 0 flags: 0 (uid: 1000 pid: 890) eventTime = 105468
,D/PowerManagerService(  890): [s] UserActivityState : 2 -> 1
,D/PowerManagerService(  890): [api] release WakeLock flags=0x2000000a tag=WindowManager uid=1000 pid=890 (0x0)
D/PowerManagerService(  890): [api] applyWakeLockFlagsOnReleaseLocked : userActivityNoUpdateLocked is called : SCREEN_BRIGHT_WAKE_LOCK        'WindowManager' ON_AFTER_RELEASE (uid=1000, pid=890, ws=WorkSource{10059}) (elapsedTime=3481)
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1169): value : false
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1169): value : false
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1169): value : false
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1169): value : false
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1169): value : false
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1169): value : false
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1169): value : false
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
,I/GAV4    ( 7901): Thread[GAThread,5,main]: No campaign data found.
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1169): value : false
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1169): value : false
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1169): value : false
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1169): value : false
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1169): value : false
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1169): value : false
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1169): value : false
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1169): value : false
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1169): value : false
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1169): value : false
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1169): value : false
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1169): value : false
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
,I/SurfaceFlinger(  249): id=16 Removed Toast (8/8)
,I/SurfaceFlinger(  249): id=16 Removed Toast (-2/8)
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1169): value : false
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1169): value : false
,E/SMD     (  277): DCD ON
,I/PCWCLIENTTRACE_SYSTEMReceiver( 7615): mConnectivityHandler : connected
,D/ConnectivityService(  890): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,W/PCWCLIENTTRACE_AccountUtil( 7615): [hasSamungAccount] - No Samsung Account
,I/CSTORAGE( 7615): ================================================
I/CSTORAGE( 7615):  CSTORAGE_SKM_LIB, v1.0.22, MSM8974|MSM8x26|MSM8x10
,I/CSTORAGE( 7615): ================================================
I/PCWCLIENTTRACE_SecurePreferencesJNI( 7615): [GetString-S]
E/art     ( 7615): No implementation found for java.lang.String com.sec.pcw.device.util.SecurePreferencesJNI.getString() (tried Java_com_sec_pcw_device_util_SecurePreferencesJNI_getString and Java_com_sec_pcw_device_util_SecurePreferencesJNI_getString__)
W/PCWCLIENTTRACE_SecurePreferencesJNI( 7615): GetString : secure API is not supported!! No implementation found for java.lang.String com.sec.pcw.device.util.SecurePreferencesJNI.getString() (tried Java_com_sec_pcw_device_util_SecurePreferencesJNI_getString and Java_com_sec_pcw_device_util_SecurePreferencesJNI_getString__)
I/PCWCLIENTTRACE_SecurePreferencesJNI( 7615): [GetString-E]
,I/PCWCLIENTTRACE_PushUtil( 7615): SPPPushClient is installed : true
I/PCWCLIENTTRACE_PushUtil( 7615): sales region : global
I/PCWCLIENTTRACE_PushUtil( 7615): getPushTypeList : [SPP, GCM]
E/PCWCLIENTTRACE_PCWHandler( 7615): [ensureRegistration] - No Samsung account
,D/SSRM:m  (  890): SIOP:: AP = 410, PST = 423, CUR = 300
,D/StatusBar.NetworkController( 1169): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02012b/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020464/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth,
,D/StatusBar.NetworkController( 1169): refreshSignalCluster - setNWBoosterIndicators(false),
,D/StatusBar.NetworkController( 1169): applyOpen
,D/StatusBar.NetworkController( 1169): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1169): applyOpen
,D/StatusBar.NetworkController( 1169): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1169): applyOpen
,D/StatusBar.NetworkController( 1169): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1169): applyOpen
,V/AlarmManager(  890): waitForAlarm result :4
,D/ConnectivityService(  890): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/BatteryService(  890): level:100, scale:100, status:5, health:2, present:true, voltage: 4383, temperature: 285, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  890): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  890): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  890):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  890): Plugged
I/MotionRecognitionService(  890): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1169): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1169): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1169):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3256): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 3256): Disconnected process message: 10
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/ConnectivityService(  890): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  890): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/ConnectivityService(  890): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/dhcpcd  ( 7748): wlan0: sending IPv6 Router Solicitation
,D/PackageManager(  890): [MSG] SEND_PENDING_BROADCAST
,D/ResourcesManager(  890): creating new AssetManager and set to /data/app/com.google.android.gms-1/base.apk
,D/ResourcesManager(  890): creating new AssetManager and set to /system/priv-app/SNS/SNS.apk
,D/ResourcesManager(  890): creating new AssetManager and set to /system/priv-app/Samsungservice2_xxhdpi/Samsungservice2_xxhdpi.apk
,D/ResourcesManager(  890): creating new AssetManager and set to /system/app/ChatON_MARKET/ChatON_MARKET.apk
,D/ResourcesManager(  890): creating new AssetManager and set to /system/app/Dropbox/Dropbox.apk
,D/ResourcesManager(  890): creating new AssetManager and set to /system/app/Gmail2/Gmail2.apk
,D/ResourcesManager(  890): creating new AssetManager and set to /system/app/SBrowser/SBrowser.apk
,D/ResourcesManager(  890): creating new AssetManager and set to /system/app/SecEmail_K/SecEmail_K.apk
,D/ResourcesManager(  890): creating new AssetManager and set to /system/priv-app/InputDevices/InputDevices.apk
,E/ActivityManager(  890): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  890): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  890): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  890): checkUser: useridlist=null, currentuser=0
,I/InputReader(  890): Reconfiguring input devices.  changes=0x00000010
,E/Zygote  ( 8090): MountEmulatedStorage()
E/Zygote  ( 8090): v2
I/libpersona( 8090): KNOX_SDCARD checking this for 10034
I/libpersona( 8090): KNOX_SDCARD not a persona
,I/ActivityManager(  890): Start proc com.samsung.android.app.galaxyfinder for broadcast com.samsung.android.app.galaxyfinder/.ApplicationStatusReceiver: pid=8090 uid=10034 gids={50034, 9997, 1028, 1015, 3003, 3002} abi=armeabi-v7a
,D/ResourcesManager(  890): creating new AssetManager and set to /system/priv-app/GoogleServicesFramework/GoogleServicesFramework.apk
,D/ResourcesManager(  890): creating new AssetManager and set to /system/priv-app/SecContacts/SecContacts.apk
D/ResourcesManager(  890): creating new AssetManager and set to /system/priv-app/SHealth3_5/SHealth3_5.apk
,I/art     (  317): Explicit concurrent mark sweep GC freed 8719(370KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 14MB/23MB, paused 275us total 21.348ms
,I/SELinux ( 8090): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 8090): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 8090): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/art     (  317): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 14MB/23MB, paused 251us total 8.121ms
,D/GCM     ( 1670): Connected
,D/ConnectivityService(  890): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ResourcesManager( 1490): creating new AssetManager and set to /system/app/AccuweatherPhone2014_K_LMR_fHD/AccuweatherPhone2014_K_LMR_fHD.apk
,D/RegisteredServicesCache( 1469): empty dynamic service
,I/Atfwd_Sendcmd(  326): AtCmdFwd service not ready - Exhausted retry attempts - :6
,I/Atfwd_Daemon(  326): result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,D/ConnectivityService(  890): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/art     (  317): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 14MB/23MB, paused 259us total 8.213ms
,D/ConnectivityService(  890): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,W/ResourcesManager( 1490): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 1490): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,W/ResourcesManager( 1490): Asset path '/system/framework/sws.jar' does not exist or contains no resources.
D/ConnectivityService(  890): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ResourcesManager( 1490): creating new AssetManager and set to /system/app/SPlannerWidget_OS_UPG/SPlannerWidget_OS_UPG.apk
,W/ResourcesManager( 1490): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 1490): Asset path '/system/framework/sws.jar' does not exist or contains no resources.
,D/ResourcesManager(  890): creating new AssetManager and set to /system/priv-app/SecGallery2014/SecGallery2014.apk
,D/ConnectivityService(  890): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/GCM     ( 1670): Message class com.google.f.a.a.p
,D/ConnectivityService(  890): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/ResourcesManager(  890): creating new AssetManager and set to /system/priv-app/sCloudSyncCalendar/sCloudSyncCalendar.apk
,W/Resources(  890): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/ResourcesManager(  890): creating new AssetManager and set to /system/priv-app/SecMms_Candy/SecMms_Candy.apk
,D/ResourcesManager(  890): creating new AssetManager and set to /system/priv-app/sCloudSyncContacts/sCloudSyncContacts.apk
,D/ConnectivityService(  890): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ResourcesManager(  890): creating new AssetManager and set to /system/priv-app/sCloudSyncMemo/sCloudSyncMemo.apk
,D/TimaKeyStoreProvider( 8090): TimaSignature is unavailable
,D/ActivityThread( 8090): Added TimaKeyStore provider
,D/ResourcesManager(  890): creating new AssetManager and set to /system/priv-app/sCloudSyncSBrowser/sCloudSyncSBrowser.apk
,D/ResourcesManager(  890): creating new AssetManager and set to /system/priv-app/sCloudSyncSNote3/sCloudSyncSNote3.apk
,D/ResourcesManager(  890): creating new AssetManager and set to /system/app/Books/Books.apk
,D/ResourcesManager(  890): creating new AssetManager and set to /system/app/Chrome/Chrome.apk
,D/ResourcesManager(  890): creating new AssetManager and set to /system/app/Drive/Drive.apk
,D/ResourcesManager( 8090): creating new AssetManager and set to /system/priv-app/SFinder/SFinder.apk
,D/ResourcesManager(  890): creating new AssetManager and set to /system/app/EditorsDocs/EditorsDocs.apk
,D/ResourcesManager(  890): creating new AssetManager and set to /system/app/GoogleCalendarSyncAdapter/GoogleCalendarSyncAdapter.apk
,D/ResourcesManager(  890): creating new AssetManager and set to /system/app/GoogleContactsSyncAdapter/GoogleContactsSyncAdapter.apk
,D/SecContentProvider2(  890): uri = 11 selection = getMyKnoxAdmin
D/SecContentProvider2(  890): mCursor = null
,D/ResourcesManager(  890): creating new AssetManager and set to /system/app/Music2/Music2.apk
,W/Resources(  890): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/ResourcesManager(  890): creating new AssetManager and set to /system/app/Newsstand/Newsstand.apk
,D/ResourcesManager(  890): creating new AssetManager and set to /system/app/PlusOne/PlusOne.apk
,D/ResourcesManager(  890): creating new AssetManager and set to /system/app/SecExchange/SecExchange.apk
,D/ResourcesManager(  890): creating new AssetManager and set to /system/app/Videos/Videos.apk
,I/FeatureConfig( 8090): init() refresh[false], Select[false], DisplayOrder[false], HelpMenu[false]
,W/Resources(  890): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/ResourcesManager(  890): creating new AssetManager and set to /system/app/SecMemoDL/SecMemoDL.apk
,W/Resources(  890): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/BackupManagerService(  890): Received broadcast Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.sec.enterprise.knox.cloudmdm.smdms flg=0x4000010 (has extras) }
,D/ResourcesManager(  890): creating new AssetManager and set to /system/app/YouTube/YouTube.apk
,D/ResourcesManager(  890): creating new AssetManager and set to /system/priv-app/SFinder/SFinder.apk
,W/Resources(  890): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources(  890): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources(  890): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/ResourcesManager(  890): creating new AssetManager and set to /system/app/InteractiveTutorial/InteractiveTutorial.apk
,W/Resources(  890): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/ResourcesManager(  890): creating new AssetManager and set to /system/app/PlayGames/PlayGames.apk
,D/ResourcesManager(  890): creating new AssetManager and set to /system/app/SPlanner_OS_UPG/SPlanner_OS_UPG.apk
,W/ResourcesManager(  890): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
,W/ResourcesManager(  890): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager(  890): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,W/Resources(  890): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/ResourcesManager(  890): creating new AssetManager and set to /system/app/SmartRemote_KL/SmartRemote_KL.apk
,D/ResourcesManager(  890): creating new AssetManager and set to /data/app/de.pizza-1/base.apk
,D/ResourcesManager(  890): creating new AssetManager and set to /data/app/de.kaufda.android-1/base.apk
,D/ResourcesManager(  890): creating new AssetManager and set to /system/priv-app/Velvet/Velvet.apk
,D/ResourcesManager(  890): creating new AssetManager and set to /system/priv-app/SamsungMusic_20/SamsungMusic_20.apk
,W/Resources(  890): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources(  890): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources(  890): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources(  890): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,D/ResourcesManager(  890): creating new AssetManager and set to /system/priv-app/SecMyFiles2014/SecMyFiles2014.apk
,W/Resources(  890): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/ResourcesManager(  890): creating new AssetManager and set to /system/priv-app/SecVideoPlayer/SecVideoPlayer.apk
,W/Resources(  890): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources(  890): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,D/ResourcesManager(  890): creating new AssetManager and set to /system/priv-app/VoiceNote/VoiceNote.apk
,W/Resources(  890): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources(  890): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,W/Resources(  890): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/ResourcesManager( 8090): creating new AssetManager and set to /system/priv-app/SecMms_Candy/SecMms_Candy.apk
,W/ResourcesManager( 8090): Asset path '/system/framework/minimode.jar' does not exist or contains no resources.
,W/ResourcesManager( 8090): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 8090): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager( 8090): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 8090): Asset path '/system/framework/imsmanager.jar' does not exist or contains no resources.
,D/ResourcesManager( 8090): creating new AssetManager and set to /system/priv-app/SecSettings/SecSettings.apk
,W/ResourcesManager( 8090): Asset path '/system/framework/sec_platform_library.jar' does not exist or contains no resources.
,W/ResourcesManager( 8090): Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
W/ResourcesManager( 8090): Asset path '/system/framework/secvisualeffect.jar' does not exist or contains no resources.
W/ResourcesManager( 8090): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 8090): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 8090): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,W/ResourcesManager( 8090): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,D/ResourcesManager( 8090): creating new AssetManager and set to /system/app/ChatON_MARKET/ChatON_MARKET.apk
,W/ResourcesManager( 8090): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,D/ResourcesManager( 8090): creating new AssetManager and set to /system/app/InteractiveTutorial/InteractiveTutorial.apk
,D/ResourcesManager( 8090): creating new AssetManager and set to /system/app/SPlanner_OS_UPG/SPlanner_OS_UPG.apk
,W/ResourcesManager( 8090): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 8090): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 8090): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,D/ResourcesManager( 8090): creating new AssetManager and set to /system/priv-app/SecContacts/SecContacts.apk
,W/ResourcesManager( 8090): Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
W/ResourcesManager( 8090): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 8090): Asset path '/system/framework/imsmanager.jar' does not exist or contains no resources.
,D/ResourcesManager( 8090): creating new AssetManager and set to /system/priv-app/SecGallery2014/SecGallery2014.apk
,W/ResourcesManager( 8090): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 8090): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 8090): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager( 8090): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,W/ResourcesManager( 8090): Asset path '/system/framework/secimaging.jar' does not exist or contains no resources.
W/ResourcesManager( 8090): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
W/ResourcesManager( 8090): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
,W/ResourcesManager( 8090): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,D/ResourcesManager( 8090): creating new AssetManager and set to /system/priv-app/SecMyFiles2014/SecMyFiles2014.apk
,W/ResourcesManager( 8090): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 8090): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
,D/ResourcesManager( 8090): creating new AssetManager and set to /system/priv-app/SecVideoPlayer/SecVideoPlayer.apk
,W/ResourcesManager( 8090): Asset path '/system/framework/minimode.jar' does not exist or contains no resources.
W/ResourcesManager( 8090): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 8090): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager( 8090): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 8090): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
,D/ResourcesManager( 8090): creating new AssetManager and set to /system/app/SBrowser/SBrowser.apk
,W/ResourcesManager( 8090): Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
W/ResourcesManager( 8090): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 8090): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,D/ResourcesManager( 8090): creating new AssetManager and set to /system/app/SecEmail_K/SecEmail_K.apk
,W/ResourcesManager( 8090): Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
,W/ResourcesManager( 8090): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 8090): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager( 8090): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,D/ResourcesManager( 8090): creating new AssetManager and set to /system/app/SecMemoDL/SecMemoDL.apk
,W/ResourcesManager( 8090): Asset path '/system/framework/secmediarecorder.jar' does not exist or contains no resources.
W/ResourcesManager( 8090): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
,D/ResourcesManager( 8090): creating new AssetManager and set to /system/app/Chrome/Chrome.apk
,I/WifiStateMachine(  890): CMD_RSSI_POLL : calculateWifiScore in!
,D/ResourcesManager( 8090): creating new AssetManager and set to /system/priv-app/SamsungMusic_20/SamsungMusic_20.apk
,I/WifiStateMachine(  890): CMD_RSSI_POLL : calculateWifiScore out!
I/WifiStateMachine(  890): CMD_RSSI_POLL : out!
,W/ResourcesManager( 8090): Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
,W/ResourcesManager( 8090): Asset path '/system/framework/secvisualeffect.jar' does not exist or contains no resources.
W/ResourcesManager( 8090): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 8090): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager( 8090): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,W/ResourcesManager( 8090): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
,D/ResourcesManager( 8090): creating new AssetManager and set to /system/priv-app/VoiceNote/VoiceNote.apk
,W/ResourcesManager( 8090): Asset path '/system/framework/secmediarecorder.jar' does not exist or contains no resources.
,W/ResourcesManager( 8090): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,E/ActivityManager(  890): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  890): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  890): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  890): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 8121): MountEmulatedStorage()
E/Zygote  ( 8121): v2
I/libpersona( 8121): KNOX_SDCARD checking this for 10035
I/libpersona( 8121): KNOX_SDCARD not a persona
,I/ActivityManager(  890): Start proc com.sec.android.app.shealth for broadcast com.sec.android.app.shealth/.receiver.InstalledReceiver: pid=8121 uid=10035 gids={50035, 9997, 3003, 1028, 1015, 3001, 3002} abi=armeabi-v7a
,I/ActivityManager(  890): Killing 6611:com.google.android.gms:car/u0a12 (adj 15): bgCount ##41
,I/SELinux ( 8121): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
I/SELinux ( 8121): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
E/SELinux ( 8121): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,D/StatusBar.NetworkController( 1169): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02012b/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020466/com.android.systemui:drawable/stat_sys_signal_inout mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
D/StatusBar.NetworkController( 1169): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1169): applyOpen
,D/StatusBar.NetworkController( 1169): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1169): applyOpen
,D/StatusBar.NetworkController( 1169): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1169): applyOpen
D/StatusBar.NetworkController( 1169): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1169): applyOpen
,W/libprocessgroup(  890): failed to open /acct/uid_10012/pid_6611/cgroup.procs: No such file or directory
,D/TimaKeyStoreProvider( 8121): TimaSignature is unavailable
,D/ActivityThread( 8121): Added TimaKeyStore provider
,D/ResourcesManager( 8121): creating new AssetManager and set to /system/priv-app/SHealth3_5/SHealth3_5.apk
,D/SHealthUpgrade(SHealthUpgradeUtil)( 8121): isShealthServiceInstalled() : HealthService is Installed.
,D/SHealthUpgrade(SHealthUpgradeUtil)( 8121): isShealthService2xInstalled() : HEALTH SERVICE is INSTALLED.
D/SHealthUpgrade(SHealthUpgradeUtil)( 8121): isShealthService2xInstalled() : HEALTH SERVICE VERSION = 2.x
,D/SHealthUpgrade(SHealthUpgradeUtil)( 8121): checkState()
,D/SHealthUpgrade(SHealthUpgradeUtil)( 8121): checkState() : APP TYPE = Full
,D/SHealthUpgrade(SHealthUpgradeUtil)( 8121): isFitnessWithGearInstalled() : Fitness with Gear isn't Installed.
,D/SHealthUpgrade(SHealthUpgradeUtil)( 8121): isShealthServiceInstalled() : HealthService is Installed.
,D/SHealthUpgrade(SHealthUpgradeUtil)( 8121): isShealthService1xInstalled() : HEALTH SERVICE is INSTALLED.
,D/SHealthUpgrade(SHealthUpgradeUtil)( 8121): isShealthService1xInstalled() : HEALTH SERVICE VERSION is NOT 1.x !!!
D/SHealthUpgrade(SHealthUpgradeUtil)( 8121): isShealthService0xInstalled() : HEALTH SERVICE is INSTALLED.
D/SHealthUpgrade(SHealthUpgradeUtil)( 8121): isShealthService0xInstalled() : HEALTH SERVICE VERSION is NOT 0.x !!!
D/SHealthUpgrade(SHealthUpgradeUtil)( 8121): isShealthService2xInstalled() : HEALTH SERVICE is INSTALLED.
D/SHealthUpgrade(SHealthUpgradeUtil)( 8121): isShealthService2xInstalled() : HEALTH SERVICE VERSION = 2.x
,D/SHealthUpgrade(SHealthUpgradeUtil)( 8121): checkState() : =========== UPGRADE_STATE_APP_UPGRADE_DONE ===========
,D/SHealthUpgrade(SHealthUpgradeUtil)( 8121): isShealthServiceInstalled() : HealthService is Installed.
,D/SHealthUpgrade(SHealthUpgradeUtil)( 8121): isShealthService2xInstalled() : HEALTH SERVICE is INSTALLED.
D/SHealthUpgrade(SHealthUpgradeUtil)( 8121): isShealthService2xInstalled() : HEALTH SERVICE VERSION = 2.x
,D/SHealthUpgrade(SHealthUpgradeUtil)( 8121): isShealthServiceInstalled() : HealthService is Installed.
D/SHealthUpgrade(SHealthUpgradeUtil)( 8121): isShealthService2xInstalled() : HEALTH SERVICE is INSTALLED.
D/SHealthUpgrade(SHealthUpgradeUtil)( 8121): isShealthService2xInstalled() : HEALTH SERVICE VERSION = 2.x
,D/SHealthUpgrade(SHealthUpgradeUtil)( 8121): isShealthService2xInstalled() : HEALTH SERVICE is INSTALLED.
,D/SHealthUpgrade(SHealthUpgradeUtil)( 8121): isShealthService2xInstalled() : HEALTH SERVICE VERSION = 2.x
,E/ActivityManager(  890): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  890): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  890): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  890): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 8142): MountEmulatedStorage()
,E/Zygote  ( 8142): v2
I/libpersona( 8142): KNOX_SDCARD checking this for 10017
I/libpersona( 8142): KNOX_SDCARD not a persona
,I/ActivityManager(  890): Start proc com.sec.android.service.health for content provider com.sec.android.service.health/.cp.MigrationCpProvider: pid=8142 uid=10017 gids={50017, 9997} abi=armeabi-v7a
,I/SELinux ( 8142): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 8142): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 8142): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 8142): TimaSignature is unavailable
,D/ActivityThread( 8142): Added TimaKeyStore provider
,D/ResourcesManager( 8142): creating new AssetManager and set to /system/priv-app/HealthService/HealthService.apk
,D/SHealthUpgrade(SHealthUpgradeUtil)( 8121): isShealthService2xInstalled() : HEALTH SERVICE is INSTALLED.
,D/SHealthUpgrade(SHealthUpgradeUtil)( 8121): isShealthService2xInstalled() : HEALTH SERVICE VERSION = 2.x
,D/BluetoothManager( 8121): getConnectedDevices
,D/-----SIC-----( 8121): ------------------skip uv
,D/-----SIC-----( 8121): ------------------skip SPO2
,D/-----SIC-----( 8121): ------------------skip TGH
,I/SecureStorage( 8142): [INFO]: SPID(0x00000000)Processing data
,I/SecureStorage(  351): [INFO]: SPID(0x00000005)Credentials: uid 10017, gid 10017, pid 8142
I/SecureStorage(  351): [INFO]: SPID(0x00000005)Received function mask & code: 0x00000106
,E/Vold    (  248): Failed to find mounted volume for /storage/extSdCard/Android/data/com.sec.android.app.shealth/cache/
W/Vold    (  248): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 8121): Failed to ensure directory: /storage/extSdCard/Android/data/com.sec.android.app.shealth/cache
,E/Vold    (  248): Failed to find mounted volume for /storage/extSdCard/Android/data/com.sec.android.app.shealth/files/
W/Vold    (  248): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 8121): Failed to ensure directory: /storage/extSdCard/Android/data/com.sec.android.app.shealth/files
,V/MediaPlayer( 8121): decode(33, 19359868, 4230)
,V/MediaPlayerService(  285): decode(30, 19359868, 4230)
,V/MediaPlayerService(  285): player type = 3
,V/AwesomePlayer(  285): setDefault
V/AwesomePlayer(  285): constructor
,V/AwesomePlayer(  285): setDefault
,V/AwesomePlayer(  285): reset_l()
V/AwesomePlayer(  285): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  285): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  285): mAudioTrackVector clear
V/AwesomePlayer(  285): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  285): mSecCapture clear
,V/AwesomePlayer(  285): mSecMediaClock clear
V/StagefrightPlayer(  285): StagefrightPlayer
V/AwesomePlayer(  285): setListener
V/StagefrightPlayer(  285): initCheck
V/AwesomePlayer(  285): setAudioSink
V/StagefrightPlayer(  285): setDataSource(30, 19359868, 4230)
,V/AwesomePlayer(  285): reset_l()
V/AwesomePlayer(  285): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  285): notify(0xb0618420, 8, 0, 0)
V/AudioCache(  285): ignored
V/AwesomePlayer(  285): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  285): mAudioTrackVector clear
V/AwesomePlayer(  285): reset_l() mAudioPlayer successfully deleted
,V/AwesomePlayer(  285): mSecCapture clear
V/AwesomePlayer(  285): mSecMediaClock clear
D/Utils   (  285): printFileName fd(31) -> /system/priv-app/SHealth3_5/SHealth3_5.apk
,V/AwesomePlayer(  285): track of type 'audio/vorbis' does not publish bitrate
,V/AwesomePlayer(  285): mBitrate = -1 bits/sec
I/OggExtractor(  285): OggSource::OggSource() mExtractor ref count = 4
V/AwesomePlayer(  285): current audio track index (0) is added to vector
V/AwesomePlayer(  285): setDataSource_l: Audio(1), Video(0)
I/AwesomePlayer(  285): checkRightsStatus is not necessary - AwesomePlayer::setDataSource_l
V/MediaPlayerService(  285): prepare
,V/AwesomePlayer(  285): prepareAsync
V/MediaPlayerService(  285): wait for prepare
,V/AwesomePlayer(  285): onPrepareAsyncEvent
I/SecMediaClock(  285): SecMediaClock constructor
I/SecMediaClock(  285): reset
I/SecVideoCapture(  285): SecVideoCapture constructor
I/SecVideoCapture(  285): reset
V/AwesomePlayer(  285): initAudioDecoder
V/AwesomePlayer(  285): checkOffloadExceptions is true
V/AudioPolicyManager(  285): isOffloadSupported: SR=44100, CM=0x1, Format=0x7000000, StreamType=-1, BitRate=4294967295, duration=20770 us, has_video=0
V/AudioPolicyManager(  285): isOffloadSupported: stream_type != MUSIC, returning false
I/OMXCodec(  285): Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
,I/OMXCodec(  285): Successfully allocated OMX node 'OMX.google.vorbis.decoder'
I/OMXCodec(  285): >>>UHQA initOutputFormat 16
I/AwesomePlayer(  285): Could not offload audio decode, try pcm offload
V/AudioPolicyManager(  285): isOffloadSupported: SR=44100, CM=0x1, Format=0x1c000001, StreamType=-1, BitRate=4294967295, duration=20770 us, has_video=0
V/AudioPolicyManager(  285): isOffloadSupported: stream_type != MUSIC, returning false
I/OMXCodec(  285): [OMX.google.vorbis.decoder] OMXCodec::start mState=1
I/OMXCodec(  285): [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
,I/OMXCodec(  285): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
I/OMXCodec(  285): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
,V/AwesomePlayer(  285): finishAsyncPrepare_l
V/AwesomePlayer(  285): notifyListner_l() msg (200-MEDIA_INFO), ext1 (973), ext2 (0)
V/AudioCache(  285): notify(0xb0618420, 200, 973, 0)
V/AudioCache(  285): ignored
V/AwesomePlayer(  285): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache(  285): notify(0xb0618420, 5, 0, 0)
V/AudioCache(  285): ignored
V/AwesomePlayer(  285): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache(  285): notify(0xb0618420, 1, 0, 0)
V/AudioCache(  285): prepared
V/AudioCache(  285): wait - success
V/MediaPlayerService(  285): start
V/StagefrightPlayer(  285): start
V/AwesomePlayer(  285): play
V/AwesomePlayer(  285): AwesomePlayer::play_l():: This is not a DRM content
V/AwesomePlayer(  285): startAudioPlayer_l, sendErrorNotification (0)
D/AudioPlayer(  285): start of Playback, useOffload 0
,I/OMXCodec(  285): [OMX.google.vorbis.decoder] 0onCmdComplete  mState =  7
I/OMXCodec(  285): [OMX.google.vorbis.decoder] PORT_DISABLED(1)
I/OMXCodec(  285): >>>UHQA initOutputFormat 16
I/OMXCodec(  285): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
,I/OMXCodec(  285): [OMX.google.vorbis.decoder] End Of Stream
I/AudioPlayer(  285): Audio channels(1)
I/AudioPlayer(  285): Audioplayer kKeyAudioPCMFormat:0, 1, 0
I/AudioPlayer(  285): Audioplayer kKeyAudioPCMFormat read fail(1, 1)
V/AudioCache(  285): open(44100, 1, 0x0, 1, 0)
,V/AwesomePlayer(  285): notifyListner_l() msg (6-MEDIA_STARTED), ext1 (0), ext2 (0)
,V/AudioCache(  285): notify(0xb0618420, 6, 0, 0)
V/AudioCache(  285): ignored
I/AudioPlayer(  285): First fillBuffer call!!
V/AwesomePlayer(  285): addBatteryData
I/AudioPlayer(  285): >>> setAudioEffect Read mAudioFormat : 1, event : 4587583, value : 4390976
E/AudioPlayer(  285): >>> setAudioEffect Error mAudioFormat : 1, event : 4587583, value : 4390976
,V/AwesomePlayer(  285): postAudioEOS delayUs (0)
,V/MediaPlayerService(  285): wait for playback complete
V/AwesomePlayer(  285): onCheckAudioStatus
V/AwesomePlayer(  285): onCheckAudioStatus() set AUDIO_AT_EOS flag
V/AwesomePlayer(  285): onStreamDone
V/AwesomePlayer(  285): MEDIA_PLAYBACK_COMPLETE
V/AwesomePlayer(  285): notifyListner_l() msg (2-MEDIA_PLAYBACK_COMPLETE), ext1 (0), ext2 (0)
V/AudioCache(  285): notify(0xb0618420, 2, 0, 0)
V/AudioCache(  285): playback complete - thread will wake up later
V/AwesomePlayer(  285): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache(  285): notify(0xb0618420, 7, 0, 0)
V/AudioCache(  285): ignored
V/AwesomePlayer(  285): cancelPlayerEvents (keepNotifications=1)
V/AwesomePlayer(  285): addBatteryData
,V/AudioCache(  285): wait - success
V/StagefrightPlayer(  285): reset
V/AwesomePlayer(  285): reset_l()
V/AwesomePlayer(  285): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  285): notify(0xb0618420, 8, 0, 0)
V/AudioCache(  285): ignored
V/AwesomePlayer(  285): cancelPlayerEvents (keepNotifications=0)
,V/AwesomePlayer(  285): mAudioTrackVector clear
D/AudioPlayer(  285): reset: mPlaying=0 mReachedEOS=1 useOffload=0
I/OMXCodec(  285): [OMX.google.vorbis.decoder] stop mState=4
I/OMXCodec(  285): [OMX.google.vorbis.decoder] stop() sendCommand(0x74, OMX_CommandStateSet, OMX_StateIdle)
,I/OMXCodec(  285): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
,I/OMXCodec(  285): [OMX.google.vorbis.decoder] stopOmxComponent_l() mstate = 1
I/OggExtractor(  285): OggSource::stop() mExtractor ref count = 1
,I/OggExtractor(  285): OggSource::~OggSource() mExtractor !mStarted ref count = 1
I/OggExtractor(  285): ~OggSource --
I/OggExtractor(  285): ~OggExtractor ++
I/OggExtractor(  285): ~MyVorbisExtractor ++ 
I/OggExtractor(  285): ~MyVorbisExtractor --
I/OggExtractor(  285): ~OggExtractor --
,I/AudioPlayer(  285): reset out
,V/AwesomePlayer(  285): reset_l() mAudioPlayer successfully deleted
I/SecVideoCapture(  285): SecVideoCapture destructor
I/SecVideoCapture(  285): reset
V/AwesomePlayer(  285): mSecCapture clear
I/SecMediaClock(  285): SecMediaClock destructor
V/AwesomePlayer(  285): mSecMediaClock clear
V/StagefrightPlayer(  285): ~StagefrightPlayer
,V/StagefrightPlayer(  285): reset
V/AwesomePlayer(  285): reset_l()
V/AwesomePlayer(  285): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  285): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  285): mAudioTrackVector clear
V/AwesomePlayer(  285): reset_l() mAudioPlayer successfully deleted
,V/AwesomePlayer(  285): mSecCapture clear
V/AwesomePlayer(  285): mSecMediaClock clear
V/AwesomePlayer(  285): destructor
,V/AwesomePlayer(  285): reset_l()
,V/AwesomePlayer(  285): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  285): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  285): mAudioTrackVector clear
V/AwesomePlayer(  285): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  285): mSecCapture clear
V/AwesomePlayer(  285): mSecMediaClock clear
,V/MediaPlayer( 8121): decode(35, 19213040, 15440)
V/MediaPlayerService(  285): decode(30, 19213040, 15440)
,V/MediaPlayerService(  285): player type = 3
,V/AwesomePlayer(  285): setDefault
,V/AwesomePlayer(  285): constructor
,V/AwesomePlayer(  285): setDefault
,V/AwesomePlayer(  285): reset_l()
V/AwesomePlayer(  285): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  285): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  285): mAudioTrackVector clear
V/AwesomePlayer(  285): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  285): mSecCapture clear
,V/AwesomePlayer(  285): mSecMediaClock clear
V/StagefrightPlayer(  285): StagefrightPlayer
V/AwesomePlayer(  285): setListener
V/StagefrightPlayer(  285): initCheck
V/AwesomePlayer(  285): setAudioSink
V/StagefrightPlayer(  285): setDataSource(30, 19213040, 15440)
,V/AwesomePlayer(  285): reset_l()
V/AwesomePlayer(  285): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  285): notify(0xb092b1f0, 8, 0, 0)
V/AudioCache(  285): ignored
V/AwesomePlayer(  285): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  285): mAudioTrackVector clear
,V/AwesomePlayer(  285): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  285): mSecCapture clear
V/AwesomePlayer(  285): mSecMediaClock clear
D/Utils   (  285): printFileName fd(31) -> /system/priv-app/SHealth3_5/SHealth3_5.apk
,V/AwesomePlayer(  285): track of type 'audio/vorbis' does not publish bitrate
,V/AwesomePlayer(  285): mBitrate = -1 bits/sec
I/OggExtractor(  285): OggSource::OggSource() mExtractor ref count = 4
,V/AwesomePlayer(  285): current audio track index (0) is added to vector
V/AwesomePlayer(  285): setDataSource_l: Audio(1), Video(0)
I/AwesomePlayer(  285): checkRightsStatus is not necessary - AwesomePlayer::setDataSource_l
V/MediaPlayerService(  285): prepare
,V/AwesomePlayer(  285): prepareAsync
V/MediaPlayerService(  285): wait for prepare
,D/SHealthUpgrade(SHealthUpgradeUtil)( 8121): isShealthServiceInstalled() : HealthService is Installed.
,D/SHealthUpgrade(SHealthUpgradeUtil)( 8121): isShealthService2xInstalled() : HEALTH SERVICE is INSTALLED.
D/SHealthUpgrade(SHealthUpgradeUtil)( 8121): isShealthService2xInstalled() : HEALTH SERVICE VERSION = 2.x
,D/AdaptiveEventManager( 1169): removeAdaptiveEvent() requestClass = com.sec.android.app.shealth.walkingmate.service.WalkingMateDayStepService
D/AdaptiveEventManager( 1169): M updateContainers()
D/AdaptiveEventContainerSmall( 1169): C updatePedoContainer()
D/AdaptiveEventContainerSmall( 1169): handlePedoUpdate()
D/AdaptiveEventContainerSmall( 1169): pedoEvent == null
,V/AwesomePlayer(  285): onPrepareAsyncEvent
I/SecMediaClock(  285): SecMediaClock constructor
I/SecMediaClock(  285): reset
I/SecVideoCapture(  285): SecVideoCapture constructor
I/SecVideoCapture(  285): reset
V/AwesomePlayer(  285): initAudioDecoder
V/AwesomePlayer(  285): checkOffloadExceptions is true
V/AudioPolicyManager(  285): isOffloadSupported: SR=44100, CM=0x3, Format=0x7000000, StreamType=-1, BitRate=4294967295, duration=849387 us, has_video=0
V/AudioPolicyManager(  285): isOffloadSupported: stream_type != MUSIC, returning false
I/OMXCodec(  285): Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
,I/OMXCodec(  285): Successfully allocated OMX node 'OMX.google.vorbis.decoder'
I/OMXCodec(  285): >>>UHQA initOutputFormat 16
I/AwesomePlayer(  285): Could not offload audio decode, try pcm offload
V/AudioPolicyManager(  285): isOffloadSupported: SR=44100, CM=0x1, Format=0x1c000001, StreamType=-1, BitRate=4294967295, duration=849387 us, has_video=0
V/AudioPolicyManager(  285): isOffloadSupported: stream_type != MUSIC, returning false
I/OMXCodec(  285): [OMX.google.vorbis.decoder] OMXCodec::start mState=1
I/OMXCodec(  285): [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
I/OMXCodec(  285): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
,I/OMXCodec(  285): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
V/AwesomePlayer(  285): finishAsyncPrepare_l
V/AwesomePlayer(  285): notifyListner_l() msg (200-MEDIA_INFO), ext1 (973), ext2 (0)
V/AudioCache(  285): notify(0xb092b1f0, 200, 973, 0)
V/AudioCache(  285): ignored
V/AwesomePlayer(  285): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache(  285): notify(0xb092b1f0, 5, 0, 0)
V/AudioCache(  285): ignored
V/AwesomePlayer(  285): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache(  285): notify(0xb092b1f0, 1, 0, 0)
V/AudioCache(  285): prepared
V/AudioCache(  285): wait - success
V/MediaPlayerService(  285): start
V/StagefrightPlayer(  285): start
,V/AwesomePlayer(  285): play
V/AwesomePlayer(  285): AwesomePlayer::play_l():: This is not a DRM content
V/AwesomePlayer(  285): startAudioPlayer_l, sendErrorNotification (0)
D/AudioPlayer(  285): start of Playback, useOffload 0
,I/OMXCodec(  285): [OMX.google.vorbis.decoder] 0onCmdComplete  mState =  7
,I/OMXCodec(  285): [OMX.google.vorbis.decoder] PORT_DISABLED(1)
I/OMXCodec(  285): >>>UHQA initOutputFormat 16
D/AdaptiveEventManager( 1169): removeAdaptiveEvent() requestClass = com.sec.android.app.shealth.walkingmate.service.WalkingMateDayStepService
D/AdaptiveEventManager( 1169): M updateContainers()
D/AdaptiveEventContainerSmall( 1169): C updatePedoContainer()
D/AdaptiveEventContainerSmall( 1169): handlePedoUpdate()
D/AdaptiveEventContainerSmall( 1169): pedoEvent == null
I/OMXCodec(  285): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
,I/AudioPlayer(  285): Audio channels(2)
I/AudioPlayer(  285): Audioplayer kKeyAudioPCMFormat:0, 1, 0
I/AudioPlayer(  285): Audioplayer kKeyAudioPCMFormat read fail(2, 1)
V/AudioCache(  285): open(44100, 2, 0x0, 1, 0)
,V/AwesomePlayer(  285): notifyListner_l() msg (6-MEDIA_STARTED), ext1 (0), ext2 (0)
V/AudioCache(  285): notify(0xb092b1f0, 6, 0, 0)
V/AudioCache(  285): ignored
V/AwesomePlayer(  285): addBatteryData
V/MediaPlayerService(  285): wait for playback complete
,I/ActivityManager(  890): Killing 7069:com.samsung.android.provider.shootingmodeprovider/u0a170 (adj 15): bgCount ##41
,I/AudioPlayer(  285): First fillBuffer call!!
I/AudioPlayer(  285): >>> setAudioEffect Read mAudioFormat : 1, event : 235670794, value : 319688206
E/AudioPlayer(  285): >>> setAudioEffect Error mAudioFormat : 1, event : 235670794, value : 319688206
,I/UpdateIcingCorporaServi( 1559): Updating corpora: APPS=com.sec.enterprise.knox.cloudmdm.smdms, CONTACTS=MAYBE
,E/ActivityManager(  890): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  890): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  890): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  890): checkUser: useridlist=null, currentuser=0
,I/OMXCodec(  285): [OMX.google.vorbis.decoder] End Of Stream
V/AwesomePlayer(  285): postAudioEOS delayUs (0)
V/AwesomePlayer(  285): onCheckAudioStatus
V/AwesomePlayer(  285): onCheckAudioStatus() set AUDIO_AT_EOS flag
V/AwesomePlayer(  285): onStreamDone
V/AwesomePlayer(  285): MEDIA_PLAYBACK_COMPLETE
V/AwesomePlayer(  285): notifyListner_l() msg (2-MEDIA_PLAYBACK_COMPLETE), ext1 (0), ext2 (0)
V/AudioCache(  285): notify(0xb092b1f0, 2, 0, 0)
V/AudioCache(  285): playback complete - thread will wake up later
V/AwesomePlayer(  285): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache(  285): notify(0xb092b1f0, 7, 0, 0)
V/AudioCache(  285): ignored
V/AwesomePlayer(  285): cancelPlayerEvents (keepNotifications=1)
V/AwesomePlayer(  285): addBatteryData
V/AudioCache(  285): wait - success
V/StagefrightPlayer(  285): reset
,V/AwesomePlayer(  285): reset_l()
V/AwesomePlayer(  285): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  285): notify(0xb092b1f0, 8, 0, 0)
V/AudioCache(  285): ignored
V/AwesomePlayer(  285): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  285): mAudioTrackVector clear
D/AudioPlayer(  285): reset: mPlaying=0 mReachedEOS=1 useOffload=0
I/OMXCodec(  285): [OMX.google.vorbis.decoder] stop mState=4
I/OMXCodec(  285): [OMX.google.vorbis.decoder] stop() sendCommand(0x75, OMX_CommandStateSet, OMX_StateIdle)
I/OMXCodec(  285): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
I/OMXCodec(  285): [OMX.google.vorbis.decoder] stopOmxComponent_l() mstate = 1
I/OggExtractor(  285): OggSource::stop() mExtractor ref count = 1
I/OggExtractor(  285): OggSource::~OggSource() mExtractor !mStarted ref count = 1
I/OggExtractor(  285): ~OggSource --
I/OggExtractor(  285): ~OggExtractor ++
I/OggExtractor(  285): ~MyVorbisExtractor ++ 
I/OggExtractor(  285): ~MyVorbisExtractor --
I/OggExtractor(  285): ~OggExtractor --
E/Zygote  ( 8196): MountEmulatedStorage()
E/Zygote  ( 8196): v2
I/libpersona( 8196): KNOX_SDCARD checking this for 10075
I/libpersona( 8196): KNOX_SDCARD not a persona
,I/AudioPlayer(  285): reset out
,V/AwesomePlayer(  285): reset_l() mAudioPlayer successfully deleted
I/SecVideoCapture(  285): SecVideoCapture destructor
I/SecVideoCapture(  285): reset
,V/AwesomePlayer(  285): mSecCapture clear
I/SecMediaClock(  285): SecMediaClock destructor
V/AwesomePlayer(  285): mSecMediaClock clear
V/StagefrightPlayer(  285): ~StagefrightPlayer
,V/StagefrightPlayer(  285): reset
V/AwesomePlayer(  285): reset_l()
V/AwesomePlayer(  285): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  285): cancelPlayerEvents (keepNotifications=0)
,V/AwesomePlayer(  285): mAudioTrackVector clear
,I/ActivityManager(  890): Start proc com.samsung.android.app.FileShareServer for broadcast com.samsung.android.app.FileShareServer/.ServerBroadcastReceiver: pid=8196 uid=10075 gids={50075, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,V/AwesomePlayer(  285): reset_l() mAudioPlayer successfully deleted
,V/AwesomePlayer(  285): mSecCapture clear
V/AwesomePlayer(  285): mSecMediaClock clear
V/AwesomePlayer(  285): destructor
,V/AwesomePlayer(  285): reset_l()
V/AwesomePlayer(  285): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  285): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  285): mAudioTrackVector clear
V/AwesomePlayer(  285): reset_l() mAudioPlayer successfully deleted
,V/AwesomePlayer(  285): mSecCapture clear
V/AwesomePlayer(  285): mSecMediaClock clear
V/MediaPlayer( 8121): decode(37, 19257568, 9226)
,I/SELinux ( 8196): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
V/MediaPlayerService(  285): decode(30, 19257568, 9226)
,V/MediaPlayerService(  285): player type = 3
V/AwesomePlayer(  285): setDefault
V/AwesomePlayer(  285): constructor
V/AwesomePlayer(  285): setDefault
V/AwesomePlayer(  285): reset_l()
V/AwesomePlayer(  285): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  285): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  285): mAudioTrackVector clear
I/SELinux ( 8196): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
V/AwesomePlayer(  285): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  285): mSecCapture clear
V/AwesomePlayer(  285): mSecMediaClock clear
V/StagefrightPlayer(  285): StagefrightPlayer
V/AwesomePlayer(  285): setListener
V/StagefrightPlayer(  285): initCheck
E/SELinux ( 8196): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
V/AwesomePlayer(  285): setAudioSink
V/StagefrightPlayer(  285): setDataSource(30, 19257568, 9226)
V/AwesomePlayer(  285): reset_l()
V/AwesomePlayer(  285): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  285): notify(0xb050f1a0, 8, 0, 0)
V/AudioCache(  285): ignored
V/AwesomePlayer(  285): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  285): mAudioTrackVector clear
V/AwesomePlayer(  285): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  285): mSecCapture clear
V/AwesomePlayer(  285): mSecMediaClock clear
D/Utils   (  285): printFileName fd(31) -> /system/priv-app/SHealth3_5/SHealth3_5.apk
,V/AwesomePlayer(  285): track of type 'audio/vorbis' does not publish bitrate
,V/AwesomePlayer(  285): mBitrate = -1 bits/sec
I/OggExtractor(  285): OggSource::OggSource() mExtractor ref count = 4
V/AwesomePlayer(  285): current audio track index (0) is added to vector
V/AwesomePlayer(  285): setDataSource_l: Audio(1), Video(0)
I/AwesomePlayer(  285): checkRightsStatus is not necessary - AwesomePlayer::setDataSource_l
,V/MediaPlayerService(  285): prepare
V/AwesomePlayer(  285): prepareAsync
V/MediaPlayerService(  285): wait for prepare
,V/AwesomePlayer(  285): onPrepareAsyncEvent
I/SecMediaClock(  285): SecMediaClock constructor
I/SecMediaClock(  285): reset
I/SecVideoCapture(  285): SecVideoCapture constructor
I/SecVideoCapture(  285): reset
V/AwesomePlayer(  285): initAudioDecoder
V/AwesomePlayer(  285): checkOffloadExceptions is true
V/AudioPolicyManager(  285): isOffloadSupported: SR=44100, CM=0x3, Format=0x7000000, StreamType=-1, BitRate=4294967295, duration=404897 us, has_video=0
V/AudioPolicyManager(  285): isOffloadSupported: stream_type != MUSIC, returning false
I/OMXCodec(  285): Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
,I/OMXCodec(  285): Successfully allocated OMX node 'OMX.google.vorbis.decoder'
I/OMXCodec(  285): >>>UHQA initOutputFormat 16
I/ActivityManager(  890): Killing 6187:com.google.android.gm/u0a114 (adj 15): bgCount ##41
I/AwesomePlayer(  285): Could not offload audio decode, try pcm offload
V/AudioPolicyManager(  285): isOffloadSupported: SR=44100, CM=0x1, Format=0x1c000001, StreamType=-1, BitRate=4294967295, duration=404897 us, has_video=0
V/AudioPolicyManager(  285): isOffloadSupported: stream_type != MUSIC, returning false
I/OMXCodec(  285): [OMX.google.vorbis.decoder] OMXCodec::start mState=1
,I/OMXCodec(  285): [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
I/OMXCodec(  285): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
,I/OMXCodec(  285): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
,V/AwesomePlayer(  285): finishAsyncPrepare_l
V/AwesomePlayer(  285): notifyListner_l() msg (200-MEDIA_INFO), ext1 (973), ext2 (0)
V/AudioCache(  285): notify(0xb050f1a0, 200, 973, 0)
V/AudioCache(  285): ignored
V/AwesomePlayer(  285): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache(  285): notify(0xb050f1a0, 5, 0, 0)
V/AudioCache(  285): ignored
V/AwesomePlayer(  285): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache(  285): notify(0xb050f1a0, 1, 0, 0)
V/AudioCache(  285): prepared
V/AudioCache(  285): wait - success
V/MediaPlayerService(  285): start
V/StagefrightPlayer(  285): start
V/AwesomePlayer(  285): play
V/AwesomePlayer(  285): AwesomePlayer::play_l():: This is not a DRM content
V/AwesomePlayer(  285): startAudioPlayer_l, sendErrorNotification (0)
D/AudioPlayer(  285): start of Playback, useOffload 0
,I/OMXCodec(  285): [OMX.google.vorbis.decoder] 0onCmdComplete  mState =  7
I/OMXCodec(  285): [OMX.google.vorbis.decoder] PORT_DISABLED(1)
I/OMXCodec(  285): >>>UHQA initOutputFormat 16
I/OMXCodec(  285): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
,I/AudioPlayer(  285): Audio channels(2)
I/AudioPlayer(  285): Audioplayer kKeyAudioPCMFormat:0, 1, 0
I/AudioPlayer(  285): Audioplayer kKeyAudioPCMFormat read fail(2, 1)
V/AudioCache(  285): open(44100, 2, 0x0, 1, 0)
,V/AwesomePlayer(  285): notifyListner_l() msg (6-MEDIA_STARTED), ext1 (0), ext2 (0)
V/AudioCache(  285): notify(0xb050f1a0, 6, 0, 0)
V/AudioCache(  285): ignored
V/AwesomePlayer(  285): addBatteryData
V/MediaPlayerService(  285): wait for playback complete
,D/TimaKeyStoreProvider( 8196): TimaSignature is unavailable
,D/ActivityThread( 8196): Added TimaKeyStore provider
,I/AudioPlayer(  285): First fillBuffer call!!
I/AudioPlayer(  285): >>> setAudioEffect Read mAudioFormat : 1, event : 4587583, value : 4390976
E/AudioPlayer(  285): >>> setAudioEffect Error mAudioFormat : 1, event : 4587583, value : 4390976
,I/OMXCodec(  285): [OMX.google.vorbis.decoder] End Of Stream
,V/AwesomePlayer(  285): postAudioEOS delayUs (0)
V/AwesomePlayer(  285): onCheckAudioStatus
V/AwesomePlayer(  285): onCheckAudioStatus() set AUDIO_AT_EOS flag
V/AwesomePlayer(  285): onStreamDone
V/AwesomePlayer(  285): MEDIA_PLAYBACK_COMPLETE
V/AwesomePlayer(  285): notifyListner_l() msg (2-MEDIA_PLAYBACK_COMPLETE), ext1 (0), ext2 (0)
V/AudioCache(  285): notify(0xb050f1a0, 2, 0, 0)
V/AudioCache(  285): playback complete - thread will wake up later
V/AwesomePlayer(  285): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache(  285): notify(0xb050f1a0, 7, 0, 0)
V/AudioCache(  285): ignored
V/AwesomePlayer(  285): cancelPlayerEvents (keepNotifications=1)
V/AwesomePlayer(  285): addBatteryData
V/AudioCache(  285): wait - success
V/StagefrightPlayer(  285): reset
V/AwesomePlayer(  285): reset_l()
V/AwesomePlayer(  285): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  285): notify(0xb050f1a0, 8, 0, 0)
V/AudioCache(  285): ignored
V/AwesomePlayer(  285): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  285): mAudioTrackVector clear
D/AudioPlayer(  285): reset: mPlaying=0 mReachedEOS=1 useOffload=0
I/OMXCodec(  285): [OMX.google.vorbis.decoder] stop mState=4
I/OMXCodec(  285): [OMX.google.vorbis.decoder] stop() sendCommand(0x76, OMX_CommandStateSet, OMX_StateIdle)
E/DatabaseUtils(  890): Writing exception to parcel
E/DatabaseUtils(  890): java.lang.NullPointerException: key == null
E/DatabaseUtils(  890): 	at android.util.LruCache.get(LruCache.java:112)
E/DatabaseUtils(  890): 	at com.android.providers.settings.SettingsProvider.lookupValue(SettingsProvider.java:982)
E/DatabaseUtils(  890): 	at com.android.providers.settings.SettingsProvider.call(SettingsProvider.java:822)
E/DatabaseUtils(  890): 	at android.content.ContentProvider$Transport.call(ContentProvider.java:370)
E/DatabaseUtils(  890): 	at android.content.ContentProviderNative.onTransact(ContentProviderNative.java:282)
E/DatabaseUtils(  890): 	at android.os.Binder.execTransact(Binder.java:446)
,I/OMXCodec(  285): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
I/OMXCodec(  285): [OMX.google.vorbis.decoder] stopOmxComponent_l() mstate = 1
I/OggExtractor(  285): OggSource::stop() mExtractor ref count = 1
I/OggExtractor(  285): OggSource::~OggSource() mExtractor !mStarted ref count = 1
I/OggExtractor(  285): ~OggSource --
I/OggExtractor(  285): ~OggExtractor ++
I/OggExtractor(  285): ~MyVorbisExtractor ++ 
I/OggExtractor(  285): ~MyVorbisExtractor --
I/OggExtractor(  285): ~OggExtractor --
,I/AudioPlayer(  285): reset out
V/AwesomePlayer(  285): reset_l() mAudioPlayer successfully deleted
I/SecVideoCapture(  285): SecVideoCapture destructor
I/SecVideoCapture(  285): reset
V/AwesomePlayer(  285): mSecCapture clear
I/SecMediaClock(  285): SecMediaClock destructor
V/AwesomePlayer(  285): mSecMediaClock clear
V/StagefrightPlayer(  285): ~StagefrightPlayer
V/StagefrightPlayer(  285): reset
V/AwesomePlayer(  285): reset_l()
V/AwesomePlayer(  285): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  285): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  285): mAudioTrackVector clear
V/AwesomePlayer(  285): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  285): mSecCapture clear
V/AwesomePlayer(  285): mSecMediaClock clear
V/AwesomePlayer(  285): destructor
V/AwesomePlayer(  285): reset_l()
V/AwesomePlayer(  285): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  285): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  285): mAudioTrackVector clear
V/AwesomePlayer(  285): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  285): mSecCapture clear
V/AwesomePlayer(  285): mSecMediaClock clear
V/MediaPlayer( 8121): decode(38, 19364180, 4890)
V/MediaPlayerService(  285): decode(30, 19364180, 4890)
,V/MediaPlayerService(  285): player type = 3
V/AwesomePlayer(  285): setDefault
V/AwesomePlayer(  285): constructor
,V/AwesomePlayer(  285): setDefault
V/AwesomePlayer(  285): reset_l()
V/AwesomePlayer(  285): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  285): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  285): mAudioTrackVector clear
V/AwesomePlayer(  285): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  285): mSecCapture clear
V/AwesomePlayer(  285): mSecMediaClock clear
V/StagefrightPlayer(  285): StagefrightPlayer
V/AwesomePlayer(  285): setListener
V/StagefrightPlayer(  285): initCheck
V/AwesomePlayer(  285): setAudioSink
V/StagefrightPlayer(  285): setDataSource(30, 19364180, 4890)
V/AwesomePlayer(  285): reset_l()
V/AwesomePlayer(  285): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  285): notify(0xb050f0b0, 8, 0, 0)
V/AudioCache(  285): ignored
V/AwesomePlayer(  285): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  285): mAudioTrackVector clear
V/AwesomePlayer(  285): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  285): mSecCapture clear
V/AwesomePlayer(  285): mSecMediaClock clear
D/Utils   (  285): printFileName fd(31) -> /system/priv-app/SHealth3_5/SHealth3_5.apk
,V/AwesomePlayer(  285): track of type 'audio/vorbis' does not publish bitrate
V/AwesomePlayer(  285): mBitrate = -1 bits/sec
I/OggExtractor(  285): OggSource::OggSource() mExtractor ref count = 4
V/AwesomePlayer(  285): current audio track index (0) is added to vector
V/AwesomePlayer(  285): setDataSource_l: Audio(1), Video(0)
I/AwesomePlayer(  285): checkRightsStatus is not necessary - AwesomePlayer::setDataSource_l
V/MediaPlayerService(  285): prepare
V/AwesomePlayer(  285): prepareAsync
V/MediaPlayerService(  285): wait for prepare
V/AwesomePlayer(  285): onPrepareAsyncEvent
I/SecMediaClock(  285): SecMediaClock constructor
I/SecMediaClock(  285): reset
I/SecVideoCapture(  285): SecVideoCapture constructor
I/SecVideoCapture(  285): reset
V/AwesomePlayer(  285): initAudioDecoder
V/AwesomePlayer(  285): checkOffloadExceptions is true
V/AudioPolicyManager(  285): isOffloadSupported: SR=44100, CM=0x1, Format=0x7000000, StreamType=-1, BitRate=4294967295, duration=64058 us, has_video=0
V/AudioPolicyManager(  285): isOffloadSupported: stream_type != MUSIC, returning false
I/OMXCodec(  285): Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
,I/OMXCodec(  285): Successfully allocated OMX node 'OMX.google.vorbis.decoder'
I/OMXCodec(  285): >>>UHQA initOutputFormat 16
I/AwesomePlayer(  285): Could not offload audio decode, try pcm offload
V/AudioPolicyManager(  285): isOffloadSupported: SR=44100, CM=0x1, Format=0x1c000001, StreamType=-1, BitRate=4294967295, duration=64058 us, has_video=0
V/AudioPolicyManager(  285): isOffloadSupported: stream_type != MUSIC, returning false
I/OMXCodec(  285): [OMX.google.vorbis.decoder] OMXCodec::start mState=1
I/OMXCodec(  285): [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
I/OMXCodec(  285): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
,I/OMXCodec(  285): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
V/AwesomePlayer(  285): finishAsyncPrepare_l
V/AwesomePlayer(  285): notifyListner_l() msg (200-MEDIA_INFO), ext1 (973), ext2 (0)
V/AudioCache(  285): notify(0xb050f0b0, 200, 973, 0)
V/AudioCache(  285): ignored
V/AwesomePlayer(  285): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache(  285): notify(0xb050f0b0, 5, 0, 0)
V/AudioCache(  285): ignored
V/AwesomePlayer(  285): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache(  285): notify(0xb050f0b0, 1, 0, 0)
V/AudioCache(  285): prepared
V/AudioCache(  285): wait - success
V/MediaPlayerService(  285): start
V/StagefrightPlayer(  285): start
V/AwesomePlayer(  285): play
V/AwesomePlayer(  285): AwesomePlayer::play_l():: This is not a DRM content
V/AwesomePlayer(  285): startAudioPlayer_l, sendErrorNotification (0)
D/AudioPlayer(  285): start of Playback, useOffload 0
,I/OMXCodec(  285): [OMX.google.vorbis.decoder] 0onCmdComplete  mState =  7
I/OMXCodec(  285): [OMX.google.vorbis.decoder] PORT_DISABLED(1)
I/OMXCodec(  285): >>>UHQA initOutputFormat 16
I/OMXCodec(  285): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
,I/AudioPlayer(  285): Audio channels(1)
I/AudioPlayer(  285): Audioplayer kKeyAudioPCMFormat:0, 1, 0
I/AudioPlayer(  285): Audioplayer kKeyAudioPCMFormat read fail(1, 1)
V/AudioCache(  285): open(44100, 1, 0x0, 1, 0)
,V/AwesomePlayer(  285): notifyListner_l() msg (6-MEDIA_STARTED), ext1 (0), ext2 (0)
V/AudioCache(  285): notify(0xb050f0b0, 6, 0, 0)
V/AudioCache(  285): ignored
V/AwesomePlayer(  285): addBatteryData
,V/MediaPlayerService(  285): wait for playback complete
I/AudioPlayer(  285): First fillBuffer call!!
I/AudioPlayer(  285): >>> setAudioEffect Read mAudioFormat : 1, event : 168430090, value : 151652874
E/AudioPlayer(  285): >>> setAudioEffect Error mAudioFormat : 1, event : 168430090, value : 151652874
,I/OMXCodec(  285): [OMX.google.vorbis.decoder] End Of Stream
,V/AwesomePlayer(  285): postAudioEOS delayUs (0)
,D/ResourcesManager( 8196): creating new AssetManager and set to /system/app/AllshareFileShareServer/AllshareFileShareServer.apk
,I/UpdateIcingCorporaServi( 1559): UpdateCorporaTask done [took 103 ms] updated apps [took 103 ms] 
,V/AwesomePlayer(  285): onCheckAudioStatus
V/AwesomePlayer(  285): onCheckAudioStatus() set AUDIO_AT_EOS flag
V/AwesomePlayer(  285): onStreamDone
V/AwesomePlayer(  285): MEDIA_PLAYBACK_COMPLETE
V/AwesomePlayer(  285): notifyListner_l() msg (2-MEDIA_PLAYBACK_COMPLETE), ext1 (0), ext2 (0)
V/AudioCache(  285): notify(0xb050f0b0, 2, 0, 0)
V/AudioCache(  285): playback complete - thread will wake up later
V/AwesomePlayer(  285): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache(  285): notify(0xb050f0b0, 7, 0, 0)
V/AudioCache(  285): ignored
V/AwesomePlayer(  285): cancelPlayerEvents (keepNotifications=1)
V/AwesomePlayer(  285): addBatteryData
V/AudioCache(  285): wait - success
V/StagefrightPlayer(  285): reset
V/AwesomePlayer(  285): reset_l()
V/AwesomePlayer(  285): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  285): notify(0xb050f0b0, 8, 0, 0)
V/AudioCache(  285): ignored
V/AwesomePlayer(  285): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  285): mAudioTrackVector clear
D/AudioPlayer(  285): reset: mPlaying=0 mReachedEOS=1 useOffload=0
I/OMXCodec(  285): [OMX.google.vorbis.decoder] stop mState=4
I/OMXCodec(  285): [OMX.google.vorbis.decoder] stop() sendCommand(0x77, OMX_CommandStateSet, OMX_StateIdle)
I/OMXCodec(  285): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
I/OMXCodec(  285): [OMX.google.vorbis.decoder] stopOmxComponent_l() mstate = 1
I/OggExtractor(  285): OggSource::stop() mExtractor ref count = 1
I/OggExtractor(  285): OggSource::~OggSource() mExtractor !mStarted ref count = 1
I/OggExtractor(  285): ~OggSource --
I/OggExtractor(  285): ~OggExtractor ++
I/OggExtractor(  285): ~MyVorbisExtractor ++ 
I/OggExtractor(  285): ~MyVorbisExtractor --
I/OggExtractor(  285): ~OggExtractor --
,I/AudioPlayer(  285): reset out
V/AwesomePlayer(  285): reset_l() mAudioPlayer successfully deleted
I/SecVideoCapture(  285): SecVideoCapture destructor
I/SecVideoCapture(  285): reset
V/AwesomePlayer(  285): mSecCapture clear
I/SecMediaClock(  285): SecMediaClock destructor
V/AwesomePlayer(  285): mSecMediaClock clear
V/StagefrightPlayer(  285): ~StagefrightPlayer
V/StagefrightPlayer(  285): reset
V/AwesomePlayer(  285): reset_l()
V/AwesomePlayer(  285): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  285): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  285): mAudioTrackVector clear
V/AwesomePlayer(  285): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  285): mSecCapture clear
V/AwesomePlayer(  285): mSecMediaClock clear
V/AwesomePlayer(  285): destructor
V/AwesomePlayer(  285): reset_l()
V/AwesomePlayer(  285): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  285): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  285): mAudioTrackVector clear
V/AwesomePlayer(  285): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  285): mSecCapture clear
V/AwesomePlayer(  285): mSecMediaClock clear
V/MediaPlayer( 8121): decode(32, 19290344, 17329)
V/MediaPlayerService(  285): decode(30, 19290344, 17329)
,V/MediaPlayerService(  285): player type = 3
V/AwesomePlayer(  285): setDefault
V/AwesomePlayer(  285): constructor
V/AwesomePlayer(  285): setDefault
V/AwesomePlayer(  285): reset_l()
V/AwesomePlayer(  285): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  285): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  285): mAudioTrackVector clear
V/AwesomePlayer(  285): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  285): mSecCapture clear
V/AwesomePlayer(  285): mSecMediaClock clear
V/StagefrightPlayer(  285): StagefrightPlayer
V/AwesomePlayer(  285): setListener
V/StagefrightPlayer(  285): initCheck
V/AwesomePlayer(  285): setAudioSink
V/StagefrightPlayer(  285): setDataSource(30, 19290344, 17329)
V/AwesomePlayer(  285): reset_l()
V/AwesomePlayer(  285): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  285): notify(0xb0618330, 8, 0, 0)
V/AudioCache(  285): ignored
V/AwesomePlayer(  285): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  285): mAudioTrackVector clear
V/AwesomePlayer(  285): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  285): mSecCapture clear
V/AwesomePlayer(  285): mSecMediaClock clear
D/Utils   (  285): printFileName fd(31) -> /system/priv-app/SHealth3_5/SHealth3_5.apk
,V/AwesomePlayer(  285): track of type 'audio/vorbis' does not publish bitrate
V/AwesomePlayer(  285): mBitrate = -1 bits/sec
I/OggExtractor(  285): OggSource::OggSource() mExtractor ref count = 4
V/AwesomePlayer(  285): current audio track index (0) is added to vector
V/AwesomePlayer(  285): setDataSource_l: Audio(1), Video(0)
I/AwesomePlayer(  285): checkRightsStatus is not necessary - AwesomePlayer::setDataSource_l
V/MediaPlayerService(  285): prepare
V/AwesomePlayer(  285): prepareAsync
V/MediaPlayerService(  285): wait for prepare
V/AwesomePlayer(  285): onPrepareAsyncEvent
I/SecMediaClock(  285): SecMediaClock constructor
I/SecMediaClock(  285): reset
I/SecVideoCapture(  285): SecVideoCapture constructor
I/SecVideoCapture(  285): reset
V/AwesomePlayer(  285): initAudioDecoder
V/AwesomePlayer(  285): checkOffloadExceptions is true
V/AudioPolicyManager(  285): isOffloadSupported: SR=44100, CM=0x3, Format=0x7000000, StreamType=-1, BitRate=4294967295, duration=857142 us, has_video=0
V/AudioPolicyManager(  285): isOffloadSupported: stream_type != MUSIC, returning false
I/OMXCodec(  285): Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
,I/OMXCodec(  285): Successfully allocated OMX node 'OMX.google.vorbis.decoder'
,I/OMXCodec(  285): >>>UHQA initOutputFormat 16
I/AwesomePlayer(  285): Could not offload audio decode, try pcm offload
V/AudioPolicyManager(  285): isOffloadSupported: SR=44100, CM=0x1, Format=0x1c000001, StreamType=-1, BitRate=4294967295, duration=857142 us, has_video=0
V/AudioPolicyManager(  285): isOffloadSupported: stream_type != MUSIC, returning false
I/OMXCodec(  285): [OMX.google.vorbis.decoder] OMXCodec::start mState=1
I/OMXCodec(  285): [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
I/OMXCodec(  285): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
I/OMXCodec(  285): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
,V/AwesomePlayer(  285): finishAsyncPrepare_l
V/AwesomePlayer(  285): notifyListner_l() msg (200-MEDIA_INFO), ext1 (973), ext2 (0)
V/AudioCache(  285): notify(0xb0618330, 200, 973, 0)
V/AudioCache(  285): ignored
V/AwesomePlayer(  285): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache(  285): notify(0xb0618330, 5, 0, 0)
V/AudioCache(  285): ignored
V/AwesomePlayer(  285): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache(  285): notify(0xb0618330, 1, 0, 0)
V/AudioCache(  285): prepared
V/AudioCache(  285): wait - success
V/MediaPlayerService(  285): start
V/StagefrightPlayer(  285): start
V/AwesomePlayer(  285): play
V/AwesomePlayer(  285): AwesomePlayer::play_l():: This is not a DRM content
V/AwesomePlayer(  285): startAudioPlayer_l, sendErrorNotification (0)
D/AudioPlayer(  285): start of Playback, useOffload 0
,I/OMXCodec(  285): [OMX.google.vorbis.decoder] 0onCmdComplete  mState =  7
I/OMXCodec(  285): [OMX.google.vorbis.decoder] PORT_DISABLED(1)
I/OMXCodec(  285): >>>UHQA initOutputFormat 16
I/OMXCodec(  285): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
,I/AudioPlayer(  285): Audio channels(2)
I/AudioPlayer(  285): Audioplayer kKeyAudioPCMFormat:0, 1, 0
I/AudioPlayer(  285): Audioplayer kKeyAudioPCMFormat read fail(2, 1)
V/AudioCache(  285): open(44100, 2, 0x0, 1, 0)
,V/AwesomePlayer(  285): notifyListner_l() msg (6-MEDIA_STARTED), ext1 (0), ext2 (0)
V/AudioCache(  285): notify(0xb0618330, 6, 0, 0)
V/AudioCache(  285): ignored
V/AwesomePlayer(  285): addBatteryData
V/MediaPlayerService(  285): wait for playback complete
,I/AudioPlayer(  285): First fillBuffer call!!
I/AudioPlayer(  285): >>> setAudioEffect Read mAudioFormat : 1, event : 235670794, value : 319688206
E/AudioPlayer(  285): >>> setAudioEffect Error mAudioFormat : 1, event : 235670794, value : 319688206
,D/FileShare-Server( 8196): ServerBroadcastReceiver.onReceive - action android.intent.action.PACKAGE_CHANGED // package:com.sec.enterprise.knox.cloudmdm.smdms
,W/libprocessgroup(  890): failed to open /acct/uid_10170/pid_7069/cgroup.procs: No such file or directory
,I/OMXCodec(  285): [OMX.google.vorbis.decoder] End Of Stream
,V/AwesomePlayer(  285): postAudioEOS delayUs (0)
,V/AwesomePlayer(  285): onCheckAudioStatus
V/AwesomePlayer(  285): onCheckAudioStatus() set AUDIO_AT_EOS flag
V/AwesomePlayer(  285): onStreamDone
V/AwesomePlayer(  285): MEDIA_PLAYBACK_COMPLETE
V/AwesomePlayer(  285): notifyListner_l() msg (2-MEDIA_PLAYBACK_COMPLETE), ext1 (0), ext2 (0)
V/AudioCache(  285): notify(0xb0618330, 2, 0, 0)
V/AudioCache(  285): playback complete - thread will wake up later
V/AwesomePlayer(  285): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache(  285): notify(0xb0618330, 7, 0, 0)
V/AudioCache(  285): ignored
V/AwesomePlayer(  285): cancelPlayerEvents (keepNotifications=1)
V/AwesomePlayer(  285): addBatteryData
V/AudioCache(  285): wait - success
V/StagefrightPlayer(  285): reset
V/AwesomePlayer(  285): reset_l()
V/AwesomePlayer(  285): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  285): notify(0xb0618330, 8, 0, 0)
V/AudioCache(  285): ignored
V/AwesomePlayer(  285): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  285): mAudioTrackVector clear
D/AudioPlayer(  285): reset: mPlaying=0 mReachedEOS=1 useOffload=0
I/OMXCodec(  285): [OMX.google.vorbis.decoder] stop mState=4
I/OMXCodec(  285): [OMX.google.vorbis.decoder] stop() sendCommand(0x78, OMX_CommandStateSet, OMX_StateIdle)
I/OMXCodec(  285): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
I/OMXCodec(  285): [OMX.google.vorbis.decoder] stopOmxComponent_l() mstate = 1
I/OggExtractor(  285): OggSource::stop() mExtractor ref count = 1
I/OggExtractor(  285): OggSource::~OggSource() mExtractor !mStarted ref count = 1
I/OggExtractor(  285): ~OggSource --
I/OggExtractor(  285): ~OggExtractor ++
I/OggExtractor(  285): ~MyVorbisExtractor ++ 
I/OggExtractor(  285): ~MyVorbisExtractor --
I/OggExtractor(  285): ~OggExtractor --
,I/AudioPlayer(  285): reset out
V/AwesomePlayer(  285): reset_l() mAudioPlayer successfully deleted
I/SecVideoCapture(  285): SecVideoCapture destructor
I/SecVideoCapture(  285): reset
V/AwesomePlayer(  285): mSecCapture clear
I/SecMediaClock(  285): SecMediaClock destructor
V/AwesomePlayer(  285): mSecMediaClock clear
V/StagefrightPlayer(  285): ~StagefrightPlayer
V/StagefrightPlayer(  285): reset
V/AwesomePlayer(  285): reset_l()
V/AwesomePlayer(  285): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  285): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  285): mAudioTrackVector clear
V/AwesomePlayer(  285): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  285): mSecCapture clear
V/AwesomePlayer(  285): mSecMediaClock clear
V/AwesomePlayer(  285): destructor
V/AwesomePlayer(  285): reset_l()
V/AwesomePlayer(  285): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  285): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  285): mAudioTrackVector clear
V/AwesomePlayer(  285): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  285): mSecCapture clear
V/AwesomePlayer(  285): mSecMediaClock clear
V/MediaPlayer( 8121): decode(39, 19190536, 6644)
V/MediaPlayerService(  285): decode(30, 19190536, 6644)
V/MediaPlayerService(  285): player type = 3
V/AwesomePlayer(  285): setDefault
V/AwesomePlayer(  285): constructor
,V/AwesomePlayer(  285): setDefault
V/AwesomePlayer(  285): reset_l()
V/AwesomePlayer(  285): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  285): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  285): mAudioTrackVector clear
V/AwesomePlayer(  285): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  285): mSecCapture clear
V/AwesomePlayer(  285): mSecMediaClock clear
V/StagefrightPlayer(  285): StagefrightPlayer
V/AwesomePlayer(  285): setListener
V/StagefrightPlayer(  285): initCheck
V/AwesomePlayer(  285): setAudioSink
V/StagefrightPlayer(  285): setDataSource(30, 19190536, 6644)
V/AwesomePlayer(  285): reset_l()
V/AwesomePlayer(  285): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  285): notify(0xb06187e0, 8, 0, 0)
V/AudioCache(  285): ignored
V/AwesomePlayer(  285): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  285): mAudioTrackVector clear
V/AwesomePlayer(  285): reset_l() mAudioPlayer successfully deleted
E/ActivityManager(  890): checkUser: useridlist=null, currentuser=0
V/AwesomePlayer(  285): mSecCapture clear
E/ActivityManager(  890): checkUser: useridlist=null, currentuser=0
V/AwesomePlayer(  285): mSecMediaClock clear
E/ActivityManager(  890): checkUser: useridlist=null, currentuser=0
D/Utils   (  285): printFileName fd(31) -> /system/priv-app/SHealth3_5/SHealth3_5.apk
E/ActivityManager(  890): checkUser: useridlist=null, currentuser=0
,V/AwesomePlayer(  285): track of type 'audio/vorbis' does not publish bitrate
V/AwesomePlayer(  285): mBitrate = -1 bits/sec
I/OggExtractor(  285): OggSource::OggSource() mExtractor ref count = 4
V/AwesomePlayer(  285): current audio track index (0) is added to vector
V/AwesomePlayer(  285): setDataSource_l: Audio(1), Video(0)
I/AwesomePlayer(  285): checkRightsStatus is not necessary - AwesomePlayer::setDataSource_l
V/MediaPlayerService(  285): prepare
V/AwesomePlayer(  285): prepareAsync
V/MediaPlayerService(  285): wait for prepare
V/AwesomePlayer(  285): onPrepareAsyncEvent
I/SecMediaClock(  285): SecMediaClock constructor
I/SecMediaClock(  285): reset
I/SecVideoCapture(  285): SecVideoCapture constructor
I/SecVideoCapture(  285): reset
V/AwesomePlayer(  285): initAudioDecoder
V/AwesomePlayer(  285): checkOffloadExceptions is true
V/AudioPolicyManager(  285): isOffloadSupported: SR=44100, CM=0x1, Format=0x7000000, StreamType=-1, BitRate=4294967295, duration=213446 us, has_video=0
V/AudioPolicyManager(  285): isOffloadSupported: stream_type != MUSIC, returning false
I/OMXCodec(  285): Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
,I/OMXCodec(  285): Successfully allocated OMX node 'OMX.google.vorbis.decoder'
I/OMXCodec(  285): >>>UHQA initOutputFormat 16
I/AwesomePlayer(  285): Could not offload audio decode, try pcm offload
V/AudioPolicyManager(  285): isOffloadSupported: SR=44100, CM=0x1, Format=0x1c000001, StreamType=-1, BitRate=4294967295, duration=213446 us, has_video=0
V/AudioPolicyManager(  285): isOffloadSupported: stream_type != MUSIC, returning false
I/OMXCodec(  285): [OMX.google.vorbis.decoder] OMXCodec::start mState=1
I/OMXCodec(  285): [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
I/OMXCodec(  285): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
,I/OMXCodec(  285): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
V/AwesomePlayer(  285): finishAsyncPrepare_l
V/AwesomePlayer(  285): notifyListner_l() msg (200-MEDIA_INFO), ext1 (973), ext2 (0)
V/AudioCache(  285): notify(0xb06187e0, 200, 973, 0)
V/AudioCache(  285): ignored
V/AwesomePlayer(  285): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache(  285): notify(0xb06187e0, 5, 0, 0)
V/AudioCache(  285): ignored
V/AwesomePlayer(  285): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache(  285): notify(0xb06187e0, 1, 0, 0)
V/AudioCache(  285): prepared
V/AudioCache(  285): wait - success
V/MediaPlayerService(  285): start
V/StagefrightPlayer(  285): start
V/AwesomePlayer(  285): play
V/AwesomePlayer(  285): AwesomePlayer::play_l():: This is not a DRM content
,V/AwesomePlayer(  285): startAudioPlayer_l, sendErrorNotification (0)
D/AudioPlayer(  285): start of Playback, useOffload 0
,I/OMXCodec(  285): [OMX.google.vorbis.decoder] 0onCmdComplete  mState =  7
I/OMXCodec(  285): [OMX.google.vorbis.decoder] PORT_DISABLED(1)
I/OMXCodec(  285): >>>UHQA initOutputFormat 16
I/OMXCodec(  285): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
,I/AudioPlayer(  285): Audio channels(1)
I/AudioPlayer(  285): Audioplayer kKeyAudioPCMFormat:0, 1, 0
I/AudioPlayer(  285): Audioplayer kKeyAudioPCMFormat read fail(1, 1)
V/AudioCache(  285): open(44100, 1, 0x0, 1, 0)
,V/AwesomePlayer(  285): notifyListner_l() msg (6-MEDIA_STARTED), ext1 (0), ext2 (0)
V/AudioCache(  285): notify(0xb06187e0, 6, 0, 0)
V/AudioCache(  285): ignored
V/AwesomePlayer(  285): addBatteryData
I/AudioPlayer(  285): First fillBuffer call!!
,V/MediaPlayerService(  285): wait for playback complete
I/AudioPlayer(  285): >>> setAudioEffect Read mAudioFormat : 1, event : 168430090, value : 151652874
E/AudioPlayer(  285): >>> setAudioEffect Error mAudioFormat : 1, event : 168430090, value : 151652874
,E/Zygote  ( 8229): MountEmulatedStorage()
E/Zygote  ( 8229): v2
I/libpersona( 8229): KNOX_SDCARD checking this for 1000
I/libpersona( 8229): KNOX_SDCARD not a persona
,I/ActivityManager(  890): Start proc com.sec.knox.knoxsetupwizardclient for broadcast com.sec.knox.knoxsetupwizardclient/.shortcut.ShortcutReceiver: pid=8229 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,I/ActivityManager(  890): Killing 7149:com.sec.android.app.music:service/u0a44 (adj 15): bgCount ##41
,I/OMXCodec(  285): [OMX.google.vorbis.decoder] End Of Stream
,V/AwesomePlayer(  285): postAudioEOS delayUs (0)
,V/AwesomePlayer(  285): onCheckAudioStatus
V/AwesomePlayer(  285): onCheckAudioStatus() set AUDIO_AT_EOS flag
V/AwesomePlayer(  285): onStreamDone
V/AwesomePlayer(  285): MEDIA_PLAYBACK_COMPLETE
V/AwesomePlayer(  285): notifyListner_l() msg (2-MEDIA_PLAYBACK_COMPLETE), ext1 (0), ext2 (0)
V/AudioCache(  285): notify(0xb06187e0, 2, 0, 0)
V/AudioCache(  285): playback complete - thread will wake up later
V/AwesomePlayer(  285): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache(  285): notify(0xb06187e0, 7, 0, 0)
V/AudioCache(  285): ignored
V/AwesomePlayer(  285): cancelPlayerEvents (keepNotifications=1)
,V/AwesomePlayer(  285): addBatteryData
V/AudioCache(  285): wait - success
V/StagefrightPlayer(  285): reset
V/AwesomePlayer(  285): reset_l()
,V/AwesomePlayer(  285): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  285): notify(0xb06187e0, 8, 0, 0)
V/AudioCache(  285): ignored
V/AwesomePlayer(  285): cancelPlayerEvents (keepNotifications=0)
,V/AwesomePlayer(  285): mAudioTrackVector clear
D/AudioPlayer(  285): reset: mPlaying=0 mReachedEOS=1 useOffload=0
I/OMXCodec(  285): [OMX.google.vorbis.decoder] stop mState=4
I/OMXCodec(  285): [OMX.google.vorbis.decoder] stop() sendCommand(0x79, OMX_CommandStateSet, OMX_StateIdle)
,I/OMXCodec(  285): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
I/OMXCodec(  285): [OMX.google.vorbis.decoder] stopOmxComponent_l() mstate = 1
,I/OggExtractor(  285): OggSource::stop() mExtractor ref count = 1
I/OggExtractor(  285): OggSource::~OggSource() mExtractor !mStarted ref count = 1
I/OggExtractor(  285): ~OggSource --
I/OggExtractor(  285): ~OggExtractor ++
I/OggExtractor(  285): ~MyVorbisExtractor ++ 
,I/OggExtractor(  285): ~MyVorbisExtractor --
I/OggExtractor(  285): ~OggExtractor --
,I/AudioPlayer(  285): reset out
,V/AwesomePlayer(  285): reset_l() mAudioPlayer successfully deleted
I/SecVideoCapture(  285): SecVideoCapture destructor
I/SecVideoCapture(  285): reset
V/AwesomePlayer(  285): mSecCapture clear
,I/SecMediaClock(  285): SecMediaClock destructor
V/AwesomePlayer(  285): mSecMediaClock clear
V/StagefrightPlayer(  285): ~StagefrightPlayer
V/StagefrightPlayer(  285): reset
V/AwesomePlayer(  285): reset_l()
,V/AwesomePlayer(  285): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  285): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  285): mAudioTrackVector clear
V/AwesomePlayer(  285): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  285): mSecCapture clear
,V/AwesomePlayer(  285): mSecMediaClock clear
V/AwesomePlayer(  285): destructor
,V/AwesomePlayer(  285): reset_l()
,V/AwesomePlayer(  285): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  285): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  285): mAudioTrackVector clear
V/AwesomePlayer(  285): reset_l() mAudioPlayer successfully deleted
,V/AwesomePlayer(  285): mSecCapture clear
V/AwesomePlayer(  285): mSecMediaClock clear
,V/MediaPlayer( 8121): decode(40, 19266876, 23389)
I/SELinux ( 8229): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,V/MediaPlayerService(  285): decode(29, 19266876, 23389)
W/libprocessgroup(  890): failed to open /acct/uid_10114/pid_6187/cgroup.procs: No such file or directory
,V/MediaPlayerService(  285): player type = 3
V/AwesomePlayer(  285): setDefault
V/AwesomePlayer(  285): constructor
V/AwesomePlayer(  285): setDefault
V/AwesomePlayer(  285): reset_l()
V/AwesomePlayer(  285): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  285): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  285): mAudioTrackVector clear
V/AwesomePlayer(  285): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  285): mSecCapture clear
V/AwesomePlayer(  285): mSecMediaClock clear
V/StagefrightPlayer(  285): StagefrightPlayer
V/AwesomePlayer(  285): setListener
V/StagefrightPlayer(  285): initCheck
V/AwesomePlayer(  285): setAudioSink
V/StagefrightPlayer(  285): setDataSource(29, 19266876, 23389)
V/AwesomePlayer(  285): reset_l()
V/AwesomePlayer(  285): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  285): notify(0xb0618420, 8, 0, 0)
V/AudioCache(  285): ignored
V/AwesomePlayer(  285): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  285): mAudioTrackVector clear
V/AwesomePlayer(  285): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  285): mSecCapture clear
V/AwesomePlayer(  285): mSecMediaClock clear
D/Utils   (  285): printFileName fd(31) -> /system/priv-app/SHealth3_5/SHealth3_5.apk
I/SELinux ( 8229): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 8229): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
V/AwesomePlayer(  285): track of type 'audio/vorbis' does not publish bitrate
V/AwesomePlayer(  285): mBitrate = -1 bits/sec
I/OggExtractor(  285): OggSource::OggSource() mExtractor ref count = 4
V/AwesomePlayer(  285): current audio track index (0) is added to vector
V/AwesomePlayer(  285): setDataSource_l: Audio(1), Video(0)
I/AwesomePlayer(  285): checkRightsStatus is not necessary - AwesomePlayer::setDataSource_l
V/MediaPlayerService(  285): prepare
V/AwesomePlayer(  285): prepareAsync
V/MediaPlayerService(  285): wait for prepare
V/AwesomePlayer(  285): onPrepareAsyncEvent
I/SecMediaClock(  285): SecMediaClock constructor
I/SecMediaClock(  285): reset
I/SecVideoCapture(  285): SecVideoCapture constructor
I/SecVideoCapture(  285): reset
V/AwesomePlayer(  285): initAudioDecoder
V/AwesomePlayer(  285): checkOffloadExceptions is true
V/AudioPolicyManager(  285): isOffloadSupported: SR=44100, CM=0x3, Format=0x7000000, StreamType=-1, BitRate=4294967295, duration=1250000 us, has_video=0
V/AudioPolicyManager(  285): isOffloadSupported: stream_type != MUSIC, returning false
I/OMXCodec(  285): Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
,I/OMXCodec(  285): Successfully allocated OMX node 'OMX.google.vorbis.decoder'
,I/OMXCodec(  285): >>>UHQA initOutputFormat 16
I/AwesomePlayer(  285): Could not offload audio decode, try pcm offload
V/AudioPolicyManager(  285): isOffloadSupported: SR=44100, CM=0x1, Format=0x1c000001, StreamType=-1, BitRate=4294967295, duration=1250000 us, has_video=0
V/AudioPolicyManager(  285): isOffloadSupported: stream_type != MUSIC, returning false
I/OMXCodec(  285): [OMX.google.vorbis.decoder] OMXCodec::start mState=1
,I/OMXCodec(  285): [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
I/OMXCodec(  285): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
I/OMXCodec(  285): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
,V/AwesomePlayer(  285): finishAsyncPrepare_l
V/AwesomePlayer(  285): notifyListner_l() msg (200-MEDIA_INFO), ext1 (973), ext2 (0)
V/AudioCache(  285): notify(0xb0618420, 200, 973, 0)
V/AudioCache(  285): ignored
V/AwesomePlayer(  285): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache(  285): notify(0xb0618420, 5, 0, 0)
V/AudioCache(  285): ignored
V/AwesomePlayer(  285): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache(  285): notify(0xb0618420, 1, 0, 0)
V/AudioCache(  285): prepared
V/AudioCache(  285): wait - success
V/MediaPlayerService(  285): start
V/StagefrightPlayer(  285): start
V/AwesomePlayer(  285): play
V/AwesomePlayer(  285): AwesomePlayer::play_l():: This is not a DRM content
V/AwesomePlayer(  285): startAudioPlayer_l, sendErrorNotification (0)
D/AudioPlayer(  285): start of Playback, useOffload 0
,I/OMXCodec(  285): [OMX.google.vorbis.decoder] 0onCmdComplete  mState =  7
I/OMXCodec(  285): [OMX.google.vorbis.decoder] PORT_DISABLED(1)
I/OMXCodec(  285): >>>UHQA initOutputFormat 16
I/OMXCodec(  285): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
,I/AudioPlayer(  285): Audio channels(2)
I/AudioPlayer(  285): Audioplayer kKeyAudioPCMFormat:0, 1, 0
I/AudioPlayer(  285): Audioplayer kKeyAudioPCMFormat read fail(2, 1)
V/AudioCache(  285): open(44100, 2, 0x0, 1, 0)
,V/AwesomePlayer(  285): notifyListner_l() msg (6-MEDIA_STARTED), ext1 (0), ext2 (0)
V/AudioCache(  285): notify(0xb0618420, 6, 0, 0)
V/AudioCache(  285): ignored
V/AwesomePlayer(  285): addBatteryData
V/MediaPlayerService(  285): wait for playback complete
,I/AudioPlayer(  285): First fillBuffer call!!
I/AudioPlayer(  285): >>> setAudioEffect Read mAudioFormat : 1, event : 235670794, value : 319688206
E/AudioPlayer(  285): >>> setAudioEffect Error mAudioFormat : 1, event : 235670794, value : 319688206
,D/TimaKeyStoreProvider( 8229): TimaSignature is unavailable
,D/ActivityThread( 8229): Added TimaKeyStore provider
,I/OMXCodec(  285): [OMX.google.vorbis.decoder] End Of Stream
,V/AwesomePlayer(  285): postAudioEOS delayUs (0)
,V/AwesomePlayer(  285): onCheckAudioStatus
V/AwesomePlayer(  285): onCheckAudioStatus() set AUDIO_AT_EOS flag
V/AwesomePlayer(  285): onStreamDone
V/AwesomePlayer(  285): MEDIA_PLAYBACK_COMPLETE
V/AwesomePlayer(  285): notifyListner_l() msg (2-MEDIA_PLAYBACK_COMPLETE), ext1 (0), ext2 (0)
,V/AudioCache(  285): notify(0xb0618420, 2, 0, 0)
V/AudioCache(  285): playback complete - thread will wake up later
V/AwesomePlayer(  285): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache(  285): notify(0xb0618420, 7, 0, 0)
V/AudioCache(  285): ignored
V/AwesomePlayer(  285): cancelPlayerEvents (keepNotifications=1)
,V/AwesomePlayer(  285): addBatteryData
V/AudioCache(  285): wait - success
V/StagefrightPlayer(  285): reset
,V/AwesomePlayer(  285): reset_l()
V/AwesomePlayer(  285): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  285): notify(0xb0618420, 8, 0, 0)
V/AudioCache(  285): ignored
V/AwesomePlayer(  285): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  285): mAudioTrackVector clear
D/AudioPlayer(  285): reset: mPlaying=0 mReachedEOS=1 useOffload=0
I/OMXCodec(  285): [OMX.google.vorbis.decoder] stop mState=4
I/OMXCodec(  285): [OMX.google.vorbis.decoder] stop() sendCommand(0x7a, OMX_CommandStateSet, OMX_StateIdle)
I/OMXCodec(  285): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
,I/OMXCodec(  285): [OMX.google.vorbis.decoder] stopOmxComponent_l() mstate = 1
I/OggExtractor(  285): OggSource::stop() mExtractor ref count = 1
I/OggExtractor(  285): OggSource::~OggSource() mExtractor !mStarted ref count = 1
I/OggExtractor(  285): ~OggSource --
I/OggExtractor(  285): ~OggExtractor ++
I/OggExtractor(  285): ~MyVorbisExtractor ++ 
I/OggExtractor(  285): ~MyVorbisExtractor --
I/OggExtractor(  285): ~OggExtractor --
,I/AudioPlayer(  285): reset out
V/AwesomePlayer(  285): reset_l() mAudioPlayer successfully deleted
I/SecVideoCapture(  285): SecVideoCapture destructor
I/SecVideoCapture(  285): reset
V/AwesomePlayer(  285): mSecCapture clear
I/SecMediaClock(  285): SecMediaClock destructor
V/AwesomePlayer(  285): mSecMediaClock clear
V/StagefrightPlayer(  285): ~StagefrightPlayer
V/StagefrightPlayer(  285): reset
V/AwesomePlayer(  285): reset_l()
V/AwesomePlayer(  285): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  285): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  285): mAudioTrackVector clear
V/AwesomePlayer(  285): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  285): mSecCapture clear
V/AwesomePlayer(  285): mSecMediaClock clear
V/AwesomePlayer(  285): destructor
V/AwesomePlayer(  285): reset_l()
V/AwesomePlayer(  285): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  285): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  285): mAudioTrackVector clear
V/AwesomePlayer(  285): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  285): mSecCapture clear
V/AwesomePlayer(  285): mSecMediaClock clear
V/MediaPlayer( 8121): decode(41, 19156232, 8154)
V/MediaPlayerService(  285): decode(30, 19156232, 8154)
,V/MediaPlayerService(  285): player type = 3
V/AwesomePlayer(  285): setDefault
V/AwesomePlayer(  285): constructor
V/AwesomePlayer(  285): setDefault
V/AwesomePlayer(  285): reset_l()
V/AwesomePlayer(  285): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  285): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  285): mAudioTrackVector clear
V/AwesomePlayer(  285): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  285): mSecCapture clear
V/AwesomePlayer(  285): mSecMediaClock clear
V/StagefrightPlayer(  285): StagefrightPlayer
V/AwesomePlayer(  285): setListener
V/StagefrightPlayer(  285): initCheck
V/AwesomePlayer(  285): setAudioSink
V/StagefrightPlayer(  285): setDataSource(30, 19156232, 8154)
V/AwesomePlayer(  285): reset_l()
V/AwesomePlayer(  285): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  285): notify(0xb050f1a0, 8, 0, 0)
V/AudioCache(  285): ignored
V/AwesomePlayer(  285): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  285): mAudioTrackVector clear
V/AwesomePlayer(  285): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  285): mSecCapture clear
V/AwesomePlayer(  285): mSecMediaClock clear
D/Utils   (  285): printFileName fd(31) -> /system/priv-app/SHealth3_5/SHealth3_5.apk
,V/AwesomePlayer(  285): track of type 'audio/vorbis' does not publish bitrate
V/AwesomePlayer(  285): mBitrate = -1 bits/sec
I/OggExtractor(  285): OggSource::OggSource() mExtractor ref count = 4
V/AwesomePlayer(  285): current audio track index (0) is added to vector
V/AwesomePlayer(  285): setDataSource_l: Audio(1), Video(0)
I/AwesomePlayer(  285): checkRightsStatus is not necessary - AwesomePlayer::setDataSource_l
V/MediaPlayerService(  285): prepare
V/AwesomePlayer(  285): prepareAsync
V/MediaPlayerService(  285): wait for prepare
V/AwesomePlayer(  285): onPrepareAsyncEvent
I/SecMediaClock(  285): SecMediaClock constructor
I/SecMediaClock(  285): reset
I/SecVideoCapture(  285): SecVideoCapture constructor
I/SecVideoCapture(  285): reset
V/AwesomePlayer(  285): initAudioDecoder
V/AwesomePlayer(  285): checkOffloadExceptions is true
V/AudioPolicyManager(  285): isOffloadSupported: SR=44100, CM=0x1, Format=0x7000000, StreamType=-1, BitRate=4294967295, duration=405328 us, has_video=0
V/AudioPolicyManager(  285): isOffloadSupported: stream_type != MUSIC, returning false
I/OMXCodec(  285): Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
,I/OMXCodec(  285): Successfully allocated OMX node 'OMX.google.vorbis.decoder'
I/OMXCodec(  285): >>>UHQA initOutputFormat 16
I/AwesomePlayer(  285): Could not offload audio decode, try pcm offload
V/AudioPolicyManager(  285): isOffloadSupported: SR=44100, CM=0x1, Format=0x1c000001, StreamType=-1, BitRate=4294967295, duration=405328 us, has_video=0
V/AudioPolicyManager(  285): isOffloadSupported: stream_type != MUSIC, returning false
I/OMXCodec(  285): [OMX.google.vorbis.decoder] OMXCodec::start mState=1
I/OMXCodec(  285): [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
I/OMXCodec(  285): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
I/OMXCodec(  285): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
D/ResourcesManager( 8229): creating new AssetManager and set to /system/app/KnoxSetupWizardClient/KnoxSetupWizardClient.apk
,V/AwesomePlayer(  285): finishAsyncPrepare_l
V/AwesomePlayer(  285): notifyListner_l() msg (200-MEDIA_INFO), ext1 (973), ext2 (0)
V/AudioCache(  285): notify(0xb050f1a0, 200, 973, 0)
V/AudioCache(  285): ignored
V/AwesomePlayer(  285): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache(  285): notify(0xb050f1a0, 5, 0, 0)
V/AudioCache(  285): ignored
V/AwesomePlayer(  285): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache(  285): notify(0xb050f1a0, 1, 0, 0)
V/AudioCache(  285): prepared
V/AudioCache(  285): wait - success
V/MediaPlayerService(  285): start
V/StagefrightPlayer(  285): start
V/AwesomePlayer(  285): play
V/AwesomePlayer(  285): AwesomePlayer::play_l():: This is not a DRM content
V/AwesomePlayer(  285): startAudioPlayer_l, sendErrorNotification (0)
D/AudioPlayer(  285): start of Playback, useOffload 0
,I/OMXCodec(  285): [OMX.google.vorbis.decoder] 0onCmdComplete  mState =  7
I/OMXCodec(  285): [OMX.google.vorbis.decoder] PORT_DISABLED(1)
I/OMXCodec(  285): >>>UHQA initOutputFormat 16
I/OMXCodec(  285): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
,I/AudioPlayer(  285): Audio channels(1)
I/AudioPlayer(  285): Audioplayer kKeyAudioPCMFormat:0, 1, 0
I/AudioPlayer(  285): Audioplayer kKeyAudioPCMFormat read fail(1, 1)
V/AudioCache(  285): open(44100, 1, 0x0, 1, 0)
,V/AwesomePlayer(  285): notifyListner_l() msg (6-MEDIA_STARTED), ext1 (0), ext2 (0)
V/AudioCache(  285): notify(0xb050f1a0, 6, 0, 0)
V/AudioCache(  285): ignored
V/AwesomePlayer(  285): addBatteryData
V/MediaPlayerService(  285): wait for playback complete
I/AudioPlayer(  285): First fillBuffer call!!
,I/AudioPlayer(  285): >>> setAudioEffect Read mAudioFormat : 1, event : 168430090, value : 151652874
E/AudioPlayer(  285): >>> setAudioEffect Error mAudioFormat : 1, event : 168430090, value : 151652874
,I/OMXCodec(  285): [OMX.google.vorbis.decoder] End Of Stream
,W/libprocessgroup(  890): failed to open /acct/uid_10044/pid_7149/cgroup.procs: No such file or directory
V/AwesomePlayer(  285): postAudioEOS delayUs (0)
,V/AwesomePlayer(  285): onCheckAudioStatus
V/AwesomePlayer(  285): onCheckAudioStatus() set AUDIO_AT_EOS flag
V/AwesomePlayer(  285): onStreamDone
V/AwesomePlayer(  285): MEDIA_PLAYBACK_COMPLETE
V/AwesomePlayer(  285): notifyListner_l() msg (2-MEDIA_PLAYBACK_COMPLETE), ext1 (0), ext2 (0)
V/AudioCache(  285): notify(0xb050f1a0, 2, 0, 0)
V/AudioCache(  285): playback complete - thread will wake up later
V/AwesomePlayer(  285): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache(  285): notify(0xb050f1a0, 7, 0, 0)
V/AudioCache(  285): ignored
V/AwesomePlayer(  285): cancelPlayerEvents (keepNotifications=1)
V/AwesomePlayer(  285): addBatteryData
V/AudioCache(  285): wait - success
V/StagefrightPlayer(  285): reset
V/AwesomePlayer(  285): reset_l()
V/AwesomePlayer(  285): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  285): notify(0xb050f1a0, 8, 0, 0)
V/AudioCache(  285): ignored
V/AwesomePlayer(  285): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  285): mAudioTrackVector clear
D/AudioPlayer(  285): reset: mPlaying=0 mReachedEOS=1 useOffload=0
I/OMXCodec(  285): [OMX.google.vorbis.decoder] stop mState=4
I/OMXCodec(  285): [OMX.google.vorbis.decoder] stop() sendCommand(0x7b, OMX_CommandStateSet, OMX_StateIdle)
I/OMXCodec(  285): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
I/OMXCodec(  285): [OMX.google.vorbis.decoder] stopOmxComponent_l() mstate = 1
I/OggExtractor(  285): OggSource::stop() mExtractor ref count = 1
I/OggExtractor(  285): OggSource::~OggSource() mExtractor !mStarted ref count = 1
I/OggExtractor(  285): ~OggSource --
I/OggExtractor(  285): ~OggExtractor ++
I/OggExtractor(  285): ~MyVorbisExtractor ++ 
I/OggExtractor(  285): ~MyVorbisExtractor --
I/OggExtractor(  285): ~OggExtractor --
,I/AudioPlayer(  285): reset out
V/AwesomePlayer(  285): reset_l() mAudioPlayer successfully deleted
I/SecVideoCapture(  285): SecVideoCapture destructor
I/SecVideoCapture(  285): reset
V/AwesomePlayer(  285): mSecCapture clear
I/SecMediaClock(  285): SecMediaClock destructor
V/AwesomePlayer(  285): mSecMediaClock clear
V/StagefrightPlayer(  285): ~StagefrightPlayer
V/StagefrightPlayer(  285): reset
V/AwesomePlayer(  285): reset_l()
V/AwesomePlayer(  285): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  285): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  285): mAudioTrackVector clear
V/AwesomePlayer(  285): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  285): mSecCapture clear
V/AwesomePlayer(  285): mSecMediaClock clear
V/AwesomePlayer(  285): destructor
V/AwesomePlayer(  285): reset_l()
V/AwesomePlayer(  285): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  285): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  285): mAudioTrackVector clear
V/AwesomePlayer(  285): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  285): mSecCapture clear
V/AwesomePlayer(  285): mSecMediaClock clear
V/MediaPlayer( 8121): decode(42, 19129712, 4804)
V/MediaPlayerService(  285): decode(30, 19129712, 4804)
,V/MediaPlayerService(  285): player type = 3
V/AwesomePlayer(  285): setDefault
V/AwesomePlayer(  285): constructor
V/AwesomePlayer(  285): setDefault
V/AwesomePlayer(  285): reset_l()
V/AwesomePlayer(  285): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
,V/AwesomePlayer(  285): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  285): mAudioTrackVector clear
V/AwesomePlayer(  285): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  285): mSecCapture clear
V/AwesomePlayer(  285): mSecMediaClock clear
V/StagefrightPlayer(  285): StagefrightPlayer
V/AwesomePlayer(  285): setListener
V/StagefrightPlayer(  285): initCheck
,V/AwesomePlayer(  285): setAudioSink
V/StagefrightPlayer(  285): setDataSource(30, 19129712, 4804)
V/AwesomePlayer(  285): reset_l()
V/AwesomePlayer(  285): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  285): notify(0xb050f0b0, 8, 0, 0)
V/AudioCache(  285): ignored
V/AwesomePlayer(  285): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  285): mAudioTrackVector clear
,V/AwesomePlayer(  285): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  285): mSecCapture clear
V/AwesomePlayer(  285): mSecMediaClock clear
D/Utils   (  285): printFileName fd(31) -> /system/priv-app/SHealth3_5/SHealth3_5.apk
V/AwesomePlayer(  285): track of type 'audio/vorbis' does not publish bitrate
V/AwesomePlayer(  285): mBitrate = -1 bits/sec
,I/OggExtractor(  285): OggSource::OggSource() mExtractor ref count = 4
V/AwesomePlayer(  285): current audio track index (0) is added to vector
V/AwesomePlayer(  285): setDataSource_l: Audio(1), Video(0)
I/AwesomePlayer(  285): checkRightsStatus is not necessary - AwesomePlayer::setDataSource_l
V/MediaPlayerService(  285): prepare
V/AwesomePlayer(  285): prepareAsync
V/MediaPlayerService(  285): wait for prepare
V/AwesomePlayer(  285): onPrepareAsyncEvent
,I/SecMediaClock(  285): SecMediaClock constructor
I/SecMediaClock(  285): reset
I/SecVideoCapture(  285): SecVideoCapture constructor
I/SecVideoCapture(  285): reset
V/AwesomePlayer(  285): initAudioDecoder
V/AwesomePlayer(  285): checkOffloadExceptions is true
V/AudioPolicyManager(  285): isOffloadSupported: SR=44100, CM=0x1, Format=0x7000000, StreamType=-1, BitRate=4294967295, duration=110476 us, has_video=0
V/AudioPolicyManager(  285): isOffloadSupported: stream_type != MUSIC, returning false
,I/OMXCodec(  285): Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
I/OMXCodec(  285): Successfully allocated OMX node 'OMX.google.vorbis.decoder'
I/OMXCodec(  285): >>>UHQA initOutputFormat 16
I/AwesomePlayer(  285): Could not offload audio decode, try pcm offload
V/AudioPolicyManager(  285): isOffloadSupported: SR=44100, CM=0x1, Format=0x1c000001, StreamType=-1, BitRate=4294967295, duration=110476 us, has_video=0
V/AudioPolicyManager(  285): isOffloadSupported: stream_type != MUSIC, returning false
,I/OMXCodec(  285): [OMX.google.vorbis.decoder] OMXCodec::start mState=1
I/OMXCodec(  285): [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
I/OMXCodec(  285): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
I/OMXCodec(  285): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
V/AwesomePlayer(  285): finishAsyncPrepare_l
V/AwesomePlayer(  285): notifyListner_l() msg (200-MEDIA_INFO), ext1 (973), ext2 (0)
,V/AudioCache(  285): notify(0xb050f0b0, 200, 973, 0)
V/AudioCache(  285): ignored
V/AwesomePlayer(  285): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache(  285): notify(0xb050f0b0, 5, 0, 0)
V/AudioCache(  285): ignored
V/AwesomePlayer(  285): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache(  285): notify(0xb050f0b0, 1, 0, 0)
,V/AudioCache(  285): prepared
V/AudioCache(  285): wait - success
V/MediaPlayerService(  285): start
V/StagefrightPlayer(  285): start
V/AwesomePlayer(  285): play
V/AwesomePlayer(  285): AwesomePlayer::play_l():: This is not a DRM content
V/AwesomePlayer(  285): startAudioPlayer_l, sendErrorNotification (0)
,D/AudioPlayer(  285): start of Playback, useOffload 0
,I/OMXCodec(  285): [OMX.google.vorbis.decoder] 0onCmdComplete  mState =  7,
I/OMXCodec(  285): [OMX.google.vorbis.decoder] PORT_DISABLED(1)
I/OMXCodec(  285): >>>UHQA initOutputFormat 16
I/OMXCodec(  285): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
,I/AudioPlayer(  285): Audio channels(1)
I/AudioPlayer(  285): Audioplayer kKeyAudioPCMFormat:0, 1, 0
,I/AudioPlayer(  285): Audioplayer kKeyAudioPCMFormat read fail(1, 1)
V/AudioCache(  285): open(44100, 1, 0x0, 1, 0)
V/AwesomePlayer(  285): notifyListner_l() msg (6-MEDIA_STARTED), ext1 (0), ext2 (0)
V/AudioCache(  285): notify(0xb050f0b0, 6, 0, 0)
,V/AudioCache(  285): ignored
V/AwesomePlayer(  285): addBatteryData
I/AudioPlayer(  285): First fillBuffer call!!
V/MediaPlayerService(  285): wait for playback complete
,I/AudioPlayer(  285): >>> setAudioEffect Read mAudioFormat : 1, event : 168430090, value : 151652874
E/AudioPlayer(  285): >>> setAudioEffect Error mAudioFormat : 1, event : 168430090, value : 151652874
,I/OMXCodec(  285): [OMX.google.vorbis.decoder] End Of Stream
,V/AwesomePlayer(  285): postAudioEOS delayUs (0)
V/AwesomePlayer(  285): onCheckAudioStatus
V/AwesomePlayer(  285): onCheckAudioStatus() set AUDIO_AT_EOS flag
V/AwesomePlayer(  285): onStreamDone
V/AwesomePlayer(  285): MEDIA_PLAYBACK_COMPLETE
V/AwesomePlayer(  285): notifyListner_l() msg (2-MEDIA_PLAYBACK_COMPLETE), ext1 (0), ext2 (0)
V/AudioCache(  285): notify(0xb050f0b0, 2, 0, 0)
V/AudioCache(  285): playback complete - thread will wake up later
V/AwesomePlayer(  285): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache(  285): notify(0xb050f0b0, 7, 0, 0)
V/AudioCache(  285): ignored
V/AwesomePlayer(  285): cancelPlayerEvents (keepNotifications=1)
V/AudioCache(  285): wait - success
V/StagefrightPlayer(  285): reset
V/AwesomePlayer(  285): addBatteryData
V/AwesomePlayer(  285): reset_l()
V/AwesomePlayer(  285): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  285): notify(0xb050f0b0, 8, 0, 0)
V/AudioCache(  285): ignored
V/AwesomePlayer(  285): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  285): mAudioTrackVector clear
D/AudioPlayer(  285): reset: mPlaying=0 mReachedEOS=1 useOffload=0
I/OMXCodec(  285): [OMX.google.vorbis.decoder] stop mState=4
I/OMXCodec(  285): [OMX.google.vorbis.decoder] stop() sendCommand(0x7c, OMX_CommandStateSet, OMX_StateIdle)
I/OMXCodec(  285): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
I/OMXCodec(  285): [OMX.google.vorbis.decoder] stopOmxComponent_l() mstate = 1
I/OggExtractor(  285): OggSource::stop() mExtractor ref count = 1
I/OggExtractor(  285): OggSource::~OggSource() mExtractor !mStarted ref count = 1
I/OggExtractor(  285): ~OggSource --
I/OggExtractor(  285): ~OggExtractor ++
I/OggExtractor(  285): ~MyVorbisExtractor ++ 
I/OggExtractor(  285): ~MyVorbisExtractor --
I/OggExtractor(  285): ~OggExtractor --
,I/AudioPlayer(  285): reset out
V/AwesomePlayer(  285): reset_l() mAudioPlayer successfully deleted
I/SecVideoCapture(  285): SecVideoCapture destructor
I/SecVideoCapture(  285): reset
V/AwesomePlayer(  285): mSecCapture clear
I/SecMediaClock(  285): SecMediaClock destructor
V/AwesomePlayer(  285): mSecMediaClock clear
V/StagefrightPlayer(  285): ~StagefrightPlayer
V/StagefrightPlayer(  285): reset
V/AwesomePlayer(  285): reset_l()
V/AwesomePlayer(  285): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  285): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  285): mAudioTrackVector clear
V/AwesomePlayer(  285): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  285): mSecCapture clear
V/AwesomePlayer(  285): mSecMediaClock clear
V/AwesomePlayer(  285): destructor
V/AwesomePlayer(  285): reset_l()
V/AwesomePlayer(  285): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  285): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  285): mAudioTrackVector clear
V/AwesomePlayer(  285): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  285): mSecCapture clear
V/AwesomePlayer(  285): mSecMediaClock clear
V/MediaPlayer( 8121): decode(43, 19099164, 9400)
,V/MediaPlayerService(  285): decode(30, 19099164, 9400)
V/MediaPlayerService(  285): player type = 3
,V/AwesomePlayer(  285): setDefault
V/AwesomePlayer(  285): constructor
V/AwesomePlayer(  285): setDefault
V/AwesomePlayer(  285): reset_l()
,V/AwesomePlayer(  285): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  285): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  285): mAudioTrackVector clear
V/AwesomePlayer(  285): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  285): mSecCapture clear
V/AwesomePlayer(  285): mSecMediaClock clear
V/StagefrightPlayer(  285): StagefrightPlayer
,V/AwesomePlayer(  285): setListener
V/StagefrightPlayer(  285): initCheck
V/AwesomePlayer(  285): setAudioSink
V/StagefrightPlayer(  285): setDataSource(30, 19099164, 9400)
V/AwesomePlayer(  285): reset_l()
V/AwesomePlayer(  285): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
,V/AudioCache(  285): notify(0xb0618330, 8, 0, 0)
V/AudioCache(  285): ignored
V/AwesomePlayer(  285): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  285): mAudioTrackVector clear
V/AwesomePlayer(  285): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  285): mSecCapture clear
V/AwesomePlayer(  285): mSecMediaClock clear
,D/Utils   (  285): printFileName fd(31) -> /system/priv-app/SHealth3_5/SHealth3_5.apk
,V/AwesomePlayer(  285): track of type 'audio/vorbis' does not publish bitrate
,V/AwesomePlayer(  285): mBitrate = -1 bits/sec
V/MediaPlayer( 8121): decode(49, 19172584, 4112)
I/OggExtractor(  285): OggSource::OggSource() mExtractor ref count = 4
V/AwesomePlayer(  285): current audio track index (0) is added to vector
V/AwesomePlayer(  285): setDataSource_l: Audio(1), Video(0)
V/MediaPlayerService(  285): decode(33, 19172584, 4112)
I/AwesomePlayer(  285): checkRightsStatus is not necessary - AwesomePlayer::setDataSource_l
V/MediaPlayerService(  285): prepare
,V/AwesomePlayer(  285): prepareAsync
V/MediaPlayerService(  285): player type = 3
V/AwesomePlayer(  285): setDefault
V/AwesomePlayer(  285): constructor
V/AwesomePlayer(  285): setDefault
V/AwesomePlayer(  285): reset_l()
V/AwesomePlayer(  285): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  285): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  285): mAudioTrackVector clear
V/AwesomePlayer(  285): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  285): mSecCapture clear
V/AwesomePlayer(  285): mSecMediaClock clear
V/StagefrightPlayer(  285): StagefrightPlayer
V/AwesomePlayer(  285): setListener
V/StagefrightPlayer(  285): initCheck
V/AwesomePlayer(  285): setAudioSink
V/StagefrightPlayer(  285): setDataSource(33, 19172584, 4112)
V/AwesomePlayer(  285): reset_l()
V/AwesomePlayer(  285): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  285): notify(0xb092b1f0, 8, 0, 0)
V/AudioCache(  285): ignored
V/AwesomePlayer(  285): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  285): mAudioTrackVector clear
V/AwesomePlayer(  285): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  285): mSecCapture clear
V/AwesomePlayer(  285): mSecMediaClock clear
D/Utils   (  285): printFileName fd(34) -> /system/priv-app/SHealth3_5/SHealth3_5.apk
,V/MediaPlayerService(  285): wait for prepare
V/AwesomePlayer(  285): onPrepareAsyncEvent
I/SecMediaClock(  285): SecMediaClock constructor
V/AwesomePlayer(  285): track of type 'audio/vorbis' does not publish bitrate
V/AwesomePlayer(  285): mBitrate = -1 bits/sec
I/OggExtractor(  285): OggSource::OggSource() mExtractor ref count = 4
V/AwesomePlayer(  285): current audio track index (0) is added to vector
V/AwesomePlayer(  285): setDataSource_l: Audio(1), Video(0)
I/AwesomePlayer(  285): checkRightsStatus is not necessary - AwesomePlayer::setDataSource_l
V/MediaPlayerService(  285): prepare
V/AwesomePlayer(  285): prepareAsync
V/MediaPlayerService(  285): wait for prepare
,I/SecMediaClock(  285): reset
I/SecVideoCapture(  285): SecVideoCapture constructor
I/SecVideoCapture(  285): reset
V/AwesomePlayer(  285): initAudioDecoder
V/AwesomePlayer(  285): checkOffloadExceptions is true
V/AudioPolicyManager(  285): isOffloadSupported: SR=44100, CM=0x1, Format=0x7000000, StreamType=-1, BitRate=4294967295, duration=731360 us, has_video=0
V/AudioPolicyManager(  285): isOffloadSupported: stream_type != MUSIC, returning false
I/OMXCodec(  285): Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
V/AwesomePlayer(  285): onPrepareAsyncEvent
I/SecMediaClock(  285): SecMediaClock constructor
I/SecMediaClock(  285): reset
I/SecVideoCapture(  285): SecVideoCapture constructor
I/SecVideoCapture(  285): reset
V/AwesomePlayer(  285): initAudioDecoder
V/AwesomePlayer(  285): checkOffloadExceptions is true
V/AudioPolicyManager(  285): isOffloadSupported: SR=44100, CM=0x1, Format=0x7000000, StreamType=-1, BitRate=4294967295, duration=4331 us, has_video=0
V/AudioPolicyManager(  285): isOffloadSupported: stream_type != MUSIC, returning false
I/OMXCodec(  285): Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
,D/ShortcutReceiver( 8229):  ShortcutReceiver onReceive() intent: android.intent.action.PACKAGE_CHANGED
,I/OMXCodec(  285): Successfully allocated OMX node 'OMX.google.vorbis.decoder'
,I/OMXCodec(  285): >>>UHQA initOutputFormat 16
I/AwesomePlayer(  285): Could not offload audio decode, try pcm offload
V/AudioPolicyManager(  285): isOffloadSupported: SR=44100, CM=0x1, Format=0x1c000001, StreamType=-1, BitRate=4294967295, duration=4331 us, has_video=0
V/AudioPolicyManager(  285): isOffloadSupported: stream_type != MUSIC, returning false
I/OMXCodec(  285): [OMX.google.vorbis.decoder] OMXCodec::start mState=1
,I/OMXCodec(  285): [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
I/OMXCodec(  285): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
I/OMXCodec(  285): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
I/OMXCodec(  285): Successfully allocated OMX node 'OMX.google.vorbis.decoder'
,I/OMXCodec(  285): >>>UHQA initOutputFormat 16
I/AwesomePlayer(  285): Could not offload audio decode, try pcm offload
V/AwesomePlayer(  285): finishAsyncPrepare_l
V/AwesomePlayer(  285): notifyListner_l() msg (200-MEDIA_INFO), ext1 (973), ext2 (0)
V/AudioCache(  285): notify(0xb092b1f0, 200, 973, 0)
V/AudioCache(  285): ignored
V/AwesomePlayer(  285): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache(  285): notify(0xb092b1f0, 5, 0, 0)
V/AudioCache(  285): ignored
V/AwesomePlayer(  285): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache(  285): notify(0xb092b1f0, 1, 0, 0)
V/AudioCache(  285): prepared
,V/AudioPolicyManager(  285): isOffloadSupported: SR=44100, CM=0x1, Format=0x1c000001, StreamType=-1, BitRate=4294967295, duration=731360 us, has_video=0
V/AudioPolicyManager(  285): isOffloadSupported: stream_type != MUSIC, returning false
V/AudioCache(  285): wait - success
V/MediaPlayerService(  285): start
V/StagefrightPlayer(  285): start
V/AwesomePlayer(  285): play
V/AwesomePlayer(  285): AwesomePlayer::play_l():: This is not a DRM content
V/AwesomePlayer(  285): startAudioPlayer_l, sendErrorNotification (0)
D/AudioPlayer(  285): start of Playback, useOffload 0
I/OMXCodec(  285): [OMX.google.vorbis.decoder] OMXCodec::start mState=1
,I/OMXCodec(  285): [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
I/OMXCodec(  285): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
,I/OMXCodec(  285): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
V/AwesomePlayer(  285): finishAsyncPrepare_l
V/AwesomePlayer(  285): notifyListner_l() msg (200-MEDIA_INFO), ext1 (973), ext2 (0)
,V/AudioCache(  285): notify(0xb0618330, 200, 973, 0)
V/AudioCache(  285): ignored
V/AwesomePlayer(  285): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache(  285): notify(0xb0618330, 5, 0, 0)
V/AudioCache(  285): ignored
V/AwesomePlayer(  285): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache(  285): notify(0xb0618330, 1, 0, 0)
V/AudioCache(  285): prepared
V/AudioCache(  285): wait - success
V/MediaPlayerService(  285): start
V/StagefrightPlayer(  285): start
,V/AwesomePlayer(  285): play
V/AwesomePlayer(  285): AwesomePlayer::play_l():: This is not a DRM content
V/AwesomePlayer(  285): startAudioPlayer_l, sendErrorNotification (0)
D/AudioPlayer(  285): start of Playback, useOffload 0
,I/OMXCodec(  285): [OMX.google.vorbis.decoder] End Of Stream
,I/OMXCodec(  285): [OMX.google.vorbis.decoder] 0onCmdComplete  mState =  7
I/OMXCodec(  285): [OMX.google.vorbis.decoder] PORT_DISABLED(1)
I/OMXCodec(  285): [OMX.google.vorbis.decoder] 0onCmdComplete  mState =  7
I/OMXCodec(  285): [OMX.google.vorbis.decoder] PORT_DISABLED(1)
I/OMXCodec(  285): >>>UHQA initOutputFormat 16
I/OMXCodec(  285): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
I/OMXCodec(  285): >>>UHQA initOutputFormat 16
,I/OMXCodec(  285): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
,I/AudioPlayer(  285): Audio channels(1)
I/AudioPlayer(  285): Audioplayer kKeyAudioPCMFormat:0, 1, 0
I/AudioPlayer(  285): Audioplayer kKeyAudioPCMFormat read fail(1, 1)
V/AudioCache(  285): open(44100, 1, 0x0, 1, 0)
I/AudioPlayer(  285): Audio channels(1)
,I/AudioPlayer(  285): Audioplayer kKeyAudioPCMFormat:0, 1, 0
I/AudioPlayer(  285): Audioplayer kKeyAudioPCMFormat read fail(1, 1)
V/AudioCache(  285): open(44100, 1, 0x0, 1, 0)
V/AwesomePlayer(  285): notifyListner_l() msg (6-MEDIA_STARTED), ext1 (0), ext2 (0)
,V/AwesomePlayer(  285): notifyListner_l() msg (6-MEDIA_STARTED), ext1 (0), ext2 (0)
V/AudioCache(  285): notify(0xb0618330, 6, 0, 0)
V/AudioCache(  285): notify(0xb092b1f0, 6, 0, 0)
V/AudioCache(  285): ignored
V/AwesomePlayer(  285): addBatteryData
I/AudioPlayer(  285): First fillBuffer call!!
V/AudioCache(  285): ignored
V/AwesomePlayer(  285): addBatteryData
,V/MediaPlayerService(  285): wait for playback complete
V/MediaPlayerService(  285): wait for playback complete
I/AudioPlayer(  285): >>> setAudioEffect Read mAudioFormat : 1, event : 4587583, value : 4390976
,E/AudioPlayer(  285): >>> setAudioEffect Error mAudioFormat : 1, event : 4587583, value : 4390976
I/AudioPlayer(  285): First fillBuffer call!!
I/AudioPlayer(  285): >>> setAudioEffect Read mAudioFormat : 1, event : 168430090, value : 151652874
E/AudioPlayer(  285): >>> setAudioEffect Error mAudioFormat : 1, event : 168430090, value : 151652874
V/AwesomePlayer(  285): postAudioEOS delayUs (0)
V/AwesomePlayer(  285): onCheckAudioStatus
V/AwesomePlayer(  285): onCheckAudioStatus() set AUDIO_AT_EOS flag
V/AwesomePlayer(  285): onStreamDone
V/AwesomePlayer(  285): MEDIA_PLAYBACK_COMPLETE
V/AwesomePlayer(  285): notifyListner_l() msg (2-MEDIA_PLAYBACK_COMPLETE), ext1 (0), ext2 (0)
V/AudioCache(  285): notify(0xb092b1f0, 2, 0, 0)
V/AudioCache(  285): playback complete - thread will wake up later
V/AwesomePlayer(  285): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache(  285): notify(0xb092b1f0, 7, 0, 0)
V/AudioCache(  285): ignored
V/AwesomePlayer(  285): cancelPlayerEvents (keepNotifications=1)
V/AwesomePlayer(  285): addBatteryData
V/AudioCache(  285): wait - success
V/StagefrightPlayer(  285): reset
V/AwesomePlayer(  285): reset_l()
V/AwesomePlayer(  285): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  285): notify(0xb092b1f0, 8, 0, 0)
V/AudioCache(  285): ignored
V/AwesomePlayer(  285): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  285): mAudioTrackVector clear
D/AudioPlayer(  285): reset: mPlaying=0 mReachedEOS=1 useOffload=0
I/OMXCodec(  285): [OMX.google.vorbis.decoder] stop mState=4
I/OMXCodec(  285): [OMX.google.vorbis.decoder] stop() sendCommand(0x7e, OMX_CommandStateSet, OMX_StateIdle)
I/OMXCodec(  285): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
I/OMXCodec(  285): [OMX.google.vorbis.decoder] stopOmxComponent_l() mstate = 1
I/OggExtractor(  285): OggSource::stop() mExtractor ref count = 1
I/OggExtractor(  285): OggSource::~OggSource() mExtractor !mStarted ref count = 1
I/OggExtractor(  285): ~OggSource --
I/OggExtractor(  285): ~OggExtractor ++
I/OggExtractor(  285): ~MyVorbisExtractor ++ 
I/OggExtractor(  285): ~MyVorbisExtractor --
I/OggExtractor(  285): ~OggExtractor --
,I/AudioPlayer(  285): reset out
V/AwesomePlayer(  285): reset_l() mAudioPlayer successfully deleted
I/SecVideoCapture(  285): SecVideoCapture destructor
I/SecVideoCapture(  285): reset
V/AwesomePlayer(  285): mSecCapture clear
I/SecMediaClock(  285): SecMediaClock destructor
V/AwesomePlayer(  285): mSecMediaClock clear
V/StagefrightPlayer(  285): ~StagefrightPlayer
V/StagefrightPlayer(  285): reset
V/AwesomePlayer(  285): reset_l()
V/AwesomePlayer(  285): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  285): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  285): mAudioTrackVector clear
V/AwesomePlayer(  285): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  285): mSecCapture clear
V/AwesomePlayer(  285): mSecMediaClock clear
V/AwesomePlayer(  285): destructor
V/AwesomePlayer(  285): reset_l()
V/AwesomePlayer(  285): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  285): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  285): mAudioTrackVector clear
V/AwesomePlayer(  285): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  285): mSecCapture clear
V/AwesomePlayer(  285): mSecMediaClock clear
,I/OMXCodec(  285): [OMX.google.vorbis.decoder] End Of Stream
,V/AwesomePlayer(  285): postAudioEOS delayUs (0)
,V/AwesomePlayer(  285): onCheckAudioStatus
V/AwesomePlayer(  285): onCheckAudioStatus() set AUDIO_AT_EOS flag
V/AwesomePlayer(  285): onStreamDone
V/AwesomePlayer(  285): MEDIA_PLAYBACK_COMPLETE
V/AwesomePlayer(  285): notifyListner_l() msg (2-MEDIA_PLAYBACK_COMPLETE), ext1 (0), ext2 (0)
V/AudioCache(  285): notify(0xb0618330, 2, 0, 0)
V/AudioCache(  285): playback complete - thread will wake up later
V/AwesomePlayer(  285): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache(  285): notify(0xb0618330, 7, 0, 0)
V/AudioCache(  285): ignored
V/AwesomePlayer(  285): cancelPlayerEvents (keepNotifications=1)
,V/AwesomePlayer(  285): addBatteryData
V/AudioCache(  285): wait - success
V/StagefrightPlayer(  285): reset
,V/AwesomePlayer(  285): reset_l()
V/AwesomePlayer(  285): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  285): notify(0xb0618330, 8, 0, 0)
V/AudioCache(  285): ignored
V/AwesomePlayer(  285): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  285): mAudioTrackVector clear
D/AudioPlayer(  285): reset: mPlaying=0 mReachedEOS=1 useOffload=0
I/OMXCodec(  285): [OMX.google.vorbis.decoder] stop mState=4
I/OMXCodec(  285): [OMX.google.vorbis.decoder] stop() sendCommand(0x7d, OMX_CommandStateSet, OMX_StateIdle)
I/OMXCodec(  285): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
,I/OMXCodec(  285): [OMX.google.vorbis.decoder] stopOmxComponent_l() mstate = 1
I/OggExtractor(  285): OggSource::stop() mExtractor ref count = 1
I/OggExtractor(  285): OggSource::~OggSource() mExtractor !mStarted ref count = 1
I/OggExtractor(  285): ~OggSource --
I/OggExtractor(  285): ~OggExtractor ++
I/OggExtractor(  285): ~MyVorbisExtractor ++ 
I/OggExtractor(  285): ~MyVorbisExtractor --
I/OggExtractor(  285): ~OggExtractor --
,I/AudioPlayer(  285): reset out
V/AwesomePlayer(  285): reset_l() mAudioPlayer successfully deleted
I/SecVideoCapture(  285): SecVideoCapture destructor
I/SecVideoCapture(  285): reset
V/AwesomePlayer(  285): mSecCapture clear
I/SecMediaClock(  285): SecMediaClock destructor
V/AwesomePlayer(  285): mSecMediaClock clear
V/StagefrightPlayer(  285): ~StagefrightPlayer
V/StagefrightPlayer(  285): reset
V/AwesomePlayer(  285): reset_l()
V/AwesomePlayer(  285): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  285): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  285): mAudioTrackVector clear
V/AwesomePlayer(  285): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  285): mSecCapture clear
V/AwesomePlayer(  285): mSecMediaClock clear
V/AwesomePlayer(  285): destructor
,V/AwesomePlayer(  285): reset_l()
V/AwesomePlayer(  285): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  285): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  285): mAudioTrackVector clear
,V/AwesomePlayer(  285): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  285): mSecCapture clear
V/AwesomePlayer(  285): mSecMediaClock clear
,V/MediaPlayer( 8121): decode(44, 19307764, 52024)
V/MediaPlayerService(  285): decode(30, 19307764, 52024)
,V/MediaPlayerService(  285): player type = 3
V/AwesomePlayer(  285): setDefault
V/AwesomePlayer(  285): constructor
,V/AwesomePlayer(  285): setDefault
V/AwesomePlayer(  285): reset_l()
V/AwesomePlayer(  285): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  285): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  285): mAudioTrackVector clear
V/AwesomePlayer(  285): reset_l() mAudioPlayer successfully deleted
,V/AwesomePlayer(  285): mSecCapture clear
V/AwesomePlayer(  285): mSecMediaClock clear
V/StagefrightPlayer(  285): StagefrightPlayer
V/AwesomePlayer(  285): setListener
V/StagefrightPlayer(  285): initCheck
V/AwesomePlayer(  285): setAudioSink
,V/StagefrightPlayer(  285): setDataSource(30, 19307764, 52024)
V/AwesomePlayer(  285): reset_l()
V/AwesomePlayer(  285): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  285): notify(0xb06187e0, 8, 0, 0)
V/AudioCache(  285): ignored
,V/AwesomePlayer(  285): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  285): mAudioTrackVector clear
V/AwesomePlayer(  285): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  285): mSecCapture clear
V/AwesomePlayer(  285): mSecMediaClock clear
D/Utils   (  285): printFileName fd(31) -> /system/priv-app/SHealth3_5/SHealth3_5.apk
,I/ActivityManager(  890): Killing 7178:com.sec.android.app.videoplayer/u0a54 (adj 15): bgCount ##41
D/PackageBroadcastService( 2447): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.sec.enterprise.knox.cloudmdm.smdms
,V/AwesomePlayer(  285): track of type 'audio/vorbis' does not publish bitrate
,V/AwesomePlayer(  285): mBitrate = -1 bits/sec
I/OggExtractor(  285): OggSource::OggSource() mExtractor ref count = 4
V/AwesomePlayer(  285): current audio track index (0) is added to vector
V/AwesomePlayer(  285): setDataSource_l: Audio(1), Video(0)
I/AwesomePlayer(  285): checkRightsStatus is not necessary - AwesomePlayer::setDataSource_l
V/MediaPlayerService(  285): prepare
V/AwesomePlayer(  285): prepareAsync
,V/MediaPlayerService(  285): wait for prepare
V/AwesomePlayer(  285): onPrepareAsyncEvent
I/SecMediaClock(  285): SecMediaClock constructor
I/SecMediaClock(  285): reset
I/SecVideoCapture(  285): SecVideoCapture constructor
I/SecVideoCapture(  285): reset
V/AwesomePlayer(  285): initAudioDecoder
V/AwesomePlayer(  285): checkOffloadExceptions is true
V/AudioPolicyManager(  285): isOffloadSupported: SR=48000, CM=0x3, Format=0x7000000, StreamType=-1, BitRate=4294967295, duration=2880000 us, has_video=0
V/AudioPolicyManager(  285): isOffloadSupported: stream_type != MUSIC, returning false
I/OMXCodec(  285): Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
,I/OMXCodec(  285): Successfully allocated OMX node 'OMX.google.vorbis.decoder'
I/OMXCodec(  285): >>>UHQA initOutputFormat 16
I/AwesomePlayer(  285): Could not offload audio decode, try pcm offload
V/AudioPolicyManager(  285): isOffloadSupported: SR=44100, CM=0x1, Format=0x1c000001, StreamType=-1, BitRate=4294967295, duration=2880000 us, has_video=0
V/AudioPolicyManager(  285): isOffloadSupported: stream_type != MUSIC, returning false
I/OMXCodec(  285): [OMX.google.vorbis.decoder] OMXCodec::start mState=1
I/OMXCodec(  285): [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
I/OMXCodec(  285): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
,I/OMXCodec(  285): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
V/AwesomePlayer(  285): finishAsyncPrepare_l
V/AwesomePlayer(  285): notifyListner_l() msg (200-MEDIA_INFO), ext1 (973), ext2 (0)
V/AudioCache(  285): notify(0xb06187e0, 200, 973, 0)
V/AudioCache(  285): ignored
V/AwesomePlayer(  285): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache(  285): notify(0xb06187e0, 5, 0, 0)
V/AudioCache(  285): ignored
V/AwesomePlayer(  285): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache(  285): notify(0xb06187e0, 1, 0, 0)
V/AudioCache(  285): prepared
V/AudioCache(  285): wait - success
V/MediaPlayerService(  285): start
V/StagefrightPlayer(  285): start
V/AwesomePlayer(  285): play
V/AwesomePlayer(  285): AwesomePlayer::play_l():: This is not a DRM content
V/AwesomePlayer(  285): startAudioPlayer_l, sendErrorNotification (0)
D/AudioPlayer(  285): start of Playback, useOffload 0
,I/OMXCodec(  285): [OMX.google.vorbis.decoder] 0onCmdComplete  mState =  7
I/OMXCodec(  285): [OMX.google.vorbis.decoder] PORT_DISABLED(1)
I/OMXCodec(  285): >>>UHQA initOutputFormat 16
,I/OMXCodec(  285): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
,I/AudioPlayer(  285): Audio channels(2)
I/AudioPlayer(  285): Audioplayer kKeyAudioPCMFormat:0, 1, 0
I/AudioPlayer(  285): Audioplayer kKeyAudioPCMFormat read fail(2, 1)
V/AudioCache(  285): open(48000, 2, 0x0, 1, 0)
,V/AwesomePlayer(  285): notifyListner_l() msg (6-MEDIA_STARTED), ext1 (0), ext2 (0)
V/AudioCache(  285): notify(0xb06187e0, 6, 0, 0)
V/AudioCache(  285): ignored
V/AwesomePlayer(  285): addBatteryData
V/MediaPlayerService(  285): wait for playback complete
,I/AudioPlayer(  285): First fillBuffer call!!
I/AudioPlayer(  285): >>> setAudioEffect Read mAudioFormat : 1, event : 4587583, value : 4390976
E/AudioPlayer(  285): >>> setAudioEffect Error mAudioFormat : 1, event : 4587583, value : 4390976
,D/SHealthUpgrade(SHealthUpgradeUtil)( 8121): isShealthServiceInstalled() : HealthService is Installed.
D/SHealthUpgrade(SHealthUpgradeUtil)( 8121): isShealthService2xInstalled() : HEALTH SERVICE is INSTALLED.
D/SHealthUpgrade(SHealthUpgradeUtil)( 8121): isShealthService2xInstalled() : HEALTH SERVICE VERSION = 2.x
,I/PeopleContactsSync( 2447): CP2 sync disabled
,I/OMXCodec(  285): [OMX.google.vorbis.decoder] End Of Stream
,V/AwesomePlayer(  285): postAudioEOS delayUs (0)
,V/AwesomePlayer(  285): onCheckAudioStatus
,V/AwesomePlayer(  285): onCheckAudioStatus() set AUDIO_AT_EOS flag
V/AwesomePlayer(  285): onStreamDone
V/AwesomePlayer(  285): MEDIA_PLAYBACK_COMPLETE
V/AwesomePlayer(  285): notifyListner_l() msg (2-MEDIA_PLAYBACK_COMPLETE), ext1 (0), ext2 (0)
V/AudioCache(  285): notify(0xb06187e0, 2, 0, 0)
V/AudioCache(  285): playback complete - thread will wake up later
V/AwesomePlayer(  285): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
,V/AudioCache(  285): notify(0xb06187e0, 7, 0, 0)
V/AudioCache(  285): ignored
V/AwesomePlayer(  285): cancelPlayerEvents (keepNotifications=1)
V/AwesomePlayer(  285): addBatteryData
V/AudioCache(  285): wait - success
V/StagefrightPlayer(  285): reset
,V/AwesomePlayer(  285): reset_l()
V/AwesomePlayer(  285): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  285): notify(0xb06187e0, 8, 0, 0)
V/AudioCache(  285): ignored
V/AwesomePlayer(  285): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  285): mAudioTrackVector clear
D/AudioPlayer(  285): reset: mPlaying=0 mReachedEOS=1 useOffload=0
I/OMXCodec(  285): [OMX.google.vorbis.decoder] stop mState=4
I/OMXCodec(  285): [OMX.google.vorbis.decoder] stop() sendCommand(0x7f, OMX_CommandStateSet, OMX_StateIdle)
I/OMXCodec(  285): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
,I/OMXCodec(  285): [OMX.google.vorbis.decoder] stopOmxComponent_l() mstate = 1
I/OggExtractor(  285): OggSource::stop() mExtractor ref count = 1
I/OggExtractor(  285): OggSource::~OggSource() mExtractor !mStarted ref count = 1
I/OggExtractor(  285): ~OggSource --
I/OggExtractor(  285): ~OggExtractor ++
I/OggExtractor(  285): ~MyVorbisExtractor ++ 
I/OggExtractor(  285): ~MyVorbisExtractor --
I/OggExtractor(  285): ~OggExtractor --
,I/AudioPlayer(  285): reset out
V/AwesomePlayer(  285): reset_l() mAudioPlayer successfully deleted
I/SecVideoCapture(  285): SecVideoCapture destructor
I/SecVideoCapture(  285): reset
V/AwesomePlayer(  285): mSecCapture clear
I/SecMediaClock(  285): SecMediaClock destructor
V/AwesomePlayer(  285): mSecMediaClock clear
V/StagefrightPlayer(  285): ~StagefrightPlayer
V/StagefrightPlayer(  285): reset
V/AwesomePlayer(  285): reset_l()
V/AwesomePlayer(  285): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  285): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  285): mAudioTrackVector clear
V/AwesomePlayer(  285): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  285): mSecCapture clear
V/AwesomePlayer(  285): mSecMediaClock clear
V/AwesomePlayer(  285): destructor
V/AwesomePlayer(  285): reset_l()
V/AwesomePlayer(  285): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  285): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  285): mAudioTrackVector clear
V/AwesomePlayer(  285): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  285): mSecCapture clear
V/AwesomePlayer(  285): mSecMediaClock clear
V/MediaPlayer( 8121): decode(45, 19172584, 4112)
,V/MediaPlayerService(  285): decode(30, 19172584, 4112)
,V/MediaPlayerService(  285): player type = 3
V/AwesomePlayer(  285): setDefault
V/AwesomePlayer(  285): constructor
V/AwesomePlayer(  285): setDefault
V/AwesomePlayer(  285): reset_l()
V/AwesomePlayer(  285): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
,V/AwesomePlayer(  285): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  285): mAudioTrackVector clear
V/AwesomePlayer(  285): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  285): mSecCapture clear
V/AwesomePlayer(  285): mSecMediaClock clear
V/StagefrightPlayer(  285): StagefrightPlayer
V/AwesomePlayer(  285): setListener
V/StagefrightPlayer(  285): initCheck
,V/AwesomePlayer(  285): setAudioSink
V/StagefrightPlayer(  285): setDataSource(30, 19172584, 4112)
V/AwesomePlayer(  285): reset_l()
V/AwesomePlayer(  285): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  285): notify(0xb0618420, 8, 0, 0)
V/AudioCache(  285): ignored
V/AwesomePlayer(  285): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  285): mAudioTrackVector clear
,V/AwesomePlayer(  285): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  285): mSecCapture clear
V/AwesomePlayer(  285): mSecMediaClock clear
D/Utils   (  285): printFileName fd(31) -> /system/priv-app/SHealth3_5/SHealth3_5.apk
,V/AwesomePlayer(  285): track of type 'audio/vorbis' does not publish bitrate
V/AwesomePlayer(  285): mBitrate = -1 bits/sec
I/OggExtractor(  285): OggSource::OggSource() mExtractor ref count = 4
V/AwesomePlayer(  285): current audio track index (0) is added to vector
V/AwesomePlayer(  285): setDataSource_l: Audio(1), Video(0)
I/AwesomePlayer(  285): checkRightsStatus is not necessary - AwesomePlayer::setDataSource_l
,V/MediaPlayerService(  285): prepare
V/AwesomePlayer(  285): prepareAsync
V/MediaPlayerService(  285): wait for prepare
V/AwesomePlayer(  285): onPrepareAsyncEvent
I/SecMediaClock(  285): SecMediaClock constructor
I/SecMediaClock(  285): reset
I/SecVideoCapture(  285): SecVideoCapture constructor
I/SecVideoCapture(  285): reset
,V/AwesomePlayer(  285): initAudioDecoder
V/AwesomePlayer(  285): checkOffloadExceptions is true
V/AudioPolicyManager(  285): isOffloadSupported: SR=44100, CM=0x1, Format=0x7000000, StreamType=-1, BitRate=4294967295, duration=4331 us, has_video=0
V/AudioPolicyManager(  285): isOffloadSupported: stream_type != MUSIC, returning false
I/OMXCodec(  285): Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
,I/OMXCodec(  285): Successfully allocated OMX node 'OMX.google.vorbis.decoder'
I/OMXCodec(  285): >>>UHQA initOutputFormat 16
I/AwesomePlayer(  285): Could not offload audio decode, try pcm offload
V/AudioPolicyManager(  285): isOffloadSupported: SR=44100, CM=0x1, Format=0x1c000001, StreamType=-1, BitRate=4294967295, duration=4331 us, has_video=0
V/AudioPolicyManager(  285): isOffloadSupported: stream_type != MUSIC, returning false
I/OMXCodec(  285): [OMX.google.vorbis.decoder] OMXCodec::start mState=1
I/OMXCodec(  285): [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
I/OMXCodec(  285): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
,I/OMXCodec(  285): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
V/AwesomePlayer(  285): finishAsyncPrepare_l
V/AwesomePlayer(  285): notifyListner_l() msg (200-MEDIA_INFO), ext1 (973), ext2 (0)
V/AudioCache(  285): notify(0xb0618420, 200, 973, 0)
V/AudioCache(  285): ignored
V/AwesomePlayer(  285): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache(  285): notify(0xb0618420, 5, 0, 0)
V/AudioCache(  285): ignored
V/AwesomePlayer(  285): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
,V/AudioCache(  285): notify(0xb0618420, 1, 0, 0)
V/AudioCache(  285): prepared
V/AudioCache(  285): wait - success
V/MediaPlayerService(  285): start
V/StagefrightPlayer(  285): start
V/AwesomePlayer(  285): play
,V/AwesomePlayer(  285): AwesomePlayer::play_l():: This is not a DRM content
V/AwesomePlayer(  285): startAudioPlayer_l, sendErrorNotification (0)
D/AudioPlayer(  285): start of Playback, useOffload 0
,I/OMXCodec(  285): [OMX.google.vorbis.decoder] End Of Stream
,I/OMXCodec(  285): [OMX.google.vorbis.decoder] 0onCmdComplete  mState =  7
I/OMXCodec(  285): [OMX.google.vorbis.decoder] PORT_DISABLED(1)
I/OMXCodec(  285): >>>UHQA initOutputFormat 16
I/OMXCodec(  285): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
,I/AudioPlayer(  285): Audio channels(1)
I/AudioPlayer(  285): Audioplayer kKeyAudioPCMFormat:0, 1, 0
I/AudioPlayer(  285): Audioplayer kKeyAudioPCMFormat read fail(1, 1)
V/AudioCache(  285): open(44100, 1, 0x0, 1, 0)
,V/AwesomePlayer(  285): notifyListner_l() msg (6-MEDIA_STARTED), ext1 (0), ext2 (0)
V/AudioCache(  285): notify(0xb0618420, 6, 0, 0)
,V/AudioCache(  285): ignored
V/AwesomePlayer(  285): addBatteryData
I/AudioPlayer(  285): First fillBuffer call!!
I/AudioPlayer(  285): >>> setAudioEffect Read mAudioFormat : 1, event : 168430090, value : 151652874
V/MediaPlayerService(  285): wait for playback complete
E/AudioPlayer(  285): >>> setAudioEffect Error mAudioFormat : 1, event : 168430090, value : 151652874
V/AwesomePlayer(  285): postAudioEOS delayUs (0)
,V/AwesomePlayer(  285): onCheckAudioStatus
V/AwesomePlayer(  285): onCheckAudioStatus() set AUDIO_AT_EOS flag
V/AwesomePlayer(  285): onStreamDone
V/AwesomePlayer(  285): MEDIA_PLAYBACK_COMPLETE
V/AwesomePlayer(  285): notifyListner_l() msg (2-MEDIA_PLAYBACK_COMPLETE), ext1 (0), ext2 (0)
V/AudioCache(  285): notify(0xb0618420, 2, 0, 0)
V/AudioCache(  285): playback complete - thread will wake up later
,V/AwesomePlayer(  285): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache(  285): notify(0xb0618420, 7, 0, 0)
V/AudioCache(  285): ignored
V/AwesomePlayer(  285): cancelPlayerEvents (keepNotifications=1)
V/AudioCache(  285): wait - success
V/StagefrightPlayer(  285): reset
V/AwesomePlayer(  285): addBatteryData
V/AwesomePlayer(  285): reset_l()
,V/AwesomePlayer(  285): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  285): notify(0xb0618420, 8, 0, 0)
V/AudioCache(  285): ignored
V/AwesomePlayer(  285): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  285): mAudioTrackVector clear
D/AudioPlayer(  285): reset: mPlaying=0 mReachedEOS=1 useOffload=0
I/OMXCodec(  285): [OMX.google.vorbis.decoder] stop mState=4
I/OMXCodec(  285): [OMX.google.vorbis.decoder] stop() sendCommand(0x80, OMX_CommandStateSet, OMX_StateIdle)
,I/OMXCodec(  285): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
I/OMXCodec(  285): [OMX.google.vorbis.decoder] stopOmxComponent_l() mstate = 1
I/OggExtractor(  285): OggSource::stop() mExtractor ref count = 1
I/OggExtractor(  285): OggSource::~OggSource() mExtractor !mStarted ref count = 1
I/OggExtractor(  285): ~OggSource --
I/OggExtractor(  285): ~OggExtractor ++
I/OggExtractor(  285): ~MyVorbisExtractor ++ 
I/OggExtractor(  285): ~MyVorbisExtractor --
,I/OggExtractor(  285): ~OggExtractor --
I/AudioPlayer(  285): reset out
V/AwesomePlayer(  285): reset_l() mAudioPlayer successfully deleted
I/SecVideoCapture(  285): SecVideoCapture destructor
I/SecVideoCapture(  285): reset
V/AwesomePlayer(  285): mSecCapture clear
,I/SecMediaClock(  285): SecMediaClock destructor
V/AwesomePlayer(  285): mSecMediaClock clear
V/StagefrightPlayer(  285): ~StagefrightPlayer
V/StagefrightPlayer(  285): reset
V/AwesomePlayer(  285): reset_l()
V/AwesomePlayer(  285): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  285): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  285): mAudioTrackVector clear
,V/AwesomePlayer(  285): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  285): mSecCapture clear
V/AwesomePlayer(  285): mSecMediaClock clear
V/AwesomePlayer(  285): destructor
V/AwesomePlayer(  285): reset_l()
V/AwesomePlayer(  285): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  285): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  285): mAudioTrackVector clear
,V/AwesomePlayer(  285): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  285): mSecCapture clear
V/AwesomePlayer(  285): mSecMediaClock clear
V/MediaPlayer( 8121): decode(46, 19235660, 21825)
V/MediaPlayerService(  285): decode(30, 19235660, 21825)
V/MediaPlayerService(  285): player type = 3
V/AwesomePlayer(  285): setDefault
V/AwesomePlayer(  285): constructor
,V/AwesomePlayer(  285): setDefault
V/AwesomePlayer(  285): reset_l()
V/AwesomePlayer(  285): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  285): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  285): mAudioTrackVector clear
V/AwesomePlayer(  285): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  285): mSecCapture clear
V/AwesomePlayer(  285): mSecMediaClock clear
,V/StagefrightPlayer(  285): StagefrightPlayer
V/AwesomePlayer(  285): setListener
V/StagefrightPlayer(  285): initCheck
V/AwesomePlayer(  285): setAudioSink
V/StagefrightPlayer(  285): setDataSource(30, 19235660, 21825)
V/AwesomePlayer(  285): reset_l()
V/AwesomePlayer(  285): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
,V/AudioCache(  285): notify(0xb050f1a0, 8, 0, 0)
V/AudioCache(  285): ignored
V/AwesomePlayer(  285): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  285): mAudioTrackVector clear
V/AwesomePlayer(  285): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  285): mSecCapture clear
V/AwesomePlayer(  285): mSecMediaClock clear
D/Utils   (  285): printFileName fd(31) -> /system/priv-app/SHealth3_5/SHealth3_5.apk
,V/AwesomePlayer(  285): track of type 'audio/vorbis' does not publish bitrate
V/AwesomePlayer(  285): mBitrate = -1 bits/sec
I/OggExtractor(  285): OggSource::OggSource() mExtractor ref count = 4
V/AwesomePlayer(  285): current audio track index (0) is added to vector
,V/AwesomePlayer(  285): setDataSource_l: Audio(1), Video(0)
I/AwesomePlayer(  285): checkRightsStatus is not necessary - AwesomePlayer::setDataSource_l
V/MediaPlayerService(  285): prepare
V/AwesomePlayer(  285): prepareAsync
V/MediaPlayerService(  285): wait for prepare
V/AwesomePlayer(  285): onPrepareAsyncEvent
I/SecMediaClock(  285): SecMediaClock constructor
W/libprocessgroup(  890): failed to open /acct/uid_10054/pid_7178/cgroup.procs: No such file or directory
,I/SecMediaClock(  285): reset
I/SecVideoCapture(  285): SecVideoCapture constructor
I/SecVideoCapture(  285): reset
V/AwesomePlayer(  285): initAudioDecoder
V/AwesomePlayer(  285): checkOffloadExceptions is true
V/AudioPolicyManager(  285): isOffloadSupported: SR=44100, CM=0x3, Format=0x7000000, StreamType=-1, BitRate=4294967295, duration=1250000 us, has_video=0
V/AudioPolicyManager(  285): isOffloadSupported: stream_type != MUSIC, returning false
I/OMXCodec(  285): Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
,I/OMXCodec(  285): Successfully allocated OMX node 'OMX.google.vorbis.decoder'
I/OMXCodec(  285): >>>UHQA initOutputFormat 16
I/AwesomePlayer(  285): Could not offload audio decode, try pcm offload
V/AudioPolicyManager(  285): isOffloadSupported: SR=44100, CM=0x1, Format=0x1c000001, StreamType=-1, BitRate=4294967295, duration=1250000 us, has_video=0
V/AudioPolicyManager(  285): isOffloadSupported: stream_type != MUSIC, returning false
I/OMXCodec(  285): [OMX.google.vorbis.decoder] OMXCodec::start mState=1
,I/OMXCodec(  285): [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
I/OMXCodec(  285): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
I/OMXCodec(  285): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
V/AwesomePlayer(  285): finishAsyncPrepare_l
V/AwesomePlayer(  285): notifyListner_l() msg (200-MEDIA_INFO), ext1 (973), ext2 (0)
V/AudioCache(  285): notify(0xb050f1a0, 200, 973, 0)
V/AudioCache(  285): ignored
,V/AwesomePlayer(  285): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache(  285): notify(0xb050f1a0, 5, 0, 0)
V/AudioCache(  285): ignored
V/AwesomePlayer(  285): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache(  285): notify(0xb050f1a0, 1, 0, 0)
V/AudioCache(  285): prepared
V/AudioCache(  285): wait - success
V/MediaPlayerService(  285): start
,V/StagefrightPlayer(  285): start
V/AwesomePlayer(  285): play
V/AwesomePlayer(  285): AwesomePlayer::play_l():: This is not a DRM content
V/AwesomePlayer(  285): startAudioPlayer_l, sendErrorNotification (0)
D/AudioPlayer(  285): start of Playback, useOffload 0
,I/OMXCodec(  285): [OMX.google.vorbis.decoder] 0onCmdComplete  mState =  7
,I/OMXCodec(  285): [OMX.google.vorbis.decoder] PORT_DISABLED(1)
I/OMXCodec(  285): >>>UHQA initOutputFormat 16
I/OMXCodec(  285): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
I/AudioPlayer(  285): Audio channels(2)
I/AudioPlayer(  285): Audioplayer kKeyAudioPCMFormat:0, 1, 0
I/AudioPlayer(  285): Audioplayer kKeyAudioPCMFormat read fail(2, 1)
V/AudioCache(  285): open(44100, 2, 0x0, 1, 0)
,V/AwesomePlayer(  285): notifyListner_l() msg (6-MEDIA_STARTED), ext1 (0), ext2 (0)
V/AudioCache(  285): notify(0xb050f1a0, 6, 0, 0)
V/AudioCache(  285): ignored
V/AwesomePlayer(  285): addBatteryData
V/MediaPlayerService(  285): wait for playback complete
I/AudioPlayer(  285): First fillBuffer call!!
I/AudioPlayer(  285): >>> setAudioEffect Read mAudioFormat : 1, event : 235670794, value : 319688206
,E/AudioPlayer(  285): >>> setAudioEffect Error mAudioFormat : 1, event : 235670794, value : 319688206
,I/OMXCodec(  285): [OMX.google.vorbis.decoder] End Of Stream
,V/AwesomePlayer(  285): postAudioEOS delayUs (0)
,V/AwesomePlayer(  285): onCheckAudioStatus
V/AwesomePlayer(  285): onCheckAudioStatus() set AUDIO_AT_EOS flag
V/AwesomePlayer(  285): onStreamDone
V/AwesomePlayer(  285): MEDIA_PLAYBACK_COMPLETE
V/AwesomePlayer(  285): notifyListner_l() msg (2-MEDIA_PLAYBACK_COMPLETE), ext1 (0), ext2 (0)
V/AudioCache(  285): notify(0xb050f1a0, 2, 0, 0)
V/AudioCache(  285): playback complete - thread will wake up later
,V/AwesomePlayer(  285): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache(  285): notify(0xb050f1a0, 7, 0, 0)
V/AudioCache(  285): ignored
V/AwesomePlayer(  285): cancelPlayerEvents (keepNotifications=1)
V/AwesomePlayer(  285): addBatteryData
V/AudioCache(  285): wait - success
V/StagefrightPlayer(  285): reset
V/AwesomePlayer(  285): reset_l()
,V/AwesomePlayer(  285): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  285): notify(0xb050f1a0, 8, 0, 0)
V/AudioCache(  285): ignored
V/AwesomePlayer(  285): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  285): mAudioTrackVector clear
D/AudioPlayer(  285): reset: mPlaying=0 mReachedEOS=1 useOffload=0
I/OMXCodec(  285): [OMX.google.vorbis.decoder] stop mState=4
I/OMXCodec(  285): [OMX.google.vorbis.decoder] stop() sendCommand(0x81, OMX_CommandStateSet, OMX_StateIdle)
,I/OMXCodec(  285): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
I/OMXCodec(  285): [OMX.google.vorbis.decoder] stopOmxComponent_l() mstate = 1
I/OggExtractor(  285): OggSource::stop() mExtractor ref count = 1
I/OggExtractor(  285): OggSource::~OggSource() mExtractor !mStarted ref count = 1
I/OggExtractor(  285): ~OggSource --
I/OggExtractor(  285): ~OggExtractor ++
I/OggExtractor(  285): ~MyVorbisExtractor ++ 
I/OggExtractor(  285): ~MyVorbisExtractor --
,I/OggExtractor(  285): ~OggExtractor --
I/AudioPlayer(  285): reset out
V/AwesomePlayer(  285): reset_l() mAudioPlayer successfully deleted
I/SecVideoCapture(  285): SecVideoCapture destructor
I/SecVideoCapture(  285): reset
V/AwesomePlayer(  285): mSecCapture clear
I/SecMediaClock(  285): SecMediaClock destructor
V/AwesomePlayer(  285): mSecMediaClock clear
,V/StagefrightPlayer(  285): ~StagefrightPlayer
V/StagefrightPlayer(  285): reset
V/AwesomePlayer(  285): reset_l()
V/AwesomePlayer(  285): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  285): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  285): mAudioTrackVector clear
V/AwesomePlayer(  285): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  285): mSecCapture clear
,V/AwesomePlayer(  285): mSecMediaClock clear
V/AwesomePlayer(  285): destructor
V/AwesomePlayer(  285): reset_l()
V/AwesomePlayer(  285): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  285): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  285): mAudioTrackVector clear
V/AwesomePlayer(  285): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  285): mSecCapture clear
,V/AwesomePlayer(  285): mSecMediaClock clear
V/MediaPlayer( 8121): decode(47, 19134596, 21552)
V/MediaPlayerService(  285): decode(30, 19134596, 21552)
V/MediaPlayerService(  285): player type = 3
V/AwesomePlayer(  285): setDefault
V/AwesomePlayer(  285): constructor
V/AwesomePlayer(  285): setDefault
V/AwesomePlayer(  285): reset_l()
,V/AwesomePlayer(  285): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  285): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  285): mAudioTrackVector clear
V/AwesomePlayer(  285): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  285): mSecCapture clear
V/AwesomePlayer(  285): mSecMediaClock clear
V/StagefrightPlayer(  285): StagefrightPlayer
V/AwesomePlayer(  285): setListener
,V/StagefrightPlayer(  285): initCheck
V/AwesomePlayer(  285): setAudioSink
V/StagefrightPlayer(  285): setDataSource(30, 19134596, 21552)
V/AwesomePlayer(  285): reset_l()
V/AwesomePlayer(  285): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  285): notify(0xb050f0b0, 8, 0, 0)
V/AudioCache(  285): ignored
V/AwesomePlayer(  285): cancelPlayerEvents (keepNotifications=0)
,V/AwesomePlayer(  285): mAudioTrackVector clear
V/AwesomePlayer(  285): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  285): mSecCapture clear
V/AwesomePlayer(  285): mSecMediaClock clear
D/Utils   (  285): printFileName fd(31) -> /system/priv-app/SHealth3_5/SHealth3_5.apk
V/AwesomePlayer(  285): track of type 'audio/vorbis' does not publish bitrate
V/AwesomePlayer(  285): mBitrate = -1 bits/sec
I/OggExtractor(  285): OggSource::OggSource() mExtractor ref count = 4
,V/AwesomePlayer(  285): current audio track index (0) is added to vector
V/AwesomePlayer(  285): setDataSource_l: Audio(1), Video(0)
I/AwesomePlayer(  285): checkRightsStatus is not necessary - AwesomePlayer::setDataSource_l
V/MediaPlayerService(  285): prepare
V/AwesomePlayer(  285): prepareAsync
V/MediaPlayerService(  285): wait for prepare
V/AwesomePlayer(  285): onPrepareAsyncEvent
I/SecMediaClock(  285): SecMediaClock constructor
,I/SecMediaClock(  285): reset
I/SecVideoCapture(  285): SecVideoCapture constructor
I/SecVideoCapture(  285): reset
V/AwesomePlayer(  285): initAudioDecoder
V/AwesomePlayer(  285): checkOffloadExceptions is true
V/AudioPolicyManager(  285): isOffloadSupported: SR=44100, CM=0x3, Format=0x7000000, StreamType=-1, BitRate=4294967295, duration=1250000 us, has_video=0
V/AudioPolicyManager(  285): isOffloadSupported: stream_type != MUSIC, returning false
I/OMXCodec(  285): Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
,I/OMXCodec(  285): Successfully allocated OMX node 'OMX.google.vorbis.decoder'
I/OMXCodec(  285): >>>UHQA initOutputFormat 16
I/AwesomePlayer(  285): Could not offload audio decode, try pcm offload
V/AudioPolicyManager(  285): isOffloadSupported: SR=44100, CM=0x1, Format=0x1c000001, StreamType=-1, BitRate=4294967295, duration=1250000 us, has_video=0
,V/AudioPolicyManager(  285): isOffloadSupported: stream_type != MUSIC, returning false
I/OMXCodec(  285): [OMX.google.vorbis.decoder] OMXCodec::start mState=1
I/OMXCodec(  285): [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
I/OMXCodec(  285): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
I/OMXCodec(  285): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
,V/AwesomePlayer(  285): finishAsyncPrepare_l
V/AwesomePlayer(  285): notifyListner_l() msg (200-MEDIA_INFO), ext1 (973), ext2 (0)
V/AudioCache(  285): notify(0xb050f0b0, 200, 973, 0)
V/AudioCache(  285): ignored
V/AwesomePlayer(  285): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache(  285): notify(0xb050f0b0, 5, 0, 0)
V/AudioCache(  285): ignored
,V/AwesomePlayer(  285): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache(  285): notify(0xb050f0b0, 1, 0, 0)
V/AudioCache(  285): prepared
V/AudioCache(  285): wait - success
V/MediaPlayerService(  285): start
V/StagefrightPlayer(  285): start
V/AwesomePlayer(  285): play
V/AwesomePlayer(  285): AwesomePlayer::play_l():: This is not a DRM content
,V/AwesomePlayer(  285): startAudioPlayer_l, sendErrorNotification (0)
D/AudioPlayer(  285): start of Playback, useOffload 0
,I/OMXCodec(  285): [OMX.google.vorbis.decoder] 0onCmdComplete  mState =  7
,I/OMXCodec(  285): [OMX.google.vorbis.decoder] PORT_DISABLED(1)
I/OMXCodec(  285): >>>UHQA initOutputFormat 16
I/OMXCodec(  285): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
I/AudioPlayer(  285): Audio channels(2)
I/AudioPlayer(  285): Audioplayer kKeyAudioPCMFormat:0, 1, 0
I/AudioPlayer(  285): Audioplayer kKeyAudioPCMFormat read fail(2, 1)
V/AudioCache(  285): open(44100, 2, 0x0, 1, 0),
V/AwesomePlayer(  285): notifyListner_l() msg (6-MEDIA_STARTED), ext1 (0), ext2 (0)
V/AudioCache(  285): notify(0xb050f0b0, 6, 0, 0)
V/AudioCache(  285): ignored
V/AwesomePlayer(  285): addBatteryData
V/MediaPlayerService(  285): wait for playback complete
,I/AudioPlayer(  285): First fillBuffer call!!
,I/OMXCodec(  285): [OMX.google.vorbis.decoder] End Of Stream
,V/AwesomePlayer(  285): postAudioEOS delayUs (0)
,V/AwesomePlayer(  285): onCheckAudioStatus
V/AwesomePlayer(  285): onCheckAudioStatus() set AUDIO_AT_EOS flag
V/AwesomePlayer(  285): onStreamDone
V/AwesomePlayer(  285): MEDIA_PLAYBACK_COMPLETE
V/AwesomePlayer(  285): notifyListner_l() msg (2-MEDIA_PLAYBACK_COMPLETE), ext1 (0), ext2 (0)
V/AudioCache(  285): notify(0xb050f0b0, 2, 0, 0)
V/AudioCache(  285): playback complete - thread will wake up later
,V/AwesomePlayer(  285): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache(  285): notify(0xb050f0b0, 7, 0, 0)
V/AudioCache(  285): ignored
V/AwesomePlayer(  285): cancelPlayerEvents (keepNotifications=1)
V/AudioCache(  285): wait - success
V/StagefrightPlayer(  285): reset
V/AwesomePlayer(  285): addBatteryData
V/AwesomePlayer(  285): reset_l()
,V/AwesomePlayer(  285): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  285): notify(0xb050f0b0, 8, 0, 0)
V/AudioCache(  285): ignored
V/AwesomePlayer(  285): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  285): mAudioTrackVector clear
D/AudioPlayer(  285): reset: mPlaying=0 mReachedEOS=1 useOffload=0
I/OMXCodec(  285): [OMX.google.vorbis.decoder] stop mState=4
I/OMXCodec(  285): [OMX.google.vorbis.decoder] stop() sendCommand(0x82, OMX_CommandStateSet, OMX_StateIdle)
,I/OMXCodec(  285): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
I/OMXCodec(  285): [OMX.google.vorbis.decoder] stopOmxComponent_l() mstate = 1
I/OggExtractor(  285): OggSource::stop() mExtractor ref count = 1
I/OggExtractor(  285): OggSource::~OggSource() mExtractor !mStarted ref count = 1
I/OggExtractor(  285): ~OggSource --
I/OggExtractor(  285): ~OggExtractor ++
I/OggExtractor(  285): ~MyVorbisExtractor ++ 
I/OggExtractor(  285): ~MyVorbisExtractor --
,I/OggExtractor(  285): ~OggExtractor --
I/AudioPlayer(  285): reset out
V/AwesomePlayer(  285): reset_l() mAudioPlayer successfully deleted
I/SecVideoCapture(  285): SecVideoCapture destructor
I/SecVideoCapture(  285): reset
V/AwesomePlayer(  285): mSecCapture clear
I/SecMediaClock(  285): SecMediaClock destructor
V/AwesomePlayer(  285): mSecMediaClock clear
,V/StagefrightPlayer(  285): ~StagefrightPlayer
V/StagefrightPlayer(  285): reset
V/AwesomePlayer(  285): reset_l()
V/AwesomePlayer(  285): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  285): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  285): mAudioTrackVector clear
V/AwesomePlayer(  285): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  285): mSecCapture clear
,V/AwesomePlayer(  285): mSecMediaClock clear
V/AwesomePlayer(  285): destructor
V/AwesomePlayer(  285): reset_l()
V/AwesomePlayer(  285): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  285): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  285): mAudioTrackVector clear
V/AwesomePlayer(  285): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  285): mSecCapture clear
,V/AwesomePlayer(  285): mSecMediaClock clear
V/MediaPlayer( 8121): decode(48, 19228560, 7017)
V/MediaPlayerService(  285): decode(30, 19228560, 7017)
V/MediaPlayerService(  285): player type = 3
V/AwesomePlayer(  285): setDefault
V/AwesomePlayer(  285): constructor
V/AwesomePlayer(  285): setDefault
V/AwesomePlayer(  285): reset_l()
,V/AwesomePlayer(  285): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  285): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  285): mAudioTrackVector clear
V/AwesomePlayer(  285): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  285): mSecCapture clear
V/AwesomePlayer(  285): mSecMediaClock clear
V/StagefrightPlayer(  285): StagefrightPlayer
V/AwesomePlayer(  285): setListener
,V/StagefrightPlayer(  285): initCheck
V/AwesomePlayer(  285): setAudioSink
V/StagefrightPlayer(  285): setDataSource(30, 19228560, 7017)
V/AwesomePlayer(  285): reset_l()
V/AwesomePlayer(  285): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  285): notify(0xb092b1f0, 8, 0, 0)
V/AudioCache(  285): ignored
V/AwesomePlayer(  285): cancelPlayerEvents (keepNotifications=0)
,V/AwesomePlayer(  285): mAudioTrackVector clear
V/AwesomePlayer(  285): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  285): mSecCapture clear
V/AwesomePlayer(  285): mSecMediaClock clear
D/Utils   (  285): printFileName fd(31) -> /system/priv-app/SHealth3_5/SHealth3_5.apk
V/AwesomePlayer(  285): track of type 'audio/vorbis' does not publish bitrate
V/AwesomePlayer(  285): mBitrate = -1 bits/sec
I/OggExtractor(  285): OggSource::OggSource() mExtractor ref count = 4
,V/AwesomePlayer(  285): current audio track index (0) is added to vector
V/AwesomePlayer(  285): setDataSource_l: Audio(1), Video(0)
I/AwesomePlayer(  285): checkRightsStatus is not necessary - AwesomePlayer::setDataSource_l
V/MediaPlayerService(  285): prepare
V/AwesomePlayer(  285): prepareAsync
V/MediaPlayerService(  285): wait for prepare
V/AwesomePlayer(  285): onPrepareAsyncEvent
I/SecMediaClock(  285): SecMediaClock constructor
I/SecMediaClock(  285): reset
I/SecVideoCapture(  285): SecVideoCapture constructor
I/SecVideoCapture(  285): reset
V/AwesomePlayer(  285): initAudioDecoder
V/AwesomePlayer(  285): checkOffloadExceptions is true
V/AudioPolicyManager(  285): isOffloadSupported: SR=44100, CM=0x3, Format=0x7000000, StreamType=-1, BitRate=4294967295, duration=173945 us, has_video=0
V/AudioPolicyManager(  285): isOffloadSupported: stream_type != MUSIC, returning false
,I/OMXCodec(  285): Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
I/OMXCodec(  285): Successfully allocated OMX node 'OMX.google.vorbis.decoder'
I/OMXCodec(  285): >>>UHQA initOutputFormat 16
I/AwesomePlayer(  285): Could not offload audio decode, try pcm offload
V/AudioPolicyManager(  285): isOffloadSupported: SR=44100, CM=0x1, Format=0x1c000001, StreamType=-1, BitRate=4294967295, duration=173945 us, has_video=0
V/AudioPolicyManager(  285): isOffloadSupported: stream_type != MUSIC, returning false
I/OMXCodec(  285): [OMX.google.vorbis.decoder] OMXCodec::start mState=1
I/OMXCodec(  285): [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
,I/OMXCodec(  285): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
I/OMXCodec(  285): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
V/AwesomePlayer(  285): finishAsyncPrepare_l
V/AwesomePlayer(  285): notifyListner_l() msg (200-MEDIA_INFO), ext1 (973), ext2 (0)
V/AudioCache(  285): notify(0xb092b1f0, 200, 973, 0)
V/AudioCache(  285): ignored
V/AwesomePlayer(  285): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache(  285): notify(0xb092b1f0, 5, 0, 0)
V/AudioCache(  285): ignored
,V/AwesomePlayer(  285): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache(  285): notify(0xb092b1f0, 1, 0, 0)
V/AudioCache(  285): prepared
V/AudioCache(  285): wait - success
V/MediaPlayerService(  285): start
V/StagefrightPlayer(  285): start
V/AwesomePlayer(  285): play
V/AwesomePlayer(  285): AwesomePlayer::play_l():: This is not a DRM content
,V/AwesomePlayer(  285): startAudioPlayer_l, sendErrorNotification (0)
D/AudioPlayer(  285): start of Playback, useOffload 0
,I/OMXCodec(  285): [OMX.google.vorbis.decoder] 0onCmdComplete  mState =  7
,I/OMXCodec(  285): [OMX.google.vorbis.decoder] PORT_DISABLED(1)
I/OMXCodec(  285): >>>UHQA initOutputFormat 16
I/OMXCodec(  285): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
,I/AudioPlayer(  285): Audio channels(2)
I/AudioPlayer(  285): Audioplayer kKeyAudioPCMFormat:0, 1, 0
I/AudioPlayer(  285): Audioplayer kKeyAudioPCMFormat read fail(2, 1)
V/AudioCache(  285): open(44100, 2, 0x0, 1, 0)
V/AwesomePlayer(  285): notifyListner_l() msg (6-MEDIA_STARTED), ext1 (0), ext2 (0)
,V/AudioCache(  285): notify(0xb092b1f0, 6, 0, 0)
V/AudioCache(  285): ignored
V/AwesomePlayer(  285): addBatteryData
V/MediaPlayerService(  285): wait for playback complete
I/AudioPlayer(  285): First fillBuffer call!!
I/AudioPlayer(  285): >>> setAudioEffect Read mAudioFormat : 1, event : 235670794, value : 319688206
E/AudioPlayer(  285): >>> setAudioEffect Error mAudioFormat : 1, event : 235670794, value : 319688206
,I/OMXCodec(  285): [OMX.google.vorbis.decoder] End Of Stream
,V/AwesomePlayer(  285): postAudioEOS delayUs (0)
,V/AwesomePlayer(  285): onCheckAudioStatus
V/AwesomePlayer(  285): onCheckAudioStatus() set AUDIO_AT_EOS flag
V/AwesomePlayer(  285): onStreamDone
V/AwesomePlayer(  285): MEDIA_PLAYBACK_COMPLETE
V/AwesomePlayer(  285): notifyListner_l() msg (2-MEDIA_PLAYBACK_COMPLETE), ext1 (0), ext2 (0)
V/AudioCache(  285): notify(0xb092b1f0, 2, 0, 0)
V/AudioCache(  285): playback complete - thread will wake up later
V/AwesomePlayer(  285): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache(  285): notify(0xb092b1f0, 7, 0, 0)
V/AudioCache(  285): ignored
V/AwesomePlayer(  285): cancelPlayerEvents (keepNotifications=1)
V/AudioCache(  285): wait - success
V/StagefrightPlayer(  285): reset
V/AwesomePlayer(  285): addBatteryData
V/AwesomePlayer(  285): reset_l()
V/AwesomePlayer(  285): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  285): notify(0xb092b1f0, 8, 0, 0)
V/AudioCache(  285): ignored
V/AwesomePlayer(  285): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  285): mAudioTrackVector clear
D/AudioPlayer(  285): reset: mPlaying=0 mReachedEOS=1 useOffload=0
I/OMXCodec(  285): [OMX.google.vorbis.decoder] stop mState=4
I/OMXCodec(  285): [OMX.google.vorbis.decoder] stop() sendCommand(0x83, OMX_CommandStateSet, OMX_StateIdle)
,I/OMXCodec(  285): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
I/OMXCodec(  285): [OMX.google.vorbis.decoder] stopOmxComponent_l() mstate = 1
I/OggExtractor(  285): OggSource::stop() mExtractor ref count = 1
I/OggExtractor(  285): OggSource::~OggSource() mExtractor !mStarted ref count = 1
,I/OggExtractor(  285): ~OggSource --
I/OggExtractor(  285): ~OggExtractor ++
I/OggExtractor(  285): ~MyVorbisExtractor ++ 
I/OggExtractor(  285): ~MyVorbisExtractor --
I/OggExtractor(  285): ~OggExtractor --
,I/AudioPlayer(  285): reset out
V/AwesomePlayer(  285): reset_l() mAudioPlayer successfully deleted
I/SecVideoCapture(  285): SecVideoCapture destructor
I/SecVideoCapture(  285): reset
V/AwesomePlayer(  285): mSecCapture clear
,I/SecMediaClock(  285): SecMediaClock destructor
V/AwesomePlayer(  285): mSecMediaClock clear
V/StagefrightPlayer(  285): ~StagefrightPlayer
V/StagefrightPlayer(  285): reset
V/AwesomePlayer(  285): reset_l()
V/AwesomePlayer(  285): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  285): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  285): mAudioTrackVector clear
,V/AwesomePlayer(  285): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  285): mSecCapture clear
V/AwesomePlayer(  285): mSecMediaClock clear
V/AwesomePlayer(  285): destructor
V/AwesomePlayer(  285): reset_l()
V/AwesomePlayer(  285): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  285): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  285): mAudioTrackVector clear
,V/AwesomePlayer(  285): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  285): mSecCapture clear
V/AwesomePlayer(  285): mSecMediaClock clear
,I/SecureStorage(  351): [INFO]: SPID(0x00000005)Secure Storage Daemon finished processing with result: 0
,I/SecureStorage(  351): [INFO]: SPID(0x00000005)PID: 8142, TID: 8154
,E/SMD     (  277): DCD ON
,I/SecureStorage( 8142): [INFO]: SPID(0x00000000)Processing data has been completed
,I/SecureStorage( 8142): [INFO]: SPID(0x00000000)WARNING! Failed to find SecureStorageExceptionJNI!..
,I/SecSQLiteOpenHelper( 8121): getWritableDatabase(pwd)
,I/SecSQLiteOpenHelper( 8121): getDatabaseLocked(b,b,pwd)...
I/SecSQLiteOpenHelper( 8121): Open platform.db in secure mode
,D/SecSQLiteDatabase( 8121): Android Version: 5.0
,D/SecSQLiteDatabase( 8121): Load library secsqlite.so for Android 5.0
,I/SecSQLiteDatabase( 8121): openSecureDatabase...
,I/SecSQLiteDatabase( 8121): private openSecureDatabase...
,I/SecSQLiteConnectionPool( 8121): OpenSecure
I/SecSQLiteConnectionPool( 8121): OpenSecure with password
,I/SecSQLiteConnectionPool( 8121): openSecureConnectionLocked
,I/SecSQLiteDatabase( 8121): ...private openSecureDatabase
I/SecSQLiteDatabase( 8121): ...openSecureDatabase
,I/SecSQLiteOpenHelper( 8121): ...getDatabaseLocked(b,b,pwd)
,D/SecSQLiteOpenHelper( 8121): ...getDatabaseLocked(b,b,pwd)
,D/SHealthUpgrade(SHealthUpgradeUtil)( 8121): isShealthServiceInstalled() : HealthService is Installed.
,D/SHealthUpgrade(SHealthUpgradeUtil)( 8121): isShealthService2xInstalled() : HEALTH SERVICE is INSTALLED.
D/SHealthUpgrade(SHealthUpgradeUtil)( 8121): isShealthService2xInstalled() : HEALTH SERVICE VERSION = 2.x
,W/System.err( 8121): java.lang.NumberFormatException: Invalid int: "null"
,W/System.err( 8121): 	at java.lang.Integer.invalidInt(Integer.java:138)
,W/System.err( 8121): 	at java.lang.Integer.parseInt(Integer.java:358)
W/System.err( 8121): 	at java.lang.Integer.parseInt(Integer.java:334)
W/System.err( 8121): 	at com.sec.android.app.shealth.common.utils.logging.service.LogManager.setProfileItems(LogManager.java:449)
W/System.err( 8121): 	at com.sec.android.app.shealth.common.utils.logging.service.LogManager$LogHandler.handleMessage(LogManager.java:1173)
W/System.err( 8121): 	at android.os.Handler.dispatchMessage(Handler.java:102)
,W/System.err( 8121): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 8121): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,D/StatusBar.NetworkController( 1169): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02012b/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020464/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
D/StatusBar.NetworkController( 1169): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1169): applyOpen
,D/StatusBar.NetworkController( 1169): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1169): applyOpen
,D/StatusBar.NetworkController( 1169): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1169): applyOpen
,D/StatusBar.NetworkController( 1169): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1169): applyOpen
,I/WifiStateMachine(  890): CMD_RSSI_POLL : calculateWifiScore in!
,I/WifiStateMachine(  890): CMD_RSSI_POLL : calculateWifiScore out!
I/WifiStateMachine(  890): CMD_RSSI_POLL : out!
,D/StatusBar.NetworkController( 1169): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02012b/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020466/com.android.systemui:drawable/stat_sys_signal_inout mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
D/StatusBar.NetworkController( 1169): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1169): applyOpen
,D/StatusBar.NetworkController( 1169): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1169): applyOpen
,D/StatusBar.NetworkController( 1169): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1169): applyOpen
,D/StatusBar.NetworkController( 1169): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1169): applyOpen
,I/dhcpcd  ( 7748): wlan0: sending IPv6 Router Solicitation
,I/dhcpcd  ( 7748): wlan0: no IPv6 Routers available
,D/PreloadUpdateManagerStateMachine( 7089): execute::IDLE:EXECUTE
,D/PreloadUpdateManagerStateMachine( 7089): exit::IDLE
,D/PreloadUpdateManagerStateMachine( 7089): entry::CHECK_TIMEOUT_FOR_UPDATE
,D/hcjo    ( 7089): AutoUpdateTriggerManager:IDLE:setInterval:86400000
,I/art     (  890): Explicit concurrent mark sweep GC freed 62570(3MB) AllocSpace objects, 7(307KB) LOS objects, 30% free, 36MB/52MB, paused 1.778ms total 140.499ms
,D/hcjo    ( 7089): AutoUpdateTriggerManager:IDLE:notifyNextTime
D/PreloadUpdateManagerStateMachine( 7089): execute::CHECK_TIMEOUT_FOR_UPDATE:NO_TIMED_OUT
,D/PreloadUpdateManagerStateMachine( 7089): exit::CHECK_TIMEOUT_FOR_UPDATE
D/PreloadUpdateManagerStateMachine( 7089): entry::IDLE
,W/ContextImpl(  890): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/PreloadUpdateManagerStateMachine( 7089): execute::IDLE:EXECUTE
D/PreloadUpdateManagerStateMachine( 7089): exit::IDLE
D/PreloadUpdateManagerStateMachine( 7089): entry::CHECK_TIMEOUT_FOR_UPDATE
D/hcjo    ( 7089): AutoUpdateTriggerManager:IDLE:notifyNextTime
,D/PreloadUpdateManagerStateMachine( 7089): execute::CHECK_TIMEOUT_FOR_UPDATE:NO_TIMED_OUT
,D/PreloadUpdateManagerStateMachine( 7089): exit::CHECK_TIMEOUT_FOR_UPDATE
D/PreloadUpdateManagerStateMachine( 7089): entry::IDLE
,E/SMD     (  277): DCD ON
,I/ServiceManager(  326): Waiting for service AtCmdFwd...
,D/StatusBar.NetworkController( 1169): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02012b/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020464/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
,D/StatusBar.NetworkController( 1169): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1169): applyOpen
,D/StatusBar.NetworkController( 1169): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1169): applyOpen
D/StatusBar.NetworkController( 1169): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1169): applyOpen
D/StatusBar.NetworkController( 1169): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1169): applyOpen
,I/ServiceManager(  326): Waiting for service AtCmdFwd...
,I/GAV3    ( 8121): Thread[GAThread,5,main]: No campaign data found.
,I/WifiStateMachine(  890): CMD_RSSI_POLL : calculateWifiScore in!
,I/WifiStateMachine(  890): CMD_RSSI_POLL : calculateWifiScore out!
,I/WifiStateMachine(  890): CMD_RSSI_POLL : out!
,D/StatusBar.NetworkController( 1169): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02012b/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020468/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
,D/StatusBar.NetworkController( 1169): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1169): applyOpen
,D/StatusBar.NetworkController( 1169): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1169): applyOpen
D/StatusBar.NetworkController( 1169): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1169): applyOpen
D/StatusBar.NetworkController( 1169): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1169): applyOpen
,I/ServiceManager(  326): Waiting for service AtCmdFwd...
,E/SMD     (  277): DCD ON
,I/ServiceManager(  326): Waiting for service AtCmdFwd...
,D/StatusBar.NetworkController( 1169): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02012b/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020466/com.android.systemui:drawable/stat_sys_signal_inout mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
,D/StatusBar.NetworkController( 1169): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1169): applyOpen
,D/StatusBar.NetworkController( 1169): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1169): applyOpen
D/StatusBar.NetworkController( 1169): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1169): applyOpen
D/StatusBar.NetworkController( 1169): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1169): applyOpen
,I/ServiceManager(  326): Waiting for service AtCmdFwd...
,D/FactoryTest( 6669): Not factory mode
D/FactoryTest( 6669): Not factory mode. isFactoryMode() returend false
,D/MTPRx   ( 6669): DRIVER_TIME_OUT 60s lapsed
D/MTPRx   ( 6669): still no open session command from host, so toast
,W/ContextImpl( 6669): Calling a method in the system process without a qualified user: android.app.ContextImpl.startActivity:1526 android.content.ContextWrapper.startActivity:337 android.content.ContextWrapper.startActivity:337 com.samsung.android.MtpApplication.MtpReceiver$3.handleMessage:713 android.os.Handler.dispatchMessage:102 
,W/ContextImpl( 6669): Calling a method in the system process without a qualified user: android.app.ContextImpl.startActivity:1538 android.app.ContextImpl.startActivity:1527 android.content.ContextWrapper.startActivity:337 android.content.ContextWrapper.startActivity:337 com.samsung.android.MtpApplication.MtpReceiver$3.handleMessage:713 
I/Timeline( 6669): Timeline: Activity_launch_request id:com.android.settings time:117047
,E/PersonaManagerService(  890): inState():  stateMachine is null !!
,V/ApplicationPolicy(  890): isApplicationStateBlocked userId 0 pkgname com.android.settings
,I/ActivityManager(  890): START u0 {flg=0x10000000 cmp=com.android.settings/.SettingsReceiverActivity} from uid 1000 on display 0
,D/CustomFrequencyManagerService(  890): acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1958400  uid : 1000  pid : 890  pkgName : ACTIVITY_RESUME_BOOSTER@6
,W/ActivityManager(  890): mDVFSHelper.acquire()
,D/SSRM:m  (  890): SIOP:: AP = 380, PST = 415, CUR = 300
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1169): value : false
E/MTPRx   ( 6669): started activity for popup
,I/SQLiteSecureOpenHelper( 3581): getWritableDatabase(pwd)
I/SQLiteSecureOpenHelper( 3581): getDatabaseLocked(b,b,pwd)...
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1169): value : false
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
,D/ConnectivityService(  890): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
,D/ResourcesManager( 6669): creating new AssetManager and set to /system/priv-app/SecSettings/SecSettings.apk
,W/ResourcesManager( 6669): Asset path '/system/framework/sec_platform_library.jar' does not exist or contains no resources.
,W/ResourcesManager( 6669): Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
W/ResourcesManager( 6669): Asset path '/system/framework/secvisualeffect.jar' does not exist or contains no resources.
W/ResourcesManager( 6669): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 6669): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 6669): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,W/ResourcesManager( 6669): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,E/SettingsReceiverActivity( 6669): PREF_DONT_ASK_AGAIN : true
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1169): value : false
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
,D/InputMethodManagerService(  890): windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,E/ActivityManager(  890): Invalid thumbnail dimensions: 576x576
,W/InputMethodManagerService(  890): Window already focused, ignoring focus gain of: com.android.internal.view.IInputMethodClient$Stub$Proxy@fa882a2 attribute=null, token = android.os.BinderProxy@27b86d97
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
,I/SQLiteSecureOpenHelper( 3581): getWritableDatabase(pwd)
I/SQLiteSecureOpenHelper( 3581): getDatabaseLocked(b,b,pwd)...
,I/WifiStateMachine(  890): CMD_RSSI_POLL : calculateWifiScore in!
,V/BitmapFactory( 6669): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_015.png
I/WifiStateMachine(  890): CMD_RSSI_POLL : calculateWifiScore out!
I/WifiStateMachine(  890): CMD_RSSI_POLL : out!
,V/BitmapFactory( 6669): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_000.png
,V/BitmapFactory( 6669): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_015.png
,V/BitmapFactory( 6669): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_000.png
,V/BitmapFactory( 6669): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_000.png
,V/BitmapFactory( 6669): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_001.png
,V/BitmapFactory( 6669): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_002.png
,V/BitmapFactory( 6669): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_003.png
,V/BitmapFactory( 6669): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_004.png
,V/BitmapFactory( 6669): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_005.png
V/BitmapFactory( 6669): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_006.png
,V/BitmapFactory( 6669): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_007.png
,V/BitmapFactory( 6669): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_008.png
,V/BitmapFactory( 6669): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_010.png
,V/BitmapFactory( 6669): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_011.png
,V/BitmapFactory( 6669): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_012.png
,V/BitmapFactory( 6669): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_013.png
,V/BitmapFactory( 6669): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_014.png
,V/BitmapFactory( 6669): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_015.png
,V/BitmapFactory( 6669): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_000.png
,V/BitmapFactory( 6669): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_001.png
,V/BitmapFactory( 6669): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_002.png
,V/BitmapFactory( 6669): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_003.png
,V/BitmapFactory( 6669): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_004.png
,V/BitmapFactory( 6669): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_005.png
,V/BitmapFactory( 6669): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_006.png
V/BitmapFactory( 6669): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_007.png
,V/BitmapFactory( 6669): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_008.png
,V/BitmapFactory( 6669): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_010.png
,V/BitmapFactory( 6669): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_011.png
,V/BitmapFactory( 6669): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_012.png
,V/BitmapFactory( 6669): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_013.png
,V/BitmapFactory( 6669): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_014.png
,V/BitmapFactory( 6669): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_015.png
,D/SettingsReceiverActivity( 6669): dev.kiessupport is : TRUE
,D/Activity( 6669): performCreate Call secproduct feature valuefalse
D/Activity( 6669): performCreate Call debug elastic valuetrue
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1169): value : false
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1169): value : false
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
,D/ActivityManager(  890): post active user change for 0
,D/KnoxTimeoutHandler(  890): postActiveUserChange for user 0
D/KnoxTimeoutHandler(  890): handleActiveUserChange for user 0
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1169): value : false
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
,I/Timeline( 7474): Timeline: Activity_idle id: android.os.BinderProxy@7d50a7b time:117324
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
,D/StatusBar.NetworkController( 1169): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02012b/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020464/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
D/StatusBar.NetworkController( 1169): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1169): applyOpen
,D/StatusBar.NetworkController( 1169): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1169): applyOpen
D/StatusBar.NetworkController( 1169): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1169): applyOpen
D/StatusBar.NetworkController( 1169): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1169): applyOpen
,D/ConnectivityService(  890): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,V/AlarmManager(  890): waitForAlarm result :4
,D/BatteryService(  890): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 286, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  890): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
D/BatteryService(  890): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  890):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
I/MotionRecognitionService(  890): Plugged
I/MotionRecognitionService(  890): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1169): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1169): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1169):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3256): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3256): Disconnected process message: 10
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,W/Atfwd_Sendcmd(  326): AtCmdFwd service not published, waiting... retryCnt : 1
,V/GLSActivity( 1670): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1670): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
,I/GLSUser ( 1670): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1670): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1670): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1670): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/Finsky  ( 6565): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,D/Finsky  ( 6565): [1] 5.onFinished: Installation state replication failed.
D/Finsky  ( 6565): [1] 5.onFinished: Scheduling replication attempt 3.
,D/StatusBar.NetworkController( 1169): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02012b/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020468/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
D/StatusBar.NetworkController( 1169): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1169): applyOpen
,D/StatusBar.NetworkController( 1169): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1169): applyOpen
D/StatusBar.NetworkController( 1169): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1169): applyOpen
D/StatusBar.NetworkController( 1169): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1169): applyOpen
,E/SMD     (  277): DCD ON
,D/StatusBar.NetworkController( 1169): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02012b/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020464/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
D/StatusBar.NetworkController( 1169): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1169): applyOpen
,D/StatusBar.NetworkController( 1169): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1169): applyOpen
D/StatusBar.NetworkController( 1169): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1169): applyOpen
D/StatusBar.NetworkController( 1169): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1169): applyOpen
,D/CustomFrequencyManagerService(  890): releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1958400  uid : 1000  pid : 890  tag : ACTIVITY_RESUME_BOOSTER@6
,W/ActivityManager(  890): mDVFSHelper.release()
,D/CustomFrequencyManagerService(  890): acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1958400  uid : 1000  pid : 890  pkgName : ACTIVITY_RESUME_BOOSTER@10
,I/WifiStateMachine(  890): CMD_RSSI_POLL : calculateWifiScore in!
,I/WifiStateMachine(  890): CMD_RSSI_POLL : calculateWifiScore out!
I/WifiStateMachine(  890): CMD_RSSI_POLL : out!
,D/CustomFrequencyManagerService(  890): releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1958400  uid : 1000  pid : 890  tag : ACTIVITY_RESUME_BOOSTER@10
,D/StatusBar.NetworkController( 1169): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02012b/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020468/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
D/StatusBar.NetworkController( 1169): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1169): applyOpen
,D/StatusBar.NetworkController( 1169): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1169): applyOpen
D/StatusBar.NetworkController( 1169): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1169): applyOpen
D/StatusBar.NetworkController( 1169): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1169): applyOpen
,D/StatusBar.NetworkController( 1169): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02012b/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020466/com.android.systemui:drawable/stat_sys_signal_inout mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
,D/StatusBar.NetworkController( 1169): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1169): applyOpen,
,D/StatusBar.NetworkController( 1169): refreshSignalCluster - setNWBoosterIndicators(false),
,D/StatusBar.NetworkController( 1169): applyOpen
D/StatusBar.NetworkController( 1169): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1169): applyOpen
D/StatusBar.NetworkController( 1169): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1169): applyOpen
,V/AlarmManager(  890): waitForAlarm result :4
,D/ConnectivityService(  890): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/SMD     (  277): DCD ON
,D/StatusBar.NetworkController( 1169): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02012b/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020464/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
,D/StatusBar.NetworkController( 1169): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1169): applyOpen
,D/StatusBar.NetworkController( 1169): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1169): applyOpen
D/StatusBar.NetworkController( 1169): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1169): applyOpen
,D/StatusBar.NetworkController( 1169): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1169): applyOpen
,I/ServiceManager(  326): Waiting for service AtCmdFwd...
,I/WifiStateMachine(  890): CMD_RSSI_POLL : calculateWifiScore in!
,I/WifiStateMachine(  890): CMD_RSSI_POLL : calculateWifiScore out!
I/WifiStateMachine(  890): CMD_RSSI_POLL : out!
,I/ServiceManager(  326): Waiting for service AtCmdFwd...
,E/SMD     (  277): DCD ON
,I/ServiceManager(  326): Waiting for service AtCmdFwd...
,I/ServiceManager(  326): Waiting for service AtCmdFwd...
,I/WifiStateMachine(  890): CMD_RSSI_POLL : calculateWifiScore in!
,I/WifiStateMachine(  890): CMD_RSSI_POLL : calculateWifiScore out!
I/WifiStateMachine(  890): CMD_RSSI_POLL : out!
,D/StatusBar.NetworkController( 1169): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02012b/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020466/com.android.systemui:drawable/stat_sys_signal_inout mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
,D/StatusBar.NetworkController( 1169): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1169): applyOpen
,D/StatusBar.NetworkController( 1169): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1169): applyOpen
,D/StatusBar.NetworkController( 1169): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1169): applyOpen
,D/StatusBar.NetworkController( 1169): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1169): applyOpen
,I/ServiceManager(  326): Waiting for service AtCmdFwd...
,D/SSRM:m  (  890): SIOP:: AP = 350, PST = 403, CUR = 300
D/X       (  890): broadcastSiopLevelIntent:: currentSiopLevel = -1
,I/SystemBroadcastReceiver( 7113): [#DCM#] [DCM_Performance] onReceive completed in time  1448 microsec. 
,E/ActivityManager(  890): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  890): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  890): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  890): checkUser: useridlist=null, currentuser=0
,I/SystemBroadcastReceiver( 7113): [#DCM#] Calling notifyListeners. 
,I/DCMPolicyManager( 7113): [#DCM#] onReceive action = EVENT_SIOP
,D/ContentApp( 1224):  LEVEL : -1
,E/Zygote  ( 8331): MountEmulatedStorage()
,E/Zygote  ( 8331): v2
I/libpersona( 8331): KNOX_SDCARD checking this for 10054
,I/libpersona( 8331): KNOX_SDCARD not a persona
,I/ActivityManager(  890): Start proc com.sec.android.app.videoplayer for broadcast com.sec.android.app.videoplayer/.videowall.TranscodeReceiver: pid=8331 uid=10054 gids={50054, 9997, 3003, 3002, 1028, 1015, 1023} abi=armeabi-v7a
,I/SELinux ( 8331): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 8331): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 8331): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 8331): TimaSignature is unavailable
,D/ActivityThread( 8331): Added TimaKeyStore provider
,D/ResourcesManager( 8331): creating new AssetManager and set to /system/priv-app/SecVideoPlayer/SecVideoPlayer.apk
,W/ResourcesManager( 8331): Asset path '/system/framework/minimode.jar' does not exist or contains no resources.
W/ResourcesManager( 8331): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 8331): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager( 8331): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 8331): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
,E/TranscodeReceiver( 8331): onReceive : android.intent.action.CHECK_SIOP_LEVEL
,D/videowall-Global( 8331): core_num = 4
,W/linker  ( 8331): libsthmb.so has text relocations. This is wasting memory and prevents security hardening. Please fix.
,W/linker  ( 8331): libvwengine.so has text relocations. This is wasting memory and prevents security hardening. Please fix.
,D/videowall-Global( 8331): density : 3.0 width : 1080 height : 1920 Raw width : 1080 Raw height : 1920
D/videowall-Global( 8331): dsp : 1080, swkey : false, Cores : 4, Clock : 0
,D/TranscodeReceiver( 8331):  SIOP_LEVEL: -1
,D/StatusBar.NetworkController( 1169): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02012b/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020464/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
,D/StatusBar.NetworkController( 1169): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1169): applyOpen
,D/StatusBar.NetworkController( 1169): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1169): applyOpen
,D/StatusBar.NetworkController( 1169): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1169): applyOpen
I/ActivityManager(  890): Killing 4946:com.android.defcontainer/u0a5 (adj 15): bgCount ##41
D/StatusBar.NetworkController( 1169): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1169): applyOpen
,W/libprocessgroup(  890): failed to open /acct/uid_10005/pid_4946/cgroup.procs: No such file or directory
,E/SMD     (  277): DCD ON
,W/Atfwd_Sendcmd(  326): AtCmdFwd service not published, waiting... retryCnt : 2
,D/BatteryService(  890): level:100, scale:100, status:5, health:2, present:true, voltage: 4378, temperature: 286, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  890): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  890): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  890):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
I/MotionRecognitionService(  890): Plugged
I/MotionRecognitionService(  890): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1169): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1169): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1169):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3256): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3256): Disconnected process message: 10
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/WifiStateMachine(  890): CMD_RSSI_POLL : calculateWifiScore in!
,I/WifiStateMachine(  890): CMD_RSSI_POLL : calculateWifiScore out!
I/WifiStateMachine(  890): CMD_RSSI_POLL : out!
,D/PowerManagerService(  890): [s] UserActivityState : 1 -> 2
,D/DisplayPowerController(  890): getFinalBrightness : 14 -> 14
,D/PowerManagerService(  890): [s] DisplayPowerCallbacks : onStateChanged()
,D/lights  (  890): lcd : 16 +
,D/lights  (  890): lcd : 16 -
,D/DisplayPowerController(  890): getFinalBrightness : 14 -> 14
,D/lights  (  890): lcd : 14 +
,D/lights  (  890): lcd : 14 -
,D/DisplayPowerController(  890): getFinalBrightness : 14 -> 14
,E/SMD     (  277): DCD ON
,D/StatusBar.NetworkController( 1169): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02012b/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020466/com.android.systemui:drawable/stat_sys_signal_inout mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
,D/StatusBar.NetworkController( 1169): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1169): applyOpen
,D/StatusBar.NetworkController( 1169): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1169): applyOpen
D/StatusBar.NetworkController( 1169): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1169): applyOpen
,D/StatusBar.NetworkController( 1169): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1169): applyOpen
,W/ContextImpl(  890): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/WifiStateMachine(  890): CMD_RSSI_POLL : calculateWifiScore in!
,I/WifiStateMachine(  890): CMD_RSSI_POLL : calculateWifiScore out!
,I/WifiStateMachine(  890): CMD_RSSI_POLL : out!
,D/StatusBar.NetworkController( 1169): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02012b/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020464/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
,D/StatusBar.NetworkController( 1169): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1169): applyOpen
,D/StatusBar.NetworkController( 1169): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1169): applyOpen
D/StatusBar.NetworkController( 1169): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1169): applyOpen
D/StatusBar.NetworkController( 1169): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1169): applyOpen
,E/SMD     (  277): DCD ON
,E/Watchdog(  890): !@Sync 4
,I/WifiStateMachine(  890): CMD_RSSI_POLL : calculateWifiScore in!
,I/WifiStateMachine(  890): CMD_RSSI_POLL : calculateWifiScore out!
,I/WifiStateMachine(  890): CMD_RSSI_POLL : out!
,D/PowerManagerService(  890): [s] UserActivityState : 2 -> 4
I/PowerManagerService(  890): Nap time (uid 1000)...
I/PowerManagerService(  890): !@[ps] Screen__Off(2) : 
I/PowerManagerService(  890): Going to sleep due to screen timeout (uid 1000)...
D/PowerManagerService(  890): [PWL] sb acquire: PowerManagerService.Broadcasts
,D/PowerManagerService(  890): SecHardwareInterface.setBatteryADC : false
,D/InputManager-JNI(  890): setDeviceInteractive: 0
,D/PowerManagerService(  890): handleSandman : startDream()
,E/PowerManagerService(  890): handleSandman : startDreaming, but isDreaming false
I/PowerManagerService(  890): Sleeping (uid 1000)...
D/PowerManagerService(  890): [s] UserActivityState : 4 -> 0
D/PowerManagerService(  890): [input device light] setInputDeviceLightOn is called : 0
,D/InputManager-JNI(  890): sysfs_write +: /sys/class/input/event1/device/enabled: 0
D/PowerManagerService(  890): [input device light] handleInputDeviceLightOff,
I/SurfaceFlinger(  249): id=17 createSurf (1080x1920),2 flag=404, ColorFade
,D/InputManager-JNI(  890): sysfs_write +: /sys/class/input/event2/device/enabled: 0
,D/InputManager-JNI(  890): sysfs_write -: /sys/class/input/event1/device/enabled: 0
,D/InputManager-JNI(  890): sysfs_write -: /sys/class/input/event2/device/enabled: 0
,D/SContextService(  890): 	.unregisterCallback : 1, client=
,D/SContextService(  890): unregisterCallback() : Listener = android.hardware.scontext.SContextService$Listener@b17ae55, Service = Auto Rotation, used = 1
,W/CAE     (  890): unregisterCallback(ContextAwareService.java:199) - [unregi 01] Mutex is locked for AUTO_ROTATION
,V/CAE     (  890): stop(ContextProvider.java:149)
,V/CAE     (  890): clear(AutoRotationRunner.java:182)
,V/CAE     (  890): disable(AutoRotationRunner.java:171)
,I/CAE     (  890): sendCmdToSensorHub(SensorHubCommManager.java:144) - -78, 7, 0, 0,
D/SensorHubManager(  890): SendSensorHubData: send data = -78, 7, 0, 0
D/Sensorhubs(  294): sendContextData: -78, 7, 0, 0
,D/CAE     (  890): getFaultDetectionResult(AutoRotationRunner.java:195) - true
,I/CAE     (  890): notifyCmdProcessResultObserver(ContextProvider.java:617) - CheckResult = 0, Cause = Success
,D/CAE     (  890): doCommendProcess(ContextAwareService.java:314) - complete notify the operation result.
,I/CAE     (  890): displayUsedCountForService(ContextAwareService.java:406) - totalCnt = 0, serviceCount = 0, subCollectionCount = 0
,D/CAE     (  890): showListenerList(ContextAwareService.java:247) - ===== Context Aware Service List =====
,W/CAE     (  890): unregisterCallback(ContextAwareService.java:234) - [unregi 02] Mutex is unlocked for AUTO_ROTATION
,D/SContextService(  890): removeSContextService() : service = Auto Rotation
D/SContextService(  890): ===== SContext Service List =====
D/SContextManager(  890):   .unregisterListener : listener = com.android.internal.policy.impl.WindowOrientationListener$SContextListenerImpl@1a3bd8cb, service=Auto Rotation
,D/KeyguardViewMediator( 1169): onScreenTurnedOff(3)
,I/KeyguardEffectViewController( 1169): *** KeyguardEffectView getInstanceIfExists ***
D/KeyguardEffectViewController( 1169): changeWallpaperByScreenOff()
D/KeyguardViewMediator( 1169): notifyScreenOffLocked
,I/SQLiteSecureOpenHelper( 3581): getWritableDatabase(pwd)
,I/SQLiteSecureOpenHelper( 3581): getDatabaseLocked(b,b,pwd)...
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1169): value : false
D/KeyguardViewMediator( 1169): timeout : 5000
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1169): value : false
,D/DisplayPowerController(  890): ColorFade: onAnimationStart
D/DisplayPowerController(  890): getFinalBrightness : 24 -> 0
,D/lights  (  890): lcd : 7 +
,D/KeyguardViewMediator( 1169): setting alarm to turn off keyguard, seq = 2
D/KeyguardViewMediator( 1169): handleNotifyScreenOff
,D/DisplayPowerController(  890): getFinalBrightness : 24 -> 0
,D/LightsService(  890): [api] [SvcLED] setFlashing :: id = 3, color = 0, mode = 14, onMS = 0, offMS = 0,  (uid: 1000 pid: 890) 
D/LightsService(  890): [SvcLED] setSvcLedStateLocked:: SvcLEDState : 0x0 -> 0x40 | SvcLED(id=3) set On
,D/lights  (  890): lcd : 7 -
D/lights  (  890): lcd : 0 +
,D/LightsService(  890): [SvcLED]  onSensorChanged::light value = 14
,D/SensorManager(  890): registerListener :: 6, TMG399X RGB Sensor, 200000, 0,  
,D/SensorManager(  890): unregisterListener ::   
D/BatteryService(  890): turn on LED for fully charged
,I/CAE     (  890): handleMessage(CaPowerManager.java:182) - AP_SLEEP
D/lights  (  890): lcd : 0 -
D/lights  (  890): led_pattern : 5 +
,I/CAE     (  890): updateApPowerStatus(SensorHubParserProvider.java:421) - AP_SLEEP
,I/CAE     (  890): sendCmdToSensorHub(SensorHubCommManager.java:144) - -76, 13, -46, 0,
D/SensorHubManager(  890): SendSensorHubData: send data = -76, 13, -46, 0
D/Sensorhubs(  294): sendContextData: -76, 13, -46, 0
,D/lights  (  890): led_pattern : 5 -
,D/LightsService(  890): [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=3) maintains its priority right
,I/CAE     (  890): sendCmdToSensorHub(SensorHubCommManager.java:144) - -63, 14, 12, 17, 55,
D/SensorHubManager(  890): SendSensorHubData: send data = -63, 14, 12, 17, 55
D/Sensorhubs(  294): sendContextData: -63, 14, 12, 17, 55
,D/MotionRecognitionService(  890):   mReceiver.onReceive : ACTION_SCREEN_OFF
,E/MotionRecognitionService(  890):  handler : SCREEN_OFF end 
,D/WifiStateMachine(  890): backgroundScan enabled=false startBackgroundScanIfNeeded:false
E/WifiStateMachine(  890): handleScreenStateChanged Exit: false
,D/NotificationService(  890): ACTION_SCREEN_OFF
D/LightsService(  890): [api] [SvcLED] setFlashing :: id = 4, color = ffffffff, mode = 12, onMS = 500, offMS = 2000,  (uid: 1000 pid: 890) 
D/LightsService(  890): [SvcLED] setSvcLedStateLocked:: SvcLEDState : 0x40 -> 0x42 | SvcLED(id=4) set On
,D/LightsService(  890): [SvcLED]  onSensorChanged::light value = 14
,E/WifiStateMachine(  890): setSuspendOptimizationsNative: 4 true -want true stack:setSuspendOptimizationsNative - access$16800 - processMessage - processMsg
,E/WifiStateMachine(  890): setSuspendOptimizationsNative do it 4 true stack:setSuspendOptimizationsNative - access$16800 - processMessage - processMsg
E/native  (  890): do suspend true
,D/SensorManager(  890): registerListener :: 6, TMG399X RGB Sensor, 200000, 0,  
D/SensorManager(  890): unregisterListener ::   
D/LightsService(  890): [SvcLED]  setSvcLedLightLocked :: priority changed! SvcLED(id=3) OUT; SvcLED(id=4) IN
,D/audio_hw_primary(  285): adev_set_parameters: enter: screen_state=off
V/voice   (  285): voice_set_parameters: enter: screen_state=off
V/voice   (  285): voice_set_parameters: exit with code(-2)
V/msm8974_platform(  285): platform_set_parameters: enter: screen_state=off
V/msm8974_platform(  285): platform_set_parameters: exit with code(-2)
D/audio_hw_hfp(  285): audio_extn_hfp_set_parameters: enter
V/audio_hw_primary(  285): adev_set_parameters: exit
,I/SecExternalDisplayIntents_Java(  890): Intent Recieved ..  -android.intent.action.SCREEN_OFFBroadCast Map value - 18
,D/IpRemoteDisplayController(  890): intent received android.intent.action.SCREEN_OFF
D/IpRemoteDisplayController(  890): Bridge Server is not available
,D/VolumePanel( 1169): mCoverBroadcastReceiver: Screen OFF start
,D/VolumePanel( 1169): mCoverBroadcastReceiver : call onDismissSafeVolumeWarning() #1
D/VolumePanel( 1169): mCoverBroadcastReceiver: Screen OFF end
,D/VolumePanel( 1169): mCoverBroadcastReceiver: onReceive() end : intent=Intent { act=android.intent.action.SCREEN_OFF flg=0x50000010 (has extras) }
,D/PersonaManagerService(  890): ACTION_SCREEN_OFF onReceive
,D/PersonaManagerServiceHandler(  890): MSG_ACTION_SCREEN_OFF called
,D/NfcService( 1469): call the applyRotuiing
,D/STATUSBAR-PhoneStatusBar( 1169):      ACTION_SCREEN_OFF is finished!!!! 
,E/StatusBar( 1169): onReceive : Intent.ACTION_SCREEN_OFF
,D/Recents_AlternateRecentsComponent( 1169): dismissHelpPopup 
,D/DisplayPowerState(  890): !@ ColorFade entry
,D/DisplayPowerController(  890): ColorFade: onAnimationEnd
,D/AutomaticBrightnessController(  890): [DAB] setLightSensorEnabled : Send Update unregisterListener mLightSensor
I/AutomaticBrightnessController(  890): [DAB] fileWriteInt : /sys/class/tcon/tcon/auto_br  value : 0
,I/AutomaticBrightnessController(  890): [DAB] fileWriteInt : /sys/class/backlight/panel/auto_brightness  value : 0
D/AutomaticBrightnessController(  890): [DAB] setLightSensorEnabled : unregisterListener mLightSensor
E/LightSensor(  890): Light old sensor_state 8705, new sensor_state : 8193 en : 0
,D/accuweather( 2166): [KK AccuPhone]>>> SWW:66 [0:0] action : androidintentactionSCREEN_OFF
,D/accuweather( 2166): [KK AccuPhone]>>> SWW:467 [0:0] stopRefreshIcon : 1
D/accuweather( 2166): [KK AccuPhone]>>> SWW:364 [0:0] getWeatherRenderer : 1
,D/SensorManager(  890): unregisterListener ::   
,E/Sensors (  890): Acc old sensor_state 8193, new sensor_state : 8192 en : 0
,D/DisplayPowerController(  890): getFinalBrightness : 0 -> 0
,I/DisplayManagerService(  890): Display device changed: DisplayDeviceInfo{"Built-in Screen": 1080 x 1920, 60.0 fps, supportedRefreshRates [60.0], density 480, 422.03 x 424.069 dpi, appVsyncOff 0, presDeadline 17666667, touch INTERNAL, rotation 0, type BUILT_IN, state OFF, FLAG_DEFAULT_DISPLAY, FLAG_ROTATES_WITH_CONTENT, FLAG_SECURE, FLAG_SUPPORTS_PROTECTED_BUFFERS}
,D/SurfaceFlinger(  249): Set power mode=0, type=0 flinger=0xb6a62000
D/qdhwcomposer(  249): hwc_blank: Blanking display: 0
,V/ActivityManager(  890): Display changed displayId=0
,D/DisplayPowerController(  890): getFinalBrightness : 0 -> 0
,D/SensorManager(  890): unregisterListener ::   
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/StatusBar.NetworkController( 1169): onSignalStrengthsChanged signalStrength=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte level=0
D/StatusBar.NetworkController( 1169): updateTelephonySignalStrength: hasService=false ss=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte
D/LockPatternUtilsCache( 1169): value : false
D/StatusBar.NetworkController( 1169): updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal
,D/StatusBar.NetworkController( 1169): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02012b/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020464/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
,D/ConnectivityService(  890): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
,I/SystemBroadcastReceiver( 7113): [#DCM#] [DCM_Performance] onReceive completed in time  221 microsec. 
,I/SystemBroadcastReceiver( 7113): [#DCM#] Calling notifyListeners. 
I/DCMPolicyManager( 7113): [#DCM#] onReceive action = EVENT_SCREEN_OFF
I/DCMController( 7113): [#DCM#] onIntentReceived eventid = EVENT_SCREEN_OFF
,D/SSRM:m  (  890): SIOP:: AP = 330, PST = 388, CUR = 300
,W/ActivityManager(  890): getTasks: caller 10086 does not hold GET_TASKS; limiting output
,W/ActivityManager(  890): getTasks: caller 10086 does not hold GET_TASKS; limiting output
,D/PowerManagerService(  890): [PWL] sb release: PowerManagerService.Broadcasts
,I/rmt_storage(  268): rmt_storage_connect_cb: clnt_h=0x5 conn_h=0xb6b01090
I/rmt_storage(  268): rmt_storage_rw_iovec_cb: /boot/modem_fs2: clnt_h=0x2: req_h=0xa msg_id=3: R/W request received
I/rmt_storage(  268): wakelock acquired: 1, error no: 42
,I/rmt_storage(  268): rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2 Unblock worker thread (th_id: -1229454592)
,I/rmt_storage(  268): rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2: req_h=0xa msg_id=3: Bytes written = 1572864
I/rmt_storage(  268): rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2: req_h=0xa msg_id=3: Send response: res=0 err=0
,I/rmt_storage(  268): rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2 About to block rmt_storage client thread (th_id: -1229454592) wakelock released: 1, error no: 22
I/rmt_storage(  268): 
,I/rmt_storage(  268): rmt_storage_disconnect_cb: clnt_h=0x0x5 conn_h=0x0xb6b01090
,I/qdhwcomposer(  249): handle_blank_event: dpy:0 panel power state: 0
D/qdhwcomposer(  249): hwc_blank: Done blanking display: 0
,D/SurfaceControl(  890): Excessive delay in setPowerMode(): 251ms
D/PowerManagerService(  890): !@[s] blankAllDisplays() : blankAllDisplaysFromPowerManage
D/MISC PowerHAL(  890): sysfs_write +: /sys/class/power_supply/battery/lcd: 0
D/MISC PowerHAL(  890): sysfs_write -: /sys/class/power_supply/battery/lcd: 0
,I/QCOM PowerHAL(  890): Got set_interactive hint
,I/PowerManagerService(  890): [PWL] Off : 0s ago
,I/PowerManagerService(  890): [PWL]   PowerManagerService.Display: ref count=2
I/PowerManagerService(  890): [PWL]     mDisplayReady : false
D/DisplayPowerController(  890): getFinalBrightness : 0 -> 0
D/PowerManagerService(  890): [s] DisplayPowerCallbacks : onStateChanged()
,D/PowerManagerService(  890): [PWL] sb release: PowerManagerService.Display
,E/SMD     (  277): DCD ON
,I/ServiceManager(  326): Waiting for service AtCmdFwd...
,V/AlarmManager(  890): waitForAlarm result :4
,D/BatteryService(  890): level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 287, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  890): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  890): stay LED for fully charged
,D/BatteryService(  890): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  890):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  890): Plugged
,I/MotionRecognitionService(  890): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1169): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1169): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1169):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3256): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3256): Disconnected process message: 10
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/GLSActivity( 1670): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1670): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
I/GLSUser ( 1670): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1670): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1670): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1670): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/Finsky  ( 6565): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,D/Finsky  ( 6565): [1] 5.onFinished: Installation state replication failed.
D/Finsky  ( 6565): [1] 5.onFinished: Scheduling replication attempt 4.
,I/ServiceManager(  326): Waiting for service AtCmdFwd...
,E/SMD     (  277): DCD ON
,I/ServiceManager(  326): Waiting for service AtCmdFwd...
,V/AlarmManager(  890): waitForAlarm result :8
,V/AlarmManager(  890): waitForAlarm result :4
,D/KeyguardUpdateMonitor( 1169): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1169): handleTimeUpdate
,D/KeyguardViewMediator( 1169): received DELAYED_KEYGUARD_ACTION with seq = 2, mDelayedShowingSequence = 2
,D/PersonaManager( 1169): isKioskContainerExistOnDevice
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1169): value : false
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
D/KeyguardViewMediator( 1169): doKeyguard: not showing because lockscreen is off
,D/KeyguardEffectViewController( 1169): onReceive action : android.intent.action.TIME_TICK
,I/KeyguardEffectViewController( 1169): *** don't update sliding image ***
,D/DateView( 1169): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1169): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,I/ServiceManager(  326): Waiting for service AtCmdFwd...
,I/PowerManagerService(  890): [PWL] Off : 5s ago
,I/ServiceManager(  326): Waiting for service AtCmdFwd...
,E/SMD     (  277): DCD ON
,W/Atfwd_Sendcmd(  326): AtCmdFwd service not published, waiting... retryCnt : 3
,E/SMD     (  277): DCD ON
,D/SSRM:m  (  890): SIOP:: AP = 330, PST = 377, CUR = 300
,E/SMD     (  277): DCD ON
,I/PowerManagerService(  890): [PWL] Off : 15s ago
,V/AlarmManager(  890): waitForAlarm result :4
,D/ConnectivityService(  890): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/SMD     (  277): DCD ON
,D/ConnectivityService(  890): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/GLSUser ( 1670): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,I/GLSUser ( 1670): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1670): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1670): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1670): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/BitmapFactory( 1670): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  890): uri = 14 selection = getSealedState
,D/SecContentProvider2(  890): mCursor = null
D/SecContentProvider2(  890): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  890): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy(  890): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/StatusBar( 1169): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,I/PhoneStatusBar( 1169): Icon Only
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
D/PanelView( 1169): There is/are notification(s) 
D/PanelView( 1169): There is/are notification(s) 
,E/HttpOperation( 6526): [kfu{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
E/HttpOperation( 6526): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 6526): 	at kfv.a(PG:65)
E/HttpOperation( 6526): 	at kff.u(PG:385)
E/HttpOperation( 6526): 	at kfb.a(PG:29)
E/HttpOperation( 6526): 	at kff.l(PG:132)
E/HttpOperation( 6526): 	at dsf.a(PG:807)
E/HttpOperation( 6526): 	at fhk.a(PG:1126)
E/HttpOperation( 6526): 	at fhk.a(PG:908)
E/HttpOperation( 6526): 	at fhk.onPerformSync(PG:636)
E/HttpOperation( 6526): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/HttpOperation( 6526): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/HttpOperation( 6526): 	at ihi.a(PG:22)
E/HttpOperation( 6526): 	at kft.a(PG:91)
E/HttpOperation( 6526): 	at kfv.a(PG:62)
E/HttpOperation( 6526): 	... 8 more
E/HttpOperation( 6526): Caused by: gdi: User intervention required. Notification has been pushed.
E/HttpOperation( 6526): 	at gde.c(Unknown Source)
E/HttpOperation( 6526): 	at gde.b(Unknown Source)
E/HttpOperation( 6526): 	at ihi.a(PG:19)
E/HttpOperation( 6526): 	... 10 more
,I/GLSUser ( 1670): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,I/GLSUser ( 1670): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1670): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1670): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1670): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/BitmapFactory( 1670): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  890): uri = 14 selection = getSealedState
D/SecContentProvider2(  890): mCursor = null
,D/SecContentProvider2(  890): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  890): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy(  890): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/StatusBar( 1169): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,I/PhoneStatusBar( 1169): Icon Only
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
D/PanelView( 1169): There is/are notification(s) 
D/PanelView( 1169): There is/are notification(s) 
,E/HttpOperation( 6526): [getmobileexperiments] Unexpected exception
E/HttpOperation( 6526): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 6526): 	at kfv.a(PG:65)
E/HttpOperation( 6526): 	at kff.u(PG:385)
E/HttpOperation( 6526): 	at kfb.a(PG:29)
E/HttpOperation( 6526): 	at kff.l(PG:132)
E/HttpOperation( 6526): 	at ieo.a(PG:43)
E/HttpOperation( 6526): 	at iep.a(PG:93)
E/HttpOperation( 6526): 	at fhn.a(PG:59)
E/HttpOperation( 6526): 	at lex.a(PG:85)
E/HttpOperation( 6526): 	at lex.b(PG:132)
E/HttpOperation( 6526): 	at fhk.a(PG:1146)
E/HttpOperation( 6526): 	at fhk.a(PG:908)
E/HttpOperation( 6526): 	at fhk.onPerformSync(PG:636)
E/HttpOperation( 6526): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/HttpOperation( 6526): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/HttpOperation( 6526): 	at ihi.a(PG:22)
E/HttpOperation( 6526): 	at kft.a(PG:91)
E/HttpOperation( 6526): 	at kfv.a(PG:62)
E/HttpOperation( 6526): 	... 12 more
E/HttpOperation( 6526): Caused by: gdi: User intervention required. Notification has been pushed.
E/HttpOperation( 6526): 	at gde.c(Unknown Source)
E/HttpOperation( 6526): 	at gde.b(Unknown Source)
E/HttpOperation( 6526): 	at ihi.a(PG:19)
E/HttpOperation( 6526): 	... 14 more
,E/ExperimentLoader( 6526): [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 6526): java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 6526): 	at kfv.a(PG:65)
E/ExperimentLoader( 6526): 	at kff.u(PG:385)
E/ExperimentLoader( 6526): 	at kfb.a(PG:29)
E/ExperimentLoader( 6526): 	at kff.l(PG:132)
E/ExperimentLoader( 6526): 	at ieo.a(PG:43)
E/ExperimentLoader( 6526): 	at iep.a(PG:93)
E/ExperimentLoader( 6526): 	at fhn.a(PG:59)
E/ExperimentLoader( 6526): 	at lex.a(PG:85)
E/ExperimentLoader( 6526): 	at lex.b(PG:132)
E/ExperimentLoader( 6526): 	at fhk.a(PG:1146)
E/ExperimentLoader( 6526): 	at fhk.a(PG:908)
E/ExperimentLoader( 6526): 	at fhk.onPerformSync(PG:636)
E/ExperimentLoader( 6526): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/ExperimentLoader( 6526): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/ExperimentLoader( 6526): 	at ihi.a(PG:22)
E/ExperimentLoader( 6526): 	at kft.a(PG:91)
E/ExperimentLoader( 6526): 	at kfv.a(PG:62)
E/ExperimentLoader( 6526): 	... 12 more
E/ExperimentLoader( 6526): Caused by: gdi: User intervention required. Notification has been pushed.
E/ExperimentLoader( 6526): 	at gde.c(Unknown Source)
E/ExperimentLoader( 6526): 	at gde.b(Unknown Source)
E/ExperimentLoader( 6526): 	at ihi.a(PG:19)
E/ExperimentLoader( 6526): 	... 14 more
,I/GLSUser ( 1670): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,I/GLSUser ( 1670): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1670): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1670): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1670): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/BitmapFactory( 1670): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  890): uri = 14 selection = getSealedState
,D/SecContentProvider2(  890): mCursor = null
D/SecContentProvider2(  890): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  890): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy(  890): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/StatusBar( 1169): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,I/PhoneStatusBar( 1169): Icon Only
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
D/PanelView( 1169): There is/are notification(s) 
D/PanelView( 1169): There is/are notification(s) 
,E/HttpOperation( 6526): [getaccountstatus] Unexpected exception
E/HttpOperation( 6526): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 6526): 	at kfv.a(PG:65)
E/HttpOperation( 6526): 	at kff.u(PG:385)
E/HttpOperation( 6526): 	at kfb.a(PG:29)
E/HttpOperation( 6526): 	at ixd.a(PG:248)
E/HttpOperation( 6526): 	at ixd.b(PG:206)
E/HttpOperation( 6526): 	at ixd.a(PG:175)
E/HttpOperation( 6526): 	at fig.a(PG:78)
E/HttpOperation( 6526): 	at lex.a(PG:85)
E/HttpOperation( 6526): 	at lex.b(PG:132)
E/HttpOperation( 6526): 	at fhk.a(PG:1146)
E/HttpOperation( 6526): 	at fhk.a(PG:908)
E/HttpOperation( 6526): 	at fhk.onPerformSync(PG:636)
E/HttpOperation( 6526): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/HttpOperation( 6526): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/HttpOperation( 6526): 	at ihi.a(PG:22)
E/HttpOperation( 6526): 	at kft.a(PG:91)
E/HttpOperation( 6526): 	at kfv.a(PG:62)
E/HttpOperation( 6526): 	... 12 more
E/HttpOperation( 6526): Caused by: gdi: User intervention required. Notification has been pushed.
E/HttpOperation( 6526): 	at gde.c(Unknown Source)
E/HttpOperation( 6526): 	at gde.b(Unknown Source)
E/HttpOperation( 6526): 	at ihi.a(PG:19)
E/HttpOperation( 6526): 	... 14 more
,E/EsSyncAdapterService( 6526): Sync failure
E/EsSyncAdapterService( 6526): java.io.IOException: Rpc failed
E/EsSyncAdapterService( 6526): 	at ixd.a(PG:348)
E/EsSyncAdapterService( 6526): 	at ixd.a(PG:248)
E/EsSyncAdapterService( 6526): 	at ixd.b(PG:206)
E/EsSyncAdapterService( 6526): 	at ixd.a(PG:175)
E/EsSyncAdapterService( 6526): 	at fig.a(PG:78)
E/EsSyncAdapterService( 6526): 	at lex.a(PG:85)
E/EsSyncAdapterService( 6526): 	at lex.b(PG:132)
E/EsSyncAdapterService( 6526): 	at fhk.a(PG:1146)
E/EsSyncAdapterService( 6526): 	at fhk.a(PG:908)
E/EsSyncAdapterService( 6526): 	at fhk.onPerformSync(PG:636)
E/EsSyncAdapterService( 6526): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/EsSyncAdapterService( 6526): Caused by: java.io.IOException: Cannot obtain authentication token
E/EsSyncAdapterService( 6526): 	at kfv.a(PG:65)
E/EsSyncAdapterService( 6526): 	at kff.u(PG:385)
E/EsSyncAdapterService( 6526): 	at kfb.a(PG:29)
E/EsSyncAdapterService( 6526): 	... 10 more
E/EsSyncAdapterService( 6526): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/EsSyncAdapterService( 6526): 	at ihi.a(PG:22)
E/EsSyncAdapterService( 6526): 	at kft.a(PG:91)
E/EsSyncAdapterService( 6526): 	at kfv.a(PG:62)
E/EsSyncAdapterService( 6526): 	... 12 more
E/EsSyncAdapterService( 6526): Caused by: gdi: User intervention required. Notification has been pushed.
E/EsSyncAdapterService( 6526): 	at gde.c(Unknown Source)
E/EsSyncAdapterService( 6526): 	at gde.b(Unknown Source)
E/EsSyncAdapterService( 6526): 	at ihi.a(PG:19)
E/EsSyncAdapterService( 6526): 	... 14 more
,D/ConnectivityService(  890): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SyncManager(  890): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, PERIODIC, currentRunTime 124929, reason: Periodic, SyncResult: stats [ numIoExceptions: 2]
,D/ConnectivityService(  890): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  890): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SecContentProvider2(  890): uri = 11 selection = getMyKnoxAdmin
D/SecContentProvider2(  890): mCursor = null
,W/ContextImpl(  890): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SQLiteLog( 1670): (10) POSIX Error : 11 SQLite Error : 3850
,E/SMD     (  277): DCD ON
,D/SSRM:m  (  890): SIOP:: AP = 320, PST = 368, CUR = 300
,E/SMD     (  277): DCD ON,
,I/ServiceManager(  326): Waiting for service AtCmdFwd...
,V/AlarmManager(  890): waitForAlarm result :4,
,I/ServiceManager(  326): Waiting for service AtCmdFwd...
,I/art     ( 1670): Explicit concurrent mark sweep GC freed 42618(2MB) AllocSpace objects, 30(2MB) LOS objects, 40% free, 17MB/29MB, paused 835us total 88.824ms
,V/GLSActivity( 1670): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1670): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
,I/GLSUser ( 1670): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1670): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1670): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1670): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/Finsky  ( 6565): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,D/Finsky  ( 6565): [1] 5.onFinished: Installation state replication failed.
D/Finsky  ( 6565): [1] 5.onFinished: Scheduling replication attempt 5.
,I/ServiceManager(  326): Waiting for service AtCmdFwd...
,E/SMD     (  277): DCD ON
,I/ServiceManager(  326): Waiting for service AtCmdFwd...
,D/BatteryService(  890): level:100, scale:100, status:5, health:2, present:true, voltage: 4386, temperature: 287, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  890): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  890): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  890):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  890): Plugged
,I/MotionRecognitionService(  890): setPowerConnected  = true
,D/BatteryService(  890): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1169): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1169): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1169):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3256): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3256): Disconnected process message: 10
,I/ServiceManager(  326): Waiting for service AtCmdFwd...
,W/Atfwd_Sendcmd(  326): AtCmdFwd service not published, waiting... retryCnt : 4
,E/SMD     (  277): DCD ON
,E/Watchdog(  890): !@Sync 5
,D/SSRM:m  (  890): SIOP:: AP = 310, PST = 358, CUR = 300
,I/PowerManagerService(  890): [PWL] Off : 30s ago
,E/SMD     (  277): DCD ON
,E/SMD     (  277): DCD ON
,W/ContextImpl(  890): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  277): DCD ON
,E/SMD     (  277): DCD ON
,D/SSRM:m  (  890): SIOP:: AP = 310, PST = 349, CUR = 300
,E/SMD     (  277): DCD ON
,V/AlarmManager(  890): waitForAlarm result :4
,D/ConnectivityService(  890): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  890): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,V/GLSActivity( 1670): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ConnectivityService(  890): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/VacuumService( 1670): Vacuum at: now=1452773919185 tag=VacuumService
,D/ConnectivityService(  890): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/GoogleURLConnFactory( 1670): Using platform SSLCertificateSocketFactory
,D/ConnectivityService(  890): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/GLSUser ( 1670): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
I/GLSUser ( 1670): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1670): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1670): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1670): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/BitmapFactory( 1670): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/common_ic_googleplayservices.png
,V/BitmapFactory( 1670): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  890): uri = 14 selection = getSealedState
D/SecContentProvider2(  890): mCursor = null
D/SecContentProvider2(  890): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  890): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
V/ApplicationPolicy(  890): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/StatusBar( 1169): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,I/PhoneStatusBar( 1169): Icon Only
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
D/PanelView( 1169): There is/are notification(s) 
D/PanelView( 1169): There is/are notification(s) 
E/Uploader( 1670): Failed to get auth token: User intervention required. Notification has been pushed.
E/Uploader( 1670): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
E/Uploader( 1670): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
E/Uploader( 1670): 	at com.google.android.gms.auth.p.d(SourceFile:599)
E/Uploader( 1670): 	at com.google.android.gms.auth.p.c(SourceFile:550)
E/Uploader( 1670): 	at com.google.android.gms.auth.p.b(SourceFile:477)
E/Uploader( 1670): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:508)
E/Uploader( 1670): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:337)
E/Uploader( 1670): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:263)
E/Uploader( 1670): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:235)
E/Uploader( 1670): 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:125)
E/Uploader( 1670): 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:78)
E/Uploader( 1670): 	at com.google.android.gms.gcm.am.run(SourceFile:135)
,I/System.out( 1670): (HTTPLog)-Static: SBServiceAPI: getService class android.os.ServiceManager
I/System.out( 1670): (HTTPLog)-Static: isShipBuild true
I/System.out( 1670): (HTTPLog)-Thread-204-117890384: SmartBonding Enabling is true, SHIP_BUILD is true, log to file is false, DBG is false
,I/qtaguid ( 1670): Tagging socket 55 with tag 120100000000{4609,0} uid -1, pid: 1670, getuid(): 10012
,V/GLSActivity( 1670): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1670): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
I/GLSUser ( 1670): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1670): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1670): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1670): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/qtaguid ( 1670): Tagging socket 61 with tag 120100000000{4609,0} uid -1, pid: 1670, getuid(): 10012
,D/Finsky  ( 6565): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,D/Finsky  ( 6565): [1] 5.onFinished: Installation state replication failed.
,D/Finsky  ( 6565): [1] 5.onFinished: Giving up after 6 failures.
,W/Uploader( 1670): No account for auth token provided
,I/qtaguid ( 1670): Tagging socket 55 with tag 120100000000{4609,0} uid -1, pid: 1670, getuid(): 10012
,W/Uploader( 1670): No account for auth token provided
,I/qtaguid ( 1670): Tagging socket 55 with tag 120100000000{4609,0} uid -1, pid: 1670, getuid(): 10012
,W/Uploader( 1670): No account for auth token provided
,I/qtaguid ( 1670): Tagging socket 55 with tag 120100000000{4609,0} uid -1, pid: 1670, getuid(): 10012
,W/Uploader( 1670): No account for auth token provided
,I/qtaguid ( 1670): Tagging socket 55 with tag 120100000000{4609,0} uid -1, pid: 1670, getuid(): 10012
,W/Uploader( 1670):  no longer exists, so no auth token.
,I/qtaguid ( 1670): Tagging socket 55 with tag 120100000000{4609,0} uid -1, pid: 1670, getuid(): 10012
,E/SQLiteLog( 1670): (10) POSIX Error : 11 SQLite Error : 3850
,D/ConnectivityService(  890): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/SMD     (  277): DCD ON
,V/AlarmManager(  890): waitForAlarm result :4
,D/ConnectivityService(  890): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  890): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/BooksSync( 7396): Starting books sync, d
,D/ConnectivityService(  890): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,V/GLSActivity( 1670): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1670): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
,I/GLSUser ( 1670): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1670): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1670): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1670): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ResourcesManager( 1670): creating new AssetManager and set to /system/app/Books/Books.apk
,V/BitmapFactory( 1670): DecodeImagePath(decodeResourceStream3) : res/mipmap-xxhdpi-v4/ic_launcher_play_books.png
,V/BitmapFactory( 1670): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  890): uri = 14 selection = getSealedState
,D/SecContentProvider2(  890): mCursor = null
D/SecContentProvider2(  890): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  890): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy(  890): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/StatusBar( 1169): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,I/PhoneStatusBar( 1169): Icon Only
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
D/PanelView( 1169): There is/are notification(s) 
D/PanelView( 1169): There is/are notification(s) 
,W/GLSActivity( 1670): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1670): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1670): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1670): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1670): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1670): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1670): 	at android.os.Binder.execTransact(Binder.java:446)
,E/BooksAccountManager( 7396): Authentication error
E/BooksAccountManager( 7396): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 7396): android.accounts.AccountManager.convertErrorToException(AccountManager.java:1893)
,E/HttpHelper( 7396): null auth token
,I/qtaguid ( 7396): Tagging socket 34 with tag 10000000000{256,0} uid -1, pid: 7396, getuid(): 10082
,I/qtaguid ( 7396): Tagging socket 34 with tag 10000000000{256,0} uid -1, pid: 7396, getuid(): 10082
,I/qtaguid ( 7396): Untagging socket 34
,W/ApiaryClient( 7396): Error response from books API: {
W/ApiaryClient( 7396):  "error": {
W/ApiaryClient( 7396):   "errors": [
W/ApiaryClient( 7396):    {
W/ApiaryClient( 7396):     "domain": "global",
W/ApiaryClient( 7396):     "reason": "required",
W/ApiaryClient( 7396):     "message": "Login Required",
W/ApiaryClient( 7396):     "locationType": "header",
W/ApiaryClient( 7396):     "location": "Authorization"
W/ApiaryClient( 7396):    }
W/ApiaryClient( 7396):   ],
W/ApiaryClient( 7396):   "code": 401,
W/ApiaryClient( 7396):   "message": "Login Required"
W/ApiaryClient( 7396):  }
W/ApiaryClient( 7396): }
,W/ApiaryClient( 7396): errCount = 1: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 7396): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3DS0HXd4TFLU4&nonce=-170290088781239185&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 7396): Headers suppressed
,D/ConnectivityService(  890): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/ServiceManager(  326): Waiting for service AtCmdFwd...
,V/GLSActivity( 1670): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1670): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
,I/GLSUser ( 1670): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1670): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1670): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1670): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/BitmapFactory( 1670): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  890): uri = 14 selection = getSealedState
,D/SecContentProvider2(  890): mCursor = null
,D/SecContentProvider2(  890): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  890): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy(  890): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/StatusBar( 1169): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,I/PhoneStatusBar( 1169): Icon Only
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
D/PanelView( 1169): There is/are notification(s) 
,D/PanelView( 1169): There is/are notification(s) 
,W/GLSActivity( 1670): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1670): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1670): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1670): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1670): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1670): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1670): 	at android.os.Binder.execTransact(Binder.java:446)
,E/BooksAccountManager( 7396): Authentication error
E/BooksAccountManager( 7396): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 7396): android.accounts.AccountManager.convertErrorToException(AccountManager.java:1893)
,E/HttpHelper( 7396): null auth token
,I/qtaguid ( 7396): Tagging socket 34 with tag 10000000000{256,0} uid -1, pid: 7396, getuid(): 10082
,I/qtaguid ( 7396): Tagging socket 39 with tag 10000000000{256,0} uid -1, pid: 7396, getuid(): 10082
,I/qtaguid ( 7396): Untagging socket 34
,W/ApiaryClient( 7396): Error response from books API: {
W/ApiaryClient( 7396):  "error": {
W/ApiaryClient( 7396):   "errors": [
W/ApiaryClient( 7396):    {
W/ApiaryClient( 7396):     "domain": "global",
W/ApiaryClient( 7396):     "reason": "required",
W/ApiaryClient( 7396):     "message": "Login Required",
W/ApiaryClient( 7396):     "locationType": "header",
W/ApiaryClient( 7396):     "location": "Authorization"
W/ApiaryClient( 7396):    }
W/ApiaryClient( 7396):   ],
W/ApiaryClient( 7396):   "code": 401,
W/ApiaryClient( 7396):   "message": "Login Required"
W/ApiaryClient( 7396):  }
W/ApiaryClient( 7396): }
,W/ApiaryClient( 7396): errCount = 2: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 7396): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3DS0HXd4TFLU4&nonce=-170290088781239185&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 7396): Headers suppressed
,D/ConnectivityService(  890): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/ServiceManager(  326): Waiting for service AtCmdFwd...
,V/GLSActivity( 1670): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1670): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
,I/GLSUser ( 1670): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1670): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1670): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1670): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/BitmapFactory( 1670): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  890): uri = 14 selection = getSealedState
,D/SecContentProvider2(  890): mCursor = null
,D/SecContentProvider2(  890): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  890): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy(  890): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/StatusBar( 1169): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,I/PhoneStatusBar( 1169): Icon Only
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
D/PanelView( 1169): There is/are notification(s) 
,D/PanelView( 1169): There is/are notification(s) 
,W/GLSActivity( 1670): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1670): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1670): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1670): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1670): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1670): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1670): 	at android.os.Binder.execTransact(Binder.java:446)
,E/BooksAccountManager( 7396): Authentication error
E/BooksAccountManager( 7396): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 7396): android.accounts.AccountManager.convertErrorToException(AccountManager.java:1893)
,E/HttpHelper( 7396): null auth token
,I/qtaguid ( 7396): Tagging socket 34 with tag 10000000000{256,0} uid -1, pid: 7396, getuid(): 10082
,E/SMD     (  277): DCD ON
,I/qtaguid ( 7396): Untagging socket 34
,W/ApiaryClient( 7396): Error response from books API: {
W/ApiaryClient( 7396):  "error": {
W/ApiaryClient( 7396):   "errors": [
W/ApiaryClient( 7396):    {
W/ApiaryClient( 7396):     "domain": "global",
W/ApiaryClient( 7396):     "reason": "required",
W/ApiaryClient( 7396):     "message": "Login Required",
W/ApiaryClient( 7396):     "locationType": "header",
W/ApiaryClient( 7396):     "location": "Authorization"
W/ApiaryClient( 7396):    }
W/ApiaryClient( 7396):   ],
W/ApiaryClient( 7396):   "code": 401,
W/ApiaryClient( 7396):   "message": "Login Required"
W/ApiaryClient( 7396):  }
W/ApiaryClient( 7396): }
,W/ApiaryClient( 7396): errCount = 3: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 7396): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3DS0HXd4TFLU4&nonce=-170290088781239185&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 7396): Headers suppressed
,D/ConnectivityService(  890): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/ServiceManager(  326): Waiting for service AtCmdFwd...
,E/BooksSync( 7396): Soft error
E/BooksSync( 7396): com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
E/BooksSync( 7396): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3DS0HXd4TFLU4&nonce=-170290088781239185&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
E/BooksSync( 7396): Headers suppressed
E/BooksSync( 7396): 
E/BooksSync( 7396): com.google.android.apps.books.net.HttpHelper.wrapExceptionBasedOnStatus(HttpHelper.java:212)
,E/BooksSync( 7396): Sync error
E/BooksSync( 7396): com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
E/BooksSync( 7396): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3DS0HXd4TFLU4&nonce=-170290088781239185&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
E/BooksSync( 7396): Headers suppressed
E/BooksSync( 7396): 
E/BooksSync( 7396): com.google.android.apps.books.net.HttpHelper.wrapExceptionBasedOnStatus(HttpHelper.java:212)
,I/BooksSync( 7396): Finished books sync
,D/ConnectivityService(  890): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SyncManager(  890): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 157794, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,D/ConnectivityService(  890): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  890): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/ServiceManager(  326): Waiting for service AtCmdFwd...
,D/ConnectivityService(  890): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/art     (  890): Explicit concurrent mark sweep GC freed 68322(3MB) AllocSpace objects, 32(3MB) LOS objects, 30% free, 36MB/52MB, paused 2.021ms total 176.600ms
,D/SecContentProvider2(  890): uri = 11 selection = getMyKnoxAdmin
D/SecContentProvider2(  890): mCursor = null
,D/ConnectivityService(  890): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false],
,I/GLSUser ( 1670): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
I/GLSUser ( 1670): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1670): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1670): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1670): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ResourcesManager( 1670): creating new AssetManager and set to /system/app/PlusOne/PlusOne.apk
,V/BitmapFactory( 1670): DecodeImagePath(decodeResourceStream3) : res/mipmap-xxhdpi-v4/quantum_logo_google_plus_color_44in48.png
,V/BitmapFactory( 1670): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  890): uri = 14 selection = getSealedState
D/SecContentProvider2(  890): mCursor = null
,D/SecContentProvider2(  890): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  890): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy(  890): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/StatusBar( 1169): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,E/HttpOperation( 6526): [kfu{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
E/HttpOperation( 6526): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 6526): 	at kfv.a(PG:65)
E/HttpOperation( 6526): 	at kff.u(PG:385)
E/HttpOperation( 6526): 	at kfb.a(PG:29)
E/HttpOperation( 6526): 	at kff.l(PG:132)
E/HttpOperation( 6526): 	at dsf.a(PG:807)
E/HttpOperation( 6526): 	at fhk.a(PG:1126)
E/HttpOperation( 6526): 	at fhk.a(PG:908)
E/HttpOperation( 6526): 	at fhk.onPerformSync(PG:636)
E/HttpOperation( 6526): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/HttpOperation( 6526): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/HttpOperation( 6526): 	at ihi.a(PG:22)
E/HttpOperation( 6526): 	at kft.a(PG:91)
E/HttpOperation( 6526): 	at kfv.a(PG:62)
E/HttpOperation( 6526): 	... 8 more
E/HttpOperation( 6526): Caused by: gdi: User intervention required. Notification has been pushed.
E/HttpOperation( 6526): 	at gde.c(Unknown Source)
E/HttpOperation( 6526): 	at gde.b(Unknown Source)
E/HttpOperation( 6526): 	at ihi.a(PG:19)
E/HttpOperation( 6526): 	... 10 more
,I/PhoneStatusBar( 1169): Icon Only
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
D/PanelView( 1169): There is/are notification(s) 
D/PanelView( 1169): There is/are notification(s) 
,I/GLSUser ( 1670): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
I/GLSUser ( 1670): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1670): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1670): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/PowerManagerService(  890): [PWL] Off : 50s ago
,I/PowerManagerService(  890): [PWL]   PowerManagerService.WakeLocks: ref count=1
V/GLSActivity( 1670): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/PowerManagerService(  890): [PWL]     mWakeLockSummary : 0x1
,I/PowerManagerService(  890): [PWL]       PARTIAL_WAKE_LOCK              '*sync*/com.google.android.apps.plus.content.EsProvider/com.google/eM_ADDR' (uid=1000, pid=890, ws=WorkSource{10135}) (elapsedTime=394)
,V/BitmapFactory( 1670): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  890): uri = 14 selection = getSealedState
,D/SecContentProvider2(  890): mCursor = null
D/SecContentProvider2(  890): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  890): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
V/ApplicationPolicy(  890): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/StatusBar( 1169): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,I/PhoneStatusBar( 1169): Icon Only
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
D/PanelView( 1169): There is/are notification(s) 
,D/PanelView( 1169): There is/are notification(s) 
,E/HttpOperation( 6526): [getmobileexperiments] Unexpected exception
E/HttpOperation( 6526): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 6526): 	at kfv.a(PG:65)
E/HttpOperation( 6526): 	at kff.u(PG:385)
E/HttpOperation( 6526): 	at kfb.a(PG:29)
E/HttpOperation( 6526): 	at kff.l(PG:132)
E/HttpOperation( 6526): 	at ieo.a(PG:43)
E/HttpOperation( 6526): 	at iep.a(PG:93)
E/HttpOperation( 6526): 	at fhn.a(PG:59)
E/HttpOperation( 6526): 	at lex.a(PG:85)
E/HttpOperation( 6526): 	at lex.b(PG:132)
E/HttpOperation( 6526): 	at fhk.a(PG:1146)
E/HttpOperation( 6526): 	at fhk.a(PG:908)
E/HttpOperation( 6526): 	at fhk.onPerformSync(PG:636)
E/HttpOperation( 6526): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/HttpOperation( 6526): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/HttpOperation( 6526): 	at ihi.a(PG:22)
E/HttpOperation( 6526): 	at kft.a(PG:91)
E/HttpOperation( 6526): 	at kfv.a(PG:62)
E/HttpOperation( 6526): 	... 12 more
E/HttpOperation( 6526): Caused by: gdi: User intervention required. Notification has been pushed.
E/HttpOperation( 6526): 	at gde.c(Unknown Source)
E/HttpOperation( 6526): 	at gde.b(Unknown Source)
E/HttpOperation( 6526): 	at ihi.a(PG:19)
E/HttpOperation( 6526): 	... 14 more
,E/ExperimentLoader( 6526): [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 6526): java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 6526): 	at kfv.a(PG:65)
E/ExperimentLoader( 6526): 	at kff.u(PG:385)
E/ExperimentLoader( 6526): 	at kfb.a(PG:29)
E/ExperimentLoader( 6526): 	at kff.l(PG:132)
E/ExperimentLoader( 6526): 	at ieo.a(PG:43)
E/ExperimentLoader( 6526): 	at iep.a(PG:93)
E/ExperimentLoader( 6526): 	at fhn.a(PG:59)
E/ExperimentLoader( 6526): 	at lex.a(PG:85)
E/ExperimentLoader( 6526): 	at lex.b(PG:132)
E/ExperimentLoader( 6526): 	at fhk.a(PG:1146)
E/ExperimentLoader( 6526): 	at fhk.a(PG:908)
E/ExperimentLoader( 6526): 	at fhk.onPerformSync(PG:636)
E/ExperimentLoader( 6526): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/ExperimentLoader( 6526): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/ExperimentLoader( 6526): 	at ihi.a(PG:22)
E/ExperimentLoader( 6526): 	at kft.a(PG:91)
E/ExperimentLoader( 6526): 	at kfv.a(PG:62)
E/ExperimentLoader( 6526): 	... 12 more
E/ExperimentLoader( 6526): Caused by: gdi: User intervention required. Notification has been pushed.
E/ExperimentLoader( 6526): 	at gde.c(Unknown Source)
E/ExperimentLoader( 6526): 	at gde.b(Unknown Source)
E/ExperimentLoader( 6526): 	at ihi.a(PG:19)
E/ExperimentLoader( 6526): 	... 14 more
D/SSRM:m  (  890): SIOP:: AP = 310, PST = 343, CUR = 300
,I/GLSUser ( 1670): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,I/GLSUser ( 1670): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1670): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1670): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1670): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/BitmapFactory( 1670): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  890): uri = 14 selection = getSealedState
,D/SecContentProvider2(  890): mCursor = null
D/SecContentProvider2(  890): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  890): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy(  890): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/StatusBar( 1169): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,I/PhoneStatusBar( 1169): Icon Only
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
D/PanelView( 1169): There is/are notification(s) 
,D/PanelView( 1169): There is/are notification(s) 
,E/HttpOperation( 6526): [getaccountstatus] Unexpected exception
E/HttpOperation( 6526): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 6526): 	at kfv.a(PG:65)
E/HttpOperation( 6526): 	at kff.u(PG:385)
E/HttpOperation( 6526): 	at kfb.a(PG:29)
E/HttpOperation( 6526): 	at ixd.a(PG:248)
E/HttpOperation( 6526): 	at ixd.b(PG:206)
E/HttpOperation( 6526): 	at ixd.a(PG:175)
E/HttpOperation( 6526): 	at fig.a(PG:78)
E/HttpOperation( 6526): 	at lex.a(PG:85)
E/HttpOperation( 6526): 	at lex.b(PG:132)
E/HttpOperation( 6526): 	at fhk.a(PG:1146)
E/HttpOperation( 6526): 	at fhk.a(PG:908)
E/HttpOperation( 6526): 	at fhk.onPerformSync(PG:636)
E/HttpOperation( 6526): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/HttpOperation( 6526): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/HttpOperation( 6526): 	at ihi.a(PG:22)
E/HttpOperation( 6526): 	at kft.a(PG:91)
E/HttpOperation( 6526): 	at kfv.a(PG:62)
E/HttpOperation( 6526): 	... 12 more
E/HttpOperation( 6526): Caused by: gdi: User intervention required. Notification has been pushed.
E/HttpOperation( 6526): 	at gde.c(Unknown Source)
E/HttpOperation( 6526): 	at gde.b(Unknown Source)
E/HttpOperation( 6526): 	at ihi.a(PG:19)
E/HttpOperation( 6526): 	... 14 more
,E/EsSyncAdapterService( 6526): Sync failure
E/EsSyncAdapterService( 6526): java.io.IOException: Rpc failed
E/EsSyncAdapterService( 6526): 	at ixd.a(PG:348)
E/EsSyncAdapterService( 6526): 	at ixd.a(PG:248)
E/EsSyncAdapterService( 6526): 	at ixd.b(PG:206)
E/EsSyncAdapterService( 6526): 	at ixd.a(PG:175)
E/EsSyncAdapterService( 6526): 	at fig.a(PG:78)
E/EsSyncAdapterService( 6526): 	at lex.a(PG:85)
E/EsSyncAdapterService( 6526): 	at lex.b(PG:132)
E/EsSyncAdapterService( 6526): 	at fhk.a(PG:1146)
E/EsSyncAdapterService( 6526): 	at fhk.a(PG:908)
E/EsSyncAdapterService( 6526): 	at fhk.onPerformSync(PG:636)
E/EsSyncAdapterService( 6526): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/EsSyncAdapterService( 6526): Caused by: java.io.IOException: Cannot obtain authentication token
E/EsSyncAdapterService( 6526): 	at kfv.a(PG:65)
E/EsSyncAdapterService( 6526): 	at kff.u(PG:385)
E/EsSyncAdapterService( 6526): 	at kfb.a(PG:29)
E/EsSyncAdapterService( 6526): 	... 10 more
E/EsSyncAdapterService( 6526): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/EsSyncAdapterService( 6526): 	at ihi.a(PG:22)
E/EsSyncAdapterService( 6526): 	at kft.a(PG:91)
E/EsSyncAdapterService( 6526): 	at kfv.a(PG:62)
E/EsSyncAdapterService( 6526): 	... 12 more
E/EsSyncAdapterService( 6526): Caused by: gdi: User intervention required. Notification has been pushed.
E/EsSyncAdapterService( 6526): 	at gde.c(Unknown Source)
E/EsSyncAdapterService( 6526): 	at gde.b(Unknown Source)
E/EsSyncAdapterService( 6526): 	at ihi.a(PG:19)
E/EsSyncAdapterService( 6526): 	... 14 more
,D/ConnectivityService(  890): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/SyncManager(  890): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, PERIODIC, currentRunTime 183928, reason: Periodic, SyncResult: stats [ numIoExceptions: 2]
D/ConnectivityService(  890): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  890): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SecContentProvider2(  890): uri = 11 selection = getMyKnoxAdmin
D/SecContentProvider2(  890): mCursor = null
,I/ServiceManager(  326): Waiting for service AtCmdFwd...
,E/SQLiteLog( 1670): (10) POSIX Error : 11 SQLite Error : 3850
,E/SMD     (  277): DCD ON
,W/Atfwd_Sendcmd(  326): AtCmdFwd service not published, waiting... retryCnt : 5
,D/BatteryService(  890): level:100, scale:100, status:5, health:2, present:true, voltage: 4383, temperature: 287, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  890): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  890): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  890):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  890): Plugged
,I/MotionRecognitionService(  890): setPowerConnected  = true
,D/BatteryService(  890): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1169): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1169): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1169):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3256): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3256): Disconnected process message: 10
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  277): DCD ON
,W/ContextImpl(  890): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  277): DCD ON
,E/Watchdog(  890): !@Sync 6
,D/SSRM:m  (  890): SIOP:: AP = 300, PST = 335, CUR = 300
,E/SMD     (  277): DCD ON
,E/SMD     (  277): DCD ON,
,V/AlarmManager(  890): waitForAlarm result :8
,D/BatteryService(  890): level:100, scale:100, status:5, health:2, present:true, voltage: 4382, temperature: 287, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  890): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  890): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  890):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  890): Plugged
,I/MotionRecognitionService(  890): setPowerConnected  = true
,D/BatteryService(  890): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1169): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1169): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1169):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3256): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3256): Disconnected process message: 10
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  277): DCD ON
,E/SMD     (  277): DCD ON
,D/SSRM:m  (  890): SIOP:: AP = 300, PST = 324, CUR = 300
,E/SMD     (  277): DCD ON
,I/PowerManagerService(  890): [PWL] Off : 75s ago
,E/SMD     (  277): DCD ON
,V/AlarmManager(  890): waitForAlarm result :4
,D/KeyguardUpdateMonitor( 1169): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1169): handleTimeUpdate
,D/KeyguardEffectViewController( 1169): onReceive action : android.intent.action.TIME_TICK
,I/KeyguardEffectViewController( 1169): *** don't update sliding image ***
,D/BatteryService(  890): level:100, scale:100, status:5, health:2, present:true, voltage: 4386, temperature: 287, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  890): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
D/BatteryService(  890): stay LED for fully charged
,D/BatteryService(  890): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1169): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1169): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1169):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/MotionRecognitionService(  890):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  890): Plugged
I/MotionRecognitionService(  890): setPowerConnected  = true
,V/HeadsetService( 3256): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3256): Disconnected process message: 10
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/DateView( 1169): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1169): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/ConnectivityService(  890): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,W/ContextImpl(  890): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/Atfwd_Sendcmd(  326): AtCmdFwd service not ready - Exhausted retry attempts - :6
I/Atfwd_Daemon(  326): result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,E/SMD     (  277): DCD ON
,D/SSRM:m  (  890): SIOP:: AP = 300, PST = 316, CUR = 300
,E/SMD     (  277): DCD ON
,E/SMD     (  277): DCD ON
,D/BatteryService(  890): level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 287, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  890): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  890): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  890):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  890): Plugged
,I/MotionRecognitionService(  890): setPowerConnected  = true
,D/BatteryService(  890): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1169): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1169): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1169):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3256): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3256): Disconnected process message: 10
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/ServiceManager(  326): Waiting for service AtCmdFwd...
,E/SMD     (  277): DCD ON
,E/Watchdog(  890): !@Sync 7
,I/ServiceManager(  326): Waiting for service AtCmdFwd...
,I/ServiceManager(  326): Waiting for service AtCmdFwd...
,I/ServiceManager(  326): Waiting for service AtCmdFwd...
,D/SSRM:m  (  890): SIOP:: AP = 300, PST = 311, CUR = 300
,E/SMD     (  277): DCD ON
,I/ServiceManager(  326): Waiting for service AtCmdFwd...
,W/Atfwd_Sendcmd(  326): AtCmdFwd service not published, waiting... retryCnt : 1
,E/SMD     (  277): DCD ON
,W/ContextImpl(  890): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  277): DCD ON
,I/ServiceManager(  326): Waiting for service AtCmdFwd...
,I/ServiceManager(  326): Waiting for service AtCmdFwd...
,I/ServiceManager(  326): Waiting for service AtCmdFwd...
,E/SMD     (  277): DCD ON
,I/ServiceManager(  326): Waiting for service AtCmdFwd...
,D/SSRM:m  (  890): SIOP:: AP = 290, PST = 307, CUR = 300
,I/ServiceManager(  326): Waiting for service AtCmdFwd...
,W/Atfwd_Sendcmd(  326): AtCmdFwd service not published, waiting... retryCnt : 2
,E/SMD     (  277): DCD ON
,I/PowerManagerService(  890): [PWL] Off : 105s ago
,E/SMD     (  277): DCD ON
,V/AlarmManager(  890): waitForAlarm result :4
,D/ConnectivityService(  890): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/BatteryService(  890): level:100, scale:100, status:5, health:2, present:true, voltage: 4383, temperature: 287, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  890): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
D/BatteryService(  890): stay LED for fully charged
,D/BatteryService(  890): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  890):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  890): Plugged
I/MotionRecognitionService(  890): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1169): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1169): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1169):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3256): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3256): Disconnected process message: 10
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/ConnectivityService(  890): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/BooksSync( 7396): Starting books sync, d
,D/ConnectivityService(  890): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,V/GLSActivity( 1670): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1670): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
,I/GLSUser ( 1670): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1670): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1670): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1670): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/BitmapFactory( 1670): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  890): uri = 14 selection = getSealedState
D/SecContentProvider2(  890): mCursor = null
,D/SecContentProvider2(  890): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  890): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0,
V/ApplicationPolicy(  890): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,W/GLSActivity( 1670): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1670): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1670): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1670): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1670): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1670): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1670): 	at android.os.Binder.execTransact(Binder.java:446)
,E/BooksAccountManager( 7396): Authentication error
E/BooksAccountManager( 7396): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 7396): android.accounts.AccountManager.convertErrorToException(AccountManager.java:1893)
E/HttpHelper( 7396): null auth token
,I/qtaguid ( 7396): Tagging socket 34 with tag 10000000000{256,0} uid -1, pid: 7396, getuid(): 10082
,D/StatusBar( 1169): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,I/PhoneStatusBar( 1169): Icon Only
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1169): value : false
D/PanelView( 1169): There is/are notification(s) 
D/PanelView( 1169): There is/are notification(s) 
,I/qtaguid ( 7396): Untagging socket 34
,W/ApiaryClient( 7396): Error response from books API: {
W/ApiaryClient( 7396):  "error": {
W/ApiaryClient( 7396):   "errors": [
W/ApiaryClient( 7396):    {
W/ApiaryClient( 7396):     "domain": "global",
W/ApiaryClient( 7396):     "reason": "required",
W/ApiaryClient( 7396):     "message": "Login Required",
W/ApiaryClient( 7396):     "locationType": "header",
W/ApiaryClient( 7396):     "location": "Authorization"
W/ApiaryClient( 7396):    }
W/ApiaryClient( 7396):   ],
W/ApiaryClient( 7396):   "code": 401,
W/ApiaryClient( 7396):   "message": "Login Required"
W/ApiaryClient( 7396):  }
W/ApiaryClient( 7396): }
,W/ApiaryClient( 7396): errCount = 1: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 7396): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3DS0HXd4TFLU4&nonce=1804332134571485207&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 7396): Headers suppressed
,D/ConnectivityService(  890): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,V/GLSActivity( 1670): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1670): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
,I/GLSUser ( 1670): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1670): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1670): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1670): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/BitmapFactory( 1670): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  890): uri = 14 selection = getSealedState
,D/SecContentProvider2(  890): mCursor = null
D/SecContentProvider2(  890): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  890): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy(  890): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/StatusBar( 1169): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,I/PhoneStatusBar( 1169): Icon Only
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
D/PanelView( 1169): There is/are notification(s) 
,D/PanelView( 1169): There is/are notification(s) 
,W/GLSActivity( 1670): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1670): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1670): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1670): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1670): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1670): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1670): 	at android.os.Binder.execTransact(Binder.java:446)
,E/BooksAccountManager( 7396): Authentication error
E/BooksAccountManager( 7396): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 7396): android.accounts.AccountManager.convertErrorToException(AccountManager.java:1893)
,E/HttpHelper( 7396): null auth token
,I/qtaguid ( 7396): Tagging socket 34 with tag 10000000000{256,0} uid -1, pid: 7396, getuid(): 10082
,I/qtaguid ( 7396): Untagging socket 34
,W/ApiaryClient( 7396): Error response from books API: {
W/ApiaryClient( 7396):  "error": {
W/ApiaryClient( 7396):   "errors": [
W/ApiaryClient( 7396):    {
W/ApiaryClient( 7396):     "domain": "global",
W/ApiaryClient( 7396):     "reason": "required",
W/ApiaryClient( 7396):     "message": "Login Required",
W/ApiaryClient( 7396):     "locationType": "header",
W/ApiaryClient( 7396):     "location": "Authorization"
W/ApiaryClient( 7396):    }
W/ApiaryClient( 7396):   ],
W/ApiaryClient( 7396):   "code": 401,
W/ApiaryClient( 7396):   "message": "Login Required"
W/ApiaryClient( 7396):  }
W/ApiaryClient( 7396): }
,W/ApiaryClient( 7396): errCount = 2: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 7396): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3DS0HXd4TFLU4&nonce=1804332134571485207&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 7396): Headers suppressed
,D/ConnectivityService(  890): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/SMD     (  277): DCD ON
,V/GLSActivity( 1670): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1670): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
,I/GLSUser ( 1670): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1670): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1670): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1670): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/BitmapFactory( 1670): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  890): uri = 14 selection = getSealedState
,D/SecContentProvider2(  890): mCursor = null
D/SecContentProvider2(  890): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  890): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy(  890): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/StatusBar( 1169): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,I/PhoneStatusBar( 1169): Icon Only
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
D/PanelView( 1169): There is/are notification(s) 
,D/PanelView( 1169): There is/are notification(s) 
,W/GLSActivity( 1670): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1670): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1670): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1670): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1670): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1670): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1670): 	at android.os.Binder.execTransact(Binder.java:446)
,E/BooksAccountManager( 7396): Authentication error
E/BooksAccountManager( 7396): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 7396): android.accounts.AccountManager.convertErrorToException(AccountManager.java:1893)
,E/HttpHelper( 7396): null auth token
,I/qtaguid ( 7396): Tagging socket 34 with tag 10000000000{256,0} uid -1, pid: 7396, getuid(): 10082
,I/qtaguid ( 7396): Untagging socket 34
,W/ApiaryClient( 7396): Error response from books API: {
W/ApiaryClient( 7396):  "error": {
W/ApiaryClient( 7396):   "errors": [
W/ApiaryClient( 7396):    {
W/ApiaryClient( 7396):     "domain": "global",
W/ApiaryClient( 7396):     "reason": "required",
W/ApiaryClient( 7396):     "message": "Login Required",
W/ApiaryClient( 7396):     "locationType": "header",
W/ApiaryClient( 7396):     "location": "Authorization"
W/ApiaryClient( 7396):    }
W/ApiaryClient( 7396):   ],
W/ApiaryClient( 7396):   "code": 401,
W/ApiaryClient( 7396):   "message": "Login Required"
W/ApiaryClient( 7396):  }
W/ApiaryClient( 7396): }
,W/ApiaryClient( 7396): errCount = 3: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 7396): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3DS0HXd4TFLU4&nonce=1804332134571485207&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 7396): Headers suppressed
,D/ConnectivityService(  890): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/BooksSync( 7396): Soft error
E/BooksSync( 7396): com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
E/BooksSync( 7396): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3DS0HXd4TFLU4&nonce=1804332134571485207&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
E/BooksSync( 7396): Headers suppressed
E/BooksSync( 7396): 
E/BooksSync( 7396): com.google.android.apps.books.net.HttpHelper.wrapExceptionBasedOnStatus(HttpHelper.java:212)
,E/BooksSync( 7396): Sync error
E/BooksSync( 7396): com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
E/BooksSync( 7396): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3DS0HXd4TFLU4&nonce=1804332134571485207&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
E/BooksSync( 7396): Headers suppressed
E/BooksSync( 7396): 
E/BooksSync( 7396): com.google.android.apps.books.net.HttpHelper.wrapExceptionBasedOnStatus(HttpHelper.java:212)
,I/BooksSync( 7396): Finished books sync
,D/ConnectivityService(  890): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SyncManager(  890): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 216540, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,D/ConnectivityService(  890): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SecContentProvider2(  890): uri = 11 selection = getMyKnoxAdmin
,D/SecContentProvider2(  890): mCursor = null
,D/ConnectivityService(  890): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SSRM:m  (  890): SIOP:: AP = 290, PST = 303, CUR = 300
,E/SMD     (  277): DCD ON
,I/ServiceManager(  326): Waiting for service AtCmdFwd...
,I/ServiceManager(  326): Waiting for service AtCmdFwd...
,I/ServiceManager(  326): Waiting for service AtCmdFwd...
,E/SMD     (  277): DCD ON
,I/ServiceManager(  326): Waiting for service AtCmdFwd...
,I/ServiceManager(  326): Waiting for service AtCmdFwd...
,D/BatteryService(  890): level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 287, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  890): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  890): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  890):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  890): Plugged
,I/MotionRecognitionService(  890): setPowerConnected  = true
,D/BatteryService(  890): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1169): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1169): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1169):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3256): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3256): Disconnected process message: 10
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,W/ContextImpl(  890): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,W/Atfwd_Sendcmd(  326): AtCmdFwd service not published, waiting... retryCnt : 3
,E/SMD     (  277): DCD ON
,E/Watchdog(  890): !@Sync 8
,E/SMD     (  277): DCD ON
,D/SSRM:m  (  890): SIOP:: AP = 290, PST = 300, CUR = 300
,E/SMD     (  277): DCD ON
,V/AlarmManager(  890): waitForAlarm result :8
,D/BatteryService(  890): level:100, scale:100, status:5, health:2, present:true, voltage: 4383, temperature: 287, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  890): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  890): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  890):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  890): Plugged
,I/MotionRecognitionService(  890): setPowerConnected  = true
,D/BatteryService(  890): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1169): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1169): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1169):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3256): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3256): Disconnected process message: 10
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  277): DCD ON
,E/SMD     (  277): DCD ON
,D/SSRM:m  (  890): SIOP:: AP = 290, PST = 298, CUR = 300
,I/ServiceManager(  326): Waiting for service AtCmdFwd...
,E/SMD     (  277): DCD ON
,I/ServiceManager(  326): Waiting for service AtCmdFwd...
,I/ServiceManager(  326): Waiting for service AtCmdFwd...
,I/ServiceManager(  326): Waiting for service AtCmdFwd...
,E/SMD     (  277): DCD ON
,I/ServiceManager(  326): Waiting for service AtCmdFwd...
,V/AlarmManager(  890): waitForAlarm result :4
,D/KeyguardUpdateMonitor( 1169): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1169): handleTimeUpdate
,D/KeyguardEffectViewController( 1169): onReceive action : android.intent.action.TIME_TICK
,I/KeyguardEffectViewController( 1169): *** don't update sliding image ***
,D/BatteryService(  890): level:100, scale:100, status:5, health:2, present:true, voltage: 4383, temperature: 286, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  890): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  890): stay LED for fully charged
D/BatteryService(  890): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  890):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  890): Plugged
I/MotionRecognitionService(  890): setPowerConnected  = true
,V/HeadsetService( 3256): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3256): Disconnected process message: 10
,D/DateView( 1169): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/KeyguardUpdateMonitor( 1169): received broadcast android.intent.action.BATTERY_CHANGED
,D/STATUSBAR-PhoneStatusBar( 1169):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/DateView( 1169): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/KeyguardUpdateMonitor( 1169): handleBatteryUpdate
,W/ContextImpl(  890): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/ConnectivityService(  890): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  890): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/GLSUser ( 1670): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
I/GLSUser ( 1670): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1670): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1670): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1670): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/BitmapFactory( 1670): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  890): uri = 14 selection = getSealedState
,D/SecContentProvider2(  890): mCursor = null
,D/SecContentProvider2(  890): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  890): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy(  890): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/StatusBar( 1169): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,E/HttpOperation( 6526): [kfu{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
E/HttpOperation( 6526): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 6526): 	at kfv.a(PG:65)
E/HttpOperation( 6526): 	at kff.u(PG:385)
E/HttpOperation( 6526): 	at kfb.a(PG:29)
E/HttpOperation( 6526): 	at kff.l(PG:132)
E/HttpOperation( 6526): 	at dsf.a(PG:807)
E/HttpOperation( 6526): 	at fhk.a(PG:1126)
E/HttpOperation( 6526): 	at fhk.a(PG:908)
E/HttpOperation( 6526): 	at fhk.onPerformSync(PG:636)
E/HttpOperation( 6526): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/HttpOperation( 6526): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/HttpOperation( 6526): 	at ihi.a(PG:22)
E/HttpOperation( 6526): 	at kft.a(PG:91)
E/HttpOperation( 6526): 	at kfv.a(PG:62)
E/HttpOperation( 6526): 	... 8 more
E/HttpOperation( 6526): Caused by: gdi: User intervention required. Notification has been pushed.
E/HttpOperation( 6526): 	at gde.c(Unknown Source)
E/HttpOperation( 6526): 	at gde.b(Unknown Source)
E/HttpOperation( 6526): 	at ihi.a(PG:19)
E/HttpOperation( 6526): 	... 10 more
,I/PhoneStatusBar( 1169): Icon Only
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
D/PanelView( 1169): There is/are notification(s) 
D/PanelView( 1169): There is/are notification(s) 
,I/GLSUser ( 1670): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,I/GLSUser ( 1670): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1670): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1670): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1670): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/Atfwd_Sendcmd(  326): AtCmdFwd service not published, waiting... retryCnt : 4
,V/BitmapFactory( 1670): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  890): uri = 14 selection = getSealedState
D/SecContentProvider2(  890): mCursor = null
,D/SecContentProvider2(  890): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  890): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy(  890): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/StatusBar( 1169): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,E/HttpOperation( 6526): [getmobileexperiments] Unexpected exception
E/HttpOperation( 6526): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 6526): 	at kfv.a(PG:65)
E/HttpOperation( 6526): 	at kff.u(PG:385)
E/HttpOperation( 6526): 	at kfb.a(PG:29)
E/HttpOperation( 6526): 	at kff.l(PG:132)
E/HttpOperation( 6526): 	at ieo.a(PG:43)
E/HttpOperation( 6526): 	at iep.a(PG:93)
E/HttpOperation( 6526): 	at fhn.a(PG:59)
E/HttpOperation( 6526): 	at lex.a(PG:85)
E/HttpOperation( 6526): 	at lex.b(PG:132)
E/HttpOperation( 6526): 	at fhk.a(PG:1146)
E/HttpOperation( 6526): 	at fhk.a(PG:908)
E/HttpOperation( 6526): 	at fhk.onPerformSync(PG:636)
E/HttpOperation( 6526): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/HttpOperation( 6526): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/HttpOperation( 6526): 	at ihi.a(PG:22)
E/HttpOperation( 6526): 	at kft.a(PG:91)
E/HttpOperation( 6526): 	at kfv.a(PG:62)
E/HttpOperation( 6526): 	... 12 more
E/HttpOperation( 6526): Caused by: gdi: User intervention required. Notification has been pushed.
E/HttpOperation( 6526): 	at gde.c(Unknown Source)
E/HttpOperation( 6526): 	at gde.b(Unknown Source)
E/HttpOperation( 6526): 	at ihi.a(PG:19)
E/HttpOperation( 6526): 	... 14 more
,E/ExperimentLoader( 6526): [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 6526): java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 6526): 	at kfv.a(PG:65)
E/ExperimentLoader( 6526): 	at kff.u(PG:385)
E/ExperimentLoader( 6526): 	at kfb.a(PG:29)
E/ExperimentLoader( 6526): 	at kff.l(PG:132)
E/ExperimentLoader( 6526): 	at ieo.a(PG:43)
E/ExperimentLoader( 6526): 	at iep.a(PG:93)
E/ExperimentLoader( 6526): 	at fhn.a(PG:59)
E/ExperimentLoader( 6526): 	at lex.a(PG:85)
E/ExperimentLoader( 6526): 	at lex.b(PG:132)
E/ExperimentLoader( 6526): 	at fhk.a(PG:1146)
E/ExperimentLoader( 6526): 	at fhk.a(PG:908)
E/ExperimentLoader( 6526): 	at fhk.onPerformSync(PG:636)
E/ExperimentLoader( 6526): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/ExperimentLoader( 6526): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/ExperimentLoader( 6526): 	at ihi.a(PG:22)
E/ExperimentLoader( 6526): 	at kft.a(PG:91)
E/ExperimentLoader( 6526): 	at kfv.a(PG:62)
E/ExperimentLoader( 6526): 	... 12 more
E/ExperimentLoader( 6526): Caused by: gdi: User intervention required. Notification has been pushed.
E/ExperimentLoader( 6526): 	at gde.c(Unknown Source)
E/ExperimentLoader( 6526): 	at gde.b(Unknown Source)
E/ExperimentLoader( 6526): 	at ihi.a(PG:19)
E/ExperimentLoader( 6526): 	... 14 more
I/PhoneStatusBar( 1169): Icon Only
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
D/PanelView( 1169): There is/are notification(s) 
D/PanelView( 1169): There is/are notification(s) 
E/SQLiteLog( 1670): (10) POSIX Error : 11 SQLite Error : 3850
,I/art     ( 1670): Explicit concurrent mark sweep GC freed 51558(3MB) AllocSpace objects, 68(4MB) LOS objects, 40% free, 18MB/30MB, paused 850us total 49.557ms
,I/GLSUser ( 1670): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,I/GLSUser ( 1670): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1670): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1670): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1670): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ResourcesManager( 1670): creating new AssetManager and set to /system/app/PlusOne/PlusOne.apk
,V/BitmapFactory( 1670): DecodeImagePath(decodeResourceStream3) : res/mipmap-xxhdpi-v4/quantum_logo_google_plus_color_44in48.png
,V/BitmapFactory( 1670): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  890): uri = 14 selection = getSealedState
D/SecContentProvider2(  890): mCursor = null
D/SecContentProvider2(  890): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  890): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
V/ApplicationPolicy(  890): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,E/HttpOperation( 6526): [getaccountstatus] Unexpected exception
E/HttpOperation( 6526): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 6526): 	at kfv.a(PG:65)
E/HttpOperation( 6526): 	at kff.u(PG:385)
E/HttpOperation( 6526): 	at kfb.a(PG:29)
E/HttpOperation( 6526): 	at ixd.a(PG:248)
E/HttpOperation( 6526): 	at ixd.b(PG:206)
E/HttpOperation( 6526): 	at ixd.a(PG:175)
E/HttpOperation( 6526): 	at fig.a(PG:78)
E/HttpOperation( 6526): 	at lex.a(PG:85)
E/HttpOperation( 6526): 	at lex.b(PG:132)
E/HttpOperation( 6526): 	at fhk.a(PG:1146)
E/HttpOperation( 6526): 	at fhk.a(PG:908)
E/HttpOperation( 6526): 	at fhk.onPerformSync(PG:636)
E/HttpOperation( 6526): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/HttpOperation( 6526): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/HttpOperation( 6526): 	at ihi.a(PG:22)
E/HttpOperation( 6526): 	at kft.a(PG:91)
E/HttpOperation( 6526): 	at kfv.a(PG:62)
E/HttpOperation( 6526): 	... 12 more
E/HttpOperation( 6526): Caused by: gdi: User intervention required. Notification has been pushed.
E/HttpOperation( 6526): 	at gde.c(Unknown Source)
E/HttpOperation( 6526): 	at gde.b(Unknown Source)
E/HttpOperation( 6526): 	at ihi.a(PG:19)
E/HttpOperation( 6526): 	... 14 more
E/EsSyncAdapterService( 6526): Sync failure
E/EsSyncAdapterService( 6526): java.io.IOException: Rpc failed
E/EsSyncAdapterService( 6526): 	at ixd.a(PG:348)
E/EsSyncAdapterService( 6526): 	at ixd.a(PG:248)
E/EsSyncAdapterService( 6526): 	at ixd.b(PG:206)
E/EsSyncAdapterService( 6526): 	at ixd.a(PG:175)
E/EsSyncAdapterService( 6526): 	at fig.a(PG:78)
E/EsSyncAdapterService( 6526): 	at lex.a(PG:85)
E/EsSyncAdapterService( 6526): 	at lex.b(PG:132)
E/EsSyncAdapterService( 6526): 	at fhk.a(PG:1146)
E/EsSyncAdapterService( 6526): 	at fhk.a(PG:908)
E/EsSyncAdapterService( 6526): 	at fhk.onPerformSync(PG:636)
E/EsSyncAdapterService( 6526): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/EsSyncAdapterService( 6526): Caused by: java.io.IOException: Cannot obtain authentication token
E/EsSyncAdapterService( 6526): 	at kfv.a(PG:65)
E/EsSyncAdapterService( 6526): 	at kff.u(PG:385)
E/EsSyncAdapterService( 6526): 	at kfb.a(PG:29)
E/EsSyncAdapterService( 6526): 	... 10 more
E/EsSyncAdapterService( 6526): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/EsSyncAdapterService( 6526): 	at ihi.a(PG:22)
E/EsSyncAdapterService( 6526): 	at kft.a(PG:91)
E/EsSyncAdapterService( 6526): 	at kfv.a(PG:62)
E/EsSyncAdapterService( 6526): 	... 12 more
E/EsSyncAdapterService( 6526): Caused by: gdi: User intervention required. Notification has been pushed.
E/EsSyncAdapterService( 6526): 	at gde.c(Unknown Source)
E/EsSyncAdapterService( 6526): 	at gde.b(Unknown Source)
E/EsSyncAdapterService( 6526): 	at ihi.a(PG:19)
E/EsSyncAdapterService( 6526): 	... 14 more
,D/ConnectivityService(  890): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/StatusBar( 1169): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
I/PhoneStatusBar( 1169): Icon Only
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
D/PanelView( 1169): There is/are notification(s) 
D/PanelView( 1169): There is/are notification(s) 
D/SyncManager(  890): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, PERIODIC, currentRunTime 250102, reason: Periodic, SyncResult: stats [ numIoExceptions: 2]
D/ConnectivityService(  890): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ResourcesManager( 2861): creating new AssetManager and set to /system/app/ChatON_MARKET/ChatON_MARKET.apk
,D/ConnectivityService(  890): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ResourcesManager( 2861): creating new AssetManager and set to /system/app/PlusOne/PlusOne.apk
,D/SecContentProvider2(  890): uri = 11 selection = getMyKnoxAdmin
,D/SecContentProvider2(  890): mCursor = null
,E/SQLiteLog( 1670): (10) POSIX Error : 11 SQLite Error : 3850
,E/SMD     (  277): DCD ON
,I/PowerManagerService(  890): [PWL] Off : 140s ago
,D/SSRM:m  (  890): SIOP:: AP = 290, PST = 296, CUR = 300
,E/SMD     (  277): DCD ON
,E/SMD     (  277): DCD ON
,E/SMD     (  277): DCD ON
,E/Watchdog(  890): !@Sync 9
,E/SMD     (  277): DCD ON
,D/SSRM:m  (  890): SIOP:: AP = 290, PST = 294, CUR = 300
,E/SMD     (  277): DCD ON
,W/ContextImpl(  890): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/BatteryService(  890): level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 286, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  890): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  890): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  890):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  890): Plugged
,I/MotionRecognitionService(  890): setPowerConnected  = true
,D/BatteryService(  890): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1169): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1169): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1169):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3256): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3256): Disconnected process message: 10
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  277): DCD ON
,I/ServiceManager(  326): Waiting for service AtCmdFwd...
,I/ServiceManager(  326): Waiting for service AtCmdFwd...
,I/ServiceManager(  326): Waiting for service AtCmdFwd...
,E/SMD     (  277): DCD ON
,I/ServiceManager(  326): Waiting for service AtCmdFwd...
,D/SSRM:m  (  890): SIOP:: AP = 290, PST = 293, CUR = 300
,I/ServiceManager(  326): Waiting for service AtCmdFwd...
,W/Atfwd_Sendcmd(  326): AtCmdFwd service not published, waiting... retryCnt : 5
,E/SMD     (  277): DCD ON
,E/SMD     (  277): DCD ON
,V/AlarmManager(  890): waitForAlarm result :4
,D/ConnectivityService(  890): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/SMD     (  277): DCD ON
,D/SSRM:m  (  890): SIOP:: AP = 290, PST = 292, CUR = 300
,E/SMD     (  277): DCD ON
,E/SMD     (  277): DCD ON
,D/TimaService(  890): TIMA: TimaService scheduler is intialized. 
,D/TimaService(  890): TimaServiceHandler.handleMessage what =1
,D/TimaService(  890): TIMA: checkEvent, operation: 50000 subject: 10000
,I/TLC_TIMA_PKM_initialize(  890): initializing...
,I/TLC_TIMA_PKM_initialize(  890): root = /firmware/image, root_strlen = 15
,I/TLC_TIMA_PKM_initialize(  890): process = tima_pkm, process_strlen = 8
,I/TZ: qc_tlc_communication(  890): root = /firmware/image, root_len = 15
,I/TZ: qc_tlc_communication(  890): process = tima_pkm, process_strlen = 8
,I/TZ: qc_tlc_communication(  890): aligned max_sendmsg_size = 262208 = 0x40040
,I/TZ: qc_tlc_communication(  890): aligned max_recvmsg_size = 262208 = 0x40040
,I/TZ: qc_tlc_communication(  890): max_message_size = 524416 = 0x80080
,D/QSEECOMAPI: (  890): QSEECom_get_handle sb_length = 0x80080
,D/QSEECOMAPI: (  890): App is not loaded in QSEE
,D/QSEECOMAPI: (  890): Loaded image: APP id = 2
,I/TZ: qc_tlc_communication(  890): TIMA: path = /firmware/image, fname = tima_pkm, tzapp is loaded
,I/TLC_TIMA_PKM_initialize(  890): Trustlet response is completed
,W/ContextImpl(  890): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/BatteryService(  890): level:100, scale:100, status:5, health:2, present:true, voltage: 4386, temperature: 286, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  890): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  890): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  890):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  890): Plugged
,I/MotionRecognitionService(  890): setPowerConnected  = true
,D/BatteryService(  890): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1169): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1169): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1169):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3256): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3256): Disconnected process message: 10
,E/SMD     (  277): DCD ON
,E/Watchdog(  890): !@Sync 10
,I/TLC_TIMA_PKM_measure_kernel(  890): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel(  890): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService(  890): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService(  890): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,I/PowerManagerService(  890): [PWL] Off : 180s ago
,E/SMD     (  277): DCD ON
,D/SSRM:m  (  890): SIOP:: AP = 290, PST = 291, CUR = 300
,E/SMD     (  277): DCD ON
,V/AlarmManager(  890): waitForAlarm result :8
,E/SMD     (  277): DCD ON
,I/Atfwd_Sendcmd(  326): AtCmdFwd service not ready - Exhausted retry attempts - :6
I/Atfwd_Daemon(  326): result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,E/SMD     (  277): DCD ON
,D/SSRM:m  (  890): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  277): DCD ON
,E/SMD     (  277): DCD ON
,W/ContextImpl(  890): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,V/AlarmManager(  890): waitForAlarm result :4
,D/KeyguardUpdateMonitor( 1169): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1169): handleTimeUpdate
,D/KeyguardEffectViewController( 1169): onReceive action : android.intent.action.TIME_TICK
,I/KeyguardEffectViewController( 1169): *** don't update sliding image ***
,D/BatteryService(  890): level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 286, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  890): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
D/BatteryService(  890): stay LED for fully charged
,D/BatteryService(  890): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  890):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  890): Plugged
I/MotionRecognitionService(  890): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1169): received broadcast android.intent.action.BATTERY_CHANGED
,D/STATUSBAR-PhoneStatusBar( 1169):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/KeyguardUpdateMonitor( 1169): handleBatteryUpdate
,V/HeadsetService( 3256): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3256): Disconnected process message: 10
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/DateView( 1169): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1169): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/ConnectivityService(  890): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  890): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/BooksSync( 7396): Starting books sync, d
,D/ConnectivityService(  890): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,V/GLSActivity( 1670): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1670): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
,I/GLSUser ( 1670): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1670): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1670): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1670): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ResourcesManager( 1670): creating new AssetManager and set to /system/app/Books/Books.apk
,V/BitmapFactory( 1670): DecodeImagePath(decodeResourceStream3) : res/mipmap-xxhdpi-v4/ic_launcher_play_books.png
,V/BitmapFactory( 1670): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  890): uri = 14 selection = getSealedState
D/SecContentProvider2(  890): mCursor = null
,D/SecContentProvider2(  890): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  890): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy(  890): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,W/GLSActivity( 1670): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1670): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1670): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1670): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1670): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1670): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1670): 	at android.os.Binder.execTransact(Binder.java:446)
,E/BooksAccountManager( 7396): Authentication error
E/BooksAccountManager( 7396): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 7396): android.accounts.AccountManager.convertErrorToException(AccountManager.java:1893)
E/HttpHelper( 7396): null auth token
I/qtaguid ( 7396): Tagging socket 34 with tag 10000000000{256,0} uid -1, pid: 7396, getuid(): 10082
,D/StatusBar( 1169): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,I/PhoneStatusBar( 1169): Icon Only
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
D/PanelView( 1169): There is/are notification(s) 
D/PanelView( 1169): There is/are notification(s) 
,I/qtaguid ( 7396): Untagging socket 34
,W/ApiaryClient( 7396): Error response from books API: {
W/ApiaryClient( 7396):  "error": {
W/ApiaryClient( 7396):   "errors": [
W/ApiaryClient( 7396):    {
W/ApiaryClient( 7396):     "domain": "global",
W/ApiaryClient( 7396):     "reason": "required",
W/ApiaryClient( 7396):     "message": "Login Required",
W/ApiaryClient( 7396):     "locationType": "header",
W/ApiaryClient( 7396):     "location": "Authorization"
W/ApiaryClient( 7396):    }
W/ApiaryClient( 7396):   ],
W/ApiaryClient( 7396):   "code": 401,
W/ApiaryClient( 7396):   "message": "Login Required"
W/ApiaryClient( 7396):  }
W/ApiaryClient( 7396): }
,W/ApiaryClient( 7396): errCount = 1: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 7396): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3DS0HXd4TFLU4&nonce=2380225658942655086&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 7396): Headers suppressed
,D/ConnectivityService(  890): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,V/GLSActivity( 1670): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/AlarmManager(  890): waitForAlarm result :4
,E/ActivityManager(  890): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  890): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  890): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  890): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 8606): MountEmulatedStorage()
,E/Zygote  ( 8606): v2
,I/libpersona( 8606): KNOX_SDCARD checking this for 10081
I/libpersona( 8606): KNOX_SDCARD not a persona
,I/ActivityManager(  890): Start proc com.blurb.checkout for broadcast com.blurb.checkout/.RebootReceiver: pid=8606 uid=10081 gids={50081, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/SELinux ( 8606): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 8606): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 8606): [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
,I/GLSUser ( 1670): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
,I/GLSUser ( 1670): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1670): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1670): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1670): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/BitmapFactory( 1670): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  890): uri = 14 selection = getSealedState
,D/SecContentProvider2(  890): mCursor = null
,D/SecContentProvider2(  890): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  890): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy(  890): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/TimaKeyStoreProvider( 8606): TimaSignature is unavailable
,D/ActivityThread( 8606): Added TimaKeyStore provider
,W/GLSActivity( 1670): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1670): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1670): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1670): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1670): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1670): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1670): 	at android.os.Binder.execTransact(Binder.java:446)
,D/StatusBar( 1169): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,E/BooksAccountManager( 7396): Authentication error
E/BooksAccountManager( 7396): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 7396): android.accounts.AccountManager.convertErrorToException(AccountManager.java:1893)
,E/HttpHelper( 7396): null auth token
,I/PhoneStatusBar( 1169): Icon Only
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
I/qtaguid ( 7396): Tagging socket 34 with tag 10000000000{256,0} uid -1, pid: 7396, getuid(): 10082
,D/PanelView( 1169): There is/are notification(s) 
,D/PanelView( 1169): There is/are notification(s) 
,D/ResourcesManager( 8606): creating new AssetManager and set to /system/app/Blurb/Blurb.apk
,I/qtaguid ( 7396): Untagging socket 34
,W/ApiaryClient( 7396): Error response from books API: {
W/ApiaryClient( 7396):  "error": {
W/ApiaryClient( 7396):   "errors": [
W/ApiaryClient( 7396):    {
W/ApiaryClient( 7396):     "domain": "global",
W/ApiaryClient( 7396):     "reason": "required",
W/ApiaryClient( 7396):     "message": "Login Required",
W/ApiaryClient( 7396):     "locationType": "header",
W/ApiaryClient( 7396):     "location": "Authorization"
W/ApiaryClient( 7396):    }
W/ApiaryClient( 7396):   ],
W/ApiaryClient( 7396):   "code": 401,
W/ApiaryClient( 7396):   "message": "Login Required"
W/ApiaryClient( 7396):  }
W/ApiaryClient( 7396): }
W/ApiaryClient( 7396): errCount = 2: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 7396): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3DS0HXd4TFLU4&nonce=2380225658942655086&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 7396): Headers suppressed
,D/ConnectivityService(  890): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/SMD     (  277): DCD ON
,V/GLSActivity( 1670): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1670): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
,I/GLSUser ( 1670): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1670): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1670): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1670): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/BitmapFactory( 1670): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  890): uri = 14 selection = getSealedState
,D/SecContentProvider2(  890): mCursor = null
D/SecContentProvider2(  890): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  890): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy(  890): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/StatusBar( 1169): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,I/PhoneStatusBar( 1169): Icon Only
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
D/PanelView( 1169): There is/are notification(s) 
,D/PanelView( 1169): There is/are notification(s) 
,W/GLSActivity( 1670): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1670): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1670): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1670): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1670): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1670): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1670): 	at android.os.Binder.execTransact(Binder.java:446)
,E/BooksAccountManager( 7396): Authentication error
E/BooksAccountManager( 7396): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 7396): android.accounts.AccountManager.convertErrorToException(AccountManager.java:1893)
,E/HttpHelper( 7396): null auth token
,I/qtaguid ( 7396): Tagging socket 34 with tag 10000000000{256,0} uid -1, pid: 7396, getuid(): 10082
,I/qtaguid ( 7396): Untagging socket 34
,W/ApiaryClient( 7396): Error response from books API: {
W/ApiaryClient( 7396):  "error": {
W/ApiaryClient( 7396):   "errors": [
W/ApiaryClient( 7396):    {
W/ApiaryClient( 7396):     "domain": "global",
W/ApiaryClient( 7396):     "reason": "required",
W/ApiaryClient( 7396):     "message": "Login Required",
W/ApiaryClient( 7396):     "locationType": "header",
W/ApiaryClient( 7396):     "location": "Authorization"
W/ApiaryClient( 7396):    }
W/ApiaryClient( 7396):   ],
W/ApiaryClient( 7396):   "code": 401,
W/ApiaryClient( 7396):   "message": "Login Required"
W/ApiaryClient( 7396):  }
W/ApiaryClient( 7396): }
,W/ApiaryClient( 7396): errCount = 3: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 7396): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3DS0HXd4TFLU4&nonce=2380225658942655086&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 7396): Headers suppressed
,D/ConnectivityService(  890): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/BooksSync( 7396): Soft error
E/BooksSync( 7396): com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
E/BooksSync( 7396): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3DS0HXd4TFLU4&nonce=2380225658942655086&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
E/BooksSync( 7396): Headers suppressed
E/BooksSync( 7396): 
E/BooksSync( 7396): com.google.android.apps.books.net.HttpHelper.wrapExceptionBasedOnStatus(HttpHelper.java:212)
,E/BooksSync( 7396): Sync error
E/BooksSync( 7396): com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
E/BooksSync( 7396): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3DS0HXd4TFLU4&nonce=2380225658942655086&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
E/BooksSync( 7396): Headers suppressed
E/BooksSync( 7396): 
E/BooksSync( 7396): com.google.android.apps.books.net.HttpHelper.wrapExceptionBasedOnStatus(HttpHelper.java:212)
,I/BooksSync( 7396): Finished books sync
,D/ConnectivityService(  890): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/ActivityManager(  890): Killing 5657:com.android.mms/u0a50 (adj 15): bgCount ##41
,D/SyncManager(  890): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 307958, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,D/ConnectivityService(  890): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/CountryDetector(  890): No listener is left
,D/ConnectivityService(  890): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,W/libprocessgroup(  890): failed to open /acct/uid_10050/pid_5657/cgroup.procs: No such file or directory
,I/art     (  890): Explicit concurrent mark sweep GC freed 62560(3MB) AllocSpace objects, 62(1772KB) LOS objects, 30% free, 36MB/52MB, paused 1.810ms total 183.045ms
,D/SecContentProvider2(  890): uri = 11 selection = getMyKnoxAdmin
D/SecContentProvider2(  890): mCursor = null
,D/SSRM:m  (  890): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  277): DCD ON
,I/ServiceManager(  326): Waiting for service AtCmdFwd...
,I/jxcore-log( 7474): --= Surplus to requirements =--
I/jxcore-log( 7474): 
,I/jxcore-log( 7474): ****TEST TOOK:  ms ****
I/jxcore-log( 7474): 
I/jxcore-log( 7474): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 7474): 
,D/AndroidRuntime( 8663): 
D/AndroidRuntime( 8663): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
,D/AndroidRuntime( 8663): CheckJNI is OFF
,D/AndroidRuntime( 8663): setted country_code = Germany
,D/AndroidRuntime( 8663): setted countryiso_code = DE
,D/AndroidRuntime( 8663): setted sales_code = DBT
,D/AndroidRuntime( 8663): readGMSProperty: start
D/AndroidRuntime( 8663): readGMSProperty: already setted!!
,D/AndroidRuntime( 8663): readGMSProperty: end
,D/AndroidRuntime( 8663): addProductProperty: start
,E/AffinityControl( 8663): AffinityControl: registerfunction enter
,D/AndroidRuntime( 8663): Calling main entry com.android.commands.pm.Pm
,D/PackageManager(  890): START PACKAGE DELETE: observer{254860923}
D/PackageManager(  890): pkg{<packageName>}
D/PackageManager(  890): user{0}
D/PackageManager(  890): caller{2000}
D/PackageManager(  890): flags{3}
,D/PersonaManagerService(  890): isFromApprovedUnInstaller: uid, userId, appid : 2000 0 2000
,D/PersonaManagerService(  890): isFromApprovedUnInstaller: isApproved : true
,D/PersonaManagerService(  890): isFromApprovedUnInstaller: isApproved before exit: true
D/PackageManager(  890): deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag3
,D/PackageManager(  890): deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag3
,D/PackageManager(  890): [MSG] DELETE_PACKAGE_AS_USER
,D/PackageManagerService(  890): deletePackage- pkg:com.test.thalitest, edmuserId:0
,D/PackageManagerService(  890): deletePackage- pkg:com.test.thalitest, edmuserId:-1
,D/ApplicationPolicy(  890): getApplicationUninstallationEnabled
,D/ApplicationPolicy(  890): getApplicationUninstallationEnabled :  enabled true
,D/PackageManager(  890): !@killApplicatoin: 10200, uninstall pkg
,I/ActivityManager(  890): Force stopping com.test.thalitest appid=10200 user=-1: uninstall pkg
,I/ActivityManager(  890): Killing 7474:com.test.thalitest/u0a200 (adj 0): stop com.test.thalitest
,I/ServiceManager(  326): Waiting for service AtCmdFwd...
,I/ActivityManager(  890):   Force finishing activity ActivityRecord{2f372d19 u0 com.test.thalitest/.MainActivity t17}
,D/FocusedStackFrame(  890): Set to : 0
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
,I/SurfaceFlinger(  249): id=15 Removed com.test.thalitest/com.test.thalitest.MainActivity (5/8)
,I/SurfaceFlinger(  249): id=15 Removed com.test.thalitest/com.test.thalitest.MainActivity (-2/8)
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
,I/ActivityManager(  890): Force stopping com.test.thalitest appid=10200 user=0: pkg removed
,D/ConnectivityService(  890): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/WifiService(  890): Client connection lost with reason: 4
,I/art     ( 4508): Explicit concurrent mark sweep GC freed 5023(278KB) AllocSpace objects, 1(16KB) LOS objects, 40% free, 14MB/24MB, paused 812us total 68.562ms
,I/art     ( 1559): Explicit concurrent mark sweep GC freed 18367(1191KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 16MB/27MB, paused 395us total 45.443ms
,D/ResourcesManager(  890): creating new AssetManager and set to /data/app/com.google.android.gms-1/base.apk
,D/ResourcesManager(  890): creating new AssetManager and set to /system/priv-app/Velvet/Velvet.apk
,D/ResourcesManager(  890): creating new AssetManager and set to /system/priv-app/InputDevices/InputDevices.apk
,E/libprocessgroup(  890): failed to kill 1 processes for processgroup 7474
E/SamsungIME( 1864): mOCRHelper is null
,D/ResourcesManager(  890): creating new AssetManager and set to /system/priv-app/SNS/SNS.apk
,I/InputReader(  890): Reconfiguring input devices.  changes=0x00000010
,W/GeofencerStateMachine( 2097): Ignoring removeGeofence because network location is disabled.
,D/ResourcesManager(  890): creating new AssetManager and set to /system/priv-app/Samsungservice2_xxhdpi/Samsungservice2_xxhdpi.apk
,D/ResourcesManager(  890): creating new AssetManager and set to /system/app/ChatON_MARKET/ChatON_MARKET.apk
,I/KLMS-2.4.503: ( 7699): KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,D/ResourcesManager(  890): creating new AssetManager and set to /system/app/Dropbox/Dropbox.apk
,I/KLMS-2.4.503: ( 7699): MainReciver(): EventNotificationReciver- method called: AppActivityListner onReceive for Intent Action : android.intent.action.PACKAGE_REMOVED , timestamp: 1452774079088
,D/ResourcesManager(  890): creating new AssetManager and set to /system/app/Gmail2/Gmail2.apk
,I/KLMS-2.4.503: ( 7699): MainReciver(): PACKAGE_REMOVED
,D/ResourcesManager(  890): creating new AssetManager and set to /system/app/SBrowser/SBrowser.apk
,I/KLMS-2.4.503: ( 7699): MainReciver(): REPLACING: false | pkgName: com.test.thalitest
,D/ResourcesManager(  890): creating new AssetManager and set to /system/app/SecEmail_K/SecEmail_K.apk
,D/ResourcesManager(  890): creating new AssetManager and set to /system/priv-app/GoogleServicesFramework/GoogleServicesFramework.apk
,D/ResourcesManager(  890): creating new AssetManager and set to /system/priv-app/SHealth3_5/SHealth3_5.apk
,D/ResourcesManager(  890): creating new AssetManager and set to /system/app/SamsungIME/SamsungIME.apk
,D/SecContentProvider2(  890): uri = 11 selection = getMyKnoxAdmin
,D/SecContentProvider2(  890): mCursor = null
,D/ResourcesManager(  890): creating new AssetManager and set to /system/priv-app/SecGallery2014/SecGallery2014.apk
,D/RegisteredServicesCache( 1469): empty dynamic service
,D/ResourcesManager(  890): creating new AssetManager and set to /system/priv-app/sCloudSyncCalendar/sCloudSyncCalendar.apk
,D/ResourcesManager(  890): creating new AssetManager and set to /system/priv-app/sCloudSyncContacts/sCloudSyncContacts.apk
,D/ResourcesManager(  890): creating new AssetManager and set to /system/priv-app/sCloudSyncMemo/sCloudSyncMemo.apk
,D/ResourcesManager(  890): creating new AssetManager and set to /system/priv-app/sCloudSyncSBrowser/sCloudSyncSBrowser.apk
,D/ResourcesManager(  890): creating new AssetManager and set to /system/priv-app/sCloudSyncSNote3/sCloudSyncSNote3.apk
,D/ResourcesManager(  890): creating new AssetManager and set to /system/app/Books/Books.apk
,D/ResourcesManager(  890): creating new AssetManager and set to /system/app/Chrome/Chrome.apk
,D/ResourcesManager(  890): creating new AssetManager and set to /system/app/Drive/Drive.apk
,D/ResourcesManager(  890): creating new AssetManager and set to /system/app/EditorsDocs/EditorsDocs.apk
,D/ResourcesManager(  890): creating new AssetManager and set to /system/app/GoogleCalendarSyncAdapter/GoogleCalendarSyncAdapter.apk
,D/ResourcesManager(  890): creating new AssetManager and set to /system/app/GoogleContactsSyncAdapter/GoogleContactsSyncAdapter.apk
,D/ResourcesManager(  890): creating new AssetManager and set to /system/app/Music2/Music2.apk
,D/ResourcesManager(  890): creating new AssetManager and set to /system/app/Newsstand/Newsstand.apk
,D/ResourcesManager(  890): creating new AssetManager and set to /system/app/PlusOne/PlusOne.apk
,E/ActivityManager(  890): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  890): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  890): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  890): checkUser: useridlist=null, currentuser=0
,D/ResourcesManager(  890): creating new AssetManager and set to /system/app/SecExchange/SecExchange.apk
,D/ResourcesManager(  890): creating new AssetManager and set to /system/app/Videos/Videos.apk
,E/Zygote  ( 8693): MountEmulatedStorage()
E/Zygote  ( 8693): v2
I/libpersona( 8693): KNOX_SDCARD checking this for 10104
I/libpersona( 8693): KNOX_SDCARD not a persona
,I/ActivityManager(  890): Start proc com.sec.esdk.elm for broadcast com.sec.esdk.elm/.receiver.MainReceiver: pid=8693 uid=10104 gids={50104, 9997, 3003} abi=armeabi-v7a
,D/ResourcesManager(  890): creating new AssetManager and set to /system/app/talkback/talkback.apk
,D/RCPManagerService(  890): PackageReceiver onReceive()
I/HarmonyEASService(  890): onReceive : android.intent.action.PACKAGE_REMOVED for 0
,D/KnoxMUMContainerPolicy(  890): mPackageReceiver : action - android.intent.action.PACKAGE_REMOVED
,D/BackupManagerService(  890): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
,D/JobSchedulerService(  890): Receieved: android.intent.action.PACKAGE_REMOVED
I/SELinux ( 8693): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
D/EnterpriseDeviceManagerService(  890): Package has changed for user 0
D/EnterpriseDeviceManagerService(  890): Admin package name: com.google.android.gms
,V/EnterpriseBillingPolicy(  890): packageModificationReceiver - onreceive - start - android.intent.action.PACKAGE_REMOVED
V/EnterpriseBillingPolicy(  890): uID is 10200
V/EnterpriseBillingPolicy(  890): Removed Packageuid is0
V/EnterpriseBillingPolicyStorage(  890): getProfileForApplication - enter
V/EnterpriseBillingPolicyStorage(  890): getProfileForApplication - exit null
V/EnterpriseBillingPolicy(  890): packageModificationReceiver - onreceive - personal application - profile null
V/EnterpriseBillingPolicy(  890): packageModificationReceiver - onreceive - might be a vpn vendor package 
V/EnterpriseBillingPolicyStorage(  890): getBillingProfileForVpnEngine - start - com.test.thalitest
,I/SELinux ( 8693): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
V/EnterpriseBillingPolicyStorage(  890): getBillingProfileForVpnEngine - end - null
E/SELinux ( 8693): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
D/ResourcesManager(  890): creating new AssetManager and set to /system/priv-app/SecContacts/SecContacts.apk
D/TaskPersister(  890): removeObsoleteFile: deleting file=17_task.xml
D/TaskPersister(  890): removeObsoleteFile: deleting file=17_task_thumbnail.png
W/Resources(  890): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager(  890): creating new AssetManager and set to /system/priv-app/SecMms_Candy/SecMms_Candy.apk
,W/Resources(  890): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager(  890): creating new AssetManager and set to /system/app/Books/Books.apk
D/TimaKeyStoreProvider( 8693): TimaSignature is unavailable
D/ActivityThread( 8693): Added TimaKeyStore provider
D/ResourcesManager(  890): creating new AssetManager and set to /system/app/EditorsDocs/EditorsDocs.apk
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
I/art     (  890): Explicit concurrent mark sweep GC freed 21598(1631KB) AllocSpace objects, 7(112KB) LOS objects, 30% free, 36MB/52MB, paused 4.683ms total 352.475ms
D/ResourcesManager(  890): creating new AssetManager and set to /system/app/Music2/Music2.apk
D/ResourcesManager(  890): creating new AssetManager and set to /system/app/SecEmail_K/SecEmail_K.apk
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
D/SurfaceWidgetView( 1490): destroyHardwareResources():373658336
V/WindowOrientationListener(  890): mSContextAutoRotationListener.getProposedRotation, mbResultFaceDectection: false
V/WindowOrientationListener(  890): mSContextAutoRotationListener.getProposedRotation, Rotation: -1
V/WindowManager(  890): rotationForOrientationLw(orient=1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false
V/WindowOrientationListener(  890): mSContextAutoRotationListener.getProposedRotation, mbResultFaceDectection: false
V/WindowOrientationListener(  890): mSContextAutoRotationListener.getProposedRotation, Rotation: -1
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
D/Launcher( 1490): onRestart, Launcher: 891420338
D/Launcher( 1490): onStart, Launcher: 891420338
D/Launcher.HomeView( 1490): onStart
D/SurfaceWidgetClient$ISurfaceWidgetStub( 2166): [237392/6] Surface widget visibility changed visibility = true on instance = 1
D/SurfaceWidget.Renderer( 2166): [237392/6] SurfaceWidget drawing first frame
W/Resources(  890): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager(  890): creating new AssetManager and set to /system/app/SecMemoDL/SecMemoDL.apk
D/ResourcesManager( 8693): creating new AssetManager and set to /system/app/ELMAgent/ELMAgent.apk
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
I/SurfaceFlinger(  249): id=18 createSurf (1080x1920),1 flag=4, com.sec.android.app.launcher/com.android.launcher2.Launcher
D/StatusBarManagerService(  890): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
D/StatusBarManagerService(  890): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
W/Resources(  890): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
D/ResourcesManager(  890): creating new AssetManager and set to /system/app/Videos/Videos.apk
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
D/ResourcesManager(  890): creating new AssetManager and set to /system/app/YouTube/YouTube.apk
,D/ResourcesManager(  890): creating new AssetManager and set to /system/priv-app/SFinder/SFinder.apk
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
D/elm:14451( 8693): ELMAbstractReceiver.onReceive() : Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.receiver.MainReceiver (has extras) }
D/InputMethodManagerService(  890): windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
W/Resources(  890): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources(  890): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager(  890): creating new AssetManager and set to /system/app/ChatON_MARKET/ChatON_MARKET.apk
W/InputMethodManagerService(  890): Got RemoteException sending setActive(false) notification to pid 7474 uid 10200
W/ContextImpl(  890): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.android.server.InputMethodManagerService$6.run:2728 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
D/elm:14451( 8693): ELMEngine.ELMEngine( context ).
D/elm:14451( 8693): MDMBridge.setEnterpriseBridge()
W/Resources(  890): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager(  890): creating new AssetManager and set to /system/app/Chrome/Chrome.apk
D/elm:14451( 8693): ELMAbstractReceiver : Receive Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) } END.
D/elm:14451( 8693): ElmAgentService : onCreate()
D/elm:14451( 8693): ElmAgentService : onHandleIntent() Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) }
D/elm:14451( 8693): MainReceiver.listeningToPackageRemoved()
D/elm:14451( 8693): MDMBridge.getInstance()
D/elm:14451( 8693): MDMBridge.getAllLicenseInfoFromSDK()
D/com.sec.android.service.health.upgrade.UninstallReceiver( 8142): onReceive()
I/com.sec.android.service.health.upgrade.UninstallReceiver( 8142): onReceive called  PACKAGE_REMOVED package:com.test.thalitest
D/com.sec.android.service.health.upgrade.UninstallReceiver( 8142): onReceive() : package name is not s health. Return !!!
,D/ResourcesManager(  890): creating new AssetManager and set to /system/app/Drive/Drive.apk
D/elm:14451( 8693): MDMBridge.getAllLicenseInfoFromSDK()
I/PCWCLIENTTRACE_PushUtil( 7615): SPPPushClient is installed : true
I/PCWCLIENTTRACE_PushUtil( 7615): sales region : global
I/PCWCLIENTTRACE_PushUtil( 7615): getPushTypeList : [SPP, GCM]
I/PCWCLIENTTRACE_SYSTEMReceiver( 7615): [onReceive] - android.intent.action.PACKAGE_REMOVED
D/ResourcesManager(  890): creating new AssetManager and set to /system/app/Dropbox/Dropbox.apk
D/elm:14451( 8693): ElmAgentService : onDestroy().
D/ResourcesManager(  890): creating new AssetManager and set to /system/app/InteractiveTutorial/InteractiveTutorial.apk
,W/Resources(  890): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/ResourcesManager(  890): creating new AssetManager and set to /system/app/Newsstand/Newsstand.apk
D/PackageManager(  890): delete codoeFile: 
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1169): value : false
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
D/PackageManager(  890): result of delete: 1{254860923}
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
,E/ActivityManager(  890): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  890): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  890): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  890): checkUser: useridlist=null, currentuser=0
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
,D/ResourcesManager(  890): creating new AssetManager and set to /system/app/PlayGames/PlayGames.apk
,D/ResourcesManager(  890): creating new AssetManager and set to /system/app/SPlanner_OS_UPG/SPlanner_OS_UPG.apk
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
E/Zygote  ( 8716): MountEmulatedStorage()
I/libpersona( 8716): KNOX_SDCARD checking this for 10038
E/Zygote  ( 8716): v2
I/libpersona( 8716): KNOX_SDCARD not a persona
,W/ResourcesManager(  890): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
,W/ResourcesManager(  890): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager(  890): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,I/ActivityManager(  890): Start proc com.sec.spp.push:RemoteNotiProcess for broadcast com.sec.spp.push/.notisvc.registration.PackageRemovedReceiver: pid=8716 uid=10038 gids={50038, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/Timeline(  890): Timeline: Activity_windows_visible id: ActivityRecord{17e74190 u0 com.sec.android.app.launcher/com.android.launcher2.Launcher t15} time:339643
D/AndroidRuntime( 8663): Shutting down VM
,W/Resources(  890): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager(  890): creating new AssetManager and set to /system/app/SmartRemote_KL/SmartRemote_KL.apk
,I/ActivityManager(  890): Killing 7310:com.sec.android.widgetapp.digitalclock/u0a94 (adj 15): bgCount ##41
,D/ResourcesManager(  890): creating new AssetManager and set to /data/app/de.pizza-1/base.apk
,D/ResourcesManager(  890): creating new AssetManager and set to /data/app/de.kaufda.android-1/base.apk
,D/ResourcesManager(  890): creating new AssetManager and set to /system/priv-app/Velvet/Velvet.apk
,D/ResourcesManager(  890): creating new AssetManager and set to /system/priv-app/SamsungMusic_20/SamsungMusic_20.apk
,W/Resources(  890): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources(  890): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/ResourcesManager(  890): creating new AssetManager and set to /system/priv-app/SecGallery2014/SecGallery2014.apk
,W/Resources(  890): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources(  890): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
D/ResourcesManager(  890): creating new AssetManager and set to /system/priv-app/SecMyFiles2014/SecMyFiles2014.apk
,W/Resources(  890): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/ResourcesManager(  890): creating new AssetManager and set to /system/priv-app/SecVideoPlayer/SecVideoPlayer.apk
,W/Resources(  890): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources(  890): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
D/ResourcesManager(  890): creating new AssetManager and set to /system/priv-app/VoiceNote/VoiceNote.apk
,W/Resources(  890): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources(  890): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
D/ResourcesManager(  890): creating new AssetManager and set to /system/app/SBrowser/SBrowser.apk
,I/SELinux ( 8716): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,W/Resources(  890): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
,I/SELinux ( 8716): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 8716): [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
,D/ResourcesManager( 8090): creating new AssetManager and set to /system/priv-app/SecMms_Candy/SecMms_Candy.apk
,W/ResourcesManager( 8090): Asset path '/system/framework/minimode.jar' does not exist or contains no resources.
,W/ResourcesManager( 8090): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,W/ResourcesManager( 8090): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager( 8090): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 8090): Asset path '/system/framework/imsmanager.jar' does not exist or contains no resources.
,D/ResourcesManager( 8090): creating new AssetManager and set to /system/priv-app/SecSettings/SecSettings.apk
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
,D/UsbSettingsManager(  890): clearDefaults: com.test.thalitest
W/ResourcesManager( 8090): Asset path '/system/framework/sec_platform_library.jar' does not exist or contains no resources.
,W/ResourcesManager( 8090): Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
W/ResourcesManager( 8090): Asset path '/system/framework/secvisualeffect.jar' does not exist or contains no resources.
,W/ResourcesManager( 8090): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
,W/ResourcesManager( 8090): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 8090): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 8090): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,I/CrashAnrDetector(  890): onPackageRemoved : com.test.thalitest
,D/ResourcesManager( 8090): creating new AssetManager and set to /system/app/ChatON_MARKET/ChatON_MARKET.apk
,W/ResourcesManager( 8090): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,D/ResourcesManager( 8090): creating new AssetManager and set to /system/app/InteractiveTutorial/InteractiveTutorial.apk
,W/libprocessgroup(  890): failed to open /acct/uid_10094/pid_7310/cgroup.procs: No such file or directory
,D/ResourcesManager( 8090): creating new AssetManager and set to /system/app/SPlanner_OS_UPG/SPlanner_OS_UPG.apk
,D/TimaKeyStoreProvider( 8716): TimaSignature is unavailable
,D/ActivityThread( 8716): Added TimaKeyStore provider
,W/ResourcesManager( 8090): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
,W/ResourcesManager( 8090): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 8090): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,D/ResourcesManager( 8090): creating new AssetManager and set to /system/priv-app/SecContacts/SecContacts.apk
,W/ResourcesManager( 8090): Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
W/ResourcesManager( 8090): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 8090): Asset path '/system/framework/imsmanager.jar' does not exist or contains no resources.
,D/ResourcesManager( 8716): creating new AssetManager and set to /system/priv-app/SPPPushClient_Prod/SPPPushClient_Prod.apk
,D/ResourcesManager( 8090): creating new AssetManager and set to /system/priv-app/SecGallery2014/SecGallery2014.apk
,W/ResourcesManager( 8090): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
,W/ResourcesManager( 8090): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 8090): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager( 8090): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,W/ResourcesManager( 8090): Asset path '/system/framework/secimaging.jar' does not exist or contains no resources.
W/ResourcesManager( 8090): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,W/ResourcesManager( 8090): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
W/ResourcesManager( 8090): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,D/ResourcesManager( 8090): creating new AssetManager and set to /system/priv-app/SecMyFiles2014/SecMyFiles2014.apk
,W/ResourcesManager( 8090): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 8090): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
,E/SPPClientService( 8716): ============PushLog. commonIsShipBuild. stop!
E/SPPClientService( 8716): [PushClientApplication] Push log off : This is Ship build version
,D/SPPClientService( 8716): PushLog.txt file is not deleted.
D/SPPClientService( 8716): PushLog.txt file is not deleted.
D/SPPClientService( 8716): ============PushLog. stop!
,D/ResourcesManager( 8090): creating new AssetManager and set to /system/priv-app/SecVideoPlayer/SecVideoPlayer.apk
,W/ResourcesManager( 8090): Asset path '/system/framework/minimode.jar' does not exist or contains no resources.
W/ResourcesManager( 8090): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 8090): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager( 8090): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 8090): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
,D/ResourcesManager( 8090): creating new AssetManager and set to /system/app/SBrowser/SBrowser.apk
,W/ResourcesManager( 8090): Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
W/ResourcesManager( 8090): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 8090): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,D/ResourcesManager( 8090): creating new AssetManager and set to /system/app/SecEmail_K/SecEmail_K.apk
,W/ResourcesManager( 8090): Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
W/ResourcesManager( 8090): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 8090): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager( 8090): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,D/ResourcesManager( 8090): creating new AssetManager and set to /system/app/SecMemoDL/SecMemoDL.apk
,W/ResourcesManager( 8090): Asset path '/system/framework/secmediarecorder.jar' does not exist or contains no resources.
W/ResourcesManager( 8090): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
,D/ResourcesManager( 8090): creating new AssetManager and set to /system/app/Chrome/Chrome.apk
,E/ActivityManager(  890): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  890): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  890): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  890): checkUser: useridlist=null, currentuser=0
,D/ResourcesManager( 8090): creating new AssetManager and set to /system/priv-app/SamsungMusic_20/SamsungMusic_20.apk
,W/ResourcesManager( 8090): Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
W/ResourcesManager( 8090): Asset path '/system/framework/secvisualeffect.jar' does not exist or contains no resources.
W/ResourcesManager( 8090): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 8090): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager( 8090): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 8090): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
,D/ResourcesManager( 8090): creating new AssetManager and set to /system/priv-app/VoiceNote/VoiceNote.apk
,W/ResourcesManager( 8090): Asset path '/system/framework/secmediarecorder.jar' does not exist or contains no resources.
W/ResourcesManager( 8090): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,E/Zygote  ( 8732): MountEmulatedStorage()
E/Zygote  ( 8732): v2
I/libpersona( 8732): KNOX_SDCARD checking this for 10042
I/libpersona( 8732): KNOX_SDCARD not a persona
,I/ActivityManager(  890): Start proc com.samsung.android.sdk.samsunglink for broadcast com.samsung.android.sdk.samsunglink/com.sec.pcw.service.push.spp.SPPReceiver: pid=8732 uid=10042 gids={50042, 9997, 1007, 3003, 1028, 1015, 1023, 3002, 3001} abi=armeabi-v7a
,I/SELinux ( 8732): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/ActivityManager(  890): Killing 7336:com.sec.android.widgetapp.dualclockdigital/u0a103 (adj 15): bgCount ##41
,I/SELinux ( 8732): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 8732): [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
,I/ServiceManager(  326): Waiting for service AtCmdFwd...
,D/TimaKeyStoreProvider( 8732): TimaSignature is unavailable
,D/ActivityThread( 8732): Added TimaKeyStore provider
,D/ResourcesManager( 8732): creating new AssetManager and set to /system/priv-app/SamsungLinkPlatform/SamsungLinkPlatform.apk
,W/ResourcesManager( 8732): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 8732): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
,W/libprocessgroup(  890): failed to open /acct/uid_10103/pid_7336/cgroup.procs: No such file or directory
,E/SQLiteDatabase( 8732): Failed to open database '/data/data/com.samsung.android.sdk.samsunglink/databases/asp.db'.
E/SQLiteDatabase( 8732): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 8732): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 8732): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
E/SQLiteDatabase( 8732): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
E/SQLiteDatabase( 8732): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase( 8732): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase( 8732): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase( 8732): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:891)
E/SQLiteDatabase( 8732): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:861)
E/SQLiteDatabase( 8732): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
E/SQLiteDatabase( 8732): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1450)
E/SQLiteDatabase( 8732): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/SQLiteDatabase( 8732): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 8732): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 8732): 	at com.mfluent.asp.datamodel.ASPMediaStoreProvider.onCreate(SourceFile:462)
E/SQLiteDatabase( 8732): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1714)
E/SQLiteDatabase( 8732): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1683)
E/SQLiteDatabase( 8732): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5453)
E/SQLiteDatabase( 8732): 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:5048)
E/SQLiteDatabase( 8732): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4988)
E/SQLiteDatabase( 8732): 	at android.app.ActivityThread.access$1600(ActivityThread.java:172)
E/SQLiteDatabase( 8732): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1483)
E/SQLiteDatabase( 8732): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 8732): 	at android.os.Looper.loop(Looper.java:145)
E/SQLiteDatabase( 8732): 	at android.app.ActivityThread.main(ActivityThread.java:5832)
E/SQLiteDatabase( 8732): 	at java.lang.reflect.Method.invoke(Native Method)
E/SQLiteDatabase( 8732): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/SQLiteDatabase( 8732): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
E/SQLiteDatabase( 8732): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
,D/AndroidRuntime( 8732): Shutting down VM
E/AndroidRuntime( 8732): FATAL EXCEPTION: main
E/AndroidRuntime( 8732): Process: com.samsung.android.sdk.samsunglink, PID: 8732
E/AndroidRuntime( 8732): java.lang.RuntimeException: Unable to get provider com.mfluent.asp.datamodel.ASPMediaStoreProvider: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 8732): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5456)
E/AndroidRuntime( 8732): 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:5048)
E/AndroidRuntime( 8732): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4988)
E/AndroidRuntime( 8732): 	at android.app.ActivityThread.access$1600(ActivityThread.java:172)
E/AndroidRuntime( 8732): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1483)
E/AndroidRuntime( 8732): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 8732): 	at android.os.Looper.loop(Looper.java:145)
E/AndroidRuntime( 8732): 	at android.app.ActivityThread.main(ActivityThread.java:5832)
E/AndroidRuntime( 8732): 	at java.lang.reflect.Method.invoke(Native Method)
E/AndroidRuntime( 8732): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/AndroidRuntime( 8732): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
E/AndroidRuntime( 8732): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
E/AndroidRuntime( 8732): Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 8732): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 8732): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
E/AndroidRuntime( 8732): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
E/AndroidRuntime( 8732): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/AndroidRuntime( 8732): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/AndroidRuntime( 8732): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/AndroidRuntime( 8732): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:891)
E/AndroidRuntime( 8732): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:861)
E/AndroidRuntime( 8732): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
E/AndroidRuntime( 8732): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1450)
E/AndroidRuntime( 8732): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/AndroidRuntime( 8732): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/AndroidRuntime( 8732): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/AndroidRuntime( 8732): 	at com.mfluent.asp.datamodel.ASPMediaStoreProvider.onCreate(SourceFile:462)
E/AndroidRuntime( 8732): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1714)
E/AndroidRuntime( 8732): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1683)
E/AndroidRuntime( 8732): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5453)
E/AndroidRuntime( 8732): 	... 11 more
F/libc    ( 8732): Fatal signal 7 (SIGBUS), code 2, fault addr 0x7195e498 in tid 8732 (sdk.samsunglink)
E/audit_log( 2005): File locking failed. error= Bad file number
,E/audit_log( 2005): File locking failed. error= Bad file number
,I/ActivityManager(  890): Process com.samsung.android.sdk.samsunglink (pid 8732)(adj 0) has died(224,488)
,I/SA      ( 7782): [SUR] onReceive log=[SA = 2.1.0142 V = 21 HWD = 1920X1080 3.0 dpi = 480  SIZE = 2 LOCALE = en_US CSC = DBT MCC = 0 MNC 0 T = user DEVICE = klte P = kltexx I = LRX21T M = SM-G900F OKLEFT false DIS LRX21T.G900FXXU1BOD3 PSS = 5.219788042639568  ]
,I/SA      ( 7782): [SUR] onReceive Intent=[ action_PACKAGE_REMOVED package extra.REMOVED_FOR_ALL_USERS.:true extra.UID.:10200 extra.DATA_REMOVED.:true extra.user_handle.:0 ]
,I/EventHub(  890): Removing device '/dev/input/event4' due to inotify event
,F/libc    ( 1799): Fatal signal 7 (SIGBUS), code 2, fault addr 0x7828ee10 in tid 1858 (ContactsProvide)
,F/libc    ( 1799): Unable to open connection to debuggerd: Connection refused
E/audit_log( 2005): File locking failed. error= Bad file number
,I/Zygote  (  317): Process 8732 exited due to signal (7)
,I/EventHub(  890): Removing device '/dev/input/event5' due to inotify event
,I/ActivityManager(  890): Process android.process.acore (pid 1799)(adj 0) has died(230,489)
,F/libc    (  890): Fatal signal 7 (SIGBUS), code 2, fault addr 0xa04054bc in tid 1359 (Binder_7)
,F/libc    (  890): Unable to open connection to debuggerd: Connection refused
,E/audit_log( 2005): File locking failed. error= Bad file number
,I/Zygote  (  317): Process 1799 exited due to signal (7)
,W/Sensors ( 6008): sensorservice died [0xaf0f9540]
,I/ServiceManager(  247): service 'lock_settings' died
I/ServiceManager(  247): service 'device_policy' died
I/ServiceManager(  247): service 'harmony_eas_service' died
I/ServiceManager(  247): service 'sdp' died
I/ServiceManager(  247): service 'log_manager_service' died
I/ServiceManager(  247): service 'application_policy' died
I/ServiceManager(  247): service 'wifi_policy' died
I/ServiceManager(  247): service 'phone_restriction_policy' died
I/ServiceManager(  247): service 'remoteinjection' died
I/ServiceManager(  247): service 'mum_container_policy' died
I/ServiceManager(  247): service 'enterprise_billing_policy' died
I/ServiceManager(  247): service 'knox_timakeystore_policy' died
I/ServiceManager(  247): service 'enterprise_policy' died
I/ServiceManager(  247): service 'statusbar' died
I/ServiceManager(  247): service 'clipboard' died
I/ServiceManager(  247): service 'clipboardEx' died
I/ServiceManager(  247): service 'network_management' died
I/ServiceManager(  247): service 'ABTPersistenceService' died
E/audit_log( 2005): File locking failed. error= Bad file number
I/ServiceManager(  247): service 'textservices' died
I/ServiceManager(  247): service 'network_score' died
,I/ServiceManager(  247): service 'netstats' died
,I/ServiceManager(  247): service 'wifi' died
,I/ServiceManager(  247): service 'msapwifi' died
,I/ServiceManager(  247): service 'wifiscanner' died
,I/ServiceManager(  247): service 'rttmanager' died
,I/ServiceManager(  247): service 'connectivity' died
,I/ServiceManager(  247): service 'sb_service' died
,I/ServiceManager(  247): service 'clinfo' died
I/ServiceManager(  247): service 'servicediscovery' died
I/ServiceManager(  247): service 'updatelock' died
I/ServiceManager(  247): service 'notification' died
I/ServiceManager(  247): service 'devicestoragemonitor' died
I/ServiceManager(  247): service 'location' died,
I/ServiceManager(  247): service 'country_detector' died
I/ServiceManager(  247): service 'sec_location' died
I/ServiceManager(  247): service 'search' died
I/ServiceManager(  247): service 'dropbox' died
I/ServiceManager(  247): service 'wallpaper' died
,I/ServiceManager(  247): service 'netpolicy' died
I/ServiceManager(  247): service 'wifip2p' died
I/ServiceManager(  247): service 'backup' died
I/ServiceManager(  247): service 'appwidget' died
I/ServiceManager(  247): service 'voiceinteraction' died
I/ServiceManager(  247): service 'SecExternalDisplayService' died
I/ServiceManager(  247): service 'diskstats' died
I/ServiceManager(  247): service 'spengestureservice' died
I/ServiceManager(  247): service 'quickconnect' died
I/ServiceManager(  247): service 'samplingprofiler' died
,I/ServiceManager(  247): service 'commontime_management' died
I/ServiceManager(  247): service 'dreams' died
I/ServiceManager(  247): service 'print' died
I/ServiceManager(  247): service 'restrictions' died
I/ServiceManager(  247): service 'media_session' died
I/ServiceManager(  247): service 'media_router' died
I/ServiceManager(  247): service 'trust' died
I/ServiceManager(  247): service 'fingerprint' died
I/ServiceManager(  247): service 'launcherapps' died
,I/ServiceManager(  247): service 'voip' died
I/ServiceManager(  247): service 'media_projection' died
I/ServiceManager(  247): service 'imms' died
I/ServiceManager(  247): service 'audio' died
I/ServiceManager(  247): service 'DockObserver' died
I/ServiceManager(  247): service 'usb' died
I/ServiceManager(  247): service 'serial' died
I/ServiceManager(  247): service 'uimode' died
I/ServiceManager(  247): service 'jobscheduler' died
,I/ServiceManager(  247): service 'enterprise_license_policy' died
I/ServiceManager(  247): service 'context_aware' died
I/ServiceManager(  247): service 'scontext' died
I/ServiceManager(  247): service 'barbeam' died
I/ServiceManager(  247): service 'multiwindow_facade' died
I/ServiceManager(  247): service 'window' died
I/ServiceManager(  247): service 'input' died
I/ServiceManager(  247): service 'tactileassist' died
I/ServiceManager(  247): service 'bluetooth_manager' died
I/ServiceManager(  247): service 'bluetooth_secure_mode_manager' died
,I/ServiceManager(  247): service 'rcp' died
I/ServiceManager(  247): service 'accessibility' died
I/ServiceManager(  247): service 'motion_recognition' died
I/ServiceManager(  247): service 'cover' died
I/ServiceManager(  247): service 'sec_analytics' died
I/ServiceManager(  247): service 'input_method' died
I/ServiceManager(  247): service 'mount' died
I/ServiceManager(  247): service 'batterystats' died
I/ServiceManager(  247): service 'appops' died
,I/ServiceManager(  247): service 'power' died
I/ServiceManager(  247): service 'display' died
I/ServiceManager(  247): service 'persona_policy' died
I/ServiceManager(  247): service 'SEAMService' died
I/ServiceManager(  247): service 'persona' died
I/ServiceManager(  247): service 'account' died
,I/ServiceManager(  247): service 'content' died
I/ServiceManager(  247): service 'DirEncryptService' died
I/ServiceManager(  247): service 'ReactiveService' died
I/ServiceManager(  247): service 'sedenial' died
I/ServiceManager(  247): service 'vibrator' died
I/ServiceManager(  247): service 'tw_toolbox' died
I/ServiceManager(  247): service 'tima' died
I/ServiceManager(  247): service 'cepproxyks' died
I/ServiceManager(  247): service 'CustomFrequencyManagerService' died
,I/ServiceManager(  247): service 'samsung.smartfaceservice' died
I/ServiceManager(  247): service 'consumer_ir' died
I/ServiceManager(  247): service 'alarm' died
I/ServiceManager(  247): service 'gfxinfo' died
,I/ServiceManager(  247): service 'scheduling_policy' died
I/ServiceManager(  247): service 'user' died
I/ServiceManager(  247): service 'dbinfo' died
I/ServiceManager(  247): service 'activity' died
I/ServiceManager(  247): service 'meminfo' died
I/ServiceManager(  247): service 'usagestats' died
I/ServiceManager(  247): service 'edmnativehelper' died
I/ServiceManager(  247): service 'package' died
I/ServiceManager(  247): service 'cpuinfo' died
,I/ServiceManager(  247): service 'hardware' died
I/ServiceManager(  247): service 'webviewupdate' died
I/ServiceManager(  247): service 'telephony.registry' died
I/ServiceManager(  247): service 'entropy' died
I/ServiceManager(  247): service 'sensorservice' died
I/ServiceManager(  247): service 'mdm.remotedesktop' died
I/ServiceManager(  247): service 'battery' died
I/ServiceManager(  247): service 'procstats' died
I/ServiceManager(  247): service 'permission' died
,F/libc    ( 1670): Fatal signal 7 (SIGBUS), code 2, fault addr 0x758b6c2d in tid 1670 (e.process.gapps)
F/libc    ( 1670): Unable to open connection to debuggerd: Connection refused
I/SurfaceFlinger(  249): restart the boot-animation @ binderDied
D/SurfaceFlinger(  249): Set power mode=2, type=0 flinger=0xb6a62000
D/qdhwcomposer(  249): hwc_blank: Unblanking display: 0
W/Sensors ( 2132): sensorservice died [0xaf0bfc00]
W/Sensors ( 1475): sensorservice died [0xaf07e340]
W/AudioFlinger(  285): power manager service died !!!
,W/AudioFlinger(  285): power manager service died !!!
W/Sensors ( 1458): sensorservice died [0xaf0bfb80]
I/SurfaceFlinger(  249): id=7 Removed com.android.systemui.ImageWallpaper (3/8)
I/SurfaceFlinger(  249): id=7 Removed com.android.systemui.ImageWallpaper (-2/8)
I/SurfaceFlinger(  249): id=18 Removed com.sec.android.app.launcher/com.android.launcher2.Launcher (4/7)
I/SurfaceFlinger(  249): id=18 Removed com.sec.android.app.launcher/com.android.launcher2.Launcher (-2/7)
I/SurfaceFlinger(  249): id=9 Removed StatusBar (5/6)
,I/SurfaceFlinger(  249): id=9 Removed StatusBar (-2/6)
I/SurfaceFlinger(  249): id=17 Removed ColorFade (5/5)
I/SurfaceFlinger(  249): id=17 Removed ColorFade (-2/5)
I/SurfaceFlinger(  249): id=5 Removed DimLayer (2/4)
I/SurfaceFlinger(  249): id=6 Removed DimLayer (3/3)
I/SurfaceFlinger(  249): id=2 Removed FocusedStackFrame (2/2)
I/SurfaceFlinger(  249): id=3 Removed DimLayer (0/1)
I/SurfaceFlinger(  249): id=4 Removed DimLayer (0/0)
,I/SurfaceFlinger(  249): id=5 Removed DimLayer (-2/0)
I/SurfaceFlinger(  249): id=6 Removed DimLayer (-2/0)
I/SurfaceFlinger(  249): id=2 Removed FocusedStackFrame (-2/0)
I/SurfaceFlinger(  249): id=3 Removed DimLayer (-2/0)
I/SurfaceFlinger(  249): id=4 Removed DimLayer (-2/0)
E/WifiManager( 1765): Channel connection lost
,E/WifiManager( 1169): Channel connection lost
,W/Sensors ( 2097): sensorservice died [0xaf0c1ec0]
,E/WifiManager( 1559): Channel connection lost
,W/Sensors ( 1490): sensorservice died [0xaf065400]
,E/WifiManager( 1475): Channel connection lost
,W/Sensors ( 1169): sensorservice died [0xaf0d00c0]
,W/Sensors ( 1304): sensorservice died [0x9d4212c0]
,E/SMD     (  277): DCD ON
,E/WifiManager( 1304): Channel connection lost
,E/WifiManager( 2097): Channel connection lost
,F/libc    ( 2447): Fatal signal 7 (SIGBUS), code 2, fault addr 0x758b6dd5 in tid 2447 (gle.android.gms)
,F/libc    ( 2447): Unable to open connection to debuggerd: Connection refused
E/audit_log( 2005): File locking failed. error= Bad file number
F/libc    ( 2097): Fatal signal 7 (SIGBUS), code 2, fault addr 0x758b6dd5 in tid 2097 (.gms.persistent)
F/libc    ( 2097): Unable to open connection to debuggerd: Connection refused
E/audit_log( 2005): File locking failed. error= Bad file number
,I/Zygote  (  317): Process 1670 exited due to signal (7)
,F/libc    ( 7396): Fatal signal 7 (SIGBUS), code 2, fault addr 0x78b2417a in tid 7396 (roid.apps.books)
F/libc    ( 7396): Unable to open connection to debuggerd: Connection refused
,E/audit_log( 2005): File locking failed. error= Bad file number
,I/Zygote  (  317): Process 2447 exited due to signal (7)
,F/libc    ( 6565): Fatal signal 7 (SIGBUS), code 2, fault addr 0xa03688ec in tid 6565 (android.vending)
F/libc    ( 6565): Unable to open connection to debuggerd: Connection refused
,E/audit_log( 2005): File locking failed. error= Bad file number
,I/Zygote  (  317): Process 7396 exited due to signal (7)
,I/Zygote  (  317): Process 2097 exited due to signal (7)
,E/installd(  289): eof
E/installd(  289): failed to read size
I/installd(  289): closing connection
,I/Zygote  (  317): Process 6565 exited due to signal (7)
,I/qdhwcomposer(  249): handle_blank_event: dpy:0 panel power state: 0
,E/qdexternal(  249): writeHPDOption: file write failed '/sys/devices/virtual/graphics/fb1/hpd'
D/qdhwcomposer(  249): hwc_blank: Done unblanking display: 0
,E/qdhwcomposer(  249): hwc_vsync_control: vsync control failed. Dpy=0, enable=1 : Operation not permitted
E/SurfaceFlinger(  249): eventControl(0, 1) failed Operation not permitted
,I/ServiceManager(  326): Waiting for service AtCmdFwd...
,I/qdhwcomposer(  249): handle_blank_event: dpy:0 panel power state: 0
,I/lowmemorykiller(  246): ActivityManager disconnected
I/lowmemorykiller(  246): Closing Activity Manager data connection

```
