#### Test 8504691174f7534_thali04_samsung-SM-G935F Logs


```
--------- beginning of system
,09-15 12:02:59.354  3410  4952 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
09-15 12:02:59.354  3410  4952 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4354, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303413, invalid charger:0, maxChargingCurrent:0
09-15 12:02:59.354  3410  4952 D BatteryService: online:4, current avg:142, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:137
09-15 12:02:59.354  3410  3410 D BatteryService: Sending ACTION_BATTERY_CHANGED.
09-15 12:02:59.364  3410  3410 I MotionRecognitionService: Plugged
09-15 12:02:59.364  3410  3410 D MotionRecognitionService:   cableConnection= 1
09-15 12:02:59.364  3410  3410 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
09-15 12:02:59.364  3410  3410 D MotionRecognitionService: skip setTransmitPower. 
--------- beginning of main
09-15 12:02:59.374  3410  3862 D WifiController: ApOrStaEnabledState  msg.what= 155652
09-15 12:02:59.374  3950  3950 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
09-15 12:02:59.374  3950  3950 D KeyguardUpdateMonitor: handleBatteryUpdate
09-15 12:02:59.374  3950  3950 D PowerUI : priorPlugType = 2 mPlugType =  2
09-15 12:02:59.404  5070  5070 D CommonServiceConfiguration: getStringValueSetting
09-15 12:02:59.404  5031  5031 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
09-15 12:02:59.404  3950  3950 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
09-15 12:02:59.404  5031  5431 D HeadsetStateMachine: Disconnected process message: 10, size: 0
09-15 12:02:59.404  3950  3950 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
09-15 12:02:59.414  5070  5070 D BatteryMonitor: new battery level: 100
09-15 12:02:59.824  9947  9947 I FIPS_bssl: FIPS approved mode (1) | 9947 | app_process
09-15 12:02:59.834  9947  9947 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
09-15 12:02:59.834  9947  9947 D AndroidRuntime: CheckJNI is OFF
09-15 12:02:59.834  9947  9947 D AndroidRuntime: readGMSProperty: start
09-15 12:02:59.834  9947  9947 D AndroidRuntime: readGMSProperty: already setted!!
09-15 12:02:59.834  9947  9947 D AndroidRuntime: propertySet: couldn't set property (it is from app)
09-15 12:02:59.834  9947  9947 D AndroidRuntime: readGMSProperty: could not set the property(default)!!
09-15 12:02:59.834  9947  9947 D AndroidRuntime: readGMSProperty: end
09-15 12:02:59.834  9947  9947 D AndroidRuntime: addProductProperty: start
09-15 12:02:59.854  9947  9947 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
09-15 12:02:59.874  9947  9947 I Radio-JNI: register_android_hardware_Radio DONE
09-15 12:02:59.884  9947  9947 E AffinityControl: AffinityControl: registerfunction enter
09-15 12:02:59.884  9947  9947 D AndroidRuntime: Calling main entry com.android.commands.am.Am
09-15 12:02:59.924  3410  4951 D VirtualScreenPolicy: applyVirtualScreenAttrs attrs=VirtualScreenAttrs{mDisplayId=0, mBaseDisplayId=0, mBaseActivity=false}
09-15 12:02:59.924  3410  4951 W ResourcesManager: getTopLevelResources: /data/app/com.test.thalitest-1/base.apk / 1.0 running in null rsrc of package com.test.thalitest
09-15 12:02:59.944  3410  4951 D ResourcesManager: For user 0 new overlays fetched Null
09-15 12:02:59.944  3410  4951 D GameManagerService: identifyGamePackage. com.test.thalitest
09-15 12:02:59.944  3410  4951 D MultiWindowPolicy: Gamemode - return 0,  when calling  identifyForegroundApp(com.test.thalitest)
09-15 12:02:59.944  3410  4951 D CustomFrequencyManagerService: acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1872000  uid : 1000  pid : 3410  pkgName : ACTIVITY_RESUME_BOOSTER@7
09-15 12:02:59.954  3410  4951 D ActivityManager: mDVFSHelper.acquire()
09-15 12:02:59.954  3410  4951 D FocusedStackFrame: Set to : 0
09-15 12:02:59.954  3410  4951 V WindowManager: addAppToken: AppWindowToken{d0f894eae token=Token{89b6b29 ActivityRecord{bc890b0 u0 com.test.thalitest/.MainActivity t75}}} to stack=2 task=75 at 0
09-15 12:02:59.954  4300  4300 D Launcher: onPause, Launcher: 198492302
09-15 12:02:59.954  4300  4300 D Launcher.HomeView: onPause
09-15 12:02:59.954  3410  3572 D SecWifiDisplayUtil: Metadata value : SecSettings2
09-15 12:02:59.954  4300  4300 D Launcher.Workspace: exitWidgetResizeMode. isClearResizeFrame is false
09-15 12:02:59.954  3410  4951 D InputDispatcher: Focused application set to: xxxx
09-15 12:02:59.954  3410  3572 I InjectionManager: Inside getClassLibPath caller 
09-15 12:02:59.954  3410  4951 D InputDispatcher: Focus left window: 4300
09-15 12:02:59.954  9947  9947 D AndroidRuntime: Shutting down VM
09-15 12:02:59.954  3410  3572 D ViewRootImpl: #1 mView = com.android.internal.policy.PhoneWindow$DecorView{cdbde47 V.E...... R.....ID 0,0-0,0}
09-15 12:02:59.954  3410  3572 D ISSUE_DEBUG: InputChannelName : 4aef79d Starting com.test.thalitest
09-15 12:02:59.964  3410  3572 D PointerIcon: setMouseIconStyle1 pointerType: 1001 iconType:101 flag:0 pid:3410 uid:1000
09-15 12:02:59.964  3410  3572 D PointerIcon: setMouseCustomIcon IconType is same.101
09-15 12:02:59.964  9956  9956 E Zygote  : v2
09-15 12:02:59.964  9956  9956 I libpersona: KNOX_SDCARD checking this for 10177
09-15 12:02:59.964  9956  9956 I libpersona: KNOX_SDCARD not a persona
09-15 12:02:59.964  3410  3971 I ActivityManager: Start proc 9956:com.test.thalitest/u0a177 for activity com.test.thalitest/.MainActivity
09-15 12:02:59.964  9956  9956 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0013
09-15 12:02:59.964  9956  9956 E Zygote  : accessInfo : 0
09-15 12:02:59.964  9956  9956 W SELinux : SELinux: seapp_context_lookup: seinfo=default, level=s0:c512,c768, pkgname=com.test.thalitest 
09-15 12:02:59.974  3009  3009 I SurfaceFlinger: id=21 createSurf (1x1),1 flag=404, uhalitest
09-15 12:02:59.974  4431  4445 W SearchService: Abort, client detached.
09-15 12:02:59.974  4431  9930 I DeviceStateChecker: DeviceStateChecker cancelled
09-15 12:02:59.974  4431  4431 I MicroDetector: Keeping mic open: false
09-15 12:02:59.974  4431  4431 I MicrophoneInputStream: mic_close com.google.android.apps.gsa.speech.audio.ae@bbd1015
09-15 12:02:59.974  4431  9932 E AudioRecord-JNI: Error -4 during AudioRecord native read
09-15 12:02:59.974  3162  3162 I APM::AudioPolicyManager: stopInput() input 27
09-15 12:02:59.974  3162  9934 I audio_hw_primary: do_in_standby : in->standby 0
09-15 12:02:59.984  4431  9918 I MicroRecognitionRunner: Stopping hotword detection.
09-15 12:02:59.984  4431  9931 I MicroRecognitionRunner: Detection finished
09-15 12:02:59.984  3162  9934 V audio_hw_primary: select_devices output_scenario:-1 input_scenario:-1 out_snd_device 0x0 in_snd_device:0x0
09-15 12:02:59.984  3162  9934 I audio_route: 
09-15 12:02:59.984  3162  9934 I audio_route: > audio_route_reset :
09-15 12:02:59.984  3162  9934 I audio_route: 
09-15 12:02:59.984  3162  9934 I audio_route: > audio_route_update_mixer : +
09-15 12:02:59.984  3410  3541 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{e5f7412 u0 update-hint qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{8de53ff 4431:com.google.android.googlequicksearchbox:search/u0a72}
09-15 12:02:59.994  3410  3572 D ViewRootImpl: MSG_RESIZED_REPORT: ci=Rect(0, 96 - 0, 0) vi=Rect(0, 96 - 0, 0) or=1
09-15 12:02:59.994  3410  3817 V AlarmManager: Expired Alarm result :8
09-15 12:02:59.994  9956  9956 D TimaKeyStoreProvider: TimaSignature is unavailable
09-15 12:02:59.994  9956  9956 D ActivityThread: Added TimaKeyStore provider
09-15 12:03:00.004  3410  4248 V WindowOrientationListener: setCurrentAppOrientation :-1
09-15 12:03:00.004  3410  4248 V WindowOrientationListener: OrientationSensorJudge.getProposedRotation, Rotation: -1
09-15 12:03:00.004  3410  4248 V WindowManager: rotationForOrientationLw(orient=-1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false mMobileKeyboardEnabled=false displayId=0
09-15 12:03:00.004  3410  4248 V WindowOrientationListener: OrientationSensorJudge.getProposedRotation, Rotation: -1
09-15 12:03:00.004  3410  4248 D ActivityManager:  Launching com.test.thalitest, updated priority
09-15 12:03:00.014  3410  3572 V WindowStateAnimator: Finishing drawing window Window{4aef79d u0 d0 Starting com.test.thalitest}: mDrawState=DRAW_PENDING
09-15 12:03:00.014  3950  3950 D KeyguardUpdateMonitor: received broadcast android.intent.action.TIME_TICK
09-15 12:03:00.014  3950  3950 D KeyguardUpdateMonitor: handleTimeUpdate
09-15 12:03:00.014  3162  9934 I audio_route: > audio_route_update_mixer : changed(5) -
09-15 12:03:00.014  3162  9934 I audio_hw_primary: select_devices - 
09-15 12:03:00.014  3162  4185 V audio_hw_primary: stop_voice_note_recording
09-15 12:03:00.014  3162  4185 E audio_hw_primary: adev_close_input_stream, set jack_in to null
09-15 12:03:00.014  3009  3009 D libEGL  : eglInitialize EGLDisplay = 0x7ff285be68
09-15 12:03:00.014  9956  9956 D ContextRelationManager: ContextRelationManager() : FEATURE_ENABLED=true
09-15 12:03:00.014  9956  9956 D RelationGraph: garbageCollect()
09-15 12:03:00.024  9956  9956 W ResourcesManager: getTopLevelResources: /data/app/com.test.thalitest-1/base.apk / 1.0 running in com.test.thalitest rsrc of package com.test.thalitest
09-15 12:03:00.024  3410  4248 I InjectionManagerService -AppFeature: getCoreFeaturePkgList :[]
09-15 12:03:00.024  9956  9956 I InjectionManager: Inside getClassLibPath + mLibMap{0=, 1=}
09-15 12:03:00.024  3410  3410 D GameManagerService: NotifyRunnable. pkg: com.test.thalitest, type: 4, isMinimized: false, isTunableApp: false
09-15 12:03:00.024  3009  3017 D libEGL  : eglTerminate EGLDisplay = 0x7fb1d80e78
09-15 12:03:00.024  3009  3017 D libEGL  : eglTerminate EGLDisplay = 0x7fb1d80e78
09-15 12:03:00.024  3410  3541 V MARsPolicyManager: updatePackagesScore PackageInfo name -- com.test.thalitest
09-15 12:03:00.024  3950  3950 D Clock   : received broadcast android.intent.action.TIME_TICK
09-15 12:03:00.024  9956  9956 D ResourcesManager: For user 0 new overlays fetched Null
09-15 12:03:00.034  3410  3542 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=Window{4aef79d u0 d0 Starting com.test.thalitest}
09-15 12:03:00.034  3410  3856 D NetworkPolicy: isUidForegroundLocked: 10177, mScreenOn: true, uidstate: 2, mProxSensorScreenOff: false
09-15 12:03:00.034  3410  6444 D GameManagerService: identifyGamePackage. com.test.thalitest
09-15 12:03:00.034  3009  3017 I SurfaceFlinger: Modify Choreographer's phase offset to 0
09-15 12:03:00.034  9956  9956 I InjectionManager: Inside getClassLibPath caller 
09-15 12:03:00.034  3009  4466 I SurfaceFlinger: Modify SurfaceFlinger's phase offset to 0
09-15 12:03:00.034  3410  6444 D GameManagerService: identifyGamePackage. com.test.thalitest
09-15 12:03:00.034  3410  6444 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
09-15 12:03:00.034  3410  6444 D GameManagerService: identifyGamePackage. com.test.thalitest
09-15 12:03:00.044  9956  9956 D InjectionManager: InjectionManager
09-15 12:03:00.044  9956  9956 D InjectionManager: fillFeatureStoreMap com.test.thalitest
09-15 12:03:00.044  9956  9956 I InjectionManager: Constructor com.test.thalitest, Feature store :{}
09-15 12:03:00.044  9956  9956 I InjectionManager: featureStore :{}
09-15 12:03:00.044  3410  6444 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
09-15 12:03:00.044  9956  9956 W ResourcesManager: getTopLevelResources: /data/app/com.test.thalitest-1/base.apk / 1.0 running in com.test.thalitest rsrc of package com.test.thalitest
09-15 12:03:00.044  9956  9956 D RelationGraph: garbageCollect()
09-15 12:03:00.044  3410  6444 D GameManagerService: identifyGamePackage. com.test.thalitest
09-15 12:03:00.044  3410  6444 D GameManagerService: identifyGamePackage. com.test.thalitest
09-15 12:03:00.044  9956  9956 W ResourcesManager: getTopLevelResources: /data/app/com.test.thalitest-1/base.apk / 1.0 running in com.test.thalitest rsrc of package com.test.thalitest
09-15 12:03:00.064  3950  3950 D DateView: received broadcast android.intent.action.TIME_TICK
09-15 12:03:00.064  9956  9956 I WebViewFactory: Loading com.google.android.webview version 49.0.2623.105 (code 262310550)
09-15 12:03:00.074  4645  4645 D [Weather Widget]  WeatherService: {[EC3334F14841398C8B464A72D0E61AB7C564889C89112557F2146D56794659083956C77974A4825103AB5C5D4AC85EDAA24236388AC138058106446B92A35777]}
09-15 12:03:00.074  4645  4645 D [Weather Widget]  : {[3AE6950019B083611567B0F9442DB03EEFA9050249635C043F7E254E316C2550]}
09-15 12:03:00.074  4645  4645 D [Weather Widget]  : {[3AE6950019B083611567B0F9442DB03EAB01DC5C99149A39F887E17599325AFBFF089086AA9902184ADA25758C536FE2]}
09-15 12:03:00.074  4645  4645 D [Weather Widget]  : {[3AE6950019B083611567B0F9442DB03EFF0B905BDFF72B69FB632A6CB072B41F95D2E6F4F84443284E97F40042D431D8350388453A923ABD8469D82798FA7548]}
09-15 12:03:00.074  4645  4645 D [Weather Widget]  : {[A1AF0F6A1A65A89C43D705938923D0FEFB71880C4E84718DA0A3E1F383E54FB27A4284D9BEDF7BAA2ABFFE671EB65C640578FF9DE16A23BFE3280A9DCDBB09A0667C1DF25612C95EF6A3B2AF22DB7DC67FD2FE87C643D24FBEBEB211EACD562C3A9D06815CF07CA979EBF318D9F64F8C]}
09-15 12:03:00.074  4645  4645 D [Weather Widget]  : {[15C09394A4E9AFE55A5C62F22AB3FC5902EB2A2150B6646A86F2B3102D669614]}
09-15 12:03:00.104  9956  9956 W ResourcesManager: getTopLevelResources: /system/app/WebViewGoogle/WebViewGoogle.apk / 1.0 running in com.test.thalitest rsrc of package com.google.android.webview
09-15 12:03:00.114  9956  9956 D ResourcesManager: For user 0 new overlays fetched Null
09-15 12:03:00.114  9956  9956 I InjectionManager: Inside getClassLibPath caller 
09-15 12:03:00.114  9956  9956 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
09-15 12:03:00.154  9956  9956 I cr_LibraryLoader: Time to load native libraries: 22 ms (timestamps 4288-4310)
09-15 12:03:00.154  9956  9956 I cr_LibraryLoader: Expected native library version number "49.0.2623.105", actual native library version number "49.0.2623.105"
,09-15 12:03:00.184  9956  9970 W System.err: remove failed: ENOENT (No such file or directory) : /data/user/0/com.test.thalitest/shared_prefs/WebViewChromiumPrefs.xml.bak
,09-15 12:03:00.194  9956  9956 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {267bd95}
09-15 12:03:00.194  9956  9956 I cr_LibraryLoader: Expected native library version number "49.0.2623.105", actual native library version number "49.0.2623.105"
,09-15 12:03:00.204  9956  9956 I chromium: [INFO:library_loader_hooks.cc(144)] Chromium logging enabled: level = 0, default verbosity = 0
,09-15 12:03:00.224  9956  9956 I cr_BrowserStartup: Initializing chromium process, singleProcess=true
,09-15 12:03:00.274  3410  3880 D MdnieScenarioControlService:  packageName : com.test.thalitest    className : com.test.thalitest.MainActivity
,09-15 12:03:00.314  9956  9956 D libEGL  : eglInitialize EGLDisplay = 0xfffbe9cc
,09-15 12:03:00.344  3410  3473 D ActivityManager: The following uid has registered to recieve broadcast for proxy related updates 10177
,09-15 12:03:00.354  3410  3473 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:845 com.android.server.am.ActivityManagerService.requestKnoxVpnToSendProxyBroadcast:29734 com.android.server.am.ActivityManagerService.registerReceiver:22599 android.app.ActivityManagerNative.onTransact:431 com.android.server.am.ActivityManagerService.onTransact:3990 
,09-15 12:03:00.364  3410  3856 D NetworkPolicy: isUidForegroundLocked: 10021, mScreenOn: true, uidstate: 2, mProxSensorScreenOff: false
,09-15 12:03:00.374  3410  3880 I MdnieScenarioControlService: mGameModeLauncher : false
,09-15 12:03:00.374  3410  3880 I MdnieScenarioControlService: setUIMode
,09-15 12:03:00.394  9956  9956 D cr_Ime  : [InputMethodManagerWrapper.java:27] Constructor
09-15 12:03:00.394  3009  3070 I SurfaceFlinger: id=9 Removed MauncherAct (4/11)
09-15 12:03:00.394  3009  3019 I SurfaceFlinger: id=9 Removed MauncherAct (-2/11)
09-15 12:03:00.394  3950  3950 D ImageWallpaper: onVisibilityChanged:false
09-15 12:03:00.394  3950  3950 D ImageWallpaper: drawFrame:false rotation:0 mLastRotation:0
09-15 12:03:00.394  3950  3950 D ImageWallpaper: drawFrame:[frame.width()]2240[frame.height()]2560
09-15 12:03:00.394  3950  3950 D ImageWallpaper: Suppressed drawFrame since redraw is not needed and offsets have not changed.
09-15 12:03:00.404  9956  9956 W cr_AwContents: onDetachedFromWindow called when already detached. Ignoring
09-15 12:03:00.404  9956  9956 D cr_Ime  : [InputMethodManagerWrapper.java:56] isActive: false
09-15 12:03:00.414  3009  3009 D libEGL  : eglTerminate EGLDisplay = 0x7ff285bf88
,09-15 12:03:00.414  9956  9956 D SystemWebViewEngine: CordovaWebView is running on device made by: samsung
,09-15 12:03:00.444  9956  9956 D Activity: performCreate Call Injection manager
,09-15 12:03:00.444  9956  9956 I InjectionManager: dispatchOnViewCreated > Target : com.test.thalitest.MainActivity isFragment :false
,09-15 12:03:00.444  9956  9956 D SecWifiDisplayUtil: Metadata value : SecSettings2
,09-15 12:03:00.454  9956  9956 D ViewRootImpl: #1 mView = com.android.internal.policy.PhoneWindow$DecorView{95627b I.E...... R.....ID 0,0-0,0}
09-15 12:03:00.454  9956 10007 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
,09-15 12:03:00.454  3410  3971 D ISSUE_DEBUG: InputChannelName : 445946c com.test.thalitest/com.test.thalitest.MainActivity
,09-15 12:03:00.454  3410  4123 D ActivityManager: post active user change for 0 fullscreen true isFloatingActivity() false isHomeActivity() false
09-15 12:03:00.454  3410  4123 D KnoxTimeoutHandler: postActiveUserChange [MsgParam] userId: 0 fullscreen is true showWhenlocked is false
09-15 12:03:00.454  3410  3410 D KnoxTimeoutHandler: handleActiveUserChange [MsgParam] userId: 0 fullscreen is true showWhenlocked is false
,09-15 12:03:00.454  3410  3410 I KnoxTimeoutHandler: Shared devices show user statefalse
,09-15 12:03:00.464  9956  9970 W System.err: remove failed: ENOENT (No such file or directory) : /data/user/0/com.test.thalitest/shared_prefs/com.test.thalitest_preferences.xml.bak
,09-15 12:03:00.474  9956  9956 D ConnectivityManager: requestNetwork; getAppId(CallingUid) : 10177, CallingPid : 9956
,09-15 12:03:00.474  3410  3979 D ConnectivityService: listenForNetwork for Listen from uid/pid:10177/9956 for NetworkRequest [ id=7, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,09-15 12:03:00.474  3410  3868 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 502]
09-15 12:03:00.474  3410  3576 D InputManager-JNI: setInteractive(false)
09-15 12:03:00.474  3410  3576 D PowerManagerService: [s] UserActivityState : 2 -> 4
09-15 12:03:00.474  3410  3576 I PowerManagerService: !@[ps] Screen__Off - 1 : timeout (0x4) (2)
09-15 12:03:00.474  3410  3576 I PowerManagerService: Going to sleep due to screen timeout (uid 1000)...
09-15 12:03:00.474  3410  3576 D PowerManagerService: mDisplayReady: false
09-15 12:03:00.474  3410  3576 D DisplayPowerController: animateScreenStateChange[0]: target=1
09-15 12:03:00.474  3410  3868 D ConnectivityService:  network has: NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{502}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::4e66:41ff:fea6:c72d/64,192.168.1.107/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains:  MTU: 0 TcpBufferSizes: 524288,1048576,2097120,524288,1048576,4194240}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN&VALIDATED LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -44]}  Score{60}  everValidated{true}  lastValidated{true}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
09-15 12:03:00.474  3410  3576 D ColorFade: prepare: mode=4
09-15 12:03:00.474  3410  3901 D NetworkPolicy: onScreenStateChanged, state: false, reason: 3
,09-15 12:03:00.474  3009  3009 I SurfaceFlinger: id=22 createSurf (1440x2560),2 flag=404, DolorFade
,09-15 12:03:00.474  3950  3966 D KeyguardViewMediator: onStartedGoingToSleep(3)
,09-15 12:03:00.484  3410  3576 D mali_winsys: EGLint new_window_surface(egl_winsys_display*, void*, EGLSurface, EGLConfig, egl_winsys_surface**, egl_color_buffer_format*, EGLBoolean) returns 0x3000,  [1440x2560]-format:1
,09-15 12:03:00.484  3410  3856 D NetworkPolicy: isUidForegroundLocked: 10021, mScreenOn: true, uidstate: 6, mProxSensorScreenOff: false
,09-15 12:03:00.494  9956  9956 D SecWifiDisplayUtil: Metadata value : SecSettings2
,09-15 12:03:00.504  3410  3868 D ConnectivityService: Network NetworkAgentInfo [WIFI () - 502] was already satisfying request 1. No change.
,09-15 12:03:00.504  3410  3576 D libEGL  : eglInitialize EGLDisplay = 0x7f59d7e778
,09-15 12:03:00.504  3410  3576 D libEGL  : eglTerminate EGLDisplay = 0x7f59d7e8e8
,09-15 12:03:00.504  3950  3966 E KeyguardViewMediator: lockAfterTimeout = 5000 policyTimeout = 0
,09-15 12:03:00.514  3009  3009 I SurfaceFlinger: id=23 createSurf (1x1),1 flag=404, NainActivit
,09-15 12:03:00.514  3410  3576 D ColorFade: ColorFade is ready
09-15 12:03:00.514  3410  3576 D DisplayPowerController: ColorFade: onAnimationStart
09-15 12:03:00.514  3410  3576 D DisplayPowerController: [Dual Screen Compatible] state[0] :2
,09-15 12:03:00.514  3410  3576 D DisplayPowerController: getFinalBrightness : Summary is 99 -> 99
09-15 12:03:00.514  3410  3868 D ConnectivityService:   checking if request is: NetworkRequest [ id=4, legacyType=-1, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] satisfies: true nri.isRequest: false
,09-15 12:03:00.514  3950  3966 D KeyguardViewMediator: timeout : 5000
,09-15 12:03:00.514  3410  3868 D ConnectivityService:   checking if request is: NetworkRequest [ id=7, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] satisfies: true nri.isRequest: false
,09-15 12:03:00.514  3950  3966 D KeyguardViewMediator: setting alarm to turn off keyguard, seq = 2
,09-15 12:03:00.514  3950  3966 D KeyguardViewMediator: notifyStartedGoingToSleep
09-15 12:03:00.514  3950  3950 V KeyguardFingerPrint: updateFingerprintListeningState(false)
09-15 12:03:00.514  3950  3950 D KeyguardFingerPrint: shouldListenForFingerprint ( FingerPrint is not enabled. ) 
09-15 12:03:00.514  3950  3950 V KeyguardUpdateMonitor: stopListeningForFingerprint()
09-15 12:03:00.514  3950  3950 D KeyguardViewMediator: handleNotifyStartedGoingToSleep
,09-15 12:03:00.514  3410  3868 D ConnectivityService:   checking if request is: NetworkRequest [ id=3, legacyType=-1, [ Transports: CELLULAR Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] satisfies: false nri.isRequest: false
,09-15 12:03:00.514  3410  3868 D ConnectivityService:   checking if request is: NetworkRequest [ id=6, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] satisfies: true nri.isRequest: false
,09-15 12:03:00.524  3410  3868 D ConnectivityService:   checking if request is: NetworkRequest [ id=5, legacyType=-1, [] ] satisfies: true nri.isRequest: false
,09-15 12:03:00.524  3410  3868 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=7, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,09-15 12:03:00.524  3410  3474 D InputDispatcher: Focus entered window: 9956
,09-15 12:03:00.534  3410  3572 D PointerIcon: setMouseIconStyle1 pointerType: 1001 iconType:101 flag:0 pid:3410 uid:1000
,09-15 12:03:00.534  3410  3572 D PointerIcon: setMouseCustomIcon IconType is same.101
09-15 12:03:00.534  9956 10007 D libEGL  : eglInitialize EGLDisplay = 0xdbfbf7c4
09-15 12:03:00.534  9956 10007 I OpenGLRenderer: Initialized EGL, version 1.4
,09-15 12:03:00.534  9956 10007 D mali_winsys: EGLint new_window_surface(egl_winsys_display*, void*, EGLSurface, EGLConfig, egl_winsys_surface**, egl_color_buffer_format*, EGLBoolean) returns 0x3000,  [1440x2560]-format:1
,09-15 12:03:00.544  9956  9956 W DisplayListCanvas: DisplayListCanvas is started on unbinded RenderNode (without mOwningView)
,09-15 12:03:00.544  3009  3009 D libEGL  : eglInitialize EGLDisplay = 0x7ff285be68
,09-15 12:03:00.564  3009  3009 D libEGL  : eglInitialize EGLDisplay = 0x7ff285be68
,09-15 12:03:00.574  3009  3009 D libEGL  : eglInitialize EGLDisplay = 0x7ff285be68
,09-15 12:03:00.574  3009  3009 D libEGL  : eglInitialize EGLDisplay = 0x7ff285be68
,09-15 12:03:00.574  3410  4951 V WindowStateAnimator: Finishing drawing window Window{445946c u0 d0 com.test.thalitest/com.test.thalitest.MainActivity}: mDrawState=DRAW_PENDING
,09-15 12:03:00.574  9956  9956 D ViewRootImpl: MSG_RESIZED_REPORT: ci=Rect(0, 96 - 0, 0) vi=Rect(0, 96 - 0, 0) or=1
,09-15 12:03:00.584  3410  4254 D InputMethodManagerService: windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,09-15 12:03:00.584  3410  3572 D KnoxTimeoutHandler: notifyActivityDrawn [MsgParam] userId: 0 fullscreen is true showWhenlocked is false
,09-15 12:03:00.584  3410  3410 D KnoxTimeoutHandler: activityDrawn [MsgParam] userId: 0 fullscreen is true showWhenlocked is false
09-15 12:03:00.584  3410  3572 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +627ms
09-15 12:03:00.584  3410  3572 D CustomFrequencyManagerService: releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1872000  uid : 1000  pid : 3410  tag : ACTIVITY_RESUME_BOOSTER@7
,09-15 12:03:00.584  3410  3572 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{bc890b0 u0 com.test.thalitest/.MainActivity t75} time:204744
09-15 12:03:00.584  3410  3572 D ActivityManager: mDVFSHelper.release()
09-15 12:03:00.584  3410  3572 D ViewRootImpl: #3 mView = null
09-15 12:03:00.584  3410  3541 D CustomFrequencyManagerService: acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1872000  uid : 1000  pid : 3410  pkgName : ACTIVITY_RESUME_BOOSTER@13
,09-15 12:03:00.584  3410  3410 I KnoxTimeoutHandler: SD activityfalse
,09-15 12:03:00.584  7169  7169 D SamsungIME: IMPL finishInput
,09-15 12:03:00.584  7169  7169 D SamsungIME: SwiftKeyWrapper writeDBdataToFileOnFinishInput
09-15 12:03:00.584  7169  7169 D SamsungIME: saveAndClear +
09-15 12:03:00.584  7169  7169 D SamsungIME: saveAndClear -
,09-15 12:03:00.594  9956 10013 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,09-15 12:03:00.594  9956 10013 D libEGL  : eglInitialize EGLDisplay = 0xdb5bf3f4
,09-15 12:03:00.594  3410  3971 V WindowStateAnimator: Finishing drawing window Window{445946c u0 d0 com.test.thalitest/com.test.thalitest.MainActivity}: mDrawState=HAS_DRAWN
,09-15 12:03:00.604  9956  9956 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@2778b20 time:204760
,09-15 12:03:00.604  4300  4300 D Launcher.HomeView: onStop
,09-15 12:03:00.604  4300  4300 D capture : ----destroy
09-15 12:03:00.604  4300  4300 V ActivityThread: updateVisibility : ActivityRecord{37ea16c token=android.os.BinderProxy@72e9445 {com.sec.android.app.launcher/com.sec.android.app.launcher.activities.LauncherActivity}} show : false
,09-15 12:03:00.604  9956 10013 D libGLESv2: DTS_GLAPI : DTS is not allowed for Package : com.test.thalitest
,09-15 12:03:00.604  3410  3856 D NetworkPolicy: isUidForegroundLocked: 10072, mScreenOn: true, uidstate: 3, mProxSensorScreenOff: false
,09-15 12:03:00.614  3009  3009 D libEGL  : eglInitialize EGLDisplay = 0x7ff285be68
,09-15 12:03:00.614  4300  4300 D Launcher: onTrimMemory. Level: 20
,09-15 12:03:00.624  9956  9956 W cr_BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 9956
,09-15 12:03:00.644  3009  3009 D libEGL  : eglInitialize EGLDisplay = 0x7ff285be68
,09-15 12:03:00.674  9956  9956 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,09-15 12:03:00.784  3009  4362 I SurfaceFlinger: id=21 Removed uhalitest (6/12)
,09-15 12:03:00.784  3009  4466 I SurfaceFlinger: id=21 Removed uhalitest (-2/12)
,09-15 12:03:00.794  3009  3009 D libEGL  : eglTerminate EGLDisplay = 0x7ff285bf88
,09-15 12:03:00.794  9956 10020 D jxcore_app_log: JniHelper::setJavaVM(0xf49f4000), pthread_self() = -685246160
,09-15 12:03:00.804  9956 10020 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
09-15 12:03:00.804  9956 10020 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
09-15 12:03:00.804  9956 10020 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
09-15 12:03:00.804  9956 10020 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
09-15 12:03:00.804  9956 10020 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
09-15 12:03:00.804  9956 10020 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@bbfe06b added. We now have 1 listener(s)
,09-15 12:03:00.804  9956 10020 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: A8:81:95:E9:5F:6F
,09-15 12:03:00.804  9956 10020 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "A8:81:95:E9:5F:6F"
,09-15 12:03:00.804  9956 10020 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-15 12:03:00.804  9956 10020 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,09-15 12:03:00.804  9956 10020 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
09-15 12:03:00.804  9956 10020 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
09-15 12:03:00.804  9956 10020 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
09-15 12:03:00.804  9956 10020 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: A8:81:95:E9:5F:6F
09-15 12:03:00.804  9956 10020 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
09-15 12:03:00.804  9956 10020 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
09-15 12:03:00.804  9956 10020 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
09-15 12:03:00.804  9956 10020 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
09-15 12:03:00.804  9956 10020 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
09-15 12:03:00.804  9956 10020 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
09-15 12:03:00.804  9956 10020 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
09-15 12:03:00.804  9956 10020 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
09-15 12:03:00.804  9956 10020 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
09-15 12:03:00.804  9956 10020 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
09-15 12:03:00.804  9956 10020 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2bb6786 added. We now have 1 listener(s)
09-15 12:03:00.804  9956 10020 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-15 12:03:00.814  3410  3576 D DisplayPowerState: !@ [0] ColorFade entry
,09-15 12:03:00.824  3410  3576 D PowerManagerService: [input device light] onColorFadeExit(false)
09-15 12:03:00.824  3410  3576 D DisplayPowerController: ColorFade: onAnimationEnd
,09-15 12:03:00.824  3410  3904 D lights  : lcd : 0 +
09-15 12:03:00.824  3410  3576 D DisplayPowerController: animateScreenStateChange[0]: target=1
09-15 12:03:00.824  3410  3576 D DisplayPowerController: [M OS] 0 REPORTED_TO_POLICY_SCREEN_* -> REPORTED_TO_POLICY_SCREEN_OFF.
,09-15 12:03:00.834  9956 10020 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
09-15 12:03:00.834  9956 10020 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
09-15 12:03:00.834  9956 10020 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
09-15 12:03:00.834  9956 10020 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
09-15 12:03:00.834  9956 10020 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
,09-15 12:03:00.844  3410  3904 D lights  : lcd : 0 -
,09-15 12:03:00.884  3410  3410 D CustomFrequencyManagerService: releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1872000  uid : 1000  pid : 3410  tag : ACTIVITY_RESUME_BOOSTER@13
,09-15 12:03:00.894  3410  3576 D SContextService: unregisterCallback() : Listener = android.hardware.scontext.SContextService$Listener@8e5df1c, Service = Auto Rotation, used = 0
,09-15 12:03:00.894  3410  3576 W CAE     : unregisterCallback(ContextAwareService.java:206) - [unregi 01] Mutex is locked for AUTO_ROTATION
09-15 12:03:00.894  9956 10020 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-15 12:03:00.894  3410  3576 V CAE     : stop(ContextProvider.java:155)
09-15 12:03:00.894  9956 10020 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is A8:81:95:E9:5F:6F
,09-15 12:03:00.894  3410  3880 D MdnieScenarioControlService:  packageName : com.test.thalitest    className : com.test.thalitest.MainActivity
09-15 12:03:00.894  3410  3576 V CAE     : clear(AutoRotationRunner.java:182)
09-15 12:03:00.894  3410  3856 D NetworkPolicy: isUidForegroundLocked: 10177, mScreenOn: true, uidstate: 5, mProxSensorScreenOff: false
09-15 12:03:00.894  3410  3576 V CAE     : disable(AutoRotationRunner.java:171)
09-15 12:03:00.894  3410  3576 I CAE     : sendCmdToSensorHub(SensorHubCommManager.java:162) - -78, 7, 0, 0,
09-15 12:03:00.894  3410  3576 D SensorHubManager: SendSensorHubData: send data = -78, 7, 0, 0
,09-15 12:03:00.894  3169  3208 D Sensorhubs: sendContextData: -78, 7, 0, 0
,09-15 12:03:00.904  3410  3576 D CAE     : getFaultDetectionResult(AutoRotationRunner.java:195) - true
,09-15 12:03:00.914  3410  3576 I CAE     : notifyCmdProcessResultObserver(ContextProvider.java:627) - CheckResult = 0, Cause = Success
,09-15 12:03:00.924  3410  3576 D CAE     : doCommendProcess(ContextAwareService.java:433) - complete notify the operation result.
,09-15 12:03:00.924  3410  3576 I CAE     : displayUsedCountForService(ContextAwareService.java:525) - totalCnt = 0, serviceCount = 0, subCollectionCount = 0
,09-15 12:03:00.924  3410  3576 D CAE     : showListenerList(ContextAwareService.java:366) - ===== Context Aware Service List =====
09-15 12:03:00.924  3410  3576 I CAE     : showListenerList(ContextAwareService.java:375) - Listener : com.samsung.android.contextaware.manager.ContextAwareService$Listener@4604ec9, Service : ACTIVITY_TRACKER_CURRENT_INFO(1)
,09-15 12:03:00.924  3410  3576 I CAE     : showListenerList(ContextAwareService.java:375) - Listener : com.samsung.android.contextaware.manager.ContextAwareService$Listener@4604ec9, Service : ACTIVITY_TRACKER(1)
09-15 12:03:00.924  3410  3576 I CAE     : showListenerList(ContextAwareService.java:375) - Listener : com.samsung.android.contextaware.manager.ContextAwareService$Listener@473076d, Service : AUTO_BRIGHTNESS(1)
09-15 12:03:00.924  3410  3576 W CAE     : unregisterCallback(ContextAwareService.java:241) - [unregi 02] Mutex is unlocked for AUTO_ROTATION
09-15 12:03:00.924  3410  3576 D SContextService: 	.unregisterCallback : 3, client=
09-15 12:03:00.924  3410  3576 D SContextService: ===== SContext Service List =====
09-15 12:03:00.924  3410  3576 D SContextService: Listener : android.hardware.scontext.SContextService$Listener@c8b8fa2, Service : Auto Brightness
,09-15 12:03:00.924  3410  3576 D SContextService: Listener : android.hardware.scontext.SContextService$Listener@a1370fa, Service : Activity Tracker
09-15 12:03:00.924  3410  3576 D SContextManager:   .unregisterListener : listener = com.android.server.policy.WindowOrientationListener$OrientationSensorJudge@b1753e, service=Auto Rotation
09-15 12:03:00.924  3410  3576 V KeyguardServiceDelegate: onScreenTurnedOff()
09-15 12:03:00.924  3950  3960 D KeyguardViewMediator: notifyScreenTurnedOff
09-15 12:03:00.924  3950  3950 D KeyguardViewMediator: handleNotifyScreenTurnedOff
09-15 12:03:00.924  3950  3950 D vol.SecVolumeDialog: onScreenTurnedOff()
09-15 12:03:00.924  3950  3950 D vol.SecVolumeDialog: dismissH reason: 4
09-15 12:03:00.924  3950  3950 D vol.SecVolumeDialog: dismissH : false
,09-15 12:03:00.924  3410  3576 D DisplayPowerController: mWindowManagerPolicy.screenTurnedOff(0)
09-15 12:03:00.924  3410  3576 D DisplayPowerController: [Dual Screen Compatible] state[0] :1
09-15 12:03:00.924  3410  3576 D PowerManagerUtil: fileWriteInt to /sys/class/tcon/tcon/auto_br, 0
09-15 12:03:00.934  3410  3576 D PowerManagerUtil: fileWriteInt to /sys/class/backlight/panel/auto_brightness, 0
09-15 12:03:00.934  3410  3542 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1305 com.android.server.policy.sec.SamsungPhoneWindowManager$22.run:4514 android.os.Handler.handleCallback:739 android.os.Handler.dispatchMessage:95 android.os.Looper.loop:158 
09-15 12:03:00.934  3410  3903 D AutomaticBrightnessController: [DAB] setLightSensorEnabled : unregisterListenerRunnable
09-15 12:03:00.934  3410  3903 D SContextService: unregisterCallback() : Listener = android.hardware.scontext.SContextService$Listener@c8b8fa2, Service = Auto Brightness, used = 0
09-15 12:03:00.934  4751  4751 I AODService: onStartCommand : action : com.samsung.android.app.aodservice.intent.action.AOD_SCREEN_OFF
09-15 12:03:00.934  4751  4751 I AODService: onCreate cause: [09-15 11:59:50.559][AOD:true, NightClock:false]<com.samsung.android.app.aodservice.intent.action.AOD_SCREEN_ON> (when Screen on ...)
09-15 12:03:00.934  3410  3903 W CAE     : unregisterCallback(ContextAwareService.java:206) - [unregi 01] Mutex is locked for AUTO_BRIGHTNESS
,09-15 12:03:00.934  3410  3903 V CAE     : stop(ContextProvider.java:155)
,09-15 12:03:00.934  3410  3576 D PowerManagerUtil: fileWriteInt to /sys/class/mdnie/mdnie/auto_brightness, 0
09-15 12:03:00.934  3410 10022 D MISC PowerHAL: sysfs_write +: /sys/class/input/event0/device/enabled: 0
09-15 12:03:00.934  3410  3576 D AutomaticBrightnessController: [DAB] no lux value from sensor manager
09-15 12:03:00.934  3410 10023 D MISC PowerHAL: sysfs_write +: /sys/class/input/event1/device/enabled: 0
09-15 12:03:00.934  3410  3576 D DisplayPowerController: getFinalBrightness : Summary is 0 -> 0
09-15 12:03:00.934  3410 10022 D MISC PowerHAL: sysfs_write -: /sys/class/input/event0/device/enabled: 0
09-15 12:03:00.934  3410  3576 D DisplayPowerController: Animating brightness: target=0, rate=0 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
09-15 12:03:00.934  3410  3903 V CAE     : clear(AutoBrightnessRunner.java:297)
09-15 12:03:00.934  3410  3576 D DisplayPowerController: animateScreenStateChange[0]: target=1
09-15 12:03:00.934  3410 10023 D MISC PowerHAL: sysfs_write -: /sys/class/input/event1/device/enabled: 0
09-15 12:03:00.934  3410  3576 D DisplayPowerController: [Dual Screen Compatible] state[0] :1
09-15 12:03:00.934  9956 10020 D BluetoothAdapter: STATE_ON
09-15 12:03:00.934  3410  3576 D DisplayPowerController: getFinalBrightness : Summary is 0 -> 0
09-15 12:03:00.934  3410  3586 D MISC PowerHAL: sysfs_write +: /sys/class/power_supply/battery/lcd: 0
09-15 12:03:00.934  3410  3576 D DisplayPowerController: Animating brightness: target=0, rate=0 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
09-15 12:03:00.934  3410  3586 D MISC PowerHAL: sysfs_write -: /sys/class/power_supply/battery/lcd: 0
09-15 12:03:00.944  3410  3586 D DisplayManagerService: !@display_state: ON -> OFF brightness: 0 -> 0
09-15 12:03:00.944  3410  3903 V CAE     : disable(AutoBrightnessRunner.java:286)
09-15 12:03:00.944  3410  3572 I DisplayManagerService: Display device changed state: "Wbudowany ekran", OFF
09-15 12:03:00.944  3410  3903 I CAE     : sendCmdToSensorHub(SensorHubCommManager.java:162) - -78, 48, 0, 0,
09-15 12:03:00.944  3410  3572 I DisplayManagerService: Display device changed state: "ActivityViewVirtualDisplay", OFF
09-15 12:03:00.944  3410  3903 D SensorHubManager: SendSensorHubData: send data = -78, 48, 0, 0
,09-15 12:03:00.944  3009  3009 D SurfaceFlinger: Set power mode=0, type=0 flinger=0x7fb2003c00
,09-15 12:03:00.944  3009  3009 I hwcomposer: int exynos_setPowerMode(hwc_composer_device_1*, int, int):: disp(0), mode(0)
09-15 12:03:00.944  3410  3421 I art     : Background partial concurrent mark sweep GC freed 52342(3MB) AllocSpace objects, 22(440KB) LOS objects, 31% free, 34MB/50MB, paused 4.501ms total 111.433ms
,09-15 12:03:00.954  3169  3169 D Sensorhubs: sendContextData: -78, 48, 0, 0
,09-15 12:03:00.974  3410  3903 D CAE     : getFaultDetectionResult(AutoBrightnessRunner.java:311) - true
,09-15 12:03:00.974  3410  3903 I CAE     : notifyCmdProcessResultObserver(ContextProvider.java:627) - CheckResult = 0, Cause = Success
,09-15 12:03:00.984  6198  6198 E CocktailBarPositionManager: Window direction: 0
,09-15 12:03:00.984  6198  6198 I CocktailBarPositionManager: updateAlphaScreenPosition position is dirty 0
,09-15 12:03:00.984  9956 10020 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (SUPPORTED) in persistent storage
09-15 12:03:00.984  9956 10020 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-15 12:03:00.984  9956 10020 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-15 12:03:00.984  9956 10020 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-15 12:03:00.984  9956 10020 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-15 12:03:00.984  9956 10020 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-15 12:03:00.984  9956 10020 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-15 12:03:00.984  9956 10020 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-15 12:03:00.984  9956 10020 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-15 12:03:00.984  9956 10020 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
09-15 12:03:00.984  9956 10020 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-15 12:03:00.984  9956 10020 I io.jxcore.node.LifeCycleMonitor: start: OK
,09-15 12:03:00.994  3410  3903 D CAE     : doCommendProcess(ContextAwareService.java:433) - complete notify the operation result.,
,09-15 12:03:00.994  3410  3903 I CAE     : displayUsedCountForService(ContextAwareService.java:525) - totalCnt = 0, serviceCount = 0, subCollectionCount = 0
,09-15 12:03:00.994  3410  3903 D CAE     : showListenerList(ContextAwareService.java:366) - ===== Context Aware Service List =====
,09-15 12:03:00.994  3410  3903 I CAE     : showListenerList(ContextAwareService.java:375) - Listener : com.samsung.android.contextaware.manager.ContextAwareService$Listener@4604ec9, Service : ACTIVITY_TRACKER_CURRENT_INFO(1)
09-15 12:03:00.994  3410  3903 I CAE     : showListenerList(ContextAwareService.java:375) - Listener : com.samsung.android.contextaware.manager.ContextAwareService$Listener@4604ec9, Service : ACTIVITY_TRACKER(1)
09-15 12:03:00.994  3410  3880 I MdnieScenarioControlService: mGameModeLauncher : false
09-15 12:03:00.994  3410  3903 W CAE     : unregisterCallback(ContextAwareService.java:241) - [unregi 02] Mutex is unlocked for AUTO_BRIGHTNESS
09-15 12:03:00.994  3410  3903 D PowerManagerUtil: Excessive delay in SensorHubAutoBrightnessEnabled::unregisterListener done: 67ms
09-15 12:03:00.994  3410  3903 D SContextService: 	.unregisterCallback : 2, client=
09-15 12:03:00.994  3410  3903 D SContextService: ===== SContext Service List =====
09-15 12:03:00.994  3410  3903 D SContextService: Listener : android.hardware.scontext.SContextService$Listener@a1370fa, Service : Activity Tracker
09-15 12:03:00.994  3410  3903 D SContextManager:   .unregisterListener : listener = com.android.server.display.AutomaticBrightnessController$6@dc5d85a, service=Auto Brightness
09-15 12:03:01.004  3410  3880 I MdnieScenarioControlService: setUIMode
,09-15 12:03:01.004  9956  9956 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-15 12:03:01.004  9956  9956 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-15 12:03:01.014  3410  4952 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
09-15 12:03:01.014  9956  9956 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@acb0bb9 Bundle[{plugin=Bundle[{}], android:viewHierarchyState=Bundle[{android:views={100=android.view.AbsSavedState$1@e567612, 16908290=android.view.AbsSavedState$1@e567612}, android:focusedViewId=100}]}]
,09-15 12:03:01.014  9956  9956 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: SAVE_INSTANCE_STATE
,09-15 12:03:01.014  9956  9956 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
09-15 12:03:01.014  9956  9956 V ActivityThread: updateVisibility : ActivityRecord{6b5f1e3 token=android.os.BinderProxy@2778b20 {com.test.thalitest/com.test.thalitest.MainActivity}} show : true
09-15 12:03:01.014  9956  9956 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: STOPPED
,09-15 12:03:01.014  3410  3979 D CoverManagerWhiteLists: isAllowedToUse : SIGNATURE_MATCH
09-15 12:03:01.014  4751  4751 D ScoverManager: registerListener
09-15 12:03:01.014  3410  4123 D CoverManagerWhiteLists: isAllowedToUse : SIGNATURE_MATCH
,09-15 12:03:01.014  3410  4251 D CoverManagerWhiteLists: isAllowedToUse : SIGNATURE_MATCH
,09-15 12:03:01.014  3410  4251 D CoverManager.StateNotifier: registerListenerCallback : binder = android.os.BinderProxy@3467a88, pid : 4751, uid : 10000, type : 1
,09-15 12:03:01.034  3410  6452 W ResourcesManager: getTopLevelResources: /data/app/com.test.thalitest-1/base.apk / 1.0 running in null rsrc of package com.test.thalitest
,09-15 12:03:01.034  4751 10026 D AODService: onCreate register mSContextListener : com.samsung.android.app.aodservice.AODService$7@bbe01b7
09-15 12:03:01.044  3410  4248 W CAE     : setCAProperty(ContextAwareService.java:578) - [setProperty 01] Mutex is locked for DEVICE_PHYSICAL_CONTEXT_MONITOR
09-15 12:03:01.044  9956  9956 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,09-15 12:03:01.044  3410  4248 I CAE     : sendCmdToSensorHub(SensorHubCommManager.java:162) - -63, 23, 56, 4, 0, 0, 0, 1, 2,
,09-15 12:03:01.044  3410  4248 D SensorHubManager: SendSensorHubData: send data = -63, 23, 56, 4, 0, 0, 0, 1, 2
,09-15 12:03:01.044  3169  3208 D Sensorhubs: sendContextData: -63, 23, 56, 4, 0, 0, 0, 1, 2
09-15 12:03:01.044  3410  4951 D SensorService: SensorEventConnection::SocketBufferSize, SystemSocketBufferSize - 102400, 2097152
,09-15 12:03:01.044  3410  4425 I Sensors : Light old sensor_state 0, new sensor_state : 512 en : 1
,09-15 12:03:01.054  3410  4248 I CAE     : setCAProperty(ContextAwareService.java:583) - result : true
,09-15 12:03:01.054  3410  4248 W CAE     : setCAProperty(ContextAwareService.java:584) - [setProperty 02] Mutex is unlocked for DEVICE_PHYSICAL_CONTEXT_MONITOR
09-15 12:03:01.054  3410  4248 W CAE     : registerCallback(ContextAwareService.java:144) - [regi 01] Mutex is locked for DEVICE_PHYSICAL_CONTEXT_MONITOR
09-15 12:03:01.054  3410  4248 V CAE     : start(ContextProvider.java:128)
,09-15 12:03:01.054  3410  4248 V CAE     : clear(DevicePhysicalContextMonitorRunner.java:497)
09-15 12:03:01.054  3410  4248 V CAE     : enable(DevicePhysicalContextMonitorRunner.java:471)
09-15 12:03:01.054  3410  4248 I CAE     : sendCmdToSensorHub(SensorHubCommManager.java:162) - -79, 56, 0, 10, 3, 1,
09-15 12:03:01.054  3410  4248 D SensorHubManager: SendSensorHubData: send data = -79, 56, 0, 10, 3, 1
09-15 12:03:01.054  3169  3169 D Sensorhubs: sendContextData: -79, 56, 0, 10, 3, 1
,09-15 12:03:01.054  4751  4751 D SensorManager: registerListener :: 6, TMD4093 RGB Sensor, 200000, 0,  
,09-15 12:03:01.054  4751  4751 D AODService: registerBatteryReceiver
,09-15 12:03:01.054  4751  4751 D BatteryController: saveBatteryData : level[100], status[5]
09-15 12:03:01.054  4751  4751 D AODService: Cover coverOpen[true], isBlackListCover(type)[false]
09-15 12:03:01.054  4751  4751 D AODService.ClockTimer: ClockTimer:start : true
,09-15 12:03:01.064  4751  4751 D AODService.ClockTimer: observe start aod
,09-15 12:03:01.064  3410  4248 D CAE     : getFaultDetectionResult(DevicePhysicalContextMonitorRunner.java:521) - true
09-15 12:03:01.064  4751  4751 D AODService.ClockTimer: notifyWakeUp
09-15 12:03:01.064  3410  4248 I CAE     : notifyCmdProcessResultObserver(ContextProvider.java:627) - CheckResult = 0, Cause = Success
,09-15 12:03:01.064  4751  4751 V BatteryController: getBatteryLevel[100.0], batteryStatus[5]
,09-15 12:03:01.064  3410  4951 D SettingsProvider: isChangeAllowed() : name = aod_show_state
09-15 12:03:01.064  3410  4951 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
09-15 12:03:01.064  3410  4951 D SecContentProvider: query(), uri = 17 selection = isSettingsChangesAllowed
,09-15 12:03:01.064  3410  4951 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
09-15 12:03:01.064  3410  4951 D SettingsProvider: selectionArgs: false
09-15 12:03:01.064  3410  4951 D SettingsProvider: selectionArgs: 10000
09-15 12:03:01.064  3410  4951 D SettingsProvider: ret = -1
,09-15 12:03:01.074  4751  4751 E SettingsUtils: setAODShowState  config = 1
,09-15 12:03:01.074  4751  4751 D AlpmModeManager: setFirstStartALPM() initialize value
09-15 12:03:01.074  4751  4751 D AODService: createWindow
,09-15 12:03:01.074  3410  4248 D CAE     : doCommendProcess(ContextAwareService.java:433) - complete notify the operation result.
,09-15 12:03:01.074  3410  4248 I CAE     : displayUsedCountForService(ContextAwareService.java:525) - totalCnt = 1, serviceCount = 1, subCollectionCount = 0
,09-15 12:03:01.074  3410  4248 D CAE     : showListenerList(ContextAwareService.java:366) - ===== Context Aware Service List =====
09-15 12:03:01.074  3410  4248 I CAE     : showListenerList(ContextAwareService.java:375) - Listener : com.samsung.android.contextaware.manager.ContextAwareService$Listener@4604ec9, Service : ACTIVITY_TRACKER_CURRENT_INFO(1),
09-15 12:03:01.074  3410  4248 I CAE     : showListenerList(ContextAwareService.java:375) - Listener : com.samsung.android.contextaware.manager.ContextAwareService$Listener@4604ec9, Service : ACTIVITY_TRACKER(1)
,09-15 12:03:01.074  3410  4248 I CAE     : showListenerList(ContextAwareService.java:375) - Listener : com.samsung.android.contextaware.manager.ContextAwareService$Listener@eefdfa3, Service : DEVICE_PHYSICAL_CONTEXT_MONITOR(1)
09-15 12:03:01.074  3410  4248 W CAE     : registerCallback(ContextAwareService.java:180) - [regi 02] Mutex is unlocked for DEVICE_PHYSICAL_CONTEXT_MONITOR
,09-15 12:03:01.074  3410  4248 D SContextService: 	.registerCallback : 2, client=
09-15 12:03:01.074  3410  4248 D SContextService: ===== SContext Service List =====
09-15 12:03:01.074  3410  4248 D SContextService: Listener : android.hardware.scontext.SContextService$Listener@a1370fa, Service : Activity Tracker
09-15 12:03:01.074  3410  4248 D SContextService: Listener : android.hardware.scontext.SContextService$Listener@d5812a0, Service : Device Physical Context Monitor
,09-15 12:03:01.074  4751 10026 D SContextManager:   .registerListener : listener = com.samsung.android.app.aodservice.AODService$7@bbe01b7, service=Device Physical Context Monitor
,09-15 12:03:01.084  4751  4751 I AODUpdatePositionController: initPosition : X[22], Y[677] Rect(-50, 0 - 50, 920)
,09-15 12:03:01.084  3410  4952 W CAE     : setCAProperty(ContextAwareService.java:578) - [setProperty 01] Mutex is locked for DEVICE_PHYSICAL_CONTEXT_MONITOR
,09-15 12:03:01.084  3410  4952 I CAE     : sendCmdToSensorHub(SensorHubCommManager.java:162) - -63, 23, 56, 3, 1, 2, 88,
09-15 12:03:01.084  3410  4952 D SensorHubManager: SendSensorHubData: send data = -63, 23, 56, 3, 1, 2, 88
09-15 12:03:01.084  4751  4751 D Minikin : FontFamily bestFont == NULL, so return vacant FakedFont
09-15 12:03:01.084  4751  4751 D Minikin : FontFamily bestFont == NULL, so return vacant FakedFont
09-15 12:03:01.084  4751  4751 D Minikin : FontFamily bestFont == NULL, so return vacant FakedFont
09-15 12:03:01.084  3169  3208 D Sensorhubs: sendContextData: -63, 23, 56, 3, 1, 2, 88
,09-15 12:03:01.084  4751  4751 D Minikin : FontFamily bestFont == NULL, so return vacant FakedFont
09-15 12:03:01.084  4751  4751 D Minikin : FontFamily bestFont == NULL, so return vacant FakedFont
09-15 12:03:01.084  4751  4751 D Minikin : FontFamily bestFont == NULL, so return vacant FakedFont
,09-15 12:03:01.084  3410  4952 I CAE     : setCAProperty(ContextAwareService.java:583) - result : true
09-15 12:03:01.084  3410  4952 W CAE     : setCAProperty(ContextAwareService.java:584) - [setProperty 02] Mutex is unlocked for DEVICE_PHYSICAL_CONTEXT_MONITOR
,09-15 12:03:01.084  4751  4751 D Minikin : FontFamily bestFont == NULL, so return vacant FakedFont
09-15 12:03:01.084  4751  4751 D Minikin : FontFamily bestFont == NULL, so return vacant FakedFont
09-15 12:03:01.084  4751  4751 D Minikin : FontFamily bestFont == NULL, so return vacant FakedFont
,09-15 12:03:01.084  3410  4715 W CAE     : setCAProperty(ContextAwareService.java:578) - [setProperty 01] Mutex is locked for DEVICE_PHYSICAL_CONTEXT_MONITOR
,09-15 12:03:01.094  3410  4715 I CAE     : sendCmdToSensorHub(SensorHubCommManager.java:162) - -63, 23, 56, 3, 2, 0, 3,
09-15 12:03:01.094  3410  4715 D SensorHubManager: SendSensorHubData: send data = -63, 23, 56, 3, 2, 0, 3
09-15 12:03:01.094  3169  3169 D Sensorhubs: sendContextData: -63, 23, 56, 3, 2, 0, 3
09-15 12:03:01.094  4751  4751 I DefaultClockView: composeDefaultClockView: Selected clock = 0
,09-15 12:03:01.094  3410  4715 I CAE     : setCAProperty(ContextAwareService.java:583) - result : true
,09-15 12:03:01.094  3410  4715 W CAE     : setCAProperty(ContextAwareService.java:584) - [setProperty 02] Mutex is unlocked for DEVICE_PHYSICAL_CONTEXT_MONITOR
,09-15 12:03:01.094  3410  3971 W CAE     : setCAProperty(ContextAwareService.java:578) - [setProperty 01] Mutex is locked for DEVICE_PHYSICAL_CONTEXT_MONITOR
,09-15 12:03:01.094  3410  3971 I CAE     : sendCmdToSensorHub(SensorHubCommManager.java:162) - -63, 23, 56, 3, 3, 0, 60,
09-15 12:03:01.094  3410  3971 D SensorHubManager: SendSensorHubData: send data = -63, 23, 56, 3, 3, 0, 60
09-15 12:03:01.094  3169  3208 D Sensorhubs: sendContextData: -63, 23, 56, 3, 3, 0, 60
,09-15 12:03:01.104  4751  4751 D BatteryMeterView: BatteryMeterView 
09-15 12:03:01.104  3410  3971 I CAE     : setCAProperty(ContextAwareService.java:583) - result : true
09-15 12:03:01.104  3410  3971 W CAE     : setCAProperty(ContextAwareService.java:584) - [setProperty 02] Mutex is unlocked for DEVICE_PHYSICAL_CONTEXT_MONITOR
,09-15 12:03:01.104  3410  4254 W CAE     : setCAProperty(ContextAwareService.java:578) - [setProperty 01] Mutex is locked for DEVICE_PHYSICAL_CONTEXT_MONITOR
,09-15 12:03:01.104  3410  4254 I CAE     : sendCmdToSensorHub(SensorHubCommManager.java:162) - -63, 23, 56, 3, 4, 0, 1,
09-15 12:03:01.104  3410  4254 D SensorHubManager: SendSensorHubData: send data = -63, 23, 56, 3, 4, 0, 1
,09-15 12:03:01.104  3169  3169 D Sensorhubs: sendContextData: -63, 23, 56, 3, 4, 0, 1
,09-15 12:03:01.104  4751  4751 D Minikin : FontFamily bestFont == NULL, so return vacant FakedFont
,09-15 12:03:01.104  4751  4751 D Minikin : FontFamily bestFont == NULL, so return vacant FakedFont
09-15 12:03:01.104  4751  4751 D Minikin : FontFamily bestFont == NULL, so return vacant FakedFont
,09-15 12:03:01.104  3410  4254 I CAE     : setCAProperty(ContextAwareService.java:583) - result : true
09-15 12:03:01.104  3410  4254 W CAE     : setCAProperty(ContextAwareService.java:584) - [setProperty 02] Mutex is unlocked for DEVICE_PHYSICAL_CONTEXT_MONITOR
,09-15 12:03:01.104  4751  4751 D DefaultClockView: LocalTime Pattern : HH:mm
,09-15 12:03:01.104  4751  4751 I AODUpdatePositionController: updatePosition: start current clock, Current X[22] Current Y[677] NewPositionTimer[60]
09-15 12:03:01.104  3410  4248 W CAE     : setCAProperty(ContextAwareService.java:578) - [setProperty 01] Mutex is locked for DEVICE_PHYSICAL_CONTEXT_MONITOR
,09-15 12:03:01.114  4751  4751 D TimeViewHolder: onTimeUpdate: timeZone:libcore.util.ZoneInfo[id="Europe/Warsaw",mRawOffset=3600000,mEarliestRawOffset=3600000,mUseDst=true,mDstSavings=3600000,transitions=167] isSplitHour:false isSingleView:false isAMPMonLeft:null time01: 12:03 time02: null ampm: null
09-15 12:03:01.114  3410  4248 I CAE     : sendCmdToSensorHub(SensorHubCommManager.java:162) - -63, 23, 56, 4, 0, 0, 0, 110, 1,
09-15 12:03:01.114  3410  4248 D SensorHubManager: SendSensorHubData: send data = -63, 23, 56, 4, 0, 0, 0, 110, 1
09-15 12:03:01.114  3169  3208 D Sensorhubs: sendContextData: -63, 23, 56, 4, 0, 0, 0, 110, 1
,09-15 12:03:01.114  4751  4751 D RoamingTimeViewHolder: isDualClockSetting :: true isHomeTimeZoneExist :: false isEasyUxON :: false Utils.isRoaming(mContext) :: false
09-15 12:03:01.114  4751  4751 D RoamingTimeViewHolder: getHomeCalendar : No homecity_timezone, set as default :  (libcore.util.ZoneInfo[id="Europe/Warsaw",mRawOffset=3600000,mEarliestRawOffset=3600000,mUseDst=true,mDstSavings=3600000,transitions=167])
09-15 12:03:01.114  4751  4751 D RoamingTimeViewHolder: onTimeUpdate: isVisible:false timeZone:libcore.util.ZoneInfo[id="Europe/Warsaw",mRawOffset=3600000,mEarliestRawOffset=3600000,mUseDst=true,mDstSavings=3600000,transitions=167] text:czw., 15 wrz 12:03
,09-15 12:03:01.114  4751  4751 D DefaultClockView: show
09-15 12:03:01.114  3410  4248 I CAE     : setCAProperty(ContextAwareService.java:583) - result : true
09-15 12:03:01.114  3410  4248 W CAE     : setCAProperty(ContextAwareService.java:584) - [setProperty 02] Mutex is unlocked for DEVICE_PHYSICAL_CONTEXT_MONITOR
,09-15 12:03:01.114  4751  4751 D ViewRootImpl: #1 mView = com.samsung.android.app.aodservice.nightclock.DefaultClockView{3dc28ab V.E...... ......ID 0,0-0,0}
,09-15 12:03:01.114  3410  4123 W CAE     : setCAProperty(ContextAwareService.java:578) - [setProperty 01] Mutex is locked for DEVICE_PHYSICAL_CONTEXT_MONITOR
09-15 12:03:01.124  3410  3586 D PowerManagerUtil: Excessive delay in !@display_state: OFF: 180ms
09-15 12:03:01.124  3410  3586 D SurfaceControl: Excessive delay in setPowerMode(): 179ms
09-15 12:03:01.124  3410  3586 D PowerManagerUtil: Excessive delay in DisplayManagerInternal.requestDesiredDisplayState: 187ms
09-15 12:03:01.124  3410  4123 I CAE     : sendCmdToSensorHub(SensorHubCommManager.java:162) - -63, 23, 56, 4, 0, 0, 0, 17, 2,
09-15 12:03:01.124  3410  3576 D DisplayPowerController: animateScreenStateChange[0]: target=1
09-15 12:03:01.124  3410  4123 D SensorHubManager: SendSensorHubData: send data = -63, 23, 56, 4, 0, 0, 0, 17, 2
09-15 12:03:01.124  3410  3576 D DisplayPowerController: [Dual Screen Compatible] state[0] :1
09-15 12:03:01.124  3410  3576 I libsuspend: !@autosuspend_wakeup_count_enable
09-15 12:03:01.124  3410  3576 D DisplayPowerController: getFinalBrightness : Summary is 0 -> 0
09-15 12:03:01.124  3169  3169 D Sensorhubs: sendContextData: -63, 23, 56, 4, 0, 0, 0, 17, 2
09-15 12:03:01.124  3410  3576 D DisplayPowerController: Animating brightness: target=0, rate=0 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
09-15 12:03:01.124  3410  3576 I libsuspend: !@autosuspend_wakeup_count_enable done
09-15 12:03:01.124  3410  3576 I PowerManagerService: [PWL] Off : 0s ago
09-15 12:03:01.124  3410  4951 D ISSUE_DEBUG: InputChannelName : 16ffa1e AOD
09-15 12:03:01.124  3410  3576 I PowerManagerService: [PWL]   PowerManagerService.WakeLocks: ref count=1,
,09-15 12:03:01.124  3410  3901 D PersonaManagerService: onfinishedGoingToSleep why = 3
,09-15 12:03:01.124  3410  3576 I PowerManagerService: [PWL]     mWakeLockSummary : 0x1
09-15 12:03:01.124  3950  3966 D KeyguardViewMediator: onFinishedGoingToSleep(3)
09-15 12:03:01.124  3410  3576 I PowerManagerService: [PWL]       PARTIAL_WAKE_LOCK              'AlwaysOnDisplay_EnsureWorkingTime' (uid=10000, pid=4751, ws=null) (elapsedTime=84)
09-15 12:03:01.124  3950  3966 D KeyguardViewMediator: notifyFinishedGoingToSleep,
09-15 12:03:01.124  3410  3576 I PowerManagerService: [PWL]   PowerManagerService.Display: ref count=2
09-15 12:03:01.124  3410  4951 D InputDispatcher: Focus left window: 9956
09-15 12:03:01.124  3410  3576 I PowerManagerService: [PWL]     mUserActivitySummary : 0x4
,09-15 12:03:01.124  3410  4951 D InputDispatcher: Focus entered window: 4751
09-15 12:03:01.124  3410  3576 I PowerManagerService: [PWL]     mDisplayReady : false
09-15 12:03:01.124  3950  3950 D KeyguardViewMediator: handleNotifyFinishedGoingToSleep
09-15 12:03:01.124  3410  3576 D DisplayPowerController: animateScreenStateChange[0]: target=1
09-15 12:03:01.124  3950  3950 D KeyguardEffectViewController: onScreenTurnedOff
,09-15 12:03:01.124  3410  3576 D DisplayPowerController: [Dual Screen Compatible] state[0] :1
09-15 12:03:01.124  3950  3950 D KeyguardEffectViewController: ## mBackgroundView.onPause()
09-15 12:03:01.124  3410  3576 D DisplayPowerController: getFinalBrightness : Summary is 0 -> 0
09-15 12:03:01.124  3950  3950 D KeyguardEffectViewLayered: onPause()
09-15 12:03:01.124  3410  3576 D DisplayPowerController: Animating brightness: target=0, rate=0 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
09-15 12:03:01.124  3950  3950 D SecKeyguardStatusView: onFinishedGoingToSleep() why=3
,09-15 12:03:01.124  3410  3576 D PowerManagerService: [s] DisplayPowerCallbacks : onStateChanged()
09-15 12:03:01.124  3950  3950 V KeyguardFingerPrint: updateFingerprintListeningState(false)
09-15 12:03:01.124  3410  3576 D PowerManagerService: mDisplayReady: true
09-15 12:03:01.124  3950  3950 D KeyguardFingerPrint: shouldListenForFingerprint ( FingerPrint is not enabled. ) 
,09-15 12:03:01.124  3410  3576 D PowerManagerService: [PWL] sb release: PowerManagerService.Display
09-15 12:03:01.124  3950  3950 V KeyguardUpdateMonitor: stopListeningForFingerprint()
,09-15 12:03:01.124  3410  3576 D PowerManagerService: handleSandman : startDreaming: true  (canDreamLocked: false  canDozeLocked: true)
09-15 12:03:01.124  3950  3950 D PhoneStatusBar: setSystemUiVisibility vis=8000 mask=ffffffff oldVal=8600 newVal=8000 diff=600
09-15 12:03:01.124  3410  3576 D PowerManagerService: handleSandman : startDream(true)
09-15 12:03:01.124  3410  3572 D PointerIcon: setMouseIconStyle1 pointerType: 1001 iconType:101 flag:0 pid:3410 uid:1000
09-15 12:03:01.124  3410  3576 E PowerManagerService: handleSandman : startDreaming, but isDreaming false
09-15 12:03:01.124  3410  3572 D PointerIcon: setMouseCustomIcon IconType is same.101
09-15 12:03:01.124  3410  3576 I PowerManagerService: Sleeping (uid 1000)...
09-15 12:03:01.124  3410  3576 D PowerManagerService: [s] UserActivityState : 4 -> 0
09-15 12:03:01.134  3410  3606 D PersonaManagerServiceHandler: MSG_ACTION_SCREEN_OFF called
09-15 12:03:01.124  3410  3576 D PowerManagerService: [PWL] sb acquire: PowerManagerService.Broadcasts
09-15 12:03:01.134  3410  4123 I CAE     : setCAProperty(ContextAwareService.java:583) - result : true
09-15 12:03:01.124  3410  3542 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=Window{16ffa1e u0 d0 AOD}
09-15 12:03:01.134  3410  4123 W CAE     : setCAProperty(ContextAwareService.java:584) - [setProperty 02] Mutex is unlocked for DEVICE_PHYSICAL_CONTEXT_MONITOR
,09-15 12:03:01.144  3410  3410 D LightsService: [api] [SvcLED] setFlashing :: id = 5, color = 0, mode = 14, onMS = 0, offMS = 0,  (uid: 1000 pid: 3410) 
,09-15 12:03:01.154  3410  3410 D LightsService: [SvcLED] setSvcLedStateLocked:: SvcLEDState : 0x0 -> 0x40 | SvcLED(id=5) set On
,09-15 12:03:01.154  3410  3410 D SensorService: SensorEventConnection::SocketBufferSize, SystemSocketBufferSize - 102400, 2097152
,09-15 12:03:01.154  3410  3410 D SensorManager: registerListener :: 6, TMD4093 RGB Sensor, 200000, 0,  
09-15 12:03:01.154  3410  3583 D LightsService: [SvcLED]  onSensorChanged::light value = 14
09-15 12:03:01.154  3410  3410 D BatteryService: turn on LED for fully charged
,09-15 12:03:01.154  3410  3583 D SensorManager: unregisterListener ::   
09-15 12:03:01.154  3410  3583 D lights  : led_pattern : 5 +
,09-15 12:03:01.154  3410  3583 D lights  : led_pattern : 5 -
09-15 12:03:01.154  3410  3583 D LightsService: [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=5) maintains its priority right
,09-15 12:03:01.154  3410  3583 V AlarmManager:  remove PendingIntent] PendingIntent{54c9007: PendingIntentRecord{1e5a534 android broadcastIntent}}
,09-15 12:03:01.164  9882  9893 D BadgeProvider: query, [selection] : null
,09-15 12:03:01.184  4751  4751 D AODMissedEventController: [com.android.contacts] badgeCount : 0, [com.android.mms] badgeCount : 0
,09-15 12:03:01.184  4751  4751 I AODService.ClockTimer: startAlarm : TICK
,09-15 12:03:01.184  3410  3473 V AlarmManager: Add whitelist package alarm :PendingIntent{c16d2ff: PendingIntentRecord{e57db46 com.samsung.android.app.aodservice broadcastIntent}}
,09-15 12:03:01.184  3410  3410 I CAE     : handleMessage(CaPowerManager.java:182) - AP_SLEEP
,09-15 12:03:01.184  4751  4751 I AODService.ClockTimer: startAlarm : SLEEP
09-15 12:03:01.184  3410  3410 I CAE     : updateApPowerStatus(SensorHubParserProvider.java:443) - AP_SLEEP
09-15 12:03:01.184  3410  3410 I CAE     : sendCmdToSensorHub(SensorHubCommManager.java:162) - -76, 13, -46, 0,
09-15 12:03:01.184  3410  3410 D SensorHubManager: SendSensorHubData: send data = -76, 13, -46, 0
09-15 12:03:01.184  3169  3208 D Sensorhubs: sendContextData: -76, 13, -46, 0
09-15 12:03:01.184  3410  3410 I CAE     : sendCmdToSensorHub(SensorHubCommManager.java:162) - -63, 14, 10, 3, 1,
,09-15 12:03:01.184  3410  3410 D SensorHubManager: SendSensorHubData: send data = -63, 14, 10, 3, 1
09-15 12:03:01.184  3169  3169 D Sensorhubs: sendContextData: -63, 14, 10, 3, 1
09-15 12:03:01.184  4751  4751 V AODService.ClockTimer: AOD Trigger: next AOD WAKEUP time is 9:0
,09-15 12:03:01.194  4751  4751 D AODService.ClockTimer: startAlarm is canceled. triggerAtMillis = -1, currentTime = 1473933781195
09-15 12:03:01.194  4751  4751 I AODService.ClockTimer: stopAlarm : WAKEUP
09-15 12:03:01.194  3410  3971 V AlarmManager:  remove PendingIntent] PendingIntent{a3bb8cc: PendingIntentRecord{7a665d2 com.samsung.android.app.aodservice broadcastIntent}}
,09-15 12:03:01.194  4751  4751 D BatteryController: saveBatteryData : level[100], status[5]
,09-15 12:03:01.194  3410  3410 D MotionRecognitionService:   mReceiver.onReceive : ACTION_SCREEN_OFF
,09-15 12:03:01.194  3009  3009 I SurfaceFlinger: id=24 createSurf (1x1),1 flag=404, BOD
,09-15 12:03:01.194  3410  3979 V WindowOrientationListener: setCurrentAppOrientation :5
09-15 12:03:01.194  3410  3979 V WindowManager: rotationForOrientationLw(orient=5, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false mMobileKeyboardEnabled=false displayId=0
,09-15 12:03:01.204  3410  3823 D MotionRecognitionService: Screen off setAccIntStatus 
,09-15 12:03:01.204  3410  3823 E MotionRecognitionService:  handler : SCREEN_OFF end 
,09-15 12:03:01.214  4751  7112 D mali_winsys: EGLint new_window_surface(egl_winsys_display*, void*, EGLSurface, EGLConfig, egl_winsys_surface**, egl_color_buffer_format*, EGLBoolean) returns 0x3000,  [1440x2560]-format:1
,09-15 12:03:01.214  3410  3541 I ActivityManager: Start proc 10028:com.samsung.android.SettingsReceiver/1000 for broadcast-3 com.samsung.android.SettingsReceiver/.AccessibilityReceiver
,09-15 12:03:01.224 10028 10028 E Zygote  : v2
09-15 12:03:01.224 10028 10028 I libpersona: KNOX_SDCARD checking this for 1000
09-15 12:03:01.224 10028 10028 I libpersona: KNOX_SDCARD not a persona
09-15 12:03:01.224 10028 10028 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0013
,09-15 12:03:01.224 10028 10028 E Zygote  : accessInfo : 0
09-15 12:03:01.224  3410  4424 D InputMethodManagerService: windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
09-15 12:03:01.224  3410  3410 D UniversalCredentialManagerService: inside mBReciever onReceive : android.intent.action.SCREEN_OFF
,09-15 12:03:01.224  3410  3410 D UniversalCredentialManagerService: ****MSG_LOCK_STATUS_UPDATE block started****
09-15 12:03:01.224  3410  3410 D UniversalCredentialManagerService: notifyChangeToPlugin is called for Lock status update...
09-15 12:03:01.224  7169  7169 D SamsungIME: IMPL finishInput
09-15 12:03:01.224  3410  3410 D UcmService: notifyChangeToPlugin event 16
09-15 12:03:01.224  3410  3410 D UcmService: checkCallerPermissionFor is called for method-notifyChangeToPlugin
09-15 12:03:01.224  7169  7169 D SamsungIME: SwiftKeyWrapper writeDBdataToFileOnFinishInput
09-15 12:03:01.224  7169  7169 D SamsungIME: saveAndClear +
09-15 12:03:01.224  3410  3410 I UcmService: checkIfNotify for cs Name = com.sec.smartcard.manager:com.samsung.ucs.agent.baiMobile Package name = com.sec.smartcard.manager
,09-15 12:03:01.224  3410  3410 D UcmService: notifying to unmanaged plugin
09-15 12:03:01.224  7169  7169 D SamsungIME: saveAndClear -
09-15 12:03:01.234  4342  4411 E ucsBai_agentService: notifyChange NOT SUPPORTED
09-15 12:03:01.234  3410  3410 D UcmService: agentService com.sec.smartcard.manager:com.samsung.ucs.agent.baiMobile notify status - 0
09-15 12:03:01.234  3410  3410 D UcmService: agentService status-0
09-15 12:03:01.234  3410  3410 I UcmService: checkIfNotify for cs Name = com.samsung.ucs.agent.ese:eSE Credential Storage Package name = com.samsung.ucs.agent.ese
09-15 12:03:01.234  3410  3410 D UcmService: notifying to managed plugin
,09-15 12:03:01.234  3410  3410 D UcmService: checkIfNotify: Valid userid - 0
09-15 12:03:01.234  3410  3410 D PolicyManager: PolicyManager.isStorageEnabled() for userId = 0
09-15 12:03:01.234  3410  3410 D UniversalCredentialManagerService: checkCallerPermissionFor is called for method-isCredentialStorageManagedAsUser
09-15 12:03:01.234  3410  3410 D UniversalCredentialManagerService: isCredentialStorageManagedAsUser is called....
09-15 12:03:01.234  3410  3410 D PolicyManager: PolicyManager.isStorageEnabled() result = false
09-15 12:03:01.234  3410  3410 D UcmService: agentService com.samsung.ucs.agent.ese:eSE Credential Storage not notified
09-15 12:03:01.234  3410  3410 D UcmService: agentService status-0
09-15 12:03:01.234  3410  3410 I UcmService: checkIfNotify for cs Name = com.samsung.ucs.agent.boot:com.samsung.ucs.agent.boot Package name = com.samsung.ucs.agent.boot
,09-15 12:03:01.234  3410  3410 D UcmService: notifying to unmanaged plugin
,09-15 12:03:01.234  4352  4409 D BootAgentService: notifyChange eventId-16
,09-15 12:03:01.234  3410  3410 D UcmService: agentService com.samsung.ucs.agent.boot:com.samsung.ucs.agent.boot notify status - -1
09-15 12:03:01.234  3410  3410 D UcmService: agentService status--1
,09-15 12:03:01.234  3410  3410 D UniversalCredentialManagerService: ****MSG_LOCK_STATUS_UPDATE block ended****
,09-15 12:03:01.234  3410  3572 V WindowAnimator: hide by NightClock Window{ff92b92 u0 d0 StatusBar}
09-15 12:03:01.234  7169  7169 D SamsungIME: onStartInput: No inputType, No imeOption, isInputViewShown = false, isExtractViewShown = false, isShowInputRequested = false, isConfigChanged = false
09-15 12:03:01.234  4751  4751 D ViewRootImpl: MSG_RESIZED_REPORT: ci=Rect(0, 0 - 0, 0) vi=Rect(0, 0 - 0, 0) or=1
,09-15 12:03:01.244  4751  4751 W DisplayListCanvas: DisplayListCanvas is started on unbinded RenderNode (without mOwningView)
,09-15 12:03:01.244  3410  3981 W InputMethodManagerService: Starting input on non-focused client com.android.internal.view.IInputMethodClient$Stub$Proxy@7840715 (uid=10177 pid=9956)
,09-15 12:03:01.254  3410  4951 V WindowStateAnimator: Finishing drawing window Window{16ffa1e u0 d0 AOD}: mDrawState=DRAW_PENDING
,09-15 12:03:01.254  3410  3410 I WifiTrafficPoller: evaluateTrafficStatsPolling
,09-15 12:03:01.254  3410  3797 I Sensors : #>LightSensor r=14 g=11 b=9 c=33 atime=245 again=64 lux=26
,09-15 12:03:01.254  4751  4751 I AODService: onSensorChanged: lux [26.0], NIT state [HIGH]
,09-15 12:03:01.254  3009  3009 D libEGL  : eglInitialize EGLDisplay = 0x7ff285be68
,09-15 12:03:01.264 10028 10028 D TimaKeyStoreProvider: TimaSignature is unavailable
09-15 12:03:01.264 10028 10028 D ActivityThread: Added TimaKeyStore provider
09-15 12:03:01.264  3410  3858 D WifiStateMachine: handleScreenStateChanged, screen off, set scan interval as max value  !!!
09-15 12:03:01.264  3410  3858 D WifiNative-wlan0: callSECApiVoid - ID [19]
,09-15 12:03:01.264  3410  3410 D NotificationService: ACTION_SCREEN_OFF
09-15 12:03:01.264  4124  4124 I wpa_supplicant: set PERIODIC_SCAN_INTERVAL_MAX to 128sec !!!
09-15 12:03:01.264  3410  3410 D LightsService: [api] [SvcLED] turnOff:: id = 6 (uid: 1000 pid: 3410) 
09-15 12:03:01.264  3950  3950 D PanelView: updateQsState
09-15 12:03:01.264  3410  3410 D LightsService: [SvcLED] setSvcLedStateLocked:: SvcLEDState : 0x40 -> 0x40 | SvcLED(id=6) set Off
09-15 12:03:01.264  3950  3950 D KeyguardCircleAffordanceView: setPreviewView: mRight=false,preview=null
09-15 12:03:01.264  3410  3583 D LightsService: [SvcLED]  onSensorChanged::light value = 26
09-15 12:03:01.264  3410  3410 D SensorService: SensorEventConnection::SocketBufferSize, SystemSocketBufferSize - 102400, 2097152
09-15 12:03:01.264  3950  3950 D KeyguardCircleAffordanceView: setPreviewView: mRight=true,preview=null
09-15 12:03:01.264  3410  3583 I LightsService: fileWriteInt : /sys/class/sec/led/led_lowpower  value : 0
09-15 12:03:01.264  3410  3410 D SensorManager: registerListener :: 6, TMD4093 RGB Sensor, 200000, 0,  
09-15 12:03:01.264  3410  3410 D EdgeLight: Turning off
09-15 12:03:01.264  3950  3950 D KeyguardSwipeHelper: reset()
09-15 12:03:01.264  3950  3950 D KeyguardUnlockEventHandler: reset()
09-15 12:03:01.264  3950  3950 D KeyguardSwipeHelper: resetChildViewVI()
09-15 12:03:01.264  3410  3583 D SensorManager: unregisterListener ::   
09-15 12:03:01.264  3410  3583 D lights  : led_pattern : 5 +
,09-15 12:03:01.264  3410  3858 E WifiNative-wlan0: do suspend true
,09-15 12:03:01.264  3410  3583 D lights  : led_pattern : 5 -
,09-15 12:03:01.264  3410  3583 D LightsService: [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=5) maintains its priority right
09-15 12:03:01.274  3410  3583 V AlarmManager:  remove PendingIntent] PendingIntent{54c9007: PendingIntentRecord{1e5a534 android broadcastIntent}}
,09-15 12:03:01.274  4150  4161 D PeopleNotiListenerService: onEdgeNotificationRemoved() : pkg android,id=0,extra=Bundle[mParcelledData.dataSize=112]
,09-15 12:03:01.274  4150  4150 D PeopleNotiListenerService: removeEdgeNotification:Bundle[{samsung.notification.id=0, samsung.people.package_name=android, samsung.people.notification_type=led_indicator}]
09-15 12:03:01.274  3162  3859 D audio_hw_primary: adev_set_parameters: enter: kvpairs: screen_state=off
09-15 12:03:01.274  4150  4150 I PeopleStripeService: PeopleNotificationReceiver:3
,09-15 12:03:01.284  4150  4150 I PeopleStripeService: sendEdgeNotification  peopleEnabled true lightingEnabled true edgeEnabled true
09-15 12:03:01.284  4150  4150 I PeopleDataManager: removeNotification
09-15 12:03:01.284  4150  4150 I NotificationParser: getNotiType:android,led_indicator
09-15 12:03:01.284  4150  4150 D PeopleDataManager: removeNotiInfo: id =0,packageName=android,isEdgeNotification=true,key=null,removeAll=false
09-15 12:03:01.284  4150  4150 D PeopleDataManager: removeNotiInfo =null
,09-15 12:03:01.294  3410  3971 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{c9d9a2a u-1 com.samsung.settings.action.directaccess.CLOSE_DIALOG qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{a8fa01b 10028:com.samsung.android.SettingsReceiver/1000}
,09-15 12:03:01.304 10028 10028 D ContextRelationManager: ContextRelationManager() : FEATURE_ENABLED=true
,09-15 12:03:01.304 10028 10028 D RelationGraph: garbageCollect()
,09-15 12:03:01.314 10028 10028 W ResourcesManager: getTopLevelResources: /system/priv-app/SettingsReceiver/SettingsReceiver.apk / 1.0 running in com.samsung.android.SettingsReceiver rsrc of package com.samsung.android.SettingsReceiver
,09-15 12:03:01.314  3410  3410 I MdnieScenarioControlService: action  :  android.intent.action.SCREEN_OFF
,09-15 12:03:01.314  3410  4190 I InjectionManagerService -AppFeature: getCoreFeaturePkgList :[]
09-15 12:03:01.314 10028 10028 I InjectionManager: Inside getClassLibPath + mLibMap{0=, 1=}
,09-15 12:03:01.314  3410  3410 I FingerprintService: onReceive: android.intent.action.SCREEN_OFF
,09-15 12:03:01.314 10028 10028 D ResourcesManager: For user 0 new overlays fetched Null
,09-15 12:03:01.314  3410  3410 I BackgroundCompactionService: Schedule Type1 BGCompaction
,09-15 12:03:01.314 10028 10028 I InjectionManager: Inside getClassLibPath caller 
,09-15 12:03:01.324  3410  3410 D WifiService: ACTION_SCREEN_OFF, mSContextManager.unregisterListener !!
,09-15 12:03:01.324  3410  3410 D SContextService: unregisterCallback() : Listener = android.hardware.scontext.SContextService$Listener@a1370fa, Service = Activity Tracker, used = 0
09-15 12:03:01.324  3410  3862 D WifiController: ApOrStaEnabledState  msg.what= 155651
09-15 12:03:01.324  3410  3410 W CAE     : unregisterCallback(ContextAwareService.java:206) - [unregi 01] Mutex is locked for ACTIVITY_TRACKER
09-15 12:03:01.324  3410  3410 V CAE     : stop(ContextProvider.java:155)
,09-15 12:03:01.324  3410  3410 V CAE     : clear(ActivityTrackerRunner.java:108)
09-15 12:03:01.324  3410  3410 V CAE     : disable(ActivityTrackerRunner.java:96)
,09-15 12:03:01.324  3410  3410 I CAE     : sendCmdToSensorHub(SensorHubCommManager.java:162) - -78, 26, 0, 0, 0, 0, 0, 0, 0, 0,
,09-15 12:03:01.324  3410  3410 D SensorHubManager: SendSensorHubData: send data = -78, 26, 0, 0, 0, 0, 0, 0, 0, 0
09-15 12:03:01.324  3169  3208 D Sensorhubs: sendContextData: -78, 26, 0, 0, 0, 0, 0, 0, 0, 0
09-15 12:03:01.324 10028 10028 W System  : ClassLoader referenced unknown path: /system/priv-app/SettingsReceiver/lib/arm64
09-15 12:03:01.324 10028 10028 D InjectionManager: InjectionManager
09-15 12:03:01.324 10028 10028 D InjectionManager: fillFeatureStoreMap com.samsung.android.SettingsReceiver
09-15 12:03:01.324 10028 10028 I InjectionManager: Constructor com.samsung.android.SettingsReceiver, Feature store :{}
09-15 12:03:01.324 10028 10028 I InjectionManager: featureStore :{}
,09-15 12:03:01.334  3410  4424 I ActivityManager: Killing 8437:com.samsung.android.coreapps/5011 (adj 15): DHA:empty #33
,09-15 12:03:01.344  3410  3410 D CAE     : getFaultDetectionResult(ActivityTrackerRunner.java:154) - true
,09-15 12:03:01.344  3410  3410 I CAE     : notifyCmdProcessResultObserver(ContextProvider.java:627) - CheckResult = 0, Cause = Success
,09-15 12:03:01.354  3410  3410 D CAE     : doCommendProcess(ContextAwareService.java:433) - complete notify the operation result.
,09-15 12:03:01.354  3410  3410 I CAE     : displayUsedCountForService(ContextAwareService.java:525) - totalCnt = 0, serviceCount = 0, subCollectionCount = 0
09-15 12:03:01.354  3410  3410 D CAE     : showListenerList(ContextAwareService.java:366) - ===== Context Aware Service List =====
,09-15 12:03:01.354  3410  3410 I CAE     : showListenerList(ContextAwareService.java:375) - Listener : com.samsung.android.contextaware.manager.ContextAwareService$Listener@4604ec9, Service : ACTIVITY_TRACKER_CURRENT_INFO(1)
,09-15 12:03:01.354  3410  3410 I CAE     : showListenerList(ContextAwareService.java:375) - Listener : com.samsung.android.contextaware.manager.ContextAwareService$Listener@eefdfa3, Service : DEVICE_PHYSICAL_CONTEXT_MONITOR(1)
09-15 12:03:01.354  3410  3410 W CAE     : unregisterCallback(ContextAwareService.java:241) - [unregi 02] Mutex is unlocked for ACTIVITY_TRACKER
09-15 12:03:01.354  3410  3410 D SContextService: 	.unregisterCallback : 2, client=
09-15 12:03:01.354  3410  3410 D SContextService: ===== SContext Service List =====
09-15 12:03:01.354  3410  3410 D SContextService: Listener : android.hardware.scontext.SContextService$Listener@d5812a0, Service : Device Physical Context Monitor
09-15 12:03:01.354  3410  3410 D SContextManager:   .unregisterListener : listener = com.android.server.wifi.WifiServiceImpl$11@f82b725, service=Activity Tracker
,09-15 12:03:01.364  9956 10025 W jxcore-log: Initializing JXcore engine
09-15 12:03:01.364  9956 10025 W jxcore-log: JXcore engine is ready
,09-15 12:03:01.364  3410  3572 D IpRemoteDisplayController: intent received android.intent.action.SCREEN_OFF
09-15 12:03:01.364  3410  3572 D IpRemoteDisplayController: Bridge Server is not available
,09-15 12:03:01.364  3410  3410 D NetworkPolicy: mScreenReceiver: ACTION_SCREEN_OFF, extra: 3
09-15 12:03:01.364  3410  3856 D NetworkPolicy: MSG_SCREEN_ON_CHANGED: 3
09-15 12:03:01.364  3410  3856 D NetworkPolicy: isUidForegroundLocked: 10009, mScreenOn: false, uidstate: 0, mProxSensorScreenOff: false
,09-15 12:03:01.364  3410  3856 D NetworkPolicy: isUidForegroundLocked: 10065, mScreenOn: false, uidstate: 0, mProxSensorScreenOff: false
,09-15 12:03:01.374  3410  4190 D ActivityManager: isAutoRunBlockedApp:: com.samsung.android.coreapps, Auto Run ON
,09-15 12:03:01.384  3410  3536 D GpsLocationProvider: receive broadcast intent, action: android.intent.action.SCREEN_OFF
,09-15 12:03:01.384  5044  5044 E audit   : type=1400 msg=audit(1473933781.384:264): avc:  denied  { ioctl } for  pid=10025 comm="Thread-161" path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=3095 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
09-15 12:03:01.384  5044  5044 E audit   :  SEPF_SECMOBILE_6.0.1_0013
09-15 12:03:01.384  5044  5044 E audit   : type=1300 msg=audit(1473933781.384:264): arch=40000028 syscall=54 per=8 success=no exit=-13 a0=8 a1=5451 a2=2 a3=d12f93c8 items=0 ppid=3186 pid=10025 auid=4294967295 uid=10177 gid=10177 euid=10177 suid=10177 fsuid=10177 egid=10177 sgid=10177 fsgid=10177 tty=(none) ses=4294967295 comm="Thread-161" exe="/system/bin/app_process32" subj=u:r:untrusted_app:s0:c512,c768 key=(null)
09-15 12:03:01.384  5044  5044 E audit   : type=1327 msg=audit(1473933781.384:264): proctitle="com.test.thalitest"
09-15 12:03:01.384  5044  5044 E audit   : type=1320 msg=audit(1473933781.384:264): 
09-15 12:03:01.384  5044  5044 E audit   : type=1400 msg=audit(1473933781.384:265): avc:  denied  { ioctl } for  pid=10025 comm="Thread-161" path="socket:[36385]" dev="sockfs" ino=36385 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
09-15 12:03:01.384  5044  5044 E audit   :  SEPF_SECMOBILE_6.0.1_0013
09-15 12:03:01.384  5044  5044 E audit   : type=1300 msg=audit(1473933781.384:265): arch=40000028 syscall=54 per=8 success=no exit=-13 a0=3b a1=5451 a2=2 a3=d12f93c8 items=0 ppid=3186 pid=10025 auid=4294967295 uid=10177 gid=10177 euid=10177 suid=10177 fsuid=10177 egid=10177 sgid=10177 fsgid=10177 tty=(none) ses=4294967295 comm="Thread-161" exe="/system/bin/app_process32" subj=u:r:untrusted_app:s0:c512,c768 key=(null)
09-15 12:03:01.384  5044  5044 E audit   : type=1327 msg=audit(1473933781.384:265): proctitle="com.test.thalitest"
09-15 12:03:01.384  5044  5044 E audit   : type=1320 msg=audit(1473933781.384:265): 
,09-15 12:03:01.394  9956 10025 W jxcore-log: Starting JXcore engine
,09-15 12:03:01.394  4224  4224 D FusedLocationReceiver: BroadcastReceiver : ACTION_SCREEN_OFF
,09-15 12:03:01.404  4276 10041 D NfcService: call the applyRouting
,09-15 12:03:01.414  3950  4135 D NetworkController.MobileSignalController(0/2147483643): onDataActivity: direction=0
,09-15 12:03:01.424  4300  4300 D Launcher.Workspace: exitWidgetResizeMode. isClearResizeFrame is false
,09-15 12:03:01.434  3410  3797 I Sensors : #>LightSensor r=14 g=10 b=9 c=32 atime=245 again=64 lux=24
,09-15 12:03:01.444  9956 10025 W jxcore-log: Platform android
09-15 12:03:01.444  9956 10025 W jxcore-log: 
,09-15 12:03:01.444  9956 10025 W jxcore-log: Process ARCH arm
09-15 12:03:01.444  9956 10025 W jxcore-log: 
,09-15 12:03:01.464  5031  5031 D BtGatt.GattService: LCD turned off
09-15 12:03:01.464  5031  5219 D BtGatt.ScanManager: handleLcdOffIntent
09-15 12:03:01.464  5031  5219 D BtGatt.ScanManager: handleLcdOffIntent : thresholdScanValue is = 10 mLastConfiguredScanValue =0
,09-15 12:03:01.504  4578 10042 D MdnsClient: Multicast lock held. Releasing
,09-15 12:03:01.514  6198  6198 D CocktailBarUiController: ACTION_SCREEN_OFF
09-15 12:03:01.514  6198  6198 D AbstractCocktailPanelView: setPanelVisible: CocktailPortraitRemotePanelViewfalse will be hiden: 3
09-15 12:03:01.514  6198  6198 D CocktailBarPanelVisibilityManager: updateActivePanelView:  vis=false screenOn=false onTransit=false -hide: 3 current Active: 3
,09-15 12:03:01.514  6198  6198 E AbstractCocktailPanelView: notifyPanelVisibilityChanged: visibility not changed 2 id: 3
09-15 12:03:01.514  6198  6198 I TrayVisibilityController: handleMessage : msg.what = 1
,09-15 12:03:01.524  6198  6198 I Utils   : isCurrentUser current = 0, ownerId = 0
09-15 12:03:01.524  6198  6198 I TrayVisibilityController: getComputedTrayVisible : keyguardState = 3
09-15 12:03:01.524  6198  6198 I TrayVisibilityController: updateTrayVisible : State : 3 visible = 2 mCurrentVisible = 1
,09-15 12:03:01.524  6198  6198 D TrayStateController: putInputRect mDynamicInputRegion=135622831@LastEvent=t=1473933735741Rect(8, 0 - 64, 588),Rect=Rect(0, 0 - 0, 0)
09-15 12:03:01.524  4150  4150 D PeopleStripeService: ACTION_SCREEN_OFF
09-15 12:03:01.524  4150  4150 D PeopleStripeManager: requestCloseCircleViews()
09-15 12:03:01.524  4150  4150 I CircleImageSaveLayout: hideImageSaveLayout()
09-15 12:03:01.524  4150  4150 D CircleImageSaveLayout: releaseWakeLock()
09-15 12:03:01.524  4150  4150 D SweepImageListView: hide
09-15 12:03:01.524  4150  4150 D SweepImageListView: setAdapter mAdapter =null:30157432
09-15 12:03:01.524  4150  4150 I PeopleEdgeCommContainer: hideEffectView() 
09-15 12:03:01.524  4150  4150 I CirclePokingManager: stopParticleEffectView  mParticleEffectView-null
09-15 12:03:01.524  4150  4150 I PeopleDataManager: deleteMarkedCircleEvent : people = null
09-15 12:03:01.524  4150  4150 I PeopleEdgeCommContainer: setPeopleChannelShowStatus false
09-15 12:03:01.524  6198  6198 D TrayStateController: setUiState: 0 --> 2
,09-15 12:03:01.524  3410  3881 I AbsCocktailBarStatePolicy: handleMessage: entry what = 1
09-15 12:03:01.524  4150  4150 I PeopleStripeWindow: updateWindowParam : minimize=true,mLastMinimized=true,color0 blur true
,09-15 12:03:01.534  4150  4150 D PeopleStripeVisibilityController: setEmoHistory enable=false
,09-15 12:03:01.534  4150  4150 I PeopleStripeVisibilityController: getComputedTrayVisible : keyguardState = 1
09-15 12:03:01.534  4150  4150 I PeopleStripeVisibilityController: isVisibleByAlwaysOn : mState = 1
09-15 12:03:01.534  4150  4150 E PeopleStripeProcessMonitor: getTopActivity : MultiWindowFacade.taskList = []
,09-15 12:03:01.534  4150  4150 I PeopleStripeProcessMonitor: isPeopleStripeTask packageName = com.test.thalitest 0
,09-15 12:03:01.534  4150  4150 E PeopleStripeProcessMonitor: getTopActivity : MultiWindowFacade.taskList = []
,09-15 12:03:01.534  4150  4150 I PeopleStripeVisibilityController: updateStripeVisible : State 1 visible = 1
,09-15 12:03:01.534  4150  4150 I PeopleStripeManager: isExistVisibleHandler false
09-15 12:03:01.534  4150  4150 I PeopleStripeManager: showStripe Not exist noti handler.
09-15 12:03:01.534  4150  4150 I PeopleStripeManager: hideStripe
09-15 12:03:01.534  4150  4150 D PeopleStripeManager: onVisibilityChanged : 2
09-15 12:03:01.534  4150  4150 D PeopleStripeVisibilityController: setHiddenEdgePanel enable=true
09-15 12:03:01.534  4150  4150 I PeopleStripeVisibilityController: updateStripeVisible : State 1028 visible = 2
09-15 12:03:01.534  4150  4150 I PeopleStripeManager: hideStripe
,09-15 12:03:01.544  9956 10025 I jxcore-log: JXcore Cordova bridge is ready!
09-15 12:03:01.544  9956 10025 I jxcore-log: 
,09-15 12:03:01.544  9956 10025 W jxcore-log: JXcore engine is started
09-15 12:03:01.544  3410  6444 D SSRM:n  : SIOP:: AP = 310, PST = 302 (W:6), CP = 247, CUR = 142, LCD = 0
,09-15 12:03:01.554  3009  3017 D libEGL  : eglTerminate EGLDisplay = 0x7fb1d80e78
,09-15 12:03:01.554  9956 10020 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,09-15 12:03:01.554  3009  4466 I SurfaceFlinger: id=20 Removed DocktailBar (8/12)
,09-15 12:03:01.554  3009  4362 I SurfaceFlinger: id=20 Removed DocktailBar (-2/12)
09-15 12:03:01.554  3410  3410 I SurveyLogManager: mDeviceInfo.mScreen = false
,09-15 12:03:01.554  9956  9956 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
09-15 12:03:01.554  3009  3009 D libEGL  : eglTerminate EGLDisplay = 0x7ff285bf88
,09-15 12:03:01.564  3410  6444 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
,09-15 12:03:01.574  6198  6198 D CocktailBarUiController: onCocktailBarStateChanged: flag=0x1 vis=2 bgType=0 showTimeout=-1 activate=true
,09-15 12:03:01.594  7169  7169 E SamsungIME: invoke(): method is null
,09-15 12:03:01.594  4645  4645 D [Weather Widget]  WeatherService: {[EC3334F14841398C8B464A72D0E61AB7C564889C89112557F2146D56794659083956C77974A4825103AB5C5D4AC85EDA0E41DE4F26DD020CF7906DED0A6ECA9F]}
,09-15 12:03:01.594  4645  4645 D [Weather Widget]  WeatherService: {[EC3334F14841398C8B464A72D0E61AB71D02215B774510884CB3BFD0FBDB0EDC]}
,09-15 12:03:01.594  4645  4645 D [Weather Widget]  : {[3AE6950019B083611567B0F9442DB03EEFA9050249635C043F7E254E316C2550]}
,09-15 12:03:01.604  3410  3901 D PowerManagerService: [PWL] sb release: PowerManagerService.Broadcasts
,09-15 12:03:01.614  4645  4645 D [Weather Widget]  WeatherService: {[44BE909F148A112BE24DB9207B7094FCDA9342562AE17780A60BEC6E95DC6F0D]}
,09-15 12:03:01.614  3410  4951 I ActivityManager: Killing 9330:com.samsung.android.app.aodservice:settingui/u0a0 (adj 15): DHA:empty #33
,09-15 12:03:01.614  3410  3797 I Sensors : #>LightSensor r=14 g=11 b=9 c=32 atime=245 again=64 lux=24
,09-15 12:03:01.634  3410  4248 D ActivityManager: isAutoRunBlockedApp:: com.samsung.android.app.aodservice, Auto Run ON
,09-15 12:03:01.644  3410 10043 I BatteryStatsDumper: In refreshStats isReason Screen ON/OFF: true
09-15 12:03:01.654  3410 10043 D BluetoothAdapter: STATE_ON
,09-15 12:03:01.654  3410  3979 V AlarmManager:  remove PendingIntent] PendingIntent{5532ef6: PendingIntentRecord{e9a4bf3 com.android.bluetooth broadcastIntent}}
,09-15 12:03:01.664  3410  4714 V AlarmManager:  remove PendingIntent] PendingIntent{4fe22f7: PendingIntentRecord{e9a4bf3 com.android.bluetooth broadcastIntent}}
,09-15 12:03:01.694  3410 10043 D BatteryStatsImpl: poolsize= 1, curBatteryRealtime= 0, mUpdateTime= 0, mTimeout= 0, mNesting= 0, mTotalTime= 0
,09-15 12:03:01.714  3410 10043 D BatteryStatsImpl: poolsize= 1, curBatteryRealtime= 0, mUpdateTime= 0, mTimeout= 0, mNesting= 0, mTotalTime= 0
,09-15 12:03:01.714  3410 10043 I BatteryStatsDumper: Previous Battery Level: 100 Current Level: 100 Delta: 0
,09-15 12:03:01.744  4751  4751 I AlpmModeManager: startAlpmMode : state  = IDLE
,09-15 12:03:01.744  4751  4751 I AlpmModeManager: handleUnblankDisplay: state  = IDLE
09-15 12:03:01.744  4751  4751 V AlpmModeManager: handleUnblankDisplay: setDoze [DISPLAY_STATE_DOZE]
09-15 12:03:01.744  4751  4751 D AlpmModeManager: getLastAlpmHlpmBright : HighNit[true], AlpmHlpm[1], NitMode[[ALPM]_60NIT_ON]
09-15 12:03:01.744  3410  4251 I PowerManagerService: [api] setDozeOverrideFromAod AlpmHlpmSysfs = 3, screenState = 3, Brightness = 0, wakefulness = false
,09-15 12:03:01.744  3410  4251 D PowerManagerService: [s] UserActivityState : 0 -> 4
09-15 12:03:01.744  4751  4751 I AlpmModeManager: handleUnblankDisplay: AlpmModeManager wakeLock [ACQUIRE]
09-15 12:03:01.744  3410  3474 D PowerManagerService: [api] acquire WakeLock flags=0x40 tag=AlpmModeManager uid=10000 pid=4751
09-15 12:03:01.744  3410  3474 I libsuspend: !@autosuspend_wakeup_count_disable
,09-15 12:03:01.744  3410  3474 D PowerManagerService: mDisplayReady: false
09-15 12:03:01.744  3410  3474 I libsuspend: !@autosuspend_wakeup_count_disable done
09-15 12:03:01.744  3410  3576 D DisplayPowerController: animateScreenStateChange[0]: target=3
09-15 12:03:01.744  3410  3474 D PowerManagerService: [PWL] sb acquire: PowerManagerService.Display
09-15 12:03:01.744  3410  3576 D DisplayPowerState: !@ [0] ColorFade exit
09-15 12:03:01.744  3410  3576 D PowerManagerService: [input device light] onColorFadeExit(true)
,09-15 12:03:01.754  3009  3017 D libEGL  : eglTerminate EGLDisplay = 0x7fb1d80e78
,09-15 12:03:01.754  3009  3017 D libEGL  : eglTerminate EGLDisplay = 0x7fb1d80e78
,09-15 12:03:01.754  3009  4466 I SurfaceFlinger: id=22 Removed DolorFade (9/11)
,09-15 12:03:01.754  3009  4362 I SurfaceFlinger: id=22 Removed DolorFade (-2/11)
09-15 12:03:01.754  3410  3576 D DisplayPowerController: [Dual Screen Compatible] state[0] :3
09-15 12:03:01.754  3410  3576 D DisplayPowerController: getFinalBrightness : Summary is 1 -> 1
09-15 12:03:01.754  3410  3576 D DisplayPowerController: Animating brightness: target=1, rate=2000 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
09-15 12:03:01.754  3410  3576 D DisplayPowerState: Requesting new screen state: [0] state=DOZE, backlight (By colorFade)=0
09-15 12:03:01.754  3410  3904 D DisplayPowerState: Updating screen state [0]: state=DOZE, backlight (by ColorFade)=0
09-15 12:03:01.754  3410  3586 D DisplayManagerService: !@display_state: OFF -> DOZE brightness: 0 -> 0
09-15 12:03:01.754  3410  3572 I DisplayManagerService: Display device changed state: "Wbudowany ekran", DOZE
09-15 12:03:01.754  3009  3009 D SurfaceFlinger: Set power mode=1, type=0 flinger=0x7fb2003c00
09-15 12:03:01.754  3410  3572 I DisplayManagerService: Display device changed state: "ActivityViewVirtualDisplay", DOZE
09-15 12:03:01.754  3009  3009 I hwcomposer: int exynos_setPowerMode(hwc_composer_device_1*, int, int):: disp(0), mode(1)
,09-15 12:03:01.764  6198  6198 E CocktailBarPositionManager: Window direction: 0
09-15 12:03:01.764  6198  6198 I CocktailBarPositionManager: updateAlphaScreenPosition position is dirty 0
,09-15 12:03:01.774  3410  4190 D PowerManagerService: [api] acquire WakeLock flags=0x80 tag=Window:AOD uid=1000 pid=3410
,09-15 12:03:01.774  3410  4425 D PowerManagerService: [api] acquire WakeLock flags=0x80 tag=Window:com.test.thalitest/com.test.thalitest.MainActivity uid=1000 pid=3410
,09-15 12:03:01.784  3410 10043 I BatteryStatsDumper: Writing to database completed
,09-15 12:03:01.794  3410  3904 D lights  : lcd : 1 +
09-15 12:03:01.794  3410  3576 D DisplayPowerController: animateScreenStateChange[0]: target=3
09-15 12:03:01.794  3410  3904 D lights  : lcd : 1 -
09-15 12:03:01.794  3410  3576 D DisplayPowerController: [Dual Screen Compatible] state[0] :3
09-15 12:03:01.794  3410  3576 D DisplayPowerController: getFinalBrightness : Summary is 1 -> 1
09-15 12:03:01.794  3410  3576 D DisplayPowerController: Animating brightness: target=1, rate=2000 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
,09-15 12:03:01.804  3410  4251 D PowerManagerService: [api] acquire WakeLock flags=0x80 tag=Window:AOD uid=1000 pid=3410
,09-15 12:03:01.824  4751  4751 D DefaultClockView: Start AOD Enter Animation
,09-15 12:03:01.824  3410  3981 D PowerManagerService: [api] acquire WakeLock flags=0x80 tag=Window:AOD uid=1000 pid=3410
,09-15 12:03:01.834  4150  4150 I PeopleStripeManager: isExistVisibleHandler false
09-15 12:03:01.834  4150  4150 I PeopleStripeManager: hideStripe
,09-15 12:03:01.854  3410  4424 D PowerManagerService: [api] acquire WakeLock flags=0x80 tag=Window:AOD uid=1000 pid=3410
,09-15 12:03:01.894  4023  4023 D Recents : onTaskStackChanged
,09-15 12:03:01.904  4023  4023 W ResourcesManager: getTopLevelResources: /data/app/com.test.thalitest-1/base.apk / 1.0 running in com.android.systemui rsrc of package com.test.thalitest
,09-15 12:03:01.914  4023  4023 D ResourcesManager: For user 0 new overlays fetched Null
,09-15 12:03:01.924  3410  3410 D PowerManagerService: [api] release WakeLock flags=0x80 tag=Window:com.test.thalitest/com.test.thalitest.MainActivity uid=1000 pid=3410 (0x0)
,09-15 12:03:01.974  3410  3586 D SurfaceControl: Excessive delay in setPowerMode(): 223ms
09-15 12:03:01.974  3410  3586 D PowerManagerUtil: Excessive delay in !@display_state: DOZE: 224ms
09-15 12:03:01.974  3009  3009 D libEGL  : eglTerminate EGLDisplay = 0x7ff285bf88
09-15 12:03:01.974  3410  3586 D PowerManagerUtil: Excessive delay in DisplayManagerInternal.requestDesiredDisplayState: 224ms
09-15 12:03:01.974  3410  3576 D DisplayPowerController: animateScreenStateChange[0]: target=3
09-15 12:03:01.974  3410  3576 I libsuspend: !@autosuspend_wakeup_count_enable
09-15 12:03:01.974  3410  3576 D DisplayPowerController: [Dual Screen Compatible] state[0] :3
09-15 12:03:01.974  3410  3576 I libsuspend: !@autosuspend_wakeup_count_enable done
09-15 12:03:01.974  3410  3576 D DisplayPowerController: getFinalBrightness : Summary is 1 -> 1
09-15 12:03:01.974  3410  3576 D DisplayPowerController: Animating brightness: target=1, rate=2000 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
09-15 12:03:01.974  3410  3576 D DisplayPowerController: animateScreenStateChange[0]: target=3
09-15 12:03:01.974  3410  3576 D DisplayPowerController: [Dual Screen Compatible] state[0] :3
09-15 12:03:01.974  3009  3009 D libEGL  : eglInitialize EGLDisplay = 0x7ff285be68
09-15 12:03:01.974  3410  3576 D DisplayPowerController: getFinalBrightness : Summary is 1 -> 1
09-15 12:03:01.974  3410  3576 D DisplayPowerController: Animating brightness: target=1, rate=2000 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
09-15 12:03:01.974  3410  3576 D PowerManagerService: [s] DisplayPowerCallbacks : onStateChanged()
09-15 12:03:01.974  3410  3576 D PowerManagerService: mDisplayReady: true
09-15 12:03:01.974  3410  3576 D PowerManagerService: [PWL] sb release: PowerManagerService.Display
,09-15 12:03:01.984  4751  4751 I AlpmModeManager: handleAlpmModeOn: state  = UNBLANK
,09-15 12:03:01.984  3410  4190 D PowerManagerService: [api] acquire WakeLock flags=0x80 tag=Window:AOD uid=1000 pid=3410
,09-15 12:03:01.994  3009  3009 D libEGL  : eglInitialize EGLDisplay = 0x7ff285be68
,09-15 12:03:01.994  3410  3474 D PowerManagerService: [api] acquire WakeLock flags=0x80 tag=Window:AOD uid=1000 pid=3410
,09-15 12:03:02.014  3410  4951 D PowerManagerService: [api] acquire WakeLock flags=0x80 tag=Window:AOD uid=1000 pid=3410
,09-15 12:03:02.044  4751  4751 D DefaultClockView: End AOD Enter Animation : ForceStopAnimation : false
09-15 12:03:02.054  4751  4751 D AODService: : state = Start AOD mode!!
,09-15 12:03:02.054  3410  4251 D PowerManagerService: [api] acquire WakeLock flags=0x80 tag=Window:AOD uid=1000 pid=3410
,09-15 12:03:02.084  4751  4751 D BatteryMeterView: onDraw batteryColor : -986896
,09-15 12:03:02.084  3410  3971 D PowerManagerService: [api] acquire WakeLock flags=0x80 tag=Window:AOD uid=1000 pid=3410
,09-15 12:03:02.234  3410  3410 D PowerManagerService: [api] release WakeLock flags=0x80 tag=Window:AOD uid=1000 pid=3410 (0x0)
,09-15 12:03:02.354  4751  4751 I AlpmModeManager: handleBlankDisplay: current state [ALPM_ON] to [ALPM_STATE_BLANK]
09-15 12:03:02.354  4751  4751 V AlpmModeManager: handleBlankDisplay: setDoze [DISPLAY_STATE_DOZE_SUSPEND] Keep bright
,09-15 12:03:02.354  3410  3473 I PowerManagerService: [api] setDozeOverrideFromAod AlpmHlpmSysfs = -1, screenState = 4, Brightness = 0, wakefulness = false
09-15 12:03:02.354  3410  3473 I libsuspend: !@autosuspend_wakeup_count_disable
09-15 12:03:02.354  3410  3473 D PowerManagerService: setDozeModeBySysfs:  value is -1 , we ignore it. 
09-15 12:03:02.354  3410  3473 I libsuspend: !@autosuspend_wakeup_count_disable done
09-15 12:03:02.354  3410  3473 D PowerManagerService: mDisplayReady: false
09-15 12:03:02.354  3410  3576 D DisplayPowerController: animateScreenStateChange[0]: target=4
09-15 12:03:02.354  3410  3473 D PowerManagerService: [PWL] sb acquire: PowerManagerService.Display
09-15 12:03:02.354  3009  3009 D SurfaceFlinger: Set power mode=3, type=0 flinger=0x7fb2003c00
09-15 12:03:02.354  3410  3576 D DisplayPowerController: [Dual Screen Compatible] state[0] :4
09-15 12:03:02.354  3009  3009 I hwcomposer: int exynos_setPowerMode(hwc_composer_device_1*, int, int):: disp(0), mode(3)
,09-15 12:03:02.354  3410  3576 D DisplayPowerController: getFinalBrightness : Summary is 1 -> 1
09-15 12:03:02.354  3410  3576 D DisplayPowerController: Animating brightness: target=1, rate=0 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
09-15 12:03:02.354  3410  3586 D DisplayManagerService: !@display_state: DOZE -> DOZE_SUSPEND brightness: 1 -> 1
,09-15 12:03:02.354  3410  3572 I DisplayManagerService: Display device changed state: "Wbudowany ekran", DOZE_SUSPEND
09-15 12:03:02.354  3410  3572 I DisplayManagerService: Display device changed state: "ActivityViewVirtualDisplay", DOZE_SUSPEND
,09-15 12:03:02.374  3410  3576 D DisplayPowerController: animateScreenStateChange[0]: target=4
09-15 12:03:02.374  3410  3576 D DisplayPowerController: [Dual Screen Compatible] state[0] :4
09-15 12:03:02.374  3410  3576 I libsuspend: !@autosuspend_wakeup_count_enable
09-15 12:03:02.374  3410  3576 D DisplayPowerController: getFinalBrightness : Summary is 1 -> 1
09-15 12:03:02.374  3410  3576 I libsuspend: !@autosuspend_wakeup_count_enable done
09-15 12:03:02.374  3410  3576 D DisplayPowerController: Animating brightness: target=1, rate=0 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
09-15 12:03:02.374  3410  3576 D DisplayPowerController: animateScreenStateChange[0]: target=4
09-15 12:03:02.374  3410  3576 D DisplayPowerController: [Dual Screen Compatible] state[0] :4
09-15 12:03:02.374  3410  3576 D DisplayPowerController: getFinalBrightness : Summary is 1 -> 1
09-15 12:03:02.374  3410  3576 D DisplayPowerController: Animating brightness: target=1, rate=0 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
09-15 12:03:02.374  3410  3576 D PowerManagerService: [s] DisplayPowerCallbacks : onStateChanged()
09-15 12:03:02.374  3410  3576 D PowerManagerService: mDisplayReady: true
09-15 12:03:02.374  3410  3576 D PowerManagerService: [PWL] sb release: PowerManagerService.Display
,09-15 12:03:02.394  6198  6198 E CocktailBarPositionManager: Window direction: 0
09-15 12:03:02.394  6198  6198 I CocktailBarPositionManager: updateAlphaScreenPosition position is dirty 0
,09-15 12:03:02.624  3410  6452 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 b.J.a:-1 b.J.a:-1 b.L.run:-1 android.os.Handler.handleCallback:739 
,09-15 12:03:02.634  3410  3541 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{e65564 u0 com.samsung.android.sm.lowpowercontext.START_ANALYSIS qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{280aae1 9470:com.samsung.android.sm.provider/1000}
,09-15 12:03:02.964  3410  3907 W System.err: remove failed: ENOENT (No such file or directory) : /data/system/recent_tasks/75_task.xml.bak
,09-15 12:03:05.514  3410  3817 V AlarmManager: Expired Alarm result :4
,09-15 12:03:05.514  3950  3950 D KeyguardViewMediator: received DELAYED_KEYGUARD_ACTION with seq = 2, mDelayedShowingSequence = 2
,09-15 12:03:05.524  3950  3950 D FactoryTest: checkAutomationTestOption() : option=0
,09-15 12:03:05.524  3950  3950 D FactoryTest: checkAutomationTestOption() : mode_screenlock=0
09-15 12:03:05.524  3950  3950 D KeyguardViewMediator: doKeyguard: showing the lock screen
09-15 12:03:05.524  3950  3950 D KeyguardViewMediator: showLocked
,09-15 12:03:05.524  3950  3950 D KeyguardViewMediator: handleShow
,09-15 12:03:05.524  3950  3950 E KeyguardViewMediator: setShowingLocked mShowing = true
,09-15 12:03:05.534  3950  3950 D StatusBar-Window: fnf=false sanc=true, kni=false, sbf=false
09-15 12:03:05.534  3950  3950 D CoverUI : applyFocusableFlag() : Remove SAMSUNG_FLAG_SVIEW_COVER
,09-15 12:03:05.534  3950  3950 D StatusBarWindowManager: forceCollapsed : false isKeyguardShowingAndNotOccluded() : true panelVisible : false keyguardFadingAway : false bouncerShowing : false headsUpShowing : false
09-15 12:03:05.534  3950  3950 D CoverUI : applyHeight h = -1, oc = true, fa = false, ac = false, sc = false
,09-15 12:03:05.534  3950  3950 D KeyguardEffectViewController: setKeyguardShowing = true
,09-15 12:03:05.534  3950  3950 D KeyguardEffectViewController: mShowing=true, mOccluded=false, mKeyguardFadingAway=false, match_parent=false
09-15 12:03:05.534  3950  3950 D StatusBarKeyguardViewManager: showBouncerOrKeyguard
,09-15 12:03:05.534  3950  3950 V KeyguardUpdateMonitor: *** register callback for com.android.keyguard.KeyguardHostView$1@f4b24ab
,09-15 12:03:05.534  3950  3950 V KeyguardUpdateMonitor: *** unregister callback for null
,09-15 12:03:05.534  3950  3950 D KeyguardSecurityPolicyUtils: MDM is not enabled...
09-15 12:03:05.534  3950  3950 V KeyguardUpdateMonitor: *** register callback for com.android.keyguard.KeyguardSecurityContainer$1@f6ce708
09-15 12:03:05.534  3950  3950 V KeyguardUpdateMonitor: *** unregister callback for null
09-15 12:03:05.544  3950  3950 D KeyguardSecurityModel: getSecurityMode( getActivePasswordQuality = 0 , currentuser = 0
09-15 12:03:05.544  3950  3950 V KeyguardSecurityView: showPrimarySecurityScreen(turningOff=false)
09-15 12:03:05.544  3950  3950 D KeyguardSecurityView: showSecurityScreen(None)
09-15 12:03:05.544  3950  3950 D StatusBar-Window: fnf=false sanc=true, kni=false, sbf=false
09-15 12:03:05.544  3950  3950 D CoverUI : applyFocusableFlag() : Remove SAMSUNG_FLAG_SVIEW_COVER
09-15 12:03:05.544  3950  3950 D StatusBarWindowManager: forceCollapsed : false isKeyguardShowingAndNotOccluded() : true panelVisible : false keyguardFadingAway : false bouncerShowing : false headsUpShowing : false
09-15 12:03:05.544  3950  3950 D CoverUI : applyHeight h = -1, oc = true, fa = false, ac = false, sc = false
,09-15 12:03:05.554  3950  3950 D KeyguardSecurityModel: getSecurityMode( getActivePasswordQuality = 0 , currentuser = 0
,09-15 12:03:05.554  3950  3950 D PhoneStatusBar: showKeyguard
09-15 12:03:05.554  3950  3950 D PhoneStatusBar: setBarState: state - 1
09-15 12:03:05.554  3950  3950 D StatusBar-Window: fnf=false sanc=true, kni=false, sbf=false
09-15 12:03:05.554  3950  3950 D CoverUI : applyFocusableFlag() : Remove SAMSUNG_FLAG_SVIEW_COVER
09-15 12:03:05.554  3950  3950 D StatusBarWindowManager: forceCollapsed : false isKeyguardShowingAndNotOccluded() : true panelVisible : false keyguardFadingAway : false bouncerShowing : false headsUpShowing : false
09-15 12:03:05.554  3950  3950 D CoverUI : applyHeight h = -1, oc = true, fa = false, ac = false, sc = false
09-15 12:03:05.554  3950  3950 I PhoneStatusBar: updateKeyguardState 0 to 1
,09-15 12:03:05.554  3950  3950 D PanelView: updateQsState
,09-15 12:03:05.554  3950  3950 D KeyguardSwipeHelper: reset()
09-15 12:03:05.554  3950  3950 D KeyguardUnlockEventHandler: reset()
09-15 12:03:05.554  3950  3950 D KeyguardSwipeHelper: resetChildViewVI()
,09-15 12:03:05.564  3950  3950 D StatusBar: LSSN:1
09-15 12:03:05.564  3950  3950 E LSO     : LSO Service is not yet ready!!!
,09-15 12:03:05.564  3950  3950 D PanelView: setKeyguardBottomAreaVisibility() prevState=0, newState - 1 goingToShade - false
,09-15 12:03:05.564  3950  3950 D PhoneStatusBar/KeyguardBottomAreaView: updateCameraVisibility isCameraDisabledByDpm=false
,09-15 12:03:05.564  3950  3950 V KeyguardBottomAreaShortcutView: updateLeftPreview
,09-15 12:03:05.564  3950  3950 V KeyguardBottomAreaShortcutView: updateRightPreview
09-15 12:03:05.564  3950  3950 D KeyguardCircleAffordanceView: setPreviewView: mRight=false,preview=android.widget.RelativeLayout{1e41740 I.E...... ......ID 0,0-1440,2560}
09-15 12:03:05.564  3950  4106 V KeyguardBottomAreaShortcutView: updateLeftPreview - mLeftAffordanceView
,09-15 12:03:05.584  3950  4106 V PreviewInflater: switching default dialer action
,09-15 12:03:05.604  3950  3950 D KeyguardCircleAffordanceView: setPreviewView: mRight=true,preview=android.widget.AbsoluteLayout{8b39679 I.E...... ......ID 0,0-1440,2560}
,09-15 12:03:05.624  3950  3950 D PanelView: updateQsState
,09-15 12:03:05.624  3950  3950 D NotificationStackScrollLayout:  scroll range should be extended : 884
,09-15 12:03:05.634  3950  3950 D KeyguardSecurityModel: getSecurityMode( getActivePasswordQuality = 0 , currentuser = 0
,09-15 12:03:05.634  3950  3950 D PhoneStatusBar: Make expanded visible: expanded visible=false
09-15 12:03:05.634  3950  3950 D StatusBar-Window: fnf=false sanc=true, kni=false, sbf=true
09-15 12:03:05.634  3950  3950 D PhoneStatusBar: adjustDisableFlags:false, false, true, false, false, 1
09-15 12:03:05.634  3950  3950 D CoverUI : applyFocusableFlag() : Remove SAMSUNG_FLAG_SVIEW_COVER
09-15 12:03:05.634  3950  3950 D StatusBarWindowManager: forceCollapsed : false isKeyguardShowingAndNotOccluded() : true panelVisible : true keyguardFadingAway : false bouncerShowing : false headsUpShowing : false
09-15 12:03:05.634  3950  3950 D CoverUI : applyHeight h = -1, oc = true, fa = false, ac = false, sc = false
,09-15 12:03:05.634  3950  3950 D PhoneStatusBar: disable: < expand ICONS* alerts SYSTEM_INFO* back home recent clock search quick_settings >
,09-15 12:03:05.644  6198  6198 I TrayVisibilityController: TrayStateVisibilityReceiver action :com.samsung.systemui.statusbar.ANIMATING
,09-15 12:03:05.644  3950  3950 D PhoneStatusBar: Make expanded visible: expanded visible=true
09-15 12:03:05.644  3950  3950 D StatusBar.BrightnessController: setListening  = true
,09-15 12:03:05.644  3950  3950 D KeyguardEffectViewLayered: reset()
09-15 12:03:05.644  3950  3950 D KeyguardEffectViewLayered: init()
09-15 12:03:05.644  3950  3950 D KeyguardEffectViewLayered: mViewWidth = 1440, mViewHeight = 96
09-15 12:03:05.644  3950  3950 D KeyguardEffectViewLayered: mBitmapImageList size = 3
09-15 12:03:05.644  3950  3950 D KeyguardEffectViewLayered: DENSITY = 1.0
,09-15 12:03:05.644  3950  3950 D PhoneStatusBar/KeyguardBottomAreaView: updateCameraVisibility isCameraDisabledByDpm=false
,09-15 12:03:05.644  3950  3950 D KeyguardViewBase: show()
,09-15 12:03:05.654  3950  3950 D KeyguardSecurityModel: getSecurityMode( getActivePasswordQuality = 0 , currentuser = 0
,09-15 12:03:05.654  3950  3950 V KeyguardSecurityView: showPrimarySecurityScreen(turningOff=false)
09-15 12:03:05.654  3950  3950 D KeyguardSecurityView: showSecurityScreen(None)
,09-15 12:03:05.654  3950  3950 D KeyguardUpdateMonitor: onKeyguardVisibilityChanged(true)
,09-15 12:03:05.654  3950  4106 V KeyguardBottomAreaShortcutView: updateRightPreview - mRightAffordanceView
09-15 12:03:05.654  3950  4106 D ShortcutManager: th = 1 is camera package
,09-15 12:03:05.664  3950  3950 V KeyguardFingerPrint: updateFingerprintListeningState(false)
,09-15 12:03:05.664  3950  3950 D KeyguardFingerPrint: shouldListenForFingerprint ( FingerPrint is not enabled. ) 
09-15 12:03:05.664  3950  3950 V KeyguardUpdateMonitor: stopListeningForFingerprint()
,09-15 12:03:05.664  3950  4106 V PreviewInflater: switching default camera action
,09-15 12:03:05.664  3950  3950 D KeyguardViewMediator: adjustStatusBarLocked: mShowing=true mOccluded=false isSecure=false --> flags=0x3200000
,09-15 12:03:05.664  3410  3979 D StatusBarManagerService: manageDisableList userId=0 what=0x3200000 pkg=com.android.systemui
,09-15 12:03:05.674  3410  3981 D PowerManagerService: [api] [s] userActivity : event: 0 flags: 0 (uid: 10065 pid: 3950) eventTime = 209831
,09-15 12:03:05.674  3950  3950 D KeyguardViewMediator: onSdpLocked :: Inside...
09-15 12:03:05.674  3950  3950 D KeyguardViewMediator: isPwdChangeRequested :: false
09-15 12:03:05.674  3950  3950 D KeyguardViewMediator: onSdpLocked :: Lock SDP for User 0
,09-15 12:03:05.674  3950  3950 V KeyguardDisplayManager: show (false)
,09-15 12:03:05.674  3410  4425 E SdpServiceKeeper: isLicensed {pid:3950 uid:10065 userid:0 doPkg:null}
09-15 12:03:05.674  3410  4425 E SdpServiceKeeper: System app. Skip license activation
,09-15 12:03:05.674  3410  4251 E SdpServiceKeeper: isLicensed {pid:3950 uid:10065 userid:0 doPkg:null}
,09-15 12:03:05.674  3410  4251 E SdpServiceKeeper: System app. Skip license activation
,09-15 12:03:05.674  3410  3474 D SdpManagerService: lockInternal 0
09-15 12:03:05.674  3410  3474 E SDP.CRYPTO:     On Locked OK, id 0
09-15 12:03:05.674  3410  3474 D SdpManagerService: clearCachedMasterKey (CMK) 0
09-15 12:03:05.674  3410  3474 E SdpManagerService: sendBroadcastAsUser(INTENT_SDP_STATE_CHANGED, state:1)
,09-15 12:03:05.674  3950 10045 D KeyguardViewMediator: lockSdp :: Lock SDP Successful...!
,09-15 12:03:05.684  3410  3541 V BroadcastQueue: [foreground] Process cur broadcast BroadcastRecord{71d26ce u0 com.sec.sdp.SDP_STATE_CHANGED qIdx=2}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{61e3689 9763:com.sec.android.app.sbrowser/u0a141}
,09-15 12:03:05.684  3410  4190 E SdpServiceKeeper: isLicensed {pid:9763 uid:10141 userid:0 doPkg:null}
09-15 12:03:05.684  3410  4190 E SdpServiceKeeper: White listed. Skip license activation
,09-15 12:03:05.684  9763  9763 E SdpStateChangedReceiver: com.sec.enterprise.knox.sdp.exception.SdpEngineNotExistsException
,09-15 12:03:05.704  3009  3070 D libEGL  : eglTerminate EGLDisplay = 0x7fab73ee78
09-15 12:03:05.704  3009  3070 D libEGL  : eglTerminate EGLDisplay = 0x7fab73ee78
,09-15 12:03:05.704  3950  4129 D mali_winsys: EGLint new_window_surface(egl_winsys_display*, void*, EGLSurface, EGLConfig, egl_winsys_surface**, egl_color_buffer_format*, EGLBoolean) returns 0x3000,  [1440x2560]-format:1
,09-15 12:03:05.704  3950  3950 D KeyguardEffectViewController: onLayoutChange() v: com.android.keyguard.effect.EffectBehindView{9e50b28 I.E...... ......ID 0,0-1440,2560 #7f0e0330 app:id/keyguard_effect_behind}, bottom : 2560, oldBottom : 96
09-15 12:03:05.704  3950  3950 D KeyguardEffectViewController: mShowing=true, mOccluded=false, mKeyguardFadingAway=false, match_parent=true
,09-15 12:03:05.704  3950  3950 D NotificationStackScrollLayout:  scroll range should be extended : 884
,09-15 12:03:05.704  3950  3950 D StatusBar-Window: fnf=false sanc=true, kni=false, sbf=true
09-15 12:03:05.704  3950  3950 D CoverUI : applyFocusableFlag() : Remove SAMSUNG_FLAG_SVIEW_COVER
09-15 12:03:05.714  3950  3950 D StatusBarWindowManager: forceCollapsed : false isKeyguardShowingAndNotOccluded() : true panelVisible : true keyguardFadingAway : false bouncerShowing : false headsUpShowing : false
09-15 12:03:05.714  3950  3950 D CoverUI : applyHeight h = -1, oc = true, fa = false, ac = false, sc = false
,09-15 12:03:05.834  3410  4190 V WindowStateAnimator: Finishing drawing window Window{ff92b92 u0 d0 StatusBar}: mDrawState=DRAW_PENDING
,09-15 12:03:05.834  3950  3950 D KeyguardUpdateMonitor: handleKeyguardReset
09-15 12:03:05.834  3950  3950 V KeyguardFingerPrint: updateFingerprintListeningState(false)
,09-15 12:03:05.834  3950  3950 D KeyguardFingerPrint: shouldListenForFingerprint ( FingerPrint is not enabled. ) 
,09-15 12:03:05.834  3950  3950 V KeyguardUpdateMonitor: stopListeningForFingerprint()
09-15 12:03:05.844  9956 10025 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
09-15 12:03:05.844  9956 10025 I jxcore-log: 
,09-15 12:03:05.844  3009  3009 D libEGL  : eglInitialize EGLDisplay = 0x7ff285be68
,09-15 12:03:05.844  3009  3009 D libEGL  : eglTerminate EGLDisplay = 0x7ff285bef8
,09-15 12:03:05.844  9956 10025 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
09-15 12:03:05.844  9956 10025 I jxcore-log: 
,09-15 12:03:05.844  3950  3950 D KeyguardCircleAffordanceView: setPreviewView: mRight=false,preview=android.widget.RelativeLayout{d91a8c6 I.E...... ......ID 0,0-0,0}
09-15 12:03:05.844  3950  3950 V KeyguardBottomAreaShortcutView: mLeftAffordanceView preview = android.widget.RelativeLayout{d91a8c6 I.E...... ......ID 0,0-0,0}
09-15 12:03:05.844  3950  3950 D PhoneStatusBar: adjustDisableFlags:false, false, true, false, false, 1
,09-15 12:03:05.854  3950  3950 D PhoneStatusBar: disable: < expand ICONS alerts SYSTEM_INFO back HOME* RECENT* clock SEARCH* quick_settings >
,09-15 12:03:05.854  3950  3950 D ViewRootImpl: MSG_RESIZED_REPORT: ci=Rect(0, 0 - 0, 0) vi=Rect(0, 0 - 0, 0) or=1
,09-15 12:03:05.854  9956 10025 D BluetoothAdapter: STATE_ON
09-15 12:03:05.854  3950  3950 D KeyguardCircleAffordanceView: setPreviewView: mRight=true,preview=android.widget.AbsoluteLayout{7956087 I.E...... ......ID 0,0-0,0}
09-15 12:03:05.854  3950  3950 V KeyguardBottomAreaShortcutView: mRightAffordanceView preview = android.widget.AbsoluteLayout{7956087 I.E...... ......ID 0,0-0,0}
,09-15 12:03:05.854  9956 10025 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-15 12:03:05.854  9956 10025 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-15 12:03:05.854  9956 10025 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-15 12:03:05.854  9956 10025 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-15 12:03:05.854  9956 10025 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-15 12:03:05.854  9956 10025 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-15 12:03:05.854  9956 10025 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-15 12:03:05.854  9956 10025 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-15 12:03:05.854  9956 10025 D BluetoothAdapter: STATE_ON
,09-15 12:03:05.864  9956 10025 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-15 12:03:05.864  9956 10025 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
09-15 12:03:05.864  9956 10025 I jxcore-log: 
,09-15 12:03:05.864  9956 10025 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
09-15 12:03:05.864  9956 10025 I jxcore-log: 
,09-15 12:03:05.884  3950  3950 D KeyguardEffectViewController: onLayoutChange() v: com.android.keyguard.effect.EffectBehindView{9e50b28 V.E...... ......I. 0,0-1440,2560 #7f0e0330 app:id/keyguard_effect_behind}, bottom : 2560, oldBottom : 2560
,09-15 12:03:05.914  3410  4952 V WindowStateAnimator: Finishing drawing window Window{ff92b92 u0 d0 StatusBar}: mDrawState=READY_TO_SHOW
,09-15 12:03:05.914  3950  3950 D Recents : handleProxyCall type=3
,09-15 12:03:05.914  4023  4023 D Recents : handleProxyCall type=3
,09-15 12:03:05.924  3009  3009 D libEGL  : eglInitialize EGLDisplay = 0x7ff285be68
,09-15 12:03:05.944  3009  3009 D libEGL  : eglInitialize EGLDisplay = 0x7ff285be68
,09-15 12:03:06.064  3410  6444 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
,09-15 12:03:06.104  9956 10025 D executeNativeTests: Running unit tests
,09-15 12:03:06.114  9956 10025 D com.test.thalitest.ThaliTestRunner: Total number of executed tests: 1
,09-15 12:03:06.114  9956 10025 D com.test.thalitest.ThaliTestRunner: Number of passed tests: 1
09-15 12:03:06.114  9956 10025 D com.test.thalitest.ThaliTestRunner: Number of failed tests:  0
09-15 12:03:06.114  9956 10025 D com.test.thalitest.ThaliTestRunner: Number of ignored tests: 0
09-15 12:03:06.114  9956 10025 D com.test.thalitest.ThaliTestRunner: Total duration: 1 ms
09-15 12:03:06.114  9956 10025 I jxcore-log: *Native tests were executed*
09-15 12:03:06.114  9956 10025 I jxcore-log: 
,09-15 12:03:06.114  9956 10025 I jxcore-log: Total number of executed tests:  1
09-15 12:03:06.114  9956 10025 I jxcore-log: 
09-15 12:03:06.114  9956 10025 I jxcore-log: Number of passed tests:  1
09-15 12:03:06.114  9956 10025 I jxcore-log: 
09-15 12:03:06.114  9956 10025 I jxcore-log: Number of failed tests:  0
09-15 12:03:06.114  9956 10025 I jxcore-log: 
09-15 12:03:06.114  9956 10025 I jxcore-log: Number of ignored tests:  0
09-15 12:03:06.114  9956 10025 I jxcore-log: 
,09-15 12:03:06.114  9956 10025 I jxcore-log: Total duration:  1
09-15 12:03:06.114  9956 10025 I jxcore-log: 
09-15 12:03:06.114  9956 10025 I jxcore-log: ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
09-15 12:03:06.114  9956 10025 I jxcore-log: 
09-15 12:03:06.114  9956 10025 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-15 12:03:06.114  9956 10025 I jxcore-log: 
,09-15 12:03:06.134  9956  9956 I chromium: [INFO:CONSOLE(68)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (68)
,09-15 12:03:06.574 10047 10047 I FIPS_bssl: FIPS approved mode (1) | 10047 | app_process
,09-15 12:03:06.584 10047 10047 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
,09-15 12:03:06.584 10047 10047 D AndroidRuntime: CheckJNI is OFF
09-15 12:03:06.584 10047 10047 D AndroidRuntime: readGMSProperty: start
09-15 12:03:06.584 10047 10047 D AndroidRuntime: readGMSProperty: already setted!!
09-15 12:03:06.584 10047 10047 D AndroidRuntime: propertySet: couldn't set property (it is from app)
09-15 12:03:06.584 10047 10047 D AndroidRuntime: readGMSProperty: could not set the property(default)!!
09-15 12:03:06.584 10047 10047 D AndroidRuntime: readGMSProperty: end
09-15 12:03:06.584 10047 10047 D AndroidRuntime: addProductProperty: start
,09-15 12:03:06.604 10047 10047 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
,09-15 12:03:06.624 10047 10047 I Radio-JNI: register_android_hardware_Radio DONE
,09-15 12:03:06.624 10047 10047 E AffinityControl: AffinityControl: registerfunction enter
,09-15 12:03:06.634 10047 10047 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
,09-15 12:03:06.644  3410  4714 D PackageManager: START PACKAGE DELETE: observer{177240559}
09-15 12:03:06.644  3410  4714 D PackageManager: pkg{<packageName>}
09-15 12:03:06.644  3410  4714 D PackageManager: user{0}
09-15 12:03:06.644  3410  4714 D PackageManager: caller{2000}
09-15 12:03:06.644  3410  4714 D PackageManager: flags{2}
,09-15 12:03:06.644  3410  4714 D PersonaManagerService: isFromApprovedUnInstaller: uid, userId, appid : 2000 0 2000
09-15 12:03:06.644  3410  4714 D PersonaManagerService: isFromApprovedUnInstaller: isApproved : true
09-15 12:03:06.644  3410  4714 D PersonaManagerService: isFromApprovedUnInstaller: isApproved before exit: true
09-15 12:03:06.644  3410  4714 D PackageManager: deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag2
,09-15 12:03:06.644  3410  4714 D PackageManager: deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag2
09-15 12:03:06.644  3410  3594 D PackageManager: [MSG] DELETE_PACKAGE_AS_USER
09-15 12:03:06.644  3410  3594 D PackageManagerService: deletePackage- pkg:com.test.thalitest, edmuserId:0
,09-15 12:03:06.644  3410  3594 D PackageManagerService: deletePackage- pkg:com.test.thalitest, edmuserId:-1
09-15 12:03:06.644  3410  3594 D ApplicationPolicy: getApplicationUninstallationEnabled
09-15 12:03:06.644  3410  3594 D ApplicationPolicy: getApplicationUninstallationEnabled :  enabled true
09-15 12:03:06.644  3410  3594 I PackageManager: !@  calling am.removeDeletedPkgsFromLru from PMS
,09-15 12:03:06.644  3410  3594 D ActivityManager: removeDeletedPkgsFromLruStats called in AMS...com.test.thalitest
,09-15 12:03:06.644  3410  3594 D PackageManager: !@killApplicatoin: 10177, uninstall pkg
,09-15 12:03:06.644  3410  3594 I PackageManager: !@  calling am.removeDeletedPkgsFromLru from PMS
09-15 12:03:06.644  3410  3594 D ActivityManager: removeDeletedPkgsFromLruStats called in AMS...com.test.thalitest
,09-15 12:03:06.644  3410  3541 I ActivityManager: Force stopping com.test.thalitest appid=10177 user=-1: uninstall pkg
09-15 12:03:06.644  3410  3541 I ActivityManager: Killing 9956:com.test.thalitest/u0a177 (adj 0): stop com.test.thalitest cause uninstall pkg
,09-15 12:03:06.654  3410  3541 D ActivityManager: isAutoRunBlockedApp:: com.test.thalitest, Auto Run ON
,09-15 12:03:06.664  3410  3541 D ActivityManager: mDVFSHelper.acquire()
,09-15 12:03:06.674  3410  3594 D AASAinstall: there is not AASApackages.xml file
,09-15 12:03:06.674 10056 10056 E Zygote  : v2
09-15 12:03:06.674 10056 10056 I libpersona: KNOX_SDCARD checking this for 10177
09-15 12:03:06.674 10056 10056 I libpersona: KNOX_SDCARD not a persona
09-15 12:03:06.684 10056 10056 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0013
,09-15 12:03:06.684 10056 10056 E Zygote  : accessInfo : 0
09-15 12:03:06.684 10056 10056 W SELinux : SELinux: seapp_context_lookup: seinfo=default, level=s0:c512,c768, pkgname=com.test.thalitest 
,09-15 12:03:06.684  3410  3541 I ActivityManager: Start proc 10056:com.test.thalitest/u0a177 for activity com.test.thalitest/.MainActivity
,09-15 12:03:06.694  3410  3541 W VirtualScreenManagerService: moveTaskBackToDisplayIfNeeded(): top activity or app is null
09-15 12:03:06.694  3410  3541 I ActivityManager:   Force finishing activity ActivityRecord{bc890b0 u0 com.test.thalitest/.MainActivity t75}
,09-15 12:03:06.704 10056 10056 D TimaKeyStoreProvider: TimaSignature is unavailable
09-15 12:03:06.704 10056 10056 D ActivityThread: Added TimaKeyStore provider
,09-15 12:03:06.714  3009  4362 I SurfaceFlinger: id=23 Removed NainActivit (5/10)
,09-15 12:03:06.714  3009  3017 I SurfaceFlinger: id=23 Removed NainActivit (-2/10)
,09-15 12:03:06.714  3410  3541 D InputDispatcher: Focused application released
,09-15 12:03:06.714  3410  3541 D FocusedStackFrame: Set to : 0
09-15 12:03:06.714  3410  3541 W VirtualScreenManagerService: failed to move task null
,09-15 12:03:06.724  3009  3009 D libEGL  : eglTerminate EGLDisplay = 0x7ff285bf58
09-15 12:03:06.724  3009  3009 D libEGL  : eglTerminate EGLDisplay = 0x7ff285bf58
09-15 12:03:06.724  3009  3009 D libEGL  : eglTerminate EGLDisplay = 0x7ff285bf58
,09-15 12:03:06.794  3410  4248 D GraphicsStats: Buffer count: 7
09-15 12:03:06.794  3410  3979 D ConnectivityService: ConnectivityService NetworkRequestInfo binderDied(NetworkRequest [ id=7, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ], android.os.BinderProxy@847b7e7)
,09-15 12:03:06.794  3410  3868 D ConnectivityService: releasing NetworkRequest NetworkRequest [ id=7, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-15 12:03:06.794  3410  3868 D ConnectivityService: sending notification RELEASED for NetworkRequest [ id=7, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,09-15 12:03:06.794  3410  3868 E ConnectivityService: RemoteException caught trying to send a callback msg for NetworkRequest [ id=7, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,09-15 12:03:06.904  3410  3594 W System.err: remove failed: ENOENT (No such file or directory) : /data/system/packages.xml.bak
,09-15 12:03:06.984  3410  3594 W System.err: remove failed: ENOENT (No such file or directory) : /data/system/users/0/package-restrictions.xml.bak
09-15 12:03:06.984  3410  3572 W System.err: android.content.pm.PackageManager$NameNotFoundException: com.test.thalitest
,09-15 12:03:06.984  3410  3572 W System.err: 	at android.app.ApplicationPackageManager.getApplicationInfo(ApplicationPackageManager.java:366)
09-15 12:03:06.984  3410  3572 W System.err: 	at com.android.internal.policy.PhoneWindow.installDecor(PhoneWindow.java:4813)
,09-15 12:03:06.984  3410  3572 W System.err: 	at com.android.internal.policy.PhoneWindow.getDecorView(PhoneWindow.java:2263)
09-15 12:03:06.984  3410  3572 W System.err: 	at com.android.server.policy.PhoneWindowManager.addStartingWindow(PhoneWindowManager.java:4338)
09-15 12:03:06.984  3410  3572 W System.err: 	at com.android.server.wm.WindowManagerService$H.handleMessage(WindowManagerService.java:13481)
09-15 12:03:06.984  3410  3572 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-15 12:03:06.984  3410  3572 W System.err: 	at android.os.Looper.loop(Looper.java:158)
,09-15 12:03:06.984  3410  3572 D SecWifiDisplayUtil: Metadata value : SecSettings2
09-15 12:03:06.984  3410  3572 W System.err: 	at android.os.HandlerThread.run(HandlerThread.java:61)
09-15 12:03:06.984  3410  3572 W System.err: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
09-15 12:03:06.984  3167  3167 W keystore: ENTER clear_uid from uid 1000 for 10177
,09-15 12:03:06.984  3410  3572 D ViewRootImpl: #1 mView = com.android.internal.policy.PhoneWindow$DecorView{43bdf94 V.E...... R.....ID 0,0-0,0}
,09-15 12:03:06.984  3410  3594 I art     : Starting a blocking GC Explicit
,09-15 12:03:06.994  3410  3572 W WindowManager: Failed looking up window
09-15 12:03:06.994  3410  3572 W WindowManager: java.lang.IllegalArgumentException: Requested window android.view.ViewRootImpl$W@c157a3d does not exist
09-15 12:03:06.994  3410  3572 W WindowManager: 	at com.android.server.wm.WindowManagerService.windowForClientLocked(WindowManagerService.java:14804)
09-15 12:03:06.994  3410  3572 W WindowManager: 	at com.android.server.wm.WindowManagerService.pokeDrawLock(WindowManagerService.java:5176)
09-15 12:03:06.994  3410  3572 W WindowManager: 	at com.android.server.wm.Session.pokeDrawLock(Session.java:505)
09-15 12:03:06.994  3410  3572 W WindowManager: 	at android.view.ViewRootImpl.pokeDrawLockIfNeeded(ViewRootImpl.java:1203)
09-15 12:03:06.994  3410  3572 W WindowManager: 	at android.view.ViewRootImpl.scheduleTraversals(ViewRootImpl.java:1415)
09-15 12:03:06.994  3410  3572 W WindowManager: 	at android.view.ViewRootImpl.requestLayout(ViewRootImpl.java:1222)
09-15 12:03:06.994  3410  3572 W WindowManager: 	at android.view.ViewRootImpl.setView(ViewRootImpl.java:800)
09-15 12:03:06.994  3410  3572 W WindowManager: 	at android.view.WindowManagerGlobal.addView(WindowManagerGlobal.java:337)
09-15 12:03:06.994  3410  3572 W WindowManager: 	at android.view.WindowManagerImpl.addView(WindowManagerImpl.java:91)
09-15 12:03:06.994  3410  3572 W WindowManager: 	at com.android.server.policy.PhoneWindowManager.addStartingWindow(PhoneWindowManager.java:4378)
09-15 12:03:06.994  3410  3572 W WindowManager: 	at com.android.server.wm.WindowManagerService$H.handleMessage(WindowManagerService.java:13481)
09-15 12:03:06.994  3410  3572 W WindowManager: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-15 12:03:06.994  3410  3572 W WindowManager: 	at android.os.Looper.loop(Looper.java:158)
09-15 12:03:06.994  3410  3572 W WindowManager: 	at android.os.HandlerThread.run(HandlerThread.java:61)
09-15 12:03:06.994  3410  3572 W WindowManager: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
,09-15 12:03:06.994  3410  3572 D ViewRootImpl: #3 mView = null
09-15 12:03:06.994  3410  3572 W WindowManager: Attempted to add application window with unknown token Token{89b6b29 ActivityRecord{bc890b0 u0 com.test.thalitest/.MainActivity t75 f}}.  Aborting.
,09-15 12:03:07.004  3410  3572 W WindowManager: Token{89b6b29 ActivityRecord{bc890b0 u0 com.test.thalitest/.MainActivity t75 f}} already running, starting window not displayed. Unable to add window -- token Token{89b6b29 ActivityRecord{bc890b0 u0 com.test.thalitest/.MainActivity t75 f}} is not valid; is your activity running?
,09-15 12:03:07.004  3410  3572 W WindowManager: view not successfully added to wm, removing view
,09-15 12:03:07.004  3410  3572 W WindowManager: Exception when adding starting window
09-15 12:03:07.004  3410  3572 W WindowManager: java.lang.IllegalArgumentException: View=com.android.internal.policy.PhoneWindow$DecorView{43bdf94 V.E...... R.....ID 0,0-0,0} not attached to window manager
09-15 12:03:07.004  3410  3572 W WindowManager: 	at android.view.WindowManagerGlobal.findViewLocked(WindowManagerGlobal.java:451)
09-15 12:03:07.004  3410  3572 W WindowManager: 	at android.view.WindowManagerGlobal.removeView(WindowManagerGlobal.java:377)
09-15 12:03:07.004  3410  3572 W WindowManager: 	at android.view.WindowManagerImpl.removeViewImmediate(WindowManagerImpl.java:122)
09-15 12:03:07.004  3410  3572 W WindowManager: 	at com.android.server.policy.PhoneWindowManager.addStartingWindow(PhoneWindowManager.java:4395)
09-15 12:03:07.004  3410  3572 W WindowManager: 	at com.android.server.wm.WindowManagerService$H.handleMessage(WindowManagerService.java:13481)
09-15 12:03:07.004  3410  3572 W WindowManager: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-15 12:03:07.004  3410  3572 W WindowManager: 	at android.os.Looper.loop(Looper.java:158)
09-15 12:03:07.004  3410  3572 W WindowManager: 	at android.os.HandlerThread.run(HandlerThread.java:61)
09-15 12:03:07.004  3410  3572 W WindowManager: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
,09-15 12:03:07.014  3410  3410 D GameManagerService: NotifyRunnable. pkg: com.sec.android.app.launcher, type: 4, isMinimized: false, isTunableApp: false
,09-15 12:03:07.014  4300  4300 D Launcher: onRestart, Launcher: 198492302
,09-15 12:03:07.014  4300  4300 W ResourcesManager: getTopLevelResources: /system/app/ClockPackage_M/ClockPackage_M.apk / 1.0 running in com.sec.android.app.launcher rsrc of package com.sec.android.app.clockpackage
,09-15 12:03:07.024  4300  4300 D ResourcesManager: For user 0 new overlays fetched Null
,09-15 12:03:07.034  3410  3541 V MARsPolicyManager: updatePackagesScore PackageInfo name -- com.sec.android.app.launcher
,09-15 12:03:07.034  4300  4300 D ApplicationPackageManager: we has com.sec.android.app.clockpackage class. reuse it 
,09-15 12:03:07.034  3410  4952 I ActivityManager: Killing 8752:com.google.android.talk/u0a117 (adj 15): DHA:empty #33
,09-15 12:03:07.034  4300  4300 W ResourcesManager: getTopLevelResources: /system/app/ClockPackage_M/ClockPackage_M.apk / 1.0 running in com.sec.android.app.launcher rsrc of package com.sec.android.app.clockpackage
,09-15 12:03:07.054  3410  6444 D GameManagerService: identifyGamePackage. com.sec.android.app.launcher
,09-15 12:03:07.074  6198  6198 E CocktailBarPositionManager: Window direction: 0
09-15 12:03:07.074  6198  6198 I CocktailBarPositionManager: updateAlphaScreenPosition position is dirty 0
,09-15 12:03:07.084  3410  4714 D ActivityManager: isAutoRunBlockedApp:: com.google.android.talk, Auto Run ON
,09-15 12:03:07.084  3009  3070 I SurfaceFlinger: Modify Choreographer's phase offset to 6666666
,09-15 12:03:07.084  3009  3019 I SurfaceFlinger: Modify SurfaceFlinger's phase offset to 6666666
,09-15 12:03:07.094  4300  4300 W ResourcesManager: getTopLevelResources: /system/app/SPlanner_M/SPlanner_M.apk / 1.0 running in com.sec.android.app.launcher rsrc of package com.android.calendar
,09-15 12:03:07.094 10056 10056 D ContextRelationManager: ContextRelationManager() : FEATURE_ENABLED=true
,09-15 12:03:07.094 10056 10056 D RelationGraph: garbageCollect()
09-15 12:03:07.094  4300  4300 D ResourcesManager: For user 0 new overlays fetched Null
,09-15 12:03:07.094 10056 10056 W ResourcesManager: getTopLevelResources: /data/app/com.test.thalitest-1/base.apk / 1.0 running in com.test.thalitest rsrc of package com.test.thalitest
,09-15 12:03:07.094  3410  6444 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
,09-15 12:03:07.094  3410  4424 I InjectionManagerService -AppFeature: getCoreFeaturePkgList :[]
,09-15 12:03:07.104  4300  4300 D ApplicationPackageManager: we has com.android.calendar class. reuse it 
,09-15 12:03:07.104 10056 10056 I InjectionManager: Inside getClassLibPath + mLibMap{0=, 1=}
09-15 12:03:07.104  4300  4300 W ResourcesManager: getTopLevelResources: /system/app/SPlanner_M/SPlanner_M.apk / 1.0 running in com.sec.android.app.launcher rsrc of package com.android.calendar
,09-15 12:03:07.104  3410  6444 D GameManagerService: identifyGamePackage. com.sec.android.app.launcher
,09-15 12:03:07.104  4300  4300 D Minikin : FontFamily bestFont == NULL, so return vacant FakedFont
,09-15 12:03:07.104  4300  4300 D Minikin : FontFamily bestFont == NULL, so return vacant FakedFont
09-15 12:03:07.104  4300  4300 D Minikin : FontFamily bestFont == NULL, so return vacant FakedFont
,09-15 12:03:07.104  3410  6444 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
,09-15 12:03:07.114  4300  4300 D Launcher: onStart, Launcher: 198492302
,09-15 12:03:07.114  3410  6444 D GameManagerService: identifyGamePackage. com.sec.android.app.launcher
09-15 12:03:07.114  4300  4300 D Launcher.HomeView: onStart
09-15 12:03:07.114  3410  6444 D GameManagerService: identifyGamePackage. com.sec.android.app.launcher
09-15 12:03:07.114  4300  4300 D Launcher: onResume, Launcher: 198492302
09-15 12:03:07.114  3410  4190 D SettingsProvider: isChangeAllowed() : name = kids_home_mode
,09-15 12:03:07.114  3410  4190 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
09-15 12:03:07.114  3410  4190 D SecContentProvider: query(), uri = 17 selection = isSettingsChangesAllowed
09-15 12:03:07.114  3410  4190 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
09-15 12:03:07.114  3410  4190 D SettingsProvider: selectionArgs: false
09-15 12:03:07.114  3410  4190 D SettingsProvider: selectionArgs: 10069
,09-15 12:03:07.114 10056 10056 W ContextImpl: Unable to create files subdir /data/user/0/com.test.thalitest/cache
,09-15 12:03:07.114 10056 10056 V ActivityThread: Unable to initialize "java.io.tmpdir" property due to missing cache directory
09-15 12:03:07.114  3410  4190 D SettingsProvider: ret = -1
09-15 12:03:07.114 10056 10056 W ContextImpl: Unable to create files subdir /data/user/0/com.test.thalitest/code_cache
09-15 12:03:07.114 10056 10056 E ActivityThread: Unable to setupGraphicsSupport due to missing code-cache directory
09-15 12:03:07.114  4300  4300 D Launcher.HomeView: onResume
,09-15 12:03:07.114 10056 10056 I InjectionManager: Inside getClassLibPath caller 
,09-15 12:03:07.114  4300  4300 D capture : ---------checkFileExist land
09-15 12:03:07.114  4300  4300 D capture : currentOrientation: 1 mMainHomeScreenshot: false mMainHomeScreenshotLand: true
,09-15 12:03:07.124  3410  3541 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{891d232 u0 com.android.launcher.action.HOME_MODE_CHANGE qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{1da5c03 9906:com.sec.android.app.clockpackage/u0a93}
,09-15 12:03:07.124  4300  4300 D MenuAppsGridFragment: onResume
09-15 12:03:07.124  4300  4300 D MenuAppsGridFragment: changeState: (new)NORMAL(old)NORMAL(force)false
,09-15 12:03:07.124  4300  4300 D Launcher.MenuAppsGrid: updateGridSize:GRID_4x4 cellWidth:348  cellHeight:432
,09-15 12:03:07.134 10056 10056 D AndroidRuntime: Shutting down VM
,09-15 12:03:07.134 10056 10056 E AndroidRuntime: FATAL EXCEPTION: main
09-15 12:03:07.134 10056 10056 E AndroidRuntime: Process: com.test.thalitest, PID: 10056
09-15 12:03:07.134 10056 10056 E AndroidRuntime: java.lang.RuntimeException: Unable to instantiate application android.app.Application: java.lang.IllegalStateException: Unable to get package info for com.test.thalitest; is package not installed?
09-15 12:03:07.134 10056 10056 E AndroidRuntime: 	at android.app.LoadedApk.makeApplication(LoadedApk.java:676)
09-15 12:03:07.134 10056 10056 E AndroidRuntime: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:6294)
09-15 12:03:07.134 10056 10056 E AndroidRuntime: 	at android.app.ActivityThread.access$1800(ActivityThread.java:222)
09-15 12:03:07.134 10056 10056 E AndroidRuntime: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1861)
09-15 12:03:07.134 10056 10056 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-15 12:03:07.134 10056 10056 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:158)
09-15 12:03:07.134 10056 10056 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:7229)
09-15 12:03:07.134 10056 10056 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
09-15 12:03:07.134 10056 10056 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1230)
09-15 12:03:07.134 10056 10056 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1120)
09-15 12:03:07.134 10056 10056 E AndroidRuntime: Caused by: java.lang.IllegalStateException: Unable to get package info for com.test.thalitest; is package not installed?
09-15 12:03:07.134 10056 10056 E AndroidRuntime: 	at android.app.LoadedApk.initializeJavaContextClassLoader(LoadedApk.java:485)
09-15 12:03:07.134 10056 10056 E AndroidRuntime: 	at android.app.LoadedApk.makeApplication(LoadedApk.java:661)
09-15 12:03:07.134 10056 10056 E AndroidRuntime: 	... 9 more
,09-15 12:03:07.154  3410  3981 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{891d232 u0 com.android.launcher.action.HOME_MODE_CHANGE qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{1da5c03 9906:com.sec.android.app.clockpackage/u0a93}
,09-15 12:03:07.164  3410  3979 D ActivityManager: post active user change for 0 fullscreen true isFloatingActivity() false isHomeActivity() true
09-15 12:03:07.164  3410  3979 I WallpaperManagerService: switchPersonaWallpaper is called for personaId-0
09-15 12:03:07.164  3410  3979 D KnoxTimeoutHandler: post home show event for user 0
09-15 12:03:07.164  3410  3410 D WallpaperManagerService:  force update = false; persona id = 0; current user =0; current persona = 0
09-15 12:03:07.164  3410  3979 D KnoxTimeoutHandler: postActiveUserChange [MsgParam] userId: 0 fullscreen is true showWhenlocked is false
09-15 12:03:07.164  3410  3410 D KnoxTimeoutHandler: handleHomeShow for 0 and current 0
09-15 12:03:07.164  3410  3410 D KnoxTimeoutHandler: handleActiveUserChange [MsgParam] userId: 0 fullscreen is true showWhenlocked is false
,09-15 12:03:07.164 10056 10056 I Process : Sending signal. PID: 10056 SIG: 9
,09-15 12:03:07.164  3410  3594 I art     : Explicit concurrent mark sweep GC freed 146706(7MB) AllocSpace objects, 21(680KB) LOS objects, 31% free, 34MB/50MB, paused 3.370ms total 175.673ms
,09-15 12:03:07.174  3410  3410 I KnoxTimeoutHandler: Shared devices show user statefalse
,09-15 12:03:07.174  3009  3009 I SurfaceFlinger: id=25 createSurf (1440x2560),1 flag=4, MauncherAct
,09-15 12:03:07.184  4300  4643 D mali_winsys: EGLint new_window_surface(egl_winsys_display*, void*, EGLSurface, EGLConfig, egl_winsys_surface**, egl_color_buffer_format*, EGLBoolean) returns 0x3000,  [1440x2560]-format:1
,09-15 12:03:07.184  3410  3981 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{891d232 u0 com.android.launcher.action.HOME_MODE_CHANGE qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{1da5c03 9906:com.sec.android.app.clockpackage/u0a93}
,09-15 12:03:07.184  3410  3594 W PackageManager: Couldn't remove dex file for package:  at location /data/app/com.test.thalitest-1/base.apk, retcode=-1
09-15 12:03:07.184  3410  3594 D AASAuninstall: userId = 0, info.removedAppID = 10177, info.uid = 10177, packageName = com.test.thalitest
,09-15 12:03:07.184  3410  3594 D AASAinstall: there is not AASApackages.xml file
09-15 12:03:07.194  3410  3594 D PackageManager: result of delete: 1{177240559}
,09-15 12:03:07.194  3410  4714 I ActivityManager: Process com.test.thalitest (pid 10056)(adj 9) has died(246,1589)
,09-15 12:03:07.194  3410  4714 D ActivityManager: isAutoRunBlockedApp:: com.test.thalitest, Auto Run ON
,09-15 12:03:07.204  3410  4714 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.android.server.am.ActivityManagerService.updateOomAdjLocked:26743 com.android.server.am.ActivityManagerService.appDiedLocked:7562 com.android.server.am.ActivityManagerService$AppDeathRecipient.binderDied:1916 android.os.BinderProxy.sendDeathNotice:558 
,09-15 12:03:07.204 10047 10047 I art     : System.exit called, status: 0
09-15 12:03:07.204 10047 10047 I AndroidRuntime: VM exiting with result code 0.
09-15 12:03:07.204  4300  4300 D Launcher: onPause, Launcher: 198492302
09-15 12:03:07.204  4300  4300 D Launcher.HomeView: onPause
09-15 12:03:07.204  3410  3594 D PackageManager: [MSG] START_CLEANING_PACKAGE packageName{com.test.thalitest}
09-15 12:03:07.204  3410  3594 D PackageManager: userId{-1}
09-15 12:03:07.204  3410  3594 D PackageManager: andCode{true}
09-15 12:03:07.204  4300  4300 D Launcher.Workspace: exitWidgetResizeMode. isClearResizeFrame is false
,09-15 12:03:07.214  3410  3979 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{891d232 u0 com.android.launcher.action.HOME_MODE_CHANGE qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{1da5c03 9906:com.sec.android.app.clockpackage/u0a93}
,09-15 12:03:07.234  3410  3594 I ActivityManager: Force stopping com.test.thalitest appid=10177 user=0: pkg removed
,09-15 12:03:07.264  3410  4251 V WindowStateAnimator: Finishing drawing window Window{5bab6a9 u0 d0 com.sec.android.app.launcher/com.sec.android.app.launcher.activities.LauncherActivity}: mDrawState=DRAW_PENDING
09-15 12:03:07.264  4300  4300 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@72e9445 time:211423
,09-15 12:03:07.264  9412 10072 W System.err: remove failed: ENOENT (No such file or directory) : /storage/emulated/0/Android/data/com.test.thalitest
,09-15 12:03:07.264  9412 10072 W System.err: remove failed: ENOENT (No such file or directory) : /storage/emulated/0/Android/media/com.test.thalitest
,09-15 12:03:07.274  3009  3009 D libEGL  : eglInitialize EGLDisplay = 0x7ff285be68
,09-15 12:03:07.274  9412 10072 W System.err: remove failed: ENOENT (No such file or directory) : /storage/emulated/0/Android/obb/com.test.thalitest
,09-15 12:03:07.294  3410  3410 W ResourcesManager: getTopLevelResources: /system/priv-app/GmsCore/GmsCore.apk / 1.0 running in null rsrc of package com.google.android.gms
09-15 12:03:07.294  3410  3536 W ResourcesManager: getTopLevelResources: /system/priv-app/Velvet/Velvet.apk / 1.0 running in null rsrc of package com.google.android.googlequicksearchbox
,09-15 12:03:07.304  3410  3536 D ResourcesManager: For user 0 new overlays fetched Null
,09-15 12:03:07.304  3410  3536 W ResourcesManager: getTopLevelResources: /system/priv-app/Velvet/Velvet.apk / 1.0 running in null rsrc of package com.google.android.googlequicksearchbox
,09-15 12:03:07.304  3410  3536 W ResourcesManager: getTopLevelResources: /system/app/SamsungIMEv3/SamsungIMEv3.apk / 1.0 running in null rsrc of package com.sec.android.inputmethod
09-15 12:03:07.304  3950  3950 D ShortcutManager: onReceive : android.intent.action.PACKAGE_REMOVED
09-15 12:03:07.304  3950  3950 D ShortcutManager: onReceive : Intent.EXTRA_REPLACING false,com.test.thalitest
,09-15 12:03:07.304  3410  3410 D ResourcesManager: For user 0 new overlays fetched Null
,09-15 12:03:07.304  4137  4137 I CatchNotificationsService: mPackageChangedReceiver : onReceive action = android.intent.action.PACKAGE_REMOVED
09-15 12:03:07.304  3410  3536 D ResourcesManager: For user 0 new overlays fetched Null
,09-15 12:03:07.314  3410  3410 W ResourcesManager: getTopLevelResources: /system/priv-app/GmsCore/GmsCore.apk / 1.0 running in null rsrc of package com.google.android.gms
09-15 12:03:07.314  3410  3536 W ResourcesManager: getTopLevelResources: /system/app/SamsungIMEv3/SamsungIMEv3.apk / 1.0 running in null rsrc of package com.sec.android.inputmethod
,09-15 12:03:07.314  3410  3410 W ResourcesManager: getTopLevelResources: /system/priv-app/SNS_v2/SNS_v2.apk / 1.0 running in null rsrc of package com.sec.android.app.sns3
,09-15 12:03:07.314  3410  3410 D ResourcesManager: For user 0 new overlays fetched Null
,09-15 12:03:07.314  3410  3536 W ResourcesManager: getTopLevelResources: /system/priv-app/Velvet/Velvet.apk / 1.0 running in null rsrc of package com.google.android.googlequicksearchbox
09-15 12:03:07.314  3410  3410 W ResourcesManager: getTopLevelResources: /system/priv-app/SNS_v2/SNS_v2.apk / 1.0 running in null rsrc of package com.sec.android.app.sns3
09-15 12:03:07.314  3410  3410 W ResourcesManager: getTopLevelResources: /system/priv-app/SNS_v2/SNS_v2.apk / 1.0 running in null rsrc of package com.sec.android.app.sns3
09-15 12:03:07.314  3410  3536 W ResourcesManager: getTopLevelResources: /system/app/SamsungIMEv3/SamsungIMEv3.apk / 1.0 running in null rsrc of package com.sec.android.inputmethod
,09-15 12:03:07.314  3410  3410 W ResourcesManager: getTopLevelResources: /system/priv-app/SNS_v2/SNS_v2.apk / 1.0 running in null rsrc of package com.sec.android.app.sns3
09-15 12:03:07.314  3410  3536 W ResourcesManager: getTopLevelResources: /system/app/SamsungIMEv3/SamsungIMEv3.apk / 1.0 running in null rsrc of package com.sec.android.inputmethod
,09-15 12:03:07.314  3410  3410 W ResourcesManager: getTopLevelResources: /system/priv-app/SNS_v2/SNS_v2.apk / 1.0 running in null rsrc of package com.sec.android.app.sns3
09-15 12:03:07.314  3410  3410 W ResourcesManager: getTopLevelResources: /system/priv-app/SNS_v2/SNS_v2.apk / 1.0 running in null rsrc of package com.sec.android.app.sns3,
09-15 12:03:07.314  3410  3536 W ResourcesManager: getTopLevelResources: /system/priv-app/LiveBroadcast/LiveBroadcast.apk / 1.0 running in null rsrc of package com.sec.android.app.camera.plb
09-15 12:03:07.314  3410  3410 W ResourcesManager: getTopLevelResources: /system/priv-app/SamsungAccount_Hero/SamsungAccount_Hero.apk / 1.0 running in null rsrc of package com.osp.app.signin
,09-15 12:03:07.324  3410  3410 D ResourcesManager: For user 0 new overlays fetched Null
09-15 12:03:07.324  3410  3536 D ResourcesManager: For user 0 new overlays fetched Null
,09-15 12:03:07.324  3410  3536 W ResourcesManager: getTopLevelResources: /system/priv-app/LiveBroadcast/LiveBroadcast.apk / 1.0 running in null rsrc of package com.sec.android.app.camera.plb
,09-15 12:03:07.324  3410  3536 W ResourcesManager: getTopLevelResources: /system/priv-app/SamsungCamera5/SamsungCamera5.apk / 1.0 running in null rsrc of package com.sec.android.app.camera
,09-15 12:03:07.324  3410  3410 W ResourcesManager: getTopLevelResources: /system/priv-app/SamsungAccount_Hero/SamsungAccount_Hero.apk / 1.0 running in null rsrc of package com.osp.app.signin
09-15 12:03:07.324  3410  3410 W ResourcesManager: getTopLevelResources: /system/priv-app/SecEmail_M/SecEmail_M.apk / 1.0 running in null rsrc of package com.samsung.android.email.provider
,09-15 12:03:07.334  3410  3536 D ResourcesManager: For user 0 new overlays fetched Null
,09-15 12:03:07.334  3410  3536 W ResourcesManager: getTopLevelResources: /system/priv-app/SamsungCamera5/SamsungCamera5.apk / 1.0 running in null rsrc of package com.sec.android.app.camera
09-15 12:03:07.334  3410  3536 W ResourcesManager: getTopLevelResources: /system/app/STalkback/STalkback.apk / 1.0 running in null rsrc of package com.samsung.android.app.talkback
,09-15 12:03:07.334  4287  4287 W ResourcesManager: getTopLevelResources: /system/priv-app/SecMms_Epic_Common/SecMms_Epic_Common.apk / 1.0 running in com.android.phone rsrc of package com.android.mms
,09-15 12:03:07.334  3410  3536 D ResourcesManager: For user 0 new overlays fetched Null
09-15 12:03:07.334  3410  3410 D ResourcesManager: For user 0 new overlays fetched Null
,09-15 12:03:07.334  3410  3410 W ResourcesManager: getTopLevelResources: /system/priv-app/SecEmail_M/SecEmail_M.apk / 1.0 running in null rsrc of package com.samsung.android.email.provider
09-15 12:03:07.334  3410  3410 W ResourcesManager: getTopLevelResources: /system/priv-app/SecEmail_M/SecEmail_M.apk / 1.0 running in null rsrc of package com.samsung.android.email.provider
09-15 12:03:07.334  3410  3536 W ResourcesManager: getTopLevelResources: /system/app/STalkback/STalkback.apk / 1.0 running in null rsrc of package com.samsung.android.app.talkback
09-15 12:03:07.334  3410  3410 W ResourcesManager: getTopLevelResources: /system/priv-app/SecEmail_M/SecEmail_M.apk / 1.0 running in null rsrc of package com.samsung.android.email.provider
09-15 12:03:07.334  3410  3410 W ResourcesManager: getTopLevelResources: /system/priv-app/SecEmail_M/SecEmail_M.apk / 1.0 running in null rsrc of package com.samsung.android.email.provider
09-15 12:03:07.334  3410  3410 W ResourcesManager: getTopLevelResources: /system/priv-app/SecEmail_M/SecEmail_M.apk / 1.0 running in null rsrc of package com.samsung.android.email.provider
09-15 12:03:07.334  3410  3536 W ResourcesManager: getTopLevelResources: /system/app/UniversalSwitch/UniversalSwitch.apk / 1.0 running in null rsrc of package com.samsung.android.universalswitch
09-15 12:03:07.334  3410  3410 W ResourcesManager: getTopLevelResources: /system/app/CoreApps/CoreApps.apk / 1.0 running in null rsrc of package com.samsung.android.coreapps
,09-15 12:03:07.334  3410  3410 D ResourcesManager: For user 0 new overlays fetched Null
,09-15 12:03:07.344  3410  3410 W ResourcesManager: getTopLevelResources: /system/app/CoreApps/CoreApps.apk / 1.0 running in null rsrc of package com.samsung.android.coreapps
09-15 12:03:07.344  3410  3536 D ResourcesManager: For user 0 new overlays fetched Null
09-15 12:03:07.344  3410  3410 W ResourcesManager: getTopLevelResources: /system/app/Gmail2/Gmail2.apk / 1.0 running in null rsrc of package com.google.android.gm
09-15 12:03:07.344  3410  3536 W ResourcesManager: getTopLevelResources: /system/app/UniversalSwitch/UniversalSwitch.apk / 1.0 running in null rsrc of package com.samsung.android.universalswitch
,09-15 12:03:07.344  3410  3536 D AccessibilityManagerService: onUserStateChangedLocked()
09-15 12:03:07.344  4313  4827 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
09-15 12:03:07.344  3410  3536 D AccessibilityManagerService: updateServicesLocked().mIsAccessibilityEnabled : false
09-15 12:03:07.344  3410  3410 D ResourcesManager: For user 0 new overlays fetched Null
09-15 12:03:07.344  4287  4287 D ResourcesManager: For user 0 new overlays fetched Null
09-15 12:03:07.344  3410  3410 W ResourcesManager: getTopLevelResources: /system/app/Gmail2/Gmail2.apk / 1.0 running in null rsrc of package com.google.android.gm
09-15 12:03:07.344  3410  3410 W ResourcesManager: getTopLevelResources: /system/app/Gmail2/Gmail2.apk / 1.0 running in null rsrc of package com.google.android.gm
09-15 12:03:07.344  3410  3410 W ResourcesManager: getTopLevelResources: /system/app/Gmail2/Gmail2.apk / 1.0 running in null rsrc of package com.google.android.gm
09-15 12:03:07.344  3410  3410 W ResourcesManager: getTopLevelResources: /system/app/OneDrive_Samsung_v2/OneDrive_Samsung_v2.apk / 1.0 running in null rsrc of package com.microsoft.skydrive
,09-15 12:03:07.344  3410  3410 D ResourcesManager: For user 0 new overlays fetched Null
,09-15 12:03:07.344  3410  3410 W ResourcesManager: getTopLevelResources: /system/app/OneDrive_Samsung_v2/OneDrive_Samsung_v2.apk / 1.0 running in null rsrc of package com.microsoft.skydrive
09-15 12:03:07.344  3410  3410 W ResourcesManager: getTopLevelResources: /system/app/OneNote/OneNote.apk / 1.0 running in null rsrc of package com.microsoft.office.onenote
,09-15 12:03:07.344  5070  5273 D PresenceModule: onReceive: package removed
,09-15 12:03:07.344  5070  5273 D PresenceModule: handleMessage: msg 50, Last Publish Info: null
09-15 12:03:07.344  3410  3410 D ResourcesManager: For user 0 new overlays fetched Null
09-15 12:03:07.344  5070  5273 D PresenceModule: Application package removed
09-15 12:03:07.344  3410  3410 W ResourcesManager: getTopLevelResources: /system/app/OneNote/OneNote.apk / 1.0 running in null rsrc of package com.microsoft.office.onenote
09-15 12:03:07.344  5070  5273 D PresenceModule: onAppPkgRemoved: com.test.thalitest
09-15 12:03:07.344  3410  3410 W ResourcesManager: getTopLevelResources: /system/app/SBrowser_4_LATEST/SBrowser_4_LATEST.apk / 1.0 running in null rsrc of package com.sec.android.app.sbrowser
09-15 12:03:07.344  5070  5273 D PresenceModule: onApplicationPackageRemoved: invalid package
,09-15 12:03:07.354  4150  4150 I PeoplePackageManager: onReceive:android.intent.action.PACKAGE_REMOVED
,09-15 12:03:07.354  3410  3410 D ResourcesManager: For user 0 new overlays fetched Null
09-15 12:03:07.354  3410  3536 D EnterpriseDeviceManagerService: Package has changed for user 0
09-15 12:03:07.354  3410  3410 W ResourcesManager: getTopLevelResources: /system/app/SBrowser_4_LATEST/SBrowser_4_LATEST.apk / 1.0 running in null rsrc of package com.sec.android.app.sbrowser
09-15 12:03:07.354  3410  3536 D EnterpriseDeviceManagerService: Admin package name: com.google.android.gms
09-15 12:03:07.354  4287  4287 W ResourcesManager: getTopLevelResources: /system/app/Hangouts/Hangouts.apk / 1.0 running in com.android.phone rsrc of package com.google.android.talk
09-15 12:03:07.354  3410  3536 W ResourcesManager: getTopLevelResources: /system/app/SamsungIMEv3/SamsungIMEv3.apk / 1.0 running in null rsrc of package com.sec.android.inputmethod
09-15 12:03:07.354  3410  3410 W ResourcesManager: getTopLevelResources: /system/priv-app/GmsCore/GmsCore.apk / 1.0 running in null rsrc of package com.google.android.gms
09-15 12:03:07.354  3410  3536 W ResourcesManager: getTopLevelResources: /system/app/SamsungIMEv3/SamsungIMEv3.apk / 1.0 running in null rsrc of package com.sec.android.inputmethod
09-15 12:03:07.354  4287  4287 D ResourcesManager: For user 0 new overlays fetched Null
09-15 12:03:07.364  3410  3410 W ResourcesManager: getTopLevelResources: /system/priv-app/GmsCore/GmsCore.apk / 1.0 running in null rsrc of package com.google.android.gms
09-15 12:03:07.364  3410  3410 W ResourcesManager: getTopLevelResources: /system/priv-app/GmsCore/GmsCore.apk / 1.0 running in null rsrc of package com.google.android.gms
09-15 12:03:07.364  3410  3410 W ResourcesManager: getTopLevelResources: /system/priv-app/GmsCore/GmsCore.apk / 1.0 running in null rsrc of package com.google.android.gms
09-15 12:03:07.364  3410  3410 W ResourcesManager: getTopLevelResources: /system/priv-app/GmsCore/GmsCore.apk / 1.0 running in null rsrc of package com.google.android.gms
09-15 12:03:07.364  3410  3410 W ResourcesManager: getTopLevelResources: /system/priv-app/GmsCore/GmsCore.apk / 1.0 running in null rsrc of package com.google.android.gms
09-15 12:03:07.364  3410  3410 W ResourcesManager: getTopLevelResources: /system/priv-app/GmsCore/GmsCore.apk / 1.0 running in null rsrc of package com.google.android.gms
09-15 12:03:07.364  3410  3410 W ResourcesManager: getTopLevelResources: /system/priv-app/GmsCore/GmsCore.apk / 1.0 running in null rsrc of package com.google.android.gms
09-15 12:03:07.364  3410  3410 W ResourcesManager: getTopLevelResources: /system/priv-app/GmsCore/GmsCore.apk / 1.0 running in null rsrc of package com.google.android.gms
09-15 12:03:07.364  3410  3410 W ResourcesManager: getTopLevelResources: /system/priv-app/GmsCore/GmsCore.apk / 1.0 running in null rsrc of package com.google.android.gms
09-15 12:03:07.364  3410  3410 W ResourcesManager: getTopLevelResources: /system/priv-app/GmsCore/GmsCore.apk / 1.0 running in null rsrc of package com.google.android.gms
09-15 12:03:07.364  3410  3410 W ResourcesManager: getTopLevelResources: /system/priv-app/GmsCore/GmsCore.apk / 1.0 running in null rsrc of package com.google.android.gms
09-15 12:03:07.364  3410  3410 W ResourcesManager: getTopLevelResources: /system/priv-app/GmsCore/GmsCore.apk / 1.0 running in null rsrc of package com.google.android.gms
09-15 12:03:07.364  3410  3410 W ResourcesManager: getTopLevelResources: /system/priv-app/GmsCore/GmsCore.apk / 1.0 running in null rsrc of package com.google.android.gms
09-15 12:03:07.364  3410  3410 W ResourcesManager: getTopLevelResources: /system/priv-app/GmsCore/GmsCore.apk / 1.0 running in null rsrc of package com.google.android.gms
09-15 12:03:07.364  3410  3410 W ResourcesManager: getTopLevelResources: /system/priv-app/GmsCore/GmsCore.apk / 1.0 running in null rsrc of package com.google.android.gms
,09-15 12:03:07.364  3410  3410 W ResourcesManager: getTopLevelResources: /system/priv-app/GmsCore/GmsCore.apk / 1.0 running in null rsrc of package com.google.android.gms
09-15 12:03:07.364  3410  3410 W ResourcesManager: getTopLevelResources: /system/priv-app/GmsCore/GmsCore.apk / 1.0 running in null rsrc of package com.google.android.gms
09-15 12:03:07.364  3410  4952 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{c3bf4de u0 android.intent.action.DROPBOX_ENTRY_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{116a3b 9313:com.samsung.android.sm/1000}
09-15 12:03:07.364  3410  3410 W ResourcesManager: getTopLevelResources: /system/priv-app/GmsCore/GmsCore.apk / 1.0 running in null rsrc of package com.google.android.gms
09-15 12:03:07.364  3410  3410 W ResourcesManager: getTopLevelResources: /system/priv-app/GmsCore/GmsCore.apk / 1.0 running in null rsrc of package com.google.android.gms
09-15 12:03:07.364  3410  3410 W ResourcesManager: getTopLevelResources: /system/priv-app/GmsCore/GmsCore.apk / 1.0 running in null rsrc of package com.google.android.gms
09-15 12:03:07.364  3410  3410 W ResourcesManager: getTopLevelResources: /system/priv-app/GmsCore/GmsCore.apk / 1.0 running in null rsrc of package com.google.android.gms
09-15 12:03:07.364  3410  3410 W ResourcesManager: getTopLevelResources: /system/priv-app/GmsCore/GmsCore.apk / 1.0 running in null rsrc of package com.google.android.gms
09-15 12:03:07.364  3410  3410 W ResourcesManager: getTopLevelResources: /system/priv-app/GmsCore/GmsCore.apk / 1.0 running in null rsrc of package com.google.android.gms
09-15 12:03:07.364  3410  3410 W ResourcesManager: getTopLevelResources: /system/priv-app/GmsCore/GmsCore.apk / 1.0 running in null rsrc of package com.google.android.gms
09-15 12:03:07.364  3410  3410 W ResourcesManager: getTopLevelResources: /system/priv-app/GmsCore/GmsCore.apk / 1.0 running in null rsrc of package com.google.android.gms
09-15 12:03:07.364  3410  3410 W ResourcesManager: getTopLevelResources: /system/priv-app/GmsCore/GmsCore.apk / 1.0 running in null rsrc of package com.google.android.gms
09-15 12:03:07.364  3410  3410 W ResourcesManager: getTopLevelResources: /system/priv-app/GmsCore/GmsCore.apk / 1.0 running in null rsrc of package com.google.android.gms
09-15 12:03:07.364  3410  3410 W ResourcesManager: getTopLevelResources: /system/priv-app/GmsCore/GmsCore.apk / 1.0 running in null rsrc of package com.google.android.gms
09-15 12:03:07.364  3410  3410 W ResourcesManager: getTopLevelResources: /system/priv-app/GmsCore/GmsCore.apk / 1.0 running in null rsrc of package com.google.android.gms
09-15 12:03:07.364  3410  3410 W ResourcesManager: getTopLevelResources: /system/priv-app/GmsCore/GmsCore.apk / 1.0 running in null rsrc of package com.google.android.gms
09-15 12:03:07.364  3410  3410 W ResourcesManager: getTopLevelResources: /system/priv-app/GmsCore/GmsCore.apk / 1.0 running in null rsrc of package com.google.android.gms
09-15 12:03:07.364  3410  3410 W ResourcesManager: getTopLevelResources: /system/priv-app/GoogleServicesFramework/GoogleServicesFramework.apk / 1.0 running in null rsrc of package com.google.android.gsf
09-15 12:03:07.364  3410  3536 W ResourcesManager: getTopLevelResources: /system/priv-app/SecSettings2/SecSettings2.apk / 1.0 running in null rsrc of package com.android.settings
09-15 12:03:07.364  3410  3410 D ResourcesManager: For user 0 new overlays fetched Null
09-15 12:03:07.364  3410  3410 W ResourcesManager: getTopLevelResources: /system/priv-app/GoogleServicesFramework/GoogleServicesFramework.apk / 1.0 running in null rsrc of package com.google.android.gsf
09-15 12:03:07.374  3410  3410 W ResourcesManager: getTopLevelResources: /system/priv-app/SHealth4/SHealth4.apk / 1.0 running in null rsrc of package com.sec.android.app.shealth
09-15 12:03:07.374  3410  3572 D KnoxTimeoutHandler: notifyActivityDrawn [MsgParam] userId: 0 fullscreen is true showWhenlocked is false
09-15 12:03:07.374  9313  9313 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1305 android.content.ContextWrapper.startService:606 android.content.ContextWrapper.startService:606 com.samsung.android.sm.common.SmartManagerReceiver.b:259 com.samsung.android.sm.common.SmartManagerReceiver.onReceive:107 
09-15 12:03:07.374  3410  3410 D ResourcesManager: For user 0 new overlays fetched Null
09-15 12:03:07.374  3410  3536 D ResourcesManager: For user 0 new overlays fetched Null
09-15 12:03:07.374  3410  3410 W ResourcesManager: getTopLevelResources: /system/priv-app/SHealth4/SHealth4.apk / 1.0 running in null rsrc of package com.sec.android.app.shealth
09-15 12:03:07.374  3410  3536 W ResourcesManager: getTopLevelResources: /system/priv-app/SecSettings2/SecSettings2.apk / 1.0 running in null rsrc of package com.android.settings
09-15 12:03:07.374  3410  3410 W ResourcesManager: getTopLevelResources: /system/priv-app/SHealth4/SHealth4.apk / 1.0 running in null rsrc of package com.sec.android.app.shealth
09-15 12:03:07.374  3410  3410 W ResourcesManager: getTopLevelResources: /system/priv-app/SHealth4/SHealth4.apk / 1.0 running in null rsrc of package com.sec.android.app.shealth
09-15 12:03:07.374  3410  3536 W ResourcesManager: getTopLevelResources: /system/priv-app/SecContacts_M/SecContacts_M.apk / 1.0 running in null rsrc of package com.android.contacts
09-15 12:03:07.374  3410  3410 W ResourcesManager: getTopLevelResources: /system/priv-app/SNS_v2/SNS_v2.apk / 1.0 running in null rsrc of package com.sec.android.app.sns3
09-15 12:03:07.374  3410  3410 W ResourcesManager: getTopLevelResources: /system/priv-app/SNS_v2/SNS_v2.apk / 1.0 running in null rsrc of package com.sec.android.app.sns3
09-15 12:03:07.374  3410  3410 W ResourcesManager: getTopLevelResources: /system/priv-app/SNS_v2/SNS_v2.apk / 1.0 running in null rsrc of package com.sec.android.app.sns3
09-15 12:03:07.374  3410  3410 W ResourcesManager: getTopLevelResources: /system/priv-app/SNS_v2/SNS_v2.apk / 1.0 running in null rsrc of package com.sec.android.app.sns3
09-15 12:03:07.374  3410  3410 W ResourcesManager: getTopLevelResources: /system/priv-app/SNS_v2/SNS_v2.apk / 1.0 running in null rsrc of package com.sec.android.app.sns3
09-15 12:03:07.374  3410  3410 W ResourcesManager: getTopLevelResources: /system/priv-app/SNS_v2/SNS_v2.apk / 1.0 running in null rsrc of package com.sec.android.app.sns3
09-15 12:03:07.374  3410  3410 W ResourcesManager: getTopLevelResources: /system/priv-app/SNS_v2/SNS_v2.apk / 1.0 running in null rsrc of package com.sec.android.app.sns3
09-15 12:03:07.374  3410  3410 W ResourcesManager: getTopLevelResources: /system/priv-app/SNS_v2/SNS_v2.apk / 1.0 running in null rsrc of package com.sec.android.app.sns3
09-15 12:03:07.374  3410  3410 W ResourcesManager: getTopLevelResources: /system/priv-app/SNS_v2/SNS_v2.apk / 1.0 running in null rsrc of package com.sec.android.app.sns3
09-15 12:03:07.374  3410  3410 W ResourcesManager: getTopLevelResources: /system/priv-app/SNS_v2/SNS_v2.apk / 1.0 running in null rsrc of package com.sec.android.app.sns3
09-15 12:03:07.374  3410  3410 W ResourcesManager: getTopLevelResources: /system/priv-app/SNS_v2/SNS_v2.apk / 1.0 running in null rsrc of package com.sec.android.app.sns3
09-15 12:03:07.374  3410  3410 W ResourcesManager: getTopLevelResources: /system/priv-app/SNS_v2/SNS_v2.apk / 1.0 running in null rsrc of package com.sec.android.app.sns3
09-15 12:03:07.374  3410  3410 W ResourcesManager: getTopLevelResources: /system/priv-app/SecEmail_M/SecEmail_M.apk / 1.0 running in null rsrc of package com.samsung.android.email.provider
09-15 12:03:07.374  3410  3410 W ResourcesManager: getTopLevelResources: /system/priv-app/SecEmail_M/SecEmail_M.apk / 1.0 running in null rsrc of package com.samsung.android.email.provider
09-15 12:03:07.374  3410  3410 W ResourcesManager: getTopLevelResources: /system/priv-app/SecEmail_M/SecEmail_M.apk / 1.0 running in null rsrc of package com.samsung.android.email.provider
09-15 12:03:07.374  3410  3410 W ResourcesManager: getTopLevelResources: /system/priv-app/SecEmail_M/SecEmail_M.apk / 1.0 running in null rsrc of package com.samsung.android.email.provider
09-15 12:03:07.374  3410  3410 W ResourcesManager: getTopLevelResources: /system/priv-app/SecEmail_M/SecEmail_M.apk / 1.0 running in null rsrc of package com.samsung.android.email.provider
09-15 12:03:07.374  3410  3410 W ResourcesManager: getTopLevelResources: /system/priv-app/SecEmail_M/SecEmail_M.apk / 1.0 running in null rsrc of package com.samsung.android.email.provider
09-15 12:03:07.374  3410  3410 W ResourcesManager: getTopLevelResources: /system/priv-app/SecEmail_M/SecEmail_M.apk / 1.0 running in null rsrc of package com.samsung.android.email.provider
09-15 12:03:07.374  3410  3410 W ResourcesManager: getTopLevelResources: /system/priv-app/SecEmail_M/SecEmail_M.apk / 1.0 running in null rsrc of package com.samsung.android.email.provider
09-15 12:03:07.374  3410  3410 W ResourcesManager: getTopLevelResources: /system/priv-app/SecEmail_M/SecEmail_M.apk / 1.0 running in null rsrc of package com.samsung.android.email.provider
09-15 12:03:07.374  3410  3536 D ResourcesManager: For user 0 new overlays fetched Null
09-15 12:03:07.374  3410  3410 W ResourcesManager: getTopLevelResources: /system/priv-app/SecEmail_M/SecEmail_M.apk / 1.0 running in null rsrc of package com.samsung.android.email.provider
09-15 12:03:07.374  3410  3410 W ResourcesManager: getTopLevelResources: /system/priv-app/SecEmail_M/SecEmail_M.apk / 1.0 running in null rsrc of package com.samsung.android.email.provider
09-15 12:03:07.374  3410  3410 W ResourcesManager: getTopLevelResources: /system/priv-app/SecEmail_M/SecEmail_M.apk / 1.0 running in null rsrc of package com.samsung.android.email.provider
09-15 12:03:07.374  3410  3536 W ResourcesManager: getTopLevelResources: /system/priv-app/SecContacts_M/SecContacts_M.apk / 1.0 running in null rsrc of package com.android.contacts
09-15 12:03:07.374  3410  3410 W ResourcesManager: getTopLevelResources: /system/priv-app/SecEmail_M/SecEmail_M.apk / 1.0 running in null rsrc of package com.samsung.android.email.provider
09-15 12:03:07.374  3410  3410 W ResourcesManager: getTopLevelResources: /system/priv-app/SecEmail_M/SecEmail_M.apk / 1.0 running in null rsrc of package com.samsung.android.email.provider
09-15 12:03:07.374  3410  3410 W ResourcesManager: getTopLevelResources: /system/priv-app/SecEmail_M/SecEmail_M.apk / 1.0 running in null rsrc of package com.samsung.android.email.provider
09-15 12:03:07.374  3410  3536 W ResourcesManager: getTopLevelResources: /system/priv-app/SecContacts_M/SecContacts_M.apk / 1.0 running in null rsrc of package com.android.contacts
09-15 12:03:07.374  3410  3410 W ResourcesManager: getTopLevelResources: /system/priv-app/SecEmail_M/SecEmail_M.apk / 1.0 running in null rsrc of package com.samsung.android.email.provider
09-15 12:03:07.384  3410  3410 W ResourcesManager: getTopLevelResources: /system/priv-app/SamsungCloud/SamsungCloud.apk / 1.0 running in null rsrc of package com.samsung.android.scloud
09-15 12:03:07.384  3410  3536 W ResourcesManager: getTopLevelResources: /system/priv-app/SecContacts_M/SecContacts_M.apk / 1.0 running in null rsrc of package com.android.contacts
09-15 12:03:07.384  3410  3536 W ResourcesManager: getTopLevelResources: /system/priv-app/SecEmail_M/SecEmail_M.apk / 1.0 running in null rsrc of package com.samsung.android.email.provider
09-15 12:03:07.384  3410  3536 W ResourcesManager: getTopLevelResources: /system/priv-app/SecEmail_M/SecEmail_M.apk / 1.0 running in null rsrc of package com.samsung.android.email.provider
09-15 12:03:07.384  3410  3410 D ResourcesManager: For user 0 new overlays fetched Null
09-15 12:03:07.384  3410  3536 W ResourcesManager: getTopLevelResources: /system/priv-app/SecMms_Epic_Common/SecMms_Epic_Common.apk / 1.0 running in null rsrc of package com.android.mms
09-15 12:03:07.384  3410  3410 W ResourcesManager: getTopLevelResources: /system/priv-app/SamsungCloud/SamsungCloud.apk / 1.0 running in null rsrc of package com.samsung.android.scloud
09-15 12:03:07.384  3410  3410 W ResourcesManager: getTopLevelResources: /system/priv-app/SamsungCloud/SamsungCloud.apk / 1.0 running in null rsrc of package com.samsung.android.scloud
09-15 12:03:07.384  3410  3410 W ResourcesManager: getTopLevelResources: /system/priv-app/SamsungCloud/SamsungCloud.apk / 1.0 running in null rsrc of package com.samsung.android.scloud
09-15 12:03:07.384  3410  3410 W ResourcesManager: getTopLevelResources: /system/priv-app/SamsungCloud/SamsungCloud.apk / 1.0 running in null rsrc of package com.samsung.android.scloud
09-15 12:03:07.384  3410  3410 W ResourcesManager: getTopLevelResources: /system/priv-app/SamsungCloud/SamsungCloud.apk / 1.0 running in null rsrc of package com.samsung.android.scloud
09-15 12:03:07.384  3410  3410 W ResourcesManager: getTopLevelResources: /system/priv-app/SamsungCloud/SamsungCloud.apk / 1.0 running in null rsrc of package com.samsung.android.scloud
09-15 12:03:07.384  4300  4300 V ActivityThread: updateVisibility : ActivityRecord{37ea16c token=android.os.BinderProxy@72e9445 {com.sec.android.app.launcher/com.sec.android.app.launcher.activities.LauncherActivity}} show : true
09-15 12:03:07.384  3410  3410 W ResourcesManager: getTopLevelResources: /system/priv-app/SamsungCloud/SamsungCloud.apk / 1.0 running in null rsrc of package com.samsung.android.scloud
09-15 12:03:07.384  3410  3410 W ResourcesManager: getTopLevelResources: /system/priv-app/SamsungCloud/SamsungCloud.apk / 1.0 running in null rsrc of package com.samsung.android.scloud
09-15 12:03:07.384  3410  3410 W ResourcesManager: getTopLevelResources: /system/priv-app/SamsungCloud/SamsungCloud.apk / 1.0 running in null rsrc of package com.samsung.android.scloud
09-15 12:03:07.384  3410  3410 W ResourcesManager: getTopLevelResources: /system/priv-app/SamsungCloud/SamsungCloud.apk / 1.0 running in null rsrc of package com.samsung.android.scloud
09-15 12:03:07.384  3410  3410 W ResourcesManager: getTopLevelResources: /system/priv-app/SamsungCloud/SamsungCloud.apk / 1.0 running in null rsrc of package com.samsung.android.scloud
09-15 12:03:07.384  3410  3410 W ResourcesManager: getTopLevelResources: /system/priv-app/SamsungCloud/SamsungCloud.apk / 1.0 running in null rsrc of package com.samsung.android.scloud
09-15 12:03:07.384  3410  3410 W ResourcesManager: getTopLevelResources: /system/priv-app/SamsungCloud/SamsungCloud.apk / 1.0 running in null rsrc of package com.samsung.android.scloud
09-15 12:03:07.384  4023  4023 I Recents_MultiWindowAppListInfo: android.intent.action.PACKAGE_REMOVE
09-15 12:03:07.384  3410  3410 W ResourcesManager: getTopLevelResources: /system/app/Chrome/Chrome.apk / 1.0 running in null rsrc of package com.android.chrome
09-15 12:03:07.384  3410  3536 D ResourcesManager: For user 0 new overlays fetched Null
09-15 12:03:07.384  3410  3536 W ResourcesManager: getTopLevelResources: /system/priv-app/SecMms_Epic_Common/SecMms_Epic_Common.apk / 1.0 running in null rsrc of package com.android.mms
09-15 12:03:07.384  3410  3536 W ResourcesManager: getTopLevelResources: /system/priv-app/SecMyFiles/SecMyFiles.apk / 1.0 running in null rsrc of package com.sec.android.app.myfiles
09-15 12:03:07.384  4300  4300 D Launcher.HomeView: onStop
09-15 12:03:07.384  4300  4300 D capture : ----destroy
09-15 12:03:07.384  3410  3410 D ResourcesManager: For user 0 new overlays fetched Null
09-15 12:03:07.384  3410  3536 D ResourcesManager: For user 0 new overlays fetched Null
09-15 12:03:07.384  3410  3410 W ResourcesManager: getTopLevelResources: /system/app/Chrome/Chrome.apk / 1.0 running in null rsrc of package com.android.chrome
09-15 12:03:07.384  3410  3410 W ResourcesManager: getTopLevelResources: /system/app/CoreApps/CoreApps.apk / 1.0 running in null rsrc of package com.samsung.android.coreapps
09-15 12:03:07.394  3410  3410 W ResourcesManager: getTopLevelResources: /system/app/CoreApps/CoreApps.apk / 1.0 running in null rsrc of package com.samsung.android.coreapps
09-15 12:03:07.394  3410  3410 W ResourcesManager: getTopLevelResources: /system/app/Drive/Drive.apk / 1.0 running in null rsrc of package com.google.android.apps.docs
09-15 12:03:07.394  3410  3536 W ResourcesManager: getTopLevelResources: /system/priv-app/SecMyFiles/SecMyFiles.apk / 1.0 running in null rsrc of package com.sec.android.app.myfiles
09-15 12:03:07.394  3410  3880 D MdnieScenarioControlService:  packageName : com.sec.android.app.launcher    className : com.sec.android.app.launcher.activities.LauncherActivity
09-15 12:03:07.394  3410  3880 I MdnieScenarioControlService: mGameModeLauncher : false
09-15 12:03:07.394  3410  3880 I MdnieScenarioControlService: setUIMode
09-15 12:03:07.394  3410  4715 W ActivityManager: Permission Denial: Accessing service ComponentInfo{com.google.android.music/com.google.android.music.dial.DialMediaRouteProviderService} from pid=4829, uid=10130 that is not exported from uid 10128
09-15 12:03:07.394  3410  3536 W ResourcesManager: getTopLevelResources: /system/app/Music2/Music2.apk / 1.0 running in null rsrc of package com.google.android.music
09-15 12:03:07.394  3410  3410 D ResourcesManager: For user 0 new overlays fetched Null
,09-15 12:03:07.394  3410  3410 W ResourcesManager: getTopLevelResources: /system/app/Drive/Drive.apk / 1.0 running in null rsrc of package com.google.android.apps.docs
09-15 12:03:07.394  3410  3410 W ResourcesManager: getTopLevelResources: /system/app/Gmail2/Gmail2.apk / 1.0 running in null rsrc of package com.google.android.gm
09-15 12:03:07.394  3410  3410 W ResourcesManager: getTopLevelResources: /system/app/Gmail2/Gmail2.apk / 1.0 running in null rsrc of package com.google.android.gm
09-15 12:03:07.394  3410  3410 W ResourcesManager: getTopLevelResources: /system/app/Gmail2/Gmail2.apk / 1.0 running in null rsrc of package com.google.android.gm
09-15 12:03:07.394  3410  3410 W ResourcesManager: getTopLevelResources: /system/app/Gmail2/Gmail2.apk / 1.0 running in null rsrc of package com.google.android.gm
09-15 12:03:07.394  3410  3410 W ResourcesManager: getTopLevelResources: /system/app/Gmail2/Gmail2.apk / 1.0 running in null rsrc of package com.google.android.gm
09-15 12:03:07.394  3410  3410 W ResourcesManager: getTopLevelResources: /system/app/Gmail2/Gmail2.apk / 1.0 running in null rsrc of package com.google.android.gm
09-15 12:03:07.394  3410  3410 W ResourcesManager: getTopLevelResources: /system/app/GoogleCalendarSyncAdapter/GoogleCalendarSyncAdapter.apk / 1.0 running in null rsrc of package com.google.android.syncadapters.calendar
09-15 12:03:07.394  3410  3410 D ResourcesManager: For user 0 new overlays fetched Null
09-15 12:03:07.404  3410  3410 W ResourcesManager: getTopLevelResources: /system/app/GoogleCalendarSyncAdapter/GoogleCalendarSyncAdapter.apk / 1.0 running in null rsrc of package com.google.android.syncadapters.calendar
09-15 12:03:07.404  3410  3410 W ResourcesManager: getTopLevelResources: /system/app/GoogleContactsSyncAdapter/GoogleContactsSyncAdapter.apk / 1.0 running in null rsrc of package com.google.android.syncadapters.contacts
09-15 12:03:07.404  3410  3536 D ResourcesManager: For user 0 new overlays fetched Null
09-15 12:03:07.404  3410  3410 D ResourcesManager: For user 0 new overlays fetched Null
09-15 12:03:07.404  3410  3410 W ResourcesManager: getTopLevelResources: /system/app/GoogleContactsSyncAdapter/GoogleContactsSyncAdapter.apk / 1.0 running in null rsrc of package com.google.android.syncadapters.contacts
09-15 12:03:07.404  3410  3410 W ResourcesManager: getTopLevelResources: /system/app/Music2/Music2.apk / 1.0 running in null rsrc of package com.google.android.music
09-15 12:03:07.404  3410  3536 W ResourcesManager: getTopLevelResources: /system/app/Music2/Music2.apk / 1.0 running in null rsrc of package com.google.android.music
09-15 12:03:07.404  3410  3410 W ResourcesManager: getTopLevelResources: /system/app/Music2/Music2.apk / 1.0 running in null rsrc of package com.google.android.music
09-15 12:03:07.404  3410  3410 W ResourcesManager: getTopLevelResources: /system/app/OneDrive_Samsung_v2/OneDrive_Samsung_v2.apk / 1.0 running in null rsrc of package com.microsoft.skydrive
09-15 12:03:07.404  3410  3572 D ActivityManager: mDVFSHelper.release()
09-15 12:03:07.404  3410  3572 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{138251a u0 com.sec.android.app.launcher/.activities.LauncherActivity t72} time:211567
09-15 12:03:07.404  3410  3410 W ResourcesManager: getTopLevelResources: /system/app/OneDrive_Samsung_v2/OneDrive_Samsung_v2.apk / 1.0 running in null rsrc of package com.microsoft.skydrive
09-15 12:03:07.404  3410  3410 W ResourcesManager: getTopLevelResources: /system/app/OneNote/OneNote.apk / 1.0 running in null rsrc of package com.microsoft.office.onenote
09-15 12:03:07.404  3410  3907 W System.err: remove failed: EROFS (Read-only file system) : /data/system/recent_tasks/75_task.xml
09-15 12:03:07.404  3410  3410 W ResourcesManager: getTopLevelResources: /system/app/OneNote/OneNote.apk / 1.0 running in null rsrc of package com.microsoft.office.onenote
09-15 12:03:07.404  3410  3907 W System.err: remove failed: EROFS (Read-only file system) : /data/system/recent_images/75_task_thumbnail.png
09-15 12:03:07.404  3410  3410 W ResourcesManager: getTopLevelResources: /system/app/SBrowser_4_LATEST/SBrowser_4_LATEST.apk / 1.0 running in null rsrc of package com.sec.android.app.sbrowser
09-15 12:03:07.404  3410  3572 W ResourcesManager: getTopLevelResources: /system/priv-app/InputDevices/InputDevices.apk / 1.0 running in null rsrc of package com.android.inputdevices
09-15 12:03:07.404  3410  3410 W ResourcesManager: getTopLevelResources: /system/app/SBrowser_4_LATEST/SBrowser_4_LATEST.apk / 1.0 running in null rsrc of package com.sec.android.app.sbrowser
09-15 12:03:07.404  3410  3410 W ResourcesManager: getTopLevelResources: /system/app/Videos/Videos.apk / 1.0 running in null rsrc of package com.google.android.videos
09-15 12:03:07.414  3410  3572 D ResourcesManager: For user 0 new overlays fetched Null
09-15 12:03:07.414  3410  3410 D ResourcesManager: For user 0 new overlays fetched Null
09-15 12:03:07.414  3410  3410 W ResourcesManager: getTopLevelResources: /system/app/Videos/Videos.apk / 1.0 running in null rsrc of package com.google.android.videos
09-15 12:03:07.414  4287  4287 D CarrierServiceBindHelper: Receive action: android.intent.action.PACKAGE_REMOVED
09-15 12:03:07.414  3410  3572 W ResourcesManager: getTopLevelResources: /system/priv-app/InputDevices/InputDevices.apk / 1.0 running in null rsrc of package com.android.inputdevices
09-15 12:03:07.414  3410  3410 V AlarmManager: Remove alarm for next reason : android.intent.action.PACKAGE_REMOVED : package: com.test.thalitest
09-15 12:03:07.414  3410  3410 I HarmonyEASService: onReceive : android.intent.action.PACKAGE_REMOVED for 0
09-15 12:03:07.414  3410  3831 I InputReader: Reconfiguring input devices.  changes=0x00000010
09-15 12:03:07.414  3410  3536 W ResourcesManager: getTopLevelResources: /system/app/SecMemo3/SecMemo3.apk / 1.0 running in null rsrc of package com.samsung.android.app.memo
09-15 12:03:07.414  3410  3410 D UniversalCredentialManagerService: inside mPkgReciever onReceive : android.intent.action.PACKAGE_REMOVED
09-15 12:03:07.414  3410  3410 D UniversalCredentialManagerService: ACTION_PACKAGE_REMOVED is called....
09-15 12:03:07.414  3410  3410 D KnoxMUMContainerPolicy: mPackageReceiver : action - android.intent.action.PACKAGE_REMOVED
09-15 12:03:07.414  3410  3410 I OTPFW   : PackageRemovalReceiver::onReceive Enter
09-15 12:03:07.414  3410  3410 D OTPFW   : PackageRemovalReceiver::onReceive deleting token for Pkg = com.test.thalitest uid = 10177 container id = 0
09-15 12:03:07.414  3410  3410 I OTPFW   : ProvisionData::getAllEntries Enter
09-15 12:03:07.424  3410  3536 D ResourcesManager: For user 0 new overlays fetched Null
09-15 12:03:07.424  3410  3410 E OTPFW   : ProvisionData::getAllEntries Table is empty
09-15 12:03:07.424  3410  3410 E SDAgentPackageStateReceiver: Not going to handle 'com.test.thalitest'!
09-15 12:03:07.424  3410  3536 W ResourcesManager: getTopLevelResources: /system/app/SecMemo3/SecMemo3.apk / 1.0 running in null rsrc of package com.samsung.android.app.memo

```
