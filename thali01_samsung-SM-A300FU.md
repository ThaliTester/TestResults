#### Test 757892686fd65a6_thali01_samsung-SM-A300FU Logs


```
--------- beginning of main
07-01 08:58:44.143   293   293 E SMD     : DCD OFF
--------- beginning of system
07-01 08:58:44.283  1017  2851 D SSRM:n  : SIOP:: AP = 300
07-01 08:58:44.833   332   332 I ServiceManager: Waiting for service AtCmdFwd...
,07-01 08:58:45.833  6784  6784 D AndroidRuntime: 
07-01 08:58:45.833  6784  6784 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
07-01 08:58:45.833   332   332 I ServiceManager: Waiting for service AtCmdFwd...
07-01 08:58:45.833  6784  6784 D AndroidRuntime: CheckJNI is OFF
07-01 08:58:45.833  6784  6784 D AndroidRuntime: readGMSProperty: start
07-01 08:58:45.833  6784  6784 D AndroidRuntime: readGMSProperty: already setted!!
07-01 08:58:45.833  6784  6784 D AndroidRuntime: propertySet: couldn't set property (it is from app)
07-01 08:58:45.833  6784  6784 D AndroidRuntime: readGMSProperty: could not set the property(default)!!
07-01 08:58:45.833  6784  6784 D AndroidRuntime: readGMSProperty: end
07-01 08:58:45.833  6784  6784 D AndroidRuntime: addProductProperty: start
07-01 08:58:45.963  6784  6784 E AffinityControl: AffinityControl: registerfunction enter
07-01 08:58:45.993  6784  6784 D AndroidRuntime: Calling main entry com.android.commands.am.Am
07-01 08:58:46.003  1017  1502 E PersonaManagerService: inState():  stateMachine is null !!
07-01 08:58:46.003  1017  1502 I PersonaManagerService: PersonaId don't exist
07-01 08:58:46.003  1017  1502 I ActivityManager: do not start freezing screen for locked container getKeyguardshowstate = false
07-01 08:58:46.003  1017  1502 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
07-01 08:58:46.023  1017  1502 W ActivityManager: mDVFSHelper.acquire()
07-01 08:58:46.023  1017  1502 D FocusedStackFrame: Set to : 0
07-01 08:58:46.023  1017  1047 D PhoneWindow: *FMB* installDecor mIsFloating : false
07-01 08:58:46.023  1017  1047 D PhoneWindow: *FMB* installDecor flags : -2122120936
07-01 08:58:46.033  1017  1502 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-01 08:58:46.033  1017  1502 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-01 08:58:46.033  1017  1502 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-01 08:58:46.033  1017  1502 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-01 08:58:46.043  1017  1502 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.sec.android.app.launcher
07-01 08:58:46.043  1017  1502 I ActivityManager: Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=6795 uid=10151 gids={50151, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
07-01 08:58:46.043  1017  1502 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
07-01 08:58:46.043  6795  6795 I libpersona: KNOX_SDCARD checking this for 10151
07-01 08:58:46.043  1017  1502 D InputDispatcher: Focused application set to: xxxx
07-01 08:58:46.043  6795  6795 I libpersona: KNOX_SDCARD not a persona
07-01 08:58:46.043  1017  1502 D InputDispatcher: Focus left window: 1507
07-01 08:58:46.043  6795  6795 E Zygote  : MountEmulatedStorage()
07-01 08:58:46.043  6795  6795 E Zygote  : v2
07-01 08:58:46.043  1017  1047 D PhoneWindow: *FMB* isFloatingMenuEnabled mFloatingMenuBtn : null
07-01 08:58:46.043  1017  1047 D PhoneWindow: *FMB* isFloatingMenuEnabled return false
07-01 08:58:46.043   259   259 I SurfaceFlinger: id=12 createSurf (1x1),1 flag=404, uhalitest
07-01 08:58:46.043  6784  6784 D AndroidRuntime: Shutting down VM
07-01 08:58:46.043  6795  6795 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
07-01 08:58:46.053  6795  6795 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
07-01 08:58:46.053  6795  6795 E SELinux : [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
07-01 08:58:46.063  1017  1047 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
07-01 08:58:46.063  1017  1047 D PointerIcon: setMouseCustomIcon IconType is same.101
07-01 08:58:46.073  6795  6795 D TimaKeyStoreProvider: TimaSignature is unavailable
07-01 08:58:46.073  6795  6795 D ActivityThread: Added TimaKeyStore provider
07-01 08:58:46.073  1017  1505 V WindowManager: rotationForOrientationLw(orient=-1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false
07-01 08:58:46.083  1017  1045 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
07-01 08:58:46.093  1017  1505 D PersonaManager: isKioskContainerExistOnDevice
07-01 08:58:46.113  1017  1017 D WindowOrientationListener:   mReceiver.onReceive :com.samsung.intent.action.AUTOROTATION,  delay = 66
07-01 08:58:46.123   259  1097 I SurfaceFlinger: id=9 Removed Mauncher (5/9)
07-01 08:58:46.123   259   453 I SurfaceFlinger: id=9 Removed Mauncher (-2/9)
07-01 08:58:46.133  1507  1507 V ActivityThread: updateVisibility : ActivityRecord{3756368d token=android.os.BinderProxy@591c66e {com.sec.android.app.launcher/com.android.launcher2.Launcher}} show : false
07-01 08:58:46.133  1507  1507 D Launcher: onTrimMemory. Level: 20
07-01 08:58:46.213  6795  6795 I WebViewFactory: Loading com.google.android.webview version 43.0.2357.121 (code 2357121)
07-01 08:58:46.223  6795  6795 I LibraryLoader: Time to load native libraries: 1 ms (timestamps 1873-1874)
07-01 08:58:46.223  6795  6795 I LibraryLoader: Expected native library version number "",actual native library version number ""
07-01 08:58:46.253  6784  6784 W art     : ConditionVariable::~ConditionVariable for GC request condition variable called with 1 waiters.
07-01 08:58:46.263  6795  6795 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {11ded78a}
07-01 08:58:46.263  6795  6795 I LibraryLoader: Expected native library version number "",actual native library version number ""
07-01 08:58:46.263  6795  6795 I chromium: [INFO:library_loader_hooks.cc(112)] Chromium logging enabled: level = 0, default verbosity = 0
,07-01 08:58:46.293  6795  6795 I BrowserStartupController: Initializing chromium process, singleProcess=true,
,07-01 08:58:46.293  6795  6795 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,07-01 08:58:46.293  6795  6795 E SysUtils: ApplicationContext is null in ApplicationStatus,
,07-01 08:58:46.323  6795  6795 W chromium: [WARNING:resource_bundle.cc(286)] locale_file_path.empty()
,07-01 08:58:46.323  6795  6795 I chromium: [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=38 off=50556 len=3379
,07-01 08:58:46.323  6795  6795 I chromium: [INFO:aw_browser_main_parts.cc(76)] Loading webviewchromium.pak from, fd:39 off:7638088 len:1165478
,07-01 08:58:46.323  6795  6795 I Adreno-EGL: <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: SKARAJGA_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018__release_ENGG (I856e09677e)
07-01 08:58:46.323  6795  6795 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.02
07-01 08:58:46.323  6795  6795 I Adreno-EGL: Build Date: 04/06/15 Mon
07-01 08:58:46.323  6795  6795 I Adreno-EGL: Local Branch: 
07-01 08:58:46.323  6795  6795 I Adreno-EGL: Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018
07-01 08:58:46.323  6795  6795 I Adreno-EGL: Local Patches: 112c106f3772623daa7b4181c6cf23491044ead1 Revert "Disable ASTC on A405"
07-01 08:58:46.323  6795  6795 I Adreno-EGL:                  58a118cb818fdc906095a49a90977c15f9d3b223 Remove ASTC
,07-01 08:58:46.483  1017  2055 V SAMP_SPCM_test: CSC File load.. 
,07-01 08:58:46.483  1017  2055 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-application
,07-01 08:58:46.483  1017  2055 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-bluetooth
07-01 08:58:46.483  1017  2055 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-device-inventory
07-01 08:58:46.483  1017  2055 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-date-time
07-01 08:58:46.483  1017  2055 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-exchange-account
,07-01 08:58:46.483  1017  2055 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-roaming
07-01 08:58:46.483  1017  2055 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-wifi
07-01 08:58:46.483  1017  2055 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-security
07-01 08:58:46.483  1017  2055 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-email-account
07-01 08:58:46.483  1017  2055 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-hardware-control
07-01 08:58:46.483  1017  2055 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-tethering
,07-01 08:58:46.483  1017  2055 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-location
07-01 08:58:46.483  1017  2055 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-calling
07-01 08:58:46.483  1017  2055 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-email
07-01 08:58:46.483  1017  2055 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-vpn
07-01 08:58:46.483  1017  2055 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-apn-settings
07-01 08:58:46.483  1017  2055 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-browser-settings
,07-01 08:58:46.483  1017  2055 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-phone-restriction
07-01 08:58:46.483  1017  2055 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-firewall
07-01 08:58:46.483  1017  2055 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-enterprise-vpn
07-01 08:58:46.483  1017  2055 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-data-time
,07-01 08:58:46.533  1017  2055 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-application
,07-01 08:58:46.533  1017  2055 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-bluetooth
07-01 08:58:46.533  1017  2055 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-device-inventory
07-01 08:58:46.533  1017  2055 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-date-time
07-01 08:58:46.533  1017  2055 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-exchange-account
07-01 08:58:46.533  1017  2055 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-roaming
07-01 08:58:46.533  1017  2055 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-wifi
07-01 08:58:46.533  1017  2055 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-security
07-01 08:58:46.533  1017  2055 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-email-account
07-01 08:58:46.533  1017  2055 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-hardware-control
07-01 08:58:46.533  1017  2055 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-tethering
07-01 08:58:46.533  1017  2055 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-location
07-01 08:58:46.533  1017  2055 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-calling
07-01 08:58:46.533  1017  2055 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-email
07-01 08:58:46.533  1017  2055 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-vpn
07-01 08:58:46.533  1017  2055 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-apn-settings
07-01 08:58:46.533  1017  2055 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-browser-settings
07-01 08:58:46.533  1017  2055 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-phone-restriction
07-01 08:58:46.533  1017  2055 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-firewall
07-01 08:58:46.533  1017  2055 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-enterprise-vpn
07-01 08:58:46.533  1017  2055 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-data-time
,07-01 08:58:46.533  6795  6823 W chromium: [WARNING:data_reduction_proxy_config.cc(318)] SPDY proxy OFF at startup,
,07-01 08:58:46.553  1017  2055 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: history-password
07-01 08:58:46.553  1017  2055 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: allow-attachments
07-01 08:58:46.553  1017  2055 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: limit-attachments
07-01 08:58:46.553  1017  2055 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: allow-camera
07-01 08:58:46.553  1017  2055 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: allow-htmlemail
07-01 08:58:46.553  1017  2055 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: require-manualsyncroaming
07-01 08:58:46.553  1017  2055 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: min-passwordcomplexchars
07-01 08:58:46.553  1017  2055 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: max-calendarage
07-01 08:58:46.553  1017  2055 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: max-emailage
07-01 08:58:46.553  1017  2055 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: max-emailbodytruncsize
07-01 08:58:46.553  1017  2055 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: max-htmlemailbodytruncsize
07-01 08:58:46.553  1017  2055 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: require-signedsmimemessages
07-01 08:58:46.553  1017  2055 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: require-encryptedsmimemessages
07-01 08:58:46.553  1017  2055 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: require-signedsmimealgorithm
07-01 08:58:46.553  1017  2055 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: require-encryptionsmimealgorithm
07-01 08:58:46.553  1017  2055 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: allow-smimeencryptionalgonegotiation
07-01 08:58:46.553  1017  2055 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: allow-smimesoftcerts
07-01 08:58:46.553  1017  2055 W DeviceAdminInfo: Unknown tag under, uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: require-device-encryption
07-01 08:58:46.553  1017  2055 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-application
07-01 08:58:46.553  1017  2055 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-bluetooth
07-01 08:58:46.553  1017  2055 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-device-inventory
07-01 08:58:46.553  1017  2055 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-date-time
07-01 08:58:46.553  1017  2055 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-exchange-account
07-01 08:58:46.553  1017  2055 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-roaming
07-01 08:58:46.553  1017  2055 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-wifi
07-01 08:58:46.553  1017  2055 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-security
07-01 08:58:46.553  1017  2055 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-email-account
07-01 08:58:46.553  1017  2055 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-hardware-control
07-01 08:58:46.553  1017  2055 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-tethering
07-01 08:58:46.553  1017  2055 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-location
07-01 08:58:46.553  1017  2055 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-calling
07-01 08:58:46.553  1017  2055 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-email
07-01 08:58:46.553  1017  2055 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-vpn
07-01 08:58:46.553  1017  2055 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-apn-settings
07-01 08:58:46.553  1017  2055 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-browser-settings
07-01 08:58:46.553  1017  2055 ,W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-phone-restriction
07-01 08:58:46.553  1017  2055 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-firewall
07-01 08:58:46.553  1017  2055 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-enterprise-vpn
07-01 08:58:46.553  1017  2055 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-data-time
,07-01 08:58:46.563  1017  2055 E SAMP_SPCMtest: setPackageLockingTimeBySPCM() :72
,07-01 08:58:46.593  1017  1042 W ActivityManager: Activity pause timeout for ActivityRecord{5aee535 u0 com.test.thalitest/.MainActivity t81}
,07-01 08:58:46.593  6795  6795 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,07-01 08:58:46.613  6795  6795 W AwContents: onDetachedFromWindow called when already detached. Ignoring
,07-01 08:58:46.623  6795  6795 D PhoneWindow: *FMB* installDecor mIsFloating : false
,07-01 08:58:46.623  6795  6795 D PhoneWindow: *FMB* installDecor flags : -2139027200
,07-01 08:58:46.623  6795  6795 D SystemWebViewEngine: CordovaWebView is running on device made by: samsung
,07-01 08:58:46.633  6795  6795 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,07-01 08:58:46.633  6795  6795 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,07-01 08:58:46.703  6795  6836 D OpenGLRenderer: Render dirty regions requested: true
,07-01 08:58:46.713  1017  1030 D ActivityManager: post active user change for 0 fullscreen true record.isFloatingActivity() false
,07-01 08:58:46.713  1017  1030 D KnoxTimeoutHandler: postActiveUserChange for user 0
07-01 08:58:46.713  1017  1030 I KnoxTimeoutHandler: postActiveUserChange, showWhenLocked: false
,07-01 08:58:46.713  1017  1017 D KnoxTimeoutHandler: handleActiveUserChange for user 0
07-01 08:58:46.713  1017  1017 D PersonaManagerService: getPersonasForUser(): returning null!
,07-01 08:58:46.723  6795  6795 V ActivityThread: updateVisibility : ActivityRecord{24cc451d token=android.os.BinderProxy@35ce0fc7 {com.test.thalitest/com.test.thalitest.MainActivity}} show : true
,07-01 08:58:46.723  6795  6795 D PhoneWindow: *FMB* isFloatingMenuEnabled mFloatingMenuBtn : null
07-01 08:58:46.723  6795  6795 D PhoneWindow: *FMB* isFloatingMenuEnabled return false
,07-01 08:58:46.733   259   259 I SurfaceFlinger: id=13 createSurf (1x1),1 flag=404, NainActivit,
,07-01 08:58:46.743  1017  4141 D InputDispatcher: Focus entered window: 6795
,07-01 08:58:46.753  1017  1047 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0,
07-01 08:58:46.753  1017  1047 D PointerIcon: setMouseCustomIcon IconType is same.101
07-01 08:58:46.753  6795  6795 D SRIB_DCS: log_dcs ThreadedRenderer::initialize entered! 
07-01 08:58:46.753  6795  6836 I OpenGLRenderer: Initialized EGL, version 1.4
,07-01 08:58:46.753  6795  6836 D OpenGLRenderer: Get maximum texture size. GL_MAX_TEXTURE_SIZE is 4096
,07-01 08:58:46.753  6795  6836 D OpenGLRenderer: Enabling debug mode 0
,07-01 08:58:46.803  1017  1561 D InputMethodManagerService: windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,07-01 08:58:46.813  1017  6839 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.android.server.InputMethodManagerService$6.run:2762 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,07-01 08:58:46.813  1181  1181 I StatusBar: Icon Only
,07-01 08:58:46.813  1181  1181 D PanelView: There is/are notification(s) 
,07-01 08:58:46.823  1017  1047 I ActivityManager: Displayed Component not be shown by security: +728ms (total +26s932ms)
,07-01 08:58:46.823  1017  1047 W ActivityManager: mDVFSHelper.release()
,07-01 08:58:46.823  1017  1047 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{5aee535 u0 com.test.thalitest/.MainActivity t81} time:142475
,07-01 08:58:46.823   259   456 I SurfaceFlinger: id=12 Removed uhalitest (7/9)
,07-01 08:58:46.823   259   453 I SurfaceFlinger: id=12 Removed uhalitest (-2/9)
,07-01 08:58:46.833  6795  6795 W IInputConnectionWrapper: showStatusIcon on inactive InputConnection
,07-01 08:58:46.833   332   332 I ServiceManager: Waiting for service AtCmdFwd...
,07-01 08:58:46.843  1994  1994 I SamsungIME: getCurrentCandidateView
,07-01 08:58:46.853  6795  6795 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@35ce0fc7 time:142501
,07-01 08:58:46.933  6795  6795 W BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 6795
,07-01 08:58:46.953  1994  1994 D SamsungIME: Dismiss ExpandCandiate
,07-01 08:58:47.043  6795  6795 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,07-01 08:58:47.103  1994  1994 I SamsungIME: getDebugLevel  : 0x4f4c
,07-01 08:58:47.133  1994  1994 I SamsungIME: getDebugLevel  : 0x4f4c
,07-01 08:58:47.143   293   293 E SMD     : DCD OFF
,07-01 08:58:47.153  1994  1994 I SamsungIME: KeybaordView init() : load resources
,07-01 08:58:47.163  6795  6842 D jxcore_app_log: JniHelper::setJavaVM(0xb80dd2f0), pthread_self() = -1201432040
,07-01 08:58:47.173  6795  6842 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
07-01 08:58:47.173  6795  6842 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
07-01 08:58:47.173  6795  6842 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
07-01 08:58:47.173  6795  6842 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
07-01 08:58:47.173  6795  6842 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
,07-01 08:58:47.173  6795  6842 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c2daf8d added. We now have 1 listener(s)
,07-01 08:58:47.173  1994  1994 I SamsungIME: getCurrentKeyboard
07-01 08:58:47.173  1994  1994 I SamsungIME: getTextKeyboard
,07-01 08:58:47.183  6795  6842 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: 08:EC:A9:50:75:41
,07-01 08:58:47.183  6795  6842 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "08:EC:A9:50:75:41"
,07-01 08:58:47.183  6795  6842 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,07-01 08:58:47.183  6795  6842 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,07-01 08:58:47.183  6795  6842 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
07-01 08:58:47.183  6795  6842 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
07-01 08:58:47.183  6795  6842 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
07-01 08:58:47.183  6795  6842 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: 08:EC:A9:50:75:41
07-01 08:58:47.183  6795  6842 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
07-01 08:58:47.183  6795  6842 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
07-01 08:58:47.183  6795  6842 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
07-01 08:58:47.183  6795  6842 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
07-01 08:58:47.183  6795  6842 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
07-01 08:58:47.183  6795  6842 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
07-01 08:58:47.183  6795  6842 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
07-01 08:58:47.183  6795  6842 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@815d290 added. We now have 1 listener(s)
,07-01 08:58:47.183  6795  6842 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,07-01 08:58:47.193  6795  6842 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: isBleMultipleAdvertisementSupported: Storing the value (SUPPORTED) in persistent storage
,07-01 08:58:47.193  6795  6842 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
07-01 08:58:47.193  6795  6842 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseMode: 1 -> 2
07-01 08:58:47.193  6795  6842 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseTxPowerLevel: 2 -> 3
,07-01 08:58:47.193  6795  6842 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setScanMode: 1 -> 2
,07-01 08:58:47.203  1994  1994 D SamsungIME: [SwiftkeyWrapper] currentLangauge : 1701729619
,07-01 08:58:47.203  6795  6842 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,07-01 08:58:47.203  6795  6842 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 08:EC:A9:50:75:41
,07-01 08:58:47.203  6795  6842 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
07-01 08:58:47.203  6795  6842 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-01 08:58:47.203  6795  6842 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
07-01 08:58:47.203  6795  6842 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-01 08:58:47.203  6795  6842 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
07-01 08:58:47.203  6795  6842 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: 84:b2:61:0f:9c:30
07-01 08:58:47.203  6795  6842 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
07-01 08:58:47.203  6795  6842 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
07-01 08:58:47.203  6795  6842 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
07-01 08:58:47.203  6795  6842 D io.jxcore.node.ConnectivityMonitor: start: OK
,07-01 08:58:47.203  6795  6842 I io.jxcore.node.LifeCycleMonitor: start: OK
,07-01 08:58:47.213  6795  6795 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,07-01 08:58:47.213  6795  6795 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,07-01 08:58:47.243  6795  6795 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,07-01 08:58:47.773  6795  6847 W jxcore-log: Initializing JXcore engine
07-01 08:58:47.773  6795  6847 W jxcore-log: JXcore engine is ready
,07-01 08:58:47.823  2013  2013 E audit   : type=1400 msg=audit(1467356327.823:205): avc:  denied  { ioctl } for  pid=6847 comm="Thread-1264" path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=2064 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
,07-01 08:58:47.833  2013  2013 E audit   :  SEPF_SM-A300FU_5.0.2-1_0051,
07-01 08:58:47.833  2013  2013 E audit   : type=1300 msg=audit(1467356327.823:205): arch=40000028 syscall=54 per=800000 success=no exit=-13 a0=7 a1=5451 a2=2 a3=9d4008f8 items=0 ppid=315 ppcomm=main pid=6847 auid=4294967295 uid=10151 gid=10151 euid=10151 suid=10151 fsuid=10151 egid=10151 sgid=10151 fsgid=10151 ses=4294967295 tty=(none) comm="Thread-1264" exe="/system/bin/app_process32" subj=u:r:untrusted_app:s0 key=(null)
07-01 08:58:47.833  2013  2013 E audit   : type=1320 msg=audit(1467356327.823:205): 
,07-01 08:58:47.833  6795  6847 W jxcore-log: Starting JXcore engine,
,07-01 08:58:47.833   332   332 I ServiceManager: Waiting for service AtCmdFwd...
,07-01 08:58:47.933  6795  6847 W jxcore-log: Platform android
07-01 08:58:47.933  6795  6847 W jxcore-log: 
,07-01 08:58:47.933  6795  6847 W jxcore-log: Process ARCH arm
07-01 08:58:47.933  6795  6847 W jxcore-log: 
,07-01 08:58:48.143  6795  6847 I jxcore-log: JXcore Cordova bridge is ready!
07-01 08:58:48.143  6795  6847 I jxcore-log: 
,07-01 08:58:48.143  6795  6847 W jxcore-log: JXcore engine is started
,07-01 08:58:48.143  6795  6842 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,07-01 08:58:48.153  6795  6795 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,07-01 08:58:48.153  6795  6847 E jxcore  : Error!: No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js
07-01 08:58:48.153  6795  6847 E jxcore  : Stack: [{"_fileName":"node.js","_functionName":"$h.require","_lineNumber":"1472","_columnNumber":"1","_msg":"    at $h.require@node.js:1472:1"},{"_fileName":"main.js.js","_functionName":"internal_methods.loadMainFile","_lineNumber":"260","_columnNumber":"5","_msg":"    at internal_methods.loadMainFile@main.js.js:260:5"},{"_fileName":"main.js.js","_functionName":"JXMobile.executeJSON","_lineNumber":"279","_columnNumber":"7","_msg":"    at JXMobile.executeJSON@main.js.js:279:7"},{"_fileName":"JX_Evaluate","_functionName":"","_lineNumber":"1","_columnNumber":"1","_msg":"    at @JX_Evaluate:1:1"},{"_fileName":"node.js","_functionName":"unknown","_lineNumber":"1472","_columnNumber":"1","_msg":""}]
,07-01 08:58:48.163  6795  6795 I chromium: [INFO:CONSOLE(57)] "App.js file failed to load : "No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js\nError: No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js\n    at $h.require@node.js:1472:1\n    at internal_methods.loadMainFile@main.js.js:260:5\n    at JXMobile.executeJSON@main.js.js:279:7\n    at @JX_Evaluate:1:1\n"", source: file:///android_asset/www/js/thali_main.js (57)
,07-01 08:58:48.163  6795  6795 I chromium: [INFO:CONSOLE(62)] "****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****", source: file:///android_asset/www/js/thali_main.js (62)
,07-01 08:58:48.163  1017  1319 D FocusedStackFrame: Set to : 0
07-01 08:58:48.163  1017  1319 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
07-01 08:58:48.163  1017  1319 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.sec.android.app.launcher
07-01 08:58:48.163  1017  1319 D InputDispatcher: Focused application set to: xxxx
07-01 08:58:48.163  1017  1319 D InputDispatcher: Focus left window: 6795
07-01 08:58:48.173  1017  1047 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
07-01 08:58:48.173  1017  1047 D PointerIcon: setMouseCustomIcon IconType is same.101
07-01 08:58:48.173  1017  1319 I ActivityManager: Killing 5777:com.sec.android.gallery3d/u0a39 (adj 15): empty #21
,07-01 08:58:48.183  6795  6795 D io.jxcore.node.LifeCycleMonitor: onActivityDestroyed
07-01 08:58:48.183  6795  6795 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: DESTROYED
,07-01 08:58:48.183  6795  6795 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-01 08:58:48.183  6795  6795 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-01 08:58:48.183  6795  6795 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-01 08:58:48.183  6795  6795 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
07-01 08:58:48.183  6795  6795 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c2daf8d removed from the list
07-01 08:58:48.183  6795  6795 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-01 08:58:48.183  6795  6795 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@815d290 removed from the list
07-01 08:58:48.183  6795  6795 D io.jxcore.node.ConnectivityMonitor: stop
07-01 08:58:48.183  6795  6795 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: No more listeners, de-initializing...
,07-01 08:58:48.183  6795  6795 I io.jxcore.node.LifeCycleMonitor: stop: OK
,07-01 08:58:48.183  6795  6842 W PluginManager: THREAD WARNING: exec() call to CoreAndroid.exitApp blocked the main thread for 23ms. Plugin should use CordovaInterface.getThreadPool().
,07-01 08:58:48.203   259  1162 I SurfaceFlinger: id=13 Removed NainActivit (6/8)
,07-01 08:58:48.203   259   456 I SurfaceFlinger: id=13 Removed NainActivit (-2/8)
07-01 08:58:48.203  1017  1552 W ActivityManager: mDVFSHelper.acquire()
,07-01 08:58:48.213  1017  1552 V WindowManager: rotationForOrientationLw(orient=1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false
,07-01 08:58:48.233  1507  1507 D Launcher: onRestart, Launcher: 744153686
,07-01 08:58:48.233  1507  1507 D Launcher: onStart, Launcher: 744153686
07-01 08:58:48.233  1507  1507 D Launcher.HomeView: onStart
07-01 08:58:48.233  1507  1507 D Launcher: onResume, Launcher: 744153686
07-01 08:58:48.243  1017  1505 D SettingsProvider: name = kids_home_mode
07-01 08:58:48.243  1017  1505 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
07-01 08:58:48.243  1017  1505 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
07-01 08:58:48.243  1017  1505 D SettingsProvider: selectionArgs: false
07-01 08:58:48.243  1017  1505 D SettingsProvider: selectionArgs: 10006
07-01 08:58:48.243  1017  1505 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
07-01 08:58:48.243  1017  1505 D SettingsProvider: ret = -1
,07-01 08:58:48.243  1507  1507 D Launcher.HomeView: onResume
,07-01 08:58:48.243  1507  1507 D Launcher: Launcher::setSystemUiTransparency(): getSystemUiVisibility() after setting  = 0
,07-01 08:58:48.253  1507  1507 D MenuAppsGridFragment: onResume
,07-01 08:58:48.253  1017  1042 W ActivityManager: userId = 0, bbcId = -10000
,07-01 08:58:48.253  1507  1507 D WallpaperManager: SEC_PRODUCT_FEATURE_COMMON_SUPPORT_TEXTURE_COMPRESSION is true
07-01 08:58:48.253  1017  1042 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
07-01 08:58:48.253  1017  1042 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.android.contacts
07-01 08:58:48.263  1507  1507 D WallpaperManager: SEC_PRODUCT_FEATURE_COMMON_SUPPORT_TEXTURE_COMPRESSION is true
,07-01 08:58:48.263  1017  1136 I splitIntent: Split this intent : com.sec.android.intent.action.HOME_RESUME, mSplitNum[0]=3, mSplitNum[1]=7, mSplitNum[2]=9, mBgSplitQueueNum=3 divideNum= 2 r.nextReceiver= 1 receivers.size=11
,07-01 08:58:48.273  1017  1136 I splitIntent: finish to split intent : com.sec.android.intent.action.HOME_RESUME !! Enqueue -> schedule it!!
,07-01 08:58:48.273  1017  1136 W ActivityManager: userId = 0, bbcId = -10000
,07-01 08:58:48.273  1017  1136 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
07-01 08:58:48.273  1017  1136 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.sec.android.gallery3d
07-01 08:58:48.273  1017  1136 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.gallery3d, hostingType: broadcast
07-01 08:58:48.273  1017  1136 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-01 08:58:48.273  1017  1136 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-01 08:58:48.273  1017  1136 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-01 08:58:48.273  1017  1136 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-01 08:58:48.293  6851  6851 E Zygote  : MountEmulatedStorage()
07-01 08:58:48.293  6851  6851 E Zygote  : v2
07-01 08:58:48.293  6851  6851 I libpersona: KNOX_SDCARD checking this for 10039
07-01 08:58:48.293  6851  6851 I libpersona: KNOX_SDCARD not a persona
07-01 08:58:48.293  6851  6851 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
07-01 08:58:48.293  1017  1136 I ActivityManager: Start proc com.sec.android.gallery3d for broadcast com.sec.android.gallery3d/.app.MediaScannerReceiver: pid=6851 uid=10039 gids={50039, 9997, 3003, 1028, 1015, 1023, 3002} abi=armeabi-v7a
07-01 08:58:48.293  1017  1562 D ActivityManager: handle home activity for 0
07-01 08:58:48.293  1017  1017 D PersonaManagerService: getPersonasForUser(): returning null!
07-01 08:58:48.293  1017  1562 I WallpaperManagerService: switchPersonaWallpaper is called for personaId-0
07-01 08:58:48.293  1017  1562 D KnoxTimeoutHandler: post home show event for user 0
07-01 08:58:48.293  1017  1562 D ActivityManager: post active user change for 0 fullscreen true record.isFloatingActivity() false
07-01 08:58:48.293  1017  1562 D KnoxTimeoutHandler: postActiveUserChange for user 0
07-01 08:58:48.293  1017  1562 I KnoxTimeoutHandler: postActiveUserChange, showWhenLocked: false
07-01 08:58:48.293  1017  1017 D WallpaperManagerService:  force update = false; persona id = 0; current user =0; current persona = 0
07-01 08:58:48.293  1017  1017 D KnoxTimeoutHandler: handleHomeShow for 0 and current 0
07-01 08:58:48.293  1017  1017 D KnoxTimeoutHandler: handleActiveUserChange for user 0
07-01 08:58:48.293  6851  6851 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
07-01 08:58:48.303  6851  6851 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
07-01 08:58:48.303  1017  1042 W ActivityManager: userId = 0, bbcId = -10000
07-01 08:58:48.303  1017  1042 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
07-01 08:58:48.303  1017  1042 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.android.settings
07-01 08:58:48.303  1507  1507 D Launcher.HomeView: onPause
07-01 08:58:48.303  1507  1507 D Launcher: Launcher::setSystemUiTransparency(): getSystemUiVisibility() after setting  = 0
07-01 08:58:48.303  1017  1042 W ActivityManager: userId = 0, bbcId = -10000
07-01 08:58:48.303  1017  1042 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.widgetapp.dualclockdigital, hostingType: broadcast
07-01 08:58:48.303  1017  1042 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
07-01 08:58:48.303  1017  1042 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.sec.android.widgetapp.dualclockdigital
07-01 08:58:48.313  1017  1042 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-01 08:58:48.313  1017  1042 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-01 08:58:48.313  1017  1042 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-01 08:58:48.313  1017  1042 E ActivityManager: checkUser: useridlist=null, currentuser=0
,07-01 08:58:48.333  6867  6867 E Zygote  : MountEmulatedStorage()
07-01 08:58:48.333  6867  6867 E Zygote  : v2
07-01 08:58:48.333  6867  6867 I libpersona: KNOX_SDCARD checking this for 10089
07-01 08:58:48.333  6867  6867 I libpersona: KNOX_SDCARD not a persona
07-01 08:58:48.333  6867  6867 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
07-01 08:58:48.333  6867  6867 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
07-01 08:58:48.333  1017  1042 I ActivityManager: Start proc com.sec.android.widgetapp.dualclockdigital for broadcast com.sec.android.widgetapp.dualclockdigital/.DigitalDualClockWidgetProvider: pid=6867 uid=10089 gids={50089, 9997, 3003} abi=armeabi-v7a
07-01 08:58:48.333  6867  6867 E SELinux : [DEBUG] get_category: variable seinfo: shared sensitivity: NULL, cateogry: NULL
,07-01 08:58:48.333  1017  1042 W ActivityManager: userId = 0, bbcId = -10000
07-01 08:58:48.333  1017  1042 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.widgetapp.activeapplicationwidget, hostingType: broadcast
07-01 08:58:48.333  1017  1042 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
07-01 08:58:48.333  1017  1042 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.sec.android.widgetapp.activeapplicationwidget
,07-01 08:58:48.333  1017  1042 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-01 08:58:48.333  1017  1042 E ActivityManager: checkUser: useridlist=null, currentuser=0
,07-01 08:58:48.333  1017  1042 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-01 08:58:48.333  1017  1042 E ActivityManager: checkUser: useridlist=null, currentuser=0
,07-01 08:58:48.343  6851  6851 D TimaKeyStoreProvider: TimaSignature is unavailable
07-01 08:58:48.343  6851  6851 D ActivityThread: Added TimaKeyStore provider
,07-01 08:58:48.353  6878  6878 E Zygote  : MountEmulatedStorage()
,07-01 08:58:48.353  6878  6878 E Zygote  : v2
07-01 08:58:48.353  6878  6878 I libpersona: KNOX_SDCARD checking this for 10139
07-01 08:58:48.353  6878  6878 I libpersona: KNOX_SDCARD not a persona
,07-01 08:58:48.353  6878  6878 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,07-01 08:58:48.353  1017  1042 I ActivityManager: Start proc com.sec.android.widgetapp.activeapplicationwidget for broadcast com.sec.android.widgetapp.activeapplicationwidget/.ProgramMonitorProvider: pid=6878 uid=10139 gids={50139, 9997, 1028, 1015} abi=armeabi-v7a
07-01 08:58:48.363  6878  6878 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,07-01 08:58:48.363  6878  6878 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,07-01 08:58:48.363  1017  1318 W ActivityManager: userId = 0, bbcId = -10000
07-01 08:58:48.363  1017  1318 W BroadcastQueue: Permission Denial: broadcasting Intent { act=com.sec.android.intent.action.HOME_RESUME flg=0x10 } from com.sec.android.app.launcher (pid=1507, uid=10006) is not exported from uid 1000 due to receiver com.android.settings/.accessibilitywidget.AccessibilityEasyWidgetProviderAssistiveLight
07-01 08:58:48.363  1017  1318 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
07-01 08:58:48.363  1017  1318 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.android.settings
,07-01 08:58:48.373  1017  1042 W ActivityManager: userId = 0, bbcId = -10000
07-01 08:58:48.373  1017  1042 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
07-01 08:58:48.373  1017  1042 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.android.systemui
,07-01 08:58:48.383   259   259 I SurfaceFlinger: id=14 createSurf (540x960),1 flag=4, Mauncher
,07-01 08:58:48.383  1017  1045 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
,07-01 08:58:48.383  6851  6851 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
,07-01 08:58:48.383  6851  6851 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
07-01 08:58:48.383  6851  6851 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
07-01 08:58:48.383  6851  6851 W ResourcesManager: Asset path '/system/framework/secimaging.jar' does not exist or contains no resources.
07-01 08:58:48.383  6851  6851 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
07-01 08:58:48.383  6851  6851 W ResourcesManager: Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
07-01 08:58:48.383  6851  6851 W ResourcesManager: Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,07-01 08:58:48.383  2625  2625 D Recents_RecreateReceiver: onReceive by home
07-01 08:58:48.383  1017  1045 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
,07-01 08:58:48.393  1017  1318 W ActivityManager: userId = 0, bbcId = -10000
07-01 08:58:48.393  1017  1318 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.widgetapp.digitalclock, hostingType: broadcast
07-01 08:58:48.393  1017  1318 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
07-01 08:58:48.393  1017  1318 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.sec.android.widgetapp.digitalclock
07-01 08:58:48.393  1017  1559 D InputDispatcher: Focus entered window: 1507
,07-01 08:58:48.393  6878  6878 D TimaKeyStoreProvider: TimaSignature is unavailable
,07-01 08:58:48.393  1017  1047 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
07-01 08:58:48.393  1017  1047 D PointerIcon: setMouseCustomIcon IconType is same.101
07-01 08:58:48.393  6867  6867 D TimaKeyStoreProvider: TimaSignature is unavailable
07-01 08:58:48.393  1507  1507 D SRIB_DCS: log_dcs ThreadedRenderer::initialize entered! 
07-01 08:58:48.393  6867  6867 D ActivityThread: Added TimaKeyStore provider,
07-01 08:58:48.393  1017  1318 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-01 08:58:48.393  6878  6878 D ActivityThread: Added TimaKeyStore provider
07-01 08:58:48.393  1017  1318 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-01 08:58:48.393  1017  1318 E ActivityManager: checkUser: useridlist=null, currentuser=0,
07-01 08:58:48.393  1017  1318 E ActivityManager: checkUser: useridlist=null, currentuser=0
,07-01 08:58:48.403  1507  1507 D Launcher.HomeView: onStop
07-01 08:58:48.403  1507  1507 V ActivityThread: updateVisibility : ActivityRecord{3756368d token=android.os.BinderProxy@591c66e {com.sec.android.app.launcher/com.android.launcher2.Launcher}} show : true
07-01 08:58:48.403  1017  4379 D InputMethodManagerService: windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,07-01 08:58:48.413  6795  6795 W IInputConnectionWrapper: showStatusIcon on inactive InputConnection
,07-01 08:58:48.413  1017  6898 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.android.server.InputMethodManagerService$6.run:2762 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,07-01 08:58:48.413  1994  1994 D SamsungIME: onStartInput: No inputType, No imeOption, isInputViewShown = false, isExtractViewShown = false, isShowInputRequested = false, isConfigChanged = false
,07-01 08:58:48.413  6899  6899 E Zygote  : MountEmulatedStorage(),
07-01 08:58:48.413  6899  6899 E Zygote  : v2
07-01 08:58:48.413  6899  6899 I libpersona: KNOX_SDCARD checking this for 10084
,07-01 08:58:48.413  6899  6899 I libpersona: KNOX_SDCARD not a persona
,07-01 08:58:48.423  1017  1318 I ActivityManager: Start proc com.sec.android.widgetapp.digitalclock for broadcast com.sec.android.widgetapp.digitalclock/.DigitalClockWidgetProvider: pid=6899 uid=10084 gids={50084, 9997} abi=armeabi-v7a
,07-01 08:58:48.423  6899  6899 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,07-01 08:58:48.423  6899  6899 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
07-01 08:58:48.423  6899  6899 E SELinux : [DEBUG] get_category: variable seinfo: shared sensitivity: NULL, cateogry: NULL
,07-01 08:58:48.423  1181  1181 I StatusBar: Icon Only
,07-01 08:58:48.423  1181  1181 D PanelView: There is/are notification(s) 
,07-01 08:58:48.453  1507  1507 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@591c66e time:144102
,07-01 08:58:48.453  6899  6899 D TimaKeyStoreProvider: TimaSignature is unavailable
07-01 08:58:48.453  6899  6899 D ActivityThread: Added TimaKeyStore provider
,07-01 08:58:48.463  6848  6848 D AndroidRuntime: 
07-01 08:58:48.463  6848  6848 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
,07-01 08:58:48.463  6867  6867 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
07-01 08:58:48.463  6867  6867 W ResourcesManager: Asset path '/system/framework/sec_feature.jar' does not exist or contains no resources.
,07-01 08:58:48.463  6848  6848 D AndroidRuntime: CheckJNI is OFF
07-01 08:58:48.463  6848  6848 D AndroidRuntime: readGMSProperty: start
07-01 08:58:48.463  6848  6848 D AndroidRuntime: readGMSProperty: already setted!!
07-01 08:58:48.463  6848  6848 D AndroidRuntime: propertySet: couldn't set property (it is from app)
07-01 08:58:48.463  6848  6848 D AndroidRuntime: readGMSProperty: could not set the property(default)!!
07-01 08:58:48.463  6848  6848 D AndroidRuntime: readGMSProperty: end
07-01 08:58:48.463  6848  6848 D AndroidRuntime: addProductProperty: start
,07-01 08:58:48.473  6878  6878 V TaskCloserActivity: TaskCloserActivity enter()
,07-01 08:58:48.473  1017  1047 W ActivityManager: mDVFSHelper.release()
07-01 08:58:48.473  1017  1047 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{19dc7ce u0 com.sec.android.app.launcher/com.android.launcher2.Launcher t79} time:144128
,07-01 08:58:48.483  6899  6899 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,07-01 08:58:48.493  1017  1017 D WindowOrientationListener:   mReceiver.onReceive :com.samsung.intent.action.AUTOROTATION,  delay = 200
,07-01 08:58:48.503  6878  6878 V TaskCloserActivity: TaskCloserActivity onReceive() - com.sec.android.intent.action.HOME_RESUME
,07-01 08:58:48.503  1017  1552 W ActivityManager: userId = 0, bbcId = -10000
07-01 08:58:48.503  1017  1552 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
07-01 08:58:48.503  1017  1552 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.android.phone
,07-01 08:58:48.503  1017  1552 I ActivityManager: Killing 6430:com.samsung.android.app.assistantmenu/1000 (adj 15): empty #21
,07-01 08:58:48.523  1017  1498 I ActivityManager: Killing 6452:com.google.android.partnersetup/u0a14 (adj 15): empty #21
,07-01 08:58:48.523  1017  1498 W ActivityManager: userId = 0, bbcId = -10000
07-01 08:58:48.523  1017  1498 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.app.camera, hostingType: broadcast
07-01 08:58:48.523  1017  1498 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
07-01 08:58:48.523  1017  1498 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.sec.android.app.camera
07-01 08:58:48.523  1017  1498 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-01 08:58:48.523  1017  1498 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-01 08:58:48.523  1017  1498 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-01 08:58:48.523  1017  1498 E ActivityManager: checkUser: useridlist=null, currentuser=0
,07-01 08:58:48.543  6925  6925 E Zygote  : MountEmulatedStorage()
,07-01 08:58:48.543  6925  6925 E Zygote  : v2
07-01 08:58:48.543  6925  6925 I libpersona: KNOX_SDCARD checking this for 10135
07-01 08:58:48.543  6925  6925 I libpersona: KNOX_SDCARD not a persona
,07-01 08:58:48.543  6925  6925 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,07-01 08:58:48.543  1017  1498 I ActivityManager: Start proc com.sec.android.app.camera for broadcast com.sec.android.app.camera/.HomeResumeCamera: pid=6925 uid=10135 gids={50135, 9997, 1028, 1015, 3003, 1023} abi=armeabi-v7a
07-01 08:58:48.543  1017  1498 I ActivityManager: Killing 6518:com.sec.pcw.device/1000 (adj 15): empty #21
,07-01 08:58:48.543  6925  6925 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051,
,07-01 08:58:48.543  6925  6925 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL,
,07-01 08:58:48.553  1017  1030 D PersonaManager: isKioskContainerExistOnDevice
,07-01 08:58:48.573  6925  6925 D TimaKeyStoreProvider: TimaSignature is unavailable
,07-01 08:58:48.573  6925  6925 D ActivityThread: Added TimaKeyStore provider
,07-01 08:58:48.583  6925  6925 W ResourcesManager: Asset path '/system/framework/secmediarecorder.jar' does not exist or contains no resources.
07-01 08:58:48.583  6925  6925 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
07-01 08:58:48.583  6925  6925 W ResourcesManager: Asset path '/system/framework/secimaging.jar' does not exist or contains no resources.
07-01 08:58:48.583  6925  6925 W ResourcesManager: Asset path '/system/framework/seccamera.jar' does not exist or contains no resources.
,07-01 08:58:48.583  6925  6925 W ResourcesManager: Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,07-01 08:58:48.593  6851  6851 D NearbySource: Nearby Source Create!
07-01 08:58:48.593  6851  6851 D NearbyContext: Nearby Context Create!
,07-01 08:58:48.603  1017  1552 I ActivityManager: Killing 6537:com.samsung.android.app.galaxyfinder/u0a29 (adj 15): empty #21
,07-01 08:58:48.603  6848  6848 E AffinityControl: AffinityControl: registerfunction enter
,07-01 08:58:48.633  6848  6848 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
,07-01 08:58:48.643   258   536 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.sec.android.gallery3d/cache/
07-01 08:58:48.643  6851  6851 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.sec.android.gallery3d/cache
07-01 08:58:48.643   258   536 W Vold    : Returning OperationFailed - no handler for errno 0
,07-01 08:58:48.643  6851  6851 D SLinkSource: Samsung link source created
,07-01 08:58:48.643  1017  4379 D PersonaManagerService: isFromApprovedUnInstaller: uid, userId, appid : 2000 0 2000
07-01 08:58:48.643  1017  4379 D PackageManager: START PACKAGE DELETE: observer{1015607602}
07-01 08:58:48.643  1017  4379 D PackageManager: pkg{<packageName>}
07-01 08:58:48.643  1017  4379 D PackageManager: user{0}
07-01 08:58:48.643  1017  4379 D PackageManager: caller{2000}
07-01 08:58:48.643  1017  4379 D PackageManager: flags{2}
07-01 08:58:48.643  1017  4379 D PersonaManagerService: isFromApprovedUnInstaller: isApproved : true
07-01 08:58:48.643  1017  1057 D PackageManager: [MSG] DELETE_PACKAGE_AS_USER
07-01 08:58:48.643  1017  4379 D PersonaManagerService: isFromApprovedUnInstaller: isApproved before exit: true
07-01 08:58:48.643  1017  4379 D PackageManager: deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag2
07-01 08:58:48.643  1017  4379 D PackageManager: deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag2
07-01 08:58:48.643  1017  1057 D PackageManagerService: deletePackage- pkg:com.test.thalitest, edmuserId:0
07-01 08:58:48.643  1017  1057 D PackageManagerService: deletePackage- pkg:com.test.thalitest, edmuserId:-1
07-01 08:58:48.643  1017  1057 D ApplicationPolicy: getApplicationUninstallationEnabled
07-01 08:58:48.643  1017  1057 D ApplicationPolicy: getApplicationUninstallationEnabled :  enabled true
,07-01 08:58:48.643  1017  1057 D PackageManager: !@killApplicatoin: 10151, uninstall pkg
,07-01 08:58:48.653  1017  1042 I ActivityManager: Force stopping com.test.thalitest appid=10151 user=-1: uninstall pkg
,07-01 08:58:48.653  1017  1042 I ActivityManager: Killing 6795:com.test.thalitest/u0a151 (adj 15): stop com.test.thalitest cause uninstall pkg
,07-01 08:58:48.763  1017  1498 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,07-01 08:58:48.773  6851  6942 D ContactProvider: getAllContactInfoList Start
,07-01 08:58:48.773  1017  1502 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,07-01 08:58:48.773  6851  6851 D GalleryCacheReady: Receive : home resume
,07-01 08:58:48.783  1017  4141 W ActivityManager: userId = 0, bbcId = -10000
,07-01 08:58:48.783  1017  4141 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
07-01 08:58:48.783  1017  4141 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.android.mms
,07-01 08:58:48.783  6472  6472 D Mms/UIEventReceiver: ui event
,07-01 08:58:48.783  1017  1057 I ActivityManager: Force stopping com.test.thalitest appid=10151 user=0: pkg removed
,07-01 08:58:48.823  1017  1057 W ActivityManager: CustomStartingWindow se packge removed so remove capture also
,07-01 08:58:48.823  6152  6152 I art     : Explicit concurrent mark sweep GC freed 12938(711KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 4MB/6MB, paused 932us total 33.554ms
,07-01 08:58:48.833   332   332 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 3
,07-01 08:58:48.853  6648  6648 I art     : Explicit concurrent mark sweep GC freed 22895(1192KB) AllocSpace objects, 0(0B) LOS objects, 50% free, 3MB/7MB, paused 970us total 35.039ms
,07-01 08:58:48.863  1017  1099 I InputReader: Reconfiguring input devices.  changes=0x00000010
,07-01 08:58:48.873  6213  6213 I art     : Explicit concurrent mark sweep GC freed 17162(1843KB) AllocSpace objects, 0(0B) LOS objects, 27% free, 5MB/7MB, paused 1.422ms total 71.210ms
,07-01 08:58:48.883  1675  1870 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
,07-01 08:58:48.893  1994  1994 E SamsungIME: mOCRHelper is null
,07-01 08:58:48.893  1017  1042 I splitIntent: Queue : background intent com.sec.android.intent.action.HOME_RESUME is finished at BG and BG split queue. set mSplitStart  false.
,07-01 08:58:48.903  1017  1042 W ActivityManager: userId = 0, bbcId = -10000
,07-01 08:58:48.903  1017  1042 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
07-01 08:58:48.903  1017  1042 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.sec.android.widgetapp.activeapplicationwidget
,07-01 08:58:48.903  1017  4141 I splitIntent: Do not split the intent. r.nextReceiver = 3 receivers.size =11 intent : com.sec.android.intent.action.HOME_RESUME
,07-01 08:58:48.913  1017  1123 V NetworkStats: removeUidsLocked() for UIDs [10151]
07-01 08:58:48.913  1017  1123 D NtpTrustedTime: currentTimeMillis() cache hit
07-01 08:58:48.913  1017  1123 V NetworkStats: performPollLocked(flags=0x3)
,07-01 08:58:48.913  1017  1123 D NetworkStatsFactory: UpdateStatsForKnox updated
07-01 08:58:48.913  1017  1123 D NetworkStatsFactory: UpdateStatsForKnox main else ---
,07-01 08:58:48.913  1017  1123 V NetworkStats: performPollLocked() took 6ms
07-01 08:58:48.913  1017  1123 D NtpTrustedTime: currentTimeMillis() cache hit
,07-01 08:58:48.913  1017  1041 D EnterpriseDeviceManagerService: Package has changed for user 0
07-01 08:58:48.913  1017  1041 D EnterpriseDeviceManagerService: Admin package name: com.google.android.gms
07-01 08:58:48.913  1017  1041 W TextServicesManagerService: no available spell checker services found
,07-01 08:58:48.923  6878  6878 V TaskCloserActivity: TaskCloserActivity onReceive() - com.sec.android.intent.action.HOME_PAUSE
,07-01 08:58:48.923  1465  1465 D PersonaManager: isKioskContainerExistOnDevice
,07-01 08:58:48.933  1465  1465 D RegisteredServicesCache: empty dynamic service
,07-01 08:58:48.943  4362  4362 I KLMS-2.5.123: : KLMSAbstractReciever(): onReceive(): Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.samsung.klmsagent/.listner.MainReciver (has extras) } | timestamp: Fri Jul 01 08:58:48 GMT+02:00 2016
,07-01 08:58:48.943  1017  4141 D ActivityManager: startService callerProcessName:com.samsung.klmsagent, calleePkgName: com.samsung.klmsagent
07-01 08:58:48.943  1017  4141 D ActivityManager: retrieveServiceLocked(): component = com.samsung.klmsagent/com.samsung.klmsagent.services.KLMSIntentService; callingUser = 0; userId(target) = 0
,07-01 08:58:48.943  1017  4141 W ActivityManager: userId = 0, bbcId = -10000
07-01 08:58:48.943  1017  4141 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
07-01 08:58:48.943  1017  4141 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.klmsagent, destAppInfo.processName = com.samsung.klmsagent
,07-01 08:58:48.953  1465  1465 D RegisteredComponentCache: Collect Tech packages for Knox
07-01 08:58:48.953  4362  4362 I KLMS-2.5.123: : KLMSAbstractReciever(): onReceive().END.
,07-01 08:58:48.953  1017  1041 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,07-01 08:58:48.953  1465  1465 D PersonaManager: isKioskContainerExistOnDevice
07-01 08:58:48.953  1017  1552 I splitIntent: Split this intent : android.intent.action.PACKAGE_REMOVED, mSplitNum[0]=12, mSplitNum[1]=23, mSplitNum[2]=33, mBgSplitQueueNum=3 divideNum= 10 r.nextReceiver= 1 receivers.size=43
07-01 08:58:48.953  1017  1552 I splitIntent: finish to split intent : android.intent.action.PACKAGE_REMOVED !! Enqueue -> schedule it!!
,07-01 08:58:48.973  1017  1041 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,07-01 08:58:48.973  1017  1552 D ActivityManager: startProcessLocked calleePkgName: com.sec.esdk.elm, hostingType: broadcast
,07-01 08:58:48.973  4362  4362 I KLMS-2.5.123: : KLMSIntentService(): onCreate()
,07-01 08:58:48.983  1017  1552 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-01 08:58:48.983  1017  1552 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-01 08:58:48.983  1017  1552 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-01 08:58:48.983  1017  1552 E ActivityManager: checkUser: useridlist=null, currentuser=0
,07-01 08:58:48.983  4362  4362 I KLMS-2.5.123: : KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,07-01 08:58:48.993  6945  6945 E Zygote  : MountEmulatedStorage()
07-01 08:58:48.993  6945  6945 E Zygote  : v2
07-01 08:58:48.993  6945  6945 I libpersona: KNOX_SDCARD checking this for 10090
07-01 08:58:48.993  6945  6945 I libpersona: KNOX_SDCARD not a persona
,07-01 08:58:49.003  6945  6945 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,07-01 08:58:49.003  1017  1552 I ActivityManager: Start proc com.sec.esdk.elm for broadcast com.sec.esdk.elm/.receiver.MainReceiver: pid=6945 uid=10090 gids={50090, 9997, 3003} abi=armeabi-v7a
,07-01 08:58:49.003  1017  1124 D NtpTrustedTime: currentTimeMillis() cache hit
07-01 08:58:49.003  6945  6945 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,07-01 08:58:49.003  1017  1124 D NtpTrustedTime: currentTimeMillis() cache hit
,07-01 08:58:49.003  6945  6945 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL,
07-01 08:58:49.013  1017  1042 D ActivityManager: startProcessLocked calleePkgName: com.sec.spp.push, hostingType: broadcast
,07-01 08:58:49.013  4362  4362 I KLMS-2.5.123: : KLMSUtility(): isTestMode(): product_ship: true | testApk: false
,07-01 08:58:49.013  1017  1042 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-01 08:58:49.013  1017  1042 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-01 08:58:49.013  1017  1042 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-01 08:58:49.013  1017  1042 E ActivityManager: checkUser: useridlist=null, currentuser=0
,07-01 08:58:49.023  1017  1017 I art     : Explicit concurrent mark sweep GC freed 54517(3MB) AllocSpace objects, 18(288KB) LOS objects, 33% free, 23MB/34MB, paused 3.148ms total 204.078ms
,07-01 08:58:49.023   315   315 I art     : Explicit concurrent mark sweep GC freed 8679(369KB) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 715us total 21.503ms
07-01 08:58:49.023  1017  1057 I art     : WaitForGcToComplete blocked for 117.017ms for cause Explicit
,07-01 08:58:49.023  4362  6944 I KLMS-2.5.123: : KLMSIntentService(): onHandleIntent().START: Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.samsung.klmsagent/.services.KLMSIntentService (has extras) }
,07-01 08:58:49.043   315   315 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 753us total 16.934ms
,07-01 08:58:49.043  4362  6944 I KLMS-2.5.123: : KLMSIntentService(): PACKAGE_REMOVED
,07-01 08:58:49.043  1017  4381 D SecContentProvider2: uri = 11 selection = getMyKnoxAdmin
07-01 08:58:49.043  1017  4381 D SecContentProvider2: mCursor = null
,07-01 08:58:49.043  6945  6945 D TimaKeyStoreProvider: TimaSignature is unavailable
,07-01 08:58:49.053  4362  6944 I KLMS-2.5.123: : KLMSIntentService(): listeningToPackageRemoved().START
07-01 08:58:49.053  6945  6945 D ActivityThread: Added TimaKeyStore provider
,07-01 08:58:49.053  4362  6944 I KLMS-2.5.123: : KLMSIntentService(): REPLACING: false | pkgName: com.test.thalitest
,07-01 08:58:49.053   315   315 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 584us total 16.644ms
,07-01 08:58:49.063  6960  6960 E Zygote  : MountEmulatedStorage()
07-01 08:58:49.063  6960  6960 E Zygote  : v2
07-01 08:58:49.063  6960  6960 I libpersona: KNOX_SDCARD checking this for 10032
07-01 08:58:49.063  6960  6960 I libpersona: KNOX_SDCARD not a persona
,07-01 08:58:49.073  6960  6960 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,07-01 08:58:49.073  6960  6960 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,07-01 08:58:49.073  1017  1042 I ActivityManager: Start proc com.sec.spp.push for broadcast com.sec.spp.push/.receiver.PackageInfoChangeReceiver: pid=6960 uid=10032 gids={50032, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,07-01 08:58:49.073  6960  6960 E SELinux : [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
07-01 08:58:49.073  1017  1042 D ActivityManager: startProcessLocked calleePkgName: com.google.android.googlequicksearchbox, hostingType: broadcast
,07-01 08:58:49.083  1017  1042 E ActivityManager: checkUser: useridlist=null, currentuser=0
,07-01 08:58:49.083  1017  1042 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-01 08:58:49.083  1017  1042 E ActivityManager: checkUser: useridlist=null, currentuser=0,
07-01 08:58:49.083  1017  1042 E ActivityManager: checkUser: useridlist=null, currentuser=0
,07-01 08:58:49.093  1017  1017 D RCPManagerService: PackageReceiver onReceive()
07-01 08:58:49.093  1017  1017 I HarmonyEASService: onReceive : android.intent.action.PACKAGE_REMOVED for 0
,07-01 08:58:49.103  1017  1041 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,07-01 08:58:49.113  6975  6975 E Zygote  : MountEmulatedStorage()
07-01 08:58:49.113  6975  6975 I libpersona: KNOX_SDCARD checking this for 10052
07-01 08:58:49.113  6975  6975 E Zygote  : v2
07-01 08:58:49.113  6975  6975 I libpersona: KNOX_SDCARD not a persona
,07-01 08:58:49.113  6975  6975 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,07-01 08:58:49.113  6960  6960 D TimaKeyStoreProvider: TimaSignature is unavailable
07-01 08:58:49.113  1017  1017 D KnoxMUMContainerPolicy: mPackageReceiver : action - android.intent.action.PACKAGE_REMOVED,
07-01 08:58:49.113  1017  1017 I OTPFW   : PackageRemovalReceiver::onReceive Enter
07-01 08:58:49.113  1017  1017 D OTPFW   : PackageRemovalReceiver::onReceive deleting token for Pkg = com.test.thalitest uid = 10151 container id = 0
07-01 08:58:49.113  6960  6960 D ActivityThread: Added TimaKeyStore provider
,07-01 08:58:49.113  6975  6975 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051,
07-01 08:58:49.113  1017  1017 I OTPFW   : ProvisionData::getAllEntries Enter
07-01 08:58:49.113  1017  1017 E OTPFW   : ProvisionData::getAllEntries Table is empty
07-01 08:58:49.113  1017  1041 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
07-01 08:58:49.113  6975  6975 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,07-01 08:58:49.123  1017  1042 I ActivityManager: Start proc com.google.android.googlequicksearchbox:search for broadcast com.google.android.googlequicksearchbox/com.google.android.search.core.icingsync.IcingCorporaChangedReceiver: pid=6975 uid=10052 gids={50052, 9997, 3003, 3001, 1028, 3002, 1015} abi=armeabi-v7a
,07-01 08:58:49.123  1017  1042 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.app.watchmanagerstub, hostingType: broadcast
,07-01 08:58:49.123  1017  1042 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-01 08:58:49.123  1017  1042 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-01 08:58:49.123  1017  1042 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-01 08:58:49.123  1017  1042 E ActivityManager: checkUser: useridlist=null, currentuser=0
,07-01 08:58:49.143  6989  6989 E Zygote  : MountEmulatedStorage()
07-01 08:58:49.143  6989  6989 I libpersona: KNOX_SDCARD checking this for 10098
07-01 08:58:49.143  6989  6989 E Zygote  : v2
07-01 08:58:49.143  6989  6989 I libpersona: KNOX_SDCARD not a persona
,07-01 08:58:49.153  6989  6989 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,07-01 08:58:49.153  6989  6989 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
07-01 08:58:49.153  6989  6989 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,07-01 08:58:49.153  6975  6975 D TimaKeyStoreProvider: TimaSignature is unavailable,
07-01 08:58:49.153  1017  1042 I ActivityManager: Start proc com.samsung.android.app.watchmanagerstub for broadcast com.samsung.android.app.watchmanagerstub/com.sec.android.applicationmgr.PackageIntentReceiver: pid=6989 uid=10098 gids={50098, 9997, 3003, 1028, 1015, 3002, 3001} abi=armeabi-v7a
07-01 08:58:49.153  6975  6975 D ActivityThread: Added TimaKeyStore provider
,07-01 08:58:49.173  4362  6944 I KLMS-2.5.123: : KLMSIntentService(): Notification App List is Null. Remove Notification.
,07-01 08:58:49.193  6989  6989 D TimaKeyStoreProvider: TimaSignature is unavailable
,07-01 08:58:49.193  6989  6989 D ActivityThread: Added TimaKeyStore provider
,07-01 08:58:49.203  6851  6942 D ContactProvider: getAllContactInfoList End
,07-01 08:58:49.203  6851  6942 I syncContacts: thread: 1248, sync time = 518
,07-01 08:58:49.223  4362  6944 I KLMS-2.5.123: : KLMSValidator(): IsPackageExistInDevice().Not Exsit: com.test.thalitest
,07-01 08:58:49.223  4362  6944 I KLMS-2.5.123: : KLMSIntentService(): listeningToPackageRemoved().END
,07-01 08:58:49.223  1017  1319 D ActivityManager: startProcessLocked calleePkgName: com.samsung.helphub, hostingType: broadcast
,07-01 08:58:49.223  1017  1319 E ActivityManager: checkUser: useridlist=null, currentuser=0
,07-01 08:58:49.223  1017  1319 E ActivityManager: checkUser: useridlist=null, currentuser=0
,07-01 08:58:49.223  1017  1319 E ActivityManager: checkUser: useridlist=null, currentuser=0
,07-01 08:58:49.223  1017  1319 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-01 08:58:49.223  6945  6945 D elm:15121: ELMAbstractReceiver.onReceive() : Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.receiver.MainReceiver (has extras) }
,07-01 08:58:49.233  6945  6945 D elm:15121: ELMEngine.ELMEngine( context ).
,07-01 08:58:49.233  4362  4362 I KLMS-2.5.123: : KLMSIntentService(): onDestroy()
,07-01 08:58:49.243  6945  6945 D elm:15121: MDMBridge.setEnterpriseBridge(),
,07-01 08:58:49.243  7007  7007 E Zygote  : MountEmulatedStorage(),
07-01 08:58:49.243  7007  7007 E Zygote  : v2
07-01 08:58:49.243  7007  7007 I libpersona: KNOX_SDCARD checking this for 1000
07-01 08:58:49.243  7007  7007 I libpersona: KNOX_SDCARD not a persona
07-01 08:58:49.243  7007  7007 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51,
,07-01 08:58:49.243  7007  7007 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051,
,07-01 08:58:49.243  7007  7007 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,07-01 08:58:49.253  1017  1319 I ActivityManager: Start proc com.samsung.helphub for broadcast com.samsung.helphub/.broadcast.HelpHubBroadcastReceiver: pid=7007 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,07-01 08:58:49.253  1017  1319 I ActivityManager: Killing 6416:com.google.android.apps.plus/u0a117 (adj 15): empty #21
,07-01 08:58:49.253  1017  1498 D ActivityManager: startService callerProcessName:com.sec.esdk.elm, calleePkgName: com.sec.esdk.elm
07-01 08:58:49.253  1017  1498 D ActivityManager: retrieveServiceLocked(): component = com.sec.esdk.elm/com.sec.esdk.elm.service.ElmAgentService; callingUser = 0; userId(target) = 0,
07-01 08:58:49.253  1017  1498 W ActivityManager: userId = 0, bbcId = -10000
07-01 08:58:49.253  1017  1498 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
07-01 08:58:49.253  1017  1498 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.esdk.elm, destAppInfo.processName = com.sec.esdk.elm,
,07-01 08:58:49.263  6945  6945 D elm:15121: ELMAbstractReceiver : Receive Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) } END.
,07-01 08:58:49.263  3615  3615 D AASAservice-UpdateReceiver: AASAUpdateReceiver: android.intent.action.PACKAGE_REMOVED, package = com.test.thalitest, uid = -1
,07-01 08:58:49.263  3615  3615 W System.err: android.content.pm.PackageManager$NameNotFoundException: com.test.thalitest
,07-01 08:58:49.273  3615  3615 W System.err: 	at android.app.ApplicationPackageManager.getApplicationInfo(ApplicationPackageManager.java:332)
07-01 08:58:49.273  3615  3615 W System.err: 	at com.samsung.aasaservice.AASAUpdateReceiver.onReceive(AASAUpdateReceiver.java:33)
07-01 08:58:49.273  3615  3615 W System.err: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:3125)
07-01 08:58:49.273  3615  3615 W System.err: 	at android.app.ActivityThread.access$1800(ActivityThread.java:181)
07-01 08:58:49.273  3615  3615 W System.err: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1559)
07-01 08:58:49.273  3615  3615 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-01 08:58:49.273  3615  3615 W System.err: 	at android.os.Looper.loop(Looper.java:145)
07-01 08:58:49.273  3615  3615 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
07-01 08:58:49.273  3615  3615 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
07-01 08:58:49.273  3615  3615 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
07-01 08:58:49.273  3615  3615 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
07-01 08:58:49.273  3615  3615 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
07-01 08:58:49.273  6945  6945 D elm:15121: ElmAgentService : onCreate()
,07-01 08:58:49.273  6960  7006 E SPPClientService: ============PushLog. commonIsShipBuild. stop!
,07-01 08:58:49.273  6960  7006 E SPPClientService: [PushClientApplication] Push log off : This is Ship build version
,07-01 08:58:49.273  6945  7016 D elm:15121: ElmAgentService : onHandleIntent() Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) }
07-01 08:58:49.273  6945  7016 D elm:15121: MainReceiver.listeningToPackageRemoved()
07-01 08:58:49.273  6945  7016 D elm:15121: MDMBridge.getInstance()
07-01 08:58:49.273  6945  7016 D elm:15121: MDMBridge.getAllLicenseInfoFromSDK()
,07-01 08:58:49.273  6945  7016 D elm:15121: MDMBridge.getAllLicenseInfoFromSDK()
,07-01 08:58:49.283  1017  1498 D ActivityManager: startProcessLocked calleePkgName: com.sec.spp.push, hostingType: broadcast
,07-01 08:58:49.283  6960  7006 D SPPClientService: PushLog.txt file is not deleted.
07-01 08:58:49.283  7007  7007 D TimaKeyStoreProvider: TimaSignature is unavailable
07-01 08:58:49.283  6960  7006 D SPPClientService: PushLog.txt file is not deleted.
07-01 08:58:49.283  6960  7006 D SPPClientService: ============PushLog. stop!
,07-01 08:58:49.283  7007  7007 D ActivityThread: Added TimaKeyStore provider
,07-01 08:58:49.283  1017  1498 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-01 08:58:49.283  1017  1498 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-01 08:58:49.283  1017  1498 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-01 08:58:49.283  1017  1498 E ActivityManager: checkUser: useridlist=null, currentuser=0
,07-01 08:58:49.293  7024  7024 E Zygote  : MountEmulatedStorage(),
07-01 08:58:49.293  7024  7024 I libpersona: KNOX_SDCARD checking this for 10032
07-01 08:58:49.293  7024  7024 E Zygote  : v2
07-01 08:58:49.293  7024  7024 I libpersona: KNOX_SDCARD not a persona
07-01 08:58:49.293  7024  7024 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
07-01 08:58:49.303  7024  7024 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,07-01 08:58:49.303  7024  7024 E SELinux : [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
,07-01 08:58:49.303  1017  1057 W art     : Suspending all threads took: 5.796ms
,07-01 08:58:49.323  1017  1498 I ActivityManager: Start proc com.sec.spp.push:RemoteNotiProcess for broadcast com.sec.spp.push/.notisvc.registration.PackageRemovedReceiver: pid=7024 uid=10032 gids={50032, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,07-01 08:58:49.323  1017  1498 I ActivityManager: Killing 6567:com.samsung.android.provider.shootingmodeprovider/u0a148 (adj 15): empty #21
,07-01 08:58:49.333  7024  7024 D TimaKeyStoreProvider: TimaSignature is unavailable
,07-01 08:58:49.333  7024  7024 D ActivityThread: Added TimaKeyStore provider
,07-01 08:58:49.353  1017  1041 W ResourceType: Failure getting entry for 0x7f07007b (t=6 e=123) (error -75)
,07-01 08:58:49.353  6945  6945 D elm:15121: ElmAgentService : onDestroy().
,07-01 08:58:49.353  1017  1319 D ActivityManager: startService callerProcessName:com.google.android.googlequicksearchbox, calleePkgName: com.google.android.googlequicksearchbox
07-01 08:58:49.353  1017  1319 D ActivityManager: retrieveServiceLocked(): component = com.google.android.googlequicksearchbox/com.google.android.search.core.icingsync.UpdateIcingCorporaService; callingUser = 0; userId(target) = 0
,07-01 08:58:49.353  1017  1319 W ActivityManager: userId = 0, bbcId = -10000
,07-01 08:58:49.353  1017  1319 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
07-01 08:58:49.353  1017  1319 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.googlequicksearchbox, destAppInfo.processName = com.google.android.googlequicksearchbox
,07-01 08:58:49.363  1017  1057 I art     : Explicit concurrent mark sweep GC freed 12980(826KB) AllocSpace objects, 2(32KB) LOS objects, 33% free, 23MB/34MB, paused 23.836ms total 336.026ms
,07-01 08:58:49.363  1017  1552 I ActivityManager: Killing 6587:com.samsung.android.bbc.bbcagent/1000 (adj 15): empty #21
,07-01 08:58:49.383  1017  1041 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,07-01 08:58:49.393  1017  1552 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.intelligenceservice, hostingType: broadcast
,07-01 08:58:49.393  1017  1552 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-01 08:58:49.393  1017  1552 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-01 08:58:49.393  1017  1552 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-01 08:58:49.393  1017  1552 E ActivityManager: checkUser: useridlist=null, currentuser=0
,07-01 08:58:49.403  1017  1057 D PackageManager: delete codoeFile: 
,07-01 08:58:49.403  7041  7041 E Zygote  : MountEmulatedStorage()
07-01 08:58:49.403  7041  7041 E Zygote  : v2
07-01 08:58:49.403  7041  7041 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,07-01 08:58:49.403  7041  7041 I libpersona: KNOX_SDCARD checking this for 10055
07-01 08:58:49.403  7041  7041 I libpersona: KNOX_SDCARD not a persona
,07-01 08:58:49.413  7041  7041 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,07-01 08:58:49.413  7041  7041 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,07-01 08:58:49.413  7024  7044 E SPPClientService: ============PushLog. commonIsShipBuild. stop!
07-01 08:58:49.413  1017  1552 I ActivityManager: Start proc com.samsung.android.intelligenceservice for broadcast com.samsung.android.intelligenceservice/.useranalysis.UserAnalysisBroadcastReceiver: pid=7041 uid=10055 gids={50055, 9997, 3001, 3002} abi=armeabi-v7a
,07-01 08:58:49.413  1017  1041 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1},
,07-01 08:58:49.413  7024  7044 E SPPClientService: [PushClientApplication] Push log off : This is Ship build version
,07-01 08:58:49.413  1017  1057 I AASA_removePackage: UID=10151 Target=com.test.thalitest
07-01 08:58:49.413  1017  1057 D AASAuninstall: userId = 0, info.removedAppID = 10151, info.uid = 10151, packageName = com.test.thalitest
07-01 08:58:49.413  1017  4381 D ActivityManager: startProcessLocked calleePkgName: com.android.keychain, hostingType: broadcast
,07-01 08:58:49.423  1017  1057 D PackageManager: result of delete: 1{1015607602}
07-01 08:58:49.423  1017  4381 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-01 08:58:49.423  1017  4381 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-01 08:58:49.423  1017  4381 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-01 08:58:49.423  1017  4381 E ActivityManager: checkUser: useridlist=null, currentuser=0
,07-01 08:58:49.433  1017  1041 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,07-01 08:58:49.433  6848  6848 D AndroidRuntime: Shutting down VM
,07-01 08:58:49.433  7051  7051 E Zygote  : MountEmulatedStorage()
,07-01 08:58:49.433  7051  7051 E Zygote  : v2
07-01 08:58:49.433  7051  7051 I libpersona: KNOX_SDCARD checking this for 1000
07-01 08:58:49.433  7051  7051 I libpersona: KNOX_SDCARD not a persona
,07-01 08:58:49.433  7051  7051 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51,
,07-01 08:58:49.443  7051  7051 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051,
07-01 08:58:49.443  1017  4381 I ActivityManager: Start proc com.android.keychain for broadcast com.android.keychain/.KeyChainBroadcastReceiver: pid=7051 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
07-01 08:58:49.443  7051  7051 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
07-01 08:58:49.443  1017  4381 I ActivityManager: Killing 6607:com.sec.android.widgetapp.tapandpay/u0a152 (adj 15): empty #21
07-01 08:58:49.443  7024  7044 D SPPClientService: PushLog.txt file is not deleted.,
07-01 08:58:49.443  1017  1017 D BackupManagerService: Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
07-01 08:58:49.443  7024  7044 D SPPClientService: PushLog.txt file is not deleted.
07-01 08:58:49.443  7024  7044 D SPPClientService: ============PushLog. stop!
07-01 08:58:49.453  6975  7040 I UpdateIcingCorporaServi: Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
,07-01 08:58:49.453  1017  1017 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
07-01 08:58:49.453  1017  1017 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - start - android.intent.action.PACKAGE_REMOVED
07-01 08:58:49.453  1017  1017 V EnterpriseBillingPolicy: uID is 10151
07-01 08:58:49.453  1017  1017 V EnterpriseBillingPolicy: Removed Packageuid is0
07-01 08:58:49.453  1017  1017 V EnterpriseBillingPolicyStorage: getProfileForApplication - enter
,07-01 08:58:49.453  1017  1017 V EnterpriseBillingPolicyStorage: getProfileForApplication - exit null : containerId = 0
07-01 08:58:49.453  1017  1017 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - personal application - profile null
07-01 08:58:49.453  1017  1017 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - might be a vpn vendor package 
07-01 08:58:49.453  1017  1017 V EnterpriseBillingPolicyStorage: getBillingProfileForVpnEngine - start - com.test.thalitest
,07-01 08:58:49.453  1017  1017 V EnterpriseBillingPolicyStorage: getBillingProfileForVpnEngine - end - null
,07-01 08:58:49.463  1017  4380 D ActivityManager: startProcessLocked calleePkgName: com.osp.app.signin, hostingType: broadcast
,07-01 08:58:49.463  1017  4380 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-01 08:58:49.463  1017  4380 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-01 08:58:49.463  1017  4380 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-01 08:58:49.463  1017  4380 E ActivityManager: checkUser: useridlist=null, currentuser=0
,07-01 08:58:49.463  1017  1057 D PackageManager: [MSG] START_CLEANING_PACKAGE packageName{com.test.thalitest}
07-01 08:58:49.463  1017  1057 D PackageManager: userId{-1}
07-01 08:58:49.463  1017  1057 D PackageManager: andCode{true}
,07-01 08:58:49.473  7051  7051 D TimaKeyStoreProvider: TimaSignature is unavailable
,07-01 08:58:49.473  7051  7051 D ActivityThread: Added TimaKeyStore provider
,07-01 08:58:49.473  7041  7041 D TimaKeyStoreProvider: TimaSignature is unavailable
,07-01 08:58:49.473  7041  7041 D ActivityThread: Added TimaKeyStore provider
,07-01 08:58:49.473  1017  1041 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
07-01 08:58:49.473  1017  1041 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
07-01 08:58:49.473  1017  1041 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,07-01 08:58:49.483  7074  7074 E Zygote  : MountEmulatedStorage()
07-01 08:58:49.483  7074  7074 E Zygote  : v2
07-01 08:58:49.483  7074  7074 I libpersona: KNOX_SDCARD checking this for 10036
07-01 08:58:49.483  1017  1041 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
07-01 08:58:49.483  7074  7074 I libpersona: KNOX_SDCARD not a persona
,07-01 08:58:49.483  7074  7074 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,07-01 08:58:49.483  1017  4380 I ActivityManager: Start proc com.osp.app.signin for broadcast com.osp.app.signin/com.msc.sa.selfupdate.SelfUpgradeReceiver: pid=7074 uid=10036 gids={50036, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,07-01 08:58:49.483  7074  7074 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051,
07-01 08:58:49.483  1017  4380 I ActivityManager: Killing 6632:com.sec.android.provider.badge/u0a68 (adj 15): empty #21
,07-01 08:58:49.483  7074  7074 E SELinux : [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
,07-01 08:58:49.483  1017  1057 D ActivityManager: retrieveServiceLocked(): component = com.android.defcontainer/com.android.defcontainer.DefaultContainerService; callingUser = 0; userId(target) = 0
,07-01 08:58:49.493  1017  1041 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,07-01 08:58:49.503  1017  1041 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,07-01 08:58:49.513  1017  1041 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
07-01 08:58:49.513  1017  1041 W Resources: Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,07-01 08:58:49.513  1017  1017 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
,07-01 08:58:49.513  1017  1041 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,07-01 08:58:49.513  1017  1017 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - start - android.intent.action.PACKAGE_FULLY_REMOVED
07-01 08:58:49.513  1017  1017 V EnterpriseBillingPolicy: uID is 10151
07-01 08:58:49.513  1017  1017 V EnterpriseBillingPolicy: Removed Packageuid is0
07-01 08:58:49.513  1017  1017 V EnterpriseBillingPolicyStorage: getProfileForApplication - enter
07-01 08:58:49.513  1017  2851 D SSRM:bc : MSG_TYPE_APP_REMOVED::
,07-01 08:58:49.513  1017  1163 D TaskPersister: removeObsoleteFile: deleting file=81_task.xml
,07-01 08:58:49.523  1017  1017 V EnterpriseBillingPolicyStorage: getProfileForApplication - exit null : containerId = 0
07-01 08:58:49.523  1017  1017 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - personal application - profile null
07-01 08:58:49.523  1017  1017 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - might be a vpn vendor package 
07-01 08:58:49.523  1017  1017 V EnterpriseBillingPolicyStorage: getBillingProfileForVpnEngine - start - com.test.thalitest
,07-01 08:58:49.523  1017  1017 V EnterpriseBillingPolicyStorage: getBillingProfileForVpnEngine - end - null
,07-01 08:58:49.523  7074  7074 D TimaKeyStoreProvider: TimaSignature is unavailable
,07-01 08:58:49.523  7074  7074 D ActivityThread: Added TimaKeyStore provider
07-01 08:58:49.523  1017  1017 V AlarmManagerEXT: com.test.thalitest(10151) is removed.
,07-01 08:58:49.543  1017  1041 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,07-01 08:58:49.543  7041  7041 D UserAnalysis.PlaceProvider: PlaceProvider onCreate()
,07-01 08:58:49.563  1017  1041 W Resources: Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,07-01 08:58:49.563  7051  7051 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:3125 
,07-01 08:58:49.563  1017  4380 D ActivityManager: startService callerProcessName:com.android.keychain, calleePkgName: com.android.keychain
07-01 08:58:49.563  1017  4380 D ActivityManager: retrieveServiceLocked(): component = com.android.keychain/com.android.keychain.KeyChainService; callingUser = 0; userId(target) = 0
,07-01 08:58:49.563  1017  4380 W ActivityManager: userId = 0, bbcId = -10000
,07-01 08:58:49.563  1017  4380 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,07-01 08:58:49.563  1017  4380 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.keychain, destAppInfo.processName = com.android.keychain
,07-01 08:58:49.573  1017  1562 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.app.mirrorlink, hostingType: broadcast
,07-01 08:58:49.573  7041  7041 D UserAnalysis.SecureDbManager: Key for secure DB is newly created
,07-01 08:58:49.573  7041  7041 D UserAnalysis.SecurePlaceDbHelper: SecurePlaceDbHelper() 
07-01 08:58:49.573  1017  1562 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-01 08:58:49.573  7041  7041 D UserAnalysis: Create SecureDbHelper
,07-01 08:58:49.573  1017  1562 E ActivityManager: checkUser: useridlist=null, currentuser=0
,07-01 08:58:49.583  1017  1562 E ActivityManager: checkUser: useridlist=null, currentuser=0
,07-01 08:58:49.583  1017  1041 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
07-01 08:58:49.583  1017  1041 W Resources: Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,07-01 08:58:49.583  1017  1562 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-01 08:58:49.583  1017  1041 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,07-01 08:58:49.593  7091  7091 E Zygote  : MountEmulatedStorage()
07-01 08:58:49.593  7091  7091 I libpersona: KNOX_SDCARD checking this for 1000
07-01 08:58:49.593  7091  7091 E Zygote  : v2
07-01 08:58:49.593  7091  7091 I libpersona: KNOX_SDCARD not a persona
07-01 08:58:49.593  7091  7091 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
07-01 08:58:49.593  1017  1562 I ActivityManager: Start proc ACMS.Process for broadcast com.samsung.android.app.mirrorlink/com.samsung.android.mirrorlink.acms.receivers.AcmsPackageEventListener: pid=7091 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
07-01 08:58:49.593  7091  7091 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
07-01 08:58:49.603  7091  7091 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,07-01 08:58:49.603  7041  7041 D IntelligenceServiceApplication: onCreate()
,07-01 08:58:49.603  7041  7041 D UserAnalysis.UserAnalysisBroadcastReceiver: Intent(action: android.intent.action.PACKAGE_REMOVED) is received.
,07-01 08:58:49.613  7041  7041 D IntelligenceServiceApplication: no applications having user consent for prediction
,07-01 08:58:49.623  1017  4141 D ActivityManager: retrieveServiceLocked(): component = com.samsung.android.intelligenceservice/com.samsung.android.placedetection.main.service.ServiceManager; callingUser = 0; userId(target) = 0
,07-01 08:58:49.623  1017  1041 D UsbSettingsManager: clearDefaults: com.test.thalitest
07-01 08:58:49.623  1017  1041 I CrashAnrDetector: onPackageRemoved : com.test.thalitest
,07-01 08:58:49.623  7091  7091 D TimaKeyStoreProvider: TimaSignature is unavailable
07-01 08:58:49.623  1711  1711 E NetworkScheduler.SchedulerReceiver: Invalid parameter app
07-01 08:58:49.623  1711  1711 E NetworkScheduler.SchedulerReceiver: Invalid package name : Perhaps you didn't include a PendingIntent in the extras?
,07-01 08:58:49.623  7091  7091 D ActivityThread: Added TimaKeyStore provider
,07-01 08:58:49.623  7074  7074 I SA      : [SSP] onCreated
,07-01 08:58:49.623  7041  7041 V PlaceDetection v1.0.19 : [PlaceDetection::stopService] Service stopped.
,07-01 08:58:49.633  1017  4380 D ActivityManager: getContentProviderImpl callerProcessName:com.google.android.googlequicksearchbox, calleePkgName: com.google.android.partnersetup
,07-01 08:58:49.643  1017  4380 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-01 08:58:49.643  6848  6848 W art     : ConditionVariable::~ConditionVariable for GC request condition variable called with 1 waiters.
07-01 08:58:49.643  1017  4380 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-01 08:58:49.643  1017  4380 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-01 08:58:49.643  1017  4380 E ActivityManager: checkUser: useridlist=null, currentuser=0
,07-01 08:58:49.643  7041  7041 V PlaceDetection v1.0.19 : [PlaceDetectionManager::removeDetectionListener] PlaceDetectionListener removed.
,07-01 08:58:49.653  1017  1562 D LocationManagerService: getProviders()=[passive, gps]
,07-01 08:58:49.663  7114  7114 E Zygote  : MountEmulatedStorage()
,07-01 08:58:49.663  7114  7114 E Zygote  : v2
07-01 08:58:49.663  7114  7114 I libpersona: KNOX_SDCARD checking this for 10014
07-01 08:58:49.663  7114  7114 I libpersona: KNOX_SDCARD not a persona
07-01 08:58:49.663  7114  7114 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,07-01 08:58:49.663  1017  4380 I ActivityManager: Start proc com.google.android.partnersetup for content provider com.google.android.partnersetup/.RlzAppProvider: pid=7114 uid=10014 gids={50014, 9997, 3003} abi=armeabi-v7a
07-01 08:58:49.663  7114  7114 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,07-01 08:58:49.663  7114  7114 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL,
,07-01 08:58:49.673  6152  7104 E SQLiteLog: (284) automatic index on crash_info_summary(package_name_touched)
,07-01 08:58:49.673  6152  6152 I art     : Explicit concurrent mark sweep GC freed 1076(50KB) AllocSpace objects, 0(0B) LOS objects, 32% free, 4MB/6MB, paused 1.093ms total 31.123ms
,07-01 08:58:49.683  1017  1561 I ActivityManager: Killing 6625:com.sec.android.app.myfiles/u0a42 (adj 15): empty #21
,07-01 08:58:49.693  7074  7074 I SA      : [TPM] There is no property file
,07-01 08:58:49.693  1017  1318 D ActivityManager: startService callerProcessName:com.google.android.gsf, calleePkgName: com.google.android.gms
07-01 08:58:49.693  1017  1318 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.app.service.PackageBroadcastService; callingUser = 0; userId(target) = 0
07-01 08:58:49.693  7041  7041 V PlaceDetection v1.0.19 : [PlaceDetection::setDisableDetection] PlaceType PLACE_OTHER disabled.
07-01 08:58:49.693  7041  7041 V PlaceDetection v1.0.19 : [PlaceDetectionManager::setChangeDetector] PlaceType PLACE_OTHER set as false.
,07-01 08:58:49.693  7041  7041 V PlaceDetection v1.0.19 : [PlaceDetectionManager::setSharedData] PreferenceValue PLACE_OTHER_ACTIVITY set as false
07-01 08:58:49.693  7041  7041 V PlaceDetection v1.0.19 : [PlaceDetectionManager::setSharedData] PreferenceValue COLLECTION_GPS set as false
,07-01 08:58:49.693  7041  7041 V PlaceDetection v1.0.19 : [PlaceDetectionManager::setSharedData] PreferenceValue COLLECTION_WIFI set as false
,07-01 08:58:49.703  7041  7041 V PlaceDetection v1.0.19 : [PlaceDetectionManager::setSharedData] PreferenceValue COLLECTION_NETWORK set as false
,07-01 08:58:49.703  7041  7041 V PlaceDetection v1.0.19 : [PlaceDetectionManager::setSharedData] PreferenceValue COLLECTION_SENSOR set as false
07-01 08:58:49.703  7041  7041 V PlaceDetection v1.0.19 : [PlaceDetection::setDisableDetection] PlaceType PLACE_HOME disabled.
,07-01 08:58:49.703  7041  7041 V PlaceDetection v1.0.19 : [PlaceDetectionManager::setChangeDetector] PlaceType PLACE_HOME set as false.
,07-01 08:58:49.703  7041  7041 V PlaceDetection v1.0.19 : [PlaceDetectionManager::setSharedData] PreferenceValue PLACE_HOME set as false
07-01 08:58:49.703  7041  7041 V PlaceDetection v1.0.19 : [PlaceDetectionManager::setSharedData] PreferenceValue COLLECTION_GPS set as false
,07-01 08:58:49.703  7041  7041 V PlaceDetection v1.0.19 : [PlaceDetectionManager::setSharedData] PreferenceValue COLLECTION_WIFI set as false
07-01 08:58:49.703  7074  7074 I SA      : [SCU] isHaveSA() - false
07-01 08:58:49.703  7041  7041 V PlaceDetection v1.0.19 : [PlaceDetectionManager::setSharedData] PreferenceValue COLLECTION_NETWORK set as false
,07-01 08:58:49.703  7041  7041 V PlaceDetection v1.0.19 : [PlaceDetectionManager::setSharedData] PreferenceValue COLLECTION_SENSOR set as false
,07-01 08:58:49.703  7041  7041 V PlaceDetection v1.0.19 : [PlaceDetection::setDisableDetection] PlaceType PLACE_WORK disabled.
07-01 08:58:49.703  7041  7041 V PlaceDetection v1.0.19 : [PlaceDetectionManager::setChangeDetector] PlaceType PLACE_WORK set as false.
,07-01 08:58:49.703  7041  7041 V PlaceDetection v1.0.19 : [PlaceDetectionManager::setSharedData] PreferenceValue PLACE_WORK set as false
07-01 08:58:49.703  7041  7041 V PlaceDetection v1.0.19 : [PlaceDetectionManager::setSharedData] PreferenceValue COLLECTION_GPS set as false
,07-01 08:58:49.703  7041  7041 V PlaceDetection v1.0.19 : [PlaceDetectionManager::setSharedData] PreferenceValue COLLECTION_WIFI set as false
,07-01 08:58:49.703  7041  7041 V PlaceDetection v1.0.19 : [PlaceDetectionManager::setSharedData] PreferenceValue COLLECTION_NETWORK set as false
07-01 08:58:49.703  7041  7041 V PlaceDetection v1.0.19 : [PlaceDetectionManager::setSharedData] PreferenceValue COLLECTION_SENSOR set as false
,07-01 08:58:49.703  7041  7041 V PlaceDetection v1.0.19 : [PlaceDetection::setDisableDetection] PlaceType MYCAR disabled.
07-01 08:58:49.703  7041  7041 V PlaceDetection v1.0.19 : [PlaceDetectionManager::setChangeDetector] PlaceType MYCAR set as false.
,07-01 08:58:49.703  7041  7041 V PlaceDetection v1.0.19 : [PlaceDetectionManager::setSharedData] PreferenceValue PLACE_CAR set as false
,07-01 08:58:49.713  1017  1318 W ActivityManager: userId = 0, bbcId = -10000
,07-01 08:58:49.713  1017  1318 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
07-01 08:58:49.713  1017  1318 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,07-01 08:58:49.713  7074  7074 I SA      : [TPM] getModelProperty : null
07-01 08:58:49.713  7074  7074 I SA      : [TPM] getCSCProperty : null
,07-01 08:58:49.723  7074  7074 I SA      : [DM] FLOATING AMOLED FEATURE: true
07-01 08:58:49.723  7074  7074 I SA      : [DM] PRODUCT AMOLED FEATURE: false
07-01 08:58:49.723  7074  7074 I SA      : [DM] TFT FEATURE: false
,07-01 08:58:49.723  7074  7074 I SA      : [DM] init START
07-01 08:58:49.723  7114  7114 D TimaKeyStoreProvider: TimaSignature is unavailable
,07-01 08:58:49.723  7114  7114 D ActivityThread: Added TimaKeyStore provider
,07-01 08:58:49.743  3400  3400 D ChimeraRcvrProxy: Creating receiver proxy ComponentInfo{com.google.android.gms/com.google.android.gms.games.chimera.GamesSystemBroadcastReceiverProxy}
07-01 08:58:49.743  3400  3400 D ChimeraRcvrProxy: Proxying container receiver ComponentInfo{com.google.android.gms/com.google.android.gms.games.chimera.GamesSystemBroadcastReceiverProxy} to Chimera receiver impl com.google.android.gms.games.receiver.PlaySystemBroadcastReceiver
07-01 08:58:49.743  3400  7132 D PackageBroadcastService: Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
07-01 08:58:49.743  3400  3400 D ChimeraCfgMgr: Loading module com.google.android.gms.games from APK com.google.android.play.games
07-01 08:58:49.743  3400  3400 D ChimeraModuleLdr: Module APK com.google.android.play.games already loaded
07-01 08:58:49.743  7041  7041 D BluetoothAdapter: cancelDiscovery
07-01 08:58:49.743  1017  1552 D ActivityManager: getContentProviderImpl callerProcessName:com.samsung.android.sm, calleePkgName: com.sec.android.provider.badge
,07-01 08:58:49.743  7074  7074 I SA      : [DM] This device is not a Vodafone
,07-01 08:58:49.743  1017  1552 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-01 08:58:49.743  3400  7132 D AccountUtils: Clearing selected account for com.test.thalitest
07-01 08:58:49.743  1017  1552 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-01 08:58:49.743  1017  1552 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-01 08:58:49.743  1017  1552 E ActivityManager: checkUser: useridlist=null, currentuser=0
,07-01 08:58:49.753  6975  7040 E SQLiteLog: (28) failed to open "/data/data/com.google.android.googlequicksearchbox/databases/icingcorpora.db" with flag (131138) and mode_t (0) due to error (30)
,07-01 08:58:49.763  7134  7134 E Zygote  : MountEmulatedStorage()
07-01 08:58:49.763  7134  7134 I libpersona: KNOX_SDCARD checking this for 10068
07-01 08:58:49.763  7134  7134 E Zygote  : v2
07-01 08:58:49.763  7134  7134 I libpersona: KNOX_SDCARD not a persona
,07-01 08:58:49.763  6975  7040 E SQLiteDatabase: Failed to open database '/data/data/com.google.android.googlequicksearchbox/databases/icingcorpora.db'.
,07-01 08:58:49.763  6975  7040 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
07-01 08:58:49.763  6975  7040 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
07-01 08:58:49.763  6975  7040 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
07-01 08:58:49.763  6975  7040 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
07-01 08:58:49.763  6975  7040 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
07-01 08:58:49.763  6975  7040 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
07-01 08:58:49.763  6975  7040 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
07-01 08:58:49.763  6975  7040 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
07-01 08:58:49.763  6975  7040 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
07-01 08:58:49.763  6975  7040 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
07-01 08:58:49.763  6975  7040 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1519)
07-01 08:58:49.763  6975  7040 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
07-01 08:58:49.763  6975  7040 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
07-01 08:58:49.763  6975  7040 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
07-01 08:58:49.763  6975  7040 E SQLiteDatabase: 	at com.google.android.search.core.icingsync.w.getWritableDatabase(InternalIcingCorporaProvider.java:561)
07-01 08:58:49.763  6975  7040 E SQLiteDatabase: 	at com.google.android.search.core.icingsync.InternalIcingCorporaProvider.update(InternalIcingCorporaProvider.java:276)
07-01 08:58:49.763  6975  7040 E SQLiteDatabase: 	at android.content.ContentProvider$Transport.update(ContentProvider.java:340)
07-01 08:58:49.763  6975  7040 E SQLiteDatabase: 	at android.content.ContentResolver.update(ContentResolver.java:1386)
07-01 08:58:49.763  6975  7040 E SQLiteDatabase: 	at com.google.android.search.core.icingsync.z.amO(UpdateIcingCorporaService.java:358)
07-01 08:58:49.763  6975  7040 E SQLiteDatabase: 	at com.google.android.search.core.icingsync.ab.amQ(UpdateIcingCorporaService.java:297)
07-01 08:58:49.763  6975  7040 E SQLiteDatabase: 	at com.google.android.search.core.icingsync.UpdateIcingCorporaService.a(UpdateIcingCorporaService.java:270)
07-01 08:58:49.763  6975  7040 E SQLiteDatabase: 	at com.google.android.search.core.icingsync.UpdateIcingCorporaService.aF(UpdateIcingCorporaService.java:194)
07-01 08:58:49.763  6975  7040 E SQLiteDatabase: 	at com.google.android.search.core.icingsync.UpdateIcingCorporaService.onHandleIntent(UpdateIcingCorporaService.java:182)
07-01 08:58:49.763  6975  7040 E SQLiteDatabase: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
07-01 08:58:49.763  6975  7040 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-01 08:58:49.763  6975  7040 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:145)
07-01 08:58:49.763  6975  7040 E SQLiteDatabase: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,07-01 08:58:49.763  1017  1552 I ActivityManager: Start proc com.sec.android.provider.badge for content provider com.sec.android.provider.badge/.BadgeProvider: pid=7134 uid=10068 gids={50068, 9997} abi=armeabi-v7a
07-01 08:58:49.763  1017  1319 D ActivityManager: startService callerProcessName:com.google.android.googlequicksearchbox, calleePkgName: com.google.android.googlequicksearchbox
07-01 08:58:49.773  7134  7134 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
07-01 08:58:49.763  1017  1319 D ActivityManager: retrieveServiceLocked(): component = com.google.android.googlequicksearchbox/com.google.android.apps.gsa.d.b; callingUser = 0; userId(target) = 0
07-01 08:58:49.763  1017  1319 W ActivityManager: Unable to start service Intent { cmp=com.google.android.googlequicksearchbox/com.google.android.apps.gsa.d.b (has extras) } U=0: not found
,07-01 08:58:49.773  1017  4381 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,07-01 08:58:49.773  7134  7134 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051,
,07-01 08:58:49.773  1017  4381 W ActivityManager: userId = 0, bbcId = -10000
,07-01 08:58:49.773  1017  4381 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
07-01 08:58:49.773  1017  4381 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
07-01 08:58:49.773  7074  7074 W ResourceType: Failure getting entry for 0x7f060010 (t=5 e=16) (error -75)
07-01 08:58:49.773  7074  7074 W ResourceType: Failure getting entry for 0x7f060008 (t=5 e=8) (error -75)
07-01 08:58:49.773  7074  7074 W ResourceType: Failure getting entry for 0x7f060009 (t=5 e=9) (error -75)
07-01 08:58:49.773  7074  7074 W ResourceType: Failure getting entry for 0x7f06000c (t=5 e=12) (error -75)
,07-01 08:58:49.773  7074  7074 W ResourceType: Failure getting entry for 0x7f06000d (t=5 e=13) (error -75)
07-01 08:58:49.773  7074  7074 W ResourceType: Failure getting entry for 0x7f060002 (t=5 e=2) (error -75)
07-01 08:58:49.773  7074  7074 W ResourceType: Failure getting entry for 0x7f060014 (t=5 e=20) (error -75)
,07-01 08:58:49.773  2776  2898 D BluetoothAdapterProperties: mDiscovering is false
07-01 08:58:49.773  1017  1562 D ActivityManager: startProcessLocked calleePkgName: com.google.android.apps.plus, hostingType: broadcast
07-01 08:58:49.773  2776  2898 E BluetoothAdapterService: This is not a scanning status. cancelDiscovery() will be not called.
07-01 08:58:49.773  7134  7134 E SELinux : [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
07-01 08:58:49.783  7041  7041 D BluetoothAdapter: cancelDiscovery = true
,07-01 08:58:49.783  7041  7041 V PlaceDetection v1.0.19 : [BTManager::unregisterReceiver] Error : Failed to unregister bluetooth broadcast receiver.
07-01 08:58:49.783  3400  3400 D ChimeraSrvcProxy: Creating service proxy ComponentInfo{com.google.android.gms/com.google.android.gms.games.chimera.GamesAsyncServiceProxy}
07-01 08:58:49.783  1017  1562 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-01 08:58:49.783  3400  3400 D ChimeraSrvcProxy: Proxying container service ComponentInfo{com.google.android.gms/com.google.android.gms.games.chimera.GamesAsyncServiceProxy} to Chimera service impl com.google.android.gms.games.service.PlayGamesAsyncService
07-01 08:58:49.783  1017  1562 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-01 08:58:49.783  3400  3400 D ChimeraCfgMgr: Loading module com.google.android.gms.games from APK com.google.android.play.games
07-01 08:58:49.783  1017  1562 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-01 08:58:49.783  3400  3400 D ChimeraModuleLdr: Module APK com.google.android.play.games already loaded
07-01 08:58:49.783  1017  1562 E ActivityManager: checkUser: useridlist=null, currentuser=0
,07-01 08:58:49.783  7074  7074 W ResourceType: No package identifier when getting value for resource number 0x00000000
,07-01 08:58:49.783  7074  7074 W ResourceType: Failure getting entry for 0x7f060026 (t=5 e=38) (error -75)
07-01 08:58:49.793  7074  7074 W ResourceType: Failure getting entry for 0x7f060027 (t=5 e=39) (error -75)
07-01 08:58:49.793  7074  7074 W ResourceType: Failure getting entry for 0x7f060028 (t=5 e=40) (error -75)
07-01 08:58:49.793  7074  7074 W ResourceType: Failure getting entry for 0x7f060029 (t=5 e=41) (error -75)
07-01 08:58:49.793  7074  7074 W ResourceType: Failure getting entry for 0x7f06002a (t=5 e=42) (error -75)
07-01 08:58:49.793  7074  7074 W ResourceType: Failure getting entry for 0x7f06002b (t=5 e=43) (error -75)
07-01 08:58:49.793  7074  7074 W ResourceType: Failure getting entry for 0x7f06002c (t=5 e=44) (error -75)
07-01 08:58:49.793  7074  7074 W ResourceType: Failure getting entry for 0x7f06002d (t=5 e=45) (error -75)
07-01 08:58:49.793  7074  7074 W ResourceType: Failure getting entry for 0x7f06002e (t=5 e=46) (error -75)
07-01 08:58:49.793   315   315 I art     : Explicit concurrent mark sweep GC freed 8718(371KB) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 1.801ms total 29.889ms
07-01 08:58:49.793  7074  7074 W ResourceType: Failure getting entry for 0x7f06001d (t=5 e=29) (error -75)
07-01 08:58:49.793  7074  7074 W ResourceType: Failure getting entry for 0x7f06001e (t=5 e=30) (error -75)
07-01 08:58:49.793  7074  7074 W ResourceType: Failure getting entry for 0x7f06001f (t=5 e=31) (error -75)
07-01 08:58:49.793  7074  7074 W ResourceType: Failure getting entry for 0x7f060011 (t=5 e=17) (error -75)
07-01 08:58:49.793  7074  7074 W ResourceType: Failure getting entry for 0x7f06000a (t=5 e=10) (error -75)
07-01 08:58:49.793  7074  7074 W ResourceType: Failure getting entry for 0x7f06000b (t=5 e=11) (error -75)
07-01 08:58:49.793  7074  7074 W ResourceType: Failure getting entry for 0x7f060003 (t=5 e=3) (error -75)
07-01 08:58:49.793  7074  7074 W ResourceType: Failure getting entry for 0x7f060015 (t=5 e=21) (error -75)
07-01 08:58:49.793  7074  7074 W ResourceType: Failure getting entry for 0x7f060016 (t=5 e=22) (error -75)
07-01 08:58:49.793  7134  7134 D TimaKeyStoreProvider: TimaSignature is unavailable
,07-01 08:58:49.803  7134  7134 D ActivityThread: Added TimaKeyStore provider
,07-01 08:58:49.803  7091  7141 D AcmsPackageEventListener: Received: android.intent.action.PACKAGE_REMOVED
07-01 08:58:49.803  6975  7040 E SharedPreferencesImpl: Couldn't create directory for SharedPreferences file /data/data/com.google.android.googlequicksearchbox/shared_prefs/uncaught_exception_handler_stats.xml
,07-01 08:58:49.803  6975  7040 E AndroidRuntime: FATAL EXCEPTION: IntentService[UpdateCorporaService]
07-01 08:58:49.803  6975  7040 E AndroidRuntime: Process: com.google.android.googlequicksearchbox:search, PID: 6975
07-01 08:58:49.803  6975  7040 E AndroidRuntime: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
07-01 08:58:49.803  6975  7040 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
07-01 08:58:49.803  6975  7040 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
07-01 08:58:49.803  6975  7040 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
07-01 08:58:49.803  6975  7040 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
07-01 08:58:49.803  6975  7040 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
07-01 08:58:49.803  6975  7040 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
07-01 08:58:49.803  6975  7040 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
07-01 08:58:49.803  6975  7040 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
07-01 08:58:49.803  6975  7040 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
07-01 08:58:49.803  6975  7040 E AndroidRuntime: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1519)
07-01 08:58:49.803  6975  7040 E AndroidRuntime: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
07-01 08:58:49.803  6975  7040 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
07-01 08:58:49.803  6975  7040 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
07-01 08:58:49.803  6975  7040 E AndroidRuntime: 	at com.google.android.search.core.icingsync.w.getWritableDatabase(InternalIcingCorporaProvider.java:561)
07-01 08:58:49.803  6975  7040 E AndroidRuntime: 	at com.google.android.search.core.icingsync.InternalIcingCorporaProvider.update(InternalIcingCorporaProvider.java:276)
07-01 08:58:49.803  6975  7040 E AndroidRuntime: 	at android.content.ContentProvider$Transport.update(ContentProvider.java:340)
07-01 08:58:49.803  6975  7040 E AndroidRuntime: 	at android.content.ContentResolver.update(ContentResolver.java:1386)
07-01 08:58:49.803  6975  7040 E AndroidRuntime: 	at com.google.android.search.core.icingsync.z.amO(UpdateIcingCorporaService.java:358)
07-01 08:58:49.803  6975  7040 E AndroidRuntime: 	at com.google.android.search.core.icingsync.ab.amQ(UpdateIcingCorporaService.java:297)
07-01 08:58:49.803  6975  7040 E AndroidRuntime: 	at com.google.android.search.core.icingsync.UpdateIcingCorporaService.a(UpdateIcingCorporaService.java:270)
07-01 08:58:49.803  6975  7040 E AndroidRuntime: 	at com.google.android.search.core.icingsync.UpdateIcingCorporaService.aF(UpdateIcingCorporaService.java:194)
07-01 08:58:49.803  6975  7040 E AndroidRuntime: 	at com.google.android.search.core.icingsync.UpdateIcingCorporaService.onHandleIntent(UpdateIcingCorporaService.java:182)
07-01 08:58:49.803  6975  7040 E AndroidRuntime: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
07-01 08:58:49.803  6975  7040 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-01 08:58:49.803  6975  7040 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:145)
07-01 08:58:49.803  6975  7040 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,07-01 08:58:49.803  7091  7141 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.samsung.android.mirrorlink.acms.receivers.AcmsPackageEventListener$asyncstart.doInBackground:54 com.samsung.android.mirrorlink.acms.receivers.AcmsPackageEventListener$asyncstart.doInBackground:1 
,07-01 08:58:49.803  7074  7074 I SA      : [SCU] isHaveSA() - false
07-01 08:58:49.803  7074  7074 I SA      : support phone number id : false
07-01 08:58:49.803  7074  7074 I SA      : [DM] Supports Ref Jpn : true
,07-01 08:58:49.803  7074  7074 I SA      : [DM] init END
07-01 08:58:49.803  7074  7074 I SA      : [SUR] onReceive log=[SA = 2.1.0173 V = 21 HWD = 960X540 1.5 dpi = 240  SIZE = 2 LOCALE = en_US CSC = XEO MCC = 0 MNC 0 T = user DEVICE = a3ulte P = a3ultexx I = LRX22G M = SM-A300FU OKLEFT false DIS LRX22G.A300FUXXU1BOJ5 PSS = 4.497050696380942  ]
,07-01 08:58:49.813  7074  7074 I SA      : [SUR] onReceive Intent=[ action_PACKAGE_REMOVED package extra.REMOVED_FOR_ALL_USERS.:true extra.UID.:10151 extra.DATA_REMOVED.:true extra.user_handle.:0 ],
,07-01 08:58:49.813   315   315 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 692us total 18.342ms
,07-01 08:58:49.833   315   315 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 564us total 16.205ms

```
