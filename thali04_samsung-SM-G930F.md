#### Test 8504691174f7534_thali04_samsung-SM-G930F Logs


```
--------- beginning of system
,09-15 12:02:55.414  3399  5991 D SSRM:n  : SIOP:: AP = 290, PST = 305 (W:6), CP = 253, CUR = 153, LCD = 57
--------- beginning of main
09-15 12:02:55.894  9358  9358 I FIPS_bssl: FIPS approved mode (1) | 9358 | app_process
09-15 12:02:55.894  9358  9358 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
09-15 12:02:55.904  9358  9358 D AndroidRuntime: CheckJNI is OFF
09-15 12:02:55.904  9358  9358 D AndroidRuntime: readGMSProperty: start
09-15 12:02:55.904  9358  9358 D AndroidRuntime: readGMSProperty: already setted!!
09-15 12:02:55.904  9358  9358 D AndroidRuntime: propertySet: couldn't set property (it is from app)
09-15 12:02:55.904  9358  9358 D AndroidRuntime: readGMSProperty: could not set the property(default)!!
09-15 12:02:55.904  9358  9358 D AndroidRuntime: readGMSProperty: end
09-15 12:02:55.904  9358  9358 D AndroidRuntime: addProductProperty: start
09-15 12:02:55.924  9358  9358 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
09-15 12:02:55.944  9358  9358 I Radio-JNI: register_android_hardware_Radio DONE
09-15 12:02:55.944  9358  9358 E AffinityControl: AffinityControl: registerfunction enter
09-15 12:02:55.954  9358  9358 D AndroidRuntime: Calling main entry com.android.commands.am.Am
09-15 12:02:55.984  3399  4898 D VirtualScreenPolicy: applyVirtualScreenAttrs attrs=VirtualScreenAttrs{mDisplayId=0, mBaseDisplayId=0, mBaseActivity=false}
09-15 12:02:55.984  3399  4898 W ResourcesManager: getTopLevelResources: /data/app/com.test.thalitest-1/base.apk / 1.0 running in null rsrc of package com.test.thalitest
09-15 12:02:56.004  3399  4898 D ResourcesManager: For user 0 new overlays fetched Null
09-15 12:02:56.004  3399  4898 D GameManagerService: identifyGamePackage. com.test.thalitest
09-15 12:02:56.004  3399  4898 D MultiWindowPolicy: Gamemode - return 0,  when calling  identifyForegroundApp(com.test.thalitest)
09-15 12:02:56.014  3399  4898 D CustomFrequencyManagerService: acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1872000  uid : 1000  pid : 3399  pkgName : ACTIVITY_RESUME_BOOSTER@3
09-15 12:02:56.014  3399  4898 D ActivityManager: mDVFSHelper.acquire()
09-15 12:02:56.014  3399  4898 D FocusedStackFrame: Set to : 0
09-15 12:02:56.014  3399  4898 V WindowManager: addAppToken: AppWindowToken{d0f62b8fa token=Token{6e21f25 ActivityRecord{e01e71c u0 com.test.thalitest/.MainActivity t10}}} to stack=2 task=10 at 0
09-15 12:02:56.014  3399  4898 D InputDispatcher: Focused application set to: xxxx
09-15 12:02:56.014  4280  4280 D Launcher: onPause, Launcher: 27478326
09-15 12:02:56.014  4280  4280 D Launcher.HomeView: onPause
09-15 12:02:56.014  4280  4280 D Launcher.Workspace: exitWidgetResizeMode. isClearResizeFrame is false
09-15 12:02:56.014  3399  4898 D InputDispatcher: Focus left window: 4280
09-15 12:02:56.014  9358  9358 D AndroidRuntime: Shutting down VM
09-15 12:02:56.024  3399  3562 I InjectionManager: Inside getClassLibPath caller 
09-15 12:02:56.024  3399  3562 D SecWifiDisplayUtil: Metadata value : SecSettings2
09-15 12:02:56.024  3399  3562 D ViewRootImpl: #1 mView = com.android.internal.policy.PhoneWindow$DecorView{dcb6d52 V.E...... R.....ID 0,0-0,0}
09-15 12:02:56.024  3399  3562 D ISSUE_DEBUG: InputChannelName : df34120 Starting com.test.thalitest
09-15 12:02:56.024  3399  3562 D PointerIcon: setMouseIconStyle1 pointerType: 1001 iconType:101 flag:0 pid:3399 uid:1000
09-15 12:02:56.024  3399  3562 D PointerIcon: setMouseCustomIcon IconType is same.101
09-15 12:02:56.024  3006  3006 I SurfaceFlinger: id=20 createSurf (1440x2560),1 flag=404, uhalitest
09-15 12:02:56.034  9367  9367 E Zygote  : v2
09-15 12:02:56.034  9367  9367 I libpersona: KNOX_SDCARD checking this for 10171
09-15 12:02:56.034  9367  9367 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0013
09-15 12:02:56.034  9367  9367 I libpersona: KNOX_SDCARD not a persona
09-15 12:02:56.034  9367  9367 E Zygote  : accessInfo : 0
09-15 12:02:56.034  9367  9367 W SELinux : SELinux: seapp_context_lookup: seinfo=default, level=s0:c512,c768, pkgname=com.test.thalitest 
09-15 12:02:56.034  3399  3562 D ViewRootImpl: MSG_RESIZED_REPORT: ci=Rect(0, 96 - 0, 0) vi=Rect(0, 96 - 0, 0) or=1
09-15 12:02:56.034  3399  3996 I ActivityManager: Start proc 9367:com.test.thalitest/u0a171 for activity com.test.thalitest/.MainActivity
09-15 12:02:56.034  3399  3853 D NetworkPolicy: isUidForegroundLocked: 10171, mScreenOn: true, uidstate: -1, mProxSensorScreenOff: false
09-15 12:02:56.034  4411  4422 W SearchService: Abort, client detached.
09-15 12:02:56.044  4411  9343 I DeviceStateChecker: DeviceStateChecker cancelled
09-15 12:02:56.044  4411  4411 I MicroDetector: Keeping mic open: false
09-15 12:02:56.044  4411  4411 I MicrophoneInputStream: mic_close com.google.android.apps.gsa.speech.audio.ae@679d22a
09-15 12:02:56.044  4411  9345 E AudioRecord-JNI: Error -4 during AudioRecord native read
09-15 12:02:56.054  3399  3562 V WindowStateAnimator: Finishing drawing window Window{df34120 u0 d0 Starting com.test.thalitest}: mDrawState=DRAW_PENDING
09-15 12:02:56.054  9367  9367 D TimaKeyStoreProvider: TimaSignature is unavailable
09-15 12:02:56.054  9367  9367 D ActivityThread: Added TimaKeyStore provider
09-15 12:02:56.054  3159  3159 I APM::AudioPolicyManager: stopInput() input 27
09-15 12:02:56.054  3399  4397 V WindowOrientationListener: setCurrentAppOrientation :-1
09-15 12:02:56.054  3399  4397 V WindowOrientationListener: OrientationSensorJudge.getProposedRotation, Rotation: -1
09-15 12:02:56.054  3399  4397 V WindowManager: rotationForOrientationLw(orient=-1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false mMobileKeyboardEnabled=false displayId=0
09-15 12:02:56.054  3399  4397 V WindowOrientationListener: OrientationSensorJudge.getProposedRotation, Rotation: -1
09-15 12:02:56.054  3399  4397 D ActivityManager:  Launching com.test.thalitest, updated priority
09-15 12:02:56.054  4411  9293 I MicroRecognitionRunner: Stopping hotword detection.
09-15 12:02:56.054  4411  9344 I MicroRecognitionRunner: Detection finished
09-15 12:02:56.054  3006  3006 D libEGL  : eglInitialize EGLDisplay = 0x7fc83bb698
09-15 12:02:56.064  3159  9347 I audio_hw_primary: do_in_standby : in->standby 0
09-15 12:02:56.064  3399  3399 D GameManagerService: NotifyRunnable. pkg: com.test.thalitest, type: 4, isMinimized: false, isTunableApp: false
09-15 12:02:56.064  3159  9347 V audio_hw_primary: select_devices output_scenario:-1 input_scenario:-1 out_snd_device 0x0 in_snd_device:0x0
09-15 12:02:56.064  3159  9347 I audio_route: 
09-15 12:02:56.064  3159  9347 I audio_route: > audio_route_reset :
09-15 12:02:56.064  3159  9347 I audio_route: 
09-15 12:02:56.064  3159  9347 I audio_route: > audio_route_update_mixer : +
09-15 12:02:56.074  3399  3537 V MARsPolicyManager: updatePackagesScore PackageInfo name -- com.test.thalitest
09-15 12:02:56.074  9367  9367 W ResourcesManager: getTopLevelResources: /data/app/com.test.thalitest-1/base.apk / 1.0 running in com.test.thalitest rsrc of package com.test.thalitest
09-15 12:02:56.074  3399  3469 I InjectionManagerService -AppFeature: getCoreFeaturePkgList :[]
09-15 12:02:56.074  9367  9367 I InjectionManager: Inside getClassLibPath + mLibMap{0=, 1=}
09-15 12:02:56.084  3159  9347 I audio_route: > audio_route_update_mixer : changed(5) -
09-15 12:02:56.084  3159  9347 I audio_hw_primary: select_devices - 
09-15 12:02:56.084  3159  3650 V audio_hw_primary: stop_voice_note_recording
09-15 12:02:56.084  3159  3650 E audio_hw_primary: adev_close_input_stream, set jack_in to null
09-15 12:02:56.084  3399  3537 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{121b95 u0 update-hint qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{175dc82 4411:com.google.android.googlequicksearchbox:search/u0a68}
09-15 12:02:56.084  9367  9367 D ResourcesManager: For user 0 new overlays fetched Null
09-15 12:02:56.084  3399  3538 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=Window{df34120 u0 d0 Starting com.test.thalitest}
09-15 12:02:56.084  3006  3017 D libEGL  : eglTerminate EGLDisplay = 0x7f87bfee78
09-15 12:02:56.084  3006  3015 I SurfaceFlinger: Modify Choreographer's phase offset to 0
09-15 12:02:56.084  3006  3900 I SurfaceFlinger: Modify SurfaceFlinger's phase offset to 0
09-15 12:02:56.084  3399  5991 D GameManagerService: identifyGamePackage. com.test.thalitest
09-15 12:02:56.084  3399  5991 D GameManagerService: identifyGamePackage. com.test.thalitest
09-15 12:02:56.094  9367  9367 I InjectionManager: Inside getClassLibPath caller 
09-15 12:02:56.104  3399  5991 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
09-15 12:02:56.104  3399  5991 D GameManagerService: identifyGamePackage. com.test.thalitest
09-15 12:02:56.104  9367  9367 D InjectionManager: InjectionManager
09-15 12:02:56.104  9367  9367 D InjectionManager: fillFeatureStoreMap com.test.thalitest
09-15 12:02:56.104  9367  9367 I InjectionManager: Constructor com.test.thalitest, Feature store :{}
09-15 12:02:56.104  9367  9367 I InjectionManager: featureStore :{}
09-15 12:02:56.104  3399  5991 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
09-15 12:02:56.104  3399  5991 D GameManagerService: identifyGamePackage. com.test.thalitest
09-15 12:02:56.104  3399  5991 D GameManagerService: identifyGamePackage. com.test.thalitest
09-15 12:02:56.104  9367  9367 W ResourcesManager: getTopLevelResources: /data/app/com.test.thalitest-1/base.apk / 1.0 running in com.test.thalitest rsrc of package com.test.thalitest
09-15 12:02:56.114  9367  9367 D ContextRelationManager: ContextRelationManager() : FEATURE_ENABLED=true
09-15 12:02:56.114  9367  9367 D RelationGraph: garbageCollect()
09-15 12:02:56.114  9367  9367 W ResourcesManager: getTopLevelResources: /data/app/com.test.thalitest-1/base.apk / 1.0 running in com.test.thalitest rsrc of package com.test.thalitest
09-15 12:02:56.124  9367  9367 I WebViewFactory: Loading com.google.android.webview version 49.0.2623.105 (code 262310550)
09-15 12:02:56.144  9367  9367 W ResourcesManager: getTopLevelResources: /system/app/WebViewGoogle/WebViewGoogle.apk / 1.0 running in com.test.thalitest rsrc of package com.google.android.webview
09-15 12:02:56.144  9367  9367 D ResourcesManager: For user 0 new overlays fetched Null
09-15 12:02:56.144  9367  9367 I InjectionManager: Inside getClassLibPath caller 
09-15 12:02:56.144  9367  9367 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
09-15 12:02:56.184  9367  9367 I cr_LibraryLoader: Time to load native libraries: 20 ms (timestamps 8591-8611)
09-15 12:02:56.184  9367  9367 I cr_LibraryLoader: Expected native library version number "49.0.2623.105", actual native library version number "49.0.2623.105"
09-15 12:02:56.214  9367  9381 W System.err: remove failed: ENOENT (No such file or directory) : /data/user/0/com.test.thalitest/shared_prefs/WebViewChromiumPrefs.xml.bak
09-15 12:02:56.214  9367  9367 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {42f6d5e}
09-15 12:02:56.214  9367  9367 I cr_LibraryLoader: Expected native library version number "49.0.2623.105", actual native library version number "49.0.2623.105"
,09-15 12:02:56.234  9367  9367 I chromium: [INFO:library_loader_hooks.cc(144)] Chromium logging enabled: level = 0, default verbosity = 0
,09-15 12:02:56.244  9367  9367 I cr_BrowserStartup: Initializing chromium process, singleProcess=true
,09-15 12:02:56.334  3399  3876 D MdnieScenarioControlService:  packageName : com.test.thalitest    className : com.test.thalitest.MainActivity
,09-15 12:02:56.334  9367  9367 D libEGL  : eglInitialize EGLDisplay = 0xff9d2eec
,09-15 12:02:56.374  3399  4898 D ActivityManager: The following uid has registered to recieve broadcast for proxy related updates 10171
,09-15 12:02:56.374  3399  4898 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:845 com.android.server.am.ActivityManagerService.requestKnoxVpnToSendProxyBroadcast:29734 com.android.server.am.ActivityManagerService.registerReceiver:22599 android.app.ActivityManagerNative.onTransact:431 com.android.server.am.ActivityManagerService.onTransact:3990 
,09-15 12:02:56.394  3399  3853 D NetworkPolicy: isUidForegroundLocked: 10019, mScreenOn: true, uidstate: 2, mProxSensorScreenOff: false
,09-15 12:02:56.424  9367  9367 D cr_Ime  : [InputMethodManagerWrapper.java:27] Constructor
,09-15 12:02:56.424  9367  9367 W cr_AwContents: onDetachedFromWindow called when already detached. Ignoring
,09-15 12:02:56.424  9367  9367 D cr_Ime  : [InputMethodManagerWrapper.java:56] isActive: false
,09-15 12:02:56.434  3399  3876 I MdnieScenarioControlService: mGameModeLauncher : false
,09-15 12:02:56.434  3399  3876 I MdnieScenarioControlService: setUIMode
,09-15 12:02:56.444  9367  9367 D SystemWebViewEngine: CordovaWebView is running on device made by: samsung
,09-15 12:02:56.464  3006  3900 I SurfaceFlinger: id=19 Removed MauncherAct (4/10)
,09-15 12:02:56.464  3006  3015 I SurfaceFlinger: id=19 Removed MauncherAct (-2/10)
,09-15 12:02:56.464  3944  3944 D ImageWallpaper: onVisibilityChanged:false
,09-15 12:02:56.464  3944  3944 D ImageWallpaper: drawFrame:false rotation:0 mLastRotation:0
09-15 12:02:56.464  3944  3944 D ImageWallpaper: drawFrame:[frame.width()]2240[frame.height()]2560
09-15 12:02:56.464  3944  3944 D ImageWallpaper: Suppressed drawFrame since redraw is not needed and offsets have not changed.
,09-15 12:02:56.464  9367  9367 D Activity: performCreate Call Injection manager
,09-15 12:02:56.464  9367  9367 I InjectionManager: dispatchOnViewCreated > Target : com.test.thalitest.MainActivity isFragment :false
,09-15 12:02:56.474  9367  9367 D SecWifiDisplayUtil: Metadata value : SecSettings2
,09-15 12:02:56.474  9367  9367 D ViewRootImpl: #1 mView = com.android.internal.policy.PhoneWindow$DecorView{1f26c I.E...... R.....ID 0,0-0,0}
,09-15 12:02:56.474  3006  3006 D libEGL  : eglTerminate EGLDisplay = 0x7fc83bb7b8
,09-15 12:02:56.474  9367  9418 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
,09-15 12:02:56.484  3399  3969 D ISSUE_DEBUG: InputChannelName : 960f07b com.test.thalitest/com.test.thalitest.MainActivity
,09-15 12:02:56.484  3399  4410 D ActivityManager: post active user change for 0 fullscreen true isFloatingActivity() false isHomeActivity() false
09-15 12:02:56.484  3399  4410 D KnoxTimeoutHandler: postActiveUserChange [MsgParam] userId: 0 fullscreen is true showWhenlocked is false
09-15 12:02:56.484  3399  3399 D KnoxTimeoutHandler: handleActiveUserChange [MsgParam] userId: 0 fullscreen is true showWhenlocked is false
,09-15 12:02:56.484  3399  3399 I KnoxTimeoutHandler: Shared devices show user statefalse
,09-15 12:02:56.484  9367  9381 W System.err: remove failed: ENOENT (No such file or directory) : /data/user/0/com.test.thalitest/shared_prefs/com.test.thalitest_preferences.xml.bak
,09-15 12:02:56.494  9367  9367 D ConnectivityManager: requestNetwork; getAppId(CallingUid) : 10171, CallingPid : 9367
,09-15 12:02:56.504  3399  4397 D ConnectivityService: listenForNetwork for Listen from uid/pid:10171/9367 for NetworkRequest [ id=7, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,09-15 12:02:56.504  3399  3864 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 502]
09-15 12:02:56.504  3399  3864 D ConnectivityService:  network has: NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{502}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::4e66:41ff:fea9:1541/64,192.168.1.137/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains:  MTU: 0 TcpBufferSizes: 524288,1048576,2097120,524288,1048576,4194240}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN&VALIDATED LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -53]}  Score{60}  everValidated{true}  lastValidated{true}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,09-15 12:02:56.504  3399  3864 D ConnectivityService: Network NetworkAgentInfo [WIFI () - 502] was already satisfying request 1. No change.
,09-15 12:02:56.504  3399  3864 D ConnectivityService:   checking if request is: NetworkRequest [ id=3, legacyType=-1, [] ] satisfies: true nri.isRequest: false
,09-15 12:02:56.504  3399  3853 D NetworkPolicy: isUidForegroundLocked: 10019, mScreenOn: true, uidstate: 6, mProxSensorScreenOff: false
,09-15 12:02:56.514  3399  3864 D ConnectivityService:   checking if request is: NetworkRequest [ id=7, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] satisfies: true nri.isRequest: false
,09-15 12:02:56.514  9367  9367 D SecWifiDisplayUtil: Metadata value : SecSettings2
,09-15 12:02:56.514  3399  3864 D ConnectivityService:   checking if request is: NetworkRequest [ id=6, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] satisfies: true nri.isRequest: false
,09-15 12:02:56.514  3399  3864 D ConnectivityService:   checking if request is: NetworkRequest [ id=5, legacyType=-1, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] satisfies: true nri.isRequest: false
,09-15 12:02:56.524  3399  3864 D ConnectivityService:   checking if request is: NetworkRequest [ id=4, legacyType=-1, [ Transports: CELLULAR Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] satisfies: false nri.isRequest: false
,09-15 12:02:56.524  3399  3864 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=7, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,09-15 12:02:56.524  3006  3006 I SurfaceFlinger: id=21 createSurf (1x1),1 flag=404, NainActivit
,09-15 12:02:56.524  3399  4235 D InputDispatcher: Focus entered window: 9367
,09-15 12:02:56.524  3399  3562 D PointerIcon: setMouseIconStyle1 pointerType: 1001 iconType:101 flag:0 pid:3399 uid:1000
09-15 12:02:56.524  3399  3562 D PointerIcon: setMouseCustomIcon IconType is same.101
09-15 12:02:56.524  9367  9418 D libEGL  : eglInitialize EGLDisplay = 0xdc77f7c4
09-15 12:02:56.524  9367  9418 I OpenGLRenderer: Initialized EGL, version 1.4
,09-15 12:02:56.534  9367  9418 D mali_winsys: EGLint new_window_surface(egl_winsys_display*, void*, EGLSurface, EGLConfig, egl_winsys_surface**, egl_color_buffer_format*, EGLBoolean) returns 0x3000,  [1440x2560]-format:1
,09-15 12:02:56.544  9367  9367 W DisplayListCanvas: DisplayListCanvas is started on unbinded RenderNode (without mOwningView)
,09-15 12:02:56.584  3399  4443 V WindowStateAnimator: Finishing drawing window Window{960f07b u0 d0 com.test.thalitest/com.test.thalitest.MainActivity}: mDrawState=DRAW_PENDING
,09-15 12:02:56.584  9367  9367 D ViewRootImpl: MSG_RESIZED_REPORT: ci=Rect(0, 96 - 0, 0) vi=Rect(0, 96 - 0, 0) or=1
,09-15 12:02:56.584  3399  3969 D InputMethodManagerService: windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,09-15 12:02:56.584  3399  3562 D KnoxTimeoutHandler: notifyActivityDrawn [MsgParam] userId: 0 fullscreen is true showWhenlocked is false
09-15 12:02:56.584  3399  3399 D KnoxTimeoutHandler: activityDrawn [MsgParam] userId: 0 fullscreen is true showWhenlocked is false
,09-15 12:02:56.584  3399  3562 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +566ms
09-15 12:02:56.584  3399  3562 D CustomFrequencyManagerService: releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1872000  uid : 1000  pid : 3399  tag : ACTIVITY_RESUME_BOOSTER@3
09-15 12:02:56.584  3399  3562 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{e01e71c u0 com.test.thalitest/.MainActivity t10} time:179017
09-15 12:02:56.584  3399  3562 D ActivityManager: mDVFSHelper.release()
09-15 12:02:56.584  3399  3562 D ViewRootImpl: #3 mView = null
,09-15 12:02:56.594  3399  3537 D CustomFrequencyManagerService: acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1872000  uid : 1000  pid : 3399  pkgName : ACTIVITY_RESUME_BOOSTER@9
,09-15 12:02:56.594  3006  3006 D libEGL  : eglInitialize EGLDisplay = 0x7fc83bb698
09-15 12:02:56.594  3399  3399 I KnoxTimeoutHandler: SD activityfalse
,09-15 12:02:56.594  7485  7485 D SamsungIME: IMPL finishInput
09-15 12:02:56.594  7485  7485 D SamsungIME: SwiftKeyWrapper writeDBdataToFileOnFinishInput
,09-15 12:02:56.594  7485  7485 D SamsungIME: saveAndClear +
09-15 12:02:56.594  7485  7485 D SamsungIME: saveAndClear -
,09-15 12:02:56.604  9367  9424 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
09-15 12:02:56.604  9367  9424 D libEGL  : eglInitialize EGLDisplay = 0xd8e6c3f4
,09-15 12:02:56.604  3399  4310 V WindowStateAnimator: Finishing drawing window Window{960f07b u0 d0 com.test.thalitest/com.test.thalitest.MainActivity}: mDrawState=HAS_DRAWN
,09-15 12:02:56.604  9367  9367 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@1493d9d time:179033
09-15 12:02:56.604  4280  4280 D Launcher.HomeView: onStop
09-15 12:02:56.604  4280  4280 D capture : ----destroy
09-15 12:02:56.604  4280  4280 V ActivityThread: updateVisibility : ActivityRecord{23143fd token=android.os.BinderProxy@898930d {com.sec.android.app.launcher/com.sec.android.app.launcher.activities.LauncherActivity}} show : false
,09-15 12:02:56.604  3399  3853 D NetworkPolicy: isUidForegroundLocked: 10068, mScreenOn: true, uidstate: 3, mProxSensorScreenOff: false
,09-15 12:02:56.614  3006  3006 D libEGL  : eglInitialize EGLDisplay = 0x7fc83bb698
,09-15 12:02:56.614  4280  4280 D Launcher: onTrimMemory. Level: 20
,09-15 12:02:56.614  9367  9424 D libGLESv2: DTS_GLAPI : DTS is not allowed for Package : com.test.thalitest
,09-15 12:02:56.634  9367  9367 W cr_BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 9367
,09-15 12:02:56.664  3006  3006 D libEGL  : eglInitialize EGLDisplay = 0x7fc83bb698
,09-15 12:02:56.744  9367  9367 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,09-15 12:02:56.784  3006  4108 I SurfaceFlinger: id=20 Removed uhalitest (6/10)
09-15 12:02:56.784  3006  3015 I SurfaceFlinger: id=20 Removed uhalitest (-2/10)
,09-15 12:02:56.794  3006  3006 D libEGL  : eglTerminate EGLDisplay = 0x7fc83bb7b8
,09-15 12:02:56.814  9367  9432 D jxcore_app_log: JniHelper::setJavaVM(0xf4db4000), pthread_self() = -758085328
,09-15 12:02:56.814  9367  9432 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
09-15 12:02:56.814  9367  9432 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
09-15 12:02:56.814  9367  9432 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
09-15 12:02:56.814  9367  9432 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
09-15 12:02:56.814  9367  9432 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
09-15 12:02:56.814  9367  9432 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f9cce9c added. We now have 1 listener(s)
,09-15 12:02:56.814  9367  9432 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: 44:78:3E:94:4A:3E
,09-15 12:02:56.814  9367  9432 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "44:78:3E:94:4A:3E"
09-15 12:02:56.814  9367  9432 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-15 12:02:56.814  9367  9432 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,09-15 12:02:56.814  9367  9432 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
09-15 12:02:56.814  9367  9432 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
09-15 12:02:56.814  9367  9432 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
09-15 12:02:56.814  9367  9432 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: 44:78:3E:94:4A:3E
09-15 12:02:56.814  9367  9432 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
09-15 12:02:56.814  9367  9432 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
09-15 12:02:56.814  9367  9432 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
09-15 12:02:56.814  9367  9432 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
09-15 12:02:56.814  9367  9432 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
09-15 12:02:56.814  9367  9432 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
09-15 12:02:56.814  9367  9432 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
09-15 12:02:56.814  9367  9432 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
09-15 12:02:56.814  9367  9432 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
09-15 12:02:56.814  9367  9432 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
09-15 12:02:56.814  9367  9432 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ac8cc2b added. We now have 1 listener(s)
09-15 12:02:56.814  9367  9432 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-15 12:02:56.824  9367  9432 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
09-15 12:02:56.824  9367  9432 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
09-15 12:02:56.824  9367  9432 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
09-15 12:02:56.824  9367  9432 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
09-15 12:02:56.824  9367  9432 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
,09-15 12:02:56.824  9367  9432 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-15 12:02:56.824  9367  9432 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 44:78:3E:94:4A:3E
,09-15 12:02:56.824  9367  9432 D BluetoothAdapter: STATE_ON
,09-15 12:02:56.824  9367  9432 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (SUPPORTED) in persistent storage
09-15 12:02:56.824  9367  9432 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-15 12:02:56.824  9367  9432 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-15 12:02:56.824  9367  9432 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-15 12:02:56.824  9367  9432 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-15 12:02:56.824  9367  9432 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-15 12:02:56.824  9367  9432 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-15 12:02:56.824  9367  9432 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-15 12:02:56.824  9367  9432 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-15 12:02:56.824  9367  9432 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
09-15 12:02:56.824  9367  9432 D io.jxcore.node.ConnectivityMonitor: start: OK
09-15 12:02:56.824  9367  9432 I io.jxcore.node.LifeCycleMonitor: start: OK
,09-15 12:02:56.824  9367  9367 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-15 12:02:56.834  9367  9367 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-15 12:02:56.834  9367  9367 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,09-15 12:02:56.864  3399  3876 D MdnieScenarioControlService:  packageName : com.test.thalitest    className : com.test.thalitest.MainActivity
,09-15 12:02:56.894  3399  3399 D CustomFrequencyManagerService: releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1872000  uid : 1000  pid : 3399  tag : ACTIVITY_RESUME_BOOSTER@9
,09-15 12:02:56.964  3399  3876 I MdnieScenarioControlService: mGameModeLauncher : false
09-15 12:02:56.974  3399  3876 I MdnieScenarioControlService: setUIMode
09-15 12:02:57.034  4017  4017 D Recents : onTaskStackChanged
09-15 12:02:57.044  4017  4017 W ResourcesManager: getTopLevelResources: /data/app/com.test.thalitest-1/base.apk / 1.0 running in com.android.systemui rsrc of package com.test.thalitest
09-15 12:02:57.054  4017  4017 D ResourcesManager: For user 0 new overlays fetched Null
09-15 12:02:57.084  3399  5992 W ResourcesManager: getTopLevelResources: /data/app/com.test.thalitest-1/base.apk / 1.0 running in null rsrc of package com.test.thalitest
09-15 12:02:57.114  9367  9433 W jxcore-log: Initializing JXcore engine
09-15 12:02:57.114  9367  9433 W jxcore-log: JXcore engine is ready
09-15 12:02:57.134  5050  5050 E audit   : type=1400 msg=audit(1473933777.134:264): avc:  denied  { ioctl } for  pid=9433 comm="Thread-162" path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=4136 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
09-15 12:02:57.134  5050  5050 E audit   :  SEPF_SECMOBILE_6.0.1_0013
09-15 12:02:57.134  5050  5050 E audit   : type=1300 msg=audit(1473933777.134:264): arch=40000028 syscall=54 per=8 success=no exit=-13 a0=8 a1=5451 a2=2 a3=d21083c8 items=0 ppid=3176 pid=9433 auid=4294967295 uid=10171 gid=10171 euid=10171 suid=10171 fsuid=10171 egid=10171 sgid=10171 fsgid=10171 tty=(none) ses=4294967295 comm="Thread-162" exe="/system/bin/app_process32" subj=u:r:untrusted_app:s0:c512,c768 key=(null)
09-15 12:02:57.134  5050  5050 E audit   : type=1327 msg=audit(1473933777.134:264): proctitle="com.test.thalitest"
09-15 12:02:57.134  5050  5050 E audit   : type=1320 msg=audit(1473933777.134:264): 
09-15 12:02:57.134  5050  5050 E audit   : type=1400 msg=audit(1473933777.134:265): avc:  denied  { ioctl } for  pid=9433 comm="Thread-162" path="socket:[37261]" dev="sockfs" ino=37261 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
09-15 12:02:57.134  5050  5050 E audit   :  SEPF_SECMOBILE_6.0.1_0013
09-15 12:02:57.134  5050  5050 E audit   : type=1300 msg=audit(1473933777.134:265): arch=40000028 syscall=54 per=8 success=no exit=-13 a0=3b a1=5451 a2=2 a3=d21083c8 items=0 ppid=3176 pid=9433 auid=4294967295 uid=10171 gid=10171 euid=10171 suid=10171 fsuid=10171 egid=10171 sgid=10171 fsgid=10171 tty=(none) ses=4294967295 comm="Thread-162" exe="/system/bin/app_process32" subj=u:r:untrusted_app:s0:c512,c768 key=(null)
09-15 12:02:57.134  5050  5050 E audit   : type=1327 msg=audit(1473933777.134:265): proctitle="com.test.thalitest"
09-15 12:02:57.134  5050  5050 E audit   : type=1320 msg=audit(1473933777.134:265): 
09-15 12:02:57.134  9367  9433 W jxcore-log: Starting JXcore engine
09-15 12:02:57.174  9367  9433 W jxcore-log: Platform android
09-15 12:02:57.174  9367  9433 W jxcore-log: 
09-15 12:02:57.174  9367  9433 W jxcore-log: Process ARCH arm
09-15 12:02:57.174  9367  9433 W jxcore-log: 
09-15 12:02:57.244  9367  9433 I jxcore-log: JXcore Cordova bridge is ready!
09-15 12:02:57.244  9367  9433 I jxcore-log: 
09-15 12:02:57.244  9367  9433 W jxcore-log: JXcore engine is started
09-15 12:02:57.254  9367  9432 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
09-15 12:02:57.254  9367  9367 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
09-15 12:02:57.644  3399  3567 D PowerManagerService: [s] UserActivityState : 2 -> 4
09-15 12:02:57.644  3399  3567 D InputManager-JNI: setInteractive(false)
09-15 12:02:57.644  3399  3567 I PowerManagerService: !@[ps] Screen__Off - 1 : timeout (0x4) (2)
09-15 12:02:57.644  3399  3567 I PowerManagerService: Going to sleep due to screen timeout (uid 1000)...
09-15 12:02:57.644  3399  3567 D PowerManagerService: mDisplayReady: false
09-15 12:02:57.644  3399  3567 D DisplayPowerController: animateScreenStateChange[0]: target=1
09-15 12:02:57.644  3399  3567 D ColorFade: prepare: mode=4
09-15 12:02:57.644  3399  3895 D NetworkPolicy: onScreenStateChanged, state: false, reason: 3
09-15 12:02:57.644  3006  3006 I SurfaceFlinger: id=22 createSurf (1440x2560),2 flag=404, DolorFade
09-15 12:02:57.644  3944  3961 D KeyguardViewMediator: onStartedGoingToSleep(3)
09-15 12:02:57.654  7485  7485 D SamsungIME: IMPL finishInput
09-15 12:02:57.654  7485  7485 D SamsungIME: SwiftKeyWrapper writeDBdataToFileOnFinishInput
09-15 12:02:57.654  7485  7485 D SamsungIME: saveAndClear +
09-15 12:02:57.654  7485  7485 D SamsungIME: saveAndClear -
09-15 12:02:57.654  3399  3567 D mali_winsys: EGLint new_window_surface(egl_winsys_display*, void*, EGLSurface, EGLConfig, egl_winsys_surface**, egl_color_buffer_format*, EGLBoolean) returns 0x3000,  [1440x2560]-format:1
09-15 12:02:57.664  3944  3961 E KeyguardViewMediator: lockAfterTimeout = 5000 policyTimeout = 0
09-15 12:02:57.664  3944  3961 D KeyguardViewMediator: timeout : 5000
09-15 12:02:57.674  3944  3961 D KeyguardViewMediator: setting alarm to turn off keyguard, seq = 2
09-15 12:02:57.674  3944  3961 D KeyguardViewMediator: notifyStartedGoingToSleep
09-15 12:02:57.674  3944  3944 V KeyguardFingerPrint: updateFingerprintListeningState(false)
09-15 12:02:57.674  3944  3944 D KeyguardFingerPrint: shouldListenForFingerprint ( FingerPrint is not enabled. ) 
09-15 12:02:57.674  3944  3944 V KeyguardUpdateMonitor: stopListeningForFingerprint()
09-15 12:02:57.674  3944  3944 D KeyguardViewMediator: handleNotifyStartedGoingToSleep
09-15 12:02:57.684  3399  3567 D libEGL  : eglInitialize EGLDisplay = 0x7f79c2f778
09-15 12:02:57.684  3399  3567 D libEGL  : eglTerminate EGLDisplay = 0x7f79c2f8e8
09-15 12:02:57.694  3399  3567 D ColorFade: ColorFade is ready
09-15 12:02:57.694  3399  3567 D DisplayPowerController: ColorFade: onAnimationStart
09-15 12:02:57.694  3399  3567 D DisplayPowerController: [Dual Screen Compatible] state[0] :2
09-15 12:02:57.694  3399  3567 D DisplayPowerController: getFinalBrightness : Summary is 107 -> 107
09-15 12:02:57.724  3006  3006 D libEGL  : eglInitialize EGLDisplay = 0x7fc83bb698
09-15 12:02:57.734  3006  3006 D libEGL  : eglInitialize EGLDisplay = 0x7fc83bb698
09-15 12:02:57.754  3006  3006 D libEGL  : eglInitialize EGLDisplay = 0x7fc83bb698
,09-15 12:02:57.984  3399  3567 D DisplayPowerState: !@ [0] ColorFade entry,
09-15 12:02:57.984  3399  3567 D PowerManagerService: [input device light] onColorFadeExit(false)
09-15 12:02:57.984  3399  3567 D DisplayPowerController: ColorFade: onAnimationEnd
,09-15 12:02:57.994  3399  3898 D lights  : lcd : 0 +
09-15 12:02:57.994  3399  3567 D DisplayPowerController: animateScreenStateChange[0]: target=1
09-15 12:02:57.994  3399  3567 D DisplayPowerController: [M OS] 0 REPORTED_TO_POLICY_SCREEN_* -> REPORTED_TO_POLICY_SCREEN_OFF.
,09-15 12:02:58.024  3399  3898 D lights  : lcd : 0 -
,09-15 12:02:58.034  9367  9367 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
09-15 12:02:58.034  9367  9367 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: PAUSED
,09-15 12:02:58.124  3399  3567 D SContextService: unregisterCallback() : Listener = android.hardware.scontext.SContextService$Listener@73a52ef, Service = Auto Rotation, used = 0
,09-15 12:02:58.124  3399  3567 W CAE     : unregisterCallback(ContextAwareService.java:206) - [unregi 01] Mutex is locked for AUTO_ROTATION
09-15 12:02:58.124  3399  3567 V CAE     : stop(ContextProvider.java:155)
,09-15 12:02:58.124  3399  3567 V CAE     : clear(AutoRotationRunner.java:182)
09-15 12:02:58.124  3399  3567 V CAE     : disable(AutoRotationRunner.java:171)
,09-15 12:02:58.124  3399  3567 I CAE     : sendCmdToSensorHub(SensorHubCommManager.java:162) - -78, 7, 0, 0,
09-15 12:02:58.124  3399  3567 D SensorHubManager: SendSensorHubData: send data = -78, 7, 0, 0
,09-15 12:02:58.134  3166  3213 D Sensorhubs: sendContextData: -78, 7, 0, 0
,09-15 12:02:58.134  9367  9367 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@d953172 Bundle[{plugin=Bundle[{}], android:viewHierarchyState=Bundle[{android:views={100=android.view.AbsSavedState$1@6558627, 16908290=android.view.AbsSavedState$1@6558627}, android:focusedViewId=100}]}]
09-15 12:02:58.134  9367  9367 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: SAVE_INSTANCE_STATE
,09-15 12:02:58.134  9367  9367 V ActivityThread: updateVisibility : ActivityRecord{a7430d4 token=android.os.BinderProxy@1493d9d {com.test.thalitest/com.test.thalitest.MainActivity}} show : true
,09-15 12:02:58.134  3399  3567 D CAE     : getFaultDetectionResult(AutoRotationRunner.java:195) - true
09-15 12:02:58.134  3399  3567 I CAE     : notifyCmdProcessResultObserver(ContextProvider.java:627) - CheckResult = 0, Cause = Success
,09-15 12:02:58.134  9367  9367 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
09-15 12:02:58.134  9367  9367 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: STOPPED
,09-15 12:02:58.144  3399  3853 D NetworkPolicy: isUidForegroundLocked: 10171, mScreenOn: true, uidstate: 5, mProxSensorScreenOff: false
,09-15 12:02:58.144  3399  3567 D CAE     : doCommendProcess(ContextAwareService.java:433) - complete notify the operation result.
,09-15 12:02:58.144  3399  3567 I CAE     : displayUsedCountForService(ContextAwareService.java:525) - totalCnt = 0, serviceCount = 0, subCollectionCount = 0
09-15 12:02:58.144  3399  3567 D CAE     : showListenerList(ContextAwareService.java:366) - ===== Context Aware Service List =====
,09-15 12:02:58.144  3399  3567 I CAE     : showListenerList(ContextAwareService.java:375) - Listener : com.samsung.android.contextaware.manager.ContextAwareService$Listener@529c78c, Service : ACTIVITY_TRACKER_CURRENT_INFO(1)
09-15 12:02:58.144  3399  3567 I CAE     : showListenerList(ContextAwareService.java:375) - Listener : com.samsung.android.contextaware.manager.ContextAwareService$Listener@529c78c, Service : ACTIVITY_TRACKER(1)
09-15 12:02:58.144  3399  3567 I CAE     : showListenerList(ContextAwareService.java:375) - Listener : com.samsung.android.contextaware.manager.ContextAwareService$Listener@509dbf7, Service : AUTO_BRIGHTNESS(1)
,09-15 12:02:58.144  3399  3567 W CAE     : unregisterCallback(ContextAwareService.java:241) - [unregi 02] Mutex is unlocked for AUTO_ROTATION
09-15 12:02:58.144  3399  3567 D SContextService: 	.unregisterCallback : 3, client=
09-15 12:02:58.144  3399  3567 D SContextService: ===== SContext Service List =====
09-15 12:02:58.144  3399  3567 D SContextService: Listener : android.hardware.scontext.SContextService$Listener@e421a64, Service : Auto Brightness
09-15 12:02:58.144  3399  3567 D SContextService: Listener : android.hardware.scontext.SContextService$Listener@9e9e085, Service : Activity Tracker
09-15 12:02:58.144  3399  3567 D SContextManager:   .unregisterListener : listener = com.android.server.policy.WindowOrientationListener$OrientationSensorJudge@c55b906, service=Auto Rotation
09-15 12:02:58.144  3399  3567 V KeyguardServiceDelegate: onScreenTurnedOff()
,09-15 12:02:58.144  3944  3955 D KeyguardViewMediator: notifyScreenTurnedOff
09-15 12:02:58.144  3944  3944 D KeyguardViewMediator: handleNotifyScreenTurnedOff
09-15 12:02:58.144  3944  3944 D vol.SecVolumeDialog: onScreenTurnedOff()
09-15 12:02:58.154  3944  3944 D vol.SecVolumeDialog: dismissH reason: 4
09-15 12:02:58.154  3944  3944 D vol.SecVolumeDialog: dismissH : false
,09-15 12:02:58.154  3399  3567 D DisplayPowerController: mWindowManagerPolicy.screenTurnedOff(0)
,09-15 12:02:58.154  3399  3567 D DisplayPowerController: [Dual Screen Compatible] state[0] :1
09-15 12:02:58.154  3399  3897 D SContextService: unregisterCallback() : Listener = android.hardware.scontext.SContextService$Listener@e421a64, Service = Auto Brightness, used = 0
09-15 12:02:58.154  3399  3567 D PowerManagerUtil: fileWriteInt to /sys/class/tcon/tcon/auto_br, 0
09-15 12:02:58.154  3399  3897 D AutomaticBrightnessController: [DAB] setLightSensorEnabled : unregisterListenerRunnable
,09-15 12:02:58.154  3399  3897 W CAE     : unregisterCallback(ContextAwareService.java:206) - [unregi 01] Mutex is locked for AUTO_BRIGHTNESS
09-15 12:02:58.154  3399  3567 D PowerManagerUtil: fileWriteInt to /sys/class/backlight/panel/auto_brightness, 0
09-15 12:02:58.154  3399  3538 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1305 com.android.server.policy.sec.SamsungPhoneWindowManager$22.run:4514 android.os.Handler.handleCallback:739 android.os.Handler.dispatchMessage:95 android.os.Looper.loop:158 
09-15 12:02:58.154  3399  3897 V CAE     : stop(ContextProvider.java:155)
,09-15 12:02:58.154  3399  3897 V CAE     : clear(AutoBrightnessRunner.java:297)
,09-15 12:02:58.154  3399  3897 V CAE     : disable(AutoBrightnessRunner.java:286)
09-15 12:02:58.154  3399  3567 D PowerManagerUtil: fileWriteInt to /sys/class/mdnie/mdnie/auto_brightness, 0
09-15 12:02:58.154  3399  3897 I CAE     : sendCmdToSensorHub(SensorHubCommManager.java:162) - -78, 48, 0, 0,
09-15 12:02:58.154  3399  3567 D AutomaticBrightnessController: [DAB] no lux value from sensor manager
09-15 12:02:58.154  3399  3897 D SensorHubManager: SendSensorHubData: send data = -78, 48, 0, 0
09-15 12:02:58.154  3399  3567 D DisplayPowerController: getFinalBrightness : Summary is 0 -> 0
09-15 12:02:58.154  4734  4734 I AODService: onStartCommand : action : com.samsung.android.app.aodservice.intent.action.AOD_SCREEN_OFF
09-15 12:02:58.154  3399  3567 D DisplayPowerController: Animating brightness: target=0, rate=0 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
09-15 12:02:58.154  4734  4734 I AODService: onCreate cause: [09-15 12:00:13.161][AOD:true, NightClock:false]<com.samsung.android.app.aodservice.intent.action.AOD_APP_START> (when Screen on ...)
09-15 12:02:58.154  3399  3567 D DisplayPowerController: animateScreenStateChange[0]: target=1
09-15 12:02:58.154  3166  3166 D Sensorhubs: sendContextData: -78, 48, 0, 0
09-15 12:02:58.154  3399  3567 D DisplayPowerController: [Dual Screen Compatible] state[0] :1
09-15 12:02:58.154  3399  9435 D MISC PowerHAL: sysfs_write +: /sys/class/input/event0/device/enabled: 0
09-15 12:02:58.154  3399  3567 D DisplayPowerController: getFinalBrightness : Summary is 0 -> 0
09-15 12:02:58.154  3399  9436 D MISC PowerHAL: sysfs_write +: /sys/class/input/event1/device/enabled: 0
09-15 12:02:58.154  3399  3567 D DisplayPowerController: Animating brightness: target=0, rate=0 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
09-15 12:02:58.154  3399  9435 D MISC PowerHAL: sysfs_write -: /sys/class/input/event0/device/enabled: 0
09-15 12:02:58.164  3399  9436 D MISC PowerHAL: sysfs_write -: /sys/class/input/event1/device/enabled: 0
,09-15 12:02:58.164  3399  3575 D DisplayManagerService: !@display_state: ON -> OFF brightness: 0 -> 0
09-15 12:02:58.164  3399  3575 D MISC PowerHAL: sysfs_write +: /sys/class/power_supply/battery/lcd: 0
09-15 12:02:58.164  3399  3575 D MISC PowerHAL: sysfs_write -: /sys/class/power_supply/battery/lcd: 0
09-15 12:02:58.164  3399  3562 I DisplayManagerService: Display device changed state: "Wbudowany ekran", OFF
09-15 12:02:58.164  3399  3562 I DisplayManagerService: Display device changed state: "ActivityViewVirtualDisplay", OFF
,09-15 12:02:58.164  3006  3006 D SurfaceFlinger: Set power mode=0, type=0 flinger=0x7f88103c00
,09-15 12:02:58.164  3006  3006 I hwcomposer: int exynos_setPowerMode(hwc_composer_device_1*, int, int):: disp(0), mode(0)
,09-15 12:02:58.174  3399  3410 I art     : Background partial concurrent mark sweep GC freed 65264(4MB) AllocSpace objects, 28(560KB) LOS objects, 32% free, 33MB/49MB, paused 1.303ms total 153.295ms
,09-15 12:02:58.184  3399  3897 D CAE     : getFaultDetectionResult(AutoBrightnessRunner.java:311) - true
,09-15 12:02:58.184  3399  3897 I CAE     : notifyCmdProcessResultObserver(ContextProvider.java:627) - CheckResult = 0, Cause = Success
,09-15 12:02:58.204  3399  3897 D CAE     : doCommendProcess(ContextAwareService.java:433) - complete notify the operation result.
,09-15 12:02:58.204  3399  3897 I CAE     : displayUsedCountForService(ContextAwareService.java:525) - totalCnt = 0, serviceCount = 0, subCollectionCount = 0
,09-15 12:02:58.204  3399  3897 D CAE     : showListenerList(ContextAwareService.java:366) - ===== Context Aware Service List =====
09-15 12:02:58.204  3399  3897 I CAE     : showListenerList(ContextAwareService.java:375) - Listener : com.samsung.android.contextaware.manager.ContextAwareService$Listener@529c78c, Service : ACTIVITY_TRACKER_CURRENT_INFO(1)
,09-15 12:02:58.204  3399  3897 I CAE     : showListenerList(ContextAwareService.java:375) - Listener : com.samsung.android.contextaware.manager.ContextAwareService$Listener@529c78c, Service : ACTIVITY_TRACKER(1)
09-15 12:02:58.204  3399  3897 W CAE     : unregisterCallback(ContextAwareService.java:241) - [unregi 02] Mutex is unlocked for AUTO_BRIGHTNESS
,09-15 12:02:58.204  3399  3897 D SContextService: 	.unregisterCallback : 2, client=
09-15 12:02:58.204  3399  3897 D SContextService: ===== SContext Service List =====
09-15 12:02:58.204  3399  3897 D PowerManagerUtil: Excessive delay in SensorHubAutoBrightnessEnabled::unregisterListener done: 52ms
09-15 12:02:58.204  3399  3469 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
09-15 12:02:58.204  3399  3897 D SContextService: Listener : android.hardware.scontext.SContextService$Listener@9e9e085, Service : Activity Tracker
09-15 12:02:58.204  3399  3897 D SContextManager:   .unregisterListener : listener = com.android.server.display.AutomaticBrightnessController$6@e3724c8, service=Auto Brightness
09-15 12:02:58.204  3399  4898 D CoverManagerWhiteLists: isAllowedToUse : SIGNATURE_MATCH
,09-15 12:02:58.204  4734  4734 D ScoverManager: registerListener
,09-15 12:02:58.204  3399  4279 D CoverManagerWhiteLists: isAllowedToUse : SIGNATURE_MATCH
,09-15 12:02:58.214  3399  4235 D CoverManagerWhiteLists: isAllowedToUse : SIGNATURE_MATCH
,09-15 12:02:58.214  3399  4235 D CoverManager.StateNotifier: registerListenerCallback : binder = android.os.BinderProxy@9680647, pid : 4734, uid : 10000, type : 1
,09-15 12:02:58.214  4734  9437 D AODService: onCreate register mSContextListener : com.samsung.android.app.aodservice.AODService$7@abcd199
09-15 12:02:58.214  3399  4397 D SensorService: SensorEventConnection::SocketBufferSize, SystemSocketBufferSize - 102400, 2097152
09-15 12:02:58.214  3399  3969 W CAE     : setCAProperty(ContextAwareService.java:578) - [setProperty 01] Mutex is locked for DEVICE_PHYSICAL_CONTEXT_MONITOR
09-15 12:02:58.214  3399  3969 I CAE     : sendCmdToSensorHub(SensorHubCommManager.java:162) - -63, 23, 56, 4, 0, 0, 0, 1, 2,
09-15 12:02:58.214  3399  3969 D SensorHubManager: SendSensorHubData: send data = -63, 23, 56, 4, 0, 0, 0, 1, 2
09-15 12:02:58.214  3166  3213 D Sensorhubs: sendContextData: -63, 23, 56, 4, 0, 0, 0, 1, 2
09-15 12:02:58.214  3399  4899 I Sensors : Light old sensor_state 0, new sensor_state : 512 en : 1
09-15 12:02:58.224  3399  3969 I CAE     : setCAProperty(ContextAwareService.java:583) - result : true
09-15 12:02:58.224  3399  3969 W CAE     : setCAProperty(ContextAwareService.java:584) - [setProperty 02] Mutex is unlocked for DEVICE_PHYSICAL_CONTEXT_MONITOR
09-15 12:02:58.224  3399  3969 W CAE     : registerCallback(ContextAwareService.java:144) - [regi 01] Mutex is locked for DEVICE_PHYSICAL_CONTEXT_MONITOR
09-15 12:02:58.224  3399  3969 V CAE     : start(ContextProvider.java:128)
09-15 12:02:58.224  4734  4734 D SensorManager: registerListener :: 6, TMD4093 RGB Sensor, 200000, 0,  
09-15 12:02:58.224  4734  4734 D AODService: registerBatteryReceiver
09-15 12:02:58.224  3399  3969 V CAE     : clear(DevicePhysicalContextMonitorRunner.java:497)
09-15 12:02:58.224  3399  3969 V CAE     : enable(DevicePhysicalContextMonitorRunner.java:471)
09-15 12:02:58.224  3399  3969 I CAE     : sendCmdToSensorHub(SensorHubCommManager.java:162) - -79, 56, 0, 10, 2, 58,
09-15 12:02:58.224  3399  3969 D SensorHubManager: SendSensorHubData: send data = -79, 56, 0, 10, 2, 58
,09-15 12:02:58.224  3166  3166 D Sensorhubs: sendContextData: -79, 56, 0, 10, 2, 58
09-15 12:02:58.224  4734  4734 D BatteryController: saveBatteryData : level[100], status[5]
09-15 12:02:58.224  4734  4734 D AODService: Cover coverOpen[true], isBlackListCover(type)[false]
09-15 12:02:58.224  4734  4734 D AODService.ClockTimer: ClockTimer:start : true
,09-15 12:02:58.224  4734  4734 D AODService.ClockTimer: observe start aod
09-15 12:02:58.224  4734  4734 D AODService.ClockTimer: notifyWakeUp
09-15 12:02:58.234  3399  3969 D CAE     : getFaultDetectionResult(DevicePhysicalContextMonitorRunner.java:521) - true
09-15 12:02:58.234  4734  4734 V BatteryController: getBatteryLevel[100.0], batteryStatus[5]
09-15 12:02:58.234  3399  3969 I CAE     : notifyCmdProcessResultObserver(ContextProvider.java:627) - CheckResult = 0, Cause = Success
09-15 12:02:58.234  3399  3470 D SettingsProvider: isChangeAllowed() : name = aod_show_state
09-15 12:02:58.234  3399  3470 D SecContentProvider: query(), uri = 17 selection = isSettingsChangesAllowed
09-15 12:02:58.234  3399  3470 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
09-15 12:02:58.234  3399  3470 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
09-15 12:02:58.234  3399  3470 D SettingsProvider: selectionArgs: false
09-15 12:02:58.234  3399  3470 D SettingsProvider: selectionArgs: 10000
09-15 12:02:58.234  3399  3470 D SettingsProvider: ret = -1
,09-15 12:02:58.234  4734  4734 E SettingsUtils: setAODShowState  config = 1
09-15 12:02:58.234  4734  4734 D AlpmModeManager: setFirstStartALPM() initialize value
,09-15 12:02:58.234  4734  4734 D AODService: createWindow
,09-15 12:02:58.244  4734  4734 I AODUpdatePositionController: initPosition : X[-9], Y[263] Rect(-50, 0 - 50, 920)
,09-15 12:02:58.244  4734  4734 D Minikin : FontFamily bestFont == NULL, so return vacant FakedFont
,09-15 12:02:58.244  4734  4734 D Minikin : FontFamily bestFont == NULL, so return vacant FakedFont
09-15 12:02:58.244  4734  4734 D Minikin : FontFamily bestFont == NULL, so return vacant FakedFont
,09-15 12:02:58.244  3399  3969 D CAE     : doCommendProcess(ContextAwareService.java:433) - complete notify the operation result.
,09-15 12:02:58.244  3399  3969 I CAE     : displayUsedCountForService(ContextAwareService.java:525) - totalCnt = 1, serviceCount = 1, subCollectionCount = 0
,09-15 12:02:58.244  4734  4734 D Minikin : FontFamily bestFont == NULL, so return vacant FakedFont
09-15 12:02:58.244  4734  4734 D Minikin : FontFamily bestFont == NULL, so return vacant FakedFont
09-15 12:02:58.244  4734  4734 D Minikin : FontFamily bestFont == NULL, so return vacant FakedFont
09-15 12:02:58.244  3399  3969 D CAE     : showListenerList(ContextAwareService.java:366) - ===== Context Aware Service List =====
09-15 12:02:58.244  3399  3969 I CAE     : showListenerList(ContextAwareService.java:375) - Listener : com.samsung.android.contextaware.manager.ContextAwareService$Listener@529c78c, Service : ACTIVITY_TRACKER_CURRENT_INFO(1)
,09-15 12:02:58.244  3399  3969 I CAE     : showListenerList(ContextAwareService.java:375) - Listener : com.samsung.android.contextaware.manager.ContextAwareService$Listener@529c78c, Service : ACTIVITY_TRACKER(1)
09-15 12:02:58.244  3399  3969 I CAE     : showListenerList(ContextAwareService.java:375) - Listener : com.samsung.android.contextaware.manager.ContextAwareService$Listener@171875e, Service : DEVICE_PHYSICAL_CONTEXT_MONITOR(1)
,09-15 12:02:58.244  3399  3969 W CAE     : registerCallback(ContextAwareService.java:180) - [regi 02] Mutex is unlocked for DEVICE_PHYSICAL_CONTEXT_MONITOR
,09-15 12:02:58.244  3399  3969 D SContextService: 	.registerCallback : 2, client=
09-15 12:02:58.244  3399  3969 D SContextService: ===== SContext Service List =====
09-15 12:02:58.244  3399  3969 D SContextService: Listener : android.hardware.scontext.SContextService$Listener@9e9e085, Service : Activity Tracker
09-15 12:02:58.244  3399  3969 D SContextService: Listener : android.hardware.scontext.SContextService$Listener@549773f, Service : Device Physical Context Monitor
,09-15 12:02:58.244  4734  9437 D SContextManager:   .registerListener : listener = com.samsung.android.app.aodservice.AODService$7@abcd199, service=Device Physical Context Monitor
09-15 12:02:58.244  4734  4734 D Minikin : FontFamily bestFont == NULL, so return vacant FakedFont
09-15 12:02:58.244  4734  4734 D Minikin : FontFamily bestFont == NULL, so return vacant FakedFont
09-15 12:02:58.244  4734  4734 D Minikin : FontFamily bestFont == NULL, so return vacant FakedFont
,09-15 12:02:58.254  3399  4054 W CAE     : setCAProperty(ContextAwareService.java:578) - [setProperty 01] Mutex is locked for DEVICE_PHYSICAL_CONTEXT_MONITOR
,09-15 12:02:58.254  3399  4054 I CAE     : sendCmdToSensorHub(SensorHubCommManager.java:162) - -63, 23, 56, 3, 1, 2, 88,
09-15 12:02:58.254  3399  4054 D SensorHubManager: SendSensorHubData: send data = -63, 23, 56, 3, 1, 2, 88
09-15 12:02:58.254  3166  3213 D Sensorhubs: sendContextData: -63, 23, 56, 3, 1, 2, 88
,09-15 12:02:58.254  4734  4734 I DefaultClockView: composeDefaultClockView: Selected clock = 0
,09-15 12:02:58.254  3399  4054 I CAE     : setCAProperty(ContextAwareService.java:583) - result : true
,09-15 12:02:58.254  3399  4054 W CAE     : setCAProperty(ContextAwareService.java:584) - [setProperty 02] Mutex is unlocked for DEVICE_PHYSICAL_CONTEXT_MONITOR
,09-15 12:02:58.254  3399  4235 W CAE     : setCAProperty(ContextAwareService.java:578) - [setProperty 01] Mutex is locked for DEVICE_PHYSICAL_CONTEXT_MONITOR
,09-15 12:02:58.254  3399  4235 I CAE     : sendCmdToSensorHub(SensorHubCommManager.java:162) - -63, 23, 56, 3, 2, 0, 3,
09-15 12:02:58.254  3399  4235 D SensorHubManager: SendSensorHubData: send data = -63, 23, 56, 3, 2, 0, 3
09-15 12:02:58.254  3166  3166 D Sensorhubs: sendContextData: -63, 23, 56, 3, 2, 0, 3
,09-15 12:02:58.254  3399  4235 I CAE     : setCAProperty(ContextAwareService.java:583) - result : true
,09-15 12:02:58.254  4734  4734 D BatteryMeterView: BatteryMeterView 
09-15 12:02:58.264  3399  4235 W CAE     : setCAProperty(ContextAwareService.java:584) - [setProperty 02] Mutex is unlocked for DEVICE_PHYSICAL_CONTEXT_MONITOR
,09-15 12:02:58.264  3399  3996 W CAE     : setCAProperty(ContextAwareService.java:578) - [setProperty 01] Mutex is locked for DEVICE_PHYSICAL_CONTEXT_MONITOR
,09-15 12:02:58.264  3399  3996 I CAE     : sendCmdToSensorHub(SensorHubCommManager.java:162) - -63, 23, 56, 3, 3, 0, 60,
09-15 12:02:58.264  3399  3996 D SensorHubManager: SendSensorHubData: send data = -63, 23, 56, 3, 3, 0, 60
09-15 12:02:58.264  3166  3213 D Sensorhubs: sendContextData: -63, 23, 56, 3, 3, 0, 60
,09-15 12:02:58.264  3399  3996 I CAE     : setCAProperty(ContextAwareService.java:583) - result : true
,09-15 12:02:58.264  3399  3996 W CAE     : setCAProperty(ContextAwareService.java:584) - [setProperty 02] Mutex is unlocked for DEVICE_PHYSICAL_CONTEXT_MONITOR
,09-15 12:02:58.264  3399  4443 W CAE     : setCAProperty(ContextAwareService.java:578) - [setProperty 01] Mutex is locked for DEVICE_PHYSICAL_CONTEXT_MONITOR
,09-15 12:02:58.264  3399  4443 I CAE     : sendCmdToSensorHub(SensorHubCommManager.java:162) - -63, 23, 56, 3, 4, 0, 1,
09-15 12:02:58.264  3399  4443 D SensorHubManager: SendSensorHubData: send data = -63, 23, 56, 3, 4, 0, 1
09-15 12:02:58.264  3166  3166 D Sensorhubs: sendContextData: -63, 23, 56, 3, 4, 0, 1
,09-15 12:02:58.274  4734  4734 D Minikin : FontFamily bestFont == NULL, so return vacant FakedFont
09-15 12:02:58.274  4734  4734 D Minikin : FontFamily bestFont == NULL, so return vacant FakedFont
,09-15 12:02:58.274  4734  4734 D Minikin : FontFamily bestFont == NULL, so return vacant FakedFont
09-15 12:02:58.274  3399  4443 I CAE     : setCAProperty(ContextAwareService.java:583) - result : true
,09-15 12:02:58.274  3399  4443 W CAE     : setCAProperty(ContextAwareService.java:584) - [setProperty 02] Mutex is unlocked for DEVICE_PHYSICAL_CONTEXT_MONITOR
09-15 12:02:58.274  4734  4734 D DefaultClockView: LocalTime Pattern : HH:mm
,09-15 12:02:58.274  4734  4734 I AODUpdatePositionController: updatePosition: start current clock, Current X[-9] Current Y[263] NewPositionTimer[60]
,09-15 12:02:58.274  4734  4734 D TimeViewHolder: onTimeUpdate: timeZone:libcore.util.ZoneInfo[id="Europe/Warsaw",mRawOffset=3600000,mEarliestRawOffset=3600000,mUseDst=true,mDstSavings=3600000,transitions=167] isSplitHour:false isSingleView:false isAMPMonLeft:null time01: 12:02 time02: null ampm: null
09-15 12:02:58.274  3399  4899 W CAE     : setCAProperty(ContextAwareService.java:578) - [setProperty 01] Mutex is locked for DEVICE_PHYSICAL_CONTEXT_MONITOR
,09-15 12:02:58.274  3399  4899 I CAE     : sendCmdToSensorHub(SensorHubCommManager.java:162) - -63, 23, 56, 4, 0, 0, 0, 110, 1,
,09-15 12:02:58.274  3399  4899 D SensorHubManager: SendSensorHubData: send data = -63, 23, 56, 4, 0, 0, 0, 110, 1
09-15 12:02:58.274  3166  3213 D Sensorhubs: sendContextData: -63, 23, 56, 4, 0, 0, 0, 110, 1
,09-15 12:02:58.274  3399  4899 I CAE     : setCAProperty(ContextAwareService.java:583) - result : true
,09-15 12:02:58.274  4734  4734 D RoamingTimeViewHolder: isDualClockSetting :: true isHomeTimeZoneExist :: false isEasyUxON :: false Utils.isRoaming(mContext) :: false
09-15 12:02:58.274  3399  4899 W CAE     : setCAProperty(ContextAwareService.java:584) - [setProperty 02] Mutex is unlocked for DEVICE_PHYSICAL_CONTEXT_MONITOR
09-15 12:02:58.274  4734  4734 D RoamingTimeViewHolder: getHomeCalendar : No homecity_timezone, set as default :  (libcore.util.ZoneInfo[id="Europe/Warsaw",mRawOffset=3600000,mEarliestRawOffset=3600000,mUseDst=true,mDstSavings=3600000,transitions=167])
09-15 12:02:58.274  4734  4734 D RoamingTimeViewHolder: onTimeUpdate: isVisible:false timeZone:libcore.util.ZoneInfo[id="Europe/Warsaw",mRawOffset=3600000,mEarliestRawOffset=3600000,mUseDst=true,mDstSavings=3600000,transitions=167] text:czw., 15 wrz 12:02
09-15 12:02:58.274  4734  4734 D DefaultClockView: show
,09-15 12:02:58.274  3399  3969 W CAE     : setCAProperty(ContextAwareService.java:578) - [setProperty 01] Mutex is locked for DEVICE_PHYSICAL_CONTEXT_MONITOR
,09-15 12:02:58.284  4734  4734 D ViewRootImpl: #1 mView = com.samsung.android.app.aodservice.nightclock.DefaultClockView{37cba04 V.E...... ......ID 0,0-0,0}
,09-15 12:02:58.284  3399  3969 I CAE     : sendCmdToSensorHub(SensorHubCommManager.java:162) - -63, 23, 56, 4, 0, 0, 0, 17, 2,
09-15 12:02:58.284  3399  3969 D SensorHubManager: SendSensorHubData: send data = -63, 23, 56, 4, 0, 0, 0, 17, 2
09-15 12:02:58.284  3166  3166 D Sensorhubs: sendContextData: -63, 23, 56, 4, 0, 0, 0, 17, 2
,09-15 12:02:58.284  3399  4443 D ISSUE_DEBUG: InputChannelName : 497e555 AOD
,09-15 12:02:58.284  3399  3538 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=Window{497e555 u0 d0 AOD}
,09-15 12:02:58.284  3399  4443 D InputDispatcher: Focus left window: 9367
09-15 12:02:58.284  3399  4443 D InputDispatcher: Focus entered window: 4734
09-15 12:02:58.284  3399  3562 D PointerIcon: setMouseIconStyle1 pointerType: 1001 iconType:101 flag:0 pid:3399 uid:1000
,09-15 12:02:58.284  3399  3562 D PointerIcon: setMouseCustomIcon IconType is same.101
09-15 12:02:58.284  3944  3944 D PhoneStatusBar: setSystemUiVisibility vis=8000 mask=ffffffff oldVal=8600 newVal=8000 diff=600
09-15 12:02:58.284  3399  3969 I CAE     : setCAProperty(ContextAwareService.java:583) - result : true
,09-15 12:02:58.284  3399  3969 W CAE     : setCAProperty(ContextAwareService.java:584) - [setProperty 02] Mutex is unlocked for DEVICE_PHYSICAL_CONTEXT_MONITOR
,09-15 12:02:58.304  9438  9438 E Zygote  : v2
09-15 12:02:58.304  9438  9438 I libpersona: KNOX_SDCARD checking this for 10003
09-15 12:02:58.304  9438  9438 I libpersona: KNOX_SDCARD not a persona
,09-15 12:02:58.304  9438  9438 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0013
,09-15 12:02:58.304  9438  9438 E Zygote  : accessInfo : 0
09-15 12:02:58.304  3399  4443 I ActivityManager: Start proc 9438:com.sec.android.provider.badge/u0a3 for content provider com.sec.android.provider.badge/.BadgeProvider
09-15 12:02:58.304  9438  9438 W SELinux : SELinux: seapp_context_lookup: seinfo=platform, level=s0:c512,c768, pkgname=com.sec.android.provider.badge 
,09-15 12:02:58.314  9438  9438 D TimaKeyStoreProvider: TimaSignature is unavailable
09-15 12:02:58.314  9438  9438 D ActivityThread: Added TimaKeyStore provider
,09-15 12:02:58.334  3399  3575 D SurfaceControl: Excessive delay in setPowerMode(): 170ms
09-15 12:02:58.334  3399  3575 D PowerManagerUtil: Excessive delay in !@display_state: OFF: 171ms
09-15 12:02:58.334  3399  3567 I libsuspend: !@autosuspend_wakeup_count_enable
09-15 12:02:58.334  3399  3575 D PowerManagerUtil: Excessive delay in DisplayManagerInternal.requestDesiredDisplayState: 173ms
09-15 12:02:58.334  3399  3567 I libsuspend: !@autosuspend_wakeup_count_enable done
,09-15 12:02:58.334  3399  3567 D DisplayPowerController: animateScreenStateChange[0]: target=1
09-15 12:02:58.334  3399  3567 D DisplayPowerController: [Dual Screen Compatible] state[0] :1
09-15 12:02:58.334  3399  3567 D DisplayPowerController: getFinalBrightness : Summary is 0 -> 0
09-15 12:02:58.334  3399  3567 D DisplayPowerController: Animating brightness: target=0, rate=0 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
09-15 12:02:58.334  3399  3567 I PowerManagerService: [PWL] Off : 0s ago
09-15 12:02:58.334  3399  3567 I PowerManagerService: [PWL]   PowerManagerService.WakeLocks: ref count=1
09-15 12:02:58.334  3399  3567 I PowerManagerService: [PWL]     mWakeLockSummary : 0x1
09-15 12:02:58.334  3399  3567 I PowerManagerService: [PWL]       PARTIAL_WAKE_LOCK              'AlwaysOnDisplay_EnsureWorkingTime' (uid=10000, pid=4734, ws=null) (elapsedTime=119)
09-15 12:02:58.334  3399  3567 I PowerManagerService: [PWL]   PowerManagerService.Display: ref count=2
09-15 12:02:58.334  3399  3567 I PowerManagerService: [PWL]     mUserActivitySummary : 0x4
09-15 12:02:58.334  3399  3895 D PersonaManagerService: onfinishedGoingToSleep why = 3
09-15 12:02:58.334  3399  3567 I PowerManagerService: [PWL]     mDisplayReady : false
,09-15 12:02:58.334  3399  3567 D DisplayPowerController: animateScreenStateChange[0]: target=1
09-15 12:02:58.334  3944  3955 D KeyguardViewMediator: onFinishedGoingToSleep(3)
09-15 12:02:58.334  3399  3567 D DisplayPowerController: [Dual Screen Compatible] state[0] :1
,09-15 12:02:58.334  3944  3955 D KeyguardViewMediator: notifyFinishedGoingToSleep
09-15 12:02:58.334  3399  3567 D DisplayPowerController: getFinalBrightness : Summary is 0 -> 0
09-15 12:02:58.334  3944  3944 D KeyguardViewMediator: handleNotifyFinishedGoingToSleep
09-15 12:02:58.334  3399  3567 D DisplayPowerController: Animating brightness: target=0, rate=0 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
,09-15 12:02:58.334  3399  3590 D PersonaManagerServiceHandler: MSG_ACTION_SCREEN_OFF called
,09-15 12:02:58.334  3399  3567 D PowerManagerService: [s] DisplayPowerCallbacks : onStateChanged()
09-15 12:02:58.334  3944  3944 D KeyguardEffectViewController: onScreenTurnedOff
09-15 12:02:58.334  3399  3567 D PowerManagerService: mDisplayReady: true
09-15 12:02:58.334  3944  3944 D KeyguardEffectViewController: ## mBackgroundView.onPause()
09-15 12:02:58.334  3399  3567 D PowerManagerService: [PWL] sb release: PowerManagerService.Display
,09-15 12:02:58.334  3944  3944 D KeyguardEffectViewLayered: onPause()
09-15 12:02:58.334  3399  3567 D PowerManagerService: handleSandman : startDreaming: true  (canDreamLocked: false  canDozeLocked: true)
09-15 12:02:58.334  3944  3944 D SecKeyguardStatusView: onFinishedGoingToSleep() why=3
09-15 12:02:58.334  3399  3567 D PowerManagerService: handleSandman : startDream(true)
09-15 12:02:58.334  3944  3944 V KeyguardFingerPrint: updateFingerprintListeningState(false)
09-15 12:02:58.334  3399  3567 E PowerManagerService: handleSandman : startDreaming, but isDreaming false
,09-15 12:02:58.334  3944  3944 D KeyguardFingerPrint: shouldListenForFingerprint ( FingerPrint is not enabled. ) 
09-15 12:02:58.334  3399  3567 I PowerManagerService: Sleeping (uid 1000)...
09-15 12:02:58.334  3944  3944 V KeyguardUpdateMonitor: stopListeningForFingerprint()
,09-15 12:02:58.334  3399  3567 D PowerManagerService: [s] UserActivityState : 4 -> 0
09-15 12:02:58.334  9438  9438 I InjectionManager: Inside getClassLibPath + mLibMap{0=, 1=}
09-15 12:02:58.334  3399  3567 D PowerManagerService: [PWL] sb acquire: PowerManagerService.Broadcasts
09-15 12:02:58.334  9438  9438 W ResourcesManager: getTopLevelResources: /system/priv-app/BadgeProvider_M/BadgeProvider_M.apk / 1.0 running in com.sec.android.provider.badge rsrc of package com.sec.android.provider.badge
09-15 12:02:58.334  4017  4017 D Recents_RecentsActivity: Screen off broadcast is received
09-15 12:02:58.334  4017  4017 D Recents_RecentsActivity: clearWindowFlag is getting called
,09-15 12:02:58.334  4017  4017 D Recents_RecentsActivity: dismissRecentsToHome, animated=false
09-15 12:02:58.334  3399  3469 I InjectionManagerService -AppFeature: getCoreFeaturePkgList :[]
09-15 12:02:58.344  9438  9438 D ResourcesManager: For user 0 new overlays fetched Null
,09-15 12:02:58.344  9438  9438 I InjectionManager: Inside getClassLibPath caller 
,09-15 12:02:58.344  9438  9438 W System  : ClassLoader referenced unknown path: /system/priv-app/BadgeProvider_M/lib/arm64
,09-15 12:02:58.354  9438  9438 D BadgeProvider: onCreate
09-15 12:02:58.354  9438  9438 D BadgeProvider: DatabaseHelper
,09-15 12:02:58.354  9438  9438 D InjectionManager: InjectionManager
,09-15 12:02:58.354  9438  9438 D InjectionManager: fillFeatureStoreMap com.sec.android.provider.badge
,09-15 12:02:58.354  9438  9438 I InjectionManager: Constructor com.sec.android.provider.badge, Feature store :{}
,09-15 12:02:58.354  9438  9438 I InjectionManager: featureStore :{}
,09-15 12:02:58.364  3399  3399 D LightsService: [api] [SvcLED] setFlashing :: id = 5, color = 0, mode = 14, onMS = 0, offMS = 0,  (uid: 1000 pid: 3399) 
,09-15 12:02:58.364  3399  3399 D LightsService: [SvcLED] setSvcLedStateLocked:: SvcLEDState : 0x0 -> 0x40 | SvcLED(id=5) set On
,09-15 12:02:58.364  3399  3399 D SensorService: SensorEventConnection::SocketBufferSize, SystemSocketBufferSize - 102400, 2097152
09-15 12:02:58.364  3399  3399 D SensorManager: registerListener :: 6, TMD4093 RGB Sensor, 200000, 0,  
09-15 12:02:58.364  3399  3573 D LightsService: [SvcLED]  onSensorChanged::light value = 24
09-15 12:02:58.364  3399  3399 D BatteryService: turn on LED for fully charged
09-15 12:02:58.364  3399  3573 D SensorManager: unregisterListener ::   
09-15 12:02:58.364  3399  3573 I LightsService: fileWriteInt : /sys/class/sec/led/led_lowpower  value : 0
09-15 12:02:58.364  3399  3573 D lights  : led_pattern : 5 +
,09-15 12:02:58.374  3399  3573 D lights  : led_pattern : 5 -
,09-15 12:02:58.374  3399  3573 D LightsService: [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=5) maintains its priority right
,09-15 12:02:58.374  9438  9448 D BadgeProvider: query, [selection] : null
09-15 12:02:58.374  3399  3573 V AlarmManager:  remove PendingIntent] PendingIntent{9e1e2c1: PendingIntentRecord{a8a8a66 android broadcastIntent}}
,09-15 12:02:58.394  3399  3399 I CAE     : handleMessage(CaPowerManager.java:182) - AP_SLEEP
,09-15 12:02:58.394  4734  4734 D AODMissedEventController: [com.android.contacts] badgeCount : 0, [com.android.mms] badgeCount : 0
09-15 12:02:58.394  3399  3399 I CAE     : updateApPowerStatus(SensorHubParserProvider.java:443) - AP_SLEEP
09-15 12:02:58.394  4734  4734 I AODService.ClockTimer: startAlarm : TICK
,09-15 12:02:58.404  3399  3399 I CAE     : sendCmdToSensorHub(SensorHubCommManager.java:162) - -76, 13, -46, 0,
09-15 12:02:58.404  3399  3399 D SensorHubManager: SendSensorHubData: send data = -76, 13, -46, 0
09-15 12:02:58.404  3399  3779 V AlarmManager: Add whitelist package alarm :PendingIntent{14abb6a: PendingIntentRecord{c916656 com.samsung.android.app.aodservice broadcastIntent}}
,09-15 12:02:58.404  3166  3213 D Sensorhubs: sendContextData: -76, 13, -46, 0
,09-15 12:02:58.404  3399  3399 I CAE     : sendCmdToSensorHub(SensorHubCommManager.java:162) - -63, 14, 10, 2, 58,
09-15 12:02:58.404  3399  3399 D SensorHubManager: SendSensorHubData: send data = -63, 14, 10, 2, 58
09-15 12:02:58.404  3166  3166 D Sensorhubs: sendContextData: -63, 14, 10, 2, 58
,09-15 12:02:58.404  4734  4734 I AODService.ClockTimer: startAlarm : SLEEP
,09-15 12:02:58.404  4734  4734 V AODService.ClockTimer: AOD Trigger: next AOD WAKEUP time is 9:0
,09-15 12:02:58.404  3399  3399 D MotionRecognitionService:   mReceiver.onReceive : ACTION_SCREEN_OFF
,09-15 12:02:58.404  4734  4734 D AODService.ClockTimer: startAlarm is canceled. triggerAtMillis = -1, currentTime = 1473933778417
09-15 12:02:58.404  4734  4734 I AODService.ClockTimer: stopAlarm : WAKEUP
,09-15 12:02:58.404  3399  3969 V AlarmManager:  remove PendingIntent] PendingIntent{fe8485b: PendingIntentRecord{17acbc4 com.samsung.android.app.aodservice broadcastIntent}}
,09-15 12:02:58.404  4734  4734 D BatteryController: saveBatteryData : level[100], status[5]
,09-15 12:02:58.414  3006  3006 I SurfaceFlinger: id=23 createSurf (1440x2560),1 flag=404, BOD
,09-15 12:02:58.414  3399  4397 V WindowOrientationListener: setCurrentAppOrientation :5
09-15 12:02:58.414  3399  4397 V WindowManager: rotationForOrientationLw(orient=5, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false mMobileKeyboardEnabled=false displayId=0
,09-15 12:02:58.414  4734  7416 D mali_winsys: EGLint new_window_surface(egl_winsys_display*, void*, EGLSurface, EGLConfig, egl_winsys_surface**, egl_color_buffer_format*, EGLBoolean) returns 0x3000,  [1440x2560]-format:1
,09-15 12:02:58.424  3399  3794 I Sensors : #>LightSensor r=18 g=12 b=11 c=41 atime=245 again=64 lux=29
,09-15 12:02:58.424  3399  3537 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{d54b8f8 u-1 com.samsung.settings.action.directaccess.CLOSE_DIALOG qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{288f651 9309:com.samsung.android.SettingsReceiver/1000}
09-15 12:02:58.424  3399  3820 D MotionRecognitionService: Screen off setAccIntStatus 
,09-15 12:02:58.424  3399  3820 E MotionRecognitionService:  handler : SCREEN_OFF end 
,09-15 12:02:58.424  3399  3399 D UniversalCredentialManagerService: inside mBReciever onReceive : android.intent.action.SCREEN_OFF
,09-15 12:02:58.434  3399  3399 D UniversalCredentialManagerService: ****MSG_LOCK_STATUS_UPDATE block started****
,09-15 12:02:58.434  3399  3562 V WindowAnimator: hide by NightClock Window{b724853 u0 d0 StatusBar}
09-15 12:02:58.434  3399  3399 D UniversalCredentialManagerService: notifyChangeToPlugin is called for Lock status update...
09-15 12:02:58.434  3399  3399 D UcmService: notifyChangeToPlugin event 16
09-15 12:02:58.434  3399  3399 D UcmService: checkCallerPermissionFor is called for method-notifyChangeToPlugin
09-15 12:02:58.434  3399  3399 I UcmService: checkIfNotify for cs Name = com.sec.smartcard.manager:com.samsung.ucs.agent.baiMobile Package name = com.sec.smartcard.manager
09-15 12:02:58.434  3399  3399 D UcmService: notifying to unmanaged plugin
09-15 12:02:58.434  4330  4359 E ucsBai_agentService: notifyChange NOT SUPPORTED
09-15 12:02:58.434  3399  3399 D UcmService: agentService com.sec.smartcard.manager:com.samsung.ucs.agent.baiMobile notify status - 0
09-15 12:02:58.434  3399  3399 D UcmService: agentService status-0
09-15 12:02:58.434  3399  3399 I UcmService: checkIfNotify for cs Name = com.samsung.ucs.agent.ese:eSE Credential Storage Package name = com.samsung.ucs.agent.ese
09-15 12:02:58.434  3399  3399 D UcmService: notifying to managed plugin
09-15 12:02:58.434  3399  3399 D UcmService: checkIfNotify: Valid userid - 0
09-15 12:02:58.434  3399  3399 D PolicyManager: PolicyManager.isStorageEnabled() for userId = 0
09-15 12:02:58.434  3399  3399 D UniversalCredentialManagerService: checkCallerPermissionFor is called for method-isCredentialStorageManagedAsUser
09-15 12:02:58.434  3399  3399 D UniversalCredentialManagerService: isCredentialStorageManagedAsUser is called....
09-15 12:02:58.444  3399  3399 D PolicyManager: PolicyManager.isStorageEnabled() result = false
09-15 12:02:58.444  3399  3399 D UcmService: agentService com.samsung.ucs.agent.ese:eSE Credential Storage not notified
09-15 12:02:58.444  3399  3399 D UcmService: agentService status-0
09-15 12:02:58.444  3399  3399 I UcmService: checkIfNotify for cs Name = com.samsung.ucs.agent.boot:com.samsung.ucs.agent.boot Package name = com.samsung.ucs.agent.boot
09-15 12:02:58.444  3399  3399 D UcmService: notifying to unmanaged plugin
09-15 12:02:58.444  4340  4404 D BootAgentService: notifyChange eventId-16
09-15 12:02:58.444  3399  3399 D UcmService: agentService com.samsung.ucs.agent.boot:com.samsung.ucs.agent.boot notify status - -1
09-15 12:02:58.444  3399  3399 D UcmService: agentService status--1
09-15 12:02:58.444  3399  3399 D UniversalCredentialManagerService: ****MSG_LOCK_STATUS_UPDATE block ended****
09-15 12:02:58.444  3399  4292 D InputMethodManagerService: windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,09-15 12:02:58.444  7485  7485 D SamsungIME: IMPL finishInput
09-15 12:02:58.444  7485  7485 D SamsungIME: SwiftKeyWrapper writeDBdataToFileOnFinishInput
09-15 12:02:58.444  7485  7485 D SamsungIME: saveAndClear +
09-15 12:02:58.444  3399  4442 W InputMethodManagerService: Starting input on non-focused client com.android.internal.view.IInputMethodClient$Stub$Proxy@53e81d1 (uid=10171 pid=9367)
09-15 12:02:58.444  7485  7485 D SamsungIME: saveAndClear -
09-15 12:02:58.444  3399  3399 I WifiTrafficPoller: evaluateTrafficStatsPolling
09-15 12:02:58.444  7485  7485 D SamsungIME: onStartInput: No inputType, No imeOption, isInputViewShown = false, isExtractViewShown = false, isShowInputRequested = false, isConfigChanged = false
09-15 12:02:58.454  3399  4279 I ActivityManager: Killing 8075:com.samsung.storyservice/5004 (adj 15): DHA:empty #33
09-15 12:02:58.454  3399  3855 D WifiStateMachine: handleScreenStateChanged, screen off, set scan interval as max value  !!!
09-15 12:02:58.454  3399  3855 D WifiNative-wlan0: callSECApiVoid - ID [19]
09-15 12:02:58.454  4109  4109 I wpa_supplicant: set PERIODIC_SCAN_INTERVAL_MAX to 128sec !!!
09-15 12:02:58.454  3399  3855 E WifiNative-wlan0: do suspend true
09-15 12:02:58.464  4734  4734 D ViewRootImpl: MSG_RESIZED_REPORT: ci=Rect(0, 0 - 0, 0) vi=Rect(0, 0 - 0, 0) or=1
09-15 12:02:58.464  4734  4734 W DisplayListCanvas: DisplayListCanvas is started on unbinded RenderNode (without mOwningView)
09-15 12:02:58.464  3399  3399 D NotificationService: ACTION_SCREEN_OFF
09-15 12:02:58.464  3399  3399 D LightsService: [api] [SvcLED] turnOff:: id = 6 (uid: 1000 pid: 3399) 
09-15 12:02:58.464  3399  3399 D LightsService: [SvcLED] setSvcLedStateLocked:: SvcLEDState : 0x40 -> 0x40 | SvcLED(id=6) set Off
09-15 12:02:58.464  3399  3399 D SensorService: SensorEventConnection::SocketBufferSize, SystemSocketBufferSize - 102400, 2097152
09-15 12:02:58.464  3399  3399 D SensorManager: registerListener :: 6, TMD4093 RGB Sensor, 200000, 0,  
09-15 12:02:58.464  3399  3573 D LightsService: [SvcLED]  onSensorChanged::light value = 29
09-15 12:02:58.464  3399  3399 D EdgeLight: Turning off
09-15 12:02:58.464  3399  3573 D SensorManager: unregisterListener ::   
09-15 12:02:58.464  3399  3573 D LightsService: [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=5) maintains its priority right
09-15 12:02:58.464  3399  3573 V AlarmManager:  remove PendingIntent] PendingIntent{9e1e2c1: PendingIntentRecord{a8a8a66 android broadcastIntent}}
09-15 12:02:58.474  3159  4121 D audio_hw_primary: adev_set_parameters: enter: kvpairs: screen_state=off
09-15 12:02:58.474  3399  4054 V WindowStateAnimator: Finishing drawing window Window{497e555 u0 d0 AOD}: mDrawState=DRAW_PENDING
09-15 12:02:58.484  3399  4443 D ActivityManager: isAutoRunBlockedApp:: com.samsung.storyservice, Auto Run ON
,09-15 12:02:58.484  3944  3944 D PanelView: updateQsState
09-15 12:02:58.484  3944  3944 D KeyguardSwipeHelper: reset()
09-15 12:02:58.484  3944  3944 D KeyguardUnlockEventHandler: reset()
09-15 12:02:58.484  3944  3944 D KeyguardSwipeHelper: resetChildViewVI()
09-15 12:02:58.494  3006  3006 D libEGL  : eglInitialize EGLDisplay = 0x7fc83bb698
09-15 12:02:58.494  3399  3399 I MdnieScenarioControlService: action  :  android.intent.action.SCREEN_OFF
09-15 12:02:58.494  3399  3399 I FingerprintService: onReceive: android.intent.action.SCREEN_OFF
09-15 12:02:58.504  3399  3399 I BackgroundCompactionService: Schedule Type1 BGCompaction
09-15 12:02:58.504  3399  3399 D WifiService: ACTION_SCREEN_OFF, mSContextManager.unregisterListener !!
09-15 12:02:58.504  3399  3399 D SContextService: unregisterCallback() : Listener = android.hardware.scontext.SContextService$Listener@9e9e085, Service = Activity Tracker, used = 0
09-15 12:02:58.504  3399  3858 D WifiController: ApOrStaEnabledState  msg.what= 155651
09-15 12:02:58.504  3399  3399 W CAE     : unregisterCallback(ContextAwareService.java:206) - [unregi 01] Mutex is locked for ACTIVITY_TRACKER
09-15 12:02:58.504  3399  3399 V CAE     : stop(ContextProvider.java:155)
09-15 12:02:58.504  3399  3399 V CAE     : clear(ActivityTrackerRunner.java:108)
09-15 12:02:58.504  3399  3399 V CAE     : disable(ActivityTrackerRunner.java:96)
09-15 12:02:58.504  3399  3399 I CAE     : sendCmdToSensorHub(SensorHubCommManager.java:162) - -78, 26, 0, 0, 0, 0, 0, 0, 0, 0,
09-15 12:02:58.504  3399  3399 D SensorHubManager: SendSensorHubData: send data = -78, 26, 0, 0, 0, 0, 0, 0, 0, 0
09-15 12:02:58.504  3166  3213 D Sensorhubs: sendContextData: -78, 26, 0, 0, 0, 0, 0, 0, 0, 0
09-15 12:02:58.514  3399  3399 D CAE     : getFaultDetectionResult(ActivityTrackerRunner.java:154) - true
09-15 12:02:58.514  3399  3399 I CAE     : notifyCmdProcessResultObserver(ContextProvider.java:627) - CheckResult = 0, Cause = Success
,09-15 12:02:58.524  3399  3399 D CAE     : doCommendProcess(ContextAwareService.java:433) - complete notify the operation result.
,09-15 12:02:58.524  3399  3399 I CAE     : displayUsedCountForService(ContextAwareService.java:525) - totalCnt = 0, serviceCount = 0, subCollectionCount = 0
09-15 12:02:58.524  3399  3399 D CAE     : showListenerList(ContextAwareService.java:366) - ===== Context Aware Service List =====
09-15 12:02:58.524  3399  3399 I CAE     : showListenerList(ContextAwareService.java:375) - Listener : com.samsung.android.contextaware.manager.ContextAwareService$Listener@529c78c, Service : ACTIVITY_TRACKER_CURRENT_INFO(1)
09-15 12:02:58.524  3399  3399 I CAE     : showListenerList(ContextAwareService.java:375) - Listener : com.samsung.android.contextaware.manager.ContextAwareService$Listener@171875e, Service : DEVICE_PHYSICAL_CONTEXT_MONITOR(1)
09-15 12:02:58.524  3399  3399 W CAE     : unregisterCallback(ContextAwareService.java:241) - [unregi 02] Mutex is unlocked for ACTIVITY_TRACKER
,09-15 12:02:58.524  3399  3399 D SContextService: 	.unregisterCallback : 2, client=
09-15 12:02:58.524  3399  3399 D SContextService: ===== SContext Service List =====
09-15 12:02:58.524  3399  3399 D SContextService: Listener : android.hardware.scontext.SContextService$Listener@549773f, Service : Device Physical Context Monitor
09-15 12:02:58.524  3399  3399 D SContextManager:   .unregisterListener : listener = com.android.server.wifi.WifiServiceImpl$11@cf451fc, service=Activity Tracker
,09-15 12:02:58.524  3399  3562 D IpRemoteDisplayController: intent received android.intent.action.SCREEN_OFF
,09-15 12:02:58.524  3399  3562 D IpRemoteDisplayController: Bridge Server is not available
,09-15 12:02:58.534  3399  3399 D NetworkPolicy: mScreenReceiver: ACTION_SCREEN_OFF, extra: 3
09-15 12:02:58.534  3399  3853 D NetworkPolicy: MSG_SCREEN_ON_CHANGED: 3
09-15 12:02:58.534  3399  3853 D NetworkPolicy: isUidForegroundLocked: 10007, mScreenOn: false, uidstate: 0, mProxSensorScreenOff: false
,09-15 12:02:58.534  3399  3853 D NetworkPolicy: isUidForegroundLocked: 10062, mScreenOn: false, uidstate: 0, mProxSensorScreenOff: false
,09-15 12:02:58.534  3399  3527 D GpsLocationProvider: receive broadcast intent, action: android.intent.action.SCREEN_OFF
,09-15 12:02:58.544  4206  4206 D FusedLocationReceiver: BroadcastReceiver : ACTION_SCREEN_OFF
,09-15 12:02:58.554  4255  9452 D NfcService: call the applyRouting
,09-15 12:02:58.564  3944  4111 D NetworkController.MobileSignalController(0/2147483643): onDataActivity: direction=0
,09-15 12:02:58.564  4280  4280 D Launcher.Workspace: exitWidgetResizeMode. isClearResizeFrame is false
,09-15 12:02:58.604  3399  3794 I Sensors : #>LightSensor r=17 g=12 b=10 c=40 atime=245 again=64 lux=31
,09-15 12:02:58.614  5041  5041 D BtGatt.GattService: LCD turned off
,09-15 12:02:58.614  5041  5210 D BtGatt.ScanManager: handleLcdOffIntent
09-15 12:02:58.614  5041  5210 D BtGatt.ScanManager: handleLcdOffIntent : thresholdScanValue is = 10 mLastConfiguredScanValue =0
,09-15 12:02:58.654  4560  9453 D MdnsClient: Multicast lock held. Releasing
,09-15 12:02:58.684  3399  5992 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 b.J.a:-1 b.J.a:-1 b.L.run:-1 android.os.Handler.handleCallback:739 
,09-15 12:02:58.694  3399  3537 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{841af10 u0 com.samsung.android.sm.lowpowercontext.START_ANALYSIS qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{fa77d28 8866:com.samsung.android.sm.provider/1000}
,09-15 12:02:58.704  3399  5991 D SSRM:n  : SIOP:: AP = 330, PST = 308 (W:6), CP = 254, CUR = 153, LCD = 0
,09-15 12:02:58.724  3399  3399 I SurveyLogManager: mDeviceInfo.mScreen = false
,09-15 12:02:58.734  3399  5991 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
,09-15 12:02:58.754  7485  7485 E SamsungIME: invoke(): method is null
,09-15 12:02:58.764  4664  4664 D [Weather Widget]  WeatherService: {[EC3334F14841398C8B464A72D0E61AB7C564889C89112557F2146D56794659083956C77974A4825103AB5C5D4AC85EDA0E41DE4F26DD020CF7906DED0A6ECA9F]}
,09-15 12:02:58.764  4664  4664 D [Weather Widget]  WeatherService: {[EC3334F14841398C8B464A72D0E61AB71D02215B774510884CB3BFD0FBDB0EDC]}
09-15 12:02:58.764  4664  4664 D [Weather Widget]  : {[3AE6950019B083611567B0F9442DB03EEFA9050249635C043F7E254E316C2550]}
,09-15 12:02:58.764  3399  3895 D PowerManagerService: [PWL] sb release: PowerManagerService.Broadcasts
,09-15 12:02:58.774  4664  4664 D [Weather Widget]  WeatherService: {[44BE909F148A112BE24DB9207B7094FCDA9342562AE17780A60BEC6E95DC6F0D]}
,09-15 12:02:58.774  3399  4235 I ActivityManager: Killing 8359:com.google.android.gm/u0a108 (adj 15): DHA:empty #33
,09-15 12:02:58.784  3399  3794 I Sensors : #>LightSensor r=18 g=12 b=11 c=41 atime=245 again=64 lux=29
,09-15 12:02:58.794  3399  4310 D ActivityManager: isAutoRunBlockedApp:: com.google.android.gm, Auto Run ON
,09-15 12:02:58.804  3399  9455 I BatteryStatsDumper: In refreshStats isReason Screen ON/OFF: true
,09-15 12:02:58.804  3399  9455 D BluetoothAdapter: STATE_ON
,09-15 12:02:58.814  3399  3470 V AlarmManager:  remove PendingIntent] PendingIntent{23c840e: PendingIntentRecord{d9a888f com.android.bluetooth broadcastIntent}}
,09-15 12:02:58.814  3399  4292 V AlarmManager:  remove PendingIntent] PendingIntent{4d4ae2f: PendingIntentRecord{d9a888f com.android.bluetooth broadcastIntent}}
,09-15 12:02:58.844  3399  9455 D BatteryStatsImpl: poolsize= 1, curBatteryRealtime= 0, mUpdateTime= 0, mTimeout= 0, mNesting= 0, mTotalTime= 0
,09-15 12:02:58.884  3399  9455 D BatteryStatsImpl: poolsize= 1, curBatteryRealtime= 0, mUpdateTime= 0, mTimeout= 0, mNesting= 0, mTotalTime= 0
,09-15 12:02:58.884  3399  9455 I BatteryStatsDumper: Previous Battery Level: 100 Current Level: 100 Delta: 0
,09-15 12:02:58.894  4734  4734 I AlpmModeManager: startAlpmMode : state  = IDLE
,09-15 12:02:58.894  4734  4734 I AlpmModeManager: handleUnblankDisplay: state  = IDLE
09-15 12:02:58.894  4734  4734 V AlpmModeManager: handleUnblankDisplay: setDoze [DISPLAY_STATE_DOZE]
09-15 12:02:58.894  4734  4734 D AlpmModeManager: getLastAlpmHlpmBright : HighNit[true], AlpmHlpm[1], NitMode[[ALPM]_60NIT_ON]
,09-15 12:02:58.894  3399  4054 I PowerManagerService: [api] setDozeOverrideFromAod AlpmHlpmSysfs = 3, screenState = 3, Brightness = 0, wakefulness = false
09-15 12:02:58.894  3399  4054 D PowerManagerService: [s] UserActivityState : 0 -> 4
09-15 12:02:58.894  4734  4734 I AlpmModeManager: handleUnblankDisplay: AlpmModeManager wakeLock [ACQUIRE]
,09-15 12:02:58.894  3399  3469 D PowerManagerService: [api] acquire WakeLock flags=0x40 tag=AlpmModeManager uid=10000 pid=4734
09-15 12:02:58.894  3399  3469 I libsuspend: !@autosuspend_wakeup_count_disable
09-15 12:02:58.894  3399  3469 D PowerManagerService: mDisplayReady: false
09-15 12:02:58.894  3399  3469 I libsuspend: !@autosuspend_wakeup_count_disable done
,09-15 12:02:58.894  3399  3567 D DisplayPowerController: animateScreenStateChange[0]: target=3
09-15 12:02:58.894  3399  3469 D PowerManagerService: [PWL] sb acquire: PowerManagerService.Display
09-15 12:02:58.894  3399  3567 D DisplayPowerState: !@ [0] ColorFade exit
09-15 12:02:58.894  3399  3567 D PowerManagerService: [input device light] onColorFadeExit(true)
,09-15 12:02:58.894  3006  3015 D libEGL  : eglTerminate EGLDisplay = 0x7f87e80e78
09-15 12:02:58.894  3006  3015 D libEGL  : eglTerminate EGLDisplay = 0x7f87e80e78
,09-15 12:02:58.894  3006  3017 I SurfaceFlinger: id=22 Removed DolorFade (9/11),
09-15 12:02:58.904  3006  4328 I SurfaceFlinger: id=22 Removed DolorFade (-2/11)
09-15 12:02:58.904  3399  3567 D DisplayPowerController: [Dual Screen Compatible] state[0] :3
09-15 12:02:58.904  3399  3567 D DisplayPowerController: getFinalBrightness : Summary is 1 -> 1
,09-15 12:02:58.904  3399  3567 D DisplayPowerController: Animating brightness: target=1, rate=2000 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
09-15 12:02:58.904  3399  3567 D DisplayPowerState: Requesting new screen state: [0] state=DOZE, backlight (By colorFade)=0
09-15 12:02:58.904  3399  3898 D DisplayPowerState: Updating screen state [0]: state=DOZE, backlight (by ColorFade)=0
09-15 12:02:58.904  3399  3575 D DisplayManagerService: !@display_state: OFF -> DOZE brightness: 0 -> 0
,09-15 12:02:58.904  3006  3006 D SurfaceFlinger: Set power mode=1, type=0 flinger=0x7f88103c00
09-15 12:02:58.904  3399  3562 I DisplayManagerService: Display device changed state: "Wbudowany ekran", DOZE
09-15 12:02:58.904  3006  3006 I hwcomposer: int exynos_setPowerMode(hwc_composer_device_1*, int, int):: disp(0), mode(1)
09-15 12:02:58.904  3399  3562 I DisplayManagerService: Display device changed state: "ActivityViewVirtualDisplay", DOZE
,09-15 12:02:58.914  3399  4898 D PowerManagerService: [api] acquire WakeLock flags=0x80 tag=Window:AOD uid=1000 pid=3399
,09-15 12:02:58.924  3399  4442 D PowerManagerService: [api] acquire WakeLock flags=0x80 tag=Window:com.test.thalitest/com.test.thalitest.MainActivity uid=1000 pid=3399
,09-15 12:02:58.934  3399  3898 D lights  : lcd : 1 +
09-15 12:02:58.934  3399  3567 D DisplayPowerController: animateScreenStateChange[0]: target=3
09-15 12:02:58.934  3399  3898 D lights  : lcd : 1 -
09-15 12:02:58.934  3399  3567 D DisplayPowerController: [Dual Screen Compatible] state[0] :3
09-15 12:02:58.934  3399  3567 D DisplayPowerController: getFinalBrightness : Summary is 1 -> 1
09-15 12:02:58.934  3399  3567 D DisplayPowerController: Animating brightness: target=1, rate=2000 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
,09-15 12:02:58.954  3399  4292 D PowerManagerService: [api] acquire WakeLock flags=0x80 tag=Window:AOD uid=1000 pid=3399
,09-15 12:02:58.964  3399  9455 I BatteryStatsDumper: Writing to database completed
,09-15 12:02:58.964  4734  4734 D DefaultClockView: Start AOD Enter Animation
,09-15 12:02:58.964  3399  3969 D PowerManagerService: [api] acquire WakeLock flags=0x80 tag=Window:AOD uid=1000 pid=3399
,09-15 12:02:58.984  3399  4397 D PowerManagerService: [api] acquire WakeLock flags=0x80 tag=Window:AOD uid=1000 pid=3399
,09-15 12:02:59.024  3399  3902 W System.err: remove failed: ENOENT (No such file or directory) : /data/system/recent_tasks/10_task.xml.bak
,09-15 12:02:59.074  3399  3399 D PowerManagerService: [api] release WakeLock flags=0x80 tag=Window:com.test.thalitest/com.test.thalitest.MainActivity uid=1000 pid=3399 (0x0)
,09-15 12:02:59.124  4017  4017 D Recents : onTaskStackChanged
,09-15 12:02:59.134  3399  3399 D PowerManagerService: [api] release WakeLock flags=0x80 tag=Window:AOD uid=1000 pid=3399 (0x0)
,09-15 12:02:59.144  3399  3575 D SurfaceControl: Excessive delay in setPowerMode(): 247ms
,09-15 12:02:59.144  3399  3575 D PowerManagerUtil: Excessive delay in !@display_state: DOZE: 248ms
09-15 12:02:59.144  3006  3006 D libEGL  : eglTerminate EGLDisplay = 0x7fc83bb7b8
,09-15 12:02:59.144  3399  3575 D PowerManagerUtil: Excessive delay in DisplayManagerInternal.requestDesiredDisplayState: 248ms
09-15 12:02:59.154  3399  3567 I libsuspend: !@autosuspend_wakeup_count_enable
09-15 12:02:59.154  3399  3567 D DisplayPowerController: animateScreenStateChange[0]: target=3
,09-15 12:02:59.154  3399  3567 I libsuspend: !@autosuspend_wakeup_count_enable done
09-15 12:02:59.154  3399  3567 D DisplayPowerController: [Dual Screen Compatible] state[0] :3
09-15 12:02:59.154  3006  3006 D libEGL  : eglInitialize EGLDisplay = 0x7fc83bb698
09-15 12:02:59.154  3399  3567 D DisplayPowerController: getFinalBrightness : Summary is 1 -> 1
,09-15 12:02:59.154  3399  3567 D DisplayPowerController: Animating brightness: target=1, rate=2000 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
09-15 12:02:59.154  3399  3567 D DisplayPowerController: animateScreenStateChange[0]: target=3
09-15 12:02:59.154  3399  3567 D DisplayPowerController: [Dual Screen Compatible] state[0] :3
,09-15 12:02:59.154  3399  3567 D DisplayPowerController: getFinalBrightness : Summary is 1 -> 1
09-15 12:02:59.154  3399  3567 D DisplayPowerController: Animating brightness: target=1, rate=2000 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
09-15 12:02:59.154  3399  3567 D PowerManagerService: [s] DisplayPowerCallbacks : onStateChanged()
,09-15 12:02:59.154  3399  3567 D PowerManagerService: mDisplayReady: true
09-15 12:02:59.154  3399  3567 D PowerManagerService: [PWL] sb release: PowerManagerService.Display
09-15 12:02:59.154  3399  3567 D DisplayPowerController: animateScreenStateChange[0]: target=3
,09-15 12:02:59.154  3399  3567 D DisplayPowerController: [Dual Screen Compatible] state[0] :3
09-15 12:02:59.154  3399  3567 D DisplayPowerController: getFinalBrightness : Summary is 1 -> 1
09-15 12:02:59.154  3399  3567 D DisplayPowerController: Animating brightness: target=1, rate=2000 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
,09-15 12:02:59.164  3399  4442 D PowerManagerService: [api] acquire WakeLock flags=0x80 tag=Window:AOD uid=1000 pid=3399
,09-15 12:02:59.164  3006  3006 D libEGL  : eglInitialize EGLDisplay = 0x7fc83bb698
,09-15 12:02:59.164  4734  4734 I AlpmModeManager: handleAlpmModeOn: state  = UNBLANK
,09-15 12:02:59.174  3399  3779 D PowerManagerService: [api] acquire WakeLock flags=0x80 tag=Window:AOD uid=1000 pid=3399
,09-15 12:02:59.184  4734  4734 D DefaultClockView: End AOD Enter Animation : ForceStopAnimation : false
09-15 12:02:59.184  4734  4734 D AODService: : state = Start AOD mode!!
,09-15 12:02:59.184  3399  4443 D PowerManagerService: [api] acquire WakeLock flags=0x80 tag=Window:AOD uid=1000 pid=3399
,09-15 12:02:59.254  4734  4734 D BatteryMeterView: onDraw batteryColor : -986896
,09-15 12:02:59.254  3399  3996 D PowerManagerService: [api] acquire WakeLock flags=0x80 tag=Window:AOD uid=1000 pid=3399
,09-15 12:02:59.414  3399  3399 D PowerManagerService: [api] release WakeLock flags=0x80 tag=Window:AOD uid=1000 pid=3399 (0x0)
09-15 12:02:59.484  4734  4734 I AlpmModeManager: handleBlankDisplay: current state [ALPM_ON] to [ALPM_STATE_BLANK]
09-15 12:02:59.484  4734  4734 V AlpmModeManager: handleBlankDisplay: setDoze [DISPLAY_STATE_DOZE_SUSPEND] Keep bright
09-15 12:02:59.484  3399  4292 I PowerManagerService: [api] setDozeOverrideFromAod AlpmHlpmSysfs = -1, screenState = 4, Brightness = 0, wakefulness = false
09-15 12:02:59.484  3399  4292 I libsuspend: !@autosuspend_wakeup_count_disable
09-15 12:02:59.484  3399  4292 D PowerManagerService: setDozeModeBySysfs:  value is -1 , we ignore it. 
09-15 12:02:59.484  3399  4292 I libsuspend: !@autosuspend_wakeup_count_disable done
09-15 12:02:59.484  3399  4292 D PowerManagerService: mDisplayReady: false
09-15 12:02:59.484  3399  3567 D DisplayPowerController: animateScreenStateChange[0]: target=4
09-15 12:02:59.484  3399  4292 D PowerManagerService: [PWL] sb acquire: PowerManagerService.Display
09-15 12:02:59.484  3399  3567 D DisplayPowerController: [Dual Screen Compatible] state[0] :4
09-15 12:02:59.484  3399  3567 D DisplayPowerController: getFinalBrightness : Summary is 1 -> 1
09-15 12:02:59.484  3006  3006 D SurfaceFlinger: Set power mode=3, type=0 flinger=0x7f88103c00
09-15 12:02:59.484  3399  3567 D DisplayPowerController: Animating brightness: target=1, rate=0 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
09-15 12:02:59.484  3006  3006 I hwcomposer: int exynos_setPowerMode(hwc_composer_device_1*, int, int):: disp(0), mode(3)
09-15 12:02:59.484  3399  3575 D DisplayManagerService: !@display_state: DOZE -> DOZE_SUSPEND brightness: 1 -> 1
09-15 12:02:59.484  3399  3562 I DisplayManagerService: Display device changed state: "Wbudowany ekran", DOZE_SUSPEND
09-15 12:02:59.484  3399  3562 I DisplayManagerService: Display device changed state: "ActivityViewVirtualDisplay", DOZE_SUSPEND
09-15 12:02:59.504  3399  3567 D DisplayPowerController: animateScreenStateChange[0]: target=4
09-15 12:02:59.504  3399  3567 D DisplayPowerController: [Dual Screen Compatible] state[0] :4
09-15 12:02:59.504  3399  3567 D DisplayPowerController: getFinalBrightness : Summary is 1 -> 1
09-15 12:02:59.504  3399  3567 I libsuspend: !@autosuspend_wakeup_count_enable
09-15 12:02:59.504  3399  3567 D DisplayPowerController: Animating brightness: target=1, rate=0 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
09-15 12:02:59.504  3399  3567 I libsuspend: !@autosuspend_wakeup_count_enable done
09-15 12:02:59.504  3399  3567 D DisplayPowerController: animateScreenStateChange[0]: target=4
09-15 12:02:59.504  3399  3567 D DisplayPowerController: [Dual Screen Compatible] state[0] :4
09-15 12:02:59.504  3399  3567 D DisplayPowerController: getFinalBrightness : Summary is 1 -> 1
09-15 12:02:59.504  3399  3567 D DisplayPowerController: Animating brightness: target=1, rate=0 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
09-15 12:02:59.504  3399  3567 D PowerManagerService: [s] DisplayPowerCallbacks : onStateChanged()
09-15 12:02:59.504  3399  3567 D PowerManagerService: mDisplayReady: true
09-15 12:02:59.504  3399  3567 D PowerManagerService: [PWL] sb release: PowerManagerService.Display
09-15 12:02:59.794  3399  5992 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 b.J.a:-1 b.J.a:-1 b.L.run:-1 android.os.Handler.handleCallback:739 
09-15 12:02:59.814  3399  3537 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{2faac3c u0 com.samsung.android.sm.lowpowercontext.START_ANALYSIS qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{fa77d28 8866:com.samsung.android.sm.provider/1000}
09-15 12:02:59.984  3399  3814 V AlarmManager: Expired Alarm result :8
,09-15 12:03:00.404  3399  3814 V AlarmManager: Expired Alarm result :4
,09-15 12:03:00.404  3399  3814 V AlarmManager: Send whitelist package alarm :PendingIntent{14abb6a: PendingIntentRecord{c916656 com.samsung.android.app.aodservice broadcastIntent}}
,09-15 12:03:00.404  3944  3944 D KeyguardUpdateMonitor: received broadcast android.intent.action.TIME_TICK
09-15 12:03:00.404  3944  3944 D KeyguardUpdateMonitor: handleTimeUpdate
,09-15 12:03:00.424  3944  3944 D Clock   : received broadcast android.intent.action.TIME_TICK
,09-15 12:03:00.494  3944  3944 D DateView: received broadcast android.intent.action.TIME_TICK
,09-15 12:03:00.514  4734  4734 D AODService.ClockTimer: onReceive : com.samsung.android.app.aodservice.ClockTimer.TICK, mWakeUp = true
,09-15 12:03:00.514  4734  4734 V BatteryController: getBatteryLevel[100.0], batteryStatus[5]
,09-15 12:03:00.524  3399  4899 W CAE     : setCAProperty(ContextAwareService.java:578) - [setProperty 01] Mutex is locked for DEVICE_PHYSICAL_CONTEXT_MONITOR
,09-15 12:03:00.524  3399  4899 I CAE     : setPropertyValue(DevicePhysicalContextMonitorRunner.java:155) - Get status
09-15 12:03:00.524  3399  4899 I CAE     : sendCmdToSensorHub(SensorHubCommManager.java:162) - -72, 56, 1, 1,
09-15 12:03:00.524  3399  4899 D SensorHubManager: SendSensorHubData: send data = -72, 56, 1, 1
,09-15 12:03:00.524  3166  3166 D Sensorhubs: sendContextData: -72, 56, 1, 1
,09-15 12:03:00.524  3399  4899 I CAE     : setCAProperty(ContextAwareService.java:583) - result : true
,09-15 12:03:00.524  3399  4899 W CAE     : setCAProperty(ContextAwareService.java:584) - [setProperty 02] Mutex is unlocked for DEVICE_PHYSICAL_CONTEXT_MONITOR
09-15 12:03:00.524  3399  4899 D SContextService: requestToUpdate() : service = Device Physical Context Monitor
09-15 12:03:00.524  4734  4734 D SContextManager:   .requestToUpdate : listener = com.samsung.android.app.aodservice.AODService$7@abcd199, service=Device Physical Context Monitor
09-15 12:03:00.524  4734  4734 I AlpmModeManager: startAlpmMode : state  = BLANK
,09-15 12:03:00.524  4734  4734 D DefaultClockView: Window showed. Time views updating
09-15 12:03:00.524  3399  4310 D PowerManagerService: [api] acquire WakeLock flags=0x80 tag=Window:AOD uid=1000 pid=3399
,09-15 12:03:00.524  3399  4310 I libsuspend: !@autosuspend_wakeup_count_disable
,09-15 12:03:00.524  3399  4310 D PowerManagerService: mDisplayReady: false
,09-15 12:03:00.524  3399  4310 I libsuspend: !@autosuspend_wakeup_count_disable done
,09-15 12:03:00.524  3399  3567 D DisplayPowerController: animateScreenStateChange[0]: target=3
09-15 12:03:00.524  4734  4734 D AODUpdatePositionController: updatePosition: direction[5] updatePosition: X[-8] Y[264] NewPositionTimer[59]
09-15 12:03:00.524  3399  4310 D PowerManagerService: [PWL] sb acquire: PowerManagerService.Display
09-15 12:03:00.524  3006  3006 D SurfaceFlinger: Set power mode=1, type=0 flinger=0x7f88103c00
09-15 12:03:00.524  3399  3567 D DisplayPowerController: [Dual Screen Compatible] state[0] :3
09-15 12:03:00.524  3006  3006 I hwcomposer: int exynos_setPowerMode(hwc_composer_device_1*, int, int):: disp(0), mode(1)
09-15 12:03:00.524  3399  3567 D DisplayPowerController: getFinalBrightness : Summary is 1 -> 1
,09-15 12:03:00.524  4734  4734 D DefaultClockView: LocalTime Pattern : HH:mm
09-15 12:03:00.524  3399  3567 D DisplayPowerController: Animating brightness: target=1, rate=2000 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
09-15 12:03:00.524  3399  3575 D DisplayManagerService: !@display_state: DOZE_SUSPEND -> DOZE brightness: 1 -> 1
09-15 12:03:00.534  4734  4734 D TimeViewHolder: onTimeUpdate: timeZone:libcore.util.ZoneInfo[id="Europe/Warsaw",mRawOffset=3600000,mEarliestRawOffset=3600000,mUseDst=true,mDstSavings=3600000,transitions=167] isSplitHour:false isSingleView:false isAMPMonLeft:null time01: 12:03 time02: null ampm: null
09-15 12:03:00.524  3399  3562 I DisplayManagerService: Display device changed state: "Wbudowany ekran", DOZE
,09-15 12:03:00.524  3399  3562 I DisplayManagerService: Display device changed state: "ActivityViewVirtualDisplay", DOZE
,09-15 12:03:00.534  3399  3567 D DisplayPowerController: animateScreenStateChange[0]: target=3
,09-15 12:03:00.534  3399  3567 D DisplayPowerController: [Dual Screen Compatible] state[0] :3
09-15 12:03:00.534  3399  3567 I libsuspend: !@autosuspend_wakeup_count_enable
09-15 12:03:00.534  3399  3567 D DisplayPowerController: getFinalBrightness : Summary is 1 -> 1
,09-15 12:03:00.534  3399  3567 I libsuspend: !@autosuspend_wakeup_count_enable done
09-15 12:03:00.534  3399  3567 D DisplayPowerController: Animating brightness: target=1, rate=2000 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
09-15 12:03:00.534  3399  3567 D DisplayPowerController: animateScreenStateChange[0]: target=3
09-15 12:03:00.534  3399  3567 D DisplayPowerController: [Dual Screen Compatible] state[0] :3
09-15 12:03:00.534  3399  3567 D DisplayPowerController: getFinalBrightness : Summary is 1 -> 1
,09-15 12:03:00.534  3399  3567 D DisplayPowerController: Animating brightness: target=1, rate=2000 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
09-15 12:03:00.534  3399  3567 D PowerManagerService: [s] DisplayPowerCallbacks : onStateChanged()
09-15 12:03:00.534  3399  3567 D PowerManagerService: mDisplayReady: true
,09-15 12:03:00.544  3399  3567 D PowerManagerService: [PWL] sb release: PowerManagerService.Display
,09-15 12:03:00.544  4734  4734 D RoamingTimeViewHolder: isDualClockSetting :: true isHomeTimeZoneExist :: false isEasyUxON :: false Utils.isRoaming(mContext) :: false
,09-15 12:03:00.544  4734  4734 D RoamingTimeViewHolder: getHomeCalendar : No homecity_timezone, set as default :  (libcore.util.ZoneInfo[id="Europe/Warsaw",mRawOffset=3600000,mEarliestRawOffset=3600000,mUseDst=true,mDstSavings=3600000,transitions=167])
,09-15 12:03:00.544  4734  4734 D RoamingTimeViewHolder: onTimeUpdate: isVisible:false timeZone:libcore.util.ZoneInfo[id="Europe/Warsaw",mRawOffset=3600000,mEarliestRawOffset=3600000,mUseDst=true,mDstSavings=3600000,transitions=167] text:czw., 15 wrz 12:03
09-15 12:03:00.544  4734  4734 I AODService.ClockTimer: startAlarm : TICK
,09-15 12:03:00.544  3399  4397 V AlarmManager: Add whitelist package alarm :PendingIntent{5e45028: PendingIntentRecord{c916656 com.samsung.android.app.aodservice broadcastIntent}}
,09-15 12:03:00.554  4734  4734 I AlpmModeManager: handleUnblankDisplay: state  = BLANK
,09-15 12:03:00.554  4734  4734 V AlpmModeManager: updateAlpmMode: setDoze [DISPLAY_STATE_DOZE_SUSPEND]
09-15 12:03:00.554  3399  4279 I PowerManagerService: [api] setDozeOverrideFromAod AlpmHlpmSysfs = -1, screenState = 4, Brightness = 0, wakefulness = false
,09-15 12:03:00.554  3399  4279 D PowerManagerService: setDozeModeBySysfs:  value is -1 , we ignore it. 
09-15 12:03:00.554  3399  3969 D PowerManagerService: [api] acquire WakeLock flags=0x80 tag=Window:AOD uid=1000 pid=3399
,09-15 12:03:00.554  4734  4734 D DefaultClockView: RootView invalidate()
,09-15 12:03:00.564  3166  3211 D Sensorhubs: readContextData: 1, 1, 56, 1, 1, 1, 1
09-15 12:03:00.564  3399  3469 D PowerManagerService: [api] acquire WakeLock flags=0x80 tag=Window:AOD uid=1000 pid=3399
,09-15 12:03:00.564  3399  3817 D SensorHubManager: onGetSensorHubDataLocked: library(7) = 1, 1, 56, 1, 1, 1, 1
,09-15 12:03:00.564  3399  3816 I CAE     : sendCmdToSensorHub(SensorHubCommManager.java:162) - -63, 14, 10, 3, 0,
09-15 12:03:00.564  3399  3816 D SensorHubManager: SendSensorHubData: send data = -63, 14, 10, 3, 0
09-15 12:03:00.564  3166  3213 D Sensorhubs: sendContextData: -63, 14, 10, 3, 0
,09-15 12:03:00.564  3399  3816 D CAE     : onGetSensorHubData(SensorHubParserProvider.java:92) - onGetSensorHubData Event [event buffer len :7], AP_SLEEP
,09-15 12:03:00.564  3399  3816 I CAE     : parse(SensorHubParserProvider.java:188) - buffer size = 7
09-15 12:03:00.564  3399  3816 I CAE     : parse(SensorHubParserProvider.java:199) - 1, 1, 56, 1, 1, 1, 1,
09-15 12:03:00.564  3399  3816 D CAE     : display(ContextProvider.java:375) - ================= DEVICE_PHYSICAL_CONTEXT_MONITOR =================
,09-15 12:03:00.564  3399  3816 I CAE     : display(ContextProvider.java:391) - AODReason=[1], AODStatus=[1], DataType=[1]
09-15 12:03:00.564  3399  3819 D SContextService: updateSContext() : event = Device Physical Context Monitor
,09-15 12:03:00.594  4734  4734 I AODService: onSContextChanged: AODScreenShown state is already true
,09-15 12:03:00.714  3399  3399 D PowerManagerService: [api] release WakeLock flags=0x80 tag=Window:AOD uid=1000 pid=3399 (0x0)
,09-15 12:03:00.714  3399  3399 I libsuspend: !@autosuspend_wakeup_count_disable
09-15 12:03:00.714  3399  3399 D PowerManagerService: mDisplayReady: false
09-15 12:03:00.714  3399  3399 I libsuspend: !@autosuspend_wakeup_count_disable done
09-15 12:03:00.714  3399  3567 D DisplayPowerController: animateScreenStateChange[0]: target=4
,09-15 12:03:00.714  3399  3399 D PowerManagerService: [PWL] sb acquire: PowerManagerService.Display
09-15 12:03:00.714  3006  3006 D SurfaceFlinger: Set power mode=3, type=0 flinger=0x7f88103c00
09-15 12:03:00.714  3399  3567 D DisplayPowerController: [Dual Screen Compatible] state[0] :4
09-15 12:03:00.714  3006  3006 I hwcomposer: int exynos_setPowerMode(hwc_composer_device_1*, int, int):: disp(0), mode(3)
09-15 12:03:00.714  3399  3567 D DisplayPowerController: getFinalBrightness : Summary is 1 -> 1
09-15 12:03:00.714  3399  3567 D DisplayPowerController: Animating brightness: target=1, rate=0 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
,09-15 12:03:00.714  3399  3575 D DisplayManagerService: !@display_state: DOZE -> DOZE_SUSPEND brightness: 1 -> 1
09-15 12:03:00.714  3399  3562 I DisplayManagerService: Display device changed state: "Wbudowany ekran", DOZE_SUSPEND
09-15 12:03:00.714  3399  3562 I DisplayManagerService: Display device changed state: "ActivityViewVirtualDisplay", DOZE_SUSPEND
,09-15 12:03:00.724  3399  3567 D DisplayPowerController: animateScreenStateChange[0]: target=4
,09-15 12:03:00.724  3399  3567 D DisplayPowerController: [Dual Screen Compatible] state[0] :4
09-15 12:03:00.724  3399  3567 I libsuspend: !@autosuspend_wakeup_count_enable
09-15 12:03:00.724  3399  3567 D DisplayPowerController: getFinalBrightness : Summary is 1 -> 1
,09-15 12:03:00.724  3399  3567 D DisplayPowerController: Animating brightness: target=1, rate=0 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
09-15 12:03:00.734  3399  3567 I libsuspend: !@autosuspend_wakeup_count_enable done
09-15 12:03:00.724  3399  3567 D DisplayPowerController: animateScreenStateChange[0]: target=4
09-15 12:03:00.724  3399  3567 D DisplayPowerController: [Dual Screen Compatible] state[0] :4
09-15 12:03:00.724  3399  3567 D DisplayPowerController: getFinalBrightness : Summary is 1 -> 1
09-15 12:03:00.724  3399  3567 D DisplayPowerController: Animating brightness: target=1, rate=0 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
,09-15 12:03:00.724  3399  3567 D PowerManagerService: [s] DisplayPowerCallbacks : onStateChanged()
09-15 12:03:00.724  3399  3567 D PowerManagerService: mDisplayReady: true
09-15 12:03:00.734  3399  3567 D PowerManagerService: [PWL] sb release: PowerManagerService.Display
,09-15 12:03:00.984  3399  4899 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
09-15 12:03:00.984  3399  4899 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4311, temperature: 279, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303413, invalid charger:0, maxChargingCurrent:0
09-15 12:03:00.984  3399  4899 D BatteryService: online:4, current avg:-27, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:-231
09-15 12:03:00.984  3399  4899 D BatteryService: stay LED for fully charged
09-15 12:03:00.984  3399  3399 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,09-15 12:03:00.984  3399  3399 I MotionRecognitionService: Plugged
09-15 12:03:00.994  3399  3399 D MotionRecognitionService:   cableConnection= 1
09-15 12:03:00.994  3399  3399 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
09-15 12:03:00.994  3399  3399 D MotionRecognitionService: skip setTransmitPower. 
09-15 12:03:00.994  3399  3858 D WifiController: ApOrStaEnabledState  msg.what= 155652
09-15 12:03:00.994  3944  3944 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
09-15 12:03:00.994  3944  3944 D KeyguardUpdateMonitor: handleBatteryUpdate
,09-15 12:03:00.994  3944  3944 D PowerUI : priorPlugType = 2 mPlugType =  2
,09-15 12:03:01.004  5083  5083 D CommonServiceConfiguration: getStringValueSetting
,09-15 12:03:01.014  5041  5041 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,09-15 12:03:01.014  5041  5413 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,09-15 12:03:01.014  5083  5083 D BatteryMonitor: new battery level: 100
,09-15 12:03:01.014  4734  4734 D BatteryController: saveBatteryData : level[100], status[5]
,09-15 12:03:01.044  3944  3944 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,09-15 12:03:01.044  3944  3944 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,09-15 12:03:01.474  9367  9433 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
09-15 12:03:01.474  9367  9433 I jxcore-log: 
,09-15 12:03:01.474  9367  9433 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
09-15 12:03:01.474  9367  9433 I jxcore-log: 
,09-15 12:03:01.474  9367  9433 D BluetoothAdapter: STATE_ON
,09-15 12:03:01.484  9367  9433 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-15 12:03:01.484  9367  9433 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-15 12:03:01.484  9367  9433 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-15 12:03:01.484  9367  9433 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-15 12:03:01.484  9367  9433 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-15 12:03:01.484  9367  9433 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-15 12:03:01.484  9367  9433 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-15 12:03:01.484  9367  9433 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-15 12:03:01.484  9367  9433 D BluetoothAdapter: STATE_ON
,09-15 12:03:01.494  9367  9433 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-15 12:03:01.494  9367  9433 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
09-15 12:03:01.494  9367  9433 I jxcore-log: 
09-15 12:03:01.494  9367  9433 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
09-15 12:03:01.494  9367  9433 I jxcore-log: 
,09-15 12:03:01.714  9367  9433 D executeNativeTests: Running unit tests
,09-15 12:03:01.724  9367  9433 D com.test.thalitest.ThaliTestRunner: Total number of executed tests: 1
09-15 12:03:01.724  9367  9433 D com.test.thalitest.ThaliTestRunner: Number of passed tests: 1
09-15 12:03:01.724  9367  9433 D com.test.thalitest.ThaliTestRunner: Number of failed tests:  0
09-15 12:03:01.724  9367  9433 D com.test.thalitest.ThaliTestRunner: Number of ignored tests: 0
09-15 12:03:01.724  9367  9433 D com.test.thalitest.ThaliTestRunner: Total duration: 1 ms
09-15 12:03:01.724  9367  9433 I jxcore-log: *Native tests were executed*
09-15 12:03:01.724  9367  9433 I jxcore-log: 
09-15 12:03:01.724  9367  9433 I jxcore-log: Total number of executed tests:  1
09-15 12:03:01.724  9367  9433 I jxcore-log: 
09-15 12:03:01.724  9367  9433 I jxcore-log: Number of passed tests:  1
09-15 12:03:01.724  9367  9433 I jxcore-log: 
09-15 12:03:01.724  9367  9433 I jxcore-log: Number of failed tests:  0
09-15 12:03:01.724  9367  9433 I jxcore-log: 
09-15 12:03:01.724  9367  9433 I jxcore-log: Number of ignored tests:  0
09-15 12:03:01.724  9367  9433 I jxcore-log: 
09-15 12:03:01.724  9367  9433 I jxcore-log: Total duration:  1
09-15 12:03:01.724  9367  9433 I jxcore-log: 
09-15 12:03:01.724  9367  9433 I jxcore-log: ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
09-15 12:03:01.724  9367  9433 I jxcore-log: 
09-15 12:03:01.724  9367  9433 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-15 12:03:01.724  9367  9433 I jxcore-log: 
,09-15 12:03:01.744  9367  9367 I chromium: [INFO:CONSOLE(68)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (68)
,09-15 12:03:02.124  3399  5991 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
,09-15 12:03:02.194  9458  9458 I FIPS_bssl: FIPS approved mode (1) | 9458 | app_process
,09-15 12:03:02.194  9458  9458 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
,09-15 12:03:02.194  9458  9458 D AndroidRuntime: CheckJNI is OFF
09-15 12:03:02.194  9458  9458 D AndroidRuntime: readGMSProperty: start
09-15 12:03:02.194  9458  9458 D AndroidRuntime: readGMSProperty: already setted!!
09-15 12:03:02.194  9458  9458 D AndroidRuntime: propertySet: couldn't set property (it is from app)
09-15 12:03:02.194  9458  9458 D AndroidRuntime: readGMSProperty: could not set the property(default)!!
09-15 12:03:02.194  9458  9458 D AndroidRuntime: readGMSProperty: end
09-15 12:03:02.194  9458  9458 D AndroidRuntime: addProductProperty: start
,09-15 12:03:02.214  9458  9458 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
,09-15 12:03:02.234  9458  9458 I Radio-JNI: register_android_hardware_Radio DONE
,09-15 12:03:02.244  9458  9458 E AffinityControl: AffinityControl: registerfunction enter
,09-15 12:03:02.244  9458  9458 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
,09-15 12:03:02.254  3399  4054 D PackageManager: START PACKAGE DELETE: observer{160596289}
09-15 12:03:02.254  3399  4054 D PackageManager: pkg{<packageName>}
09-15 12:03:02.254  3399  4054 D PackageManager: user{0}
09-15 12:03:02.254  3399  4054 D PackageManager: caller{2000}
09-15 12:03:02.254  3399  4054 D PackageManager: flags{2}
,09-15 12:03:02.254  3399  4054 D PersonaManagerService: isFromApprovedUnInstaller: uid, userId, appid : 2000 0 2000
09-15 12:03:02.254  3399  4054 D PersonaManagerService: isFromApprovedUnInstaller: isApproved : true
09-15 12:03:02.254  3399  4054 D PersonaManagerService: isFromApprovedUnInstaller: isApproved before exit: true
09-15 12:03:02.254  3399  4054 D PackageManager: deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag2
,09-15 12:03:02.254  3399  4054 D PackageManager: deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag2
09-15 12:03:02.254  3399  3583 D PackageManager: [MSG] DELETE_PACKAGE_AS_USER
09-15 12:03:02.254  3399  3583 D PackageManagerService: deletePackage- pkg:com.test.thalitest, edmuserId:0
09-15 12:03:02.254  3399  3583 D PackageManagerService: deletePackage- pkg:com.test.thalitest, edmuserId:-1
,09-15 12:03:02.254  3399  3583 D ApplicationPolicy: getApplicationUninstallationEnabled
09-15 12:03:02.264  3399  3583 D ApplicationPolicy: getApplicationUninstallationEnabled :  enabled true
09-15 12:03:02.264  3399  3583 I PackageManager: !@  calling am.removeDeletedPkgsFromLru from PMS
09-15 12:03:02.264  3399  3583 D ActivityManager: removeDeletedPkgsFromLruStats called in AMS...com.test.thalitest
,09-15 12:03:02.264  3399  3583 D PackageManager: !@killApplicatoin: 10171, uninstall pkg
09-15 12:03:02.264  3399  3583 I PackageManager: !@  calling am.removeDeletedPkgsFromLru from PMS
,09-15 12:03:02.264  3399  3537 I ActivityManager: Force stopping com.test.thalitest appid=10171 user=-1: uninstall pkg
09-15 12:03:02.264  3399  3583 D ActivityManager: removeDeletedPkgsFromLruStats called in AMS...com.test.thalitest
09-15 12:03:02.264  3399  3537 I ActivityManager: Killing 9367:com.test.thalitest/u0a171 (adj 0): stop com.test.thalitest cause uninstall pkg
,09-15 12:03:02.264  3399  3537 D ActivityManager: isAutoRunBlockedApp:: com.test.thalitest, Auto Run ON
,09-15 12:03:02.274  3399  3537 D ActivityManager: mDVFSHelper.acquire()
,09-15 12:03:02.294  3399  3583 D AASAinstall: there is not AASApackages.xml file
,09-15 12:03:02.294  9467  9467 E Zygote  : v2
09-15 12:03:02.294  9467  9467 I libpersona: KNOX_SDCARD checking this for 10171
09-15 12:03:02.294  9467  9467 I libpersona: KNOX_SDCARD not a persona
,09-15 12:03:02.294  9467  9467 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0013
,09-15 12:03:02.294  9467  9467 E Zygote  : accessInfo : 0
09-15 12:03:02.294  9467  9467 W SELinux : SELinux: seapp_context_lookup: seinfo=default, level=s0:c512,c768, pkgname=com.test.thalitest 
,09-15 12:03:02.294  3399  3537 I ActivityManager: Start proc 9467:com.test.thalitest/u0a171 for activity com.test.thalitest/.MainActivity
,09-15 12:03:02.304  3399  3537 W VirtualScreenManagerService: moveTaskBackToDisplayIfNeeded(): top activity or app is null
09-15 12:03:02.304  3399  3537 I ActivityManager:   Force finishing activity ActivityRecord{e01e71c u0 com.test.thalitest/.MainActivity t10}
,09-15 12:03:02.314  9467  9467 D TimaKeyStoreProvider: TimaSignature is unavailable
09-15 12:03:02.314  9467  9467 D ActivityThread: Added TimaKeyStore provider
,09-15 12:03:02.324  3006  3900 I SurfaceFlinger: id=21 Removed NainActivit (5/10)
,09-15 12:03:02.324  3006  4328 I SurfaceFlinger: id=21 Removed NainActivit (-2/10)
,09-15 12:03:02.324  3399  3537 D InputDispatcher: Focused application released
,09-15 12:03:02.324  3399  3537 D FocusedStackFrame: Set to : 0
09-15 12:03:02.324  3399  3537 W VirtualScreenManagerService: failed to move task null
,09-15 12:03:02.334  3006  3006 D libEGL  : eglTerminate EGLDisplay = 0x7fc83bb788
09-15 12:03:02.334  3006  3006 D libEGL  : eglTerminate EGLDisplay = 0x7fc83bb788
09-15 12:03:02.334  3006  3006 D libEGL  : eglTerminate EGLDisplay = 0x7fc83bb788
,09-15 12:03:02.404  3399  4899 D GraphicsStats: Buffer count: 6
,09-15 12:03:02.404  3399  4054 D ConnectivityService: ConnectivityService NetworkRequestInfo binderDied(NetworkRequest [ id=7, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ], android.os.BinderProxy@bb51779)
09-15 12:03:02.404  3399  3864 D ConnectivityService: releasing NetworkRequest NetworkRequest [ id=7, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-15 12:03:02.404  3399  3864 D ConnectivityService: sending notification RELEASED for NetworkRequest [ id=7, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,09-15 12:03:02.414  3399  3864 E ConnectivityService: RemoteException caught trying to send a callback msg for NetworkRequest [ id=7, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,09-15 12:03:02.574  3399  3583 W System.err: remove failed: ENOENT (No such file or directory) : /data/system/packages.xml.bak
,09-15 12:03:02.644  3399  3583 W System.err: remove failed: ENOENT (No such file or directory) : /data/system/users/0/package-restrictions.xml.bak
,09-15 12:03:02.644  3399  3562 W System.err: android.content.pm.PackageManager$NameNotFoundException: com.test.thalitest
09-15 12:03:02.644  3399  3562 D SecWifiDisplayUtil: Metadata value : SecSettings2
09-15 12:03:02.644  3399  3562 W System.err: 	at android.app.ApplicationPackageManager.getApplicationInfo(ApplicationPackageManager.java:366)
,09-15 12:03:02.644  3399  3562 W System.err: 	at com.android.internal.policy.PhoneWindow.installDecor(PhoneWindow.java:4813)
09-15 12:03:02.644  3399  3562 W System.err: 	at com.android.internal.policy.PhoneWindow.getDecorView(PhoneWindow.java:2263)
09-15 12:03:02.644  3399  3562 W System.err: 	at com.android.server.policy.PhoneWindowManager.addStartingWindow(PhoneWindowManager.java:4338)
09-15 12:03:02.644  3399  3562 W System.err: 	at com.android.server.wm.WindowManagerService$H.handleMessage(WindowManagerService.java:13481)
,09-15 12:03:02.644  3399  3562 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-15 12:03:02.644  3399  3562 W System.err: 	at android.os.Looper.loop(Looper.java:158)
09-15 12:03:02.644  3399  3562 W System.err: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,09-15 12:03:02.644  3399  3562 W System.err: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
09-15 12:03:02.644  3399  3562 D ViewRootImpl: #1 mView = com.android.internal.policy.PhoneWindow$DecorView{9d80cbe V.E...... R.....ID 0,0-0,0}
09-15 12:03:02.644  3164  3164 W keystore: ENTER clear_uid from uid 1000 for 10171
09-15 12:03:02.654  3399  3583 I art     : Starting a blocking GC Explicit
,09-15 12:03:02.654  3399  3562 W WindowManager: Failed looking up window
09-15 12:03:02.654  3399  3562 W WindowManager: java.lang.IllegalArgumentException: Requested window android.view.ViewRootImpl$W@dd3811f does not exist
09-15 12:03:02.654  3399  3562 W WindowManager: 	at com.android.server.wm.WindowManagerService.windowForClientLocked(WindowManagerService.java:14804)
09-15 12:03:02.654  3399  3562 W WindowManager: 	at com.android.server.wm.WindowManagerService.pokeDrawLock(WindowManagerService.java:5176)
09-15 12:03:02.654  3399  3562 W WindowManager: 	at com.android.server.wm.Session.pokeDrawLock(Session.java:505)
09-15 12:03:02.654  3399  3562 W WindowManager: 	at android.view.ViewRootImpl.pokeDrawLockIfNeeded(ViewRootImpl.java:1203)
09-15 12:03:02.654  3399  3562 W WindowManager: 	at android.view.ViewRootImpl.scheduleTraversals(ViewRootImpl.java:1415)
09-15 12:03:02.654  3399  3562 W WindowManager: 	at android.view.ViewRootImpl.requestLayout(ViewRootImpl.java:1222)
09-15 12:03:02.654  3399  3562 W WindowManager: 	at android.view.ViewRootImpl.setView(ViewRootImpl.java:800)
09-15 12:03:02.654  3399  3562 W WindowManager: 	at android.view.WindowManagerGlobal.addView(WindowManagerGlobal.java:337)
09-15 12:03:02.654  3399  3562 W WindowManager: 	at android.view.WindowManagerImpl.addView(WindowManagerImpl.java:91)
09-15 12:03:02.654  3399  3562 W WindowManager: 	at com.android.server.policy.PhoneWindowManager.addStartingWindow(PhoneWindowManager.java:4378)
09-15 12:03:02.654  3399  3562 W WindowManager: 	at com.android.server.wm.WindowManagerService$H.handleMessage(WindowManagerService.java:13481)
09-15 12:03:02.654  3399  3562 W WindowManager: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-15 12:03:02.654  3399  3562 W WindowManager: 	at android.os.Looper.loop(Looper.java:158)
09-15 12:03:02.654  3399  3562 W WindowManager: 	at android.os.HandlerThread.run(HandlerThread.java:61)
09-15 12:03:02.654  3399  3562 W WindowManager: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
,09-15 12:03:02.664  3399  3562 W WindowManager: Attempted to add application window with unknown token Token{6e21f25 ActivityRecord{e01e71c u0 com.test.thalitest/.MainActivity t10 f}}.  Aborting.
,09-15 12:03:02.664  3399  3562 D ViewRootImpl: #3 mView = null
,09-15 12:03:02.664  3399  3562 W WindowManager: Token{6e21f25 ActivityRecord{e01e71c u0 com.test.thalitest/.MainActivity t10 f}} already running, starting window not displayed. Unable to add window -- token Token{6e21f25 ActivityRecord{e01e71c u0 com.test.thalitest/.MainActivity t10 f}} is not valid; is your activity running?
09-15 12:03:02.664  3399  3562 W WindowManager: view not successfully added to wm, removing view
,09-15 12:03:02.664  3399  3562 W WindowManager: Exception when adding starting window
09-15 12:03:02.664  3399  3562 W WindowManager: java.lang.IllegalArgumentException: View=com.android.internal.policy.PhoneWindow$DecorView{9d80cbe V.E...... R.....ID 0,0-0,0} not attached to window manager
09-15 12:03:02.664  3399  3562 W WindowManager: 	at android.view.WindowManagerGlobal.findViewLocked(WindowManagerGlobal.java:451)
09-15 12:03:02.664  3399  3562 W WindowManager: 	at android.view.WindowManagerGlobal.removeView(WindowManagerGlobal.java:377)
09-15 12:03:02.664  3399  3562 W WindowManager: 	at android.view.WindowManagerImpl.removeViewImmediate(WindowManagerImpl.java:122)
09-15 12:03:02.664  3399  3562 W WindowManager: 	at com.android.server.policy.PhoneWindowManager.addStartingWindow(PhoneWindowManager.java:4395)
09-15 12:03:02.664  3399  3562 W WindowManager: 	at com.android.server.wm.WindowManagerService$H.handleMessage(WindowManagerService.java:13481)
09-15 12:03:02.664  3399  3562 W WindowManager: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-15 12:03:02.664  3399  3562 W WindowManager: 	at android.os.Looper.loop(Looper.java:158)
09-15 12:03:02.664  3399  3562 W WindowManager: 	at android.os.HandlerThread.run(HandlerThread.java:61)
09-15 12:03:02.664  3399  3562 W WindowManager: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
,09-15 12:03:02.664  3399  3814 V AlarmManager: Expired Alarm result :4
,09-15 12:03:02.674  3399  3399 D GameManagerService: NotifyRunnable. pkg: com.sec.android.app.launcher, type: 4, isMinimized: false, isTunableApp: false
,09-15 12:03:02.674  3399  3537 V MARsPolicyManager: updatePackagesScore PackageInfo name -- com.sec.android.app.launcher
,09-15 12:03:02.684  4280  4280 D Launcher: onRestart, Launcher: 27478326
,09-15 12:03:02.684  3399  4442 I ActivityManager: Killing 7680:com.samsung.android.coreapps/5011 (adj 15): DHA:empty #33
,09-15 12:03:02.694  4280  4280 W ResourcesManager: getTopLevelResources: /system/app/ClockPackage_M/ClockPackage_M.apk / 1.0 running in com.sec.android.app.launcher rsrc of package com.sec.android.app.clockpackage
,09-15 12:03:02.694  4280  4280 D ResourcesManager: For user 0 new overlays fetched Null
,09-15 12:03:02.704  3944  3944 D KeyguardViewMediator: received DELAYED_KEYGUARD_ACTION with seq = 2, mDelayedShowingSequence = 2
,09-15 12:03:02.714  4280  4280 D ApplicationPackageManager: we has com.sec.android.app.clockpackage class. reuse it 
,09-15 12:03:02.724  4280  4280 W ResourcesManager: getTopLevelResources: /system/app/ClockPackage_M/ClockPackage_M.apk / 1.0 running in com.sec.android.app.launcher rsrc of package com.sec.android.app.clockpackage
,09-15 12:03:02.734  3944  3944 D FactoryTest: checkAutomationTestOption() : option=0
,09-15 12:03:02.734  3944  3944 D FactoryTest: checkAutomationTestOption() : mode_screenlock=0
09-15 12:03:02.734  3944  3944 D KeyguardViewMediator: doKeyguard: showing the lock screen
09-15 12:03:02.734  3944  3944 D KeyguardViewMediator: showLocked
,09-15 12:03:02.734  9467  9467 W ResourcesManager: getTopLevelResources: /data/app/com.test.thalitest-1/base.apk / 1.0 running in com.test.thalitest rsrc of package com.test.thalitest
,09-15 12:03:02.734  3399  3996 D ActivityManager: isAutoRunBlockedApp:: com.samsung.android.coreapps, Auto Run ON
,09-15 12:03:02.744  3944  3944 D KeyguardViewMediator: handleShow
,09-15 12:03:02.744  3944  3944 E KeyguardViewMediator: setShowingLocked mShowing = true
,09-15 12:03:02.744  3006  3015 I SurfaceFlinger: Modify Choreographer's phase offset to 6666666
09-15 12:03:02.744  3944  3944 D StatusBar-Window: fnf=false sanc=true, kni=false, sbf=false
09-15 12:03:02.744  3944  3944 D CoverUI : applyFocusableFlag() : Remove SAMSUNG_FLAG_SVIEW_COVER
09-15 12:03:02.744  3944  3944 D StatusBarWindowManager: forceCollapsed : false isKeyguardShowingAndNotOccluded() : true panelVisible : false keyguardFadingAway : false bouncerShowing : false headsUpShowing : false
09-15 12:03:02.744  3944  3944 D CoverUI : applyHeight h = -1, oc = true, fa = false, ac = false, sc = false
,09-15 12:03:02.754  3944  3944 D KeyguardEffectViewController: setKeyguardShowing = true
09-15 12:03:02.754  3944  3944 D KeyguardEffectViewController: mShowing=true, mOccluded=false, mKeyguardFadingAway=false, match_parent=false
09-15 12:03:02.754  3944  3944 D StatusBarKeyguardViewManager: showBouncerOrKeyguard
,09-15 12:03:02.754  3399  3470 I InjectionManagerService -AppFeature: getCoreFeaturePkgList :[]
,09-15 12:03:02.754  9467  9467 I InjectionManager: Inside getClassLibPath + mLibMap{0=, 1=}
,09-15 12:03:02.754  3006  4108 I SurfaceFlinger: Modify SurfaceFlinger's phase offset to 6666666
,09-15 12:03:02.754  3399  5991 D GameManagerService: identifyGamePackage. com.sec.android.app.launcher
09-15 12:03:02.754  3944  3944 V KeyguardUpdateMonitor: *** register callback for com.android.keyguard.KeyguardHostView$1@989f31e
09-15 12:03:02.754  3944  3944 V KeyguardUpdateMonitor: *** unregister callback for null
,09-15 12:03:02.764  3944  3944 D KeyguardSecurityPolicyUtils: MDM is not enabled...
09-15 12:03:02.764  3944  3944 V KeyguardUpdateMonitor: *** register callback for com.android.keyguard.KeyguardSecurityContainer$1@f03d7ff
09-15 12:03:02.764  3944  3944 V KeyguardUpdateMonitor: *** unregister callback for null
,09-15 12:03:02.764  9467  9467 W ContextImpl: Unable to create files subdir /data/user/0/com.test.thalitest/cache
09-15 12:03:02.764  9467  9467 V ActivityThread: Unable to initialize "java.io.tmpdir" property due to missing cache directory
09-15 12:03:02.774  9467  9467 W ContextImpl: Unable to create files subdir /data/user/0/com.test.thalitest/code_cache
09-15 12:03:02.774  9467  9467 E ActivityThread: Unable to setupGraphicsSupport due to missing code-cache directory
09-15 12:03:02.774  3399  5991 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
,09-15 12:03:02.774  3399  5991 D GameManagerService: identifyGamePackage. com.sec.android.app.launcher
,09-15 12:03:02.774  9467  9467 I InjectionManager: Inside getClassLibPath caller 
09-15 12:03:02.774  4280  4280 W ResourcesManager: getTopLevelResources: /system/app/SPlanner_M/SPlanner_M.apk / 1.0 running in com.sec.android.app.launcher rsrc of package com.android.calendar
,09-15 12:03:02.774  4280  4280 D ResourcesManager: For user 0 new overlays fetched Null
,09-15 12:03:02.784  3944  3944 D KeyguardSecurityModel: getSecurityMode( getActivePasswordQuality = 0 , currentuser = 0
,09-15 12:03:02.784  3944  3944 V KeyguardSecurityView: showPrimarySecurityScreen(turningOff=false)
09-15 12:03:02.784  3399  5991 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
,09-15 12:03:02.784  3944  3944 D KeyguardSecurityView: showSecurityScreen(None)
09-15 12:03:02.784  3944  3944 D StatusBar-Window: fnf=false sanc=true, kni=false, sbf=false
09-15 12:03:02.784  3944  3944 D CoverUI : applyFocusableFlag() : Remove SAMSUNG_FLAG_SVIEW_COVER
,09-15 12:03:02.784  3944  3944 D StatusBarWindowManager: forceCollapsed : false isKeyguardShowingAndNotOccluded() : true panelVisible : false keyguardFadingAway : false bouncerShowing : false headsUpShowing : false
09-15 12:03:02.784  3944  3944 D CoverUI : applyHeight h = -1, oc = true, fa = false, ac = false, sc = false
09-15 12:03:02.784  4280  4280 D ApplicationPackageManager: we has com.android.calendar class. reuse it 
,09-15 12:03:02.784  4280  4280 W ResourcesManager: getTopLevelResources: /system/app/SPlanner_M/SPlanner_M.apk / 1.0 running in com.sec.android.app.launcher rsrc of package com.android.calendar
09-15 12:03:02.784  3399  5991 D GameManagerService: identifyGamePackage. com.sec.android.app.launcher
,09-15 12:03:02.784  3399  5991 D GameManagerService: identifyGamePackage. com.sec.android.app.launcher
,09-15 12:03:02.784  4280  4280 D Minikin : FontFamily bestFont == NULL, so return vacant FakedFont
,09-15 12:03:02.784  4280  4280 D Minikin : FontFamily bestFont == NULL, so return vacant FakedFont
09-15 12:03:02.784  4280  4280 D Minikin : FontFamily bestFont == NULL, so return vacant FakedFont
,09-15 12:03:02.794  9467  9467 D AndroidRuntime: Shutting down VM
,09-15 12:03:02.794  9467  9467 E AndroidRuntime: FATAL EXCEPTION: main
09-15 12:03:02.794  9467  9467 E AndroidRuntime: Process: com.test.thalitest, PID: 9467
09-15 12:03:02.794  9467  9467 E AndroidRuntime: java.lang.RuntimeException: Unable to instantiate application android.app.Application: java.lang.IllegalStateException: Unable to get package info for com.test.thalitest; is package not installed?
09-15 12:03:02.794  9467  9467 E AndroidRuntime: 	at android.app.LoadedApk.makeApplication(LoadedApk.java:676)
09-15 12:03:02.794  9467  9467 E AndroidRuntime: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:6294)
09-15 12:03:02.794  9467  9467 E AndroidRuntime: 	at android.app.ActivityThread.access$1800(ActivityThread.java:222)
09-15 12:03:02.794  9467  9467 E AndroidRuntime: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1861)
09-15 12:03:02.794  9467  9467 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-15 12:03:02.794  9467  9467 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:158)
09-15 12:03:02.794  9467  9467 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:7229)
09-15 12:03:02.794  9467  9467 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
09-15 12:03:02.794  9467  9467 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1230)
09-15 12:03:02.794  9467  9467 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1120)
09-15 12:03:02.794  9467  9467 E AndroidRuntime: Caused by: java.lang.IllegalStateException: Unable to get package info for com.test.thalitest; is package not installed?
09-15 12:03:02.794  9467  9467 E AndroidRuntime: 	at android.app.LoadedApk.initializeJavaContextClassLoader(LoadedApk.java:485)
09-15 12:03:02.794  9467  9467 E AndroidRuntime: 	at android.app.LoadedApk.makeApplication(LoadedApk.java:661)
09-15 12:03:02.794  9467  9467 E AndroidRuntime: 	... 9 more
,09-15 12:03:02.794  3944  3944 D KeyguardSecurityModel: getSecurityMode( getActivePasswordQuality = 0 , currentuser = 0
,09-15 12:03:02.794  3944  3944 D PhoneStatusBar: showKeyguard
09-15 12:03:02.794  3944  3944 D PhoneStatusBar: setBarState: state - 1
09-15 12:03:02.794  3944  3944 D StatusBar-Window: fnf=false sanc=true, kni=false, sbf=false
09-15 12:03:02.794  3944  3944 D CoverUI : applyFocusableFlag() : Remove SAMSUNG_FLAG_SVIEW_COVER
09-15 12:03:02.794  3944  3944 D StatusBarWindowManager: forceCollapsed : false isKeyguardShowingAndNotOccluded() : true panelVisible : false keyguardFadingAway : false bouncerShowing : false headsUpShowing : false
09-15 12:03:02.794  3944  3944 D CoverUI : applyHeight h = -1, oc = true, fa = false, ac = false, sc = false
,09-15 12:03:02.794  3944  3944 I PhoneStatusBar: updateKeyguardState 0 to 1
,09-15 12:03:02.794  4280  4280 D Launcher: onStart, Launcher: 27478326
,09-15 12:03:02.794  4280  4280 D Launcher.HomeView: onStart
09-15 12:03:02.794  4280  4280 D Launcher: onResume, Launcher: 27478326
,09-15 12:03:02.794  3944  3944 D PanelView: updateQsState
,09-15 12:03:02.794  3399  4279 D SettingsProvider: isChangeAllowed() : name = kids_home_mode
09-15 12:03:02.794  3399  4279 D SecContentProvider: query(), uri = 17 selection = isSettingsChangesAllowed
,09-15 12:03:02.794  3399  4279 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
09-15 12:03:02.794  3944  3944 D KeyguardSwipeHelper: reset()
,09-15 12:03:02.794  3399  4279 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
09-15 12:03:02.794  3944  3944 D KeyguardUnlockEventHandler: reset()
,09-15 12:03:02.794  3399  4279 D SettingsProvider: selectionArgs: false
09-15 12:03:02.794  3944  3944 D KeyguardSwipeHelper: resetChildViewVI()
09-15 12:03:02.794  3399  4279 D SettingsProvider: selectionArgs: 10065
,09-15 12:03:02.794  3944  3944 D StatusBar: LSSN:1
09-15 12:03:02.794  3399  4279 D SettingsProvider: ret = -1
,09-15 12:03:02.794  4280  4280 D Launcher.HomeView: onResume
09-15 12:03:02.804  3944  3944 E LSO     : LSO Service is not yet ready!!!
09-15 12:03:02.804  4280  4280 D capture : ---------checkFileExist land
09-15 12:03:02.804  4280  4280 D capture : currentOrientation: 1 mMainHomeScreenshot: false mMainHomeScreenshotLand: true
09-15 12:03:02.804  3944  3944 D PanelView: setKeyguardBottomAreaVisibility() prevState=0, newState - 1 goingToShade - false
,09-15 12:03:02.814  3399  3537 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{ee01358 u0 com.android.launcher.action.HOME_MODE_CHANGE qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{d423460 9282:com.sec.android.app.clockpackage/u0a88}
,09-15 12:03:02.814  9467  9467 I Process : Sending signal. PID: 9467 SIG: 9
,09-15 12:03:02.814  4280  4280 D MenuAppsGridFragment: onResume
09-15 12:03:02.814  4280  4280 D MenuAppsGridFragment: changeState: (new)NORMAL(old)NORMAL(force)false
09-15 12:03:02.814  4280  4280 D Launcher.MenuAppsGrid: updateGridSize:GRID_4x4 cellWidth:348  cellHeight:432
09-15 12:03:02.814  3399  3583 I art     : Explicit concurrent mark sweep GC freed 145486(7MB) AllocSpace objects, 20(644KB) LOS objects, 31% free, 34MB/50MB, paused 1.974ms total 163.444ms
,09-15 12:03:02.834  3399  3583 W PackageManager: Couldn't remove dex file for package:  at location /data/app/com.test.thalitest-1/base.apk, retcode=-1
09-15 12:03:02.834  3399  3583 D AASAuninstall: userId = 0, info.removedAppID = 10171, info.uid = 10171, packageName = com.test.thalitest
,09-15 12:03:02.834  3399  3583 D AASAinstall: there is not AASApackages.xml file
09-15 12:03:02.834  3399  3583 D PackageManager: result of delete: 1{160596289}
,09-15 12:03:02.834  9458  9458 I art     : System.exit called, status: 0
09-15 12:03:02.834  9458  9458 I AndroidRuntime: VM exiting with result code 0.
09-15 12:03:02.834  3399  3583 D PackageManager: [MSG] START_CLEANING_PACKAGE packageName{com.test.thalitest}
09-15 12:03:02.834  3399  3583 D PackageManager: userId{-1}
09-15 12:03:02.834  3399  3583 D PackageManager: andCode{true}
,09-15 12:03:02.834  3399  4054 I ActivityManager: Process com.test.thalitest (pid 9467)(adj 9) has died(226,1714)
,09-15 12:03:02.834  3399  4054 D ActivityManager: isAutoRunBlockedApp:: com.test.thalitest, Auto Run ON
,09-15 12:03:02.844  3399  4054 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.android.server.am.ActivityManagerService.updateOomAdjLocked:26743 com.android.server.am.ActivityManagerService.appDiedLocked:7562 com.android.server.am.ActivityManagerService$AppDeathRecipient.binderDied:1916 android.os.BinderProxy.sendDeathNotice:558 
,09-15 12:03:02.844  3399  4410 D ActivityManager: post active user change for 0 fullscreen true isFloatingActivity() false isHomeActivity() true
09-15 12:03:02.844  3399  4410 I WallpaperManagerService: switchPersonaWallpaper is called for personaId-0
09-15 12:03:02.844  3399  4410 D KnoxTimeoutHandler: post home show event for user 0
09-15 12:03:02.844  3399  4410 D KnoxTimeoutHandler: postActiveUserChange [MsgParam] userId: 0 fullscreen is true showWhenlocked is false
09-15 12:03:02.844  3399  3399 D WallpaperManagerService:  force update = false; persona id = 0; current user =0; current persona = 0
09-15 12:03:02.844  3399  3399 D KnoxTimeoutHandler: handleHomeShow for 0 and current 0
09-15 12:03:02.844  3399  3399 D KnoxTimeoutHandler: handleActiveUserChange [MsgParam] userId: 0 fullscreen is true showWhenlocked is false
09-15 12:03:02.844  4280  4280 D Launcher: onPause, Launcher: 27478326
09-15 12:03:02.844  4280  4280 D Launcher.HomeView: onPause
09-15 12:03:02.844  4280  4280 D Launcher.Workspace: exitWidgetResizeMode. isClearResizeFrame is false
,09-15 12:03:02.854  3944  3944 D PhoneStatusBar/KeyguardBottomAreaView: updateCameraVisibility isCameraDisabledByDpm=false
,09-15 12:03:02.854  3399  3399 I KnoxTimeoutHandler: Shared devices show user statefalse
,09-15 12:03:02.854  3944  3944 V KeyguardBottomAreaShortcutView: updateLeftPreview
09-15 12:03:02.854  3944  3944 V KeyguardBottomAreaShortcutView: updateRightPreview
09-15 12:03:02.854  3944  3944 D KeyguardCircleAffordanceView: setPreviewView: mRight=false,preview=android.widget.RelativeLayout{c586631 I.E...... ......ID 0,0-1440,2560}
,09-15 12:03:02.854  3944  4101 V KeyguardBottomAreaShortcutView: updateLeftPreview - mLeftAffordanceView
,09-15 12:03:02.854  3399  3583 I ActivityManager: Force stopping com.test.thalitest appid=10171 user=0: pkg removed
,09-15 12:03:02.864  3944  4101 V PreviewInflater: switching default dialer action
,09-15 12:03:02.884  3944  3944 D KeyguardCircleAffordanceView: setPreviewView: mRight=true,preview=android.widget.AbsoluteLayout{d848425 I.E...... ......ID 0,0-1440,2560}
,09-15 12:03:02.884  3006  3006 I SurfaceFlinger: id=24 createSurf (1440x2560),1 flag=4, MauncherAct
,09-15 12:03:02.894  3399  3399 W ResourcesManager: getTopLevelResources: /system/priv-app/GmsCore/GmsCore.apk / 1.0 running in null rsrc of package com.google.android.gms
,09-15 12:03:02.904  3399  3399 D ResourcesManager: For user 0 new overlays fetched Null
,09-15 12:03:02.904  3399  3399 W ResourcesManager: getTopLevelResources: /system/priv-app/GmsCore/GmsCore.apk / 1.0 running in null rsrc of package com.google.android.gms
,09-15 12:03:02.904  3399  3399 W ResourcesManager: getTopLevelResources: /system/priv-app/SNS_v2/SNS_v2.apk / 1.0 running in null rsrc of package com.sec.android.app.sns3
,09-15 12:03:02.914  3944  3944 D PanelView: updateQsState
09-15 12:03:02.914  3399  3399 D ResourcesManager: For user 0 new overlays fetched Null
09-15 12:03:02.914  3399  3399 W ResourcesManager: getTopLevelResources: /system/priv-app/SNS_v2/SNS_v2.apk / 1.0 running in null rsrc of package com.sec.android.app.sns3
09-15 12:03:02.914  3399  3399 W ResourcesManager: getTopLevelResources: /system/priv-app/SNS_v2/SNS_v2.apk / 1.0 running in null rsrc of package com.sec.android.app.sns3
09-15 12:03:02.914  3399  3399 W ResourcesManager: getTopLevelResources: /system/priv-app/SNS_v2/SNS_v2.apk / 1.0 running in null rsrc of package com.sec.android.app.sns3
09-15 12:03:02.914  3399  3399 W ResourcesManager: getTopLevelResources: /system/priv-app/SNS_v2/SNS_v2.apk / 1.0 running in null rsrc of package com.sec.android.app.sns3
09-15 12:03:02.914  3399  3399 W ResourcesManager: getTopLevelResources: /system/priv-app/SNS_v2/SNS_v2.apk / 1.0 running in null rsrc of package com.sec.android.app.sns3
09-15 12:03:02.914  3399  3399 W ResourcesManager: getTopLevelResources: /system/priv-app/SamsungAccount_Hero/SamsungAccount_Hero.apk / 1.0 running in null rsrc of package com.osp.app.signin
,09-15 12:03:02.924  3399  3399 D ResourcesManager: For user 0 new overlays fetched Null
09-15 12:03:02.924  3399  3399 W ResourcesManager: getTopLevelResources: /system/priv-app/SamsungAccount_Hero/SamsungAccount_Hero.apk / 1.0 running in null rsrc of package com.osp.app.signin
09-15 12:03:02.924  3399  3399 W ResourcesManager: getTopLevelResources: /system/priv-app/SecEmail_M/SecEmail_M.apk / 1.0 running in null rsrc of package com.samsung.android.email.provider
,09-15 12:03:02.924  3944  3944 D NotificationStackScrollLayout:  scroll range should be extended : 884
,09-15 12:03:02.924  3399  3399 D ResourcesManager: For user 0 new overlays fetched Null
,09-15 12:03:02.924  3399  3399 W ResourcesManager: getTopLevelResources: /system/priv-app/SecEmail_M/SecEmail_M.apk / 1.0 running in null rsrc of package com.samsung.android.email.provider
,09-15 12:03:02.924  3399  3399 W ResourcesManager: getTopLevelResources: /system/priv-app/SecEmail_M/SecEmail_M.apk / 1.0 running in null rsrc of package com.samsung.android.email.provider
,09-15 12:03:02.924  3399  3399 W ResourcesManager: getTopLevelResources: /system/priv-app/SecEmail_M/SecEmail_M.apk / 1.0 running in null rsrc of package com.samsung.android.email.provider
09-15 12:03:02.924  3399  3399 W ResourcesManager: getTopLevelResources: /system/priv-app/SecEmail_M/SecEmail_M.apk / 1.0 running in null rsrc of package com.samsung.android.email.provider
,09-15 12:03:02.934  3399  3399 W ResourcesManager: getTopLevelResources: /system/priv-app/SecEmail_M/SecEmail_M.apk / 1.0 running in null rsrc of package com.samsung.android.email.provider
09-15 12:03:02.934  3399  3399 W ResourcesManager: getTopLevelResources: /system/app/CoreApps/CoreApps.apk / 1.0 running in null rsrc of package com.samsung.android.coreapps
,09-15 12:03:02.934  3399  3399 D ResourcesManager: For user 0 new overlays fetched Null
,09-15 12:03:02.934  3399  3399 W ResourcesManager: getTopLevelResources: /system/app/CoreApps/CoreApps.apk / 1.0 running in null rsrc of package com.samsung.android.coreapps
,09-15 12:03:02.934  3399  3399 W ResourcesManager: getTopLevelResources: /system/app/Gmail2/Gmail2.apk / 1.0 running in null rsrc of package com.google.android.gm
,09-15 12:03:02.934  3399  3399 D ResourcesManager: For user 0 new overlays fetched Null
,09-15 12:03:02.934  3399  3399 W ResourcesManager: getTopLevelResources: /system/app/Gmail2/Gmail2.apk / 1.0 running in null rsrc of package com.google.android.gm
09-15 12:03:02.934  3399  3399 W ResourcesManager: getTopLevelResources: /system/app/Gmail2/Gmail2.apk / 1.0 running in null rsrc of package com.google.android.gm
09-15 12:03:02.934  3399  3399 W ResourcesManager: getTopLevelResources: /system/app/Gmail2/Gmail2.apk / 1.0 running in null rsrc of package com.google.android.gm
09-15 12:03:02.934  3399  3399 W ResourcesManager: getTopLevelResources: /system/app/OneDrive_Samsung_v2/OneDrive_Samsung_v2.apk / 1.0 running in null rsrc of package com.microsoft.skydrive
,09-15 12:03:02.934  3399  3399 D ResourcesManager: For user 0 new overlays fetched Null
09-15 12:03:02.934  3399  3399 W ResourcesManager: getTopLevelResources: /system/app/OneDrive_Samsung_v2/OneDrive_Samsung_v2.apk / 1.0 running in null rsrc of package com.microsoft.skydrive
09-15 12:03:02.934  3399  3399 W ResourcesManager: getTopLevelResources: /system/app/OneNote/OneNote.apk / 1.0 running in null rsrc of package com.microsoft.office.onenote
,09-15 12:03:02.944  3399  3399 D ResourcesManager: For user 0 new overlays fetched Null
09-15 12:03:02.944  3399  3399 W ResourcesManager: getTopLevelResources: /system/app/OneNote/OneNote.apk / 1.0 running in null rsrc of package com.microsoft.office.onenote
,09-15 12:03:02.944  4280  4632 D mali_winsys: EGLint new_window_surface(egl_winsys_display*, void*, EGLSurface, EGLConfig, egl_winsys_surface**, egl_color_buffer_format*, EGLBoolean) returns 0x3000,  [1440x2560]-format:1
09-15 12:03:02.944  3399  3399 W ResourcesManager: getTopLevelResources: /system/app/SBrowser_4_LATEST/SBrowser_4_LATEST.apk / 1.0 running in null rsrc of package com.sec.android.app.sbrowser
,09-15 12:03:02.944  3399  3399 D ResourcesManager: For user 0 new overlays fetched Null
,09-15 12:03:02.944  3399  3399 W ResourcesManager: getTopLevelResources: /system/app/SBrowser_4_LATEST/SBrowser_4_LATEST.apk / 1.0 running in null rsrc of package com.sec.android.app.sbrowser
09-15 12:03:02.944  3399  3527 W ResourcesManager: getTopLevelResources: /system/priv-app/Velvet/Velvet.apk / 1.0 running in null rsrc of package com.google.android.googlequicksearchbox
,09-15 12:03:02.944  3399  3399 W ResourcesManager: getTopLevelResources: /system/priv-app/GmsCore/GmsCore.apk / 1.0 running in null rsrc of package com.google.android.gms
,09-15 12:03:02.944  3399  3399 W ResourcesManager: getTopLevelResources: /system/priv-app/GmsCore/GmsCore.apk / 1.0 running in null rsrc of package com.google.android.gms
09-15 12:03:02.944  8813  9484 W System.err: remove failed: ENOENT (No such file or directory) : /storage/emulated/0/Android/data/com.test.thalitest
09-15 12:03:02.944  3399  3399 W ResourcesManager: getTopLevelResources: /system/priv-app/GmsCore/GmsCore.apk / 1.0 running in null rsrc of package com.google.android.gms
,09-15 12:03:02.944  3399  3399 W ResourcesManager: getTopLevelResources: /system/priv-app/GmsCore/GmsCore.apk / 1.0 running in null rsrc of package com.google.android.gms
09-15 12:03:02.944  3399  3399 W ResourcesManager: getTopLevelResources: /system/priv-app/GmsCore/GmsCore.apk / 1.0 running in null rsrc of package com.google.android.gms
09-15 12:03:02.944  3399  3399 W ResourcesManager: getTopLevelResources: /system/priv-app/GmsCore/GmsCore.apk / 1.0 running in null rsrc of package com.google.android.gms
09-15 12:03:02.944  3399  3399 W ResourcesManager: getTopLevelResources: /system/priv-app/GmsCore/GmsCore.apk / 1.0 running in null rsrc of package com.google.android.gms
09-15 12:03:02.944  3399  3399 W ResourcesManager: getTopLevelResources: /system/priv-app/GmsCore/GmsCore.apk / 1.0 running in null rsrc of package com.google.android.gms
09-15 12:03:02.944  3399  3399 W ResourcesManager: getTopLevelResources: /system/priv-app/GmsCore/GmsCore.apk / 1.0 running in null rsrc of package com.google.android.gms
,09-15 12:03:02.944  3399  3399 W ResourcesManager: getTopLevelResources: /system/priv-app/GmsCore/GmsCore.apk / 1.0 running in null rsrc of package com.google.android.gms
09-15 12:03:02.944  3399  3399 W ResourcesManager: getTopLevelResources: /system/priv-app/GmsCore/GmsCore.apk / 1.0 running in null rsrc of package com.google.android.gms
09-15 12:03:02.944  3399  3399 W ResourcesManager: getTopLevelResources: /system/priv-app/GmsCore/GmsCore.apk / 1.0 running in null rsrc of package com.google.android.gms
09-15 12:03:02.944  3399  3399 W ResourcesManager: getTopLevelResources: /system/priv-app/GmsCore/GmsCore.apk / 1.0 running in null rsrc of package com.google.android.gms
09-15 12:03:02.944  3399  3399 W ResourcesManager: getTopLevelResources: /system/priv-app/GmsCore/GmsCore.apk / 1.0 running in null rsrc of package com.google.android.gms
09-15 12:03:02.944  3399  3399 W ResourcesManager: getTopLevelResources: /system/priv-app/GmsCore/GmsCore.apk / 1.0 running in null rsrc of package com.google.android.gms
09-15 12:03:02.944  3399  3399 W ResourcesManager: getTopLevelResources: /system/priv-app/GmsCore/GmsCore.apk / 1.0 running in null rsrc of package com.google.android.gms
,09-15 12:03:02.944  3399  3399 W ResourcesManager: getTopLevelResources: /system/priv-app/GmsCore/GmsCore.apk / 1.0 running in null rsrc of package com.google.android.gms
09-15 12:03:02.944  3399  3399 W ResourcesManager: getTopLevelResources: /system/priv-app/GmsCore/GmsCore.apk / 1.0 running in null rsrc of package com.google.android.gms
09-15 12:03:02.944  3399  3399 W ResourcesManager: getTopLevelResources: /system/priv-app/GmsCore/GmsCore.apk / 1.0 running in null rsrc of package com.google.android.gms
09-15 12:03:02.944  3399  3399 W ResourcesManager: getTopLevelResources: /system/priv-app/GmsCore/GmsCore.apk / 1.0 running in null rsrc of package com.google.android.gms
09-15 12:03:02.944  3399  3399 W ResourcesManager: getTopLevelResources: /system/priv-app/GmsCore/GmsCore.apk / 1.0 running in null rsrc of package com.google.android.gms
,09-15 12:03:02.944  3399  3399 W ResourcesManager: getTopLevelResources: /system/priv-app/GmsCore/GmsCore.apk / 1.0 running in null rsrc of package com.google.android.gms
09-15 12:03:02.944  3399  3399 W ResourcesManager: getTopLevelResources: /system/priv-app/GmsCore/GmsCore.apk / 1.0 running in null rsrc of package com.google.android.gms
09-15 12:03:02.944  3399  3399 W ResourcesManager: getTopLevelResources: /system/priv-app/GmsCore/GmsCore.apk / 1.0 running in null rsrc of package com.google.android.gms
09-15 12:03:02.944  3399  3399 W ResourcesManager: getTopLevelResources: /system/priv-app/GmsCore/GmsCore.apk / 1.0 running in null rsrc of package com.google.android.gms
09-15 12:03:02.954  3944  4101 V KeyguardBottomAreaShortcutView: updateRightPreview - mRightAffordanceView
,09-15 12:03:02.944  3399  3399 W ResourcesManager: getTopLevelResources: /system/priv-app/GmsCore/GmsCore.apk / 1.0 running in null rsrc of package com.google.android.gms
09-15 12:03:02.954  3944  4101 D ShortcutManager: th = 1 is camera package
09-15 12:03:02.944  3399  3399 W ResourcesManager: getTopLevelResources: /system/priv-app/GmsCore/GmsCore.apk / 1.0 running in null rsrc of package com.google.android.gms
09-15 12:03:02.944  3399  3399 W ResourcesManager: getTopLevelResources: /system/priv-app/GmsCore/GmsCore.apk / 1.0 running in null rsrc of package com.google.android.gms
09-15 12:03:02.944  3399  3527 D ResourcesManager: For user 0 new overlays fetched Null
09-15 12:03:02.944  3399  3399 W ResourcesManager: getTopLevelResources: /system/priv-app/GmsCore/GmsCore.apk / 1.0 running in null rsrc of package com.google.android.gms
09-15 12:03:02.944  3399  3399 W ResourcesManager: getTopLevelResources: /system/priv-app/GmsCore/GmsCore.apk / 1.0 running in null rsrc of package com.google.android.gms
,09-15 12:03:02.944  3399  3399 W ResourcesManager: getTopLevelResources: /system/priv-app/GmsCore/GmsCore.apk / 1.0 running in null rsrc of package com.google.android.gms
09-15 12:03:02.944  3399  3527 W ResourcesManager: getTopLevelResources: /system/priv-app/Velvet/Velvet.apk / 1.0 running in null rsrc of package com.google.android.googlequicksearchbox
09-15 12:03:02.944  3399  3399 W ResourcesManager: getTopLevelResources: /system/priv-app/GmsCore/GmsCore.apk / 1.0 running in null rsrc of package com.google.android.gms
09-15 12:03:02.944  3399  3399 W ResourcesManager: getTopLevelResources: /system/priv-app/GoogleServicesFramework/GoogleServicesFramework.apk / 1.0 running in null rsrc of package com.google.android.gsf
09-15 12:03:02.944  3399  3527 W ResourcesManager: getTopLevelResources: /system/app/SamsungIMEv3/SamsungIMEv3.apk / 1.0 running in null rsrc of package com.sec.android.inputmethod
09-15 12:03:02.954  3399  3399 D ResourcesManager: For user 0 new overlays fetched Null
09-15 12:03:02.954  3399  3527 D ResourcesManager: For user 0 new overlays fetched Null
,09-15 12:03:02.954  3399  3399 W ResourcesManager: getTopLevelResources: /system/priv-app/GoogleServicesFramework/GoogleServicesFramework.apk / 1.0 running in null rsrc of package com.google.android.gsf
09-15 12:03:02.954  3399  3399 W ResourcesManager: getTopLevelResources: /system/priv-app/SHealth4/SHealth4.apk / 1.0 running in null rsrc of package com.sec.android.app.shealth
09-15 12:03:02.954  3399  3527 W ResourcesManager: getTopLevelResources: /system/app/SamsungIMEv3/SamsungIMEv3.apk / 1.0 running in null rsrc of package com.sec.android.inputmethod
,09-15 12:03:02.954  3399  3527 W ResourcesManager: getTopLevelResources: /system/priv-app/Velvet/Velvet.apk / 1.0 running in null rsrc of package com.google.android.googlequicksearchbox
,09-15 12:03:02.954  3399  3527 W ResourcesManager: getTopLevelResources: /system/app/SamsungIMEv3/SamsungIMEv3.apk / 1.0 running in null rsrc of package com.sec.android.inputmethod
09-15 12:03:02.954  3399  3527 W ResourcesManager: getTopLevelResources: /system/app/SamsungIMEv3/SamsungIMEv3.apk / 1.0 running in null rsrc of package com.sec.android.inputmethod
,09-15 12:03:02.954  3399  3527 W ResourcesManager: getTopLevelResources: /system/priv-app/LiveBroadcast/LiveBroadcast.apk / 1.0 running in null rsrc of package com.sec.android.app.camera.plb
09-15 12:03:02.954  3399  3399 D ResourcesManager: For user 0 new overlays fetched Null
,09-15 12:03:02.954  3399  3399 W ResourcesManager: getTopLevelResources: /system/priv-app/SHealth4/SHealth4.apk / 1.0 running in null rsrc of package com.sec.android.app.shealth
09-15 12:03:02.954  3399  3399 W ResourcesManager: getTopLevelResources: /system/priv-app/SHealth4/SHealth4.apk / 1.0 running in null rsrc of package com.sec.android.app.shealth
09-15 12:03:02.954  3399  3399 W ResourcesManager: getTopLevelResources: /system/priv-app/SHealth4/SHealth4.apk / 1.0 running in null rsrc of package com.sec.android.app.shealth
09-15 12:03:02.954  3399  3399 W ResourcesManager: getTopLevelResources: /system/priv-app/SNS_v2/SNS_v2.apk / 1.0 running in null rsrc of package com.sec.android.app.sns3
09-15 12:03:02.954  3399  3527 D ResourcesManager: For user 0 new overlays fetched Null
,09-15 12:03:02.954  3399  3399 W ResourcesManager: getTopLevelResources: /system/priv-app/SNS_v2/SNS_v2.apk / 1.0 running in null rsrc of package com.sec.android.app.sns3
09-15 12:03:02.954  3399  3399 W ResourcesManager: getTopLevelResources: /system/priv-app/SNS_v2/SNS_v2.apk / 1.0 running in null rsrc of package com.sec.android.app.sns3
09-15 12:03:02.954  3399  3527 W ResourcesManager: getTopLevelResources: /system/priv-app/LiveBroadcast/LiveBroadcast.apk / 1.0 running in null rsrc of package com.sec.android.app.camera.plb
09-15 12:03:02.954  3399  3399 W ResourcesManager: getTopLevelResources: /system/priv-app/SNS_v2/SNS_v2.apk / 1.0 running in null rsrc of package com.sec.android.app.sns3
09-15 12:03:02.954  3399  3527 W ResourcesManager: getTopLevelResources: /system/priv-app/SamsungCamera5/SamsungCamera5.apk / 1.0 running in null rsrc of package com.sec.android.app.camera
09-15 12:03:02.954  3399  3399 W ResourcesManager: getTopLevelResources: /system/priv-app/SNS_v2/SNS_v2.apk / 1.0 running in null rsrc of package com.sec.android.app.sns3
09-15 12:03:02.954  3399  3399 W ResourcesManager: getTopLevelResources: /system/priv-app/SNS_v2/SNS_v2.apk / 1.0 running in null rsrc of package com.sec.android.app.sns3
09-15 12:03:02.954  3399  3399 W ResourcesManager: getTopLevelResources: /system/priv-app/SNS_v2/SNS_v2.apk / 1.0 running in null rsrc of package com.sec.android.app.sns3
,09-15 12:03:02.954  3399  3399 W ResourcesManager: getTopLevelResources: /system/priv-app/SNS_v2/SNS_v2.apk / 1.0 running in null rsrc of package com.sec.android.app.sns3
09-15 12:03:02.954  3399  3399 W ResourcesManager: getTopLevelResources: /system/priv-app/SNS_v2/SNS_v2.apk / 1.0 running in null rsrc of package com.sec.android.app.sns3
09-15 12:03:02.954  3399  3399 W ResourcesManager: getTopLevelResources: /system/priv-app/SNS_v2/SNS_v2.apk / 1.0 running in null rsrc of package com.sec.android.app.sns3
09-15 12:03:02.954  3399  3399 W ResourcesManager: getTopLevelResources: /system/priv-app/SNS_v2/SNS_v2.apk / 1.0 running in null rsrc of package com.sec.android.app.sns3
09-15 12:03:02.954  3399  3399 W ResourcesManager: getTopLevelResources: /system/priv-app/SNS_v2/SNS_v2.apk / 1.0 running in null rsrc of package com.sec.android.app.sns3
09-15 12:03:02.954  3399  3399 W ResourcesManager: getTopLevelResources: /system/priv-app/SecEmail_M/SecEmail_M.apk / 1.0 running in null rsrc of package com.samsung.android.email.provider
,09-15 12:03:02.954  3399  3399 W ResourcesManager: getTopLevelResources: /system/priv-app/SecEmail_M/SecEmail_M.apk / 1.0 running in null rsrc of package com.samsung.android.email.provider
09-15 12:03:02.954  3399  3399 W ResourcesManager: getTopLevelResources: /system/priv-app/SecEmail_M/SecEmail_M.apk / 1.0 running in null rsrc of package com.samsung.android.email.provider
09-15 12:03:02.954  3399  3527 D ResourcesManager: For user 0 new overlays fetched Null
09-15 12:03:02.954  3399  3399 W ResourcesManager: getTopLevelResources: /system/priv-app/SecEmail_M/SecEmail_M.apk / 1.0 running in null rsrc of package com.samsung.android.email.provider
09-15 12:03:02.954  3399  3399 W ResourcesManager: getTopLevelResources: /system/priv-app/SecEmail_M/SecEmail_M.apk / 1.0 running in null rsrc of package com.samsung.android.email.provider
09-15 12:03:02.954  3399  3399 W ResourcesManager: getTopLevelResources: /system/priv-app/SecEmail_M/SecEmail_M.apk / 1.0 running in null rsrc of package com.samsung.android.email.provider
09-15 12:03:02.954  3399  3527 W ResourcesManager: getTopLevelResources: /system/priv-app/SamsungCamera5/SamsungCamera5.apk / 1.0 running in null rsrc of package com.sec.android.app.camera
,09-15 12:03:02.954  3399  3399 W ResourcesManager: getTopLevelResources: /system/priv-app/SecEmail_M/SecEmail_M.apk / 1.0 running in null rsrc of package com.samsung.android.email.provider
09-15 12:03:02.954  3399  3527 W ResourcesManager: getTopLevelResources: /system/app/STalkback/STalkback.apk / 1.0 running in null rsrc of package com.samsung.android.app.talkback
09-15 12:03:02.954  3399  3399 W ResourcesManager: getTopLevelResources: /system/priv-app/SecEmail_M/SecEmail_M.apk / 1.0 running in null rsrc of package com.samsung.android.email.provider
09-15 12:03:02.954  3399  3399 W ResourcesManager: getTopLevelResources: /system/priv-app/SecEmail_M/SecEmail_M.apk / 1.0 running in null rsrc of package com.samsung.android.email.provider
09-15 12:03:02.964  3399  3399 W ResourcesManager: getTopLevelResources: /system/priv-app/SecEmail_M/SecEmail_M.apk / 1.0 running in null rsrc of package com.samsung.android.email.provider
,09-15 12:03:02.964  3399  3399 W ResourcesManager: getTopLevelResources: /system/priv-app/SecEmail_M/SecEmail_M.apk / 1.0 running in null rsrc of package com.samsung.android.email.provider
09-15 12:03:02.964  3399  3399 W ResourcesManager: getTopLevelResources: /system/priv-app/SecEmail_M/SecEmail_M.apk / 1.0 running in null rsrc of package com.samsung.android.email.provider
09-15 12:03:02.964  3399  3399 W ResourcesManager: getTopLevelResources: /system/priv-app/SecEmail_M/SecEmail_M.apk / 1.0 running in null rsrc of package com.samsung.android.email.provider
09-15 12:03:02.964  3399  3399 W ResourcesManager: getTopLevelResources: /system/priv-app/SecEmail_M/SecEmail_M.apk / 1.0 running in null rsrc of package com.samsung.android.email.provider
09-15 12:03:02.964  3399  3399 W ResourcesManager: getTopLevelResources: /system/priv-app/SecEmail_M/SecEmail_M.apk / 1.0 running in null rsrc of package com.samsung.android.email.provider
09-15 12:03:02.964  3399  3527 D ResourcesManager: For user 0 new overlays fetched Null
09-15 12:03:02.964  3399  3399 W ResourcesManager: getTopLevelResources: /system/priv-app/SecEmail_M/SecEmail_M.apk / 1.0 running in null rsrc of package com.samsung.android.email.provider
,09-15 12:03:02.964  3399  3399 W ResourcesManager: getTopLevelResources: /system/priv-app/SamsungCloud/SamsungCloud.apk / 1.0 running in null rsrc of package com.samsung.android.scloud
09-15 12:03:02.964  3399  3527 W ResourcesManager: getTopLevelResources: /system/app/STalkback/STalkback.apk / 1.0 running in null rsrc of package com.samsung.android.app.talkback
09-15 12:03:02.964  3399  3527 W ResourcesManager: getTopLevelResources: /system/app/UniversalSwitch/UniversalSwitch.apk / 1.0 running in null rsrc of package com.samsung.android.universalswitch
,09-15 12:03:02.964  3399  3399 D ResourcesManager: For user 0 new overlays fetched Null
,09-15 12:03:02.964  3399  3527 D ResourcesManager: For user 0 new overlays fetched Null
09-15 12:03:02.964  3399  3527 W ResourcesManager: getTopLevelResources: /system/app/UniversalSwitch/UniversalSwitch.apk / 1.0 running in null rsrc of package com.samsung.android.universalswitch
09-15 12:03:02.964  3399  3399 W ResourcesManager: getTopLevelResources: /system/priv-app/SamsungCloud/SamsungCloud.apk / 1.0 running in null rsrc of package com.samsung.android.scloud
09-15 12:03:02.964  8813  9484 W System.err: remove failed: ENOENT (No such file or directory) : /storage/emulated/0/Android/media/com.test.thalitest
,09-15 12:03:02.964  3399  3399 W ResourcesManager: getTopLevelResources: /system/priv-app/SamsungCloud/SamsungCloud.apk / 1.0 running in null rsrc of package com.samsung.android.scloud
09-15 12:03:02.964  3399  3527 D AccessibilityManagerService: onUserStateChangedLocked()
,09-15 12:03:02.964  3399  3527 D AccessibilityManagerService: updateServicesLocked().mIsAccessibilityEnabled : false
09-15 12:03:02.964  3399  3399 W ResourcesManager: getTopLevelResources: /system/priv-app/SamsungCloud/SamsungCloud.apk / 1.0 running in null rsrc of package com.samsung.android.scloud
09-15 12:03:02.964  3399  3399 W ResourcesManager: getTopLevelResources: /system/priv-app/SamsungCloud/SamsungCloud.apk / 1.0 running in null rsrc of package com.samsung.android.scloud
,09-15 12:03:02.964  3399  3399 W ResourcesManager: getTopLevelResources: /system/priv-app/SamsungCloud/SamsungCloud.apk / 1.0 running in null rsrc of package com.samsung.android.scloud
09-15 12:03:02.964  3399  3399 W ResourcesManager: getTopLevelResources: /system/priv-app/SamsungCloud/SamsungCloud.apk / 1.0 running in null rsrc of package com.samsung.android.scloud
09-15 12:03:02.964  3399  3399 W ResourcesManager: getTopLevelResources: /system/priv-app/SamsungCloud/SamsungCloud.apk / 1.0 running in null rsrc of package com.samsung.android.scloud
09-15 12:03:02.964  3399  3399 W ResourcesManager: getTopLevelResources: /system/priv-app/SamsungCloud/SamsungCloud.apk / 1.0 running in null rsrc of package com.samsung.android.scloud
,09-15 12:03:02.964  3399  3399 W ResourcesManager: getTopLevelResources: /system/priv-app/SamsungCloud/SamsungCloud.apk / 1.0 running in null rsrc of package com.samsung.android.scloud
09-15 12:03:02.964  3399  3399 W ResourcesManager: getTopLevelResources: /system/priv-app/SamsungCloud/SamsungCloud.apk / 1.0 running in null rsrc of package com.samsung.android.scloud
09-15 12:03:02.964  3399  3399 W ResourcesManager: getTopLevelResources: /system/priv-app/SamsungCloud/SamsungCloud.apk / 1.0 running in null rsrc of package com.samsung.android.scloud
09-15 12:03:02.964  3399  3399 W ResourcesManager: getTopLevelResources: /system/priv-app/SamsungCloud/SamsungCloud.apk / 1.0 running in null rsrc of package com.samsung.android.scloud
09-15 12:03:02.964  3399  3399 W ResourcesManager: getTopLevelResources: /system/priv-app/SamsungCloud/SamsungCloud.apk / 1.0 running in null rsrc of package com.samsung.android.scloud
,09-15 12:03:02.964  3399  3399 W ResourcesManager: getTopLevelResources: /system/app/Chrome/Chrome.apk / 1.0 running in null rsrc of package com.android.chrome
09-15 12:03:02.964  3399  3399 D ResourcesManager: For user 0 new overlays fetched Null
09-15 12:03:02.964  3399  3399 W ResourcesManager: getTopLevelResources: /system/app/Chrome/Chrome.apk / 1.0 running in null rsrc of package com.android.chrome
09-15 12:03:02.964  3399  3399 W ResourcesManager: getTopLevelResources: /system/app/CoreApps/CoreApps.apk / 1.0 running in null rsrc of package com.samsung.android.coreapps
09-15 12:03:02.964  3399  3399 W ResourcesManager: getTopLevelResources: /system/app/CoreApps/CoreApps.apk / 1.0 running in null rsrc of package com.samsung.android.coreapps
,09-15 12:03:02.964  3399  3399 W ResourcesManager: getTopLevelResources: /system/app/Drive/Drive.apk / 1.0 running in null rsrc of package com.google.android.apps.docs
09-15 12:03:02.964  3399  3399 D ResourcesManager: For user 0 new overlays fetched Null
09-15 12:03:02.964  3399  3399 W ResourcesManager: getTopLevelResources: /system/app/Drive/Drive.apk / 1.0 running in null rsrc of package com.google.android.apps.docs
09-15 12:03:02.964  3399  3399 W ResourcesManager: getTopLevelResources: /system/app/Gmail2/Gmail2.apk / 1.0 running in null rsrc of package com.google.android.gm
09-15 12:03:02.964  3399  3399 W ResourcesManager: getTopLevelResources: /system/app/Gmail2/Gmail2.apk / 1.0 running in null rsrc of package com.google.android.gm
,09-15 12:03:02.964  3399  3399 W ResourcesManager: getTopLevelResources: /system/app/Gmail2/Gmail2.apk / 1.0 running in null rsrc of package com.google.android.gm
09-15 12:03:02.964  3399  3399 W ResourcesManager: getTopLevelResources: /system/app/Gmail2/Gmail2.apk / 1.0 running in null rsrc of package com.google.android.gm
09-15 12:03:02.964  3399  3399 W ResourcesManager: getTopLevelResources: /system/app/Gmail2/Gmail2.apk / 1.0 running in null rsrc of package com.google.android.gm
09-15 12:03:02.964  3399  3399 W ResourcesManager: getTopLevelResources: /system/app/Gmail2/Gmail2.apk / 1.0 running in null rsrc of package com.google.android.gm
09-15 12:03:02.964  3399  3399 W ResourcesManager: getTopLevelResources: /system/app/GoogleCalendarSyncAdapter/GoogleCalendarSyncAdapter.apk / 1.0 running in null rsrc of package com.google.android.syncadapters.calendar
09-15 12:03:02.974  3399  3399 D ResourcesManager: For user 0 new overlays fetched Null
09-15 12:03:02.974  3399  3399 W ResourcesManager: getTopLevelResources: /system/app/GoogleCalendarSyncAdapter/GoogleCalendarSyncAdapter.apk / 1.0 running in null rsrc of package com.google.android.syncadapters.calendar
09-15 12:03:02.974  3399  3399 W ResourcesManager: getTopLevelResources: /system/app/GoogleContactsSyncAdapter/GoogleContactsSyncAdapter.apk / 1.0 running in null rsrc of package com.google.android.syncadapters.contacts
09-15 12:03:02.974  3399  3399 D ResourcesManager: For user 0 new overlays fetched Null
,09-15 12:03:02.974  3399  3399 W ResourcesManager: getTopLevelResources: /system/app/GoogleContactsSyncAdapter/GoogleContactsSyncAdapter.apk / 1.0 running in null rsrc of package com.google.android.syncadapters.contacts
09-15 12:03:02.974  3399  3399 W ResourcesManager: getTopLevelResources: /system/app/Music2/Music2.apk / 1.0 running in null rsrc of package com.google.android.music
,09-15 12:03:02.974  3399  3399 D ResourcesManager: For user 0 new overlays fetched Null
,09-15 12:03:02.974  3399  3399 W ResourcesManager: getTopLevelResources: /system/app/Music2/Music2.apk / 1.0 running in null rsrc of package com.google.android.music
09-15 12:03:02.974  3399  3399 W ResourcesManager: getTopLevelResources: /system/app/OneDrive_Samsung_v2/OneDrive_Samsung_v2.apk / 1.0 running in null rsrc of package com.microsoft.skydrive
09-15 12:03:02.974  3399  3399 W ResourcesManager: getTopLevelResources: /system/app/OneDrive_Samsung_v2/OneDrive_Samsung_v2.apk / 1.0 running in null rsrc of package com.microsoft.skydrive
09-15 12:03:02.974  3399  3399 W ResourcesManager: getTopLevelResources: /system/app/OneNote/OneNote.apk / 1.0 running in null rsrc of package com.microsoft.office.onenote
,09-15 12:03:02.974  3399  3399 W ResourcesManager: getTopLevelResources: /system/app/OneNote/OneNote.apk / 1.0 running in null rsrc of package com.microsoft.office.onenote
09-15 12:03:02.974  3399  3399 W ResourcesManager: getTopLevelResources: /system/app/SBrowser_4_LATEST/SBrowser_4_LATEST.apk / 1.0 running in null rsrc of package com.sec.android.app.sbrowser
09-15 12:03:02.974  3399  3399 W ResourcesManager: getTopLevelResources: /system/app/SBrowser_4_LATEST/SBrowser_4_LATEST.apk / 1.0 running in null rsrc of package com.sec.android.app.sbrowser
09-15 12:03:02.974  3399  3399 W ResourcesManager: getTopLevelResources: /system/app/Videos/Videos.apk / 1.0 running in null rsrc of package com.google.android.videos
,09-15 12:03:02.974  3399  3399 D ResourcesManager: For user 0 new overlays fetched Null
,09-15 12:03:02.974  3399  3399 W ResourcesManager: getTopLevelResources: /system/app/Videos/Videos.apk / 1.0 running in null rsrc of package com.google.android.videos
09-15 12:03:02.974  3399  3399 V AlarmManager: Remove alarm for next reason : android.intent.action.PACKAGE_REMOVED : package: com.test.thalitest
09-15 12:03:02.974  3399  3399 I HarmonyEASService: onReceive : android.intent.action.PACKAGE_REMOVED for 0
09-15 12:03:02.974  3399  3399 V AlarmManagerEXT: com.test.thalitest(10171) is removed.
,09-15 12:03:02.974  3399  3399 W System.err: java.io.FileNotFoundException: /data/system/harmony_third_party_apps.xml.tmp: open failed: EROFS (Read-only file system)
09-15 12:03:02.974  3399  3399 W System.err: 	at libcore.io.IoBridge.open(IoBridge.java:452)
,09-15 12:03:02.984  3399  3399 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
,09-15 12:03:02.984  3399  3399 W System.err: 	at com.android.server.HarmonyEASService.saveHash(HarmonyEASService.java:303)
09-15 12:03:02.984  3399  3399 W System.err: 	at com.android.server.HarmonyEASService.access$000(HarmonyEASService.java:60)
09-15 12:03:02.984  3399  3399 W System.err: 	at com.android.server.HarmonyEASService$PackageHandler.handleMessage(HarmonyEASService.java:100)
09-15 12:03:02.984  3399  3399 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-15 12:03:02.984  3399  3399 W System.err: 	at android.os.Looper.loop(Looper.java:158)
09-15 12:03:02.984  3399  3399 W System.err: 	at com.android.server.SystemServer.run(SystemServer.java:508)
09-15 12:03:02.984  3399  3399 W System.err: 	at com.android.server.SystemServer.main(SystemServer.java:363)
09-15 12:03:02.984  3399  3399 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
09-15 12:03:02.984  3399  3399 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1230)
09-15 12:03:02.984  3399  3399 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1120)
09-15 12:03:02.984  3399  3399 W System.err: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
09-15 12:03:02.984  3399  3399 W System.err: 	at libcore.io.Posix.open(Native Method)
09-15 12:03:02.984  3399  3399 W System.err: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
09-15 12:03:02.984  3399  3399 W System.err: 	at libcore.io.IoBridge.open(IoBridge.java:438)
09-15 12:03:02.984  3399  3399 W System.err: 	... 11 more
09-15 12:03:02.984  3399  3399 W System.err: remove failed: ENOENT (No such file or directory) : /data/system/harmony_third_party_apps.xml.tmp
,09-15 12:03:02.984  3399  3399 W System.err: java.io.FileNotFoundException: /data/system/harmony_third_party_apps.xml.tmp: open failed: EROFS (Read-only file system)
09-15 12:03:02.984  3399  3399 W System.err: 	at libcore.io.IoBridge.open(IoBridge.java:452)
09-15 12:03:02.984  3399  3399 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
09-15 12:03:02.984  3399  3399 W System.err: 	at com.android.server.HarmonyEASService.saveHash(HarmonyEASService.java:303)
09-15 12:03:02.984  3399  3399 W System.err: 	at com.android.server.HarmonyEASService.access$000(HarmonyEASService.java:60)
09-15 12:03:02.984  3399  3399 W System.err: 	at com.android.server.HarmonyEASService$PackageHandler.handleMessage(HarmonyEASService.java:100)
09-15 12:03:02.984  3399  3399 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-15 12:03:02.984  3399  3399 W System.err: 	at android.os.Looper.loop(Looper.java:158)
09-15 12:03:02.984  3399  3399 W System.err: 	at com.android.server.SystemServer.run(SystemServer.java:508)
09-15 12:03:02.984  3399  3399 W System.err: 	at com.android.server.SystemServer.main(SystemServer.java:363)
09-15 12:03:02.984  3399  3399 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
09-15 12:03:02.984  3399  3399 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1230)
09-15 12:03:02.984  3399  3399 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1120)
09-15 12:03:02.984  3399  3399 W System.err: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
09-15 12:03:02.984  3399  3399 W System.err: 	at libcore.io.Posix.open(Native Method)
09-15 12:03:02.984  3399  3399 W System.err: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
09-15 12:03:02.984  3399  3399 W System.err: 	at libcore.io.IoBridge.open(IoBridge.java:438)
09-15 12:03:02.984  3399  3399 W System.err: 	... 11 more
09-15 12:03:02.984  3399  3399 W System.err: remove failed: ENOENT (No such file or directory) : /data/system/harmony_third_party_apps.xml.tmp
,09-15 12:03:02.984  3399  3399 D UniversalCredentialManagerService: inside mPkgReciever onReceive : android.intent.action.PACKAGE_REMOVED
09-15 12:03:02.984  3399  3399 D UniversalCredentialManagerService: ACTION_PACKAGE_REMOVED is called....
09-15 12:03:02.984  3399  3399 D UniversalCredentialManagerService: ****MSG_CLEAN_INFO block started****
09-15 12:03:02.984  3399  3399 D UniversalCredentialManagerService: uid - 10171, userId-0
09-15 12:03:02.984  3399  3399 D UniversalCredentialManagerService: notifyChangeToPlugin is called for package uninstalled...
09-15 12:03:02.984  3399  3399 D UcmService: notifyChangeToPlugin event 12
09-15 12:03:02.984  3399  3399 D UcmService: checkCallerPermissionFor is called for method-notifyChangeToPlugin
09-15 12:03:02.984  3399  3399 I UcmService: checkIfNotify for cs Name = com.sec.smartcard.manager:com.samsung.ucs.agent.baiMobile Package name = com.sec.smartcard.manager
09-15 12:03:02.984  3399  3399 D UcmService: notifying to unmanaged plugin
09-15 12:03:02.984  8813  9484 W System.err: remove failed: ENOENT (No such file or directory) : /storage/emulated/0/Android/obb/com.test.thalitest
09-15 12:03:02.984  4330  4361 E ucsBai_agentService: notifyChange NOT SUPPORTED
,09-15 12:03:02.984  3399  3399 D UcmService: agentService com.sec.smartcard.manager:com.samsung.ucs.agent.baiMobile notify status - 0
09-15 12:03:02.984  3399  3399 D UcmService: agentService status-0
09-15 12:03:02.984  3399  3399 I UcmService: checkIfNotify for cs Name = com.samsung.ucs.agent.ese:eSE Credential Storage Package name = com.samsung.ucs.agent.ese
09-15 12:03:02.984  3399  3399 D UcmService: notifying to managed plugin
09-15 12:03:02.984  3399  3399 D UcmService: checkIfNotify: Valid userid - 0
09-15 12:03:02.984  3399  3399 D PolicyManager: PolicyManager.isStorageEnabled() for userId = 0
09-15 12:03:02.984  3399  3399 D UniversalCredentialManagerService: checkCallerPermissionFor is called for method-isCredentialStorageManagedAsUser
09-15 12:03:02.984  3399  3399 D UniversalCredentialManagerService: isCredentialStorageManagedAsUser is called....
09-15 12:03:02.984  3399  3399 D PolicyManager: PolicyManager.isStorageEnabled() result = false
09-15 12:03:02.984  3399  3399 D UcmService: agentService com.samsung.ucs.agent.ese:eSE Credential Storage not notified
09-15 12:03:02.984  3399  3399 D UcmService: agentService status-0
09-15 12:03:02.984  3399  3399 I UcmService: checkIfNotify for cs Name = com.samsung.ucs.agent.boot:com.samsung.ucs.agent.boot Package name = com.samsung.ucs.agent.boot
09-15 12:03:02.984  3399  3399 D UcmService: notifying to unmanaged plugin
09-15 12:03:02.984  4340  4403 D BootAgentService: notifyChange eventId-12
,09-15 12:03:02.984  3399  3399 D UcmService: agentService com.samsung.ucs.agent.boot:com.samsung.ucs.agent.boot notify status - -1
09-15 12:03:02.984  3399  3399 D UcmService: agentService status--1
09-15 12:03:02.984  3399  3399 D UniversalCredentialManagerService: ****MSG_CLEAN_INFO block ended****
09-15 12:03:02.984  3399  3399 D KnoxMUMContainerPolicy: mPackageReceiver : action - android.intent.action.PACKAGE_REMOVED
09-15 12:03:02.984  3399  3399 I OTPFW   : PackageRemovalReceiver::onReceive Enter
09-15 12:03:02.984  3399  3399 D OTPFW   : PackageRemovalReceiver::onReceive deleting token for Pkg = com.test.thalitest uid = 10171 container id = 0
,09-15 12:03:02.984  3399  3399 I OTPFW   : ProvisionData::getAllEntries Enter
,09-15 12:03:02.984  3399  3399 E OTPFW   : ProvisionData::getAllEntries Table is empty
09-15 12:03:02.994  3399  3399 E SDAgentPackageStateReceiver: Not going to handle 'com.test.thalitest'!
09-15 12:03:02.994  3399  3527 D EnterpriseDeviceManagerService: Package has changed for user 0
09-15 12:03:02.994  3399  3527 D EnterpriseDeviceManagerService: Admin package name: com.google.android.gms
09-15 12:03:02.994  3399  3399 D AccessibilityManagerService: checkUniversalSwitchState start:
09-15 12:03:02.994  3399  3399 D AccessibilityManagerService: checkUniversalSwitchState universalSwitchEnabled:false
09-15 12:03:02.994  3399  3399 D AccessibilityManagerService: updateInputFilter universalSwitchState:false
09-15 12:03:02.994  3399  3399 D AccessibilityManagerService: updateInputFilter userState.mIsUniversalSwitchEnabled:false
,09-15 12:03:02.994  3399  3527 W ResourcesManager: getTopLevelResources: /system/app/SamsungIMEv3/SamsungIMEv3.apk / 1.0 running in null rsrc of package com.sec.android.inputmethod
,09-15 12:03:02.994  3399  3527 W ResourcesManager: getTopLevelResources: /system/app/SamsungIMEv3/SamsungIMEv3.apk / 1.0 running in null rsrc of package com.sec.android.inputmethod
,09-15 12:03:02.994  3399  4310 V WindowStateAnimator: Finishing drawing window Window{959948e u0 d0 com.sec.android.app.launcher/com.sec.android.app.launcher.activities.LauncherActivity}: mDrawState=DRAW_PENDING
,09-15 12:03:02.994  4280  4280 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@898930d time:185425
09-15 12:03:02.994  3399  3527 W ResourcesManager: getTopLevelResources: /system/priv-app/SecSettings2/SecSettings2.apk / 1.0 running in null rsrc of package com.android.settings
,09-15 12:03:02.994  3399  3399 D UcmService: onReceive android.intent.action.PACKAGE_REMOVED
09-15 12:03:02.994  3399  3399 D UcmService: Package update in userId-0 and uid-10171
09-15 12:03:02.994  3399  3399 D UcmService: *****refreshAgentList userId-0 is called***
09-15 12:03:02.994  3399  3399 D UcmService: resolveAllowedAgents for user 0
09-15 12:03:02.994  3399  3399 D UcmService: found com.sec.smartcard.manager
09-15 12:03:02.994  3399  3399 D UcmService: found com.samsung.ucs.agent.ese
09-15 12:03:02.994  3399  3527 D ResourcesManager: For user 0 new overlays fetched Null
09-15 12:03:02.994  3399  3399 D UcmService: found com.samsung.ucs.agent.boot
09-15 12:03:02.994  3399  3399 D UcmService: mPersistentServices size is 3
09-15 12:03:02.994  3399  3399 D UcmService: -------Processing started for agentPackageName----- -com.sec.smartcard.manager
09-15 12:03:02.994  3399  3399 D UcmService:   agentPackageName -com.sec.smartcard.manager is an active plugin
09-15 12:03:02.994  3399  3399 D UcmService:   Check if caller has UCS Plugin permission...
09-15 12:03:02.994  3399  3399 D UcmService:   Agent has UCS PLUGIN permission. Processing further...
09-15 12:03:02.994  3399  3399 D UcmService: -------Processing started for agentPackageName----- -com.samsung.ucs.agent.ese
09-15 12:03:02.994  3399  3399 D UcmService:   agentPackageName -com.samsung.ucs.agent.ese is an active plugin
09-15 12:03:02.994  3399  3399 D UcmService:   Check if caller has UCS Plugin permission...
09-15 12:03:02.994  3399  3399 D UcmService:   Agent has UCS PLUGIN permission. Processing further...
09-15 12:03:02.994  3399  3399 D UcmService:   agentPackageName com.samsung.ucs.agent.ese is system storage. Checking system signature
09-15 12:03:02.994  3399  3399 D UcmService:   Signature match
09-15 12:03:02.994  3399  3399 D UcmService:   Valid system storage found is com.samsung.ucs.agent.ese
09-15 12:03:02.994  3399  3399 D UcmService: -------Processing started for agentPackageName----- -com.samsung.ucs.agent.boot
09-15 12:03:02.994  3399  3527 W ResourcesManager: getTopLevelResources: /system/priv-app/SecSettings2/SecSettings2.apk / 1.0 running in null rsrc of package com.android.settings
09-15 12:03:02.994  3399  3399 D UcmService:   agentPackageName -com.samsung.ucs.agent.boot is an active plugin
09-15 12:03:02.994  3399  3399 D UcmService:   Check if caller has UCS Plugin permission...
09-15 12:03:02.994  3399  3399 D UcmService:   Agent has UCS PLUGIN permission. Processing further...
09-15 12:03:02.994  3399  3399 D UcmService:   agentPackageName com.samsung.ucs.agent.boot is system storage. Checking system signature
09-15 12:03:02.994  3399  3399 D UcmService:   Signature match
09-15 12:03:02.994  3399  3399 D UcmService:   Valid system storage found is com.samsung.ucs.agent.boot
,09-15 12:03:02.994  3399  3399 W System.err: rename failed: EROFS (Read-only file system) : /data/system/registered_ucm_services/com.samsung.ucm.agent.xml -> /data/system/registered_ucm_services/com.samsung.ucm.agent.xml.bak
09-15 12:03:02.994  3399  3527 W ResourcesManager: getTopLevelResources: /system/priv-app/SecContacts_M/SecContacts_M.apk / 1.0 running in null rsrc of package com.android.contacts
09-15 12:03:02.994  3399  3399 W AtomicFile: Couldn't rename file /data/system/registered_ucm_services/com.samsung.ucm.agent.xml to backup file /data/system/registered_ucm_services/com.samsung.ucm.agent.xml.bak
09-15 12:03:03.004  3399  3399 D InjectionManagerService -AppFeature:  Info before com.test.thalitest removal target ={} 
09-15 12:03:03.004  3399  3399 D InjectionManagerService -AppFeature:  source ={}
09-15 12:03:03.004  3399  3399 W UcmService: Error writing accounts
09-15 12:03:03.004  3399  3399 W UcmService: java.io.IOException: Couldn't create directory /data/system/registered_ucm_services/com.samsung.ucm.agent.xml
09-15 12:03:03.004  3399  3399 W UcmService: 	at android.util.AtomicFile.startWrite(AtomicFile.java:124)
09-15 12:03:03.004  3399  3399 W UcmService: 	at android.util.AtomicFile.startWrite(AtomicFile.java:100)
09-15 12:03:03.004  3399  3399 W UcmService: 	at com.samsung.ucm.ucmservice.CredentialManagerService.writePersistentServicesLocked(CredentialManagerService.java:810)
09-15 12:03:03.004  3399  3399 W UcmService: 	at com.samsung.ucm.ucmservice.CredentialManagerService.refreshAgentList(CredentialManagerService.java:573)
09-15 12:03:03.004  3399  3399 W UcmService: 	at com.samsung.ucm.ucmservice.CredentialManagerService.access$300(CredentialManagerService.java:95)
09-15 12:03:03.004  3399  3399 W UcmService: 	at com.samsung.ucm.ucmservice.CredentialManagerService$1.handleMessage(CredentialManagerService.java:188)
09-15 12:03:03.004  3399  3399 W UcmService: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-15 12:03:03.004  3399  3399 W UcmService: 	at android.os.Looper.loop(Looper.java:158)
09-15 12:03:03.004  3399  3399 W UcmService: 	at com.android.server.SystemServer.run(SystemServer.java:508)
09-15 12:03:03.004  3399  3399 W UcmService: 	at com.android.server.SystemServer.main(SystemServer.java:363)
09-15 12:03:03.004  3399  3399 W UcmService: 	at java.lang.reflect.Method.invoke(Native Method)
09-15 12:03:03.004  3399  3399 W UcmService: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1230)
09-15 12:03:03.004  3399  3399 W UcmService: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1120)
09-15 12:03:03.004  3399  3527 D ResourcesManager: For user 0 new overlays fetched Null
09-15 12:03:03.004  3399  3399 D UcmService: readPersistentServicesLocked is called...
09-15 12:03:03.004  3399  3527 W ResourcesManager: getTopLevelResources: /system/priv-app/SecContacts_M/SecContacts_M.apk / 1.0 running in null rsrc of package com.android.contacts
09-15 12:03:03.004  3399  3399 D UcmService: PersistentServices  key-com.samsung.ucs.agent.boot:com.samsung.ucs.agent.boot
09-15 12:03:03.004  3399  3399 D UcmService: PersistentServices  value-1000
09-15 12:03:03.004  3399  3399 D UcmService: PersistentServices  key-com.sec.smartcard.manager:com.samsung.ucs.agent.baiMobile
09-15 12:03:03.004  3399  3527 W ResourcesManager: getTopLevelResources: /system/priv-app/SecContacts_M/SecContacts_M.apk / 1.0 running in null rsrc of package com.android.contacts
09-15 12:03:03.004  3399  3399 D UcmService: PersistentServices  value-10059
09-15 12:03:03.004  3399  3399 D UcmService: PersistentServices  key-com.samsung.ucs.agent.ese:eSE Credential Storage
09-15 12:03:03.004  3399  3399 D UcmService: PersistentServices  value-10094
09-15 12:03:03.004  3399  3399 W SQLiteLog: (28) failed to open "/data/system/gamemanager.db" with flag (131138) and mode_t (0) due to error (30)
09-15 12:03:03.004  3399  3527 W ResourcesManager: getTopLevelResources: /system/priv-app/SecContacts_M/SecContacts_M.apk / 1.0 running in null rsrc of package com.and,roid.contacts
09-15 12:03:03.004  3944  4101 V PreviewInflater: switching default camera action
09-15 12:03:03.004  3399  3527 W ResourcesManager: getTopLevelResources: /system/priv-app/SecEmail_M/SecEmail_M.apk / 1.0 running in null rsrc of package com.samsung.android.email.provider
09-15 12:03:03.004  3399  3527 W ResourcesManager: getTopLevelResources: /system/priv-app/SecEmail_M/SecEmail_M.apk / 1.0 running in null rsrc of package com.samsung.android.email.provider
09-15 12:03:03.004  3399  3527 W ResourcesManager: getTopLevelResources: /system/priv-app/SecMms_Epic_Common/SecMms_Epic_Common.apk / 1.0 running in null rsrc of package com.android.mms
09-15 12:03:03.004  3399  3399 E SQLiteDatabase: Failed to open database '/data/system/gamemanager.db'.
09-15 12:03:03.004  3399  3399 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-15 12:03:03.004  3399  3399 E SQLiteDatabase: #################################################################
09-15 12:03:03.004  3399  3399 E SQLiteDatabase: Error Code : 0 (SQLITE_OK)
09-15 12:03:03.004  3399  3399 E SQLiteDatabase: Caused By : not an error (code 0): Could not open the database in read/write mode.
09-15 12:03:03.004  3399  3399 E SQLiteDatabase: #################################################################
09-15 12:03:03.004  3399  3399 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
09-15 12:03:03.004  3399  3399 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:283)
09-15 12:03:03.004  3399  3399 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:210)
09-15 12:03:03.004  3399  3399 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
09-15 12:03:03.004  3399  3399 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
09-15 12:03:03.004  3399  3399 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
09-15 12:03:03.004  3399  3399 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
09-15 12:03:03.004  3399  3399 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
09-15 12:03:03.004  3399  3399 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
09-15 12:03:03.004  3399  3399 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:633)
09-15 12:03:03.004  3399  3399 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
09-15 12:03:03.004  3399  3399 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
09-15 12:03:03.004  3399  3399 E SQLiteDatabase: 	at com.samsung.android.game.data.DatabaseHelper.removeGame(DatabaseHelper.java:144)
09-15 12:03:03.004  3399  3399 E SQLiteDatabase: 	at com.samsung.android.game.GameManagerService$UninstallReceiver.onReceive(GameManagerService.java:512)
09-15 12:03:03.004  3399  3399 E SQLiteDatabase: 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:993)
09-15 12:03:03.004  3399  3399 E SQLiteDatabase: 	at android.os.Handler.handleCallback(Handler.java:739)
09-15 12:03:03.004  3399  3399 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:95)
09-15 12:03:03.004  3399  3399 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:158)
09-15 12:03:03.004  3399  3399 E SQLiteDatabase: 	at com.android.server.SystemServer.run(SystemServer.java:508)
09-15 12:03:03.004  3399  3399 E SQLiteDatabase: 	at com.android.server.SystemServer.main(SystemServer.java:363)
09-15 12:03:03.004  3399  3399 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Native Method)
09-15 12:03:03.004  3399  3399 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1230)
09-15 12:03:03.004  3399  3399 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1120)
09-15 12:03:03.004  3399  3399 D AndroidRuntime: Shutting down VM
09-15 12:03:03.004  3399  3399 E AndroidRuntime: *** FATAL EXCEPTION IN SYSTEM PROCESS: main
09-15 12:03:03.004  3399  3399 E AndroidRuntime: java.lang.RuntimeException: Error receiving broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 bqHint=4 VirtualScreenParam=Params{mDisplayId=-1, null, mFlags=0x00000000)} (has extras) } in com.samsung.android.game.GameManagerService$UninstallReceiver@6e9ff6f
09-15 12:03:03.004  3399  3399 E AndroidRuntime: 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:1003)
09-15 12:03:03.004  3399  3399 E AndroidRuntime: 	at android.os.Handler.handleCallback(Handler.java:739)
09-15 12:03:03.004  3399  3399 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:95)
09-15 12:03:03.004  3399  3399 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:158)
09-15 12:03:03.004  3399  3399 E AndroidRuntime: 	at com.android.server.SystemServer.run(SystemServer.java:508)
09-15 12:03:03.004  3399  3399 E AndroidRuntime: 	at com.android.server.SystemServer.main(SystemServer.java:363)
09-15 12:03:03.004  3399  3399 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
09-15 12:03:03.004  3399  3399 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1230)
09-15 12:03:03.004  3399  3399 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1120)
09-15 12:03:03.004  3399  3399 E AndroidRuntime: Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-15 12:03:03.004  3399  3399 E AndroidRuntime: #################################################################
09-15 12:03:03.004  3399  3399 E AndroidRuntime: Error Code : 0 (SQLITE_OK)
09-15 12:03:03.004  3399  3399 E AndroidRuntime: Caused By : not an error (code 0): Could not open the database in read/write mode.
09-15 12:03:03.004  3399  3399 E AndroidRuntime: #################################################################
09-15 12:03:03.004  3399  3399 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
09-15 12:03:03.004  3399  3399 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:283)
09-15 12:03:03.004  3399  3399 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:210)
09-15 12:03:03.004  3399  3399 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
09-15 12:03:03.004  3399  3399 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
09-15 12:03:03.004  3399  3399 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
09-15 12:03:03.004  3399  3399 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
09-15 12:03:03.004  3399  3399 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
09-15 12:03:03.004  3399  3399 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
09-15 12:03:03.004  3399  3399 E AndroidRuntime: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:633)
09-15 12:03:03.004  3399  3399 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
09-15 12:03:03.004  3399  3399 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
09-15 12:03:03.004  3399  3399 E AndroidRuntime: 	at com.samsung.android.game.data.DatabaseHelper.removeGame(DatabaseHelper.java:144)
09-15 12:03:03.004  3399  3399 E AndroidRuntime: 	at com.samsung.android.game.GameManagerService$UninstallReceiver.onReceive(GameManagerService.java:512)
09-15 12:03:03.004  3399  3399 E AndroidRuntime: 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:993)
09-15 12:03:03.004  3399  3399 E AndroidRuntime: 	... 8 more
09-15 12:03:03.004  3399  3527 D ResourcesManager: For user 0 new overlays fetched Null
09-15 12:03:03.004  3399  3527 W ResourcesManager: getTopLevelResources: /system/priv-app/SecMms_Epic_Common/SecMms_Epic_Common.apk / 1.0 running in null rsrc of package com.android.mms
09-15 12:03:03.004  3399  3527 W ResourcesManager: getTopLevelResources: /system/priv-app/SecMyFiles/SecMyFiles.apk / 1.0 running in null rsrc of package com.sec.android.app.myfiles
09-15 12:03:03.004  3399  3527 D ResourcesManager: For user 0 new overlays fetched Null
09-15 12:03:03.004  3399  3527 W ResourcesManager: getTopLevelResources: /system/priv-app/SecMyFiles/SecMyFiles.apk / 1.0 running in null rsrc of package com.sec.android.app.myfiles
09-15 12:03:03.004  3399  3527 W ResourcesManager: getTopLevelResources: /system/app/Music2/Music2.apk / 1.0 running in null rsrc of package com.google.android.music
09-15 12:03:03.004  3399  3527 W ResourcesManager: getTopLevelResources: /system/app/Music2/Music2.apk / 1.0 running in null rsrc of package com.google.android.music
09-15 12:03:03.004  3399  3527 W ResourcesManager: getTopLevelResources: /system/app/SecMemo3/SecMemo3.apk / 1.0 running in null rsrc of package com.samsung.android.app.memo
09-15 12:03:03.014  3006  3006 D libEGL  : eglInitialize EGLDisplay = 0x7fc83bb698
09-15 12:03:03.014  3399  3527 D ResourcesManager: For user 0 new overlays fetched Null
09-15 12:03:03.014  3399  3527 W ResourcesManager: getTopLevelResources: /system/app/SecMemo3/SecMemo3.apk / 1.0 running in null rsrc of package com.samsung.android.app.memo
09-15 12:03:03.014  3399  3527 W ResourcesManager: getTopLevelResources: /system/app/Weather2016/Weather2016.apk / 1.0 running in null rsrc of package com.samsung.android.weather
09-15 12:03:03.014  3399  3527 D ResourcesManager: For user 0 new overlays fetched Null
09-15 12:03:03.014  3399  3527 W ResourcesManager: getTopLevelResources: /system/app/Weather2016/Weather2016.apk / 1.0 running in null rsrc of package com.samsung.android.weather
09-15 12:03:03.014  3399  3527 W ResourcesManager: getTopLevelResources: /system/app/YouTube/YouTube.apk / 1.0 running in null rsrc of package com.google.android.youtube
09-15 12:03:03.024  3399  3399 E android.os.Debug: THIS IS SYSTEM_SERVER.. store dumpState!!
09-15 12:03:03.024  3399  3527 D ResourcesManager: For user 0 new overlays fetched Null
09-15 12:03:03.024  4307  4805 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
09-15 12:03:03.024  3399  3527 W ResourcesManager: getTopLevelResources: /system/app/YouTube/YouTube.apk / 1.0 running in null rsrc of package com.google.android.youtube
09-15 12:03:03.024  3399  3527 W ResourcesManager: getTopLevelResources: /system/priv-app/GmsCore/GmsCore.apk / 1.0 running in null rsrc of package com.google.android.gms
09-15 12:03:03.024  3399  3527 W ResourcesManager: getTopLevelResources: /system/priv-app/GmsCore/GmsCore.apk / 1.0 running in null rsrc of package com.google.android.gms
09-15 12:03:03.024  3399  3527 W ResourcesManager: getTopLevelResources: /system/priv-app/MyPlaces_Hero/MyPlaces_Hero.apk / 1.0 running in null rsrc of package com.sec.android.widgetapp.locationwidget
09-15 12:03:03.024  3399  3527 D ResourcesManager: For user 0 new overlays fetched Null
09-15 12:03:03.024  3399  3527 W ResourcesManager: getTopLevelResources: /system/priv-app/MyPlaces_Hero/MyPlaces_Hero.apk / 1.0 running in null rsrc of package com.sec.android.widgetapp.locationwidget
09-15 12:03:03.024  3399  3527 W ResourcesManager: getTopLevelResources: /system/priv-app/SecEmail_M/SecEmail_M.apk / 1.0 running in null rsrc of package com.samsung.android.email.provider
09-15 12:03:03.024  3399  3527 W ResourcesManager: getTopLevelResources: /system/priv-app/SecSettings2/SecSettings2.apk / 1.0 running in null rsrc of package com.android.settings
09-15 12:03:03.024  3399  3527 W ResourcesManager: getTopLevelResources: /system/priv-app/TouchWizHome_2016/TouchWizHome_2016.apk / 1.0 running in null rsrc of package com.sec.android.app.launcher
09-15 12:03:03.024  3399  3527 W ResourcesManager: getTopLevelResources: /system/app/Chrome/Chrome.apk / 1.0 running in null rsrc of package com.android.chrome
09-15 12:03:03.024  3399  3527 W ResourcesManager: getTopLevelResources: /system/app/Chrome/Chrome.apk / 1.0 running in null rsrc of package com.android.chrome
09-15 12:03:03.024  3399  3527 W ResourcesManager: getTopLevelResources: /system/app/Drive/Drive.apk / 1.0 running in null rsrc of package com.google.android.apps.docs
09-15 12:03:03.024  3399  3527 W ResourcesManager: getTopLevelResources: /system/app/Drive/Drive.apk / 1.0 running in null rsrc of package com.google.android.apps.docs
09-15 12:03:03.024  3399  3527 W ResourcesManager: getTopLevelResources: /system/app/Drive/Drive.apk / 1.0 running in null rsrc of package com.google.android.apps.docs
09-15 12:03:03.024  3399  3527 W ResourcesManager: getTopLevelResources: /system/app/OneDrive_Samsung_v2/OneDrive_Samsung_v2.apk / 1.0 running in null rsrc of package com.microsoft.skydrive
09-15 12:03:03.024  3399  3527 W ResourcesManager: getTopLevelResources: /system/app/OneDrive_Samsung_v2/OneDrive_Samsung_v2.apk / 1.0 running in null rsrc of package com.microsoft.skydrive
09-15 12:03:03.024  3399  3527 W ResourcesManager: getTopLevelResources: /system/app/SPlanner_M/SPlanner_M.apk / 1.0 running in null rsrc of package com.android.calendar
09-15 12:03:03.024  3399  3527 D ResourcesManager: For user 0 new overlays fetched Null
09-15 12:03:03.024  3399  3527 W ResourcesManager: getTopLevelResources: /system/app/SPlanner_M/SPlanner_M.apk / 1.0 running in null rsrc of package com.android.calendar
09-15 12:03:03.024  3399  3527 W ResourcesManager: getTopLevelResources: /system/app/SPlanner_M/SPlanner_M.apk / 1.0 running in null rsrc of package com.android.calendar
09-15 12:03:03.024  3399  3527 W ResourcesManager: getTopLevelResources: /system/app/Weather2016/Weather2016.apk / 1.0 running in null rsrc of package com.samsung.android.weather
09-15 12:03:03.024  3399  3527 W ResourcesManager: getTopLevelResources: /system/app/Weather2016/Weather2016.apk / 1.0 running in null rsrc of package com.samsung.android.weather
09-15 12:03:03.034  3399  3527 W ResourcesManager: getTopLevelResources: /system/app/YouTube/YouTube.apk / 1.0 running in null rsrc of package com.google.android.youtube
09-15 12:03:03.034  3399  3527 W ResourcesManager: getTopLevelResources: /system/priv-app/Velvet/Velvet.apk / 1.0 running in null rsrc of package com.google.android.googlequicksearchbox
09-15 12:03:03.034  3399  3527 W ResourcesManager: getTopLevelResources: /system/priv-app/Velvet/Velvet.apk / 1.0 running in null rsrc of package com.google.android.googlequicksearchbox
09-15 12:03:03.034  3399  3527 W ResourcesManager: getTopLevelResources: /system/priv-app/SecContacts_M/SecContacts_M.apk / 1.0 running in null rsrc of package com.android.contacts
09-15 12:03:03.034  3399  3527 W ResourcesManager: getTopLevelResources: /system/priv-app/SecGallery2015/SecGallery2015.apk / 1.0 running in null rsrc of package com.sec.android.gallery3d
09-15 12:03:03.034  5083  5301 D PresenceModule: onReceive: package removed
09-15 12:03:03.034  5083  5301 D PresenceModule: handleMessage: msg 50, Last Publish Info: null
09-15 12:03:03.034  5083  5301 D PresenceModule: Application package removed
09-15 12:03:03.034  5083  5301 D PresenceModule: onAppPkgRemoved: com.test.thalitest
09-15 12:03:03.034  5083  5301 D PresenceModule: onApplicationPackageRemoved: invalid package
09-15 12:03:03.034  3399  3527 D ResourcesManager: For user 0 new overlays fetched Null
09-15 12:03:03.034  3399  3527 W ResourcesManager: getTopLevelResources: /system/priv-app/SecGallery2015/SecGallery2015.apk / 1.0 running in null rsrc of package com.sec.android.gallery3d
09-15 12:03:03.034  3399  3527 W ResourcesManager: getTopLevelResources: /system/priv-app/SFinder_v4/SFinder_v4.apk / 1.0 running in null rsrc of package com.samsung.android.app.galaxyfinder
09-15 12:03:03.034  3399  3527 D ResourcesManager: For user 0 new overlays fetched Null
09-15 12:03:03.034  3399  3527 W ResourcesManager: getTopLevelResources: /system/priv-app/SFinder_v4/SFinder_v4.apk / 1.0 running in null rsrc of package com.samsung.android.app.galaxyfinder
09-15 12:03:03.034  3399  3527 W ResourcesManager: getTopLevelResources: /system/priv-app/SFinder_v4/SFinder_v4.apk / 1.0 running in null rsrc of package com.samsung.android.app.galaxyfinder
09-15 12:03:03.034  3399  3527 W ResourcesManager: getTopLevelResources: /system/priv-app/VoiceNote_4.0/VoiceNote_4.0.apk / 1.0 running in null rsrc of package com.sec.android.app.voicenote
09-15 12:03:03.034  3399  3527 D ResourcesManager: For user 0 new overlays fetched Null
09-15 12:03:03.034  3399  3527 W ResourcesManager: getTopLevelResources: /system/priv-app/VoiceNote_4.0/VoiceNote_4.0.apk / 1.0 running in null rsrc of package com.sec.android.app.voicenote
09-15 12:03:03.034  3399  3527 W ResourcesManager: getTopLevelResources: /system/priv-app/VoiceNote_4.0/VoiceNote_4.0.apk / 1.0 running in null rsrc of package com.sec.android.app.voicenote
09-15 12:03:03.034  3399  3527 W ResourcesManager: getTopLevelResources: /system/app/SBrowser_4_LATEST/SBrowser_4_LATEST.apk / 1.0 running in null rsrc of package com.sec.android.app.sbrowser
09-15 12:03:03.034  3399  3527 W ResourcesManager: getTopLevelResources: /system/app/SBrowser_4_LATEST/SBrowser_4_LATEST.apk / 1.0 running in null rsrc of package com.sec.android.app.sbrowser
,09-15 12:03:03.044  3399  4235 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{ee01358 u0 com.android.launcher.action.HOME_MODE_CHANGE qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{d423460 9282:com.sec.android.app.clockpackage/u0a88}
09-15 12:03:03.054  4267  4267 D CarrierServiceBindHelper: Receive action: android.intent.action.PACKAGE_REMOVED
09-15 12:03:03.054  3399  3562 D KnoxTimeoutHandler: notifyActivityDrawn [MsgParam] userId: 0 fullscreen is true showWhenlocked is false
09-15 12:03:03.054  4017  4017 I Recents_MultiWindowAppListInfo: android.intent.action.PACKAGE_REMOVE
09-15 12:03:03.054  3399  3562 D ActivityManager: mDVFSHelper.release()
09-15 12:03:03.054  3399  3562 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{866f6c5 u0 com.sec.android.app.launcher/.activities.LauncherActivity t6} time:185483
09-15 12:03:03.054  3399  3562 W ResourcesManager: getTopLevelResources: /system/priv-app/InputDevices/InputDevices.apk / 1.0 running in null rsrc of package com.android.inputdevices
09-15 12:03:03.054  3399  3527 W ResourcesManager: getTopLevelResources: /system/priv-app/LiveBroadcast/LiveBroadcast.apk / 1.0 running in null rsrc of package com.sec.android.app.camera.plb
09-15 12:03:03.054  3399  3527 W ResourcesManager: getTopLevelResources: /system/priv-app/LiveBroadcast/LiveBroadcast.apk / 1.0 running in null rsrc of package com.sec.android.app.camera.plb
09-15 12:03:03.054  3399  3527 W ResourcesManager: getTopLevelResources: /system/priv-app/LiveBroadcast/LiveBroadcast.apk / 1.0 running in null rsrc of package com.sec.android.app.camera.plb
09-15 12:03:03.054  3399  3527 W ResourcesManager: getTopLevelResources: /system/priv-app/SFinder_v4/SFinder_v4.apk / 1.0 running in null rsrc of package com.samsung.android.app.galaxyfinder
09-15 12:03:03.054  4280  4280 V ActivityThread: updateVisibility : ActivityRecord{23143fd token=android.os.BinderProxy@898930d {com.sec.android.app.launcher/com.sec.android.app.launcher.activities.LauncherActivity}} show : true
09-15 12:03:03.054  3399  3562 D ResourcesManager: For user 0 new overlays fetched Null
09-15 12:03:03.054  4280  4280 D Launcher.HomeView: onStop
09-15 12:03:03.054  4280  4280 D capture : ----destroy
09-15 12:03:03.054  3399  3527 W ResourcesManager: getTopLevelResources: /system/priv-app/SamsungCamera5/SamsungCamera5.apk / 1.0 running in null rsrc of package com.sec.android.app.camera
09-15 12:03:03.054  3399  3562 W ResourcesManager: getTopLevelResources: /system/priv-app/InputDevices/InputDevices.apk / 1.0 running in null rsrc of package com.android.inputdevices
09-15 12:03:03.054  3399  3527 W ResourcesManager: getTopLevelResources: /system/priv-app/SamsungCamera5/SamsungCamera5.apk / 1.0 running in null rsrc of package com.sec.android.app.camera
09-15 12:03:03.064  3399  3527 W ResourcesManager: getTopLevelResources: /system/priv-app/SecContacts_M/SecContacts_M.apk / 1.0 running in null rsrc of package com.android.contacts
09-15 12:03:03.064  3399  3828 I InputReader: Reconfiguring input devices.  changes=0x00000010
09-15 12:03:03.064  3399  3527 W ResourcesManager: getTopLevelResources: /system/priv-app/SecContacts_M/SecContacts_M.apk / 1.0 running in null rsrc of package com.android.contacts
09-15 12:03:03.074  3399  3876 D MdnieScenarioControlService:  packageName : com.sec.android.app.launcher    className : com.sec.android.app.launcher.activities.LauncherActivity
09-15 12:03:03.074  3399  3876 I MdnieScenarioControlService: mGameModeLauncher : false
09-15 12:03:03.074  3399  3876 I MdnieScenarioControlService: setUIMode
09-15 12:03:03.074  3399  3527 W ResourcesManager: getTopLevelResources: /system/priv-app/SecContacts_M/SecContacts_M.apk / 1.0 running in null rsrc of package com.android.contacts
09-15 12:03:03.074  3399  4279 W ActivityManager: Permission Denial: Accessing service ComponentInfo{com.google.android.music/com.google.android.music.dial.DialMediaRouteProviderService} from pid=4830, uid=10124 that is not exported from uid 10122
09-15 12:03:03.074  3399  3527 W ResourcesManager: getTopLevelResources: /system/priv-app/SecContacts_M/SecContacts_M.apk / 1.0 running in null rsrc of package com.android.contacts
09-15 12:03:03.074  3399  3902 W System.err: remove failed: EROFS (Read-only file system) : /data/system/recent_tasks/10_task.xml
09-15 12:03:03.084  3399  3902 W System.err: remove failed: EROFS (Read-only file system) : /data/system/recent_images/10_task_thumbnail.png
,09-15 12:03:03.084  3399  3527 W ResourcesManager: getTopLevelResources: /system/priv-app/SecEmail_M/SecEmail_M.apk / 1.0 running in null rsrc of package com.samsung.android.email.provider
,09-15 12:03:03.084  3399  3527 W ResourcesManager: getTopLevelResources: /system/priv-app/SecGallery2015/SecGallery2015.apk / 1.0 running in null rsrc of package com.sec.android.gallery3d

```
