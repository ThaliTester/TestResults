#### Test 83268893e6b65d6_thali03_samsung-SM-A500FU Logs


```
--------- beginning of main
09-02 15:25:45.950  5404  5404 D FactoryTest: Not factory mode
09-02 15:25:45.950  5404  5404 D FactoryTest: Not factory mode. isFactoryMode() returend false
--------- beginning of system
09-02 15:25:45.950  5404  5404 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startActivity:1595 android.content.ContextWrapper.startActivity:337 android.content.ContextWrapper.startActivity:337 com.samsung.android.MtpApplication.MtpReceiver$3.handleMessage:708 android.os.Handler.dispatchMessage:102 
09-02 15:25:45.950  5404  5404 D MTPRx   : DRIVER_TIME_OUT 60s lapsed
09-02 15:25:45.950  5404  5404 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startActivity:1607 android.app.ContextImpl.startActivity:1596 android.content.ContextWrapper.startActivity:337 android.content.ContextWrapper.startActivity:337 com.samsung.android.MtpApplication.MtpReceiver$3.handleMessage:708 
09-02 15:25:45.950  5404  5404 D MTPRx   : still no open session command from host, so toast
09-02 15:25:45.950  5404  5404 I Timeline: Timeline: Activity_launch_request id:com.android.settings time:114727
09-02 15:25:45.950  1019  1322 E PersonaManagerService: inState():  stateMachine is null !!
09-02 15:25:45.950  1019  1322 I PersonaManagerService: PersonaId don't exist
09-02 15:25:45.950  1019  1322 I ActivityManager: do not start freezing screen for locked container getKeyguardshowstate = false
09-02 15:25:45.960  1019  1322 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.android.settings
09-02 15:25:45.960  1019  1322 W ActivityManager: userId = 0, bbcId = -10000
09-02 15:25:45.960  1019  1322 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-02 15:25:45.960  1019  1322 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.android.MtpApplication, destAppInfo.processName = com.android.settings
09-02 15:25:45.960  1019  1322 W ActivityManager: mDVFSHelper.acquire()
09-02 15:25:45.970  1019  1019 V ActivityManager: Display changed displayId=0
09-02 15:25:45.980  1019  1322 D PersonaManager: isKioskContainerExistOnDevice
09-02 15:25:45.980  1019  1322 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.wssyncmldm
09-02 15:25:45.980  1019  1322 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.android.settings
09-02 15:25:45.980  1019  1322 D InputDispatcher: Focused application set to: xxxx
09-02 15:25:45.990  1019  1322 D InputDispatcher: Focus left window: 3151
09-02 15:25:45.990  5404  5404 E MTPRx   : started activity for popup
09-02 15:25:45.990  1019  1051 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
09-02 15:25:45.990  1019  1051 D PointerIcon: setMouseCustomIcon IconType is same.101
09-02 15:25:46.020  5404  5404 W ResourcesManager: Asset path '/system/framework/sec_platform_library.jar' does not exist or contains no resources.
09-02 15:25:46.020  5404  5404 W ResourcesManager: Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
09-02 15:25:46.020  5404  5404 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
09-02 15:25:46.020  5404  5404 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
09-02 15:25:46.020  5404  5404 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
09-02 15:25:46.020  5404  5404 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
09-02 15:25:46.040  5404  5404 E SettingsReceiverActivity: PREF_DONT_ASK_AGAIN : true
09-02 15:25:46.040  1019  2952 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.android.settings
09-02 15:25:46.040  1019  2952 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.wssyncmldm
09-02 15:25:46.040  1019  2952 D InputDispatcher: Focused application set to: xxxx
09-02 15:25:46.040  1019  2952 D InputDispatcher: Focus entered window: 3151
09-02 15:25:46.040  1019  1051 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
09-02 15:25:46.040  1019  1051 D PointerIcon: setMouseCustomIcon IconType is same.101
09-02 15:25:46.040  1019  3109 D InputMethodManagerService: windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
09-02 15:25:46.040  1019  3109 W InputMethodManagerService: Window already focused, ignoring focus gain of: com.android.internal.view.IInputMethodClient$Stub$Proxy@2a3ead0c attribute=android.view.inputmethod.EditorInfo@38b18655, token = android.os.BinderProxy@3c063fce
09-02 15:25:46.050  1954  1954 D SamsungIME: onStartInput: No inputType, No imeOption, isInputViewShown = false, isExtractViewShown = false, isShowInputRequested = false, isConfigChanged = false
09-02 15:25:46.080  5404  5404 D SettingsReceiverActivity: dev.kiessupport is : TRUE
09-02 15:25:46.090  5404  5404 D PhoneWindow: *FMB* installDecor mIsFloating : true
09-02 15:25:46.090  5404  5404 D PhoneWindow: *FMB* installDecor flags : 8388610
09-02 15:25:46.100  3151  3151 I DBG_DM  : [com.wssyncmldm.ui.XUIInstallConfirmActivity(428/onResume)] 
09-02 15:25:46.110  3151  3151 I DBG_DM  : [com.wssyncmldm.db.file.XDB(5416/IlIlllIlllllIlIllllI)] Get Postpone Count : 6
09-02 15:25:46.120  3151  3151 I DBG_DM  : [com.wssyncmldm.db.file.XDB(5138/lIIIIIIIlllllllIIlll)] Get Priority : 0
09-02 15:25:46.130  3151  3151 I DBG_DM  : [com.wssyncmldm.db.file.XDB(5438/llIIlIIlIllIllIlllII)] Get Postpone Max Count : 0
09-02 15:25:46.130  3151  3151 I DBG_DM  : [com.wssyncmldm.ui.XUIInstallConfirmActivity(438/onResume)] Postpone Count : 6
09-02 15:25:46.130  3151  3151 I DBG_DM  : [com.wssyncmldm.db.file.XDB(5479/llIlIIIIlllIlllllIll)] Download Postpone status : 0
09-02 15:25:46.140  3151  3151 I DBG_DM  : [com.wssyncmldm.XDMService(649/lllIlIlIIIllIIlIllIl)] Idle Screen : true
09-02 15:25:46.150  3151  3151 I DBG_DM  : [com.wssyncmldm.ui.lIlIIlIlIlIllllllIII(330/llIIIIlllllIIllIIllI)] NotificationID : 4 / Notification IndicatorState : 7
09-02 15:25:46.150  3151  3151 I DBG_DM  : [com.wssyncmldm.db.file.XDB(5138/lIIIIIIIlllllllIIlll)] Get Priority : 0
09-02 15:25:46.170  1019  1223 D ApplicationPolicy: isStatusBarNotificationAllowedAsUser: packageName = com.wssyncmldm,userId = 0
09-02 15:25:46.170  1019  1223 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.wssyncmldm
09-02 15:25:46.170  1019  1019 W NotificationService: Pray mode not found android.content.pm.PackageManager$NameNotFoundException: Application package com.sec.android.settings.praymodewidget not found
09-02 15:25:46.170  1182  1182 D StatusBar: ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
09-02 15:25:46.170  3151  3151 I DBG_DM  : [com.wssyncmldm.db.file.XDB(5416/IlIlllIlllllIlIllllI)] Get Postpone Count : 6
09-02 15:25:46.180  1182  1182 D PersonaManager: isKioskContainerExistOnDevice
09-02 15:25:46.180  1182  1182 D PersonaManager: isKioskContainerExistOnDevice
09-02 15:25:46.180  1182  1182 D PanelView: There is/are notification(s) 
09-02 15:25:46.180  1182  1182 D PanelView: kidsfalse mQsExpansionEnabled:true
09-02 15:25:46.180  1182  1182 D PersonaManager: isKioskContainerExistOnDevice
09-02 15:25:46.180  3151  3151 I DBG_DM  : [com.wssyncmldm.db.file.XDB(5058/IIlllIlIIlIllIlllIll)] Get Force status : 0
09-02 15:25:46.180  1182  1182 D PanelView: There is/are notification(s) 
09-02 15:25:46.180  1182  1182 D PanelView: kidsfalse mQsExpansionEnabled:true
09-02 15:25:46.190  3151  3151 I DBG_DM  : [com.wssyncmldm.db.file.XDB(5438/llIIlIIlIllIllIlllII)] Get Postpone Max Count : 0
09-02 15:25:46.190  3151  3151 I DBG_DM  : [com.wssyncmldm.ui.XUIInstallConfirmActivity(532/llIIIIlllllIIllIIllI)] Check Force Install : false
09-02 15:25:46.190  3151  3151 I DBG_DM  : [llIIlIIlIllIllIlllII(329/IllIlIIIIlIIlIIIllIl)] 
09-02 15:25:46.190  3151  3151 I DBG_DM  : [llIIlIIlIllIllIlllII(335/IllIlIIIIlIIlIIIllIl)] InternalEncrypted : [false]
09-02 15:25:46.190  1019  3213 D ActivityManager: post active user change for 0 fullscreen true record.isFloatingActivity() false
09-02 15:25:46.190  1019  3213 D KnoxTimeoutHandler: postActiveUserChange for user 0
09-02 15:25:46.190  1019  3213 I KnoxTimeoutHandler: postActiveUserChange, showWhenLocked: false
09-02 15:25:46.190  1019  1019 D KnoxTimeoutHandler: handleActiveUserChange for user 0
09-02 15:25:46.190  1019  1019 D PersonaManagerService: getPersonasForUser(): returning null!
09-02 15:25:46.200  3151  3151 I DBG_DM  : [com.wssyncmldm.ui.XUIInstallConfirmActivity(420/onPause)] 
09-02 15:25:46.200  3151  3151 V ActivityThread: updateVisibility : ActivityRecord{1b076e55 token=android.os.BinderProxy@d67f290 {com.wssyncmldm/com.wssyncmldm.ui.XUIInstallConfirmActivity}} show : true
09-02 15:25:46.200  3151  3151 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@d67f290 time:114977
09-02 15:25:46.210  1019  1484 D PersonaManager: isKioskContainerExistOnDevice
09-02 15:25:46.250  1182  1182 D PanelView: mClearAll.setVisibility - mIsFullyOpened : false isShade : true mHasNotification : true mIsUpwardFling : false mQsFullyExpanded : true isShadeLocked : false mClearAllVisible : false
09-02 15:25:46.650   338   338 I ServiceManager: Waiting for service AtCmdFwd...
,09-02 15:25:46.920  6202  6202 D AndroidRuntime: 
09-02 15:25:46.920  6202  6202 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
09-02 15:25:46.930  6202  6202 D AndroidRuntime: CheckJNI is OFF
09-02 15:25:46.930  6202  6202 D AndroidRuntime: readGMSProperty: start
09-02 15:25:46.930  6202  6202 D AndroidRuntime: readGMSProperty: already setted!!
09-02 15:25:46.930  6202  6202 D AndroidRuntime: propertySet: couldn't set property (it is from app)
09-02 15:25:46.930  6202  6202 D AndroidRuntime: readGMSProperty: could not set the property(default)!!
09-02 15:25:46.930  6202  6202 D AndroidRuntime: readGMSProperty: end
09-02 15:25:46.930  6202  6202 D AndroidRuntime: addProductProperty: start
09-02 15:25:47.020   288   288 E SMD     : DCD OFF
09-02 15:25:47.070  6202  6202 E AffinityControl: AffinityControl: registerfunction enter
09-02 15:25:47.090  6202  6202 D AndroidRuntime: Calling main entry com.android.commands.am.Am
09-02 15:25:47.100  1019  2952 E PersonaManagerService: inState():  stateMachine is null !!
09-02 15:25:47.100  1019  2952 I PersonaManagerService: PersonaId don't exist
09-02 15:25:47.100  1019  2952 I ActivityManager: do not start freezing screen for locked container getKeyguardshowstate = false
09-02 15:25:47.110  1019  2952 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
09-02 15:25:47.120  1019  2952 W ActivityManager: mDVFSHelper.acquire()
09-02 15:25:47.120  1019  1051 D PhoneWindow: *FMB* installDecor mIsFloating : false
09-02 15:25:47.120  1019  1051 D PhoneWindow: *FMB* installDecor flags : -2122120936
09-02 15:25:47.130  1019  2952 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-02 15:25:47.130  1019  2952 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-02 15:25:47.130  1019  2952 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-02 15:25:47.130  1019  2952 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-02 15:25:47.140  6212  6212 E Zygote  : MountEmulatedStorage()
09-02 15:25:47.140  6212  6212 I libpersona: KNOX_SDCARD checking this for 10155
09-02 15:25:47.140  6212  6212 E Zygote  : v2
09-02 15:25:47.140  6212  6212 I libpersona: KNOX_SDCARD not a persona
09-02 15:25:47.140  1019  2952 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.wssyncmldm
09-02 15:25:47.140  1019  2952 I ActivityManager: Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=6212 uid=10155 gids={50155, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
09-02 15:25:47.140  1019  2952 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
09-02 15:25:47.140  1019  2952 D InputDispatcher: Focused application set to: xxxx
09-02 15:25:47.140  1019  2952 D InputDispatcher: Focus left window: 3151
09-02 15:25:47.140  1019  1051 D PhoneWindow: *FMB* isFloatingMenuEnabled mFloatingMenuBtn : null
09-02 15:25:47.140  1019  1051 D PhoneWindow: *FMB* isFloatingMenuEnabled return false
09-02 15:25:47.140   258   258 I SurfaceFlinger: id=13 createSurf (1x1),1 flag=404, uhalitest
09-02 15:25:47.140  6202  6202 D AndroidRuntime: Shutting down VM
09-02 15:25:47.140  6212  6212 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51
09-02 15:25:47.150  6212  6212 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051
09-02 15:25:47.150  6212  6212 E SELinux : [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
09-02 15:25:47.160  1019  1051 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
09-02 15:25:47.160  1019  1051 D PointerIcon: setMouseCustomIcon IconType is same.101
09-02 15:25:47.160   316   316 I art     : Explicit concurrent mark sweep GC freed 8696(370KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 625us total 24.575ms
09-02 15:25:47.180  6212  6212 D TimaKeyStoreProvider: TimaSignature is unavailable
09-02 15:25:47.180  6212  6212 D ActivityThread: Added TimaKeyStore provider
09-02 15:25:47.180   316   316 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 607us total 17.483ms
09-02 15:25:47.190  1019  1049 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
09-02 15:25:47.200   316   316 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 601us total 16.788ms
09-02 15:25:47.200  1019  1322 D PersonaManager: isKioskContainerExistOnDevice
09-02 15:25:47.240   258   429 I SurfaceFlinger: id=10 Removed YUIInstallC (5/9)
09-02 15:25:47.240  3151  3151 V ActivityThread: updateVisibility : ActivityRecord{1b076e55 token=android.os.BinderProxy@d67f290 {com.wssyncmldm/com.wssyncmldm.ui.XUIInstallConfirmActivity}} show : false
09-02 15:25:47.270  1019  3093 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
09-02 15:25:47.270  1019  3093 D BatteryService: level:94, scale:100, status:2, health:2, present:true, voltage: 4212, temperature: 285, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
09-02 15:25:47.270  1019  3093 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
09-02 15:25:47.270  1019  3093 D BatteryService: stay LED for charging
09-02 15:25:47.270  1019  1019 D BatteryService: Sending ACTION_BATTERY_CHANGED.
09-02 15:25:47.270  1019  1019 I MotionRecognitionService: Plugged
09-02 15:25:47.280  1019  1019 I MotionRecognitionService: mGripSensorEnabled= false
09-02 15:25:47.280  1182  1182 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
09-02 15:25:47.280  1182  1182 D KeyguardUpdateMonitor: handleBatteryUpdate
09-02 15:25:47.280  1422  1422 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
09-02 15:25:47.280  1422  1422 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 94
09-02 15:25:47.290  2636  2636 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
09-02 15:25:47.290  2636  2712 D HeadsetStateMachine: Disconnected process message: 10
09-02 15:25:47.310  1182  1182 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:94 status:2 health:2
09-02 15:25:47.310  1182  1182 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:94 status:2 health:2
09-02 15:25:47.310  1182  1182 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:94 status:2 health:2
09-02 15:25:47.330  6212  6212 I WebViewFactory: Loading com.google.android.webview version 43.0.2357.121 (code 2357121)
09-02 15:25:47.340  6212  6212 I LibraryLoader: Time to load native libraries: 2 ms (timestamps 6112-6114)
09-02 15:25:47.340  6212  6212 I LibraryLoader: Expected native library version number "",actual native library version number ""
09-02 15:25:47.350  6202  6202 W art     : ConditionVariable::~ConditionVariable for GC request condition variable called with 1 waiters.
,09-02 15:25:47.370  6212  6212 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {a523621}
,09-02 15:25:47.380  6212  6212 I LibraryLoader: Expected native library version number "",actual native library version number ""
,09-02 15:25:47.380  6212  6212 I chromium: [INFO:library_loader_hooks.cc(112)] Chromium logging enabled: level = 0, default verbosity = 0
,09-02 15:25:47.410  6212  6212 I BrowserStartupController: Initializing chromium process, singleProcess=true
,09-02 15:25:47.410  6212  6212 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,09-02 15:25:47.410  6212  6212 E SysUtils: ApplicationContext is null in ApplicationStatus
,09-02 15:25:47.430  6212  6212 W chromium: [WARNING:resource_bundle.cc(286)] locale_file_path.empty()
,09-02 15:25:47.430  6212  6212 I chromium: [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=38 off=50556 len=3379
,09-02 15:25:47.430  6212  6212 I chromium: [INFO:aw_browser_main_parts.cc(76)] Loading webviewchromium.pak from, fd:39 off:7638088 len:1165478
,09-02 15:25:47.440  6212  6212 I Adreno-EGL: <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: SKARAJGA_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018__release_ENGG (I856e09677e)
09-02 15:25:47.440  6212  6212 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.02
09-02 15:25:47.440  6212  6212 I Adreno-EGL: Build Date: 04/06/15 Mon
09-02 15:25:47.440  6212  6212 I Adreno-EGL: Local Branch: 
09-02 15:25:47.440  6212  6212 I Adreno-EGL: Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018
09-02 15:25:47.440  6212  6212 I Adreno-EGL: Local Patches: 112c106f3772623daa7b4181c6cf23491044ead1 Revert "Disable ASTC on A405"
09-02 15:25:47.440  6212  6212 I Adreno-EGL:                  58a118cb818fdc906095a49a90977c15f9d3b223 Remove ASTC
,09-02 15:25:47.550  6212  6240 W chromium: [WARNING:data_reduction_proxy_config.cc(318)] SPDY proxy OFF at startup
,09-02 15:25:47.590  6212  6212 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,09-02 15:25:47.610  6212  6212 W AwContents: onDetachedFromWindow called when already detached. Ignoring
,09-02 15:25:47.620  6212  6212 D PhoneWindow: *FMB* installDecor mIsFloating : false
,09-02 15:25:47.620  6212  6212 D PhoneWindow: *FMB* installDecor flags : -2139027200
,09-02 15:25:47.620  6212  6212 D SystemWebViewEngine: CordovaWebView is running on device made by: samsung
,09-02 15:25:47.630  6212  6212 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,09-02 15:25:47.630  6212  6212 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,09-02 15:25:47.650   338   338 I ServiceManager: Waiting for service AtCmdFwd...
,09-02 15:25:47.670  6212  6253 D OpenGLRenderer: Render dirty regions requested: true
,09-02 15:25:47.680  1019  1484 D ActivityManager: post active user change for 0 fullscreen true record.isFloatingActivity() false
,09-02 15:25:47.680  1019  1484 D KnoxTimeoutHandler: postActiveUserChange for user 0
09-02 15:25:47.680  1019  1484 I KnoxTimeoutHandler: postActiveUserChange, showWhenLocked: false
,09-02 15:25:47.680  1019  1019 D KnoxTimeoutHandler: handleActiveUserChange for user 0
09-02 15:25:47.680  1019  1019 D PersonaManagerService: getPersonasForUser(): returning null!
,09-02 15:25:47.690  6212  6212 D PhoneWindow: *FMB* isFloatingMenuEnabled mFloatingMenuBtn : null
,09-02 15:25:47.690  6212  6212 D PhoneWindow: *FMB* isFloatingMenuEnabled return false
,09-02 15:25:47.700   258   258 I SurfaceFlinger: id=14 createSurf (1x1),1 flag=404, NainActivit
,09-02 15:25:47.720  1019  1082 D InputDispatcher: Focus entered window: 6212,
,09-02 15:25:47.720  1019  1051 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
09-02 15:25:47.720  1019  1051 D PointerIcon: setMouseCustomIcon IconType is same.101
,09-02 15:25:47.730  6212  6212 D SRIB_DCS: log_dcs ThreadedRenderer::initialize entered! 
09-02 15:25:47.730  6212  6253 I OpenGLRenderer: Initialized EGL, version 1.4
,09-02 15:25:47.730  6212  6253 D OpenGLRenderer: Get maximum texture size. GL_MAX_TEXTURE_SIZE is 4096,
09-02 15:25:47.730  6212  6253 D OpenGLRenderer: Enabling debug mode 0
,09-02 15:25:47.760  6212  6212 V ActivityThread: updateVisibility : ActivityRecord{385ff5d0 token=android.os.BinderProxy@235b0682 {com.test.thalitest/com.test.thalitest.MainActivity}} show : true
,09-02 15:25:47.780  1019  1319 D InputMethodManagerService: windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,09-02 15:25:47.780  1182  1182 D PanelView: There is/are notification(s) 
,09-02 15:25:47.780  1019  6256 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.android.server.InputMethodManagerService$6.run:2762 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,09-02 15:25:47.790  1019  1051 I ActivityManager: Displayed Component not be shown by security: +577ms (total +1s826ms),
09-02 15:25:47.790  1019  1051 W ActivityManager: mDVFSHelper.release()
09-02 15:25:47.790  1019  1051 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{b45515b u0 com.test.thalitest/.MainActivity t129} time:116567,
,09-02 15:25:47.800   258  1041 I SurfaceFlinger: id=13 Removed uhalitest (7/9)
,09-02 15:25:47.800   258   427 I SurfaceFlinger: id=13 Removed uhalitest (-2/9)
,09-02 15:25:47.800  6212  6212 W IInputConnectionWrapper: showStatusIcon on inactive InputConnection
,09-02 15:25:47.800  6212  6212 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@235b0682 time:116578
,09-02 15:25:47.800  1954  1954 I SamsungIME: getCurrentCandidateView
,09-02 15:25:47.870  6212  6212 W BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 6212
,09-02 15:25:47.900  1954  1954 D SamsungIME: Dismiss ExpandCandiate
,09-02 15:25:47.980  6212  6212 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,09-02 15:25:48.040  1954  1954 I SamsungIME: getDebugLevel  : 0x4f4c
,09-02 15:25:48.070  1954  1954 I SamsungIME: getDebugLevel  : 0x4f4c
,09-02 15:25:48.080  1954  1954 I SamsungIME: KeybaordView init() : load resources
,09-02 15:25:48.090  6212  6258 D jxcore_app_log: JniHelper::setJavaVM(0xb7cf8328), pthread_self() = -1205467368
,09-02 15:25:48.100  6212  6258 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
09-02 15:25:48.100  6212  6258 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
09-02 15:25:48.100  6212  6258 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
09-02 15:25:48.100  6212  6258 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
09-02 15:25:48.100  6212  6258 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
09-02 15:25:48.100  6212  6258 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2847300 added. We now have 1 listener(s)
,09-02 15:25:48.110  6212  6258 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: 7C:F9:0E:37:96:AB
,09-02 15:25:48.110  6212  6258 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "7C:F9:0E:37:96:AB"
,09-02 15:25:48.110  6212  6258 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66,
09-02 15:25:48.110  6212  6258 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,09-02 15:25:48.110  1954  1954 I SamsungIME: getCurrentKeyboard
09-02 15:25:48.110  1954  1954 I SamsungIME: getTextKeyboard
,09-02 15:25:48.120  6212  6258 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
09-02 15:25:48.120  6212  6258 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
09-02 15:25:48.120  6212  6258 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
09-02 15:25:48.120  6212  6258 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: 7C:F9:0E:37:96:AB
09-02 15:25:48.120  6212  6258 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
09-02 15:25:48.120  6212  6258 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
09-02 15:25:48.120  6212  6258 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
09-02 15:25:48.120  6212  6258 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
09-02 15:25:48.120  6212  6258 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
09-02 15:25:48.120  6212  6258 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
09-02 15:25:48.120  6212  6258 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
09-02 15:25:48.120  6212  6258 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
09-02 15:25:48.120  6212  6258 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
09-02 15:25:48.120  6212  6258 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
09-02 15:25:48.120  6212  6258 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1a1d76df added. We now have 1 listener(s)
09-02 15:25:48.120  6212  6258 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-02 15:25:48.120  1019  2755 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,09-02 15:25:48.130  1954  1954 D SamsungIME: [SwiftkeyWrapper] currentLangauge : 1701729619
,09-02 15:25:48.130  6212  6258 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
09-02 15:25:48.130  6212  6258 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
,09-02 15:25:48.130  6212  6258 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
09-02 15:25:48.130  6212  6258 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
09-02 15:25:48.130  6212  6258 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
,09-02 15:25:48.130  6212  6258 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-02 15:25:48.140  6212  6258 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 7C:F9:0E:37:96:AB
,09-02 15:25:48.150  6212  6258 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (SUPPORTED) in persistent storage
,09-02 15:25:48.150  6212  6258 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-02 15:25:48.150  6212  6258 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-02 15:25:48.150  6212  6258 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-02 15:25:48.150  6212  6258 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-02 15:25:48.150  6212  6258 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-02 15:25:48.150  6212  6258 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-02 15:25:48.150  6212  6258 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-02 15:25:48.150  6212  6258 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-02 15:25:48.150  6212  6258 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
09-02 15:25:48.150  6212  6258 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-02 15:25:48.150  6212  6258 I io.jxcore.node.LifeCycleMonitor: start: OK
,09-02 15:25:48.150  6212  6212 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-02 15:25:48.150  6212  6212 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-02 15:25:48.180  6212  6212 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,09-02 15:25:48.640  1954  6262 D SamsungIME: [SwiftkeyWrapper] currentLangauge : 1701729619
,09-02 15:25:48.650   338   338 I ServiceManager: Waiting for service AtCmdFwd...
,09-02 15:25:48.680  6212  6266 W jxcore-log: Initializing JXcore engine
09-02 15:25:48.680  6212  6266 W jxcore-log: JXcore engine is ready
,09-02 15:25:48.740  1875  1875 E audit   : type=1400 msg=audit(1472822748.740:205): avc:  denied  { ioctl } for  pid=6266 comm="Thread-1073" path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=2061 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
09-02 15:25:48.740  1875  1875 E audit   :  SEPF_SM-A500FU_5.0.2-1_0051
09-02 15:25:48.740  1875  1875 E audit   : type=1300 msg=audit(1472822748.740:205): arch=40000028 syscall=54 per=800000 success=no exit=-13 a0=7 a1=5451 a2=3 a3=9e2c08f8 items=0 ppid=316 ppcomm=main pid=6266 auid=4294967295 uid=10155 gid=10155 euid=10155 suid=10155 fsuid=10155 egid=10155 sgid=10155 fsgid=10155 ses=4294967295 tty=(none) comm="Thread-1073" exe="/system/bin/app_process32" subj=u:r:untrusted_app:s0 key=(null)
09-02 15:25:48.740  1875  1875 E audit   : type=1320 msg=audit(1472822748.740:205): 
,09-02 15:25:48.750  6212  6266 W jxcore-log: Starting JXcore engine
,09-02 15:25:48.860  6212  6266 W jxcore-log: Platform android
09-02 15:25:48.860  6212  6266 W jxcore-log: 
09-02 15:25:48.860  6212  6266 W jxcore-log: Process ARCH arm
09-02 15:25:48.860  6212  6266 W jxcore-log: 
,09-02 15:25:49.060  6212  6266 I jxcore-log: JXcore Cordova bridge is ready!
09-02 15:25:49.060  6212  6266 I jxcore-log: 
,09-02 15:25:49.070  6212  6266 W jxcore-log: JXcore engine is started
,09-02 15:25:49.070  6212  6258 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,09-02 15:25:49.070  6212  6212 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,09-02 15:25:49.650   338   338 I ServiceManager: Waiting for service AtCmdFwd...
,09-02 15:25:49.950  1019  2713 D SSRM:n  : SIOP:: AP = 330
,09-02 15:25:50.020   288   288 E SMD     : DCD OFF,
,09-02 15:25:50.120  1019  1165 D TaskPersister: removeObsoleteFile: deleting file=127_task.xml,
,09-02 15:25:50.650   338   338 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 1,
,09-02 15:25:51.230  1019  1100 V AlarmManager: waitForAlarm result :4,
,09-02 15:25:51.230  1019  1100 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.drive.api.ApiService; callingUser = 0; userId(target) = 0
,09-02 15:25:51.260  1883  1883 E NetworkScheduler.ATC: Provided calling package not found: com.google.android.apps.photos
,09-02 15:25:51.290  1019  1031 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,09-02 15:25:51.290  1019  1031 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.libraries.social.autobackup.AutoBackupGcmTaskService; callingUser = 0; userId(target) = 0
,09-02 15:25:51.290  1019  1031 W ActivityManager: userId = 0, bbcId = -10000
,09-02 15:25:51.290  1019  1031 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-02 15:25:51.290  1019  1031 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-02 15:25:51.350  3800  3800 D ConnectivityManager: CallingUid : 10012, CallingPid : 3800
,09-02 15:25:51.350  1019  3093 D ConnectivityService: listenForNetwork for NetworkRequest [ id=4, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,09-02 15:25:51.360  1019  1138 D ConnectivityService: handleRegisterNetworkRequest checking NetworkAgentInfo [WIFI () - 502]
,09-02 15:25:51.360  1019  1138 D ConnectivityService: apparently satisfied.  currentScore=60
,09-02 15:25:51.360  1019  1138 D ConnectivityService: handleRegisterNetworkRequest checking NetworkAgentInfo [WIFI_P2P () - 501]
,09-02 15:25:51.360  3800  6269 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
,09-02 15:25:51.420  3800  6270 W DriveInitializer: Background init thread started
,09-02 15:25:51.440   257   526 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.gms/files/
09-02 15:25:51.440   257   526 W Vold    : Returning OperationFailed - no handler for errno 0
,09-02 15:25:51.440  3800  6270 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.gms/files
,09-02 15:25:51.490  1019  2905 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,09-02 15:25:51.490  1019  2905 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.ads.jams.NegotiationService; callingUser = 0; userId(target) = 0
,09-02 15:25:51.500  1019  2905 W ActivityManager: userId = 0, bbcId = -10000
09-02 15:25:51.500  1019  2905 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,09-02 15:25:51.500  1019  2905 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-02 15:25:51.530  1019  2903 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.google.android.gms, action: android.accounts.AccountAuthenticator
09-02 15:25:51.530  1019  2903 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.account.authenticator.GoogleAccountAuthenticatorService; callingUser = 0; userId(target) = 0
,09-02 15:25:51.530  1019  1319 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,09-02 15:25:51.530  1019  1319 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.gass.chimera.SchedulePeriodicTasksService; callingUser = 0; userId(target) = 0
,09-02 15:25:51.540  1019  1319 W ActivityManager: userId = 0, bbcId = -10000
09-02 15:25:51.540  1019  1319 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,09-02 15:25:51.540  1019  1319 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-02 15:25:51.560  3800  6270 W DriveInitializer: Background init thread ended
,09-02 15:25:51.560  3800  6277 D SchedPeriodicTask: Will NOT schedule AdAttestation signal task because it's disabled.
09-02 15:25:51.560  3800  6277 D SchedPeriodicTask: Scheduled AdAttestation task.
,09-02 15:25:51.590  1883  1883 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,09-02 15:25:51.620  1019  1046 W ActivityManager: userId = 0, bbcId = -10000
09-02 15:25:51.620  1019  1046 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-02 15:25:51.620  1019  1046 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-02 15:25:51.720  1019  1032 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,09-02 15:25:51.720  1019  1032 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.account.be.legacy.AuthCronService; callingUser = 0; userId(target) = 0
,09-02 15:25:51.720  1019  1032 W ActivityManager: userId = 0, bbcId = -10000
09-02 15:25:51.720  1019  1032 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-02 15:25:51.720  1019  1032 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-02 15:25:51.760  1019  3105 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,09-02 15:25:51.760  1019  3105 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.udc.service.UdcContextInitService; callingUser = 0; userId(target) = 0
,09-02 15:25:51.760  1019  3105 W ActivityManager: userId = 0, bbcId = -10000
,09-02 15:25:51.760  1019  3105 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-02 15:25:51.760  1019  3105 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-02 15:25:51.810  1019  3109 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,09-02 15:25:51.810  1019  3109 W ActivityManager: userId = 0, bbcId = -10000
,09-02 15:25:51.810  1019  3109 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,09-02 15:25:51.810  1019  3109 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-02 15:25:51.830  1019  1223 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,09-02 15:25:51.830  1019  1223 W ActivityManager: userId = 0, bbcId = -10000
,09-02 15:25:51.830  1019  1223 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-02 15:25:51.830  1019  1223 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-02 15:25:51.890  1019  3105 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,09-02 15:25:51.890  1019  3105 W ActivityManager: userId = 0, bbcId = -10000
,09-02 15:25:51.890  1019  3105 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-02 15:25:51.890  1019  3105 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-02 15:25:51.890  1019  3105 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-02 15:25:51.890  1019  3105 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-02 15:25:51.890  1019  3105 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-02 15:25:51.890  1019  3105 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-02 15:25:51.910  6283  6283 E Zygote  : MountEmulatedStorage(),
09-02 15:25:51.910  6283  6283 E Zygote  : v2
09-02 15:25:51.910  6283  6283 I libpersona: KNOX_SDCARD checking this for 10012
09-02 15:25:51.910  6283  6283 I libpersona: KNOX_SDCARD not a persona
,09-02 15:25:51.910  6283  6283 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51,
,09-02 15:25:51.910  6283  6283 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051,
09-02 15:25:51.910  1019  3105 I ActivityManager: Start proc com.google.android.gms.unstable for service com.google.android.gms/.droidguard.DroidGuardService: pid=6283 uid=10012 gids={50012, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 3007} abi=armeabi-v7a
09-02 15:25:51.910  6283  6283 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL,
,09-02 15:25:51.940  6283  6283 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-02 15:25:51.940  6283  6283 D ActivityThread: Added TimaKeyStore provider
,09-02 15:25:51.960  6283  6283 W ResourcesManager: Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,09-02 15:25:51.960  6283  6283 W ResourcesManager: Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,09-02 15:25:52.000  6283  6283 I MultiDex: VM with version 2.1.0 has multidex support
,09-02 15:25:52.000  6283  6283 I MultiDex: install
09-02 15:25:52.000  6283  6283 I MultiDex: VM has multidex support, MultiDex support library is disabled.
,09-02 15:25:52.030  6283  6283 V JNIHelp : Registering com/google/android/gms/org/conscrypt/NativeCrypto's 255 native methods...
,09-02 15:25:52.090  6283  6283 W ActivityThread: ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,09-02 15:25:52.090  6283  6283 W System  : Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@12e7ede2: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
,09-02 15:25:52.100  6283  6283 I ProviderInstaller: Installed default security provider GmsCore_OpenSSL
,09-02 15:25:52.110  6283  6283 D ChimeraCfgMgr: Reading stored module config
,09-02 15:25:52.150  1019  2903 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,09-02 15:25:52.150  1019  2903 W ActivityManager: userId = 0, bbcId = -10000
09-02 15:25:52.150  1019  2903 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-02 15:25:52.150  1019  2903 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-02 15:25:52.160  1019  1484 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.contextmanager.service.ContextManagerService; callingUser = 0; userId(target) = 0
,09-02 15:25:52.200  6283  6297 I art     : Background sticky concurrent mark sweep GC freed 20828(1037KB) AllocSpace objects, 3(133KB) LOS objects, 5% free, 10MB/11MB, paused 5.484ms total 58.328ms
,09-02 15:25:52.220  6283  6283 I art     : Rejecting re-init on previously-failed class java.lang.Class<irq>
,09-02 15:25:52.220  6283  6283 I art     : Rejecting re-init on previously-failed class java.lang.Class<irq>
,09-02 15:25:52.230  6283  6300 D NativeLibraryUtils: Install completed successfully. count=12 extracted=0
,09-02 15:25:52.270  1883  2117 I art     : Explicit concurrent mark sweep GC freed 70523(3MB) AllocSpace objects, 15(480KB) LOS objects, 40% free, 14MB/23MB, paused 1.466ms total 110.417ms
,09-02 15:25:52.290  1019  1322 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,09-02 15:25:52.290  1019  1322 W ActivityManager: userId = 0, bbcId = -10000
09-02 15:25:52.290  1019  1322 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-02 15:25:52.290  1019  1322 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-02 15:25:52.320  1883  1883 E ctxmgr  : [FencePendingIntentCache]Expected to find a PendingIntent for pendingIntentKey=e9880adf-55ba-4b05-a3e7-3b4b34239615
,09-02 15:25:52.340  1019  2905 D ActivityManager: bindService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms, action: null
,09-02 15:25:52.340  1019  2905 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GetToken; callingUser = 0; userId(target) = 0
,09-02 15:25:52.340  1019  2905 W ActivityManager: userId = 0, bbcId = -10000
09-02 15:25:52.340  1019  2905 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-02 15:25:52.340  1019  2905 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-02 15:25:52.360  1883  1883 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,09-02 15:25:52.370  1883  1883 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,09-02 15:25:52.380   283   700 D WVCdm   : Instantiating CDM.
,09-02 15:25:52.380   283   680 I WVCdm   : CdmEngine::OpenSession
,09-02 15:25:52.380   283   680 I WVCdm   : Level3 Library Sep 25 2014 17:10:03
,09-02 15:25:52.390  1019  1082 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,09-02 15:25:52.400  1019  1082 W ActivityManager: userId = 0, bbcId = -10000
,09-02 15:25:52.400  1019  1082 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023,
09-02 15:25:52.400  1019  1082 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-02 15:25:52.400   283   680 W WVCdm   : Could not read /data/mediadrm/IDM1013/ay64.dat2: No such file or directory
,09-02 15:25:52.430   283   680 D DrmWidevineDash: OEMCrypto_Initialize: starts! g_qsee_apps_version = 0x15
,09-02 15:25:52.430   283   680 D DrmWidevineDash: Service_Initialize: starts!
09-02 15:25:52.430   283   680 D QSEECOMAPI: : QSEECom_get_handle sb_length = 0x19000
09-02 15:25:52.430   283   680 D QSEECOMAPI: : App is not loaded in QSEE
,09-02 15:25:52.430   283   680 E QSEECOMAPI: : Error::Cannot open the file /vendor/firmware/widevine.mdt
09-02 15:25:52.430   283   680 E QSEECOMAPI: : Error::Loading image failed with ret = -1
09-02 15:25:52.430   283   680 D QSEECOMAPI: : QSEECom_get_handle sb_length = 0x19000
09-02 15:25:52.430   283   680 D QSEECOMAPI: : App is not loaded in QSEE
,09-02 15:25:52.430   283   680 E QSEECOMAPI: : Error::Cannot open the file /system/etc/firmware/widevine.mdt
09-02 15:25:52.430   283   680 E QSEECOMAPI: : Error::Loading image failed with ret = -1
09-02 15:25:52.430   283   680 D QSEECOMAPI: : QSEECom_get_handle sb_length = 0x19000
09-02 15:25:52.430   283   680 D QSEECOMAPI: : App is not loaded in QSEE
,09-02 15:25:52.450   283   680 D QSEECOMAPI: : Loaded image: APP id = 11
,09-02 15:25:52.450   283   680 D DrmWidevineDash: Service_Initialize: ends! returns 0
,09-02 15:25:52.450   283   680 D QSAPPSVER: qsapps_get_capabilities: Capability from secure side: 0x0
09-02 15:25:52.450   283   680 D QSAPPSVER: qsapps_get_capabilities: returns 0
09-02 15:25:52.450   283   680 D DrmWidevineDash: OEMCrypto_Initialize sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb16fc000
09-02 15:25:52.450   283   680 E DrmWidevineDash: sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb16fc000
09-02 15:25:52.450   283   680 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
,09-02 15:25:52.450   421   438 D DrmLibTime: got the req here! ret=0
09-02 15:25:52.460   421   438 D DrmLibTime: command id, time_cmd_id = 770
09-02 15:25:52.460   421   438 D DrmLibTime: time_getutcsec starts!
09-02 15:25:52.460   421   438 D DrmLibTime: QSEE Time Listener: time_getutcsec
09-02 15:25:52.460   421   438 D DrmLibTime: QSEE Time Listener: get_utc_seconds
09-02 15:25:52.460   421   438 D DrmLibTime: QSEE Time Listener: time_get_modem_time
09-02 15:25:52.460   421   438 D DrmLibTime: QSEE Time Listener: Checking if ATS_MODEM is set or not.
,09-02 15:25:52.460   421   438 D QC-time-services: Lib:time_genoff_operation: pargs->base = 13,
09-02 15:25:52.460   421   438 D QC-time-services: Lib:time_genoff_operation: pargs->operation = 2
09-02 15:25:52.460   421   438 D QC-time-services: Lib:time_genoff_operation: pargs->ts_val = 0
09-02 15:25:52.460   421   438 D QC-time-services: Lib:time_genoff_operation: Send to server  passed!!
,09-02 15:25:52.460   340   551 D QC-time-services: Daemon: Connection accepted:time_genoff
,09-02 15:25:52.460   340  6306 D QC-time-services: Daemon:Received base = 13, unit = 1, operation = 2,value = 0
09-02 15:25:52.460   340  6306 D QC-time-services: Daemon:genoff_opr: Base = 13, val = 0, operation = 2
,09-02 15:25:52.460   340  6306 D QC-time-services: offset is: 0 for base: 0
,09-02 15:25:52.460   421   438 E QC-time-services: Receive Passed == base = 13, unit = 1, operation = 2, result = 0
09-02 15:25:52.460   421   438 D DrmLibTime: QSEE Time Listener: ATS_MODEM is not set. Fallback to Android system time.
09-02 15:25:52.460   421   438 D DrmLibTime: QSEE Time Listener: Retrieved Android system time: 1472822752
,09-02 15:25:52.460   421   438 D DrmLibTime: time_getutcsec returns 0, sec = 1472822752; nsec = 0
09-02 15:25:52.460   421   438 D DrmLibTime: time_getutcsec finished! 
09-02 15:25:52.460   421   438 D DrmLibTime: iotcl_continue_command finished! and return 0 
09-02 15:25:52.460   421   438 D DrmLibTime: before calling ioctl to read the next time_cmd
09-02 15:25:52.460   283   680 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
09-02 15:25:52.460   340   551 E QC-time-services: Daemon: Time-services: Waiting to acceptconnection
,09-02 15:25:52.500   283   680 D DrmWidevineDash: OEMCrypto_Initialize: ends! returns 0
09-02 15:25:52.500   283   680 D DrmWidevineDash: OEMCrypto_APIVersion: starts!
09-02 15:25:52.500   283   680 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
,09-02 15:25:52.500   283   680 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
09-02 15:25:52.500   283   680 D DrmWidevineDash: hlos api version =  9
09-02 15:25:52.500   283   680 D DrmWidevineDash: tz api version =  9
09-02 15:25:52.500   283   680 D DrmWidevineDash: OEMCrypto_APIVersion: ends! returns version 9
09-02 15:25:52.500   283   680 D DrmWidevineDash: OEMCrypto_IsKeyboxValid: starts!
09-02 15:25:52.500   283   680 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
,09-02 15:25:52.510  1648  1676 I art     : Explicit concurrent mark sweep GC freed 1375(47KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 7MB/12MB, paused 1.201ms total 28.344ms
,09-02 15:25:52.550   283   680 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
,09-02 15:25:52.550   283   680 D DrmWidevineDash: OEMCrypto_IsKeyboxValid: ends! returns 0
,09-02 15:25:52.550   283   680 D WVCdm   : OEMCrypto_Initialize Level 1 success. I will use level 1.
09-02 15:25:52.550   283   680 D DrmWidevineDash: OEMCrypto_OpenSession: starts! SID=0xb1950960
,09-02 15:25:52.550   283   680 D DrmWidevineDash: OEMCrypto_OpenSession Session ID = 0
09-02 15:25:52.550   283   680 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
,09-02 15:25:52.550   283   680 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
09-02 15:25:52.550  6283  6293 I System.out: (HTTPLog)-Static: SBServiceAPI: getService class android.os.ServiceManager
09-02 15:25:52.550  6283  6293 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
09-02 15:25:52.550  6283  6293 I System.out: (HTTPLog)-Static: isShipBuild true
09-02 15:25:52.550  6283  6293 I System.out: (HTTPLog)-Thread-1055-520269767: SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
09-02 15:25:52.550  6283  6293 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,09-02 15:25:52.550   283   680 D DrmWidevineDash: OEMCrypto_OpenSession SID = 1
09-02 15:25:52.550   283   680 D DrmWidevineDash: OEMCrypto_OpenSession: ends! returns 0
09-02 15:25:52.550   283   680 D DrmWidevineDash: OEMCrypto_GetRandom: starts! randomData=0xb8914a48, dataLength=8
,09-02 15:25:52.550   283   680 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
,09-02 15:25:52.560   278   994 D EnterpriseController: uids 10012
09-02 15:25:52.560   278   994 D EnterpriseController: mIsMarkChainAdded is 18 mIsBlockChainAdded is 252 netId is 0
09-02 15:25:52.560   278   994 D Netd    : getNetworkForDns: using netid 502 for uid 10012
,09-02 15:25:52.560   283   680 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
,09-02 15:25:52.560   283   680 D DrmWidevineDash: OEMCrypto_GetRandom: ends! returns 0
,09-02 15:25:52.560   283   680 D DrmWidevineDash: OEMCrypto_LoadDeviceRSAKey: starts! SID=1, wrapped_rsa_key=0xb8921308, wrapped_rsa_key_length=1280
09-02 15:25:52.560   283   680 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
,09-02 15:25:52.560   283   680 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
09-02 15:25:52.560   283   680 D DrmWidevineDash: OEMCrypto_LoadDeviceRSAKey: ends! returns 0
09-02 15:25:52.560   283   680 I WVCdm   : CdmEngine::QueryKeyControlInfo
,09-02 15:25:52.570   283  1017 W WVCdm   : BufferReader::Read<T> : Failure during parse: Not enough bytes (4)
09-02 15:25:52.570   283  1017 W WVCdm   : CdmEngine::ExtractWidevinePssh: Unable to read PSSH atom size
09-02 15:25:52.570   283  1017 I WVCdm   : CdmEngine::GenerateKeyRequest
09-02 15:25:52.570   283  1017 D DrmWidevineDash: OEMCrypto_GetDeviceID: starts! deviceID=0xb891fb50, idLength=0xb126f730
09-02 15:25:52.570   283  1017 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
,09-02 15:25:52.580   283  1017 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
09-02 15:25:52.580   283  1017 D DrmWidevineDash: OEMCrypto_GetDeviceID: ends! returns 0
09-02 15:25:52.580   283  1017 D DrmWidevineDash: OEMCrypto_SupportsUsageTable: starts!
09-02 15:25:52.580   283  1017 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
,09-02 15:25:52.580   283  1017 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
09-02 15:25:52.580   283  1017 D DrmWidevineDash: OEMCrypto_SupportsUsageTable: is_supported = 1
09-02 15:25:52.580   283  1017 D DrmWidevineDash: OEMCrypto_SupportsUsageTable: wv_app_version = 24
09-02 15:25:52.580   283  1017 D DrmWidevineDash: OEMCrypto_SupportsUsageTable: ends! returns 0
09-02 15:25:52.580   283  1017 D DrmWidevineDash: OEMCrypto_GetHDCPCapability: starts!, current = 0xb126f746, maximum = 0xb126f747
09-02 15:25:52.580   283  1017 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
09-02 15:25:52.580   283  1017 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
09-02 15:25:52.580   283  1017 D DrmWidevineDash: OEMCrypto_GetHDCPCapability: ends! returns 0
09-02 15:25:52.580   283  1017 D DrmWidevineDash: OEMCrypto_APIVersion: starts!
09-02 15:25:52.580   283  1017 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
09-02 15:25:52.580   283  1017 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
09-02 15:25:52.580   283  1017 D DrmWidevineDash: hlos api version =  9
09-02 15:25:52.580   283  1017 D DrmWidevineDash: tz api version =  9
09-02 15:25:52.580   283  1017 D DrmWidevineDash: OEMCrypto_APIVersion: ends! returns version 9
09-02 15:25:52.580   283  1017 D DrmWidevineDash: OEMCrypto_GenerateNonce: starts! SID=1, nonce=0xb126f7b4
09-02 15:25:52.580   283  1017 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
09-02 15:25:52.580   283  1017 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0,
09-02 15:25:52.580   283  1017 D DrmWidevineDash: OEMCrypto_GenerateNonce: ends! returns 0
09-02 15:25:52.580   283  1017 D WVCdm   : PrepareKeyRequest: nonce=1104999755
09-02 15:25:52.580   283  1017 D DrmWidevineDash: OEMCrypto_GenerateRSASignature starts! SID=1, message=0xb891a8e8
09-02 15:25:52.580   283  1017 D DrmWidevineDash: message_length=1599, signature=0xb89212f0, signature_length=0xb126f714
09-02 15:25:52.580   283  1017 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
,09-02 15:25:52.610  6283  6293 I System.out: KnoxVpnUidStorageknoxVpnSupported API value returned is false
,09-02 15:25:52.610  6283  6293 I qtaguid : Tagging socket 30 with tag 1000180300000000{268441603,0} for uid -1, pid: 6283, getuid(): 10012
,09-02 15:25:52.650  1883  2110 W GCoreFlp: No location to return for getLastLocation()
,09-02 15:25:52.680  1019  2905 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,09-02 15:25:52.680  1019  2905 W ActivityManager: userId = 0, bbcId = -10000
,09-02 15:25:52.690  1019  2905 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-02 15:25:52.690  1019  2905 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-02 15:25:52.690  1019  1031 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,09-02 15:25:52.690  1019  1031 W ActivityManager: userId = 0, bbcId = -10000
,09-02 15:25:52.690  1019  1031 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-02 15:25:52.690  1019  1031 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-02 15:25:52.690  1019  1319 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,09-02 15:25:52.690  1019  1319 W ActivityManager: userId = 0, bbcId = -10000
,09-02 15:25:52.700  1019  1319 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-02 15:25:52.700  1019  1319 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-02 15:25:52.700  1883  2114 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
,09-02 15:25:52.700  1883  2130 E ctxmgr  : [FenceManager]Could not remove all geofences. status=Status{statusCode=unknown status code: 1000, resolution=null}
,09-02 15:25:52.720  3800  6279 D UdcContextInitService: registered all accounts: true
,09-02 15:25:52.750   283  1017 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
09-02 15:25:52.750   283  1017 D DrmWidevineDash: OEMCrypto_GenerateRSASignature returns 0
,09-02 15:25:52.760   283   700 I WVCdm   : CdmEngine::CloseSession
,09-02 15:25:52.760   283   700 D DrmWidevineDash: OEMCrypto_CloseSession: starts! SID=1
09-02 15:25:52.760   283   700 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
09-02 15:25:52.760   283   700 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
09-02 15:25:52.760   283   700 D DrmWidevineDash: OEMCrypto_CloseSession: ends! returns 0
09-02 15:25:52.760   283   700 I WVCdm   : L3 Terminate.
09-02 15:25:52.760   283   700 D DrmWidevineDash: OEMCrypto_Terminate: starts!
09-02 15:25:52.760   283   700 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
09-02 15:25:52.760   283   700 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
09-02 15:25:52.760   283   700 D DrmWidevineDash: Service_Uninitialize: starts!
09-02 15:25:52.760   283   700 D QSEECOMAPI: : QSEECom_dealloc_memory 
09-02 15:25:52.760   283   700 D QSEECOMAPI: : QSEECom_shutdown_app, app_id = 11
,09-02 15:25:52.760   283   700 D DrmWidevineDash: Service_Uninitialize: ends! returns 0x0
09-02 15:25:52.760   283   700 D DrmWidevineDash: OEMCrypto_Terminate: ends! returns 0
,09-02 15:25:52.760  6283  6297 I art     : Background partial concurrent mark sweep GC freed 4390(402KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 10MB/17MB, paused 8.772ms total 42.558ms
,09-02 15:25:52.950  1019  1032 I art     : Explicit concurrent mark sweep GC freed 33297(1832KB) AllocSpace objects, 17(272KB) LOS objects, 33% free, 27MB/41MB, paused 2.612ms total 150.375ms
,09-02 15:25:52.980  6283  6293 I qtaguid : Untagging socket 30
,09-02 15:25:53.020   288   288 E SMD     : DCD OFF
,09-02 15:25:53.080  1019  2905 D ActivityManager: bindService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms, action: null
,09-02 15:25:53.080  1019  2905 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GetToken; callingUser = 0; userId(target) = 0
,09-02 15:25:53.080  1019  2905 W ActivityManager: userId = 0, bbcId = -10000
,09-02 15:25:53.080  1019  2905 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-02 15:25:53.080  1019  2905 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-02 15:25:53.170  1019  3213 D ActivityManager: bindService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms, action: null
,09-02 15:25:53.170  1019  3213 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.gcm.http.GoogleHttpService; callingUser = 0; userId(target) = 0
,09-02 15:25:53.170  1019  3213 W ActivityManager: userId = 0, bbcId = -10000
09-02 15:25:53.170  1019  3213 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-02 15:25:53.170  1019  3213 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-02 15:25:53.180  1883  2130 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,09-02 15:25:53.190   278   994 D EnterpriseController: uids 10012
09-02 15:25:53.190   278   994 D EnterpriseController: mIsMarkChainAdded is 18 mIsBlockChainAdded is 252 netId is 0
09-02 15:25:53.190   278   994 D Netd    : getNetworkForDns: using netid 502 for uid 10012
,09-02 15:25:53.190  1883  2130 I System.out: KnoxVpnUidStorageknoxVpnSupported API value returned is false
,09-02 15:25:53.190  1883  2130 I qtaguid : Tagging socket 60 with tag 1000040100000000{268436481,0} for uid 10012, pid: 1883, getuid(): 10012
,09-02 15:25:53.230  1883  2130 I qtaguid : Tagging socket 68 with tag 1000040100000000{268436481,0} for uid 10012, pid: 1883, getuid(): 10012
,09-02 15:25:53.390  6316  6316 I dex2oat : ----------------------------------------------------
09-02 15:25:53.390  6316  6316 I dex2oat : <SS>: S T A R T I N G . . .
09-02 15:25:53.390  6316  6316 I dex2oat : <SS>: Zip is absent. Canceled.
,09-02 15:25:53.390  6316  6316 I dex2oat : /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm --instruction-set-features=div --compiler-filter=interpret-only --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.google.android.gms/app_fb/f.apk --oat-fd=44 --art-fd=-1 --oat-location=/data/data/com.google.android.gms/app_fb/f.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
,09-02 15:25:53.420  6316  6316 I dex2oat : dex2oat took 23.281ms (threads: 4)
,09-02 15:25:53.430  6283  6293 I Adreno-EGL: <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: SKARAJGA_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018__release_ENGG (I856e09677e)
09-02 15:25:53.430  6283  6293 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.02
09-02 15:25:53.430  6283  6293 I Adreno-EGL: Build Date: 04/06/15 Mon
09-02 15:25:53.430  6283  6293 I Adreno-EGL: Local Branch: 
09-02 15:25:53.430  6283  6293 I Adreno-EGL: Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018
09-02 15:25:53.430  6283  6293 I Adreno-EGL: Local Patches: 112c106f3772623daa7b4181c6cf23491044ead1 Revert "Disable ASTC on A405"
09-02 15:25:53.430  6283  6293 I Adreno-EGL:                  58a118cb818fdc906095a49a90977c15f9d3b223 Remove ASTC
,09-02 15:25:53.770  6283  6293 I Adreno-EGL: <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: SKARAJGA_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018__release_ENGG (I856e09677e)
09-02 15:25:53.770  6283  6293 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.02
09-02 15:25:53.770  6283  6293 I Adreno-EGL: Build Date: 04/06/15 Mon
09-02 15:25:53.770  6283  6293 I Adreno-EGL: Local Branch: 
09-02 15:25:53.770  6283  6293 I Adreno-EGL: Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018
09-02 15:25:53.770  6283  6293 I Adreno-EGL: Local Patches: 112c106f3772623daa7b4181c6cf23491044ead1 Revert "Disable ASTC on A405"
09-02 15:25:53.770  6283  6293 I Adreno-EGL:                  58a118cb818fdc906095a49a90977c15f9d3b223 Remove ASTC
,09-02 15:25:53.820  6283  6293 I Adreno-EGL: <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: SKARAJGA_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018__release_ENGG (I856e09677e)
09-02 15:25:53.820  6283  6293 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.02
09-02 15:25:53.820  6283  6293 I Adreno-EGL: Build Date: 04/06/15 Mon
09-02 15:25:53.820  6283  6293 I Adreno-EGL: Local Branch: 
09-02 15:25:53.820  6283  6293 I Adreno-EGL: Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018
09-02 15:25:53.820  6283  6293 I Adreno-EGL: Local Patches: 112c106f3772623daa7b4181c6cf23491044ead1 Revert "Disable ASTC on A405"
09-02 15:25:53.820  6283  6293 I Adreno-EGL:                  58a118cb818fdc906095a49a90977c15f9d3b223 Remove ASTC
,09-02 15:25:53.970  1883  6281 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,09-02 15:25:53.970  1883  6281 I System.out: KnoxVpnUidStorageknoxVpnSupported API value returned is false
,09-02 15:25:53.970  1883  6281 I qtaguid : Tagging socket 69 with tag 1000040100000000{268436481,0} for uid 10012, pid: 1883, getuid(): 10012
,09-02 15:25:54.020  1883  6281 I qtaguid : Tagging socket 72 with tag 1000040100000000{268436481,0} for uid 10012, pid: 1883, getuid(): 10012
,09-02 15:25:54.170  1883  2130 I GoogleURLConnFactory: Using platform SSLCertificateSocketFactory
,09-02 15:25:54.170  1883  2130 E BaseAppContext: Tried to stop global GMSCore RequestQueue. This is likely unintended, so ignoring.
,09-02 15:25:54.190  1883  2130 W ctxmgr  : [WorkManager]Long workInfo: label=NetworkManager#getAcl, startTime=2016-09-02 15:25:52.994+0200, stopTime=2016-09-02 15:25:54.192+0200, duration=1198ms
,09-02 15:25:54.200  1883  6324 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,09-02 15:25:54.200   278   994 D EnterpriseController: uids 10012
09-02 15:25:54.200   278   994 D EnterpriseController: mIsMarkChainAdded is 18 mIsBlockChainAdded is 252 netId is 0
09-02 15:25:54.200   278   994 D Netd    : getNetworkForDns: using netid 502 for uid 10012
,09-02 15:25:54.210  1883  6324 I System.out: KnoxVpnUidStorageknoxVpnSupported API value returned is false
,09-02 15:25:54.210  1883  6324 I qtaguid : Tagging socket 74 with tag 1000310500000000{268448005,0} for uid 10012, pid: 1883, getuid(): 10012
,09-02 15:25:54.240  1019  1032 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.udc.service.UdcContextListenerService; callingUser = 0; userId(target) = 0
,09-02 15:25:54.260  1883  6324 I qtaguid : Tagging socket 76 with tag 1000310500000000{268448005,0} for uid 10012, pid: 1883, getuid(): 10012
,09-02 15:25:54.530  1883  6324 I qtaguid : Untagging socket 74
,09-02 15:25:54.560  1019  1322 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,09-02 15:25:54.560  1019  1322 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.clearcut.uploader.UploaderService; callingUser = 0; userId(target) = 0
,09-02 15:25:54.560  1019  1322 W ActivityManager: userId = 0, bbcId = -10000
09-02 15:25:54.560  1019  1322 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-02 15:25:54.560  1019  1322 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-02 15:25:54.590  1883  2130 W ctxmgr  : [AccountAclCallback]Failed Acl fetch for account account#61035162# with status: UNKNOWN).  Giving up.
,09-02 15:25:54.650  1019  3213 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,09-02 15:25:54.650  1019  3213 W ActivityManager: userId = 0, bbcId = -10000
,09-02 15:25:54.650  1019  3213 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-02 15:25:54.650  1019  3213 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-02 15:25:54.670  1019  3105 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,09-02 15:25:54.680  1019  3105 W ActivityManager: userId = 0, bbcId = -10000
09-02 15:25:54.680  1019  3105 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-02 15:25:54.680  1019  3105 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-02 15:25:54.720  1019  3214 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,09-02 15:25:54.720  1019  3214 W ActivityManager: userId = 0, bbcId = -10000
,09-02 15:25:54.720  1019  3214 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-02 15:25:54.720  1019  3214 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-02 15:25:54.720  1883  6331 E CommitToConfigurationOperation: Malformed snapshot token (size): 
,09-02 15:25:54.720  1883  6329 W PhenotypeFlagCommitter: Committing snapshot for com.google.android.gms.playlog.uploader failed, retrying
,09-02 15:25:54.720  1019  1322 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,09-02 15:25:54.720  1019  1322 W ActivityManager: userId = 0, bbcId = -10000
09-02 15:25:54.720  1019  1322 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-02 15:25:54.720  1019  1322 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-02 15:25:54.750  1019  1032 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,09-02 15:25:54.750  1019  1032 W ActivityManager: userId = 0, bbcId = -10000
,09-02 15:25:54.750  1019  1032 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-02 15:25:54.750  1019  1032 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-02 15:25:54.750  1883  6331 E CommitToConfigurationOperation: Malformed snapshot token (size): 
,09-02 15:25:54.750  1883  6329 W PhenotypeFlagCommitter: Committing snapshot for com.google.android.gms.playlog.uploader failed, retrying
,09-02 15:25:54.750  1019  1082 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,09-02 15:25:54.750  1019  1082 W ActivityManager: userId = 0, bbcId = -10000
,09-02 15:25:54.750  1019  1082 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-02 15:25:54.750  1019  1082 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-02 15:25:54.780  1019  3093 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,09-02 15:25:54.780  1019  3093 W ActivityManager: userId = 0, bbcId = -10000
,09-02 15:25:54.780  1019  3093 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-02 15:25:54.780  1019  3093 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-02 15:25:54.780  1883  6331 E CommitToConfigurationOperation: Malformed snapshot token (size): 
,09-02 15:25:54.780  1883  6329 W PhenotypeFlagCommitter: Committing snapshot for com.google.android.gms.playlog.uploader failed, retrying
,09-02 15:25:54.780  1883  6329 W PhenotypeFlagCommitter: No more attempts remaining, giving up for com.google.android.gms.playlog.uploader
,09-02 15:25:54.790  1883  6329 I GoogleURLConnFactory: Using platform SSLCertificateSocketFactory
,09-02 15:25:54.840  1019  1032 D LocationManagerService: getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,09-02 15:25:54.880  1883  6329 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,09-02 15:25:54.880   278   994 D EnterpriseController: uids 10012
09-02 15:25:54.880   278   994 D EnterpriseController: mIsMarkChainAdded is 18 mIsBlockChainAdded is 252 netId is 0
09-02 15:25:54.880   278   994 D Netd    : getNetworkForDns: using netid 502 for uid 10012
,09-02 15:25:54.880  1883  6329 I System.out: KnoxVpnUidStorageknoxVpnSupported API value returned is false
,09-02 15:25:54.880  1883  6329 I qtaguid : Tagging socket 85 with tag fffff33b00000000{4294964027,0} for uid -1, pid: 1883, getuid(): 10012
,09-02 15:25:54.950  1883  6329 I qtaguid : Tagging socket 88 with tag fffff33b00000000{4294964027,0} for uid -1, pid: 1883, getuid(): 10012
,09-02 15:25:55.260  1019  2905 D LocationManagerService: getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,09-02 15:25:55.270  1883  6329 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,09-02 15:25:55.270  1883  6329 I qtaguid : Tagging socket 85 with tag 11065c0800000000{285629448,0} for uid -1, pid: 1883, getuid(): 10012
,09-02 15:25:55.640  1019  2952 D LocationManagerService: getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,09-02 15:25:55.650  1883  6329 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,09-02 15:25:55.650  1883  6329 I qtaguid : Tagging socket 85 with tag 11065fff00000000{285630463,0} for uid -1, pid: 1883, getuid(): 10012
,09-02 15:25:55.650   338   338 I ServiceManager: Waiting for service AtCmdFwd...,
,09-02 15:25:55.800  1019  2905 D LocationManagerService: getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,09-02 15:25:55.810  1883  6329 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,09-02 15:25:55.810  1883  6329 I qtaguid : Tagging socket 85 with tag fffffb1f00000000{4294966047,0} for uid -1, pid: 1883, getuid(): 10012
,09-02 15:25:55.960  1019  1082 D LocationManagerService: getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,09-02 15:25:55.960  1883  6329 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,09-02 15:25:55.960  1883  6329 I qtaguid : Tagging socket 85 with tag 1106583100000000{285628465,0} for uid -1, pid: 1883, getuid(): 10012
,09-02 15:25:56.030   288   288 E SMD     : DCD OFF
,09-02 15:25:56.110  1019  1223 D LocationManagerService: getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,09-02 15:25:56.110  1883  6329 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,09-02 15:25:56.110  1883  6329 I qtaguid : Tagging socket 85 with tag 11065b5800000000{285629272,0} for uid -1, pid: 1883, getuid(): 10012
,09-02 15:25:56.330  1883  6323 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,09-02 15:25:56.330  1883  6323 I qtaguid : Tagging socket 74 with tag 1000310200000000{268448002,0} for uid 10012, pid: 1883, getuid(): 10012
,09-02 15:25:56.530  1883  6323 I qtaguid : Untagging socket 74
,09-02 15:25:56.530  1883  2130 E ctxmgr  : [GcmSyncStatisticsImpl]Context recd stats incorrect mode 0
,09-02 15:25:56.590  1019  3213 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.udc.service.UdcContextListenerService; callingUser = 0; userId(target) = 0
,09-02 15:25:56.650   338   338 I ServiceManager: Waiting for service AtCmdFwd...
,09-02 15:25:57.170  1019  1061 D PackageManager: [MSG] WRITE_PACKAGE_RESTRICTIONS
,09-02 15:25:57.330  1019  1031 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,09-02 15:25:57.330  1019  1031 D BatteryService: level:94, scale:100, status:2, health:2, present:true, voltage: 4206, temperature: 285, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
,09-02 15:25:57.330  1019  1031 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
09-02 15:25:57.330  1019  1031 D BatteryService: stay LED for charging
09-02 15:25:57.330  1019  1019 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,09-02 15:25:57.340  1019  1019 I MotionRecognitionService: Plugged
09-02 15:25:57.340  1019  1019 I MotionRecognitionService: mGripSensorEnabled= false
,09-02 15:25:57.340  1182  1182 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,09-02 15:25:57.340  1182  1182 D KeyguardUpdateMonitor: handleBatteryUpdate
,09-02 15:25:57.350  1422  1422 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,09-02 15:25:57.350  1422  1422 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 94
,09-02 15:25:57.360  2636  2636 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,09-02 15:25:57.360  2636  2712 D HeadsetStateMachine: Disconnected process message: 10
,09-02 15:25:57.370  1182  1182 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:94 status:2 health:2
,09-02 15:25:57.370  1182  1182 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:94 status:2 health:2
,09-02 15:25:57.370  1182  1182 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:94 status:2 health:2
,09-02 15:25:57.650   338   338 I ServiceManager: Waiting for service AtCmdFwd...
,09-02 15:25:58.650   338   338 I ServiceManager: Waiting for service AtCmdFwd...,
,09-02 15:25:58.970  1019  1082 I ActivityManager: Killing 5322:com.google.android.talk/u0a104 (adj 15): empty #31
,09-02 15:25:59.030   288   288 E SMD     : DCD OFF
,09-02 15:25:59.580  1019  1053 I PowerManagerService: [PWL] Off : 50s ago
,09-02 15:25:59.650   338   338 I ServiceManager: Waiting for service AtCmdFwd...,
,09-02 15:25:59.990  1019  2713 D SSRM:n  : SIOP:: AP = 350
,09-02 15:25:59.990  1019  1100 V AlarmManager: waitForAlarm result :8
,09-02 15:26:00.650   338   338 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 2,
,09-02 15:26:01.720  6212  6266 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
09-02 15:26:01.720  6212  6266 I jxcore-log: 
,09-02 15:26:01.720  6212  6266 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
09-02 15:26:01.720  6212  6266 I jxcore-log: 
,09-02 15:26:01.720  6212  6266 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-02 15:26:01.720  6212  6266 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-02 15:26:01.720  6212  6266 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-02 15:26:01.720  6212  6266 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-02 15:26:01.720  6212  6266 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-02 15:26:01.720  6212  6266 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-02 15:26:01.720  6212  6266 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-02 15:26:01.720  6212  6266 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-02 15:26:01.730  6212  6266 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-02 15:26:01.730  6212  6266 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
09-02 15:26:01.730  6212  6266 I jxcore-log: 
,09-02 15:26:01.730  6212  6266 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
09-02 15:26:01.730  6212  6266 I jxcore-log: 
,09-02 15:26:02.030   288   288 E SMD     : DCD OFF,
,09-02 15:26:02.360  6212  6266 D executeNativeTests: Running unit tests
,09-02 15:26:02.440  6212  6266 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-02 15:26:02.440  6212  6266 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@9e489d0 added. We now have 2 listener(s)
,09-02 15:26:02.440  6212  6266 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "7C:F9:0E:37:96:AB"
,09-02 15:26:02.440  6212  6266 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-02 15:26:02.440  6212  6266 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,09-02 15:26:02.440  6212  6266 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-02 15:26:02.440  6212  6266 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3f2c3dc9 added. We now have 2 listener(s)
09-02 15:26:02.440  6212  6266 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-02 15:26:02.440  6212  6266 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-02 15:26:02.450  6212  6266 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-02 15:26:02.450  6212  6266 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-02 15:26:02.450  6212  6266 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-02 15:26:02.450  6212  6266 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-02 15:26:02.450  6212  6266 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-02 15:26:02.450  6212  6266 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-02 15:26:02.450  6212  6266 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-02 15:26:02.450  6212  6266 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-02 15:26:02.450  6212  6266 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-02 15:26:02.450  6212  6266 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-02 15:26:02.450  6212  6266 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-02 15:26:02.450  6212  6212 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-02 15:26:02.450  6212  6266 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
09-02 15:26:02.450  6212  6266 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-02 15:26:02.450  6212  6266 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,09-02 15:26:02.460  6212  6266 E io.jxcore.node.ConnectionHelper: onConnectionTimeout: Connection attempt with peer [<no peer name> 00:11:22:33:44:55] timed out
09-02 15:26:02.460  6212  6266 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
09-02 15:26:02.460  6212  6266 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
09-02 15:26:02.460  6212  6266 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-02 15:26:02.460  6212  6266 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
,09-02 15:26:02.460  6212  6212 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-02 15:26:02.460  6212  6266 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-02 15:26:02.460  6212  6266 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-02 15:26:02.460  6212  6266 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-02 15:26:02.460  6212  6266 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-02 15:26:02.460  6212  6266 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-02 15:26:02.460  6212  6266 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-02 15:26:02.460  6212  6266 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-02 15:26:02.460  6212  6266 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@9e489d0 removed from the list
09-02 15:26:02.460  6212  6266 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-02 15:26:02.460  6212  6266 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3f2c3dc9 removed from the list
09-02 15:26:02.460  6212  6266 D io.jxcore.node.ConnectivityMonitor: stop
09-02 15:26:02.460  6212  6266 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-02 15:26:02.460  6212  6266 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 15:26:02.460  6212  6266 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-02 15:26:02.470  6212  6266 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-02 15:26:02.470  6212  6266 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-02 15:26:02.470  6212  6266 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-02 15:26:02.470  6212  6266 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3f2c3dc9 not in the list
,09-02 15:26:02.470  6212  6266 D io.jxcore.node.ConnectionHelper: onBluetoothMacAddressResolved: 00:11:22:33:44:55 - Bro Mode is not supported
,09-02 15:26:02.470  6212  6266 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-02 15:26:02.470  6212  6266 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-02 15:26:02.470  6212  6266 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-02 15:26:02.470  6212  6266 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-02 15:26:02.470  6212  6266 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 15:26:02.470  6212  6266 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-02 15:26:02.470  6212  6266 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@9e489d0 not in the list
09-02 15:26:02.470  6212  6266 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-02 15:26:02.470  6212  6266 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3f2c3dc9 not in the list
09-02 15:26:02.470  6212  6266 D io.jxcore.node.ConnectivityMonitor: stop
09-02 15:26:02.470  6212  6266 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 15:26:02.470  6212  6266 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-02 15:26:02.470  6212  6266 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 15:26:02.470  6212  6266 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-02 15:26:02.470  6212  6266 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-02 15:26:02.470  6212  6266 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-02 15:26:02.470  6212  6266 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-02 15:26:02.470  6212  6266 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3f2c3dc9 not in the list
09-02 15:26:02.480  6212  6266 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
09-02 15:26:02.480  6212  6266 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
09-02 15:26:02.480  6212  6266 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
09-02 15:26:02.480  6212  6266 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
09-02 15:26:02.480  6212  6266 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
09-02 15:26:02.480  6212  6266 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
09-02 15:26:02.480  6212  6266 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
09-02 15:26:02.480  6212  6266 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
09-02 15:26:02.480  6212  6266 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
09-02 15:26:02.480  6212  6266 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
09-02 15:26:02.480  6212  6266 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
09-02 15:26:02.480  6212  6266 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
09-02 15:26:02.480  6212  6266 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
09-02 15:26:02.480  6212  6266 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
09-02 15:26:02.480  6212  6266 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
09-02 15:26:02.480  6212  6266 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
09-02 15:26:02.480  6212  6266 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
09-02 15:26:02.480  6212  6266 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
09-02 15:26:02.480  6212  6266 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
09-02 15:26:02.480  6212  6266 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
09-02 15:26:02.480  6212  6266 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
09-02 15:26:02.480  6212  6266 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
09-02 15:26:02.480  6212  6266 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
09-02 15:26:02.480  6212  6266 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
09-02 15:26:02.480  6212  6266 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
09-02 15:26:02.480  6212  6266 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
09-02 15:26:02.480  6212  6266 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
09-02 15:26:02.480  6212  6266 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
09-02 15:26:02.480  6212  6266 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
09-02 15:26:02.480  6212  6266 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
09-02 15:26:02.480  6212  6266 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
09-02 15:26:02.480  6212  6266 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-02 15:26:02.480  6212  6266 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-02 15:26:02.480  6212  6266 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-02 15:26:02.480  6212  6266 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-02 15:26:02.480  6212  6266 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 15:26:02.480  6212  6266 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-02 15:26:02.480  6212  6266 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@9e489d0 not in the list
09-02 15:26:02.480  6212  6266 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-02 15:26:02.480  6212  6266 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3f2c3dc9 not in the list
09-02 15:26:02.480  6212  6266 D io.jxcore.node.ConnectivityMonitor: stop
09-02 15:26:02.480  6212  6266 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 15:26:02.480  6212  6266 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-02 15:26:02.480  6212  6266 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 15:26:02.480  6212  6266 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-02 15:26:02.480  6212  6266 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-02 15:26:02.480  6212  6266 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-02 15:26:02.480  6212  6266 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-02 15:26:02.480  6212  6266 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3f2c3dc9 not in the list
09-02 15:26:02.480  6212  6266 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
09-02 15:26:02.480  6212  6266 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-02 15:26:02.490  6212  6266 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-02 15:26:02.490  6212  6266 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-02 15:26:02.490  6212  6266 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-02 15:26:02.490  6212  6266 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-02 15:26:02.490  6212  6266 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-02 15:26:02.490  6212  6266 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-02 15:26:02.490  6212  6266 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-02 15:26:02.490  6212  6266 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-02 15:26:02.500  6212  6266 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-02 15:26:02.500  6212  6266 D io.jxcore.node.ConnectivityMonitor: start: OK
09-02 15:26:02.500  6212  6266 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-02 15:26:02.500  6212  6266 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only,
09-02 15:26:02.500  6212  6266 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-02 15:26:02.500  6212  6266 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-02 15:26:02.500  6212  6266 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-02 15:26:02.500  6212  6212 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-02 15:26:02.510  6212  6212 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-02 15:26:02.510  6212  6266 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
09-02 15:26:02.520  6212  6266 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
09-02 15:26:02.520  6212  6266 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
09-02 15:26:02.520  6212  6266 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded filtering: Storing the value (SUPPORTED) in persistent storage
09-02 15:26:02.530  6212  6266 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded scan batching: Storing the value (SUPPORTED) in persistent storage
09-02 15:26:02.530  6212  6266 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
09-02 15:26:02.530  6212  6266 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
09-02 15:26:02.540  6212  6266 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,09-02 15:26:02.560  2636  2892 D BtGatt.GattService: registerClient() - UUID=41b7bd7a-02ec-4e76-8f96-069fef21d869
,09-02 15:26:02.600  2636  2706 D BtGatt.GattService: onClientRegistered() - UUID=41b7bd7a-02ec-4e76-8f96-069fef21d869, clientIf=6
,09-02 15:26:02.610  6212  6221 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=6
,09-02 15:26:02.610  2636  2710 D BtGatt.GattService: start scan with filters
,09-02 15:26:02.610  2636  2709 D BtGatt.ScanManager: handling starting scan
,09-02 15:26:02.610  2636  2709 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@a523621
,09-02 15:26:02.620  6212  6266 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,09-02 15:26:02.620  6212  6266 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
,09-02 15:26:02.620  6212  6266 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
,09-02 15:26:02.620  6212  6266 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,09-02 15:26:02.620  6212  6266 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,09-02 15:26:02.630  6212  6212 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,09-02 15:26:02.630  2636  2706 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=6, status=0, action=1
,09-02 15:26:02.630  2636  2706 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,09-02 15:26:02.630  2636  2709 D BtGatt.ScanManager: allow scan with filters
,09-02 15:26:02.630  2636  2709 D BtGatt.ScanManager: client filter size is = 1available filters are = 13
,09-02 15:26:02.630  2636  2709 D BtGatt.ScanManager: set filter index= 3 for clientIf= 6
,09-02 15:26:02.630  6212  6266 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,09-02 15:26:02.640  6212  6266 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,09-02 15:26:02.640  2636  2706 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=0, availableSpace=15
,09-02 15:26:02.640  2636  2706 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,09-02 15:26:02.640  2636  2709 D BtGatt.ScanManager: Starting BLE batch scan
,09-02 15:26:02.640  2636  2709 D BtGatt.ScanManager: configuring batch scan storage, appIf 6
,09-02 15:26:02.650  6212  6266 I io.jxcore.node.ConnectionHelper: start: OK
,09-02 15:26:02.650  2636  2706 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=6, status=0
,09-02 15:26:02.650  2636  2706 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,09-02 15:26:02.650  6212  6266 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-02 15:26:02.660  6212  6266 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
,09-02 15:26:02.660  6212  6266 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
09-02 15:26:02.660  6212  6266 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
09-02 15:26:02.660  6212  6266 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-02 15:26:02.660  6212  6266 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-02 15:26:02.660  6212  6266 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
,09-02 15:26:02.660  2636  2706 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=1
,09-02 15:26:02.660  2636  2706 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,09-02 15:26:02.670  6212  6266 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-02 15:26:02.670  6212  6266 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-02 15:26:02.670  6212  6266 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,09-02 15:26:02.670  6212  6266 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-02 15:26:02.670  6212  6266 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,09-02 15:26:02.670  2636  2648 D BtGatt.GattService: stopScan() - queue size =1
,09-02 15:26:02.670  2636  2892 D BtGatt.GattService: unregisterClient() - clientIf=6
,09-02 15:26:02.670  6212  6266 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-02 15:26:02.670  6212  6266 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
09-02 15:26:02.670  6212  6266 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
09-02 15:26:02.670  6212  6266 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
09-02 15:26:02.670  6212  6266 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,09-02 15:26:02.670  6212  6266 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,09-02 15:26:02.670  6212  6266 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-02 15:26:02.670  6212  6266 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-02 15:26:02.670  6212  6266 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-02 15:26:02.670  6212  6266 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-02 15:26:02.680  6212  6266 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-02 15:26:02.680  6212  6266 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 15:26:02.680  6212  6266 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-02 15:26:02.680  6212  6266 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@9e489d0 not in the list
09-02 15:26:02.680  6212  6266 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-02 15:26:02.680  6212  6266 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3f2c3dc9 not in the list
09-02 15:26:02.680  6212  6266 D io.jxcore.node.ConnectivityMonitor: stop
09-02 15:26:02.680  6212  6266 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-02 15:26:02.680  6212  6212 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-02 15:26:02.680  6212  6212 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-02 15:26:02.680  6212  6212 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-02 15:26:02.680  6212  6266 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
,09-02 15:26:02.680  6212  6266 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-02 15:26:02.690  6212  6266 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-02 15:26:02.690  6212  6266 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-02 15:26:02.690  6212  6266 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-02 15:26:02.690  6212  6266 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-02 15:26:02.690  6212  6266 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-02 15:26:02.690  6212  6266 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-02 15:26:02.690  6212  6266 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-02 15:26:02.690  6212  6266 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-02 15:26:02.690  6212  6266 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-02 15:26:02.690  6212  6266 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-02 15:26:02.690  6212  6212 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-02 15:26:02.690  6212  6212 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-02 15:26:02.690  6212  6266 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
,09-02 15:26:02.690  6212  6266 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-02 15:26:02.690  6212  6266 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-02 15:26:02.690  6212  6266 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-02 15:26:02.690  6212  6266 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,09-02 15:26:02.700  2636  2709 D BtGatt.ScanManager: 1. app : com.android.bluetooth 2. Action : LESC 3. Callng app : com.test.thalitest 4. Count : 18
,09-02 15:26:02.700  6212  6266 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,09-02 15:26:02.700  2636  2709 D BtGatt.ScanManager: filter size is 1
,09-02 15:26:02.700  2636  2709 D BtGatt.ScanManager: delete FilterIndex - 3
,09-02 15:26:02.700  2636  2706 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=1, availableSpace=16
,09-02 15:26:02.700  2636  2706 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,09-02 15:26:02.700  2636  2709 D BtGatt.ScanManager: stopping BLe Batch
,09-02 15:26:02.710  6212  6266 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,09-02 15:26:02.710  2636  2706 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=0
,09-02 15:26:02.710  2636  2706 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
09-02 15:26:02.710  2636  2709 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
,09-02 15:26:02.710  2636  2706 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=0
,09-02 15:26:02.710  2636  2706 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,09-02 15:26:02.710  6212  6266 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,09-02 15:26:02.720  6212  6266 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,09-02 15:26:02.720  6212  6266 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
09-02 15:26:02.720  6212  6266 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,09-02 15:26:02.720  2636  2892 D BtGatt.GattService: registerClient() - UUID=285cc6e8-966f-4a76-b26e-783925ae9a09
,09-02 15:26:02.760  2636  2706 D BtGatt.GattService: onClientRegistered() - UUID=285cc6e8-966f-4a76-b26e-783925ae9a09, clientIf=6
,09-02 15:26:02.760  6212  6220 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=6
,09-02 15:26:02.760  2636  2710 D BtGatt.GattService: start scan with filters
,09-02 15:26:02.770  2636  2709 D BtGatt.ScanManager: handling starting scan
,09-02 15:26:02.770  6212  6266 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,09-02 15:26:02.770  2636  2706 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=6, status=0, action=1
,09-02 15:26:02.770  2636  2706 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
09-02 15:26:02.770  2636  2709 D BtGatt.ScanManager: allow scan with filters
09-02 15:26:02.770  2636  2709 D BtGatt.ScanManager: client filter size is = 1available filters are = 13
,09-02 15:26:02.770  2636  2709 D BtGatt.ScanManager: set filter index= 4 for clientIf= 6
09-02 15:26:02.770  6212  6266 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
,09-02 15:26:02.770  6212  6266 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
,09-02 15:26:02.770  2636  2706 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=0, availableSpace=15
09-02 15:26:02.770  2636  2706 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
09-02 15:26:02.770  2636  2709 D BtGatt.ScanManager: Starting BLE batch scan
09-02 15:26:02.770  2636  2709 D BtGatt.ScanManager: configuring batch scan storage, appIf 6
,09-02 15:26:02.770  6212  6266 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,09-02 15:26:02.780  2636  2706 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=6, status=0
,09-02 15:26:02.780  2636  2706 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,09-02 15:26:02.780  2636  2706 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=1
,09-02 15:26:02.780  2636  2706 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,09-02 15:26:02.790  6212  6266 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
09-02 15:26:02.790  6212  6266 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,09-02 15:26:02.790  6212  6212 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,09-02 15:26:02.790  6212  6266 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,09-02 15:26:02.800  2636  2709 D BtGatt.ScanManager: 1. app : com.android.bluetooth 2. Action : LESC 3. Callng app : com.test.thalitest 4. Count : 19
,09-02 15:26:02.800  6212  6266 I io.jxcore.node.ConnectionHelper: start: OK
,09-02 15:26:02.800  6212  6266 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-02 15:26:02.800  6212  6266 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
09-02 15:26:02.800  6212  6266 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
09-02 15:26:02.800  6212  6266 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
,09-02 15:26:02.800  6212  6266 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 15:26:02.800  6212  6266 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-02 15:26:02.800  6212  6266 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
,09-02 15:26:02.810  6212  6266 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-02 15:26:02.810  6212  6266 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-02 15:26:02.810  6212  6266 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,09-02 15:26:02.810  6212  6266 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-02 15:26:02.810  6212  6266 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,09-02 15:26:02.810  2636  2648 D BtGatt.GattService: stopScan() - queue size =1
,09-02 15:26:02.810  2636  2709 D BtGatt.ScanManager: filter size is 1
,09-02 15:26:02.810  2636  2709 D BtGatt.ScanManager: delete FilterIndex - 4
,09-02 15:26:02.810  2636  2706 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=1, availableSpace=16
,09-02 15:26:02.810  2636  2706 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
09-02 15:26:02.810  2636  2709 D BtGatt.ScanManager: stopping BLe Batch
,09-02 15:26:02.810  2636  2892 D BtGatt.GattService: unregisterClient() - clientIf=6
,09-02 15:26:02.810  6212  6266 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-02 15:26:02.810  6212  6266 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
09-02 15:26:02.810  6212  6266 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
09-02 15:26:02.810  6212  6266 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
09-02 15:26:02.810  6212  6266 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,09-02 15:26:02.820  2636  2706 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=0
09-02 15:26:02.820  2636  2706 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
09-02 15:26:02.820  2636  2709 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
,09-02 15:26:02.820  6212  6266 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,09-02 15:26:02.820  2636  2706 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=0
09-02 15:26:02.820  2636  2706 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,09-02 15:26:02.820  6212  6266 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-02 15:26:02.820  6212  6266 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-02 15:26:02.820  6212  6266 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-02 15:26:02.820  6212  6266 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-02 15:26:02.820  6212  6212 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-02 15:26:02.820  6212  6266 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-02 15:26:02.820  6212  6266 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 15:26:02.820  6212  6266 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-02 15:26:02.820  6212  6266 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@9e489d0 not in the list
09-02 15:26:02.820  6212  6266 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-02 15:26:02.820  6212  6266 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3f2c3dc9 not in the list
09-02 15:26:02.820  6212  6266 D io.jxcore.node.ConnectivityMonitor: stop
09-02 15:26:02.820  6212  6266 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-02 15:26:02.820  6212  6266 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 15:26:02.820  6212  6266 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-02 15:26:02.820  6212  6266 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-02 15:26:02.820  6212  6266 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-02 15:26:02.820  6212  6266 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-02 15:26:02.820  6212  6266 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3f2c3dc9 not in the list
,09-02 15:26:02.820  6212  6266 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
09-02 15:26:02.820  6212  6212 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,09-02 15:26:02.820  6212  6212 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,09-02 15:26:02.830  6212  6266 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-02 15:26:02.830  6212  6266 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-02 15:26:02.830  6212  6266 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-02 15:26:02.830  6212  6266 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-02 15:26:02.830  6212  6266 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-02 15:26:02.830  6212  6266 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-02 15:26:02.830  6212  6266 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-02 15:26:02.830  6212  6266 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-02 15:26:02.830  6212  6266 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-02 15:26:02.830  6212  6266 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-02 15:26:02.830  6212  6266 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-02 15:26:02.830  6212  6266 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-02 15:26:02.830  6212  6266 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-02 15:26:02.830  6212  6266 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-02 15:26:02.830  6212  6266 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-02 15:26:02.830  6212  6266 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,09-02 15:26:02.840  6212  6212 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-02 15:26:02.840  6212  6266 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
09-02 15:26:02.840  6212  6212 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-02 15:26:02.840  6212  6266 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,09-02 15:26:02.840  6212  6266 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,09-02 15:26:02.850  6212  6266 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,09-02 15:26:02.850  6212  6266 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
09-02 15:26:02.850  6212  6266 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,09-02 15:26:02.850  2636  2710 D BtGatt.GattService: registerClient() - UUID=ba4ca4a4-ac4a-4eaf-bb28-b8ad988666ce
,09-02 15:26:02.890  2636  2706 D BtGatt.GattService: onClientRegistered() - UUID=ba4ca4a4-ac4a-4eaf-bb28-b8ad988666ce, clientIf=6
,09-02 15:26:02.890  6212  6221 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=6,
09-02 15:26:02.890  2636  2645 D BtGatt.GattService: start scan with filters
09-02 15:26:02.890  2636  2709 D BtGatt.ScanManager: handling starting scan
09-02 15:26:02.890  6212  6266 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
09-02 15:26:02.890  6212  6266 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
09-02 15:26:02.890  6212  6266 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
09-02 15:26:02.890  6212  6266 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,09-02 15:26:02.900  6212  6266 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
09-02 15:26:02.900  6212  6212 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,09-02 15:26:02.900  6212  6266 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
09-02 15:26:02.900  6212  6266 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,09-02 15:26:02.900  2636  2706 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=6, status=0, action=1
09-02 15:26:02.900  2636  2706 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
09-02 15:26:02.900  2636  2709 D BtGatt.ScanManager: allow scan with filters
09-02 15:26:02.900  2636  2709 D BtGatt.ScanManager: client filter size is = 1available filters are = 13
09-02 15:26:02.900  2636  2709 D BtGatt.ScanManager: set filter index= 5 for clientIf= 6
,09-02 15:26:02.910  6212  6266 I io.jxcore.node.ConnectionHelper: start: OK
,09-02 15:26:02.910  6212  6266 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-02 15:26:02.910  6212  6266 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
,09-02 15:26:02.910  6212  6266 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
09-02 15:26:02.910  6212  6266 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
,09-02 15:26:02.910  2636  2706 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=0, availableSpace=15
,09-02 15:26:02.910  2636  2706 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
09-02 15:26:02.910  2636  2709 D BtGatt.ScanManager: Starting BLE batch scan
,09-02 15:26:02.910  2636  2709 D BtGatt.ScanManager: configuring batch scan storage, appIf 6
09-02 15:26:02.910  6212  6266 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 15:26:02.910  6212  6266 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-02 15:26:02.910  6212  6266 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
09-02 15:26:02.910  6212  6266 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-02 15:26:02.910  6212  6266 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-02 15:26:02.910  6212  6266 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-02 15:26:02.910  6212  6266 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-02 15:26:02.910  6212  6266 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,09-02 15:26:02.920  2636  2710 D BtGatt.GattService: stopScan() - queue size =1
,09-02 15:26:02.920  2636  2645 D BtGatt.GattService: unregisterClient() - clientIf=6
,09-02 15:26:02.920  6212  6266 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,09-02 15:26:02.920  6212  6266 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
09-02 15:26:02.920  6212  6266 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
09-02 15:26:02.920  6212  6266 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
09-02 15:26:02.920  6212  6266 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,09-02 15:26:02.920  2636  2706 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=6, status=0
,09-02 15:26:02.920  2636  2706 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,09-02 15:26:02.920  6212  6266 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
09-02 15:26:02.920  6212  6266 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,09-02 15:26:02.920  6212  6266 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-02 15:26:02.920  6212  6266 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,09-02 15:26:02.920  6212  6266 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left,
09-02 15:26:02.930  6212  6212 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,09-02 15:26:02.930  6212  6266 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-02 15:26:02.930  6212  6266 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
09-02 15:26:02.930  6212  6266 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,09-02 15:26:02.930  6212  6266 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-02 15:26:02.930  6212  6266 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-02 15:26:02.930  6212  6266 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-02 15:26:02.930  6212  6266 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-02 15:26:02.930  6212  6266 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@9e489d0 not in the list
09-02 15:26:02.930  6212  6266 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-02 15:26:02.930  6212  6266 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3f2c3dc9 not in the list
,09-02 15:26:02.930  6212  6266 D io.jxcore.node.ConnectivityMonitor: stop,
09-02 15:26:02.930  6212  6266 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-02 15:26:02.930  6212  6212 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,09-02 15:26:02.930  6212  6266 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 15:26:02.930  6212  6212 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-02 15:26:02.930  6212  6266 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-02 15:26:02.930  6212  6266 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-02 15:26:02.930  6212  6266 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,09-02 15:26:02.930  6212  6266 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-02 15:26:02.930  6212  6266 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3f2c3dc9 not in the list
09-02 15:26:02.930  6212  6266 D io.jxcore.node.ConnectionHelper: onPeerReadyToProvideBluetoothMacAddress: Bro Mode is not supported
09-02 15:26:02.930  6212  6266 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-02 15:26:02.930  6212  6266 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-02 15:26:02.930  6212  6266 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-02 15:26:02.930  6212  6266 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-02 15:26:02.930  6212  6266 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 15:26:02.930  6212  6266 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-02 15:26:02.930  6212  6266 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@9e489d0 not in the list
09-02 15:26:02.930  6212  6266 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-02 15:26:02.930  6212  6266 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3f2c3dc9 not in the list
09-02 15:26:02.930  6212  6266 D io.jxcore.node.ConnectivityMonitor: stop
09-02 15:26:02.930  6212  6266 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed,
,09-02 15:26:02.930  6212  6266 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-02 15:26:02.930  6212  6266 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 15:26:02.930  6212  6266 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-02 15:26:02.930  6212  6266 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-02 15:26:02.930  6212  6266 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-02 15:26:02.930  6212  6266 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-02 15:26:02.930  6212  6266 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3f2c3dc9 not in the list
,09-02 15:26:02.940  2636  2706 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=1
09-02 15:26:02.940  2636  2706 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
09-02 15:26:02.940  6212  6266 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
09-02 15:26:02.940  6212  6266 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-02 15:26:02.940  6212  6266 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,09-02 15:26:02.940  6212  6266 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-02 15:26:02.940  6212  6266 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-02 15:26:02.940  6212  6266 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 15:26:02.940  6212  6266 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-02 15:26:02.940  6212  6266 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@9e489d0 not in the list,
09-02 15:26:02.940  6212  6266 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-02 15:26:02.940  6212  6266 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3f2c3dc9 not in the list
09-02 15:26:02.940  6212  6266 D io.jxcore.node.ConnectivityMonitor: stop
09-02 15:26:02.940  6212  6266 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-02 15:26:02.940  6212  6266 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-02 15:26:02.940  6212  6266 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 15:26:02.940  6212  6266 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-02 15:26:02.940  6212  6266 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-02 15:26:02.940  6212  6266 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery,
09-02 15:26:02.940  6212  6266 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-02 15:26:02.940  6212  6266 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3f2c3dc9 not in the list
,09-02 15:26:02.950  6212  6266 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: null
,09-02 15:26:02.950  6212  6266 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-02 15:26:02.950  6212  6266 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-02 15:26:02.950  6212  6266 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-02 15:26:02.950  6212  6266 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-02 15:26:02.950  6212  6266 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 15:26:02.950  6212  6266 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-02 15:26:02.950  6212  6266 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@9e489d0 not in the list
09-02 15:26:02.950  6212  6266 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-02 15:26:02.950  6212  6266 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3f2c3dc9 not in the list
09-02 15:26:02.950  6212  6266 D io.jxcore.node.ConnectivityMonitor: stop
09-02 15:26:02.950  6212  6266 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 15:26:02.950  6212  6266 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-02 15:26:02.950  6212  6266 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 15:26:02.950  6212  6266 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-02 15:26:02.950  6212  6266 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,09-02 15:26:02.950  6212  6266 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-02 15:26:02.950  6212  6266 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-02 15:26:02.950  6212  6266 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3f2c3dc9 not in the list
,09-02 15:26:02.960  2636  2709 D BtGatt.ScanManager: 1. app : com.android.bluetooth 2. Action : LESC 3. Callng app : com.test.thalitest 4. Count : 20
,09-02 15:26:02.960  6212  6266 V io.jxcore.node.ConnectionHelper: Received a request for permission "randomString", but we are expecting that all the required permissions have already been granted
09-02 15:26:02.960  6212  6266 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-02 15:26:02.960  6212  6266 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-02 15:26:02.960  6212  6266 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-02 15:26:02.960  2636  2709 D BtGatt.ScanManager: filter size is 1
,09-02 15:26:02.960  6212  6266 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-02 15:26:02.960  6212  6266 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 15:26:02.960  6212  6266 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-02 15:26:02.960  6212  6266 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@9e489d0 not in the list
09-02 15:26:02.960  6212  6266 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-02 15:26:02.960  6212  6266 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3f2c3dc9 not in the list
09-02 15:26:02.960  6212  6266 D io.jxcore.node.ConnectivityMonitor: stop
09-02 15:26:02.960  6212  6266 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 15:26:02.960  6212  6266 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-02 15:26:02.960  6212  6266 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 15:26:02.960  6212  6266 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-02 15:26:02.960  2636  2709 D BtGatt.ScanManager: delete FilterIndex - 5
09-02 15:26:02.960  6212  6266 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,09-02 15:26:02.960  6212  6266 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-02 15:26:02.960  6212  6266 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-02 15:26:02.960  6212  6266 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3f2c3dc9 not in the list
,09-02 15:26:02.960  6212  6266 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
09-02 15:26:02.960  6212  6266 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-02 15:26:02.960  6212  6266 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
09-02 15:26:02.960  6212  6266 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-02 15:26:02.960  6212  6266 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
09-02 15:26:02.960  6212  6266 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-02 15:26:02.960  6212  6266 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-02 15:26:02.960  6212  6266 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-02 15:26:02.960  6212  6266 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-02 15:26:02.960  6212  6266 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-02 15:26:02.960  6212  6266 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 15:26:02.960  6212  6266 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-02 15:26:02.960  6212  6266 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@9e489d0 not in the list
09-02 15:26:02.960  6212  6266 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-02 15:26:02.960  6212  6266 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3f2c3dc9 not in the list
,09-02 15:26:02.960  6212  6266 D io.jxcore.node.ConnectivityMonitor: stop
09-02 15:26:02.960  6212  6266 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 15:26:02.960  6212  6266 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-02 15:26:02.960  6212  6266 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 15:26:02.960  6212  6266 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-02 15:26:02.960  6212  6266 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-02 15:26:02.960  6212  6266 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-02 15:26:02.960  6212  6266 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-02 15:26:02.960  6212  6266 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3f2c3dc9 not in the list
,09-02 15:26:02.970  6212  6266 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-02 15:26:02.970  6212  6266 E io.jxcore.node.ConnectionHelper: connect: We already have an outgoing connection to peer with ID 00:11:22:33:44:55
09-02 15:26:02.970  6212  6266 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
,09-02 15:26:02.970  2636  2706 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=1, availableSpace=16
09-02 15:26:02.970  2636  2706 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,09-02 15:26:02.970  2636  2709 D BtGatt.ScanManager: stopping BLe Batch
09-02 15:26:02.970  6212  6266 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-02 15:26:02.970  6212  6266 E io.jxcore.node.ConnectionHelper: connect: Maximum number of peer connections (30) reached, please try again after disconnecting a peer
09-02 15:26:02.970  6212  6266 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
,09-02 15:26:02.970  6212  6266 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
09-02 15:26:02.970  6212  6266 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
09-02 15:26:02.970  6212  6266 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
,09-02 15:26:02.970  6212  6266 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
09-02 15:26:02.970  6212  6266 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
09-02 15:26:02.970  6212  6266 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
09-02 15:26:02.970  6212  6266 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
09-02 15:26:02.970  6212  6266 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
,09-02 15:26:02.970  6212  6266 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
09-02 15:26:02.970  6212  6266 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
09-02 15:26:02.970  6212  6266 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
09-02 15:26:02.970  6212  6266 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
09-02 15:26:02.970  6212  6266 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
09-02 15:26:02.970  6212  6266 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
09-02 15:26:02.970  6212  6266 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
09-02 15:26:02.970  6212  6266 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
09-02 15:26:02.970  6212  6266 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
,09-02 15:26:02.970  6212  6266 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
09-02 15:26:02.970  6212  6266 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
09-02 15:26:02.970  6212  6266 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
09-02 15:26:02.970  6212  6266 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
09-02 15:26:02.970  6212  6266 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
09-02 15:26:02.970  6212  6266 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
09-02 15:26:02.970  6212  6266 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
09-02 15:26:02.970  6212  6266 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
09-02 15:26:02.970  6212  6266 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
09-02 15:26:02.970  6212  6266 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
09-02 15:26:02.970  6212  6266 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
09-02 15:26:02.970  6212  6266 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
09-02 15:26:02.970  6212  6266 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID abcd
09-02 15:26:02.970  6212  6266 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
09-02 15:26:02.970  6212  6266 E io.jxcore.node.ConnectionHelper: connect: Invalid Bluetooth MAC address: abcd
09-02 15:26:02.970  6212  6266 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-02 15:26:02.970  6212  6266 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
09-02 15:26:02.970  6212  6266 E io.jxcore.node.ConnectionHelper: connect: Failed to add the callback for the connection
09-02 15:26:02.970  6212  6266 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-02 15:26:02.970  6212  6266 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
09-02 15:26:02.970  6212  6266 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: connect: [<no peer name> 00:11:22:33:44:55]
09-02 15:26:02.970  6212  6266 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Trying to start connecting to null in address 00:11:22:33:44:55
,09-02 15:26:02.980  6212  6266 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setInsecureRfcommSocketPortNumber: Using port -1
09-02 15:26:02.980  6212  6266 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setMaxNumberOfRetries: 0
,09-02 15:26:02.980  6212  6266 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnecting: null 00:11:22:33:44:55
09-02 15:26:02.980  6212  6266 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Started connecting to null in address 00:11:22:33:44:55
09-02 15:26:02.980  6212  6266 I io.jxcore.node.ConnectionHelper: connect: Connection process successfully started (peer ID: 00:11:22:33:44:55)
09-02 15:26:02.980  6212  6266 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-02 15:26:02.980  6212  6266 E io.jxcore.node.ConnectionHelper: connect: Callback is null
09-02 15:26:02.980  6212  6266 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-02 15:26:02.980  6212  6266 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-02 15:26:02.980  6212  6266 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,09-02 15:26:02.980  6212  6266 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-02 15:26:02.980  6212  6266 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 15:26:02.980  6212  6266 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-02 15:26:02.980  6212  6266 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: cancelAllConnectionAttempts: Shutting down 1 client threads
09-02 15:26:02.980  6212  6266 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@9e489d0 not in the list
09-02 15:26:02.980  6212  6266 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-02 15:26:02.980  6212  6266 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3f2c3dc9 not in the list
09-02 15:26:02.980  6212  6266 D io.jxcore.node.ConnectivityMonitor: stop
09-02 15:26:02.980  6212  6266 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 15:26:02.980  6212  6266 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-02 15:26:02.980  6212  6266 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 15:26:02.980  6212  6266 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-02 15:26:02.980  2636  2706 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=0
09-02 15:26:02.980  2636  2706 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
09-02 15:26:02.980  2636  2709 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
09-02 15:26:02.980  6212  6266 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-02 15:26:02.980  6212  6266 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-02 15:26:02.980  6212  6266 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-02 15:26:02.980  6212  6266 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3f2c3dc9 not in the list
09-02 15:26:02.980  6212  6343 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: shutdown: Thread ID: 1137
,09-02 15:26:02.980  6212  6266 E io.jxcore.node.ConnectionHelper: onProvideBluetoothMacAddressRequest: Request ID: 1111 - Bro Mode is not supported
,09-02 15:26:02.980  6212  6266 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-02 15:26:02.980  6212  6266 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-02 15:26:02.980  6212  6266 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-02 15:26:02.980  6212  6266 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-02 15:26:02.980  6212  6266 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 15:26:02.980  6212  6266 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-02 15:26:02.980  6212  6266 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@9e489d0 not in the list
09-02 15:26:02.980  6212  6266 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-02 15:26:02.980  6212  6266 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3f2c3dc9 not in the list
09-02 15:26:02.980  6212  6266 D io.jxcore.node.ConnectivityMonitor: stop
09-02 15:26:02.980  6212  6266 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 15:26:02.980  6212  6266 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-02 15:26:02.980  6212  6266 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 15:26:02.980  6212  6266 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-02 15:26:02.980  6212  6342 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Trying to connect to peer with address 00:11:22:33:44:55 (thread ID: 1137)
09-02 15:26:02.980  6212  6342 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Exiting thread (thread ID: 1137)
,09-02 15:26:02.980  2636  2706 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=0
,09-02 15:26:02.980  2636  2706 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
09-02 15:26:02.980  6212  6266 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,09-02 15:26:02.980  6212  6266 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-02 15:26:02.980  6212  6266 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-02 15:26:02.980  6212  6266 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3f2c3dc9 not in the list
09-02 15:26:02.990  6212  6266 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: true
09-02 15:26:02.990  6212  6266 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-02 15:26:02.990  6212  6266 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,09-02 15:26:02.990  6212  6266 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,09-02 15:26:02.990  6212  6266 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-02 15:26:02.990  6212  6266 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-02 15:26:02.990  6212  6266 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-02 15:26:02.990  6212  6266 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@9e489d0 not in the list
09-02 15:26:02.990  6212  6266 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-02 15:26:02.990  6212  6266 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3f2c3dc9 not in the list
09-02 15:26:02.990  6212  6266 D io.jxcore.node.ConnectivityMonitor: stop
09-02 15:26:02.990  6212  6266 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 15:26:02.990  6212  6266 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-02 15:26:02.990  6212  6266 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 15:26:02.990  6212  6266 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-02 15:26:02.990  6212  6266 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-02 15:26:02.990  6212  6266 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-02 15:26:02.990  6212  6266 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-02 15:26:02.990  6212  6266 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3f2c3dc9 not in the list
09-02 15:26:02.990  6212  6266 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID randomString
09-02 15:26:02.990  6212  6266 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID randomString
09-02 15:26:02.990  6212  6266 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
09-02 15:26:02.990  6212  6266 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: randomString), either no such connection or failed to close the connection
09-02 15:26:02.990  6212  6266 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
09-02 15:26:02.990  6212  6266 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 00:11:22:33:44:55
09-02 15:26:02.990  6212  6266 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
09-02 15:26:02.990  6212  6266 I io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Successfully disconnected (peer ID: 00:11:22:33:44:55
09-02 15:26:02.990  6212  6266 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
09-02 15:26:02.990  6212  6266 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 00:11:22:33:44:55
09-02 15:26:02.990  6212  6266 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
09-02 15:26:02.990  6212  6266 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: 00:11:22:33:44:55), either no such connection or failed to close the connection
09-02 15:26:02.990  6212  6266 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-02 15:26:02.990  6212  6266 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false, - Stop operation: Should start/stop everything
09-02 15:26:02.990  6212  6266 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-02 15:26:02.990  6212  6266 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-02 15:26:02.990  6212  6266 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 15:26:02.990  6212  6266 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-02 15:26:02.990  6212  6266 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@9e489d0 not in the list
09-02 15:26:02.990  6212  6266 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-02 15:26:02.990  6212  6266 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3f2c3dc9 not in the list
09-02 15:26:02.990  6212  6266 D io.jxcore.node.ConnectivityMonitor: stop
09-02 15:26:02.990  6212  6266 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-02 15:26:02.990  6212  6266 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-02 15:26:02.990  6212  6266 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 15:26:02.990  6212  6266 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-02 15:26:02.990  6212  6266 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-02 15:26:02.990  6212  6266 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery,
09-02 15:26:02.990  6212  6266 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-02 15:26:02.990  6212  6266 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3f2c3dc9 not in the list
09-02 15:26:02.990  6212  6266 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-02 15:26:02.990  6212  6266 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 15:26:02.990  6212  6266 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-02 15:26:02.990  6212  6266 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@9e489d0 not in the list,
09-02 15:26:02.990  6212  6266 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-02 15:26:02.990  6212  6266 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3f2c3dc9 not in the list
09-02 15:26:02.990  6212  6266 D io.jxcore.node.ConnectivityMonitor: stop
09-02 15:26:02.990  6212  6266 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed,
09-02 15:26:02.990  6212  6266 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-02 15:26:02.990  6212  6266 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-02 15:26:02.990  6212  6266 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3f2c3dc9 not in the list
09-02 15:26:02.990  6212  6266 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-02 15:26:02.990  6212  6266 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 15:26:02.990  6212  6266 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-02 15:26:02.990  6212  6266 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@9e489d0 not in the list
09-02 15:26:02.990  6212  6266 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-02 15:26:02.990  6212  6266 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-02 15:26:02.990  6212  6266 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,09-02 15:26:02.990  6212  6266 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-02 15:26:02.990  6212  6266 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 15:26:02.990  6212  6266 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-02 15:26:02.990  6212  6266 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@9e489d0 not in the list
,09-02 15:26:02.990  6212  6266 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-02 15:26:02.990  6212  6266 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3f2c3dc9 not in the list
09-02 15:26:02.990  6212  6266 D io.jxcore.node.ConnectivityMonitor: stop
09-02 15:26:02.990  6212  6266 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-02 15:26:02.990  6212  6266 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-02 15:26:02.990  6212  6266 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 15:26:02.990  6212  6266 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-02 15:26:03.000  6212  6266 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-02 15:26:03.000  6212  6266 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-02 15:26:03.000  6212  6266 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-02 15:26:03.000  6212  6266 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3f2c3dc9 not in the list
,09-02 15:26:03.000  6212  6266 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
,09-02 15:26:03.000  6212  6266 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-02 15:26:03.010  6212  6266 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
,09-02 15:26:03.010  6212  6266 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
,09-02 15:26:03.010  6212  6266 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
09-02 15:26:03.010  6212  6266 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
09-02 15:26:03.010  6212  6266 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
09-02 15:26:03.010  6212  6212 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
09-02 15:26:03.010  6212  6266 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-02 15:26:03.010  6212  6266 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
09-02 15:26:03.010  6212  6266 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
09-02 15:26:03.010  6212  6266 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
09-02 15:26:03.010  6212  6266 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-02 15:26:03.010  6212  6266 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
09-02 15:26:03.010  6212  6212 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
09-02 15:26:03.010  6212  6266 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@9e489d0 not in the list
09-02 15:26:03.010  6212  6266 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-02 15:26:03.010  6212  6266 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-02 15:26:03.010  6212  6266 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-02 15:26:03.010  6212  6266 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-02 15:26:03.010  6212  6346 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
09-02 15:26:03.010  6212  6346 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
09-02 15:26:03.010  6212  6266 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 15:26:03.010  6212  6266 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-02 15:26:03.010  6212  6266 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
09-02 15:26:03.010  6212  6266 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3f2c3dc9 not in the list
09-02 15:26:03.010  6212  6266 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-02 15:26:03.010  6212  6266 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything,
09-02 15:26:03.010  6212  6266 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-02 15:26:03.010  6212  6266 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-02 15:26:03.010  6212  6266 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 15:26:03.010  6212  6266 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-02 15:26:03.010  6212  6266 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@9e489d0 not in the list
09-02 15:26:03.010  6212  6266 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-02 15:26:03.010  6212  6266 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3f2c3dc9 not in the list
09-02 15:26:03.010  6212  6266 D io.jxcore.node.ConnectivityMonitor: stop
,09-02 15:26:03.010  6212  6266 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 15:26:03.010  6212  6266 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-02 15:26:03.010  6212  6266 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 15:26:03.010  6212  6266 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-02 15:26:03.010  6212  6212 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-02 15:26:03.010  6212  6212 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-02 15:26:03.010  6212  6212 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
09-02 15:26:03.010  6212  6212 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-02 15:26:03.010  6212  6266 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-02 15:26:03.010  6212  6266 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-02 15:26:03.010  6212  6266 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-02 15:26:03.010  6212  6266 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3f2c3dc9 not in the list
09-02 15:26:03.010  6212  6266 E io.jxcore.node.ConnectionHelper: onConnectionFailed: Peer properties: [<no peer name> 00:11:22:33:44:55], error message: ErrorMessage
09-02 15:26:03.010  6212  6266 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed,
09-02 15:26:03.010  6212  6266 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
09-02 15:26:03.010  6212  6266 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-02 15:26:03.010  6212  6266 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-02 15:26:03.010  6212  6266 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-02 15:26:03.010  6212  6266 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-02 15:26:03.010  6212  6266 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-02 15:26:03.010  6212  6266 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 15:26:03.010  6212  6266 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-02 15:26:03.010  6212  6266 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@9e489d0 not in the list
09-02 15:26:03.010  6212  6266 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-02 15:26:03.010  6212  6266 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3f2c3dc9 not in the list
09-02 15:26:03.010  6212  6266 D io.jxcore.node.ConnectivityMonitor: stop
09-02 15:26:03.010  6212  6266 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 15:26:03.010  6212  6266 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-02 15:26:03.010  6212  6266 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 15:26:03.010  6212  6266 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-02 15:26:03.010  6212  6266 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-02 15:26:03.010  6212  6266 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-02 15:26:03.010  6212  6266 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-02 15:26:03.010  6212  6266 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3f2c3dc9 not in the list
,09-02 15:26:03.020  6212  6266 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-02 15:26:03.020  6212  6266 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-02 15:26:03.020  6212  6266 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-02 15:26:03.020  6212  6266 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-02 15:26:03.020  6212  6266 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 15:26:03.020  6212  6266 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-02 15:26:03.020  6212  6266 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@9e489d0 not in the list
09-02 15:26:03.020  6212  6266 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-02 15:26:03.020  6212  6266 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3f2c3dc9 not in the list
,09-02 15:26:03.020  6212  6266 D io.jxcore.node.ConnectivityMonitor: stop
09-02 15:26:03.020  6212  6266 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 15:26:03.020  6212  6266 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-02 15:26:03.020  6212  6266 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 15:26:03.020  6212  6266 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-02 15:26:03.020  6212  6266 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,09-02 15:26:03.020  6212  6266 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-02 15:26:03.020  6212  6266 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-02 15:26:03.020  6212  6266 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3f2c3dc9 not in the list
09-02 15:26:03.020  6212  6266 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-02 15:26:03.020  6212  6266 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-02 15:26:03.020  6212  6266 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-02 15:26:03.020  6212  6266 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-02 15:26:03.020  6212  6266 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-02 15:26:03.020  6212  6266 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-02 15:26:03.020  6212  6266 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@9e489d0 not in the list
09-02 15:26:03.020  6212  6266 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-02 15:26:03.020  6212  6266 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3f2c3dc9 not in the list
09-02 15:26:03.020  6212  6266 D io.jxcore.node.ConnectivityMonitor: stop
09-02 15:26:03.020  6212  6266 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 15:26:03.020  6212  6266 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-02 15:26:03.020  6212  6266 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 15:26:03.020  6212  6266 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-02 15:26:03.020  6212  6266 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-02 15:26:03.020  6212  6266 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-02 15:26:03.020  6212  6266 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-02 15:26:03.020  6212  6266 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3f2c3dc9 not in the list
09-02 15:26:03.020  6212  6266 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing
09-02 15:26:03.020  6212  6266 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
09-02 15:26:03.020  6212  6266 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID outgoing
09-02 15:26:03.020  6212  6266 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
09-02 15:26:03.020  6212  6266 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing2
09-02 15:26:03.020  6212  6266 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
09-02 15:26:03.020  6212  6266 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
09-02 15:26:03.020  6212  6266 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> outgoing]
09-02 15:26:03.020  6212  6266 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 1
09-02 15:26:03.020  6212  6266 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
09-02 15:26:03.020  6212  6266 E io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Failed to find an incoming connection thread with ID 1
09-02 15:26:03.020  6212  6266 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
09-02 15:26:03.020  6212  6266 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 2
09-02 15:26:03.020  6212  6266 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
09-02 15:26:03.020  6212  6266 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing1" removed
09-02 15:26:03.020  6212  6266 D io.jxco,re.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing2" removed
09-02 15:26:03.020  6212  6266 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID id
09-02 15:26:03.020  6212  6266 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID outgoing
09-02 15:26:03.020  6212  6266 D io.jxcore.node.ConnectionModel: hasConnection: We have an incoming connection with peer with ID incoming
09-02 15:26:03.020  6212  6266 D io.jxcore.node.ConnectionModel: hasConnection: We have an outgoing connection with peer with ID outgoing
09-02 15:26:03.030  6212  6266 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-02 15:26:03.030  6212  6266 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@1dd56983 added. We now have 2 listener(s)
09-02 15:26:03.030  6212  6266 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-02 15:26:03.030  6212  6266 D BluetoothAdapter: enable()
,09-02 15:26:03.030  6212  6266 D BluetoothAdapter: enable(): BT is already enabled..!
,09-02 15:26:03.030  1019  1485 D SecContentProvider: uri = 18 selection = isWifiEnabled
09-02 15:26:03.030  1019  1485 D SecContentProvider2: uri = 20 selection = isWifiStateChangeAllowed
09-02 15:26:03.030  1019  1485 D SecContentProvider2: mCursor = null
,09-02 15:26:03.030  1019  1485 D WifiService: setWifiEnabled: true pid=6212, uid=10155,
09-02 15:26:03.030  1019  1485 W ActivityManager: Permission Denial: getCurrentUser() from pid=6212, uid=10155 requires android.permission.INTERACT_ACROSS_USERS
09-02 15:26:03.030  1019  1485 W WifiService: Failed getting userId using ActivityManagerNative,
09-02 15:26:03.030  1019  1485 W WifiService: java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=6212, uid=10155 requires android.permission.INTERACT_ACROSS_USERS
09-02 15:26:03.030  1019  1485 W WifiService: 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:23916)
09-02 15:26:03.030  1019  1485 W WifiService: 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2216)
09-02 15:26:03.030  1019  1485 W WifiService: 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2204)
09-02 15:26:03.030  1019  1485 W WifiService: 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:223)
09-02 15:26:03.030  1019  1485 W WifiService: 	at android.os.Binder.execTransact(Binder.java:446)
,09-02 15:26:03.030  1019  1485 D SettingsProvider: name = wifi_on
,09-02 15:26:03.030  6212  6266 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-02 15:26:03.030  6212  6266 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@18560700 added. We now have 3 listener(s)
09-02 15:26:03.030  6212  6266 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-02 15:26:03.040  6212  6266 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-02 15:26:03.040  6212  6266 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@3cc32b39 added. We now have 4 listener(s)
09-02 15:26:03.040  6212  6266 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-02 15:26:03.040  6212  6266 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-02 15:26:03.040  6212  6266 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@3d5af57e added. We now have 5 listener(s)
09-02 15:26:03.040  6212  6266 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-02 15:26:03.040  1019  1032 D SecContentProvider: uri = 18 selection = isWifiEnabled
09-02 15:26:03.040  1019  1032 D WifiService: setWifiEnabled: false pid=6212, uid=10155
09-02 15:26:03.040  1019  1032 D SecContentProvider2: uri = 20 selection = isWifiStateChangeAllowed
09-02 15:26:03.040  1019  1032 D SecContentProvider2: mCursor = null
09-02 15:26:03.040  1019  1032 D SettingsProvider: name = wifi_on
,09-02 15:26:03.050  1019  1132 E WifiStateMachine: WifiStateMachine: Leaving Connected state
09-02 15:26:03.050  2107  2107 I wpa_supplicant: reset timer : RESET_TIMER 0
09-02 15:26:03.050  2107  2107 I wpa_supplicant: wlan0: Setting scan request: 0 sec 0 usec
09-02 15:26:03.050  2107  2107 I wpa_supplicant: P2P: Current p2p state = IDLE
,09-02 15:26:03.050  2107  2107 I wpa_supplicant: Scan requested (ret=0) - scan timeout 30 seconds
09-02 15:26:03.050  6212  6266 D BluetoothAdapter: disable()
09-02 15:26:03.050  1019  1132 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,09-02 15:26:03.060  1019  2952 D SettingsProvider: name = bluetooth_on
,09-02 15:26:03.070  6212  6266 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-02 15:26:03.070  2636  2703 D BluetoothAdapterState: CURRENT_STATE=ON, MSG = USER_TURN_OFF,
,09-02 15:26:03.070  2636  2703 D BluetoothAdapterProperties: Setting state to 13
09-02 15:26:03.070  1019  3213 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
09-02 15:26:03.070  2636  2703 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
09-02 15:26:03.070  1019  3213 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pbap.BluetoothPbapService; callingUser = 0; userId(target) = 0
09-02 15:26:03.070  2636  2703 D BluetoothAdapterService: Bluetooth PBAP supproted is true
09-02 15:26:03.070  2636  2703 D BluetoothAdapterService: updateAdapterState state is 13
09-02 15:26:03.070  1019  1132 E WifiNative-wlan0: do suspend true
09-02 15:26:03.070  1019  3213 W ActivityManager: userId = 0, bbcId = -10000
09-02 15:26:03.070  1019  3213 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-02 15:26:03.070  1019  3213 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-02 15:26:03.070  2636  2636 I BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED, state: 13
09-02 15:26:03.070  2636  2703 D BluetoothAdapterService: Autoconnection is available 
09-02 15:26:03.070  2636  2703 D BluetoothAdapterService: updateAdapterState prevState = 12newState = 13
09-02 15:26:03.070  2636  2703 D BluetoothAdapterService: terminating service from this receiver
,09-02 15:26:03.070  2636  2636 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@8c5ffeb, channel: 19, state: LISTENING
,09-02 15:26:03.070  1019  2905 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.samsung.ble.BleAutoConnectService; callingUser = 0; userId(target) = 0
09-02 15:26:03.070  6212  6266 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-02 15:26:03.070  6212  6266 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-02 15:26:03.070  6212  6266 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-02 15:26:03.070  6212  6266 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-02 15:26:03.070  6212  6266 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-02 15:26:03.070  6212  6266 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-02 15:26:03.070  6212  6266 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-02 15:26:03.070  6212  6266 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-02 15:26:03.070  6212  6266 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-02 15:26:03.070  2636  2636 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@8c5ffeb, channel: 19, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@16075573, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@2b09c148mSocket: android.net.LocalSocket@11bb6be1 impl:android.net.LocalSocketImpl@38b1ad06 fd:FileDescriptor[74]
09-02 15:26:03.070  2636  2636 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@11bb6be1 impl:android.net.LocalSocketImpl@38b1ad06 fd:FileDescriptor[74]
,09-02 15:26:03.070  1019  2905 W ActivityManager: userId = 0, bbcId = -10000
09-02 15:26:03.070  1019  2905 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-02 15:26:03.070  1019  2905 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
09-02 15:26:03.080  6212  6266 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-02 15:26:03.080  6212  6266 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-02 15:26:03.080  6212  6266 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-02 15:26:03.080  2636  2703 D BluetoothAdapterProperties: onBluetoothDisable()
,09-02 15:26:03.080  2636  2703 D BluetoothAdapterProperties: mDiscovering is false
09-02 15:26:03.080  1019  1223 D SecContentProvider: uri = 3 selection = isDiscoverableEnabled
09-02 15:26:03.080  2636  2703 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=false, isTurningOff()=true
,09-02 15:26:03.080  1296  1296 D BluetoothPbap: Proxy object disconnected
09-02 15:26:03.080  1296  1296 D PbapServerProfile: Bluetooth service disconnected
,09-02 15:26:03.090  6212  6212 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes,
09-02 15:26:03.090  2636  2706 D BluetoothUtils: getBtEnabledContainers(): btContainers = []
09-02 15:26:03.090  2636  2706 D BluetoothAdapterProperties: Scan Mode:20
,09-02 15:26:03.090  2636  2703 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = BEGIN_DISABLE, isTurningOn=false, isTurningOff=true
09-02 15:26:03.090  2636  2703 E bt-btif : btif_vhci_sock_cleanup, sock_thread_handle:6, rfc_init:1, vhci_init:1
09-02 15:26:03.090  2636  2703 E bt-btif : btif_sock_cleanup, sock_thread_handle:6, rfc_init:1, vhci_init:0
,09-02 15:26:03.090  2636  2703 E bt-btif : cmd socket is not created
,09-02 15:26:03.090  2636  2703 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
09-02 15:26:03.090  2636  4978 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
09-02 15:26:03.090  6212  6212 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-02 15:26:03.090  2636  2782 E bt-btm  : btm_ble_start_auto_conn start : 0, 0
09-02 15:26:03.090  2636  2782 W bt-btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
,09-02 15:26:03.100  6212  6212 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-02 15:26:03.100  6212  6212 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-02 15:26:03.100  6212  6212 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-02 15:26:03.100  6212  6212 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-02 15:26:03.100  6212  6212 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-02 15:26:03.100  6212  6212 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-02 15:26:03.100  6212  6212 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-02 15:26:03.100  6212  6212 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-02 15:26:03.100  6212  6212 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-02 15:26:03.100  6212  6212 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-02 15:26:03.100  6212  6212 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-02 15:26:03.100  2636  2782 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
09-02 15:26:03.100  2636  2782 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-02 15:26:03.100  2636  2782 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
,09-02 15:26:03.110  6212  6212 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-02 15:26:03.120  1019  1019 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
09-02 15:26:03.120  1019  1019 I InputMethodManagerService: [BT Setting State] State =13
,09-02 15:26:03.130  1182  1182 D BluetoothTile:  onBluetoothStateChange:
,09-02 15:26:03.130  1182  1182 D BluetoothTile:  onBluetoothPairedDevicesChanged:
,09-02 15:26:03.130  1182  1704 D BluetoothTile:  handleUpdatestate:false name:null
,09-02 15:26:03.130  1182  1182 D BluetoothTile: onReceive : android.bluetooth.adapter.action.STATE_CHANGED
,09-02 15:26:03.130  1182  1704 D BluetoothTile:  handleUpdatestate:false name:null
,09-02 15:26:03.130  1182  1182 D BluetoothTile:  getBluetoothState : 13
,09-02 15:26:03.130  1182  1704 D STATUSBAR-QSTileView: onStateChanged: Bluetooth
,09-02 15:26:03.130  1954  1954 I SamsungIME: STATE_CHANGED = 13, KEYBOARD_BT(0), mBTKeyboardCount =0
,09-02 15:26:03.140  2636  2636 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@9da9f4, channel: 5, state: LISTENING
09-02 15:26:03.140  2636  2636 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@9da9f4, channel: 5, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@271a9c30, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@33a1e51dmSocket: android.net.LocalSocket@212b9392 impl:android.net.LocalSocketImpl@1b708163 fd:FileDescriptor[76]
09-02 15:26:03.140  2636  2636 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@212b9392 impl:android.net.LocalSocketImpl@1b708163 fd:FileDescriptor[76]
09-02 15:26:03.140  1019  3093 D StatusBarManagerService: setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
,09-02 15:26:03.140  1019  1484 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=false
,09-02 15:26:03.140  2636  2636 I BtOppRfcommListener: stopping Accept Thread
09-02 15:26:03.140  2636  2636 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@2be57160, channel: 12, state: LISTENING
09-02 15:26:03.140  2636  2636 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@2be57160, channel: 12, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@1f55573a, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@297cb619mSocket: android.net.LocalSocket@19eb56de impl:android.net.LocalSocketImpl@b5fd0bf fd:FileDescriptor[80]
09-02 15:26:03.140  2636  2636 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@19eb56de impl:android.net.LocalSocketImpl@b5fd0bf fd:FileDescriptor[80]
,09-02 15:26:03.140  1296  1296 V BluetoothEventManager: Received android.bluetooth.adapter.action.STATE_CHANGED
09-02 15:26:03.140  2636  4978 I BtOppRfcommListener: BluetoothSocket listen thread finished
09-02 15:26:03.140  1019  2903 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
09-02 15:26:03.140  1019  2903 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.nearby.discovery.service.DiscoveryService; callingUser = 0; userId(target) = 0
,09-02 15:26:03.140  1182  1182 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 )
09-02 15:26:03.140  6212  6212 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-02 15:26:03.150  1019  2903 W ActivityManager: userId = 0, bbcId = -10000
09-02 15:26:03.150  1019  2903 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-02 15:26:03.150  1019  2903 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-02 15:26:03.150  6212  6212 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-02 15:26:03.150  2636  2636 V BluetoothOppManager: cleanUp...
09-02 15:26:03.150  1296  1296 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,09-02 15:26:03.150  1019  1082 D ActivityManager: startService callerProcessName:com.android.settings, calleePkgName: com.android.settings
,09-02 15:26:03.150  1019  1082 D ActivityManager: retrieveServiceLocked(): component = com.android.settings/com.android.settings.bluetooth.DockService; callingUser = 0; userId(target) = 0
,09-02 15:26:03.150  1019  1082 W ActivityManager: userId = 0, bbcId = -10000
,09-02 15:26:03.150  1019  1082 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-02 15:26:03.150  1019  1082 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.settings
,09-02 15:26:03.160  1296  1296 D DockEventReceiver: finishStartingService: stopping service
,09-02 15:26:03.170  1296  1296 D BluetoothNotiBroadcastReceiver: onReceive
,09-02 15:26:03.170  1182  1182 V BluetoothStatusReceiver: Received android.bluetooth.adapter.action.STATE_CHANGED
,09-02 15:26:03.170  1182  1182 D BluetoothStatusReceiver: AdapterStateChanged :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 13
,09-02 15:26:03.170  1019  1485 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.intelligenceservice, hostingType: broadcast
,09-02 15:26:03.180  1019  1485 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-02 15:26:03.180  1019  1485 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-02 15:26:03.180  1019  1485 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-02 15:26:03.180  1019  1485 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-02 15:26:03.190  6352  6352 E Zygote  : MountEmulatedStorage()
,09-02 15:26:03.190  6352  6352 E Zygote  : v2
09-02 15:26:03.190  6352  6352 I libpersona: KNOX_SDCARD checking this for 10003
09-02 15:26:03.190  6352  6352 I libpersona: KNOX_SDCARD not a persona
,09-02 15:26:03.190  6352  6352 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51
,09-02 15:26:03.190  1019  1485 I ActivityManager: Start proc com.samsung.android.intelligenceservice for broadcast com.samsung.android.intelligenceservice/.useranalysis.predictor.PlacePredictor$BtConnectionReceiver: pid=6352 uid=10003 gids={50003, 9997, 3002, 3003, 1023, 1028, 1015, 1007, 3001} abi=armeabi-v7a
,09-02 15:26:03.200  6352  6352 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051,
,09-02 15:26:03.200  6352  6352 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,09-02 15:26:03.230  6352  6352 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-02 15:26:03.230  6352  6352 D ActivityThread: Added TimaKeyStore provider
,09-02 15:26:03.260  6352  6352 D UserAnalysis.PlaceProvider: PlaceProvider onCreate()
,09-02 15:26:03.290  6352  6352 D UserAnalysis.SecureDbManager: Key for secure DB is newly created
,09-02 15:26:03.290  6352  6352 D UserAnalysis.SecurePlaceDbHelper: SecurePlaceDbHelper() 
09-02 15:26:03.290  6352  6352 D UserAnalysis: Create SecureDbHelper
,09-02 15:26:03.290  2636  2782 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
,09-02 15:26:03.290  2636  2782 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-02 15:26:03.290  2636  2782 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
,09-02 15:26:03.300  2636  2782 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
09-02 15:26:03.300  2636  2782 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-02 15:26:03.300  2636  2782 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
09-02 15:26:03.300  2636  2782 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
09-02 15:26:03.300  2636  2782 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-02 15:26:03.300  2636  2782 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
09-02 15:26:03.300  2636  2782 W bt-btif : ag scb idx 1 not allocated
09-02 15:26:03.300  2636  2782 W bt-btif : ag scb idx 2 not allocated
09-02 15:26:03.300  2636  2782 E bt-btif : BTA AG is already disabled, ignoring ...
,09-02 15:26:03.300  2636  2825 I bt_userial_mct: exiting userial_read_thread
09-02 15:26:03.300  2636  2825 D bt_userial_mct: Leaving userial_evt_read_thread()
09-02 15:26:03.300  2636  2706 D bt_userial_mct: userial_close_reader Joined userial reader thread: 0
,09-02 15:26:03.300  2636  2785 I bt_vendor: hw_epilog_process
09-02 15:26:03.300  2636  2706 D bt_userial_mct: userial_close
,09-02 15:26:03.300  2636  2706 I bt_vendor: bt-vendor : BT_VND_OP_USERIAL_CLOSE btSocType: 0
09-02 15:26:03.300  6352  6352 D IntelligenceServiceApplication: onCreate()
,09-02 15:26:03.310  1019  1485 D ActivityManager: startProcessLocked calleePkgName: com.google.android.apps.maps, hostingType: broadcast
,09-02 15:26:03.310  1019  1485 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-02 15:26:03.310  1019  1485 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-02 15:26:03.310  1019  1485 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-02 15:26:03.310  1019  1485 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-02 15:26:03.310  6352  6352 D IntelligenceServiceApplication: no applications having user consent for prediction
,09-02 15:26:03.320  1883  6351 I art     : Explicit concurrent mark sweep GC freed 66104(3MB) AllocSpace objects, 87(4MB) LOS objects, 40% free, 14MB/24MB, paused 1.759ms total 84.503ms
09-02 15:26:03.320  6368  6368 E Zygote  : MountEmulatedStorage()
09-02 15:26:03.320  6368  6368 E Zygote  : v2
09-02 15:26:03.320  6368  6368 I libpersona: KNOX_SDCARD checking this for 10107
09-02 15:26:03.320  6368  6368 I libpersona: KNOX_SDCARD not a persona
09-02 15:26:03.320  6368  6368 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51
,09-02 15:26:03.330  1019  1485 I ActivityManager: Start proc com.google.android.apps.maps for broadcast com.google.android.apps.maps/com.google.android.apps.gmm.iamhere.ble.StartBleServiceReceiver: pid=6368 uid=10107 gids={50107, 9997, 3003, 1028, 1015, 3002, 3001} abi=armeabi-v7a
,09-02 15:26:03.330  6368  6368 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051
,09-02 15:26:03.330  6368  6368 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
09-02 15:26:03.330  1019  3105 D ActivityManager: retrieveServiceLocked(): component = com.samsung.android.intelligenceservice/com.samsung.android.placedetection.main.service.ServiceManager; callingUser = 0; userId(target) = 0
,09-02 15:26:03.330  6352  6352 V PlaceDetection v1.0.19 : [PlaceDetection::stopService] Service stopped.
,09-02 15:26:03.340  6352  6352 V PlaceDetection v1.0.19 : [PlaceDetectionManager::removeDetectionListener] PlaceDetectionListener removed.
,09-02 15:26:03.340  1019  3093 I ActivityManager: Killing 5015:com.sec.android.gallery3d/u0a44 (adj 15): empty #31
,09-02 15:26:03.360  6368  6368 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-02 15:26:03.360  6368  6368 D ActivityThread: Added TimaKeyStore provider
,09-02 15:26:03.510  6212  6212 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,09-02 15:26:03.540  1019  1319 D ActivityManager: bindService callerProcessName:com.google.android.apps.maps, calleePkgName: com.google.android.gms, action: null
09-02 15:26:03.540  1019  1319 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GetToken; callingUser = 0; userId(target) = 0
,09-02 15:26:03.540  2636  2706 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: Off
09-02 15:26:03.540  2636  2706 I bt_vendor: bluetooth satus is on
,09-02 15:26:03.540  2636  2706 I bt_vendor: bt-vendor : resetting BT status
09-02 15:26:03.540  2636  2706 I bt_vendor: Starting hciattach daemon
09-02 15:26:03.540  2636  2706 I bt_vendor: try to set false
,09-02 15:26:03.540  2636  2706 I bt_vendor: Starting hciattach daemon
09-02 15:26:03.540  1019  1319 W ActivityManager: userId = 0, bbcId = -10000
09-02 15:26:03.540  2636  2706 I bt_vendor: try to set false
09-02 15:26:03.540  1019  1319 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-02 15:26:03.540  1019  1319 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.apps.maps, destAppInfo.processName = com.google.android.gms
,09-02 15:26:03.540  2636  2706 I bt_vendor: cleanup
09-02 15:26:03.540  2636  2782 I GKI_LINUX: gki_task task_id=0 [BTU] terminating
09-02 15:26:03.540  2636  2706 I GKI_LINUX: GKI_exit_task 0 done
,09-02 15:26:03.540  2636  2706 I GKI_LINUX: GKI_shutdown(): task [BTU] terminated,
,09-02 15:26:03.550  1883  1883 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.,
,09-02 15:26:03.550  1883  1883 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,09-02 15:26:03.550  2636  2703 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = DISABLED, isTurningOn=false, isTurningOff=true
,09-02 15:26:03.550  2636  2703 D BtConfig.SecureMode: isSecureModeOn:false,
09-02 15:26:03.550  2636  2703 D BluetoothAdapterService: mProfilesStarted : true supportedProfileServices.length : 12
,09-02 15:26:03.550  2636  2703 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.gatt.GattService
09-02 15:26:03.550  2636  2703 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.gatt.GattService
09-02 15:26:03.550  2636  2703 W BluetoothAdapterService: Not skipping com.android.bluetooth.gatt.GattService
,09-02 15:26:03.560  1019  3105 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,09-02 15:26:03.560  1019  3105 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.gatt.GattService; callingUser = 0; userId(target) = 0
,09-02 15:26:03.560  1019  3105 W ActivityManager: userId = 0, bbcId = -10000
09-02 15:26:03.560  1019  3105 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-02 15:26:03.560  1019  3105 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-02 15:26:03.560  2636  2703 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hfp.HeadsetService
09-02 15:26:03.560  2636  2703 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
09-02 15:26:03.560  2636  2636 D BtGatt.DebugUtils: handleDebugAction() action=null
,09-02 15:26:03.560  2636  2703 W BluetoothAdapterService: Not skipping com.android.bluetooth.hfp.HeadsetService
,09-02 15:26:03.560  1019  2952 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
09-02 15:26:03.560  1019  2952 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = 0
09-02 15:26:03.560  2636  2636 D BtGatt.GattService: Received stop request...Stopping profile...
,09-02 15:26:03.560  2636  2636 D BtGatt.GattService: stop()
09-02 15:26:03.560  2636  2636 D BtGatt.AdvertiseManager: advertise clients cleared
,09-02 15:26:03.560  1019  2952 W ActivityManager: userId = 0, bbcId = -10000
09-02 15:26:03.560  1019  2952 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-02 15:26:03.560  1019  2952 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-02 15:26:03.560  2636  2703 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.a2dp.A2dpService
09-02 15:26:03.560  2636  2703 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
,09-02 15:26:03.560  2636  2636 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@a523621
,09-02 15:26:03.570  2636  2703 W BluetoothAdapterService: Not skipping com.android.bluetooth.a2dp.A2dpService
,09-02 15:26:03.570  2636  2636 D HeadsetService: Received stop request...Stopping profile...
09-02 15:26:03.570  1019  1319 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,09-02 15:26:03.570  1019  1319 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
,09-02 15:26:03.570  1019  1319 W ActivityManager: userId = 0, bbcId = -10000
09-02 15:26:03.570  1019  1319 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-02 15:26:03.570  1019  1319 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-02 15:26:03.570  2636  2703 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hid.HidService
09-02 15:26:03.570  2636  2703 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
,09-02 15:26:03.570  2636  2703 W BluetoothAdapterService: Not skipping com.android.bluetooth.hid.HidService
,09-02 15:26:03.570  2636  2636 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@a523621
09-02 15:26:03.570  1019  1019 D AudioService: onServiceDisconnected: Bluetooth profile: 1
09-02 15:26:03.570  1019  1485 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
09-02 15:26:03.570  1019  1485 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hid.HidService; callingUser = 0; userId(target) = 0
,09-02 15:26:03.570  1019  1485 W ActivityManager: userId = 0, bbcId = -10000
09-02 15:26:03.570  1019  1485 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-02 15:26:03.570  1019  1485 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-02 15:26:03.580  1296  1296 D HeadsetProfile: Bluetooth service disconnected
09-02 15:26:03.580  2636  2703 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hdp.HealthService
09-02 15:26:03.580  2636  2703 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
,09-02 15:26:03.580  2636  2703 W BluetoothAdapterService: Not skipping com.android.bluetooth.hdp.HealthService
,09-02 15:26:03.580  1019  1082 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,09-02 15:26:03.580  1019  1082 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hdp.HealthService; callingUser = 0; userId(target) = 0
,09-02 15:26:03.580  1019  1082 W ActivityManager: userId = 0, bbcId = -10000
,09-02 15:26:03.580  1019  1082 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-02 15:26:03.580  1019  1082 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-02 15:26:03.580  2636  2703 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.pan.PanService
,09-02 15:26:03.580  2636  2703 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.pan.PanService
,09-02 15:26:03.580  2636  2703 W BluetoothAdapterService: Not skipping com.android.bluetooth.pan.PanService
,09-02 15:26:03.590  1019  3213 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,09-02 15:26:03.590  1019  3213 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pan.PanService; callingUser = 0; userId(target) = 0
,09-02 15:26:03.590  1019  3213 W ActivityManager: userId = 0, bbcId = -10000
09-02 15:26:03.590  1019  3213 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-02 15:26:03.590  1019  3213 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
09-02 15:26:03.590  2636  2703 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.map.BluetoothMapService
09-02 15:26:03.590  2636  2703 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
,09-02 15:26:03.590  2636  2703 W BluetoothAdapterService: Not skipping com.android.bluetooth.map.BluetoothMapService
,09-02 15:26:03.590  1019  3109 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,09-02 15:26:03.590  1019  3109 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.map.BluetoothMapService; callingUser = 0; userId(target) = 0
,09-02 15:26:03.600  1019  3109 W ActivityManager: userId = 0, bbcId = -10000
,09-02 15:26:03.600  1019  3109 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-02 15:26:03.600  1019  3109 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-02 15:26:03.600  2636  2703 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.broadcom.bt.service.sap.SapService
,09-02 15:26:03.600  2636  2703 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
,09-02 15:26:03.600  2636  2703 W BluetoothAdapterService: Not skipping com.broadcom.bt.service.sap.SapService
,09-02 15:26:03.600  1019  2905 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,09-02 15:26:03.600  1019  2905 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.broadcom.bt.service.sap.SapService; callingUser = 0; userId(target) = 0
,09-02 15:26:03.600  1019  2905 W ActivityManager: userId = 0, bbcId = -10000
,09-02 15:26:03.600  1019  2905 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-02 15:26:03.600  1019  2905 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-02 15:26:03.600  2636  2703 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hfpclient.HeadsetClientService
09-02 15:26:03.600  2636  2703 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfpclient.HeadsetClientService
,09-02 15:26:03.600  2636  2703 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.hfpclient.HeadsetClientService
09-02 15:26:03.600  2636  2703 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.a2dp.A2dpSinkService
09-02 15:26:03.600  2636  2703 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpSinkService
09-02 15:26:03.600  2636  2703 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.a2dp.A2dpSinkService
09-02 15:26:03.610  2636  2703 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.sapclient.SapClientService
09-02 15:26:03.610  2636  2703 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.sapclient.SapClientService
09-02 15:26:03.610  6368  6368 D StrictMode: StrictMode policy violation; ~duration=195 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
09-02 15:26:03.610  6368  6368 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
09-02 15:26:03.610  6368  6368 D StrictMode: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182)
09-02 15:26:03.610  6368  6368 D StrictMode: 	at libcore.io.IoUtils.canOpenReadOnly(IoUtils.java:165)
09-02 15:26:03.610  6368  6368 D StrictMode: 	at dalvik.system.DexPathList.findLibrary(DexPathList.java:383)
09-02 15:26:03.610  6368  6368 D StrictMode: 	at dalvik.system.BaseDexClassLoader.findLibrary(BaseDexClassLoader.java:77)
09-02 15:26:03.610  6368  6368 D StrictMode: 	at java.lang.Runtime.loadLibrary(Runtime.java:360)
09-02 15:26:03.610  6368  6368 D StrictMode: 	at java.lang.System.loadLibrary(System.java:989)
09-02 15:26:03.610  6368  6368 D StrictMode: 	at com.google.android.libraries.social.jni.crashreporter.NativeCrashHandler.a(PG:189)
09-02 15:26:03.610  6368  6368 D StrictMode: 	at com.google.android.libraries.social.jni.crashreporter.NativeCrashHandler.a(PG:1060)
09-02 15:26:03.610  6368  6368 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:82)
09-02 15:26:03.610  6368  6368 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:195)
09-02 15:26:03.610  6368  6368 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:164)
09-02 15:26:03.610  6368  6368 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
09-02 15:26:03.610  6368  6368 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
09-02 15:26:03.610  6368  6368 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
09-02 15:26:03.610  6368  6368 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
09-02 15:26:03.610  6368  6368 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-02 15:26:03.610  6368  6368 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
09-02 15:26:03.610  6368  6368 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
09-02 15:26:03.610  6368  6368 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-02 15:26:03.610  6368  6368 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
09-02 15:26:03.610  6368  6368 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
09-02 15:26:03.610  6368  6368 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
09-02 15:26:03.610  6368  6368 D StrictMode: StrictMode policy violation; ~duration=188 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
09-02 15:26:03.610  6368  6368 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
09-02 15:26:03.610  6368  6368 D StrictMode: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182)
09-02 15:26:03.610  6368  6368 D StrictMode: 	at libcore.io.IoUti,ls.canOpenReadOnly(IoUtils.java:165)
09-02 15:26:03.610  6368  6368 D StrictMode: 	at dalvik.system.DexPathList.findLibrary(DexPathList.java:383)
09-02 15:26:03.610  6368  6368 D StrictMode: 	at dalvik.system.BaseDexClassLoader.findLibrary(BaseDexClassLoader.java:77)
09-02 15:26:03.610  6368  6368 D StrictMode: 	at java.lang.Runtime.loadLibrary(Runtime.java:360)
09-02 15:26:03.610  6368  6368 D StrictMode: 	at java.lang.System.loadLibrary(System.java:989)
09-02 15:26:03.610  6368  6368 D StrictMode: 	at com.google.android.apps.gmm.map.util.jni.NativeHelper.initialize(PG:48)
09-02 15:26:03.610  6368  6368 D StrictMode: 	at com.google.android.apps.gmm.map.l.g.<clinit>(PG:92)
09-02 15:26:03.610  6368  6368 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:189)
09-02 15:26:03.610  6368  6368 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:1211)
09-02 15:26:03.610  6368  6368 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:195)
09-02 15:26:03.610  6368  6368 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:164)
09-02 15:26:03.610  6368  6368 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
09-02 15:26:03.610  6368  6368 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
09-02 15:26:03.610  6368  6368 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
09-02 15:26:03.610  6368  6368 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
09-02 15:26:03.610  6368  6368 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-02 15:26:03.610  6368  6368 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
09-02 15:26:03.610  6368  6368 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
09-02 15:26:03.610  6368  6368 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-02 15:26:03.610  6368  6368 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
09-02 15:26:03.610  6368  6368 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
09-02 15:26:03.610  6368  6368 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
09-02 15:26:03.610  6368  6368 D StrictMode: StrictMode policy violation; ~duration=140 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
09-02 15:26:03.610  6368  6368 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
09-02 15:26:03.610  6368  6368 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
09-02 15:26:03.610  6368  6368 D StrictMode: 	at java.io.File.doAccess(File.java:283)
09-02 15:26:03.610  6368  6368 D StrictMode: 	at java.io.File.exists(File.java:363)
09-02 15:26:03.610  6368  6368 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:1366)
09-02 15:26:03.610  6368  6368 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:1389)
09-02 15:26:03.610  6368  6368 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:1331)
09-02 15:26:03.610  6368  6368 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:190)
09-02 15:26:03.610  6368  6368 D StrictMode: 	at com.google.android.apps.gmm.shared.f.h.a(PG:150)
09-02 15:26:03.610  6368  6368 D StrictMode: 	at com.google.android.apps.gmm.map.l.s.a(PG:7682)
09-02 15:26:03.610  6368  6368 D StrictMode: 	at com.google.b.a.ca.a(PG:125)
09-02 15:26:03.610  6368  6368 D StrictMode: 	at com.google.android.apps.gmm.map.l.g.a(PG:1530)
09-02 15:26:03.610  6368  6368 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:189)
09-02 15:26:03.610  6368  6368 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:1211)
09-02 15:26:03.610  6368  6368 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:195)
09-02 15:26:03.,610  6368  6368 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:164)
09-02 15:26:03.610  6368  6368 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
09-02 15:26:03.610  6368  6368 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
09-02 15:26:03.610  6368  6368 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
09-02 15:26:03.610  6368  6368 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
09-02 15:26:03.610  6368  6368 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-02 15:26:03.610  6368  6368 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
09-02 15:26:03.610  6368  6368 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
09-02 15:26:03.610  6368  6368 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-02 15:26:03.610  6368  6368 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
09-02 15:26:03.610  6368  6368 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
09-02 15:26:03.610  6368  6368 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
09-02 15:26:03.610  6368  6368 D StrictMode: StrictMode policy violation; ~duration=140 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
09-02 15:26:03.610  6368  6368 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
09-02 15:26:03.610  6368  6368 D StrictMode: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182)
09-02 15:26:03.610  6368  6368 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:442)
09-02 15:26:03.610  6368  6368 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
09-02 15:26:03.610  6368  6368 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:1332)
09-02 15:26:03.610  6368  6368 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:190)
09-02 15:26:03.610  6368  6368 D StrictMode: 	at com.google.android.apps.gmm.shared.f.h.a(PG:150)
09-02 15:26:03.610  6368  6368 D StrictMode: 	at com.google.android.apps.gmm.map.l.s.a(PG:7682)
09-02 15:26:03.610  6368  6368 D StrictMode: 	at com.google.b.a.ca.a(PG:125)
09-02 15:26:03.610  6368  6368 D StrictMode: 	at com.google.android.apps.gmm.map.l.g.a(PG:1530)
09-02 15:26:03.610  6368  6368 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:189)
09-02 15:26:03.610  6368  6368 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:1211)
09-02 15:26:03.610  6368  6368 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:195)
09-02 15:26:03.610  6368  6368 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:164)
09-02 15:26:03.610  6368  6368 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
09-02 15:26:03.610  6368  6368 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
09-02 15:26:03.610  6368  6368 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
09-02 15:26:03.610  6368  6368 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
09-02 15:26:03.610  6368  6368 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-02 15:26:03.610  6368  6368 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
09-02 15:26:03.610  6368  6368 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
09-02 15:26:03.610  6368  6368 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-02 15:26:03.610  6368  6368 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
09-02 15:26:03.610  6368  6368 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
09-02 15:26:03.610  6368  6368 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
09-02 15:26:03.610  6368  6368 D StrictMode: StrictMode policy violation; ~duration=139 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
09-02 15:26:03.610  6368  6368 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
09-02 15:26:03.610  6368  6368 D StrictMode: 	at libcore.io.BlockGuardOs.fstat(BlockGuardOs.java:132)
09-02 15:26:03.610  6368  6368 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:445)
09-02 15:26:03.610  6368  6368 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
09-02 15:26:03.610  6368  6368 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:1332)
09-02 15:26:03.610  6368  6368 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:190)
09-02 15:26:03.610  6368  6368 D StrictMode: 	at com.google.android.apps.gmm.shared.f.h.a(PG:150)
09-02 15:26:03.610  6368  6368 D StrictMode: 	at com.google.android.apps.gmm.map.l.s.a(PG:7682)
09-02 15:26:03.610  6368  6368 D StrictMode: 	at com.google.b.a.ca.a(PG:125)
09-02 15:26:03.610  6368  6368 D StrictMode: 	at com.google.android.apps.gmm.map.l.g.a(PG:1530)
09-02 15:26:03.610  6368  6368 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:189)
09-02 15:26:03.610  6368  6368 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:1211)
09-02 15:26:03.610  6368  6368 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:195)
09-02 15:26:03.610  6368  6368 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:164)
09-02 15:26:03.610  6368  6368 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
09-02 15:26:03.610  6368  6368 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
09-02 15:26:03.610  6368  6368 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
09-02 15:26:03.610  6368  6368 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
09-02 15:26:03.610  6368  6368 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-02 15:26:03.610  6368  6368 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
09-02 15:26:03.610  6368  6368 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
09-02 15:26:03.610  6368  6368 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-02 15:26:03.610  6368  6368 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
09-02 15:26:03.610  6368  6368 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
09-02 15:26:03.610  6368  6368 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
09-02 15:26:03.610  6368  6368 D StrictMode: StrictMode policy violation; ~duration=137 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
09-02 15:26:03.610  6368  6368 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
09-02 15:26:03.610  6368  6368 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
09-02 15:26:03.610  6368  6368 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:472)
09-02 15:26:03.610  6368  6368 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
09-02 15:26:03.610  6368  6368 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
09-02 15:26:03.610  6368  6368 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
09-02 15:26:03.610  6368  6368 D StrictMode: 	at com.google.r.k.c(PG:1187)
09-02 15:26:03.610  6368  6368 D StrictMode: 	at com.google.r.k.a(PG:2107)
09-02 15:26:03.610  6368  6368 D StrictMode: 	at com.google.v.a.a.eq.<init>(PG:23)
09-02 15:26:03.610  6368  6368 D StrictMode: 	at com.google.v.a.a.eq.a(PG:12397)
09-02 15:26:03.610  6368  6368 D StrictMode: 	at com.google.r.v.a(PG:1206)
09-02 15:26:03.610  6368  6368 D StrictMode: 	at com.google.r.y.a(PG:2233)
09-02 15:26:03.610  6368  6368 D StrictMode: 	at com.google.r.e.b(PG:170)
09-02 15:26:03.610  6368  6368 D StrictMode: 	at com.google.r.e.b(PG:13188)
09-02 15:26:03.610  6368  6368 D StrictMode: 	at com.google.android.apps.gmm.shared.f.h.a(PG:151)
09-02 15:26:03.610  6368  6368 D StrictMode: 	at com.google.android.apps.gmm.map.l.s.a(PG:7682)
09-02 15:26:03.610  6368  6368 D StrictMode: 	at com.google.b.a.ca.a(PG:125)
09-02 15:26:03.610  6368  6368 D StrictMode: 	at com.google.android.apps.gmm.map.l.g.a(PG:1530)
09-02 15:26:03.610  6368  6368 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:189)
09-02 15:26:03.610  6368  6368 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:1211)
09-02 15:26:03.610  6368  6368 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:195)
09-02 15:26:03.610  6368  6368 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:164)
09-02 15:26:03.610  6368  6368 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
09-02 15:26:03.610  6368  6368 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
09-02 15:26:03.610  6368  6368 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
09-02 15:26:03.610  6368  6368 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
09-02 15:26:03.610  6368  6368 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-02 15:26:03.610  6368  6368 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
09-02 15:26:03.610  6368  6368 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
09-02 15:26:03.610  6368  6368 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-02 15:26:03.610  6368  6368 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
09-02 15:26:03.610  6368  6368 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
09-02 15:26:03.610  6368  6368 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
09-02 15:26:03.610  1019  2952 I ActivityManager: Killing 5467:com.google.android.partnersetup/u0a15 (adj 15): empty #31
09-02 15:26:03.610  6368  6368 D StrictMode: StrictMode policy violation; ~duration=135 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
09-02 15:26:03.610  6368  6368 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
09-02 15:26:03.610  6368  6368 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
09-02 15:26:03.610  6368  6368 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:472)
09-02 15:26:03.610  6368  6368 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
09-02 15:26:03.610  6368  6368 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
09-02 15:26:03.610  6368  6368 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
09-02 15:26:03.610  6368  6368 D StrictMode: 	at com.google.r.k.c(PG:1187)
09-02 15:26:03.610  6368  6368 D StrictMode: 	at com.google.r.k.b(PG:14147)
09-02 15:26:03.610  6368  6368 D StrictMode: 	at com.google.r.k.c(PG:583)
09-02 15:26:03.610  6368  6368 D StrictMode: 	at com.google.v.a.a.eq.<init>(PG:40)
09-02 15:26:03.610  6368  6368 D StrictMode: 	at com.google.v.a.a.eq.a(PG:12397)
09-02 15:26:03.610  6368  6368 D StrictMode: 	at com.google.r.v.a(PG:1206)
09-02 15:26:03.610  6368  6368 D StrictMode: 	at com.google.r.y.a(PG:2233)
09-02 15:26:03.610  6368  6368 D StrictMode: 	at com.google.r.e.b(PG:170)
09-02 15:26:03.610  6368  6368 D StrictMode: 	at com.google.r.e.b(PG:13188)
09-02 15:26:03.610  6368  6368 D StrictMode: 	at com.google.android.apps.gmm.shared.f.h.a(PG:151)
09-02 15:26:03.610  6368  6368 D StrictMode: 	at com.google.android.apps.gmm.map.l.s.a(PG:7682)
09-02 15:26:03.610  6368  6368 D StrictMode: 	at com.google.b.a.ca.a(PG:125)
09-02 15:26:03.610  6368  6368 D StrictMode: 	at com.google.android.apps.gmm.map.l.g.a(PG:1530)
09-02 15:26:03.610  6368  6368 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:189)
09-02 15:26:03.610  6368  6368 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:1211)
09-02 15:26:03.610  6368  6368 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:195)
09-02 15:26:03.610  6368  6368 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:164)
09-02 15:26:03.610  6368  6368 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
09-02 15:26:03.610  6368  6368 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
09-02 15:26:03.610  6368  6368 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
09-02 15:26:03.610  6368  6368 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
09-02 15:26:03.610  6368  6368 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-02 15:26:03.610  6368  6368 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
09-02 15:26:03.610  6368  6368 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
09-02 15:26:03.610  6368  6368 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-02 15:26:03.610  6368  6368 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
09-02 15:26:03.610  6368  6368 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
09-02 15:26:03.610  6368  6368 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
09-02 15:26:03.610  2636  2703 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.sapclient.SapClientService
09-02 15:26:03.610  2636  2703 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hid.HidDevService
09-02 15:26:03.610  6368  6368 D StrictMode: StrictMode policy violation; ~duration=112 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
09-02 15:26:03.610  6368  6368 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
09-02 15:26:03.610  6368  6368 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
09-02 15:26:03.610  6368  6368 D StrictMode: 	at java.io.File.doAccess(File.java:283)
09-02 15:26:03.610  6368  6368 D StrictMode: 	at java.io.File.exists(File.java:363)
09-02 15:26:03.610  6368  6368 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:1366)
09-02 15:26:03.610  6368  6368 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:1389)
09-02 15:26:03.610  6368  6368 D StrictMode: 	at android.app.ContextImpl.getFileStreamPath(ContextImpl.java:1497)
09-02 15:26:03.610  6368  6368 D StrictMode: 	at android.content.ContextWrapper.getFileStreamPath(ContextWrapper.java:206)
09-02 15:26:03.610  6368  6368 D StrictMode: 	at com.google.android.apps.gmm.map.l.s.a(PG:7690)
09-02 15:26:03.610  6368  6368 D StrictMode: 	at com.google.b.a.ca.a(PG:125)
09-02 15:26:03.610  6368  6368 D StrictMode: 	at com.google.android.apps.gmm.map.l.g.a(PG:1530)
09-02 15:26:03.610  6368  6368 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:189)
09-02 15:26:03.610  6368  6368 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:1211)
09-02 15:26:03.610  6368  6368 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:195)
09-02 15:26:03.610  6368  6368 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:164)
09-02 15:26:03.610  6368  6368 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
09-02 15:26:03.610  6368  6368 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
09-02 15:26:03.610  6368  6368 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
09-02 15:26:03.610  6368  6368 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
09-02 15:26:03.610  6368  6368 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-02 15:26:03.610  6368  6368 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
09-02 15:26:03.610  6368  6368 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
09-02 15:26:03.610  6368  6368 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-02 15:26:03.610  6368  6368 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
09-02 15:26:03.610  6368  6368 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
09-02 15:26:03.610  6368  6368 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
09-02 15:26:03.610  2636  2703 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidDevService
09-02 15:26:03.610  2636  2703 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.hid.HidDevService
09-02 15:26:03.610  2636  2703 D BluetoothAdapterState: Stopping profile services that were post enabled
09-02 15:26:03.610  2636  2636 E BluetoothAdapterService(173159969): processProfileServiceStateChanged() serviceName=com.android.bluetooth.gatt.GattService, state=10, doUpdate=false
09-02 15:26:03.610  2636  2636 D A2dpService: Received stop request...Stopping profile...
09-02 15:26:03.610  1883  1883 D EasyUnlockReceiver: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.easyunlock.authorization.BluetoothStateChangeReceiver (has extras) }.
09-02 15:26:03.610  2636  2716 D A2dpStateMachine: Exit Disconnected: -1
09-02 15:26:03.620  2636  2636 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@a523621
09-02 15:26:03.620  1883  1883 D BtServices: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.proximity.BluetoothServicesAdapterStateChangeReceiver (has extras) }.
09-02 15:26:03.620  1019  1019 D BluetoothA2dp: Proxy object disconnected
09-02 15:26:03.620  1019  1019 D AudioService: onServiceDisconnected: Bluetooth profile: 2
09-02 15:26:03.620  2636  2636 E BluetoothAdapterService(173159969): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hfp.HeadsetService, state=10, doUpdate=true
09-02 15:26:03.620  2636  2636 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
09-02 15:26:03.620  2636  2636 D BluetoothAdapterService: Profile still running: com.android.bluetooth.hid.HidService
09-02 15:26:03.620  2850  2850 D BluetoothA2dp: Proxy object disconnected
09-02 15:26:03.620  1296  1296 D BluetoothA2dp: Proxy object disconnected
09-02 15:26:03.620  1296  1296 D A2dpProfile: Bluetooth service disconnected
09-02 15:26:03.630  2636  2636 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
09-02 15:26:03.630  2636  2636 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
09-02 15:26:03.630  2636  2636 D HidService: Received stop request...Stopping profile...
09-02 15:26:03.630  2636  2636 D HidService: Stopping Bluetooth HidService
09-02 15:26:03.630  2636  2636 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
09-02 15:26:03.630  2636  2636 W bt-btif : cleanup: HH disabling or disabled already, status = 0
09-02 15:26:03.630  2636  2636 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
09-02 15:26:03.630  2636  2636 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@a523621
09-02 15:26:03.630  2636  2636 D HealthService: Received stop request...Stopping profile...
09-02 15:26:03.630  1296  1296 D BluetoothInputDevice: Proxy object disconnected
09-02 15:26:03.630  1296  1296 D HidProfile: Bluetooth service disconnected
09-02 15:26:03.630  2636  2636 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@a523621
09-02 15:26:03.630  2636  2636 D PanService: Received stop request...Stopping profile...
09-02 15:26:03.630  2636  2636 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@a523621
09-02 15:26:03.630  1019  1019 D BluetoothPan: BluetoothPAN Proxy object disconnected
09-02 15:26:03.630  1019  3213 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
09-02 15:26:03.630  2636  2636 D BluetoothMapService: Received stop request...Stopping profile...
09-02 15:26:03.630  1296  1296 D BluetoothPan: BluetoothPAN Proxy object disconnected
09-02 15:26:03.630  1296  1296 D PanProfile: Bluetooth service disconnected
09-02 15:26:03.640  1019  3213 W ActivityManager: userId = 0, bbcId = -10000
09-02 15:26:03.640  1019  3213 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-02 15:26:03.640  1019  3213 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-02 15:26:03.650  2636  2636 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@a523621
09-02 15:26:03.650  1296  1296 D BluetoothMap: Proxy object disconnected
09-02 15:26:03.650  1296  1296 D MapProfile: Bluetooth service disconnected
09-02 15:26:03.650  2636  2636 D SapService: Received stop request...Stopping profile...
09-02 15:26:03.650  2636  2636 D SapService: Stopping Bluetooth SapService
09-02 15:26:03.650  2636  2636 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@a523621
09-02 15:26:03.650  2636  2636 E BluetoothAdapterService(173159969): processProfileServiceStateChanged() serviceName=com.android.bluetooth.a2dp.A2dpService, state=10, doUpdate=true
09-02 15:26:03.650  2636  2636 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
09-02 15:26:03.650  2636  2636 D BluetoothAdapterService: Profile still running: com.android.bluetooth.hid.HidService
09-02 15:26:03.650  2636  2636 D BluetoothA2dp: Proxy object disconnected
09-02 15:26:03.650  2636  2636 D BluetoothAdapterService: Bluetooth A2dp source service disconnected
09-02 15:26:03.650  1296  1296 D Bluetoothsap: BluetoothSAP Proxy object disconnected
09-02 15:26:03.650  1296  1296 D SapProfile: Bluetooth service disconnected
09-02 15:26:03.650  2636  2717 I GKI_LINUX: gki_task task_id=2 [A2DP-MEDIA] terminating
09-02 15:26:03.650  2636  2636 I GKI_LINUX: GKI_exit_task 2 done
09-02 15:26:03.650  2636  2636 I GKI_LINUX: GKI_shutdown(): task [A2DP-MEDIA] terminated
09-02 15:26:03.650  2636  2636 E BluetoothAdapterService(173159969): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hid.HidService, state=10, doUpdate=true
09-02 15:26:03.650  2636  2636 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
09-02 15:26:03.650  2636  2636 D BluetoothAdapterService: Profile still running: com.android.bluetooth.map.BluetoothMapService
09-02 15:26:03.650  2636  2636 E BluetoothAdapterService(173159969): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hdp.HealthService, state=10, doUpdate=true
09-02 15:26:03.650  2636  2636 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
09-02 15:26:03.650  2636  2636 D BluetoothAdapterService: Profile still running: com.android.bluetooth.map.BluetoothMapService
09-02 15:26:03.650  2636  2636 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
09-02 15:26:03.650  2636  2636 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
09-02 15:26:03.660  2636  2636 E BluetoothAdapterService(173159969): processProfileServiceStateChanged() serviceName=com.android.bluetooth.pan.PanService, state=10, doUpdate=true
09-02 15:26:03.660  2636  2636 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
09-02 15:26:03.660  2636  2636 D BluetoothAdapterService: Profile still running: com.android.bluetooth.map.BluetoothMapService
09-02 15:26:03.660  2636  2636 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
09-02 15:26:03.660  2636  2636 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
09-02 15:26:03.660  2636  2636 E BluetoothAdapterService(173159969): processProfileServiceStateChanged() serviceName=com.android.bluetooth.map.BluetoothMapService, state=10, doUpdate=true
09-02 15:26:03.660  2636  2636 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
09-02 15:26:03.660  2636  2636 D BluetoothAdapterService: Profile still running: com.broadcom.bt.service.sap.SapService
09-02 15:26:03.660  2636  2636 E BluetoothAdapterService(173159969): processProfileServiceStateChanged() serviceName=com.broadcom.bt.service.sap.SapService, state=10, doUpdate=true
09-02 15:26:03.660  2636  2636 W BluetoothSAPServiceJni: ## WARNING : cleanupNative(L251): Cleaning up Bluetooth SAP Interface...##
09-02 15:26:03.660  2636  2636 W BluetoothSAPServiceJni: ## WARNING : cleanupNative(L257): Cleaning up Bluetooth SAP callback object##
09-02 15:26:03.660  2636  2703 D BluetoothAdapterState: CURRENT_STATE=PENDING,MSG = STOPPED, isTurningOn=false, isTurningOff=true
09-02 15:26:03.660  2636  2703 D BluetoothAdapterProperties: Setting state to 10
09-02 15:26:03.660  2636  2703 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 10
09-02 15:26:03.660  2636  2703 D BluetoothAdapterService: Bluetooth PBAP supproted is true
09-02 15:26:03.660  2636  2703 D BluetoothAdapterService: updateAdapterState state is 10
09-02 15:26:03.660  1296  6395 D Bluetoothsap: onBluetoothStateChange: up=false
09-02 15:26:03.660  1296  6395 D Bluetoothsap: Unbinding service...
09-02 15:26:03.660  2636  2703 D BluetoothAdapterService: Autoconnection is available 
09-02 15:26:03.660  2636  2703 D BluetoothAdapterService: updateAdapterState prevState = 13newState = 10
09-02 15:26:03.660  2636  2703 I BluetoothAdapterState: Entering OffState
09-02 15:26:03.660  1433  1453 D BluetoothAdapter: onBluetoothStateChange: up=false
09-02 15:26:03.660  1433  1453 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
09-02 15:26:03.660  1296  1307 D BluetoothAdapter: onBluetoothStateChange: up=false
09-02 15:26:03.660  1296  1307 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
09-02 15:26:03.660  1444  1456 D BluetoothAdapter: onBluetoothStateChange: up=false
09-02 15:26:03.660  1444  1456 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
09-02 15:26:03.670  6212  6220 D BluetoothAdapter: onBluetoothStateChange: up=false
09-02 15:26:03.670  6212  6220 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
09-02 15:26:03.670  6212  6220 D BluetoothLeAdvertiser: stop All Advertising :: standalone boolean value is = false
09-02 15:26:03.670  6212  6220 D BluetoothLeAdvertiser: Exit stop advertising
09-02 15:26:03.670  6212  6220 D BluetoothLeScanner: stopAllScan standalone boolean is value is = false
09-02 15:26:03.670  6212  6220 D BluetoothLeScanner: Exiting stopAllScan
09-02 15:26:03.670  1182  1659 D BluetoothAdapter: onBluetoothStateChange: up=false
09-02 15:26:03.670  1182  1659 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
09-02 15:26:03.670  1883  1898 D BluetoothAdapter: onBluetoothStateChange: up=false
09-02 15:26:03.670  1883  1898 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
09-02 15:26:03.670  1296  6395 D BluetoothPbap: onBluetoothStateChange: up=false
09-02 15:26:03.670  1019  1050 D BluetoothAdapter: onBluetoothStateChange: up=false
09-02 15:26:03.670  1019  1050 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
09-02 15:26:03.670  2850  2863 D BluetoothA2dp: onBluetoothStateChange: up=false
09-02 15:26:03.670  1296  1307 D BluetoothInputDevice: onBluetoothStateChange: up=false
09-02 15:26:03.670  2636  2892 D BluetoothA2dp: onBluetoothStateChange: up=false
09-02 15:26:03.670  1460  1476 D BluetoothAdapter: onBluetoothStateChange: up=false
09-02 15:26:03.670  1460  1476 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
09-02 15:26:03.670  2636  2710 D BluetoothAdapter: onBluetoothStateChange: up=false
09-02 15:26:03.670  2636  2710 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
09-02 15:26:03.670  1019  1050 D BluetoothA2dp: onBluetoothStateChange: up=false
09-02 15:26:03.670  2850  2863 D BluetoothAdapter: onBluetoothStateChange: up=false
09-02 15:26:03.670  2850  2863 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
09-02 15:26:03.670  1296  6395 D BluetoothA2dp: onBluetoothStateChange: up=false
09-02 15:26:03.670  1296  1307 D BluetoothMap: onBluetoothStateChange: up=false
09-02 15:26:03.680  1019  1050 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 10 receivers.
09-02 15:26:03.680  6368  6392 W com.google.a.a.b.d.a: Application name is not set. Call Builder#setApplicationName.
09-02 15:26:03.680  1019  1050 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 0 receivers.
,09-02 15:26:03.690  1019  1019 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
09-02 15:26:03.690  1019  1019 I InputMethodManagerService: [BT Setting State] State =10
09-02 15:26:03.690  1019  1019 I InputMethodManagerService: [BT Setting on -> off] mBTKeyboardCount =0, KEYBOARD_BT(0)
,09-02 15:26:03.690  1182  1182 D BluetoothAdapter: 611874534: getState() :  mService = null. Returning STATE_OFF
09-02 15:26:03.690  1182  1182 D BluetoothTile:  onBluetoothPairedDevicesChanged:
09-02 15:26:03.690  1182  1704 D BluetoothAdapter: 611874534: getState() :  mService = null. Returning STATE_OFF
,09-02 15:26:03.690  1182  1182 D BluetoothTile: onReceive : android.bluetooth.adapter.action.STATE_CHANGED,
09-02 15:26:03.690  1182  1182 D BluetoothTile:  getBluetoothState : 10
09-02 15:26:03.690  1182  1704 D BluetoothAdapter: 611874534: getState() :  mService = null. Returning STATE_OFF
09-02 15:26:03.700  1182  1182 D BluetoothAdapter: 611874534: getState() :  mService = null. Returning STATE_OFF
09-02 15:26:03.700  1182  1182 D BluetoothAdapter: 611874534: getState() :  mService = null. Returning STATE_OFF
,09-02 15:26:03.700  1954  1954 I SamsungIME: STATE_CHANGED = 10, KEYBOARD_BT(0), mBTKeyboardCount =0
09-02 15:26:03.700  1019  2903 D StatusBarManagerService: setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
,09-02 15:26:03.700  1019  1032 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=false
09-02 15:26:03.700  1182  1182 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 )
09-02 15:26:03.700  1883  2125 D BluetoothAdapter: 1052030209: getState() :  mService = null. Returning STATE_OFF
09-02 15:26:03.700  1883  2125 D BluetoothAdapter: 1052030209: getState() :  mService = null. Returning STATE_OFF
,09-02 15:26:03.700  1296  1296 V BluetoothEventManager: Received android.bluetooth.adapter.action.STATE_CHANGED
,09-02 15:26:03.700  6212  6212 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-02 15:26:03.700  1019  1031 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,09-02 15:26:03.710  1019  1031 W ActivityManager: userId = 0, bbcId = -10000
,09-02 15:26:03.710  6212  6212 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-02 15:26:03.710  1019  1031 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-02 15:26:03.710  1019  1031 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.apps.maps, destAppInfo.processName = com.google.android.gms
,09-02 15:26:03.710  1019  2905 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
09-02 15:26:03.710  1019  2905 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.nearby.discovery.service.DiscoveryService; callingUser = 0; userId(target) = 0
,09-02 15:26:03.710  2636  2706 I GKI_LINUX: gki_task task_id=1 [BTIF] terminating
09-02 15:26:03.710  1019  2905 W ActivityManager: userId = 0, bbcId = -10000
09-02 15:26:03.710  1019  2905 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-02 15:26:03.710  1019  2905 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
09-02 15:26:03.710  2636  2636 I GKI_LINUX: GKI_exit_task 1 done
09-02 15:26:03.710  2636  2636 I GKI_LINUX: GKI_shutdown(): task [BTIF] terminated
09-02 15:26:03.710  2636  2636 I BluetoothServiceJni: cleanupNative: return from cleanup
,09-02 15:26:03.710  1296  1296 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
09-02 15:26:03.710  1019  2952 D ActivityManager: startService callerProcessName:com.android.settings, calleePkgName: com.android.settings
09-02 15:26:03.710  1019  2952 D ActivityManager: retrieveServiceLocked(): component = com.android.settings/com.android.settings.bluetooth.DockService; callingUser = 0; userId(target) = 0
,09-02 15:26:03.720  1019  2952 W ActivityManager: userId = 0, bbcId = -10000
,09-02 15:26:03.720  1019  2952 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-02 15:26:03.720  1019  2952 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.settings
09-02 15:26:03.720  2636  2636 I art     : System.exit called, status: 0
09-02 15:26:03.720  2636  2636 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,09-02 15:26:03.730  1296  1296 D DockEventReceiver: finishStartingService: stopping service
,09-02 15:26:03.730  1296  1296 D BluetoothNotiBroadcastReceiver: onReceive
,09-02 15:26:03.740  1182  1182 V BluetoothStatusReceiver: Received android.bluetooth.adapter.action.STATE_CHANGED
09-02 15:26:03.740  1182  1182 D BluetoothStatusReceiver: AdapterStateChanged :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 10
,09-02 15:26:03.740  1019  3214 E JavaBinder: !!! FAILED BINDER TRANSACTION !!!
,09-02 15:26:03.750  1019  3214 E JavaBinder: !!! FAILED BINDER TRANSACTION !!!
,09-02 15:26:03.750  1019  3214 W BroadcastQueue: Exception when sending broadcast to ComponentInfo{com.android.bluetooth/com.android.bluetooth.opp.BluetoothOppReceiver}
09-02 15:26:03.750  1019  3214 W BroadcastQueue: android.os.TransactionTooLargeException
09-02 15:26:03.750  1019  3214 W BroadcastQueue: 	at android.os.BinderProxy.transactNative(Native Method)
09-02 15:26:03.750  1019  3214 W BroadcastQueue: 	at android.os.BinderProxy.transact(Binder.java:496)
09-02 15:26:03.750  1019  3214 W BroadcastQueue: 	at android.app.ApplicationThreadProxy.scheduleReceiver(ApplicationThreadNative.java:969)
09-02 15:26:03.750  1019  3214 W BroadcastQueue: 	at com.android.server.am.BroadcastQueue.processCurBroadcastLocked(BroadcastQueue.java:310)
09-02 15:26:03.750  1019  3214 W BroadcastQueue: 	at com.android.server.am.BroadcastQueue.processNextBroadcast(BroadcastQueue.java:1284)
09-02 15:26:03.750  1019  3214 W BroadcastQueue: 	at com.android.server.am.ActivityManagerService.finishReceiver(ActivityManagerService.java:20437)
09-02 15:26:03.750  1019  3214 W BroadcastQueue: 	at android.app.ActivityManagerNative.onTransact(ActivityManagerNative.java:472)
09-02 15:26:03.750  1019  3214 W BroadcastQueue: 	at com.android.server.am.ActivityManagerService.onTransact(ActivityManagerService.java:3278)
09-02 15:26:03.750  1019  3214 W BroadcastQueue: 	at android.os.Binder.execTransact(Binder.java:446)
09-02 15:26:03.750  1019  3214 D ActivityManager: startProcessLocked calleePkgName: com.android.bluetooth, hostingType: broadcast
,09-02 15:26:03.750  1019  3214 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-02 15:26:03.750  1019  3214 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-02 15:26:03.750  1019  3214 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-02 15:26:03.750  1019  3214 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-02 15:26:03.760  6403  6403 E Zygote  : MountEmulatedStorage()
09-02 15:26:03.760  6403  6403 I libpersona: KNOX_SDCARD checking this for 1002
09-02 15:26:03.760  6403  6403 E Zygote  : v2
09-02 15:26:03.760  6403  6403 I libpersona: KNOX_SDCARD not a persona
09-02 15:26:03.760  6403  6403 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51
09-02 15:26:03.760  1019  3214 I ActivityManager: Start proc com.android.bluetooth for broadcast com.android.bluetooth/.opp.BluetoothOppReceiver: pid=6403 uid=1002 gids={41002, 9997, 3003, 3002, 3001, 1028, 1015, 3005, 1016, 3008} abi=armeabi-v7a
,09-02 15:26:03.760  6403  6403 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051
,09-02 15:26:03.770  6403  6403 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,09-02 15:26:03.790  6403  6403 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-02 15:26:03.790  6403  6403 D ActivityThread: Added TimaKeyStore provider
,09-02 15:26:03.800  6403  6403 W ResourcesManager: Asset path '/system/framework/javax.obex.jar' does not exist or contains no resources.
09-02 15:26:03.800  6403  6403 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,09-02 15:26:03.820  6403  6403 I BluetoothA2dpSinkServiceJni: register_com_android_bluetooth_a2dp_sink
,09-02 15:26:03.850  6403  6403 D BtSettings.ProfileConfig: Adding GattService
,09-02 15:26:03.850  6403  6403 D BtSettings.ProfileConfig: Adding HeadsetService
09-02 15:26:03.850  6403  6403 D BtSettings.ProfileConfig: Adding A2dpService
,09-02 15:26:03.850  6403  6403 D BtSettings.ProfileConfig: Adding HidService
09-02 15:26:03.850  6403  6403 D BtSettings.ProfileConfig: Adding HealthService
09-02 15:26:03.850  6403  6403 D BtSettings.ProfileConfig: Adding PanService
,09-02 15:26:03.850  6403  6403 D BtSettings.ProfileConfig: Adding BluetoothMapService
09-02 15:26:03.850  6403  6403 D BtSettings.ProfileConfig: Adding SapService
09-02 15:26:03.850  6403  6403 D BtSettings.ProfileConfig: Adding HeadsetClientService
,09-02 15:26:03.850  6403  6403 D BtSettings.ProfileConfig: Adding A2dpSinkService
09-02 15:26:03.850  6403  6403 D BtSettings.ProfileConfig: Adding SapClientService
09-02 15:26:03.850  6403  6403 D BtSettings.ProfileConfig: Adding HidDevService
09-02 15:26:03.850  6403  6403 I BtSettings.ProfileConfig: *********Initializing Bluetooth Profile Settings*******,
,09-02 15:26:03.860  1019  1223 D SettingsProvider: name = bt_svcst_com.android.bluetooth.gatt.GattService
,09-02 15:26:03.860  1019  1223 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
09-02 15:26:03.860  1019  1223 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
09-02 15:26:03.860  1019  1223 D SettingsProvider: selectionArgs: false
,09-02 15:26:03.860  1019  1223 D SettingsProvider: selectionArgs: 1002
09-02 15:26:03.860  1019  1223 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
,09-02 15:26:03.860  1019  1223 D SettingsProvider: ret = -1
,09-02 15:26:03.860  1019  3214 D SettingsProvider: name = bt_svcst_com.android.bluetooth.hfp.HeadsetService
09-02 15:26:03.860  1019  3214 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
09-02 15:26:03.860  1019  3214 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
09-02 15:26:03.860  1019  3214 D SettingsProvider: selectionArgs: false
09-02 15:26:03.860  1019  3214 D SettingsProvider: selectionArgs: 1002
09-02 15:26:03.860  1019  3214 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
09-02 15:26:03.860  1019  3214 D SettingsProvider: ret = -1
,09-02 15:26:03.860  1019  1485 D SettingsProvider: name = bt_svcst_com.android.bluetooth.a2dp.A2dpService
09-02 15:26:03.860  1019  1485 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
09-02 15:26:03.860  1019  1485 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
09-02 15:26:03.860  1019  1485 D SettingsProvider: selectionArgs: false
09-02 15:26:03.860  1019  1485 D SettingsProvider: selectionArgs: 1002
09-02 15:26:03.860  1019  1485 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
09-02 15:26:03.860  1019  1485 D SettingsProvider: ret = -1
09-02 15:26:03.860  1019  1082 D SettingsProvider: name = bt_svcst_com.android.bluetooth.hid.HidService
09-02 15:26:03.860  1019  1082 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
09-02 15:26:03.860  1019  1082 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
09-02 15:26:03.860  1019  1082 D SettingsProvider: selectionArgs: false
09-02 15:26:03.860  1019  1082 D SettingsProvider: selectionArgs: 1002
09-02 15:26:03.860  1019  1082 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
09-02 15:26:03.860  1019  1082 D SettingsProvider: ret = -1
,09-02 15:26:03.860  1019  3093 D SettingsProvider: name = bt_svcst_com.android.bluetooth.hdp.HealthService
09-02 15:26:03.860  1019  3093 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
09-02 15:26:03.860  1019  3093 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
,09-02 15:26:03.860  1019  3093 D SettingsProvider: selectionArgs: false
09-02 15:26:03.860  1019  3093 D SettingsProvider: selectionArgs: 1002
09-02 15:26:03.860  1019  3093 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
,09-02 15:26:03.860  1019  3093 D SettingsProvider: ret = -1
,09-02 15:26:03.860  1019  3105 D SettingsProvider: name = bt_svcst_com.android.bluetooth.pan.PanService
09-02 15:26:03.860  1019  3105 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
,09-02 15:26:03.860  1019  3105 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
09-02 15:26:03.860  1019  3105 D SettingsProvider: selectionArgs: false
09-02 15:26:03.860  1019  3105 D SettingsProvider: selectionArgs: 1002
09-02 15:26:03.860  1019  3105 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
09-02 15:26:03.860  1019  3105 D SettingsProvider: ret = -1
,09-02 15:26:03.860  1019  1319 D SettingsProvider: name = bt_svcst_com.android.bluetooth.map.BluetoothMapService
09-02 15:26:03.860  1019  1319 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
09-02 15:26:03.860  1019  1319 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
09-02 15:26:03.860  1019  1319 D SettingsProvider: selectionArgs: false
09-02 15:26:03.870  1019  1319 D SettingsProvider: selectionArgs: 1002
,09-02 15:26:03.870  1019  1319 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
09-02 15:26:03.870  1019  1319 D SettingsProvider: ret = -1
,09-02 15:26:03.870  1019  1322 D SettingsProvider: name = bt_svcst_com.broadcom.bt.service.sap.SapService
09-02 15:26:03.870  1019  1322 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
09-02 15:26:03.870  1019  1322 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
09-02 15:26:03.870  1019  1322 D SettingsProvider: selectionArgs: false
09-02 15:26:03.870  1019  1322 D SettingsProvider: selectionArgs: 1002
09-02 15:26:03.870  1019  1322 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
09-02 15:26:03.870  1019  1322 D SettingsProvider: ret = -1
,09-02 15:26:03.870  1019  2903 D SettingsProvider: name = bt_svcst_com.android.bluetooth.hfpclient.HeadsetClientService
09-02 15:26:03.870  1019  2903 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
09-02 15:26:03.870  1019  1131 D WifiP2pService: InactiveState{ what=143375 }
09-02 15:26:03.870  1019  2903 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
09-02 15:26:03.870  1019  1131 D WifiP2pService: P2pEnabledState{ what=143375 }
09-02 15:26:03.870  1019  2903 D SettingsProvider: selectionArgs: false
09-02 15:26:03.880  1019  1138 D ConnectivityService: NetworkAgentInfo [WIFI () - 502] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
09-02 15:26:03.870  1019  2903 D SettingsProvider: selectionArgs: 1002
09-02 15:26:03.880  1019  1138 D ConnectivityService: NetworkAgentInfo [WIFI () - 502] got DISCONNECTED, was satisfying 3
09-02 15:26:03.870  1019  2903 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
09-02 15:26:03.870  1019  2903 D SettingsProvider: ret = -1
09-02 15:26:03.870  1019  1031 D SettingsProvider: name = bt_svcst_com.android.bluetooth.a2dp.A2dpSinkService
09-02 15:26:03.870  1019  1031 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
09-02 15:26:03.870  1019  1031 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
09-02 15:26:03.870  1019  1031 D SettingsProvider: selectionArgs: false
09-02 15:26:03.870  1019  1031 D SettingsProvider: selectionArgs: 1002
09-02 15:26:03.870  1019  1031 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
09-02 15:26:03.870  1019  1031 D SettingsProvider: ret = -1
09-02 15:26:03.870  1019  3213 D SettingsProvider: name = bt_svcst_com.android.bluetooth.sapclient.SapClientService
09-02 15:26:03.870  1019  3213 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
09-02 15:26:03.870  1019  3213 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
09-02 15:26:03.870  1019  3213 D SettingsProvider: selectionArgs: false
09-02 15:26:03.870  1019  3213 D SettingsProvider: selectionArgs: 1002
09-02 15:26:03.870   278   998 D CommandListener: Clearing all IP addresses on wlan0
09-02 15:26:03.870  1019  3213 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
09-02 15:26:03.870  1019  3213 D SettingsProvider: ret = -1
09-02 15:26:03.870  1019  2905 D SettingsProvider: name = bt_svcst_com.android.bluetooth.hid.HidDevService
09-02 15:26:03.870  1019  2905 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
09-02 15:26:03.870  1019  2905 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
09-02 15:26:03.870  1019  2905 D SettingsProvider: selectionArgs: false
09-02 15:26:03.870  1019  2905 D SettingsProvider: selectionArgs: 1002
,09-02 15:26:03.870  1019  2905 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
09-02 15:26:03.870  1019  2905 D SettingsProvider: ret = -1
09-02 15:26:03.880  1883  4369 V NativeCrypto: Read error: ssl=0xb81cf148: I/O error during system call, Connection timed out
09-02 15:26:03.880  1182  1182 D StatusBar.NetworkController: refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
09-02 15:26:03.880  1182  1182 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:"NG700"
09-02 15:26:03.880  1182  1182 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-02 15:26:03.880  1182  1182 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-02 15:26:03.880  1182  1182 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-02 15:26:03.880  1182  1182 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-02 15:26:03.880  1019  1138 E ConnectivityService: updateNetworkInfo()
09-02 15:26:03.880  1019  1138 E ConnectivityService: updateNetworkInfo()
09-02 15:26:03.880  1883  4369 V NativeCrypto: SSL shutdown failed: ssl=0xb81cf148: I/O error during system call, Broken pipe
,09-02 15:26:03.880  1883  4369 E GCM     : Wifi connection closed with errorCode 20
09-02 15:26:03.880  1019  1019 I WifiTrafficPoller: evaluateTrafficStatsPolling
,09-02 15:26:03.890  1019  3213 D ConnectivityService: reportBadNetwork(NetworkAgentInfo [WIFI () - 502]) by 10012
09-02 15:26:03.890  1019  2217 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: ValidatedState{ when=0 what=532488 arg1=10012 target=com.android.internal.util.StateMachine$SmHandler }
09-02 15:26:03.890  1019  2217 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: DefaultState{ when=0 what=532488 arg1=10012 target=com.android.internal.util.StateMachine$SmHandler }
09-02 15:26:03.890  1019  2217 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Forcing reevaluation
09-02 15:26:03.890  1019  2217 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: EvaluatingState{ when=0 what=532486 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
09-02 15:26:03.890  1019  2217 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Checking http://connectivitycheck.android.com/generate_204 on <unknown ssid>
09-02 15:26:03.890  1019  2217 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,09-02 15:26:03.890  1019  2217 I qtaguid : Tagging socket 353 with tag ffffffff00000000{4294967295,0} for uid 10012, pid: 1019, getuid(): 1000
,09-02 15:26:03.890  1019  2217 I qtaguid : Untagging socket 353
,09-02 15:26:03.890  1019  2217 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,09-02 15:26:03.900  1182  1182 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,09-02 15:26:03.900  1019  1131 D WifiP2pService: InactiveState{ what=131204 }
09-02 15:26:03.900  1182  1182 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
09-02 15:26:03.900  1019  1131 D WifiP2pService: P2pEnabledState{ what=131204 }
09-02 15:26:03.900  1182  1182 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-02 15:26:03.900  1019  1131 D WifiP2pService: sending p2p connection changed broadcast: FAILED
09-02 15:26:03.900  1182  1182 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-02 15:26:03.900  1182  1182 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-02 15:26:03.900  1182  1182 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-02 15:26:03.900  1019  1132 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
09-02 15:26:03.900  1019  1019 D WifiScanningService: SCAN_AVAILABLE : 1
09-02 15:26:03.900  1019  1154 D WifiScanningService: DefaultState got{ when=-1ms what=160007 target=com.android.internal.util.StateMachine$SmHandler }
09-02 15:26:03.900  1019  1019 D RttService: SCAN_AVAILABLE : 1
,09-02 15:26:03.900  1019  1155 D RttService: EnabledState got{ when=0 what=160513 target=com.android.internal.util.StateMachine$SmHandler }
,09-02 15:26:03.910  1019  1051 D WifiDisplayController: Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/FAILED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-02 15:26:03.910  1019  1051 D WifiDisplayAdapter: onP2pDisconnected
09-02 15:26:03.910  1019  1051 D IpRemoteDisplayController: disconnectWfdBridgeServer
09-02 15:26:03.910  1019  1051 D IpRemoteDisplayController: WfdBridgeServer is already null
,09-02 15:26:03.910  1019  1322 I ActivityManager: Killing 5553:com.google.android.apps.plus/u0a120 (adj 15): empty #31
,09-02 15:26:03.910  1883  1883 D EasyUnlockReceiver: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.easyunlock.authorization.BluetoothStateChangeReceiver (has extras) }.
,09-02 15:26:03.910  1019  1485 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,09-02 15:26:03.910  1019  1485 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.easyunlock.authorization.InitializerIntentService; callingUser = 0; userId(target) = 0
09-02 15:26:03.920  1019  1485 W ActivityManager: userId = 0, bbcId = -10000
09-02 15:26:03.920  1019  1485 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-02 15:26:03.920  1019  1485 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-02 15:26:03.920  1019  1131 D WifiP2pService: sending p2p connection changed broadcast: DISCONNECTED
,09-02 15:26:03.920  1019  1131 D WifiP2pService: P2pDisablingState
09-02 15:26:03.920  1019  1131 D WifiP2pService: P2pDisablingState{ what=147458 }
09-02 15:26:03.920  1019  1131 D WifiP2pService: p2p socket connection lost
09-02 15:26:03.920  1019  1132 E WifiNative-wlan0: do suspend true
09-02 15:26:03.920  1019  1131 D WifiP2pService: P2pDisabledState
,09-02 15:26:03.930  1019  1019 E WifiStateMachine: BroadcastReceiver : WIFI_P2P_STATE_CHANGED_ACTION is : android.net.wifi.p2p.STATE_CHANGED
,09-02 15:26:03.930  1883  6423 D EasyUnlockInitService: Handling intent for initializer IntentService.,
09-02 15:26:03.930  1019  1051 D WifiDisplayController: Received WIFI_P2P_STATE_CHANGED_ACTION: enabled=false
09-02 15:26:03.930  1883  1883 D BtServices: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.proximity.BluetoothServicesAdapterStateChangeReceiver (has extras) }.
09-02 15:26:03.930  1019  1051 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
09-02 15:26:03.930  1019  1051 D WifiDisplayController: disconnect
,09-02 15:26:03.930  1019  1051 D WifiDisplayController: updateConnection
09-02 15:26:03.930  1019  1051 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
09-02 15:26:03.930  1019  1051 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
09-02 15:26:03.930  1019  1051 D WifiDisplayController: Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: false, isConnectedToProvisioningNetwork: false]
09-02 15:26:03.930  1019  1051 D WifiDisplayAdapter: onP2pDisconnected
09-02 15:26:03.930  1019  1051 D IpRemoteDisplayController: disconnectWfdBridgeServer
09-02 15:26:03.930  1019  1051 D IpRemoteDisplayController: WfdBridgeServer is already null
,09-02 15:26:03.930  1182  1182 D AllShareCastTile: action: android.hardware.display.action.WIFI_DISPLAY_STATUS_CHANGED
09-02 15:26:03.930  1019  2903 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
09-02 15:26:03.930  1019  3214 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
09-02 15:26:03.930  1182  1182 D AllShareCastTile: wifi display status changed! scanstate : 0, ActiveDisplayState : 0
,09-02 15:26:03.940  1019  3214 W ActivityManager: userId = 0, bbcId = -10000,
09-02 15:26:03.940  1019  3214 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-02 15:26:03.940  1019  3214 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-02 15:26:03.950  1019  3093 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
09-02 15:26:03.950  1019  3093 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,09-02 15:26:03.950  1019  3093 W ActivityManager: userId = 0, bbcId = -10000
09-02 15:26:03.950  1019  3093 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-02 15:26:03.950  1019  3093 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,09-02 15:26:03.950  3631  3631 I Hs20UtilService: Starting #8
,09-02 15:26:03.950  3631  3649 I Hs20UtilService: Message received 5007
,09-02 15:26:03.960  1296  1296 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,09-02 15:26:03.960  1296  1296 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
,09-02 15:26:03.960  1296  1296 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,09-02 15:26:03.960  1296  1296 I NearbySettings: DMSUtil.isNetworkConnected - P2P: IDLE
09-02 15:26:03.960  1296  1296 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
,09-02 15:26:03.960  1296  1296 I NearbySettings: MountReceiver.onReceive - Set preference state off
09-02 15:26:03.960  1296  3038 V NearbySettings: MountReceiver.mPrefHandler - 7002
,09-02 15:26:03.960  1019  3109 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,09-02 15:26:03.960  1019  3109 W ActivityManager: userId = 0, bbcId = -10000
,09-02 15:26:03.960  1019  3109 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-02 15:26:03.960  1019  3109 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-02 15:26:03.970  1883  6423 D EasyUnlockInitService: Not initializing EasyUnlock: remote_devices=0, bluetooth_on=false
,09-02 15:26:03.970  1296  1296 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.p2p.CONNECTION_STATE_CHANGE
,09-02 15:26:03.970  1296  1296 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
,09-02 15:26:03.970  1296  1296 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,09-02 15:26:03.980  1296  1296 I NearbySettings: DMSUtil.isNetworkConnected - P2P: IDLE
09-02 15:26:03.980  1296  1296 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
09-02 15:26:03.980  1296  1296 I NearbySettings: MountReceiver.onReceive - Set preference state off
,09-02 15:26:03.980  1296  3038 V NearbySettings: MountReceiver.mPrefHandler - 7002
,09-02 15:26:03.980  1019  2952 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.app.FileShareClient, hostingType: broadcast
,09-02 15:26:03.980  1019  2952 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-02 15:26:03.980  1019  2952 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-02 15:26:03.980  1019  2952 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-02 15:26:03.980  1019  2952 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-02 15:26:03.990  6425  6425 E Zygote  : MountEmulatedStorage()
09-02 15:26:03.990  6425  6425 I libpersona: KNOX_SDCARD checking this for 10068
09-02 15:26:03.990  6425  6425 E Zygote  : v2
09-02 15:26:03.990  6425  6425 I libpersona: KNOX_SDCARD not a persona
09-02 15:26:03.990  6425  6425 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51
,09-02 15:26:04.000  6425  6425 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051,
,09-02 15:26:04.000  1019  2952 I ActivityManager: Start proc com.samsung.android.app.FileShareClient for broadcast com.samsung.android.app.FileShareClient/.ClientBroadcastReceiver: pid=6425 uid=10068 gids={50068, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,09-02 15:26:04.000  6425  6425 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,09-02 15:26:04.010  6425  6425 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-02 15:26:04.010  6425  6425 D ActivityThread: Added TimaKeyStore provider
,09-02 15:26:04.030  6425  6425 W ResourcesManager: Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
,09-02 15:26:04.040  6425  6425 D FileShare-Client: ClientBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,09-02 15:26:04.050  6425  6425 D FileShare-Client: ClientBroadcastReceiver.onReceive - disconnected
,09-02 15:26:04.070  6425  6425 D FileShare-Client: Outbound.stopDelayTimer - 
,09-02 15:26:04.070  1019  1485 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.app.FileShareServer, hostingType: broadcast
,09-02 15:26:04.080  1019  1485 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-02 15:26:04.080  1019  1485 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-02 15:26:04.080  1019  1485 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-02 15:26:04.080  1019  1485 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-02 15:26:04.090  6440  6440 E Zygote  : MountEmulatedStorage(),
,09-02 15:26:04.090  6440  6440 E Zygote  : v2
,09-02 15:26:04.090  6440  6440 I libpersona: KNOX_SDCARD checking this for 10069
09-02 15:26:04.090  6440  6440 I libpersona: KNOX_SDCARD not a persona
,09-02 15:26:04.090  6440  6440 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51
,09-02 15:26:04.090  1019  1485 I ActivityManager: Start proc com.samsung.android.app.FileShareServer for broadcast com.samsung.android.app.FileShareServer/.ServerBroadcastReceiver: pid=6440 uid=10069 gids={50069, 9997, 3003, 1028, 1015} abi=armeabi-v7a,
,09-02 15:26:04.090  6440  6440 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051
,09-02 15:26:04.100  6440  6440 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,09-02 15:26:04.110  6440  6440 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-02 15:26:04.110  6440  6440 D ActivityThread: Added TimaKeyStore provider
,09-02 15:26:04.130  6440  6440 D FileShare-Server: ServerBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,09-02 15:26:04.130  1019  1485 W ActivityManager: userId = 0, bbcId = -10000
,09-02 15:26:04.130  1019  1485 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-02 15:26:04.130  1019  1485 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.talk
09-02 15:26:04.130  1019  1485 D ActivityManager: startProcessLocked calleePkgName: com.google.android.talk, hostingType: broadcast
,09-02 15:26:04.140  1019  1485 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-02 15:26:04.140  1019  1485 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-02 15:26:04.140  1019  1485 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-02 15:26:04.140  1019  1485 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-02 15:26:04.150  6455  6455 E Zygote  : MountEmulatedStorage(),
,09-02 15:26:04.150  6455  6455 E Zygote  : v2
,09-02 15:26:04.150  6455  6455 I libpersona: KNOX_SDCARD checking this for 10104
09-02 15:26:04.150  6455  6455 I libpersona: KNOX_SDCARD not a persona
,09-02 15:26:04.150  1019  1485 I ActivityManager: Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver: pid=6455 uid=10104 gids={50104, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
09-02 15:26:04.150  1019  1485 I ActivityManager: Killing 5790:com.sec.pcw.device/1000 (adj 15): empty #31
09-02 15:26:04.150  6455  6455 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51
,09-02 15:26:04.160  6455  6455 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051
,09-02 15:26:04.160  6455  6455 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,09-02 15:26:04.180  6455  6455 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-02 15:26:04.180  6455  6455 D ActivityThread: Added TimaKeyStore provider
,09-02 15:26:04.190  6455  6455 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,09-02 15:26:04.370  6455  6478 I Babel   : MmsConfig: mnc/mcc: 0/0
,09-02 15:26:04.370  6455  6478 I Babel   : MmsConfig.loadMmsSettings
,09-02 15:26:04.380  6455  6478 I Babel   : MmsConfig.loadDeviceMmsSettings from API: mUserAgent=SAMSUNG-ANDROID-MMS/SM-A500FU, mUaProfUrl=http://wap.samsungmobile.com/uaprof/SM-A500FU.xml
09-02 15:26:04.380  6455  6478 I Babel   : MmsConfig.loadFromDatabase
,09-02 15:26:04.390  6455  6478 E Babel   : canonicalizeMccMnc: invalid mccmnc 
09-02 15:26:04.390  6455  6478 I Babel   : MmsConfig.loadFromResources
,09-02 15:26:04.390  6455  6478 E Babel   : canonicalizeMccMnc: invalid mccmnc nullnull
,09-02 15:26:04.390  6455  6478 I Babel   : MmsConfig.loadMmsSettings: mUserAgent=SAMSUNG-ANDROID-MMS/SM-A500FU, mUaProfUrl=http://wap.samsungmobile.com/uaprof/SM-A500FU.xml
,09-02 15:26:04.400  1019  3213 D ActivityManager: bindService callerProcessName:com.google.android.talk, calleePkgName: com.google.android.talk, action: null
,09-02 15:26:04.400  1019  3213 D ActivityManager: retrieveServiceLocked(): component = com.google.android.talk/com.google.android.libraries.hangouts.video.CallService; callingUser = 0; userId(target) = 0
,09-02 15:26:04.400  1019  3213 W ActivityManager: userId = 0, bbcId = -10000
,09-02 15:26:04.400  1019  3213 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-02 15:26:04.400  1019  3213 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.talk
,09-02 15:26:04.400  6455  6455 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,09-02 15:26:04.430  6455  6455 I Babel_StickerModule: App launched.
,09-02 15:26:04.440   283   680 W QCamera2Factory: getCameraInfo: E, camera_id = 0
,09-02 15:26:04.440   283   680 W QCamera2Factory: getCameraInfo: X
,09-02 15:26:04.450   283  1017 W QCamera2Factory: getCameraInfo: E, camera_id = 1
09-02 15:26:04.450   283  1017 W QCamera2Factory: getCameraInfo: X
,09-02 15:26:04.470  6455  6455 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,09-02 15:26:04.470  6455  6455 W AudioCapabilities: Unsupported mime audio/evrc
,09-02 15:26:04.470  6455  6455 W AudioCapabilities: Unsupported mime audio/qcelp
,09-02 15:26:04.480  6455  6455 W AudioCapabilities: Unsupported mime audio/mpeg-L1
,09-02 15:26:04.480  6455  6455 W AudioCapabilities: Unsupported mime audio/mpeg-L2
,09-02 15:26:04.480  6455  6455 W AudioCapabilities: Unsupported mime audio/x-ms-wma
,09-02 15:26:04.480  6455  6455 W AudioCapabilities: Unsupported mime audio/x-ima
,09-02 15:26:04.480  6455  6455 W AudioCapabilities: Unsupported mime audio/qcelp
,09-02 15:26:04.490  6455  6455 W AudioCapabilities: Unsupported mime audio/evrc
,09-02 15:26:04.490  6455  6455 W VideoCapabilities: Unsupported mime video/wvc1
,09-02 15:26:04.500  6455  6455 W VideoCapabilities: Unsupported mime video/x-ms-wmv
,09-02 15:26:04.500  6455  6455 W VideoCapabilities: Unrecognized profile/level 32768/2 for video/mp4v-es
,09-02 15:26:04.500  6455  6455 W VideoCapabilities: Unsupported mime video/wvc1
,09-02 15:26:04.510  6455  6455 W VideoCapabilities: Unsupported mime video/x-ms-wmv
,09-02 15:26:04.510  6455  6455 W VideoCapabilities: Unsupported mime video/x-ms-wmv7
,09-02 15:26:04.510  6455  6455 W VideoCapabilities: Unsupported mime video/x-ms-wmv8
,09-02 15:26:04.510  6455  6455 W VideoCapabilities: Unsupported mime video/mp43
,09-02 15:26:04.520  6455  6455 W VideoCapabilities: Unsupported mime video/sorenson
,09-02 15:26:04.520  6455  6455 W VideoCapabilities: Unsupported mime video/mp4v-esdp
,09-02 15:26:04.540  6455  6455 I VideoCapabilities: Unsupported profile 4 for video/mp4v-es
,09-02 15:26:04.560  1019  1031 D ActivityManager: bindService callerProcessName:com.google.android.talk, calleePkgName: com.google.android.talk, action: com.google.android.talk.SOFT_BIND
09-02 15:26:04.560  1019  1031 D ActivityManager: retrieveServiceLocked(): component = com.google.android.talk/com.google.android.libraries.hangouts.video.VideoChatService; callingUser = 0; userId(target) = 0
,09-02 15:26:04.560  1019  1031 W ActivityManager: userId = 0, bbcId = -10000
09-02 15:26:04.560  1019  1031 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-02 15:26:04.560  1019  1031 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.talk
,09-02 15:26:04.560  1019  3214 I ActivityManager: Killing 5088:com.samsung.android.app.assistantmenu/1000 (adj 15): empty #31
,09-02 15:26:04.720   278   994 D EnterpriseController: uids 1000
09-02 15:26:04.720   278   994 D EnterpriseController: mIsMarkChainAdded is 18 mIsBlockChainAdded is 252 netId is 0
,09-02 15:26:04.720   278   994 D Netd    : getNetworkForDns: using netid 0 for uid 1000
09-02 15:26:04.720   278   998 D CommandListener: Clearing all IP addresses on wlan0
,09-02 15:26:04.720  1019  1131 D WifiP2pService: P2pDisabledState{ what=143375 }
09-02 15:26:04.720  1019  1131 D WifiP2pService: DefaultState{ what=143375 }
,09-02 15:26:04.720  1019  2217 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "connectivitycheck.android.com": No address associated with hostname
09-02 15:26:04.720  1019  1138 E NetdConnector: NDC Command {53 network destroy 502} took too long (842ms)
09-02 15:26:04.720  1019  2217 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Validated
09-02 15:26:04.720  1019  1138 D ConnectivityService: setProvNotificationVisibleIntent: E visible=false networkType=1 extraInfo=null
09-02 15:26:04.720  1019  1138 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 502]
,09-02 15:26:04.730  1182  1182 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
09-02 15:26:04.730  1182  1182 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
09-02 15:26:04.730  1182  1698 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524292
09-02 15:26:04.730  1182  1182 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-02 15:26:04.730  1182  1182 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-02 15:26:04.730  1182  1182 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-02 15:26:04.730  1182  1182 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-02 15:26:04.730  1019  2217 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: ValidatedState{ when=-1ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
,09-02 15:26:04.730  1019  1138 D ConnectivityService: Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,09-02 15:26:04.730  3800  6269 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524292
,09-02 15:26:04.730  1019  1050 D EntConnectivity: Not allowed due to - mEnabled false - primarySimSlot false
,09-02 15:26:04.730  1019  1131 D WIFI_P2P: evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= false
,09-02 15:26:04.730  1019  1019 I WifiTrafficPoller: evaluateTrafficStatsPolling
,09-02 15:26:04.740  1019  1138 D CSLegacyTypeTracker: Removing agent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{502}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.111/24,fe80::7ef9:eff:fe37:96ac/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{true} created{true} explicitlySelected{false} }
09-02 15:26:04.740  1019  1138 D CSLegacyTypeTracker: Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 502] isDefaultNetwork=false
09-02 15:26:04.740  1019  1138 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,09-02 15:26:04.740  1460  1460 D TelephonyNetworkFactory: evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= false
09-02 15:26:04.740  1460  1460 D TelephonyNetworkFactory: Cellular needs Network for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,09-02 15:26:04.740  2107  2107 I wpa_supplicant: p2p0: State: DISCONNECTED -> DISCONNECTED
,09-02 15:26:04.750  1182  1182 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,09-02 15:26:04.750  1182  1182 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
,09-02 15:26:04.750  1019  1050 D EntConnectivity: Not allowed due to - mEnabled false - primarySimSlot false
,09-02 15:26:04.750  1182  1182 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-02 15:26:04.750  1019  1019 D Tethering: Tethering got CONNECTIVITY_ACTION_IMMEDIATE
09-02 15:26:04.750  1182  1182 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-02 15:26:04.750  1182  1182 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-02 15:26:04.750  1182  1182 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-02 15:26:04.760  1019  1139 D Tethering: MasterInitialState.processMessage what=3
,09-02 15:26:04.760  1019  1138 D ConnectivityService: nai.networkMonitor.doQuit()
09-02 15:26:04.760  1019  1138 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: doQuit - quitNow()
09-02 15:26:04.760  1019  1132 D WIFI    : evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= false
,09-02 15:26:04.760  1019  1138 E ConnectivityService: updateNetworkInfo()
09-02 15:26:04.760  1019  1138 D ConnectivityService: NetworkAgentInfo [WIFI_P2P () - 501] EVENT_NETWORK_INFO_CHANGED, going from UNKNOWN to DISCONNECTED, reason = null, [ Transports: WIFI Capabilities: WIFI_P2P&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
09-02 15:26:04.760  1019  1138 E ConnectivityService: updateNetworkInfo()
,09-02 15:26:04.760  1019  1129 V NetworkStats: updateIfacesLocked()
,09-02 15:26:04.760  1019  1129 V NetworkStats: performPollLocked(flags=0x1)
09-02 15:26:04.760  1019  1129 D NtpTrustedTime: currentTimeMillis() cache hit
,09-02 15:26:04.760  1019  1132 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
09-02 15:26:04.760  1019  1132 D SecContentProvider2: mCursor = null
,09-02 15:26:04.760  1019  1130 D NtpTrustedTime: currentTimeMillis() cache hit
,09-02 15:26:04.770  1182  1182 D StatusBar.NetworkController: EthernetConnected: false
09-02 15:26:04.770  1182  1182 D StatusBar.NetworkController: getUpdateDataNetType(): 0
09-02 15:26:04.770  1182  1182 D StatusBar.NetworkController: getUpdateDataNetType(): mDataTypeBrand = LTE
09-02 15:26:04.770  1182  1182 D StatusBar.NetworkController: updateDataNetType()
09-02 15:26:04.770  1182  1182 D StatusBar.NetworkController: NoService, mRoamingIconId = 0
09-02 15:26:04.770  1182  1182 E StatusBar.NetworkController: updateLTEICONDataNetType:0
09-02 15:26:04.770  1019  1129 D NetworkStatsFactory: UpdateStatsForKnox updated
09-02 15:26:04.770  1019  1129 D NetworkStatsFactory: UpdateStatsForKnox main else ---
,09-02 15:26:04.770  1019  1130 D NtpTrustedTime: currentTimeMillis() cache hit
09-02 15:26:04.770  1019  1130 D NtpTrustedTime: currentTimeMillis() cache hit
09-02 15:26:04.770  1019  1130 D NtpTrustedTime: currentTimeMillis() cache hit
09-02 15:26:04.770  1019  1130 V NetworkStats: advisePersistThreshold() given 9223372036854775, clamped to 2097152
,09-02 15:26:04.770  1019  1129 V NetworkStats: performPollLocked() took 12ms
09-02 15:26:04.770  1019  1129 D NtpTrustedTime: currentTimeMillis() cache hit
,09-02 15:26:04.770  1182  1182 D StatusBar.NetworkController: updateDataIcon, mDataDirectionIconId = (null) mDataConnected = false
,09-02 15:26:04.770  1182  1182 D StatusBar.NetworkController: updateTelephonySignalStrength: hasService=false ss=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte
,09-02 15:26:04.780  1182  1182 D StatusBar.NetworkController: updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal
09-02 15:26:04.780  1182  1182 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
09-02 15:26:04.780  1182  1182 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
09-02 15:26:04.780  1182  1704 D STATUSBAR-QSTileView: onStateChanged: Wi-Fi
09-02 15:26:04.780  1182  1182 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
09-02 15:26:04.780  1182  1182 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-02 15:26:04.780  1182  1182 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-02 15:26:04.780  1182  1182 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-02 15:26:04.780  1182  1182 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-02 15:26:04.780  1182  1182 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x0/(null) mQSWifiIconId=0x0/(null) mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
09-02 15:26:04.780  1182  1182 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=false enabledDesc:null
09-02 15:26:04.780  1182  1182 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-02 15:26:04.780  1182  1182 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-02 15:26:04.780  1182  1182 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-02 15:26:04.780  1182  1182 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-02 15:26:04.780  1296  1296 D WifiCredService: Action received :android.net.wifi.WIFI_STATE_CHANGED
09-02 15:26:04.780  1182  1182 D STATUSBAR-WifiQuickSettingButton: onReceive : android.net.wifi.WIFI_STATE_CHANGED
09-02 15:26:04.780  1182  1182 D STATUSBAR-WifiQuickSettingButton: Wifi onReceive(0)
,09-02 15:26:04.780  1182  1182 D HotspotTile: onReceive : 0, 0
,09-02 15:26:04.780  1019  3093 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
09-02 15:26:04.780  1019  3093 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,09-02 15:26:04.780  6212  6212 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-02 15:26:04.780  6212  6212 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-02 15:26:04.780  6212  6212 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-02 15:26:04.780  6212  6212 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-02 15:26:04.780  6212  6212 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-02 15:26:04.780  6212  6212 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-02 15:26:04.780  6212  6212 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-02 15:26:04.780  6212  6212 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-02 15:26:04.780  6212  6212 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-02 15:26:04.780  6212  6212 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-02 15:26:04.780  6212  6212 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-02 15:26:04.780  1019  3093 W ActivityManager: userId = 0, bbcId = -10000
09-02 15:26:04.780  6212  6212 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-02 15:26:04.780  6212  6212 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-02 15:26:04.780  6212  6212 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-02 15:26:04.780  6212  6212 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-02 15:26:04.780  6212  6212 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-02 15:26:04.780  6212  6212 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-02 15:26:04.780  6212  6212 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-02 15:26:04.780  6212  6212 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-02 15:26:04.780  6212  6212 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-02 15:26:04.780  6212  6212 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-02 15:26:04.780  6212  6212 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-02 15:26:04.780  1019  3093 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-02 15:26:04.780  1019  3093 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,09-02 15:26:04.790  3631  3631 I Hs20UtilService: Starting #9
,09-02 15:26:04.790  3631  3649 I Hs20UtilService: Message received 5007
,09-02 15:26:04.790  1019  1130 D NtpTrustedTime: currentTimeMillis() cache hit
,09-02 15:26:04.790  1019  1130 D NtpTrustedTime: currentTimeMillis() cache hit
,09-02 15:26:04.800  1296  1296 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
09-02 15:26:04.800  1296  1296 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
,09-02 15:26:04.800  1296  1296 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,09-02 15:26:04.800  1296  1296 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
09-02 15:26:04.800  1296  1296 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
09-02 15:26:04.800  1296  1296 I NearbySettings: MountReceiver.onReceive - Set preference state off
,09-02 15:26:04.800  1296  3038 V NearbySettings: MountReceiver.mPrefHandler - 7002
,09-02 15:26:04.830  1019  1319 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
,09-02 15:26:04.830  1019  1319 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,09-02 15:26:04.830  1019  1319 W ActivityManager: userId = 0, bbcId = -10000
09-02 15:26:04.830  1019  1319 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-02 15:26:04.830  1019  1319 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,09-02 15:26:04.830  3631  3631 I Hs20UtilService: Starting #10
,09-02 15:26:04.840  3631  3649 I Hs20UtilService: Message received 5011
,09-02 15:26:04.840  1019  1082 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.securitylogagent, hostingType: broadcast
,09-02 15:26:04.840  1019  1082 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-02 15:26:04.840  1019  1082 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-02 15:26:04.840  1019  1082 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-02 15:26:04.840  1019  1082 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-02 15:26:04.850  2107  2107 I wpa_supplicant: Blacklist: Clear (all) 
,09-02 15:26:04.850  1019  1082 I ActivityManager: Start proc com.samsung.android.securitylogagent for broadcast com.samsung.android.securitylogagent/.receivers.NetworkReceiver: pid=6483 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
,09-02 15:26:04.860  6483  6483 E Zygote  : MountEmulatedStorage(),
09-02 15:26:04.860  6483  6483 I libpersona: KNOX_SDCARD checking this for 1000
09-02 15:26:04.860  6483  6483 E Zygote  : v2
09-02 15:26:04.860  6483  6483 I libpersona: KNOX_SDCARD not a persona
,09-02 15:26:04.860  6483  6483 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51,
,09-02 15:26:04.860  6483  6483 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051,
,09-02 15:26:04.870  6483  6483 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,09-02 15:26:04.890  1460  1460 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,09-02 15:26:04.890  1460  1460 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,09-02 15:26:04.890  1460  1460 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,09-02 15:26:04.900  1460  1460 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
09-02 15:26:04.900  1460  1460 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,09-02 15:26:04.900  1460  1460 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,09-02 15:26:04.900  1460  1460 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,09-02 15:26:04.900  1460  1460 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,09-02 15:26:04.910  1460  1460 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,09-02 15:26:04.910  1460  1460 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
09-02 15:26:04.910  1460  1460 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,09-02 15:26:04.910  1460  1460 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,09-02 15:26:04.910  1460  1460 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,09-02 15:26:04.910  6483  6483 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-02 15:26:04.910  1460  1460 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
09-02 15:26:04.910  6483  6483 D ActivityThread: Added TimaKeyStore provider
,09-02 15:26:04.920  1460  1460 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,09-02 15:26:04.920  1460  1460 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,09-02 15:26:04.920  1460  1460 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,09-02 15:26:04.920  1460  1460 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,09-02 15:26:04.930  1460  1460 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,09-02 15:26:04.930  1460  1460 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,09-02 15:26:04.930  1460  1460 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,09-02 15:26:04.930  1460  1460 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,09-02 15:26:04.930  1460  1460 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,09-02 15:26:04.930  1460  1460 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,09-02 15:26:04.930  1460  1460 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,09-02 15:26:04.930  1460  1460 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,09-02 15:26:04.930  1460  1460 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,09-02 15:26:04.940  1460  1460 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,09-02 15:26:04.940  1460  1460 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,09-02 15:26:04.940  1460  1460 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,09-02 15:26:04.960  6483  6483 D SecurityLogAgent: KnoxConfiguration : Current State = 1
,09-02 15:26:04.960  6483  6483 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
09-02 15:26:04.960  2107  2107 I wpa_supplicant: p2p0: CTRL-EVENT-TERMINATING 
09-02 15:26:04.960  6483  6483 D SecurityLogAgent: StateMachine : Current State = 1
,09-02 15:26:04.960  1019  1048 D Tethering: interfaceLinkStateChanged p2p0, false
09-02 15:26:04.960  1019  1048 D Tethering: interfaceStatusChanged p2p0, false
,09-02 15:26:04.970  1019  1048 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
,09-02 15:26:04.970  6483  6483 D SecurityLogAgent: StateMachine : Changed Current State = 1
,09-02 15:26:04.970  1019  3105 I ActivityManager: Killing 5488:com.samsung.android.app.galaxyfinder/u0a32 (adj 15): empty #31
,09-02 15:26:04.980  1019  1082 W ActivityManager: userId = 0, bbcId = -10000
,09-02 15:26:04.980  1019  1082 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-02 15:26:04.980  1019  1082 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,09-02 15:26:04.980  1019  1019 W ActivityManager: userId = 0, bbcId = -10000
,09-02 15:26:04.980  1019  1019 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-02 15:26:04.980  1019  1019 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,09-02 15:26:04.990  1019  1019 W ActivityManager: userId = 0, bbcId = -10000
09-02 15:26:04.990  1019  1019 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,09-02 15:26:04.990  1019  1019 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,09-02 15:26:04.990  2107  2107 I wpa_supplicant: CTRL-EVENT-DISCONNECTED bssid=F4.99.3E reason=3 locally_generated=1
,09-02 15:26:04.990  2107  2107 I wpa_supplicant: wlan0: State: COMPLETED -> DISCONNECTED
09-02 15:26:04.990  2107  2107 I wpa_supplicant: Prev BSS - hexdump(len=6): f4 f2 6d 22 99 3e
09-02 15:26:04.990  2107  2107 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=F4.99.3E SSID=4E47373030
09-02 15:26:04.990  1019  1132 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.android.server.wifi.WifiStateMachine.insertLog:14956 com.android.server.wifi.WifiStateMachine.access$2700:217 com.android.server.wifi.WifiStateMachine$DefaultState.processMessage:6951 com.android.internal.util.StateMachine$SmHandler.processMsg:966 
09-02 15:26:04.990  2107  2107 I wpa_supplicant: wlan0: State: DISCONNECTED -> DISCONNECTED
,09-02 15:26:04.990  1019  1048 D Tethering: interfaceLinkStateChanged wlan0, false
09-02 15:26:04.990  1019  1048 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
09-02 15:26:04.990  1019  1048 D Tethering: interfaceStatusChanged wlan0, false
09-02 15:26:04.990  1019  1139 D Tethering: InitialState.processMessage what=4
,09-02 15:26:04.990  1019  1139 E Tethering: No numeric data
,09-02 15:26:04.990  1019  1019 W ActivityManager: userId = 0, bbcId = -10000
09-02 15:26:04.990  1019  1048 D Tethering: interfaceLinkStateChanged wlan0, false
09-02 15:26:04.990  1019  1019 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-02 15:26:04.990  1019  1019 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
09-02 15:26:04.990  1019  1048 D Tethering: interfaceStatusChanged wlan0, false
,09-02 15:26:04.990  1019  1048 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
,09-02 15:26:05.000  1019  1048 D Tethering: interfaceLinkStateChanged wlan0, false
09-02 15:26:05.000  1019  1048 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
09-02 15:26:05.000  1019  1048 D Tethering: interfaceStatusChanged wlan0, false
,09-02 15:26:05.000  1019  1139 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
09-02 15:26:05.000  1019  1139 D Tethering: clearTetheredNotification()
,09-02 15:26:05.000  1019  1129 V NetworkStats: performPollLocked(flags=0x1)
,09-02 15:26:05.000  1019  1129 D NtpTrustedTime: currentTimeMillis() cache hit
,09-02 15:26:05.000  1019  1129 D NetworkStatsFactory: UpdateStatsForKnox updated
09-02 15:26:05.000  1182  1182 D HotspotTile: onReceive : android.net.conn.TETHER_STATE_CHANGED
09-02 15:26:05.000  1182  1182 D HotspotTile: updateTetherState():false, false
,09-02 15:26:05.000  1019  1129 D NetworkStatsFactory: UpdateStatsForKnox main else ---
,09-02 15:26:05.000  1019  1019 W ActivityManager: userId = 0, bbcId = -10000
09-02 15:26:05.000  1019  1019 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-02 15:26:05.000  1019  1019 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,09-02 15:26:05.000  1019  1129 D NtpTrustedTime: currentTimeMillis() cache hit
09-02 15:26:05.000  1019  1129 V NetworkStats: performPollLocked() took 6ms
,09-02 15:26:05.010  1019  1019 W ActivityManager: userId = 0, bbcId = -10000
09-02 15:26:05.010  1019  1019 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-02 15:26:05.010  1019  1019 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,09-02 15:26:05.010  1019  1130 D NtpTrustedTime: currentTimeMillis() cache hit
,09-02 15:26:05.010  1019  1130 D NtpTrustedTime: currentTimeMillis() cache hit
,09-02 15:26:05.010  1019  1019 W ActivityManager: userId = 0, bbcId = -10000
09-02 15:26:05.010  1019  1019 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-02 15:26:05.010  1019  1019 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,09-02 15:26:05.020  1019  1019 W ActivityManager: userId = 0, bbcId = -10000
,09-02 15:26:05.020  1019  1019 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-02 15:26:05.020  1019  1019 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,09-02 15:26:05.020  1019  1019 W ActivityManager: userId = 0, bbcId = -10000
,09-02 15:26:05.020  1019  1019 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-02 15:26:05.020  1019  1019 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,09-02 15:26:05.020  1019  1019 W ActivityManager: userId = 0, bbcId = -10000
,09-02 15:26:05.020  1019  1019 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-02 15:26:05.030  1019  1019 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,09-02 15:26:05.030  1019  1019 W ActivityManager: userId = 0, bbcId = -10000
,09-02 15:26:05.030  1019  1019 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-02 15:26:05.030  1019  1019 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,09-02 15:26:05.030   288   288 E SMD     : DCD OFF
,09-02 15:26:05.030  1019  1019 W ActivityManager: userId = 0, bbcId = -10000
,09-02 15:26:05.040  1019  1019 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-02 15:26:05.040  1019  1019 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,09-02 15:26:05.040  1019  1019 W ActivityManager: userId = 0, bbcId = -10000
,09-02 15:26:05.040  1019  1019 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-02 15:26:05.040  1019  1019 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,09-02 15:26:05.040  1019  1019 W ActivityManager: userId = 0, bbcId = -10000
,09-02 15:26:05.040  1019  1019 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-02 15:26:05.040  1019  1019 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
09-02 15:26:05.040   273   273 I rmt_storage: rmt_storage_connect_cb: clnt_h=0x5 conn_h=0xb814b7c8
,09-02 15:26:05.040   273   273 I rmt_storage: rmt_storage_rw_iovec_cb: /boot/modem_fs2: clnt_h=0x2: req_h=0xa msg_id=3: R/W request received
09-02 15:26:05.050   273   273 I rmt_storage: wakelock acquired: 1, error no: 42
,09-02 15:26:05.050   273   325 I rmt_storage: rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2 Unblock worker thread (th_id: -1206601592)
09-02 15:26:05.050  1019  1019 W ActivityManager: userId = 0, bbcId = -10000
09-02 15:26:05.050  1019  1019 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-02 15:26:05.050  1019  1019 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,09-02 15:26:05.090   273   325 I rmt_storage: rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2: req_h=0xa msg_id=3: Bytes written = 917504
,09-02 15:26:05.090   273   325 I rmt_storage: rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2: req_h=0xa msg_id=3: Send response: res=0 err=0
09-02 15:26:05.090   273   325 I rmt_storage: rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2 About to block rmt_storage client thread (th_id: -1206601592) wakelock released: 1, error no: 0
09-02 15:26:05.090   273   325 I rmt_storage: 
,09-02 15:26:05.100   273   273 I rmt_storage: rmt_storage_disconnect_cb: clnt_h=0x5 conn_h=0xb814b7c8
,09-02 15:26:05.190  2107  2107 I wpa_supplicant: Blacklist: Clear (all) 
,09-02 15:26:05.250  1019  1138 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,09-02 15:26:05.260  1019  1019 I ApplicationPolicy: updateDataUsageMap
,09-02 15:26:05.270  6212  6212 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-02 15:26:05.280  1019  1045 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
,09-02 15:26:05.280  1019  1046 D ActivityManager: startProcessLocked calleePkgName: com.sec.pcw.device, hostingType: broadcast
,09-02 15:26:05.280  6212  6212 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-02 15:26:05.280  1019  1046 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-02 15:26:05.280  1019  1046 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-02 15:26:05.280  1019  1046 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-02 15:26:05.280  1019  1046 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-02 15:26:05.300  3151  3151 I DBG_DM  : [com.wssyncmldm.XDMService(936/lIllIlllIIllllIlIlIl)] WiFi network Connected : false
,09-02 15:26:05.300  1019  1048 D Tethering: interfaceLinkStateChanged wlan0, false,
09-02 15:26:05.300  1019  1048 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
09-02 15:26:05.300  1019  1048 D Tethering: interfaceStatusChanged wlan0, false
09-02 15:26:05.300  2107  2107 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING 
09-02 15:26:05.310  1019  1046 I ActivityManager: Start proc com.sec.pcw.device for broadcast com.sec.pcw.device/.receiver.SYSTEMReceiver: pid=6515 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
09-02 15:26:05.310  3151  3151 I DBG_DM  : [com.wssyncmldm.XDMService(952/llIlIllllllllllllllI)] Bluetooth Data Connected : false
09-02 15:26:05.310  6515  6515 E Zygote  : MountEmulatedStorage()
09-02 15:26:05.310  6515  6515 I libpersona: KNOX_SDCARD checking this for 1000
09-02 15:26:05.310  6515  6515 E Zygote  : v2
09-02 15:26:05.310  6515  6515 I libpersona: KNOX_SDCARD not a persona
09-02 15:26:05.320  6515  6515 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51
,09-02 15:26:05.320  6515  6515 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051
,09-02 15:26:05.320  6515  6515 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,09-02 15:26:05.340  6515  6515 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-02 15:26:05.340  6515  6515 D ActivityThread: Added TimaKeyStore provider
,09-02 15:26:05.360  6515  6515 I PCWCLIENTTRACE_LOG: DEFAULT_LOGON : true
09-02 15:26:05.360  6515  6515 I PCWCLIENTTRACE_LOG: DEFAULT_LOGLEVEL : 3
09-02 15:26:05.360  6515  6515 I PCWCLIENTTRACE_DMDBOpenHelper: new DMDBOpenHelper instance
,09-02 15:26:05.370  6515  6515 I PCWCLIENTTRACE_PushUtil: SPPPushClient is installed : true
,09-02 15:26:05.380  6515  6515 I PCWCLIENTTRACE_PushUtil: sales region : global
09-02 15:26:05.380  6515  6515 I PCWCLIENTTRACE_PushUtil: getPushTypeList : [SPP, GCM]
09-02 15:26:05.380  6515  6515 I PCWCLIENTTRACE_SYSTEMReceiver: [onReceive] - android.net.conn.CONNECTIVITY_CHANGE
,09-02 15:26:05.380  1019  2905 I splitIntent: Split this intent : android.net.conn.CONNECTIVITY_CHANGE, mSplitNum[0]=8, mSplitNum[1]=17, mSplitNum[2]=25, mBgSplitQueueNum=3 divideNum= 8 r.nextReceiver= 1 receivers.size=33
,09-02 15:26:05.380  1019  2905 I splitIntent: finish to split intent : android.net.conn.CONNECTIVITY_CHANGE !! Enqueue -> schedule it!!
09-02 15:26:05.380  1019  2905 D ActivityManager: startProcessLocked calleePkgName: com.google.android.music, hostingType: broadcast
,09-02 15:26:05.380  1019  2905 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-02 15:26:05.380  1019  2905 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-02 15:26:05.380  1019  2905 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-02 15:26:05.380  1019  2905 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-02 15:26:05.380  6515  6530 I PCWCLIENTTRACE_SYSTEMReceiver: noConnectivity : true
,09-02 15:26:05.390  6532  6532 E Zygote  : MountEmulatedStorage(),
,09-02 15:26:05.390  6532  6532 E Zygote  : v2
,09-02 15:26:05.400  6532  6532 I libpersona: KNOX_SDCARD checking this for 10111
09-02 15:26:05.400  6532  6532 I libpersona: KNOX_SDCARD not a persona
,09-02 15:26:05.400  1019  2905 I ActivityManager: Start proc com.google.android.music:main for broadcast com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver: pid=6532 uid=10111 gids={50111, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,09-02 15:26:05.400  6532  6532 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51
09-02 15:26:05.400  1019  2905 I ActivityManager: Killing 5808:com.samsung.android.bbc.bbcagent/1000 (adj 15): empty #31
,09-02 15:26:05.400  6532  6532 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051
,09-02 15:26:05.400  6532  6532 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,09-02 15:26:05.400  1019  1046 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.fotaclient, hostingType: broadcast
,09-02 15:26:05.400  1019  1046 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-02 15:26:05.400  1019  1046 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-02 15:26:05.400  1019  1046 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-02 15:26:05.400  1019  1046 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-02 15:26:05.410  6532  6532 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-02 15:26:05.420  6532  6532 D ActivityThread: Added TimaKeyStore provider
,09-02 15:26:05.420  6547  6547 E Zygote  : MountEmulatedStorage()
,09-02 15:26:05.420  6547  6547 E Zygote  : v2
09-02 15:26:05.420  6547  6547 I libpersona: KNOX_SDCARD checking this for 10009
09-02 15:26:05.420  6547  6547 I libpersona: KNOX_SDCARD not a persona
,09-02 15:26:05.420  6547  6547 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51,
09-02 15:26:05.430  1019  1046 I ActivityManager: Start proc com.sec.android.fotaclient for broadcast com.sec.android.fotaclient/.FotaRegisterReceiver: pid=6547 uid=10009 gids={50009, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,09-02 15:26:05.430  6547  6547 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051,
,09-02 15:26:05.430  6547  6547 E SELinux : [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
09-02 15:26:05.430  1019  1046 D ActivityManager: startProcessLocked calleePkgName: com.android.email, hostingType: broadcast
09-02 15:26:05.430  1722  1722 D accuweather: [KK AccuPhone]>>> WCW:32 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
09-02 15:26:05.440  1019  1046 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-02 15:26:05.440  1019  1046 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-02 15:26:05.440  1019  1046 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-02 15:26:05.440  1019  1046 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-02 15:26:05.450   316   316 I art     : Explicit concurrent mark sweep GC freed 8731(372KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 622us total 22.371ms
,09-02 15:26:05.450  6547  6547 D TimaKeyStoreProvider: TimaSignature is unavailable
09-02 15:26:05.450  6547  6547 D ActivityThread: Added TimaKeyStore provider
,09-02 15:26:05.460   316   316 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 591us total 17.019ms
,09-02 15:26:05.480   316   316 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 600us total 16.994ms,
,09-02 15:26:05.490  6562  6562 E Zygote  : MountEmulatedStorage(),
09-02 15:26:05.490  6562  6562 E Zygote  : v2
09-02 15:26:05.490  6562  6562 I libpersona: KNOX_SDCARD checking this for 10145
09-02 15:26:05.490  6562  6562 I libpersona: KNOX_SDCARD not a persona
,09-02 15:26:05.500  1019  1046 I ActivityManager: Start proc com.android.email for broadcast com.android.email/.EmailConnectivityManager: pid=6562 uid=10145 gids={50145, 9997, 3003, 1028, 1015, 1023, 3002, 3001, 1003} abi=armeabi-v7a,
09-02 15:26:05.500  6562  6562 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51
,09-02 15:26:05.500  1019  1132 E WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:0
09-02 15:26:05.500  1019  1132 D WifiNative-wlan0: callSECApiBoolean - ID [21]
09-02 15:26:05.500  1019  1132 E WifiConfigStore: setLastSelectedConfiguration -1
,09-02 15:26:05.500  6562  6562 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051
,09-02 15:26:05.500  6562  6562 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,09-02 15:26:05.510  1722  1722 D accuweather: [KK AccuPhone]>>> U:4106 [0:0] getPWC : surface = 0, remote = 1
,09-02 15:26:05.510  6455  6455 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-02 15:26:05.510  1722  1722 D accuweather: [KK AccuPhone]>>> U:4284 [0:0] Store PWC = 1
,09-02 15:26:05.510  1722  1722 D accuweather: [KK AccuPhone]>>> U:4158 [0:0] addPWC = 1
09-02 15:26:05.510  1722  1722 D accuweather: [KK AccuPhone]>>> UIM:306 [0:0]  action:androidnetconnCONNECTIVITY_CHANGE
,09-02 15:26:05.520  1182  1182 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x0/(null) mQSWifiIconId=0x0/(null) mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
09-02 15:26:05.520  1182  1182 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=false enabledDesc:null
09-02 15:26:05.520  1182  1182 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-02 15:26:05.520  1182  1182 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-02 15:26:05.520  1182  1182 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-02 15:26:05.520  1182  1182 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-02 15:26:05.520  1182  1182 D STATUSBAR-WifiQuickSettingButton: onReceive : android.net.wifi.WIFI_STATE_CHANGED
09-02 15:26:05.520  1182  1182 D STATUSBAR-WifiQuickSettingButton: Wifi onReceive(1)
,09-02 15:26:05.520  1182  1704 D STATUSBAR-QSTileView: onStateChanged: Wi-Fi
09-02 15:26:05.520  1182  1182 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
,09-02 15:26:05.520  1182  1182 D HotspotTile: onReceive : 1, 0
,09-02 15:26:05.520  1883  2125 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,09-02 15:26:05.530  1296  1296 D WifiCredService: Action received :android.net.wifi.WIFI_STATE_CHANGED
,09-02 15:26:05.530  6212  6212 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-02 15:26:05.530  6212  6212 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-02 15:26:05.530  6562  6562 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-02 15:26:05.530  6562  6562 D ActivityThread: Added TimaKeyStore provider
,09-02 15:26:05.530  1722  1722 D accuweather: [KK AccuPhone]>>> WC:30 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,09-02 15:26:05.540  1722  1722 D accuweather: [KK AccuPhone]>>> UIMEM:104 [0:0] The widget does not exist in idle!!
,09-02 15:26:05.540  1019  1485 D ActivityManager: startProcessLocked calleePkgName: com.android.chrome, hostingType: broadcast
,09-02 15:26:05.540  1019  1485 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-02 15:26:05.540  1019  1485 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-02 15:26:05.540  1019  1485 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-02 15:26:05.540  1019  1485 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-02 15:26:05.550  1321  1333 D daemonapp: [MSC_Daemon]>>> WCP:1254 [0:0] cp update : count : 1, pt : 13
,09-02 15:26:05.560  6577  6577 E Zygote  : MountEmulatedStorage()
09-02 15:26:05.560  6577  6577 E Zygote  : v2
09-02 15:26:05.560  6577  6577 I libpersona: KNOX_SDCARD checking this for 10081
09-02 15:26:05.560  6577  6577 I libpersona: KNOX_SDCARD not a persona
,09-02 15:26:05.560  6577  6577 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51
,09-02 15:26:05.560  6577  6577 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051
,09-02 15:26:05.570  1019  1485 I ActivityManager: Start proc com.android.chrome for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher: pid=6577 uid=10081 gids={50081, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,09-02 15:26:05.570  6577  6577 E SELinux : [DEBUG] get_category: variable seinfo: chrome sensitivity: NULL, cateogry: NULL
,09-02 15:26:05.570  1722  1722 D accuweather: [KK AccuPhone]>>> U:4250 [0:0] Store PWC succeed
,09-02 15:26:05.580  6562  6562 W ResourcesManager: Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
,09-02 15:26:05.580  6562  6562 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
09-02 15:26:05.580  6562  6562 W ResourcesManager: Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
09-02 15:26:05.580  6562  6562 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
09-02 15:26:05.580  6562  6562 W ResourcesManager: Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,09-02 15:26:05.590  6577  6577 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-02 15:26:05.590  6577  6577 D ActivityThread: Added TimaKeyStore provider
,09-02 15:26:05.630  1019  1485 I ActivityManager: Killing 5820:com.samsung.android.provider.shootingmodeprovider/u0a152 (adj 15): empty #31
,09-02 15:26:05.630  3653  3653 I KLMS-2.5.183: : KLMSAbstractReciever(): onReceive(): Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.samsung.klmsagent/.listner.MainReciver (has extras) } | timestamp: Fri Sep 02 15:26:05 GMT+02:00 2016
,09-02 15:26:05.630  1019  3214 D ActivityManager: startService callerProcessName:com.samsung.klmsagent, calleePkgName: com.samsung.klmsagent
,09-02 15:26:05.630  1019  3214 D ActivityManager: retrieveServiceLocked(): component = com.samsung.klmsagent/com.samsung.klmsagent.services.KLMSIntentService; callingUser = 0; userId(target) = 0
,09-02 15:26:05.630  1019  3214 W ActivityManager: userId = 0, bbcId = -10000
09-02 15:26:05.630  1019  3214 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,09-02 15:26:05.630  1019  3214 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.klmsagent, destAppInfo.processName = com.samsung.klmsagent
,09-02 15:26:05.640  3653  3653 I KLMS-2.5.183: : KLMSAbstractReciever(): onReceive().END.
,09-02 15:26:05.640  1019  3105 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.soagent, hostingType: broadcast
,09-02 15:26:05.650  3653  3653 I KLMS-2.5.183: : KLMSIntentService(): onCreate()
,09-02 15:26:05.650  1019  3105 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-02 15:26:05.650  1019  3105 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-02 15:26:05.650  1019  3105 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-02 15:26:05.650  1019  3105 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-02 15:26:05.650  3653  3653 I KLMS-2.5.183: : KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,09-02 15:26:05.650  6532  6532 I MusicStore: Database version: 108
,09-02 15:26:05.650  3653  3653 I KLMS-2.5.183: : KLMSUtility(): isTestMode(): product_ship: true | testApk: false
,09-02 15:26:05.660  3653  6596 I KLMS-2.5.183: : KLMSIntentService(): onHandleIntent().START: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.samsung.klmsagent/.services.KLMSIntentService (has extras) }
,09-02 15:26:05.660  6597  6597 E Zygote  : MountEmulatedStorage(),
09-02 15:26:05.660  6597  6597 E Zygote  : v2
09-02 15:26:05.660  6597  6597 I libpersona: KNOX_SDCARD checking this for 10034
09-02 15:26:05.660  6597  6597 I libpersona: KNOX_SDCARD not a persona,
,09-02 15:26:05.660  6597  6597 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51,
,09-02 15:26:05.670  1019  3105 I ActivityManager: Start proc com.sec.android.soagent for broadcast com.sec.android.soagent/.RegisterReceiver: pid=6597 uid=10034 gids={50034, 9997, 3003} abi=armeabi-v7a
,09-02 15:26:05.670  6597  6597 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051
,09-02 15:26:05.670  6597  6597 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,09-02 15:26:05.680  3653  6596 I KLMS-2.5.183: : KLMSIntentService(): NETWORK_STATE_CHANGED_ACTION
,09-02 15:26:05.690  1019  2905 D RCPManagerService: exchangeData() failure , invalid userId
,09-02 15:26:05.690  3653  6596 I KLMS-2.5.183: : KLMSUtility(): isNetworkAvailable() - WIFI : false| MOBILE : false| ETHERNET : false
09-02 15:26:05.690  1019  1322 D ActivityManager: bindService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music, action: null
09-02 15:26:05.690  1019  1322 D ActivityManager: retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.net.NetworkMonitor; callingUser = 0; userId(target) = 0
,09-02 15:26:05.690  1019  1322 W ActivityManager: userId = 0, bbcId = -10000
09-02 15:26:05.690  1019  1322 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-02 15:26:05.690  1019  1322 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,09-02 15:26:05.700  6597  6597 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-02 15:26:05.700  3653  6596 I KLMS-2.5.183: : StateImplV2(): networkChangeListener().END
,09-02 15:26:05.700  6597  6597 D ActivityThread: Added TimaKeyStore provider
,09-02 15:26:05.700  3653  3653 I KLMS-2.5.183: : KLMSIntentService(): onDestroy()
,09-02 15:26:05.720  1019  1484 D RCPManagerService: exchangeData() failure , invalid userId
,09-02 15:26:05.740  6597  6597 I SO_AGENT: [com.sec.android.soagent.RegisterReceiver(95/onReceive)] Network is not available
,09-02 15:26:05.740  1019  1082 I ActivityManager: Killing 5521:com.sec.knox.bridge/1000 (adj 15): empty #31
,09-02 15:26:05.780  3217  6619 I DBG_POLICYDM: [com.policydm.XDMService(515/xdmProtoIsWIFIConnected)] WiFi network Connected : false
09-02 15:26:05.780  6532  6532 W ResourcesManager: Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
09-02 15:26:05.780  6532  6532 W ResourcesManager: Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,09-02 15:26:05.780  5840  5840 E SPPClientService: [[SystemStateMoniter]] SystemStateMonitorService : noConnect? : true
,09-02 15:26:05.790  3217  6619 I DBG_POLICYDM: [com.policydm.XDMService(525/xdmProtoIsMobileDataConnected)] Mobile Data Connected : false
,09-02 15:26:05.790  6044  6044 I SA      : [DM] init START
,09-02 15:26:05.790  3217  6619 E DBG_POLICYDM: [com.policydm.XDMBroadcastReceiver$2(104/run)] network is unserviceable
,09-02 15:26:05.800  3217  6619 I DBG_POLICYDM: [com.policydm.XDMService(481/isNetworkChanged)] a previous network is 2, current network is 0
,09-02 15:26:05.800  3217  6619 E DBG_POLICYDM: [com.policydm.XDMService(483/isNetworkChanged)] network changed.... 
,09-02 15:26:05.800  1019  2905 D ActivityManager: startService callerProcessName:com.sec.spp.push, calleePkgName: com.sec.spp.push
,09-02 15:26:05.800  1019  2905 D ActivityManager: retrieveServiceLocked(): component = com.sec.spp.push/com.sec.spp.push.monitor.SystemStateMonitorService; callingUser = 0; userId(target) = 0
,09-02 15:26:05.800  1019  2905 W ActivityManager: userId = 0, bbcId = -10000
09-02 15:26:05.800  1019  2905 W ActivityManager: NORMAL SET : dst_category = 1023, src_allowCategory = 0,701-1023
09-02 15:26:05.800  1019  2905 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.spp.push, destAppInfo.processName = com.sec.spp.push
,09-02 15:26:05.800  1019  2952 D ActivityManager: startProcessLocked calleePkgName: com.google.android.apps.magazines, hostingType: broadcast
,09-02 15:26:05.810  1019  2952 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-02 15:26:05.810  1019  2952 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-02 15:26:05.810  1019  2952 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-02 15:26:05.810  1019  2952 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-02 15:26:05.810  6044  6044 I SA      : [DM] This device is not a Vodafone
,09-02 15:26:05.820  5840  6622 E SPPClientService: [[SystemStateMonitorService]] No Active Internet
,09-02 15:26:05.830  1019  1082 D RCPManagerService: exchangeData() failure , invalid userId,
09-02 15:26:05.830  6624  6624 E Zygote  : MountEmulatedStorage()
09-02 15:26:05.830  6624  6624 E Zygote  : v2,
09-02 15:26:05.830  6624  6624 I libpersona: KNOX_SDCARD checking this for 10113,
09-02 15:26:05.830  6624  6624 I libpersona: KNOX_SDCARD not a persona
,09-02 15:26:05.830  6624  6624 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51
,09-02 15:26:05.840  6624  6624 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051,
09-02 15:26:05.840  1019  2952 I ActivityManager: Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=6624 uid=10113 gids={50113, 9997, 3003, 1028, 1015} abi=armeabi-v7a
09-02 15:26:05.840  6532  6532 V JNIHelp : Registering com/google/android/gms/org/conscrypt/NativeCrypto's 255 native methods...
09-02 15:26:05.840  6624  6624 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,09-02 15:26:05.850  6044  6044 W ResourceType: Failure getting entry for 0x7f060010 (t=5 e=16) (error -75)
,09-02 15:26:05.850  6044  6044 W ResourceType: Failure getting entry for 0x7f060008 (t=5 e=8) (error -75)
,09-02 15:26:05.850  6044  6044 W ResourceType: Failure getting entry for 0x7f060009 (t=5 e=9) (error -75)
09-02 15:26:05.850  6044  6044 W ResourceType: Failure getting entry for 0x7f06000c (t=5 e=12) (error -75)
,09-02 15:26:05.850  6044  6044 W ResourceType: Failure getting entry for 0x7f06000d (t=5 e=13) (error -75)
09-02 15:26:05.850  6044  6044 W ResourceType: Failure getting entry for 0x7f060002 (t=5 e=2) (error -75)
,09-02 15:26:05.850  6044  6044 W ResourceType: Failure getting entry for 0x7f060014 (t=5 e=20) (error -75)
,09-02 15:26:05.850  6044  6044 W ResourceType: No package identifier when getting value for resource number 0x00000000
,09-02 15:26:05.850  6044  6044 W ResourceType: Failure getting entry for 0x7f060027 (t=5 e=39) (error -75)
,09-02 15:26:05.850  6044  6044 W ResourceType: Failure getting entry for 0x7f060028 (t=5 e=40) (error -75)
,09-02 15:26:05.860  6624  6624 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-02 15:26:05.860  6624  6624 D ActivityThread: Added TimaKeyStore provider
,09-02 15:26:05.860  1019  1223 D RCPManagerService: exchangeData() failure , invalid userId
,09-02 15:26:05.870  6044  6044 W ResourceType: Failure getting entry for 0x7f060029 (t=5 e=41) (error -75)
,09-02 15:26:05.870  6044  6044 W ResourceType: Failure getting entry for 0x7f06002a (t=5 e=42) (error -75)
,09-02 15:26:05.880  6044  6044 W ResourceType: Failure getting entry for 0x7f06002b (t=5 e=43) (error -75)
,09-02 15:26:05.880  6044  6044 W ResourceType: Failure getting entry for 0x7f06002c (t=5 e=44) (error -75)
,09-02 15:26:05.880  6044  6044 W ResourceType: Failure getting entry for 0x7f06002d (t=5 e=45) (error -75)
09-02 15:26:05.880  6044  6044 W ResourceType: Failure getting entry for 0x7f06002e (t=5 e=46) (error -75)
,09-02 15:26:05.880  6044  6044 W ResourceType: Failure getting entry for 0x7f06002f (t=5 e=47) (error -75)
09-02 15:26:05.880  6044  6044 W ResourceType: Failure getting entry for 0x7f060030 (t=5 e=48) (error -75)
,09-02 15:26:05.880  6044  6044 W ResourceType: Failure getting entry for 0x7f06001e (t=5 e=30) (error -75)
,09-02 15:26:05.880  6044  6044 W ResourceType: Failure getting entry for 0x7f06001f (t=5 e=31) (error -75)
,09-02 15:26:05.880  6044  6044 W ResourceType: Failure getting entry for 0x7f060011 (t=5 e=17) (error -75)
09-02 15:26:05.880  6044  6044 W ResourceType: Failure getting entry for 0x7f06000a (t=5 e=10) (error -75)
,09-02 15:26:05.880  6044  6044 W ResourceType: Failure getting entry for 0x7f06000b (t=5 e=11) (error -75)
09-02 15:26:05.880  6044  6044 W ResourceType: Failure getting entry for 0x7f060003 (t=5 e=3) (error -75)
,09-02 15:26:05.880  6044  6044 W ResourceType: Failure getting entry for 0x7f060015 (t=5 e=21) (error -75)
09-02 15:26:05.880  6044  6044 W ResourceType: Failure getting entry for 0x7f060016 (t=5 e=22) (error -75)
,09-02 15:26:05.900  6044  6044 I SA      : [SCU] isHaveSA() - false
09-02 15:26:05.900  6044  6044 I SA      : support phone number id : false
09-02 15:26:05.900  6044  6044 I SA      : [DM] Supports Ref Jpn : true
,09-02 15:26:05.900  6044  6044 I SA      : [DM] init END
,09-02 15:26:05.900  6044  6044 I SA      : [OR] onReceive log=[SA = 2.1.0240 V = 21 HWD = 1280X720 2.0 dpi = 320  SIZE = 2 LOCALE = en_US CSC = XEO MCC = 0 MNC 0 T = user DEVICE = a5ulte P = a5ultexx I = LRX22G M = SM-A500FU OKLEFT false DIS LRX22G.A500FUXXU1BOJ6 PSS = 4.978878039476607  ]
,09-02 15:26:05.900  6044  6044 I SA      : [OR] onReceive Intent=[ conn.CONNECTIVITY_CHANGE. networkInfo:[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] networkType:1 inetCondition:0 extraInfo:? noConnectivity:true ]
09-02 15:26:05.900  6044  6044 I SA      : [OR] == ACTION_CONNECTIVITY_CHANGE ==
,09-02 15:26:05.900  6044  6044 I SA      : [SLFUCHKMGR] constructor called
,09-02 15:26:05.920  6044  6044 I SA      : [TPMU]  strSIMState 	:SIM_STATE_ABSENT
09-02 15:26:05.920  6044  6044 I SA      : [OR] == isSIMCardReady false ==
,09-02 15:26:05.920  6044  6044 I SA      : [SCU] == networkStateCheck == false
09-02 15:26:05.920  6044  6044 I SA      : [OR] onReceive END
,09-02 15:26:05.920  6532  6532 W ActivityThread: ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,09-02 15:26:05.920  6532  6532 W System  : Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@251f4e65: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
,09-02 15:26:05.920  6532  6532 I ProviderInstaller: Installed default security provider GmsCore_OpenSSL
09-02 15:26:05.920  6532  6532 D AndroidMusic: GMSCore installation verified
,09-02 15:26:05.920  1235  1235 V DownloadManager: onReceive intent + android.net.conn.CONNECTIVITY_CHANGE
,09-02 15:26:05.930  1019  3213 D RCPManagerService: exchangeData() failure , invalid userId
,09-02 15:26:05.940  1019  2903 D RCPManagerService: exchangeData() failure , invalid userId
,09-02 15:26:05.940  1019  3109 D ActivityManager: bindService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music, action: null
09-02 15:26:05.940  1019  3109 D ActivityManager: retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.preferences.MusicPreferenceService$MusicPreferenceServiceBinder; callingUser = 0; userId(target) = 0
,09-02 15:26:05.940  1019  3109 W ActivityManager: userId = 0, bbcId = -10000
,09-02 15:26:05.940  1019  3109 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-02 15:26:05.940  1019  3109 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,09-02 15:26:05.950  5929  5937 D BadgeProvider: query, [selection] : package='com.android.email' AND class='com.android.email.activity.Welcome' AND extraData='base_extra_badge'
,09-02 15:26:05.960  6532  6532 I ConfigStore: Config Database version: 1
,09-02 15:26:05.970  1486  1486 D Launcher.Model: reloadBadges entered.
,09-02 15:26:05.970  5929  5937 D BadgeProvider: sendNotify entered. [uri] : content://com.sec.badge/apps/1
09-02 15:26:05.970  5929  5937 D BadgeProvider: sendNotify, [notify] : null
09-02 15:26:05.970  5929  5937 D BadgeProvider: update, [uri] : content://com.sec.badge/apps/1
09-02 15:26:05.970  5929  5937 D BadgeProvider: update, [BadgeCount] : badgecount=0
09-02 15:26:05.970  5929  5937 D BadgeProvider: update, [UpdateCount] : 1
,09-02 15:26:05.970  1019  1048 D Tethering: interfaceRemoved wlan0
09-02 15:26:05.970  1019  1048 E Tethering: attempting to remove unknown iface (wlan0), ignoring
,09-02 15:26:05.980  1019  2903 D RCPManagerService: exchangeData() failure , invalid userId
,09-02 15:26:05.990  1019  1319 D RCPManagerService: exchangeData() failure , invalid userId
,09-02 15:26:06.000  6483  6483 D SecurityLogAgent: KnoxConfiguration : Current State = 1
,09-02 15:26:06.000  6483  6483 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
,09-02 15:26:06.000  6483  6483 D SecurityLogAgent: StateMachine : Current State = 1
,09-02 15:26:06.010  6483  6483 D SecurityLogAgent: StateMachine : Changed Current State = 1
,09-02 15:26:06.010  1019  1319 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.service.travel, hostingType: broadcast
,09-02 15:26:06.010  1019  1319 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-02 15:26:06.010  1019  1319 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-02 15:26:06.010  1019  1319 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-02 15:26:06.010  1019  1319 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-02 15:26:06.020  6648  6648 E Zygote  : MountEmulatedStorage()
09-02 15:26:06.020  6648  6648 E Zygote  : v2
09-02 15:26:06.020  6648  6648 I libpersona: KNOX_SDCARD checking this for 10159
09-02 15:26:06.020  6648  6648 I libpersona: KNOX_SDCARD not a persona
,09-02 15:26:06.030  6648  6648 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51
,09-02 15:26:06.030  6648  6648 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051,
09-02 15:26:06.030  1019  1319 I ActivityManager: Start proc com.samsung.android.service.travel for broadcast com.samsung.android.service.travel/com.samsung.android.travel.bindService.TravelBroadcastReceiver: pid=6648 uid=10159 gids={50159, 9997, 3003, 1028, 1015} abi=armeabi-v7a
09-02 15:26:06.030  6648  6648 E SELinux : [DEBUG] get_category: variable seinfo: shared sensitivity: NULL, cateogry: NULL,
,09-02 15:26:06.060  6648  6648 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-02 15:26:06.060  6648  6648 D ActivityThread: Added TimaKeyStore provider
,09-02 15:26:06.080  1019  3093 D SecContentProvider: uri = 18 selection = isWifiEnabled
,09-02 15:26:06.080  1019  3093 D SecContentProvider2: uri = 20 selection = isWifiStateChangeAllowed
09-02 15:26:06.080  1019  3093 D SecContentProvider2: mCursor = null
,09-02 15:26:06.080  1019  3093 D WifiService: setWifiEnabled: true pid=6212, uid=10155
,09-02 15:26:06.080  1019  3093 W ActivityManager: Permission Denial: getCurrentUser() from pid=6212, uid=10155 requires android.permission.INTERACT_ACROSS_USERS
,09-02 15:26:06.080  1019  3093 W WifiService: Failed getting userId using ActivityManagerNative
09-02 15:26:06.080  1019  3093 W WifiService: java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=6212, uid=10155 requires android.permission.INTERACT_ACROSS_USERS
09-02 15:26:06.080  1019  3093 W WifiService: 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:23916)
09-02 15:26:06.080  1019  3093 W WifiService: 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2216)
09-02 15:26:06.080  1019  3093 W WifiService: 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2204)
09-02 15:26:06.080  1019  3093 W WifiService: 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:223)
09-02 15:26:06.080  1019  3093 W WifiService: 	at android.os.Binder.execTransact(Binder.java:446)
,09-02 15:26:06.080  1019  3093 D SettingsProvider: name = wifi_on
,09-02 15:26:06.110   257   526 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.music/files/
09-02 15:26:06.110   257   526 W Vold    : Returning OperationFailed - no handler for errno 0
,09-02 15:26:06.110  6532  6532 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.music/files
,09-02 15:26:06.120   257   526 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.music/files/
09-02 15:26:06.120   257   526 W Vold    : Returning OperationFailed - no handler for errno 0
,09-02 15:26:06.120  6532  6532 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.music/files
,09-02 15:26:06.120  1019  1048 D Tethering: interfaceRemoved p2p0
09-02 15:26:06.120  1019  1048 E Tethering: attempting to remove unknown iface (p2p0), ignoring
,09-02 15:26:06.120   257   526 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.music/files/
09-02 15:26:06.120   257   526 W Vold    : Returning OperationFailed - no handler for errno 0
,09-02 15:26:06.120  6532  6532 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.music/files
,09-02 15:26:06.130  1019  1082 I ActivityManager: Killing 5868:com.sec.android.widgetapp.tapandpay/u0a156 (adj 15): empty #31
,09-02 15:26:06.140  1019  1319 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,09-02 15:26:06.140  1019  1319 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.gcm.GcmService; callingUser = 0; userId(target) = 0
,09-02 15:26:06.140  1019  1319 W ActivityManager: userId = 0, bbcId = -10000
,09-02 15:26:06.140  1019  1319 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-02 15:26:06.140  1019  1319 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-02 15:26:06.150  3800  3800 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,09-02 15:26:06.150  1019  3105 I art     : Explicit concurrent mark sweep GC freed 56898(3MB) AllocSpace objects, 8(176KB) LOS objects, 33% free, 27MB/41MB, paused 2.830ms total 180.902ms
,09-02 15:26:06.160  3800  4588 I iu.UploadsManager: num queued entries: 0
09-02 15:26:06.160  3800  4588 I iu.UploadsManager: num updated entries: 0
,09-02 15:26:06.160  3800  4588 I iu.SyncManager: NEXT; no task
,09-02 15:26:06.170  1019  3214 D ActivityManager: startService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music
,09-02 15:26:06.170  1019  3214 D ActivityManager: retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.download.cache.StorageMigrationService; callingUser = 0; userId(target) = 0
,09-02 15:26:06.170  1019  3214 W ActivityManager: userId = 0, bbcId = -10000
,09-02 15:26:06.170  1019  3214 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,09-02 15:26:06.170  1019  3214 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,09-02 15:26:06.190  1019  1485 I ActivityManager: Killing 5772:com.android.mms/u0a46 (adj 15): empty #31
,09-02 15:26:06.200  1019  3213 D ActivityManager: bindService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music, action: null
,09-02 15:26:06.200  1019  3213 D ActivityManager: retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.download.artwork.ArtDownloadService2; callingUser = 0; userId(target) = 0
,09-02 15:26:06.200  1019  3213 W ActivityManager: userId = 0, bbcId = -10000
,09-02 15:26:06.200  1019  3213 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-02 15:26:06.200  1019  3213 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,09-02 15:26:06.220   257   526 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache/
09-02 15:26:06.220   257   526 W Vold    : Returning OperationFailed - no handler for errno 0
,09-02 15:26:06.220  1019  1319 D CountryDetector: No listener is left
,09-02 15:26:06.220  6624  6668 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache
,09-02 15:26:06.230  1019  3105 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,09-02 15:26:06.230   257   526 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/files/
09-02 15:26:06.230   257   526 W Vold    : Returning OperationFailed - no handler for errno 0
,09-02 15:26:06.230  6624  6668 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/files
,09-02 15:26:06.230  1019  1485 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,09-02 15:26:06.240  1019  3109 I AudioService: getStreamVolume 3 index 0
,09-02 15:26:06.240   257   526 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache/
09-02 15:26:06.240   257   526 W Vold    : Returning OperationFailed - no handler for errno 0
,09-02 15:26:06.240  6624  6672 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache
,09-02 15:26:06.240  6532  6532 I MediaRouter: Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, canDisconnect=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=0, volumeMax=15, presentationDisplayId=-1, extras=null, settingsIntent=null, providerPackageName=android }
,09-02 15:26:06.250   257   526 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/files/
09-02 15:26:06.250   257   526 W Vold    : Returning OperationFailed - no handler for errno 0
,09-02 15:26:06.250  6624  6672 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/files
09-02 15:26:06.250  6532  6532 V MusicLeanback: onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,09-02 15:26:06.270  1019  2952 D ActivityManager: bindService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music, action: null
09-02 15:26:06.270  1019  2952 D ActivityManager: retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.net.NetworkMonitor; callingUser = 0; userId(target) = 0
,09-02 15:26:06.270  1019  2952 W ActivityManager: userId = 0, bbcId = -10000
09-02 15:26:06.270  1019  2952 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,09-02 15:26:06.270  1019  2952 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,09-02 15:26:06.270  1019  2903 D ActivityManager: bindService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music, action: null
,09-02 15:26:06.270  1019  2903 D ActivityManager: retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.download.ArtDownloadQueueService; callingUser = 0; userId(target) = 0
,09-02 15:26:06.270  1019  2903 W ActivityManager: userId = 0, bbcId = -10000
,09-02 15:26:06.270  1019  2903 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,09-02 15:26:06.270  1019  2903 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,09-02 15:26:06.280  1019  3109 D ActivityManager: bindService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music, action: null
09-02 15:26:06.280  1019  3109 D ActivityManager: retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.download.cache.ArtCacheService; callingUser = 0; userId(target) = 0
,09-02 15:26:06.280  1019  3109 W ActivityManager: userId = 0, bbcId = -10000
09-02 15:26:06.280  1019  3109 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,09-02 15:26:06.280  1019  3109 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,09-02 15:26:06.290  1019  1322 I ActivityManager: Killing 5945:com.sec.android.app.myfiles/u0a47 (adj 15): empty #31
,09-02 15:26:06.290  1019  1032 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,09-02 15:26:06.290  1019  2952 D ActivityManager: retrieveServiceLocked(): component = com.android.email/com.android.email.service.AttachmentDownloadService; callingUser = 0; userId(target) = 0
09-02 15:26:06.290  1019  2952 W ActivityManager: Unable to start service Intent { cmp=com.android.email/.service.AttachmentDownloadService } U=0: not found
,09-02 15:26:06.290  1019  3213 D ActivityManager: retrieveServiceLocked(): component = com.android.email/com.android.email.service.EmailDebugService; callingUser = 0; userId(target) = 0
,09-02 15:26:06.290  1019  3214 D ActivityManager: retrieveServiceLocked(): component = com.android.email/com.android.email.legacypush.ImapPushService; callingUser = 0; userId(target) = 0
,09-02 15:26:06.300  1019  1019 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.cloudagent, hostingType: broadcast
,09-02 15:26:06.300  1019  1019 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-02 15:26:06.300  1019  1019 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-02 15:26:06.300  1019  1019 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-02 15:26:06.300  1019  1019 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-02 15:26:06.320  6676  6676 E Zygote  : MountEmulatedStorage(),
09-02 15:26:06.320  6676  6676 E Zygote  : v2
09-02 15:26:06.320  6676  6676 I libpersona: KNOX_SDCARD checking this for 10002
09-02 15:26:06.320  6676  6676 I libpersona: KNOX_SDCARD not a persona
09-02 15:26:06.320  6676  6676 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51,
,09-02 15:26:06.320  1019  1019 I ActivityManager: Start proc com.sec.android.cloudagent for broadcast com.sec.android.cloudagent/.detector.DetectorReceiver: pid=6676 uid=10002 gids={50002, 9997, 3003, 1028, 1015} abi=armeabi-v7a
09-02 15:26:06.320  6676  6676 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051
,09-02 15:26:06.320  6676  6676 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,09-02 15:26:06.340  1019  1484 D ActivityManager: bindService callerProcessName:com.google.android.music, calleePkgName: com.google.android.gms, action: null
,09-02 15:26:06.340  1019  1484 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.gcm.http.GoogleHttpService; callingUser = 0; userId(target) = 0
,09-02 15:26:06.340  6676  6676 D TimaKeyStoreProvider: TimaSignature is unavailable
09-02 15:26:06.340  1019  1484 W ActivityManager: userId = 0, bbcId = -10000
09-02 15:26:06.340  1019  1484 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-02 15:26:06.340  1019  1484 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.gms
09-02 15:26:06.340  6676  6676 D ActivityThread: Added TimaKeyStore provider
,09-02 15:26:06.350  6532  6532 I GHttpClientFactory: Using the GMSCore's GoogleHttpClient
,09-02 15:26:06.360  1019  3109 D ActivityManager: bindService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music, action: null
09-02 15:26:06.360  1019  3109 D ActivityManager: retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.net.NetworkMonitor; callingUser = 0; userId(target) = 0
,09-02 15:26:06.360  1019  3109 W ActivityManager: userId = 0, bbcId = -10000
09-02 15:26:06.360  1019  3109 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-02 15:26:06.360  1019  3109 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,09-02 15:26:06.390  1019  1322 I ActivityManager: Killing 5962:com.wsomacp/u0a25 (adj 15): empty #31
,09-02 15:26:06.410  1019  2952 I ActivityManager: Killing 5899:com.samsung.android.sdk.samsunglink/u0a38 (adj 15): empty #31
,09-02 15:26:06.410  1019  2952 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.diagmonagent, hostingType: broadcast
,09-02 15:26:06.420  1019  2952 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-02 15:26:06.420  1019  2952 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-02 15:26:06.420  1019  2952 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-02 15:26:06.420  1019  2952 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-02 15:26:06.430  6707  6707 E Zygote  : MountEmulatedStorage()
,09-02 15:26:06.430  6707  6707 E Zygote  : v2
09-02 15:26:06.430  6707  6707 I libpersona: KNOX_SDCARD checking this for 1000
09-02 15:26:06.430  6707  6707 I libpersona: KNOX_SDCARD not a persona
,09-02 15:26:06.430  6707  6707 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51
,09-02 15:26:06.430  1019  2952 I ActivityManager: Start proc com.sec.android.diagmonagent for broadcast com.sec.android.diagmonagent/.DiagMonRegistrationReceiver: pid=6707 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
,09-02 15:26:06.430  6707  6707 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051
,09-02 15:26:06.430  6707  6707 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,09-02 15:26:06.450  1019  1032 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,09-02 15:26:06.450  1019  1032 W ActivityManager: userId = 0, bbcId = -10000
,09-02 15:26:06.450  1019  1032 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-02 15:26:06.450  1019  1032 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.apps.magazines, destAppInfo.processName = com.google.android.gms
,09-02 15:26:06.460  6707  6707 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-02 15:26:06.460  6707  6707 D ActivityThread: Added TimaKeyStore provider
,09-02 15:26:06.470  6624  6624 I WebViewFactory: Loading com.google.android.webview version 43.0.2357.121 (code 2357121)
,09-02 15:26:06.490  6624  6624 I LibraryLoader: Time to load native libraries: 2 ms (timestamps 5261-5263)
09-02 15:26:06.490  6624  6624 I LibraryLoader: Expected native library version number "",actual native library version number ""
,09-02 15:26:06.500  6624  6624 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {212b9392}
,09-02 15:26:06.500  6624  6624 I LibraryLoader: Expected native library version number "",actual native library version number ""
,09-02 15:26:06.500  6624  6624 I chromium: [INFO:library_loader_hooks.cc(112)] Chromium logging enabled: level = 0, default verbosity = 0
,09-02 15:26:06.500  6707  6707 I DIAGMON_AGENT: [com.diagmondm.db.file.XDB(372/llIlIIIIlIIIIIlIlIII)] 
,09-02 15:26:06.520  6624  6624 I BrowserStartupController: Initializing chromium process, singleProcess=true
,09-02 15:26:06.520  6624  6624 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,09-02 15:26:06.520  6624  6624 E SysUtils: ApplicationContext is null in ApplicationStatus
,09-02 15:26:06.540  6624  6624 W chromium: [WARNING:resource_bundle.cc(286)] locale_file_path.empty()
,09-02 15:26:06.540  6624  6624 I chromium: [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=44 off=50556 len=3379
,09-02 15:26:06.540  6624  6624 I chromium: [INFO:aw_browser_main_parts.cc(76)] Loading webviewchromium.pak from, fd:45 off:7638088 len:1165478
,09-02 15:26:06.550  6624  6624 I Adreno-EGL: <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: SKARAJGA_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018__release_ENGG (I856e09677e)
09-02 15:26:06.550  6624  6624 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.02
09-02 15:26:06.550  6624  6624 I Adreno-EGL: Build Date: 04/06/15 Mon
09-02 15:26:06.550  6624  6624 I Adreno-EGL: Local Branch: 
09-02 15:26:06.550  6624  6624 I Adreno-EGL: Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018
09-02 15:26:06.550  6624  6624 I Adreno-EGL: Local Patches: 112c106f3772623daa7b4181c6cf23491044ead1 Revert "Disable ASTC on A405"
09-02 15:26:06.550  6624  6624 I Adreno-EGL:                  58a118cb818fdc906095a49a90977c15f9d3b223 Remove ASTC
,09-02 15:26:06.600  6624  6735 W AudioManagerAndroid: Requires BLUETOOTH permission
,09-02 15:26:06.610  6624  6624 I NSApplication: Starting up...
,09-02 15:26:06.620  1019  3093 D ActivityManager: startProcessLocked calleePkgName: com.google.android.apps.plus, hostingType: broadcast
,09-02 15:26:06.620  1019  3093 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-02 15:26:06.620  1019  3093 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-02 15:26:06.620  1019  3093 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-02 15:26:06.620  1019  3093 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-02 15:26:06.620  6707  6707 I DIAGMON_AGENT: [com.sec.android.diagmonagent.DiagMonAgentApplication(59/onCreate)] nStatus : 0
,09-02 15:26:06.630  6740  6740 E Zygote  : MountEmulatedStorage()
09-02 15:26:06.630  6740  6740 I libpersona: KNOX_SDCARD checking this for 10120
09-02 15:26:06.630  6740  6740 E Zygote  : v2
09-02 15:26:06.630  6740  6740 I libpersona: KNOX_SDCARD not a persona
09-02 15:26:06.630  6707  6707 I DIAGMON_AGENT: [com.sec.android.diagmonagent.DiagMonAgentApplication(76/onCreate)] DiagMon DM Application Start !
09-02 15:26:06.630  6740  6740 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51
09-02 15:26:06.630  6707  6707 I DIAGMON_AGENT: [lllIIIIlIIlIlllIlIIl(39/llIIIIlllllIIllIIllI)] Receive broadcast: android.net.conn.CONNECTIVITY_CHANGE
09-02 15:26:06.630  6707  6707 I DIAGMON_AGENT: [lllIIIIlIIlIlllIlIIl(40/llIIIIlllllIIllIIllI)] Receive broadcast:
09-02 15:26:06.630  6707  6707 I DIAGMON_AGENT: ./extraInfo: <unknown ssid>
09-02 15:26:06.630  6740  6740 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051
09-02 15:26:06.630  6707  6707 W DIAGMON_AGENT: [lllIIIIlIIlIlllIlIIl(27/llIIIIlllllIIllIIllI)] Network is changed and not available now, so don't do anything
09-02 15:26:06.640  6740  6740 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,09-02 15:26:06.640  1019  3093 I ActivityManager: Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.ConnectivityReceiver: pid=6740 uid=10120 gids={50120, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,09-02 15:26:06.640  1019  3093 I ActivityManager: Killing 6021:com.sec.android.app.soundalive/u0a53 (adj 15): empty #31
,09-02 15:26:06.640  1019  3109 I ActivityManager: Killing 5755:com.samsung.android.sm/1000 (adj 15): empty #31
,09-02 15:26:06.660  6740  6740 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-02 15:26:06.660  6740  6740 D ActivityThread: Added TimaKeyStore provider
,09-02 15:26:06.670  6740  6740 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,09-02 15:26:06.860  1019  1132 E WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:1
,09-02 15:26:06.860  1019  1132 E WifiHW  : ##################### set firmware type 0 #####################
,09-02 15:26:06.940  1019  1082 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.sconnect, hostingType: broadcast
,09-02 15:26:06.940  1019  1082 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-02 15:26:06.940  1019  1082 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-02 15:26:06.940  1019  1082 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-02 15:26:06.940  1019  1082 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-02 15:26:06.960  6761  6761 E Zygote  : MountEmulatedStorage(),
09-02 15:26:06.960  6761  6761 E Zygote  : v2
09-02 15:26:06.960  6761  6761 I libpersona: KNOX_SDCARD checking this for 10125
09-02 15:26:06.960  6761  6761 I libpersona: KNOX_SDCARD not a persona
,09-02 15:26:06.960  6761  6761 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51
,09-02 15:26:06.960  6761  6761 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051
09-02 15:26:06.960  1019  1082 I ActivityManager: Start proc com.samsung.android.sconnect for broadcast com.samsung.android.sconnect/.periph.PeriphStartReceiver: pid=6761 uid=10125 gids={50125, 9997, 3002, 3001, 1028, 1015, 3003} abi=armeabi-v7a
09-02 15:26:06.960  6761  6761 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
09-02 15:26:06.960  1019  1082 I ActivityManager: Killing 5856:com.google.android.apps.docs/u0a91 (adj 15): empty #31
,09-02 15:26:06.980  6761  6761 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-02 15:26:06.990  6761  6761 D ActivityThread: Added TimaKeyStore provider
,09-02 15:26:07.000  6761  6761 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
09-02 15:26:07.000  6761  6761 W ResourcesManager: Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
09-02 15:26:07.000  6761  6761 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,09-02 15:26:07.010  6761  6761 D QuickConnect: PeriphStartReceiver.onReceive - android.net.conn.CONNECTIVITY_CHANGE
,09-02 15:26:07.020  6761  6761 I QuickConnect: PeriphStartReceiver.onReceive - USER_OWNER care CONNECTIVITY_ACTION. run P service
,09-02 15:26:07.020  6761  6761 I QuickConnect: PeriphStartReceiver.onReceive - no need to start
,09-02 15:26:07.020  1019  3109 I splitIntent: Queue : backgroundsplit_1 intent android.net.conn.CONNECTIVITY_CHANGE is finished at BG and BG split queue. set mSplitStart and mBgSplitQueueOnlyRun false.
,09-02 15:26:07.020  1019  3109 I ActivityManager: Killing 6083:com.samsung.android.app.watchmanagerstub/u0a100 (adj 15): empty #31
,09-02 15:26:07.030  1019  3213 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
,09-02 15:26:07.030  1019  3213 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,09-02 15:26:07.030  1019  3213 W ActivityManager: userId = 0, bbcId = -10000
09-02 15:26:07.030  1019  3213 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-02 15:26:07.030  1019  3213 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,09-02 15:26:07.030  3631  3631 I Hs20UtilService: Starting #11
09-02 15:26:07.030  3631  3649 I Hs20UtilService: Message received 5011
,09-02 15:26:07.030  6483  6483 D SecurityLogAgent: KnoxConfiguration : Current State = 1
,09-02 15:26:07.030  6483  6483 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
09-02 15:26:07.030  6483  6483 D SecurityLogAgent: StateMachine : Current State = 1
,09-02 15:26:07.030  6483  6483 D SecurityLogAgent: StateMachine : Changed Current State = 1
,09-02 15:26:07.220  1019  1048 D Tethering: interfaceAdded wlan0
,09-02 15:26:07.220  1019  1139 E Tethering: No numeric data
,09-02 15:26:07.230  1019  1129 V NetworkStats: performPollLocked(flags=0x1)
,09-02 15:26:07.230  1019  1129 D NtpTrustedTime: currentTimeMillis() cache hit
,09-02 15:26:07.230  1182  1182 D HotspotTile: onReceive : android.net.conn.TETHER_STATE_CHANGED
,09-02 15:26:07.230  1182  1182 D HotspotTile: updateTetherState():false, false
,09-02 15:26:07.230  1019  1129 D NetworkStatsFactory: UpdateStatsForKnox updated
,09-02 15:26:07.230  1019  1139 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0,
,09-02 15:26:07.230  1019  1139 D Tethering: clearTetheredNotification(),
09-02 15:26:07.230  1019  1129 D NetworkStatsFactory: UpdateStatsForKnox main else ---
,09-02 15:26:07.240  1019  1129 V NetworkStats: performPollLocked() took 14ms
,09-02 15:26:07.240  1019  1129 D NtpTrustedTime: currentTimeMillis() cache hit
,09-02 15:26:07.240  1019  1048 D Tethering: interfaceLinkStateChanged wlan0, false
,09-02 15:26:07.240  1019  1048 I Nat464Xlat: interfaceLinkStateChanged wlan0, false,
09-02 15:26:07.240  1019  1048 D Tethering: interfaceStatusChanged wlan0, false
09-02 15:26:07.240  1019  1139 D Tethering: InitialState.processMessage what=4
09-02 15:26:07.250  1019  1139 E Tethering: No numeric data
,09-02 15:26:07.250  1019  1048 D Tethering: interfaceLinkStateChanged p2p0, false
,09-02 15:26:07.250  1019  1130 D NtpTrustedTime: currentTimeMillis() cache hit
09-02 15:26:07.250  1019  1130 D NtpTrustedTime: currentTimeMillis() cache hit
,09-02 15:26:07.250  1019  1048 D Tethering: interfaceStatusChanged p2p0, false
09-02 15:26:07.250  1019  1048 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
,09-02 15:26:07.260  1019  1139 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
,09-02 15:26:07.260  1019  1139 D Tethering: clearTetheredNotification()
09-02 15:26:07.260   278   998 I WifiHW  : wifi_change_fw_path(): fwpath = sta
09-02 15:26:07.260   278   998 D SoftapController: Softap fwReload - Ok
,09-02 15:26:07.270   278   998 D CommandListener: Setting iface cfg
,09-02 15:26:07.270  1019  1129 V NetworkStats: performPollLocked(flags=0x1)
09-02 15:26:07.270  1019  1129 D NtpTrustedTime: currentTimeMillis() cache hit
09-02 15:26:07.270   278   998 D CommandListener: Trying to bring down wlan0
09-02 15:26:07.270  1019  1048 D Tethering: interfaceAdded p2p0,
09-02 15:26:07.270  1019  1129 D NetworkStatsFactory: UpdateStatsForKnox updated
,09-02 15:26:07.270  1182  1182 D HotspotTile: onReceive : android.net.conn.TETHER_STATE_CHANGED
09-02 15:26:07.270   278   998 D CommandListener: Clearing all IP addresses on wlan0
09-02 15:26:07.270  1182  1182 D HotspotTile: updateTetherState():false, false
09-02 15:26:07.270  1019  1129 D NetworkStatsFactory: UpdateStatsForKnox main else ---
09-02 15:26:07.270  1019  1048 D Tethering: p2p0 is not a tetherable iface, ignoring
,09-02 15:26:07.280  1019  1129 D NtpTrustedTime: currentTimeMillis() cache hit
09-02 15:26:07.280  1019  1129 V NetworkStats: performPollLocked() took 11ms
09-02 15:26:07.280  1019  1130 D NtpTrustedTime: currentTimeMillis() cache hit
09-02 15:26:07.280  1019  1130 D NtpTrustedTime: currentTimeMillis() cache hit
,09-02 15:26:07.290  1019  1132 E WifiHW  : supplicant_name : p2p_supplicant
,09-02 15:26:07.290  1019  1132 D WifiMonitor: startMonitoring(wlan0) with mConnected = false,
,09-02 15:26:07.300  1182  1182 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x0/(null) mQSWifiIconId=0x0/(null) mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,09-02 15:26:07.300  1182  1182 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=false enabledDesc:null
09-02 15:26:07.300  1182  1182 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-02 15:26:07.300  1182  1182 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-02 15:26:07.300  1182  1182 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-02 15:26:07.300  1182  1182 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-02 15:26:07.300  1182  1182 D STATUSBAR-WifiQuickSettingButton: onReceive : android.net.wifi.WIFI_STATE_CHANGED
09-02 15:26:07.300  1182  1182 D STATUSBAR-WifiQuickSettingButton: Wifi onReceive(2)
,09-02 15:26:07.300  1182  1704 D STATUSBAR-QSTileView: onStateChanged: Wi-Fi
,09-02 15:26:07.310  1182  1182 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
09-02 15:26:07.310  1182  1182 D HotspotTile: onReceive : 2, 0
,09-02 15:26:07.320  1296  1296 D WifiCredService: Action received :android.net.wifi.WIFI_STATE_CHANGED
,09-02 15:26:07.320  6212  6212 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-02 15:26:07.320  6212  6212 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-02 15:26:07.320  1019  1032 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
09-02 15:26:07.320  1019  1032 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
09-02 15:26:07.320  1019  1032 W ActivityManager: userId = 0, bbcId = -10000
,09-02 15:26:07.320  1019  1032 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-02 15:26:07.320  1019  1032 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,09-02 15:26:07.330  3631  3631 I Hs20UtilService: Starting #12
,09-02 15:26:07.330  3631  3649 I Hs20UtilService: Message received 5011
,09-02 15:26:07.340  6483  6483 D SecurityLogAgent: KnoxConfiguration : Current State = 1
09-02 15:26:07.340  6483  6483 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
09-02 15:26:07.340  6483  6483 D SecurityLogAgent: StateMachine : Current State = 1
09-02 15:26:07.340  6483  6483 D SecurityLogAgent: StateMachine : Changed Current State = 1
,09-02 15:26:07.350  6785  6785 I wpa_supplicant: [wpa_supplicant_init]: use SECRIL
09-02 15:26:07.350  6785  6785 I wpa_supplicant: Successfully initialized wpa_supplicant
,09-02 15:26:07.350  6785  6785 I SecureStorage: [INFO]: SPID(0x00000000)Checking if this device supports Secure Storage
,09-02 15:26:07.360  6785  6785 I SecureStorage: [INFO]: SPID(0x00000000)This device supports Secure Storage,
,09-02 15:26:07.360   409   409 I SecureStorage: [INFO]: SPID(0x00000002)Credentials: uid 1010, gid 1010, pid 6785,
09-02 15:26:07.360   409   409 I SecureStorage: [INFO]: SPID(0x00000002)Received function mask & code: 0x0000010C
09-02 15:26:07.360  6785  6785 I SecureStorage: [INFO]: SPID(0x00000000)SS Daemon is running
09-02 15:26:07.360  6785  6785 I wpa_supplicant: ssSupport state is = 1,
09-02 15:26:07.360  6785  6785 I wpa_supplicant: >>>>> GET KEY, IV <<<<<
09-02 15:26:07.360  6785  6785 I SecureStorage: [INFO]: SPID(0x00000000)Processing data
09-02 15:26:07.360   409   409 I SecureStorage: [INFO]: SPID(0x00000002)Credentials: uid 1010, gid 1010, pid 6785
09-02 15:26:07.360   409   409 I SecureStorage: [INFO]: SPID(0x00000002)Received function mask & code: 0x00000106
,09-02 15:26:07.390  1019  3109 D BatteryService: !@BatteryListener : batteryPropertiesChanged!,
09-02 15:26:07.390  1019  3109 D BatteryService: level:94, scale:100, status:2, health:2, present:true, voltage: 4211, temperature: 285, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
09-02 15:26:07.390  1019  3109 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
,09-02 15:26:07.390  1019  3109 D BatteryService: stay LED for charging
09-02 15:26:07.390  1019  1019 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,09-02 15:26:07.400  1019  1019 I MotionRecognitionService: Plugged,
,09-02 15:26:07.400  1019  1019 I MotionRecognitionService: mGripSensorEnabled= false
,09-02 15:26:07.400  1182  1182 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
09-02 15:26:07.400  1182  1182 D KeyguardUpdateMonitor: handleBatteryUpdate
09-02 15:26:07.400  1422  1422 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
09-02 15:26:07.400  1422  1422 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 94
,09-02 15:26:07.410  1182  1182 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:94 status:2 health:2
,09-02 15:26:07.430  1182  1182 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:94 status:2 health:2,
09-02 15:26:07.430  1182  1182 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:94 status:2 health:2
,09-02 15:26:07.530   409   409 I SecureStorage: [INFO]: SPID(0x00000003)Secure Storage Daemon finished processing with result: 0,
,09-02 15:26:07.540  6785  6785 I SecureStorage: [INFO]: SPID(0x00000003)Processing data has been completed,
,09-02 15:26:07.600  6785  6785 I wpa_supplicant: Ctrl_iface: loading cred from phone
09-02 15:26:07.600  6785  6785 I SecureStorage: [INFO]: SPID(0x00000003)Checking if this device supports Secure Storage
,09-02 15:26:07.620  6785  6785 I SecureStorage: [INFO]: SPID(0x00000003)This device supports Secure Storage,
09-02 15:26:07.620   409   409 I SecureStorage: [INFO]: SPID(0x00000003)Credentials: uid 1010, gid 1010, pid 6785
,09-02 15:26:07.620   409   409 I SecureStorage: [INFO]: SPID(0x00000003)Received function mask & code: 0x0000010C
09-02 15:26:07.620  6785  6785 I SecureStorage: [INFO]: SPID(0x00000003)SS Daemon is running
,09-02 15:26:07.620  6785  6785 I wpa_supplicant: ssSupport state is = 1
09-02 15:26:07.620  6785  6785 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
09-02 15:26:07.630  6785  6785 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
,09-02 15:26:07.630  6785  6785 E wpa_supplicant: SIM READ ERROR
09-02 15:26:07.630  6785  6785 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
09-02 15:26:07.630  6785  6785 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
09-02 15:26:07.630  6785  6785 E wpa_supplicant: SIM READ ERROR
,09-02 15:26:07.630  6785  6785 I wpa_supplicant: Blacklist: Clear (all) 
09-02 15:26:07.630  6785  6785 I wpa_supplicant: wpa_default_ap_write_once
09-02 15:26:07.630  6785  6785 I wpa_supplicant: There is no /data/misc/wifi/default_ap.check. Start copy default ap
09-02 15:26:07.630  6785  6785 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
09-02 15:26:07.630  6785  6785 E wpa_supplicant: getSavedIMSI cannot open /data/misc/wifi/.kmem: No such file or directory
09-02 15:26:07.630  6785  6785 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
09-02 15:26:07.630  6785  6785 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
09-02 15:26:07.630  6785  6785 I wpa_supplicant: rfkill: Cannot open RFKILL control device
09-02 15:26:07.630  1019  1048 D Tethering: interfaceLinkStateChanged wlan0, false
09-02 15:26:07.630  1019  1048 D Tethering: interfaceStatusChanged wlan0, false
09-02 15:26:07.630  1019  1048 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
,09-02 15:26:07.700  6785  6785 I wpa_supplicant: wlan0: Setting scan request: 0 sec 100000 usec,
,09-02 15:26:07.870  6785  6785 I wpa_supplicant: wlan0: State: DISCONNECTED -> DISCONNECTED
,09-02 15:26:07.870  6785  6785 I SecureStorage: [INFO]: SPID(0x00000003)Checking if this device supports Secure Storage
,09-02 15:26:07.880  6785  6785 I SecureStorage: [INFO]: SPID(0x00000003)This device supports Secure Storage
,09-02 15:26:07.890   409   409 I SecureStorage: [INFO]: SPID(0x00000003)Credentials: uid 1010, gid 1010, pid 6785
09-02 15:26:07.890   409   409 I SecureStorage: [INFO]: SPID(0x00000003)Received function mask & code: 0x0000010C
09-02 15:26:07.890  6785  6785 I SecureStorage: [INFO]: SPID(0x00000003)SS Daemon is running,
09-02 15:26:07.890  6785  6785 I wpa_supplicant: ssSupport state is = 1
09-02 15:26:07.890  6785  6785 I wpa_supplicant: Ctrl_iface: loading cred from phone
09-02 15:26:07.890  6785  6785 I SecureStorage: [INFO]: SPID(0x00000003)Checking if this device supports Secure Storage
,09-02 15:26:07.900  6785  6785 I SecureStorage: [INFO]: SPID(0x00000003)This device supports Secure Storage,
09-02 15:26:07.900   409   409 I SecureStorage: [INFO]: SPID(0x00000003)Credentials: uid 1010, gid 1010, pid 6785
09-02 15:26:07.900   409   409 I SecureStorage: [INFO]: SPID(0x00000003)Received function mask & code: 0x0000010C
09-02 15:26:07.900  6785  6785 I SecureStorage: [INFO]: SPID(0x00000003)SS Daemon is running
09-02 15:26:07.910  1019  1048 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
09-02 15:26:07.900  6785  6785 I wpa_supplicant: ssSupport state is = 1
,09-02 15:26:07.900  6785  6785 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
09-02 15:26:07.900  6785  6785 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
09-02 15:26:07.900  6785  6785 E wpa_supplicant: SIM READ ERROR
09-02 15:26:07.900  6785  6785 I wpa_supplicant: wpa_default_ap_write_once
09-02 15:26:07.900  6785  6785 I wpa_supplicant: There is no /data/misc/wifi/default_ap.check. Start copy default ap
09-02 15:26:07.900  6785  6785 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,09-02 15:26:07.900  1019  1048 D Tethering: interfaceLinkStateChanged p2p0, false
09-02 15:26:07.910  1019  1048 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
09-02 15:26:07.900  1019  1048 D Tethering: interfaceStatusChanged p2p0, false
09-02 15:26:07.910  1019  1048 D Tethering: interfaceLinkStateChanged p2p0, false
09-02 15:26:07.910  1019  1048 D Tethering: interfaceStatusChanged p2p0, false
,09-02 15:26:08.030   288   288 E SMD     : DCD OFF,
,09-02 15:26:08.040  6785  6785 I wpa_supplicant: p2p0: State: DISCONNECTED -> INACTIVE,
09-02 15:26:08.040  6785  6785 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=-1 state=2 BSSID=00.00.00 SSID=
,09-02 15:26:08.080  6785  6785 I wpa_supplicant: p2p0: State: INACTIVE -> DISCONNECTED,
09-02 15:26:08.080  6785  6785 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=-1 state=0 BSSID=00.00.00 SSID=
,09-02 15:26:08.080  6785  6785 I wpa_supplicant: Skip scan - bUseNetwork false
,09-02 15:26:08.090  1019  1132 E WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:2,
09-02 15:26:08.090  1019  1132 D WifiNative-wlan0: callSECApiBoolean - ID [21]
,09-02 15:26:08.100  6785  6785 I wpa_supplicant: HOTSPOT20_ENABLE called,
09-02 15:26:08.100  6785  6785 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
09-02 15:26:08.100  6785  6785 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
09-02 15:26:08.100  6785  6785 E wpa_supplicant: SIM READ ERROR
09-02 15:26:08.100  6785  6785 I wpa_supplicant: Blacklist: Clear (all) ,
,09-02 15:26:08.120  6785  6785 I wpa_supplicant: wlan0: Setting scan request: 0 sec 0 usec,
,09-02 15:26:08.120  1019  2755 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,09-02 15:26:08.130  6785  6785 I wpa_supplicant: Skip scan - bUseNetwork false
,09-02 15:26:08.130  1019  1132 D WifiNative-wlan0: callSECApiInt - ID [210],
,09-02 15:26:08.130  1019  1132 D WifiConfigStore: Loading config and enabling all networks 
09-02 15:26:08.130  1182  1704 D STATUSBAR-QSTileView: onStateChanged: Wi-Fi
09-02 15:26:08.130  1182  1182 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,09-02 15:26:08.130  1182  1182 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
09-02 15:26:08.130  1182  1182 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-02 15:26:08.130  1182  1182 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-02 15:26:08.130  1182  1182 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-02 15:26:08.130  1182  1182 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-02 15:26:08.130  1182  1182 D STATUSBAR-WifiQuickSettingButton: onReceive : android.net.wifi.WIFI_STATE_CHANGED
09-02 15:26:08.130  1182  1182 D STATUSBAR-WifiQuickSettingButton: Wifi onReceive(3)
09-02 15:26:08.140  1182  1182 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
,09-02 15:26:08.140  1182  1182 D HotspotTile: onReceive : 3, 0
,09-02 15:26:08.140  1296  1296 D WifiCredService: Action received :android.net.wifi.WIFI_STATE_CHANGED
,09-02 15:26:08.140  6212  6212 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value,
09-02 15:26:08.140  6212  6212 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-02 15:26:08.140  6212  6212 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-02 15:26:08.140  6212  6212 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-02 15:26:08.140  6212  6212 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-02 15:26:08.140  6212  6212 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-02 15:26:08.140  6212  6212 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-02 15:26:08.140  6212  6212 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-02 15:26:08.140  6212  6212 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-02 15:26:08.140  6212  6212 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-02 15:26:08.140  6212  6212 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-02 15:26:08.140  6212  6212 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-02 15:26:08.140  6212  6212 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-02 15:26:08.140  6212  6212 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-02 15:26:08.140  6212  6212 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-02 15:26:08.140  6212  6212 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
,09-02 15:26:08.140  6212  6212 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-02 15:26:08.140  6212  6212 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-02 15:26:08.140  6212  6212 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-02 15:26:08.140  6212  6212 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-02 15:26:08.140  6212  6212 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-02 15:26:08.150  1019  3213 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
09-02 15:26:08.140  6212  6212 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-02 15:26:08.150  1019  3213 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
09-02 15:26:08.150  1019  3213 W ActivityManager: userId = 0, bbcId = -10000
09-02 15:26:08.150  1019  3213 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-02 15:26:08.150  1019  3213 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,09-02 15:26:08.150  3631  3631 I Hs20UtilService: Starting #13
,09-02 15:26:08.160  3631  3649 I Hs20UtilService: Message received 5011
,09-02 15:26:08.160  6483  6483 D SecurityLogAgent: KnoxConfiguration : Current State = 1
,09-02 15:26:08.160  6483  6483 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
09-02 15:26:08.160  6483  6483 D SecurityLogAgent: StateMachine : Current State = 1
,09-02 15:26:08.160  6483  6483 D SecurityLogAgent: StateMachine : Changed Current State = 1
,09-02 15:26:08.160  1019  1132 E WifiConfigStore: Not a HS20
,09-02 15:26:08.160  1019  1132 E WifiConfigStore: Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
,09-02 15:26:08.170  1019  1132 D WifiNative-wlan0: callSECApiInt - ID [65]
,09-02 15:26:08.170  1019  1132 D WifiNative-wlan0: callSECApiBoolean - ID [13]
09-02 15:26:08.170  6785  6785 I wpa_supplicant: USE_NETWORK : USE_NETWORK ON
09-02 15:26:08.170  6785  6785 I wpa_supplicant: wlan0: Setting scan request: 8 sec 0 usec
,09-02 15:26:08.170  6785  6785 I wpa_supplicant: reset timer : RESET_TIMER 0
09-02 15:26:08.170  6785  6785 I wpa_supplicant: P2P: Current p2p state = IDLE
09-02 15:26:08.170  6785  6785 I wpa_supplicant: wlan0: State: DISCONNECTED -> SCANNING
09-02 15:26:08.170  6785  6785 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00.00.00 SSID=
09-02 15:26:08.170  6785  6785 I wpa_supplicant: First Scan Start
09-02 15:26:08.170  6785  6785 I wpa_supplicant: Scan requested (ret=0) - scan timeout 30 seconds
,09-02 15:26:08.170  1019  1132 D WifiNative-wlan0: Setting external_sim to 1
,09-02 15:26:08.170  1019  1132 D WifiStateMachine: Setting OUI to DA-A1-19
09-02 15:26:08.170  1019  1132 I WifiNative-HAL: startHal
09-02 15:26:08.170  1019  1132 E wifi    : getStaticLongField sWifiHalHandle 0x9c84d88c
09-02 15:26:08.170  1019  1132 I WifiNative-HAL: Could not start hal
,09-02 15:26:08.170  6455  6455 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,09-02 15:26:08.180  1019  1132 E WifiNative-wlan0: do suspend true
,09-02 15:26:08.180  1019  1131 D WifiP2pService: P2pDisabledState{ what=131203 }
,09-02 15:26:08.180  1019  1132 E WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:3,
09-02 15:26:08.180  1019  1019 D WifiScanningService: SCAN_AVAILABLE : 3
09-02 15:26:08.180  1019  1154 D WifiScanningService: DefaultState got{ when=-1ms what=160006 target=com.android.internal.util.StateMachine$SmHandler }
09-02 15:26:08.180  1019  1154 I WifiNative-HAL: startHal
,09-02 15:26:08.180  1019  1154 E wifi    : getStaticLongField sWifiHalHandle 0x9dd059bc
09-02 15:26:08.180  1019  1154 I WifiNative-HAL: Could not start hal
09-02 15:26:08.180  1019  1154 E WifiScanningService: could not start HAL
,09-02 15:26:08.180  1019  1131 D WifiP2pService: P2pEnablingState,
09-02 15:26:08.180  1019  1019 D RttService: SCAN_AVAILABLE : 3
09-02 15:26:08.180  1019  1131 D WifiP2pService: P2pEnablingState{ what=147457 }
,09-02 15:26:08.180  1019  1155 D RttService: DefaultState got{ when=0 what=160512 target=com.android.internal.util.StateMachine$SmHandler }
09-02 15:26:08.180  1019  1131 D WifiP2pService: P2p socket connection successful,
09-02 15:26:08.180   278   998 D CommandListener: Setting iface cfg
,09-02 15:26:08.180  1019  1131 D WifiP2pService: P2pEnabledState,
09-02 15:26:08.180   278   998 D CommandListener: Trying to bring up p2p0
09-02 15:26:08.190  1019  1131 D WifiP2pService: sending p2p connection changed broadcast: DISCONNECTED
09-02 15:26:08.180  1019  1132 E WifiStateMachine: DriverStatedState::CMD_SEC_STRING_API - inner msg [207]
09-02 15:26:08.190  1019  1051 D WifiDisplayController: Received WIFI_P2P_STATE_CHANGED_ACTION: enabled=true,
09-02 15:26:08.180  1019  1131 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
09-02 15:26:08.190  1019  1051 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
09-02 15:26:08.180  1019  1132 D WifiNative-wlan0: callSECStringApiVoid - ID [215]
,09-02 15:26:08.190  1019  1051 D WifiDisplayController: disconnect
09-02 15:26:08.180  1019  1132 E WifiNative-wlan0: invaild command id : 215
09-02 15:26:08.190  1019  1051 D WifiDisplayController: updateConnection
09-02 15:26:08.180  1019  1132 E WifiStateMachine: DriverStatedState::CMD_SEC_STRING_API - inner msg [207]
09-02 15:26:08.190  1019  1051 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
09-02 15:26:08.180  1019  1132 D WifiNative-wlan0: callSECStringApiVoid - ID [215]
09-02 15:26:08.190  1019  1051 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
09-02 15:26:08.180  1019  1132 E WifiNative-wlan0: invaild command id : 215
09-02 15:26:08.190  1019  1019 E WifiStateMachine: BroadcastReceiver : WIFI_P2P_STATE_CHANGED_ACTION is : android.net.wifi.p2p.STATE_CHANGED
,09-02 15:26:08.190  6785  6785 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=PL
09-02 15:26:08.190  1019  1138 E ConnectivityService: updateNetworkInfo()
09-02 15:26:08.190  6785  6785 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=PL
,09-02 15:26:08.190  1182  1182 D AllShareCastTile: action: android.hardware.display.action.WIFI_DISPLAY_STATUS_CHANGED
09-02 15:26:08.190  1019  1223 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0},
09-02 15:26:08.190  1182  1182 D AllShareCastTile: wifi display status changed! scanstate : 0, ActiveDisplayState : 0
,09-02 15:26:08.200  1019  1051 D WifiDisplayController: Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,09-02 15:26:08.200  6785  6785 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=UNKNOWN
09-02 15:26:08.200  1019  1051 D WifiDisplayAdapter: onP2pDisconnected
09-02 15:26:08.200  1019  1051 D IpRemoteDisplayController: disconnectWfdBridgeServer,
09-02 15:26:08.200  1019  1051 D IpRemoteDisplayController: WfdBridgeServer is already null
,09-02 15:26:08.200  1296  1296 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.p2p.CONNECTION_STATE_CHANGE
09-02 15:26:08.200  1296  1296 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
,09-02 15:26:08.200  1296  1296 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,09-02 15:26:08.200  1296  1296 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
09-02 15:26:08.200  1296  1296 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
09-02 15:26:08.200  1296  1296 I NearbySettings: MountReceiver.onReceive - Set preference state off
09-02 15:26:08.200  1296  3038 V NearbySettings: MountReceiver.mPrefHandler - 7002
,09-02 15:26:08.200  1019  1132 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
09-02 15:26:08.200  1019  1132 D SecContentProvider2: mCursor = null
,09-02 15:26:08.210  1019  1131 D WifiNative-p2p0: p2pGetDeviceAddress
,09-02 15:26:08.210  1019  1131 D WifiNative-p2p0: p2pGetDeviceAddress returning 7e:f9:0e:37:96:ac
09-02 15:26:08.210  6425  6425 D FileShare-Client: ClientBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
09-02 15:26:08.210  6425  6425 D FileShare-Client: ClientBroadcastReceiver.onReceive - disconnected
09-02 15:26:08.210  6425  6425 D FileShare-Client: Outbound.stopDelayTimer - 
09-02 15:26:08.210  1019  1131 D WifiP2pService: DeviceAddress: 7e:96:ac
09-02 15:26:08.210  1019  1132 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
09-02 15:26:08.210  1019  1132 D SecContentProvider2: mCursor = null
09-02 15:26:08.210  1019  1051 D WifiDisplayController: Received WIFI_P2P_THIS_DEVICE_CHANGED_ACTION: mThisDevice= Device: A5-1
09-02 15:26:08.210  1019  1051 D WifiDisplayController:  deviceAddress: 7e:f9:0e:37:96:ac
09-02 15:26:08.210  1019  1051 D WifiDisplayController:  primary type: 10-0050F204-5
09-02 15:26:08.210  1019  1051 D WifiDisplayController:  secondary type: null
09-02 15:26:08.210  1019  1051 D WifiDisplayController:  wps: 0
09-02 15:26:08.210  1019  1051 D WifiDisplayController:  grpcapab: 0
09-02 15:26:08.210  1019  1051 D WifiDisplayController:  devcapab: 0
09-02 15:26:08.210  1019  1051 D WifiDisplayController:  status: 3
09-02 15:26:08.210  1019  1051 D WifiDisplayController:  wfdInfo: null
09-02 15:26:08.210  1019  1051 D WifiDisplayController:  groupownerAddress: null
09-02 15:26:08.210  1019  1051 D WifiDisplayController:  GOdeviceName: null
09-02 15:26:08.210  1019  1051 D WifiDisplayController:  interfaceAddress: 
09-02 15:26:08.210  1019  1051 D WifiDisplayController:  SConnectInfo : null
,09-02 15:26:08.220  6440  6440 D FileShare-Server: ServerBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,09-02 15:26:08.230  1019  1131 D WifiP2pService: sending p2p persistent groups changed broadcast
,09-02 15:26:08.230  1019  1131 D WifiP2pService: InactiveState
,09-02 15:26:08.230  1019  1131 D WifiP2pService: InactiveState{ what=143376 }
,09-02 15:26:08.230  1019  1131 D WifiP2pService: P2pEnabledState{ what=143376 }
,09-02 15:26:08.230  6785  6785 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=PL,
,09-02 15:26:08.230  1019  1131 D WifiP2pService: InactiveState{ what=143376 }
,09-02 15:26:08.230  1019  1131 D WifiP2pService: P2pEnabledState{ what=143376 }
,09-02 15:26:08.240  1019  1048 D Tethering: interfaceLinkStateChanged p2p0, false
,09-02 15:26:08.240  1019  1048 D Tethering: interfaceStatusChanged p2p0, false
09-02 15:26:08.240  1019  1048 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
,09-02 15:26:08.980  1019  1032 I ActivityManager: Killing 6105:com.samsung.helphub/1000 (adj 15): empty #31
,09-02 15:26:09.090  1019  3109 D SecContentProvider: uri = 18 selection = isWifiEnabled,
09-02 15:26:09.090  1019  3109 D WifiService: setWifiEnabled: false pid=6212, uid=10155
09-02 15:26:09.090  1019  3109 D SecContentProvider2: uri = 20 selection = isWifiStateChangeAllowed
,09-02 15:26:09.090  1019  3109 D SecContentProvider2: mCursor = null
09-02 15:26:09.090  1019  3109 D SettingsProvider: name = wifi_on
,09-02 15:26:09.100  1019  1019 D WifiScanningService: SCAN_AVAILABLE : 1
,09-02 15:26:09.100  1019  1154 D WifiScanningService: DefaultState got{ when=0 what=160007 target=com.android.internal.util.StateMachine$SmHandler }
,09-02 15:26:09.100  1019  1019 D RttService: SCAN_AVAILABLE : 1
,09-02 15:26:09.110  1019  1155 D RttService: EnabledState got{ when=-1ms what=160513 target=com.android.internal.util.StateMachine$SmHandler }
,09-02 15:26:09.110  1019  1131 D WifiP2pService: InactiveState{ what=131204 }
09-02 15:26:09.110  1019  1131 D WifiP2pService: P2pEnabledState{ what=131204 }
09-02 15:26:09.110  1019  1131 D WifiP2pService: sending p2p connection changed broadcast: FAILED
,09-02 15:26:09.110  1019  1138 E ConnectivityService: updateNetworkInfo()
,09-02 15:26:09.110  1019  1051 D WifiDisplayController: Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/FAILED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,09-02 15:26:09.110  1019  1051 D WifiDisplayAdapter: onP2pDisconnected
09-02 15:26:09.110  1019  1051 D IpRemoteDisplayController: disconnectWfdBridgeServer
09-02 15:26:09.110  1019  1051 D IpRemoteDisplayController: WfdBridgeServer is already null
,09-02 15:26:09.120  1019  1131 D WifiP2pService: sending p2p connection changed broadcast: DISCONNECTED
,09-02 15:26:09.120  1019  1138 E ConnectivityService: updateNetworkInfo()
09-02 15:26:09.120  1296  1296 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.p2p.CONNECTION_STATE_CHANGE
,09-02 15:26:09.120  1019  1019 E WifiStateMachine: BroadcastReceiver : WIFI_P2P_STATE_CHANGED_ACTION is : android.net.wifi.p2p.STATE_CHANGED
,09-02 15:26:09.120  1019  1051 D WifiDisplayController: Received WIFI_P2P_STATE_CHANGED_ACTION: enabled=false
,09-02 15:26:09.120  1019  1051 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
,09-02 15:26:09.120  1019  1051 D WifiDisplayController: disconnect
09-02 15:26:09.120  1019  1051 D WifiDisplayController: updateConnection
09-02 15:26:09.120  1019  1051 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
09-02 15:26:09.120  1019  1051 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,09-02 15:26:09.120  1019  1131 D WifiP2pService: P2pDisablingState
,09-02 15:26:09.120  1019  1131 D WifiP2pService: P2pDisablingState{ what=147458 }
,09-02 15:26:09.120  1019  1131 D WifiP2pService: p2p socket connection lost
,09-02 15:26:09.130  1019  1131 D WifiP2pService: P2pDisabledState
,09-02 15:26:09.130  1019  1051 D WifiDisplayController: Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: false, isConnectedToProvisioningNetwork: false]
09-02 15:26:09.130  1019  1051 D WifiDisplayAdapter: onP2pDisconnected
,09-02 15:26:09.130  1019  1051 D IpRemoteDisplayController: disconnectWfdBridgeServer
09-02 15:26:09.130  1019  1051 D IpRemoteDisplayController: WfdBridgeServer is already null
,09-02 15:26:09.130  1296  1296 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
,09-02 15:26:09.130  1296  1296 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
09-02 15:26:09.130  1182  1182 D AllShareCastTile: action: android.hardware.display.action.WIFI_DISPLAY_STATUS_CHANGED
,09-02 15:26:09.130  1019  3214 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,09-02 15:26:09.130  1296  1296 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
09-02 15:26:09.130  1296  1296 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
09-02 15:26:09.130  1296  1296 I NearbySettings: MountReceiver.onReceive - Set preference state off
,09-02 15:26:09.130  1182  1182 D AllShareCastTile: wifi display status changed! scanstate : 0, ActiveDisplayState : 0
09-02 15:26:09.140  1296  3038 V NearbySettings: MountReceiver.mPrefHandler - 7002
,09-02 15:26:09.140   278   998 D CommandListener: Clearing all IP addresses on wlan0
,09-02 15:26:09.140  6425  6425 D FileShare-Client: ClientBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,09-02 15:26:09.150  6425  6425 D FileShare-Client: ClientBroadcastReceiver.onReceive - disconnected
09-02 15:26:09.150  6425  6425 D FileShare-Client: Outbound.stopDelayTimer - 
,09-02 15:26:09.160  1019  1019 I WifiTrafficPoller: evaluateTrafficStatsPolling
,09-02 15:26:09.160  6440  6440 D FileShare-Server: ServerBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
09-02 15:26:09.160  6785  6785 I wpa_supplicant: p2p0: State: DISCONNECTED -> DISCONNECTED
,09-02 15:26:09.170  1182  1182 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
09-02 15:26:09.170  1182  1182 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
09-02 15:26:09.170  1182  1182 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-02 15:26:09.170  1182  1182 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-02 15:26:09.170  1182  1182 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-02 15:26:09.170  1182  1182 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-02 15:26:09.170  1182  1182 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x0/(null) mQSWifiIconId=0x0/(null) mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,09-02 15:26:09.170  1182  1182 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=false enabledDesc:null
,09-02 15:26:09.170  1182  1182 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-02 15:26:09.170  1182  1182 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-02 15:26:09.170  1182  1182 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-02 15:26:09.170  1182  1182 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-02 15:26:09.170  1182  1182 D STATUSBAR-WifiQuickSettingButton: onReceive : android.net.wifi.WIFI_STATE_CHANGED
09-02 15:26:09.170  1182  1182 D STATUSBAR-WifiQuickSettingButton: Wifi onReceive(0)
09-02 15:26:09.170  1182  1182 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
,09-02 15:26:09.170  1182  1704 D STATUSBAR-QSTileView: onStateChanged: Wi-Fi
09-02 15:26:09.170  1182  1182 D HotspotTile: onReceive : 0, 0
,09-02 15:26:09.180  6212  6212 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-02 15:26:09.180  6212  6212 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-02 15:26:09.180  6212  6212 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-02 15:26:09.180  6212  6212 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-02 15:26:09.180  6212  6212 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-02 15:26:09.180  6212  6212 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-02 15:26:09.180  6212  6212 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-02 15:26:09.180  6212  6212 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-02 15:26:09.180  6212  6212 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-02 15:26:09.180  6212  6212 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-02 15:26:09.180  6212  6212 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-02 15:26:09.180  6212  6212 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-02 15:26:09.180  6212  6212 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-02 15:26:09.180  6212  6212 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-02 15:26:09.180  6212  6212 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-02 15:26:09.180  6212  6212 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-02 15:26:09.180  6212  6212 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-02 15:26:09.180  6212  6212 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-02 15:26:09.180  6212  6212 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-02 15:26:09.180  6212  6212 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-02 15:26:09.180  6212  6212 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-02 15:26:09.180  6212  6212 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-02 15:26:09.180  1296  1296 D WifiCredService: Action received :android.net.wifi.WIFI_STATE_CHANGED
,09-02 15:26:09.190  1296  1296 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.p2p.CONNECTION_STATE_CHANGE
,09-02 15:26:09.190  1296  1296 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
,09-02 15:26:09.190  1296  1296 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,09-02 15:26:09.190  1296  1296 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
09-02 15:26:09.190  1296  1296 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
09-02 15:26:09.190  1296  1296 I NearbySettings: MountReceiver.onReceive - Set preference state off
09-02 15:26:09.190  1296  3038 V NearbySettings: MountReceiver.mPrefHandler - 7002
,09-02 15:26:09.190  6425  6425 D FileShare-Client: ClientBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,09-02 15:26:09.190  6425  6425 D FileShare-Client: ClientBroadcastReceiver.onReceive - disconnected
09-02 15:26:09.190  6425  6425 D FileShare-Client: Outbound.stopDelayTimer - 
,09-02 15:26:09.200  6440  6440 D FileShare-Server: ServerBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,09-02 15:26:09.210  1019  1082 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
,09-02 15:26:09.210  1019  1082 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,09-02 15:26:09.210  1019  1082 W ActivityManager: userId = 0, bbcId = -10000
,09-02 15:26:09.210  1019  1082 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-02 15:26:09.210  1019  1082 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,09-02 15:26:09.210  1296  1296 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
09-02 15:26:09.210  1296  1296 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
,09-02 15:26:09.210  1296  1296 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,09-02 15:26:09.210  3631  3631 I Hs20UtilService: Starting #14
,09-02 15:26:09.220  1296  1296 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
,09-02 15:26:09.220  1296  1296 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
,09-02 15:26:09.220  3631  3649 I Hs20UtilService: Message received 5007
,09-02 15:26:09.220  1296  1296 I NearbySettings: MountReceiver.onReceive - Set preference state off
,09-02 15:26:09.220  1296  3038 V NearbySettings: MountReceiver.mPrefHandler - 7002
,09-02 15:26:09.230  1019  3214 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
,09-02 15:26:09.230  1019  3214 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,09-02 15:26:09.230  1019  3214 W ActivityManager: userId = 0, bbcId = -10000
09-02 15:26:09.230  1019  3214 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,09-02 15:26:09.230  1019  3214 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,09-02 15:26:09.240  3631  3631 I Hs20UtilService: Starting #15
,09-02 15:26:09.240  3631  3649 I Hs20UtilService: Message received 5011
,09-02 15:26:09.240  6483  6483 D SecurityLogAgent: KnoxConfiguration : Current State = 1
09-02 15:26:09.240  6483  6483 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
,09-02 15:26:09.240  6483  6483 D SecurityLogAgent: StateMachine : Current State = 1
09-02 15:26:09.240  6483  6483 D SecurityLogAgent: StateMachine : Changed Current State = 1
,09-02 15:26:09.260  6785  6785 I wpa_supplicant: Blacklist: Clear (all) 
,09-02 15:26:09.340  6785  6785 I wpa_supplicant: p2p0: CTRL-EVENT-TERMINATING 
09-02 15:26:09.340  6785  6785 I wpa_supplicant: wlan0: State: SCANNING -> DISCONNECTED
09-02 15:26:09.340  6785  6785 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=-1 state=0 BSSID=00.00.00 SSID=
,09-02 15:26:09.340  1019  1048 D Tethering: interfaceLinkStateChanged p2p0, false
09-02 15:26:09.340  1019  1048 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
09-02 15:26:09.340  1019  1048 D Tethering: interfaceStatusChanged p2p0, false
,09-02 15:26:09.660  6785  6785 I wpa_supplicant: Blacklist: Clear (all) ,
,09-02 15:26:09.680  1019  1345 E Watchdog: !@Sync 4,
,09-02 15:26:09.820  6785  6785 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING ,
09-02 15:26:09.830  1019  1048 D Tethering: interfaceLinkStateChanged wlan0, false
09-02 15:26:09.830  1019  1048 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
09-02 15:26:09.830  1019  1048 D Tethering: interfaceStatusChanged wlan0, false
,09-02 15:26:09.940  1019  1132 E WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:0
,09-02 15:26:09.940  1019  1132 D WifiNative-wlan0: callSECApiBoolean - ID [21]
,09-02 15:26:09.940  1019  1132 E WifiConfigStore: setLastSelectedConfiguration -1
,09-02 15:26:09.940  6455  6455 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,09-02 15:26:09.950  1182  1182 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x0/(null) mQSWifiIconId=0x0/(null) mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth,
09-02 15:26:09.950  1182  1182 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=false enabledDesc:null
09-02 15:26:09.950  1182  1182 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-02 15:26:09.950  1182  1182 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-02 15:26:09.950  1182  1182 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-02 15:26:09.950  1182  1182 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-02 15:26:09.950  1182  1182 D STATUSBAR-WifiQuickSettingButton: onReceive : android.net.wifi.WIFI_STATE_CHANGED
,09-02 15:26:09.950  1182  1182 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
09-02 15:26:09.950  1182  1182 D STATUSBAR-WifiQuickSettingButton: Wifi onReceive(1)
09-02 15:26:09.960  1182  1704 D STATUSBAR-QSTileView: onStateChanged: Wi-Fi
09-02 15:26:09.960  1182  1182 D HotspotTile: onReceive : 1, 0
,09-02 15:26:09.960  1883  2125 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,09-02 15:26:09.960  1296  1296 D WifiCredService: Action received :android.net.wifi.WIFI_STATE_CHANGED
,09-02 15:26:09.960  6212  6212 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-02 15:26:09.960  6212  6212 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-02 15:26:09.970  1019  1485 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
,09-02 15:26:09.970  1019  1485 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,09-02 15:26:09.970  1019  1485 W ActivityManager: userId = 0, bbcId = -10000
,09-02 15:26:09.970  1019  1485 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-02 15:26:09.970  1019  1485 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,09-02 15:26:09.980  3631  3631 I Hs20UtilService: Starting #16
,09-02 15:26:09.980  6483  6483 D SecurityLogAgent: KnoxConfiguration : Current State = 1
09-02 15:26:09.980  6483  6483 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
,09-02 15:26:09.980  6483  6483 D SecurityLogAgent: StateMachine : Current State = 1
09-02 15:26:09.980  6483  6483 D SecurityLogAgent: StateMachine : Changed Current State = 1
09-02 15:26:09.980  3631  3649 I Hs20UtilService: Message received 5011
,09-02 15:26:10.000  1019  2713 D SSRM:n  : SIOP:: AP = 350
,09-02 15:26:10.590  1019  1048 D Tethering: interfaceRemoved wlan0
09-02 15:26:10.590  1019  1048 E Tethering: attempting to remove unknown iface (wlan0), ignoring
,09-02 15:26:10.660   338   338 I ServiceManager: Waiting for service AtCmdFwd...,
,09-02 15:26:10.820  1019  1048 D Tethering: interfaceRemoved p2p0
,09-02 15:26:10.820  1019  1048 E Tethering: attempting to remove unknown iface (p2p0), ignoring
,09-02 15:26:11.030   288   288 E SMD     : DCD OFF
,09-02 15:26:11.230  1019  1046 W ActivityManager: userId = 0, bbcId = -10000
,09-02 15:26:11.230  1019  1046 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-02 15:26:11.230  1019  1046 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,09-02 15:26:11.240  1019  3105 D ActivityManager: startService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music
,09-02 15:26:11.240  1019  3105 D ActivityManager: retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.leanback.AutoCacheSchedulingService; callingUser = 0; userId(target) = 0
,09-02 15:26:11.240  1019  3105 W ActivityManager: userId = 0, bbcId = -10000
,09-02 15:26:11.240  1019  3105 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-02 15:26:11.240  1019  3105 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,09-02 15:26:11.250  1019  3214 D ActivityManager: bindService callerProcessName:com.google.android.apps.magazines, calleePkgName: com.google.android.gms, action: com.google.android.gms.analytics.service.START
,09-02 15:26:11.250  1019  3214 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.analytics.service.AnalyticsService; callingUser = 0; userId(target) = 0
,09-02 15:26:11.250  1019  3214 W ActivityManager: userId = 0, bbcId = -10000
,09-02 15:26:11.250  1019  3214 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-02 15:26:11.250  1019  3214 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.apps.magazines, destAppInfo.processName = com.google.android.gms
,09-02 15:26:11.260  6624  6669 I GAV4    : Thread[GAThread,5,main]: No campaign data found.
,09-02 15:26:11.270  1019  1484 W ActivityManager: userId = 0, bbcId = -10000
,09-02 15:26:11.270  1019  1484 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-02 15:26:11.270  1019  1484 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,09-02 15:26:11.280  1019  3109 D ActivityManager: bindService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music, action: null
,09-02 15:26:11.280  1019  3109 D ActivityManager: retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.download.TrackDownloadQueueService; callingUser = 0; userId(target) = 0
,09-02 15:26:11.280  1019  3109 W ActivityManager: userId = 0, bbcId = -10000
,09-02 15:26:11.280  1019  3109 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-02 15:26:11.280  1019  3109 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,09-02 15:26:11.280  1019  2905 D ActivityManager: bindService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music, action: null
09-02 15:26:11.280  1019  2905 D ActivityManager: retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.download.cache.TrackCacheService; callingUser = 0; userId(target) = 0
,09-02 15:26:11.280  1019  2905 W ActivityManager: userId = 0, bbcId = -10000
09-02 15:26:11.280  1019  2905 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,09-02 15:26:11.280  1019  2905 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,09-02 15:26:11.290  1019  1082 D ActivityManager: bindService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music, action: null
,09-02 15:26:11.290  1019  1082 D ActivityManager: retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.net.NetworkMonitor; callingUser = 0; userId(target) = 0
,09-02 15:26:11.290  1019  1082 W ActivityManager: userId = 0, bbcId = -10000
09-02 15:26:11.290  1019  1082 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,09-02 15:26:11.290  1019  1082 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,09-02 15:26:11.300  1019  1485 D ActivityManager: startService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music
,09-02 15:26:11.300  1019  1485 D ActivityManager: retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.wear.WearMetadataSyncService; callingUser = 0; userId(target) = 0
,09-02 15:26:11.300  1019  1485 W ActivityManager: userId = 0, bbcId = -10000
,09-02 15:26:11.300  1019  1485 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-02 15:26:11.300  1019  1485 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,09-02 15:26:11.330  1019  1032 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,09-02 15:26:11.330  1019  1032 W ActivityManager: userId = 0, bbcId = -10000
,09-02 15:26:11.330  1019  1032 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-02 15:26:11.330  1019  1032 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.gms
,09-02 15:26:11.340  1883  1883 D WearableService: callingUid 10012, callindPid: 1883
,09-02 15:26:11.360  1019  3109 D ActivityManager: bindService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music, action: null
09-02 15:26:11.360  1019  3109 D ActivityManager: retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.net.NetworkMonitor; callingUser = 0; userId(target) = 0
,09-02 15:26:11.360  1019  3109 W ActivityManager: userId = 0, bbcId = -10000
,09-02 15:26:11.360  1019  3109 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-02 15:26:11.360  1019  3109 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,09-02 15:26:11.380  6532  6796 I MusicLeanback: Conditions not met for autocaching.
09-02 15:26:11.380  6532  6796 I MusicLeanback: Stop autocaching.
,09-02 15:26:11.400  6532  6532 E GmsUtils: Failed to connect to Google API client: ConnectionResult{statusCode=unknown status code 16, resolution=null}
,09-02 15:26:11.400  6532  6802 E GmsUtils: Failed to connect to Google API client: ConnectionResult{statusCode=unknown status code 16, resolution=null}
,09-02 15:26:11.570  1019  1132 E WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:1
,09-02 15:26:11.660   338   338 I ServiceManager: Waiting for service AtCmdFwd...
,09-02 15:26:12.100  6212  6266 D BluetoothAdapter: enable()
,09-02 15:26:12.110  1019  3105 W ActivityManager: Permission Denial: getCurrentUser() from pid=6212, uid=10155 requires android.permission.INTERACT_ACROSS_USERS
,09-02 15:26:12.110  1019  3105 W BluetoothManagerService: Failed getting userId using ActivityManagerNative
09-02 15:26:12.110  1019  3105 W BluetoothManagerService: java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=6212, uid=10155 requires android.permission.INTERACT_ACROSS_USERS
09-02 15:26:12.110  1019  3105 W BluetoothManagerService: 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:23916)
09-02 15:26:12.110  1019  3105 W BluetoothManagerService: 	at com.android.server.BluetoothManagerService.CheckItPolicy(BluetoothManagerService.java:2270)
09-02 15:26:12.110  1019  3105 W BluetoothManagerService: 	at com.android.server.BluetoothManagerService.enable(BluetoothManagerService.java:702)
09-02 15:26:12.110  1019  3105 W BluetoothManagerService: 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:116)
09-02 15:26:12.110  1019  3105 W BluetoothManagerService: 	at android.os.Binder.execTransact(Binder.java:446)
,09-02 15:26:12.110  1019  3105 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
09-02 15:26:12.110  1019  3105 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
,09-02 15:26:12.110  1019  3105 D SettingsProvider: name = bluetooth_on
,09-02 15:26:12.120  1019  1050 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
,09-02 15:26:12.120  1019  1050 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
,09-02 15:26:12.120  1019  1050 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetooth
,09-02 15:26:12.120  1019  1050 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.btservice.AdapterService; callingUser = 0; userId(target) = -2
,09-02 15:26:12.160  6403  6403 D BluetoothAdapterState: make
,09-02 15:26:12.160  6403  6403 I bluedroid: init
,09-02 15:26:12.170  6403  6804 I BluetoothAdapterState: Entering OffState,
,09-02 15:26:12.170  6403  6403 I bte_conf: bte_load_conf attempt to load stack conf from /etc/bluetooth/bt_stack.conf
,09-02 15:26:12.170  6403  6403 I bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
,09-02 15:26:12.170  6403  6403 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
09-02 15:26:12.170  6403  6403 I bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
,09-02 15:26:12.180  6403  6403 E bt-btif : btif_fetch_local_ble_random_bdaddr
,09-02 15:26:12.180  6403  6403 I bluedroid: get_profile_interface socket
09-02 15:26:12.180  6403  6403 I bluedroid: get_profile_interface map_client
,09-02 15:26:12.180  6403  6403 D BluetoothAdapterService: checkAddrForIOP: Loading from conf
,09-02 15:26:12.180  6403  6807 I GKI_LINUX: gki_task_entry task_id=1 [BTIF] starting
,09-02 15:26:12.180  6403  6807 D BluetoothAdapterProperties: Address is:7C:F9:0E:37:96:AB
,09-02 15:26:12.190  6403  6807 E BluetoothServiceJni: populateRssiValuesNative
09-02 15:26:12.190  6403  6807 I bluedroid: getModelRssiValues
09-02 15:26:12.190  6403  6807 E BluetoothServiceJni: model_rssi_values_callback: low = -70, mid = -60, high = 127
09-02 15:26:12.190  6403  6807 D BluetoothAdapterProperties: modelRssiValuesCallback, low, mid, high = -70,-60,127
,09-02 15:26:12.190  6403  6403 D BluetoothA2dp: doBind(): CallingUid(myUserHandle) = 0
,09-02 15:26:12.190  1019  1019 D SettingsProvider: name = bluetooth_name
,09-02 15:26:12.190  1019  1223 D ActivityManager: bindService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothA2dp
,09-02 15:26:12.190  1019  1223 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
09-02 15:26:12.190  6403  6807 D BluetoothAdapterProperties: Name is: A5-1
,09-02 15:26:12.190  1019  1223 W ActivityManager: userId = 0, bbcId = -10000
09-02 15:26:12.190  1019  1223 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,09-02 15:26:12.190  1019  1223 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-02 15:26:12.190  6403  6415 I bluedroid: config_hci_snoop_log
,09-02 15:26:12.190  1019  1050 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 11 receivers.
,09-02 15:26:12.200  1019  1050 D BluetoothManagerService: Ble is always on enable gatt
,09-02 15:26:12.200  1019  1050 I BluetoothManagerService: enableGattForLeMode, doBind called
,09-02 15:26:12.200  1019  1050 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothGatt
,09-02 15:26:12.200  1019  1050 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.gatt.GattService; callingUser = 0; userId(target) = -2
,09-02 15:26:12.200  1019  1050 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
,09-02 15:26:12.210  6403  6403 I BtGatt.JNI: classInitNative(L900): classInitNative: Success!
09-02 15:26:12.210  1019  1050 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
,09-02 15:26:12.210  1019  1050 D SecContentProvider: uri = 3 selection = isBluetoothEnabled
,09-02 15:26:12.210  6403  6804 D BluetoothAdapterState: CURRENT_STATE=OFF, MSG = USER_TURN_ON
,09-02 15:26:12.210  6403  6804 D BluetoothAdapterProperties: Setting state to 11
09-02 15:26:12.210  6403  6804 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 11
09-02 15:26:12.210  6403  6804 D BluetoothAdapterService: Bluetooth PBAP supproted is true
09-02 15:26:12.210  6403  6804 D BluetoothAdapterService: updateAdapterState state is 11
,09-02 15:26:12.210  6403  6804 D BluetoothAdapterService: Autoconnection is available 
09-02 15:26:12.210  6403  6804 D BluetoothAdapterService: updateAdapterState prevState = 10newState = 11
,09-02 15:26:12.210  1019  1019 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
,09-02 15:26:12.220  1019  1019 I InputMethodManagerService: [BT Setting State] State =11
,09-02 15:26:12.220  1954  1954 I SamsungIME: STATE_CHANGED = 11, KEYBOARD_BT(0), mBTKeyboardCount =0
,09-02 15:26:12.230  1182  1182 D BluetoothTile:  onBluetoothPairedDevicesChanged:
09-02 15:26:12.230  1182  1182 D BluetoothTile: onReceive : android.bluetooth.adapter.action.STATE_CHANGED
09-02 15:26:12.230  1182  1182 D BluetoothTile:  getBluetoothState : 11
,09-02 15:26:12.230  1296  1296 V BluetoothEventManager: Received android.bluetooth.adapter.action.STATE_CHANGED
,09-02 15:26:12.230  6403  6804 D BluetoothSecureManager: getInstant: null
09-02 15:26:12.230  6403  6804 D BluetoothSecureManager: calling getMethod for getService
09-02 15:26:12.230  6403  6804 D BluetoothSecureManager: calling getService
,09-02 15:26:12.230  6403  6804 D BluetoothSecureManager: getService return binder: android.os.BinderProxy@1e225115
,09-02 15:26:12.230  1019  3214 D StatusBarManagerService: setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
,09-02 15:26:12.230  1019  1031 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=false
,09-02 15:26:12.230  1182  1182 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 )
,09-02 15:26:12.230  1019  3093 D BluetoothSecureManagerService: isSecureModeEnabled
,09-02 15:26:12.230  6212  6212 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-02 15:26:12.240  1182  1704 D BluetoothTile:  handleUpdatestate:false name:null
,09-02 15:26:12.240  1019  3093 D BluetoothSecureManagerService: getSecureModeSetting, name: secure_mode_enable
09-02 15:26:12.240  1019  1032 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,09-02 15:26:12.240  1019  1032 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.nearby.discovery.service.DiscoveryService; callingUser = 0; userId(target) = 0
09-02 15:26:12.240  1182  1704 D STATUSBAR-QSTileView: onStateChanged: Bluetooth
,09-02 15:26:12.240  6403  6804 D BtConfig.SecureMode: isSecureModeOn:false
09-02 15:26:12.240  6403  6804 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.gatt.GattService
,09-02 15:26:12.240  6212  6212 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-02 15:26:12.240  1019  1050 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 0 receivers.
09-02 15:26:12.240  6403  6804 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.gatt.GattService
09-02 15:26:12.240  6403  6804 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
,09-02 15:26:12.240  1019  1032 W ActivityManager: userId = 0, bbcId = -10000
09-02 15:26:12.240  1019  1032 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-02 15:26:12.240  1019  1032 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
09-02 15:26:12.240  6403  6804 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.hfp.HeadsetService
09-02 15:26:12.240  6403  6804 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
,09-02 15:26:12.240  6403  6804 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.a2dp.A2dpService
09-02 15:26:12.240  6403  6804 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
,09-02 15:26:12.240  6403  6804 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.hid.HidService
09-02 15:26:12.240  6403  6804 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
,09-02 15:26:12.240  6403  6804 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.hdp.HealthService
09-02 15:26:12.240  6403  6804 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.pan.PanService
,09-02 15:26:12.240  6403  6804 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.pan.PanService
09-02 15:26:12.240  6403  6804 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
09-02 15:26:12.240  6403  6804 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.map.BluetoothMapService
09-02 15:26:12.250  6403  6804 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
,09-02 15:26:12.250  1296  1296 D BluetoothNotiBroadcastReceiver: onReceive
09-02 15:26:12.250  6403  6804 W BluetoothAdapterService: isProfileEnabled(): profile not found com.broadcom.bt.service.sap.SapService
09-02 15:26:12.250  6403  6804 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfpclient.HeadsetClientService
09-02 15:26:12.250  6403  6804 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.hfpclient.HeadsetClientService
,09-02 15:26:12.250  6403  6804 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpSinkService
09-02 15:26:12.250  6403  6804 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.a2dp.A2dpSinkService
09-02 15:26:12.250  6403  6804 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.sapclient.SapClientService
09-02 15:26:12.250  1182  1182 V BluetoothStatusReceiver: Received android.bluetooth.adapter.action.STATE_CHANGED
09-02 15:26:12.250  1182  1182 D BluetoothStatusReceiver: AdapterStateChanged :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 11
09-02 15:26:12.250  6403  6804 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.sapclient.SapClientService
,09-02 15:26:12.250  6403  6804 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidDevService
,09-02 15:26:12.250  6403  6804 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.hid.HidDevService
,09-02 15:26:12.250  6403  6804 D BluetoothBondStateMachine: make
,09-02 15:26:12.260  6403  6804 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.gatt.GattService
09-02 15:26:12.260  6403  6804 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.gatt.GattService
09-02 15:26:12.260  6403  6804 W BluetoothAdapterService: Not skipping com.android.bluetooth.gatt.GattService
,09-02 15:26:12.260  1019  1031 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,09-02 15:26:12.260  1019  1031 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.gatt.GattService; callingUser = 0; userId(target) = 0
,09-02 15:26:12.260  1019  1031 W ActivityManager: userId = 0, bbcId = -10000
,09-02 15:26:12.260  1019  1031 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-02 15:26:12.260  1019  1031 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-02 15:26:12.260  6403  6804 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hfp.HeadsetService
09-02 15:26:12.260  6403  6804 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
09-02 15:26:12.260  6403  6804 W BluetoothAdapterService: Not skipping com.android.bluetooth.hfp.HeadsetService
,09-02 15:26:12.270  6403  6810 I BluetoothBondStateMachine: StableState(): Entering Off State
,09-02 15:26:12.270  6403  6403 D BtGatt.DebugUtils: handleDebugAction() action=null
,09-02 15:26:12.270  6403  6403 D BtGatt.GattService: Received start request. Starting profile...
,09-02 15:26:12.270  6403  6403 D BtGatt.GattService: start()
09-02 15:26:12.270  6403  6403 D BtGatt.GattService: start()
09-02 15:26:12.270  6403  6403 I bluedroid: get_profile_interface gatt
,09-02 15:26:12.270  6403  6403 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@7062407
09-02 15:26:12.270  6403  6403 D BtGatt.AdvertiseManager: advertise manager created
,09-02 15:26:12.280  1019  1082 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,09-02 15:26:12.280  1019  1082 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = 0
,09-02 15:26:12.280  1019  1082 W ActivityManager: userId = 0, bbcId = -10000
,09-02 15:26:12.280  1019  1082 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-02 15:26:12.280  1019  1082 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-02 15:26:12.280  6403  6804 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.a2dp.A2dpService
,09-02 15:26:12.280  6403  6804 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
09-02 15:26:12.280  6403  6804 W BluetoothAdapterService: Not skipping com.android.bluetooth.a2dp.A2dpService
09-02 15:26:12.280  1019  3214 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
09-02 15:26:12.280  1019  3214 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
,09-02 15:26:12.280  1019  3214 W ActivityManager: userId = 0, bbcId = -10000
09-02 15:26:12.280  1019  3214 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-02 15:26:12.280  1019  3214 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-02 15:26:12.290  6403  6804 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hid.HidService
09-02 15:26:12.290  6403  6804 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
09-02 15:26:12.290  6403  6804 W BluetoothAdapterService: Not skipping com.android.bluetooth.hid.HidService
,09-02 15:26:12.290  1019  1319 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
09-02 15:26:12.290  1019  1319 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hid.HidService; callingUser = 0; userId(target) = 0
09-02 15:26:12.290  1883  1883 D EasyUnlockReceiver: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.easyunlock.authorization.BluetoothStateChangeReceiver (has extras) }.
,09-02 15:26:12.290  6403  6403 D BtGatt.GattService: mStartError = false
09-02 15:26:12.290  6403  6403 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@7062407
09-02 15:26:12.290  1019  1319 W ActivityManager: userId = 0, bbcId = -10000
,09-02 15:26:12.290  1019  1319 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-02 15:26:12.290  1019  1319 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-02 15:26:12.290  6403  6403 D HeadsetService: Received start request. Starting profile...
09-02 15:26:12.290  6403  6403 D HeadsetService: start()
,09-02 15:26:12.290  6403  6403 I BluetoothHeadsetServiceJni: classInitNative: succeeds
,09-02 15:26:12.290  6403  6403 D HeadsetStateMachine: make
,09-02 15:26:12.300  6403  6804 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hdp.HealthService
,09-02 15:26:12.300  6403  6804 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
09-02 15:26:12.300  6403  6804 W BluetoothAdapterService: Not skipping com.android.bluetooth.hdp.HealthService
,09-02 15:26:12.300  6403  6403 E HeadsetStateMachine: # of Max HF connection is 2
09-02 15:26:12.300  1019  3093 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,09-02 15:26:12.300  1019  3093 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hdp.HealthService; callingUser = 0; userId(target) = 0
,09-02 15:26:12.300  1019  3093 W ActivityManager: userId = 0, bbcId = -10000
09-02 15:26:12.300  1019  3093 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-02 15:26:12.300  1019  3093 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-02 15:26:12.310  6403  6804 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.pan.PanService
09-02 15:26:12.310  6403  6804 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.pan.PanService
09-02 15:26:12.310  6403  6804 W BluetoothAdapterService: Not skipping com.android.bluetooth.pan.PanService
09-02 15:26:12.310  1883  1883 D BtServices: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.proximity.BluetoothServicesAdapterStateChangeReceiver (has extras) }.
,09-02 15:26:12.310  1019  1032 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
09-02 15:26:12.310  1019  1032 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pan.PanService; callingUser = 0; userId(target) = 0
,09-02 15:26:12.310  1019  1032 W ActivityManager: userId = 0, bbcId = -10000
09-02 15:26:12.310  1019  1032 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-02 15:26:12.310  1019  1032 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-02 15:26:12.310  1019  2952 D ActivityManager: bindService callerProcessName:com.android.bluetooth, calleePkgName: com.android.server.telecom, action: android.bluetooth.IBluetoothHeadsetPhone
09-02 15:26:12.310  1019  2952 D ActivityManager: retrieveServiceLocked(): component = com.android.server.telecom/com.android.server.telecom.BluetoothPhoneService; callingUser = 0; userId(target) = 0
,09-02 15:26:12.310  6403  6804 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.map.BluetoothMapService
09-02 15:26:12.310  6403  6804 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
09-02 15:26:12.310  6403  6804 W BluetoothAdapterService: Not skipping com.android.bluetooth.map.BluetoothMapService
09-02 15:26:12.310  1019  2952 W ActivityManager: userId = 0, bbcId = -10000
09-02 15:26:12.310  1019  2952 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-02 15:26:12.310  1019  2952 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.server.telecom
,09-02 15:26:12.320  1019  1485 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
09-02 15:26:12.320  1019  1485 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.map.BluetoothMapService; callingUser = 0; userId(target) = 0
,09-02 15:26:12.320  1019  1485 W ActivityManager: userId = 0, bbcId = -10000
09-02 15:26:12.320  1019  1485 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-02 15:26:12.320  1019  1485 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-02 15:26:12.320  6403  6804 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.broadcom.bt.service.sap.SapService
09-02 15:26:12.320  6403  6804 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
09-02 15:26:12.320  1019  3214 D ActivityManager: bindService callerProcessName:com.android.bluetooth, calleePkgName: com.android.server.telecom, action: com.samsung.bt.hfp.IBluetoothHeadsetVoIP
09-02 15:26:12.320  6403  6804 W BluetoothAdapterService: Not skipping com.broadcom.bt.service.sap.SapService
09-02 15:26:12.320  1019  3214 D ActivityManager: retrieveServiceLocked(): component = com.android.server.telecom/com.android.server.telecom.BluetoothVoIPService; callingUser = 0; userId(target) = 0
,09-02 15:26:12.320  1019  3214 W ActivityManager: userId = 0, bbcId = -10000
,09-02 15:26:12.320  1019  3214 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-02 15:26:12.320  1019  3214 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.server.telecom
09-02 15:26:12.330  6403  6403 I bluedroid: get_profile_interface handsfree
,09-02 15:26:12.330  1019  1319 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,09-02 15:26:12.330  1019  1319 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.broadcom.bt.service.sap.SapService; callingUser = 0; userId(target) = 0
,09-02 15:26:12.330  1019  1319 W ActivityManager: userId = 0, bbcId = -10000
09-02 15:26:12.330  1019  1319 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-02 15:26:12.330  1019  1319 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-02 15:26:12.330  6403  6804 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hfpclient.HeadsetClientService
09-02 15:26:12.330  6403  6804 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfpclient.HeadsetClientService
09-02 15:26:12.330  6403  6804 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.hfpclient.HeadsetClientService
09-02 15:26:12.330  6403  6804 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.a2dp.A2dpSinkService
09-02 15:26:12.330  6403  6804 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpSinkService
09-02 15:26:12.330  6403  6804 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.a2dp.A2dpSinkService
09-02 15:26:12.330  6403  6804 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.sapclient.SapClientService
09-02 15:26:12.330  6403  6804 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.sapclient.SapClientService
09-02 15:26:12.330  6403  6804 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.sapclient.SapClientService
09-02 15:26:12.330  6403  6804 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hid.HidDevService
09-02 15:26:12.330  6403  6804 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidDevService
09-02 15:26:12.330  6403  6804 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.hid.HidDevService
09-02 15:26:12.330  6403  6804 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=true, isTurningOff()=false
,09-02 15:26:12.340  6403  6403 I DualScoManager: Instantiating Dual Sco Manager
,09-02 15:26:12.340  6403  6403 I DualScoManager: Set HeadsetServiceHelper
,09-02 15:26:12.340  6403  6403 D BluetoothAtMessage: createCMTIContentObservers
09-02 15:26:12.340  1019  1223 D SettingsProvider: name = bluetooth_hfp_allowed_bvra
09-02 15:26:12.340  1019  1223 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
09-02 15:26:12.340  1019  1223 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
09-02 15:26:12.340  1019  1223 D SettingsProvider: selectionArgs: false
09-02 15:26:12.340  1019  1223 D SettingsProvider: selectionArgs: 1002
09-02 15:26:12.340  1019  1223 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
09-02 15:26:12.340  1019  1223 D SettingsProvider: ret = -1
09-02 15:26:12.350  6403  6813 D HeadsetStateMachine: Enter Disconnected: -2
09-02 15:26:12.350  6403  6403 D HeadsetService: mStartError = false
09-02 15:26:12.350  6403  6403 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@7062407
09-02 15:26:12.350  6403  6403 D A2dpService: Received start request. Starting profile...
09-02 15:26:12.350  6403  6403 D A2dpService: start()
09-02 15:26:12.350  6403  6813 D HeadsetStateMachine: Clear mHeadsetBrsf
09-02 15:26:12.350  6403  6813 D HeadsetStateMachine: map size, before remove : 0
09-02 15:26:12.350  6403  6813 D HeadsetStateMachine: map size, after remove: 0
09-02 15:26:12.350  6403  6403 I BluetoothAvrcpServiceJni: classInitNative: succeeds
,09-02 15:26:12.350  6403  6403 I bluedroid: get_profile_interface avrcp
,09-02 15:26:12.360  6403  6403 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,09-02 15:26:12.380  6403  6403 I Avrcp   :  Updating now playing list upon AVRCP Start
,09-02 15:26:12.380  6403  6817 D BluetoothMediaBrowser:  getNowPlayingListcontent://media/external/audio/playlists?secFilter=include
09-02 15:26:12.380  6403  6403 I BluetoothA2dpServiceJni: classInitNative: succeeds
09-02 15:26:12.380  6403  6403 D A2dpStateMachine: make
,09-02 15:26:12.380  6403  6403 I bluedroid: get_profile_interface a2dp
,09-02 15:26:12.380  6403  6819 I GKI_LINUX: gki_task_entry task_id=2 [A2DP-MEDIA] starting,
09-02 15:26:12.380  6403  6403 E bt-btif : warning : media task started media_task_refcnt 1 
,09-02 15:26:12.380  6403  6403 D A2dpService: mStartError = false
09-02 15:26:12.380  6403  6403 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@7062407
,09-02 15:26:12.380  6403  6403 E BluetoothAdapterService(117842951): processProfileServiceStateChanged() serviceName=com.android.bluetooth.gatt.GattService, state=12, doUpdate=false
,09-02 15:26:12.380  6403  6403 I BluetoothHidServiceJni: classInitNative: succeeds
,09-02 15:26:12.380  6403  6818 D A2dpStateMachine: Enter Disconnected: -2
,09-02 15:26:12.390  6403  6403 D HidService: Received start request. Starting profile...
09-02 15:26:12.390  6403  6403 D HidService: start()
09-02 15:26:12.390  6403  6403 I bluedroid: get_profile_interface hidhost
09-02 15:26:12.390  6403  6403 D HidService: setHidService(): set to: null
09-02 15:26:12.390  6403  6403 D HidService: mStartError = false
09-02 15:26:12.390  6403  6403 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@7062407
,09-02 15:26:12.390  6403  6403 I BluetoothHealthServiceJni: classInitNative: succeeds
,09-02 15:26:12.390  6403  6403 D HealthService: Received start request. Starting profile...
09-02 15:26:12.390  6403  6403 D HealthService: start()
,09-02 15:26:12.390  6403  6403 I bluedroid: get_profile_interface health
,09-02 15:26:12.390  6403  6403 D HealthService: mStartError = false
09-02 15:26:12.390  6403  6403 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@7062407
,09-02 15:26:12.390  6403  6403 I BluetoothPanServiceJni: classInitNative(L105): succeeds
,09-02 15:26:12.400  6403  6403 D PanService: Received start request. Starting profile...
09-02 15:26:12.400  6403  6403 D PanService: start()
09-02 15:26:12.400  6403  6403 D BluetoothPanServiceJni: initializeNative(L110): pan
09-02 15:26:12.400  6403  6403 I bluedroid: get_profile_interface pan
,09-02 15:26:12.400  6403  6403 D PanService: mStartError = false
09-02 15:26:12.400  6403  6403 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@7062407
,09-02 15:26:12.400  6403  6403 D HeadsetStateMachine: Try to query the phonestate on bind
,09-02 15:26:12.400  1433  1453 I Telecom : BluetoothPhoneService: queryPhoneState
,09-02 15:26:12.400  1433  1433 I Telecom : BluetoothPhoneService: handleMessage(7) / param 0
,09-02 15:26:12.400  1433  1433 I Telecom : BluetoothPhoneService: updateHeadsetWithCallState
,09-02 15:26:12.400  1433  1453 I Telecom : BluetoothPhoneService: Result of Message : true
,09-02 15:26:12.400  6403  6817 D BluetoothMediaBrowser: no now playing list
,09-02 15:26:12.400  6403  6817 D BluetoothMediaBrowser:  getNowPlayingId now playing id : -1
,09-02 15:26:12.410  6403  6403 D BluetoothMapService: Received start request. Starting profile...
,09-02 15:26:12.410  6403  6403 D BluetoothMapService: start()
,09-02 15:26:12.410  6403  6403 D BluetoothMapService: mStartError = false
09-02 15:26:12.410  6403  6403 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@7062407
,09-02 15:26:12.410  6403  6403 D HeadsetStateMachine: Proxy object connected
,09-02 15:26:12.410  6403  6403 I BluetoothSAPServiceJni: classInitNative(L204): succeeds
,09-02 15:26:12.410  6403  6403 D SapService: Received start request. Starting profile...
,09-02 15:26:12.410  6403  6403 D SapService: start()
09-02 15:26:12.410  6403  6403 D BluetoothSAPServiceJni: initializeNative(L209): sap
,09-02 15:26:12.410  6403  6403 I bluedroid: get_profile_interface sap
09-02 15:26:12.410  6403  6403 D SapService: mStartError = false
09-02 15:26:12.410  6403  6403 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@7062407
,09-02 15:26:12.410  6403  6403 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=0
,09-02 15:26:12.410  6403  6403 D HeadsetPhoneState: sendDeviceDataStateChanged,
09-02 15:26:12.410  6403  6813 D HeadsetStateMachine: Disconnected process message: 11
09-02 15:26:12.410  6403  6813 D HeadsetStateMachine: Disconnected process message: 18,
09-02 15:26:12.410  6403  6403 D HeadsetPhoneState: Signal level : previous=0 curr=0
09-02 15:26:12.410  6403  6403 E BluetoothAdapterService(117842951): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hfp.HeadsetService, state=12, doUpdate=true
09-02 15:26:12.410  6403  6403 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
09-02 15:26:12.410  6403  6403 D BluetoothA2dp: Proxy object connected
,09-02 15:26:12.410  6403  6813 D HeadsetStateMachine: Disconnected process message: 10
09-02 15:26:12.410  6403  6403 D BluetoothAdapterService: Bluetooth A2dp source service connected
09-02 15:26:12.410  6403  6403 E BluetoothAdapterService(117842951): processProfileServiceStateChanged() serviceName=com.android.bluetooth.a2dp.A2dpService, state=12, doUpdate=true
09-02 15:26:12.410  6403  6403 E BluetoothAdapterService(117842951): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hid.HidService, state=12, doUpdate=true
09-02 15:26:12.410  6403  6403 E BluetoothAdapterService(117842951): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hdp.HealthService, state=12, doUpdate=true
09-02 15:26:12.420  6403  6403 E BluetoothAdapterService(117842951): processProfileServiceStateChanged() serviceName=com.android.bluetooth.pan.PanService, state=12, doUpdate=true
,09-02 15:26:12.420  6403  6813 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
,09-02 15:26:12.420  6403  6813 D HeadsetStateMachine: Disconnected process message: 11
,09-02 15:26:12.440  6403  6403 E BluetoothAdapterService(117842951): processProfileServiceStateChanged() serviceName=com.android.bluetooth.map.BluetoothMapService, state=12, doUpdate=true
,09-02 15:26:12.440  6403  6403 E BluetoothAdapterService(117842951): processProfileServiceStateChanged() serviceName=com.broadcom.bt.service.sap.SapService, state=12, doUpdate=true
,09-02 15:26:12.450  6403  6804 D BluetoothAdapterState: CURRENT_STATE=PENDING, MSG = STARTED, isTurningOn=true, isTurningOff=false
,09-02 15:26:12.450  6403  6804 I bluedroid: enable
09-02 15:26:12.450  6403  6804 I bt_hci_bdroid: init
,09-02 15:26:12.450  6403  6824 I GKI_LINUX: gki_task_entry task_id=0 [BTU] starting
,09-02 15:26:12.450  6403  6804 I bt_vendor: bt-vendor : init
,09-02 15:26:12.450  6403  6804 I bt_vendor: bt-vendor : get_bt_soc_type
09-02 15:26:12.450  6403  6804 E bt_vendor: get_bt_soc_type: Failed to get soc type
,09-02 15:26:12.450  6403  6804 I bt_vendor: init: Local BD Address : ab:96:37:0e:f9:7c
09-02 15:26:12.450  6403  6804 D bt_userial_mct: userial_init
,09-02 15:26:12.450  6403  6804 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: Off
,09-02 15:26:12.450  6403  6804 I bt_vendor: Starting hciattach daemon
09-02 15:26:12.450  6403  6804 I bt_vendor: try to set false
,09-02 15:26:12.470  6403  6804 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: On
09-02 15:26:12.470  6403  6804 I bt_vendor: Starting hciattach daemon
09-02 15:26:12.470  6403  6804 I bt_vendor: try to set true
,09-02 15:26:12.490  6830  6830 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: init.qcom.bt.sh config =  ,
,09-02 15:26:12.540  6836  6836 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Transport : smd ,
,09-02 15:26:12.550  6837  6837 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** ,
,09-02 15:26:12.570  6839  6839 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Power Class: Ignored. Default(1) used (1-CLASS1/2-CLASS2/3-CUSTOM) ,
,09-02 15:26:12.580  6840  6840 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Power Class: To override, Before turning BT ON; setprop qcom.bt.dev_power_class <1 or 2 or 3> ,
,09-02 15:26:12.590  6841  6841 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: LE Power Class: Ignored. Default(2) used (1-CLASS1/2-CLASS2/3-CUSTOM) ,
,09-02 15:26:12.590  6842  6842 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: LE Power Class: To override, Before turning BT ON; setprop qcom.bt.le_dev_pwr_class <1 or 2 or 3> ,
,09-02 15:26:12.660   338   338 I ServiceManager: Waiting for service AtCmdFwd...
,09-02 15:26:12.800  6845  6845 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Bluetooth QSoC firmware download succeeded, /dev/ttyHS0 qualcomm 3000000 7c:f9:0e:37:96:ab ,
,09-02 15:26:12.810  6846  6846 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** ,
,09-02 15:26:12.830  6403  6804 I bt_vendor: bluetooth satus is on,
09-02 15:26:12.830  6403  6826 D bt_userial_mct: userial_open(port:0)
09-02 15:26:12.830  6403  6826 I bt_vendor: bt-vendor : BT_VND_OP_USERIAL_OPEN,
,09-02 15:26:12.830  6403  6826 I bt_vendor: Done intiailizing UART
,09-02 15:26:12.830  6403  6826 I bt_vendor: Done intiailizing UART,
09-02 15:26:12.830  6403  6826 I bt_userial_mct: CMD=66, EVT=66, ACL_Out=67, ACL_In=67
09-02 15:26:12.830  6403  6826 I bt_vendor: Bluetooth Firmware and transport layer are initialized,
,09-02 15:26:12.840  6403  6848 D bt_userial_mct: Entering userial_read_thread()
,09-02 15:26:12.840  6403  6824 I         : BTE_InitTraceLevels -- TRC_HCI
,09-02 15:26:12.840  6403  6824 I         : BTE_InitTraceLevels -- TRC_L2CAP
09-02 15:26:12.840  6403  6824 I         : BTE_InitTraceLevels -- TRC_RFCOMM
,09-02 15:26:12.840  6403  6824 I         : BTE_InitTraceLevels -- TRC_AVDT
,09-02 15:26:12.840  6403  6824 I         : BTE_InitTraceLevels -- TRC_AVRC
09-02 15:26:12.840  6403  6824 I         : BTE_InitTraceLevels -- TRC_A2D
,09-02 15:26:12.840  6403  6824 I         : BTE_InitTraceLevels -- TRC_BNEP
09-02 15:26:12.840  6403  6824 I         : BTE_InitTraceLevels -- TRC_BTM
,09-02 15:26:12.840  6403  6824 I         : BTE_InitTraceLevels -- TRC_GAP
09-02 15:26:12.840  6403  6824 I         : BTE_InitTraceLevels -- TRC_PAN
,09-02 15:26:12.850  6403  6824 I         : BTE_InitTraceLevels -- TRC_SAP
09-02 15:26:12.850  6403  6824 I         : BTE_InitTraceLevels -- TRC_SDP
09-02 15:26:12.850  6403  6824 I         : BTE_InitTraceLevels -- TRC_GATT
09-02 15:26:12.850  6403  6824 I         : BTE_InitTraceLevels -- TRC_SMP
09-02 15:26:12.850  6403  6824 I         : BTE_InitTraceLevels -- TRC_BTAPP
09-02 15:26:12.850  6403  6824 I         : BTE_InitTraceLevels -- TRC_BTIF
09-02 15:26:12.850  6403  6824 I         : BTE_InitTraceLevels -- TRC_PROTOCOL
,09-02 15:26:12.950  6403  6824 W bt-l2cap: l2c_link_processs_ble_num_bufs 16
,09-02 15:26:12.950  6403  6824 E bt-btm  : BTM_SecRegister:p_cb_info->p_le_callback == 0xa3f626e9 
,09-02 15:26:12.950  6403  6824 E bt-btm  : BTM_SecRegister: btm_cb.api.p_le_callback = 0xa3f626e9 
,09-02 15:26:12.970  6403  6807 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 10 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 32 mNumOfOffloadedScanFilterSupported = 16 mOffloadedScanResultStorageBytes= 10240 mIsActivityAndEnergyReporting = true mAobleSupported = 0
,09-02 15:26:12.970  6403  6807 E bt-btif : Calling BTA_HhEnable
,09-02 15:26:12.980  6403  6807 E bt-btif : btif_storage_get_adapter_property service_mask:0x2120048
,09-02 15:26:12.980  6403  6807 D BluetoothAdapterProperties: Address is:7C:F9:0E:37:96:AB
,09-02 15:26:12.980  6403  6807 E BluetoothServiceJni: populateRssiValuesNative
09-02 15:26:12.980  6403  6807 I bluedroid: getModelRssiValues
09-02 15:26:12.980  6403  6807 E BluetoothServiceJni: model_rssi_values_callback: low = -70, mid = -60, high = 127
09-02 15:26:12.980  6403  6807 D BluetoothAdapterProperties: modelRssiValuesCallback, low, mid, high = -70,-60,127
,09-02 15:26:12.980  6403  6807 D BluetoothAdapterProperties: Name is: A5-1
,09-02 15:26:12.980  1019  1019 D SettingsProvider: name = bluetooth_name,
,09-02 15:26:12.990  6212  6212 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-02 15:26:12.990  6212  6212 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-02 15:26:12.990  6403  6807 D BluetoothUtils: getBtEnabledContainers(): btContainers = []
,09-02 15:26:12.990  6403  6807 D BluetoothAdapterProperties: Scan Mode:20
09-02 15:26:12.990  6403  6807 D BluetoothAdapterProperties: Discoverable Timeout:120
09-02 15:26:12.990  6403  6807 D BluetoothAdapterProperties: LE Address is:FC:F3:1C:6E:2D:57
09-02 15:26:12.990  6403  6807 E bt-btif : btif_handle_bluetooth_enable_evt: btif_core_radio_ref_count:1
09-02 15:26:12.990  6403  6807 E bt-btif : btif_sock_init, radio_req:0, rfc_init:0, vhci_init:0
09-02 15:26:12.990  6403  6807 E bt-btif : btif_sock_init: !radio_req && !rfc_init
09-02 15:26:12.990  6403  6807 E bt-btif : btif_sock_init: !vhci_init
09-02 15:26:12.990  6403  6807 D IOP_DB_BT: db_open: file /etc/bluetooth/iop_bt.db
,09-02 15:26:13.000  6403  6807 D IOP_DB_BT: db_open: db_open : handle 3025874960l, read 13894 bytes onto local cache
,09-02 15:26:13.000  6403  6807 D IOP_DB_BT: db_query: id __IOPFLAGS :: key __KEY_ENABLE_VERBOSE, value 1
,09-02 15:26:13.000  6403  6807 D IOP_DB_BT: db_query: result 1
,09-02 15:26:13.000  6403  6807 I         : iop_db_open: iop_db_open status 0
,09-02 15:26:13.000  6403  6807 D bte_conf: Device ID record 1 : primary
,09-02 15:26:13.000  6403  6807 D bte_conf:   vendorId            = 0075
,09-02 15:26:13.000  6403  6807 D bte_conf:   vendorIdSource      = 0001
09-02 15:26:13.000  6403  6807 D bte_conf:   product             = 0100
09-02 15:26:13.000  6403  6807 D bte_conf:   version             = 0200
09-02 15:26:13.000  6403  6807 D bte_conf:   clientExecutableURL = 
09-02 15:26:13.000  6403  6807 D bte_conf:   serviceDescription  = 
09-02 15:26:13.000  6403  6807 D bte_conf:   documentationURL    = 
09-02 15:26:13.000  6403  6807 D bte_conf: bte_load_did_conf no section named DID2.
09-02 15:26:13.000  6403  6807 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
,09-02 15:26:13.000  6403  6804 D BluetoothAdapterState: CURRENT_STATE=PENDING, MSG = ENABLE_READY, isTurningOn=true, isTurningOff=false
,09-02 15:26:13.000  6403  6804 D BluetoothAdapterProperties: ScanMode =  20
,09-02 15:26:13.010  6403  6804 D BluetoothAdapterProperties: State =  11
09-02 15:26:13.010  6403  6848 E bt_mct  : hci lib postload completed
,09-02 15:26:13.010  1019  2903 D SecContentProvider: uri = 3 selection = isDiscoverableEnabled
,09-02 15:26:13.010  6403  6804 D BluetoothAdapterProperties: Setting state to 12,
09-02 15:26:13.010  6403  6804 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
,09-02 15:26:13.010  6403  6807 D BluetoothUtils: getBtEnabledContainers(): btContainers = []
09-02 15:26:13.010  6403  6807 D BluetoothAdapterProperties: Scan Mode:21
,09-02 15:26:13.010  1019  3105 D SettingsProvider: name = bluetooth_a2dp_sink_mode
,09-02 15:26:13.010  1019  3105 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
09-02 15:26:13.010  1019  3105 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
09-02 15:26:13.010  1019  3105 D SettingsProvider: selectionArgs: false
09-02 15:26:13.010  1019  3105 D SettingsProvider: selectionArgs: 1002
09-02 15:26:13.010  1019  3105 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
09-02 15:26:13.010  1019  3105 D SettingsProvider: ret = -1
,09-02 15:26:13.020  6403  6807 D BluetoothAdapterProperties: Discoverable Timeout:120
,09-02 15:26:13.020  6403  6804 D BluetoothAdapterService: Bluetooth PBAP supproted is true
09-02 15:26:13.020  6403  6804 D BluetoothAdapterService: updateAdapterState state is 12
,09-02 15:26:13.020  1019  1031 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,09-02 15:26:13.020  1019  1031 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pbap.BluetoothPbapService; callingUser = 0; userId(target) = 0
,09-02 15:26:13.020  1019  1031 W ActivityManager: userId = 0, bbcId = -10000
,09-02 15:26:13.020  1019  1031 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-02 15:26:13.020  1019  1031 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-02 15:26:13.020  6212  6212 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-02 15:26:13.020  6212  6212 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-02 15:26:13.020  6212  6212 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-02 15:26:13.020  6212  6212 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-02 15:26:13.020  6212  6212 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-02 15:26:13.020  6212  6212 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-02 15:26:13.020  6212  6212 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-02 15:26:13.020  6212  6212 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-02 15:26:13.030  6403  6804 D BluetoothAdapterService: Autoconnection is available 
,09-02 15:26:13.030  6403  6804 D BluetoothAdapterService: updateAdapterState prevState = 11newState = 12
,09-02 15:26:13.030  6403  6804 D BluetoothAdapterService: starting service from this receiver
,09-02 15:26:13.030  1019  1082 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,09-02 15:26:13.030  1019  1082 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.samsung.ble.BleAutoConnectService; callingUser = 0; userId(target) = 0
,09-02 15:26:13.030  1019  1082 W ActivityManager: userId = 0, bbcId = -10000
,09-02 15:26:13.030  1019  1082 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,09-02 15:26:13.030  1019  1082 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-02 15:26:13.040  1296  1309 D Bluetoothsap: onBluetoothStateChange: up=true
,09-02 15:26:13.040  1296  1309 D Bluetoothsap: Binding service...
,09-02 15:26:13.040  1296  1309 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:2136 android.content.ContextWrapper.bindService:559 com.broadcom.bt.service.sap.BluetoothSap.doBind:186 com.broadcom.bt.service.sap.BluetoothSap$1.onBluetoothStateChange:156 android.bluetooth.IBluetoothStateChangeCallback$Stub.onTransact:55 
,09-02 15:26:13.040  6403  6804 I BluetoothAdapterState: Entering On State from state = 11
09-02 15:26:13.040  1019  1050 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: com.broadcom.bt.service.sap.IBluetoothSap
09-02 15:26:13.040  1019  1050 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.broadcom.bt.service.sap.SapService; callingUser = 0; userId(target) = 0
,09-02 15:26:13.040  6212  6212 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-02 15:26:13.050  1019  1050 W ActivityManager: userId = 0, bbcId = -10000
,09-02 15:26:13.050  1019  1050 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-02 15:26:13.050  1019  1050 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,09-02 15:26:13.050  1296  1309 D Bluetoothsap: bindService called to Bluetooth SAP Service
,09-02 15:26:13.050  1433  1451 D BluetoothAdapter: onBluetoothStateChange: up=true
,09-02 15:26:13.050  1433  1451 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,09-02 15:26:13.050  6403  6411 D BluetoothAdapter: onBluetoothStateChange: up=true
09-02 15:26:13.050  6403  6411 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,09-02 15:26:13.050  6403  6403 I BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED, state: 12
,09-02 15:26:13.060  1296  6395 D BluetoothAdapter: onBluetoothStateChange: up=true
,09-02 15:26:13.060  1296  6395 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,09-02 15:26:13.060  6212  6212 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-02 15:26:13.060  6212  6212 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-02 15:26:13.060  6212  6212 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-02 15:26:13.060  6212  6212 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-02 15:26:13.060  6212  6212 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-02 15:26:13.060  6212  6212 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-02 15:26:13.060  6212  6212 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-02 15:26:13.060  6212  6212 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-02 15:26:13.060  1444  1456 D BluetoothAdapter: onBluetoothStateChange: up=true
09-02 15:26:13.060  1444  1456 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,09-02 15:26:13.060  1296  1307 D BluetoothPan: Binding service...
,09-02 15:26:13.060  1019  1050 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothPan
09-02 15:26:13.060  1019  1050 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pan.PanService; callingUser = 0; userId(target) = 0
,09-02 15:26:13.070  1019  1050 W ActivityManager: userId = 0, bbcId = -10000
09-02 15:26:13.070  1019  1050 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-02 15:26:13.070  1019  1050 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,09-02 15:26:13.070  6212  6212 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-02 15:26:13.070  1019  1050 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,09-02 15:26:13.070  1019  1050 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
09-02 15:26:13.070  1019  1050 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,09-02 15:26:13.070  6403  6403 I BluetoothPbapService: Handler(): got msg=1
,09-02 15:26:13.070  1019  1050 E BluetoothHeadset: BluetoothHeadset service is binded
09-02 15:26:13.070  6212  6221 D BluetoothAdapter: onBluetoothStateChange: up=true
09-02 15:26:13.070  6212  6221 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,09-02 15:26:13.070  1296  1296 D Bluetoothsap: BluetoothSAP Proxy object connected
09-02 15:26:13.070  1296  1296 D SapProfile: Bluetooth service connected
09-02 15:26:13.070  1296  1296 D Bluetoothsap: getConnectedDevices()
,09-02 15:26:13.070  1182  1206 D BluetoothAdapter: onBluetoothStateChange: up=true
,09-02 15:26:13.070  1019  1223 D SecContentProvider: uri = 4 selection = isProfileAuthorizedBySecurityPolicy
09-02 15:26:13.070  1182  1206 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,09-02 15:26:13.070  1883  1903 D BluetoothAdapter: onBluetoothStateChange: up=true
09-02 15:26:13.070  1883  1903 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,09-02 15:26:13.080  6368  6381 D BluetoothAdapter: onBluetoothStateChange: up=true
09-02 15:26:13.080  6368  6381 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,09-02 15:26:13.080  1296  6395 D BluetoothPbap: onBluetoothStateChange: up=true
,09-02 15:26:13.080  1296  1296 D BluetoothPan: BluetoothPAN Proxy object connected
09-02 15:26:13.080  1296  1296 D PanProfile: Bluetooth service connected
,09-02 15:26:13.080  1019  1050 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothPbap
09-02 15:26:13.080  1019  1050 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pbap.BluetoothPbapService; callingUser = 0; userId(target) = 0
,09-02 15:26:13.080  1019  1050 W ActivityManager: userId = 0, bbcId = -10000
09-02 15:26:13.080  1019  1050 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-02 15:26:13.080  1019  1050 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,09-02 15:26:13.080  1433  1453 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,09-02 15:26:13.080  1019  1050 D ActivityManager: bindService callerProcessName:com.android.server.telecom, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
,09-02 15:26:13.080  1019  1050 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,09-02 15:26:13.090  1019  1050 W ActivityManager: userId = 0, bbcId = -10000
,09-02 15:26:13.090  1019  1050 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-02 15:26:13.090  1019  1050 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.server.telecom, destAppInfo.processName = com.android.bluetooth
,09-02 15:26:13.090  6403  6851 V BluetoothPbapService: PBAP Service initSocket try: 0
,09-02 15:26:13.090  1433  1453 E BluetoothHeadset: BluetoothHeadset service is binded
,09-02 15:26:13.090  1019  1050 D BluetoothAdapter: onBluetoothStateChange: up=true
09-02 15:26:13.090  1019  1050 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
09-02 15:26:13.090  2850  2863 D BluetoothA2dp: onBluetoothStateChange: up=true
,09-02 15:26:13.090  2850  2863 D BluetoothA2dp: doBind(): CallingUid(myUserHandle) = 0
,09-02 15:26:13.090  1296  1296 D BluetoothPbap: Proxy object connected
09-02 15:26:13.090  1019  1050 D ActivityManager: bindService callerProcessName:com.samsung.android.providers.context, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothA2dp
09-02 15:26:13.090  1019  1050 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
,09-02 15:26:13.090  1019  1050 W ActivityManager: userId = 0, bbcId = -10000
09-02 15:26:13.090  1019  1050 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-02 15:26:13.090  1296  1296 D PbapServerProfile: Bluetooth service connected
09-02 15:26:13.090  1019  1050 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.android.providers.context, destAppInfo.processName = com.android.bluetooth
,09-02 15:26:13.090  2850  2850 D BluetoothA2dp: Proxy object connected
09-02 15:26:13.090  1296  1307 D BluetoothInputDevice: onBluetoothStateChange: up=true
,09-02 15:26:13.100  6403  6851 D BluetoothSocket: bindListen(): myUserId = 0
09-02 15:26:13.100  6403  6851 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-02 15:26:13.100  1019  1050 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothInputDevice
09-02 15:26:13.100  1019  1050 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hid.HidService; callingUser = 0; userId(target) = 0
,09-02 15:26:13.100  1019  1050 W ActivityManager: userId = 0, bbcId = -10000
09-02 15:26:13.100  1019  1050 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-02 15:26:13.100  1019  1050 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,09-02 15:26:13.100  6403  6415 D BluetoothA2dp: onBluetoothStateChange: up=true
,09-02 15:26:13.100  6403  6851 D BluetoothSocket: bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[75]}
09-02 15:26:13.100  1019  1050 D BluetoothPan: Binding service...
09-02 15:26:13.100  6403  6851 D BluetoothSocket: bindListen(), new LocalSocket 
09-02 15:26:13.100  6403  6851 D BluetoothSocket: bindListen(), new LocalSocket.getInputStream() 
09-02 15:26:13.100  6403  6851 D BluetoothSocket: bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@271a9c30
09-02 15:26:13.100  6403  6851 D BluetoothSocket: channel: 19
09-02 15:26:13.100  6403  6851 D BluetoothPbapService: PBAP Socket is BluetoothServerSocket
,09-02 15:26:13.100  1019  1050 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothPan
09-02 15:26:13.100  1019  1019 D BluetoothPan: BluetoothPAN Proxy object connected
09-02 15:26:13.100  1019  1050 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pan.PanService; callingUser = 0; userId(target) = 0
,09-02 15:26:13.100  1296  1296 D BluetoothInputDevice: Proxy object connected
,09-02 15:26:13.100  1296  1296 D HidProfile: Bluetooth service connected
,09-02 15:26:13.100  1296  1309 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,09-02 15:26:13.110  1019  1050 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
09-02 15:26:13.110  1019  1050 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,09-02 15:26:13.110  1019  1050 W ActivityManager: userId = 0, bbcId = -10000
09-02 15:26:13.110  1019  1050 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-02 15:26:13.110  1019  1050 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,09-02 15:26:13.110  1296  1309 E BluetoothHeadset: BluetoothHeadset service is binded
,09-02 15:26:13.110  1460  1687 D BluetoothAdapter: onBluetoothStateChange: up=true
09-02 15:26:13.110  1460  1687 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
09-02 15:26:13.110  1296  1296 D HeadsetProfile: Bluetooth service connected
,09-02 15:26:13.110  2850  2858 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,09-02 15:26:13.110  1019  1050 D ActivityManager: bindService callerProcessName:com.samsung.android.providers.context, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
09-02 15:26:13.110  1019  1050 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,09-02 15:26:13.110  1019  1050 W ActivityManager: userId = 0, bbcId = -10000
09-02 15:26:13.110  1019  1050 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-02 15:26:13.110  1019  1050 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.android.providers.context, destAppInfo.processName = com.android.bluetooth
,09-02 15:26:13.110  2850  2858 E BluetoothHeadset: BluetoothHeadset service is binded
,09-02 15:26:13.120  1433  1453 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,09-02 15:26:13.120  1019  1050 D ActivityManager: bindService callerProcessName:com.android.server.telecom, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
09-02 15:26:13.120  1019  1050 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,09-02 15:26:13.120  1019  1050 W ActivityManager: userId = 0, bbcId = -10000
09-02 15:26:13.120  1019  1050 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-02 15:26:13.120  1019  1050 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.server.telecom, destAppInfo.processName = com.android.bluetooth
,09-02 15:26:13.120  1433  1453 E BluetoothHeadset: BluetoothHeadset service is binded
09-02 15:26:13.120  1019  1050 D BluetoothA2dp: onBluetoothStateChange: up=true
,09-02 15:26:13.120  1019  1050 D BluetoothA2dp: doBind(): CallingUid(myUserHandle) = 0
09-02 15:26:13.120  1019  1050 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothA2dp
09-02 15:26:13.120  1019  1050 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
,09-02 15:26:13.120  1019  1019 D BluetoothA2dp: Proxy object connected
,09-02 15:26:13.120  1460  2431 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,09-02 15:26:13.120  1019  1050 D ActivityManager: bindService callerProcessName:com.android.phone, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
,09-02 15:26:13.120  1019  1050 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,09-02 15:26:13.130  1019  1050 W ActivityManager: userId = 0, bbcId = -10000
09-02 15:26:13.130  1019  1050 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-02 15:26:13.130  1019  1050 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = com.android.bluetooth
,09-02 15:26:13.130  1460  2431 E BluetoothHeadset: BluetoothHeadset service is binded
,09-02 15:26:13.130  1433  6854 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,09-02 15:26:13.130  1019  1050 D ActivityManager: bindService callerProcessName:com.android.server.telecom, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
09-02 15:26:13.130  1019  1050 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,09-02 15:26:13.130  1019  1050 W ActivityManager: userId = 0, bbcId = -10000
09-02 15:26:13.130  1019  1050 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-02 15:26:13.130  1019  1050 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.server.telecom, destAppInfo.processName = com.android.bluetooth
,09-02 15:26:13.130  1433  6854 E BluetoothHeadset: BluetoothHeadset service is binded
,09-02 15:26:13.130  2850  6855 D BluetoothAdapter: onBluetoothStateChange: up=true
09-02 15:26:13.130  2850  6855 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,09-02 15:26:13.130  1296  6395 D BluetoothA2dp: onBluetoothStateChange: up=true
,09-02 15:26:13.130  1296  6395 D BluetoothA2dp: doBind(): CallingUid(myUserHandle) = 0
,09-02 15:26:13.130  1019  1050 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothA2dp
,09-02 15:26:13.130  1019  1050 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
,09-02 15:26:13.140  1019  1050 W ActivityManager: userId = 0, bbcId = -10000
,09-02 15:26:13.140  1019  1050 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,09-02 15:26:13.140  1019  1050 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,09-02 15:26:13.140  1296  1296 D BluetoothA2dp: Proxy object connected
09-02 15:26:13.140  1296  1296 D A2dpProfile: Bluetooth service connected
,09-02 15:26:13.140  1296  1307 D BluetoothMap: onBluetoothStateChange: up=true
,09-02 15:26:13.140  1019  1050 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothMap
09-02 15:26:13.140  1019  1050 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.map.BluetoothMapService; callingUser = 0; userId(target) = 0
,09-02 15:26:13.140  1019  1050 W ActivityManager: userId = 0, bbcId = -10000
09-02 15:26:13.140  1019  1050 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,09-02 15:26:13.140  1019  1050 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,09-02 15:26:13.150  1019  1050 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothGatt
09-02 15:26:13.150  1019  1050 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.gatt.GattService; callingUser = 0; userId(target) = -2
,09-02 15:26:13.150  1296  1296 D BluetoothMap: Proxy object connected
,09-02 15:26:13.150  1296  1296 D MapProfile: Bluetooth service connected
09-02 15:26:13.150  1296  1296 D BluetoothMap: getConnectedDevices()
,09-02 15:26:13.150  1019  1019 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
09-02 15:26:13.150  1019  1019 I InputMethodManagerService: [BT Setting State] State =12
09-02 15:26:13.150  1019  1019 I InputMethodManagerService: [BT Setting off -> on] mBTKeyboardCount =0, KEYBOARD_BT(0)
,09-02 15:26:13.150  1182  1182 D BluetoothTile:  onBluetoothStateChange:
,09-02 15:26:13.150  1433  1433 D BluetoothHeadset: registerListener : 11, listenercom.android.server.telecom.wearable.BluetoothMessageListener@1a1d76df, true
,09-02 15:26:13.160  1433  1433 D BluetoothHeadset: registerMessageListener
,09-02 15:26:13.160  1182  1182 D BluetoothTile:  onBluetoothPairedDevicesChanged:
09-02 15:26:13.160  1182  1182 D BluetoothTile: onReceive : android.bluetooth.adapter.action.STATE_CHANGED
09-02 15:26:13.160  1182  1182 D BluetoothTile:  getBluetoothState : 12
,09-02 15:26:13.160  1954  1954 I SamsungIME: STATE_CHANGED = 12, KEYBOARD_BT(0), mBTKeyboardCount =0
,09-02 15:26:13.160  1019  1485 D StatusBarManagerService: setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
,09-02 15:26:13.170  1019  1485 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=true
,09-02 15:26:13.170  1182  1182 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
,09-02 15:26:13.170  1182  1704 D BluetoothTile:  handleUpdatestate:false name:null
,09-02 15:26:13.170  6212  6212 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-02 15:26:13.170  1182  1704 D BluetoothTile:  handleUpdatestate:false name:null
,09-02 15:26:13.170  6403  6411 D HeadsetService: registerMessageListener
,09-02 15:26:13.170  1019  3109 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
09-02 15:26:13.170  6403  6411 D HeadsetService: registerMessageListener
09-02 15:26:13.170  1019  3109 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.nearby.discovery.service.DiscoveryService; callingUser = 0; userId(target) = 0
09-02 15:26:13.170  6403  6813 D HeadsetStateMachine: Disconnected process message: 70
09-02 15:26:13.170  1433  1433 I Telecom : BluetoothPhoneService: handleMessage(7) / param null
09-02 15:26:13.170  6403  6813 D HeadsetStateMachine: processRegisterMessageListener : 11, com.samsung.bt.hfp.IMessageListener$Stub$Proxy@3f0b50a9
,09-02 15:26:13.170  1433  1433 I Telecom : BluetoothPhoneService: updateHeadsetWithCallState
09-02 15:26:13.170  1019  3109 W ActivityManager: userId = 0, bbcId = -10000
,09-02 15:26:13.170  1019  3109 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-02 15:26:13.170  1019  3109 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
09-02 15:26:13.180  1296  1296 V BluetoothEventManager: Received android.bluetooth.adapter.action.STATE_CHANGED
09-02 15:26:13.180  6212  6212 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-02 15:26:13.180  1182  1704 D BluetoothTile:  handleUpdatestate:false name:null
,09-02 15:26:13.180  1433  1433 I Telecom : BluetoothPhoneService: getCurrentCallPhoneType, Defalut Phonetype : 1
,09-02 15:26:13.180  1433  1433 I Telecom : BluetoothPhoneService: getCurrentCallPhoneType, Current Phonetype : 1
09-02 15:26:13.180  6403  6856 D BluetoothMapMasInstance: set MAP SDP message type : 1
,09-02 15:26:13.180  1433  1433 I Telecom : BluetoothPhoneService: updateHeadsetWithCallState numActive 0, numHeld 0, callState 6, ringing number [da39a3ee5e6b4b0d3255bfef95601890afd80709], ringing type 128
,09-02 15:26:13.190  6403  6813 D HeadsetStateMachine: Disconnected process message: 9
,09-02 15:26:13.190  6403  6813 D HeadsetStateMachine: mNumActive: 0 mNumHeld: 0 mCallState: 6
,09-02 15:26:13.190  6403  6856 D BluetoothSocket: bindListen(): myUserId = 0
,09-02 15:26:13.190  6403  6856 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-02 15:26:13.190  1296  1296 W LocalBluetoothProfileManager: Warning: MAP profile was previously added but the UUID is now missing.
,09-02 15:26:13.190  1296  1296 W LocalBluetoothProfileManager: Warning: PBAP profile was previously added but the UUID is now missing.
09-02 15:26:13.190  1296  1296 W LocalBluetoothProfileManager: Warning: SAP profile was previously added but the UUID is now missing.
09-02 15:26:13.190  1296  1296 W LocalBluetoothProfileManager: Warning: HID profile was previously added but the UUID is now missing.
,09-02 15:26:13.200  6403  6856 D BluetoothSocket: bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[77]}
09-02 15:26:13.200  6403  6856 D BluetoothSocket: bindListen(), new LocalSocket 
09-02 15:26:13.200  6403  6856 D BluetoothSocket: bindListen(), new LocalSocket.getInputStream() 
09-02 15:26:13.200  6403  6856 D BluetoothSocket: bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@161b062e
09-02 15:26:13.200  6403  6856 D BluetoothSocket: channel: 5
,09-02 15:26:13.200   283  1017 D audio_hw_primary: adev_set_parameters: enter: A2dpSuspended=false
09-02 15:26:13.200   283  1017 V voice   : voice_set_parameters: enter: A2dpSuspended=false
09-02 15:26:13.200   283  1017 V voice   : voice_set_parameters: exit with code(-2)
09-02 15:26:13.200   283  1017 V msm8974_platform: platform_set_parameters: enter: A2dpSuspended=false
09-02 15:26:13.200   283  1017 V msm8974_platform: platform_set_parameters: exit with code(-2)
09-02 15:26:13.200   283  1017 D audio_hw_hfp: audio_extn_hfp_set_parameters: enter
09-02 15:26:13.200   283  1017 V audio_hw_primary: adev_set_parameters: exit
,09-02 15:26:13.210  6403  6813 E HeadsetStateMachine: terminateScoUsingVirtualVoiceCall:No present call to terminate
,09-02 15:26:13.210  1296  1296 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,09-02 15:26:13.210  1019  1485 D ActivityManager: startService callerProcessName:com.android.settings, calleePkgName: com.android.settings
09-02 15:26:13.210  1019  1485 D ActivityManager: retrieveServiceLocked(): component = com.android.settings/com.android.settings.bluetooth.DockService; callingUser = 0; userId(target) = 0
,09-02 15:26:13.220  1019  1485 W ActivityManager: userId = 0, bbcId = -10000
,09-02 15:26:13.220  1019  1485 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-02 15:26:13.220  1019  1485 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.settings
,09-02 15:26:13.220  1296  1296 D DockEventReceiver: finishStartingService: stopping service
,09-02 15:26:13.220  1296  1296 D BluetoothNotiBroadcastReceiver: onReceive
,09-02 15:26:13.230  1182  1182 V BluetoothStatusReceiver: Received android.bluetooth.adapter.action.STATE_CHANGED
,09-02 15:26:13.230  1182  1182 D BluetoothStatusReceiver: AdapterStateChanged :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 12
,09-02 15:26:13.240  6403  6403 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@7062407
,09-02 15:26:13.240  6403  6403 D BtConfig.SecureMode: isSecureModeOn:false
,09-02 15:26:13.240  1019  3213 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,09-02 15:26:13.240  1019  3213 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.opp.BluetoothOppService; callingUser = 0; userId(target) = 0
,09-02 15:26:13.240  1019  3213 W ActivityManager: userId = 0, bbcId = -10000
,09-02 15:26:13.240  1019  3213 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-02 15:26:13.240  1019  3213 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-02 15:26:13.270  1883  1883 D EasyUnlockReceiver: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.easyunlock.authorization.BluetoothStateChangeReceiver (has extras) }.
,09-02 15:26:13.270  1019  1031 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
09-02 15:26:13.270  1019  1031 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.easyunlock.authorization.InitializerIntentService; callingUser = 0; userId(target) = 0
,09-02 15:26:13.270  1019  1032 D SecContentProvider: uri = 4 selection = isProfileAuthorizedBySecurityPolicy
,09-02 15:26:13.270  1019  1031 W ActivityManager: userId = 0, bbcId = -10000
09-02 15:26:13.270  1019  1031 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-02 15:26:13.270  1019  1031 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-02 15:26:13.270  1883  6866 D EasyUnlockInitService: Handling intent for initializer IntentService.
,09-02 15:26:13.280  1883  1883 D BtServices: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.proximity.BluetoothServicesAdapterStateChangeReceiver (has extras) }.
,09-02 15:26:13.280  1019  1485 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,09-02 15:26:13.280  6403  6867 D BluetoothSocket: bindListen(): myUserId = 0
09-02 15:26:13.280  6403  6867 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-02 15:26:13.280  1019  1485 W ActivityManager: userId = 0, bbcId = -10000
,09-02 15:26:13.280  1019  1485 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-02 15:26:13.280  1019  1485 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-02 15:26:13.290  6403  6867 D BluetoothSocket: bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[79]}
,09-02 15:26:13.290  6403  6867 D BluetoothSocket: bindListen(), new LocalSocket 
09-02 15:26:13.290  6403  6867 D BluetoothSocket: bindListen(), new LocalSocket.getInputStream() 
,09-02 15:26:13.290  6403  6867 D BluetoothSocket: bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@1f55573a
09-02 15:26:13.290  6403  6867 D BluetoothSocket: channel: 12
,09-02 15:26:13.290  6403  6867 I BtOppRfcommListener: Accept thread started.
,09-02 15:26:13.300  1019  2903 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,09-02 15:26:13.300  1019  2903 W ActivityManager: userId = 0, bbcId = -10000
,09-02 15:26:13.300  1019  2903 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-02 15:26:13.300  1019  2903 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-02 15:26:13.310  1883  6866 D EasyUnlockInitService: Not initializing EasyUnlock: remote_devices=0, bluetooth_on=true
,09-02 15:26:13.560  1019  1939 V SAMP_SPCM_test: CSC File load.. 
,09-02 15:26:13.570  1019  1939 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-application
,09-02 15:26:13.570  1019  1939 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-bluetooth
09-02 15:26:13.570  1019  1939 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-device-inventory
09-02 15:26:13.570  1019  1939 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-date-time
09-02 15:26:13.570  1019  1939 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-exchange-account
09-02 15:26:13.570  1019  1939 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-roaming
09-02 15:26:13.570  1019  1939 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-wifi
09-02 15:26:13.570  1019  1939 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-security
09-02 15:26:13.570  1019  1939 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-email-account
09-02 15:26:13.570  1019  1939 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-hardware-control
09-02 15:26:13.570  1019  1939 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-tethering
09-02 15:26:13.570  1019  1939 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-location
09-02 15:26:13.570  1019  1939 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-calling
09-02 15:26:13.570  1019  1939 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-email
09-02 15:26:13.570  1019  1939 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-vpn
09-02 15:26:13.570  1019  1939 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-apn-settings
09-02 15:26:13.570  1019  1939 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-browser-settings
09-02 15:26:13.570  1019  1939 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-phone-restriction
09-02 15:26:13.570  1019  1939 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-firewall
09-02 15:26:13.570  1019  1939 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-enterprise-vpn
09-02 15:26:13.570  1019  1939 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-data-time
,09-02 15:26:13.620  1019  1939 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-application
09-02 15:26:13.620  1019  1939 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-bluetooth
09-02 15:26:13.620  1019  1939 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-device-inventory
09-02 15:26:13.620  1019  1939 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-date-time
09-02 15:26:13.620  1019  1939 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-exchange-account
09-02 15:26:13.620  1019  1939 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-roaming
09-02 15:26:13.620  1019  1939 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-wifi
09-02 15:26:13.620  1019  1939 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-security
09-02 15:26:13.620  1019  1939 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-email-account
09-02 15:26:13.620  1019  1939 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-hardware-control
09-02 15:26:13.620  1019  1939 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-tethering
09-02 15:26:13.620  1019  1939 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-location
09-02 15:26:13.620  1019  1939 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-calling
09-02 15:26:13.620  1019  1939 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-email
09-02 15:26:13.620  1019  1939 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-vpn
09-02 15:26:13.620  1019  1939 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-apn-settings
09-02 15:26:13.620  1019  1939 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-browser-settings
09-02 15:26:13.620  1019  1939 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-phone-restriction
09-02 15:26:13.620  1019  1939 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-firewall
09-02 15:26:13.620  1019  1939 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-enterprise-vpn
09-02 15:26:13.620  1019  1939 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-data-time
,09-02 15:26:13.630  1019  1939 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: history-password
,09-02 15:26:13.630  1019  1939 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: allow-attachments
,09-02 15:26:13.630  1019  1939 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: limit-attachments
,09-02 15:26:13.630  1019  1939 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: allow-camera
,09-02 15:26:13.630  1019  1939 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: allow-htmlemail
,09-02 15:26:13.630  1019  1939 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: require-manualsyncroaming
,09-02 15:26:13.630  1019  1939 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: min-passwordcomplexchars
,09-02 15:26:13.630  1019  1939 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: max-calendarage
09-02 15:26:13.630  1019  1939 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: max-emailage
,09-02 15:26:13.640  1019  1939 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: max-emailbodytruncsize
09-02 15:26:13.640  1019  1939 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: max-htmlemailbodytruncsize
09-02 15:26:13.640  1019  1939 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: require-signedsmimemessages
09-02 15:26:13.640  1019  1939 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: require-encryptedsmimemessages
09-02 15:26:13.640  1019  1939 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: require-signedsmimealgorithm
09-02 15:26:13.640  1019  1939 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: require-encryptionsmimealgorithm
09-02 15:26:13.640  1019  1939 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: allow-smimeencryptionalgonegotiation
09-02 15:26:13.640  1019  1939 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: allow-smimesoftcerts
09-02 15:26:13.640  1019  1939 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: require-device-encryption
09-02 15:26:13.640  1019  1939 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-application
09-02 15:26:13.640  1019  1939 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-bluetooth
09-02 15:26:13.640  1019  1939 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-device-inventory
09-02 15:26:13.640  1019  1939 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-date-time
09-02 15:26:13.640  1019  1939 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-exchange-account
09-02 15:26:13.640  1019  1939 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-roaming
09-02 15:26:13.640  1019  1939 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-wifi
09-02 15:26:13.640  1019  1939 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-security
09-02 15:26:13.640  1019  1939 W DeviceAdminInfo: Unknown tag under uses-policies o,f ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-email-account
09-02 15:26:13.640  1019  1939 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-hardware-control
09-02 15:26:13.640  1019  1939 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-tethering
09-02 15:26:13.640  1019  1939 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-location
09-02 15:26:13.640  1019  1939 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-calling
09-02 15:26:13.640  1019  1939 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-email
09-02 15:26:13.640  1019  1939 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-vpn
09-02 15:26:13.640  1019  1939 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-apn-settings
09-02 15:26:13.640  1019  1939 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-browser-settings
09-02 15:26:13.640  1019  1939 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-phone-restriction
09-02 15:26:13.640  1019  1939 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-firewall
09-02 15:26:13.640  1019  1939 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-enterprise-vpn
09-02 15:26:13.640  1019  1939 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-data-time
,09-02 15:26:13.640  1019  1939 D ActivityManager: getContentProviderImpl callerProcessName:android, calleePkgName: com.samsung.android.sm,
,09-02 15:26:13.640  1019  1939 E ActivityManager: checkUser: useridlist=null, currentuser=0,
,09-02 15:26:13.640  1019  1939 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-02 15:26:13.640  1019  1939 E ActivityManager: checkUser: useridlist=null, currentuser=0,
09-02 15:26:13.640  1019  1939 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-02 15:26:13.660   338   338 I ServiceManager: Waiting for service AtCmdFwd...
,09-02 15:26:13.660  6868  6868 E Zygote  : MountEmulatedStorage()
,09-02 15:26:13.660  6868  6868 I libpersona: KNOX_SDCARD checking this for 1000
09-02 15:26:13.660  6868  6868 E Zygote  : v2
09-02 15:26:13.660  6868  6868 I libpersona: KNOX_SDCARD not a persona
,09-02 15:26:13.670  1019  1939 I ActivityManager: Start proc com.samsung.android.sm for content provider com.samsung.android.sm/.database.SmProvider: pid=6868 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
,09-02 15:26:13.670  6868  6868 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51
,09-02 15:26:13.670  6868  6868 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051
,09-02 15:26:13.670  6868  6868 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,09-02 15:26:13.700  6868  6868 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-02 15:26:13.700  6868  6868 D ActivityThread: Added TimaKeyStore provider
,09-02 15:26:13.720  6868  6868 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,09-02 15:26:13.760  1019  1939 E SAMP_SPCMtest: setPackageLockingTimeBySPCM() :72
,09-02 15:26:14.040   288   288 E SMD     : DCD OFF
,09-02 15:26:14.660   338   338 I ServiceManager: Waiting for service AtCmdFwd...
,09-02 15:26:15.120  6212  6266 D BluetoothAdapter: disable()
,09-02 15:26:15.120  1019  1031 D SettingsProvider: name = bluetooth_on
,09-02 15:26:15.130  6403  6804 D BluetoothAdapterState: CURRENT_STATE=ON, MSG = USER_TURN_OFF
,09-02 15:26:15.130  6403  6804 D BluetoothAdapterProperties: Setting state to 13
,09-02 15:26:15.140  6403  6804 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
09-02 15:26:15.140  6403  6804 D BluetoothAdapterService: Bluetooth PBAP supproted is true
09-02 15:26:15.140  6403  6804 D BluetoothAdapterService: updateAdapterState state is 13
,09-02 15:26:15.140  1019  3213 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,09-02 15:26:15.140  1019  3213 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pbap.BluetoothPbapService; callingUser = 0; userId(target) = 0
,09-02 15:26:15.140  1019  3213 W ActivityManager: userId = 0, bbcId = -10000
09-02 15:26:15.140  1019  3213 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,09-02 15:26:15.140  1019  3213 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-02 15:26:15.140  6403  6403 I BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED, state: 13
,09-02 15:26:15.140  6403  6403 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@8c5ffeb, channel: 19, state: LISTENING
,09-02 15:26:15.140  6403  6403 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@8c5ffeb, channel: 19, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@271a9c30, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@2b09c148mSocket: android.net.LocalSocket@11bb6be1 impl:android.net.LocalSocketImpl@38b1ad06 fd:FileDescriptor[75]
,09-02 15:26:15.140  6403  6403 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@11bb6be1 impl:android.net.LocalSocketImpl@38b1ad06 fd:FileDescriptor[75]
,09-02 15:26:15.150  1296  1296 D BluetoothPbap: Proxy object disconnected
09-02 15:26:15.150  1296  1296 D PbapServerProfile: Bluetooth service disconnected
09-02 15:26:15.150  6403  6804 D BluetoothAdapterService: Autoconnection is available 
09-02 15:26:15.150  6403  6804 D BluetoothAdapterService: updateAdapterState prevState = 12newState = 13
09-02 15:26:15.150  6403  6804 D BluetoothAdapterService: terminating service from this receiver
,09-02 15:26:15.150  1019  3105 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.samsung.ble.BleAutoConnectService; callingUser = 0; userId(target) = 0
,09-02 15:26:15.150  1019  3105 W ActivityManager: userId = 0, bbcId = -10000
,09-02 15:26:15.150  1019  3105 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-02 15:26:15.150  1019  3105 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-02 15:26:15.150  6403  6804 D BluetoothAdapterProperties: onBluetoothDisable(),
09-02 15:26:15.150  6403  6804 D BluetoothAdapterProperties: mDiscovering is false,
09-02 15:26:15.150  1019  1319 D SecContentProvider: uri = 3 selection = isDiscoverableEnabled
09-02 15:26:15.160  6403  6804 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=false, isTurningOff()=true
,09-02 15:26:15.160  1019  1019 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
09-02 15:26:15.160  1019  1019 I InputMethodManagerService: [BT Setting State] State =13
,09-02 15:26:15.170  1182  1182 D BluetoothTile:  onBluetoothStateChange:
,09-02 15:26:15.170  1182  1182 D BluetoothTile:  onBluetoothPairedDevicesChanged:
,09-02 15:26:15.170  1182  1182 D BluetoothTile: onReceive : android.bluetooth.adapter.action.STATE_CHANGED
09-02 15:26:15.170  1182  1182 D BluetoothTile:  getBluetoothState : 13
,09-02 15:26:15.170  1182  1704 D BluetoothTile:  handleUpdatestate:false name:null
,09-02 15:26:15.170  1182  1704 D BluetoothTile:  handleUpdatestate:false name:null
,09-02 15:26:15.170  1954  1954 I SamsungIME: STATE_CHANGED = 13, KEYBOARD_BT(0), mBTKeyboardCount =0
,09-02 15:26:15.180  1296  1296 V BluetoothEventManager: Received android.bluetooth.adapter.action.STATE_CHANGED
,09-02 15:26:15.180  1019  3109 D StatusBarManagerService: setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
,09-02 15:26:15.180  1019  1031 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=false
,09-02 15:26:15.180  6212  6212 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-02 15:26:15.180  1182  1182 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 )
09-02 15:26:15.180  6212  6212 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-02 15:26:15.180  6212  6212 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-02 15:26:15.180  6212  6212 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-02 15:26:15.180  6212  6212 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-02 15:26:15.180  6212  6212 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-02 15:26:15.180  6212  6212 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-02 15:26:15.180  6212  6212 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-02 15:26:15.180  6212  6212 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-02 15:26:15.190  6212  6212 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-02 15:26:15.190  6212  6212 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-02 15:26:15.190  6403  6807 D BluetoothUtils: getBtEnabledContainers(): btContainers = []
09-02 15:26:15.190  6403  6807 D BluetoothAdapterProperties: Scan Mode:20
,09-02 15:26:15.190  1182  1704 D STATUSBAR-QSTileView: onStateChanged: Bluetooth
,09-02 15:26:15.190  1019  3105 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,09-02 15:26:15.190  1019  3105 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.nearby.discovery.service.DiscoveryService; callingUser = 0; userId(target) = 0
,09-02 15:26:15.200  6212  6212 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-02 15:26:15.200  6212  6212 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-02 15:26:15.200  6212  6212 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-02 15:26:15.200  6212  6212 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-02 15:26:15.200  6212  6212 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-02 15:26:15.200  6212  6212 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-02 15:26:15.200  6212  6212 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-02 15:26:15.200  6212  6212 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-02 15:26:15.200  6212  6212 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-02 15:26:15.200  1019  3105 W ActivityManager: userId = 0, bbcId = -10000
09-02 15:26:15.200  1019  3105 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-02 15:26:15.200  1019  3105 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-02 15:26:15.200  6212  6212 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-02 15:26:15.200  6212  6212 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-02 15:26:15.200  1296  1296 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,09-02 15:26:15.210  6212  6212 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-02 15:26:15.210  1019  2903 D ActivityManager: startService callerProcessName:com.android.settings, calleePkgName: com.android.settings
09-02 15:26:15.210  1019  2903 D ActivityManager: retrieveServiceLocked(): component = com.android.settings/com.android.settings.bluetooth.DockService; callingUser = 0; userId(target) = 0
,09-02 15:26:15.210  1019  2903 W ActivityManager: userId = 0, bbcId = -10000
,09-02 15:26:15.210  6212  6212 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-02 15:26:15.210  1019  2903 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,09-02 15:26:15.210  1019  2903 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.settings
,09-02 15:26:15.210  6403  6804 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = BEGIN_DISABLE, isTurningOn=false, isTurningOff=true
,09-02 15:26:15.210  6403  6804 E bt-btif : btif_vhci_sock_cleanup, sock_thread_handle:6, rfc_init:1, vhci_init:1
,09-02 15:26:15.220  6403  6804 E bt-btif : btif_sock_cleanup, sock_thread_handle:6, rfc_init:1, vhci_init:0
,09-02 15:26:15.220  6403  6804 E bt-btif : cmd socket is not created
,09-02 15:26:15.220  6403  6824 E bt-btm  : btm_ble_start_auto_conn start : 0, 0
09-02 15:26:15.220  6403  6867 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
09-02 15:26:15.220  6403  6824 W bt-btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
09-02 15:26:15.220  6403  6824 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
09-02 15:26:15.220  6403  6824 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-02 15:26:15.220  6403  6824 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
,09-02 15:26:15.220  6403  6804 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,09-02 15:26:15.230  1296  1296 D DockEventReceiver: finishStartingService: stopping service
,09-02 15:26:15.230  6403  6403 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@9da9f4, channel: 5, state: LISTENING
09-02 15:26:15.230  6403  6403 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@9da9f4, channel: 5, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@161b062e, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@33a1e51dmSocket: android.net.LocalSocket@212b9392 impl:android.net.LocalSocketImpl@1b708163 fd:FileDescriptor[77]
09-02 15:26:15.230  6403  6403 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@212b9392 impl:android.net.LocalSocketImpl@1b708163 fd:FileDescriptor[77]
09-02 15:26:15.230  6403  6403 I BtOppRfcommListener: stopping Accept Thread
09-02 15:26:15.230  6403  6403 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@2be57160, channel: 12, state: LISTENING
09-02 15:26:15.230  6403  6403 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@2be57160, channel: 12, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@1f55573a, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@297cb619mSocket: android.net.LocalSocket@19eb56de impl:android.net.LocalSocketImpl@b5fd0bf fd:FileDescriptor[79]
09-02 15:26:15.230  6403  6403 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@19eb56de impl:android.net.LocalSocketImpl@b5fd0bf fd:FileDescriptor[79]
,09-02 15:26:15.230  6403  6867 I BtOppRfcommListener: BluetoothSocket listen thread finished
,09-02 15:26:15.230  1296  1296 D BluetoothNotiBroadcastReceiver: onReceive
,09-02 15:26:15.240  1182  1182 V BluetoothStatusReceiver: Received android.bluetooth.adapter.action.STATE_CHANGED
,09-02 15:26:15.240  1182  1182 D BluetoothStatusReceiver: AdapterStateChanged :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 13
,09-02 15:26:15.240  6403  6403 V BluetoothOppManager: cleanUp...
,09-02 15:26:15.260  1883  1883 D EasyUnlockReceiver: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.easyunlock.authorization.BluetoothStateChangeReceiver (has extras) }.
,09-02 15:26:15.270  1883  1883 D BtServices: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.proximity.BluetoothServicesAdapterStateChangeReceiver (has extras) }.
,09-02 15:26:15.420  6403  6824 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
,09-02 15:26:15.420  6403  6824 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
,09-02 15:26:15.420  6403  6824 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
09-02 15:26:15.420  6403  6824 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
,09-02 15:26:15.420  6403  6824 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-02 15:26:15.420  6403  6824 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
,09-02 15:26:15.420  6403  6824 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
09-02 15:26:15.420  6403  6824 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
,09-02 15:26:15.420  6403  6824 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
09-02 15:26:15.420  6403  6824 W bt-btif : ag scb idx 1 not allocated
09-02 15:26:15.420  6403  6824 W bt-btif : ag scb idx 2 not allocated
,09-02 15:26:15.420  6403  6824 E bt-btif : BTA AG is already disabled, ignoring ...
09-02 15:26:15.420  6403  6848 I bt_userial_mct: exiting userial_read_thread,
09-02 15:26:15.420  6403  6848 D bt_userial_mct: Leaving userial_evt_read_thread()
,09-02 15:26:15.430  6403  6807 D bt_userial_mct: userial_close_reader Joined userial reader thread: 0
,09-02 15:26:15.430  6403  6826 I bt_vendor: hw_epilog_process
,09-02 15:26:15.430  6403  6807 D bt_userial_mct: userial_close
,09-02 15:26:15.430  6403  6807 I bt_vendor: bt-vendor : BT_VND_OP_USERIAL_CLOSE btSocType: 0
,09-02 15:26:15.660   338   338 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 3
,09-02 15:26:16.310  6403  6807 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: Off
,09-02 15:26:16.310  6403  6807 I bt_vendor: bluetooth satus is on
09-02 15:26:16.310  6403  6807 I bt_vendor: bt-vendor : resetting BT status
,09-02 15:26:16.310  6403  6807 I bt_vendor: Starting hciattach daemon
09-02 15:26:16.310  6403  6807 I bt_vendor: try to set false
,09-02 15:26:16.310  6403  6807 I bt_vendor: Starting hciattach daemon
,09-02 15:26:16.310  6403  6807 I bt_vendor: try to set false
,09-02 15:26:16.310  6403  6807 I bt_vendor: cleanup
,09-02 15:26:16.310  6403  6824 I GKI_LINUX: gki_task task_id=0 [BTU] terminating
,09-02 15:26:16.310  6403  6807 I GKI_LINUX: GKI_exit_task 0 done
,09-02 15:26:16.310  6403  6807 I GKI_LINUX: GKI_shutdown(): task [BTU] terminated
,09-02 15:26:16.320  6403  6804 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = DISABLED, isTurningOn=false, isTurningOff=true
,09-02 15:26:16.320  6403  6804 D BtConfig.SecureMode: isSecureModeOn:false
,09-02 15:26:16.320  6403  6804 D BluetoothAdapterService: mProfilesStarted : true supportedProfileServices.length : 12
,09-02 15:26:16.320  6403  6804 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.gatt.GattService
09-02 15:26:16.320  6403  6804 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.gatt.GattService
,09-02 15:26:16.320  6403  6804 W BluetoothAdapterService: Not skipping com.android.bluetooth.gatt.GattService
,09-02 15:26:16.320  1019  1484 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,09-02 15:26:16.320  1019  1484 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.gatt.GattService; callingUser = 0; userId(target) = 0
,09-02 15:26:16.320  1019  1484 W ActivityManager: userId = 0, bbcId = -10000
,09-02 15:26:16.320  1019  1484 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-02 15:26:16.320  1019  1484 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-02 15:26:16.320  6403  6403 D BtGatt.DebugUtils: handleDebugAction() action=null
09-02 15:26:16.320  6403  6804 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hfp.HeadsetService
09-02 15:26:16.320  6403  6804 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
09-02 15:26:16.320  6403  6804 W BluetoothAdapterService: Not skipping com.android.bluetooth.hfp.HeadsetService
,09-02 15:26:16.320  1019  2905 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
09-02 15:26:16.320  1019  2905 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = 0
,09-02 15:26:16.320  6403  6403 D BtGatt.GattService: Received stop request...Stopping profile...
09-02 15:26:16.320  6403  6403 D BtGatt.GattService: stop()
09-02 15:26:16.320  6403  6403 D BtGatt.AdvertiseManager: advertise clients cleared
,09-02 15:26:16.330  1019  2905 W ActivityManager: userId = 0, bbcId = -10000
,09-02 15:26:16.330  1019  2905 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,09-02 15:26:16.330  1019  2905 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-02 15:26:16.330  6403  6403 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@7062407
,09-02 15:26:16.330  6403  6804 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.a2dp.A2dpService
,09-02 15:26:16.330  6403  6804 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
,09-02 15:26:16.330  6403  6403 D HeadsetService: Received stop request...Stopping profile...
,09-02 15:26:16.330  6403  6403 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@7062407
09-02 15:26:16.330  6403  6804 W BluetoothAdapterService: Not skipping com.android.bluetooth.a2dp.A2dpService
,09-02 15:26:16.330  1019  1019 D AudioService: onServiceDisconnected: Bluetooth profile: 1
,09-02 15:26:16.330  1019  2952 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,09-02 15:26:16.340  1019  2952 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
09-02 15:26:16.340  1296  1296 D HeadsetProfile: Bluetooth service disconnected
,09-02 15:26:16.340  1019  2952 W ActivityManager: userId = 0, bbcId = -10000
,09-02 15:26:16.340  1019  2952 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-02 15:26:16.340  1019  2952 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-02 15:26:16.340  6403  6804 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hid.HidService
09-02 15:26:16.340  6403  6804 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
09-02 15:26:16.340  6403  6804 W BluetoothAdapterService: Not skipping com.android.bluetooth.hid.HidService
,09-02 15:26:16.340  1019  1485 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,09-02 15:26:16.340  1019  1485 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hid.HidService; callingUser = 0; userId(target) = 0
,09-02 15:26:16.340  1019  1485 W ActivityManager: userId = 0, bbcId = -10000
,09-02 15:26:16.340  1019  1485 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-02 15:26:16.340  1019  1485 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-02 15:26:16.340  6403  6804 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hdp.HealthService
,09-02 15:26:16.340  6403  6804 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
,09-02 15:26:16.340  6403  6804 W BluetoothAdapterService: Not skipping com.android.bluetooth.hdp.HealthService
,09-02 15:26:16.340  1019  1031 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,09-02 15:26:16.340  1019  1031 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hdp.HealthService; callingUser = 0; userId(target) = 0
,09-02 15:26:16.350  1019  1031 W ActivityManager: userId = 0, bbcId = -10000
,09-02 15:26:16.350  1019  1031 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-02 15:26:16.350  1019  1031 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-02 15:26:16.350  6403  6804 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.pan.PanService
09-02 15:26:16.350  6403  6804 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.pan.PanService
09-02 15:26:16.350  6403  6804 W BluetoothAdapterService: Not skipping com.android.bluetooth.pan.PanService
,09-02 15:26:16.350  1019  2905 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
09-02 15:26:16.350  1019  2905 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pan.PanService; callingUser = 0; userId(target) = 0
,09-02 15:26:16.350  1019  2905 W ActivityManager: userId = 0, bbcId = -10000
,09-02 15:26:16.350  1019  2905 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-02 15:26:16.350  1019  2905 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-02 15:26:16.350  6403  6804 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.map.BluetoothMapService
,09-02 15:26:16.350  6403  6804 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
,09-02 15:26:16.350  6403  6804 W BluetoothAdapterService: Not skipping com.android.bluetooth.map.BluetoothMapService
,09-02 15:26:16.350  1019  3105 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,09-02 15:26:16.350  1019  3105 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.map.BluetoothMapService; callingUser = 0; userId(target) = 0
,09-02 15:26:16.350  1019  3105 W ActivityManager: userId = 0, bbcId = -10000
,09-02 15:26:16.350  1019  3105 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-02 15:26:16.350  1019  3105 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-02 15:26:16.360  6403  6804 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.broadcom.bt.service.sap.SapService
09-02 15:26:16.360  6403  6804 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
09-02 15:26:16.360  6403  6804 W BluetoothAdapterService: Not skipping com.broadcom.bt.service.sap.SapService
,09-02 15:26:16.360  1019  1082 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,09-02 15:26:16.360  1019  1082 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.broadcom.bt.service.sap.SapService; callingUser = 0; userId(target) = 0
,09-02 15:26:16.360  1019  1082 W ActivityManager: userId = 0, bbcId = -10000
,09-02 15:26:16.360  1019  1082 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-02 15:26:16.360  1019  1082 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-02 15:26:16.360  6403  6804 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hfpclient.HeadsetClientService
,09-02 15:26:16.360  6403  6804 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfpclient.HeadsetClientService
,09-02 15:26:16.360  6403  6804 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.hfpclient.HeadsetClientService
09-02 15:26:16.360  6403  6804 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.a2dp.A2dpSinkService
09-02 15:26:16.360  6403  6804 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpSinkService
,09-02 15:26:16.360  6403  6804 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.a2dp.A2dpSinkService
09-02 15:26:16.360  6403  6804 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.sapclient.SapClientService
,09-02 15:26:16.360  6403  6804 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.sapclient.SapClientService
09-02 15:26:16.360  6403  6804 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.sapclient.SapClientService
,09-02 15:26:16.360  6403  6804 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hid.HidDevService
09-02 15:26:16.360  6403  6804 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidDevService
,09-02 15:26:16.360  6403  6804 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.hid.HidDevService
,09-02 15:26:16.360  6403  6804 D BluetoothAdapterState: Stopping profile services that were post enabled
09-02 15:26:16.360  6403  6403 E BluetoothAdapterService(117842951): processProfileServiceStateChanged() serviceName=com.android.bluetooth.gatt.GattService, state=10, doUpdate=false
,09-02 15:26:16.370  6403  6403 E BluetoothAdapterService(117842951): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hfp.HeadsetService, state=10, doUpdate=true
09-02 15:26:16.370  6403  6403 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
09-02 15:26:16.370  6403  6403 D BluetoothAdapterService: Profile still running: com.android.bluetooth.hid.HidService
,09-02 15:26:16.370  6403  6403 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
,09-02 15:26:16.370  6403  6403 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
,09-02 15:26:16.370  6403  6403 D A2dpService: Received stop request...Stopping profile...
,09-02 15:26:16.370  6403  6818 D A2dpStateMachine: Exit Disconnected: -1
,09-02 15:26:16.370  6403  6403 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@7062407
,09-02 15:26:16.370  1019  1019 D BluetoothA2dp: Proxy object disconnected,
09-02 15:26:16.370  1019  1019 D AudioService: onServiceDisconnected: Bluetooth profile: 2
09-02 15:26:16.370  2850  2850 D BluetoothA2dp: Proxy object disconnected
09-02 15:26:16.370  6403  6403 D HidService: Received stop request...Stopping profile...
09-02 15:26:16.380  6403  6403 D HidService: Stopping Bluetooth HidService
09-02 15:26:16.380  6403  6403 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
09-02 15:26:16.380  6403  6403 W bt-btif : cleanup: HH disabling or disabled already, status = 0
09-02 15:26:16.380  6403  6403 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
09-02 15:26:16.380  6403  6403 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@7062407
,09-02 15:26:16.380  6403  6403 D HealthService: Received stop request...Stopping profile...
,09-02 15:26:16.380  6403  6403 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@7062407
09-02 15:26:16.380  1296  1296 D BluetoothA2dp: Proxy object disconnected
,09-02 15:26:16.380  1296  1296 D A2dpProfile: Bluetooth service disconnected
09-02 15:26:16.380  1296  1296 D BluetoothInputDevice: Proxy object disconnected
09-02 15:26:16.380  1296  1296 D HidProfile: Bluetooth service disconnected
,09-02 15:26:16.380  6403  6403 D PanService: Received stop request...Stopping profile...
,09-02 15:26:16.380  6403  6403 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@7062407
,09-02 15:26:16.380  6403  6403 D BluetoothMapService: Received stop request...Stopping profile...
,09-02 15:26:16.390  1019  1019 D BluetoothPan: BluetoothPAN Proxy object disconnected,
09-02 15:26:16.390  1296  1296 D BluetoothPan: BluetoothPAN Proxy object disconnected
09-02 15:26:16.390  1296  1296 D PanProfile: Bluetooth service disconnected
,09-02 15:26:16.390  6403  6403 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@7062407
,09-02 15:26:16.390  6403  6403 D SapService: Received stop request...Stopping profile...
,09-02 15:26:16.390  6403  6403 D SapService: Stopping Bluetooth SapService
,09-02 15:26:16.390  6403  6403 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@7062407
09-02 15:26:16.390  1296  1296 D BluetoothMap: Proxy object disconnected
,09-02 15:26:16.390  1296  1296 D MapProfile: Bluetooth service disconnected
,09-02 15:26:16.390  6403  6403 E BluetoothAdapterService(117842951): processProfileServiceStateChanged() serviceName=com.android.bluetooth.a2dp.A2dpService, state=10, doUpdate=true
,09-02 15:26:16.390  6403  6403 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
,09-02 15:26:16.390  6403  6403 D BluetoothAdapterService: Profile still running: com.android.bluetooth.hid.HidService
,09-02 15:26:16.390  6403  6403 D BluetoothA2dp: Proxy object disconnected
09-02 15:26:16.390  6403  6403 D BluetoothAdapterService: Bluetooth A2dp source service disconnected
09-02 15:26:16.390  1296  1296 D Bluetoothsap: BluetoothSAP Proxy object disconnected
09-02 15:26:16.390  1296  1296 D SapProfile: Bluetooth service disconnected
09-02 15:26:16.400  6403  6819 I GKI_LINUX: gki_task task_id=2 [A2DP-MEDIA] terminating
,09-02 15:26:16.400  6403  6403 I GKI_LINUX: GKI_exit_task 2 done
09-02 15:26:16.400  6403  6403 I GKI_LINUX: GKI_shutdown(): task [A2DP-MEDIA] terminated
,09-02 15:26:16.400  6403  6403 E BluetoothAdapterService(117842951): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hid.HidService, state=10, doUpdate=true
,09-02 15:26:16.400  6403  6403 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
,09-02 15:26:16.400  6403  6403 D BluetoothAdapterService: Profile still running: com.android.bluetooth.map.BluetoothMapService
,09-02 15:26:16.400  6403  6403 E BluetoothAdapterService(117842951): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hdp.HealthService, state=10, doUpdate=true
,09-02 15:26:16.400  6403  6403 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
09-02 15:26:16.400  6403  6403 D BluetoothAdapterService: Profile still running: com.android.bluetooth.map.BluetoothMapService
,09-02 15:26:16.400  6403  6403 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
,09-02 15:26:16.400  6403  6403 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
09-02 15:26:16.400  6403  6403 E BluetoothAdapterService(117842951): processProfileServiceStateChanged() serviceName=com.android.bluetooth.pan.PanService, state=10, doUpdate=true
09-02 15:26:16.400  6403  6403 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
09-02 15:26:16.400  6403  6403 D BluetoothAdapterService: Profile still running: com.android.bluetooth.map.BluetoothMapService
09-02 15:26:16.400  6403  6403 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
09-02 15:26:16.400  6403  6403 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
,09-02 15:26:16.400  6403  6403 E BluetoothAdapterService(117842951): processProfileServiceStateChanged() serviceName=com.android.bluetooth.map.BluetoothMapService, state=10, doUpdate=true
09-02 15:26:16.400  6403  6403 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
09-02 15:26:16.400  6403  6403 D BluetoothAdapterService: Profile still running: com.broadcom.bt.service.sap.SapService
,09-02 15:26:16.400  6403  6403 E BluetoothAdapterService(117842951): processProfileServiceStateChanged() serviceName=com.broadcom.bt.service.sap.SapService, state=10, doUpdate=true
09-02 15:26:16.400  6403  6403 W BluetoothSAPServiceJni: ## WARNING : cleanupNative(L251): Cleaning up Bluetooth SAP Interface...##
09-02 15:26:16.400  6403  6403 W BluetoothSAPServiceJni: ## WARNING : cleanupNative(L257): Cleaning up Bluetooth SAP callback object##
,09-02 15:26:16.410  6403  6804 D BluetoothAdapterState: CURRENT_STATE=PENDING,MSG = STOPPED, isTurningOn=false, isTurningOff=true
,09-02 15:26:16.410  6403  6804 D BluetoothAdapterProperties: Setting state to 10
09-02 15:26:16.410  6403  6804 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 10
09-02 15:26:16.410  6403  6804 D BluetoothAdapterService: Bluetooth PBAP supproted is true
09-02 15:26:16.410  6403  6804 D BluetoothAdapterService: updateAdapterState state is 10
,09-02 15:26:16.410  6403  6804 D BluetoothAdapterService: Autoconnection is available 
09-02 15:26:16.410  6403  6804 D BluetoothAdapterService: updateAdapterState prevState = 13newState = 10
09-02 15:26:16.410  6403  6804 I BluetoothAdapterState: Entering OffState
,09-02 15:26:16.410  1296  6395 D Bluetoothsap: onBluetoothStateChange: up=false
09-02 15:26:16.410  1296  6395 D Bluetoothsap: Unbinding service...
,09-02 15:26:16.410  1433  6854 D BluetoothAdapter: onBluetoothStateChange: up=false
,09-02 15:26:16.410  1433  6854 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,09-02 15:26:16.410  6403  6853 D BluetoothAdapter: onBluetoothStateChange: up=false
09-02 15:26:16.410  6403  6853 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,09-02 15:26:16.410  1296  1309 D BluetoothAdapter: onBluetoothStateChange: up=false
,09-02 15:26:16.410  1296  1309 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
09-02 15:26:16.410  1444  1456 D BluetoothAdapter: onBluetoothStateChange: up=false
09-02 15:26:16.410  1444  1456 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,09-02 15:26:16.410  6212  6221 D BluetoothAdapter: onBluetoothStateChange: up=false
,09-02 15:26:16.410  6212  6221 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
09-02 15:26:16.410  6212  6221 D BluetoothLeAdvertiser: stop All Advertising :: standalone boolean value is = false
,09-02 15:26:16.410  6212  6221 D BluetoothLeAdvertiser: Exit stop advertising
09-02 15:26:16.410  6212  6221 D BluetoothLeScanner: stopAllScan standalone boolean is value is = false
09-02 15:26:16.410  6212  6221 D BluetoothLeScanner: Exiting stopAllScan
,09-02 15:26:16.410  1182  2702 D BluetoothAdapter: onBluetoothStateChange: up=false
,09-02 15:26:16.410  1182  2702 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,09-02 15:26:16.420  1883  1903 D BluetoothAdapter: onBluetoothStateChange: up=false
09-02 15:26:16.420  1883  1903 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,09-02 15:26:16.420  6368  6383 D BluetoothAdapter: onBluetoothStateChange: up=false
,09-02 15:26:16.420  6368  6383 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,09-02 15:26:16.420  1296  6395 D BluetoothPbap: onBluetoothStateChange: up=false
,09-02 15:26:16.420  1019  1050 D BluetoothAdapter: onBluetoothStateChange: up=false
,09-02 15:26:16.420  1019  1050 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,09-02 15:26:16.420  2850  2858 D BluetoothA2dp: onBluetoothStateChange: up=false
,09-02 15:26:16.420  1296  1309 D BluetoothInputDevice: onBluetoothStateChange: up=false
,09-02 15:26:16.420  6403  6808 D BluetoothA2dp: onBluetoothStateChange: up=false
,09-02 15:26:16.420  1460  2431 D BluetoothAdapter: onBluetoothStateChange: up=false
,09-02 15:26:16.420  1460  2431 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,09-02 15:26:16.420  1019  1050 D BluetoothA2dp: onBluetoothStateChange: up=false
,09-02 15:26:16.430  2850  2863 D BluetoothAdapter: onBluetoothStateChange: up=false
,09-02 15:26:16.430  2850  2863 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
09-02 15:26:16.430  1296  6395 D BluetoothA2dp: onBluetoothStateChange: up=false
,09-02 15:26:16.430  1296  1309 D BluetoothMap: onBluetoothStateChange: up=false
,09-02 15:26:16.430  1019  1050 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 11 receivers.
,09-02 15:26:16.430  1019  1050 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 0 receivers.
,09-02 15:26:16.440  1019  1019 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
,09-02 15:26:16.440  1019  1019 I InputMethodManagerService: [BT Setting State] State =10
09-02 15:26:16.440  1019  1019 I InputMethodManagerService: [BT Setting on -> off] mBTKeyboardCount =0, KEYBOARD_BT(0)
,09-02 15:26:16.440  1182  1182 D BluetoothAdapter: 611874534: getState() :  mService = null. Returning STATE_OFF
,09-02 15:26:16.440  1182  1182 D BluetoothTile:  onBluetoothPairedDevicesChanged:
,09-02 15:26:16.440  1182  1704 D BluetoothAdapter: 611874534: getState() :  mService = null. Returning STATE_OFF
,09-02 15:26:16.440  1182  1182 D BluetoothTile: onReceive : android.bluetooth.adapter.action.STATE_CHANGED
,09-02 15:26:16.440  1182  1182 D BluetoothTile:  getBluetoothState : 10
09-02 15:26:16.440  1182  1704 D BluetoothAdapter: 611874534: getState() :  mService = null. Returning STATE_OFF
,09-02 15:26:16.440  1182  1182 D BluetoothAdapter: 611874534: getState() :  mService = null. Returning STATE_OFF
09-02 15:26:16.440  1182  1182 D BluetoothAdapter: 611874534: getState() :  mService = null. Returning STATE_OFF
,09-02 15:26:16.440  1019  3105 D StatusBarManagerService: setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
,09-02 15:26:16.450  1296  1296 V BluetoothEventManager: Received android.bluetooth.adapter.action.STATE_CHANGED
,09-02 15:26:16.450  1883  2125 D BluetoothAdapter: 1052030209: getState() :  mService = null. Returning STATE_OFF
09-02 15:26:16.450  1883  2125 D BluetoothAdapter: 1052030209: getState() :  mService = null. Returning STATE_OFF
,09-02 15:26:16.450  1954  1954 I SamsungIME: STATE_CHANGED = 10, KEYBOARD_BT(0), mBTKeyboardCount =0
09-02 15:26:16.450  1019  2905 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=false
,09-02 15:26:16.450  6212  6212 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-02 15:26:16.450  1182  1182 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 )
,09-02 15:26:16.450  6212  6212 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-02 15:26:16.450  1019  1031 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
09-02 15:26:16.450  1019  1031 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.nearby.discovery.service.DiscoveryService; callingUser = 0; userId(target) = 0
,09-02 15:26:16.450  1019  1031 W ActivityManager: userId = 0, bbcId = -10000
09-02 15:26:16.450  1019  1031 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-02 15:26:16.450  1019  1031 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-02 15:26:16.450  6403  6807 I GKI_LINUX: gki_task task_id=1 [BTIF] terminating
,09-02 15:26:16.450  6403  6403 I GKI_LINUX: GKI_exit_task 1 done
09-02 15:26:16.450  6403  6403 I GKI_LINUX: GKI_shutdown(): task [BTIF] terminated
09-02 15:26:16.450  1296  1296 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,09-02 15:26:16.450  1019  1319 D ActivityManager: startService callerProcessName:com.android.settings, calleePkgName: com.android.settings
09-02 15:26:16.450  1019  1319 D ActivityManager: retrieveServiceLocked(): component = com.android.settings/com.android.settings.bluetooth.DockService; callingUser = 0; userId(target) = 0
,09-02 15:26:16.460  6403  6403 I BluetoothServiceJni: cleanupNative: return from cleanup
09-02 15:26:16.460  1019  1319 W ActivityManager: userId = 0, bbcId = -10000
09-02 15:26:16.460  1019  1319 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-02 15:26:16.460  1019  1319 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.settings
,09-02 15:26:16.460  6403  6403 I art     : System.exit called, status: 0
09-02 15:26:16.460  6403  6403 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,09-02 15:26:16.470  1296  1296 D DockEventReceiver: finishStartingService: stopping service
,09-02 15:26:16.470  1296  1296 D BluetoothNotiBroadcastReceiver: onReceive
,09-02 15:26:16.470  1182  1182 V BluetoothStatusReceiver: Received android.bluetooth.adapter.action.STATE_CHANGED
09-02 15:26:16.470  1182  1182 D BluetoothStatusReceiver: AdapterStateChanged :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 10
,09-02 15:26:16.620  1019  3213 I ActivityManager: Process com.android.bluetooth (pid 6403)(adj 0) has died(60,1084)
,09-02 15:26:16.630  1883  1883 D EasyUnlockReceiver: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.easyunlock.authorization.BluetoothStateChangeReceiver (has extras) }.
,09-02 15:26:16.630  1019  1032 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,09-02 15:26:16.630  1019  1032 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.easyunlock.authorization.InitializerIntentService; callingUser = 0; userId(target) = 0
,09-02 15:26:16.640  1019  1032 W ActivityManager: userId = 0, bbcId = -10000
,09-02 15:26:16.640  1019  1032 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,09-02 15:26:16.640  1019  1032 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-02 15:26:16.650  1883  1883 D BtServices: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.proximity.BluetoothServicesAdapterStateChangeReceiver (has extras) }.
,09-02 15:26:16.650  1883  6898 D EasyUnlockInitService: Handling intent for initializer IntentService.
,09-02 15:26:16.660  1019  1319 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,09-02 15:26:16.660  1019  1319 W ActivityManager: userId = 0, bbcId = -10000
,09-02 15:26:16.660  1019  1319 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,09-02 15:26:16.660  1019  1319 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-02 15:26:16.670  1883  6898 D EasyUnlockInitService: Not initializing EasyUnlock: remote_devices=0, bluetooth_on=false
,09-02 15:26:17.040   288   288 E SMD     : DCD OFF,
,09-02 15:26:17.470  1019  3105 D BatteryService: !@BatteryListener : batteryPropertiesChanged!,
09-02 15:26:17.470  1019  3105 D BatteryService: level:93, scale:100, status:2, health:2, present:true, voltage: 4231, temperature: 285, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
09-02 15:26:17.470  1019  3105 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
09-02 15:26:17.470  1019  3105 D BatteryService: stay LED for charging
,09-02 15:26:17.470  1019  1019 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,09-02 15:26:17.470  1019  1053 D PowerManagerService: [PSM] lowPowerModeEnabled: false (mLowPowerModeSetting: false, mAutoLowPowerModeConfigured: false, mBatteryLevel: 93, mLowBatteryTriggerLevel: 0)
,09-02 15:26:17.480  1019  1019 I MotionRecognitionService: Plugged
09-02 15:26:17.480  1019  1019 I MotionRecognitionService: mGripSensorEnabled= false
,09-02 15:26:17.480  1182  1182 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,09-02 15:26:17.480  1182  1182 D KeyguardUpdateMonitor: handleBatteryUpdate
,09-02 15:26:17.480  1182  1182 D SecKeyguardStatusUtils: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,09-02 15:26:17.490  1422  1422 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
09-02 15:26:17.490  1422  1422 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 93
,09-02 15:26:17.510  1182  1182 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:93 status:2 health:2
,09-02 15:26:17.510  1182  1182 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:93 status:2 health:2
09-02 15:26:17.510  1182  1182 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:93 status:2 health:2
,09-02 15:26:18.130  6212  6266 D io.jxcore.node.ConnectivityMonitor: stop,
09-02 15:26:18.130  6212  6266 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-02 15:26:20.030  1019  2713 D SSRM:n  : SIOP:: AP = 330
,09-02 15:26:20.040   288   288 E SMD     : DCD OFF
,09-02 15:26:21.130  6212  6266 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded,
09-02 15:26:21.130  6212  6266 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@b94932c added. We now have 6 listener(s)
09-02 15:26:21.130  6212  6266 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-02 15:26:21.140  6212  6266 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,09-02 15:26:21.140  6212  6266 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@332241f5 added. We now have 7 listener(s)
09-02 15:26:21.140  6212  6266 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-02 15:26:21.140  6212  6266 I System.out: IsBluetoothEnabled
09-02 15:26:21.140  6212  6266 D BluetoothAdapter: disable()
09-02 15:26:21.140  1019  2903 E BluetoothManagerService: Bluetooth is already disabled. DO NOT disable again.
09-02 15:26:21.140  6212  6266 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-02 15:26:21.140  1019  2905 W ActivityManager: Permission Denial: getCurrentUser() from pid=6212, uid=10155 requires android.permission.INTERACT_ACROSS_USERS
09-02 15:26:21.140  6212  6266 D BluetoothAdapter: enable()
,09-02 15:26:21.150  1019  2905 W BluetoothManagerService: Failed getting userId using ActivityManagerNative
09-02 15:26:21.150  1019  2905 W BluetoothManagerService: java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=6212, uid=10155 requires android.permission.INTERACT_ACROSS_USERS
09-02 15:26:21.150  1019  2905 W BluetoothManagerService: 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:23916)
09-02 15:26:21.150  1019  2905 W BluetoothManagerService: 	at com.android.server.BluetoothManagerService.CheckItPolicy(BluetoothManagerService.java:2270)
09-02 15:26:21.150  1019  2905 W BluetoothManagerService: 	at com.android.server.BluetoothManagerService.enable(BluetoothManagerService.java:702)
09-02 15:26:21.150  1019  2905 W BluetoothManagerService: 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:116)
09-02 15:26:21.150  1019  2905 W BluetoothManagerService: 	at android.os.Binder.execTransact(Binder.java:446)
09-02 15:26:21.150  1019  2905 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
09-02 15:26:21.150  1019  2905 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
,09-02 15:26:21.150  1019  2905 D SettingsProvider: name = bluetooth_on
,09-02 15:26:21.160  1019  1050 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
09-02 15:26:21.160  1019  1050 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
,09-02 15:26:21.160  1019  1050 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetooth
09-02 15:26:21.160  1019  1050 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.btservice.AdapterService; callingUser = 0; userId(target) = -2
,09-02 15:26:21.160  1019  1050 E ActivityManager: checkUser: useridlist=null, currentuser=0,
09-02 15:26:21.160  1019  1050 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-02 15:26:21.160  1019  1050 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-02 15:26:21.160  1019  1050 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-02 15:26:21.170  6906  6906 E Zygote  : MountEmulatedStorage(),
09-02 15:26:21.170  6906  6906 I libpersona: KNOX_SDCARD checking this for 1002
09-02 15:26:21.170  6906  6906 E Zygote  : v2
09-02 15:26:21.170  6906  6906 I libpersona: KNOX_SDCARD not a persona
09-02 15:26:21.170  6906  6906 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51
,09-02 15:26:21.180  6906  6906 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051
,09-02 15:26:21.180  1019  1050 I ActivityManager: Start proc com.android.bluetooth for service com.android.bluetooth/.btservice.AdapterService: pid=6906 uid=1002 gids={41002, 9997, 3003, 3002, 3001, 1028, 1015, 3005, 1016, 3008} abi=armeabi-v7a
09-02 15:26:21.180  6906  6906 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,09-02 15:26:21.200  6906  6906 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-02 15:26:21.200  6906  6906 D ActivityThread: Added TimaKeyStore provider,
09-02 15:26:21.210   316   316 I art     : Explicit concurrent mark sweep GC freed 8714(371KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 764us total 24.389ms
,09-02 15:26:21.220  6906  6906 W ResourcesManager: Asset path '/system/framework/javax.obex.jar' does not exist or contains no resources.
,09-02 15:26:21.220  6906  6906 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,09-02 15:26:21.230   316   316 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 806us total 20.299ms,
,09-02 15:26:21.250   316   316 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 708us total 20.054ms,
,09-02 15:26:21.260  6906  6906 I BluetoothA2dpSinkServiceJni: register_com_android_bluetooth_a2dp_sink
,09-02 15:26:21.300  6906  6906 D BtSettings.ProfileConfig: Adding GattService
,09-02 15:26:21.300  6906  6906 D BtSettings.ProfileConfig: Adding HeadsetService
,09-02 15:26:21.300  6906  6906 D BtSettings.ProfileConfig: Adding A2dpService
09-02 15:26:21.300  6906  6906 D BtSettings.ProfileConfig: Adding HidService
,09-02 15:26:21.300  6906  6906 D BtSettings.ProfileConfig: Adding HealthService
09-02 15:26:21.300  6906  6906 D BtSettings.ProfileConfig: Adding PanService
,09-02 15:26:21.300  6906  6906 D BtSettings.ProfileConfig: Adding BluetoothMapService
09-02 15:26:21.300  6906  6906 D BtSettings.ProfileConfig: Adding SapService
,09-02 15:26:21.300  6906  6906 D BtSettings.ProfileConfig: Adding HeadsetClientService
09-02 15:26:21.300  6906  6906 D BtSettings.ProfileConfig: Adding A2dpSinkService
09-02 15:26:21.300  6906  6906 D BtSettings.ProfileConfig: Adding SapClientService
,09-02 15:26:21.300  6906  6906 D BtSettings.ProfileConfig: Adding HidDevService
09-02 15:26:21.300  6906  6906 I BtSettings.ProfileConfig: *********Initializing Bluetooth Profile Settings*******
,09-02 15:26:21.300  1019  3105 D SettingsProvider: name = bt_svcst_com.android.bluetooth.gatt.GattService
,09-02 15:26:21.310  1019  3105 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
09-02 15:26:21.310  1019  3105 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
09-02 15:26:21.310  1019  3105 D SettingsProvider: selectionArgs: false
09-02 15:26:21.310  1019  3105 D SettingsProvider: selectionArgs: 1002
09-02 15:26:21.310  1019  3105 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
,09-02 15:26:21.310  1019  3105 D SettingsProvider: ret = -1
,09-02 15:26:21.310  1019  1082 D SettingsProvider: name = bt_svcst_com.android.bluetooth.hfp.HeadsetService
09-02 15:26:21.310  1019  1082 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
09-02 15:26:21.310  1019  1082 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
,09-02 15:26:21.310  1019  1082 D SettingsProvider: selectionArgs: false
09-02 15:26:21.310  1019  1082 D SettingsProvider: selectionArgs: 1002
09-02 15:26:21.310  1019  1082 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
09-02 15:26:21.310  1019  1082 D SettingsProvider: ret = -1,
09-02 15:26:21.310  1019  1322 D SettingsProvider: name = bt_svcst_com.android.bluetooth.a2dp.A2dpService
09-02 15:26:21.310  1019  1322 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
09-02 15:26:21.310  1019  1322 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
,09-02 15:26:21.310  1019  1322 D SettingsProvider: selectionArgs: false
09-02 15:26:21.310  1019  1322 D SettingsProvider: selectionArgs: 1002
09-02 15:26:21.310  1019  1322 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
,09-02 15:26:21.310  1019  1322 D SettingsProvider: ret = -1
09-02 15:26:21.310  1019  1223 D SettingsProvider: name = bt_svcst_com.android.bluetooth.hid.HidService,
09-02 15:26:21.310  1019  1223 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
09-02 15:26:21.310  1019  1223 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
09-02 15:26:21.310  1019  1223 D SettingsProvider: selectionArgs: false
09-02 15:26:21.310  1019  1223 D SettingsProvider: selectionArgs: 1002
09-02 15:26:21.310  1019  1223 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
,09-02 15:26:21.310  1019  1223 D SettingsProvider: ret = -1
09-02 15:26:21.310  1019  3093 D SettingsProvider: name = bt_svcst_com.android.bluetooth.hdp.HealthService
09-02 15:26:21.310  1019  3093 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
09-02 15:26:21.310  1019  3093 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
09-02 15:26:21.310  1019  3093 D SettingsProvider: selectionArgs: false
09-02 15:26:21.310  1019  3093 D SettingsProvider: selectionArgs: 1002,
,09-02 15:26:21.310  1019  3093 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
09-02 15:26:21.310  1019  3093 D SettingsProvider: ret = -1
09-02 15:26:21.310  1019  1032 D SettingsProvider: name = bt_svcst_com.android.bluetooth.pan.PanService
09-02 15:26:21.310  1019  1032 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
09-02 15:26:21.310  1019  1032 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
,09-02 15:26:21.310  1019  1032 D SettingsProvider: selectionArgs: false
09-02 15:26:21.310  1019  1032 D SettingsProvider: selectionArgs: 1002
09-02 15:26:21.310  1019  1032 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
09-02 15:26:21.310  1019  1032 D SettingsProvider: ret = -1
09-02 15:26:21.310  1019  3109 D SettingsProvider: name = bt_svcst_com.android.bluetooth.map.BluetoothMapService
09-02 15:26:21.310  1019  3109 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
09-02 15:26:21.310  1019  3109 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
,09-02 15:26:21.310  1019  3109 D SettingsProvider: selectionArgs: false
09-02 15:26:21.310  1019  3109 D SettingsProvider: selectionArgs: 1002
09-02 15:26:21.310  1019  3109 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
09-02 15:26:21.310  1019  3109 D SettingsProvider: ret = -1
09-02 15:26:21.310  1019  1484 D SettingsProvider: name = bt_svcst_com.broadcom.bt.service.sap.SapService
,09-02 15:26:21.310  1019  1484 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
09-02 15:26:21.310  1019  1484 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
,09-02 15:26:21.310  1019  1484 D SettingsProvider: selectionArgs: false
09-02 15:26:21.310  1019  1484 D SettingsProvider: selectionArgs: 1002
09-02 15:26:21.310  1019  1484 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
09-02 15:26:21.310  1019  1484 D SettingsProvider: ret = -1
,09-02 15:26:21.310  1019  1319 D SettingsProvider: name = bt_svcst_com.android.bluetooth.hfpclient.HeadsetClientService
09-02 15:26:21.310  1019  1319 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
09-02 15:26:21.310  1019  1319 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
09-02 15:26:21.310  1019  1319 D SettingsProvider: selectionArgs: false
09-02 15:26:21.310  1019  1319 D SettingsProvider: selectionArgs: 1002
09-02 15:26:21.310  1019  1319 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
,09-02 15:26:21.310  1019  1319 D SettingsProvider: ret = -1
09-02 15:26:21.310  1019  1485 D SettingsProvider: name = bt_svcst_com.android.bluetooth.a2dp.A2dpSinkService
09-02 15:26:21.310  1019  1485 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
09-02 15:26:21.310  1019  1485 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
,09-02 15:26:21.310  1019  1485 D SettingsProvider: selectionArgs: false
09-02 15:26:21.310  1019  1485 D SettingsProvider: selectionArgs: 1002
09-02 15:26:21.310  1019  1485 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
09-02 15:26:21.310  1019  1485 D SettingsProvider: ret = -1
09-02 15:26:21.310  1019  1031 D SettingsProvider: name = bt_svcst_com.android.bluetooth.sapclient.SapClientService
09-02 15:26:21.310  1019  1031 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3,
09-02 15:26:21.310  1019  1031 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
09-02 15:26:21.310  1019  1031 D SettingsProvider: selectionArgs: false
09-02 15:26:21.310  1019  1031 D SettingsProvider: selectionArgs: 1002
09-02 15:26:21.310  1019  1031 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
,09-02 15:26:21.310  1019  1031 D SettingsProvider: ret = -1
09-02 15:26:21.320  1019  2903 D SettingsProvider: name = bt_svcst_com.android.bluetooth.hid.HidDevService
09-02 15:26:21.320  1019  2903 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
09-02 15:26:21.320  1019  2903 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
,09-02 15:26:21.320  1019  2903 D SettingsProvider: selectionArgs: false
09-02 15:26:21.320  1019  2903 D SettingsProvider: selectionArgs: 1002
09-02 15:26:21.320  1019  2903 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
09-02 15:26:21.320  1019  2903 D SettingsProvider: ret = -1
,09-02 15:26:21.330  6906  6906 D BluetoothAdapterState: make
,09-02 15:26:21.330  6906  6906 I bluedroid: init
09-02 15:26:21.330  6906  6921 I BluetoothAdapterState: Entering OffState
,09-02 15:26:21.340  6906  6906 I bte_conf: bte_load_conf attempt to load stack conf from /etc/bluetooth/bt_stack.conf
,09-02 15:26:21.340  6906  6906 I bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
,09-02 15:26:21.340  6906  6906 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
09-02 15:26:21.340  6906  6906 I bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
,09-02 15:26:21.340  6906  6906 E bt-btif : btif_fetch_local_ble_random_bdaddr,
,09-02 15:26:21.340  6906  6906 I bluedroid: get_profile_interface socket
09-02 15:26:21.340  6906  6906 I bluedroid: get_profile_interface map_client
09-02 15:26:21.340  6906  6924 I GKI_LINUX: gki_task_entry task_id=1 [BTIF] starting
09-02 15:26:21.340  6906  6924 D BluetoothAdapterProperties: Address is:7C:F9:0E:37:96:AB
09-02 15:26:21.340  6906  6924 E BluetoothServiceJni: populateRssiValuesNative
,09-02 15:26:21.340  6906  6924 I bluedroid: getModelRssiValues
09-02 15:26:21.340  6906  6924 E BluetoothServiceJni: model_rssi_values_callback: low = -70, mid = -60, high = 127
09-02 15:26:21.340  6906  6924 D BluetoothAdapterProperties: modelRssiValuesCallback, low, mid, high = -70,-60,127
09-02 15:26:21.340  6906  6906 D BluetoothAdapterService: checkAddrForIOP: Loading from conf
09-02 15:26:21.340  6906  6924 D BluetoothAdapterProperties: Name is: A5-1
,09-02 15:26:21.340  1019  1019 D SettingsProvider: name = bluetooth_name
,09-02 15:26:21.350  6906  6906 D BluetoothA2dp: doBind(): CallingUid(myUserHandle) = 0
,09-02 15:26:21.350  1019  3109 D ActivityManager: bindService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothA2dp
,09-02 15:26:21.350  1019  3109 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
,09-02 15:26:21.350  1019  3109 W ActivityManager: userId = 0, bbcId = -10000
,09-02 15:26:21.350  1019  3109 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-02 15:26:21.350  1019  3109 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-02 15:26:21.360  6906  6914 I bluedroid: config_hci_snoop_log
,09-02 15:26:21.360  1019  1050 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 11 receivers.
,09-02 15:26:21.360  1019  1050 D BluetoothManagerService: Ble is always on enable gatt
,09-02 15:26:21.360  1019  1050 I BluetoothManagerService: enableGattForLeMode, doBind called
,09-02 15:26:21.360  1019  1050 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothGatt
,09-02 15:26:21.360  1019  1050 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.gatt.GattService; callingUser = 0; userId(target) = -2
,09-02 15:26:21.360  1019  1050 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
,09-02 15:26:21.370  6906  6906 I BtGatt.JNI: classInitNative(L900): classInitNative: Success!
09-02 15:26:21.370  1019  1050 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
,09-02 15:26:21.370  1019  1050 D SecContentProvider: uri = 3 selection = isBluetoothEnabled
,09-02 15:26:21.370  1019  1050 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 0 receivers.
,09-02 15:26:21.370  6906  6921 D BluetoothAdapterState: CURRENT_STATE=OFF, MSG = USER_TURN_ON
,09-02 15:26:21.370  6906  6921 D BluetoothAdapterProperties: Setting state to 11
09-02 15:26:21.370  6906  6921 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 11
09-02 15:26:21.370  6906  6921 D BluetoothAdapterService: Bluetooth PBAP supproted is true
09-02 15:26:21.370  6906  6921 D BluetoothAdapterService: updateAdapterState state is 11
,09-02 15:26:21.370  6906  6921 D BluetoothAdapterService: Autoconnection is available 
,09-02 15:26:21.380  6906  6921 D BluetoothAdapterService: updateAdapterState prevState = 10newState = 11
,09-02 15:26:21.380  1019  1019 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
09-02 15:26:21.380  1019  1019 I InputMethodManagerService: [BT Setting State] State =11
,09-02 15:26:21.380  6906  6921 D BluetoothSecureManager: getInstant: null
09-02 15:26:21.380  1182  1182 D BluetoothTile:  onBluetoothPairedDevicesChanged:
09-02 15:26:21.380  1182  1182 D BluetoothTile: onReceive : android.bluetooth.adapter.action.STATE_CHANGED
09-02 15:26:21.380  1182  1182 D BluetoothTile:  getBluetoothState : 11
09-02 15:26:21.390  6906  6921 D BluetoothSecureManager: calling getMethod for getService
09-02 15:26:21.390  6906  6921 D BluetoothSecureManager: calling getService
,09-02 15:26:21.390  1954  1954 I SamsungIME: STATE_CHANGED = 11, KEYBOARD_BT(0), mBTKeyboardCount =0
,09-02 15:26:21.390  6906  6921 D BluetoothSecureManager: getService return binder: android.os.BinderProxy@11558cff
,09-02 15:26:21.390  1019  2905 D BluetoothSecureManagerService: isSecureModeEnabled
09-02 15:26:21.390  1019  2905 D BluetoothSecureManagerService: getSecureModeSetting, name: secure_mode_enable
,09-02 15:26:21.390  1182  1704 D BluetoothTile:  handleUpdatestate:false name:null
,09-02 15:26:21.390  6906  6921 D BtConfig.SecureMode: isSecureModeOn:false
,09-02 15:26:21.390  6906  6921 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.gatt.GattService
,09-02 15:26:21.390  6906  6921 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.gatt.GattService
09-02 15:26:21.390  1182  1704 D STATUSBAR-QSTileView: onStateChanged: Bluetooth
09-02 15:26:21.390  6906  6921 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
,09-02 15:26:21.390  6906  6921 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.hfp.HeadsetService
09-02 15:26:21.390  6906  6921 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
,09-02 15:26:21.390  6906  6921 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.a2dp.A2dpService
,09-02 15:26:21.390  6906  6921 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
,09-02 15:26:21.390  6906  6921 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.hid.HidService
09-02 15:26:21.390  6906  6921 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
,09-02 15:26:21.400  6906  6921 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.hdp.HealthService
09-02 15:26:21.400  6906  6921 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.pan.PanService
09-02 15:26:21.400  1019  3213 D StatusBarManagerService: setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
09-02 15:26:21.400  1182  1182 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 )
09-02 15:26:21.400  1019  1082 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=false
09-02 15:26:21.400  6906  6921 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.pan.PanService
09-02 15:26:21.400  6906  6921 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
09-02 15:26:21.400  1296  1296 V BluetoothEventManager: Received android.bluetooth.adapter.action.STATE_CHANGED
09-02 15:26:21.400  6906  6921 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.map.BluetoothMapService
09-02 15:26:21.400  6906  6921 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
,09-02 15:26:21.400  6906  6921 W BluetoothAdapterService: isProfileEnabled(): profile not found com.broadcom.bt.service.sap.SapService
09-02 15:26:21.400  6906  6921 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfpclient.HeadsetClientService
,09-02 15:26:21.400  6906  6921 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.hfpclient.HeadsetClientService
09-02 15:26:21.400  6906  6921 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpSinkService
,09-02 15:26:21.400  6906  6921 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.a2dp.A2dpSinkService
09-02 15:26:21.400  6906  6921 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.sapclient.SapClientService
09-02 15:26:21.400  6906  6921 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.sapclient.SapClientService
09-02 15:26:21.400  1019  1082 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,09-02 15:26:21.400  6906  6921 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidDevService
09-02 15:26:21.400  1019  1082 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.nearby.discovery.service.DiscoveryService; callingUser = 0; userId(target) = 0
09-02 15:26:21.400  6212  6212 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-02 15:26:21.400  6906  6921 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.hid.HidDevService
09-02 15:26:21.400  1019  1082 W ActivityManager: userId = 0, bbcId = -10000
09-02 15:26:21.400  1019  1082 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-02 15:26:21.400  1019  1082 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-02 15:26:21.410  1296  1296 D BluetoothNotiBroadcastReceiver: onReceive
,09-02 15:26:21.410  1182  1182 V BluetoothStatusReceiver: Received android.bluetooth.adapter.action.STATE_CHANGED
09-02 15:26:21.410  1182  1182 D BluetoothStatusReceiver: AdapterStateChanged :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 11
,09-02 15:26:21.410  6906  6921 D BluetoothBondStateMachine: make
,09-02 15:26:21.420  6906  6921 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.gatt.GattService
09-02 15:26:21.420  6906  6921 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.gatt.GattService
09-02 15:26:21.420  6906  6921 W BluetoothAdapterService: Not skipping com.android.bluetooth.gatt.GattService
,09-02 15:26:21.420  6906  6926 I BluetoothBondStateMachine: StableState(): Entering Off State
,09-02 15:26:21.420  1019  1032 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,09-02 15:26:21.420  1019  1032 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.gatt.GattService; callingUser = 0; userId(target) = 0
,09-02 15:26:21.420  1019  1032 W ActivityManager: userId = 0, bbcId = -10000
,09-02 15:26:21.430  1019  1032 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-02 15:26:21.430  1019  1032 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-02 15:26:21.430  6906  6906 D BtGatt.DebugUtils: handleDebugAction() action=null
,09-02 15:26:21.430  6906  6906 D BtGatt.GattService: Received start request. Starting profile...
09-02 15:26:21.430  6906  6906 D BtGatt.GattService: start()
09-02 15:26:21.430  6906  6906 D BtGatt.GattService: start()
09-02 15:26:21.430  6906  6906 I bluedroid: get_profile_interface gatt
,09-02 15:26:21.430  6906  6906 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@a523621
09-02 15:26:21.430  6906  6906 D BtGatt.AdvertiseManager: advertise manager created
09-02 15:26:21.430  6906  6921 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hfp.HeadsetService
09-02 15:26:21.430  6906  6921 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
09-02 15:26:21.430  6906  6921 W BluetoothAdapterService: Not skipping com.android.bluetooth.hfp.HeadsetService
,09-02 15:26:21.430  1019  3105 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,09-02 15:26:21.430  1019  3105 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = 0
,09-02 15:26:21.440  1019  3105 W ActivityManager: userId = 0, bbcId = -10000
,09-02 15:26:21.440  1019  3105 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-02 15:26:21.440  1019  3105 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-02 15:26:21.440  6906  6921 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.a2dp.A2dpService
,09-02 15:26:21.440  6906  6921 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
09-02 15:26:21.440  6906  6921 W BluetoothAdapterService: Not skipping com.android.bluetooth.a2dp.A2dpService
,09-02 15:26:21.450  6906  6906 D BtGatt.GattService: mStartError = false
,09-02 15:26:21.450  6906  6906 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@a523621
,09-02 15:26:21.450  6906  6906 D HeadsetService: Received start request. Starting profile...
09-02 15:26:21.450  6906  6906 D HeadsetService: start()
,09-02 15:26:21.450  6906  6906 I BluetoothHeadsetServiceJni: classInitNative: succeeds
,09-02 15:26:21.450  6906  6906 D HeadsetStateMachine: make
,09-02 15:26:21.450  1019  2903 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
09-02 15:26:21.450  1019  2903 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
,09-02 15:26:21.450  1019  2903 W ActivityManager: userId = 0, bbcId = -10000
09-02 15:26:21.450  1019  2903 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-02 15:26:21.450  1019  2903 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-02 15:26:21.460  6906  6921 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hid.HidService
09-02 15:26:21.460  6906  6921 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
09-02 15:26:21.460  6906  6921 W BluetoothAdapterService: Not skipping com.android.bluetooth.hid.HidService
09-02 15:26:21.460  6906  6906 E HeadsetStateMachine: # of Max HF connection is 2
,09-02 15:26:21.460  1019  3093 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
09-02 15:26:21.460  1019  3093 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hid.HidService; callingUser = 0; userId(target) = 0
,09-02 15:26:21.470  1019  3093 W ActivityManager: userId = 0, bbcId = -10000
09-02 15:26:21.470  1019  3093 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-02 15:26:21.470  1019  3093 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-02 15:26:21.470  6906  6921 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hdp.HealthService
09-02 15:26:21.470  1019  1485 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
09-02 15:26:21.470  6906  6921 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
09-02 15:26:21.470  1019  1485 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hdp.HealthService; callingUser = 0; userId(target) = 0
09-02 15:26:21.470  6906  6921 W BluetoothAdapterService: Not skipping com.android.bluetooth.hdp.HealthService
,09-02 15:26:21.470  1019  1485 W ActivityManager: userId = 0, bbcId = -10000
,09-02 15:26:21.470  1019  1485 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-02 15:26:21.470  1019  1485 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-02 15:26:21.480  1019  1032 D ActivityManager: bindService callerProcessName:com.android.bluetooth, calleePkgName: com.android.server.telecom, action: android.bluetooth.IBluetoothHeadsetPhone
09-02 15:26:21.480  6906  6921 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.pan.PanService
09-02 15:26:21.480  6906  6921 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.pan.PanService
09-02 15:26:21.480  6906  6921 W BluetoothAdapterService: Not skipping com.android.bluetooth.pan.PanService
,09-02 15:26:21.480  1019  1032 D ActivityManager: retrieveServiceLocked(): component = com.android.server.telecom/com.android.server.telecom.BluetoothPhoneService; callingUser = 0; userId(target) = 0
,09-02 15:26:21.480  1019  1032 W ActivityManager: userId = 0, bbcId = -10000
09-02 15:26:21.480  1019  1032 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-02 15:26:21.480  1019  1032 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.server.telecom
,09-02 15:26:21.480  1019  2905 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,09-02 15:26:21.480  1019  2905 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pan.PanService; callingUser = 0; userId(target) = 0
,09-02 15:26:21.480  1019  2905 W ActivityManager: userId = 0, bbcId = -10000
,09-02 15:26:21.480  1019  2905 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-02 15:26:21.480  1019  2905 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-02 15:26:21.490  1019  1223 D ActivityManager: bindService callerProcessName:com.android.bluetooth, calleePkgName: com.android.server.telecom, action: com.samsung.bt.hfp.IBluetoothHeadsetVoIP
09-02 15:26:21.490  1019  1223 D ActivityManager: retrieveServiceLocked(): component = com.android.server.telecom/com.android.server.telecom.BluetoothVoIPService; callingUser = 0; userId(target) = 0
,09-02 15:26:21.490  1019  1223 W ActivityManager: userId = 0, bbcId = -10000
09-02 15:26:21.490  1019  1223 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-02 15:26:21.490  1019  1223 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.server.telecom
09-02 15:26:21.490  6906  6906 I bluedroid: get_profile_interface handsfree
09-02 15:26:21.490  6906  6921 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.map.BluetoothMapService
,09-02 15:26:21.490  6906  6921 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
09-02 15:26:21.490  6906  6921 W BluetoothAdapterService: Not skipping com.android.bluetooth.map.BluetoothMapService
,09-02 15:26:21.490  1883  1883 D EasyUnlockReceiver: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.easyunlock.authorization.BluetoothStateChangeReceiver (has extras) }.
09-02 15:26:21.490  1019  3214 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
09-02 15:26:21.490  1019  3214 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.map.BluetoothMapService; callingUser = 0; userId(target) = 0
,09-02 15:26:21.490  1019  3214 W ActivityManager: userId = 0, bbcId = -10000
09-02 15:26:21.490  1019  3214 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-02 15:26:21.490  1019  3214 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-02 15:26:21.500  6906  6921 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.broadcom.bt.service.sap.SapService
,09-02 15:26:21.500  6906  6921 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
,09-02 15:26:21.500  6906  6921 W BluetoothAdapterService: Not skipping com.broadcom.bt.service.sap.SapService
,09-02 15:26:21.500  1019  3213 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
09-02 15:26:21.500  1019  3213 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.broadcom.bt.service.sap.SapService; callingUser = 0; userId(target) = 0
,09-02 15:26:21.500  1019  3213 W ActivityManager: userId = 0, bbcId = -10000
09-02 15:26:21.500  1019  3213 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,09-02 15:26:21.500  1019  3213 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
09-02 15:26:21.500  1883  1883 D BtServices: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.proximity.BluetoothServicesAdapterStateChangeReceiver (has extras) }.
,09-02 15:26:21.510  6906  6921 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hfpclient.HeadsetClientService
09-02 15:26:21.510  6906  6921 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfpclient.HeadsetClientService
09-02 15:26:21.510  6906  6921 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.hfpclient.HeadsetClientService
09-02 15:26:21.510  6906  6921 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.a2dp.A2dpSinkService
09-02 15:26:21.510  6906  6921 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpSinkService
09-02 15:26:21.510  6906  6921 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.a2dp.A2dpSinkService
09-02 15:26:21.510  6906  6921 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.sapclient.SapClientService
09-02 15:26:21.510  6906  6921 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.sapclient.SapClientService
09-02 15:26:21.510  6906  6921 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.sapclient.SapClientService
09-02 15:26:21.510  6906  6921 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hid.HidDevService
09-02 15:26:21.510  6906  6921 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidDevService
09-02 15:26:21.510  6906  6921 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.hid.HidDevService
09-02 15:26:21.510  6906  6921 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=true, isTurningOff()=false
,09-02 15:26:21.510  6906  6906 I DualScoManager: Instantiating Dual Sco Manager
,09-02 15:26:21.510  6906  6906 I DualScoManager: Set HeadsetServiceHelper
,09-02 15:26:21.510  6906  6906 D BluetoothAtMessage: createCMTIContentObservers
,09-02 15:26:21.510  1019  2952 D SettingsProvider: name = bluetooth_hfp_allowed_bvra
,09-02 15:26:21.510  1019  2952 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
09-02 15:26:21.510  1019  2952 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
09-02 15:26:21.510  1019  2952 D SettingsProvider: selectionArgs: false
09-02 15:26:21.510  1019  2952 D SettingsProvider: selectionArgs: 1002
09-02 15:26:21.510  1019  2952 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
09-02 15:26:21.510  1019  2952 D SettingsProvider: ret = -1
09-02 15:26:21.520  6906  6931 D HeadsetStateMachine: Enter Disconnected: -2
,09-02 15:26:21.520  6906  6906 D HeadsetService: mStartError = false
09-02 15:26:21.520  6906  6906 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@a523621
,09-02 15:26:21.520  6906  6906 E BluetoothAdapterService(173159969): processProfileServiceStateChanged() serviceName=com.android.bluetooth.gatt.GattService, state=12, doUpdate=false
,09-02 15:26:21.520  6906  6906 D A2dpService: Received start request. Starting profile...
09-02 15:26:21.520  6906  6906 D A2dpService: start()
,09-02 15:26:21.520  6906  6931 D HeadsetStateMachine: Clear mHeadsetBrsf
09-02 15:26:21.520  6906  6931 D HeadsetStateMachine: map size, before remove : 0
09-02 15:26:21.520  6906  6931 D HeadsetStateMachine: map size, after remove: 0
,09-02 15:26:21.520  6906  6906 I BluetoothAvrcpServiceJni: classInitNative: succeeds
,09-02 15:26:21.520  6906  6906 I bluedroid: get_profile_interface avrcp
,09-02 15:26:21.530  6906  6906 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,09-02 15:26:21.540  6906  6906 I Avrcp   :  Updating now playing list upon AVRCP Start
,09-02 15:26:21.550  6906  6933 D BluetoothMediaBrowser:  getNowPlayingListcontent://media/external/audio/playlists?secFilter=include
,09-02 15:26:21.550  6906  6906 I BluetoothA2dpServiceJni: classInitNative: succeeds
09-02 15:26:21.550  6906  6906 D A2dpStateMachine: make
,09-02 15:26:21.550  6906  6906 I bluedroid: get_profile_interface a2dp
,09-02 15:26:21.550  6906  6935 I GKI_LINUX: gki_task_entry task_id=2 [A2DP-MEDIA] starting
,09-02 15:26:21.550  6906  6906 E bt-btif : warning : media task started media_task_refcnt 1 
,09-02 15:26:21.550  6906  6906 D A2dpService: mStartError = false
09-02 15:26:21.550  6906  6906 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@a523621
,09-02 15:26:21.550  6906  6934 D A2dpStateMachine: Enter Disconnected: -2
,09-02 15:26:21.550  6906  6906 I BluetoothHidServiceJni: classInitNative: succeeds
,09-02 15:26:21.550  6906  6906 D HidService: Received start request. Starting profile...
09-02 15:26:21.550  6906  6906 D HidService: start()
09-02 15:26:21.550  6906  6906 I bluedroid: get_profile_interface hidhost
09-02 15:26:21.550  6906  6906 D HidService: setHidService(): set to: null
09-02 15:26:21.550  6906  6906 D HidService: mStartError = false
09-02 15:26:21.550  6906  6906 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@a523621
,09-02 15:26:21.560  6906  6906 I BluetoothHealthServiceJni: classInitNative: succeeds
,09-02 15:26:21.560  6906  6906 D HealthService: Received start request. Starting profile...
09-02 15:26:21.560  6906  6906 D HealthService: start()
,09-02 15:26:21.560  6906  6906 I bluedroid: get_profile_interface health
,09-02 15:26:21.560  6906  6906 D HealthService: mStartError = false
09-02 15:26:21.560  6906  6906 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@a523621
09-02 15:26:21.560  6906  6906 D HeadsetStateMachine: Try to query the phonestate on bind
,09-02 15:26:21.560  1433  6854 I Telecom : BluetoothPhoneService: queryPhoneState
,09-02 15:26:21.560  1433  1433 I Telecom : BluetoothPhoneService: handleMessage(7) / param 0
09-02 15:26:21.560  1433  1433 I Telecom : BluetoothPhoneService: updateHeadsetWithCallState
09-02 15:26:21.560  1433  6854 I Telecom : BluetoothPhoneService: Result of Message : true
,09-02 15:26:21.560  6906  6906 I BluetoothPanServiceJni: classInitNative(L105): succeeds
,09-02 15:26:21.560  6906  6906 D PanService: Received start request. Starting profile...
09-02 15:26:21.560  6906  6906 D PanService: start()
09-02 15:26:21.560  6906  6906 D BluetoothPanServiceJni: initializeNative(L110): pan
09-02 15:26:21.560  6906  6906 I bluedroid: get_profile_interface pan
,09-02 15:26:21.560  6906  6933 D BluetoothMediaBrowser: no now playing list
09-02 15:26:21.560  6906  6933 D BluetoothMediaBrowser:  getNowPlayingId now playing id : -1
09-02 15:26:21.560  6906  6906 D PanService: mStartError = false
09-02 15:26:21.560  6906  6906 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@a523621
09-02 15:26:21.560  6906  6906 D HeadsetStateMachine: Proxy object connected
,09-02 15:26:21.560  6906  6906 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=0
09-02 15:26:21.560  6906  6931 D HeadsetStateMachine: Disconnected process message: 11
,09-02 15:26:21.570  6906  6906 D BluetoothMapService: Received start request. Starting profile...
,09-02 15:26:21.570  6906  6906 D BluetoothMapService: start()
,09-02 15:26:21.570  6906  6906 D BluetoothMapService: mStartError = false
,09-02 15:26:21.570  6906  6906 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@a523621
,09-02 15:26:21.570  6906  6906 D HeadsetPhoneState: sendDeviceDataStateChanged
,09-02 15:26:21.570  6906  6931 D HeadsetStateMachine: Disconnected process message: 18,
09-02 15:26:21.570  6906  6906 D HeadsetPhoneState: Signal level : previous=0 curr=0
09-02 15:26:21.570  6906  6906 I BluetoothSAPServiceJni: classInitNative(L204): succeeds
,09-02 15:26:21.570  6906  6906 D SapService: Received start request. Starting profile...
,09-02 15:26:21.570  6906  6906 D SapService: start()
09-02 15:26:21.570  6906  6906 D BluetoothSAPServiceJni: initializeNative(L209): sap
09-02 15:26:21.570  6906  6906 I bluedroid: get_profile_interface sap
09-02 15:26:21.570  6906  6906 D SapService: mStartError = false
09-02 15:26:21.570  6906  6906 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@a523621
09-02 15:26:21.570  6906  6906 E BluetoothAdapterService(173159969): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hfp.HeadsetService, state=12, doUpdate=true
09-02 15:26:21.570  6906  6906 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,09-02 15:26:21.570  6906  6906 D BluetoothA2dp: Proxy object connected
09-02 15:26:21.570  6906  6931 D HeadsetStateMachine: Disconnected process message: 10
09-02 15:26:21.570  6906  6906 D BluetoothAdapterService: Bluetooth A2dp source service connected
09-02 15:26:21.570  6906  6906 E BluetoothAdapterService(173159969): processProfileServiceStateChanged() serviceName=com.android.bluetooth.a2dp.A2dpService, state=12, doUpdate=true
09-02 15:26:21.570  6906  6931 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
09-02 15:26:21.570  6906  6906 E BluetoothAdapterService(173159969): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hid.HidService, state=12, doUpdate=true
09-02 15:26:21.570  6906  6931 D HeadsetStateMachine: Disconnected process message: 11
,09-02 15:26:21.570  6906  6906 E BluetoothAdapterService(173159969): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hdp.HealthService, state=12, doUpdate=true
,09-02 15:26:21.580  6906  6906 E BluetoothAdapterService(173159969): processProfileServiceStateChanged() serviceName=com.android.bluetooth.pan.PanService, state=12, doUpdate=true,
,09-02 15:26:21.600  6906  6906 E BluetoothAdapterService(173159969): processProfileServiceStateChanged() serviceName=com.android.bluetooth.map.BluetoothMapService, state=12, doUpdate=true
,09-02 15:26:21.600  6906  6906 E BluetoothAdapterService(173159969): processProfileServiceStateChanged() serviceName=com.broadcom.bt.service.sap.SapService, state=12, doUpdate=true
,09-02 15:26:21.600  6906  6921 D BluetoothAdapterState: CURRENT_STATE=PENDING, MSG = STARTED, isTurningOn=true, isTurningOff=false
,09-02 15:26:21.600  6906  6921 I bluedroid: enable
,09-02 15:26:21.600  6906  6921 I bt_hci_bdroid: init
09-02 15:26:21.610  6906  6939 I GKI_LINUX: gki_task_entry task_id=0 [BTU] starting
,09-02 15:26:21.610  6906  6921 I bt_vendor: bt-vendor : init
,09-02 15:26:21.610  6906  6921 I bt_vendor: bt-vendor : get_bt_soc_type
,09-02 15:26:21.610  6906  6921 E bt_vendor: get_bt_soc_type: Failed to get soc type
,09-02 15:26:21.610  6906  6921 I bt_vendor: init: Local BD Address : ab:96:37:0e:f9:7c
09-02 15:26:21.610  6906  6921 D bt_userial_mct: userial_init
,09-02 15:26:21.610  6906  6921 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: Off
,09-02 15:26:21.610  6906  6921 I bt_vendor: Starting hciattach daemon
09-02 15:26:21.610  6906  6921 I bt_vendor: try to set false
,09-02 15:26:21.610  6906  6921 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: On
,09-02 15:26:21.610  6906  6921 I bt_vendor: Starting hciattach daemon
09-02 15:26:21.610  6906  6921 I bt_vendor: try to set true
,09-02 15:26:21.630  6943  6943 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: init.qcom.bt.sh config =  ,
,09-02 15:26:21.680  6949  6949 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Transport : smd 
,09-02 15:26:21.690  6950  6950 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** ,
,09-02 15:26:21.700  6952  6952 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Power Class: Ignored. Default(1) used (1-CLASS1/2-CLASS2/3-CUSTOM) ,
,09-02 15:26:21.710  6953  6953 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Power Class: To override, Before turning BT ON; setprop qcom.bt.dev_power_class <1 or 2 or 3> ,
,09-02 15:26:21.720  6954  6954 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: LE Power Class: Ignored. Default(2) used (1-CLASS1/2-CLASS2/3-CUSTOM) ,
,09-02 15:26:21.730  6955  6955 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: LE Power Class: To override, Before turning BT ON; setprop qcom.bt.le_dev_pwr_class <1 or 2 or 3> ,
,09-02 15:26:21.920  6958  6958 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Bluetooth QSoC firmware download succeeded, /dev/ttyHS0 qualcomm 3000000 7c:f9:0e:37:96:ab ,
,09-02 15:26:21.930  6959  6959 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** ,
,09-02 15:26:21.970  6906  6921 I bt_vendor: bluetooth satus is on
,09-02 15:26:21.970  6906  6941 D bt_userial_mct: userial_open(port:0)
09-02 15:26:21.970  6906  6941 I bt_vendor: bt-vendor : BT_VND_OP_USERIAL_OPEN
,09-02 15:26:21.970  6906  6941 I bt_vendor: Done intiailizing UART
,09-02 15:26:21.970  6906  6941 I bt_vendor: Done intiailizing UART,
,09-02 15:26:21.970  6906  6941 I bt_userial_mct: CMD=65, EVT=65, ACL_Out=66, ACL_In=66
09-02 15:26:21.970  6906  6941 I bt_vendor: Bluetooth Firmware and transport layer are initialized
09-02 15:26:21.980  6906  6961 D bt_userial_mct: Entering userial_read_thread(),
,09-02 15:26:21.980  6906  6939 I         : BTE_InitTraceLevels -- TRC_HCI
,09-02 15:26:21.980  6906  6939 I         : BTE_InitTraceLevels -- TRC_L2CAP
,09-02 15:26:21.980  6906  6939 I         : BTE_InitTraceLevels -- TRC_RFCOMM
09-02 15:26:21.980  6906  6939 I         : BTE_InitTraceLevels -- TRC_AVDT
,09-02 15:26:21.980  6906  6939 I         : BTE_InitTraceLevels -- TRC_AVRC
09-02 15:26:21.980  6906  6939 I         : BTE_InitTraceLevels -- TRC_A2D
,09-02 15:26:21.980  6906  6939 I         : BTE_InitTraceLevels -- TRC_BNEP
09-02 15:26:21.980  6906  6939 I         : BTE_InitTraceLevels -- TRC_BTM
,09-02 15:26:21.980  6906  6939 I         : BTE_InitTraceLevels -- TRC_GAP
09-02 15:26:21.980  6906  6939 I         : BTE_InitTraceLevels -- TRC_PAN
,09-02 15:26:21.980  6906  6939 I         : BTE_InitTraceLevels -- TRC_SAP
09-02 15:26:21.980  6906  6939 I         : BTE_InitTraceLevels -- TRC_SDP
09-02 15:26:21.980  6906  6939 I         : BTE_InitTraceLevels -- TRC_GATT
,09-02 15:26:21.980  6906  6939 I         : BTE_InitTraceLevels -- TRC_SMP
09-02 15:26:21.980  6906  6939 I         : BTE_InitTraceLevels -- TRC_BTAPP
,09-02 15:26:21.990  6906  6939 I         : BTE_InitTraceLevels -- TRC_BTIF
09-02 15:26:21.990  6906  6939 I         : BTE_InitTraceLevels -- TRC_PROTOCOL
,09-02 15:26:22.080  6906  6939 W bt-l2cap: l2c_link_processs_ble_num_bufs 16
,09-02 15:26:22.090  6906  6939 E bt-btm  : BTM_SecRegister:p_cb_info->p_le_callback == 0xa3f686e9 
,09-02 15:26:22.090  6906  6939 E bt-btm  : BTM_SecRegister: btm_cb.api.p_le_callback = 0xa3f686e9 
,09-02 15:26:22.110  6906  6924 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 10 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 32 mNumOfOffloadedScanFilterSupported = 16 mOffloadedScanResultStorageBytes= 10240 mIsActivityAndEnergyReporting = true mAobleSupported = 0
,09-02 15:26:22.110  6906  6924 E bt-btif : Calling BTA_HhEnable
,09-02 15:26:22.120  6906  6924 E bt-btif : Adding UUID=0x110Adapter_property service_mask:0x2120048
,09-02 15:26:22.120  6906  6924 D BluetoothAdapterProperties: Address is:7C:F9:0E:37:96:AB
09-02 15:26:22.120  6906  6924 E BluetoothServiceJni: populateRssiValuesNative
09-02 15:26:22.120  6906  6924 I bluedroid: getModelRssiValues
09-02 15:26:22.120  6906  6924 E BluetoothServiceJni: model_rssi_values_callback: low = -70, mid = -60, high = 127
09-02 15:26:22.120  6906  6924 D BluetoothAdapterProperties: modelRssiValuesCallback, low, mid, high = -70,-60,127
,09-02 15:26:22.120  6906  6924 D BluetoothAdapterProperties: Name is: A5-1
,09-02 15:26:22.120  1019  1019 D SettingsProvider: name = bluetooth_name
,09-02 15:26:22.130  6212  6212 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes,
,09-02 15:26:22.130  6906  6924 D BluetoothUtils: getBtEnabledContainers(): btContainers = []
,09-02 15:26:22.130  6906  6924 D BluetoothAdapterProperties: Scan Mode:20
,09-02 15:26:22.130  6906  6924 D BluetoothAdapterProperties: Discoverable Timeout:120
,09-02 15:26:22.130  6906  6924 D BluetoothAdapterProperties: LE Address is:FC:F3:1C:6E:2D:57
,09-02 15:26:22.130  6906  6924 E bt-btif : btif_handle_bluetooth_enable_evt: btif_core_radio_ref_count:1
,09-02 15:26:22.130  6906  6924 E bt-btif : btif_sock_init, radio_req:0, rfc_init:0, vhci_init:0
,09-02 15:26:22.130  6906  6924 E bt-btif : btif_sock_init: !radio_req && !rfc_init
,09-02 15:26:22.130  6906  6924 E bt-btif : btif_sock_init: !vhci_init
,09-02 15:26:22.140  6906  6924 D IOP_DB_BT: db_open: file /etc/bluetooth/iop_bt.db
09-02 15:26:22.140  6906  6924 D IOP_DB_BT: db_open: db_open : handle 3028078608l, read 13894 bytes onto local cache
09-02 15:26:22.140  6906  6924 D IOP_DB_BT: db_query: id __IOPFLAGS :: key __KEY_ENABLE_VERBOSE, value 1
09-02 15:26:22.140  6906  6961 E bt_mct  : hci lib postload completed
09-02 15:26:22.140  6906  6924 D IOP_DB_BT: db_query: result 1
09-02 15:26:22.140  6906  6924 I         : iop_db_open: iop_db_open status 0
,09-02 15:26:22.140  6906  6924 D bte_conf: Device ID record 1 : primary
09-02 15:26:22.140  6906  6924 D bte_conf:   vendorId            = 0075
09-02 15:26:22.140  6906  6924 D bte_conf:   vendorIdSource      = 0001
09-02 15:26:22.140  6906  6924 D bte_conf:   product             = 0100
09-02 15:26:22.140  6906  6924 D bte_conf:   version             = 0200
09-02 15:26:22.140  6906  6924 D bte_conf:   clientExecutableURL = 
,09-02 15:26:22.140  6906  6924 D bte_conf:   serviceDescription  = 
09-02 15:26:22.140  6906  6924 D bte_conf:   documentationURL    = 
09-02 15:26:22.140  6906  6924 D bte_conf: bte_load_did_conf no section named DID2.
,09-02 15:26:22.140  6906  6924 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
,09-02 15:26:22.140  6906  6921 D BluetoothAdapterState: CURRENT_STATE=PENDING, MSG = ENABLE_READY, isTurningOn=true, isTurningOff=false
,09-02 15:26:22.140  6906  6921 D BluetoothAdapterProperties: ScanMode =  20
,09-02 15:26:22.140  6906  6921 D BluetoothAdapterProperties: State =  11
,09-02 15:26:22.140  1019  1223 D SecContentProvider: uri = 3 selection = isDiscoverableEnabled
,09-02 15:26:22.150  6906  6921 D BluetoothAdapterProperties: Setting state to 12
,09-02 15:26:22.150  6906  6921 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
,09-02 15:26:22.150  1019  1032 D SettingsProvider: name = bluetooth_a2dp_sink_mode
,09-02 15:26:22.150  1019  1032 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
,09-02 15:26:22.150  1019  1032 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
09-02 15:26:22.150  1019  1032 D SettingsProvider: selectionArgs: false
09-02 15:26:22.150  1019  1032 D SettingsProvider: selectionArgs: 1002
09-02 15:26:22.150  1019  1032 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
09-02 15:26:22.150  1019  1032 D SettingsProvider: ret = -1
,09-02 15:26:22.150  6906  6921 D BluetoothAdapterService: Bluetooth PBAP supproted is true
,09-02 15:26:22.150  6906  6921 D BluetoothAdapterService: updateAdapterState state is 12
,09-02 15:26:22.150  6906  6924 D BluetoothUtils: getBtEnabledContainers(): btContainers = []
09-02 15:26:22.150  6906  6924 D BluetoothAdapterProperties: Scan Mode:21
09-02 15:26:22.150  6906  6924 D BluetoothAdapterProperties: Discoverable Timeout:120
,09-02 15:26:22.160  1019  3109 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
09-02 15:26:22.160  1019  3109 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pbap.BluetoothPbapService; callingUser = 0; userId(target) = 0
,09-02 15:26:22.160  1019  3109 W ActivityManager: userId = 0, bbcId = -10000
09-02 15:26:22.160  1019  3109 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-02 15:26:22.160  1019  3109 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-02 15:26:22.160  6906  6921 D BluetoothAdapterService: Autoconnection is available 
,09-02 15:26:22.160  6906  6921 D BluetoothAdapterService: updateAdapterState prevState = 11newState = 12
,09-02 15:26:22.160  6906  6921 D BluetoothAdapterService: starting service from this receiver
09-02 15:26:22.160  1019  1031 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
09-02 15:26:22.160  1019  1031 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.samsung.ble.BleAutoConnectService; callingUser = 0; userId(target) = 0
,09-02 15:26:22.160  1296  1307 D Bluetoothsap: onBluetoothStateChange: up=true
09-02 15:26:22.160  1296  1307 D Bluetoothsap: Binding service...
,09-02 15:26:22.160  1019  1031 W ActivityManager: userId = 0, bbcId = -10000
,09-02 15:26:22.170  1019  1031 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,09-02 15:26:22.170  1296  1307 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:2136 android.content.ContextWrapper.bindService:559 com.broadcom.bt.service.sap.BluetoothSap.doBind:186 com.broadcom.bt.service.sap.BluetoothSap$1.onBluetoothStateChange:156 android.bluetooth.IBluetoothStateChangeCallback$Stub.onTransact:55 
09-02 15:26:22.170  1019  1031 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-02 15:26:22.170  6906  6921 I BluetoothAdapterState: Entering On State from state = 11
,09-02 15:26:22.180  6212  6212 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-02 15:26:22.180  6212  6212 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-02 15:26:22.180  6212  6212 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-02 15:26:22.180  6212  6212 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-02 15:26:22.180  6212  6212 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-02 15:26:22.180  6212  6212 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-02 15:26:22.180  6212  6212 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-02 15:26:22.180  6212  6212 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-02 15:26:22.190  6906  6906 I BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED, state: 12
,09-02 15:26:22.190  6212  6266 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-02 15:26:22.190  6212  6266 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-02 15:26:22.190  6212  6266 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-02 15:26:22.190  6212  6266 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-02 15:26:22.190  6212  6266 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-02 15:26:22.190  6212  6266 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-02 15:26:22.190  6212  6266 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-02 15:26:22.190  6212  6266 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-02 15:26:22.190  6212  6212 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-02 15:26:22.200  6212  6266 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-02 15:26:22.200  6212  6266 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,09-02 15:26:22.200  6212  6266 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@2e2ceb8a added. We now have 8 listener(s)
09-02 15:26:22.200  6212  6266 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-02 15:26:22.200  1019  1223 D SecContentProvider: uri = 18 selection = isWifiEnabled
,09-02 15:26:22.200  1019  1223 D SecContentProvider2: uri = 20 selection = isWifiStateChangeAllowed
,09-02 15:26:22.200  1019  1223 D SecContentProvider2: mCursor = null
,09-02 15:26:22.210  1019  1223 D WifiService: setWifiEnabled: false pid=6212, uid=10155
,09-02 15:26:22.210  1019  1223 D SettingsProvider: name = wifi_on
,09-02 15:26:22.210  6212  6266 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-02 15:26:22.210  1019  3093 D SecContentProvider: uri = 18 selection = isWifiEnabled
,09-02 15:26:22.210  1019  3093 D SecContentProvider2: uri = 20 selection = isWifiStateChangeAllowed
,09-02 15:26:22.210  1019  3093 D SecContentProvider2: mCursor = null
,09-02 15:26:22.220  1019  3093 D WifiService: setWifiEnabled: true pid=6212, uid=10155
,09-02 15:26:22.220  1019  3093 W ActivityManager: Permission Denial: getCurrentUser() from pid=6212, uid=10155 requires android.permission.INTERACT_ACROSS_USERS
,09-02 15:26:22.220  1019  3093 W WifiService: Failed getting userId using ActivityManagerNative
09-02 15:26:22.220  1019  3093 W WifiService: java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=6212, uid=10155 requires android.permission.INTERACT_ACROSS_USERS
09-02 15:26:22.220  1019  3093 W WifiService: 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:23916)
09-02 15:26:22.220  1019  3093 W WifiService: 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2216)
09-02 15:26:22.220  1019  3093 W WifiService: 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2204)
09-02 15:26:22.220  1019  3093 W WifiService: 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:223)
09-02 15:26:22.220  1019  3093 W WifiService: 	at android.os.Binder.execTransact(Binder.java:446)
,09-02 15:26:22.220  1019  3093 D SettingsProvider: name = wifi_on
,09-02 15:26:22.220  1019  1132 E WifiHW  : ##################### set firmware type 0 #####################
,09-02 15:26:22.360  1019  1050 I art     : Explicit concurrent mark sweep GC freed 67097(3MB) AllocSpace objects, 9(144KB) LOS objects, 33% free, 27MB/41MB, paused 2.682ms total 189.105ms
,09-02 15:26:22.360  1019  1050 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: com.broadcom.bt.service.sap.IBluetoothSap
09-02 15:26:22.360  1019  1050 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.broadcom.bt.service.sap.SapService; callingUser = 0; userId(target) = 0
,09-02 15:26:22.360  1019  1050 W ActivityManager: userId = 0, bbcId = -10000
09-02 15:26:22.360  1019  1050 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-02 15:26:22.360  1019  1050 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,09-02 15:26:22.360  1296  1307 D Bluetoothsap: bindService called to Bluetooth SAP Service
,09-02 15:26:22.360  1433  1453 D BluetoothAdapter: onBluetoothStateChange: up=true
09-02 15:26:22.360  1433  1453 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,09-02 15:26:22.360  1296  1309 D BluetoothAdapter: onBluetoothStateChange: up=true
09-02 15:26:22.360  1296  1309 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,09-02 15:26:22.360  1444  1470 D BluetoothAdapter: onBluetoothStateChange: up=true
09-02 15:26:22.360  1444  1470 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,09-02 15:26:22.360  1296  6395 D BluetoothPan: Binding service...
,09-02 15:26:22.370  6906  6906 I BluetoothPbapService: Handler(): got msg=1
,09-02 15:26:22.370  1019  1050 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothPan
09-02 15:26:22.370  1019  1050 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pan.PanService; callingUser = 0; userId(target) = 0
,09-02 15:26:22.370  1019  2905 D SecContentProvider: uri = 4 selection = isProfileAuthorizedBySecurityPolicy
09-02 15:26:22.370  1019  1050 W ActivityManager: userId = 0, bbcId = -10000
09-02 15:26:22.370  1019  1050 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-02 15:26:22.370  1019  1050 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,09-02 15:26:22.370  1019  1050 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,09-02 15:26:22.370  1019  1050 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
09-02 15:26:22.370  1019  1050 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,09-02 15:26:22.370  1019  1050 E BluetoothHeadset: BluetoothHeadset service is binded
,09-02 15:26:22.370  6212  6220 D BluetoothAdapter: onBluetoothStateChange: up=true
,09-02 15:26:22.370  6212  6220 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,09-02 15:26:22.370  1182  2347 D BluetoothAdapter: onBluetoothStateChange: up=true
09-02 15:26:22.370  1182  2347 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,09-02 15:26:22.370  1883  2117 D BluetoothAdapter: onBluetoothStateChange: up=true
09-02 15:26:22.370  1883  2117 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,09-02 15:26:22.370  6368  6381 D BluetoothAdapter: onBluetoothStateChange: up=true
09-02 15:26:22.370  6368  6381 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,09-02 15:26:22.380  6906  6969 V BluetoothPbapService: PBAP Service initSocket try: 0
,09-02 15:26:22.380  1296  6395 D BluetoothPbap: onBluetoothStateChange: up=true
,09-02 15:26:22.380  1019  1050 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothPbap
09-02 15:26:22.380  1019  1050 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pbap.BluetoothPbapService; callingUser = 0; userId(target) = 0
,09-02 15:26:22.380  1019  1050 W ActivityManager: userId = 0, bbcId = -10000
09-02 15:26:22.380  1019  1050 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-02 15:26:22.380  1019  1050 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,09-02 15:26:22.380  1433  1451 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,09-02 15:26:22.380  1019  1050 D ActivityManager: bindService callerProcessName:com.android.server.telecom, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
09-02 15:26:22.380  1019  1050 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,09-02 15:26:22.380  6906  6969 D BluetoothSocket: bindListen(): myUserId = 0
,09-02 15:26:22.390  1019  1050 W ActivityManager: userId = 0, bbcId = -10000
09-02 15:26:22.390  1019  1050 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-02 15:26:22.390  1019  1050 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.server.telecom, destAppInfo.processName = com.android.bluetooth
,09-02 15:26:22.390  1433  1451 E BluetoothHeadset: BluetoothHeadset service is binded
,09-02 15:26:22.390  6906  6969 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-02 15:26:22.390  1296  1296 D Bluetoothsap: BluetoothSAP Proxy object connected
09-02 15:26:22.390  1296  1296 D SapProfile: Bluetooth service connected
09-02 15:26:22.390  1296  1296 D Bluetoothsap: getConnectedDevices()
09-02 15:26:22.390  6906  6964 D BluetoothA2dp: onBluetoothStateChange: up=true
,09-02 15:26:22.390  1019  1050 D BluetoothAdapter: onBluetoothStateChange: up=true
09-02 15:26:22.390  1019  1050 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,09-02 15:26:22.390  6906  6969 D BluetoothSocket: bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[74]}
09-02 15:26:22.390  6906  6969 D BluetoothSocket: bindListen(), new LocalSocket 
09-02 15:26:22.390  6906  6969 D BluetoothSocket: bindListen(), new LocalSocket.getInputStream() 
09-02 15:26:22.390  6906  6969 D BluetoothSocket: bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@12e7ede2
,09-02 15:26:22.390  2850  6855 D BluetoothA2dp: onBluetoothStateChange: up=true
09-02 15:26:22.390  6906  6969 D BluetoothSocket: channel: 19
09-02 15:26:22.390  6906  6969 D BluetoothPbapService: PBAP Socket is BluetoothServerSocket
,09-02 15:26:22.390  1296  1296 D BluetoothPan: BluetoothPAN Proxy object connected
09-02 15:26:22.390  1296  1296 D PanProfile: Bluetooth service connected
,09-02 15:26:22.390  2850  6855 D BluetoothA2dp: doBind(): CallingUid(myUserHandle) = 0
,09-02 15:26:22.400  1019  1050 D ActivityManager: bindService callerProcessName:com.samsung.android.providers.context, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothA2dp
09-02 15:26:22.400  1019  1050 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
,09-02 15:26:22.400  1019  1050 W ActivityManager: userId = 0, bbcId = -10000
09-02 15:26:22.400  1019  1050 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-02 15:26:22.400  1019  1050 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.android.providers.context, destAppInfo.processName = com.android.bluetooth
,09-02 15:26:22.400  1296  6395 D BluetoothInputDevice: onBluetoothStateChange: up=true
,09-02 15:26:22.400  1296  1296 D BluetoothPbap: Proxy object connected
09-02 15:26:22.400  1296  1296 D PbapServerProfile: Bluetooth service connected
09-02 15:26:22.400  2850  2850 D BluetoothA2dp: Proxy object connected
,09-02 15:26:22.400  1019  1050 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothInputDevice
,09-02 15:26:22.400  1019  1050 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hid.HidService; callingUser = 0; userId(target) = 0
,09-02 15:26:22.400  1019  1050 W ActivityManager: userId = 0, bbcId = -10000
,09-02 15:26:22.400  1019  1050 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,09-02 15:26:22.400  1019  1050 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,09-02 15:26:22.400  1296  1296 D BluetoothInputDevice: Proxy object connected
,09-02 15:26:22.400  1296  1296 D HidProfile: Bluetooth service connected
,09-02 15:26:22.410  1019  1050 D BluetoothPan: Binding service...
,09-02 15:26:22.410  1019  1050 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothPan
,09-02 15:26:22.410  1019  1050 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pan.PanService; callingUser = 0; userId(target) = 0
,09-02 15:26:22.410  1019  1019 D BluetoothPan: BluetoothPAN Proxy object connected
,09-02 15:26:22.410  6906  6920 D BluetoothAdapter: onBluetoothStateChange: up=true
09-02 15:26:22.410  6906  6920 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,09-02 15:26:22.410  1296  1309 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,09-02 15:26:22.410  1019  1050 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
,09-02 15:26:22.410  1019  1050 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
09-02 15:26:22.410  1019  1050 W ActivityManager: userId = 0, bbcId = -10000
09-02 15:26:22.410  1019  1050 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-02 15:26:22.410  1019  1050 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,09-02 15:26:22.410  1296  1309 E BluetoothHeadset: BluetoothHeadset service is binded
,09-02 15:26:22.420  1460  1687 D BluetoothAdapter: onBluetoothStateChange: up=true
09-02 15:26:22.420  1460  1687 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
09-02 15:26:22.420  1296  1296 D HeadsetProfile: Bluetooth service connected
,09-02 15:26:22.420  2850  2858 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,09-02 15:26:22.420  1019  1050 D ActivityManager: bindService callerProcessName:com.samsung.android.providers.context, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
,09-02 15:26:22.420  1019  1050 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,09-02 15:26:22.420  1019  1050 W ActivityManager: userId = 0, bbcId = -10000
,09-02 15:26:22.420  1019  1050 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-02 15:26:22.420  1019  1050 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.android.providers.context, destAppInfo.processName = com.android.bluetooth
,09-02 15:26:22.420  2850  2858 E BluetoothHeadset: BluetoothHeadset service is binded
,09-02 15:26:22.420  1433  6854 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,09-02 15:26:22.420  1019  1050 D ActivityManager: bindService callerProcessName:com.android.server.telecom, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
,09-02 15:26:22.420  1019  1050 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,09-02 15:26:22.430  1019  1050 W ActivityManager: userId = 0, bbcId = -10000,
09-02 15:26:22.430  1019  1050 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-02 15:26:22.430  1019  1050 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.server.telecom, destAppInfo.processName = com.android.bluetooth
,09-02 15:26:22.430  1433  6854 E BluetoothHeadset: BluetoothHeadset service is binded
,09-02 15:26:22.430  1019  1050 D BluetoothA2dp: onBluetoothStateChange: up=true
,09-02 15:26:22.430  1019  1050 D BluetoothA2dp: doBind(): CallingUid(myUserHandle) = 0
09-02 15:26:22.430  1019  1050 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothA2dp
09-02 15:26:22.430  1019  1050 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
,09-02 15:26:22.430  1019  1019 D BluetoothA2dp: Proxy object connected
,09-02 15:26:22.430  1460  1476 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,09-02 15:26:22.430  1019  1050 D ActivityManager: bindService callerProcessName:com.android.phone, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
09-02 15:26:22.430  1019  1050 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,09-02 15:26:22.430  1019  1050 W ActivityManager: userId = 0, bbcId = -10000
09-02 15:26:22.430  1019  1050 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,09-02 15:26:22.430  1019  1050 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = com.android.bluetooth
09-02 15:26:22.430  1460  1476 E BluetoothHeadset: BluetoothHeadset service is binded
,09-02 15:26:22.430  1433  1451 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0,
09-02 15:26:22.430  1019  1050 D ActivityManager: bindService callerProcessName:com.android.server.telecom, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
09-02 15:26:22.430  1019  1050 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
09-02 15:26:22.430  1019  1050 W ActivityManager: userId = 0, bbcId = -10000
09-02 15:26:22.440  1019  1050 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,09-02 15:26:22.440  1019  1050 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.server.telecom, destAppInfo.processName = com.android.bluetooth
09-02 15:26:22.440  1433  1451 E BluetoothHeadset: BluetoothHeadset service is binded
,09-02 15:26:22.440  2850  2863 D BluetoothAdapter: onBluetoothStateChange: up=true
09-02 15:26:22.440  2850  2863 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,09-02 15:26:22.440  1296  1307 D BluetoothA2dp: onBluetoothStateChange: up=true
,09-02 15:26:22.440  1296  1307 D BluetoothA2dp: doBind(): CallingUid(myUserHandle) = 0
,09-02 15:26:22.440  1019  1050 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothA2dp
,09-02 15:26:22.440  1019  1050 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
,09-02 15:26:22.440  1019  1050 W ActivityManager: userId = 0, bbcId = -10000
,09-02 15:26:22.440  1019  1050 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-02 15:26:22.440  1019  1050 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,09-02 15:26:22.440  1296  1296 D BluetoothA2dp: Proxy object connected
09-02 15:26:22.440  1296  1296 D A2dpProfile: Bluetooth service connected
,09-02 15:26:22.440  1296  1309 D BluetoothMap: onBluetoothStateChange: up=true
,09-02 15:26:22.440  1019  1050 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothMap
09-02 15:26:22.440  1019  1050 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.map.BluetoothMapService; callingUser = 0; userId(target) = 0
,09-02 15:26:22.440  1019  1050 W ActivityManager: userId = 0, bbcId = -10000
09-02 15:26:22.440  1019  1050 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-02 15:26:22.440  1019  1050 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,09-02 15:26:22.450  1019  1050 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothGatt
09-02 15:26:22.450  1019  1050 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.gatt.GattService; callingUser = 0; userId(target) = -2
,09-02 15:26:22.450  1019  1019 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
,09-02 15:26:22.450  1019  1019 I InputMethodManagerService: [BT Setting State] State =12
,09-02 15:26:22.450  1019  1019 I InputMethodManagerService: [BT Setting off -> on] mBTKeyboardCount =0, KEYBOARD_BT(0)
,09-02 15:26:22.460  1182  1182 D BluetoothTile:  onBluetoothStateChange:
,09-02 15:26:22.460  1182  1182 D BluetoothTile:  onBluetoothPairedDevicesChanged:
,09-02 15:26:22.460  1182  1704 D BluetoothTile:  handleUpdatestate:false name:null
,09-02 15:26:22.460  1182  1704 D BluetoothTile:  handleUpdatestate:false name:null
,09-02 15:26:22.460  1182  1182 D BluetoothTile: onReceive : android.bluetooth.adapter.action.STATE_CHANGED
,09-02 15:26:22.460  1182  1182 D BluetoothTile:  getBluetoothState : 12
,09-02 15:26:22.460  1182  1704 D BluetoothTile:  handleUpdatestate:false name:null
,09-02 15:26:22.460  1433  1433 D BluetoothHeadset: registerListener : 11, listenercom.android.server.telecom.wearable.BluetoothMessageListener@283dbf2c, true
,09-02 15:26:22.470  1433  1433 D BluetoothHeadset: registerMessageListener
,09-02 15:26:22.470  1954  1954 I SamsungIME: STATE_CHANGED = 12, KEYBOARD_BT(0), mBTKeyboardCount =0
,09-02 15:26:22.470  1296  1296 V BluetoothEventManager: Received android.bluetooth.adapter.action.STATE_CHANGED
,09-02 15:26:22.470  1019  3214 D StatusBarManagerService: setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 ),
09-02 15:26:22.470  1019  2903 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=true
,09-02 15:26:22.470  1182  1182 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
,09-02 15:26:22.480  6212  6212 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-02 15:26:22.480  1019  3105 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
09-02 15:26:22.480  1019  3105 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.nearby.discovery.service.DiscoveryService; callingUser = 0; userId(target) = 0
,09-02 15:26:22.480  6906  6920 D HeadsetService: registerMessageListener
,09-02 15:26:22.480  6906  6920 D HeadsetService: registerMessageListener
,09-02 15:26:22.480  6906  6931 D HeadsetStateMachine: Disconnected process message: 70
09-02 15:26:22.480  6906  6931 D HeadsetStateMachine: processRegisterMessageListener : 11, com.samsung.bt.hfp.IMessageListener$Stub$Proxy@16075573
,09-02 15:26:22.480  1433  1433 I Telecom : BluetoothPhoneService: handleMessage(7) / param null
09-02 15:26:22.480  1433  1433 I Telecom : BluetoothPhoneService: updateHeadsetWithCallState
,09-02 15:26:22.480  1019  3105 W ActivityManager: userId = 0, bbcId = -10000
09-02 15:26:22.480  1019  3105 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-02 15:26:22.480  1019  3105 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-02 15:26:22.480  1433  1433 I Telecom : BluetoothPhoneService: getCurrentCallPhoneType, Defalut Phonetype : 1
09-02 15:26:22.490  1433  1433 I Telecom : BluetoothPhoneService: getCurrentCallPhoneType, Current Phonetype : 1
,09-02 15:26:22.490  1296  1296 W LocalBluetoothProfileManager: Warning: MAP profile was previously added but the UUID is now missing.
09-02 15:26:22.490  1433  1433 I Telecom : BluetoothPhoneService: updateHeadsetWithCallState numActive 0, numHeld 0, callState 6, ringing number [da39a3ee5e6b4b0d3255bfef95601890afd80709], ringing type 128
09-02 15:26:22.490  1296  1296 W LocalBluetoothProfileManager: Warning: PBAP profile was previously added but the UUID is now missing.
09-02 15:26:22.490  1296  1296 W LocalBluetoothProfileManager: Warning: SAP profile was previously added but the UUID is now missing.
,09-02 15:26:22.490  1296  1296 W LocalBluetoothProfileManager: Warning: HID profile was previously added but the UUID is now missing.
,09-02 15:26:22.490  6906  6931 D HeadsetStateMachine: Disconnected process message: 9
,09-02 15:26:22.490  6906  6931 D HeadsetStateMachine: mNumActive: 0 mNumHeld: 0 mCallState: 6,
,09-02 15:26:22.490  6906  6979 D BluetoothMapMasInstance: set MAP SDP message type : 1
,09-02 15:26:22.500   283   283 D audio_hw_primary: adev_set_parameters: enter: A2dpSuspended=false
09-02 15:26:22.500   283   283 V voice   : voice_set_parameters: enter: A2dpSuspended=false
09-02 15:26:22.500   283   283 V voice   : voice_set_parameters: exit with code(-2)
09-02 15:26:22.500   283   283 V msm8974_platform: platform_set_parameters: enter: A2dpSuspended=false
09-02 15:26:22.500   283   283 V msm8974_platform: platform_set_parameters: exit with code(-2)
09-02 15:26:22.500   283   283 D audio_hw_hfp: audio_extn_hfp_set_parameters: enter
09-02 15:26:22.500   283   283 V audio_hw_primary: adev_set_parameters: exit
,09-02 15:26:22.500  1296  1296 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,09-02 15:26:22.500  1019  3109 D ActivityManager: startService callerProcessName:com.android.settings, calleePkgName: com.android.settings
09-02 15:26:22.500  1019  3109 D ActivityManager: retrieveServiceLocked(): component = com.android.settings/com.android.settings.bluetooth.DockService; callingUser = 0; userId(target) = 0
,09-02 15:26:22.500  6906  6931 E HeadsetStateMachine: terminateScoUsingVirtualVoiceCall:No present call to terminate
09-02 15:26:22.500  1019  3109 W ActivityManager: userId = 0, bbcId = -10000
09-02 15:26:22.500  1019  3109 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-02 15:26:22.500  1019  3109 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.settings
,09-02 15:26:22.500  6906  6979 D BluetoothSocket: bindListen(): myUserId = 0
09-02 15:26:22.500  6906  6979 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-02 15:26:22.510  6906  6979 D BluetoothSocket: bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[76]}
09-02 15:26:22.510  6906  6979 D BluetoothSocket: bindListen(), new LocalSocket 
09-02 15:26:22.510  6906  6979 D BluetoothSocket: bindListen(), new LocalSocket.getInputStream() 
09-02 15:26:22.510  6906  6979 D BluetoothSocket: bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@271a9c30
,09-02 15:26:22.510  6906  6979 D BluetoothSocket: channel: 5
,09-02 15:26:22.510  1296  1296 D BluetoothMap: Proxy object connected
,09-02 15:26:22.510  1296  1296 D MapProfile: Bluetooth service connected
09-02 15:26:22.510  1296  1296 D BluetoothMap: getConnectedDevices()
,09-02 15:26:22.520  1296  1296 D DockEventReceiver: finishStartingService: stopping service
,09-02 15:26:22.520  1296  1296 D BluetoothNotiBroadcastReceiver: onReceive
,09-02 15:26:22.520  1182  1182 V BluetoothStatusReceiver: Received android.bluetooth.adapter.action.STATE_CHANGED
,09-02 15:26:22.520  1182  1182 D BluetoothStatusReceiver: AdapterStateChanged :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 12
,09-02 15:26:22.530  6906  6906 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@a523621
,09-02 15:26:22.530  6906  6906 D BtConfig.SecureMode: isSecureModeOn:false
,09-02 15:26:22.540  1019  1484 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
09-02 15:26:22.540  1019  1484 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.opp.BluetoothOppService; callingUser = 0; userId(target) = 0
,09-02 15:26:22.540  1019  1484 W ActivityManager: userId = 0, bbcId = -10000
09-02 15:26:22.540  1019  1484 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-02 15:26:22.540  1019  1484 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-02 15:26:22.560  1883  1883 D EasyUnlockReceiver: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.easyunlock.authorization.BluetoothStateChangeReceiver (has extras) }.
,09-02 15:26:22.560  1019  2905 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,09-02 15:26:22.560  1019  2905 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.easyunlock.authorization.InitializerIntentService; callingUser = 0; userId(target) = 0
,09-02 15:26:22.560  1019  2905 W ActivityManager: userId = 0, bbcId = -10000
,09-02 15:26:22.560  1019  2905 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,09-02 15:26:22.560  1019  2905 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-02 15:26:22.570  1019  3093 D SecContentProvider: uri = 4 selection = isProfileAuthorizedBySecurityPolicy
,09-02 15:26:22.570  1883  6988 D EasyUnlockInitService: Handling intent for initializer IntentService.
,09-02 15:26:22.580  1883  1883 D BtServices: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.proximity.BluetoothServicesAdapterStateChangeReceiver (has extras) }.
,09-02 15:26:22.580  1019  3214 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,09-02 15:26:22.580  6906  6989 D BluetoothSocket: bindListen(): myUserId = 0
09-02 15:26:22.580  6906  6989 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-02 15:26:22.590  1019  1048 D Tethering: interfaceAdded wlan0
,09-02 15:26:22.590  1019  1048 D Tethering: interfaceLinkStateChanged wlan0, false
09-02 15:26:22.590  1019  1048 D Tethering: interfaceStatusChanged wlan0, false
,09-02 15:26:22.590  1019  1139 E Tethering: No numeric data
,09-02 15:26:22.590  1019  3214 W ActivityManager: userId = 0, bbcId = -10000,
09-02 15:26:22.590  1019  3214 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,09-02 15:26:22.590  1019  3214 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
09-02 15:26:22.600  1019  1048 I Nat464Xlat: interfaceLinkStateChanged wlan0, false,
,09-02 15:26:22.600  1019  1139 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
,09-02 15:26:22.600  1019  1139 D Tethering: clearTetheredNotification()
09-02 15:26:22.600  1019  1139 D Tethering: InitialState.processMessage what=4
,09-02 15:26:22.600  1019  1048 D Tethering: interfaceAdded p2p0
,09-02 15:26:22.600  1019  1139 E Tethering: No numeric data
,09-02 15:26:22.600  6906  6989 D BluetoothSocket: bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[79]}
09-02 15:26:22.600  6906  6989 D BluetoothSocket: bindListen(), new LocalSocket 
09-02 15:26:22.600  6906  6989 D BluetoothSocket: bindListen(), new LocalSocket.getInputStream() 
09-02 15:26:22.600  6906  6989 D BluetoothSocket: bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@1f55573a
,09-02 15:26:22.600  6906  6989 D BluetoothSocket: channel: 12
09-02 15:26:22.600  6906  6989 I BtOppRfcommListener: Accept thread started.
,09-02 15:26:22.610  1019  1048 D Tethering: p2p0 is not a tetherable iface, ignoring
,09-02 15:26:22.610  1019  1129 D NtpTrustedTime: currentTimeMillis() cache hit
09-02 15:26:22.610  1019  1129 V NetworkStats: performPollLocked(flags=0x1)
09-02 15:26:22.610   278   998 I WifiHW  : wifi_change_fw_path(): fwpath = sta
09-02 15:26:22.610  1019  1129 D NetworkStatsFactory: UpdateStatsForKnox updated
09-02 15:26:22.610  1019  1129 D NetworkStatsFactory: UpdateStatsForKnox main else ---
09-02 15:26:22.610  1019  1048 D Tethering: interfaceLinkStateChanged p2p0, false
09-02 15:26:22.610  1019  1048 D Tethering: interfaceStatusChanged p2p0, false
09-02 15:26:22.610   278   998 D SoftapController: Softap fwReload - Ok
09-02 15:26:22.610  1019  1048 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
,09-02 15:26:22.610  1019  1129 V NetworkStats: performPollLocked() took 6ms
,09-02 15:26:22.610  1019  1129 D NtpTrustedTime: currentTimeMillis() cache hit
,09-02 15:26:22.620   278   998 D CommandListener: Setting iface cfg
09-02 15:26:22.620   278   998 D CommandListener: Trying to bring down wlan0
,09-02 15:26:22.620   278   998 D CommandListener: Clearing all IP addresses on wlan0
09-02 15:26:22.620  1182  1182 D HotspotTile: onReceive : android.net.conn.TETHER_STATE_CHANGED
09-02 15:26:22.620  1019  1139 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
09-02 15:26:22.620  1182  1182 D HotspotTile: updateTetherState():false, false
09-02 15:26:22.620  1019  1139 D Tethering: clearTetheredNotification()
,09-02 15:26:22.620  1019  1132 E WifiHW  : supplicant_name : p2p_supplicant
,09-02 15:26:22.630  1019  1129 V NetworkStats: performPollLocked(flags=0x1)
,09-02 15:26:22.630  1019  1129 D NtpTrustedTime: currentTimeMillis() cache hit
,09-02 15:26:22.630  1019  1129 D NetworkStatsFactory: UpdateStatsForKnox updated
,09-02 15:26:22.630  1019  1129 D NetworkStatsFactory: UpdateStatsForKnox main else ---
09-02 15:26:22.630  1019  1130 D NtpTrustedTime: currentTimeMillis() cache hit
,09-02 15:26:22.630  1019  1130 D NtpTrustedTime: currentTimeMillis() cache hit
09-02 15:26:22.630  1019  1132 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
,09-02 15:26:22.630  1182  1182 D HotspotTile: onReceive : android.net.conn.TETHER_STATE_CHANGED
09-02 15:26:22.630  1182  1182 D HotspotTile: updateTetherState():false, false
,09-02 15:26:22.630  1019  1129 D NtpTrustedTime: currentTimeMillis() cache hit
09-02 15:26:22.630  1019  1129 V NetworkStats: performPollLocked() took 5ms
,09-02 15:26:22.640  1182  1182 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x0/(null) mQSWifiIconId=0x0/(null) mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
09-02 15:26:22.640  1182  1182 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=false enabledDesc:null
09-02 15:26:22.640  1182  1182 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-02 15:26:22.640  1182  1182 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-02 15:26:22.640  1182  1182 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-02 15:26:22.640  1182  1182 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-02 15:26:22.640  1182  1182 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
09-02 15:26:22.640  1182  1182 D STATUSBAR-WifiQuickSettingButton: onReceive : android.net.wifi.WIFI_STATE_CHANGED
09-02 15:26:22.640  1182  1182 D STATUSBAR-WifiQuickSettingButton: Wifi onReceive(2)
09-02 15:26:22.640  1182  1704 D STATUSBAR-QSTileView: onStateChanged: Wi-Fi
,09-02 15:26:22.640  1182  1182 D HotspotTile: onReceive : 2, 0
,09-02 15:26:22.640  1296  1296 D WifiCredService: Action received :android.net.wifi.WIFI_STATE_CHANGED
,09-02 15:26:22.640  1019  1484 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,09-02 15:26:22.640  6212  6212 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-02 15:26:22.640  1019  1484 W ActivityManager: userId = 0, bbcId = -10000
,09-02 15:26:22.640  1019  1484 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,09-02 15:26:22.640  1019  1484 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-02 15:26:22.650  1019  1130 D NtpTrustedTime: currentTimeMillis() cache hit
09-02 15:26:22.650  1019  1130 D NtpTrustedTime: currentTimeMillis() cache hit
,09-02 15:26:22.650  1019  3214 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
09-02 15:26:22.650  1019  3214 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,09-02 15:26:22.650  1019  3214 W ActivityManager: userId = 0, bbcId = -10000
09-02 15:26:22.650  1019  3214 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,09-02 15:26:22.650  1019  3214 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,09-02 15:26:22.660  6993  6993 I wpa_supplicant: [wpa_supplicant_init]: use SECRIL,
09-02 15:26:22.660  6993  6993 I wpa_supplicant: Successfully initialized wpa_supplicant
09-02 15:26:22.660  6993  6993 I SecureStorage: [INFO]: SPID(0x00000000)Checking if this device supports Secure Storage,
,09-02 15:26:22.660  3631  3631 I Hs20UtilService: Starting #17
09-02 15:26:22.670  1883  6988 D EasyUnlockInitService: Not initializing EasyUnlock: remote_devices=0, bluetooth_on=true
09-02 15:26:22.670  3631  3649 I Hs20UtilService: Message received 5011
,09-02 15:26:22.670  6483  6483 D SecurityLogAgent: KnoxConfiguration : Current State = 1
09-02 15:26:22.670  6483  6483 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
09-02 15:26:22.670  6483  6483 D SecurityLogAgent: StateMachine : Current State = 1
09-02 15:26:22.670  6483  6483 D SecurityLogAgent: StateMachine : Changed Current State = 1
,09-02 15:26:22.680  6993  6993 I SecureStorage: [INFO]: SPID(0x00000000)This device supports Secure Storage
,09-02 15:26:22.680   409   409 I SecureStorage: [INFO]: SPID(0x00000003)Credentials: uid 1010, gid 1010, pid 6993
09-02 15:26:22.680   409   409 I SecureStorage: [INFO]: SPID(0x00000003)Received function mask & code: 0x0000010C
09-02 15:26:22.680  6993  6993 I SecureStorage: [INFO]: SPID(0x00000000)SS Daemon is running
09-02 15:26:22.680  6993  6993 I wpa_supplicant: ssSupport state is = 1
09-02 15:26:22.680  6993  6993 I wpa_supplicant: >>>>> GET KEY, IV <<<<<
09-02 15:26:22.680  6993  6993 I SecureStorage: [INFO]: SPID(0x00000000)Processing data
,09-02 15:26:22.680   409   409 I SecureStorage: [INFO]: SPID(0x00000003)Credentials: uid 1010, gid 1010, pid 6993
09-02 15:26:22.680   409   409 I SecureStorage: [INFO]: SPID(0x00000003)Received function mask & code: 0x00000106
,09-02 15:26:22.820   409   409 I SecureStorage: [INFO]: SPID(0x00000004)Secure Storage Daemon finished processing with result: 0,
,09-02 15:26:22.820  6993  6993 I SecureStorage: [INFO]: SPID(0x00000004)Processing data has been completed,
,09-02 15:26:22.890  6993  6993 I wpa_supplicant: Ctrl_iface: loading cred from phone,
09-02 15:26:22.890  6993  6993 I SecureStorage: [INFO]: SPID(0x00000004)Checking if this device supports Secure Storage
,09-02 15:26:22.900  6993  6993 I SecureStorage: [INFO]: SPID(0x00000004)This device supports Secure Storage,
09-02 15:26:22.900   409   409 I SecureStorage: [INFO]: SPID(0x00000004)Credentials: uid 1010, gid 1010, pid 6993
09-02 15:26:22.900   409   409 I SecureStorage: [INFO]: SPID(0x00000004)Received function mask & code: 0x0000010C
,09-02 15:26:22.900  6993  6993 I SecureStorage: [INFO]: SPID(0x00000004)SS Daemon is running
09-02 15:26:22.900  6993  6993 I wpa_supplicant: ssSupport state is = 1
09-02 15:26:22.900  6993  6993 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
09-02 15:26:22.900  6993  6993 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory,
09-02 15:26:22.900  6993  6993 E wpa_supplicant: SIM READ ERROR
09-02 15:26:22.900  6993  6993 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
09-02 15:26:22.900  6993  6993 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory,
09-02 15:26:22.900  6993  6993 E wpa_supplicant: SIM READ ERROR
09-02 15:26:22.900  6993  6993 I wpa_supplicant: Blacklist: Clear (all) 
09-02 15:26:22.900  6993  6993 I wpa_supplicant: wpa_default_ap_write_once,
09-02 15:26:22.900  6993  6993 I wpa_supplicant: There is no /data/misc/wifi/default_ap.check. Start copy default ap
09-02 15:26:22.900  6993  6993 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
09-02 15:26:22.900  6993  6993 E wpa_supplicant: getSavedIMSI cannot open /data/misc/wifi/.kmem: No such file or directory,
09-02 15:26:22.900  6993  6993 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
09-02 15:26:22.900  6993  6993 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
,09-02 15:26:22.900  6993  6993 I wpa_supplicant: rfkill: Cannot open RFKILL control device,
,09-02 15:26:22.900  1019  1048 D Tethering: interfaceLinkStateChanged wlan0, false
09-02 15:26:22.900  1019  1048 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
09-02 15:26:22.900  1019  1048 D Tethering: interfaceStatusChanged wlan0, false
,09-02 15:26:22.980  6993  6993 I wpa_supplicant: wlan0: Setting scan request: 0 sec 100000 usec,
,09-02 15:26:23.040   288   288 E SMD     : DCD OFF
,09-02 15:26:23.090  6993  6993 I wpa_supplicant: wlan0: State: DISCONNECTED -> DISCONNECTED
,09-02 15:26:23.090  6993  6993 I SecureStorage: [INFO]: SPID(0x00000004)Checking if this device supports Secure Storage
,09-02 15:26:23.100  6993  6993 I SecureStorage: [INFO]: SPID(0x00000004)This device supports Secure Storage
,09-02 15:26:23.100   409   409 I SecureStorage: [INFO]: SPID(0x00000004)Credentials: uid 1010, gid 1010, pid 6993
09-02 15:26:23.100   409   409 I SecureStorage: [INFO]: SPID(0x00000004)Received function mask & code: 0x0000010C
09-02 15:26:23.100  6993  6993 I SecureStorage: [INFO]: SPID(0x00000004)SS Daemon is running
09-02 15:26:23.100  6993  6993 I wpa_supplicant: ssSupport state is = 1,
09-02 15:26:23.100  6993  6993 I wpa_supplicant: Ctrl_iface: loading cred from phone
09-02 15:26:23.110  6993  6993 I SecureStorage: [INFO]: SPID(0x00000004)Checking if this device supports Secure Storage
,09-02 15:26:23.120  6993  6993 I SecureStorage: [INFO]: SPID(0x00000004)This device supports Secure Storage,
09-02 15:26:23.120   409   409 I SecureStorage: [INFO]: SPID(0x00000004)Credentials: uid 1010, gid 1010, pid 6993
,09-02 15:26:23.120   409   409 I SecureStorage: [INFO]: SPID(0x00000004)Received function mask & code: 0x0000010C
09-02 15:26:23.120  6993  6993 I SecureStorage: [INFO]: SPID(0x00000004)SS Daemon is running
09-02 15:26:23.120  6993  6993 I wpa_supplicant: ssSupport state is = 1
,09-02 15:26:23.120  6993  6993 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
09-02 15:26:23.120  6993  6993 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
09-02 15:26:23.120  6993  6993 E wpa_supplicant: SIM READ ERROR
09-02 15:26:23.120  6993  6993 I wpa_supplicant: wpa_default_ap_write_once,
09-02 15:26:23.120  6993  6993 I wpa_supplicant: There is no /data/misc/wifi/default_ap.check. Start copy default ap
09-02 15:26:23.120  6993  6993 I wpa_supplicant: rfkill: Cannot open RFKILL control device
09-02 15:26:23.120  1019  1048 D Tethering: interfaceLinkStateChanged p2p0, false
09-02 15:26:23.120  1019  1048 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
09-02 15:26:23.120  1019  1048 D Tethering: interfaceStatusChanged p2p0, false
,09-02 15:26:23.120  1019  1048 D Tethering: interfaceLinkStateChanged p2p0, false
09-02 15:26:23.120  1019  1048 D Tethering: interfaceStatusChanged p2p0, false
09-02 15:26:23.120  1019  1048 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
,09-02 15:26:23.220  6993  6993 I wpa_supplicant: p2p0: State: DISCONNECTED -> INACTIVE
09-02 15:26:23.220  6993  6993 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=-1 state=2 BSSID=00.00.00 SSID=
,09-02 15:26:23.340  6993  6993 I wpa_supplicant: p2p0: State: INACTIVE -> DISCONNECTED
,09-02 15:26:23.340  6993  6993 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=-1 state=0 BSSID=00.00.00 SSID=
09-02 15:26:23.340  6993  6993 I wpa_supplicant: Skip scan - bUseNetwork false
,09-02 15:26:23.350  1019  1132 E WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:2
09-02 15:26:23.350  1019  1132 D WifiNative-wlan0: callSECApiBoolean - ID [21]
,09-02 15:26:23.350  6993  6993 I wpa_supplicant: HOTSPOT20_ENABLE called
,09-02 15:26:23.350  6993  6993 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
09-02 15:26:23.350  6993  6993 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
09-02 15:26:23.350  6993  6993 E wpa_supplicant: SIM READ ERROR
09-02 15:26:23.350  6993  6993 I wpa_supplicant: Blacklist: Clear (all) 
,09-02 15:26:23.370  6993  6993 I wpa_supplicant: wlan0: Setting scan request: 0 sec 0 usec
,09-02 15:26:23.380  1019  1132 D WifiNative-wlan0: callSECApiInt - ID [210]
09-02 15:26:23.380  6993  6993 I wpa_supplicant: Skip scan - bUseNetwork false
,09-02 15:26:23.380  1182  1182 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
09-02 15:26:23.380  1182  1182 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
09-02 15:26:23.380  1182  1182 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-02 15:26:23.380  1182  1182 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-02 15:26:23.380  1182  1182 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-02 15:26:23.380  1182  1182 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-02 15:26:23.390  1182  1182 D STATUSBAR-WifiQuickSettingButton: onReceive : android.net.wifi.WIFI_STATE_CHANGED
09-02 15:26:23.390  1182  1182 D STATUSBAR-WifiQuickSettingButton: Wifi onReceive(3)
,09-02 15:26:23.390  1019  1132 D WifiConfigStore: Loading config and enabling all networks 
09-02 15:26:23.390  1182  1704 D STATUSBAR-QSTileView: onStateChanged: Wi-Fi
09-02 15:26:23.390  1182  1182 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
,09-02 15:26:23.390  1182  1182 D HotspotTile: onReceive : 3, 0
,09-02 15:26:23.400  1296  1296 D WifiCredService: Action received :android.net.wifi.WIFI_STATE_CHANGED
,09-02 15:26:23.400  6212  6212 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-02 15:26:23.400  6212  6212 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-02 15:26:23.400  6212  6212 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-02 15:26:23.400  6212  6212 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-02 15:26:23.400  6212  6212 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-02 15:26:23.400  6212  6212 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-02 15:26:23.400  6212  6212 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-02 15:26:23.400  6212  6212 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-02 15:26:23.400  6212  6212 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-02 15:26:23.410  1019  3214 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
09-02 15:26:23.410  1019  3214 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,09-02 15:26:23.410  1019  3214 W ActivityManager: userId = 0, bbcId = -10000
09-02 15:26:23.410  1019  1132 E WifiConfigStore: Not a HS20
09-02 15:26:23.410  1019  3214 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,09-02 15:26:23.410  1019  3214 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
09-02 15:26:23.410  1019  1132 E WifiConfigStore: Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
,09-02 15:26:23.410  3631  3631 I Hs20UtilService: Starting #18
,09-02 15:26:23.410  1019  1132 D WifiNative-wlan0: callSECApiInt - ID [65]
,09-02 15:26:23.410  3631  3649 I Hs20UtilService: Message received 5011
,09-02 15:26:23.410  1019  1132 D WifiNative-wlan0: callSECApiBoolean - ID [13]
09-02 15:26:23.410  6993  6993 I wpa_supplicant: USE_NETWORK : USE_NETWORK ON
09-02 15:26:23.410  6993  6993 I wpa_supplicant: wlan0: Setting scan request: 8 sec 0 usec
,09-02 15:26:23.410  6993  6993 I wpa_supplicant: reset timer : RESET_TIMER 0
09-02 15:26:23.410  6993  6993 I wpa_supplicant: P2P: Current p2p state = IDLE
09-02 15:26:23.410  6993  6993 I wpa_supplicant: wlan0: State: DISCONNECTED -> SCANNING
09-02 15:26:23.410  6993  6993 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00.00.00 SSID=
09-02 15:26:23.410  6993  6993 I wpa_supplicant: First Scan Start
,09-02 15:26:23.410  6993  6993 I wpa_supplicant: Scan requested (ret=0) - scan timeout 30 seconds
,09-02 15:26:23.420  6483  6483 D SecurityLogAgent: KnoxConfiguration : Current State = 1
09-02 15:26:23.420  6483  6483 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
09-02 15:26:23.420  6483  6483 D SecurityLogAgent: StateMachine : Current State = 1
09-02 15:26:23.420  6483  6483 D SecurityLogAgent: StateMachine : Changed Current State = 1
,09-02 15:26:23.420  1019  1132 D WifiNative-wlan0: Setting external_sim to 1
,09-02 15:26:23.420  1019  1132 D WifiStateMachine: Setting OUI to DA-A1-19
,09-02 15:26:23.420  1019  1132 I WifiNative-HAL: startHal
09-02 15:26:23.420  1019  1132 E wifi    : getStaticLongField sWifiHalHandle 0x9c84d88c
09-02 15:26:23.420  1019  1132 I WifiNative-HAL: Could not start hal
,09-02 15:26:23.430  1019  1132 E WifiNative-wlan0: do suspend true
09-02 15:26:23.430  6455  6455 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,09-02 15:26:23.430  1019  1131 D WifiP2pService: P2pDisabledState{ what=131203 }
,09-02 15:26:23.430   278   998 D CommandListener: Setting iface cfg
09-02 15:26:23.430   278   998 D CommandListener: Trying to bring up p2p0
,09-02 15:26:23.430  1019  1132 E WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:3
,09-02 15:26:23.430  1019  1131 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
09-02 15:26:23.430  1019  1019 D WifiScanningService: SCAN_AVAILABLE : 3
09-02 15:26:23.430  1019  1154 D WifiScanningService: DefaultState got{ when=0 what=160006 target=com.android.internal.util.StateMachine$SmHandler }
09-02 15:26:23.430  1019  1131 D WifiP2pService: P2pEnablingState
,09-02 15:26:23.430  1019  1154 I WifiNative-HAL: startHal
09-02 15:26:23.430  1019  1019 D RttService: SCAN_AVAILABLE : 3
,09-02 15:26:23.430  1019  1155 D RttService: DefaultState got{ when=0 what=160512 target=com.android.internal.util.StateMachine$SmHandler }
09-02 15:26:23.430  1019  1131 D WifiP2pService: P2pEnablingState{ what=147457 }
,09-02 15:26:23.430  1019  1131 D WifiP2pService: P2p socket connection successful
09-02 15:26:23.430  1019  1154 E wifi    : getStaticLongField sWifiHalHandle 0x9dd059bc
09-02 15:26:23.430  1019  1154 I WifiNative-HAL: Could not start hal
09-02 15:26:23.430  1019  1131 D WifiP2pService: P2pEnabledState
09-02 15:26:23.430  1019  1154 E WifiScanningService: could not start HAL
,09-02 15:26:23.430  1019  1132 E WifiStateMachine: DriverStatedState::CMD_SEC_STRING_API - inner msg [207]
09-02 15:26:23.430  1019  1132 D WifiNative-wlan0: callSECStringApiVoid - ID [215]
09-02 15:26:23.430  1019  1132 E WifiNative-wlan0: invaild command id : 215
,09-02 15:26:23.440  1019  1131 D WifiP2pService: sending p2p connection changed broadcast: DISCONNECTED
09-02 15:26:23.440  1019  1132 E WifiStateMachine: DriverStatedState::CMD_SEC_STRING_API - inner msg [207]
09-02 15:26:23.440  1019  1132 D WifiNative-wlan0: callSECStringApiVoid - ID [215]
09-02 15:26:23.440  1019  1132 E WifiNative-wlan0: invaild command id : 215
,09-02 15:26:23.440  1019  1138 E ConnectivityService: updateNetworkInfo()
,09-02 15:26:23.440  1019  1019 E WifiStateMachine: BroadcastReceiver : WIFI_P2P_STATE_CHANGED_ACTION is : android.net.wifi.p2p.STATE_CHANGED
,09-02 15:26:23.440  6993  6993 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=PL
09-02 15:26:23.440  1019  1051 D WifiDisplayController: Received WIFI_P2P_STATE_CHANGED_ACTION: enabled=true
09-02 15:26:23.440  1019  1051 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
09-02 15:26:23.440  1019  1051 D WifiDisplayController: disconnect
09-02 15:26:23.440  1019  1051 D WifiDisplayController: updateConnection
09-02 15:26:23.440  1019  1051 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
09-02 15:26:23.440  1019  1051 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,09-02 15:26:23.440  6993  6993 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=PL
,09-02 15:26:23.440  6993  6993 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=UNKNOWN
09-02 15:26:23.440  1182  1182 D AllShareCastTile: action: android.hardware.display.action.WIFI_DISPLAY_STATUS_CHANGED
09-02 15:26:23.440  1019  3105 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,09-02 15:26:23.440  1182  1182 D AllShareCastTile: wifi display status changed! scanstate : 0, ActiveDisplayState : 0
09-02 15:26:23.450  1019  1132 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
09-02 15:26:23.450  1019  1132 D SecContentProvider2: mCursor = null
,09-02 15:26:23.450  1019  1051 D WifiDisplayController: Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,09-02 15:26:23.450  1019  1051 D WifiDisplayAdapter: onP2pDisconnected
09-02 15:26:23.450  1019  1051 D IpRemoteDisplayController: disconnectWfdBridgeServer
09-02 15:26:23.450  1019  1051 D IpRemoteDisplayController: WfdBridgeServer is already null
,09-02 15:26:23.450  1019  1131 D WifiNative-p2p0: p2pGetDeviceAddress
09-02 15:26:23.450  1019  1131 D WifiNative-p2p0: p2pGetDeviceAddress returning 7e:f9:0e:37:96:ac
,09-02 15:26:23.450  1019  1131 D WifiP2pService: DeviceAddress: 7e:96:ac
,09-02 15:26:23.450  1019  1132 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
09-02 15:26:23.450  1019  1132 D SecContentProvider2: mCursor = null
,09-02 15:26:23.460  1296  1296 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.p2p.CONNECTION_STATE_CHANGE
09-02 15:26:23.460  1296  1296 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
,09-02 15:26:23.460  1296  1296 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,09-02 15:26:23.460  1019  1051 D WifiDisplayController: Received WIFI_P2P_THIS_DEVICE_CHANGED_ACTION: mThisDevice= Device: A5-1
09-02 15:26:23.460  1019  1051 D WifiDisplayController:  deviceAddress: 7e:f9:0e:37:96:ac
09-02 15:26:23.460  1019  1051 D WifiDisplayController:  primary type: 10-0050F204-5
09-02 15:26:23.460  1019  1051 D WifiDisplayController:  secondary type: null
09-02 15:26:23.460  1019  1051 D WifiDisplayController:  wps: 0
09-02 15:26:23.460  1019  1051 D WifiDisplayController:  grpcapab: 0
09-02 15:26:23.460  1019  1051 D WifiDisplayController:  devcapab: 0
09-02 15:26:23.460  1019  1051 D WifiDisplayController:  status: 3
09-02 15:26:23.460  1019  1051 D WifiDisplayController:  wfdInfo: null
09-02 15:26:23.460  1019  1051 D WifiDisplayController:  groupownerAddress: null
09-02 15:26:23.460  1019  1051 D WifiDisplayController:  GOdeviceName: null
09-02 15:26:23.460  1019  1051 D WifiDisplayController:  interfaceAddress: 
09-02 15:26:23.460  1019  1051 D WifiDisplayController:  SConnectInfo : null
,09-02 15:26:23.460  1296  1296 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
09-02 15:26:23.460  1296  1296 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
09-02 15:26:23.460  1296  1296 I NearbySettings: MountReceiver.onReceive - Set preference state off
,09-02 15:26:23.460  6425  6425 D FileShare-Client: ClientBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
09-02 15:26:23.460  1296  3038 V NearbySettings: MountReceiver.mPrefHandler - 7002
,09-02 15:26:23.460  6425  6425 D FileShare-Client: ClientBroadcastReceiver.onReceive - disconnected
,09-02 15:26:23.460  6425  6425 D FileShare-Client: Outbound.stopDelayTimer - 
,09-02 15:26:23.470  6440  6440 D FileShare-Server: ServerBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,09-02 15:26:23.480  1019  1131 D WifiP2pService: sending p2p persistent groups changed broadcast
,09-02 15:26:23.480  1019  1131 D WifiP2pService: InactiveState
,09-02 15:26:23.480  1019  1131 D WifiP2pService: InactiveState{ what=143376 }
,09-02 15:26:23.480  1019  1131 D WifiP2pService: P2pEnabledState{ what=143376 }
09-02 15:26:23.480  6993  6993 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=PL
,09-02 15:26:23.480  1019  1131 D WifiP2pService: InactiveState{ what=143376 }
,09-02 15:26:23.480  1019  1131 D WifiP2pService: P2pEnabledState{ what=143376 }
,09-02 15:26:23.590  1019  1048 D Tethering: interfaceLinkStateChanged p2p0, false
,09-02 15:26:23.590  1019  1048 D Tethering: interfaceStatusChanged p2p0, false
,09-02 15:26:23.590  1019  1048 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
,09-02 15:26:24.240  6212  6266 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-02 15:26:24.240  6212  6266 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-02 15:26:24.240  6212  6266 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-02 15:26:24.240  6212  6266 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-02 15:26:24.240  6212  6266 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-02 15:26:24.240  6212  6266 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-02 15:26:24.240  6212  6266 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-02 15:26:24.240  6212  6266 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-02 15:26:24.240  6212  6266 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-02 15:26:24.250  6212  6266 D io.jxcore.node.LifeCycleMonitor: onActivityCreated: Bundle[{}]
,09-02 15:26:24.250  6212  6266 D io.jxcore.node.LifeCycleMonitor: onActivityResumed
,09-02 15:26:24.250  6212  6266 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@963e991 Bundle[{}]
,09-02 15:26:24.250  6212  6266 I io.jxcore.node.LifeCycleMonitor: start: OK
,09-02 15:26:24.250  6212  6266 I io.jxcore.node.LifeCycleMonitor: stop: OK
,09-02 15:26:24.250  6212  6266 D io.jxcore.node.LifeCycleMonitor: onActivityStarted
,09-02 15:26:24.250  6212  6266 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
,09-02 15:26:24.250  6212  6266 D io.jxcore.node.LifeCycleMonitor: onActivityDestroyed
,09-02 15:26:24.260  6212  6266 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
,09-02 15:26:24.260  6212  6266 I System.out: Running OutgoingSocketThread
,09-02 15:26:24.260  6212  7003 D io.jxcore.node.OutgoingSocketThread: Entering thread (ID: 1167)
,09-02 15:26:24.270  6212  7003 D io.jxcore.node.OutgoingSocketThread: Server socket local port: 41405
,09-02 15:26:24.270  6212  7003 I io.jxcore.node.OutgoingSocketThread: Now accepting connections...
,09-02 15:26:24.490  6993  6993 I wpa_supplicant: nl80211: Received scan results (20 BSSes),
,09-02 15:26:24.490  6993  6993 I wpa_supplicant: wlan0: Setting scan request: 8 sec 0 usec
,09-02 15:26:24.490  1019  6998 D WifiMonitor: didn't find BSSID Trying to associate with SSID 'NG700',
,09-02 15:26:24.490  6993  6993 I wpa_supplicant: Trying to associate with SSID '4E47373030'
,09-02 15:26:24.490  6993  6993 I wpa_supplicant: Trying to associate with  'G700'
09-02 15:26:24.490  6993  6993 I wpa_supplicant: wlan0: State: SCANNING -> ASSOCIATING
,09-02 15:26:24.500  6993  6993 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=5 BSSID=00.00.00 SSID=4E47373030
,09-02 15:26:24.510  1019  1132 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
,09-02 15:26:24.510  1019  1132 D SecContentProvider2: mCursor = null
,09-02 15:26:24.580  1019  1053 I PowerManagerService: [PWL] Off : 75s ago
09-02 15:26:24.580  1019  1053 I PowerManagerService: [PWL]   PowerManagerService.WakeLocks: ref count=1
09-02 15:26:24.580  1019  1053 I PowerManagerService: [PWL]     mWakeLockSummary : 0x1
09-02 15:26:24.580  1019  1053 I PowerManagerService: [PWL]       PARTIAL_WAKE_LOCK              'ConnectivityService' (uid=1000, pid=1019, ws=null) (elapsedTime=19827)
09-02 15:26:24.580  1019  1053 I PowerManagerService: [PWL]       PARTIAL_WAKE_LOCK              'bluedroid_timer' (uid=1002, pid=6906, ws=null) (elapsedTime=2600)
09-02 15:26:24.580  1019  1053 I PowerManagerService: [PWL]       PARTIAL_WAKE_LOCK              'AudioMix' (uid=1013, pid=0, ws=null) (elapsedTime=2085)
09-02 15:26:24.580  1019  1053 I PowerManagerService: [PWL]       PARTIAL_WAKE_LOCK              'AudioMix' (uid=1013, pid=0, ws=null) (elapsedTime=2084)
,09-02 15:26:24.610  6993  6993 E wpa_supplicant: Cmd 35605 not handled
,09-02 15:26:24.620  1019  1048 D Tethering: interfaceLinkStateChanged wlan0, false
09-02 15:26:24.620  1019  1048 D Tethering: interfaceStatusChanged wlan0, false
09-02 15:26:24.620  6993  6993 I wpa_supplicant: wlan0: State: ASSOCIATING -> ASSOCIATED
09-02 15:26:24.620  6993  6993 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00.00.00 SSID=4E47373030
09-02 15:26:24.620  6993  6993 I wpa_supplicant: Associated with F4.99.3E
09-02 15:26:24.620  1019  1048 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
09-02 15:26:24.620  6993  6993 I wpa_supplicant: wlan0: RX EAPOL from f4:f2:6d:22:99:3e
09-02 15:26:24.620  6993  6993 I wpa_supplicant: wlan0: State: ASSOCIATED -> 4WAY_HANDSHAKE
09-02 15:26:24.620  6993  6993 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=F4.99.3E SSID=4E47373030
,09-02 15:26:24.620  1019  1048 D Tethering: interfaceLinkStateChanged wlan0, false
09-02 15:26:24.620  1019  1048 D Tethering: interfaceStatusChanged wlan0, false
09-02 15:26:24.620  1019  1048 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
,09-02 15:26:24.620  1019  1048 D Tethering: interfaceLinkStateChanged wlan0, false
,09-02 15:26:24.620  1019  1048 D Tethering: interfaceStatusChanged wlan0, false
,09-02 15:26:24.620  1019  1048 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
,09-02 15:26:24.620  1019  1048 D Tethering: interfaceLinkStateChanged wlan0, true
,09-02 15:26:24.620  1019  1048 D Tethering: interfaceStatusChanged wlan0, true
,09-02 15:26:24.630  1019  1132 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
09-02 15:26:24.630  1019  1132 D SecContentProvider2: mCursor = null
,09-02 15:26:24.630  1019  1139 E Tethering: No numeric data
,09-02 15:26:24.630  1019  1048 I Nat464Xlat: interfaceLinkStateChanged wlan0, true
,09-02 15:26:24.630  1019  1132 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
09-02 15:26:24.630  1019  1132 D SecContentProvider2: mCursor = null
,09-02 15:26:24.630  1019  1139 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
,09-02 15:26:24.630  1019  1139 D Tethering: clearTetheredNotification()
,09-02 15:26:24.630  1019  1129 V NetworkStats: performPollLocked(flags=0x1)
,09-02 15:26:24.640  1019  1129 D NtpTrustedTime: currentTimeMillis() cache hit
,09-02 15:26:24.640  1019  1129 D NetworkStatsFactory: UpdateStatsForKnox updated
09-02 15:26:24.640  1182  1182 D HotspotTile: onReceive : android.net.conn.TETHER_STATE_CHANGED
09-02 15:26:24.640  1019  1129 D NetworkStatsFactory: UpdateStatsForKnox main else ---
,09-02 15:26:24.640  1182  1182 D HotspotTile: updateTetherState():false, false
,09-02 15:26:24.640  1019  1129 V NetworkStats: performPollLocked() took 6ms
,09-02 15:26:24.640  1019  1129 D NtpTrustedTime: currentTimeMillis() cache hit
,09-02 15:26:24.640  1019  1130 D NtpTrustedTime: currentTimeMillis() cache hit
09-02 15:26:24.640  1019  1130 D NtpTrustedTime: currentTimeMillis() cache hit
09-02 15:26:24.640  6993  6993 I wpa_supplicant: wlan0: RX EAPOL from f4:f2:6d:22:99:3e
,09-02 15:26:24.640  6993  6993 I wpa_supplicant: wlan0: State: 4WAY_HANDSHAKE -> 4WAY_HANDSHAKE
,09-02 15:26:24.650  6993  6993 I wpa_supplicant: wlan0: State: 4WAY_HANDSHAKE -> GROUP_HANDSHAKE
09-02 15:26:24.650  6993  6993 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=F4.99.3E SSID=4E47373030
,09-02 15:26:24.650  6993  6993 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
09-02 15:26:24.650  6993  6993 I wpa_supplicant: wlan0: State: GROUP_HANDSHAKE -> COMPLETED,
09-02 15:26:24.650  6993  6993 I wpa_supplicant: CTRL-EVENT-CONNECTED - Connection to F4.99.3E completed (auth) [id=0 id_str=]
09-02 15:26:24.650  1019  1048 I Nat464Xlat: interfaceLinkStateChanged wlan0, true
09-02 15:26:24.650  6993  6993 I wpa_supplicant: Blacklist: Clear (temp) 
09-02 15:26:24.650  6993  6993 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=F4.99.3E SSID=4E47373030
09-02 15:26:24.650  1019  1048 D Tethering: interfaceLinkStateChanged wlan0, true
09-02 15:26:24.650  1019  1048 D Tethering: interfaceStatusChanged wlan0, true
,09-02 15:26:24.650  1019  1132 D WifiNative-wlan0: callSECApiVoid - ID [50]
,09-02 15:26:24.660  1019  1132 E WifiConfigStore: setLastSelectedConfiguration -1
,09-02 15:26:24.660  1182  1182 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
09-02 15:26:24.660  1182  1182 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
09-02 15:26:24.660  1182  1182 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-02 15:26:24.660  1182  1182 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-02 15:26:24.660  1182  1182 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-02 15:26:24.660  1182  1182 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-02 15:26:24.660  1019  1132 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{false} explicitlySelected{false} }
,09-02 15:26:24.670  1019  1138 D ConnectivityService: hsengiv:checkWhatTypeOfNetwork and the value is false
09-02 15:26:24.670  1019  1138 E ConnectivityService: updateNetworkInfo()
09-02 15:26:24.670  1019  1138 D ConnectivityService: NetworkAgentInfo [WIFI () - 503] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
,09-02 15:26:24.670  1019  1132 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,09-02 15:26:24.670  1019  1223 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
,09-02 15:26:24.670  1019  1223 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,09-02 15:26:24.670  1019  1223 W ActivityManager: userId = 0, bbcId = -10000
,09-02 15:26:24.670  1019  1223 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-02 15:26:24.670  1019  1223 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,09-02 15:26:24.680  3631  3631 I Hs20UtilService: Starting #19
09-02 15:26:24.680  1019  1132 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,09-02 15:26:24.680  3631  3649 I Hs20UtilService: Message received 5007
,09-02 15:26:24.680  1296  1296 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,09-02 15:26:24.680  1296  1296 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
,09-02 15:26:24.680  1296  1296 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,09-02 15:26:24.680  1296  1296 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
,09-02 15:26:24.680  1296  1296 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
09-02 15:26:24.680  1296  1296 I NearbySettings: MountReceiver.onReceive - Set preference state off
,09-02 15:26:24.680  1296  3038 V NearbySettings: MountReceiver.mPrefHandler - 7002
,09-02 15:26:24.690   278   998 D CommandListener: Setting iface cfg
,09-02 15:26:24.690  1019  1132 E WifiStateMachine: Start Dhcp Watchdog 2
,09-02 15:26:24.690  1019  1132 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
,09-02 15:26:24.690  1019  1132 D SecContentProvider2: mCursor = null
,09-02 15:26:24.700  1182  1182 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,09-02 15:26:24.700  1182  1182 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
,09-02 15:26:24.700  1182  1182 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-02 15:26:24.700  1182  1182 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-02 15:26:24.700  1182  1182 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-02 15:26:24.700  1182  1182 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-02 15:26:24.710  1019  1132 E WifiNative-wlan0: do suspend false
,09-02 15:26:24.710  1019  1131 D WifiP2pService: InactiveState{ what=143375 }
,09-02 15:26:24.710  1019  1131 D WifiP2pService: P2pEnabledState{ what=143375 }
09-02 15:26:24.710  1019  1132 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
09-02 15:26:24.710  1019  1132 D SecContentProvider2: mCursor = null
,09-02 15:26:24.930  7006  7006 E dhcpcd  : fopen `/system/etc/dhcpcd/dhcpcd.conf': No such file or directory
09-02 15:26:24.930  7006  7006 I dhcpcd  : version 5.5.6 starting
09-02 15:26:24.940  7006  7006 E dhcpcd  : fopen `/system/etc/dhcpcd/dhcpcd.conf': No such file or directory
,09-02 15:26:24.990  7006  7006 I dhcpcd  : wlan0: sending IPv6 Router Solicitation,
09-02 15:26:24.990  7006  7006 E dhcpcd  : wlan0: sendmsg: Cannot assign requested address
09-02 15:26:24.990  7006  7006 I dhcpcd  : if(wlan0) info get Success. (MAC : F4.99.3E)
09-02 15:26:24.990  7006  7006 I dhcpcd  : bssid match
09-02 15:26:24.990  7006  7006 I dhcpcd  : wlan0: rebinding lease of 192.168.1.111
,09-02 15:26:25.080  7006  7006 I dhcpcd  : wlan0: acknowledged 192.168.1.111 from 192.168.1.1,
,09-02 15:26:25.160  7006  7006 I dhcpcd  : wlan0: leased 192.168.1.111 for 172800 seconds,
,09-02 15:26:25.260  6212  6266 I io.jxcore.node.OutgoingSocketThread: close (thread ID: 1168)
09-02 15:26:25.260  6212  6266 I io.jxcore.node.OutgoingSocketThread: close: Complete (thread ID: 1168)
,09-02 15:26:25.270  6212  6266 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 1173)
,09-02 15:26:25.270  6212  6266 V io.jxcore.node.SocketThreadBase: close: Closing the localhost socket...,
09-02 15:26:25.270  6212  6266 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 1174)
,09-02 15:26:25.270  6212  6266 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded,
09-02 15:26:25.270  6212  6266 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@fa085fb added. We now have 2 listener(s)
,09-02 15:26:25.270  6212  6266 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "7C:F9:0E:37:96:AB"
09-02 15:26:25.270  6212  6266 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,09-02 15:26:25.270  6212  6266 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-02 15:26:25.270  6212  6266 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-02 15:26:25.270  6212  6266 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2b4db618 added. We now have 9 listener(s)
09-02 15:26:25.270  6212  6266 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-02 15:26:25.270  6212  6266 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-02 15:26:25.280  6212  6266 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-02 15:26:25.280  6212  6266 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:,
09-02 15:26:25.280  6212  6266 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-02 15:26:25.280  6212  6266 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-02 15:26:25.280  6212  6266 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-02 15:26:25.280  6212  6266 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-02 15:26:25.280  6212  6266 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-02 15:26:25.280  6212  6266 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-02 15:26:25.280  6212  6266 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-02 15:26:25.280  6212  6266 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-02 15:26:25.280  6212  6266 D io.jxcore.node.ConnectivityMonitor: start: OK
09-02 15:26:25.280  6212  6266 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-02 15:26:25.280  6212  6266 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1763656 added. We now have 3 listener(s)
09-02 15:26:25.280  6212  6212 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-02 15:26:25.290  6212  6212 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-02 15:26:25.290  6212  6266 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "7C:F9:0E:37:96:AB"
09-02 15:26:25.290  6212  6266 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-02 15:26:25.290  6212  6266 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-02 15:26:25.290  6212  6266 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded,
09-02 15:26:25.290  6212  6266 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6786d7 added. We now have 10 listener(s)
09-02 15:26:25.290  6212  6266 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-02 15:26:25.290  6212  6266 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-02 15:26:25.290  6212  6266 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-02 15:26:25.290  6212  6266 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-02 15:26:25.290  6212  6266 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-02 15:26:25.290  6212  6266 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 15:26:25.290  6212  6266 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-02 15:26:25.290  6212  6266 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-02 15:26:25.290  6212  6266 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@fa085fb removed from the list
,09-02 15:26:25.290  6212  6266 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-02 15:26:25.290  6212  6266 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2b4db618 removed from the list
09-02 15:26:25.290  6212  6266 D io.jxcore.node.ConnectivityMonitor: stop
09-02 15:26:25.290  6212  6266 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-02 15:26:25.290  6212  6266 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 15:26:25.290  6212  6266 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-02 15:26:25.290  6212  6266 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-02 15:26:25.290  6212  6266 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-02 15:26:25.290  6212  6266 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-02 15:26:25.290  6212  6266 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2b4db618 not in the list
09-02 15:26:25.290  6212  6266 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 15:26:25.290  6212  6266 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-02 15:26:25.290  6212  6266 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,09-02 15:26:25.290  6212  6266 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-02 15:26:25.290  6212  6266 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-02 15:26:25.290  6212  6266 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6786d7 removed from the list,
09-02 15:26:25.290  6212  6266 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-02 15:26:25.290  6212  6266 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 15:26:25.290  6212  6266 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-02 15:26:25.290  6212  6266 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,09-02 15:26:25.290  6212  6266 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1763656 removed from the list
09-02 15:26:25.290  6212  6266 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-02 15:26:25.290  6212  6266 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@18741bc4 added. We now have 2 listener(s)
,09-02 15:26:25.300  6212  6266 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "7C:F9:0E:37:96:AB"
09-02 15:26:25.300  6212  6266 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-02 15:26:25.300  6212  6266 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-02 15:26:25.300  6212  6266 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-02 15:26:25.300  6212  6266 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@77dbaad added. We now have 9 listener(s)
09-02 15:26:25.300  6212  6266 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-02 15:26:25.300  6212  6266 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-02 15:26:25.310  6212  6266 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-02 15:26:25.310  6212  6266 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-02 15:26:25.310  6212  6266 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
,09-02 15:26:25.310  6212  6266 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-02 15:26:25.310  6212  6266 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-02 15:26:25.310  6212  6266 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-02 15:26:25.310  6212  6266 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-02 15:26:25.310  6212  6266 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-02 15:26:25.310  6212  6266 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-02 15:26:25.320  6212  6266 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-02 15:26:25.320  6212  6266 D io.jxcore.node.ConnectivityMonitor: start: OK
09-02 15:26:25.320  6212  6266 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,09-02 15:26:25.320  6212  6266 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@433b973 added. We now have 3 listener(s)
,09-02 15:26:25.320  6212  6212 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-02 15:26:25.320  6212  6212 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-02 15:26:25.320  6212  6266 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "7C:F9:0E:37:96:AB"
09-02 15:26:25.320  6212  6266 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-02 15:26:25.320  6212  6266 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-02 15:26:25.320  6212  6266 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-02 15:26:25.320  6212  6266 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2e793030 added. We now have 10 listener(s)
09-02 15:26:25.320  6212  6266 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-02 15:26:25.320  6212  6266 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-02 15:26:25.320  6212  6266 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-02 15:26:25.320  6212  6266 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-02 15:26:25.320  6212  6266 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-02 15:26:25.320  6212  6266 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,09-02 15:26:25.330  6212  6266 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,09-02 15:26:25.340  6212  6266 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,09-02 15:26:25.340  6212  6266 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,09-02 15:26:25.340  6212  6266 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,09-02 15:26:25.340  6212  6266 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
09-02 15:26:25.340  6212  6266 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
09-02 15:26:25.340  6906  6920 D BtGatt.GattService: registerClient() - UUID=565ffb10-d299-493a-bf15-50c3b0fb3772
,09-02 15:26:25.390  6906  6924 D BtGatt.GattService: onClientRegistered() - UUID=565ffb10-d299-493a-bf15-50c3b0fb3772, clientIf=6,
09-02 15:26:25.390  6212  6221 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=6
09-02 15:26:25.390  6906  6964 D BtGatt.GattService: start scan with filters
,09-02 15:26:25.390  6212  6266 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
09-02 15:26:25.390  6212  6266 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
09-02 15:26:25.390  6212  6266 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
09-02 15:26:25.390  6212  6266 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,09-02 15:26:25.390  6906  6928 D BtGatt.ScanManager: handling starting scan
09-02 15:26:25.390  6906  6928 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@a523621
09-02 15:26:25.390  6212  6266 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,09-02 15:26:25.390  6212  6266 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
09-02 15:26:25.390  6212  6212 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false,
09-02 15:26:25.390  6906  6924 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=6, status=0, action=1,
,09-02 15:26:25.390  6906  6924 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
09-02 15:26:25.390  6906  6928 D BtGatt.ScanManager: allow scan with filters
09-02 15:26:25.390  6906  6928 D BtGatt.ScanManager: client filter size is = 1available filters are = 13
09-02 15:26:25.390  6906  6928 D BtGatt.ScanManager: set filter index= 3 for clientIf= 6
,09-02 15:26:25.390  6212  6266 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,09-02 15:26:25.400  6906  6924 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=0, availableSpace=15
09-02 15:26:25.400  6906  6924 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,09-02 15:26:25.400  6906  6928 D BtGatt.ScanManager: Starting BLE batch scan
,09-02 15:26:25.400  6906  6928 D BtGatt.ScanManager: configuring batch scan storage, appIf 6
09-02 15:26:25.400  6906  6924 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=6, status=0
09-02 15:26:25.400  6906  6924 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,09-02 15:26:25.400  6212  6266 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
,09-02 15:26:25.400  6212  6266 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
,09-02 15:26:25.400  6212  6266 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
,09-02 15:26:25.400  6212  6266 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 15:26:25.400  6212  6266 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-02 15:26:25.400  6212  6266 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
09-02 15:26:25.400  6212  6266 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-02 15:26:25.400  6212  6266 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-02 15:26:25.400  6212  6266 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,09-02 15:26:25.400  6212  6266 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-02 15:26:25.400  6212  6266 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,09-02 15:26:25.400  6906  6924 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=1
,09-02 15:26:25.400  6906  6924 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,09-02 15:26:25.410  6906  6964 D BtGatt.GattService: stopScan() - queue size =1
,09-02 15:26:25.410  6906  6914 D BtGatt.GattService: unregisterClient() - clientIf=6
,09-02 15:26:25.410  6212  6266 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,09-02 15:26:25.410  6212  6266 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
09-02 15:26:25.410  6212  6266 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
,09-02 15:26:25.410  6212  6266 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
09-02 15:26:25.410  6212  6266 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,09-02 15:26:25.420  6212  6266 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,09-02 15:26:25.420  6212  6266 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,09-02 15:26:25.420  6212  6266 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
,09-02 15:26:25.420  6212  6266 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,09-02 15:26:25.420  6212  6266 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-02 15:26:25.420  6212  6212 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,09-02 15:26:25.420  6212  6212 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-02 15:26:25.420  6212  6212 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,09-02 15:26:25.420  6212  6266 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-02 15:26:25.420  6212  6266 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-02 15:26:25.420  6212  6266 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-02 15:26:25.420  6212  6266 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-02 15:26:25.420  6212  6266 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 15:26:25.420  6212  6266 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-02 15:26:25.420  6212  6266 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-02 15:26:25.420  6212  6266 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@18741bc4 removed from the list
09-02 15:26:25.420  6212  6266 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-02 15:26:25.420  6212  6266 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@77dbaad removed from the list
09-02 15:26:25.420  6212  6266 D io.jxcore.node.ConnectivityMonitor: stop
09-02 15:26:25.420  6212  6266 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-02 15:26:25.420  6212  6266 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 15:26:25.420  6212  6266 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-02 15:26:25.420  6212  6266 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-02 15:26:25.420  6212  6266 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-02 15:26:25.420  6212  6266 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-02 15:26:25.420  6212  6266 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@77dbaad not in the list
09-02 15:26:25.420  6212  6266 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 15:26:25.420  6212  6266 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-02 15:26:25.430  6212  6266 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-02 15:26:25.430  6212  6266 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-02 15:26:25.430  6212  6266 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-02 15:26:25.430  6212  6266 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2e793030 removed from the list
09-02 15:26:25.430  6212  6266 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-02 15:26:25.430  6212  6266 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 15:26:25.430  6212  6266 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-02 15:26:25.430  6212  6266 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-02 15:26:25.430  6212  6266 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@433b973 removed from the list
,09-02 15:26:25.430  6212  6266 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-02 15:26:25.430  6212  6266 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c791f5c added. We now have 2 listener(s)
,09-02 15:26:25.430  6212  6266 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "7C:F9:0E:37:96:AB"
09-02 15:26:25.430  6212  6266 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-02 15:26:25.430  6212  6266 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-02 15:26:25.430  6212  6266 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-02 15:26:25.430  6212  6266 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@14489265 added. We now have 9 listener(s)
09-02 15:26:25.430  6212  6266 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-02 15:26:25.430  6212  6266 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-02 15:26:25.440  6212  6266 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-02 15:26:25.440  6212  6266 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-02 15:26:25.440  6212  6266 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-02 15:26:25.440  6212  6266 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-02 15:26:25.440  6212  6266 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-02 15:26:25.440  6212  6266 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-02 15:26:25.440  6212  6266 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-02 15:26:25.440  6212  6266 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-02 15:26:25.440  6212  6266 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-02 15:26:25.440  6212  6266 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-02 15:26:25.440  6212  6266 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-02 15:26:25.440  6212  6266 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-02 15:26:25.440  6212  6266 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3b9ae3eb added. We now have 3 listener(s)
,09-02 15:26:25.440  6212  6212 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-02 15:26:25.450  6212  6212 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-02 15:26:25.450  6212  6266 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "7C:F9:0E:37:96:AB"
09-02 15:26:25.450  6212  6266 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-02 15:26:25.450  6212  6266 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-02 15:26:25.450  6212  6266 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,09-02 15:26:25.450  6212  6266 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@526d548 added. We now have 10 listener(s)
09-02 15:26:25.450  6212  6266 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-02 15:26:25.450  6212  6266 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
,09-02 15:26:25.450  6212  6266 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-02 15:26:25.450  6212  6266 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-02 15:26:25.450  6212  6266 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-02 15:26:25.450  6212  6266 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-02 15:26:25.450  6212  6266 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,09-02 15:26:25.450  6906  6928 D BtGatt.ScanManager: 1. app : com.android.bluetooth 2. Action : LESC 3. Callng app : com.test.thalitest 4. Count : 21
,09-02 15:26:25.450  6212  6266 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,09-02 15:26:25.450  6906  6928 D BtGatt.ScanManager: filter size is 1
,09-02 15:26:25.450  6906  6928 D BtGatt.ScanManager: delete FilterIndex - 3
,09-02 15:26:25.460  6906  6924 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=1, availableSpace=16
09-02 15:26:25.460  6906  6924 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
09-02 15:26:25.460  6906  6928 D BtGatt.ScanManager: stopping BLe Batch
,09-02 15:26:25.460  6212  6266 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,09-02 15:26:25.460  6906  6924 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=0
,09-02 15:26:25.460  6906  6924 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,09-02 15:26:25.460  6906  6928 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
,09-02 15:26:25.460  6906  6924 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=0
,09-02 15:26:25.460  6906  6924 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,09-02 15:26:25.470  6212  6266 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,09-02 15:26:25.470  6212  6266 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,09-02 15:26:25.470  6212  6266 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
,09-02 15:26:25.470  6212  6266 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,09-02 15:26:25.470  6906  6920 D BtGatt.GattService: registerClient() - UUID=61bb652c-f320-4918-9be6-f5ae1d505962
,09-02 15:26:25.510  6906  6924 D BtGatt.GattService: onClientRegistered() - UUID=61bb652c-f320-4918-9be6-f5ae1d505962, clientIf=6
09-02 15:26:25.510  6212  6221 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=6
09-02 15:26:25.510  6906  6978 D BtGatt.GattService: start scan with filters
,09-02 15:26:25.520  6212  6266 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING,
,09-02 15:26:25.520  6212  6266 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
,09-02 15:26:25.520  6212  6266 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
,09-02 15:26:25.520  6212  6266 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING],
09-02 15:26:25.520  6906  6928 D BtGatt.ScanManager: handling starting scan
09-02 15:26:25.520  6906  6924 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=6, status=0, action=1
09-02 15:26:25.520  6906  6924 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
09-02 15:26:25.520  6906  6928 D BtGatt.ScanManager: allow scan with filters
09-02 15:26:25.520  6906  6928 D BtGatt.ScanManager: client filter size is = 1available filters are = 13
09-02 15:26:25.520  6906  6928 D BtGatt.ScanManager: set filter index= 4 for clientIf= 6
,09-02 15:26:25.520  6212  6266 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
09-02 15:26:25.520  6212  6266 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,09-02 15:26:25.520  6212  6212 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,09-02 15:26:25.520  6906  6924 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=0, availableSpace=15
09-02 15:26:25.520  6906  6924 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
09-02 15:26:25.520  6906  6928 D BtGatt.ScanManager: Starting BLE batch scan
09-02 15:26:25.520  6906  6928 D BtGatt.ScanManager: configuring batch scan storage, appIf 6
,09-02 15:26:25.530  6906  6924 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=6, status=0
,09-02 15:26:25.530  6906  6924 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,09-02 15:26:25.530  1019  1132 E WifiNative-wlan0: do suspend true
,09-02 15:26:25.530  6906  6924 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=1
,09-02 15:26:25.530  6906  6924 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,09-02 15:26:25.540  6212  6266 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,09-02 15:26:25.540  6212  6266 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
09-02 15:26:25.540  6212  6266 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,09-02 15:26:25.540  6212  6266 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-02 15:26:25.550  6212  6266 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-02 15:26:25.550  6212  6266 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-02 15:26:25.550  6212  6266 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-02 15:26:25.550  6212  6266 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 15:26:25.550  6212  6266 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-02 15:26:25.550  6212  6266 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-02 15:26:25.550  6212  6266 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c791f5c removed from the list
09-02 15:26:25.550  6212  6266 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-02 15:26:25.550  6212  6266 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@14489265 removed from the list
09-02 15:26:25.550  6212  6266 D io.jxcore.node.ConnectivityMonitor: stop
09-02 15:26:25.550  6212  6266 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-02 15:26:25.550  6212  6266 W org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: The given listener does not exist in the list - probably already removed
09-02 15:26:25.550  6212  6266 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 1 listener(s) left
09-02 15:26:25.550  6212  6266 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-02 15:26:25.550  6212  6266 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-02 15:26:25.550  6212  6266 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,09-02 15:26:25.550  6212  6266 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,09-02 15:26:25.550  6212  6266 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-02 15:26:25.550  6212  6266 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@14489265 not in the list
09-02 15:26:25.550  6212  6266 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-02 15:26:25.550  6212  6266 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
,09-02 15:26:25.550  6212  6266 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode,
09-02 15:26:25.550  6212  6266 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-02 15:26:25.550  6212  6266 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
09-02 15:26:25.550  6906  6978 D BtGatt.GattService: stopScan() - queue size =1
,09-02 15:26:25.550  1019  1131 D WifiP2pService: InactiveState{ what=143375 }
,09-02 15:26:25.550  1019  1131 D WifiP2pService: P2pEnabledState{ what=143375 }
09-02 15:26:25.550  6906  6964 D BtGatt.GattService: unregisterClient() - clientIf=6
,09-02 15:26:25.560  6212  6266 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,09-02 15:26:25.560  6212  6266 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
09-02 15:26:25.560  6212  6266 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
09-02 15:26:25.560  6212  6266 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
09-02 15:26:25.560  6212  6266 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,09-02 15:26:25.560  1019  1132 E WifiStateMachine: WifiStateMachine: handleSuccessfulIpConfiguration and no scan results"NG700"WPA_PSK
09-02 15:26:25.560  1019  1132 E WifiStateMachine: VerifyingLinkState enter
09-02 15:26:25.560  6906  6928 D BtGatt.ScanManager: 1. app : com.android.bluetooth 2. Action : LESC 3. Callng app : com.test.thalitest 4. Count : 22
,09-02 15:26:25.560  6212  6266 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
09-02 15:26:25.560  1182  1182 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
09-02 15:26:25.560  1182  1182 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
09-02 15:26:25.560  1182  1182 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-02 15:26:25.560  1182  1182 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-02 15:26:25.560  1182  1182 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-02 15:26:25.560  1182  1182 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-02 15:26:25.560  6906  6928 D BtGatt.ScanManager: filter size is 1
,09-02 15:26:25.560  6906  6928 D BtGatt.ScanManager: delete FilterIndex - 4
09-02 15:26:25.560  6212  6266 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-02 15:26:25.560  6212  6266 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-02 15:26:25.560  6212  6266 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-02 15:26:25.560  1019  1132 D WifiNative-wlan0: callSECApiInt - ID [210]
09-02 15:26:25.560  6906  6924 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=1, availableSpace=16
09-02 15:26:25.560  6906  6924 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,09-02 15:26:25.560  6212  6266 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-02 15:26:25.560  6906  6928 D BtGatt.ScanManager: stopping BLe Batch
,09-02 15:26:25.570  1019  1138 E ConnectivityService: updateNetworkInfo()
,09-02 15:26:25.570  1019  1138 D ConnectivityService: updateLinkProperties: newLp = {InterfaceName: wlan0 LinkAddresses: [192.168.1.111/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}, oldLp = null
09-02 15:26:25.570  1019  1138 D ConnectivityService: Adding iface wlan0 to network 503
,09-02 15:26:25.570  6906  6924 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=0
,09-02 15:26:25.570  6906  6924 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,09-02 15:26:25.570  6906  6928 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
09-02 15:26:25.570  6212  6212 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,09-02 15:26:25.570  6212  6212 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-02 15:26:25.570  6212  6212 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-02 15:26:25.570  6212  6266 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-02 15:26:25.570  6212  6266 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-02 15:26:25.570  6212  6266 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose,
09-02 15:26:25.570  6212  6266 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@526d548 removed from the list
09-02 15:26:25.570  6212  6266 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-02 15:26:25.570  6212  6266 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 15:26:25.570  6212  6266 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-02 15:26:25.570  6212  6266 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-02 15:26:25.570  6212  6266 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3b9ae3eb removed from the list
09-02 15:26:25.570  6212  6266 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-02 15:26:25.570  6212  6266 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2177fdf4 added. We now have 2 listener(s)
,09-02 15:26:25.580  6906  6924 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=0
09-02 15:26:25.580  6906  6924 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,09-02 15:26:25.590  1019  1148 D WifiWatchdogStateMachine: updateDnsLinkProperty: enter
,09-02 15:26:25.590  1019  1148 D WifiWatchdogStateMachine.DnsPinger: setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.111/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
09-02 15:26:25.590  1019  1148 D WifiWatchdogStateMachine.DnsResolver: setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.111/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
09-02 15:26:25.590  1019  1148 D WifiWatchdogStateMachine.SingDnsChecker: setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.111/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
09-02 15:26:25.590  1019  1148 D WifiWatchdogStateMachine.CaptivePortalDnsResolver: setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.111/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
,09-02 15:26:25.600  1019  1138 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 503
,09-02 15:26:25.600  1182  1182 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,09-02 15:26:25.600  1182  1182 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
09-02 15:26:25.600  1182  1182 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-02 15:26:25.600  1182  1182 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-02 15:26:25.600  1182  1182 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-02 15:26:25.600  1182  1182 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-02 15:26:25.600  1019  1138 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 503
,09-02 15:26:25.600  1019  1138 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network. 503
09-02 15:26:25.600  1019  1138 E ConnectivityService: Unexpected mtu value: 0, wlan0
09-02 15:26:25.600  1019  1138 D ConnectivityService: Setting Dns servers for network 503 to [/192.168.1.1]
09-02 15:26:25.600  1019  1132 E WifiStateMachine: VerifyingLinkState GOOD_LINK_DETECTED: transition to (new) connected (old)captive portal check
09-02 15:26:25.600  1019  1138 D ConnectivityService: LTETest block dns file not exists
,09-02 15:26:25.610  6212  6266 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "7C:F9:0E:37:96:AB"
09-02 15:26:25.610  6212  6266 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-02 15:26:25.610  6212  6266 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-02 15:26:25.610  6212  6266 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-02 15:26:25.610  6212  6266 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2e2fa91d added. We now have 9 listener(s)
09-02 15:26:25.610  6212  6266 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-02 15:26:25.610  1019  1138 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 503]
,09-02 15:26:25.610  6212  6266 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-02 15:26:25.620  1019  1138 E ConnectivityService: updateNetworkInfo()
,09-02 15:26:25.620  1019  1031 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
09-02 15:26:25.620  1019  1031 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,09-02 15:26:25.620  6212  6266 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-02 15:26:25.620  1019  1031 W ActivityManager: userId = 0, bbcId = -10000
09-02 15:26:25.620  1019  1031 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-02 15:26:25.620  1019  1031 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,09-02 15:26:25.620  1019  1138 E ConnectivityService: updateNetworkInfo()
09-02 15:26:25.620  1019  1138 D ConnectivityService: NetworkAgentInfo [WIFI () - 503] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
09-02 15:26:25.620  1019  1138 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 503]
,09-02 15:26:25.620  1019  1138 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 503]
09-02 15:26:25.620  1019  7004 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: DefaultState{ when=0 what=532481 target=com.android.internal.util.StateMachine$SmHandler }
09-02 15:26:25.620  1019  7004 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Connected
09-02 15:26:25.620  1019  7004 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
,09-02 15:26:25.620  1019  7004 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Checking http://connectivitycheck.android.com/generate_204 on "NG700"
,09-02 15:26:25.620  1019  7004 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,09-02 15:26:25.620  3631  3631 I Hs20UtilService: Starting #20
,09-02 15:26:25.630  1019  1019 I WifiTrafficPoller: evaluateTrafficStatsPolling
,09-02 15:26:25.630  3631  3649 I Hs20UtilService: Message received 5007
,09-02 15:26:25.630   278   994 D EnterpriseController: uids 1000
09-02 15:26:25.630   278   994 D EnterpriseController: mIsMarkChainAdded is 18 mIsBlockChainAdded is 252 netId is 0
09-02 15:26:25.630   278   994 D Netd    : getNetworkForDns: using netid 503 for uid 1000
09-02 15:26:25.630  1019  1138 D ConnectivityService:    accepting network in place of null
,09-02 15:26:25.630  1019  1131 D WIFI_P2P: evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= false
,09-02 15:26:25.630  1019  1138 E CSLegacyTypeTracker: add() : Adding agent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{503}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.111/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{true} explicitlySelected{false} } for legacy network type 1
09-02 15:26:25.630  1460  1460 D TelephonyNetworkFactory: evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= true
09-02 15:26:25.630  1019  1138 D CSLegacyTypeTracker: Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 503] isDefaultNetwork=true
09-02 15:26:25.630  1460  1460 D TelephonyNetworkFactory: Cellular releasing Network for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-02 15:26:25.630  1019  1138 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,09-02 15:26:25.630  6212  6266 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-02 15:26:25.630  6212  6266 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-02 15:26:25.630  6212  6266 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-02 15:26:25.630  6212  6266 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-02 15:26:25.630  6212  6266 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-02 15:26:25.630  6212  6266 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-02 15:26:25.630  6212  6266 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-02 15:26:25.630  6212  6266 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-02 15:26:25.640  6212  6266 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-02 15:26:25.640  6212  6266 D io.jxcore.node.ConnectivityMonitor: start: OK,
09-02 15:26:25.640  6212  6266 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-02 15:26:25.640  6212  6266 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2f7de563 added. We now have 3 listener(s)
,09-02 15:26:25.640  1182  1182 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
09-02 15:26:25.640  1182  1182 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
09-02 15:26:25.640  1182  1182 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-02 15:26:25.640  1182  1182 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-02 15:26:25.640  1182  1182 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-02 15:26:25.640  1182  1182 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-02 15:26:25.650  1019  1019 I WifiTrafficPoller: evaluateTrafficStatsPolling
,09-02 15:26:25.650  1019  1019 I WifiTrafficPoller: mBoosterFLAG : 0
09-02 15:26:25.650  1019  1019 I WifiTrafficPoller: current booster mode : FullMode
09-02 15:26:25.650  1019  1132 D WIFI    : evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= true
09-02 15:26:25.650  1019  1019 D WifiNative-wlan0: callSECApiVoid - ID [212]
,09-02 15:26:25.660  1182  1182 D StatusBar.NetworkController: refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,09-02 15:26:25.660  1182  1182 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:"NG700"
09-02 15:26:25.660  1182  1182 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-02 15:26:25.660  1182  1182 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-02 15:26:25.660  1182  1182 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-02 15:26:25.660  1182  1182 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-02 15:26:25.660  1296  1296 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,09-02 15:26:25.660  1296  1296 I NearbySettings: MountReceiver.onReceive - Keep current state
,09-02 15:26:25.660  6212  6266 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "7C:F9:0E:37:96:AB"
09-02 15:26:25.660  6212  6266 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-02 15:26:25.660  6212  6266 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-02 15:26:25.660  6212  6266 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-02 15:26:25.660  6212  6266 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@22110560 added. We now have 10 listener(s)
09-02 15:26:25.660  6212  6266 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-02 15:26:25.660  6212  6266 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-02 15:26:25.670  6212  6266 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-02 15:26:25.670  6212  6266 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-02 15:26:25.670  6212  6266 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-02 15:26:25.670  6212  6266 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,09-02 15:26:25.670  1019  1138 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{503}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.111/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{true} explicitlySelected{false} }
,09-02 15:26:25.670  1019  1138 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 503]
,09-02 15:26:25.670  1019  1050 D EntConnectivity: Not allowed due to - mEnabled false - primarySimSlot false
09-02 15:26:25.670  1019  1019 D Tethering: Tethering got CONNECTIVITY_ACTION_IMMEDIATE
09-02 15:26:25.670  1019  1139 D Tethering: MasterInitialState.processMessage what=3
,09-02 15:26:25.680  1182  1698 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
,09-02 15:26:25.680  6212  6212 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-02 15:26:25.680  6212  6212 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-02 15:26:25.680  6212  6212 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-02 15:26:25.680  6212  6212 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-02 15:26:25.680  6212  6212 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-02 15:26:25.680  6212  6212 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-02 15:26:25.680  6212  6212 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-02 15:26:25.680  6212  6212 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-02 15:26:25.680  3800  6269 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
,09-02 15:26:25.680  6212  6212 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-02 15:26:25.680  6212  6212 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-02 15:26:25.690  1019  1129 D NtpTrustedTime: currentTimeMillis() cache hit
09-02 15:26:25.690  1019  1129 V NetworkStats: updateIfacesLocked()
,09-02 15:26:25.690  1019  1129 D NetworkStatsFactory: UpdateStatsForKnox updated
09-02 15:26:25.690  1019  1129 V NetworkStats: performPollLocked(flags=0x1)
09-02 15:26:25.690  1019  1129 D NetworkStatsFactory: UpdateStatsForKnox main else ---
,09-02 15:26:25.690  1019  1129 V NetworkStats: performPollLocked() took 5ms
,09-02 15:26:25.690  1019  1129 D NtpTrustedTime: currentTimeMillis() cache hit
,09-02 15:26:25.690  6212  6266 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,09-02 15:26:25.700  1019  1130 D NtpTrustedTime: currentTimeMillis() cache hit
,09-02 15:26:25.700  1182  1182 D StatusBar.NetworkController: EthernetConnected: false
09-02 15:26:25.700  1182  1182 D StatusBar.NetworkController: getUpdateDataNetType(): 0
09-02 15:26:25.700  1182  1182 D StatusBar.NetworkController: getUpdateDataNetType(): mDataTypeBrand = LTE
09-02 15:26:25.700  1182  1182 D StatusBar.NetworkController: updateDataNetType()
09-02 15:26:25.700  1182  1182 D StatusBar.NetworkController: NoService, mRoamingIconId = 0
09-02 15:26:25.700  1182  1182 E StatusBar.NetworkController: updateLTEICONDataNetType:0
,09-02 15:26:25.700  1019  1130 D NtpTrustedTime: currentTimeMillis() cache hit
09-02 15:26:25.700  1019  1130 D NtpTrustedTime: currentTimeMillis() cache hit,
,09-02 15:26:25.700  1019  1130 V NetworkStats: advisePersistThreshold() given 9223372036854775, clamped to 2097152,
09-02 15:26:25.700  1019  1130 D NtpTrustedTime: currentTimeMillis() cache hit
,09-02 15:26:25.710  1019  1130 D NtpTrustedTime: currentTimeMillis() cache hit
,09-02 15:26:25.710  1019  1130 D NtpTrustedTime: currentTimeMillis() cache hit
,09-02 15:26:25.710  1182  1182 D StatusBar.NetworkController: updateDataIcon, mDataDirectionIconId = (null) mDataConnected = false
09-02 15:26:25.710  1182  1182 D StatusBar.NetworkController: updateTelephonySignalStrength: hasService=false ss=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte
09-02 15:26:25.710  1182  1182 D StatusBar.NetworkController: updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal
,09-02 15:26:25.710  1182  1182 D StatusBar.NetworkController: refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
09-02 15:26:25.710  1182  1182 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:"NG700"
09-02 15:26:25.710  1182  1182 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-02 15:26:25.710  1182  1182 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-02 15:26:25.710  1182  1182 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-02 15:26:25.710  1182  1182 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-02 15:26:25.710  6212  6266 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,09-02 15:26:25.710  6212  6266 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,09-02 15:26:25.720  1019  1031 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
09-02 15:26:25.720  1019  1031 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,09-02 15:26:25.720  1019  1031 W ActivityManager: userId = 0, bbcId = -10000
09-02 15:26:25.720  1019  1031 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-02 15:26:25.720  1019  1031 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,09-02 15:26:25.720  6212  6266 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
09-02 15:26:25.720  6212  6266 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
09-02 15:26:25.720  6212  6266 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,09-02 15:26:25.720  3631  3631 I Hs20UtilService: Starting #21
,09-02 15:26:25.720  6906  6920 D BtGatt.GattService: registerClient() - UUID=3d82ba8f-a0ef-4669-86ab-3d4a66081327
,09-02 15:26:25.720  1296  1296 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
09-02 15:26:25.720  3631  3649 I Hs20UtilService: Message received 5007
,09-02 15:26:25.720  1296  1296 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
09-02 15:26:25.720  1296  1296 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: CONNECTED
,09-02 15:26:25.720  1296  1296 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
09-02 15:26:25.720  1296  1296 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-true, Hotspot-false, P2P-false, Eth-false
09-02 15:26:25.720  1296  1296 I NearbySettings: MountReceiver.onReceive - Keep current state
,09-02 15:26:25.730  1019  1082 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
,09-02 15:26:25.730  1019  1082 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,09-02 15:26:25.730  1019  1082 W ActivityManager: userId = 0, bbcId = -10000
,09-02 15:26:25.730  1019  1082 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-02 15:26:25.730  1019  1082 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,09-02 15:26:25.740  3631  3631 I Hs20UtilService: Starting #22
,09-02 15:26:25.740  3631  3649 I Hs20UtilService: Message received 5007
,09-02 15:26:25.740  1019  7004 I System.out: KnoxVpnUidStorageknoxVpnSupported API value returned is false
,09-02 15:26:25.740  1296  1296 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,09-02 15:26:25.740  1296  1296 I NearbySettings: MountReceiver.onReceive - Keep current state
,09-02 15:26:25.750  1019  1484 D WifiStateMachine: SEC_COMMAND_ID_GET_FWS_OPEN_AP_CHECK : 0
,09-02 15:26:25.750  1019  3093 D SecContentProvider2: uri = 15 selection = getToastGravityEnabledState
,09-02 15:26:25.750  1019  3093 D SecContentProvider2: mCursor = null
,09-02 15:26:25.750  1019  1322 D SecContentProvider2: uri = 15 selection = getToastGravity
,09-02 15:26:25.750  1019  1322 D SecContentProvider2: mCursor = null
,09-02 15:26:25.750  1019  2905 D SecContentProvider2: uri = 15 selection = getToastGravityXOffset
,09-02 15:26:25.750  1019  2905 D SecContentProvider2: mCursor = null
,09-02 15:26:25.750  1019  1223 D SecContentProvider2: uri = 15 selection = getToastGravityYOffset
,09-02 15:26:25.750  1019  1223 D SecContentProvider2: mCursor = null
,09-02 15:26:25.760  1019  3109 D SecContentProvider2: uri = 15 selection = getToastEnabledState
,09-02 15:26:25.760  1019  3109 D SecContentProvider2: mCursor = null
,09-02 15:26:25.760  1019  2952 D SecContentProvider2: uri = 15 selection = getToastShowPackageNameState
,09-02 15:26:25.760  1019  2952 D SecContentProvider2: mCursor = null
,09-02 15:26:25.760  6906  6924 D BtGatt.GattService: onClientRegistered() - UUID=3d82ba8f-a0ef-4669-86ab-3d4a66081327, clientIf=6
,09-02 15:26:25.760  6212  6221 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=6
,09-02 15:26:25.760  6906  6978 D BtGatt.GattService: start scan with filters
,09-02 15:26:25.760  6212  6266 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
09-02 15:26:25.760  6212  6266 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
09-02 15:26:25.760  6212  6266 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
09-02 15:26:25.760  6212  6266 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,09-02 15:26:25.770  6906  6928 D BtGatt.ScanManager: handling starting scan
,09-02 15:26:25.770  6906  6924 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=6, status=0, action=1,
09-02 15:26:25.770  6906  6924 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
09-02 15:26:25.770  6906  6928 D BtGatt.ScanManager: allow scan with filters
,09-02 15:26:25.770  6906  6928 D BtGatt.ScanManager: client filter size is = 1available filters are = 13
09-02 15:26:25.770  6906  6928 D BtGatt.ScanManager: set filter index= 5 for clientIf= 6
,09-02 15:26:25.770  6906  6924 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=0, availableSpace=15
,09-02 15:26:25.770  6906  6924 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
09-02 15:26:25.770  6906  6928 D BtGatt.ScanManager: Starting BLE batch scan
09-02 15:26:25.770  6906  6928 D BtGatt.ScanManager: configuring batch scan storage, appIf 6
09-02 15:26:25.770  6906  6924 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=6, status=0
09-02 15:26:25.770  6906  6924 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
09-02 15:26:25.780  6212  6266 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
09-02 15:26:25.780  6212  6212 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
09-02 15:26:25.780  6906  6924 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=1
09-02 15:26:25.780  6906  6924 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
09-02 15:26:25.790  6212  6266 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
09-02 15:26:25.790   258   258 I SurfaceFlinger: id=15 createSurf (1x1),1 flag=4, Uoast
09-02 15:26:25.790  6212  6266 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
09-02 15:26:25.790  6906  6928 D BtGatt.ScanManager: 1. app : com.android.bluetooth 2. Action : LESC 3. Callng app : com.test.thalitest 4. Count : 23
09-02 15:26:25.790  6212  6266 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-02 15:26:25.790  6212  6266 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-02 15:26:25.790  6212  6266 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,09-02 15:26:25.800  6212  6266 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-02 15:26:25.800  6212  6266 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 15:26:25.800  6212  6266 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-02 15:26:25.800  6212  6266 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-02 15:26:25.800  6212  6266 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2177fdf4 removed from the list
,09-02 15:26:25.800  6212  6266 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-02 15:26:25.800  6212  6266 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2e2fa91d removed from the list
09-02 15:26:25.800  6212  6266 D io.jxcore.node.ConnectivityMonitor: stop
,09-02 15:26:25.800  6212  6266 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-02 15:26:25.800  6212  6266 W org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: The given listener does not exist in the list - probably already removed
,09-02 15:26:25.800  6212  6266 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 1 listener(s) left
09-02 15:26:25.800  6212  6266 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 15:26:25.800  6212  6266 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-02 15:26:25.800  6212  6266 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,09-02 15:26:25.800  6212  6266 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-02 15:26:25.800  6212  6266 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-02 15:26:25.800  6212  6266 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2e2fa91d not in the list
09-02 15:26:25.800  6212  6266 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-02 15:26:25.800  6212  6266 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-02 15:26:25.800  6212  6266 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-02 15:26:25.800  6212  6266 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-02 15:26:25.800  6212  6266 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,09-02 15:26:25.800  6906  6920 D BtGatt.GattService: stopScan() - queue size =1
,09-02 15:26:25.800  6906  6978 D BtGatt.GattService: unregisterClient() - clientIf=6
,09-02 15:26:25.800  6906  6928 D BtGatt.ScanManager: filter size is 1
09-02 15:26:25.800  6906  6928 D BtGatt.ScanManager: delete FilterIndex - 5
,09-02 15:26:25.800  6212  6266 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-02 15:26:25.800  6212  6266 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
09-02 15:26:25.800  6212  6266 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
09-02 15:26:25.800  6212  6266 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
09-02 15:26:25.800  6212  6266 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,09-02 15:26:25.800  6906  6924 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=1, availableSpace=16
09-02 15:26:25.800  6906  6924 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,09-02 15:26:25.800  6906  6928 D BtGatt.ScanManager: stopping BLe Batch
09-02 15:26:25.800  6212  6266 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,09-02 15:26:25.810  6212  6266 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-02 15:26:25.810  6212  6266 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-02 15:26:25.810  6212  6266 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,09-02 15:26:25.810  6212  6266 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-02 15:26:25.810  1019  3105 D PowerManagerService: [api] acquire WakeLock flags=0x2000000a tag=WindowManager uid=1000 pid=1019
,09-02 15:26:25.810  6212  6266 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-02 15:26:25.810  6212  6266 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-02 15:26:25.810  6212  6266 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-02 15:26:25.810  6212  6266 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@22110560 removed from the list
09-02 15:26:25.810  6212  6266 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-02 15:26:25.810  6212  6266 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 15:26:25.810  6212  6266 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-02 15:26:25.810  6212  6266 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-02 15:26:25.810  6212  6266 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2f7de563 removed from the list
09-02 15:26:25.810  6212  6212 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-02 15:26:25.810  6212  6212 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-02 15:26:25.810  6212  6212 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-02 15:26:25.810  6212  6266 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-02 15:26:25.810  6212  6266 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2b71178c added. We now have 2 listener(s)
,09-02 15:26:25.810  6906  6924 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=0
09-02 15:26:25.810  6906  6924 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,09-02 15:26:25.810  6906  6928 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
,09-02 15:26:25.810  6212  6266 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "7C:F9:0E:37:96:AB"
09-02 15:26:25.810  6212  6266 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-02 15:26:25.810  6212  6266 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,09-02 15:26:25.810  6212  6266 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-02 15:26:25.810  6212  6266 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@369bded5 added. We now have 9 listener(s)
09-02 15:26:25.810  6212  6266 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-02 15:26:25.810  6212  6266 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-02 15:26:25.810  6906  6924 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=0
09-02 15:26:25.810  6906  6924 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,09-02 15:26:25.810  1019  7004 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Fri, 02 Sep 2016 13:26:25 GMT], X-Android-Received-Millis=[1472822785820], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1472822785780]}
09-02 15:26:25.810  1019  7004 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Don't send network conditions - lacking user consent.
09-02 15:26:25.810  1019  7004 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Validated
09-02 15:26:25.810  1019  1138 D ConnectivityService: Validated NetworkAgentInfo [WIFI () - 503]
09-02 15:26:25.810  1019  1138 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 503]
,09-02 15:26:25.810  1019  1138 D ConnectivityService: Network NetworkAgentInfo [WIFI () - 503] was already satisfying request 1. No change.
09-02 15:26:25.810  1019  1138 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 503]
,09-02 15:26:25.820  1019  1138 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,09-02 15:26:25.820  1182  1698 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
09-02 15:26:25.820  6212  6266 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-02 15:26:25.820  3800  6269 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
,09-02 15:26:25.820  1182  1182 D SRIB_DCS: log_dcs ThreadedRenderer::initialize entered! 
,09-02 15:26:25.830  6212  6266 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-02 15:26:25.830  6212  6266 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-02 15:26:25.830  6212  6266 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-02 15:26:25.830  6212  6266 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-02 15:26:25.830  6212  6266 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-02 15:26:25.830  6212  6266 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-02 15:26:25.830  6212  6266 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-02 15:26:25.830  6212  6266 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-02 15:26:25.830  1182  1182 D StatusBar.NetworkController: EthernetConnected: false
,09-02 15:26:25.830  1182  1182 D StatusBar.NetworkController: getUpdateDataNetType(): 0
,09-02 15:26:25.830  1182  1182 D StatusBar.NetworkController: getUpdateDataNetType(): mDataTypeBrand = LTE
09-02 15:26:25.830  1182  1182 D StatusBar.NetworkController: updateDataNetType()
09-02 15:26:25.830  6212  6266 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-02 15:26:25.830  1182  1182 D StatusBar.NetworkController: NoService, mRoamingIconId = 0
09-02 15:26:25.830  6212  6266 D io.jxcore.node.ConnectivityMonitor: start: OK
09-02 15:26:25.830  1182  1182 E StatusBar.NetworkController: updateLTEICONDataNetType:0
,09-02 15:26:25.830  6212  6266 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,09-02 15:26:25.830  6212  6266 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2aa09ddb added. We now have 3 listener(s)
,09-02 15:26:25.840  6212  6212 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-02 15:26:25.840  1182  1182 D StatusBar.NetworkController: updateDataIcon, mDataDirectionIconId = (null) mDataConnected = false
09-02 15:26:25.840  1182  1182 D StatusBar.NetworkController: updateTelephonySignalStrength: hasService=false ss=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte
09-02 15:26:25.840  1182  1182 D StatusBar.NetworkController: updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal
,09-02 15:26:25.840  1182  1182 D StatusBar.NetworkController: refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
09-02 15:26:25.840  1182  1182 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:"NG700"
09-02 15:26:25.840  1182  1182 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-02 15:26:25.840  1182  1182 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-02 15:26:25.840  1182  1182 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-02 15:26:25.840  1182  1182 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-02 15:26:25.840  6212  6266 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "7C:F9:0E:37:96:AB"
,09-02 15:26:25.840  6212  6266 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-02 15:26:25.840  6212  6266 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-02 15:26:25.840  6212  6266 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-02 15:26:25.840  6212  6266 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8de2078 added. We now have 10 listener(s)
09-02 15:26:25.840  6212  6266 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-02 15:26:25.840  6212  6266 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-02 15:26:25.840  6212  6266 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-02 15:26:25.840  6212  6266 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-02 15:26:25.840  6212  6266 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-02 15:26:25.840  6212  6266 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed,
09-02 15:26:25.840  6212  6266 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-02 15:26:25.840  6212  6266 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-02 15:26:25.840  6212  6266 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2b71178c removed from the list
,09-02 15:26:25.840  6212  6266 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-02 15:26:25.840  6212  6266 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@369bded5 removed from the list
09-02 15:26:25.840  6212  6212 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-02 15:26:25.840  6212  6266 D io.jxcore.node.ConnectivityMonitor: stop
09-02 15:26:25.840  6212  6266 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-02 15:26:25.840  6212  6266 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 15:26:25.840  6212  6266 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-02 15:26:25.840  6212  6266 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-02 15:26:25.840  6212  6266 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-02 15:26:25.840  6212  6266 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-02 15:26:25.840  6212  6266 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@369bded5 not in the list
09-02 15:26:25.840  6212  6266 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 15:26:25.840  6212  6266 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-02 15:26:25.840  6212  6266 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,09-02 15:26:25.840  6212  6266 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,09-02 15:26:25.840  6212  6266 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-02 15:26:25.850  6212  6266 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8de2078 removed from the list
,09-02 15:26:25.850  6212  6266 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-02 15:26:25.850  6212  6266 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 15:26:25.850  6212  6266 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-02 15:26:25.850  6212  6266 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-02 15:26:25.850  6212  6266 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2aa09ddb removed from the list
,09-02 15:26:25.850  6212  6266 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: true, is advertising: true - Start operation: Should start/stop everything
,09-02 15:26:25.850  6212  6266 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
,09-02 15:26:25.850  6212  6266 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
,09-02 15:26:25.850  6212  6266 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-02 15:26:25.850  6212  6266 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should affect listening to advertisements only
09-02 15:26:25.850  6212  6266 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
,09-02 15:26:25.860  6212  7045 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 1181, name: My test thread name)
,09-02 15:26:25.860  6212  7045 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 1181, thread name: My test thread name)
,09-02 15:26:25.860  6212  7045 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 1181, name: My test thread name), during the lifetime of the thread the total number of bytes read was 122 and the total number of bytes written 122
,09-02 15:26:25.860  6212  7046 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 1183, name: My test thread name)
,09-02 15:26:25.860  6212  7046 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 1183, thread name: My test thread name)
09-02 15:26:25.860  6212  7046 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 1183, name: My test thread name), during the lifetime of the thread the total number of bytes read was 122 and the total number of bytes written 122
,09-02 15:26:25.870  6212  6266 D com.test.thalitest.ThaliTestRunner: Total number of executed tests: 80
09-02 15:26:25.870  6212  6266 D com.test.thalitest.ThaliTestRunner: Number of passed tests: 80
09-02 15:26:25.870  6212  6266 D com.test.thalitest.ThaliTestRunner: Number of failed tests:  0
09-02 15:26:25.870  6212  6266 D com.test.thalitest.ThaliTestRunner: Number of ignored tests: 0
09-02 15:26:25.870  6212  6266 D com.test.thalitest.ThaliTestRunner: Total duration: 23431 ms
,09-02 15:26:25.870  6212  6266 I jxcore-log: *Native tests were executed*,
09-02 15:26:25.870  6212  6266 I jxcore-log: 
09-02 15:26:25.870  6212  6266 I jxcore-log: Total number of executed tests:  80
09-02 15:26:25.870  6212  6266 I jxcore-log: 
09-02 15:26:25.870  6212  6266 I jxcore-log: Number of passed tests:  80
09-02 15:26:25.870  6212  6266 I jxcore-log: ,
09-02 15:26:25.870  6212  6266 I jxcore-log: Number of failed tests:  0
09-02 15:26:25.870  6212  6266 I jxcore-log: 
09-02 15:26:25.870  6212  6266 I jxcore-log: Number of ignored tests:  0
09-02 15:26:25.870  6212  6266 I jxcore-log: 
,09-02 15:26:25.870  6212  6266 I jxcore-log: Total duration:  23431
09-02 15:26:25.870  6212  6266 I jxcore-log: 
09-02 15:26:25.870  6212  6266 I jxcore-log: ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****,
09-02 15:26:25.870  6212  6266 I jxcore-log: 
09-02 15:26:25.870  6212  6266 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-02 15:26:25.870  6212  6266 I jxcore-log: 
09-02 15:26:25.880  6212  6266 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-02 15:26:25.880  6212  6266 I jxcore-log: 
09-02 15:26:25.880  6212  6266 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-02 15:26:25.880  6212  6266 I jxcore-log: 
09-02 15:26:25.880  6212  6266 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-02 15:26:25.880  6212  6266 I jxcore-log: 
09-02 15:26:25.880  6212  6266 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-02 15:26:25.880  6212  6266 I jxcore-log: 
09-02 15:26:25.880  6212  6266 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-02 15:26:25.880  6212  6266 I jxcore-log: 
09-02 15:26:25.880  6212  6266 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-02 15:26:25.880  6212  6266 I jxcore-log: 
,09-02 15:26:25.890  6212  6266 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
09-02 15:26:25.890  6212  6266 I jxcore-log: 
,09-02 15:26:25.890  6212  6266 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-02 15:26:25.890  6212  6266 I jxcore-log: 
,09-02 15:26:25.890  6212  6266 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-02 15:26:25.890  6212  6266 I jxcore-log: 
,09-02 15:26:25.890  6212  6212 I chromium: [INFO:CONSOLE(68)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (68)
,09-02 15:26:25.890  6212  6266 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
09-02 15:26:25.890  6212  6266 I jxcore-log: 
,09-02 15:26:25.890  6212  6266 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
09-02 15:26:25.890  6212  6266 I jxcore-log: 
,09-02 15:26:25.890  6212  6266 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-02 15:26:25.890  6212  6266 I jxcore-log: 
,09-02 15:26:25.890  6212  6266 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-02 15:26:25.890  6212  6266 I jxcore-log: 
,09-02 15:26:25.890  6212  6266 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
09-02 15:26:25.890  6212  6266 I jxcore-log: 
,09-02 15:26:25.890  6212  6266 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
09-02 15:26:25.890  6212  6266 I jxcore-log: 
09-02 15:26:25.890  6212  6266 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-02 15:26:25.890  6212  6266 I jxcore-log: 
,09-02 15:26:25.890  6212  6266 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-02 15:26:25.890  6212  6266 I jxcore-log: 
,09-02 15:26:25.890  6212  6266 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
09-02 15:26:25.890  6212  6266 I jxcore-log: 
,09-02 15:26:25.900  6212  6266 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
09-02 15:26:25.900  6212  6266 I jxcore-log: 
,09-02 15:26:25.900  6212  6266 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-02 15:26:25.900  6212  6266 I jxcore-log: 
,09-02 15:26:25.900  6212  6266 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-02 15:26:25.900  6212  6266 I jxcore-log: 
,09-02 15:26:25.900  6212  6266 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-02 15:26:25.900  6212  6266 I jxcore-log: 
,09-02 15:26:25.900  6212  6266 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-02 15:26:25.900  6212  6266 I jxcore-log: 
,09-02 15:26:25.900  6212  6266 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-02 15:26:25.900  6212  6266 I jxcore-log: 
,09-02 15:26:25.900  6212  6266 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
,09-02 15:26:25.900  6212  6266 I jxcore-log: 
,09-02 15:26:25.900  6212  6266 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-02 15:26:25.900  6212  6266 I jxcore-log: 
,09-02 15:26:25.900  6212  6266 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-02 15:26:25.900  6212  6266 I jxcore-log: 
,09-02 15:26:25.920  6212  6212 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false,
09-02 15:26:25.920  6212  6266 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
09-02 15:26:25.920  6212  6266 I jxcore-log: 
,09-02 15:26:26.040   288   288 E SMD     : DCD OFF
,09-02 15:26:26.070  6212  6212 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
09-02 15:26:26.070  6212  6266 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
09-02 15:26:26.070  6212  6266 I jxcore-log: 
,09-02 15:26:26.130  7047  7047 D AndroidRuntime: 
09-02 15:26:26.130  7047  7047 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
,09-02 15:26:26.140  7047  7047 D AndroidRuntime: CheckJNI is OFF
,09-02 15:26:26.140  7047  7047 D AndroidRuntime: readGMSProperty: start
09-02 15:26:26.140  7047  7047 D AndroidRuntime: readGMSProperty: already setted!!
09-02 15:26:26.140  7047  7047 D AndroidRuntime: propertySet: couldn't set property (it is from app)
09-02 15:26:26.140  7047  7047 D AndroidRuntime: readGMSProperty: could not set the property(default)!!
09-02 15:26:26.140  7047  7047 D AndroidRuntime: readGMSProperty: end
09-02 15:26:26.140  7047  7047 D AndroidRuntime: addProductProperty: start
,09-02 15:26:26.170  1019  1138 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,09-02 15:26:26.180  1019  1045 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
,09-02 15:26:26.190  6212  6212 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-02 15:26:26.190  6212  6212 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-02 15:26:26.190  6212  6212 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-02 15:26:26.190  6212  6212 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-02 15:26:26.190  6212  6212 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-02 15:26:26.190  6212  6212 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-02 15:26:26.190  6212  6212 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-02 15:26:26.190  6212  6212 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-02 15:26:26.200  6212  6212 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-02 15:26:26.200  3151  3151 I DBG_DM  : [llllIlIIIllllIIlIlll(88/llIIIIlllllIIllIIllI)] WiFi Network is connected
,09-02 15:26:26.200  6212  6266 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-02 15:26:26.200  6212  6266 I jxcore-log: 
,09-02 15:26:26.200  6532  6532 I NetworkMonitor: type=WIFI subType= reason=null isConnected=true
,09-02 15:26:26.210  6515  6515 I PCWCLIENTTRACE_PushUtil: SPPPushClient is installed : true
09-02 15:26:26.210  6515  6515 I PCWCLIENTTRACE_PushUtil: sales region : global
09-02 15:26:26.210  6515  6515 I PCWCLIENTTRACE_PushUtil: getPushTypeList : [SPP, GCM]
09-02 15:26:26.210  6515  6515 I PCWCLIENTTRACE_SYSTEMReceiver: [onReceive] - android.net.conn.CONNECTIVITY_CHANGE
,09-02 15:26:26.210  1019  3109 I splitIntent: Split this intent : android.net.conn.CONNECTIVITY_CHANGE, mSplitNum[0]=8, mSplitNum[1]=17, mSplitNum[2]=25, mBgSplitQueueNum=3 divideNum= 8 r.nextReceiver= 1 receivers.size=33
,09-02 15:26:26.210  1019  3109 I splitIntent: finish to split intent : android.net.conn.CONNECTIVITY_CHANGE !! Enqueue -> schedule it!!
,09-02 15:26:26.220  6532  6532 V MusicLeanback: onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,09-02 15:26:26.220  1722  1722 D accuweather: [KK AccuPhone]>>> WCW:32 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,09-02 15:26:26.230  1019  1031 D RCPManagerService: exchangeData() failure , invalid userId
,09-02 15:26:26.230  1019  1082 D RCPManagerService: exchangeData() failure , invalid userId
09-02 15:26:26.240  6547  6547 I FOTA_Client: [com.sec.android.fotaclient.FotaRegisterReceiver(102/onReceive)] Already device registered...
,09-02 15:26:26.240  1722  1722 D accuweather: [KK AccuPhone]>>> U:4106 [0:0] getPWC : surface = 0, remote = 1
09-02 15:26:26.240  1722  1722 D accuweather: [KK AccuPhone]>>> U:4284 [0:0] Store PWC = 1
09-02 15:26:26.240  1722  1722 D accuweather: [KK AccuPhone]>>> U:4158 [0:0] addPWC = 1
,09-02 15:26:26.250  1722  1722 D accuweather: [KK AccuPhone]>>> UIM:306 [0:0]  action:androidnetconnCONNECTIVITY_CHANGE
,09-02 15:26:26.250  1019  1322 D SecContentProvider2: uri = 11 selection = getMyKnoxAdmin
09-02 15:26:26.250  1019  1322 D SecContentProvider2: mCursor = null
,09-02 15:26:26.250  6547  6547 I FOTA_Client: [com.sec.android.fotaclient.FotaUpdaterReceiver(93/onReceive)] Auto update settings is activated
,09-02 15:26:26.250  6483  6483 D SecurityLogAgent: KnoxConfiguration : Current State = 1
09-02 15:26:26.250  6483  6483 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
09-02 15:26:26.250  6483  6483 D SecurityLogAgent: StateMachine : Current State = 1
09-02 15:26:26.250  6547  6547 I FOTA_Client: [IlIlIIllllIllIIIIIll(81/llllIIIllIlIIIIllllI)] Polling time is vaild
09-02 15:26:26.260  6483  6483 D SecurityLogAgent: StateMachine : Changed Current State = 1
,09-02 15:26:26.260  1321  1765 D daemonapp: [MSC_Daemon]>>> WCP:1254 [0:0] cp update : count : 1, pt : 4
09-02 15:26:26.260  6547  6547 W FOTA_Client: [lIllIlIIlIIlllllIIll(98/llllIIIllIlIIIIllllI)] No file exists in Directory
,09-02 15:26:26.260  1722  1722 D accuweather: [KK AccuPhone]>>> WC:30 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,09-02 15:26:26.260  1722  1722 D accuweather: [KK AccuPhone]>>> UIMEM:104 [0:0] The widget does not exist in idle!!
,09-02 15:26:26.260  1722  1722 D accuweather: [KK AccuPhone]>>> U:4250 [0:0] Store PWC succeed
,09-02 15:26:26.270  6707  6707 I DIAGMON_AGENT: [lllIIIIlIIlIlllIlIIl(39/llIIIIlllllIIllIIllI)] Receive broadcast: android.net.conn.CONNECTIVITY_CHANGE,
09-02 15:26:26.270  6707  6707 I DIAGMON_AGENT: [lllIIIIlIIlIlllIlIIl(40/llIIIIlllllIIllIIllI)] Receive broadcast:
09-02 15:26:26.270  6707  6707 I DIAGMON_AGENT: ./extraInfo: "NG700"
09-02 15:26:26.270  6707  6707 I DIAGMON_AGENT: [lllIIIIlIIlIlllIlIIl(54/llIIIIlllllIIllIIllI)] Running with RegistrationReceiver
,09-02 15:26:26.280  3653  3653 I KLMS-2.5.183: : KLMSAbstractReciever(): onReceive(): Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.samsung.klmsagent/.listner.MainReciver (has extras) } | timestamp: Fri Sep 02 15:26:26 GMT+02:00 2016
,09-02 15:26:26.280  1019  3213 D ActivityManager: startService callerProcessName:com.samsung.klmsagent, calleePkgName: com.samsung.klmsagent
09-02 15:26:26.280  1019  3213 D ActivityManager: retrieveServiceLocked(): component = com.samsung.klmsagent/com.samsung.klmsagent.services.KLMSIntentService; callingUser = 0; userId(target) = 0
,09-02 15:26:26.280  1019  3213 W ActivityManager: userId = 0, bbcId = -10000
09-02 15:26:26.280  1019  3213 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-02 15:26:26.280  1019  3213 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.klmsagent, destAppInfo.processName = com.samsung.klmsagent
,09-02 15:26:26.290  3653  3653 I KLMS-2.5.183: : KLMSAbstractReciever(): onReceive().END.
,09-02 15:26:26.290  3653  3653 I KLMS-2.5.183: : KLMSIntentService(): onCreate()
,09-02 15:26:26.290  7047  7047 E AffinityControl: AffinityControl: registerfunction enter
,09-02 15:26:26.290  1019  1223 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
09-02 15:26:26.290  1019  1223 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.gcm.GcmService; callingUser = 0; userId(target) = 0
,09-02 15:26:26.290  1019  1223 W ActivityManager: userId = 0, bbcId = -10000
09-02 15:26:26.290  1019  1223 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-02 15:26:26.290  1019  1223 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
09-02 15:26:26.290  3653  3653 I KLMS-2.5.183: : KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,09-02 15:26:26.300  3653  3653 I KLMS-2.5.183: : KLMSUtility(): isTestMode(): product_ship: true | testApk: false
,09-02 15:26:26.300   278   994 D EnterpriseController: uids 10012
09-02 15:26:26.300   278   994 D EnterpriseController: mIsMarkChainAdded is 18 mIsBlockChainAdded is 252 netId is 0
09-02 15:26:26.300   278   994 D Netd    : getNetworkForDns: using netid 503 for uid 10012
,09-02 15:26:26.310  6212  6212 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
09-02 15:26:26.310  1019  3109 D ActivityManager: startService callerProcessName:com.samsung.android.app.galaxyfinder, calleePkgName: com.samsung.android.app.galaxyfinder
09-02 15:26:26.310  1019  3109 W ActivityManager: userId = 0, bbcId = -10000
09-02 15:26:26.310  1019  3109 D ActivityManager: retrieveServiceLocked(): component = com.samsung.android.app.galaxyfinder/com.samsung.android.app.galaxyfinder.tag.LocationTagReadyService; callingUser = 0; userId(target) = 0
09-02 15:26:26.310  1019  3109 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-02 15:26:26.310  1019  3109 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.android.app.galaxyfinder, destAppInfo.processName = com.samsung.android.app.galaxyfinder
09-02 15:26:26.310  6212  6266 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
09-02 15:26:26.310  6212  6266 I jxcore-log: 
,09-02 15:26:26.320  3800  3800 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,09-02 15:26:26.320  7047  7047 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
,09-02 15:26:26.330  3800  4588 I iu.UploadsManager: num queued entries: 0
09-02 15:26:26.330  3800  4588 I iu.UploadsManager: num updated entries: 0
09-02 15:26:26.330  3800  4588 I iu.SyncManager: NEXT; no task
,09-02 15:26:26.330  3653  7057 I KLMS-2.5.183: : KLMSIntentService(): onHandleIntent().START: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.samsung.klmsagent/.services.KLMSIntentService (has extras) }
,09-02 15:26:26.330  3653  7057 I KLMS-2.5.183: : KLMSIntentService(): NETWORK_STATE_CHANGED_ACTION
,09-02 15:26:26.340  3653  7057 I KLMS-2.5.183: : KLMSUtility(): isNetworkAvailable() - WIFI : true| MOBILE : false| ETHERNET : false
,09-02 15:26:26.340  1019  2903 D PackageManager: START PACKAGE DELETE: observer{793268884}
09-02 15:26:26.340  1019  2903 D PackageManager: pkg{<packageName>}
09-02 15:26:26.340  1019  2903 D PackageManager: user{0}
09-02 15:26:26.340  1019  2903 D PackageManager: caller{2000}
09-02 15:26:26.340  1019  2903 D PackageManager: flags{2}
09-02 15:26:26.340  1019  2903 D PersonaManagerService: isFromApprovedUnInstaller: uid, userId, appid : 2000 0 2000
09-02 15:26:26.340  1019  2903 D PersonaManagerService: isFromApprovedUnInstaller: isApproved : true
09-02 15:26:26.340  1019  2903 D PersonaManagerService: isFromApprovedUnInstaller: isApproved before exit: true
09-02 15:26:26.340  1019  2903 D PackageManager: deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag2
09-02 15:26:26.340  1019  2903 D PackageManager: deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag2
,09-02 15:26:26.340  3653  7057 I KLMS-2.5.183: : StateImplV2(): networkChangeListener().START
,09-02 15:26:26.350  3653  7057 I KLMS-2.5.183: : NetworkChangeOperations(): uploadRequestLog().START 
09-02 15:26:26.350  1019  1061 D PackageManager: [MSG] DELETE_PACKAGE_AS_USER
09-02 15:26:26.350  1019  1061 D PackageManagerService: deletePackage- pkg:com.test.thalitest, edmuserId:0
09-02 15:26:26.350  1019  1061 D PackageManagerService: deletePackage- pkg:com.test.thalitest, edmuserId:-1
09-02 15:26:26.350  1019  1061 D ApplicationPolicy: getApplicationUninstallationEnabled
,09-02 15:26:26.350  1019  1061 D ApplicationPolicy: getApplicationUninstallationEnabled :  enabled true
,09-02 15:26:26.350  3653  7057 I KLMS-2.5.183: : NetworkChangeOperations(): uploadRequestLog().END 
,09-02 15:26:26.350  1019  1061 D PackageManager: !@killApplicatoin: 10155, uninstall pkg
09-02 15:26:26.360  3653  7057 I KLMS-2.5.183: : StateImplV2(): networkChangeListener().END
,09-02 15:26:26.360  3653  3653 I KLMS-2.5.183: : KLMSIntentService(): onDestroy()
,09-02 15:26:26.360  5980  5980 D WaitQueueForNetworkActivate: notifyNetworkActivated
,09-02 15:26:26.370  1019  1046 I ActivityManager: Force stopping com.test.thalitest appid=10155 user=-1: uninstall pkg
,09-02 15:26:26.370  1019  1046 I ActivityManager: Killing 6212:com.test.thalitest/u0a155 (adj 0): stop com.test.thalitest cause uninstall pkg
,09-02 15:26:26.370  1019  1046 I ActivityManager:   Force finishing activity ActivityRecord{b45515b u0 com.test.thalitest/.MainActivity t129}
,09-02 15:26:26.370  1019  1046 W ActivityManager: mDVFSHelper.acquire()
,09-02 15:26:26.490  3151  3151 I DBG_DM  : [com.wssyncmldm.ui.XUIInstallConfirmActivity(428/onResume)] 
,09-02 15:26:26.490  1019  1046 E JavaBinder: !!! FAILED BINDER TRANSACTION !!!
,09-02 15:26:26.500  3151  3151 I DBG_DM  : [com.wssyncmldm.db.file.XDB(5416/IlIlllIlllllIlIllllI)] Get Postpone Count : 6
,09-02 15:26:26.500  1019  1046 D InputDispatcher: Focus left window: 6212
,09-02 15:26:26.510  1019  1046 D InputDispatcher: Focused application released,
,09-02 15:26:26.510  1019  1032 I WindowState: WIN DEATH: Window{3ce993b u0 com.test.thalitest/com.test.thalitest.MainActivity}
09-02 15:26:26.510  1019  1051 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0,
09-02 15:26:26.510  1019  1032 E WindowState: getStack: Window{3ce993b u0 com.test.thalitest/com.test.thalitest.MainActivity} couldn't find taskId=129 Callers=com.android.server.wm.WindowState.getDisplayContent:1224 com.android.server.wm.WindowState.getWindowList:1991 com.android.server.wm.WindowManagerService.removeWindowInnerLocked:3693 com.android.server.wm.WindowManagerService.removeWindowLocked:3559 ,
09-02 15:26:26.510  1019  1051 D PointerIcon: setMouseCustomIcon IconType is same.101
09-02 15:26:26.510  1019  1032 E WindowState: getStack: Window{3ce993b u0 com.test.thalitest/com.test.thalitest.MainActivity} couldn't find taskId=129 Callers=com.android.server.wm.WindowState.getDisplayContent:1224 com.android.server.wm.WindowManagerService.removeWindowInnerLocked:3698 com.android.server.wm.WindowManagerService.removeWindowLocked:3559 com.android.server.wm.WindowState$DeathRecipient.binderDied:1650 
09-02 15:26:26.510  1019  1102 E InputDispatcher: Received spurious receive callback for unknown input channel.  fd=372, events=0x9
,09-02 15:26:26.510   258  1042 I SurfaceFlinger: id=14 Removed NainActivit (6/9)
09-02 15:26:26.510   258  1041 I SurfaceFlinger: id=14 Removed NainActivit (-2/9)
,09-02 15:26:26.510  6761  6761 D QuickConnect: PeriphStartReceiver.onReceive - android.net.conn.CONNECTIVITY_CHANGE,
09-02 15:26:26.510   258  1042 I SurfaceFlinger: id=14 Removed NainActivit (-2/9)
09-02 15:26:26.510  6761  6761 I QuickConnect: PeriphStartReceiver.onReceive - USER_OWNER care CONNECTIVITY_ACTION. run P service,
09-02 15:26:26.510  1883  7058 I qtaguid : Tagging socket 49 with tag 1000040700000000{268436487,0} for uid -1, pid: 1883, getuid(): 10012
09-02 15:26:26.520  6761  6761 I QuickConnect: PeriphStartReceiver.onReceive - no need to start
,09-02 15:26:26.520  3151  3151 I DBG_DM  : [com.wssyncmldm.db.file.XDB(5138/lIIIIIIIlllllllIIlll)] Get Priority : 0
,09-02 15:26:26.520  3217  7070 I DBG_POLICYDM: [com.sec.android.fota.common.Network(88/isWiFiNetworkConnected)] WiFi Network is connected
09-02 15:26:26.520  3217  7070 I DBG_POLICYDM: [com.policydm.XDMService(481/isNetworkChanged)] a previous network is 0, current network is 2
,09-02 15:26:26.520  3217  7070 E DBG_POLICYDM: [com.policydm.XDMService(483/isNetworkChanged)] network changed.... 
,09-02 15:26:26.520  1019  1061 I ActivityManager: Force stopping com.test.thalitest appid=10155 user=0: pkg removed,
,09-02 15:26:26.530  5840  5840 E SPPClientService: [[SystemStateMoniter]] SystemStateMonitorService : noConnect? : false,
,09-02 15:26:26.530  3151  3151 I DBG_DM  : [com.wssyncmldm.db.file.XDB(5438/llIIlIIlIllIllIlllII)] Get Postpone Max Count : 0
,09-02 15:26:26.530  3151  3151 I DBG_DM  : [com.wssyncmldm.ui.XUIInstallConfirmActivity(438/onResume)] Postpone Count : 6
,09-02 15:26:26.540  3151  3151 I DBG_DM  : [com.wssyncmldm.db.file.XDB(5479/llIlIIIIlllIlllllIll)] Download Postpone status : 0
,09-02 15:26:26.560  1019  1061 W ActivityManager: CustomStartingWindow se packge removed so remove capture also
,09-02 15:26:26.570  5656  5656 I art     : Explicit concurrent mark sweep GC freed 2328(137KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 749us total 33.447ms
,09-02 15:26:26.590  3217  7070 I DBG_POLICYDM: [com.policydm.XDMBroadcastReceiver(277/xdmExecResumeCase)] 
,09-02 15:26:26.590  3217  7070 I DBG_POLICYDM: [com.policydm.db.XDBFile(61/xdbFileExists)] doesn't exist target file: /data/security/sepolicy
,09-02 15:26:26.600  3217  7070 I DBG_POLICYDM: [com.policydm.db.XDBFile(61/xdbFileExists)] doesn't exist target file: /data/security/seapp_contexts
,09-02 15:26:26.600  3217  7070 I DBG_POLICYDM: [com.policydm.db.XDBFile(61/xdbFileExists)] doesn't exist target file: /data/security/property_contexts
,09-02 15:26:26.600  3217  7070 I DBG_POLICYDM: [com.policydm.db.XDBFile(61/xdbFileExists)] doesn't exist target file: /data/security/file_contexts
,09-02 15:26:26.600  3217  7070 I DBG_POLICYDM: [com.policydm.db.XDBFile(61/xdbFileExists)] doesn't exist target file: /data/security/service_contexts
,09-02 15:26:26.610  3217  7070 I DBG_POLICYDM: [com.policydm.db.XDBFile(61/xdbFileExists)] doesn't exist target file: /data/security/mac_permissions.xml
,09-02 15:26:26.610  3217  7070 I DBG_POLICYDM: [com.policydm.XDMBroadcastReceiver(294/xdmExecResumeCase)] Start resumecase for INIT
,09-02 15:26:26.620  3217  7070 E DBG_POLICYDM: [com.policydm.db.XDBSpdAdp(35/xdbGetSpdDeviceRegister)] Device is Registered
,09-02 15:26:26.630  5444  5444 I art     : Explicit concurrent mark sweep GC freed 399(27KB) AllocSpace objects, 0(0B) LOS objects, 24% free, 8MB/11MB, paused 23.069ms total 64.576ms
,09-02 15:26:26.640  3800  3800 I art     : Explicit concurrent mark sweep GC freed 23766(1440KB) AllocSpace objects, 3(48KB) LOS objects, 40% free, 15MB/26MB, paused 1.369ms total 87.516ms
,09-02 15:26:26.640  3217  7070 I DBG_POLICYDM: [com.sec.android.fota.common.Network(88/isWiFiNetworkConnected)] WiFi Network is connected
,09-02 15:26:26.670  1954  1954 E SamsungIME: mOCRHelper is null
,09-02 15:26:26.670  1019  1138 D ConnectivityService: NetTransition Wakelock (NetworkAgentInfo [WIFI () - 502] cleared because we found a replacement network
,09-02 15:26:26.670  1883  2114 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
,09-02 15:26:26.680  1019  1103 I InputReader: Reconfiguring input devices.  changes=0x00000010
,09-02 15:26:26.700  6044  6044 I SA      : [OR] onReceive log=[SA = 2.1.0240 V = 21 HWD = 1280X720 2.0 dpi = 320  SIZE = 2 LOCALE = en_US CSC = XEO MCC = 0 MNC 0 T = user DEVICE = a5ulte P = a5ultexx I = LRX22G M = SM-A500FU OKLEFT false DIS LRX22G.A500FUXXU1BOJ6 PSS = 4.978878039476607  ]
,09-02 15:26:26.700  6044  6044 I SA      : [OR] onReceive Intent=[ conn.CONNECTIVITY_CHANGE. networkInfo:[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] networkType:1 inetCondition:0 extraInfo:? isDefault:true ]
09-02 15:26:26.710  6044  6044 I SA      : [OR] == ACTION_CONNECTIVITY_CHANGE ==
,09-02 15:26:26.710  1019  1223 D ActivityManager: startService callerProcessName:com.sec.android.app.samsungapps, calleePkgName: com.sec.android.app.samsungapps
09-02 15:26:26.710  1019  1223 D ActivityManager: retrieveServiceLocked(): component = com.sec.android.app.samsungapps/com.sec.android.app.samsungapps.autoupdateservice.AutoUpdateService; callingUser = 0; userId(target) = 0
,09-02 15:26:26.720  1444  1444 D PersonaManager: isKioskContainerExistOnDevice
,09-02 15:26:26.720  1019  1223 W ActivityManager: userId = 0, bbcId = -10000
,09-02 15:26:26.720  1019  1223 W ActivityManager: NORMAL SET : dst_category = 1023, src_allowCategory = 0,701-1023
09-02 15:26:26.720  1019  1223 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.android.app.samsungapps, destAppInfo.processName = com.sec.android.app.samsungapps
09-02 15:26:26.720  6044  6044 I SA      : [TPMU]  strSIMState 	:SIM_STATE_ABSENT
09-02 15:26:26.720  6044  6044 I SA      : [OR] == isSIMCardReady false ==
,09-02 15:26:26.730  5980  5980 D hcjo    : AutoUpdateManager:IDLE:AutoUpdateManager::execute : false false true state: IDLE
,09-02 15:26:26.730  6044  6044 I SA      : [SCU] == networkStateCheck == true
,09-02 15:26:26.730  6044  6044 I SA      : [DM] getCountryCodeFromCSC : PL
09-02 15:26:26.730  6044  6044 I SA      : isChinaCountryCode : false
09-02 15:26:26.730  6044  6044 I SA      : [SCU] is ChinestModel Data Restricted   : false
09-02 15:26:26.730  6044  6044 I SA      : [OR] == networkStateCheck true ==
,09-02 15:26:26.740  3151  3151 I DBG_DM  : [com.wssyncmldm.XDMService(649/lllIlIlIIIllIIlIllIl)] Idle Screen : true
,09-02 15:26:26.740  1444  1444 D RegisteredServicesCache: empty dynamic service
,09-02 15:26:26.750  3151  3151 I DBG_DM  : [com.wssyncmldm.ui.lIlIIlIlIlIllllllIII(330/llIIIIlllllIIllIIllI)] NotificationID : 4 / Notification IndicatorState : 7
,09-02 15:26:26.750  5980  5980 D hcjo    : AutoUpdateManager:INITCHECK:AutoUpdateManager::checkInitialize
,09-02 15:26:26.750  5980  5980 D InitializeManagerStateMachine: execute::IDLE:EXECUTE
,09-02 15:26:26.750  5980  5980 D InitializeManagerStateMachine: exit::IDLE
09-02 15:26:26.750  5980  5980 D InitializeManagerStateMachine: entry::NETWORK_CHECK
,09-02 15:26:26.750  1019  1045 D EnterpriseDeviceManagerService: Package has changed for user 0
,09-02 15:26:26.750  1019  1045 D EnterpriseDeviceManagerService: Admin package name: com.google.android.gms
09-02 15:26:26.750  6044  6044 I SA      : [OR] GetMyCountryZoneTask
,09-02 15:26:26.750  6044  6044 I SA      : [OR] onReceive END
,09-02 15:26:26.750  5980  5980 D InitializeManagerStateMachine: execute::NETWORK_CHECK:NETWORK_STATE_OK
09-02 15:26:26.750  5980  5980 D InitializeManagerStateMachine: exit::NETWORK_CHECK
09-02 15:26:26.750  5980  5980 D InitializeManagerStateMachine: entry::CHECK_COUNTRY_INFO
09-02 15:26:26.750  5980  5980 D InitializeManagerStateMachine: execute::CHECK_COUNTRY_INFO:COUNTRY_INFO_OK
09-02 15:26:26.750  5980  5980 D InitializeManagerStateMachine: exit::CHECK_COUNTRY_INFO
09-02 15:26:26.750  5980  5980 D InitializeManagerStateMachine: entry::SUCCESS
09-02 15:26:26.750  5980  5980 D hcjo    : AutoUpdateManager:INITCHECK:onInitializeSuccess
,09-02 15:26:26.760  6044  7077 I SA      : [SRS] prepareGetMyCountryZone
,09-02 15:26:26.760  1019  1045 W TextServicesManagerService: no available spell checker services found
,09-02 15:26:26.760  1019  1129 V NetworkStats: removeUidsLocked() for UIDs [10155]
09-02 15:26:26.760  1019  1129 D NtpTrustedTime: currentTimeMillis() cache hit
09-02 15:26:26.760  1019  1129 V NetworkStats: performPollLocked(flags=0x3)
,09-02 15:26:26.760  1019  1129 D NetworkStatsFactory: UpdateStatsForKnox updated
09-02 15:26:26.760  1019  1129 D NetworkStatsFactory: UpdateStatsForKnox main else ---
,09-02 15:26:26.760  5980  5980 D hcjo    : AutoUpdateTriggerManager:IDLE:notifyNextTime
09-02 15:26:26.760  1019  1129 V NetworkStats: performPollLocked() took 6ms
09-02 15:26:26.760  1019  1129 D NtpTrustedTime: currentTimeMillis() cache hit
09-02 15:26:26.760  5980  5980 D hcjo    : AutoUpdateManager:UPD_CHECK_TIMING:onNoUpdateTime
,09-02 15:26:26.770  6044  7077 I SA      : [TPMU]  strSIMState 	:SIM_STATE_ABSENT
,09-02 15:26:26.770  5980  5980 D InitializeManagerStateMachine: exit::SUCCESS
09-02 15:26:26.770  5980  5980 D InitializeManagerStateMachine: entry::IDLE
,09-02 15:26:26.770  1235  1235 V DownloadManager: onReceive intent + android.net.conn.CONNECTIVITY_CHANGE
,09-02 15:26:26.780  6044  7077 I SA      : [SSP] query invoked
09-02 15:26:26.780  1019  3214 D SecContentProvider2: uri = 11 selection = getMyKnoxAdmin
09-02 15:26:26.780  1019  3214 D SecContentProvider2: mCursor = null
,09-02 15:26:26.790  1019  1485 D ActivityManager: startService callerProcessName:com.android.providers.media, calleePkgName: com.android.providers.downloads
09-02 15:26:26.790  1019  1485 D ActivityManager: retrieveServiceLocked(): component = com.android.providers.downloads/com.android.providers.downloads.DownloadService; callingUser = 0; userId(target) = 0
,09-02 15:26:26.790  1019  1485 W ActivityManager: userId = 0, bbcId = -10000
09-02 15:26:26.790  1019  1485 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,09-02 15:26:26.790  6044  7077 I SA      : [TPMU] GetMccFromDB : null
09-02 15:26:26.790  6044  7077 I SA      : [SCU] getMccFromPreferece mcc = 260
09-02 15:26:26.790  6044  7077 I SA      : [LBE] isSupportCheckDomainRegion : false
,09-02 15:26:26.790  6044  7077 I SA      : [TPM] isNoProxy(default) : true
,09-02 15:26:26.790  1019  1485 W ActivityManager: NORMAL SET : srcAppInfo.processName = android.process.media, destAppInfo.processName = android.process.media
,09-02 15:26:26.800  6044  7077 E File    : fail readDirectory() errno=2
,09-02 15:26:26.800  1019  1045 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,09-02 15:26:26.810  1019  1019 D RCPManagerService: PackageReceiver onReceive()
,09-02 15:26:26.820  1019  1019 I HarmonyEASService: onReceive : android.intent.action.PACKAGE_REMOVED for 0
,09-02 15:26:26.820  1444  1444 D RegisteredComponentCache: Collect Tech packages for Knox
09-02 15:26:26.820  3151  3151 I DBG_DM  : [com.wssyncmldm.db.file.XDB(5138/lIIIIIIIlllllllIIlll)] Get Priority : 0
,09-02 15:26:26.820  1444  1444 D PersonaManager: isKioskContainerExistOnDevice
,09-02 15:26:26.840  1019  1019 D KnoxMUMContainerPolicy: mPackageReceiver : action - android.intent.action.PACKAGE_REMOVED
,09-02 15:26:26.840  1019  1019 I OTPFW   : PackageRemovalReceiver::onReceive Enter
,09-02 15:26:26.840  1019  1045 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,09-02 15:26:26.840  1019  3213 D ApplicationPolicy: isStatusBarNotificationAllowedAsUser: packageName = com.wssyncmldm,userId = 0
,09-02 15:26:26.840  1019  3213 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.wssyncmldm
,09-02 15:26:26.840  1019  1019 D OTPFW   : OtpDbHelper::getInstance New instance created
,09-02 15:26:26.840  1019  1019 D OTPFW   : DBIntegrity::getInstance - New instance created
,09-02 15:26:26.850  3151  3151 I DBG_DM  : [com.wssyncmldm.db.file.XDB(5416/IlIlllIlllllIlIllllI)] Get Postpone Count : 6
,09-02 15:26:26.860  1019  1031 I splitIntent: Queue : background intent android.net.conn.CONNECTIVITY_CHANGE is finished at BG and BG split queue. set mSplitStart  false.
,09-02 15:26:26.860  1019  1130 D NtpTrustedTime: currentTimeMillis() cache hit
,09-02 15:26:26.860  1019  1019 D OTPFW   : PackageRemovalReceiver::onReceive deleting token for Pkg = com.test.thalitest uid = 10155 container id = 0
,09-02 15:26:26.860  1019  1130 D NtpTrustedTime: currentTimeMillis() cache hit
,09-02 15:26:26.860  1019  1322 D SecContentProvider2: uri = 15 selection = getAppBlockDownloadState
,09-02 15:26:26.860  1019  1322 D SecContentProvider2: mCursor = null
,09-02 15:26:26.870  3151  3151 I DBG_DM  : [com.wssyncmldm.db.file.XDB(5058/IIlllIlIIlIllIlllIll)] Get Force status : 0
,09-02 15:26:26.870  1019  1045 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,09-02 15:26:26.870  3151  3151 I DBG_DM  : [com.wssyncmldm.db.file.XDB(5438/llIIlIIlIllIllIlllII)] Get Postpone Max Count : 0
,09-02 15:26:26.880  3151  3151 I DBG_DM  : [com.wssyncmldm.ui.XUIInstallConfirmActivity(532/llIIIIlllllIIllIIllI)] Check Force Install : false
,09-02 15:26:26.880  3151  3151 I DBG_DM  : [llIIlIIlIllIllIlllII(329/IllIlIIIIlIIlIIIllIl)] 
,09-02 15:26:26.880  3151  3151 I DBG_DM  : [llIIlIIlIllIllIlllII(335/IllIlIIIIlIIlIIIllIl)] InternalEncrypted : [false]
,09-02 15:26:26.880  1019  1019 I OTPFW   : ProvisionData::getAllEntries Enter
,09-02 15:26:26.880  1019  1485 D ActivityManager: post active user change for 0 fullscreen true record.isFloatingActivity() false
,09-02 15:26:26.880  1019  1485 D KnoxTimeoutHandler: postActiveUserChange for user 0
,09-02 15:26:26.880  1019  1485 I KnoxTimeoutHandler: postActiveUserChange, showWhenLocked: false
,09-02 15:26:26.890  1019  1019 E OTPFW   : ProvisionData::getAllEntries Table is empty
,09-02 15:26:26.890  1019  1046 W ActivityManager: Activity pause timeout for ActivityRecord{3e9fd217 u0 com.wssyncmldm/.ui.XUIInstallConfirmActivity t127}
,09-02 15:26:26.890  1019  1019 D BackupManagerService: Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
,09-02 15:26:26.890  1019  1019 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
09-02 15:26:26.890  1019  1019 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - start - android.intent.action.PACKAGE_REMOVED
09-02 15:26:26.890  1019  1019 V EnterpriseBillingPolicy: uID is 10155
09-02 15:26:26.890  1019  1019 V EnterpriseBillingPolicy: Removed Packageuid is0
09-02 15:26:26.890  1019  1019 V EnterpriseBillingPolicyStorage: getProfileForApplication - enter
,09-02 15:26:26.890  1019  1019 V EnterpriseBillingPolicyStorage: getProfileForApplication - exit null : containerId = 0
09-02 15:26:26.890  1019  1019 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - personal application - profile null
,09-02 15:26:26.890  1019  1019 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - might be a vpn vendor package 
,09-02 15:26:26.890  1019  1019 V EnterpriseBillingPolicyStorage: getBillingProfileForVpnEngine - start - com.test.thalitest
,09-02 15:26:26.890  1019  1019 V EnterpriseBillingPolicyStorage: getBillingProfileForVpnEngine - end - null
,09-02 15:26:26.890  3653  3653 I KLMS-2.5.183: : KLMSAbstractReciever(): onReceive(): Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.samsung.klmsagent/.listner.MainReciver (has extras) } | timestamp: Fri Sep 02 15:26:26 GMT+02:00 2016,
,09-02 15:26:26.900  1019  1019 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
,09-02 15:26:26.900  1019  1019 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - start - android.intent.action.PACKAGE_FULLY_REMOVED
09-02 15:26:26.900  1019  1019 V EnterpriseBillingPolicy: uID is 10155
09-02 15:26:26.900  1019  1019 V EnterpriseBillingPolicy: Removed Packageuid is0
09-02 15:26:26.900  1019  1019 V EnterpriseBillingPolicyStorage: getProfileForApplication - enter
,09-02 15:26:26.900  1019  2713 D SSRM:bc : MSG_TYPE_APP_REMOVED::
09-02 15:26:26.900  1019  1019 V EnterpriseBillingPolicyStorage: getProfileForApplication - exit null : containerId = 0
09-02 15:26:26.900  1019  1019 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - personal application - profile null
09-02 15:26:26.900  1019  1019 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - might be a vpn vendor package 
09-02 15:26:26.900  1019  1019 V EnterpriseBillingPolicyStorage: getBillingProfileForVpnEngine - start - com.test.thalitest
,09-02 15:26:26.900  1019  1019 V EnterpriseBillingPolicyStorage: getBillingProfileForVpnEngine - end - null
,09-02 15:26:26.900  3151  3151 I DBG_DM  : [com.wssyncmldm.ui.XUIInstallConfirmActivity(420/onPause)] 
,09-02 15:26:26.900  1019  1019 V AlarmManagerEXT: com.test.thalitest(10155) is removed.
,09-02 15:26:26.910  1019  3109 D ActivityManager: startService callerProcessName:com.samsung.klmsagent, calleePkgName: com.samsung.klmsagent
,09-02 15:26:26.910  1019  3109 D ActivityManager: retrieveServiceLocked(): component = com.samsung.klmsagent/com.samsung.klmsagent.services.KLMSIntentService; callingUser = 0; userId(target) = 0
,09-02 15:26:26.920  1019  3109 W ActivityManager: userId = 0, bbcId = -10000
,09-02 15:26:26.920  1019  3109 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,09-02 15:26:26.920  1019  3109 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.klmsagent, destAppInfo.processName = com.samsung.klmsagent
,09-02 15:26:26.920  1019  1165 D TaskPersister: removeObsoleteFile: deleting file=127_task.xml
,09-02 15:26:26.930  1019  1165 D TaskPersister: removeObsoleteFile: deleting file=129_task.xml
,09-02 15:26:26.930   258   258 I SurfaceFlinger: id=16 createSurf (720x1280),1 flag=404, YUIInstallC
,09-02 15:26:26.930  1019  1049 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
,09-02 15:26:26.930  1019  3213 D InputDispatcher: Focus entered window: 3151
,09-02 15:26:26.940  1019  1051 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
,09-02 15:26:26.940  1019  1019 W NotificationService: Pray mode not found android.content.pm.PackageManager$NameNotFoundException: Application package com.sec.android.settings.praymodewidget not found
09-02 15:26:26.940  1019  1019 D KnoxTimeoutHandler: handleActiveUserChange for user 0
09-02 15:26:26.940  1019  1019 D PersonaManagerService: getPersonasForUser(): returning null!
,09-02 15:26:26.940  1019  1051 D PointerIcon: setMouseCustomIcon IconType is same.101
,09-02 15:26:26.940  3151  3151 D SRIB_DCS: log_dcs ThreadedRenderer::initialize entered! 
,09-02 15:26:26.940  3653  3653 I KLMS-2.5.183: : KLMSAbstractReciever(): onReceive().END.
,09-02 15:26:26.950  1019  1485 I splitIntent: Split this intent : android.intent.action.PACKAGE_REMOVED, mSplitNum[0]=12, mSplitNum[1]=21, mSplitNum[2]=34, mBgSplitQueueNum=3 divideNum= 10 r.nextReceiver= 1 receivers.size=44
09-02 15:26:26.950  1019  1485 I splitIntent: finish to split intent : android.intent.action.PACKAGE_REMOVED !! Enqueue -> schedule it!!
,09-02 15:26:26.950  1019  1485 D ActivityManager: startProcessLocked calleePkgName: com.sec.esdk.elm, hostingType: broadcast
,09-02 15:26:26.950  3151  3151 V ActivityThread: updateVisibility : ActivityRecord{1b076e55 token=android.os.BinderProxy@d67f290 {com.wssyncmldm/com.wssyncmldm.ui.XUIInstallConfirmActivity}} show : true
,09-02 15:26:26.950  1019  2905 D InputMethodManagerService: windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,09-02 15:26:26.950  1019  1485 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-02 15:26:26.950  1019  1485 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-02 15:26:26.950  1019  1485 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-02 15:26:26.950  1019  1485 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-02 15:26:26.960  1182  1182 D PanelView: There is/are notification(s) 
,09-02 15:26:26.960  1019  2905 W InputMethodManagerService: Got RemoteException sending setActive(false) notification to pid 6212 uid 10155
09-02 15:26:26.960  1182  1182 D StatusBar: ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
09-02 15:26:26.960  1182  1182 D PersonaManager: isKioskContainerExistOnDevice
09-02 15:26:26.960  1182  1182 D PersonaManager: isKioskContainerExistOnDevice
09-02 15:26:26.960  1182  1182 D PanelView: There is/are notification(s) 
,09-02 15:26:26.960  1182  1182 D PanelView: kidsfalse mQsExpansionEnabled:true
09-02 15:26:26.960  1182  1182 D PersonaManager: isKioskContainerExistOnDevice
09-02 15:26:26.960  1182  1182 D PanelView: There is/are notification(s) 
09-02 15:26:26.960  1182  1182 D PanelView: kidsfalse mQsExpansionEnabled:true
,09-02 15:26:26.970  3653  3653 I KLMS-2.5.183: : KLMSIntentService(): onCreate()
,09-02 15:26:26.980  1019  7083 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.android.server.InputMethodManagerService$6.run:2762 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> ,
09-02 15:26:26.980  3653  3653 I KLMS-2.5.183: : KLMSSystemProperties(): getBoolean(): ro.product_ship = true,
09-02 15:26:26.980  3653  3653 I KLMS-2.5.183: : KLMSUtility(): isTestMode(): product_ship: true | testApk: false
,09-02 15:26:26.980  7085  7085 E Zygote  : MountEmulatedStorage()
09-02 15:26:26.980  7085  7085 E Zygote  : v2
09-02 15:26:26.980  3653  7082 I KLMS-2.5.183: : KLMSIntentService(): onHandleIntent().START: Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.samsung.klmsagent/.services.KLMSIntentService (has extras) }
,09-02 15:26:26.980  7085  7085 I libpersona: KNOX_SDCARD checking this for 10094
09-02 15:26:26.980  7085  7085 I libpersona: KNOX_SDCARD not a persona
,09-02 15:26:26.980  3653  7082 I KLMS-2.5.183: : KLMSIntentService(): PACKAGE_REMOVED
,09-02 15:26:26.980  1019  1485 I ActivityManager: Start proc com.sec.esdk.elm for broadcast com.sec.esdk.elm/.receiver.MainReceiver: pid=7085 uid=10094 gids={50094, 9997, 3003} abi=armeabi-v7a,
,09-02 15:26:26.990  1954  1954 D SamsungIME: onStartInput: No inputType, No imeOption, isInputViewShown = false, isExtractViewShown = false, isShowInputRequested = false, isConfigChanged = false
,09-02 15:26:26.990  7085  7085 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51
,09-02 15:26:26.990  7085  7085 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051
09-02 15:26:26.990  7085  7085 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
09-02 15:26:27.000  1019  1061 W art     : Suspending all threads took: 5.139ms
,09-02 15:26:27.000  3653  7082 I KLMS-2.5.183: : KLMSIntentService(): listeningToPackageRemoved().START
,09-02 15:26:27.000  1019  1046 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.gallery3d, hostingType: broadcast
,09-02 15:26:27.010  3653  7082 I KLMS-2.5.183: : KLMSIntentService(): REPLACING: false | pkgName: com.test.thalitest
,09-02 15:26:27.010  3151  3151 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@d67f290 time:155786
,09-02 15:26:27.010  1019  1046 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-02 15:26:27.010  1019  1046 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-02 15:26:27.010  1019  1046 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-02 15:26:27.010  1019  1046 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-02 15:26:27.030  1182  1182 D PanelView: mClearAll.setVisibility - mIsFullyOpened : false isShade : true mHasNotification : true mIsUpwardFling : false mQsFullyExpanded : true isShadeLocked : false mClearAllVisible : false
09-02 15:26:27.030  1019  1046 I ActivityManager: Start proc com.sec.android.gallery3d for broadcast com.sec.android.gallery3d/.app.PackagesMonitor: pid=7099 uid=10044 gids={50044, 9997, 3003, 1028, 1015, 1023, 3002} abi=armeabi-v7a
,09-02 15:26:27.040  7099  7099 E Zygote  : MountEmulatedStorage()
09-02 15:26:27.040  7099  7099 I libpersona: KNOX_SDCARD checking this for 10044
09-02 15:26:27.040  7099  7099 E Zygote  : v2
09-02 15:26:27.040  7099  7099 I libpersona: KNOX_SDCARD not a persona
09-02 15:26:27.040  7099  7099 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51
,09-02 15:26:27.040  7099  7099 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051
09-02 15:26:27.040  7099  7099 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,09-02 15:26:27.050  1019  1046 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.app.themechooser, hostingType: broadcast
,09-02 15:26:27.050  7085  7085 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-02 15:26:27.050  7085  7085 D ActivityThread: Added TimaKeyStore provider
,09-02 15:26:27.050  1019  1045 W ResourceType: Failure getting entry for 0x7f07007b (t=6 e=123) (error -75)
,09-02 15:26:27.060  1019  1046 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-02 15:26:27.060  1019  1046 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-02 15:26:27.060  1019  1046 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-02 15:26:27.060  1019  1046 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-02 15:26:27.060  1019  1045 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,09-02 15:26:27.060  1019  1045 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,09-02 15:26:27.070  7114  7114 E Zygote  : MountEmulatedStorage()
,09-02 15:26:27.070  7114  7114 E Zygote  : v2
09-02 15:26:27.070  7114  7114 I libpersona: KNOX_SDCARD checking this for 10149
,09-02 15:26:27.070  1019  1046 I ActivityManager: Start proc com.sec.android.app.themechooser for broadcast com.sec.android.app.themechooser/.CustomBroadCastReceiver: pid=7114 uid=10149 gids={50149, 9997, 3003, 1028, 1015} abi=armeabi-v7a
09-02 15:26:27.070  7114  7114 I libpersona: KNOX_SDCARD not a persona
09-02 15:26:27.070  7114  7114 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51
09-02 15:26:27.070  1019  1045 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,09-02 15:26:27.080  7114  7114 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051,
,09-02 15:26:27.080  7114  7114 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,09-02 15:26:27.080  7099  7099 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-02 15:26:27.090  7099  7099 D ActivityThread: Added TimaKeyStore provider
,09-02 15:26:27.090  3653  7082 I KLMS-2.5.183: : KLMSIntentService(): Notification App List is Null. Remove Notification.
,09-02 15:26:27.090  1019  1045 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
09-02 15:26:27.090  1019  1045 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
09-02 15:26:27.090  1019  1045 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,09-02 15:26:27.090  1019  1045 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,09-02 15:26:27.100  6868  7107 E SQLiteLog: (284) automatic index on crash_info_summary(package_name_touched)
,09-02 15:26:27.110  3653  7082 I KLMS-2.5.183: : KLMSValidator(): IsPackageExistInDevice().Not Exsit: com.test.thalitest
,09-02 15:26:27.110  1019  1061 I art     : Explicit concurrent mark sweep GC freed 83500(5MB) AllocSpace objects, 12(192KB) LOS objects, 33% free, 28MB/42MB, paused 10.636ms total 394.979ms
,09-02 15:26:27.110  3653  7082 I KLMS-2.5.183: : KLMSIntentService(): listeningToPackageRemoved().END
,09-02 15:26:27.130  7114  7114 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-02 15:26:27.130  7114  7114 D ActivityThread: Added TimaKeyStore provider
,09-02 15:26:27.140  1019  1051 W ActivityManager: mDVFSHelper.release()
09-02 15:26:27.140  1019  1051 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{3e9fd217 u0 com.wssyncmldm/.ui.XUIInstallConfirmActivity t127} time:155910
,09-02 15:26:27.140  3653  3653 I KLMS-2.5.183: : KLMSIntentService(): onDestroy()
,09-02 15:26:27.150  7099  7099 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
,09-02 15:26:27.150  7099  7099 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
09-02 15:26:27.150  7099  7099 W ResourcesManager: Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
09-02 15:26:27.150  7099  7099 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
09-02 15:26:27.150  7099  7099 W ResourcesManager: Asset path '/system/framework/secimaging.jar' does not exist or contains no resources.
,09-02 15:26:27.150  7099  7099 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
09-02 15:26:27.150  7099  7099 W ResourcesManager: Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
09-02 15:26:27.150  7099  7099 W ResourcesManager: Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,09-02 15:26:27.160  1019  1138 D ConnectivityService: updateLinkProperties: newLp = {InterfaceName: wlan0 LinkAddresses: [192.168.1.111/24,fe80::7ef9:eff:fe37:96ac/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}, oldLp = {InterfaceName: wlan0 LinkAddresses: [192.168.1.111/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
09-02 15:26:27.160  1019  1138 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 503]
,09-02 15:26:27.160  1019  1138 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 503]
,09-02 15:26:27.170  3800  6269 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524295
,09-02 15:26:27.170  1182  1698 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524295
,09-02 15:26:27.170  1182  1698 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524295
,09-02 15:26:27.170  3800  6269 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524295
,09-02 15:26:27.190  7085  7085 D elm:15183: ELMAbstractReceiver.onReceive() : Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.receiver.MainReceiver (has extras) }
,09-02 15:26:27.190  7085  7085 D elm:15183: ELMEngine.ELMEngine( context ).
,09-02 15:26:27.190  7085  7085 D elm:15183: MDMBridge.setEnterpriseBridge()
,09-02 15:26:27.200  1019  1032 D ActivityManager: startService callerProcessName:com.sec.esdk.elm, calleePkgName: com.sec.esdk.elm
,09-02 15:26:27.200  1019  1032 D ActivityManager: retrieveServiceLocked(): component = com.sec.esdk.elm/com.sec.esdk.elm.service.ElmAgentService; callingUser = 0; userId(target) = 0
,09-02 15:26:27.200  1019  1032 W ActivityManager: userId = 0, bbcId = -10000
,09-02 15:26:27.200  1019  1032 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-02 15:26:27.200  1019  1032 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.esdk.elm, destAppInfo.processName = com.sec.esdk.elm
,09-02 15:26:27.200  1019  1061 D PackageManager: delete codoeFile: 
,09-02 15:26:27.200  1019  1223 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.app.assistantmenu, hostingType: broadcast
,09-02 15:26:27.200  1019  1223 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-02 15:26:27.200  1019  1223 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-02 15:26:27.200  1019  1223 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-02 15:26:27.200  1019  1223 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-02 15:26:27.200  7085  7085 D elm:15183: ELMAbstractReceiver : Receive Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) } END.
,09-02 15:26:27.220  7134  7134 E Zygote  : MountEmulatedStorage(),
09-02 15:26:27.220  7134  7134 E Zygote  : v2
09-02 15:26:27.220  7134  7134 I libpersona: KNOX_SDCARD checking this for 1000
09-02 15:26:27.220  7134  7134 I libpersona: KNOX_SDCARD not a persona
09-02 15:26:27.220  1019  1061 I AASA_removePackage: UID=10155 Target=com.test.thalitest
,09-02 15:26:27.220  1019  1061 D AASAuninstall: userId = 0, info.removedAppID = 10155, info.uid = 10155, packageName = com.test.thalitest
09-02 15:26:27.220  7134  7134 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51
,09-02 15:26:27.220  1019  1061 D PackageManager: result of delete: 1{793268884},
,09-02 15:26:27.220  7134  7134 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051
,09-02 15:26:27.220  7134  7134 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
09-02 15:26:27.220  1019  1223 I ActivityManager: Start proc com.samsung.android.app.assistantmenu for broadcast com.samsung.android.app.assistantmenu/.AssistantMenuReceiver: pid=7134 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
,09-02 15:26:27.230  3361  3361 D AASAservice-UpdateReceiver: AASAUpdateReceiver: android.intent.action.PACKAGE_REMOVED, package = com.test.thalitest, uid = -1
,09-02 15:26:27.230  3361  3361 W System.err: android.content.pm.PackageManager$NameNotFoundException: com.test.thalitest
09-02 15:26:27.230  3361  3361 W System.err: 	at android.app.ApplicationPackageManager.getApplicationInfo(ApplicationPackageManager.java:332)
09-02 15:26:27.230  3361  3361 W System.err: 	at com.samsung.aasaservice.AASAUpdateReceiver.onReceive(AASAUpdateReceiver.java:33)
09-02 15:26:27.230  3361  3361 W System.err: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:3125)
09-02 15:26:27.230  3361  3361 W System.err: 	at android.app.ActivityThread.access$1800(ActivityThread.java:181)
09-02 15:26:27.230  3361  3361 W System.err: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1559)
09-02 15:26:27.230  3361  3361 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-02 15:26:27.230  3361  3361 W System.err: 	at android.os.Looper.loop(Looper.java:145)
09-02 15:26:27.230  3361  3361 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
09-02 15:26:27.230  3361  3361 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
09-02 15:26:27.230  3361  3361 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
09-02 15:26:27.230  3361  3361 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
09-02 15:26:27.230  3361  3361 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
,09-02 15:26:27.230  6868  7107 W art     : Suspending all threads took: 18.687ms
,09-02 15:26:27.240  7047  7047 D AndroidRuntime: Shutting down VM
,09-02 15:26:27.240  7085  7085 D elm:15183: ElmAgentService : onCreate()
,09-02 15:26:27.240  6868  7107 I art     : Explicit concurrent mark sweep GC freed 1093(69KB) AllocSpace objects, 0(0B) LOS objects, 24% free, 6MB/9MB, paused 25.638ms total 107.388ms
,09-02 15:26:27.240  7085  7133 D elm:15183: ElmAgentService : onHandleIntent() Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) }
,09-02 15:26:27.240  7085  7133 D elm:15183: MainReceiver.listeningToPackageRemoved()
09-02 15:26:27.240  7085  7133 D elm:15183: MDMBridge.getInstance()
09-02 15:26:27.240  7085  7133 D elm:15183: MDMBridge.getAllLicenseInfoFromSDK()
,09-02 15:26:27.250  7134  7134 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-02 15:26:27.250  7134  7134 D ActivityThread: Added TimaKeyStore provider
,09-02 15:26:27.250  7085  7133 D elm:15183: MDMBridge.getAllLicenseInfoFromSDK()
,09-02 15:26:27.250  7114  7114 D ThemeInfoUtil: getCurrentFestivalName is [null]
09-02 15:26:27.250  7114  7114 D ThemeInfoUtil: isCurrentFestival = false
,09-02 15:26:27.260  1019  3213 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.provider.shootingmodeprovider, hostingType: broadcast
,09-02 15:26:27.270  1019  3213 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-02 15:26:27.270  1019  3213 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-02 15:26:27.270  1019  3213 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-02 15:26:27.270  1019  3213 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-02 15:26:27.270  6515  6515 I PCWCLIENTTRACE_PushUtil: SPPPushClient is installed : true
09-02 15:26:27.270  6515  6515 I PCWCLIENTTRACE_PushUtil: sales region : global
09-02 15:26:27.270  6515  6515 I PCWCLIENTTRACE_PushUtil: getPushTypeList : [SPP, GCM]
09-02 15:26:27.270  6515  6515 I PCWCLIENTTRACE_SYSTEMReceiver: [onReceive] - android.intent.action.PACKAGE_REMOVED
,09-02 15:26:27.270  1019  1045 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,09-02 15:26:27.280  1019  1045 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,09-02 15:26:27.280  7151  7151 E Zygote  : MountEmulatedStorage(),
09-02 15:26:27.280  7151  7151 E Zygote  : v2
09-02 15:26:27.280  7151  7151 I libpersona: KNOX_SDCARD checking this for 10152
09-02 15:26:27.280  7151  7151 I libpersona: KNOX_SDCARD not a persona,
09-02 15:26:27.280  7151  7151 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51,
09-02 15:26:27.280  1019  3213 I ActivityManager: Start proc com.samsung.android.provider.shootingmodeprovider for broadcast com.samsung.android.provider.shootingmodeprovider/com.samsung.android.app.shootingmodeinstaller.PackageIntentReceiver: pid=7151 uid=10152 gids={50152, 9997, 1023} abi=armeabi-v7a
,09-02 15:26:27.290  7151  7151 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051
,09-02 15:26:27.290  7151  7151 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
09-02 15:26:27.290  1019  1045 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
09-02 15:26:27.290  1019  3213 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.app.galaxyfinder, hostingType: broadcast
09-02 15:26:27.290  1019  1045 W Resources: Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
09-02 15:26:27.290  1019  3213 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-02 15:26:27.290  1019  3213 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-02 15:26:27.290  1019  3213 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-02 15:26:27.290  1019  3213 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-02 15:26:27.290  1019  1045 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
09-02 15:26:27.290  1019  1045 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
09-02 15:26:27.290  1019  1045 W Resources: Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,09-02 15:26:27.300  1019  1045 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1},
09-02 15:26:27.300  1019  1045 W Resources: Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,09-02 15:26:27.300  1019  1045 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1},
,09-02 15:26:27.310  7162  7162 E Zygote  : MountEmulatedStorage(),
09-02 15:26:27.310  7162  7162 E Zygote  : v2,
09-02 15:26:27.310  7162  7162 I libpersona: KNOX_SDCARD checking this for 10032,
,09-02 15:26:27.310  7162  7162 I libpersona: KNOX_SDCARD not a persona
,09-02 15:26:27.310  7162  7162 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51
09-02 15:26:27.310  1019  3213 I ActivityManager: Start proc com.samsung.android.app.galaxyfinder for broadcast com.samsung.android.app.galaxyfinder/.ApplicationStatusReceiver: pid=7162 uid=10032 gids={50032, 9997, 1028, 1015, 3003, 3002} abi=armeabi-v7a
,09-02 15:26:27.310  7162  7162 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051
,09-02 15:26:27.320  7162  7162 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,09-02 15:26:27.320  7085  7085 D elm:15183: ElmAgentService : onDestroy().
,09-02 15:26:27.330  1019  1045 D UsbSettingsManager: clearDefaults: com.test.thalitest
,09-02 15:26:27.330  1019  1223 I ActivityManager: Killing 5444:com.google.android.googlequicksearchbox:search/u0a57 (adj 15): empty #31
,09-02 15:26:27.330  1019  1045 I CrashAnrDetector: onPackageRemoved : com.test.thalitest
,09-02 15:26:27.340  5929  5940 D BadgeProvider: sendNotify entered. [uri] : content://com.sec.badge/apps
09-02 15:26:27.340  5929  5940 D BadgeProvider: sendNotify, [notify] : null
09-02 15:26:27.340  5929  5940 D BadgeProvider: update, [uri] : content://com.sec.badge/apps
09-02 15:26:27.340  5929  5940 D BadgeProvider: update, [BadgeCount] : badgecount=0
09-02 15:26:27.340  5929  5940 D BadgeProvider: update, [UpdateCount] : 1
,09-02 15:26:27.340  7162  7162 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-02 15:26:27.340  7162  7162 D ActivityThread: Added TimaKeyStore provider
,09-02 15:26:27.350  7151  7151 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-02 15:26:27.350  7151  7151 D ActivityThread: Added TimaKeyStore provider
,09-02 15:26:27.350  7134  7134 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.samsung.android.app.assistantmenu.AssistantMenuReceiver.onReceive:159 android.app.ActivityThread.handleReceiver:3125 
,09-02 15:26:27.360  1019  1322 D ActivityManager: startService callerProcessName:com.samsung.android.app.assistantmenu, calleePkgName: com.samsung.android.app.assistantmenu
09-02 15:26:27.360  1019  1322 D ActivityManager: retrieveServiceLocked(): component = com.samsung.android.app.assistantmenu/com.samsung.android.app.assistantmenu.serviceframework.AMMetaDataParserService; callingUser = 0; userId(target) = 0
,09-02 15:26:27.360  1019  1322 W ActivityManager: userId = 0, bbcId = -10000
09-02 15:26:27.360  1019  1322 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-02 15:26:27.360  1019  1322 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.android.app.assistantmenu, destAppInfo.processName = com.samsung.android.app.assistantmenu
,09-02 15:26:27.370  1019  3213 D ActivityManager: startProcessLocked calleePkgName: com.sec.knox.bridge, hostingType: broadcast
,09-02 15:26:27.370  1019  3213 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-02 15:26:27.370  1019  3213 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-02 15:26:27.370  1019  3213 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-02 15:26:27.370  1019  3213 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-02 15:26:27.390  1019  3213 I ActivityManager: Start proc com.sec.knox.bridge for broadcast com.sec.knox.bridge/.PersonaShortcutReceiver: pid=7183 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
,09-02 15:26:27.400  7183  7183 E Zygote  : MountEmulatedStorage()
09-02 15:26:27.400  7183  7183 I libpersona: KNOX_SDCARD checking this for 1000
09-02 15:26:27.400  7183  7183 E Zygote  : v2
09-02 15:26:27.400  7183  7183 I libpersona: KNOX_SDCARD not a persona
09-02 15:26:27.400  7183  7183 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51
,09-02 15:26:27.400  7183  7183 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051
,09-02 15:26:27.400  7183  7183 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,09-02 15:26:27.400  1019  1032 D PersonaManager: isKioskContainerExistOnDevice
,09-02 15:26:27.410  1019  2905 I ActivityManager: Killing 6146:com.google.android.gms:car/u0a12 (adj 15): empty #31
,09-02 15:26:27.430  7183  7183 D TimaKeyStoreProvider: TimaSignature is unavailable
09-02 15:26:27.430  7183  7183 D ActivityThread: Added TimaKeyStore provider
09-02 15:26:27.440  7099  7099 D NearbySource: Nearby Source Create!
09-02 15:26:27.440  7099  7099 D NearbyContext: Nearby Context Create!
,09-02 15:26:27.440  7162  7195 I FeatureConfig: init() refresh[false], Select[false], DisplayOrder[false], HelpMenu[false]
,09-02 15:26:27.450  7047  7047 W art     : ConditionVariable::~ConditionVariable for GC request condition variable called with 1 waiters.
,09-02 15:26:27.460  7151  7151 E SQLiteLog: (284) automatic index on shooting_modes(title_id),
09-02 15:26:27.460  1019  1032 D ActivityManager: startProcessLocked calleePkgName: com.sec.spp.push, hostingType: broadcast
09-02 15:26:27.460  1019  1032 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-02 15:26:27.460  1019  1032 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-02 15:26:27.460  1019  1032 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-02 15:26:27.460  1019  1032 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-02 15:26:27.490  7200  7200 E Zygote  : MountEmulatedStorage()
09-02 15:26:27.490  7200  7200 E Zygote  : v2
09-02 15:26:27.490  7200  7200 I libpersona: KNOX_SDCARD checking this for 10035
09-02 15:26:27.490  7200  7200 I libpersona: KNOX_SDCARD not a persona
09-02 15:26:27.490  7200  7200 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51
,09-02 15:26:27.490  1019  1032 I ActivityManager: Start proc com.sec.spp.push:RemoteNotiProcess for broadcast com.sec.spp.push/.notisvc.registration.PackageRemovedReceiver: pid=7200 uid=10035 gids={50035, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,09-02 15:26:27.490  1019  1032 I ActivityManager: Killing 5719:com.android.defcontainer/u0a4 (adj 15): empty #31
,09-02 15:26:27.490  7200  7200 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051
,09-02 15:26:27.500  7200  7200 E SELinux : [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
09-02 15:26:27.500   257   526 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.sec.android.gallery3d/cache/
09-02 15:26:27.500   257   526 W Vold    : Returning OperationFailed - no handler for errno 0
09-02 15:26:27.500  7099  7099 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.sec.android.gallery3d/cache
,09-02 15:26:27.500  7099  7099 D SLinkSource: Samsung link source created
,09-02 15:26:27.510  1019  1032 D ActivityManager: startService callerProcessName:com.samsung.android.provider.shootingmodeprovider, calleePkgName: com.samsung.android.provider.shootingmodeprovider
09-02 15:26:27.510  1019  1032 D ActivityManager: retrieveServiceLocked(): component = com.samsung.android.provider.shootingmodeprovider/com.samsung.android.app.shootingmodeinstaller.ShootingModesService; callingUser = 0; userId(target) = 0
,09-02 15:26:27.510  1019  1032 W ActivityManager: userId = 0, bbcId = -10000
09-02 15:26:27.510  1019  1032 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-02 15:26:27.510  1019  1032 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.android.provider.shootingmodeprovider, destAppInfo.processName = com.samsung.android.provider.shootingmodeprovider
,09-02 15:26:27.520  1019  2905 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.widgetapp.tapandpay, hostingType: broadcast
,09-02 15:26:27.520  7183  7183 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,09-02 15:26:27.530  7200  7200 D TimaKeyStoreProvider: TimaSignature is unavailable,
09-02 15:26:27.530  7200  7200 D ActivityThread: Added TimaKeyStore provider
,09-02 15:26:27.530  1019  2905 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-02 15:26:27.530  1019  2905 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-02 15:26:27.530  1019  2905 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-02 15:26:27.530  1019  2905 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-02 15:26:27.540  1019  3093 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
09-02 15:26:27.540  1019  3093 D BatteryService: level:93, scale:100, status:2, health:2, present:true, voltage: 4150, temperature: 285, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
09-02 15:26:27.540  1019  3093 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
09-02 15:26:27.540  1019  3093 D BatteryService: stay LED for charging
09-02 15:26:27.540  1019  1019 D BatteryService: Sending ACTION_BATTERY_CHANGED.
09-02 15:26:27.540  7162  7195 W ResourcesManager: Asset path '/system/framework/minimode.jar' does not exist or contains no resources.
09-02 15:26:27.540  7162  7195 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
09-02 15:26:27.540  7162  7195 W ResourcesManager: Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
09-02 15:26:27.540  7162  7195 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,09-02 15:26:27.550  7217  7217 E Zygote  : MountEmulatedStorage()
09-02 15:26:27.550  7217  7217 E Zygote  : v2
09-02 15:26:27.550  7217  7217 I libpersona: KNOX_SDCARD checking this for 10156
09-02 15:26:27.550  1019  1061 D PackageManager: [MSG] START_CLEANING_PACKAGE packageName{com.test.thalitest}
09-02 15:26:27.550  1019  1061 D PackageManager: userId{-1}
09-02 15:26:27.550  1019  1061 D PackageManager: andCode{true}
,09-02 15:26:27.550  7217  7217 I libpersona: KNOX_SDCARD not a persona
,09-02 15:26:27.560  1019  2905 I ActivityManager: Start proc com.sec.android.widgetapp.tapandpay for broadcast com.sec.android.widgetapp.tapandpay/.TapandpayAppWidgetProvider: pid=7217 uid=10156 gids={50156, 9997} abi=armeabi-v7a
,09-02 15:26:27.560  7162  7195 W ResourcesManager: Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
09-02 15:26:27.560  7162  7195 W ResourcesManager: Asset path '/system/framework/imsmanager.jar' does not exist or contains no resources.
09-02 15:26:27.570  1019  1019 I MotionRecognitionService: Plugged
09-02 15:26:27.570  1019  1019 I MotionRecognitionService: mGripSensorEnabled= false
09-02 15:26:27.570  7162  7195 W ResourcesManager: Asset path '/system/framework/sec_platform_library.jar' does not exist or contains no resources.
09-02 15:26:27.570  7162  7195 W ResourcesManager: Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
09-02 15:26:27.570  7162  7195 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
09-02 15:26:27.570  7162  7195 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
09-02 15:26:27.570  7162  7195 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
09-02 15:26:27.570  7162  7195 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,09-02 15:26:27.570  7217  7217 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51
,09-02 15:26:27.580  7217  7217 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051
09-02 15:26:27.580  1182  1182 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
09-02 15:26:27.580  1182  1182 D KeyguardUpdateMonitor: handleBatteryUpdate
,09-02 15:26:27.580  1422  1422 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
09-02 15:26:27.580  7217  7217 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
09-02 15:26:27.580  1422  1422 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 93
,09-02 15:26:27.590  7183  7183 D RCPManager:  in createShortcut() for packageName: com.test.thalitest userId0
,09-02 15:26:27.610  1182  1182 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:93 status:2 health:2
09-02 15:26:27.610  1182  1182 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:93 status:2 health:2
09-02 15:26:27.610  1182  1182 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:93 status:2 health:2
,09-02 15:26:27.610  6906  6906 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
09-02 15:26:27.610  1019  1061 D ActivityManager: retrieveServiceLocked(): component = com.android.defcontainer/com.android.defcontainer.DefaultContainerService; callingUser = 0; userId(target) = 0
,09-02 15:26:27.610  6906  6931 D HeadsetStateMachine: Disconnected process message: 10
,09-02 15:26:27.610  1019  1061 W ActivityManager: Application dead when creating service ServiceRecord{28ae67 u0 com.android.defcontainer/.DefaultContainerService}
,09-02 15:26:27.620  7162  7195 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
09-02 15:26:27.620  7162  7195 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
09-02 15:26:27.620  7162  7195 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,09-02 15:26:27.620  7217  7217 D TimaKeyStoreProvider: TimaSignature is unavailable
09-02 15:26:27.620  7217  7217 D ActivityThread: Added TimaKeyStore provider
,09-02 15:26:27.630  1019  1319 D RCPManagerService:  in createShortcut() for packageName: com.test.thalitest userId0
,09-02 15:26:27.630  1019  1319 D RCPManagerService: queryAllProviders():  providerCallBack is not register for 0
,09-02 15:26:27.630  7162  7195 W ResourcesManager: Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
09-02 15:26:27.630  7162  7195 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
09-02 15:26:27.630  7162  7195 W ResourcesManager: Asset path '/system/framework/imsmanager.jar' does not exist or contains no resources.
,09-02 15:26:27.630  1019  1061 W ActivityManager: Scheduling restart of crashed service com.android.defcontainer/.DefaultContainerService in 1000ms
09-02 15:26:27.630  6868  7131 E SQLiteLog: (10) POSIX Error : 9 SQLite Error : 3850
09-02 15:26:27.630  6868  7131 E SQLiteLog: (3850) statement aborts at 22: [INSERT INTO system_env_info(name,value) VALUES (?,?)] disk I/O error
,09-02 15:26:27.630  6868  7131 E SQLiteDatabase: Error inserting name=UT enabled value=false
09-02 15:26:27.630  6868  7131 E SQLiteDatabase: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
09-02 15:26:27.630  6868  7131 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForLastInsertedRowId(Native Method)
09-02 15:26:27.630  6868  7131 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.executeForLastInsertedRowId(SQLiteConnection.java:952)
09-02 15:26:27.630  6868  7131 E SQLiteDatabase: 	at android.database.sqlite.SQLiteSession.executeForLastInsertedRowId(SQLiteSession.java:788)
09-02 15:26:27.630  6868  7131 E SQLiteDatabase: 	at android.database.sqlite.SQLiteStatement.executeInsert(SQLiteStatement.java:86)
09-02 15:26:27.630  6868  7131 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.insertWithOnConflict(SQLiteDatabase.java:1609)
09-02 15:26:27.630  6868  7131 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.insert(SQLiteDatabase.java:1479)
09-02 15:26:27.630  6868  7131 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.c$b.a(DataStore.java:2487)
09-02 15:26:27.630  6868  7131 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.c.b(DataStore.java:1740)
09-02 15:26:27.630  6868  7131 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.f.g(LowpowerContextEngine.java:210)
09-02 15:26:27.630  6868  7131 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.f.e(LowpowerContextEngine.java:150)
09-02 15:26:27.630  6868  7131 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.f.<init>(LowpowerContextEngine.java:100)
09-02 15:26:27.630  6868  7131 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.f.a(LowpowerContextEngine.java:106)
09-02 15:26:27.630  6868  7131 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.LowpowerContextReceiver$SystemBroadcastReceiver.a(LowpowerContextReceiver.java:100)
09-02 15:26:27.630  6868  7131 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.LowpowerContextReceiver$SystemBroadcastReceiver.a(LowpowerContextReceiver.java:41)
09-02 15:26:27.630  6868  7131 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.n.run(LowpowerContextReceiver.java:51)
09-02 15:26:27.630  6868  7131 E SQLiteDatabase: 	at android.os.Handler.handleCallback(Handler.java:739)
09-02 15:26:27.630  6868  7131 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:95)
09-02 15:26:27.630  6868  7131 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:145)
09-02 15:26:27.630  6868  7131 E SQLiteDatabase: 	at android.os.HandlerThread.run(HandlerThread.java:61)
09-02 15:26:27.640  1019  1061 W ActivityManager: Scheduling restart of crashed service com.android.defcontainer/.DefaultContainerService in 4000ms
09-02 15:26:27.640  1019  1031 W ActivityManager: Spurious death for ProcessRecord{11fd414 0:com.android.defcontainer/u0a4}, curProc for 5719: null
,09-02 15:26:27.640  1019  1485 D ActivityManager: startProcessLocked calleePkgName: com.google.android.apps.docs, hostingType: broadcast
,09-02 15:26:27.650  7162  7195 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
09-02 15:26:27.650  7162  7195 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
09-02 15:26:27.650  6868  7131 E SQLiteLog: (10) POSIX Error : 9 SQLite Error : 3850
09-02 15:26:27.650  7162  7195 W ResourcesManager: Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
09-02 15:26:27.650  6868  7131 E SQLiteLog: (3850) statement aborts at 22: [INSERT INTO system_env_info(name,value) VALUES (?,?)] disk I/O error
09-02 15:26:27.650  7162  7195 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
09-02 15:26:27.650  7162  7195 W ResourcesManager: Asset path '/system/framework/secimaging.jar' does not exist or contains no resources.
09-02 15:26:27.650  7162  7195 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,09-02 15:26:27.650  7162  7195 W ResourcesManager: Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
09-02 15:26:27.650  7162  7195 W ResourcesManager: Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
09-02 15:26:27.650  6868  7131 E SQLiteDatabase: Error inserting name=AFP Enabled value=true
09-02 15:26:27.650  6868  7131 E SQLiteDatabase: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
09-02 15:26:27.650  6868  7131 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForLastInsertedRowId(Native Method)
09-02 15:26:27.650  6868  7131 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.executeForLastInsertedRowId(SQLiteConnection.java:952)
09-02 15:26:27.650  6868  7131 E SQLiteDatabase: 	at android.database.sqlite.SQLiteSession.executeForLastInsertedRowId(SQLiteSession.java:788)
09-02 15:26:27.650  6868  7131 E SQLiteDatabase: 	at android.database.sqlite.SQLiteStatement.executeInsert(SQLiteStatement.java:86)
09-02 15:26:27.650  6868  7131 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.insertWithOnConflict(SQLiteDatabase.java:1609)
09-02 15:26:27.650  6868  7131 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.insert(SQLiteDatabase.java:1479)
09-02 15:26:27.650  6868  7131 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.c$b.a(DataStore.java:2487)
09-02 15:26:27.650  6868  7131 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.c.b(DataStore.java:1740)
09-02 15:26:27.650  6868  7131 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.f.g(LowpowerContextEngine.java:211)
09-02 15:26:27.650  6868  7131 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.f.e(LowpowerContextEngine.java:150)
09-02 15:26:27.650  6868  7131 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.f.<init>(LowpowerContextEngine.java:100)
09-02 15:26:27.650  6868  7131 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.f.a(LowpowerContextEngine.java:106)
09-02 15:26:27.650  6868  7131 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.LowpowerContextReceiver$SystemBroadcastReceiver.a(LowpowerContextReceiver.java:100)
09-02 15:26:27.650  6868  7131 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.LowpowerContextReceiver$SystemBroadcastReceiver.a(LowpowerContextReceiver.java:41)
09-02 15:26:27.650  6868  7131 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.n.run(LowpowerContextReceiver.java:51)
09-02 15:26:27.650  6868  7131 E SQLiteDatabase: 	at android.os.Handler.handleCallback(Handler.java:739)
09-02 15:26:27.650  6868  7131 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:95)
09-02 15:26:27.650  6868  7131 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:145)
09-02 15:26:27.650  6868  7131 E SQLiteDatabase: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,09-02 15:26:27.650  6868  7131 E SQLiteLog: (10) POSIX Error : 9 SQLite Error : 3850
09-02 15:26:27.650  6868  7131 E SQLiteLog: (3850) statement aborts at 22: [INSERT INTO system_env_info(name,value) VALUES (?,?)] disk I/O error
,09-02 15:26:27.650  6868  7131 E SQLiteDatabase: Error inserting name=SleepDetection Enabled value=false
09-02 15:26:27.650  6868  7131 E SQLiteDatabase: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
09-02 15:26:27.650  6868  7131 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForLastInsertedRowId(Native Method)
09-02 15:26:27.650  6868  7131 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.executeForLastInsertedRowId(SQLiteConnection.java:952)
09-02 15:26:27.650  6868  7131 E SQLiteDatabase: 	at android.database.sqlite.SQLiteSession.executeForLastInsertedRowId(SQLiteSession.java:788)
09-02 15:26:27.650  6868  7131 E SQLiteDatabase: 	at android.database.sqlite.SQLiteStatement.executeInsert(SQLiteStatement.java:86)
09-02 15:26:27.650  6868  7131 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.insertWithOnConflict(SQLiteDatabase.java:1609)
09-02 15:26:27.650  6868  7131 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.insert(SQLiteDatabase.java:1479)
09-02 15:26:27.650  6868  7131 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.c$b.a(DataStore.java:2487)
09-02 15:26:27.650  6868  7131 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.c.b(DataStore.java:1740)
09-02 15:26:27.650  6868  7131 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.f.g(LowpowerContextEngine.java:212)
09-02 15:26:27.650  6868  7131 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.f.e(LowpowerContextEngine.java:150)
09-02 15:26:27.650  6868  7131 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.f.<init>(LowpowerContextEngine.java:100)
09-02 15:26:27.650  6868  7131 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.f.a(LowpowerContextEngine.java:106)
09-02 15:26:27.650  6868  7131 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.LowpowerContextReceiver$SystemBroadcastReceiver.a(LowpowerContextReceiver.java:100)
09-02 15:26:27.650  6868  7131 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.LowpowerContextReceiver$SystemBroadcastReceiver.a(LowpowerContextReceiver.java:41)
09-02 15:26:27.650  6868  7131 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.n.run(LowpowerContextReceiver.java:51)
09-02 15:26:27.650  6868  7131 E SQLiteDatabase: 	at android.os.Handler.handleCallback(Handler.java:739)
09-02 15:26:27.650  6868  7131 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:95)
09-02 15:26:27.650  6868  7131 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:145)
09-02 15:26:27.650  6868  7131 E SQLiteDatabase: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,09-02 15:26:27.650  6868  7131 E SQLiteLog: (10) POSIX Error : 9 SQLite Error : 3850
09-02 15:26:27.650  6868  7131 E SQLiteLog: (3850) statement aborts at 22: [INSERT INTO system_env_info(name,value) VALUES (?,?)] disk I/O error
,09-02 15:26:27.650  6868  7131 E SQLiteDatabase: Error inserting name=System Build Version Release value=5.0.2
09-02 15:26:27.650  6868  7131 E SQLiteDatabase: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
09-02 15:26:27.650  6868  7131 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForLastInsertedRowId(Native Method)
09-02 15:26:27.650  6868  7131 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.executeForLastInsertedRowId(SQLiteConnection.java:952)
09-02 15:26:27.650  6868  7131 E SQLiteDatabase: 	at android.database.sqlite.SQLiteSession.executeForLastInsertedRowId(SQLiteSession.java:788)
09-02 15:26:27.650  6868  7131 E SQLiteDatabase: 	at android.database.sqlite.SQLiteStatement.executeInsert(SQLiteStatement.java:86)
09-02 15:26:27.650  6868  7131 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.insertWithOnConflict(SQLiteDatabase.java:1609)
09-02 15:26:27.650  6868  7131 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.insert(SQLiteDatabase.java:1479)
09-02 15:26:27.650  6868  7131 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.c$b.a(DataStore.java:2487)
09-02 15:26:27.650  6868  7131 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.c.b(DataStore.java:1740)
09-02 15:26:27.650  6868  7131 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.f.g(LowpowerContextEngine.java:213)
09-02 15:26:27.650  6868  7131 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.f.e(LowpowerContextEngine.java:150)
09-02 15:26:27.650  6868  7131 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.f.<init>(LowpowerContextEngine.java:100)
09-02 15:26:27.650  6868  7131 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.f.a(LowpowerContextEngine.java:106)
09-02 15:26:27.650  6868  7131 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.LowpowerContextReceiver$SystemBroadcastReceiver.a(LowpowerContextReceiver.java:100)
09-02 15:26:27.650  6868  7131 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.LowpowerContextReceiver$SystemBroadcastReceiver.a(LowpowerContextReceiver.java:41)
09-02 15:26:27.650  6868  7131 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.n.run(LowpowerContextReceiver.java:51)
09-02 15:26:27.650  6868  7131 E SQLiteDatabase: 	at android.os.Handler.handleCallback(Handler.java:739)
09-02 15:26:27.650  6868  7131 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:95)
09-02 15:26:27.650  6868  7131 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:145)
09-02 15:26:27.650  6868  7131 E SQLiteDatabase: 	at android.os.HandlerThread.run(HandlerThread.java:61)
09-02 15:26:27.650  1019  1485 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-02 15:26:27.650  1019  1485 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-02 15:26:27.650  1019  1485 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-02 15:26:27.650  6868  7131 E SQLiteLog: (10) POSIX Error : 9 SQLite Error : 3850
09-02 15:26:27.650  6868  7131 E SQLiteLog: (3850) statement aborts at 22: [INSERT INTO system_env_info(name,value) VALUES (?,?)] disk I/O error
,09-02 15:26:27.650  6868  7131 E SQLiteDatabase: Error inserting name=status value=successfully initialized
09-02 15:26:27.650  6868  7131 E SQLiteDatabase: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
09-02 15:26:27.650  6868  7131 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForLastInsertedRowId(Native Method)
09-02 15:26:27.650  6868  7131 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.executeForLastInsertedRowId(SQLiteConnection.java:952)
09-02 15:26:27.650  6868  7131 E SQLiteDatabase: 	at android.database.sqlite.SQLiteSession.executeForLastInsertedRowId(SQLiteSession.java:788)
09-02 15:26:27.650  6868  7131 E SQLiteDatabase: 	at android.database.sqlite.SQLiteStatement.executeInsert(SQLiteStatement.java:86)
09-02 15:26:27.650  6868  7131 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.insertWithOnConflict(SQLiteDatabase.java:1609)
09-02 15:26:27.650  6868  7131 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.insert(SQLiteDatabase.java:1479)
09-02 15:26:27.650  6868  7131 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.c$b.a(DataStore.java:2487)
09-02 15:26:27.650  6868  7131 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.c.b(DataStore.java:1740)
09-02 15:26:27.650  6868  7131 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.f.g(LowpowerContextEngine.java:214)
09-02 15:26:27.650  6868  7131 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.f.e(LowpowerContextEngine.java:150)
09-02 15:26:27.650  6868  7131 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.f.<init>(LowpowerContextEngine.java:100)
09-02 15:26:27.650  6868  7131 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.f.a(LowpowerContextEngine.java:106)
09-02 15:26:27.650  6868  7131 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.LowpowerContextReceiver$SystemBroadcastReceiver.a(LowpowerContextReceiver.java:100)
09-02 15:26:27.650  6868  7131 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.LowpowerContextReceiver$SystemBroadcastReceiver.a(LowpowerContextReceiver.java:41)
09-02 15:26:27.650  6868  7131 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.n.run(LowpowerContextReceiver.java:51)
09-02 15:26:27.650  6868  7131 E SQLiteDatabase: 	at android.os.Handler.handleCallback(Handler.java:739)
09-02 15:26:27.650  6868  7131 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:95)
09-02 15:26:27.650  6868  7131 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:145)
09-02 15:26:27.650  6868  7131 E SQLiteDatabase: 	at android.os.HandlerThread.run(HandlerThread.java:61)
09-02 15:26:27.660  1019  1485 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-02 15:26:27.660  7099  7099 E SQLiteLog: (28) failed to open "/data/data/com.sec.android.gallery3d/databases/local.db" with flag (131138) and mode_t (0) due to error (30),
,09-02 15:26:27.660  7099  7099 E SQLiteDatabase: Failed to open database '/data/data/com.sec.android.gallery3d/databases/local.db'.
09-02 15:26:27.660  7099  7099 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-02 15:26:27.660  7099  7099 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
09-02 15:26:27.660  7099  7099 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
09-02 15:26:27.660  7099  7099 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
09-02 15:26:27.660  7099  7099 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
09-02 15:26:27.660  7099  7099 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
09-02 15:26:27.660  7099  7099 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
09-02 15:26:27.660  7099  7099 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
09-02 15:26:27.660  7099  7099 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
09-02 15:26:27.660  7099  7099 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
09-02 15:26:27.660  7099  7099 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1519)
09-02 15:26:27.660  7099  7099 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
09-02 15:26:27.660  7099  7099 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
09-02 15:26:27.660  7099  7099 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
09-02 15:26:27.660  7099  7099 E SQLiteDatabase: 	at com.sec.samsung.gallery.util.LocalDatabaseManager.getReadableDatabase(LocalDatabaseManager.java:232)
09-02 15:26:27.660  7099  7099 E SQLiteDatabase: 	at com.sec.samsung.gallery.util.LocalDatabaseManager.<init>(LocalDatabaseManager.java:202)
09-02 15:26:27.660  7099  7099 E SQLiteDatabase: 	at com.sec.samsung.gallery.util.LocalDatabaseManager.getInstance(LocalDatabaseManager.java:212)
09-02 15:26:27.660  7099  7099 E SQLiteDatabase: 	at com.sec.android.gallery3d.app.GalleryAppImpl.initLocalDataBase(GalleryAppImpl.java:211)
09-02 15:26:27.660  7099  7099 E SQLiteDatabase: 	at com.sec.android.gallery3d.app.GalleryAppImpl.onCreate(GalleryAppImpl.java:203)
09-02 15:26:27.660  7099  7099 E SQLiteDatabase: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
09-02 15:26:27.660  7099  7099 E SQLiteDatabase: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
09-02 15:26:27.660  7099  7099 E SQLiteDatabase: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
09-02 15:26:27.660  7099  7099 E SQLiteDatabase: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
09-02 15:26:27.660  7099  7099 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-02 15:26:27.660  7099  7099 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:145)
09-02 15:26:27.660  7099  7099 E SQLiteDatabase: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
09-02 15:26:27.660  7099  7099 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Native Method)
09-02 15:26:27.660  7099  7099 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Method.java:372)
09-02 15:26:27.660  7099  7099 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
09-02 15:26:27.660  7099  7099 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
09-02 15:26:27.660  7099  7099 E SQLiteOpenHelper: Couldn't open local.db for writing (will try re,ad-only):
09-02 15:26:27.660  7099  7099 E SQLiteOpenHelper: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-02 15:26:27.660  7099  7099 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
09-02 15:26:27.660  7099  7099 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
09-02 15:26:27.660  7099  7099 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
09-02 15:26:27.660  7099  7099 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
09-02 15:26:27.660  7099  7099 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
09-02 15:26:27.660  7099  7099 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
09-02 15:26:27.660  7099  7099 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
09-02 15:26:27.660  7099  7099 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
09-02 15:26:27.660  7099  7099 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
09-02 15:26:27.660  7099  7099 E SQLiteOpenHelper: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1519)
09-02 15:26:27.660  7099  7099 E SQLiteOpenHelper: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
09-02 15:26:27.660  7099  7099 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
09-02 15:26:27.660  7099  7099 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
09-02 15:26:27.660  7099  7099 E SQLiteOpenHelper: 	at com.sec.samsung.gallery.util.LocalDatabaseManager.getReadableDatabase(LocalDatabaseManager.java:232)
09-02 15:26:27.660  7099  7099 E SQLiteOpenHelper: 	at com.sec.samsung.gallery.util.LocalDatabaseManager.<init>(LocalDatabaseManager.java:202)
09-02 15:26:27.660  7099  7099 E SQLiteOpenHelper: 	at com.sec.samsung.gallery.util.LocalDatabaseManager.getInstance(LocalDatabaseManager.java:212)
09-02 15:26:27.660  7099  7099 E SQLiteOpenHelper: 	at com.sec.android.gallery3d.app.GalleryAppImpl.initLocalDataBase(GalleryAppImpl.java:211)
09-02 15:26:27.660  7099  7099 E SQLiteOpenHelper: 	at com.sec.android.gallery3d.app.GalleryAppImpl.onCreate(GalleryAppImpl.java:203)
09-02 15:26:27.660  7099  7099 E SQLiteOpenHelper: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
09-02 15:26:27.660  7099  7099 E SQLiteOpenHelper: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
09-02 15:26:27.660  7099  7099 E SQLiteOpenHelper: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
09-02 15:26:27.660  7099  7099 E SQLiteOpenHelper: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
09-02 15:26:27.660  7099  7099 E SQLiteOpenHelper: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-02 15:26:27.660  7099  7099 E SQLiteOpenHelper: 	at android.os.Looper.loop(Looper.java:145)
09-02 15:26:27.660  7099  7099 E SQLiteOpenHelper: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
09-02 15:26:27.660  7099  7099 E SQLiteOpenHelper: 	at java.lang.reflect.Method.invoke(Native Method)
09-02 15:26:27.660  7099  7099 E SQLiteOpenHelper: 	at java.lang.reflect.Method.invoke(Method.java:372)
09-02 15:26:27.660  7099  7099 E SQLiteOpenHelper: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
09-02 15:26:27.660  7099  7099 E SQLiteOpenHelper: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
,09-02 15:26:27.660  7099  7099 W SQLiteOpenHelper: Opened local.db in read-only mode
,09-02 15:26:27.670  7162  7195 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
09-02 15:26:27.670  7162  7195 W ResourcesManager: Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
09-02 15:26:27.670  7162  7195 W ResourcesManager: Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,09-02 15:26:27.670  1019  3109 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
09-02 15:26:27.670  7234  7234 E Zygote  : MountEmulatedStorage()
09-02 15:26:27.670  7234  7234 E Zygote  : v2
,09-02 15:26:27.670  7234  7234 I libpersona: KNOX_SDCARD checking this for 10091,
09-02 15:26:27.670  7234  7234 I libpersona: KNOX_SDCARD not a persona
,09-02 15:26:27.680  7234  7234 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51
09-02 15:26:27.680  7162  7195 W ResourcesManager: Asset path '/system/framework/minimode.jar' does not exist or contains no resources.,
09-02 15:26:27.680  7162  7195 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
09-02 15:26:27.680  7162  7195 W ResourcesManager: Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
09-02 15:26:27.680  7162  7195 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
09-02 15:26:27.680  7162  7195 W ResourcesManager: Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
09-02 15:26:27.680  1019  1485 I ActivityManager: Start proc com.google.android.apps.docs for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver: pid=7234 uid=10091 gids={50091, 9997, 3003, 1028, 1015} abi=armeabi-v7a
09-02 15:26:27.680  7234  7234 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051
,09-02 15:26:27.680  7234  7234 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,09-02 15:26:27.680  1019  1485 I ActivityManager: Killing 5573:com.android.vending/u0a28 (adj 15): empty #31
,09-02 15:26:27.690  1019  1485 I ActivityManager: Killing 6283:com.google.android.gms.unstable/u0a12 (adj 15): empty #31

```
