#### Test 8180285644342f8_thali04_samsung-SM-A300FU Logs


```
--------- beginning of main
08-19 17:54:48.046  1380  1380 I wpa_supplicant: nl80211: Received scan results (37 BSSes)
08-19 17:54:48.056  1380  1380 I wpa_supplicant: wlan0: Setting scan request: 32 sec 0 usec
08-19 17:54:48.056  1380  1380 I wpa_supplicant: CTRL-EVENT-SSID-REENABLED id=0 ssid="4E47373030"
08-19 17:54:48.056  1015  1534 D WifiMonitor: didn't find BSSID Trying to associate with SSID 'NG700'
08-19 17:54:48.056  1380  1380 I wpa_supplicant: Trying to associate with SSID '4E47373030'
08-19 17:54:48.056  1380  1380 I wpa_supplicant: Trying to associate with  'G700'
08-19 17:54:48.056  1380  1380 I wpa_supplicant: wlan0: State: SCANNING -> ASSOCIATING
08-19 17:54:48.056  1380  1380 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=5 BSSID=00.00.00 SSID=4E47373030
08-19 17:54:48.066  1015  1123 E WifiStateMachine: ConnectModeState SSID state=re-enabled nid=0 [id=0 ssid="NG700"]
08-19 17:54:48.076  1015  1123 E WifiConfigStore: SSID re-enabled for  "NG700"WPA_PSK had autoJoinStatus=0 self added false ephemeral false
08-19 17:54:48.086  1015  1123 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
08-19 17:54:48.086  1015  1123 D SecContentProvider2: mCursor = null
08-19 17:54:48.146   273   273 I rmt_storage: rmt_storage_connect_cb: clnt_h=0x5 conn_h=0xb840a7c8
08-19 17:54:48.146   273   273 I rmt_storage: rmt_storage_rw_iovec_cb: /boot/modem_fs2: clnt_h=0x2: req_h=0xa msg_id=3: R/W request received
08-19 17:54:48.146   273   273 I rmt_storage: wakelock acquired: 1, error no: 42
08-19 17:54:48.146   273   328 I rmt_storage: rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2 Unblock worker thread (th_id: -1203722104)
08-19 17:54:48.196   273   328 I rmt_storage: rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2: req_h=0xa msg_id=3: Bytes written = 917504
08-19 17:54:48.196   273   328 I rmt_storage: rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2: req_h=0xa msg_id=3: Send response: res=0 err=0
08-19 17:54:48.196   273   328 I rmt_storage: rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2 About to block rmt_storage client thread (th_id: -1203722104) wakelock released: 1, error no: 0
08-19 17:54:48.196   273   328 I rmt_storage: 
08-19 17:54:48.196   273   273 I rmt_storage: rmt_storage_disconnect_cb: clnt_h=0x5 conn_h=0xb840a7c8
,08-19 17:54:48.756  6209  6209 D AndroidRuntime: 
08-19 17:54:48.756  6209  6209 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
08-19 17:54:48.766  6209  6209 D AndroidRuntime: CheckJNI is OFF
08-19 17:54:48.766  6209  6209 D AndroidRuntime: readGMSProperty: start
08-19 17:54:48.766  6209  6209 D AndroidRuntime: readGMSProperty: already setted!!
08-19 17:54:48.766  6209  6209 D AndroidRuntime: propertySet: couldn't set property (it is from app)
08-19 17:54:48.766  6209  6209 D AndroidRuntime: readGMSProperty: could not set the property(default)!!
08-19 17:54:48.766  6209  6209 D AndroidRuntime: readGMSProperty: end
08-19 17:54:48.766  6209  6209 D AndroidRuntime: addProductProperty: start
--------- beginning of system
08-19 17:54:48.866  1015  1470 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
08-19 17:54:48.866  1015  1470 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4330, temperature: 280, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
08-19 17:54:48.866  1015  1470 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
08-19 17:54:48.866  1015  1470 D BatteryService: stay LED for fully charged
08-19 17:54:48.866  1015  1015 D BatteryService: Sending ACTION_BATTERY_CHANGED.
08-19 17:54:48.876  1172  1172 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
08-19 17:54:48.876  1015  1015 I MotionRecognitionService: Plugged
08-19 17:54:48.876  1172  1172 D KeyguardUpdateMonitor: handleBatteryUpdate
08-19 17:54:48.876  1015  1015 I MotionRecognitionService: mGripSensorEnabled= false
08-19 17:54:48.876  1405  1405 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
08-19 17:54:48.876  1405  1405 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
08-19 17:54:48.896  2704  2704 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
08-19 17:54:48.896  2704  2769 D HeadsetStateMachine: Disconnected process message: 10
08-19 17:54:48.906  1172  1172 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
08-19 17:54:48.906  1172  1172 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
08-19 17:54:48.906  1172  1172 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
08-19 17:54:48.926  6209  6209 E AffinityControl: AffinityControl: registerfunction enter
08-19 17:54:48.956  6209  6209 D AndroidRuntime: Calling main entry com.android.commands.am.Am
08-19 17:54:48.966  1015  3485 E PersonaManagerService: inState():  stateMachine is null !!
08-19 17:54:48.966  1015  3485 I PersonaManagerService: PersonaId don't exist
08-19 17:54:48.966  1015  3485 I ActivityManager: do not start freezing screen for locked container getKeyguardshowstate = false
08-19 17:54:48.976  1015  3485 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
08-19 17:54:48.986  1015  3485 W ActivityManager: mDVFSHelper.acquire()
08-19 17:54:48.986   258   258 I SurfaceFlinger: id=10 createSurf (16x16),-1 flag=20004, EimLayer(Di
08-19 17:54:48.986   258   258 I SurfaceFlinger: id=11 createSurf (16x16),-1 flag=20004, EimLayer(An
08-19 17:54:48.996  1015  3485 D FocusedStackFrame: Set to : 0
08-19 17:54:49.006  1015  1045 D PhoneWindow: *FMB* installDecor mIsFloating : false
08-19 17:54:49.006  1015  1045 D PhoneWindow: *FMB* installDecor flags : -2122120936
08-19 17:54:49.006  1015  3485 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-19 17:54:49.006  1015  3485 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-19 17:54:49.006  1015  3485 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-19 17:54:49.006  1015  3485 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-19 17:54:49.016  1015  1045 D PhoneWindow: *FMB* isFloatingMenuEnabled mFloatingMenuBtn : null
08-19 17:54:49.016  1015  1045 D PhoneWindow: *FMB* isFloatingMenuEnabled return false
08-19 17:54:49.016   258   258 I SurfaceFlinger: id=12 createSurf (540x960),1 flag=404, uhalitest
08-19 17:54:49.026  6220  6220 E Zygote  : MountEmulatedStorage()
08-19 17:54:49.026  6220  6220 E Zygote  : v2
08-19 17:54:49.026  6220  6220 I libpersona: KNOX_SDCARD checking this for 10171
08-19 17:54:49.026  6220  6220 I libpersona: KNOX_SDCARD not a persona
08-19 17:54:49.026  6220  6220 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
08-19 17:54:49.026  1015  3485 I ActivityManager: Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=6220 uid=10171 gids={50171, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
08-19 17:54:49.026  1015  3485 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.sec.android.app.launcher
08-19 17:54:49.026  1015  3485 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
08-19 17:54:49.026  1015  3485 D InputDispatcher: Focused application set to: xxxx
08-19 17:54:49.026  1015  3485 D InputDispatcher: Focus left window: 1476
08-19 17:54:49.026  6220  6220 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
08-19 17:54:49.026  6209  6209 D AndroidRuntime: Shutting down VM
08-19 17:54:49.036  6220  6220 E SELinux : [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
08-19 17:54:49.036  1015  1045 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
08-19 17:54:49.036  1015  1045 D PointerIcon: setMouseCustomIcon IconType is same.101
08-19 17:54:49.046  1015  2770 D SSRM:n  : SIOP:: AP = 320
08-19 17:54:49.066  6220  6220 D TimaKeyStoreProvider: TimaSignature is unavailable
08-19 17:54:49.066  6220  6220 D ActivityThread: Added TimaKeyStore provider
08-19 17:54:49.076  1015  1475 V WindowManager: rotationForOrientationLw(orient=-1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false
08-19 17:54:49.076  1015  1043 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
08-19 17:54:49.086  1015  1475 D PersonaManager: isKioskContainerExistOnDevice
08-19 17:54:49.096  1015  1015 D WindowOrientationListener:   mReceiver.onReceive :com.samsung.intent.action.AUTOROTATION,  delay = 66
08-19 17:54:49.116   258   436 I SurfaceFlinger: id=6 Removed Mauncher (5/9)
08-19 17:54:49.116   258  5339 I SurfaceFlinger: id=6 Removed Mauncher (-2/9)
08-19 17:54:49.126  1476  1476 D Launcher: onTrimMemory. Level: 20
08-19 17:54:49.126  1476  1476 V ActivityThread: updateVisibility : ActivityRecord{3e6ab48a token=android.os.BinderProxy@3fd4bd0d {com.sec.android.app.launcher/com.android.launcher2.Launcher}} show : false
08-19 17:54:49.146  1015  1042 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
08-19 17:54:49.146  1015  1042 D Tethering: interfaceLinkStateChanged wlan0, false
08-19 17:54:49.146  1015  1042 D Tethering: interfaceStatusChanged wlan0, false
08-19 17:54:49.156  1380  1380 I wpa_supplicant: CTRL-EVENT-ASSOC-REJECT bssid=F4.99.3E status_code=1
08-19 17:54:49.166  1380  1380 I wpa_supplicant: CTRL-EVENT-SSID-TEMP-DISABLED id=0 ssid="4E47373030" auth_failures=4 duration=60
08-19 17:54:49.166  1380  1380 I wpa_supplicant: wlan0: Setting scan request: 10 sec 0 usec
08-19 17:54:49.166  1380  1380 I wpa_supplicant: wlan0: State: ASSOCIATING -> DISCONNECTED
08-19 17:54:49.166  1015  1123 E WifiStateMachine: ConnectModeState SSID state=temp-disabled nid=0 [id=0 ssid="NG700" auth_failures=4 duration=60]
08-19 17:54:49.166  1015  1123 E WifiConfigStore: SSID temp disabled for  "NG700"WPA_PSK had autoJoinStatus=0 self added false ephemeral false
08-19 17:54:49.166  1015  1123 E WifiConfigStore:  message=id=0 ssid="NG700" auth_failures=4 duration=60
08-19 17:54:49.166  1380  1380 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=00.00.00 SSID=4E47373030
08-19 17:54:49.166  1015  1123 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
08-19 17:54:49.166  1015  1123 D SecContentProvider2: mCursor = null
08-19 17:54:49.196  6220  6220 I WebViewFactory: Loading com.google.android.webview version 45.0.2454.95 (code 246109500)
08-19 17:54:49.216  6220  6220 I cr.library_loader: Time to load native libraries: 2 ms (timestamps 6443-6445)
08-19 17:54:49.216  6220  6220 I cr.library_loader: Expected native library version number "", actual native library version number ""
08-19 17:54:49.236  6209  6209 W art     : ConditionVariable::~ConditionVariable for GC request condition variable called with 1 waiters.
,08-19 17:54:49.246  6220  6220 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {219f5e1e}
,08-19 17:54:49.246  6220  6220 I cr.library_loader: Expected native library version number "", actual native library version number ""
,08-19 17:54:49.246  6220  6220 I chromium: [INFO:library_loader_hooks.cc(121)] Chromium logging enabled: level = 0, default verbosity = 0
,08-19 17:54:49.286  6220  6220 I cr.BrowserStartup: Initializing chromium process, singleProcess=true
,08-19 17:54:49.286  6220  6220 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,08-19 17:54:49.296  6220  6220 E SysUtils: ApplicationContext is null in ApplicationStatus
,08-19 17:54:49.336  6220  6240 W chromium: [WARNING:dns_config_service_posix.cc(298)] Failed to read DnsConfig.
,08-19 17:54:49.336  6220  6220 I Adreno-EGL: <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: SKARAJGA_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018__release_ENGG (I856e09677e)
08-19 17:54:49.336  6220  6220 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.02
08-19 17:54:49.336  6220  6220 I Adreno-EGL: Build Date: 04/06/15 Mon
08-19 17:54:49.336  6220  6220 I Adreno-EGL: Local Branch: 
08-19 17:54:49.336  6220  6220 I Adreno-EGL: Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018
08-19 17:54:49.336  6220  6220 I Adreno-EGL: Local Patches: 112c106f3772623daa7b4181c6cf23491044ead1 Revert "Disable ASTC on A405"
08-19 17:54:49.336  6220  6220 I Adreno-EGL:                  58a118cb818fdc906095a49a90977c15f9d3b223 Remove ASTC
,08-19 17:54:49.416  6220  6220 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,08-19 17:54:49.426  6220  6220 I art     : Rejecting re-init on previously-failed class java.lang.Class<com.android.webview.chromium.FloatingSelectActionModeCallback>
,08-19 17:54:49.436  6220  6220 I art     : Rejecting re-init on previously-failed class java.lang.Class<com.android.webview.chromium.FloatingSelectActionModeCallback>
,08-19 17:54:49.436  6220  6220 I art     : Rejecting re-init on previously-failed class java.lang.Class<com.android.webview.chromium.WebViewContentsClientAdapter$WebResourceErrorImpl>
,08-19 17:54:49.436  6220  6220 I art     : Rejecting re-init on previously-failed class java.lang.Class<com.android.webview.chromium.WebViewContentsClientAdapter$WebResourceErrorImpl>
,08-19 17:54:49.566  6220  6220 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,08-19 17:54:49.576  6220  6220 W AwContents: onDetachedFromWindow called when already detached. Ignoring
,08-19 17:54:49.586  6220  6220 D PhoneWindow: *FMB* installDecor mIsFloating : false
,08-19 17:54:49.586  6220  6220 D PhoneWindow: *FMB* installDecor flags : -2139027200
,08-19 17:54:49.596  6220  6220 D SystemWebViewEngine: CordovaWebView is running on device made by: samsung
,08-19 17:54:49.596  1015  1040 W ActivityManager: Activity pause timeout for ActivityRecord{367e6aae u0 com.test.thalitest/.MainActivity t2}
,08-19 17:54:49.596  6220  6220 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,08-19 17:54:49.596  6220  6220 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,08-19 17:54:49.646  6220  6262 D OpenGLRenderer: Render dirty regions requested: true
,08-19 17:54:49.656  1015  3485 D ActivityManager: post active user change for 0 fullscreen true record.isFloatingActivity() false
,08-19 17:54:49.656  1015  3485 D KnoxTimeoutHandler: postActiveUserChange for user 0
08-19 17:54:49.656  1015  3485 I KnoxTimeoutHandler: postActiveUserChange, showWhenLocked: false
,08-19 17:54:49.656  1015  1015 D KnoxTimeoutHandler: handleActiveUserChange for user 0
08-19 17:54:49.656  1015  1015 D PersonaManagerService: getPersonasForUser(): returning null!
,08-19 17:54:49.656  6220  6249 W chromium: [WARNING:data_reduction_proxy_config.cc(630)] SPDY proxy OFF at startup,
,08-19 17:54:49.666  6220  6220 V ActivityThread: updateVisibility : ActivityRecord{3c38437e token=android.os.BinderProxy@253c3f83 {com.test.thalitest/com.test.thalitest.MainActivity}} show : true
,08-19 17:54:49.666  6220  6220 D PhoneWindow: *FMB* isFloatingMenuEnabled mFloatingMenuBtn : null
08-19 17:54:49.666  6220  6220 D PhoneWindow: *FMB* isFloatingMenuEnabled return false
,08-19 17:54:49.676   258   258 I SurfaceFlinger: id=13 createSurf (1x1),1 flag=404, NainActivit
,08-19 17:54:49.696  1015  3494 D InputDispatcher: Focus entered window: 6220
,08-19 17:54:49.696  1015  1045 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
,08-19 17:54:49.696  1015  1045 D PointerIcon: setMouseCustomIcon IconType is same.101
,08-19 17:54:49.706  6220  6220 D SRIB_DCS: log_dcs ThreadedRenderer::initialize entered! 
,08-19 17:54:49.706  6220  6262 I OpenGLRenderer: Initialized EGL, version 1.4
,08-19 17:54:49.706  6220  6262 D OpenGLRenderer: Get maximum texture size. GL_MAX_TEXTURE_SIZE is 4096
,08-19 17:54:49.706  6220  6262 D OpenGLRenderer: Enabling debug mode 0
,08-19 17:54:49.726   291   291 E SMD     : DCD OFF
,08-19 17:54:49.726  1015  1446 D InputMethodManagerService: windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,08-19 17:54:49.736  1015  6266 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.android.server.InputMethodManagerService$6.run:2762 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,08-19 17:54:49.736  1172  1172 I StatusBar: Icon Only
,08-19 17:54:49.736  1172  1172 D PanelView: There is/are notification(s) 
,08-19 17:54:49.746  6220  6220 W IInputConnectionWrapper: showStatusIcon on inactive InputConnection
,08-19 17:54:49.746  6220  6220 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@253c3f83 time:106977
,08-19 17:54:49.786  1015  1045 I ActivityManager: Displayed Component not be shown by security: +686ms (total +780ms)
,08-19 17:54:49.786  1015  1045 W ActivityManager: mDVFSHelper.release()
08-19 17:54:49.786  1015  1045 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{367e6aae u0 com.test.thalitest/.MainActivity t2} time:107012
,08-19 17:54:49.786  1823  1823 I SamsungIME: getCurrentCandidateView
,08-19 17:54:49.796   258   808 I SurfaceFlinger: id=12 Removed uhalitest (7/9)
,08-19 17:54:49.796   258   439 I SurfaceFlinger: id=12 Removed uhalitest (-2/9)
,08-19 17:54:49.876  6220  6220 W cr.BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 6220
,08-19 17:54:49.886  1823  1823 D SamsungIME: Dismiss ExpandCandiate
,08-19 17:54:50.036  1823  1823 I SamsungIME: getDebugLevel  : 0x4f4c
,08-19 17:54:50.066  6220  6220 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,08-19 17:54:50.076  1823  1823 I SamsungIME: getDebugLevel  : 0x4f4c
,08-19 17:54:50.096  1823  1823 I SamsungIME: KeybaordView init() : load resources
,08-19 17:54:50.116  1823  1823 I SamsungIME: getCurrentKeyboard
,08-19 17:54:50.116  1823  1823 I SamsungIME: getTextKeyboard
,08-19 17:54:50.136  1823  1823 D SamsungIME: [SwiftkeyWrapper] currentLangauge : 1701729619
,08-19 17:54:50.146  6220  6268 D jxcore_app_log: JniHelper::setJavaVM(0xb8dd82b0), pthread_self() = -1187617592
,08-19 17:54:50.156  6220  6268 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
08-19 17:54:50.156  6220  6268 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
08-19 17:54:50.156  6220  6268 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
08-19 17:54:50.156  6220  6268 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
08-19 17:54:50.156  6220  6268 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
08-19 17:54:50.156  6220  6268 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@786d9c4 added. We now have 1 listener(s)
,08-19 17:54:50.166  6220  6268 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: 08:EC:A9:50:76:27
,08-19 17:54:50.166  6220  6268 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "08:EC:A9:50:76:27"
,08-19 17:54:50.166  6220  6268 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-19 17:54:50.166  6220  6268 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-19 17:54:50.176  6220  6268 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
08-19 17:54:50.176  6220  6268 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
08-19 17:54:50.176  6220  6268 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
08-19 17:54:50.176  6220  6268 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: 08:EC:A9:50:76:27
08-19 17:54:50.176  6220  6268 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
08-19 17:54:50.176  6220  6268 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
08-19 17:54:50.176  6220  6268 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
08-19 17:54:50.176  6220  6268 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
08-19 17:54:50.176  6220  6268 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
08-19 17:54:50.176  6220  6268 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
08-19 17:54:50.176  6220  6268 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
08-19 17:54:50.176  6220  6268 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
08-19 17:54:50.176  6220  6268 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
08-19 17:54:50.176  6220  6268 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
08-19 17:54:50.176  6220  6268 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@15fc0f73 added. We now have 1 listener(s)
08-19 17:54:50.176  6220  6268 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-19 17:54:50.176  6220  6268 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-19 17:54:50.176  6220  6268 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
08-19 17:54:50.176  6220  6268 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
,08-19 17:54:50.176  6220  6268 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
08-19 17:54:50.176  6220  6268 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
,08-19 17:54:50.186  6220  6268 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-19 17:54:50.186  6220  6268 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 08:EC:A9:50:76:27
,08-19 17:54:50.186  6220  6268 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (SUPPORTED) in persistent storage
,08-19 17:54:50.186  6220  6268 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-19 17:54:50.186  6220  6268 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-19 17:54:50.186  6220  6268 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-19 17:54:50.186  6220  6268 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-19 17:54:50.186  6220  6268 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-19 17:54:50.186  6220  6268 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-19 17:54:50.186  6220  6268 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-19 17:54:50.186  6220  6268 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-19 17:54:50.186  6220  6268 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
08-19 17:54:50.186  6220  6268 D io.jxcore.node.ConnectivityMonitor: start: OK
08-19 17:54:50.196  6220  6268 I io.jxcore.node.LifeCycleMonitor: start: OK
08-19 17:54:50.196  6220  6220 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-19 17:54:50.226  6220  6220 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,08-19 17:54:50.746  1015  1303 E Watchdog: !@Sync 3
,08-19 17:54:50.796  6220  6275 W jxcore-log: Initializing JXcore engine
08-19 17:54:50.796  6220  6275 W jxcore-log: JXcore engine is ready
,08-19 17:54:50.856  1952  1952 E audit   : type=1400 msg=audit(1471622090.856:203): avc:  denied  { ioctl } for  pid=6275 comm="Thread-1125" path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=3080 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
08-19 17:54:50.856  1952  1952 E audit   :  SEPF_SM-A300FU_5.0.2-1_0051
08-19 17:54:50.856  1952  1952 E audit   : type=1300 msg=audit(1471622090.856:203): arch=40000028 syscall=54 per=800000 success=no exit=-13 a0=7 a1=5451 a2=3 a3=9f3fb8f8 items=0 ppid=308 ppcomm=main pid=6275 auid=4294967295 uid=10171 gid=10171 euid=10171 suid=10171 fsuid=10171 egid=10171 sgid=10171 fsgid=10171 ses=4294967295 tty=(none) comm="Thread-1125" exe="/system/bin/app_process32" subj=u:r:untrusted_app:s0 key=(null)
08-19 17:54:50.856  1952  1952 E audit   : type=1320 msg=audit(1471622090.856:203): 
,08-19 17:54:50.866  6220  6275 W jxcore-log: Starting JXcore engine,
,08-19 17:54:50.966  6220  6275 W jxcore-log: Platform android
08-19 17:54:50.966  6220  6275 W jxcore-log: 
08-19 17:54:50.966  6220  6275 W jxcore-log: Process ARCH arm
08-19 17:54:50.966  6220  6275 W jxcore-log: 
,08-19 17:54:51.176  6220  6275 I jxcore-log: JXcore Cordova bridge is ready!
08-19 17:54:51.176  6220  6275 I jxcore-log: 
,08-19 17:54:51.176  6220  6275 W jxcore-log: JXcore engine is started
,08-19 17:54:51.186  6220  6268 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,08-19 17:54:51.186  6220  6220 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,08-19 17:54:51.726   323   323 I Atfwd_Sendcmd: AtCmdFwd service not ready - Exhausted retry attempts - :6
08-19 17:54:51.726   323   323 I Atfwd_Daemon: result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,08-19 17:54:52.396  5208  5208 D FactoryTest: Not factory mode
,08-19 17:54:52.396  5208  5208 D FactoryTest: Not factory mode. isFactoryMode() returend false
,08-19 17:54:52.396  5208  5208 D MTPRx   : DRIVER_TIME_OUT 60s lapsed
,08-19 17:54:52.396  5208  5208 D MTPRx   : still no open session command from host, so toast
,08-19 17:54:52.396  5208  5208 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startActivity:1595 android.content.ContextWrapper.startActivity:337 android.content.ContextWrapper.startActivity:337 com.samsung.android.MtpApplication.MtpReceiver$3.handleMessage:708 android.os.Handler.dispatchMessage:102 
,08-19 17:54:52.396  5208  5208 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startActivity:1607 android.app.ContextImpl.startActivity:1596 android.content.ContextWrapper.startActivity:337 android.content.ContextWrapper.startActivity:337 com.samsung.android.MtpApplication.MtpReceiver$3.handleMessage:708 
,08-19 17:54:52.396  5208  5208 I Timeline: Timeline: Activity_launch_request id:com.android.settings time:109628
,08-19 17:54:52.396  1015  1133 E PersonaManagerService: inState():  stateMachine is null !!
,08-19 17:54:52.396  1015  1133 I PersonaManagerService: PersonaId don't exist
08-19 17:54:52.396  1015  1133 I ActivityManager: do not start freezing screen for locked container getKeyguardshowstate = false
,08-19 17:54:52.406  1015  1133 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.android.settings
,08-19 17:54:52.406  1015  1133 W ActivityManager: userId = 0, bbcId = -10000
,08-19 17:54:52.406  1015  1133 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-19 17:54:52.406  1015  1133 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.android.MtpApplication, destAppInfo.processName = com.android.settings
,08-19 17:54:52.416  1015  1133 W ActivityManager: mDVFSHelper.acquire()
,08-19 17:54:52.426  1015  1133 D PersonaManager: isKioskContainerExistOnDevice
,08-19 17:54:52.446  1015  1133 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
08-19 17:54:52.446  1015  1133 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.android.settings
,08-19 17:54:52.446  1015  1133 D InputDispatcher: Focused application set to: xxxx
08-19 17:54:52.446  1015  1133 D InputDispatcher: Focus left window: 6220
,08-19 17:54:52.446  5208  5208 E MTPRx   : started activity for popup
,08-19 17:54:52.446  1015  1045 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
,08-19 17:54:52.446  1015  1045 D PointerIcon: setMouseCustomIcon IconType is same.101
,08-19 17:54:52.486  5208  5208 W ResourcesManager: Asset path '/system/framework/sec_platform_library.jar' does not exist or contains no resources.
,08-19 17:54:52.486  5208  5208 W ResourcesManager: Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
,08-19 17:54:52.486  5208  5208 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
08-19 17:54:52.486  5208  5208 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-19 17:54:52.486  5208  5208 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,08-19 17:54:52.486  5208  5208 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,08-19 17:54:52.506  5208  5208 E SettingsReceiverActivity: PREF_DONT_ASK_AGAIN : true
,08-19 17:54:52.506  1015  1028 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.android.settings
,08-19 17:54:52.506  1015  1028 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
08-19 17:54:52.506  1015  1028 D InputDispatcher: Focused application set to: xxxx
08-19 17:54:52.506  1015  1028 D InputDispatcher: Focus entered window: 6220
,08-19 17:54:52.506  1015  1045 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
,08-19 17:54:52.516  1015  1045 D PointerIcon: setMouseCustomIcon IconType is same.101
,08-19 17:54:52.516  1015  1768 D InputMethodManagerService: windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,08-19 17:54:52.516  1015  1768 W InputMethodManagerService: Window already focused, ignoring focus gain of: com.android.internal.view.IInputMethodClient$Stub$Proxy@82f3b79 attribute=null, token = android.os.BinderProxy@3b97be09
,08-19 17:54:52.546  5208  5208 D SettingsReceiverActivity: dev.kiessupport is : TRUE
,08-19 17:54:52.556  5208  5208 D PhoneWindow: *FMB* installDecor mIsFloating : true
08-19 17:54:52.556  5208  5208 D PhoneWindow: *FMB* installDecor flags : 8388610
,08-19 17:54:52.576  6220  6220 D io.jxcore.node.LifeCycleMonitor: onActivityStarted
,08-19 17:54:52.576  6220  6220 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: STARTED
,08-19 17:54:52.576  6220  6220 D io.jxcore.node.LifeCycleMonitor: onActivityResumed
08-19 17:54:52.576  6220  6220 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: RESUMED
,08-19 17:54:52.576  1015  1338 D ActivityManager: post active user change for 0 fullscreen true record.isFloatingActivity() false
,08-19 17:54:52.576  1015  1338 D KnoxTimeoutHandler: postActiveUserChange for user 0
,08-19 17:54:52.576  1015  1338 I KnoxTimeoutHandler: postActiveUserChange, showWhenLocked: false
,08-19 17:54:52.576  1015  1015 D KnoxTimeoutHandler: handleActiveUserChange for user 0
08-19 17:54:52.576  1015  1015 D PersonaManagerService: getPersonasForUser(): returning null!
,08-19 17:54:52.596  6220  6220 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
,08-19 17:54:52.596  6220  6220 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: PAUSED
,08-19 17:54:52.596  6220  6220 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@15c30def Bundle[{plugin=Bundle[{}], android:viewHierarchyState=Bundle[{android:views={100=android.view.AbsSavedState$1@31c146f6, 16908290=android.view.AbsSavedState$1@31c146f6}, android:focusedViewId=100}]}]
,08-19 17:54:52.596  6220  6220 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: SAVE_INSTANCE_STATE
,08-19 17:54:52.596  6220  6220 V ActivityThread: updateVisibility : ActivityRecord{3c38437e token=android.os.BinderProxy@253c3f83 {com.test.thalitest/com.test.thalitest.MainActivity}} show : true
,08-19 17:54:52.596  6220  6220 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
,08-19 17:54:52.596  6220  6220 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: STOPPED
,08-19 17:54:52.606  6220  6220 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@253c3f83 time:109830
,08-19 17:54:52.616  1015  3492 D PersonaManager: isKioskContainerExistOnDevice
,08-19 17:54:52.726   291   291 E SMD     : DCD OFF
,08-19 17:54:55.416  1015  1040 W ActivityManager: mDVFSHelper.release(),
,08-19 17:54:55.736   291   291 E SMD     : DCD OFF,
,08-19 17:54:56.726   323   323 I ServiceManager: Waiting for service AtCmdFwd...,
,08-19 17:54:57.726   323   323 I ServiceManager: Waiting for service AtCmdFwd...,
,08-19 17:54:58.586  1015  2805 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> ,
,08-19 17:54:58.726   323   323 I ServiceManager: Waiting for service AtCmdFwd...,
,08-19 17:54:58.736   291   291 E SMD     : DCD OFF,
,08-19 17:54:58.926  1015  1338 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-19 17:54:58.926  1015  1338 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4323, temperature: 280, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
,08-19 17:54:58.926  1015  1338 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
08-19 17:54:58.926  1015  1338 D BatteryService: stay LED for fully charged
08-19 17:54:58.926  1015  1015 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,08-19 17:54:58.926  1015  1015 I MotionRecognitionService: Plugged
08-19 17:54:58.926  1015  1015 I MotionRecognitionService: mGripSensorEnabled= false
,08-19 17:54:58.936  1172  1172 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,08-19 17:54:58.936  1172  1172 D KeyguardUpdateMonitor: handleBatteryUpdate
08-19 17:54:58.936  1405  1405 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
08-19 17:54:58.936  1405  1405 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,08-19 17:54:58.946  2704  2704 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,08-19 17:54:58.946  2704  2769 D HeadsetStateMachine: Disconnected process message: 10
,08-19 17:54:58.966  1172  1172 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-19 17:54:58.966  1172  1172 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
08-19 17:54:58.966  1172  1172 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-19 17:54:59.006  1015  1093 V AlarmManager: waitForAlarm result :4,
,08-19 17:54:59.016  1015  1015 D ActivityManager: bindService callerProcessName:android, calleePkgName: android, action: null
,08-19 17:54:59.016  1015  1015 D ActivityManager: retrieveServiceLocked(): component = android/com.android.server.os.BackgroundCompactionService; callingUser = 0; userId(target) = 0
,08-19 17:54:59.016  1015  1015 I BackgroundCompactionService: onStart. jobID=801
,08-19 17:54:59.026  1015  1015 I BackgroundCompactionService: onStart done. jobID=801
,08-19 17:54:59.026  1015  6282 I BackgroundCompactionService: Execute BGCompaction (type1). (0 times)
,08-19 17:54:59.026  1015  6282 I BackgroundCompactionService: compact_memory command done
,08-19 17:54:59.056  1015  1055 D PackageManager: [MSG] WRITE_PACKAGE_RESTRICTIONS
,08-19 17:54:59.066  1015  2770 D SSRM:n  : SIOP:: AP = 340
,08-19 17:54:59.106  1015  1047 I PowerManagerService: [PWL] Off : 30s ago
,08-19 17:54:59.166  1380  1380 I wpa_supplicant: P2P: Current p2p state = IDLE,
08-19 17:54:59.166  1380  1380 I wpa_supplicant: wlan0: State: DISCONNECTED -> SCANNING
08-19 17:54:59.166  1380  1380 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00.00.00 SSID=
08-19 17:54:59.166  1380  1380 I wpa_supplicant: Scan requested (ret=0) - scan timeout 30 seconds
,08-19 17:54:59.176  1015  1123 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
08-19 17:54:59.176  1015  1123 D SecContentProvider2: mCursor = null
,08-19 17:54:59.726   323   323 I ServiceManager: Waiting for service AtCmdFwd...
,08-19 17:54:59.986  1015  1093 V AlarmManager: waitForAlarm result :8,
,08-19 17:55:00.436  1380  1380 I wpa_supplicant: nl80211: Received scan results (26 BSSes),
08-19 17:55:00.436  1380  1380 I wpa_supplicant: wlan0: Setting scan request: 8 sec 0 usec,
,08-19 17:55:00.446  1380  1380 I wpa_supplicant: wlan0: ANQP fetch completed,
,08-19 17:55:00.726   323   323 I ServiceManager: Waiting for service AtCmdFwd...
,08-19 17:55:01.726   323   323 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 1,
,08-19 17:55:01.736   291   291 E SMD     : DCD OFF,
,08-19 17:55:02.776  1015  1093 V AlarmManager: waitForAlarm result :4,
,08-19 17:55:02.786  1015  1093 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.drive.api.ApiService; callingUser = 0; userId(target) = 0
,08-19 17:55:02.796  1015  1015 V AlarmManager: ___SyncScheduler (v3) ACTIVATED___
08-19 17:55:02.796  1015  1015 V AlarmManagerEXT: <AppSync3 Whitelist>
08-19 17:55:02.796  1015  1015 V AlarmManagerEXT: (AppSync) ### 0 added ###
,08-19 17:55:02.796  1172  1172 D KeyguardUpdateMonitor: received broadcast android.intent.action.TIME_TICK
08-19 17:55:02.796  1172  1172 D KeyguardUpdateMonitor: handleTimeUpdate
,08-19 17:55:02.806  1172  1172 D SecKeyguardClockView: onTimeChanged() : mShouldShowDualClock - false, isDualClockSet() -false
,08-19 17:55:02.806  1172  1172 D SecKeyguardClockView: HomeTimezone(): 1
,08-19 17:55:02.826  1172  1172 D SecKeyguardStatusUtils: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,08-19 17:55:02.826  1172  1172 D KeyguardEffectViewController: onReceive action : android.intent.action.TIME_TICK
,08-19 17:55:02.826  1172  1172 I KeyguardEffectViewController: *** don't update sliding image ***
,08-19 17:55:02.856  1172  1172 D DateView: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,08-19 17:55:02.866  1172  1172 D DateView: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,08-19 17:55:02.866  1172  1172 D DateView: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,08-19 17:55:02.886  1172  1172 D SecKeyguardStatusUtils: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,08-19 17:55:02.936  4129  4129 D ConnectivityManager: CallingUid : 10011, CallingPid : 4129
08-19 17:55:02.936  1015  1028 D ConnectivityService: listenForNetwork for NetworkRequest [ id=3, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-19 17:55:02.936  1015  1125 D ConnectivityService: handleRegisterNetworkRequest checking NetworkAgentInfo [WIFI_P2P () - 501]
,08-19 17:55:02.986  4129  6287 W DriveInitializer: Background init thread started
,08-19 17:55:03.046   257   541 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.gms/files/
08-19 17:55:03.046   257   541 W Vold    : Returning OperationFailed - no handler for errno 0
,08-19 17:55:03.046  4129  6287 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.gms/files
,08-19 17:55:03.076  4129  6287 W DriveInitializer: Background init thread ended
,08-19 17:55:03.436  6220  6275 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
08-19 17:55:03.436  6220  6275 I jxcore-log: 
,08-19 17:55:03.436  6220  6275 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
08-19 17:55:03.436  6220  6275 I jxcore-log: 
,08-19 17:55:03.436  6220  6275 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-19 17:55:03.436  6220  6275 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-19 17:55:03.436  6220  6275 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-19 17:55:03.436  6220  6275 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-19 17:55:03.436  6220  6275 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-19 17:55:03.436  6220  6275 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-19 17:55:03.436  6220  6275 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-19 17:55:03.436  6220  6275 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-19 17:55:03.446  6220  6275 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-19 17:55:03.446  6220  6275 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
08-19 17:55:03.446  6220  6275 I jxcore-log: 
08-19 17:55:03.446  6220  6275 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
08-19 17:55:03.446  6220  6275 I jxcore-log: 
,08-19 17:55:04.086  6220  6275 D ExecuteNativeTests: Running unit tests,
,08-19 17:55:04.176  6220  6275 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-19 17:55:04.176  6220  6275 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@6f5efe7 added. We now have 2 listener(s)
,08-19 17:55:04.176  6220  6275 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "08:EC:A9:50:76:27"
,08-19 17:55:04.176  6220  6275 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-19 17:55:04.176  6220  6275 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,08-19 17:55:04.176  6220  6275 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-19 17:55:04.176  6220  6275 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1979b794 added. We now have 2 listener(s)
,08-19 17:55:04.176  6220  6275 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-19 17:55:04.176  6220  6275 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-19 17:55:04.186  6220  6275 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-19 17:55:04.186  6220  6275 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-19 17:55:04.186  6220  6275 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-19 17:55:04.186  6220  6275 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-19 17:55:04.186  6220  6275 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-19 17:55:04.186  6220  6275 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-19 17:55:04.186  6220  6275 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-19 17:55:04.186  6220  6275 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-19 17:55:04.186  6220  6275 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-19 17:55:04.186  6220  6275 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-19 17:55:04.186  6220  6275 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-19 17:55:04.186  6220  6220 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-19 17:55:04.196  6220  6275 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
,08-19 17:55:04.196  6220  6275 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-19 17:55:04.196  6220  6275 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,08-19 17:55:04.196  6220  6275 E io.jxcore.node.ConnectionHelper: onConnectionTimeout: Connection attempt with peer [<no peer name> 00:11:22:33:44:55] timed out
,08-19 17:55:04.196  6220  6275 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
08-19 17:55:04.196  6220  6275 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
08-19 17:55:04.196  6220  6275 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-19 17:55:04.196  6220  6275 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
,08-19 17:55:04.196  6220  6275 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-19 17:55:04.196  6220  6275 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-19 17:55:04.196  6220  6275 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-19 17:55:04.196  6220  6275 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-19 17:55:04.196  6220  6275 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-19 17:55:04.196  6220  6275 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left,
08-19 17:55:04.196  6220  6275 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-19 17:55:04.196  6220  6275 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@6f5efe7 removed from the list
08-19 17:55:04.196  6220  6275 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-19 17:55:04.196  6220  6275 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1979b794 removed from the list
08-19 17:55:04.196  6220  6275 D io.jxcore.node.ConnectivityMonitor: stop
08-19 17:55:04.196  6220  6275 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-19 17:55:04.196  6220  6275 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-19 17:55:04.196  6220  6275 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-19 17:55:04.196  6220  6275 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-19 17:55:04.196  6220  6275 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-19 17:55:04.196  6220  6275 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-19 17:55:04.196  6220  6275 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1979b794 not in the list
08-19 17:55:04.206  6220  6275 D io.jxcore.node.ConnectionHelper: onBluetoothMacAddressResolved: 00:11:22:33:44:55 - Bro Mode is not supported
,08-19 17:55:04.206  6220  6275 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-19 17:55:04.206  6220  6275 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-19 17:55:04.206  6220  6275 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-19 17:55:04.206  6220  6275 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-19 17:55:04.206  6220  6275 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-19 17:55:04.206  6220  6275 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-19 17:55:04.206  6220  6275 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@6f5efe7 not in the list
08-19 17:55:04.206  6220  6275 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-19 17:55:04.206  6220  6275 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1979b794 not in the list
08-19 17:55:04.206  6220  6275 D io.jxcore.node.ConnectivityMonitor: stop
08-19 17:55:04.206  6220  6275 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-19 17:55:04.206  6220  6275 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-19 17:55:04.206  6220  6275 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-19 17:55:04.206  6220  6275 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-19 17:55:04.206  6220  6275 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-19 17:55:04.206  6220  6275 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-19 17:55:04.206  6220  6275 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-19 17:55:04.206  6220  6275 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1979b794 not in the list
,08-19 17:55:04.206  6220  6275 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
08-19 17:55:04.206  6220  6275 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
08-19 17:55:04.206  6220  6275 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
08-19 17:55:04.206  6220  6275 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
08-19 17:55:04.206  6220  6275 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
08-19 17:55:04.206  6220  6275 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
,08-19 17:55:04.206  6220  6275 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
08-19 17:55:04.206  6220  6275 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
08-19 17:55:04.206  6220  6275 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
08-19 17:55:04.206  6220  6275 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
08-19 17:55:04.206  6220  6275 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
08-19 17:55:04.206  6220  6275 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
08-19 17:55:04.206  6220  6275 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
08-19 17:55:04.206  6220  6275 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
08-19 17:55:04.206  6220  6275 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
08-19 17:55:04.206  6220  6275 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
08-19 17:55:04.206  6220  6275 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
08-19 17:55:04.206  6220  6275 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
08-19 17:55:04.206  6220  6275 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
08-19 17:55:04.206  6220  6275 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
08-19 17:55:04.206  6220  6275 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
08-19 17:55:04.206  6220  6275 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
08-19 17:55:04.206  6220  6275 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
08-19 17:55:04.206  6220  6275 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
08-19 17:55:04.206  6220  6275 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
08-19 17:55:04.216  6220  6275 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
08-19 17:55:04.216  6220  6275 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
08-19 17:55:04.216  6220  6275 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
08-19 17:55:04.216  6220  6275 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
08-19 17:55:04.216  6220  6275 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
08-19 17:55:04.216  6220  6275 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
08-19 17:55:04.216  6220  6275 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-19 17:55:04.216  6220  6275 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_,STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-19 17:55:04.216  6220  6275 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-19 17:55:04.216  6220  6275 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-19 17:55:04.216  6220  6275 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-19 17:55:04.216  6220  6275 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-19 17:55:04.216  6220  6275 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@6f5efe7 not in the list
08-19 17:55:04.216  6220  6275 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-19 17:55:04.216  6220  6275 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1979b794 not in the list
08-19 17:55:04.216  6220  6275 D io.jxcore.node.ConnectivityMonitor: stop
08-19 17:55:04.216  6220  6275 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-19 17:55:04.216  6220  6275 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-19 17:55:04.216  6220  6275 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-19 17:55:04.216  6220  6275 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-19 17:55:04.216  6220  6275 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-19 17:55:04.216  6220  6275 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-19 17:55:04.216  6220  6275 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-19 17:55:04.216  6220  6275 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1979b794 not in the list
08-19 17:55:04.216  6220  6275 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
08-19 17:55:04.216  6220  6275 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-19 17:55:04.216  6220  6275 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-19 17:55:04.216  6220  6275 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-19 17:55:04.216  6220  6275 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-19 17:55:04.216  6220  6275 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-19 17:55:04.216  6220  6275 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-19 17:55:04.216  6220  6275 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-19 17:55:04.216  6220  6275 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-19 17:55:04.216  6220  6275 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-19 17:55:04.216  6220  6275 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-19 17:55:04.216  6220  6275 D io.jxcore.node.ConnectivityMonitor: start: OK
08-19 17:55:04.216  6220  6275 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-19 17:55:04.216  6220  6275 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-19 17:55:04.216  6220  6275 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-19 17:55:04.216  6220  6275 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-19 17:55:04.216  6220  6275 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-19 17:55:04.226  6220  6220 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-19 17:55:04.226  6220  6275 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
08-19 17:55:04.226  6220  6275 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
08-19 17:55:04.236  6220  6275 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
08-19 17:55:04.236  6220  6275 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded filtering: Storing the value (SUPPORTED) in persistent storage
08-19 17:55:04.236  6220  6275 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded scan batching: Storing the value (SUPPORTED) in persistent storage
08-19 17:55:04.236  6220  6275 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
08-19 17:55:04.246  6220  6275 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
08-19 17:55:04.246  6220  6275 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,08-19 17:55:04.256  2704  2721 D BtGatt.GattService: registerClient() - UUID=fa152cd3-383f-47ba-ae0a-4fa0b35e596a
,08-19 17:55:04.296  2704  2763 D BtGatt.GattService: onClientRegistered() - UUID=fa152cd3-383f-47ba-ae0a-4fa0b35e596a, clientIf=6
,08-19 17:55:04.306  6220  6228 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=6
,08-19 17:55:04.306  2704  2947 D BtGatt.GattService: start scan with filters
,08-19 17:55:04.306  2704  2768 D BtGatt.ScanManager: handling starting scan
,08-19 17:55:04.306  6220  6275 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,08-19 17:55:04.306  6220  6275 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
,08-19 17:55:04.306  6220  6275 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
,08-19 17:55:04.306  6220  6275 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,08-19 17:55:04.316  6220  6275 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false,
08-19 17:55:04.316  2704  2768 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@336b5259
08-19 17:55:04.316  6220  6220 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
08-19 17:55:04.316  6220  6275 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
08-19 17:55:04.316  6220  6275 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-19 17:55:04.316  2704  2763 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=6, status=0, action=1,
08-19 17:55:04.316  2704  2763 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-19 17:55:04.316  2704  2768 D BtGatt.ScanManager: allow scan with filters
08-19 17:55:04.316  2704  2768 D BtGatt.ScanManager: client filter size is = 1available filters are = 13
08-19 17:55:04.316  2704  2768 D BtGatt.ScanManager: set filter index= 3 for clientIf= 6
08-19 17:55:04.326  6220  6275 I io.jxcore.node.ConnectionHelper: start: OK
,08-19 17:55:04.326  2704  2763 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=0, availableSpace=15
,08-19 17:55:04.326  2704  2763 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-19 17:55:04.326  2704  2768 D BtGatt.ScanManager: Starting BLE batch scan
,08-19 17:55:04.326  2704  2768 D BtGatt.ScanManager: configuring batch scan storage, appIf 6
,08-19 17:55:04.326  6220  6275 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-19 17:55:04.326  6220  6275 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
,08-19 17:55:04.326  6220  6275 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
,08-19 17:55:04.326  6220  6275 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
08-19 17:55:04.326  6220  6275 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-19 17:55:04.326  6220  6275 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,08-19 17:55:04.326  2704  2763 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=6, status=0
,08-19 17:55:04.336  2704  2763 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-19 17:55:04.336  6220  6275 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-19 17:55:04.336  6220  6275 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-19 17:55:04.336  6220  6275 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-19 17:55:04.336  6220  6275 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,08-19 17:55:04.336  6220  6275 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
,08-19 17:55:04.336  6220  6275 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,08-19 17:55:04.336  2704  2947 D BtGatt.GattService: stopScan() - queue size =1
,08-19 17:55:04.336  2704  2721 D BtGatt.GattService: unregisterClient() - clientIf=6
,08-19 17:55:04.336  2704  2763 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=1
08-19 17:55:04.336  2704  2763 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-19 17:55:04.336  6220  6275 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-19 17:55:04.336  6220  6275 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
08-19 17:55:04.336  6220  6275 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
,08-19 17:55:04.336  6220  6275 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
08-19 17:55:04.336  6220  6275 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,08-19 17:55:04.336  6220  6275 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,08-19 17:55:04.346  6220  6275 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
08-19 17:55:04.346  6220  6275 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-19 17:55:04.346  6220  6275 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,08-19 17:55:04.346  6220  6275 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-19 17:55:04.346  2704  2768 D BtGatt.ScanManager: filter size is 1
,08-19 17:55:04.346  6220  6220 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-19 17:55:04.346  6220  6275 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-19 17:55:04.346  6220  6275 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-19 17:55:04.346  6220  6275 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-19 17:55:04.346  6220  6275 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@6f5efe7 not in the list
08-19 17:55:04.346  6220  6275 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-19 17:55:04.346  6220  6275 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1979b794 not in the list
08-19 17:55:04.346  6220  6275 D io.jxcore.node.ConnectivityMonitor: stop
08-19 17:55:04.346  6220  6275 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-19 17:55:04.346  6220  6275 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
08-19 17:55:04.346  6220  6220 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-19 17:55:04.346  6220  6220 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,08-19 17:55:04.346  6220  6275 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-19 17:55:04.346  2704  2768 D BtGatt.ScanManager: delete FilterIndex - 3
,08-19 17:55:04.346  6220  6275 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-19 17:55:04.346  6220  6275 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-19 17:55:04.346  6220  6275 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-19 17:55:04.346  6220  6275 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-19 17:55:04.346  6220  6275 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-19 17:55:04.346  6220  6275 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-19 17:55:04.346  6220  6275 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-19 17:55:04.346  6220  6275 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-19 17:55:04.346  2704  2763 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=1, availableSpace=16
,08-19 17:55:04.346  2704  2763 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-19 17:55:04.346  2704  2768 D BtGatt.ScanManager: stopping BLe Batch
,08-19 17:55:04.346  6220  6275 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-19 17:55:04.346  6220  6275 D io.jxcore.node.ConnectivityMonitor: start: OK
08-19 17:55:04.356  6220  6275 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-19 17:55:04.356  6220  6275 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-19 17:55:04.356  6220  6275 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-19 17:55:04.356  6220  6275 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-19 17:55:04.356  6220  6275 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,08-19 17:55:04.356  6220  6220 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-19 17:55:04.356  2704  2763 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=0
,08-19 17:55:04.356  2704  2763 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-19 17:55:04.356  2704  2768 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
,08-19 17:55:04.356  6220  6275 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,08-19 17:55:04.356  2704  2763 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=0
,08-19 17:55:04.356  2704  2763 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-19 17:55:04.366  6220  6275 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-19 17:55:04.366  6220  6275 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-19 17:55:04.366  6220  6275 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,08-19 17:55:04.366  6220  6275 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
,08-19 17:55:04.366  6220  6275 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,08-19 17:55:04.366  2704  2947 D BtGatt.GattService: registerClient() - UUID=2a6d1216-5fcd-4cbd-a750-138ffb90cc86
,08-19 17:55:04.406  2704  2763 D BtGatt.GattService: onClientRegistered() - UUID=2a6d1216-5fcd-4cbd-a750-138ffb90cc86, clientIf=6
,08-19 17:55:04.416  6220  6228 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=6,
08-19 17:55:04.416  2704  2721 D BtGatt.GattService: start scan with filters
,08-19 17:55:04.416  2704  2768 D BtGatt.ScanManager: handling starting scan
,08-19 17:55:04.416  6220  6275 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,08-19 17:55:04.416  6220  6275 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
,08-19 17:55:04.416  6220  6275 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
08-19 17:55:04.416  6220  6275 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,08-19 17:55:04.416  2704  2763 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=6, status=0, action=1
,08-19 17:55:04.416  2704  2763 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-19 17:55:04.416  2704  2768 D BtGatt.ScanManager: allow scan with filters
,08-19 17:55:04.416  2704  2768 D BtGatt.ScanManager: client filter size is = 1available filters are = 13
08-19 17:55:04.416  2704  2768 D BtGatt.ScanManager: set filter index= 4 for clientIf= 6
,08-19 17:55:04.426  2704  2763 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=0, availableSpace=15
,08-19 17:55:04.426  2704  2763 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-19 17:55:04.426  2704  2768 D BtGatt.ScanManager: Starting BLE batch scan
,08-19 17:55:04.426  2704  2768 D BtGatt.ScanManager: configuring batch scan storage, appIf 6
,08-19 17:55:04.426  6220  6275 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-19 17:55:04.426  6220  6220 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-19 17:55:04.436  6220  6275 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,08-19 17:55:04.436  2704  2763 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=6, status=0
08-19 17:55:04.436  2704  2763 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-19 17:55:04.436  6220  6275 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-19 17:55:04.436  2704  2763 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=1
,08-19 17:55:04.436  2704  2763 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-19 17:55:04.446  6220  6275 I io.jxcore.node.ConnectionHelper: start: OK
,08-19 17:55:04.446  6220  6275 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-19 17:55:04.446  6220  6275 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
,08-19 17:55:04.446  6220  6275 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
,08-19 17:55:04.446  6220  6275 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
08-19 17:55:04.446  6220  6275 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-19 17:55:04.446  6220  6275 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,08-19 17:55:04.446  6220  6275 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-19 17:55:04.446  6220  6275 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-19 17:55:04.446  6220  6275 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-19 17:55:04.446  6220  6275 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,08-19 17:55:04.456  6220  6275 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
,08-19 17:55:04.456  6220  6275 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,08-19 17:55:04.456  2704  2946 D BtGatt.GattService: stopScan() - queue size =1
,08-19 17:55:04.456  2704  2768 D BtGatt.ScanManager: filter size is 1
,08-19 17:55:04.456  2704  2768 D BtGatt.ScanManager: delete FilterIndex - 4
,08-19 17:55:04.456  2704  2947 D BtGatt.GattService: unregisterClient() - clientIf=6
,08-19 17:55:04.456  2704  2763 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=1, availableSpace=16
08-19 17:55:04.456  2704  2763 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-19 17:55:04.456  6220  6275 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-19 17:55:04.456  6220  6275 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
08-19 17:55:04.456  6220  6275 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
08-19 17:55:04.456  6220  6275 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
08-19 17:55:04.456  6220  6275 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,08-19 17:55:04.456  2704  2768 D BtGatt.ScanManager: stopping BLe Batch
,08-19 17:55:04.456  6220  6275 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,08-19 17:55:04.466  6220  6275 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,08-19 17:55:04.466  6220  6275 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
,08-19 17:55:04.466  6220  6275 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,08-19 17:55:04.466  6220  6275 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-19 17:55:04.466  2704  2763 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=0
,08-19 17:55:04.466  2704  2763 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-19 17:55:04.466  2704  2768 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
,08-19 17:55:04.466  6220  6275 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-19 17:55:04.466  6220  6275 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-19 17:55:04.466  6220  6275 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-19 17:55:04.466  6220  6275 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@6f5efe7 not in the list
08-19 17:55:04.466  6220  6275 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-19 17:55:04.466  6220  6275 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1979b794 not in the list
08-19 17:55:04.466  6220  6275 D io.jxcore.node.ConnectivityMonitor: stop
08-19 17:55:04.466  6220  6275 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-19 17:55:04.466  6220  6275 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-19 17:55:04.466  6220  6275 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-19 17:55:04.476  6220  6275 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-19 17:55:04.476  6220  6275 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-19 17:55:04.476  6220  6275 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-19 17:55:04.476  6220  6275 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1979b794 not in the list
,08-19 17:55:04.476  6220  6275 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
,08-19 17:55:04.476  2704  2763 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=0
,08-19 17:55:04.476  2704  2763 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-19 17:55:04.476  6220  6220 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-19 17:55:04.476  6220  6220 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-19 17:55:04.476  6220  6220 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,08-19 17:55:04.476  6220  6275 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-19 17:55:04.476  6220  6275 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-19 17:55:04.476  6220  6275 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-19 17:55:04.476  6220  6275 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-19 17:55:04.476  6220  6275 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-19 17:55:04.476  6220  6275 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-19 17:55:04.476  6220  6275 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-19 17:55:04.476  6220  6275 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-19 17:55:04.476  6220  6275 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-19 17:55:04.476  6220  6275 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-19 17:55:04.486  6220  6275 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-19 17:55:04.486  6220  6220 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-19 17:55:04.486  6220  6275 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-19 17:55:04.486  6220  6275 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-19 17:55:04.486  6220  6275 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-19 17:55:04.486  6220  6275 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-19 17:55:04.486  6220  6275 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,08-19 17:55:04.486  6220  6275 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,08-19 17:55:04.496  6220  6275 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-19 17:55:04.496  6220  6275 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-19 17:55:04.496  6220  6275 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,08-19 17:55:04.496  6220  6275 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
,08-19 17:55:04.496  6220  6275 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,08-19 17:55:04.496  2704  2947 D BtGatt.GattService: registerClient() - UUID=e89c06dc-3472-41a3-8a57-515e9867c19a
,08-19 17:55:04.546  2704  2763 D BtGatt.GattService: onClientRegistered() - UUID=e89c06dc-3472-41a3-8a57-515e9867c19a, clientIf=6
,08-19 17:55:04.546  6220  6228 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=6
,08-19 17:55:04.546  2704  2721 D BtGatt.GattService: start scan with filters
,08-19 17:55:04.546  2704  2768 D BtGatt.ScanManager: handling starting scan
,08-19 17:55:04.546  6220  6275 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,08-19 17:55:04.546  6220  6275 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
08-19 17:55:04.546  6220  6275 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
,08-19 17:55:04.546  6220  6275 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,08-19 17:55:04.546  2704  2763 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=6, status=0, action=1
,08-19 17:55:04.546  2704  2763 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-19 17:55:04.546  2704  2768 D BtGatt.ScanManager: allow scan with filters
,08-19 17:55:04.546  2704  2768 D BtGatt.ScanManager: client filter size is = 1available filters are = 13
08-19 17:55:04.546  2704  2768 D BtGatt.ScanManager: set filter index= 5 for clientIf= 6
,08-19 17:55:04.556  2704  2763 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=0, availableSpace=15
,08-19 17:55:04.556  2704  2763 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-19 17:55:04.556  2704  2768 D BtGatt.ScanManager: Starting BLE batch scan
,08-19 17:55:04.556  2704  2768 D BtGatt.ScanManager: configuring batch scan storage, appIf 6
,08-19 17:55:04.556  6220  6275 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-19 17:55:04.556  6220  6220 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-19 17:55:04.566  6220  6275 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
08-19 17:55:04.566  2704  2763 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=6, status=0
08-19 17:55:04.566  2704  2763 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-19 17:55:04.566  6220  6275 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-19 17:55:04.566  2704  2763 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=1
,08-19 17:55:04.566  2704  2763 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-19 17:55:04.576  6220  6275 I io.jxcore.node.ConnectionHelper: start: OK
,08-19 17:55:04.576  6220  6275 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-19 17:55:04.576  6220  6275 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
,08-19 17:55:04.576  6220  6275 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
,08-19 17:55:04.576  6220  6275 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
08-19 17:55:04.576  6220  6275 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-19 17:55:04.576  6220  6275 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-19 17:55:04.576  6220  6275 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
,08-19 17:55:04.576  6220  6275 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
,08-19 17:55:04.576  6220  6275 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-19 17:55:04.576  6220  6275 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,08-19 17:55:04.576  6220  6275 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
,08-19 17:55:04.576  6220  6275 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,08-19 17:55:04.586  2704  2947 D BtGatt.GattService: stopScan() - queue size =1,
,08-19 17:55:04.586  2704  2768 D BtGatt.ScanManager: filter size is 1
,08-19 17:55:04.586  2704  2768 D BtGatt.ScanManager: delete FilterIndex - 5
,08-19 17:55:04.586  2704  2721 D BtGatt.GattService: unregisterClient() - clientIf=6
,08-19 17:55:04.586  2704  2763 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=1, availableSpace=16
08-19 17:55:04.586  2704  2763 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-19 17:55:04.586  2704  2768 D BtGatt.ScanManager: stopping BLe Batch
,08-19 17:55:04.586  6220  6275 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-19 17:55:04.586  6220  6275 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
08-19 17:55:04.586  6220  6275 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
08-19 17:55:04.586  6220  6275 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
08-19 17:55:04.586  6220  6275 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,08-19 17:55:04.586  6220  6275 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,08-19 17:55:04.596  6220  6275 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,08-19 17:55:04.596  6220  6275 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
,08-19 17:55:04.596  6220  6275 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,08-19 17:55:04.596  6220  6275 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-19 17:55:04.596  2704  2763 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=0
,08-19 17:55:04.596  2704  2763 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-19 17:55:04.596  2704  2768 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
,08-19 17:55:04.596  6220  6220 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,08-19 17:55:04.596  6220  6220 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,08-19 17:55:04.606  6220  6275 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-19 17:55:04.606  6220  6275 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
08-19 17:55:04.606  6220  6275 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-19 17:55:04.606  6220  6275 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-19 17:55:04.606  6220  6275 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-19 17:55:04.606  6220  6275 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-19 17:55:04.606  6220  6275 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-19 17:55:04.606  6220  6275 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@6f5efe7 not in the list
08-19 17:55:04.606  6220  6275 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-19 17:55:04.606  6220  6220 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-19 17:55:04.606  6220  6275 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1979b794 not in the list
08-19 17:55:04.606  6220  6275 D io.jxcore.node.ConnectivityMonitor: stop
08-19 17:55:04.606  6220  6275 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-19 17:55:04.606  2704  2763 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=0
08-19 17:55:04.606  2704  2763 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-19 17:55:04.606  6220  6275 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-19 17:55:04.606  6220  6275 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-19 17:55:04.606  6220  6275 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-19 17:55:04.606  6220  6275 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-19 17:55:04.606  6220  6275 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-19 17:55:04.606  6220  6275 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1979b794 not in the list
,08-19 17:55:04.606  6220  6275 D io.jxcore.node.ConnectionHelper: onPeerReadyToProvideBluetoothMacAddress: Bro Mode is not supported
,08-19 17:55:04.606  6220  6275 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-19 17:55:04.606  6220  6275 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-19 17:55:04.606  6220  6275 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-19 17:55:04.606  6220  6275 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-19 17:55:04.606  6220  6275 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-19 17:55:04.606  6220  6275 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-19 17:55:04.606  6220  6275 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@6f5efe7 not in the list
08-19 17:55:04.606  6220  6275 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-19 17:55:04.616  6220  6275 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1979b794 not in the list
08-19 17:55:04.616  6220  6275 D io.jxcore.node.ConnectivityMonitor: stop
08-19 17:55:04.616  6220  6275 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-19 17:55:04.616  6220  6275 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-19 17:55:04.616  6220  6275 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-19 17:55:04.616  6220  6275 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-19 17:55:04.616  6220  6275 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-19 17:55:04.616  6220  6275 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-19 17:55:04.616  6220  6275 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-19 17:55:04.616  6220  6275 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1979b794 not in the list
,08-19 17:55:04.616  6220  6275 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
,08-19 17:55:04.616  6220  6275 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-19 17:55:04.616  6220  6275 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-19 17:55:04.616  6220  6275 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-19 17:55:04.616  6220  6275 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-19 17:55:04.616  6220  6275 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-19 17:55:04.616  6220  6275 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-19 17:55:04.616  6220  6275 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@6f5efe7 not in the list
08-19 17:55:04.616  6220  6275 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-19 17:55:04.616  6220  6275 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1979b794 not in the list
08-19 17:55:04.616  6220  6275 D io.jxcore.node.ConnectivityMonitor: stop
08-19 17:55:04.616  6220  6275 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-19 17:55:04.616  6220  6275 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-19 17:55:04.616  6220  6275 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-19 17:55:04.616  6220  6275 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-19 17:55:04.616  6220  6275 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-19 17:55:04.616  6220  6275 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-19 17:55:04.616  6220  6275 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-19 17:55:04.616  6220  6275 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1979b794 not in the list
,08-19 17:55:04.626  6220  6275 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: null
,08-19 17:55:04.626  6220  6275 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-19 17:55:04.626  6220  6275 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-19 17:55:04.626  6220  6275 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-19 17:55:04.626  6220  6275 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-19 17:55:04.626  6220  6275 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-19 17:55:04.626  6220  6275 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-19 17:55:04.626  6220  6275 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@6f5efe7 not in the list
,08-19 17:55:04.626  6220  6275 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-19 17:55:04.626  6220  6275 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1979b794 not in the list
08-19 17:55:04.626  6220  6275 D io.jxcore.node.ConnectivityMonitor: stop
,08-19 17:55:04.626  6220  6275 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-19 17:55:04.626  6220  6275 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-19 17:55:04.626  6220  6275 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-19 17:55:04.626  6220  6275 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-19 17:55:04.626  6220  6275 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-19 17:55:04.626  6220  6275 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-19 17:55:04.626  6220  6275 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-19 17:55:04.626  6220  6275 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1979b794 not in the list
,08-19 17:55:04.626  6220  6275 V io.jxcore.node.ConnectionHelper: Received a request for permission "randomString", but we are expecting that all the required permissions have already been granted
,08-19 17:55:04.626  6220  6275 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-19 17:55:04.626  6220  6275 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,08-19 17:55:04.626  6220  6275 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-19 17:55:04.626  6220  6275 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-19 17:55:04.626  6220  6275 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-19 17:55:04.626  6220  6275 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-19 17:55:04.626  6220  6275 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@6f5efe7 not in the list
08-19 17:55:04.626  6220  6275 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-19 17:55:04.626  6220  6275 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1979b794 not in the list
,08-19 17:55:04.626  6220  6275 D io.jxcore.node.ConnectivityMonitor: stop
08-19 17:55:04.626  6220  6275 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-19 17:55:04.626  6220  6275 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-19 17:55:04.626  6220  6275 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-19 17:55:04.626  6220  6275 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-19 17:55:04.626  6220  6275 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-19 17:55:04.626  6220  6275 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery,
08-19 17:55:04.626  6220  6275 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-19 17:55:04.626  6220  6275 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1979b794 not in the list
,08-19 17:55:04.636  6220  6275 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
,08-19 17:55:04.636  6220  6275 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-19 17:55:04.636  6220  6275 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
08-19 17:55:04.636  6220  6275 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-19 17:55:04.636  6220  6275 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
08-19 17:55:04.636  6220  6275 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-19 17:55:04.636  6220  6275 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-19 17:55:04.636  6220  6275 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-19 17:55:04.636  6220  6275 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-19 17:55:04.636  6220  6275 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-19 17:55:04.636  6220  6275 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-19 17:55:04.636  6220  6275 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-19 17:55:04.636  6220  6275 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@6f5efe7 not in the list
08-19 17:55:04.636  6220  6275 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-19 17:55:04.636  6220  6275 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1979b794 not in the list
,08-19 17:55:04.636  6220  6275 D io.jxcore.node.ConnectivityMonitor: stop
08-19 17:55:04.636  6220  6275 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-19 17:55:04.636  6220  6275 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-19 17:55:04.636  6220  6275 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-19 17:55:04.636  6220  6275 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-19 17:55:04.636  6220  6275 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-19 17:55:04.636  6220  6275 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-19 17:55:04.636  6220  6275 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-19 17:55:04.636  6220  6275 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1979b794 not in the list
08-19 17:55:04.636  6220  6275 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-19 17:55:04.636  6220  6275 E io.jxcore.node.ConnectionHelper: connect: We already have an outgoing connection to peer with ID 00:11:22:33:44:55
08-19 17:55:04.636  6220  6275 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
,08-19 17:55:04.636  6220  6275 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55,
08-19 17:55:04.636  6220  6275 E io.jxcore.node.ConnectionHelper: connect: Maximum number of peer connections (30) reached, please try again after disconnecting a peer
08-19 17:55:04.636  6220  6275 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
,08-19 17:55:04.636  6220  6275 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
08-19 17:55:04.636  6220  6275 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
08-19 17:55:04.636  6220  6275 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
08-19 17:55:04.636  6220  6275 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
,08-19 17:55:04.636  6220  6275 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
08-19 17:55:04.636  6220  6275 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
08-19 17:55:04.636  6220  6275 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
08-19 17:55:04.636  6220  6275 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
08-19 17:55:04.636  6220  6275 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
08-19 17:55:04.636  6220  6275 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
,08-19 17:55:04.636  6220  6275 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
08-19 17:55:04.636  6220  6275 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
08-19 17:55:04.636  6220  6275 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
08-19 17:55:04.636  6220  6275 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
08-19 17:55:04.636  6220  6275 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
08-19 17:55:04.636  6220  6275 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
,08-19 17:55:04.636  6220  6275 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
08-19 17:55:04.636  6220  6275 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
08-19 17:55:04.636  6220  6275 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
08-19 17:55:04.636  6220  6275 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
,08-19 17:55:04.636  6220  6275 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
08-19 17:55:04.636  6220  6275 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
08-19 17:55:04.636  6220  6275 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
08-19 17:55:04.636  6220  6275 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
08-19 17:55:04.636  6220  6275 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
08-19 17:55:04.636  6220  6275 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
08-19 17:55:04.636  6220  6275 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
08-19 17:55:04.636  6220  6275 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
08-19 17:55:04.636  6220  6275 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
08-19 17:55:04.636  6220  6275 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID abcd
08-19 17:55:04.636  6220  6275 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
08-19 17:55:04.636  6220  6275 E io.jxcore.node.ConnectionHelper: connect: Invalid Bluetooth MAC address: abcd
08-19 17:55:04.636  6220  6275 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-19 17:55:04.636  6220  6275 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
08-19 17:55:04.636  6220  6275 E io.jxcore.node.ConnectionHelper: connect: Failed to add the callback for the connection
08-19 17:55:04.636  6220  6275 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-19 17:55:04.636  6220  6275 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
08-19 17:55:04.636  6220  6275 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: connect: [<no peer name> 00:11:22:33:44:55],
,08-19 17:55:04.646  6220  6275 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Trying to start connecting to null in address 00:11:22:33:44:55
08-19 17:55:04.646  6220  6275 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setInsecureRfcommSocketPortNumber: Using port -1
08-19 17:55:04.646  6220  6275 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setMaxNumberOfRetries: 0
,08-19 17:55:04.646  6220  6275 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnecting: null 00:11:22:33:44:55
08-19 17:55:04.646  6220  6275 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Started connecting to null in address 00:11:22:33:44:55
08-19 17:55:04.646  6220  6275 I io.jxcore.node.ConnectionHelper: connect: Connection process successfully started (peer ID: 00:11:22:33:44:55)
08-19 17:55:04.646  6220  6275 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-19 17:55:04.646  6220  6275 E io.jxcore.node.ConnectionHelper: connect: Callback is null
08-19 17:55:04.646  6220  6275 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections,
,08-19 17:55:04.646  6220  6275 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-19 17:55:04.646  6220  6298 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Trying to connect to peer with address 00:11:22:33:44:55 (thread ID: 1189)
08-19 17:55:04.646  6220  6275 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-19 17:55:04.646  6220  6275 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-19 17:55:04.646  6220  6275 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-19 17:55:04.646  6220  6275 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-19 17:55:04.646  6220  6275 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: cancelAllConnectionAttempts: Shutting down 1 client threads
08-19 17:55:04.646  6220  6275 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@6f5efe7 not in the list
08-19 17:55:04.646  6220  6275 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-19 17:55:04.646  6220  6275 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1979b794 not in the list
08-19 17:55:04.646  6220  6275 D io.jxcore.node.ConnectivityMonitor: stop
08-19 17:55:04.646  6220  6275 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-19 17:55:04.646  6220  6275 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-19 17:55:04.646  6220  6275 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-19 17:55:04.646  6220  6275 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-19 17:55:04.646  6220  6275 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-19 17:55:04.646  6220  6275 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-19 17:55:04.646  6220  6275 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-19 17:55:04.646  6220  6275 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1979b794 not in the list
,08-19 17:55:04.646  6220  6299 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: shutdown: Thread ID: 1189
,08-19 17:55:04.646  6220  6275 E io.jxcore.node.ConnectionHelper: onProvideBluetoothMacAddressRequest: Request ID: 1111 - Bro Mode is not supported
08-19 17:55:04.646  6220  6275 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-19 17:55:04.646  6220  6275 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,08-19 17:55:04.646  6220  6275 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-19 17:55:04.646  6220  6275 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-19 17:55:04.646  6220  6275 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-19 17:55:04.646  6220  6275 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-19 17:55:04.646  6220  6275 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@6f5efe7 not in the list
08-19 17:55:04.646  6220  6275 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose,
08-19 17:55:04.646  6220  6275 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1979b794 not in the list
08-19 17:55:04.646  6220  6275 D io.jxcore.node.ConnectivityMonitor: stop
08-19 17:55:04.656  6220  6275 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-19 17:55:04.656  6220  6275 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-19 17:55:04.656  6220  6275 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-19 17:55:04.656  6220  6275 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-19 17:55:04.656  6220  6275 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-19 17:55:04.656  6220  6275 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-19 17:55:04.656  6220  6275 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-19 17:55:04.656  6220  6275 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1979b794 not in the list
08-19 17:55:04.656  6220  6275 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: true
08-19 17:55:04.656  6220  6275 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-19 17:55:04.656  6220  6275 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-19 17:55:04.656  6220  6275 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-19 17:55:04.656  6220  6275 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-19 17:55:04.656  6220  6275 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-19 17:55:04.656  6220  6275 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-19 17:55:04.656  6220  6275 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@6f5efe7 not in the list
08-19 17:55:04.656  6220  6275 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-19 17:55:04.656  6220  6275 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1979b794 not in the list
08-19 17:55:04.656  6220  6275 D io.jxcore.node.ConnectivityMonitor: stop
,08-19 17:55:04.656  6220  6275 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-19 17:55:04.656  6220  6275 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-19 17:55:04.656  6220  6275 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-19 17:55:04.656  6220  6275 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-19 17:55:04.656  6220  6275 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-19 17:55:04.656  6220  6275 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-19 17:55:04.656  6220  6275 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-19 17:55:04.656  6220  6275 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1979b794 not in the list
08-19 17:55:04.656  6220  6298 D BluetoothUtils: isSocketAllowedBySecurityPolicy start : device null
08-19 17:55:04.656  6220  6275 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID randomString
08-19 17:55:04.656  6220  6275 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID randomString
08-19 17:55:04.656  6220  6275 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
08-19 17:55:04.656  6220  6275 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: randomString), either no such connection or failed to close the connection
08-19 17:55:04.656  6220  6275 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
08-19 17:55:04.656  6220  6275 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 00:11:22:33:44:55
08-19 17:55:04.656  6220  6275 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
08-19 17:55:04.656  6220  6275 I io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Successfully disconnected (peer ID: 00:11:22:33:44:55
08-19 17:55:04.656  6220  6275 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
08-19 17:55:04.656  6220  6275 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 00:11:22:33:44:55
08-19 17:55:04.656  6220  6275 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
08-19 17:55:04.656  6220  6275 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: 00:11:22:33:44:55), either no such connection or failed to close the connection
08-19 17:55:04.656  6220  6275 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-19 17:55:04.656  6220  6275 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-19 17:55:04.656  6220  6275 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-19 17:55:04.656  6220  6275 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-19 17:55:04.656  6220  6275 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-19 17:55:04.656  6220  6275 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-19 17:55:04.656  6220  6275 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@6f5efe7 not in the list
08-19 17:55:04.656  6220  6275 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-19 17:55:04.656  6220  6275 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1979b794 not in the list
08-19 17:55:04.656  6220  6275 D io.jxcore.node.ConnectivityMonitor: stop
08-19 17:55:04.656  6220  6275 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-19 17:55:04.656  6220  6275 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-19 17:55:04.656  6220  6275 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-19 17:55:04.656  6220  6275 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-19 17:55:04.656  6220  6275 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-19 17:55:04.656  6220  6275 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-19 17:55:04.656  6220  6275 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-19 17:55:04.656  6220  6275 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1979b794 not in the list
08-19 17:55:04.656  6220  6275 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-19 17:55:04.656  6220  6275 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-19 17:55:04.656  6220  6275 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-19 17:55:04.666  6220  6275 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@6f5efe7 not in the list
08-19 17:55:04.666  6220  6275 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-19 17:55:04.666  6220  6275 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1979b794 not in the list
08-19 17:55:04.666  6220  6275 D io.jxcore.node.ConnectivityMonitor: stop
08-19 17:55:04.666  6220  6275 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-19 17:55:04.666  6220  6275 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-19 17:55:04.666  6220  6275 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-19 17:55:04.666  6220  6275 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1979b794 not in the list
08-19 17:55:04.666  6220  6275 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-19 17:55:04.666  6220  6275 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-19 17:55:04.666  6220  6275 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-19 17:55:04.666  6220  6275 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@6f5efe7 not in the list
08-19 17:55:04.666  6220  6275 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-19 17:55:04.666  6220  6275 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-19 17:55:04.666  6220  6275 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-19 17:55:04.666  6220  6275 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-19 17:55:04.666  6220  6275 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-19 17:55:04.666  6220  6275 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-19 17:55:04.666  6220  6275 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@6f5efe7 not in the list
08-19 17:55:04.666  6220  6275 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-19 17:55:04.666  6220  6275 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1979b794 not in the list
08-19 17:55:04.666  6220  6275 D io.jxcore.node.ConnectivityMonitor: stop
08-19 17:55:04.666  6220  6275 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-19 17:55:04.666  6220  6275 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-19 17:55:04.666  6220  6275 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-19 17:55:04.666  6220  6275 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-19 17:55:04.666  6220  6275 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-19 17:55:04.666  6220  6275 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-19 17:55:04.666  6220  6275 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-19 17:55:04.666  6220  6275 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1979b794 not in the list
08-19 17:55:04.666  6220  6298 D BluetoothSocket: connect(): myUserId = 0
08-19 17:55:04.666  6220  6298 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-19 17:55:04.666  6220  6275 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
08-19 17:55:04.666  6220  6275 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-19 17:55:04.666  2704  2946 D BTIF_SOCK: service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
08-19 17:55:04.666  6220  6275 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
08-19 17:55:04.666  6220  6275 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
08-19 17:55:04.666  6220  6275 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
08-19 17:55:04.666  6220  6275 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
08-19 17:55:04.666  6220  6275 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-19 17:55:04.666  6220  6275 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-19 17:55:04.666  6220  6275 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
08-19 17:55:04.666  6220  6275 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
08-19 17:55:04.666  6220  6275 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
08-19 17:55:04.666  6220  6275 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-19 17:55:04.666  6220  6275 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
08-19 17:55:04.666  6220  6275 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@6f5efe7 not in the list
08-19 17:55:04.666  6220  6275 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-19 17:55:04.666  6220  6275 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-19 17:55:04.666  6220  6275 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-19 17:55:04.666  6220  6275 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-19 17:55:04.666  6220  6275 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-19 17:55:04.666  6220  6275 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-19 17:55:04.666  6220  6220 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
08-19 17:55:04.666  6220  6220 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
08-19 17:55:04.666  6220  6298 D BluetoothSocket: connect(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[106]}
08-19 17:55:04.676  6220  6275 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-19 17:55:04.676  6220  6275 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1979b794 not in the list
08-19 17:55:04.676  6220  6275 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-19 17:55:04.676  6220  6275 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-19 17:55:04.676  6220  6275 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-19 17:55:04.676  6220  6220 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-19 17:55:04.676  6220  6275 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-19 17:55:04.676  6220  6275 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-19 17:55:04.676  6220  6275 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-19 17:55:04.676  6220  6275 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@6f5efe7 not in the list
08-19 17:55:04.676  6220  6275 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-19 17:55:04.676  6220  6275 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1979b794 not in the list
08-19 17:55:04.676  6220  6275 D io.jxcore.node.ConnectivityMonitor: stop
08-19 17:55:04.676  6220  6275 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-19 17:55:04.676  6220  6275 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-19 17:55:04.676  6220  6275 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-19 17:55:04.676  6220  6275 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-19 17:55:04.676  6220  6300 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
08-19 17:55:04.676  6220  6300 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
08-19 17:55:04.676  6220  6220 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-19 17:55:04.676  6220  6220 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-19 17:55:04.676  6220  6220 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
08-19 17:55:04.676  6220  6275 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-19 17:55:04.676  6220  6275 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-19 17:55:04.676  6220  6275 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-19 17:55:04.676  6220  6275 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1979b794 not in the list
08-19 17:55:04.676  6220  6275 E io.jxcore.node.ConnectionHelper: onConnectionFailed: Peer properties: [<no peer name> 00:11:22:33:44:55], error message: ErrorMessage
08-19 17:55:04.676  6220  6275 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
08-19 17:55:04.676  6220  6275 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
08-19 17:55:04.676  6220  6275 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-19 17:55:04.676  6220  6275 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-19 17:55:04.676  6220  6275 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-19 17:55:04.676  6220  6275 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-19 17:55:04.676  6220  6275 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-19 17:55:04.676  6220  6275 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-19 17:55:04.676  6220  6275 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-19 17:55:04.676  6220  6275 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@6f5efe7 not in the list
08-19 17:55:04.676  6220  6275 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-19 17:55:04.676  6220  6275 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1979b794 not in the list
08-19 17:55:04.676  6220  6275 D io.jxcore.node.ConnectivityMonitor: stop
08-19 17:55:04.676  6220  6275 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-19 17:55:04.676  6220  6275 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-19 17:55:04.676  6220  6275 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-19 17:55:04.676  6220  6275 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-19 17:55:04.676  6220  6275 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-19 17:55:04.676  6220  6275 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-19 17:55:04.676  6220  6275 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-19 17:55:04.676  6220  6275 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1979b794 not in the list
08-19 17:55:04.676  6220  6275 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-19 17:55:04.676  6220  6275 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-19 17:55:04.676  6220  6275 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-19 17:55:04.676  6220  6275 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-19 17:55:04.676  6220  6275 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-19 17:55:04.676  6220  6275 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-19 17:55:04.676  6220  6275 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@6f5efe7 not in the list
08-19 17:55:04.676  6220  6275 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-19 17:55:04.676  6220  6275 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1979b794 not in the list
08-19 17:55:04.676  6220  6275 D io.jxcore.node.ConnectivityMonitor: stop
08-19 17:55:04.676  6220  6275 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-19 17:55:04.676  6220  6275 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-19 17:55:04.676  6220  6275 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-19 17:55:04.676  6220  6275 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-19 17:55:04.686  6220  6275 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-19 17:55:04.686  6220  6275 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-19 17:55:04.686  6220  6275 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-19 17:55:04.686  6220  6275 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1979b794 not in the list
08-19 17:55:04.686  6220  6275 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-19 17:55:04.686  6220  6275 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-19 17:55:04.686  6220  6275 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-19 17:55:04.686  6220  6275 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-19 17:55:04.686  6220  6275 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-19 17:55:04.686  6220  6275 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-19 17:55:04.686  6220  6275 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@6f5efe7 not in the list
08-19 17:55:04.686  6220  6275 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-19 17:55:04.686  6220  6275 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1979b794 not in the list
08-19 17:55:04.686  6220  6275 D io.jxcore.node.ConnectivityMonitor: stop
08-19 17:55:04.686  6220  6275 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-19 17:55:04.686  6220  6275 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-19 17:55:04.686  6220  6275 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-19 17:55:04.686  6220  6275 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-19 17:55:04.686  6220  6275 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-19 17:55:04.686  6220  6275 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-19 17:55:04.686  6220  6275 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-19 17:55:04.686  6220  6275 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1979b794 not in the list
08-19 17:55:04.686  6220  6275 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing
08-19 17:55:04.686  6220  6275 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
08-19 17:55:04.686  6220  6275 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID outgoing
08-19 17:55:04.686  6220  6275 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
08-19 17:55:04.686  6220  6275 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing2
08-19 17:55:04.686  6220  6275 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
,08-19 17:55:04.686  6220  6275 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
08-19 17:55:04.686  6220  6275 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> outgoing]
08-19 17:55:04.686  6220  6275 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 1
08-19 17:55:04.686  6220  6275 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
08-19 17:55:04.686  6220  6275 E io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Failed to find an incoming connection thread with ID 1
08-19 17:55:04.686  6220  6275 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
08-19 17:55:04.686  6220  6275 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 2
08-19 17:55:04.686  6220  6275 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
08-19 17:55:04.686  6220  6275 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing1" removed
08-19 17:55:04.686  6220  6275 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing2" removed
08-19 17:55:04.686  6220  6275 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID id
08-19 17:55:04.686  6220  6275 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID outgoing
08-19 17:55:04.686  6220  6275 D io.jxcore.node.ConnectionModel: hasConnection: We have an incoming connection with peer with ID incoming
08-19 17:55:04.686  6220  6275 D io.jxcore.node.ConnectionModel: hasConnection: We have an outgoing connection with peer with ID outgoing
08-19 17:55:04.686  6220  6275 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-19 17:55:04.686  6220  6275 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@224f7856 added. We now have 2 listener(s)
08-19 17:55:04.686  6220  6275 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-19 17:55:04.686  6220  6275 D BluetoothAdapter: enable()
08-19 17:55:04.696  6220  6275 D BluetoothAdapter: enable(): BT is already enabled..!
08-19 17:55:04.696  1015  1446 D SecContentProvider: uri = 18 selection = isWifiEnabled
08-19 17:55:04.696  1015  1446 D SecContentProvider2: uri = 20 selection = isWifiStateChangeAllowed
08-19 17:55:04.696  1015  1446 D SecContentProvider2: mCursor = null
08-19 17:55:04.696  1015  1446 D WifiService: setWifiEnabled: true pid=6220, uid=10171
08-19 17:55:04.696  1015  1446 W ActivityManager: Permission Denial: getCurrentUser() from pid=6220, uid=10171 requires android.permission.INTERACT_ACROSS_USERS
08-19 17:55:04.706  1015  1446 W WifiService: Failed getting userId using ActivityManagerNative
08-19 17:55:04.706  1015  1446 W WifiService: java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=6220, uid=10171 requires android.permission.INTERACT_ACROSS_USERS
08-19 17:55:04.706  1015  1446 W WifiService: 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:23972)
08-19 17:55:04.706  1015  1446 W WifiService: 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2216)
08-19 17:55:04.706  1015  1446 W WifiService: 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2204)
08-19 17:55:04.706  1015  1446 W WifiService: 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:223)
08-19 17:55:04.706  1015  1446 W WifiService: 	at android.os.Binder.execTransact(Binder.java:446)
08-19 17:55:04.706  1015  1446 D SettingsProvider: name = wifi_on
08-19 17:55:04.706  6220  6275 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-19 17:55:04.706  6220  6275 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@3b04a0d7 added. We now have 3 listener(s)
08-19 17:55:04.706  6220  6275 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-19 17:55:04.706  6220  6275 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-19 17:55:04.706  6220  6275 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@7442dc4 added. We now have 4 listener(s)
08-19 17:55:04.706  6220  6275 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-19 17:55:04.716  6220  6275 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-19 17:55:04.716  6220  6275 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@79164ad added. We now have 5 listener(s)
08-19 17:55:04.716  6220  6275 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-19 17:55:04.716  1015  3485 D SecContentProvider: uri = 18 selection = isWifiEnabled
08-19 17:55:04.716  1015  3485 D SecContentProvider2: uri = 20 selection = isWifiStateChangeAllowed
08-19 17:55:04.716  1015  3485 D SecContentProvider2: mCursor = null
08-19 17:55:04.716  1015  3485 D WifiService: setWifiEnabled: false pid=6220, uid=10171
08-19 17:55:04.716  1015  3485 D SettingsProvider: name = wifi_on
08-19 17:55:04.726  1015  1015 D WifiScanningService: SCAN_AVAILABLE : 1
,08-19 17:55:04.726  1015  1015 D RttService: SCAN_AVAILABLE : 1
,08-19 17:55:04.726  1015  1147 D WifiScanningService: DefaultState got{ when=-1ms what=160007 target=com.android.internal.util.StateMachine$SmHandler }
08-19 17:55:04.726  1015  1148 D RttService: EnabledState got{ when=0 what=160513 target=com.android.internal.util.StateMachine$SmHandler }
,08-19 17:55:04.726  1015  1122 D WifiP2pService: InactiveState{ what=131204 }
,08-19 17:55:04.726  1015  1122 D WifiP2pService: P2pEnabledState{ what=131204 }
,08-19 17:55:04.726  6220  6275 D BluetoothAdapter: disable()
,08-19 17:55:04.736  1015  3494 D SettingsProvider: name = bluetooth_on
,08-19 17:55:04.736   291   291 E SMD     : DCD OFF
,08-19 17:55:04.736  2704  2760 D BluetoothAdapterState: CURRENT_STATE=ON, MSG = USER_TURN_OFF
,08-19 17:55:04.746  2704  2760 D BluetoothAdapterProperties: Setting state to 13
,08-19 17:55:04.746  2704  2760 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
08-19 17:55:04.746  2704  2760 D BluetoothAdapterService: Bluetooth PBAP supproted is true
08-19 17:55:04.746  2704  2760 D BluetoothAdapterService: updateAdapterState state is 13
,08-19 17:55:04.746  1015  1470 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-19 17:55:04.746  1015  1470 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pbap.BluetoothPbapService; callingUser = 0; userId(target) = 0
,08-19 17:55:04.746  1015  1470 W ActivityManager: userId = 0, bbcId = -10000
08-19 17:55:04.746  1015  1470 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-19 17:55:04.746  1015  1470 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-19 17:55:04.746  2704  2704 I BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED, state: 13
,08-19 17:55:04.746  2704  2704 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@af52360, channel: 19, state: LISTENING
08-19 17:55:04.746  2704  2704 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@af52360, channel: 19, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@255d3348, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@17678019mSocket: android.net.LocalSocket@2c6f58de impl:android.net.LocalSocketImpl@3230aabf fd:FileDescriptor[74]
08-19 17:55:04.746  2704  2704 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@2c6f58de impl:android.net.LocalSocketImpl@3230aabf fd:FileDescriptor[74]
08-19 17:55:04.746  2704  2760 D BluetoothAdapterService: Autoconnection is available 
08-19 17:55:04.746  2704  2760 D BluetoothAdapterService: updateAdapterState prevState = 12newState = 13
08-19 17:55:04.746  2704  2760 D BluetoothAdapterService: terminating service from this receiver
,08-19 17:55:04.746  1015  1122 D WifiP2pService: sending p2p connection changed broadcast: FAILED
,08-19 17:55:04.746  1015  1125 E ConnectivityService: updateNetworkInfo()
08-19 17:55:04.746  1015  1125 D ConnectivityService: NetworkAgentInfo [WIFI_P2P () - 501] EVENT_NETWORK_INFO_CHANGED, going from UNKNOWN to DISCONNECTED, reason = null, [ Transports: WIFI Capabilities: WIFI_P2P&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-19 17:55:04.756  1015  1027 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.samsung.ble.BleAutoConnectService; callingUser = 0; userId(target) = 0
,08-19 17:55:04.756  1015  1027 W ActivityManager: userId = 0, bbcId = -10000
08-19 17:55:04.756  1015  1027 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-19 17:55:04.756  1015  1027 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-19 17:55:04.756  2704  2760 D BluetoothAdapterProperties: onBluetoothDisable()
08-19 17:55:04.756  2704  2760 D BluetoothAdapterProperties: mDiscovering is false
,08-19 17:55:04.756  1015  1301 D SecContentProvider: uri = 3 selection = isDiscoverableEnabled
08-19 17:55:04.756  1015  1015 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
08-19 17:55:04.756  1015  1015 I InputMethodManagerService: [BT Setting State] State =13
,08-19 17:55:04.756  2704  2760 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=false, isTurningOff()=true
,08-19 17:55:04.756  1172  1172 D BluetoothTile:  onBluetoothStateChange:
,08-19 17:55:04.766  1172  1172 D BluetoothTile:  onBluetoothPairedDevicesChanged:
,08-19 17:55:04.766  1172  1172 D BluetoothTile: onReceive : android.bluetooth.adapter.action.STATE_CHANGED
08-19 17:55:04.766  1172  1172 D BluetoothTile:  getBluetoothState : 13
,08-19 17:55:04.766  1172  1745 D BluetoothTile:  handleUpdatestate:false name:null
08-19 17:55:04.766  1823  1823 I SamsungIME: STATE_CHANGED = 13, KEYBOARD_BT(0), mBTKeyboardCount =0
,08-19 17:55:04.766  1015  1446 D StatusBarManagerService: setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
,08-19 17:55:04.766  1015  1475 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=false
,08-19 17:55:04.776  1172  1172 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 )
,08-19 17:55:04.776  1172  1745 D BluetoothTile:  handleUpdatestate:false name:null
,08-19 17:55:04.776  1304  1304 V BluetoothEventManager: Received android.bluetooth.adapter.action.STATE_CHANGED
,08-19 17:55:04.776  1172  1745 D STATUSBAR-QSTileView: onStateChanged: Bluetooth
,08-19 17:55:04.776  1015  1045 D WifiDisplayController: Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/FAILED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,08-19 17:55:04.776  1015  1045 D WifiDisplayAdapter: onP2pDisconnected
,08-19 17:55:04.776  6220  6220 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-19 17:55:04.776  6220  6220 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-19 17:55:04.776  6220  6220 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-19 17:55:04.776  6220  6220 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-19 17:55:04.776  6220  6220 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-19 17:55:04.776  6220  6220 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-19 17:55:04.776  6220  6220 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-19 17:55:04.776  6220  6220 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-19 17:55:04.776  6220  6220 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-19 17:55:04.776  1015  1045 D IpRemoteDisplayController: disconnectWfdBridgeServer
08-19 17:55:04.776  1015  1045 D IpRemoteDisplayController: WfdBridgeServer is already null
,08-19 17:55:04.786  6220  6220 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-19 17:55:04.786  6220  6220 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-19 17:55:04.786  6220  6275 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-19 17:55:04.786  1015  1122 D WifiP2pService: sending p2p connection changed broadcast: DISCONNECTED
,08-19 17:55:04.786  1015  1125 E ConnectivityService: updateNetworkInfo()
,08-19 17:55:04.786  2704  2763 D BluetoothUtils: getBtEnabledContainers(): btContainers = []
08-19 17:55:04.786  2704  2763 D BluetoothAdapterProperties: Scan Mode:20
08-19 17:55:04.786  6220  6275 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-19 17:55:04.796  6220  6275 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-19 17:55:04.796  6220  6275 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-19 17:55:04.796  6220  6275 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-19 17:55:04.796  6220  6275 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-19 17:55:04.796  6220  6275 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-19 17:55:04.796  6220  6275 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-19 17:55:04.796  6220  6275 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-19 17:55:04.796  6220  6275 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-19 17:55:04.796  1015  1015 E WifiStateMachine: BroadcastReceiver : WIFI_P2P_STATE_CHANGED_ACTION is : android.net.wifi.p2p.STATE_CHANGED
,08-19 17:55:04.796  1015  1045 D WifiDisplayController: Received WIFI_P2P_STATE_CHANGED_ACTION: enabled=false
08-19 17:55:04.796  1015  1045 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
08-19 17:55:04.796  1015  1045 D WifiDisplayController: disconnect
08-19 17:55:04.796  1015  1045 D WifiDisplayController: updateConnection
08-19 17:55:04.796  1015  1045 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
08-19 17:55:04.796  1015  1045 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,08-19 17:55:04.796  6220  6275 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-19 17:55:04.796  6220  6275 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-19 17:55:04.796  6220  6275 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-19 17:55:04.796  1015  1027 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,08-19 17:55:04.796  1015  1122 D WifiP2pService: P2pDisablingState
08-19 17:55:04.796  1015  1122 D WifiP2pService: P2pDisablingState{ what=147458 }
08-19 17:55:04.796  1015  1122 D WifiP2pService: p2p socket connection lost
,08-19 17:55:04.796  1015  1122 D WifiP2pService: P2pDisabledState
08-19 17:55:04.796  6220  6220 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-19 17:55:04.806  1015  1027 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.nearby.discovery.service.DiscoveryService; callingUser = 0; userId(target) = 0
,08-19 17:55:04.806   281   971 D CommandListener: Clearing all IP addresses on wlan0
,08-19 17:55:04.806  1015  1027 W ActivityManager: userId = 0, bbcId = -10000
08-19 17:55:04.806  1015  1027 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-19 17:55:04.806  1015  1027 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-19 17:55:04.806  6220  6220 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-19 17:55:04.806  1304  1304 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-19 17:55:04.806  6220  6220 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-19 17:55:04.806  2704  2760 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = BEGIN_DISABLE, isTurningOn=false, isTurningOff=true
08-19 17:55:04.806  2704  2760 E bt-btif : btif_vhci_sock_cleanup, sock_thread_handle:6, rfc_init:1, vhci_init:1
,08-19 17:55:04.806  2704  2760 E bt-btif : btif_sock_cleanup, sock_thread_handle:6, rfc_init:1, vhci_init:0
08-19 17:55:04.806  2704  2760 E bt-btif : cmd socket is not created
,08-19 17:55:04.806  2704  4720 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,08-19 17:55:04.816  2704  2813 E bt-btm  : btm_ble_start_auto_conn start : 0, 0
08-19 17:55:04.816  2704  2813 W bt-btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
,08-19 17:55:04.816  6220  6298 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@34887373, channel: -1, state: INIT
08-19 17:55:04.816  1015  1045 D WifiDisplayController: Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: false, isConnectedToProvisioningNetwork: false]
08-19 17:55:04.816  6220  6298 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@34887373, channel: -1, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@2f386230, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@2a0c9ea9mSocket: android.net.LocalSocket@1f6d3c2e impl:android.net.LocalSocketImpl@236cd3cf fd:FileDescriptor[106]
08-19 17:55:04.816  1015  1045 D WifiDisplayAdapter: onP2pDisconnected
08-19 17:55:04.816  6220  6298 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@1f6d3c2e impl:android.net.LocalSocketImpl@236cd3cf fd:FileDescriptor[106]
08-19 17:55:04.816  1015  1045 D IpRemoteDisplayController: disconnectWfdBridgeServer
08-19 17:55:04.816  6220  6298 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Exiting thread (thread ID: 1189)
08-19 17:55:04.816  1015  1045 D IpRemoteDisplayController: WfdBridgeServer is already null
,08-19 17:55:04.816  2704  2760 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,08-19 17:55:04.826  1015  3494 D ActivityManager: startService callerProcessName:com.android.settings, calleePkgName: com.android.settings
,08-19 17:55:04.826  1015  3494 D ActivityManager: retrieveServiceLocked(): component = com.android.settings/com.android.settings.bluetooth.DockService; callingUser = 0; userId(target) = 0
08-19 17:55:04.826  1172  1172 D AllShareCastTile: action: android.hardware.display.action.WIFI_DISPLAY_STATUS_CHANGED
,08-19 17:55:04.826  1015  3494 W ActivityManager: userId = 0, bbcId = -10000
08-19 17:55:04.826  1015  3494 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-19 17:55:04.826  1015  3494 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.settings
,08-19 17:55:04.826  2704  2813 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-19 17:55:04.826  2704  2813 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-19 17:55:04.826  2704  2813 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
,08-19 17:55:04.826  1015  1446 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,08-19 17:55:04.826  1172  1172 D AllShareCastTile: wifi display status changed! scanstate : 0, ActiveDisplayState : 0
,08-19 17:55:04.836  1015  1015 I WifiTrafficPoller: evaluateTrafficStatsPolling
,08-19 17:55:04.836  1380  1380 I wpa_supplicant: p2p0: State: DISCONNECTED -> DISCONNECTED
,08-19 17:55:04.836  1304  1304 D BluetoothPbap: Proxy object disconnected
08-19 17:55:04.836  1304  1304 D PbapServerProfile: Bluetooth service disconnected
,08-19 17:55:04.846  1015  1015 D LightsService: [api] [SvcLED] turnOff:: id = 4 (uid: 1000 pid: 1015) 
,08-19 17:55:04.846  1015  1015 D LightsService: [SvcLED] setSvcLedStateLocked:: SvcLEDState : 0x40 -> 0x40 | SvcLED(id=4) set Off
,08-19 17:55:04.846  1015  1075 D LightsService: [SvcLED] Lux failed to be updated in 0ms. -> handleForcedSvcLEDTasK
,08-19 17:55:04.846  1015  1075 D LightsService: [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=3) maintains its priority right
,08-19 17:55:04.846  1304  1304 D DockEventReceiver: finishStartingService: stopping service
,08-19 17:55:04.846  2704  2704 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@179158c, channel: 5, state: LISTENING
,08-19 17:55:04.846  2704  2704 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@179158c, channel: 5, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@3ffef5e1, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@3b6704d5mSocket: android.net.LocalSocket@1424ea impl:android.net.LocalSocketImpl@22cf33db fd:FileDescriptor[76]
,08-19 17:55:04.846  2704  2704 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@1424ea impl:android.net.LocalSocketImpl@22cf33db fd:FileDescriptor[76]
,08-19 17:55:04.856  1304  1304 D BluetoothNotiBroadcastReceiver: onReceive,
08-19 17:55:04.856  2704  2704 I BtOppRfcommListener: stopping Accept Thread
,08-19 17:55:04.856  2704  2704 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@2a67fe78, channel: 12, state: LISTENING,
08-19 17:55:04.856  2704  2704 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@2a67fe78, channel: 12, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@2707bb63, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@6a01951mSocket: android.net.LocalSocket@3f87a5b6 impl:android.net.LocalSocketImpl@20332b7 fd:FileDescriptor[80],
08-19 17:55:04.856  2704  2704 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@3f87a5b6 impl:android.net.LocalSocketImpl@20332b7 fd:FileDescriptor[80]
08-19 17:55:04.856  1172  1172 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x0/(null) mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-19 17:55:04.856  1172  1172 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
08-19 17:55:04.856  1172  1172 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-19 17:55:04.856  1172  1172 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-19 17:55:04.856  1172  1172 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-19 17:55:04.856  1172  1172 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-19 17:55:04.856  2704  4720 I BtOppRfcommListener: BluetoothSocket listen thread finished
,08-19 17:55:04.856  1172  1172 D PersonaManager: isKioskContainerExistOnDevice
08-19 17:55:04.856  1172  1172 D PersonaManager: isKioskContainerExistOnDevice
08-19 17:55:04.856  1172  1172 I PhoneStatusBar: Icon Only
,08-19 17:55:04.866  1172  1172 I StatusBar: Icon Only
,08-19 17:55:04.866  1172  1172 D PanelView: There is/are notification(s) 
08-19 17:55:04.866  1172  1172 D PanelView: kidsfalse mQsExpansionEnabled:true
,08-19 17:55:04.866  1172  1172 D PersonaManager: isKioskContainerExistOnDevice
08-19 17:55:04.866  1172  1172 I PhoneStatusBar: Icon Only
08-19 17:55:04.866  1172  1172 I StatusBar: Icon Only
08-19 17:55:04.866  1172  1172 D PanelView: There is/are notification(s) 
08-19 17:55:04.866  1172  1172 D PanelView: kidsfalse mQsExpansionEnabled:true
,08-19 17:55:04.866  1172  1172 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x0/(null) mQSWifiIconId=0x0/(null) mWifiActivityIconId=0x0/(null) mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-19 17:55:04.866  1172  1172 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=false enabledDesc:null
08-19 17:55:04.866  1172  1172 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-19 17:55:04.866  1172  1172 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-19 17:55:04.866  1172  1172 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-19 17:55:04.866  1172  1172 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-19 17:55:04.866  1172  1172 D STATUSBAR-WifiQuickSettingButton: onReceive : android.net.wifi.WIFI_STATE_CHANGED
,08-19 17:55:04.866  1172  1172 D STATUSBAR-WifiQuickSettingButton: Wifi onReceive(0)
,08-19 17:55:04.866  1172  1172 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
,08-19 17:55:04.866  1172  1745 D STATUSBAR-QSTileView: onStateChanged: Wi-Fi
08-19 17:55:04.866  1172  1172 D HotspotTile: onReceive : 0, 0
,08-19 17:55:04.866  1304  1304 D WifiCredService: Action received :android.net.wifi.WIFI_STATE_CHANGED
,08-19 17:55:04.876  6220  6220 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-19 17:55:04.876  6220  6220 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-19 17:55:04.876  6220  6220 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-19 17:55:04.876  6220  6220 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-19 17:55:04.876  6220  6220 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-19 17:55:04.876  6220  6220 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-19 17:55:04.876  6220  6220 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-19 17:55:04.876  6220  6220 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-19 17:55:04.876  6220  6220 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-19 17:55:04.876  6220  6220 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-19 17:55:04.876  6220  6220 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-19 17:55:04.876  6220  6220 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-19 17:55:04.876  6220  6220 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-19 17:55:04.876  6220  6220 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-19 17:55:04.876  6220  6220 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-19 17:55:04.876  6220  6220 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-19 17:55:04.876  6220  6220 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-19 17:55:04.876  6220  6220 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-19 17:55:04.876  6220  6220 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-19 17:55:04.876  6220  6220 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-19 17:55:04.876  6220  6220 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-19 17:55:04.886  6220  6220 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-19 17:55:04.886  1172  1172 V BluetoothStatusReceiver: Received android.bluetooth.adapter.action.STATE_CHANGED
08-19 17:55:04.886  1172  1172 D BluetoothStatusReceiver: AdapterStateChanged :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 13
,08-19 17:55:04.886  2704  2704 V BluetoothOppManager: cleanUp...
,08-19 17:55:04.886  1015  3485 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.intelligenceservice, hostingType: broadcast
,08-19 17:55:04.886  1015  3485 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-19 17:55:04.886  1015  3485 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-19 17:55:04.886  1015  3485 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-19 17:55:04.886  1015  3485 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-19 17:55:04.906  6307  6307 E Zygote  : MountEmulatedStorage(),
,08-19 17:55:04.906  6307  6307 E Zygote  : v2
08-19 17:55:04.906  6307  6307 I libpersona: KNOX_SDCARD checking this for 10055
08-19 17:55:04.906  6307  6307 I libpersona: KNOX_SDCARD not a persona
,08-19 17:55:04.906  6307  6307 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-19 17:55:04.916  6307  6307 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-19 17:55:04.916  1015  3485 I ActivityManager: Start proc com.samsung.android.intelligenceservice for broadcast com.samsung.android.intelligenceservice/.useranalysis.predictor.PlacePredictor$BtConnectionReceiver: pid=6307 uid=10055 gids={50055, 9997, 3001, 3002} abi=armeabi-v7a
08-19 17:55:04.916  6307  6307 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-19 17:55:04.936   308   308 I art     : Explicit concurrent mark sweep GC freed 8735(371KB) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 591us total 24.364ms
,08-19 17:55:04.936  1172  1172 D PanelView: mClearAll.setVisibility - mIsFullyOpened : false isShade : true mHasNotification : true mIsUpwardFling : false mQsFullyExpanded : true isShadeLocked : false mClearAllVisible : false
,08-19 17:55:04.936  6307  6307 D TimaKeyStoreProvider: TimaSignature is unavailable
08-19 17:55:04.936  6307  6307 D ActivityThread: Added TimaKeyStore provider
,08-19 17:55:04.946   308   308 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 586us total 16.816ms
,08-19 17:55:04.956  1380  1380 I wpa_supplicant: Blacklist: Clear (all) 
,08-19 17:55:04.966   308   308 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 581us total 16.701ms
,08-19 17:55:05.006  6307  6307 D UserAnalysis.PlaceProvider: PlaceProvider onCreate()
,08-19 17:55:05.016  1380  1380 I wpa_supplicant: p2p0: CTRL-EVENT-TERMINATING 
,08-19 17:55:05.016  1380  1380 I wpa_supplicant: wlan0: State: SCANNING -> DISCONNECTED
08-19 17:55:05.016  1380  1380 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=-1 state=0 BSSID=00.00.00 SSID=
,08-19 17:55:05.016  1015  1042 I Nat464Xlat: interfaceLinkStateChanged p2p0, false,
,08-19 17:55:05.016  2704  2813 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-19 17:55:05.016  2704  2813 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-19 17:55:05.016  2704  2813 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-19 17:55:05.016  2704  2813 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-19 17:55:05.016  2704  2813 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
,08-19 17:55:05.016  2704  2813 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-19 17:55:05.016  2704  2813 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-19 17:55:05.016  2704  2813 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-19 17:55:05.016  2704  2813 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-19 17:55:05.016  2704  2813 W bt-btif : ag scb idx 1 not allocated
08-19 17:55:05.016  2704  2813 W bt-btif : ag scb idx 2 not allocated
,08-19 17:55:05.016  2704  2813 E bt-btif : BTA AG is already disabled, ignoring ...
08-19 17:55:05.016  2704  2918 I bt_userial_mct: exiting userial_read_thread
08-19 17:55:05.016  2704  2918 D bt_userial_mct: Leaving userial_evt_read_thread()
,08-19 17:55:05.016  1015  1042 D Tethering: interfaceLinkStateChanged p2p0, false
08-19 17:55:05.016  1015  1042 D Tethering: interfaceStatusChanged p2p0, false
08-19 17:55:05.016  2704  2763 D bt_userial_mct: userial_close_reader Joined userial reader thread: 0
08-19 17:55:05.016  2704  2815 I bt_vendor: hw_epilog_process
08-19 17:55:05.026  2704  2763 D bt_userial_mct: userial_close
08-19 17:55:05.026  2704  2763 I bt_vendor: bt-vendor : BT_VND_OP_USERIAL_CLOSE btSocType: 0,
,08-19 17:55:05.046  6307  6307 D UserAnalysis.SecureDbManager: Key for secure DB is newly created,
,08-19 17:55:05.046  6307  6307 D UserAnalysis.SecurePlaceDbHelper: SecurePlaceDbHelper() 
,08-19 17:55:05.046  6307  6307 D UserAnalysis: Create SecureDbHelper
,08-19 17:55:05.056  6307  6307 D IntelligenceServiceApplication: onCreate()
,08-19 17:55:05.066  6307  6307 D IntelligenceServiceApplication: no applications having user consent for prediction,
08-19 17:55:05.066  1015  1301 D ActivityManager: startProcessLocked calleePkgName: com.google.android.apps.maps, hostingType: broadcast
,08-19 17:55:05.066  1015  1301 E ActivityManager: checkUser: useridlist=null, currentuser=0,
08-19 17:55:05.066  1015  1301 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-19 17:55:05.066  1015  1301 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-19 17:55:05.066  1015  1301 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-19 17:55:05.086  6323  6323 E Zygote  : MountEmulatedStorage()
08-19 17:55:05.086  6323  6323 E Zygote  : v2
08-19 17:55:05.086  6323  6323 I libpersona: KNOX_SDCARD checking this for 10105
08-19 17:55:05.086  6323  6323 I libpersona: KNOX_SDCARD not a persona
,08-19 17:55:05.086  6323  6323 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-19 17:55:05.086  1015  1301 I ActivityManager: Start proc com.google.android.apps.maps for broadcast com.google.android.apps.maps/com.google.android.apps.gmm.iamhere.ble.StartBleServiceReceiver: pid=6323 uid=10105 gids={50105, 9997, 3003, 1028, 1015, 3002, 3001} abi=armeabi-v7a,
08-19 17:55:05.086  1015  1470 D ActivityManager: retrieveServiceLocked(): component = com.samsung.android.intelligenceservice/com.samsung.android.placedetection.main.service.ServiceManager; callingUser = 0; userId(target) = 0
08-19 17:55:05.096  6307  6307 V PlaceDetection v1.0.19 : [PlaceDetection::stopService] Service stopped.
08-19 17:55:05.096  6323  6323 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051,
,08-19 17:55:05.096  6323  6323 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,08-19 17:55:05.106  6323  6323 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-19 17:55:05.106  6323  6323 D ActivityThread: Added TimaKeyStore provider
,08-19 17:55:05.116  6307  6307 V PlaceDetection v1.0.19 : [PlaceDetectionManager::removeDetectionListener] PlaceDetectionListener removed.
,08-19 17:55:05.116  1015  3492 I art     : Explicit concurrent mark sweep GC freed 74000(4MB) AllocSpace objects, 23(660KB) LOS objects, 33% free, 24MB/36MB, paused 2.681ms total 156.682ms
,08-19 17:55:05.176  6220  6220 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,08-19 17:55:05.196  1380  1380 I wpa_supplicant: Blacklist: Clear (all) ,
,08-19 17:55:05.196  1979  6306 I art     : Explicit concurrent mark sweep GC freed 57621(3MB) AllocSpace objects, 20(320KB) LOS objects, 39% free, 10MB/17MB, paused 1.222ms total 83.972ms
,08-19 17:55:05.216  1015  1475 I ActivityManager: Killing 5793:com.sec.pcw.device/1000 (adj 15): empty #21
,08-19 17:55:05.236   257   541 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.maps/files/
08-19 17:55:05.236   257   541 W Vold    : Returning OperationFailed - no handler for errno 0
,08-19 17:55:05.236  6323  6343 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.maps/files
,08-19 17:55:05.246   257   541 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.maps/files/
08-19 17:55:05.246   257   541 W Vold    : Returning OperationFailed - no handler for errno 0
,08-19 17:55:05.246  6323  6343 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.maps/files
,08-19 17:55:05.286  2704  2763 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: Off
08-19 17:55:05.286  2704  2763 I bt_vendor: bluetooth satus is on
08-19 17:55:05.286  2704  2763 I bt_vendor: bt-vendor : resetting BT status
08-19 17:55:05.286  2704  2763 I bt_vendor: Starting hciattach daemon
08-19 17:55:05.286  2704  2763 I bt_vendor: try to set false
08-19 17:55:05.286  1380  1380 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING 
,08-19 17:55:05.286  1015  1042 D Tethering: interfaceLinkStateChanged wlan0, false,
08-19 17:55:05.286  1015  1042 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
08-19 17:55:05.286  1015  1042 D Tethering: interfaceStatusChanged wlan0, false
,08-19 17:55:05.286  2704  2763 I bt_vendor: Starting hciattach daemon
,08-19 17:55:05.286  2704  2763 I bt_vendor: try to set false,
08-19 17:55:05.296  2704  2763 I bt_vendor: cleanup
,08-19 17:55:05.296  2704  2813 I GKI_LINUX: gki_task task_id=0 [BTU] terminating,
08-19 17:55:05.296  2704  2763 I GKI_LINUX: GKI_exit_task 0 done
08-19 17:55:05.296  2704  2763 I GKI_LINUX: GKI_shutdown(): task [BTU] terminated
,08-19 17:55:05.306  2704  2760 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = DISABLED, isTurningOn=false, isTurningOff=true,
08-19 17:55:05.306  1015  1028 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-19 17:55:05.306  2704  2760 D BtConfig.SecureMode: isSecureModeOn:false
08-19 17:55:05.306  1015  1028 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.gatt.GattService; callingUser = 0; userId(target) = 0
08-19 17:55:05.306  2704  2760 D BluetoothAdapterService: mProfilesStarted : true supportedProfileServices.length : 12
08-19 17:55:05.306  2704  2760 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.gatt.GattService
08-19 17:55:05.306  2704  2760 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.gatt.GattService
08-19 17:55:05.306  2704  2760 W BluetoothAdapterService: Not skipping com.android.bluetooth.gatt.GattService
08-19 17:55:05.306  1015  1028 W ActivityManager: userId = 0, bbcId = -10000
08-19 17:55:05.306  1015  1028 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-19 17:55:05.306  1015  1028 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
08-19 17:55:05.306  1015  1123 E WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:0
08-19 17:55:05.306  2704  2760 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hfp.HeadsetService
08-19 17:55:05.306  1015  1123 D WifiNative-wlan0: callSECApiBoolean - ID [21]
08-19 17:55:05.306  2704  2760 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
08-19 17:55:05.306  2704  2704 D BtGatt.DebugUtils: handleDebugAction() action=null
,08-19 17:55:05.306  2704  2704 D BtGatt.GattService: Received stop request...Stopping profile...
08-19 17:55:05.306  2704  2704 D BtGatt.GattService: stop()
08-19 17:55:05.306  2704  2704 D BtGatt.AdvertiseManager: advertise clients cleared
,08-19 17:55:05.306  2704  2760 W BluetoothAdapterService: Not skipping com.android.bluetooth.hfp.HeadsetService
,08-19 17:55:05.316  1172  1172 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x0/(null) mQSWifiIconId=0x0/(null) mWifiActivityIconId=0x0/(null) mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,08-19 17:55:05.316  1172  1172 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=false enabledDesc:null
08-19 17:55:05.316  1172  1172 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-19 17:55:05.316  1172  1172 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-19 17:55:05.316  1172  1172 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-19 17:55:05.316  1172  1172 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-19 17:55:05.316  1172  1172 D STATUSBAR-WifiQuickSettingButton: onReceive : android.net.wifi.WIFI_STATE_CHANGED
08-19 17:55:05.316  1172  1172 D STATUSBAR-WifiQuickSettingButton: Wifi onReceive(1)
,08-19 17:55:05.316  1172  1745 D STATUSBAR-QSTileView: onStateChanged: Wi-Fi
,08-19 17:55:05.316  1172  1172 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
,08-19 17:55:05.316  1172  1172 D HotspotTile: onReceive : 1, 0
,08-19 17:55:05.326  1304  1304 D WifiCredService: Action received :android.net.wifi.WIFI_STATE_CHANGED
,08-19 17:55:05.326  1979  2176 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-19 17:55:05.326  6220  6220 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-19 17:55:05.326  1015  1475 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-19 17:55:05.326  1015  1475 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = 0
,08-19 17:55:05.326  2704  2704 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@336b5259
,08-19 17:55:05.326  1015  1475 W ActivityManager: userId = 0, bbcId = -10000
08-19 17:55:05.326  1015  1475 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-19 17:55:05.326  1015  1475 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-19 17:55:05.326  2704  2760 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.a2dp.A2dpService
08-19 17:55:05.326  6220  6220 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-19 17:55:05.326  2704  2760 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
,08-19 17:55:05.326  2704  2760 W BluetoothAdapterService: Not skipping com.android.bluetooth.a2dp.A2dpService
,08-19 17:55:05.336  1015  3485 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-19 17:55:05.336  1015  3485 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
,08-19 17:55:05.336  1015  3485 W ActivityManager: userId = 0, bbcId = -10000
08-19 17:55:05.336  1015  3485 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-19 17:55:05.336  1015  3485 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
08-19 17:55:05.336  2704  2760 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hid.HidService
08-19 17:55:05.336  2704  2760 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
,08-19 17:55:05.336  2704  2760 W BluetoothAdapterService: Not skipping com.android.bluetooth.hid.HidService
08-19 17:55:05.336  1015  1027 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,08-19 17:55:05.336  1015  1027 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hid.HidService; callingUser = 0; userId(target) = 0
,08-19 17:55:05.336  1015  1027 W ActivityManager: userId = 0, bbcId = -10000
08-19 17:55:05.336  1015  1027 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-19 17:55:05.336  1015  1027 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-19 17:55:05.336  2704  2760 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hdp.HealthService
08-19 17:55:05.336  2704  2760 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
,08-19 17:55:05.336  2704  2760 W BluetoothAdapterService: Not skipping com.android.bluetooth.hdp.HealthService
,08-19 17:55:05.336  1015  1474 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-19 17:55:05.336  1015  1474 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hdp.HealthService; callingUser = 0; userId(target) = 0
,08-19 17:55:05.336  1015  1474 W ActivityManager: userId = 0, bbcId = -10000
08-19 17:55:05.336  1015  1474 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-19 17:55:05.336  1015  1474 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-19 17:55:05.336  2704  2760 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.pan.PanService
08-19 17:55:05.336  2704  2760 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.pan.PanService
,08-19 17:55:05.336  2704  2760 W BluetoothAdapterService: Not skipping com.android.bluetooth.pan.PanService
,08-19 17:55:05.346  1015  1482 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-19 17:55:05.346  1015  1482 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pan.PanService; callingUser = 0; userId(target) = 0
,08-19 17:55:05.346  1015  1482 W ActivityManager: userId = 0, bbcId = -10000
08-19 17:55:05.346  1015  1482 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-19 17:55:05.346  1015  1482 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-19 17:55:05.346  2704  2760 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.map.BluetoothMapService
08-19 17:55:05.346  2704  2760 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
,08-19 17:55:05.346  2704  2760 W BluetoothAdapterService: Not skipping com.android.bluetooth.map.BluetoothMapService
,08-19 17:55:05.346  1015  3492 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-19 17:55:05.346  1015  3492 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.map.BluetoothMapService; callingUser = 0; userId(target) = 0
,08-19 17:55:05.346  1015  3492 W ActivityManager: userId = 0, bbcId = -10000
08-19 17:55:05.346  1015  3492 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-19 17:55:05.346  1015  3492 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-19 17:55:05.346  2704  2760 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.broadcom.bt.service.sap.SapService
08-19 17:55:05.346  2704  2760 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
,08-19 17:55:05.346  2704  2760 W BluetoothAdapterService: Not skipping com.broadcom.bt.service.sap.SapService
08-19 17:55:05.346  1015  1301 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-19 17:55:05.346  1015  1301 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.broadcom.bt.service.sap.SapService; callingUser = 0; userId(target) = 0
,08-19 17:55:05.346  1015  1301 W ActivityManager: userId = 0, bbcId = -10000
,08-19 17:55:05.346  1015  1301 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-19 17:55:05.346  1015  1301 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-19 17:55:05.346  2704  2760 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hfpclient.HeadsetClientService
08-19 17:55:05.346  2704  2760 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfpclient.HeadsetClientService
08-19 17:55:05.346  2704  2760 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.hfpclient.HeadsetClientService
08-19 17:55:05.346  2704  2760 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.a2dp.A2dpSinkService
08-19 17:55:05.346  2704  2760 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpSinkService
,08-19 17:55:05.346  2704  2760 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.a2dp.A2dpSinkService
08-19 17:55:05.356  2704  2760 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.sapclient.SapClientService
08-19 17:55:05.356  2704  2760 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.sapclient.SapClientService
,08-19 17:55:05.356  2704  2760 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.sapclient.SapClientService
08-19 17:55:05.356  2704  2760 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hid.HidDevService
08-19 17:55:05.356  2704  2760 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidDevService
,08-19 17:55:05.356  2704  2760 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.hid.HidDevService
08-19 17:55:05.356  2704  2760 D BluetoothAdapterState: Stopping profile services that were post enabled
08-19 17:55:05.356  2704  2704 E BluetoothAdapterService(862671449): processProfileServiceStateChanged() serviceName=com.android.bluetooth.gatt.GattService, state=10, doUpdate=false
,08-19 17:55:05.356  2704  2704 D HeadsetService: Received stop request...Stopping profile...
08-19 17:55:05.356  2704  2704 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@336b5259
,08-19 17:55:05.356  1015  1015 D AudioService: onServiceDisconnected: Bluetooth profile: 1
,08-19 17:55:05.356  2704  2704 D A2dpService: Received stop request...Stopping profile...
,08-19 17:55:05.356  2704  2772 D A2dpStateMachine: Exit Disconnected: -1
,08-19 17:55:05.356  1304  1304 D HeadsetProfile: Bluetooth service disconnected
,08-19 17:55:05.366  2704  2704 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@336b5259
,08-19 17:55:05.366  1015  1015 D BluetoothA2dp: Proxy object disconnected
,08-19 17:55:05.366  2704  2704 D HidService: Received stop request...Stopping profile...
08-19 17:55:05.366  2704  2704 D HidService: Stopping Bluetooth HidService
08-19 17:55:05.366  2704  2704 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
08-19 17:55:05.366  2704  2704 W bt-btif : cleanup: HH disabling or disabled already, status = 0
08-19 17:55:05.366  2704  2704 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
08-19 17:55:05.366  2704  2704 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@336b5259
08-19 17:55:05.366  1015  1015 D AudioService: onServiceDisconnected: Bluetooth profile: 2
,08-19 17:55:05.366  2704  2704 D HealthService: Received stop request...Stopping profile...
,08-19 17:55:05.366  2704  2704 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@336b5259
08-19 17:55:05.366  1304  1304 D BluetoothA2dp: Proxy object disconnected
08-19 17:55:05.366  1304  1304 D A2dpProfile: Bluetooth service disconnected
08-19 17:55:05.366  1304  1304 D BluetoothInputDevice: Proxy object disconnected
08-19 17:55:05.366  1304  1304 D HidProfile: Bluetooth service disconnected
,08-19 17:55:05.366  2704  2704 D PanService: Received stop request...Stopping profile...
08-19 17:55:05.366  2704  2704 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@336b5259
08-19 17:55:05.366  1015  1015 D BluetoothPan: BluetoothPAN Proxy object disconnected
,08-19 17:55:05.366  1304  1304 D BluetoothPan: BluetoothPAN Proxy object disconnected
08-19 17:55:05.366  1304  1304 D PanProfile: Bluetooth service disconnected
,08-19 17:55:05.366  2704  2704 D BluetoothMapService: Received stop request...Stopping profile...
,08-19 17:55:05.376  2704  2704 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@336b5259
,08-19 17:55:05.376  2704  2704 D SapService: Received stop request...Stopping profile...
,08-19 17:55:05.376  2704  2704 D SapService: Stopping Bluetooth SapService
08-19 17:55:05.376  2704  2704 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@336b5259
08-19 17:55:05.376  1304  1304 D BluetoothMap: Proxy object disconnected
08-19 17:55:05.376  1304  1304 D MapProfile: Bluetooth service disconnected
,08-19 17:55:05.376  2704  2704 E BluetoothAdapterService(862671449): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hfp.HeadsetService, state=10, doUpdate=true
08-19 17:55:05.376  2704  2704 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
08-19 17:55:05.376  2704  2704 D BluetoothAdapterService: Profile still running: com.android.bluetooth.hid.HidService
08-19 17:55:05.376  1304  1304 D Bluetoothsap: BluetoothSAP Proxy object disconnected
08-19 17:55:05.376  1304  1304 D SapProfile: Bluetooth service disconnected
,08-19 17:55:05.376  2704  2704 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
08-19 17:55:05.376  2704  2704 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
,08-19 17:55:05.376  2704  2704 E BluetoothAdapterService(862671449): processProfileServiceStateChanged() serviceName=com.android.bluetooth.a2dp.A2dpService, state=10, doUpdate=true
08-19 17:55:05.376  2704  2704 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
08-19 17:55:05.376  2704  2704 D BluetoothAdapterService: Profile still running: com.android.bluetooth.hid.HidService
08-19 17:55:05.376  2704  2704 D BluetoothA2dp: Proxy object disconnected
08-19 17:55:05.376  2704  2704 D BluetoothAdapterService: Bluetooth A2dp source service disconnected
08-19 17:55:05.376  2704  2773 I GKI_LINUX: gki_task task_id=2 [A2DP-MEDIA] terminating
,08-19 17:55:05.376  2704  2704 I GKI_LINUX: GKI_exit_task 2 done
08-19 17:55:05.376  2704  2704 I GKI_LINUX: GKI_shutdown(): task [A2DP-MEDIA] terminated
08-19 17:55:05.386  2704  2704 E BluetoothAdapterService(862671449): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hid.HidService, state=10, doUpdate=true
08-19 17:55:05.386  2704  2704 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
08-19 17:55:05.386  2704  2704 D BluetoothAdapterService: Profile still running: com.android.bluetooth.map.BluetoothMapService
,08-19 17:55:05.386  2704  2704 E BluetoothAdapterService(862671449): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hdp.HealthService, state=10, doUpdate=true
08-19 17:55:05.386  2704  2704 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
08-19 17:55:05.386  2704  2704 D BluetoothAdapterService: Profile still running: com.android.bluetooth.map.BluetoothMapService
,08-19 17:55:05.386  2704  2704 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
08-19 17:55:05.386  2704  2704 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
08-19 17:55:05.386  2704  2704 E BluetoothAdapterService(862671449): processProfileServiceStateChanged() serviceName=com.android.bluetooth.pan.PanService, state=10, doUpdate=true
08-19 17:55:05.386  2704  2704 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
08-19 17:55:05.386  2704  2704 D BluetoothAdapterService: Profile still running: com.android.bluetooth.map.BluetoothMapService
08-19 17:55:05.386  2704  2704 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
08-19 17:55:05.386  2704  2704 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
,08-19 17:55:05.386  2704  2704 E BluetoothAdapterService(862671449): processProfileServiceStateChanged() serviceName=com.android.bluetooth.map.BluetoothMapService, state=10, doUpdate=true
08-19 17:55:05.386  2704  2704 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
08-19 17:55:05.386  2704  2704 D BluetoothAdapterService: Profile still running: com.broadcom.bt.service.sap.SapService
,08-19 17:55:05.386  2704  2704 E BluetoothAdapterService(862671449): processProfileServiceStateChanged() serviceName=com.broadcom.bt.service.sap.SapService, state=10, doUpdate=true
08-19 17:55:05.386  2704  2704 W BluetoothSAPServiceJni: ## WARNING : cleanupNative(L251): Cleaning up Bluetooth SAP Interface...##
08-19 17:55:05.386  2704  2704 W BluetoothSAPServiceJni: ## WARNING : cleanupNative(L257): Cleaning up Bluetooth SAP callback object##
,08-19 17:55:05.386  2704  2760 D BluetoothAdapterState: CURRENT_STATE=PENDING,MSG = STOPPED, isTurningOn=false, isTurningOff=true
08-19 17:55:05.386  2704  2760 D BluetoothAdapterProperties: Setting state to 10
08-19 17:55:05.386  2704  2760 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 10
08-19 17:55:05.386  2704  2760 D BluetoothAdapterService: Bluetooth PBAP supproted is true
08-19 17:55:05.386  2704  2760 D BluetoothAdapterService: updateAdapterState state is 10
,08-19 17:55:05.386  2704  2760 D BluetoothAdapterService: Autoconnection is available 
08-19 17:55:05.386  2704  2760 D BluetoothAdapterService: updateAdapterState prevState = 13newState = 10
08-19 17:55:05.386  2704  2760 I BluetoothAdapterState: Entering OffState
,08-19 17:55:05.386  1304  1315 D Bluetoothsap: onBluetoothStateChange: up=false
08-19 17:55:05.386  1304  1315 D Bluetoothsap: Unbinding service...
,08-19 17:55:05.386  1304  6303 D BluetoothPbap: onBluetoothStateChange: up=false
,08-19 17:55:05.386  1172  1919 D BluetoothAdapter: onBluetoothStateChange: up=false
08-19 17:55:05.396  1172  1919 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,08-19 17:55:05.396  1979  1988 D BluetoothAdapter: onBluetoothStateChange: up=false
,08-19 17:55:05.396  1979  1988 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,08-19 17:55:05.396  6220  6233 D BluetoothAdapter: onBluetoothStateChange: up=false
08-19 17:55:05.396  6220  6233 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
08-19 17:55:05.396  6220  6233 D BluetoothLeAdvertiser: stop All Advertising :: standalone boolean value is = false
08-19 17:55:05.396  6220  6233 D BluetoothLeAdvertiser: Exit stop advertising
,08-19 17:55:05.396  6220  6233 D BluetoothLeScanner: stopAllScan standalone boolean is value is = false
08-19 17:55:05.396  6220  6233 D BluetoothLeScanner: Exiting stopAllScan
,08-19 17:55:05.396  2704  2721 D BluetoothA2dp: onBluetoothStateChange: up=false
,08-19 17:55:05.396  1015  1044 D BluetoothAdapter: onBluetoothStateChange: up=false
08-19 17:55:05.396  1015  1044 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
08-19 17:55:05.396  1015  1044 D BluetoothA2dp: onBluetoothStateChange: up=false
,08-19 17:55:05.396  1412  1438 D BluetoothAdapter: onBluetoothStateChange: up=false
08-19 17:55:05.396  1412  1438 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,08-19 17:55:05.396  1304  1315 D BluetoothAdapter: onBluetoothStateChange: up=false
08-19 17:55:05.396  1304  1315 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,08-19 17:55:05.396  1304  1325 D BluetoothMap: onBluetoothStateChange: up=false
,08-19 17:55:05.396  1447  2437 D BluetoothAdapter: onBluetoothStateChange: up=false
08-19 17:55:05.396  1447  2437 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,08-19 17:55:05.396  2704  2947 D BluetoothAdapter: onBluetoothStateChange: up=false
08-19 17:55:05.396  2704  2947 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
08-19 17:55:05.396  1304  1315 D BluetoothInputDevice: onBluetoothStateChange: up=false
,08-19 17:55:05.406  1427  1454 D BluetoothAdapter: onBluetoothStateChange: up=false
,08-19 17:55:05.406  1427  1454 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
08-19 17:55:05.406  1304  6303 D BluetoothA2dp: onBluetoothStateChange: up=false
,08-19 17:55:05.406  1015  1044 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 9 receivers.
,08-19 17:55:05.406  1015  1044 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 0 receivers.
,08-19 17:55:05.416  1015  1015 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
08-19 17:55:05.416  1015  1015 I InputMethodManagerService: [BT Setting State] State =10
08-19 17:55:05.416  1015  1015 I InputMethodManagerService: [BT Setting on -> off] mBTKeyboardCount =0, KEYBOARD_BT(0)
,08-19 17:55:05.416  1172  1172 D BluetoothAdapter: 728109433: getState() :  mService = null. Returning STATE_OFF
08-19 17:55:05.416  1172  1172 D BluetoothTile:  onBluetoothPairedDevicesChanged:
,08-19 17:55:05.416  1172  1745 D BluetoothAdapter: 728109433: getState() :  mService = null. Returning STATE_OFF
,08-19 17:55:05.416  1172  1172 D BluetoothTile: onReceive : android.bluetooth.adapter.action.STATE_CHANGED
,08-19 17:55:05.416  1172  1172 D BluetoothTile:  getBluetoothState : 10
,08-19 17:55:05.426  1172  1745 D BluetoothAdapter: 728109433: getState() :  mService = null. Returning STATE_OFF
08-19 17:55:05.426  1172  1172 D BluetoothAdapter: 728109433: getState() :  mService = null. Returning STATE_OFF
,08-19 17:55:05.426  1172  1172 D BluetoothAdapter: 728109433: getState() :  mService = null. Returning STATE_OFF
,08-19 17:55:05.426  1823  1823 I SamsungIME: STATE_CHANGED = 10, KEYBOARD_BT(0), mBTKeyboardCount =0
08-19 17:55:05.426  1979  2176 D BluetoothAdapter: 777567744: getState() :  mService = null. Returning STATE_OFF
08-19 17:55:05.426  1015  3485 D StatusBarManagerService: setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
,08-19 17:55:05.426  1979  2176 D BluetoothAdapter: 777567744: getState() :  mService = null. Returning STATE_OFF
08-19 17:55:05.426  1015  1133 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=false
,08-19 17:55:05.426  1015  1301 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
08-19 17:55:05.426  1015  1301 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.nearby.discovery.service.DiscoveryService; callingUser = 0; userId(target) = 0
08-19 17:55:05.426  1172  1172 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 )
,08-19 17:55:05.426  1015  1301 W ActivityManager: userId = 0, bbcId = -10000
08-19 17:55:05.426  1015  1301 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-19 17:55:05.426  1015  1301 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
08-19 17:55:05.426  1304  1304 V BluetoothEventManager: Received android.bluetooth.adapter.action.STATE_CHANGED
,08-19 17:55:05.426  6220  6220 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-19 17:55:05.426  6220  6220 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-19 17:55:05.436  2704  2763 I GKI_LINUX: gki_task task_id=1 [BTIF] terminating
,08-19 17:55:05.436  2704  2704 I GKI_LINUX: GKI_exit_task 1 done
08-19 17:55:05.436  2704  2704 I GKI_LINUX: GKI_shutdown(): task [BTIF] terminated
,08-19 17:55:05.436  2704  2704 I BluetoothServiceJni: cleanupNative: return from cleanup
,08-19 17:55:05.436  2704  2704 I art     : System.exit called, status: 0
08-19 17:55:05.436  2704  2704 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,08-19 17:55:05.456  6323  6323 D StrictMode: StrictMode policy violation; ~duration=206 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
08-19 17:55:05.456  6323  6323 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
08-19 17:55:05.456  6323  6323 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
08-19 17:55:05.456  6323  6323 D StrictMode: 	at java.io.File.doAccess(File.java:283)
08-19 17:55:05.456  6323  6323 D StrictMode: 	at java.io.File.exists(File.java:363)
08-19 17:55:05.456  6323  6323 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:1366)
08-19 17:55:05.456  6323  6323 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:1389)
08-19 17:55:05.456  6323  6323 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:1331)
08-19 17:55:05.456  6323  6323 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:190)
08-19 17:55:05.456  6323  6323 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:252)
08-19 17:55:05.456  6323  6323 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8690)
08-19 17:55:05.456  6323  6323 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-19 17:55:05.456  6323  6323 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
08-19 17:55:05.456  6323  6323 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-19 17:55:05.456  6323  6323 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-19 17:55:05.456  6323  6323 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
08-19 17:55:05.456  6323  6323 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
08-19 17:55:05.456  6323  6323 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
08-19 17:55:05.456  6323  6323 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
08-19 17:55:05.456  6323  6323 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
08-19 17:55:05.456  6323  6323 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
08-19 17:55:05.456  6323  6323 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-19 17:55:05.456  6323  6323 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
08-19 17:55:05.456  6323  6323 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-19 17:55:05.456  6323  6323 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-19 17:55:05.456  6323  6323 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-19 17:55:05.456  6323  6323 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-19 17:55:05.456  6323  6323 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
08-19 17:55:05.456  6323  6323 D StrictMode: StrictMode policy violation; ~duration=206 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
08-19 17:55:05.456  6323  6323 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
08-19 17:55:05.456  6323  6323 D StrictMode: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182)
08-19 17:55:05.456  6323  6323 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:442)
08-19 17:55:05.456  6323  6323 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
08-19 17:55:05.456  6323  6323 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:1332)
08-19 17:55:05.456  6323  6323 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:190)
08-19 17:55:05.456  6323  6323 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:252)
08-19 17:55:05.456  6323  6323 D StrictMode: 	at com.google.android.app,s.gmm.map.m.q.a(PG:8690)
08-19 17:55:05.456  6323  6323 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-19 17:55:05.456  6323  6323 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
08-19 17:55:05.456  6323  6323 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-19 17:55:05.456  6323  6323 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-19 17:55:05.456  6323  6323 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
08-19 17:55:05.456  6323  6323 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
08-19 17:55:05.456  6323  6323 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
08-19 17:55:05.456  6323  6323 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
08-19 17:55:05.456  6323  6323 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
08-19 17:55:05.456  6323  6323 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
08-19 17:55:05.456  6323  6323 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-19 17:55:05.456  6323  6323 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
08-19 17:55:05.456  6323  6323 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-19 17:55:05.456  6323  6323 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-19 17:55:05.456  6323  6323 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-19 17:55:05.456  6323  6323 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-19 17:55:05.456  6323  6323 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
08-19 17:55:05.456  6323  6323 D StrictMode: StrictMode policy violation; ~duration=205 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
08-19 17:55:05.456  6323  6323 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
08-19 17:55:05.456  6323  6323 D StrictMode: 	at libcore.io.BlockGuardOs.fstat(BlockGuardOs.java:132)
08-19 17:55:05.456  6323  6323 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:445)
08-19 17:55:05.456  6323  6323 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
08-19 17:55:05.456  6323  6323 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:1332)
08-19 17:55:05.456  6323  6323 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:190)
08-19 17:55:05.456  6323  6323 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:252)
08-19 17:55:05.456  6323  6323 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8690)
08-19 17:55:05.456  6323  6323 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-19 17:55:05.456  6323  6323 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
08-19 17:55:05.456  6323  6323 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-19 17:55:05.456  6323  6323 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-19 17:55:05.456  6323  6323 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
08-19 17:55:05.456  6323  6323 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
08-19 17:55:05.456  6323  6323 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
08-19 17:55:05.456  6323  6323 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
08-19 17:55:05.456  6323  6323 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
08-19 17:55:05.456  6323  6323 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
08-19 17:55:05.456  6323  6323 D StrictMode: 	at ,android.os.Handler.dispatchMessage(Handler.java:102)
08-19 17:55:05.456  6323  6323 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
08-19 17:55:05.456  6323  6323 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-19 17:55:05.456  6323  6323 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-19 17:55:05.456  6323  6323 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-19 17:55:05.456  6323  6323 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-19 17:55:05.456  6323  6323 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
08-19 17:55:05.456  6323  6323 D StrictMode: StrictMode policy violation; ~duration=204 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
08-19 17:55:05.456  6323  6323 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
08-19 17:55:05.456  6323  6323 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
08-19 17:55:05.456  6323  6323 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:472)
08-19 17:55:05.456  6323  6323 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
08-19 17:55:05.456  6323  6323 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
08-19 17:55:05.456  6323  6323 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
08-19 17:55:05.456  6323  6323 D StrictMode: 	at com.google.q.k.d(PG:1187)
08-19 17:55:05.456  6323  6323 D StrictMode: 	at com.google.q.k.a(PG:2107)
08-19 17:55:05.456  6323  6323 D StrictMode: 	at com.google.v.a.a.dq.<init>(PG:23)
08-19 17:55:05.456  6323  6323 D StrictMode: 	at com.google.v.a.a.dq.a(PG:405)
08-19 17:55:05.456  6323  6323 D StrictMode: 	at com.google.q.v.a(PG:1161)
08-19 17:55:05.456  6323  6323 D StrictMode: 	at com.google.q.y.a(PG:2188)
08-19 17:55:05.456  6323  6323 D StrictMode: 	at com.google.q.e.b(PG:170)
08-19 17:55:05.456  6323  6323 D StrictMode: 	at com.google.q.e.b(PG:15188)
08-19 17:55:05.456  6323  6323 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:253)
08-19 17:55:05.456  6323  6323 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8690)
08-19 17:55:05.456  6323  6323 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-19 17:55:05.456  6323  6323 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
08-19 17:55:05.456  6323  6323 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-19 17:55:05.456  6323  6323 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-19 17:55:05.456  6323  6323 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
08-19 17:55:05.456  6323  6323 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
08-19 17:55:05.456  6323  6323 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
08-19 17:55:05.456  6323  6323 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
08-19 17:55:05.456  6323  6323 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
08-19 17:55:05.456  6323  6323 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
08-19 17:55:05.456  6323  6323 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-19 17:55:05.456  6323  6323 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
08-19 17:55:05.456  6323  6323 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-19 17:55:05.456  6323  6323 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-19 17:55:05.456  6323  6323 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-19 17:55:05.456  6323  6323 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-19 17:55:05.456  6323  6323 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
08-19 17:55:05.456  6323  6323 D StrictMode: StrictMode policy violation; ~duration=201 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
08-19 17:55:05.456  6323  6323 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
08-19 17:55:05.456  6323  6323 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
08-19 17:55:05.456  6323  6323 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:472)
08-19 17:55:05.456  6323  6323 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
08-19 17:55:05.456  6323  6323 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
08-19 17:55:05.456  6323  6323 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
08-19 17:55:05.456  6323  6323 D StrictMode: 	at com.google.q.k.d(PG:1187)
08-19 17:55:05.456  6323  6323 D StrictMode: 	at com.google.q.k.c(PG:18147)
08-19 17:55:05.456  6323  6323 D StrictMode: 	at com.google.q.k.d(PG:583)
08-19 17:55:05.456  6323  6323 D StrictMode: 	at com.google.v.a.a.dq.<init>(PG:40)
08-19 17:55:05.456  6323  6323 D StrictMode: 	at com.google.v.a.a.dq.a(PG:405)
08-19 17:55:05.456  6323  6323 D StrictMode: 	at com.google.q.v.a(PG:1161)
08-19 17:55:05.456  6323  6323 D StrictMode: 	at com.google.q.y.a(PG:2188)
08-19 17:55:05.456  6323  6323 D StrictMode: 	at com.google.q.e.b(PG:170)
08-19 17:55:05.456  6323  6323 D StrictMode: 	at com.google.q.e.b(PG:15188)
08-19 17:55:05.456  6323  6323 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:253)
08-19 17:55:05.456  6323  6323 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8690)
08-19 17:55:05.456  6323  6323 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-19 17:55:05.456  6323  6323 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
08-19 17:55:05.456  6323  6323 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-19 17:55:05.456  6323  6323 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-19 17:55:05.456  6323  6323 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
08-19 17:55:05.456  6323  6323 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
08-19 17:55:05.456  6323  6323 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
08-19 17:55:05.456  6323  6323 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
08-19 17:55:05.456  6323  6323 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
08-19 17:55:05.456  6323  6323 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
08-19 17:55:05.456  6323  6323 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-19 17:55:05.456  6323  6323 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
08-19 17:55:05.456  6323  6323 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-19 17:55:05.456  6323  6323 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-19 17:55:05.456  6323  6323 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-19 17:55:05.456  6323  6323 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-19 17:55:05.456  6323  6323 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
08-19 17:55:05.456  6323  6323 D StrictMode: StrictMode policy violation; ~duration=181 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
08-19 17:55:05.456  6323  6323 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
08-19 17:55:05.456  6323  6323 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
08-19 17:55:05.456  6323  6323 D StrictMode: 	at java.io.File.doAccess(File.java:283)
08-19 17:55:05.456  6323  6323 D StrictMode: 	at java.io.File.exists(File.java:363)
08-19 17:55:05.456  6323  6323 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:1366)
08-19 17:55:05.456  6323  6323 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:1389)
08-19 17:55:05.456  6323  6323 D StrictMode: 	at android.app.ContextImpl.getFileStreamPath(ContextImpl.java:1497)
08-19 17:55:05.456  6323  6323 D StrictMode: 	at android.content.ContextWrapper.getFileStreamPath(ContextWrapper.java:206)
08-19 17:55:05.456  6323  6323 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8698)
08-19 17:55:05.456  6323  6323 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-19 17:55:05.456  6323  6323 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
08-19 17:55:05.456  6323  6323 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-19 17:55:05.456  6323  6323 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-19 17:55:05.456  6323  6323 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
08-19 17:55:05.456  6323  6323 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
08-19 17:55:05.456  6323  6323 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
08-19 17:55:05.456  6323  6323 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
08-19 17:55:05.456  6323  6323 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
08-19 17:55:05.456  6323  6323 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
08-19 17:55:05.456  6323  6323 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-19 17:55:05.456  6323  6323 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
08-19 17:55:05.456  6323  6323 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-19 17:55:05.456  6323  6323 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-19 17:55:05.456  6323  6323 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-19 17:55:05.456  6323  6323 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-19 17:55:05.456  6323  6323 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
08-19 17:55:05.456  6323  6323 D StrictMode: StrictMode policy violation; ~duration=181 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
08-19 17:55:05.456  6323  6323 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
08-19 17:55:05.456  6323  6323 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
08-19 17:55:05.456  6323  6323 D StrictMode: 	at java.io.File.doAccess(File.java:283)
08-19 17:55:05.456  6323  6323 D StrictMode: 	at java.io.File.exists(File.java:363)
08-19 17:55:05.456  6323  6323 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8700)
08-19 17:55:05.456  6323  6323 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-19 17:55:05.456  6323  6323 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
08-19 17:55:05.456  6323  6323 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-19 17:55:05.456  6323  6323 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-19 17:55:05.456  6323  6323 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
08-19 17:55:05.456  6323  6323 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
08-19 17:55:05.456  6323  6323 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
08-19 17:55:05.456  6323  6323 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
08-19 17:55:05.456  6323  6323 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
08-19 17:55:05.456  6323  6323 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
08-19 17:55:05.456  6323  6323 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-19 17:55:05.456  6323  6323 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
08-19 17:55:05.456  6323  6323 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-19 17:55:05.456  6323  6323 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-19 17:55:05.456  6323  6323 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-19 17:55:05.456  6323  6323 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-19 17:55:05.456  6323  6323 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
08-19 17:55:05.456  6323  6323 D StrictMode: StrictMode policy violation; ~duration=180 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
08-19 17:55:05.456  6323  6323 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
08-19 17:55:05.456  6323  6323 D StrictMode: 	at libcore.io.BlockGuardOs.stat(BlockGuardOs.java:292)
08-19 17:55:05.456  6323  6323 D StrictMode: 	at java.io.File.lastModified(File.java:571)
08-19 17:55:05.456  6323  6323 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8701)
08-19 17:55:05.456  6323  6323 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-19 17:55:05.456  6323  6323 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
08-19 17:55:05.456  6323  6323 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-19 17:55:05.456  6323  6323 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-19 17:55:05.456  6323  6323 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
08-19 17:55:05.456  6323  6323 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
08-19 17:55:05.456  6323  6323 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
08-19 17:55:05.456  6323  6323 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
08-19 17:55:05.456  6323  6323 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
08-19 17:55:05.456  6323  6323 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
08-19 17:55:05.456  6323  6323 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-19 17:55:05.456  6323  6323 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
08-19 17:55:05.456  6323  6323 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-19 17:55:05.456  6323  6323 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-19 17:55:05.456  6323  6323 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-19 17:55:05.456  6323  6323 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-19 17:55:05.456  6323  6323 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
08-19 17:55:05.466  1015  3485 I ActivityManager: Killing 5809:com.google.android.apps.docs/u0a87 (adj 15): empty #21
08-19 17:55:05.466  1979  1979 D EasyUnlockReceiver: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.easyunlock.authorization.BluetoothStateChangeReceiver (has extras) }.
08-19 17:55:05.466  1979  1979 D BtServices: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.proximity.BluetoothServicesAdapterStateChangeReceiver (has extras) }.
08-19 17:55:05.476  1304  1304 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.p2p.CONNECTION_STATE_CHANGE
08-19 17:55:05.476  1304  1304 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
08-19 17:55:05.476  1304  1304 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
08-19 17:55:05.476  1304  1304 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
08-19 17:55:05.476  1304  1304 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
08-19 17:55:05.476  1304  1304 I NearbySettings: MountReceiver.onReceive - Set preference state off
08-19 17:55:05.476  1015  1301 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.app.FileShareClient, hostingType: broadcast
08-19 17:55:05.486  1304  2187 V NearbySettings: MountReceiver.mPrefHandler - 7002
08-19 17:55:05.486  1015  1301 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-19 17:55:05.486  1015  1301 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-19 17:55:05.486  1015  1301 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-19 17:55:05.486  1015  1301 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-19 17:55:05.496  1015  1301 I ActivityManager: Start proc com.samsung.android.app.FileShareClient for broadcast com.samsung.android.app.FileShareClient/.ClientBroadcastReceiver: pid=6362 uid=10064 gids={50064, 9997, 3003, 1028, 1015} abi=armeabi-v7a
08-19 17:55:05.496  6362  6362 E Zygote  : MountEmulatedStorage()
08-19 17:55:05.496  6362  6362 E Zygote  : v2
08-19 17:55:05.496  6362  6362 I libpersona: KNOX_SDCARD checking this for 10064
08-19 17:55:05.496  6362  6362 I libpersona: KNOX_SDCARD not a persona
08-19 17:55:05.496  6362  6362 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
08-19 17:55:05.506  6362  6362 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
08-19 17:55:05.506  6362  6362 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
08-19 17:55:05.516  6323  6349 W com.google.a.a.b.d.a: Application name is not set. Call Builder#setApplicationName.
08-19 17:55:05.526  1015  1301 I ActivityManager: Process com.android.bluetooth (pid 2704)(adj 0) has died(39,722)
,08-19 17:55:05.536  6362  6362 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-19 17:55:05.536  6362  6362 D ActivityThread: Added TimaKeyStore provider
,08-19 17:55:05.546  1015  3494 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-19 17:55:05.546  1015  3494 W ActivityManager: userId = 0, bbcId = -10000
08-19 17:55:05.546  1015  3494 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-19 17:55:05.546  1015  3494 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.apps.maps, destAppInfo.processName = com.google.android.gms
,08-19 17:55:05.556  6362  6362 W ResourcesManager: Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
,08-19 17:55:05.566  6362  6362 D FileShare-Client: ClientBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,08-19 17:55:05.576  6362  6362 D FileShare-Client: ClientBroadcastReceiver.onReceive - disconnected
,08-19 17:55:05.596  6362  6362 D FileShare-Client: Outbound.stopDelayTimer - 
,08-19 17:55:05.596  1015  1028 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.app.FileShareServer, hostingType: broadcast
,08-19 17:55:05.606  1015  1028 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-19 17:55:05.606  1015  1028 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-19 17:55:05.606  1015  1028 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-19 17:55:05.606  1015  1028 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-19 17:55:05.616  1015  1028 I ActivityManager: Start proc com.samsung.android.app.FileShareServer for broadcast com.samsung.android.app.FileShareServer/.ServerBroadcastReceiver: pid=6379 uid=10065 gids={50065, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,08-19 17:55:05.616  6379  6379 E Zygote  : MountEmulatedStorage()
,08-19 17:55:05.616  6379  6379 E Zygote  : v2
08-19 17:55:05.616  6379  6379 I libpersona: KNOX_SDCARD checking this for 10065
08-19 17:55:05.616  6379  6379 I libpersona: KNOX_SDCARD not a persona
,08-19 17:55:05.616  6379  6379 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
08-19 17:55:05.616  1015  1028 I ActivityManager: Killing 5820:com.samsung.android.bbc.bbcagent/1000 (adj 15): empty #21
,08-19 17:55:05.616  6379  6379 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-19 17:55:05.626  6379  6379 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-19 17:55:05.636  6379  6379 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-19 17:55:05.636  6379  6379 D ActivityThread: Added TimaKeyStore provider
,08-19 17:55:05.656  6379  6379 D FileShare-Server: ServerBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,08-19 17:55:05.666  1015  3485 I ActivityManager: Killing 5844:com.sec.android.widgetapp.tapandpay/u0a152 (adj 15): empty #21
,08-19 17:55:05.676  1015  1301 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
08-19 17:55:05.676  1015  1301 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,08-19 17:55:05.676  1015  1301 W ActivityManager: userId = 0, bbcId = -10000
08-19 17:55:05.676  1015  1301 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-19 17:55:05.676  1015  1301 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,08-19 17:55:05.676  1619  1619 I Hs20UtilService: Starting #4
,08-19 17:55:05.676  1619  1650 I Hs20UtilService: Message received 5007
,08-19 17:55:05.676  1304  1304 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,08-19 17:55:05.676  1304  1304 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
,08-19 17:55:05.676  1304  1304 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,08-19 17:55:05.676  1304  1304 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
08-19 17:55:05.676  1304  1304 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
08-19 17:55:05.676  1304  1304 I NearbySettings: MountReceiver.onReceive - Set preference state off
08-19 17:55:05.676  1304  2187 V NearbySettings: MountReceiver.mPrefHandler - 7002
,08-19 17:55:05.686  1015  1133 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
,08-19 17:55:05.686  1015  1133 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,08-19 17:55:05.686  1015  1133 W ActivityManager: userId = 0, bbcId = -10000
08-19 17:55:05.686  1015  1133 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-19 17:55:05.686  1015  1133 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,08-19 17:55:05.686  1619  1619 I Hs20UtilService: Starting #5
08-19 17:55:05.686  1619  1650 I Hs20UtilService: Message received 5011
,08-19 17:55:05.686  1015  3494 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.securitylogagent, hostingType: broadcast
,08-19 17:55:05.686  1015  3494 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-19 17:55:05.686  1015  3494 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-19 17:55:05.686  1015  3494 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-19 17:55:05.686  1015  3494 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-19 17:55:05.706  6394  6394 E Zygote  : MountEmulatedStorage()
,08-19 17:55:05.706  6394  6394 E Zygote  : v2
08-19 17:55:05.706  6394  6394 I libpersona: KNOX_SDCARD checking this for 1000
08-19 17:55:05.706  6394  6394 I libpersona: KNOX_SDCARD not a persona
,08-19 17:55:05.706  6394  6394 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
08-19 17:55:05.706  1015  3494 I ActivityManager: Start proc com.samsung.android.securitylogagent for broadcast com.samsung.android.securitylogagent/.receivers.NetworkReceiver: pid=6394 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,08-19 17:55:05.706  6394  6394 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-19 17:55:05.706  6394  6394 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL,
,08-19 17:55:05.726  6394  6394 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-19 17:55:05.726  6394  6394 D ActivityThread: Added TimaKeyStore provider
,08-19 17:55:05.756  6394  6394 D SecurityLogAgent: KnoxConfiguration : Current State = 1
,08-19 17:55:05.756  6394  6394 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
,08-19 17:55:05.756  6394  6394 D SecurityLogAgent: StateMachine : Current State = 1
,08-19 17:55:05.766  6394  6394 D SecurityLogAgent: StateMachine : Changed Current State = 1
,08-19 17:55:05.766  1015  1470 I ActivityManager: Killing 5876:com.samsung.android.app.galaxyfinder/u0a29 (adj 15): empty #21
,08-19 17:55:05.776  1015  3494 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
,08-19 17:55:05.776  1015  3494 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
08-19 17:55:05.776  1015  3494 W ActivityManager: userId = 0, bbcId = -10000
08-19 17:55:05.776  1015  3494 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-19 17:55:05.776  1015  3494 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,08-19 17:55:05.776  1619  1619 I Hs20UtilService: Starting #6
,08-19 17:55:05.786  1619  1650 I Hs20UtilService: Message received 5011
,08-19 17:55:05.786  6394  6394 D SecurityLogAgent: KnoxConfiguration : Current State = 1
,08-19 17:55:05.786  6394  6394 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
08-19 17:55:05.786  6394  6394 D SecurityLogAgent: StateMachine : Current State = 1
08-19 17:55:05.786  6394  6394 D SecurityLogAgent: StateMachine : Changed Current State = 1
,08-19 17:55:05.796  1304  1304 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-19 17:55:05.796  1015  1133 D ActivityManager: startService callerProcessName:com.android.settings, calleePkgName: com.android.settings
,08-19 17:55:05.796  1015  1133 D ActivityManager: retrieveServiceLocked(): component = com.android.settings/com.android.settings.bluetooth.DockService; callingUser = 0; userId(target) = 0
,08-19 17:55:05.796  1015  1133 W ActivityManager: userId = 0, bbcId = -10000
,08-19 17:55:05.796  1015  1133 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-19 17:55:05.796  1015  1133 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.settings
,08-19 17:55:05.806  1304  1304 D DockEventReceiver: finishStartingService: stopping service
,08-19 17:55:05.806  1304  1304 D BluetoothNotiBroadcastReceiver: onReceive
,08-19 17:55:05.806  1172  1172 V BluetoothStatusReceiver: Received android.bluetooth.adapter.action.STATE_CHANGED
,08-19 17:55:05.806  1172  1172 D BluetoothStatusReceiver: AdapterStateChanged :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 10
,08-19 17:55:05.816  1015  1474 D ActivityManager: startProcessLocked calleePkgName: com.android.bluetooth, hostingType: broadcast
,08-19 17:55:05.816  1015  1474 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-19 17:55:05.816  1015  1474 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-19 17:55:05.816  1015  1474 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-19 17:55:05.816  1015  1474 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-19 17:55:05.826  6411  6411 E Zygote  : MountEmulatedStorage()
,08-19 17:55:05.826  6411  6411 E Zygote  : v2
08-19 17:55:05.826  6411  6411 I libpersona: KNOX_SDCARD checking this for 1002
08-19 17:55:05.826  6411  6411 I libpersona: KNOX_SDCARD not a persona
,08-19 17:55:05.826  6411  6411 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51,
08-19 17:55:05.826  1015  1474 I ActivityManager: Start proc com.android.bluetooth for broadcast com.android.bluetooth/.opp.BluetoothOppReceiver: pid=6411 uid=1002 gids={41002, 9997, 3003, 3002, 3001, 1028, 1015, 3005, 1016, 3008} abi=armeabi-v7a
,08-19 17:55:05.826  6411  6411 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051,
,08-19 17:55:05.836  1015  1042 D Tethering: interfaceRemoved wlan0
08-19 17:55:05.836  1015  1042 E Tethering: attempting to remove unknown iface (wlan0), ignoring
,08-19 17:55:05.836  6411  6411 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-19 17:55:05.856  6411  6411 D TimaKeyStoreProvider: TimaSignature is unavailable
08-19 17:55:05.856  6411  6411 D ActivityThread: Added TimaKeyStore provider
,08-19 17:55:05.866  6411  6411 W ResourcesManager: Asset path '/system/framework/javax.obex.jar' does not exist or contains no resources.
,08-19 17:55:05.866  6411  6411 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,08-19 17:55:05.896  6411  6411 I BluetoothA2dpSinkServiceJni: register_com_android_bluetooth_a2dp_sink
,08-19 17:55:05.926  6411  6411 D BtSettings.ProfileConfig: Adding GattService
,08-19 17:55:05.926  6411  6411 D BtSettings.ProfileConfig: Adding HeadsetService
08-19 17:55:05.926  6411  6411 D BtSettings.ProfileConfig: Adding A2dpService
,08-19 17:55:05.926  6411  6411 D BtSettings.ProfileConfig: Adding HidService
08-19 17:55:05.926  6411  6411 D BtSettings.ProfileConfig: Adding HealthService
08-19 17:55:05.926  6411  6411 D BtSettings.ProfileConfig: Adding PanService
,08-19 17:55:05.926  6411  6411 D BtSettings.ProfileConfig: Adding BluetoothMapService
08-19 17:55:05.926  6411  6411 D BtSettings.ProfileConfig: Adding SapService
08-19 17:55:05.926  6411  6411 D BtSettings.ProfileConfig: Adding HeadsetClientService
,08-19 17:55:05.926  6411  6411 D BtSettings.ProfileConfig: Adding A2dpSinkService
08-19 17:55:05.926  6411  6411 D BtSettings.ProfileConfig: Adding SapClientService
08-19 17:55:05.926  6411  6411 D BtSettings.ProfileConfig: Adding HidDevService
,08-19 17:55:05.926  6411  6411 I BtSettings.ProfileConfig: *********Initializing Bluetooth Profile Settings*******
,08-19 17:55:05.926  1015  1301 D SettingsProvider: name = bt_svcst_com.android.bluetooth.gatt.GattService
,08-19 17:55:05.926  1015  1301 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-19 17:55:05.926  1015  1301 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-19 17:55:05.926  1015  1301 D SettingsProvider: selectionArgs: false
08-19 17:55:05.926  1015  1301 D SettingsProvider: selectionArgs: 1002
08-19 17:55:05.926  1015  1301 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-19 17:55:05.926  1015  1301 D SettingsProvider: ret = -1
,08-19 17:55:05.926  1015  1482 D SettingsProvider: name = bt_svcst_com.android.bluetooth.hfp.HeadsetService
08-19 17:55:05.926  1015  1482 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
,08-19 17:55:05.926  1015  1482 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-19 17:55:05.926  1015  1482 D SettingsProvider: selectionArgs: false
08-19 17:55:05.926  1015  1482 D SettingsProvider: selectionArgs: 1002
08-19 17:55:05.926  1015  1482 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-19 17:55:05.926  1015  1482 D SettingsProvider: ret = -1
,08-19 17:55:05.926  1015  3485 D SettingsProvider: name = bt_svcst_com.android.bluetooth.a2dp.A2dpService
08-19 17:55:05.926  1015  3485 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-19 17:55:05.926  1015  3485 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-19 17:55:05.926  1015  3485 D SettingsProvider: selectionArgs: false
08-19 17:55:05.926  1015  3485 D SettingsProvider: selectionArgs: 1002
08-19 17:55:05.936  1015  3485 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-19 17:55:05.936  1015  3485 D SettingsProvider: ret = -1
08-19 17:55:05.936  1015  1475 D SettingsProvider: name = bt_svcst_com.android.bluetooth.hid.HidService
,08-19 17:55:05.936  1015  1475 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-19 17:55:05.936  1015  1475 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-19 17:55:05.936  1015  1475 D SettingsProvider: selectionArgs: false
08-19 17:55:05.936  1015  1475 D SettingsProvider: selectionArgs: 1002
08-19 17:55:05.936  1015  1475 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-19 17:55:05.936  1015  1475 D SettingsProvider: ret = -1
,08-19 17:55:05.936  1015  1446 D SettingsProvider: name = bt_svcst_com.android.bluetooth.hdp.HealthService
08-19 17:55:05.936  1015  1446 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-19 17:55:05.936  1015  1446 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-19 17:55:05.936  1015  1446 D SettingsProvider: selectionArgs: false
08-19 17:55:05.936  1015  1446 D SettingsProvider: selectionArgs: 1002
08-19 17:55:05.936  1015  1446 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-19 17:55:05.936  1015  1446 D SettingsProvider: ret = -1
,08-19 17:55:05.936  1015  1768 D SettingsProvider: name = bt_svcst_com.android.bluetooth.pan.PanService
08-19 17:55:05.936  1015  1768 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-19 17:55:05.936  1015  1768 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-19 17:55:05.936  1015  1768 D SettingsProvider: selectionArgs: false
08-19 17:55:05.936  1015  1768 D SettingsProvider: selectionArgs: 1002
08-19 17:55:05.936  1015  1768 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-19 17:55:05.936  1015  1768 D SettingsProvider: ret = -1
,08-19 17:55:05.936  1015  1133 D SettingsProvider: name = bt_svcst_com.android.bluetooth.map.BluetoothMapService
08-19 17:55:05.936  1015  1133 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-19 17:55:05.936  1015  1133 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-19 17:55:05.936  1015  1133 D SettingsProvider: selectionArgs: false
08-19 17:55:05.936  1015  1133 D SettingsProvider: selectionArgs: 1002
08-19 17:55:05.936  1015  1133 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-19 17:55:05.936  1015  1133 D SettingsProvider: ret = -1
,08-19 17:55:05.936  1015  1470 D SettingsProvider: name = bt_svcst_com.broadcom.bt.service.sap.SapService
08-19 17:55:05.936  1015  1470 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-19 17:55:05.936  1015  1470 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-19 17:55:05.936  1015  1470 D SettingsProvider: selectionArgs: false
08-19 17:55:05.936  1015  1470 D SettingsProvider: selectionArgs: 1002
08-19 17:55:05.936  1015  1470 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-19 17:55:05.936  1015  1470 D SettingsProvider: ret = -1
,08-19 17:55:05.936  1015  1338 D SettingsProvider: name = bt_svcst_com.android.bluetooth.hfpclient.HeadsetClientService
08-19 17:55:05.936  1015  1338 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-19 17:55:05.936  1015  1338 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-19 17:55:05.936  1015  1338 D SettingsProvider: selectionArgs: false
,08-19 17:55:05.936  1015  1338 D SettingsProvider: selectionArgs: 1002
08-19 17:55:05.936  1015  1338 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-19 17:55:05.936  1015  1338 D SettingsProvider: ret = -1
08-19 17:55:05.936  1015  1027 D SettingsProvider: name = bt_svcst_com.android.bluetooth.a2dp.A2dpSinkService
,08-19 17:55:05.936  1015  1027 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-19 17:55:05.936  1015  1027 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-19 17:55:05.936  1015  1027 D SettingsProvider: selectionArgs: false
08-19 17:55:05.936  1015  1027 D SettingsProvider: selectionArgs: 1002
08-19 17:55:05.936  1015  1027 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-19 17:55:05.936  1015  1027 D SettingsProvider: ret = -1
,08-19 17:55:05.936  1015  1474 D SettingsProvider: name = bt_svcst_com.android.bluetooth.sapclient.SapClientService
08-19 17:55:05.936  1015  1474 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-19 17:55:05.936  1015  1474 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
,08-19 17:55:05.936  1015  1474 D SettingsProvider: selectionArgs: false
08-19 17:55:05.936  1015  1474 D SettingsProvider: selectionArgs: 1002
,08-19 17:55:05.936  1015  1474 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-19 17:55:05.936  1015  1474 D SettingsProvider: ret = -1
,08-19 17:55:05.946  1015  3494 D SettingsProvider: name = bt_svcst_com.android.bluetooth.hid.HidDevService
08-19 17:55:05.946  1015  3494 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-19 17:55:05.946  1015  3494 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-19 17:55:05.946  1015  3494 D SettingsProvider: selectionArgs: false
08-19 17:55:05.946  1015  3494 D SettingsProvider: selectionArgs: 1002
08-19 17:55:05.946  1015  3494 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-19 17:55:05.946  1015  3494 D SettingsProvider: ret = -1
,08-19 17:55:05.946  1015  1028 I ActivityManager: Killing 5857:com.sec.android.app.soundalive/u0a48 (adj 15): empty #21
,08-19 17:55:05.956  1979  1979 D EasyUnlockReceiver: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.easyunlock.authorization.BluetoothStateChangeReceiver (has extras) }.
,08-19 17:55:05.956  1015  1470 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
08-19 17:55:05.956  1015  1470 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.easyunlock.authorization.InitializerIntentService; callingUser = 0; userId(target) = 0
,08-19 17:55:05.956  1015  1470 W ActivityManager: userId = 0, bbcId = -10000
,08-19 17:55:05.956  1015  1470 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-19 17:55:05.956  1015  1470 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-19 17:55:05.966  1979  6427 D EasyUnlockInitService: Handling intent for initializer IntentService.
08-19 17:55:05.966  1979  1979 D BtServices: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.proximity.BluetoothServicesAdapterStateChangeReceiver (has extras) }.
,08-19 17:55:05.966  1015  1028 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-19 17:55:05.966  1015  1028 W ActivityManager: userId = 0, bbcId = -10000
,08-19 17:55:05.966  1015  1028 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,08-19 17:55:05.976  1015  1028 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-19 17:55:05.986  1015  1042 D Tethering: interfaceRemoved p2p0
08-19 17:55:05.986  1015  1042 E Tethering: attempting to remove unknown iface (p2p0), ignoring
,08-19 17:55:05.986  1015  3492 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-19 17:55:05.986  1015  3492 W ActivityManager: userId = 0, bbcId = -10000
08-19 17:55:05.986  1015  3492 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-19 17:55:05.986  1015  3492 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-19 17:55:05.996  1979  6427 D EasyUnlockInitService: Not initializing EasyUnlock: remote_devices=0, bluetooth_on=false
,08-19 17:55:06.736   323   323 I ServiceManager: Waiting for service AtCmdFwd...,
,08-19 17:55:06.786  1015  1123 E WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:1
,08-19 17:55:07.736   323   323 I ServiceManager: Waiting for service AtCmdFwd...,
,08-19 17:55:07.736   291   291 E SMD     : DCD OFF,
,08-19 17:55:07.796  1015  1482 D SecContentProvider: uri = 18 selection = isWifiEnabled,
,08-19 17:55:07.796  1015  1482 D WifiService: setWifiEnabled: true pid=6220, uid=10171,
,08-19 17:55:07.796  1015  1482 D SecContentProvider2: uri = 20 selection = isWifiStateChangeAllowed,
08-19 17:55:07.796  1015  1482 W ActivityManager: Permission Denial: getCurrentUser() from pid=6220, uid=10171 requires android.permission.INTERACT_ACROSS_USERS
,08-19 17:55:07.796  1015  1482 D SecContentProvider2: mCursor = null,
,08-19 17:55:07.796  1015  1482 W WifiService: Failed getting userId using ActivityManagerNative
08-19 17:55:07.796  1015  1482 W WifiService: java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=6220, uid=10171 requires android.permission.INTERACT_ACROSS_USERS
08-19 17:55:07.796  1015  1482 W WifiService: 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:23972)
08-19 17:55:07.796  1015  1482 W WifiService: 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2216)
08-19 17:55:07.796  1015  1482 W WifiService: 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2204)
08-19 17:55:07.796  1015  1482 W WifiService: 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:223)
08-19 17:55:07.796  1015  1482 W WifiService: 	at android.os.Binder.execTransact(Binder.java:446)
,08-19 17:55:07.796  1015  1482 D SettingsProvider: name = wifi_on
08-19 17:55:07.806  1015  1123 E WifiHW  : ##################### set firmware type 0 #####################
,08-19 17:55:08.156  1015  1042 D Tethering: interfaceAdded wlan0
,08-19 17:55:08.166  1015  1128 E Tethering: No numeric data
,08-19 17:55:08.166  1015  1120 D NtpTrustedTime: forceRefresh() from cache miss
,08-19 17:55:08.176  1015  1042 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
,08-19 17:55:08.176  1015  1042 D Tethering: interfaceLinkStateChanged wlan0, false
08-19 17:55:08.176  1015  1042 D Tethering: interfaceStatusChanged wlan0, false
,08-19 17:55:08.176   281   967 D EnterpriseController: mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
08-19 17:55:08.176  1172  1172 D HotspotTile: onReceive : android.net.conn.TETHER_STATE_CHANGED
08-19 17:55:08.176   281   967 D Netd    : getNetworkForDns: using netid 0 for uid 1000
08-19 17:55:08.176  1172  1172 D HotspotTile: updateTetherState():false, false
08-19 17:55:08.176  1015  1128 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
08-19 17:55:08.176  1015  1128 D Tethering: clearTetheredNotification()
08-19 17:55:08.176  1015  1128 D Tethering: InitialState.processMessage what=4
,08-19 17:55:08.176  1015  1042 D Tethering: interfaceAdded p2p0
,08-19 17:55:08.186  1015  1128 E Tethering: No numeric data
08-19 17:55:08.186  1172  1172 D HotspotTile: onReceive : android.net.conn.TETHER_STATE_CHANGED
08-19 17:55:08.186  1015  1128 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
08-19 17:55:08.186  1172  1172 D HotspotTile: updateTetherState():false, false,
08-19 17:55:08.186  1015  1128 D Tethering: clearTetheredNotification()
08-19 17:55:08.186  1015  1042 D Tethering: p2p0 is not a tetherable iface, ignoring
,08-19 17:55:08.186   281   967 D EnterpriseController: mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0,
08-19 17:55:08.186   281   967 D Netd    : getNetworkForDns: using netid 0 for uid 1000
,08-19 17:55:08.196  1015  1120 D NtpTrustedTime: forceRefresh Fail.
,08-19 17:55:08.196  1015  1120 V NetworkStats: performPollLocked(flags=0x1)
08-19 17:55:08.196  1015  1042 D Tethering: interfaceLinkStateChanged p2p0, false
08-19 17:55:08.196  1015  1042 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
08-19 17:55:08.196  1015  1042 D Tethering: interfaceStatusChanged p2p0, false
08-19 17:55:08.196  1015  1120 D NetworkStatsFactory: UpdateStatsForKnox updated
08-19 17:55:08.196  1015  1120 D NetworkStatsFactory: UpdateStatsForKnox main else ---,
,08-19 17:55:08.206  1015  1120 V NetworkStats: performPollLocked() took 9ms
08-19 17:55:08.206   281   971 I WifiHW  : wifi_change_fw_path(): fwpath = sta
,08-19 17:55:08.206   281   971 D SoftapController: Softap fwReload - Ok
,08-19 17:55:08.206   281   971 D CommandListener: Setting iface cfg
08-19 17:55:08.206   281   971 D CommandListener: Trying to bring down wlan0
,08-19 17:55:08.206  1015  1121 D NtpTrustedTime: forceRefresh() from cache miss
,08-19 17:55:08.206  1015  1120 D NtpTrustedTime: forceRefresh() from cache miss
,08-19 17:55:08.206  1015  1120 D NtpTrustedTime: forceRefresh Fail.
,08-19 17:55:08.206  1015  1120 V NetworkStats: performPollLocked(flags=0x1)
08-19 17:55:08.206  1015  1121 D NtpTrustedTime: forceRefresh Fail.
,08-19 17:55:08.206   281   971 D CommandListener: Clearing all IP addresses on wlan0
08-19 17:55:08.206  1015  1120 D NetworkStatsFactory: UpdateStatsForKnox updated
,08-19 17:55:08.206  1015  1120 D NetworkStatsFactory: UpdateStatsForKnox main else ---
,08-19 17:55:08.206  1015  1120 V NetworkStats: performPollLocked() took 3ms
,08-19 17:55:08.216  1015  1123 E WifiHW  : supplicant_name : p2p_supplicant
,08-19 17:55:08.216  1015  1121 D NtpTrustedTime: forceRefresh() from cache miss
,08-19 17:55:08.216  1015  1121 D NtpTrustedTime: forceRefresh Fail.
,08-19 17:55:08.216  1015  1123 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
,08-19 17:55:08.226  1172  1172 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x0/(null) mQSWifiIconId=0x0/(null) mWifiActivityIconId=0x0/(null) mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-19 17:55:08.226  1172  1172 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=false enabledDesc:null
08-19 17:55:08.226  1172  1172 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-19 17:55:08.226  1172  1172 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-19 17:55:08.226  1172  1172 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-19 17:55:08.226  1172  1172 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-19 17:55:08.226  1172  1172 D STATUSBAR-WifiQuickSettingButton: onReceive : android.net.wifi.WIFI_STATE_CHANGED
08-19 17:55:08.226  1172  1745 D STATUSBAR-QSTileView: onStateChanged: Wi-Fi
08-19 17:55:08.226  1172  1172 D STATUSBAR-WifiQuickSettingButton: Wifi onReceive(2)
,08-19 17:55:08.236  1172  1172 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED,
08-19 17:55:08.236  1172  1172 D HotspotTile: onReceive : 2, 0
,08-19 17:55:08.236  1304  1304 D WifiCredService: Action received :android.net.wifi.WIFI_STATE_CHANGED
,08-19 17:55:08.236  6220  6220 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-19 17:55:08.246  6220  6220 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-19 17:55:08.246  1015  1028 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
08-19 17:55:08.246  1015  1028 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,08-19 17:55:08.246  1015  1028 W ActivityManager: userId = 0, bbcId = -10000
08-19 17:55:08.246  1015  1028 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-19 17:55:08.246  1015  1028 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,08-19 17:55:08.246  1619  1619 I Hs20UtilService: Starting #7,
,08-19 17:55:08.246  1619  1650 I Hs20UtilService: Message received 5011
,08-19 17:55:08.246  6394  6394 D SecurityLogAgent: KnoxConfiguration : Current State = 1
08-19 17:55:08.246  6394  6394 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
08-19 17:55:08.246  6394  6394 D SecurityLogAgent: StateMachine : Current State = 1
08-19 17:55:08.246  6394  6394 D SecurityLogAgent: StateMachine : Changed Current State = 1
,08-19 17:55:08.276  6438  6438 I wpa_supplicant: [wpa_supplicant_init]: use SECRIL,
08-19 17:55:08.276  6438  6438 I wpa_supplicant: Successfully initialized wpa_supplicant
08-19 17:55:08.276  6438  6438 I SecureStorage: [INFO]: SPID(0x00000000)Checking if this device supports Secure Storage
,08-19 17:55:08.286  6438  6438 I SecureStorage: [INFO]: SPID(0x00000000)This device supports Secure Storage,
08-19 17:55:08.286   369   369 I SecureStorage: [INFO]: SPID(0x00000001)Credentials: uid 1010, gid 1010, pid 6438
08-19 17:55:08.286   369   369 I SecureStorage: [INFO]: SPID(0x00000001)Received function mask & code: 0x0000010C
,08-19 17:55:08.286  6438  6438 I SecureStorage: [INFO]: SPID(0x00000000)SS Daemon is running
08-19 17:55:08.286  6438  6438 I wpa_supplicant: ssSupport state is = 1
08-19 17:55:08.286  6438  6438 I wpa_supplicant: >>>>> GET KEY, IV <<<<<
08-19 17:55:08.286  6438  6438 I SecureStorage: [INFO]: SPID(0x00000000)Processing data
,08-19 17:55:08.286   369   369 I SecureStorage: [INFO]: SPID(0x00000001)Credentials: uid 1010, gid 1010, pid 6438
08-19 17:55:08.286   369   369 I SecureStorage: [INFO]: SPID(0x00000001)Received function mask & code: 0x00000106
,08-19 17:55:08.456   369   369 I SecureStorage: [INFO]: SPID(0x00000002)Secure Storage Daemon finished processing with result: 0,
,08-19 17:55:08.456  6438  6438 I SecureStorage: [INFO]: SPID(0x00000002)Processing data has been completed,
,08-19 17:55:08.506  6438  6438 I wpa_supplicant: Ctrl_iface: loading cred from phone,
08-19 17:55:08.506  6438  6438 I SecureStorage: [INFO]: SPID(0x00000002)Checking if this device supports Secure Storage
,08-19 17:55:08.516  6438  6438 I SecureStorage: [INFO]: SPID(0x00000002)This device supports Secure Storage
,08-19 17:55:08.516   369   369 I SecureStorage: [INFO]: SPID(0x00000002)Credentials: uid 1010, gid 1010, pid 6438
08-19 17:55:08.516   369   369 I SecureStorage: [INFO]: SPID(0x00000002)Received function mask & code: 0x0000010C
08-19 17:55:08.516  6438  6438 I SecureStorage: [INFO]: SPID(0x00000002)SS Daemon is running,
08-19 17:55:08.516  6438  6438 I wpa_supplicant: ssSupport state is = 1
08-19 17:55:08.516  6438  6438 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
08-19 17:55:08.516  6438  6438 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory,
08-19 17:55:08.516  6438  6438 E wpa_supplicant: SIM READ ERROR
08-19 17:55:08.516  6438  6438 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
08-19 17:55:08.516  6438  6438 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
08-19 17:55:08.516  6438  6438 E wpa_supplicant: SIM READ ERROR
,08-19 17:55:08.516  6438  6438 I wpa_supplicant: Blacklist: Clear (all) 
08-19 17:55:08.516  6438  6438 I wpa_supplicant: wpa_default_ap_write_once
08-19 17:55:08.516  6438  6438 I wpa_supplicant: There is no /data/misc/wifi/default_ap.check. Start copy default ap
08-19 17:55:08.516  6438  6438 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
08-19 17:55:08.516  6438  6438 E wpa_supplicant: getSavedIMSI cannot open /data/misc/wifi/.kmem: No such file or directory
,08-19 17:55:08.516  6438  6438 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
08-19 17:55:08.516  6438  6438 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
08-19 17:55:08.516  6438  6438 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,08-19 17:55:08.526  1015  1042 D Tethering: interfaceLinkStateChanged wlan0, false
08-19 17:55:08.526  1015  1042 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
08-19 17:55:08.526  1015  1042 D Tethering: interfaceStatusChanged wlan0, false
,08-19 17:55:08.636  6438  6438 I wpa_supplicant: wlan0: Setting scan request: 0 sec 100000 usec,
,08-19 17:55:08.736   323   323 I ServiceManager: Waiting for service AtCmdFwd...,
,08-19 17:55:08.796  6438  6438 I wpa_supplicant: wlan0: State: DISCONNECTED -> DISCONNECTED,
,08-19 17:55:08.796  6438  6438 I SecureStorage: [INFO]: SPID(0x00000002)Checking if this device supports Secure Storage,
,08-19 17:55:08.806  6438  6438 I SecureStorage: [INFO]: SPID(0x00000002)This device supports Secure Storage,
08-19 17:55:08.806   369   369 I SecureStorage: [INFO]: SPID(0x00000002)Credentials: uid 1010, gid 1010, pid 6438,
08-19 17:55:08.806   369   369 I SecureStorage: [INFO]: SPID(0x00000002)Received function mask & code: 0x0000010C
,08-19 17:55:08.816  6438  6438 I SecureStorage: [INFO]: SPID(0x00000002)SS Daemon is running,
,08-19 17:55:08.816  6438  6438 I wpa_supplicant: ssSupport state is = 1
,08-19 17:55:08.816  6438  6438 I wpa_supplicant: Ctrl_iface: loading cred from phone,
08-19 17:55:08.816  6438  6438 I SecureStorage: [INFO]: SPID(0x00000002)Checking if this device supports Secure Storage
,08-19 17:55:08.836  6438  6438 I SecureStorage: [INFO]: SPID(0x00000002)This device supports Secure Storage,
08-19 17:55:08.836   369   369 I SecureStorage: [INFO]: SPID(0x00000002)Credentials: uid 1010, gid 1010, pid 6438
08-19 17:55:08.836   369   369 I SecureStorage: [INFO]: SPID(0x00000002)Received function mask & code: 0x0000010C,
08-19 17:55:08.836  6438  6438 I SecureStorage: [INFO]: SPID(0x00000002)SS Daemon is running
08-19 17:55:08.836  6438  6438 I wpa_supplicant: ssSupport state is = 1,
08-19 17:55:08.836  6438  6438 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
08-19 17:55:08.836  6438  6438 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
08-19 17:55:08.836  6438  6438 E wpa_supplicant: SIM READ ERROR,
08-19 17:55:08.836  6438  6438 I wpa_supplicant: wpa_default_ap_write_once
08-19 17:55:08.836  6438  6438 I wpa_supplicant: There is no /data/misc/wifi/default_ap.check. Start copy default ap
08-19 17:55:08.836  6438  6438 I wpa_supplicant: rfkill: Cannot open RFKILL control device,
,08-19 17:55:08.836  1015  1042 D Tethering: interfaceLinkStateChanged p2p0, false
08-19 17:55:08.836  1015  1042 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
08-19 17:55:08.836  1015  1042 D Tethering: interfaceStatusChanged p2p0, false,
,08-19 17:55:08.846  1015  1042 D Tethering: interfaceLinkStateChanged p2p0, false,
,08-19 17:55:08.846  1015  1042 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
08-19 17:55:08.846  1015  1042 D Tethering: interfaceStatusChanged p2p0, false
,08-19 17:55:08.886  6438  6438 I wpa_supplicant: p2p0: State: DISCONNECTED -> INACTIVE,
08-19 17:55:08.886  6438  6438 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=-1 state=2 BSSID=00.00.00 SSID=
,08-19 17:55:08.936  6438  6438 I wpa_supplicant: p2p0: State: INACTIVE -> DISCONNECTED
08-19 17:55:08.936  6438  6438 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=-1 state=0 BSSID=00.00.00 SSID=
08-19 17:55:08.936  6438  6438 I wpa_supplicant: Skip scan - bUseNetwork false
,08-19 17:55:08.936  1015  1123 E WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:2
,08-19 17:55:08.936  1015  1123 D WifiNative-wlan0: callSECApiBoolean - ID [21]
,08-19 17:55:08.946  6438  6438 I wpa_supplicant: HOTSPOT20_ENABLE called
08-19 17:55:08.946  6438  6438 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
08-19 17:55:08.946  6438  6438 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
08-19 17:55:08.946  6438  6438 E wpa_supplicant: SIM READ ERROR
08-19 17:55:08.946  6438  6438 I wpa_supplicant: Blacklist: Clear (all) 
,08-19 17:55:08.956  6438  6438 I wpa_supplicant: wlan0: Setting scan request: 0 sec 0 usec
,08-19 17:55:08.966  6438  6438 I wpa_supplicant: Skip scan - bUseNetwork false,
,08-19 17:55:08.966  1015  1123 D WifiConfigStore: Loading config and enabling all networks 
08-19 17:55:08.966  1172  1172 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x0/(null) mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-19 17:55:08.966  1172  1172 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
,08-19 17:55:08.966  1172  1172 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-19 17:55:08.966  1172  1172 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-19 17:55:08.966  1172  1172 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-19 17:55:08.966  1172  1172 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-19 17:55:08.986  1172  1172 D STATUSBAR-WifiQuickSettingButton: onReceive : android.net.wifi.WIFI_STATE_CHANGED
08-19 17:55:08.986  1172  1172 D STATUSBAR-WifiQuickSettingButton: Wifi onReceive(3)
08-19 17:55:08.986  1172  1745 D STATUSBAR-QSTileView: onStateChanged: Wi-Fi
08-19 17:55:08.986  1172  1172 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
,08-19 17:55:08.986  1172  1172 D HotspotTile: onReceive : 3, 0
,08-19 17:55:08.986  1015  1123 E WifiConfigStore: Not a HS20
,08-19 17:55:08.986  1015  1123 E WifiConfigStore: Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory),
,08-19 17:55:08.996  1304  1304 D WifiCredService: Action received :android.net.wifi.WIFI_STATE_CHANGED,
08-19 17:55:08.996  6220  6220 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-19 17:55:08.996  6220  6220 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-19 17:55:08.996  6220  6220 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-19 17:55:08.996  6220  6220 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-19 17:55:08.996  6220  6220 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-19 17:55:08.996  6220  6220 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-19 17:55:08.996  6220  6220 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-19 17:55:08.996  6220  6220 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-19 17:55:08.996  6220  6220 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-19 17:55:08.996  6220  6220 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value,
08-19 17:55:08.996  6220  6220 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-19 17:55:08.996  6220  6220 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-19 17:55:09.006  6220  6220 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-19 17:55:09.006  6220  6220 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-19 17:55:09.006  6220  6220 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-19 17:55:09.006  6220  6220 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-19 17:55:09.006  6220  6220 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
,08-19 17:55:09.006  6220  6220 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-19 17:55:09.006  6220  6220 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
,08-19 17:55:09.006  6220  6220 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-19 17:55:09.006  6220  6220 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value,
08-19 17:55:09.006  1015  1470 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
08-19 17:55:09.006  6220  6220 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-19 17:55:09.006  1015  1470 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4327, temperature: 280, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
,08-19 17:55:09.006  1015  1338 W ActivityManager: userId = 0, bbcId = -10000
08-19 17:55:09.006  1015  1470 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
08-19 17:55:09.006  1015  1338 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-19 17:55:09.006  1015  1470 D BatteryService: stay LED for fully charged
08-19 17:55:09.006  1015  1338 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,08-19 17:55:09.006  1015  1015 D BatteryService: Sending ACTION_BATTERY_CHANGED.
08-19 17:55:09.006  1015  1338 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
08-19 17:55:09.016  1619  1619 I Hs20UtilService: Starting #8,
08-19 17:55:09.006  1015  1338 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,08-19 17:55:09.016  1619  1650 I Hs20UtilService: Message received 5011
08-19 17:55:09.016  1015  1015 I MotionRecognitionService: Plugged
,08-19 17:55:09.016  1015  1015 I MotionRecognitionService: mGripSensorEnabled= false
,08-19 17:55:09.016  1172  1172 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,08-19 17:55:09.016  1172  1172 D KeyguardUpdateMonitor: handleBatteryUpdate,
,08-19 17:55:09.026  1405  1405 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,08-19 17:55:09.026  1405  1405 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,08-19 17:55:09.036  1015  1123 D WifiNative-wlan0: callSECApiInt - ID [65]
,08-19 17:55:09.046  1015  1123 D WifiNative-wlan0: callSECApiBoolean - ID [13]
,08-19 17:55:09.046  6438  6438 I wpa_supplicant: USE_NETWORK : USE_NETWORK ON,
08-19 17:55:09.046  6438  6438 I wpa_supplicant: wlan0: Setting scan request: 8 sec 0 usec
08-19 17:55:09.046  1172  1172 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
08-19 17:55:09.046  1172  1172 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-19 17:55:09.046  6394  6394 D SecurityLogAgent: KnoxConfiguration : Current State = 1
08-19 17:55:09.046  6438  6438 I wpa_supplicant: reset timer : RESET_TIMER 0
08-19 17:55:09.046  6438  6438 I wpa_supplicant: P2P: Current p2p state = IDLE
,08-19 17:55:09.046  6438  6438 I wpa_supplicant: wlan0: State: DISCONNECTED -> SCANNING
08-19 17:55:09.046  6438  6438 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00.00.00 SSID=
08-19 17:55:09.046  6438  6438 I wpa_supplicant: First Scan Start
,08-19 17:55:09.046  6438  6438 I wpa_supplicant: Scan requested (ret=0) - scan timeout 30 seconds
,08-19 17:55:09.046  6394  6394 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
,08-19 17:55:09.046  6394  6394 D SecurityLogAgent: StateMachine : Current State = 1
08-19 17:55:09.046  1172  1172 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
08-19 17:55:09.046  6394  6394 D SecurityLogAgent: StateMachine : Changed Current State = 1
08-19 17:55:09.046  1015  1123 D WifiNative-wlan0: Setting external_sim to 1
,08-19 17:55:09.046  1015  1123 D WifiStateMachine: Setting OUI to DA-A1-19
08-19 17:55:09.046  1015  1123 I WifiNative-HAL: startHal
08-19 17:55:09.046  1015  1123 E wifi    : getStaticLongField sWifiHalHandle 0x9d5c488c
08-19 17:55:09.046  1015  1123 I WifiNative-HAL: Could not start hal
,08-19 17:55:09.056  1015  1123 E WifiNative-wlan0: do suspend true
,08-19 17:55:09.056  1015  1122 D WifiP2pService: P2pDisabledState{ what=131203 }
,08-19 17:55:09.056  1015  1123 E WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:3
08-19 17:55:09.056   281   971 D CommandListener: Setting iface cfg
08-19 17:55:09.056   281   971 D CommandListener: Trying to bring up p2p0
,08-19 17:55:09.066  1015  1015 D WifiScanningService: SCAN_AVAILABLE : 3
08-19 17:55:09.066  1015  1122 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
08-19 17:55:09.066  1015  1147 D WifiScanningService: DefaultState got{ when=0 what=160006 target=com.android.internal.util.StateMachine$SmHandler }
08-19 17:55:09.066  1015  1147 I WifiNative-HAL: startHal
,08-19 17:55:09.066  1015  1147 E wifi    : getStaticLongField sWifiHalHandle 0x9e7769bc
08-19 17:55:09.066  1015  1122 D WifiP2pService: P2pEnablingState
08-19 17:55:09.066  1015  1147 I WifiNative-HAL: Could not start hal
08-19 17:55:09.066  1015  1147 E WifiScanningService: could not start HAL
08-19 17:55:09.066  1015  1122 D WifiP2pService: P2pEnablingState{ what=147457 }
08-19 17:55:09.066  1015  1015 D RttService: SCAN_AVAILABLE : 3
08-19 17:55:09.066  1015  1148 D RttService: DefaultState got{ when=0 what=160512 target=com.android.internal.util.StateMachine$SmHandler }
08-19 17:55:09.066  1015  1122 D WifiP2pService: P2p socket connection successful
08-19 17:55:09.066  1015  1122 D WifiP2pService: P2pEnabledState
08-19 17:55:09.066  1015  1123 E WifiStateMachine: DriverStatedState::CMD_SEC_STRING_API - inner msg [207]
08-19 17:55:09.066  1015  1123 D WifiNative-wlan0: callSECStringApiVoid - ID [215]
08-19 17:55:09.066  1015  1123 E WifiNative-wlan0: invaild command id : 215
,08-19 17:55:09.066  1015  1123 E WifiStateMachine: DriverStatedState::CMD_SEC_STRING_API - inner msg [207]
08-19 17:55:09.066  1015  1123 D WifiNative-wlan0: callSECStringApiVoid - ID [215]
08-19 17:55:09.066  1015  1123 E WifiNative-wlan0: invaild command id : 215
,08-19 17:55:09.066  1015  1015 E WifiStateMachine: BroadcastReceiver : WIFI_P2P_STATE_CHANGED_ACTION is : android.net.wifi.p2p.STATE_CHANGED
,08-19 17:55:09.066  1015  1122 D WifiP2pService: sending p2p connection changed broadcast: DISCONNECTED
,08-19 17:55:09.066  1015  1125 E ConnectivityService: updateNetworkInfo()
08-19 17:55:09.066  6438  6438 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=PL
08-19 17:55:09.066  1015  1045 D WifiDisplayController: Received WIFI_P2P_STATE_CHANGED_ACTION: enabled=true
08-19 17:55:09.066  1015  1045 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
08-19 17:55:09.066  1015  1045 D WifiDisplayController: disconnect
08-19 17:55:09.066  1015  1045 D WifiDisplayController: updateConnection
08-19 17:55:09.066  1015  1045 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
08-19 17:55:09.066  1015  1045 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,08-19 17:55:09.066  6438  6438 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=PL
,08-19 17:55:09.076  6438  6438 E wpa_supplicant: wpa_driver_nl80211_driver_cmd: failed to issue private commands,
08-19 17:55:09.076  1015  1123 E WifiStateMachine: Failed to set frequency band 0
08-19 17:55:09.076  1015  1123 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
08-19 17:55:09.076  1015  1123 D SecContentProvider2: mCursor = null
08-19 17:55:09.076  1172  1172 D AllShareCastTile: action: android.hardware.display.action.WIFI_DISPLAY_STATUS_CHANGED
,08-19 17:55:09.076  1015  1028 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
08-19 17:55:09.076  1172  1172 D AllShareCastTile: wifi display status changed! scanstate : 0, ActiveDisplayState : 0
08-19 17:55:09.076  1015  1122 D WifiNative-p2p0: p2pGetDeviceAddress
08-19 17:55:09.076  1015  1122 D WifiNative-p2p0: p2pGetDeviceAddress returning 0a:ec:a9:50:76:28
,08-19 17:55:09.086  1015  1045 D WifiDisplayController: Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false],
,08-19 17:55:09.086  1015  1045 D WifiDisplayAdapter: onP2pDisconnected
,08-19 17:55:09.086  1015  1045 D IpRemoteDisplayController: disconnectWfdBridgeServer
08-19 17:55:09.086  1015  1045 D IpRemoteDisplayController: WfdBridgeServer is already null
,08-19 17:55:09.086  1304  1304 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.p2p.CONNECTION_STATE_CHANGE
,08-19 17:55:09.086  1015  1122 D WifiP2pService: DeviceAddress: 0a:76:28
,08-19 17:55:09.096  1015  1123 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
,08-19 17:55:09.096  1015  1123 D SecContentProvider2: mCursor = null
08-19 17:55:09.096  1015  2770 D SSRM:n  : SIOP:: AP = 340
,08-19 17:55:09.096  1304  1304 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
,08-19 17:55:09.096  1304  1304 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,08-19 17:55:09.096  1015  1045 D WifiDisplayController: Received WIFI_P2P_THIS_DEVICE_CHANGED_ACTION: mThisDevice= Device: Thali Test (Galaxy A3)
08-19 17:55:09.096  1015  1045 D WifiDisplayController:  deviceAddress: 0a:ec:a9:50:76:28
08-19 17:55:09.096  1015  1045 D WifiDisplayController:  primary type: 10-0050F204-5
08-19 17:55:09.096  1015  1045 D WifiDisplayController:  secondary type: null
08-19 17:55:09.096  1015  1045 D WifiDisplayController:  wps: 0
08-19 17:55:09.096  1015  1045 D WifiDisplayController:  grpcapab: 0
08-19 17:55:09.096  1015  1045 D WifiDisplayController:  devcapab: 0
08-19 17:55:09.096  1015  1045 D WifiDisplayController:  status: 3
08-19 17:55:09.096  1015  1045 D WifiDisplayController:  wfdInfo: null
08-19 17:55:09.096  1015  1045 D WifiDisplayController:  groupownerAddress: null
08-19 17:55:09.096  1015  1045 D WifiDisplayController:  GOdeviceName: null
08-19 17:55:09.096  1015  1045 D WifiDisplayController:  interfaceAddress: 
08-19 17:55:09.096  1015  1045 D WifiDisplayController:  SConnectInfo : null
,08-19 17:55:09.106  1304  1304 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
08-19 17:55:09.106  1015  1122 D WifiP2pService: sending p2p persistent groups changed broadcast
08-19 17:55:09.106  1304  1304 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
08-19 17:55:09.106  1304  1304 I NearbySettings: MountReceiver.onReceive - Set preference state off
08-19 17:55:09.106  1304  2187 V NearbySettings: MountReceiver.mPrefHandler - 7002
,08-19 17:55:09.106  6438  6438 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=PL
08-19 17:55:09.106  1015  1122 D WifiP2pService: InactiveState
08-19 17:55:09.106  6362  6362 D FileShare-Client: ClientBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,08-19 17:55:09.106  1015  1122 D WifiP2pService: InactiveState{ what=143376 }
08-19 17:55:09.106  1015  1122 D WifiP2pService: P2pEnabledState{ what=143376 }
,08-19 17:55:09.106  6362  6362 D FileShare-Client: ClientBroadcastReceiver.onReceive - disconnected
,08-19 17:55:09.106  1015  1122 D WifiP2pService: InactiveState{ what=143376 }
,08-19 17:55:09.106  6362  6362 D FileShare-Client: Outbound.stopDelayTimer - 
08-19 17:55:09.106  1015  1122 D WifiP2pService: P2pEnabledState{ what=143376 }
,08-19 17:55:09.116  6379  6379 D FileShare-Server: ServerBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,08-19 17:55:09.176  1015  1042 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
,08-19 17:55:09.176  1015  1042 D Tethering: interfaceLinkStateChanged p2p0, false
,08-19 17:55:09.176  1015  1042 D Tethering: interfaceStatusChanged p2p0, false
,08-19 17:55:09.736   323   323 I ServiceManager: Waiting for service AtCmdFwd...
,08-19 17:55:10.256  6438  6438 I wpa_supplicant: nl80211: Received scan results (32 BSSes),
08-19 17:55:10.256  6438  6438 I wpa_supplicant: wlan0: Setting scan request: 8 sec 0 usec
08-19 17:55:10.256  6438  6438 I wpa_supplicant: Trying to associate with SSID '4E47373030',
08-19 17:55:10.256  6438  6438 I wpa_supplicant: Trying to associate with  'G700'
08-19 17:55:10.256  6438  6438 I wpa_supplicant: wlan0: State: SCANNING -> ASSOCIATING,
08-19 17:55:10.256  6438  6438 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=5 BSSID=00.00.00 SSID=4E47373030
08-19 17:55:10.266  1015  6443 D WifiMonitor: didn't find BSSID Trying to associate with SSID 'NG700',
,08-19 17:55:10.286  1015  1123 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
,08-19 17:55:10.286  1015  1123 D SecContentProvider2: mCursor = null
,08-19 17:55:10.736   323   323 I ServiceManager: Waiting for service AtCmdFwd...,
,08-19 17:55:10.736   291   291 E SMD     : DCD OFF,
,08-19 17:55:10.806  1015  3492 D SecContentProvider: uri = 18 selection = isWifiEnabled
,08-19 17:55:10.806  1015  3492 D SecContentProvider2: uri = 20 selection = isWifiStateChangeAllowed
08-19 17:55:10.816  1015  3492 D SecContentProvider2: mCursor = null
,08-19 17:55:10.816  1015  3492 D WifiService: setWifiEnabled: false pid=6220, uid=10171
,08-19 17:55:10.816  1015  3492 D SettingsProvider: name = wifi_on
,08-19 17:55:10.826  1015  1122 D WifiP2pService: InactiveState{ what=131204 }
,08-19 17:55:10.826  1015  1122 D WifiP2pService: P2pEnabledState{ what=131204 }
08-19 17:55:10.826  1015  1015 D WifiScanningService: SCAN_AVAILABLE : 1
,08-19 17:55:10.826  1015  1147 D WifiScanningService: DefaultState got{ when=0 what=160007 target=com.android.internal.util.StateMachine$SmHandler }
08-19 17:55:10.826  1015  1122 D WifiP2pService: sending p2p connection changed broadcast: FAILED
08-19 17:55:10.826  1015  1015 D RttService: SCAN_AVAILABLE : 1
,08-19 17:55:10.826  1015  1125 E ConnectivityService: updateNetworkInfo()
08-19 17:55:10.826  1015  1148 D RttService: EnabledState got{ when=0 what=160513 target=com.android.internal.util.StateMachine$SmHandler }
,08-19 17:55:10.826  1015  1045 D WifiDisplayController: Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/FAILED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,08-19 17:55:10.826  1015  1045 D WifiDisplayAdapter: onP2pDisconnected
08-19 17:55:10.826  1015  1045 D IpRemoteDisplayController: disconnectWfdBridgeServer
08-19 17:55:10.826  1015  1045 D IpRemoteDisplayController: WfdBridgeServer is already null
,08-19 17:55:10.836  1015  1122 D WifiP2pService: sending p2p connection changed broadcast: DISCONNECTED
,08-19 17:55:10.836  1304  1304 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.p2p.CONNECTION_STATE_CHANGE
08-19 17:55:10.836  1304  1304 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
,08-19 17:55:10.836  1015  1125 E ConnectivityService: updateNetworkInfo()
,08-19 17:55:10.836  1304  1304 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,08-19 17:55:10.836  1015  1015 E WifiStateMachine: BroadcastReceiver : WIFI_P2P_STATE_CHANGED_ACTION is : android.net.wifi.p2p.STATE_CHANGED
08-19 17:55:10.836  1304  1304 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
08-19 17:55:10.836  1304  1304 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
08-19 17:55:10.836  1304  1304 I NearbySettings: MountReceiver.onReceive - Set preference state off
,08-19 17:55:10.846  1015  1122 D WifiP2pService: P2pDisablingState
,08-19 17:55:10.846  1015  1122 D WifiP2pService: P2pDisablingState{ what=147458 }
,08-19 17:55:10.846  1015  1122 D WifiP2pService: p2p socket connection lost
,08-19 17:55:10.846  1015  1122 D WifiP2pService: P2pDisabledState
08-19 17:55:10.846  1015  1045 D WifiDisplayController: Received WIFI_P2P_STATE_CHANGED_ACTION: enabled=false
08-19 17:55:10.846  1015  1045 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
08-19 17:55:10.846   281   971 D CommandListener: Clearing all IP addresses on wlan0
08-19 17:55:10.846  1015  1045 D WifiDisplayController: disconnect
08-19 17:55:10.846  1304  2187 V NearbySettings: MountReceiver.mPrefHandler - 7002
08-19 17:55:10.846  1015  1045 D WifiDisplayController: updateConnection
08-19 17:55:10.846  1015  1045 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
08-19 17:55:10.846  1015  1045 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,08-19 17:55:10.856  6362  6362 D FileShare-Client: ClientBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,08-19 17:55:10.856  1015  1045 D WifiDisplayController: Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: false, isConnectedToProvisioningNetwork: false]
08-19 17:55:10.856  1015  1045 D WifiDisplayAdapter: onP2pDisconnected
,08-19 17:55:10.856  1015  1045 D IpRemoteDisplayController: disconnectWfdBridgeServer
08-19 17:55:10.856  6362  6362 D FileShare-Client: ClientBroadcastReceiver.onReceive - disconnected
08-19 17:55:10.856  1015  1045 D IpRemoteDisplayController: WfdBridgeServer is already null
08-19 17:55:10.856  6362  6362 D FileShare-Client: Outbound.stopDelayTimer - 
,08-19 17:55:10.856  1172  1172 D AllShareCastTile: action: android.hardware.display.action.WIFI_DISPLAY_STATUS_CHANGED
,08-19 17:55:10.856  1015  3485 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,08-19 17:55:10.856  1172  1172 D AllShareCastTile: wifi display status changed! scanstate : 0, ActiveDisplayState : 0
,08-19 17:55:10.866  1015  1015 I WifiTrafficPoller: evaluateTrafficStatsPolling
,08-19 17:55:10.866  6438  6438 I wpa_supplicant: p2p0: State: DISCONNECTED -> DISCONNECTED
,08-19 17:55:10.876  1172  1172 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x0/(null) mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-19 17:55:10.876  1172  1172 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
08-19 17:55:10.876  1172  1172 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-19 17:55:10.876  1172  1172 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-19 17:55:10.876  1172  1172 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-19 17:55:10.876  1172  1172 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-19 17:55:10.876  6379  6379 D FileShare-Server: ServerBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,08-19 17:55:10.886  1172  1172 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x0/(null) mQSWifiIconId=0x0/(null) mWifiActivityIconId=0x0/(null) mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,08-19 17:55:10.896  1172  1172 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=false enabledDesc:null
08-19 17:55:10.896  1172  1172 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-19 17:55:10.896  1172  1172 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-19 17:55:10.896  1172  1172 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-19 17:55:10.896  1172  1172 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-19 17:55:10.896  1172  1172 D STATUSBAR-WifiQuickSettingButton: onReceive : android.net.wifi.WIFI_STATE_CHANGED
,08-19 17:55:10.896  1172  1172 D STATUSBAR-WifiQuickSettingButton: Wifi onReceive(0)
,08-19 17:55:10.896  1172  1745 D STATUSBAR-QSTileView: onStateChanged: Wi-Fi
,08-19 17:55:10.906  1172  1172 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
,08-19 17:55:10.906  1172  1172 D HotspotTile: onReceive : 0, 0
,08-19 17:55:10.906  1304  1304 D WifiCredService: Action received :android.net.wifi.WIFI_STATE_CHANGED
,08-19 17:55:10.906  6220  6220 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-19 17:55:10.906  6220  6220 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-19 17:55:10.906  6220  6220 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-19 17:55:10.906  6220  6220 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-19 17:55:10.906  6220  6220 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-19 17:55:10.906  6220  6220 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-19 17:55:10.906  6220  6220 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-19 17:55:10.906  6220  6220 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-19 17:55:10.906  6220  6220 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-19 17:55:10.906  6220  6220 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-19 17:55:10.906  6220  6220 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-19 17:55:10.916  6220  6220 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value,
08-19 17:55:10.916  6220  6220 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-19 17:55:10.916  6220  6220 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-19 17:55:10.916  6220  6220 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-19 17:55:10.916  6220  6220 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-19 17:55:10.916  6220  6220 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-19 17:55:10.916  6220  6220 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-19 17:55:10.916  6220  6220 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-19 17:55:10.916  6220  6220 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false,
08-19 17:55:10.916  6220  6220 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-19 17:55:10.916  6220  6220 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-19 17:55:10.916  1304  1304 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.p2p.CONNECTION_STATE_CHANGE
,08-19 17:55:10.916  1304  1304 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
,08-19 17:55:10.916  1304  1304 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,08-19 17:55:10.916  1304  1304 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
,08-19 17:55:10.916  1304  1304 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
08-19 17:55:10.916  1304  1304 I NearbySettings: MountReceiver.onReceive - Set preference state off
,08-19 17:55:10.926  1304  2187 V NearbySettings: MountReceiver.mPrefHandler - 7002
,08-19 17:55:10.926  6362  6362 D FileShare-Client: ClientBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,08-19 17:55:10.926  6362  6362 D FileShare-Client: ClientBroadcastReceiver.onReceive - disconnected
,08-19 17:55:10.926  6362  6362 D FileShare-Client: Outbound.stopDelayTimer - 
,08-19 17:55:10.936  6379  6379 D FileShare-Server: ServerBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,08-19 17:55:10.936  1015  3492 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
08-19 17:55:10.936  1015  3492 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,08-19 17:55:10.936  1015  3492 W ActivityManager: userId = 0, bbcId = -10000
08-19 17:55:10.936  1015  3492 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-19 17:55:10.936  1015  3492 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,08-19 17:55:10.936  1619  1619 I Hs20UtilService: Starting #9
,08-19 17:55:10.946  1619  1650 I Hs20UtilService: Message received 5007
,08-19 17:55:10.946  1304  1304 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
08-19 17:55:10.946  1304  1304 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
,08-19 17:55:10.946  1304  1304 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,08-19 17:55:10.946  1304  1304 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
,08-19 17:55:10.946  1304  1304 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
,08-19 17:55:10.946  1304  1304 I NearbySettings: MountReceiver.onReceive - Set preference state off
,08-19 17:55:10.946  1304  2187 V NearbySettings: MountReceiver.mPrefHandler - 7002
,08-19 17:55:10.956  1015  1446 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
,08-19 17:55:10.956  1015  1446 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,08-19 17:55:10.956  1015  1446 W ActivityManager: userId = 0, bbcId = -10000
,08-19 17:55:10.956  1015  1446 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-19 17:55:10.956  1015  1446 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,08-19 17:55:10.966  1619  1619 I Hs20UtilService: Starting #10
,08-19 17:55:10.966  1619  1650 I Hs20UtilService: Message received 5011
,08-19 17:55:10.966  6394  6394 D SecurityLogAgent: KnoxConfiguration : Current State = 1
08-19 17:55:10.966  6394  6394 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
,08-19 17:55:10.966  6394  6394 D SecurityLogAgent: StateMachine : Current State = 1
08-19 17:55:10.966  6394  6394 D SecurityLogAgent: StateMachine : Changed Current State = 1
,08-19 17:55:11.126  6438  6438 I wpa_supplicant: Blacklist: Clear (all) 
,08-19 17:55:11.166  6438  6438 I wpa_supplicant: p2p0: CTRL-EVENT-TERMINATING ,
,08-19 17:55:11.166  1015  1042 I Nat464Xlat: interfaceLinkStateChanged p2p0, false,
,08-19 17:55:11.166  1015  1042 D Tethering: interfaceLinkStateChanged p2p0, false
08-19 17:55:11.166  1015  1042 D Tethering: interfaceStatusChanged p2p0, false,
,08-19 17:55:11.386  6438  6438 I wpa_supplicant: CTRL-EVENT-DISCONNECTED bssid=00.00.00 reason=3 locally_generated=1
,08-19 17:55:11.386  6438  6438 I wpa_supplicant: wlan0: State: ASSOCIATING -> DISCONNECTED,
08-19 17:55:11.386  6438  6438 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=00.00.00 SSID=4E47373030
08-19 17:55:11.386  1015  1042 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
08-19 17:55:11.386  6438  6438 I wpa_supplicant: wlan0: State: DISCONNECTED -> DISCONNECTED
08-19 17:55:11.386  1015  1042 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
08-19 17:55:11.386  1015  1042 D Tethering: interfaceLinkStateChanged wlan0, false
08-19 17:55:11.386  1015  1042 D Tethering: interfaceStatusChanged wlan0, false
08-19 17:55:11.386  1015  1042 D Tethering: interfaceLinkStateChanged wlan0, false
08-19 17:55:11.386  1015  1042 D Tethering: interfaceStatusChanged wlan0, false
,08-19 17:55:11.616  6438  6438 I wpa_supplicant: Blacklist: Clear (all) 
,08-19 17:55:11.726  6438  6438 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING ,
08-19 17:55:11.726  1015  1042 I Nat464Xlat: interfaceLinkStateChanged wlan0, false,
,08-19 17:55:11.726  1015  1042 D Tethering: interfaceLinkStateChanged wlan0, false
08-19 17:55:11.726  1015  1042 D Tethering: interfaceStatusChanged wlan0, false
08-19 17:55:11.736   323   323 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 2
08-19 17:55:11.736  1015  1123 E WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:0
08-19 17:55:11.736  1015  1123 D WifiNative-wlan0: callSECApiBoolean - ID [21]
,08-19 17:55:11.746  1172  1172 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x0/(null) mQSWifiIconId=0x0/(null) mWifiActivityIconId=0x0/(null) mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth,
,08-19 17:55:11.746  1172  1172 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=false enabledDesc:null
08-19 17:55:11.746  1172  1745 D STATUSBAR-QSTileView: onStateChanged: Wi-Fi
,08-19 17:55:11.746  1172  1172 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-19 17:55:11.746  1172  1172 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
08-19 17:55:11.746  1172  1172 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-19 17:55:11.746  1172  1172 D HotspotTile: onReceive : 1, 0
,08-19 17:55:11.746  1172  1172 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-19 17:55:11.746  1172  1172 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-19 17:55:11.746  1172  1172 D STATUSBAR-WifiQuickSettingButton: onReceive : android.net.wifi.WIFI_STATE_CHANGED
,08-19 17:55:11.746  1172  1172 D STATUSBAR-WifiQuickSettingButton: Wifi onReceive(1)
08-19 17:55:11.746  1979  2176 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-19 17:55:11.746  1304  1304 D WifiCredService: Action received :android.net.wifi.WIFI_STATE_CHANGED
,08-19 17:55:11.746  6220  6220 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-19 17:55:11.756  6220  6220 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-19 17:55:11.756  1015  3492 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings,
,08-19 17:55:11.756  1015  3492 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,08-19 17:55:11.756  1015  3492 W ActivityManager: userId = 0, bbcId = -10000
,08-19 17:55:11.756  1015  3492 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-19 17:55:11.756  1015  3492 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,08-19 17:55:11.766  1619  1619 I Hs20UtilService: Starting #11
,08-19 17:55:11.766  6394  6394 D SecurityLogAgent: KnoxConfiguration : Current State = 1
,08-19 17:55:11.766  6394  6394 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
08-19 17:55:11.766  6394  6394 D SecurityLogAgent: StateMachine : Current State = 1
,08-19 17:55:11.766  6394  6394 D SecurityLogAgent: StateMachine : Changed Current State = 1
,08-19 17:55:11.766  1619  1650 I Hs20UtilService: Message received 5011
,08-19 17:55:12.486  1015  1042 D Tethering: interfaceRemoved wlan0
,08-19 17:55:12.486  1015  1042 E Tethering: attempting to remove unknown iface (wlan0), ignoring
,08-19 17:55:12.606  1015  1042 D Tethering: interfaceRemoved p2p0,
,08-19 17:55:12.606  1015  1042 E Tethering: attempting to remove unknown iface (p2p0), ignoring
,08-19 17:55:13.386  1015  1123 E WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:1,
,08-19 17:55:13.746   291   291 E SMD     : DCD OFF,
,08-19 17:55:13.826  6220  6275 D BluetoothAdapter: enable()
,08-19 17:55:13.826  1015  1028 W ActivityManager: Permission Denial: getCurrentUser() from pid=6220, uid=10171 requires android.permission.INTERACT_ACROSS_USERS,
,08-19 17:55:13.836  1015  1028 W BluetoothManagerService: Failed getting userId using ActivityManagerNative,
,08-19 17:55:13.836  1015  1028 W BluetoothManagerService: java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=6220, uid=10171 requires android.permission.INTERACT_ACROSS_USERS
08-19 17:55:13.836  1015  1028 W BluetoothManagerService: 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:23972),
08-19 17:55:13.836  1015  1028 W BluetoothManagerService: 	at com.android.server.BluetoothManagerService.CheckItPolicy(BluetoothManagerService.java:2256)
08-19 17:55:13.836  1015  1028 W BluetoothManagerService: 	at com.android.server.BluetoothManagerService.enable(BluetoothManagerService.java:688)
08-19 17:55:13.836  1015  1028 W BluetoothManagerService: 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:98)
08-19 17:55:13.836  1015  1028 W BluetoothManagerService: 	at android.os.Binder.execTransact(Binder.java:446)
,08-19 17:55:13.836  1015  1028 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
08-19 17:55:13.836  1015  1028 D SettingsProvider: name = bluetooth_on
08-19 17:55:13.836  1015  1028 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
08-19 17:55:13.846  1015  1044 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2,
08-19 17:55:13.846  1015  1044 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
,08-19 17:55:13.846  1015  1044 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetooth
08-19 17:55:13.846  1015  1044 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.btservice.AdapterService; callingUser = 0; userId(target) = -2
,08-19 17:55:13.876  6411  6411 D BluetoothAdapterState: make
,08-19 17:55:13.876  6411  6411 I bluedroid: init,
,08-19 17:55:13.876  6411  6453 I BluetoothAdapterState: Entering OffState,
,08-19 17:55:13.886  6411  6411 I bte_conf: bte_load_conf attempt to load stack conf from /etc/bluetooth/bt_stack.conf,
08-19 17:55:13.886  6411  6411 I bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
08-19 17:55:13.886  6411  6411 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
08-19 17:55:13.886  6411  6411 I bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
,08-19 17:55:13.886  6411  6411 E bt-btif : btif_fetch_local_ble_random_bdaddr
08-19 17:55:13.886  6411  6411 I bluedroid: get_profile_interface socket
08-19 17:55:13.886  6411  6411 I bluedroid: get_profile_interface map_client
,08-19 17:55:13.886  6411  6456 I GKI_LINUX: gki_task_entry task_id=1 [BTIF] starting
,08-19 17:55:13.886  6411  6411 D BluetoothAdapterService: checkAddrForIOP: Loading from conf
,08-19 17:55:13.896  6411  6456 D BluetoothAdapterProperties: Address is:08:EC:A9:50:76:27
,08-19 17:55:13.896  6411  6456 E BluetoothServiceJni: populateRssiValuesNative
,08-19 17:55:13.896  6411  6456 I bluedroid: getModelRssiValues
08-19 17:55:13.896  6411  6456 E BluetoothServiceJni: model_rssi_values_callback: low = -70, mid = -60, high = 127
08-19 17:55:13.896  6411  6456 D BluetoothAdapterProperties: modelRssiValuesCallback, low, mid, high = -70,-60,127
,08-19 17:55:13.896  6411  6456 D BluetoothAdapterProperties: Name is: Thali Test (Galaxy A3)
,08-19 17:55:13.896  1015  1015 D SettingsProvider: name = bluetooth_name
,08-19 17:55:13.896  6411  6411 D BluetoothA2dp: doBind(): CallingUid(myUserHandle) = 0
,08-19 17:55:13.896  1015  1133 D ActivityManager: bindService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothA2dp
08-19 17:55:13.896  1015  1133 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
,08-19 17:55:13.896  1015  1133 W ActivityManager: userId = 0, bbcId = -10000
,08-19 17:55:13.896  1015  1133 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-19 17:55:13.896  1015  1133 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-19 17:55:13.906  6411  6424 I bluedroid: config_hci_snoop_log
,08-19 17:55:13.906  1015  1044 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 10 receivers.
,08-19 17:55:13.906  1015  1044 D BluetoothManagerService: Ble is always on enable gatt
,08-19 17:55:13.906  1015  1044 I BluetoothManagerService: enableGattForLeMode, doBind called
,08-19 17:55:13.906  1015  1044 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothGatt
,08-19 17:55:13.906  1015  1044 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.gatt.GattService; callingUser = 0; userId(target) = -2
,08-19 17:55:13.916  1015  1044 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
08-19 17:55:13.916  1015  1044 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
,08-19 17:55:13.916  6411  6411 I BtGatt.JNI: classInitNative(L900): classInitNative: Success!
,08-19 17:55:13.916  1015  1044 D SecContentProvider: uri = 3 selection = isBluetoothEnabled
,08-19 17:55:13.916  6411  6453 D BluetoothAdapterState: CURRENT_STATE=OFF, MSG = USER_TURN_ON
,08-19 17:55:13.916  6411  6453 D BluetoothAdapterProperties: Setting state to 11
,08-19 17:55:13.916  6411  6453 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 11
08-19 17:55:13.916  6411  6453 D BluetoothAdapterService: Bluetooth PBAP supproted is true
,08-19 17:55:13.916  6411  6453 D BluetoothAdapterService: updateAdapterState state is 11
,08-19 17:55:13.916  6411  6453 D BluetoothAdapterService: Autoconnection is available 
08-19 17:55:13.916  6411  6453 D BluetoothAdapterService: updateAdapterState prevState = 10newState = 11
,08-19 17:55:13.926  1015  1015 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
,08-19 17:55:13.926  1015  1015 I InputMethodManagerService: [BT Setting State] State =11
,08-19 17:55:13.926  6411  6453 D BluetoothSecureManager: getInstant: null
08-19 17:55:13.926  6411  6453 D BluetoothSecureManager: calling getMethod for getService
08-19 17:55:13.926  6411  6453 D BluetoothSecureManager: calling getService
,08-19 17:55:13.926  6411  6453 D BluetoothSecureManager: getService return binder: android.os.BinderProxy@30fad964
,08-19 17:55:13.926  1015  1470 D BluetoothSecureManagerService: isSecureModeEnabled
08-19 17:55:13.926  1015  1470 D BluetoothSecureManagerService: getSecureModeSetting, name: secure_mode_enable
08-19 17:55:13.926  6411  6453 D BtConfig.SecureMode: isSecureModeOn:false
08-19 17:55:13.926  6411  6453 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.gatt.GattService
,08-19 17:55:13.936  1172  1172 D BluetoothTile:  onBluetoothPairedDevicesChanged:
08-19 17:55:13.936  6411  6453 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.gatt.GattService
08-19 17:55:13.936  6411  6453 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
,08-19 17:55:13.936  1172  1172 D BluetoothTile: onReceive : android.bluetooth.adapter.action.STATE_CHANGED
08-19 17:55:13.936  1172  1172 D BluetoothTile:  getBluetoothState : 11
,08-19 17:55:13.936  6411  6453 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.hfp.HeadsetService
08-19 17:55:13.936  6411  6453 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
08-19 17:55:13.936  1823  1823 I SamsungIME: STATE_CHANGED = 11, KEYBOARD_BT(0), mBTKeyboardCount =0
,08-19 17:55:13.936  6411  6453 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.a2dp.A2dpService
,08-19 17:55:13.936  6411  6453 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
,08-19 17:55:13.936  6411  6453 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.hid.HidService
08-19 17:55:13.936  6411  6453 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
,08-19 17:55:13.936  1304  1304 V BluetoothEventManager: Received android.bluetooth.adapter.action.STATE_CHANGED
,08-19 17:55:13.936  6411  6453 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.hdp.HealthService
08-19 17:55:13.936  6411  6453 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.pan.PanService
,08-19 17:55:13.936  1015  1027 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,08-19 17:55:13.946  6411  6453 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.pan.PanService
08-19 17:55:13.946  6411  6453 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
08-19 17:55:13.946  1015  1027 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.nearby.discovery.service.DiscoveryService; callingUser = 0; userId(target) = 0
,08-19 17:55:13.946  6411  6453 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.map.BluetoothMapService
,08-19 17:55:13.946  6411  6453 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
,08-19 17:55:13.946  1172  1745 D BluetoothTile:  handleUpdatestate:false name:null
08-19 17:55:13.946  1172  1745 D STATUSBAR-QSTileView: onStateChanged: Bluetooth
,08-19 17:55:13.946  6220  6220 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-19 17:55:13.946  6411  6453 W BluetoothAdapterService: isProfileEnabled(): profile not found com.broadcom.bt.service.sap.SapService
08-19 17:55:13.946  6411  6453 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfpclient.HeadsetClientService
,08-19 17:55:13.946  6411  6453 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.hfpclient.HeadsetClientService
08-19 17:55:13.946  6411  6453 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpSinkService
08-19 17:55:13.946  1015  1027 W ActivityManager: userId = 0, bbcId = -10000
08-19 17:55:13.946  1015  1027 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-19 17:55:13.946  1015  1027 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-19 17:55:13.946  6411  6453 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.a2dp.A2dpSinkService
08-19 17:55:13.946  6411  6453 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.sapclient.SapClientService
,08-19 17:55:13.946  1015  1044 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 0 receivers.
08-19 17:55:13.946  6220  6220 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-19 17:55:13.946  6411  6453 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.sapclient.SapClientService
08-19 17:55:13.946  6411  6453 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidDevService
,08-19 17:55:13.946  1015  1470 D StatusBarManagerService: setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
,08-19 17:55:13.946  1015  1470 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=false
08-19 17:55:13.946  6411  6453 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.hid.HidDevService
,08-19 17:55:13.956  1172  1172 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 )
08-19 17:55:13.956  6411  6453 D BluetoothBondStateMachine: make
,08-19 17:55:13.956  1304  1304 D BluetoothNotiBroadcastReceiver: onReceive
,08-19 17:55:13.956  1172  1172 V BluetoothStatusReceiver: Received android.bluetooth.adapter.action.STATE_CHANGED
08-19 17:55:13.956  1172  1172 D BluetoothStatusReceiver: AdapterStateChanged :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 11
,08-19 17:55:13.956  6411  6453 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.gatt.GattService
08-19 17:55:13.956  6411  6453 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.gatt.GattService
08-19 17:55:13.956  6411  6453 W BluetoothAdapterService: Not skipping com.android.bluetooth.gatt.GattService
,08-19 17:55:13.956  6411  6459 I BluetoothBondStateMachine: StableState(): Entering Off State
,08-19 17:55:13.966  1015  1474 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,08-19 17:55:13.966  1015  1474 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.gatt.GattService; callingUser = 0; userId(target) = 0
,08-19 17:55:13.966  1015  1474 W ActivityManager: userId = 0, bbcId = -10000
08-19 17:55:13.966  1015  1474 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-19 17:55:13.966  1015  1474 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-19 17:55:13.966  6411  6453 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hfp.HeadsetService
08-19 17:55:13.966  6411  6453 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
08-19 17:55:13.966  6411  6453 W BluetoothAdapterService: Not skipping com.android.bluetooth.hfp.HeadsetService
,08-19 17:55:13.966  6411  6411 D BtGatt.DebugUtils: handleDebugAction() action=null
,08-19 17:55:13.966  6411  6411 D BtGatt.GattService: Received start request. Starting profile...
,08-19 17:55:13.966  6411  6411 D BtGatt.GattService: start()
08-19 17:55:13.966  6411  6411 D BtGatt.GattService: start()
08-19 17:55:13.966  6411  6411 I bluedroid: get_profile_interface gatt
,08-19 17:55:13.966  6411  6411 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@8bc66ff
08-19 17:55:13.966  6411  6411 D BtGatt.AdvertiseManager: advertise manager created
,08-19 17:55:13.976  1015  1133 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,08-19 17:55:13.976  1015  1133 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = 0
,08-19 17:55:13.976  1015  1133 W ActivityManager: userId = 0, bbcId = -10000,
08-19 17:55:13.976  1015  1133 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-19 17:55:13.976  1015  1133 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-19 17:55:13.976  6411  6453 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.a2dp.A2dpService
08-19 17:55:13.976  6411  6453 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
08-19 17:55:13.976  6411  6453 W BluetoothAdapterService: Not skipping com.android.bluetooth.a2dp.A2dpService
,08-19 17:55:13.986  1015  1027 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-19 17:55:13.986  1015  1027 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
,08-19 17:55:13.986  1015  1027 W ActivityManager: userId = 0, bbcId = -10000
08-19 17:55:13.986  1015  1027 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-19 17:55:13.986  1015  1027 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-19 17:55:13.986  6411  6411 D BtGatt.GattService: mStartError = false
08-19 17:55:13.986  6411  6411 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@8bc66ff
,08-19 17:55:13.986  6411  6453 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hid.HidService
,08-19 17:55:13.986  6411  6453 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
08-19 17:55:13.986  6411  6453 W BluetoothAdapterService: Not skipping com.android.bluetooth.hid.HidService
,08-19 17:55:13.986  6411  6411 D HeadsetService: Received start request. Starting profile...
,08-19 17:55:13.986  6411  6411 D HeadsetService: start()
,08-19 17:55:13.986  6411  6411 I BluetoothHeadsetServiceJni: classInitNative: succeeds
,08-19 17:55:13.986  6411  6411 D HeadsetStateMachine: make
,08-19 17:55:13.996  6411  6411 E HeadsetStateMachine: # of Max HF connection is 2
,08-19 17:55:14.006  1015  3485 D ActivityManager: bindService callerProcessName:com.android.bluetooth, calleePkgName: com.android.server.telecom, action: android.bluetooth.IBluetoothHeadsetPhone
,08-19 17:55:14.006  1015  3485 D ActivityManager: retrieveServiceLocked(): component = com.android.server.telecom/com.android.server.telecom.BluetoothPhoneService; callingUser = 0; userId(target) = 0
,08-19 17:55:14.006  1015  3485 W ActivityManager: userId = 0, bbcId = -10000
,08-19 17:55:14.006  1015  3485 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-19 17:55:14.006  1015  3485 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.server.telecom,
08-19 17:55:14.006  1015  1475 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-19 17:55:14.006  1015  1475 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hid.HidService; callingUser = 0; userId(target) = 0
,08-19 17:55:14.006  1015  1475 W ActivityManager: userId = 0, bbcId = -10000
,08-19 17:55:14.006  1015  1475 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-19 17:55:14.006  1015  1475 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-19 17:55:14.016  1015  1028 D ActivityManager: bindService callerProcessName:com.android.bluetooth, calleePkgName: com.android.server.telecom, action: com.samsung.bt.hfp.IBluetoothHeadsetVoIP
,08-19 17:55:14.016  1015  1028 D ActivityManager: retrieveServiceLocked(): component = com.android.server.telecom/com.android.server.telecom.BluetoothVoIPService; callingUser = 0; userId(target) = 0
,08-19 17:55:14.016  1015  1028 W ActivityManager: userId = 0, bbcId = -10000
08-19 17:55:14.016  1015  1028 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-19 17:55:14.016  1015  1028 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.server.telecom
,08-19 17:55:14.016  6411  6411 I bluedroid: get_profile_interface handsfree
,08-19 17:55:14.016  1979  1979 D EasyUnlockReceiver: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.easyunlock.authorization.BluetoothStateChangeReceiver (has extras) }.
,08-19 17:55:14.016  6411  6453 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hdp.HealthService
,08-19 17:55:14.026  6411  6453 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
08-19 17:55:14.026  6411  6453 W BluetoothAdapterService: Not skipping com.android.bluetooth.hdp.HealthService
,08-19 17:55:14.026  1015  3485 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-19 17:55:14.026  1015  3485 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hdp.HealthService; callingUser = 0; userId(target) = 0
,08-19 17:55:14.026  1015  3485 W ActivityManager: userId = 0, bbcId = -10000
08-19 17:55:14.026  1015  3485 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,08-19 17:55:14.026  1015  3485 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-19 17:55:14.026  6411  6453 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.pan.PanService
08-19 17:55:14.026  1015  1028 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-19 17:55:14.026  6411  6453 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.pan.PanService
08-19 17:55:14.026  1015  1028 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pan.PanService; callingUser = 0; userId(target) = 0
08-19 17:55:14.026  6411  6453 W BluetoothAdapterService: Not skipping com.android.bluetooth.pan.PanService
08-19 17:55:14.036  1979  1979 D BtServices: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.proximity.BluetoothServicesAdapterStateChangeReceiver (has extras) }.
,08-19 17:55:14.036  1015  1028 W ActivityManager: userId = 0, bbcId = -10000
,08-19 17:55:14.036  1015  1028 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-19 17:55:14.036  1015  1028 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-19 17:55:14.036  6411  6411 I DualScoManager: Instantiating Dual Sco Manager
,08-19 17:55:14.036  6411  6411 I DualScoManager: Set HeadsetServiceHelper,
,08-19 17:55:14.036  6411  6411 D BluetoothAtMessage: createCMTIContentObservers
08-19 17:55:14.046  6411  6453 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.map.BluetoothMapService
08-19 17:55:14.046  6411  6453 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
08-19 17:55:14.046  6411  6453 W BluetoothAdapterService: Not skipping com.android.bluetooth.map.BluetoothMapService
08-19 17:55:14.046  1015  3492 D SettingsProvider: name = bluetooth_hfp_allowed_bvra
08-19 17:55:14.046  1015  3492 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-19 17:55:14.046  1015  3492 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-19 17:55:14.046  1015  3492 D SettingsProvider: selectionArgs: false
08-19 17:55:14.046  1015  3492 D SettingsProvider: selectionArgs: 1002
08-19 17:55:14.046  1015  3492 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-19 17:55:14.046  1015  3492 D SettingsProvider: ret = -1
,08-19 17:55:14.046  6411  6462 D HeadsetStateMachine: Enter Disconnected: -2
08-19 17:55:14.046  1015  3492 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-19 17:55:14.046  1015  3492 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.map.BluetoothMapService; callingUser = 0; userId(target) = 0
,08-19 17:55:14.046  1015  3492 W ActivityManager: userId = 0, bbcId = -10000
08-19 17:55:14.046  1015  3492 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-19 17:55:14.046  1015  3492 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-19 17:55:14.046  6411  6453 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.broadcom.bt.service.sap.SapService
08-19 17:55:14.046  6411  6453 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
08-19 17:55:14.046  6411  6453 W BluetoothAdapterService: Not skipping com.broadcom.bt.service.sap.SapService
,08-19 17:55:14.046  6411  6411 D HeadsetService: mStartError = false
,08-19 17:55:14.046  6411  6411 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@8bc66ff
,08-19 17:55:14.046  1015  1301 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-19 17:55:14.046  1015  1301 W ActivityManager: userId = 0, bbcId = -10000
08-19 17:55:14.046  1015  1301 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.broadcom.bt.service.sap.SapService; callingUser = 0; userId(target) = 0
08-19 17:55:14.046  1015  1301 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-19 17:55:14.046  1015  1301 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-19 17:55:14.046  6411  6462 D HeadsetStateMachine: Clear mHeadsetBrsf
,08-19 17:55:14.056  6411  6462 D HeadsetStateMachine: map size, before remove : 0
,08-19 17:55:14.056  6411  6453 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hfpclient.HeadsetClientService
08-19 17:55:14.056  6411  6453 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfpclient.HeadsetClientService
08-19 17:55:14.056  6411  6453 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.hfpclient.HeadsetClientService
,08-19 17:55:14.056  6411  6453 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.a2dp.A2dpSinkService
08-19 17:55:14.056  6411  6453 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpSinkService
08-19 17:55:14.056  6411  6453 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.a2dp.A2dpSinkService
08-19 17:55:14.056  6411  6453 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.sapclient.SapClientService
08-19 17:55:14.056  6411  6453 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.sapclient.SapClientService
08-19 17:55:14.056  6411  6453 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.sapclient.SapClientService
08-19 17:55:14.056  6411  6453 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hid.HidDevService
08-19 17:55:14.056  6411  6453 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidDevService
08-19 17:55:14.056  6411  6453 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.hid.HidDevService
08-19 17:55:14.056  6411  6453 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=true, isTurningOff()=false
08-19 17:55:14.056  6411  6462 D HeadsetStateMachine: map size, after remove: 0
08-19 17:55:14.056  6411  6411 E BluetoothAdapterService(146564863): processProfileServiceStateChanged() serviceName=com.android.bluetooth.gatt.GattService, state=12, doUpdate=false
,08-19 17:55:14.056  6411  6411 D A2dpService: Received start request. Starting profile...
,08-19 17:55:14.056  6411  6411 D A2dpService: start()
,08-19 17:55:14.056  6411  6411 I BluetoothAvrcpServiceJni: classInitNative: succeeds
,08-19 17:55:14.056  6411  6411 I bluedroid: get_profile_interface avrcp
,08-19 17:55:14.066  6411  6411 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,08-19 17:55:14.066  6411  6411 D Avrcp   : Initialize Media Controller
,08-19 17:55:14.066  6411  6411 D Avrcp   : Get the Context Package Name: com.android.bluetooth
,08-19 17:55:14.066  6411  6411 E Avrcp   : getActiveSessions
,08-19 17:55:14.066  6411  6411 D Avrcp   : pick active media Controller
,08-19 17:55:14.066  6411  6411 D Avrcp   : Get the active Media Controller 
,08-19 17:55:14.086  6411  6411 I Avrcp   :  Updating now playing list upon AVRCP Start
,08-19 17:55:14.086  6411  6466 D BluetoothMediaBrowser:  getNowPlayingListcontent://media/external/audio/playlists?secFilter=include
08-19 17:55:14.086  6411  6411 I BluetoothA2dpServiceJni: classInitNative: succeeds
08-19 17:55:14.086  6411  6411 D A2dpStateMachine: make
,08-19 17:55:14.086  6411  6411 I bluedroid: get_profile_interface a2dp
,08-19 17:55:14.086  6411  6468 I GKI_LINUX: gki_task_entry task_id=2 [A2DP-MEDIA] starting
08-19 17:55:14.086  6411  6411 E bt-btif : warning : media task started media_task_refcnt 1 
,08-19 17:55:14.086  6411  6411 D A2dpService: mStartError = false
08-19 17:55:14.086  6411  6411 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@8bc66ff
,08-19 17:55:14.086  6411  6411 D HeadsetStateMachine: Try to query the phonestate on bind
,08-19 17:55:14.096  1412  1431 I Telecom : BluetoothPhoneService: queryPhoneState
,08-19 17:55:14.096  6411  6467 D A2dpStateMachine: Enter Disconnected: -2
08-19 17:55:14.096  1412  1412 I Telecom : BluetoothPhoneService: handleMessage(7) / param 0
08-19 17:55:14.096  1412  1412 I Telecom : BluetoothPhoneService: updateHeadsetWithCallState
,08-19 17:55:14.096  1412  1431 I Telecom : BluetoothPhoneService: Result of Message : true
,08-19 17:55:14.096  6411  6411 I BluetoothHidServiceJni: classInitNative: succeeds
,08-19 17:55:14.096  6411  6411 D HidService: Received start request. Starting profile...
08-19 17:55:14.096  6411  6411 D HidService: start()
,08-19 17:55:14.096  6411  6411 I bluedroid: get_profile_interface hidhost
08-19 17:55:14.096  6411  6411 D HidService: setHidService(): set to: null
08-19 17:55:14.096  6411  6411 D HidService: mStartError = false
08-19 17:55:14.096  6411  6411 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@8bc66ff
,08-19 17:55:14.096  6411  6411 D HeadsetStateMachine: Proxy object connected
,08-19 17:55:14.096  6411  6411 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=0
08-19 17:55:14.096  6411  6462 D HeadsetStateMachine: Disconnected process message: 11
,08-19 17:55:14.096  6411  6411 I BluetoothHealthServiceJni: classInitNative: succeeds
,08-19 17:55:14.106  6411  6411 D HealthService: Received start request. Starting profile...
08-19 17:55:14.106  6411  6411 D HealthService: start()
,08-19 17:55:14.106  6411  6466 D BluetoothMediaBrowser: no now playing list
,08-19 17:55:14.106  6411  6466 D BluetoothMediaBrowser:  getNowPlayingId now playing id : -1
08-19 17:55:14.106  6411  6411 I bluedroid: get_profile_interface health
,08-19 17:55:14.106  6411  6411 D HealthService: mStartError = false
08-19 17:55:14.106  6411  6411 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@8bc66ff
08-19 17:55:14.106  6411  6411 D HeadsetPhoneState: sendDeviceDataStateChanged
08-19 17:55:14.106  6411  6462 D HeadsetStateMachine: Disconnected process message: 18
08-19 17:55:14.106  6411  6411 D HeadsetPhoneState: Signal level : previous=0 curr=0
,08-19 17:55:14.106  6411  6411 I BluetoothPanServiceJni: classInitNative(L105): succeeds
,08-19 17:55:14.106  6411  6411 D PanService: Received start request. Starting profile...
,08-19 17:55:14.106  6411  6411 D PanService: start()
,08-19 17:55:14.106  6411  6411 D BluetoothPanServiceJni: initializeNative(L110): pan
08-19 17:55:14.106  6411  6411 I bluedroid: get_profile_interface pan
,08-19 17:55:14.106  6411  6411 D PanService: mStartError = false
,08-19 17:55:14.106  6411  6411 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@8bc66ff
,08-19 17:55:14.116  6411  6411 E BluetoothAdapterService(146564863): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hfp.HeadsetService, state=12, doUpdate=true
,08-19 17:55:14.116  6411  6411 D BluetoothMapService: Received start request. Starting profile...
,08-19 17:55:14.116  6411  6411 D BluetoothMapService: start()
,08-19 17:55:14.116  6411  6411 D BluetoothMapService: mStartError = false
,08-19 17:55:14.116  6411  6411 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@8bc66ff
08-19 17:55:14.116  6411  6411 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,08-19 17:55:14.116  6411  6462 D HeadsetStateMachine: Disconnected process message: 10,
08-19 17:55:14.116  6411  6462 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
08-19 17:55:14.116  6411  6462 D HeadsetStateMachine: Disconnected process message: 11
,08-19 17:55:14.116  6411  6411 I BluetoothSAPServiceJni: classInitNative(L204): succeeds
,08-19 17:55:14.126  6411  6411 D SapService: Received start request. Starting profile...
,08-19 17:55:14.126  6411  6411 D SapService: start()
08-19 17:55:14.126  6411  6411 D BluetoothSAPServiceJni: initializeNative(L209): sap
,08-19 17:55:14.126  6411  6411 I bluedroid: get_profile_interface sap
08-19 17:55:14.126  6411  6411 D SapService: mStartError = false
,08-19 17:55:14.126  6411  6411 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@8bc66ff
08-19 17:55:14.126  6411  6411 D BluetoothA2dp: Proxy object connected
08-19 17:55:14.126  6411  6411 D BluetoothAdapterService: Bluetooth A2dp source service connected
,08-19 17:55:14.126  6411  6411 E BluetoothAdapterService(146564863): processProfileServiceStateChanged() serviceName=com.android.bluetooth.a2dp.A2dpService, state=12, doUpdate=true
08-19 17:55:14.126  6411  6411 E BluetoothAdapterService(146564863): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hid.HidService, state=12, doUpdate=true
,08-19 17:55:14.126  6411  6411 E BluetoothAdapterService(146564863): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hdp.HealthService, state=12, doUpdate=true
08-19 17:55:14.126  6411  6411 E BluetoothAdapterService(146564863): processProfileServiceStateChanged() serviceName=com.android.bluetooth.pan.PanService, state=12, doUpdate=true
,08-19 17:55:14.126  1015  1475 D ActivityManager: getContentProviderImpl callerProcessName:com.android.bluetooth, calleePkgName: com.android.email
,08-19 17:55:14.126  1015  1475 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-19 17:55:14.126  1015  1475 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-19 17:55:14.136  1015  1475 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-19 17:55:14.136  1015  1475 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-19 17:55:14.146  1015  1475 I ActivityManager: Start proc com.android.email for content provider com.android.email/.provider.EmailProvider: pid=6472 uid=10141 gids={50141, 9997, 3003, 1028, 1015, 1023, 3002, 3001, 1003} abi=armeabi-v7a
,08-19 17:55:14.146  6472  6472 E Zygote  : MountEmulatedStorage(),
08-19 17:55:14.146  6472  6472 I libpersona: KNOX_SDCARD checking this for 10141
08-19 17:55:14.146  6472  6472 E Zygote  : v2
08-19 17:55:14.146  6472  6472 I libpersona: KNOX_SDCARD not a persona,
08-19 17:55:14.146  6472  6472 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-19 17:55:14.146  6472  6472 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-19 17:55:14.156  6472  6472 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-19 17:55:14.166  6472  6472 D TimaKeyStoreProvider: TimaSignature is unavailable,
,08-19 17:55:14.176  6472  6472 D ActivityThread: Added TimaKeyStore provider
,08-19 17:55:14.186  6472  6472 W ResourcesManager: Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
,08-19 17:55:14.186  6472  6472 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-19 17:55:14.186  6472  6472 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
08-19 17:55:14.186  6472  6472 W ResourcesManager: Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,08-19 17:55:14.236  1015  1133 D RCPManagerService: exchangeData() failure , invalid userId
,08-19 17:55:14.256  1015  3494 D RCPManagerService: exchangeData() failure , invalid userId
,08-19 17:55:14.306  6411  6411 E BluetoothAdapterService(146564863): processProfileServiceStateChanged() serviceName=com.android.bluetooth.map.BluetoothMapService, state=12, doUpdate=true
08-19 17:55:14.306  6411  6411 E BluetoothAdapterService(146564863): processProfileServiceStateChanged() serviceName=com.broadcom.bt.service.sap.SapService, state=12, doUpdate=true
,08-19 17:55:14.316  6411  6453 D BluetoothAdapterState: CURRENT_STATE=PENDING, MSG = STARTED, isTurningOn=true, isTurningOff=false
,08-19 17:55:14.316  6411  6453 I bluedroid: enable
08-19 17:55:14.316  6411  6453 I bt_hci_bdroid: init
,08-19 17:55:14.316  6411  6491 I GKI_LINUX: gki_task_entry task_id=0 [BTU] starting
,08-19 17:55:14.316  1015  3494 D ActivityManager: getContentProviderImpl callerProcessName:com.android.email, calleePkgName: com.sec.android.provider.badge
,08-19 17:55:14.316  6411  6453 I bt_vendor: bt-vendor : init
08-19 17:55:14.316  6411  6453 I bt_vendor: bt-vendor : get_bt_soc_type
08-19 17:55:14.316  6411  6453 E bt_vendor: get_bt_soc_type: Failed to get soc type
08-19 17:55:14.316  6411  6453 I bt_vendor: init: Local BD Address : 27:76:50:a9:ec:08
08-19 17:55:14.316  6411  6453 D bt_userial_mct: userial_init
,08-19 17:55:14.316  1015  3494 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-19 17:55:14.316  1015  3494 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-19 17:55:14.316  1015  3494 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-19 17:55:14.316  1015  3494 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-19 17:55:14.316  6411  6453 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: Off
,08-19 17:55:14.326  6411  6453 I bt_vendor: Starting hciattach daemon
08-19 17:55:14.326  6411  6453 I bt_vendor: try to set false
,08-19 17:55:14.326  6411  6453 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: On
,08-19 17:55:14.326  6411  6453 I bt_vendor: Starting hciattach daemon
08-19 17:55:14.326  6411  6453 I bt_vendor: try to set true
,08-19 17:55:14.326  1015  3485 D RCPManagerService: exchangeData() failure , invalid userId
,08-19 17:55:14.336  6497  6497 E Zygote  : MountEmulatedStorage(),
08-19 17:55:14.336  6497  6497 E Zygote  : v2
08-19 17:55:14.336  6497  6497 I libpersona: KNOX_SDCARD checking this for 10068
08-19 17:55:14.336  6497  6497 I libpersona: KNOX_SDCARD not a persona
,08-19 17:55:14.336  6497  6497 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51,
08-19 17:55:14.336  1015  3494 I ActivityManager: Start proc com.sec.android.provider.badge for content provider com.sec.android.provider.badge/.BadgeProvider: pid=6497 uid=10068 gids={50068, 9997} abi=armeabi-v7a
,08-19 17:55:14.336  6497  6497 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051,
08-19 17:55:14.336  6497  6497 E SELinux : [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,08-19 17:55:14.346  1015  1027 D RCPManagerService: exchangeData() failure , invalid userId
,08-19 17:55:14.346  6503  6503 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: init.qcom.bt.sh config =  
,08-19 17:55:14.376  6497  6497 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-19 17:55:14.376  6497  6497 D ActivityThread: Added TimaKeyStore provider
,08-19 17:55:14.376  1015  1475 D RCPManagerService: exchangeData() failure , invalid userId
,08-19 17:55:14.376  1015  1768 I ActivityManager: Killing 5897:com.sec.spp.push/u0a32 (adj 15): empty #21
,08-19 17:55:14.386  1015  1446 D RCPManagerService: exchangeData() failure , invalid userId
,08-19 17:55:14.396  6520  6520 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Transport : smd 
,08-19 17:55:14.406  6497  6497 D BadgeProvider: onCreate,
08-19 17:55:14.406  6497  6497 D BadgeProvider: DatabaseHelper
,08-19 17:55:14.416  6521  6521 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** 
,08-19 17:55:14.426  6497  6510 D BadgeProvider: query, [selection] : package='com.android.email' AND class='com.android.email.activity.Welcome' AND extraData='base_extra_badge'
,08-19 17:55:14.436  6523  6523 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Power Class: Ignored. Default(1) used (1-CLASS1/2-CLASS2/3-CUSTOM) ,
,08-19 17:55:14.446  6524  6524 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Power Class: To override, Before turning BT ON; setprop qcom.bt.dev_power_class <1 or 2 or 3> 
,08-19 17:55:14.456  6525  6525 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: LE Power Class: Ignored. Default(2) used (1-CLASS1/2-CLASS2/3-CUSTOM) 
,08-19 17:55:14.456  6497  6510 D BadgeProvider: sendNotify entered. [uri] : content://com.sec.badge/apps/1,
,08-19 17:55:14.456  6497  6510 D BadgeProvider: sendNotify, [notify] : null
08-19 17:55:14.456  6497  6510 D BadgeProvider: update, [uri] : content://com.sec.badge/apps/1
08-19 17:55:14.456  6497  6510 D BadgeProvider: update, [BadgeCount] : badgecount=0
08-19 17:55:14.456  6497  6510 D BadgeProvider: update, [UpdateCount] : 1,
,08-19 17:55:14.466  6526  6526 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: LE Power Class: To override, Before turning BT ON; setprop qcom.bt.le_dev_pwr_class <1 or 2 or 3> 
,08-19 17:55:14.466  1476  1476 D Launcher.Model: reloadBadges entered.
,08-19 17:55:14.576  1015  1446 D ActivityManager: retrieveServiceLocked(): component = com.android.email/com.android.email.service.AttachmentDownloadService; callingUser = 0; userId(target) = 0
08-19 17:55:14.576  1015  1446 W ActivityManager: Unable to start service Intent { cmp=com.android.email/.service.AttachmentDownloadService } U=0: not found
,08-19 17:55:14.576  1015  1133 D ActivityManager: retrieveServiceLocked(): component = com.android.email/com.android.email.service.EmailDebugService; callingUser = 0; userId(target) = 0
,08-19 17:55:14.586  1015  3492 D ActivityManager: retrieveServiceLocked(): component = com.android.email/com.android.email.legacypush.ImapPushService; callingUser = 0; userId(target) = 0
,08-19 17:55:14.666  6530  6530 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Bluetooth QSoC firmware download succeeded, /dev/ttyHS0 qualcomm 3000000 08:ec:a9:50:76:27 ,
,08-19 17:55:14.676  6531  6531 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** ,
,08-19 17:55:14.736  6411  6453 I bt_vendor: bluetooth satus is on,
08-19 17:55:14.736  6411  6493 D bt_userial_mct: userial_open(port:0)
,08-19 17:55:14.736  6411  6493 I bt_vendor: bt-vendor : BT_VND_OP_USERIAL_OPEN
08-19 17:55:14.736  6411  6493 I bt_vendor: Done intiailizing UART
08-19 17:55:14.736  6411  6493 I bt_vendor: Done intiailizing UART
08-19 17:55:14.736  6411  6493 I bt_userial_mct: CMD=66, EVT=66, ACL_Out=67, ACL_In=67
08-19 17:55:14.736  6411  6493 I bt_vendor: Bluetooth Firmware and transport layer are initialized
,08-19 17:55:14.746  6411  6533 D bt_userial_mct: Entering userial_read_thread(),
,08-19 17:55:14.746  6411  6491 I         : BTE_InitTraceLevels -- TRC_HCI
,08-19 17:55:14.746  6411  6491 I         : BTE_InitTraceLevels -- TRC_L2CAP
08-19 17:55:14.746  6411  6491 I         : BTE_InitTraceLevels -- TRC_RFCOMM
,08-19 17:55:14.746  6411  6491 I         : BTE_InitTraceLevels -- TRC_AVDT
08-19 17:55:14.746  6411  6491 I         : BTE_InitTraceLevels -- TRC_AVRC
,08-19 17:55:14.746  6411  6491 I         : BTE_InitTraceLevels -- TRC_A2D
08-19 17:55:14.746  6411  6491 I         : BTE_InitTraceLevels -- TRC_BNEP
,08-19 17:55:14.746  6411  6491 I         : BTE_InitTraceLevels -- TRC_BTM
,08-19 17:55:14.746  6411  6491 I         : BTE_InitTraceLevels -- TRC_GAP
08-19 17:55:14.746  6411  6491 I         : BTE_InitTraceLevels -- TRC_PAN
,08-19 17:55:14.746  6411  6491 I         : BTE_InitTraceLevels -- TRC_SAP
08-19 17:55:14.746  6411  6491 I         : BTE_InitTraceLevels -- TRC_SDP
,08-19 17:55:14.746  6411  6491 I         : BTE_InitTraceLevels -- TRC_GATT
08-19 17:55:14.756  6411  6491 I         : BTE_InitTraceLevels -- TRC_SMP
08-19 17:55:14.756  6411  6491 I         : BTE_InitTraceLevels -- TRC_BTAPP
08-19 17:55:14.756  6411  6491 I         : BTE_InitTraceLevels -- TRC_BTIF
08-19 17:55:14.756  6411  6491 I         : BTE_InitTraceLevels -- TRC_PROTOCOL
,08-19 17:55:14.846  6411  6491 W bt-l2cap: l2c_link_processs_ble_num_bufs 16
,08-19 17:55:14.846  6411  6491 E bt-btm  : BTM_SecRegister:p_cb_info->p_le_callback == 0xa41c1ed1 
,08-19 17:55:14.846  6411  6491 E bt-btm  : BTM_SecRegister: btm_cb.api.p_le_callback = 0xa41c1ed1 
,08-19 17:55:14.866  6411  6456 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 10 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 32 mNumOfOffloadedScanFilterSupported = 16 mOffloadedScanResultStorageBytes= 10240 mIsActivityAndEnergyReporting = true mAobleSupported = 0
,08-19 17:55:14.866  6411  6456 E bt-btif : Calling BTA_HhEnable
,08-19 17:55:14.866  6411  6456 E bt-btif : btif_storage_get_adapter_property service_mask:0x2120048
,08-19 17:55:14.866  6411  6456 D BluetoothAdapterProperties: Address is:08:EC:A9:50:76:27
,08-19 17:55:14.866  6411  6456 E BluetoothServiceJni: populateRssiValuesNative
,08-19 17:55:14.866  6411  6456 I bluedroid: getModelRssiValues
,08-19 17:55:14.876  6411  6456 E BluetoothServiceJni: model_rssi_values_callback: low = -70, mid = -60, high = 127
08-19 17:55:14.876  6411  6456 D BluetoothAdapterProperties: modelRssiValuesCallback, low, mid, high = -70,-60,127
,08-19 17:55:14.876  6411  6456 D BluetoothAdapterProperties: Name is: Thali Test (Galaxy A3)
,08-19 17:55:14.876  1015  1015 D SettingsProvider: name = bluetooth_name
,08-19 17:55:14.876  6220  6220 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-19 17:55:14.876  6220  6220 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-19 17:55:14.886  6411  6456 D BluetoothUtils: getBtEnabledContainers(): btContainers = []
,08-19 17:55:14.886  6411  6456 D BluetoothAdapterProperties: Scan Mode:20
,08-19 17:55:14.886  6411  6456 D BluetoothAdapterProperties: Discoverable Timeout:120
,08-19 17:55:14.886  6411  6456 D BluetoothAdapterProperties: LE Address is:C8:D9:53:A0:EC:4E
08-19 17:55:14.886  6411  6456 E bt-btif : btif_handle_bluetooth_enable_evt: btif_core_radio_ref_count:1
08-19 17:55:14.886  6411  6456 E bt-btif : btif_sock_init, radio_req:0, rfc_init:0, vhci_init:0
,08-19 17:55:14.886  6411  6456 E bt-btif : btif_sock_init: !radio_req && !rfc_init
08-19 17:55:14.886  6411  6456 E bt-btif : btif_sock_init: !vhci_init
,08-19 17:55:14.886  6411  6456 D IOP_DB_BT: db_open: file /etc/bluetooth/iop_bt.db
,08-19 17:55:14.896  6411  6456 D IOP_DB_BT: db_open: db_open : handle 3028148240l, read 13894 bytes onto local cache
,08-19 17:55:14.896  6411  6456 D IOP_DB_BT: db_query: id __IOPFLAGS :: key __KEY_ENABLE_VERBOSE, value 1
,08-19 17:55:14.896  6411  6533 E bt_mct  : hci lib postload completed
08-19 17:55:14.896  6411  6456 D IOP_DB_BT: db_query: result 1
08-19 17:55:14.896  6411  6456 I         : iop_db_open: iop_db_open status 0
,08-19 17:55:14.896  6411  6456 D bte_conf: Device ID record 1 : primary
,08-19 17:55:14.896  6411  6456 D bte_conf:   vendorId            = 0075
08-19 17:55:14.896  6411  6456 D bte_conf:   vendorIdSource      = 0001
08-19 17:55:14.896  6411  6456 D bte_conf:   product             = 0100
08-19 17:55:14.896  6411  6456 D bte_conf:   version             = 0200
08-19 17:55:14.896  6411  6456 D bte_conf:   clientExecutableURL = 
08-19 17:55:14.896  6411  6456 D bte_conf:   serviceDescription  = 
08-19 17:55:14.896  6411  6456 D bte_conf:   documentationURL    = 
08-19 17:55:14.896  6411  6456 D bte_conf: bte_load_did_conf no section named DID2.
,08-19 17:55:14.896  6411  6456 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
,08-19 17:55:14.896  6411  6453 D BluetoothAdapterState: CURRENT_STATE=PENDING, MSG = ENABLE_READY, isTurningOn=true, isTurningOff=false
,08-19 17:55:14.896  6411  6453 D BluetoothAdapterProperties: ScanMode =  20
,08-19 17:55:14.896  6411  6453 D BluetoothAdapterProperties: State =  11
,08-19 17:55:14.906  1015  3492 D SecContentProvider: uri = 3 selection = isDiscoverableEnabled
,08-19 17:55:14.906  6411  6453 D BluetoothAdapterProperties: Setting state to 12
,08-19 17:55:14.906  6411  6453 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
,08-19 17:55:14.906  6411  6456 D BluetoothUtils: getBtEnabledContainers(): btContainers = []
08-19 17:55:14.906  6411  6456 D BluetoothAdapterProperties: Scan Mode:21
08-19 17:55:14.906  6411  6456 D BluetoothAdapterProperties: Discoverable Timeout:120
,08-19 17:55:14.906  1015  1027 D SettingsProvider: name = bluetooth_a2dp_sink_mode
,08-19 17:55:14.906  1015  1027 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
,08-19 17:55:14.916  1015  1027 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-19 17:55:14.916  1015  1027 D SettingsProvider: selectionArgs: false
08-19 17:55:14.916  1015  1027 D SettingsProvider: selectionArgs: 1002
,08-19 17:55:14.916  1015  1027 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
,08-19 17:55:14.916  1015  1027 D SettingsProvider: ret = -1
,08-19 17:55:14.916  6411  6453 D BluetoothAdapterService: Bluetooth PBAP supproted is true
,08-19 17:55:14.916  6411  6453 D BluetoothAdapterService: updateAdapterState state is 12
,08-19 17:55:14.916  1015  1474 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-19 17:55:14.916  1015  1474 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pbap.BluetoothPbapService; callingUser = 0; userId(target) = 0
,08-19 17:55:14.916  1015  1474 W ActivityManager: userId = 0, bbcId = -10000
,08-19 17:55:14.916  1015  1474 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-19 17:55:14.916  1015  1474 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-19 17:55:14.916  6411  6453 D BluetoothAdapterService: Autoconnection is available 
,08-19 17:55:14.926  6411  6453 D BluetoothAdapterService: updateAdapterState prevState = 11newState = 12
08-19 17:55:14.926  6411  6453 D BluetoothAdapterService: starting service from this receiver
,08-19 17:55:14.926  1015  1475 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,08-19 17:55:14.926  1015  1475 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.samsung.ble.BleAutoConnectService; callingUser = 0; userId(target) = 0
,08-19 17:55:14.926  1015  1475 W ActivityManager: userId = 0, bbcId = -10000
,08-19 17:55:14.926  1015  1475 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,08-19 17:55:14.926  1015  1475 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-19 17:55:14.936  6411  6453 I BluetoothAdapterState: Entering On State from state = 11
,08-19 17:55:14.936  6220  6220 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-19 17:55:14.936  6220  6220 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-19 17:55:14.936  6220  6220 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-19 17:55:14.936  6220  6220 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-19 17:55:14.936  6220  6220 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-19 17:55:14.936  6220  6220 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-19 17:55:14.936  6220  6220 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-19 17:55:14.936  6220  6220 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-19 17:55:14.936  1412  6355 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,08-19 17:55:14.936  1015  1044 D ActivityManager: bindService callerProcessName:com.android.server.telecom, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
08-19 17:55:14.936  1015  1044 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,08-19 17:55:14.936  1015  1044 W ActivityManager: userId = 0, bbcId = -10000
08-19 17:55:14.936  1015  1044 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-19 17:55:14.936  1015  1044 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.server.telecom, destAppInfo.processName = com.android.bluetooth
,08-19 17:55:14.936  1412  6355 E BluetoothHeadset: BluetoothHeadset service is binded
08-19 17:55:14.936  6220  6220 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-19 17:55:14.936  1015  1044 D BluetoothPan: Binding service...
,08-19 17:55:14.946  1015  1044 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothPan
,08-19 17:55:14.946  1015  1044 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pan.PanService; callingUser = 0; userId(target) = 0
,08-19 17:55:14.946  1304  1315 D Bluetoothsap: onBluetoothStateChange: up=true
,08-19 17:55:14.946  1304  1315 D Bluetoothsap: Binding service...
,08-19 17:55:14.946  1304  1315 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:2136 android.content.ContextWrapper.bindService:559 com.broadcom.bt.service.sap.BluetoothSap.doBind:186 com.broadcom.bt.service.sap.BluetoothSap$1.onBluetoothStateChange:156 android.bluetooth.IBluetoothStateChangeCallback$Stub.onTransact:55 
,08-19 17:55:14.946  1015  1044 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: com.broadcom.bt.service.sap.IBluetoothSap
08-19 17:55:14.956  1015  1044 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.broadcom.bt.service.sap.SapService; callingUser = 0; userId(target) = 0
,08-19 17:55:14.956  1015  1044 W ActivityManager: userId = 0, bbcId = -10000
08-19 17:55:14.956  1015  1044 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-19 17:55:14.956  1015  1044 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,08-19 17:55:14.956  1304  1315 D Bluetoothsap: bindService called to Bluetooth SAP Service
,08-19 17:55:14.956  6411  6411 I BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED, state: 12
,08-19 17:55:14.956  6220  6220 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-19 17:55:14.956  6220  6220 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-19 17:55:14.956  6220  6220 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-19 17:55:14.956  6220  6220 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-19 17:55:14.956  6220  6220 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-19 17:55:14.956  6220  6220 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-19 17:55:14.956  6220  6220 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-19 17:55:14.956  6220  6220 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-19 17:55:14.956  1304  1325 D BluetoothPbap: onBluetoothStateChange: up=true
,08-19 17:55:14.956  6220  6220 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-19 17:55:14.966  1015  1044 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothPbap
08-19 17:55:14.966  1015  1044 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pbap.BluetoothPbapService; callingUser = 0; userId(target) = 0
,08-19 17:55:14.966  1015  1044 W ActivityManager: userId = 0, bbcId = -10000
08-19 17:55:14.966  1015  1044 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-19 17:55:14.966  1015  1044 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,08-19 17:55:14.966  1304  6303 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,08-19 17:55:14.966  1015  1044 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
08-19 17:55:14.966  1015  1044 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,08-19 17:55:14.966  1015  1044 W ActivityManager: userId = 0, bbcId = -10000
08-19 17:55:14.966  1015  1044 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-19 17:55:14.966  1015  1044 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,08-19 17:55:14.966  1304  6303 E BluetoothHeadset: BluetoothHeadset service is binded
,08-19 17:55:14.966  1172  1185 D BluetoothAdapter: onBluetoothStateChange: up=true
,08-19 17:55:14.966  1172  1185 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,08-19 17:55:14.966  6323  6333 D BluetoothAdapter: onBluetoothStateChange: up=true
08-19 17:55:14.966  6323  6333 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,08-19 17:55:14.976  1304  1304 D HeadsetProfile: Bluetooth service connected
,08-19 17:55:14.976  1412  1438 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,08-19 17:55:14.976  1015  1044 D ActivityManager: bindService callerProcessName:com.android.server.telecom, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
,08-19 17:55:14.976  1015  1015 D BluetoothPan: BluetoothPAN Proxy object connected
,08-19 17:55:14.976  1015  1044 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,08-19 17:55:14.976  1015  1044 W ActivityManager: userId = 0, bbcId = -10000
08-19 17:55:14.976  1015  1044 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-19 17:55:14.976  1015  1044 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.server.telecom, destAppInfo.processName = com.android.bluetooth
,08-19 17:55:14.976  1412  1438 E BluetoothHeadset: BluetoothHeadset service is binded
,08-19 17:55:14.976  6411  6411 I BluetoothPbapService: Handler(): got msg=1
,08-19 17:55:14.976  1979  2172 D BluetoothAdapter: onBluetoothStateChange: up=true
08-19 17:55:14.976  1979  2172 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,08-19 17:55:14.976  6220  6228 D BluetoothAdapter: onBluetoothStateChange: up=true
08-19 17:55:14.976  6220  6228 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,08-19 17:55:14.976  1015  1044 D BluetoothAdapter: onBluetoothStateChange: up=true
08-19 17:55:14.976  1015  1044 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,08-19 17:55:14.976  6411  6422 D BluetoothA2dp: onBluetoothStateChange: up=true
08-19 17:55:14.976  1015  1044 D BluetoothA2dp: onBluetoothStateChange: up=true
08-19 17:55:14.976  1015  1044 D BluetoothA2dp: doBind(): CallingUid(myUserHandle) = 0
,08-19 17:55:14.976  1015  1044 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothA2dp
08-19 17:55:14.976  1015  1044 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
08-19 17:55:14.986  1015  1768 D SecContentProvider: uri = 4 selection = isProfileAuthorizedBySecurityPolicy
,08-19 17:55:14.986  1412  1431 D BluetoothAdapter: onBluetoothStateChange: up=true
08-19 17:55:14.986  1412  1431 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
08-19 17:55:14.986  1304  1304 D Bluetoothsap: BluetoothSAP Proxy object connected
08-19 17:55:14.986  1304  1304 D SapProfile: Bluetooth service connected
08-19 17:55:14.986  1304  1304 D Bluetoothsap: getConnectedDevices()
08-19 17:55:14.986  1015  1015 D BluetoothA2dp: Proxy object connected
08-19 17:55:14.986  1304  6303 D BluetoothAdapter: onBluetoothStateChange: up=true
08-19 17:55:14.986  1304  6303 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,08-19 17:55:14.986  1412  6355 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,08-19 17:55:14.986  1015  1044 D ActivityManager: bindService callerProcessName:com.android.server.telecom, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset,
08-19 17:55:14.986  1015  1044 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,08-19 17:55:14.986  1015  1044 W ActivityManager: userId = 0, bbcId = -10000
08-19 17:55:14.986  1015  1044 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-19 17:55:14.986  1015  1044 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.server.telecom, destAppInfo.processName = com.android.bluetooth
,08-19 17:55:14.986  1412  6355 E BluetoothHeadset: BluetoothHeadset service is binded
,08-19 17:55:14.986  1304  1325 D BluetoothPan: Binding service...
,08-19 17:55:14.986  1304  1304 D BluetoothPbap: Proxy object connected
08-19 17:55:14.986  1304  1304 D PbapServerProfile: Bluetooth service connected
,08-19 17:55:14.986  6411  6537 V BluetoothPbapService: PBAP Service initSocket try: 0
08-19 17:55:14.986  1015  1044 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothPan
08-19 17:55:14.986  1015  1044 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pan.PanService; callingUser = 0; userId(target) = 0
08-19 17:55:14.986  1015  1044 W ActivityManager: userId = 0, bbcId = -10000
08-19 17:55:14.986  1015  1044 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-19 17:55:14.986  1015  1044 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,08-19 17:55:14.986  1304  6303 D BluetoothMap: onBluetoothStateChange: up=true
08-19 17:55:14.996  1304  1304 D BluetoothPan: BluetoothPAN Proxy object connected
08-19 17:55:14.996  1304  1304 D PanProfile: Bluetooth service connected
,08-19 17:55:14.996  1015  1044 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothMap
08-19 17:55:14.996  1015  1044 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.map.BluetoothMapService; callingUser = 0; userId(target) = 0
,08-19 17:55:14.996  1015  1044 W ActivityManager: userId = 0, bbcId = -10000
,08-19 17:55:14.996  1015  1044 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,08-19 17:55:14.996  1015  1044 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,08-19 17:55:14.996  1015  1044 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,08-19 17:55:14.996  1015  1044 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
08-19 17:55:14.996  1304  1304 D BluetoothMap: Proxy object connected
08-19 17:55:14.996  1015  1044 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,08-19 17:55:14.996  6411  6537 D BluetoothSocket: bindListen(): myUserId = 0
08-19 17:55:14.996  6411  6537 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-19 17:55:14.996  1304  1304 D MapProfile: Bluetooth service connected
08-19 17:55:14.996  1015  1044 E BluetoothHeadset: BluetoothHeadset service is binded
,08-19 17:55:14.996  1447  1660 D BluetoothAdapter: onBluetoothStateChange: up=true
08-19 17:55:14.996  1447  1660 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,08-19 17:55:15.006  1304  1304 D BluetoothMap: getConnectedDevices()
08-19 17:55:15.006  6411  6457 D BluetoothAdapter: onBluetoothStateChange: up=true
08-19 17:55:15.006  6411  6457 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,08-19 17:55:15.006  1304  1315 D BluetoothInputDevice: onBluetoothStateChange: up=true
,08-19 17:55:15.006  6411  6537 D BluetoothSocket: bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[75]}
08-19 17:55:15.006  1015  1044 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothInputDevice
08-19 17:55:15.006  1015  1044 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hid.HidService; callingUser = 0; userId(target) = 0
,08-19 17:55:15.006  6411  6537 D BluetoothSocket: bindListen(), new LocalSocket 
,08-19 17:55:15.006  6411  6537 D BluetoothSocket: bindListen(), new LocalSocket.getInputStream() 
08-19 17:55:15.006  6411  6537 D BluetoothSocket: bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@3ffef5e1
08-19 17:55:15.006  6411  6537 D BluetoothSocket: channel: 19
08-19 17:55:15.006  6411  6537 D BluetoothPbapService: PBAP Socket is BluetoothServerSocket
,08-19 17:55:15.006  1015  1044 W ActivityManager: userId = 0, bbcId = -10000
08-19 17:55:15.006  1015  1044 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-19 17:55:15.006  1015  1044 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,08-19 17:55:15.006  1427  1454 D BluetoothAdapter: onBluetoothStateChange: up=true
08-19 17:55:15.006  1427  1454 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,08-19 17:55:15.006  1304  6303 D BluetoothA2dp: onBluetoothStateChange: up=true
,08-19 17:55:15.006  1304  6303 D BluetoothA2dp: doBind(): CallingUid(myUserHandle) = 0
,08-19 17:55:15.016  1304  1304 D BluetoothInputDevice: Proxy object connected
08-19 17:55:15.016  1015  1044 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothA2dp
08-19 17:55:15.016  1015  1044 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
,08-19 17:55:15.016  1015  1044 W ActivityManager: userId = 0, bbcId = -10000
08-19 17:55:15.016  1015  1044 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-19 17:55:15.016  1015  1044 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,08-19 17:55:15.016  1304  1304 D HidProfile: Bluetooth service connected
,08-19 17:55:15.016  1447  2437 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,08-19 17:55:15.016  1015  1044 D ActivityManager: bindService callerProcessName:com.android.phone, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
08-19 17:55:15.016  1015  1044 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,08-19 17:55:15.016  1304  1304 D BluetoothA2dp: Proxy object connected
08-19 17:55:15.016  1015  1044 W ActivityManager: userId = 0, bbcId = -10000
08-19 17:55:15.016  1015  1044 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-19 17:55:15.016  1015  1044 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = com.android.bluetooth
,08-19 17:55:15.016  1447  2437 E BluetoothHeadset: BluetoothHeadset service is binded
,08-19 17:55:15.016  1304  1304 D A2dpProfile: Bluetooth service connected
,08-19 17:55:15.016  1015  1044 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothGatt
08-19 17:55:15.016  1015  1044 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.gatt.GattService; callingUser = 0; userId(target) = -2
,08-19 17:55:15.026  1015  1015 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
08-19 17:55:15.026  1015  1015 I InputMethodManagerService: [BT Setting State] State =12
08-19 17:55:15.026  1015  1015 I InputMethodManagerService: [BT Setting off -> on] mBTKeyboardCount =0, KEYBOARD_BT(0)
,08-19 17:55:15.026  1172  1172 D BluetoothTile:  onBluetoothStateChange:
,08-19 17:55:15.026  1172  1172 D BluetoothTile:  onBluetoothPairedDevicesChanged:
,08-19 17:55:15.036  1412  1412 D BluetoothHeadset: registerListener : 11, listenercom.android.server.telecom.wearable.BluetoothMessageListener@15367cd7, true
,08-19 17:55:15.036  1412  1412 D BluetoothHeadset: registerMessageListener
,08-19 17:55:15.036  1172  1172 D BluetoothTile: onReceive : android.bluetooth.adapter.action.STATE_CHANGED
,08-19 17:55:15.036  1172  1172 D BluetoothTile:  getBluetoothState : 12
08-19 17:55:15.036  1172  1745 D BluetoothTile:  handleUpdatestate:false name:null
,08-19 17:55:15.036  1172  1745 D BluetoothTile:  handleUpdatestate:false name:null
,08-19 17:55:15.036  1823  1823 I SamsungIME: STATE_CHANGED = 12, KEYBOARD_BT(0), mBTKeyboardCount =0
,08-19 17:55:15.046  1304  1304 V BluetoothEventManager: Received android.bluetooth.adapter.action.STATE_CHANGED
,08-19 17:55:15.046  6220  6220 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-19 17:55:15.046  1015  1474 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,08-19 17:55:15.046  1015  1474 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.nearby.discovery.service.DiscoveryService; callingUser = 0; userId(target) = 0
,08-19 17:55:15.046  1015  1474 W ActivityManager: userId = 0, bbcId = -10000
08-19 17:55:15.046  1015  1474 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-19 17:55:15.046  1015  1474 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-19 17:55:15.046  6411  6422 D HeadsetService: registerMessageListener
08-19 17:55:15.046  6220  6220 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-19 17:55:15.056  1015  1768 D StatusBarManagerService: setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
,08-19 17:55:15.056  6411  6422 D HeadsetService: registerMessageListener
08-19 17:55:15.056  6411  6462 D HeadsetStateMachine: Disconnected process message: 70
,08-19 17:55:15.056  1412  1412 I Telecom : BluetoothPhoneService: handleMessage(7) / param null
08-19 17:55:15.056  1412  1412 I Telecom : BluetoothPhoneService: updateHeadsetWithCallState
,08-19 17:55:15.056  1015  3492 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=true
,08-19 17:55:15.056  6411  6462 D HeadsetStateMachine: processRegisterMessageListener : 11, com.samsung.bt.hfp.IMessageListener$Stub$Proxy@3b7f6f06
,08-19 17:55:15.056  1172  1172 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
,08-19 17:55:15.056  1172  1745 D BluetoothTile:  handleUpdatestate:false name:null
,08-19 17:55:15.056  1304  1304 W LocalBluetoothProfileManager: Warning: MAP profile was previously added but the UUID is now missing.
,08-19 17:55:15.056  1304  1304 W LocalBluetoothProfileManager: Warning: PBAP profile was previously added but the UUID is now missing.
08-19 17:55:15.056  1304  1304 W LocalBluetoothProfileManager: Warning: SAP profile was previously added but the UUID is now missing.
08-19 17:55:15.056  1304  1304 W LocalBluetoothProfileManager: Warning: HID profile was previously added but the UUID is now missing.
,08-19 17:55:15.066  1412  1412 I Telecom : BluetoothPhoneService: getCurrentCallPhoneType, Defalut Phonetype : 1
08-19 17:55:15.066  1412  1412 I Telecom : BluetoothPhoneService: getCurrentCallPhoneType, Current Phonetype : 1
,08-19 17:55:15.066  1412  1412 I Telecom : BluetoothPhoneService: updateHeadsetWithCallState numActive 0, numHeld 0, callState 6, ringing number [da39a3ee5e6b4b0d3255bfef95601890afd80709], ringing type 128
,08-19 17:55:15.066  6411  6539 D BluetoothMapMasInstance: set MAP SDP message type : 1
,08-19 17:55:15.066  6411  6462 D HeadsetStateMachine: Disconnected process message: 9
,08-19 17:55:15.066  6411  6462 D HeadsetStateMachine: mNumActive: 0 mNumHeld: 0 mCallState: 6
,08-19 17:55:15.066  6411  6539 D BluetoothSocket: bindListen(): myUserId = 0
08-19 17:55:15.066  6411  6539 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-19 17:55:15.066  6411  6539 D BluetoothSocket: bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[77]}
08-19 17:55:15.066  6411  6539 D BluetoothSocket: bindListen(), new LocalSocket 
08-19 17:55:15.066  6411  6539 D BluetoothSocket: bindListen(), new LocalSocket.getInputStream() 
08-19 17:55:15.066  6411  6539 D BluetoothSocket: bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@dba49c7
,08-19 17:55:15.066  6411  6539 D BluetoothSocket: channel: 5
,08-19 17:55:15.066  1304  1304 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-19 17:55:15.076  1015  3494 D ActivityManager: startService callerProcessName:com.android.settings, calleePkgName: com.android.settings
,08-19 17:55:15.076  1015  3494 D ActivityManager: retrieveServiceLocked(): component = com.android.settings/com.android.settings.bluetooth.DockService; callingUser = 0; userId(target) = 0
,08-19 17:55:15.076  1015  3494 W ActivityManager: userId = 0, bbcId = -10000
,08-19 17:55:15.076  1015  3494 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-19 17:55:15.076  1015  3494 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.settings
,08-19 17:55:15.086   286   746 D audio_hw_primary: adev_set_parameters: enter: A2dpSuspended=false
08-19 17:55:15.086   286   746 V voice   : voice_set_parameters: enter: A2dpSuspended=false
08-19 17:55:15.086   286   746 V voice   : voice_set_parameters: exit with code(-2)
08-19 17:55:15.086   286   746 V msm8974_platform: platform_set_parameters: enter: A2dpSuspended=false
08-19 17:55:15.086   286   746 V msm8974_platform: platform_set_parameters: exit with code(-2)
08-19 17:55:15.086   286   746 D audio_hw_hfp: audio_extn_hfp_set_parameters: enter
08-19 17:55:15.086   286   746 V audio_hw_primary: adev_set_parameters: exit
08-19 17:55:15.086  6411  6462 E HeadsetStateMachine: terminateScoUsingVirtualVoiceCall:No present call to terminate
,08-19 17:55:15.096  1304  1304 D DockEventReceiver: finishStartingService: stopping service
,08-19 17:55:15.096  1304  1304 D BluetoothNotiBroadcastReceiver: onReceive
,08-19 17:55:15.096  1172  1172 V BluetoothStatusReceiver: Received android.bluetooth.adapter.action.STATE_CHANGED
08-19 17:55:15.096  1172  1172 D BluetoothStatusReceiver: AdapterStateChanged :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 12
,08-19 17:55:15.106  6411  6411 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@8bc66ff
,08-19 17:55:15.106  6411  6411 D BtConfig.SecureMode: isSecureModeOn:false
,08-19 17:55:15.106  1015  3485 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-19 17:55:15.106  1015  3485 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.opp.BluetoothOppService; callingUser = 0; userId(target) = 0
,08-19 17:55:15.106  1015  3485 W ActivityManager: userId = 0, bbcId = -10000
08-19 17:55:15.106  1015  3485 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-19 17:55:15.106  1015  3485 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-19 17:55:15.126  1979  1979 D EasyUnlockReceiver: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.easyunlock.authorization.BluetoothStateChangeReceiver (has extras) }.
,08-19 17:55:15.126  1015  1338 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,08-19 17:55:15.126  1015  1338 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.easyunlock.authorization.InitializerIntentService; callingUser = 0; userId(target) = 0
,08-19 17:55:15.126  1015  1338 W ActivityManager: userId = 0, bbcId = -10000
,08-19 17:55:15.126  1015  1338 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,08-19 17:55:15.126  1015  1338 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-19 17:55:15.136  1015  1301 D SecContentProvider: uri = 4 selection = isProfileAuthorizedBySecurityPolicy
,08-19 17:55:15.136  1979  6548 D EasyUnlockInitService: Handling intent for initializer IntentService.
,08-19 17:55:15.136  1979  1979 D BtServices: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.proximity.BluetoothServicesAdapterStateChangeReceiver (has extras) }.
,08-19 17:55:15.146  1015  1482 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-19 17:55:15.146  1015  1482 W ActivityManager: userId = 0, bbcId = -10000
,08-19 17:55:15.146  1015  1482 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-19 17:55:15.146  1015  1482 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-19 17:55:15.156  6411  6549 D BluetoothSocket: bindListen(): myUserId = 0
08-19 17:55:15.156  6411  6549 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-19 17:55:15.156  6411  6549 D BluetoothSocket: bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[79]}
08-19 17:55:15.156  6411  6549 D BluetoothSocket: bindListen(), new LocalSocket 
08-19 17:55:15.156  6411  6549 D BluetoothSocket: bindListen(), new LocalSocket.getInputStream() 
08-19 17:55:15.156  6411  6549 D BluetoothSocket: bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@2707bb63
,08-19 17:55:15.156  6411  6549 D BluetoothSocket: channel: 12
08-19 17:55:15.156  6411  6549 I BtOppRfcommListener: Accept thread started.
,08-19 17:55:15.156  1015  1028 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-19 17:55:15.166  1015  1028 W ActivityManager: userId = 0, bbcId = -10000
,08-19 17:55:15.166  1015  1028 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-19 17:55:15.166  1015  1028 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-19 17:55:15.166  1979  6548 D EasyUnlockInitService: Not initializing EasyUnlock: remote_devices=0, bluetooth_on=true
,08-19 17:55:16.746   291   291 E SMD     : DCD OFF
,08-19 17:55:16.846  6220  6275 D BluetoothAdapter: disable()
,08-19 17:55:16.846  1015  1301 D SettingsProvider: name = bluetooth_on
,08-19 17:55:16.856  6411  6453 D BluetoothAdapterState: CURRENT_STATE=ON, MSG = USER_TURN_OFF
08-19 17:55:16.856  6411  6453 D BluetoothAdapterProperties: Setting state to 13
08-19 17:55:16.856  6411  6453 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
08-19 17:55:16.856  6411  6453 D BluetoothAdapterService: Bluetooth PBAP supproted is true
08-19 17:55:16.856  6411  6453 D BluetoothAdapterService: updateAdapterState state is 13
,08-19 17:55:16.856  1015  1482 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,08-19 17:55:16.856  1015  1482 W ActivityManager: userId = 0, bbcId = -10000,
,08-19 17:55:16.856  1015  1482 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pbap.BluetoothPbapService; callingUser = 0; userId(target) = 0
08-19 17:55:16.856  1015  1482 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-19 17:55:16.856  1015  3494 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.samsung.ble.BleAutoConnectService; callingUser = 0; userId(target) = 0
08-19 17:55:16.856  1015  1482 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-19 17:55:16.856  6411  6453 D BluetoothAdapterService: Autoconnection is available ,
08-19 17:55:16.856  6411  6453 D BluetoothAdapterService: updateAdapterState prevState = 12newState = 13
08-19 17:55:16.856  6411  6453 D BluetoothAdapterService: terminating service from this receiver,
,08-19 17:55:16.856  6411  6411 I BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED, state: 13,
08-19 17:55:16.866  6411  6411 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@af52360, channel: 19, state: LISTENING
08-19 17:55:16.866  6411  6411 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@af52360, channel: 19, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@3ffef5e1, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@17678019mSocket: android.net.LocalSocket@2c6f58de impl:android.net.LocalSocketImpl@3230aabf fd:FileDescriptor[75]
08-19 17:55:16.866  6411  6411 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@2c6f58de impl:android.net.LocalSocketImpl@3230aabf fd:FileDescriptor[75]
08-19 17:55:16.866  1015  3494 W ActivityManager: userId = 0, bbcId = -10000
08-19 17:55:16.866  1015  3494 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-19 17:55:16.866  1015  3494 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
08-19 17:55:16.866  6411  6453 D BluetoothAdapterProperties: onBluetoothDisable()
08-19 17:55:16.866  6411  6453 D BluetoothAdapterProperties: mDiscovering is false
08-19 17:55:16.866  1015  1338 D SecContentProvider: uri = 3 selection = isDiscoverableEnabled
08-19 17:55:16.866  6411  6453 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=false, isTurningOff()=true
08-19 17:55:16.876  1304  1304 D BluetoothPbap: Proxy object disconnected
08-19 17:55:16.876  1304  1304 D PbapServerProfile: Bluetooth service disconnected
,08-19 17:55:16.876  6411  6456 D BluetoothUtils: getBtEnabledContainers(): btContainers = []
08-19 17:55:16.876  6411  6456 D BluetoothAdapterProperties: Scan Mode:20
,08-19 17:55:16.876  6220  6220 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-19 17:55:16.876  6220  6220 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-19 17:55:16.876  6220  6220 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-19 17:55:16.876  6220  6220 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-19 17:55:16.876  6220  6220 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-19 17:55:16.876  6220  6220 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-19 17:55:16.876  6220  6220 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-19 17:55:16.876  6220  6220 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-19 17:55:16.876  6220  6220 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-19 17:55:16.886  1015  1015 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
,08-19 17:55:16.886  1015  1015 I InputMethodManagerService: [BT Setting State] State =13
,08-19 17:55:16.886  6220  6220 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-19 17:55:16.886  6220  6220 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-19 17:55:16.886  6220  6220 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-19 17:55:16.886  6220  6220 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-19 17:55:16.886  6220  6220 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-19 17:55:16.886  6220  6220 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-19 17:55:16.886  6220  6220 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-19 17:55:16.886  6220  6220 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-19 17:55:16.886  6220  6220 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-19 17:55:16.886  6220  6220 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-19 17:55:16.886  6220  6220 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-19 17:55:16.896  6220  6220 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-19 17:55:16.896  6220  6220 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-19 17:55:16.896  1172  1172 D BluetoothTile:  onBluetoothStateChange:
,08-19 17:55:16.896  1172  1172 D BluetoothTile: onReceive : android.bluetooth.adapter.action.STATE_CHANGED
,08-19 17:55:16.896  1172  1172 D BluetoothTile:  onBluetoothPairedDevicesChanged:
,08-19 17:55:16.896  1172  1172 D BluetoothTile:  getBluetoothState : 13
08-19 17:55:16.896  1172  1745 D BluetoothTile:  handleUpdatestate:false name:null
08-19 17:55:16.896  1172  1745 D BluetoothTile:  handleUpdatestate:false name:null
,08-19 17:55:16.906  1823  1823 I SamsungIME: STATE_CHANGED = 13, KEYBOARD_BT(0), mBTKeyboardCount =0
,08-19 17:55:16.906  1172  1745 D STATUSBAR-QSTileView: onStateChanged: Bluetooth
,08-19 17:55:16.906  1304  1304 V BluetoothEventManager: Received android.bluetooth.adapter.action.STATE_CHANGED
,08-19 17:55:16.906  1015  1446 D StatusBarManagerService: setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
,08-19 17:55:16.906  1015  1482 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=false
,08-19 17:55:16.906  6220  6220 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-19 17:55:16.916  1172  1172 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 )
,08-19 17:55:16.916  1015  1027 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,08-19 17:55:16.916  1015  1027 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.nearby.discovery.service.DiscoveryService; callingUser = 0; userId(target) = 0
,08-19 17:55:16.916  6411  6453 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = BEGIN_DISABLE, isTurningOn=false, isTurningOff=true
,08-19 17:55:16.916  6411  6453 E bt-btif : btif_vhci_sock_cleanup, sock_thread_handle:6, rfc_init:1, vhci_init:1
,08-19 17:55:16.916  6220  6220 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-19 17:55:16.916  6411  6453 E bt-btif : btif_sock_cleanup, sock_thread_handle:6, rfc_init:1, vhci_init:0
,08-19 17:55:16.916  6411  6453 E bt-btif : cmd socket is ]: id 57
,08-19 17:55:16.916  6411  6453 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,08-19 17:55:16.916  6411  6491 E bt-btm  : btm_ble_start_auto_conn start : 0, 0
,08-19 17:55:16.916  6411  6491 W bt-btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
,08-19 17:55:16.916  6411  6491 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
,08-19 17:55:16.916  6411  6491 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-19 17:55:16.916  6411  6491 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
,08-19 17:55:16.926  6411  6549 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,08-19 17:55:16.926  1015  1027 W ActivityManager: userId = 0, bbcId = -10000
,08-19 17:55:16.926  1015  1027 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,08-19 17:55:16.926  1015  1027 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-19 17:55:16.926  1304  1304 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-19 17:55:16.926  1015  1470 D ActivityManager: startService callerProcessName:com.android.settings, calleePkgName: com.android.settings
,08-19 17:55:16.926  1015  1470 D ActivityManager: retrieveServiceLocked(): component = com.android.settings/com.android.settings.bluetooth.DockService; callingUser = 0; userId(target) = 0
,08-19 17:55:16.936  1015  1470 W ActivityManager: userId = 0, bbcId = -10000
,08-19 17:55:16.936  1015  1470 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,08-19 17:55:16.936  1015  1470 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.settings
,08-19 17:55:16.946  1304  1304 D DockEventReceiver: finishStartingService: stopping service
,08-19 17:55:16.946  6411  6411 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@3b6704d5, channel: 5, state: LISTENING
,08-19 17:55:16.946  6411  6411 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@3b6704d5, channel: 5, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@dba49c7, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@1424eamSocket: android.net.LocalSocket@22cf33db impl:android.net.LocalSocketImpl@2a67fe78 fd:FileDescriptor[77]
,08-19 17:55:16.946  6411  6411 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@22cf33db impl:android.net.LocalSocketImpl@2a67fe78 fd:FileDescriptor[77]
,08-19 17:55:16.946  6411  6411 I BtOppRfcommListener: stopping Accept Thread
08-19 17:55:16.946  6411  6411 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@6a01951, channel: 12, state: LISTENING
,08-19 17:55:16.946  6411  6411 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@6a01951, channel: 12, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@2707bb63, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@3f87a5b6mSocket: android.net.LocalSocket@20332b7 impl:android.net.LocalSocketImpl@55a8a24 fd:FileDescriptor[79]
08-19 17:55:16.946  6411  6411 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@20332b7 impl:android.net.LocalSocketImpl@55a8a24 fd:FileDescriptor[79]
08-19 17:55:16.946  6411  6549 I BtOppRfcommListener: BluetoothSocket listen thread finished
,08-19 17:55:16.956  1304  1304 D BluetoothNotiBroadcastReceiver: onReceive
,08-19 17:55:16.956  6411  6411 V BluetoothOppManager: cleanUp...
,08-19 17:55:16.966  1172  1172 V BluetoothStatusReceiver: Received android.bluetooth.adapter.action.STATE_CHANGED
08-19 17:55:16.966  1172  1172 D BluetoothStatusReceiver: AdapterStateChanged :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 13
,08-19 17:55:16.976  1979  1979 D EasyUnlockReceiver: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.easyunlock.authorization.BluetoothStateChangeReceiver (has extras) }.
,08-19 17:55:16.986  1979  1979 D BtServices: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.proximity.BluetoothServicesAdapterStateChangeReceiver (has extras) }.
,08-19 17:55:17.126  6411  6491 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
,08-19 17:55:17.126  6411  6491 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
,08-19 17:55:17.126  6411  6491 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
,08-19 17:55:17.126  6411  6533 I bt_userial_mct: exiting userial_read_thread
08-19 17:55:17.126  6411  6533 D bt_userial_mct: Leaving userial_evt_read_thread()
08-19 17:55:17.126  6411  6456 D bt_userial_mct: userial_close_reader Joined userial reader thread: 0
08-19 17:55:17.126  6411  6493 I bt_vendor: hw_epilog_process
,08-19 17:55:17.126  6411  6491 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-19 17:55:17.126  6411  6491 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-19 17:55:17.126  6411  6456 D bt_userial_mct: userial_close
08-19 17:55:17.126  6411  6456 I bt_vendor: bt-vendor : BT_VND_OP_USERIAL_CLOSE btSocType: 0
,08-19 17:55:17.126  6411  6491 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-19 17:55:17.126  6411  6491 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
,08-19 17:55:17.126  6411  6491 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
,08-19 17:55:17.126  6411  6491 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
,08-19 17:55:17.126  6411  6491 W bt-btif : ag scb idx 1 not allocated
08-19 17:55:17.126  6411  6491 W bt-btif : ag scb idx 2 not allocated,
08-19 17:55:17.126  6411  6491 E bt-btif : BTA AG is already disabled, ignoring ...
,08-19 17:55:17.526  6411  6456 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: Off,
,08-19 17:55:17.526  6411  6456 I bt_vendor: bluetooth satus is on
,08-19 17:55:17.526  6411  6456 I bt_vendor: bt-vendor : resetting BT status
08-19 17:55:17.526  6411  6456 I bt_vendor: Starting hciattach daemon,
,08-19 17:55:17.526  6411  6456 I bt_vendor: try to set false,
08-19 17:55:17.526  6411  6456 I bt_vendor: Starting hciattach daemon
,08-19 17:55:17.526  6411  6456 I bt_vendor: try to set false
08-19 17:55:17.526  6411  6456 I bt_vendor: cleanup
,08-19 17:55:17.526  6411  6491 I GKI_LINUX: gki_task task_id=0 [BTU] terminating
08-19 17:55:17.526  6411  6456 I GKI_LINUX: GKI_exit_task 0 done,
08-19 17:55:17.526  6411  6456 I GKI_LINUX: GKI_shutdown(): task [BTU] terminated
,08-19 17:55:17.536  6411  6453 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = DISABLED, isTurningOn=false, isTurningOff=true,
,08-19 17:55:17.536  6411  6453 D BtConfig.SecureMode: isSecureModeOn:false,
08-19 17:55:17.536  1015  1482 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth,
08-19 17:55:17.536  6411  6453 D BluetoothAdapterService: mProfilesStarted : true supportedProfileServices.length : 12,
08-19 17:55:17.536  1015  1482 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.gatt.GattService; callingUser = 0; userId(target) = 0,
08-19 17:55:17.536  6411  6453 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.gatt.GattService
,08-19 17:55:17.536  1015  3494 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth,
,08-19 17:55:17.536  6411  6453 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.gatt.GattService
08-19 17:55:17.536  1015  3494 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = 0
08-19 17:55:17.536  6411  6453 W BluetoothAdapterService: Not skipping com.android.bluetooth.gatt.GattService
,08-19 17:55:17.536  1015  1482 W ActivityManager: userId = 0, bbcId = -10000
08-19 17:55:17.536  1015  1482 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-19 17:55:17.536  1015  1482 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
08-19 17:55:17.536  6411  6453 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hfp.HeadsetService,
08-19 17:55:17.536  6411  6453 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
08-19 17:55:17.536  6411  6453 W BluetoothAdapterService: Not skipping com.android.bluetooth.hfp.HeadsetService
08-19 17:55:17.536  6411  6411 D BtGatt.DebugUtils: handleDebugAction() action=null,
08-19 17:55:17.546  6411  6411 D BtGatt.GattService: Received stop request...Stopping profile...
08-19 17:55:17.546  6411  6411 D BtGatt.GattService: stop()
,08-19 17:55:17.546  6411  6411 D BtGatt.AdvertiseManager: advertise clients cleared
08-19 17:55:17.546  1015  3494 W ActivityManager: userId = 0, bbcId = -10000
,08-19 17:55:17.546  1015  3494 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-19 17:55:17.546  1015  3494 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-19 17:55:17.546  6411  6453 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.a2dp.A2dpService
08-19 17:55:17.546  1015  3485 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-19 17:55:17.546  6411  6453 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
,08-19 17:55:17.546  1015  3485 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
08-19 17:55:17.546  6411  6453 W BluetoothAdapterService: Not skipping com.android.bluetooth.a2dp.A2dpService
08-19 17:55:17.546  6411  6411 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@8bc66ff
,08-19 17:55:17.546  1015  3485 W ActivityManager: userId = 0, bbcId = -10000
08-19 17:55:17.546  1015  3485 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-19 17:55:17.546  1015  3485 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
08-19 17:55:17.546  6411  6453 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hid.HidService
,08-19 17:55:17.546  6411  6453 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
08-19 17:55:17.546  6411  6453 W BluetoothAdapterService: Not skipping com.android.bluetooth.hid.HidService
08-19 17:55:17.546  1015  1027 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,08-19 17:55:17.546  1015  1027 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hid.HidService; callingUser = 0; userId(target) = 0
,08-19 17:55:17.556  1015  1027 W ActivityManager: userId = 0, bbcId = -10000
,08-19 17:55:17.556  1015  1027 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-19 17:55:17.556  1015  1027 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-19 17:55:17.556  6411  6453 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hdp.HealthService
,08-19 17:55:17.556  6411  6453 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
08-19 17:55:17.556  6411  6453 W BluetoothAdapterService: Not skipping com.android.bluetooth.hdp.HealthService
,08-19 17:55:17.556  1015  1301 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-19 17:55:17.556  1015  1301 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hdp.HealthService; callingUser = 0; userId(target) = 0
08-19 17:55:17.556  6411  6411 D HeadsetService: Received stop request...Stopping profile...
,08-19 17:55:17.556  1015  1301 W ActivityManager: userId = 0, bbcId = -10000
,08-19 17:55:17.556  1015  1301 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-19 17:55:17.556  1015  1301 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-19 17:55:17.556  6411  6453 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.pan.PanService
08-19 17:55:17.556  6411  6453 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.pan.PanService
,08-19 17:55:17.556  6411  6411 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@8bc66ff
08-19 17:55:17.556  6411  6453 W BluetoothAdapterService: Not skipping com.android.bluetooth.pan.PanService
08-19 17:55:17.556  1015  1482 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-19 17:55:17.556  1015  1482 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pan.PanService; callingUser = 0; userId(target) = 0
,08-19 17:55:17.556  1015  1482 W ActivityManager: userId = 0, bbcId = -10000
,08-19 17:55:17.556  1015  1482 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-19 17:55:17.556  1015  1482 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-19 17:55:17.566  6411  6453 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.map.BluetoothMapService
08-19 17:55:17.566  6411  6453 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
08-19 17:55:17.566  6411  6453 W BluetoothAdapterService: Not skipping com.android.bluetooth.map.BluetoothMapService
,08-19 17:55:17.566  1015  1015 D AudioService: onServiceDisconnected: Bluetooth profile: 1
,08-19 17:55:17.566  1015  1768 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-19 17:55:17.566  1015  1768 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.map.BluetoothMapService; callingUser = 0; userId(target) = 0
,08-19 17:55:17.566  1015  1768 W ActivityManager: userId = 0, bbcId = -10000
08-19 17:55:17.566  1015  1768 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-19 17:55:17.566  1015  1768 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
08-19 17:55:17.566  6411  6453 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.broadcom.bt.service.sap.SapService
08-19 17:55:17.566  6411  6453 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
08-19 17:55:17.566  6411  6453 W BluetoothAdapterService: Not skipping com.broadcom.bt.service.sap.SapService
08-19 17:55:17.566  1015  1028 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-19 17:55:17.566  1015  1028 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.broadcom.bt.service.sap.SapService; callingUser = 0; userId(target) = 0
08-19 17:55:17.566  1015  1028 W ActivityManager: userId = 0, bbcId = -10000
08-19 17:55:17.566  1015  1028 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-19 17:55:17.566  1015  1028 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
08-19 17:55:17.566  1304  1304 D HeadsetProfile: Bluetooth service disconnected
,08-19 17:55:17.566  6411  6453 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hfpclient.HeadsetClientService
,08-19 17:55:17.576  6411  6453 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfpclient.HeadsetClientService
08-19 17:55:17.576  6411  6453 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.hfpclient.HeadsetClientService
08-19 17:55:17.576  6411  6453 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.a2dp.A2dpSinkService
08-19 17:55:17.576  6411  6453 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpSinkService
08-19 17:55:17.576  6411  6453 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.a2dp.A2dpSinkService
08-19 17:55:17.576  6411  6453 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.sapclient.SapClientService
08-19 17:55:17.576  6411  6453 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.sapclient.SapClientService
08-19 17:55:17.576  6411  6453 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.sapclient.SapClientService
08-19 17:55:17.576  6411  6453 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hid.HidDevService
08-19 17:55:17.576  6411  6453 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidDevService
08-19 17:55:17.576  6411  6453 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.hid.HidDevService
08-19 17:55:17.576  6411  6453 D BluetoothAdapterState: Stopping profile services that were post enabled
08-19 17:55:17.576  6411  6411 E BluetoothAdapterService(146564863): processProfileServiceStateChanged() serviceName=com.android.bluetooth.gatt.GattService, state=10, doUpdate=false,
08-19 17:55:17.576  6411  6411 D A2dpService: Received stop request...Stopping profile...
08-19 17:55:17.576  6411  6467 D A2dpStateMachine: Exit Disconnected: -1
,08-19 17:55:17.576  6411  6411 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@8bc66ff
,08-19 17:55:17.576  1015  1015 D BluetoothA2dp: Proxy object disconnected
08-19 17:55:17.576  1015  1015 D AudioService: onServiceDisconnected: Bluetooth profile: 2
,08-19 17:55:17.576  1304  1304 D BluetoothA2dp: Proxy object disconnected
08-19 17:55:17.576  1304  1304 D A2dpProfile: Bluetooth service disconnected
,08-19 17:55:17.576  6411  6411 D HidService: Received stop request...Stopping profile...
,08-19 17:55:17.576  6411  6411 D HidService: Stopping Bluetooth HidService
,08-19 17:55:17.586  6411  6411 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
,08-19 17:55:17.586  6411  6411 W bt-btif : cleanup: HH disabling or disabled already, status = 0
08-19 17:55:17.586  6411  6411 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object,
08-19 17:55:17.586  6411  6411 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@8bc66ff
,08-19 17:55:17.586  6411  6411 D HealthService: Received stop request...Stopping profile...
,08-19 17:55:17.586  1304  1304 D BluetoothInputDevice: Proxy object disconnected
08-19 17:55:17.586  1304  1304 D HidProfile: Bluetooth service disconnected
,08-19 17:55:17.586  6411  6411 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@8bc66ff
,08-19 17:55:17.586  6411  6411 E BluetoothAdapterService(146564863): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hfp.HeadsetService, state=10, doUpdate=true
08-19 17:55:17.586  6411  6411 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
08-19 17:55:17.586  6411  6411 D BluetoothAdapterService: Profile still running: com.android.bluetooth.hid.HidService
,08-19 17:55:17.586  6411  6411 D PanService: Received stop request...Stopping profile...
08-19 17:55:17.586  6411  6411 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@8bc66ff
,08-19 17:55:17.596  1015  1015 D BluetoothPan: BluetoothPAN Proxy object disconnected,
,08-19 17:55:17.596  1304  1304 D BluetoothPan: BluetoothPAN Proxy object disconnected
08-19 17:55:17.596  1304  1304 D PanProfile: Bluetooth service disconnected
08-19 17:55:17.596  6411  6411 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
08-19 17:55:17.596  6411  6411 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
08-19 17:55:17.596  6411  6411 D BluetoothMapService: Received stop request...Stopping profile...
,08-19 17:55:17.596  6411  6411 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@8bc66ff
,08-19 17:55:17.596  1304  1304 D BluetoothMap: Proxy object disconnected
,08-19 17:55:17.596  1304  1304 D MapProfile: Bluetooth service disconnected
08-19 17:55:17.596  6411  6411 D SapService: Received stop request...Stopping profile...
08-19 17:55:17.596  6411  6411 D SapService: Stopping Bluetooth SapService
08-19 17:55:17.596  6411  6411 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@8bc66ff
,08-19 17:55:17.606  1304  1304 D Bluetoothsap: BluetoothSAP Proxy object disconnected
08-19 17:55:17.606  1304  1304 D SapProfile: Bluetooth service disconnected
,08-19 17:55:17.606  6411  6411 E BluetoothAdapterService(146564863): processProfileServiceStateChanged() serviceName=com.android.bluetooth.a2dp.A2dpService, state=10, doUpdate=true
08-19 17:55:17.606  6411  6411 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
08-19 17:55:17.606  6411  6411 D BluetoothAdapterService: Profile still running: com.android.bluetooth.hid.HidService
08-19 17:55:17.606  6411  6411 D BluetoothA2dp: Proxy object disconnected
08-19 17:55:17.606  6411  6411 D BluetoothAdapterService: Bluetooth A2dp source service disconnected
,08-19 17:55:17.606  6411  6468 I GKI_LINUX: gki_task task_id=2 [A2DP-MEDIA] terminating
,08-19 17:55:17.606  6411  6411 I GKI_LINUX: GKI_exit_task 2 done
08-19 17:55:17.606  6411  6411 I GKI_LINUX: GKI_shutdown(): task [A2DP-MEDIA] terminated
,08-19 17:55:17.606  6411  6411 E BluetoothAdapterService(146564863): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hid.HidService, state=10, doUpdate=true,
08-19 17:55:17.606  6411  6411 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
08-19 17:55:17.606  6411  6411 D BluetoothAdapterService: Profile still running: com.android.bluetooth.map.BluetoothMapService
08-19 17:55:17.606  6411  6411 E BluetoothAdapterService(146564863): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hdp.HealthService, state=10, doUpdate=true
08-19 17:55:17.606  6411  6411 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
08-19 17:55:17.606  6411  6411 D BluetoothAdapterService: Profile still running: com.android.bluetooth.map.BluetoothMapService
08-19 17:55:17.606  6411  6411 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...,
08-19 17:55:17.606  6411  6411 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
08-19 17:55:17.606  6411  6411 E BluetoothAdapterService(146564863): processProfileServiceStateChanged() serviceName=com.android.bluetooth.pan.PanService, state=10, doUpdate=true
08-19 17:55:17.606  6411  6411 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
,08-19 17:55:17.606  6411  6411 D BluetoothAdapterService: Profile still running: com.android.bluetooth.map.BluetoothMapService
08-19 17:55:17.606  6411  6411 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
08-19 17:55:17.606  6411  6411 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
,08-19 17:55:17.606  6411  6411 E BluetoothAdapterService(146564863): processProfileServiceStateChanged() serviceName=com.android.bluetooth.map.BluetoothMapService, state=10, doUpdate=true
08-19 17:55:17.606  6411  6411 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
08-19 17:55:17.606  6411  6411 D BluetoothAdapterService: Profile still running: com.broadcom.bt.service.sap.SapService
08-19 17:55:17.606  6411  6411 E BluetoothAdapterService(146564863): processProfileServiceStateChanged() serviceName=com.broadcom.bt.service.sap.SapService, state=10, doUpdate=true
08-19 17:55:17.616  6411  6411 W BluetoothSAPServiceJni: ## WARNING : cleanupNative(L251): Cleaning up Bluetooth SAP Interface...##
08-19 17:55:17.616  6411  6411 W BluetoothSAPServiceJni: ## WARNING : cleanupNative(L257): Cleaning up Bluetooth SAP callback object##
,08-19 17:55:17.616  6411  6453 D BluetoothAdapterState: CURRENT_STATE=PENDING,MSG = STOPPED, isTurningOn=false, isTurningOff=true
,08-19 17:55:17.616  6411  6453 D BluetoothAdapterProperties: Setting state to 10
08-19 17:55:17.616  6411  6453 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 10
08-19 17:55:17.616  6411  6453 D BluetoothAdapterService: Bluetooth PBAP supproted is true
08-19 17:55:17.616  6411  6453 D BluetoothAdapterService: updateAdapterState state is 10
,08-19 17:55:17.616  6411  6453 D BluetoothAdapterService: Autoconnection is available 
,08-19 17:55:17.616  6411  6453 D BluetoothAdapterService: updateAdapterState prevState = 13newState = 10
,08-19 17:55:17.616  6411  6453 I BluetoothAdapterState: Entering OffState
,08-19 17:55:17.616  1304  1315 D Bluetoothsap: onBluetoothStateChange: up=false
,08-19 17:55:17.616  1304  1315 D Bluetoothsap: Unbinding service...
,08-19 17:55:17.616  1304  6303 D BluetoothPbap: onBluetoothStateChange: up=false
,08-19 17:55:17.626  1172  1185 D BluetoothAdapter: onBluetoothStateChange: up=false,
08-19 17:55:17.626  1172  1185 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
08-19 17:55:17.626  6323  6332 D BluetoothAdapter: onBluetoothStateChange: up=false
08-19 17:55:17.626  6323  6332 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,08-19 17:55:17.626  1979  3305 D BluetoothAdapter: onBluetoothStateChange: up=false
,08-19 17:55:17.626  1979  3305 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,08-19 17:55:17.626  6220  6228 D BluetoothAdapter: onBluetoothStateChange: up=false
,08-19 17:55:17.626  6220  6228 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,08-19 17:55:17.626  6220  6228 D BluetoothLeAdvertiser: stop All Advertising :: standalone boolean value is = false
,08-19 17:55:17.626  6220  6228 D BluetoothLeAdvertiser: Exit stop advertising
,08-19 17:55:17.626  6220  6228 D BluetoothLeScanner: stopAllScan standalone boolean is value is = false
08-19 17:55:17.626  6220  6228 D BluetoothLeScanner: Exiting stopAllScan
,08-19 17:55:17.626  1015  1044 D BluetoothAdapter: onBluetoothStateChange: up=false
,08-19 17:55:17.626  1015  1044 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
08-19 17:55:17.626  6411  6422 D BluetoothA2dp: onBluetoothStateChange: up=false
,08-19 17:55:17.626  1015  1044 D BluetoothA2dp: onBluetoothStateChange: up=false
,08-19 17:55:17.636  1412  6355 D BluetoothAdapter: onBluetoothStateChange: up=false
,08-19 17:55:17.636  1412  6355 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,08-19 17:55:17.636  1304  1315 D BluetoothAdapter: onBluetoothStateChange: up=false
,08-19 17:55:17.636  1304  1315 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,08-19 17:55:17.636  1304  1325 D BluetoothMap: onBluetoothStateChange: up=false
,08-19 17:55:17.636  1447  2437 D BluetoothAdapter: onBluetoothStateChange: up=false
,08-19 17:55:17.636  1447  2437 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,08-19 17:55:17.636  6411  6424 D BluetoothAdapter: onBluetoothStateChange: up=false
,08-19 17:55:17.636  6411  6424 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,08-19 17:55:17.636  1304  1315 D BluetoothInputDevice: onBluetoothStateChange: up=false
,08-19 17:55:17.636  1427  1454 D BluetoothAdapter: onBluetoothStateChange: up=false
,08-19 17:55:17.636  1427  1454 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,08-19 17:55:17.646  1304  6303 D BluetoothA2dp: onBluetoothStateChange: up=false
,08-19 17:55:17.646  1015  1044 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 10 receivers.
,08-19 17:55:17.646  1015  1044 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 0 receivers.
,08-19 17:55:17.656  1015  1015 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
08-19 17:55:17.656  1015  1015 I InputMethodManagerService: [BT Setting State] State =10
08-19 17:55:17.656  1015  1015 I InputMethodManagerService: [BT Setting on -> off] mBTKeyboardCount =0, KEYBOARD_BT(0)
,08-19 17:55:17.656  6411  6456 I GKI_LINUX: gki_task task_id=1 [BTIF] terminating
08-19 17:55:17.656  6411  6411 I GKI_LINUX: GKI_exit_task 1 done
08-19 17:55:17.656  6411  6411 I GKI_LINUX: GKI_shutdown(): task [BTIF] terminated
,08-19 17:55:17.656  6411  6411 I BluetoothServiceJni: cleanupNative: return from cleanup
,08-19 17:55:17.666  6411  6411 I art     : System.exit called, status: 0
08-19 17:55:17.666  6411  6411 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,08-19 17:55:17.666  1172  1172 D BluetoothAdapter: 728109433: getState() :  mService = null. Returning STATE_OFF
08-19 17:55:17.666  1172  1172 D BluetoothTile:  onBluetoothPairedDevicesChanged:
08-19 17:55:17.666  1172  1172 D BluetoothTile: onReceive : android.bluetooth.adapter.action.STATE_CHANGED
08-19 17:55:17.666  1172  1172 D BluetoothTile:  getBluetoothState : 10
08-19 17:55:17.666  1172  1745 D BluetoothAdapter: 728109433: getState() :  mService = null. Returning STATE_OFF
,08-19 17:55:17.666  1172  1745 D BluetoothAdapter: 728109433: getState() :  mService = null. Returning STATE_OFF
,08-19 17:55:17.666  1172  1172 D BluetoothAdapter: 728109433: getState() :  mService = null. Returning STATE_OFF
08-19 17:55:17.666  1172  1172 D BluetoothAdapter: 728109433: getState() :  mService = null. Returning STATE_OFF
,08-19 17:55:17.666  1823  1823 I SamsungIME: STATE_CHANGED = 10, KEYBOARD_BT(0), mBTKeyboardCount =0
,08-19 17:55:17.666  1015  1446 D StatusBarManagerService: setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
,08-19 17:55:17.666  1015  1475 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=false
,08-19 17:55:17.676  1304  1304 V BluetoothEventManager: Received android.bluetooth.adapter.action.STATE_CHANGED
,08-19 17:55:17.676  1979  2176 D BluetoothAdapter: 777567744: getState() :  mService = null. Returning STATE_OFF
,08-19 17:55:17.676  1979  2176 D BluetoothAdapter: 777567744: getState() :  mService = null. Returning STATE_OFF
,08-19 17:55:17.676  1172  1172 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 )
08-19 17:55:17.676  1015  3485 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
08-19 17:55:17.676  1015  3485 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.nearby.discovery.service.DiscoveryService; callingUser = 0; userId(target) = 0
,08-19 17:55:17.676  1015  3485 W ActivityManager: userId = 0, bbcId = -10000
08-19 17:55:17.676  1015  3485 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-19 17:55:17.676  1015  3485 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-19 17:55:17.676  6220  6220 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-19 17:55:17.676  6220  6220 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-19 17:55:17.686  1304  1304 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-19 17:55:17.686  1015  1028 D ActivityManager: startService callerProcessName:com.android.settings, calleePkgName: com.android.settings
08-19 17:55:17.686  1015  1028 D ActivityManager: retrieveServiceLocked(): component = com.android.settings/com.android.settings.bluetooth.DockService; callingUser = 0; userId(target) = 0
,08-19 17:55:17.686  1015  1028 W ActivityManager: userId = 0, bbcId = -10000
08-19 17:55:17.686  1015  1028 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-19 17:55:17.686  1015  1028 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.settings
,08-19 17:55:17.696  1304  1304 D DockEventReceiver: finishStartingService: stopping service
,08-19 17:55:17.696  1304  1304 D BluetoothNotiBroadcastReceiver: onReceive
,08-19 17:55:17.696  1172  1172 V BluetoothStatusReceiver: Received android.bluetooth.adapter.action.STATE_CHANGED
,08-19 17:55:17.706  1172  1172 D BluetoothStatusReceiver: AdapterStateChanged :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 10
,08-19 17:55:17.716  1015  3485 E JavaBinder: !!! FAILED BINDER TRANSACTION !!!
,08-19 17:55:17.716  1015  3485 E JavaBinder: !!! FAILED BINDER TRANSACTION !!!
,08-19 17:55:17.716  1015  3485 W BroadcastQueue: Exception when sending broadcast to ComponentInfo{com.android.bluetooth/com.android.bluetooth.opp.BluetoothOppReceiver}
08-19 17:55:17.716  1015  3485 W BroadcastQueue: android.os.TransactionTooLargeException
08-19 17:55:17.716  1015  3485 W BroadcastQueue: 	at android.os.BinderProxy.transactNative(Native Method)
08-19 17:55:17.716  1015  3485 W BroadcastQueue: 	at android.os.BinderProxy.transact(Binder.java:496)
08-19 17:55:17.716  1015  3485 W BroadcastQueue: 	at android.app.ApplicationThreadProxy.scheduleReceiver(ApplicationThreadNative.java:969)
08-19 17:55:17.716  1015  3485 W BroadcastQueue: 	at com.android.server.am.BroadcastQueue.processCurBroadcastLocked(BroadcastQueue.java:310)
08-19 17:55:17.716  1015  3485 W BroadcastQueue: 	at com.android.server.am.BroadcastQueue.processNextBroadcast(BroadcastQueue.java:1284)
08-19 17:55:17.716  1015  3485 W BroadcastQueue: 	at com.android.server.am.ActivityManagerService.finishReceiver(ActivityManagerService.java:20499)
08-19 17:55:17.716  1015  3485 W BroadcastQueue: 	at android.app.ActivityManagerNative.onTransact(ActivityManagerNative.java:472)
08-19 17:55:17.716  1015  3485 W BroadcastQueue: 	at com.android.server.am.ActivityManagerService.onTransact(ActivityManagerService.java:3280)
08-19 17:55:17.716  1015  3485 W BroadcastQueue: 	at android.os.Binder.execTransact(Binder.java:446)
,08-19 17:55:17.716  1015  3485 D ActivityManager: startProcessLocked calleePkgName: com.android.bluetooth, hostingType: broadcast
,08-19 17:55:17.716  1015  3485 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-19 17:55:17.716  1015  3485 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-19 17:55:17.716  1015  3485 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-19 17:55:17.716  1015  3485 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-19 17:55:17.736  6565  6565 E Zygote  : MountEmulatedStorage(),
08-19 17:55:17.736  6565  6565 E Zygote  : v2
08-19 17:55:17.736  6565  6565 I libpersona: KNOX_SDCARD checking this for 1002
,08-19 17:55:17.736  6565  6565 I libpersona: KNOX_SDCARD not a persona
,08-19 17:55:17.736  1015  3485 I ActivityManager: Start proc com.android.bluetooth for broadcast com.android.bluetooth/.opp.BluetoothOppReceiver: pid=6565 uid=1002 gids={41002, 9997, 3003, 3002, 3001, 1028, 1015, 3005, 1016, 3008} abi=armeabi-v7a
,08-19 17:55:17.746  6565  6565 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-19 17:55:17.746  6565  6565 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051,
,08-19 17:55:17.746  6565  6565 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-19 17:55:17.766  6565  6565 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-19 17:55:17.766  6565  6565 D ActivityThread: Added TimaKeyStore provider
,08-19 17:55:17.776  6565  6565 W ResourcesManager: Asset path '/system/framework/javax.obex.jar' does not exist or contains no resources.
,08-19 17:55:17.776  6565  6565 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,08-19 17:55:17.796  6565  6565 I BluetoothA2dpSinkServiceJni: register_com_android_bluetooth_a2dp_sink
,08-19 17:55:17.836  6565  6565 D BtSettings.ProfileConfig: Adding GattService
,08-19 17:55:17.836  6565  6565 D BtSettings.ProfileConfig: Adding HeadsetService
,08-19 17:55:17.836  6565  6565 D BtSettings.ProfileConfig: Adding A2dpService
,08-19 17:55:17.846  6565  6565 D BtSettings.ProfileConfig: Adding HidService
,08-19 17:55:17.846  6565  6565 D BtSettings.ProfileConfig: Adding HealthService
,08-19 17:55:17.846  6565  6565 D BtSettings.ProfileConfig: Adding PanService
,08-19 17:55:17.846  6565  6565 D BtSettings.ProfileConfig: Adding BluetoothMapService
,08-19 17:55:17.846  6565  6565 D BtSettings.ProfileConfig: Adding SapService
,08-19 17:55:17.846  6565  6565 D BtSettings.ProfileConfig: Adding HeadsetClientService
,08-19 17:55:17.846  6565  6565 D BtSettings.ProfileConfig: Adding A2dpSinkService
,08-19 17:55:17.846  6565  6565 D BtSettings.ProfileConfig: Adding SapClientService
,08-19 17:55:17.846  6565  6565 D BtSettings.ProfileConfig: Adding HidDevService
,08-19 17:55:17.846  6565  6565 I BtSettings.ProfileConfig: *********Initializing Bluetooth Profile Settings*******
,08-19 17:55:17.856  1015  1027 D SettingsProvider: name = bt_svcst_com.android.bluetooth.gatt.GattService
,08-19 17:55:17.856  1015  1027 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-19 17:55:17.856  1015  1027 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
,08-19 17:55:17.856  1015  1027 D SettingsProvider: selectionArgs: false
08-19 17:55:17.856  1015  1027 D SettingsProvider: selectionArgs: 1002
08-19 17:55:17.856  1015  1027 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-19 17:55:17.856  1015  1027 D SettingsProvider: ret = -1
08-19 17:55:17.856  1015  1133 D SettingsProvider: name = bt_svcst_com.android.bluetooth.hfp.HeadsetService
08-19 17:55:17.856  1015  1133 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-19 17:55:17.856  1015  1133 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-19 17:55:17.856  1015  1133 D SettingsProvider: selectionArgs: false
08-19 17:55:17.856  1015  1133 D SettingsProvider: selectionArgs: 1002
08-19 17:55:17.856  1015  1133 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-19 17:55:17.856  1015  1133 D SettingsProvider: ret = -1
08-19 17:55:17.856  1015  1482 D SettingsProvider: name = bt_svcst_com.android.bluetooth.a2dp.A2dpService
08-19 17:55:17.856  1015  1482 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-19 17:55:17.856  1015  1482 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
,08-19 17:55:17.856  1015  1482 D SettingsProvider: selectionArgs: false
08-19 17:55:17.856  1015  1482 D SettingsProvider: selectionArgs: 1002
08-19 17:55:17.856  1015  1482 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-19 17:55:17.856  1015  1482 D SettingsProvider: ret = -1
08-19 17:55:17.856  1015  3492 D SettingsProvider: name = bt_svcst_com.android.bluetooth.hid.HidService
08-19 17:55:17.856  1015  3492 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
,08-19 17:55:17.856  1015  3492 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-19 17:55:17.856  1015  3492 D SettingsProvider: selectionArgs: false
08-19 17:55:17.856  1015  3492 D SettingsProvider: selectionArgs: 1002
08-19 17:55:17.856  1015  3492 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-19 17:55:17.856  1015  3492 D SettingsProvider: ret = -1
,08-19 17:55:17.856  1015  1474 D SettingsProvider: name = bt_svcst_com.android.bluetooth.hdp.HealthService
08-19 17:55:17.856  1015  1474 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
,08-19 17:55:17.856  1015  1474 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-19 17:55:17.856  1015  1474 D SettingsProvider: selectionArgs: false
08-19 17:55:17.856  1015  1474 D SettingsProvider: selectionArgs: 1002
08-19 17:55:17.856  1015  1474 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-19 17:55:17.856  1015  1474 D SettingsProvider: ret = -1
,08-19 17:55:17.856  1015  1475 D SettingsProvider: name = bt_svcst_com.android.bluetooth.pan.PanService
08-19 17:55:17.856  1015  1475 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-19 17:55:17.856  1015  1475 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-19 17:55:17.856  1015  1475 D SettingsProvider: selectionArgs: false
08-19 17:55:17.856  1015  1475 D SettingsProvider: selectionArgs: 1002
08-19 17:55:17.856  1015  1475 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-19 17:55:17.856  1015  1475 D SettingsProvider: ret = -1
08-19 17:55:17.856  1015  1470 D SettingsProvider: name = bt_svcst_com.android.bluetooth.map.BluetoothMapService
08-19 17:55:17.856  1015  1470 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-19 17:55:17.856  1015  1470 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-19 17:55:17.856  1015  1470 D SettingsProvider: selectionArgs: false
,08-19 17:55:17.856  1015  1470 D SettingsProvider: selectionArgs: 1002
08-19 17:55:17.856  1015  1470 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-19 17:55:17.856  1015  1470 D SettingsProvider: ret = -1
08-19 17:55:17.856  1015  1338 D SettingsProvider: name = bt_svcst_com.broadcom.bt.service.sap.SapService
08-19 17:55:17.856  1015  1338 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-19 17:55:17.856  1015  1338 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
,08-19 17:55:17.856  1015  1338 D SettingsProvider: selectionArgs: false
08-19 17:55:17.856  1015  1338 D SettingsProvider: selectionArgs: 1002
08-19 17:55:17.856  1015  1338 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-19 17:55:17.856  1015  1338 D SettingsProvider: ret = -1
08-19 17:55:17.856  1015  1028 D SettingsProvider: name = bt_svcst_com.android.bluetooth.hfpclient.HeadsetClientService
,08-19 17:55:17.856  1015  1028 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-19 17:55:17.856  1015  1028 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-19 17:55:17.856  1015  1028 D SettingsProvider: selectionArgs: false
08-19 17:55:17.856  1015  1028 D SettingsProvider: selectionArgs: 1002
,08-19 17:55:17.856  1015  1028 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-19 17:55:17.856  1015  1028 D SettingsProvider: ret = -1
08-19 17:55:17.856  1015  1768 D SettingsProvider: name = bt_svcst_com.android.bluetooth.a2dp.A2dpSinkService
08-19 17:55:17.856  1015  1768 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
,08-19 17:55:17.856  1015  1768 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-19 17:55:17.856  1015  1768 D SettingsProvider: selectionArgs: false
08-19 17:55:17.856  1015  1768 D SettingsProvider: selectionArgs: 1002
08-19 17:55:17.856  1015  1768 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
,08-19 17:55:17.856  1015  1768 D SettingsProvider: ret = -1
08-19 17:55:17.856  1015  3494 D SettingsProvider: name = bt_svcst_com.android.bluetooth.sapclient.SapClientService
08-19 17:55:17.856  1015  3494 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-19 17:55:17.856  1015  3494 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
,08-19 17:55:17.856  1015  3494 D SettingsProvider: selectionArgs: false
08-19 17:55:17.856  1015  3494 D SettingsProvider: selectionArgs: 1002
08-19 17:55:17.856  1015  3494 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-19 17:55:17.856  1015  3494 D SettingsProvider: ret = -1,
08-19 17:55:17.866  1015  1301 D SettingsProvider: name = bt_svcst_com.android.bluetooth.hid.HidDevService
08-19 17:55:17.866  1015  1301 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-19 17:55:17.866  1015  1301 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
,08-19 17:55:17.866  1015  1301 D SettingsProvider: selectionArgs: false,
08-19 17:55:17.866  1015  1301 D SettingsProvider: selectionArgs: 1002
08-19 17:55:17.866  1015  1301 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
,08-19 17:55:17.866  1015  1301 D SettingsProvider: ret = -1
,08-19 17:55:17.876  1979  1979 D EasyUnlockReceiver: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.easyunlock.authorization.BluetoothStateChangeReceiver (has extras) }.
,08-19 17:55:17.876  1015  1474 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,08-19 17:55:17.876  1015  1474 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.easyunlock.authorization.InitializerIntentService; callingUser = 0; userId(target) = 0
,08-19 17:55:17.886  1015  1474 W ActivityManager: userId = 0, bbcId = -10000
,08-19 17:55:17.886  1015  1474 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-19 17:55:17.886  1015  1474 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-19 17:55:17.886  1979  6581 D EasyUnlockInitService: Handling intent for initializer IntentService.
,08-19 17:55:18.046  1015  1475 I art     : Explicit concurrent mark sweep GC freed 60631(3MB) AllocSpace objects, 5(80KB) LOS objects, 33% free, 23MB/35MB, paused 2.450ms total 164.346ms
,08-19 17:55:18.046  1015  1446 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-19 17:55:18.046  1015  1446 W ActivityManager: userId = 0, bbcId = -10000
,08-19 17:55:18.046  1015  1446 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-19 17:55:18.046  1979  1979 D BtServices: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.proximity.BluetoothServicesAdapterStateChangeReceiver (has extras) }.
08-19 17:55:18.046  1015  1446 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-19 17:55:18.056  1979  6581 D EasyUnlockInitService: Not initializing EasyUnlock: remote_devices=0, bluetooth_on=false
,08-19 17:55:18.596  1015  2805 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,08-19 17:55:19.066  1015  3492 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-19 17:55:19.076  1015  3492 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4328, temperature: 280, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
,08-19 17:55:19.076  1015  3492 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
08-19 17:55:19.076  1015  3492 D BatteryService: stay LED for fully charged
,08-19 17:55:19.076  1015  1015 D BatteryService: Sending ACTION_BATTERY_CHANGED.,
,08-19 17:55:19.076  1015  1015 I MotionRecognitionService: Plugged,
08-19 17:55:19.076  1015  1015 I MotionRecognitionService: mGripSensorEnabled= false,
,08-19 17:55:19.086  1172  1172 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,08-19 17:55:19.086  1172  1172 D KeyguardUpdateMonitor: handleBatteryUpdate
,08-19 17:55:19.086  1405  1405 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,08-19 17:55:19.086  1405  1405 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,08-19 17:55:19.106  1015  1047 I PowerManagerService: [PWL] Off : 50s ago
,08-19 17:55:19.116  1172  1172 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-19 17:55:19.116  1172  1172 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
08-19 17:55:19.126  1172  1172 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-19 17:55:19.136  1015  2770 D SSRM:n  : SIOP:: AP = 330,
,08-19 17:55:19.746   291   291 E SMD     : DCD OFF
,08-19 17:55:19.856  6220  6275 D io.jxcore.node.ConnectivityMonitor: stop
,08-19 17:55:19.856  6220  6275 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-19 17:55:20.746  1015  1303 E Watchdog: !@Sync 4
,08-19 17:55:21.216  1015  1093 V AlarmManager: waitForAlarm result :8,
08-19 17:55:21.216  1015  1093 V AlarmManager: No more alarm at this time.nowELAPSED=138444 batch.start=169175
,08-19 17:55:21.736   323   323 I ServiceManager: Waiting for service AtCmdFwd...,
,08-19 17:55:22.736   323   323 I ServiceManager: Waiting for service AtCmdFwd...
,08-19 17:55:22.746   291   291 E SMD     : DCD OFF,
,08-19 17:55:22.856  6220  6275 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded,
08-19 17:55:22.856  6220  6275 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@a94ed3a added. We now have 6 listener(s)
08-19 17:55:22.856  6220  6275 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1,
08-19 17:55:22.856  6220  6275 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-19 17:55:22.856  6220  6275 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@168cddeb added. We now have 7 listener(s),
08-19 17:55:22.856  6220  6275 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-19 17:55:22.866  6220  6275 I System.out: IsBluetoothEnabled
,08-19 17:55:22.866  6220  6275 D BluetoothAdapter: disable(),
08-19 17:55:22.866  1015  1482 E BluetoothManagerService: Bluetooth is already disabled. DO NOT disable again.
08-19 17:55:22.866  6220  6275 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-19 17:55:22.866  6220  6275 D BluetoothAdapter: enable()
08-19 17:55:22.866  1015  1474 W ActivityManager: Permission Denial: getCurrentUser() from pid=6220, uid=10171 requires android.permission.INTERACT_ACROSS_USERS
,08-19 17:55:22.866  1015  1474 W BluetoothManagerService: Failed getting userId using ActivityManagerNative
08-19 17:55:22.866  1015  1474 W BluetoothManagerService: java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=6220, uid=10171 requires android.permission.INTERACT_ACROSS_USERS
08-19 17:55:22.866  1015  1474 W BluetoothManagerService: 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:23972)
08-19 17:55:22.866  1015  1474 W BluetoothManagerService: 	at com.android.server.BluetoothManagerService.CheckItPolicy(BluetoothManagerService.java:2256)
08-19 17:55:22.866  1015  1474 W BluetoothManagerService: 	at com.android.server.BluetoothManagerService.enable(BluetoothManagerService.java:688)
08-19 17:55:22.866  1015  1474 W BluetoothManagerService: 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:98)
08-19 17:55:22.866  1015  1474 W BluetoothManagerService: 	at android.os.Binder.execTransact(Binder.java:446)
,08-19 17:55:22.866  1015  1474 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
08-19 17:55:22.866  1015  1474 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
08-19 17:55:22.876  1015  1474 D SettingsProvider: name = bluetooth_on,
,08-19 17:55:22.876  1015  1044 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
08-19 17:55:22.876  1015  1044 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
,08-19 17:55:22.876  1015  1044 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetooth
,08-19 17:55:22.886  1015  1044 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.btservice.AdapterService; callingUser = 0; userId(target) = -2
,08-19 17:55:22.916  6565  6565 D BluetoothAdapterState: make
,08-19 17:55:22.926  6565  6565 I bluedroid: init
,08-19 17:55:22.926  6565  6587 I BluetoothAdapterState: Entering OffState
,08-19 17:55:22.926  6565  6565 I bte_conf: bte_load_conf attempt to load stack conf from /etc/bluetooth/bt_stack.conf
,08-19 17:55:22.926  6565  6565 I bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
,08-19 17:55:22.936  6565  6565 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
08-19 17:55:22.936  6565  6565 I bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found,
,08-19 17:55:22.936  6565  6565 E bt-btif : btif_fetch_local_ble_random_bdaddr
,08-19 17:55:22.936  6565  6565 I bluedroid: get_profile_interface socket
08-19 17:55:22.936  6565  6565 I bluedroid: get_profile_interface map_client
08-19 17:55:22.936  6565  6590 I GKI_LINUX: gki_task_entry task_id=1 [BTIF] starting
,08-19 17:55:22.936  6565  6565 D BluetoothAdapterService: checkAddrForIOP: Loading from conf
,08-19 17:55:22.936  6565  6590 D BluetoothAdapterProperties: Address is:08:EC:A9:50:76:27
,08-19 17:55:22.936  6565  6590 E BluetoothServiceJni: populateRssiValuesNative
,08-19 17:55:22.936  6565  6590 I bluedroid: getModelRssiValues
08-19 17:55:22.936  6565  6590 E BluetoothServiceJni: model_rssi_values_callback: low = -70, mid = -60, high = 127
,08-19 17:55:22.936  6565  6590 D BluetoothAdapterProperties: modelRssiValuesCallback, low, mid, high = -70,-60,127
,08-19 17:55:22.946  1015  1015 D SettingsProvider: name = bluetooth_name
,08-19 17:55:22.946  6565  6565 D BluetoothA2dp: doBind(): CallingUid(myUserHandle) = 0
,08-19 17:55:22.956  6565  6590 D BluetoothAdapterProperties: Name is: Thali Test (Galaxy A3)
,08-19 17:55:22.956  1015  3492 D ActivityManager: bindService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothA2dp
08-19 17:55:22.956  1015  3492 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
08-19 17:55:22.956  1015  3492 W ActivityManager: userId = 0, bbcId = -10000
,08-19 17:55:22.956  1015  3492 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-19 17:55:22.956  1015  3492 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-19 17:55:22.956  6565  6573 I bluedroid: config_hci_snoop_log
,08-19 17:55:22.956  1015  1044 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 10 receivers.
,08-19 17:55:22.966  1015  1044 D BluetoothManagerService: Ble is always on enable gatt
08-19 17:55:22.966  1015  1044 I BluetoothManagerService: enableGattForLeMode, doBind called
,08-19 17:55:22.966  1015  1044 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothGatt
08-19 17:55:22.966  1015  1044 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.gatt.GattService; callingUser = 0; userId(target) = -2
,08-19 17:55:22.966  6565  6565 I BtGatt.JNI: classInitNative(L900): classInitNative: Success!
,08-19 17:55:22.966  1015  1044 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
,08-19 17:55:22.966  1015  1044 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
,08-19 17:55:22.976  1015  1044 D SecContentProvider: uri = 3 selection = isBluetoothEnabled
,08-19 17:55:22.976  6565  6587 D BluetoothAdapterState: CURRENT_STATE=OFF, MSG = USER_TURN_ON
,08-19 17:55:22.976  6565  6587 D BluetoothAdapterProperties: Setting state to 11,
08-19 17:55:22.976  6565  6587 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 11
08-19 17:55:22.976  6565  6587 D BluetoothAdapterService: Bluetooth PBAP supproted is true
08-19 17:55:22.976  6565  6587 D BluetoothAdapterService: updateAdapterState state is 11
08-19 17:55:22.976  6565  6587 D BluetoothAdapterService: Autoconnection is available 
08-19 17:55:22.976  6565  6587 D BluetoothAdapterService: updateAdapterState prevState = 10newState = 11
,08-19 17:55:22.986  1015  1015 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
,08-19 17:55:22.986  1015  1015 I InputMethodManagerService: [BT Setting State] State =11
,08-19 17:55:22.986  6565  6587 D BluetoothSecureManager: getInstant: null
08-19 17:55:22.986  6565  6587 D BluetoothSecureManager: calling getMethod for getService
08-19 17:55:22.986  6565  6587 D BluetoothSecureManager: calling getService
,08-19 17:55:22.986  6565  6587 D BluetoothSecureManager: getService return binder: android.os.BinderProxy@30fad964
,08-19 17:55:22.986  1015  1475 D BluetoothSecureManagerService: isSecureModeEnabled
,08-19 17:55:22.986  1015  1475 D BluetoothSecureManagerService: getSecureModeSetting, name: secure_mode_enable
,08-19 17:55:22.996  1172  1172 D BluetoothTile:  onBluetoothPairedDevicesChanged:
,08-19 17:55:22.996  6565  6587 D BtConfig.SecureMode: isSecureModeOn:false
08-19 17:55:22.996  6565  6587 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.gatt.GattService
,08-19 17:55:22.996  6565  6587 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.gatt.GattService
08-19 17:55:22.996  6565  6587 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
,08-19 17:55:22.996  6565  6587 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.hfp.HeadsetService
08-19 17:55:22.996  6565  6587 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
,08-19 17:55:22.996  6565  6587 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.a2dp.A2dpService
08-19 17:55:22.996  6565  6587 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
,08-19 17:55:22.996  1172  1172 D BluetoothTile: onReceive : android.bluetooth.adapter.action.STATE_CHANGED
08-19 17:55:22.996  1172  1172 D BluetoothTile:  getBluetoothState : 11
,08-19 17:55:22.996  6565  6587 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.hid.HidService
08-19 17:55:22.996  6565  6587 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
,08-19 17:55:22.996  1823  1823 I SamsungIME: STATE_CHANGED = 11, KEYBOARD_BT(0), mBTKeyboardCount =0
08-19 17:55:22.996  6565  6587 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.hdp.HealthService
,08-19 17:55:22.996  6565  6587 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.pan.PanService
,08-19 17:55:23.006  6565  6587 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.pan.PanService
,08-19 17:55:23.006  6565  6587 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
,08-19 17:55:23.006  1304  1304 V BluetoothEventManager: Received android.bluetooth.adapter.action.STATE_CHANGED
,08-19 17:55:23.006  6565  6587 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.map.BluetoothMapService
08-19 17:55:23.006  6565  6587 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
,08-19 17:55:23.006  6565  6587 W BluetoothAdapterService: isProfileEnabled(): profile not found com.broadcom.bt.service.sap.SapService
08-19 17:55:23.006  6565  6587 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfpclient.HeadsetClientService
,08-19 17:55:23.006  6565  6587 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.hfpclient.HeadsetClientService
08-19 17:55:23.006  6565  6587 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpSinkService
,08-19 17:55:23.006  6220  6220 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-19 17:55:23.006  6565  6587 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.a2dp.A2dpSinkService
08-19 17:55:23.006  6565  6587 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.sapclient.SapClientService
,08-19 17:55:23.006  6565  6587 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.sapclient.SapClientService
,08-19 17:55:23.006  1015  1028 D StatusBarManagerService: setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
08-19 17:55:23.006  6565  6587 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidDevService
08-19 17:55:23.006  6565  6587 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.hid.HidDevService
,08-19 17:55:23.006  1015  1044 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 0 receivers.
08-19 17:55:23.006  6565  6587 D BluetoothBondStateMachine: make
,08-19 17:55:23.016  1172  1745 D BluetoothTile:  handleUpdatestate:false name:null
08-19 17:55:23.016  1172  1745 D STATUSBAR-QSTileView: onStateChanged: Bluetooth
,08-19 17:55:23.016  1015  1475 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=false
,08-19 17:55:23.016  1172  1172 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
,08-19 17:55:23.016  1172  1172 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 )
,08-19 17:55:23.016  1304  1304 D BluetoothNotiBroadcastReceiver: onReceive
08-19 17:55:23.016  1015  1338 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,08-19 17:55:23.016  6565  6587 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.gatt.GattService
08-19 17:55:23.016  6565  6592 I BluetoothBondStateMachine: StableState(): Entering Off State
08-19 17:55:23.016  1015  1338 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.nearby.discovery.service.DiscoveryService; callingUser = 0; userId(target) = 0
08-19 17:55:23.016  6565  6587 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.gatt.GattService
08-19 17:55:23.016  6565  6587 W BluetoothAdapterService: Not skipping com.android.bluetooth.gatt.GattService
,08-19 17:55:23.016  1015  1338 W ActivityManager: userId = 0, bbcId = -10000
,08-19 17:55:23.016  1015  1338 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-19 17:55:23.016  1015  1338 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-19 17:55:23.026  1015  1474 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-19 17:55:23.026  1015  1474 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.gatt.GattService; callingUser = 0; userId(target) = 0
,08-19 17:55:23.026  1015  1474 W ActivityManager: userId = 0, bbcId = -10000
08-19 17:55:23.026  1015  1474 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,08-19 17:55:23.026  1015  1474 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-19 17:55:23.026  6565  6587 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hfp.HeadsetService
08-19 17:55:23.026  6565  6587 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
08-19 17:55:23.026  6565  6587 W BluetoothAdapterService: Not skipping com.android.bluetooth.hfp.HeadsetService
,08-19 17:55:23.026  6565  6565 D BtGatt.DebugUtils: handleDebugAction() action=null
,08-19 17:55:23.026  6565  6565 D BtGatt.GattService: Received start request. Starting profile...
,08-19 17:55:23.026  6565  6565 D BtGatt.GattService: start()
08-19 17:55:23.026  6565  6565 D BtGatt.GattService: start()
08-19 17:55:23.026  6565  6565 I bluedroid: get_profile_interface gatt
,08-19 17:55:23.026  1015  1482 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,08-19 17:55:23.026  1015  1482 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = 0
,08-19 17:55:23.026  6565  6565 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@8bc66ff
08-19 17:55:23.026  6565  6565 D BtGatt.AdvertiseManager: advertise manager created
,08-19 17:55:23.026  1015  1482 W ActivityManager: userId = 0, bbcId = -10000
,08-19 17:55:23.036  1015  1482 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-19 17:55:23.036  1172  1172 V BluetoothStatusReceiver: Received android.bluetooth.adapter.action.STATE_CHANGED
08-19 17:55:23.036  1172  1172 D BluetoothStatusReceiver: AdapterStateChanged :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 11
,08-19 17:55:23.036  1015  1482 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-19 17:55:23.036  6565  6587 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.a2dp.A2dpService
08-19 17:55:23.036  6565  6587 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
08-19 17:55:23.036  1015  1475 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-19 17:55:23.036  6565  6587 W BluetoothAdapterService: Not skipping com.android.bluetooth.a2dp.A2dpService
08-19 17:55:23.036  1015  1475 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
,08-19 17:55:23.036  1015  1475 W ActivityManager: userId = 0, bbcId = -10000
08-19 17:55:23.036  1015  1475 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-19 17:55:23.036  1015  1475 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-19 17:55:23.046  6565  6587 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hid.HidService
08-19 17:55:23.046  6565  6587 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
08-19 17:55:23.046  6565  6587 W BluetoothAdapterService: Not skipping com.android.bluetooth.hid.HidService
,08-19 17:55:23.046  1015  1301 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,08-19 17:55:23.046  1015  1301 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hid.HidService; callingUser = 0; userId(target) = 0
,08-19 17:55:23.046  1015  1301 W ActivityManager: userId = 0, bbcId = -10000
,08-19 17:55:23.046  1015  1301 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-19 17:55:23.046  1015  1301 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-19 17:55:23.056  6565  6587 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hdp.HealthService
08-19 17:55:23.056  6565  6587 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
08-19 17:55:23.056  6565  6587 W BluetoothAdapterService: Not skipping com.android.bluetooth.hdp.HealthService
,08-19 17:55:23.056  6565  6565 D BtGatt.GattService: mStartError = false
,08-19 17:55:23.056  6565  6565 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@8bc66ff
,08-19 17:55:23.056  6565  6565 D HeadsetService: Received start request. Starting profile...
,08-19 17:55:23.056  6565  6565 D HeadsetService: start()
,08-19 17:55:23.066  6565  6565 I BluetoothHeadsetServiceJni: classInitNative: succeeds
,08-19 17:55:23.066  1015  1768 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-19 17:55:23.066  6565  6565 D HeadsetStateMachine: make
,08-19 17:55:23.066  1015  1768 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hdp.HealthService; callingUser = 0; userId(target) = 0
,08-19 17:55:23.066  1015  1768 W ActivityManager: userId = 0, bbcId = -10000
08-19 17:55:23.066  1015  1768 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-19 17:55:23.066  1015  1768 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-19 17:55:23.066  6565  6565 E HeadsetStateMachine: # of Max HF connection is 2
,08-19 17:55:23.076  6565  6587 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.pan.PanService
08-19 17:55:23.076  6565  6587 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.pan.PanService
08-19 17:55:23.076  6565  6587 W BluetoothAdapterService: Not skipping com.android.bluetooth.pan.PanService
,08-19 17:55:23.076  1015  1027 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,08-19 17:55:23.076  1015  1027 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pan.PanService; callingUser = 0; userId(target) = 0
,08-19 17:55:23.076  1015  1027 W ActivityManager: userId = 0, bbcId = -10000
,08-19 17:55:23.076  1015  1027 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-19 17:55:23.076  1015  1027 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-19 17:55:23.076  6565  6587 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.map.BluetoothMapService
,08-19 17:55:23.076  6565  6587 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
,08-19 17:55:23.076  6565  6587 W BluetoothAdapterService: Not skipping com.android.bluetooth.map.BluetoothMapService
,08-19 17:55:23.086  1015  3485 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-19 17:55:23.086  1015  3485 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.map.BluetoothMapService; callingUser = 0; userId(target) = 0
,08-19 17:55:23.086  1015  3485 W ActivityManager: userId = 0, bbcId = -10000
,08-19 17:55:23.086  1015  3485 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,08-19 17:55:23.086  1015  3485 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-19 17:55:23.086  1015  1470 D ActivityManager: bindService callerProcessName:com.android.bluetooth, calleePkgName: com.android.server.telecom, action: android.bluetooth.IBluetoothHeadsetPhone
,08-19 17:55:23.086  1015  1470 D ActivityManager: retrieveServiceLocked(): component = com.android.server.telecom/com.android.server.telecom.BluetoothPhoneService; callingUser = 0; userId(target) = 0
,08-19 17:55:23.086  1015  1470 W ActivityManager: userId = 0, bbcId = -10000
08-19 17:55:23.086  1015  1470 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-19 17:55:23.086  1015  1470 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.server.telecom
,08-19 17:55:23.086  6565  6587 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.broadcom.bt.service.sap.SapService
08-19 17:55:23.086  6565  6587 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
08-19 17:55:23.086  6565  6587 W BluetoothAdapterService: Not skipping com.broadcom.bt.service.sap.SapService
,08-19 17:55:23.096  1015  1474 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-19 17:55:23.096  1015  1474 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.broadcom.bt.service.sap.SapService; callingUser = 0; userId(target) = 0
,08-19 17:55:23.096  1015  1474 W ActivityManager: userId = 0, bbcId = -10000
,08-19 17:55:23.096  1015  1474 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-19 17:55:23.096  1015  1474 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-19 17:55:23.096  1015  1338 D ActivityManager: bindService callerProcessName:com.android.bluetooth, calleePkgName: com.android.server.telecom, action: com.samsung.bt.hfp.IBluetoothHeadsetVoIP
,08-19 17:55:23.096  1015  1338 D ActivityManager: retrieveServiceLocked(): component = com.android.server.telecom/com.android.server.telecom.BluetoothVoIPService; callingUser = 0; userId(target) = 0
,08-19 17:55:23.096  6565  6587 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hfpclient.HeadsetClientService
08-19 17:55:23.096  1015  1338 W ActivityManager: userId = 0, bbcId = -10000
08-19 17:55:23.096  6565  6587 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfpclient.HeadsetClientService
08-19 17:55:23.096  6565  6587 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.hfpclient.HeadsetClientService
08-19 17:55:23.096  6565  6587 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.a2dp.A2dpSinkService
08-19 17:55:23.096  6565  6587 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpSinkService
08-19 17:55:23.096  6565  6587 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.a2dp.A2dpSinkService
08-19 17:55:23.096  6565  6587 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.sapclient.SapClientService
08-19 17:55:23.096  6565  6587 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.sapclient.SapClientService
08-19 17:55:23.096  6565  6587 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.sapclient.SapClientService
08-19 17:55:23.096  6565  6587 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hid.HidDevService
08-19 17:55:23.096  6565  6587 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidDevService
08-19 17:55:23.096  6565  6587 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.hid.HidDevService
08-19 17:55:23.096  6565  6587 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=true, isTurningOff()=false
,08-19 17:55:23.096  1015  1338 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-19 17:55:23.096  1015  1338 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.server.telecom,
,08-19 17:55:23.106  6565  6565 I bluedroid: get_profile_interface handsfree
,08-19 17:55:23.116  6565  6565 I DualScoManager: Instantiating Dual Sco Manager
08-19 17:55:23.116  6565  6565 I DualScoManager: Set HeadsetServiceHelper
08-19 17:55:23.116  6565  6565 D BluetoothAtMessage: createCMTIContentObservers
,08-19 17:55:23.116  1015  3492 D SettingsProvider: name = bluetooth_hfp_allowed_bvra
,08-19 17:55:23.116  1015  3492 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-19 17:55:23.116  1015  3492 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-19 17:55:23.116  1015  3492 D SettingsProvider: selectionArgs: false
08-19 17:55:23.116  1015  3492 D SettingsProvider: selectionArgs: 1002
08-19 17:55:23.116  1015  3492 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-19 17:55:23.116  1015  3492 D SettingsProvider: ret = -1
,08-19 17:55:23.126  6565  6596 D HeadsetStateMachine: Enter Disconnected: -2
08-19 17:55:23.126  6565  6565 D HeadsetService: mStartError = false
08-19 17:55:23.126  6565  6565 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@8bc66ff
,08-19 17:55:23.126  6565  6565 D A2dpService: Received start request. Starting profile...,
08-19 17:55:23.126  6565  6565 D A2dpService: start()
,08-19 17:55:23.126  6565  6565 I BluetoothAvrcpServiceJni: classInitNative: succeeds
,08-19 17:55:23.126  6565  6596 D HeadsetStateMachine: Clear mHeadsetBrsf
,08-19 17:55:23.126  6565  6565 I bluedroid: get_profile_interface avrcp
08-19 17:55:23.126  6565  6596 D HeadsetStateMachine: map size, before remove : 0
08-19 17:55:23.126  6565  6596 D HeadsetStateMachine: map size, after remove: 0
,08-19 17:55:23.136  6565  6565 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,08-19 17:55:23.136  6565  6565 D Avrcp   : Initialize Media Controller
08-19 17:55:23.136  6565  6565 D Avrcp   : Get the Context Package Name: com.android.bluetooth
,08-19 17:55:23.136  6565  6565 E Avrcp   : getActiveSessions
,08-19 17:55:23.136  6565  6565 D Avrcp   : pick active media Controller
08-19 17:55:23.136  6565  6565 D Avrcp   : Get the active Media Controller 
,08-19 17:55:23.156  6565  6565 I Avrcp   :  Updating now playing list upon AVRCP Start,
08-19 17:55:23.156  6565  6600 D BluetoothMediaBrowser:  getNowPlayingListcontent://media/external/audio/playlists?secFilter=include
,08-19 17:55:23.156  6565  6565 I BluetoothA2dpServiceJni: classInitNative: succeeds
08-19 17:55:23.156  6565  6565 D A2dpStateMachine: make
,08-19 17:55:23.156  6565  6565 I bluedroid: get_profile_interface a2dp
,08-19 17:55:23.156  6565  6602 I GKI_LINUX: gki_task_entry task_id=2 [A2DP-MEDIA] starting
08-19 17:55:23.156  6565  6565 E bt-btif : warning : media task started media_task_refcnt 1 
,08-19 17:55:23.156  6565  6565 D A2dpService: mStartError = false
08-19 17:55:23.156  6565  6565 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@8bc66ff
,08-19 17:55:23.156  6565  6601 D A2dpStateMachine: Enter Disconnected: -2
,08-19 17:55:23.156  6565  6565 I BluetoothHidServiceJni: classInitNative: succeeds
,08-19 17:55:23.166  6565  6565 D HidService: Received start request. Starting profile...
08-19 17:55:23.166  6565  6565 D HidService: start()
08-19 17:55:23.166  6565  6565 I bluedroid: get_profile_interface hidhost
08-19 17:55:23.166  6565  6565 D HidService: setHidService(): set to: null
08-19 17:55:23.166  6565  6565 D HidService: mStartError = false
08-19 17:55:23.166  6565  6565 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@8bc66ff
,08-19 17:55:23.166  6565  6565 E BluetoothAdapterService(146564863): processProfileServiceStateChanged() serviceName=com.android.bluetooth.gatt.GattService, state=12, doUpdate=false
,08-19 17:55:23.166  6565  6565 I BluetoothHealthServiceJni: classInitNative: succeeds
,08-19 17:55:23.166  6565  6565 D HealthService: Received start request. Starting profile...
08-19 17:55:23.166  6565  6565 D HealthService: start()
,08-19 17:55:23.166  6565  6565 I bluedroid: get_profile_interface health
,08-19 17:55:23.166  6565  6565 D HealthService: mStartError = false
08-19 17:55:23.166  6565  6565 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@8bc66ff
,08-19 17:55:23.166  6565  6565 I BluetoothPanServiceJni: classInitNative(L105): succeeds
,08-19 17:55:23.166  6565  6565 D PanService: Received start request. Starting profile...
08-19 17:55:23.166  6565  6565 D PanService: start()
08-19 17:55:23.166  6565  6565 D BluetoothPanServiceJni: initializeNative(L110): pan
08-19 17:55:23.166  6565  6565 I bluedroid: get_profile_interface pan
,08-19 17:55:23.166  6565  6565 D PanService: mStartError = false
08-19 17:55:23.166  6565  6565 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@8bc66ff
,08-19 17:55:23.176  6565  6600 D BluetoothMediaBrowser: no now playing list
08-19 17:55:23.176  6565  6600 D BluetoothMediaBrowser:  getNowPlayingId now playing id : -1
,08-19 17:55:23.176  6565  6565 D BluetoothMapService: Received start request. Starting profile...
08-19 17:55:23.176  6565  6565 D BluetoothMapService: start()
,08-19 17:55:23.176  1979  1979 D EasyUnlockReceiver: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.easyunlock.authorization.BluetoothStateChangeReceiver (has extras) }.
,08-19 17:55:23.176  6565  6565 D BluetoothMapService: mStartError = false
08-19 17:55:23.176  6565  6565 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@8bc66ff
,08-19 17:55:23.176  6565  6565 D HeadsetStateMachine: Try to query the phonestate on bind
,08-19 17:55:23.176  1412  6355 I Telecom : BluetoothPhoneService: queryPhoneState
,08-19 17:55:23.176  1412  1412 I Telecom : BluetoothPhoneService: handleMessage(7) / param 0
,08-19 17:55:23.176  1412  1412 I Telecom : BluetoothPhoneService: updateHeadsetWithCallState
,08-19 17:55:23.186  1412  6355 I Telecom : BluetoothPhoneService: Result of Message : true
,08-19 17:55:23.186  6565  6565 I BluetoothSAPServiceJni: classInitNative(L204): succeeds
,08-19 17:55:23.186  1979  1979 D BtServices: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.proximity.BluetoothServicesAdapterStateChangeReceiver (has extras) }.
,08-19 17:55:23.186  6565  6565 D SapService: Received start request. Starting profile...
08-19 17:55:23.186  6565  6565 D SapService: start()
08-19 17:55:23.186  6565  6565 D BluetoothSAPServiceJni: initializeNative(L209): sap
08-19 17:55:23.186  6565  6565 I bluedroid: get_profile_interface sap
08-19 17:55:23.186  6565  6565 D SapService: mStartError = false
08-19 17:55:23.186  6565  6565 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@8bc66ff
08-19 17:55:23.186  6565  6565 D HeadsetStateMachine: Proxy object connected
,08-19 17:55:23.186  6565  6565 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=0
08-19 17:55:23.186  6565  6565 D HeadsetPhoneState: sendDeviceDataStateChanged
08-19 17:55:23.186  6565  6565 D HeadsetPhoneState: Signal level : previous=0 curr=0
08-19 17:55:23.186  6565  6565 E BluetoothAdapterService(146564863): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hfp.HeadsetService, state=12, doUpdate=true
,08-19 17:55:23.186  6565  6565 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
08-19 17:55:23.186  6565  6565 D BluetoothA2dp: Proxy object connected
08-19 17:55:23.186  6565  6565 D BluetoothAdapterService: Bluetooth A2dp source service connected
08-19 17:55:23.186  6565  6565 E BluetoothAdapterService(146564863): processProfileServiceStateChanged() serviceName=com.android.bluetooth.a2dp.A2dpService, state=12, doUpdate=true
08-19 17:55:23.186  6565  6565 E BluetoothAdapterService(146564863): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hid.HidService, state=12, doUpdate=true
08-19 17:55:23.186  6565  6565 E BluetoothAdapterService(146564863): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hdp.HealthService, state=12, doUpdate=true
08-19 17:55:23.186  6565  6565 E BluetoothAdapterService(146564863): processProfileServiceStateChanged() serviceName=com.android.bluetooth.pan.PanService, state=12, doUpdate=true
,08-19 17:55:23.186  6565  6596 D HeadsetStateMachine: Disconnected process message: 11
08-19 17:55:23.186  6565  6596 D HeadsetStateMachine: Disconnected process message: 18
08-19 17:55:23.186  6565  6596 D HeadsetStateMachine: Disconnected process message: 10
,08-19 17:55:23.186  6565  6596 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
08-19 17:55:23.186  6565  6596 D HeadsetStateMachine: Disconnected process message: 11
,08-19 17:55:23.206  6565  6565 E BluetoothAdapterService(146564863): processProfileServiceStateChanged() serviceName=com.android.bluetooth.map.BluetoothMapService, state=12, doUpdate=true
,08-19 17:55:23.206  6565  6565 E BluetoothAdapterService(146564863): processProfileServiceStateChanged() serviceName=com.broadcom.bt.service.sap.SapService, state=12, doUpdate=true
,08-19 17:55:23.216  6565  6587 D BluetoothAdapterState: CURRENT_STATE=PENDING, MSG = STARTED, isTurningOn=true, isTurningOff=false
,08-19 17:55:23.216  6565  6587 I bluedroid: enable
,08-19 17:55:23.216  6565  6587 I bt_hci_bdroid: init
,08-19 17:55:23.216  6565  6607 I GKI_LINUX: gki_task_entry task_id=0 [BTU] starting
08-19 17:55:23.216  6565  6587 I bt_vendor: bt-vendor : init
08-19 17:55:23.216  6565  6587 I bt_vendor: bt-vendor : get_bt_soc_type
08-19 17:55:23.216  6565  6587 E bt_vendor: get_bt_soc_type: Failed to get soc type
08-19 17:55:23.216  6565  6587 I bt_vendor: init: Local BD Address : 27:76:50:a9:ec:08
08-19 17:55:23.216  6565  6587 D bt_userial_mct: userial_init
08-19 17:55:23.216  6565  6587 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: Off
08-19 17:55:23.216  6565  6587 I bt_vendor: Starting hciattach daemon
08-19 17:55:23.216  6565  6587 I bt_vendor: try to set false
,08-19 17:55:23.216  6565  6587 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: On
,08-19 17:55:23.216  6565  6587 I bt_vendor: Starting hciattach daemon
08-19 17:55:23.216  6565  6587 I bt_vendor: try to set true
,08-19 17:55:23.236  6611  6611 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: init.qcom.bt.sh config =  ,
,08-19 17:55:23.276  6617  6617 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Transport : smd ,
,08-19 17:55:23.286  6618  6618 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** ,
,08-19 17:55:23.296  6620  6620 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Power Class: Ignored. Default(1) used (1-CLASS1/2-CLASS2/3-CUSTOM) ,
,08-19 17:55:23.306  6621  6621 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Power Class: To override, Before turning BT ON; setprop qcom.bt.dev_power_class <1 or 2 or 3> ,
,08-19 17:55:23.316  6622  6622 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: LE Power Class: Ignored. Default(2) used (1-CLASS1/2-CLASS2/3-CUSTOM) ,
,08-19 17:55:23.326  6623  6623 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: LE Power Class: To override, Before turning BT ON; setprop qcom.bt.le_dev_pwr_class <1 or 2 or 3> ,
,08-19 17:55:23.536  6626  6626 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Bluetooth QSoC firmware download succeeded, /dev/ttyHS0 qualcomm 3000000 08:ec:a9:50:76:27 ,
,08-19 17:55:23.546  6627  6627 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** ,
,08-19 17:55:23.576  6565  6587 I bt_vendor: bluetooth satus is on,
08-19 17:55:23.576  6565  6609 D bt_userial_mct: userial_open(port:0)
08-19 17:55:23.576  6565  6609 I bt_vendor: bt-vendor : BT_VND_OP_USERIAL_OPEN
,08-19 17:55:23.576  6565  6609 I bt_vendor: Done intiailizing UART,
,08-19 17:55:23.576  6565  6609 I bt_vendor: Done intiailizing UART
08-19 17:55:23.576  6565  6609 I bt_userial_mct: CMD=66, EVT=66, ACL_Out=67, ACL_In=67,
08-19 17:55:23.576  6565  6609 I bt_vendor: Bluetooth Firmware and transport layer are initialized
,08-19 17:55:23.576  6565  6629 D bt_userial_mct: Entering userial_read_thread()
,08-19 17:55:23.586  6565  6607 I         : BTE_InitTraceLevels -- TRC_HCI,
08-19 17:55:23.586  6565  6607 I         : BTE_InitTraceLevels -- TRC_L2CAP
08-19 17:55:23.586  6565  6607 I         : BTE_InitTraceLevels -- TRC_RFCOMM
,08-19 17:55:23.586  6565  6607 I         : BTE_InitTraceLevels -- TRC_AVDT
08-19 17:55:23.586  6565  6607 I         : BTE_InitTraceLevels -- TRC_AVRC
08-19 17:55:23.586  6565  6607 I         : BTE_InitTraceLevels -- TRC_A2D,
08-19 17:55:23.586  6565  6607 I         : BTE_InitTraceLevels -- TRC_BNEP
08-19 17:55:23.586  6565  6607 I         : BTE_InitTraceLevels -- TRC_BTM,
08-19 17:55:23.586  6565  6607 I         : BTE_InitTraceLevels -- TRC_GAP
08-19 17:55:23.586  6565  6607 I         : BTE_InitTraceLevels -- TRC_PAN
,08-19 17:55:23.586  6565  6607 I         : BTE_InitTraceLevels -- TRC_SAP
08-19 17:55:23.586  6565  6607 I         : BTE_InitTraceLevels -- TRC_SDP
,08-19 17:55:23.586  6565  6607 I         : BTE_InitTraceLevels -- TRC_GATT
08-19 17:55:23.586  6565  6607 I         : BTE_InitTraceLevels -- TRC_SMP
08-19 17:55:23.586  6565  6607 I         : BTE_InitTraceLevels -- TRC_BTAPP,
08-19 17:55:23.586  6565  6607 I         : BTE_InitTraceLevels -- TRC_BTIF
,08-19 17:55:23.586  6565  6607 I         : BTE_InitTraceLevels -- TRC_PROTOCOL
,08-19 17:55:23.676  6565  6607 W bt-l2cap: l2c_link_processs_ble_num_bufs 16
,08-19 17:55:23.686  6565  6607 E bt-btm  : BTM_SecRegister:p_cb_info->p_le_callback == 0xa41c7ed1 
,08-19 17:55:23.686  6565  6607 E bt-btm  : BTM_SecRegister: btm_cb.api.p_le_callback = 0xa41c7ed1 
,08-19 17:55:23.696  6565  6590 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 10 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 32 mNumOfOffloadedScanFilterSupported = 16 mOffloadedScanResultStorageBytes= 10240 mIsActivityAndEnergyReporting = true mAobleSupported = 0
,08-19 17:55:23.706  6565  6590 E bt-btif : Calling BTA_HhEnable
,08-19 17:55:23.706  6565  6590 E bt-btif : btif_storage_get_adapter_property service_mask:0x2120048
,08-19 17:55:23.706  6565  6590 D BluetoothAdapterProperties: Address is:08:EC:A9:50:76:27
,08-19 17:55:23.706  6565  6590 E BluetoothServiceJni: populateRssiValuesNative
,08-19 17:55:23.706  6565  6590 I bluedroid: getModelRssiValues
08-19 17:55:23.706  6565  6590 E BluetoothServiceJni: model_rssi_values_callback: low = -70, mid = -60, high = 127
,08-19 17:55:23.706  6565  6590 D BluetoothAdapterProperties: modelRssiValuesCallback, low, mid, high = -70,-60,127
,08-19 17:55:23.706  1015  1015 D SettingsProvider: name = bluetooth_name
,08-19 17:55:23.706  6565  6590 D BluetoothAdapterProperties: Name is: Thali Test (Galaxy A3)
,08-19 17:55:23.716  6220  6220 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-19 17:55:23.716  6565  6590 D BluetoothUtils: getBtEnabledContainers(): btContainers = []
,08-19 17:55:23.716  6565  6590 D BluetoothAdapterProperties: Scan Mode:20
,08-19 17:55:23.716  6565  6590 D BluetoothAdapterProperties: Discoverable Timeout:120
,08-19 17:55:23.716  6565  6590 D BluetoothAdapterProperties: LE Address is:C8:D9:53:A0:EC:4E
,08-19 17:55:23.726  6565  6590 E bt-btif : btif_handle_bluetooth_enable_evt: btif_core_radio_ref_count:1
08-19 17:55:23.726  6565  6590 E bt-btif : btif_sock_init, radio_req:0, rfc_init:0, vhci_init:0
,08-19 17:55:23.726  6565  6590 E bt-btif : btif_sock_init: !radio_req && !rfc_init
,08-19 17:55:23.726  6565  6590 E bt-btif : btif_sock_init: !vhci_init
,08-19 17:55:23.726  6565  6590 D IOP_DB_BT: db_open: file /etc/bluetooth/iop_bt.db
,08-19 17:55:23.726  6565  6629 E bt_mct  : hci lib postload completed
,08-19 17:55:23.726  6565  6590 D IOP_DB_BT: db_open: db_open : handle 3028189200l, read 13894 bytes onto local cache
08-19 17:55:23.726  6565  6590 D IOP_DB_BT: db_query: id __IOPFLAGS :: key __KEY_ENABLE_VERBOSE, value 1
,08-19 17:55:23.726  6565  6590 D IOP_DB_BT: db_query: result 1
,08-19 17:55:23.726  6565  6590 I         : iop_db_open: iop_db_open status 0
,08-19 17:55:23.726  6565  6590 D bte_conf: Device ID record 1 : primary
08-19 17:55:23.726  6565  6590 D bte_conf:   vendorId            = 0075
08-19 17:55:23.726  6565  6590 D bte_conf:   vendorIdSource      = 0001
08-19 17:55:23.726  6565  6590 D bte_conf:   product             = 0100
08-19 17:55:23.726  6565  6590 D bte_conf:   version             = 0200
08-19 17:55:23.726  6565  6590 D bte_conf:   clientExecutableURL = 
08-19 17:55:23.726  6565  6590 D bte_conf:   serviceDescription  = 
08-19 17:55:23.726  6565  6590 D bte_conf:   documentationURL    = 
08-19 17:55:23.726  6565  6590 D bte_conf: bte_load_did_conf no section named DID2.
,08-19 17:55:23.726  6565  6590 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
,08-19 17:55:23.726  6565  6587 D BluetoothAdapterState: CURRENT_STATE=PENDING, MSG = ENABLE_READY, isTurningOn=true, isTurningOff=false
,08-19 17:55:23.736  6565  6587 D BluetoothAdapterProperties: ScanMode =  20
,08-19 17:55:23.736  6565  6587 D BluetoothAdapterProperties: State =  11
,08-19 17:55:23.736  1015  1028 D SecContentProvider: uri = 3 selection = isDiscoverableEnabled
,08-19 17:55:23.736  6565  6587 D BluetoothAdapterProperties: Setting state to 12
08-19 17:55:23.736  6565  6587 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
,08-19 17:55:23.736  6565  6590 D BluetoothUtils: getBtEnabledContainers(): btContainers = []
08-19 17:55:23.736  6565  6590 D BluetoothAdapterProperties: Scan Mode:21
08-19 17:55:23.736  6565  6590 D BluetoothAdapterProperties: Discoverable Timeout:120
,08-19 17:55:23.736   323   323 I ServiceManager: Waiting for service AtCmdFwd...
,08-19 17:55:23.736  1015  1446 D SettingsProvider: name = bluetooth_a2dp_sink_mode
,08-19 17:55:23.736  1015  1446 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
,08-19 17:55:23.746  1015  1446 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-19 17:55:23.746  1015  1446 D SettingsProvider: selectionArgs: false
08-19 17:55:23.746  1015  1446 D SettingsProvider: selectionArgs: 1002
,08-19 17:55:23.746  1015  1446 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
,08-19 17:55:23.746  1015  1446 D SettingsProvider: ret = -1
,08-19 17:55:23.746  6565  6587 D BluetoothAdapterService: Bluetooth PBAP supproted is true
,08-19 17:55:23.746  6565  6587 D BluetoothAdapterService: updateAdapterState state is 12
,08-19 17:55:23.746  1015  1338 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,08-19 17:55:23.746  1015  1338 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pbap.BluetoothPbapService; callingUser = 0; userId(target) = 0
,08-19 17:55:23.746  1015  1338 W ActivityManager: userId = 0, bbcId = -10000
,08-19 17:55:23.756  1015  1338 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,08-19 17:55:23.756  1015  1338 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-19 17:55:23.756  6565  6587 D BluetoothAdapterService: Autoconnection is available 
08-19 17:55:23.756  6565  6587 D BluetoothAdapterService: updateAdapterState prevState = 11newState = 12
08-19 17:55:23.756  6565  6587 D BluetoothAdapterService: starting service from this receiver
,08-19 17:55:23.756  1015  1028 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-19 17:55:23.756  1015  1028 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.samsung.ble.BleAutoConnectService; callingUser = 0; userId(target) = 0
,08-19 17:55:23.756  1015  1028 W ActivityManager: userId = 0, bbcId = -10000
08-19 17:55:23.756  1015  1028 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-19 17:55:23.756  1015  1028 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-19 17:55:23.756  1412  1438 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,08-19 17:55:23.766  1015  1044 D ActivityManager: bindService callerProcessName:com.android.server.telecom, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
08-19 17:55:23.766  1015  1044 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,08-19 17:55:23.766  6565  6587 I BluetoothAdapterState: Entering On State from state = 11
,08-19 17:55:23.766  1015  1044 W ActivityManager: userId = 0, bbcId = -10000
08-19 17:55:23.766  1015  1044 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-19 17:55:23.766  1015  1044 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.server.telecom, destAppInfo.processName = com.android.bluetooth
,08-19 17:55:23.766  1412  1438 E BluetoothHeadset: BluetoothHeadset service is binded
08-19 17:55:23.766  1015  1044 D BluetoothPan: Binding service...
,08-19 17:55:23.766  1015  1044 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothPan
,08-19 17:55:23.766  1015  1044 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pan.PanService; callingUser = 0; userId(target) = 0
,08-19 17:55:23.766  6220  6220 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-19 17:55:23.766  6220  6220 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-19 17:55:23.766  6220  6220 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-19 17:55:23.766  6220  6220 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-19 17:55:23.766  6220  6220 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-19 17:55:23.766  6220  6220 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-19 17:55:23.766  6220  6220 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-19 17:55:23.766  6220  6220 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-19 17:55:23.766  1304  1315 D Bluetoothsap: onBluetoothStateChange: up=true
08-19 17:55:23.766  1304  1315 D Bluetoothsap: Binding service...
,08-19 17:55:23.766  1304  1315 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:2136 android.content.ContextWrapper.bindService:559 com.broadcom.bt.service.sap.BluetoothSap.doBind:186 com.broadcom.bt.service.sap.BluetoothSap$1.onBluetoothStateChange:156 android.bluetooth.IBluetoothStateChangeCallback$Stub.onTransact:55 
,08-19 17:55:23.776  6220  6220 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-19 17:55:23.776  1015  1044 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: com.broadcom.bt.service.sap.IBluetoothSap
08-19 17:55:23.776  1015  1044 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.broadcom.bt.service.sap.SapService; callingUser = 0; userId(target) = 0
,08-19 17:55:23.776  1015  1044 W ActivityManager: userId = 0, bbcId = -10000
,08-19 17:55:23.776  1015  1044 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,08-19 17:55:23.776  6565  6565 I BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED, state: 12
08-19 17:55:23.776  1015  1044 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,08-19 17:55:23.776  1304  1315 D Bluetoothsap: bindService called to Bluetooth SAP Service
,08-19 17:55:23.776  1304  6303 D BluetoothPbap: onBluetoothStateChange: up=true
,08-19 17:55:23.776  1015  1044 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothPbap
,08-19 17:55:23.776  1015  1044 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pbap.BluetoothPbapService; callingUser = 0; userId(target) = 0
,08-19 17:55:23.776  1015  1044 W ActivityManager: userId = 0, bbcId = -10000
08-19 17:55:23.776  1015  1044 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-19 17:55:23.776  1015  1044 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,08-19 17:55:23.786  1304  1325 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,08-19 17:55:23.786  1015  1044 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
,08-19 17:55:23.786  1015  1044 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,08-19 17:55:23.786  1015  1044 W ActivityManager: userId = 0, bbcId = -10000
08-19 17:55:23.786  1015  1044 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-19 17:55:23.786  1015  1044 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,08-19 17:55:23.786  1304  1325 E BluetoothHeadset: BluetoothHeadset service is binded
,08-19 17:55:23.786  1172  1192 D BluetoothAdapter: onBluetoothStateChange: up=true
08-19 17:55:23.786  1172  1192 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,08-19 17:55:23.796  1304  1304 D HeadsetProfile: Bluetooth service connected
,08-19 17:55:23.796  6565  6565 I BluetoothPbapService: Handler(): got msg=1
,08-19 17:55:23.796  1015  1015 D BluetoothPan: BluetoothPAN Proxy object connected
08-19 17:55:23.796  6323  6333 D BluetoothAdapter: onBluetoothStateChange: up=true
08-19 17:55:23.796  6323  6333 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,08-19 17:55:23.796  1015  1028 D SecContentProvider: uri = 4 selection = isProfileAuthorizedBySecurityPolicy
,08-19 17:55:23.796  1412  1431 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,08-19 17:55:23.796  1015  1044 D ActivityManager: bindService callerProcessName:com.android.server.telecom, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
08-19 17:55:23.796  1015  1044 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,08-19 17:55:23.796  1015  1044 W ActivityManager: userId = 0, bbcId = -10000
,08-19 17:55:23.806  1015  1044 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-19 17:55:23.806  1015  1044 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.server.telecom, destAppInfo.processName = com.android.bluetooth
08-19 17:55:23.806  1412  1431 E BluetoothHeadset: BluetoothHeadset service is binded
,08-19 17:55:23.806  1979  2172 D BluetoothAdapter: onBluetoothStateChange: up=true
08-19 17:55:23.806  1979  2172 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,08-19 17:55:23.806  6565  6633 V BluetoothPbapService: PBAP Service initSocket try: 0
08-19 17:55:23.806  6220  6233 D BluetoothAdapter: onBluetoothStateChange: up=true
08-19 17:55:23.806  6220  6233 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
08-19 17:55:23.806  1304  1304 D Bluetoothsap: BluetoothSAP Proxy object connected
08-19 17:55:23.806  1304  1304 D SapProfile: Bluetooth service connected
08-19 17:55:23.806  1304  1304 D Bluetoothsap: getConnectedDevices()
,08-19 17:55:23.806  6565  6573 D BluetoothA2dp: onBluetoothStateChange: up=true
08-19 17:55:23.806  6565  6591 D BluetoothAdapter: onBluetoothStateChange: up=true
08-19 17:55:23.806  6565  6591 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,08-19 17:55:23.806  1015  1044 D BluetoothAdapter: onBluetoothStateChange: up=true
08-19 17:55:23.806  1015  1044 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
08-19 17:55:23.806  1015  1044 D BluetoothA2dp: onBluetoothStateChange: up=true
08-19 17:55:23.806  1015  1044 D BluetoothA2dp: doBind(): CallingUid(myUserHandle) = 0
,08-19 17:55:23.806  1015  1044 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothA2dp
08-19 17:55:23.806  1015  1044 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
08-19 17:55:23.806  1015  1015 D BluetoothA2dp: Proxy object connected
,08-19 17:55:23.806  1412  6558 D BluetoothAdapter: onBluetoothStateChange: up=true
08-19 17:55:23.806  1412  6558 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,08-19 17:55:23.806  1304  1304 D BluetoothPbap: Proxy object connected
,08-19 17:55:23.806  1304  1304 D PbapServerProfile: Bluetooth service connected
08-19 17:55:23.806  1304  1325 D BluetoothAdapter: onBluetoothStateChange: up=true
08-19 17:55:23.806  1304  1325 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,08-19 17:55:23.806  6565  6633 D BluetoothSocket: bindListen(): myUserId = 0
08-19 17:55:23.806  6565  6633 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-19 17:55:23.806  1412  6355 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,08-19 17:55:23.806  1015  1044 D ActivityManager: bindService callerProcessName:com.android.server.telecom, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
08-19 17:55:23.806  1015  1044 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,08-19 17:55:23.806  1015  1044 W ActivityManager: userId = 0, bbcId = -10000
,08-19 17:55:23.816  1015  1044 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-19 17:55:23.816  1015  1044 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.server.telecom, destAppInfo.processName = com.android.bluetooth
08-19 17:55:23.816  6565  6633 D BluetoothSocket: bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[75]}
08-19 17:55:23.816  6565  6633 D BluetoothSocket: bindListen(), new LocalSocket 
08-19 17:55:23.816  6565  6633 D BluetoothSocket: bindListen(), new LocalSocket.getInputStream() 
08-19 17:55:23.816  6565  6633 D BluetoothSocket: bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@3ffef5e1
08-19 17:55:23.816  1412  6355 E BluetoothHeadset: BluetoothHeadset service is binded
08-19 17:55:23.816  6565  6633 D BluetoothSocket: channel: 19
08-19 17:55:23.816  6565  6633 D BluetoothPbapService: PBAP Socket is BluetoothServerSocket
,08-19 17:55:23.816  1304  1315 D BluetoothPan: Binding service...
,08-19 17:55:23.816  1015  1044 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothPan
,08-19 17:55:23.816  1015  1044 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pan.PanService; callingUser = 0; userId(target) = 0
,08-19 17:55:23.816  1015  1044 W ActivityManager: userId = 0, bbcId = -10000
,08-19 17:55:23.816  1015  1044 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-19 17:55:23.816  1015  1044 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,08-19 17:55:23.816  1304  1304 D BluetoothPan: BluetoothPAN Proxy object connected
,08-19 17:55:23.816  1304  1304 D PanProfile: Bluetooth service connected
,08-19 17:55:23.816  1304  1325 D BluetoothMap: onBluetoothStateChange: up=true
,08-19 17:55:23.816  1015  1044 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothMap
,08-19 17:55:23.816  1015  1044 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.map.BluetoothMapService; callingUser = 0; userId(target) = 0
,08-19 17:55:23.826  1015  1044 W ActivityManager: userId = 0, bbcId = -10000
,08-19 17:55:23.826  1015  1044 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-19 17:55:23.826  1015  1044 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,08-19 17:55:23.826  1304  1304 D BluetoothMap: Proxy object connected
,08-19 17:55:23.826  1304  1304 D MapProfile: Bluetooth service connected
08-19 17:55:23.826  1304  1304 D BluetoothMap: getConnectedDevices()
08-19 17:55:23.826  1015  1044 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
08-19 17:55:23.826  1015  1044 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
,08-19 17:55:23.826  1015  1044 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
08-19 17:55:23.826  1015  1044 E BluetoothHeadset: BluetoothHeadset service is binded
,08-19 17:55:23.826  1447  1459 D BluetoothAdapter: onBluetoothStateChange: up=true
08-19 17:55:23.826  1447  1459 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,08-19 17:55:23.826  1304  6303 D BluetoothInputDevice: onBluetoothStateChange: up=true
,08-19 17:55:23.826  1015  1044 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothInputDevice
08-19 17:55:23.826  1015  1044 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hid.HidService; callingUser = 0; userId(target) = 0
,08-19 17:55:23.826  1015  1044 W ActivityManager: userId = 0, bbcId = -10000
,08-19 17:55:23.826  1015  1044 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-19 17:55:23.826  1015  1044 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,08-19 17:55:23.836  1304  1304 D BluetoothInputDevice: Proxy object connected
,08-19 17:55:23.836  1304  1304 D HidProfile: Bluetooth service connected
,08-19 17:55:23.836  1427  1443 D BluetoothAdapter: onBluetoothStateChange: up=true
,08-19 17:55:23.836  1427  1443 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,08-19 17:55:23.836  1304  1315 D BluetoothA2dp: onBluetoothStateChange: up=true
,08-19 17:55:23.836  1304  1315 D BluetoothA2dp: doBind(): CallingUid(myUserHandle) = 0
,08-19 17:55:23.836  1015  1044 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothA2dp
08-19 17:55:23.836  1015  1044 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
,08-19 17:55:23.836  1015  1044 W ActivityManager: userId = 0, bbcId = -10000
08-19 17:55:23.836  1015  1044 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-19 17:55:23.836  1015  1044 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,08-19 17:55:23.836  1304  1304 D BluetoothA2dp: Proxy object connected
08-19 17:55:23.836  1304  1304 D A2dpProfile: Bluetooth service connected
,08-19 17:55:23.836  1447  2437 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,08-19 17:55:23.846  1015  1044 D ActivityManager: bindService callerProcessName:com.android.phone, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
08-19 17:55:23.846  1015  1044 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,08-19 17:55:23.846  1015  1044 W ActivityManager: userId = 0, bbcId = -10000
08-19 17:55:23.846  1015  1044 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,08-19 17:55:23.846  1015  1044 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = com.android.bluetooth
08-19 17:55:23.846  1447  2437 E BluetoothHeadset: BluetoothHeadset service is binded
,08-19 17:55:23.846  1015  1044 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothGatt
08-19 17:55:23.846  1015  1044 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.gatt.GattService; callingUser = 0; userId(target) = -2
,08-19 17:55:23.846  1015  1015 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
,08-19 17:55:23.846  1015  1015 I InputMethodManagerService: [BT Setting State] State =12
08-19 17:55:23.846  1015  1015 I InputMethodManagerService: [BT Setting off -> on] mBTKeyboardCount =0, KEYBOARD_BT(0)
,08-19 17:55:23.846  1172  1172 D BluetoothTile:  onBluetoothStateChange:
,08-19 17:55:23.856  1412  1412 D BluetoothHeadset: registerListener : 11, listenercom.android.server.telecom.wearable.BluetoothMessageListener@786d9c4, true
,08-19 17:55:23.856  1172  1172 D BluetoothTile:  onBluetoothPairedDevicesChanged:
08-19 17:55:23.856  1172  1172 D BluetoothTile: onReceive : android.bluetooth.adapter.action.STATE_CHANGED
08-19 17:55:23.856  1172  1172 D BluetoothTile:  getBluetoothState : 12
,08-19 17:55:23.856  1823  1823 I SamsungIME: STATE_CHANGED = 12, KEYBOARD_BT(0), mBTKeyboardCount =0
08-19 17:55:23.856  1172  1745 D BluetoothTile:  handleUpdatestate:false name:null
,08-19 17:55:23.856  1412  1412 D BluetoothHeadset: registerMessageListener
,08-19 17:55:23.856  1304  1304 V BluetoothEventManager: Received android.bluetooth.adapter.action.STATE_CHANGED
,08-19 17:55:23.856  6220  6220 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-19 17:55:23.856  1172  1745 D BluetoothTile:  handleUpdatestate:false name:null
,08-19 17:55:23.866  1015  3485 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,08-19 17:55:23.866  1015  3485 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.nearby.discovery.service.DiscoveryService; callingUser = 0; userId(target) = 0
,08-19 17:55:23.866  6565  6573 D HeadsetService: registerMessageListener
,08-19 17:55:23.866  6565  6573 D HeadsetService: registerMessageListener
,08-19 17:55:23.866  6565  6596 D HeadsetStateMachine: Disconnected process message: 70
08-19 17:55:23.866  6565  6596 D HeadsetStateMachine: processRegisterMessageListener : 11, com.samsung.bt.hfp.IMessageListener$Stub$Proxy@3b7f6f06
,08-19 17:55:23.866  1172  1745 D BluetoothTile:  handleUpdatestate:false name:null
,08-19 17:55:23.866  1412  1412 I Telecom : BluetoothPhoneService: handleMessage(7) / param null
08-19 17:55:23.866  1412  1412 I Telecom : BluetoothPhoneService: updateHeadsetWithCallState
,08-19 17:55:23.866  1015  3485 W ActivityManager: userId = 0, bbcId = -10000
08-19 17:55:23.866  1015  3485 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-19 17:55:23.866  1015  3485 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-19 17:55:23.876  1412  1412 I Telecom : BluetoothPhoneService: getCurrentCallPhoneType, Defalut Phonetype : 1
,08-19 17:55:23.876  1412  1412 I Telecom : BluetoothPhoneService: getCurrentCallPhoneType, Current Phonetype : 1
08-19 17:55:23.876  1412  1412 I Telecom : BluetoothPhoneService: updateHeadsetWithCallState numActive 0, numHeld 0, callState 6, ringing number [da39a3ee5e6b4b0d3255bfef95601890afd80709], ringing type 128
08-19 17:55:23.876  1015  3492 D StatusBarManagerService: setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
,08-19 17:55:23.876  1015  1470 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=true
08-19 17:55:23.876  1304  1304 W LocalBluetoothProfileManager: Warning: MAP profile was previously added but the UUID is now missing.
,08-19 17:55:23.876  1172  1172 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
,08-19 17:55:23.876  1304  1304 W LocalBluetoothProfileManager: Warning: PBAP profile was previously added but the UUID is now missing.
,08-19 17:55:23.876  6565  6635 D BluetoothMapMasInstance: set MAP SDP message type : 1
,08-19 17:55:23.876  6565  6596 D HeadsetStateMachine: Disconnected process message: 9
,08-19 17:55:23.876  6565  6596 D HeadsetStateMachine: mNumActive: 0 mNumHeld: 0 mCallState: 6
,08-19 17:55:23.876  1304  1304 W LocalBluetoothProfileManager: Warning: SAP profile was previously added but the UUID is now missing.
08-19 17:55:23.876  1304  1304 W LocalBluetoothProfileManager: Warning: HID profile was previously added but the UUID is now missing.
,08-19 17:55:23.886  6565  6635 D BluetoothSocket: bindListen(): myUserId = 0
08-19 17:55:23.886  6565  6635 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-19 17:55:23.886  6565  6635 D BluetoothSocket: bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[77]}
08-19 17:55:23.886  6565  6635 D BluetoothSocket: bindListen(), new LocalSocket 
08-19 17:55:23.886  6565  6635 D BluetoothSocket: bindListen(), new LocalSocket.getInputStream() 
08-19 17:55:23.886  6565  6635 D BluetoothSocket: bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@dba49c7
,08-19 17:55:23.886  6565  6635 D BluetoothSocket: channel: 5
,08-19 17:55:23.886   286   746 D audio_hw_primary: adev_set_parameters: enter: A2dpSuspended=false
08-19 17:55:23.886   286   746 V voice   : voice_set_parameters: enter: A2dpSuspended=false
08-19 17:55:23.886   286   746 V voice   : voice_set_parameters: exit with code(-2)
08-19 17:55:23.886   286   746 V msm8974_platform: platform_set_parameters: enter: A2dpSuspended=false
08-19 17:55:23.886   286   746 V msm8974_platform: platform_set_parameters: exit with code(-2)
08-19 17:55:23.886   286   746 D audio_hw_hfp: audio_extn_hfp_set_parameters: enter
08-19 17:55:23.886   286   746 V audio_hw_primary: adev_set_parameters: exit
,08-19 17:55:23.896  6565  6596 E HeadsetStateMachine: terminateScoUsingVirtualVoiceCall:No present call to terminate
08-19 17:55:23.896  6220  6275 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-19 17:55:23.896  6220  6275 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-19 17:55:23.896  6220  6275 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-19 17:55:23.896  6220  6275 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-19 17:55:23.896  6220  6275 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-19 17:55:23.896  6220  6275 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-19 17:55:23.896  6220  6275 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-19 17:55:23.896  6220  6275 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-19 17:55:23.896  6220  6275 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-19 17:55:23.896  6220  6275 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-19 17:55:23.896  6220  6275 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@145a4748 added. We now have 8 listener(s)
08-19 17:55:23.896  6220  6275 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-19 17:55:23.896  1304  1304 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-19 17:55:23.896  1015  3485 D SecContentProvider: uri = 18 selection = isWifiEnabled
,08-19 17:55:23.896  1015  3485 D SecContentProvider2: uri = 20 selection = isWifiStateChangeAllowed
08-19 17:55:23.896  1015  3485 D SecContentProvider2: mCursor = null
08-19 17:55:23.896  1015  3494 D ActivityManager: startService callerProcessName:com.android.settings, calleePkgName: com.android.settings
,08-19 17:55:23.906  1015  3494 D ActivityManager: retrieveServiceLocked(): component = com.android.settings/com.android.settings.bluetooth.DockService; callingUser = 0; userId(target) = 0
,08-19 17:55:23.906  1015  3485 D SettingsProvider: name = wifi_on
08-19 17:55:23.906  1015  3485 D WifiService: setWifiEnabled: false pid=6220, uid=10171
,08-19 17:55:23.906  1015  3494 W ActivityManager: userId = 0, bbcId = -10000
08-19 17:55:23.906  1015  3494 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-19 17:55:23.906  1015  3494 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.settings
,08-19 17:55:23.906  1304  1304 D DockEventReceiver: finishStartingService: stopping service
,08-19 17:55:23.906  1304  1304 D BluetoothNotiBroadcastReceiver: onReceive
,08-19 17:55:23.916  6220  6275 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-19 17:55:23.916  1015  1301 D SecContentProvider: uri = 18 selection = isWifiEnabled
,08-19 17:55:23.916  1172  1172 V BluetoothStatusReceiver: Received android.bluetooth.adapter.action.STATE_CHANGED
,08-19 17:55:23.916  1172  1172 D BluetoothStatusReceiver: AdapterStateChanged :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 12
,08-19 17:55:23.916  1015  1301 D SecContentProvider2: uri = 20 selection = isWifiStateChangeAllowed
08-19 17:55:23.916  1015  1301 D SecContentProvider2: mCursor = null
,08-19 17:55:23.916  1015  1301 D WifiService: setWifiEnabled: true pid=6220, uid=10171
,08-19 17:55:23.916  1015  1301 W ActivityManager: Permission Denial: getCurrentUser() from pid=6220, uid=10171 requires android.permission.INTERACT_ACROSS_USERS
,08-19 17:55:23.916  1015  1301 W WifiService: Failed getting userId using ActivityManagerNative
08-19 17:55:23.916  1015  1301 W WifiService: java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=6220, uid=10171 requires android.permission.INTERACT_ACROSS_USERS
08-19 17:55:23.916  1015  1301 W WifiService: 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:23972)
08-19 17:55:23.916  1015  1301 W WifiService: 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2216)
08-19 17:55:23.916  1015  1301 W WifiService: 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2204)
08-19 17:55:23.916  1015  1301 W WifiService: 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:223)
08-19 17:55:23.916  1015  1301 W WifiService: 	at android.os.Binder.execTransact(Binder.java:446)
,08-19 17:55:23.916  1015  1301 D SettingsProvider: name = wifi_on
,08-19 17:55:23.926  6565  6565 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@8bc66ff
,08-19 17:55:23.926  6565  6565 D BtConfig.SecureMode: isSecureModeOn:false
,08-19 17:55:23.936  1015  1123 E WifiHW  : ##################### set firmware type 0 #####################
,08-19 17:55:23.936  1015  1027 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-19 17:55:23.936  1015  1027 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.opp.BluetoothOppService; callingUser = 0; userId(target) = 0,
,08-19 17:55:23.946  1015  1027 W ActivityManager: userId = 0, bbcId = -10000,
08-19 17:55:23.946  1015  1027 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-19 17:55:23.946  1015  1027 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-19 17:55:23.976  1015  1027 D SecContentProvider: uri = 4 selection = isProfileAuthorizedBySecurityPolicy
,08-19 17:55:23.976  1979  1979 D EasyUnlockReceiver: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.easyunlock.authorization.BluetoothStateChangeReceiver (has extras) }.
,08-19 17:55:23.976  1015  1028 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
08-19 17:55:23.976  1015  1028 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.easyunlock.authorization.InitializerIntentService; callingUser = 0; userId(target) = 0
,08-19 17:55:23.986  1015  1028 W ActivityManager: userId = 0, bbcId = -10000
,08-19 17:55:23.986  1015  1028 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-19 17:55:23.986  1015  1028 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-19 17:55:23.986  1979  6649 D EasyUnlockInitService: Handling intent for initializer IntentService.
,08-19 17:55:23.986  1979  1979 D BtServices: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.proximity.BluetoothServicesAdapterStateChangeReceiver (has extras) }.
,08-19 17:55:23.996  1015  1768 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-19 17:55:23.996  1015  1768 W ActivityManager: userId = 0, bbcId = -10000
,08-19 17:55:23.996  1015  1768 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-19 17:55:23.996  1015  1768 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-19 17:55:24.006  6565  6650 D BluetoothSocket: bindListen(): myUserId = 0
08-19 17:55:24.006  6565  6650 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-19 17:55:24.006  6565  6650 D BluetoothSocket: bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[79]}
08-19 17:55:24.006  6565  6650 D BluetoothSocket: bindListen(), new LocalSocket 
08-19 17:55:24.006  6565  6650 D BluetoothSocket: bindListen(), new LocalSocket.getInputStream() 
08-19 17:55:24.006  6565  6650 D BluetoothSocket: bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@2707bb63
08-19 17:55:24.006  6565  6650 D BluetoothSocket: channel: 12
,08-19 17:55:24.006  6565  6650 I BtOppRfcommListener: Accept thread started.
,08-19 17:55:24.016  1015  1482 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-19 17:55:24.016  1015  1482 W ActivityManager: userId = 0, bbcId = -10000
,08-19 17:55:24.016  1015  1482 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-19 17:55:24.016  1015  1482 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-19 17:55:24.026  1979  6649 D EasyUnlockInitService: Not initializing EasyUnlock: remote_devices=0, bluetooth_on=true
,08-19 17:55:24.276  1015  1042 D Tethering: interfaceAdded wlan0
,08-19 17:55:24.276  1015  1042 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
,08-19 17:55:24.276  1015  1042 D Tethering: interfaceLinkStateChanged wlan0, false
08-19 17:55:24.276  1015  1042 D Tethering: interfaceStatusChanged wlan0, false
,08-19 17:55:24.276  1015  1128 E Tethering: No numeric data
,08-19 17:55:24.286  1015  1128 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
08-19 17:55:24.286  1015  1128 D Tethering: clearTetheredNotification()
,08-19 17:55:24.286  1015  1128 D Tethering: InitialState.processMessage what=4
,08-19 17:55:24.286  1015  1042 D Tethering: interfaceAdded p2p0,
08-19 17:55:24.286  1015  1120 D NtpTrustedTime: forceRefresh() from cache miss
08-19 17:55:24.286  1172  1172 D HotspotTile: onReceive : android.net.conn.TETHER_STATE_CHANGED
08-19 17:55:24.286  1015  1128 E Tethering: No numeric data
08-19 17:55:24.286  1172  1172 D HotspotTile: updateTetherState():false, false
,08-19 17:55:24.296  1015  1128 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
08-19 17:55:24.296  1015  1128 D Tethering: clearTetheredNotification()
,08-19 17:55:24.296  1015  1042 D Tethering: p2p0 is not a tetherable iface, ignoring
,08-19 17:55:24.296  1172  1172 D HotspotTile: onReceive : android.net.conn.TETHER_STATE_CHANGED
08-19 17:55:24.296  1172  1172 D HotspotTile: updateTetherState():false, false
,08-19 17:55:24.296  1015  1042 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
,08-19 17:55:24.296  1015  1042 D Tethering: interfaceLinkStateChanged p2p0, false
08-19 17:55:24.296  1015  1042 D Tethering: interfaceStatusChanged p2p0, false
,08-19 17:55:24.306   281   971 I WifiHW  : wifi_change_fw_path(): fwpath = sta
08-19 17:55:24.306   281   971 D SoftapController: Softap fwReload - Ok
,08-19 17:55:24.306   281   967 D EnterpriseController: mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
,08-19 17:55:24.306   281   967 D Netd    : getNetworkForDns: using netid 0 for uid 1000
08-19 17:55:24.306   281   971 D CommandListener: Setting iface cfg
08-19 17:55:24.306   281   971 D CommandListener: Trying to bring down wlan0
08-19 17:55:24.316   281   971 D CommandListener: Clearing all IP addresses on wlan0
,08-19 17:55:24.316   281   967 D EnterpriseController: mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0,
08-19 17:55:24.316   281   967 D Netd    : getNetworkForDns: using netid 0 for uid 1000
,08-19 17:55:24.316  1015  1120 D NtpTrustedTime: forceRefresh Fail.
,08-19 17:55:24.316  1015  1120 V NetworkStats: performPollLocked(flags=0x1)
,08-19 17:55:24.316  1015  1123 E WifiHW  : supplicant_name : p2p_supplicant
,08-19 17:55:24.316  1015  1120 D NetworkStatsFactory: UpdateStatsForKnox updated
08-19 17:55:24.316  1015  1120 D NetworkStatsFactory: UpdateStatsForKnox main else ---
,08-19 17:55:24.326  1015  1123 D WifiMonitor: startMonitoring(wlan0) with mConnected = false,
,08-19 17:55:24.326  1015  1120 V NetworkStats: performPollLocked() took 7ms,
,08-19 17:55:24.326  1015  1120 D NtpTrustedTime: forceRefresh() from cache miss
,08-19 17:55:24.326  1015  1120 D NtpTrustedTime: forceRefresh Fail.
,08-19 17:55:24.326  1015  1120 V NetworkStats: performPollLocked(flags=0x1)
08-19 17:55:24.326  1015  1120 D NetworkStatsFactory: UpdateStatsForKnox updated
08-19 17:55:24.326  1015  1120 D NetworkStatsFactory: UpdateStatsForKnox main else ---
,08-19 17:55:24.336  1015  1120 V NetworkStats: performPollLocked() took 5ms
,08-19 17:55:24.336  1172  1172 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x0/(null) mQSWifiIconId=0x0/(null) mWifiActivityIconId=0x0/(null) mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,08-19 17:55:24.336  1172  1172 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=false enabledDesc:null
08-19 17:55:24.336  1172  1172 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-19 17:55:24.336  1172  1172 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-19 17:55:24.336  1172  1172 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-19 17:55:24.336  1172  1172 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-19 17:55:24.346  1172  1172 D STATUSBAR-WifiQuickSettingButton: onReceive : android.net.wifi.WIFI_STATE_CHANGED
08-19 17:55:24.346  1172  1172 D STATUSBAR-WifiQuickSettingButton: Wifi onReceive(2)
,08-19 17:55:24.346  1172  1172 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
,08-19 17:55:24.346  1172  1172 D HotspotTile: onReceive : 2, 0
08-19 17:55:24.346  1172  1745 D STATUSBAR-QSTileView: onStateChanged: Wi-Fi
,08-19 17:55:24.346  1304  1304 D WifiCredService: Action received :android.net.wifi.WIFI_STATE_CHANGED
,08-19 17:55:24.346  1015  1121 D NtpTrustedTime: forceRefresh() from cache miss
,08-19 17:55:24.356  1015  1121 D NtpTrustedTime: forceRefresh Fail.
,08-19 17:55:24.356  6220  6220 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-19 17:55:24.356  1015  1338 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
08-19 17:55:24.356  1015  1338 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,08-19 17:55:24.356  1015  1338 W ActivityManager: userId = 0, bbcId = -10000
,08-19 17:55:24.356  1015  1338 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-19 17:55:24.356  1015  1338 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,08-19 17:55:24.356  1619  1619 I Hs20UtilService: Starting #12
08-19 17:55:24.356  1015  1121 D NtpTrustedTime: forceRefresh() from cache miss
,08-19 17:55:24.366  1015  1121 D NtpTrustedTime: forceRefresh Fail.
08-19 17:55:24.366  1619  1650 I Hs20UtilService: Message received 5011
,08-19 17:55:24.366  6394  6394 D SecurityLogAgent: KnoxConfiguration : Current State = 1
,08-19 17:55:24.366  6394  6394 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
,08-19 17:55:24.366  6394  6394 D SecurityLogAgent: StateMachine : Current State = 1
08-19 17:55:24.366  6394  6394 D SecurityLogAgent: StateMachine : Changed Current State = 1
,08-19 17:55:24.386  6660  6660 I wpa_supplicant: [wpa_supplicant_init]: use SECRIL
,08-19 17:55:24.386  6660  6660 I wpa_supplicant: Successfully initialized wpa_supplicant
,08-19 17:55:24.386  6660  6660 I SecureStorage: [INFO]: SPID(0x00000000)Checking if this device supports Secure Storage
,08-19 17:55:24.396  6660  6660 I SecureStorage: [INFO]: SPID(0x00000000)This device supports Secure Storage
08-19 17:55:24.396   369   369 I SecureStorage: [INFO]: SPID(0x00000002)Credentials: uid 1010, gid 1010, pid 6660
08-19 17:55:24.396   369   369 I SecureStorage: [INFO]: SPID(0x00000002)Received function mask & code: 0x0000010C
08-19 17:55:24.396  6660  6660 I SecureStorage: [INFO]: SPID(0x00000000)SS Daemon is running
08-19 17:55:24.396  6660  6660 I wpa_supplicant: ssSupport state is = 1
08-19 17:55:24.396  6660  6660 I wpa_supplicant: >>>>> GET KEY, IV <<<<<
08-19 17:55:24.396  6660  6660 I SecureStorage: [INFO]: SPID(0x00000000)Processing data
08-19 17:55:24.396   369   369 I SecureStorage: [INFO]: SPID(0x00000002)Credentials: uid 1010, gid 1010, pid 6660
08-19 17:55:24.396   369   369 I SecureStorage: [INFO]: SPID(0x00000002)Received function mask & code: 0x00000106
,08-19 17:55:24.536   369   369 I SecureStorage: [INFO]: SPID(0x00000003)Secure Storage Daemon finished processing with result: 0,
,08-19 17:55:24.536  6660  6660 I SecureStorage: [INFO]: SPID(0x00000003)Processing data has been completed
,08-19 17:55:24.586  6660  6660 I wpa_supplicant: Ctrl_iface: loading cred from phone,
08-19 17:55:24.586  6660  6660 I SecureStorage: [INFO]: SPID(0x00000003)Checking if this device supports Secure Storage
,08-19 17:55:24.596  6660  6660 I SecureStorage: [INFO]: SPID(0x00000003)This device supports Secure Storage
08-19 17:55:24.596   369   369 I SecureStorage: [INFO]: SPID(0x00000003)Credentials: uid 1010, gid 1010, pid 6660,
08-19 17:55:24.596   369   369 I SecureStorage: [INFO]: SPID(0x00000003)Received function mask & code: 0x0000010C
08-19 17:55:24.596  6660  6660 I SecureStorage: [INFO]: SPID(0x00000003)SS Daemon is running
08-19 17:55:24.596  6660  6660 I wpa_supplicant: ssSupport state is = 1
08-19 17:55:24.596  6660  6660 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0,
,08-19 17:55:24.596  6660  6660 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
08-19 17:55:24.596  6660  6660 E wpa_supplicant: SIM READ ERROR
08-19 17:55:24.596  6660  6660 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
08-19 17:55:24.596  6660  6660 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
08-19 17:55:24.596  6660  6660 E wpa_supplicant: SIM READ ERROR
08-19 17:55:24.596  6660  6660 I wpa_supplicant: Blacklist: Clear (all) 
08-19 17:55:24.596  6660  6660 I wpa_supplicant: wpa_default_ap_write_once
08-19 17:55:24.596  6660  6660 I wpa_supplicant: There is no /data/misc/wifi/default_ap.check. Start copy default ap
08-19 17:55:24.596  6660  6660 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
08-19 17:55:24.596  6660  6660 E wpa_supplicant: getSavedIMSI cannot open /data/misc/wifi/.kmem: No such file or directory
08-19 17:55:24.596  6660  6660 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
08-19 17:55:24.596  6660  6660 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
08-19 17:55:24.596  6660  6660 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,08-19 17:55:24.606  1015  1042 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
,08-19 17:55:24.606  1015  1042 D Tethering: interfaceLinkStateChanged wlan0, false
,08-19 17:55:24.606  1015  1042 D Tethering: interfaceStatusChanged wlan0, false
,08-19 17:55:24.686  6660  6660 I wpa_supplicant: wlan0: Setting scan request: 0 sec 100000 usec,
,08-19 17:55:24.736   323   323 I ServiceManager: Waiting for service AtCmdFwd...
,08-19 17:55:24.816  1015  2017 V SAMP_SPCM_test: CSC File load.. 
,08-19 17:55:24.826  1015  2017 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-application,
08-19 17:55:24.836  1015  2017 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-bluetooth
08-19 17:55:24.836  1015  2017 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-device-inventory
08-19 17:55:24.836  1015  2017 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-date-time
,08-19 17:55:24.836  1015  2017 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-exchange-account
08-19 17:55:24.836  1015  2017 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-roaming
08-19 17:55:24.836  1015  2017 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-wifi
,08-19 17:55:24.836  1015  2017 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-security
08-19 17:55:24.836  1015  2017 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-email-account
08-19 17:55:24.836  1015  2017 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-hardware-control
08-19 17:55:24.836  1015  2017 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-tethering
,08-19 17:55:24.836  1015  2017 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-location
08-19 17:55:24.836  1015  2017 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-calling
08-19 17:55:24.836  1015  2017 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-email
,08-19 17:55:24.836  1015  2017 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-vpn
08-19 17:55:24.836  1015  2017 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-apn-settings
08-19 17:55:24.836  1015  2017 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-browser-settings
,08-19 17:55:24.836  1015  2017 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-phone-restriction
08-19 17:55:24.836  1015  2017 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-firewall
08-19 17:55:24.836  1015  2017 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-enterprise-vpn
,08-19 17:55:24.836  1015  2017 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-data-time
,08-19 17:55:24.866  1015  2017 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-application
,08-19 17:55:24.876  1015  2017 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-bluetooth
08-19 17:55:24.876  1015  2017 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-device-inventory
08-19 17:55:24.876  1015  2017 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-date-time
08-19 17:55:24.876  1015  2017 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-exchange-account
08-19 17:55:24.876  1015  2017 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-roaming
08-19 17:55:24.876  1015  2017 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-wifi
08-19 17:55:24.876  1015  2017 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-security
08-19 17:55:24.876  1015  2017 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-email-account
08-19 17:55:24.876  1015  2017 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-hardware-control
08-19 17:55:24.876  1015  2017 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-tethering
08-19 17:55:24.876  1015  2017 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-location
08-19 17:55:24.876  1015  2017 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-calling
08-19 17:55:24.876  1015  2017 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-email
08-19 17:55:24.876  1015  2017 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-vpn
08-19 17:55:24.876  1015  2017 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-apn-settings
08-19 17:55:24.876  1015  2017 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-browser-settings
08-19 17:55:24.876  1015  2017 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-phone-restriction
08-19 17:55:24.876  1015  2017 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-firewall
08-19 17:55:24.876  1015  2017 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-enterprise-vpn
08-19 17:55:24.876  1015  2017 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-data-time
,08-19 17:55:24.886  1015  2017 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: history-password,
08-19 17:55:24.886  1015  2017 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: allow-attachments,
08-19 17:55:24.886  1015  2017 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: limit-attachments
,08-19 17:55:24.886  1015  2017 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: allow-camera
,08-19 17:55:24.886  1015  2017 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: allow-htmlemail
,08-19 17:55:24.886  1015  2017 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: require-manualsyncroaming
,08-19 17:55:24.886  1015  2017 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: min-passwordcomplexchars,
08-19 17:55:24.886  1015  2017 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: max-calendarage
,08-19 17:55:24.886  1015  2017 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: max-emailage
08-19 17:55:24.886  1015  2017 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: max-emailbodytruncsize
,08-19 17:55:24.886  1015  2017 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: max-htmlemailbodytruncsize,
08-19 17:55:24.886  1015  2017 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: require-signedsmimemessages
,08-19 17:55:24.886  1015  2017 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: require-encryptedsmimemessages
08-19 17:55:24.886  1015  2017 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: require-signedsmimealgorithm
,08-19 17:55:24.886  1015  2017 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: require-encryptionsmimealgorithm
08-19 17:55:24.886  1015  2017 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: allow-smimeencryptionalgonegotiation
08-19 17:55:24.886  1015  2017 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: allow-smimesoftcerts,
08-19 17:55:24.886  1015  2017 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: require-device-encryption
08-19 17:55:24.886  1015  2017 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-application
,08-19 17:55:24.886  1015  2017 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-bluetooth
08-19 17:55:24.886  1015  2017 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-device-inventory
08-19 17:55:24.886  1015  2017 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-date-time
,08-19 17:55:24.886  1015  2017 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-exchange-account
08-19 17:55:24.886  1015  2017 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-roaming
08-19 17:55:24.886  1015  2017 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-wifi,
08-19 17:55:24.886  1015  2017 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-security
08-19 17:55:24.886  1015  2017 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-email-account
08-19 17:55:24.886  1015  2017 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-hardware-control
,08-19 17:55:24.886  1015  2017 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-tethering
08-19 17:55:24.886  1015  2017 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-location
,08-19 17:55:24.886  1015  2017 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-calling
08-19 17:55:24.886  1015  2017 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-email,
08-19 17:55:24.886  1015  2017 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-vpn
08-19 17:55:24.886  1015  2017 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-apn-settings
08-19 17:55:24.886  1015  2017 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-browser-settings
08-19 17:55:24.886  1015  2017 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-phone-restriction
08-19 17:55:24.886  1015  2017 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-firewall
08-19 17:55:24.886  1015  2017 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-enterprise-vpn
08-19 17:55:24.886  1015  2017 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-data-time
,08-19 17:55:24.906  1015  2017 E SAMP_SPCMtest: setPackageLockingTimeBySPCM() :72
,08-19 17:55:24.936  6660  6660 I wpa_supplicant: wlan0: State: DISCONNECTED -> DISCONNECTED,
,08-19 17:55:24.936  6660  6660 I SecureStorage: [INFO]: SPID(0x00000003)Checking if this device supports Secure Storage,
,08-19 17:55:24.956  6660  6660 I SecureStorage: [INFO]: SPID(0x00000003)This device supports Secure Storage,
08-19 17:55:24.956   369   369 I SecureStorage: [INFO]: SPID(0x00000003)Credentials: uid 1010, gid 1010, pid 6660
08-19 17:55:24.956   369   369 I SecureStorage: [INFO]: SPID(0x00000003)Received function mask & code: 0x0000010C
,08-19 17:55:24.956  6660  6660 I SecureStorage: [INFO]: SPID(0x00000003)SS Daemon is running
08-19 17:55:24.956  6660  6660 I wpa_supplicant: ssSupport state is = 1
08-19 17:55:24.956  6660  6660 I wpa_supplicant: Ctrl_iface: loading cred from phone
08-19 17:55:24.956  6660  6660 I SecureStorage: [INFO]: SPID(0x00000003)Checking if this device supports Secure Storage
,08-19 17:55:24.966  6660  6660 I SecureStorage: [INFO]: SPID(0x00000003)This device supports Secure Storage,
08-19 17:55:24.966   369   369 I SecureStorage: [INFO]: SPID(0x00000003)Credentials: uid 1010, gid 1010, pid 6660
08-19 17:55:24.966   369   369 I SecureStorage: [INFO]: SPID(0x00000003)Received function mask & code: 0x0000010C,
,08-19 17:55:24.966  6660  6660 I SecureStorage: [INFO]: SPID(0x00000003)SS Daemon is running
08-19 17:55:24.976  1015  1042 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
08-19 17:55:24.966  6660  6660 I wpa_supplicant: ssSupport state is = 1
08-19 17:55:24.966  6660  6660 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
08-19 17:55:24.966  6660  6660 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
08-19 17:55:24.966  6660  6660 E wpa_supplicant: SIM READ ERROR
08-19 17:55:24.966  6660  6660 I wpa_supplicant: wpa_default_ap_write_once
08-19 17:55:24.966  6660  6660 I wpa_supplicant: There is no /data/misc/wifi/default_ap.check. Start copy default ap
08-19 17:55:24.966  6660  6660 I wpa_supplicant: rfkill: Cannot open RFKILL control device
08-19 17:55:24.976  1015  1042 D Tethering: interfaceLinkStateChanged p2p0, false
08-19 17:55:24.976  1015  1042 D Tethering: interfaceStatusChanged p2p0, false
,08-19 17:55:24.976  1015  1042 D Tethering: interfaceLinkStateChanged p2p0, false
08-19 17:55:24.976  1015  1042 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
08-19 17:55:24.976  1015  1042 D Tethering: interfaceStatusChanged p2p0, false,
,08-19 17:55:25.016  6660  6660 I wpa_supplicant: p2p0: State: DISCONNECTED -> INACTIVE,
08-19 17:55:25.016  6660  6660 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=-1 state=2 BSSID=00.00.00 SSID=
,08-19 17:55:25.166  6660  6660 I wpa_supplicant: p2p0: State: INACTIVE -> DISCONNECTED
,08-19 17:55:25.166  6660  6660 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=-1 state=0 BSSID=00.00.00 SSID=
08-19 17:55:25.166  6660  6660 I wpa_supplicant: Skip scan - bUseNetwork false
,08-19 17:55:25.176  1015  1123 E WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:2,
,08-19 17:55:25.176  1015  1123 D WifiNative-wlan0: callSECApiBoolean - ID [21],
08-19 17:55:25.176  6660  6660 I wpa_supplicant: HOTSPOT20_ENABLE called
08-19 17:55:25.176  6660  6660 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0,
08-19 17:55:25.176  6660  6660 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
08-19 17:55:25.176  6660  6660 E wpa_supplicant: SIM READ ERROR
08-19 17:55:25.176  6660  6660 I wpa_supplicant: Blacklist: Clear (all) 
,08-19 17:55:25.186  6660  6660 I wpa_supplicant: wlan0: Setting scan request: 0 sec 0 usec,
,08-19 17:55:25.196  1172  1172 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x0/(null) mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth,
08-19 17:55:25.196  1172  1172 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
08-19 17:55:25.196  1172  1172 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false),
08-19 17:55:25.196  1172  1172 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-19 17:55:25.196  1172  1172 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false),
08-19 17:55:25.196  1172  1172 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false),
08-19 17:55:25.196  1172  1172 D STATUSBAR-WifiQuickSettingButton: onReceive : android.net.wifi.WIFI_STATE_CHANGED
08-19 17:55:25.206  1172  1745 D STATUSBAR-QSTileView: onStateChanged: Wi-Fi
08-19 17:55:25.196  1172  1172 D STATUSBAR-WifiQuickSettingButton: Wifi onReceive(3)
08-19 17:55:25.206  1172  1172 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
08-19 17:55:25.206  6660  6660 I wpa_supplicant: Skip scan - bUseNetwork false
,08-19 17:55:25.206  1015  1123 D WifiConfigStore: Loading config and enabling all networks ,
08-19 17:55:25.206  1172  1172 D HotspotTile: onReceive : 3, 0
,08-19 17:55:25.206  1304  1304 D WifiCredService: Action received :android.net.wifi.WIFI_STATE_CHANGED,
,08-19 17:55:25.216  6220  6220 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-19 17:55:25.216  6220  6220 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-19 17:55:25.216  6220  6220 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-19 17:55:25.216  6220  6220 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-19 17:55:25.216  6220  6220 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-19 17:55:25.216  6220  6220 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-19 17:55:25.216  6220  6220 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-19 17:55:25.216  6220  6220 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-19 17:55:25.216  1015  1123 E WifiConfigStore: Not a HS20
,08-19 17:55:25.216  1015  1123 E WifiConfigStore: Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
,08-19 17:55:25.216  6220  6220 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-19 17:55:25.226  1015  1123 D WifiNative-wlan0: callSECApiInt - ID [65]
,08-19 17:55:25.226  1015  1123 D WifiNative-wlan0: callSECApiBoolean - ID [13]
08-19 17:55:25.226  6660  6660 I wpa_supplicant: USE_NETWORK : USE_NETWORK ON
08-19 17:55:25.226  6660  6660 I wpa_supplicant: wlan0: Setting scan request: 8 sec 0 usec
,08-19 17:55:25.226  6660  6660 I wpa_supplicant: reset timer : RESET_TIMER 0
08-19 17:55:25.226  6660  6660 I wpa_supplicant: P2P: Current p2p state = IDLE
08-19 17:55:25.226  6660  6660 I wpa_supplicant: wlan0: State: DISCONNECTED -> SCANNING
08-19 17:55:25.226  6660  6660 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00.00.00 SSID=
08-19 17:55:25.226  6660  6660 I wpa_supplicant: First Scan Start
08-19 17:55:25.226  6660  6660 I wpa_supplicant: Scan requested (ret=0) - scan timeout 30 seconds
,08-19 17:55:25.236  1015  3485 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
,08-19 17:55:25.236  1015  3485 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,08-19 17:55:25.236  1015  3485 W ActivityManager: userId = 0, bbcId = -10000
,08-19 17:55:25.236  1015  3485 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-19 17:55:25.236  1015  3485 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,08-19 17:55:25.236  1619  1619 I Hs20UtilService: Starting #13
,08-19 17:55:25.236  1015  1123 D WifiNative-wlan0: Setting external_sim to 1
08-19 17:55:25.236  1015  1123 D WifiStateMachine: Setting OUI to DA-A1-19
08-19 17:55:25.236  1015  1123 I WifiNative-HAL: startHal
08-19 17:55:25.236  1015  1123 E wifi    : getStaticLongField sWifiHalHandle 0x9d5c488c
08-19 17:55:25.236  1015  1123 I WifiNative-HAL: Could not start hal
,08-19 17:55:25.236  1619  1650 I Hs20UtilService: Message received 5011
,08-19 17:55:25.246  1015  1123 E WifiNative-wlan0: do suspend true
,08-19 17:55:25.246  6394  6394 D SecurityLogAgent: KnoxConfiguration : Current State = 1
,08-19 17:55:25.246  1015  1123 E WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:3
,08-19 17:55:25.246  1015  1122 D WifiP2pService: P2pDisabledState{ what=131203 }
,08-19 17:55:25.246  1015  1015 D WifiScanningService: SCAN_AVAILABLE : 3
,08-19 17:55:25.256  1015  1122 D WifiP2pService: P2pEnablingState
08-19 17:55:25.246  1015  1147 D WifiScanningService: DefaultState got{ when=0 what=160006 target=com.android.internal.util.StateMachine$SmHandler },
08-19 17:55:25.256  1015  1122 D WifiP2pService: P2pEnablingState{ what=147457 }
08-19 17:55:25.246  1015  1147 I WifiNative-HAL: startHal
08-19 17:55:25.256  1015  1122 D WifiP2pService: P2p socket connection successful
08-19 17:55:25.246  1015  1147 E wifi    : getStaticLongField sWifiHalHandle 0x9e7769bc
08-19 17:55:25.256  1015  1122 D WifiP2pService: P2pEnabledState
08-19 17:55:25.246  1015  1147 I WifiNative-HAL: Could not start hal
08-19 17:55:25.246  1015  1147 E WifiScanningService: could not start HAL
08-19 17:55:25.246  1015  1015 D RttService: SCAN_AVAILABLE : 3
08-19 17:55:25.246   281   971 D CommandListener: Setting iface cfg
08-19 17:55:25.246  1015  1148 D RttService: DefaultState got{ when=0 what=160512 target=com.android.internal.util.StateMachine$SmHandler }
08-19 17:55:25.246   281   971 D CommandListener: Trying to bring up p2p0
08-19 17:55:25.256  6394  6394 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
08-19 17:55:25.256  6394  6394 D SecurityLogAgent: StateMachine : Current State = 1
08-19 17:55:25.256  6394  6394 D SecurityLogAgent: StateMachine : Changed Current State = 1
08-19 17:55:25.256  1015  1122 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
08-19 17:55:25.256  1015  1123 E WifiStateMachine: DriverStatedState::CMD_SEC_STRING_API - inner msg [207]
08-19 17:55:25.256  1015  1122 D WifiP2pService: sending p2p connection changed broadcast: DISCONNECTED
08-19 17:55:25.256  1015  1123 D WifiNative-wlan0: callSECStringApiVoid - ID [215]
08-19 17:55:25.256  1015  1123 E WifiNative-wlan0: invaild command id : 215
08-19 17:55:25.256  6660  6660 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=PL,
08-19 17:55:25.256  6660  6660 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=PL,
,08-19 17:55:25.256  1015  1125 E ConnectivityService: updateNetworkInfo()
08-19 17:55:25.266  1015  1015 E WifiStateMachine: BroadcastReceiver : WIFI_P2P_STATE_CHANGED_ACTION is : android.net.wifi.p2p.STATE_CHANGED
,08-19 17:55:25.266  1015  1045 D WifiDisplayController: Received WIFI_P2P_STATE_CHANGED_ACTION: enabled=true
,08-19 17:55:25.266  1015  1045 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
08-19 17:55:25.266  1015  1045 D WifiDisplayController: disconnect
08-19 17:55:25.266  1015  1045 D WifiDisplayController: updateConnection
08-19 17:55:25.266  1015  1045 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
08-19 17:55:25.266  1015  1045 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,08-19 17:55:25.266  1015  1122 D WifiNative-p2p0: p2pGetDeviceAddress
08-19 17:55:25.266  6660  6660 E wpa_supplicant: wpa_driver_nl80211_driver_cmd: failed to issue private commands
08-19 17:55:25.266  1015  1045 D WifiDisplayController: Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-19 17:55:25.266  1015  1045 D WifiDisplayAdapter: onP2pDisconnected
08-19 17:55:25.266  1015  1123 E WifiStateMachine: Failed to set frequency band 0
08-19 17:55:25.266  1015  1045 D IpRemoteDisplayController: disconnectWfdBridgeServer
08-19 17:55:25.266  1015  1045 D IpRemoteDisplayController: WfdBridgeServer is already null
,08-19 17:55:25.266  1015  1122 D WifiNative-p2p0: p2pGetDeviceAddress returning 0a:ec:a9:50:76:28
08-19 17:55:25.266  1015  1123 E WifiStateMachine: DriverStatedState::CMD_SEC_STRING_API - inner msg [207]
08-19 17:55:25.266  1015  1123 D WifiNative-wlan0: callSECStringApiVoid - ID [215]
08-19 17:55:25.266  1015  1123 E WifiNative-wlan0: invaild command id : 215
,08-19 17:55:25.266  1015  1123 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
08-19 17:55:25.266  1172  1172 D AllShareCastTile: action: android.hardware.display.action.WIFI_DISPLAY_STATUS_CHANGED
08-19 17:55:25.266  1015  1123 D SecContentProvider2: mCursor = null
08-19 17:55:25.266  1015  1338 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
08-19 17:55:25.266  1172  1172 D AllShareCastTile: wifi display status changed! scanstate : 0, ActiveDisplayState : 0
,08-19 17:55:25.276  1015  1042 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
08-19 17:55:25.276  1015  1042 D Tethering: interfaceLinkStateChanged p2p0, false
08-19 17:55:25.276  1015  1042 D Tethering: interfaceStatusChanged p2p0, false
,08-19 17:55:25.276  1304  1304 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.p2p.CONNECTION_STATE_CHANGE
08-19 17:55:25.276  1304  1304 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
,08-19 17:55:25.276  1304  1304 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,08-19 17:55:25.276  1015  1122 D WifiP2pService: DeviceAddress: 0a:76:28
,08-19 17:55:25.276  1015  1123 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
08-19 17:55:25.276  1015  1045 D WifiDisplayController: Received WIFI_P2P_THIS_DEVICE_CHANGED_ACTION: mThisDevice= Device: Thali Test (Galaxy A3)
08-19 17:55:25.276  1015  1045 D WifiDisplayController:  deviceAddress: 0a:ec:a9:50:76:28
08-19 17:55:25.276  1015  1045 D WifiDisplayController:  primary type: 10-0050F204-5
08-19 17:55:25.276  1015  1045 D WifiDisplayController:  secondary type: null
08-19 17:55:25.276  1015  1045 D WifiDisplayController:  wps: 0
08-19 17:55:25.276  1015  1045 D WifiDisplayController:  grpcapab: 0
08-19 17:55:25.276  1015  1045 D WifiDisplayController:  devcapab: 0
08-19 17:55:25.276  1015  1045 D WifiDisplayController:  status: 3
08-19 17:55:25.276  1015  1045 D WifiDisplayController:  wfdInfo: null
,08-19 17:55:25.276  1015  1045 D WifiDisplayController:  groupownerAddress: null
08-19 17:55:25.276  1015  1045 D WifiDisplayController:  GOdeviceName: null
08-19 17:55:25.276  1015  1045 D WifiDisplayController:  interfaceAddress: 
08-19 17:55:25.276  1015  1045 D WifiDisplayController:  SConnectInfo : null
08-19 17:55:25.276  1015  1123 D SecContentProvider2: mCursor = null
,08-19 17:55:25.286  1304  1304 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
08-19 17:55:25.286  1304  1304 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
08-19 17:55:25.286  1304  1304 I NearbySettings: MountReceiver.onReceive - Set preference state off
08-19 17:55:25.286  1304  2187 V NearbySettings: MountReceiver.mPrefHandler - 7002
,08-19 17:55:25.286  6362  6362 D FileShare-Client: ClientBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,08-19 17:55:25.286  6362  6362 D FileShare-Client: ClientBroadcastReceiver.onReceive - disconnected
,08-19 17:55:25.286  6362  6362 D FileShare-Client: Outbound.stopDelayTimer - 
,08-19 17:55:25.296  6379  6379 D FileShare-Server: ServerBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,08-19 17:55:25.306  1015  1122 D WifiP2pService: sending p2p persistent groups changed broadcast
,08-19 17:55:25.306  1015  1122 D WifiP2pService: InactiveState
,08-19 17:55:25.306  1015  1122 D WifiP2pService: InactiveState{ what=143376 }
,08-19 17:55:25.306  1015  1122 D WifiP2pService: P2pEnabledState{ what=143376 }
,08-19 17:55:25.306  6660  6660 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=PL
,08-19 17:55:25.306  1015  1122 D WifiP2pService: InactiveState{ what=143376 }
,08-19 17:55:25.306  1015  1122 D WifiP2pService: P2pEnabledState{ what=143376 }
,08-19 17:55:25.736   323   323 I ServiceManager: Waiting for service AtCmdFwd...
,08-19 17:55:25.746   291   291 E SMD     : DCD OFF,
,08-19 17:55:25.936  6220  6275 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-19 17:55:25.936  6220  6275 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-19 17:55:25.936  6220  6275 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-19 17:55:25.936  6220  6275 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-19 17:55:25.936  6220  6275 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-19 17:55:25.936  6220  6275 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-19 17:55:25.936  6220  6275 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-19 17:55:25.936  6220  6275 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-19 17:55:25.936  6220  6275 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null,
,08-19 17:55:25.946  6220  6275 D io.jxcore.node.LifeCycleMonitor: onActivityCreated: Bundle[{}]
,08-19 17:55:25.946  6220  6275 D io.jxcore.node.LifeCycleMonitor: onActivityResumed
,08-19 17:55:25.946  6220  6275 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@15c30def Bundle[{}]
,08-19 17:55:25.946  6220  6275 I io.jxcore.node.LifeCycleMonitor: start: OK
,08-19 17:55:25.956  6220  6275 I io.jxcore.node.LifeCycleMonitor: stop: OK
,08-19 17:55:25.956  6220  6275 D io.jxcore.node.LifeCycleMonitor: onActivityStarted
,08-19 17:55:25.956  6220  6275 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
,08-19 17:55:25.956  6220  6275 D io.jxcore.node.LifeCycleMonitor: onActivityDestroyed
,08-19 17:55:25.956  6220  6275 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
,08-19 17:55:25.966  6220  6275 I System.out: Running OutgoingSocketThread
,08-19 17:55:25.966  6220  6668 D io.jxcore.node.OutgoingSocketThread: Entering thread (ID: 1219)
,08-19 17:55:25.966  6220  6668 D io.jxcore.node.OutgoingSocketThread: Server socket local port: 57072
,08-19 17:55:25.966  6220  6668 I io.jxcore.node.OutgoingSocketThread: Now accepting connections...
,08-19 17:55:26.446  6660  6660 I wpa_supplicant: nl80211: Received scan results (26 BSSes),
08-19 17:55:26.446  6660  6660 I wpa_supplicant: wlan0: Setting scan request: 8 sec 0 usec
,08-19 17:55:26.446  6660  6660 I wpa_supplicant: Trying to associate with SSID '4E47373030'
08-19 17:55:26.446  6660  6660 I wpa_supplicant: Trying to associate with  'G700'
08-19 17:55:26.446  6660  6660 I wpa_supplicant: wlan0: State: SCANNING -> ASSOCIATING
08-19 17:55:26.446  6660  6660 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=5 BSSID=00.00.00 SSID=4E47373030,
,08-19 17:55:26.456  1015  6666 D WifiMonitor: didn't find BSSID Trying to associate with SSID 'NG700'
,08-19 17:55:26.466  1015  1123 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
08-19 17:55:26.466  1015  1123 D SecContentProvider2: mCursor = null
,08-19 17:55:26.736   323   323 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 3
,08-19 17:55:26.966  6220  6275 I io.jxcore.node.OutgoingSocketThread: close (thread ID: 1220),
08-19 17:55:26.966  6220  6275 I io.jxcore.node.OutgoingSocketThread: close: Complete (thread ID: 1220)
,08-19 17:55:26.966  6220  6275 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 1225)
08-19 17:55:26.966  6220  6275 V io.jxcore.node.SocketThreadBase: close: Closing the localhost socket...
08-19 17:55:26.966  6220  6275 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 1226),
,08-19 17:55:26.976  6220  6275 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,08-19 17:55:26.976  6220  6275 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@15d879e1 added. We now have 2 listener(s)
,08-19 17:55:26.976  6220  6275 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "08:EC:A9:50:76:27"
,08-19 17:55:26.976  6220  6275 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,08-19 17:55:26.976  6220  6275 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,08-19 17:55:26.976  6220  6275 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-19 17:55:26.976  6220  6275 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2754a306 added. We now have 9 listener(s)
,08-19 17:55:26.986  6220  6275 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-19 17:55:26.986  6220  6275 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-19 17:55:26.986  6220  6275 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-19 17:55:26.986  6220  6275 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-19 17:55:26.986  6220  6275 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-19 17:55:26.986  6220  6275 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-19 17:55:26.986  6220  6275 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-19 17:55:26.986  6220  6275 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-19 17:55:26.986  6220  6275 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-19 17:55:26.986  6220  6275 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-19 17:55:26.986  6220  6275 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-19 17:55:26.996  6220  6275 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-19 17:55:26.996  6220  6275 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-19 17:55:26.996  6220  6220 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-19 17:55:26.996  6220  6275 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-19 17:55:26.996  6220  6275 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@15708ff4 added. We now have 3 listener(s)
,08-19 17:55:26.996  6220  6275 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "08:EC:A9:50:76:27"
,08-19 17:55:26.996  6220  6275 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-19 17:55:27.006  6220  6275 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-19 17:55:27.006  6220  6275 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-19 17:55:27.006  6220  6275 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3781d31d added. We now have 10 listener(s)
,08-19 17:55:27.006  6220  6275 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-19 17:55:27.006  6220  6275 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-19 17:55:27.006  6220  6275 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,08-19 17:55:27.006  6220  6275 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-19 17:55:27.006  6220  6275 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-19 17:55:27.006  6220  6275 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-19 17:55:27.006  6220  6275 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-19 17:55:27.006  6220  6275 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-19 17:55:27.006  6220  6275 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@15d879e1 removed from the list
,08-19 17:55:27.006  6220  6275 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-19 17:55:27.006  6220  6275 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2754a306 removed from the list
08-19 17:55:27.006  6220  6275 D io.jxcore.node.ConnectivityMonitor: stop
08-19 17:55:27.006  6220  6275 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-19 17:55:27.006  6220  6275 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-19 17:55:27.006  6220  6275 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-19 17:55:27.006  6220  6275 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising,
08-19 17:55:27.006  6220  6275 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-19 17:55:27.006  6220  6275 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-19 17:55:27.006  6220  6275 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2754a306 not in the list
08-19 17:55:27.006  6220  6275 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-19 17:55:27.006  6220  6275 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-19 17:55:27.006  6220  6275 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-19 17:55:27.006  6220  6275 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-19 17:55:27.006  6220  6275 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-19 17:55:27.006  6220  6275 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3781d31d removed from the list
08-19 17:55:27.006  6220  6275 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-19 17:55:27.006  6220  6275 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-19 17:55:27.006  6220  6275 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left,
08-19 17:55:27.006  6220  6275 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-19 17:55:27.006  6220  6275 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@15708ff4 removed from the list
08-19 17:55:27.006  6220  6275 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,08-19 17:55:27.006  6220  6275 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1607e992 added. We now have 2 listener(s)
,08-19 17:55:27.006  6220  6275 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "08:EC:A9:50:76:27"
08-19 17:55:27.006  6220  6275 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-19 17:55:27.006  6220  6275 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,08-19 17:55:27.006  6220  6275 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-19 17:55:27.006  6220  6275 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3751f63 added. We now have 9 listener(s)
08-19 17:55:27.006  6220  6275 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-19 17:55:27.006  6220  6275 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-19 17:55:27.016  6220  6275 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener,
,08-19 17:55:27.016  6220  6275 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-19 17:55:27.016  6220  6275 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-19 17:55:27.016  6220  6275 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-19 17:55:27.016  6220  6275 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-19 17:55:27.016  6220  6275 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-19 17:55:27.016  6220  6275 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-19 17:55:27.016  6220  6275 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-19 17:55:27.016  6220  6275 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-19 17:55:27.016  6220  6275 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-19 17:55:27.016  6220  6275 D io.jxcore.node.ConnectivityMonitor: start: OK
08-19 17:55:27.016  6220  6275 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-19 17:55:27.016  6220  6275 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@166d8419 added. We now have 3 listener(s)
,08-19 17:55:27.026  6220  6220 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-19 17:55:27.026  6220  6275 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "08:EC:A9:50:76:27"
,08-19 17:55:27.026  6220  6275 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-19 17:55:27.026  6220  6275 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-19 17:55:27.026  6220  6275 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-19 17:55:27.026  6220  6275 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2f370cde added. We now have 10 listener(s),
,08-19 17:55:27.026  6220  6275 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-19 17:55:27.026  6220  6275 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-19 17:55:27.026  6220  6275 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only,
08-19 17:55:27.026  6220  6275 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-19 17:55:27.026  6220  6275 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-19 17:55:27.026  6220  6275 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,08-19 17:55:27.026  6220  6275 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,08-19 17:55:27.036  6220  6275 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-19 17:55:27.036  6220  6275 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0,
,08-19 17:55:27.036  6220  6275 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,08-19 17:55:27.036  6220  6275 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
08-19 17:55:27.036  6220  6275 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,08-19 17:55:27.036  6565  6634 D BtGatt.GattService: registerClient() - UUID=31c87bab-bb3b-4798-bfe9-08011fcf7f25
,08-19 17:55:27.086  6565  6590 D BtGatt.GattService: onClientRegistered() - UUID=31c87bab-bb3b-4798-bfe9-08011fcf7f25, clientIf=6
,08-19 17:55:27.086  6220  6233 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=6
,08-19 17:55:27.086  6565  6591 D BtGatt.GattService: start scan with filters
,08-19 17:55:27.086  6565  6595 D BtGatt.ScanManager: handling starting scan
,08-19 17:55:27.086  6220  6275 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,08-19 17:55:27.086  6220  6275 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
08-19 17:55:27.086  6220  6275 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
08-19 17:55:27.086  6220  6275 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
08-19 17:55:27.086  6565  6595 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@8bc66ff
,08-19 17:55:27.096  6220  6275 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false,
08-19 17:55:27.096  6565  6590 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=6, status=0, action=1
08-19 17:55:27.096  6565  6590 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0,
08-19 17:55:27.096  6565  6595 D BtGatt.ScanManager: allow scan with filters
,08-19 17:55:27.096  6565  6595 D BtGatt.ScanManager: client filter size is = 1available filters are = 13,
08-19 17:55:27.096  6565  6595 D BtGatt.ScanManager: set filter index= 3 for clientIf= 6
08-19 17:55:27.096  6220  6275 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
08-19 17:55:27.096  6220  6220 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
08-19 17:55:27.096  6565  6590 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=0, availableSpace=15
08-19 17:55:27.096  6565  6590 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-19 17:55:27.096  6565  6595 D BtGatt.ScanManager: Starting BLE batch scan
08-19 17:55:27.096  6565  6595 D BtGatt.ScanManager: configuring batch scan storage, appIf 6
,08-19 17:55:27.106  6220  6275 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-19 17:55:27.106  6565  6590 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=6, status=0
,08-19 17:55:27.106  6565  6590 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-19 17:55:27.106  6565  6590 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=1
,08-19 17:55:27.106  6565  6590 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-19 17:55:27.116  6220  6275 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
08-19 17:55:27.116  6220  6275 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
08-19 17:55:27.116  6220  6275 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
08-19 17:55:27.116  6220  6275 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-19 17:55:27.116  6220  6275 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-19 17:55:27.116  6220  6275 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-19 17:55:27.116  6220  6275 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-19 17:55:27.116  6220  6275 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-19 17:55:27.116  6220  6275 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-19 17:55:27.116  6220  6275 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-19 17:55:27.116  6220  6275 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,08-19 17:55:27.116  6565  6634 D BtGatt.GattService: stopScan() - queue size =1
,08-19 17:55:27.116  6565  6579 D BtGatt.GattService: unregisterClient() - clientIf=6
,08-19 17:55:27.126  6220  6275 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-19 17:55:27.126  6220  6275 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
08-19 17:55:27.126  6220  6275 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
08-19 17:55:27.126  6220  6275 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
08-19 17:55:27.126  6220  6275 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,08-19 17:55:27.126  6565  6595 D BtGatt.ScanManager: filter size is 1
08-19 17:55:27.126  6565  6595 D BtGatt.ScanManager: delete FilterIndex - 3
,08-19 17:55:27.126  6565  6590 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=1, availableSpace=16
,08-19 17:55:27.126  6565  6590 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-19 17:55:27.126  6565  6595 D BtGatt.ScanManager: stopping BLe Batch
,08-19 17:55:27.126  6220  6275 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,08-19 17:55:27.126  6220  6275 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,08-19 17:55:27.126  6220  6275 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
,08-19 17:55:27.126  6220  6275 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,08-19 17:55:27.136  6565  6590 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=0
08-19 17:55:27.136  6565  6590 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-19 17:55:27.136  6565  6595 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
,08-19 17:55:27.136  6220  6275 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-19 17:55:27.136  6565  6590 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=0
,08-19 17:55:27.136  6565  6590 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-19 17:55:27.136  6220  6220 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,08-19 17:55:27.136  6220  6220 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,08-19 17:55:27.136  6220  6220 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,08-19 17:55:27.146  6220  6275 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-19 17:55:27.146  6220  6275 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,08-19 17:55:27.146  6220  6275 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-19 17:55:27.146  6220  6275 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-19 17:55:27.146  6220  6275 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-19 17:55:27.146  6220  6275 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-19 17:55:27.146  6220  6275 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,08-19 17:55:27.146  6220  6275 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1607e992 removed from the list
08-19 17:55:27.146  6220  6275 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-19 17:55:27.146  6220  6275 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3751f63 removed from the list
08-19 17:55:27.146  6220  6275 D io.jxcore.node.ConnectivityMonitor: stop
,08-19 17:55:27.146  6220  6275 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-19 17:55:27.146  6220  6275 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-19 17:55:27.146  6220  6275 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-19 17:55:27.146  6220  6275 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-19 17:55:27.146  6220  6275 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-19 17:55:27.156  6220  6275 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-19 17:55:27.156  6220  6275 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3751f63 not in the list
,08-19 17:55:27.156  6220  6275 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-19 17:55:27.156  6220  6275 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-19 17:55:27.156  6220  6275 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-19 17:55:27.156  6220  6275 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-19 17:55:27.156  6220  6275 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-19 17:55:27.156  6220  6275 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2f370cde removed from the list
08-19 17:55:27.156  6220  6275 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-19 17:55:27.156  6220  6275 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-19 17:55:27.156  6220  6275 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-19 17:55:27.156  6220  6275 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,08-19 17:55:27.156  6220  6275 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@166d8419 removed from the list
,08-19 17:55:27.156  6220  6275 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,08-19 17:55:27.156  6220  6275 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@39a318ea added. We now have 2 listener(s)
,08-19 17:55:27.166  6220  6275 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "08:EC:A9:50:76:27"
,08-19 17:55:27.166  6220  6275 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,08-19 17:55:27.166  6220  6275 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-19 17:55:27.166  6220  6275 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-19 17:55:27.166  6220  6275 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2b0517db added. We now have 9 listener(s)
08-19 17:55:27.166  6220  6275 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-19 17:55:27.166  6220  6275 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-19 17:55:27.166  6220  6275 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-19 17:55:27.176  6220  6275 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-19 17:55:27.176  6220  6275 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-19 17:55:27.176  6220  6275 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-19 17:55:27.176  6220  6275 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-19 17:55:27.176  6220  6275 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-19 17:55:27.176  6220  6275 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-19 17:55:27.176  6220  6275 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-19 17:55:27.176  6220  6275 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-19 17:55:27.176  6220  6275 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-19 17:55:27.176  6220  6275 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-19 17:55:27.176  6220  6275 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-19 17:55:27.176  6220  6275 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@17e29d51 added. We now have 3 listener(s)
,08-19 17:55:27.176  6220  6220 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-19 17:55:27.176  6220  6275 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "08:EC:A9:50:76:27"
,08-19 17:55:27.176  6220  6275 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,08-19 17:55:27.186  6220  6275 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-19 17:55:27.186  6220  6275 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-19 17:55:27.186  6220  6275 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3511d9b6 added. We now have 10 listener(s)
,08-19 17:55:27.186  6220  6275 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-19 17:55:27.186  6220  6275 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-19 17:55:27.186  6220  6275 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-19 17:55:27.186  6220  6275 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-19 17:55:27.186  6220  6275 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-19 17:55:27.186  6220  6275 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-19 17:55:27.186  6220  6275 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener,
,08-19 17:55:27.186  6220  6275 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,08-19 17:55:27.186  6220  6275 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
08-19 17:55:27.186  6220  6275 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-19 17:55:27.196  6220  6275 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,08-19 17:55:27.196  6220  6275 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
08-19 17:55:27.196  6220  6275 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,08-19 17:55:27.196  6565  6591 D BtGatt.GattService: registerClient() - UUID=4b66a788-0265-4c5b-a601-e3201f78a68a
,08-19 17:55:27.236  6565  6590 D BtGatt.GattService: onClientRegistered() - UUID=4b66a788-0265-4c5b-a601-e3201f78a68a, clientIf=6
,08-19 17:55:27.236  6220  6233 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=6,
08-19 17:55:27.236  6565  6579 D BtGatt.GattService: start scan with filters
08-19 17:55:27.236  6565  6595 D BtGatt.ScanManager: handling starting scan,
08-19 17:55:27.236  6220  6275 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
08-19 17:55:27.236  6220  6275 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
08-19 17:55:27.236  6220  6275 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
,08-19 17:55:27.236  6220  6275 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
08-19 17:55:27.236  6565  6590 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=6, status=0, action=1
08-19 17:55:27.236  6565  6590 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-19 17:55:27.236  6565  6595 D BtGatt.ScanManager: allow scan with filters
08-19 17:55:27.236  6565  6595 D BtGatt.ScanManager: client filter size is = 1available filters are = 13
,08-19 17:55:27.236  6565  6595 D BtGatt.ScanManager: set filter index= 4 for clientIf= 6
,08-19 17:55:27.246  6565  6590 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=0, availableSpace=15
08-19 17:55:27.246  6565  6590 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-19 17:55:27.246  6565  6595 D BtGatt.ScanManager: Starting BLE batch scan
,08-19 17:55:27.246  6565  6595 D BtGatt.ScanManager: configuring batch scan storage, appIf 6
08-19 17:55:27.246  6565  6590 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=6, status=0
08-19 17:55:27.246  6565  6590 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-19 17:55:27.246  6220  6275 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
08-19 17:55:27.246  6220  6275 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,08-19 17:55:27.246  6220  6220 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-19 17:55:27.246  6565  6590 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=1,
08-19 17:55:27.246  6565  6590 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-19 17:55:27.246  6220  6275 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-19 17:55:27.256  6220  6275 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
,08-19 17:55:27.256  6220  6275 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,08-19 17:55:27.256  6220  6275 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-19 17:55:27.256  6220  6275 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-19 17:55:27.256  6220  6275 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-19 17:55:27.256  6220  6275 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-19 17:55:27.256  6220  6275 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-19 17:55:27.256  6220  6275 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-19 17:55:27.256  6220  6275 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,08-19 17:55:27.256  6220  6275 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@39a318ea removed from the list
08-19 17:55:27.266  6220  6275 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-19 17:55:27.266  6220  6275 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2b0517db removed from the list
08-19 17:55:27.266  6220  6275 D io.jxcore.node.ConnectivityMonitor: stop
,08-19 17:55:27.266  6220  6275 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-19 17:55:27.266  6220  6275 W org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: The given listener does not exist in the list - probably already removed
,08-19 17:55:27.266  6220  6275 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 1 listener(s) left
08-19 17:55:27.266  6220  6275 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-19 17:55:27.266  6220  6275 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-19 17:55:27.266  6220  6275 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising,
08-19 17:55:27.266  6220  6275 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-19 17:55:27.266  6220  6275 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-19 17:55:27.266  6220  6275 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2b0517db not in the list
08-19 17:55:27.266  6220  6275 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-19 17:55:27.266  6220  6275 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
,08-19 17:55:27.266  6220  6275 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-19 17:55:27.266  6220  6275 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-19 17:55:27.266  6220  6275 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,08-19 17:55:27.266  6565  6579 D BtGatt.GattService: stopScan() - queue size =1
,08-19 17:55:27.266  6565  6595 D BtGatt.ScanManager: filter size is 1
08-19 17:55:27.266  6565  6595 D BtGatt.ScanManager: delete FilterIndex - 4
,08-19 17:55:27.266  6565  6573 D BtGatt.GattService: unregisterClient() - clientIf=6
,08-19 17:55:27.266  6220  6275 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-19 17:55:27.266  6220  6275 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
08-19 17:55:27.266  6220  6275 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
08-19 17:55:27.266  6220  6275 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
08-19 17:55:27.266  6220  6275 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,08-19 17:55:27.266  6565  6590 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=1, availableSpace=16
,08-19 17:55:27.276  6565  6590 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-19 17:55:27.276  6220  6275 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,08-19 17:55:27.276  6565  6595 D BtGatt.ScanManager: stopping BLe Batch
,08-19 17:55:27.276  6220  6275 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
08-19 17:55:27.276  6220  6275 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-19 17:55:27.276  6220  6275 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,08-19 17:55:27.276  6220  6275 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-19 17:55:27.276  6220  6220 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,08-19 17:55:27.276  6220  6220 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false,
08-19 17:55:27.276  6220  6220 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false,
08-19 17:55:27.276  6220  6275 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-19 17:55:27.276  6220  6275 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-19 17:55:27.276  6220  6275 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose,
08-19 17:55:27.276  6220  6275 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3511d9b6 removed from the list
08-19 17:55:27.276  6220  6275 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-19 17:55:27.276  6220  6275 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-19 17:55:27.276  6220  6275 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-19 17:55:27.276  6565  6590 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=0
08-19 17:55:27.276  6220  6275 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,08-19 17:55:27.276  6565  6590 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-19 17:55:27.276  6220  6275 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@17e29d51 removed from the list
08-19 17:55:27.276  6565  6595 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
08-19 17:55:27.276  6565  6590 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=0
08-19 17:55:27.276  6565  6590 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-19 17:55:27.276  6220  6275 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded,
08-19 17:55:27.276  6220  6275 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@5d9db42 added. We now have 2 listener(s)
,08-19 17:55:27.286  6220  6275 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "08:EC:A9:50:76:27"
,08-19 17:55:27.286  6220  6275 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,08-19 17:55:27.286  6220  6275 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-19 17:55:27.286  6220  6275 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-19 17:55:27.286  6220  6275 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@359ca753 added. We now have 9 listener(s)
08-19 17:55:27.286  6220  6275 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1,
08-19 17:55:27.286  6220  6275 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-19 17:55:27.286  6220  6275 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-19 17:55:27.286  6220  6275 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-19 17:55:27.286  6220  6275 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-19 17:55:27.286  6220  6275 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-19 17:55:27.286  6220  6275 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-19 17:55:27.286  6220  6275 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-19 17:55:27.286  6220  6275 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-19 17:55:27.286  6220  6275 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-19 17:55:27.286  6220  6275 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-19 17:55:27.296  6220  6275 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-19 17:55:27.296  6220  6275 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-19 17:55:27.296  6220  6275 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-19 17:55:27.296  6220  6275 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@164aa589 added. We now have 3 listener(s)
,08-19 17:55:27.296  6220  6220 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-19 17:55:27.296  6220  6275 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "08:EC:A9:50:76:27"
,08-19 17:55:27.296  6220  6275 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,08-19 17:55:27.296  6220  6275 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-19 17:55:27.296  6220  6275 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-19 17:55:27.296  6220  6275 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d2e698e added. We now have 10 listener(s)
08-19 17:55:27.296  6220  6275 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-19 17:55:27.296  6220  6275 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-19 17:55:27.296  6220  6275 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
,08-19 17:55:27.306  6220  6275 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
,08-19 17:55:27.306  6220  6275 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-19 17:55:27.306  6220  6275 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,08-19 17:55:27.306  6220  6275 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,08-19 17:55:27.306  6220  6275 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-19 17:55:27.306  6220  6275 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-19 17:55:27.316  6220  6275 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
08-19 17:55:27.316  6220  6275 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
08-19 17:55:27.316  6220  6275 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,08-19 17:55:27.316  6565  6579 D BtGatt.GattService: registerClient() - UUID=6274689c-be64-4ad7-adae-ff8157cf0aae
,08-19 17:55:27.356  6565  6590 D BtGatt.GattService: onClientRegistered() - UUID=6274689c-be64-4ad7-adae-ff8157cf0aae, clientIf=6
,08-19 17:55:27.356  6220  6233 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=6
,08-19 17:55:27.356  6565  6573 D BtGatt.GattService: start scan with filters
,08-19 17:55:27.356  6565  6595 D BtGatt.ScanManager: handling starting scan
08-19 17:55:27.356  6220  6275 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
08-19 17:55:27.366  6220  6275 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
08-19 17:55:27.366  6220  6275 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
08-19 17:55:27.366  6220  6275 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
08-19 17:55:27.366  6565  6590 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=6, status=0, action=1
08-19 17:55:27.366  6565  6590 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-19 17:55:27.366  6565  6595 D BtGatt.ScanManager: allow scan with filters
08-19 17:55:27.366  6565  6595 D BtGatt.ScanManager: client filter size is = 1available filters are = 13
08-19 17:55:27.366  6565  6595 D BtGatt.ScanManager: set filter index= 5 for clientIf= 6
08-19 17:55:27.366  6565  6590 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=0, availableSpace=15
08-19 17:55:27.366  6565  6590 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-19 17:55:27.366  6565  6595 D BtGatt.ScanManager: Starting BLE batch scan
08-19 17:55:27.366  6565  6595 D BtGatt.ScanManager: configuring batch scan storage, appIf 6
08-19 17:55:27.366  6565  6590 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=6, status=0
08-19 17:55:27.366  6565  6590 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-19 17:55:27.366  6220  6275 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
08-19 17:55:27.366  6220  6275 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
08-19 17:55:27.366  6220  6220 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
08-19 17:55:27.366  6565  6590 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=1
08-19 17:55:27.366  6565  6590 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-19 17:55:27.366  6220  6275 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
08-19 17:55:27.376  6220  6275 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-19 17:55:27.376  6220  6275 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-19 17:55:27.376  6220  6275 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-19 17:55:27.376  6220  6275 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-19 17:55:27.376  6220  6275 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-19 17:55:27.376  6220  6275 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-19 17:55:27.376  6220  6275 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-19 17:55:27.376  6220  6275 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@5d9db42 removed from the list
08-19 17:55:27.376  6220  6275 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-19 17:55:27.376  6220  6275 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@359ca753 removed from the list
08-19 17:55:27.376  6220  6275 D io.jxcore.node.ConnectivityMonitor: stop
08-19 17:55:27.376  6220  6275 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-19 17:55:27.376  6220  6275 W org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: The given listener does not exist in the list - probably already removed
08-19 17:55:27.376  6220  6275 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 1 listener(s) left
08-19 17:55:27.376  6220  6275 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-19 17:55:27.376  6220  6275 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-19 17:55:27.386  6220  6275 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-19 17:55:27.386  6220  6275 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-19 17:55:27.386  6220  6275 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-19 17:55:27.386  6220  6275 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@359ca753 not in the list
08-19 17:55:27.386  6220  6275 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-19 17:55:27.386  6220  6275 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-19 17:55:27.386  6220  6275 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-19 17:55:27.386  6220  6275 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-19 17:55:27.386  6220  6275 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
08-19 17:55:27.386  6565  6579 D BtGatt.GattService: stopScan() - queue size =1
08-19 17:55:27.386  6565  6595 D BtGatt.ScanManager: filter size is 1
08-19 17:55:27.386  6565  6595 D BtGatt.ScanManager: delete FilterIndex - 5
08-19 17:55:27.386  6565  6573 D BtGatt.GattService: unregisterClient() - clientIf=6
08-19 17:55:27.386  6565  6590 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=1, availableSpace=16
08-19 17:55:27.386  6565  6590 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-19 17:55:27.386  6565  6595 D BtGatt.ScanManager: stopping BLe Batch
08-19 17:55:27.386  6220  6275 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-19 17:55:27.396  6220  6275 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
08-19 17:55:27.396  6220  6275 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
08-19 17:55:27.396  6220  6275 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
08-19 17:55:27.396  6220  6275 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
08-19 17:55:27.396  6220  6275 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-19 17:55:27.396  6565  6590 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=0
08-19 17:55:27.396  6565  6590 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-19 17:55:27.396  6565  6595 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
08-19 17:55:27.396  6565  6590 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=0
08-19 17:55:27.396  6565  6590 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-19 17:55:27.396  6220  6275 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
08-19 17:55:27.396  6220  6275 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-19 17:55:27.396  6220  6275 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-19 17:55:27.396  6220  6275 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-19 17:55:27.396  6220  6275 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-19 17:55:27.396  6220  6275 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-19 17:55:27.396  6220  6275 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-19 17:55:27.396  6220  6275 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d2e698e removed from the list
08-19 17:55:27.396  6220  6275 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-19 17:55:27.396  6220  6275 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-19 17:55:27.396  6220  6275 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-19 17:55:27.396  6220  6275 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-19 17:55:27.396  6220  6275 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@164aa589 removed from the list
08-19 17:55:27.396  6220  6220 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-19 17:55:27.396  6220  6220 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-19 17:55:27.396  6220  6220 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-19 17:55:27.396  6220  6275 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-19 17:55:27.396  6220  6275 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3a2b909a added. We now have 2 listener(s)
08-19 17:55:27.406  6220  6275 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "08:EC:A9:50:76:27"
08-19 17:55:27.406  6220  6275 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-19 17:55:27.406  6220  6275 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-19 17:55:27.406  6220  6275 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-19 17:55:27.406  6220  6275 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3bb7adcb added. We now have 9 listener(s)
08-19 17:55:27.406  6220  6275 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-19 17:55:27.406  6220  6275 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-19 17:55:27.406  6220  6275 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-19 17:55:27.406  6220  6275 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-19 17:55:27.406  6220  6275 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-19 17:55:27.406  6220  6275 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-19 17:55:27.406  6220  6275 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-19 17:55:27.406  6220  6275 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-19 17:55:27.406  6220  6275 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-19 17:55:27.406  6220  6275 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-19 17:55:27.406  6220  6275 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-19 17:55:27.406  6220  6275 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-19 17:55:27.406  6220  6275 D io.jxcore.node.ConnectivityMonitor: start: OK
08-19 17:55:27.406  6220  6275 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-19 17:55:27.406  6220  6275 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@21347cc1 added. We now have 3 listener(s)
08-19 17:55:27.416  6220  6220 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-19 17:55:27.416  6220  6275 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "08:EC:A9:50:76:27"
08-19 17:55:27.416  6220  6275 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-19 17:55:27.416  6220  6275 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-19 17:55:27.416  6220  6275 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-19 17:55:27.416  6220  6275 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1fa21c66 added. We now have 10 listener(s)
08-19 17:55:27.416  6220  6275 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-19 17:55:27.416  6220  6275 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-19 17:55:27.416  6220  6275 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-19 17:55:27.416  6220  6275 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-19 17:55:27.416  6220  6275 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-19 17:55:27.416  6220  6275 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-19 17:55:27.416  6220  6275 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-19 17:55:27.416  6220  6275 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-19 17:55:27.416  6220  6275 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3a2b909a removed from the list
08-19 17:55:27.416  6220  6275 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-19 17:55:27.416  6220  6275 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3bb7adcb removed from the list
08-19 17:55:27.416  6220  6275 D io.jxcore.node.ConnectivityMonitor: stop
08-19 17:55:27.416  6220  6275 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-19 17:55:27.416  6220  6275 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-19 17:55:27.416  6220  6275 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-19 17:55:27.416  6220  6275 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-19 17:55:27.416  6220  6275 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-19 17:55:27.416  6220  6275 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-19 17:55:27.416  6220  6275 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3bb7adcb not in the list
08-19 17:55:27.416  6220  6275 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-19 17:55:27.416  6220  6275 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-19 17:55:27.416  6220  6275 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-19 17:55:27.416  6220  6275 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-19 17:55:27.416  6220  6275 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-19 17:55:27.416  6220  6275 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1fa21c66 removed from the list
08-19 17:55:27.416  6220  6275 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-19 17:55:27.416  6220  6275 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-19 17:55:27.416  6220  6275 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-19 17:55:27.416  6220  6275 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-19 17:55:27.416  6220  6275 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@21347cc1 removed from the list
08-19 17:55:27.426  6220  6275 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: true, is advertising: true - Start operation: Should start/stop everything
08-19 17:55:27.426  6220  6275 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
08-19 17:55:27.426  6220  6275 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
08-19 17:55:27.426  6220  6275 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-19 17:55:27.426  6220  6275 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should affect listening to advertisements only
08-19 17:55:27.426  6220  6275 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
,08-19 17:55:27.426  6220  6672 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 1233, name: My test thread name)
08-19 17:55:27.426  6220  6672 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 1233, thread name: My test thread name)
08-19 17:55:27.426  6220  6672 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 1233, name: My test thread name), during the lifetime of the thread the total number of bytes read was 122 and the total number of bytes written 122
,08-19 17:55:27.426  6220  6673 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 1235, name: My test thread name),
08-19 17:55:27.426  6220  6673 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 1235, thread name: My test thread name)
08-19 17:55:27.426  6220  6673 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 1235, name: My test thread name), during the lifetime of the thread the total number of bytes read was 122 and the total number of bytes written 122
,08-19 17:55:27.426  6220  6275 D com.test.thalitest.ThaliTestRunner: Total number of executed tests: 80
08-19 17:55:27.426  6220  6275 D com.test.thalitest.ThaliTestRunner: Number of passed tests: 80
,08-19 17:55:27.426  6220  6275 D com.test.thalitest.ThaliTestRunner: Number of failed tests:  0
08-19 17:55:27.426  6220  6275 D com.test.thalitest.ThaliTestRunner: Number of ignored tests: 0
08-19 17:55:27.426  6220  6275 D com.test.thalitest.ThaliTestRunner: Total duration: 23258 ms
,08-19 17:55:27.436  6220  6275 I jxcore-log: Total number of executed tests:  80
08-19 17:55:27.436  6220  6275 I jxcore-log: 
08-19 17:55:27.436  6220  6275 I jxcore-log: Number of passed tests:  80
08-19 17:55:27.436  6220  6275 I jxcore-log: 
,08-19 17:55:27.436  6220  6275 I jxcore-log: Number of failed tests:  0
08-19 17:55:27.436  6220  6275 I jxcore-log: 
08-19 17:55:27.436  6220  6275 I jxcore-log: Number of ignored tests:  0
08-19 17:55:27.436  6220  6275 I jxcore-log: 
08-19 17:55:27.436  6220  6275 I jxcore-log: Total duration:  23258
08-19 17:55:27.436  6220  6275 I jxcore-log: 
,08-19 17:55:27.436  6220  6275 I jxcore-log: ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
08-19 17:55:27.436  6220  6275 I jxcore-log: 
,08-19 17:55:27.436  6220  6275 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-19 17:55:27.436  6220  6275 I jxcore-log: 
08-19 17:55:27.446  6220  6220 I chromium: [INFO:CONSOLE(68)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (68)
08-19 17:55:27.446  6220  6275 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-19 17:55:27.446  6220  6275 I jxcore-log: 
08-19 17:55:27.446  6220  6275 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-19 17:55:27.446  6220  6275 I jxcore-log: 
08-19 17:55:27.446  6220  6275 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-19 17:55:27.446  6220  6275 I jxcore-log: 
08-19 17:55:27.446  6220  6275 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-19 17:55:27.446  6220  6275 I jxcore-log: 
08-19 17:55:27.446  6220  6275 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-19 17:55:27.446  6220  6275 I jxcore-log: 
08-19 17:55:27.446  6220  6275 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-19 17:55:27.446  6220  6275 I jxcore-log: 
08-19 17:55:27.456  6220  6275 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-19 17:55:27.456  6220  6275 I jxcore-log: 
08-19 17:55:27.456  6220  6275 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-19 17:55:27.456  6220  6275 I jxcore-log: 
08-19 17:55:27.456  6220  6275 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false},
08-19 17:55:27.456  6220  6275 I jxcore-log: 
08-19 17:55:27.456  6220  6275 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-19 17:55:27.456  6220  6275 I jxcore-log: 
08-19 17:55:27.456  6220  6275 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-19 17:55:27.456  6220  6275 I jxcore-log: 
08-19 17:55:27.456  6220  6275 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-19 17:55:27.456  6220  6275 I jxcore-log: 
08-19 17:55:27.456  6220  6275 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-19 17:55:27.456  6220  6275 I jxcore-log: 
08-19 17:55:27.456  6220  6275 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-19 17:55:27.456  6220  6275 I jxcore-log: 
,08-19 17:55:27.456  6220  6275 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-19 17:55:27.456  6220  6275 I jxcore-log: 
,08-19 17:55:27.456  6220  6275 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-19 17:55:27.456  6220  6275 I jxcore-log: 
08-19 17:55:27.456  6220  6275 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-19 17:55:27.456  6220  6275 I jxcore-log: 
,08-19 17:55:27.466  6220  6275 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-19 17:55:27.466  6220  6275 I jxcore-log: 
,08-19 17:55:27.466  6220  6275 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-19 17:55:27.466  6220  6275 I jxcore-log: 
08-19 17:55:27.466  6220  6275 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-19 17:55:27.466  6220  6275 I jxcore-log: 
08-19 17:55:27.466  6220  6275 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-19 17:55:27.466  6220  6275 I jxcore-log: 
08-19 17:55:27.466  6220  6275 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-19 17:55:27.466  6220  6275 I jxcore-log: 
,08-19 17:55:27.466  6220  6275 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-19 17:55:27.466  6220  6275 I jxcore-log: 
08-19 17:55:27.466  6220  6275 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-19 17:55:27.466  6220  6275 I jxcore-log: 
,08-19 17:55:27.466  6220  6275 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-19 17:55:27.466  6220  6275 I jxcore-log: 
08-19 17:55:27.466  6220  6275 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-19 17:55:27.466  6220  6275 I jxcore-log: 
,08-19 17:55:27.546  1015  1042 D Tethering: interfaceLinkStateChanged wlan0, false
08-19 17:55:27.546  1015  1042 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
08-19 17:55:27.546  1015  1042 D Tethering: interfaceStatusChanged wlan0, false
,08-19 17:55:27.556  6660  6660 I wpa_supplicant: CTRL-EVENT-ASSOC-REJECT bssid=F4.99.3E status_code=1
08-19 17:55:27.556  6660  6660 I wpa_supplicant: wlan0: Setting scan request: 0 sec 100000 usec
08-19 17:55:27.556  6660  6660 I wpa_supplicant: wlan0: State: ASSOCIATING -> DISCONNECTED
08-19 17:55:27.556  6660  6660 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=00.00.00 SSID=4E47373030
,08-19 17:55:27.566  1015  1123 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
,08-19 17:55:27.566  1015  1123 D SecContentProvider2: mCursor = null
,08-19 17:55:27.636  6220  6220 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false,
08-19 17:55:27.636  6220  6275 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-19 17:55:27.636  6220  6275 I jxcore-log: 
,08-19 17:55:27.656  6660  6660 I wpa_supplicant: P2P: Current p2p state = IDLE
08-19 17:55:27.656  6660  6660 I wpa_supplicant: wlan0: State: DISCONNECTED -> SCANNING
08-19 17:55:27.656  6660  6660 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00.00.00 SSID=
08-19 17:55:27.656  6660  6660 I wpa_supplicant: Scan requested (ret=0) - scan timeout 30 seconds
,08-19 17:55:27.666  6660  6660 I wpa_supplicant: nl80211: Received scan results (26 BSSes)
08-19 17:55:27.666  1015  1123 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
08-19 17:55:27.666  1015  1123 D SecContentProvider2: mCursor = null
08-19 17:55:27.666  6660  6660 I wpa_supplicant: wlan0: Setting scan request: 8 sec 0 usec
08-19 17:55:27.666  6660  6660 I wpa_supplicant: Trying to associate with SSID '4E47373030'
08-19 17:55:27.666  6660  6660 I wpa_supplicant: Trying to associate with  'G700'
08-19 17:55:27.666  6660  6660 I wpa_supplicant: wlan0: State: SCANNING -> ASSOCIATING
08-19 17:55:27.666  6660  6660 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=5 BSSID=00.00.00 SSID=4E47373030
08-19 17:55:27.666  1015  6666 D WifiMonitor: didn't find BSSID Trying to associate with SSID 'NG700'
,08-19 17:55:27.676  1015  1123 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
08-19 17:55:27.676  1015  1123 D SecContentProvider2: mCursor = null
,08-19 17:55:27.706  6674  6674 D AndroidRuntime: ,
08-19 17:55:27.706  6674  6674 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
,08-19 17:55:27.706  6674  6674 D AndroidRuntime: CheckJNI is OFF,
08-19 17:55:27.706  6674  6674 D AndroidRuntime: readGMSProperty: start
,08-19 17:55:27.706  6674  6674 D AndroidRuntime: readGMSProperty: already setted!!
08-19 17:55:27.706  6674  6674 D AndroidRuntime: propertySet: couldn't set property (it is from app)
08-19 17:55:27.706  6674  6674 D AndroidRuntime: readGMSProperty: could not set the property(default)!!
08-19 17:55:27.706  6674  6674 D AndroidRuntime: readGMSProperty: end
08-19 17:55:27.706  6674  6674 D AndroidRuntime: addProductProperty: start
,08-19 17:55:27.776  6220  6220 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false,
08-19 17:55:27.776  6220  6275 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-19 17:55:27.776  6220  6275 I jxcore-log: 
,08-19 17:55:27.836  6674  6674 E AffinityControl: AffinityControl: registerfunction enter
,08-19 17:55:27.866  6674  6674 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm,
,08-19 17:55:27.876  1015  1027 D PersonaManagerService: isFromApprovedUnInstaller: uid, userId, appid : 2000 0 2000,
08-19 17:55:27.876  1015  1027 D PackageManager: START PACKAGE DELETE: observer{931359026}
08-19 17:55:27.876  1015  1027 D PackageManager: pkg{<packageName>}
08-19 17:55:27.876  1015  1027 D PackageManager: user{0}
08-19 17:55:27.876  1015  1027 D PackageManager: caller{2000}
08-19 17:55:27.876  1015  1027 D PackageManager: flags{2}
08-19 17:55:27.876  1015  1027 D PersonaManagerService: isFromApprovedUnInstaller: isApproved : true,
08-19 17:55:27.876  1015  1055 D PackageManager: [MSG] DELETE_PACKAGE_AS_USER
08-19 17:55:27.876  1015  1027 D PersonaManagerService: isFromApprovedUnInstaller: isApproved before exit: true
08-19 17:55:27.876  1015  1027 D PackageManager: deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag2,
,08-19 17:55:27.876  1015  1027 D PackageManager: deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag2
08-19 17:55:27.876  1015  1055 D PackageManagerService: deletePackage- pkg:com.test.thalitest, edmuserId:0
08-19 17:55:27.876  1015  1055 D PackageManagerService: deletePackage- pkg:com.test.thalitest, edmuserId:-1
,08-19 17:55:27.876  1015  1055 D ApplicationPolicy: getApplicationUninstallationEnabled
08-19 17:55:27.876  1015  1055 D ApplicationPolicy: getApplicationUninstallationEnabled :  enabled true
,08-19 17:55:27.886  1015  1055 D PackageManager: !@killApplicatoin: 10171, uninstall pkg,
,08-19 17:55:27.896  1015  1040 I ActivityManager: Force stopping com.test.thalitest appid=10171 user=-1: uninstall pkg
,08-19 17:55:27.896  1015  1040 I ActivityManager: Killing 6220:com.test.thalitest/u0a171 (adj 0): stop com.test.thalitest cause uninstall pkg
,08-19 17:55:27.966  1015  1055 W PackageSettings: Skipping PackageSetting{5f84aa2 com.example.hello/10168} due to missing metadata
,08-19 17:55:27.996  1015  1040 I ActivityManager:   Force finishing activity ActivityRecord{367e6aae u0 com.test.thalitest/.MainActivity t2}
,08-19 17:55:27.996  1015  1040 E JavaBinder: !!! FAILED BINDER TRANSACTION !!!
,08-19 17:55:28.006  1015  1040 D InputDispatcher: Focus left window: 6220
,08-19 17:55:28.006   258   436 I SurfaceFlinger: id=13 Removed NainActivit (6/8)
,08-19 17:55:28.006   258  5339 I SurfaceFlinger: id=13 Removed NainActivit (-2/8)
,08-19 17:55:28.016  1015  1040 D InputDispatcher: Focused application released
,08-19 17:55:28.016  1015  1040 D FocusedStackFrame: Set to : 0,
08-19 17:55:28.016  1015  1045 E JavaBinder: !!! FAILED BINDER TRANSACTION !!!,
,08-19 17:55:28.026  1015  1040 W ActivityManager: mDVFSHelper.acquire()
,08-19 17:55:28.026  1015  1045 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
08-19 17:55:28.026  1015  1045 D PointerIcon: setMouseCustomIcon IconType is same.101
,08-19 17:55:28.026  1015  1040 V WindowManager: rotationForOrientationLw(orient=1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false
,08-19 17:55:28.036  1015  1055 I ActivityManager: Force stopping com.test.thalitest appid=10171 user=0: pkg removed
,08-19 17:55:28.056  1015  1055 W ActivityManager: CustomStartingWindow se packge removed so remove capture also
,08-19 17:55:28.086  1476  1476 D Launcher: onRestart, Launcher: 712358677
,08-19 17:55:28.086  1476  1476 D Launcher: onStart, Launcher: 712358677
,08-19 17:55:28.086  1476  1476 D Launcher.HomeView: onStart
,08-19 17:55:28.086  1476  1476 D Launcher: onResume, Launcher: 712358677
,08-19 17:55:28.086  1015  1474 D SettingsProvider: name = kids_home_mode
08-19 17:55:28.086  1015  1474 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-19 17:55:28.086  1015  1474 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-19 17:55:28.086  1015  1474 D SettingsProvider: selectionArgs: false
08-19 17:55:28.086  1015  1474 D SettingsProvider: selectionArgs: 10006
08-19 17:55:28.086  1015  1474 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-19 17:55:28.086  1015  1474 D SettingsProvider: ret = -1
08-19 17:55:28.086  1476  1476 D Launcher.HomeView: onResume
,08-19 17:55:28.096  1476  1476 D Launcher: Launcher::setSystemUiTransparency(): getSystemUiVisibility() after setting  = 0
,08-19 17:55:28.096  1476  1476 D MenuAppsGridFragment: onResume
,08-19 17:55:28.096  1015  3492 D ActivityManager: handle home activity for 0
08-19 17:55:28.096  1015  3492 I WallpaperManagerService: switchPersonaWallpaper is called for personaId-0
08-19 17:55:28.096  1015  3492 D KnoxTimeoutHandler: post home show event for user 0
08-19 17:55:28.096  1015  3492 D ActivityManager: post active user change for 0 fullscreen true record.isFloatingActivity() false
08-19 17:55:28.096  1015  3492 D KnoxTimeoutHandler: postActiveUserChange for user 0
08-19 17:55:28.096  1015  3492 I KnoxTimeoutHandler: postActiveUserChange, showWhenLocked: false
08-19 17:55:28.096  1476  1476 D Launcher.HomeView: onPause
,08-19 17:55:28.096  1476  1476 D Launcher: Launcher::setSystemUiTransparency(): getSystemUiVisibility() after setting  = 0
,08-19 17:55:28.096  5998  5998 I art     : Explicit concurrent mark sweep GC freed 14970(855KB) AllocSpace objects, 0(0B) LOS objects, 50% free, 3MB/7MB, paused 739us total 45.175ms
,08-19 17:55:28.116   258   258 I SurfaceFlinger: id=14 createSurf (540x960),1 flag=4, Mauncher
,08-19 17:55:28.116  1015  1043 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
,08-19 17:55:28.116  1015  1043 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
,08-19 17:55:28.126  1015  1474 D InputDispatcher: Focus entered window: 1476
,08-19 17:55:28.126  1015  1045 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
08-19 17:55:28.126  1015  1045 D PointerIcon: setMouseCustomIcon IconType is same.101
,08-19 17:55:28.126  1476  1476 D SRIB_DCS: log_dcs ThreadedRenderer::initialize entered! 
,08-19 17:55:28.126  4129  4129 I art     : Explicit concurrent mark sweep GC freed 6220(368KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 12MB/20MB, paused 1.246ms total 81.831ms
,08-19 17:55:28.136  1476  1476 V ActivityThread: updateVisibility : ActivityRecord{3e6ab48a token=android.os.BinderProxy@3fd4bd0d {com.sec.android.app.launcher/com.android.launcher2.Launcher}} show : true
,08-19 17:55:28.136  1476  1476 D Launcher.HomeView: onStop
,08-19 17:55:28.156  1979  2165 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
,08-19 17:55:28.156  1015  1096 I InputReader: Reconfiguring input devices.  changes=0x00000010
,08-19 17:55:28.166  1823  1823 E SamsungIME: mOCRHelper is null
,08-19 17:55:28.166  5904  5904 I art     : Explicit concurrent mark sweep GC freed 429(28KB) AllocSpace objects, 0(0B) LOS objects, 25% free, 6MB/8MB, paused 803us total 100.954ms
,08-19 17:55:28.176  1015  1474 D InputMethodManagerService: windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,08-19 17:55:28.186  1015  1120 V NetworkStats: removeUidsLocked() for UIDs [10171]
08-19 17:55:28.186  1015  1120 V NetworkStats: performPollLocked(flags=0x3)
,08-19 17:55:28.186  1015  1120 D NetworkStatsFactory: UpdateStatsForKnox updated
08-19 17:55:28.186  1015  1474 W InputMethodManagerService: Got RemoteException sending setActive(false) notification to pid 6220 uid 10171
,08-19 17:55:28.186  1015  1120 D NetworkStatsFactory: UpdateStatsForKnox main else ---
,08-19 17:55:28.186  1015  1120 V NetworkStats: performPollLocked() took 7ms
,08-19 17:55:28.206  1015  6686 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.android.server.InputMethodManagerService$6.run:2762 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,08-19 17:55:28.206  1823  1823 D SamsungIME: onStartInput: No inputType, No imeOption, isInputViewShown = false, isExtractViewShown = false, isShowInputRequested = false, isConfigChanged = false
,08-19 17:55:28.226  1476  1476 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@3fd4bd0d time:145457
,08-19 17:55:28.226  1427  1427 D PersonaManager: isKioskContainerExistOnDevice
,08-19 17:55:28.236  3835  3835 I KLMS-2.5.123: : KLMSAbstractReciever(): onReceive(): Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.samsung.klmsagent/.listner.MainReciver (has extras) } | timestamp: Fri Aug 19 17:55:28 GMT+02:00 2016
,08-19 17:55:28.236  1427  1427 D RegisteredServicesCache: empty dynamic service
,08-19 17:55:28.246  1015  1768 D ActivityManager: startService callerProcessName:com.samsung.klmsagent, calleePkgName: com.samsung.klmsagent
08-19 17:55:28.246  1015  1768 D ActivityManager: retrieveServiceLocked(): component = com.samsung.klmsagent/com.samsung.klmsagent.services.KLMSIntentService; callingUser = 0; userId(target) = 0
,08-19 17:55:28.246  1015  1768 W ActivityManager: userId = 0, bbcId = -10000
,08-19 17:55:28.246  1015  1768 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-19 17:55:28.246  1015  1768 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.klmsagent, destAppInfo.processName = com.samsung.klmsagent
,08-19 17:55:28.266  1015  1045 W ActivityManager: mDVFSHelper.release()
,08-19 17:55:28.266  1015  1045 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{2e6c1502 u0 com.sec.android.app.launcher/com.android.launcher2.Launcher t1} time:145494
,08-19 17:55:28.276  1015  1039 D EnterpriseDeviceManagerService: Package has changed for user 0
08-19 17:55:28.276  1015  1039 D EnterpriseDeviceManagerService: Admin package name: com.google.android.gms
,08-19 17:55:28.276  1015  1039 W TextServicesManagerService: no available spell checker services found
,08-19 17:55:28.276  1015  1015 I art     : Explicit concurrent mark sweep GC freed 62543(3MB) AllocSpace objects, 8(128KB) LOS objects, 33% free, 24MB/36MB, paused 5.157ms total 219.520ms
08-19 17:55:28.276  1015  1015 D WallpaperManagerService:  force update = false; persona id = 0; current user =0; current persona = 0
08-19 17:55:28.276  1015  1015 D KnoxTimeoutHandler: handleHomeShow for 0 and current 0
08-19 17:55:28.276  1015  1015 D PersonaManagerService: getPersonasForUser(): returning null!
08-19 17:55:28.276  1015  1015 D KnoxTimeoutHandler: handleActiveUserChange for user 0
08-19 17:55:28.276  1015  1055 I art     : WaitForGcToComplete blocked for 211.067ms for cause Explicit
,08-19 17:55:28.296  3835  3835 I KLMS-2.5.123: : KLMSAbstractReciever(): onReceive().END.
,08-19 17:55:28.296  1427  1427 D RegisteredComponentCache: Collect Tech packages for Knox
,08-19 17:55:28.296  1015  1470 I splitIntent: Split this intent : android.intent.action.PACKAGE_REMOVED, mSplitNum[0]=11, mSplitNum[1]=21, mSplitNum[2]=31, mBgSplitQueueNum=3 divideNum= 10 r.nextReceiver= 1 receivers.size=41
08-19 17:55:28.296  1015  1470 I splitIntent: finish to split intent : android.intent.action.PACKAGE_REMOVED !! Enqueue -> schedule it!!
,08-19 17:55:28.296  1015  1470 D ActivityManager: startProcessLocked calleePkgName: com.sec.esdk.elm, hostingType: broadcast
,08-19 17:55:28.306  1015  1470 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-19 17:55:28.306  1015  1470 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-19 17:55:28.306  1015  1470 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-19 17:55:28.306  1015  1470 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-19 17:55:28.306  1015  1039 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,08-19 17:55:28.316  1015  1133 D SecContentProvider2: uri = 11 selection = getMyKnoxAdmin
08-19 17:55:28.316  1015  1133 D SecContentProvider2: mCursor = null
,08-19 17:55:28.316  6690  6690 E Zygote  : MountEmulatedStorage()
08-19 17:55:28.316  6690  6690 E Zygote  : v2
08-19 17:55:28.316  6690  6690 I libpersona: KNOX_SDCARD checking this for 10090
08-19 17:55:28.316  6690  6690 I libpersona: KNOX_SDCARD not a persona
08-19 17:55:28.316  6690  6690 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51,
08-19 17:55:28.316  1015  1121 D NtpTrustedTime: forceRefresh() from cache miss
,08-19 17:55:28.326  6690  6690 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
08-19 17:55:28.326  1015  1470 I ActivityManager: Start proc com.sec.esdk.elm for broadcast com.sec.esdk.elm/.receiver.MainReceiver: pid=6690 uid=10090 gids={50090, 9997, 3003} abi=armeabi-v7a
,08-19 17:55:28.326   281   967 D EnterpriseController: mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
08-19 17:55:28.326   281   967 D Netd    : getNetworkForDns: using netid 0 for uid 1000
08-19 17:55:28.326  6690  6690 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-19 17:55:28.326  1015  1039 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
08-19 17:55:28.326   281   967 D EnterpriseController: mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
08-19 17:55:28.326   281   967 D Netd    : getNetworkForDns: using netid 0 for uid 1000
08-19 17:55:28.326  1015  1121 D NtpTrustedTime: forceRefresh Fail.
08-19 17:55:28.326  3835  3835 I KLMS-2.5.123: : KLMSIntentService(): onCreate()
,08-19 17:55:28.336  1015  1040 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.app.assistantmenu, hostingType: broadcast
,08-19 17:55:28.336  3835  3835 I KLMS-2.5.123: : KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,08-19 17:55:28.336  1015  1040 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-19 17:55:28.336  1015  1040 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-19 17:55:28.336  1015  1040 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-19 17:55:28.336  1015  1040 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-19 17:55:28.346  3835  3835 I KLMS-2.5.123: : KLMSUtility(): isTestMode(): product_ship: true | testApk: false
,08-19 17:55:28.346  6705  6705 E Zygote  : MountEmulatedStorage()
,08-19 17:55:28.346  6705  6705 E Zygote  : v2,
08-19 17:55:28.346  6705  6705 I libpersona: KNOX_SDCARD checking this for 1000,
08-19 17:55:28.356  6705  6705 I libpersona: KNOX_SDCARD not a persona
,08-19 17:55:28.356  1015  1027 I TactileAssist: enable value -1
,08-19 17:55:28.356  1015  1040 I ActivityManager: Start proc com.samsung.android.app.assistantmenu for broadcast com.samsung.android.app.assistantmenu/.AssistantMenuReceiver: pid=6705 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
08-19 17:55:28.356  1015  1027 I TactileAssist: internal enable value -1
08-19 17:55:28.356  1015  1027 I TactileAssist: intensity value -1
08-19 17:55:28.356  1015  1027 I TactileAssist: saveAppList value true
,08-19 17:55:28.356  6705  6705 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-19 17:55:28.356  6705  6705 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-19 17:55:28.356  6705  6705 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-19 17:55:28.366  6690  6690 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-19 17:55:28.366  6690  6690 D ActivityThread: Added TimaKeyStore provider
,08-19 17:55:28.366  1015  1027 I TactileAssist: List of disabled apps :
,08-19 17:55:28.366  1015  1040 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.app.popupuireceiver, hostingType: broadcast
,08-19 17:55:28.376  3835  6689 I KLMS-2.5.123: : KLMSIntentService(): onHandleIntent().START: Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.samsung.klmsagent/.services.KLMSIntentService (has extras) }
,08-19 17:55:28.376  1015  1040 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-19 17:55:28.376  1015  1040 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-19 17:55:28.376  1015  1040 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-19 17:55:28.376  3835  6689 I KLMS-2.5.123: : KLMSIntentService(): PACKAGE_REMOVED
08-19 17:55:28.376  1015  1040 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-19 17:55:28.376  3835  6689 I KLMS-2.5.123: : KLMSIntentService(): listeningToPackageRemoved().START
,08-19 17:55:28.386  3835  6689 I KLMS-2.5.123: : KLMSIntentService(): REPLACING: false | pkgName: com.test.thalitest
,08-19 17:55:28.386  6722  6722 E Zygote  : MountEmulatedStorage()
08-19 17:55:28.386  6722  6722 E Zygote  : v2
08-19 17:55:28.386  6722  6722 I libpersona: KNOX_SDCARD checking this for 1000
08-19 17:55:28.386  6722  6722 I libpersona: KNOX_SDCARD not a persona
,08-19 17:55:28.396  6722  6722 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51,
,08-19 17:55:28.396  6722  6722 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
08-19 17:55:28.396  6722  6722 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-19 17:55:28.396  1015  1015 D RCPManagerService: PackageReceiver onReceive()
08-19 17:55:28.396  1015  1040 I ActivityManager: Start proc com.sec.android.app.popupuireceiver for broadcast com.sec.android.app.popupuireceiver/.PopupuiReceiver: pid=6722 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,08-19 17:55:28.406  6705  6705 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-19 17:55:28.406  6705  6705 D ActivityThread: Added TimaKeyStore provider
08-19 17:55:28.406  1015  1015 I HarmonyEASService: onReceive : android.intent.action.PACKAGE_REMOVED for 0
08-19 17:55:28.406  1427  1427 D PersonaManager: isKioskContainerExistOnDevice
,08-19 17:55:28.426   308   308 I art     : Explicit concurrent mark sweep GC freed 8730(371KB) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 612us total 31.204ms,
,08-19 17:55:28.426  1015  1015 D KnoxMUMContainerPolicy: mPackageReceiver : action - android.intent.action.PACKAGE_REMOVED
08-19 17:55:28.426  1015  1015 I OTPFW   : PackageRemovalReceiver::onReceive Enter
08-19 17:55:28.426  1015  1015 D OTPFW   : PackageRemovalReceiver::onReceive deleting token for Pkg = com.test.thalitest uid = 10171 container id = 0
,08-19 17:55:28.436  6722  6722 D TimaKeyStoreProvider: TimaSignature is unavailable
08-19 17:55:28.446  6722  6722 D ActivityThread: Added TimaKeyStore provider
,08-19 17:55:28.446   308   308 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 574us total 16.904ms
,08-19 17:55:28.446  1015  1015 I OTPFW   : ProvisionData::getAllEntries Enter
,08-19 17:55:28.466   308   308 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 596us total 16.724ms
08-19 17:55:28.466  1015  1039 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,08-19 17:55:28.476  1015  1039 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,08-19 17:55:28.496  1015  1475 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.app.soundalive, hostingType: broadcast
,08-19 17:55:28.496  1015  1475 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-19 17:55:28.496  1015  1475 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-19 17:55:28.496  1015  1475 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-19 17:55:28.496  1015  1475 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-19 17:55:28.506  6737  6737 E Zygote  : MountEmulatedStorage()
08-19 17:55:28.506  6737  6737 E Zygote  : v2
08-19 17:55:28.506  6737  6737 I libpersona: KNOX_SDCARD checking this for 10048
08-19 17:55:28.506  6737  6737 I libpersona: KNOX_SDCARD not a persona
,08-19 17:55:28.506  6737  6737 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-19 17:55:28.516  6737  6737 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-19 17:55:28.516  6737  6737 E SELinux : [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,08-19 17:55:28.516  1015  1475 I ActivityManager: Start proc com.sec.android.app.soundalive for broadcast com.sec.android.app.soundalive/.compatibility.Compatibility$Receiver: pid=6737 uid=10048 gids={50048, 9997, 3003, 3002} abi=armeabi-v7a
,08-19 17:55:28.526  6722  6722 D PopupuiReceiver: onReceive() getAction : android.intent.action.PACKAGE_REMOVED
,08-19 17:55:28.526  1015  1015 E OTPFW   : ProvisionData::getAllEntries Table is empty
,08-19 17:55:28.526  1015  1133 D SecContentProvider2: uri = -1 selection = getSealedState
08-19 17:55:28.526  1015  1133 D SecContentProvider2: mCursor = null
,08-19 17:55:28.526  6722  6722 I PopupuiReceiver_KNOX: getSealedState : true
08-19 17:55:28.526  1015  1475 D SecContentProvider2: uri = 15 selection = getSealedHideNotificationMessages
08-19 17:55:28.526  1015  1475 D SecContentProvider2: mCursor = null
,08-19 17:55:28.536  6722  6722 I PopupuiReceiver_KNOX: getSealedHideNotificationMessages : 1
,08-19 17:55:28.536  1015  1027 D SecContentProvider2: uri = 15 selection = getCheckCoverPopupState
08-19 17:55:28.536  1015  1027 D SecContentProvider2: mCursor = null
08-19 17:55:28.536  6722  6722 I PopupuiReceiver_KNOX: getCheckCoverPopupState : true
08-19 17:55:28.536  6722  6722 D PopupuiReceiver: Action package removed
,08-19 17:55:28.536  1015  1055 I art     : Explicit concurrent mark sweep GC freed 13466(1083KB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 24MB/36MB, paused 12.980ms total 263.256ms
08-19 17:55:28.546  1015  1133 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.app.themechooser, hostingType: broadcast
,08-19 17:55:28.546  1015  1133 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-19 17:55:28.546  3835  6689 I KLMS-2.5.123: : KLMSIntentService(): Notification App List is Null. Remove Notification.
08-19 17:55:28.546  1015  1133 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-19 17:55:28.546  1015  1133 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-19 17:55:28.546  1015  1133 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-19 17:55:28.556  6705  6705 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.samsung.android.app.assistantmenu.AssistantMenuReceiver.onReceive:159 android.app.ActivityThread.handleReceiver:3125 
,08-19 17:55:28.556  6737  6737 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-19 17:55:28.556  6737  6737 D ActivityThread: Added TimaKeyStore provider
,08-19 17:55:28.556  6690  6690 D elm:15121: ELMAbstractReceiver.onReceive() : Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.receiver.MainReceiver (has extras) }
,08-19 17:55:28.556  6690  6690 D elm:15121: ELMEngine.ELMEngine( context ).,
,08-19 17:55:28.566  6690  6690 D elm:15121: MDMBridge.setEnterpriseBridge()
,08-19 17:55:28.566  3835  6689 I KLMS-2.5.123: : KLMSValidator(): IsPackageExistInDevice().Not Exsit: com.test.thalitest
,08-19 17:55:28.566  6752  6752 E Zygote  : MountEmulatedStorage()
,08-19 17:55:28.566  6752  6752 E Zygote  : v2
,08-19 17:55:28.566  3835  6689 I KLMS-2.5.123: : KLMSIntentService(): listeningToPackageRemoved().END
08-19 17:55:28.566  6752  6752 I libpersona: KNOX_SDCARD checking this for 10145
08-19 17:55:28.566  6752  6752 I libpersona: KNOX_SDCARD not a persona
08-19 17:55:28.566  1015  1133 I ActivityManager: Start proc com.sec.android.app.themechooser for broadcast com.sec.android.app.themechooser/.CustomBroadCastReceiver: pid=6752 uid=10145 gids={50145, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,08-19 17:55:28.566  6752  6752 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-19 17:55:28.576  1015  1446 D ActivityManager: startService callerProcessName:com.sec.esdk.elm, calleePkgName: com.sec.esdk.elm
08-19 17:55:28.576  1015  1446 D ActivityManager: retrieveServiceLocked(): component = com.sec.esdk.elm/com.sec.esdk.elm.service.ElmAgentService; callingUser = 0; userId(target) = 0
,08-19 17:55:28.576  1015  1446 W ActivityManager: userId = 0, bbcId = -10000
08-19 17:55:28.576  1015  1446 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-19 17:55:28.576  1015  1446 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.esdk.elm, destAppInfo.processName = com.sec.esdk.elm
08-19 17:55:28.576  6752  6752 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-19 17:55:28.576  6752  6752 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-19 17:55:28.576  6690  6690 D elm:15121: ELMAbstractReceiver : Receive Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) } END.
08-19 17:55:28.576  1015  1475 D ActivityManager: startService callerProcessName:com.samsung.android.app.assistantmenu, calleePkgName: com.samsung.android.app.assistantmenu
08-19 17:55:28.576  1015  1475 D ActivityManager: retrieveServiceLocked(): component = com.samsung.android.app.assistantmenu/com.samsung.android.app.assistantmenu.serviceframework.AMMetaDataParserService; callingUser = 0; userId(target) = 0
,08-19 17:55:28.576  1015  1475 W ActivityManager: userId = 0, bbcId = -10000
08-19 17:55:28.576  1015  1475 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-19 17:55:28.576  1015  1475 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.android.app.assistantmenu, destAppInfo.processName = com.samsung.android.app.assistantmenu
,08-19 17:55:28.586  3835  3835 I KLMS-2.5.123: : KLMSIntentService(): onDestroy()
08-19 17:55:28.586  1015  1474 D ActivityManager: startProcessLocked calleePkgName: com.sec.knox.bridge, hostingType: broadcast
08-19 17:55:28.586  1015  1474 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-19 17:55:28.586  1015  1474 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-19 17:55:28.586  1015  1474 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-19 17:55:28.586  1015  1474 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-19 17:55:28.596  6690  6690 D elm:15121: ElmAgentService : onCreate()
,08-19 17:55:28.596  6690  6759 D elm:15121: ElmAgentService : onHandleIntent() Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) }
,08-19 17:55:28.596  6690  6759 D elm:15121: MainReceiver.listeningToPackageRemoved()
08-19 17:55:28.596  6690  6759 D elm:15121: MDMBridge.getInstance()
08-19 17:55:28.596  6690  6759 D elm:15121: MDMBridge.getAllLicenseInfoFromSDK()
,08-19 17:55:28.606  6690  6759 D elm:15121: MDMBridge.getAllLicenseInfoFromSDK()
,08-19 17:55:28.606  6767  6767 E Zygote  : MountEmulatedStorage()
08-19 17:55:28.606  6767  6767 I libpersona: KNOX_SDCARD checking this for 1000
08-19 17:55:28.606  6767  6767 E Zygote  : v2
08-19 17:55:28.606  6767  6767 I libpersona: KNOX_SDCARD not a persona
,08-19 17:55:28.606  6767  6767 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-19 17:55:28.616  6737  6737 D Compatibility: onReceive() it will make start service,
08-19 17:55:28.616  6767  6767 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-19 17:55:28.616  6767  6767 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-19 17:55:28.616  1015  1474 I ActivityManager: Start proc com.sec.knox.bridge for broadcast com.sec.knox.bridge/.PersonaShortcutReceiver: pid=6767 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,08-19 17:55:28.616  1015  1039 W ResourceType: Failure getting entry for 0x7f07007b (t=6 e=123) (error -75)
,08-19 17:55:28.626  1015  3485 D ActivityManager: startService callerProcessName:com.sec.android.app.soundalive, calleePkgName: com.sec.android.app.soundalive
,08-19 17:55:28.626  1015  3485 D ActivityManager: retrieveServiceLocked(): component = com.sec.android.app.soundalive/com.sec.android.app.soundalive.compatibility.Compatibility$Service; callingUser = 0; userId(target) = 0
,08-19 17:55:28.626  6752  6752 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-19 17:55:28.626  6752  6752 D ActivityThread: Added TimaKeyStore provider
08-19 17:55:28.626  1015  3485 W ActivityManager: userId = 0, bbcId = -10000
08-19 17:55:28.626  1015  3485 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-19 17:55:28.626  1015  3485 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.android.app.soundalive, destAppInfo.processName = com.sec.android.app.soundalive
,08-19 17:55:28.636  1015  1768 D ActivityManager: startService callerProcessName:com.google.android.googlequicksearchbox, calleePkgName: com.google.android.googlequicksearchbox
08-19 17:55:28.636  1015  1768 D ActivityManager: retrieveServiceLocked(): component = com.google.android.googlequicksearchbox/com.google.android.search.core.icingsync.UpdateIcingCorporaService; callingUser = 0; userId(target) = 0
,08-19 17:55:28.636  6690  6690 D elm:15121: ElmAgentService : onDestroy().
,08-19 17:55:28.646  1015  1768 W ActivityManager: userId = 0, bbcId = -10000
08-19 17:55:28.646  1015  1768 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-19 17:55:28.646  1015  1768 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.googlequicksearchbox, destAppInfo.processName = com.google.android.googlequicksearchbox
,08-19 17:55:28.646  6737  6783 D Compatibility: onHandleIntent()
08-19 17:55:28.646  6737  6783 D Compatibility: intentservice saw: Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.android.app.soundalive/.compatibility.Compatibility$Receiver (has extras) } Bundle[{android.intent.extra.REMOVED_FOR_ALL_USERS=true, android.intent.extra.UID=10171, android.intent.extra.DATA_REMOVED=true, android.intent.extra.user_handle=0}]
,08-19 17:55:28.646  6737  6783 D Compatibility: found: 2
,08-19 17:55:28.656  6767  6767 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-19 17:55:28.656  6767  6767 D ActivityThread: Added TimaKeyStore provider
,08-19 17:55:28.666  1015  3485 I ActivityManager: Killing 5935:com.sec.android.app.samsungapps/u0a9 (adj 15): empty #21
,08-19 17:55:28.666  1015  1027 D ActivityManager: startService callerProcessName:com.google.android.googlequicksearchbox, calleePkgName: com.google.android.googlequicksearchbox
,08-19 17:55:28.666  1015  1027 D ActivityManager: retrieveServiceLocked(): component = com.google.android.googlequicksearchbox/com.google.android.search.core.icingsync.UpdateIcingCorporaService; callingUser = 0; userId(target) = 0
,08-19 17:55:28.666  1015  1027 W ActivityManager: userId = 0, bbcId = -10000
08-19 17:55:28.666  1015  1027 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-19 17:55:28.666  1015  1027 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.googlequicksearchbox, destAppInfo.processName = com.google.android.googlequicksearchbox
,08-19 17:55:28.676  6737  6783 D Compatibility: saved default: com.sec.android.app.soundalive.SAControlPanelActivity
,08-19 17:55:28.686  6767  6767 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,08-19 17:55:28.686  6737  6783 D Compatibility: skipping ResolveInfo{10383b34 com.sec.android.app.soundalive/.compatibility.Compatibility$Redirector p=2147483647 m=0x108000}
,08-19 17:55:28.686  1015  1039 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,08-19 17:55:28.686  6737  6783 D Compatibility: considering ResolveInfo{8333d5d com.sec.android.app.soundalive/.SAControlPanelActivity m=0x108000}
08-19 17:55:28.686  6737  6783 D Compatibility: default: com.sec.android.app.soundalive.SAControlPanelActivity
,08-19 17:55:28.696  5904  6787 I UpdateIcingCorporaServi: Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
08-19 17:55:28.696  1015  1055 D PackageManager: delete codoeFile: 
,08-19 17:55:28.696  6307  6307 D UserAnalysis.UserAnalysisBroadcastReceiver: Intent(action: android.intent.action.PACKAGE_REMOVED) is received.
,08-19 17:55:28.696  6737  6783 D Compatibility: enabling receiver ResolveInfo{2d71a6d2 com.sec.android.app.soundalive/.SAControlPanelReceiver m=0x108000}
,08-19 17:55:28.706  1015  1039 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,08-19 17:55:28.716  6737  6783 D Compatibility: enabling receiver ResolveInfo{12a433a3 com.sec.android.app.soundalive/.compatibility.HelperGooglePlayMusic m=0x108000}
,08-19 17:55:28.716  1015  1055 D AASAuninstall: userId = 0, info.removedAppID = 10171, info.uid = 10171, packageName = com.test.thalitest
08-19 17:55:28.716  1015  1055 I AASA_removePackage: UID=10171 Target=com.test.thalitest
08-19 17:55:28.716  1015  1055 D PackageManager: result of delete: 1{931359026}
,08-19 17:55:28.716  6752  6752 D ThemeInfoUtil: getCurrentFestivalName is [null]
08-19 17:55:28.716  6752  6752 D ThemeInfoUtil: isCurrentFestival = false
,08-19 17:55:28.716  6767  6767 D RCPManager:  in createShortcut() for packageName: com.test.thalitest userId0
,08-19 17:55:28.726  1015  3494 D PersonaManager: isKioskContainerExistOnDevice
,08-19 17:55:28.726  1015  1338 D RCPManagerService:  in createShortcut() for packageName: com.test.thalitest userId0
08-19 17:55:28.726  1015  1338 D RCPManagerService: queryAllProviders():  providerCallBack is not register for 0
,08-19 17:55:28.736  6737  6783 D Compatibility: enabling receiver ResolveInfo{ab7d6a0 com.sec.android.app.soundalive/.SAControlPanelReceiver m=0x108000}
,08-19 17:55:28.736  6737  6783 D Compatibility: enabling receiver ResolveInfo{336b5259 com.sec.android.app.soundalive/.compatibility.HelperGooglePlayMusic m=0x108000}
,08-19 17:55:28.736  1015  1039 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,08-19 17:55:28.746  6674  6674 D AndroidRuntime: Shutting down VM
,08-19 17:55:28.746  6737  6783 D Compatibility: wrote com.sec.android.app.soundalive/com.sec.android.app.soundalive.SAControlPanelActivity as default
,08-19 17:55:28.746  1015  1028 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.provider.shootingmodeprovider, hostingType: broadcast
,08-19 17:55:28.746   291   291 E SMD     : DCD OFF
,08-19 17:55:28.746  1015  1028 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-19 17:55:28.746  1015  1028 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-19 17:55:28.746  1015  1028 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-19 17:55:28.746  1015  1028 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-19 17:55:28.756  6307  6307 V PlaceDetection v1.0.19 : [PlaceDetection::setDisableDetection] PlaceType PLACE_OTHER disabled.
,08-19 17:55:28.756  6307  6307 V PlaceDetection v1.0.19 : [PlaceDetectionManager::setChangeDetector] PlaceType PLACE_OTHER set as false.
,08-19 17:55:28.756  6307  6307 V PlaceDetection v1.0.19 : [PlaceDetectionManager::setSharedData] PreferenceValue PLACE_OTHER_ACTIVITY set as false
08-19 17:55:28.756  6307  6307 V PlaceDetection v1.0.19 : [PlaceDetectionManager::setSharedData] PreferenceValue COLLECTION_GPS set as false
08-19 17:55:28.756  6307  6307 V PlaceDetection v1.0.19 : [PlaceDetectionManager::setSharedData] PreferenceValue COLLECTION_WIFI set as false
,08-19 17:55:28.756  6307  6307 V PlaceDetection v1.0.19 : [PlaceDetectionManager::setSharedData] PreferenceValue COLLECTION_NETWORK set as false
08-19 17:55:28.756  6307  6307 V PlaceDetection v1.0.19 : [PlaceDetectionManager::setSharedData] PreferenceValue COLLECTION_SENSOR set as false
08-19 17:55:28.756  6307  6307 V PlaceDetection v1.0.19 : [PlaceDetection::setDisableDetection] PlaceType PLACE_HOME disabled.
,08-19 17:55:28.756  6307  6307 V PlaceDetection v1.0.19 : [PlaceDetectionManager::setChangeDetector] PlaceType PLACE_HOME set as false.
08-19 17:55:28.756  6307  6307 V PlaceDetection v1.0.19 : [PlaceDetectionManager::setSharedData] PreferenceValue PLACE_HOME set as false
08-19 17:55:28.756  6307  6307 V PlaceDetection v1.0.19 : [PlaceDetectionManager::setSharedData] PreferenceValue COLLECTION_GPS set as false
,08-19 17:55:28.756  6307  6307 V PlaceDetection v1.0.19 : [PlaceDetectionManager::setSharedData] PreferenceValue COLLECTION_WIFI set as false
08-19 17:55:28.756  6307  6307 V PlaceDetection v1.0.19 : [PlaceDetectionManager::setSharedData] PreferenceValue COLLECTION_NETWORK set as false
08-19 17:55:28.756  6307  6307 V PlaceDetection v1.0.19 : [PlaceDetectionManager::setSharedData] PreferenceValue COLLECTION_SENSOR set as false
08-19 17:55:28.756  6307  6307 V PlaceDetection v1.0.19 : [PlaceDetection::setDisableDetection] PlaceType PLACE_WORK disabled.
08-19 17:55:28.756  6307  6307 V PlaceDetection v1.0.19 : [PlaceDetectionManager::setChangeDetector] PlaceType PLACE_WORK set as false.
08-19 17:55:28.756  6307  6307 V PlaceDetection v1.0.19 : [PlaceDetectionManager::setSharedData] PreferenceValue PLACE_WORK set as false
08-19 17:55:28.756  6307  6307 V PlaceDetection v1.0.19 : [PlaceDetectionManager::setSharedData] PreferenceValue COLLECTION_GPS set as false
,08-19 17:55:28.766  6307  6307 V PlaceDetection v1.0.19 : [PlaceDetectionManager::setSharedData] PreferenceValue COLLECTION_WIFI set as false
,08-19 17:55:28.766  6307  6307 V PlaceDetection v1.0.19 : [PlaceDetectionManager::setSharedData] PreferenceValue COLLECTION_NETWORK set as false
08-19 17:55:28.766  6307  6307 V PlaceDetection v1.0.19 : [PlaceDetectionManager::setSharedData] PreferenceValue COLLECTION_SENSOR set as false
08-19 17:55:28.766  6307  6307 V PlaceDetection v1.0.19 : [PlaceDetection::setDisableDetection] PlaceType MYCAR disabled.
,08-19 17:55:28.766  6307  6307 V PlaceDetection v1.0.19 : [PlaceDetectionManager::setChangeDetector] PlaceType MYCAR set as false.
08-19 17:55:28.766  6307  6307 V PlaceDetection v1.0.19 : [PlaceDetectionManager::setSharedData] PreferenceValue PLACE_CAR set as false
,08-19 17:55:28.766  1015  1028 I ActivityManager: Start proc com.samsung.android.provider.shootingmodeprovider for broadcast com.samsung.android.provider.shootingmodeprovider/com.samsung.android.app.shootingmodeinstaller.PackageIntentReceiver: pid=6789 uid=10148 gids={50148, 9997, 1023} abi=armeabi-v7a
,08-19 17:55:28.766  6789  6789 E Zygote  : MountEmulatedStorage()
08-19 17:55:28.766  6789  6789 I libpersona: KNOX_SDCARD checking this for 10148
08-19 17:55:28.766  6789  6789 E Zygote  : v2
08-19 17:55:28.766  6789  6789 I libpersona: KNOX_SDCARD not a persona
,08-19 17:55:28.776  6789  6789 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
08-19 17:55:28.776  1015  1028 D ActivityManager: startProcessLocked calleePkgName: com.google.android.apps.docs, hostingType: broadcast
,08-19 17:55:28.776  6789  6789 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
08-19 17:55:28.776  1015  1039 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.,
08-19 17:55:28.776  6789  6789 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL,
08-19 17:55:28.776  1015  1039 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-19 17:55:28.776  1015  1042 D Tethering: interfaceLinkStateChanged wlan0, false
,08-19 17:55:28.776  1015  1039 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
08-19 17:55:28.776  1015  1042 D Tethering: interfaceStatusChanged wlan0, false
08-19 17:55:28.776  1015  1028 E ActivityManager: checkUser: useridlist=null, currentuser=0,
,08-19 17:55:28.776  1015  1039 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
08-19 17:55:28.776  1015  1028 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-19 17:55:28.776  1015  1028 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-19 17:55:28.776  1015  1028 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-19 17:55:28.776  1015  1042 I Nat464Xlat: interfaceLinkStateChanged wlan0, false,
08-19 17:55:28.786  6307  6307 D BluetoothAdapter: cancelDiscovery
,08-19 17:55:28.796  6660  6660 I wpa_supplicant: CTRL-EVENT-ASSOC-REJECT bssid=F4.99.3E status_code=1
08-19 17:55:28.796  6660  6660 I wpa_supplicant: wlan0: Setting scan request: 0 sec 500000 usec
08-19 17:55:28.796  6660  6660 I wpa_supplicant: wlan0: State: ASSOCIATING -> DISCONNECTED
08-19 17:55:28.796  6660  6660 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=00.00.00 SSID=4E47373030
,08-19 17:55:28.796  1015  1123 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
08-19 17:55:28.796  1015  1123 D SecContentProvider2: mCursor = null
,08-19 17:55:28.796  1015  1015 D BackupManagerService: Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
,08-19 17:55:28.796  1015  1015 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
08-19 17:55:28.796  1015  1015 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - start - android.intent.action.PACKAGE_REMOVED
08-19 17:55:28.796  1015  1015 V EnterpriseBillingPolicy: uID is 10171
08-19 17:55:28.796  1015  1015 V EnterpriseBillingPolicy: Removed Packageuid is0
08-19 17:55:28.796  1015  1015 V EnterpriseBillingPolicyStorage: getProfileForApplication - enter
,08-19 17:55:28.806  1015  1015 V EnterpriseBillingPolicyStorage: getProfileForApplication - exit null : containerId = 0
08-19 17:55:28.806  1015  1015 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - personal application - profile null
08-19 17:55:28.806  1015  1015 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - might be a vpn vendor package 
08-19 17:55:28.806  1015  1015 V EnterpriseBillingPolicyStorage: getBillingProfileForVpnEngine - start - com.test.thalitest
08-19 17:55:28.806  1015  1015 V EnterpriseBillingPolicyStorage: getBillingProfileForVpnEngine - end - null
,08-19 17:55:28.806  6798  6798 E Zygote  : MountEmulatedStorage(),
08-19 17:55:28.806  6798  6798 E Zygote  : v2
08-19 17:55:28.806  6798  6798 I libpersona: KNOX_SDCARD checking this for 10087
08-19 17:55:28.806  6798  6798 I libpersona: KNOX_SDCARD not a persona
08-19 17:55:28.806  6178  6788 E SQLiteLog: (284) automatic index on crash_info_summary(package_name_touched)
,08-19 17:55:28.806  6798  6798 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
08-19 17:55:28.806  1015  1028 I ActivityManager: Start proc com.google.android.apps.docs for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver: pid=6798 uid=10087 gids={50087, 9997, 1028, 3003, 1015} abi=armeabi-v7a
,08-19 17:55:28.816  1015  1028 I ActivityManager: Killing 5957:com.sec.android.gallery3d/u0a39 (adj 15): empty #21,
,08-19 17:55:28.816  6798  6798 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051,
,08-19 17:55:28.816  1015  1039 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
08-19 17:55:28.816  6798  6798 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
08-19 17:55:28.816  1015  1015 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
08-19 17:55:28.826  6789  6789 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-19 17:55:28.826  1015  1015 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - start - android.intent.action.PACKAGE_FULLY_REMOVED,
08-19 17:55:28.826  1015  1015 V EnterpriseBillingPolicy: uID is 10171
08-19 17:55:28.826  1015  2770 D SSRM:bc : MSG_TYPE_APP_REMOVED::
08-19 17:55:28.826  1015  1015 V EnterpriseBillingPolicy: Removed Packageuid is0
08-19 17:55:28.826  1015  1015 V EnterpriseBillingPolicyStorage: getProfileForApplication - enter
08-19 17:55:28.826  1015  1015 V EnterpriseBillingPolicyStorage: getProfileForApplication - exit null : containerId = 0
08-19 17:55:28.826  1015  1015 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - personal application - profile null
08-19 17:55:28.826  1015  1015 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - might be a vpn vendor package 
08-19 17:55:28.826  1015  1015 V EnterpriseBillingPolicyStorage: getBillingProfileForVpnEngine - start - com.test.thalitest
,08-19 17:55:28.826  6565  6573 D BluetoothAdapterProperties: mDiscovering is false
08-19 17:55:28.826  6565  6573 E BluetoothAdapterService: This is not a scanning status. cancelDiscovery() will be not called.
08-19 17:55:28.826  6307  6307 D BluetoothAdapter: cancelDiscovery = true
,08-19 17:55:28.826  6307  6307 V PlaceDetection v1.0.19 : [BTManager::unregisterReceiver] Error : Failed to unregister bluetooth broadcast receiver.
08-19 17:55:28.826  1015  1015 D WindowOrientationListener:   mReceiver.onReceive :com.samsung.intent.action.AUTOROTATION,  delay = 200
08-19 17:55:28.826  6789  6789 D ActivityThread: Added TimaKeyStore provider
08-19 17:55:28.826  1015  1015 V AlarmManagerEXT: com.test.thalitest(10171) is removed.
08-19 17:55:28.826  1015  1015 V EnterpriseBillingPolicyStorage: getBillingProfileForVpnEngine - end - null
,08-19 17:55:28.826  1172  1172 I StatusBar: Icon Only
08-19 17:55:28.826  1172  1172 D PanelView: There is/are notification(s) 
,08-19 17:55:28.836  1015  1028 I ActivityManager: Killing 6065:com.samsung.android.app.filterinstaller/1000 (adj 15): empty #21
,08-19 17:55:28.836  1015  1446 D ActivityManager: retrieveServiceLocked(): component = com.samsung.android.intelligenceservice/com.samsung.android.placedetection.main.service.ServiceManager; callingUser = 0; userId(target) = 0
,08-19 17:55:28.836  1015  1039 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,08-19 17:55:28.846  1015  1039 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
08-19 17:55:28.846  1015  1039 W Resources: Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
08-19 17:55:28.846  6307  6307 V PlaceDetection v1.0.19 : [PlaceDetection::stopService] Service stopped.
,08-19 17:55:28.846  6307  6307 V PlaceDetection v1.0.19 : [PlaceDetectionManager::removeDetectionListener] PlaceDetectionListener removed.
,08-19 17:55:28.846  1015  1039 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,08-19 17:55:28.856  1015  1039 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
08-19 17:55:28.856  1015  1039 W Resources: Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,08-19 17:55:28.856  1015  1039 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
08-19 17:55:28.856  1015  1039 W Resources: Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
08-19 17:55:28.856  6798  6798 D TimaKeyStoreProvider: TimaSignature is unavailable
08-19 17:55:28.856  6798  6798 D ActivityThread: Added TimaKeyStore provider
08-19 17:55:28.856  1015  1039 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,08-19 17:55:28.856  1015  1039 D UsbSettingsManager: clearDefaults: com.test.thalitest
08-19 17:55:28.856  1015  1039 I CrashAnrDetector: onPackageRemoved : com.test.thalitest
,08-19 17:55:28.876  1476  1476 I Choreographer: Skipped 37 frames!  The application may be doing too much work on its main thread.
,08-19 17:55:28.886  6178  6788 I art     : Explicit concurrent mark sweep GC freed 834(58KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 4MB/6MB, paused 1.033ms total 30.645ms
,08-19 17:55:28.886  1015  1158 D TaskPersister: removeObsoleteFile: deleting file=2_task.xml
,08-19 17:55:28.896  6789  6789 E SQLiteLog: (284) automatic index on shooting_modes(title_id)
,08-19 17:55:28.906  1015  1768 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-19 17:55:28.906  1015  1768 W ActivityManager: userId = 0, bbcId = -10000
08-19 17:55:28.906  1015  1768 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-19 17:55:28.906  1015  1768 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.googlequicksearchbox, destAppInfo.processName = com.google.android.gms
,08-19 17:55:28.906  1015  1768 W ActivityManager: getRunningAppProcesses: caller 10087 does not hold REAL_GET_TASKS; limiting output
,08-19 17:55:28.916  1015  3494 I ActivityManager: Killing 6082:com.samsung.android.app.watchmanagerstub/u0a98 (adj 15): empty #21
,08-19 17:55:28.916  1015  1446 D ActivityManager: startService callerProcessName:com.samsung.android.provider.shootingmodeprovider, calleePkgName: com.samsung.android.provider.shootingmodeprovider
08-19 17:55:28.916  1015  1446 D ActivityManager: retrieveServiceLocked(): component = com.samsung.android.provider.shootingmodeprovider/com.samsung.android.app.shootingmodeinstaller.ShootingModesService; callingUser = 0; userId(target) = 0
,08-19 17:55:28.916  1015  1446 W ActivityManager: userId = 0, bbcId = -10000
08-19 17:55:28.916  1015  1446 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-19 17:55:28.916  1015  1446 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.android.provider.shootingmodeprovider, destAppInfo.processName = com.samsung.android.provider.shootingmodeprovider
,08-19 17:55:28.916  1015  3492 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
08-19 17:55:28.916  1015  3492 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
,08-19 17:55:28.926  1015  3492 W ActivityManager: userId = 0, bbcId = -10000
,08-19 17:55:28.926  1015  3492 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-19 17:55:28.926  1015  3492 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-19 17:55:28.926  1015  1338 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.widgetapp.tapandpay, hostingType: broadcast
,08-19 17:55:28.926  1015  1338 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-19 17:55:28.926  1015  1338 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-19 17:55:28.936  1015  1338 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-19 17:55:28.936  1015  1338 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-19 17:55:28.936  1476  1476 D Launcher.Model: reloadBadges entered.
,08-19 17:55:28.936  6497  6510 D BadgeProvider: sendNotify entered. [uri] : content://com.sec.badge/apps
08-19 17:55:28.936  6497  6510 D BadgeProvider: sendNotify, [notify] : null
08-19 17:55:28.936  1015  1482 W ActivityManager: getRunningAppProcesses: caller 10087 does not hold REAL_GET_TASKS; limiting output
08-19 17:55:28.936  6497  6510 D BadgeProvider: update, [uri] : content://com.sec.badge/apps
08-19 17:55:28.936  6497  6510 D BadgeProvider: update, [BadgeCount] : badgecount=0
08-19 17:55:28.936  6497  6510 D BadgeProvider: update, [UpdateCount] : 1
,08-19 17:55:28.946  6822  6822 E Zygote  : MountEmulatedStorage(),
08-19 17:55:28.946  6822  6822 I libpersona: KNOX_SDCARD checking this for 10152
08-19 17:55:28.946  6822  6822 E Zygote  : v2
08-19 17:55:28.946  6822  6822 I libpersona: KNOX_SDCARD not a persona
,08-19 17:55:28.946  6822  6822 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
08-19 17:55:28.946  1015  1338 I ActivityManager: Start proc com.sec.android.widgetapp.tapandpay for broadcast com.sec.android.widgetapp.tapandpay/.TapandpayAppWidgetProvider: pid=6822 uid=10152 gids={50152, 9997} abi=armeabi-v7a
08-19 17:55:28.946  6822  6822 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
08-19 17:55:28.946  1015  1015 D ActivityManager: startProcessLocked calleePkgName: com.sec.pcw.device, hostingType: broadcast
08-19 17:55:28.946  6822  6822 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
08-19 17:55:28.956  1015  1015 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-19 17:55:28.956  1015  1015 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-19 17:55:28.956  6674  6674 W art     : ConditionVariable::~ConditionVariable for GC request condition variable called with 1 waiters.
08-19 17:55:28.956  1015  1015 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-19 17:55:28.956  1015  1015 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-19 17:55:28.966  6832  6832 E Zygote  : MountEmulatedStorage()
08-19 17:55:28.966  6832  6832 E Zygote  : v2
08-19 17:55:28.966  6832  6832 I libpersona: KNOX_SDCARD checking this for 1000
08-19 17:55:28.966  6832  6832 I libpersona: KNOX_SDCARD not a persona
,08-19 17:55:28.966  6832  6832 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
08-19 17:55:28.966  1015  1015 I ActivityManager: Start proc com.sec.pcw.device for broadcast com.sec.pcw.device/.receiver.SYSTEMReceiver: pid=6832 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
08-19 17:55:28.976  6832  6832 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
08-19 17:55:28.976  6832  6832 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-19 17:55:28.976  1015  1475 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
08-19 17:55:28.976  1015  1475 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.proxy.UpdateIcingCorporaService; callingUser = 0; userId(target) = 0
,08-19 17:55:28.976  1015  1475 W ActivityManager: userId = 0, bbcId = -10000
08-19 17:55:28.976  1015  1475 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-19 17:55:28.976  1015  1475 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-19 17:55:28.986  1015  3494 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
,08-19 17:55:28.986  1015  3494 W ActivityManager: userId = 0, bbcId = -10000
08-19 17:55:28.986  1015  3494 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-19 17:55:28.986  1015  3494 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-19 17:55:28.986  1015  1055 D PackageManager: [MSG] START_CLEANING_PACKAGE packageName{com.test.thalitest}
08-19 17:55:28.986  1015  1055 D PackageManager: userId{-1}
08-19 17:55:28.986  1015  1055 D PackageManager: andCode{true}
08-19 17:55:28.986  1015  1055 D ActivityManager: retrieveServiceLocked(): component = com.android.defcontainer/com.android.defcontainer.DefaultContainerService; callingUser = 0; userId(target) = 0
08-19 17:55:28.996  6822  6822 D TimaKeyStoreProvider: TimaSignature is unavailable
08-19 17:55:28.996  6822  6822 D ActivityThread: Added TimaKeyStore provider
,08-19 17:55:29.006  1015  1474 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
08-19 17:55:29.006  1015  1474 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
,08-19 17:55:29.016  1015  1474 W ActivityManager: userId = 0, bbcId = -10000
08-19 17:55:29.016  1015  1474 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-19 17:55:29.016  1015  1474 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-19 17:55:29.016  6832  6832 D TimaKeyStoreProvider: TimaSignature is unavailable
08-19 17:55:29.016  6832  6832 D ActivityThread: Added TimaKeyStore provider
,08-19 17:55:29.036  1015  3485 I ActivityManager: Killing 6098:com.samsung.helphub/1000 (adj 15): empty #21
,08-19 17:55:29.066  6178  6819 E SQLiteLog: (10) POSIX Error : 9 SQLite Error : 3850
08-19 17:55:29.066  6178  6819 E SQLiteLog: (3850) statement aborts at 21: [DELETE FROM usage_log WHERE strftime('%s','now', '-40 days')*1000 - start_time >= 0] disk I/O error
,08-19 17:55:29.066  6178  6819 E SQLiteLog: (10) POSIX Error : 9 SQLite Error : 3850
08-19 17:55:29.066  6178  6819 E SQLiteLog: (3850) statement aborts at 17: [DELETE FROM running_service_log WHERE strftime('%s','now', '-40 days')*1000 - captured_time >= 0] disk I/O error
,08-19 17:55:29.066  6178  6819 E SQLiteLog: (10) POSIX Error : 9 SQLite Error : 3850
,08-19 17:55:29.076  6178  6819 E SQLiteLog: (3850) statement aborts at 17: [DELETE FROM noti_info WHERE strftime('%s','now', '-40 days')*1000 - posted_date >= 0] disk I/O error
,08-19 17:55:29.076  6822  6822 I TapandpayWidget:TapandpayAppWidgetProvider: onReceive()
,08-19 17:55:29.076  6822  6822 D TapandpayWidget:TapandpayAppWidgetProvider: onReceive() - action : android.intent.action.PACKAGE_REMOVED / mCurIndex :-10
,08-19 17:55:29.076  6178  6819 E SQLiteLog: (10) POSIX Error : 9 SQLite Error : 3850
08-19 17:55:29.076  6178  6819 E SQLiteLog: (3850) statement aborts at 17: [DELETE FROM screen_state_log WHERE strftime('%s','now', '-40 days')*1000 - time >= 0] disk I/O error
,08-19 17:55:29.076  6178  6819 E SQLiteLog: (10) POSIX Error : 9 SQLite Error : 3850
08-19 17:55:29.076  6178  6819 E SQLiteLog: (3850) statement aborts at 17: [DELETE FROM debug_log_info WHERE strftime('%s','now', '-20 days')*1000 - created_At >= 0] disk I/O error
,08-19 17:55:29.076  6178  6819 E SQLiteLog: (10) POSIX Error : 9 SQLite Error : 3850
08-19 17:55:29.076  6178  6819 E SQLiteLog: (3850) statement aborts at 3: [DELETE FROM system_env_info] disk I/O error
,08-19 17:55:29.086  6178  6819 E SQLiteLog: (10) POSIX Error : 9 SQLite Error : 3850
08-19 17:55:29.086  6178  6819 E SQLiteLog: (3850) statement aborts at 22: [INSERT INTO system_env_info(name,value) VALUES (?,?)] disk I/O error
,08-19 17:55:29.086  6178  6819 E SQLiteDatabase: Error inserting name=this value=SmartManager LowpowerContextEngine
08-19 17:55:29.086  6178  6819 E SQLiteDatabase: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
08-19 17:55:29.086  6178  6819 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForLastInsertedRowId(Native Method)
08-19 17:55:29.086  6178  6819 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.executeForLastInsertedRowId(SQLiteConnection.java:952)
08-19 17:55:29.086  6178  6819 E SQLiteDatabase: 	at android.database.sqlite.SQLiteSession.executeForLastInsertedRowId(SQLiteSession.java:788)
08-19 17:55:29.086  6178  6819 E SQLiteDatabase: 	at android.database.sqlite.SQLiteStatement.executeInsert(SQLiteStatement.java:86)
08-19 17:55:29.086  6178  6819 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.insertWithOnConflict(SQLiteDatabase.java:1609)
08-19 17:55:29.086  6178  6819 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.insert(SQLiteDatabase.java:1479)
08-19 17:55:29.086  6178  6819 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.f$b.a(DataStore.java:2487)
08-19 17:55:29.086  6178  6819 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.f.b(DataStore.java:1740)
08-19 17:55:29.086  6178  6819 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.i.g(LowpowerContextEngine.java:206)
08-19 17:55:29.086  6178  6819 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.i.e(LowpowerContextEngine.java:152)
08-19 17:55:29.086  6178  6819 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.i.<init>(LowpowerContextEngine.java:100)
08-19 17:55:29.086  6178  6819 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.i.a(LowpowerContextEngine.java:106)
08-19 17:55:29.086  6178  6819 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.LowpowerContextReceiver$SystemBroadcastReceiver.b(LowpowerContextReceiver.java:133)
08-19 17:55:29.086  6178  6819 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.LowpowerContextReceiver$SystemBroadcastReceiver.a(LowpowerContextReceiver.java:102)
08-19 17:55:29.086  6178  6819 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.LowpowerContextReceiver$SystemBroadcastReceiver.a(LowpowerContextReceiver.java:42)
08-19 17:55:29.086  6178  6819 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.q.run(LowpowerContextReceiver.java:52)
08-19 17:55:29.086  6178  6819 E SQLiteDatabase: 	at android.os.Handler.handleCallback(Handler.java:739)
08-19 17:55:29.086  6178  6819 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-19 17:55:29.086  6178  6819 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:145)
08-19 17:55:29.086  6178  6819 E SQLiteDatabase: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,08-19 17:55:29.086  6178  6819 E SQLiteLog: (10) POSIX Error : 9 SQLite Error : 3850
08-19 17:55:29.086  6178  6819 E SQLiteLog: (3850) statement aborts at 22: [INSERT INTO system_env_info(name,value) VALUES (?,?)] disk I/O error
,08-19 17:55:29.086  6178  6819 E SQLiteDatabase: Error inserting name=now value=Fri Aug 19 17:55:29 GMT+02:00 2016
08-19 17:55:29.086  6178  6819 E SQLiteDatabase: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
08-19 17:55:29.086  6178  6819 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForLastInsertedRowId(Native Method)
08-19 17:55:29.086  6178  6819 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.executeForLastInsertedRowId(SQLiteConnection.java:952)
08-19 17:55:29.086  6178  6819 E SQLiteDatabase: 	at android.database.sqlite.SQLiteSession.executeForLastInsertedRowId(SQLiteSession.java:788)
,08-19 17:55:29.086  6178  6819 E SQLiteDatabase: 	at android.database.sqlite.SQLiteStatement.executeInsert(SQLiteStatement.java:86)
08-19 17:55:29.086  6178  6819 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.insertWithOnConflict(SQLiteDatabase.java:1609)
08-19 17:55:29.086  6178  6819 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.insert(SQLiteDatabase.java:1479)
08-19 17:55:29.086  6178  6819 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.f$b.a(DataStore.java:2487)
08-19 17:55:29.086  6178  6819 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.f.b(DataStore.java:1740)
08-19 17:55:29.086  6178  6819 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.i.g(LowpowerContextEngine.java:207)
08-19 17:55:29.086  6178  6819 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.i.e(LowpowerContextEngine.java:152)
08-19 17:55:29.086  6178  6819 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.i.<init>(LowpowerContextEngine.java:100)
08-19 17:55:29.086  6178  6819 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.i.a(LowpowerContextEngine.java:106)
08-19 17:55:29.086  6178  6819 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.LowpowerContextReceiver$SystemBroadcastReceiver.b(LowpowerContextReceiver.java:133)
08-19 17:55:29.086  6178  6819 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.LowpowerContextReceiver$SystemBroadcastReceiver.a(LowpowerContextReceiver.java:102)
08-19 17:55:29.086  6178  6819 E SQLiteDatabase: 	,at com.samsung.android.sm.database.lowpowercontext.LowpowerContextReceiver$SystemBroadcastReceiver.a(LowpowerContextReceiver.java:42)
08-19 17:55:29.086  6178  6819 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.q.run(LowpowerContextReceiver.java:52)
08-19 17:55:29.086  6178  6819 E SQLiteDatabase: 	at android.os.Handler.handleCallback(Handler.java:739)
08-19 17:55:29.086  6178  6819 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-19 17:55:29.086  6178  6819 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:145)
08-19 17:55:29.086  6178  6819 E SQLiteDatabase: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-19 17:55:29.086  6178  6819 E SQLiteLog: (10) POSIX Error : 9 SQLite Error : 3850
08-19 17:55:29.086  6178  6819 E SQLiteLog: (3850) statement aborts at 22: [INSERT INTO system_env_info(name,value) VALUES (?,?)] disk I/O error
,08-19 17:55:29.086  6178  6819 E SQLiteDatabase: Error inserting name=isSystemBuild value=false
08-19 17:55:29.086  6178  6819 E SQLiteDatabase: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
08-19 17:55:29.086  6178  6819 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForLastInsertedRowId(Native Method)
08-19 17:55:29.086  6178  6819 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.executeForLastInsertedRowId(SQLiteConnection.java:952)
08-19 17:55:29.086  6178  6819 E SQLiteDatabase: 	at android.database.sqlite.SQLiteSession.executeForLastInsertedRowId(SQLiteSession.java:788)
08-19 17:55:29.086  6178  6819 E SQLiteDatabase: 	at android.database.sqlite.SQLiteStatement.executeInsert(SQLiteStatement.java:86)
,08-19 17:55:29.086  6178  6819 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.insertWithOnConflict(SQLiteDatabase.java:1609)
08-19 17:55:29.086  6178  6819 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.insert(SQLiteDatabase.java:1479)
08-19 17:55:29.086  6178  6819 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.f$b.a(DataStore.java:2487)
08-19 17:55:29.086  6178  6819 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.f.b(DataStore.java:1740)
08-19 17:55:29.086  6178  6819 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.i.g(LowpowerContextEngine.java:208)
08-19 17:55:29.086  6178  6819 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.i.e(LowpowerContextEngine.java:152)
08-19 17:55:29.086  6178  6819 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.i.<init>(LowpowerContextEngine.java:100)
08-19 17:55:29.086  6178  6819 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.i.a(LowpowerContextEngine.java:106)
08-19 17:55:29.086  6178  6819 E SQLiteDatabase: 	,at com.samsung.android.sm.database.lowpowercontext.LowpowerContextReceiver$SystemBroadcastReceiver.b(LowpowerContextReceiver.java:133)
08-19 17:55:29.086  6178  6819 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.LowpowerContextReceiver$SystemBroadcastReceiver.a(LowpowerContextReceiver.java:102)
08-19 17:55:29.086  6178  6819 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.LowpowerContextReceiver$SystemBroadcastReceiver.a(LowpowerContextReceiver.java:42)
08-19 17:55:29.086  6178  6819 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.q.run(LowpowerContextReceiver.java:52)
08-19 17:55:29.086  6178  6819 E SQLiteDatabase: 	at android.os.Handler.handleCallback(Handler.java:739)
08-19 17:55:29.086  6178  6819 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-19 17:55:29.086  6178  6819 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:145)
08-19 17:55:29.086  6178  6819 E SQLiteDatabase: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,08-19 17:55:29.096  6178  6819 E SQLiteLog: (10) POSIX Error : 9 SQLite Error : 3850
08-19 17:55:29.096  1015  3485 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
08-19 17:55:29.096  6178  6819 E SQLiteLog: (3850) statement aborts at 22: [INSERT INTO system_env_info(name,value) VALUES (?,?)] disk I/O error
08-19 17:55:29.096  4129  6849 E SQLiteLog: (10) POSIX Error : 9 SQLite Error : 3850
,08-19 17:55:29.096  4129  6849 E SQLiteLog: (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
,08-19 17:55:29.096  6822  6822 I TapandpayWidget:Utils: Clear T&P info.
,08-19 17:55:29.096  1015  3485 W ActivityManager: userId = 0, bbcId = -10000
,08-19 17:55:29.096  6178  6819 E SQLiteDatabase: Error inserting name=isDevelopVersion value=false
08-19 17:55:29.096  6178  6819 E SQLiteDatabase: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
08-19 17:55:29.096  6178  6819 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForLastInsertedRowId(Native Method)
08-19 17:55:29.096  6178  6819 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.executeForLastInsertedRowId(SQLiteConnection.java:952)
08-19 17:55:29.096  6178  6819 E SQLiteDatabase: 	at android.database.sqlite.SQLiteSession.executeForLastInsertedRowId(SQLiteSession.java:788)
08-19 17:55:29.096  6178  6819 E SQLiteDatabase: 	at android.database.sqlite.SQLiteStatement.executeInsert(SQLiteStatement.java:86)
08-19 17:55:29.096  6178  6819 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.insertWithOnConflict(SQLiteDatabase.java:1609)
08-19 17:55:29.096  6178  6819 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.insert(SQLiteDatabase.java:1479)
08-19 17:55:29.096  6178  6819 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.f$b.a(DataStore.java:2487)
08-19 17:55:29.096  6178  6819 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.f.b(DataStore.java:1740)
08-19 17:55:29.096  6178  6819 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.i.g(LowpowerContextEngine.java:209)
08-19 17:55:29.096  6178  6819 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.i.e(LowpowerContextEngine.java:152)
08-19 17:55:29.096  6178  6819 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.i.<init>(LowpowerContextEngine.java:100)
08-19 17:55:29.096  6178  6819 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.i.a(LowpowerContextEngine.java:106)
08-19 17:55:29.096  6178  6819 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.LowpowerContextReceiver$SystemBroadcastReceiver.b(LowpowerContextReceiver.java:133)
08-19 17:55:29.096  6178  6819 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.LowpowerContextReceiver$SystemBroadcastReceiver.a(LowpowerContextReceiver.java:102)
08-19 17:55:29.096  6178  6819 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.LowpowerContextReceiver$SystemBroadcastReceiver.a(LowpowerContextReceiver.java:42)
08-19 17:55:29.096  6178  6819 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.q.run(LowpowerContextReceiver.java:52)
08-19 17:55:29.096  6178  6819 E SQLiteDatabase: 	at android.os.Handler.handleCallback(Handler.java:739)
08-19 17:55:29.096  6178  6819 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-19 17:55:29.096  6178  6819 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:145)
08-19 17:55:29.096  6178  6819 E SQLiteDatabase: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-19 17:55:29.096  6832  6832 I PCWCLIENTTRACE_LOG: DEFAULT_LOGON : true
08-19 17:55:29.096  6832  6832 I PCWCLIENTTRACE_LOG: DEFAULT_LOGLEVEL : 3
08-19 17:55:29.096  6832  6832 I PCWCLIENTTRACE_DMDBOpenHelper: new DMDBOpenHelper instance
08-19 17:55:29.106  1015  3485 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-19 17:55:29.106  1015  3485 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-19 17:55:29.106  6178  6819 E SQLiteLog: (10) POSIX Error : 9 SQLite Error : 3850
08-19 17:55:29.106  6178  6819 E SQLiteLog: (3850) statement aborts at 22: [INSERT INTO system_env_info(name,value) VALUES (?,?)] disk I/O error
,08-19 17:55:29.106  6178  6819 E SQLiteDatabase: Error inserting name=DBVersion value=2003
08-19 17:55:29.106  6178  6819 E SQLiteDatabase: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
08-19 17:55:29.106  6178  6819 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForLastInsertedRowId(Native Method)
08-19 17:55:29.106  6178  6819 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.executeForLastInsertedRowId(SQLiteConnection.java:952)
08-19 17:55:29.106  6178  6819 E SQLiteDatabase: 	at android.database.sqlite.SQLiteSession.executeForLastInsertedRowId(SQLiteSession.java:788)
08-19 17:55:29.106  6178  6819 E SQLiteDatabase: 	at android.database.sqlite.SQLiteStatement.executeInsert(SQLiteStatement.java:86)
08-19 17:55:29.106  6178  6819 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.insertWithOnConflict(SQLiteDatabase.java:1609)
08-19 17:55:29.106  6178  6819 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.insert(SQLiteDatabase.java:1479)
08-19 17:55:29.106  6178  6819 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.f$b.a(DataStore.java:2487)
08-19 17:55:29.106  6178  6819 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.f.b(DataStore.java:1740)
08-19 17:55:29.106  6178  6819 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.i.g(LowpowerContextEngine.java:210)
08-19 17:55:29.106  6178  6819 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.i.e(LowpowerContextEngine.java:152)
08-19 17:55:29.106  6178  6819 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.i.<init>(LowpowerContextEngine.java:100)
08-19 17:55:29.106  6178  6819 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.i.a(LowpowerContextEngine.java:106)
08-19 17:55:29.106  6178  6819 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.LowpowerContextReceiver$SystemBroadcastReceiver.b(LowpowerContextReceiver.java:133)
08-19 17:55:29.106  6178  6819 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.LowpowerContextReceiver$SystemBroadcastReceiver.a(LowpowerContextReceiver.java:102)
08-19 17:55:29.106  6178  6819 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.LowpowerContextReceiver$SystemBroadcastReceiver.a(LowpowerContextReceiver.java:42)
08-19 17:55:29.106  6178  6819 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.q.run(LowpowerContextReceiver.java:52)
08-19 17:55:29.106  6178  6819 E SQLiteDatabase: 	at android.os.Handler.handleCallback(Handler.java:739)
08-19 17:55:29.106  6178  6819 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-19 17:55:29.106  6178  6819 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:145)
08-19 17:55:29.106  6178  6819 E SQLiteDatabase: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,08-19 17:55:29.106  6178  6819 E SQLiteLog: (10) POSIX Error : 9 SQLite Error : 3850
08-19 17:55:29.106  6178  6819 E SQLiteLog: (3850) statement aborts at 22: [INSERT INTO system_env_info(name,value) VALUES (?,?)] disk I/O error
08-19 17:55:29.106  6832  6832 E SQLiteLog: (28) failed to open "/data/data/com.sec.pcw.device/databases/value.db" with flag (131138) and mode_t (0) due to error (30)
,08-19 17:55:29.106  6178  6819 E SQLiteDatabase: Error inserting name=LPCSystemVersion value=1.0.0
08-19 17:55:29.106  6178  6819 E SQLiteDatabase: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
08-19 17:55:29.106  6178  6819 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForLastInsertedRowId(Native Method)
08-19 17:55:29.106  6178  6819 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.executeForLastInsertedRowId(SQLiteConnection.java:952)
08-19 17:55:29.106  6178  6819 E SQLiteDatabase: 	at android.database.sqlite.SQLiteSession.executeForLastInsertedRowId(SQLiteSession.java:788)
08-19 17:55:29.106  6178  6819 E SQLiteDatabase: 	at android.database.sqlite.SQLiteStatement.executeInsert(SQLiteStatement.java:86)
08-19 17:55:29.106  6178  6819 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.insertWithOnConflict(SQLiteDatabase.java:1609)
08-19 17:55:29.106  6178  6819 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.insert(SQLiteDatabase.java:1479)
08-19 17:55:29.106  6178  6819 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.f$b.a(DataStore.java:2487)
08-19 17:55:29.106  6178  6819 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.f.b(DataStore.java:1740)
08-19 17:55:29.106  6178  6819 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.i.g(LowpowerContextEngine.java:211)
08-19 17:55:29.106  6178  6819 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.i.e(LowpowerContextEngine.java:152)
08-19 17:55:29.106  6178  6819 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.i.<init>(LowpowerContextEngine.java:100)
08-19 17:55:29.106  6178  6819 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.i.a(LowpowerContextEngine.java:106)
08-19 17:55:29.106  6178  6819 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.LowpowerContextReceiver$SystemBroadcastReceiver.b(LowpowerContextReceiver.java:133)
08-19 17:55:29.106  6178  6819 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.LowpowerContextReceiver$SystemBroadcastReceiver.a(LowpowerContextReceiver.java:102)
08-19 17:55:29.106  6178  6819 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.LowpowerContextReceiver$SystemBroadcastReceiver.a(LowpowerContextReceiver.java:42)
08-19 17:55:29.106  6178  6819 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.q.run(LowpowerContextReceiver.java:52)
08-19 17:55:29.106  6178  6819 E SQLiteDatabase: 	at android.os.Handler.handleCallback(Handler.java:739)
08-19 17:55:29.106  6178  6819 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-19 17:55:29.106  6178  6819 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:145)
08-19 17:55:29.106  6178  6819 E SQLiteDatabase: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,08-19 17:55:29.106  6832  6832 E SQLiteDatabase: Failed to open database '/data/data/com.sec.pcw.device/databases/value.db'.
08-19 17:55:29.106  6832  6832 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-19 17:55:29.106  6832  6832 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-19 17:55:29.106  6832  6832 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
,08-19 17:55:29.106  6832  6832 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
08-19 17:55:29.106  6832  6832 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
08-19 17:55:29.106  6832  6832 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
08-19 17:55:29.106  6832  6832 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
08-19 17:55:29.106  6832  6832 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
08-19 17:55:29.106  6832  6832 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
08-19 17:55:29.106  6832  6832 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
08-19 17:55:29.106  6832  6832 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1519)
08-19 17:55:29.106  6832  6832 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
08-19 17:55:29.106  6832  6832 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-19 17:55:29.106  6832  6832 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-19 17:55:29.106  6832  6832 E SQLiteDatabase: 	at com.sec.p,cw.device.contentprovider.DMProvider.onCreate(DMProvider.java:32)
08-19 17:55:29.106  6832  6832 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1729)
08-19 17:55:29.106  6832  6832 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1698)
08-19 17:55:29.106  6832  6832 E SQLiteDatabase: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5702)
08-19 17:55:29.106  6832  6832 E SQLiteDatabase: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:5297)
08-19 17:55:29.106  6832  6832 E SQLiteDatabase: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5237)
08-19 17:55:29.106  6832  6832 E SQLiteDatabase: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
08-19 17:55:29.106  6832  6832 E SQLiteDatabase: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
08-19 17:55:29.106  6832  6832 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-19 17:55:29.106  6832  6832 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:145)
08-19 17:55:29.106  6832  6832 E SQLiteDatabase: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-19 17:55:29.106  6832  6832 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Native Method)
08-19 17:55:29.106  6832  6832 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-19 17:55:29.106  6832  6832 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-19 17:55:29.106  6832  6832 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
08-19 17:55:29.106  6832  6832 D AndroidRuntime: Shutting down VM
08-19 17:55:29.106  6832  6832 E AndroidRuntime: FATAL EXCEPTION: main
08-19 17:55:29.106  6832  6832 E AndroidRuntime: Process: com.sec.pcw.device, PID: 6832
08-19 17:55:29.106  6832  6832 E AndroidRuntime: java.lang.RuntimeException: Unable to get provider com.sec.pcw.device.contentprovider.DMProvider: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-19 17:55:29.106  6832  6832 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5705)
08-19 17:55:29.106  6832  6832 E AndroidRuntime: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:5297)
08-19 17:55:29.106  6832  6832 E AndroidRuntime: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5237)
08-19 17:55:29.106  6832  6832 E AndroidRuntime: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
08-19 17:55:29.106  6832  6832 E AndroidRuntime: 	,at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
08-19 17:55:29.106  6832  6832 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-19 17:55:29.106  6832  6832 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:145)
08-19 17:55:29.106  6832  6832 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-19 17:55:29.106  6832  6832 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
08-19 17:55:29.106  6832  6832 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-19 17:55:29.106  6832  6832 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-19 17:55:29.106  6832  6832 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
08-19 17:55:29.106  6832  6832 E AndroidRuntime: Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-19 17:55:29.106  6832  6832 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-19 17:55:29.106  6832  6832 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
08-19 17:55:29.106  6832  6832 E AndroidRuntime: 	,at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228),
08-19 17:55:29.106  6832  6832 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
08-19 17:55:29.106  6832  6832 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
08-19 17:55:29.106  6832  6832 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
08-19 17:55:29.106  6832  6832 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
08-19 17:55:29.106  6832  6832 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
08-19 17:55:29.106  6832  6832 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699),
08-19 17:55:29.106  6832  6832 E AndroidRuntime: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1519)
08-19 17:55:29.106  6832  6832 E AndroidRuntime: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
08-19 17:55:29.106  6832  6832 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-19 17:55:29.106  6832  6832 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-19 17:55:29.106  6832  6832 E AndroidRuntime: 	at com.sec.pcw.device.contentprovider.DMProvider.onCreate(DMProvider.java:32)
08-19 17:55:29.106  6832  6832 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1729),
08-19 17:55:29.106  6832  6832 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1698)
08-19 17:55:29.106  6832  6832 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5702)
08-19 17:55:29.106  6832  6832 E AndroidRuntime: 	... 11 more
08-19 17:55:29.116  6178  6819 E SQLiteLog: (10) POSIX Error : 9 SQLite Error : 3850
08-19 17:55:29.116  6178  6819 E SQLiteLog: (3850) statement aborts at 22: [INSERT INTO system_env_info(name,value) VALUES (?,?)] disk I/O error
08-19 17:55:29.116  6178  6819 E SQLiteDatabase: Error inserting name=UT enabled value=false
08-19 17:55:29.116  6178  6819 E SQLiteDatabase: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
08-19 17:55:29.116  6178  6819 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForLastInsertedRowId(Native Method)
08-19 17:55:29.116  6178  6819 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.executeForLastInsertedRowId(SQLiteConnection.java:952)
08-19 17:55:29.116  6178  6819 E SQLiteDatabase: 	at android.database.sqlite.SQLiteSession.executeForLastInsertedRowId(SQLiteSession.java:788)
08-19 17:55:29.116  6178  6819 E SQLiteDatabase: 	at android.database.sqlite.SQLiteStatement.executeInsert(SQLiteStatement.java:86)
08-19 17:55:29.116  6178  6819 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.insertWithOnConflict(SQLiteDatabase.java:1609)
08-19 17:55:29.116  6178  6819 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.insert(SQLiteDatabase.java:1479)
08-19 17:55:29.116  6178  6819 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.f$b.a(DataStore.java:2487)
08-19 17:55:29.116  6178  6819 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.f.b(DataStore.java:1740)
08-19 17:55:29.116  6178  6819 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.i.g(LowpowerContextEngine.java:212)
08-19 17:55:29.116  6178  6819 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.i.e(LowpowerContextEngine.java:152)
08-19 17:55:29.116  6178  6819 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.i.<init>(LowpowerContextEngine.java:100)
08-19 17:55:29.116  6178  6819 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.i.a(LowpowerContextEngine.java:106)
08-19 17:55:29.116  6178  6819 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.LowpowerContextReceiver$SystemBroadcastReceiver.b(LowpowerContextReceiver.java:133)
08-19 17:55:29.116  6178  6819 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.LowpowerContextReceiver$SystemBroadcastReceiver.a(LowpowerContextReceiver.java:102)
08-19 17:55:29.116  6178  6819 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.LowpowerContextReceiver$SystemBroadcastReceiver.a(LowpowerContextReceiver.java:42),
08-19 17:55:29.116  6178  6819 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.q.run(LowpowerContextReceiver.java:52)
08-19 17:55:29.116  6178  6819 E SQLiteDatabase: 	at android.os.Handler.handleCallback(Handler.java:739)
08-19 17:55:29.116  6178  6819 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-19 17:55:29.116  6178  6819 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:145)
08-19 17:55:29.116  6178  6819 E SQLiteDatabase: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-19 17:55:29.116  6178  6819 E SQLiteLog: (10) POSIX Error : 9 SQLite Error : 3850
08-19 17:55:29.116  6178  6819 E SQLiteLog: (3850) statement aborts at 22: [INSERT INTO system_env_info(name,value) VALUES (?,?)] disk I/O error
08-19 17:55:29.116  6178  6819 E SQLiteDatabase: Error inserting name=AFP Enabled value=true
08-19 17:55:29.116  6178  6819 E SQLiteDatabase: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
08-19 17:55:29.116  6178  6819 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForLastInsertedRowId(Native Method)
08-19 17:55:29.116  6178  6819 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.executeForLastInsertedRowId(SQLiteConnection.java:952)
08-19 17:55:29.116  6178  6819 E SQLiteDatabase: 	at android.database.sqlite.SQLiteSession.executeForLastInsertedRowId(SQLiteSession.java:788)
08-19 17:55:29.116  6178  6819 E SQLiteDatabase: 	at android.database.sqlite.SQLiteStatement.executeInsert(SQLiteStatement.java:86)
08-19 17:55:29.116  6178  6819 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.insertWithOnConflict(SQLiteDatabase.java:1609)
08-19 17:55:29.116  6178  6819 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.insert(SQLiteDatabase.java:1479)
08-19 17:55:29.116  6178  6819 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.f$b.a(DataStore.java:2487)
08-19 17:55:29.116  6178  6819 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.f.b(DataStore.java:1740)
08-19 17:55:29.116  6178  6819 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.i.g(LowpowerContextEngine.java:213)
08-19 17:55:29.116  6178  6819 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.i.e(LowpowerContextEngine.java:152)
08-19 17:55:29.116  6178  6819 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.i.<init>(LowpowerContextEngine.java:100)
08-19 17:55:29.116  6178  6819 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.i.a(LowpowerContextEngine.java:106)
08-19 17:55:29.116  6178  6819 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.LowpowerContextReceiver$SystemBroadcastReceiver.b(LowpowerContextReceiver.java:133)
08-19 17:55:29.116  6178  6819 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.LowpowerContextReceiver$SystemBroadcastReceiver.a(LowpowerContextReceiver.java:102)
08-19 17:55:29.116  6178  6819 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.LowpowerContextReceiver$SystemBroadcastReceiver.a(LowpowerContextReceiver.java:42)
08-19 17:55:29.116  6178  6819 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.q.run(LowpowerContextReceiver.java:52)
08-19 17:55:29.116  6178  6819 E SQLiteDatabase: 	at android.os.Handler.handleCallback(Handler.java:739)
08-19 17:55:29.116  6178  6819 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-19 17:55:29.116  6178  6819 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:145)
08-19 17:55:29.116  6178  6819 E SQLiteDatabase: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-19 17:55:29.116  6178  6819 E SQLiteLog: (10) POSIX Error : 9 SQLite Error : 3850
08-19 17:55:29.116  6178  6819 E SQLiteLog: (3850) statement aborts at 22: [INSERT INTO system_env_info(name,value) VALUES (?,?)] disk I/O error
08-19 17:55:29.116  6178  6819 E SQLiteDatabase: Error inserting name=SleepDetection Enabled value=,false
08-19 17:55:29.116  6178  6819 E SQLiteDatabase: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
08-19 17:55:29.116  6178  6819 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForLastInsertedRowId(Native Method)
08-19 17:55:29.116  6178  6819 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.executeForLastInsertedRowId(SQLiteConnection.java:952)
08-19 17:55:29.116  6178  6819 E SQLiteDatabase: 	at android.database.sqlite.SQLiteSession.executeForLastInsertedRowId(SQLiteSession.java:788)
08-19 17:55:29.116  6178  6819 E SQLiteDatabase: 	at android.database.sqlite.SQLiteStatement.executeInsert(SQLiteStatement.java:86)
08-19 17:55:29.116  6178  6819 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.insertWithOnConflict(SQLiteDatabase.java:1609)
08-19 17:55:29.116  6178  6819 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.insert(SQLiteDatabase.java:1479)
08-19 17:55:29.116  6178  6819 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.f$b.a(DataStore.java:2487)
08-19 17:55:29.116  6178  6819 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.f.b(DataStore.java:1740)
08-19 17:55:29.116  6178  6819 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.i.g(LowpowerContextEngine.java:214)
08-19 17:55:29.116  6178  6819 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.i.e(LowpowerContextEngine.java:152)
08-19 17:55:29.116  6178  6819 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.i.<init>(LowpowerContextEngine.java:100)
08-19 17:55:29.116  6178  6819 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.i.a(LowpowerContextEngine.java:106)
08-19 17:55:29.116  6178  6819 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.LowpowerContextReceiver$SystemBroadcastReceiver.b(LowpowerContextReceiver.java:133)
08-19 17:55:29.116  6178  6819 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.LowpowerContextReceiver$SystemBroadcastReceiver.a(LowpowerContextReceiver.java:102)
08-19 17:55:29.116  6178  6819 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.LowpowerContextReceiver$SystemBroadcastReceiver.a(LowpowerContextReceiver.java:42)
08-19 17:55:29.116  6178  6819 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.q.run(LowpowerContextReceiver.java:52)
08-19 17:55:29.116  6178  6819 E SQLiteDatabase: 	at android.os.Handler.handleCallback(Handler.java:739)
08-19 17:55:29.116  6178  6819 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-19 17:55:29.116  6178  6819 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:145)
08-19 17:55:29.116  6178  6819 E SQLiteDatabase: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-19 17:55:29.116  6178  6819 E SQLiteLog: (10) POSIX Error : 9 SQLite Error : 3850
08-19 17:55:29.116  6178  6819 E SQLiteLog: (3850) statement aborts at 22: [INSERT INTO system_env_info(name,value) VALUES (?,?)] disk I/O error
08-19 17:55:29.126  6178  6819 E SQLiteDatabase: Error inserting name=System Build Version Release value=5.0.2
08-19 17:55:29.126  6178  6819 E SQLiteDatabase: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
08-19 17:55:29.126  6178  6819 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForLastInsertedRowId(Native Method)
08-19 17:55:29.126  6178  6819 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.executeForLastInsertedRowId(SQLiteConnection.java:952)
08-19 17:55:29.126  6178  6819 E SQLiteDatabase: 	at android.database.sqlite.SQLiteSession.executeForLastInsertedRowId(SQLiteSession.java:788)
08-19 17:55:29.126  6178  6819 E SQLiteDatabase: 	at android.database.sqlite.SQLiteStatement.executeInsert(SQLiteStatement.java:86)
08-19 17:55:29.126  6178  6819 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.insertWithOnConflict(SQLiteDatabase.java:1609)
08-19 17:55:29.126  6178  ,6819 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.insert(SQLiteDatabase.java:1479)
08-19 17:55:29.126  6178  6819 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.f$b.a(DataStore.java:2487)
08-19 17:55:29.126  6178  6819 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.f.b(DataStore.java:1740)
08-19 17:55:29.126  6178  6819 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.i.g(LowpowerContextEngine.java:215)
08-19 17:55:29.126  6178  6819 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.i.e(LowpowerContextEngine.java:152)
08-19 17:55:29.126  6178  6819 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.i.<init>(LowpowerContextEngine.java:100)
08-19 17:55:29.126  6178  6819 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.i.a(LowpowerContextEngine.java:106)
08-19 17:55:29.126  6178  6819 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.LowpowerContextReceiver$SystemBroadcastReceiver.b(LowpowerContextReceiver.java:133)
08-19 17:55:29.126  6178  6819 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.LowpowerContextReceiver$SystemBroadcastReceiver.a(LowpowerContextReceiver.java:102)
08-19 17:55:29.126  6178  6819 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.LowpowerContextReceiver$SystemBroadcastReceiver.a(LowpowerContextReceiver.java:42)
08-19 17:55:29.126  6178  6819 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.q.run(LowpowerContextReceiver.java:52)
08-19 17:55:29.126  6178  6819 E SQLiteDatabase: 	at android.os.Handler.handleCallback(Handler.java:739)
08-19 17:55:29.126  6178  6819 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-19 17:55:29.126  6178  6819 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:145)
08-19 17:55:29.126  6178  6819 E SQLiteDatabase: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-19 17:55:29.126  6178  6819 E SQLiteLog: (10) POSIX Error : 9 SQLite Error : 3850
08-19 17:55:29.126  6178  6819 E SQLiteLog: (3850) statement aborts at 22: [INSERT INTO system_env_info(name,value) VALUES (?,?)] disk I/O error
08-19 17:55:29.126  6178  6819 E SQLiteDatabase: Error inserting name=status value=successfully initialized
08-19 17:55:29.126  6178  6819 E SQLiteDatabase: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
08-19 17:55:29.126  6178  6819 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForLastInsertedRowId(Native Method)
08-19 17:55:29.126  6178  6819 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.executeForLastInsertedRowId(SQLiteConnection.java:952)
08-19 17:55:29.126  6178  6819 E SQLiteDatabase: 	at android.database.sqlite.SQLiteSession.executeForLastInsertedRowId(SQLiteSession.java:788)
08-19 17:55:29.126  6178  6819 E SQLiteDatabase: 	at android.database.sqlite.SQLiteStatement.executeInsert(SQLiteStatement.java:86)
08-19 17:55:29.126  6178  6819 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.insertWithOnConflict(SQLiteDatabase.java:1609)
08-19 17:55:29.126  6178  6819 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.insert(SQLiteDatabase.java:1479)
08-19 17:55:29.126  6178  6819 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.f$b.a(DataStore.java:2487)
08-19 17:55:29.126  6178  6819 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.f.b(DataStore.java:1740)
08-19 17:55:29.126  6178  6819 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.i.g(LowpowerContextEngine.java:216)
08-19 17:55:29.126  6178  6819 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.i.e(LowpowerContextEngine.java:152)
08-19 17:55:29.126  6178  6819 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.i.<init>(LowpowerContextEngine.java:100)
08-19 17:55:29.126  6178  6819 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.i.a(LowpowerContextEngine.java:106)
08-19 17:55:29.126  6178  6819 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.LowpowerContextReceiver$SystemBroadcastReceiver.b(LowpowerContextReceiver.java:133)
08-19 17:55:29.126  6178  6819 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.LowpowerContextReceiver$SystemBroadcastReceiver.a(LowpowerContextReceiver.java:102)
08-19 17:55:29.126  6178  6819 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.LowpowerContextReceiver$SystemBroadcastReceiver.a(LowpowerContextReceiver.java:42)
08-19 17:55:29.126  6178  6819 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.q.run(LowpowerContextReceiver.java:52)
08-19 17:55:29.126  6178  6819 E SQLiteDatabase: 	at android.os.Handler.handleCallback(Handler.java:739)
08-19 17:55:29.126  6178  6819 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-19 17:55:29.126  6178  6819 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:145)
08-19 17:55:29.126  6178  6819 E SQLiteDatabase: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-19 17:55:29.126  1015  1446 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.sec.pcw.device
08-19 17:55:29.126  1015  1040 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.app.galaxyfinder, hostingType: broadcast
08-19 17:55:29.126  4129  6849 I GCore-Chimera-Crash: Cg0KB3ZJbmZyYTQQstg5Gl8KHWNvbS5nb29nbGUuYW5kcm9pZC
08-19 17:55:29.126  4129  6849 I GCore-Chimera-Crash: 5wbGF5LmdhbWVzEhQzLjcuMjQgKDMwNTE3NzQtMDM0KRji-eAR
08-19 17:55:29.126  4129  6849 I GCore-Chimera-Crash: IiMKHGNvbS5nb29nbGUuYW5kcm9pZC5nbXMuZ2FtZXMQwPngEQ
08-19 17:55:29.126  4129  6849 I GCore-Chimera-Crash: ==
08-19 17:55:29.126  4129  6849 I GCore-Chimera-Crash: GCore-Chimera-Crash
08-19 17:55:29.126  4129  6849 I DeviceDoctorDatabaseHelper: Cleaning stale data from database!
08-19 17:55:29.136  4129  6849 E SQLiteLog: (28) failed to open "/data/data/com.google.android.gms/databases/com.google.android.gms.devicedoctor.db" with flag (131138) and mode_t (0) due to error (30)
08-19 17:55:29.136  4129  6849 E SQLiteLog: (28) failed to open "/data/data/com.google.android.gms/databases/com.google.android.gms.devicedoctor.db" with flag (131072) and mode_t (0) due to error (2)
08-19 17:55:29.136  4129  6849 E SQLiteLog: (14) cannot open file at line 32510 of [b3bb660af9]
08-19 17:55:29.136  4129  6849 E SQLiteLog: (14) os_unix.c:32510: (2) open(/data/data/com.google.android.gms/databases/com.google.android.gms.devicedoctor.db) - 
08-19 17:55:29.136  1015  1040 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-19 17:55:29.136  1015  1040 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-19 17:55:29.136  1015  1040 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-19 17:55:29.136  1015  1040 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-19 17:55:29.136  1015  3485 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
08-19 17:55:29.146  1015  3485 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4308, temperature: 282, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
08-19 17:55:29.146  1015  3485 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
08-19 17:55:29.146  1015  3485 D BatteryService: stay LED for fully charged
08-19 17:55:29.146  1015  1015 D BatteryService: Sending ACTION_BATTERY_CHANGED.
08-19 17:55:29.146  6822  6822 D TapandpayWidget:TapandpayAppWidgetProvider: Widget is not attached.
08-19 17:55:29.146  1015  6858 E DropBoxManagerService: Can't write: system_app_crash
08-19 17:55:29.146  1015  6858 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop188.tmp: open failed: EROFS (Read-only file system)
08-19 17:55:29.146  1015  6858 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:456)
08-19 17:55:29.146  1015  6858 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-19 17:55:29.146  1015  6858 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-19 17:55:29.146  1015  6858 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-19 17:55:29.146  1015  6858 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:269)
08-19 17:55:29.146  1015  6858 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$24.run(ActivityManagerService.java:15780)
08-19 17:55:29.146  1015  6858 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-19 17:55:29.146  1015  6858 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-19 17:55:29.146  1015  6858 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-19 17:55:29.146  1015  6858 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:442)
08-19 17:55:29.146  1015  6858 E DropBoxManagerService: 	... 5 more
08-19 17:55:29.146  6859  6859 E Zygote  : MountEmulatedStorage()
08-19 17:55:29.146  6859  6859 E Zygote  : v2
08-19 17:55:29.146  6859  6859 I libpersona: KNOX_SDCARD checking this for 10029
08-19 17:55:29.146  6859  6859 I libpersona: KNOX_SDCARD not a persona
08-19 17:55:29.146  4129  6849 E SQLiteDatabase: Failed to open database '/data/data/com.google.android.gms/databases/com.google.android.gms.devicedoctor.db'.
08-19 17:55:29.146  4129  6849 E SQLiteDatabase: android.database.sqlite.SQLiteCantOpenDatabaseException: unknown error (code 14): Could not open database
08-19 17:55:29.146  4129  6849 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-19 17:55:29.146  4129  6849 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
08-19 17:55:29.146  4129  6849 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
08-19 17:55:29.146  4129  6849 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
08-19 17:55:29.146  4129  6849 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
08-19 17:55:29.146  4129  6849 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
08-19 17:55:29.146  4129  6849 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
08-19 17:55:29.146  4129  6849 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
08-19 17:55:29.146  4129  6849 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
08-19 17:55:29.146  4129  6849 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1519)
08-19 17:55:29.146  4129  6849 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1508)
08-19 17:55:29.146  4129  6849 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:276)
08-19 17:55:29.146  4129  6849 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:276)
08-19 17:55:29.146  4129  6849 E SQLiteDatabase: 	at ivm.g(:com.google.android.gms:204)
08-19 17:55:29.146  4129  6849 E SQLiteDatabase: 	at ivm.e(:com.google.android.gms:176)
08-19 17:55:29.146  4129  6849 E SQLiteDatabase: 	at ivh.a(:com.google.android.gms:22519)
08-19 17:55:29.146  4129  6849 E SQLiteDatabase: 	at iiq.c(:com.google.android.gms:207)
08-19 17:55:29.146  4129  6849 E SQLiteDatabase: 	at ifm.uncaughtException(:com.google.android.gms:2111)
08-19 17:55:29.146  4129  6849 E SQLiteDatabase: 	at ifs.uncaughtException(:com.google.android.gms:54)
08-19 17:55:29.146  4129  6849 E SQLiteDatabase: 	at ifl.uncaughtException(:com.google.android.gms:62)
08-19 17:55:29.146  4129  6849 E SQLiteDatabase: 	at java.lang.ThreadGroup.uncaughtException(ThreadGroup.java:693)
08-19 17:55:29.146  4129  6849 E SQLiteDatabase: 	at java.lang.ThreadGroup.uncaughtException(ThreadGroup.java:690)
08-19 17:55:29.156  6859  6859 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
08-19 17:55:29.156  6859  6859 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
08-19 17:55:29.156  6859  6859 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
08-19 17:55:29.156  1015  1040 I ActivityManager: Start proc com.samsung.android.app.galaxyfinder for broadcast com.samsung.android.app.galaxyfinder/.ApplicationStatusReceiver: pid=6859 uid=10029 gids={50029, 9997, 1028, 1015, 3003, 3002} abi=armeabi-v7a
08-19 17:55:29.156  6832  6832 I Process : Sending signal. PID: 6832 SIG: 9

```
