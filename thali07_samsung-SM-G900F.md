#### Test 50650278ec2c976_thali07_samsung-SM-G900F Logs


```
--------- beginning of main,
D/StatusBar.NetworkController( 1169): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02012b/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020466/com.android.systemui:drawable/stat_sys_signal_inout mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
D/StatusBar.NetworkController( 1169): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1169): applyOpen
D/StatusBar.NetworkController( 1169): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1169): applyOpen
D/StatusBar.NetworkController( 1169): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1169): applyOpen
D/StatusBar.NetworkController( 1169): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1169): applyOpen
D/AndroidRuntime( 7371): 
D/AndroidRuntime( 7371): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 7371): CheckJNI is OFF
D/AndroidRuntime( 7371): setted country_code = Germany
D/AndroidRuntime( 7371): setted countryiso_code = DE
D/AndroidRuntime( 7371): setted sales_code = DBT
D/AndroidRuntime( 7371): readGMSProperty: start
D/AndroidRuntime( 7371): readGMSProperty: already setted!!
D/AndroidRuntime( 7371): readGMSProperty: end
D/AndroidRuntime( 7371): addProductProperty: start
V/GLSActivity( 1652): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/GLSUser ( 1652): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
I/GLSUser ( 1652): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1652): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1652): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 1652): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/BitmapFactory( 1652): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
D/SecContentProvider2(  875): uri = 14 selection = getSealedState
D/SecContentProvider2(  875): mCursor = null
D/SecContentProvider2(  875): KnoxCustomManagerService offline: service is not available
D/ApplicationPolicy(  875): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
V/ApplicationPolicy(  875): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
D/StatusBar( 1169): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
I/PhoneStatusBar( 1169): Icon Only
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
D/PanelView( 1169): There is/are notification(s) 
D/PanelView( 1169): There is/are notification(s) 
W/GLSActivity( 1652): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1652): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1652): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1652): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1652): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1652): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1652): 	at android.os.Binder.execTransact(Binder.java:446)
E/BooksAccountManager( 7308): Authentication error
E/BooksAccountManager( 7308): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 7308): android.accounts.AccountManager.convertErrorToException(AccountManager.java:1893)
E/HttpHelper( 7308): null auth token
I/qtaguid ( 7308): Tagging socket 34 with tag 10000000000{256,0} uid -1, pid: 7308, getuid(): 10082
I/qtaguid ( 7308): Tagging socket 38 with tag 10000000000{256,0} uid -1, pid: 7308, getuid(): 10082
E/AffinityControl( 7371): AffinityControl: registerfunction enter
I/qtaguid ( 7308): Untagging socket 34
D/AndroidRuntime( 7371): Calling main entry com.android.commands.am.Am
W/ApiaryClient( 7308): Error response from books API: {
W/ApiaryClient( 7308):  "error": {
W/ApiaryClient( 7308):   "errors": [
W/ApiaryClient( 7308):    {
W/ApiaryClient( 7308):     "domain": "global",
W/ApiaryClient( 7308):     "reason": "required",
W/ApiaryClient( 7308):     "message": "Login Required",
W/ApiaryClient( 7308):     "locationType": "header",
W/ApiaryClient( 7308):     "location": "Authorization"
W/ApiaryClient( 7308):    }
W/ApiaryClient( 7308):   ],
W/ApiaryClient( 7308):   "code": 401,
W/ApiaryClient( 7308):   "message": "Login Required"
W/ApiaryClient( 7308):  }
W/ApiaryClient( 7308): }
W/ApiaryClient( 7308): errCount = 2: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 7308): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3DS0HXd4TFLU4&nonce=-8918747899513531564&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 7308): Headers suppressed
--------- beginning of system
D/ConnectivityService(  875): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
E/PersonaManagerService(  875): inState():  stateMachine is null !!
V/ApplicationPolicy(  875): isApplicationStateBlocked userId 0 pkgname com.test.thalitest
I/ActivityManager(  875): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
D/ResourcesManager(  875): creating new AssetManager and set to /data/app/com.test.thalitest-1/base.apk
D/CustomFrequencyManagerService(  875): acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1958400  uid : 1000  pid : 875  pkgName : ACTIVITY_RESUME_BOOSTER@6
W/ActivityManager(  875): mDVFSHelper.acquire()
D/FocusedStackFrame(  875): Set to : 0
D/AndroidRuntime( 7371): Shutting down VM
D/Launcher.HomeView( 1471): onPause
D/Launcher( 1471): Launcher::setSystemUiTransparency(): getSystemUiVisibility() after setting  = 40000000
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
V/TaskCloserActivity( 7146): TaskCloserActivity onReceive() - com.sec.android.intent.action.HOME_PAUSE
E/ActivityManager(  875): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  875): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  875): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  875): checkUser: useridlist=null, currentuser=0
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
I/SurfaceFlinger(  249): id=14 createSurf (1x1),1 flag=404, Starting com.test.thalitest
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
E/Zygote  ( 7393): MountEmulatedStorage()
E/Zygote  ( 7393): v2
I/libpersona( 7393): KNOX_SDCARD checking this for 10367
I/libpersona( 7393): KNOX_SDCARD not a persona
I/ActivityManager(  875): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=7393 uid=10367 gids={50367, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
I/SELinux ( 7393): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
I/SELinux ( 7393): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
E/SELinux ( 7393): [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
D/StatusBarManagerService(  875): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
I/MicrophoneInputStream( 1527): mic_close gfk@23e9fcc8
E/SMD     (  287): DCD ON
V/AudioPolicyManager(  293): stopInput() input 29
V/AudioPolicyManager(  293): releaseInput() 29
V/AudioPolicyManager(  293): closeInput(29)
V/audio_hw_primary(  293): in_standby: enter
I/HotwordRecognitionRnr( 1527): Hotword detection finished
I/HotwordRecognitionRnr( 1527): Stopping hotword detection.
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
D/TimaKeyStoreProvider( 7393): TimaSignature is unavailable
D/ActivityThread( 7393): Added TimaKeyStore provider
V/WindowOrientationListener(  875): mSContextAutoRotationListener.getProposedRotation, mbResultFaceDectection: false
V/WindowOrientationListener(  875): mSContextAutoRotationListener.getProposedRotation, Rotation: -1
V/WindowManager(  875): rotationForOrientationLw(orient=-1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false
V/WindowOrientationListener(  875): mSContextAutoRotationListener.getProposedRotation, mbResultFaceDectection: false
V/WindowOrientationListener(  875): mSContextAutoRotationListener.getProposedRotation, Rotation: -1
V/ActivityManager(  875): Display changed displayId=0
D/Launcher.HomeView( 1471): onStop
D/SurfaceWidgetClient$ISurfaceWidgetStub( 2135): [237392/6] Surface widget pause on instance = 1
D/accuweather( 2135): [KK AccuPhone]>>> SWW:239 [0:0] [SWW] onPause : instance = 1
D/accuweather( 2135): [KK AccuPhone]>>> SWW:254 [0:0] onPause : size = 0
D/accuweather( 2135): [KK AccuPhone]>>> SWW:545 [0:0]  unRegisterTTReceiver !! 
V/audio_hw_primary(  293): stop_input_stream: enter: usecase(7: audio-record)
V/audio_hw_primary(  293): disable_audio_route: enter: usecase(7)
V/audio_hw_primary(  293): disable_audio_route: reset mixer path: audio-record
D/audio_route(  293): ++++ audio_route_update_mixer ==============
D/audio_route(  293): Setting mixer control: MultiMedia1 Mixer SLIM_0_TX
D/audio_route(  293): Setting mixer control: value: 0
D/audio_route(  293): ------ audio_route_update_mixer ==============
V/audio_hw_primary(  293): disable_audio_route: exit
V/audio_hw_primary(  293): disable_snd_device: snd_device(122: vr-main-mic)
D/audio_route(  293): ++++ audio_route_update_mixer ==============
D/audio_route(  293): Setting mixer control: DEC2 Volume
D/audio_route(  293): Setting mixer control: value: 0
D/audio_route(  293): Setting mixer control: SLIM TX7 MUX, value: 0
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
D/audio_route(  293): Setting mixer control: AIF1_CAP Mixer SLIM TX7
D/audio_route(  293): Setting mixer control: value: 0
D/audio_route(  293): Setting mixer control: DEC2 MUX, value: 0
D/audio_route(  293): ------ audio_route_update_mixer ==============
V/audio_hw_primary(  293): stop_input_stream: exit: status(0)
V/audio_hw_primary(  293): in_standby: exit:  status(0)
V/audio_hw_primary(  293): adev_close_input_stream
V/audio_hw_primary(  293): in_standby: enter
V/audio_hw_primary(  293): in_standby: exit:  status(0)
E/audio_hw_primary(  293): adev_close_input_stream, set jack_in to null
V/AudioPolicyManager(  293): releaseInput() exit
D/SurfaceWidgetClient$ISurfaceWidgetStub( 2135): [237392/6] Surface widget visibility changed visibility = false on instance = 1
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
D/SurfaceWidgetView( 1471): destroyHardwareResources():37753014
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
D/StatusBarManagerService(  875): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
D/accuweather( 2135): [KK AccuPhone]>>> WR:132 [0:0] onPause
D/accuweather( 2135): [KK AccuPhone]>>> SM:538 [0:0] onPause
D/ConnectivityService(  875): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/ResourcesManager( 7393): creating new AssetManager and set to /data/app/com.test.thalitest-1/base.apk
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
D/Launcher( 1471): onTrimMemory. Level: 20
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/SurfaceWidgetView( 1471): destroyHardwareResources():37753014
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
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
I/WebViewFactory( 7393): Loading com.google.android.webview version 37 (1726107-arm) (code 119201)
D/ResourcesManager( 7393): creating new AssetManager and set to /system/app/WebViewGoogle/WebViewGoogle.apk
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
I/LibraryLoader( 7393): Loading: webviewchromium
I/LibraryLoader( 7393): Time to load native libraries: 1 ms (timestamps 4702-4703)
I/LibraryLoader( 7393): Expected native library version number "",actual native library version number ""
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
V/WebViewChromiumFactoryProvider( 7393): Binding Chromium to main looper Looper (main, tid 1) {3292e37e}
I/LibraryLoader( 7393): Expected native library version number "",actual native library version number ""
I/chromium( 7393): [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 7393): Initializing chromium process, renderers=0
W/art     ( 7393): Attempt to remove local handle scope entry from IRT, ignoring
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
W/chromium( 7393): [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
I/chromium( 7393): [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=35 off=46768 len=2953
I/chromium( 7393): [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:36 off:229524 len:643667
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
I/Adreno-EGL( 7393): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 7393): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 7393): Build Date: 03/03/15 Tue
I/Adreno-EGL( 7393): Local Branch: LA.BF.1.1_RB1_20150108_025_1077123_1158499
I/Adreno-EGL( 7393): Remote Branch: 
I/Adreno-EGL( 7393): Local Patches: 
I/Adreno-EGL( 7393): Reconstruct Branch: 
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
W/chromium( 7393): [WARNING:proxy_service.cc(901)] PAC support disabled because there is no system implementation
W/chromium( 7393): [WARNING:data_reduction_proxy_settings.cc(403)] SPDY proxy OFF at startup
W/art     ( 7393): Attempt to remove local handle scope entry from IRT, ignoring
W/AwContents( 7393): onDetachedFromWindow called when already detached. Ignoring
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
D/SystemWebViewEngine( 7393): CordovaWebView is running on device made by: samsung
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
W/art     ( 7393): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 7393): Attempt to remove local handle scope entry from IRT, ignoring
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
D/Activity( 7393): performCreate Call secproduct feature valuefalse
D/Activity( 7393): performCreate Call debug elastic valuetrue
D/OpenGLRenderer( 7393): Render dirty regions requested: true
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
D/ActivityManager(  875): post active user change for 0
D/KnoxTimeoutHandler(  875): postActiveUserChange for user 0
D/KnoxTimeoutHandler(  875): handleActiveUserChange for user 0
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
I/OpenGLRenderer( 7393): Initialized EGL, version 1.4
I/OpenGLRenderer( 7393): HWUI protection enabled for context ,  &this =0xa1653060 ,&mEglDisplay = 1 , &mEglConfig = 8 
D/OpenGLRenderer( 7393): Enabling debug mode 0
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
D/InputMethodManagerService(  875): windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
W/ContextImpl(  875): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.android.server.InputMethodManagerService$6.run:2728 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
W/ContextImpl(  875): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.android.server.InputMethodManagerService$6.run:2728 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
I/SurfaceFlinger(  249): id=8 Removed com.sec.android.app.launcher/com.android.launcher2.Launcher (4/9)
I/SurfaceFlinger(  249): id=8 Removed com.sec.android.app.launcher/com.android.launcher2.Launcher (-2/9)
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
I/ActivityManager(  875): Displayed com.test.thalitest/.MainActivity: +628ms
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
I/Timeline( 7393): Timeline: Activity_idle id: android.os.BinderProxy@2378baa9 time:95065
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
D/JsMessageQueue( 7393): Set native->JS mode to OnlineEventsBridgeMode
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
I/chromium( 7393): [INFO:SkUtilsArm.cpp(179)] Device supports ARM NEON instructions!
I/chromium( 7393): 
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
D/jxcore_app_log( 7393): JniHelper::setJavaVM(0xb4e5c280), pthread_self() = -1359590400
D/JX-Cordova( 7393): jxcore cordova android initializing
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
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
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
D/CustomFrequencyManagerService(  875): releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1958400  uid : 1000  pid : 875  tag : ACTIVITY_RESUME_BOOSTER@6
W/ActivityManager(  875): mDVFSHelper.release()
I/Timeline(  875): Timeline: Activity_windows_visible id: ActivityRecord{2294a978 u0 com.test.thalitest/.MainActivity t11} time:95302
D/CustomFrequencyManagerService(  875): acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1958400  uid : 1000  pid : 875  pkgName : ACTIVITY_RESUME_BOOSTER@10
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
V/GLSActivity( 1652): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/GLSUser ( 1652): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
I/GLSUser ( 1652): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1652): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1652): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 1652): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/BitmapFactory( 1652): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
D/SecContentProvider2(  875): uri = 14 selection = getSealedState
D/SecContentProvider2(  875): mCursor = null
D/SecContentProvider2(  875): KnoxCustomManagerService offline: service is not available
D/ApplicationPolicy(  875): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
V/ApplicationPolicy(  875): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
D/StatusBar( 1169): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
I/PhoneStatusBar( 1169): Icon Only
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
D/PanelView( 1169): There is/are notification(s) 
D/PanelView( 1169): There is/are notification(s) 
,W/GLSActivity( 1652): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1652): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1652): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1652): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1652): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1652): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1652): 	at android.os.Binder.execTransact(Binder.java:446)
,E/BooksAccountManager( 7308): Authentication error
E/BooksAccountManager( 7308): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 7308): android.accounts.AccountManager.convertErrorToException(AccountManager.java:1893)
E/HttpHelper( 7308): null auth token
,I/qtaguid ( 7308): Tagging socket 34 with tag 10000000000{256,0} uid -1, pid: 7308, getuid(): 10082
,D/CustomFrequencyManagerService(  875): releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1958400  uid : 1000  pid : 875  tag : ACTIVITY_RESUME_BOOSTER@10
,I/WifiStateMachine(  875): CMD_RSSI_POLL : calculateWifiScore in!
,I/WifiStateMachine(  875): CMD_RSSI_POLL : calculateWifiScore out!
I/WifiStateMachine(  875): CMD_RSSI_POLL : out!
I/qtaguid ( 7308): Untagging socket 34
W/ApiaryClient( 7308): Error response from books API: {
W/ApiaryClient( 7308):  "error": {
W/ApiaryClient( 7308):   "errors": [
W/ApiaryClient( 7308):    {
W/ApiaryClient( 7308):     "domain": "global",
W/ApiaryClient( 7308):     "reason": "required",
W/ApiaryClient( 7308):     "message": "Login Required",
W/ApiaryClient( 7308):     "locationType": "header",
W/ApiaryClient( 7308):     "location": "Authorization"
W/ApiaryClient( 7308):    }
W/ApiaryClient( 7308):   ],
W/ApiaryClient( 7308):   "code": 401,
W/ApiaryClient( 7308):   "message": "Login Required"
W/ApiaryClient( 7308):  }
W/ApiaryClient( 7308): }
W/ApiaryClient( 7308): errCount = 3: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 7308): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3DS0HXd4TFLU4&nonce=-8918747899513531564&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 7308): Headers suppressed
D/ConnectivityService(  875): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/SQLiteLog( 1652): (10) POSIX Error : 11 SQLite Error : 3850
,W/jxcore-log( 7393): Initializing JXcore engine
,E/BooksSync( 7308): Soft error
E/BooksSync( 7308): com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
E/BooksSync( 7308): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3DS0HXd4TFLU4&nonce=-8918747899513531564&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
E/BooksSync( 7308): Headers suppressed
E/BooksSync( 7308): 
E/BooksSync( 7308): com.google.android.apps.books.net.HttpHelper.wrapExceptionBasedOnStatus(HttpHelper.java:212)
W/jxcore-log( 7393): JXcore engine is ready
,E/BooksSync( 7308): Sync error
E/BooksSync( 7308): com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
E/BooksSync( 7308): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3DS0HXd4TFLU4&nonce=-8918747899513531564&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
E/BooksSync( 7308): Headers suppressed
E/BooksSync( 7308): 
E/BooksSync( 7308): com.google.android.apps.books.net.HttpHelper.wrapExceptionBasedOnStatus(HttpHelper.java:212)
,I/BooksSync( 7308): Finished books sync
,D/ConnectivityService(  875): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,W/jxcore-log( 7393): Starting JXcore engine
,D/SyncManager(  875): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 67246, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,I/ActivityManager(  875): Killing 6646:com.samsung.groupcast/u0a16 (adj 15): bgCount ##41
,D/ConnectivityService(  875): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  875): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SecContentProvider2(  875): uri = 11 selection = getMyKnoxAdmin
D/SecContentProvider2(  875): mCursor = null
,E/auditd  ( 2170): In denial and Property audit_ondenial is set to 1 ,
,D/SecurityLogAgent:SEDenialService(  875): Got Modify Event and sending Denial Intent foraudit.log
,W/ContextImpl(  875): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.android.server.SEDenialService$AuditFileObserver.onEvent:76 android.os.FileObserver$ObserverThread.onEvent:122 android.os.FileObserver$ObserverThread.observe:-2 android.os.FileObserver$ObserverThread.run:85 
,E/ActivityManager(  875): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  875): checkUser: useridlist=null, currentuser=0
D/SecurityLogAgent:SEDenialService(  875): audit.ondenial set to 0 after sending samsung.intent.action.knox.DENIAL_NOTIFICATION intent
E/ActivityManager(  875): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  875): checkUser: useridlist=null, currentuser=0
,W/libprocessgroup(  875): failed to open /acct/uid_10016/pid_6646/cgroup.procs: No such file or directory
,E/Zygote  ( 7462): MountEmulatedStorage()
E/Zygote  ( 7462): v2
I/libpersona( 7462): KNOX_SDCARD checking this for 1000
I/libpersona( 7462): KNOX_SDCARD not a persona
,I/ActivityManager(  875): Start proc com.samsung.android.securitylogagent for broadcast com.samsung.android.securitylogagent/.receivers.SeDenialReceiver: pid=7462 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,I/art     (  324): Explicit concurrent mark sweep GC freed 8710(370KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 14MB/23MB, paused 278us total 10.463ms
,I/art     (  324): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 14MB/23MB, paused 250us total 7.760ms
,I/art     (  324): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 14MB/23MB, paused 250us total 7.472ms
,I/SELinux ( 7462): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 7462): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 7462): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,W/jxcore-log( 7393): Platform android
W/jxcore-log( 7393): 
W/jxcore-log( 7393): Process ARCH arm
W/jxcore-log( 7393): 
,D/TimaKeyStoreProvider( 7462): TimaSignature is unavailable
,D/ActivityThread( 7462): Added TimaKeyStore provider
,D/ResourcesManager( 7462): creating new AssetManager and set to /system/app/SecurityLogAgent/SecurityLogAgent.apk
,D/SecurityLogAgent( 7462):  SeDenialReceiver : Intent Received : samsung.intent.action.knox.DENIAL_NOTIFICATION
,D/SecurityLogAgent( 7462):  SeDenialReceiver : File path = null
,I/ActivityManager(  875): Killing 6662:com.sec.pcw.device/1000 (adj 15): bgCount ##41
,W/libprocessgroup(  875): failed to open /acct/uid_1000/pid_6662/cgroup.procs: No such file or directory
,D/PowerManagerService(  875): [api] release WakeLock flags=0x10000006 tag=PowerUI.Notification uid=10059 pid=1169 (0x0)
,I/jxcore-log( 7393): JXcore Cordova bridge is ready!
I/jxcore-log( 7393): 
,W/jxcore-log( 7393): JXcore engine is started
,E/Adreno-ES20( 7393): <check_framebuffer_attachment:854>: Invalid texture format! Returning error!
,E/Adreno-ES20( 7393): <check_framebuffer_object_status:1237>: Framebuffer color attachment incomplete. Returning GL_FRAMEBUFFER_INCOMPLETE_ATTACHMENT!
,E/SMD     (  287): DCD ON
,I/GAV2    ( 7308): Thread[GAThread,5,main]: No campaign data found.
,D/StatusBar.NetworkController( 1169): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02012b/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020464/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
,D/StatusBar.NetworkController( 1169): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1169): applyOpen
,D/StatusBar.NetworkController( 1169): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1169): applyOpen
D/StatusBar.NetworkController( 1169): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1169): applyOpen
D/StatusBar.NetworkController( 1169): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1169): applyOpen
,D/SSRM:m  (  875): SIOP:: AP = 400, PST = 440, CUR = 300
,I/jxcore-log( 7393): Toggling radios to true
I/jxcore-log( 7393): 
,D/BluetoothAdapter( 7393): enable()
,D/BluetoothAdapter( 7393): enable(): BT is already enabled..!
,D/WifiService(  875): New client listening to asynchronous messages
,I/WifiManager( 7393): packageName : com.test.thalitest
,D/SecContentProvider(  875): uri = 18 selection = isWifiEnabled
D/SecContentProvider2(  875): uri = 20 selection = isWifiStateChangeAllowed
D/SecContentProvider2(  875): mCursor = null
,D/WifiService(  875): setWifiEnabled: true pid=7393, uid=10367
E/WifiService(  875): Invoking mWifiStateMachine.setWifiEnabled
,W/ActivityManager(  875): Permission Denial: getCurrentUser() from pid=7393, uid=10367 requires android.permission.INTERACT_ACROSS_USERS
,W/WifiService(  875): Failed getting userId using ActivityManagerNative
W/WifiService(  875): java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=7393, uid=10367 requires android.permission.INTERACT_ACROSS_USERS
W/WifiService(  875): 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:22619)
W/WifiService(  875): 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2119)
W/WifiService(  875): 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2107)
W/WifiService(  875): 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:223)
W/WifiService(  875): 	at android.os.Binder.execTransact(Binder.java:446)
,D/SettingsProvider(  875): name = wifi_on
,I/WifiService(  875): disconnect: pid=7393, uid=10367
,I/wpa_supplicant( 1281): [wpa_supplicant_ctrl_iface_process] : DISCONNECT
,I/jxcore-log( 7393): Radios toggled
I/jxcore-log( 7393): 
,I/jxcore-log( 7393): Got Device Bluetooth address: B0:C5:59:3F:75:69
I/jxcore-log( 7393): 
,I/jxcore-log( 7393): Perf Test app loaded loaded
I/jxcore-log( 7393): 
,I/jxcore-log( 7393): check test folder
I/jxcore-log( 7393): 
,I/jxcore-log( 7393): found test : ./testFindPeers.js
I/jxcore-log( 7393): 
,I/wpa_supplicant( 1281): CTRL-EVENT-DISCONNECTED bssid=C0.AA.48 reason=3 locally_generated=1
,I/wpa_supplicant( 1281): wlan0: State: COMPLETED -> DISCONNECTED
,I/wpa_supplicant( 1281): CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=C0.AA.48 SSID=4E47373030
I/wpa_supplicant( 1281): wlan0: State: DISCONNECTED -> DISCONNECTED
,E/WifiStateMachine(  875): WifiStateMachine: Leaving Connected state
I/wpa_supplicant( 1281): reset timer : RESET_TIMER 0
I/wpa_supplicant( 1281): wlan0: Setting scan request: 0 sec 0 usec
,I/wpa_supplicant( 1281): Disconnected - do not scan
I/wpa_supplicant( 1281): wlan0: State: DISCONNECTED -> DISCONNECTED
,E/WifiStateMachine(  875): handleNetworkDisconnect: Stopping DHCP and clearing IP stack:handleNetworkDisconnect - access$11200 - exit - invokeExitMethods
E/WifiStateMachine(  875): handleNetworkDisconnect c0:ff:d4:d3:aa:48 config "NG700"WPA_PSK config.bssid any
E/WifiStateMachine(  875): handleNetworkDisconnect "NG700" nid=0
E/WifiConfigStore(  875): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,E/WifiStateMachine(  875): setSuspendOptimizationsNative: 1 true -want true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - stopDhcp - handleNetworkDisconnect
,D/WifiP2pService(  875): InactiveState{ what=143375 }
,D/WifiP2pService(  875): P2pEnabledState{ what=143375 }
,D/StatusBar.NetworkController( 1169): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02012b/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020464/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
,V/AlarmManager(  875): waitForAlarm result :8
,D/CommandListener(  279): Clearing all IP addresses on wlan0
,V/NativeCrypto( 1652): Read error: ssl=0xaf01ba00: I/O error during system call, Connection timed out
,V/AlarmManager(  875): waitForAlarm result :4
,D/NtpTrustedTime(  875): forceRefresh() from cache miss
,I/jxcore-log( 7393): found test : ./testSendData.js
I/jxcore-log( 7393): 
,D/NtpTrustedTime(  875): forceRefresh Fail.
,V/NativeCrypto( 1652): SSL shutdown failed: ssl=0xaf01ba00: I/O error during system call, Broken pipe
,E/WifiStateMachine(  875): setDetailed state, old =CONNECTED and new state=DISCONNECTED hidden=false
,E/ConnectivityService(  875): updateNetworkInfo()
,D/ConnectivityService(  875): NetworkAgentInfo [WIFI () - 502] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityService(  875): NetworkAgentInfo [WIFI () - 502] got DISCONNECTED, was satisfying 2
,D/StatusBar.NetworkController( 1169): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020498/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020133/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020464/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
,D/StatusBar.NetworkController( 1169): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1169): applyOpen
,D/StatusBar.NetworkController( 1169): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1169): applyOpen
D/StatusBar.NetworkController( 1169): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1169): applyOpen
,D/StatusBar.NetworkController( 1169): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1169): applyOpen
,E/WifiConfigStore(  875): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,I/WifiTrafficPoller(  875): evaluateTrafficStatsPolling
D/ConnectivityService(  875): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  875): reportBadNetwork(NetworkAgentInfo [WIFI () - 502]) by 10012
I/CLocInfoService(  875): External Intent Received android.net.wifi.STATE_CHANGE
,E/WifiStateMachine(  875): Start Disconnecting Watchdog 1
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  875): ValidatedState{ when=-1ms what=532488 arg1=10012 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  875): DefaultState{ when=-4ms what=532488 arg1=10012 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  875): Forcing reevaluation
,I/wpa_supplicant( 1281): wlan0: Setting scan request: 0 sec 0 usec
I/wpa_supplicant( 1281): P2P: Current p2p state = IDLE
I/wpa_supplicant( 1281): wlan0: State: DISCONNECTED -> SCANNING
I/wpa_supplicant( 1281): CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00.00.00 SSID=
I/wpa_supplicant( 1281): First Scan Start
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  875): EvaluatingState{ when=-2ms what=532486 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  875): Validated
,D/ConnectivityService(  875): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  875): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/WifiStateMachine(  875): ConnectModeState: Network connection lost 
,E/WifiStateMachine(  875): handleNetworkDisconnect: Stopping DHCP and clearing IP stack:handleNetworkDisconnect - access$11200 - processMessage - processMsg
,E/WifiStateMachine(  875): setSuspendOptimizationsNative: 1 true -want true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - stopDhcp - handleNetworkDisconnect
,I/wpa_supplicant( 1281): Scan requested (ret=0) - scan timeout 30 seconds
,D/WifiP2pService(  875): InactiveState{ what=143375 }
,D/WifiP2pService(  875): P2pEnabledState{ what=143375 }
,D/StatusBar.NetworkController( 1169): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020498/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020133/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020464/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
,I/Hs20UtilService( 1309): Starting #6
I/Hs20UtilService( 1309): Message received 5007
,D/NearbySettings( 1309): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
V/NearbySettings( 1309): DMSUtil.isNetworkConnected - flag-null, state-null
,D/ConnectivityService(  875): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/NearbySettings( 1309): DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,D/ConnectivityService(  875): returning getNetworkInfo(networkType - 13) :[type: WIFI_P2P[] - WIFI_P2P, state: UNKNOWN/IDLE, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/NearbySettings( 1309): DMSUtil.isNetworkConnected - P2P: IDLE
,I/NearbySettings( 1309): DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
I/NearbySettings( 1309): MountReceiver.onReceive - Set preference state off
V/NearbySettings( 1309): MountReceiver.mPrefHandler - 7002
,D/CommandListener(  279): Clearing all IP addresses on wlan0
,D/ConnectivityService(  875): notifyType LOST for NetworkAgentInfo [WIFI () - 502]
D/ConnectivityService(  875): calling update connectivity
D/ConnectivityService(  875):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  875):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
,D/EntConnectivity(  875): Not allowed due to - mEnabled false
D/ConnectivityService(  875): sending notification LOST for NetworkRequest [ id=2, legacyType=-1, [] ]
D/Nat464Xlat(  875): requiresClat: netType=1, connected=false, hasIPv4Address=true
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  875): ValidatedState{ when=0 what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  875): DefaultState{ when=0 what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  875): Disconnected - quitting
,D/ConnectivityManager.CallbackHandler( 1169): CM callback handler got msg 524292
E/WifiStateMachine(  875): setDetailed state, old =DISCONNECTED and new state=DISCONNECTED hidden=false
,D/ConnectivityService(  875): Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  875): sending new Min Network Score(0): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,D/CSLegacyTypeTracker(  875): Removing agent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{502}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::ee1f:72ff:fe18:8b78/64,192.168.1.135/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{true} created{true} explicitlySelected{false} }
D/WifiStateMachine(  875): updateConfiguredNetworkExpiration - currTime: 1450109347360
D/CSLegacyTypeTracker(  875): Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 502] isDefaultNetwork=false
D/WifiStateMachine(  875): updateConfiguredNetworkExpiration - AP, "NG700", is not shared AP.
,D/ConnectivityService(  875): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
I/WifiTrafficPoller(  875): evaluateTrafficStatsPolling
,I/CLocInfoService(  875): External Intent Received android.net.wifi.STATE_CHANGE
,E/WifiStateMachine(  875): SUPPLICANT_STATE_CHANGE_EVENT state=DISCONNECTED -> state= DISCONNECTED debouncing=false
E/WifiStateMachine(  875): setDetailed state, old =DISCONNECTED and new state=DISCONNECTED hidden=false
,D/TelephonyNetworkFactory( 1457): Cellular needs Network for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,D/StatusBar.NetworkController( 1169): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020498/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020133/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020464/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
,E/WifiStateMachine(  875): Link configuration changed for netId: -1 old: {LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0} new: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0}
E/WifiStateMachine(  875): updateLinkProperties nid: -1 state: DISCONNECTED reason: CMD_UPDATE_LINKPROPERTIES
,E/WifiStateMachine(  875): Link configuration changed for netId: -1 old: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576} new: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0}
E/WifiStateMachine(  875): updateLinkProperties nid: -1 state: DISCONNECTED reason: CMD_UPDATE_LINKPROPERTIES
D/WifiNetworkAgent(  875): NetworkAgent: NetworkAgent channel lost
,D/ConnectivityService(  875): sendStickyBroadcastDelayed: delayMs=500, action=android.net.conn.CONNECTIVITY_CHANGE
,D/SmartBondingService(  875): SmartBondingReceiver: onReceive action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,D/NtpTrustedTime(  875): forceRefresh() from cache miss
V/NetworkStats(  875): updateIfacesLocked()
V/NetworkStats(  875): performPollLocked(flags=0x1)
,D/NtpTrustedTime(  875): forceRefresh Fail.
,D/NetworkStatsFactory(  875): UpdateStatsForKnox
D/ConnectivityService(  875): returning getNetworkInfo(networkType - 28) :[type: MOBILE_ENT1[] - MOBILE_ENT1, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/ConnectivityService(  875): EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
D/SmartBondingService(  875): EVENT_UPDATE_SB_STATE called / mDisableBySIOP false
,D/SmartBondingService(  875): getSBEnabled() enabled =false
D/StatusBar.NetworkController( 1169): getUpdateDataNetType(): 0
D/StatusBar.NetworkController( 1169): updateDataNetType()
D/StatusBar.NetworkController( 1169): NoService, mRoamingIconId = 0
D/SmartBondingService(  875): getSBEnabled() enabled =false
D/SmartBondingService(  875): getSBEnabled() enabled =false
,E/ConnectivityService(  875): EVENT_NETWORK_VALIDATED - isLiveNetworkAgent found mismatched netId: null - NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{502}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::ee1f:72ff:fe18:8b78/64,192.168.1.135/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{true} created{true} explicitlySelected{false} }
,V/NetworkStats(  875): advisePersistThreshold() given 9223372036854775, clamped to 2097152
,V/NetworkStats(  875): performPollLocked() took 7ms
,D/SmartBondingService(  875): getNetworkEnabled : wifi : true mobile : true
,D/StatusBar.NetworkController( 1169): updateDataIcon, mDataDirectionIconId = (null) mDataConnected = false
D/StatusBar.NetworkController( 1169): updateTelephonySignalStrength: hasService=false ss=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte
,D/StatusBar.NetworkController( 1169): updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal
,E/WifiStateMachine(  875): SUPPLICANT_STATE_CHANGE_EVENT state=SCANNING -> state= SCANNING debouncing=false
E/WifiStateMachine(  875): setDetailed state, old =DISCONNECTED and new state=SCANNING hidden=false
D/StatusBar.NetworkController( 1169): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020498/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020133/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020464/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
D/StatusBar.NetworkController( 1169): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1169): applyOpen
,D/StatusBar.NetworkController( 1169): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1169): applyOpen
D/StatusBar.NetworkController( 1169): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1169): applyOpen
D/StatusBar.NetworkController( 1169): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1169): applyOpen
,E/WifiStateMachine(  875): setDetailed state send new extra info"NG700"
,D/SecContentProvider2(  875): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2(  875): mCursor = null
,I/Hs20UtilService( 1309): Starting #7
,I/Hs20UtilService( 1309): Message received 5007
,D/NtpTrustedTime(  875): forceRefresh() from cache miss
,D/NtpTrustedTime(  875): forceRefresh Fail.
,D/NearbySettings( 1309): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,V/NearbySettings( 1309): DMSUtil.isNetworkConnected - flag-null, state-null
,D/ConnectivityService(  875): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/NearbySettings( 1309): DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,D/ConnectivityService(  875): returning getNetworkInfo(networkType - 13) :[type: WIFI_P2P[] - WIFI_P2P, state: UNKNOWN/IDLE, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/NearbySettings( 1309): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 1309): DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
I/NearbySettings( 1309): MountReceiver.onReceive - Set preference state off
,D/SecContentProvider2(  875): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2(  875): mCursor = null
,V/NearbySettings( 1309): MountReceiver.mPrefHandler - 7002
,I/Choreographer( 7393): Skipped 78 frames!  The application may be doing too much work on its main thread.
,D/FileWriteThread_Telephony( 1457): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 1457): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 1457): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 1457): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 1457): FileWriteThread : threadType = 3
D/FileWriteThread_Telephony( 1457): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 1457): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 1457): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 1457): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 1457): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 1457): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 1457): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 1457): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 1457): FileWriteThread : threadType = 3
,I/chromium( 7393): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,I/chromium( 7393): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
,V/GLSActivity( 1652): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1652): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
,I/GLSUser ( 1652): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1652): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1652): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1652): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/Finsky  ( 6561): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
D/Finsky  ( 6561): [1] 5.onFinished: Installation state replication failed.
D/Finsky  ( 6561): [1] 5.onFinished: Scheduling replication attempt 2.
,D/ConnectivityService(  875): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,I/ApplicationPolicy(  875): updateDataUsageMap
,D/ConnectivityService(  875): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  875): returning getNetworkInfo(networkType - 0) :[type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  875): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/accuweather( 2135): [KK AccuPhone]>>> SWW:66 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
D/Tethering(  875): MasterInitialState.processMessage what=3
D/ConnectivityService(  875): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/SmartBondingService(  875): SmartBondingReceiver: onReceive action=android.net.conn.CONNECTIVITY_CHANGE
D/ConnectivityService(  875): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/SmartBondingService(  875): EVENT_UPDATE_SB_STATE called / mDisableBySIOP false
D/SmartBondingService(  875): getSBEnabled() enabled =false
D/SmartBondingService(  875): getSBEnabled() enabled =false
D/SmartBondingService(  875): getSBEnabled() enabled =false
D/ConnectivityService(  875): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/ConnectivityService(  875): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/CLocInfoService(  875): External Intent Received android.net.conn.CONNECTIVITY_CHANGE
D/ConnectivityService(  875): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/CLocInfoService(  875): CLoinfo wifi false
E/ActivityManager(  875): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  875): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  875): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  875): checkUser: useridlist=null, currentuser=0
D/SmartBondingService(  875): getNetworkEnabled : wifi : true mobile : true
,W/SLocation(  875): No Active Data Connection
,I/DBG_DM  ( 3868): [com.wssyncmldm.XDMService(1111/IlIlllIIlIlIIIlIlIll)] WiFi network Connected : false
,E/Zygote  ( 7522): MountEmulatedStorage()
I/libpersona( 7522): KNOX_SDCARD checking this for 1000
E/Zygote  ( 7522): v2
I/libpersona( 7522): KNOX_SDCARD not a persona
,I/ActivityManager(  875): Start proc com.sec.pcw.device for broadcast com.sec.pcw.device/.receiver.SYSTEMReceiver: pid=7522 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,D/ConnectivityService(  875): returning getNetworkInfo(networkType - 7) :[type: BLUETOOTH[] - BLUETOOTH, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/SELinux ( 7522): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
I/DBG_DM  ( 3868): [com.wssyncmldm.XDMService(1125/lllllIlIlIIIIIIIIlIl)] Bluetooth Data Connected : false
,I/SELinux ( 7522): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 7522): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 7522): TimaSignature is unavailable
,D/ActivityThread( 7522): Added TimaKeyStore provider
,D/ResourcesManager( 7522): creating new AssetManager and set to /system/priv-app/PCWClientS18/PCWClientS18.apk
,I/PCWCLIENTTRACE_LOG( 7522): DEFAULT_LOGON : true
,I/PCWCLIENTTRACE_LOG( 7522): DEFAULT_LOGLEVEL : 3
I/PCWCLIENTTRACE_DMDBOpenHelper( 7522): new DMDBOpenHelper instance
,I/PCWCLIENTTRACE_PushUtil( 7522): SPPPushClient is installed : true
,I/PCWCLIENTTRACE_PushUtil( 7522): sales region : global
I/PCWCLIENTTRACE_PushUtil( 7522): getPushTypeList : [SPP, GCM]
I/PCWCLIENTTRACE_SYSTEMReceiver( 7522): [onReceive] - android.net.conn.CONNECTIVITY_CHANGE
,I/PCWCLIENTTRACE_SYSTEMReceiver( 7522): noConnectivity : true
,E/ActivityManager(  875): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  875): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  875): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  875): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 7539): MountEmulatedStorage()
E/Zygote  ( 7539): v2
I/libpersona( 7539): KNOX_SDCARD checking this for 10126
I/libpersona( 7539): KNOX_SDCARD not a persona
,I/ActivityManager(  875): Start proc com.google.android.music:main for broadcast com.google.android.music/.homewidgets.IFLWidgetProvider: pid=7539 uid=10126 gids={50126, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  875): Killing 6463:com.samsung.android.app.galaxyfinder/u0a34 (adj 15): bgCount ##41
,I/SELinux ( 7539): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 7539): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
E/SELinux ( 7539): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 7539): TimaSignature is unavailable
,D/ActivityThread( 7539): Added TimaKeyStore provider
,D/ResourcesManager( 7539): creating new AssetManager and set to /system/app/Music2/Music2.apk
,W/libprocessgroup(  875): failed to open /acct/uid_10034/pid_6463/cgroup.procs: No such file or directory
,I/MusicStore( 7539): Database version: 104
,D/ResourcesManager( 7539): creating new AssetManager and set to /data/app/com.google.android.gms-1/base.apk
,W/ResourcesManager( 7539): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,W/ResourcesManager( 7539): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,V/JNIHelp ( 7539): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
,W/ActivityThread( 7539): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,W/System  ( 7539): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@3d29b8d8: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 7539): Installed default security provider GmsCore_OpenSSL
,D/AndroidMusic( 7539): GMSCore installation verified
,I/ConfigStore( 7539): Config Database version: 1
,E/Vold    (  248): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.music/files/
W/Vold    (  248): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7539): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.music/files
,E/Vold    (  248): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.music/files/
W/Vold    (  248): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7539): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.music/files
,E/Vold    (  248): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.music/files/
W/Vold    (  248): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7539): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.music/files
,D/WifiDisplayAdapter(  875): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,D/WifiDisplayAdapter(  875): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,V/AudioPolicyManager(  293): getOutputsForDevice device 0002 -> 0002
,I/AudioService(  875): getStreamVolume 3 index 70
I/MediaRouter( 7539): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=7, volumeMax=15, presentationDisplayId=-1, extras=null, providerPackageName=android }
,I/wpa_supplicant( 1281): nl80211: Received scan results (3 BSSes)
,I/wpa_supplicant( 1281): wlan0: Setting scan request: 8 sec 0 usec
I/wpa_supplicant( 1281): Trying to associate with C0.AA.48 (SSID='4E47373030' freq=2412 MHz)
I/wpa_supplicant( 1281): wlan0: State: SCANNING -> ASSOCIATING
I/wpa_supplicant( 1281): CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00.00.00 SSID=
,E/WifiStateMachine(  875): [1,450,109,348,433 ms] noteScanEnd no scan source
,E/WifiStateMachine(  875): wifi setScanResults statecom.android.server.wifi.WifiStateMachine$DisconnectedState@ee0888e sup_state=SCANNING debouncing=false
,E/WifiStateMachine(  875): SUPPLICANT_STATE_CHANGE_EVENT state=ASSOCIATING -> state= CONNECTING debouncing=false
E/WifiStateMachine(  875): setDetailed state, old =SCANNING and new state=CONNECTING hidden=false
E/WifiStateMachine(  875): setDetailed state send new extra info0x
,D/SecContentProvider2(  875): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2(  875): mCursor = null
,I/CLocInfoService(  875): External Intent Received android.net.wifi.SCAN_RESULTS
,E/ActivityManager(  875): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  875): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  875): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  875): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 7569): MountEmulatedStorage()
,E/Zygote  ( 7569): v2
I/libpersona( 7569): KNOX_SDCARD checking this for 10002
I/libpersona( 7569): KNOX_SDCARD not a persona
,I/ActivityManager(  875): Start proc com.sec.android.cloudagent for broadcast com.sec.android.cloudagent/.detector.DetectorReceiver: pid=7569 uid=10002 gids={50002, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/SELinux ( 7569): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 7569): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 7569): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/WifiDisplayAdapter(  875): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,D/ConnectivityService(  875): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/NetworkMonitor( 7539): type=WIFI subType= reason=null isConnected=false
,I/ActivityManager(  875): Killing 4782:com.sec.android.app.shealth/u0a35 (adj 15): bgCount ##41
,D/TimaKeyStoreProvider( 7569): TimaSignature is unavailable
,D/ActivityThread( 7569): Added TimaKeyStore provider
,D/ResourcesManager( 7569): creating new AssetManager and set to /system/priv-app/CloudAgent/CloudAgent.apk
,I/wpa_supplicant( 1281): wlan0: State: ASSOCIATING -> ASSOCIATED
I/wpa_supplicant( 1281): CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00.00.00 SSID=4E47373030
,I/wpa_supplicant( 1281): Associated with C0.AA.48
,E/WifiStateMachine(  875): SUPPLICANT_STATE_CHANGE_EVENT state=ASSOCIATED -> state= CONNECTING debouncing=false
E/WifiStateMachine(  875): setDetailed state, old =CONNECTING and new state=CONNECTING hidden=false
,D/SecContentProvider2(  875): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2(  875): mCursor = null
,I/wpa_supplicant( 1281): wlan0: State: ASSOCIATED -> 4WAY_HANDSHAKE
I/wpa_supplicant( 1281): CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=C0.AA.48 SSID=4E47373030
,E/WifiStateMachine(  875): SUPPLICANT_STATE_CHANGE_EVENT state=FOUR_WAY_HANDSHAKE -> state= AUTHENTICATING debouncing=false
E/WifiStateMachine(  875): setDetailed state, old =CONNECTING and new state=AUTHENTICATING hidden=false
,E/WifiStateMachine(  875): setDetailed state send new extra info"NG700"
,D/SecContentProvider2(  875): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2(  875): mCursor = null
,I/wpa_supplicant( 1281): wlan0: State: 4WAY_HANDSHAKE -> 4WAY_HANDSHAKE
,I/wpa_supplicant( 1281): wlan0: State: 4WAY_HANDSHAKE -> GROUP_HANDSHAKE
I/wpa_supplicant( 1281): CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=C0.AA.48 SSID=4E47373030
,E/WifiStateMachine(  875): SUPPLICANT_STATE_CHANGE_EVENT state=GROUP_HANDSHAKE -> state= AUTHENTICATING debouncing=false
E/WifiStateMachine(  875): setDetailed state, old =AUTHENTICATING and new state=AUTHENTICATING hidden=false
,I/wpa_supplicant( 1281): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
I/wpa_supplicant( 1281): wlan0: State: GROUP_HANDSHAKE -> COMPLETED
I/wpa_supplicant( 1281): CTRL-EVENT-CONNECTED - Connection to C0.AA.48 completed (auth) [id=0 id_str=]
,I/wpa_supplicant( 1281): Blacklist: Clear (temp) 
I/wpa_supplicant( 1281): CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=C0.AA.48 SSID=4E47373030
,E/WifiStateMachine(  875): Network connection established
,D/WifiNative-HAL(  875): callSECApiVoid - ID [50]
,E/WifiStateMachine(  875): setDetailed state, old =AUTHENTICATING and new state=OBTAINING_IPADDR hidden=false
,E/WifiStateMachine(  875): setDetailed state, old =OBTAINING_IPADDR and new state=CONNECTING hidden=false
,I/CLocInfoService(  875): External Intent Received android.net.wifi.STATE_CHANGE
,D/ConnectivityService(  875): registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{false} explicitlySelected{false} }
,E/WifiStateMachine(  875): L2ConnectedState c0:ff:d4:d3:aa:48 config "NG700"WPA_PSK config.bssid any
D/ConnectivityService(  875): Got NetworkAgent Messenger
D/ConnectivityService(  875): hsengiv:checkWhatTypeOfNetwork and the value is false
,E/ConnectivityService(  875): updateNetworkInfo()
D/ConnectivityService(  875): NetworkAgentInfo [WIFI () - 503] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
,D/StatusBar.NetworkController( 1169): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020498/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020133/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020464/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
,D/ConnectivityService(  875): NetworkAgent connected
,E/WifiStateMachine(  875): L2ConnectedState "NG700" nid=0
E/WifiConfigStore(  875): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,I/ActivityManager(  875): Killing 6680:com.policydm/1000 (adj 15): bgCount ##41
E/WifiStateMachine(  875): enter ObtainingIpState netId=0 "NG700"WPA_PSK  roam=0 static=false watchdog= 1
E/WifiStateMachine(  875): ObtainingIpAddress c0:ff:d4:d3:aa:48 config "NG700"WPA_PSK config.bssid any
E/WifiStateMachine(  875): ObtainingIpAddress "NG700" nid=0
E/WifiConfigStore(  875): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,W/libprocessgroup(  875): failed to open /acct/uid_10035/pid_4782/cgroup.procs: No such file or directory
,E/ActivityManager(  875): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  875): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  875): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  875): checkUser: useridlist=null, currentuser=0
,D/CommandListener(  279): Setting iface cfg
,E/WifiStateMachine(  875): Start Dhcp Watchdog 2
,D/SecContentProvider2(  875): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2(  875): mCursor = null
,E/Zygote  ( 7592): MountEmulatedStorage()
E/Zygote  ( 7592): v2
I/libpersona( 7592): KNOX_SDCARD checking this for 1000
I/libpersona( 7592): KNOX_SDCARD not a persona
,I/ActivityManager(  875): Start proc com.sec.android.diagmonagent for broadcast com.sec.android.diagmonagent/.DiagMonRegistrationReceiver: pid=7592 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,I/WifiStateMachine(  875): CMD_RSSI_POLL : calculateWifiScore in!
E/WifiStateMachine(  875): calculateWifiScore() report new score 60
I/WifiStateMachine(  875): calculateWifiScore : sendNetworkScore in!
I/WifiStateMachine(  875): calculateWifiScore : sendNetworkScore out!
I/WifiStateMachine(  875): CMD_RSSI_POLL : calculateWifiScore out!
I/WifiStateMachine(  875): CMD_RSSI_POLL : out!
,D/ConnectivityService(  875): updateNetworkScore for NetworkAgentInfo [WIFI () - 503] to 60
,E/WifiStateMachine(  875): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576} new: {InterfaceName: wlan0 LinkAddresses: []  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0}
,E/WifiStateMachine(  875): updateLinkProperties nid: 0 state: CONNECTING reason: CMD_UPDATE_LINKPROPERTIES
D/ConnectivityService(  875): Update of LinkProperties for NetworkAgentInfo [WIFI () - 503]; created=false
,I/SELinux ( 7592): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 7592): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 7592): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,W/libprocessgroup(  875): failed to open /acct/uid_1000/pid_6680/cgroup.procs: No such file or directory
,D/TimaKeyStoreProvider( 7592): TimaSignature is unavailable
,D/ActivityThread( 7592): Added TimaKeyStore provider
,D/ResourcesManager( 7592): creating new AssetManager and set to /system/priv-app/DiagMonAgent/DiagMonAgent.apk
,I/DIAGMON_AGENT( 7592): [com.sec.android.diagmonagent.DiagMonAgentApplication(41/onCreate)] myUserId : 0
,I/DIAGMON_AGENT( 7592): [com.diagmondm.db.file.XDB(374/llIlIIIIlIIIIIlIlIII)] 
,E/WifiStateMachine(  875): setSuspendOptimizationsNative: 1 false -want true stack:setSuspendOptimizationsNative - handlePreDhcpSetup - processMessage - processMsg
E/native  (  875): do suspend false
,D/SecContentProvider2(  875): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2(  875): mCursor = null
,D/WifiP2pService(  875): InactiveState{ what=143375 }
D/WifiP2pService(  875): P2pEnabledState{ what=143375 }
,I/DIAGMON_AGENT( 7592): [com.sec.android.diagmonagent.DiagMonAgentApplication(61/onCreate)] nStatus : 0
,I/DIAGMON_AGENT( 7592): [com.sec.android.diagmonagent.DiagMonAgentApplication(78/onCreate)] DiagMon DM Application Start !
,I/DIAGMON_AGENT( 7592): [lIIllllllllIlIlIllll(17/llIIIIlllllIIllIIllI)] Receive broadcast: android.net.conn.CONNECTIVITY_CHANGE
,I/DIAGMON_AGENT( 7592): [lIIllllllllIlIlIllll(31/llIIIIlllllIIllIIllI)] Running with RegistrationReceiver
,E/ActivityManager(  875): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  875): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  875): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  875): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 7608): MountEmulatedStorage()
,E/Zygote  ( 7608): v2
I/libpersona( 7608): KNOX_SDCARD checking this for 10011
I/libpersona( 7608): KNOX_SDCARD not a persona
,I/ActivityManager(  875): Start proc com.sec.android.fotaclient for content provider com.sec.android.fotaclient/.log.MasterLogProvider: pid=7608 uid=10011 gids={50011, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/SELinux ( 7608): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 7608): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 7608): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 7608): TimaSignature is unavailable
,D/ActivityThread( 7608): Added TimaKeyStore provider
,D/ResourcesManager( 7608): creating new AssetManager and set to /system/priv-app/FotaClient/FotaClient.apk
,E/dhcpcd  ( 7623): fopen `/system/etc/dhcpcd/dhcpcd.conf': No such file or directory
,I/dhcpcd  ( 7623): version 5.5.6 starting
,E/dhcpcd  ( 7623): fopen `/system/etc/dhcpcd/dhcpcd.conf': No such file or directory
,I/ActivityManager(  875): Killing 5260:com.sec.spp.push/u0a38 (adj 15): bgCount ##41
,I/FOTA_Client( 7608): [com.sec.android.fotaclient.FotaRegisterReceiver(113/onReceive)] Already device registered...
,I/FOTA_Client( 7608): [com.sec.android.fotaclient.FotaUpdaterReceiver(103/onReceive)] Auto update settings is activated
,I/FOTA_Client( 7608): [lllllllllllIlllllIIl(197/lllIlIlIIIllIIlIllIl)] Polling time is vaild
,I/FOTA_Client( 7608): [com.sec.android.fotaclient.FotaUpdaterReceiver(126/onReceive)] Heartbeat settings is activated.
,I/FOTA_Client( 7608): [llIlIIIIlllIlllllIll(125/llIlIIIIlIIIIIlIlIII)] heartbeat time is vaild
,E/ActivityManager(  875): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  875): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  875): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  875): checkUser: useridlist=null, currentuser=0
,I/dhcpcd  ( 7623): wlan0: sending IPv6 Router Solicitation
E/dhcpcd  ( 7623): wlan0: sendmsg: Cannot assign requested address
I/dhcpcd  ( 7623): if(wlan0) info get Success. (MAC : C0.AA.48)
I/dhcpcd  ( 7623): bssid match
,I/dhcpcd  ( 7623): wlan0: rebinding lease of 192.168.1.135
,E/Zygote  ( 7630): MountEmulatedStorage()
E/Zygote  ( 7630): v2
I/libpersona( 7630): KNOX_SDCARD checking this for 10019
I/libpersona( 7630): KNOX_SDCARD not a persona
,I/ActivityManager(  875): Start proc com.samsung.klmsagent for broadcast com.samsung.klmsagent/.listner.MainReciver: pid=7630 uid=10019 gids={50019, 9997, 3003} abi=armeabi-v7a
,I/ActivityManager(  875): Killing 5905:com.samsung.android.sdk.samsunglink/u0a42 (adj 15): bgCount ##41
,I/SELinux ( 7630): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
I/SELinux ( 7630): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
E/SELinux ( 7630): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 7630): TimaSignature is unavailable
,D/ActivityThread( 7630): Added TimaKeyStore provider
,W/libprocessgroup(  875): failed to open /acct/uid_10038/pid_5260/cgroup.procs: No such file or directory
,W/libprocessgroup(  875): failed to open /acct/uid_10042/pid_5905/cgroup.procs: No such file or directory
,D/ResourcesManager( 7630): creating new AssetManager and set to /system/priv-app/KLMSAgent/KLMSAgent.apk
,I/KLMS-2.4.503: ( 7630): KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,I/KLMS-2.4.503: ( 7630): MainReciver(): EventNotificationReciver- method called: AppActivityListner onReceive for Intent Action : android.net.conn.CONNECTIVITY_CHANGE , timestamp: 1450109349008
,I/KLMS-2.4.503: ( 7630): MainReciver(): NETWORK_STATE_CHANGED_ACTION
,D/ConnectivityService(  875): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  875): returning getNetworkInfo(networkType - 0) :[type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/KLMS-2.4.503: ( 7630): KLMSUtility(): isNetworkAvailable() - WIFI : false| MOBILE : false
,I/KLMS-2.4.503: ( 7630): StateImplV2(): networkChangeListener().END
,I/ActivityManager(  875): Killing 6700:com.osp.app.signin/u0a45 (adj 15): bgCount ##41
,E/ActivityManager(  875): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  875): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  875): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  875): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 7645): MountEmulatedStorage()
I/libpersona( 7645): KNOX_SDCARD checking this for 10037
E/Zygote  ( 7645): v2
I/libpersona( 7645): KNOX_SDCARD not a persona
,I/ActivityManager(  875): Start proc com.sec.android.soagent for broadcast com.sec.android.soagent/.RegisterReceiver: pid=7645 uid=10037 gids={50037, 9997, 3003} abi=armeabi-v7a
,I/SELinux ( 7645): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 7645): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 7645): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,W/libprocessgroup(  875): failed to open /acct/uid_10045/pid_6700/cgroup.procs: No such file or directory
,D/TimaKeyStoreProvider( 7645): TimaSignature is unavailable
,D/ActivityThread( 7645): Added TimaKeyStore provider
,D/ResourcesManager( 7645): creating new AssetManager and set to /system/priv-app/SOAgent/SOAgent.apk
,I/SO_AGENT( 7645): [com.sec.android.soagent.RegisterReceiver(98/onReceive)] Network is not available
E/SMD     (  287): DCD ON
,E/ActivityManager(  875): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  875): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  875): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  875): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 7660): MountEmulatedStorage()
,E/Zygote  ( 7660): v2
I/libpersona( 7660): KNOX_SDCARD checking this for 1000
I/libpersona( 7660): KNOX_SDCARD not a persona
,I/ActivityManager(  875): Start proc com.policydm for broadcast com.policydm/.XDMBroadcastReceiver: pid=7660 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,I/ActivityManager(  875): Killing 6748:com.sec.android.provider.badge/u0a78 (adj 15): bgCount ##41
,I/SELinux ( 7660): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 7660): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 7660): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,W/libprocessgroup(  875): failed to open /acct/uid_10078/pid_6748/cgroup.procs: No such file or directory
,D/TimaKeyStoreProvider( 7660): TimaSignature is unavailable
,D/ActivityThread( 7660): Added TimaKeyStore provider
,D/ResourcesManager( 7660): creating new AssetManager and set to /system/priv-app/SPDClient/SPDClient.apk
,D/ConnectivityService(  875): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  875): returning getNetworkInfo(networkType - 0) :[type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/ActivityManager(  875): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  875): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  875): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  875): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 7680): MountEmulatedStorage()
E/Zygote  ( 7680): v2
I/libpersona( 7680): KNOX_SDCARD checking this for 10038
I/libpersona( 7680): KNOX_SDCARD not a persona
,I/ActivityManager(  875): Start proc com.sec.spp.push for broadcast com.sec.spp.push/.monitor.SystemStateMoniter: pid=7680 uid=10038 gids={50038, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  875): Killing 6763:com.wsomacp/u0a25 (adj 15): bgCount ##41
,I/SELinux ( 7680): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
I/SELinux ( 7680): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
E/SELinux ( 7680): [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 7680): TimaSignature is unavailable
,D/ActivityThread( 7680): Added TimaKeyStore provider
,D/ConnectivityService(  875): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  875): returning getNetworkInfo(networkType - 0) :[type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ResourcesManager( 7680): creating new AssetManager and set to /system/priv-app/SPPPushClient_Prod/SPPPushClient_Prod.apk
,W/libprocessgroup(  875): failed to open /acct/uid_10025/pid_6763/cgroup.procs: No such file or directory
,E/SPPClientService( 7680): ============PushLog. commonIsShipBuild. stop!
E/SPPClientService( 7680): [PushClientApplication] Push log off : This is Ship build version
,D/SPPClientService( 7680): PushLog.txt file is not deleted.
,D/SPPClientService( 7680): PushLog.txt file is not deleted.
D/SPPClientService( 7680): ============PushLog. stop!
,E/SPPClientService( 7680): [[SystemStateMoniter]] SystemStateMonitorService : noConnect? : true
,E/ActivityManager(  875): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  875): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  875): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  875): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 7696): MountEmulatedStorage()
E/Zygote  ( 7696): v2
I/libpersona( 7696): KNOX_SDCARD checking this for 10045
I/libpersona( 7696): KNOX_SDCARD not a persona
,I/ActivityManager(  875): Start proc com.osp.app.signin for broadcast com.osp.app.signin/.OspReceiver: pid=7696 uid=10045 gids={50045, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  875): Killing 6780:com.sec.android.app.myfiles/u0a51 (adj 15): bgCount ##41
,I/SELinux ( 7696): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
I/SELinux ( 7696): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 7696): [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
,E/SPPClientService( 7680): [[SystemStateMonitorService]] No Active Internet
,D/TimaKeyStoreProvider( 7696): TimaSignature is unavailable
W/libprocessgroup(  875): failed to open /acct/uid_10051/pid_6780/cgroup.procs: No such file or directory
,D/ActivityThread( 7696): Added TimaKeyStore provider
,D/ResourcesManager( 7696): creating new AssetManager and set to /system/priv-app/Samsungservice2_xxhdpi/Samsungservice2_xxhdpi.apk
,I/SA      ( 7696): [SSP] onCreated
,I/SA      ( 7696): [TPM] There is no property file
,I/SA      ( 7696): [SCU] isHaveSA() - false
,I/SA      ( 7696): [TPM] getModelProperty : null
,I/SA      ( 7696): [TPM] getCSCProperty : null
,I/SA      ( 7696): [DM] init START
,I/SA      ( 7696): [DM] This device is not a Vodafone
,W/ResourceType( 7696): Failure getting entry for 0x7f06000f (t=5 e=15) (error -75)
,W/ResourceType( 7696): Failure getting entry for 0x7f060007 (t=5 e=7) (error -75)
W/ResourceType( 7696): Failure getting entry for 0x7f060008 (t=5 e=8) (error -75)
,W/ResourceType( 7696): Failure getting entry for 0x7f06000b (t=5 e=11) (error -75)
W/ResourceType( 7696): Failure getting entry for 0x7f06000c (t=5 e=12) (error -75)
W/ResourceType( 7696): Failure getting entry for 0x7f060001 (t=5 e=1) (error -75)
,W/ResourceType( 7696): Failure getting entry for 0x7f060013 (t=5 e=19) (error -75)
,W/ResourceType( 7696): No package identifier when getting value for resource number 0x00000000
,W/ResourceType( 7696): Failure getting entry for 0x7f060022 (t=5 e=34) (error -75)
W/ResourceType( 7696): Failure getting entry for 0x7f060023 (t=5 e=35) (error -75)
,W/ResourceType( 7696): Failure getting entry for 0x7f060024 (t=5 e=36) (error -75)
W/ResourceType( 7696): Failure getting entry for 0x7f060025 (t=5 e=37) (error -75)
,W/ResourceType( 7696): Failure getting entry for 0x7f060026 (t=5 e=38) (error -75)
,W/ResourceType( 7696): No package identifier when getting value for resource number 0x00000000
W/ResourceType( 7696): Failure getting entry for 0x7f060010 (t=5 e=16) (error -75)
,W/ResourceType( 7696): Failure getting entry for 0x7f060009 (t=5 e=9) (error -75)
W/ResourceType( 7696): Failure getting entry for 0x7f06000a (t=5 e=10) (error -75)
,W/ResourceType( 7696): Failure getting entry for 0x7f060002 (t=5 e=2) (error -75)
W/ResourceType( 7696): Failure getting entry for 0x7f060014 (t=5 e=20) (error -75)
W/ResourceType( 7696): Failure getting entry for 0x7f060015 (t=5 e=21) (error -75)
,I/SA      ( 7696): [SCU] isHaveSA() - false
I/SA      ( 7696): support phone number id : false
,I/SA      ( 7696): [DM] init END
I/SA      ( 7696): [OR] onReceive log=[SA = 2.1.0142 V = 21 HWD = 1920X1080 3.0 dpi = 480  SIZE = 2 LOCALE = en_US CSC = DBT MCC = 0 MNC 0 T = user DEVICE = klte P = kltexx I = LRX21T M = SM-G900F OKLEFT false DIS LRX21T.G900FXXU1BOD3 PSS = 5.219788042639568  ]
,I/SA      ( 7696): [OR] onReceive Intent=[ conn.CONNECTIVITY_CHANGE. networkInfo:[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] networkType:1 inetCondition:0 extraInfo:? noConnectivity:true ]
I/SA      ( 7696): [OR] == ACTION_CONNECTIVITY_CHANGE ==
,I/SA      ( 7696): [SLFUCHKMGR] constructor called
,I/SA      ( 7696): [TPMU]  strSIMState 	:SIM_STATE_UNKNOWN
I/SA      ( 7696): [OR] == isSIMCardReady false ==
,I/SA      ( 7696): [SCU] == networkStateCheck == false
I/SA      ( 7696): [OR] onReceive END
,I/ActivityManager(  875): Killing 6797:com.sec.android.app.soundalive/u0a58 (adj 15): bgCount ##41
,D/accuweather( 7215): [KK AccuPhone]>>> WC:30 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,D/accuweather( 7215): [KK AccuPhone]>>> WC:37 [0:0] oR : create UI manager : start
,D/accuweather( 7215): [KK AccuPhone]>>> UIMEM:90 [0:0] getInstance
,D/accuweather( 7215): [KK AccuPhone]>>> UIMEM:78 [0:0] UIManager : create ui manager
D/accuweather( 7215): [KK AccuPhone]>>> RM:73 [0:0] RefreshManager : create
D/accuweather( 7215): [KK AccuPhone]>>> RM:136 [0:0]  V init 
,W/libprocessgroup(  875): failed to open /acct/uid_10058/pid_6797/cgroup.procs: No such file or directory
,D/daemonapp( 1370): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/accuweather( 7215): [KK AccuPhone]>>> RM:128 [0:0] updateCityList
,D/daemonapp( 1370): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/weatherinfo
,D/accuweather( 7215): [KK AccuPhone]>>> DBH:3354 [0:0] gADWI : count = 0
,D/daemonapp( 1370): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/accuweather( 7215): [KK AccuPhone]>>> UIMEM:106 [0:0] The widget does not exist in idle!!
,D/accuweather( 7215): [KK AccuPhone]>>> UIMEM:106 [0:0] The widget does not exist in idle!!
,E/ActivityManager(  875): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  875): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  875): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  875): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 7717): MountEmulatedStorage()
E/Zygote  ( 7717): v2
I/libpersona( 7717): KNOX_SDCARD checking this for 1000
I/libpersona( 7717): KNOX_SDCARD not a persona
,I/SELinux ( 7717): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/ActivityManager(  875): Start proc com.sec.knox.bridge for broadcast com.sec.knox.bridge/.knoxusage.KnoxUsageReceiver: pid=7717 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,I/SELinux ( 7717): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 7717): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 7717): TimaSignature is unavailable
,I/art     (  324): Explicit concurrent mark sweep GC freed 8759(372KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 14MB/23MB, paused 268us total 12.902ms
D/ActivityThread( 7717): Added TimaKeyStore provider
,I/art     (  324): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 14MB/23MB, paused 252us total 8.399ms
,D/ResourcesManager( 7717): creating new AssetManager and set to /system/app/Bridge/Bridge.apk
,I/art     (  324): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 14MB/23MB, paused 256us total 8.176ms
,W/ResourcesManager( 7717): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,D/PowerManagerService(  875): [s] UserActivityState : 1 -> 2
D/DisplayPowerController(  875): getFinalBrightness : 1 -> 1
,D/PowerManagerService(  875): [s] DisplayPowerCallbacks : onStateChanged()
,I/KnoxUsageLogPro( 7717): KnoxUsageReceiver onReceive :android.net.conn.CONNECTIVITY_CHANGE myUserId=0
,D/lights  (  875): lcd : 2 +
,I/KnoxUsageLogPro( 7717): premStatus:2
,I/KnoxUsageLogPro( 7717): isEulaShown : false
I/KnoxUsageLogPro( 7717): KnoxUsageReceiver onReceive : not Processible, just return
,D/lights  (  875): lcd : 2 -
,E/ActivityManager(  875): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  875): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  875): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  875): checkUser: useridlist=null, currentuser=0
,D/DisplayPowerController(  875): getFinalBrightness : 1 -> 1
D/lights  (  875): lcd : 1 +
,E/Zygote  ( 7732): MountEmulatedStorage()
E/Zygote  ( 7732): v2
I/libpersona( 7732): KNOX_SDCARD checking this for 10088
I/libpersona( 7732): KNOX_SDCARD not a persona
,I/ActivityManager(  875): Start proc com.android.chrome for broadcast com.android.chrome/com.google.android.apps.chrome.precache.PrecacheServiceLauncher: pid=7732 uid=10088 gids={50088, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  875): Killing 6138:com.samsung.android.app.assistantmenu/1000 (adj 15): bgCount ##41
,D/lights  (  875): lcd : 1 -
D/DisplayPowerController(  875): getFinalBrightness : 1 -> 1
,I/SELinux ( 7732): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 7732): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 7732): [DEBUG] get_category: variable seinfo: chrome sensitivity: NULL, cateogry: NULL
,W/libprocessgroup(  875): failed to open /acct/uid_1000/pid_6138/cgroup.procs: No such file or directory
,D/TimaKeyStoreProvider( 7732): TimaSignature is unavailable
,D/ActivityThread( 7732): Added TimaKeyStore provider
,D/ResourcesManager( 7732): creating new AssetManager and set to /system/app/Chrome/Chrome.apk
,I/ActivityManager(  875): Killing 6823:com.google.android.apps.docs/u0a98 (adj 15): bgCount ##41
,D/Headlines( 5507): HeadlinesSystemBroadcastReceiver onReceive android.net.conn.CONNECTIVITY_CHANGE
,D/HeadlinesChannelUtil( 5507): getCountryCode(): countryCode = DE
,D/Headlines( 5507): Breath.onStartCommand : com.samsung.android.internal.headlines.UPDATE_WELCOME_CARD flag : 0
,D/HeadlinesCardManager( 5507): updateCategory : HeadlinesCardManager:updateCategory() category size == 0
E/ActivityManager(  875): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  875): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  875): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  875): checkUser: useridlist=null, currentuser=0
,D/HeadlinesCardManager( 5507): updateCategory : HeadlinesCardManager:updateCategory() try to query category list
D/Headlines( 5507): queryCategory.  mRequest is not initialized.
,D/HeadlinesCardManager( 5507): updateCategory : HeadlinesCardManager:updateCategory() reponse : false
,D/HeadlinesCardManager( 5507): requestUpdateNewsWelcomeCard : request update welcome card to content card.
D/HeadlinesDataCenter( 5507): requestUpdateNewsWelcomeCard !!! no welcome card
,E/Zygote  ( 7751): MountEmulatedStorage()
E/Zygote  ( 7751): v2
I/libpersona( 7751): KNOX_SDCARD checking this for 10128
I/libpersona( 7751): KNOX_SDCARD not a persona
,I/ActivityManager(  875): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=7751 uid=10128 gids={50128, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/SELinux ( 7751): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 7751): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 7751): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 7751): TimaSignature is unavailable
,D/ActivityThread( 7751): Added TimaKeyStore provider
,W/libprocessgroup(  875): failed to open /acct/uid_10098/pid_6823/cgroup.procs: No such file or directory
,D/ResourcesManager( 7751): creating new AssetManager and set to /system/app/Newsstand/Newsstand.apk
,I/dhcpcd  ( 7623): wlan0: acknowledged 192.168.1.135 from 192.168.1.1
,I/dhcpcd  ( 7623): wlan0: leased 192.168.1.135 for 86400 seconds
,E/WifiStateMachine(  875): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: []  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576} new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.135/24,]  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0}
,D/ConnectivityService(  875): Update of LinkProperties for NetworkAgentInfo [WIFI () - 503]; created=false
,E/WifiStateMachine(  875): updateLinkProperties nid: 0 state: CONNECTING reason: CMD_UPDATE_LINKPROPERTIES v4
,E/Vold    (  248): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  248): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7751): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache
,E/Vold    (  248): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  248): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7751): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/files
,E/Vold    (  248): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  248): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7751): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache
,E/Vold    (  248): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  248): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7751): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/files
,E/WifiStateMachine(  875): setSuspendOptimizationsNative: 1 true -want true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - processMessage - processMsg
,D/WifiP2pService(  875): InactiveState{ what=143375 }
D/WifiP2pService(  875): P2pEnabledState{ what=143375 }
,E/WifiStateMachine(  875): WifiStateMachine DHCP successful
,E/WifiStateMachine(  875): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: [192.168.1.135/24,]  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576} new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.135/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0}
,D/ConnectivityService(  875): Update of LinkProperties for NetworkAgentInfo [WIFI () - 503]; created=false
E/WifiStateMachine(  875): updateLinkProperties nid: 0 state: CONNECTING reason: DHCP_SUCCESS v4 v4r v4dns isprov
,D/StatusBar.NetworkController( 1169): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020498/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020133/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020464/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
,E/WifiStateMachine(  875): WifiStateMachine: handleSuccessfulIpConfiguration and no scan results"NG700"WPA_PSK
D/WifiStateMachine(  875): Not connected state, yet.
E/WifiStateMachine(  875): VerifyingLinkState enter
,I/WebViewFactory( 7751): Loading com.google.android.webview version 37 (1726107-arm) (code 119201)
D/WifiStateMachine(  875): updatePoorNetworkAvoidance - Poor Network Test Enabled / !mIsFmcNetwork : false / true - mPoorNetworkAvoidanceEnabled:disabled
D/WifiStateMachine(  875): updatePoorNetworkDetection - Airplane Mode Off / Mobile Data Enabled / SIM State-Ready / MobilePolicyDataDisabled / !mIsFmcNetwork : 
D/WifiStateMachine(  875): false / true / false / true / true - mPoorNetworkDetectionEnabled: disabled
D/WifiNative-HAL(  875): callSECApiInt - ID [210]
,E/WifiStateMachine(  875): setDetailed state, old =CONNECTING and new state=VERIFYING_POOR_LINK hidden=false
D/ResourcesManager( 7751): creating new AssetManager and set to /system/app/WebViewGoogle/WebViewGoogle.apk
E/ConnectivityService(  875): updateNetworkInfo()
,D/ConnectivityService(  875): updateLinkProperties: newLp = {InterfaceName: wlan0 LinkAddresses: [192.168.1.135/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}
D/ConnectivityService(  875): Adding iface wlan0 to network 503
,I/CLocInfoService(  875): External Intent Received android.net.wifi.STATE_CHANGE
D/WifiWatchdogStateMachine(  875): updateDnsLinkProperty: enter
D/WifiWatchdogStateMachine.DnsPinger(  875): setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.135/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}
D/WifiWatchdogStateMachine.DnsResolver(  875): setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.135/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}
,D/WifiWatchdogStateMachine.SingDnsChecker(  875): setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.135/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}
D/WifiWatchdogStateMachine.CaptivePortalDnsResolver(  875): setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.135/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}
,D/StatusBar.NetworkController( 1169): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020498/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020133/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020464/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
,I/LibraryLoader( 7751): Loading: webviewchromium
,E/WifiStateMachine(  875): VerifyingLinkState GOOD_LINK_DETECTED: transition to (new) connected (old)captive portal check
D/WifiStateMachine(  875): Now, connected state.
E/WifiStateMachine(  875): setDetailed state, old =VERIFYING_POOR_LINK and new state=CAPTIVE_PORTAL_CHECK hidden=false
,E/WifiStateMachine(  875): setDetailed state, old =CAPTIVE_PORTAL_CHECK and new state=CONNECTED hidden=false
I/WifiTrafficPoller(  875): evaluateTrafficStatsPolling
I/LibraryLoader( 7751): Time to load native libraries: 6 ms (timestamps 1485-1491)
I/LibraryLoader( 7751): Expected native library version number "",actual native library version number ""
I/CLocInfoService(  875): External Intent Received android.net.wifi.STATE_CHANGE
,E/WifiStateMachine(  875): Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,I/WifiTrafficPoller(  875): evaluateTrafficStatsPolling
I/WifiTrafficPoller(  875): mBoosterFLAG : 0
I/WifiTrafficPoller(  875): current booster mode : FullMode
D/WifiNative-HAL(  875): callSECApiVoid - ID [212]
,D/ConnectivityService(  875): Adding Route [fe80::/64 -> :: wlan0] to network 503
I/CLocInfoService(  875): External Intent Received android.net.wifi.STATE_CHANGE
,D/StatusBar.NetworkController( 1169): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020498/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020133/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020464/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
,D/ConnectivityService(  875): Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 503
,D/ConnectivityService(  875): Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 503
,D/StatusBar.NetworkController( 1169): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020498/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020133/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020464/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
,E/ConnectivityService(  875): Unexpected mtu value: 0, wlan0
D/ConnectivityService(  875): updateSourceRoutes : add source routing for type : 1
,D/ConnectivityService(  875): updateSourceRoutes : add src route for:192.168.1.135
V/        (  279): QcRouteController
E/WifiStateMachine(  875): ConnectedState Enter  mScreenOn=true scanperiod=20000
,D/StatusBar.NetworkController( 1169): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02012b/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020466/com.android.systemui:drawable/stat_sys_signal_inout mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
D/StatusBar.NetworkController( 1169): refreshSignalCluster - setNWBoosterIndicators(false)
I/WifiStateMachine(  875): REQUEST_POWER_SAVE_ON
,D/StatusBar.NetworkController( 1169): applyOpen
,D/StatusBar.NetworkController( 1169): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1169): applyOpen
,D/StatusBar.NetworkController( 1169): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1169): applyOpen
D/StatusBar.NetworkController( 1169): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1169): applyOpen
,V/WebViewChromiumFactoryProvider( 7751): Binding Chromium to main looper Looper (main, tid 1) {2f11e9ec}
,I/LibraryLoader( 7751): Expected native library version number "",actual native library version number ""
,I/chromium( 7751): [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
,V/        (  279): QcRouteController
,V/        (  279): QcRouteController
,V/        (  279): QcRouteController
,I/BrowserStartupController( 7751): Initializing chromium process, renderers=0
,W/art     ( 7751): Attempt to remove local handle scope entry from IRT, ignoring
,V/        (  279): QcRouteController
,V/        (  279): QcRouteController
,V/        (  279): QcRouteController
,W/chromium( 7751): [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
,I/chromium( 7751): [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=41 off=46768 len=2953
,I/chromium( 7751): [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:42 off:229524 len:643667
,W/AudioManagerAndroid( 7751): Requires BLUETOOTH permission
,V/        (  279): QcRouteController
,I/Adreno-EGL( 7751): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 7751): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 7751): Build Date: 03/03/15 Tue
I/Adreno-EGL( 7751): Local Branch: LA.BF.1.1_RB1_20150108_025_1077123_1158499
I/Adreno-EGL( 7751): Remote Branch: 
I/Adreno-EGL( 7751): Local Patches: 
I/Adreno-EGL( 7751): Reconstruct Branch: 
,D/ConnectivityService(  875): Setting Dns servers for network 503 to [/192.168.1.1]
,D/Nat464Xlat(  875): requiresClat: netType=1, connected=false, hasIPv4Address=true
D/ConnectivityService(  875): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 503]
E/ConnectivityService(  875): updateNetworkInfo()
D/ConnectivityService(  875): calling update connectivity
E/ConnectivityService(  875): updateNetworkInfo()
D/ConnectivityService(  875): ignoring duplicate network state non-change
D/ConnectivityService(  875): ignoring duplicate network state non-change
D/ConnectivityService(  875): NetworkAgentInfo [WIFI () - 503] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityService(  875): notifyType PRECHECK for NetworkAgentInfo [WIFI () - 503]
D/ConnectivityService(  875): calling update connectivity
,D/ConnectivityService(  875): rematching NetworkAgentInfo [WIFI () - 503]
D/ConnectivityService(  875):  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityService(  875):   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  875):   checking if request is satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  875): currentScore = 0, newScore = 60
D/ConnectivityService(  875):    accepting network in place of null
D/ConnectivityService(  875): sending new Min Network Score(60): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  875): DefaultState{ when=-1ms what=532481 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  875): Connected
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  875): EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  875): Validated
,D/TelephonyNetworkFactory( 1457): Cellular releasing Network for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,E/CSLegacyTypeTracker(  875): add() : Adding agent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{503}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.135/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{true} explicitlySelected{false} } for legacy network type 1
D/CSLegacyTypeTracker(  875): Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 503] isDefaultNetwork=true
D/ConnectivityService(  875): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,D/ConnectivityService(  875): sendStickyBroadcastDelayed: delayMs=500, action=android.net.conn.CONNECTIVITY_CHANGE
,D/ConnectivityService(  875): Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{503}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.135/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{true} explicitlySelected{false} }
,D/SmartBondingService(  875): SmartBondingReceiver: onReceive action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,D/SmartBondingService(  875): EVENT_UPDATE_SB_STATE called / mDisableBySIOP false
D/EntConnectivity(  875): Not allowed due to - mEnabled false
D/ConnectivityService(  875): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 503]
D/ConnectivityService(  875): calling update connectivity
D/ConnectivityService(  875):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  875):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
,D/SmartBondingService(  875): getSBEnabled() enabled =false
D/ConnectivityService(  875): sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
V/NetworkStats(  875): updateIfacesLocked()
V/NetworkStats(  875): performPollLocked(flags=0x1)
D/ConnectivityManager.CallbackHandler( 1169): CM callback handler got msg 524290
,D/SmartBondingService(  875): getSBEnabled() enabled =false
D/NetworkStatsFactory(  875): UpdateStatsForKnox
D/ConnectivityService(  875): Validated NetworkAgentInfo [WIFI () - 503]
D/ConnectivityService(  875): rematching NetworkAgentInfo [WIFI () - 503]
D/ConnectivityService(  875):  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityService(  875): returning getNetworkInfo(networkType - 28) :[type: MOBILE_ENT1[] - MOBILE_ENT1, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/ConnectivityService(  875):   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  875): Network NetworkAgentInfo [WIFI () - 503] was already satisfying request 1. No change.
D/ConnectivityService(  875): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 503]
D/ConnectivityService(  875): calling update connectivity
D/ConnectivityService(  875):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  875):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
,D/SmartBondingService(  875): getSBEnabled() enabled =false
D/NtpTrustedTime(  875): forceRefresh() from cache miss
D/SmartBondingService(  875): getNetworkEnabled : wifi : true mobile : true
V/NetworkStats(  875): performPollLocked() took 4ms
D/ConnectivityService(  875): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/StatusBar.NetworkController( 1169): getUpdateDataNetType(): 0
D/StatusBar.NetworkController( 1169): updateDataNetType()
D/StatusBar.NetworkController( 1169): NoService, mRoamingIconId = 0
D/ConnectivityService(  875): sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityManager.CallbackHandler( 1169): CM callback handler got msg 524290
D/StatusBar.NetworkController( 1169): updateDataIcon, mDataDirectionIconId = (null) mDataConnected = false
D/StatusBar.NetworkController( 1169): updateTelephonySignalStrength: hasService=false ss=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte
D/StatusBar.NetworkController( 1169): updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal
D/StatusBar.NetworkController( 1169): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02012b/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020466/com.android.systemui:drawable/stat_sys_signal_inout mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
D/StatusBar.NetworkController( 1169): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1169): applyOpen
D/StatusBar.NetworkController( 1169): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1169): applyOpen
D/StatusBar.NetworkController( 1169): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1169): applyOpen
D/StatusBar.NetworkController( 1169): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1169): applyOpen
D/ConnectivityService(  875): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
D/ConnectivityService(  875): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/StatusBar.NetworkController( 1169): getUpdateDataNetType(): 0
D/StatusBar.NetworkController( 1169): updateDataNetType()
D/StatusBar.NetworkController( 1169): NoService, mRoamingIconId = 0
D/StatusBar.NetworkController( 1169): updateDataIcon, mDataDirectionIconId = (null) mDataConnected = false
D/StatusBar.NetworkController( 1169): updateTelephonySignalStrength: hasService=false ss=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte
D/StatusBar.NetworkController( 1169): updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal
D/StatusBar.NetworkController( 1169): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02012b/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020466/com.android.systemui:drawable/stat_sys_signal_inout mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
,I/NSApplication( 7751): Starting up...
D/ConnectivityService(  875): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/ConnectivityService(  875): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/ConnectivityService(  875): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/NtpTrustedTime(  875): requestTime Success from server:2.android.pool.ntp.org mCachedNtpTime : 1450109350272 mCachedNtpElapsedRealtime : 101670 mCachedNtpCertainty : 11
D/ConnectivityService(  875): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/NtpTrustedTime(  875): currentTimeMillis() cache hit
D/NtpTrustedTime(  875): currentTimeMillis() cache hit
D/NtpTrustedTime(  875): currentTimeMillis() cache hit
D/NtpTrustedTime(  875): currentTimeMillis() cache hit
D/NtpTrustedTime(  875): currentTimeMillis() cache hit
D/NtpTrustedTime(  875): currentTimeMillis() cache hit
V/NetworkStats(  875): advisePersistThreshold() given 9223372036854775, clamped to 2097152
E/ActivityManager(  875): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  875): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  875): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  875): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 7853): MountEmulatedStorage()
E/Zygote  ( 7853): v2
I/libpersona( 7853): KNOX_SDCARD checking this for 10138
I/libpersona( 7853): KNOX_SDCARD not a persona
,I/ActivityManager(  875): Start proc com.samsung.android.sconnect for broadcast com.samsung.android.sconnect/.periph.PeriphStartReceiver: pid=7853 uid=10138 gids={50138, 9997, 3002, 3001, 1028, 1015, 3003} abi=armeabi-v7a
,I/ActivityManager(  875): Killing 6874:com.vlingo.midas/u0a33 (adj 15): bgCount ##41
,I/SELinux ( 7853): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 7853): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
E/SELinux ( 7853): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 7853): TimaSignature is unavailable
,D/ActivityThread( 7853): Added TimaKeyStore provider
,W/libprocessgroup(  875): failed to open /acct/uid_10033/pid_6874/cgroup.procs: No such file or directory
,D/ResourcesManager( 7853): creating new AssetManager and set to /system/app/QuickConnect/QuickConnect.apk
,W/ResourcesManager( 7853): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,W/ResourcesManager( 7853): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
W/ResourcesManager( 7853): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,D/QuickConnect( 7853): PeriphStartReceiver.onReceive - android.net.conn.CONNECTIVITY_CHANGE
,I/QuickConnect( 7853): PeriphStartReceiver.onReceive - USER_OWNER care CONNECTIVITY_ACTION. run P service
,I/QuickConnect( 7853): PeriphStartReceiver.onReceive - no need to start
,E/ActivityManager(  875): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  875): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  875): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  875): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 7868): MountEmulatedStorage()
I/libpersona( 7868): KNOX_SDCARD checking this for 10163
E/Zygote  ( 7868): v2
I/libpersona( 7868): KNOX_SDCARD not a persona
,I/ActivityManager(  875): Start proc com.android.email for broadcast com.android.email/.EmailConnectivityManager: pid=7868 uid=10163 gids={50163, 9997, 3003, 1028, 1015, 1023, 3002, 3001, 1003} abi=armeabi-v7a
,I/ActivityManager(  875): Killing 6846:com.sec.android.automotive.drivelink/u0a99 (adj 15): bgCount ##41
,I/SELinux ( 7868): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 7868): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 7868): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 7868): TimaSignature is unavailable
,D/ActivityThread( 7868): Added TimaKeyStore provider
,D/ResourcesManager( 7868): creating new AssetManager and set to /system/app/SecEmail_K/SecEmail_K.apk
,W/ResourcesManager( 7868): Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
,W/ResourcesManager( 7868): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 7868): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager( 7868): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,W/libprocessgroup(  875): failed to open /acct/uid_10099/pid_6846/cgroup.procs: No such file or directory
,D/RCPManagerService(  875): exchangeData() failure , invalid userId
,D/RCPManagerService(  875): exchangeData() failure , invalid userId
,D/RCPManagerService(  875): exchangeData() failure , invalid userId
,V/BitmapFactory( 7868): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_015.png
,E/ActivityManager(  875): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  875): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  875): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  875): checkUser: useridlist=null, currentuser=0
,V/BitmapFactory( 7868): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_000.png
V/BitmapFactory( 7868): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_015.png
,V/BitmapFactory( 7868): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_000.png
,V/BitmapFactory( 7868): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_000.png
,V/BitmapFactory( 7868): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_001.png
,V/BitmapFactory( 7868): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_002.png
,V/BitmapFactory( 7868): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_003.png
,D/RCPManagerService(  875): exchangeData() failure , invalid userId
I/libpersona( 7894): KNOX_SDCARD checking this for 10078
E/Zygote  ( 7894): MountEmulatedStorage()
I/libpersona( 7894): KNOX_SDCARD not a persona
E/Zygote  ( 7894): v2
,V/BitmapFactory( 7868): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_004.png
,V/BitmapFactory( 7868): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_005.png
,I/ActivityManager(  875): Start proc com.sec.android.provider.badge for content provider com.sec.android.provider.badge/.BadgeProvider: pid=7894 uid=10078 gids={50078, 9997} abi=armeabi-v7a
,V/BitmapFactory( 7868): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_006.png
,V/BitmapFactory( 7868): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_007.png
,V/BitmapFactory( 7868): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_008.png
,V/BitmapFactory( 7868): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_010.png
,V/BitmapFactory( 7868): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_011.png
,V/BitmapFactory( 7868): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_012.png
,V/BitmapFactory( 7868): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_013.png
,V/BitmapFactory( 7868): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_014.png
,V/BitmapFactory( 7868): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_015.png
,V/BitmapFactory( 7868): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_000.png
,V/BitmapFactory( 7868): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_001.png
,V/BitmapFactory( 7868): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_002.png
,V/BitmapFactory( 7868): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_003.png
I/SELinux ( 7894): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 7894): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 7894): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,V/BitmapFactory( 7868): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_004.png
,V/BitmapFactory( 7868): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_005.png
,V/BitmapFactory( 7868): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_006.png
,D/ConnectivityService(  875): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,V/BitmapFactory( 7868): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_007.png
,D/ConnectivityService(  875): returning getNetworkInfo(networkType - 0) :[type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,V/BitmapFactory( 7868): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_008.png
,D/RCPManagerService(  875): exchangeData() failure , invalid userId
D/RCPManagerService(  875): exchangeData() failure , invalid userId
,V/BitmapFactory( 7868): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_010.png
,V/BitmapFactory( 7868): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_011.png
,V/BitmapFactory( 7868): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_012.png
,V/BitmapFactory( 7868): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_013.png
,V/BitmapFactory( 7868): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_014.png
,V/BitmapFactory( 7868): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_015.png
,V/BitmapFactory( 7868): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/delete_glance_line.pkm
,V/BitmapFactory( 7868): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/delete_glance_icon_undo.pkm
,D/TimaKeyStoreProvider( 7894): TimaSignature is unavailable
,D/ActivityThread( 7894): Added TimaKeyStore provider
,D/ConnectivityService(  875): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/SecurityLogAgent( 7462): KnoxConfiguration : Current State = 1
D/SecurityLogAgent( 7462): KnoxConfiguration : Current State Mapping Found 
D/SecurityLogAgent( 7462): StateMachine : Current State = 1
,D/ConnectivityService(  875): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/ActivityManager(  875): Killing 6921:com.sec.android.provider.logsprovider/u0a20 (adj 15): bgCount ##41
,D/SecurityLogAgent( 7462): StateMachine : Changed Current State = 1
,V/BitmapFactory( 7868): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/list_icon_calendar_1.pkm
V/BitmapFactory( 7868): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/email_attach_icon_etc.pkm
,V/BitmapFactory( 7868): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/list_icon_flag.pkm
V/BitmapFactory( 7868): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/list_icon_complate.pkm
V/BitmapFactory( 7868): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/list_icon_flag_off_white.pkm
V/BitmapFactory( 7868): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/email_list_attach_icon_star_off.pkm
,V/BitmapFactory( 7868): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/email_list_attach_icon_star_on.pkm
,V/BitmapFactory( 7868): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/list_icon_flag_f.pkm
V/BitmapFactory( 7868): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/list_icon_complate_f.pkm
V/BitmapFactory( 7868): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/list_icon_flag_off_f.pkm
V/BitmapFactory( 7868): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/email_icon_foward.pkm
,V/BitmapFactory( 7868): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/email_icon_foward_focus.pkm
V/BitmapFactory( 7868): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/list_icon_reply_forward.pkm
,V/BitmapFactory( 7868): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/email_icon_reply.pkm
V/BitmapFactory( 7868): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/email_icon_reply_focus.pkm
V/BitmapFactory( 7868): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/list_icon_vip.pkm
,V/BitmapFactory( 7868): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/email_list_high_priority.pkm
V/BitmapFactory( 7868): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/email_list_low_priority.pkm
,V/BitmapFactory( 7868): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/list_icon_server_draft.pkm
V/BitmapFactory( 7868): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/list_icon_client_draft.pkm
,V/BitmapFactory( 7868): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/permission.pkm
V/BitmapFactory( 7868): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/list_icon_voicemail.pkm
,V/BitmapFactory( 7868): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/list_icon_sms.pkm
V/BitmapFactory( 7868): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/list_icon_sign.pkm
,V/BitmapFactory( 7868): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/list_icon_encryption.pkm
,V/BitmapFactory( 7868): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/tw_expander_open_01_holo_light.pkm
,V/BitmapFactory( 7868): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/tw_expander_close_01_holo_light.pkm
,W/libprocessgroup(  875): failed to open /acct/uid_10020/pid_6921/cgroup.procs: No such file or directory
,D/ConnectivityService(  875): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,I/art     (  875): Explicit concurrent mark sweep GC freed 69559(3MB) AllocSpace objects, 8(258KB) LOS objects, 30% free, 36MB/52MB, paused 1.286ms total 88.173ms
,D/ConnectivityService(  875): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  875): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/Tethering(  875): MasterInitialState.processMessage what=3
,D/SmartBondingService(  875): SmartBondingReceiver: onReceive action=android.net.conn.CONNECTIVITY_CHANGE
D/SmartBondingService(  875): SmartBondingReceiver: wifi is connected
D/SmartBondingService(  875): SmartBondingReceiver: wifi ap is not changed
,D/ConnectivityService(  875): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  875): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/CLocInfoService(  875): External Intent Received android.net.conn.CONNECTIVITY_CHANGE
D/SmartBondingService(  875): EVENT_UPDATE_SB_STATE called / mDisableBySIOP false
,D/SmartBondingService(  875): getSBEnabled() enabled =false
D/SmartBondingService(  875): getSBEnabled() enabled =false
D/SmartBondingService(  875): getSBEnabled() enabled =false
,D/ConnectivityService(  875): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/CLocInfoService(  875): CLocinfo wifi true 
D/ConnectivityService(  875): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/accuweather( 2135): [KK AccuPhone]>>> SWW:66 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,D/ConnectivityService(  875): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/NtpTrustedTime(  875): currentTimeMillis() cache hit
D/ResourcesManager( 7894): creating new AssetManager and set to /system/app/BadgeProvider/BadgeProvider.apk
,D/ConnectivityService(  875): returning getNetworkInfo(networkType - 0) :[type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/ConnectivityService(  875): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SmartBondingService(  875): getNetworkEnabled : wifi : true mobile : true
,D/ConnectivityService(  875): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  875): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/ConnectivityService(  875): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/AlarmManagerService(  875): Setting time of day to sec=1450109350
D/AlarmManagerService(  875): Trying to open a file
D/ConnectivityService(  875): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/AlarmManagerService(  875): File Open Success
D/AlarmManagerService(  875): File Close Success
I/AlarmManagerService(  875): DRM_TIME_PATH CHMOD 666 for resetState done 
,V/AlarmManager(  875): waitForAlarm result :65536
W/AlarmManagerService(  875): Unable to set rtc to 1450109350: Invalid argument
,D/ConnectivityService(  875): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  875): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  875): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,W/ContextImpl( 2177): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1994 android.content.ContextWrapper.startService:533 com.samsung.SMT.SamsungTTSService.d:-1 com.samsung.SMT.SamsungTTSService.a:-1 com.samsung.SMT.ai.onReceive:-1 
I/DBG_DM  ( 3868): [lllllllIlllIIlllIlIl(88/llIIIIlllllIIllIIllI)] WiFi Network is connected
I/DBG_DM  ( 3868): [com.wssyncmldm.XDMService(1111/IlIlllIIlIlIIIlIlIll)] WiFi network Connected : true
,W/ContextImpl( 2177): Implicit intents with startService are not safe: Intent { act=com.samsung.SMT.UpdateManager.UPDATE_DATA } android.content.ContextWrapper.startService:533 com.samsung.SMT.SamsungTTSService.d:-1 com.samsung.SMT.SamsungTTSService.a:-1 
,D/ConnectivityService(  875): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/ActivityManager(  875): Killing 6936:com.samsung.android.intelligenceservice/u0a3 (adj 15): bgCount ##41
,D/ConnectivityService(  875): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  875): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/ConnectivityService(  875): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/ConnectivityService(  875): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  875): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/NetworkMonitor( 7539): type=WIFI subType= reason=null isConnected=true
D/com.peel.receiver.ConnectivityActionReceiver( 1823): ConnectivityActionReceiver onReceive
,D/com.peel.receiver.ConnectivityActionReceiver( 1823): 
D/com.peel.receiver.ConnectivityActionReceiver( 1823): 
D/com.peel.receiver.ConnectivityActionReceiver( 1823): country_code: Germany -- rom region: GB
D/com.peel.receiver.ConnectivityActionReceiver( 1823): 
D/ConnectivityService(  875): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  875): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  875): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  875): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/ConnectivityService(  875): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/WifiStateMachine(  875): android.intent.action.TIME_SET - start updateConfiguredNetworkExpiration()
D/WifiStateMachine(  875): updateConfiguredNetworkExpiration - currTime: 1450109350760
D/WifiStateMachine(  875): updateConfiguredNetworkExpiration - AP, "NG700", is not shared AP.
,D/KeyguardUpdateMonitor( 1169): received broadcast android.intent.action.TIME_SET
D/KeyguardUpdateMonitor( 1169): handleTimeUpdate
,I/DowntimeConditions(  875): android.intent.action.TIME_SET ignored because schedule turned off.
,D/com.peel.receiver.ConnectivityActionReceiver( 1823): 
D/com.peel.receiver.ConnectivityActionReceiver( 1823): 
D/com.peel.receiver.ConnectivityActionReceiver( 1823):  network type WIFI path... network offline: false
D/com.peel.receiver.ConnectivityActionReceiver( 1823): 
D/com.peel.receiver.ConnectivityActionReceiver( 1823): has active network... run services...
D/com.peel.receiver.ConnectivityActionReceiver( 1823): 
D/com.peel.receiver.ConnectivityActionReceiver( 1823): 
D/com.peel.receiver.ConnectivityActionReceiver( 1823): last run: 1450100212786 -- System.currentTimeMillis()-last_run: 9137981
D/com.peel.receiver.ConnectivityActionReceiver( 1823): ... skip 
D/com.peel.receiver.ConnectivityActionReceiver( 1823): ... skip last_72_check
,D/KeyguardEffectViewController( 1169): onReceive action : android.intent.action.TIME_SET
,D/StatusBar-DoNotDistrub( 1169): Received intent with android.intent.action.TIME_SET action
,D/BadgeProvider( 7894): onCreate
D/BadgeProvider( 7894): DatabaseHelper
,D/StatusBar-DoNotDistrub( 1169): Not data shared android.content.pm.PackageManager$NameNotFoundException: Application package com.sec.android.settings.praymodewidget not found
,D/SecContentProvider2(  875): uri = 11 selection = getMyKnoxAdmin
D/SecContentProvider2(  875): mCursor = null
,D/accuweather( 2135): [KK AccuPhone]>>> SWW:66 [0:0] action : androidintentactionTIME_SET
,D/accuweather( 2135): [KK AccuPhone]>>> SWW:479 [0:0] doChangeDayOrNight : 1
D/accuweather( 2135): [KK AccuPhone]>>> SWW:364 [0:0] getWeatherRenderer : 1
D/accuweather( 2135): [KK AccuPhone]>>> SWW:496 [0:0] makeClock : 1
D/accuweather( 2135): [KK AccuPhone]>>> SWW:364 [0:0] getWeatherRenderer : 1
,D/accuweather( 2135): [KK AccuPhone]>>> SM:679 [0:0] [sCCTZ] set default tZ
D/accuweather( 2135): [KK AccuPhone]>>> SM:1402 [0:0] setClockLayoutContent
,W/Settings(  875): Setting auto_time has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/StatusBar-DoNotDistrub( 1169): sendBroadcast android.intent.action.DORMANT_MODE_OFF
,V/AudioPolicyManager(  293): getOutputsForDevice device 0002 -> 0002
I/AudioService(  875): getStreamVolume 5 index 110
,I/DrmEventService(  875):  no response from SecureClock 
D/StatusBar-DoNotDistrub( 1169): The STREAM NOTIFICATION volume is 0
,D/StatusBarManagerService(  875): manageDisableList userId=0 what=0x0 pkg=com.android.systemui
,E/ActivityManager(  875): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  875): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  875): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  875): checkUser: useridlist=null, currentuser=0
,D/DateView( 1169): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1169): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,E/Zygote  ( 7918): MountEmulatedStorage()
E/Zygote  ( 7918): v2
I/libpersona( 7918): KNOX_SDCARD checking this for 10178
I/libpersona( 7918): KNOX_SDCARD not a persona
,I/ActivityManager(  875): Start proc com.samsung.android.service.travel for broadcast com.samsung.android.service.travel/com.samsung.android.travel.bindService.TravelBroadcastReceiver: pid=7918 uid=10178 gids={50178, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,W/ActivityManager(  875): Unable to start service Intent { cmp=com.android.email/.service.AttachmentDownloadService } U=0: not found
,D/ConnectivityService(  875): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/SELinux ( 7918): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,D/BadgeProvider( 7894): query, [selection] : package='com.android.email' AND class='com.android.email.activity.Welcome' AND extraData='base_extra_badge'
I/SELinux ( 7918): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 7918): [DEBUG] get_category: variable seinfo: shared sensitivity: NULL, cateogry: NULL
,D/SurfaceWidget.Renderer( 2135): [237392/6] SurfaceWidget drawing first frame
,D/SurfaceWidget.Renderer( 2135): [237392/6] SurfaceWidget drawing first frame
D/SurfaceWidget.Renderer( 2135): [237392/6] SurfaceWidget drawing first frame
D/SurfaceWidget.Renderer( 2135): [237392/6] SurfaceWidget drawing first frame
,W/libprocessgroup(  875): failed to open /acct/uid_10003/pid_6936/cgroup.procs: No such file or directory
,D/BadgeProvider( 7894): sendNotify entered. [uri] : content://com.sec.badge/apps/1
D/BadgeProvider( 7894): sendNotify, [notify] : null
D/BadgeProvider( 7894): update, [uri] : content://com.sec.badge/apps/1
D/Launcher.Model( 1471): reloadBadges entered.
,D/BadgeProvider( 7894): update, [BadgeCount] : badgecount=0
D/BadgeProvider( 7894): update, [UpdateCount] : 1
,D/TimaKeyStoreProvider( 7918): TimaSignature is unavailable
,D/ActivityThread( 7918): Added TimaKeyStore provider
,D/ResourcesManager( 7918): creating new AssetManager and set to /system/app/TravelService_K/TravelService_K.apk
,I/ActivityManager(  875): Killing 6948:com.samsung.android.app.filterinstaller/1000 (adj 15): bgCount ##41
,D/ConnectivityService(  875): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  875): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  875): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  875): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  875): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,W/libprocessgroup(  875): failed to open /acct/uid_1000/pid_6948/cgroup.procs: No such file or directory
,D/ChimeraCfgMgr( 2474): Loading module com.google.android.gms.kids from APK com.google.android.gms
,D/ConnectivityService(  875): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  875): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ChimeraCfgMgr( 2474): Loading module com.google.android.gms.kids from APK com.google.android.gms
,D/ConnectivityService(  875): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  875): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/GLSUser ( 1652): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: ac2dm
,I/GLSUser ( 1652): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> ac2dm without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1652): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1652): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1652): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/WaitQueueForNetworkActivate( 7079): notifyNetworkActivated
,V/BitmapFactory( 1652): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/common_ic_googleplayservices.png
,V/BitmapFactory( 1652): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  875): uri = 14 selection = getSealedState
D/SecContentProvider2(  875): mCursor = null
,D/SecContentProvider2(  875): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  875): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy(  875): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/StatusBar( 1169): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,I/PhoneStatusBar( 1169): Icon Only
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
D/PanelView( 1169): There is/are notification(s) 
D/PanelView( 1169): There is/are notification(s) 
,W/ContextImpl( 7079): Implicit intents with startService are not safe: Intent { act=com.sec.knox.containeragent.service.containermanager.ContainerManagerService } android.content.ContextWrapper.bindService:559 com.sec.knox.containeragent.ContainerManager.<init>:49 com.sec.android.app.samsungapps.vlibrary2.knoxmode.KNOXAPI.<init>:20 
W/Kids    ( 2474): [AccountUtils] Account not ready
W/Kids    ( 2474): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/Kids    ( 2474): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/Kids    ( 2474): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/Kids    ( 2474): 	at com.google.android.gms.auth.p.c(SourceFile:550)
W/Kids    ( 2474): 	at com.google.android.gms.auth.p.b(SourceFile:477)
W/Kids    ( 2474): 	at com.google.android.gms.kids.account.k.d(SourceFile:103)
W/Kids    ( 2474): 	at com.google.android.gms.kids.account.p.a(SourceFile:70)
W/Kids    ( 2474): 	at com.google.android.gms.kids.account.t.a(SourceFile:62)
W/Kids    ( 2474): 	at com.google.android.gms.chimera.f.run(SourceFile:179)
W/Kids    ( 2474): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
W/Kids    ( 2474): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
W/Kids    ( 2474): 	at java.lang.Thread.run(Thread.java:818)
,W/ActivityManager(  875): Unable to start service Intent { act=com.sec.knox.containeragent.service.containermanager.ContainerManagerService } U=0: not found
,D/hcjo    ( 7079): AutoUpdateManager:IDLE:execute
,I/Hs20UtilService( 1309): Starting #8
,D/InitializeManagerStateMachine( 7079): execute::IDLE:EXECUTE
,D/InitializeManagerStateMachine( 7079): exit::IDLE
D/InitializeManagerStateMachine( 7079): entry::NETWORK_CHECK
,D/ConnectivityService(  875): returning getNetworkInfo(networkType - 0) :[type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/NearbySettings( 1309): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,V/NearbySettings( 1309): DMSUtil.isNetworkConnected - flag-null, state-null
I/Hs20UtilService( 1309): Message received 5007
D/ConnectivityService(  875): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/ConnectivityService(  875): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/NearbySettings( 1309): DMSUtil.isNetworkConnected - WIFI: CONNECTED
D/InitializeManagerStateMachine( 7079): execute::NETWORK_CHECK:NETWORK_STATE_OK
,D/InitializeManagerStateMachine( 7079): exit::NETWORK_CHECK
D/InitializeManagerStateMachine( 7079): entry::CHECK_COUNTRY_INFO
D/InitializeManagerStateMachine( 7079): execute::CHECK_COUNTRY_INFO:COUNTRY_INFO_OK
D/InitializeManagerStateMachine( 7079): exit::CHECK_COUNTRY_INFO
D/ConnectivityService(  875): returning getNetworkInfo(networkType - 13) :[type: WIFI_P2P[] - WIFI_P2P, state: UNKNOWN/IDLE, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/InitializeManagerStateMachine( 7079): entry::SUCCESS
D/hcjo    ( 7079): AutoUpdateManager:INITCHECK:onInitializeSuccess
I/NearbySettings( 1309): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 1309): DMSUtil.isNetworkConnected - WIFI-true, Hotspot-false, P2P-false, Eth-false
I/NearbySettings( 1309): MountReceiver.onReceive - Keep current state
,D/hcjo    ( 7079): AutoUpdateTriggerManager:IDLE:notifyNextTime
,D/hcjo    ( 7079): AutoUpdateManager:UPD_CHECK_TIMING:onNoUpdateTime
,D/ConnectivityService(  875): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/InitializeManagerStateMachine( 7079): exit::SUCCESS
D/InitializeManagerStateMachine( 7079): entry::IDLE
,I/Hs20UtilService( 1309): Starting #9
,I/Hs20UtilService( 1309): Message received 5007
,D/NearbySettings( 1309): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,I/NearbySettings( 1309): MountReceiver.onReceive - Keep current state
,I/Hs20UtilService( 1309): Starting #10
,I/Hs20UtilService( 1309): Message received 5007
,D/NearbySettings( 1309): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,V/NearbySettings( 1309): DMSUtil.isNetworkConnected - flag-null, state-null
D/ConnectivityService(  875): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/NearbySettings( 1309): DMSUtil.isNetworkConnected - WIFI: CONNECTED
D/ConnectivityService(  875): returning getNetworkInfo(networkType - 13) :[type: WIFI_P2P[] - WIFI_P2P, state: UNKNOWN/IDLE, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/NearbySettings( 1309): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 1309): DMSUtil.isNetworkConnected - WIFI-true, Hotspot-false, P2P-false, Eth-false
I/NearbySettings( 1309): MountReceiver.onReceive - Keep current state
,I/Hs20UtilService( 1309): Starting #11
,I/Hs20UtilService( 1309): Message received 5007
,D/NearbySettings( 1309): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,I/NearbySettings( 1309): MountReceiver.onReceive - Keep current state
,I/WifiStateMachine(  875): callSECApi what=220
D/WifiStateMachine(  875): SEC_COMMAND_ID_GET_FWS_OPEN_AP_CHECK : 0
,I/PCWCLIENTTRACE_PushUtil( 7522): SPPPushClient is installed : true
,I/PCWCLIENTTRACE_PushUtil( 7522): sales region : global
I/PCWCLIENTTRACE_PushUtil( 7522): getPushTypeList : [SPP, GCM]
I/PCWCLIENTTRACE_SYSTEMReceiver( 7522): [onReceive] - android.net.conn.CONNECTIVITY_CHANGE
,I/SurfaceFlinger(  249): id=16 createSurf (1x1),1 flag=4, Toast
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
,I/DIAGMON_AGENT( 7592): [lIIllllllllIlIlIllll(17/llIIIIlllllIIllIIllI)] Receive broadcast: android.net.conn.CONNECTIVITY_CHANGE
,I/DIAGMON_AGENT( 7592): [lIIllllllllIlIlIllll(31/llIIIIlllllIIllIIllI)] Running with RegistrationReceiver
,D/PowerManagerService(  875): [api] acquire WakeLock flags=0x2000000a tag=WindowManager uid=1000 pid=875
,D/DisplayPowerController(  875): getFinalBrightness : 8 -> 8
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
,D/PowerManagerService(  875): [s] DisplayPowerCallbacks : onStateChanged()
,D/lights  (  875): lcd : 8 +
D/DisplayPowerController(  875): getFinalBrightness : 8 -> 8
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
,D/ConnectivityService(  875): NetTransition Wakelock (NetworkAgentInfo [WIFI () - 502] cleared because we found a replacement network
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
,D/lights  (  875): lcd : 8 -
,D/DisplayPowerController(  875): getFinalBrightness : 8 -> 8
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
,I/FOTA_Client( 7608): [com.sec.android.fotaclient.FotaRegisterReceiver(113/onReceive)] Already device registered...
,I/FOTA_Client( 7608): [com.sec.android.fotaclient.FotaUpdaterReceiver(103/onReceive)] Auto update settings is activated
,I/FOTA_Client( 7608): [lllllllllllIlllllIIl(197/lllIlIlIIIllIIlIllIl)] Polling time is vaild
,I/FOTA_Client( 7608): [com.sec.android.fotaclient.FotaUpdaterReceiver(126/onReceive)] Heartbeat settings is activated.
,I/FOTA_Client( 7608): [llIlIIIIlllIlllllIll(125/llIlIIIIlIIIIIlIlIII)] heartbeat time is vaild
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
,I/KLMS-2.4.503: ( 7630): KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,I/KLMS-2.4.503: ( 7630): MainReciver(): EventNotificationReciver- method called: AppActivityListner onReceive for Intent Action : android.net.conn.CONNECTIVITY_CHANGE , timestamp: 1450109351251
,I/KLMS-2.4.503: ( 7630): MainReciver(): NETWORK_STATE_CHANGED_ACTION
,D/ConnectivityService(  875): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/ConnectivityService(  875): returning getNetworkInfo(networkType - 0) :[type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/KLMS-2.4.503: ( 7630): KLMSUtility(): isNetworkAvailable() - WIFI : true| MOBILE : false
,I/KLMS-2.4.503: ( 7630): StateImplV2(): networkChangeListener().START
,I/KLMS-2.4.503: ( 7630): NetworkChangeOperations(): uploadRequestLog().START 
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1169): value : false
,I/KLMS-2.4.503: ( 7630): StateImplV2(): networkChangeListener().END
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1169): value : false
,I/SO_AGENT( 7645): [com.sec.android.soagent.RegisterReceiver(104/onReceive)] Get Accessory List
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
,E/WifiStateMachine(  875): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: [192.168.1.135/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576} new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.135/24,fe80::ee1f:72ff:fe18:8b78/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0}
,E/WifiStateMachine(  875): updateLinkProperties nid: 0 state: CONNECTED reason: CMD_UPDATE_LINKPROPERTIES v4 v4r v4dns isprov
D/ConnectivityService(  875): Update of LinkProperties for NetworkAgentInfo [WIFI () - 503]; created=true
,D/ConnectivityService(  875): updateLinkProperties: newLp = {InterfaceName: wlan0 LinkAddresses: [192.168.1.135/24,fe80::ee1f:72ff:fe18:8b78/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}
D/SmartBondingService(  875): SmartBondingReceiver: onReceive action=android.net.wifi.LINK_CONFIGURATION_CHANGED
,D/ConnectivityService(  875): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/SmartBondingService(  875): EVENT_UPDATE_SB_STATE called / mDisableBySIOP false
D/SmartBondingService(  875): getSBEnabled() enabled =false
D/SmartBondingService(  875): getSBEnabled() enabled =false
,D/SmartBondingService(  875): getSBEnabled() enabled =false
D/ConnectivityService(  875): identical MTU - not setting
D/ConnectivityService(  875): updateSourceRoutes : add source routing for type : 1
,D/ConnectivityService(  875): updateSourceRoutes : add src route for:fe80::ee1f:72ff:fe18:8b78
V/        (  279): QcRouteController
,D/ConnectivityService(  875): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/ConnectivityService(  875): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1169): value : false
,E/SPPClientService( 7680): [[SystemStateMoniter]] SystemStateMonitorService : noConnect? : false
,V/        (  279): QcRouteController
,W/NetworkManagementService(  875): route cmd failed: 
W/NetworkManagementService(  875): com.android.server.NativeDaemonConnector$NativeDaemonFailureException: command '72 route replace src v6 wlan0 fe80::ee1f:72ff:fe18:8b78 2 ::' failed with '400 72 -6 route replace default via :: dev wlan0 scope global table 2: RTNETLINK answers: Invalid argument
W/NetworkManagementService(  875): '
W/NetworkManagementService(  875): 	at com.android.server.NativeDaemonConnector.execute(NativeDaemonConnector.java:438)
W/NetworkManagementService(  875): 	at com.android.server.NativeDaemonConnector.executeForList(NativeDaemonConnector.java:371)
W/NetworkManagementService(  875): 	at com.android.server.NativeDaemonConnector.execute(NativeDaemonConnector.java:336)
W/NetworkManagementService(  875): 	at com.android.server.NativeDaemonConnector.execute(NativeDaemonConnector.java:321)
W/NetworkManagementService(  875): 	at com.android.server.NetworkManagementService.replaceSrcRoute(NetworkManagementService.java:2812)
W/NetworkManagementService(  875): 	at com.android.server.ConnectivityService.updateSourceRoutes(ConnectivityService.java:5478)
W/NetworkManagementService(  875): 	at com.android.server.ConnectivityService.updateLinkProperties(ConnectivityService.java:5305)
W/NetworkManagementService(  875): 	at com.android.server.ConnectivityService.access$1800(ConnectivityService.java:230)
W/NetworkManagementService(  875): 	at com.android.server.ConnectivityService$NetworkStateTrackerHandler.handleMessage(ConnectivityService.java:2324)
W/NetworkManagementService(  875): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/NetworkManagementService(  875): 	at android.os.Looper.loop(Looper.java:145)
W/NetworkManagementService(  875): 	at android.os.HandlerThread.run(HandlerThread.java:61)
D/Nat464Xlat(  875): requiresClat: netType=1, connected=true, hasIPv4Address=true
D/ConnectivityService(  875): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 503]
D/ConnectivityService(  875): calling update connectivity
D/ConnectivityService(  875):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  875):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
,D/ConnectivityService(  875): sending notification IP_CHANGED for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  875): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 503]
,D/ConnectivityService(  875): calling update connectivity
D/ConnectivityManager.CallbackHandler( 1169): CM callback handler got msg 524295
D/ConnectivityService(  875):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  875):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
,D/ConnectivityService(  875): sending notification IP_CHANGED for NetworkRequest [ id=2, legacyType=-1, [] ]
,D/ConnectivityManager.CallbackHandler( 1169): CM callback handler got msg 524295
,I/SA      ( 7696): [OR] onReceive log=[SA = 2.1.0142 V = 21 HWD = 1920X1080 3.0 dpi = 480  SIZE = 2 LOCALE = en_US CSC = DBT MCC = 0 MNC 0 T = user DEVICE = klte P = kltexx I = LRX21T M = SM-G900F OKLEFT false DIS LRX21T.G900FXXU1BOD3 PSS = 5.219788042639568  ]
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1169): value : false
I/SA      ( 7696): [OR] onReceive Intent=[ conn.CONNECTIVITY_CHANGE. networkInfo:[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] networkType:1 inetCondition:0 extraInfo:? isDefault:true ]
I/SA      ( 7696): [OR] == ACTION_CONNECTIVITY_CHANGE ==
,I/SA      ( 7696): [TPMU]  strSIMState 	:SIM_STATE_UNKNOWN
I/SA      ( 7696): [OR] == isSIMCardReady false ==
D/ConnectivityService(  875): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/SA      ( 7696): [SCU] == networkStateCheck == true
I/SA      ( 7696): [DM] getCountryCodeFromCSC : DE
I/SA      ( 7696): isChinaCountryCode : false
I/SA      ( 7696): [SCU] is ChinestModel Data Restricted   : false
I/SA      ( 7696): [OR] == networkStateCheck true ==
,I/SA      ( 7696): [OR] GetMyCountryZoneTask
,I/SA      ( 7696): [OR] onReceive END
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
,D/ConnectivityService(  875): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/SA      ( 7696): [SRS] prepareGetMyCountryZone
,D/accuweather( 7215): [KK AccuPhone]>>> WC:30 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,D/accuweather( 7215): [KK AccuPhone]>>> UIMEM:106 [0:0] The widget does not exist in idle!!
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1169): value : false
,D/ConnectivityService(  875): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/KnoxUsageLogPro( 7717): KnoxUsageReceiver onReceive :android.net.conn.CONNECTIVITY_CHANGE myUserId=0
,I/KnoxUsageLogPro( 7717): premStatus:2
I/KnoxUsageLogPro( 7717): isEulaShown : false
,I/KnoxUsageLogPro( 7717): KnoxUsageReceiver onReceive : not Processible, just return
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
,D/Headlines( 5507): HeadlinesSystemBroadcastReceiver onReceive android.net.conn.CONNECTIVITY_CHANGE
,D/HeadlinesChannelUtil( 5507): getCountryCode(): countryCode = DE
,D/Headlines( 5507): Breath.onStartCommand : com.samsung.android.internal.headlines.UPDATE_WELCOME_CARD flag : 0
,D/HeadlinesCardManager( 5507): updateCategory : HeadlinesCardManager:updateCategory() category size == 0
D/HeadlinesCardManager( 5507): updateCategory : HeadlinesCardManager:updateCategory() try to query category list
D/Headlines( 5507): queryCategory.  mRequest is not initialized.
,D/HeadlinesCardManager( 5507): updateCategory : HeadlinesCardManager:updateCategory() reponse : false
D/HeadlinesCardManager( 5507): requestUpdateNewsWelcomeCard : request update welcome card to content card.
D/HeadlinesDataCenter( 5507): requestUpdateNewsWelcomeCard !!! no welcome card
,D/ConnectivityService(  875): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/SA      ( 7696): [TPMU]  strSIMState 	:SIM_STATE_UNKNOWN
,I/SA      ( 7696): [SSP] query invoked
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1169): value : false
,I/SA      ( 7696): [TPMU] GetMccFromDB : null
,D/ConnectivityService(  875): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  875): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/SA      ( 7696): [SCU] getMccFromPreferece mcc = 260
I/SA      ( 7696): [TPM] isNoProxy(default) : true
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
,D/QuickConnect( 7853): PeriphStartReceiver.onReceive - android.net.conn.CONNECTIVITY_CHANGE
,I/QuickConnect( 7853): PeriphStartReceiver.onReceive - USER_OWNER care CONNECTIVITY_ACTION. run P service
I/QuickConnect( 7853): PeriphStartReceiver.onReceive - no need to start
,D/ConnectivityService(  875): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  875): returning getNetworkInfo(networkType - 0) :[type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/RCPManagerService(  875): exchangeData() failure , invalid userId
,D/RCPManagerService(  875): exchangeData() failure , invalid userId
,D/ConnectivityService(  875): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SecurityLogAgent( 7462): KnoxConfiguration : Current State = 1
D/SecurityLogAgent( 7462): KnoxConfiguration : Current State Mapping Found 
D/SecurityLogAgent( 7462): StateMachine : Current State = 1
D/ConnectivityService(  875): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SecurityLogAgent( 7462): StateMachine : Changed Current State = 1
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
,E/File    ( 7696): fail readDirectory() errno=2
,D/com.peel.receiver.ConnectivityActionReceiver( 1823): ConnectivityActionReceiver onReceive
D/com.peel.receiver.ConnectivityActionReceiver( 1823): 
D/com.peel.receiver.ConnectivityActionReceiver( 1823): 
D/com.peel.receiver.ConnectivityActionReceiver( 1823): country_code: Germany -- rom region: GB
D/com.peel.receiver.ConnectivityActionReceiver( 1823): 
,D/ConnectivityService(  875): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/ConnectivityService(  875): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/com.peel.receiver.ConnectivityActionReceiver( 1823): 
D/com.peel.receiver.ConnectivityActionReceiver( 1823): 
D/com.peel.receiver.ConnectivityActionReceiver( 1823):  network type WIFI path... network offline: false
D/com.peel.receiver.ConnectivityActionReceiver( 1823): 
D/com.peel.receiver.ConnectivityActionReceiver( 1823): has active network... run services...
D/com.peel.receiver.ConnectivityActionReceiver( 1823): 
D/com.peel.receiver.ConnectivityActionReceiver( 1823): 
D/com.peel.receiver.ConnectivityActionReceiver( 1823): last run: 1450100212786 -- System.currentTimeMillis()-last_run: 9138648
D/com.peel.receiver.ConnectivityActionReceiver( 1823): ... skip 
D/com.peel.receiver.ConnectivityActionReceiver( 1823): ... skip last_72_check
,D/ConnectivityService(  875): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
,D/ConnectivityService(  875): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  875): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
,D/ConnectivityService(  875): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  875): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ChimeraCfgMgr( 2474): Loading module com.google.android.gms.kids from APK com.google.android.gms
,D/ConnectivityService(  875): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  875): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
,D/ConnectivityService(  875): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  875): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/hcjo    ( 7079): AutoUpdateManager:IDLE:execute
,D/InitializeManagerStateMachine( 7079): execute::IDLE:EXECUTE
D/InitializeManagerStateMachine( 7079): exit::IDLE
D/InitializeManagerStateMachine( 7079): entry::NETWORK_CHECK
,D/ConnectivityService(  875): returning getNetworkInfo(networkType - 0) :[type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/ConnectivityService(  875): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/InitializeManagerStateMachine( 7079): execute::NETWORK_CHECK:NETWORK_STATE_OK
D/InitializeManagerStateMachine( 7079): exit::NETWORK_CHECK
D/InitializeManagerStateMachine( 7079): entry::CHECK_COUNTRY_INFO
D/InitializeManagerStateMachine( 7079): execute::CHECK_COUNTRY_INFO:COUNTRY_INFO_OK
D/InitializeManagerStateMachine( 7079): exit::CHECK_COUNTRY_INFO
D/InitializeManagerStateMachine( 7079): entry::SUCCESS
D/hcjo    ( 7079): AutoUpdateManager:INITCHECK:onInitializeSuccess
,I/FOTA_Client( 7608): [com.sec.android.fotaclient.FotaRegisterReceiver(113/onReceive)] Already device registered...
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
,D/hcjo    ( 7079): AutoUpdateTriggerManager:IDLE:notifyNextTime
D/hcjo    ( 7079): AutoUpdateManager:UPD_CHECK_TIMING:onNoUpdateTime
,D/ConnectivityService(  875): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/InitializeManagerStateMachine( 7079): exit::SUCCESS
D/InitializeManagerStateMachine( 7079): entry::IDLE
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
,I/FOTA_Client( 7608): [com.sec.android.fota.osp.time.ServerTimeReceiver(47/onReceive)] No action is available before server time settings
,I/GLSUser ( 1652): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: ac2dm
,I/GLSUser ( 1652): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> ac2dm without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1652): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1652): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/KLMS-2.4.503: ( 7630): KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,I/KLMS-2.4.503: ( 7630): MainReciver(): EventNotificationReciver- method called: AppActivityListner onReceive for Intent Action : android.intent.action.TIME_SET , timestamp: 1450109351522
,V/GLSActivity( 1652): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/KLMS-2.4.503: ( 7630): MainReciver(): TIME_CHANGED
,I/KLMS-2.4.503: ( 7630): StateImplV2(): dateTimeChanged().START : Mon Dec 14 17:09:11 GMT+01:00 2015
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
,I/KLMS-2.4.503: ( 7630): StateImplV2(): dateTimeChanged().END
,E/ActivityManager(  875): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  875): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  875): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  875): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 7961): MountEmulatedStorage()
E/Zygote  ( 7961): v2
I/libpersona( 7961): KNOX_SDCARD checking this for 10035
I/libpersona( 7961): KNOX_SDCARD not a persona
,I/ActivityManager(  875): Start proc com.sec.android.app.shealth for broadcast com.sec.android.app.shealth/com.cigna.mobile.coach.CoachBroadcastReceiver: pid=7961 uid=10035 gids={50035, 9997, 3003, 1028, 1015, 3001, 3002} abi=armeabi-v7a
,I/WifiStateMachine(  875): CMD_RSSI_POLL : calculateWifiScore in!
,I/WifiStateMachine(  875): CMD_RSSI_POLL : calculateWifiScore out!
I/WifiStateMachine(  875): CMD_RSSI_POLL : out!
,I/SELinux ( 7961): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,D/StatusBar.NetworkController( 1169): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02012b/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020466/com.android.systemui:drawable/stat_sys_signal_inout mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
,I/SELinux ( 7961): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,V/BitmapFactory( 1652): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,E/SELinux ( 7961): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,D/SecContentProvider2(  875): uri = 14 selection = getSealedState
,D/SecContentProvider2(  875): mCursor = null
D/SecContentProvider2(  875): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  875): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
V/ApplicationPolicy(  875): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/StatusBar( 1169): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,I/PhoneStatusBar( 1169): Icon Only
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
D/PanelView( 1169): There is/are notification(s) 
,D/PanelView( 1169): There is/are notification(s) 
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
W/Kids    ( 2474): [AccountUtils] Account not ready
W/Kids    ( 2474): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/Kids    ( 2474): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/Kids    ( 2474): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/Kids    ( 2474): 	at com.google.android.gms.auth.p.c(SourceFile:550)
W/Kids    ( 2474): 	at com.google.android.gms.auth.p.b(SourceFile:477)
W/Kids    ( 2474): 	at com.google.android.gms.kids.account.k.d(SourceFile:103)
W/Kids    ( 2474): 	at com.google.android.gms.kids.account.p.a(SourceFile:70)
W/Kids    ( 2474): 	at com.google.android.gms.kids.account.t.a(SourceFile:62)
W/Kids    ( 2474): 	at com.google.android.gms.chimera.f.run(SourceFile:179)
W/Kids    ( 2474): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
W/Kids    ( 2474): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
W/Kids    ( 2474): 	at java.lang.Thread.run(Thread.java:818)
D/LockPatternUtilsCache( 1169): value : false
,D/TimaKeyStoreProvider( 7961): TimaSignature is unavailable
,D/ActivityThread( 7961): Added TimaKeyStore provider
,D/ResourcesManager( 7961): creating new AssetManager and set to /system/priv-app/SHealth3_5/SHealth3_5.apk
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1169): value : false
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1169): value : false
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1169): value : false
,V/AlarmManager(  875): waitForAlarm result :4
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode(),
D/LockPatternUtilsCache( 1169): value : false
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
,D/SHealthUpgrade(SHealthUpgradeUtil)( 7961): isShealthServiceInstalled() : HealthService is Installed.
,D/SHealthUpgrade(SHealthUpgradeUtil)( 7961): isShealthService2xInstalled() : HEALTH SERVICE is INSTALLED.
D/SHealthUpgrade(SHealthUpgradeUtil)( 7961): isShealthService2xInstalled() : HEALTH SERVICE VERSION = 2.x
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
,D/SHealthUpgrade(SHealthUpgradeUtil)( 7961): checkState()
,D/SHealthUpgrade(SHealthUpgradeUtil)( 7961): checkState() : APP TYPE = Full
,D/BatteryService(  875): level:100, scale:100, status:5, health:2, present:true, voltage: 4267, temperature: 298, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
D/BatteryService(  875): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
D/BatteryService(  875): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  875):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
I/MotionRecognitionService(  875): Plugged
I/MotionRecognitionService(  875): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1169): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1169): handleBatteryUpdate
D/SHealthUpgrade(SHealthUpgradeUtil)( 7961): isFitnessWithGearInstalled() : Fitness with Gear isn't Installed.
,D/SHealthUpgrade(SHealthUpgradeUtil)( 7961): isShealthServiceInstalled() : HealthService is Installed.
D/SHealthUpgrade(SHealthUpgradeUtil)( 7961): isShealthService1xInstalled() : HEALTH SERVICE is INSTALLED.
D/SHealthUpgrade(SHealthUpgradeUtil)( 7961): isShealthService1xInstalled() : HEALTH SERVICE VERSION is NOT 1.x !!!
,D/SHealthUpgrade(SHealthUpgradeUtil)( 7961): isShealthService0xInstalled() : HEALTH SERVICE is INSTALLED.
D/SHealthUpgrade(SHealthUpgradeUtil)( 7961): isShealthService0xInstalled() : HEALTH SERVICE VERSION is NOT 0.x !!!
,D/SHealthUpgrade(SHealthUpgradeUtil)( 7961): isShealthService2xInstalled() : HEALTH SERVICE is INSTALLED.
D/SHealthUpgrade(SHealthUpgradeUtil)( 7961): isShealthService2xInstalled() : HEALTH SERVICE VERSION = 2.x
,D/STATUSBAR-PhoneStatusBar( 1169):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/SHealthUpgrade(SHealthUpgradeUtil)( 7961): checkState() : =========== UPGRADE_STATE_APP_UPGRADE_DONE ===========
,D/SHealthUpgrade(SHealthUpgradeUtil)( 7961): isShealthServiceInstalled() : HealthService is Installed.
,D/SHealthUpgrade(SHealthUpgradeUtil)( 7961): isShealthService2xInstalled() : HEALTH SERVICE is INSTALLED.
D/SHealthUpgrade(SHealthUpgradeUtil)( 7961): isShealthService2xInstalled() : HEALTH SERVICE VERSION = 2.x
D/SHealthUpgrade(SHealthUpgradeUtil)( 7961): isShealthServiceInstalled() : HealthService is Installed.
,D/SHealthUpgrade(SHealthUpgradeUtil)( 7961): isShealthService2xInstalled() : HEALTH SERVICE is INSTALLED.
D/SHealthUpgrade(SHealthUpgradeUtil)( 7961): isShealthService2xInstalled() : HEALTH SERVICE VERSION = 2.x
V/HeadsetService( 3249): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3249): Disconnected process message: 10
,D/SHealthUpgrade(SHealthUpgradeUtil)( 7961): isShealthService2xInstalled() : HEALTH SERVICE is INSTALLED.
D/SHealthUpgrade(SHealthUpgradeUtil)( 7961): isShealthService2xInstalled() : HEALTH SERVICE VERSION = 2.x
,E/ActivityManager(  875): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  875): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  875): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  875): checkUser: useridlist=null, currentuser=0
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Zygote  ( 7982): MountEmulatedStorage()
,E/Zygote  ( 7982): v2
I/libpersona( 7982): KNOX_SDCARD checking this for 10017
,I/libpersona( 7982): KNOX_SDCARD not a persona
,I/ActivityManager(  875): Start proc com.sec.android.service.health for content provider com.sec.android.service.health/.cp.MigrationCpProvider: pid=7982 uid=10017 gids={50017, 9997} abi=armeabi-v7a
,I/SELinux ( 7982): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 7982): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 7982): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 7982): TimaSignature is unavailable
,D/ActivityThread( 7982): Added TimaKeyStore provider
,D/ResourcesManager( 7982): creating new AssetManager and set to /system/priv-app/HealthService/HealthService.apk
,D/SHealthUpgrade(SHealthUpgradeUtil)( 7961): isShealthService2xInstalled() : HEALTH SERVICE is INSTALLED.
D/SHealthUpgrade(SHealthUpgradeUtil)( 7961): isShealthService2xInstalled() : HEALTH SERVICE VERSION = 2.x
,D/BluetoothManager( 7961): getConnectedDevices
,D/-----SIC-----( 7961): ------------------skip uv
,D/-----SIC-----( 7961): ------------------skip SPO2
,D/-----SIC-----( 7961): ------------------skip TGH
,I/SecureStorage( 7982): [INFO]: SPID(0x00000000)Processing data
,I/SecureStorage(  358): [INFO]: SPID(0x00000005)Credentials: uid 10017, gid 10017, pid 7982
I/SecureStorage(  358): [INFO]: SPID(0x00000005)Received function mask & code: 0x00000106
,E/Vold    (  248): Failed to find mounted volume for /storage/extSdCard/Android/data/com.sec.android.app.shealth/cache/
W/Vold    (  248): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7961): Failed to ensure directory: /storage/extSdCard/Android/data/com.sec.android.app.shealth/cache
,E/Vold    (  248): Failed to find mounted volume for /storage/extSdCard/Android/data/com.sec.android.app.shealth/files/
W/Vold    (  248): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 7961): Failed to ensure directory: /storage/extSdCard/Android/data/com.sec.android.app.shealth/files
,V/MediaPlayer( 7961): decode(33, 19359868, 4230)
,V/MediaPlayerService(  293): decode(30, 19359868, 4230)
,V/MediaPlayerService(  293): player type = 3
V/AwesomePlayer(  293): setDefault
V/AwesomePlayer(  293): constructor
,V/AwesomePlayer(  293): setDefault
V/AwesomePlayer(  293): reset_l()
V/AwesomePlayer(  293): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  293): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  293): mAudioTrackVector clear
V/AwesomePlayer(  293): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  293): mSecCapture clear
V/AwesomePlayer(  293): mSecMediaClock clear
V/StagefrightPlayer(  293): StagefrightPlayer
V/AwesomePlayer(  293): setListener
V/StagefrightPlayer(  293): initCheck
V/AwesomePlayer(  293): setAudioSink
V/StagefrightPlayer(  293): setDataSource(30, 19359868, 4230)
V/AwesomePlayer(  293): reset_l()
V/AwesomePlayer(  293): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  293): notify(0xafa141a0, 8, 0, 0)
V/AudioCache(  293): ignored
V/AwesomePlayer(  293): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  293): mAudioTrackVector clear
V/AwesomePlayer(  293): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  293): mSecCapture clear
V/AwesomePlayer(  293): mSecMediaClock clear
D/Utils   (  293): printFileName fd(31) -> /system/priv-app/SHealth3_5/SHealth3_5.apk
,V/AwesomePlayer(  293): track of type 'audio/vorbis' does not publish bitrate
V/AwesomePlayer(  293): mBitrate = -1 bits/sec
I/OggExtractor(  293): OggSource::OggSource() mExtractor ref count = 4
V/AwesomePlayer(  293): current audio track index (0) is added to vector
V/AwesomePlayer(  293): setDataSource_l: Audio(1), Video(0)
I/AwesomePlayer(  293): checkRightsStatus is not necessary - AwesomePlayer::setDataSource_l
V/MediaPlayerService(  293): prepare
,V/AwesomePlayer(  293): prepareAsync
,V/AwesomePlayer(  293): onPrepareAsyncEvent
,I/SecMediaClock(  293): SecMediaClock constructor
I/SecMediaClock(  293): reset
I/SecVideoCapture(  293): SecVideoCapture constructor
I/SecVideoCapture(  293): reset
V/AwesomePlayer(  293): initAudioDecoder
V/AwesomePlayer(  293): checkOffloadExceptions is true
V/AudioPolicyManager(  293): isOffloadSupported: SR=44100, CM=0x1, Format=0x7000000, StreamType=-1, BitRate=4294967295, duration=20770 us, has_video=0
,V/AudioPolicyManager(  293): isOffloadSupported: stream_type != MUSIC, returning false
I/OMXCodec(  293): Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
,V/MediaPlayerService(  293): wait for prepare
,I/OMXCodec(  293): Successfully allocated OMX node 'OMX.google.vorbis.decoder'
,I/OMXCodec(  293): >>>UHQA initOutputFormat 16
,I/AwesomePlayer(  293): Could not offload audio decode, try pcm offload
V/AudioPolicyManager(  293): isOffloadSupported: SR=44100, CM=0x1, Format=0x1c000001, StreamType=-1, BitRate=4294967295, duration=20770 us, has_video=0
V/AudioPolicyManager(  293): isOffloadSupported: stream_type != MUSIC, returning false
I/OMXCodec(  293): [OMX.google.vorbis.decoder] OMXCodec::start mState=1
,I/OMXCodec(  293): [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
I/OMXCodec(  293): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
,I/OMXCodec(  293): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
,V/AwesomePlayer(  293): finishAsyncPrepare_l
V/AwesomePlayer(  293): notifyListner_l() msg (200-MEDIA_INFO), ext1 (973), ext2 (0)
V/AudioCache(  293): notify(0xafa141a0, 200, 973, 0)
V/AudioCache(  293): ignored
V/AwesomePlayer(  293): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache(  293): notify(0xafa141a0, 5, 0, 0)
V/AudioCache(  293): ignored
V/AwesomePlayer(  293): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache(  293): notify(0xafa141a0, 1, 0, 0)
V/AudioCache(  293): prepared
V/AudioCache(  293): wait - success
V/MediaPlayerService(  293): start
V/StagefrightPlayer(  293): start
V/AwesomePlayer(  293): play
V/AwesomePlayer(  293): AwesomePlayer::play_l():: This is not a DRM content
V/AwesomePlayer(  293): startAudioPlayer_l, sendErrorNotification (0)
D/AudioPlayer(  293): start of Playback, useOffload 0
,I/OMXCodec(  293): [OMX.google.vorbis.decoder] 0onCmdComplete  mState =  7
I/OMXCodec(  293): [OMX.google.vorbis.decoder] PORT_DISABLED(1)
I/OMXCodec(  293): >>>UHQA initOutputFormat 16
I/OMXCodec(  293): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
,I/OMXCodec(  293): [OMX.google.vorbis.decoder] End Of Stream
I/AudioPlayer(  293): Audio channels(1)
I/AudioPlayer(  293): Audioplayer kKeyAudioPCMFormat:0, 1, 0
,I/AudioPlayer(  293): Audioplayer kKeyAudioPCMFormat read fail(1, 1)
V/AudioCache(  293): open(44100, 1, 0x0, 1, 0)
,V/AwesomePlayer(  293): notifyListner_l() msg (6-MEDIA_STARTED), ext1 (0), ext2 (0)
V/AudioCache(  293): notify(0xafa141a0, 6, 0, 0)
V/AudioCache(  293): ignored
V/AwesomePlayer(  293): addBatteryData
,I/AudioPlayer(  293): First fillBuffer call!!
V/MediaPlayerService(  293): wait for playback complete
V/AwesomePlayer(  293): postAudioEOS delayUs (0)
,V/AwesomePlayer(  293): onCheckAudioStatus
V/AwesomePlayer(  293): onCheckAudioStatus() set AUDIO_AT_EOS flag
V/AwesomePlayer(  293): onStreamDone
V/AwesomePlayer(  293): MEDIA_PLAYBACK_COMPLETE
V/AwesomePlayer(  293): notifyListner_l() msg (2-MEDIA_PLAYBACK_COMPLETE), ext1 (0), ext2 (0)
V/AudioCache(  293): notify(0xafa141a0, 2, 0, 0)
V/AudioCache(  293): playback complete - thread will wake up later
V/AwesomePlayer(  293): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache(  293): notify(0xafa141a0, 7, 0, 0)
V/AudioCache(  293): ignored
V/AwesomePlayer(  293): cancelPlayerEvents (keepNotifications=1)
,V/AwesomePlayer(  293): addBatteryData
V/AudioCache(  293): wait - success
V/StagefrightPlayer(  293): reset
V/AwesomePlayer(  293): reset_l()
V/AwesomePlayer(  293): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  293): notify(0xafa141a0, 8, 0, 0)
V/AudioCache(  293): ignored
,V/AwesomePlayer(  293): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  293): mAudioTrackVector clear
D/AudioPlayer(  293): reset: mPlaying=0 mReachedEOS=1 useOffload=0
I/OMXCodec(  293): [OMX.google.vorbis.decoder] stop mState=4
I/OMXCodec(  293): [OMX.google.vorbis.decoder] stop() sendCommand(0x74, OMX_CommandStateSet, OMX_StateIdle)
,I/OMXCodec(  293): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
I/OMXCodec(  293): [OMX.google.vorbis.decoder] stopOmxComponent_l() mstate = 1
,I/OggExtractor(  293): OggSource::stop() mExtractor ref count = 1
I/OggExtractor(  293): OggSource::~OggSource() mExtractor !mStarted ref count = 1
I/OggExtractor(  293): ~OggSource --
I/OggExtractor(  293): ~OggExtractor ++
I/OggExtractor(  293): ~MyVorbisExtractor ++ 
I/OggExtractor(  293): ~MyVorbisExtractor --
,I/OggExtractor(  293): ~OggExtractor --
,I/AudioPlayer(  293): reset out
,V/AwesomePlayer(  293): reset_l() mAudioPlayer successfully deleted
I/SecVideoCapture(  293): SecVideoCapture destructor
I/SecVideoCapture(  293): reset
V/AwesomePlayer(  293): mSecCapture clear
I/SecMediaClock(  293): SecMediaClock destructor
V/AwesomePlayer(  293): mSecMediaClock clear
,V/StagefrightPlayer(  293): ~StagefrightPlayer
V/StagefrightPlayer(  293): reset
V/AwesomePlayer(  293): reset_l()
V/AwesomePlayer(  293): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  293): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  293): mAudioTrackVector clear
V/AwesomePlayer(  293): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  293): mSecCapture clear
,V/AwesomePlayer(  293): mSecMediaClock clear
V/AwesomePlayer(  293): destructor
V/AwesomePlayer(  293): reset_l()
,V/AwesomePlayer(  293): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  293): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  293): mAudioTrackVector clear
V/AwesomePlayer(  293): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  293): mSecCapture clear
V/AwesomePlayer(  293): mSecMediaClock clear
,V/MediaPlayer( 7961): decode(34, 19213040, 15440)
V/MediaPlayerService(  293): decode(30, 19213040, 15440)
,V/MediaPlayerService(  293): player type = 3
,V/AwesomePlayer(  293): setDefault
V/AwesomePlayer(  293): constructor
V/AwesomePlayer(  293): setDefault
V/AwesomePlayer(  293): reset_l()
V/AwesomePlayer(  293): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  293): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  293): mAudioTrackVector clear
V/AwesomePlayer(  293): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  293): mSecCapture clear
V/AwesomePlayer(  293): mSecMediaClock clear
V/StagefrightPlayer(  293): StagefrightPlayer
V/AwesomePlayer(  293): setListener
V/StagefrightPlayer(  293): initCheck
V/AwesomePlayer(  293): setAudioSink
V/StagefrightPlayer(  293): setDataSource(30, 19213040, 15440)
V/AwesomePlayer(  293): reset_l()
V/AwesomePlayer(  293): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  293): notify(0xb05183d0, 8, 0, 0)
V/AudioCache(  293): ignored
V/AwesomePlayer(  293): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  293): mAudioTrackVector clear
V/AwesomePlayer(  293): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  293): mSecCapture clear
V/AwesomePlayer(  293): mSecMediaClock clear
D/Utils   (  293): printFileName fd(31) -> /system/priv-app/SHealth3_5/SHealth3_5.apk
,V/AwesomePlayer(  293): track of type 'audio/vorbis' does not publish bitrate
V/AwesomePlayer(  293): mBitrate = -1 bits/sec
I/OggExtractor(  293): OggSource::OggSource() mExtractor ref count = 4
V/AwesomePlayer(  293): current audio track index (0) is added to vector
V/AwesomePlayer(  293): setDataSource_l: Audio(1), Video(0)
I/AwesomePlayer(  293): checkRightsStatus is not necessary - AwesomePlayer::setDataSource_l
V/MediaPlayerService(  293): prepare
V/AwesomePlayer(  293): prepareAsync
V/MediaPlayerService(  293): wait for prepare
V/AwesomePlayer(  293): onPrepareAsyncEvent
I/SecMediaClock(  293): SecMediaClock constructor
I/SecMediaClock(  293): reset
I/SecVideoCapture(  293): SecVideoCapture constructor
I/SecVideoCapture(  293): reset
V/AwesomePlayer(  293): initAudioDecoder
V/AwesomePlayer(  293): checkOffloadExceptions is true
V/AudioPolicyManager(  293): isOffloadSupported: SR=44100, CM=0x3, Format=0x7000000, StreamType=-1, BitRate=4294967295, duration=849387 us, has_video=0
V/AudioPolicyManager(  293): isOffloadSupported: stream_type != MUSIC, returning false
I/OMXCodec(  293): Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
,I/OMXCodec(  293): Successfully allocated OMX node 'OMX.google.vorbis.decoder'
I/OMXCodec(  293): >>>UHQA initOutputFormat 16
I/AwesomePlayer(  293): Could not offload audio decode, try pcm offload
V/AudioPolicyManager(  293): isOffloadSupported: SR=44100, CM=0x1, Format=0x1c000001, StreamType=-1, BitRate=4294967295, duration=849387 us, has_video=0
V/AudioPolicyManager(  293): isOffloadSupported: stream_type != MUSIC, returning false
I/OMXCodec(  293): [OMX.google.vorbis.decoder] OMXCodec::start mState=1
I/OMXCodec(  293): [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
I/OMXCodec(  293): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
,I/OMXCodec(  293): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
V/AwesomePlayer(  293): finishAsyncPrepare_l
V/AwesomePlayer(  293): notifyListner_l() msg (200-MEDIA_INFO), ext1 (973), ext2 (0)
V/AudioCache(  293): notify(0xb05183d0, 200, 973, 0)
V/AudioCache(  293): ignored
V/AwesomePlayer(  293): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache(  293): notify(0xb05183d0, 5, 0, 0)
V/AudioCache(  293): ignored
V/AwesomePlayer(  293): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache(  293): notify(0xb05183d0, 1, 0, 0)
V/AudioCache(  293): prepared
V/AudioCache(  293): wait - success
V/MediaPlayerService(  293): start
V/StagefrightPlayer(  293): start
V/AwesomePlayer(  293): play
V/AwesomePlayer(  293): AwesomePlayer::play_l():: This is not a DRM content
V/AwesomePlayer(  293): startAudioPlayer_l, sendErrorNotification (0)
D/AudioPlayer(  293): start of Playback, useOffload 0
D/SHealthUpgrade(SHealthUpgradeUtil)( 7961): isShealthServiceInstalled() : HealthService is Installed.
D/SHealthUpgrade(SHealthUpgradeUtil)( 7961): isShealthService2xInstalled() : HEALTH SERVICE is INSTALLED.
D/SHealthUpgrade(SHealthUpgradeUtil)( 7961): isShealthService2xInstalled() : HEALTH SERVICE VERSION = 2.x
I/OMXCodec(  293): [OMX.google.vorbis.decoder] 0onCmdComplete  mState =  7
I/OMXCodec(  293): [OMX.google.vorbis.decoder] PORT_DISABLED(1)
I/OMXCodec(  293): >>>UHQA initOutputFormat 16
I/OMXCodec(  293): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
I/AudioPlayer(  293): Audio channels(2)
I/AudioPlayer(  293): Audioplayer kKeyAudioPCMFormat:0, 1, 0
I/AudioPlayer(  293): Audioplayer kKeyAudioPCMFormat read fail(2, 1)
V/AudioCache(  293): open(44100, 2, 0x0, 1, 0)
V/AwesomePlayer(  293): notifyListner_l() msg (6-MEDIA_STARTED), ext1 (0), ext2 (0)
V/AudioCache(  293): notify(0xb05183d0, 6, 0, 0)
V/AudioCache(  293): ignored
V/AwesomePlayer(  293): addBatteryData
,V/MediaPlayerService(  293): wait for playback complete
I/AudioPlayer(  293): First fillBuffer call!!
I/AudioPlayer(  293): >>> setAudioEffect Read mAudioFormat : 1, event : 235670794, value : 319688206
E/AudioPlayer(  293): >>> setAudioEffect Error mAudioFormat : 1, event : 235670794, value : 319688206
I/ActivityManager(  875): Killing 6972:com.samsung.android.app.watchmanagerstub/u0a112 (adj 15): bgCount ##41
,I/SO_AGENT( 7645): [com.sec.android.fota.osp.time.ServerTimeReceiver(47/onReceive)] No action is available before server time settings
,E/SMD     (  287): DCD ON
,I/SA      ( 7696): [SBR] StdBroadcastReceiver received Intent of  action.TIME_SET.
,I/OMXCodec(  293): [OMX.google.vorbis.decoder] End Of Stream
,V/AwesomePlayer(  293): postAudioEOS delayUs (0)
V/AwesomePlayer(  293): onCheckAudioStatus
V/AwesomePlayer(  293): onCheckAudioStatus() set AUDIO_AT_EOS flag
V/AwesomePlayer(  293): onStreamDone
V/AwesomePlayer(  293): MEDIA_PLAYBACK_COMPLETE
V/AwesomePlayer(  293): notifyListner_l() msg (2-MEDIA_PLAYBACK_COMPLETE), ext1 (0), ext2 (0)
V/AudioCache(  293): notify(0xb05183d0, 2, 0, 0)
V/AudioCache(  293): playback complete - thread will wake up later
V/AwesomePlayer(  293): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache(  293): notify(0xb05183d0, 7, 0, 0)
V/AudioCache(  293): ignored
V/AwesomePlayer(  293): cancelPlayerEvents (keepNotifications=1)
V/AwesomePlayer(  293): addBatteryData
V/AudioCache(  293): wait - success
V/StagefrightPlayer(  293): reset
,V/AwesomePlayer(  293): reset_l()
V/AwesomePlayer(  293): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  293): notify(0xb05183d0, 8, 0, 0)
V/AudioCache(  293): ignored
V/AwesomePlayer(  293): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  293): mAudioTrackVector clear
D/AudioPlayer(  293): reset: mPlaying=0 mReachedEOS=1 useOffload=0
I/OMXCodec(  293): [OMX.google.vorbis.decoder] stop mState=4
I/OMXCodec(  293): [OMX.google.vorbis.decoder] stop() sendCommand(0x75, OMX_CommandStateSet, OMX_StateIdle)
I/OMXCodec(  293): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
,I/OMXCodec(  293): [OMX.google.vorbis.decoder] stopOmxComponent_l() mstate = 1
I/OggExtractor(  293): OggSource::stop() mExtractor ref count = 1
I/OggExtractor(  293): OggSource::~OggSource() mExtractor !mStarted ref count = 1
I/OggExtractor(  293): ~OggSource --
I/OggExtractor(  293): ~OggExtractor ++
I/OggExtractor(  293): ~MyVorbisExtractor ++ 
I/OggExtractor(  293): ~MyVorbisExtractor --
I/OggExtractor(  293): ~OggExtractor --
,I/AudioPlayer(  293): reset out
V/AwesomePlayer(  293): reset_l() mAudioPlayer successfully deleted
I/SecVideoCapture(  293): SecVideoCapture destructor
I/SecVideoCapture(  293): reset
V/AwesomePlayer(  293): mSecCapture clear
I/SecMediaClock(  293): SecMediaClock destructor
V/AwesomePlayer(  293): mSecMediaClock clear
V/StagefrightPlayer(  293): ~StagefrightPlayer
V/StagefrightPlayer(  293): reset
V/AwesomePlayer(  293): reset_l()
V/AwesomePlayer(  293): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  293): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  293): mAudioTrackVector clear
V/AwesomePlayer(  293): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  293): mSecCapture clear
V/AwesomePlayer(  293): mSecMediaClock clear
V/AwesomePlayer(  293): destructor
V/AwesomePlayer(  293): reset_l()
V/AwesomePlayer(  293): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  293): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  293): mAudioTrackVector clear
V/AwesomePlayer(  293): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  293): mSecCapture clear
V/AwesomePlayer(  293): mSecMediaClock clear
,V/MediaPlayer( 7961): decode(35, 19257568, 9226)
V/MediaPlayerService(  293): decode(30, 19257568, 9226)
V/MediaPlayerService(  293): player type = 3
V/AwesomePlayer(  293): setDefault
V/AwesomePlayer(  293): constructor
V/AwesomePlayer(  293): setDefault
V/AwesomePlayer(  293): reset_l()
V/AwesomePlayer(  293): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  293): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  293): mAudioTrackVector clear
V/AwesomePlayer(  293): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  293): mSecCapture clear
V/AwesomePlayer(  293): mSecMediaClock clear
V/StagefrightPlayer(  293): StagefrightPlayer
V/AwesomePlayer(  293): setListener
V/StagefrightPlayer(  293): initCheck
V/AwesomePlayer(  293): setAudioSink
V/StagefrightPlayer(  293): setDataSource(30, 19257568, 9226)
V/AwesomePlayer(  293): reset_l()
V/AwesomePlayer(  293): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  293): notify(0xb03fc510, 8, 0, 0)
V/AudioCache(  293): ignored
V/AwesomePlayer(  293): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  293): mAudioTrackVector clear
V/AwesomePlayer(  293): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  293): mSecCapture clear
V/AwesomePlayer(  293): mSecMediaClock clear
D/Utils   (  293): printFileName fd(31) -> /system/priv-app/SHealth3_5/SHealth3_5.apk
,V/AwesomePlayer(  293): track of type 'audio/vorbis' does not publish bitrate
V/AwesomePlayer(  293): mBitrate = -1 bits/sec
I/OggExtractor(  293): OggSource::OggSource() mExtractor ref count = 4
V/AwesomePlayer(  293): current audio track index (0) is added to vector
V/AwesomePlayer(  293): setDataSource_l: Audio(1), Video(0)
I/AwesomePlayer(  293): checkRightsStatus is not necessary - AwesomePlayer::setDataSource_l
V/MediaPlayerService(  293): prepare
V/AwesomePlayer(  293): prepareAsync
V/MediaPlayerService(  293): wait for prepare
V/AwesomePlayer(  293): onPrepareAsyncEvent
I/SecMediaClock(  293): SecMediaClock constructor
I/SecMediaClock(  293): reset
I/SecVideoCapture(  293): SecVideoCapture constructor
I/SecVideoCapture(  293): reset
V/AwesomePlayer(  293): initAudioDecoder
V/AwesomePlayer(  293): checkOffloadExceptions is true
V/AudioPolicyManager(  293): isOffloadSupported: SR=44100, CM=0x3, Format=0x7000000, StreamType=-1, BitRate=4294967295, duration=404897 us, has_video=0
V/AudioPolicyManager(  293): isOffloadSupported: stream_type != MUSIC, returning false
I/OMXCodec(  293): Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
,I/OMXCodec(  293): Successfully allocated OMX node 'OMX.google.vorbis.decoder'
I/OMXCodec(  293): >>>UHQA initOutputFormat 16
I/AwesomePlayer(  293): Could not offload audio decode, try pcm offload
V/AudioPolicyManager(  293): isOffloadSupported: SR=44100, CM=0x1, Format=0x1c000001, StreamType=-1, BitRate=4294967295, duration=404897 us, has_video=0
V/AudioPolicyManager(  293): isOffloadSupported: stream_type != MUSIC, returning false
I/OMXCodec(  293): [OMX.google.vorbis.decoder] OMXCodec::start mState=1
I/OMXCodec(  293): [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
I/OMXCodec(  293): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
,I/OMXCodec(  293): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
V/AwesomePlayer(  293): finishAsyncPrepare_l
V/AwesomePlayer(  293): notifyListner_l() msg (200-MEDIA_INFO), ext1 (973), ext2 (0)
V/AudioCache(  293): notify(0xb03fc510, 200, 973, 0)
V/AudioCache(  293): ignored
V/AwesomePlayer(  293): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache(  293): notify(0xb03fc510, 5, 0, 0)
V/AudioCache(  293): ignored
V/AwesomePlayer(  293): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache(  293): notify(0xb03fc510, 1, 0, 0)
V/AudioCache(  293): prepared
V/AudioCache(  293): wait - success
V/MediaPlayerService(  293): start
V/StagefrightPlayer(  293): start
V/AwesomePlayer(  293): play
V/AwesomePlayer(  293): AwesomePlayer::play_l():: This is not a DRM content
V/AwesomePlayer(  293): startAudioPlayer_l, sendErrorNotification (0)
D/AudioPlayer(  293): start of Playback, useOffload 0
,I/OMXCodec(  293): [OMX.google.vorbis.decoder] 0onCmdComplete  mState =  7
I/OMXCodec(  293): [OMX.google.vorbis.decoder] PORT_DISABLED(1)
I/OMXCodec(  293): >>>UHQA initOutputFormat 16
I/OMXCodec(  293): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
,I/AudioPlayer(  293): Audio channels(2)
I/AudioPlayer(  293): Audioplayer kKeyAudioPCMFormat:0, 1, 0
I/AudioPlayer(  293): Audioplayer kKeyAudioPCMFormat read fail(2, 1)
V/AudioCache(  293): open(44100, 2, 0x0, 1, 0)
,V/AwesomePlayer(  293): notifyListner_l() msg (6-MEDIA_STARTED), ext1 (0), ext2 (0)
V/AudioCache(  293): notify(0xb03fc510, 6, 0, 0)
V/AudioCache(  293): ignored
V/AwesomePlayer(  293): addBatteryData
,I/AudioPlayer(  293): First fillBuffer call!!
I/AudioPlayer(  293): >>> setAudioEffect Read mAudioFormat : 1, event : 4587583, value : 4390976
V/MediaPlayerService(  293): wait for playback complete
E/AudioPlayer(  293): >>> setAudioEffect Error mAudioFormat : 1, event : 4587583, value : 4390976
,D/AdaptiveEventManager( 1169): removeAdaptiveEvent() requestClass = com.sec.android.app.shealth.walkingmate.service.WalkingMateDayStepService
D/AdaptiveEventManager( 1169): M updateContainers()
D/AdaptiveEventContainerSmall( 1169): C updatePedoContainer()
D/AdaptiveEventContainerSmall( 1169): handlePedoUpdate()
D/AdaptiveEventContainerSmall( 1169): pedoEvent == null
,I/OMXCodec(  293): [OMX.google.vorbis.decoder] End Of Stream
,D/AdaptiveEventManager( 1169): removeAdaptiveEvent() requestClass = com.sec.android.app.shealth.walkingmate.service.WalkingMateDayStepService
D/AdaptiveEventManager( 1169): M updateContainers()
D/AdaptiveEventContainerSmall( 1169): C updatePedoContainer()
D/AdaptiveEventContainerSmall( 1169): handlePedoUpdate()
D/AdaptiveEventContainerSmall( 1169): pedoEvent == null
,E/DatabaseUtils(  875): Writing exception to parcel
E/DatabaseUtils(  875): java.lang.NullPointerException: key == null
E/DatabaseUtils(  875): 	at android.util.LruCache.get(LruCache.java:112)
E/DatabaseUtils(  875): 	at com.android.providers.settings.SettingsProvider.lookupValue(SettingsProvider.java:982)
E/DatabaseUtils(  875): 	at com.android.providers.settings.SettingsProvider.call(SettingsProvider.java:822)
E/DatabaseUtils(  875): 	at android.content.ContentProvider$Transport.call(ContentProvider.java:370)
E/DatabaseUtils(  875): 	at android.content.ContentProviderNative.onTransact(ContentProviderNative.java:282)
E/DatabaseUtils(  875): 	at android.os.Binder.execTransact(Binder.java:446)
,V/AwesomePlayer(  293): postAudioEOS delayUs (0)
,V/AwesomePlayer(  293): onCheckAudioStatus
V/AwesomePlayer(  293): onCheckAudioStatus() set AUDIO_AT_EOS flag
V/AwesomePlayer(  293): onStreamDone
V/AwesomePlayer(  293): MEDIA_PLAYBACK_COMPLETE
V/AwesomePlayer(  293): notifyListner_l() msg (2-MEDIA_PLAYBACK_COMPLETE), ext1 (0), ext2 (0)
V/AudioCache(  293): notify(0xb03fc510, 2, 0, 0)
V/AudioCache(  293): playback complete - thread will wake up later
V/AwesomePlayer(  293): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache(  293): notify(0xb03fc510, 7, 0, 0)
V/AudioCache(  293): ignored
V/AwesomePlayer(  293): cancelPlayerEvents (keepNotifications=1)
,V/AwesomePlayer(  293): addBatteryData
V/AudioCache(  293): wait - success
V/StagefrightPlayer(  293): reset
,V/AwesomePlayer(  293): reset_l()
V/AwesomePlayer(  293): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  293): notify(0xb03fc510, 8, 0, 0)
V/AudioCache(  293): ignored
V/AwesomePlayer(  293): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  293): mAudioTrackVector clear
D/AudioPlayer(  293): reset: mPlaying=0 mReachedEOS=1 useOffload=0
I/OMXCodec(  293): [OMX.google.vorbis.decoder] stop mState=4
I/OMXCodec(  293): [OMX.google.vorbis.decoder] stop() sendCommand(0x76, OMX_CommandStateSet, OMX_StateIdle)
I/OMXCodec(  293): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
,I/OMXCodec(  293): [OMX.google.vorbis.decoder] stopOmxComponent_l() mstate = 1
I/OggExtractor(  293): OggSource::stop() mExtractor ref count = 1
I/OggExtractor(  293): OggSource::~OggSource() mExtractor !mStarted ref count = 1
I/OggExtractor(  293): ~OggSource --
I/OggExtractor(  293): ~OggExtractor ++
I/OggExtractor(  293): ~MyVorbisExtractor ++ 
I/OggExtractor(  293): ~MyVorbisExtractor --
I/OggExtractor(  293): ~OggExtractor --
,I/AudioPlayer(  293): reset out
V/AwesomePlayer(  293): reset_l() mAudioPlayer successfully deleted
I/SecVideoCapture(  293): SecVideoCapture destructor
I/SecVideoCapture(  293): reset
V/AwesomePlayer(  293): mSecCapture clear
I/SecMediaClock(  293): SecMediaClock destructor
V/AwesomePlayer(  293): mSecMediaClock clear
V/StagefrightPlayer(  293): ~StagefrightPlayer
V/StagefrightPlayer(  293): reset
V/AwesomePlayer(  293): reset_l()
V/AwesomePlayer(  293): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  293): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  293): mAudioTrackVector clear
V/AwesomePlayer(  293): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  293): mSecCapture clear
V/AwesomePlayer(  293): mSecMediaClock clear
V/AwesomePlayer(  293): destructor
V/AwesomePlayer(  293): reset_l()
V/AwesomePlayer(  293): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  293): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  293): mAudioTrackVector clear
V/AwesomePlayer(  293): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  293): mSecCapture clear
V/AwesomePlayer(  293): mSecMediaClock clear
V/MediaPlayer( 7961): decode(37, 19364180, 4890)
V/MediaPlayerService(  293): decode(30, 19364180, 4890)
,V/MediaPlayerService(  293): player type = 3
V/AwesomePlayer(  293): setDefault
V/AwesomePlayer(  293): constructor
V/AwesomePlayer(  293): setDefault
V/AwesomePlayer(  293): reset_l()
V/AwesomePlayer(  293): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  293): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  293): mAudioTrackVector clear
V/AwesomePlayer(  293): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  293): mSecCapture clear
V/AwesomePlayer(  293): mSecMediaClock clear
V/StagefrightPlayer(  293): StagefrightPlayer
V/AwesomePlayer(  293): setListener
V/StagefrightPlayer(  293): initCheck
V/AwesomePlayer(  293): setAudioSink
V/StagefrightPlayer(  293): setDataSource(30, 19364180, 4890)
V/AwesomePlayer(  293): reset_l()
V/AwesomePlayer(  293): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  293): notify(0xb02092e0, 8, 0, 0)
V/AudioCache(  293): ignored
V/AwesomePlayer(  293): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  293): mAudioTrackVector clear
V/AwesomePlayer(  293): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  293): mSecCapture clear
V/AwesomePlayer(  293): mSecMediaClock clear
D/Utils   (  293): printFileName fd(31) -> /system/priv-app/SHealth3_5/SHealth3_5.apk
,V/AwesomePlayer(  293): track of type 'audio/vorbis' does not publish bitrate
V/AwesomePlayer(  293): mBitrate = -1 bits/sec
I/OggExtractor(  293): OggSource::OggSource() mExtractor ref count = 4
V/AwesomePlayer(  293): current audio track index (0) is added to vector
V/AwesomePlayer(  293): setDataSource_l: Audio(1), Video(0)
I/AwesomePlayer(  293): checkRightsStatus is not necessary - AwesomePlayer::setDataSource_l
V/MediaPlayerService(  293): prepare
V/AwesomePlayer(  293): prepareAsync
V/MediaPlayerService(  293): wait for prepare
V/AwesomePlayer(  293): onPrepareAsyncEvent
I/SecMediaClock(  293): SecMediaClock constructor
I/SecMediaClock(  293): reset
I/SecVideoCapture(  293): SecVideoCapture constructor
I/SecVideoCapture(  293): reset
V/AwesomePlayer(  293): initAudioDecoder
V/AwesomePlayer(  293): checkOffloadExceptions is true
V/AudioPolicyManager(  293): isOffloadSupported: SR=44100, CM=0x1, Format=0x7000000, StreamType=-1, BitRate=4294967295, duration=64058 us, has_video=0
V/AudioPolicyManager(  293): isOffloadSupported: stream_type != MUSIC, returning false
I/OMXCodec(  293): Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
,I/OMXCodec(  293): Successfully allocated OMX node 'OMX.google.vorbis.decoder'
I/OMXCodec(  293): >>>UHQA initOutputFormat 16
I/AwesomePlayer(  293): Could not offload audio decode, try pcm offload
V/AudioPolicyManager(  293): isOffloadSupported: SR=44100, CM=0x1, Format=0x1c000001, StreamType=-1, BitRate=4294967295, duration=64058 us, has_video=0
V/AudioPolicyManager(  293): isOffloadSupported: stream_type != MUSIC, returning false
I/OMXCodec(  293): [OMX.google.vorbis.decoder] OMXCodec::start mState=1
I/OMXCodec(  293): [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
I/OMXCodec(  293): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
,I/OMXCodec(  293): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
,V/AwesomePlayer(  293): finishAsyncPrepare_l
V/AwesomePlayer(  293): notifyListner_l() msg (200-MEDIA_INFO), ext1 (973), ext2 (0)
V/AudioCache(  293): notify(0xb02092e0, 200, 973, 0)
V/AudioCache(  293): ignored
V/AwesomePlayer(  293): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache(  293): notify(0xb02092e0, 5, 0, 0)
V/AudioCache(  293): ignored
V/AwesomePlayer(  293): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache(  293): notify(0xb02092e0, 1, 0, 0)
V/AudioCache(  293): prepared
V/AudioCache(  293): wait - success
V/MediaPlayerService(  293): start
V/StagefrightPlayer(  293): start
,V/AwesomePlayer(  293): play
V/AwesomePlayer(  293): AwesomePlayer::play_l():: This is not a DRM content
V/AwesomePlayer(  293): startAudioPlayer_l, sendErrorNotification (0)
D/AudioPlayer(  293): start of Playback, useOffload 0
,I/OMXCodec(  293): [OMX.google.vorbis.decoder] 0onCmdComplete  mState =  7
I/OMXCodec(  293): [OMX.google.vorbis.decoder] PORT_DISABLED(1)
I/OMXCodec(  293): >>>UHQA initOutputFormat 16
I/OMXCodec(  293): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
,I/AudioPlayer(  293): Audio channels(1)
I/AudioPlayer(  293): Audioplayer kKeyAudioPCMFormat:0, 1, 0
I/AudioPlayer(  293): Audioplayer kKeyAudioPCMFormat read fail(1, 1)
V/AudioCache(  293): open(44100, 1, 0x0, 1, 0)
,V/AwesomePlayer(  293): notifyListner_l() msg (6-MEDIA_STARTED), ext1 (0), ext2 (0)
V/AudioCache(  293): notify(0xb02092e0, 6, 0, 0)
V/AudioCache(  293): ignored
V/AwesomePlayer(  293): addBatteryData
V/MediaPlayerService(  293): wait for playback complete
I/AudioPlayer(  293): First fillBuffer call!!
,I/AudioPlayer(  293): >>> setAudioEffect Read mAudioFormat : 1, event : 168430090, value : 151652874
E/AudioPlayer(  293): >>> setAudioEffect Error mAudioFormat : 1, event : 168430090, value : 151652874
,I/OMXCodec(  293): [OMX.google.vorbis.decoder] End Of Stream
,V/AwesomePlayer(  293): postAudioEOS delayUs (0)
,V/AwesomePlayer(  293): onCheckAudioStatus
V/AwesomePlayer(  293): onCheckAudioStatus() set AUDIO_AT_EOS flag
V/AwesomePlayer(  293): onStreamDone
V/AwesomePlayer(  293): MEDIA_PLAYBACK_COMPLETE
V/AwesomePlayer(  293): notifyListner_l() msg (2-MEDIA_PLAYBACK_COMPLETE), ext1 (0), ext2 (0)
V/AudioCache(  293): notify(0xb02092e0, 2, 0, 0)
V/AudioCache(  293): playback complete - thread will wake up later
V/AwesomePlayer(  293): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache(  293): notify(0xb02092e0, 7, 0, 0)
V/AudioCache(  293): ignored
V/AwesomePlayer(  293): cancelPlayerEvents (keepNotifications=1)
V/AwesomePlayer(  293): addBatteryData
V/AudioCache(  293): wait - success
V/StagefrightPlayer(  293): reset
V/AwesomePlayer(  293): reset_l()
V/AwesomePlayer(  293): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  293): notify(0xb02092e0, 8, 0, 0)
V/AudioCache(  293): ignored
V/AwesomePlayer(  293): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  293): mAudioTrackVector clear
D/AudioPlayer(  293): reset: mPlaying=0 mReachedEOS=1 useOffload=0
I/OMXCodec(  293): [OMX.google.vorbis.decoder] stop mState=4
I/OMXCodec(  293): [OMX.google.vorbis.decoder] stop() sendCommand(0x77, OMX_CommandStateSet, OMX_StateIdle)
I/OMXCodec(  293): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
I/OMXCodec(  293): [OMX.google.vorbis.decoder] stopOmxComponent_l() mstate = 1
I/OggExtractor(  293): OggSource::stop() mExtractor ref count = 1
I/OggExtractor(  293): OggSource::~OggSource() mExtractor !mStarted ref count = 1
I/OggExtractor(  293): ~OggSource --
I/OggExtractor(  293): ~OggExtractor ++
I/OggExtractor(  293): ~MyVorbisExtractor ++ 
I/OggExtractor(  293): ~MyVorbisExtractor --
I/OggExtractor(  293): ~OggExtractor --
,I/AudioPlayer(  293): reset out
V/AwesomePlayer(  293): reset_l() mAudioPlayer successfully deleted
I/SecVideoCapture(  293): SecVideoCapture destructor
I/SecVideoCapture(  293): reset
V/AwesomePlayer(  293): mSecCapture clear
I/SecMediaClock(  293): SecMediaClock destructor
V/AwesomePlayer(  293): mSecMediaClock clear
V/StagefrightPlayer(  293): ~StagefrightPlayer
V/StagefrightPlayer(  293): reset
V/AwesomePlayer(  293): reset_l()
V/AwesomePlayer(  293): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  293): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  293): mAudioTrackVector clear
V/AwesomePlayer(  293): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  293): mSecCapture clear
V/AwesomePlayer(  293): mSecMediaClock clear
V/AwesomePlayer(  293): destructor
V/AwesomePlayer(  293): reset_l()
V/AwesomePlayer(  293): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  293): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  293): mAudioTrackVector clear
V/AwesomePlayer(  293): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  293): mSecCapture clear
V/AwesomePlayer(  293): mSecMediaClock clear
V/MediaPlayer( 7961): decode(38, 19290344, 17329)
V/MediaPlayerService(  293): decode(30, 19290344, 17329)
,V/MediaPlayerService(  293): player type = 3
V/AwesomePlayer(  293): setDefault
V/AwesomePlayer(  293): constructor
V/AwesomePlayer(  293): setDefault
V/AwesomePlayer(  293): reset_l()
V/AwesomePlayer(  293): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  293): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  293): mAudioTrackVector clear
V/AwesomePlayer(  293): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  293): mSecCapture clear
V/AwesomePlayer(  293): mSecMediaClock clear
V/StagefrightPlayer(  293): StagefrightPlayer
V/AwesomePlayer(  293): setListener
V/StagefrightPlayer(  293): initCheck
V/AwesomePlayer(  293): setAudioSink
V/StagefrightPlayer(  293): setDataSource(30, 19290344, 17329)
V/AwesomePlayer(  293): reset_l()
V/AwesomePlayer(  293): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  293): notify(0xb19272e0, 8, 0, 0)
V/AudioCache(  293): ignored
V/AwesomePlayer(  293): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  293): mAudioTrackVector clear
V/AwesomePlayer(  293): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  293): mSecCapture clear
V/AwesomePlayer(  293): mSecMediaClock clear
D/Utils   (  293): printFileName fd(31) -> /system/priv-app/SHealth3_5/SHealth3_5.apk
,V/AwesomePlayer(  293): track of type 'audio/vorbis' does not publish bitrate
V/AwesomePlayer(  293): mBitrate = -1 bits/sec
I/OggExtractor(  293): OggSource::OggSource() mExtractor ref count = 4
V/AwesomePlayer(  293): current audio track index (0) is added to vector
V/AwesomePlayer(  293): setDataSource_l: Audio(1), Video(0)
,I/AwesomePlayer(  293): checkRightsStatus is not necessary - AwesomePlayer::setDataSource_l
V/MediaPlayerService(  293): prepare
V/AwesomePlayer(  293): prepareAsync
V/MediaPlayerService(  293): wait for prepare
V/AwesomePlayer(  293): onPrepareAsyncEvent
I/SecMediaClock(  293): SecMediaClock constructor
I/SecMediaClock(  293): reset
,I/SecVideoCapture(  293): SecVideoCapture constructor
I/SecVideoCapture(  293): reset
V/AwesomePlayer(  293): initAudioDecoder
V/AwesomePlayer(  293): checkOffloadExceptions is true
V/AudioPolicyManager(  293): isOffloadSupported: SR=44100, CM=0x3, Format=0x7000000, StreamType=-1, BitRate=4294967295, duration=857142 us, has_video=0
V/AudioPolicyManager(  293): isOffloadSupported: stream_type != MUSIC, returning false
I/OMXCodec(  293): Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
,I/OMXCodec(  293): Successfully allocated OMX node 'OMX.google.vorbis.decoder'
,I/OMXCodec(  293): >>>UHQA initOutputFormat 16
I/AwesomePlayer(  293): Could not offload audio decode, try pcm offload
V/AudioPolicyManager(  293): isOffloadSupported: SR=44100, CM=0x1, Format=0x1c000001, StreamType=-1, BitRate=4294967295, duration=857142 us, has_video=0
V/AudioPolicyManager(  293): isOffloadSupported: stream_type != MUSIC, returning false
I/OMXCodec(  293): [OMX.google.vorbis.decoder] OMXCodec::start mState=1
I/OMXCodec(  293): [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
I/OMXCodec(  293): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
,I/OMXCodec(  293): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
,I/SA      ( 7696): [RC New] Execute method=[GET] start
V/AwesomePlayer(  293): finishAsyncPrepare_l
V/AwesomePlayer(  293): notifyListner_l() msg (200-MEDIA_INFO), ext1 (973), ext2 (0)
V/AudioCache(  293): notify(0xb19272e0, 200, 973, 0)
V/AudioCache(  293): ignored
V/AwesomePlayer(  293): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache(  293): notify(0xb19272e0, 5, 0, 0)
,V/AudioCache(  293): ignored
V/AwesomePlayer(  293): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache(  293): notify(0xb19272e0, 1, 0, 0)
V/AudioCache(  293): prepared
V/AudioCache(  293): wait - success
V/MediaPlayerService(  293): start
V/StagefrightPlayer(  293): start
V/AwesomePlayer(  293): play
V/AwesomePlayer(  293): AwesomePlayer::play_l():: This is not a DRM content
V/AwesomePlayer(  293): startAudioPlayer_l, sendErrorNotification (0)
D/AudioPlayer(  293): start of Playback, useOffload 0
,I/OMXCodec(  293): [OMX.google.vorbis.decoder] 0onCmdComplete  mState =  7
I/OMXCodec(  293): [OMX.google.vorbis.decoder] PORT_DISABLED(1)
I/OMXCodec(  293): >>>UHQA initOutputFormat 16
I/OMXCodec(  293): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
,I/ActivityManager(  875): Killing 6987:com.samsung.android.magazine.service/u0a118 (adj 15): bgCount ##41
,I/AudioPlayer(  293): Audio channels(2)
I/AudioPlayer(  293): Audioplayer kKeyAudioPCMFormat:0, 1, 0
I/AudioPlayer(  293): Audioplayer kKeyAudioPCMFormat read fail(2, 1)
V/AudioCache(  293): open(44100, 2, 0x0, 1, 0)
V/AwesomePlayer(  293): notifyListner_l() msg (6-MEDIA_STARTED), ext1 (0), ext2 (0)
V/AudioCache(  293): notify(0xb19272e0, 6, 0, 0)
V/AudioCache(  293): ignored
V/AwesomePlayer(  293): addBatteryData
V/MediaPlayerService(  293): wait for playback complete
,I/AudioPlayer(  293): First fillBuffer call!!
,I/AudioPlayer(  293): >>> setAudioEffect Read mAudioFormat : 1, event : 235670794, value : 319688206
E/AudioPlayer(  293): >>> setAudioEffect Error mAudioFormat : 1, event : 235670794, value : 319688206
,E/ActivityManager(  875): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  875): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  875): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  875): checkUser: useridlist=null, currentuser=0
,W/libprocessgroup(  875): failed to open /acct/uid_10112/pid_6972/cgroup.procs: No such file or directory
,I/jxcore-log( 7393): BLE supported!!
I/jxcore-log( 7393): 
,E/Zygote  ( 8040): MountEmulatedStorage()
,E/Zygote  ( 8040): v2
I/libpersona( 8040): KNOX_SDCARD checking this for 10067
I/libpersona( 8040): KNOX_SDCARD not a persona
,I/OMXCodec(  293): [OMX.google.vorbis.decoder] End Of Stream
,I/ActivityManager(  875): Start proc com.samsung.android.scloud.sync for broadcast com.samsung.android.scloud.sync/com.sec.android.sCloudSync.Receivers.TimeChangedReceiver: pid=8040 uid=10067 gids={50067, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,V/AwesomePlayer(  293): postAudioEOS delayUs (0)
,V/AwesomePlayer(  293): onCheckAudioStatus
V/AwesomePlayer(  293): onCheckAudioStatus() set AUDIO_AT_EOS flag
V/AwesomePlayer(  293): onStreamDone
V/AwesomePlayer(  293): MEDIA_PLAYBACK_COMPLETE
V/AwesomePlayer(  293): notifyListner_l() msg (2-MEDIA_PLAYBACK_COMPLETE), ext1 (0), ext2 (0)
V/AudioCache(  293): notify(0xb19272e0, 2, 0, 0)
,V/AudioCache(  293): playback complete - thread will wake up later
V/AwesomePlayer(  293): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache(  293): notify(0xb19272e0, 7, 0, 0)
V/AudioCache(  293): ignored
V/AwesomePlayer(  293): cancelPlayerEvents (keepNotifications=1)
V/AwesomePlayer(  293): addBatteryData
V/AudioCache(  293): wait - success
V/StagefrightPlayer(  293): reset
,V/AwesomePlayer(  293): reset_l()
V/AwesomePlayer(  293): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  293): notify(0xb19272e0, 8, 0, 0)
V/AudioCache(  293): ignored
V/AwesomePlayer(  293): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  293): mAudioTrackVector clear
D/AudioPlayer(  293): reset: mPlaying=0 mReachedEOS=1 useOffload=0
I/OMXCodec(  293): [OMX.google.vorbis.decoder] stop mState=4
I/OMXCodec(  293): [OMX.google.vorbis.decoder] stop() sendCommand(0x78, OMX_CommandStateSet, OMX_StateIdle)
I/OMXCodec(  293): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
,I/OMXCodec(  293): [OMX.google.vorbis.decoder] stopOmxComponent_l() mstate = 1
I/OggExtractor(  293): OggSource::stop() mExtractor ref count = 1
I/OggExtractor(  293): OggSource::~OggSource() mExtractor !mStarted ref count = 1
I/OggExtractor(  293): ~OggSource --
I/OggExtractor(  293): ~OggExtractor ++
I/OggExtractor(  293): ~MyVorbisExtractor ++ 
I/OggExtractor(  293): ~MyVorbisExtractor --
I/OggExtractor(  293): ~OggExtractor --
,I/AudioPlayer(  293): reset out
V/AwesomePlayer(  293): reset_l() mAudioPlayer successfully deleted
I/SecVideoCapture(  293): SecVideoCapture destructor
I/SecVideoCapture(  293): reset
V/AwesomePlayer(  293): mSecCapture clear
I/SecMediaClock(  293): SecMediaClock destructor
V/AwesomePlayer(  293): mSecMediaClock clear
V/StagefrightPlayer(  293): ~StagefrightPlayer
V/StagefrightPlayer(  293): reset
V/AwesomePlayer(  293): reset_l()
V/AwesomePlayer(  293): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  293): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  293): mAudioTrackVector clear
V/AwesomePlayer(  293): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  293): mSecCapture clear
V/AwesomePlayer(  293): mSecMediaClock clear
V/AwesomePlayer(  293): destructor
V/AwesomePlayer(  293): reset_l()
V/AwesomePlayer(  293): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  293): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  293): mAudioTrackVector clear
V/AwesomePlayer(  293): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  293): mSecCapture clear
V/AwesomePlayer(  293): mSecMediaClock clear
,V/MediaPlayer( 7961): decode(36, 19190536, 6644)
,E/Watchdog(  875): !@Sync 3
,V/MediaPlayerService(  293): decode(30, 19190536, 6644)
,I/SELinux ( 8040): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
V/MediaPlayerService(  293): player type = 3
V/AwesomePlayer(  293): setDefault
V/AwesomePlayer(  293): constructor
,V/AwesomePlayer(  293): setDefault
V/AwesomePlayer(  293): reset_l()
V/AwesomePlayer(  293): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  293): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  293): mAudioTrackVector clear
,V/AwesomePlayer(  293): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  293): mSecCapture clear
V/AwesomePlayer(  293): mSecMediaClock clear
V/StagefrightPlayer(  293): StagefrightPlayer
V/AwesomePlayer(  293): setListener
V/StagefrightPlayer(  293): initCheck
V/AwesomePlayer(  293): setAudioSink
V/StagefrightPlayer(  293): setDataSource(30, 19190536, 6644)
V/AwesomePlayer(  293): reset_l()
V/AwesomePlayer(  293): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  293): notify(0xafa141a0, 8, 0, 0)
V/AudioCache(  293): ignored
V/AwesomePlayer(  293): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  293): mAudioTrackVector clear
V/AwesomePlayer(  293): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  293): mSecCapture clear
V/AwesomePlayer(  293): mSecMediaClock clear
D/Utils   (  293): printFileName fd(31) -> /system/priv-app/SHealth3_5/SHealth3_5.apk
I/SELinux ( 8040): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 8040): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,V/AwesomePlayer(  293): track of type 'audio/vorbis' does not publish bitrate
V/AwesomePlayer(  293): mBitrate = -1 bits/sec
I/OggExtractor(  293): OggSource::OggSource() mExtractor ref count = 4
V/AwesomePlayer(  293): current audio track index (0) is added to vector
V/AwesomePlayer(  293): setDataSource_l: Audio(1), Video(0)
I/AwesomePlayer(  293): checkRightsStatus is not necessary - AwesomePlayer::setDataSource_l
V/MediaPlayerService(  293): prepare
V/AwesomePlayer(  293): prepareAsync
V/MediaPlayerService(  293): wait for prepare
V/AwesomePlayer(  293): onPrepareAsyncEvent
I/SecMediaClock(  293): SecMediaClock constructor
I/SecMediaClock(  293): reset
I/SecVideoCapture(  293): SecVideoCapture constructor
I/SecVideoCapture(  293): reset
V/AwesomePlayer(  293): initAudioDecoder
V/AwesomePlayer(  293): checkOffloadExceptions is true
V/AudioPolicyManager(  293): isOffloadSupported: SR=44100, CM=0x1, Format=0x7000000, StreamType=-1, BitRate=4294967295, duration=213446 us, has_video=0
V/AudioPolicyManager(  293): isOffloadSupported: stream_type != MUSIC, returning false
I/OMXCodec(  293): Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
,I/OMXCodec(  293): Successfully allocated OMX node 'OMX.google.vorbis.decoder'
I/OMXCodec(  293): >>>UHQA initOutputFormat 16
I/AwesomePlayer(  293): Could not offload audio decode, try pcm offload
V/AudioPolicyManager(  293): isOffloadSupported: SR=44100, CM=0x1, Format=0x1c000001, StreamType=-1, BitRate=4294967295, duration=213446 us, has_video=0
V/AudioPolicyManager(  293): isOffloadSupported: stream_type != MUSIC, returning false
I/OMXCodec(  293): [OMX.google.vorbis.decoder] OMXCodec::start mState=1
I/OMXCodec(  293): [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
I/OMXCodec(  293): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
,I/OMXCodec(  293): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
V/AwesomePlayer(  293): finishAsyncPrepare_l
V/AwesomePlayer(  293): notifyListner_l() msg (200-MEDIA_INFO), ext1 (973), ext2 (0)
V/AudioCache(  293): notify(0xafa141a0, 200, 973, 0)
V/AudioCache(  293): ignored
V/AwesomePlayer(  293): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache(  293): notify(0xafa141a0, 5, 0, 0)
V/AudioCache(  293): ignored
V/AwesomePlayer(  293): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache(  293): notify(0xafa141a0, 1, 0, 0)
V/AudioCache(  293): prepared
V/AudioCache(  293): wait - success
V/MediaPlayerService(  293): start
V/StagefrightPlayer(  293): start
V/AwesomePlayer(  293): play
V/AwesomePlayer(  293): AwesomePlayer::play_l():: This is not a DRM content
V/AwesomePlayer(  293): startAudioPlayer_l, sendErrorNotification (0)
D/AudioPlayer(  293): start of Playback, useOffload 0
,I/OMXCodec(  293): [OMX.google.vorbis.decoder] 0onCmdComplete  mState =  7
I/OMXCodec(  293): [OMX.google.vorbis.decoder] PORT_DISABLED(1)
I/OMXCodec(  293): >>>UHQA initOutputFormat 16
I/OMXCodec(  293): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
,I/AudioPlayer(  293): Audio channels(1)
,I/AudioPlayer(  293): Audioplayer kKeyAudioPCMFormat:0, 1, 0
I/AudioPlayer(  293): Audioplayer kKeyAudioPCMFormat read fail(1, 1)
V/AudioCache(  293): open(44100, 1, 0x0, 1, 0)
,V/AwesomePlayer(  293): notifyListner_l() msg (6-MEDIA_STARTED), ext1 (0), ext2 (0)
V/AudioCache(  293): notify(0xafa141a0, 6, 0, 0)
I/AudioPlayer(  293): First fillBuffer call!!
I/AudioPlayer(  293): >>> setAudioEffect Read mAudioFormat : 1, event : 168430090, value : 151652874
E/AudioPlayer(  293): >>> setAudioEffect Error mAudioFormat : 1, event : 168430090, value : 151652874
V/AudioCache(  293): ignored
V/AwesomePlayer(  293): addBatteryData
,V/MediaPlayerService(  293): wait for playback complete
,I/OMXCodec(  293): [OMX.google.vorbis.decoder] End Of Stream
,V/AwesomePlayer(  293): postAudioEOS delayUs (0)
V/AwesomePlayer(  293): onCheckAudioStatus
V/AwesomePlayer(  293): onCheckAudioStatus() set AUDIO_AT_EOS flag
V/AwesomePlayer(  293): onStreamDone
V/AwesomePlayer(  293): MEDIA_PLAYBACK_COMPLETE
V/AwesomePlayer(  293): notifyListner_l() msg (2-MEDIA_PLAYBACK_COMPLETE), ext1 (0), ext2 (0)
V/AudioCache(  293): notify(0xafa141a0, 2, 0, 0)
V/AudioCache(  293): playback complete - thread will wake up later
V/AwesomePlayer(  293): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache(  293): notify(0xafa141a0, 7, 0, 0)
V/AudioCache(  293): ignored
V/AwesomePlayer(  293): cancelPlayerEvents (keepNotifications=1)
V/AwesomePlayer(  293): addBatteryData
V/AudioCache(  293): wait - success
V/StagefrightPlayer(  293): reset
V/AwesomePlayer(  293): reset_l()
V/AwesomePlayer(  293): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  293): notify(0xafa141a0, 8, 0, 0)
V/AudioCache(  293): ignored
V/AwesomePlayer(  293): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  293): mAudioTrackVector clear
D/AudioPlayer(  293): reset: mPlaying=0 mReachedEOS=1 useOffload=0
I/OMXCodec(  293): [OMX.google.vorbis.decoder] stop mState=4
I/OMXCodec(  293): [OMX.google.vorbis.decoder] stop() sendCommand(0x79, OMX_CommandStateSet, OMX_StateIdle)
I/OMXCodec(  293): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
I/OMXCodec(  293): [OMX.google.vorbis.decoder] stopOmxComponent_l() mstate = 1
I/OggExtractor(  293): OggSource::stop() mExtractor ref count = 1
I/OggExtractor(  293): OggSource::~OggSource() mExtractor !mStarted ref count = 1
I/OggExtractor(  293): ~OggSource --
I/OggExtractor(  293): ~OggExtractor ++
I/OggExtractor(  293): ~MyVorbisExtractor ++ 
I/OggExtractor(  293): ~MyVorbisExtractor --
I/OggExtractor(  293): ~OggExtractor --
,I/AudioPlayer(  293): reset out
V/AwesomePlayer(  293): reset_l() mAudioPlayer successfully deleted
I/SecVideoCapture(  293): SecVideoCapture destructor
I/SecVideoCapture(  293): reset
V/AwesomePlayer(  293): mSecCapture clear
I/SecMediaClock(  293): SecMediaClock destructor
V/AwesomePlayer(  293): mSecMediaClock clear
V/StagefrightPlayer(  293): ~StagefrightPlayer
V/StagefrightPlayer(  293): reset
V/AwesomePlayer(  293): reset_l()
V/AwesomePlayer(  293): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  293): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  293): mAudioTrackVector clear
V/AwesomePlayer(  293): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  293): mSecCapture clear
V/AwesomePlayer(  293): mSecMediaClock clear
V/AwesomePlayer(  293): destructor
V/AwesomePlayer(  293): reset_l()
V/AwesomePlayer(  293): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  293): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  293): mAudioTrackVector clear
V/AwesomePlayer(  293): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  293): mSecCapture clear
V/AwesomePlayer(  293): mSecMediaClock clear
V/MediaPlayer( 7961): decode(40, 19266876, 23389)
,V/MediaPlayerService(  293): decode(30, 19266876, 23389)
,W/libprocessgroup(  875): failed to open /acct/uid_10118/pid_6987/cgroup.procs: No such file or directory
,V/MediaPlayerService(  293): player type = 3
V/AwesomePlayer(  293): setDefault
V/AwesomePlayer(  293): constructor
,V/AwesomePlayer(  293): setDefault
V/AwesomePlayer(  293): reset_l()
V/AwesomePlayer(  293): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  293): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  293): mAudioTrackVector clear
V/AwesomePlayer(  293): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  293): mSecCapture clear
V/AwesomePlayer(  293): mSecMediaClock clear
V/StagefrightPlayer(  293): StagefrightPlayer
V/AwesomePlayer(  293): setListener
V/StagefrightPlayer(  293): initCheck
V/AwesomePlayer(  293): setAudioSink
V/StagefrightPlayer(  293): setDataSource(30, 19266876, 23389)
V/AwesomePlayer(  293): reset_l()
V/AwesomePlayer(  293): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  293): notify(0xb05183d0, 8, 0, 0)
V/AudioCache(  293): ignored
V/AwesomePlayer(  293): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  293): mAudioTrackVector clear
V/AwesomePlayer(  293): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  293): mSecCapture clear
V/AwesomePlayer(  293): mSecMediaClock clear
D/Utils   (  293): printFileName fd(31) -> /system/priv-app/SHealth3_5/SHealth3_5.apk
,V/AwesomePlayer(  293): track of type 'audio/vorbis' does not publish bitrate
V/AwesomePlayer(  293): mBitrate = -1 bits/sec
I/OggExtractor(  293): OggSource::OggSource() mExtractor ref count = 4
V/AwesomePlayer(  293): current audio track index (0) is added to vector
V/AwesomePlayer(  293): setDataSource_l: Audio(1), Video(0)
I/AwesomePlayer(  293): checkRightsStatus is not necessary - AwesomePlayer::setDataSource_l
V/MediaPlayerService(  293): prepare
V/AwesomePlayer(  293): prepareAsync
V/MediaPlayerService(  293): wait for prepare
V/AwesomePlayer(  293): onPrepareAsyncEvent
I/SecMediaClock(  293): SecMediaClock constructor
I/SecMediaClock(  293): reset
I/SecVideoCapture(  293): SecVideoCapture constructor
I/SecVideoCapture(  293): reset
V/AwesomePlayer(  293): initAudioDecoder
V/AwesomePlayer(  293): checkOffloadExceptions is true
V/AudioPolicyManager(  293): isOffloadSupported: SR=44100, CM=0x3, Format=0x7000000, StreamType=-1, BitRate=4294967295, duration=1250000 us, has_video=0
V/AudioPolicyManager(  293): isOffloadSupported: stream_type != MUSIC, returning false
I/OMXCodec(  293): Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
,I/OMXCodec(  293): Successfully allocated OMX node 'OMX.google.vorbis.decoder'
I/OMXCodec(  293): >>>UHQA initOutputFormat 16
I/AwesomePlayer(  293): Could not offload audio decode, try pcm offload
V/AudioPolicyManager(  293): isOffloadSupported: SR=44100, CM=0x1, Format=0x1c000001, StreamType=-1, BitRate=4294967295, duration=1250000 us, has_video=0
V/AudioPolicyManager(  293): isOffloadSupported: stream_type != MUSIC, returning false
I/OMXCodec(  293): [OMX.google.vorbis.decoder] OMXCodec::start mState=1
I/OMXCodec(  293): [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
I/OMXCodec(  293): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
,D/TimaKeyStoreProvider( 8040): TimaSignature is unavailable
,D/ActivityThread( 8040): Added TimaKeyStore provider
,I/OMXCodec(  293): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
,I/SA      ( 7696): [RC New] Security=[true]
,V/AwesomePlayer(  293): finishAsyncPrepare_l
V/AwesomePlayer(  293): notifyListner_l() msg (200-MEDIA_INFO), ext1 (973), ext2 (0)
V/AudioCache(  293): notify(0xb05183d0, 200, 973, 0)
V/AudioCache(  293): ignored
V/AwesomePlayer(  293): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache(  293): notify(0xb05183d0, 5, 0, 0)
V/AudioCache(  293): ignored
V/AwesomePlayer(  293): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache(  293): notify(0xb05183d0, 1, 0, 0)
V/AudioCache(  293): prepared
V/AudioCache(  293): wait - success
V/MediaPlayerService(  293): start
V/StagefrightPlayer(  293): start
,V/AwesomePlayer(  293): play
V/AwesomePlayer(  293): AwesomePlayer::play_l():: This is not a DRM content
V/AwesomePlayer(  293): startAudioPlayer_l, sendErrorNotification (0)
D/AudioPlayer(  293): start of Playback, useOffload 0
,I/System.out( 7696): Thread-1270(ApacheHTTPLog):Reading from variable values from setDefaultValuesToVariables
,I/OMXCodec(  293): [OMX.google.vorbis.decoder] 0onCmdComplete  mState =  7
I/OMXCodec(  293): [OMX.google.vorbis.decoder] PORT_DISABLED(1)
I/OMXCodec(  293): >>>UHQA initOutputFormat 16
I/OMXCodec(  293): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
D/ResourcesManager( 8040): creating new AssetManager and set to /system/priv-app/sCloudDataSync/sCloudDataSync.apk
,I/AudioPlayer(  293): Audio channels(2)
I/AudioPlayer(  293): Audioplayer kKeyAudioPCMFormat:0, 1, 0
I/AudioPlayer(  293): Audioplayer kKeyAudioPCMFormat read fail(2, 1)
V/AudioCache(  293): open(44100, 2, 0x0, 1, 0)
,V/AwesomePlayer(  293): notifyListner_l() msg (6-MEDIA_STARTED), ext1 (0), ext2 (0)
V/AudioCache(  293): notify(0xb05183d0, 6, 0, 0)
V/AudioCache(  293): ignored
V/AwesomePlayer(  293): addBatteryData
V/MediaPlayerService(  293): wait for playback complete
I/AudioPlayer(  293): First fillBuffer call!!
,I/AudioPlayer(  293): >>> setAudioEffect Read mAudioFormat : 1, event : 235670794, value : 319688206
E/AudioPlayer(  293): >>> setAudioEffect Error mAudioFormat : 1, event : 235670794, value : 319688206
,I/System.out( 7696): Thread-1270(ApacheHTTPLog):isShipBuild true
,I/System.out( 7696): Thread-1270(ApacheHTTPLog):SmartBonding Enabling is true, SHIP_BUILD is true, log to file is false, DBG is false
,I/OMXCodec(  293): [OMX.google.vorbis.decoder] End Of Stream
,V/AwesomePlayer(  293): postAudioEOS delayUs (0)
,V/AwesomePlayer(  293): onCheckAudioStatus
V/AwesomePlayer(  293): onCheckAudioStatus() set AUDIO_AT_EOS flag
V/AwesomePlayer(  293): onStreamDone
V/AwesomePlayer(  293): MEDIA_PLAYBACK_COMPLETE
V/AwesomePlayer(  293): notifyListner_l() msg (2-MEDIA_PLAYBACK_COMPLETE), ext1 (0), ext2 (0)
V/AudioCache(  293): notify(0xb05183d0, 2, 0, 0)
V/AudioCache(  293): playback complete - thread will wake up later
V/AwesomePlayer(  293): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache(  293): notify(0xb05183d0, 7, 0, 0)
V/AudioCache(  293): ignored
V/AwesomePlayer(  293): cancelPlayerEvents (keepNotifications=1)
V/AwesomePlayer(  293): addBatteryData
,V/AudioCache(  293): wait - success
V/StagefrightPlayer(  293): reset
V/AwesomePlayer(  293): reset_l()
V/AwesomePlayer(  293): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  293): notify(0xb05183d0, 8, 0, 0)
V/AudioCache(  293): ignored
V/AwesomePlayer(  293): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  293): mAudioTrackVector clear
D/AudioPlayer(  293): reset: mPlaying=0 mReachedEOS=1 useOffload=0
I/OMXCodec(  293): [OMX.google.vorbis.decoder] stop mState=4
I/OMXCodec(  293): [OMX.google.vorbis.decoder] stop() sendCommand(0x7a, OMX_CommandStateSet, OMX_StateIdle)
I/OMXCodec(  293): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
I/OMXCodec(  293): [OMX.google.vorbis.decoder] stopOmxComponent_l() mstate = 1
I/OggExtractor(  293): OggSource::stop() mExtractor ref count = 1
I/OggExtractor(  293): OggSource::~OggSource() mExtractor !mStarted ref count = 1
I/OggExtractor(  293): ~OggSource --
I/OggExtractor(  293): ~OggExtractor ++
I/OggExtractor(  293): ~MyVorbisExtractor ++ 
I/OggExtractor(  293): ~MyVorbisExtractor --
I/OggExtractor(  293): ~OggExtractor --
,I/AudioPlayer(  293): reset out
V/AwesomePlayer(  293): reset_l() mAudioPlayer successfully deleted
I/SecVideoCapture(  293): SecVideoCapture destructor
I/SecVideoCapture(  293): reset
V/AwesomePlayer(  293): mSecCapture clear
I/SecMediaClock(  293): SecMediaClock destructor
V/AwesomePlayer(  293): mSecMediaClock clear
V/StagefrightPlayer(  293): ~StagefrightPlayer
V/StagefrightPlayer(  293): reset
V/AwesomePlayer(  293): reset_l()
V/AwesomePlayer(  293): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  293): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  293): mAudioTrackVector clear
V/AwesomePlayer(  293): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  293): mSecCapture clear
V/AwesomePlayer(  293): mSecMediaClock clear
V/AwesomePlayer(  293): destructor
V/AwesomePlayer(  293): reset_l()
V/AwesomePlayer(  293): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  293): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  293): mAudioTrackVector clear
V/AwesomePlayer(  293): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  293): mSecCapture clear
V/AwesomePlayer(  293): mSecMediaClock clear
V/MediaPlayer( 7961): decode(41, 19156232, 8154)
V/MediaPlayerService(  293): decode(30, 19156232, 8154)
,V/MediaPlayerService(  293): player type = 3
V/AwesomePlayer(  293): setDefault
V/AwesomePlayer(  293): constructor
V/AwesomePlayer(  293): setDefault
V/AwesomePlayer(  293): reset_l()
V/AwesomePlayer(  293): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  293): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  293): mAudioTrackVector clear
V/AwesomePlayer(  293): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  293): mSecCapture clear
V/AwesomePlayer(  293): mSecMediaClock clear
V/StagefrightPlayer(  293): StagefrightPlayer
V/AwesomePlayer(  293): setListener
V/StagefrightPlayer(  293): initCheck
V/AwesomePlayer(  293): setAudioSink
V/StagefrightPlayer(  293): setDataSource(30, 19156232, 8154)
V/AwesomePlayer(  293): reset_l()
V/AwesomePlayer(  293): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  293): notify(0xb03fc510, 8, 0, 0)
V/AudioCache(  293): ignored
V/AwesomePlayer(  293): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  293): mAudioTrackVector clear
V/AwesomePlayer(  293): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  293): mSecCapture clear
V/AwesomePlayer(  293): mSecMediaClock clear
D/Utils   (  293): printFileName fd(31) -> /system/priv-app/SHealth3_5/SHealth3_5.apk
,V/AwesomePlayer(  293): track of type 'audio/vorbis' does not publish bitrate
V/AwesomePlayer(  293): mBitrate = -1 bits/sec
I/OggExtractor(  293): OggSource::OggSource() mExtractor ref count = 4
V/AwesomePlayer(  293): current audio track index (0) is added to vector
V/AwesomePlayer(  293): setDataSource_l: Audio(1), Video(0)
I/AwesomePlayer(  293): checkRightsStatus is not necessary - AwesomePlayer::setDataSource_l
V/MediaPlayerService(  293): prepare
V/AwesomePlayer(  293): prepareAsync
V/MediaPlayerService(  293): wait for prepare
V/AwesomePlayer(  293): onPrepareAsyncEvent
I/SecMediaClock(  293): SecMediaClock constructor
I/SecMediaClock(  293): reset
I/SecVideoCapture(  293): SecVideoCapture constructor
I/SecVideoCapture(  293): reset
V/AwesomePlayer(  293): initAudioDecoder
V/AwesomePlayer(  293): checkOffloadExceptions is true
V/AudioPolicyManager(  293): isOffloadSupported: SR=44100, CM=0x1, Format=0x7000000, StreamType=-1, BitRate=4294967295, duration=405328 us, has_video=0
V/AudioPolicyManager(  293): isOffloadSupported: stream_type != MUSIC, returning false
I/OMXCodec(  293): Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
,I/OMXCodec(  293): Successfully allocated OMX node 'OMX.google.vorbis.decoder'
,I/OMXCodec(  293): >>>UHQA initOutputFormat 16
I/AwesomePlayer(  293): Could not offload audio decode, try pcm offload
V/AudioPolicyManager(  293): isOffloadSupported: SR=44100, CM=0x1, Format=0x1c000001, StreamType=-1, BitRate=4294967295, duration=405328 us, has_video=0
V/AudioPolicyManager(  293): isOffloadSupported: stream_type != MUSIC, returning false
I/OMXCodec(  293): [OMX.google.vorbis.decoder] OMXCodec::start mState=1
I/OMXCodec(  293): [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
I/OMXCodec(  293): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
I/OMXCodec(  293): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
,V/AwesomePlayer(  293): finishAsyncPrepare_l
V/AwesomePlayer(  293): notifyListner_l() msg (200-MEDIA_INFO), ext1 (973), ext2 (0)
V/AudioCache(  293): notify(0xb03fc510, 200, 973, 0)
V/AudioCache(  293): ignored
V/AwesomePlayer(  293): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache(  293): notify(0xb03fc510, 5, 0, 0)
V/AudioCache(  293): ignored
V/AwesomePlayer(  293): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache(  293): notify(0xb03fc510, 1, 0, 0)
V/AudioCache(  293): prepared
V/AudioCache(  293): wait - success
V/MediaPlayerService(  293): start
V/StagefrightPlayer(  293): start
,V/AwesomePlayer(  293): play
V/AwesomePlayer(  293): AwesomePlayer::play_l():: This is not a DRM content
V/AwesomePlayer(  293): startAudioPlayer_l, sendErrorNotification (0)
D/AudioPlayer(  293): start of Playback, useOffload 0
,I/OMXCodec(  293): [OMX.google.vorbis.decoder] 0onCmdComplete  mState =  7
,I/OMXCodec(  293): [OMX.google.vorbis.decoder] PORT_DISABLED(1)
I/OMXCodec(  293): >>>UHQA initOutputFormat 16
I/OMXCodec(  293): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
,I/AudioPlayer(  293): Audio channels(1)
I/AudioPlayer(  293): Audioplayer kKeyAudioPCMFormat:0, 1, 0
I/AudioPlayer(  293): Audioplayer kKeyAudioPCMFormat read fail(1, 1)
V/AudioCache(  293): open(44100, 1, 0x0, 1, 0)
,V/AwesomePlayer(  293): notifyListner_l() msg (6-MEDIA_STARTED), ext1 (0), ext2 (0)
V/AudioCache(  293): notify(0xb03fc510, 6, 0, 0)
V/AudioCache(  293): ignored
V/AwesomePlayer(  293): addBatteryData
V/MediaPlayerService(  293): wait for playback complete
I/AudioPlayer(  293): First fillBuffer call!!
,I/AudioPlayer(  293): >>> setAudioEffect Read mAudioFormat : 1, event : 168430090, value : 151652874
E/AudioPlayer(  293): >>> setAudioEffect Error mAudioFormat : 1, event : 168430090, value : 151652874
,I/OMXCodec(  293): [OMX.google.vorbis.decoder] End Of Stream
,V/AwesomePlayer(  293): postAudioEOS delayUs (0)
V/AwesomePlayer(  293): onCheckAudioStatus
V/AwesomePlayer(  293): onCheckAudioStatus() set AUDIO_AT_EOS flag
V/AwesomePlayer(  293): onStreamDone
V/AwesomePlayer(  293): MEDIA_PLAYBACK_COMPLETE
V/AwesomePlayer(  293): notifyListner_l() msg (2-MEDIA_PLAYBACK_COMPLETE), ext1 (0), ext2 (0)
V/AudioCache(  293): notify(0xb03fc510, 2, 0, 0)
V/AudioCache(  293): playback complete - thread will wake up later
V/AwesomePlayer(  293): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache(  293): notify(0xb03fc510, 7, 0, 0)
V/AudioCache(  293): ignored
V/AwesomePlayer(  293): cancelPlayerEvents (keepNotifications=1)
V/AwesomePlayer(  293): addBatteryData
V/AudioCache(  293): wait - success
V/StagefrightPlayer(  293): reset
V/AwesomePlayer(  293): reset_l()
V/AwesomePlayer(  293): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  293): notify(0xb03fc510, 8, 0, 0)
V/AudioCache(  293): ignored
V/AwesomePlayer(  293): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  293): mAudioTrackVector clear
D/AudioPlayer(  293): reset: mPlaying=0 mReachedEOS=1 useOffload=0
I/OMXCodec(  293): [OMX.google.vorbis.decoder] stop mState=4
I/OMXCodec(  293): [OMX.google.vorbis.decoder] stop() sendCommand(0x7b, OMX_CommandStateSet, OMX_StateIdle)
I/OMXCodec(  293): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
I/OMXCodec(  293): [OMX.google.vorbis.decoder] stopOmxComponent_l() mstate = 1
I/OggExtractor(  293): OggSource::stop() mExtractor ref count = 1
I/OggExtractor(  293): OggSource::~OggSource() mExtractor !mStarted ref count = 1
I/OggExtractor(  293): ~OggSource --
I/OggExtractor(  293): ~OggExtractor ++
I/OggExtractor(  293): ~MyVorbisExtractor ++ 
I/OggExtractor(  293): ~MyVorbisExtractor --
I/OggExtractor(  293): ~OggExtractor --
,I/AudioPlayer(  293): reset out
V/AwesomePlayer(  293): reset_l() mAudioPlayer successfully deleted
I/SecVideoCapture(  293): SecVideoCapture destructor
I/SecVideoCapture(  293): reset
V/AwesomePlayer(  293): mSecCapture clear
I/SecMediaClock(  293): SecMediaClock destructor
V/AwesomePlayer(  293): mSecMediaClock clear
V/StagefrightPlayer(  293): ~StagefrightPlayer
V/StagefrightPlayer(  293): reset
V/AwesomePlayer(  293): reset_l()
V/AwesomePlayer(  293): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  293): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  293): mAudioTrackVector clear
V/AwesomePlayer(  293): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  293): mSecCapture clear
V/AwesomePlayer(  293): mSecMediaClock clear
V/AwesomePlayer(  293): destructor
V/AwesomePlayer(  293): reset_l()
V/AwesomePlayer(  293): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  293): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  293): mAudioTrackVector clear
V/AwesomePlayer(  293): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  293): mSecCapture clear
V/AwesomePlayer(  293): mSecMediaClock clear
V/MediaPlayer( 7961): decode(42, 19129712, 4804)
V/MediaPlayerService(  293): decode(30, 19129712, 4804)
,V/MediaPlayerService(  293): player type = 3
V/AwesomePlayer(  293): setDefault
V/AwesomePlayer(  293): constructor
V/AwesomePlayer(  293): setDefault
V/AwesomePlayer(  293): reset_l()
V/AwesomePlayer(  293): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  293): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  293): mAudioTrackVector clear
,V/AwesomePlayer(  293): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  293): mSecCapture clear
V/AwesomePlayer(  293): mSecMediaClock clear
V/StagefrightPlayer(  293): StagefrightPlayer
V/AwesomePlayer(  293): setListener
V/StagefrightPlayer(  293): initCheck
V/AwesomePlayer(  293): setAudioSink
V/StagefrightPlayer(  293): setDataSource(30, 19129712, 4804)
V/AwesomePlayer(  293): reset_l()
,V/AwesomePlayer(  293): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  293): notify(0xb02092e0, 8, 0, 0)
V/AudioCache(  293): ignored
V/AwesomePlayer(  293): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  293): mAudioTrackVector clear
V/AwesomePlayer(  293): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  293): mSecCapture clear
V/AwesomePlayer(  293): mSecMediaClock clear
D/Utils   (  293): printFileName fd(31) -> /system/priv-app/SHealth3_5/SHealth3_5.apk
,V/AwesomePlayer(  293): track of type 'audio/vorbis' does not publish bitrate
V/AwesomePlayer(  293): mBitrate = -1 bits/sec
I/OggExtractor(  293): OggSource::OggSource() mExtractor ref count = 4
V/AwesomePlayer(  293): current audio track index (0) is added to vector
V/AwesomePlayer(  293): setDataSource_l: Audio(1), Video(0)
I/AwesomePlayer(  293): checkRightsStatus is not necessary - AwesomePlayer::setDataSource_l
V/MediaPlayerService(  293): prepare
V/AwesomePlayer(  293): prepareAsync
,V/MediaPlayerService(  293): wait for prepare
V/AwesomePlayer(  293): onPrepareAsyncEvent
I/SecMediaClock(  293): SecMediaClock constructor
I/SecMediaClock(  293): reset
I/SecVideoCapture(  293): SecVideoCapture constructor
I/SecVideoCapture(  293): reset
V/AwesomePlayer(  293): initAudioDecoder
V/AwesomePlayer(  293): checkOffloadExceptions is true
V/AudioPolicyManager(  293): isOffloadSupported: SR=44100, CM=0x1, Format=0x7000000, StreamType=-1, BitRate=4294967295, duration=110476 us, has_video=0
,V/AudioPolicyManager(  293): isOffloadSupported: stream_type != MUSIC, returning false
I/OMXCodec(  293): Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
,I/OMXCodec(  293): Successfully allocated OMX node 'OMX.google.vorbis.decoder'
I/OMXCodec(  293): >>>UHQA initOutputFormat 16
I/AwesomePlayer(  293): Could not offload audio decode, try pcm offload
V/AudioPolicyManager(  293): isOffloadSupported: SR=44100, CM=0x1, Format=0x1c000001, StreamType=-1, BitRate=4294967295, duration=110476 us, has_video=0
V/AudioPolicyManager(  293): isOffloadSupported: stream_type != MUSIC, returning false
I/OMXCodec(  293): [OMX.google.vorbis.decoder] OMXCodec::start mState=1
I/OMXCodec(  293): [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
I/OMXCodec(  293): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
I/OMXCodec(  293): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
V/AwesomePlayer(  293): finishAsyncPrepare_l
V/AwesomePlayer(  293): notifyListner_l() msg (200-MEDIA_INFO), ext1 (973), ext2 (0)
V/AudioCache(  293): notify(0xb02092e0, 200, 973, 0)
V/AudioCache(  293): ignored
V/AwesomePlayer(  293): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache(  293): notify(0xb02092e0, 5, 0, 0)
V/AudioCache(  293): ignored
V/AwesomePlayer(  293): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache(  293): notify(0xb02092e0, 1, 0, 0)
V/AudioCache(  293): prepared
V/AudioCache(  293): wait - success
V/MediaPlayerService(  293): start
V/StagefrightPlayer(  293): start
,V/AwesomePlayer(  293): play
V/AwesomePlayer(  293): AwesomePlayer::play_l():: This is not a DRM content
V/AwesomePlayer(  293): startAudioPlayer_l, sendErrorNotification (0)
D/AudioPlayer(  293): start of Playback, useOffload 0
,I/OMXCodec(  293): [OMX.google.vorbis.decoder] 0onCmdComplete  mState =  7
I/OMXCodec(  293): [OMX.google.vorbis.decoder] PORT_DISABLED(1)
I/OMXCodec(  293): >>>UHQA initOutputFormat 16
I/OMXCodec(  293): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
,I/AudioPlayer(  293): Audio channels(1)
I/AudioPlayer(  293): Audioplayer kKeyAudioPCMFormat:0, 1, 0
I/AudioPlayer(  293): Audioplayer kKeyAudioPCMFormat read fail(1, 1)
,V/AudioCache(  293): open(44100, 1, 0x0, 1, 0)
V/AwesomePlayer(  293): notifyListner_l() msg (6-MEDIA_STARTED), ext1 (0), ext2 (0)
V/AudioCache(  293): notify(0xb02092e0, 6, 0, 0)
V/AudioCache(  293): ignored
I/AudioPlayer(  293): First fillBuffer call!!
,V/AwesomePlayer(  293): addBatteryData
I/AudioPlayer(  293): >>> setAudioEffect Read mAudioFormat : 1, event : 168430090, value : 151652874
E/AudioPlayer(  293): >>> setAudioEffect Error mAudioFormat : 1, event : 168430090, value : 151652874
V/MediaPlayerService(  293): wait for playback complete
,I/OMXCodec(  293): [OMX.google.vorbis.decoder] End Of Stream
,D/accuweather( 7215): [KK AccuPhone]>>> WC:30 [0:0] action : androidintentactionTIME_SET
,V/AwesomePlayer(  293): postAudioEOS delayUs (0)
V/AwesomePlayer(  293): onCheckAudioStatus
V/AwesomePlayer(  293): onCheckAudioStatus() set AUDIO_AT_EOS flag
V/AwesomePlayer(  293): onStreamDone
V/AwesomePlayer(  293): MEDIA_PLAYBACK_COMPLETE
V/AwesomePlayer(  293): notifyListner_l() msg (2-MEDIA_PLAYBACK_COMPLETE), ext1 (0), ext2 (0)
V/AudioCache(  293): notify(0xb02092e0, 2, 0, 0)
V/AudioCache(  293): playback complete - thread will wake up later
V/AwesomePlayer(  293): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache(  293): notify(0xb02092e0, 7, 0, 0)
V/AudioCache(  293): ignored
V/AwesomePlayer(  293): cancelPlayerEvents (keepNotifications=1)
V/AwesomePlayer(  293): addBatteryData
V/AudioCache(  293): wait - success
V/StagefrightPlayer(  293): reset
,V/AwesomePlayer(  293): reset_l()
V/AwesomePlayer(  293): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  293): notify(0xb02092e0, 8, 0, 0)
V/AudioCache(  293): ignored
V/AwesomePlayer(  293): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  293): mAudioTrackVector clear
D/AudioPlayer(  293): reset: mPlaying=0 mReachedEOS=1 useOffload=0
I/OMXCodec(  293): [OMX.google.vorbis.decoder] stop mState=4
I/OMXCodec(  293): [OMX.google.vorbis.decoder] stop() sendCommand(0x7c, OMX_CommandStateSet, OMX_StateIdle)
I/OMXCodec(  293): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
,I/OMXCodec(  293): [OMX.google.vorbis.decoder] stopOmxComponent_l() mstate = 1
I/OggExtractor(  293): OggSource::stop() mExtractor ref count = 1
I/OggExtractor(  293): OggSource::~OggSource() mExtractor !mStarted ref count = 1
I/OggExtractor(  293): ~OggSource --
I/OggExtractor(  293): ~OggExtractor ++
I/OggExtractor(  293): ~MyVorbisExtractor ++ 
I/OggExtractor(  293): ~MyVorbisExtractor --
I/OggExtractor(  293): ~OggExtractor --
,I/AudioPlayer(  293): reset out
V/AwesomePlayer(  293): reset_l() mAudioPlayer successfully deleted
I/SecVideoCapture(  293): SecVideoCapture destructor
I/SecVideoCapture(  293): reset
V/AwesomePlayer(  293): mSecCapture clear
I/SecMediaClock(  293): SecMediaClock destructor
V/AwesomePlayer(  293): mSecMediaClock clear
V/StagefrightPlayer(  293): ~StagefrightPlayer
V/StagefrightPlayer(  293): reset
V/AwesomePlayer(  293): reset_l()
V/AwesomePlayer(  293): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  293): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  293): mAudioTrackVector clear
V/AwesomePlayer(  293): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  293): mSecCapture clear
V/AwesomePlayer(  293): mSecMediaClock clear
V/AwesomePlayer(  293): destructor
V/AwesomePlayer(  293): reset_l()
V/AwesomePlayer(  293): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  293): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  293): mAudioTrackVector clear
V/AwesomePlayer(  293): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  293): mSecCapture clear
,V/AwesomePlayer(  293): mSecMediaClock clear
V/MediaPlayer( 7961): decode(43, 19099164, 9400)
D/accuweather( 7215): [KK AccuPhone]>>> UIMEM:106 [0:0] The widget does not exist in idle!!
V/MediaPlayerService(  293): decode(30, 19099164, 9400)
,V/MediaPlayerService(  293): player type = 3
V/AwesomePlayer(  293): setDefault
V/AwesomePlayer(  293): constructor
,E/ActivityManager(  875): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  875): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  875): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  875): checkUser: useridlist=null, currentuser=0
,V/AwesomePlayer(  293): setDefault
V/AwesomePlayer(  293): reset_l()
V/AwesomePlayer(  293): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  293): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  293): mAudioTrackVector clear
V/AwesomePlayer(  293): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  293): mSecCapture clear
,V/AwesomePlayer(  293): mSecMediaClock clear
V/StagefrightPlayer(  293): StagefrightPlayer
V/AwesomePlayer(  293): setListener
V/StagefrightPlayer(  293): initCheck
V/AwesomePlayer(  293): setAudioSink
V/StagefrightPlayer(  293): setDataSource(30, 19099164, 9400)
V/AwesomePlayer(  293): reset_l()
V/AwesomePlayer(  293): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
,V/AudioCache(  293): notify(0xb19272e0, 8, 0, 0)
V/AudioCache(  293): ignored
V/AwesomePlayer(  293): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  293): mAudioTrackVector clear
V/AwesomePlayer(  293): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  293): mSecCapture clear
V/AwesomePlayer(  293): mSecMediaClock clear
D/Utils   (  293): printFileName fd(31) -> /system/priv-app/SHealth3_5/SHealth3_5.apk
,I/ Time Manager ( 8040): Time Difference not stored. TIME_DIFFERENCE
,V/AwesomePlayer(  293): track of type 'audio/vorbis' does not publish bitrate
,V/AwesomePlayer(  293): mBitrate = -1 bits/sec
I/OggExtractor(  293): OggSource::OggSource() mExtractor ref count = 4
V/AwesomePlayer(  293): current audio track index (0) is added to vector
V/AwesomePlayer(  293): setDataSource_l: Audio(1), Video(0)
I/AwesomePlayer(  293): checkRightsStatus is not necessary - AwesomePlayer::setDataSource_l
V/MediaPlayerService(  293): prepare
V/AwesomePlayer(  293): prepareAsync
V/MediaPlayerService(  293): wait for prepare
,V/AwesomePlayer(  293): onPrepareAsyncEvent
,I/SecMediaClock(  293): SecMediaClock constructor
I/SecMediaClock(  293): reset
I/SecVideoCapture(  293): SecVideoCapture constructor
I/SecVideoCapture(  293): reset
V/AwesomePlayer(  293): initAudioDecoder
V/AwesomePlayer(  293): checkOffloadExceptions is true
V/AudioPolicyManager(  293): isOffloadSupported: SR=44100, CM=0x1, Format=0x7000000, StreamType=-1, BitRate=4294967295, duration=731360 us, has_video=0
V/AudioPolicyManager(  293): isOffloadSupported: stream_type != MUSIC, returning false
,I/OMXCodec(  293): Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
I/OMXCodec(  293): Successfully allocated OMX node 'OMX.google.vorbis.decoder'
I/OMXCodec(  293): >>>UHQA initOutputFormat 16
I/AwesomePlayer(  293): Could not offload audio decode, try pcm offload
V/AudioPolicyManager(  293): isOffloadSupported: SR=44100, CM=0x1, Format=0x1c000001, StreamType=-1, BitRate=4294967295, duration=731360 us, has_video=0
V/AudioPolicyManager(  293): isOffloadSupported: stream_type != MUSIC, returning false
I/OMXCodec(  293): [OMX.google.vorbis.decoder] OMXCodec::start mState=1
I/OMXCodec(  293): [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
,I/OMXCodec(  293): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
I/OMXCodec(  293): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
,V/MediaPlayer( 7961): decode(49, 19172584, 4112)
V/MediaPlayerService(  293): decode(35, 19172584, 4112)
,V/MediaPlayerService(  293): player type = 3
V/AwesomePlayer(  293): setDefault
,E/Zygote  ( 8078): MountEmulatedStorage()
I/libpersona( 8078): KNOX_SDCARD checking this for 10091
E/Zygote  ( 8078): v2
I/libpersona( 8078): KNOX_SDCARD not a persona
V/AwesomePlayer(  293): constructor
,V/AwesomePlayer(  293): setDefault
V/AwesomePlayer(  293): reset_l()
V/AwesomePlayer(  293): finishAsyncPrepare_l
V/AwesomePlayer(  293): notifyListner_l() msg (200-MEDIA_INFO), ext1 (973), ext2 (0)
V/AudioCache(  293): notify(0xb19272e0, 200, 973, 0)
V/AudioCache(  293): ignored
V/AwesomePlayer(  293): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache(  293): notify(0xb19272e0, 5, 0, 0)
V/AudioCache(  293): ignored
V/AwesomePlayer(  293): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache(  293): notify(0xb19272e0, 1, 0, 0)
V/AudioCache(  293): prepared
V/AudioCache(  293): wait - success
V/MediaPlayerService(  293): start
V/StagefrightPlayer(  293): start
V/AwesomePlayer(  293): play
V/AwesomePlayer(  293): AwesomePlayer::play_l():: This is not a DRM content
V/AwesomePlayer(  293): startAudioPlayer_l, sendErrorNotification (0)
D/AudioPlayer(  293): start of Playback, useOffload 0
,V/AwesomePlayer(  293): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  293): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  293): mAudioTrackVector clear
V/AwesomePlayer(  293): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  293): mSecCapture clear
,V/AwesomePlayer(  293): mSecMediaClock clear
V/StagefrightPlayer(  293): StagefrightPlayer
V/AwesomePlayer(  293): setListener
,V/StagefrightPlayer(  293): initCheck
I/OMXCodec(  293): [OMX.google.vorbis.decoder] 0onCmdComplete  mState =  7
I/ActivityManager(  875): Start proc com.sec.android.app.clockpackage for broadcast com.sec.android.app.clockpackage/.alarm.AlarmReceiver: pid=8078 uid=10091 gids={50091, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/OMXCodec(  293): [OMX.google.vorbis.decoder] PORT_DISABLED(1)
I/OMXCodec(  293): >>>UHQA initOutputFormat 16
I/OMXCodec(  293): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
,V/AwesomePlayer(  293): setAudioSink
I/ActivityManager(  875): Killing 7003:com.samsung.helphub/1000 (adj 15): bgCount ##41
V/StagefrightPlayer(  293): setDataSource(35, 19172584, 4112)
V/AwesomePlayer(  293): reset_l()
V/AwesomePlayer(  293): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  293): notify(0xafa141a0, 8, 0, 0)
V/AudioCache(  293): ignored
V/AwesomePlayer(  293): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  293): mAudioTrackVector clear
V/AwesomePlayer(  293): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  293): mSecCapture clear
,V/AwesomePlayer(  293): mSecMediaClock clear
D/Utils   (  293): printFileName fd(33) -> /system/priv-app/SHealth3_5/SHealth3_5.apk
I/AudioPlayer(  293): Audio channels(1)
I/AudioPlayer(  293): Audioplayer kKeyAudioPCMFormat:0, 1, 0
I/AudioPlayer(  293): Audioplayer kKeyAudioPCMFormat read fail(1, 1)
V/AudioCache(  293): open(44100, 1, 0x0, 1, 0)
,V/AwesomePlayer(  293): notifyListner_l() msg (6-MEDIA_STARTED), ext1 (0), ext2 (0)
V/AudioCache(  293): notify(0xb19272e0, 6, 0, 0)
V/AudioCache(  293): ignored
V/AwesomePlayer(  293): addBatteryData
V/MediaPlayerService(  293): wait for playback complete
,V/AwesomePlayer(  293): track of type 'audio/vorbis' does not publish bitrate
,V/AwesomePlayer(  293): mBitrate = -1 bits/sec
I/OggExtractor(  293): OggSource::OggSource() mExtractor ref count = 4
V/AwesomePlayer(  293): current audio track index (0) is added to vector
V/AwesomePlayer(  293): setDataSource_l: Audio(1), Video(0)
I/AwesomePlayer(  293): checkRightsStatus is not necessary - AwesomePlayer::setDataSource_l
,V/MediaPlayerService(  293): prepare
V/AwesomePlayer(  293): prepareAsync
V/MediaPlayerService(  293): wait for prepare
V/AwesomePlayer(  293): onPrepareAsyncEvent
I/SecMediaClock(  293): SecMediaClock constructor
I/SecMediaClock(  293): reset
I/SecVideoCapture(  293): SecVideoCapture constructor
I/SecVideoCapture(  293): reset
V/AwesomePlayer(  293): initAudioDecoder
V/AwesomePlayer(  293): checkOffloadExceptions is true
V/AudioPolicyManager(  293): isOffloadSupported: SR=44100, CM=0x1, Format=0x7000000, StreamType=-1, BitRate=4294967295, duration=4331 us, has_video=0
V/AudioPolicyManager(  293): isOffloadSupported: stream_type != MUSIC, returning false
I/OMXCodec(  293): Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
,I/OMXCodec(  293): Successfully allocated OMX node 'OMX.google.vorbis.decoder'
I/OMXCodec(  293): >>>UHQA initOutputFormat 16
I/AwesomePlayer(  293): Could not offload audio decode, try pcm offload
V/AudioPolicyManager(  293): isOffloadSupported: SR=44100, CM=0x1, Format=0x1c000001, StreamType=-1, BitRate=4294967295, duration=4331 us, has_video=0
V/AudioPolicyManager(  293): isOffloadSupported: stream_type != MUSIC, returning false
I/OMXCodec(  293): [OMX.google.vorbis.decoder] OMXCodec::start mState=1
I/OMXCodec(  293): [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
I/OMXCodec(  293): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
,I/AudioPlayer(  293): First fillBuffer call!!
,I/SELinux ( 8078): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
I/AudioPlayer(  293): >>> setAudioEffect Read mAudioFormat : 1, event : 4587583, value : 4390976
E/AudioPlayer(  293): >>> setAudioEffect Error mAudioFormat : 1, event : 4587583, value : 4390976
,I/OMXCodec(  293): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
,V/AwesomePlayer(  293): finishAsyncPrepare_l
I/SELinux ( 8078): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
V/AwesomePlayer(  293): notifyListner_l() msg (200-MEDIA_INFO), ext1 (973), ext2 (0)
V/AudioCache(  293): notify(0xafa141a0, 200, 973, 0)
V/AudioCache(  293): ignored
,V/AwesomePlayer(  293): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache(  293): notify(0xafa141a0, 5, 0, 0)
E/SELinux ( 8078): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
V/AudioCache(  293): ignored
V/AwesomePlayer(  293): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
,V/AudioCache(  293): notify(0xafa141a0, 1, 0, 0)
V/AudioCache(  293): prepared
V/AudioCache(  293): wait - success
V/MediaPlayerService(  293): start
V/StagefrightPlayer(  293): start
,V/AwesomePlayer(  293): play
,V/AwesomePlayer(  293): AwesomePlayer::play_l():: This is not a DRM content
V/AwesomePlayer(  293): startAudioPlayer_l, sendErrorNotification (0)
D/AudioPlayer(  293): start of Playback, useOffload 0
,I/OMXCodec(  293): [OMX.google.vorbis.decoder] End Of Stream
,I/OMXCodec(  293): [OMX.google.vorbis.decoder] 0onCmdComplete  mState =  7
,I/OMXCodec(  293): [OMX.google.vorbis.decoder] PORT_DISABLED(1)
I/OMXCodec(  293): >>>UHQA initOutputFormat 16
I/OMXCodec(  293): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
,I/AudioPlayer(  293): Audio channels(1)
I/OMXCodec(  293): [OMX.google.vorbis.decoder] End Of Stream
,I/AudioPlayer(  293): Audioplayer kKeyAudioPCMFormat:0, 1, 0
I/AudioPlayer(  293): Audioplayer kKeyAudioPCMFormat read fail(1, 1)
V/AudioCache(  293): open(44100, 1, 0x0, 1, 0)
V/AwesomePlayer(  293): postAudioEOS delayUs (0)
V/AwesomePlayer(  293): onCheckAudioStatus
V/AwesomePlayer(  293): onCheckAudioStatus() set AUDIO_AT_EOS flag
V/AwesomePlayer(  293): onStreamDone
V/AwesomePlayer(  293): MEDIA_PLAYBACK_COMPLETE
V/AwesomePlayer(  293): notifyListner_l() msg (2-MEDIA_PLAYBACK_COMPLETE), ext1 (0), ext2 (0)
V/AudioCache(  293): notify(0xb19272e0, 2, 0, 0)
V/AudioCache(  293): playback complete - thread will wake up later
V/AwesomePlayer(  293): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache(  293): notify(0xb19272e0, 7, 0, 0)
V/AudioCache(  293): ignored
V/AwesomePlayer(  293): cancelPlayerEvents (keepNotifications=1)
V/AwesomePlayer(  293): addBatteryData
V/AudioCache(  293): wait - success
V/StagefrightPlayer(  293): reset
V/AwesomePlayer(  293): reset_l()
V/AwesomePlayer(  293): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  293): notify(0xb19272e0, 8, 0, 0)
V/AudioCache(  293): ignored
V/AwesomePlayer(  293): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  293): mAudioTrackVector clear
D/AudioPlayer(  293): reset: mPlaying=0 mReachedEOS=1 useOffload=0
I/OMXCodec(  293): [OMX.google.vorbis.decoder] stop mState=4
I/OMXCodec(  293): [OMX.google.vorbis.decoder] stop() sendCommand(0x7d, OMX_CommandStateSet, OMX_StateIdle)
I/OMXCodec(  293): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
I/OMXCodec(  293): [OMX.google.vorbis.decoder] stopOmxComponent_l() mstate = 1
I/OggExtractor(  293): OggSource::stop() mExtractor ref count = 1
I/OggExtractor(  293): OggSource::~OggSource() mExtractor !mStarted ref count = 1
I/OggExtractor(  293): ~OggSource --
I/OggExtractor(  293): ~OggExtractor ++
I/OggExtractor(  293): ~MyVorbisExtractor ++ 
I/OggExtractor(  293): ~MyVorbisExtractor --
I/OggExtractor(  293): ~OggExtractor --
,I/AudioPlayer(  293): reset out
V/AwesomePlayer(  293): reset_l() mAudioPlayer successfully deleted
I/SecVideoCapture(  293): SecVideoCapture destructor
I/SecVideoCapture(  293): reset
V/AwesomePlayer(  293): mSecCapture clear
I/SecMediaClock(  293): SecMediaClock destructor
V/AwesomePlayer(  293): mSecMediaClock clear
V/StagefrightPlayer(  293): ~StagefrightPlayer
V/StagefrightPlayer(  293): reset
V/AwesomePlayer(  293): reset_l()
V/AwesomePlayer(  293): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  293): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  293): mAudioTrackVector clear
V/AwesomePlayer(  293): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  293): mSecCapture clear
V/AwesomePlayer(  293): mSecMediaClock clear
V/AwesomePlayer(  293): destructor
,V/AwesomePlayer(  293): notifyListner_l() msg (6-MEDIA_STARTED), ext1 (0), ext2 (0)
V/AudioCache(  293): notify(0xafa141a0, 6, 0, 0)
V/AudioCache(  293): ignored
V/AwesomePlayer(  293): addBatteryData
,V/AwesomePlayer(  293): reset_l()
V/AwesomePlayer(  293): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  293): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  293): mAudioTrackVector clear
V/AwesomePlayer(  293): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  293): mSecCapture clear
,V/AwesomePlayer(  293): mSecMediaClock clear
V/MediaPlayerService(  293): wait for playback complete
V/MediaPlayer( 7961): decode(44, 19307764, 52024)
V/MediaPlayerService(  293): decode(31, 19307764, 52024)
I/AudioPlayer(  293): First fillBuffer call!!
I/AudioPlayer(  293): >>> setAudioEffect Read mAudioFormat : 1, event : 168430090, value : 151652874
E/AudioPlayer(  293): >>> setAudioEffect Error mAudioFormat : 1, event : 168430090, value : 151652874
V/AwesomePlayer(  293): postAudioEOS delayUs (0)
,V/MediaPlayerService(  293): player type = 3
V/AwesomePlayer(  293): setDefault
V/AwesomePlayer(  293): constructor
V/AwesomePlayer(  293): onCheckAudioStatus
V/AwesomePlayer(  293): onCheckAudioStatus() set AUDIO_AT_EOS flag
V/AwesomePlayer(  293): onStreamDone
V/AwesomePlayer(  293): MEDIA_PLAYBACK_COMPLETE
,V/AwesomePlayer(  293): notifyListner_l() msg (2-MEDIA_PLAYBACK_COMPLETE), ext1 (0), ext2 (0)
V/AudioCache(  293): notify(0xafa141a0, 2, 0, 0)
V/AudioCache(  293): playback complete - thread will wake up later
V/AwesomePlayer(  293): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache(  293): notify(0xafa141a0, 7, 0, 0)
V/AudioCache(  293): ignored
V/AwesomePlayer(  293): cancelPlayerEvents (keepNotifications=1)
V/AudioCache(  293): wait - success
V/AwesomePlayer(  293): setDefault
,V/AwesomePlayer(  293): reset_l()
V/StagefrightPlayer(  293): reset
V/AwesomePlayer(  293): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  293): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  293): mAudioTrackVector clear
V/AwesomePlayer(  293): addBatteryData
V/AwesomePlayer(  293): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  293): mSecCapture clear
V/AwesomePlayer(  293): mSecMediaClock clear
V/StagefrightPlayer(  293): StagefrightPlayer
,V/AwesomePlayer(  293): setListener
V/StagefrightPlayer(  293): initCheck
V/AwesomePlayer(  293): setAudioSink
V/StagefrightPlayer(  293): setDataSource(31, 19307764, 52024)
V/AwesomePlayer(  293): reset_l()
V/AwesomePlayer(  293): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  293): notify(0xb05183d0, 8, 0, 0)
,V/AudioCache(  293): ignored
V/AwesomePlayer(  293): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  293): mAudioTrackVector clear
V/AwesomePlayer(  293): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  293): mSecCapture clear
V/AwesomePlayer(  293): mSecMediaClock clear
,D/Utils   (  293): printFileName fd(36) -> /system/priv-app/SHealth3_5/SHealth3_5.apk
V/AwesomePlayer(  293): track of type 'audio/vorbis' does not publish bitrate
V/AwesomePlayer(  293): mBitrate = -1 bits/sec
I/OggExtractor(  293): OggSource::OggSource() mExtractor ref count = 4
V/AwesomePlayer(  293): current audio track index (0) is added to vector
V/AwesomePlayer(  293): setDataSource_l: Audio(1), Video(0)
I/AwesomePlayer(  293): checkRightsStatus is not necessary - AwesomePlayer::setDataSource_l
V/MediaPlayerService(  293): prepare
,V/AwesomePlayer(  293): prepareAsync
V/MediaPlayerService(  293): wait for prepare
V/AwesomePlayer(  293): reset_l()
V/AwesomePlayer(  293): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  293): notify(0xafa141a0, 8, 0, 0)
V/AudioCache(  293): ignored
V/AwesomePlayer(  293): cancelPlayerEvents (keepNotifications=0)
,V/AwesomePlayer(  293): mAudioTrackVector clear
D/AudioPlayer(  293): reset: mPlaying=0 mReachedEOS=1 useOffload=0
I/OMXCodec(  293): [OMX.google.vorbis.decoder] stop mState=4
V/AwesomePlayer(  293): onPrepareAsyncEvent
I/OMXCodec(  293): [OMX.google.vorbis.decoder] stop() sendCommand(0x7e, OMX_CommandStateSet, OMX_StateIdle)
I/SecMediaClock(  293): SecMediaClock constructor
I/SecMediaClock(  293): reset
,I/SecVideoCapture(  293): SecVideoCapture constructor
I/SecVideoCapture(  293): reset
V/AwesomePlayer(  293): initAudioDecoder
V/AwesomePlayer(  293): checkOffloadExceptions is true
V/AudioPolicyManager(  293): isOffloadSupported: SR=48000, CM=0x3, Format=0x7000000, StreamType=-1, BitRate=4294967295, duration=2880000 us, has_video=0
I/OMXCodec(  293): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
,V/AudioPolicyManager(  293): isOffloadSupported: stream_type != MUSIC, returning false
I/OMXCodec(  293): Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
D/TimaKeyStoreProvider( 8078): TimaSignature is unavailable
D/ActivityThread( 8078): Added TimaKeyStore provider
,I/OMXCodec(  293): Successfully allocated OMX node 'OMX.google.vorbis.decoder'
I/OMXCodec(  293): >>>UHQA initOutputFormat 16
I/AwesomePlayer(  293): Could not offload audio decode, try pcm offload
V/AudioPolicyManager(  293): isOffloadSupported: SR=44100, CM=0x1, Format=0x1c000001, StreamType=-1, BitRate=4294967295, duration=2880000 us, has_video=0
V/AudioPolicyManager(  293): isOffloadSupported: stream_type != MUSIC, returning false
,I/OMXCodec(  293): [OMX.google.vorbis.decoder] OMXCodec::start mState=1
I/OMXCodec(  293): [OMX.google.vorbis.decoder] stopOmxComponent_l() mstate = 1
I/OggExtractor(  293): OggSource::stop() mExtractor ref count = 1
I/OMXCodec(  293): [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
I/OggExtractor(  293): OggSource::~OggSource() mExtractor !mStarted ref count = 1
,I/OggExtractor(  293): ~OggSource --
I/OggExtractor(  293): ~OggExtractor ++
I/OggExtractor(  293): ~MyVorbisExtractor ++ 
I/OggExtractor(  293): ~MyVorbisExtractor --
I/OggExtractor(  293): ~OggExtractor --
I/OMXCodec(  293): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
,I/AudioPlayer(  293): reset out
V/AwesomePlayer(  293): reset_l() mAudioPlayer successfully deleted
I/SecVideoCapture(  293): SecVideoCapture destructor
I/SecVideoCapture(  293): reset
V/AwesomePlayer(  293): mSecCapture clear
,I/SecMediaClock(  293): SecMediaClock destructor
V/AwesomePlayer(  293): mSecMediaClock clear
V/StagefrightPlayer(  293): ~StagefrightPlayer
V/StagefrightPlayer(  293): reset
V/AwesomePlayer(  293): reset_l()
V/AwesomePlayer(  293): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0),
V/AwesomePlayer(  293): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  293): mAudioTrackVector clear
V/AwesomePlayer(  293): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  293): mSecCapture clear
,V/AwesomePlayer(  293): mSecMediaClock clear
V/AwesomePlayer(  293): destructor
I/OMXCodec(  293): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
,V/AwesomePlayer(  293): reset_l(),
V/AwesomePlayer(  293): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  293): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  293): mAudioTrackVector clear
V/AwesomePlayer(  293): reset_l() mAudioPlayer successfully deleted
,V/AwesomePlayer(  293): mSecCapture clear
V/AwesomePlayer(  293): mSecMediaClock clear
V/AwesomePlayer(  293): finishAsyncPrepare_l
V/AwesomePlayer(  293): notifyListner_l() msg (200-MEDIA_INFO), ext1 (973), ext2 (0)
V/AudioCache(  293): notify(0xb05183d0, 200, 973, 0)
,V/AudioCache(  293): ignored
V/AwesomePlayer(  293): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache(  293): notify(0xb05183d0, 5, 0, 0)
V/AudioCache(  293): ignored
V/AwesomePlayer(  293): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache(  293): notify(0xb05183d0, 1, 0, 0),
V/AudioCache(  293): prepared
V/AudioCache(  293): wait - success
V/MediaPlayerService(  293): start
V/StagefrightPlayer(  293): start
V/AwesomePlayer(  293): play,
V/AwesomePlayer(  293): AwesomePlayer::play_l():: This is not a DRM content
V/AwesomePlayer(  293): startAudioPlayer_l, sendErrorNotification (0)
D/AudioPlayer(  293): start of Playback, useOffload 0
,I/OMXCodec(  293): [OMX.google.vorbis.decoder] 0onCmdComplete  mState =  7
,I/OMXCodec(  293): [OMX.google.vorbis.decoder] PORT_DISABLED(1)
I/OMXCodec(  293): >>>UHQA initOutputFormat 16
I/OMXCodec(  293): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
,I/AudioPlayer(  293): Audio channels(2)
I/AudioPlayer(  293): Audioplayer kKeyAudioPCMFormat:0, 1, 0
I/AudioPlayer(  293): Audioplayer kKeyAudioPCMFormat read fail(2, 1)
V/AudioCache(  293): open(48000, 2, 0x0, 1, 0)
,V/AwesomePlayer(  293): notifyListner_l() msg (6-MEDIA_STARTED), ext1 (0), ext2 (0)
V/AudioCache(  293): notify(0xb05183d0, 6, 0, 0)
V/AudioCache(  293): ignored
V/AwesomePlayer(  293): addBatteryData
V/MediaPlayerService(  293): wait for playback complete
I/AudioPlayer(  293): First fillBuffer call!!
,D/ResourcesManager( 8078): creating new AssetManager and set to /system/app/ClockPackage/ClockPackage.apk
,W/ResourcesManager( 8078): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
,W/ResourcesManager( 8078): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 8078): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager( 8078): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,W/ResourcesManager( 8078): Asset path '/system/framework/sec_feature.jar' does not exist or contains no resources.
W/libprocessgroup(  875): failed to open /acct/uid_1000/pid_7003/cgroup.procs: No such file or directory
,I/OMXCodec(  293): [OMX.google.vorbis.decoder] End Of Stream
,V/AwesomePlayer(  293): postAudioEOS delayUs (0)
V/AwesomePlayer(  293): onCheckAudioStatus
V/AwesomePlayer(  293): onCheckAudioStatus() set AUDIO_AT_EOS flag
V/AwesomePlayer(  293): onStreamDone
V/AwesomePlayer(  293): MEDIA_PLAYBACK_COMPLETE
V/AwesomePlayer(  293): notifyListner_l() msg (2-MEDIA_PLAYBACK_COMPLETE), ext1 (0), ext2 (0)
V/AudioCache(  293): notify(0xb05183d0, 2, 0, 0)
V/AudioCache(  293): playback complete - thread will wake up later
V/AwesomePlayer(  293): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache(  293): notify(0xb05183d0, 7, 0, 0)
V/AudioCache(  293): ignored
V/AwesomePlayer(  293): cancelPlayerEvents (keepNotifications=1)
,V/AwesomePlayer(  293): addBatteryData
V/AudioCache(  293): wait - success
V/StagefrightPlayer(  293): reset
,V/AwesomePlayer(  293): reset_l()
V/AwesomePlayer(  293): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  293): notify(0xb05183d0, 8, 0, 0)
V/AudioCache(  293): ignored
V/AwesomePlayer(  293): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  293): mAudioTrackVector clear
D/AudioPlayer(  293): reset: mPlaying=0 mReachedEOS=1 useOffload=0
I/OMXCodec(  293): [OMX.google.vorbis.decoder] stop mState=4
I/OMXCodec(  293): [OMX.google.vorbis.decoder] stop() sendCommand(0x7f, OMX_CommandStateSet, OMX_StateIdle)
,I/OMXCodec(  293): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
I/OMXCodec(  293): [OMX.google.vorbis.decoder] stopOmxComponent_l() mstate = 1
I/OggExtractor(  293): OggSource::stop() mExtractor ref count = 1
I/OggExtractor(  293): OggSource::~OggSource() mExtractor !mStarted ref count = 1
I/OggExtractor(  293): ~OggSource --
I/OggExtractor(  293): ~OggExtractor ++
I/OggExtractor(  293): ~MyVorbisExtractor ++ 
I/OggExtractor(  293): ~MyVorbisExtractor --
I/OggExtractor(  293): ~OggExtractor --
,I/AudioPlayer(  293): reset out
V/AwesomePlayer(  293): reset_l() mAudioPlayer successfully deleted
I/SecVideoCapture(  293): SecVideoCapture destructor
I/SecVideoCapture(  293): reset
V/AwesomePlayer(  293): mSecCapture clear
I/SecMediaClock(  293): SecMediaClock destructor
V/AwesomePlayer(  293): mSecMediaClock clear
V/StagefrightPlayer(  293): ~StagefrightPlayer
V/StagefrightPlayer(  293): reset
V/AwesomePlayer(  293): reset_l()
V/AwesomePlayer(  293): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  293): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  293): mAudioTrackVector clear
V/AwesomePlayer(  293): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  293): mSecCapture clear
V/AwesomePlayer(  293): mSecMediaClock clear
V/AwesomePlayer(  293): destructor
V/AwesomePlayer(  293): reset_l()
V/AwesomePlayer(  293): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  293): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  293): mAudioTrackVector clear
V/AwesomePlayer(  293): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  293): mSecCapture clear
V/AwesomePlayer(  293): mSecMediaClock clear
,V/MediaPlayer( 7961): decode(45, 19172584, 4112)
V/MediaPlayerService(  293): decode(30, 19172584, 4112)
,V/MediaPlayerService(  293): player type = 3
V/AwesomePlayer(  293): setDefault
V/AwesomePlayer(  293): constructor
V/AwesomePlayer(  293): setDefault
V/AwesomePlayer(  293): reset_l()
V/AwesomePlayer(  293): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  293): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  293): mAudioTrackVector clear
V/AwesomePlayer(  293): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  293): mSecCapture clear
V/AwesomePlayer(  293): mSecMediaClock clear
V/StagefrightPlayer(  293): StagefrightPlayer
V/AwesomePlayer(  293): setListener
V/StagefrightPlayer(  293): initCheck
V/AwesomePlayer(  293): setAudioSink
V/StagefrightPlayer(  293): setDataSource(30, 19172584, 4112)
V/AwesomePlayer(  293): reset_l()
V/AwesomePlayer(  293): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  293): notify(0xb03fc510, 8, 0, 0)
V/AudioCache(  293): ignored
V/AwesomePlayer(  293): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  293): mAudioTrackVector clear
V/AwesomePlayer(  293): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  293): mSecCapture clear
V/AwesomePlayer(  293): mSecMediaClock clear
D/Utils   (  293): printFileName fd(31) -> /system/priv-app/SHealth3_5/SHealth3_5.apk
,V/AwesomePlayer(  293): track of type 'audio/vorbis' does not publish bitrate
V/AwesomePlayer(  293): mBitrate = -1 bits/sec
I/OggExtractor(  293): OggSource::OggSource() mExtractor ref count = 4
V/AwesomePlayer(  293): current audio track index (0) is added to vector
V/AwesomePlayer(  293): setDataSource_l: Audio(1), Video(0)
I/AwesomePlayer(  293): checkRightsStatus is not necessary - AwesomePlayer::setDataSource_l
V/MediaPlayerService(  293): prepare
V/AwesomePlayer(  293): prepareAsync
V/MediaPlayerService(  293): wait for prepare
V/AwesomePlayer(  293): onPrepareAsyncEvent
I/SecMediaClock(  293): SecMediaClock constructor
I/SecMediaClock(  293): reset
I/SecVideoCapture(  293): SecVideoCapture constructor
I/SecVideoCapture(  293): reset
V/AwesomePlayer(  293): initAudioDecoder
V/AwesomePlayer(  293): checkOffloadExceptions is true
V/AudioPolicyManager(  293): isOffloadSupported: SR=44100, CM=0x1, Format=0x7000000, StreamType=-1, BitRate=4294967295, duration=4331 us, has_video=0
V/AudioPolicyManager(  293): isOffloadSupported: stream_type != MUSIC, returning false
I/OMXCodec(  293): Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
,I/OMXCodec(  293): Successfully allocated OMX node 'OMX.google.vorbis.decoder'
I/OMXCodec(  293): >>>UHQA initOutputFormat 16
I/AwesomePlayer(  293): Could not offload audio decode, try pcm offload
V/AudioPolicyManager(  293): isOffloadSupported: SR=44100, CM=0x1, Format=0x1c000001, StreamType=-1, BitRate=4294967295, duration=4331 us, has_video=0
V/AudioPolicyManager(  293): isOffloadSupported: stream_type != MUSIC, returning false
I/OMXCodec(  293): [OMX.google.vorbis.decoder] OMXCodec::start mState=1
I/OMXCodec(  293): [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
I/OMXCodec(  293): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
,I/OMXCodec(  293): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
V/AwesomePlayer(  293): finishAsyncPrepare_l
V/AwesomePlayer(  293): notifyListner_l() msg (200-MEDIA_INFO), ext1 (973), ext2 (0)
V/AudioCache(  293): notify(0xb03fc510, 200, 973, 0)
V/AudioCache(  293): ignored
V/AwesomePlayer(  293): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache(  293): notify(0xb03fc510, 5, 0, 0)
V/AudioCache(  293): ignored
V/AwesomePlayer(  293): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache(  293): notify(0xb03fc510, 1, 0, 0)
V/AudioCache(  293): prepared
V/AudioCache(  293): wait - success
V/MediaPlayerService(  293): start
V/StagefrightPlayer(  293): start
V/AwesomePlayer(  293): play
V/AwesomePlayer(  293): AwesomePlayer::play_l():: This is not a DRM content
V/AwesomePlayer(  293): startAudioPlayer_l, sendErrorNotification (0)
D/AudioPlayer(  293): start of Playback, useOffload 0
,I/OMXCodec(  293): [OMX.google.vorbis.decoder] End Of Stream
,I/OMXCodec(  293): [OMX.google.vorbis.decoder] 0onCmdComplete  mState =  7
I/OMXCodec(  293): [OMX.google.vorbis.decoder] PORT_DISABLED(1)
I/OMXCodec(  293): >>>UHQA initOutputFormat 16
I/OMXCodec(  293): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
,I/AudioPlayer(  293): Audio channels(1)
I/AudioPlayer(  293): Audioplayer kKeyAudioPCMFormat:0, 1, 0
I/AudioPlayer(  293): Audioplayer kKeyAudioPCMFormat read fail(1, 1)
V/AudioCache(  293): open(44100, 1, 0x0, 1, 0)
,V/AwesomePlayer(  293): notifyListner_l() msg (6-MEDIA_STARTED), ext1 (0), ext2 (0)
V/AudioCache(  293): notify(0xb03fc510, 6, 0, 0)
V/AudioCache(  293): ignored
V/AwesomePlayer(  293): addBatteryData
V/MediaPlayerService(  293): wait for playback complete
I/AudioPlayer(  293): First fillBuffer call!!
,I/AudioPlayer(  293): >>> setAudioEffect Read mAudioFormat : 1, event : 168430090, value : 151652874
E/AudioPlayer(  293): >>> setAudioEffect Error mAudioFormat : 1, event : 168430090, value : 151652874
V/AwesomePlayer(  293): postAudioEOS delayUs (0)
V/AwesomePlayer(  293): onCheckAudioStatus
V/AwesomePlayer(  293): onCheckAudioStatus() set AUDIO_AT_EOS flag
V/AwesomePlayer(  293): onStreamDone
V/AwesomePlayer(  293): MEDIA_PLAYBACK_COMPLETE
V/AwesomePlayer(  293): notifyListner_l() msg (2-MEDIA_PLAYBACK_COMPLETE), ext1 (0), ext2 (0)
V/AudioCache(  293): notify(0xb03fc510, 2, 0, 0)
V/AudioCache(  293): playback complete - thread will wake up later
V/AwesomePlayer(  293): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache(  293): notify(0xb03fc510, 7, 0, 0)
V/AudioCache(  293): ignored
V/AwesomePlayer(  293): cancelPlayerEvents (keepNotifications=1)
,V/AwesomePlayer(  293): addBatteryData
V/AudioCache(  293): wait - success
V/StagefrightPlayer(  293): reset
,V/AwesomePlayer(  293): reset_l()
V/AwesomePlayer(  293): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  293): notify(0xb03fc510, 8, 0, 0)
V/AudioCache(  293): ignored
V/AwesomePlayer(  293): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  293): mAudioTrackVector clear
D/AudioPlayer(  293): reset: mPlaying=0 mReachedEOS=1 useOffload=0
I/OMXCodec(  293): [OMX.google.vorbis.decoder] stop mState=4
I/OMXCodec(  293): [OMX.google.vorbis.decoder] stop() sendCommand(0x80, OMX_CommandStateSet, OMX_StateIdle)
I/OMXCodec(  293): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
,I/OMXCodec(  293): [OMX.google.vorbis.decoder] stopOmxComponent_l() mstate = 1
I/OggExtractor(  293): OggSource::stop() mExtractor ref count = 1
I/OggExtractor(  293): OggSource::~OggSource() mExtractor !mStarted ref count = 1
I/OggExtractor(  293): ~OggSource --
I/OggExtractor(  293): ~OggExtractor ++
I/OggExtractor(  293): ~MyVorbisExtractor ++ 
I/OggExtractor(  293): ~MyVorbisExtractor --
I/OggExtractor(  293): ~OggExtractor --
,I/AudioPlayer(  293): reset out
V/AwesomePlayer(  293): reset_l() mAudioPlayer successfully deleted
I/SecVideoCapture(  293): SecVideoCapture destructor
I/SecVideoCapture(  293): reset
V/AwesomePlayer(  293): mSecCapture clear
I/SecMediaClock(  293): SecMediaClock destructor
V/AwesomePlayer(  293): mSecMediaClock clear
V/StagefrightPlayer(  293): ~StagefrightPlayer
V/StagefrightPlayer(  293): reset
V/AwesomePlayer(  293): reset_l()
V/AwesomePlayer(  293): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  293): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  293): mAudioTrackVector clear
V/AwesomePlayer(  293): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  293): mSecCapture clear
V/AwesomePlayer(  293): mSecMediaClock clear
V/AwesomePlayer(  293): destructor
,V/AwesomePlayer(  293): reset_l()
V/AwesomePlayer(  293): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  293): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  293): mAudioTrackVector clear
V/AwesomePlayer(  293): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  293): mSecCapture clear
V/AwesomePlayer(  293): mSecMediaClock clear
V/MediaPlayer( 7961): decode(46, 19235660, 21825)
V/MediaPlayerService(  293): decode(30, 19235660, 21825)
,V/MediaPlayerService(  293): player type = 3
V/AwesomePlayer(  293): setDefault
,V/AwesomePlayer(  293): constructor
V/AwesomePlayer(  293): setDefault
V/AwesomePlayer(  293): reset_l()
V/AwesomePlayer(  293): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  293): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  293): mAudioTrackVector clear
V/AwesomePlayer(  293): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  293): mSecCapture clear
,V/AwesomePlayer(  293): mSecMediaClock clear
V/StagefrightPlayer(  293): StagefrightPlayer
V/AwesomePlayer(  293): setListener
V/StagefrightPlayer(  293): initCheck
V/AwesomePlayer(  293): setAudioSink
V/StagefrightPlayer(  293): setDataSource(30, 19235660, 21825)
V/AwesomePlayer(  293): reset_l()
V/AwesomePlayer(  293): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
,V/AudioCache(  293): notify(0xb02092e0, 8, 0, 0)
V/AudioCache(  293): ignored
V/AwesomePlayer(  293): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  293): mAudioTrackVector clear
V/AwesomePlayer(  293): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  293): mSecCapture clear
V/AwesomePlayer(  293): mSecMediaClock clear
D/Utils   (  293): printFileName fd(31) -> /system/priv-app/SHealth3_5/SHealth3_5.apk
,V/AwesomePlayer(  293): track of type 'audio/vorbis' does not publish bitrate
V/AwesomePlayer(  293): mBitrate = -1 bits/sec
I/OggExtractor(  293): OggSource::OggSource() mExtractor ref count = 4
V/AwesomePlayer(  293): current audio track index (0) is added to vector
V/AwesomePlayer(  293): setDataSource_l: Audio(1), Video(0)
I/AwesomePlayer(  293): checkRightsStatus is not necessary - AwesomePlayer::setDataSource_l
V/MediaPlayerService(  293): prepare
V/AwesomePlayer(  293): prepareAsync
,V/MediaPlayerService(  293): wait for prepare
V/AwesomePlayer(  293): onPrepareAsyncEvent
I/SecMediaClock(  293): SecMediaClock constructor
I/SecMediaClock(  293): reset
I/SecVideoCapture(  293): SecVideoCapture constructor
I/SecVideoCapture(  293): reset
V/AwesomePlayer(  293): initAudioDecoder
V/AwesomePlayer(  293): checkOffloadExceptions is true
V/AudioPolicyManager(  293): isOffloadSupported: SR=44100, CM=0x3, Format=0x7000000, StreamType=-1, BitRate=4294967295, duration=1250000 us, has_video=0
,V/AudioPolicyManager(  293): isOffloadSupported: stream_type != MUSIC, returning false
I/OMXCodec(  293): Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
,I/OMXCodec(  293): Successfully allocated OMX node 'OMX.google.vorbis.decoder'
I/OMXCodec(  293): >>>UHQA initOutputFormat 16
I/AwesomePlayer(  293): Could not offload audio decode, try pcm offload
V/AudioPolicyManager(  293): isOffloadSupported: SR=44100, CM=0x1, Format=0x1c000001, StreamType=-1, BitRate=4294967295, duration=1250000 us, has_video=0
,V/AudioPolicyManager(  293): isOffloadSupported: stream_type != MUSIC, returning false
I/OMXCodec(  293): [OMX.google.vorbis.decoder] OMXCodec::start mState=1
I/OMXCodec(  293): [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
I/OMXCodec(  293): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
I/OMXCodec(  293): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
,V/AwesomePlayer(  293): finishAsyncPrepare_l
V/AwesomePlayer(  293): notifyListner_l() msg (200-MEDIA_INFO), ext1 (973), ext2 (0)
V/AudioCache(  293): notify(0xb02092e0, 200, 973, 0)
V/AudioCache(  293): ignored
V/AwesomePlayer(  293): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache(  293): notify(0xb02092e0, 5, 0, 0)
,V/AudioCache(  293): ignored
V/AwesomePlayer(  293): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache(  293): notify(0xb02092e0, 1, 0, 0)
V/AudioCache(  293): prepared
V/AudioCache(  293): wait - success
V/MediaPlayerService(  293): start
V/StagefrightPlayer(  293): start
V/AwesomePlayer(  293): play
,V/AwesomePlayer(  293): AwesomePlayer::play_l():: This is not a DRM content
V/AwesomePlayer(  293): startAudioPlayer_l, sendErrorNotification (0)
D/AudioPlayer(  293): start of Playback, useOffload 0
,I/OMXCodec(  293): [OMX.google.vorbis.decoder] 0onCmdComplete  mState =  7
,I/OMXCodec(  293): [OMX.google.vorbis.decoder] PORT_DISABLED(1)
I/OMXCodec(  293): >>>UHQA initOutputFormat 16
I/OMXCodec(  293): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
I/AudioPlayer(  293): Audio channels(2)
I/AudioPlayer(  293): Audioplayer kKeyAudioPCMFormat:0, 1, 0
I/AudioPlayer(  293): Audioplayer kKeyAudioPCMFormat read fail(2, 1)
V/AudioCache(  293): open(44100, 2, 0x0, 1, 0)
,V/AwesomePlayer(  293): notifyListner_l() msg (6-MEDIA_STARTED), ext1 (0), ext2 (0)
V/AudioCache(  293): notify(0xb02092e0, 6, 0, 0)
V/AudioCache(  293): ignored
V/AwesomePlayer(  293): addBatteryData
V/MediaPlayerService(  293): wait for playback complete
I/AudioPlayer(  293): First fillBuffer call!!
I/AudioPlayer(  293): >>> setAudioEffect Read mAudioFormat : 1, event : 235670794, value : 319688206
E/AudioPlayer(  293): >>> setAudioEffect Error mAudioFormat : 1, event : 235670794, value : 319688206
,D/SettingsProvider(  875): name = next_alarm_formatted
,D/SettingsProvider(  875): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider(  875): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider(  875): selectionArgs: false
D/SettingsProvider(  875): selectionArgs: 10091
D/SecContentProvider(  875): uri = 17 selection = isSettingsChangesAllowed
,D/SettingsProvider(  875): ret = -1
,I/OMXCodec(  293): [OMX.google.vorbis.decoder] End Of Stream
,V/AwesomePlayer(  293): postAudioEOS delayUs (0)
V/AwesomePlayer(  293): onCheckAudioStatus
V/AwesomePlayer(  293): onCheckAudioStatus() set AUDIO_AT_EOS flag
V/AwesomePlayer(  293): onStreamDone
V/AwesomePlayer(  293): MEDIA_PLAYBACK_COMPLETE
V/AwesomePlayer(  293): notifyListner_l() msg (2-MEDIA_PLAYBACK_COMPLETE), ext1 (0), ext2 (0)
V/AudioCache(  293): notify(0xb02092e0, 2, 0, 0)
V/AudioCache(  293): playback complete - thread will wake up later
V/AwesomePlayer(  293): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache(  293): notify(0xb02092e0, 7, 0, 0)
V/AudioCache(  293): ignored
V/AwesomePlayer(  293): cancelPlayerEvents (keepNotifications=1)
V/AwesomePlayer(  293): addBatteryData
,V/AudioCache(  293): wait - success
V/StagefrightPlayer(  293): reset
V/AwesomePlayer(  293): reset_l()
V/AwesomePlayer(  293): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  293): notify(0xb02092e0, 8, 0, 0)
V/AudioCache(  293): ignored
V/AwesomePlayer(  293): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  293): mAudioTrackVector clear
D/AudioPlayer(  293): reset: mPlaying=0 mReachedEOS=1 useOffload=0
I/OMXCodec(  293): [OMX.google.vorbis.decoder] stop mState=4
I/OMXCodec(  293): [OMX.google.vorbis.decoder] stop() sendCommand(0x81, OMX_CommandStateSet, OMX_StateIdle)
I/OMXCodec(  293): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
,I/OMXCodec(  293): [OMX.google.vorbis.decoder] stopOmxComponent_l() mstate = 1
I/OggExtractor(  293): OggSource::stop() mExtractor ref count = 1
I/OggExtractor(  293): OggSource::~OggSource() mExtractor !mStarted ref count = 1
I/OggExtractor(  293): ~OggSource --
I/OggExtractor(  293): ~OggExtractor ++
I/OggExtractor(  293): ~MyVorbisExtractor ++ 
I/OggExtractor(  293): ~MyVorbisExtractor --
I/OggExtractor(  293): ~OggExtractor --
,I/AudioPlayer(  293): reset out
V/AwesomePlayer(  293): reset_l() mAudioPlayer successfully deleted
I/SecVideoCapture(  293): SecVideoCapture destructor
I/SecVideoCapture(  293): reset
V/AwesomePlayer(  293): mSecCapture clear
I/SecMediaClock(  293): SecMediaClock destructor
V/AwesomePlayer(  293): mSecMediaClock clear
V/StagefrightPlayer(  293): ~StagefrightPlayer
V/StagefrightPlayer(  293): reset
V/AwesomePlayer(  293): reset_l()
V/AwesomePlayer(  293): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  293): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  293): mAudioTrackVector clear
V/AwesomePlayer(  293): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  293): mSecCapture clear
V/AwesomePlayer(  293): mSecMediaClock clear
V/AwesomePlayer(  293): destructor
V/AwesomePlayer(  293): reset_l()
V/AwesomePlayer(  293): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  293): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  293): mAudioTrackVector clear
V/AwesomePlayer(  293): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  293): mSecCapture clear
V/AwesomePlayer(  293): mSecMediaClock clear
V/MediaPlayer( 7961): decode(47, 19134596, 21552)
V/MediaPlayerService(  293): decode(30, 19134596, 21552)
V/MediaPlayerService(  293): player type = 3
V/AwesomePlayer(  293): setDefault
V/AwesomePlayer(  293): constructor
V/AwesomePlayer(  293): setDefault
V/AwesomePlayer(  293): reset_l()
V/AwesomePlayer(  293): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  293): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  293): mAudioTrackVector clear
V/AwesomePlayer(  293): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  293): mSecCapture clear
V/AwesomePlayer(  293): mSecMediaClock clear
V/StagefrightPlayer(  293): StagefrightPlayer
V/AwesomePlayer(  293): setListener
V/StagefrightPlayer(  293): initCheck
V/AwesomePlayer(  293): setAudioSink
V/StagefrightPlayer(  293): setDataSource(30, 19134596, 21552)
V/AwesomePlayer(  293): reset_l()
V/AwesomePlayer(  293): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  293): notify(0xb19272e0, 8, 0, 0)
V/AudioCache(  293): ignored
V/AwesomePlayer(  293): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  293): mAudioTrackVector clear
V/AwesomePlayer(  293): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  293): mSecCapture clear
V/AwesomePlayer(  293): mSecMediaClock clear
D/Utils   (  293): printFileName fd(31) -> /system/priv-app/SHealth3_5/SHealth3_5.apk
V/AwesomePlayer(  293): track of type 'audio/vorbis' does not publish bitrate
V/AwesomePlayer(  293): mBitrate = -1 bits/sec
I/OggExtractor(  293): OggSource::OggSource() mExtractor ref count = 4
V/AwesomePlayer(  293): current audio track index (0) is added to vector
V/AwesomePlayer(  293): setDataSource_l: Audio(1), Video(0)
I/AwesomePlayer(  293): checkRightsStatus is not necessary - AwesomePlayer::setDataSource_l
V/MediaPlayerService(  293): prepare
V/AwesomePlayer(  293): prepareAsync
V/MediaPlayerService(  293): wait for prepare
V/AwesomePlayer(  293): onPrepareAsyncEvent
I/SecMediaClock(  293): SecMediaClock constructor
I/SecMediaClock(  293): reset
I/SecVideoCapture(  293): SecVideoCapture constructor
I/SecVideoCapture(  293): reset
V/AwesomePlayer(  293): initAudioDecoder
V/AwesomePlayer(  293): checkOffloadExceptions is true
V/AudioPolicyManager(  293): isOffloadSupported: SR=44100, CM=0x3, Format=0x7000000, StreamType=-1, BitRate=4294967295, duration=1250000 us, has_video=0
V/AudioPolicyManager(  293): isOffloadSupported: stream_type != MUSIC, returning false
I/OMXCodec(  293): Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
I/OMXCodec(  293): Successfully allocated OMX node 'OMX.google.vorbis.decoder'
I/OMXCodec(  293): >>>UHQA initOutputFormat 16
I/AwesomePlayer(  293): Could not offload audio decode, try pcm offload
V/AudioPolicyManager(  293): isOffl,oadSupported: SR=44100, CM=0x1, Format=0x1c000001, StreamType=-1, BitRate=4294967295, duration=1250000 us, has_video=0
V/AudioPolicyManager(  293): isOffloadSupported: stream_type != MUSIC, returning false
I/OMXCodec(  293): [OMX.google.vorbis.decoder] OMXCodec::start mState=1
I/OMXCodec(  293): [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
I/OMXCodec(  293): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
I/OMXCodec(  293): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
V/AwesomePlayer(  293): finishAsyncPrepare_l
V/AwesomePlayer(  293): notifyListner_l() msg (200-MEDIA_INFO), ext1 (973), ext2 (0)
V/AudioCache(  293): notify(0xb19272e0, 200, 973, 0)
V/AudioCache(  293): ignored
V/AwesomePlayer(  293): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache(  293): notify(0xb19272e0, 5, 0, 0)
V/AudioCache(  293): ignored
V/AwesomePlayer(  293): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache(  293): notify(0xb19272e0, 1, 0, 0)
V/AudioCache(  293): prepared
V/AudioCache(  293): wait - success
V/MediaPlayerService(  293): start
V/StagefrightPlayer(  293): start
V/AwesomePlayer(  293): play
V/AwesomePlayer(  293): AwesomePlayer::play_l():: This is not a DRM content
V/AwesomePlayer(  293): startAudioPlayer_l, sendErrorNotification (0)
D/AudioPlayer(  293): start of Playback, useOffload 0
I/OMXCodec(  293): [OMX.google.vorbis.decoder] 0onCmdComplete  mState =  7
I/OMXCodec(  293): [OMX.google.vorbis.decoder] PORT_DISABLED(1)
I/OMXCodec(  293): >>>UHQA initOutputFormat 16
I/OMXCodec(  293): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
,I/AudioPlayer(  293): Audio channels(2)
,I/AudioPlayer(  293): Audioplayer kKeyAudioPCMFormat:0, 1, 0
I/AudioPlayer(  293): Audioplayer kKeyAudioPCMFormat read fail(2, 1)
V/AudioCache(  293): open(44100, 2, 0x0, 1, 0)
,V/AwesomePlayer(  293): notifyListner_l() msg (6-MEDIA_STARTED), ext1 (0), ext2 (0)
V/AudioCache(  293): notify(0xb19272e0, 6, 0, 0)
V/AudioCache(  293): ignored
V/AwesomePlayer(  293): addBatteryData
I/AudioPlayer(  293): First fillBuffer call!!
,V/MediaPlayerService(  293): wait for playback complete
,E/ActivityManager(  875): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  875): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  875): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  875): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 8114): MountEmulatedStorage()
,E/Zygote  ( 8114): v2
I/libpersona( 8114): KNOX_SDCARD checking this for 10104
I/libpersona( 8114): KNOX_SDCARD not a persona
,I/ActivityManager(  875): Start proc com.sec.esdk.elm for broadcast com.sec.esdk.elm/.receiver.MainReceiver: pid=8114 uid=10104 gids={50104, 9997, 3003} abi=armeabi-v7a
,I/ActivityManager(  875): Killing 7044:com.sec.kidsplat.installer/u0a166 (adj 15): bgCount ##41
,I/OMXCodec(  293): [OMX.google.vorbis.decoder] End Of Stream
,V/AwesomePlayer(  293): postAudioEOS delayUs (0)
,V/AwesomePlayer(  293): onCheckAudioStatus
,V/AwesomePlayer(  293): onCheckAudioStatus() set AUDIO_AT_EOS flag
V/AwesomePlayer(  293): onStreamDone
V/AwesomePlayer(  293): MEDIA_PLAYBACK_COMPLETE
V/AwesomePlayer(  293): notifyListner_l() msg (2-MEDIA_PLAYBACK_COMPLETE), ext1 (0), ext2 (0)
,V/AudioCache(  293): notify(0xb19272e0, 2, 0, 0)
V/AudioCache(  293): playback complete - thread will wake up later
V/AwesomePlayer(  293): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache(  293): notify(0xb19272e0, 7, 0, 0)
V/AudioCache(  293): ignored
V/AwesomePlayer(  293): cancelPlayerEvents (keepNotifications=1)
,V/AwesomePlayer(  293): addBatteryData
V/AudioCache(  293): wait - success
V/StagefrightPlayer(  293): reset
,V/AwesomePlayer(  293): reset_l()
V/AwesomePlayer(  293): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
,V/AudioCache(  293): notify(0xb19272e0, 8, 0, 0)
V/AudioCache(  293): ignored
V/AwesomePlayer(  293): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  293): mAudioTrackVector clear
,D/AudioPlayer(  293): reset: mPlaying=0 mReachedEOS=1 useOffload=0
I/OMXCodec(  293): [OMX.google.vorbis.decoder] stop mState=4
I/OMXCodec(  293): [OMX.google.vorbis.decoder] stop() sendCommand(0x82, OMX_CommandStateSet, OMX_StateIdle)
,I/OMXCodec(  293): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
,I/art     (  324): Explicit concurrent mark sweep GC freed 8732(371KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 14MB/23MB, paused 269us total 13.808ms
,I/OMXCodec(  293): [OMX.google.vorbis.decoder] stopOmxComponent_l() mstate = 1
I/OggExtractor(  293): OggSource::stop() mExtractor ref count = 1
I/OggExtractor(  293): OggSource::~OggSource() mExtractor !mStarted ref count = 1
I/OggExtractor(  293): ~OggSource --
,I/OggExtractor(  293): ~OggExtractor ++
I/OggExtractor(  293): ~MyVorbisExtractor ++ 
I/OggExtractor(  293): ~MyVorbisExtractor --
I/OggExtractor(  293): ~OggExtractor --
,I/AudioPlayer(  293): reset out
,V/AwesomePlayer(  293): reset_l() mAudioPlayer successfully deleted
I/SecVideoCapture(  293): SecVideoCapture destructor
I/SecVideoCapture(  293): reset
V/AwesomePlayer(  293): mSecCapture clear
,I/SecMediaClock(  293): SecMediaClock destructor
V/AwesomePlayer(  293): mSecMediaClock clear
,V/StagefrightPlayer(  293): ~StagefrightPlayer
V/StagefrightPlayer(  293): reset
V/AwesomePlayer(  293): reset_l()
V/AwesomePlayer(  293): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
,V/AwesomePlayer(  293): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  293): mAudioTrackVector clear
V/AwesomePlayer(  293): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  293): mSecCapture clear
V/AwesomePlayer(  293): mSecMediaClock clear
,V/AwesomePlayer(  293): destructor
,V/AwesomePlayer(  293): reset_l()
V/AwesomePlayer(  293): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  293): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  293): mAudioTrackVector clear
,V/AwesomePlayer(  293): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  293): mSecCapture clear
V/AwesomePlayer(  293): mSecMediaClock clear
,I/art     (  324): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 14MB/23MB, paused 247us total 9.172ms
V/MediaPlayer( 7961): decode(48, 19228560, 7017)
,I/art     (  324): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 14MB/23MB, paused 245us total 7.547ms
,I/SecureStorage(  358): [INFO]: SPID(0x00000005)Secure Storage Daemon finished processing with result: 0
I/SecureStorage(  358): [INFO]: SPID(0x00000005)PID: 7982, TID: 7994
,I/SELinux ( 8114): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,V/MediaPlayerService(  293): decode(30, 19228560, 7017)
,I/SELinux ( 8114): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,V/MediaPlayerService(  293): player type = 3
V/AwesomePlayer(  293): setDefault
V/AwesomePlayer(  293): constructor
,E/SELinux ( 8114): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
V/AwesomePlayer(  293): setDefault
V/AwesomePlayer(  293): reset_l()
V/AwesomePlayer(  293): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  293): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  293): mAudioTrackVector clear
V/AwesomePlayer(  293): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  293): mSecCapture clear
V/AwesomePlayer(  293): mSecMediaClock clear
V/StagefrightPlayer(  293): StagefrightPlayer
V/AwesomePlayer(  293): setListener
V/StagefrightPlayer(  293): initCheck
V/AwesomePlayer(  293): setAudioSink
V/StagefrightPlayer(  293): setDataSource(30, 19228560, 7017)
V/AwesomePlayer(  293): reset_l()
V/AwesomePlayer(  293): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  293): notify(0xafa141a0, 8, 0, 0)
V/AudioCache(  293): ignored
V/AwesomePlayer(  293): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  293): mAudioTrackVector clear
V/AwesomePlayer(  293): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  293): mSecCapture clear
V/AwesomePlayer(  293): mSecMediaClock clear
D/Utils   (  293): printFileName fd(31) -> /system/priv-app/SHealth3_5/SHealth3_5.apk
,V/AwesomePlayer(  293): track of type 'audio/vorbis' does not publish bitrate
V/AwesomePlayer(  293): mBitrate = -1 bits/sec
I/OggExtractor(  293): OggSource::OggSource() mExtractor ref count = 4
V/AwesomePlayer(  293): current audio track index (0) is added to vector
V/AwesomePlayer(  293): setDataSource_l: Audio(1), Video(0)
I/AwesomePlayer(  293): checkRightsStatus is not necessary - AwesomePlayer::setDataSource_l
V/MediaPlayerService(  293): prepare
V/AwesomePlayer(  293): prepareAsync
V/MediaPlayerService(  293): wait for prepare
V/AwesomePlayer(  293): onPrepareAsyncEvent
I/SecMediaClock(  293): SecMediaClock constructor
I/SecMediaClock(  293): reset
I/SecVideoCapture(  293): SecVideoCapture constructor
I/SecVideoCapture(  293): reset
V/AwesomePlayer(  293): initAudioDecoder
V/AwesomePlayer(  293): checkOffloadExceptions is true
V/AudioPolicyManager(  293): isOffloadSupported: SR=44100, CM=0x3, Format=0x7000000, StreamType=-1, BitRate=4294967295, duration=173945 us, has_video=0
V/AudioPolicyManager(  293): isOffloadSupported: stream_type != MUSIC, returning false
I/OMXCodec(  293): Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
,I/OMXCodec(  293): Successfully allocated OMX node 'OMX.google.vorbis.decoder'
,I/OMXCodec(  293): >>>UHQA initOutputFormat 16
I/AwesomePlayer(  293): Could not offload audio decode, try pcm offload
V/AudioPolicyManager(  293): isOffloadSupported: SR=44100, CM=0x1, Format=0x1c000001, StreamType=-1, BitRate=4294967295, duration=173945 us, has_video=0
V/AudioPolicyManager(  293): isOffloadSupported: stream_type != MUSIC, returning false
,I/OMXCodec(  293): [OMX.google.vorbis.decoder] OMXCodec::start mState=1
I/OMXCodec(  293): [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
I/OMXCodec(  293): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
,I/OMXCodec(  293): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
V/AwesomePlayer(  293): finishAsyncPrepare_l
,V/AwesomePlayer(  293): notifyListner_l() msg (200-MEDIA_INFO), ext1 (973), ext2 (0)
V/AudioCache(  293): notify(0xafa141a0, 200, 973, 0)
V/AudioCache(  293): ignored
V/AwesomePlayer(  293): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache(  293): notify(0xafa141a0, 5, 0, 0)
V/AudioCache(  293): ignored
,V/AwesomePlayer(  293): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache(  293): notify(0xafa141a0, 1, 0, 0)
V/AudioCache(  293): prepared
,V/AudioCache(  293): wait - success
V/MediaPlayerService(  293): start
V/StagefrightPlayer(  293): start
V/AwesomePlayer(  293): play
V/AwesomePlayer(  293): AwesomePlayer::play_l():: This is not a DRM content
V/AwesomePlayer(  293): startAudioPlayer_l, sendErrorNotification (0)
D/AudioPlayer(  293): start of Playback, useOffload 0
,I/OMXCodec(  293): [OMX.google.vorbis.decoder] 0onCmdComplete  mState =  7
I/OMXCodec(  293): [OMX.google.vorbis.decoder] PORT_DISABLED(1)
I/OMXCodec(  293): >>>UHQA initOutputFormat 16
I/OMXCodec(  293): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
,I/AudioPlayer(  293): Audio channels(2)
I/AudioPlayer(  293): Audioplayer kKeyAudioPCMFormat:0, 1, 0
I/AudioPlayer(  293): Audioplayer kKeyAudioPCMFormat read fail(2, 1)
V/AudioCache(  293): open(44100, 2, 0x0, 1, 0)
,V/AwesomePlayer(  293): notifyListner_l() msg (6-MEDIA_STARTED), ext1 (0), ext2 (0)
V/AudioCache(  293): notify(0xafa141a0, 6, 0, 0)
V/AudioCache(  293): ignored
V/AwesomePlayer(  293): addBatteryData
I/AudioPlayer(  293): First fillBuffer call!!
I/AudioPlayer(  293): >>> setAudioEffect Read mAudioFormat : 1, event : 235670794, value : 319688206
E/AudioPlayer(  293): >>> setAudioEffect Error mAudioFormat : 1, event : 235670794, value : 319688206
V/MediaPlayerService(  293): wait for playback complete
,I/OMXCodec(  293): [OMX.google.vorbis.decoder] End Of Stream
,V/AwesomePlayer(  293): postAudioEOS delayUs (0)
V/AwesomePlayer(  293): onCheckAudioStatus
V/AwesomePlayer(  293): onCheckAudioStatus() set AUDIO_AT_EOS flag
V/AwesomePlayer(  293): onStreamDone
V/AwesomePlayer(  293): MEDIA_PLAYBACK_COMPLETE
V/AwesomePlayer(  293): notifyListner_l() msg (2-MEDIA_PLAYBACK_COMPLETE), ext1 (0), ext2 (0)
V/AudioCache(  293): notify(0xafa141a0, 2, 0, 0)
V/AudioCache(  293): playback complete - thread will wake up later
V/AwesomePlayer(  293): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache(  293): notify(0xafa141a0, 7, 0, 0)
V/AudioCache(  293): ignored
V/AwesomePlayer(  293): cancelPlayerEvents (keepNotifications=1)
V/AwesomePlayer(  293): addBatteryData
V/AudioCache(  293): wait - success
V/StagefrightPlayer(  293): reset
V/AwesomePlayer(  293): reset_l()
V/AwesomePlayer(  293): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  293): notify(0xafa141a0, 8, 0, 0)
V/AudioCache(  293): ignored
V/AwesomePlayer(  293): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  293): mAudioTrackVector clear
D/AudioPlayer(  293): reset: mPlaying=0 mReachedEOS=1 useOffload=0
I/OMXCodec(  293): [OMX.google.vorbis.decoder] stop mState=4
I/OMXCodec(  293): [OMX.google.vorbis.decoder] stop() sendCommand(0x83, OMX_CommandStateSet, OMX_StateIdle)
I/OMXCodec(  293): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
I/OMXCodec(  293): [OMX.google.vorbis.decoder] stopOmxComponent_l() mstate = 1
I/OggExtractor(  293): OggSource::stop() mExtractor ref count = 1
I/OggExtractor(  293): OggSource::~OggSource() mExtractor !mStarted ref count = 1
I/OggExtractor(  293): ~OggSource --
I/OggExtractor(  293): ~OggExtractor ++
I/OggExtractor(  293): ~MyVorbisExtractor ++ 
I/OggExtractor(  293): ~MyVorbisExtractor --
I/OggExtractor(  293): ~OggExtractor --
,I/AudioPlayer(  293): reset out
V/AwesomePlayer(  293): reset_l() mAudioPlayer successfully deleted
I/SecVideoCapture(  293): SecVideoCapture destructor
I/SecVideoCapture(  293): reset
V/AwesomePlayer(  293): mSecCapture clear
I/SecMediaClock(  293): SecMediaClock destructor
V/AwesomePlayer(  293): mSecMediaClock clear
V/StagefrightPlayer(  293): ~StagefrightPlayer
V/StagefrightPlayer(  293): reset
V/AwesomePlayer(  293): reset_l()
V/AwesomePlayer(  293): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  293): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  293): mAudioTrackVector clear
V/AwesomePlayer(  293): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  293): mSecCapture clear
V/AwesomePlayer(  293): mSecMediaClock clear
V/AwesomePlayer(  293): destructor
V/AwesomePlayer(  293): reset_l()
V/AwesomePlayer(  293): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  293): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  293): mAudioTrackVector clear
V/AwesomePlayer(  293): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  293): mSecCapture clear
W/libprocessgroup(  875): failed to open /acct/uid_10166/pid_7044/cgroup.procs: No such file or directory
V/AwesomePlayer(  293): mSecMediaClock clear
,D/TimaKeyStoreProvider( 8114): TimaSignature is unavailable
,D/ActivityThread( 8114): Added TimaKeyStore provider
,D/ResourcesManager( 8114): creating new AssetManager and set to /system/app/ELMAgent/ELMAgent.apk
,D/elm:14451( 8114): ELMAbstractReceiver.onReceive() : Intent { act=android.intent.action.TIME_SET flg=0x24000010 cmp=com.sec.esdk.elm/.receiver.MainReceiver }
,D/elm:14451( 8114): ELMEngine.ELMEngine( context ).
,D/elm:14451( 8114): MDMBridge.setEnterpriseBridge()
,D/elm:14451( 8114): ELMAbstractReceiver : Receive Intent { act=android.intent.action.TIME_SET flg=0x24000010 cmp=com.sec.esdk.elm/.service.ElmAgentService } END.
,D/elm:14451( 8114): ElmAgentService : onCreate()
,D/GeoLookout( 7257): H: oG7yKmvlgCB+MeB9ScCFjRATu9ZqRwmv7A7uEos9Q9mvO4YDA6qaoxYEtGEMNH1w
D/elm:14451( 8114): ElmAgentService : onHandleIntent() Intent { act=android.intent.action.TIME_SET flg=0x24000010 cmp=com.sec.esdk.elm/.service.ElmAgentService }
,D/GeoLookout( 7257): H: oG7yKmvlgCB+MeB9ScCFjRej64htfcxG5kL3SHyGYDkvkgPm5dotWx3IPNd1bDZ3HtYRASO8LE3XMTl+CWy7mA0iuhqjXXzZB9tx1thU84s=
,D/GeoLookout( 7257): H: oG7yKmvlgCB+MeB9ScCFjfFK6n2WxeJSk2pAGNbQ5p0X1S2Rcjfuoz/uR69LW7q4dRvDIbb+p93sEFNr9NIFsA==
,D/GeoLookout( 7257): H: oG7yKmvlgCB+MeB9ScCFjYXOqDX8ezzeYFlqIugeVh9tddYklHQaYJQeZ5D1n0CWhpLwjVw6z1MjJ35DMCBpaiDarp/XHnFoZkDEv7L3KA0=
,D/elm:14451( 8114): ELMAgentService.listeningToTimeDateChanges( context, intent ).
,D/elm:14451( 8114): ELMEngine.ServiceHandler.handleMessage( ALARM_MODIFY ). 
D/elm:14451( 8114): ModuleBase.ModifySetAlarm()
D/elm:14451( 8114): MDMBridge.getInstance()
D/elm:14451( 8114): MDMBridge.getAllLicenseInfoFromSDK()
,D/GeoLookout( 7257): H: oG7yKmvlgCB+MeB9ScCFjfFK6n2WxeJSk2pAGNbQ5p22QnYVOq7PKBLe2qMCpGYydjAdGQcIiahEY/ZKpSgLLdWk9sWz2GyOXv6qxHaW2H26fDXZ20X1h16kWUzITBbTh7G11qed9LU9uS7nht+c434ovyAFMeLCkHYTLVI5fwY=
D/GeoLookout( 7257): H: oG7yKmvlgCB+MeB9ScCFjfFK6n2WxeJSk2pAGNbQ5p3XGW9731/b3rcTnBUpVV7cdjAdGQcIiahEY/ZKpSgLLdWk9sWz2GyOXv6qxHaW2H26fDXZ20X1h16kWUzITBbTuusrI/cx+kAef/132msRDOjT1uSoU6fTNM2FcLdxHvc=
,D/GeoLookout( 7257): H: oG7yKmvlgCB+MeB9ScCFjfFK6n2WxeJSk2pAGNbQ5p2JyN4reRVmsjd9hDStHSrotCc+mJqVQceay8W/Aon4dQ==
,D/GeoLookout( 7257): H: oG7yKmvlgCB+MeB9ScCFjfFK6n2WxeJSk2pAGNbQ5p1uWsUHzWsv+tlyIgF4nsoYQRDW3di+2lqtjRvD6Foc0OSK79yglawLMq2qfKHF0t+rzoiO7awSXeKcgiSJMfNZu89EQ821mpIbyCdOp1WNyQ==
,D/GeoLookout( 7257): H: oG7yKmvlgCB+MeB9ScCFjfFK6n2WxeJSk2pAGNbQ5p3cXw/c05/SMEtFN8iBNLnY4tvU5wsp5Dwccfz++DFQoQ==
,D/GeoLookout( 7257): H: oG7yKmvlgCB+MeB9ScCFjfFK6n2WxeJSk2pAGNbQ5p1QdJyd/p15/7HTe6I45I69M4svW0ahfvr+YIey5W092wGcTlQvpBSgOqyfO72Z3wUxq59dXfXVWbt+zgy3TJ0U
,D/elm:14451( 8114): ElmAgentService : onDestroy().
,D/GeoLookout( 7257): H: oG7yKmvlgCB+MeB9ScCFjRATu9ZqRwmv7A7uEos9Q9mvO4YDA6qaoxYEtGEMNH1w
,D/GeoLookout( 7257): H: oG7yKmvlgCB+MeB9ScCFjRej64htfcxG5kL3SHyGYDkvkgPm5dotWx3IPNd1bDZ3HtYRASO8LE3XMTl+CWy7mA0iuhqjXXzZB9tx1thU84s=
,D/GeoLookout( 7257): H: oG7yKmvlgCB+MeB9ScCFjVjhROowReQZ6uZ83+PHbxXxfrUuNQHmPlY4PsIKqeHXpHMfmw7BKa8EvZP1XFE95vEpSHlOxg9XQoR6KQvcMJUezCj+VlRSvYmiaFKv4yMdF9ANJ7ri8t1rvBR++sDAZA==
,E/ActivityManager(  875): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  875): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  875): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  875): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 8136): MountEmulatedStorage()
E/Zygote  ( 8136): v2
I/libpersona( 8136): KNOX_SDCARD checking this for 10149
I/libpersona( 8136): KNOX_SDCARD not a persona
,I/ActivityManager(  875): Start proc com.sec.android.widgetapp.SPlannerAppWidget for broadcast com.sec.android.widgetapp.SPlannerAppWidget/.EasyWidget.EasyCalendarAppWidgetProvider: pid=8136 uid=10149 gids={50149, 9997} abi=armeabi-v7a
,I/ActivityManager(  875): Killing 6598:com.google.android.gms:car/u0a12 (adj 15): bgCount ##41
,I/SELinux ( 8136): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 8136): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 8136): [DEBUG] get_category: variable seinfo: shared sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 8136): TimaSignature is unavailable
,D/ActivityThread( 8136): Added TimaKeyStore provider
,W/libprocessgroup(  875): failed to open /acct/uid_10012/pid_6598/cgroup.procs: No such file or directory
,D/ResourcesManager( 8136): creating new AssetManager and set to /system/app/SPlannerWidget_OS_UPG/SPlannerWidget_OS_UPG.apk
,W/ResourcesManager( 8136): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,W/ResourcesManager( 8136): Asset path '/system/framework/sws.jar' does not exist or contains no resources.
,E/ActivityManager(  875): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  875): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  875): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  875): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 8151): MountEmulatedStorage()
I/libpersona( 8151): KNOX_SDCARD checking this for 10150
E/Zygote  ( 8151): v2
I/libpersona( 8151): KNOX_SDCARD not a persona
,I/ActivityManager(  875): Start proc com.android.calendar for broadcast com.android.calendar/.alerts.AlertReceiver: pid=8151 uid=10150 gids={50150, 9997, 3003, 1028, 1015, 1023, 3002} abi=armeabi-v7a
,I/ActivityManager(  875): Killing 7062:com.samsung.android.provider.shootingmodeprovider/u0a170 (adj 15): bgCount ##41
,I/SELinux ( 8151): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 8151): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 8151): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 8151): TimaSignature is unavailable
,D/ActivityThread( 8151): Added TimaKeyStore provider
,W/libprocessgroup(  875): failed to open /acct/uid_10170/pid_7062/cgroup.procs: No such file or directory
,D/ResourcesManager( 8151): creating new AssetManager and set to /system/app/SPlanner_OS_UPG/SPlanner_OS_UPG.apk
,W/ResourcesManager( 8151): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
,W/ResourcesManager( 8151): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 8151): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,D/daemonapp( 1370): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,I/SecureStorage( 7982): [INFO]: SPID(0x00000000)Processing data has been completed
,I/SecureStorage( 7982): [INFO]: SPID(0x00000000)WARNING! Failed to find SecureStorageExceptionJNI!..
,E/ActivityManager(  875): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  875): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  875): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  875): checkUser: useridlist=null, currentuser=0
,I/SA      ( 7696): [RC New] [v2liruge] api execute + 657
,I/SA      ( 7696): [RC New] executeRequest [v2liruge] httpResponse : HTTP/1.1 200 OK
,I/System.out( 7696): AsyncTask #1 calls detatch()
,I/SA      ( 7696): [ODM] saveOpenData( GEO_IP, PL )
,E/Zygote  ( 8174): MountEmulatedStorage()
E/Zygote  ( 8174): v2
I/libpersona( 8174): KNOX_SDCARD checking this for 10046
I/libpersona( 8174): KNOX_SDCARD not a persona
,I/ActivityManager(  875): Start proc com.android.providers.calendar for content provider com.android.providers.calendar/.CalendarProvider2: pid=8174 uid=10046 gids={50046, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/SA      ( 7696): [OCP] update openData : PL
,I/SecSQLiteOpenHelper( 7961): getWritableDatabase(pwd)
I/SecSQLiteOpenHelper( 7961): getDatabaseLocked(b,b,pwd)...
,I/SecSQLiteOpenHelper( 7961): Open platform.db in secure mode
,D/SecSQLiteDatabase( 7961): Android Version: 5.0
D/SecSQLiteDatabase( 7961): Load library secsqlite.so for Android 5.0
,I/SELinux ( 8174): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 8174): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
E/SELinux ( 8174): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,D/SecurityLogAgent( 7462): KnoxConfiguration : Current State = 1
D/SecurityLogAgent( 7462): KnoxConfiguration : Current State Mapping Found 
D/SecurityLogAgent( 7462): StateMachine : Current State = 1
,D/ConnectivityService(  875): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/SA      ( 7696): [TPMU] getNetworkMcc : 
,E/ActivityManager(  875): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  875): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  875): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  875): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 8188): MountEmulatedStorage()
,I/ActivityManager(  875): Start proc com.sec.android.app.taskmanager for broadcast com.sec.android.app.taskmanager/.UnusedAppsIntentReceiver: pid=8188 uid=10176 gids={50176, 9997} abi=armeabi-v7a
E/Zygote  ( 8188): v2
I/libpersona( 8188): KNOX_SDCARD checking this for 10176
I/libpersona( 8188): KNOX_SDCARD not a persona
,I/SA      ( 7696): [SCU] saveMccToPreferece Start
I/SA      ( 7696): [SCU] RegionMCC : 260
I/SA      ( 7696): [SSP] query invoked
,I/SecSQLiteDatabase( 7961): openSecureDatabase...
,I/SecSQLiteDatabase( 7961): private openSecureDatabase...
I/SecSQLiteConnectionPool( 7961): OpenSecure
,I/SecSQLiteConnectionPool( 7961): OpenSecure with password
I/SecSQLiteConnectionPool( 7961): openSecureConnectionLocked
,I/SecSQLiteDatabase( 7961): ...private openSecureDatabase
I/SecSQLiteDatabase( 7961): ...openSecureDatabase
,I/SELinux ( 8188): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
D/TimaKeyStoreProvider( 8174): TimaSignature is unavailable
D/ActivityThread( 8174): Added TimaKeyStore provider
I/SELinux ( 8188): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
E/SELinux ( 8188): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/SA      ( 7696): [TPMU] GetMccFromDB : null
I/SA      ( 7696): [SCU] getMccFromPreferece mcc = 260
,I/SecSQLiteOpenHelper( 7961): ...getDatabaseLocked(b,b,pwd)
,I/SA      ( 7696): [SCU] saveMccToPreferece End
,D/SecSQLiteOpenHelper( 7961): ...getDatabaseLocked(b,b,pwd)
,I/SA      ( 7696): [RC New] executeRequest [v2liruge] end. 829
,D/TimaKeyStoreProvider( 8188): TimaSignature is unavailable
,D/ActivityThread( 8188): Added TimaKeyStore provider
,D/ResourcesManager( 8174): creating new AssetManager and set to /system/priv-app/SecCalendarProvider/SecCalendarProvider.apk
,I/SA      ( 7696): [RC New] Execute end
,I/SA      ( 7696): [OR] GetMyCountryZoneTask mcc = 260
I/SA      ( 7696): [OR] GetMyCountryZoneTask Success
,W/ResourcesManager( 8174): Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
,D/ResourcesManager( 8188): creating new AssetManager and set to /system/app/TaskManager/TaskManager.apk
,W/ResourcesManager( 8188): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,I/CalendarProvider2( 8174): CalendarProvider2.onCreate() called
,E/ActivityManager(  875): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  875): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  875): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  875): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 8209): MountEmulatedStorage()
E/Zygote  ( 8209): v2
I/libpersona( 8209): KNOX_SDCARD checking this for 1000
I/libpersona( 8209): KNOX_SDCARD not a persona
,I/ActivityManager(  875): Start proc com.qualcomm.timeservice for broadcast com.qualcomm.timeservice/.TimeServiceBroadcastReceiver: pid=8209 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,I/ActivityManager(  875): Killing 7099:com.sec.android.app.videoplayer/u0a54 (adj 15): bgCount ##41
,W/System.err( 7961): java.lang.NumberFormatException: Invalid int: "null"
,W/System.err( 7961): 	at java.lang.Integer.invalidInt(Integer.java:138)
W/System.err( 7961): 	at java.lang.Integer.parseInt(Integer.java:358)
W/System.err( 7961): 	at java.lang.Integer.parseInt(Integer.java:334)
W/System.err( 7961): 	at com.sec.android.app.shealth.common.utils.logging.service.LogManager.setProfileItems(LogManager.java:449)
W/System.err( 7961): 	at com.sec.android.app.shealth.common.utils.logging.service.LogManager$LogHandler.handleMessage(LogManager.java:1173)
W/System.err( 7961): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 7961): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 7961): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/SELinux ( 8209): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/dhcpcd  ( 7623): wlan0: sending IPv6 Router Solicitation
,I/SELinux ( 8209): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 8209): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,V/AlarmManager(  875): waitForAlarm result :8
,W/libprocessgroup(  875): failed to open /acct/uid_10054/pid_7099/cgroup.procs: No such file or directory
,D/TimaKeyStoreProvider( 8209): TimaSignature is unavailable
,D/ActivityThread( 8209): Added TimaKeyStore provider
,D/ResourcesManager( 8209): creating new AssetManager and set to /system/app/TimeService/TimeService.apk
,D/TimeService( 8209): Receivedandroid.intent.action.TIME_SET intent. Current Time is 1450109353131
D/        ( 8209): TimeServiceNative: User Time to be set is 1450109353131
D/QC-time-services( 8209): Lib:time_genoff_operation: pargs->base = 2
D/QC-time-services( 8209): Lib:time_genoff_operation: pargs->operation = 0
D/QC-time-services( 8209): Lib:time_genoff_operation: pargs->ts_val = 1450109353131
,D/QC-time-services( 8209): Lib:time_genoff_operation: Send to server  passed!!
,D/QC-time-services(  351): Daemon: Connection accepted:time_genoff
,D/QC-time-services(  351): Daemon:Received base = 2, unit = 1, operation = 0,value = 1450109353131
,D/QC-time-services(  351): Daemon:genoff_opr: Base = 2, val = 1450109353131, operation = 0
,D/QC-time-services(  351): Daemon:rtc_get: Time read from RTC -- MM/DD/YY HH:MM:SS3/21/70 3:44:24
,D/QC-time-services(  351): Daemon:Value read from RTC seconds = 9517464000
D/QC-time-services(  351): Daemon:new time 1450109353131 
D/QC-time-services(  351): Daemon: delta 1440591889131 genoff 1440591889131 
,D/QC-time-services(  351): Daemon:genoff_persistent_update: Writing genoff = 1440591889131 to memory
D/QC-time-services(  351): Daemon:Opening File: /data/time/ats_2
D/QC-time-services(  351): Daemon:time_persistent_memory_opr:Genoff write operation 
,D/QC-time-services(  351): Updating the TOD offset
D/QC-time-services(  351): Daemon:genoff_persistent_update: Writing genoff = 1440591889131 to memory
D/QC-time-services(  351): Daemon:Opening File: /data/time/ats_1
D/QC-time-services(  351): Daemon:time_persistent_memory_opr:Genoff write operation 
,E/QC-time-services(  351): Daemon:Update to modem bit set
D/QC-time-services(  351): Daemon:genoff_send_modem: Sending data to MODEM !
D/QC-time-services(  351): Daemon: Base = 2, Value being sent to MODEM = 1124627089131
,E/QC-time-services( 8209): Receive Passed == base = 2, unit = 1, operation = 0, result = 0
,D/ConnectivityService(  875): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/ActivityManager(  875): Killing 4813:com.google.android.gms.wearable/u0a12 (adj 15): bgCount ##41
,E/QC-time-services(  351): Daemon:tod_update_ind_cb: Got Update from modem msg_id 40
E/QC-time-services(  351): Daemon: Time-services: Waiting to acceptconnection
,I/GLSUser ( 1652): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.googlequicksearchbox, service: oauth2:https://www.googleapis.com/auth/googlenow
I/GLSUser ( 1652): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/googlenow without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1652): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1652): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,D/daemonapp( 1370): [MSC_Daemon]>>> WU:262 [0:0] regintype : EUR
,D/daemonapp( 1370): [MSC_Daemon]>>> WU:318 [0:0] cp type is : cp_eng
V/GLSActivity( 1652): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/daemonapp( 1370): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/daemonapp( 1370): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/weatherinfo
,D/daemonapp( 1370): [MSC_Daemon]>>> WDSM:41 [0:0] Act : androidintentactionTIME_SET, run:true
,D/ResourcesManager( 1652): creating new AssetManager and set to /system/priv-app/Velvet/Velvet.apk
,D/comsamsunglog( 1370): [MSC_Daemon]>>> ====================================================================================================================
,D/comsamsunglog( 1370): [MSC_Daemon]>>> daemonapp [Version : 15010801 ] [ 2 ] 
D/comsamsunglog( 1370): [MSC_Daemon]>>> Header set to : ===> "daemonapp" <===
D/comsamsunglog( 1370): [MSC_Daemon]>>> ====================================================================================================================
,D/daemonapp( 1370): [MSC_Daemon]>>> WDSM:82 [0:0] c:null, r:3
,D/daemonapp( 1370): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/packagename
,D/daemonapp( 1370): [MSC_Daemon]>>> WU:1622 [0:0] PakNme size = 5
V/BitmapFactory( 1652): DecodeImagePath(decodeResourceStream3) : res/mipmap-xxhdpi-v4/ic_launcher_google_search.png
,V/BitmapFactory( 1652): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/daemonapp( 1370): [MSC_Daemon]>>> WU:262 [0:0] regintype : EUR
,D/daemonapp( 1370): [MSC_Daemon]>>> WU:318 [0:0] cp type is : cp_eng
D/daemonapp( 1370): [MSC_Daemon]>>> WU:1626 [0:0] CP Name cp_eng
D/SecContentProvider2(  875): uri = 14 selection = getSealedState
D/SecContentProvider2(  875): mCursor = null
,D/SecContentProvider2(  875): KnoxCustomManagerService offline: service is not available
D/daemonapp( 1370): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/packagename
,D/ApplicationPolicy(  875): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy(  875): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,E/daemonapp( 1370): [MSC_Daemon]>>> WU:1606 [0:0] [NameNotFoundException] !!
,D/StatusBar( 1169): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,W/Search.LoginHelper( 1527): User recoverable exception for scope: oauth2:https://www.googleapis.com/auth/googlenow
I/PhoneStatusBar( 1169): Icon Only
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
D/PanelView( 1169): There is/are notification(s) 
,D/PanelView( 1169): There is/are notification(s) 
,W/libprocessgroup(  875): failed to open /acct/uid_10012/pid_4813/cgroup.procs: No such file or directory
,D/comdaemonstockapp( 1370): [Daemon_Stock]>>> StockclockDaemonService.java:61 [0:0] onReceive: androidintentactionTIME_SET
,D/comdaemonstockapp( 1370): [Daemon_Stock]>>> StockclockDaemonService.java:62 [0:0] appServiceStatus: 0
,I/rmt_storage(  275): rmt_storage_connect_cb: clnt_h=0x5 conn_h=0xb6b01090
,I/rmt_storage(  275): rmt_storage_rw_iovec_cb: /boot/modem_fs1: clnt_h=0x1: req_h=0xa msg_id=3: R/W request received
I/rmt_storage(  275): wakelock acquired: 1, error no: 42
I/rmt_storage(  275): rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1 Unblock worker thread (th_id: -1229455232)
,D/ConnectivityService(  875): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SHealthUpgrade(SHealthUpgradeUtil)( 7961): isShealthServiceInstalled() : HealthService is Installed.
,D/SHealthUpgrade(SHealthUpgradeUtil)( 7961): isShealthService2xInstalled() : HEALTH SERVICE is INSTALLED.
,D/SHealthUpgrade(SHealthUpgradeUtil)( 7961): isShealthService2xInstalled() : HEALTH SERVICE VERSION = 2.x
,I/rmt_storage(  275): rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1: req_h=0xa msg_id=3: Bytes written = 1572864
I/rmt_storage(  275): rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1: req_h=0xa msg_id=3: Send response: res=0 err=0
I/rmt_storage(  275): rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1 About to block rmt_storage client thread (th_id: -1229455232) wakelock released: 1, error no: 22
I/rmt_storage(  275): 
,I/rmt_storage(  275): rmt_storage_disconnect_cb: clnt_h=0x0x5 conn_h=0x0xb6b01090
,I/WifiStateMachine(  875): REQUEST_POWER_SAVE_ON
,E/WifiStateMachine(  875): CAPTIVE_PORTAL_EVENT_AUTHENTICATED
,I/art     (  875): Explicit concurrent mark sweep GC freed 41341(2MB) AllocSpace objects, 4(259KB) LOS objects, 30% free, 36MB/52MB, paused 4.419ms total 99.312ms
,D/ConnectivityService(  875): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  875): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  875): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SHealthUpgrade(SHealthUpgradeUtil)( 7961): isShealthServiceInstalled() : HealthService is Installed.
,D/SHealthUpgrade(SHealthUpgradeUtil)( 7961): isShealthService2xInstalled() : HEALTH SERVICE is INSTALLED.
D/SHealthUpgrade(SHealthUpgradeUtil)( 7961): isShealthService2xInstalled() : HEALTH SERVICE VERSION = 2.x
,D/com.sec.android.service.health.cp.common.HttpConnectionConstants( 7961): RegionGroup for  is null
,E/ActivityManager(  875): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  875): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  875): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  875): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 8248): MountEmulatedStorage()
I/libpersona( 8248): KNOX_SDCARD checking this for 10012
E/Zygote  ( 8248): v2
I/libpersona( 8248): KNOX_SDCARD not a persona
,I/ActivityManager(  875): Start proc com.google.android.gms.wearable for service com.google.android.gms/.wearable.service.WearableService: pid=8248 uid=10012 gids={50012, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 3007} abi=armeabi-v7a
,I/SELinux ( 8248): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 8248): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 8248): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,I/MusicLeanback( 7539): Conditions not met for autocaching.
I/MusicLeanback( 7539): Stop autocaching.
,D/GCM     ( 1652): Connected
,D/ConnectivityService(  875): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  875): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  875): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  875): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/TimaKeyStoreProvider( 8248): TimaSignature is unavailable
,D/ActivityThread( 8248): Added TimaKeyStore provider
,D/ConnectivityService(  875): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/GCM     ( 1652): Message class com.google.f.a.a.p
,D/ConnectivityService(  875): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  875): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ResourcesManager( 7539): creating new AssetManager and set to /data/app/com.google.android.gms-1/base.apk
,D/ResourcesManager( 8248): creating new AssetManager and set to /data/app/com.google.android.gms-1/base.apk
,W/ResourcesManager( 8248): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 8248): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,W/ResourcesManager( 7539): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,W/ResourcesManager( 7539): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,I/GHttpClientFactory( 7539): Using the GMSCore's GoogleHttpClient
,I/art     ( 1652): Explicit concurrent mark sweep GC freed 31633(1909KB) AllocSpace objects, 22(1782KB) LOS objects, 39% free, 17MB/29MB, paused 508us total 43.909ms
,I/MultiDex( 8248): VM with version 2.1.0 has multidex support
,I/MultiDex( 8248): install
,I/MultiDex( 8248): VM has multidex support, MultiDex support library is disabled.
,D/BluetoothManager( 7961): getConnectedDevices
D/BluetoothManager( 7961): getConnectedDevices
D/BluetoothManager( 7961): getConnectedDevices
D/BluetoothManager( 7961): getConnectedDevices
,D/BluetoothManager( 7961): getConnectedDevices
,D/BluetoothManager( 7961): getConnectedDevices
,E/DatabaseUtils(  875): Writing exception to parcel
E/DatabaseUtils(  875): java.lang.NullPointerException: key == null
E/DatabaseUtils(  875): 	at android.util.LruCache.get(LruCache.java:112)
E/DatabaseUtils(  875): 	at com.android.providers.settings.SettingsProvider.lookupValue(SettingsProvider.java:982)
E/DatabaseUtils(  875): 	at com.android.providers.settings.SettingsProvider.call(SettingsProvider.java:822)
E/DatabaseUtils(  875): 	at android.content.ContentProvider$Transport.call(ContentProvider.java:370)
E/DatabaseUtils(  875): 	at android.content.ContentProviderNative.onTransact(ContentProviderNative.java:282)
E/DatabaseUtils(  875): 	at android.os.Binder.execTransact(Binder.java:446)
,V/BitmapFactory( 7961): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi/s_health_widget_engraft_pedometer_mask.qmg
V/JNIHelp ( 8248): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
,D/AdaptiveEventManager( 1169): removeAdaptiveEvent() requestClass = com.sec.android.app.shealth.walkingmate.service.WalkingMateDayStepService
D/AdaptiveEventManager( 1169): M updateContainers()
D/AdaptiveEventContainerSmall( 1169): C updatePedoContainer()
D/AdaptiveEventContainerSmall( 1169): handlePedoUpdate()
D/AdaptiveEventContainerSmall( 1169): pedoEvent == null
,V/BitmapFactory( 7961): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi/s_health_widget_engraft_pedometer_icon.qmg
,V/BitmapFactory( 7961): DecodeImagePath(decodeResourceStream3) : res/drawable-xxxhdpi/s_health_widget_mask.qmg
,V/BitmapFactory( 7961): DecodeImagePath(decodeResourceStream3) : res/drawable-xxxhdpi/s_health_widget_pedometer_icon_02.qmg
,E/ActivityThread( 7539): Service com.google.android.music.download.TrackDownloadQueueService has leaked ServiceConnection com.google.android.gms.http.GoogleURLConnectionFactory$1@186ce7b0 that was originally bound here
E/ActivityThread( 7539): android.app.ServiceConnectionLeaked: Service com.google.android.music.download.TrackDownloadQueueService has leaked ServiceConnection com.google.android.gms.http.GoogleURLConnectionFactory$1@186ce7b0 that was originally bound here
E/ActivityThread( 7539): 	at android.app.LoadedApk$ServiceDispatcher.<init>(LoadedApk.java:1134)
E/ActivityThread( 7539): 	at android.app.LoadedApk.getServiceDispatcher(LoadedApk.java:1028)
E/ActivityThread( 7539): 	at android.app.ContextImpl.bindServiceCommon(ContextImpl.java:2085)
E/ActivityThread( 7539): 	at android.app.ContextImpl.bindService(ContextImpl.java:2068)
E/ActivityThread( 7539): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:559)
E/ActivityThread( 7539): 	at com.google.android.gms.http.GoogleURLConnectionFactory.<init>(Unknown Source)
E/ActivityThread( 7539): 	at com.google.android.gms.http.GoogleHttpClient.<init>(Unknown Source)
E/ActivityThread( 7539): 	at com.google.android.gms.http.GoogleHttpClient.<init>(Unknown Source)
E/ActivityThread( 7539): 	at com.google.android.gms.http.GoogleHttpClient.<init>(Unknown Source)
E/ActivityThread( 7539): 	at com.google.android.music.GoogleHttpClientFactory.createGoogleHttpClient(GoogleHttpClientFactory.java:81)
E/ActivityThread( 7539): 	at com.google.android.music.cloudclient.MusicRequest.createHttpClient(MusicRequest.java:110)
E/ActivityThread( 7539): 	at com.google.android.music.cloudclient.MusicRequest.getSharedHttpClient(MusicRequest.java:100)
E/ActivityThread( 7539): 	at com.google.android.music.download.BaseDownloadQueueManager.<init>(BaseDownloadQueueManager.java:110)
E/ActivityThread( 7539): 	at com.google.android.music.download.TrackDownloadQueueManager.<init>(TrackDownloadQueueManager.java:10)
E/ActivityThread( 7539): 	at com.google.android.music.download.TrackDownloadQueueService.onCreate(TrackDownloadQueueService.java:25)
E/ActivityThread( 7539): 	at android.app.ActivityThread.handleCreateService(ActivityThread.java:3100)
E/ActivityThread( 7539): 	at android.app.ActivityThread.access$1900(ActivityThread.java:172)
E/ActivityThread( 7539): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1505)
E/ActivityThread( 7539): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/ActivityThread( 7539): 	at android.os.Looper.loop(Looper.java:145)
E/ActivityThread( 7539): 	at android.app.ActivityThread.main(ActivityThread.java:5832)
E/ActivityThread( 7539): 	at java.lang.reflect.Method.invoke(Native Method)
E/ActivityThread( 7539): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/ActivityThread( 7539): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
E/ActivityThread( 7539): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
,D/BluetoothManager( 7961): getConnectedDevices
,D/BluetoothManager( 7961): getConnectedDevices
,D/BluetoothManager( 7961): getConnectedDevices
,W/ActivityThread( 8248): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,W/System  ( 8248): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@35941ef9: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
,I/ProviderInstaller( 8248): Installed default security provider GmsCore_OpenSSL
,D/GCM     ( 1652): GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
,D/AuthorizationBluetoothService( 1652): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,V/GmsCoreStatsServiceLauncher( 2474): Received broadcast intent Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.common.stats.GmsCoreStatsServiceLauncher }
,D/WearableService( 8248): callingUid 10012, callindPid: 8248
,D/LocationInitializer( 2474): Restart initialization of location
,D/WearableClient( 7539): WearableClientImpl.onPostInitHandler: done
,E/MDM     ( 2192): [241] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
,D/WearableClient( 7539): WearableClientImpl.onPostInitHandler: done
,D/WearableClient( 7539): WearableClientImpl.onPostInitHandler: done
,D/WearableClient( 7539): WearableClientImpl.onPostInitHandler: done
,E/GmsUtils( 7539): Failed to connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
,E/GmsUtils( 7539): Failed to connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
,I/ActivityManager(  875): Killing 5042:com.android.defcontainer/u0a5 (adj 15): bgCount ##41
,W/libprocessgroup(  875): failed to open /acct/uid_10005/pid_5042/cgroup.procs: No such file or directory
,D/ConnectivityService(  875): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/CalendarProvider2( 8174): Sending notification intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://com.android.calendar }
,I/WifiStateMachine(  875): CMD_RSSI_POLL : calculateWifiScore in!
,I/WifiStateMachine(  875): CMD_RSSI_POLL : calculateWifiScore out!
,I/WifiStateMachine(  875): CMD_RSSI_POLL : out!
,D/ConnectivityService(  875): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/ActivityManager(  875): Killing 5880:com.sec.android.gallery3d/u0a48 (adj 15): bgCount ##41
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1169): value : false
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
,D/PowerManagerService(  875): [api] [s] userActivity : event: 0 flags: 0 (uid: 1000 pid: 875) eventTime = 106063
,W/libprocessgroup(  875): failed to open /acct/uid_10048/pid_5880/cgroup.procs: No such file or directory
,D/PowerManagerService(  875): [s] UserActivityState : 2 -> 1
,D/PowerManagerService(  875): [api] release WakeLock flags=0x2000000a tag=WindowManager uid=1000 pid=875 (0x0)
D/PowerManagerService(  875): [api] applyWakeLockFlagsOnReleaseLocked : userActivityNoUpdateLocked is called : SCREEN_BRIGHT_WAKE_LOCK        'WindowManager' ON_AFTER_RELEASE (uid=1000, pid=875, ws=WorkSource{10059}) (elapsedTime=3474)
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
D/LockPatternUtilsCache( 1169): value : false
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
,I/GAV4    ( 7751): Thread[GAThread,5,main]: No campaign data found.
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
,E/SMD     (  287): DCD ON
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
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
,I/SurfaceFlinger(  249): id=16 Removed Toast (8/8)
,I/SurfaceFlinger(  249): id=16 Removed Toast (-2/8)
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1169): value : false
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1169): value : false
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
,I/PCWCLIENTTRACE_SYSTEMReceiver( 7522): mConnectivityHandler : connected,
,D/ConnectivityService(  875): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,W/PCWCLIENTTRACE_AccountUtil( 7522): [hasSamungAccount] - No Samsung Account
,I/CSTORAGE( 7522): ================================================
I/CSTORAGE( 7522):  CSTORAGE_SKM_LIB, v1.0.22, MSM8974|MSM8x26|MSM8x10
I/CSTORAGE( 7522): ================================================
I/PCWCLIENTTRACE_SecurePreferencesJNI( 7522): [GetString-S]
E/art     ( 7522): No implementation found for java.lang.String com.sec.pcw.device.util.SecurePreferencesJNI.getString() (tried Java_com_sec_pcw_device_util_SecurePreferencesJNI_getString and Java_com_sec_pcw_device_util_SecurePreferencesJNI_getString__)
W/PCWCLIENTTRACE_SecurePreferencesJNI( 7522): GetString : secure API is not supported!! No implementation found for java.lang.String com.sec.pcw.device.util.SecurePreferencesJNI.getString() (tried Java_com_sec_pcw_device_util_SecurePreferencesJNI_getString and Java_com_sec_pcw_device_util_SecurePreferencesJNI_getString__)
I/PCWCLIENTTRACE_SecurePreferencesJNI( 7522): [GetString-E]
,I/PCWCLIENTTRACE_PushUtil( 7522): SPPPushClient is installed : true
I/PCWCLIENTTRACE_PushUtil( 7522): sales region : global
I/PCWCLIENTTRACE_PushUtil( 7522): getPushTypeList : [SPP, GCM]
,E/PCWCLIENTTRACE_PCWHandler( 7522): [ensureRegistration] - No Samsung account
,I/Atfwd_Sendcmd(  349): AtCmdFwd service not ready - Exhausted retry attempts - :6
,I/Atfwd_Daemon(  349): result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,D/SSRM:m  (  875): SIOP:: AP = 420, PST = 438, CUR = 300
,I/dhcpcd  ( 7623): wlan0: sending IPv6 Router Solicitation
,I/GAV3    ( 7961): Thread[GAThread,5,main]: No campaign data found.
,I/WifiStateMachine(  875): CMD_RSSI_POLL : calculateWifiScore in!
,I/WifiStateMachine(  875): CMD_RSSI_POLL : calculateWifiScore out!
I/WifiStateMachine(  875): CMD_RSSI_POLL : out!
,E/SMD     (  287): DCD ON
,D/StatusBar.NetworkController( 1169): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02012b/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020464/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
D/StatusBar.NetworkController( 1169): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1169): applyOpen
,D/StatusBar.NetworkController( 1169): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1169): applyOpen
D/StatusBar.NetworkController( 1169): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1169): applyOpen
D/StatusBar.NetworkController( 1169): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1169): applyOpen
,I/ActivityManager(  875): Killing 7208:com.sec.android.widgetapp.digitalclock/u0a94 (adj 15): bgCount ##41
,W/libprocessgroup(  875): failed to open /acct/uid_10094/pid_7208/cgroup.procs: No such file or directory
,D/StatusBar.NetworkController( 1169): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02012b/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020468/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
,D/StatusBar.NetworkController( 1169): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1169): applyOpen
,D/StatusBar.NetworkController( 1169): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1169): applyOpen
D/StatusBar.NetworkController( 1169): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1169): applyOpen
D/StatusBar.NetworkController( 1169): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1169): applyOpen
,I/WifiStateMachine(  875): CMD_RSSI_POLL : calculateWifiScore in!
,I/WifiStateMachine(  875): CMD_RSSI_POLL : calculateWifiScore out!
,I/WifiStateMachine(  875): CMD_RSSI_POLL : out!
,W/ContextImpl(  875): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  287): DCD ON
,I/dhcpcd  ( 7623): wlan0: sending IPv6 Router Solicitation
I/dhcpcd  ( 7623): wlan0: no IPv6 Routers available
,D/PreloadUpdateManagerStateMachine( 7079): execute::IDLE:EXECUTE
,D/PreloadUpdateManagerStateMachine( 7079): exit::IDLE
D/PreloadUpdateManagerStateMachine( 7079): entry::CHECK_TIMEOUT_FOR_UPDATE
,D/hcjo    ( 7079): AutoUpdateTriggerManager:IDLE:notifyNextTime
D/PreloadUpdateManagerStateMachine( 7079): execute::CHECK_TIMEOUT_FOR_UPDATE:NO_TIMED_OUT
,D/PreloadUpdateManagerStateMachine( 7079): exit::CHECK_TIMEOUT_FOR_UPDATE
,D/PreloadUpdateManagerStateMachine( 7079): entry::IDLE
,D/StatusBar.NetworkController( 1169): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02012b/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020471/com.android.systemui:drawable/stat_sys_signal_out mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
D/StatusBar.NetworkController( 1169): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1169): applyOpen
,D/StatusBar.NetworkController( 1169): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1169): applyOpen
D/StatusBar.NetworkController( 1169): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1169): applyOpen
D/StatusBar.NetworkController( 1169): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1169): applyOpen
,I/ServiceManager(  349): Waiting for service AtCmdFwd...
,D/PreloadUpdateManagerStateMachine( 7079): execute::IDLE:EXECUTE
D/PreloadUpdateManagerStateMachine( 7079): exit::IDLE
,D/PreloadUpdateManagerStateMachine( 7079): entry::CHECK_TIMEOUT_FOR_UPDATE
,D/hcjo    ( 7079): AutoUpdateTriggerManager:IDLE:notifyNextTime
,D/PreloadUpdateManagerStateMachine( 7079): execute::CHECK_TIMEOUT_FOR_UPDATE:NO_TIMED_OUT
,D/PreloadUpdateManagerStateMachine( 7079): exit::CHECK_TIMEOUT_FOR_UPDATE
,D/PreloadUpdateManagerStateMachine( 7079): entry::IDLE
,D/FactoryTest( 6354): Not factory mode
D/FactoryTest( 6354): Not factory mode. isFactoryMode() returend false
,D/MTPRx   ( 6354): DRIVER_TIME_OUT 60s lapsed
D/MTPRx   ( 6354): still no open session command from host, so toast
,W/ContextImpl( 6354): Calling a method in the system process without a qualified user: android.app.ContextImpl.startActivity:1526 android.content.ContextWrapper.startActivity:337 android.content.ContextWrapper.startActivity:337 com.samsung.android.MtpApplication.MtpReceiver$3.handleMessage:713 android.os.Handler.dispatchMessage:102 
,W/ContextImpl( 6354): Calling a method in the system process without a qualified user: android.app.ContextImpl.startActivity:1538 android.app.ContextImpl.startActivity:1527 android.content.ContextWrapper.startActivity:337 android.content.ContextWrapper.startActivity:337 com.samsung.android.MtpApplication.MtpReceiver$3.handleMessage:713 
,I/Timeline( 6354): Timeline: Activity_launch_request id:com.android.settings time:113513
,E/PersonaManagerService(  875): inState():  stateMachine is null !!
,V/ApplicationPolicy(  875): isApplicationStateBlocked userId 0 pkgname com.android.settings
,I/ActivityManager(  875): START u0 {flg=0x10000000 cmp=com.android.settings/.SettingsReceiverActivity} from uid 1000 on display 0
,D/CustomFrequencyManagerService(  875): acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1958400  uid : 1000  pid : 875  pkgName : ACTIVITY_RESUME_BOOSTER@6
,W/ActivityManager(  875): mDVFSHelper.acquire()
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
,E/MTPRx   ( 6354): started activity for popup
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
,I/SQLiteSecureOpenHelper( 3558): getWritableDatabase(pwd)
I/SQLiteSecureOpenHelper( 3558): getDatabaseLocked(b,b,pwd)...
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
,D/ConnectivityService(  875): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/StatusBar.NetworkController( 1169): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02012b/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020466/com.android.systemui:drawable/stat_sys_signal_inout mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
D/StatusBar.NetworkController( 1169): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1169): applyOpen
,D/StatusBar.NetworkController( 1169): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1169): applyOpen
D/StatusBar.NetworkController( 1169): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1169): applyOpen
D/StatusBar.NetworkController( 1169): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1169): applyOpen
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
,D/ResourcesManager( 6354): creating new AssetManager and set to /system/priv-app/SecSettings/SecSettings.apk
,W/ResourcesManager( 6354): Asset path '/system/framework/sec_platform_library.jar' does not exist or contains no resources.
,W/ResourcesManager( 6354): Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
W/ResourcesManager( 6354): Asset path '/system/framework/secvisualeffect.jar' does not exist or contains no resources.
W/ResourcesManager( 6354): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 6354): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,W/ResourcesManager( 6354): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 6354): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,E/SettingsReceiverActivity( 6354): PREF_DONT_ASK_AGAIN : true
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
,E/ActivityManager(  875): Invalid thumbnail dimensions: 576x576
,D/InputMethodManagerService(  875): windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,W/InputMethodManagerService(  875): Window already focused, ignoring focus gain of: com.android.internal.view.IInputMethodClient$Stub$Proxy@32da5be1 attribute=null, token = android.os.BinderProxy@9e243d8
,I/SQLiteSecureOpenHelper( 3558): getWritableDatabase(pwd)
I/SQLiteSecureOpenHelper( 3558): getDatabaseLocked(b,b,pwd)...
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
,V/BitmapFactory( 6354): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_015.png
,V/BitmapFactory( 6354): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_000.png
,V/BitmapFactory( 6354): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_015.png
,V/BitmapFactory( 6354): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_000.png
,V/BitmapFactory( 6354): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_000.png
,V/BitmapFactory( 6354): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_001.png
,V/BitmapFactory( 6354): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_002.png
,V/BitmapFactory( 6354): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_003.png
,V/BitmapFactory( 6354): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_004.png
,V/BitmapFactory( 6354): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_005.png
,V/BitmapFactory( 6354): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_006.png
,V/BitmapFactory( 6354): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_007.png
,V/BitmapFactory( 6354): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_008.png
,V/BitmapFactory( 6354): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_010.png
,V/BitmapFactory( 6354): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_011.png
,V/BitmapFactory( 6354): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_012.png
,V/BitmapFactory( 6354): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_013.png
,V/BitmapFactory( 6354): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_014.png
,V/BitmapFactory( 6354): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_015.png
,V/BitmapFactory( 6354): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_000.png
,V/BitmapFactory( 6354): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_001.png
,V/BitmapFactory( 6354): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_002.png
,V/BitmapFactory( 6354): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_003.png
,V/BitmapFactory( 6354): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_004.png
,V/BitmapFactory( 6354): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_005.png
,V/BitmapFactory( 6354): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_006.png
,V/BitmapFactory( 6354): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_007.png
,V/BitmapFactory( 6354): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_008.png
,V/BitmapFactory( 6354): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_010.png
,V/BitmapFactory( 6354): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_011.png
,V/BitmapFactory( 6354): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_012.png
,V/BitmapFactory( 6354): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_013.png
,V/BitmapFactory( 6354): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_014.png
,V/BitmapFactory( 6354): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_015.png
,D/SettingsReceiverActivity( 6354): dev.kiessupport is : TRUE
,D/Activity( 6354): performCreate Call secproduct feature valuefalse
,D/Activity( 6354): performCreate Call debug elastic valuetrue
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
,D/ActivityManager(  875): post active user change for 0
D/KnoxTimeoutHandler(  875): postActiveUserChange for user 0
,D/KnoxTimeoutHandler(  875): handleActiveUserChange for user 0
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1169): value : false
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
,I/Timeline( 7393): Timeline: Activity_idle id: android.os.BinderProxy@2378baa9 time:113775
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
,I/ServiceManager(  349): Waiting for service AtCmdFwd...
,D/ConnectivityService(  875): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/StatusBar.NetworkController( 1169): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02012b/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020464/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
D/StatusBar.NetworkController( 1169): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1169): applyOpen
,D/StatusBar.NetworkController( 1169): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1169): applyOpen
D/StatusBar.NetworkController( 1169): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1169): applyOpen
D/StatusBar.NetworkController( 1169): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1169): applyOpen
,I/ServiceManager(  349): Waiting for service AtCmdFwd...
,I/WifiStateMachine(  875): CMD_RSSI_POLL : calculateWifiScore in!
,I/WifiStateMachine(  875): CMD_RSSI_POLL : calculateWifiScore out!
I/WifiStateMachine(  875): CMD_RSSI_POLL : out!
,E/SMD     (  287): DCD ON
,I/ServiceManager(  349): Waiting for service AtCmdFwd...
,D/ConnectivityService(  875): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/CustomFrequencyManagerService(  875): releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1958400  uid : 1000  pid : 875  tag : ACTIVITY_RESUME_BOOSTER@6
,W/ActivityManager(  875): mDVFSHelper.release()
D/CustomFrequencyManagerService(  875): acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1958400  uid : 1000  pid : 875  pkgName : ACTIVITY_RESUME_BOOSTER@10
,I/ServiceManager(  349): Waiting for service AtCmdFwd...
,D/CustomFrequencyManagerService(  875): releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1958400  uid : 1000  pid : 875  tag : ACTIVITY_RESUME_BOOSTER@10
,I/ActivityManager(  875): Waited long enough for: ServiceRecord{443766c u0 com.samsung.android.app.galaxyfinder/.tag.LocationTagReadyService}
,W/Atfwd_Sendcmd(  349): AtCmdFwd service not published, waiting... retryCnt : 1
,D/SSRM:m  (  875): SIOP:: AP = 400, PST = 430, CUR = 300
,I/WifiStateMachine(  875): CMD_RSSI_POLL : calculateWifiScore in!
,I/WifiStateMachine(  875): CMD_RSSI_POLL : calculateWifiScore out!
,I/WifiStateMachine(  875): CMD_RSSI_POLL : out!
,E/SMD     (  287): DCD ON
,D/StatusBar.NetworkController( 1169): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02012b/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020466/com.android.systemui:drawable/stat_sys_signal_inout mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
,D/StatusBar.NetworkController( 1169): refreshSignalCluster - setNWBoosterIndicators(false),
,D/StatusBar.NetworkController( 1169): applyOpen,
,D/StatusBar.NetworkController( 1169): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1169): applyOpen
,D/StatusBar.NetworkController( 1169): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1169): applyOpen
,D/StatusBar.NetworkController( 1169): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1169): applyOpen
,V/AlarmManager(  875): waitForAlarm result :4
,D/BatteryService(  875): level:100, scale:100, status:5, health:2, present:true, voltage: 4386, temperature: 299, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  875): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
D/BatteryService(  875): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  875):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  875): Plugged
I/MotionRecognitionService(  875): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1169): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1169): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1169):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3249): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3249): Disconnected process message: 10
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2,
D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/StatusBar.NetworkController( 1169): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02012b/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020464/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
,D/StatusBar.NetworkController( 1169): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1169): applyOpen
,D/StatusBar.NetworkController( 1169): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1169): applyOpen
D/StatusBar.NetworkController( 1169): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1169): applyOpen
D/StatusBar.NetworkController( 1169): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1169): applyOpen
,V/GLSActivity( 1652): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1652): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
,I/GLSUser ( 1652): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1652): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1652): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1652): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/Finsky  ( 6561): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,D/Finsky  ( 6561): [1] 5.onFinished: Installation state replication failed.
,D/Finsky  ( 6561): [1] 5.onFinished: Scheduling replication attempt 3.
,I/WifiStateMachine(  875): CMD_RSSI_POLL : calculateWifiScore in!
,I/WifiStateMachine(  875): CMD_RSSI_POLL : calculateWifiScore out!
I/WifiStateMachine(  875): CMD_RSSI_POLL : out!
,E/SMD     (  287): DCD ON
,V/AlarmManager(  875): waitForAlarm result :4
,D/ConnectivityService(  875): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  875): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  875): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  875): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  875): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/GLSUser ( 1652): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,I/GLSUser ( 1652): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1652): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1652): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1652): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ResourcesManager( 1652): creating new AssetManager and set to /system/app/PlusOne/PlusOne.apk
,V/BitmapFactory( 1652): DecodeImagePath(decodeResourceStream3) : res/mipmap-xxhdpi-v4/quantum_logo_google_plus_color_44in48.png
,D/ConnectivityService(  875): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,V/BitmapFactory( 1652): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  875): uri = 14 selection = getSealedState
,D/SecContentProvider2(  875): mCursor = null
D/SecContentProvider2(  875): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  875): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy(  875): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,E/HttpOperation( 5312): [kfu{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
E/HttpOperation( 5312): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 5312): 	at kfv.a(PG:65)
E/HttpOperation( 5312): 	at kff.u(PG:385)
E/HttpOperation( 5312): 	at kfb.a(PG:29)
E/HttpOperation( 5312): 	at kff.l(PG:132)
E/HttpOperation( 5312): 	at dsf.a(PG:807)
E/HttpOperation( 5312): 	at fhk.a(PG:1126)
E/HttpOperation( 5312): 	at fhk.a(PG:908)
E/HttpOperation( 5312): 	at fhk.onPerformSync(PG:636)
E/HttpOperation( 5312): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/HttpOperation( 5312): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/HttpOperation( 5312): 	at ihi.a(PG:22)
E/HttpOperation( 5312): 	at kft.a(PG:91)
E/HttpOperation( 5312): 	at kfv.a(PG:62)
E/HttpOperation( 5312): 	... 8 more
E/HttpOperation( 5312): Caused by: gdi: User intervention required. Notification has been pushed.
E/HttpOperation( 5312): 	at gde.c(Unknown Source)
E/HttpOperation( 5312): 	at gde.b(Unknown Source)
E/HttpOperation( 5312): 	at ihi.a(PG:19)
E/HttpOperation( 5312): 	... 10 more
,D/StatusBar( 1169): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,I/PhoneStatusBar( 1169): Icon Only
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
D/PanelView( 1169): There is/are notification(s) 
,D/PanelView( 1169): There is/are notification(s) 
,I/GLSUser ( 1652): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,I/GLSUser ( 1652): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1652): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1652): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1652): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/BitmapFactory( 1652): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  875): uri = 14 selection = getSealedState
D/SecContentProvider2(  875): mCursor = null
,D/SecContentProvider2(  875): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  875): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy(  875): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,E/HttpOperation( 5312): [getaccountstatus] Unexpected exception
E/HttpOperation( 5312): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 5312): 	at kfv.a(PG:65)
E/HttpOperation( 5312): 	at kff.u(PG:385)
E/HttpOperation( 5312): 	at kfb.a(PG:29)
E/HttpOperation( 5312): 	at ixd.a(PG:248)
E/HttpOperation( 5312): 	at ixd.b(PG:206)
E/HttpOperation( 5312): 	at ixd.a(PG:175)
E/HttpOperation( 5312): 	at fig.a(PG:78)
E/HttpOperation( 5312): 	at lex.a(PG:85)
E/HttpOperation( 5312): 	at lex.b(PG:132)
E/HttpOperation( 5312): 	at fhk.a(PG:1146)
E/HttpOperation( 5312): 	at fhk.a(PG:908)
E/HttpOperation( 5312): 	at fhk.onPerformSync(PG:636)
E/HttpOperation( 5312): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/HttpOperation( 5312): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/HttpOperation( 5312): 	at ihi.a(PG:22)
E/HttpOperation( 5312): 	at kft.a(PG:91)
E/HttpOperation( 5312): 	at kfv.a(PG:62)
E/HttpOperation( 5312): 	... 12 more
E/HttpOperation( 5312): Caused by: gdi: User intervention required. Notification has been pushed.
E/HttpOperation( 5312): 	at gde.c(Unknown Source)
E/HttpOperation( 5312): 	at gde.b(Unknown Source)
E/HttpOperation( 5312): 	at ihi.a(PG:19)
E/HttpOperation( 5312): 	... 14 more
,D/StatusBar( 1169): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
E/EsSyncAdapterService( 5312): Sync failure
E/EsSyncAdapterService( 5312): java.io.IOException: Rpc failed
E/EsSyncAdapterService( 5312): 	at ixd.a(PG:348)
E/EsSyncAdapterService( 5312): 	at ixd.a(PG:248)
E/EsSyncAdapterService( 5312): 	at ixd.b(PG:206)
E/EsSyncAdapterService( 5312): 	at ixd.a(PG:175)
E/EsSyncAdapterService( 5312): 	at fig.a(PG:78)
E/EsSyncAdapterService( 5312): 	at lex.a(PG:85)
E/EsSyncAdapterService( 5312): 	at lex.b(PG:132)
E/EsSyncAdapterService( 5312): 	at fhk.a(PG:1146)
E/EsSyncAdapterService( 5312): 	at fhk.a(PG:908)
E/EsSyncAdapterService( 5312): 	at fhk.onPerformSync(PG:636)
E/EsSyncAdapterService( 5312): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/EsSyncAdapterService( 5312): Caused by: java.io.IOException: Cannot obtain authentication token
E/EsSyncAdapterService( 5312): 	at kfv.a(PG:65)
E/EsSyncAdapterService( 5312): 	at kff.u(PG:385)
E/EsSyncAdapterService( 5312): 	at kfb.a(PG:29)
E/EsSyncAdapterService( 5312): 	... 10 more
E/EsSyncAdapterService( 5312): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/EsSyncAdapterService( 5312): 	at ihi.a(PG:22)
E/EsSyncAdapterService( 5312): 	at kft.a(PG:91)
E/EsSyncAdapterService( 5312): 	at kfv.a(PG:62)
E/EsSyncAdapterService( 5312): 	... 12 more
E/EsSyncAdapterService( 5312): Caused by: gdi: User intervention required. Notification has been pushed.
E/EsSyncAdapterService( 5312): 	at gde.c(Unknown Source)
E/EsSyncAdapterService( 5312): 	at gde.b(Unknown Source)
E/EsSyncAdapterService( 5312): 	at ihi.a(PG:19)
E/EsSyncAdapterService( 5312): 	... 14 more
,D/ConnectivityService(  875): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/PhoneStatusBar( 1169): Icon Only
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
D/PanelView( 1169): There is/are notification(s) 
D/PanelView( 1169): There is/are notification(s) 
,D/ConnectivityService(  875): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/GLSUser ( 1652): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
I/GLSUser ( 1652): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1652): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1652): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1652): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/BitmapFactory( 1652): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  875): uri = 14 selection = getSealedState
,D/SecContentProvider2(  875): mCursor = null
,D/SecContentProvider2(  875): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  875): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
V/ApplicationPolicy(  875): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,E/HttpOperation( 5312): [kfu{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
E/HttpOperation( 5312): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 5312): 	at kfv.a(PG:65)
E/HttpOperation( 5312): 	at kff.u(PG:385)
E/HttpOperation( 5312): 	at kfb.a(PG:29)
E/HttpOperation( 5312): 	at kff.l(PG:132)
E/HttpOperation( 5312): 	at dsf.a(PG:807)
E/HttpOperation( 5312): 	at fhk.a(PG:1126)
E/HttpOperation( 5312): 	at fhk.a(PG:908)
E/HttpOperation( 5312): 	at fhk.onPerformSync(PG:636)
E/HttpOperation( 5312): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/HttpOperation( 5312): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/HttpOperation( 5312): 	at ihi.a(PG:22)
E/HttpOperation( 5312): 	at kft.a(PG:91)
E/HttpOperation( 5312): 	at kfv.a(PG:62)
E/HttpOperation( 5312): 	... 8 more
E/HttpOperation( 5312): Caused by: gdi: User intervention required. Notification has been pushed.
E/HttpOperation( 5312): 	at gde.c(Unknown Source)
E/HttpOperation( 5312): 	at gde.b(Unknown Source)
E/HttpOperation( 5312): 	at ihi.a(PG:19)
E/HttpOperation( 5312): 	... 10 more
,D/StatusBar( 1169): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,I/PhoneStatusBar( 1169): Icon Only
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
,D/PanelView( 1169): There is/are notification(s) 
,D/PanelView( 1169): There is/are notification(s) 
,I/ServiceManager(  349): Waiting for service AtCmdFwd...
,I/GLSUser ( 1652): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,I/GLSUser ( 1652): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1652): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1652): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1652): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/BitmapFactory( 1652): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  875): uri = 14 selection = getSealedState
D/SecContentProvider2(  875): mCursor = null
,D/SecContentProvider2(  875): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  875): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
V/ApplicationPolicy(  875): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/StatusBar( 1169): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,I/PhoneStatusBar( 1169): Icon Only
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
D/PanelView( 1169): There is/are notification(s) 
,D/PanelView( 1169): There is/are notification(s) 
E/HttpOperation( 5312): [getmobileexperiments] Unexpected exception
E/HttpOperation( 5312): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 5312): 	at kfv.a(PG:65)
E/HttpOperation( 5312): 	at kff.u(PG:385)
E/HttpOperation( 5312): 	at kfb.a(PG:29)
E/HttpOperation( 5312): 	at kff.l(PG:132)
E/HttpOperation( 5312): 	at ieo.a(PG:43)
E/HttpOperation( 5312): 	at iep.a(PG:93)
E/HttpOperation( 5312): 	at fhn.a(PG:59)
E/HttpOperation( 5312): 	at lex.a(PG:85)
E/HttpOperation( 5312): 	at lex.b(PG:132)
E/HttpOperation( 5312): 	at fhk.a(PG:1146)
E/HttpOperation( 5312): 	at fhk.a(PG:908)
E/HttpOperation( 5312): 	at fhk.onPerformSync(PG:636)
E/HttpOperation( 5312): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/HttpOperation( 5312): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/HttpOperation( 5312): 	at ihi.a(PG:22)
E/HttpOperation( 5312): 	at kft.a(PG:91)
E/HttpOperation( 5312): 	at kfv.a(PG:62)
E/HttpOperation( 5312): 	... 12 more
E/HttpOperation( 5312): Caused by: gdi: User intervention required. Notification has been pushed.
E/HttpOperation( 5312): 	at gde.c(Unknown Source)
E/HttpOperation( 5312): 	at gde.b(Unknown Source)
E/HttpOperation( 5312): 	at ihi.a(PG:19)
E/HttpOperation( 5312): 	... 14 more
E/ExperimentLoader( 5312): [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 5312): java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 5312): 	at kfv.a(PG:65)
E/ExperimentLoader( 5312): 	at kff.u(PG:385)
E/ExperimentLoader( 5312): 	at kfb.a(PG:29)
E/ExperimentLoader( 5312): 	at kff.l(PG:132)
E/ExperimentLoader( 5312): 	at ieo.a(PG:43)
E/ExperimentLoader( 5312): 	at iep.a(PG:93)
E/ExperimentLoader( 5312): 	at fhn.a(PG:59)
E/ExperimentLoader( 5312): 	at lex.a(PG:85)
E/ExperimentLoader( 5312): 	at lex.b(PG:132)
E/ExperimentLoader( 5312): 	at fhk.a(PG:1146)
E/ExperimentLoader( 5312): 	at fhk.a(PG:908)
E/ExperimentLoader( 5312): 	at fhk.onPerformSync(PG:636)
E/ExperimentLoader( 5312): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/ExperimentLoader( 5312): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/ExperimentLoader( 5312): 	at ihi.a(PG:22)
E/ExperimentLoader( 5312): 	at kft.a(PG:91)
E/ExperimentLoader( 5312): 	at kfv.a(PG:62)
E/ExperimentLoader( 5312): 	... 12 more
E/ExperimentLoader( 5312): Caused by: gdi: User intervention required. Notification has been pushed.
E/ExperimentLoader( 5312): 	at gde.c(Unknown Source)
E/ExperimentLoader( 5312): 	at gde.b(Unknown Source)
E/ExperimentLoader( 5312): 	at ihi.a(PG:19)
E/ExperimentLoader( 5312): 	... 14 more
,I/GLSUser ( 1652): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
I/GLSUser ( 1652): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1652): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1652): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1652): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/BitmapFactory( 1652): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  875): uri = 14 selection = getSealedState
,D/SecContentProvider2(  875): mCursor = null
D/SecContentProvider2(  875): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  875): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy(  875): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/StatusBar( 1169): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,E/HttpOperation( 5312): [getaccountstatus] Unexpected exception
E/HttpOperation( 5312): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 5312): 	at kfv.a(PG:65)
E/HttpOperation( 5312): 	at kff.u(PG:385)
E/HttpOperation( 5312): 	at kfb.a(PG:29)
E/HttpOperation( 5312): 	at ixd.a(PG:248)
E/HttpOperation( 5312): 	at ixd.b(PG:206)
E/HttpOperation( 5312): 	at ixd.a(PG:175)
E/HttpOperation( 5312): 	at fig.a(PG:78)
E/HttpOperation( 5312): 	at lex.a(PG:85)
E/HttpOperation( 5312): 	at lex.b(PG:132)
E/HttpOperation( 5312): 	at fhk.a(PG:1146)
E/HttpOperation( 5312): 	at fhk.a(PG:908)
E/HttpOperation( 5312): 	at fhk.onPerformSync(PG:636)
E/HttpOperation( 5312): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/HttpOperation( 5312): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/HttpOperation( 5312): 	at ihi.a(PG:22)
E/HttpOperation( 5312): 	at kft.a(PG:91)
E/HttpOperation( 5312): 	at kfv.a(PG:62)
E/HttpOperation( 5312): 	... 12 more
E/HttpOperation( 5312): Caused by: gdi: User intervention required. Notification has been pushed.
E/HttpOperation( 5312): 	at gde.c(Unknown Source)
E/HttpOperation( 5312): 	at gde.b(Unknown Source)
E/HttpOperation( 5312): 	at ihi.a(PG:19)
E/HttpOperation( 5312): 	... 14 more
,E/EsSyncAdapterService( 5312): Sync failure
E/EsSyncAdapterService( 5312): java.io.IOException: Rpc failed
E/EsSyncAdapterService( 5312): 	at ixd.a(PG:348)
E/EsSyncAdapterService( 5312): 	at ixd.a(PG:248)
E/EsSyncAdapterService( 5312): 	at ixd.b(PG:206)
E/EsSyncAdapterService( 5312): 	at ixd.a(PG:175)
E/EsSyncAdapterService( 5312): 	at fig.a(PG:78)
E/EsSyncAdapterService( 5312): 	at lex.a(PG:85)
E/EsSyncAdapterService( 5312): 	at lex.b(PG:132)
E/EsSyncAdapterService( 5312): 	at fhk.a(PG:1146)
E/EsSyncAdapterService( 5312): 	at fhk.a(PG:908)
E/EsSyncAdapterService( 5312): 	at fhk.onPerformSync(PG:636)
E/EsSyncAdapterService( 5312): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/EsSyncAdapterService( 5312): Caused by: java.io.IOException: Cannot obtain authentication token
E/EsSyncAdapterService( 5312): 	at kfv.a(PG:65)
E/EsSyncAdapterService( 5312): 	at kff.u(PG:385)
E/EsSyncAdapterService( 5312): 	at kfb.a(PG:29)
E/EsSyncAdapterService( 5312): 	... 10 more
E/EsSyncAdapterService( 5312): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/EsSyncAdapterService( 5312): 	at ihi.a(PG:22)
E/EsSyncAdapterService( 5312): 	at kft.a(PG:91)
E/EsSyncAdapterService( 5312): 	at kfv.a(PG:62)
E/EsSyncAdapterService( 5312): 	... 12 more
E/EsSyncAdapterService( 5312): Caused by: gdi: User intervention required. Notification has been pushed.
E/EsSyncAdapterService( 5312): 	at gde.c(Unknown Source)
E/EsSyncAdapterService( 5312): 	at gde.b(Unknown Source)
E/EsSyncAdapterService( 5312): 	at ihi.a(PG:19)
E/EsSyncAdapterService( 5312): 	... 14 more
,I/PhoneStatusBar( 1169): Icon Only
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
D/PanelView( 1169): There is/are notification(s) 
,D/PanelView( 1169): There is/are notification(s) 
,D/ConnectivityService(  875): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SyncManager(  875): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, PERIODIC, currentRunTime 92810, reason: Periodic, SyncResult: stats [ numIoExceptions: 2]
,D/ConnectivityService(  875): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  875): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SecContentProvider2(  875): uri = 11 selection = getMyKnoxAdmin
D/SecContentProvider2(  875): mCursor = null
,E/SQLiteLog( 1652): (10) POSIX Error : 11 SQLite Error : 3850
,D/StatusBar.NetworkController( 1169): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02012b/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020466/com.android.systemui:drawable/stat_sys_signal_inout mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
,D/StatusBar.NetworkController( 1169): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1169): applyOpen
,D/StatusBar.NetworkController( 1169): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1169): applyOpen
,D/StatusBar.NetworkController( 1169): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1169): applyOpen
,D/StatusBar.NetworkController( 1169): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1169): applyOpen
,I/ServiceManager(  349): Waiting for service AtCmdFwd...
,I/WifiStateMachine(  875): CMD_RSSI_POLL : calculateWifiScore in!
,I/WifiStateMachine(  875): CMD_RSSI_POLL : calculateWifiScore out!
I/WifiStateMachine(  875): CMD_RSSI_POLL : out!
,E/SMD     (  287): DCD ON
,D/StatusBar.NetworkController( 1169): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02012b/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020464/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
,D/StatusBar.NetworkController( 1169): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1169): applyOpen
,D/StatusBar.NetworkController( 1169): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1169): applyOpen
D/StatusBar.NetworkController( 1169): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1169): applyOpen
D/StatusBar.NetworkController( 1169): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1169): applyOpen
,I/ServiceManager(  349): Waiting for service AtCmdFwd...
,I/ServiceManager(  349): Waiting for service AtCmdFwd...
,I/ServiceManager(  349): Waiting for service AtCmdFwd...
,I/WifiStateMachine(  875): CMD_RSSI_POLL : calculateWifiScore in!
,I/WifiStateMachine(  875): CMD_RSSI_POLL : calculateWifiScore out!
I/WifiStateMachine(  875): CMD_RSSI_POLL : out!
,E/SMD     (  287): DCD ON
,W/Atfwd_Sendcmd(  349): AtCmdFwd service not published, waiting... retryCnt : 2
,D/SSRM:m  (  875): SIOP:: AP = 360, PST = 417, CUR = 300
,D/X       (  875): broadcastSiopLevelIntent:: currentSiopLevel = 0
,D/ConnectivityService(  875): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ContentApp( 1229):  LEVEL : 0
,E/ActivityManager(  875): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  875): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  875): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  875): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 8361): MountEmulatedStorage()
,E/Zygote  ( 8361): v2
I/libpersona( 8361): KNOX_SDCARD checking this for 10054
I/libpersona( 8361): KNOX_SDCARD not a persona
,I/SELinux ( 8361): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/ActivityManager(  875): Start proc com.sec.android.app.videoplayer for broadcast com.sec.android.app.videoplayer/.videowall.TranscodeReceiver: pid=8361 uid=10054 gids={50054, 9997, 3003, 3002, 1028, 1015, 1023} abi=armeabi-v7a
,I/SELinux ( 8361): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 8361): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 8361): TimaSignature is unavailable
,D/ActivityThread( 8361): Added TimaKeyStore provider
,D/ResourcesManager( 8361): creating new AssetManager and set to /system/priv-app/SecVideoPlayer/SecVideoPlayer.apk
,W/ResourcesManager( 8361): Asset path '/system/framework/minimode.jar' does not exist or contains no resources.
,W/ResourcesManager( 8361): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 8361): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager( 8361): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 8361): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
,E/TranscodeReceiver( 8361): onReceive : android.intent.action.CHECK_SIOP_LEVEL
,D/videowall-Global( 8361): core_num = 4
,W/linker  ( 8361): libsthmb.so has text relocations. This is wasting memory and prevents security hardening. Please fix.
,W/linker  ( 8361): libvwengine.so has text relocations. This is wasting memory and prevents security hardening. Please fix.
,D/videowall-Global( 8361): density : 3.0 width : 1080 height : 1920 Raw width : 1080 Raw height : 1920
D/videowall-Global( 8361): dsp : 1080, swkey : false, Cores : 4, Clock : 0
,D/TranscodeReceiver( 8361):  SIOP_LEVEL: 0
,I/ActivityManager(  875): Killing 7238:com.sec.android.widgetapp.dualclockdigital/u0a103 (adj 15): bgCount ##41
,W/libprocessgroup(  875): failed to open /acct/uid_10103/pid_7238/cgroup.procs: No such file or directory
,D/StatusBar.NetworkController( 1169): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02012b/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020466/com.android.systemui:drawable/stat_sys_signal_inout mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
,D/StatusBar.NetworkController( 1169): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1169): applyOpen
D/StatusBar.NetworkController( 1169): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1169): applyOpen
D/StatusBar.NetworkController( 1169): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1169): applyOpen
D/StatusBar.NetworkController( 1169): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1169): applyOpen
,D/BatteryService(  875): level:100, scale:100, status:5, health:2, present:true, voltage: 4386, temperature: 300, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
D/BatteryService(  875): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
D/BatteryService(  875): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  875):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  875): Plugged
I/MotionRecognitionService(  875): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1169): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1169): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1169):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3249): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3249): Disconnected process message: 10
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/StatusBar.NetworkController( 1169): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02012b/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020464/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth,
D/StatusBar.NetworkController( 1169): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1169): applyOpen
D/StatusBar.NetworkController( 1169): refreshSignalCluster - setNWBoosterIndicators(false),
D/StatusBar.NetworkController( 1169): applyOpen
D/StatusBar.NetworkController( 1169): refreshSignalCluster - setNWBoosterIndicators(false),
D/StatusBar.NetworkController( 1169): applyOpen
D/StatusBar.NetworkController( 1169): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1169): applyOpen
,D/PowerManagerService(  875): [s] UserActivityState : 1 -> 2
,D/DisplayPowerController(  875): getFinalBrightness : 1 -> 1
,D/PowerManagerService(  875): [s] DisplayPowerCallbacks : onStateChanged()
,D/DisplayPowerController(  875): getFinalBrightness : 1 -> 1
D/lights  (  875): lcd : 1 +
,D/lights  (  875): lcd : 1 -
,D/DisplayPowerController(  875): getFinalBrightness : 1 -> 1
,I/WifiStateMachine(  875): CMD_RSSI_POLL : calculateWifiScore in!
,I/WifiStateMachine(  875): CMD_RSSI_POLL : calculateWifiScore out!
I/WifiStateMachine(  875): CMD_RSSI_POLL : out!
,E/SMD     (  287): DCD ON
,W/ContextImpl(  875): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/WifiStateMachine(  875): CMD_RSSI_POLL : calculateWifiScore in!
,I/WifiStateMachine(  875): CMD_RSSI_POLL : calculateWifiScore out!
I/WifiStateMachine(  875): CMD_RSSI_POLL : out!
,E/SMD     (  287): DCD ON
,E/Watchdog(  875): !@Sync 4
,D/StatusBar.NetworkController( 1169): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02012b/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020466/com.android.systemui:drawable/stat_sys_signal_inout mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
,D/StatusBar.NetworkController( 1169): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1169): applyOpen
,D/StatusBar.NetworkController( 1169): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1169): applyOpen
D/StatusBar.NetworkController( 1169): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1169): applyOpen
,D/StatusBar.NetworkController( 1169): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1169): applyOpen
,D/StatusBar.NetworkController( 1169): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02012b/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020464/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
D/StatusBar.NetworkController( 1169): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1169): applyOpen
,D/StatusBar.NetworkController( 1169): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1169): applyOpen
D/StatusBar.NetworkController( 1169): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1169): applyOpen
D/StatusBar.NetworkController( 1169): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1169): applyOpen
,I/art     (  875): Explicit concurrent mark sweep GC freed 49242(2MB) AllocSpace objects, 23(3MB) LOS objects, 30% free, 36MB/52MB, paused 1.534ms total 165.692ms
,D/StatusBar.NetworkController( 1169): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02012b/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020468/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
,D/StatusBar.NetworkController( 1169): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1169): applyOpen
D/StatusBar.NetworkController( 1169): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1169): applyOpen
D/StatusBar.NetworkController( 1169): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1169): applyOpen
,D/StatusBar.NetworkController( 1169): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1169): applyOpen
,D/PowerManagerService(  875): [s] UserActivityState : 2 -> 4
I/PowerManagerService(  875): Nap time (uid 1000)...
,I/PowerManagerService(  875): !@[ps] Screen__Off(2) : 
I/PowerManagerService(  875): Going to sleep due to screen timeout (uid 1000)...
D/PowerManagerService(  875): [PWL] sb acquire: PowerManagerService.Broadcasts
D/PowerManagerService(  875): SecHardwareInterface.setBatteryADC : false
D/InputManager-JNI(  875): setDeviceInteractive: 0
,D/InputManager-JNI(  875): sysfs_write +: /sys/class/input/event2/device/enabled: 0
D/PowerManagerService(  875): handleSandman : startDream()
,E/PowerManagerService(  875): handleSandman : startDreaming, but isDreaming false
I/PowerManagerService(  875): Sleeping (uid 1000)...
D/PowerManagerService(  875): [s] UserActivityState : 4 -> 0
D/PowerManagerService(  875): [input device light] setInputDeviceLightOn is called : 0
,D/PowerManagerService(  875): [input device light] handleInputDeviceLightOff
I/SurfaceFlinger(  249): id=17 createSurf (1080x1920),2 flag=404, ColorFade
,D/InputManager-JNI(  875): sysfs_write +: /sys/class/input/event1/device/enabled: 0
,D/InputManager-JNI(  875): sysfs_write -: /sys/class/input/event2/device/enabled: 0
,D/InputManager-JNI(  875): sysfs_write -: /sys/class/input/event1/device/enabled: 0
,D/SContextService(  875): 	.unregisterCallback : 1, client=
D/SContextService(  875): unregisterCallback() : Listener = android.hardware.scontext.SContextService$Listener@2902741f, Service = Auto Rotation, used = 1
,W/CAE     (  875): unregisterCallback(ContextAwareService.java:199) - [unregi 01] Mutex is locked for AUTO_ROTATION
V/CAE     (  875): stop(ContextProvider.java:149)
,V/CAE     (  875): clear(AutoRotationRunner.java:182)
V/CAE     (  875): disable(AutoRotationRunner.java:171)
,I/CAE     (  875): sendCmdToSensorHub(SensorHubCommManager.java:144) - -78, 7, 0, 0,
D/SensorHubManager(  875): SendSensorHubData: send data = -78, 7, 0, 0
,D/Sensorhubs(  310): sendContextData: -78, 7, 0, 0
,D/CAE     (  875): getFaultDetectionResult(AutoRotationRunner.java:195) - true
,I/CAE     (  875): notifyCmdProcessResultObserver(ContextProvider.java:617) - CheckResult = 0, Cause = Success
,D/CAE     (  875): doCommendProcess(ContextAwareService.java:314) - complete notify the operation result.
,I/CAE     (  875): displayUsedCountForService(ContextAwareService.java:406) - totalCnt = 0, serviceCount = 0, subCollectionCount = 0
,D/CAE     (  875): showListenerList(ContextAwareService.java:247) - ===== Context Aware Service List =====
,W/CAE     (  875): unregisterCallback(ContextAwareService.java:234) - [unregi 02] Mutex is unlocked for AUTO_ROTATION
D/SContextService(  875): removeSContextService() : service = Auto Rotation
D/SContextService(  875): ===== SContext Service List =====
D/SContextManager(  875):   .unregisterListener : listener = com.android.internal.policy.impl.WindowOrientationListener$SContextListenerImpl@30f2741b, service=Auto Rotation
,D/KeyguardViewMediator( 1169): onScreenTurnedOff(3)
,I/KeyguardEffectViewController( 1169): *** KeyguardEffectView getInstanceIfExists ***
D/KeyguardEffectViewController( 1169): changeWallpaperByScreenOff()
D/KeyguardViewMediator( 1169): notifyScreenOffLocked
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1169): value : false
D/KeyguardViewMediator( 1169): timeout : 5000
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
,I/SQLiteSecureOpenHelper( 3558): getWritableDatabase(pwd)
I/SQLiteSecureOpenHelper( 3558): getDatabaseLocked(b,b,pwd)...
,D/DisplayPowerController(  875): ColorFade: onAnimationStart
D/DisplayPowerController(  875): getFinalBrightness : 8 -> 0
,D/KeyguardViewMediator( 1169): setting alarm to turn off keyguard, seq = 2
,D/KeyguardViewMediator( 1169): handleNotifyScreenOff
,D/DisplayPowerController(  875): getFinalBrightness : 8 -> 0
D/lights  (  875): lcd : 0 +
,D/LightsService(  875): [api] [SvcLED] setFlashing :: id = 3, color = 0, mode = 14, onMS = 0, offMS = 0,  (uid: 1000 pid: 875) 
D/LightsService(  875): [SvcLED] setSvcLedStateLocked:: SvcLEDState : 0x0 -> 0x40 | SvcLED(id=3) set On
,D/LightsService(  875): [SvcLED]  onSensorChanged::light value = 1
,D/SensorManager(  875): registerListener :: 6, TMG399X RGB Sensor, 200000, 0,  
D/BatteryService(  875): turn on LED for fully charged
,D/SensorManager(  875): unregisterListener ::   
,I/CAE     (  875): handleMessage(CaPowerManager.java:182) - AP_SLEEP
,I/CAE     (  875): updateApPowerStatus(SensorHubParserProvider.java:421) - AP_SLEEP
I/CAE     (  875): sendCmdToSensorHub(SensorHubCommManager.java:144) - -76, 13, -46, 0,
,D/SensorHubManager(  875): SendSensorHubData: send data = -76, 13, -46, 0
D/Sensorhubs(  310): sendContextData: -76, 13, -46, 0
,D/lights  (  875): lcd : 0 -
D/lights  (  875): led_pattern : 5 +
,I/CAE     (  875): sendCmdToSensorHub(SensorHubCommManager.java:144) - -63, 14, 16, 9, 44,
D/SensorHubManager(  875): SendSensorHubData: send data = -63, 14, 16, 9, 44
D/LightsService(  875): [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=3) maintains its priority right
D/lights  (  875): led_pattern : 5 -
D/Sensorhubs(  310): sendContextData: -63, 14, 16, 9, 44
,D/MotionRecognitionService(  875):   mReceiver.onReceive : ACTION_SCREEN_OFF
,I/WifiStateMachine(  875): CMD_RSSI_POLL : calculateWifiScore in!
,I/WifiStateMachine(  875): CMD_RSSI_POLL : calculateWifiScore out!
I/WifiStateMachine(  875): CMD_RSSI_POLL : out!
,E/MotionRecognitionService(  875):  handler : SCREEN_OFF end 
,D/NotificationService(  875): ACTION_SCREEN_OFF
D/LightsService(  875): [api] [SvcLED] setFlashing :: id = 4, color = ffffffff, mode = 12, onMS = 500, offMS = 2000,  (uid: 1000 pid: 875) 
D/LightsService(  875): [SvcLED] setSvcLedStateLocked:: SvcLEDState : 0x40 -> 0x42 | SvcLED(id=4) set On
,D/WifiStateMachine(  875): backgroundScan enabled=false startBackgroundScanIfNeeded:false
E/WifiStateMachine(  875): handleScreenStateChanged Exit: false
D/LightsService(  875): [SvcLED]  onSensorChanged::light value = 1
,E/WifiStateMachine(  875): setSuspendOptimizationsNative: 4 true -want true stack:setSuspendOptimizationsNative - access$16800 - processMessage - processMsg
,E/WifiStateMachine(  875): setSuspendOptimizationsNative do it 4 true stack:setSuspendOptimizationsNative - access$16800 - processMessage - processMsg
E/native  (  875): do suspend true
,D/SensorManager(  875): registerListener :: 6, TMG399X RGB Sensor, 200000, 0,  
,D/SensorManager(  875): unregisterListener ::   
D/LightsService(  875): [SvcLED]  setSvcLedLightLocked :: priority changed! SvcLED(id=3) OUT; SvcLED(id=4) IN
,D/audio_hw_primary(  293): adev_set_parameters: enter: screen_state=off
,V/voice   (  293): voice_set_parameters: enter: screen_state=off
V/voice   (  293): voice_set_parameters: exit with code(-2)
V/msm8974_platform(  293): platform_set_parameters: enter: screen_state=off
V/msm8974_platform(  293): platform_set_parameters: exit with code(-2)
,D/audio_hw_hfp(  293): audio_extn_hfp_set_parameters: enter
V/audio_hw_primary(  293): adev_set_parameters: exit
,I/SecExternalDisplayIntents_Java(  875): Intent Recieved ..  -android.intent.action.SCREEN_OFFBroadCast Map value - 18
,D/IpRemoteDisplayController(  875): intent received android.intent.action.SCREEN_OFF
,D/IpRemoteDisplayController(  875): Bridge Server is not available
,D/VolumePanel( 1169): mCoverBroadcastReceiver: Screen OFF start
D/VolumePanel( 1169): mCoverBroadcastReceiver : call onDismissSafeVolumeWarning() #1
,D/VolumePanel( 1169): mCoverBroadcastReceiver: Screen OFF end
D/VolumePanel( 1169): mCoverBroadcastReceiver: onReceive() end : intent=Intent { act=android.intent.action.SCREEN_OFF flg=0x50000010 (has extras) }
,D/PersonaManagerService(  875): ACTION_SCREEN_OFF onReceive
D/PersonaManagerServiceHandler(  875): MSG_ACTION_SCREEN_OFF called
,D/NfcService( 1443): call the applyRotuiing
,D/STATUSBAR-PhoneStatusBar( 1169):      ACTION_SCREEN_OFF is finished!!!! 
,E/StatusBar( 1169): onReceive : Intent.ACTION_SCREEN_OFF
D/Recents_AlternateRecentsComponent( 1169): dismissHelpPopup 
,D/accuweather( 2135): [KK AccuPhone]>>> SWW:66 [0:0] action : androidintentactionSCREEN_OFF
D/accuweather( 2135): [KK AccuPhone]>>> SWW:467 [0:0] stopRefreshIcon : 1
,D/accuweather( 2135): [KK AccuPhone]>>> SWW:364 [0:0] getWeatherRenderer : 1
,D/ConnectivityService(  875): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
,W/ActivityManager(  875): getTasks: caller 10086 does not hold GET_TASKS; limiting output
,W/ActivityManager(  875): getTasks: caller 10086 does not hold GET_TASKS; limiting output
,D/PowerManagerService(  875): [PWL] sb release: PowerManagerService.Broadcasts
,D/SSRM:m  (  875): SIOP:: AP = 350, PST = 403, CUR = 300
D/X       (  875): broadcastSiopLevelIntent:: currentSiopLevel = -1
,D/ContentApp( 1229):  LEVEL : -1
,E/TranscodeReceiver( 8361): onReceive : android.intent.action.CHECK_SIOP_LEVEL
D/TranscodeReceiver( 8361):  SIOP_LEVEL: -1
,D/DisplayPowerState(  875): !@ ColorFade entry
,D/DisplayPowerController(  875): ColorFade: onAnimationEnd
,D/AutomaticBrightnessController(  875): [DAB] setLightSensorEnabled : Send Update unregisterListener mLightSensor
,D/AutomaticBrightnessController(  875): [DAB] setLightSensorEnabled : unregisterListener mLightSensor
,E/LightSensor(  875): Light old sensor_state 8705, new sensor_state : 8193 en : 0
,I/AutomaticBrightnessController(  875): [DAB] fileWriteInt : /sys/class/tcon/tcon/auto_br  value : 0
,I/AutomaticBrightnessController(  875): [DAB] fileWriteInt : /sys/class/backlight/panel/auto_brightness  value : 0
,D/SensorManager(  875): unregisterListener ::   
,E/Sensors (  875): Acc old sensor_state 8193, new sensor_state : 8192 en : 0
,D/SensorManager(  875): unregisterListener ::   
,D/DisplayPowerController(  875): getFinalBrightness : 0 -> 0
,D/DisplayPowerController(  875): getFinalBrightness : 0 -> 0
D/SurfaceFlinger(  249): Set power mode=0, type=0 flinger=0xb6962000
D/qdhwcomposer(  249): hwc_blank: Blanking display: 0
,I/DisplayManagerService(  875): Display device changed: DisplayDeviceInfo{"Built-in Screen": 1080 x 1920, 60.0 fps, supportedRefreshRates [60.0], density 480, 422.03 x 424.069 dpi, appVsyncOff 0, presDeadline 17666667, touch INTERNAL, rotation 0, type BUILT_IN, state OFF, FLAG_DEFAULT_DISPLAY, FLAG_ROTATES_WITH_CONTENT, FLAG_SECURE, FLAG_SUPPORTS_PROTECTED_BUFFERS}
,V/ActivityManager(  875): Display changed displayId=0
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
,D/StatusBar.NetworkController( 1169): onSignalStrengthsChanged signalStrength=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte level=0
D/StatusBar.NetworkController( 1169): updateTelephonySignalStrength: hasService=false ss=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte
,D/StatusBar.NetworkController( 1169): updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal
D/StatusBar.NetworkController( 1169): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02012b/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020468/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
,E/SMD     (  287): DCD ON
,I/qdhwcomposer(  249): handle_blank_event: dpy:0 panel power state: 0
D/qdhwcomposer(  249): hwc_blank: Done blanking display: 0
,D/SurfaceControl(  875): Excessive delay in setPowerMode(): 262ms
D/PowerManagerService(  875): !@[s] blankAllDisplays() : blankAllDisplaysFromPowerManage
D/MISC PowerHAL(  875): sysfs_write +: /sys/class/power_supply/battery/lcd: 0
D/MISC PowerHAL(  875): sysfs_write -: /sys/class/power_supply/battery/lcd: 0
,I/QCOM PowerHAL(  875): Got set_interactive hint
,I/PowerManagerService(  875): [PWL] Off : 0s ago
I/PowerManagerService(  875): [PWL]   PowerManagerService.Display: ref count=2
I/PowerManagerService(  875): [PWL]     mDisplayReady : false
,D/DisplayPowerController(  875): getFinalBrightness : 0 -> 0
D/PowerManagerService(  875): [s] DisplayPowerCallbacks : onStateChanged()
,D/PowerManagerService(  875): [PWL] sb release: PowerManagerService.Display
,I/ServiceManager(  349): Waiting for service AtCmdFwd...
,I/ServiceManager(  349): Waiting for service AtCmdFwd...,
,E/SMD     (  287): DCD ON
,V/AlarmManager(  875): waitForAlarm result :4
,I/ServiceManager(  349): Waiting for service AtCmdFwd...
,V/GLSActivity( 1652): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1652): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
,I/GLSUser ( 1652): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1652): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1652): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1652): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/Finsky  ( 6561): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,D/Finsky  ( 6561): [1] 5.onFinished: Installation state replication failed.
,D/Finsky  ( 6561): [1] 5.onFinished: Scheduling replication attempt 4.
,I/ServiceManager(  349): Waiting for service AtCmdFwd...
,V/AlarmManager(  875): waitForAlarm result :4
,D/KeyguardViewMediator( 1169): received DELAYED_KEYGUARD_ACTION with seq = 2, mDelayedShowingSequence = 2
,D/PersonaManager( 1169): isKioskContainerExistOnDevice
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1169): value : false
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1169): value : false
,D/KeyguardViewMediator( 1169): doKeyguard: not showing because lockscreen is off
,I/PowerManagerService(  875): [PWL] Off : 5s ago
,I/ServiceManager(  349): Waiting for service AtCmdFwd...
,E/SMD     (  287): DCD ON
,W/Atfwd_Sendcmd(  349): AtCmdFwd service not published, waiting... retryCnt : 3
,E/SMD     (  287): DCD ON
,D/SSRM:m  (  875): SIOP:: AP = 340, PST = 391, CUR = 300
,E/SMD     (  287): DCD ON
,V/AlarmManager(  875): waitForAlarm result :8
,E/SMD     (  287): DCD ON
,I/PowerManagerService(  875): [PWL] Off : 15s ago
,W/ContextImpl(  875): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,V/AlarmManager(  875): waitForAlarm result :4
,D/KeyguardUpdateMonitor( 1169): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1169): handleTimeUpdate
,D/KeyguardEffectViewController( 1169): onReceive action : android.intent.action.TIME_TICK
,I/KeyguardEffectViewController( 1169): *** don't update sliding image ***
,D/BatteryService(  875): level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 300, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  875): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
D/BatteryService(  875): stay LED for fully charged
,D/BatteryService(  875): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  875):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  875): Plugged
I/MotionRecognitionService(  875): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1169): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1169): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1169):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3249): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3249): Disconnected process message: 10
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/DateView( 1169): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1169): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/ConnectivityService(  875): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/SMD     (  287): DCD ON
,D/SSRM:m  (  875): SIOP:: AP = 330, PST = 382, CUR = 300
,E/SMD     (  287): DCD ON
,I/ServiceManager(  349): Waiting for service AtCmdFwd...
,I/ServiceManager(  349): Waiting for service AtCmdFwd...
,I/ServiceManager(  349): Waiting for service AtCmdFwd...
,V/AlarmManager(  875): waitForAlarm result :4
,E/SMD     (  287): DCD ON
,V/GLSActivity( 1652): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/ServiceManager(  349): Waiting for service AtCmdFwd...
,I/GLSUser ( 1652): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
I/GLSUser ( 1652): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1652): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1652): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1652): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/Finsky  ( 6561): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,D/Finsky  ( 6561): [1] 5.onFinished: Installation state replication failed.
D/Finsky  ( 6561): [1] 5.onFinished: Scheduling replication attempt 5.
,I/ServiceManager(  349): Waiting for service AtCmdFwd...
,W/Atfwd_Sendcmd(  349): AtCmdFwd service not published, waiting... retryCnt : 4
,E/SMD     (  287): DCD ON
,E/Watchdog(  875): !@Sync 5
,E/SMD     (  287): DCD ON
,D/SSRM:m  (  875): SIOP:: AP = 320, PST = 372, CUR = 300
,I/PowerManagerService(  875): [PWL] Off : 30s ago
,E/SMD     (  287): DCD ON
,W/ContextImpl(  875): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  287): DCD ON
,E/SMD     (  287): DCD ON
,D/SSRM:m  (  875): SIOP:: AP = 320, PST = 363, CUR = 300
,E/SMD     (  287): DCD ON
,V/AlarmManager(  875): waitForAlarm result :4
,D/BatteryService(  875): level:100, scale:100, status:5, health:2, present:true, voltage: 4386, temperature: 300, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  875): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
D/BatteryService(  875): stay LED for fully charged
D/BatteryService(  875): Sending ACTION_BATTERY_CHANGED.
,D/ConnectivityService(  875): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  875): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/MotionRecognitionService(  875):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1169): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1169): handleBatteryUpdate
,I/MotionRecognitionService(  875): Plugged
,I/MotionRecognitionService(  875): setPowerConnected  = true
,D/STATUSBAR-PhoneStatusBar( 1169):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3249): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3249): Disconnected process message: 10
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/GLSActivity( 1652): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ConnectivityService(  875): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  875): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/VacuumService( 1652): Vacuum at: now=1450109429982 tag=VacuumService
,I/GoogleURLConnFactory( 1652): Using platform SSLCertificateSocketFactory
,D/ConnectivityService(  875): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/SMD     (  287): DCD ON
,I/GLSUser ( 1652): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
,I/GLSUser ( 1652): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1652): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1652): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1652): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/BitmapFactory( 1652): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/common_ic_googleplayservices.png
,V/BitmapFactory( 1652): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  875): uri = 14 selection = getSealedState
D/SecContentProvider2(  875): mCursor = null
,D/SecContentProvider2(  875): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  875): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy(  875): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,E/Uploader( 1652): Failed to get auth token: User intervention required. Notification has been pushed.
E/Uploader( 1652): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
E/Uploader( 1652): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
E/Uploader( 1652): 	at com.google.android.gms.auth.p.d(SourceFile:599)
E/Uploader( 1652): 	at com.google.android.gms.auth.p.c(SourceFile:550)
E/Uploader( 1652): 	at com.google.android.gms.auth.p.b(SourceFile:477)
E/Uploader( 1652): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:508)
E/Uploader( 1652): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:337)
E/Uploader( 1652): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:263)
E/Uploader( 1652): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:235)
E/Uploader( 1652): 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:125)
E/Uploader( 1652): 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:78)
E/Uploader( 1652): 	at com.google.android.gms.gcm.am.run(SourceFile:135)
,D/StatusBar( 1169): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,I/PhoneStatusBar( 1169): Icon Only
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
D/PanelView( 1169): There is/are notification(s) 
,D/PanelView( 1169): There is/are notification(s) 
,I/System.out( 1652): (HTTPLog)-Static: SBServiceAPI: getService class android.os.ServiceManager
,I/System.out( 1652): (HTTPLog)-Static: isShipBuild true
I/System.out( 1652): (HTTPLog)-Thread-199-880981722: SmartBonding Enabling is true, SHIP_BUILD is true, log to file is false, DBG is false
,I/qtaguid ( 1652): Tagging socket 58 with tag 120100000000{4609,0} uid -1, pid: 1652, getuid(): 10012
,I/qtaguid ( 1652): Tagging socket 62 with tag 120100000000{4609,0} uid -1, pid: 1652, getuid(): 10012
,V/GLSActivity( 1652): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1652): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
I/GLSUser ( 1652): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1652): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1652): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1652): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/Finsky  ( 6561): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,D/Finsky  ( 6561): [1] 5.onFinished: Installation state replication failed.
D/Finsky  ( 6561): [1] 5.onFinished: Giving up after 6 failures.
,W/Uploader( 1652): No account for auth token provided
,I/qtaguid ( 1652): Tagging socket 58 with tag 120100000000{4609,0} uid -1, pid: 1652, getuid(): 10012
,W/Uploader( 1652): No account for auth token provided
,I/qtaguid ( 1652): Tagging socket 58 with tag 120100000000{4609,0} uid -1, pid: 1652, getuid(): 10012
,W/Uploader( 1652): No account for auth token provided
,I/qtaguid ( 1652): Tagging socket 58 with tag 120100000000{4609,0} uid -1, pid: 1652, getuid(): 10012
,W/Uploader( 1652):  no longer exists, so no auth token.
,I/qtaguid ( 1652): Tagging socket 58 with tag 120100000000{4609,0} uid -1, pid: 1652, getuid(): 10012
,V/AlarmManager(  875): waitForAlarm result :4
,D/ConnectivityService(  875): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/SQLiteLog( 1652): (10) POSIX Error : 11 SQLite Error : 3850
,D/ConnectivityService(  875): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  875): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  875): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/BooksSync( 7308): Starting books sync, d
,D/ConnectivityService(  875): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,V/GLSActivity( 1652): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/art     ( 1652): Explicit concurrent mark sweep GC freed 52990(2MB) AllocSpace objects, 48(3MB) LOS objects, 40% free, 18MB/30MB, paused 885us total 64.276ms
,I/GLSUser ( 1652): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,I/GLSUser ( 1652): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1652): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1652): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1652): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/GLSUser ( 1652): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
,I/GLSUser ( 1652): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1652): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1652): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1652): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ResourcesManager( 1652): creating new AssetManager and set to /system/app/Books/Books.apk
,I/ServiceManager(  349): Waiting for service AtCmdFwd...
,V/BitmapFactory( 1652): DecodeImagePath(decodeResourceStream3) : res/mipmap-xxhdpi-v4/ic_launcher_play_books.png
,D/ResourcesManager( 1652): creating new AssetManager and set to /system/app/PlusOne/PlusOne.apk
,V/BitmapFactory( 1652): DecodeImagePath(decodeResourceStream3) : res/mipmap-xxhdpi-v4/quantum_logo_google_plus_color_44in48.png
,V/BitmapFactory( 1652): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,V/BitmapFactory( 1652): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  875): uri = 14 selection = getSealedState
D/SecContentProvider2(  875): uri = 14 selection = getSealedState
D/SecContentProvider2(  875): mCursor = null
,D/SecContentProvider2(  875): mCursor = null
D/SecContentProvider2(  875): KnoxCustomManagerService offline: service is not available
D/SecContentProvider2(  875): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  875): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
V/ApplicationPolicy(  875): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,W/GLSActivity( 1652): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1652): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1652): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1652): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1652): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1652): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1652): 	at android.os.Binder.execTransact(Binder.java:446)
,D/ApplicationPolicy(  875): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy(  875): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/StatusBar( 1169): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,I/PhoneStatusBar( 1169): Icon Only
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
D/PanelView( 1169): There is/are notification(s) 
,D/PanelView( 1169): There is/are notification(s) 
,E/BooksAccountManager( 7308): Authentication error
E/BooksAccountManager( 7308): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 7308): android.accounts.AccountManager.convertErrorToException(AccountManager.java:1893)
E/HttpHelper( 7308): null auth token
,E/HttpOperation( 5312): [kfu{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
E/HttpOperation( 5312): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 5312): 	at kfv.a(PG:65)
E/HttpOperation( 5312): 	at kff.u(PG:385)
E/HttpOperation( 5312): 	at kfb.a(PG:29)
E/HttpOperation( 5312): 	at kff.l(PG:132)
E/HttpOperation( 5312): 	at dsf.a(PG:807)
E/HttpOperation( 5312): 	at fhk.a(PG:1126)
E/HttpOperation( 5312): 	at fhk.a(PG:908)
E/HttpOperation( 5312): 	at fhk.onPerformSync(PG:636)
E/HttpOperation( 5312): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/HttpOperation( 5312): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/HttpOperation( 5312): 	at ihi.a(PG:22)
E/HttpOperation( 5312): 	at kft.a(PG:91)
E/HttpOperation( 5312): 	at kfv.a(PG:62)
E/HttpOperation( 5312): 	... 8 more
E/HttpOperation( 5312): Caused by: gdi: User intervention required. Notification has been pushed.
E/HttpOperation( 5312): 	at gde.c(Unknown Source)
E/HttpOperation( 5312): 	at gde.b(Unknown Source)
E/HttpOperation( 5312): 	at ihi.a(PG:19)
E/HttpOperation( 5312): 	... 10 more
,I/qtaguid ( 7308): Tagging socket 34 with tag 10000000000{256,0} uid -1, pid: 7308, getuid(): 10082
,D/StatusBar( 1169): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,I/PhoneStatusBar( 1169): Icon Only
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
D/PanelView( 1169): There is/are notification(s) 
,D/PanelView( 1169): There is/are notification(s) 
,I/qtaguid ( 7308): Tagging socket 34 with tag 10000000000{256,0} uid -1, pid: 7308, getuid(): 10082
,I/GLSUser ( 1652): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,I/GLSUser ( 1652): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1652): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1652): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1652): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/BitmapFactory( 1652): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  875): uri = 14 selection = getSealedState
D/SecContentProvider2(  875): mCursor = null
,D/SecContentProvider2(  875): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  875): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy(  875): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,I/qtaguid ( 7308): Untagging socket 34
,W/ApiaryClient( 7308): Error response from books API: {
W/ApiaryClient( 7308):  "error": {
W/ApiaryClient( 7308):   "errors": [
W/ApiaryClient( 7308):    {
W/ApiaryClient( 7308):     "domain": "global",
W/ApiaryClient( 7308):     "reason": "required",
W/ApiaryClient( 7308):     "message": "Login Required",
W/ApiaryClient( 7308):     "locationType": "header",
W/ApiaryClient( 7308):     "location": "Authorization"
W/ApiaryClient( 7308):    }
W/ApiaryClient( 7308):   ],
W/ApiaryClient( 7308):   "code": 401,
W/ApiaryClient( 7308):   "message": "Login Required"
W/ApiaryClient( 7308):  }
W/ApiaryClient( 7308): }
,W/ApiaryClient( 7308): errCount = 1: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 7308): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3DS0HXd4TFLU4&nonce=8240450645645800976&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 7308): Headers suppressed
,D/ConnectivityService(  875): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/StatusBar( 1169): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,E/HttpOperation( 5312): [getmobileexperiments] Unexpected exception
E/HttpOperation( 5312): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 5312): 	at kfv.a(PG:65)
E/HttpOperation( 5312): 	at kff.u(PG:385)
E/HttpOperation( 5312): 	at kfb.a(PG:29)
E/HttpOperation( 5312): 	at kff.l(PG:132)
E/HttpOperation( 5312): 	at ieo.a(PG:43)
E/HttpOperation( 5312): 	at iep.a(PG:93)
E/HttpOperation( 5312): 	at fhn.a(PG:59)
E/HttpOperation( 5312): 	at lex.a(PG:85)
E/HttpOperation( 5312): 	at lex.b(PG:132)
E/HttpOperation( 5312): 	at fhk.a(PG:1146)
E/HttpOperation( 5312): 	at fhk.a(PG:908)
E/HttpOperation( 5312): 	at fhk.onPerformSync(PG:636)
E/HttpOperation( 5312): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/HttpOperation( 5312): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/HttpOperation( 5312): 	at ihi.a(PG:22)
E/HttpOperation( 5312): 	at kft.a(PG:91)
E/HttpOperation( 5312): 	at kfv.a(PG:62)
E/HttpOperation( 5312): 	... 12 more
E/HttpOperation( 5312): Caused by: gdi: User intervention required. Notification has been pushed.
E/HttpOperation( 5312): 	at gde.c(Unknown Source)
E/HttpOperation( 5312): 	at gde.b(Unknown Source)
E/HttpOperation( 5312): 	at ihi.a(PG:19)
E/HttpOperation( 5312): 	... 14 more
,E/ExperimentLoader( 5312): [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 5312): java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 5312): 	at kfv.a(PG:65)
E/ExperimentLoader( 5312): 	at kff.u(PG:385)
E/ExperimentLoader( 5312): 	at kfb.a(PG:29)
E/ExperimentLoader( 5312): 	at kff.l(PG:132)
E/ExperimentLoader( 5312): 	at ieo.a(PG:43)
E/ExperimentLoader( 5312): 	at iep.a(PG:93)
E/ExperimentLoader( 5312): 	at fhn.a(PG:59)
E/ExperimentLoader( 5312): 	at lex.a(PG:85)
E/ExperimentLoader( 5312): 	at lex.b(PG:132)
E/ExperimentLoader( 5312): 	at fhk.a(PG:1146)
E/ExperimentLoader( 5312): 	at fhk.a(PG:908)
E/ExperimentLoader( 5312): 	at fhk.onPerformSync(PG:636)
E/ExperimentLoader( 5312): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/ExperimentLoader( 5312): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/ExperimentLoader( 5312): 	at ihi.a(PG:22)
E/ExperimentLoader( 5312): 	at kft.a(PG:91)
E/ExperimentLoader( 5312): 	at kfv.a(PG:62)
E/ExperimentLoader( 5312): 	... 12 more
E/ExperimentLoader( 5312): Caused by: gdi: User intervention required. Notification has been pushed.
E/ExperimentLoader( 5312): 	at gde.c(Unknown Source)
E/ExperimentLoader( 5312): 	at gde.b(Unknown Source)
E/ExperimentLoader( 5312): 	at ihi.a(PG:19)
E/ExperimentLoader( 5312): 	... 14 more
,I/PhoneStatusBar( 1169): Icon Only
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
D/PanelView( 1169): There is/are notification(s) 
D/PanelView( 1169): There is/are notification(s) 
,E/SQLiteLog( 1652): (10) POSIX Error : 11 SQLite Error : 3850
,I/GLSUser ( 1652): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,I/GLSUser ( 1652): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1652): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1652): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1652): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/BitmapFactory( 1652): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  875): uri = 14 selection = getSealedState
D/SecContentProvider2(  875): mCursor = null
,D/SecContentProvider2(  875): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  875): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
V/ApplicationPolicy(  875): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/StatusBar( 1169): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,I/PhoneStatusBar( 1169): Icon Only
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
D/PanelView( 1169): There is/are notification(s) 
,D/PanelView( 1169): There is/are notification(s) 
,E/HttpOperation( 5312): [getaccountstatus] Unexpected exception
E/HttpOperation( 5312): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 5312): 	at kfv.a(PG:65)
E/HttpOperation( 5312): 	at kff.u(PG:385)
E/HttpOperation( 5312): 	at kfb.a(PG:29)
E/HttpOperation( 5312): 	at ixd.a(PG:248)
E/HttpOperation( 5312): 	at ixd.b(PG:206)
E/HttpOperation( 5312): 	at ixd.a(PG:175)
E/HttpOperation( 5312): 	at fig.a(PG:78)
E/HttpOperation( 5312): 	at lex.a(PG:85)
E/HttpOperation( 5312): 	at lex.b(PG:132)
E/HttpOperation( 5312): 	at fhk.a(PG:1146)
E/HttpOperation( 5312): 	at fhk.a(PG:908)
E/HttpOperation( 5312): 	at fhk.onPerformSync(PG:636)
E/HttpOperation( 5312): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/HttpOperation( 5312): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/HttpOperation( 5312): 	at ihi.a(PG:22)
E/HttpOperation( 5312): 	at kft.a(PG:91)
E/HttpOperation( 5312): 	at kfv.a(PG:62)
E/HttpOperation( 5312): 	... 12 more
E/HttpOperation( 5312): Caused by: gdi: User intervention required. Notification has been pushed.
E/HttpOperation( 5312): 	at gde.c(Unknown Source)
E/HttpOperation( 5312): 	at gde.b(Unknown Source)
E/HttpOperation( 5312): 	at ihi.a(PG:19)
E/HttpOperation( 5312): 	... 14 more
,E/EsSyncAdapterService( 5312): Sync failure
E/EsSyncAdapterService( 5312): java.io.IOException: Rpc failed
E/EsSyncAdapterService( 5312): 	at ixd.a(PG:348)
E/EsSyncAdapterService( 5312): 	at ixd.a(PG:248)
E/EsSyncAdapterService( 5312): 	at ixd.b(PG:206)
E/EsSyncAdapterService( 5312): 	at ixd.a(PG:175)
E/EsSyncAdapterService( 5312): 	at fig.a(PG:78)
E/EsSyncAdapterService( 5312): 	at lex.a(PG:85)
E/EsSyncAdapterService( 5312): 	at lex.b(PG:132)
E/EsSyncAdapterService( 5312): 	at fhk.a(PG:1146)
E/EsSyncAdapterService( 5312): 	at fhk.a(PG:908)
E/EsSyncAdapterService( 5312): 	at fhk.onPerformSync(PG:636)
E/EsSyncAdapterService( 5312): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/EsSyncAdapterService( 5312): Caused by: java.io.IOException: Cannot obtain authentication token
E/EsSyncAdapterService( 5312): 	at kfv.a(PG:65)
E/EsSyncAdapterService( 5312): 	at kff.u(PG:385)
E/EsSyncAdapterService( 5312): 	at kfb.a(PG:29)
E/EsSyncAdapterService( 5312): 	... 10 more
E/EsSyncAdapterService( 5312): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/EsSyncAdapterService( 5312): 	at ihi.a(PG:22)
E/EsSyncAdapterService( 5312): 	at kft.a(PG:91)
E/EsSyncAdapterService( 5312): 	at kfv.a(PG:62)
E/EsSyncAdapterService( 5312): 	... 12 more
E/EsSyncAdapterService( 5312): Caused by: gdi: User intervention required. Notification has been pushed.
E/EsSyncAdapterService( 5312): 	at gde.c(Unknown Source)
E/EsSyncAdapterService( 5312): 	at gde.b(Unknown Source)
E/EsSyncAdapterService( 5312): 	at ihi.a(PG:19)
E/EsSyncAdapterService( 5312): 	... 14 more
,D/ConnectivityService(  875): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SyncManager(  875): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, PERIODIC, currentRunTime 155625, reason: Periodic, SyncResult: stats [ numIoExceptions: 2]
,D/ConnectivityService(  875): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  875): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SecContentProvider2(  875): uri = 11 selection = getMyKnoxAdmin
D/SecContentProvider2(  875): mCursor = null
,I/ServiceManager(  349): Waiting for service AtCmdFwd...
,I/art     (  875): Explicit concurrent mark sweep GC freed 48401(2MB) AllocSpace objects, 21(661KB) LOS objects, 30% free, 36MB/52MB, paused 1.724ms total 157.929ms
,E/SQLiteLog( 1652): (10) POSIX Error : 11 SQLite Error : 3850
,V/GLSActivity( 1652): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1652): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
,I/GLSUser ( 1652): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1652): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1652): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1652): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/BitmapFactory( 1652): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  875): uri = 14 selection = getSealedState
,D/SecContentProvider2(  875): mCursor = null
D/SecContentProvider2(  875): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  875): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy(  875): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/StatusBar( 1169): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,I/PhoneStatusBar( 1169): Icon Only
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
D/PanelView( 1169): There is/are notification(s) 
,D/PanelView( 1169): There is/are notification(s) 
,W/GLSActivity( 1652): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1652): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1652): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1652): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1652): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1652): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1652): 	at android.os.Binder.execTransact(Binder.java:446)
,E/BooksAccountManager( 7308): Authentication error
E/BooksAccountManager( 7308): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 7308): android.accounts.AccountManager.convertErrorToException(AccountManager.java:1893)
,E/HttpHelper( 7308): null auth token
,I/qtaguid ( 7308): Tagging socket 34 with tag 10000000000{256,0} uid -1, pid: 7308, getuid(): 10082
,I/qtaguid ( 7308): Tagging socket 39 with tag 10000000000{256,0} uid -1, pid: 7308, getuid(): 10082
,I/qtaguid ( 7308): Untagging socket 34
,W/ApiaryClient( 7308): Error response from books API: {
W/ApiaryClient( 7308):  "error": {
W/ApiaryClient( 7308):   "errors": [
W/ApiaryClient( 7308):    {
W/ApiaryClient( 7308):     "domain": "global",
W/ApiaryClient( 7308):     "reason": "required",
W/ApiaryClient( 7308):     "message": "Login Required",
W/ApiaryClient( 7308):     "locationType": "header",
W/ApiaryClient( 7308):     "location": "Authorization"
W/ApiaryClient( 7308):    }
W/ApiaryClient( 7308):   ],
W/ApiaryClient( 7308):   "code": 401,
W/ApiaryClient( 7308):   "message": "Login Required"
W/ApiaryClient( 7308):  }
W/ApiaryClient( 7308): }
,W/ApiaryClient( 7308): errCount = 2: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 7308): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3DS0HXd4TFLU4&nonce=8240450645645800976&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 7308): Headers suppressed
,D/ConnectivityService(  875): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/SMD     (  287): DCD ON
,I/ServiceManager(  349): Waiting for service AtCmdFwd...
,V/GLSActivity( 1652): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1652): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
,I/GLSUser ( 1652): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1652): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1652): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1652): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/BitmapFactory( 1652): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  875): uri = 14 selection = getSealedState
,D/SecContentProvider2(  875): mCursor = null
D/SecContentProvider2(  875): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  875): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy(  875): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/StatusBar( 1169): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,I/PhoneStatusBar( 1169): Icon Only
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
D/PanelView( 1169): There is/are notification(s) 
,D/PanelView( 1169): There is/are notification(s) 
,W/GLSActivity( 1652): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1652): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1652): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1652): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1652): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1652): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1652): 	at android.os.Binder.execTransact(Binder.java:446)
,E/BooksAccountManager( 7308): Authentication error
E/BooksAccountManager( 7308): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 7308): android.accounts.AccountManager.convertErrorToException(AccountManager.java:1893)
,E/HttpHelper( 7308): null auth token
,I/qtaguid ( 7308): Tagging socket 34 with tag 10000000000{256,0} uid -1, pid: 7308, getuid(): 10082
,I/qtaguid ( 7308): Untagging socket 34
,W/ApiaryClient( 7308): Error response from books API: {
W/ApiaryClient( 7308):  "error": {
W/ApiaryClient( 7308):   "errors": [
W/ApiaryClient( 7308):    {
W/ApiaryClient( 7308):     "domain": "global",
W/ApiaryClient( 7308):     "reason": "required",
W/ApiaryClient( 7308):     "message": "Login Required",
W/ApiaryClient( 7308):     "locationType": "header",
W/ApiaryClient( 7308):     "location": "Authorization"
W/ApiaryClient( 7308):    }
W/ApiaryClient( 7308):   ],
W/ApiaryClient( 7308):   "code": 401,
W/ApiaryClient( 7308):   "message": "Login Required"
W/ApiaryClient( 7308):  }
W/ApiaryClient( 7308): }
,W/ApiaryClient( 7308): errCount = 3: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 7308): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3DS0HXd4TFLU4&nonce=8240450645645800976&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 7308): Headers suppressed
,D/ConnectivityService(  875): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/ServiceManager(  349): Waiting for service AtCmdFwd...
,E/BooksSync( 7308): Soft error,
E/BooksSync( 7308): com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
E/BooksSync( 7308): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3DS0HXd4TFLU4&nonce=8240450645645800976&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
E/BooksSync( 7308): Headers suppressed,
E/BooksSync( 7308): 
E/BooksSync( 7308): com.google.android.apps.books.net.HttpHelper.wrapExceptionBasedOnStatus(HttpHelper.java:212)
,E/BooksSync( 7308): Sync error
E/BooksSync( 7308): com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
E/BooksSync( 7308): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3DS0HXd4TFLU4&nonce=8240450645645800976&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
E/BooksSync( 7308): Headers suppressed
E/BooksSync( 7308): 
E/BooksSync( 7308): com.google.android.apps.books.net.HttpHelper.wrapExceptionBasedOnStatus(HttpHelper.java:212)
,I/BooksSync( 7308): Finished books sync
,D/ConnectivityService(  875): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SyncManager(  875): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 161396, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,D/ConnectivityService(  875): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SSRM:m  (  875): SIOP:: AP = 320, PST = 356, CUR = 300
,I/PowerManagerService(  875): [PWL] Off : 50s ago
,I/PowerManagerService(  875): [PWL]   PowerManagerService.WakeLocks: ref count=1
I/PowerManagerService(  875): [PWL]     mWakeLockSummary : 0x1
I/PowerManagerService(  875): [PWL]       PARTIAL_WAKE_LOCK              'SyncLoopWakeLock' (uid=1000, pid=875, ws=null) (elapsedTime=112)
,D/SecContentProvider2(  875): uri = 11 selection = getMyKnoxAdmin
,D/SecContentProvider2(  875): mCursor = null
,D/ConnectivityService(  875): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/ServiceManager(  349): Waiting for service AtCmdFwd...
,E/SMD     (  287): DCD ON
,W/Atfwd_Sendcmd(  349): AtCmdFwd service not published, waiting... retryCnt : 5
,E/SMD     (  287): DCD ON
,W/ContextImpl(  875): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  287): DCD ON
,E/Watchdog(  875): !@Sync 6
,E/SMD     (  287): DCD ON
,D/SSRM:m  (  875): SIOP:: AP = 320, PST = 348, CUR = 300
,E/SMD     (  287): DCD ON,
,D/BatteryService(  875): level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 300, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  875): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  875): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  875):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  875): Plugged
,I/MotionRecognitionService(  875): setPowerConnected  = true
,D/BatteryService(  875): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1169): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1169): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1169):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3249): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3249): Disconnected process message: 10
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  287): DCD ON
,E/SMD     (  287): DCD ON
,D/SSRM:m  (  875): SIOP:: AP = 310, PST = 337, CUR = 300
,E/SMD     (  287): DCD ON
,V/AlarmManager(  875): waitForAlarm result :8
,E/SMD     (  287): DCD ON
,I/PowerManagerService(  875): [PWL] Off : 75s ago
,W/ContextImpl(  875): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,V/AlarmManager(  875): waitForAlarm result :4
,D/KeyguardUpdateMonitor( 1169): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1169): handleTimeUpdate
,D/KeyguardEffectViewController( 1169): onReceive action : android.intent.action.TIME_TICK
,I/KeyguardEffectViewController( 1169): *** don't update sliding image ***
,D/BatteryService(  875): level:100, scale:100, status:5, health:2, present:true, voltage: 4382, temperature: 300, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  875): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
D/BatteryService(  875): stay LED for fully charged
,D/BatteryService(  875): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1169): received broadcast android.intent.action.BATTERY_CHANGED
,D/MotionRecognitionService(  875):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  875): Plugged
,I/MotionRecognitionService(  875): setPowerConnected  = true
,V/HeadsetService( 3249): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3249): Disconnected process message: 10
,D/STATUSBAR-PhoneStatusBar( 1169):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/KeyguardUpdateMonitor( 1169): handleBatteryUpdate
,D/DateView( 1169): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1169): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,I/Atfwd_Sendcmd(  349): AtCmdFwd service not ready - Exhausted retry attempts - :6
I/Atfwd_Daemon(  349): result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,D/ConnectivityService(  875): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/SMD     (  287): DCD ON
,D/SSRM:m  (  875): SIOP:: AP = 310, PST = 328, CUR = 300
,E/SMD     (  287): DCD ON
,E/SMD     (  287): DCD ON
,D/BatteryService(  875): level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 300, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  875): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  875): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  875):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  875): Plugged
,I/MotionRecognitionService(  875): setPowerConnected  = true
,D/BatteryService(  875): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1169): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1169): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1169):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3249): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3249): Disconnected process message: 10
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/ServiceManager(  349): Waiting for service AtCmdFwd...
,E/SMD     (  287): DCD ON
,E/Watchdog(  875): !@Sync 7
,I/ServiceManager(  349): Waiting for service AtCmdFwd...
,I/ServiceManager(  349): Waiting for service AtCmdFwd...
,I/ServiceManager(  349): Waiting for service AtCmdFwd...
,E/SMD     (  287): DCD ON
,I/ServiceManager(  349): Waiting for service AtCmdFwd...
,D/SSRM:m  (  875): SIOP:: AP = 310, PST = 323, CUR = 300
,W/Atfwd_Sendcmd(  349): AtCmdFwd service not published, waiting... retryCnt : 1
,E/SMD     (  287): DCD ON
,W/ContextImpl(  875): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  287): DCD ON
,I/ServiceManager(  349): Waiting for service AtCmdFwd...
,D/BatteryService(  875): level:100, scale:100, status:5, health:2, present:true, voltage: 4386, temperature: 300, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  875): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  875): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  875):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  875): Plugged
,I/MotionRecognitionService(  875): setPowerConnected  = true
,D/BatteryService(  875): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1169): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1169): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1169):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3249): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3249): Disconnected process message: 10
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/ServiceManager(  349): Waiting for service AtCmdFwd...
,I/ServiceManager(  349): Waiting for service AtCmdFwd...
,E/SMD     (  287): DCD ON
,I/ServiceManager(  349): Waiting for service AtCmdFwd...
,I/ServiceManager(  349): Waiting for service AtCmdFwd...
,D/SSRM:m  (  875): SIOP:: AP = 310, PST = 319, CUR = 300
,W/Atfwd_Sendcmd(  349): AtCmdFwd service not published, waiting... retryCnt : 2
,E/SMD     (  287): DCD ON
,E/SMD     (  287): DCD ON
,I/PowerManagerService(  875): [PWL] Off : 105s ago
,V/AlarmManager(  875): waitForAlarm result :4
,D/ConnectivityService(  875): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/BatteryService(  875): level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 299, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  875): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
D/BatteryService(  875): stay LED for fully charged
D/BatteryService(  875): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  875):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  875): Plugged
I/MotionRecognitionService(  875): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1169): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1169): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1169):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3249): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3249): Disconnected process message: 10
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/ConnectivityService(  875): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/BooksSync( 7308): Starting books sync, d
,D/ConnectivityService(  875): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,V/GLSActivity( 1652): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1652): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
,I/GLSUser ( 1652): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1652): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1652): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1652): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/BitmapFactory( 1652): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  875): uri = 14 selection = getSealedState
,D/SecContentProvider2(  875): mCursor = null
D/SecContentProvider2(  875): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  875): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy(  875): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/StatusBar( 1169): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,I/PhoneStatusBar( 1169): Icon Only
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
D/PanelView( 1169): There is/are notification(s) 
,D/PanelView( 1169): There is/are notification(s) 
,W/GLSActivity( 1652): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1652): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1652): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1652): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1652): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1652): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1652): 	at android.os.Binder.execTransact(Binder.java:446)
,E/BooksAccountManager( 7308): Authentication error
E/BooksAccountManager( 7308): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 7308): android.accounts.AccountManager.convertErrorToException(AccountManager.java:1893)
,E/HttpHelper( 7308): null auth token
,I/qtaguid ( 7308): Tagging socket 34 with tag 10000000000{256,0} uid -1, pid: 7308, getuid(): 10082
,I/qtaguid ( 7308): Untagging socket 34
,W/ApiaryClient( 7308): Error response from books API: {
W/ApiaryClient( 7308):  "error": {
W/ApiaryClient( 7308):   "errors": [
W/ApiaryClient( 7308):    {
W/ApiaryClient( 7308):     "domain": "global",
W/ApiaryClient( 7308):     "reason": "required",
W/ApiaryClient( 7308):     "message": "Login Required",
W/ApiaryClient( 7308):     "locationType": "header",
W/ApiaryClient( 7308):     "location": "Authorization"
W/ApiaryClient( 7308):    }
W/ApiaryClient( 7308):   ],
W/ApiaryClient( 7308):   "code": 401,
W/ApiaryClient( 7308):   "message": "Login Required"
W/ApiaryClient( 7308):  }
W/ApiaryClient( 7308): }
,W/ApiaryClient( 7308): errCount = 1: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 7308): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3DS0HXd4TFLU4&nonce=-3188453460327020365&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 7308): Headers suppressed
,D/ConnectivityService(  875): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,V/GLSActivity( 1652): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1652): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
,I/GLSUser ( 1652): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1652): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1652): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1652): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/BitmapFactory( 1652): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  875): uri = 14 selection = getSealedState
,D/SecContentProvider2(  875): mCursor = null
D/SecContentProvider2(  875): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  875): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy(  875): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/StatusBar( 1169): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,I/PhoneStatusBar( 1169): Icon Only
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
D/PanelView( 1169): There is/are notification(s) 
,D/PanelView( 1169): There is/are notification(s) 
,W/GLSActivity( 1652): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1652): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1652): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1652): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1652): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1652): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1652): 	at android.os.Binder.execTransact(Binder.java:446)
,E/BooksAccountManager( 7308): Authentication error
E/BooksAccountManager( 7308): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 7308): android.accounts.AccountManager.convertErrorToException(AccountManager.java:1893)
,E/HttpHelper( 7308): null auth token
,I/qtaguid ( 7308): Tagging socket 34 with tag 10000000000{256,0} uid -1, pid: 7308, getuid(): 10082
,I/qtaguid ( 7308): Untagging socket 34
,E/SMD     (  287): DCD ON
,W/ApiaryClient( 7308): Error response from books API: {
W/ApiaryClient( 7308):  "error": {
W/ApiaryClient( 7308):   "errors": [
W/ApiaryClient( 7308):    {
W/ApiaryClient( 7308):     "domain": "global",
W/ApiaryClient( 7308):     "reason": "required",
W/ApiaryClient( 7308):     "message": "Login Required",
W/ApiaryClient( 7308):     "locationType": "header",
W/ApiaryClient( 7308):     "location": "Authorization"
W/ApiaryClient( 7308):    }
W/ApiaryClient( 7308):   ],
W/ApiaryClient( 7308):   "code": 401,
W/ApiaryClient( 7308):   "message": "Login Required"
W/ApiaryClient( 7308):  }
W/ApiaryClient( 7308): }
,W/ApiaryClient( 7308): errCount = 2: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 7308): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3DS0HXd4TFLU4&nonce=-3188453460327020365&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 7308): Headers suppressed
,D/ConnectivityService(  875): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,V/GLSActivity( 1652): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1652): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
,I/GLSUser ( 1652): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1652): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1652): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1652): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/BitmapFactory( 1652): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  875): uri = 14 selection = getSealedState
,D/SecContentProvider2(  875): mCursor = null
D/SecContentProvider2(  875): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  875): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy(  875): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/StatusBar( 1169): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,I/PhoneStatusBar( 1169): Icon Only
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
,D/PanelView( 1169): There is/are notification(s) 
,D/PanelView( 1169): There is/are notification(s) 
,W/GLSActivity( 1652): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1652): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1652): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1652): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1652): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1652): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1652): 	at android.os.Binder.execTransact(Binder.java:446)
,E/BooksAccountManager( 7308): Authentication error
E/BooksAccountManager( 7308): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 7308): android.accounts.AccountManager.convertErrorToException(AccountManager.java:1893)
,E/HttpHelper( 7308): null auth token
,I/qtaguid ( 7308): Tagging socket 34 with tag 10000000000{256,0} uid -1, pid: 7308, getuid(): 10082
,I/qtaguid ( 7308): Untagging socket 34
,W/ApiaryClient( 7308): Error response from books API: {
W/ApiaryClient( 7308):  "error": {
W/ApiaryClient( 7308):   "errors": [
W/ApiaryClient( 7308):    {
W/ApiaryClient( 7308):     "domain": "global",
W/ApiaryClient( 7308):     "reason": "required",
W/ApiaryClient( 7308):     "message": "Login Required",
W/ApiaryClient( 7308):     "locationType": "header",
W/ApiaryClient( 7308):     "location": "Authorization"
W/ApiaryClient( 7308):    }
W/ApiaryClient( 7308):   ],
W/ApiaryClient( 7308):   "code": 401,
W/ApiaryClient( 7308):   "message": "Login Required"
W/ApiaryClient( 7308):  }
W/ApiaryClient( 7308): }
,W/ApiaryClient( 7308): errCount = 3: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 7308): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3DS0HXd4TFLU4&nonce=-3188453460327020365&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 7308): Headers suppressed
,D/ConnectivityService(  875): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/BooksSync( 7308): Soft error
E/BooksSync( 7308): com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
E/BooksSync( 7308): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3DS0HXd4TFLU4&nonce=-3188453460327020365&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
E/BooksSync( 7308): Headers suppressed
E/BooksSync( 7308): 
E/BooksSync( 7308): com.google.android.apps.books.net.HttpHelper.wrapExceptionBasedOnStatus(HttpHelper.java:212)
,E/BooksSync( 7308): Sync error
E/BooksSync( 7308): com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
E/BooksSync( 7308): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3DS0HXd4TFLU4&nonce=-3188453460327020365&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
E/BooksSync( 7308): Headers suppressed
E/BooksSync( 7308): 
E/BooksSync( 7308): com.google.android.apps.books.net.HttpHelper.wrapExceptionBasedOnStatus(HttpHelper.java:212)
,I/BooksSync( 7308): Finished books sync
,D/ConnectivityService(  875): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SyncManager(  875): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 218966, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,D/ConnectivityService(  875): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SecContentProvider2(  875): uri = 11 selection = getMyKnoxAdmin
,D/SecContentProvider2(  875): mCursor = null
,D/ConnectivityService(  875): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SSRM:m  (  875): SIOP:: AP = 310, PST = 316, CUR = 300
,E/SMD     (  287): DCD ON
,I/ServiceManager(  349): Waiting for service AtCmdFwd...
,I/ServiceManager(  349): Waiting for service AtCmdFwd...
,I/ServiceManager(  349): Waiting for service AtCmdFwd...
,E/SMD     (  287): DCD ON
,I/ServiceManager(  349): Waiting for service AtCmdFwd...
,I/ServiceManager(  349): Waiting for service AtCmdFwd...
,W/ContextImpl(  875): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,W/Atfwd_Sendcmd(  349): AtCmdFwd service not published, waiting... retryCnt : 3
,D/BatteryService(  875): level:100, scale:100, status:5, health:2, present:true, voltage: 4386, temperature: 299, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  875): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  875): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  875):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  875): Plugged
,I/MotionRecognitionService(  875): setPowerConnected  = true
,D/BatteryService(  875): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1169): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1169): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1169):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3249): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3249): Disconnected process message: 10
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  287): DCD ON
,E/Watchdog(  875): !@Sync 8
,E/SMD     (  287): DCD ON
,D/SSRM:m  (  875): SIOP:: AP = 310, PST = 314, CUR = 300
,E/SMD     (  287): DCD ON
,E/SMD     (  287): DCD ON
,E/SMD     (  287): DCD ON
,D/SSRM:m  (  875): SIOP:: AP = 300, PST = 312, CUR = 300
,I/ServiceManager(  349): Waiting for service AtCmdFwd...
,E/SMD     (  287): DCD ON
,I/ServiceManager(  349): Waiting for service AtCmdFwd...
,I/ServiceManager(  349): Waiting for service AtCmdFwd...
,I/ServiceManager(  349): Waiting for service AtCmdFwd...
,V/AlarmManager(  875): waitForAlarm result :8
,E/SMD     (  287): DCD ON
,I/ServiceManager(  349): Waiting for service AtCmdFwd...
,W/ContextImpl(  875): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,W/Atfwd_Sendcmd(  349): AtCmdFwd service not published, waiting... retryCnt : 4
,V/AlarmManager(  875): waitForAlarm result :4
,D/KeyguardUpdateMonitor( 1169): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1169): handleTimeUpdate
,D/KeyguardEffectViewController( 1169): onReceive action : android.intent.action.TIME_TICK
,I/KeyguardEffectViewController( 1169): *** don't update sliding image ***
,D/BatteryService(  875): level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 299, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  875): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  875): stay LED for fully charged
,D/BatteryService(  875): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  875):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  875): Plugged
,I/MotionRecognitionService(  875): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1169): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1169): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1169):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3249): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3249): Disconnected process message: 10
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/DateView( 1169): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1169): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/ConnectivityService(  875): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  875): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/GLSUser ( 1652): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,I/GLSUser ( 1652): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1652): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1652): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1652): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/BitmapFactory( 1652): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  875): uri = 14 selection = getSealedState
,D/SecContentProvider2(  875): mCursor = null
,D/SecContentProvider2(  875): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  875): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy(  875): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,E/HttpOperation( 5312): [kfu{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
E/HttpOperation( 5312): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 5312): 	at kfv.a(PG:65)
E/HttpOperation( 5312): 	at kff.u(PG:385)
E/HttpOperation( 5312): 	at kfb.a(PG:29)
E/HttpOperation( 5312): 	at kff.l(PG:132)
E/HttpOperation( 5312): 	at dsf.a(PG:807)
E/HttpOperation( 5312): 	at fhk.a(PG:1126)
E/HttpOperation( 5312): 	at fhk.a(PG:908)
E/HttpOperation( 5312): 	at fhk.onPerformSync(PG:636)
E/HttpOperation( 5312): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/HttpOperation( 5312): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/HttpOperation( 5312): 	at ihi.a(PG:22)
E/HttpOperation( 5312): 	at kft.a(PG:91)
E/HttpOperation( 5312): 	at kfv.a(PG:62)
E/HttpOperation( 5312): 	... 8 more
E/HttpOperation( 5312): Caused by: gdi: User intervention required. Notification has been pushed.
E/HttpOperation( 5312): 	at gde.c(Unknown Source)
E/HttpOperation( 5312): 	at gde.b(Unknown Source)
E/HttpOperation( 5312): 	at ihi.a(PG:19)
E/HttpOperation( 5312): 	... 10 more
D/StatusBar( 1169): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,I/PhoneStatusBar( 1169): Icon Only
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
D/PanelView( 1169): There is/are notification(s) 
D/PanelView( 1169): There is/are notification(s) 
,I/GLSUser ( 1652): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,I/GLSUser ( 1652): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1652): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1652): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1652): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/BitmapFactory( 1652): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  875): uri = 14 selection = getSealedState
,D/SecContentProvider2(  875): mCursor = null
,D/SecContentProvider2(  875): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  875): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy(  875): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/StatusBar( 1169): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,I/PhoneStatusBar( 1169): Icon Only
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
D/PanelView( 1169): There is/are notification(s) 
,D/PanelView( 1169): There is/are notification(s) ,
,E/HttpOperation( 5312): [getmobileexperiments] Unexpected exception
E/HttpOperation( 5312): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 5312): 	at kfv.a(PG:65)
E/HttpOperation( 5312): 	at kff.u(PG:385)
E/HttpOperation( 5312): 	at kfb.a(PG:29)
E/HttpOperation( 5312): 	at kff.l(PG:132)
E/HttpOperation( 5312): 	at ieo.a(PG:43)
E/HttpOperation( 5312): 	at iep.a(PG:93)
E/HttpOperation( 5312): 	at fhn.a(PG:59)
E/HttpOperation( 5312): 	at lex.a(PG:85)
E/HttpOperation( 5312): 	at lex.b(PG:132)
E/HttpOperation( 5312): 	at fhk.a(PG:1146)
E/HttpOperation( 5312): 	at fhk.a(PG:908)
E/HttpOperation( 5312): 	at fhk.onPerformSync(PG:636)
E/HttpOperation( 5312): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/HttpOperation( 5312): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/HttpOperation( 5312): 	at ihi.a(PG:22)
E/HttpOperation( 5312): 	at kft.a(PG:91)
E/HttpOperation( 5312): 	at kfv.a(PG:62)
E/HttpOperation( 5312): 	... 12 more
E/HttpOperation( 5312): Caused by: gdi: User intervention required. Notification has been pushed.
E/HttpOperation( 5312): 	at gde.c(Unknown Source)
E/HttpOperation( 5312): 	at gde.b(Unknown Source)
E/HttpOperation( 5312): 	at ihi.a(PG:19)
E/HttpOperation( 5312): 	... 14 more
,E/ExperimentLoader( 5312): [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 5312): java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 5312): 	at kfv.a(PG:65)
E/ExperimentLoader( 5312): 	at kff.u(PG:385)
E/ExperimentLoader( 5312): 	at kfb.a(PG:29)
E/ExperimentLoader( 5312): 	at kff.l(PG:132)
E/ExperimentLoader( 5312): 	at ieo.a(PG:43)
E/ExperimentLoader( 5312): 	at iep.a(PG:93)
E/ExperimentLoader( 5312): 	at fhn.a(PG:59)
E/ExperimentLoader( 5312): 	at lex.a(PG:85)
E/ExperimentLoader( 5312): 	at lex.b(PG:132)
E/ExperimentLoader( 5312): 	at fhk.a(PG:1146)
E/ExperimentLoader( 5312): 	at fhk.a(PG:908)
E/ExperimentLoader( 5312): 	at fhk.onPerformSync(PG:636)
E/ExperimentLoader( 5312): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/ExperimentLoader( 5312): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/ExperimentLoader( 5312): 	at ihi.a(PG:22)
E/ExperimentLoader( 5312): 	at kft.a(PG:91)
E/ExperimentLoader( 5312): 	at kfv.a(PG:62)
E/ExperimentLoader( 5312): 	... 12 more
E/ExperimentLoader( 5312): Caused by: gdi: User intervention required. Notification has been pushed.
E/ExperimentLoader( 5312): 	at gde.c(Unknown Source)
E/ExperimentLoader( 5312): 	at gde.b(Unknown Source)
E/ExperimentLoader( 5312): 	at ihi.a(PG:19)
E/ExperimentLoader( 5312): 	... 14 more
,E/SQLiteLog( 1652): (10) POSIX Error : 11 SQLite Error : 3850
,I/GLSUser ( 1652): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,I/GLSUser ( 1652): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1652): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1652): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1652): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/BitmapFactory( 1652): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  875): uri = 14 selection = getSealedState
D/SecContentProvider2(  875): mCursor = null
,D/SecContentProvider2(  875): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  875): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy(  875): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/StatusBar( 1169): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,I/PhoneStatusBar( 1169): Icon Only
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
,D/PanelView( 1169): There is/are notification(s) 
,D/PanelView( 1169): There is/are notification(s) ,
,E/HttpOperation( 5312): [getaccountstatus] Unexpected exception
E/HttpOperation( 5312): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 5312): 	at kfv.a(PG:65)
E/HttpOperation( 5312): 	at kff.u(PG:385)
E/HttpOperation( 5312): 	at kfb.a(PG:29)
E/HttpOperation( 5312): 	at ixd.a(PG:248)
E/HttpOperation( 5312): 	at ixd.b(PG:206)
E/HttpOperation( 5312): 	at ixd.a(PG:175)
E/HttpOperation( 5312): 	at fig.a(PG:78)
E/HttpOperation( 5312): 	at lex.a(PG:85)
E/HttpOperation( 5312): 	at lex.b(PG:132)
E/HttpOperation( 5312): 	at fhk.a(PG:1146)
E/HttpOperation( 5312): 	at fhk.a(PG:908)
E/HttpOperation( 5312): 	at fhk.onPerformSync(PG:636)
E/HttpOperation( 5312): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/HttpOperation( 5312): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/HttpOperation( 5312): 	at ihi.a(PG:22)
E/HttpOperation( 5312): 	at kft.a(PG:91)
E/HttpOperation( 5312): 	at kfv.a(PG:62)
E/HttpOperation( 5312): 	... 12 more
E/HttpOperation( 5312): Caused by: gdi: User intervention required. Notification has been pushed.
E/HttpOperation( 5312): 	at gde.c(Unknown Source)
E/HttpOperation( 5312): 	at gde.b(Unknown Source)
E/HttpOperation( 5312): 	at ihi.a(PG:19)
E/HttpOperation( 5312): 	... 14 more
,E/EsSyncAdapterService( 5312): Sync failure
E/EsSyncAdapterService( 5312): java.io.IOException: Rpc failed
E/EsSyncAdapterService( 5312): 	at ixd.a(PG:348)
E/EsSyncAdapterService( 5312): 	at ixd.a(PG:248)
E/EsSyncAdapterService( 5312): 	at ixd.b(PG:206)
E/EsSyncAdapterService( 5312): 	at ixd.a(PG:175)
E/EsSyncAdapterService( 5312): 	at fig.a(PG:78)
E/EsSyncAdapterService( 5312): 	at lex.a(PG:85)
E/EsSyncAdapterService( 5312): 	at lex.b(PG:132)
E/EsSyncAdapterService( 5312): 	at fhk.a(PG:1146)
E/EsSyncAdapterService( 5312): 	at fhk.a(PG:908)
E/EsSyncAdapterService( 5312): 	at fhk.onPerformSync(PG:636)
E/EsSyncAdapterService( 5312): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/EsSyncAdapterService( 5312): Caused by: java.io.IOException: Cannot obtain authentication token
E/EsSyncAdapterService( 5312): 	at kfv.a(PG:65)
E/EsSyncAdapterService( 5312): 	at kff.u(PG:385)
E/EsSyncAdapterService( 5312): 	at kfb.a(PG:29)
E/EsSyncAdapterService( 5312): 	... 10 more
E/EsSyncAdapterService( 5312): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/EsSyncAdapterService( 5312): 	at ihi.a(PG:22)
E/EsSyncAdapterService( 5312): 	at kft.a(PG:91)
E/EsSyncAdapterService( 5312): 	at kfv.a(PG:62)
E/EsSyncAdapterService( 5312): 	... 12 more
E/EsSyncAdapterService( 5312): Caused by: gdi: User intervention required. Notification has been pushed.
E/EsSyncAdapterService( 5312): 	at gde.c(Unknown Source)
E/EsSyncAdapterService( 5312): 	at gde.b(Unknown Source)
E/EsSyncAdapterService( 5312): 	at ihi.a(PG:19)
E/EsSyncAdapterService( 5312): 	... 14 more
,D/ConnectivityService(  875): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SyncManager(  875): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, PERIODIC, currentRunTime 248766, reason: Periodic, SyncResult: stats [ numIoExceptions: 2]
,D/ConnectivityService(  875): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  875): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SecContentProvider2(  875): uri = 11 selection = getMyKnoxAdmin
D/SecContentProvider2(  875): mCursor = null
,E/SMD     (  287): DCD ON
,E/SQLiteLog( 1652): (10) POSIX Error : 11 SQLite Error : 3850
,I/PowerManagerService(  875): [PWL] Off : 140s ago
,D/SSRM:m  (  875): SIOP:: AP = 300, PST = 310, CUR = 300
,E/SMD     (  287): DCD ON
,E/SMD     (  287): DCD ON
,D/BatteryService(  875): level:100, scale:100, status:5, health:2, present:true, voltage: 4383, temperature: 299, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  875): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  875): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  875):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  875): Plugged
,I/MotionRecognitionService(  875): setPowerConnected  = true
,D/BatteryService(  875): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1169): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1169): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1169):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3249): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3249): Disconnected process message: 10
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  287): DCD ON
,E/Watchdog(  875): !@Sync 9
,E/SMD     (  287): DCD ON
,D/SSRM:m  (  875): SIOP:: AP = 300, PST = 308, CUR = 300
,E/SMD     (  287): DCD ON
,W/ContextImpl(  875): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  287): DCD ON
,I/ServiceManager(  349): Waiting for service AtCmdFwd...
,D/BatteryService(  875): level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 298, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  875): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  875): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  875):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  875): Plugged
,I/MotionRecognitionService(  875): setPowerConnected  = true
,D/BatteryService(  875): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1169): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1169): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1169):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3249): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3249): Disconnected process message: 10
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/ServiceManager(  349): Waiting for service AtCmdFwd...
,I/ServiceManager(  349): Waiting for service AtCmdFwd...
,E/SMD     (  287): DCD ON
,I/ServiceManager(  349): Waiting for service AtCmdFwd...
,I/ServiceManager(  349): Waiting for service AtCmdFwd...
,D/SSRM:m  (  875): SIOP:: AP = 300, PST = 306, CUR = 300
,W/Atfwd_Sendcmd(  349): AtCmdFwd service not published, waiting... retryCnt : 5
,E/SMD     (  287): DCD ON
,E/SMD     (  287): DCD ON
,V/AlarmManager(  875): waitForAlarm result :4
,D/ConnectivityService(  875): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/SMD     (  287): DCD ON
,D/SSRM:m  (  875): SIOP:: AP = 300, PST = 305, CUR = 300
,E/SMD     (  287): DCD ON
,E/SMD     (  287): DCD ON
,D/TimaService(  875): TIMA: TimaService scheduler is intialized. 
,D/TimaService(  875): TimaServiceHandler.handleMessage what =1
,D/TimaService(  875): TIMA: checkEvent, operation: 50000 subject: 10000
,I/TLC_TIMA_PKM_initialize(  875): initializing...
,I/TLC_TIMA_PKM_initialize(  875): root = /firmware/image, root_strlen = 15
,I/TLC_TIMA_PKM_initialize(  875): process = tima_pkm, process_strlen = 8
,I/TZ: qc_tlc_communication(  875): root = /firmware/image, root_len = 15
,I/TZ: qc_tlc_communication(  875): process = tima_pkm, process_strlen = 8
,I/TZ: qc_tlc_communication(  875): aligned max_sendmsg_size = 262208 = 0x40040
,I/TZ: qc_tlc_communication(  875): aligned max_recvmsg_size = 262208 = 0x40040
,I/TZ: qc_tlc_communication(  875): max_message_size = 524416 = 0x80080
,D/QSEECOMAPI: (  875): QSEECom_get_handle sb_length = 0x80080
,D/QSEECOMAPI: (  875): App is not loaded in QSEE
,D/QSEECOMAPI: (  875): Loaded image: APP id = 3
,I/TZ: qc_tlc_communication(  875): TIMA: path = /firmware/image, fname = tima_pkm, tzapp is loaded
,I/TLC_TIMA_PKM_initialize(  875): Trustlet response is completed
,W/ContextImpl(  875): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  287): DCD ON
,E/Watchdog(  875): !@Sync 10
,I/TLC_TIMA_PKM_measure_kernel(  875): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel(  875): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService(  875): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService(  875): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,E/SMD     (  287): DCD ON
,I/PowerManagerService(  875): [PWL] Off : 180s ago
,D/SSRM:m  (  875): SIOP:: AP = 300, PST = 304, CUR = 300
,E/SMD     (  287): DCD ON
,E/SMD     (  287): DCD ON
,I/Atfwd_Sendcmd(  349): AtCmdFwd service not ready - Exhausted retry attempts - :6
I/Atfwd_Daemon(  349): result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,E/SMD     (  287): DCD ON
,D/SSRM:m  (  875): SIOP:: AP = 300, PST = 303, CUR = 300
,E/SMD     (  287): DCD ON
,V/AlarmManager(  875): waitForAlarm result :8
,E/SMD     (  287): DCD ON
,W/ContextImpl(  875): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,V/AlarmManager(  875): waitForAlarm result :4
,D/KeyguardUpdateMonitor( 1169): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1169): handleTimeUpdate
,D/KeyguardEffectViewController( 1169): onReceive action : android.intent.action.TIME_TICK
,I/KeyguardEffectViewController( 1169): *** don't update sliding image ***
,D/BatteryService(  875): level:100, scale:100, status:5, health:2, present:true, voltage: 4386, temperature: 298, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  875): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
D/BatteryService(  875): stay LED for fully charged
,D/BatteryService(  875): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1169): received broadcast android.intent.action.BATTERY_CHANGED
,V/HeadsetService( 3249): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3249): Disconnected process message: 10
,D/MotionRecognitionService(  875):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
I/MotionRecognitionService(  875): Plugged
,I/MotionRecognitionService(  875): setPowerConnected  = true
,D/STATUSBAR-PhoneStatusBar( 1169):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/KeyguardUpdateMonitor( 1169): handleBatteryUpdate
,D/DateView( 1169): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1169): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/ConnectivityService(  875): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  875): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/BooksSync( 7308): Starting books sync, d
,D/ConnectivityService(  875): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,V/GLSActivity( 1652): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/AlarmManager(  875): waitForAlarm result :4
,E/ActivityManager(  875): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  875): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  875): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  875): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 8620): MountEmulatedStorage()
,E/Zygote  ( 8620): v2
,I/libpersona( 8620): KNOX_SDCARD checking this for 10081
I/libpersona( 8620): KNOX_SDCARD not a persona
,I/ActivityManager(  875): Start proc com.blurb.checkout for broadcast com.blurb.checkout/.RebootReceiver: pid=8620 uid=10081 gids={50081, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/SELinux ( 8620): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 8620): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 8620): [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
,I/GLSUser ( 1652): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
I/GLSUser ( 1652): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1652): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1652): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1652): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/BitmapFactory( 1652): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/TimaKeyStoreProvider( 8620): TimaSignature is unavailable
,D/ActivityThread( 8620): Added TimaKeyStore provider
D/SecContentProvider2(  875): uri = 14 selection = getSealedState
D/SecContentProvider2(  875): mCursor = null
D/SecContentProvider2(  875): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  875): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
V/ApplicationPolicy(  875): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,W/GLSActivity( 1652): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1652): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1652): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1652): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1652): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1652): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1652): 	at android.os.Binder.execTransact(Binder.java:446)
,E/BooksAccountManager( 7308): Authentication error
E/BooksAccountManager( 7308): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 7308): android.accounts.AccountManager.convertErrorToException(AccountManager.java:1893)
E/HttpHelper( 7308): null auth token
,I/qtaguid ( 7308): Tagging socket 34 with tag 10000000000{256,0} uid -1, pid: 7308, getuid(): 10082
,D/StatusBar( 1169): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,D/ResourcesManager( 8620): creating new AssetManager and set to /system/app/Blurb/Blurb.apk
,I/PhoneStatusBar( 1169): Icon Only
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
,D/PanelView( 1169): There is/are notification(s) 
D/PanelView( 1169): There is/are notification(s) 
,I/qtaguid ( 7308): Untagging socket 34
,W/ApiaryClient( 7308): Error response from books API: {
W/ApiaryClient( 7308):  "error": {
W/ApiaryClient( 7308):   "errors": [
W/ApiaryClient( 7308):    {
W/ApiaryClient( 7308):     "domain": "global",
W/ApiaryClient( 7308):     "reason": "required",
W/ApiaryClient( 7308):     "message": "Login Required",
W/ApiaryClient( 7308):     "locationType": "header",
W/ApiaryClient( 7308):     "location": "Authorization"
W/ApiaryClient( 7308):    }
W/ApiaryClient( 7308):   ],
W/ApiaryClient( 7308):   "code": 401,
W/ApiaryClient( 7308):   "message": "Login Required"
W/ApiaryClient( 7308):  }
W/ApiaryClient( 7308): }
,W/ApiaryClient( 7308): errCount = 1: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 7308): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3DS0HXd4TFLU4&nonce=7011164415978981060&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 7308): Headers suppressed
,D/ConnectivityService(  875): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/SMD     (  287): DCD ON
,V/GLSActivity( 1652): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1652): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
,I/GLSUser ( 1652): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1652): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1652): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1652): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/BitmapFactory( 1652): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  875): uri = 14 selection = getSealedState
,D/SecContentProvider2(  875): mCursor = null
D/SecContentProvider2(  875): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  875): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy(  875): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/StatusBar( 1169): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,I/PhoneStatusBar( 1169): Icon Only
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
D/PanelView( 1169): There is/are notification(s) 
,D/PanelView( 1169): There is/are notification(s) 
,W/GLSActivity( 1652): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1652): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1652): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1652): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1652): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1652): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1652): 	at android.os.Binder.execTransact(Binder.java:446)
,E/BooksAccountManager( 7308): Authentication error
E/BooksAccountManager( 7308): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 7308): android.accounts.AccountManager.convertErrorToException(AccountManager.java:1893)
,E/HttpHelper( 7308): null auth token
,I/qtaguid ( 7308): Tagging socket 34 with tag 10000000000{256,0} uid -1, pid: 7308, getuid(): 10082
,I/qtaguid ( 7308): Untagging socket 34
,W/ApiaryClient( 7308): Error response from books API: {,
W/ApiaryClient( 7308):  "error": {
W/ApiaryClient( 7308):   "errors": [
W/ApiaryClient( 7308):    {
W/ApiaryClient( 7308):     "domain": "global",
W/ApiaryClient( 7308):     "reason": "required",
W/ApiaryClient( 7308):     "message": "Login Required",
W/ApiaryClient( 7308):     "locationType": "header",
W/ApiaryClient( 7308):     "location": "Authorization"
W/ApiaryClient( 7308):    }
W/ApiaryClient( 7308):   ],
W/ApiaryClient( 7308):   "code": 401,
W/ApiaryClient( 7308):   "message": "Login Required"
W/ApiaryClient( 7308):  }
W/ApiaryClient( 7308): }
,W/ApiaryClient( 7308): errCount = 2: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 7308): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3DS0HXd4TFLU4&nonce=7011164415978981060&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 7308): Headers suppressed
,D/ConnectivityService(  875): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,V/GLSActivity( 1652): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1652): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
,I/GLSUser ( 1652): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1652): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1652): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1652): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/BitmapFactory( 1652): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  875): uri = 14 selection = getSealedState
,D/SecContentProvider2(  875): mCursor = null
D/SecContentProvider2(  875): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  875): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy(  875): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/StatusBar( 1169): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,I/PhoneStatusBar( 1169): Icon Only
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
D/PanelView( 1169): There is/are notification(s) 
,D/PanelView( 1169): There is/are notification(s) 
,W/GLSActivity( 1652): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1652): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1652): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1652): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1652): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1652): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1652): 	at android.os.Binder.execTransact(Binder.java:446)
,E/BooksAccountManager( 7308): Authentication error
E/BooksAccountManager( 7308): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 7308): android.accounts.AccountManager.convertErrorToException(AccountManager.java:1893)
,E/HttpHelper( 7308): null auth token
,I/qtaguid ( 7308): Tagging socket 34 with tag 10000000000{256,0} uid -1, pid: 7308, getuid(): 10082
,I/qtaguid ( 7308): Untagging socket 34
,W/ApiaryClient( 7308): Error response from books API: {
W/ApiaryClient( 7308):  "error": {
W/ApiaryClient( 7308):   "errors": [
W/ApiaryClient( 7308):    {
W/ApiaryClient( 7308):     "domain": "global",
W/ApiaryClient( 7308):     "reason": "required",
W/ApiaryClient( 7308):     "message": "Login Required",
W/ApiaryClient( 7308):     "locationType": "header",
W/ApiaryClient( 7308):     "location": "Authorization"
W/ApiaryClient( 7308):    }
W/ApiaryClient( 7308):   ],
W/ApiaryClient( 7308):   "code": 401,
W/ApiaryClient( 7308):   "message": "Login Required"
W/ApiaryClient( 7308):  }
W/ApiaryClient( 7308): }
,W/ApiaryClient( 7308): errCount = 3: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 7308): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3DS0HXd4TFLU4&nonce=7011164415978981060&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 7308): Headers suppressed
,D/ConnectivityService(  875): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SSRM:m  (  875): SIOP:: AP = 300, PST = 302, CUR = 300
,E/SMD     (  287): DCD ON
,E/BooksSync( 7308): Soft error
E/BooksSync( 7308): com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
E/BooksSync( 7308): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3DS0HXd4TFLU4&nonce=7011164415978981060&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
E/BooksSync( 7308): Headers suppressed
E/BooksSync( 7308): 
E/BooksSync( 7308): com.google.android.apps.books.net.HttpHelper.wrapExceptionBasedOnStatus(HttpHelper.java:212)
,E/BooksSync( 7308): Sync error
E/BooksSync( 7308): com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
E/BooksSync( 7308): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3DS0HXd4TFLU4&nonce=7011164415978981060&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
E/BooksSync( 7308): Headers suppressed
E/BooksSync( 7308): 
E/BooksSync( 7308): com.google.android.apps.books.net.HttpHelper.wrapExceptionBasedOnStatus(HttpHelper.java:212)
,I/BooksSync( 7308): Finished books sync
,D/ConnectivityService(  875): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/ActivityManager(  875): Killing 7277:com.sec.android.app.camera/u0a154 (adj 15): bgCount ##41
,D/SyncManager(  875): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 311444, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,D/ConnectivityService(  875): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,W/libprocessgroup(  875): failed to open /acct/uid_10154/pid_7277/cgroup.procs: No such file or directory
,D/ConnectivityService(  875): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/ServiceManager(  349): Waiting for service AtCmdFwd...
,I/art     (  875): Explicit concurrent mark sweep GC freed 56272(3MB) AllocSpace objects, 62(1707KB) LOS objects, 30% free, 36MB/52MB, paused 3.191ms total 161.071ms
,D/SecContentProvider2(  875): uri = 11 selection = getMyKnoxAdmin
,D/SecContentProvider2(  875): mCursor = null
,I/ServiceManager(  349): Waiting for service AtCmdFwd...
,I/ServiceManager(  349): Waiting for service AtCmdFwd...
,E/SMD     (  287): DCD ON
,I/ServiceManager(  349): Waiting for service AtCmdFwd...
,I/ServiceManager(  349): Waiting for service AtCmdFwd...
,W/Atfwd_Sendcmd(  349): AtCmdFwd service not published, waiting... retryCnt : 1
,D/BatteryService(  875): level:100, scale:100, status:5, health:2, present:true, voltage: 4383, temperature: 298, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  875): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,E/SMD     (  287): DCD ON
,D/BatteryService(  875): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  875):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  875): Plugged
,I/MotionRecognitionService(  875): setPowerConnected  = true
,D/BatteryService(  875): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1169): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1169): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1169):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3249): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3249): Disconnected process message: 10
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog(  875): !@Sync 11
,E/SMD     (  287): DCD ON
,D/SSRM:m  (  875): SIOP:: AP = 300, PST = 301, CUR = 300
,I/ServiceManager(  349): Waiting for service AtCmdFwd...
,I/ServiceManager(  349): Waiting for service AtCmdFwd...
,E/SMD     (  287): DCD ON,
,I/ServiceManager(  349): Waiting for service AtCmdFwd...

```
