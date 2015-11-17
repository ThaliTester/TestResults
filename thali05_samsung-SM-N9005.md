#### Test 503880196ac79ce_thali05_samsung-SM-N9005 Logs


```--------- beginning of main
11-17 18:30:47.106   360   360 I ServiceManager: Waiting for service AtCmdFwd...
,--------- beginning of system
11-17 18:30:47.346   756  2861 D SSRM:a  : DeviceInfo:: 000000100000
11-17 18:30:47.346   756  2861 D SSRM:a  : SettingsAirViewInfo:: 010100000
11-17 18:30:47.496  6119  6119 D AndroidRuntime: 
11-17 18:30:47.496  6119  6119 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
11-17 18:30:47.496  6119  6119 D AndroidRuntime: CheckJNI is OFF
11-17 18:30:47.506  6119  6119 D AndroidRuntime: readGMSProperty: start
11-17 18:30:47.506  6119  6119 D AndroidRuntime: readGMSProperty: already setted!!
11-17 18:30:47.506  6119  6119 D AndroidRuntime: readGMSProperty: end
11-17 18:30:47.506  6119  6119 D AndroidRuntime: addProductProperty: start
11-17 18:30:47.666  6119  6119 E AffinityControl: AffinityControl: registerfunction enter
11-17 18:30:47.676  6119  6119 D AndroidRuntime: Calling main entry com.android.commands.am.Am
11-17 18:30:47.686   756   772 E PersonaManagerService: inState():  stateMachine is null !!
11-17 18:30:47.686   756   772 I PersonaManagerService: PersonaId don't exist
11-17 18:30:47.686   756   772 I ActivityManager: do not start freezing screen for locked container getKeyguardshowstate = false
11-17 18:30:47.686   756   772 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.example.hello
11-17 18:30:47.686   756   772 I ActivityManager: START u0 {flg=0x10000000 cmp=com.example.hello/.MainActivity} from uid 2000 on display 0
11-17 18:30:47.686   756   772 D ResourcesManager: creating new AssetManager and set to /data/app/com.example.hello-1/base.apk
11-17 18:30:47.696   756   772 D CustomFrequencyManagerService: acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1958400  uid : 1000  pid : 756  pkgName : ACTIVITY_RESUME_BOOSTER@7
11-17 18:30:47.696   756   772 W ActivityManager: mDVFSHelper.acquire()
11-17 18:30:47.696   254   254 I SurfaceFlinger: id=10 createSurf (16x16),-1 flag=20004, EimLayer
11-17 18:30:47.696   254   254 I SurfaceFlinger: id=11 createSurf (16x16),-1 flag=20004, EimLayer
11-17 18:30:47.706   756   772 D FocusedStackFrame: Set to : 0
11-17 18:30:47.706   756  1168 D PowerManagerService: [input device light] handleInputDeviceLightOff
11-17 18:30:47.706   756  1168 D lights  : button : 0 +
11-17 18:30:47.716  1437  1437 D Launcher.HomeView: onPause
11-17 18:30:47.716  1437  1437 D Launcher: Launcher::setSystemUiTransparency(): getSystemUiVisibility() after setting  = 40000000
11-17 18:30:47.716  6119  6119 D AndroidRuntime: Shutting down VM
11-17 18:30:47.716  5566  5566 V TaskCloserActivity: TaskCloserActivity onReceive() - com.sec.android.intent.action.HOME_PAUSE
11-17 18:30:47.726   756  1052 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
11-17 18:30:47.726   756   771 E ActivityManager: checkUser: useridlist=null, currentuser=0
11-17 18:30:47.726   756  1052 D PointerIcon: setMouseCustomIcon IconType is same.101
11-17 18:30:47.726   756   771 E ActivityManager: checkUser: useridlist=null, currentuser=0
11-17 18:30:47.726   756  1052 D PointerIcon: setHoveringSpenIconStyle1 pointerType: 10001iconType:1 flag:0
11-17 18:30:47.726   756   771 E ActivityManager: checkUser: useridlist=null, currentuser=0
11-17 18:30:47.726   756  1052 D PointerIcon: setHoveringSpenCustomIcon IconType is same.1
11-17 18:30:47.726   756   771 E ActivityManager: checkUser: useridlist=null, currentuser=0
11-17 18:30:47.726   254   254 I SurfaceFlinger: id=12 createSurf (1x1),1 flag=404, iello
11-17 18:30:47.746   756  1168 D lights  : button : 0 -
11-17 18:30:47.746  6145  6145 E Zygote  : MountEmulatedStorage()
11-17 18:30:47.746  6145  6145 E Zygote  : v2
11-17 18:30:47.746  6145  6145 I libpersona: KNOX_SDCARD checking this for 10232
11-17 18:30:47.746  6145  6145 I libpersona: KNOX_SDCARD not a persona
11-17 18:30:47.756   756   771 I ActivityManager: Start proc com.example.hello for activity com.example.hello/.MainActivity: pid=6145 uid=10232 gids={50232, 9997, 3003, 3001, 3002} abi=armeabi-v7a
11-17 18:30:47.766  6145  6145 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0 ver=27
11-17 18:30:47.766  6145  6145 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N9005_5.0_0027
11-17 18:30:47.766  6145  6145 E SELinux : [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
11-17 18:30:47.766   756  1046 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
11-17 18:30:47.786  1437  1437 V ActivityThread: updateVisibility : ActivityRecord{e699cf9 token=android.os.BinderProxy@12e7d275 {com.sec.android.app.launcher/com.android.launcher2.Launcher}} show : true
11-17 18:30:47.786  1622  1927 I MicrophoneInputStream: mic_close gfk@1ef678ab
11-17 18:30:47.796   299   299 V AudioPolicyManager: stopInput() input 14
11-17 18:30:47.796   299   687 V AudioPolicyManager: releaseInput() 14
11-17 18:30:47.796   299   687 V AudioPolicyManager: closeInput(14)
11-17 18:30:47.796  1622  1972 I HotwordRecognitionRnr: Stopping hotword detection.
11-17 18:30:47.796  1622  6063 I HotwordRecognitionRnr: Hotword detection finished
11-17 18:30:47.796   299  6065 V audio_hw_primary: in_standby: enter
11-17 18:30:47.816  6145  6145 D TimaKeyStoreProvider: TimaSignature is unavailable
11-17 18:30:47.816  6145  6145 D ActivityThread: Added TimaKeyStore provider
11-17 18:30:47.816   756  1707 V WindowOrientationListener: mSContextAutoRotationListener.getProposedRotation, mbResultFaceDectection: false
11-17 18:30:47.816   756  1707 V WindowOrientationListener: mSContextAutoRotationListener.getProposedRotation, Rotation: -1
11-17 18:30:47.816   756  1707 V WindowManager: rotationForOrientationLw(orient=-1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false
11-17 18:30:47.816   756  1707 V WindowOrientationListener: mSContextAutoRotationListener.getProposedRotation, mbResultFaceDectection: false
11-17 18:30:47.816   756  1707 V WindowOrientationListener: mSContextAutoRotationListener.getProposedRotation, Rotation: -1
11-17 18:30:47.816   756   756 V ActivityManager: Display changed displayId=0
11-17 18:30:47.826  1437  1437 D Launcher.HomeView: onStop
11-17 18:30:47.826  1771  1780 D SurfaceWidgetClient$ISurfaceWidgetStub: [237392/8] Surface widget pause on instance = 1
11-17 18:30:47.826  1771  1771 D accuweather: [Accuweather J]>>> SWW:212 [0:0] [SWW] onPause : rI = 1
11-17 18:30:47.826  1437  1437 V ActivityThread: updateVisibility : ActivityRecord{e699cf9 token=android.os.BinderProxy@12e7d275 {com.sec.android.app.launcher/com.android.launcher2.Launcher}} show : false
11-17 18:30:47.826  1771  1771 D accuweather: [Accuweather J]>>> SWW:222 [0:0] [SWW] onPause : size = 0
11-17 18:30:47.826  1771  1780 D SurfaceWidgetClient$ISurfaceWidgetStub: [237392/8] Surface widget visibility changed visibility = false on instance = 1
11-17 18:30:47.836  1771  1771 D accuweather: [Accuweather J]>>> SWW:634 [0:0]  unRegisterTTReceiver !! 
11-17 18:30:47.836  1437  1437 D SurfaceWidgetView: destroyHardwareResources():904848728
11-17 18:30:47.836   756  2873 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
11-17 18:30:47.846   299  6065 V audio_hw_primary: stop_input_stream: enter: usecase(7: audio-record)
11-17 18:30:47.846   299  6065 V audio_hw_primary: disable_audio_route: enter: usecase(7)
11-17 18:30:47.846   299  6065 V audio_hw_primary: disable_audio_route: reset mixer path: audio-record
11-17 18:30:47.846   299  6065 D audio_route: ++++ audio_route_update_mixer ==============
11-17 18:30:47.846   299  6065 D audio_route: Setting mixer control: MultiMedia1 Mixer SLIM_0_TX
11-17 18:30:47.846   299  6065 D audio_route: Setting mixer control: value: 0
11-17 18:30:47.846   299  6065 D audio_route: ------ audio_route_update_mixer ==============
11-17 18:30:47.846   299  6065 V audio_hw_primary: disable_audio_route: exit
11-17 18:30:47.846   299  6065 V audio_hw_primary: disable_snd_device: snd_device(128: vr-main-mic)
11-17 18:30:47.846   299  6065 D audio_route: ++++ audio_route_update_mixer ==============
11-17 18:30:47.846   299  6065 D audio_route: Setting mixer control: ADC1 Volume
11-17 18:30:47.846   299  6065 D audio_route: Setting mixer control: value: 0
11-17 18:30:47.846   299  6065 D audio_route: Setting mixer control: DEC6 Volume
11-17 18:30:47.846   299  6065 D audio_route: Setting mixer control: value: 0
11-17 18:30:47.846   299  6065 D audio_route: Setting mixer control: SLIM TX7 MUX, value: 0
11-17 18:30:47.846   299  6065 D audio_route: Setting mixer control: AIF1_CAP Mixer SLIM TX7
11-17 18:30:47.846   299  6065 D audio_route: Setting mixer control: value: 0
11-17 18:30:47.846   299  6065 D audio_route: Setting mixer control: DEC6 MUX, value: 0
11-17 18:30:47.846   299  6065 D audio_route: ------ audio_route_update_mixer ==============
11-17 18:30:47.846   299  6065 V audio_hw_primary: stop_input_stream: exit: status(0)
11-17 18:30:47.846   299  6065 V audio_hw_primary: in_standby: exit:  status(0)
11-17 18:30:47.846   299   687 V audio_hw_primary: adev_close_input_stream
11-17 18:30:47.846   299   687 V audio_hw_primary: in_standby: enter
11-17 18:30:47.846   299   687 V audio_hw_primary: in_standby: exit:  status(0)
11-17 18:30:47.846   299   687 E audio_hw_primary: adev_close_input_stream, set jack_in to null
11-17 18:30:47.846   299   687 V AudioPolicyManager: releaseInput() exit
11-17 18:30:47.856   756  1046 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
11-17 18:30:47.856   756  2861 D ConnectivityService: returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
11-17 18:30:47.856  1771  1771 D accuweather: [Accuweather J]>>> WCD:1431 [0:0] cARH()
11-17 18:30:47.856  1771  1771 D accuweather: [Accuweather J]>>> WCD:549 [0:0]  onPause 
11-17 18:30:47.856  1771  1771 D accuweather: [Accuweather J]>>> WR:475 [0:0] onPause : 1
11-17 18:30:47.856  1771  1771 D accuweather: [Accuweather J]>>> SWW:540 [0:0] =================== , pause :1
11-17 18:30:47.866  6145  6145 D ResourcesManager: creating new AssetManager and set to /data/app/com.example.hello-1/base.apk
11-17 18:30:47.886  1437  1437 D Launcher: onTrimMemory. Level: 20
11-17 18:30:47.886  1437  1437 D SurfaceWidgetView: destroyHardwareResources():904848728
11-17 18:30:47.956  6145  6145 I WebViewFactory: Loading com.google.android.webview version 37 (1589900-arm) (code 110601)
11-17 18:30:47.956  6145  6145 D ResourcesManager: creating new AssetManager and set to /system/app/WebViewGoogle/WebViewGoogle.apk
11-17 18:30:47.966  6145  6145 I LibraryLoader: Loading: webviewchromium
11-17 18:30:47.976  6145  6145 I LibraryLoader: Time to load native libraries: 5 ms (timestamps 1346-1351)
11-17 18:30:47.976  6145  6145 I LibraryLoader: Expected native library version number "",actual native library version number ""
11-17 18:30:47.996  6145  6145 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {32a8337d}
11-17 18:30:47.996  6145  6145 I LibraryLoader: Expected native library version number "",actual native library version number ""
11-17 18:30:47.996  6145  6145 I chromium: [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
11-17 18:30:48.006  6145  6145 I BrowserStartupController: Initializing chromium process, renderers=0
11-17 18:30:48.016  6145  6145 W art     : Attempt to remove local handle scope entry from IRT, ignoring
11-17 18:30:48.016  6145  6162 W chromium: [WARNING:dns_config_service_posix.cc(293)] Failed to read DnsConfig.
11-17 18:30:48.026  6145  6145 W chromium: [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
11-17 18:30:48.026  6145  6145 I chromium: [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=35 off=46780 len=2953
11-17 18:30:48.026  6145  6145 I chromium: [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:36 off:229536 len:643667
11-17 18:30:48.036  6145  6166 D BluetoothAdapter: 553398898: getState() :  mService = null. Returning STATE_OFF
11-17 18:30:48.046  6145  6145 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1_RB1.05.00.00.002.025_msm8974_LA.BF.1.1_RB1__release_AU ()
11-17 18:30:48.046  6145  6145 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.01.03
11-17 18:30:48.046  6145  6145 I Adreno-EGL: Build Date: 11/19/14 Wed
11-17 18:30:48.046  6145  6145 I Adreno-EGL: Local Branch: mybranch5813579
11-17 18:30:48.046  6145  6145 I Adreno-EGL: Remote Branch: quic/LA.BF.1.1_rb1.11
11-17 18:30:48.046  6145  6145 I Adreno-EGL: Local Patches: NONE
11-17 18:30:48.046  6145  6145 I Adreno-EGL: Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1_RB1.05.00.00.002.025 + 30e7589 +  NOTHING
11-17 18:30:48.106   360   360 I ServiceManager: Waiting for service AtCmdFwd...
11-17 18:30:48.116  6145  6172 W chromium: [WARNING:proxy_service.cc(901)] PAC support disabled because there is no system implementation
11-17 18:30:48.126  6145  6145 W chromium: [WARNING:data_reduction_proxy_settings.cc(403)] SPDY proxy OFF at startup
11-17 18:30:48.146  6145  6145 W art     : Attempt to remove local handle scope entry from IRT, ignoring
11-17 18:30:48.146  6145  6145 W AwContents: onDetachedFromWindow called when already detached. Ignoring
11-17 18:30:48.156  6145  6145 D SystemWebViewEngine: CordovaWebView is running on device made by: samsung
11-17 18:30:48.156  6145  6145 W art     : Attempt to remove local handle scope entry from IRT, ignoring
11-17 18:30:48.156  6145  6145 W art     : Attempt to remove local handle scope entry from IRT, ignoring
11-17 18:30:48.186  6145  6145 D Activity: performCreate Call secproduct feature valuefalse
11-17 18:30:48.186  6145  6145 D Activity: performCreate Call debug elastic valuetrue
11-17 18:30:48.196  6145  6185 D OpenGLRenderer: Render dirty regions requested: true
11-17 18:30:48.206  6145  6145 D Atlas   : Validating map...
11-17 18:30:48.206   756   772 D ActivityManager: post active user change for 0
11-17 18:30:48.206   756   772 D KnoxTimeoutHandler: postActiveUserChange for user 0
11-17 18:30:48.206   756   756 D KnoxTimeoutHandler: handleActiveUserChange for user 0
11-17 18:30:48.226   254   254 I SurfaceFlinger: id=13 createSurf (1x1),1 flag=404, NainActivit
11-17 18:30:48.236   756  1052 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
11-17 18:30:48.236   756  1052 D PointerIcon: setMouseCustomIcon IconType is same.101
11-17 18:30:48.236   756  1052 D PointerIcon: setHoveringSpenIconStyle1 pointerType: 10001iconType:1 flag:0
11-17 18:30:48.236   756  1052 D PointerIcon: setHoveringSpenCustomIcon IconType is same.1
11-17 18:30:48.236  6145  6185 I OpenGLRenderer: Initialized EGL, version 1.4
11-17 18:30:48.246  6145  6185 I OpenGLRenderer: HWUI protection enabled for context ,  &this =0xa1853060 ,&mEglDisplay = 1 , &mEglConfig = 8 
11-17 18:30:48.246  6145  6185 D OpenGLRenderer: Enabling debug mode 0
11-17 18:30:48.276   756  1451 D InputMethodManagerService: windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
11-17 18:30:48.276   756  6191 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.android.server.InputMethodManagerService$6.run:2733 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
11-17 18:30:48.286  1713  1713 I SamsungIME: getCurrentCandidateView
11-17 18:30:48.286   756  1052 I ActivityManager: Displayed com.example.hello/.MainActivity: +569ms
11-17 18:30:48.296  6145  6145 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@2391f5ed time:81673
11-17 18:30:48.296   756  6195 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.android.server.InputMethodManagerService$6.run:2733 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
11-17 18:30:48.336   254  1059 I SurfaceFlinger: id=6 Removed Mauncher (4/10)
11-17 18:30:48.336   254   328 I SurfaceFlinger: id=6 Removed Mauncher (-2/10)
11-17 18:30:48.356  1713  1713 D SamsungIME: Dismiss ExpandCandiate
11-17 18:30:48.366  6145  6145 I chromium: [INFO:CONSOLE(10)] "The key "target-densitydpi" is not supported.", source: file:///android_asset/www/index.html (10)
11-17 18:30:48.366  6145  6178 E AndroidProtocolHandler: Unable to open asset URL: file:///android_asset/www/jxcore.js
11-17 18:30:48.416  6145  6145 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
11-17 18:30:48.436  6145  6145 I chromium: [INFO:SkUtilsArm.cpp(179)] Device supports ARM NEON instructions!
11-17 18:30:48.436  6145  6145 I chromium: 
11-17 18:30:48.456  1713  1713 I SamsungIME: getDebugLevel  : 0x4f4c
11-17 18:30:48.486  1713  1713 I SamsungIME: getDebugLevel  : 0x4f4c
11-17 18:30:48.496  1713  1713 I SamsungIME: KeybaordView init() : load resources
11-17 18:30:48.506   254  1059 I SurfaceFlinger: id=12 Removed iello (7/9)
11-17 18:30:48.506   254  1923 I SurfaceFlinger: id=12 Removed iello (-2/9)
11-17 18:30:48.516  1713  1713 I SamsungIME: getCurrentKeyboard
11-17 18:30:48.516  1713  1713 I SamsungIME: getTextKeyboard
11-17 18:30:48.526  6145  6200 D jxcore_app_log: JniHelper::setJavaVM(0xb4f5c280), pthread_self() = -1357020160
11-17 18:30:48.526  6145  6200 D JX-Cordova: jxcore cordova android initializing
11-17 18:30:48.536  1713  1713 D SamsungIME: [SwiftkeyWrapper] currentLangauge : 1701729619
11-17 18:30:48.576  6145  6145 W jxcore-log: Initializing JXcore engine
11-17 18:30:48.576  6145  6145 W jxcore-log: JXcore engine is ready
11-17 18:30:48.586  6145  6145 W jxcore-log: Starting JXcore engine
11-17 18:30:48.606   756  1052 D CustomFrequencyManagerService: releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1958400  uid : 1000  pid : 756  tag : ACTIVITY_RESUME_BOOSTER@7
11-17 18:30:48.606   756   900 D CustomFrequencyManagerService: acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1958400  uid : 1000  pid : 756  pkgName : ACTIVITY_RESUME_BOOSTER@11
11-17 18:30:48.606   756  1052 W ActivityManager: mDVFSHelper.release()
11-17 18:30:48.606   756  1052 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{4ca246 u0 com.example.hello/.MainActivity t2} time:81985
11-17 18:30:48.646  1800  1800 E auditd  : In denial and Property audit_ondenial is set to 1 
11-17 18:30:48.646   756  1019 D SecurityLogAgent:SEDenialService: Got Modify Event and sending Denial Intent foraudit.log
11-17 18:30:48.646   756  1019 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.android.server.SEDenialService$AuditFileObserver.onEvent:76 android.os.FileObserver$ObserverThread.onEvent:122 android.os.FileObserver$ObserverThread.observe:-2 android.os.FileObserver$ObserverThread.run:85 
11-17 18:30:48.646   756  1019 D SecurityLogAgent:SEDenialService: audit.ondenial set to 0 after sending android.intent.action.DENIAL_NOTIFICATION intent
11-17 18:30:48.646   756   900 E ActivityManager: checkUser: useridlist=null, currentuser=0
11-17 18:30:48.646   756   900 E ActivityManager: checkUser: useridlist=null, currentuser=0
11-17 18:30:48.646   756   900 E ActivityManager: checkUser: useridlist=null, currentuser=0
11-17 18:30:48.646   756   900 E ActivityManager: checkUser: useridlist=null, currentuser=0
11-17 18:30:48.676  6204  6204 E Zygote  : MountEmulatedStorage()
11-17 18:30:48.676  6204  6204 E Zygote  : v2
11-17 18:30:48.676  6204  6204 I libpersona: KNOX_SDCARD checking this for 1000
11-17 18:30:48.676  6204  6204 I libpersona: KNOX_SDCARD not a persona
11-17 18:30:48.686   756   900 I ActivityManager: Start proc com.samsung.android.securitylogagent for broadcast com.samsung.android.securitylogagent/.receivers.SeDenialReceiver: pid=6204 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1007, 1028, 1015, 1023, 2001, 1024, 1001} abi=armeabi-v7a
11-17 18:30:48.706   337   337 I art     : Explicit concurrent mark sweep GC freed 8747(372KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 15MB/25MB, paused 308us total 13.491ms
,11-17 18:30:48.716   337   337 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 15MB/25MB, paused 269us total 9.847ms
11-17 18:30:48.716  6204  6204 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0 ver=27
11-17 18:30:48.716  6204  6204 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N9005_5.0_0027
11-17 18:30:48.716  6204  6204 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
11-17 18:30:48.726   337   337 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 15MB/25MB, paused 287us total 9.819ms
11-17 18:30:48.746  6145  6145 W jxcore-log: Platform android
11-17 18:30:48.746  6145  6145 W jxcore-log: 
11-17 18:30:48.746  6145  6145 W jxcore-log: Process ARCH arm
11-17 18:30:48.746  6145  6145 W jxcore-log: 
11-17 18:30:48.746  6204  6204 D TimaKeyStoreProvider: TimaSignature is unavailable
11-17 18:30:48.746  6204  6204 D ActivityThread: Added TimaKeyStore provider
11-17 18:30:48.766  6204  6204 D ResourcesManager: creating new AssetManager and set to /system/app/SecurityLogAgent/SecurityLogAgent.apk
11-17 18:30:48.776  6204  6204 D SecurityLogAgent:  SeDenialReceiver : Intent Received : android.intent.action.DENIAL_NOTIFICATION
11-17 18:30:48.776  6204  6204 D SecurityLogAgent:  SeDenialReceiver : File path = null
11-17 18:30:48.776   756  1451 I ActivityManager: Killing 5211:com.sec.android.diagmonagent/1000 (adj 15): bgCount ##41
11-17 18:30:48.786  6145  6145 I jxcore-log: JXcore Cordova bridge is ready!
11-17 18:30:48.786  6145  6145 I jxcore-log: 
11-17 18:30:48.786  6145  6145 W jxcore-log: JXcore engine is started
11-17 18:30:48.896   756  1233 I ActivityManager: Killing 4397:com.android.providers.calendar/u0a51 (adj 15): bgCount ##41
11-17 18:30:48.896   251   251 E lowmemorykiller: Error writing /proc/4397/oom_score_adj; errno=22
11-17 18:30:48.906  6145  6145 E jxcore-log: >> samsung-SM-N9005
11-17 18:30:48.906  6145  6145 E jxcore-log: 
11-17 18:30:48.906  6145  6145 I jxcore-log: Total memory 2971471872
11-17 18:30:48.906  6145  6145 I jxcore-log: 
11-17 18:30:48.906  6145  6145 I jxcore-log: Free memory 417538048
11-17 18:30:48.906  6145  6145 I jxcore-log: 
11-17 18:30:48.906  6145  6145 I jxcore-log: execPath /data/data/com.example.hello/files/www/jxcore
11-17 18:30:48.906  6145  6145 I jxcore-log: 
11-17 18:30:48.906  6145  6145 I jxcore-log: process.cwd /data/data/com.example.hello/files/www/jxcore
11-17 18:30:48.906  6145  6145 I jxcore-log: 
11-17 18:30:48.906   756   756 D CustomFrequencyManagerService: releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1958400  uid : 1000  pid : 756  tag : ACTIVITY_RESUME_BOOSTER@11
11-17 18:30:48.916  6145  6145 I jxcore-log: userPath [ 'rList-com.example.hello.MainActivity', 'www' ]
11-17 18:30:48.916  6145  6145 I jxcore-log: 
11-17 18:30:48.916  6145  6145 I jxcore-log: Size 1080 1920
11-17 18:30:48.916  6145  6145 I jxcore-log: 
11-17 18:30:48.916  6145  6145 I jxcore-log: Screen Brightness 162
11-17 18:30:48.916  6145  6145 I jxcore-log: 
11-17 18:30:48.916  6145  6145 E jxcore-log: Dummy Error Log.
11-17 18:30:48.916  6145  6145 E jxcore-log: 
11-17 18:30:48.966  1713  6201 D SamsungIME: [SwiftkeyWrapper] currentLangauge : 1701729619
11-17 18:30:49.106   360   360 I ServiceManager: Waiting for service AtCmdFwd...
,11-17 18:30:49.386   756  1055 D AutomaticBrightnessController: mCallbacks.updateBrightness()
,11-17 18:30:49.396   756  1055 D DisplayPowerController: getFinalBrightness : 10 -> 10
,11-17 18:30:49.396   756  1055 D DisplayPowerController: animation target = 10, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,11-17 18:30:49.446   756  1055 D AutomaticBrightnessController: mCallbacks.updateBrightness()
,11-17 18:30:49.456   756  1055 D DisplayPowerController: getFinalBrightness : 10 -> 10
,11-17 18:30:49.456   756  1055 D DisplayPowerController: animation target = 10, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,11-17 18:30:49.506  6145  6145 I jxcore-log: getBuffer is called!!!!
11-17 18:30:49.506  6145  6145 I jxcore-log: 
,11-17 18:30:49.626   756  1055 D AutomaticBrightnessController: mCallbacks.updateBrightness()
,11-17 18:30:49.626   756  1055 D DisplayPowerController: getFinalBrightness : 10 -> 10
11-17 18:30:49.626   756  1055 D DisplayPowerController: animation target = 10, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,11-17 18:30:49.786   294   294 E SMD     : DCD ON
,11-17 18:30:49.806   756  1055 D AutomaticBrightnessController: mCallbacks.updateBrightness()
,11-17 18:30:49.806   756  1055 D DisplayPowerController: getFinalBrightness : 10 -> 10
11-17 18:30:49.806   756  1055 D DisplayPowerController: animation target = 10, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,11-17 18:30:49.986   756  1055 D AutomaticBrightnessController: mCallbacks.updateBrightness()
,11-17 18:30:49.986   756  1055 D DisplayPowerController: getFinalBrightness : 10 -> 10
11-17 18:30:49.986   756  1055 D DisplayPowerController: animation target = 10, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,11-17 18:30:50.106   360   360 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 5
,11-17 18:30:50.166   756  1055 D AutomaticBrightnessController: mCallbacks.updateBrightness()
,11-17 18:30:50.166   756  1055 D DisplayPowerController: getFinalBrightness : 10 -> 10
,11-17 18:30:50.166   756  1055 D DisplayPowerController: animation target = 10, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,11-17 18:30:50.346   756  1055 D AutomaticBrightnessController: mCallbacks.updateBrightness()
,11-17 18:30:50.346   756  1055 D DisplayPowerController: getFinalBrightness : 10 -> 10
,11-17 18:30:50.346   756  1055 D DisplayPowerController: animation target = 10, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,11-17 18:30:50.526   756  1055 D AutomaticBrightnessController: mCallbacks.updateBrightness()
,11-17 18:30:50.526   756  1055 D DisplayPowerController: getFinalBrightness : 10 -> 10
,11-17 18:30:50.526   756  1055 D DisplayPowerController: animation target = 10, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,11-17 18:30:50.706   756  1055 D AutomaticBrightnessController: mCallbacks.updateBrightness()
,11-17 18:30:50.706   756  1055 D DisplayPowerController: getFinalBrightness : 10 -> 10
,11-17 18:30:50.706   756  1055 D DisplayPowerController: animation target = 10, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,11-17 18:30:50.886   756  1055 D AutomaticBrightnessController: mCallbacks.updateBrightness()
,11-17 18:30:50.886   756  1055 D DisplayPowerController: getFinalBrightness : 10 -> 10
,11-17 18:30:50.886   756  1055 D DisplayPowerController: animation target = 10, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,11-17 18:30:51.066   756  1055 D AutomaticBrightnessController: mCallbacks.updateBrightness()
,11-17 18:30:51.066   756  1055 D DisplayPowerController: getFinalBrightness : 10 -> 10
,11-17 18:30:51.066   756  1055 D DisplayPowerController: animation target = 10, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,11-17 18:30:51.236   756  1055 D AutomaticBrightnessController: mCallbacks.updateBrightness()
,11-17 18:30:51.246   756  1055 D DisplayPowerController: getFinalBrightness : 10 -> 10
,11-17 18:30:51.246   756  1055 D DisplayPowerController: animation target = 10, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,11-17 18:30:51.416   756  1055 D AutomaticBrightnessController: mCallbacks.updateBrightness()
,11-17 18:30:51.416   756  1055 D DisplayPowerController: getFinalBrightness : 10 -> 10
11-17 18:30:51.416   756  1055 D DisplayPowerController: animation target = 10, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,11-17 18:30:51.596   756  1055 D AutomaticBrightnessController: mCallbacks.updateBrightness()
,11-17 18:30:51.606   756  1055 D DisplayPowerController: getFinalBrightness : 10 -> 10
,11-17 18:30:51.606   756  1055 D DisplayPowerController: animation target = 10, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,11-17 18:30:51.776   756  1055 D AutomaticBrightnessController: mCallbacks.updateBrightness()
,11-17 18:30:51.786   756  1055 D DisplayPowerController: getFinalBrightness : 10 -> 10
,11-17 18:30:51.786   756  1055 D DisplayPowerController: animation target = 10, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,11-17 18:30:51.956   756  1055 D AutomaticBrightnessController: mCallbacks.updateBrightness()
,11-17 18:30:51.956   756  1055 D DisplayPowerController: getFinalBrightness : 10 -> 10
,11-17 18:30:51.966   756  1055 D DisplayPowerController: animation target = 10, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,11-17 18:30:52.136   756  1055 D AutomaticBrightnessController: mCallbacks.updateBrightness()
,11-17 18:30:52.136   756  1055 D DisplayPowerController: getFinalBrightness : 10 -> 10
,11-17 18:30:52.146   756  1055 D DisplayPowerController: animation target = 10, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,11-17 18:30:52.316   756  1055 D AutomaticBrightnessController: mCallbacks.updateBrightness()
,11-17 18:30:52.316   756  1055 D DisplayPowerController: getFinalBrightness : 10 -> 10
,11-17 18:30:52.326   756  1055 D DisplayPowerController: animation target = 10, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,11-17 18:30:52.496   756  1055 D AutomaticBrightnessController: mCallbacks.updateBrightness()
,11-17 18:30:52.496   756  1055 D DisplayPowerController: getFinalBrightness : 10 -> 10
,11-17 18:30:52.506   756  1055 D DisplayPowerController: animation target = 10, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,11-17 18:30:52.676   756  1055 D AutomaticBrightnessController: mCallbacks.updateBrightness()
,11-17 18:30:52.676   756  1055 D DisplayPowerController: getFinalBrightness : 10 -> 10
,11-17 18:30:52.686   756  1055 D DisplayPowerController: animation target = 10, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,11-17 18:30:52.786   294   294 E SMD     : DCD ON
,11-17 18:30:52.856   756  1055 D AutomaticBrightnessController: mCallbacks.updateBrightness()
,11-17 18:30:52.856   756  1055 D DisplayPowerController: getFinalBrightness : 10 -> 10
,11-17 18:30:52.866   756  2873 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,11-17 18:30:52.866   756  1055 D DisplayPowerController: animation target = 10, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,11-17 18:30:53.036   756  1055 D AutomaticBrightnessController: mCallbacks.updateBrightness()
,11-17 18:30:53.036   756  1055 D DisplayPowerController: getFinalBrightness : 10 -> 10
,11-17 18:30:53.036   756  1055 D DisplayPowerController: animation target = 10, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,11-17 18:30:53.216   756  1055 D AutomaticBrightnessController: mCallbacks.updateBrightness()
,11-17 18:30:53.216   756  1055 D DisplayPowerController: getFinalBrightness : 10 -> 10
,11-17 18:30:53.216   756  1055 D DisplayPowerController: animation target = 10, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,11-17 18:30:53.396   756  1055 D AutomaticBrightnessController: mCallbacks.updateBrightness()
,11-17 18:30:53.396   756  1055 D DisplayPowerController: getFinalBrightness : 10 -> 10
,11-17 18:30:53.396   756  1055 D DisplayPowerController: animation target = 10, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,11-17 18:30:53.576   756  1055 D AutomaticBrightnessController: mCallbacks.updateBrightness()
,11-17 18:30:53.576   756  1055 D DisplayPowerController: getFinalBrightness : 10 -> 10
,11-17 18:30:53.576   756  1055 D DisplayPowerController: animation target = 10, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,11-17 18:30:53.766   756  1055 D AutomaticBrightnessController: mCallbacks.updateBrightness()
,11-17 18:30:53.766   756  1055 D DisplayPowerController: getFinalBrightness : 10 -> 10
,11-17 18:30:53.766   756  1055 D DisplayPowerController: animation target = 10, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,11-17 18:30:53.926  6145  6145 D BluetoothAdapter: disable()
,11-17 18:30:53.926   756  1634 E BluetoothManagerService: Bluetooth is already disabled. DO NOT disable again.
,11-17 18:30:53.936   756  1055 D AutomaticBrightnessController: mCallbacks.updateBrightness()
,11-17 18:30:53.936   756  1055 D DisplayPowerController: getFinalBrightness : 10 -> 10
,11-17 18:30:53.936   756  1055 D DisplayPowerController: animation target = 10, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,11-17 18:30:53.956  6145  6145 I WifiManager: packageName : com.example.hello
,11-17 18:30:53.956   756  1233 D SecContentProvider: uri = 18 selection = isWifiEnabled
,11-17 18:30:53.956   756  1233 D SecContentProvider2: uri = 20 selection = isWifiStateChangeAllowed
11-17 18:30:53.956   756  1233 D SecContentProvider2: mCursor = null
,11-17 18:30:53.956   756  1233 D WifiService: setWifiEnabled: false pid=6145, uid=10232
,11-17 18:30:53.956   756  1233 D SettingsProvider: name = wifi_on
,11-17 18:30:53.956  6145  6145 I jxcore-log: ****TEST TOOK:  5063  ms ****
11-17 18:30:53.956  6145  6145 I jxcore-log: 
,11-17 18:30:53.956  6145  6145 I jxcore-log: ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
11-17 18:30:53.956  6145  6145 I jxcore-log: 
,11-17 18:30:54.116   756  1055 D AutomaticBrightnessController: mCallbacks.updateBrightness()
11-17 18:30:54.116   756  1055 D DisplayPowerController: getFinalBrightness : 10 -> 10
11-17 18:30:54.116   756  1055 D DisplayPowerController: animation target = 10, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,11-17 18:30:54.286  6239  6239 D AndroidRuntime: 
11-17 18:30:54.286  6239  6239 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
,11-17 18:30:54.286  6239  6239 D AndroidRuntime: CheckJNI is OFF
,11-17 18:30:54.296  6239  6239 D AndroidRuntime: readGMSProperty: start,
11-17 18:30:54.296  6239  6239 D AndroidRuntime: readGMSProperty: already setted!!
11-17 18:30:54.296   756  1055 D AutomaticBrightnessController: mCallbacks.updateBrightness()
11-17 18:30:54.296   756  1055 D DisplayPowerController: getFinalBrightness : 10 -> 10
11-17 18:30:54.296   756  1055 D DisplayPowerController: animation target = 10, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,11-17 18:30:54.296  6239  6239 D AndroidRuntime: readGMSProperty: end
,11-17 18:30:54.296  6239  6239 D AndroidRuntime: addProductProperty: start
,11-17 18:30:54.476   756  1055 D AutomaticBrightnessController: mCallbacks.updateBrightness()
11-17 18:30:54.476   756  1055 D DisplayPowerController: getFinalBrightness : 10 -> 10
11-17 18:30:54.476   756  1055 D DisplayPowerController: animation target = 10, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,11-17 18:30:54.476  6239  6239 E AffinityControl: AffinityControl: registerfunction enter
,11-17 18:30:54.496  6239  6239 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
,11-17 18:30:54.506   756  1324 D PackageManager: START PACKAGE DELETE: observer{352382687}
11-17 18:30:54.506   756  1324 D PackageManager: pkg{<packageName>}
11-17 18:30:54.506   756  1324 D PackageManager: user{0}
11-17 18:30:54.506   756  1324 D PackageManager: caller{2000}
11-17 18:30:54.506   756  1324 D PackageManager: flags{3}
,11-17 18:30:54.506   756  1324 D PersonaManagerService: isFromApprovedUnInstaller: uid, userId, appid : 2000 0 2000
11-17 18:30:54.506   756  1324 D PersonaManagerService: isFromApprovedUnInstaller: isApproved : true
11-17 18:30:54.506   756  1324 D PersonaManagerService: isFromApprovedUnInstaller: isApproved before exit: true
,11-17 18:30:54.506   756  1324 D PackageManager: deletePackageAsUser- pkg:com.example.hello, userId:0, flag3
11-17 18:30:54.506   756  1324 D PackageManager: deletePackageAsUser- pkg:com.example.hello, userId:0, flag3
,11-17 18:30:54.506   756  1060 D PackageManager: [MSG] DELETE_PACKAGE_AS_USER
,11-17 18:30:54.506   756  1060 D PackageManagerService: deletePackage- pkg:com.example.hello, edmuserId:0
,11-17 18:30:54.506   756  1060 D PackageManagerService: deletePackage- pkg:com.example.hello, edmuserId:-1
11-17 18:30:54.506   756  1060 D ApplicationPolicy: getApplicationUninstallationEnabled
11-17 18:30:54.506   756  1060 D ApplicationPolicy: getApplicationUninstallationEnabled :  enabled true
,11-17 18:30:54.506   756  1060 D PackageManager: !@killApplicatoin: 10232, uninstall pkg
,11-17 18:30:54.506   756   900 I ActivityManager: Force stopping com.example.hello appid=10232 user=-1: uninstall pkg
,11-17 18:30:54.516   756   900 I ActivityManager: Killing 6145:com.example.hello/u0a232 (adj 0): stop com.example.hello
,11-17 18:30:54.586   756  1060 W PackageSettings: Skipping PackageSetting{184d8bf4 com.test.thalitest/10224} due to missing metadata
,11-17 18:30:54.586   756  1233 I WindowState: WIN DEATH: Window{1c22a9e7 u0 com.example.hello/com.example.hello.MainActivity}
,11-17 18:30:54.586   254   328 I SurfaceFlinger: id=13 Removed NainActivit (5/8)
,11-17 18:30:54.586   254  6059 I SurfaceFlinger: id=13 Removed NainActivit (-2/8)
11-17 18:30:54.586   254  6059 I SurfaceFlinger: id=13 Removed NainActivit (-2/8)
,11-17 18:30:54.596   756  1052 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
,11-17 18:30:54.596   756  1052 D PointerIcon: setMouseCustomIcon IconType is same.101
11-17 18:30:54.596   756  1052 D PointerIcon: setHoveringSpenIconStyle1 pointerType: 10001iconType:1 flag:0
11-17 18:30:54.596   756  1052 D PointerIcon: setHoveringSpenCustomIcon IconType is same.1
,11-17 18:30:54.626   756   900 W ActivityManager: Force removing ActivityRecord{4ca246 u0 com.example.hello/.MainActivity t2}: app died, no saved state
,11-17 18:30:54.626   756   900 D FocusedStackFrame: Set to : 0
,11-17 18:30:54.626   756   900 D CustomFrequencyManagerService: acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1958400  uid : 1000  pid : 756  pkgName : ACTIVITY_RESUME_BOOSTER@7
11-17 18:30:54.626   756   900 W ActivityManager: mDVFSHelper.acquire()
,11-17 18:30:54.636   756   900 V WindowOrientationListener: mSContextAutoRotationListener.getProposedRotation, mbResultFaceDectection: false
,11-17 18:30:54.636   756   900 V WindowOrientationListener: mSContextAutoRotationListener.getProposedRotation, Rotation: -1
11-17 18:30:54.636   756   900 V WindowManager: rotationForOrientationLw(orient=1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false
11-17 18:30:54.636   756   900 V WindowOrientationListener: mSContextAutoRotationListener.getProposedRotation, mbResultFaceDectection: false
11-17 18:30:54.636   756   900 V WindowOrientationListener: mSContextAutoRotationListener.getProposedRotation, Rotation: -1
,11-17 18:30:54.636  1437  1437 D SurfaceWidgetView: destroyHardwareResources():904848728
,11-17 18:30:54.646  1437  1437 D Launcher: onRestart, Launcher: 933538847
,11-17 18:30:54.646   756  1451 W ActivityManager: Spurious death for ProcessRecord{19a7d72c 6145:com.example.hello/u0a232}, curProc for 6145: null
,11-17 18:30:54.646   756  1060 I ActivityManager: Force stopping com.example.hello appid=10232 user=0: pkg removed
,11-17 18:30:54.646   756  1055 D AutomaticBrightnessController: mCallbacks.updateBrightness()
11-17 18:30:54.656   756  1055 D DisplayPowerController: getFinalBrightness : 10 -> 10
11-17 18:30:54.656   756  1055 D DisplayPowerController: animation target = 10, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,11-17 18:30:54.686  1437  1437 D Launcher: onStart, Launcher: 933538847
,11-17 18:30:54.686  1437  1437 D Launcher.HomeView: onStart
,11-17 18:30:54.686  1437  1437 D Launcher: onResume, Launcher: 933538847
11-17 18:30:54.686   756  2861 D ConnectivityService: returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,11-17 18:30:54.686   756  1356 D SettingsProvider: name = kids_home_mode
11-17 18:30:54.686   756  1356 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
11-17 18:30:54.686   756  1356 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
11-17 18:30:54.686   756  1356 D SettingsProvider: selectionArgs: false
11-17 18:30:54.686   756  1356 D SettingsProvider: selectionArgs: 10010
11-17 18:30:54.686   756  1356 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
11-17 18:30:54.686   756  1356 D SettingsProvider: ret = -1
11-17 18:30:54.686  1437  1437 D Launcher.HomeView: onResume
,11-17 18:30:54.696  1771  1783 D SurfaceWidgetClient$ISurfaceWidgetStub: [237392/8] Surface widget resume on instance = 1
,11-17 18:30:54.696  1771  1771 D accuweather: [Accuweather J]>>> SWW:179 [0:0] [SWW] onResume : rI = 1
11-17 18:30:54.696  1437  1437 D Launcher: setSystemUiTransparency.SettingNotFoundException : set as TRUE
11-17 18:30:54.696  1771  1771 D accuweather: [Accuweather J]>>> SWW:184 [0:0] [SWW] onResume : Orientation = 1/1
11-17 18:30:54.696  1771  1771 D accuweather: [Accuweather J]>>> WR:456 [0:0] =============== updateTime = 1
11-17 18:30:54.696  1437  1437 D Launcher: Launcher::setSystemUiTransparency(): getSystemUiVisibility() after setting  = 8000
11-17 18:30:54.696  1771  1771 D accuweather: [Accuweather J]>>> SWW:198 [0:0] [SWW] onResume : size = 1
,11-17 18:30:54.696   756  1052 D ResourcesManager: creating new AssetManager and set to /system/priv-app/InputDevices/InputDevices.apk
,11-17 18:30:54.696  1771  1771 D accuweather: [Accuweather J]>>> DBH:1954 [0:0] gADWI : count = 0
,11-17 18:30:54.696   756   888 D ResourcesManager: creating new AssetManager and set to /system/priv-app/Velvet/Velvet.apk
11-17 18:30:54.706  3987  3987 I art     : Explicit concurrent mark sweep GC freed 36142(1978KB) AllocSpace objects, 9(144KB) LOS objects, 39% free, 15MB/26MB, paused 406us total 23.265ms
,11-17 18:30:54.706  1713  1713 E SamsungIME: mOCRHelper is null
,11-17 18:30:54.706  1481  1803 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
,11-17 18:30:54.706   756   900 E ActivityManager: checkUser: useridlist=null, currentuser=0
11-17 18:30:54.706   756   900 E ActivityManager: checkUser: useridlist=null, currentuser=0
11-17 18:30:54.706   756   900 E ActivityManager: checkUser: useridlist=null, currentuser=0
11-17 18:30:54.706   756   900 E ActivityManager: checkUser: useridlist=null, currentuser=0
,11-17 18:30:54.716   756  1114 I InputReader: Reconfiguring input devices.  changes=0x00000010
,11-17 18:30:54.716   756   888 D ResourcesManager: creating new AssetManager and set to /system/app/SamsungIME/SamsungIME.apk
,11-17 18:30:54.726  5861  5861 I art     : Explicit concurrent mark sweep GC freed 2946(161KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 15MB/25MB, paused 392us total 20.245ms
,11-17 18:30:54.726  4249  4249 I art     : Explicit concurrent mark sweep GC freed 7212(446KB) AllocSpace objects, 1(16KB) LOS objects, 24% free, 16MB/21MB, paused 363us total 29.240ms
,11-17 18:30:54.726  1771  1771 D accuweather: [Accuweather J]>>> WCD:423 [0:0]  onFirstUpdate :: fU = false
,11-17 18:30:54.726  1771  1771 D accuweather: [Accuweather J]>>> SWW:313 [0:0] hideMsg : mResumeInstnceList[0] = 1
11-17 18:30:54.726  1771  1771 D accuweather: [Accuweather J]>>> WR:800 [0:0] hideMsg : -1, isShow = false
11-17 18:30:54.726  1771  1771 D accuweather: [Accuweather J]>>> WR:806 [0:0] hideMsg : 0
,11-17 18:30:54.726  1771  1771 D accuweather: [Accuweather J]>>> WCD:513 [0:0]  onResume : fU = false, cnt =0
11-17 18:30:54.726  1771  1771 D accuweather: [Accuweather J]>>> WCD:523 [0:0]  onResume :: mFAR = false, cC = false, isa = false
11-17 18:30:54.726  1771  1771 D accuweather: [Accuweather J]>>> SWW:605 [0:0]  registerTTReceiver ! 
,11-17 18:30:54.736  6267  6267 E Zygote  : MountEmulatedStorage()
,11-17 18:30:54.736  6267  6267 E Zygote  : v2
11-17 18:30:54.736  6267  6267 I libpersona: KNOX_SDCARD checking this for 10023
11-17 18:30:54.736  6267  6267 I libpersona: KNOX_SDCARD not a persona
11-17 18:30:54.736   756   900 I ActivityManager: Start proc com.samsung.klmsagent for broadcast com.samsung.klmsagent/.listner.MainReciver: pid=6267 uid=10023 gids={50023, 9997, 3003} abi=armeabi-v7a
11-17 18:30:54.746  1771  1771 D accuweather: [Accuweather J]>>> WR:497 [0:0] onResume : 1, widgetMode : 1, orientation : 1
11-17 18:30:54.766  6267  6267 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0 ver=27
11-17 18:30:54.766  1437  1437 D MenuAppsGridFragment: onResume
11-17 18:30:54.766  1771  2075 D SurfaceWidgetClient$ISurfaceWidgetStub: [237392/8] Surface widget visibility changed visibility = true on instance = 1
11-17 18:30:54.766   756  1664 D ActivityManager: handle home activity for 0
11-17 18:30:54.766   756  1664 I WallpaperManagerService: switchPersonaWallpaper is called for personaId-0
11-17 18:30:54.766   756  1664 D KnoxTimeoutHandler: post home show event for user 0
11-17 18:30:54.766   756  1664 D ActivityManager: post active user change for 0
11-17 18:30:54.766   756  1664 D KnoxTimeoutHandler: postActiveUserChange for user 0
11-17 18:30:54.766  1771  2009 D SurfaceWidget.Renderer: [237392/8] SurfaceWidget drawing first frame
11-17 18:30:54.766  1771  2009 D accuweather: [Accuweather J]>>> WR:623 [0:0] onGLDraw : BG texture = 5
11-17 18:30:54.766  6267  6267 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N9005_5.0_0027
11-17 18:30:54.766  1771  1771 D comsamsunglog: [Accuweather J]>>> ==============================================================================================
11-17 18:30:54.766  1771  1771 D comsamsunglog: [Accuweather J]>>> widgetappapheroaccuweather [Version : 14121502] [ 1 ] 
11-17 18:30:54.766  1771  1771 D comsamsunglog: [Accuweather J]>>> Header set to : ===> "accuweather" <===
11-17 18:30:54.766  1771  1771 D comsamsunglog: [Accuweather J]>>> ==============================================================================================
11-17 18:30:54.766  6267  6267 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
11-17 18:30:54.766   254   254 I SurfaceFlinger: id=14 createSurf (1080x1920),1 flag=4, Mauncher
11-17 18:30:54.766   756  1046 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
,11-17 18:30:54.776  1771  2009 D accuweather: [Accuweather J]>>> SM:1134 [0:0] updateCurrentCityTime : [1]0/1
11-17 18:30:54.776  1771  2009 D accuweather: [Accuweather J]>>> SM:1151 [0:0] updateCurrentCityTime , ConditionLayerWidth = 852, mConditionLayerHeight = 532
,11-17 18:30:54.776  1771  2009 D accuweather: [Accuweather J]>>> SM:2053 [0:0] drw 1nd Tm dt = Tue, 17 November
,11-17 18:30:54.786   756  1052 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
11-17 18:30:54.786   756  1052 D PointerIcon: setMouseCustomIcon IconType is same.101
11-17 18:30:54.786   756  1052 D PointerIcon: setHoveringSpenIconStyle1 pointerType: 10001iconType:1 flag:0
11-17 18:30:54.786   756  1052 D PointerIcon: setHoveringSpenCustomIcon IconType is same.1
,11-17 18:30:54.786  1771  1771 D accuweather: [Accuweather J]>>> SM:3422 [0:0] onR : isAni = false
,11-17 18:30:54.786  1771  1771 D accuweather: [Accuweather J]>>> SWW:544 [0:0] =================== , resume :1
,11-17 18:30:54.786   756   888 D EnterpriseDeviceManagerService: Package has changed for user 0
,11-17 18:30:54.786   756   888 D EnterpriseDeviceManagerService: Admin package name: com.google.android.gms
,11-17 18:30:54.806   756   756 I art     : Explicit concurrent mark sweep GC freed 42673(2MB) AllocSpace objects, 20(320KB) LOS objects, 17% free, 37MB/45MB, paused 3.700ms total 131.505ms
11-17 18:30:54.806   756  1060 I art     : WaitForGcToComplete blocked for 64.239ms for cause Explicit
,11-17 18:30:54.816   756   888 D ResourcesManager: creating new AssetManager and set to /system/app/Evernote_H/Evernote_H.apk
,11-17 18:30:54.816   756   756 D ResourcesManager: creating new AssetManager and set to /data/app/com.google.android.gms-2/base.apk
,11-17 18:30:54.826  6267  6267 D TimaKeyStoreProvider: TimaSignature is unavailable
,11-17 18:30:54.826  6267  6267 D ActivityThread: Added TimaKeyStore provider
,11-17 18:30:54.826   756  1055 D AutomaticBrightnessController: mCallbacks.updateBrightness()
11-17 18:30:54.826   756  1055 D DisplayPowerController: getFinalBrightness : 10 -> 10
11-17 18:30:54.826   756  1055 D DisplayPowerController: animation target = 10, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,11-17 18:30:54.836  1437  1437 D Launcher: setSystemUiTransparency.SettingNotFoundException : set as TRUE
,11-17 18:30:54.836  1437  1437 D Launcher: Launcher::setSystemUiTransparency(): getSystemUiVisibility() after setting  = 8000
,11-17 18:30:54.836   756  1634 D InputMethodManagerService: windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,11-17 18:30:54.836   756   756 D ResourcesManager: creating new AssetManager and set to /system/priv-app/SNS/SNS.apk
,11-17 18:30:54.836   756   888 D ResourcesManager: creating new AssetManager and set to /system/priv-app/SecContacts_Phone_OSup/SecContacts_Phone_OSup.apk
,11-17 18:30:54.856  6267  6267 D ResourcesManager: creating new AssetManager and set to /system/priv-app/KLMSAgent/KLMSAgent.apk
11-17 18:30:54.856   756  1634 W InputMethodManagerService: Got RemoteException sending setActive(false) notification to pid 6145 uid 10232
,11-17 18:30:54.856   756  6285 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.android.server.InputMethodManagerService$6.run:2733 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
11-17 18:30:54.856   756   756 D ResourcesManager: creating new AssetManager and set to /system/priv-app/Samsungservice2_xxhdpi/Samsungservice2_xxhdpi.apk
,11-17 18:30:54.866   756   756 D ResourcesManager: creating new AssetManager and set to /system/app/ChatON_MARKET/ChatON_MARKET.apk
,11-17 18:30:54.876  1622  6287 I MicrophoneInputStream: mic_starting gfk@3911ee9e
,11-17 18:30:54.876   756   756 D ResourcesManager: creating new AssetManager and set to /system/app/Dropbox/Dropbox.apk
,11-17 18:30:54.876   756   756 D ResourcesManager: creating new AssetManager and set to /system/app/Gmail2/Gmail2.apk
,11-17 18:30:54.876   299  1604 V AudioPolicyManager: getInput() inputSource 1999, samplingRate 16000, format 8, channelMask 1, session 0, flags 0x10
11-17 18:30:54.876   299  1604 V AudioPolicyManager: getDeviceForInputSource()input source 1999, device 80000004
11-17 18:30:54.876   299  1604 V audio_hw_primary: adev_open_input_stream: enter
,11-17 18:30:54.886   299  1604 E audio_hw_primary: adev_open_input_stream : jack_config 0
11-17 18:30:54.886   299  1604 E audio_hw_primary: can not make /data/snd/hal_input.pcm 
11-17 18:30:54.886   299  1604 E audio_hw_primary: can not make /data/snd/hal_input_before_ns.pcm 
,11-17 18:30:54.886   299  1604 E audio_hw_primary: can not make /data/snd/hal_input_after_ns.pcm 
11-17 18:30:54.886   299  1604 E audio_hw_primary: adev_open_input_stream input is null, set new input stream
11-17 18:30:54.886   299  1604 V audio_hw_primary: adev_open_input_stream: exit
,11-17 18:30:54.886   756  2079 I EDMNativeHelperService: isMicrophoneEnabled
,11-17 18:30:54.886   756   756 D ResourcesManager: creating new AssetManager and set to /system/app/SBrowser/SBrowser.apk
11-17 18:30:54.886  1622  6288 I HotwordRecognitionRnr: Starting hotword detection.
,11-17 18:30:54.886   299  6290 I AudioFlinger: AudioFlinger's thread 0xb1933000 ready to run
11-17 18:30:54.886   299  6290 V audio_hw_primary: in_standby: enter
11-17 18:30:54.886   299  6290 V audio_hw_primary: in_standby: exit:  status(0)
,11-17 18:30:54.896   299  6290 V audio_hw_primary: in_standby: enter
11-17 18:30:54.896   299  6290 V audio_hw_primary: in_standby: exit:  status(0)
,11-17 18:30:54.896   299   687 V AudioPolicyManager: startInput() input 16
11-17 18:30:54.896   299   687 V AudioPolicyManager: getDeviceForInputSource()input source 1999, device 80000004
11-17 18:30:54.896   299   687 V AudioPolicyManager: getNewInputDevice() selected device 80000004
11-17 18:30:54.896   299   687 V AudioPolicyManager: DeviceVector::refreshTypes() mDeviceTypes 80000004
11-17 18:30:54.896   299   687 V AudioPolicyManager: DeviceVector::getDevicesFromType() for type 80000004 found 0xb315b3c0
,11-17 18:30:54.896   299  6290 V audio_hw_primary: in_set_parameters: enter: kvpairs=input_source=6;keyIsHotword=true;routing=-2147483644
11-17 18:30:54.896   299  6290 V audio_hw_primary: in_set_parameters: exit: status(11)
11-17 18:30:54.896   299   687 V AudioPolicyManager: setInputDevice() createAudioPatch returned 11 patchHandle 0
11-17 18:30:54.896   299   687 V AudioPolicyManager: AudioPolicyManager::startInput() input source = 1999
11-17 18:30:54.896  1622  6287 I MicrophoneInputStream: mic_started gfk@3911ee9e
,11-17 18:30:54.896   756   756 D ResourcesManager: creating new AssetManager and set to /system/app/SecEmail_K/SecEmail_K.apk
,11-17 18:30:54.906   299  6290 V msm8974_platform: platform_update_usecase_from_source: input source :6
11-17 18:30:54.906   299  6290 V audio_hw_primary: start_input_stream: enter: usecase(7)
11-17 18:30:54.906   299  6290 V voice   : voice_check_and_set_incall_rec_usecase: voice call not active
11-17 18:30:54.906   299  6290 V audio_hw_primary: start_input_stream: usecase(7)
11-17 18:30:54.906  1415  1415 D RegisteredServicesCache: empty dynamic service
11-17 18:30:54.906   299  6290 D PreProcess: new SamsungRecord
11-17 18:30:54.906   299  6290 D PreProcess: new NS
11-17 18:30:54.906   299  6290 I samsungRecord: [samsungrecord] SamsungRecInit 
,11-17 18:30:54.906   299  6290 I samsungRecord: [samsungrecordMIC]Use HardCoding Values
11-17 18:30:54.906   299  6290 E samsungRecord: miccalib file can't created. (/data/snd/miccalib.txt)
11-17 18:30:54.906   299  6290 I samsungRecord: 1
11-17 18:30:54.906   299  6290 D SamsungRecord_NS: [SamsungRecord_NS] Init SR 16000
11-17 18:30:54.906   299  6290 D SamsungRecord_NS: [SamsungRecord_NS] getLevel inputsource 6, ret_level 3
11-17 18:30:54.906   299  6290 V audio_hw_primary: select_devices: ENTER
11-17 18:30:54.906   299  6290 V audio_hw_primary: select_devices: usecase(normal)
11-17 18:30:54.906   299  6290 V audio_hw_primary: select_devices: usecase(PCM_CAPTURE)
11-17 18:30:54.906   299  6290 V msm8974_platform: platform_get_input_snd_device: enter: out_device(0) in_device(0x4)
11-17 18:30:54.906   299  6290 V msm8974_platform: get_INPUT_snd_device: check by Input_source(6)
11-17 18:30:54.906   299  6290 V msm8974_platform: platform_get_input_snd_device_by_source: enter: out_device(0) in_device(0x4)
11-17 18:30:54.906   299  6290 V msm8974_platform: get_INPUT_snd_device: AUDIO_SOURCE_VOICE_RECOGNITION
11-17 18:30:54.906   299  6290 V msm8974_platform: platform_get_input_snd_device: exit: in_snd_device(vr-main-mic)
11-17 18:30:54.906   299  6290 D audio_hw_primary: select_devices: out_snd_device(0: dummy)
11-17 18:30:54.906   299  6290 D audio_hw_primary: select_devices: in_snd_device(128: vr-main-mic)
11-17 18:30:54.906   299  6290 D ACDB-LOADER: ACDB -> send_audio_cal, acdb_id = 53, path =  1
11-17 18:30:54.906   299  6290 D ACDB-LOADER: ACDB -> send_adm_topology
11-17 18:30:54.906   299  6290 D ACDB-LOADER: ACDB -> ACDB_CMD_GET_AUDPROC_COMMON_TOPOLOGY_ID
11-17 18:30:54.906   299  6290 D ACDB-LOADER: ACDB -> send_asm_topology
11-17 18:30:54.906   299  6290 D ACDB-LOADER: ACDB -> ACDB_CMD_GET_AUDPROC_STREAM_TOPOLOGY_ID
11-17 18:30:54.906   299  6290 D ACDB-LOADER: ACDB -> send_audtable
11-17 18:30:54.906   299  6290 D ACDB-LOADER: ACDB -> ACDB_CMD_GET_AUDPROC_COMMON_TABLE
11-17 18:30:54.906   299  6290 D ACDB-LOADER: ACDB -> AUDIO_SET_AUDPROC_CAL
11-17 18:30:54.906   299  6290 D ACDB-LOADER: ACDB -> send_audvoltable
11-17 18:30:54.906   299  6290 D ACDB-LOADER: ACDB -> ACDB_CMD_GET_AUDPROC_GAIN_DEP_STEP_TABLE
11-17 18:30:54.906   299  6290 D         : Failed to fetch the lookup information of the device 00000035 
11-17 18:30:54.906   299  6290 E ACDB-LOADER: Error: ACDB AudProc vol returned = -19
11-17 18:30:54.906   299  6290 D ACDB-LOADER: ACDB -> AUDIO_SET_AUDPROC_VOL_CAL
11-17 18:30:54.906   299  6290 D ACDB-LOADER: ACDB -> AUDIO_SET_AFE_CAL
11-17 18:30:54.906   299  6290 V audio_hw_primary: enable_snd_device: snd_device(128: vr-main-mic, vr-main-mic)
11-17 18:30:54.906   299  6290 D audio_route: ++++ audio_route_update_mixer ==============
11-17 18:30:54.906   299  6290 D audio_route: Setting mixer control: ADC1 Volume
11-17 18:30:54.906   299  6290 D audio_route: Setting mixer control: value: 19
,11-17 18:30:54.906   299  6290 D audio_route: Setting mixer control: DEC6 Volume
11-17 18:30:54.906   299  6290 D audio_route: Setting mixer control: value: 84
,11-17 18:30:54.906   299  6290 D audio_route: Setting mixer control: SLIM TX7 MUX, value: 13
,11-17 18:30:54.906   299  6290 D audio_route: Setting mixer control: AIF1_CAP Mixer SLIM TX7
11-17 18:30:54.906   299  6290 D audio_route: Setting mixer control: value: 1
11-17 18:30:54.906   299  6290 D audio_route: Setting mixer control: DEC6 MUX, value: 2
,11-17 18:30:54.916   299  6290 D audio_route: ------ audio_route_update_mixer ==============
11-17 18:30:54.916   299  6290 V audio_hw_primary: enable_audio_route: enter: usecase(7)
11-17 18:30:54.916   299  6290 V audio_hw_primary: enable_audio_route: apply mixer path: audio-record
11-17 18:30:54.916   299  6290 D audio_route: ++++ audio_route_update_mixer ==============
11-17 18:30:54.916   299  6290 D audio_route: Setting mixer control: MultiMedia1 Mixer SLIM_0_TX
11-17 18:30:54.916   299  6290 D audio_route: Setting mixer control: value: 1
,11-17 18:30:54.916   299  6290 D audio_route: ------ audio_route_update_mixer ==============
11-17 18:30:54.916   299  6290 V audio_hw_primary: enable_audio_route: exit
11-17 18:30:54.916   299  6290 V audio_hw_primary: start_input_stream: Opening PCM device card_id(0) device_id(0), channels 1
,11-17 18:30:54.916   299  6290 V audio_hw_primary: start_input_stream: exit
,11-17 18:30:54.916   756   756 D ResourcesManager: creating new AssetManager and set to /system/priv-app/GoogleServicesFramework/GoogleServicesFramework.apk
,11-17 18:30:54.916   756   756 D ResourcesManager: creating new AssetManager and set to /system/priv-app/Pinboard/Pinboard.apk
,11-17 18:30:54.916   756  1324 D SecContentProvider2: uri = 11 selection = getMyKnoxAdmin
11-17 18:30:54.916   756  1324 D SecContentProvider2: mCursor = null
,11-17 18:30:54.926   756   756 D ResourcesManager: creating new AssetManager and set to /system/priv-app/SHealth3_5/SHealth3_5.apk
,11-17 18:30:54.926   756  1046 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
,11-17 18:30:54.936  1437  1437 D WallpaperManager: SEC_PRODUCT_FEATURE_COMMON_SUPPORT_TEXTURE_COMPRESSION is true
,11-17 18:30:54.936  1437  1437 D WallpaperManager: SEC_PRODUCT_FEATURE_COMMON_SUPPORT_TEXTURE_COMPRESSION is true
,11-17 18:30:54.946  6267  6267 I KLMS-2.4.511: : KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,11-17 18:30:54.946   756   756 D ResourcesManager: creating new AssetManager and set to /system/priv-app/SecGallery2013/SecGallery2013.apk
,11-17 18:30:54.946  6267  6267 I KLMS-2.4.511: : MainReciver(): EventNotificationReciver- method called: AppActivityListner onReceive for Intent Action : android.intent.action.PACKAGE_REMOVED , timestamp: 1447781454950
,11-17 18:30:54.946   756   756 D ResourcesManager: creating new AssetManager and set to /system/priv-app/sCloudSyncCalendar/sCloudSyncCalendar.apk
,11-17 18:30:54.946  6267  6267 I KLMS-2.4.511: : MainReciver(): PACKAGE_REMOVED
,11-17 18:30:54.946   756   756 D ResourcesManager: creating new AssetManager and set to /system/priv-app/sCloudSyncContacts/sCloudSyncContacts.apk
,11-17 18:30:54.946  6267  6267 I KLMS-2.4.511: : MainReciver(): REPLACING: false | pkgName: com.example.hello
,11-17 18:30:54.946   756   756 D ResourcesManager: creating new AssetManager and set to /system/priv-app/sCloudSyncSBrowser/sCloudSyncSBrowser.apk
,11-17 18:30:54.946   756   756 D ResourcesManager: creating new AssetManager and set to /system/app/Books/Books.apk
,11-17 18:30:54.956   756   756 D ResourcesManager: creating new AssetManager and set to /system/app/Chrome/Chrome.apk
,11-17 18:30:54.966   756   888 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,11-17 18:30:54.966   756   888 D ResourcesManager: creating new AssetManager and set to /system/priv-app/SecMms_Candy/SecMms_Candy.apk
,11-17 18:30:54.966   756   756 D ResourcesManager: creating new AssetManager and set to /system/app/Drive/Drive.apk
,11-17 18:30:54.966  1437  1437 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@12e7d275 time:88344
,11-17 18:30:54.976   756   756 D ResourcesManager: creating new AssetManager and set to /system/app/GoogleCalendarSyncAdapter/GoogleCalendarSyncAdapter.apk
,11-17 18:30:54.986  1622  1622 I HotwordWorker: onReady
,11-17 18:30:54.986   756   756 D ResourcesManager: creating new AssetManager and set to /system/app/GoogleContactsSyncAdapter/GoogleContactsSyncAdapter.apk
,11-17 18:30:54.986   756   756 D ResourcesManager: creating new AssetManager and set to /system/app/Music2/Music2.apk
,11-17 18:30:54.986   756   756 D ResourcesManager: creating new AssetManager and set to /system/app/Newsstand/Newsstand.apk
,11-17 18:30:54.996   756   756 D ResourcesManager: creating new AssetManager and set to /system/app/PlusOne/PlusOne.apk
,11-17 18:30:54.996   756   756 D ResourcesManager: creating new AssetManager and set to /system/app/SNote4.1Preload/SNote4.1Preload.apk
,11-17 18:30:55.006   756   756 D ResourcesManager: creating new AssetManager and set to /system/app/SecExchange/SecExchange.apk
,11-17 18:30:55.006   756   756 D ResourcesManager: creating new AssetManager and set to /system/app/Videos/Videos.apk
,11-17 18:30:55.006   756  1055 D AutomaticBrightnessController: mCallbacks.updateBrightness()
11-17 18:30:55.006   756  1055 D DisplayPowerController: getFinalBrightness : 10 -> 10
11-17 18:30:55.006   756  1055 D DisplayPowerController: animation target = 10, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,11-17 18:30:55.016   756   888 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,11-17 18:30:55.026   756   888 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,11-17 18:30:55.036   756  1533 E ActivityManager: checkUser: useridlist=null, currentuser=0
11-17 18:30:55.036   756  1533 E ActivityManager: checkUser: useridlist=null, currentuser=0
11-17 18:30:55.036   756  1533 E ActivityManager: checkUser: useridlist=null, currentuser=0
11-17 18:30:55.036   756  1533 E ActivityManager: checkUser: useridlist=null, currentuser=0
,11-17 18:30:55.036   756   888 D ResourcesManager: creating new AssetManager and set to /system/app/YouTube/YouTube.apk
,11-17 18:30:55.036   756   756 D RCPManagerService: PackageReceiver onReceive()
11-17 18:30:55.036   756   756 I HarmonyEASService: onReceive : android.intent.action.PACKAGE_REMOVED for 0
11-17 18:30:55.036   756   756 D KnoxMUMContainerPolicy: mPackageReceiver : action - android.intent.action.PACKAGE_REMOVED
11-17 18:30:55.036   756   756 D BackupManagerService: Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.example.hello flg=0x4000010 (has extras) }
11-17 18:30:55.036   756   756 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
11-17 18:30:55.036   756   756 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - start - android.intent.action.PACKAGE_REMOVED
11-17 18:30:55.036   756   756 V EnterpriseBillingPolicy: uID is 10232
11-17 18:30:55.036   756   756 V EnterpriseBillingPolicy: Removed Packageuid is0
11-17 18:30:55.036   756   756 V EnterpriseBillingPolicyStorage: getProfileForApplication - enter
11-17 18:30:55.036   756   756 V EnterpriseBillingPolicyStorage: getProfileForApplication - exit null
11-17 18:30:55.036   756   756 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - personal application - profile null
11-17 18:30:55.036   756   756 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - might be a vpn vendor package 
11-17 18:30:55.036   756   756 V EnterpriseBillingPolicyStorage: getBillingProfileForVpnEngine - start - com.example.hello
11-17 18:30:55.046   756   756 V EnterpriseBillingPolicyStorage: getBillingProfileForVpnEngine - end - null
,11-17 18:30:55.046   756   888 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,11-17 18:30:55.046   756   888 D ResourcesManager: creating new AssetManager and set to /system/priv-app/SFinder/SFinder.apk
,11-17 18:30:55.056   756   888 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
11-17 18:30:55.056   756   888 D ResourcesManager: creating new AssetManager and set to /system/priv-app/SamsungLink20/SamsungLink20.apk
,11-17 18:30:55.056  6291  6291 E Zygote  : MountEmulatedStorage()
11-17 18:30:55.056  6291  6291 E Zygote  : v2
11-17 18:30:55.056  6291  6291 I libpersona: KNOX_SDCARD checking this for 10116
11-17 18:30:55.056  6291  6291 I libpersona: KNOX_SDCARD not a persona
,11-17 18:30:55.066   756  1533 I ActivityManager: Start proc com.sec.esdk.elm for broadcast com.sec.esdk.elm/.receiver.MainReceiver: pid=6291 uid=10116 gids={50116, 9997, 3003} abi=armeabi-v7a
,11-17 18:30:55.066   756  1533 I ActivityManager: Killing 5053:com.google.android.talk/u0a131 (adj 15): bgCount ##41
,11-17 18:30:55.076   756   756 D WallpaperManagerService:  force update = false; persona id = 0; current user =0; current persona = 0
11-17 18:30:55.076   756   756 D KnoxTimeoutHandler: handleHomeShow for 0 and current 0
11-17 18:30:55.076   756   756 D KnoxTimeoutHandler: handleActiveUserChange for user 0
,11-17 18:30:55.076   756  1174 D TaskPersister: removeObsoleteFile: deleting file=2_task.xml
,11-17 18:30:55.076   756   888 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,11-17 18:30:55.076   756   888 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,11-17 18:30:55.076   756   888 D ResourcesManager: creating new AssetManager and set to /system/app/ChatON_MARKET/ChatON_MARKET.apk
,11-17 18:30:55.086   756   888 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,11-17 18:30:55.086   756   888 D ResourcesManager: creating new AssetManager and set to /system/app/Chrome/Chrome.apk
,11-17 18:30:55.086   756   888 D ResourcesManager: creating new AssetManager and set to /system/app/Drive/Drive.apk
,11-17 18:30:55.086   756  1060 I art     : Explicit concurrent mark sweep GC freed 11794(728KB) AllocSpace objects, 1(16KB) LOS objects, 17% free, 37MB/45MB, paused 2.353ms total 277.371ms
,11-17 18:30:55.106  6291  6291 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0 ver=27
,11-17 18:30:55.106   756   888 D ResourcesManager: creating new AssetManager and set to /system/app/Dropbox/Dropbox.apk
,11-17 18:30:55.106  6291  6291 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N9005_5.0_0027
,11-17 18:30:55.106  6291  6291 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,11-17 18:30:55.126   756   888 D ResourcesManager: creating new AssetManager and set to /system/app/InteractiveTutorial/InteractiveTutorial.apk
11-17 18:30:55.126   756   888 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
11-17 18:30:55.126   756   888 D ResourcesManager: creating new AssetManager and set to /system/app/Maps/Maps.apk
11-17 18:30:55.126   756   900 D CustomFrequencyManagerService: releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1958400  uid : 1000  pid : 756  tag : ACTIVITY_RESUME_BOOSTER@7
11-17 18:30:55.126  6291  6291 D TimaKeyStoreProvider: TimaSignature is unavailable
11-17 18:30:55.126   756   900 W ActivityManager: mDVFSHelper.release()
,11-17 18:30:55.126   756   900 D CustomFrequencyManagerService: acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1958400  uid : 1000  pid : 756  pkgName : ACTIVITY_RESUME_BOOSTER@11
11-17 18:30:55.126  6291  6291 D ActivityThread: Added TimaKeyStore provider
,11-17 18:30:55.146   756   888 D ResourcesManager: creating new AssetManager and set to /system/app/Newsstand/Newsstand.apk
,11-17 18:30:55.146   756   888 D ResourcesManager: creating new AssetManager and set to /system/app/Peel_L/Peel_L.apk
,11-17 18:30:55.156  6291  6291 D ResourcesManager: creating new AssetManager and set to /system/app/ELMAgent/ELMAgent.apk
,11-17 18:30:55.156   756   888 D ResourcesManager: creating new AssetManager and set to /system/app/SNote4.1Preload/SNote4.1Preload.apk
,11-17 18:30:55.156   756  1060 D PackageManager: delete codoeFile: 
,11-17 18:30:55.156   756   888 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
11-17 18:30:55.156   756   888 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
11-17 18:30:55.156   756   888 D ResourcesManager: creating new AssetManager and set to /system/app/SPlanner_LEGACY/SPlanner_LEGACY.apk
,11-17 18:30:55.156   756  1060 I AASAUninstall:  com.example.hello not target!
11-17 18:30:55.156   756  1060 D PackageManager: result of delete: 1{352382687}
,11-17 18:30:55.166   756   888 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
,11-17 18:30:55.166   756   888 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
11-17 18:30:55.166   756   888 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
11-17 18:30:55.166  6239  6239 D AndroidRuntime: Shutting down VM
,11-17 18:30:55.166   756   888 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
11-17 18:30:55.166   756   888 D ResourcesManager: creating new AssetManager and set to /system/app/Videos/Videos.apk
,11-17 18:30:55.176  6291  6291 D elm:14491: ELMAbstractReceiver.onReceive() : Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.example.hello flg=0x4000010 cmp=com.sec.esdk.elm/.receiver.MainReceiver (has extras) }
,11-17 18:30:55.186  6291  6291 D elm:14491: ELMEngine.ELMEngine( context ).
,11-17 18:30:55.186   756  1052 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{2dbbbbbe u0 com.sec.android.app.launcher/com.android.launcher2.Launcher t1} time:88564
,11-17 18:30:55.186  6291  6291 D elm:14491: MDMBridge.setEnterpriseBridge()
,11-17 18:30:55.186   756   888 D ResourcesManager: creating new AssetManager and set to /system/app/YouTube/YouTube.apk
,11-17 18:30:55.186   756  1055 D AutomaticBrightnessController: mCallbacks.updateBrightness()
11-17 18:30:55.186   756  1055 D DisplayPowerController: getFinalBrightness : 10 -> 10
11-17 18:30:55.186   756  1055 D DisplayPowerController: animation target = 10, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,11-17 18:30:55.196   756   888 D ResourcesManager: creating new AssetManager and set to /data/app/com.google.android.play.games-1/base.apk
,11-17 18:30:55.196  6291  6291 D elm:14491: ELMAbstractReceiver : Receive Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.example.hello flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) } END.
,11-17 18:30:55.196   756  1577 E ActivityManager: checkUser: useridlist=null, currentuser=0
11-17 18:30:55.196   756  1577 E ActivityManager: checkUser: useridlist=null, currentuser=0
11-17 18:30:55.196   756  1577 E ActivityManager: checkUser: useridlist=null, currentuser=0
11-17 18:30:55.196   756  1577 E ActivityManager: checkUser: useridlist=null, currentuser=0
,11-17 18:30:55.206   756   888 D ResourcesManager: creating new AssetManager and set to /system/priv-app/Velvet/Velvet.apk
,11-17 18:30:55.206  6291  6291 D elm:14491: ElmAgentService : onCreate()
,11-17 18:30:55.206  6291  6306 D elm:14491: ElmAgentService : onHandleIntent() Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.example.hello flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) }
,11-17 18:30:55.206  6291  6306 D elm:14491: MainReceiver.listeningToPackageRemoved()
11-17 18:30:55.216  6291  6306 D elm:14491: MDMBridge.getInstance()
11-17 18:30:55.216  6291  6306 D elm:14491: MDMBridge.getAllLicenseInfoFromSDK()
,11-17 18:30:55.216  6291  6306 D elm:14491: MDMBridge.getAllLicenseInfoFromSDK()
,11-17 18:30:55.226  6307  6307 E Zygote  : MountEmulatedStorage()
11-17 18:30:55.226  6307  6307 I libpersona: KNOX_SDCARD checking this for 10021
11-17 18:30:55.226  6307  6307 E Zygote  : v2
11-17 18:30:55.226  6307  6307 I libpersona: KNOX_SDCARD not a persona
,11-17 18:30:55.226   756   888 D ResourcesManager: creating new AssetManager and set to /system/priv-app/SamsungMusic_20/SamsungMusic_20.apk
,11-17 18:30:55.226   756   888 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,11-17 18:30:55.226   756   888 D ResourcesManager: creating new AssetManager and set to /system/priv-app/SecContacts_Phone_OSup/SecContacts_Phone_OSup.apk
,11-17 18:30:55.236   756  1577 I ActivityManager: Start proc com.sec.android.service.health for broadcast com.sec.android.service.health/.upgrade.UninstallReceiver: pid=6307 uid=10021 gids={50021, 9997} abi=armeabi-v7a
,11-17 18:30:55.236   756   888 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,11-17 18:30:55.236   756   888 D ResourcesManager: creating new AssetManager and set to /system/priv-app/SecGallery2013/SecGallery2013.apk
,11-17 18:30:55.236   756   888 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,11-17 18:30:55.236   756   888 W Resources: Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
11-17 18:30:55.236   756   888 D ResourcesManager: creating new AssetManager and set to /system/priv-app/SecMyFiles2/SecMyFiles2.apk
,11-17 18:30:55.246  6307  6307 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0 ver=27
11-17 18:30:55.246  6291  6291 D elm:14491: ElmAgentService : onDestroy().
,11-17 18:30:55.246  6307  6307 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N9005_5.0_0027
,11-17 18:30:55.246  6307  6307 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,11-17 18:30:55.246   756  1577 I ActivityManager: Killing 5309:com.samsung.android.app.FileShareServer/u0a88 (adj 15): bgCount ##41
,11-17 18:30:55.246   756   888 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
11-17 18:30:55.246   756   888 D ResourcesManager: creating new AssetManager and set to /system/priv-app/SecVideoPlayer/SecVideoPlayer.apk
,11-17 18:30:55.256   756   888 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
11-17 18:30:55.256   756   888 W Resources: Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
11-17 18:30:55.256   756   888 D ResourcesManager: creating new AssetManager and set to /system/priv-app/VoiceNote/VoiceNote.apk
,11-17 18:30:55.256   756   888 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
11-17 18:30:55.256   756   888 W Resources: Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,11-17 18:30:55.256   756   888 D ResourcesManager: creating new AssetManager and set to /system/app/SBrowser/SBrowser.apk
,11-17 18:30:55.266  6307  6307 D TimaKeyStoreProvider: TimaSignature is unavailable
,11-17 18:30:55.266  6307  6307 D ActivityThread: Added TimaKeyStore provider
,11-17 18:30:55.276   756   888 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,11-17 18:30:55.276   756   888 D UsbSettingsManager: clearDefaults: com.example.hello
,11-17 18:30:55.276   756   888 I CrashAnrDetector: onPackageRemoved : com.example.hello
,11-17 18:30:55.286  6307  6307 D ResourcesManager: creating new AssetManager and set to /system/priv-app/HealthService/HealthService.apk
,11-17 18:30:55.306  6307  6307 D com.sec.android.service.health.upgrade.UninstallReceiver: onReceive()
11-17 18:30:55.306  6307  6307 I com.sec.android.service.health.upgrade.UninstallReceiver: onReceive called  PACKAGE_REMOVED package:com.example.hello
11-17 18:30:55.306  6307  6307 D com.sec.android.service.health.upgrade.UninstallReceiver: onReceive() : package name is not s health. Return !!!
,11-17 18:30:55.316  5712  5712 I PCWCLIENTTRACE_PushUtil: SPPPushClient is installed : true
11-17 18:30:55.316  5712  5712 I PCWCLIENTTRACE_PushUtil: sales region : global
11-17 18:30:55.316  5712  5712 I PCWCLIENTTRACE_PushUtil: getPushTypeList : [SPP, GCM]
11-17 18:30:55.316  5712  5712 I PCWCLIENTTRACE_SYSTEMReceiver: [onReceive] - android.intent.action.PACKAGE_REMOVED
,11-17 18:30:55.336   756  1664 E ActivityManager: checkUser: useridlist=null, currentuser=0
,11-17 18:30:55.336   756  1664 E ActivityManager: checkUser: useridlist=null, currentuser=0
11-17 18:30:55.336   756  1664 E ActivityManager: checkUser: useridlist=null, currentuser=0
11-17 18:30:55.336   756  1664 E ActivityManager: checkUser: useridlist=null, currentuser=0
,11-17 18:30:55.366  6324  6324 E Zygote  : MountEmulatedStorage()
,11-17 18:30:55.366  6324  6324 E Zygote  : v2
11-17 18:30:55.366  6324  6324 I libpersona: KNOX_SDCARD checking this for 10043
11-17 18:30:55.366  6324  6324 I libpersona: KNOX_SDCARD not a persona
,11-17 18:30:55.376   756  1055 D AutomaticBrightnessController: mCallbacks.updateBrightness()
11-17 18:30:55.376   756  1055 D DisplayPowerController: getFinalBrightness : 10 -> 10
11-17 18:30:55.376   756  1055 D DisplayPowerController: animation target = 10, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,11-17 18:30:55.376   756  1664 I ActivityManager: Start proc com.sec.spp.push:RemoteNotiProcess for broadcast com.sec.spp.push/.notisvc.registration.PackageRemovedReceiver: pid=6324 uid=10043 gids={50043, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,11-17 18:30:55.386  6324  6324 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0 ver=27
,11-17 18:30:55.386   756  2079 I ActivityManager: Killing 5337:com.sec.knox.bridge/1000 (adj 15): bgCount ##41
11-17 18:30:55.386  6324  6324 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N9005_5.0_0027
11-17 18:30:55.386  6324  6324 E SELinux : [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
,11-17 18:30:55.416  6324  6324 D TimaKeyStoreProvider: TimaSignature is unavailable
,11-17 18:30:55.416  6324  6324 D ActivityThread: Added TimaKeyStore provider
,11-17 18:30:55.436   756   756 D CustomFrequencyManagerService: releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1958400  uid : 1000  pid : 756  tag : ACTIVITY_RESUME_BOOSTER@11
,11-17 18:30:55.436  6324  6324 D ResourcesManager: creating new AssetManager and set to /system/priv-app/SPPPushClient_Prod/SPPPushClient_Prod.apk
,11-17 18:30:55.466  6324  6324 E SPPClientService: ============PushLog. commonIsShipBuild. stop!
11-17 18:30:55.466  6324  6324 E SPPClientService: [PushClientApplication] Push log off : This is Ship build version
,11-17 18:30:55.476  6324  6324 D SPPClientService: PushLog.txt file is not deleted.
,11-17 18:30:55.476  6324  6324 D SPPClientService: PushLog.txt file is not deleted.
11-17 18:30:55.476  6324  6324 D SPPClientService: ============PushLog. stop!
,11-17 18:30:55.486  6324  6324 W FileUtils: Failed to chmod(/data/data/com.sec.spp.push/databases/push_noti_db): android.system.ErrnoException: chmod failed: EROFS (Read-only file system)
,11-17 18:30:55.496  5794  5794 I SA      : [SUR] onReceive log=[SA = 2.1.0081 V = 21 HWD = 1920X1080 3.0 dpi = 480  SIZE = 2 LOCALE = en_US CSC = XEO MCC = 0 MNC 0 T = user DEVICE = hlte P = hltexx I = LRX21V M = SM-N9005 OKLEFT false DIS LRX21V.N9005XXUGBOB6 PSS = 5.701607447389803  ]
,11-17 18:30:55.496  5794  5794 I SA      : [SUR] onReceive Intent=[ action_PACKAGE_REMOVED package extra.REMOVED_FOR_ALL_USERS.:true extra.UID.:10232 extra.DATA_REMOVED.:true extra.user_handle.:0 ]
,11-17 18:30:55.496   756  1707 I ActivityManager: Killing 5389:com.sec.knox.knoxsetupwizardclient/1000 (adj 13): bgCount ##41
,11-17 18:30:55.516  4807  4807 E SharedPreferencesImpl: Couldn't rename file /data/data/com.sec.android.gallery3d/shared_prefs/com.sec.android.gallery3d_preferences.xml to backup file /data/data/com.sec.android.gallery3d/shared_prefs/com.sec.android.gallery3d_preferences.xml.bak
,11-17 18:30:55.516  4876  4876 D Mms/FreeMessageReceiver: onReceive, action : android.intent.action.PACKAGE_REMOVED
,11-17 18:30:55.526   756   772 I TactileAssist: enable value -1
11-17 18:30:55.526   756   772 I TactileAssist: internal enable value -1
11-17 18:30:55.526   756   772 I TactileAssist: intensity value -1
11-17 18:30:55.526   756   772 I TactileAssist: saveAppList value true
,11-17 18:30:55.526  4876  6343 D Mms/FreeMessageReceiverService: onHandleIntent, action : android.intent.action.PACKAGE_REMOVED
11-17 18:30:55.526  4876  6343 D Mms/FreeMessageReceiverService: onHandleIntent: ACTION_PACKAGE_REMOVED
,11-17 18:30:55.526   756   772 I TactileAssist: List of disabled apps :
,11-17 18:30:55.546   756  1055 D AutomaticBrightnessController: mCallbacks.updateBrightness()
11-17 18:30:55.546   756  1055 D DisplayPowerController: getFinalBrightness : 10 -> 10
11-17 18:30:55.546   756  1055 D DisplayPowerController: animation target = 10, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,11-17 18:30:55.546   756  1707 D SettingsProvider: name = reading_mode_app_list
,11-17 18:30:55.556  5815  5815 D Compatibility: onReceive() it will make start service
,11-17 18:30:55.556  5815  6344 D Compatibility: onHandleIntent()
,11-17 18:30:55.556  5815  6344 D Compatibility: intentservice saw: Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.example.hello flg=0x4000010 cmp=com.sec.android.app.soundalive/.compatibility.Compatibility$Receiver (has extras) } Bundle[{android.intent.extra.REMOVED_FOR_ALL_USERS=true, android.intent.extra.UID=10232, android.intent.extra.DATA_REMOVED=true, android.intent.extra.user_handle=0}]
,11-17 18:30:55.556  5815  6344 D Compatibility: found: 2
11-17 18:30:55.556  5815  6344 D Compatibility: saved default: com.sec.android.app.soundalive.SAControlPanelActivity
11-17 18:30:55.556  5815  6344 D Compatibility: skipping ResolveInfo{ed703be com.sec.android.app.soundalive/.compatibility.Compatibility$Redirector p=2147483647 m=0x108000}
11-17 18:30:55.556  5815  6344 D Compatibility: considering ResolveInfo{37a4ac1f com.sec.android.app.soundalive/.SAControlPanelActivity m=0x108000}
11-17 18:30:55.556  5815  6344 D Compatibility: default: com.sec.android.app.soundalive.SAControlPanelActivity
,11-17 18:30:55.556  5815  6344 D Compatibility: enabling receiver ResolveInfo{1c88eb6c com.sec.android.app.soundalive/.SAControlPanelReceiver m=0x108000}
,11-17 18:30:55.566  5815  6344 D Compatibility: enabling receiver ResolveInfo{1f8f5535 com.sec.android.app.soundalive/.compatibility.HelperGooglePlayMusic m=0x108000}
,11-17 18:30:55.566  5815  6344 D Compatibility: enabling receiver ResolveInfo{37fb9dca com.sec.android.app.soundalive/.SAControlPanelReceiver m=0x108000}
,11-17 18:30:55.566  1622  6345 I UpdateIcingCorporaServi: Updating corpora: APPS=com.example.hello, CONTACTS=MAYBE
,11-17 18:30:55.566  5815  6344 D Compatibility: enabling receiver ResolveInfo{1471eb3b com.sec.android.app.soundalive/.compatibility.HelperGooglePlayMusic m=0x108000}
,11-17 18:30:55.576  5038  5038 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2051 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.samsung.android.app.assistantmenu.AssistantMenuReceiver.onReceive:159 android.app.ActivityThread.handleReceiver:2991 
,11-17 18:30:55.576   756  1114 I EventHub: Removing device '/dev/input/event6' due to inotify event
,11-17 18:30:55.576  5815  6344 E SharedPreferencesImpl: Couldn't create directory for SharedPreferences file /data/data/com.sec.android.app.soundalive/shared_prefs/SoundAlive_Settings.xml
,11-17 18:30:55.576  5815  6344 E SharedPreferencesImpl: Couldn't create directory for SharedPreferences file /data/data/com.sec.android.app.soundalive/shared_prefs/SoundAlive_Settings.xml
11-17 18:30:55.576  5815  6344 D Compatibility: wrote com.sec.android.app.soundalive/com.sec.android.app.soundalive.SAControlPanelActivity as default
,11-17 18:30:55.576   756  2079 E ActivityManager: checkUser: useridlist=null, currentuser=0
,11-17 18:30:55.576   756  2079 E ActivityManager: checkUser: useridlist=null, currentuser=0
11-17 18:30:55.576   756  2079 E ActivityManager: checkUser: useridlist=null, currentuser=0
11-17 18:30:55.576   756  2079 E ActivityManager: checkUser: useridlist=null, currentuser=0
,11-17 18:30:55.586  5038  6346 E SQLiteLog: (28) failed to open "/data/data/com.samsung.android.app.assistantmenu/databases/AssistantMenu" with flag (131138) and mode_t (0) due to error (2)
11-17 18:30:55.586  5038  6346 E SQLiteLog: (28) failed to open "/data/data/com.samsung.android.app.assistantmenu/databases/AssistantMenu" with flag (131072) and mode_t (0) due to error (2)
11-17 18:30:55.586  5038  6346 E SQLiteLog: (14) cannot open file at line 32503 of [9491ba7d73]
11-17 18:30:55.586  5038  6346 E SQLiteLog: (14) os_unix.c:32503: (2) open(/data/data/com.samsung.android.app.assistantmenu/databases/AssistantMenu) - 
,11-17 18:30:55.586  5038  6346 E SQLiteDatabase: Failed to open database '/data/data/com.samsung.android.app.assistantmenu/databases/AssistantMenu'.
11-17 18:30:55.586  5038  6346 E SQLiteDatabase: android.database.sqlite.SQLiteCantOpenDatabaseException: unknown error (code 14): Could not open database
11-17 18:30:55.586  5038  6346 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
11-17 18:30:55.586  5038  6346 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
11-17 18:30:55.586  5038  6346 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
11-17 18:30:55.586  5038  6346 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
11-17 18:30:55.586  5038  6346 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
11-17 18:30:55.586  5038  6346 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
11-17 18:30:55.586  5038  6346 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:894)
11-17 18:30:55.586  5038  6346 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:864)
11-17 18:30:55.586  5038  6346 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
11-17 18:30:55.586  5038  6346 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1507)
11-17 18:30:55.586  5038  6346 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
11-17 18:30:55.586  5038  6346 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
11-17 18:30:55.586  5038  6346 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
11-17 18:30:55.586  5038  6346 E SQLiteDatabase: 	at com.samsung.android.app.assistantmenu.serviceframework.DatabaseHandler.deleteAMData(DatabaseHandler.java:160)
11-17 18:30:55.586  5038  6346 E SQLiteDatabase: 	at com.samsung.android.app.assistantmenu.serviceframework.AMMetaDataParserService.onHandleIntent(AMMetaDataParserService.java:109)
11-17 18:30:55.586  5038  6346 E SQLiteDatabase: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
11-17 18:30:55.586  5038  6346 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-17 18:30:55.586  5038  6346 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:145)
11-17 18:30:55.586  5038  6346 E SQLiteDatabase: 	at android.os.HandlerThread.run(HandlerThread.java:61)
11-17 18:30:55.586  5038  6346 W System.err: android.database.sqlite.SQLiteCantOpenDatabaseException: unknown error (code 14): Could not open database
11-17 18:30:55.586  5038  6346 W System.err: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
11-17 18:30:55.586  5038  6346 W System.err: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
11-17 18:30:55.586  5038  6346 W System.err: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
11-17 18:30:55.586  5038  6346 W System.err: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
11-17 18:30:55.586  5038  6346 W System.err: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
11-17 18:30:55.586  5038  6346 W System.err: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
11-17 18:30:55.586  5038  6346 W System.err: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:894)
11-17 18:30:55.586  5038  6346 W System.err: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:864)
11-17 18:30:55.586  5038  6346 W System.err: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699),
11-17 18:30:55.586  5038  6346 W System.err: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1507)
11-17 18:30:55.586  5038  6346 W System.err: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
11-17 18:30:55.586  5038  6346 W System.err: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
11-17 18:30:55.586  5038  6346 W System.err: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
11-17 18:30:55.586  5038  6346 W System.err: 	at com.samsung.android.app.assistantmenu.serviceframework.DatabaseHandler.deleteAMData(DatabaseHandler.java:160)
11-17 18:30:55.586  5038  6346 W System.err: 	at com.samsung.android.app.assistantmenu.serviceframework.AMMetaDataParserService.onHandleIntent(AMMetaDataParserService.java:109)
11-17 18:30:55.586  5038  6346 W System.err: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
11-17 18:30:55.586  5038  6346 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-17 18:30:55.586  5038  6346 W System.err: 	at android.os.Looper.loop(Looper.java:145)
11-17 18:30:55.586  5038  6346 W System.err: 	at android.os.HandlerThread.run(HandlerThread.java:61)
11-17 18:30:55.606  6347  6347 E Zygote  : MountEmulatedStorage()
11-17 18:30:55.606  6347  6347 E Zygote  : v2
11-17 18:30:55.606  6347  6347 I libpersona: KNOX_SDCARD checking this for 1000
11-17 18:30:55.606  6347  6347 I libpersona: KNOX_SDCARD not a persona
11-17 18:30:55.616   756  2079 I ActivityManager: Start proc com.sec.knox.bridge for broadcast com.sec.knox.bridge/.PersonaShortcutReceiver: pid=6347 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1007, 1028, 1015, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,11-17 18:30:55.626   756  1114 I EventHub: Removing device '/dev/input/event7' due to inotify event
,11-17 18:30:55.626  1622  6345 E SQLiteLog: (10) POSIX Error : 9 SQLite Error : 3850
,11-17 18:30:55.626  1622  6345 E SQLiteLog: (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
,11-17 18:30:55.626  1622  6345 F libc    : Fatal signal 7 (SIGBUS), code 2, fault addr 0xa041e4e1 in tid 6345 (IntentService[U)
,11-17 18:30:55.646  6347  6347 I SELinux : Function: selinux_compare_spd_ram , priority [2] , priority version is VE=SEPF_SM-N9005_5.0_0002
,11-17 18:30:55.646  6347  6347 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,11-17 18:30:55.666   756  1114 I EventHub: Removing device '/dev/input/event8' due to inotify event
,11-17 18:30:55.676  6347  6347 D TimaKeyStoreProvider: TimaSignature is unavailable
,11-17 18:30:55.676  6347  6347 D ActivityThread: Added TimaKeyStore provider
,11-17 18:30:55.686  6347  6347 D ResourcesManager: creating new AssetManager and set to /system/app/Bridge/Bridge.apk
,11-17 18:30:55.686  6347  6347 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,11-17 18:30:55.686  6347  6347 W ContextImpl: Unable to create files subdir /data/data/com.sec.knox.bridge/cache
11-17 18:30:55.686  6347  6347 E ActivityThread: Unable to setupGraphicsSupport due to missing cache directory
,11-17 18:30:55.696  6347  6347 W         : Zip: inflate read failed (11191 vs 32768)
,11-17 18:30:55.696  6347  6347 D AndroidRuntime: Shutting down VM
,11-17 18:30:55.706  6347  6347 E AndroidRuntime: FATAL EXCEPTION: main
11-17 18:30:55.706  6347  6347 E AndroidRuntime: Process: com.sec.knox.bridge, PID: 6347
11-17 18:30:55.706  6347  6347 E AndroidRuntime: java.lang.RuntimeException: Unable to instantiate receiver com.sec.knox.bridge.PersonaShortcutReceiver: java.lang.ClassNotFoundException: Didn't find class "com.sec.knox.bridge.PersonaShortcutReceiver" on path: DexPathList[[zip file "/system/framework/twframework.jar", zip file "/system/app/Bridge/Bridge.apk"],nativeLibraryDirectories=[/vendor/lib, /system/lib]]
11-17 18:30:55.706  6347  6347 E AndroidRuntime: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2972)
11-17 18:30:55.706  6347  6347 E AndroidRuntime: 	at android.app.ActivityThread.access$1800(ActivityThread.java:177)
11-17 18:30:55.706  6347  6347 E AndroidRuntime: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1525)
11-17 18:30:55.706  6347  6347 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-17 18:30:55.706  6347  6347 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:145)
11-17 18:30:55.706  6347  6347 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:5940)
11-17 18:30:55.706  6347  6347 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
11-17 18:30:55.706  6347  6347 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Method.java:372)
11-17 18:30:55.706  6347  6347 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1389)
11-17 18:30:55.706  6347  6347 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1184)
11-17 18:30:55.706  6347  6347 E AndroidRuntime: Caused by: java.lang.ClassNotFoundException: Didn't find class "com.sec.knox.bridge.PersonaShortcutReceiver" on path: DexPathList[[zip file "/system/framework/twframework.jar", zip file "/system/app/Bridge/Bridge.apk"],nativeLibraryDirectories=[/vendor/lib, /system/lib]]
11-17 18:30:55.706  6347  6347 E AndroidRuntime: 	at dalvik.system.BaseDexClassLoader.findClass(BaseDexClassLoader.java:56)
11-17 18:30:55.706  6347  6347 E AndroidRuntime: 	at java.lang.ClassLoader.loadClass(ClassLoader.java:511)
11-17 18:30:55.706  6347  6347 E AndroidRuntime: 	at java.lang.ClassLoader.loadClass(ClassLoader.java:469)
11-17 18:30:55.706  6347  6347 E AndroidRuntime: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2967)
11-17 18:30:55.706  6347  6347 E AndroidRuntime: 	... 9 more
11-17 18:30:55.706  6347  6347 E AndroidRuntime: 	Suppressed: java.io.IOException: Failed to extract 'classes.dex' from '/system/app/Bridge/Bridge.apk': I/O Error
11-17 18:30:55.706  6347  6347 E AndroidRuntime: 		at dalvik.system.DexFile.openDexFileNative(Native Method)
11-17 18:30:55.706  6347  6347 E AndroidRuntime: 		at dalvik.system.DexFile.openDexFile(DexFile.java:295)
11-17 18:30:55.706  6347  6347 E AndroidRuntime: 		at dalvik.system.DexFile.<init>(DexFile.java:80)
11-17 18:30:55.706  6347  6347 E AndroidRuntime: 		at dalvik.system.DexFile.<init>(DexFile.java:59)
11-17 18:30:55.706  6347  6347 E AndroidRuntime: 		at dalvik.system.DexPathList.loadDexFile(DexPathList.java:262)
11-17 18:30:55.706  6347  6347 E AndroidRuntime: 		at dalvik.system.DexPathList.makeDexElements(DexPathList.java:231)
11-17 18:30:55.706  6347  6347 E AndroidRuntime: 		at dalvik.system.DexPathList.<init>(DexPathList.java:109)
11-17 18:30:55.706  6347  6347 E AndroidRuntime: 		at dalvik.system.BaseDexClassLoader.<init>(BaseDexClassLoader.java:48)
11-17 18:30:55.706  6347  6347 E AndroidRuntime: 		at dalvik.system.PathClassLoader.<init>(PathClassLoader.java:65)
11-17 18:30:55.706  6347  6347 E AndroidRuntime: 		at dalvik.system.PathClassLoader.openArtFile(PathClassLoader.java:74)
11-17 18:30:55.706  6347  6347 E AndroidRuntime: 		at java.lang.reflect.Method.invoke(Native Method)
11-17 18:30:55.706  6347  6347 E AndroidRuntime: 		at java.lang.reflect.Method.invoke(Method.java:372)
11-17 18:30:55.706  6347  6347 E AndroidRuntim,e: 		at android.app.ApplicationLoaders.openArtFile(ApplicationLoaders.java:63)
11-17 18:30:55.706  6347  6347 E AndroidRuntime: 		at android.app.ApplicationLoaders.getClassLoader(ApplicationLoaders.java:119)
11-17 18:30:55.706  6347  6347 E AndroidRuntime: 		at android.app.ApplicationLoaders.getClassLoader(ApplicationLoaders.java:46)
11-17 18:30:55.706  6347  6347 E AndroidRuntime: 		at android.app.LoadedApk.getClassLoader(LoadedApk.java:415)
11-17 18:30:55.706  6347  6347 E AndroidRuntime: 		at android.app.LoadedApk.makeApplication(LoadedApk.java:615)
11-17 18:30:55.706  6347  6347 E AndroidRuntime: 		at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5084)
11-17 18:30:55.706  6347  6347 E AndroidRuntime: 		at android.app.ActivityThread.access$1600(ActivityThread.java:177)
11-17 18:30:55.706  6347  6347 E AndroidRuntime: 		at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1509)
11-17 18:30:55.706  6347  6347 E AndroidRuntime: 		... 7 more
11-17 18:30:55.706  6347  6347 E AndroidRuntime: 	Caused by: java.io.IOException: Failed to open file '/data/dalvik-cache/arm/system@app@Bridge@Bridge.apk@classes.dex': Read-only file system
11-17 18:30:55.706  6347  6347 E AndroidRuntime: 		... 27 more
11-17 18:30:55.706  6347  6347 E AndroidRuntime: 	Caused by: java.io.IOException: Failed to open oat file from dex location '/system/app/Bridge/Bridge.apk'
11-17 18:30:55.706  6347  6347 E AndroidRuntime: 		... 27 more
11-17 18:30:55.706  6347  6347 E AndroidRuntime: 	Caused by: java.io.IOException: Failed to open oat file from /system/app/Bridge/arm/Bridge.odex (error Failed to open oat filename for reading: No such file or directory) (no dalvik_cache availible) and relocation failed.
11-17 18:30:55.706  6347  6347 E AndroidRuntime: 		... 27 more
11-17 18:30:55.706  6347  6347 E AndroidRuntime: 	Caused by: java.io.IOException: 
11-17 18:30:55.706  6347  6347 E AndroidRuntime: 		... 27 more
11-17 18:30:55.706  6347  6347 E AndroidRuntime: 	Suppressed: java.lang.ClassNotFoundException: com.sec.knox.bridge.PersonaShortcutReceiver
11-17 18:30:55.706  6347  6347 E AndroidRuntime: 		at java.lang.Class.classForName(Native Method)
11-17 18:30:55.706  6347  6347 E AndroidRuntime: 		at java.lang.BootClassLoader.findClass(ClassLoader.java:781)
11-17 18:30:55.706  6347  6347 E AndroidRuntime: 		at java.lang.BootClassLoader.loadClass(ClassLoader.java:841)
11-17 18:30:55.706  6347  6347 E AndroidRuntime: 		at java.lang.ClassLoader.loadClass(ClassLoader.java:504)
11-17 18:30:55.706  6347  6347 E AndroidRuntime: 		... 11 more
11-17 18:30:55.706  6347  6347 E AndroidRuntime: 	Caused by: java.lang.NoClassDefFoundError: Class not found using the boot class loader; no stack available
11-17 18:30:55.706   756  1634 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.sec.knox.bridge
11-17 18:30:55.716   756  6362 E AndroidRuntime: *** FATAL EXCEPTION IN SYSTEM PROCESS: Error dump: system_app_crash
11-17 18:30:55.716   756  6362 E AndroidRuntime: java.lang.IllegalArgumentException: Invalid path: /data/system/dropbox
11-17 18:30:55.716   756  6362 E AndroidRuntime: 	at android.os.StatFs.doStat(StatFs.java:46)
11-17 18:30:55.716   756  6362 E AndroidRuntime: 	at android.os.StatFs.restat(StatFs.java:56)
11-17 18:30:55.716   756  6362 E AndroidRuntime: 	at com.android.server.DropBoxManagerService.trimToFit(DropBoxManagerService.java:726)
11-17 18:30:55.716   756  6362 E AndroidRuntime: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:188)
11-17 18:30:55.716   756  6362 E AndroidRuntime: 	at android.os.DropBoxManager.addText(DropBoxManager.java:269)
11-17 18:30:55.716   756  6362 E AndroidRuntime: 	at com.android.server.am.ActivityManagerService$23.run(ActivityManagerService.java:14833)
11-17 18:30:55.716   756  6362 E AndroidRuntime: Caused by: android.system.ErrnoException: statvfs failed: ENOENT (No such file or directory)
11-17 18:30:55.716   756  6362 E AndroidRuntime: 	at libcore.io.Posix.statvfs(Native Method)
11-17 18:30:55.716   756  6362 E AndroidRuntime: 	at libcore.io.BlockGuardOs.statvfs(BlockGuardOs.java:298)
11-17 18:30:55.716   756  6362 E AndroidRuntime: 	at android.system.Os.statvfs(Os.java:473)
11-17 18:30:55.716   756  6362 E AndroidRuntime: 	at android.os.StatFs.doStat(StatFs.java:44)
11-17 18:30:55.716   756  6362 E AndroidRuntime: 	... 5 more
11-17 18:30:55.716   756   900 D ResourcesManager: creating new AssetManager and set to /system/app/Bridge/Bridge.apk
11-17 18:30:55.716   756   900 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
11-17 18:30:55.736   285   285 I DEBUG   : failed to create /data/tombstones: Read-only file system
11-17 18:30:55.736   285   285 I DEBUG   : failed to open /data/tombstones: No such file or directory
11-17 18:30:55.736   285   285 E         : !@dumpstate -k -t -z -d -o /data/log/dumpstate_app_native -m 1622
,11-17 18:30:55.746   756  1046 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
11-17 18:30:55.746   756  1052 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
11-17 18:30:55.746   756  1052 D PointerIcon: setMouseCustomIcon IconType is same.101
11-17 18:30:55.746   756  1052 D PointerIcon: setHoveringSpenIconStyle1 pointerType: 10001iconType:1 flag:0
11-17 18:30:55.746   756  1052 D PointerIcon: setHoveringSpenCustomIcon IconType is same.1
11-17 18:30:55.746   756  1114 I EventHub: Removing device '/dev/input/event9' due to inotify event
11-17 18:30:55.746  5861  5861 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2051 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.samsung.android.app.filterinstaller.PackageIntentReceiver.onReceive:55 android.app.ActivityThread.handleReceiver:2991 
11-17 18:30:55.756  6365  6365 I dumpstate: begin
11-17 18:30:55.756  6365  6365 I dumpstate: open lockfile failed No such file or directory
11-17 18:30:55.756  6365  6365 E dumpstate: Cannot get free space size. So, skip dumpstate.
11-17 18:30:55.766   756   900 F libc    : Fatal signal 7 (SIGBUS), code 2, fault addr 0xa9766028 in tid 900 (ActivityManager)
11-17 18:30:55.776   756  1356 E ActivityManager: checkUser: useridlist=null, currentuser=0
11-17 18:30:55.776   756  1356 E ActivityManager: checkUser: useridlist=null, currentuser=0
11-17 18:30:55.776   756  1356 E ActivityManager: checkUser: useridlist=null, currentuser=0
11-17 18:30:55.776   756  1356 E ActivityManager: checkUser: useridlist=null, currentuser=0
,11-17 18:30:55.786   294   294 E SMD     : DCD ON
,11-17 18:30:55.796  6367  6367 E Zygote  : MountEmulatedStorage()
11-17 18:30:55.796  6367  6367 E Zygote  : v2
11-17 18:30:55.796  6367  6367 I libpersona: KNOX_SDCARD checking this for 10121
11-17 18:30:55.796  6367  6367 I libpersona: KNOX_SDCARD not a persona
,11-17 18:30:55.806   756  1114 I EventHub: Removing device '/dev/input/event10' due to inotify event
,11-17 18:30:55.806   756  1356 I ActivityManager: Start proc com.samsung.android.provider.filterprovider for content provider com.samsung.android.provider.filterprovider/.FilterProvider: pid=6367 uid=10121 gids={50121, 9997, 1023} abi=armeabi-v7a
,11-17 18:30:55.806   756  1577 E ActivityManager: checkUser: useridlist=null, currentuser=0
11-17 18:30:55.806   756  1577 E ActivityManager: checkUser: useridlist=null, currentuser=0
11-17 18:30:55.806   756  1577 E ActivityManager: checkUser: useridlist=null, currentuser=0
11-17 18:30:55.806   756  1577 E ActivityManager: checkUser: useridlist=null, currentuser=0
,11-17 18:30:55.816  1800  1800 E audit_log: File locking failed. error= Bad file number
,11-17 18:30:55.836  6373  6373 E Zygote  : MountEmulatedStorage()
11-17 18:30:55.836  6373  6373 E Zygote  : v2
11-17 18:30:55.836  6373  6373 I libpersona: KNOX_SDCARD checking this for 1000
11-17 18:30:55.836  6373  6373 I libpersona: KNOX_SDCARD not a persona
,11-17 18:30:55.846   756  1577 I ActivityManager: Start proc com.android.keychain for broadcast com.android.keychain/.KeyChainBroadcastReceiver: pid=6373 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1007, 1028, 1015, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,11-17 18:30:55.856  6367  6367 I SELinux : Function: selinux_compare_spd_ram , priority [2] , priority version is VE=SEPF_SM-N9005_5.0_0002
,11-17 18:30:55.856   756  1114 I EventHub: Removing device '/dev/input/event11' due to inotify event
,11-17 18:30:55.866   285   285 I DEBUG   : failed to create /data/tombstones: Read-only file system
11-17 18:30:55.866   285   285 I DEBUG   : failed to open /data/tombstones: No such file or directory
11-17 18:30:55.866   285   285 E         : !@dumpstate -k -t -z -d -o /data/log/dumpstate_app_native -m 756
,11-17 18:30:55.886   337   337 I Zygote  : Process 1622 exited due to signal (7)
11-17 18:30:55.886  6379  6379 I dumpstate: begin
11-17 18:30:55.886  6379  6379 I dumpstate: open lockfile failed No such file or directory
11-17 18:30:55.886  6379  6379 E dumpstate: Cannot get free space size. So, skip dumpstate.
,11-17 18:30:55.886  6373  6373 I SELinux : Function: selinux_compare_spd_ram , priority [2] , priority version is VE=SEPF_SM-N9005_5.0_0002
,11-17 18:30:55.886  6367  6367 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,11-17 18:30:55.886  6373  6373 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,11-17 18:30:55.906   299   791 V AudioPolicyManager: stopInput() input 16
11-17 18:30:55.906   299   791 V AudioPolicyManager: releaseInput() 16
11-17 18:30:55.906   299   791 V AudioPolicyManager: closeInput(16)
,11-17 18:30:55.906   299  6290 V audio_hw_primary: in_standby: enter
,11-17 18:30:55.946   299  6290 V audio_hw_primary: stop_input_stream: enter: usecase(7: audio-record)
11-17 18:30:55.946   299  6290 V audio_hw_primary: disable_audio_route: enter: usecase(7)
11-17 18:30:55.946   299  6290 V audio_hw_primary: disable_audio_route: reset mixer path: audio-record
11-17 18:30:55.946   299  6290 D audio_route: ++++ audio_route_update_mixer ==============
11-17 18:30:55.946   299  6290 D audio_route: Setting mixer control: MultiMedia1 Mixer SLIM_0_TX
11-17 18:30:55.946   299  6290 D audio_route: Setting mixer control: value: 0
,11-17 18:30:55.946   299  6290 D audio_route: ------ audio_route_update_mixer ==============
11-17 18:30:55.946   299  6290 V audio_hw_primary: disable_audio_route: exit
11-17 18:30:55.946   299  6290 V audio_hw_primary: disable_snd_device: snd_device(128: vr-main-mic)
11-17 18:30:55.946   299  6290 D audio_route: ++++ audio_route_update_mixer ==============
11-17 18:30:55.946   299  6290 D audio_route: Setting mixer control: ADC1 Volume
11-17 18:30:55.946   299  6290 D audio_route: Setting mixer control: value: 0
11-17 18:30:55.946   299  6290 D audio_route: Setting mixer control: DEC6 Volume
11-17 18:30:55.946   299  6290 D audio_route: Setting mixer control: value: 0
,11-17 18:30:55.946   299  6290 D audio_route: Setting mixer control: SLIM TX7 MUX, value: 0
,11-17 18:30:55.946   299  6290 D audio_route: Setting mixer control: AIF1_CAP Mixer SLIM TX7
11-17 18:30:55.946   299  6290 D audio_route: Setting mixer control: value: 0
,11-17 18:30:55.946   299  6290 D audio_route: Setting mixer control: DEC6 MUX, value: 0
,11-17 18:30:55.946   299  6290 D audio_route: ------ audio_route_update_mixer ==============
11-17 18:30:55.946   299  6290 V audio_hw_primary: stop_input_stream: exit: status(0)
11-17 18:30:55.946   299  6290 V audio_hw_primary: in_standby: exit:  status(0)
,11-17 18:30:55.946   299   791 V audio_hw_primary: adev_close_input_stream
11-17 18:30:55.946   299   791 V audio_hw_primary: in_standby: enter
11-17 18:30:55.946   299   791 V audio_hw_primary: in_standby: exit:  status(0)
11-17 18:30:55.946   299   791 E audio_hw_primary: adev_close_input_stream, set jack_in to null
,11-17 18:30:55.946   299   791 V AudioPolicyManager: releaseInput() exit
11-17 18:30:55.946   756  1114 I EventHub: Removing device '/dev/input/event12' due to inotify event
11-17 18:30:55.946   756  1114 I EventHub: Removing device '/dev/input/event13' due to inotify event
11-17 18:30:55.946  1800  1800 E audit_log: File locking failed. error= Bad file number
11-17 18:30:55.946   756  1122 E MotionRecognitionService: Motion Thread--
11-17 18:30:55.946   756  1122 D MotionRecognitionService: try start thread -1
11-17 18:30:55.946   756  1122 E MotionRecognitionService: Motion Thread++
,11-17 18:30:55.946   756  1057 E libsuspend: Error reading from /sys/power/wakeup_count: Interrupted system call
,11-17 18:30:56.096   306   306 E installd: eof
11-17 18:30:56.096   306   306 E installd: failed to read size
11-17 18:30:56.096   306   306 I installd: closing connection
,11-17 18:30:56.116  6347  6347 E AndroidRuntime: Error reporting crash
11-17 18:30:56.116  6347  6347 E AndroidRuntime: android.os.DeadObjectException
11-17 18:30:56.116  6347  6347 E AndroidRuntime: 	at android.os.BinderProxy.transactNative(Native Method)
11-17 18:30:56.116  6347  6347 E AndroidRuntime: 	at android.os.BinderProxy.transact(Binder.java:496)
11-17 18:30:56.116  6347  6347 E AndroidRuntime: 	at android.app.ActivityManagerProxy.handleApplicationCrash(ActivityManagerNative.java:4656)
11-17 18:30:56.116  6347  6347 E AndroidRuntime: 	at com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException(RuntimeInit.java:95)
11-17 18:30:56.116  6347  6347 E AndroidRuntime: 	at java.lang.ThreadGroup.uncaughtException(ThreadGroup.java:693)
11-17 18:30:56.116  6347  6347 E AndroidRuntime: 	at java.lang.ThreadGroup.uncaughtException(ThreadGroup.java:690)
11-17 18:30:56.116  6347  6347 I Process : Sending signal. PID: 6347 SIG: 9
,11-17 18:30:56.116  6367  6367 F libc    : Fatal signal 7 (SIGBUS), code 2, fault addr 0x7428c9c3 in tid 6367 (.filterprovider)
,11-17 18:30:56.116  1316  3056 E WifiManager: Channel connection lost
,11-17 18:30:56.116   299   687 W AudioFlinger: power manager service died !!!
11-17 18:30:56.116   299   687 W AudioCache: clearPowerManager -mWakeLockCount is 0, failed to releaseWakeLock function
11-17 18:30:56.116  1400  1412 W Sensors : sensorservice died [0xaf1c9a00]
11-17 18:30:56.116  1481  1506 W Sensors : sensorservice died [0xaf118380]
11-17 18:30:56.116   254  6059 I SurfaceFlinger: restart the boot-animation @ binderDied
11-17 18:30:56.116   254   254 D SurfaceFlinger: Set power mode=2, type=0 flinger=0xb6962000
11-17 18:30:56.116   254   254 D SurfaceFlinger: Screen type=0 is already mode=2
,11-17 18:30:56.116  1184  1217 W Sensors : sensorservice died [0xaf135200]
11-17 18:30:56.116  1437  1457 W Sensors : sensorservice died [0xaf19a300]
11-17 18:30:56.116   254  1923 I SurfaceFlinger: id=2 Removed GocusedStac (4/8)
,11-17 18:30:56.116  1871  1963 W Sensors : sensorservice died [0xaf113a80]
,11-17 18:30:56.116   254  1923 I SurfaceFlinger: id=3 Removed EimLayer (0/7)
,11-17 18:30:56.116  1771  1783 W Sensors : sensorservice died [0xaf1d83c0]
11-17 18:30:56.116   254   328 I SurfaceFlinger: id=7 Removed TtatusBar (5/6)
11-17 18:30:56.116   254   332 I SurfaceFlinger: id=5 Removed JmageWallpa (2/5)
11-17 18:30:56.116   254   332 I SurfaceFlinger: id=5 Removed JmageWallpa (-2/5)
11-17 18:30:56.116   254   332 I SurfaceFlinger: id=14 Removed Mauncher (2/4)
11-17 18:30:56.116   254   332 I SurfaceFlinger: id=7 Removed TtatusBar (-2/4)
11-17 18:30:56.116   254   332 I SurfaceFlinger: id=9 Removed Ieads Up (3/3)
11-17 18:30:56.116   254   328 I SurfaceFlinger: id=9 Removed Ieads Up (-2/3)
11-17 18:30:56.116   254   328 I SurfaceFlinger: id=10 Removed EimLayer (1/2)
11-17 18:30:56.116   254   328 I SurfaceFlinger: id=11 Removed EimLayer (1/1)
11-17 18:30:56.116   254   328 I SurfaceFlinger: id=14 Removed Mauncher (-2/1)
11-17 18:30:56.116   254  1923 I SurfaceFlinger: id=4 Removed EimLayer (0/0)
11-17 18:30:56.116   254  1923 I SurfaceFlinger: id=10 Removed EimLayer (-2/0)
11-17 18:30:56.116   254  1923 I SurfaceFlinger: id=11 Removed EimLayer (-2/0)
11-17 18:30:56.116   254  1923 I SurfaceFlinger: id=2 Removed GocusedStac (-2/0)
11-17 18:30:56.116   254  1923 I SurfaceFlinger: id=3 Removed EimLayer (-2/0)
11-17 18:30:56.116   254  1923 I SurfaceFlinger: id=4 Removed EimLayer (-2/0)
,11-17 18:30:56.116  1421  1668 W Sensors : sensorservice died [0xaf115280]
11-17 18:30:56.116  1570  2734 E WifiManager: Channel connection lost
11-17 18:30:56.116  1421  1819 E WifiManager: Channel connection lost
,11-17 18:30:56.126  1481  1797 E WifiManager: Channel connection lost
,11-17 18:30:56.126   252   252 I ServiceManager: service 'sec_analytics' died
11-17 18:30:56.126   252   252 I ServiceManager: service 'mount' died
11-17 18:30:56.126   252   252 I ServiceManager: service 'lock_settings' died
11-17 18:30:56.126   252   252 I ServiceManager: service 'device_policy' died
11-17 18:30:56.126   252   252 I ServiceManager: service 'harmony_eas_service' died
11-17 18:30:56.126   252   252 I ServiceManager: service 'sdp' died
11-17 18:30:56.126   252   252 I ServiceManager: service 'log_manager_service' died
11-17 18:30:56.126   252   252 I ServiceManager: service 'application_policy' died
11-17 18:30:56.126   252   252 I ServiceManager: service 'wifi_policy' died
11-17 18:30:56.126   252   252 I ServiceManager: service 'phone_restriction_policy' died
11-17 18:30:56.126   252   252 I ServiceManager: service 'remoteinjection' died
11-17 18:30:56.126   252   252 I ServiceManager: service 'mum_container_policy' died
11-17 18:30:56.126   252   252 I ServiceManager: service 'enterprise_billing_policy' died
11-17 18:30:56.126   252   252 I ServiceManager: service 'knox_timakeystore_policy' died
11-17 18:30:56.126   252   252 I ServiceManager: service 'backup' died
11-17 18:30:56.126   252   252 I ServiceManager: service 'appwidget' died
11-17 18:30:56.126   252   252 I ServiceManager: service 'voiceinteraction' died
11-17 18:30:56.126   252   252 I ServiceManager: service 'SecExternalDisplayService' died
11-17 18:30:56.126   252   252 I ServiceManager: service 'diskstats' died
11-17 18:30:56.126   252   252 I ServiceManager: service 'mDNIe' died
11-17 18:30:56.126   252   252 I ServiceManager: service 'spengestureservice' died
11-17 18:30:56.126   252   252 I ServiceManager: service 'input_method' died
11-17 18:30:56.126   252   252 I ServiceManager: service 'accessibility' died
11-17 18:30:56.126   252   252 I ServiceManager: service 'motion_recognition' died
11-17 18:30:56.126   252   252 I ServiceManager: service 'cover' died
11-17 18:30:56.126   252   252 I ServiceManager: service 'enterprise_policy' died
11-17 18:30:56.126   252   252 I ServiceManager: service 'statusbar' died
11-17 18:30:56.126   252   252 I ServiceManager: service 'clipboard' died
11-17 18:30:56.126   252   252 I ServiceManager: service 'clipboardEx' died
11-17 18:30:56.126   252   252 I ServiceManager: service 'network_management' died
11-17 18:30:56.126   252   252 I ServiceManager: service 'ABTPersistenceService' died
11-17 18:30:56.126   252   252 I ServiceManager: service 'textservices' died
11-17 18:30:56.126   252   252 I ServiceManager: service 'network_score' died
11-17 18:30:56.126   252   252 I ServiceManager: service 'netstats' died
11-17 18:30:56.126   252   252 I ServiceManager: service 'netpolicy' died
11-17 18:30:56.126   252   252 I ServiceManager: service 'wifip2p' died
11-17 18:30:56.126   252   252 I ServiceManager: service 'wifi' died
11-17 18:30:56.126   252   252 I ServiceManager: service 'msapwifi' died
11-17 18:30:56.126   252   252 I ServiceManager: service 'wifiscanner' died
11-17 18:30:56.126   252   252 I ServiceManager: service 'rttmanager' died
11-17 18:30:56.126   252   252 I ServiceManager: service 'connectivity' died
11-17 18:30:56.126   252   252 I ServiceManager: service 'sb_service' died
11-17 18:30:56.126   252   252 I ServiceManager: service 'servicediscovery' died
11-17 18:30:56.126   252   252 I ServiceManager: service 'updatelock' died
11-17 18:30:56.126   252   252 I ServiceManager: service 'notification' died
11-17 18:30:56.126   252   252 I ServiceManager: service 'devicestoragemonitor' died
11-17 18:30:56.126   252   252 I ServiceManager: service 'location' died
11-17 18:30:56.126   252   252 I ServiceManager: service 'country_detector' died
11-17 18:30:56.126   252   252 I ServiceManager: service 'search' died
11-17 18:30:56.126   252   252 I ServiceManager: service 'quickconnect' died
11-17 18:30:56.126   252   252 I ServiceManager: service 'samplingprofiler' died
11-17 18:30:56.126   252   252 I ServiceManager: service 'commontim,e_management' died
11-17 18:30:56.126   252   252 I ServiceManager: service 'dreams' died
11-17 18:30:56.126   252   252 I ServiceManager: service 'assetatlas' died
11-17 18:30:56.126   252   252 I ServiceManager: service 'print' died
11-17 18:30:56.126   252   252 I ServiceManager: service 'restrictions' died
11-17 18:30:56.126   252   252 I ServiceManager: service 'media_session' died
11-17 18:30:56.126   252   252 I ServiceManager: service 'media_router' died
11-17 18:30:56.126   252   252 I ServiceManager: service 'trust' died
11-17 18:30:56.126   252   252 I ServiceManager: service 'fingerprint' died
11-17 18:30:56.126   252   252 I ServiceManager: service 'launcherapps' died
11-17 18:30:56.126   252   252 I ServiceManager: service 'voip' died
11-17 18:30:56.126   252   252 I ServiceManager: service 'media_projection' died
11-17 18:30:56.126   252   252 I ServiceManager: service 'imms' died
11-17 18:30:56.126   252   252 I ServiceManager: service 'dropbox' died
11-17 18:30:56.126   252   252 I ServiceManager: service 'wallpaper' died
11-17 18:30:56.126   252   252 I ServiceManager: service 'audio' died
11-17 18:30:56.126   252   252 I ServiceManager: service 'DockObserver' died
11-17 18:30:56.126   252   252 I ServiceManager: service 'usb' died
11-17 18:30:56.126   252   252 I ServiceManager: service 'serial' died
11-17 18:30:56.126   252   252 I ServiceManager: service 'uimode' died
11-17 18:30:56.126  4807  4815 W Sensors : sensorservice died [0xaf139280]
11-17 18:30:56.126   252   252 I ServiceManager: service 'jobscheduler' died
11-17 18:30:56.126   252   252 I ServiceManager: service 'package' died
11-17 18:30:56.126   252   252 I ServiceManager: service 'hardware' died
11-17 18:30:56.126   252   252 I ServiceManager: service 'context_aware' died
11-17 18:30:56.126   252   252 I ServiceManager: service 'scontext' died
11-17 18:30:56.126   252   252 I ServiceManager: service 'barbeam' died
11-17 18:30:56.126   252   252 I ServiceManager: service 'multiwindow_facade' died
11-17 18:30:56.126   252   252 I ServiceManager: service 'window' died
11-17 18:30:56.126   252   252 I ServiceManager: service 'input' died
11-17 18:30:56.126   252   252 I ServiceManager: service 'enterprise_license_policy' died
11-17 18:30:56.126   252   252 I ServiceManager: service 'tactileassist' died
11-17 18:30:56.126   252   252 I ServiceManager: service 'bluetooth_manager' died
11-17 18:30:56.126   252   252 I ServiceManager: service 'bluetooth_secure_mode_manager' died
11-17 18:30:56.126   252   252 I ServiceManager: service 'rcp' died
11-17 18:30:56.126   252   252 I ServiceManager: service 'account' died
11-17 18:30:56.126   252   252 I ServiceManager: service 'content' died
11-17 18:30:56.126   252   252 I ServiceManager: service 'DirEncryptService' died
11-17 18:30:56.126   252   252 I ServiceManager: service 'ReactiveService' died
11-17 18:30:56.126   252   252 I ServiceManager: service 'sedenial' died
11-17 18:30:56.126   252   252 I ServiceManager: service 'vibrator' died
11-17 18:30:56.126   252   252 I ServiceManager: service 'tima' died
11-17 18:30:56.126   252   252 I ServiceManager: service 'cepproxyks' died
11-17 18:30:56.126   252   252 I ServiceManager: service 'CustomFrequencyManagerService' died
11-17 18:30:56.126   252   252 I ServiceManager: service 'samsung.smartfaceservice' died
11-17 18:30:56.126   252   252 I ServiceManager: service 'consumer_ir' died
11-17 18:30:56.126   252   252 I ServiceManager: service 'alarm' died
11-17 18:30:56.126   252   252 I ServiceManager: service 'scheduling_policy' died
11-17 18:30:56.126   252   252 I ServiceManager: service 'telephony.registry' died
11-17 18:30:56.126   252   252 I ServiceManager: service 'webviewupdate' died
,11-17 18:30:56.126   252   252 I ServiceManager: service 'entropy' died
11-17 18:30:56.126   252   252 I ServiceManager: service 'user' died
11-17 18:30:56.126   252   252 I ServiceManager: service 'cpuinfo' died
11-17 18:30:56.126   252   252 I ServiceManager: service 'permission' died
11-17 18:30:56.126   252   252 I ServiceManager: service 'usagestats' died
11-17 18:30:56.126   252   252 I ServiceManager: service 'activity' died
11-17 18:30:56.126   252   252 I ServiceManager: service 'gfxinfo' died
,11-17 18:30:56.126   252   252 I ServiceManager: service 'dbinfo' died
11-17 18:30:56.126   252   252 I ServiceManager: service 'battery' died
11-17 18:30:56.126   252   252 I ServiceManager: service 'procstats' died
11-17 18:30:56.126   252   252 I ServiceManager: service 'meminfo' died
11-17 18:30:56.126   252   252 I ServiceManager: service 'edmnativehelper' died
11-17 18:30:56.126   252   252 I ServiceManager: service 'mdm.remotedesktop' died
11-17 18:30:56.126   252   252 I ServiceManager: service 'sensorservice' died
11-17 18:30:56.126   252   252 I ServiceManager: service 'batterystats' died
11-17 18:30:56.126   252   252 I ServiceManager: service 'appops' died
11-17 18:30:56.126   252   252 I ServiceManager: service 'power' died
,11-17 18:30:56.126   252   252 I ServiceManager: service 'display' died
11-17 18:30:56.126   252   252 I ServiceManager: service 'persona_policy' died
11-17 18:30:56.126   252   252 I ServiceManager: service 'SEAMService' died
11-17 18:30:56.126   252   252 I ServiceManager: service 'persona' died
11-17 18:30:56.126  6373  6373 F libc    : Fatal signal 7 (SIGBUS), code 2, fault addr 0x7428c9c3 in tid 6373 (ndroid.keychain)
,11-17 18:30:56.136  1184  1559 E WifiManager: Channel connection lost
,11-17 18:30:56.136  5861  6366 E ActivityThread: Failed to find provider info for com.samsung.android.provider.filterprovider
,11-17 18:30:56.136  5861  6366 E ActivityThread: Failed to find provider info for com.samsung.android.provider.filterprovider
,11-17 18:30:56.136  5861  6366 E AndroidRuntime: FATAL EXCEPTION: FilterPackageServiceHandler
11-17 18:30:56.136  5861  6366 E AndroidRuntime: Process: com.samsung.android.app.filterinstaller, PID: 5861
11-17 18:30:56.136  5861  6366 E AndroidRuntime: java.lang.IllegalArgumentException: Unknown URL content://com.samsung.android.provider.filterprovider/packages/com.example.hello
11-17 18:30:56.136  5861  6366 E AndroidRuntime: 	at android.content.ContentResolver.delete(ContentResolver.java:1305)
11-17 18:30:56.136  5861  6366 E AndroidRuntime: 	at com.samsung.android.app.filterinstaller.FilterUninstaller.removeFromDB(FilterUninstaller.java:52)
11-17 18:30:56.136  5861  6366 E AndroidRuntime: 	at com.samsung.android.app.filterinstaller.FilterUninstaller.uninstallFilters(FilterUninstaller.java:43)
11-17 18:30:56.136  5861  6366 E AndroidRuntime: 	at com.samsung.android.app.filterinstaller.FilterPackageService$ServiceHandler.handleMessage(FilterPackageService.java:149)
11-17 18:30:56.136  5861  6366 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-17 18:30:56.136  5861  6366 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:145)
11-17 18:30:56.136  5861  6366 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,11-17 18:30:56.136  5861  6366 E AndroidRuntime: Error reporting crash
11-17 18:30:56.136  5861  6366 E AndroidRuntime: android.os.DeadObjectException
11-17 18:30:56.136  5861  6366 E AndroidRuntime: 	at android.os.BinderProxy.transactNative(Native Method)
11-17 18:30:56.136  5861  6366 E AndroidRuntime: 	at android.os.BinderProxy.transact(Binder.java:496)
11-17 18:30:56.136  5861  6366 E AndroidRuntime: 	at android.app.ActivityManagerProxy.handleApplicationCrash(ActivityManagerNative.java:4656)
11-17 18:30:56.136  5861  6366 E AndroidRuntime: 	at com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException(RuntimeInit.java:95)
11-17 18:30:56.136  5861  6366 E AndroidRuntime: 	at java.lang.ThreadGroup.uncaughtException(ThreadGroup.java:693)
11-17 18:30:56.136  5861  6366 E AndroidRuntime: 	at java.lang.ThreadGroup.uncaughtException(ThreadGroup.java:690)
11-17 18:30:56.136  5861  6366 I Process : Sending signal. PID: 5861 SIG: 9
,11-17 18:30:56.216   285   285 I DEBUG   : failed to create /data/tombstones: Read-only file system
11-17 18:30:56.216   285   285 I DEBUG   : failed to open /data/tombstones: No such file or directory
11-17 18:30:56.216   285   285 E         : !@dumpstate -k -t -z -d -o /data/log/dumpstate_app_native -m 6367
,11-17 18:30:56.236  6402  6402 I dumpstate: begin
11-17 18:30:56.236  6402  6402 I dumpstate: open lockfile failed No such file or directory
11-17 18:30:56.236  6402  6402 E dumpstate: Cannot get free space size. So, skip dumpstate.
,11-17 18:30:56.286  1800  1800 E audit_log: File locking failed. error= Bad file number
,11-17 18:30:56.336   285   285 I DEBUG   : failed to create /data/tombstones: Read-only file system
11-17 18:30:56.336   285   285 I DEBUG   : failed to open /data/tombstones: No such file or directory
11-17 18:30:56.336   285   285 E         : !@dumpstate -k -t -z -d -o /data/log/dumpstate_app_native -m 6373
,11-17 18:30:56.356   337   337 I Zygote  : Process 6367 exited due to signal (7)
,11-17 18:30:56.366   254   254 I SurfaceFlinger: Disp[0] Orientation 0=>0
,11-17 18:30:56.376   254   254 E qdoverlay: Failed to call ioctl MSMFB_OVERLAY_UNSET err=Operation not permitted
11-17 18:30:56.376   254   254 E qdoverlay: MdpCtrl close error in unset
,11-17 18:30:56.396   254   539 I qdhwcomposer: handle_blank_event: dpy:0 panel power state: 0
11-17 18:30:56.396   254   254 E qdoverlay: Failed to call ioctl MSMFB_OVERLAY_UNSET err=Operation not permitted
11-17 18:30:56.396   254   254 E qdoverlay: MdpCtrl close error in unset
11-17 18:30:56.396   254   254 E qdoverlay: Failed to call ioctl MSMFB_OVERLAY_UNSET err=Operation not permitted
11-17 18:30:56.396   254   254 E qdoverlay: MdpCtrl close error in unset
11-17 18:30:56.396   254   254 E qdoverlay: Failed to call ioctl MSMFB_OVERLAY_UNSET err=Operation not permitted
11-17 18:30:56.396   254   254 E qdoverlay: MdpCtrl close error in unset
,11-17 18:30:56.396  6404  6404 I dumpstate: begin
,11-17 18:30:56.396  6404  6404 I dumpstate: open lockfile failed No such file or directory
11-17 18:30:56.396  6404  6404 E dumpstate: Cannot get free space size. So, skip dumpstate.
,11-17 18:30:56.446  1800  1800 E audit_log: File locking failed. error= Bad file number
```
