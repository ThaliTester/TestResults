#### Test 83627337381d561_thali05_samsung-SM-T719 Logs


```
--------- beginning of system
09-07 11:36:47.738  1250  3581 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:836 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,--------- beginning of main
09-07 11:36:48.188  5980  5980 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
09-07 11:36:48.188  5980  5980 D AndroidRuntime: CheckJNI is OFF
09-07 11:36:48.188  5980  5980 D AndroidRuntime: readGMSProperty: start
09-07 11:36:48.188  5980  5980 D AndroidRuntime: readGMSProperty: already setted!!
09-07 11:36:48.188  5980  5980 D AndroidRuntime: propertySet: couldn't set property (it is from app)
09-07 11:36:48.188  5980  5980 D AndroidRuntime: readGMSProperty: could not set the property(default)!!
09-07 11:36:48.188  5980  5980 D AndroidRuntime: readGMSProperty: end
09-07 11:36:48.188  5980  5980 D AndroidRuntime: addProductProperty: start
09-07 11:36:48.208  5980  5980 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
09-07 11:36:48.248  5980  5980 I Radio-JNI: register_android_hardware_Radio DONE
09-07 11:36:48.248  5980  5980 E AffinityControl: AffinityControl: registerfunction enter
09-07 11:36:48.258  5980  5980 D AndroidRuntime: Calling main entry com.android.commands.am.Am
09-07 11:36:48.288  1250  2396 D VirtualScreenPolicy: applyVirtualScreenAttrs attrs=VirtualScreenAttrs{mDisplayId=0, mBaseDisplayId=0, mBaseActivity=false}
09-07 11:36:48.308  1250  2396 D GameManagerService: identifyGamePackage. com.test.thalitest
09-07 11:36:48.308  1250  2396 D MultiWindowPolicy: Gamemode - return 0,  when calling  identifyForegroundApp(com.test.thalitest)
09-07 11:36:48.308  1250  2396 D ActivityManager: mDVFSHelper.acquire()
09-07 11:36:48.318  1250  2396 V WindowManager: addAppToken: AppWindowToken{d02d5024d token=Token{3433de4 ActivityRecord{1935d77 u0 com.test.thalitest/.MainActivity t19}}} to stack=2 task=19 at 0
09-07 11:36:48.318  1250  1417 D ViewRootImpl: #1 mView = com.android.internal.policy.PhoneWindow$DecorView{70d2e05 V.E...... R.....ID 0,0-0,0}
09-07 11:36:48.318  1250  1417 D SecWifiDisplayUtil: Metadata value : SecSettings2
09-07 11:36:48.328  1250  2396 I ActivityManager: Start proc 5989:com.test.thalitest/u0a136 for activity com.test.thalitest/.MainActivity
09-07 11:36:48.328  5989  5989 E Zygote  : v2
09-07 11:36:48.328  5989  5989 I libpersona: KNOX_SDCARD checking this for 10136
09-07 11:36:48.328  5989  5989 I libpersona: KNOX_SDCARD not a persona
09-07 11:36:48.328  1250  2396 D InputDispatcher: Focused application set to: xxxx
09-07 11:36:48.328  5989  5989 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0013
09-07 11:36:48.338  1250  1621 D NetworkPolicy: isUidForegroundLocked: 10136, mScreenOn: false, uidstate: -1, mProxSensorScreenOff: false
09-07 11:36:48.338  5989  5989 E Zygote  : accessInfo : 0
09-07 11:36:48.338  5980  5980 D AndroidRuntime: Shutting down VM
09-07 11:36:48.338  5989  5989 W SELinux : SELinux: seapp_context_lookup: seinfo=default, level=s0:c512,c768, pkgname=com.test.thalitest 
09-07 11:36:48.338   445   445 I SurfaceFlinger: id=18 createSurf (1x1),1 flag=404, uhalitest
09-07 11:36:48.348  3774  3774 D ViewRootImpl: MSG_RESIZED_REPORT: ci=Rect(0, 0 - 0, 0) vi=Rect(0, 0 - 0, 0) or=1
09-07 11:36:48.348  3774  3774 D ViewRootImpl: MSG_RESIZED_REPORT: ci=Rect(0, 0 - 0, 0) vi=Rect(0, 0 - 0, 0) or=1
09-07 11:36:48.348  3774  3785 V ViewRootImpl: dispatchResized mReportNextDraw cancel... mWinFrame : Rect(256, 1016 - 1280, 1080)  frame : Rect(256, 992 - 1280, 1056) window com.samsung.android.MtpApplication/com.samsung.android.MtpApplication.USBConnection
09-07 11:36:48.348  3774  3785 V ViewRootImpl: dispatchResized mReportNextDraw cancel... mWinFrame : Rect(256, 461 - 1280, 1634)  frame : Rect(256, 437 - 1280, 1610) window com.samsung.android.MtpApplication/com.samsung.android.MtpApplication.USBConnection
09-07 11:36:48.358  1250  1417 D KnoxTimeoutHandler: notifyActivityDrawn [MsgParam] userId: 0 fullscreen is false showWhenlocked is false
09-07 11:36:48.358  1250  1417 D ViewRootImpl: MSG_RESIZED_REPORT: ci=Rect(0, 48 - 0, 0) vi=Rect(0, 48 - 0, 0) or=1
09-07 11:36:48.358  1250  1250 D KnoxTimeoutHandler: activityDrawn [MsgParam] userId: 0 fullscreen is false showWhenlocked is false
09-07 11:36:48.358  1250  1250 I KnoxTimeoutHandler: SD activityfalse
09-07 11:36:48.358  5989  5989 D TimaKeyStoreProvider: TimaSignature is unavailable
09-07 11:36:48.358  5989  5989 D ActivityThread: Added TimaKeyStore provider
09-07 11:36:48.368  1250  1720 D ActivityManager:  Launching com.test.thalitest, updated priority
09-07 11:36:48.368  1971  1971 V ActivityThread: updateVisibility : ActivityRecord{f4a80e6 token=android.os.BinderProxy@aa8634d {com.sec.android.app.launcher/com.sec.android.app.launcher.activities.LauncherActivity}} show : false
09-07 11:36:48.368  1250  1378 V MARsPolicyManager: updatePackagesScore PackageInfo name -- com.test.thalitest
09-07 11:36:48.368  1250  1250 D GameManagerService: NotifyRunnable. pkg: com.test.thalitest, type: 4, isMinimized: false, isTunableApp: false
09-07 11:36:48.378  3774  3774 D ViewRootImpl: MSG_RESIZED_REPORT: ci=Rect(0, 0 - 0, 0) vi=Rect(0, 0 - 0, 0) or=1
09-07 11:36:48.378  3774  3774 V ActivityThread: updateVisibility : ActivityRecord{8f25f46 token=android.os.BinderProxy@65eeb38 {com.samsung.android.MtpApplication/com.samsung.android.MtpApplication.USBConnection}} show : false
09-07 11:36:48.378  3774  3774 D ViewRootImpl: MSG_RESIZED_REPORT: ci=Rect(0, 0 - 0, 0) vi=Rect(0, 0 - 0, 0) or=1
09-07 11:36:48.388   445   466 I SurfaceFlinger: id=9 Removed MauncherAct (5/14)
09-07 11:36:48.388   445  1927 I SurfaceFlinger: id=9 Removed MauncherAct (-2/14)
09-07 11:36:48.398  1971  1971 D Launcher: onTrimMemory. Level: 20
09-07 11:36:48.398  1250  1417 V WindowStateAnimator: Finishing drawing window Window{f1cf88b u0 d0 Starting com.test.thalitest}: mDrawState=DRAW_PENDING
09-07 11:36:48.418   445   468 I SurfaceFlinger: id=17 Removed VSBConnecti (6/13)
09-07 11:36:48.418   445   466 I SurfaceFlinger: id=17 Removed VSBConnecti (-2/13)
09-07 11:36:48.428   445   468 I SurfaceFlinger: id=16 Removed VSBConnecti (6/12)
09-07 11:36:48.428   445   466 I SurfaceFlinger: id=16 Removed VSBConnecti (-2/12)
,09-07 11:36:48.678  1250  1720 I WindowManager: Screenshot max retries 4 of Token{3433de4 ActivityRecord{1935d77 u0 com.test.thalitest/.MainActivity t19}} appWin=Window{f1cf88b u0 d0 Starting com.test.thalitest} drawState=4
,09-07 11:36:48.678  1250  1621 D NetworkPolicy: isUidForegroundLocked: 10136, mScreenOn: false, uidstate: 5, mProxSensorScreenOff: false
,09-07 11:36:48.698  1250  3553 D GameManagerService: identifyGamePackage. com.test.thalitest
,09-07 11:36:48.698  1250  3553 D GameManagerService: identifyGamePackage. com.test.thalitest
,09-07 11:36:48.728  1250  2396 W ActivityManager: Permission Denial: getCurrentUser() from pid=5989, uid=10136 requires android.permission.INTERACT_ACROSS_USERS
,09-07 11:36:48.738  5989  5989 D ContextRelationManager: ContextRelationManager() : FEATURE_ENABLED=true
,09-07 11:36:48.738  5989  5989 D RelationGraph: garbageCollect()
,09-07 11:36:48.758  1250  1313 W ActivityManager: Permission Denial: getCurrentUser() from pid=5989, uid=10136 requires android.permission.INTERACT_ACROSS_USERS
,09-07 11:36:48.768  5989  5989 I WebViewFactory: Loading com.google.android.webview version 49.0.2623.105 (code 262310550)
,09-07 11:36:48.798  5989  5989 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
,09-07 11:36:48.828  5989  5989 I cr_LibraryLoader: Time to load native libraries: 11 ms (timestamps 2232-2243)
,09-07 11:36:48.828  5989  5989 I cr_LibraryLoader: Expected native library version number "49.0.2623.105", actual native library version number "49.0.2623.105"
,09-07 11:36:48.848  5989  6004 W System.err: remove failed: ENOENT (No such file or directory) : /data/user/0/com.test.thalitest/shared_prefs/WebViewChromiumPrefs.xml.bak
09-07 11:36:48.858  5989  5989 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {c11cc52}
09-07 11:36:48.858  5989  5989 I cr_LibraryLoader: Expected native library version number "49.0.2623.105", actual native library version number "49.0.2623.105"
,09-07 11:36:48.868  5989  5989 I chromium: [INFO:library_loader_hooks.cc(144)] Chromium logging enabled: level = 0, default verbosity = 0
,09-07 11:36:48.888  5989  5989 I cr_BrowserStartup: Initializing chromium process, singleProcess=true
,09-07 11:36:48.958  5989  5989 I Adreno  : QUALCOMM build                   : 971aff5, Ic07f1cdce3
09-07 11:36:48.958  5989  5989 I Adreno  : Build Date                       : 03/29/16
09-07 11:36:48.958  5989  5989 I Adreno  : OpenGL ES Shader Compiler Version: XE031.06.00.02
09-07 11:36:48.958  5989  5989 I Adreno  : Local Branch                     : 
09-07 11:36:48.958  5989  5989 I Adreno  : Remote Branch                    : refs/tags/AU_LINUX_ANDROID_LA.BR.1.3.3.C2.06.00.01.205.077
09-07 11:36:48.958  5989  5989 I Adreno  : Remote Branch                    : NONE
09-07 11:36:48.958  5989  5989 I Adreno  : Reconstruct Branch               : NOTHING
,09-07 11:36:49.018  1250  2396 D ActivityManager: The following uid has registered to recieve broadcast for proxy related updates 10136
,09-07 11:36:49.018  1250  2396 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:851 com.android.server.am.ActivityManagerService.requestKnoxVpnToSendProxyBroadcast:29617 com.android.server.am.ActivityManagerService.registerReceiver:22639 android.app.ActivityManagerNative.onTransact:431 com.android.server.am.ActivityManagerService.onTransact:3995 
,09-07 11:36:49.088  5989  5989 D cr_Ime  : [InputMethodManagerWrapper.java:27] Constructor
,09-07 11:36:49.098  5989  5989 W cr_AwContents: onDetachedFromWindow called when already detached. Ignoring
,09-07 11:36:49.098  5989  5989 D cr_Ime  : [InputMethodManagerWrapper.java:56] isActive: false
,09-07 11:36:49.118  5989  5989 D SystemWebViewEngine: CordovaWebView is running on device made by: samsung
,09-07 11:36:49.158  5989  5989 D SecWifiDisplayUtil: Metadata value : SecSettings2
,09-07 11:36:49.158  5989  5989 D ViewRootImpl: #1 mView = com.android.internal.policy.PhoneWindow$DecorView{6aaf703 I.E...... R.....ID 0,0-0,0}
,09-07 11:36:49.158  5989  6028 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
,09-07 11:36:49.168  1250  1994 D ActivityManager: post active user change for 0 fullscreen true isFloatingActivity() false isHomeActivity() false
09-07 11:36:49.168  1250  1994 D KnoxTimeoutHandler: postActiveUserChange [MsgParam] userId: 0 fullscreen is true showWhenlocked is false
,09-07 11:36:49.168  1250  1250 D KnoxTimeoutHandler: handleActiveUserChange [MsgParam] userId: 0 fullscreen is true showWhenlocked is false
,09-07 11:36:49.168  1250  1250 I KnoxTimeoutHandler: Shared devices show user statefalse
,09-07 11:36:49.178  5989  6004 W System.err: remove failed: ENOENT (No such file or directory) : /data/user/0/com.test.thalitest/shared_prefs/com.test.thalitest_preferences.xml.bak
,09-07 11:36:49.188  5989  5989 D ConnectivityManager: requestNetwork; getAppId(CallingUid) : 10136, CallingPid : 5989
,09-07 11:36:49.188  1250  2396 D ConnectivityService: listenForNetwork for Listen from uid/pid:10136/5989 for NetworkRequest [ id=7, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-07 11:36:49.188  1250  1630 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 502]
09-07 11:36:49.188  1250  1630 D ConnectivityService:  network has: NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{502}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.106/24,fe80::4678:3eff:feeb:95ef/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains:  MTU: 0 TcpBufferSizes: 524288,1048576,1048576,524288,1048576,4194240}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN&VALIDATED LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -39]}  Score{60}  everValidated{true}  lastValidated{true}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
09-07 11:36:49.188  1250  1630 D ConnectivityService: Network NetworkAgentInfo [WIFI () - 502] was already satisfying request 1. No change.
09-07 11:36:49.188  1250  1630 D ConnectivityService:   checking if request is: NetworkRequest [ id=4, legacyType=-1, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] satisfies: true nri.isRequest: false
09-07 11:36:49.188  1250  1630 D ConnectivityService:   checking if request is: NetworkRequest [ id=7, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] satisfies: true nri.isRequest: false
09-07 11:36:49.188  1250  1630 D ConnectivityService:   checking if request is: NetworkRequest [ id=3, legacyType=-1, [ Transports: CELLULAR Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] satisfies: false nri.isRequest: false
09-07 11:36:49.188  1250  1630 D ConnectivityService:   checking if request is: NetworkRequest [ id=6, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] satisfies: true nri.isRequest: false
09-07 11:36:49.188  1250  1630 D ConnectivityService:   checking if request is: NetworkRequest [ id=5, legacyType=-1, [] ] satisfies: true nri.isRequest: false
09-07 11:36:49.188  1250  1630 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=7, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,09-07 11:36:49.208  5989  5989 D SecWifiDisplayUtil: Metadata value : SecSettings2
,09-07 11:36:49.218   445   445 I SurfaceFlinger: id=19 createSurf (1x1),1 flag=404, NainActivit
,09-07 11:36:49.238  5989  6028 I OpenGLRenderer: Initialized EGL, version 1.4
,09-07 11:36:49.248  5989  5989 V ActivityThread: updateVisibility : ActivityRecord{2b92f0a token=android.os.BinderProxy@d9153a1 {com.test.thalitest/com.test.thalitest.MainActivity}} show : true
,09-07 11:36:49.288  5989  6028 E libGLESv2: HWUI Protection: wrong call from hwui context F: ES3-glCreateProgramSEC
,09-07 11:36:49.328  1250  2327 V WindowStateAnimator: Finishing drawing window Window{6e8afc8 u0 d0 com.test.thalitest/com.test.thalitest.MainActivity}: mDrawState=DRAW_PENDING
,09-07 11:36:49.328  5989  5989 D ViewRootImpl: MSG_RESIZED_REPORT: ci=Rect(0, 48 - 0, 0) vi=Rect(0, 48 - 0, 0) or=1
,09-07 11:36:49.328  1250  1417 D KnoxTimeoutHandler: notifyActivityDrawn [MsgParam] userId: 0 fullscreen is true showWhenlocked is false
09-07 11:36:49.328  1250  1417 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +654ms (total +1s17ms)
09-07 11:36:49.338  1250  1250 D KnoxTimeoutHandler: activityDrawn [MsgParam] userId: 0 fullscreen is true showWhenlocked is false
09-07 11:36:49.338  1250  1417 D ActivityManager: mDVFSHelper.release()
09-07 11:36:49.338  1250  1417 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{1935d77 u0 com.test.thalitest/.MainActivity t19} time:102750
09-07 11:36:49.338  1250  1417 D ViewRootImpl: #3 mView = null
,09-07 11:36:49.338   445  1927 I SurfaceFlinger: id=18 Removed uhalitest (6/12)
09-07 11:36:49.338  1250  1250 I KnoxTimeoutHandler: SD activityfalse
09-07 11:36:49.338  1250  1250 I KnoxTimeoutHandler: Fullscreen and mCurrent is not KNOX user. Hence hide keyguard
09-07 11:36:49.338   445   468 I SurfaceFlinger: id=18 Removed uhalitest (-2/12)
,09-07 11:36:49.338  5989  6033 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,09-07 11:36:49.348  1250  1990 V WindowStateAnimator: Finishing drawing window Window{6e8afc8 u0 d0 com.test.thalitest/com.test.thalitest.MainActivity}: mDrawState=HAS_DRAWN
,09-07 11:36:49.348  5989  5989 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@d9153a1 time:102764
,09-07 11:36:49.388  5989  5989 W cr_BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 5989
,09-07 11:36:49.558  5989  5989 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,09-07 11:36:49.678  5989  6039 D jxcore_app_log: JniHelper::setJavaVM(0xf4ffc000), pthread_self() = -618661584
,09-07 11:36:49.678  5989  6039 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
09-07 11:36:49.678  5989  6039 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
09-07 11:36:49.678  5989  6039 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
09-07 11:36:49.678  5989  6039 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
09-07 11:36:49.678  5989  6039 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
09-07 11:36:49.678  5989  6039 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@247a6f3 added. We now have 1 listener(s)
,09-07 11:36:49.678  5989  6039 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: 44:78:3E:EB:95:EE
,09-07 11:36:49.678  5989  6039 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "44:78:3E:EB:95:EE"
09-07 11:36:49.688  5989  6039 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-07 11:36:49.688  5989  6039 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,09-07 11:36:49.688  5989  6039 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
09-07 11:36:49.688  5989  6039 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
09-07 11:36:49.688  5989  6039 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
09-07 11:36:49.688  5989  6039 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: 44:78:3E:EB:95:EE
09-07 11:36:49.688  5989  6039 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
09-07 11:36:49.688  5989  6039 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
09-07 11:36:49.688  5989  6039 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
09-07 11:36:49.688  5989  6039 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
09-07 11:36:49.688  5989  6039 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
09-07 11:36:49.688  5989  6039 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
09-07 11:36:49.688  5989  6039 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
09-07 11:36:49.688  5989  6039 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
09-07 11:36:49.688  5989  6039 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
09-07 11:36:49.688  5989  6039 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
09-07 11:36:49.688  5989  6039 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6eea5ae added. We now have 1 listener(s)
09-07 11:36:49.688  5989  6039 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-07 11:36:49.688  5989  6039 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
09-07 11:36:49.688  5989  6039 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
09-07 11:36:49.688  5989  6039 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
09-07 11:36:49.688  5989  6039 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
09-07 11:36:49.688  5989  6039 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
,09-07 11:36:49.688  5989  6039 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-07 11:36:49.688  5989  6039 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 44:78:3E:EB:95:EE
,09-07 11:36:49.698  5989  6039 D BluetoothAdapter: STATE_ON
,09-07 11:36:49.698  5989  6039 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (SUPPORTED) in persistent storage
,09-07 11:36:49.698  5989  6039 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-07 11:36:49.698  5989  6039 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-07 11:36:49.698  5989  6039 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-07 11:36:49.698  5989  6039 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-07 11:36:49.698  5989  6039 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-07 11:36:49.698  5989  6039 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-07 11:36:49.698  5989  6039 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-07 11:36:49.698  5989  6039 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-07 11:36:49.698  5989  6039 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
09-07 11:36:49.698  5989  6039 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-07 11:36:49.698  5989  6039 I io.jxcore.node.LifeCycleMonitor: start: OK
,09-07 11:36:49.708  5989  5989 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-07 11:36:49.708  5989  5989 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-07 11:36:49.728  5989  5989 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,09-07 11:36:50.088  5989  6040 W jxcore-log: Initializing JXcore engine
09-07 11:36:50.088  5989  6040 W jxcore-log: JXcore engine is ready
,09-07 11:36:50.118  2596  2596 E audit   : type=1400 msg=audit(1473241010.118:273): avc:  denied  { ioctl } for  pid=6040 comm="Thread-112" path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=5366 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
09-07 11:36:50.118  2596  2596 E audit   :  SEPF_SECMOBILE_6.0.1_0013
09-07 11:36:50.118  2596  2596 E audit   : type=1300 msg=audit(1473241010.118:273): arch=40000028 syscall=54 per=8 success=no exit=-13 a0=7 a1=5451 a2=3 a3=db0fa3c8 items=0 ppid=596 pid=6040 auid=4294967295 uid=10136 gid=10136 euid=10136 suid=10136 fsuid=10136 egid=10136 sgid=10136 fsgid=10136 ses=4294967295 tty=(none) comm="Thread-112" exe="/system/bin/app_process32" subj=u:r:untrusted_app:s0:c512,c768 key=(null)
09-07 11:36:50.118  2596  2596 E audit   : type=1327 msg=audit(1473241010.118:273): proctitle="com.test.thalitest"
09-07 11:36:50.118  2596  2596 E audit   : type=1320 msg=audit(1473241010.118:273): 
09-07 11:36:50.118  2596  2596 E audit   : type=1400 msg=audit(1473241010.118:274): avc:  denied  { ioctl } for  pid=6040 comm="Thread-112" path="socket:[47588]" dev="sockfs" ino=47588 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
09-07 11:36:50.118  2596  2596 E audit   :  SEPF_SECMOBILE_6.0.1_0013
09-07 11:36:50.118  2596  2596 E audit   : type=1300 msg=audit(1473241010.118:274): arch=40000028 syscall=54 per=8 success=no exit=-13 a0=3c a1=5451 a2=3 a3=db0fa3c8 items=0 ppid=596 pid=6040 auid=4294967295 uid=10136 gid=10136 euid=10136 suid=10136 fsuid=10136 egid=10136 sgid=10136 fsgid=10136 ses=4294967295 tty=(none) comm="Thread-112" exe="/system/bin/app_process32" subj=u:r:untrusted_app:s0:c512,c768 key=(null)
09-07 11:36:50.118  2596  2596 E audit   : type=1327 msg=audit(1473241010.118:274): proctitle="com.test.thalitest"
09-07 11:36:50.118  2596  2596 E audit   : type=1320 msg=audit(1473241010.118:274): 
,09-07 11:36:50.128  5989  6040 W jxcore-log: Starting JXcore engine
,09-07 11:36:50.178  1796  1796 D Recents : onTaskStackChanged
,09-07 11:36:50.178  5989  6040 W jxcore-log: Platform android
09-07 11:36:50.178  5989  6040 W jxcore-log: 
09-07 11:36:50.178  5989  6040 W jxcore-log: Process ARCH arm
09-07 11:36:50.178  5989  6040 W jxcore-log: 
,09-07 11:36:50.268  5989  6040 I jxcore-log: JXcore Cordova bridge is ready!
09-07 11:36:50.268  5989  6040 I jxcore-log: 
09-07 11:36:50.268  5989  6040 W jxcore-log: JXcore engine is started
,09-07 11:36:50.268  5989  6039 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,09-07 11:36:50.278  5989  5989 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,09-07 11:36:50.338   707   707 I MSM-irqbalance: Decided to move IRQ166 from CPU2 to CPU3
,09-07 11:36:51.328  1250  1663 W System.err: remove failed: ENOENT (No such file or directory) : /data/system/recent_tasks/19_task.xml.bak
,09-07 11:36:51.708  1250  3553 D GameManagerService: identifyGamePackage. com.test.thalitest
,09-07 11:36:53.168  1250  1590 V AlarmManager: Expired Alarm result :4
,09-07 11:36:53.178  1250  1378 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{5da4d6a u0 com.google.android.gms.gcm.ACTION_CHECK_QUEUE qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{ef1b27 1866:com.google.android.gms.persistent/u0a10}
,09-07 11:36:53.188  1250  2333 V AlarmManager:  remove PendingIntent] PendingIntent{b85725b: PendingIntentRecord{e4edab6 com.google.android.gms broadcastIntent}}
,09-07 11:36:53.268  1250  2327 V AlarmManager:  remove PendingIntent] PendingIntent{7f8bbd1: PendingIntentRecord{e4edab6 com.google.android.gms broadcastIntent}}
,09-07 11:36:53.308  6042  6042 E Zygote  : v2
09-07 11:36:53.308  6042  6042 I libpersona: KNOX_SDCARD checking this for 10130
09-07 11:36:53.308  6042  6042 I libpersona: KNOX_SDCARD not a persona
,09-07 11:36:53.308  6042  6042 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0013
09-07 11:36:53.308  1250  2327 I ActivityManager: Start proc 6042:com.google.android.youtube/u0a130 for service com.google.android.youtube/com.google.android.libraries.youtube.common.gcore.gcoreclient.gcm.impl.GcmTaskServiceDelegator
09-07 11:36:53.308  1250  1621 D NetworkPolicy: isUidForegroundLocked: 10130, mScreenOn: false, uidstate: -1, mProxSensorScreenOff: false
,09-07 11:36:53.308  6042  6042 E Zygote  : accessInfo : 0
,09-07 11:36:53.308  6042  6042 W SELinux : SELinux: seapp_context_lookup: seinfo=untrusted, level=s0:c512,c768, pkgname=com.google.android.youtube 
,09-07 11:36:53.338  6042  6042 D TimaKeyStoreProvider: TimaSignature is unavailable
09-07 11:36:53.338  1250  1621 D NetworkPolicy: isUidForegroundLocked: 10130, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
09-07 11:36:53.338  6042  6042 D ActivityThread: Added TimaKeyStore provider
,09-07 11:36:53.358  6042  6042 W System  : ClassLoader referenced unknown path: /system/app/YouTube/lib/arm64
,09-07 11:36:53.398  1250  1310 W ActivityManager: Permission Denial: getCurrentUser() from pid=6042, uid=10130 requires android.permission.INTERACT_ACROSS_USERS
,09-07 11:36:53.428  6042  6055 W System  : ClassLoader referenced unknown path: /system/priv-app/GmsCore/lib/arm64
,09-07 11:36:53.488  6042  6055 V JNIHelp : Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,09-07 11:36:53.518  6042  6055 I ProviderInstaller: Installed default security provider GmsCore_OpenSSL
,09-07 11:36:53.588  6042  6042 D ContextRelationManager: ContextRelationManager() : FEATURE_ENABLED=true
,09-07 11:36:53.768  6077  6077 I dex2oat : Adjusted thread count (for runtime dex2oat): 4, 4
09-07 11:36:53.768  6077  6077 I dex2oat : /system/bin/dex2oat --dex-file=/data/user/0/com.google.android.youtube/cache/ads-1362548114.jar --oat-file=/data/user/0/com.google.android.youtube/cache/ads-1362548114.dex
,09-07 11:36:53.798  6077  6077 I dex2oat : ----------------------------------------------------
09-07 11:36:53.798  6077  6077 I dex2oat : <SS>: S T A R T I N G . . .
09-07 11:36:53.798  6077  6077 E dex2oat : <SS>: oat location is not valid /data/user/0/com.google.android.youtube/cache/ads-1362548114.dex
,09-07 11:36:53.798  6077  6077 I dex2oat : dex2oat took 36.186ms (threads: 4) arena alloc=341KB java alloc=44KB native alloc=1780KB free=1547KB
,09-07 11:36:53.818  1694  1812 D vol.MediaSessions: updateRemoteControllerH null
09-07 11:36:53.818  1694  1812 D vol.MediaSessions: onActiveSessionsUpdatedH n=0
09-07 11:36:53.818  1694  1812 D vol.MediaSessions: onActiveSessionsUpdatedH n=0
09-07 11:36:53.818  2587  2587 E Avrcp   : onActiveSessionsChanged
09-07 11:36:53.818  2587  2587 D Avrcp   : pick active media Controller
09-07 11:36:53.818  2587  2587 D Avrcp   : Get the active Media Controller 
,09-07 11:36:53.828  1250  2333 D ConnectivityService: returning getNetworkInfo for network type 0 : [type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
,09-07 11:36:53.868  6042  6042 W InstanceID/Rpc: Found 10010
,09-07 11:36:53.868  1250  1378 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{aff558 u0 com.google.android.gms.gcm.ACTION_SCHEDULE qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{ef1b27 1866:com.google.android.gms.persistent/u0a10}
,09-07 11:36:53.888  1250  1378 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{1bc76b1 u0 com.google.android.gms.gcm.ACTION_SCHEDULE qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{ef1b27 1866:com.google.android.gms.persistent/u0a10}
,09-07 11:36:53.898  1250  1378 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{8f0cced u0 com.google.android.gms.gcm.ACTION_SCHEDULE qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{ef1b27 1866:com.google.android.gms.persistent/u0a10}
,09-07 11:36:53.908  1250  1720 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{945a722 u0 com.google.android.gms.gcm.ACTION_SCHEDULE qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{ef1b27 1866:com.google.android.gms.persistent/u0a10}
,09-07 11:36:53.928  1250  1313 V AlarmManager:  remove PendingIntent] PendingIntent{1e0b5b3: PendingIntentRecord{e4edab6 com.google.android.gms broadcastIntent}}
,09-07 11:36:53.948  1250  1994 D PackageManager: setEnabledSetting : userId = 0 packageName = com.google.android.youtube cmp = com.google.android.libraries.youtube.offline.transfer.service.OfflineTransferService$DeviceStateReceiver newState = 2 callingPackage = 10130
,09-07 11:36:53.968  6042  6101 W GmsClient: mServiceBroker is null, client disconnected
,09-07 11:36:53.978  6042  6112 I System.out: (HTTPLog)-Static: Hongbao
,09-07 11:36:53.988  6042  6112 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
09-07 11:36:53.988  6042  6112 I System.out: (HTTPLog)-Static: Hongbao
09-07 11:36:53.988  6042  6112 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,09-07 11:36:53.988   554  1410 D EnterpriseController: netId is 0
09-07 11:36:53.988   554  1410 D Netd    : getNetworkForDns: using netid 502 for uid 10130
,09-07 11:36:53.998  6042  6062 I System.out: Thread-725(ApacheHTTPLog):Reading from variable values from setDefaultValuesToVariables
,09-07 11:36:53.998  6042  6062 I System.out: Thread-725(ApacheHTTPLog):isSBSettingEnabled false
09-07 11:36:53.998  6042  6062 I System.out: Thread-725(ApacheHTTPLog):isShipBuild true
09-07 11:36:53.998  6042  6062 I System.out: Thread-725(ApacheHTTPLog):getDebugLevel 0x4f4c
09-07 11:36:53.998  6042  6062 I System.out: Thread-725(ApacheHTTPLog):Smart Bonding Setting is false
09-07 11:36:53.998  6042  6062 I System.out: Thread-725(ApacheHTTPLog):SmartBonding Setting is false, SHIP_BUILD is true, log to file is false, DBG is false, DEBUG_LEVEL (1-LOW, 2-MID, 3-HIGH) is 1
,09-07 11:36:54.008   554  1410 D EnterpriseController: netId is 0
09-07 11:36:54.008   554  1410 D Netd    : getNetworkForDns: using netid 502 for uid 10130
,09-07 11:36:54.318  6042  6062 I System.out: Thread-725 calls detatch()
,09-07 11:36:54.338  1250  1378 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{224134 u0 com.google.android.gms.gcm.ACTION_SCHEDULE qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{ef1b27 1866:com.google.android.gms.persistent/u0a10}
,09-07 11:36:54.378  1250  2333 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{abcb5d u0 com.google.android.gms.gcm.ACTION_SCHEDULE qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{ef1b27 1866:com.google.android.gms.persistent/u0a10}
,09-07 11:36:54.388  1250  1964 V AlarmManager:  remove PendingIntent] PendingIntent{80a1cd2: PendingIntentRecord{e4edab6 com.google.android.gms broadcastIntent}}
,09-07 11:36:54.408  1250  1834 E Watchdog: !@Sync 3 [09-07 11:36:54.415]
,09-07 11:36:54.438  1250  2010 V AlarmManager:  remove PendingIntent] PendingIntent{d8271a3: PendingIntentRecord{e4edab6 com.google.android.gms broadcastIntent}}
,09-07 11:36:54.518  2207  6123 D UdcContextInitService: registered all accounts: true
,09-07 11:36:54.548  1250  2010 V AlarmManager:  remove PendingIntent] PendingIntent{c49341e: PendingIntentRecord{e4edab6 com.google.android.gms broadcastIntent}}
,09-07 11:36:54.598  1866  6125 I VacuumService: Vacuum at: now=1473241014605 tag=VacuumService
,09-07 11:36:54.658  1250  2396 V AlarmManager:  remove PendingIntent] PendingIntent{bb20915: PendingIntentRecord{e4edab6 com.google.android.gms broadcastIntent}}
,09-07 11:36:54.698  1250  1986 V AlarmManager:  remove PendingIntent] PendingIntent{6d9a8f6: PendingIntentRecord{6c14f7 com.google.android.gms broadcastIntent}}
,09-07 11:36:54.778  1250  3553 D SSRM:s  : SIOP:: AP = 330, PST = 345 (W:10), CP = 43, LCD = 0
,09-07 11:36:54.778  1250  3553 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
,09-07 11:36:55.318  1250  1986 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
09-07 11:36:55.318  1250  1986 D BatteryService: level:100, scale:100, status:3, health:2, present:true, voltage: 4363, temperature: 289, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303407, invalid charger:0, maxChargingCurrent:0
,09-07 11:36:55.318  1250  1986 D BatteryService: online:4, current avg:23, charge type:2, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:-105
09-07 11:36:55.318  1250  1250 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,09-07 11:36:55.328  1694  1694 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
09-07 11:36:55.328  1694  1694 D PowerUI : priorPlugType = 2 mPlugType =  2
09-07 11:36:55.328  1694  1694 D KeyguardUpdateMonitor: handleBatteryUpdate
,09-07 11:36:55.338  2587  2587 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
09-07 11:36:55.338  2587  3110 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,09-07 11:36:55.338   707   707 I MSM-irqbalance: Decided to move IRQ51 from CPU2 to CPU3
,09-07 11:36:55.348  1694  1694 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:3 health:2
09-07 11:36:55.348  1694  1694 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:3 health:2
09-07 11:36:55.348  1694  1694 D CoverUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,09-07 11:36:56.068  5989  6040 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
09-07 11:36:56.068  5989  6040 I jxcore-log: 
,09-07 11:36:56.068  5989  6040 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
09-07 11:36:56.068  5989  6040 I jxcore-log: 
,09-07 11:36:56.078  5989  6040 D BluetoothAdapter: STATE_ON,
,09-07 11:36:56.088  5989  6040 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:,
09-07 11:36:56.088  5989  6040 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-07 11:36:56.088  5989  6040 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-07 11:36:56.088  5989  6040 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-07 11:36:56.088  5989  6040 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
,09-07 11:36:56.088  5989  6040 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-07 11:36:56.088  5989  6040 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-07 11:36:56.088  5989  6040 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-07 11:36:56.088  5989  6040 D BluetoothAdapter: STATE_ON,
,09-07 11:36:56.088  5989  6040 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e,
,09-07 11:36:56.088  5989  6040 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
09-07 11:36:56.088  5989  6040 I jxcore-log: 
,09-07 11:36:56.098  5989  6040 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
09-07 11:36:56.098  5989  6040 I jxcore-log: 
,09-07 11:36:56.398  5989  6040 I jxcore-log: Unit Test app is loaded
09-07 11:36:56.398  5989  6040 I jxcore-log: 
,09-07 11:36:56.398  5989  6040 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-07 11:36:56.398  5989  6040 I jxcore-log: 
,09-07 11:36:56.398  5989  6040 D executeNativeTests: Running unit tests
,09-07 11:36:56.408  5989  5989 I chromium: [INFO:CONSOLE(68)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (68)
,09-07 11:36:56.468  5989  6040 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-07 11:36:56.468  5989  6040 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@d297dbd added. We now have 2 listener(s)
,09-07 11:36:56.468  5989  6040 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "44:78:3E:EB:95:EE"
09-07 11:36:56.468  5989  6040 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-07 11:36:56.468  5989  6040 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-07 11:36:56.468  5989  6040 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-07 11:36:56.468  5989  6040 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c284fb2 added. We now have 2 listener(s)
09-07 11:36:56.468  5989  6040 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-07 11:36:56.468  5989  6040 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-07 11:36:56.478  5989  6040 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-07 11:36:56.488  5989  6040 D BluetoothAdapter: STATE_ON
,09-07 11:36:56.488  5989  6040 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-07 11:36:56.488  5989  6040 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-07 11:36:56.488  5989  6040 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-07 11:36:56.488  5989  6040 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-07 11:36:56.488  5989  6040 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-07 11:36:56.488  5989  6040 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-07 11:36:56.488  5989  6040 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-07 11:36:56.488  5989  6040 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-07 11:36:56.498  5989  6040 D BluetoothAdapter: STATE_ON,
,09-07 11:36:56.498  5989  6040 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e,
,09-07 11:36:56.498  5989  6040 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-07 11:36:56.498  5989  6040 D BluetoothAdapter: STATE_ON,
09-07 11:36:56.498  5989  5989 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-07 11:36:56.508  5989  5989 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes,
,09-07 11:36:56.508  5989  6040 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
09-07 11:36:56.508  5989  6040 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,09-07 11:36:56.508  5989  6040 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-07 11:36:56.508  5989  6040 E io.jxcore.node.ConnectionHelper: onConnectionTimeout: Connection attempt with peer [<no peer name> 00:11:22:33:44:55] timed out
09-07 11:36:56.508  5989  6040 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
09-07 11:36:56.508  5989  6040 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
,09-07 11:36:56.508  5989  6040 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-07 11:36:56.508  5989  6040 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-07 11:36:56.508  5989  6040 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-07 11:36:56.508  5989  6040 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 11:36:56.508  5989  6040 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-07 11:36:56.508  5989  6040 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-07 11:36:56.508  5989  6040 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@d297dbd removed from the list
09-07 11:36:56.508  5989  6040 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-07 11:36:56.508  5989  6040 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c284fb2 removed from the list
09-07 11:36:56.508  5989  6040 D io.jxcore.node.ConnectivityMonitor: stop
09-07 11:36:56.508  5989  6040 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 11:36:56.518  5989  6040 D io.jxcore.node.ConnectionHelper: onBluetoothMacAddressResolved: 00:11:22:33:44:55 - Bro Mode is not supported
09-07 11:36:56.518  5989  6040 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-07 11:36:56.518  5989  6040 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 11:36:56.518  5989  6040 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 11:36:56.518  5989  6040 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@d297dbd not in the list
09-07 11:36:56.518  5989  6040 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-07 11:36:56.518  5989  6040 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c284fb2 not in the list
09-07 11:36:56.518  5989  6040 D io.jxcore.node.ConnectivityMonitor: stop
,09-07 11:36:56.518  5989  6040 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 11:36:56.518  5989  6040 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 11:36:56.518  5989  6040 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
09-07 11:36:56.518  5989  6040 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
09-07 11:36:56.518  5989  6040 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
09-07 11:36:56.518  5989  6040 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
09-07 11:36:56.518  5989  6040 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
09-07 11:36:56.518  5989  6040 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
09-07 11:36:56.518  5989  6040 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
09-07 11:36:56.518  5989  6040 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
09-07 11:36:56.518  5989  6040 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
09-07 11:36:56.518  5989  6040 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
09-07 11:36:56.518  5989  6040 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
09-07 11:36:56.518  5989  6040 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
09-07 11:36:56.518  5989  6040 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
09-07 11:36:56.518  5989  6040 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
09-07 11:36:56.518  5989  6040 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
09-07 11:36:56.518  5989  6040 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
09-07 11:36:56.518  5989  6040 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
09-07 11:36:56.518  5989  6040 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
09-07 11:36:56.518  5989  6040 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
09-07 11:36:56.518  5989  6040 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
09-07 11:36:56.518  5989  6040 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
09-07 11:36:56.518  5989  6040 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
09-07 11:36:56.518  5989  6040 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
09-07 11:36:56.518  5989  6040 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
09-07 11:36:56.518  5989  6040 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
09-07 11:36:56.518  5989  6040 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
09-07 11:36:56.518  5989  6040 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
09-07 11:36:56.518  5989  6040 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
09-07 11:36:56.518  5989  6040 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
09-07 11:36:56.518  5989  6040 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
09-07 11:36:56.518  5989  6040 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
09-07 11:36:56.518  5989  6040 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-07 11:36:56.518  5989  6040 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 11:36:56.518  5989  6040 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 11:36:56.518  5989  6040 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@d297dbd not in the list
09-07 11:36:56.518  5989  6040 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-07 11:36:56.518  5989  6040 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c284fb2 not in the list
09-07 11:36:56.518  5989  6040 D io.jxcore.node.ConnectivityMonitor: stop
09-07 11:36:56.518  5989  6040 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 11:36:56.518  5989  6040 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 11:36:56.518  5989  6040 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: true
09-07 11:36:56.518  5989  6040 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-07 11:36:56.528  5989  6040 D BluetoothAdapter: STATE_ON
09-07 11:36:56.538  5989  6040 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-07 11:36:56.538  5989  6040 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-07 11:36:56.538  5989  6040 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-07 11:36:56.538  5989  6040 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-07 11:36:56.538  5989  6040 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-07 11:36:56.538  5989  6040 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-07 11:36:56.538  5989  6040 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-07 11:36:56.538  5989  6040 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-07 11:36:56.538  5989  6040 D BluetoothAdapter: STATE_ON
09-07 11:36:56.548  5989  6040 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-07 11:36:56.548  5989  6040 D io.jxcore.node.ConnectivityMonitor: start: OK
09-07 11:36:56.548  5989  6040 I io.jxcore.node.StartStopOperationHandler: updateBeaconAdExtraInformation: New value: 1
09-07 11:36:56.548  5989  6040 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBeaconAdExtraInformation: 0 -> 1
09-07 11:36:56.548  5989  6040 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
09-07 11:36:56.548  5989  6040 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should start/stop everything
09-07 11:36:56.548  5989  6040 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
09-07 11:36:56.548  5989  6040 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-07 11:36:56.548  5989  6040 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
09-07 11:36:56.548  5989  6040 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
09-07 11:36:56.548  5989  6040 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
09-07 11:36:56.548  5989  6040 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
09-07 11:36:56.548  5989  6040 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: true
09-07 11:36:56.548  5989  6040 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-07 11:36:56.548  5989  6040 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-07 11:36:56.548  5989  5989 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-07 11:36:56.558  5989  6126 D BluetoothSocket: bindListen(): myUserId = 0
09-07 11:36:56.558  5989  6126 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-07 11:36:56.558  5989  5989 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-07 11:36:56.558  5989  6040 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
09-07 11:36:56.558  5989  5989 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
09-07 11:36:56.558  5989  6040 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
09-07 11:36:56.558  5989  6126 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
09-07 11:36:56.558  5989  6040 D BluetoothAdapter: STATE_ON
09-07 11:36:56.558  5989  6040 D BluetoothAdapter: STATE_ON
09-07 11:36:56.568  5989  6040 D BluetoothAdapter: STATE_ON
09-07 11:36:56.568  5989  6040 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
09-07 11:36:56.578  5989  6040 D BluetoothAdapter: STATE_ON
09-07 11:36:56.578  5989  6040 D BluetoothAdapter: STATE_ON
09-07 11:36:56.578  5989  6040 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
09-07 11:36:56.578  5989  6040 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
09-07 11:36:56.578  5989  6040 D BluetoothAdapter: STATE_ON
09-07 11:36:56.578  5989  6040 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
09-07 11:36:56.578  5989  6040 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "44:78:3E:EB:95:EE"
09-07 11:36:56.578  5989  6040 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 01 44 78 3E EB 95 EE
09-07 11:36:56.578  5989  6040 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[1, 68, 120, 62, -21, -107, -18]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
09-07 11:36:56.578  5989  6040 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[1, 68, 120, 62, -21, -107, -18]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
09-07 11:36:56.578  5989  6040 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting...
09-07 11:36:56.588  5989  6040 D BluetoothAdapter: STATE_ON
09-07 11:36:56.588  5989  6040 D BluetoothAdapter: STATE_ON
,09-07 11:36:56.588  5989  6040 D BluetoothLeAdvertiser: start advertising
09-07 11:36:56.588  5989  6040 D BluetoothAdapter: STATE_ON
,09-07 11:36:56.598  2587  2604 D BtGatt.GattService: registerClient() - UUID=b9f520cd-aa52-404e-801a-101a9895dd36
,09-07 11:36:56.638  2587  2756 D BtGatt.GattService: onClientRegistered() - UUID=b9f520cd-aa52-404e-801a-101a9895dd36, clientIf=6
,09-07 11:36:56.638  5989  6000 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=6
,09-07 11:36:56.638  2587  2614 D BtGatt.GattService: [GSIM LOG]: startMultiAdvertising: 2
,09-07 11:36:56.648  2587  2614 D BtGatt.GattService: [GSIM LOG]: getCallingProcessName: com.test.thalitest
09-07 11:36:56.648  2587  2614 D BtGatt.GattService: [GSIM LOG]: getCallingProcessName: com.test.thalitest
,09-07 11:36:56.648  2587  2780 E BtGatt.GattService: [GSIM LOG]: gsimLogHandler: com.test.thalitest, msg: MESSAGE_START_ADV
09-07 11:36:56.648  2587  2780 D BtGatt.GattService: [GSIM LOG]: gsimLogHandler: prevDate: 7, currDate: 7
09-07 11:36:56.648  2587  2765 D BtGatt.AdvertiseManager: message : 0
09-07 11:36:56.658  2587  2765 D BtGatt.AdvertiseManager: number of adv instance running = 0
09-07 11:36:56.658  2587  2765 D BtGatt.AdvertiseManager: size of list is =0
,09-07 11:36:56.658  2587  2765 D BtGatt.AdvertiseManager: starting advertising
,09-07 11:36:56.658  2587  2765 D BtGatt.AdvertiseManager: isStandardAdv = false
,09-07 11:36:56.658  2587  2780 D BtGatt.GattService: [GSIM LOG]: increaseAdvCount : com.test.thalitest : 19
09-07 11:36:56.658  3003  3007 I WCNSS_FILTER: ibs_msm_serial_clock_vote: vote UART CLK ON using UART driver's ioctl()
,09-07 11:36:56.658  1250  1313 V AlarmManager:  remove PendingIntent] PendingIntent{e686185: PendingIntentRecord{45887f2 com.android.bluetooth broadcastIntent}}
,09-07 11:36:56.668  3003  3007 I WCNSS_FILTER: do_write: IBS write: fd
,09-07 11:36:56.668  3003  3007 I WCNSS_FILTER: Direction(0): bytes: 28 : bytes_written: 28
,09-07 11:36:56.668  3003  3003 I WCNSS_FILTER: do_write: IBS write: fc
,09-07 11:36:56.668  3003  3003 I WCNSS_FILTER: Direction(1): bytes: 8 : bytes_written: 8
09-07 11:36:56.668  3003  3007 I WCNSS_FILTER: Direction(0): bytes: 7 : bytes_written: 7
09-07 11:36:56.668  1250  1310 V AlarmManager:  remove PendingIntent] PendingIntent{2063bda: PendingIntentRecord{45887f2 com.android.bluetooth broadcastIntent}}
09-07 11:36:56.668  3003  3003 I WCNSS_FILTER: Direction(1): bytes: 8 : bytes_written: 8
,09-07 11:36:56.668  2587  2756 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=6, status=0
09-07 11:36:56.668  2587  2780 D BtGatt.GattService: [GSIM LOG]: setAdvTime : com.test.thalitest@LowLatency : 24554016
09-07 11:36:56.668  2587  2780 D BtGatt.GattService: [GSIM LOG]: setAdvType : com.test.thalitest@LowLatency : 2
09-07 11:36:56.678  2587  2780 D BtGatt.GattService: [GSIM LOG]: updateAdvTime
,09-07 11:36:56.678  2587  2780 D BtGatt.GattService: [GSIM LOG]: com.test.thalitest@LowLatency, R time : 1 => 1
09-07 11:36:56.678  2587  2765 D BtGatt.AdvertiseManager: starting multi advertising
,09-07 11:36:56.678  3003  3007 I WCNSS_FILTER: Direction(0): bytes: 38 : bytes_written: 38
09-07 11:36:56.678  1250  1990 V AlarmManager:  remove PendingIntent] PendingIntent{780180b: PendingIntentRecord{45887f2 com.android.bluetooth broadcastIntent}}
,09-07 11:36:56.678  3003  3003 I WCNSS_FILTER: Direction(1): bytes: 8 : bytes_written: 8
09-07 11:36:56.678  2587  2756 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=6, status=0
,09-07 11:36:56.678  2587  2765 D BtGatt.AdvertiseManager: logClientsSet() - status: 0
09-07 11:36:56.678  2587  2765 D BtGatt.AdvertiseManager: clientIf: 6, Mode: 2, TxPowerLevel: 3, isConnectable: false, Timeout: 0
09-07 11:36:56.678  2587  2765 D BtGatt.AdvertiseManager: postCallback clientIf = 6 status = 0
09-07 11:36:56.678  2587  2765 D BtGatt.GattService: onMultipleAdvertiseCallback() clientIf=6, status=0, isStart=true
09-07 11:36:56.678  5989  5999 D BluetoothLeAdvertiser: onMultiAdvertiseCallback status = 0 isStart = true
09-07 11:36:56.678  5989  6040 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
09-07 11:36:56.678  5989  6040 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,09-07 11:36:56.678  1250  2396 V AlarmManager:  remove PendingIntent] PendingIntent{c5fc6e8: PendingIntentRecord{45887f2 com.android.bluetooth broadcastIntent}}
,09-07 11:36:56.678  5989  6040 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,09-07 11:36:56.678  1250  2010 V AlarmManager:  remove PendingIntent] PendingIntent{2d29101: PendingIntentRecord{45887f2 com.android.bluetooth broadcastIntent}}
09-07 11:36:56.688  5989  6040 I io.jxcore.node.ConnectionHelper: start: OK
09-07 11:36:56.688  5989  5989 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
09-07 11:36:56.688  5989  5989 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess
,09-07 11:36:56.688  5989  5989 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
09-07 11:36:56.688  5989  5989 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: true
09-07 11:36:56.688  5989  5989 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [ADVERTISING]
09-07 11:36:56.688  5989  5989 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [ADVERTISING]
,09-07 11:36:56.688  1250  1986 V AlarmManager:  remove PendingIntent] PendingIntent{39c3ba6: PendingIntentRecord{45887f2 com.android.bluetooth broadcastIntent}}
,09-07 11:36:56.688  5989  5989 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: true
09-07 11:36:56.688  5989  5989 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: true
,09-07 11:36:57.188  5989  5989 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: true,
09-07 11:36:57.188  5989  5989 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
09-07 11:36:57.188  5989  5989 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,09-07 11:36:57.678  3003  3066 I WCNSS_FILTER: do_write: IBS write: fe
09-07 11:36:57.678  3003  3066 I WCNSS_FILTER: ibs_msm_serial_clock_vote: vote UART CLK OFF using UART driver's ioctl()
,09-07 11:36:58.338  1250  1425 D PackageManager: [MSG] WRITE_PACKAGE_RESTRICTIONS
,09-07 11:36:58.368  1250  1425 W System.err: remove failed: ENOENT (No such file or directory) : /data/system/users/0/package-restrictions.xml.bak
,09-07 11:36:59.808  2207  5710 I System.out: (HTTPLog)-Static: Hongbao
,09-07 11:36:59.818  2207  5710 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
09-07 11:36:59.818  2207  5710 I System.out: (HTTPLog)-Static: Hongbao
09-07 11:36:59.818  2207  5710 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,09-07 11:36:59.818   554  1410 D EnterpriseController: netId is 0
09-07 11:36:59.818   554  1410 D Netd    : getNetworkForDns: using netid 502 for uid 10010
,09-07 11:36:59.988  1250  1590 V AlarmManager: Expired Alarm result :8
,09-07 11:37:00.068  1250  1986 V AlarmManager:  remove PendingIntent] PendingIntent{c1629e7: PendingIntentRecord{6c14f7 com.google.android.gms broadcastIntent}}
,09-07 11:37:02.688  5989  6040 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-07 11:37:02.688  5989  6040 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Stop operation: Should start/stop everything
09-07 11:37:02.688  5989  6040 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
09-07 11:37:02.688  5989  6040 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
09-07 11:37:02.688  5989  6040 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
09-07 11:37:02.688  5989  6040 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
09-07 11:37:02.688  5989  6040 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-07 11:37:02.688  5989  6040 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
09-07 11:37:02.688  5989  6040 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
09-07 11:37:02.688  5989  6040 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-07 11:37:02.688  5989  5989 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
,09-07 11:37:02.688  5989  6040 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-07 11:37:02.688  5989  6040 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-07 11:37:02.688  5989  6126 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
09-07 11:37:02.688  5989  6126 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
09-07 11:37:02.688  5989  6126 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
09-07 11:37:02.688  5989  6040 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
,09-07 11:37:02.688  5989  6040 D BluetoothAdapter: STATE_ON
,09-07 11:37:02.688  5989  6040 D BluetoothAdapter: STATE_ON
09-07 11:37:02.698  5989  6040 D BluetoothLeScanner: could not find callback wrapper
09-07 11:37:02.698  5989  6040 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-07 11:37:02.698  5989  6040 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
09-07 11:37:02.698  5989  6040 D BluetoothAdapter: STATE_ON
,09-07 11:37:02.698  5989  6040 D BluetoothAdapter: STATE_ON,
09-07 11:37:02.698  5989  6040 D BluetoothLeAdvertiser: stop advertising
,09-07 11:37:02.698  2587  2604 D BtGatt.GattService: [GSIM LOG]: getCallingProcessName: com.test.thalitest
,09-07 11:37:02.708  1250  1720 V AlarmManager:  remove PendingIntent] PendingIntent{5de6994: PendingIntentRecord{45887f2 com.android.bluetooth broadcastIntent}}
09-07 11:37:02.698  2587  2604 D BtGatt.GattService: [GSIM LOG]: getCallingProcessName: com.test.thalitest
,09-07 11:37:02.698  2587  2765 D BtGatt.AdvertiseManager: message : 1,
09-07 11:37:02.698  2587  2780 E BtGatt.GattService: [GSIM LOG]: gsimLogHandler: com.test.thalitest, msg: MESSAGE_STOP_ADV
09-07 11:37:02.698  2587  2780 D BtGatt.GattService: [GSIM LOG]: gsimLogHandler: prevDate: 7, currDate: 7
,09-07 11:37:02.698  2587  2780 D BtGatt.GattService: [GSIM LOG]: updateAdvTime
09-07 11:37:02.698  2587  2765 D BtGatt.AdvertiseManager: stop advertise for client =  6
,09-07 11:37:02.698  2587  2765 D BtGatt.AdvertiseManager: stop advertising, standardAdvClientIf = 0 client.clientIf = 6
09-07 11:37:02.698  2587  2765 D BtGatt.AdvertiseManager: logClientsSet() - status: -1
,09-07 11:37:02.708  3003  3007 I WCNSS_FILTER: ibs_msm_serial_clock_vote: vote UART CLK ON using UART driver's ioctl()
,09-07 11:37:02.708  3003  3007 I WCNSS_FILTER: do_write: IBS write: fd
,09-07 11:37:02.718  3003  3007 I WCNSS_FILTER: Direction(0): bytes: 7 : bytes_written: 7
,09-07 11:37:02.718  3003  3003 I WCNSS_FILTER: do_write: IBS write: fc
09-07 11:37:02.718  3003  3003 I WCNSS_FILTER: Direction(1): bytes: 8 : bytes_written: 8
,09-07 11:37:02.718  2587  2756 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=6, status=0
09-07 11:37:02.718  2587  2756 D BtGatt.GattService: Client app is not null!
09-07 11:37:02.718  3003  3007 E WCNSS_FILTER: do_read: read returned 0, err = Success, read bytes: 0, expected: 0
09-07 11:37:02.718  3003  3007 I WCNSS_FILTER: Direction(0): bytes: 4 : bytes_written: 4
09-07 11:37:02.718  1250  1313 V AlarmManager:  remove PendingIntent] PendingIntent{563c3d: PendingIntentRecord{45887f2 com.android.bluetooth broadcastIntent}}
09-07 11:37:02.718  5989  6000 D BluetoothLeAdvertiser: onMultiAdvertiseCallback status = 0 isStart = false
,09-07 11:37:02.718  2587  2614 D BtGatt.GattService: unregisterClient() - clientIf=6
09-07 11:37:02.718  5989  6040 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-07 11:37:02.718  5989  6040 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
09-07 11:37:02.718  5989  6040 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: false
09-07 11:37:02.718  5989  6040 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [ADVERTISING] to [NOT_STARTED]
09-07 11:37:02.718  5989  6040 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [ADVERTISING] -> [NOT_STARTED]
,09-07 11:37:02.718  1250  1964 V AlarmManager:  remove PendingIntent] PendingIntent{f406c32: PendingIntentRecord{45887f2 com.android.bluetooth broadcastIntent}}
09-07 11:37:02.718  5989  6040 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
09-07 11:37:02.718  5989  6040 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-07 11:37:02.718  5989  6040 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,09-07 11:37:02.718  5989  6040 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-07 11:37:02.728  5989  5989 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,09-07 11:37:02.728  5989  5989 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
09-07 11:37:02.728  5989  5989 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-07 11:37:02.728  5989  5989 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
09-07 11:37:02.728  5989  5989 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-07 11:37:02.728  5989  5989 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-07 11:37:02.728  2587  2780 D BtGatt.GattService: [GSIM LOG]: com.test.thalitest@LowLatency, R time : 1 => 2
09-07 11:37:02.728  2587  2780 D BtGatt.GattService: [GSIM LOG]: remove : com.test.thalitest@LowLatency at  BLE_ADV_REQUESTED_DB
,09-07 11:37:02.728  3003  3003 I WCNSS_FILTER: Direction(1): bytes: 15 : bytes_written: 15
09-07 11:37:02.728  3003  3007 I WCNSS_FILTER: Direction(0): bytes: 12 : bytes_written: 12
,09-07 11:37:02.728  1250  1310 V AlarmManager:  remove PendingIntent] PendingIntent{117d83: PendingIntentRecord{45887f2 com.android.bluetooth broadcastIntent}}
,09-07 11:37:02.728  3003  3003 I WCNSS_FILTER: Direction(1): bytes: 8 : bytes_written: 8
,09-07 11:37:02.738  1250  2327 V AlarmManager:  remove PendingIntent] PendingIntent{2028b00: PendingIntentRecord{45887f2 com.android.bluetooth broadcastIntent}}
,09-07 11:37:02.738  1250  2396 V AlarmManager:  remove PendingIntent] PendingIntent{36f5f39: PendingIntentRecord{45887f2 com.android.bluetooth broadcastIntent}}
,09-07 11:37:03.228  5989  5989 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false,
,09-07 11:37:03.728  3003  3066 I WCNSS_FILTER: do_write: IBS write: fe
09-07 11:37:03.728  3003  3066 I WCNSS_FILTER: ibs_msm_serial_clock_vote: vote UART CLK OFF using UART driver's ioctl()
,09-07 11:37:04.798  1250  3553 D SSRM:s  : SIOP:: AP = 330, PST = 343 (W:11), CP = 39, LCD = 0
09-07 11:37:04.798  1250  3553 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
,09-07 11:37:05.398  1250  1721 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
09-07 11:37:05.398  1250  1721 D BatteryService: level:100, scale:100, status:3, health:2, present:true, voltage: 4390, temperature: 289, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303407, invalid charger:0, maxChargingCurrent:0
09-07 11:37:05.398  1250  1721 D BatteryService: online:4, current avg:24, charge type:0, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:156
09-07 11:37:05.398  1250  1250 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,09-07 11:37:05.398  1694  1694 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
09-07 11:37:05.398  1694  1694 D KeyguardUpdateMonitor: handleBatteryUpdate
,09-07 11:37:05.398  1694  1694 D PowerUI : priorPlugType = 2 mPlugType =  2
,09-07 11:37:05.408  2587  2587 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
09-07 11:37:05.408  2587  3110 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,09-07 11:37:05.418  1694  1694 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:3 health:2
,09-07 11:37:05.418  1694  1694 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:3 health:2
,09-07 11:37:05.418  1694  1694 D CoverUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,09-07 11:37:05.728  5989  6040 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: true
09-07 11:37:05.728  5989  6040 V io.jxcore.node.ConnectivityMonitor: start: Already started
09-07 11:37:05.728  5989  6040 I io.jxcore.node.StartStopOperationHandler: updateBeaconAdExtraInformation: New value: 2
09-07 11:37:05.728  5989  6040 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBeaconAdExtraInformation: 1 -> 2
09-07 11:37:05.728  5989  6040 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
09-07 11:37:05.728  5989  6040 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should start/stop everything
09-07 11:37:05.728  5989  6040 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
09-07 11:37:05.728  5989  6040 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-07 11:37:05.728  5989  6040 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
09-07 11:37:05.728  5989  6040 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
09-07 11:37:05.728  5989  6040 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
09-07 11:37:05.728  5989  6040 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
09-07 11:37:05.728  5989  6040 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: true
09-07 11:37:05.728  5989  6040 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-07 11:37:05.728  5989  6040 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-07 11:37:05.728  5989  5989 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
,09-07 11:37:05.738  5989  6133 D BluetoothSocket: bindListen(): myUserId = 0
09-07 11:37:05.738  5989  6133 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-07 11:37:05.738  5989  6040 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
09-07 11:37:05.738  5989  6040 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
09-07 11:37:05.738  5989  6133 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
,09-07 11:37:05.738  5989  6040 D BluetoothAdapter: STATE_ON
,09-07 11:37:05.738  5989  6040 D BluetoothAdapter: STATE_ON
,09-07 11:37:05.738  5989  6040 D BluetoothAdapter: STATE_ON
,09-07 11:37:05.748  5989  6040 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false,
,09-07 11:37:05.748  5989  6040 D BluetoothAdapter: STATE_ON
,09-07 11:37:05.748  5989  6040 D BluetoothAdapter: STATE_ON
09-07 11:37:05.748  5989  6040 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
,09-07 11:37:05.748  5989  6040 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,09-07 11:37:05.748  5989  6040 D BluetoothAdapter: STATE_ON
,09-07 11:37:05.748  5989  6040 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
09-07 11:37:05.748  5989  6040 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "44:78:3E:EB:95:EE"
,09-07 11:37:05.748  5989  6040 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 02 44 78 3E EB 95 EE
09-07 11:37:05.748  5989  6040 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[2, 68, 120, 62, -21, -107, -18]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
09-07 11:37:05.748  5989  6040 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[2, 68, 120, 62, -21, -107, -18]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
09-07 11:37:05.748  5989  6040 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting...
,09-07 11:37:05.758  5989  6040 D BluetoothAdapter: STATE_ON
09-07 11:37:05.758  5989  6040 D BluetoothAdapter: STATE_ON
09-07 11:37:05.758  5989  6040 D BluetoothLeAdvertiser: start advertising
,09-07 11:37:05.758  5989  6040 D BluetoothAdapter: STATE_ON
,09-07 11:37:05.758  2587  3153 D BtGatt.GattService: registerClient() - UUID=a44fad4c-99e1-4ee4-8068-7254b2c08fad
,09-07 11:37:05.798  2587  2756 D BtGatt.GattService: onClientRegistered() - UUID=a44fad4c-99e1-4ee4-8068-7254b2c08fad, clientIf=6,
09-07 11:37:05.798  5989  5999 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=6
,09-07 11:37:05.798  2587  2614 D BtGatt.GattService: [GSIM LOG]: startMultiAdvertising: 2,
,09-07 11:37:05.808  2587  2614 D BtGatt.GattService: [GSIM LOG]: getCallingProcessName: com.test.thalitest
09-07 11:37:05.808  2587  2614 D BtGatt.GattService: [GSIM LOG]: getCallingProcessName: com.test.thalitest
09-07 11:37:05.808  2587  2780 E BtGatt.GattService: [GSIM LOG]: gsimLogHandler: com.test.thalitest, msg: MESSAGE_START_ADV
09-07 11:37:05.808  2587  2780 D BtGatt.GattService: [GSIM LOG]: gsimLogHandler: prevDate: 7, currDate: 7
,09-07 11:37:05.808  2587  2765 D BtGatt.AdvertiseManager: message : 0
,09-07 11:37:05.808  2587  2765 D BtGatt.AdvertiseManager: number of adv instance running = 0
09-07 11:37:05.808  2587  2765 D BtGatt.AdvertiseManager: size of list is =0
,09-07 11:37:05.808  2587  2765 D BtGatt.AdvertiseManager: starting advertising,
,09-07 11:37:05.808  2587  2765 D BtGatt.AdvertiseManager: isStandardAdv = false
,09-07 11:37:05.808  3003  3007 I WCNSS_FILTER: ibs_msm_serial_clock_vote: vote UART CLK ON using UART driver's ioctl()
09-07 11:37:05.818  1250  1720 V AlarmManager:  remove PendingIntent] PendingIntent{a5db5f5: PendingIntentRecord{45887f2 com.android.bluetooth broadcastIntent}}
,09-07 11:37:05.818  2587  2780 D BtGatt.GattService: [GSIM LOG]: increaseAdvCount : com.test.thalitest : 20,
,09-07 11:37:05.818  3003  3007 I WCNSS_FILTER: do_write: IBS write: fd
,09-07 11:37:05.818  3003  3007 I WCNSS_FILTER: Direction(0): bytes: 28 : bytes_written: 28
,09-07 11:37:05.818  3003  3003 I WCNSS_FILTER: do_write: IBS write: fc
09-07 11:37:05.828  3003  3003 I WCNSS_FILTER: Direction(1): bytes: 8 : bytes_written: 8
09-07 11:37:05.828  3003  3007 I WCNSS_FILTER: Direction(0): bytes: 7 : bytes_written: 7
09-07 11:37:05.828  1250  2010 V AlarmManager:  remove PendingIntent] PendingIntent{7d54f8a: PendingIntentRecord{45887f2 com.android.bluetooth broadcastIntent}}
09-07 11:37:05.828  3003  3003 I WCNSS_FILTER: Direction(1): bytes: 8 : bytes_written: 8
09-07 11:37:05.828  2587  2756 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=6, status=0
09-07 11:37:05.828  2587  2780 D BtGatt.GattService: [GSIM LOG]: setAdvTime : com.test.thalitest@LowLatency : 24554017
09-07 11:37:05.828  2587  2780 D BtGatt.GattService: [GSIM LOG]: setAdvType : com.test.thalitest@LowLatency : 2
09-07 11:37:05.828  2587  2780 D BtGatt.GattService: [GSIM LOG]: updateAdvTime
,09-07 11:37:05.828  2587  2780 D BtGatt.GattService: [GSIM LOG]: com.test.thalitest@LowLatency, R time : 2 => 2
09-07 11:37:05.828  2587  2765 D BtGatt.AdvertiseManager: starting multi advertising
09-07 11:37:05.828  1250  2333 V AlarmManager:  remove PendingIntent] PendingIntent{2cb19fb: PendingIntentRecord{45887f2 com.android.bluetooth broadcastIntent}}
,09-07 11:37:05.828  3003  3007 I WCNSS_FILTER: Direction(0): bytes: 38 : bytes_written: 38
09-07 11:37:05.828  3003  3003 I WCNSS_FILTER: Direction(1): bytes: 8 : bytes_written: 8
09-07 11:37:05.828  2587  2756 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=6, status=0
09-07 11:37:05.828  2587  2765 D BtGatt.AdvertiseManager: logClientsSet() - status: 0
09-07 11:37:05.828  2587  2765 D BtGatt.AdvertiseManager: clientIf: 6, Mode: 2, TxPowerLevel: 3, isConnectable: false, Timeout: 0
09-07 11:37:05.828  2587  2765 D BtGatt.AdvertiseManager: postCallback clientIf = 6 status = 0,
09-07 11:37:05.828  2587  2765 D BtGatt.GattService: onMultipleAdvertiseCallback() clientIf=6, status=0, isStart=true
09-07 11:37:05.828  5989  6000 D BluetoothLeAdvertiser: onMultiAdvertiseCallback status = 0 isStart = true
09-07 11:37:05.828  5989  6040 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
09-07 11:37:05.828  5989  6040 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
09-07 11:37:05.838  5989  6040 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
09-07 11:37:05.838  1250  1720 V AlarmManager:  remove PendingIntent] PendingIntent{586ba18: PendingIntentRecord{45887f2 com.android.bluetooth broadcastIntent}}
,09-07 11:37:05.838  5989  6040 I io.jxcore.node.ConnectionHelper: start: OK
09-07 11:37:05.838  5989  5989 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
09-07 11:37:05.838  5989  5989 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess
09-07 11:37:05.838  5989  5989 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
09-07 11:37:05.838  5989  5989 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: true
09-07 11:37:05.838  5989  5989 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [ADVERTISING]
09-07 11:37:05.838  5989  5989 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [ADVERTISING]
,09-07 11:37:05.838  5989  5989 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: true
09-07 11:37:05.838  5989  5989 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: true
,09-07 11:37:05.838  1250  1990 V AlarmManager:  remove PendingIntent] PendingIntent{da0bc71: PendingIntentRecord{45887f2 com.android.bluetooth broadcastIntent}}
,09-07 11:37:05.848  1250  2333 V AlarmManager:  remove PendingIntent] PendingIntent{740da56: PendingIntentRecord{45887f2 com.android.bluetooth broadcastIntent}}
,09-07 11:37:06.338  5989  5989 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: true,
09-07 11:37:06.338  5989  5989 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
09-07 11:37:06.338  5989  5989 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,09-07 11:37:06.838  3003  3066 I WCNSS_FILTER: do_write: IBS write: fe,
09-07 11:37:06.838  3003  3066 I WCNSS_FILTER: ibs_msm_serial_clock_vote: vote UART CLK OFF using UART driver's ioctl()
,09-07 11:37:07.738  1250  3581 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:836 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,09-07 11:37:11.838  5989  6040 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-07 11:37:11.838  5989  6040 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
09-07 11:37:11.838  5989  6040 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
09-07 11:37:11.838  5989  6040 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
09-07 11:37:11.838  5989  6040 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-07 11:37:11.838  5989  6040 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
09-07 11:37:11.838  5989  6040 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@d297dbd not in the list
09-07 11:37:11.838  5989  6040 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-07 11:37:11.838  5989  6040 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-07 11:37:11.838  5989  5989 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
09-07 11:37:11.838  5989  6040 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-07 11:37:11.838  5989  6040 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-07 11:37:11.838  5989  6133 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
09-07 11:37:11.838  5989  6133 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
09-07 11:37:11.838  5989  6133 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
09-07 11:37:11.838  5989  5989 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
09-07 11:37:11.838  5989  6040 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
,09-07 11:37:11.838  5989  6040 D BluetoothAdapter: STATE_ON
,09-07 11:37:11.838  5989  6040 D BluetoothAdapter: STATE_ON
09-07 11:37:11.838  5989  6040 D BluetoothLeScanner: could not find callback wrapper
09-07 11:37:11.838  5989  6040 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-07 11:37:11.838  5989  6040 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
09-07 11:37:11.848  5989  6040 D BluetoothAdapter: STATE_ON
09-07 11:37:11.848  5989  6040 D BluetoothAdapter: STATE_ON
09-07 11:37:11.848  5989  6040 D BluetoothLeAdvertiser: stop advertising
09-07 11:37:11.848  2587  3153 D BtGatt.GattService: [GSIM LOG]: getCallingProcessName: com.test.thalitest
09-07 11:37:11.848  2587  3153 D BtGatt.GattService: [GSIM LOG]: getCallingProcessName: com.test.thalitest
09-07 11:37:11.848  2587  2765 D BtGatt.AdvertiseManager: message : 1
09-07 11:37:11.848  2587  2780 E BtGatt.GattService: [GSIM LOG]: gsimLogHandler: com.test.thalitest, msg: MESSAGE_STOP_ADV
09-07 11:37:11.848  2587  2780 D BtGatt.GattService: [GSIM LOG]: gsimLogHandler: prevDate: 7, currDate: 7
09-07 11:37:11.848  2587  2780 D BtGatt.GattService: [GSIM LOG]: updateAdvTime
09-07 11:37:11.848  2587  2780 D BtGatt.GattService: [GSIM LOG]: com.test.thalitest@LowLatency, R time : 2 => 2
09-07 11:37:11.848  2587  2780 D BtGatt.GattService: [GSIM LOG]: remove : com.test.thalitest@LowLatency at  BLE_ADV_REQUESTED_DB
09-07 11:37:11.848  2587  2765 D BtGatt.AdvertiseManager: stop advertise for client =  6
09-07 11:37:11.848  2587  2765 D BtGatt.AdvertiseManager: stop advertising, standardAdvClientIf = 0 client.clientIf = 6
09-07 11:37:11.848  2587  2765 D BtGatt.AdvertiseManager: logClientsSet() - status: -1
,09-07 11:37:11.848  3003  3007 I WCNSS_FILTER: ibs_msm_serial_clock_vote: vote UART CLK ON using UART driver's ioctl()
09-07 11:37:11.848  1250  1994 V AlarmManager:  remove PendingIntent] PendingIntent{da75ad7: PendingIntentRecord{45887f2 com.android.bluetooth broadcastIntent}}
,09-07 11:37:11.858  3003  3007 I WCNSS_FILTER: do_write: IBS write: fd
,09-07 11:37:11.858  3003  3007 I WCNSS_FILTER: Direction(0): bytes: 7 : bytes_written: 7
09-07 11:37:11.858  3003  3003 I WCNSS_FILTER: do_write: IBS write: fc
09-07 11:37:11.858  3003  3003 I WCNSS_FILTER: Direction(1): bytes: 8 : bytes_written: 8
,09-07 11:37:11.868  2587  2756 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=6, status=0
09-07 11:37:11.868  2587  2756 D BtGatt.GattService: Client app is not null!
09-07 11:37:11.868  3003  3007 E WCNSS_FILTER: do_read: read returned 0, err = Success, read bytes: 0, expected: 0
09-07 11:37:11.868  3003  3007 I WCNSS_FILTER: Direction(0): bytes: 4 : bytes_written: 4
09-07 11:37:11.868  1250  1720 V AlarmManager:  remove PendingIntent] PendingIntent{7395fc4: PendingIntentRecord{45887f2 com.android.bluetooth broadcastIntent}}
09-07 11:37:11.868  5989  5999 D BluetoothLeAdvertiser: onMultiAdvertiseCallback status = 0 isStart = false
09-07 11:37:11.868  2587  2614 D BtGatt.GattService: unregisterClient() - clientIf=6
09-07 11:37:11.868  5989  6040 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-07 11:37:11.868  5989  6040 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
09-07 11:37:11.868  5989  6040 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: false
09-07 11:37:11.868  5989  6040 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [ADVERTISING] to [NOT_STARTED]
09-07 11:37:11.868  5989  6040 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [ADVERTISING] -> [NOT_STARTED]
09-07 11:37:11.868  5989  6040 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
09-07 11:37:11.868  5989  6040 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-07 11:37:11.868  5989  6040 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-07 11:37:11.868  5989  6040 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-07 11:37:11.868  1250  1994 V AlarmManager:  remove PendingIntent] PendingIntent{433aead: PendingIntentRecord{45887f2 com.android.bluetooth broadcastIntent}}
,09-07 11:37:11.868  5989  6040 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c284fb2 not in the list
09-07 11:37:11.868  5989  6040 D io.jxcore.node.ConnectivityMonitor: stop
09-07 11:37:11.868  5989  6040 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-07 11:37:11.868  5989  5989 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-07 11:37:11.868  5989  5989 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-07 11:37:11.868  5989  5989 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,09-07 11:37:11.868  5989  6040 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: true
,09-07 11:37:11.878  5989  6040 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-07 11:37:11.878  3003  3003 I WCNSS_FILTER: Direction(1): bytes: 15 : bytes_written: 15
,09-07 11:37:11.878  3003  3007 I WCNSS_FILTER: Direction(0): bytes: 12 : bytes_written: 12
09-07 11:37:11.878  3003  3003 I WCNSS_FILTER: Direction(1): bytes: 8 : bytes_written: 8
,09-07 11:37:11.878  1250  1994 V AlarmManager:  remove PendingIntent] PendingIntent{f8988a9: PendingIntentRecord{45887f2 com.android.bluetooth broadcastIntent}}
,09-07 11:37:11.878  5989  6040 D BluetoothAdapter: STATE_ON
,09-07 11:37:11.878  1250  1313 V AlarmManager:  remove PendingIntent] PendingIntent{e8de2e: PendingIntentRecord{45887f2 com.android.bluetooth broadcastIntent}}
,09-07 11:37:11.888  5989  6040 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-07 11:37:11.888  5989  6040 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-07 11:37:11.888  5989  6040 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-07 11:37:11.888  5989  6040 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-07 11:37:11.888  5989  6040 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-07 11:37:11.888  5989  6040 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-07 11:37:11.888  5989  6040 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-07 11:37:11.888  5989  6040 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-07 11:37:11.888  1250  2674 V AlarmManager:  remove PendingIntent] PendingIntent{c6ccdcf: PendingIntentRecord{45887f2 com.android.bluetooth broadcastIntent}},
,09-07 11:37:11.888  5989  6040 D BluetoothAdapter: STATE_ON
09-07 11:37:11.888  5989  6040 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-07 11:37:11.888  5989  6040 D io.jxcore.node.ConnectivityMonitor: start: OK
09-07 11:37:11.888  5989  6040 I io.jxcore.node.StartStopOperationHandler: updateBeaconAdExtraInformation: New value: 3
09-07 11:37:11.888  5989  6040 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBeaconAdExtraInformation: 2 -> 3
09-07 11:37:11.888  5989  6040 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
09-07 11:37:11.888  5989  6040 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should start/stop everything
09-07 11:37:11.888  5989  6040 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
09-07 11:37:11.888  5989  6040 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-07 11:37:11.888  5989  6040 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
09-07 11:37:11.888  5989  6040 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
09-07 11:37:11.888  5989  6040 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
09-07 11:37:11.888  5989  6040 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
09-07 11:37:11.888  5989  6040 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: true
09-07 11:37:11.888  5989  6040 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-07 11:37:11.888  5989  6040 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,09-07 11:37:11.898  5989  6136 D BluetoothSocket: bindListen(): myUserId = 0
09-07 11:37:11.898  5989  6136 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-07 11:37:11.898  5989  5989 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-07 11:37:11.898  5989  6040 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
09-07 11:37:11.898  5989  6040 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,09-07 11:37:11.898  5989  6136 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
,09-07 11:37:11.898  5989  5989 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-07 11:37:11.898  5989  5989 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
,09-07 11:37:11.898  5989  6040 D BluetoothAdapter: STATE_ON
,09-07 11:37:11.898  5989  6040 D BluetoothAdapter: STATE_ON
,09-07 11:37:11.898  5989  6040 D BluetoothAdapter: STATE_ON
,09-07 11:37:11.898  5989  6040 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,09-07 11:37:11.908  5989  6040 D BluetoothAdapter: STATE_ON
,09-07 11:37:11.908  5989  6040 D BluetoothAdapter: STATE_ON
09-07 11:37:11.908  5989  6040 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
09-07 11:37:11.908  5989  6040 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,09-07 11:37:11.908  5989  6040 D BluetoothAdapter: STATE_ON
,09-07 11:37:11.908  5989  6040 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
09-07 11:37:11.908  5989  6040 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "44:78:3E:EB:95:EE"
,09-07 11:37:11.908  5989  6040 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 03 44 78 3E EB 95 EE
09-07 11:37:11.908  5989  6040 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[3, 68, 120, 62, -21, -107, -18]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
09-07 11:37:11.908  5989  6040 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[3, 68, 120, 62, -21, -107, -18]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
09-07 11:37:11.908  5989  6040 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting...
,09-07 11:37:11.908  5989  6040 D BluetoothAdapter: STATE_ON
,09-07 11:37:11.908  5989  6040 D BluetoothAdapter: STATE_ON
09-07 11:37:11.908  5989  6040 D BluetoothLeAdvertiser: start advertising
,09-07 11:37:11.908  5989  6040 D BluetoothAdapter: STATE_ON
,09-07 11:37:11.918  2587  3109 D BtGatt.GattService: registerClient() - UUID=718f58d8-7a58-4383-a0af-dd8b2efad382
,09-07 11:37:11.958  2587  2756 D BtGatt.GattService: onClientRegistered() - UUID=718f58d8-7a58-4383-a0af-dd8b2efad382, clientIf=6
09-07 11:37:11.958  5989  6000 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=6
,09-07 11:37:11.958  2587  2604 D BtGatt.GattService: [GSIM LOG]: startMultiAdvertising: 2
,09-07 11:37:11.958  2587  2604 D BtGatt.GattService: [GSIM LOG]: getCallingProcessName: com.test.thalitest
09-07 11:37:11.958  2587  2604 D BtGatt.GattService: [GSIM LOG]: getCallingProcessName: com.test.thalitest
09-07 11:37:11.958  2587  2780 E BtGatt.GattService: [GSIM LOG]: gsimLogHandler: com.test.thalitest, msg: MESSAGE_START_ADV
09-07 11:37:11.958  2587  2780 D BtGatt.GattService: [GSIM LOG]: gsimLogHandler: prevDate: 7, currDate: 7
,09-07 11:37:11.958  2587  2765 D BtGatt.AdvertiseManager: message : 0
,09-07 11:37:11.968  2587  2765 D BtGatt.AdvertiseManager: number of adv instance running = 0
09-07 11:37:11.968  2587  2765 D BtGatt.AdvertiseManager: size of list is =0
,09-07 11:37:11.968  2587  2765 D BtGatt.AdvertiseManager: starting advertising
,09-07 11:37:11.968  2587  2765 D BtGatt.AdvertiseManager: isStandardAdv = false
,09-07 11:37:11.968  2587  2780 D BtGatt.GattService: [GSIM LOG]: increaseAdvCount : com.test.thalitest : 21
,09-07 11:37:11.968  2587  2780 D BtGatt.GattService: [GSIM LOG]: setAdvTime : com.test.thalitest@LowLatency : 24554017
09-07 11:37:11.968  2587  2780 D BtGatt.GattService: [GSIM LOG]: setAdvType : com.test.thalitest@LowLatency : 2
09-07 11:37:11.968  2587  2780 D BtGatt.GattService: [GSIM LOG]: updateAdvTime
09-07 11:37:11.968  2587  2780 D BtGatt.GattService: [GSIM LOG]: com.test.thalitest@LowLatency, R time : 2 => 2
09-07 11:37:11.968  3003  3007 I WCNSS_FILTER: Direction(0): bytes: 28 : bytes_written: 28
,09-07 11:37:11.968  1250  2396 V AlarmManager:  remove PendingIntent] PendingIntent{89277eb: PendingIntentRecord{45887f2 com.android.bluetooth broadcastIntent}}
09-07 11:37:11.968  3003  3003 I WCNSS_FILTER: do_write: IBS write: fc
09-07 11:37:11.968  3003  3003 I WCNSS_FILTER: Direction(1): bytes: 8 : bytes_written: 8
,09-07 11:37:11.968  3003  3007 I WCNSS_FILTER: Direction(0): bytes: 7 : bytes_written: 7
,09-07 11:37:11.978  3003  3003 I WCNSS_FILTER: Direction(1): bytes: 8 : bytes_written: 8
09-07 11:37:11.978  2587  2756 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=6, status=0
,09-07 11:37:11.978  2587  2765 D BtGatt.AdvertiseManager: starting multi advertising
,09-07 11:37:11.978  3003  3007 I WCNSS_FILTER: Direction(0): bytes: 38 : bytes_written: 38
09-07 11:37:11.978  1250  1310 V AlarmManager:  remove PendingIntent] PendingIntent{1a8d948: PendingIntentRecord{45887f2 com.android.bluetooth broadcastIntent}}
09-07 11:37:11.978  3003  3003 I WCNSS_FILTER: Direction(1): bytes: 8 : bytes_written: 8
09-07 11:37:11.978  2587  2756 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=6, status=0
09-07 11:37:11.978  2587  2765 D BtGatt.AdvertiseManager: logClientsSet() - status: 0
09-07 11:37:11.978  2587  2765 D BtGatt.AdvertiseManager: clientIf: 6, Mode: 2, TxPowerLevel: 3, isConnectable: false, Timeout: 0
09-07 11:37:11.978  2587  2765 D BtGatt.AdvertiseManager: postCallback clientIf = 6 status = 0
09-07 11:37:11.978  2587  2765 D BtGatt.GattService: onMultipleAdvertiseCallback() clientIf=6, status=0, isStart=true
09-07 11:37:11.978  5989  5999 D BluetoothLeAdvertiser: onMultiAdvertiseCallback status = 0 isStart = true
09-07 11:37:11.978  5989  6040 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
09-07 11:37:11.978  5989  6040 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,09-07 11:37:11.978  5989  6040 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,09-07 11:37:11.978  1250  1720 V AlarmManager:  remove PendingIntent] PendingIntent{cc8a3e1: PendingIntentRecord{45887f2 com.android.bluetooth broadcastIntent}}
,09-07 11:37:11.988  5989  6040 I io.jxcore.node.ConnectionHelper: start: OK
09-07 11:37:11.988  5989  5989 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
09-07 11:37:11.988  5989  5989 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess
09-07 11:37:11.988  5989  5989 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
09-07 11:37:11.988  5989  5989 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: true
09-07 11:37:11.988  5989  5989 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [ADVERTISING]
,09-07 11:37:11.988  5989  5989 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [ADVERTISING]
,09-07 11:37:11.988  5989  5989 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: true
09-07 11:37:11.988  5989  5989 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: true
09-07 11:37:11.988  1250  2333 V AlarmManager:  remove PendingIntent] PendingIntent{4628506: PendingIntentRecord{45887f2 com.android.bluetooth broadcastIntent}}
,09-07 11:37:11.998  1250  1986 V AlarmManager:  remove PendingIntent] PendingIntent{b1ea7c7: PendingIntentRecord{45887f2 com.android.bluetooth broadcastIntent}}
,09-07 11:37:11.998  1250  2010 V AlarmManager:  remove PendingIntent] PendingIntent{e1641f4: PendingIntentRecord{45887f2 com.android.bluetooth broadcastIntent}}
,09-07 11:37:12.488  5989  5989 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: true,
09-07 11:37:12.488  5989  5989 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
09-07 11:37:12.488  5989  5989 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,09-07 11:37:12.978  3003  3066 I WCNSS_FILTER: do_write: IBS write: fe,
09-07 11:37:12.978  3003  3066 I WCNSS_FILTER: ibs_msm_serial_clock_vote: vote UART CLK OFF using UART driver's ioctl()
,09-07 11:37:14.818  1250  3553 D SSRM:s  : SIOP:: AP = 310, PST = 340 (W:12), CP = 37, LCD = 0
,09-07 11:37:14.818  1250  3553 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
,09-07 11:37:17.988  5989  6040 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-07 11:37:17.988  5989  6040 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Stop operation: Should start/stop everything
09-07 11:37:17.988  5989  6040 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
09-07 11:37:17.988  5989  6040 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
09-07 11:37:17.988  5989  6040 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
09-07 11:37:17.988  5989  6040 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
09-07 11:37:17.988  5989  6040 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-07 11:37:17.988  5989  6040 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
09-07 11:37:17.988  5989  6040 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
09-07 11:37:17.988  5989  6040 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-07 11:37:17.988  5989  6040 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-07 11:37:17.988  5989  6040 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-07 11:37:17.988  5989  6040 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-07 11:37:17.988  5989  5989 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
09-07 11:37:17.988  5989  6040 D BluetoothAdapter: STATE_ON
,09-07 11:37:17.988  5989  6136 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
09-07 11:37:17.988  5989  6136 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
09-07 11:37:17.988  5989  6136 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
09-07 11:37:17.988  5989  6040 D BluetoothAdapter: STATE_ON
09-07 11:37:17.988  5989  6040 D BluetoothLeScanner: could not find callback wrapper
09-07 11:37:17.988  5989  6040 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-07 11:37:17.988  5989  6040 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
09-07 11:37:17.988  5989  6040 D BluetoothAdapter: STATE_ON
,09-07 11:37:17.988  5989  6040 D BluetoothAdapter: STATE_ON
09-07 11:37:17.988  5989  6040 D BluetoothLeAdvertiser: stop advertising
,09-07 11:37:17.998  2587  2604 D BtGatt.GattService: [GSIM LOG]: getCallingProcessName: com.test.thalitest
09-07 11:37:17.998  2587  2604 D BtGatt.GattService: [GSIM LOG]: getCallingProcessName: com.test.thalitest
09-07 11:37:17.998  2587  2765 D BtGatt.AdvertiseManager: message : 1
09-07 11:37:17.998  2587  2780 E BtGatt.GattService: [GSIM LOG]: gsimLogHandler: com.test.thalitest, msg: MESSAGE_STOP_ADV
09-07 11:37:17.998  2587  2780 D BtGatt.GattService: [GSIM LOG]: gsimLogHandler: prevDate: 7, currDate: 7
09-07 11:37:17.998  2587  2780 D BtGatt.GattService: [GSIM LOG]: updateAdvTime
09-07 11:37:17.998  2587  2780 D BtGatt.GattService: [GSIM LOG]: com.test.thalitest@LowLatency, R time : 2 => 2
09-07 11:37:17.998  2587  2780 D BtGatt.GattService: [GSIM LOG]: remove : com.test.thalitest@LowLatency at  BLE_ADV_REQUESTED_DB
09-07 11:37:17.998  2587  2765 D BtGatt.AdvertiseManager: stop advertise for client =  6
09-07 11:37:17.998  2587  2765 D BtGatt.AdvertiseManager: stop advertising, standardAdvClientIf = 0 client.clientIf = 6
,09-07 11:37:17.998  2587  2765 D BtGatt.AdvertiseManager: logClientsSet() - status: -1
09-07 11:37:17.998  3003  3007 I WCNSS_FILTER: ibs_msm_serial_clock_vote: vote UART CLK ON using UART driver's ioctl()
09-07 11:37:17.998  1250  1964 V AlarmManager:  remove PendingIntent] PendingIntent{e4a9d1d: PendingIntentRecord{45887f2 com.android.bluetooth broadcastIntent}}
,09-07 11:37:17.998  3003  3007 I WCNSS_FILTER: do_write: IBS write: fd
,09-07 11:37:18.008  3003  3007 I WCNSS_FILTER: Direction(0): bytes: 7 : bytes_written: 7,
09-07 11:37:18.008  3003  3003 I WCNSS_FILTER: do_write: IBS write: fc
,09-07 11:37:18.008  3003  3003 I WCNSS_FILTER: Direction(1): bytes: 8 : bytes_written: 8
09-07 11:37:18.008  2587  2756 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=6, status=0
09-07 11:37:18.008  1250  2396 V AlarmManager:  remove PendingIntent] PendingIntent{311eb92: PendingIntentRecord{45887f2 com.android.bluetooth broadcastIntent}}
09-07 11:37:18.008  2587  2756 D BtGatt.GattService: Client app is not null!
09-07 11:37:18.008  3003  3007 E WCNSS_FILTER: do_read: read returned 0, err = Success, read bytes: 0, expected: 0
09-07 11:37:18.008  3003  3007 I WCNSS_FILTER: Direction(0): bytes: 4 : bytes_written: 4
09-07 11:37:18.008  5989  6000 D BluetoothLeAdvertiser: onMultiAdvertiseCallback status = 0 isStart = false
09-07 11:37:18.008  2587  2614 D BtGatt.GattService: unregisterClient() - clientIf=6
,09-07 11:37:18.008  5989  6040 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-07 11:37:18.008  1250  1986 V AlarmManager:  remove PendingIntent] PendingIntent{953f963: PendingIntentRecord{45887f2 com.android.bluetooth broadcastIntent}}
09-07 11:37:18.008  5989  6040 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
09-07 11:37:18.008  5989  6040 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: false
,09-07 11:37:18.008  5989  6040 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [ADVERTISING] to [NOT_STARTED]
09-07 11:37:18.008  5989  6040 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [ADVERTISING] -> [NOT_STARTED]
,09-07 11:37:18.018  5989  6040 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
09-07 11:37:18.018  5989  6040 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-07 11:37:18.018  5989  6040 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-07 11:37:18.018  5989  6040 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-07 11:37:18.018  5989  5989 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-07 11:37:18.018  5989  5989 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
09-07 11:37:18.018  5989  5989 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,09-07 11:37:18.018  5989  5989 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-07 11:37:18.018  5989  5989 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
09-07 11:37:18.018  5989  5989 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,09-07 11:37:18.018  3003  3003 I WCNSS_FILTER: Direction(1): bytes: 15 : bytes_written: 15
09-07 11:37:18.018  3003  3007 I WCNSS_FILTER: Direction(0): bytes: 12 : bytes_written: 12
,09-07 11:37:18.018  1250  1721 V AlarmManager:  remove PendingIntent] PendingIntent{44f8960: PendingIntentRecord{45887f2 com.android.bluetooth broadcastIntent}}
09-07 11:37:18.028  3003  3003 I WCNSS_FILTER: Direction(1): bytes: 8 : bytes_written: 8
,09-07 11:37:18.028  1250  1310 V AlarmManager:  remove PendingIntent] PendingIntent{1f8ee19: PendingIntentRecord{45887f2 com.android.bluetooth broadcastIntent}}
,09-07 11:37:18.028  1250  1986 V AlarmManager:  remove PendingIntent] PendingIntent{fdf2ede: PendingIntentRecord{45887f2 com.android.bluetooth broadcastIntent}}
,09-07 11:37:18.518  5989  5989 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false,
,09-07 11:37:19.028  3003  3066 I WCNSS_FILTER: do_write: IBS write: fe
09-07 11:37:19.028  3003  3066 I WCNSS_FILTER: ibs_msm_serial_clock_vote: vote UART CLK OFF using UART driver's ioctl()
,09-07 11:37:21.018  5989  6040 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-07 11:37:21.018  5989  6040 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 11:37:21.018  5989  6040 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-07 11:37:21.018  5989  6040 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@d297dbd not in the list
09-07 11:37:21.018  5989  6040 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-07 11:37:21.018  5989  6040 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c284fb2 not in the list
09-07 11:37:21.018  5989  6040 D io.jxcore.node.ConnectivityMonitor: stop
09-07 11:37:21.018  5989  6040 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 11:37:21.018  5989  6040 D io.jxcore.node.ConnectionHelper: onPeerReadyToProvideBluetoothMacAddress: Bro Mode is not supported
09-07 11:37:21.028  5989  6040 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-07 11:37:21.028  5989  6040 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 11:37:21.028  5989  6040 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 11:37:21.028  5989  6040 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@d297dbd not in the list
09-07 11:37:21.028  5989  6040 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-07 11:37:21.028  5989  6040 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c284fb2 not in the list
09-07 11:37:21.028  5989  6040 D io.jxcore.node.ConnectivityMonitor: stop
09-07 11:37:21.028  5989  6040 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 11:37:21.028  5989  6040 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 11:37:21.028  5989  6040 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
09-07 11:37:21.028  5989  6040 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-07 11:37:21.028  5989  6040 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 11:37:21.028  5989  6040 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 11:37:21.028  5989  6040 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@d297dbd not in the list
09-07 11:37:21.028  5989  6040 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-07 11:37:21.028  5989  6040 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c284fb2 not in the list
09-07 11:37:21.028  5989  6040 D io.jxcore.node.ConnectivityMonitor: stop
09-07 11:37:21.028  5989  6040 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 11:37:21.028  5989  6040 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 11:37:21.028  5989  6040 I io.jxcore.node.ConnectionHelper: onConne,ctionManagerStateChanged: null
09-07 11:37:21.028  5989  6040 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-07 11:37:21.028  5989  6040 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 11:37:21.028  5989  6040 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 11:37:21.028  5989  6040 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@d297dbd not in the list
09-07 11:37:21.028  5989  6040 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-07 11:37:21.028  5989  6040 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c284fb2 not in the list
09-07 11:37:21.028  5989  6040 D io.jxcore.node.ConnectivityMonitor: stop
09-07 11:37:21.028  5989  6040 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 11:37:21.028  5989  6040 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 11:37:21.028  5989  6040 V io.jxcore.node.ConnectionHelper: Received a request for permission "randomString", but we are expecting that all the required permissions have already been granted
09-07 11:37:21.028  5989  6040 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-07 11:37:21.028  5989  6040 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 11:37:21.028  5989  6040 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 11:37:21.028  5989  6040 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@d297dbd not in the list
09-07 11:37:21.028  5989  6040 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-07 11:37:21.028  5989  6040 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c284fb2 not in the list
09-07 11:37:21.028  5989  6040 D io.jxcore.node.ConnectivityMonitor: stop
09-07 11:37:21.028  5989  6040 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 11:37:21.028  5989  6040 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 11:37:21.028  5989  6040 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
09-07 11:37:21.028  5989  6040 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-07 11:37:21.028  5989  6040 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
09-07 11:37:21.028  5989  6040 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
,09-07 11:37:21.028  5989  6040 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
09-07 11:37:21.028  5989  6040 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-07 11:37:21.028  5989  6040 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-07 11:37:21.028  5989  6040 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 11:37:21.028  5989  6040 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 11:37:21.028  5989  6040 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@d297dbd not in the list
09-07 11:37:21.028  5989  6040 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-07 11:37:21.028  5989  6040 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c284fb2 not in the list
,09-07 11:37:21.028  5989  6040 D io.jxcore.node.ConnectivityMonitor: stop
09-07 11:37:21.028  5989  6040 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 11:37:21.028  5989  6040 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 11:37:21.028  5989  6040 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-07 11:37:21.028  5989  6040 E io.jxcore.node.ConnectionHelper: connect: We already have an outgoing connection to peer with ID 00:11:22:33:44:55
09-07 11:37:21.028  5989  6040 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
09-07 11:37:21.038  5989  6040 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-07 11:37:21.038  5989  6040 E io.jxcore.node.ConnectionHelper: connect: Maximum number of peer connections (30) reached, please try again after disconnecting a peer
09-07 11:37:21.038  5989  6040 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
,09-07 11:37:21.038  5989  6040 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
09-07 11:37:21.038  5989  6040 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
09-07 11:37:21.038  5989  6040 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
09-07 11:37:21.038  5989  6040 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
09-07 11:37:21.038  5989  6040 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
09-07 11:37:21.038  5989  6040 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
09-07 11:37:21.038  5989  6040 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
09-07 11:37:21.038  5989  6040 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
09-07 11:37:21.038  5989  6040 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
09-07 11:37:21.038  5989  6040 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
09-07 11:37:21.038  5989  6040 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
09-07 11:37:21.038  5989  6040 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
09-07 11:37:21.038  5989  6040 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
,09-07 11:37:21.038  5989  6040 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
09-07 11:37:21.038  5989  6040 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
09-07 11:37:21.038  5989  6040 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
09-07 11:37:21.038  5989  6040 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
09-07 11:37:21.038  5989  6040 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
09-07 11:37:21.038  5989  6040 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
09-07 11:37:21.038  5989  6040 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
09-07 11:37:21.038  5989  6040 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
,09-07 11:37:21.038  5989  6040 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
09-07 11:37:21.038  5989  6040 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
09-07 11:37:21.038  5989  6040 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
09-07 11:37:21.038  5989  6040 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
09-07 11:37:21.038  5989  6040 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
,09-07 11:37:21.038  5989  6040 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
09-07 11:37:21.038  5989  6040 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
09-07 11:37:21.038  5989  6040 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
09-07 11:37:21.038  5989  6040 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID abcd
09-07 11:37:21.038  5989  6040 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
09-07 11:37:21.038  5989  6040 E io.jxcore.node.ConnectionHelper: connect: Invalid Bluetooth MAC address: abcd
09-07 11:37:21.038  5989  6040 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
,09-07 11:37:21.038  5989  6040 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
09-07 11:37:21.038  5989  6040 E io.jxcore.node.ConnectionHelper: connect: Failed to add the callback for the connection
09-07 11:37:21.038  5989  6040 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-07 11:37:21.038  5989  6040 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
,09-07 11:37:21.038  5989  6040 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: connect: [<no peer name> 00:11:22:33:44:55]
09-07 11:37:21.048  5989  6040 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Trying to start connecting to null in address 00:11:22:33:44:55
09-07 11:37:21.048  5989  6040 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setInsecureRfcommSocketPortNumber: Using port -1
,09-07 11:37:21.048  5989  6040 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setMaxNumberOfRetries: 0
,09-07 11:37:21.048  5989  6040 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnecting: null 00:11:22:33:44:55
09-07 11:37:21.048  5989  6040 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Started connecting to null in address 00:11:22:33:44:55
09-07 11:37:21.048  5989  6040 I io.jxcore.node.ConnectionHelper: connect: Connection process successfully started (peer ID: 00:11:22:33:44:55)
,09-07 11:37:21.048  5989  6040 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-07 11:37:21.048  5989  6040 E io.jxcore.node.ConnectionHelper: connect: Callback is null
09-07 11:37:21.048  5989  6140 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Trying to connect to peer with address 00:11:22:33:44:55 (thread ID: 212)
09-07 11:37:21.048  5989  6040 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-07 11:37:21.048  5989  6040 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 11:37:21.048  5989  6040 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 11:37:21.048  5989  6040 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: cancelAllConnectionAttempts: Shutting down 1 client threads
,09-07 11:37:21.048  5989  6040 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@d297dbd not in the list
09-07 11:37:21.048  5989  6040 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-07 11:37:21.048  5989  6040 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c284fb2 not in the list
09-07 11:37:21.048  5989  6040 D io.jxcore.node.ConnectivityMonitor: stop
09-07 11:37:21.048  5989  6040 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 11:37:21.048  5989  6040 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 11:37:21.048  5989  6141 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: shutdown: Thread ID: 212
09-07 11:37:21.048  5989  6040 E io.jxcore.node.ConnectionHelper: onProvideBluetoothMacAddressRequest: Request ID: 1111 - Bro Mode is not supported
,09-07 11:37:21.048  5989  6040 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-07 11:37:21.048  5989  6040 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 11:37:21.048  5989  6040 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 11:37:21.048  5989  6040 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@d297dbd not in the list
09-07 11:37:21.048  5989  6040 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-07 11:37:21.058  5989  6040 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c284fb2 not in the list
09-07 11:37:21.058  5989  6040 D io.jxcore.node.ConnectivityMonitor: stop
09-07 11:37:21.058  5989  6040 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 11:37:21.058  5989  6040 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 11:37:21.058  5989  6040 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: true
,09-07 11:37:21.058  5989  6040 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-07 11:37:21.058  5989  6040 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 11:37:21.058  5989  6040 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 11:37:21.058  5989  6040 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@d297dbd not in the list
09-07 11:37:21.058  5989  6040 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-07 11:37:21.058  5989  6040 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c284fb2 not in the list
,09-07 11:37:21.058  5989  6040 D io.jxcore.node.ConnectivityMonitor: stop
09-07 11:37:21.058  5989  6040 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 11:37:21.058  5989  6040 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 11:37:21.058  5989  6040 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID randomString
09-07 11:37:21.058  5989  6040 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID randomString
09-07 11:37:21.058  5989  6040 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
09-07 11:37:21.058  5989  6040 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: randomString), either no such connection or failed to close the connection
09-07 11:37:21.058  5989  6040 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
09-07 11:37:21.058  5989  6040 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 00:11:22:33:44:55
,09-07 11:37:21.058  5989  6040 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
09-07 11:37:21.058  5989  6040 I io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Successfully disconnected (peer ID: 00:11:22:33:44:55
09-07 11:37:21.058  5989  6040 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
09-07 11:37:21.058  5989  6040 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 00:11:22:33:44:55
09-07 11:37:21.058  5989  6040 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
09-07 11:37:21.058  5989  6040 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: 00:11:22:33:44:55), either no such connection or failed to close the connection
09-07 11:37:21.058  5989  6040 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-07 11:37:21.058  5989  6040 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 11:37:21.058  5989  6040 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 11:37:21.058  5989  6040 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@d297dbd not in the list
09-07 11:37:21.058  5989  6040 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-07 11:37:21.058  5989  6040 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c284fb2 not in the list
09-07 11:37:21.058  5989  6040 D io.jxcore.node.ConnectivityMonitor: stop
09-07 11:37:21.058  5989  6040 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 11:37:21.058  5989  6040 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 11:37:21.058  5989  6040 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: true
09-07 11:37:21.058  5989  6140 D BluetoothUtils: isSocketAllowedBySecurityPolicy start : device null
09-07 11:37:21.058  5989  6140 D BluetoothSocket: connect(): myUserId = 0
09-07 11:37:21.058  5989  6140 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-07 11:37:21.058  5989  6040 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-07 11:37:21.068  5989  6040 D BluetoothAdapter: STATE_ON
,09-07 11:37:21.068  5989  6040 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-07 11:37:21.068  5989  6040 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-07 11:37:21.068  5989  6040 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-07 11:37:21.068  5989  6040 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-07 11:37:21.068  5989  6040 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-07 11:37:21.068  5989  6040 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-07 11:37:21.068  5989  6040 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-07 11:37:21.068  5989  6040 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-07 11:37:21.068  1250  1721 D SecContentProvider: insert(), uri = 2
,09-07 11:37:21.068  2587  3057 W bt_btif : bta_dm_acl_change(), event : 2
09-07 11:37:21.068  3003  3007 I WCNSS_FILTER: ibs_msm_serial_clock_vote: vote UART CLK ON using UART driver's ioctl()
09-07 11:37:21.068  1250  1990 V AlarmManager:  remove PendingIntent] PendingIntent{9ab5aea: PendingIntentRecord{45887f2 com.android.bluetooth broadcastIntent}}
09-07 11:37:21.068  5989  6040 D BluetoothAdapter: STATE_ON
,09-07 11:37:21.068  3003  3007 I WCNSS_FILTER: do_write: IBS write: fd
09-07 11:37:21.068  5989  6040 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-07 11:37:21.068  5989  6040 D io.jxcore.node.ConnectivityMonitor: start: OK
09-07 11:37:21.068  5989  6040 I io.jxcore.node.StartStopOperationHandler: updateBeaconAdExtraInformation: New value: 4
09-07 11:37:21.068  5989  6040 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBeaconAdExtraInformation: 3 -> 4
,09-07 11:37:21.068  5989  6040 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
09-07 11:37:21.068  5989  6040 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should start/stop everything
09-07 11:37:21.078  1250  2010 V AlarmManager:  remove PendingIntent] PendingIntent{ea531db: PendingIntentRecord{45887f2 com.android.bluetooth broadcastIntent}}
09-07 11:37:21.068  5989  6040 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
09-07 11:37:21.068  5989  6040 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-07 11:37:21.078  5989  6040 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
09-07 11:37:21.078  5989  6040 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
09-07 11:37:21.078  5989  6040 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
09-07 11:37:21.078  5989  6040 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
09-07 11:37:21.078  5989  6040 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: true
09-07 11:37:21.078  5989  6040 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-07 11:37:21.078  5989  6040 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-07 11:37:21.078  3003  3007 I WCNSS_FILTER: Direction(0): bytes: 17 : bytes_written: 17
09-07 11:37:21.078  3003  3003 I WCNSS_FILTER: do_write: IBS write: fc
09-07 11:37:21.078  5989  6142 D BluetoothSocket: bindListen(): myUserId = 0
09-07 11:37:21.078  5989  6142 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-07 11:37:21.078  3003  3003 I WCNSS_FILTER: Direction(1): bytes: 7 : bytes_written: 7
,09-07 11:37:21.078  5989  5989 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-07 11:37:21.078  1250  1964 V AlarmManager:  remove PendingIntent] PendingIntent{83b10b7: PendingIntentRecord{45887f2 com.android.bluetooth broadcastIntent}}
09-07 11:37:21.078  5989  6142 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
,09-07 11:37:21.078  5989  6040 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
09-07 11:37:21.078  5989  6040 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,09-07 11:37:21.088  5989  5989 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-07 11:37:21.088  5989  5989 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
09-07 11:37:21.088  5989  6040 D BluetoothAdapter: STATE_ON
,09-07 11:37:21.088  5989  6040 D BluetoothAdapter: STATE_ON
,09-07 11:37:21.088  5989  6040 D BluetoothAdapter: STATE_ON
,09-07 11:37:21.088  5989  6040 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,09-07 11:37:21.088  5989  6040 D BluetoothAdapter: STATE_ON
09-07 11:37:21.088  5989  6040 D BluetoothAdapter: STATE_ON
,09-07 11:37:21.088  5989  6040 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
09-07 11:37:21.088  5989  6040 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,09-07 11:37:21.088  5989  6040 D BluetoothAdapter: STATE_ON
,09-07 11:37:21.088  5989  6040 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
,09-07 11:37:21.088  5989  6040 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "44:78:3E:EB:95:EE"
09-07 11:37:21.088  5989  6040 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 04 44 78 3E EB 95 EE
09-07 11:37:21.088  5989  6040 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[4, 68, 120, 62, -21, -107, -18]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
09-07 11:37:21.088  5989  6040 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[4, 68, 120, 62, -21, -107, -18]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
09-07 11:37:21.088  5989  6040 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting...
,09-07 11:37:21.098  5989  6040 D BluetoothAdapter: STATE_ON
,09-07 11:37:21.098  5989  6040 D BluetoothAdapter: STATE_ON
09-07 11:37:21.098  5989  6040 D BluetoothLeAdvertiser: start advertising
,09-07 11:37:21.098  5989  6040 D BluetoothAdapter: STATE_ON
,09-07 11:37:21.098  2587  2614 D BtGatt.GattService: registerClient() - UUID=64a8974f-e53f-4608-85dd-a74dcd11891d
,09-07 11:37:21.138  2587  2756 D BtGatt.GattService: onClientRegistered() - UUID=64a8974f-e53f-4608-85dd-a74dcd11891d, clientIf=6
,09-07 11:37:21.138  5989  6000 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=6
,09-07 11:37:21.148  2587  2604 D BtGatt.GattService: [GSIM LOG]: startMultiAdvertising: 2
,09-07 11:37:21.148  2587  2604 D BtGatt.GattService: [GSIM LOG]: getCallingProcessName: com.test.thalitest
09-07 11:37:21.148  2587  2604 D BtGatt.GattService: [GSIM LOG]: getCallingProcessName: com.test.thalitest
09-07 11:37:21.148  2587  2780 E BtGatt.GattService: [GSIM LOG]: gsimLogHandler: com.test.thalitest, msg: MESSAGE_START_ADV
,09-07 11:37:21.148  2587  2780 D BtGatt.GattService: [GSIM LOG]: gsimLogHandler: prevDate: 7, currDate: 7
09-07 11:37:21.148  2587  2765 D BtGatt.AdvertiseManager: message : 0
09-07 11:37:21.148  2587  2765 D BtGatt.AdvertiseManager: number of adv instance running = 0
09-07 11:37:21.148  2587  2765 D BtGatt.AdvertiseManager: size of list is =0
,09-07 11:37:21.148  2587  2765 D BtGatt.AdvertiseManager: starting advertising
,09-07 11:37:21.158  2587  2765 D BtGatt.AdvertiseManager: isStandardAdv = false
,09-07 11:37:21.158  3003  3007 I WCNSS_FILTER: Direction(0): bytes: 28 : bytes_written: 28
,09-07 11:37:21.158  1250  2327 V AlarmManager:  remove PendingIntent] PendingIntent{4c81024: PendingIntentRecord{45887f2 com.android.bluetooth broadcastIntent}}
09-07 11:37:21.158  3003  3003 I WCNSS_FILTER: do_write: IBS write: fc
09-07 11:37:21.158  3003  3003 I WCNSS_FILTER: Direction(1): bytes: 8 : bytes_written: 8
09-07 11:37:21.158  3003  3007 I WCNSS_FILTER: Direction(0): bytes: 7 : bytes_written: 7
,09-07 11:37:21.158  2587  2780 D BtGatt.GattService: [GSIM LOG]: increaseAdvCount : com.test.thalitest : 22
09-07 11:37:21.158  2587  2780 D BtGatt.GattService: [GSIM LOG]: setAdvTime : com.test.thalitest@LowLatency : 24554017
09-07 11:37:21.158  2587  2780 D BtGatt.GattService: [GSIM LOG]: setAdvType : com.test.thalitest@LowLatency : 2
09-07 11:37:21.158  2587  2780 D BtGatt.GattService: [GSIM LOG]: updateAdvTime
09-07 11:37:21.158  2587  2780 D BtGatt.GattService: [GSIM LOG]: com.test.thalitest@LowLatency, R time : 2 => 2
09-07 11:37:21.158  3003  3003 I WCNSS_FILTER: Direction(1): bytes: 8 : bytes_written: 8
09-07 11:37:21.158  2587  2756 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=6, status=0
09-07 11:37:21.158  2587  2765 D BtGatt.AdvertiseManager: starting multi advertising
,09-07 11:37:21.158  3003  3007 I WCNSS_FILTER: Direction(0): bytes: 38 : bytes_written: 38
09-07 11:37:21.168  1250  1994 V AlarmManager:  remove PendingIntent] PendingIntent{df2078d: PendingIntentRecord{45887f2 com.android.bluetooth broadcastIntent}}
09-07 11:37:21.168  3003  3003 I WCNSS_FILTER: Direction(1): bytes: 8 : bytes_written: 8
,09-07 11:37:21.168  2587  2756 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=6, status=0
09-07 11:37:21.168  2587  2765 D BtGatt.AdvertiseManager: logClientsSet() - status: 0
09-07 11:37:21.168  2587  2765 D BtGatt.AdvertiseManager: clientIf: 6, Mode: 2, TxPowerLevel: 3, isConnectable: false, Timeout: 0
09-07 11:37:21.168  2587  2765 D BtGatt.AdvertiseManager: postCallback clientIf = 6 status = 0
09-07 11:37:21.168  2587  2765 D BtGatt.GattService: onMultipleAdvertiseCallback() clientIf=6, status=0, isStart=true
09-07 11:37:21.168  5989  5999 D BluetoothLeAdvertiser: onMultiAdvertiseCallback status = 0 isStart = true
09-07 11:37:21.168  5989  6040 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
09-07 11:37:21.168  5989  6040 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,09-07 11:37:21.168  5989  6040 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
09-07 11:37:21.168  1250  1964 V AlarmManager:  remove PendingIntent] PendingIntent{2685d42: PendingIntentRecord{45887f2 com.android.bluetooth broadcastIntent}}
,09-07 11:37:21.168  5989  6040 I io.jxcore.node.ConnectionHelper: start: OK
,09-07 11:37:21.168  5989  5989 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
09-07 11:37:21.168  5989  5989 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess
09-07 11:37:21.168  5989  5989 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
09-07 11:37:21.168  5989  5989 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: true
09-07 11:37:21.168  5989  5989 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [ADVERTISING]
09-07 11:37:21.168  5989  5989 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [ADVERTISING]
09-07 11:37:21.168  1250  1986 V AlarmManager:  remove PendingIntent] PendingIntent{5e60153: PendingIntentRecord{45887f2 com.android.bluetooth broadcastIntent}}
,09-07 11:37:21.178  5989  5989 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: true
09-07 11:37:21.178  5989  5989 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: true
,09-07 11:37:21.178  1250  1994 V AlarmManager:  remove PendingIntent] PendingIntent{880a90: PendingIntentRecord{45887f2 com.android.bluetooth broadcastIntent}}
,09-07 11:37:21.178  1250  1964 V AlarmManager:  remove PendingIntent] PendingIntent{8848f89: PendingIntentRecord{45887f2 com.android.bluetooth broadcastIntent}}
,09-07 11:37:21.678  5989  5989 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: true,
09-07 11:37:21.678  5989  5989 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
09-07 11:37:21.678  5989  5989 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,09-07 11:37:22.168  3003  3066 I WCNSS_FILTER: do_write: IBS write: fe
09-07 11:37:22.168  3003  3066 I WCNSS_FILTER: ibs_msm_serial_clock_vote: vote UART CLK OFF using UART driver's ioctl()
,09-07 11:37:24.408  1250  1834 E Watchdog: !@Sync 4 [09-07 11:37:24.416]
,09-07 11:37:24.848  1250  3553 D SSRM:s  : SIOP:: AP = 300, PST = 336 (W:12), CP = 36, LCD = 0
,09-07 11:37:24.848  1250  3553 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
,09-07 11:37:25.338   707   707 I MSM-irqbalance: Decided to move IRQ200 from CPU0 to CPU1
,09-07 11:37:25.578  2103  2155 D ContactsProvider_EventLog: contents_sample_state: [ contacts(0) data(0) accounts({}) accounts deleted({}) calls([])  ]
09-07 11:37:25.578  2103  2155 D ContactsProvider_EventLog: contents_sample_state: [ agr({})  ]
,09-07 11:37:27.168  5989  6040 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-07 11:37:27.168  5989  6040 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
09-07 11:37:27.168  5989  6040 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
09-07 11:37:27.168  5989  6040 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
09-07 11:37:27.178  5989  6040 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-07 11:37:27.178  5989  6040 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
09-07 11:37:27.178  5989  6142 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
09-07 11:37:27.178  5989  6142 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
09-07 11:37:27.178  5989  6142 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
09-07 11:37:27.178  5989  6040 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@d297dbd not in the list
09-07 11:37:27.178  5989  6040 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-07 11:37:27.178  5989  6040 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-07 11:37:27.178  5989  6040 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-07 11:37:27.178  5989  6040 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-07 11:37:27.178  5989  6040 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-07 11:37:27.178  5989  5989 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
09-07 11:37:27.178  5989  5989 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
09-07 11:37:27.178  5989  6040 D BluetoothAdapter: STATE_ON
,09-07 11:37:27.178  5989  6040 D BluetoothAdapter: STATE_ON
09-07 11:37:27.178  5989  6040 D BluetoothLeScanner: could not find callback wrapper
09-07 11:37:27.178  5989  6040 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-07 11:37:27.178  5989  6040 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
09-07 11:37:27.178  5989  6040 D BluetoothAdapter: STATE_ON
09-07 11:37:27.178  5989  6040 D BluetoothAdapter: STATE_ON
09-07 11:37:27.178  5989  6040 D BluetoothLeAdvertiser: stop advertising
,09-07 11:37:27.188  2587  2614 D BtGatt.GattService: [GSIM LOG]: getCallingProcessName: com.test.thalitest
09-07 11:37:27.188  2587  2614 D BtGatt.GattService: [GSIM LOG]: getCallingProcessName: com.test.thalitest
09-07 11:37:27.188  2587  2765 D BtGatt.AdvertiseManager: message : 1
09-07 11:37:27.188  2587  2780 E BtGatt.GattService: [GSIM LOG]: gsimLogHandler: com.test.thalitest, msg: MESSAGE_STOP_ADV
09-07 11:37:27.188  2587  2780 D BtGatt.GattService: [GSIM LOG]: gsimLogHandler: prevDate: 7, currDate: 7
09-07 11:37:27.188  2587  2780 D BtGatt.GattService: [GSIM LOG]: updateAdvTime
09-07 11:37:27.188  2587  2765 D BtGatt.AdvertiseManager: stop advertise for client =  6,
09-07 11:37:27.188  2587  2765 D BtGatt.AdvertiseManager: stop advertising, standardAdvClientIf = 0 client.clientIf = 6
09-07 11:37:27.188  1250  1310 V AlarmManager:  remove PendingIntent] PendingIntent{1230b8e: PendingIntentRecord{45887f2 com.android.bluetooth broadcastIntent}}
09-07 11:37:27.188  2587  2780 D BtGatt.GattService: [GSIM LOG]: com.test.thalitest@LowLatency, R time : 2 => 2
09-07 11:37:27.188  2587  2780 D BtGatt.GattService: [GSIM LOG]: remove : com.test.thalitest@LowLatency at  BLE_ADV_REQUESTED_DB
09-07 11:37:27.188  2587  2765 D BtGatt.AdvertiseManager: logClientsSet() - status: -1
09-07 11:37:27.188  3003  3007 I WCNSS_FILTER: ibs_msm_serial_clock_vote: vote UART CLK ON using UART driver's ioctl()
09-07 11:37:27.188  3003  3007 I WCNSS_FILTER: do_write: IBS write: fd
09-07 11:37:27.188  3003  3007 I WCNSS_FILTER: Direction(0): bytes: 7 : bytes_written: 7
09-07 11:37:27.198  3003  3003 I WCNSS_FILTER: do_write: IBS write: fc
,09-07 11:37:27.198  3003  3003 I WCNSS_FILTER: Direction(1): bytes: 8 : bytes_written: 8
09-07 11:37:27.198  2587  2756 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=6, status=0
09-07 11:37:27.198  2587  2756 D BtGatt.GattService: Client app is not null!
,09-07 11:37:27.198  3003  3007 E WCNSS_FILTER: do_read: read returned 0, err = Success, read bytes: 0, expected: 0
09-07 11:37:27.198  3003  3007 I WCNSS_FILTER: Direction(0): bytes: 4 : bytes_written: 4
09-07 11:37:27.198  5989  6000 D BluetoothLeAdvertiser: onMultiAdvertiseCallback status = 0 isStart = false
09-07 11:37:27.198  1250  2333 V AlarmManager:  remove PendingIntent] PendingIntent{7455faf: PendingIntentRecord{45887f2 com.android.bluetooth broadcastIntent}}
09-07 11:37:27.198  2587  2604 D BtGatt.GattService: unregisterClient() - clientIf=6
,09-07 11:37:27.198  5989  6040 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-07 11:37:27.198  5989  6040 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
,09-07 11:37:27.198  5989  6040 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: false
09-07 11:37:27.198  5989  6040 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [ADVERTISING] to [NOT_STARTED]
09-07 11:37:27.198  5989  6040 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [ADVERTISING] -> [NOT_STARTED]
09-07 11:37:27.198  5989  6040 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
09-07 11:37:27.198  5989  6040 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-07 11:37:27.198  5989  6040 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-07 11:37:27.198  5989  6040 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-07 11:37:27.198  5989  6040 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c284fb2 not in the list
09-07 11:37:27.198  5989  6040 D io.jxcore.node.ConnectivityMonitor: stop
09-07 11:37:27.198  5989  6040 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 11:37:27.198  5989  5989 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-07 11:37:27.198  5989  5989 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-07 11:37:27.198  5989  5989 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,09-07 11:37:27.208  1250  1986 V AlarmManager:  remove PendingIntent] PendingIntent{c0b3fbc: PendingIntentRecord{45887f2 com.android.bluetooth broadcastIntent}}
,09-07 11:37:27.208  3003  3003 I WCNSS_FILTER: Direction(1): bytes: 15 : bytes_written: 15
09-07 11:37:27.208  3003  3007 I WCNSS_FILTER: Direction(0): bytes: 12 : bytes_written: 12
,09-07 11:37:27.208  3003  3003 I WCNSS_FILTER: Direction(1): bytes: 8 : bytes_written: 8
09-07 11:37:27.208  1250  2010 V AlarmManager:  remove PendingIntent] PendingIntent{59d9b45: PendingIntentRecord{45887f2 com.android.bluetooth broadcastIntent}}
,09-07 11:37:27.218  1250  1964 V AlarmManager:  remove PendingIntent] PendingIntent{5c8529a: PendingIntentRecord{45887f2 com.android.bluetooth broadcastIntent}}
,09-07 11:37:27.218  1250  2396 V AlarmManager:  remove PendingIntent] PendingIntent{c9247cb: PendingIntentRecord{45887f2 com.android.bluetooth broadcastIntent}}
,09-07 11:37:27.478  3003  3003 I WCNSS_FILTER: do_write: IBS write: fc
,09-07 11:37:27.478  3003  3003 I WCNSS_FILTER: Direction(1): bytes: 14 : bytes_written: 14,
09-07 11:37:27.478  2587  3057 W bt_sdp  : SDP - Rcvd conn cnf with error: 0x4  CID 0x40
09-07 11:37:27.478  1250  2333 V AlarmManager:  remove PendingIntent] PendingIntent{e2a9ba8: PendingIntentRecord{45887f2 com.android.bluetooth broadcastIntent}}
,09-07 11:37:27.478  2587  3057 E bt_btif_sock_rfcomm: SDP - Failed to look up a channel number to connect to
09-07 11:37:27.478  2587  3057 W bt_btif : bta_dm_acl_change(), event : 2
09-07 11:37:27.478  2587  3057 W bt_btif : bta_dm_acl_change(), event : 5,
09-07 11:37:27.478  2587  3150 E bt_btif_sock_rfcomm: find_rfc_slot_by_id unable to find RFCOMM slot id: 7
09-07 11:37:27.478  5989  6140 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Exiting thread (thread ID: 212)
,09-07 11:37:27.488  1250  1313 V AlarmManager:  remove PendingIntent] PendingIntent{f81a6c1: PendingIntentRecord{45887f2 com.android.bluetooth broadcastIntent}}
,09-07 11:37:27.488  2587  2751 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@c11cc52
09-07 11:37:27.488  1250  2674 V AlarmManager:  remove PendingIntent] PendingIntent{548fe66: PendingIntentRecord{45887f2 com.android.bluetooth broadcastIntent}}
,09-07 11:37:27.488  2587  2756 E BluetoothRemoteDevices: devicePropertyChangedCallback: bdDevice: 00:11:22:33:44:55, value is empty for type: 1
,09-07 11:37:27.498  1694  2100 V BluetoothEventManager: onReceive :: android.bluetooth.device.action.CLASS_CHANGED
,09-07 11:37:27.498  2587  2756 D BluetoothUtils: getBtEnabledContainers(): btContainers = []
09-07 11:37:27.498  2587  2756 E BluetoothRemoteDevices: devicePropertyChangedCallback: bdDevice: 00:11:22:33:44:55, value is empty for type: 241
,09-07 11:37:27.708  5989  5989 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,09-07 11:37:27.738  1250  3581 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:836 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,09-07 11:37:27.998  2587  2751 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@c11cc52
09-07 11:37:27.998  1250  1378 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{67b95a7 u0 com.samsung.android.providers.context.log.action.USE_APP_FEATURE_SURVEY qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{573bf46 2626:com.samsung.android.providers.context/u0a5}
,09-07 11:37:28.208  3003  3066 I WCNSS_FILTER: do_write: IBS write: fe
09-07 11:37:28.208  3003  3066 I WCNSS_FILTER: ibs_msm_serial_clock_vote: vote UART CLK OFF using UART driver's ioctl()
,09-07 11:37:30.208  5989  6040 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-07 11:37:30.208  5989  6040 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 11:37:30.208  5989  6040 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 11:37:30.208  5989  6040 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@d297dbd not in the list
09-07 11:37:30.208  5989  6040 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-07 11:37:30.208  5989  6040 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c284fb2 not in the list
09-07 11:37:30.208  5989  6040 D io.jxcore.node.ConnectivityMonitor: stop
09-07 11:37:30.208  5989  6040 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 11:37:30.208  5989  6040 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 11:37:30.208  5989  6040 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
09-07 11:37:30.208  5989  6040 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-07 11:37:30.208  5989  6040 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
09-07 11:37:30.208  5989  6040 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
09-07 11:37:30.208  5989  6040 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
09-07 11:37:30.208  5989  6040 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
09-07 11:37:30.208  5989  6040 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
09-07 11:37:30.208  5989  6040 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-07 11:37:30.208  5989  6040 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
09-07 11:37:30.208  5989  6040 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
09-07 11:37:30.208  5989  6040 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
09-07 11:37:30.208  5989  6040 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 11:37:30.208  5989  6040 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
09-07 11:37:30.208  5989  6040 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@d297dbd not in the list
09-07 11:37:30.208  5989  6040 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-07 11:37:30.208  5989  6040 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-07 11:37:30.208  5989  6040 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-07 11:37:30.208  5989  6040 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-07 11:37:30.208  5989  6040 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 11:37:30.208  5989  6040 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 11:37:30.208  5989  5989 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
09-07 11:37:30.208  5989  5989 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
09-07 11:37:30.218  5989  6147 D BluetoothSocket: bindListen(): myUserId = 0
09-07 11:37:30.218  5989  6040 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
09-07 11:37:30.218  5989  6147 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-07 11:37:30.218  5989  6040 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c284fb2 not in the list
09-07 11:37:30.218  5989  6040 D io.jxcore.node.ConnectivityMonitor: stop
09-07 11:37:30.218  5989  6040 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 11:37:30.218  5989  6040 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 11:37:30.218  5989  5989 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-07 11:37:30.218  5989  5989 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-07 11:37:30.218  5989  5989 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-07 11:37:30.218  5989  60,40 E io.jxcore.node.ConnectionHelper: onConnectionFailed: Peer properties: [<no peer name> 00:11:22:33:44:55], error message: ErrorMessage
09-07 11:37:30.218  5989  6040 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
09-07 11:37:30.218  5989  6040 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
09-07 11:37:30.218  5989  6040 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-07 11:37:30.218  5989  6040 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-07 11:37:30.218  5989  6040 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 11:37:30.218  5989  6040 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 11:37:30.218  5989  6147 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
09-07 11:37:30.218  5989  6147 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
09-07 11:37:30.218  5989  6040 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@d297dbd not in the list
09-07 11:37:30.218  5989  6040 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-07 11:37:30.218  5989  6147 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
09-07 11:37:30.218  5989  6040 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c284fb2 not in the list
09-07 11:37:30.218  5989  6040 D io.jxcore.node.ConnectivityMonitor: stop
,09-07 11:37:30.218  5989  6040 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 11:37:30.218  5989  6040 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 11:37:30.218  5989  5989 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
,09-07 11:37:30.228  5989  6040 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose,
09-07 11:37:30.228  5989  6040 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 11:37:30.228  5989  6040 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 11:37:30.228  5989  6040 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@d297dbd not in the list
09-07 11:37:30.228  5989  6040 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-07 11:37:30.228  5989  6040 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c284fb2 not in the list
09-07 11:37:30.228  5989  6040 D io.jxcore.node.ConnectivityMonitor: stop
09-07 11:37:30.228  5989  6040 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 11:37:30.228  5989  6040 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 11:37:30.228  5989  6040 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-07 11:37:30.228  5989  6040 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 11:37:30.228  5989  6040 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 11:37:30.228  5989  6040 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@d297dbd not in the list
09-07 11:37:30.228  5989  6040 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-07 11:37:30.228  5989  6040 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c284fb2 not in the list
09-07 11:37:30.228  5989  6040 D io.jxcore.node.ConnectivityMonitor: stop
09-07 11:37:30.228  5989  6040 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 11:37:30.228  5989  6040 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 11:37:30.228  5989  6040 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing
09-07 11:37:30.228  5989  6040 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
09-07 11:37:30.228  5989  6040 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID outgoing
09-07 11:37:30.228  5989  6040 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
09-07 11:37:30.228  5989  6040 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing2
09-07 11:37:30.228  5989  6040 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
,09-07 11:37:30.228  5989  6040 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
09-07 11:37:30.228  5989  6040 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> outgoing]
09-07 11:37:30.228  5989  6040 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 1
,09-07 11:37:30.228  5989  6040 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
09-07 11:37:30.228  5989  6040 E io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Failed to find an incoming connection thread with ID 1
09-07 11:37:30.228  5989  6040 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
09-07 11:37:30.228  5989  6040 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 2
09-07 11:37:30.228  5989  6040 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
09-07 11:37:30.238  5989  6040 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing1" removed
09-07 11:37:30.238  5989  6040 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing2" removed
,09-07 11:37:30.238  5989  6040 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID id
09-07 11:37:30.238  5989  6040 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID outgoing
09-07 11:37:30.238  5989  6040 D io.jxcore.node.ConnectionModel: hasConnection: We have an incoming connection with peer with ID incoming
09-07 11:37:30.238  5989  6040 D io.jxcore.node.ConnectionModel: hasConnection: We have an outgoing connection with peer with ID outgoing
,09-07 11:37:30.238  5989  6040 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-07 11:37:30.238  5989  6040 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c5c0af3 added. We now have 2 listener(s)
,09-07 11:37:30.238  5989  6040 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "44:78:3E:EB:95:EE"
09-07 11:37:30.238  5989  6040 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,09-07 11:37:30.238  5989  6040 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-07 11:37:30.238  5989  6040 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-07 11:37:30.238  5989  6040 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@978e3b0 added. We now have 2 listener(s)
09-07 11:37:30.238  5989  6040 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-07 11:37:30.238  5989  6040 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-07 11:37:30.238  5989  6040 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-07 11:37:30.248  5989  6040 D BluetoothAdapter: STATE_ON
,09-07 11:37:30.248  5989  6040 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-07 11:37:30.248  5989  6040 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-07 11:37:30.248  5989  6040 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-07 11:37:30.248  5989  6040 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-07 11:37:30.248  5989  6040 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-07 11:37:30.248  5989  6040 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-07 11:37:30.248  5989  6040 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-07 11:37:30.248  5989  6040 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-07 11:37:30.248  5989  6040 D BluetoothAdapter: STATE_ON
,09-07 11:37:30.258  5989  6040 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-07 11:37:30.258  5989  6040 D io.jxcore.node.ConnectivityMonitor: start: OK
09-07 11:37:30.258  5989  6040 D BluetoothAdapter: enable()
,09-07 11:37:30.258  5989  5989 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-07 11:37:30.258  5989  6040 D BluetoothAdapter: enable(): BT is already enabled..!
,09-07 11:37:30.258  5989  5989 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-07 11:37:30.258  1250  1378 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{7c1e543 u0 com.samsung.android.providers.context.log.action.USE_APP_FEATURE_SURVEY qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{573bf46 2626:com.samsung.android.providers.context/u0a5}
09-07 11:37:30.258  5989  6040 I WifiManager: isAllowWifiWarning() -> isCscWifiEnableWarning : false ChinaNalSecurityType : 
,09-07 11:37:30.268  1250  1990 D SecContentProvider: query(), uri = 18 selection = isWifiEnabled
,09-07 11:37:30.268  1250  1990 D SecContentProvider2: query(), uri = 20 selection = isWifiStateChangeAllowed
,09-07 11:37:30.268  1250  1990 D WifiService: System do NOT have com.sec.feature.sensorhub feature
09-07 11:37:30.268  1250  1990 D WifiService: Wi-Fi on and Screen on , checkSensorStatus !!
,09-07 11:37:30.268  1250  1990 D WifiService: setWifiEnabled: true pid=5989, uid=10136
09-07 11:37:30.268  1250  1990 W ActivityManager: Permission Denial: getCurrentUser() from pid=5989, uid=10136 requires android.permission.INTERACT_ACROSS_USERS
,09-07 11:37:30.278  1250  1990 W WifiService: Failed getting userId using ActivityManagerNative
09-07 11:37:30.278  1250  1990 W WifiService: java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=5989, uid=10136 requires android.permission.INTERACT_ACROSS_USERS
09-07 11:37:30.278  1250  1990 W WifiService: 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:28130)
09-07 11:37:30.278  1250  1990 W WifiService: 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2542)
09-07 11:37:30.278  1250  1990 W WifiService: 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2530)
09-07 11:37:30.278  1250  1990 W WifiService: 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:257)
09-07 11:37:30.278  1250  1990 W WifiService: 	at android.os.Binder.execTransact(Binder.java:453)
09-07 11:37:30.278  1250  1990 D SettingsProvider: isChangeAllowed() : name = wifi_on
09-07 11:37:30.278  1250  1623 D WifiBigDataLog: getJsonFormat() - feature : ONOF
09-07 11:37:30.278  1250  1624 D WifiController: [FCC]setFccChannel() is called !!!
09-07 11:37:30.278  1250  1624 D WifiStateMachine: setFccChannel: channel = 0
09-07 11:37:30.278  1250  1624 D WifiController: [FCC]Airplane on, setFccChannel(0)!!!
09-07 11:37:30.278  1250  1623 D WifiBigDataLog: init : 
09-07 11:37:30.278  1250  1623 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:836 com.android.server.wifi.WifiStateMachine.insertLog:18843 com.android.server.wifi.WifiStateMachine.access$4300:293 com.android.server.wifi.WifiStateMachine$DefaultState.processMessage:8707 com.android.internal.util.StateMachine$SmHandler.processMsg:968 
,09-07 11:37:30.278  5989  6040 D BluetoothAdapter: STATE_ON
09-07 11:37:30.278  1250  1378 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{63b37c0 u0 com.samsung.android.providers.context.log.action.USE_APP_FEATURE_SURVEY qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{573bf46 2626:com.samsung.android.providers.context/u0a5}
09-07 11:37:30.278  1250  1623 D WifiStateMachine: setFccChannelNative: channel = 0
09-07 11:37:30.278  1250  1623 D WifiNative-wlan0: callSECApiInt - ID [230]
,09-07 11:37:30.288  5989  6040 D BluetoothAdapter: enable()
,09-07 11:37:30.288  5989  6040 D BluetoothAdapter: enable(): BT is already enabled..!
,09-07 11:37:30.288  1250  1378 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{b36cf9 u0 com.samsung.android.providers.context.log.action.USE_APP_FEATURE_SURVEY qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{573bf46 2626:com.samsung.android.providers.context/u0a5},
09-07 11:37:30.288  1250  1721 D SecContentProvider: query(), uri = 18 selection = isWifiEnabled
,09-07 11:37:30.288  1250  1721 D SecContentProvider2: query(), uri = 20 selection = isWifiStateChangeAllowed
,09-07 11:37:30.298  1250  1721 D WifiService: setWifiEnabled: false pid=5989, uid=10136
09-07 11:37:30.298  1250  1721 D SettingsProvider: isChangeAllowed() : name = wifi_on
,09-07 11:37:30.298  1250  1623 D WifiBigDataLog: getJsonFormat() - feature : ONOF
09-07 11:37:30.298  1250  1624 D WifiStateMachine: setFccChannel: channel = 0
,09-07 11:37:30.298  1250  1624 D WifiController: [FCC]setFccChannel() is called !!!
09-07 11:37:30.298  1250  1624 D WifiController: [FCC]Airplane on, setFccChannel(0)!!!
09-07 11:37:30.298  1250  1624 D WifiController: MHS off and WIFI tunred off and move to mApStaDisabledState
,09-07 11:37:30.298  1250  1623 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:836 com.android.server.wifi.WifiStateMachine.insertLog:18843 com.android.server.wifi.WifiStateMachine.access$4300:293 com.android.server.wifi.WifiStateMachine$DefaultState.processMessage:8707 com.android.internal.util.StateMachine$SmHandler.processMsg:968 
09-07 11:37:30.298  1250  1624 D SecContentProvider: insert(), uri = 2
09-07 11:37:30.298  1250  2127 E OsAgent :  Wifi Scan Always Available: 0
,09-07 11:37:30.298  1250  2127 E IzatSvc_OSObserver: I/LocTech-Label :: OSOBSERVER :: Data Items In
09-07 11:37:30.298  1250  2127 E IzatSvc_OSObserver: I/LocTech-Value :: Data Item Value: IS_WIFI_HARDWARE_ON: false
09-07 11:37:30.298  1250  2152 E LocSvc_libulp: I/int ulp_msg_process_phone_setting_update(const UlpPhoneContextSettings*), context type: 0x4
09-07 11:37:30.298  1250  2152 E LocSvc_libulp:   gps enabled: 0
09-07 11:37:30.298  1250  2152 E LocSvc_libulp:  network position available 0
09-07 11:37:30.298  1250  2152 E LocSvc_libulp:  wifi setting enabled 0
09-07 11:37:30.298  1250  2152 E LocSvc_libulp:  battery charging 0, agps enabled 0, enh_location_services_enabled 0is_pip_user_setting_enabled 0
09-07 11:37:30.298  1250  2127 E OsAgent :  Wifi Scan Always Available: 0
09-07 11:37:30.298  1250  2152 E LocSvc_libulp: I/int ulp_msg_process_system_update(UlpSystemEvent): systemEvent:4 
09-07 11:37:30.298  1250  2127 E IzatSvc_OSObserver: I/LocTech-Label :: OSOBSERVER :: Data Items In
09-07 11:37:30.298  1250  2152 E LocSvc_libulp: I/int ulp_msg_process_start_req(), at ulp state = 1
09-07 11:37:30.298  1250  2127 E IzatSvc_OSObserver: I/LocTech-Value :: Data Item Value: IS_WIFI_HARDWARE_ON: false
09-07 11:37:30.298  1250  2127 E OsAgent :  Wifi Scan Always Available: 0
09-07 11:37:30.298  1250  2127 E IzatSvc_OSObserver: I/LocTech-Label :: OSOBSERVER :: Data Items In
,09-07 11:37:30.298  1250  2127 E IzatSvc_OSObserver: I/LocTech-Value :: Data Item Value: IS_WIFI_HARDWARE_ON: false
09-07 11:37:30.298  1250  1623 D WifiBigDataLog: init : 
09-07 11:37:30.298  1250  2132 E LocSvc_LBSApiV02: E/virtual int lbs_core::LBSApiV02::wifiEnabledStatusInject(int):677]: Error : st = 2, ind.status = 1310827456
09-07 11:37:30.298  1250  1623 D WifiStateMachine: setFccChannelNative: channel = 0
09-07 11:37:30.298  1250  1623 D WifiNative-wlan0: callSECApiInt - ID [230]
,09-07 11:37:30.308  1250  1623 D WifiStateMachine: WifiStateMachine: Leaving Connected state
09-07 11:37:30.308  1250  1378 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{f7c0fec u0 com.samsung.android.providers.context.log.action.USE_APP_FEATURE_SURVEY qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{573bf46 2626:com.samsung.android.providers.context/u0a5}
09-07 11:37:30.308  1250  1623 D WifiStateMachine: isPackageRunning - top:com.test.thalitest.MainActivity
09-07 11:37:30.308  1250  1623 D WifiStateMachine: isPackageRunning - top:com.test.thalitest.MainActivity
09-07 11:37:30.308  1250  1623 D WifiStateMachine: sendBroadcastForCaptivePortalNotLoginIcon : false
,09-07 11:37:30.308  1250  1623 D WifiStateMachine: isPackageRunning - top:com.test.thalitest.MainActivity
09-07 11:37:30.308  1694  2100 D NetworkController: onReceive: intent=Intent { act=com.samsung.intent.action.WIFI_CAPTIVE_NOT_LOGIN flg=0x10 bqHint=4 VirtualScreenParam=Params{mDisplayId=-1, null, mFlags=0x00000000)} (has extras) }
09-07 11:37:30.308  1694  2100 D NetworkController.WifiSignalController: updateWifiState : mCurrentState.wifiCaptiveNotLogin = false
,09-07 11:37:30.308  1250  1623 D WifiStateMachine: isPackageRunning - top:com.test.thalitest.MainActivity
,09-07 11:37:30.308  1250  1623 D WifiStateMachine: isPackageRunning - top:com.test.thalitest.MainActivity
09-07 11:37:30.308  1250  1623 D WifiStateMachine: isPackageRunning - top:com.test.thalitest.MainActivity
09-07 11:37:30.308  1250  1623 D WifiStateMachine: sendBroadcastForCaptivePortalNotLoginIcon : false
,09-07 11:37:30.308  1250  1623 D WifiStateMachine: isPackageRunning - top:com.test.thalitest.MainActivity
09-07 11:37:30.308  1250  1623 D WifiStateMachine: isPackageRunning - top:com.test.thalitest.MainActivity
,09-07 11:37:30.308  1250  1623 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
09-07 11:37:30.308  1250  1623 E WifiNative-wlan0: do suspend true
09-07 11:37:30.308  1694  2100 D NetworkController: onReceive: intent=Intent { act=com.samsung.intent.action.WIFI_CAPTIVE_NOT_LOGIN flg=0x10 bqHint=4 VirtualScreenParam=Params{mDisplayId=-1, null, mFlags=0x00000000)} (has extras) }
09-07 11:37:30.308  1694  2100 D NetworkController.WifiSignalController: updateWifiState : mCurrentState.wifiCaptiveNotLogin = false
,09-07 11:37:30.318  1250  1622 D WifiP2pService: InactiveState{ what=143375 }
,09-07 11:37:30.318  1250  1622 D WifiP2pService: P2pEnabledState{ what=143375 }
09-07 11:37:30.318  1250  3168 V AlarmManager:  remove PendingIntent] PendingIntent{134dfb5: PendingIntentRecord{dc416c5 android broadcastIntent}}
09-07 11:37:30.318   554  1414 D CommandListener: Clearing all IP addresses on wlan0
,09-07 11:37:30.318   766  1446 I QC-NETMGR-LIB: Received nl msg, recvmsg returned 80
09-07 11:37:30.318   766  1446 I QC-NETMGR-LIB: Received command: ID=NETMGR_KIF_MSG_CMD, link=0
09-07 11:37:30.318   766  1446 I QC-NETMGR-LIB: Received nl msg, recvmsg returned 64
09-07 11:37:30.318   766  1446 I QC-NETMGR-LIB: Received command: ID=NETMGR_KIF_MSG_CMD, link=0
,09-07 11:37:30.318  1250  1630 E ConnectivityService: updateNetworkInfo()
09-07 11:37:30.318  1250  1630 D ConnectivityService: NetworkAgentInfo [WIFI () - 502] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN&VALIDATED LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -39]
09-07 11:37:30.318   766  1442 I QC-NETMGR-LIB: Process command: ID=NETMGR_KIF_MSG_CMD, link=0, state=1
09-07 11:37:30.318  1250  1630 D ConnectivityService: ignoring duplicate network state non-change. WIFI, state = DISCONNECTED
09-07 11:37:30.318   766  1442 I QC-NETMGR-LIB: Processing RTM_DELADDR
09-07 11:37:30.318  1250  1630 D ConnectivityService: NetworkAgentInfo [WIFI () - 502] got DISCONNECTED, was satisfying 5
09-07 11:37:30.318   766  1442 I QC-NETMGR-LIB: Metainfo:  Family=2 PrefixLen=24 Scope=0x0 Index=13 Flags=[0x80]PERMANENT 
09-07 11:37:30.318   766  1442 I QC-NETMGR-LIB: Attribute: PrefixIPv4 addr [192.168.1.106]
09-07 11:37:30.318   766  1442 I QC-NETMGR-LIB: Attribute: LocalIPv4 addr [192.168.1.106]
09-07 11:37:30.318  1250  1630 V NetworkStats: updateIfacesLocked()
09-07 11:37:30.318   766  1442 I QC-NETMGR-LIB: Attribute: BroadcastIPv4 addr [192.168.1.255]
09-07 11:37:30.318  1250  1630 V NetworkStats: performPollLocked(flags=0x1)
09-07 11:37:30.318   766  1442 I QC-NETMGR-LIB: Attribute: Label name wlan0
09-07 11:37:30.318   766  1442 I QC-NETMGR-LIB: Attribute: Address Cache Info - prefered=-1 valid=-1 cstamp=0x946 tstamp=0x946
09-07 11:37:30.318   766  1442 I QC-NETMGR-LIB: Rcvd Netlink msg type [21]
09-07 11:37:30.318   766  1442 E QC-NETMGR-LIB: unrecognized ifindex 13
09-07 11:37:30.318   766  1442 I QC-NETMGR-LIB: Process command: ID=NETMGR_KIF_MSG_CMD, link=0, state=1
09-07 11:37:30.318   766  1442 I QC-NETMGR-LIB: Processing RTM_DELADDR
09-07 11:37:30.318   766  1442 I QC-NETMGR-LIB: Metainfo:  Family=10 PrefixLen=64 Scope=0xfd Index=13 Flags=[0x80]PERMANENT 
09-07 11:37:30.318   766  1442 I QC-NETMGR-LIB: Attribute: PrefixIPv6 addr [fe80:0000:0000:0000:4678:3eff:feeb:95ef]
09-07 11:37:30.318   766  1442 I QC-NETMGR-LIB: Attribute: Address Cache Info - prefered=-1 valid=-1 cstamp=0x90e tstamp=0x90e
09-07 11:37:30.318   766  1442 I QC-NETMGR-LIB: Rcvd Netlink msg type [21]
09-07 11:37:30.318   766  1442 E QC-NETMGR-LIB: unrecognized ifindex 13
09-07 11:37:30.318  1250  1630 E ConnectivityService: updateNetworkInfo()
09-07 11:37:30.318  1250  1630 D NtpTrustedTime: currentTimeMillis() cache hit
,09-07 11:37:30.328  1250  1623 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
09-07 11:37:30.328  1250  1622 D WifiP2pService: InactiveState{ what=131204 }
09-07 11:37:30.328  1250  1622 D WifiP2pService: P2pEnabledState{ what=131204 }
,09-07 11:37:30.328  1250  1630 D NtpTrustedTime: currentTimeMillis() cache hit
09-07 11:37:30.328  1250  1630 D NetworkStatsRecorder: entry.iface is null
09-07 11:37:30.328  2391  2391 I wpa_supplicant: P2P: Set prekey state (NONE -> NONE)
09-07 11:37:30.328  1250  1630 D NetworkStatsRecorder: entry.iface is null
09-07 11:37:30.328  2391  2391 I wpa_supplicant: P2P: Clear a pre-passphrase (State NONE)
09-07 11:37:30.328  1250  1630 D NetworkStatsRecorder: entry.iface is null
09-07 11:37:30.328  1866  4507 V NativeCrypto: Read error: ssl=0x7f5b010680: I/O error during system call, Connection timed out
09-07 11:37:30.328  1250  1630 D NetworkStatsRecorder: entry.iface is null
09-07 11:37:30.328  1866  4507 V NativeCrypto: SSL shutdown failed: ssl=0x7f5b010680: I/O error during system call, Broken pipe
09-07 11:37:30.328  1250  1630 V NetworkStats: performPollLocked() took 4ms
09-07 11:37:30.328  1250  1622 D WifiP2pService: sending p2p connection changed broadcast: FAILED
,09-07 11:37:30.338  1694  2100 D NetworkController: onReceive: intent=Intent { act=android.net.wifi.RSSI_CHANGED flg=0x4000010 bqHint=4 VirtualScreenParam=Params{mDisplayId=-1, null, mFlags=0x00000000)} (has extras) }
09-07 11:37:30.338  1250  1250 I WifiTrafficPoller: evaluateTrafficStatsPolling
09-07 11:37:30.338  1250  1964 V AlarmManager:  remove PendingIntent] PendingIntent{aaa964a: PendingIntentRecord{e1d8317 com.google.android.gms broadcastIntent}}
09-07 11:37:30.338  1250  1250 I Wifi-SensorMonitor: enable sensor monitoring : false
09-07 11:37:30.338  1866  4507 E GCM     : Wifi connection closed with errorCode 20
09-07 11:37:30.338  1250  1250 D SensorHAL: GRIP_WIFI  set_enable 
,09-07 11:37:30.338  1250  1250 D SensorHAL: sx9310_grip_wifi: power-off.
09-07 11:37:30.338  1250  1250 E Sensors : ~SensorEventQueue 0
09-07 11:37:30.338  1250  1250 E         : BitTube(): close sendFd (346)
09-07 11:37:30.338  1250  1250 E         : BitTube(): close receivedFd (341)
09-07 11:37:30.338  1250  1250 D SensorManager: unregisterListener ::   
09-07 11:37:30.338  1250  1250 D WifiNative-wlan0: callSECApiInt - ID [70]
09-07 11:37:30.338   707   707 I MSM-irqbalance: Decided to move IRQ215 from CPU3 to CPU1
,09-07 11:37:30.338  1250  1250 D HS20StateMachine: Broadcast Received: android.net.wifi.STATE_CHANGE
09-07 11:37:30.338  1250  1250 D HS20StateMachine: [type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true]
,09-07 11:37:30.338  1250  1250 D HS20StateMachine: checkifOSUAP  null disconnectedFromSsid"NG700"
09-07 11:37:30.338  1250  1250 I WifiHs20Service: Broadcast received:android.net.wifi.STATE_CHANGE
09-07 11:37:30.338  1694  2100 D NetworkController: onReceive: intent=Intent { act=android.net.wifi.STATE_CHANGE flg=0x4000010 bqHint=4 VirtualScreenParam=Params{mDisplayId=-1, null, mFlags=0x00000000)} (has extras) }
,09-07 11:37:30.338  1250  1628 I WifiHs20Service: Message received 5007
,09-07 11:37:30.338  1944  1944 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.net.wifi.STATE_CHANGE
09-07 11:37:30.338  1694  2126 D QSTile.WifiTile: handleUpdateState  cb.changed 14 wifiEnabled : ON 
,09-07 11:37:30.348  1250  1378 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{ba8b9bb u-1 android.net.wifi.STATE_CHANGE qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{195a0dd 5691:com.enhance.gameservice/u0a79}
,09-07 11:37:30.348  1250  1630 D ConnectivityService: getAllNetworkState networkCapability  = [ Transports: WIFI Capabilities: WIFI_P2P&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
09-07 11:37:30.348  1250  1630 D ConnectivityService: getAllNetworkState networkCapability  = [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN&VALIDATED LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -39]
,09-07 11:37:30.348  1250  1630 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 502]
09-07 11:37:30.348  1250  1630 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-07 11:37:30.348  1250  1630 D ConnectivityService:  sending notification for NetworkRequest [ id=4, legacyType=-1, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-07 11:37:30.348  1250  1250 D RttService: SCAN_AVAILABLE : 1
,09-07 11:37:30.348  1250  1630 D ConnectivityService: sending notification LOST for NetworkRequest [ id=4, legacyType=-1, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-07 11:37:30.348  1250  1650 D RttService: EnabledState got{ when=0 what=160513 target=com.android.internal.util.StateMachine$SmHandler }
09-07 11:37:30.348  1250  1630 D ConnectivityService:  sending notification for NetworkRequest [ id=5, legacyType=-1, [] ]
09-07 11:37:30.348  1250  1630 D ConnectivityService: sending notification LOST for NetworkRequest [ id=5, legacyType=-1, [] ]
09-07 11:37:30.348  1250  1630 D ConnectivityService:  sending notification for NetworkRequest [ id=6, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-07 11:37:30.348  1250  1630 D ConnectivityService: sending notification LOST for NetworkRequest [ id=6, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-07 11:37:30.348  1250  1630 D ConnectivityService:  sending notification for NetworkRequest [ id=7, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-07 11:37:30.348  1250  1630 D ConnectivityService: sending notification LOST for NetworkRequest [ id=7, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-07 11:37:30.348  1250  1630 D ConnectivityService: sending new Min Network Score(0): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-07 11:37:30.348  1250  1651 D Ethernet: new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-07 11:37:30.348  1250  3167 D NetworkMonitor/NetworkAgentInfo [WIFI () - 502]: ValidatedState{ when=-1ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
09-07 11:37:30.348  1250  1651 D Ethernet:   my score=-1, my filter=[ Transports: ETHERNET Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=100000Kbps LinkDnBandwidth>=100000Kbps]
09-07 11:37:30.348  1250  1651 D Ethernet: evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= false
09-07 11:37:30.348  1250  1651 D Ethernet: evalRequest
09-07 11:37:30.348  1250  1651 D Ethernet:   done
09-07 11:37:30.348  1250  1623 D WIFI    : new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-07 11:37:30.348  1250  1623 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
09-07 11:37:30.348  1250  1623 D WIFI    : evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= true
09-07 11:37:30.348  1250  1623 D WIFI    : evalRequest
09-07 11:37:30.348  1250  1623 D WIFI    :   done
,09-07 11:37:30.348  1250  2674 D ConnectivityService: getVpnConfig > userId : 0
,09-07 11:37:30.358  1250  1416 D EntConnectivity: Not allowed due to - mEnabled false
09-07 11:37:30.358  1250  1622 D WifiP2pService: sending p2p connection changed broadcast: DISCONNECTED
09-07 11:37:30.358  1250  1623 D WIFI    : new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-07 11:37:30.358  1250  1623 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
09-07 11:37:30.358  1250  1623 D WIFI    : evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= true
09-07 11:37:30.358  1250  1623 D WIFI    : evalRequest
09-07 11:37:30.358  1250  1623 D WIFI    :   done
09-07 11:37:30.358  1250  1623 D WIFI_UT : new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-07 11:37:30.358  1250  1623 D WIFI_UT :   my score=2147483647, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
09-07 11:37:30.358  1250  1623 D WIFI_UT : evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= true
09-07 11:37:30.358  1250  1623 D WIFI_UT : evalRequest
09-07 11:37:30.358  1250  1623 D WIFI_UT :   done
09-07 11:37:30.358  1250  1621 D NtpTrustedTime: currentTimeMillis() cache hit
,09-07 11:37:30.358  1250  1621 D NtpTrustedTime: currentTimeMillis() cache hit
09-07 11:37:30.358  1250  1417 D WifiDisplayController: Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/FAILED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
09-07 11:37:30.358  1250  1417 I WifiDisplayAdapter: onP2pDisconnected
09-07 11:37:30.358  1250  1417 D IpRemoteDisplayController: disconnectWfdBridgeServer
09-07 11:37:30.358  1250  1417 D IpRemoteDisplayController: WfdBridgeServer is already null
,09-07 11:37:30.358  1250  1250 D WifiNotificationController: SHOW_NOTI_MESSAGE : 17, visible : false, ssid : null, targetSSID : null, netId : -1, titleType : -1
09-07 11:37:30.358  1250  1250 D WifiNotificationController: showMaliciousHotspotDetectionNotification - MaliciousNetwork:null, visible:false
09-07 11:37:30.358  1250  1250 E WifiStateMachine: BroadcastReceiver : WIFI_P2P_STATE_CHANGED_ACTION is : android.net.wifi.p2p.STATE_CHANGED
09-07 11:37:30.358  1250  1417 D WifiDisplayController: Received WIFI_P2P_STATE_CHANGED_ACTION: enabled=false
09-07 11:37:30.358  1250  1417 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false, mScanRequestedInConnected = false
09-07 11:37:30.358  1250  1417 D WifiDisplayController: disconnect
09-07 11:37:30.358  1250  1417 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,09-07 11:37:30.358  1250  1994 V AlarmManager:  remove PendingIntent] PendingIntent{1103ed8: PendingIntentRecord{e4edab6 com.google.android.gms broadcastIntent}}
,09-07 11:37:30.368  1250  1622 D SecContentProvider: insert(), uri = 2
,09-07 11:37:30.368  1250  1622 D WifiP2pService: P2pDisablingState
,09-07 11:37:30.368  1250  1622 D WifiP2pService: P2pDisablingState{ what=147458 }
09-07 11:37:30.368  1250  1622 D WifiP2pService: p2p socket connection lost
09-07 11:37:30.368  1250  1622 D SecContentProvider: insert(), uri = 2
,09-07 11:37:30.368  1250  1622 D WifiP2pService: P2pDisabledState
,09-07 11:37:30.368  1250  1623 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
09-07 11:37:30.368  1250  1623 E WifiNative-wlan0: do suspend true
09-07 11:37:30.368  1250  1622 D WIFI_P2P: new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-07 11:37:30.368  1250  1622 D WIFI_P2P:   my score=60, my filter=[ Transports: WIFI Capabilities: WIFI_P2P&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
09-07 11:37:30.368  1250  1622 D WIFI_P2P: evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= false
09-07 11:37:30.368  1250  1622 D WIFI_P2P: evalRequest
09-07 11:37:30.368  1250  1622 D WIFI_P2P:   done
,09-07 11:37:30.368  1250  1622 D WifiP2pService: P2pDisabledState{ what=143375 }
09-07 11:37:30.368  1250  1622 D WifiP2pService: DefaultState{ what=143375 }
,09-07 11:37:30.368  1694  1694 D QSTileView: handleLabelStateChanged() label = Wi-Fi cellWidth 148
09-07 11:37:30.368  1250  1417 D WifiDisplayController: Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: false]
09-07 11:37:30.368  1250  1417 I WifiDisplayAdapter: onP2pDisconnected
09-07 11:37:30.368  1250  1417 D IpRemoteDisplayController: disconnectWfdBridgeServer
09-07 11:37:30.368  1250  1417 D IpRemoteDisplayController: WfdBridgeServer is already null
,09-07 11:37:30.368  1694  1694 D WifiP2pController: onReceive android.net.wifi.p2p.CONNECTION_STATE_CHANGE
09-07 11:37:30.368  1694  1694 D SoundPathController: onReceive - android.hardware.display.action.WIFI_DISPLAY_STATUS_CHANGED
,09-07 11:37:30.368  1694  1694 D ApMirroringController: onReceive android.hardware.display.action.WIFI_DISPLAY_STATUS_CHANGED
09-07 11:37:30.368  1694  1694 D AllShareCastTile: onReceive : android.hardware.display.action.WIFI_DISPLAY_STATUS_CHANGED
09-07 11:37:30.368  1250  1720 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,09-07 11:37:30.368  1694  1694 D AllShareCastTile: wifi display status changed! scanstate : 0, ActiveDisplayState : 0
,09-07 11:37:30.378  1250  1378 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{a20c231 u0 com.google.android.gcm.DISCONNECTED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{3a76423 5481:com.google.android.talk/u0a84}
,09-07 11:37:30.388   554  1414 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -D idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,09-07 11:37:30.388  1250  1378 I ActivityManager: Start proc 6153:com.sec.android.diagmonagent/1000 for broadcast-5 com.sec.android.diagmonagent/.DiagMonConnectivityChangeReciever
,09-07 11:37:30.388  6153  6153 E Zygote  : v2
09-07 11:37:30.388  6153  6153 I libpersona: KNOX_SDCARD checking this for 1000
09-07 11:37:30.388  6153  6153 I libpersona: KNOX_SDCARD not a persona
,09-07 11:37:30.388  6153  6153 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0013
,09-07 11:37:30.388  1694  1694 D WifiP2pController: onReceive android.net.wifi.p2p.CONNECTION_STATE_CHANGE
,09-07 11:37:30.388  1694  2100 D NetworkController: onReceive: intent=Intent { act=android.net.wifi.RSSI_CHANGED flg=0x4000010 bqHint=4 VirtualScreenParam=Params{mDisplayId=-1, null, mFlags=0x00000000)} (has extras) }
,09-07 11:37:30.398  6153  6153 E Zygote  : accessInfo : 0
,09-07 11:37:30.398  1250  1378 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{51f3697 u-1 android.net.wifi.p2p.CONNECTION_STATE_CHANGE qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{cdffcb4 5678:com.samsung.android.app.FileShareServer/5005}
09-07 11:37:30.398  5678  5678 D FileShare-Server: ServerBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,09-07 11:37:30.398  5678  5678 V QC40_FileShareUiAdapter: isSupportedCommonUi [enabled]true
09-07 11:37:30.398  5678  5678 D QC40_FileShareUiAdapter: isSupportedCommonUi [appState]0
,09-07 11:37:30.408   554  1414 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -D idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
09-07 11:37:30.408   554  1414 D CommandListener: Clearing all IP addresses on wlan0
,09-07 11:37:30.408  1250  1630 D CSLegacyTypeTracker: Removing agent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true]}  network{502}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.106/24,fe80::4678:3eff:feeb:95ef/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains:  MTU: 0 TcpBufferSizes: 524288,1048576,1048576,524288,1048576,4194240}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN&VALIDATED LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -39]}  Score{60}  everValidated{true}  lastValidated{true}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} } wasDefault=true
09-07 11:37:30.408  1250  1630 D CSLegacyTypeTracker: Sending DISCONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 502] isDefaultNetwork=true
09-07 11:37:30.408  1250  1630 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
09-07 11:37:30.418   447   447 I rmt_storage: rmt_storage_connect_cb: clnt_h=0xa conn_h=0x7f88a3a010
09-07 11:37:30.418   447   447 I rmt_storage: rmt_storage_rw_iovec_cb: /boot/modem_fs1: clnt_h=0x7: req_h=0xa msg_id=3: R/W request received
09-07 11:37:30.418   447   447 I rmt_storage: wakelock acquired: 1, error no: 42
09-07 11:37:30.418   447   925 I rmt_storage: rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x7 Unblock worker thread (th_id: 547749098560)
09-07 11:37:30.418  1250  1416 D EntConnectivity: Not allowed due to - mEnabled false
09-07 11:37:30.418  1250  1623 D WifiStateMachine: SupplicantStoppingState: stopSupplicant  init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
09-07 11:37:30.418  1250  1250 I WifiTrafficPoller: evaluateTrafficStatsPolling
,09-07 11:37:30.418  1250  1250 D HS20StateMachine: Broadcast Received: android.net.wifi.STATE_CHANGE
09-07 11:37:30.418  1250  1250 D HS20StateMachine: [type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: false]
09-07 11:37:30.418  1250  1250 I WifiHs20Service: Broadcast received:android.net.wifi.STATE_CHANGE
09-07 11:37:30.418  1250  1628 I WifiHs20Service: Message received 5007
,09-07 11:37:30.418  1694  2100 D NetworkController: onReceive: intent=Intent { act=android.net.wifi.STATE_CHANGE flg=0x4000010 bqHint=4 VirtualScreenParam=Params{mDisplayId=-1, null, mFlags=0x00000000)} (has extras) }
,09-07 11:37:30.428  6153  6153 D TimaKeyStoreProvider: TimaSignature is unavailable
09-07 11:37:30.428  1944  1944 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.net.wifi.STATE_CHANGE
09-07 11:37:30.428  6153  6153 D ActivityThread: Added TimaKeyStore provider
09-07 11:37:30.428  1250  1623 D SecContentProvider2: query(), uri = 20 selection = getPromptCredentialsEnabled
,09-07 11:37:30.428  1694  1694 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
09-07 11:37:30.428  1694  2100 D NetworkController: onReceive: intent=Intent { act=android.net.wifi.WIFI_STATE_CHANGED flg=0x4000010 bqHint=4 VirtualScreenParam=Params{mDisplayId=-1, null, mFlags=0x00000000)} (has extras) }
,09-07 11:37:30.428  1694  1694 D HotspotTile: onReceive : 0, 0
,09-07 11:37:30.428  1694  2126 D QSTile.WifiTile: handleUpdateState  cb.changed 5 wifiEnabled : OFF 
,09-07 11:37:30.428  1694  1694 D QSTileView: handleLabelStateChanged() label = Wi-Fi cellWidth 148
,09-07 11:37:30.438  1250  1250 D HS20StateMachine: Broadcast Received: android.net.wifi.WIFI_STATE_CHANGED
09-07 11:37:30.438  1250  1250 I WifiHs20Service: Broadcast received:android.net.wifi.WIFI_STATE_CHANGED
09-07 11:37:30.438  1250  1628 I WifiHs20Service: Message received 5011
,09-07 11:37:30.438  1250  1250 D WifiNotificationController: SHOW_NOTI_MESSAGE : 17, visible : false, ssid : null, targetSSID : null, netId : -1, titleType : -1
09-07 11:37:30.438  1250  1250 D WifiNotificationController: showMaliciousHotspotDetectionNotification - MaliciousNetwork:null, visible:false
09-07 11:37:30.438  1250  1631 D ConnectivityManager: getMobileDataEnabled()+ subId=2147483643
09-07 11:37:30.438  1944  2744 D PhoneInterfaceManager: [PhoneIntfMgr] getDataEnabled: subId=2147483643 phoneId=0
09-07 11:37:30.438  5989  5989 D BluetoothAdapter: STATE_ON
,09-07 11:37:30.438  1944  2744 D PhoneInterfaceManager: [PhoneIntfMgr] getDataEnabled: subId=2147483643 retVal=true
,09-07 11:37:30.448  1250  1631 D ConnectivityManager: getMobileDataEnabled()- subId=2147483643 retVal=true
,09-07 11:37:30.448  5989  5989 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-07 11:37:30.448  5989  5989 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-07 11:37:30.448  5989  5989 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-07 11:37:30.448  5989  5989 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-07 11:37:30.448  5989  5989 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-07 11:37:30.448  5989  5989 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-07 11:37:30.448  5989  5989 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-07 11:37:30.448  5989  5989 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-07 11:37:30.448  5989  5989 D BluetoothAdapter: STATE_ON
,09-07 11:37:30.448  1250  1416 D Tethering: MasterInitialState.processMessage what=3
,09-07 11:37:30.448  1250  6168 I ApplicationPolicy: updateDataUsageMap
,09-07 11:37:30.448  1250  1250 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
,09-07 11:37:30.458  1250  1631 D ConnectivityManager: getMobileDataEnabled()+ subId=2147483643
,09-07 11:37:30.458  1250  1878 V AlarmManager:  remove PendingIntent] PendingIntent{f20b05d: PendingIntentRecord{b959dd2 android broadcastIntent}}
,09-07 11:37:30.458  1944  1963 D PhoneInterfaceManager: [PhoneIntfMgr] getDataEnabled: subId=2147483643 phoneId=0
,09-07 11:37:30.458  1944  1963 D PhoneInterfaceManager: [PhoneIntfMgr] getDataEnabled: subId=2147483643 retVal=true
,09-07 11:37:30.458  1250  1631 D ConnectivityManager: getMobileDataEnabled()- subId=2147483643 retVal=true
,09-07 11:37:30.458  5989  5989 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-07 11:37:30.458  1250  1371 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
09-07 11:37:30.458  1250  1371 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
09-07 11:37:30.458  1250  1371 D GpsLocationProvider: handleMessage msg = 4
,09-07 11:37:30.468  5989  5989 D BluetoothAdapter: STATE_ON
09-07 11:37:30.468   447   925 I rmt_storage: rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x7: req_h=0xa msg_id=3: Bytes written = 1572864
09-07 11:37:30.468   447   925 I rmt_storage: rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x7: req_h=0xa msg_id=3: Send response: res=0 err=0
09-07 11:37:30.468   447   925 I rmt_storage: rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x7 About to block rmt_storage client thread (th_id: 547749098560) wakelock released: 1, error no: 0
09-07 11:37:30.468   447   925 I rmt_storage: 
,09-07 11:37:30.468   447   447 I rmt_storage: rmt_storage_disconnect_cb: clnt_h=0xa conn_h=0x7f88a3a010
,09-07 11:37:30.468  1250  1250 D LocSvc_java: onReceive
09-07 11:37:30.468  1250  1250 D LocSvc_java: got connectivity action
09-07 11:37:30.468  1250  1250 D LocSvc_java: broadcast - no network connections
09-07 11:37:30.468  1250  1250 D LocSvc_java: Connectivity status : mWifiConnectivity - false; mWwanConnectivity - false
09-07 11:37:30.468  1250  1250 D LocSvc_java: Sending msg: 4 arg1:0 arg2:1
09-07 11:37:30.468  5989  5989 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-07 11:37:30.468  5989  5989 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-07 11:37:30.468  5989  5989 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-07 11:37:30.468  5989  5989 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-07 11:37:30.468  5989  5989 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-07 11:37:30.468  5989  5989 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-07 11:37:30.468  5989  5989 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-07 11:37:30.468  5989  5989 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-07 11:37:30.468  1250  1250 D LocSvc_java: handleMessage msg = 4
09-07 11:37:30.468  1250  1250 D LocSvc_java: getAGpsConnectionInfo connType - 4
09-07 11:37:30.468  1250  1250 D LocSvc_java: updateNetworkState connTyp: 4 unavailable info: [type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true] info.getType():1
09-07 11:37:30.468  1694  2100 D NetworkController: onReceive: intent=Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 bqHint=4 VirtualScreenParam=Params{mDisplayId=-1, null, mFlags=0x00000000)} (has extras) }
09-07 11:37:30.468  1250  1621 D NtpTrustedTime: currentTimeMillis() cache hit
09-07 11:37:30.468  1250  1621 D ConnectivityService: getAllNetworkState networkCapability  = [ Transports: WIFI Capabilities: WIFI_P2P&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
09-07 11:37:30.468  1250  1621 D NtpTrustedTime: currentTimeMillis() cache hit
09-07 11:37:30.468  1250  1621 V NetworkStats: advisePersistThreshold() given 9223372036854775, clamped to 2097152
09-07 11:37:30.468  1250  1621 D NtpTrustedTime: currentTimeMillis() cache hit
09-07 11:37:30.468  1250  1621 D NtpTrustedTime: currentTimeMillis() cache hit
,09-07 11:37:30.478  5989  5989 D BluetoothAdapter: STATE_ON
,09-07 11:37:30.478  5989  5989 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-07 11:37:30.478  1250  1250 V MARsPolicyManager: DataConnection: false
,09-07 11:37:30.478  3113  3113 D MusicLifecycle: com.google.android.music.net.NetworkMonitor$2 generated event: Broadcast received with context com.google.android.music.net.NetworkMonitor@23104e0 and intent Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 bqHint=4 VirtualScreenParam=Params{mDisplayId=-1, null, mFlags=0x00000000)} (has extras) }
,09-07 11:37:30.488  5045  5063 I SystemBroadcastReceiver: [#CMH#] Received broadcast 
09-07 11:37:30.488  5045  5063 I SystemBroadcastReceiver: [#CMH#] No one is registered with Event Id EVENT_NETWORK_CHANGED
,09-07 11:37:30.488  5045  5063 I SystemBroadcastReceiver: [#CMH#] onReceive completed 
09-07 11:37:30.488  1250  1721 D ConnectivityService: returning getNetworkInfo for network type 0 : [type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
09-07 11:37:30.488  1250  1721 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
09-07 11:37:30.488  1250  1721 D ConnectivityService: returning getNetworkInfo for network type 2 : [type: MOBILE_MMS[] - MOBILE_MMS, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
09-07 11:37:30.488  1250  1721 D ConnectivityService: returning getNetworkInfo for network type 3 : [type: MOBILE_SUPL[] - MOBILE_SUPL, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
09-07 11:37:30.488  1250  1721 D ConnectivityService: returning getNetworkInfo for network type 4 : [type: MOBILE_DUN[] - MOBILE_DUN, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
09-07 11:37:30.488  1250  1721 D ConnectivityService: returning getNetworkInfo for network type 5 : [type: MOBILE_HIPRI[] - MOBILE_HIPRI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
09-07 11:37:30.488  1250  1721 D ConnectivityService: returning getNetworkInfo for network type 7 : [type: BLUETOOTH[] - BLUETOOTH, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
09-07 11:37:30.488  1250  1721 D ConnectivityService: returning getNetworkInfo for network type 9 : [type: ETHERNET[] - ETHERNET, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
09-07 11:37:30.488  1250  1721 D ConnectivityService: returning getNetworkInfo for network type 10 : [type: MOBILE_FOTA[] - MOBILE_FOTA, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
09-07 11:37:30.488  1250  1721 D ConnectivityService: returning getNetworkInfo for network type 11 : [type: MOBILE_IMS[] - MOBILE_IMS, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
09-07 11:37:30.488  1250  1721 D ConnectivityService: returning getNetworkInfo for network type 12 : [type: MOBILE_CBS[] - MOBILE_CBS, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
09-07 11:37:30.488  1250  1721 D ConnectivityService: returning getNetworkInfo for network type 13 : [type: WIFI_P2P[] - WIFI_P2P, state: UNKNOWN/IDLE, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
09-07 11:37:30.488  1250  1721 D ConnectivityService: returning getNetworkInfo for network type 14 : [type: MOBILE_IA[] - MOBILE_IA, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
09-07 11:37:30.488  1250  1721 D ConnectivityService: returning getNetworkInfo for network type 15 : [type: MOBILE_EMERGENCY[] - MOBILE_EMERGENCY, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
09-07 11:37:30.488  1250  1721 D ConnectivityService: returning getNetworkInfo for network type 17 : [type: VPN[] - VPN, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
,09-07 11:37:30.488  1944  1963 D PhoneInterfaceManager: [PhoneIntfMgr] getDataEnabled: subId=2147483643 phoneId=0
,09-07 11:37:30.498  2140  2140 D NetworkChangeNotifierAutoDetect: Network connectivity changed, type is: 6
,09-07 11:37:30.498  5989  5989 D NetworkChangeNotifierAutoDetect: Network connectivity changed, type is: 6
,09-07 11:37:30.498  5989  5989 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-07 11:37:30.498  5989  5989 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-07 11:37:30.498  1250  1964 D ConnectivityService: returning getNetworkInfo for network type 0 : [type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
09-07 11:37:30.498  1250  1964 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
09-07 11:37:30.498  1250  1964 D ConnectivityService: returning getNetworkInfo for network type 2 : [type: MOBILE_MMS[] - MOBILE_MMS, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
09-07 11:37:30.498  1250  1964 D ConnectivityService: returning getNetworkInfo for network type 3 : [type: MOBILE_SUPL[] - MOBILE_SUPL, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
09-07 11:37:30.498  1250  1964 D ConnectivityService: returning getNetworkInfo for network type 4 : [type: MOBILE_DUN[] - MOBILE_DUN, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
09-07 11:37:30.498  1250  1964 D ConnectivityService: returning getNetworkInfo for network type 5 : [type: MOBILE_HIPRI[] - MOBILE_HIPRI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
09-07 11:37:30.498  1250  1964 D ConnectivityService: returning getNetworkInfo for network type 7 : [type: BLUETOOTH[] - BLUETOOTH, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
09-07 11:37:30.498  1250  1964 D ConnectivityService: returning getNetworkInfo for network type 9 : [type: ETHERNET[] - ETHERNET, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
09-07 11:37:30.498  1250  1964 D ConnectivityService: returning getNetworkInfo for network type 10 : [type: MOBILE_FOTA[] - MOBILE_FOTA, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
09-07 11:37:30.498  1250  1964 D ConnectivityService: returning getNetworkInfo for network type 11 : [type: MOBILE_IMS[] - MOBILE_IMS, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
09-07 11:37:30.498  1250  1964 D ConnectivityService: returning getNetworkInfo for network type 12 : [type: MOBILE_CBS[] - MOBILE_CBS, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
09-07 11:37:30.498  1250  1964 D ConnectivityService: returning getNetworkInfo for network type 13 : [type: WIFI_P2P[] - WIFI_P2P, state: UNKNOWN/IDLE, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
09-07 11:37:30.498  1250  1964 D ConnectivityService: returning getNetworkInfo for network type 14 : [type: MOBILE_IA[] - MOBILE_IA, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
09-07 11:37:30.498  1250  1964 D ConnectivityService: returning getNetworkInfo for network type 15 : [type: MOBILE_EMERGENCY[] - MOBILE_EMERGENCY, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
09-07 11:37:30.498  1250  1964 D ConnectivityService: returning getNetworkInfo for network type 17 : [type: VPN[] - VPN, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
,09-07 11:37:30.498  1250  2127 E IzatSvc_OSObserver: I/LocTech-Label :: OSOBSERVER :: Data Items In
09-07 11:37:30.498  1250  2127 E IzatSvc_OSObserver: I/LocTech-Value :: Data Item Value: Attach state: 0, Mac address valid: false, AP MAC address: [00:00:00:00:00:00], Wifi-Ap SSID Valid: false, SSID: 
09-07 11:37:30.508  1944  1963 D PhoneInterfaceManager: [PhoneIntfMgr] getDataEnabled: subId=2147483643 retVal=true
09-07 11:37:30.508  1250  1371 D TelephonyManager: getDataEnabled: retVal=true
,09-07 11:37:30.508  1250  2146 E LocSvc_ApiV02: I/<--- void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*) line 131 QMI_LOC_NOTIFY_WIFI_ATTACHMENT_STATUS_REQ_V02
,09-07 11:37:30.508  1250  2396 V BroadcastQueue: [deferred] Process cur broadcast BroadcastRecord{ba8b9bb u-1 android.net.wifi.STATE_CHANGE qIdx=3}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{e03cd16 6153:com.sec.android.diagmonagent/1000}
,09-07 11:37:30.518   554  1414 E Netd    : netlink response contains error (No such file or directory)
,09-07 11:37:30.518  1250  1630 D ConnectivityService: setProvNotificationVisibleIntent SIGN_IN visible=false networkType=WIFI extraInfo=null highPriority=false
09-07 11:37:30.518  1250  1630 D ConnectivityService: nai.networkMonitor.doQuit()
09-07 11:37:30.518  1250  1630 D NetworkMonitor/NetworkAgentInfo [WIFI () - 502]: doQuit - quitNow()
09-07 11:37:30.518  1250  1630 E ConnectivityService: updateNetworkInfo()
09-07 11:37:30.518  1250  1630 D ConnectivityService: NetworkAgentInfo [WIFI_P2P () - 501] EVENT_NETWORK_INFO_CHANGED, going from UNKNOWN to DISCONNECTED, reason = null, [ Transports: WIFI Capabilities: WIFI_P2P&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
09-07 11:37:30.518  1250  1630 E ConnectivityService: updateNetworkInfo()
09-07 11:37:30.518  1250  1630 D ConnectivityService: ignoring duplicate network state non-change. WIFI_P2P, state = DISCONNECTED
09-07 11:37:30.518  1944  2295 D TelephonyProvider: query: url=content://telephony/carriers/preferapn, projectionIn=[Ljava.lang.String;@8f25f46, selection=nullselectionArgs=null, sort=name ASC
,09-07 11:37:30.518  1944  2295 D TelephonyProvider: query: match = 5
,09-07 11:37:30.528  1944  2295 D TelephonyProvider: getPreferredApnId(subId = 2147483643),return -1
09-07 11:37:30.528  1944  2295 D TelephonyProvider: query: selection modified to edited!=2 and edited!=3 and edited!=5 and edited!=6
,09-07 11:37:30.528  6153  6153 W System  : ClassLoader referenced unknown path: /system/priv-app/DiagMonAgent/lib/arm64
,09-07 11:37:30.538  1250  1371 E GpsLocationProvider: No APN found to select.
,09-07 11:37:30.538  2207  6172 D MdnsClient: Multicast lock held. Releasing
09-07 11:37:30.538  1250  2010 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{f6c10f0 u-1 android.net.wifi.STATE_CHANGE qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{e03cd16 6153:com.sec.android.diagmonagent/1000}
,09-07 11:37:30.548  6153  6153 I DIAGMON_AGENT: [com.diagmondm.db.file.XDB(372/llIlIIIIlIIIIIlIlIII)] 
,09-07 11:37:30.598  2391  2391 I wpa_supplicant: Blacklist: Clear (all) 
09-07 11:37:30.598  2391  2391 I wpa_supplicant: nl80211: deinit ifname=p2p0 disabled_11b_rates=0
,09-07 11:37:30.628  6153  6153 I DIAGMON_AGENT: [com.sec.android.diagmonagent.DiagMonAgentApplication(59/onCreate)] nStatus : 0
,09-07 11:37:30.628  6153  6153 I DIAGMON_AGENT: [com.sec.android.diagmonagent.DiagMonAgentApplication(72/onCreate)] DiagMon DM Application Start !
,09-07 11:37:30.628  6153  6153 I DIAGMON_AGENT: [lllIIIIIIlllIlIIIIII(51/llIIIIlllllIIllIIllI)] Receive broadcast: android.net.wifi.STATE_CHANGE
,09-07 11:37:30.628  6153  6153 I DIAGMON_AGENT: [lllIIIIIIlllIlIIIIII(52/llIIIIlllllIIllIIllI)] Receive broadcast:
09-07 11:37:30.628  6153  6153 I DIAGMON_AGENT: ./bssid: f4:f2:6d:22:99:3e
09-07 11:37:30.628  6153  6153 W DIAGMON_AGENT: [lllIIIIIIlllIlIIIIII(31/llIIIIlllllIIllIIllI)] Network is changed and not available now, so don't do anything
,09-07 11:37:30.628  6153  6153 I DIAGMON_AGENT: [lllIIIIIIlllIlIIIIII(51/llIIIIlllllIIllIIllI)] Receive broadcast: android.net.wifi.STATE_CHANGE
09-07 11:37:30.628  6153  6153 I DIAGMON_AGENT: [lllIIIIIIlllIlIIIIII(52/llIIIIlllllIIllIIllI)] Receive broadcast:
09-07 11:37:30.628  6153  6153 W DIAGMON_AGENT: [lllIIIIIIlllIlIIIIII(31/llIIIIlllllIIllIIllI)] Network is changed and not available now, so don't do anything
,09-07 11:37:30.648  6173  6173 E Zygote  : v2
09-07 11:37:30.648  6173  6173 I libpersona: KNOX_SDCARD checking this for 1000
09-07 11:37:30.648  2391  2391 I wpa_supplicant: p2p0: CTRL-EVENT-TERMINATING 
09-07 11:37:30.648  6173  6173 I libpersona: KNOX_SDCARD not a persona
09-07 11:37:30.648   766  1446 I QC-NETMGR-LIB: Received nl msg, recvmsg returned 1084
09-07 11:37:30.648   766  1446 I QC-NETMGR-LIB: Received command: ID=NETMGR_KIF_MSG_CMD, link=0
09-07 11:37:30.648   766  1442 I QC-NETMGR-LIB: Process command: ID=NETMGR_KIF_MSG_CMD, link=0, state=1
09-07 11:37:30.648   766  1442 I QC-NETMGR-LIB: Processing RTM_NEWLINK
09-07 11:37:30.648   766  1442 I QC-NETMGR-LIB: Metainfo:  Index=14 Family=0 Type=0x1 Change=[0x1]UP  Flags=[0x1002]BROADCAST MULTICAST 
09-07 11:37:30.648   766  1442 I QC-NETMGR-LIB: Rcvd Netlink msg type [16]
09-07 11:37:30.648   766  1442 I QC-NETMGR-LIB: Received RTM_NEWLINK
09-07 11:37:30.648  1250  1310 I ActivityManager: Start proc 6173:com.sec.app.RilErrorNotifier/1000 for broadcast-5 com.sec.app.RilErrorNotifier/.PhoneErrorReceiver
09-07 11:37:30.648   766  1442 E QC-NETMGR-LIB: unrecognized ifindex 14, disable link
,09-07 11:37:30.648  6173  6173 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0013
09-07 11:37:30.648   554  1406 D Netd    : Iface p2p0 link down
,09-07 11:37:30.648  6173  6173 E Zygote  : accessInfo : 0
,09-07 11:37:30.648  1250  1310 I ActivityManager: Killing 5330:com.sec.android.soagent/1000 (adj 15): DHA:empty #31
,09-07 11:37:30.658   766  1446 I QC-NETMGR-LIB: Received nl msg, recvmsg returned 1084
09-07 11:37:30.658   766  1446 I QC-NETMGR-LIB: Received command: ID=NETMGR_KIF_MSG_CMD, link=0
09-07 11:37:30.658   766  1442 I QC-NETMGR-LIB: Process command: ID=NETMGR_KIF_MSG_CMD, link=0, state=1
09-07 11:37:30.658   766  1442 I QC-NETMGR-LIB: Processing RTM_NEWLINK
09-07 11:37:30.658   766  1442 I QC-NETMGR-LIB: Metainfo:  Index=13 Family=0 Type=0x1 Change=[0x0] Flags=[0x1003]UP BROADCAST MULTICAST 
09-07 11:37:30.658   554  1406 D Netd    : Iface wlan0 link down
09-07 11:37:30.658   766  1442 I QC-NETMGR-LIB: Rcvd Netlink msg type [16]
09-07 11:37:30.658   766  1442 I QC-NETMGR-LIB: Received RTM_NEWLINK
09-07 11:37:30.658   766  1442 E QC-NETMGR-LIB: unrecognized ifindex 13, disable link
,09-07 11:37:30.658  2391  2391 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
09-07 11:37:30.658  2391  2391 I wpa_supplicant: Prev BSS - hexdump(len=6): f4 f2 6d 22 99 3e
09-07 11:37:30.658   766  1446 I QC-NETMGR-LIB: Received nl msg, recvmsg returned 76
09-07 11:37:30.658   766  1446 I QC-NETMGR-LIB: Received command: ID=NETMGR_KIF_MSG_CMD, link=0
,09-07 11:37:30.658   766  1446 I QC-NETMGR-LIB: Received nl msg, recvmsg returned 72
09-07 11:37:30.658  1250  1378 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{f6c10f0 u-1 android.net.wifi.STATE_CHANGE qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{195a0dd 5691:com.enhance.gameservice/u0a79}
09-07 11:37:30.658   766  1446 I QC-NETMGR-LIB: Received command: ID=NETMGR_KIF_MSG_CMD, link=0
09-07 11:37:30.658  1250  1416 D Tethering: InitialState.processMessage what=4
09-07 11:37:30.658   554  1406 D Netd    : Iface wlan0 link down
09-07 11:37:30.658   554  1406 D Netd    : Iface wlan0 link down
09-07 11:37:30.658  1250  1416 D Tethering: NAP Supported and not Wifi Model
09-07 11:37:30.658   766  1442 I QC-NETMGR-LIB: Process command: ID=NETMGR_KIF_MSG_CMD, link=0, state=1
09-07 11:37:30.658   766  1442 I QC-NETMGR-LIB: Processing RTM_NEWLINK
09-07 11:37:30.658   766  1442 I QC-NETMGR-LIB: Metainfo:  Index=13 Family=0 Type=0x1 Change=[0x0] Flags=[0x1043]UP BROADCAST RUNNING MULTICAST 
09-07 11:37:30.658   766  1442 I QC-NETMGR-LIB: Rcvd Netlink msg type [16]
09-07 11:37:30.658   766  1442 I QC-NETMGR-LIB: Received RTM_NEWLINK
09-07 11:37:30.658   766  1442 E QC-NETMGR-LIB: unrecognized ifindex 13, disable link
09-07 11:37:30.658   766  1442 I QC-NETMGR-LIB: Process command: ID=NETMGR_KIF_MSG_CMD, link=0, state=1
09-07 11:37:30.658   766  1442 I QC-NETMGR-LIB: Processing RTM_NEWLINK
09-07 11:37:30.658   766  1442 I QC-NETMGR-LIB: Metainfo:  Index=13 Family=0 Type=0x1 Change=[0x0] Flags=[0x1043]UP BROADCAST RUNNING MULTICAST 
09-07 11:37:30.658   766  1442 I QC-NETMGR-LIB: Rcvd Netlink msg type [16]
09-07 11:37:30.658   766  1442 I QC-NETMGR-LIB: Received RTM_NEWLINK
09-07 11:37:30.658   766  1442 E QC-NETMGR-LIB: unrecognized ifindex 13, disable link
,09-07 11:37:30.658  1250  1416 E Tethering: No numeric data
,09-07 11:37:30.668  1250  1378 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{13f68ee u-1 android.net.wifi.WIFI_STATE_CHANGED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{9925d68 5989:com.test.thalitest/u0a136}
09-07 11:37:30.668  1250  1416 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
09-07 11:37:30.668  1250  1620 D NtpTrustedTime: currentTimeMillis() cache hit
09-07 11:37:30.668  1250  1994 D ConnectivityService: returning getNetworkInfo for network type 0 : [type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
09-07 11:37:30.668  1694  1694 D HotspotTile: onReceive : android.net.conn.TETHER_STATE_CHANGED
09-07 11:37:30.668  1250  1994 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
09-07 11:37:30.668  1694  1694 D HotspotTile: updateTetherState():false, false
09-07 11:37:30.668  1250  1994 D ConnectivityService: returning getNetworkInfo for network type 2 : [type: MOBILE_MMS[] - MOBILE_MMS, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
09-07 11:37:30.668  1250  1620 V NetworkStats: performPollLocked(flags=0x1)
09-07 11:37:30.668  1250  1994 D ConnectivityService: returning getNetworkInfo for network type 3 : [type: MOBILE_SUPL[] - MOBILE_SUPL, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
09-07 11:37:30.668  1250  1994 D ConnectivityService: returning getNetworkInfo for network type 4 : [type: MOBILE_DUN[] - MOBILE_DUN, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
09-07 11:37:30.668  1250  1994 D ConnectivityService: returning getNetworkInfo for network type 5 : [type: MOBILE_HIPRI[] - MOBILE_HIPRI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
09-07 11:37:30.668  1250  1994 D ConnectivityService: returning getNetworkInfo for network type 7 : [type: BLUETOOTH[] - BLUETOOTH, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
09-07 11:37:30.668  1250  1994 D ConnectivityService: returning getNetworkInfo for network type 9 : [type: ETHERNET[] - ETHERNET, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
09-07 11:37:30.668  1250  1994 D ConnectivityService: returning getNetworkInfo for network type 10 : [type: MOBILE_FOTA[] - MOBILE_FOTA, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
09-07 11:37:30.668  1250  1994 D ConnectivityService: returning getNetworkInfo for network type 11 : [type: MOBILE_IMS[] - MOBILE_IMS, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
09-07 11:37:30.668  1250  1994 D ConnectivityService: returning getNetworkInfo for network type 12 : [type: MOBILE_CBS[] - MOBILE_CBS, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
09-07 11:37:30.668  1250  1994 D ConnectivityService: returning getNetworkInfo for network type 13 : [type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: false]
09-07 11:37:30.668  1250  1994 D ConnectivityService: returning getNetworkInfo for network type 14 : [type: MOBILE_IA[] - MOBILE_IA, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
09-07 11:37:30.668  1250  1994 D ConnectivityService: returning getNetworkInf,o for network type 15 : [type: MOBILE_EMERGENCY[] - MOBILE_EMERGENCY, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
09-07 11:37:30.668  1250  1994 D ConnectivityService: returning getNetworkInfo for network type 17 : [type: VPN[] - VPN, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
09-07 11:37:30.668  1250  1620 D NetworkStatsRecorder: entry.iface is null
09-07 11:37:30.668  1250  1620 D NetworkStatsRecorder: entry.iface is null
09-07 11:37:30.668  1250  1620 D NtpTrustedTime: currentTimeMillis() cache hit
09-07 11:37:30.668  1250  1620 D NetworkStatsRecorder: entry.iface is null
09-07 11:37:30.668  1250  1620 D NetworkStatsRecorder: entry.iface is null
09-07 11:37:30.668  1250  1620 V NetworkStats: performPollLocked() took 3ms
,09-07 11:37:30.678  1250  1621 D NtpTrustedTime: currentTimeMillis() cache hit
09-07 11:37:30.678  1250  1621 D NtpTrustedTime: currentTimeMillis() cache hit
,09-07 11:37:30.678  1250  1378 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{c618f u-1 android.net.conn.CONNECTIVITY_CHANGE qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{9925d68 5989:com.test.thalitest/u0a136}
,09-07 11:37:30.678  1250  1720 D ConnectivityService: returning getNetworkInfo for network type 0 : [type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
09-07 11:37:30.678  1250  1720 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
09-07 11:37:30.678  1250  1720 D ConnectivityService: returning getNetworkInfo for network type 2 : [type: MOBILE_MMS[] - MOBILE_MMS, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
09-07 11:37:30.678  1250  1720 D ConnectivityService: returning getNetworkInfo for network type 3 : [type: MOBILE_SUPL[] - MOBILE_SUPL, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
09-07 11:37:30.678  1250  1720 D ConnectivityService: returning getNetworkInfo for network type 4 : [type: MOBILE_DUN[] - MOBILE_DUN, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
09-07 11:37:30.678  1250  1720 D ConnectivityService: returning getNetworkInfo for network type 5 : [type: MOBILE_HIPRI[] - MOBILE_HIPRI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
09-07 11:37:30.678  1250  1720 D ConnectivityService: returning getNetworkInfo for network type 7 : [type: BLUETOOTH[] - BLUETOOTH, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
09-07 11:37:30.678  1250  1720 D ConnectivityService: returning getNetworkInfo for network type 9 : [type: ETHERNET[] - ETHERNET, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
09-07 11:37:30.678  1250  1720 D ConnectivityService: returning getNetworkInfo for network type 10 : [type: MOBILE_FOTA[] - MOBILE_FOTA, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
09-07 11:37:30.678  1250  1720 D ConnectivityService: returning getNetworkInfo for network type 11 : [type: MOBILE_IMS[] - MOBILE_IMS, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
09-07 11:37:30.678  1250  1720 D ConnectivityService: returning getNetworkInfo for network type 12 : [type: MOBILE_CBS[] - MOBILE_CBS, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
09-07 11:37:30.678  1250  1720 D ConnectivityService: returning getNetworkInfo for network type 13 : [type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: false]
09-07 11:37:30.678  1250  1720 D ConnectivityService: returning getNetworkInfo for network type 14 : [type: MOBILE_IA[] - MOBILE_IA, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
09-07 11:37:30.678  1250  1720 D ConnectivityService: returning getNetworkInfo for network type 15 : [type: MOBILE_EMERGENCY[] - MOBILE_EMERGENCY, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
09-07 11:37:30.678  1250  1720 D ConnectivityService: returning getNetworkInfo for network type 17 : [type: VPN[] - VPN, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
,09-07 11:37:30.688  1250  1313 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{c618f u-1 android.net.conn.CONNECTIVITY_CHANGE qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{667d8b1 1250:system/1000}
09-07 11:37:30.688  6173  6173 D TimaKeyStoreProvider: TimaSignature is unavailable
09-07 11:37:30.688  6173  6173 D ActivityThread: Added TimaKeyStore provider
09-07 11:37:30.688  1250  1250 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{c618f u-1 android.net.conn.CONNECTIVITY_CHANGE qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{7a2c63a 2207:com.google.android.gms/u0a10}
,09-07 11:37:30.688  2207  2207 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,09-07 11:37:30.688  2207  3201 I iu.UploadsManager: num queued entries: 0
,09-07 11:37:30.698  2207  3201 I iu.UploadsManager: num updated entries: 0
09-07 11:37:30.698  1250  2396 V BroadcastQueue: [deferred] Process cur broadcast BroadcastRecord{ba8b9bb u-1 android.net.wifi.STATE_CHANGE qIdx=3}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{7cc8669 6173:com.sec.app.RilErrorNotifier/1000}
09-07 11:37:30.698  2207  3201 I iu.SyncManager: NEXT; no task
,09-07 11:37:30.698  1250  1313 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{c618f u-1 android.net.conn.CONNECTIVITY_CHANGE qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{7a2c63a 2207:com.google.android.gms/u0a10}
,09-07 11:37:30.698  1250  2333 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{c618f u-1 android.net.conn.CONNECTIVITY_CHANGE qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{ef1b27 1866:com.google.android.gms.persistent/u0a10}
,09-07 11:37:30.708  6173  6173 W System  : ClassLoader referenced unknown path: /system/priv-app/PhoneErrService/lib/arm64
,09-07 11:37:30.708  1250  1378 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{c618f u-1 android.net.conn.CONNECTIVITY_CHANGE qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{a0c9664 5242:com.wssyncmldm/1000}
,09-07 11:37:30.718  5989  5989 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,09-07 11:37:30.718  1250  1378 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{e994c1c u-1 android.net.conn.TETHER_STATE_CHANGED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{667d8b1 1250:system/1000}
,09-07 11:37:30.718  6173  6173 I PhoneErrorReceiver: onReceive
09-07 11:37:30.718  6173  6173 I MIPErrReceiver: isWiFiConnected
,09-07 11:37:30.718  1250  1990 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
,09-07 11:37:30.738  6185  6185 E Zygote  : v2
09-07 11:37:30.738  6185  6185 I libpersona: KNOX_SDCARD checking this for 1000
09-07 11:37:30.738  6185  6185 I libpersona: KNOX_SDCARD not a persona
,09-07 11:37:30.738  6185  6185 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0013
,09-07 11:37:30.738  1250  1313 I ActivityManager: Start proc 6185:com.sec.knox.switcher/1000 for broadcast-5 com.sec.knox.switcher/.knoxusage.KnoxUsageReceiver
09-07 11:37:30.738  6185  6185 E Zygote  : accessInfo : 0
,09-07 11:37:30.738  1250  1313 I ActivityManager: Killing 5516:com.samsung.faceservice/5004 (adj 15): DHA:empty #31
,09-07 11:37:30.748  1250  2327 D ActivityManager: isAutoRunBlockedApp:: com.sec.android.soagent, Auto Run ON
09-07 11:37:30.748  1250  2327 D ActivityManager: removeProcessNameLocked mProcessNames.remove pid=5330 ,hash=74692852 ,name=com.sec.android.soagent
,09-07 11:37:30.778  6185  6185 D TimaKeyStoreProvider: TimaSignature is unavailable
09-07 11:37:30.778  6185  6185 D ActivityThread: Added TimaKeyStore provider
,09-07 11:37:30.778  1250  2010 V BroadcastQueue: [deferred] Process cur broadcast BroadcastRecord{ba8b9bb u-1 android.net.wifi.STATE_CHANGE qIdx=3}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{61e2025 6185:com.sec.knox.switcher/1000}
,09-07 11:37:30.798  6185  6185 W System  : ClassLoader referenced unknown path: /system/app/KnoxSwitcher/lib/arm64
,09-07 11:37:30.798  5045  5045 I ServiceManager: [#CMH#] Disconnected to Service  com.samsung.faceservice.FaceService
09-07 11:37:30.798  1250  1721 D ActivityManager: isAutoRunBlockedApp:: com.samsung.faceservice, Auto Run ON
09-07 11:37:30.798  1250  1721 W ActivityManager: Scheduling restart of crashed service com.samsung.faceservice/.FaceService in 1000ms
09-07 11:37:30.798  1250  1721 D ActivityManager: removeProcessNameLocked mProcessNames.remove pid=5516 ,hash=242349133 ,name=com.samsung.faceservice
,09-07 11:37:30.798  6185  6185 D KnoxUsageDB: getInstance - KnoxUsageDBHelper
09-07 11:37:30.798  6185  6185 D KnoxUsageDB: null == mDbHelperInstance - KnoxUsageDBHelper
,09-07 11:37:30.808  6185  6185 I usagelog: received in receiver
09-07 11:37:30.808  6185  6185 I KnoxUsageLogPro: KnoxUsageReceiver onReceive :android.net.wifi.STATE_CHANGE myUserId=0
,09-07 11:37:30.808  6185  6185 I KnoxUsageLogPro: premStatus:2
,09-07 11:37:30.808  6185  6185 I KnoxUsageLogPro: isEulaShown : false
09-07 11:37:30.808  6185  6185 I KnoxUsageLogPro: KnoxUsageReceiver onReceive : not Processible, just return
,09-07 11:37:30.828  6197  6197 E Zygote  : v2
09-07 11:37:30.828  6197  6197 I libpersona: KNOX_SDCARD checking this for 5005
09-07 11:37:30.828  6197  6197 I libpersona: KNOX_SDCARD not a persona
,09-07 11:37:30.828  6197  6197 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0013
,09-07 11:37:30.828  1250  1720 I ActivityManager: Start proc 6197:com.samsung.android.app.FileShareClient/5005 for broadcast-5 com.samsung.android.app.FileShareClient/.ClientBroadcastReceiver
,09-07 11:37:30.828  6197  6197 E Zygote  : accessInfo : 0
09-07 11:37:30.828  6197  6197 W SELinux : SELinux: seapp_context_lookup: seinfo=platform, level=s0:c512,c768, pkgname=com.samsung.android.app.FileShareClient 
,09-07 11:37:30.828  1250  1720 I ActivityManager: Killing 5503:com.samsung.ipservice/5004 (adj 15): DHA:empty #31
,09-07 11:37:30.858  6197  6197 D TimaKeyStoreProvider: TimaSignature is unavailable
09-07 11:37:30.858  6197  6197 D ActivityThread: Added TimaKeyStore provider
,09-07 11:37:30.868  1250  2674 V BroadcastQueue: [deferred] Process cur broadcast BroadcastRecord{51f3697 u-1 android.net.wifi.p2p.CONNECTION_STATE_CHANGE qIdx=3}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{a3d25fa 6197:com.samsung.android.app.FileShareClient/5005}
,09-07 11:37:30.888  2391  2391 I wpa_supplicant: Blacklist: Clear (all) 
09-07 11:37:30.888  6197  6197 W System  : ClassLoader referenced unknown path: /system/app/AllshareFileShareClient/lib/arm64
09-07 11:37:30.888  2391  2391 I wpa_supplicant: nl80211: deinit ifname=wlan0 disabled_11b_rates=0
,09-07 11:37:30.898  6197  6197 D FileShare-Client: ClientBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,09-07 11:37:30.898  6197  6197 D FileShare-Client: ClientBroadcastReceiver.onReceive - disconnected
,09-07 11:37:30.918  6197  6197 D FileShare-Client: Outbound.stopDelayTimer - 
,09-07 11:37:30.928  1250  1986 V BroadcastQueue: [deferred] Process cur broadcast BroadcastRecord{f6c10f0 u-1 android.net.wifi.STATE_CHANGE qIdx=3}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{7cc8669 6173:com.sec.app.RilErrorNotifier/1000}
,09-07 11:37:30.928  6173  6173 I PhoneErrorReceiver: onReceive
09-07 11:37:30.928  6173  6173 I MIPErrReceiver: isWiFiConnected
09-07 11:37:30.928  1250  2327 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
,09-07 11:37:30.928  5045  5045 I ServiceManager: [#CMH#] Disconnected to Service  com.samsung.ipservice.IPService
,09-07 11:37:30.928  1250  1986 V BroadcastQueue: [deferred] Process cur broadcast BroadcastRecord{f6c10f0 u-1 android.net.wifi.STATE_CHANGE qIdx=3}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{61e2025 6185:com.sec.knox.switcher/1000}
09-07 11:37:30.928  6185  6185 I usagelog: received in receiver
09-07 11:37:30.928  6185  6185 I KnoxUsageLogPro: KnoxUsageReceiver onReceive :android.net.wifi.STATE_CHANGE myUserId=0
09-07 11:37:30.928  6185  6185 I KnoxUsageLogPro: premStatus:2
,09-07 11:37:30.928  6185  6185 I KnoxUsageLogPro: isEulaShown : false
09-07 11:37:30.928  6185  6185 I KnoxUsageLogPro: KnoxUsageReceiver onReceive : not Processible, just return
,09-07 11:37:30.928  1250  1310 D ActivityManager: removeProcessNameLocked mProcessNames.remove pid=5503 ,hash=54078838 ,name=com.samsung.ipservice
09-07 11:37:30.928  1250  1310 D ActivityManager: isAutoRunBlockedApp:: com.samsung.ipservice, Auto Run ON
09-07 11:37:30.928  1250  1310 W ActivityManager: Scheduling restart of crashed service com.samsung.ipservice/.IPService in 10866ms
,09-07 11:37:30.948   766  1446 I QC-NETMGR-LIB: Received nl msg, recvmsg returned 1084
09-07 11:37:30.948   766  1446 I QC-NETMGR-LIB: Received command: ID=NETMGR_KIF_MSG_CMD, link=0
09-07 11:37:30.948   766  1442 I QC-NETMGR-LIB: Process command: ID=NETMGR_KIF_MSG_CMD, link=0, state=1
09-07 11:37:30.948   766  1442 I QC-NETMGR-LIB: Processing RTM_NEWLINK
09-07 11:37:30.948   766  1442 I QC-NETMGR-LIB: Metainfo:  Index=13 Family=0 Type=0x1 Change=[0x1]UP  Flags=[0x1002]BROADCAST MULTICAST 
09-07 11:37:30.948   766  1442 I QC-NETMGR-LIB: Rcvd Netlink msg type [16]
09-07 11:37:30.948   766  1442 I QC-NETMGR-LIB: Received RTM_NEWLINK
09-07 11:37:30.948   554  1406 D Netd    : Iface wlan0 link down
09-07 11:37:30.948   766  1442 E QC-NETMGR-LIB: unrecognized ifindex 13, disable link
09-07 11:37:30.948  2391  2391 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING 
,09-07 11:37:30.948  6209  6209 E Zygote  : v2
09-07 11:37:30.948  1250  2396 I ActivityManager: Start proc 6209:com.samsung.android.securitylogagent/1000 for broadcast-5 com.samsung.android.securitylogagent/.receivers.NetworkReceiver
09-07 11:37:30.948   766  1446 I QC-NETMGR-LIB: Received nl msg, recvmsg returned 64
09-07 11:37:30.948  6209  6209 I libpersona: KNOX_SDCARD checking this for 1000
09-07 11:37:30.948   766  1446 I QC-NETMGR-LIB: Received command: ID=NETMGR_KIF_MSG_CMD, link=0
09-07 11:37:30.948  6209  6209 I libpersona: KNOX_SDCARD not a persona
09-07 11:37:30.948   766  1442 I QC-NETMGR-LIB: Process command: ID=NETMGR_KIF_MSG_CMD, link=0, state=1
09-07 11:37:30.948   766  1442 I QC-NETMGR-LIB: Processing RTM_DELADDR
09-07 11:37:30.948  1250  2396 I ActivityManager: Killing 5069:com.samsung.dcmservice/5004 (adj 15): DHA:empty #31
09-07 11:37:30.948   766  1442 I QC-NETMGR-LIB: Metainfo:  Family=10 PrefixLen=64 Scope=0xfd Index=13 Flags=[0xc4]OPTIMISTIC TENTATIVE PERMANENT 
09-07 11:37:30.948   766  1442 I QC-NETMGR-LIB: Attribute: PrefixIPv6 addr [fe80:0000:0000:0000:4678:3eff:feeb:95ef]
09-07 11:37:30.948   766  1442 I QC-NETMGR-LIB: Attribute: Address Cache Info - prefered=-1 valid=-1 cstamp=0x3831 tstamp=0x3831
09-07 11:37:30.948   766  1442 I QC-NETMGR-LIB: Rcvd Netlink msg type [21]
09-07 11:37:30.948   766  1442 E QC-NETMGR-LIB: unrecognized ifindex 13
,09-07 11:37:30.958  6209  6209 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0013
,09-07 11:37:30.958  6209  6209 E Zygote  : accessInfo : 0
,09-07 11:37:30.998  6209  6209 D TimaKeyStoreProvider: TimaSignature is unavailable
09-07 11:37:30.998  6209  6209 D ActivityThread: Added TimaKeyStore provider
,09-07 11:37:30.998  1250  2327 V BroadcastQueue: [deferred] Process cur broadcast BroadcastRecord{13f68ee u-1 android.net.wifi.WIFI_STATE_CHANGED qIdx=3}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{6f787ab 6209:com.samsung.android.securitylogagent/1000}
,09-07 11:37:31.008  5045  5045 I ServiceManager: [#CMH#] Disconnected to Service  com.samsung.dcmservice.DCMService
09-07 11:37:31.008  1250  1990 D ActivityManager: isAutoRunBlockedApp:: com.samsung.dcmservice, Auto Run ON
09-07 11:37:31.008  1250  1990 W ActivityManager: Scheduling restart of crashed service com.samsung.dcmservice/.DCMService in 20792ms
09-07 11:37:31.008  1250  1990 D ActivityManager: removeProcessNameLocked mProcessNames.remove pid=5069 ,hash=50891831 ,name=com.samsung.dcmservice
,09-07 11:37:31.018  6209  6209 W System  : ClassLoader referenced unknown path: /system/app/SecurityLogAgent/lib/arm64
,09-07 11:37:31.038  6221  6221 E Zygote  : v2
09-07 11:37:31.038  6221  6221 I libpersona: KNOX_SDCARD checking this for 1000
09-07 11:37:31.038  6221  6221 I libpersona: KNOX_SDCARD not a persona
,09-07 11:37:31.038  6221  6221 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0013
09-07 11:37:31.038  1250  2010 I ActivityManager: Start proc 6221:com.policydm/1000 for broadcast-5 com.policydm/.XDMBroadcastReceiver
,09-07 11:37:31.038  6221  6221 E Zygote  : accessInfo : 0
09-07 11:37:31.038  1250  2010 I ActivityManager: Killing 5045:com.samsung.cmh:CMH/5004 (adj 15): DHA:empty #31
,09-07 11:37:31.058  1250  1623 D WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:0
,09-07 11:37:31.058  1250  1250 D WifiNotificationController: SHOW_NOTI_MESSAGE : 9, visible : false, ssid : <unknown ssid>, targetSSID : null, netId : -1, titleType : -1
,09-07 11:37:31.058  1250  1250 D WifiNotificationController: SHOW_NOTI_MESSAGE : 13, visible : false, ssid : <unknown ssid>, targetSSID : null, netId : -1, titleType : 0
09-07 11:37:31.058  1250  1250 D WifiNotificationController: showCaptivePortalDisabledStatus with ssid/visible/title:null/false/0
,09-07 11:37:31.058  1250  1250 D HS20StateMachine: Broadcast Received: android.net.wifi.WIFI_STATE_CHANGED
09-07 11:37:31.058  1250  1250 I WifiHs20Service: Broadcast received:android.net.wifi.WIFI_STATE_CHANGED
09-07 11:37:31.058  1250  1625 D HS20StateMachine: WIFI_STATE_DISABLED
09-07 11:37:31.058  1250  1625 D HS20StateMachine: CMD_HOTSPOT20_DISABLE
09-07 11:37:31.058  1250  1625 D HS20StateMachine: enter : DisablingState
09-07 11:37:31.058  1250  1628 I WifiHs20Service: Message received 5011
09-07 11:37:31.058  1250  1627 D HS20SubscriptionManager: Received CMD_RELEASE_TLS, flag=1
09-07 11:37:31.058  1250  1625 D HS20StateMachine: enter : DisabledState
,09-07 11:37:31.068  1250  1631 D ConnectivityManager: getMobileDataEnabled()+ subId=2147483643
,09-07 11:37:31.068  1694  2100 D NetworkController: onReceive: intent=Intent { act=android.net.wifi.WIFI_STATE_CHANGED flg=0x4000010 bqHint=4 VirtualScreenParam=Params{mDisplayId=-1, null, mFlags=0x00000000)} (has extras) }
09-07 11:37:31.068  1694  1694 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
09-07 11:37:31.068  1944  2744 D PhoneInterfaceManager: [PhoneIntfMgr] getDataEnabled: subId=2147483643 phoneId=0
09-07 11:37:31.068  1694  1694 D HotspotTile: onReceive : 1, 0
,09-07 11:37:31.068  1944  2744 D PhoneInterfaceManager: [PhoneIntfMgr] getDataEnabled: subId=2147483643 retVal=true
09-07 11:37:31.068  1250  1631 D ConnectivityManager: getMobileDataEnabled()- subId=2147483643 retVal=true
,09-07 11:37:31.068  1866  2363 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-07 11:37:31.068  5989  5989 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-07 11:37:31.068  1250  1378 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{73599a1 u-1 android.net.wifi.WIFI_STATE_CHANGED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{9925d68 5989:com.test.thalitest/u0a136}
,09-07 11:37:31.068  5989  5989 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-07 11:37:31.078  1250  1994 D ConnectivityService: returning getNetworkInfo for network type 0 : [type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
09-07 11:37:31.078  1250  1994 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
09-07 11:37:31.078  1250  1994 D ConnectivityService: returning getNetworkInfo for network type 2 : [type: MOBILE_MMS[] - MOBILE_MMS, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
09-07 11:37:31.078  1250  1994 D ConnectivityService: returning getNetworkInfo for network type 3 : [type: MOBILE_SUPL[] - MOBILE_SUPL, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
09-07 11:37:31.078  1250  1994 D ConnectivityService: returning getNetworkInfo for network type 4 : [type: MOBILE_DUN[] - MOBILE_DUN, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
09-07 11:37:31.078  1250  1994 D ConnectivityService: returning getNetworkInfo for network type 5 : [type: MOBILE_HIPRI[] - MOBILE_HIPRI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
09-07 11:37:31.078  1250  1994 D ConnectivityService: returning getNetworkInfo for network type 7 : [type: BLUETOOTH[] - BLUETOOTH, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
09-07 11:37:31.078  1250  1994 D ConnectivityService: returning getNetworkInfo for network type 9 : [type: ETHERNET[] - ETHERNET, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
09-07 11:37:31.078  1250  1994 D ConnectivityService: returning getNetworkInfo for network type 10 : [type: MOBILE_FOTA[] - MOBILE_FOTA, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
09-07 11:37:31.078  1250  1994 D ConnectivityService: returning getNetworkInfo for network type 11 : [type: MOBILE_IMS[] - MOBILE_IMS, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
09-07 11:37:31.078  1250  1994 D ConnectivityService: returning getNetworkInfo for network type 12 : [type: MOBILE_CBS[] - MOBILE_CBS, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
09-07 11:37:31.078  1250  1994 D ConnectivityService: returning getNetworkInfo for network type 13 : [type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: false]
09-07 11:37:31.078  1250  1994 D ConnectivityService: returning getNetworkInfo for network type 14 : [type: MOBILE_IA[] - MOBILE_IA, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
09-07 11:37:31.078  1250  1994 D ConnectivityService: returning getNetworkInfo for network type 15 : [type: MOBILE_EMERGENCY[] - MOBILE_EMERGENCY, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
09-07 11:37:31.078  1250  1994 D ConnectivityService: returning getNetworkInfo for network type 17 : [type: VPN[] - VPN, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
,09-07 11:37:31.078  6221  6221 D TimaKeyStoreProvider: TimaSignature is unavailable
09-07 11:37:31.078  6221  6221 D ActivityThread: Added TimaKeyStore provider
,09-07 11:37:31.078  1250  2396 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{73599a1 u-1 android.net.wifi.WIFI_STATE_CHANGED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{6f787ab 6209:com.samsung.android.securitylogagent/1000}
,09-07 11:37:31.088  1250  2396 V BroadcastQueue: [deferred] Process cur broadcast BroadcastRecord{c618f u-1 android.net.conn.CONNECTIVITY_CHANGE qIdx=3}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{bfd0e08 6221:com.policydm/1000}
,09-07 11:37:31.098  6221  6221 W System  : ClassLoader referenced unknown path: /system/priv-app/SPDClient/lib/arm64
,09-07 11:37:31.118  6221  6221 I FOTA    : [lIlIIlIIlIlllIIIIlll(108/llIIIIlllllIIllIIllI)] oms: /customer.xml
,09-07 11:37:31.118  6221  6221 I FOTA    : [lIlIIlIIlIlllIIIIlll(199/lllIlIlIIIllIIlIllIl)] read default : /system/csc/customer.xml
,09-07 11:37:31.138  6221  6221 I FOTA    : [com.sec.android.policyagent.PolicyApplication(36/onCreate)] PolicyApplication onCreated!
,09-07 11:37:31.148  6221  6221 I DBG_POLICYDM: [com.policydm.db.XDB(1501/IllIlIIIIlIIlIIIllIl)] xdbDMffs_Init
,09-07 11:37:31.158  6221  6221 I DBG_POLICYDM: [com.policydm.db.llIIIIlllllIIllIIllI(142/llIIIIlllllIIllIIllI)] try read dbString
,09-07 11:37:31.168  1250  1994 D ActivityManager: isAutoRunBlockedApp:: com.samsung.cmh, Auto Run ON
,09-07 11:37:31.168  1250  1994 D ActivityManager: removeProcessNameLocked mProcessNames.remove pid=5045 ,hash=220814982 ,name=com.samsung.cmh:CMH
,09-07 11:37:31.168  5157  5157 I StoryService: [StoryService] On destroy() 
09-07 11:37:31.168  5157  5157 I ServiceController: [StoryService] shutdown() 
,09-07 11:37:31.248  6221  6221 I DBG_POLICYDM: [IlIIIllIlIIIlIIlIIlI(51/<init>)] 
,09-07 11:37:31.248  6221  6221 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1403 android.content.ContextWrapper.bindService:632 IlIIIllIlIIIlIIlIIlI.<init>:55 IIIlIIlllIlIlIIIIIII.llIIIIlllllIIllIIllI:17 IIIlIIlllIlIlIIIIIII.llllIIIllIlIIIIllllI:23 
,09-07 11:37:31.258  6234  6234 E Zygote  : v2
09-07 11:37:31.258  6234  6234 I libpersona: KNOX_SDCARD checking this for 10054
09-07 11:37:31.258  6234  6234 I libpersona: KNOX_SDCARD not a persona
,09-07 11:37:31.268  6234  6234 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0013
,09-07 11:37:31.268  1250  2674 I ActivityManager: Start proc 6234:com.samsung.aasaservice/u0a54 for service com.samsung.aasaservice/.AASAService
,09-07 11:37:31.268  6234  6234 E Zygote  : accessInfo : 0
09-07 11:37:31.268  6221  6221 I DBG_POLICYDM: [IIIlIIlllIlIlIIIIIII(26/llllIIIllIlIIIIllllI)] AASAUpdater Init Success
09-07 11:37:31.268  6234  6234 W SELinux : SELinux: seapp_context_lookup: seinfo=platform, level=s0:c512,c768, pkgname=com.samsung.aasaservice 
,09-07 11:37:31.278  6221  6221 I DBG_POLICYDM: [com.policydm.db.IIIIllIlIIlIIIIlllIl(442/IIIlIIllIlIIllIlllII)] xdbGetFUMOStatus : 0
,09-07 11:37:31.278  6221  6221 I DBG_POLICYDM: [com.policydm.XDMService(574/llIlIllllllllllllllI)] get NotibarState : 0
,09-07 11:37:31.288  6221  6221 I DBG_POLICYDM: [com.policydm.db.IIIIllIlIIlIIIIlllIl(574/IlIIIllllIIlIIIIIlII)] Initiated Type: 0
,09-07 11:37:31.298  6234  6234 D TimaKeyStoreProvider: TimaSignature is unavailable
09-07 11:37:31.298  6234  6234 D ActivityThread: Added TimaKeyStore provider
,09-07 11:37:31.298  6221  6221 I DBG_POLICYDM: [com.policydm.db.IIIIllIlIIlIIIIlllIl(442/IIIlIIllIlIIllIlllII)] xdbGetFUMOStatus : 0
,09-07 11:37:31.298  6221  6221 I DBG_POLICYDM: [com.policydm.XDMService(574/llIlIllllllllllllllI)] get NotibarState : 0
,09-07 11:37:31.308  1250  1310 V BroadcastQueue: [deferred] Process cur broadcast BroadcastRecord{c618f u-1 android.net.conn.CONNECTIVITY_CHANGE qIdx=3}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{bfd0e08 6221:com.policydm/1000}
,09-07 11:37:31.308  6221  6221 I DBG_POLICYDM: [com.sec.android.policyagent.RegistrationReceiver(51/onReceive)] RegistrationReceiver onReceive! action = android.net.conn.CONNECTIVITY_CHANGE
,09-07 11:37:31.318   595  6238 I art     : Starting a blocking GC HeapTrim
,09-07 11:37:31.318  6234  6234 W System  : ClassLoader referenced unknown path: /system/app/AASAservice/lib/arm64
,09-07 11:37:31.328  6247  6247 E Zygote  : v2
09-07 11:37:31.328  6247  6247 I libpersona: KNOX_SDCARD checking this for 10027
09-07 11:37:31.328  6247  6247 I libpersona: KNOX_SDCARD not a persona
09-07 11:37:31.328  1250  1720 I ActivityManager: Start proc 6247:com.osp.app.signin/u0a27 for broadcast-5 com.osp.app.signin/.OspReceiver
,09-07 11:37:31.328  6247  6247 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0013
09-07 11:37:31.328  1250  1720 I ActivityManager: Killing 5296:com.google.android.apps.photos/u0a97 (adj 15): DHA:empty #31
09-07 11:37:31.328  6247  6247 E Zygote  : accessInfo : 0
09-07 11:37:31.328  1250  1990 W ActivityManager: Permission Denial: getCurrentUser() from pid=6234, uid=10054 requires android.permission.INTERACT_ACROSS_USERS
09-07 11:37:31.328  6247  6247 W SELinux : SELinux: seapp_context_lookup: seinfo=default, level=s0:c512,c768, pkgname=com.osp.app.signin 
,09-07 11:37:31.328  6234  6234 D AASAservice: onCreate()
,09-07 11:37:31.338  6221  6221 I DBG_POLICYDM: [lIIIIllIIlIIIlIllIII(37/onServiceConnected)] AASA: onServiceConnected
09-07 11:37:31.338  1250  1721 I ActivityManager: Killing 5273:com.google.android.gm/u0a80 (adj 15): DHA:empty #31
,09-07 11:37:31.348  6247  6247 D TimaKeyStoreProvider: TimaSignature is unavailable
09-07 11:37:31.348  6247  6247 D ActivityThread: Added TimaKeyStore provider
,09-07 11:37:31.358  1250  1964 V BroadcastQueue: [deferred] Process cur broadcast BroadcastRecord{c618f u-1 android.net.conn.CONNECTIVITY_CHANGE qIdx=3}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{1e67a52 6247:com.osp.app.signin/u0a27}
,09-07 11:37:31.378  6247  6247 W System  : ClassLoader referenced unknown path: /system/priv-app/SamsungAccount_Hero/lib/arm64
,09-07 11:37:31.388  6247  6247 I SA      : [SSP] onCreated
,09-07 11:37:31.408  1250  1310 W ActivityManager: Unable to start service Intent { cmp=com.samsung.android.server.iris/.IrisService VirtualScreenParam=Params{mDisplayId=-1, null, mFlags=0x00000000)} } U=0: not found
,09-07 11:37:31.418  1250  2674 D ActivityManager: removeProcessNameLocked mProcessNames.remove pid=5296 ,hash=114514046 ,name=com.google.android.apps.photos
09-07 11:37:31.418  1250  2674 D ActivityManager: isAutoRunBlockedApp:: com.google.android.apps.photos, Auto Run ON
,09-07 11:37:31.458  1250  1310 D ActivityManager: removeProcessNameLocked mProcessNames.remove pid=5273 ,hash=1199612 ,name=com.google.android.gm
09-07 11:37:31.458  1250  1310 D ActivityManager: isAutoRunBlockedApp:: com.google.android.gm, Auto Run ON
,09-07 11:37:31.708  6247  6247 E SIrisManager: Wait for 300ms...
,09-07 11:37:32.008  6247  6247 E SIrisManager: Wait for 600ms...
,09-07 11:37:32.098   766  1446 I QC-NETMGR-LIB: Received nl msg, recvmsg returned 476
09-07 11:37:32.098   766  1446 I QC-NETMGR-LIB: Received command: ID=NETMGR_KIF_MSG_CMD, link=0
09-07 11:37:32.098   766  1442 I QC-NETMGR-LIB: Process command: ID=NETMGR_KIF_MSG_CMD, link=0, state=1
09-07 11:37:32.098   766  1442 I QC-NETMGR-LIB: Processing RTM_DELLINK
09-07 11:37:32.098   766  1442 I QC-NETMGR-LIB: Metainfo:  Index=13 Family=0 Type=0x1 Change=[0xffffffff]UP BROADCAST DEBUG LOOPBACK POINTOPOINT NOTRAILERS RUNNING NOARP PROMISC ALLMULTI MASTER SLAVE MULTICAST PORTSEL AUTOMEDIA DYNAMIC LOWER_UP DORMANT  Flags=[0x1002]BROADCAST MULTICAST 
09-07 11:37:32.098   766  1442 I QC-NETMGR-LIB: Rcvd Netlink msg type [17]
09-07 11:37:32.098   766  1442 I QC-NETMGR-LIB: Received RTM_DELLINK
09-07 11:37:32.098   766  1442 E QC-NETMGR-LIB: unrecognized ifindex 13, disable link
,09-07 11:37:32.098  1250  1384 E EthernetNetworkFactory: stopTrackingInterface : not matched eth0/usb0 iface is wlan0
,09-07 11:37:32.308  6247  6247 E SIrisManager: Wait for 900ms...
,09-07 11:37:32.318   766  1446 I QC-NETMGR-LIB: Received nl msg, recvmsg returned 476
09-07 11:37:32.318   766  1446 I QC-NETMGR-LIB: Received command: ID=NETMGR_KIF_MSG_CMD, link=0
09-07 11:37:32.318   766  1442 I QC-NETMGR-LIB: Process command: ID=NETMGR_KIF_MSG_CMD, link=0, state=1
09-07 11:37:32.318   766  1442 I QC-NETMGR-LIB: Processing RTM_DELLINK
09-07 11:37:32.318   766  1442 I QC-NETMGR-LIB: Metainfo:  Index=14 Family=0 Type=0x1 Change=[0xffffffff]UP BROADCAST DEBUG LOOPBACK POINTOPOINT NOTRAILERS RUNNING NOARP PROMISC ALLMULTI MASTER SLAVE MULTICAST PORTSEL AUTOMEDIA DYNAMIC LOWER_UP DORMANT  Flags=[0x1002]BROADCAST MULTICAST 
09-07 11:37:32.318   766  1442 I QC-NETMGR-LIB: Rcvd Netlink msg type [17]
09-07 11:37:32.318   766  1442 I QC-NETMGR-LIB: Received RTM_DELLINK
09-07 11:37:32.318   766  1442 E QC-NETMGR-LIB: unrecognized ifindex 14, disable link
,09-07 11:37:32.318  1250  1384 E EthernetNetworkFactory: stopTrackingInterface : not matched eth0/usb0 iface is p2p0
,09-07 11:37:32.318  6247  6247 I SA      : [TPM] There is no property file
,09-07 11:37:32.328  6247  6247 I SA      : [SCU] isHaveSA() - false
,09-07 11:37:32.338  6247  6247 I SA      : [TPM] getModelProperty : null
09-07 11:37:32.338  6247  6247 I SA      : [TPM] getCSCProperty : null
,09-07 11:37:32.338  6247  6247 I SA      : [DM] FLOATING AMOLED FEATURE: true
09-07 11:37:32.338  6247  6247 I SA      : [DM] PRODUCT AMOLED FEATURE: false
09-07 11:37:32.338  6247  6247 I SA      : [DM] TFT FEATURE: false
,09-07 11:37:32.338  6247  6247 I SA      : [SCU] isHaveSA() - false
,09-07 11:37:32.338  6247  6247 I SA      : [SCU] == networkStateCheck == false
09-07 11:37:32.338  6247  6247 I SA      : [SS] network off, couldn't connect to DIR
,09-07 11:37:32.338  6247  6247 I SA      : [DM] init START,
,09-07 11:37:32.348  6247  6247 D ContextRelationManager: ContextRelationManager() : FEATURE_ENABLED=true
,09-07 11:37:32.348  6247  6247 I SA      : [DM] This device is not a Vodafone
,09-07 11:37:32.358  6247  6247 W ResourceType: No package identifier when getting value for resource number 0x00000000
,09-07 11:37:32.358  6247  6247 W ResourceType: No package identifier when getting value for resource number 0x00000000
,09-07 11:37:32.358  6247  6247 W ResourceType: No package identifier when getting value for resource number 0x00000000
,09-07 11:37:32.358  6247  6247 W ResourceType: No package identifier when getting value for resource number 0x00000000
,09-07 11:37:32.358  6247  6247 W ResourceType: No package identifier when getting value for resource number 0x00000000
09-07 11:37:32.358  6247  6247 W ResourceType: No package identifier when getting value for resource number 0x00000000
,09-07 11:37:32.358  6247  6247 W ResourceType: No package identifier when getting value for resource number 0x00000000
,09-07 11:37:32.358  6247  6247 W ResourceType: No package identifier when getting value for resource number 0x00000000
09-07 11:37:32.358  6247  6247 W ResourceType: No package identifier when getting value for resource number 0x00000000
,09-07 11:37:32.358  6247  6247 W ResourceType: No package identifier when getting value for resource number 0x00000000
09-07 11:37:32.358  6247  6247 W ResourceType: No package identifier when getting value for resource number 0x00000000
,09-07 11:37:32.358  6247  6247 W ResourceType: No package identifier when getting value for resource number 0x00000000
,09-07 11:37:32.358  6247  6247 W ResourceType: No package identifier when getting value for resource number 0x00000000
,09-07 11:37:32.358  6247  6247 W ResourceType: No package identifier when getting value for resource number 0x00000000
09-07 11:37:32.358  6247  6247 W ResourceType: No package identifier when getting value for resource number 0x00000000
,09-07 11:37:32.358  6247  6247 W ResourceType: No package identifier when getting value for resource number 0x00000000
09-07 11:37:32.358  6247  6247 W ResourceType: No package identifier when getting value for resource number 0x00000000
,09-07 11:37:32.358  6247  6247 W ResourceType: No package identifier when getting value for resource number 0x00000000
,09-07 11:37:32.358  6247  6247 W ResourceType: No package identifier when getting value for resource number 0x00000000
,09-07 11:37:32.368  6247  6247 W ResourceType: No package identifier when getting value for resource number 0x00000000
09-07 11:37:32.368  6247  6247 W ResourceType: No package identifier when getting value for resource number 0x00000000
09-07 11:37:32.368  6247  6247 W ResourceType: No package identifier when getting value for resource number 0x00000000
,09-07 11:37:32.368  6247  6247 W ResourceType: No package identifier when getting value for resource number 0x00000000
09-07 11:37:32.368  6247  6247 W ResourceType: No package identifier when getting value for resource number 0x00000000
,09-07 11:37:32.368  6247  6247 W ResourceType: No package identifier when getting value for resource number 0x00000000
,09-07 11:37:32.368  6247  6247 W ResourceType: No package identifier when getting value for resource number 0x00000000
09-07 11:37:32.368  6247  6247 W ResourceType: No package identifier when getting value for resource number 0x00000000
,09-07 11:37:32.368  6247  6247 W ResourceType: No package identifier when getting value for resource number 0x00000000
,09-07 11:37:32.368  6247  6247 W ResourceType: No package identifier when getting value for resource number 0x00000000
,09-07 11:37:32.368  6247  6247 W ResourceType: No package identifier when getting value for resource number 0x00000000
,09-07 11:37:32.368  6247  6247 W ResourceType: No package identifier when getting value for resource number 0x00000000
09-07 11:37:32.368  6247  6247 W ResourceType: No package identifier when getting value for resource number 0x00000000
,09-07 11:37:32.368  6247  6247 W ResourceType: No package identifier when getting value for resource number 0x00000000
,09-07 11:37:32.368  6247  6247 W ResourceType: No package identifier when getting value for resource number 0x00000000
09-07 11:37:32.368  6247  6247 W ResourceType: No package identifier when getting value for resource number 0x00000000,
09-07 11:37:32.368  6247  6247 W ResourceType: No package identifier when getting value for resource number 0x00000000
,09-07 11:37:32.368  6247  6247 W ResourceType: No package identifier when getting value for resource number 0x00000000
09-07 11:37:32.368  6247  6247 W ResourceType: No package identifier when getting value for resource number 0x00000000
,09-07 11:37:32.368  6247  6247 W ResourceType: No package identifier when getting value for resource number 0x00000000
,09-07 11:37:32.368  6247  6247 W ResourceType: No package identifier when getting value for resource number 0x00000000
09-07 11:37:32.368  6247  6247 W ResourceType: No package identifier when getting value for resource number 0x00000000
,09-07 11:37:32.378  6247  6247 W ResourceType: No package identifier when getting value for resource number 0x00000000
09-07 11:37:32.378  6247  6247 W ResourceType: No package identifier when getting value for resource number 0x00000000
09-07 11:37:32.378  6247  6247 W ResourceType: No package identifier when getting value for resource number 0x00000000
,09-07 11:37:32.378  6247  6247 W ResourceType: No package identifier when getting value for resource number 0x00000000
09-07 11:37:32.378  6247  6247 W ResourceType: No package identifier when getting value for resource number 0x00000000
,09-07 11:37:32.378  6247  6247 I SA      : support phone number id : true
09-07 11:37:32.378  6247  6247 I SA      : [DM] Supports Ref Jpn : true
,09-07 11:37:32.378  6247  6247 I SA      : [DM] init END
,09-07 11:37:32.378  6247  6247 I SA      : [OR] onReceive log=[SA = 2.2.01-51 V = 23 HWD = 2048X1536 2.0 dpi = 320  SIZE = 4 LOCALE = pl_PL CSC = XEO MCC = 0 MNC 0 T = user DEVICE = gts28velte P = gts28veltexx I = MMB29M M = SM-T719 OKLEFT false DIS MMB29M.T719XXU1APF6 PSS = 8.00525302084415  ]
,09-07 11:37:32.378  6247  6247 I SA      : [OR] onReceive Intent=[ conn.CONNECTIVITY_CHANGE. networkInfo:[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true] networkType:1 inetCondition:0 extraInfo:? noConnectivity:true ]
09-07 11:37:32.388  6247  6247 I SA      : [OR] == ACTION_CONNECTIVITY_CHANGE ==
,09-07 11:37:32.388  6247  6247 I SA      : [SLFUCHKMGR] constructor called
,09-07 11:37:32.388  6247  6247 I SA      : [TPMU]  strSIMState 	:SIM_STATE_ABSENT
09-07 11:37:32.388  6247  6247 I SA      : [OR] == isSIMCardReady false ==
,09-07 11:37:32.388  6247  6247 I SA      : [SCU] == networkStateCheck == false
09-07 11:37:32.388  6247  6247 I SA      : [OR] onReceive END
,09-07 11:37:32.398  1250  1964 V BroadcastQueue: [deferred] Process cur broadcast BroadcastRecord{c618f u-1 android.net.conn.CONNECTIVITY_CHANGE qIdx=3}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{7cc8669 6173:com.sec.app.RilErrorNotifier/1000}
,09-07 11:37:32.398  6173  6173 I PhoneErrorReceiver: onReceive
,09-07 11:37:32.398  6173  6173 V PhoneErrorReceiver: beginStartingService
,09-07 11:37:32.398  6173  6173 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1311 android.content.ContextWrapper.startService:606 android.content.ContextWrapper.startService:606 com.sec.app.RilErrorNotifier.PhoneErrorReceiver.beginStartingService:194 com.sec.app.RilErrorNotifier.PhoneErrorReceiver.onReceiveWithPrivilege:171 
,09-07 11:37:32.408  6173  6173 V PhoneErrService: Creating SmsReceiverService
09-07 11:37:32.408  1250  2010 V BroadcastQueue: [deferred] Process cur broadcast BroadcastRecord{c618f u-1 android.net.conn.CONNECTIVITY_CHANGE qIdx=3}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{af855d3 4453:com.sec.spp.push/u0a26}
,09-07 11:37:32.408  6173  6173 V MIP_PhoneErrService: mTelephonyManager is not null
09-07 11:37:32.408  4453  4453 E SPPClientService: [SystemStateMoniter] Action Name : android.net.conn.CONNECTIVITY_CHANGE
09-07 11:37:32.408  4453  4453 E SPPClientService: [SystemStateMoniter] Current Time : 145826
09-07 11:37:32.408  4453  4453 E SPPClientService: [SystemStateMoniter] No Connect : true
,09-07 11:37:32.418  1250  1720 V BroadcastQueue: [deferred] Process cur broadcast BroadcastRecord{c618f u-1 android.net.conn.CONNECTIVITY_CHANGE qIdx=3}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{dfe46f9 2433:android.process.media/u0a33}
,09-07 11:37:32.418  2433  2433 V DownloadManager: onReceive intent + android.net.conn.CONNECTIVITY_CHANGE
,09-07 11:37:32.418  4453  6263 E SPPClientService: [[SystemStateMonitorService]] No Active Internet
,09-07 11:37:32.428  6173  6173 V PhoneErrService: Starting #1: Bundle[mParcelledData.dataSize=448]
09-07 11:37:32.428  6173  6173 I PhoneErrService: mResultCode: 0
,09-07 11:37:32.428  6173  6173 V MIP_PhoneErrService: onDataConnectionState : -1
,09-07 11:37:32.428  6173  6264 V PhoneErrService: Handling incoming message: { when=-1ms what=0 arg1=1 obj=Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.sec.app.RilErrorNotifier/.PhoneErrService bqHint=3 VirtualScreenParam=Params{mDisplayId=-1, null, mFlags=0x00000000)} (has extras) } target=com.sec.app.RilErrorNotifier.PhoneErrService$ServiceHandler }
,09-07 11:37:32.428  6173  6264 V PhoneErrorReceiver: finishStartingService
,09-07 11:37:32.428  6265  6265 E Zygote  : v2
09-07 11:37:32.428  6265  6265 I libpersona: KNOX_SDCARD checking this for 1000
09-07 11:37:32.428  6265  6265 I libpersona: KNOX_SDCARD not a persona
09-07 11:37:32.428  6265  6265 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0013
09-07 11:37:32.428  1250  2327 I ActivityManager: Start proc 6265:com.samsung.android.SettingsReceiver/1000 for broadcast-5 com.samsung.android.SettingsReceiver/.SettingsIntentReceiver
09-07 11:37:32.428  6265  6265 E Zygote  : accessInfo : 0
,09-07 11:37:32.438  6173  6173 V PhoneErrService: Destroying PhoneErrorReceiverService
,09-07 11:37:32.438  1250  1964 I ActivityManager: Killing 5157:com.samsung.storyservice/5004 (adj 15): DHA:empty #31
,09-07 11:37:32.458  6265  6265 D TimaKeyStoreProvider: TimaSignature is unavailable
09-07 11:37:32.458  6265  6265 D ActivityThread: Added TimaKeyStore provider
,09-07 11:37:32.458  1250  2327 V BroadcastQueue: [deferred] Process cur broadcast BroadcastRecord{c618f u-1 android.net.conn.CONNECTIVITY_CHANGE qIdx=3}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{ad6dbd9 6265:com.samsung.android.SettingsReceiver/1000}
,09-07 11:37:32.478  6265  6265 W System  : ClassLoader referenced unknown path: /system/priv-app/SettingsReceiver/lib/arm64
,09-07 11:37:32.498  6277  6277 E Zygote  : v2
09-07 11:37:32.498  6277  6277 I libpersona: KNOX_SDCARD checking this for 10022
09-07 11:37:32.498  6277  6277 I libpersona: KNOX_SDCARD not a persona
,09-07 11:37:32.498  6277  6277 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0013
,09-07 11:37:32.498  1250  1986 I ActivityManager: Start proc 6277:com.myscript.atk.rmc.service.sample/u0a22 for content provider com.myscript.atk.rmc.service.sample/com.myscript.atk.rmc.DataStorageProvider
09-07 11:37:32.498  1250  1621 D NetworkPolicy: isUidForegroundLocked: 10022, mScreenOn: false, uidstate: -1, mProxSensorScreenOff: false
,09-07 11:37:32.508  6277  6277 E Zygote  : accessInfo : 0
,09-07 11:37:32.508  6277  6277 W SELinux : SELinux: seapp_context_lookup: seinfo=filtered_untrusted, level=s0:c512,c768, pkgname=com.myscript.atk.rmc.service.sample 
,09-07 11:37:32.528  1250  1721 D ActivityManager: isAutoRunBlockedApp:: com.samsung.storyservice, Auto Run ON
09-07 11:37:32.528  1250  1721 D ActivityManager: removeProcessNameLocked mProcessNames.remove pid=5157 ,hash=267381881 ,name=com.samsung.storyservice
,09-07 11:37:32.528  6277  6277 D TimaKeyStoreProvider: TimaSignature is unavailable
09-07 11:37:32.528  6277  6277 D ActivityThread: Added TimaKeyStore provider
,09-07 11:37:32.528  1250  1621 D NetworkPolicy: isUidForegroundLocked: 10022, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
,09-07 11:37:32.548  6277  6277 W System  : ClassLoader referenced unknown path: /system/priv-app/ResourceManager/lib/arm64
,09-07 11:37:32.568  1250  1964 W ActivityManager: Permission Denial: getCurrentUser() from pid=6277, uid=10022 requires android.permission.INTERACT_ACROSS_USERS
,09-07 11:37:32.568  1250  1964 I ActivityManager: Killing 5574:com.android.providers.calendar/u0a32 (adj 15): DHA:empty #31
09-07 11:37:32.568  1250  1964 I ActivityManager: Killing 5556:com.android.calendar/u0a106 (adj 15): DHA:empty #31
,09-07 11:37:32.568  1250  1964 V BroadcastQueue: [deferred] Process cur broadcast BroadcastRecord{c618f u-1 android.net.conn.CONNECTIVITY_CHANGE qIdx=3}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{6c29e29 2494:com.microsoft.skydrive/u0a93}
,09-07 11:37:32.568  1250  1994 D ConnectivityService: returning getNetworkInfo for network type 0 : [type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
,09-07 11:37:32.578  1250  1990 W IntentResolver: resolveIntent failed: found match, but none with CATEGORY_DEFAULT
,09-07 11:37:32.578  1250  1990 D PackageManager: findPreferredActivity: No PreferredActivities set
09-07 11:37:32.578  1250  1990 I PackageManager: No preferred activity: intent should not be shown
,09-07 11:37:32.598  6290  6290 E Zygote  : v2
09-07 11:37:32.598  6290  6290 I libpersona: KNOX_SDCARD checking this for 10097
09-07 11:37:32.598  6290  6290 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0013
09-07 11:37:32.598  6290  6290 I libpersona: KNOX_SDCARD not a persona
09-07 11:37:32.598  1250  1994 I ActivityManager: Start proc 6290:com.google.android.apps.photos/u0a97 for broadcast-5 com.google.android.apps.photos/.actionqueue.SystemReceiver
,09-07 11:37:32.598  6290  6290 E Zygote  : accessInfo : 0
09-07 11:37:32.598  6290  6290 W SELinux : SELinux: seapp_context_lookup: seinfo=untrusted, level=s0:c512,c768, pkgname=com.google.android.apps.photos 
,09-07 11:37:32.618  6290  6290 D TimaKeyStoreProvider: TimaSignature is unavailable
09-07 11:37:32.618  6290  6290 D ActivityThread: Added TimaKeyStore provider
,09-07 11:37:32.628  1250  1990 V BroadcastQueue: [deferred] Process cur broadcast BroadcastRecord{c618f u-1 android.net.conn.CONNECTIVITY_CHANGE qIdx=3}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{78ecc7f 6290:com.google.android.apps.photos/u0a97}
,09-07 11:37:32.658  1250  1313 D ActivityManager: isAutoRunBlockedApp:: com.android.providers.calendar, Auto Run ON
,09-07 11:37:32.658  1250  1313 D ActivityManager: removeProcessNameLocked mProcessNames.remove pid=5574 ,hash=233577067 ,name=com.android.providers.calendar
,09-07 11:37:32.658  1250  1990 D ActivityManager: isAutoRunBlockedApp:: com.android.calendar, Auto Run ON
09-07 11:37:32.658  1250  1990 D ActivityManager: removeProcessNameLocked mProcessNames.remove pid=5556 ,hash=232277221 ,name=com.android.calendar
,09-07 11:37:32.698  6290  6290 W System  : ClassLoader referenced unknown path: /system/app/Photos/lib/arm
,09-07 11:37:32.958  6290  6290 D ContextRelationManager: ContextRelationManager() : FEATURE_ENABLED=true
,09-07 11:37:33.008  1250  2327 W ActivityManager: Permission Denial: getCurrentUser() from pid=6290, uid=10097 requires android.permission.INTERACT_ACROSS_USERS
,09-07 11:37:33.028  1250  1623 D WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:1
09-07 11:37:33.028  1250  1623 E WifiStateMachine: Error! unhandled message{ when=-2m26s448ms what=131156 target=com.android.internal.util.StateMachine$SmHandler }
,09-07 11:37:33.048  6290  6290 W Primes  : Memory instrumentations are turned off.
,09-07 11:37:33.058  6290  6290 W Primes  : Timer instrumentations are turned off.
,09-07 11:37:33.058  6290  6290 W Primes  : Crash monitoring is turned off.
,09-07 11:37:33.078  6290  6290 W Primes  : Network monitoring is turned off.
09-07 11:37:33.078  6290  6290 W Primes  : Package metrics are turned off by default
,09-07 11:37:33.108  1250  1378 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{7a6b913 u0 com.google.android.apps.photos.actionqueue.INTERNAL_ACTION qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{78ecc7f 6290:com.google.android.apps.photos/u0a97}
,09-07 11:37:33.118  1250  2327 V BroadcastQueue: [deferred] Process cur broadcast BroadcastRecord{c618f u-1 android.net.conn.CONNECTIVITY_CHANGE qIdx=3}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{78ecc7f 6290:com.google.android.apps.photos/u0a97}
,09-07 11:37:33.128  1250  1378 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{612c750 u0 com.google.android.apps.photos.jobqueue.EXECUTE_JOBS qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{78ecc7f 6290:com.google.android.apps.photos/u0a97}
09-07 11:37:33.138  1250  1721 V BroadcastQueue: [deferred] Process cur broadcast BroadcastRecord{c618f u-1 android.net.conn.CONNECTIVITY_CHANGE qIdx=3}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{82191cf 4782:com.sec.android.daemonapp/u0a127}
,09-07 11:37:33.138  4782  4782 D [WeatherWidget(1210)]  ConnectivityReceiver: {[8E9CEEBB4FA5730BE17E1F2CB9E366CFAAE09BFCA326403459399C53A4EE79DAC193CEB26509F8FF7498BE5251A746097407E81C28CD811D388C49D613C81F395B356AA489D29CB4C3BE983CCC84BA76AF507AA66A943348DF162DECA2A5A7DD]}
09-07 11:37:33.138  4782  4782 D [WeatherWidget(1210)]  ConnectivityReceiver: {[8E9CEEBB4FA5730BE17E1F2CB9E366CFE2E89F45594D9820F24D88E9AF210A78F9CD3967C07B6DE6AAB9923C4C53919020112019F4465EB3AA6FD266958B212E]}
,09-07 11:37:33.148  1250  1990 V BroadcastQueue: [deferred] Process cur broadcast BroadcastRecord{c618f u-1 android.net.conn.CONNECTIVITY_CHANGE qIdx=3}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{26de453 5382:com.sec.android.app.samsungapps/u0a9}
,09-07 11:37:33.168  1250  2010 I ActivityManager: Killing 4961:com.samsung.android.communicationservice/5002 (adj 15): DHA:empty #31
,09-07 11:37:33.248  1250  1313 D ActivityManager: isAutoRunBlockedApp:: com.samsung.android.communicationservice, Auto Run ON
09-07 11:37:33.248  1250  1313 D ActivityManager: removeProcessNameLocked mProcessNames.remove pid=4961 ,hash=189842723 ,name=com.samsung.android.communicationservice
09-07 11:37:33.248  1250  1313 W ActivityManager: Scheduling restart of crashed service com.samsung.android.communicationservice/.ITransactionManagerService in 1000ms
09-07 11:37:33.248  5001  5001 D Mms/MmsApp: CommunicationService Disconnected
,09-07 11:37:34.868  1250  3553 D SSRM:s  : SIOP:: AP = 300, PST = 333 (W:12), CP = 37, LCD = 0
,09-07 11:37:34.878  1250  3553 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
,09-07 11:37:35.338   707   707 I MSM-irqbalance: Decided to move IRQ216 from CPU3 to CPU1
,09-07 11:37:35.438  1250  1721 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
09-07 11:37:35.438  1250  1721 D BatteryService: level:100, scale:100, status:3, health:2, present:true, voltage: 4375, temperature: 290, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303407, invalid charger:0, maxChargingCurrent:0
09-07 11:37:35.438  1250  1721 D BatteryService: online:4, current avg:74, charge type:0, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:-3
09-07 11:37:35.438  1250  1250 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,09-07 11:37:35.448  1694  1694 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
09-07 11:37:35.448  1694  1694 D KeyguardUpdateMonitor: handleBatteryUpdate
,09-07 11:37:35.448  1694  1694 D PowerUI : priorPlugType = 2 mPlugType =  2
,09-07 11:37:35.458  2587  2587 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
09-07 11:37:35.458  2587  3110 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,09-07 11:37:35.468  1694  1694 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:3 health:2
,09-07 11:37:35.468  1694  1694 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:3 health:2
09-07 11:37:35.468  1694  1694 D CoverUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,09-07 11:37:36.308  5989  6040 V io.jxcore.node.ConnectivityMonitor: start: Already started
,09-07 11:37:36.308  5989  6040 I WifiManager: isAllowWifiWarning() -> isCscWifiEnableWarning : false ChinaNalSecurityType : 
,09-07 11:37:36.308  1250  2396 D SecContentProvider: query(), uri = 18 selection = isWifiEnabled
09-07 11:37:36.308  1250  2396 D SecContentProvider2: query(), uri = 20 selection = isWifiStateChangeAllowed
,09-07 11:37:36.318  1250  2396 D WifiService: System do NOT have com.sec.feature.sensorhub feature
09-07 11:37:36.318  1250  2396 D WifiService: Wi-Fi on and Screen on , checkSensorStatus !!
09-07 11:37:36.318  1250  2396 D WifiService: setWifiEnabled: true pid=5989, uid=10136
09-07 11:37:36.318  1250  2396 W ActivityManager: Permission Denial: getCurrentUser() from pid=5989, uid=10136 requires android.permission.INTERACT_ACROSS_USERS
,09-07 11:37:36.318  1250  2396 W WifiService: Failed getting userId using ActivityManagerNative
09-07 11:37:36.318  1250  2396 W WifiService: java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=5989, uid=10136 requires android.permission.INTERACT_ACROSS_USERS
09-07 11:37:36.318  1250  2396 W WifiService: 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:28130)
09-07 11:37:36.318  1250  2396 W WifiService: 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2542)
09-07 11:37:36.318  1250  2396 W WifiService: 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2530)
09-07 11:37:36.318  1250  2396 W WifiService: 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:257)
09-07 11:37:36.318  1250  2396 W WifiService: 	at android.os.Binder.execTransact(Binder.java:453)
09-07 11:37:36.318  1250  2396 D SettingsProvider: isChangeAllowed() : name = wifi_on
09-07 11:37:36.318  1250  1623 D WifiBigDataLog: getJsonFormat() - feature : ONOF
09-07 11:37:36.318  1250  1623 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:836 com.android.server.wifi.WifiStateMachine.insertLog:18843 com.android.server.wifi.WifiStateMachine.access$4300:293 com.android.server.wifi.WifiStateMachine$DefaultState.processMessage:8707 com.android.internal.util.StateMachine$SmHandler.processMsg:968 
09-07 11:37:36.318  1250  1623 D WifiBigDataLog: init : 
09-07 11:37:36.318  1250  1624 D WifiController: [FCC]setFccChannel() is called !!!
09-07 11:37:36.318  1250  1624 D WifiStateMachine: setFccChannel: channel = 0
09-07 11:37:36.318  1250  1624 D WifiController: [FCC]Airplane on, setFccChannel(0)!!!
09-07 11:37:36.318  1250  1624 D SecContentProvider: insert(), uri = 2
09-07 11:37:36.318  1250  2127 E OsAgent :  Wifi Scan Always Available: 0
09-07 11:37:36.318  1250  2127 E IzatSvc_OSObserver: I/LocTech-Label :: OSOBSERVER :: Data Items In
09-07 11:37:36.318  1250  2127 E IzatSvc_OSObserver: I/LocTech-Value :: Data Item Value: IS_WIFI_HARDWARE_ON: true
09-07 11:37:36.318  1250  2152 E LocSvc_libulp: I/int ulp_msg_process_phone_setting_update(const UlpPhoneContextSettings*), context type: 0x4
09-07 11:37:36.318  1250  2152 E LocSvc_libulp:   gps enabled: 0
09-07 11:37:36.318  1250  2152 E LocSvc_libulp:  network position available 0
09-07 11:37:36.318  1250  2152 E LocSvc_libulp:  wifi setting enabled 1
09-07 11:37:36.318  1250  2152 E LocSvc_libulp:  battery charging 0, agps enabled 0, enh_location_services_enabled 0is_pip_user_setting_enabled 0
09-07 11:37:36.318  1250  2152 E LocSvc_libulp: I/int ulp_msg_process_system_update(UlpSystemEvent): systemEvent:4 
09-07 11:37:36.328  1250  2127 E OsAgent :  Wifi Scan Always Available: 0
09-07 11:37:36.328  1250  2127 E IzatSvc_OSObserver: I/LocTech-Label :: OSOBSERVER :: Data Items In
09-07 11:37:36.328  1250  2127 E IzatSvc_OSObserver: I/LocTech-Value :: Data Item Value: IS_WIFI_HARDWARE_ON: true
09-07 11:37:36.328  1250  2127 E OsAgent :  Wifi Scan Always Available: 0
09-07 11:37:36.328  1250  2127 E IzatSvc_OSObserver: I/LocTech-Label :: OSOBSERVER :: Data Items In
09-07 11:37:36.328  1250  2127 E IzatSvc_OSObserver: I/LocTech-Value :: Data Item Value: IS_WIFI_HARDWARE_ON: true
,09-07 11:37:36.328  1250  1378 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{e15f64e u0 com.samsung.android.providers.context.log.action.USE_APP_FEATURE_SURVEY qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{573bf46 2626:com.samsung.android.providers.context/u0a5}
09-07 11:37:36.328  1250  2132 E LocSvc_LBSApiV02: E/virtual int lbs_core::LBSApiV02::wifiEnabledStatusInject(int):677]: Error : st = 2, ind.status = 1310827456
09-07 11:37:36.328  1250  1623 E WifiHW  : ##################### set firmware type 0 #####################
,09-07 11:37:37.438  1250  1384 E EthernetNetworkFactory: maybeTrackInterface : not matched eth0/usb0 iface is wlan0
09-07 11:37:37.438  1250  1416 D Tethering: enter TetherInterfaceSM  and send tetherstatechangebroadcast
,09-07 11:37:37.438  1250  1416 D Tethering: NAP Supported and not Wifi Model
,09-07 11:37:37.438   766  1446 I QC-NETMGR-LIB: Received nl msg, recvmsg returned 1088
09-07 11:37:37.438   766  1446 I QC-NETMGR-LIB: Received command: ID=NETMGR_KIF_MSG_CMD, link=0
09-07 11:37:37.438   554  1406 D Netd    : Iface wlan0 link down
09-07 11:37:37.438   766  1442 I QC-NETMGR-LIB: Process command: ID=NETMGR_KIF_MSG_CMD, link=0, state=1
09-07 11:37:37.438   766  1442 I QC-NETMGR-LIB: Processing RTM_NEWLINK
09-07 11:37:37.438   766  1442 I QC-NETMGR-LIB: Metainfo:  Index=15 Family=0 Type=0x1 Change=[0xffffffff]UP BROADCAST DEBUG LOOPBACK POINTOPOINT NOTRAILERS RUNNING NOARP PROMISC ALLMULTI MASTER SLAVE MULTICAST PORTSEL AUTOMEDIA DYNAMIC LOWER_UP DORMANT  Flags=[0x1002]BROADCAST MULTICAST 
09-07 11:37:37.438   766  1442 I QC-NETMGR-LIB: Rcvd Netlink msg type [16]
09-07 11:37:37.438   766  1442 I QC-NETMGR-LIB: Received RTM_NEWLINK
09-07 11:37:37.438   766  1442 E QC-NETMGR-LIB: unrecognized ifindex 15, disable link
,09-07 11:37:37.438  1250  1416 E Tethering: No numeric data
,09-07 11:37:37.438   766  1446 I QC-NETMGR-LIB: Received nl msg, recvmsg returned 1088
09-07 11:37:37.438   766  1446 I QC-NETMGR-LIB: Received command: ID=NETMGR_KIF_MSG_CMD, link=0
09-07 11:37:37.438   766  1442 I QC-NETMGR-LIB: Process command: ID=NETMGR_KIF_MSG_CMD, link=0, state=1
09-07 11:37:37.438   766  1442 I QC-NETMGR-LIB: Processing RTM_NEWLINK
09-07 11:37:37.438   554  1406 D Netd    : Iface p2p0 link down
09-07 11:37:37.438   766  1442 I QC-NETMGR-LIB: Metainfo:  Index=16 Family=0 Type=0x1 Change=[0xffffffff]UP BROADCAST DEBUG LOOPBACK POINTOPOINT NOTRAILERS RUNNING NOARP PROMISC ALLMULTI MASTER SLAVE MULTICAST PORTSEL AUTOMEDIA DYNAMIC LOWER_UP DORMANT  Flags=[0x1002]BROADCAST MULTICAST 
09-07 11:37:37.438   766  1442 I QC-NETMGR-LIB: Rcvd Netlink msg type [16]
09-07 11:37:37.438   766  1442 I QC-NETMGR-LIB: Received RTM_NEWLINK
09-07 11:37:37.438   766  1442 E QC-NETMGR-LIB: unrecognized ifindex 16, disable link
,09-07 11:37:37.448  1250  1384 E EthernetNetworkFactory: maybeTrackInterface : not matched eth0/usb0 iface is p2p0
09-07 11:37:37.448  1250  1416 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
,09-07 11:37:37.448  1250  1416 D Tethering: InitialState.processMessage what=4
,09-07 11:37:37.448  1250  1620 D NtpTrustedTime: currentTimeMillis() cache hit
09-07 11:37:37.448  1250  1620 V NetworkStats: performPollLocked(flags=0x1)
09-07 11:37:37.448  1694  1694 D HotspotTile: onReceive : android.net.conn.TETHER_STATE_CHANGED
09-07 11:37:37.448  1694  1694 D HotspotTile: updateTetherState():false, false
09-07 11:37:37.448  1250  1416 D Tethering: NAP Supported and not Wifi Model
09-07 11:37:37.448  1250  1620 D NetworkStatsRecorder: entry.iface is null
09-07 11:37:37.448  1250  1620 D NetworkStatsRecorder: entry.iface is null
09-07 11:37:37.448  1250  1620 D NetworkStatsRecorder: entry.iface is null
09-07 11:37:37.448  1250  1620 D NetworkStatsRecorder: entry.iface is null
09-07 11:37:37.448  1250  1378 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{c1c7c81 u-1 android.net.conn.TETHER_STATE_CHANGED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{667d8b1 1250:system/1000}
,09-07 11:37:37.448  1250  1620 V NetworkStats: performPollLocked() took 5ms
09-07 11:37:37.448  1250  1620 D NtpTrustedTime: currentTimeMillis() cache hit
,09-07 11:37:37.458   554  1414 I WifiHW  : wifi_change_fw_path(): fwpath = sta
,09-07 11:37:37.458   554  1414 D SoftapController: Softap fwReload - Ok
09-07 11:37:37.458  1250  1621 D NtpTrustedTime: currentTimeMillis() cache hit
09-07 11:37:37.458  1250  1621 D NtpTrustedTime: currentTimeMillis() cache hit
,09-07 11:37:37.458  1250  1416 E Tethering: No numeric data
,09-07 11:37:37.458  1250  1416 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
,09-07 11:37:37.458   554  1414 D CommandListener: Setting iface cfg
09-07 11:37:37.458   554  1414 D CommandListener: Trying to bring down wlan0
,09-07 11:37:37.458   554  1414 D CommandListener: Clearing all IP addresses on wlan0
09-07 11:37:37.458  1694  1694 D HotspotTile: onReceive : android.net.conn.TETHER_STATE_CHANGED
,09-07 11:37:37.458  1694  1694 D HotspotTile: updateTetherState():false, false
09-07 11:37:37.458  1250  1620 D NtpTrustedTime: currentTimeMillis() cache hit
09-07 11:37:37.458  1250  1620 V NetworkStats: performPollLocked(flags=0x1)
,09-07 11:37:37.458  1250  1623 E WifiMonitor: killSupplicant p2ptrue init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
,09-07 11:37:37.458  1250  1623 D wifi    : Can not initialize the vendor function pointer table
,09-07 11:37:37.468  1250  1623 E WifiNative-HAL: Could not start hal
,09-07 11:37:37.468  1250  1620 D NetworkStatsRecorder: entry.iface is null
09-07 11:37:37.468  1250  1623 E WifiStateMachine: Failed to start HAL
09-07 11:37:37.468  1250  1620 D NetworkStatsRecorder: entry.iface is null
,09-07 11:37:37.468  1250  1623 E WifiHW  : supplicant_name : p2p_supplicant
09-07 11:37:37.468  1250  1620 D NetworkStatsRecorder: entry.iface is null
09-07 11:37:37.468  1250  1620 D NtpTrustedTime: currentTimeMillis() cache hit
09-07 11:37:37.468  1250  1620 D NetworkStatsRecorder: entry.iface is null
09-07 11:37:37.468  1250  1621 D NtpTrustedTime: currentTimeMillis() cache hit
09-07 11:37:37.468  1250  1620 V NetworkStats: performPollLocked() took 5ms
09-07 11:37:37.468  1250  1621 D NtpTrustedTime: currentTimeMillis() cache hit
09-07 11:37:37.468  1250  1378 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{2d68126 u-1 android.net.conn.TETHER_STATE_CHANGED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{667d8b1 1250:system/1000}
,09-07 11:37:37.518  6329  6329 I wpa_supplicant: [wpa_supplicant_init]: use SECRIL
09-07 11:37:37.518  6329  6329 I wpa_supplicant: Successfully initialized wpa_supplicant
09-07 11:37:37.518  6329  6329 I wpa_supplicant: set_csc_config : ifname(wlan0), certi_flags(0x0), autoconnect_flags(0x0), opbranding_flags(0x0), boolean_flags(0x20000), vendorssid_list()
,09-07 11:37:37.528  6329  6329 I SecureStorage: [INFO]: SPID(0x00000000)Checking if this device supports Secure Storage
,09-07 11:37:37.548  6329  6329 I SecureStorage: [INFO]: SPID(0x00000000)This device supports Secure Storage
,09-07 11:37:37.548   458   458 I SecureStorage: [INFO]: SPID(0x00000004)Credentials: uid 1010, gid 1010, pid 6329
09-07 11:37:37.548   458   458 I SecureStorage: [INFO]: SPID(0x00000004)Received function mask & code: 0x0000010C
,09-07 11:37:37.548  6329  6329 I SecureStorage: [INFO]: SPID(0x00000000)SS Daemon is running
09-07 11:37:37.548  6329  6329 I wpa_supplicant: ssSupport state is = 1
09-07 11:37:37.548  6329  6329 I wpa_supplicant: >>>>> GET KEY, IV <<<<<
09-07 11:37:37.548  6329  6329 I SecureStorage: [INFO]: SPID(0x00000000)Processing data
,09-07 11:37:37.548   458   458 I SecureStorage: [INFO]: SPID(0x00000004)Credentials: uid 1010, gid 1010, pid 6329
09-07 11:37:37.548   458   458 I SecureStorage: [INFO]: SPID(0x00000004)Received function mask & code: 0x00000106
,09-07 11:37:37.568  1250  1623 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
09-07 11:37:37.568  6329  6329 I SecureStorage: [INFO]: SPID(0x00000005)ss_id will be loaded by secure_storage_daemon: /system/bin/wpa_supplicant
,09-07 11:37:37.568  1250  1250 D HS20StateMachine: Broadcast Received: android.net.wifi.WIFI_STATE_CHANGED
09-07 11:37:37.568  1250  1250 I WifiHs20Service: Broadcast received:android.net.wifi.WIFI_STATE_CHANGED
09-07 11:37:37.568  1250  1628 I WifiHs20Service: Message received 5011
,09-07 11:37:37.568  1694  1694 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
09-07 11:37:37.568  1694  2100 D NetworkController: onReceive: intent=Intent { act=android.net.wifi.WIFI_STATE_CHANGED flg=0x4000010 bqHint=4 VirtualScreenParam=Params{mDisplayId=-1, null, mFlags=0x00000000)} (has extras) }
,09-07 11:37:37.568  1694  1694 D HotspotTile: onReceive : 2, 0
09-07 11:37:37.568  1250  1631 D ConnectivityManager: getMobileDataEnabled()+ subId=2147483643
,09-07 11:37:37.578  1944  2295 D PhoneInterfaceManager: [PhoneIntfMgr] getDataEnabled: subId=2147483643 phoneId=0
,09-07 11:37:37.578  1944  2295 D PhoneInterfaceManager: [PhoneIntfMgr] getDataEnabled: subId=2147483643 retVal=true
09-07 11:37:37.578  1250  1631 D ConnectivityManager: getMobileDataEnabled()- subId=2147483643 retVal=true
09-07 11:37:37.578  5989  5989 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-07 11:37:37.578  1250  1378 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{a12c167 u-1 android.net.wifi.WIFI_STATE_CHANGED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{9925d68 5989:com.test.thalitest/u0a136}
,09-07 11:37:37.578  5989  5989 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-07 11:37:37.578  1250  1313 D ConnectivityService: returning getNetworkInfo for network type 0 : [type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
09-07 11:37:37.578  1250  1313 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
09-07 11:37:37.578  1250  1313 D ConnectivityService: returning getNetworkInfo for network type 2 : [type: MOBILE_MMS[] - MOBILE_MMS, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
09-07 11:37:37.578  1250  1313 D ConnectivityService: returning getNetworkInfo for network type 3 : [type: MOBILE_SUPL[] - MOBILE_SUPL, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
09-07 11:37:37.578  1250  1313 D ConnectivityService: returning getNetworkInfo for network type 4 : [type: MOBILE_DUN[] - MOBILE_DUN, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
09-07 11:37:37.578  1250  1313 D ConnectivityService: returning getNetworkInfo for network type 5 : [type: MOBILE_HIPRI[] - MOBILE_HIPRI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
09-07 11:37:37.578  1250  1313 D ConnectivityService: returning getNetworkInfo for network type 7 : [type: BLUETOOTH[] - BLUETOOTH, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
09-07 11:37:37.578  1250  1313 D ConnectivityService: returning getNetworkInfo for network type 9 : [type: ETHERNET[] - ETHERNET, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
09-07 11:37:37.578  1250  1313 D ConnectivityService: returning getNetworkInfo for network type 10 : [type: MOBILE_FOTA[] - MOBILE_FOTA, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
09-07 11:37:37.578  1250  1313 D ConnectivityService: returning getNetworkInfo for network type 11 : [type: MOBILE_IMS[] - MOBILE_IMS, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
09-07 11:37:37.578  1250  1313 D ConnectivityService: returning getNetworkInfo for network type 12 : [type: MOBILE_CBS[] - MOBILE_CBS, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
09-07 11:37:37.578  1250  1313 D ConnectivityService: returning getNetworkInfo for network type 13 : [type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: false]
09-07 11:37:37.578  1250  1313 D ConnectivityService: returning getNetworkInfo for network type 14 : [type: MOBILE_IA[] - MOBILE_IA, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
09-07 11:37:37.578  1250  1313 D ConnectivityService: returning getNetworkInfo for network type 15 : [type: MOBILE_EMERGENCY[] - MOBILE_EMERGENCY, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
09-07 11:37:37.578  1250  1313 D ConnectivityService: returning getNetworkInfo for network type 17 : [type: VPN[] - VPN, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
,09-07 11:37:37.578  1250  2396 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{a12c167 u-1 android.net.wifi.WIFI_STATE_CHANGED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{6f787ab 6209:com.samsung.android.securitylogagent/1000}
,09-07 11:37:37.768   458   458 I SecureStorage: [INFO]: SPID(0x00000005)Secure Storage Daemon finished processing with result: 0
09-07 11:37:37.768  6329  6329 I SecureStorage: [INFO]: SPID(0x00000005)Processing data has been completed
,09-07 11:37:37.808  6329  6329 I wpa_supplicant: Loading default cred
09-07 11:37:37.808  6329  6329 I SecureStorage: [INFO]: SPID(0x00000005)Checking if this device supports Secure Storage
,09-07 11:37:37.828  6329  6329 I SecureStorage: [INFO]: SPID(0x00000005)This device supports Secure Storage
,09-07 11:37:37.828   458   458 I SecureStorage: [INFO]: SPID(0x00000005)Credentials: uid 1010, gid 1010, pid 6329
09-07 11:37:37.828   458   458 I SecureStorage: [INFO]: SPID(0x00000005)Received function mask & code: 0x0000010C
09-07 11:37:37.828  6329  6329 I SecureStorage: [INFO]: SPID(0x00000005)SS Daemon is running
09-07 11:37:37.828  6329  6329 I wpa_supplicant: ssSupport state is = 1
09-07 11:37:37.828  6329  6329 W wpa_supplicant: Loading system cred
09-07 11:37:37.828  6329  6329 I SecureStorage: [INFO]: SPID(0x00000005)Checking if this device supports Secure Storage
,09-07 11:37:37.858  6329  6329 I SecureStorage: [INFO]: SPID(0x00000005)This device supports Secure Storage
,09-07 11:37:37.858   458   458 I SecureStorage: [INFO]: SPID(0x00000005)Credentials: uid 1010, gid 1010, pid 6329
09-07 11:37:37.858   458   458 I SecureStorage: [INFO]: SPID(0x00000005)Received function mask & code: 0x0000010C
,09-07 11:37:37.858  6329  6329 I SecureStorage: [INFO]: SPID(0x00000005)SS Daemon is running
09-07 11:37:37.858  6329  6329 I wpa_supplicant: ssSupport state is = 1
09-07 11:37:37.858  6329  6329 I wpa_supplicant: Blacklist: Clear (all) 
,09-07 11:37:37.858  6329  6329 E wpa_supplicant: getSavedIMSI cannot open /data/misc/radio/kmem: No such file or directory
09-07 11:37:37.858  6329  6329 I wpa_supplicant: [getIMSI]: sim_num 0
,09-07 11:37:37.868  6329  6329 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,09-07 11:37:37.868   766  1446 I QC-NETMGR-LIB: Received nl msg, recvmsg returned 1084
09-07 11:37:37.868   766  1446 I QC-NETMGR-LIB: Received command: ID=NETMGR_KIF_MSG_CMD, link=0
09-07 11:37:37.868   766  1442 I QC-NETMGR-LIB: Process command: ID=NETMGR_KIF_MSG_CMD, link=0, state=1
09-07 11:37:37.868   766  1442 I QC-NETMGR-LIB: Processing RTM_NEWLINK
09-07 11:37:37.868   766  1442 I QC-NETMGR-LIB: Metainfo:  Index=15 Family=0 Type=0x1 Change=[0x1]UP  Flags=[0x1003]UP BROADCAST MULTICAST 
09-07 11:37:37.868   766  1442 I QC-NETMGR-LIB: Rcvd Netlink msg type [16]
09-07 11:37:37.868   766  1442 I QC-NETMGR-LIB: Received RTM_NEWLINK
09-07 11:37:37.868   766  1442 E QC-NETMGR-LIB: unrecognized ifindex 15, disable link
09-07 11:37:37.868   554  1406 D Netd    : Iface wlan0 link down
,09-07 11:37:38.168  6329  6329 I wpa_supplicant: set_csc_config : ifname(p2p0), certi_flags(0x0), autoconnect_flags(0x0), opbranding_flags(0x0), boolean_flags(0x0), vendorssid_list()
,09-07 11:37:38.168  6329  6329 I SecureStorage: [INFO]: SPID(0x00000005)Checking if this device supports Secure Storage
,09-07 11:37:38.198  6329  6329 I SecureStorage: [INFO]: SPID(0x00000005)This device supports Secure Storage
,09-07 11:37:38.208   458   458 I SecureStorage: [INFO]: SPID(0x00000005)Credentials: uid 1010, gid 1010, pid 6329
09-07 11:37:38.208   458   458 I SecureStorage: [INFO]: SPID(0x00000005)Received function mask & code: 0x0000010C
,09-07 11:37:38.208  6329  6329 I SecureStorage: [INFO]: SPID(0x00000005)SS Daemon is running
09-07 11:37:38.208  6329  6329 I wpa_supplicant: ssSupport state is = 1
09-07 11:37:38.208  6329  6329 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,09-07 11:37:38.208   766  1446 I QC-NETMGR-LIB: Received nl msg, recvmsg returned 1084
09-07 11:37:38.208   766  1446 I QC-NETMGR-LIB: Received command: ID=NETMGR_KIF_MSG_CMD, link=0
09-07 11:37:38.208   766  1442 I QC-NETMGR-LIB: Process command: ID=NETMGR_KIF_MSG_CMD, link=0, state=1
09-07 11:37:38.208   766  1442 I QC-NETMGR-LIB: Processing RTM_NEWLINK
09-07 11:37:38.208   766  1442 I QC-NETMGR-LIB: Metainfo:  Index=16 Family=0 Type=0x1 Change=[0x1]UP  Flags=[0x1043]UP BROADCAST RUNNING MULTICAST 
,09-07 11:37:38.208   766  1442 I QC-NETMGR-LIB: Rcvd Netlink msg type [16]
09-07 11:37:38.208   766  1442 I QC-NETMGR-LIB: Received RTM_NEWLINK
09-07 11:37:38.208   766  1442 E QC-NETMGR-LIB: unrecognized ifindex 16, disable link
09-07 11:37:38.208   554  1406 D Netd    : Iface p2p0 link down
,09-07 11:37:38.208   766  1446 I QC-NETMGR-LIB: Received nl msg, recvmsg returned 1084
09-07 11:37:38.208   766  1446 I QC-NETMGR-LIB: Received command: ID=NETMGR_KIF_MSG_CMD, link=0
09-07 11:37:38.208   766  1442 I QC-NETMGR-LIB: Process command: ID=NETMGR_KIF_MSG_CMD, link=0, state=1
09-07 11:37:38.208   766  1442 I QC-NETMGR-LIB: Processing RTM_NEWLINK
09-07 11:37:38.208   554  1406 D Netd    : Iface p2p0 link down
09-07 11:37:38.208   766  1442 I QC-NETMGR-LIB: Metainfo:  Index=16 Family=0 Type=0x1 Change=[0x0] Flags=[0x1003]UP BROADCAST MULTICAST 
09-07 11:37:38.208   766  1442 I QC-NETMGR-LIB: Rcvd Netlink msg type [16]
09-07 11:37:38.208   766  1442 I QC-NETMGR-LIB: Received RTM_NEWLINK
09-07 11:37:38.208   766  1442 E QC-NETMGR-LIB: unrecognized ifindex 16, disable link
,09-07 11:37:38.418  6329  6329 I wpa_supplicant: P2P: Set prekey state (NONE -> NONE)
,09-07 11:37:38.428  1250  1623 D WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:2
,09-07 11:37:38.428  1250  1623 E WifiStateMachine: Deffering msg in Supplicant Starting State131085
,09-07 11:37:38.428  1250  1623 D WifiNative-wlan0: callSECApiBoolean - ID [301]
09-07 11:37:38.428  6329  6329 I wpa_supplicant: HOTSPOT20_ENABLE called ON
09-07 11:37:38.428  6329  6329 I wpa_supplicant: Blacklist: Clear (all) 
,09-07 11:37:38.438   554  1406 D Netd    : Iface p2p0 link down
09-07 11:37:38.438   766  1446 I QC-NETMGR-LIB: Received nl msg, recvmsg returned 1084
09-07 11:37:38.438   766  1446 I QC-NETMGR-LIB: Received command: ID=NETMGR_KIF_MSG_CMD, link=0
09-07 11:37:38.438   766  1442 I QC-NETMGR-LIB: Process command: ID=NETMGR_KIF_MSG_CMD, link=0, state=1
09-07 11:37:38.438   766  1442 I QC-NETMGR-LIB: Processing RTM_NEWLINK
09-07 11:37:38.438   766  1442 I QC-NETMGR-LIB: Metainfo:  Index=16 Family=0 Type=0x1 Change=[0x0] Flags=[0x1003]UP BROADCAST MULTICAST 
09-07 11:37:38.438   766  1442 I QC-NETMGR-LIB: Rcvd Netlink msg type [16]
09-07 11:37:38.438   766  1442 I QC-NETMGR-LIB: Received RTM_NEWLINK
09-07 11:37:38.438   766  1442 E QC-NETMGR-LIB: unrecognized ifindex 16, disable link
,09-07 11:37:38.448  6329  6329 I wpa_supplicant: wlan0: Setting scan request: 0 sec 0 usec
,09-07 11:37:38.448  6329  6329 I wpa_supplicant: wlan0: Skip scan - bUseNetwork false
,09-07 11:37:38.458  1250  1623 D WifiNative-wlan0: callSECApiInt - ID [210]
09-07 11:37:38.458  1250  1250 D HS20StateMachine: Broadcast Received: android.net.wifi.WIFI_STATE_CHANGED
09-07 11:37:38.458  1250  1625 D HS20StateMachine: WIFI_STATE_ENABLED
09-07 11:37:38.458  1250  1625 D HS20StateMachine: reloadCredentialsToSupplicant
09-07 11:37:38.458  1250  1625 D HotspotDBHandler: getCredentialIds
09-07 11:37:38.458  1250  1250 I WifiHs20Service: Broadcast received:android.net.wifi.WIFI_STATE_CHANGED
09-07 11:37:38.458  1250  1628 I WifiHs20Service: Message received 5011
,09-07 11:37:38.458  1250  1631 D ConnectivityManager: getMobileDataEnabled()+ subId=2147483643
09-07 11:37:38.458  1694  2100 D NetworkController: onReceive: intent=Intent { act=android.net.wifi.WIFI_STATE_CHANGED flg=0x4000010 bqHint=4 VirtualScreenParam=Params{mDisplayId=-1, null, mFlags=0x00000000)} (has extras) }
,09-07 11:37:38.458  1694  1694 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
09-07 11:37:38.458  1944  2744 D PhoneInterfaceManager: [PhoneIntfMgr] getDataEnabled: subId=2147483643 phoneId=0
,09-07 11:37:38.458  1694  1694 D HotspotTile: onReceive : 3, 0
09-07 11:37:38.458  1944  2744 D PhoneInterfaceManager: [PhoneIntfMgr] getDataEnabled: subId=2147483643 retVal=true
09-07 11:37:38.458  1250  1631 D ConnectivityManager: getMobileDataEnabled()- subId=2147483643 retVal=true
09-07 11:37:38.458  1694  2126 D QSTile.WifiTile: handleUpdateState  cb.changed 5 wifiEnabled : ON 
,09-07 11:37:38.458  1250  1623 D WifiConfigStore: Loading config and enabling all networks 
,09-07 11:37:38.458  1694  1694 D QSTileView: handleLabelStateChanged() label = Wi-Fi cellWidth 148
,09-07 11:37:38.468  1250  1378 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{d93eb14 u-1 android.net.wifi.WIFI_STATE_CHANGED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{9925d68 5989:com.test.thalitest/u0a136}
,09-07 11:37:38.468  5989  5989 D BluetoothAdapter: STATE_ON
,09-07 11:37:38.468  5989  5989 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-07 11:37:38.468  5989  5989 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-07 11:37:38.468  5989  5989 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-07 11:37:38.468  5989  5989 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-07 11:37:38.468  5989  5989 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-07 11:37:38.468  5989  5989 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-07 11:37:38.468  5989  5989 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-07 11:37:38.468  5989  5989 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-07 11:37:38.468  5989  5989 D BluetoothAdapter: STATE_ON
,09-07 11:37:38.468  5989  5989 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-07 11:37:38.478  5989  5989 D BluetoothAdapter: STATE_ON
,09-07 11:37:38.478  1250  1623 I WifiConfigStore: "NG700" is a verified password AP: true
09-07 11:37:38.478  1250  1623 E WifiConfigStore: Not a HS20
,09-07 11:37:38.478  5989  5989 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-07 11:37:38.478  5989  5989 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-07 11:37:38.478  5989  5989 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-07 11:37:38.478  5989  5989 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-07 11:37:38.478  5989  5989 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-07 11:37:38.478  5989  5989 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-07 11:37:38.478  5989  5989 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-07 11:37:38.478  5989  5989 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-07 11:37:38.478  1250  1623 D WifiConfigStore: loaded 0 passpoint configs
09-07 11:37:38.478  1250  1623 E WifiConfigStore: Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
,09-07 11:37:38.478  1250  1623 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000
,09-07 11:37:38.478  1250  1623 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 1
09-07 11:37:38.478  5989  5989 D BluetoothAdapter: STATE_ON
,09-07 11:37:38.478  1250  1625 I ActivityManager: Start proc 6337:com.samsung.hs20provider/u0a85 for content provider com.samsung.hs20provider/.Hs20Provider
09-07 11:37:38.478  6337  6337 E Zygote  : v2
09-07 11:37:38.478  6337  6337 I libpersona: KNOX_SDCARD checking this for 10085
09-07 11:37:38.478  6337  6337 I libpersona: KNOX_SDCARD not a persona
09-07 11:37:38.478  1250  1623 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK
,09-07 11:37:38.478  6337  6337 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0013
,09-07 11:37:38.478  1250  1623 D WifiConfigStore: setNetworkPriorityDefault: networkId = 0, priority = 1
09-07 11:37:38.478  1250  1250 I WifiHs20Service: Broadcast received:android.net.wifi.CONFIGURED_NETWORKS_CHANGE
09-07 11:37:38.478  1250  1250 D WifiHs20Service: reason: 2
09-07 11:37:38.488  1250  1628 I WifiHs20Service: Message received 5014
09-07 11:37:38.488  1250  1628 E WifiHs20Service: received HS20_UTILITY_ACTION_TYPE_HS20_CONFIGURATION_CHANGED
09-07 11:37:38.488  1250  1628 E WifiHs20Service: The changed config is NULL
,09-07 11:37:38.488  6337  6337 E Zygote  : accessInfo : 0
09-07 11:37:38.488  1250  1623 D WifiNative-wlan0: callSECApiInt - ID [65]
09-07 11:37:38.488  6337  6337 W SELinux : SELinux: seapp_context_lookup: seinfo=release, level=s0:c512,c768, pkgname=com.samsung.hs20provider 
,09-07 11:37:38.488  5989  5989 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-07 11:37:38.488  1250  1721 D ConnectivityService: returning getNetworkInfo for network type 0 : [type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
09-07 11:37:38.488  1250  1721 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
09-07 11:37:38.488  1250  1721 D ConnectivityService: returning getNetworkInfo for network type 2 : [type: MOBILE_MMS[] - MOBILE_MMS, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
09-07 11:37:38.488  1250  1721 D ConnectivityService: returning getNetworkInfo for network type 3 : [type: MOBILE_SUPL[] - MOBILE_SUPL, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
09-07 11:37:38.488  1250  1721 D ConnectivityService: returning getNetworkInfo for network type 4 : [type: MOBILE_DUN[] - MOBILE_DUN, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
09-07 11:37:38.488  1250  1721 D ConnectivityService: returning getNetworkInfo for network type 5 : [type: MOBILE_HIPRI[] - MOBILE_HIPRI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
09-07 11:37:38.488  1250  1721 D ConnectivityService: returning getNetworkInfo for network type 7 : [type: BLUETOOTH[] - BLUETOOTH, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
09-07 11:37:38.488  1250  1721 D ConnectivityService: returning getNetworkInfo for network type 9 : [type: ETHERNET[] - ETHERNET, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
09-07 11:37:38.488  1250  1721 D ConnectivityService: returning getNetworkInfo for network type 10 : [type: MOBILE_FOTA[] - MOBILE_FOTA, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
09-07 11:37:38.488  1250  1721 D ConnectivityService: returning getNetworkInfo for network type 11 : [type: MOBILE_IMS[] - MOBILE_IMS, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
09-07 11:37:38.488  1250  1721 D ConnectivityService: returning getNetworkInfo for network type 12 : [type: MOBILE_CBS[] - MOBILE_CBS, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
09-07 11:37:38.488  1250  1721 D ConnectivityService: returning getNetworkInfo for network type 13 : [type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: false]
09-07 11:37:38.488  1250  1721 D ConnectivityService: returning getNetworkInfo for network type 14 : [type: MOBILE_IA[] - MOBILE_IA, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
09-07 11:37:38.488  1250  1721 D ConnectivityService: returning getNetworkInfo for network type 15 : [type: MOBILE_EMERGENCY[] - MOBILE_EMERGENCY, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
09-07 11:37:38.488  1250  1721 D ConnectivityService: returning getNetworkInfo for network type 17 : [type: VPN[] - VPN, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
,09-07 11:37:38.488  1250  1623 D WifiNative-wlan0: callSECApiBoolean - ID [13]
09-07 11:37:38.488  6329  6329 I wpa_supplicant: USE_NETWORK : USE_NETWORK ON
,09-07 11:37:38.488  6329  6329 I wpa_supplicant: resume autoscan
09-07 11:37:38.488  6329  6329 I wpa_supplicant: autoscan_samsung_exponential_notify_scan : scan_interval = 8
09-07 11:37:38.488  6329  6329 I wpa_supplicant: autoscan: autoscan_notify_scan, scan_interval = 8
09-07 11:37:38.488  6329  6329 I wpa_supplicant: wlan0: Setting scan request: 8 sec 0 usec
09-07 11:37:38.488  6329  6329 I wpa_supplicant: reset timer : RESET_TIMER 0
09-07 11:37:38.488  6329  6329 I wpa_supplicant: P2P: Current p2p state = IDLE
,09-07 11:37:38.488  6329  6329 I wpa_supplicant: First Scan Start
09-07 11:37:38.488  6329  6329 I wpa_supplicant: Scan requested (ret=0) - scan timeout 30 seconds
09-07 11:37:38.488  1250  2333 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{d93eb14 u-1 android.net.wifi.WIFI_STATE_CHANGED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{6f787ab 6209:com.samsung.android.securitylogagent/1000}
,09-07 11:37:38.498  1250  1623 D WifiNative-wlan0: Setting external_sim to 1
,09-07 11:37:38.498  1250  1623 D WifiStateMachine: [setCountryCode()] Airplane mode return !!!
09-07 11:37:38.498  1250  1623 D WifiStateMachine: Setting OUI to DA-A1-19
,09-07 11:37:38.498  6329  6329 I wpa_supplicant: bt_status is set be DISCONNECTED
,09-07 11:37:38.498  1250  1623 E WifiNative-wlan0: do suspend true
09-07 11:37:38.498  1250  1622 D WifiP2pService: P2pDisabledState{ what=131203 }
,09-07 11:37:38.498  1250  1623 D WifiNative-HAL: Failing getSupportedFeatureset because HAL isn't started
09-07 11:37:38.498  1250  1623 D WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:3
09-07 11:37:38.498  1250  1623 D WifiStateMachine: [FCC]Airplane on, setFccChannel(0)!!!
09-07 11:37:38.498  1250  1623 D WifiStateMachine: setFccChannelNative: channel = 0
09-07 11:37:38.498  1250  1623 D WifiNative-wlan0: callSECApiInt - ID [230]
09-07 11:37:38.498  1250  1250 D RttService: SCAN_AVAILABLE : 3
09-07 11:37:38.498  1250  1650 D RttService: DefaultState got{ when=0 what=160512 target=com.android.internal.util.StateMachine$SmHandler }
09-07 11:37:38.498   554  1414 D CommandListener: Setting iface cfg
09-07 11:37:38.498   554  1414 D CommandListener: Trying to bring up p2p0
,09-07 11:37:38.498  1250  1649 E WifiScanningService: could not start HAL
09-07 11:37:38.498  1250  1622 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
09-07 11:37:38.508  1250  1622 D SecContentProvider: insert(), uri = 2
09-07 11:37:38.508  1250  1622 D WifiP2pService: P2pEnablingState
09-07 11:37:38.508  1250  1622 D WifiP2pService: P2pEnablingState{ what=147457 }
09-07 11:37:38.508  1250  1622 D WifiP2pService: P2p socket connection successful
09-07 11:37:38.508  1250  1622 D WifiP2pService: P2pEnabledState
,09-07 11:37:38.508  1250  1622 D SecContentProvider: insert(), uri = 2
,09-07 11:37:38.508  1250  1623 D SecContentProvider2: query(), uri = 20 selection = getPromptCredentialsEnabled
,09-07 11:37:38.508  1250  1622 D WifiP2pService: sending p2p connection changed broadcast: DISCONNECTED
09-07 11:37:38.508  1250  1250 E WifiStateMachine: BroadcastReceiver : WIFI_P2P_STATE_CHANGED_ACTION is : android.net.wifi.p2p.STATE_CHANGED
09-07 11:37:38.508  1250  1417 D WifiDisplayController: Received WIFI_P2P_STATE_CHANGED_ACTION: enabled=true
09-07 11:37:38.508  1250  1630 E ConnectivityService: updateNetworkInfo()
09-07 11:37:38.508  1250  1630 D ConnectivityService: ignoring duplicate network state non-change. WIFI_P2P, state = DISCONNECTED
,09-07 11:37:38.508  1250  1417 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false, mScanRequestedInConnected = false
09-07 11:37:38.508  1250  1417 D WifiDisplayController: disconnect
09-07 11:37:38.508  1250  1417 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,09-07 11:37:38.508  6337  6337 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-07 11:37:38.508  6337  6337 D ActivityThread: Added TimaKeyStore provider
09-07 11:37:38.508  1694  1694 D SoundPathController: onReceive - android.hardware.display.action.WIFI_DISPLAY_STATUS_CHANGED
09-07 11:37:38.518  1694  1694 D ApMirroringController: onReceive android.hardware.display.action.WIFI_DISPLAY_STATUS_CHANGED
,09-07 11:37:38.518  1694  1694 D AllShareCastTile: onReceive : android.hardware.display.action.WIFI_DISPLAY_STATUS_CHANGED
09-07 11:37:38.518  1250  2327 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,09-07 11:37:38.518  1694  1694 D AllShareCastTile: wifi display status changed! scanstate : 0, ActiveDisplayState : 0
,09-07 11:37:38.518  6329  6329 I wpa_supplicant: P2P: Set Samsung Discovery Icon = 512
09-07 11:37:38.518  1250  1417 D WifiDisplayController: Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
09-07 11:37:38.518  1250  1417 I WifiDisplayAdapter: onP2pDisconnected
,09-07 11:37:38.518  1250  1417 D IpRemoteDisplayController: disconnectWfdBridgeServer
09-07 11:37:38.518  1250  1417 D IpRemoteDisplayController: WfdBridgeServer is already null
09-07 11:37:38.518  1694  1694 D WifiP2pController: onReceive android.net.wifi.p2p.CONNECTION_STATE_CHANGE
09-07 11:37:38.518  6329  6329 I wpa_supplicant: P2P: Set Samsung Discovery name = 
,09-07 11:37:38.518  1250  1378 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{b9989b2 u-1 android.net.wifi.p2p.CONNECTION_STATE_CHANGE qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{a3d25fa 6197:com.samsung.android.app.FileShareClient/5005}
,09-07 11:37:38.518  6197  6197 D FileShare-Client: ClientBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,09-07 11:37:38.518  6197  6197 D FileShare-Client: ClientBroadcastReceiver.onReceive - disconnected
09-07 11:37:38.518  6197  6197 D FileShare-Client: Outbound.stopDelayTimer - 
,09-07 11:37:38.528  1250  1623 D SecContentProvider2: query(), uri = 20 selection = getPromptCredentialsEnabled
,09-07 11:37:38.528  1250  2127 E IzatSvc_OSObserver: I/LocTech-Label :: OSOBSERVER :: Data Items In
09-07 11:37:38.528  1250  2127 E IzatSvc_OSObserver: I/LocTech-Value :: Data Item Value: Attach state: 3, Mac address valid: false, AP MAC address: [00:00:00:00:00:00], Wifi-Ap SSID Valid: false, SSID: 
09-07 11:37:38.528  1250  1994 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{b9989b2 u-1 android.net.wifi.p2p.CONNECTION_STATE_CHANGE qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{cdffcb4 5678:com.samsung.android.app.FileShareServer/5005}
09-07 11:37:38.528  1944  2290 E PhoneInterfaceManager: [PhoneIntfMgr] getIccId: ICC ID is null or empty.
,09-07 11:37:38.528  1250  2127 E IzatSvc_OSObserver: I/LocTech-Label :: OSOBSERVER :: Data Items In
09-07 11:37:38.528  1250  2127 E IzatSvc_OSObserver: I/LocTech-Value :: Data Item Value: Attach state: 3, Mac address valid: false, AP MAC address: [00:00:00:00:00:00], Wifi-Ap SSID Valid: false, SSID: 
,09-07 11:37:38.528  5678  5678 D FileShare-Server: ServerBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,09-07 11:37:38.528  5678  5678 V QC40_FileShareUiAdapter: isSupportedCommonUi [enabled]true
09-07 11:37:38.528  5678  5678 D QC40_FileShareUiAdapter: isSupportedCommonUi [appState]0
09-07 11:37:38.538  6337  6337 W System  : ClassLoader referenced unknown path: /system/app/Hs20Provider/lib/arm64
,09-07 11:37:38.548  1250  1990 W ActivityManager: Permission Denial: getCurrentUser() from pid=6337, uid=10085 requires android.permission.INTERACT_ACROSS_USERS
,09-07 11:37:38.548  1250  1622 E WifiP2pService: Failed to set my phone number info into probe response
09-07 11:37:38.548  1250  1622 D WifiNative-p2p0: p2pGetDeviceAddress
,09-07 11:37:38.548  1250  1622 D WifiNative-p2p0: p2pGetDeviceAddress returning 46:78:3e:eb:95:ef
,09-07 11:37:38.548  1250  1622 D WifiP2pService: DeviceAddress: 46:95:ef
09-07 11:37:38.548  1250  1417 D WifiDisplayController: Received WIFI_P2P_THIS_DEVICE_CHANGED_ACTION: mThisDevice= Device: [Tablet] Galaxy Tab S2
09-07 11:37:38.548  1250  1417 D WifiDisplayController:  deviceAddress: 46:78:3e:eb:95:ef
09-07 11:37:38.548  1250  1417 D WifiDisplayController:  primary type: 1-0050F204-9
09-07 11:37:38.548  1250  1417 D WifiDisplayController:  secondary type: null
09-07 11:37:38.548  1250  1417 D WifiDisplayController:  wps: 0
09-07 11:37:38.548  1250  1417 D WifiDisplayController:  grpcapab: 0
09-07 11:37:38.548  1250  1417 D WifiDisplayController:  devcapab: 0
09-07 11:37:38.548  1250  1417 D WifiDisplayController:  status: 3
09-07 11:37:38.548  1250  1417 D WifiDisplayController:  wfdInfo: null
09-07 11:37:38.548  1250  1417 D WifiDisplayController:  groupownerAddress: null
09-07 11:37:38.548  1250  1417 D WifiDisplayController:  GOdeviceName: null
09-07 11:37:38.548  1250  1417 D WifiDisplayController:  interfaceAddress: 
09-07 11:37:38.548  1250  1417 D WifiDisplayController:  SConnectInfo : null
09-07 11:37:38.548  1250  1417 D WifiDisplayController:  contactInfoHash : null
09-07 11:37:38.548  1250  1417 D WifiDisplayController:  ssDevInfo : 0
09-07 11:37:38.548  1250  1417 D WifiDisplayController:  iconIdx : 0
,09-07 11:37:38.548  6337  6347 D HotspotProvider: inside  query methodcontent://com.samsung.passpoint/hotspot_credentials
09-07 11:37:38.548  6337  6347 D HotspotProvider: CREDENTIAL
09-07 11:37:38.548  6337  6347 D HotspotProvider: No prepend tags
,09-07 11:37:38.558  1250  1625 D HS20StateMachine: CMD_HOTSPOT20_ENABLE : 
09-07 11:37:38.558  1250  1625 D HS20StateMachine: enter : DiscoveringState
,09-07 11:37:38.558  1250  1250 I ActivityManager: Killing 5743:com.android.defcontainer/u0a6 (adj 15): DHA:empty #31
,09-07 11:37:38.558  1250  1622 D WifiP2pService: sending p2p persistent groups changed broadcast
,09-07 11:37:38.568  1250  1622 D WifiP2pService: InactiveState
,09-07 11:37:38.568  1250  1622 D WifiP2pService: InactiveState{ what=143376 }
09-07 11:37:38.568  1250  1622 E WifiP2pService: Airplane mode : skipped SET_COUNTRY_CODE
09-07 11:37:38.568  1250  1622 D WifiP2pService: P2pEnabledState{ what=143376 }
,09-07 11:37:38.698  1250  2396 D ActivityManager: isAutoRunBlockedApp:: com.android.defcontainer, Auto Run ON
09-07 11:37:38.698  1250  2396 D ActivityManager: removeProcessNameLocked mProcessNames.remove pid=5743 ,hash=76684155 ,name=com.android.defcontainer
,09-07 11:37:39.328  1250  1313 D SecContentProvider: query(), uri = 18 selection = isWifiEnabled
,09-07 11:37:39.328  1250  1313 D SecContentProvider2: query(), uri = 20 selection = isWifiStateChangeAllowed
,09-07 11:37:39.328  1250  1313 D WifiService: setWifiEnabled: false pid=5989, uid=10136
,09-07 11:37:39.338  1250  1313 D SettingsProvider: isChangeAllowed() : name = wifi_on
,09-07 11:37:39.338  1250  1624 D WifiStateMachine: setFccChannel: channel = 0
09-07 11:37:39.338  1250  1624 D WifiController: [FCC]setFccChannel() is called !!!
09-07 11:37:39.338  1250  1624 D WifiController: MHS off and WIFI tunred off and move to mApStaDisabledState
09-07 11:37:39.338  1250  1624 D WifiController: [FCC]Airplane on, setFccChannel(0)!!!
09-07 11:37:39.338  1250  1624 D SecContentProvider: insert(), uri = 2
09-07 11:37:39.338  1250  1623 D WifiBigDataLog: getJsonFormat() - feature : ONOF
,09-07 11:37:39.338  1250  2127 E OsAgent :  Wifi Scan Always Available: 0
09-07 11:37:39.338  1250  2127 E IzatSvc_OSObserver: I/LocTech-Label :: OSOBSERVER :: Data Items In
09-07 11:37:39.338  1250  2127 E IzatSvc_OSObserver: I/LocTech-Value :: Data Item Value: IS_WIFI_HARDWARE_ON: false
09-07 11:37:39.338  1250  1623 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:836 com.android.server.wifi.WifiStateMachine.insertLog:18843 com.android.server.wifi.WifiStateMachine.access$4300:293 com.android.server.wifi.WifiStateMachine$DefaultState.processMessage:8707 com.android.internal.util.StateMachine$SmHandler.processMsg:968 
,09-07 11:37:39.338  1250  2127 E OsAgent :  Wifi Scan Always Available: 0
09-07 11:37:39.338  1250  2127 E IzatSvc_OSObserver: I/LocTech-Label :: OSOBSERVER :: Data Items In
09-07 11:37:39.338  1250  2127 E IzatSvc_OSObserver: I/LocTech-Value :: Data Item Value: IS_WIFI_HARDWARE_ON: false
09-07 11:37:39.338  1250  2127 E OsAgent :  Wifi Scan Always Available: 0
09-07 11:37:39.338  1250  2127 E IzatSvc_OSObserver: I/LocTech-Label :: OSOBSERVER :: Data Items In
09-07 11:37:39.338  1250  2127 E IzatSvc_OSObserver: I/LocTech-Value :: Data Item Value: IS_WIFI_HARDWARE_ON: false
09-07 11:37:39.338  1250  2132 E LocSvc_LBSApiV02: E/virtual int lbs_core::LBSApiV02::wifiEnabledStatusInject(int):677]: Error : st = 2, ind.status = 1310827456
09-07 11:37:39.338  1250  2152 E LocSvc_libulp: I/int ulp_msg_process_phone_setting_update(const UlpPhoneContextSettings*), context type: 0x4
09-07 11:37:39.338  1250  2152 E LocSvc_libulp:   gps enabled: 0
09-07 11:37:39.338  1250  2152 E LocSvc_libulp:  network position available 0
09-07 11:37:39.338  1250  2152 E LocSvc_libulp:  wifi setting enabled 0
09-07 11:37:39.338  1250  2152 E LocSvc_libulp:  battery charging 0, agps enabled 0, enh_location_services_enabled 0is_pip_user_setting_enabled 0
09-07 11:37:39.338  1250  2152 E LocSvc_libulp: I/int ulp_msg_process_system_update(UlpSystemEvent): systemEvent:4 
,09-07 11:37:39.348  1250  1623 D WifiBigDataLog: init : 
,09-07 11:37:39.348  1250  1623 D WifiStateMachine: setFccChannelNative: channel = 0
09-07 11:37:39.348  1250  1623 D WifiNative-wlan0: callSECApiInt - ID [230]
09-07 11:37:39.348  1250  1378 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{94ea480 u0 com.samsung.android.providers.context.log.action.USE_APP_FEATURE_SURVEY qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{573bf46 2626:com.samsung.android.providers.context/u0a5}
,09-07 11:37:39.348  1250  1623 V AlarmManager:  remove PendingIntent] PendingIntent{a985477: PendingIntentRecord{7a268e4 android broadcastIntent}}
,09-07 11:37:39.358  1250  1250 D RttService: SCAN_AVAILABLE : 1
09-07 11:37:39.358  1250  1622 D WifiP2pService: InactiveState{ what=131204 }
09-07 11:37:39.358  1250  1650 D RttService: EnabledState got{ when=0 what=160513 target=com.android.internal.util.StateMachine$SmHandler }
09-07 11:37:39.358  1250  1622 D WifiP2pService: P2pEnabledState{ what=131204 }
09-07 11:37:39.358  6329  6329 I wpa_supplicant: P2P: Set prekey state (NONE -> NONE)
,09-07 11:37:39.358  6329  6329 I wpa_supplicant: P2P: Clear a pre-passphrase (State NONE)
09-07 11:37:39.358  1250  1622 D WifiP2pService: sending p2p connection changed broadcast: FAILED
09-07 11:37:39.358  1250  1630 E ConnectivityService: updateNetworkInfo()
,09-07 11:37:39.358  1250  1630 D ConnectivityService: ignoring duplicate network state non-change. WIFI_P2P, state = DISCONNECTED
,09-07 11:37:39.358  1250  1417 D WifiDisplayController: Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/FAILED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
09-07 11:37:39.358  1250  1417 I WifiDisplayAdapter: onP2pDisconnected
,09-07 11:37:39.358  1250  1417 D IpRemoteDisplayController: disconnectWfdBridgeServer
09-07 11:37:39.358  1250  1417 D IpRemoteDisplayController: WfdBridgeServer is already null
09-07 11:37:39.358  1694  1694 D WifiP2pController: onReceive android.net.wifi.p2p.CONNECTION_STATE_CHANGE
,09-07 11:37:39.368  1250  1378 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{79b3ab9 u-1 android.net.wifi.p2p.CONNECTION_STATE_CHANGE qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{a3d25fa 6197:com.samsung.android.app.FileShareClient/5005}
,09-07 11:37:39.368  6197  6197 D FileShare-Client: ClientBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,09-07 11:37:39.368  1250  1630 E ConnectivityService: updateNetworkInfo()
09-07 11:37:39.368  1250  1622 D WifiP2pService: sending p2p connection changed broadcast: DISCONNECTED
09-07 11:37:39.368  1250  1630 D ConnectivityService: ignoring duplicate network state non-change. WIFI_P2P, state = DISCONNECTED
09-07 11:37:39.368  6197  6197 D FileShare-Client: ClientBroadcastReceiver.onReceive - disconnected
09-07 11:37:39.368  6197  6197 D FileShare-Client: Outbound.stopDelayTimer - 
,09-07 11:37:39.368  1250  1622 D SecContentProvider: insert(), uri = 2
,09-07 11:37:39.368  1250  1250 E WifiStateMachine: BroadcastReceiver : WIFI_P2P_STATE_CHANGED_ACTION is : android.net.wifi.p2p.STATE_CHANGED
09-07 11:37:39.368  1250  1417 D WifiDisplayController: Received WIFI_P2P_STATE_CHANGED_ACTION: enabled=false
09-07 11:37:39.368  1250  1417 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false, mScanRequestedInConnected = false
,09-07 11:37:39.368  1250  1622 D WifiP2pService: P2pDisablingState
09-07 11:37:39.368  1250  1417 D WifiDisplayController: disconnect
09-07 11:37:39.368  1250  1622 D WifiP2pService: P2pDisablingState{ what=147458 }
09-07 11:37:39.368  1250  1417 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
09-07 11:37:39.368  1250  1622 D WifiP2pService: p2p socket connection lost
,09-07 11:37:39.368  1250  1622 D SecContentProvider: insert(), uri = 2
09-07 11:37:39.368  1694  1694 D WifiP2pController: onReceive android.net.wifi.p2p.CONNECTION_STATE_CHANGE
09-07 11:37:39.368  1250  1623 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,09-07 11:37:39.368  1250  1622 D WifiP2pService: P2pDisabledState
09-07 11:37:39.368   554  1414 D CommandListener: Clearing all IP addresses on wlan0
,09-07 11:37:39.378  1250  1720 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{79b3ab9 u-1 android.net.wifi.p2p.CONNECTION_STATE_CHANGE qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{cdffcb4 5678:com.samsung.android.app.FileShareServer/5005}
,09-07 11:37:39.378  1250  1417 D WifiDisplayController: Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: false]
09-07 11:37:39.378  1250  1417 I WifiDisplayAdapter: onP2pDisconnected
,09-07 11:37:39.378  1250  1417 D IpRemoteDisplayController: disconnectWfdBridgeServer
09-07 11:37:39.378  1250  1417 D IpRemoteDisplayController: WfdBridgeServer is already null
,09-07 11:37:39.378  1694  1694 D SoundPathController: onReceive - android.hardware.display.action.WIFI_DISPLAY_STATUS_CHANGED
09-07 11:37:39.378  1694  1694 D ApMirroringController: onReceive android.hardware.display.action.WIFI_DISPLAY_STATUS_CHANGED
,09-07 11:37:39.378  1694  1694 D AllShareCastTile: onReceive : android.hardware.display.action.WIFI_DISPLAY_STATUS_CHANGED
09-07 11:37:39.378  1250  1721 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,09-07 11:37:39.378  1694  1694 D AllShareCastTile: wifi display status changed! scanstate : 0, ActiveDisplayState : 0
,09-07 11:37:39.378  5678  5678 D FileShare-Server: ServerBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
09-07 11:37:39.378  1250  1623 D WifiStateMachine: SupplicantStoppingState: stopSupplicant  init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
09-07 11:37:39.378  5678  5678 V QC40_FileShareUiAdapter: isSupportedCommonUi [enabled]true
,09-07 11:37:39.388  5678  5678 D QC40_FileShareUiAdapter: isSupportedCommonUi [appState]0
,09-07 11:37:39.388  1250  1250 I WifiTrafficPoller: evaluateTrafficStatsPolling
,09-07 11:37:39.388  1250  1250 D HS20StateMachine: Broadcast Received: android.net.wifi.STATE_CHANGE
09-07 11:37:39.388  1250  1250 D HS20StateMachine: [type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: false]
,09-07 11:37:39.388  1250  1250 I WifiHs20Service: Broadcast received:android.net.wifi.STATE_CHANGE
09-07 11:37:39.388  1250  1628 I WifiHs20Service: Message received 5007
,09-07 11:37:39.388  1694  2100 D NetworkController: onReceive: intent=Intent { act=android.net.wifi.STATE_CHANGE flg=0x4000010 bqHint=4 VirtualScreenParam=Params{mDisplayId=-1, null, mFlags=0x00000000)} (has extras) }
,09-07 11:37:39.388  1944  1944 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.net.wifi.STATE_CHANGE
,09-07 11:37:39.398  1694  1694 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
,09-07 11:37:39.398  1694  1694 D HotspotTile: onReceive : 0, 0
09-07 11:37:39.398  1694  2100 D NetworkController: onReceive: intent=Intent { act=android.net.wifi.WIFI_STATE_CHANGED flg=0x4000010 bqHint=4 VirtualScreenParam=Params{mDisplayId=-1, null, mFlags=0x00000000)} (has extras) }
,09-07 11:37:39.398  1694  2126 D QSTile.WifiTile: handleUpdateState  cb.changed 5 wifiEnabled : OFF 
,09-07 11:37:39.398  1694  1694 D QSTileView: handleLabelStateChanged() label = Wi-Fi cellWidth 148
09-07 11:37:39.398  1250  2327 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{d128efe u-1 android.net.wifi.p2p.CONNECTION_STATE_CHANGE qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{a3d25fa 6197:com.samsung.android.app.FileShareClient/5005}
,09-07 11:37:39.398  6197  6197 D FileShare-Client: ClientBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
09-07 11:37:39.398  5989  5989 D BluetoothAdapter: STATE_ON
,09-07 11:37:39.398  6197  6197 D FileShare-Client: ClientBroadcastReceiver.onReceive - disconnected
09-07 11:37:39.398  6197  6197 D FileShare-Client: Outbound.stopDelayTimer - 
,09-07 11:37:39.398  5989  5989 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-07 11:37:39.398  5989  5989 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-07 11:37:39.398  5989  5989 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-07 11:37:39.398  5989  5989 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-07 11:37:39.398  5989  5989 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-07 11:37:39.398  5989  5989 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-07 11:37:39.398  5989  5989 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-07 11:37:39.398  5989  5989 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-07 11:37:39.398  5989  5989 D BluetoothAdapter: STATE_ON
09-07 11:37:39.398  1250  1994 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{d128efe u-1 android.net.wifi.p2p.CONNECTION_STATE_CHANGE qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{cdffcb4 5678:com.samsung.android.app.FileShareServer/5005}
,09-07 11:37:39.408  5989  5989 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-07 11:37:39.408  1250  1250 D HS20StateMachine: Broadcast Received: android.net.wifi.WIFI_STATE_CHANGED
09-07 11:37:39.408  1250  1250 I WifiHs20Service: Broadcast received:android.net.wifi.WIFI_STATE_CHANGED
09-07 11:37:39.408  1250  1628 I WifiHs20Service: Message received 5011
,09-07 11:37:39.408  1250  1250 D WifiNotificationController: SHOW_NOTI_MESSAGE : 17, visible : false, ssid : null, targetSSID : null, netId : -1, titleType : -1
09-07 11:37:39.408  1250  1250 D WifiNotificationController: showMaliciousHotspotDetectionNotification - MaliciousNetwork:null, visible:false
09-07 11:37:39.408  5678  5678 D FileShare-Server: ServerBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,09-07 11:37:39.408  1250  1631 D ConnectivityManager: getMobileDataEnabled()+ subId=2147483643
09-07 11:37:39.408  5678  5678 V QC40_FileShareUiAdapter: isSupportedCommonUi [enabled]true
09-07 11:37:39.408  1944  1963 D PhoneInterfaceManager: [PhoneIntfMgr] getDataEnabled: subId=2147483643 phoneId=0
09-07 11:37:39.408  1944  1963 D PhoneInterfaceManager: [PhoneIntfMgr] getDataEnabled: subId=2147483643 retVal=true
09-07 11:37:39.408  5989  5989 D BluetoothAdapter: STATE_ON
09-07 11:37:39.408  1250  1631 D ConnectivityManager: getMobileDataEnabled()- subId=2147483643 retVal=true
09-07 11:37:39.408  5678  5678 D QC40_FileShareUiAdapter: isSupportedCommonUi [appState]0
,09-07 11:37:39.408  5989  5989 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-07 11:37:39.408  5989  5989 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-07 11:37:39.408  5989  5989 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-07 11:37:39.408  5989  5989 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-07 11:37:39.408  5989  5989 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-07 11:37:39.408  5989  5989 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-07 11:37:39.408  5989  5989 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-07 11:37:39.408  5989  5989 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-07 11:37:39.408  5989  5989 D BluetoothAdapter: STATE_ON
09-07 11:37:39.408  1250  1986 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{eec765f u-1 android.net.wifi.STATE_CHANGE qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{e03cd16 6153:com.sec.android.diagmonagent/1000}
,09-07 11:37:39.418  5989  5989 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-07 11:37:39.418  6153  6153 I DIAGMON_AGENT: [lllIIIIIIlllIlIIIIII(51/llIIIIlllllIIllIIllI)] Receive broadcast: android.net.wifi.STATE_CHANGE
09-07 11:37:39.418  6153  6153 I DIAGMON_AGENT: [lllIIIIIIlllIlIIIIII(52/llIIIIlllllIIllIIllI)] Receive broadcast:
,09-07 11:37:39.418  6153  6153 W DIAGMON_AGENT: [lllIIIIIIlllIlIIIIII(31/llIIIIlllllIIllIIllI)] Network is changed and not available now, so don't do anything
,09-07 11:37:39.418  1250  1990 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{eec765f u-1 android.net.wifi.STATE_CHANGE qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{7cc8669 6173:com.sec.app.RilErrorNotifier/1000}
,09-07 11:37:39.418  6173  6173 I PhoneErrorReceiver: onReceive
09-07 11:37:39.418  6173  6173 I MIPErrReceiver: isWiFiConnected
09-07 11:37:39.418  1250  2327 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
,09-07 11:37:39.418  1250  1990 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{eec765f u-1 android.net.wifi.STATE_CHANGE qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{195a0dd 5691:com.enhance.gameservice/u0a79}
,09-07 11:37:39.428  1250  2674 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{eec765f u-1 android.net.wifi.STATE_CHANGE qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{61e2025 6185:com.sec.knox.switcher/1000}
,09-07 11:37:39.428  6185  6185 I usagelog: received in receiver
09-07 11:37:39.428  6185  6185 I KnoxUsageLogPro: KnoxUsageReceiver onReceive :android.net.wifi.STATE_CHANGE myUserId=0
09-07 11:37:39.428  6185  6185 I KnoxUsageLogPro: premStatus:2
,09-07 11:37:39.428  6185  6185 I KnoxUsageLogPro: isEulaShown : false
09-07 11:37:39.428  6185  6185 I KnoxUsageLogPro: KnoxUsageReceiver onReceive : not Processible, just return
,09-07 11:37:39.428  1250  2674 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{33988ac u-1 android.net.wifi.WIFI_STATE_CHANGED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{9925d68 5989:com.test.thalitest/u0a136}
09-07 11:37:39.428  1250  1986 D ConnectivityService: returning getNetworkInfo for network type 0 : [type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
09-07 11:37:39.428  1250  1986 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
09-07 11:37:39.428  1250  1986 D ConnectivityService: returning getNetworkInfo for network type 2 : [type: MOBILE_MMS[] - MOBILE_MMS, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
09-07 11:37:39.438  1250  1986 D ConnectivityService: returning getNetworkInfo for network type 3 : [type: MOBILE_SUPL[] - MOBILE_SUPL, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
09-07 11:37:39.438  1250  1986 D ConnectivityService: returning getNetworkInfo for network type 4 : [type: MOBILE_DUN[] - MOBILE_DUN, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
09-07 11:37:39.438  1250  1986 D ConnectivityService: returning getNetworkInfo for network type 5 : [type: MOBILE_HIPRI[] - MOBILE_HIPRI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
09-07 11:37:39.438  1250  1986 D ConnectivityService: returning getNetworkInfo for network type 7 : [type: BLUETOOTH[] - BLUETOOTH, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
09-07 11:37:39.438  1250  1986 D ConnectivityService: returning getNetworkInfo for network type 9 : [type: ETHERNET[] - ETHERNET, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
09-07 11:37:39.438  1250  1986 D ConnectivityService: returning getNetworkInfo for network type 10 : [type: MOBILE_FOTA[] - MOBILE_FOTA, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
09-07 11:37:39.438  1250  1986 D ConnectivityService: returning getNetworkInfo for network type 11 : [type: MOBILE_IMS[] - MOBILE_IMS, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
09-07 11:37:39.438  1250  1986 D ConnectivityService: returning getNetworkInfo for network type 12 : [type: MOBILE_CBS[] - MOBILE_CBS, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
09-07 11:37:39.438  1250  1986 D ConnectivityService: returning getNetworkInfo for network type 13 : [type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: false]
09-07 11:37:39.438  1250  1986 D ConnectivityService: returning getNetworkInfo for network type 14 : [type: MOBILE_IA[] - MOBILE_IA, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
09-07 11:37:39.438  1250  1986 D ConnectivityService: returning getNetworkInfo for network type 15 : [type: MOBILE_EMERGENCY[] - MOBILE_EMERGENCY, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
09-07 11:37:39.438  1250  1986 D ConnectivityService: returning getNetworkInfo for network type 17 : [type: VPN[] - VPN, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false,, isAvailable: true]
,09-07 11:37:39.438  1250  2010 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{33988ac u-1 android.net.wifi.WIFI_STATE_CHANGED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{6f787ab 6209:com.samsung.android.securitylogagent/1000}
,09-07 11:37:39.518  6329  6329 I wpa_supplicant: Blacklist: Clear (all) 
09-07 11:37:39.518  6329  6329 I wpa_supplicant: nl80211: deinit ifname=p2p0 disabled_11b_rates=0
,09-07 11:37:39.618   554  1406 D Netd    : Iface p2p0 link down
09-07 11:37:39.618  6329  6329 I wpa_supplicant: p2p0: CTRL-EVENT-TERMINATING 
,09-07 11:37:39.618   766  1446 I QC-NETMGR-LIB: Received nl msg, recvmsg returned 1084
09-07 11:37:39.618   766  1446 I QC-NETMGR-LIB: Received command: ID=NETMGR_KIF_MSG_CMD, link=0
09-07 11:37:39.618   766  1442 I QC-NETMGR-LIB: Process command: ID=NETMGR_KIF_MSG_CMD, link=0, state=1
09-07 11:37:39.618   766  1442 I QC-NETMGR-LIB: Processing RTM_NEWLINK
09-07 11:37:39.618   766  1442 I QC-NETMGR-LIB: Metainfo:  Index=16 Family=0 Type=0x1 Change=[0x1]UP  Flags=[0x1002]BROADCAST MULTICAST 
09-07 11:37:39.618   766  1442 I QC-NETMGR-LIB: Rcvd Netlink msg type [16]
09-07 11:37:39.618   766  1442 I QC-NETMGR-LIB: Received RTM_NEWLINK
09-07 11:37:39.618   766  1442 E QC-NETMGR-LIB: unrecognized ifindex 16, disable link
,09-07 11:37:39.938  6329  6329 I wpa_supplicant: Blacklist: Clear (all) 
09-07 11:37:39.938  6329  6329 I wpa_supplicant: nl80211: deinit ifname=wlan0 disabled_11b_rates=0
,09-07 11:37:40.058   766  1446 I QC-NETMGR-LIB: Received nl msg, recvmsg returned 1084
09-07 11:37:40.058   766  1446 I QC-NETMGR-LIB: Received command: ID=NETMGR_KIF_MSG_CMD, link=0
09-07 11:37:40.058   554  1406 D Netd    : Iface wlan0 link down
09-07 11:37:40.058  6329  6329 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING 
09-07 11:37:40.058   766  1442 I QC-NETMGR-LIB: Process command: ID=NETMGR_KIF_MSG_CMD, link=0, state=1
09-07 11:37:40.058   766  1442 I QC-NETMGR-LIB: Processing RTM_NEWLINK
09-07 11:37:40.058   766  1442 I QC-NETMGR-LIB: Metainfo:  Index=15 Family=0 Type=0x1 Change=[0x1]UP  Flags=[0x1002]BROADCAST MULTICAST 
09-07 11:37:40.058   766  1442 I QC-NETMGR-LIB: Rcvd Netlink msg type [16]
09-07 11:37:40.058   766  1442 I QC-NETMGR-LIB: Received RTM_NEWLINK
09-07 11:37:40.058   766  1442 E QC-NETMGR-LIB: unrecognized ifindex 15, disable link
,09-07 11:37:40.158  1250  1623 D WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:0
,09-07 11:37:40.158  1250  1250 D WifiNotificationController: SHOW_NOTI_MESSAGE : 9, visible : false, ssid : <unknown ssid>, targetSSID : null, netId : -1, titleType : -1
09-07 11:37:40.158  1250  1250 D WifiNotificationController: SHOW_NOTI_MESSAGE : 13, visible : false, ssid : <unknown ssid>, targetSSID : null, netId : -1, titleType : 0
09-07 11:37:40.158  1250  1250 D WifiNotificationController: showCaptivePortalDisabledStatus with ssid/visible/title:null/false/0
,09-07 11:37:40.168  1250  1250 D HS20StateMachine: Broadcast Received: android.net.wifi.WIFI_STATE_CHANGED
09-07 11:37:40.168  1250  1625 D HS20StateMachine: WIFI_STATE_DISABLED
09-07 11:37:40.168  1250  1625 D HS20StateMachine: CMD_HOTSPOT20_DISABLE
09-07 11:37:40.168  1250  1625 D HS20StateMachine: enter : DisablingState
09-07 11:37:40.168  1250  1627 D HS20SubscriptionManager: Received CMD_RELEASE_TLS, flag=1
09-07 11:37:40.168  1250  1250 I WifiHs20Service: Broadcast received:android.net.wifi.WIFI_STATE_CHANGED
09-07 11:37:40.168  1250  1625 D HS20StateMachine: enter : DisabledState
09-07 11:37:40.168  1250  1628 I WifiHs20Service: Message received 5011
,09-07 11:37:40.168  1694  2100 D NetworkController: onReceive: intent=Intent { act=android.net.wifi.WIFI_STATE_CHANGED flg=0x4000010 bqHint=4 VirtualScreenParam=Params{mDisplayId=-1, null, mFlags=0x00000000)} (has extras) }
09-07 11:37:40.168  1694  1694 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
09-07 11:37:40.168  1250  1631 D ConnectivityManager: getMobileDataEnabled()+ subId=2147483643
,09-07 11:37:40.168  1944  2295 D PhoneInterfaceManager: [PhoneIntfMgr] getDataEnabled: subId=2147483643 phoneId=0
09-07 11:37:40.168  1694  1694 D HotspotTile: onReceive : 1, 0
09-07 11:37:40.168  1944  2295 D PhoneInterfaceManager: [PhoneIntfMgr] getDataEnabled: subId=2147483643 retVal=true
09-07 11:37:40.168  1250  1631 D ConnectivityManager: getMobileDataEnabled()- subId=2147483643 retVal=true
,09-07 11:37:40.168  1866  2363 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,09-07 11:37:40.178  5989  5989 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-07 11:37:40.178  1250  1378 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{82bc975 u-1 android.net.wifi.WIFI_STATE_CHANGED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{9925d68 5989:com.test.thalitest/u0a136}
,09-07 11:37:40.178  5989  5989 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-07 11:37:40.178  1250  1310 D ConnectivityService: returning getNetworkInfo for network type 0 : [type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
09-07 11:37:40.178  1250  1310 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
09-07 11:37:40.178  1250  1310 D ConnectivityService: returning getNetworkInfo for network type 2 : [type: MOBILE_MMS[] - MOBILE_MMS, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
09-07 11:37:40.178  1250  1310 D ConnectivityService: returning getNetworkInfo for network type 3 : [type: MOBILE_SUPL[] - MOBILE_SUPL, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
09-07 11:37:40.178  1250  1310 D ConnectivityService: returning getNetworkInfo for network type 4 : [type: MOBILE_DUN[] - MOBILE_DUN, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
09-07 11:37:40.178  1250  1310 D ConnectivityService: returning getNetworkInfo for network type 5 : [type: MOBILE_HIPRI[] - MOBILE_HIPRI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
09-07 11:37:40.178  1250  1310 D ConnectivityService: returning getNetworkInfo for network type 7 : [type: BLUETOOTH[] - BLUETOOTH, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
09-07 11:37:40.178  1250  1310 D ConnectivityService: returning getNetworkInfo for network type 9 : [type: ETHERNET[] - ETHERNET, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
09-07 11:37:40.178  1250  1310 D ConnectivityService: returning getNetworkInfo for network type 10 : [type: MOBILE_FOTA[] - MOBILE_FOTA, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
09-07 11:37:40.178  1250  1310 D ConnectivityService: returning getNetworkInfo for network type 11 : [type: MOBILE_IMS[] - MOBILE_IMS, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
09-07 11:37:40.178  1250  1310 D ConnectivityService: returning getNetworkInfo for network type 12 : [type: MOBILE_CBS[] - MOBILE_CBS, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
09-07 11:37:40.178  1250  1310 D ConnectivityService: returning getNetworkInfo for network type 13 : [type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: false]
09-07 11:37:40.178  1250  1310 D ConnectivityService: returning getNetworkInfo for network type 14 : [type: MOBILE_IA[] - MOBILE_IA, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
09-07 11:37:40.178  1250  1310 D ConnectivityService: returning getNetworkInfo for network type 15 : [type: MOBILE_EMERGENCY[] - MOBILE_EMERGENCY, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
09-07 11:37:40.178  1250  1310 D ConnectivityService: returning getNetworkInfo for network type 17 : [type: VPN[] - VPN, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
,09-07 11:37:40.188  1250  1720 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{82bc975 u-1 android.net.wifi.WIFI_STATE_CHANGED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{6f787ab 6209:com.samsung.android.securitylogagent/1000}
,09-07 11:37:40.338   707   707 I MSM-irqbalance: Decided to move IRQ155 from CPU3 to CPU1
,09-07 11:37:41.088   766  1446 I QC-NETMGR-LIB: Received nl msg, recvmsg returned 476
09-07 11:37:41.088   766  1446 I QC-NETMGR-LIB: Received command: ID=NETMGR_KIF_MSG_CMD, link=0
09-07 11:37:41.088   766  1442 I QC-NETMGR-LIB: Process command: ID=NETMGR_KIF_MSG_CMD, link=0, state=1
09-07 11:37:41.088   766  1442 I QC-NETMGR-LIB: Processing RTM_DELLINK
09-07 11:37:41.088   766  1442 I QC-NETMGR-LIB: Metainfo:  Index=15 Family=0 Type=0x1 Change=[0xffffffff]UP BROADCAST DEBUG LOOPBACK POINTOPOINT NOTRAILERS RUNNING NOARP PROMISC ALLMULTI MASTER SLAVE MULTICAST PORTSEL AUTOMEDIA DYNAMIC LOWER_UP DORMANT  Flags=[0x1002]BROADCAST MULTICAST 
09-07 11:37:41.088   766  1442 I QC-NETMGR-LIB: Rcvd Netlink msg type [17]
09-07 11:37:41.088   766  1442 I QC-NETMGR-LIB: Received RTM_DELLINK
09-07 11:37:41.088   766  1442 E QC-NETMGR-LIB: unrecognized ifindex 15, disable link
,09-07 11:37:41.088  1250  1384 E EthernetNetworkFactory: stopTrackingInterface : not matched eth0/usb0 iface is wlan0
,09-07 11:37:41.338   766  1446 I QC-NETMGR-LIB: Received nl msg, recvmsg returned 476
09-07 11:37:41.338   766  1446 I QC-NETMGR-LIB: Received command: ID=NETMGR_KIF_MSG_CMD, link=0
09-07 11:37:41.338   766  1442 I QC-NETMGR-LIB: Process command: ID=NETMGR_KIF_MSG_CMD, link=0, state=1
09-07 11:37:41.338   766  1442 I QC-NETMGR-LIB: Processing RTM_DELLINK
09-07 11:37:41.338   766  1442 I QC-NETMGR-LIB: Metainfo:  Index=16 Family=0 Type=0x1 Change=[0xffffffff]UP BROADCAST DEBUG LOOPBACK POINTOPOINT NOTRAILERS RUNNING NOARP PROMISC ALLMULTI MASTER SLAVE MULTICAST PORTSEL AUTOMEDIA DYNAMIC LOWER_UP DORMANT  Flags=[0x1002]BROADCAST MULTICAST 
09-07 11:37:41.338   766  1442 I QC-NETMGR-LIB: Rcvd Netlink msg type [17]
09-07 11:37:41.338   766  1442 I QC-NETMGR-LIB: Received RTM_DELLINK
09-07 11:37:41.338   766  1442 E QC-NETMGR-LIB: unrecognized ifindex 16, disable link
,09-07 11:37:41.338  1250  1384 E EthernetNetworkFactory: stopTrackingInterface : not matched eth0/usb0 iface is p2p0
,09-07 11:37:42.198  1250  1623 D WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:1
,09-07 11:37:42.338  5989  6040 D BluetoothAdapter: disable()
,09-07 11:37:42.348  1250  1378 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{7849d0a u0 com.samsung.android.providers.context.log.action.USE_APP_FEATURE_SURVEY qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{573bf46 2626:com.samsung.android.providers.context/u0a5}
,09-07 11:37:42.358  1250  1964 D SettingsProvider: isChangeAllowed() : name = bluetooth_on
,09-07 11:37:42.358  5989  6040 D BluetoothAdapter: enable()
09-07 11:37:42.358  1250  1416 D SecContentProvider: insert(), uri = 2
,09-07 11:37:42.368  2587  2751 D BluetoothAdapterState: Current state: ON, message: BLE_TURN_OFF
,09-07 11:37:42.368  5989  6040 D BluetoothAdapter: enable(): BT is already enabled..!
09-07 11:37:42.368  1250  1378 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{b0c197b u0 com.samsung.android.providers.context.log.action.USE_APP_FEATURE_SURVEY qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{573bf46 2626:com.samsung.android.providers.context/u0a5}
09-07 11:37:42.368  2587  2751 D BluetoothAdapterProperties: Setting state to 13
09-07 11:37:42.368  2587  2751 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
09-07 11:37:42.368  2587  2751 D BluetoothAdapterService: Bluetooth PBAP supproted is true
09-07 11:37:42.368  2587  2751 D BluetoothAdapterService: updateAdapterState state is 13
,09-07 11:37:42.368  2587  2587 I BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED, state: 13
,09-07 11:37:42.378  1250  1416 D BluetoothManagerService: Turning On/Off, G state: 3, S state: 3, mBLE count: 0, s BLE count: 0
09-07 11:37:42.378  2587  2751 D BluetoothAdapterService: Autoconnection is available 
09-07 11:37:42.378  2587  2751 D BluetoothAdapterService: updateAdapterState prevState = 12newState = 13
09-07 11:37:42.378  2587  2751 D BluetoothAdapterService: terminating service from this receiver
,09-07 11:37:42.378  1694  1694 D BluetoothPbap: Proxy object disconnected
09-07 11:37:42.378  1694  1694 D PbapServerProfile: Bluetooth service disconnected
,09-07 11:37:42.378  1250  1250 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
09-07 11:37:42.378  1250  1250 I InputMethodManagerService: [BT Setting State] State =13
09-07 11:37:42.378  2587  2751 D BluetoothAdapterProperties: onBluetoothDisable()
,09-07 11:37:42.378  2587  2751 W bt_btif : btif_dm_cancel_discovery
09-07 11:37:42.378  2040  2040 D ucsBai_ConnectionManager: BluetoothReceiver Action android.bluetooth.adapter.action.STATE_CHANGED
09-07 11:37:42.378  1250  1250 D BluetoothPhoneService: Bluetooth Adapter state : 13
,09-07 11:37:42.378  1250  2674 D SecContentProvider: query(), uri = 3 selection = isDiscoverableEnabled
,09-07 11:37:42.388  5989  6040 D BluetoothAdapter: disable()
,09-07 11:37:42.388  1250  1720 D SecContentProvider: insert(), uri = 2
09-07 11:37:42.388  1694  2100 V BluetoothEventManager: onReceive :: android.bluetooth.adapter.action.STATE_CHANGED
09-07 11:37:42.388  1694  2100 D BluetoothEventManager: AdapterStateChangedHandler :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 13
,09-07 11:37:42.388  2587  2751 I BluetoothAdapterState: Entering PendingCommandState
09-07 11:37:42.388  1250  1986 V AlarmManager:  remove PendingIntent] PendingIntent{40c8398: PendingIntentRecord{45887f2 com.android.bluetooth broadcastIntent}}
,09-07 11:37:42.388  3003  3007 I WCNSS_FILTER: ibs_msm_serial_clock_vote: vote UART CLK ON using UART driver's ioctl()
,09-07 11:37:42.398  1250  1250 D KnoxKeyguardUpdateMonitor: BroadcastReceiver onReceive
09-07 11:37:42.398  1250  1250 D KnoxKeyguardUpdateMonitor: BroadcastReceiver onReceive action: android.bluetooth.adapter.action.STATE_CHANGED
09-07 11:37:42.398  1250  1250 D KnoxKeyguardUpdateMonitor: BroadcastReceiver onReceive BT state is changed
,09-07 11:37:42.398  1250  1378 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{8fc87f1 u-1 android.bluetooth.adapter.action.STATE_CHANGED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{60a5ff2 5843:com.android.settings/1000}
,09-07 11:37:42.398  5989  5989 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-07 11:37:42.398  5989  5989 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-07 11:37:42.398  5989  5989 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-07 11:37:42.398  5989  5989 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-07 11:37:42.398  5989  5989 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-07 11:37:42.398  5989  5989 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-07 11:37:42.398  5989  5989 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-07 11:37:42.398  5989  5989 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-07 11:37:42.398  5989  5989 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-07 11:37:42.398  2587  2756 D BluetoothUtils: getBtEnabledContainers(): btContainers = []
09-07 11:37:42.398  2587  2756 D BluetoothAdapterProperties: Scan Mode:20
,09-07 11:37:42.398  2587  2751 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: BEGIN_DISABLE
09-07 11:37:42.398  5989  5989 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-07 11:37:42.398  1250  2327 V AlarmManager:  remove PendingIntent] PendingIntent{a577fd6: PendingIntentRecord{5b8d257 com.android.bluetooth broadcastIntent}}
09-07 11:37:42.398  5989  5989 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-07 11:37:42.398  3003  3007 I WCNSS_FILTER: do_write: IBS write: fd
09-07 11:37:42.398  2587  2751 E BluetoothServiceJni: disableBrEdrNative:
09-07 11:37:42.398  2587  2751 E bt_bluedroid: disable_bredr
09-07 11:37:42.398  2587  3161 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
09-07 11:37:42.398  2587  2753 E bt_btif : SOCK_LIST: free(id = 1) - NO app_fd!
09-07 11:37:42.398  2587  2753 E bt_btif : BTA_DisableBluetoothOnly
09-07 11:37:42.398  2587  3165 V ObexServerSockets: Accept exception: (expected at shutdown)java.io.IOException: read failed, socket might closed or timeout, read ret: -1
09-07 11:37:42.398  2587  3165 D ObexServerSockets: AcceptThread ended for: ServerSocket: Type: TYPE_L2CAP Channel: 4097
09-07 11:37:42.398  2587  3057 W bt_btif : bta_dm_disable_bt BTA_DISABLE_DELAY set to 200 ms
09-07 11:37:42.398  2587  3057 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-07 11:37:42.398  2587  3164 V ObexServerSockets: Accept exception: (expected at shutdown)java.io.IOException: read failed, socket might closed or timeout, read ret: -1
09-07 11:37:42.398  2587  3164 D ObexServerSockets: AcceptThread ended for: ServerSocket: Type: TYPE_RFCOMM Channel: 4
,09-07 11:37:42.408  3003  3007 I WCNSS_FILTER: Direction(0): bytes: 5 : bytes_written: 5
09-07 11:37:42.408  5843  5843 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1311 android.content.ContextWrapper.startService:606 android.content.ContextWrapper.startService:606 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,09-07 11:37:42.408  3003  3003 I WCNSS_FILTER: do_write: IBS write: fc
,09-07 11:37:42.408  3003  3003 I WCNSS_FILTER: Direction(1): bytes: 7 : bytes_written: 7
09-07 11:37:42.408  3003  3007 I WCNSS_FILTER: Direction(0): bytes: 5 : bytes_written: 5
,09-07 11:37:42.408  3003  3003 I WCNSS_FILTER: Direction(1): bytes: 7 : bytes_written: 7
09-07 11:37:42.408  5989  5989 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-07 11:37:42.408  5989  5989 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-07 11:37:42.408  5989  5989 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-07 11:37:42.408  5989  5989 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-07 11:37:42.408  5989  5989 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-07 11:37:42.408  5989  5989 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-07 11:37:42.408  5989  5989 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-07 11:37:42.408  5989  5989 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-07 11:37:42.408  5989  5989 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-07 11:37:42.408  5989  5989 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-07 11:37:42.408  1250  1313 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=false
09-07 11:37:42.408  5989  5989 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-07 11:37:42.408  3003  3007 I WCNSS_FILTER: Direction(0): bytes: 245 : bytes_written: 245
09-07 11:37:42.408  2587  2753 D IOP_DB_BT: db_close: nbr users 0
09-07 11:37:42.408  2587  2753 D IOP_DB_BT: db_close: free database
09-07 11:37:42.408  1694  2126 D BluetoothTile: handleUpdateState :  supported = true, enabled = false, enabling = false, connected = false, connecting = false, mController.getLastDeviceName() = null
,09-07 11:37:42.408  3003  3003 I WCNSS_FILTER: Direction(1): bytes: 7 : bytes_written: 7
09-07 11:37:42.408  3003  3007 I WCNSS_FILTER: Direction(0): bytes: 245 : bytes_written: 245
09-07 11:37:42.408  5989  5989 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-07 11:37:42.408  5843  5843 D LocalBluetoothManager: LocalBluetoothManager :: sInstance == null
,09-07 11:37:42.418  3003  3003 I WCNSS_FILTER: Direction(1): bytes: 7 : bytes_written: 7
,09-07 11:37:42.418  3003  3007 I WCNSS_FILTER: Direction(0): bytes: 245 : bytes_written: 245
09-07 11:37:42.418  1250  1721 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{8fc87f1 u-1 android.bluetooth.adapter.action.STATE_CHANGED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{573bf46 2626:com.samsung.android.providers.context/u0a5}
09-07 11:37:42.418  5989  5989 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-07 11:37:42.418  2587  3057 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-07 11:37:42.418  3003  3003 I WCNSS_FILTER: Direction(1): bytes: 7 : bytes_written: 7
09-07 11:37:42.418  2587  3057 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-07 11:37:42.418  2587  3057 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-07 11:37:42.418  2587  3057 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-07 11:37:42.418  2587  3057 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-07 11:37:42.418  2587  3057 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-07 11:37:42.418  2587  3057 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-07 11:37:42.418  2587  3057 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-07 11:37:42.418  1250  2327 E BluetoothManagerService: Bluetooth is already disabled. DO NOT disable again.
,09-07 11:37:42.418  3003  3007 I WCNSS_FILTER: Direction(0): bytes: 245 : bytes_written: 245
09-07 11:37:42.418  3003  3003 I WCNSS_FILTER: Direction(1): bytes: 7 : bytes_written: 7
,09-07 11:37:42.418  5843  5843 D LocalBluetoothManager: LocalBluetoothManager :: constructor
,09-07 11:37:42.418  3003  3007 I WCNSS_FILTER: Direction(0): bytes: 245 : bytes_written: 245
09-07 11:37:42.418  5843  5843 D BluetoothEventManager: BluetoothEventManager Constructor :: 
09-07 11:37:42.418  1250  1721 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{8fc87f1 u-1 android.bluetooth.adapter.action.STATE_CHANGED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{ef1b27 1866:com.google.android.gms.persistent/u0a10}
09-07 11:37:42.418  5989  6040 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-07 11:37:42.418  5989  6040 D BluetoothAdapter: enable()
09-07 11:37:42.418  1866  1866 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver bqHint=4 VirtualScreenParam=Params{mDisplayId=-1, null, mFlags=0x00000000)} (has extras) }.
09-07 11:37:42.418  3003  3003 I WCNSS_FILTER: Direction(1): bytes: 7 : bytes_written: 7
,09-07 11:37:42.428  3003  3007 I WCNSS_FILTER: Direction(0): bytes: 245 : bytes_written: 245
09-07 11:37:42.428  2587  2587 D ObexServerSockets: shutdown(block = true)
09-07 11:37:42.428  2587  2587 D ObexServerSockets: shutdown called from another thread - interrupt().
09-07 11:37:42.428  2587  2587 D ObexServerSockets: shutdown called from another thread - interrupt().
09-07 11:37:42.428  2587  2587 D BluetoothSdpJni: sdpRemoveSdpRecordNative:
09-07 11:37:42.428  2587  2587 D BluetoothSdpJni: SDP Remove record success - handle: 0
09-07 11:37:42.428  2587  2587 I BtOppRfcommListener: stopping Accept Thread
09-07 11:37:42.428  2587  3161 I BtOppRfcommListener: BluetoothSocket listen thread finished
,09-07 11:37:42.428  3003  3003 I WCNSS_FILTER: Direction(1): bytes: 7 : bytes_written: 7
,09-07 11:37:42.428  3003  3007 I WCNSS_FILTER: Direction(0): bytes: 245 : bytes_written: 245
09-07 11:37:42.428  5843  5843 D LocalBluetoothProfileManager: LocalBluetoothProfileManager :: uuid is null
09-07 11:37:42.428  1250  1721 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{8fc87f1 u-1 android.bluetooth.adapter.action.STATE_CHANGED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{60a5ff2 5843:com.android.settings/1000}
09-07 11:37:42.428  5843  5843 D LocalBluetoothProfileManager: PANU : true
09-07 11:37:42.428  3003  3003 I WCNSS_FILTER: Direction(1): bytes: 7 : bytes_written: 7
09-07 11:37:42.428  1694  1694 D QSTileView: handleLabelStateChanged() label = Bluetooth cellWidth 148
,09-07 11:37:42.428  3003  3007 I WCNSS_FILTER: Direction(0): bytes: 7 : bytes_written: 7
,09-07 11:37:42.428  3003  3003 I WCNSS_FILTER: Direction(1): bytes: 7 : bytes_written: 7
09-07 11:37:42.438  3003  3007 I WCNSS_FILTER: Direction(0): bytes: 245 : bytes_written: 245
,09-07 11:37:42.438  1250  2010 W ActivityManager: Permission Denial: getCurrentUser() from pid=5989, uid=10136 requires android.permission.INTERACT_ACROSS_USERS
,09-07 11:37:42.438  3003  3003 I WCNSS_FILTER: Direction(1): bytes: 7 : bytes_written: 7
09-07 11:37:42.438  1250  2010 W BluetoothManagerService: Failed getting userId using ActivityManagerNative
09-07 11:37:42.438  1250  2010 W BluetoothManagerService: java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=5989, uid=10136 requires android.permission.INTERACT_ACROSS_USERS
09-07 11:37:42.438  1250  2010 W BluetoothManagerService: 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:28130)
09-07 11:37:42.438  1250  2010 W BluetoothManagerService: 	at com.android.server.BluetoothManagerService.checkItPolicy(BluetoothManagerService.java:2879)
09-07 11:37:42.438  1250  2010 W BluetoothManagerService: 	at com.android.server.BluetoothManagerService.isRestrictedBtPolicy(BluetoothManagerService.java:2869)
09-07 11:37:42.438  1250  2010 W BluetoothManagerService: 	at com.android.server.BluetoothManagerService.setBtEnableFlag(BluetoothManagerService.java:1244)
09-07 11:37:42.438  1250  2010 W BluetoothManagerService: 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:262)
09-07 11:37:42.438  1250  2010 W BluetoothManagerService: 	at android.os.Binder.execTransact(Binder.java:453)
09-07 11:37:42.438  1250  2010 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
09-07 11:37:42.438  3003  3007 I WCNSS_FILTER: Direction(0): bytes: 245 : bytes_written: 245
,09-07 11:37:42.438  5843  5843 D BluetoothSap: Create BluetoothSap proxy object
09-07 11:37:42.438  2587  2587 V BluetoothOppManager: cleanUp...
09-07 11:37:42.438  1250  2010 D SecContentProvider: query(), uri = 3 selection = isBluetoothEnabled
,09-07 11:37:42.438  3003  3003 I WCNSS_FILTER: Direction(1): bytes: 7 : bytes_written: 7
09-07 11:37:42.438  1250  2010 D SettingsProvider: isChangeAllowed() : name = bluetooth_on
,09-07 11:37:42.438  5989  6040 D BluetoothAdapter: BT is in BLE_ON State or TURNING_OFF state
,09-07 11:37:42.438  2587  2751 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: USER_TURN_ON
,09-07 11:37:42.448  5843  5843 D LocalBluetoothProfileManager: LocalBluetoothProfileManager construction complete
09-07 11:37:42.448  5843  5843 D LocalBluetoothManager: LocalBluetoothManager :: onInitCallback != null
09-07 11:37:42.448  2587  2751 I BluetoothAdapterState: Deferring USER_TURN_ON request...
,09-07 11:37:42.448  5843  5843 D DockEventReceiver: finishStartingService: stopping service
,09-07 11:37:42.448  5843  5843 D BluetoothStatusReceiver: Received :: android.bluetooth.adapter.action.STATE_CHANGED
09-07 11:37:42.458  5843  5843 D BluetoothStatusReceiver: AdapterStateChanged :: state = 13
09-07 11:37:42.458  5843  5843 D BluetoothPan: BluetoothPAN Proxy object connected
09-07 11:37:42.458  5843  5843 D PanProfile: Bluetooth service connected
,09-07 11:37:42.458  5843  5843 D BluetoothSap: Proxy object connected
09-07 11:37:42.458  5843  5843 D SapProfile: Bluetooth service connected
,09-07 11:37:42.468  6360  6360 E Zygote  : v2
09-07 11:37:42.468  1250  1721 I ActivityManager: Start proc 6360:com.samsung.android.intelligenceservice2/5010 for broadcast-3 com.samsung.android.intelligenceservice2/com.samsung.android.intelligenceservice.useranalysis.predictor.PlacePredictor$BtConnectionReceiver
09-07 11:37:42.468  6360  6360 I libpersona: KNOX_SDCARD checking this for 5010
09-07 11:37:42.468  6360  6360 I libpersona: KNOX_SDCARD not a persona
,09-07 11:37:42.468  6360  6360 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0013
,09-07 11:37:42.468  6360  6360 E Zygote  : accessInfo : 0
,09-07 11:37:42.468  6360  6360 W SELinux : SELinux: seapp_context_lookup: seinfo=platform, level=s0:c512,c768, pkgname=com.samsung.android.intelligenceservice2 
,09-07 11:37:42.488  6360  6360 D TimaKeyStoreProvider: TimaSignature is unavailable
09-07 11:37:42.488  6360  6360 D ActivityThread: Added TimaKeyStore provider
,09-07 11:37:42.498  1250  2327 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{8fc87f1 u-1 android.bluetooth.adapter.action.STATE_CHANGED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{3aa8374 6360:com.samsung.android.intelligenceservice2/5010}
,09-07 11:37:42.508  6360  6360 W System  : ClassLoader referenced unknown path: /system/priv-app/intelligenceservice2/lib/arm64
,09-07 11:37:42.508  6360  6360 D UserAnalysis.Provider: PlaceProvider onCreate()
,09-07 11:37:42.538  6360  6360 D UserAnalysis.Secu: Key for secure DB is newly created
,09-07 11:37:42.538  6360  6360 D UserAnalysis.SDBH: SecurePlaceDbHelper() 
09-07 11:37:42.538  6360  6360 D UserAnalysis: Create SecureDbHelper
,09-07 11:37:42.548  1250  1313 W ActivityManager: Permission Denial: getCurrentUser() from pid=6360, uid=5010 requires android.permission.INTERACT_ACROSS_USERS
,09-07 11:37:42.558  6360  6360 D UserAnalysis.App: onCreate()
,09-07 11:37:42.558  6360  6360 D UserAnalysis.App: no applications having user consent for prediction
,09-07 11:37:42.558  1250  1310 I ActivityManager: Killing 5826:com.google.android.partnersetup/u0a14 (adj 15): DHA:empty #31
,09-07 11:37:42.558  1250  1310 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{8fc87f1 u-1 android.bluetooth.adapter.action.STATE_CHANGED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{32a7988 2587:com.android.bluetooth/1002}
,09-07 11:37:42.558  6360  6360 V PlaceDetection v1.0.29 : [PlaceDetection::stopService] Service stopped.
,09-07 11:37:42.568  6360  6360 V PlaceDetection v1.0.29 : [PlaceDetectionManager::removeDetectionListener] PlaceDetectionListener removed.
,09-07 11:37:42.578  6373  6373 E Zygote  : v2
09-07 11:37:42.578  6373  6373 I libpersona: KNOX_SDCARD checking this for 10089
09-07 11:37:42.578  6373  6373 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0013
09-07 11:37:42.578  1250  1990 I ActivityManager: Start proc 6373:com.google.android.apps.maps/u0a89 for broadcast-3 com.google.android.apps.maps/com.google.android.apps.gmm.iamhere.ble.StartBleServiceReceiver
09-07 11:37:42.578  6373  6373 E Zygote  : accessInfo : 0
09-07 11:37:42.578  6373  6373 I libpersona: KNOX_SDCARD not a persona
,09-07 11:37:42.578  6373  6373 W SELinux : SELinux: seapp_context_lookup: seinfo=untrusted, level=s0:c512,c768, pkgname=com.google.android.apps.maps 
09-07 11:37:42.578  1250  1964 D ActivityManager: isAutoRunBlockedApp:: com.google.android.partnersetup, Auto Run ON
09-07 11:37:42.578  1250  1964 D ActivityManager: removeProcessNameLocked mProcessNames.remove pid=5826 ,hash=93102675 ,name=com.google.android.partnersetup
,09-07 11:37:42.578  1250  2396 V AlarmManager:  remove PendingIntent] PendingIntent{f47c912: PendingIntentRecord{6c048e3 com.samsung.android.intelligenceservice2 broadcastIntent}}
,09-07 11:37:42.598  6373  6373 D TimaKeyStoreProvider: TimaSignature is unavailable
09-07 11:37:42.598  6373  6373 D ActivityThread: Added TimaKeyStore provider
,09-07 11:37:42.598  1250  2333 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{8fc87f1 u-1 android.bluetooth.adapter.action.STATE_CHANGED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{35f809d 6373:com.google.android.apps.maps/u0a89}
,09-07 11:37:42.598  2587  2756 E BluetoothAdapterState: stateChangeCallback : 16
09-07 11:37:42.598  2587  2751 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: BREDR_NATIVE_STOPED
09-07 11:37:42.598  1250  1310 V AlarmManager:  remove PendingIntent] PendingIntent{8a662e0: PendingIntentRecord{45887f2 com.android.bluetooth broadcastIntent}}
,09-07 11:37:42.608  2587  2751 D BtConfig.SecureMode: isSecureModeOn:false
,09-07 11:37:42.608  2587  2751 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
09-07 11:37:42.608  2587  2751 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
,09-07 11:37:42.608  2587  2587 D HeadsetService: Received stop request...Stopping profile...
09-07 11:37:42.608  2587  2587 E BluetoothAdapterService: onProfileServiceStateChanged() serviceName=com.android.bluetooth.hfp.HeadsetService, state=10, Message sending
09-07 11:37:42.608  2587  2751 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
09-07 11:37:42.608  2587  2587 E HeadsetService: notifyProfileServiceStateChanged
,09-07 11:37:42.608  2587  2587 D A2dpService: Received stop request...Stopping profile...
09-07 11:37:42.608  1694  1694 D HeadsetProfile: Bluetooth service disconnected
,09-07 11:37:42.608  1250  1250 D BluetoothHeadset: unRegisterMessageListener : 11
09-07 11:37:42.608  1250  1250 I Telecom : CallAudioManager: onBluetoothStateChange: no focus
09-07 11:37:42.608  1250  1250 W BluetoothHeadset: Proxy not attached to service
09-07 11:37:42.608  1250  1250 I Telecom : BluetoothManager : unregister MessageListener
09-07 11:37:42.608  2587  2751 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
09-07 11:37:42.608  2587  3138 D A2dpStateMachine: Exit Disconnected: -1
,09-07 11:37:42.608  2587  2587 D Avrcp   : unregisterContentObserver
09-07 11:37:42.608  2587  2587 D Avrcp   : removeOnActiveSessionsChangedListener
09-07 11:37:42.608  2587  2751 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.pan.PanService
09-07 11:37:42.608  2587  2587 E BluetoothAdapterService: onProfileServiceStateChanged() serviceName=com.android.bluetooth.a2dp.A2dpService, state=10, Message sending
09-07 11:37:42.608  2587  2587 E A2dpService: notifyProfileServiceStateChanged
09-07 11:37:42.608  1250  1250 D BluetoothA2dp: Proxy object disconnected
09-07 11:37:42.608  1694  1694 D BluetoothA2dp: Proxy object disconnected
09-07 11:37:42.608  1694  1694 D A2dpProfile: Bluetooth service disconnected
09-07 11:37:42.608  2626  2626 D BluetoothA2dp: Proxy object disconnected
09-07 11:37:42.608  2587  2587 E BluetoothAdapterService: handleMessage() - Message: 1
09-07 11:37:42.608  2587  2587 E BluetoothAdapterService: processProfileServiceStateChanged() serviceName=com.android.bluetooth.hfp.HeadsetService, state=10, Before synchronized
09-07 11:37:42.608  2587  2751 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
,09-07 11:37:42.618  2587  2587 V BluetoothAdapterState: isTurningOff()=true
09-07 11:37:42.618  2587  2587 V BluetoothAdapterState: isTurningOn()=false
09-07 11:37:42.618  2587  2587 V BluetoothAdapterState: isBleTurningOn()=false
09-07 11:37:42.618  2587  2587 V BluetoothAdapterState: isBleTurningOff()=false
,09-07 11:37:42.618  2587  2751 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.sap.SapService
,09-07 11:37:42.618  2587  2751 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfpclient.HeadsetClientService
09-07 11:37:42.618  2587  2751 W BluetoothAdapterService: setProfileServiceState() Profile supported, But not enabled com.android.bluetooth.hfpclient.HeadsetClientService
09-07 11:37:42.618  2587  2751 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpSinkService
09-07 11:37:42.618  2587  2751 W BluetoothAdapterService: setProfileServiceState() Profile supported, But not enabled com.android.bluetooth.a2dp.A2dpSinkService
,09-07 11:37:42.618  6373  6373 W System  : ClassLoader referenced unknown path: /system/app/Maps/lib/arm64
,09-07 11:37:42.618  2587  2587 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
09-07 11:37:42.618  2587  2587 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
09-07 11:37:42.618  2587  2587 D HeadsetProvider: cleanup
09-07 11:37:42.618  2587  2587 I HeadsetProvider: clearAllHeadsetSettings(0)
,09-07 11:37:42.628  2587  2587 D HidService: Received stop request...Stopping profile...
09-07 11:37:42.628  2587  2587 D HidService: Stopping Bluetooth HidService
09-07 11:37:42.628  2587  2587 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
09-07 11:37:42.628  2587  2587 W bt_btif : cleanup: HH disabling or disabled already, status = 0
09-07 11:37:42.628  2587  2587 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
09-07 11:37:42.628  2587  2587 E BluetoothAdapterService: onProfileServiceStateChanged() serviceName=com.android.bluetooth.hid.HidService, state=10, Message sending
09-07 11:37:42.628  2587  2587 E HidService: notifyProfileServiceStateChanged
09-07 11:37:42.628  1694  1694 D BluetoothInputDevice: Proxy object disconnected
09-07 11:37:42.628  1694  1694 D HidProfile: Bluetooth service disconnected
,09-07 11:37:42.628  2587  2587 D HealthService: Received stop request...Stopping profile...
09-07 11:37:42.628  2587  2587 E BluetoothAdapterService: onProfileServiceStateChanged() serviceName=com.android.bluetooth.hdp.HealthService, state=10, Message sending
09-07 11:37:42.628  2587  2587 E HealthService: notifyProfileServiceStateChanged
,09-07 11:37:42.628  2587  2587 E BluetoothAdapterService: handleMessage() - Message: 1
09-07 11:37:42.628  2587  2587 E BluetoothAdapterService: processProfileServiceStateChanged() serviceName=com.android.bluetooth.a2dp.A2dpService, state=10, Before synchronized
09-07 11:37:42.628  2587  2587 V BluetoothAdapterState: isTurningOff()=true
09-07 11:37:42.628  2587  2587 V BluetoothAdapterState: isTurningOn()=false
09-07 11:37:42.628  2587  2587 V BluetoothAdapterState: isBleTurningOn()=false
09-07 11:37:42.628  2587  2587 V BluetoothAdapterState: isBleTurningOff()=false
,09-07 11:37:42.638  2587  2587 D PanService: Received stop request...Stopping profile...
09-07 11:37:42.638  2587  2587 E BluetoothAdapterService: onProfileServiceStateChanged() serviceName=com.android.bluetooth.pan.PanService, state=10, Message sending
09-07 11:37:42.638  2587  2587 E PanService: notifyProfileServiceStateChanged
09-07 11:37:42.638  1250  1250 D BluetoothPan: BluetoothPAN Proxy object disconnected
09-07 11:37:42.638  1694  1694 D BluetoothPan: BluetoothPAN Proxy object disconnected
09-07 11:37:42.638  1694  1694 D PanProfile: Bluetooth service disconnected
09-07 11:37:42.638  5843  5843 D BluetoothPan: BluetoothPAN Proxy object disconnected
09-07 11:37:42.638  5843  5843 D PanProfile: Bluetooth service disconnected
,09-07 11:37:42.638  2587  2587 D BluetoothMapService: Received stop request...Stopping profile...
,09-07 11:37:42.638  2587  2587 E BluetoothAdapterService: onProfileServiceStateChanged() serviceName=com.android.bluetooth.map.BluetoothMapService, state=10, Message sending
09-07 11:37:42.638  2587  2587 E BluetoothMapService: notifyProfileServiceStateChanged
,09-07 11:37:42.638  1250  1720 W ActivityManager: Permission Denial: getCurrentUser() from pid=6373, uid=10089 requires android.permission.INTERACT_ACROSS_USERS
09-07 11:37:42.638  1694  1694 D BluetoothMap: Proxy object disconnected
09-07 11:37:42.638  1694  1694 D MapProfile: Bluetooth service disconnected
09-07 11:37:42.638  2587  2587 D SapService: Received stop request...Stopping profile...
09-07 11:37:42.638  2587  2587 V SapService: stop()
09-07 11:37:42.638  2587  2587 E BluetoothAdapterService: onProfileServiceStateChanged() serviceName=com.android.bluetooth.sap.SapService, state=10, Message sending
09-07 11:37:42.638  2587  2587 E SapService: notifyProfileServiceStateChanged
,09-07 11:37:42.638  5843  5843 D BluetoothSap: Proxy object disconnected
09-07 11:37:42.638  5843  5843 D SapProfile: Bluetooth service disconnected
09-07 11:37:42.638  1694  1694 D BluetoothSap: Proxy object disconnected
09-07 11:37:42.638  1694  1694 D SapProfile: Bluetooth service disconnected
09-07 11:37:42.638  2587  2587 E BluetoothAdapterService: handleMessage() - Message: 1
09-07 11:37:42.638  2587  2587 E BluetoothAdapterService: processProfileServiceStateChanged() serviceName=com.android.bluetooth.hid.HidService, state=10, Before synchronized
,09-07 11:37:42.638  2587  2587 V BluetoothAdapterState: isTurningOff()=true
09-07 11:37:42.638  2587  2587 V BluetoothAdapterState: isTurningOn()=false
09-07 11:37:42.638  2587  2587 V BluetoothAdapterState: isBleTurningOn()=false
09-07 11:37:42.638  2587  2587 V BluetoothAdapterState: isBleTurningOff()=false
09-07 11:37:42.638  2587  2587 D BluetoothAdapterService: HID Host service will be diabled
,09-07 11:37:42.648  2587  2587 D BluetoothUtils: getBtEnabledContainers(): btContainers = []
09-07 11:37:42.648  2587  2587 E BluetoothAdapterService: handleMessage() - Message: 1
09-07 11:37:42.648  2587  2587 E BluetoothAdapterService: processProfileServiceStateChanged() serviceName=com.android.bluetooth.hdp.HealthService, state=10, Before synchronized
,09-07 11:37:42.648  2587  2587 V BluetoothAdapterState: isTurningOff()=true
09-07 11:37:42.648  2587  2587 V BluetoothAdapterState: isTurningOn()=false
09-07 11:37:42.648  2587  2587 V BluetoothAdapterState: isBleTurningOn()=false
09-07 11:37:42.648  2587  2587 V BluetoothAdapterState: isBleTurningOff()=false
09-07 11:37:42.648  2587  2587 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
,09-07 11:37:42.648  2587  2587 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
09-07 11:37:42.648  2587  2587 E BluetoothAdapterService: handleMessage() - Message: 1
09-07 11:37:42.648  2587  2587 E BluetoothAdapterService: processProfileServiceStateChanged() serviceName=com.android.bluetooth.pan.PanService, state=10, Before synchronized
09-07 11:37:42.648  2587  2587 V BluetoothAdapterState: isTurningOff()=true
09-07 11:37:42.648  2587  2587 V BluetoothAdapterState: isTurningOn()=false
09-07 11:37:42.648  2587  2587 V BluetoothAdapterState: isBleTurningOn()=false
09-07 11:37:42.648  2587  2587 V BluetoothAdapterState: isBleTurningOff()=false
09-07 11:37:42.648  2587  2587 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
09-07 11:37:42.648  2587  2587 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
,09-07 11:37:42.648  2587  2587 E BluetoothAdapterService: handleMessage() - Message: 1
09-07 11:37:42.648  2587  2587 E BluetoothAdapterService: processProfileServiceStateChanged() serviceName=com.android.bluetooth.map.BluetoothMapService, state=10, Before synchronized
,09-07 11:37:42.648  2587  2587 V BluetoothAdapterState: isTurningOff()=true
09-07 11:37:42.648  2587  2587 V BluetoothAdapterState: isTurningOn()=false
09-07 11:37:42.648  2587  2587 V BluetoothAdapterState: isBleTurningOn()=false
09-07 11:37:42.648  2587  2587 V BluetoothAdapterState: isBleTurningOff()=false
09-07 11:37:42.648  2587  2587 E BluetoothAdapterService: handleMessage() - Message: 1
09-07 11:37:42.648  2587  2587 E BluetoothAdapterService: processProfileServiceStateChanged() serviceName=com.android.bluetooth.sap.SapService, state=10, Before synchronized
,09-07 11:37:42.648  2587  2587 V BluetoothAdapterState: isTurningOff()=true
09-07 11:37:42.648  2587  2587 V BluetoothAdapterState: isTurningOn()=false
09-07 11:37:42.648  2587  2587 V BluetoothAdapterState: isBleTurningOn()=false
09-07 11:37:42.648  2587  2587 V BluetoothAdapterState: isBleTurningOff()=false
09-07 11:37:42.648  2587  2751 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: BREDR_STOPPED
,09-07 11:37:42.648  2587  2751 D BtGatt.GattService: getGattService(): returning com.android.bluetooth.gatt.GattService@7656711
09-07 11:37:42.648  2587  2751 D BtGatt.GattService: serverDisconnectIncomingConnClients()
09-07 11:37:42.648  2587  2751 D BluetoothAdapterProperties: Setting state to 15
09-07 11:37:42.648  2587  2751 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 15
09-07 11:37:42.648  2587  3057 W bt_btif : BTA got unregistered event id 32
09-07 11:37:42.648  2587  2756 E bt_btif_gatt: btgatts_handle_event: Unknown event (2014)!
,09-07 11:37:42.648  2587  2751 D BluetoothAdapterService: Bluetooth PBAP supproted is true
09-07 11:37:42.648  2587  2751 D BluetoothAdapterService: updateAdapterState state is 15
,09-07 11:37:42.648  2587  2751 D BluetoothAdapterService: Autoconnection is available 
09-07 11:37:42.648  2587  2751 D BluetoothAdapterService: updateAdapterState prevState = 13newState = 15
09-07 11:37:42.648  2587  2751 I BluetoothAdapterState: Entering BleOnState
09-07 11:37:42.648  5843  5854 D BluetoothAdapter: onBluetoothStateChange: up=false
09-07 11:37:42.648  5843  5854 D BluetoothAdapter: Bluetooth is turned off, stop adv
09-07 11:37:42.648  2587  2751 D BluetoothAdapterState: Current state: BLE ON, message: USER_TURN_ON
09-07 11:37:42.658  5843  5854 D BluetoothAdapter: There are no active google scan apps, stop scan
,09-07 11:37:42.658  1250  1416 D BluetoothPan: onBluetoothStateChange on: false
09-07 11:37:42.658  1250  1416 D BluetoothA2dp: onBluetoothStateChange: up=false
09-07 11:37:42.658  2587  2751 D BluetoothAdapterProperties: Setting state to 11
09-07 11:37:42.658  2587  2751 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11
09-07 11:37:42.658  2587  2751 D BluetoothAdapterService: Bluetooth PBAP supproted is true
09-07 11:37:42.658  2587  2751 D BluetoothAdapterService: updateAdapterState state is 11
09-07 11:37:42.658  5843  5853 D BluetoothSap: onBluetoothStateChange: up=false
09-07 11:37:42.658  2587  2751 D BluetoothAdapterService: Autoconnection is available 
09-07 11:37:42.658  2587  2751 D BluetoothAdapterService: updateAdapterState prevState = 15newState = 11
09-07 11:37:42.658  2587  2751 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.hfpclient.HeadsetClientService
09-07 11:37:42.658  2587  2751 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.a2dp.A2dpSinkService
09-07 11:37:42.658  2587  2751 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
09-07 11:37:42.658  1866  2233 D BluetoothAdapter: onBluetoothStateChange: up=false
09-07 11:37:42.658  1866  2233 D BluetoothAdapter: Bluetooth is turned off, stop adv
,09-07 11:37:42.658  1866  2233 D BluetoothAdapter: There are no active google scan apps, stop scan
09-07 11:37:42.658  1694  2998 D BluetoothA2dp: onBluetoothStateChange: up=false
,09-07 11:37:42.658  2587  2751 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
,09-07 11:37:42.658  2587  3153 D BluetoothAdapter: onBluetoothStateChange: up=false
09-07 11:37:42.658  2587  3153 D BluetoothAdapter: Bluetooth is turned off, stop adv
09-07 11:37:42.658  2587  2587 D HeadsetService: Received start request. Starting profile...
09-07 11:37:42.658  2587  2587 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@c11cc52
09-07 11:37:42.658  2587  2587 D HeadsetProvider: make
09-07 11:37:42.658  2587  3153 D BluetoothAdapter: There are no active google scan apps, stop scan
09-07 11:37:42.658  2587  2587 D HeadsetProvider: HeadsetProvider
09-07 11:37:42.658  2587  2587 I HeadsetProvider: clearAllHeadsetSettings(0)
,09-07 11:37:42.658  1694  2371 D BluetoothPbap: onBluetoothStateChange: up=false
09-07 11:37:42.658  2587  2751 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
,09-07 11:37:42.658  5843  5854 D BluetoothPan: onBluetoothStateChange on: false
,09-07 11:37:42.658  2587  2587 D HeadsetStateMachine: make
,09-07 11:37:42.668  2587  2751 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
,09-07 11:37:42.668  1694  1706 D BluetoothInputDevice: onBluetoothStateChange: up=false
09-07 11:37:42.668  2587  2587 E HeadsetStateMachine: # of Max HF connection is 2
,09-07 11:37:42.668  2587  2751 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.pan.PanService
09-07 11:37:42.668  1694  1705 D BluetoothMap: onBluetoothStateChange: up=false
,09-07 11:37:42.668  2587  2751 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
09-07 11:37:42.668  1694  2998 D BluetoothPan: onBluetoothStateChange on: false
,09-07 11:37:42.678  1250  1416 D BluetoothAdapter: onBluetoothStateChange: up=false
09-07 11:37:42.678  1250  1416 D BluetoothAdapter: Bluetooth is turned off, stop adv
09-07 11:37:42.678  2587  2751 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.sap.SapService
09-07 11:37:42.678  1250  1416 D BluetoothAdapter: There are no active google scan apps, stop scan
,09-07 11:37:42.678  1694  1706 D BluetoothAdapter: onBluetoothStateChange: up=false
09-07 11:37:42.678  1694  1706 D BluetoothAdapter: Bluetooth is turned off, stop adv
09-07 11:37:42.678  2587  2587 I bt_bluedroid: get_profile_interface handsfree
,09-07 11:37:42.678  1694  1706 D BluetoothAdapter: There are no active google scan apps, stop scan
09-07 11:37:42.678  2626  2663 D BluetoothAdapter: onBluetoothStateChange: up=false
09-07 11:37:42.678  2626  2663 D BluetoothAdapter: Bluetooth is turned off, stop adv
,09-07 11:37:42.678  2626  2663 D BluetoothAdapter: There are no active google scan apps, stop scan
09-07 11:37:42.678  5989  6000 D BluetoothAdapter: onBluetoothStateChange: up=false
09-07 11:37:42.678  5989  6000 D BluetoothAdapter: Bluetooth is turned off, stop adv
09-07 11:37:42.678  5989  6000 D BluetoothLeAdvertiser: stop All Advertising :: standalone boolean value is = false
09-07 11:37:42.678  5989  6000 D BluetoothLeAdvertiser: Exit stop advertising
,09-07 11:37:42.678  2587  2751 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfpclient.HeadsetClientService
09-07 11:37:42.678  2587  2751 W BluetoothAdapterService: setProfileServiceState() Profile supported, But not enabled com.android.bluetooth.hfpclient.HeadsetClientService
09-07 11:37:42.678  2587  2751 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpSinkService
09-07 11:37:42.678  2587  2751 W BluetoothAdapterService: setProfileServiceState() Profile supported, But not enabled com.android.bluetooth.a2dp.A2dpSinkService
09-07 11:37:42.678  2587  2751 I BluetoothAdapterState: Entering PendingCommandState
,09-07 11:37:42.678  5989  6000 D BluetoothAdapter: There are no active google scan apps, stop scan
09-07 11:37:42.678  5989  6000 D BluetoothLeScanner: stopAllScan standalone boolean is value is = false
09-07 11:37:42.678  5989  6000 D BluetoothLeScanner: Exiting stopAllScan
,09-07 11:37:42.678  1694  1705 D BluetoothSap: onBluetoothStateChange: up=false
,09-07 11:37:42.678  1944  1963 D BluetoothAdapter: onBluetoothStateChange: up=false
09-07 11:37:42.678  1944  1963 D BluetoothAdapter: Bluetooth is turned off, stop adv
09-07 11:37:42.678  2587  2587 E DualScoManager: Dual Sco Manager already instantiated
09-07 11:37:42.678  2587  2587 I DualScoManager: Set HeadsetServiceHelper
09-07 11:37:42.678  2587  2587 D BluetoothAtMessage: createCMTIContentObservers
09-07 11:37:42.678  1944  1963 D BluetoothAdapter: There are no active google scan apps, stop scan
09-07 11:37:42.678  2626  2649 D BluetoothA2dp: onBluetoothStateChange: up=false
,09-07 11:37:42.688  2587  2751 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: USER_TURN_OFF
,09-07 11:37:42.688  1250  1416 D BluetoothManagerService: Turning On/Off, G state: 3, S state: 3, mBLE count: 0, s BLE count: 0
09-07 11:37:42.688  2587  2751 I BluetoothAdapterState: Deferring USER_TURN_OFF request...
09-07 11:37:42.688  1250  1250 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
09-07 11:37:42.688  1250  1250 I InputMethodManagerService: [BT Setting State] State =10
09-07 11:37:42.688  1250  1250 I InputMethodManagerService: [BT Setting on -> off] mBTKeyboardCount =0, KEYBOARD_BT(0)
,09-07 11:37:42.688  2040  2040 D ucsBai_ConnectionManager: BluetoothReceiver Action android.bluetooth.adapter.action.STATE_CHANGED
,09-07 11:37:42.688  1250  1250 D BluetoothPhoneService: Bluetooth Adapter state : 10
,09-07 11:37:42.688  2587  2587 D HeadsetProvider: Created cursor android.database.sqlite.SQLiteCursor@478d21a
09-07 11:37:42.688  1694  2100 V BluetoothEventManager: onReceive :: android.bluetooth.adapter.action.STATE_CHANGED
09-07 11:37:42.688  1694  2100 D BluetoothEventManager: AdapterStateChangedHandler :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 10
09-07 11:37:42.688  2587  2587 D HeadsetProvider: setHeadsetDB - Can't find 300 for 44:78:3E:EB:95:XX
,09-07 11:37:42.688  1250  1250 D KnoxKeyguardUpdateMonitor: BroadcastReceiver onReceive
09-07 11:37:42.688  1250  1250 D KnoxKeyguardUpdateMonitor: BroadcastReceiver onReceive action: android.bluetooth.adapter.action.STATE_CHANGED
09-07 11:37:42.688  1250  1250 D KnoxKeyguardUpdateMonitor: BroadcastReceiver onReceive BT state is changed
,09-07 11:37:42.688  5843  5843 V BluetoothEventManager: onReceive :: android.bluetooth.adapter.action.STATE_CHANGED
,09-07 11:37:42.698  5989  5989 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-07 11:37:42.698  1250  2333 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=false
09-07 11:37:42.698  5843  5843 D BluetoothEventManager: AdapterStateChangedHandler :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 10
09-07 11:37:42.698  1694  2126 D BluetoothTile: handleUpdateState :  supported = true, enabled = false, enabling = false, connected = false, connecting = false, mController.getLastDeviceName() = null
,09-07 11:37:42.698  5989  5989 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-07 11:37:42.698  2040  2040 D ucsBai_ConnectionManager: BluetoothReceiver Action android.bluetooth.adapter.action.STATE_CHANGED
,09-07 11:37:42.698  2587  2587 I HeadsetProvider: setHeadsetDB - 44:78:3E:EB:95:XX, 300, 0, true
09-07 11:37:42.698  1694  2100 V BluetoothEventManager: onReceive :: android.bluetooth.adapter.action.STATE_CHANGED
,09-07 11:37:42.698  1694  2100 D BluetoothEventManager: AdapterStateChangedHandler :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 11
,09-07 11:37:42.698  1250  1250 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
09-07 11:37:42.698  1250  1250 D BluetoothPhoneService: Bluetooth Adapter state : 11
09-07 11:37:42.698  1250  1250 I InputMethodManagerService: [BT Setting State] State =11
09-07 11:37:42.698  1250  1250 D KnoxKeyguardUpdateMonitor: BroadcastReceiver onReceive
09-07 11:37:42.698  1250  1250 D KnoxKeyguardUpdateMonitor: BroadcastReceiver onReceive action: android.bluetooth.adapter.action.STATE_CHANGED
09-07 11:37:42.698  1250  1250 D KnoxKeyguardUpdateMonitor: BroadcastReceiver onReceive BT state is changed
,09-07 11:37:42.698  5989  5989 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-07 11:37:42.698  5989  5989 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-07 11:37:42.708  1694  2126 D BluetoothTile: handleUpdateState :  supported = true, enabled = false, enabling = true, connected = false, connecting = false, mController.getLastDeviceName() = null
09-07 11:37:42.708  1250  1310 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=false
,09-07 11:37:42.708  1694  1694 D QSTileView: handleLabelStateChanged() label = Bluetooth cellWidth 148
,09-07 11:37:42.708  5843  5843 V BluetoothEventManager: onReceive :: android.bluetooth.adapter.action.STATE_CHANGED
09-07 11:37:42.708  5843  5843 D BluetoothEventManager: AdapterStateChangedHandler :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 11
,09-07 11:37:42.708  2587  2587 D HeadsetProvider: Created cursor android.database.sqlite.SQLiteCursor@16dcc41
,09-07 11:37:42.708  2587  2587 D HeadsetProvider: setHeadsetDB - Can't find 400 for 44:78:3E:EB:95:XX
,09-07 11:37:42.718  2587  2587 I HeadsetProvider: setHeadsetDB - 44:78:3E:EB:95:XX, 400, 1, true
,09-07 11:37:42.718  2587  6385 D HeadsetStateMachine: Enter Disconnected: -2, size: 0/0
,09-07 11:37:42.718  2587  2587 E BluetoothAdapterService: onProfileServiceStateChanged() serviceName=com.android.bluetooth.hfp.HeadsetService, state=12, Message sending
09-07 11:37:42.718  2587  2587 E HeadsetService: notifyProfileServiceStateChanged
,09-07 11:37:42.718  2587  2587 D A2dpService: Received start request. Starting profile...
09-07 11:37:42.718  2587  2587 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@c11cc52
09-07 11:37:42.718  2587  2587 I bt_bluedroid: get_profile_interface avrcp
09-07 11:37:42.718  2587  6385 D HeadsetStateMachine: Clear mHeadsetBrsf
09-07 11:37:42.718  2587  6385 D HeadsetStateMachine: map size, before remove : 0
09-07 11:37:42.718  2587  6385 D HeadsetStateMachine: map size, after remove: 0
,09-07 11:37:42.718  2587  2587 I Avrcp   : No of Audio players :: 1
09-07 11:37:42.718  2587  2587 I Avrcp   : App Package name is GM
,09-07 11:37:42.718  2587  2587 V Avrcp   : MediaPlayerInfo: mPlayerId=1
,09-07 11:37:42.728  2587  2587 I Avrcp   : No of Video players :: 2
09-07 11:37:42.728  2587  2587 I Avrcp   : Video App Package name is others
,09-07 11:37:42.728  2587  2587 V Avrcp   : MediaPlayerInfo: mPlayerId=2
09-07 11:37:42.728  2587  2587 I Avrcp   : Video App Package name is VP
09-07 11:37:42.728  2587  2587 V Avrcp   : MediaPlayerInfo: mPlayerId=3
09-07 11:37:42.728  2587  2587 I Avrcp   : Add tempPlayer
09-07 11:37:42.728  2587  2587 V Avrcp   : MediaPlayerInfo: mPlayerId=4
09-07 11:37:42.728  2587  2587 V Avrcp   : no_of_players : 4
09-07 11:37:42.728  2587  2587 I Avrcp   : Total no of players: 4
09-07 11:37:42.728  2587  2587 V Avrcp   : Samsung player is the 1st player
09-07 11:37:42.728  2587  2587 D Avrcp   : Compose Browsing Service Candidate
,09-07 11:37:42.728  2587  2587 D Avrcp   : ResolveInfo info ResolveInfo{6278a72 com.google.android.music/.browse.MediaBrowserService m=0x108000}
09-07 11:37:42.728  2587  2587 D Avrcp   : Initialize Media Controller
,09-07 11:37:42.728  2587  2587 D Avrcp   : Get the Context Package Name: com.android.bluetooth
,09-07 11:37:42.728  2587  2587 E Avrcp   : getActiveSessions
09-07 11:37:42.728  2587  2587 D Avrcp   : pick active media Controller
09-07 11:37:42.728  2587  2587 D Avrcp   : Get the active Media Controller 
09-07 11:37:42.728  2587  2587 D A2dpStateMachine: make
,09-07 11:37:42.728  2587  2587 I bt_bluedroid: get_profile_interface a2dp
09-07 11:37:42.728  2587  2587 E bt_btif : ### uipc_main_init ###
09-07 11:37:42.728  2587  2587 E bt_btif : warning : no command pending, ignore ack
,09-07 11:37:42.738  2587  6394 D A2dpStateMachine: Enter Disconnected: -2
,09-07 11:37:42.738  2587  2587 E BluetoothAdapterService: onProfileServiceStateChanged() serviceName=com.android.bluetooth.a2dp.A2dpService, state=12, Message sending
09-07 11:37:42.738  2587  2587 E A2dpService: notifyProfileServiceStateChanged
,09-07 11:37:42.738  2587  2587 D HidService: Received start request. Starting profile...
09-07 11:37:42.738  2587  2587 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@c11cc52
09-07 11:37:42.738  2587  2587 I bt_bluedroid: get_profile_interface hidhost
09-07 11:37:42.738  2587  2587 D HidService: setHidService(): set to: null
09-07 11:37:42.738  2587  2587 E BluetoothAdapterService: onProfileServiceStateChanged() serviceName=com.android.bluetooth.hid.HidService, state=12, Message sending
09-07 11:37:42.738  2587  2587 E HidService: notifyProfileServiceStateChanged
,09-07 11:37:42.738  6373  6388 W System.err: mkdir failed: EEXIST (File exists) : /storage/emulated/0/Android/data/com.google.android.apps.maps/testdata
,09-07 11:37:42.738  6373  6388 W System.err: mkdir failed: EEXIST (File exists) : /data/user/0/com.google.android.apps.maps/app_/testdata
,09-07 11:37:42.738  2587  2587 D HealthService: Received start request. Starting profile...
09-07 11:37:42.738  2587  2587 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@c11cc52
09-07 11:37:42.748  2587  2587 I bt_bluedroid: get_profile_interface health
09-07 11:37:42.748  2587  2587 E BluetoothAdapterService: onProfileServiceStateChanged() serviceName=com.android.bluetooth.hdp.HealthService, state=12, Message sending
09-07 11:37:42.748  2587  2587 E HealthService: notifyProfileServiceStateChanged
,09-07 11:37:42.748  2587  2587 D PanService: Received start request. Starting profile...
09-07 11:37:42.748  2587  2587 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@c11cc52
09-07 11:37:42.748  2587  2587 D BluetoothPanServiceJni: initializeNative(L118): pan
09-07 11:37:42.748  2587  2587 I bt_bluedroid: get_profile_interface pan
09-07 11:37:42.748  2587  2587 E BluetoothAdapterService: onProfileServiceStateChanged() serviceName=com.android.bluetooth.pan.PanService, state=12, Message sending
09-07 11:37:42.748  2587  2587 E PanService: notifyProfileServiceStateChanged
,09-07 11:37:42.748  2587  2587 D HeadsetStateMachine: Try to query the phonestate on bind
09-07 11:37:42.748  1250  1986 I BluetoothPhoneService: queryPhoneState
09-07 11:37:42.748  1250  1986 I BluetoothPhoneService: updateHeadsetWithCallState : true
,09-07 11:37:42.748  2587  2587 D BluetoothMapService: Received start request. Starting profile...
09-07 11:37:42.748  2587  2587 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@c11cc52
,09-07 11:37:42.748  6373  6388 W System.err: mkdir failed: EEXIST (File exists) : /storage/emulated/0/Android/data/com.google.android.apps.maps/cache
,09-07 11:37:42.748  2587  2587 E BluetoothAdapterService: onProfileServiceStateChanged() serviceName=com.android.bluetooth.map.BluetoothMapService, state=12, Message sending
09-07 11:37:42.748  2587  2587 E BluetoothMapService: notifyProfileServiceStateChanged
09-07 11:37:42.748  2587  2587 D HeadsetStateMachine: Proxy object connected
,09-07 11:37:42.748  2587  2587 V SapService: SapBinder()
09-07 11:37:42.748  2587  2587 D SapService: Received start request. Starting profile...
09-07 11:37:42.748  2587  2587 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@c11cc52
09-07 11:37:42.748  2587  2587 V SapService: start()
09-07 11:37:42.748  2587  2587 V SapService: SAP UUID disabled
09-07 11:37:42.748  2587  2587 E BluetoothAdapterService: onProfileServiceStateChanged() serviceName=com.android.bluetooth.sap.SapService, state=12, Message sending
09-07 11:37:42.748  2587  2587 E SapService: notifyProfileServiceStateChanged
09-07 11:37:42.748  2587  2587 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=0
09-07 11:37:42.748  2587  2587 D HeadsetPhoneState: sendDeviceDataStateChanged
,09-07 11:37:42.748  2587  2587 D HeadsetPhoneState: Signal level : previous=0 curr=0
09-07 11:37:42.748  2587  2587 E BluetoothAdapterService: handleMessage() - Message: 1
09-07 11:37:42.748  2587  2587 E BluetoothAdapterService: processProfileServiceStateChanged() serviceName=com.android.bluetooth.hfp.HeadsetService, state=12, Before synchronized
09-07 11:37:42.748  2587  6385 D HeadsetStateMachine: Disconnected process message: 11, size: 0
09-07 11:37:42.748  2587  6385 E HeadsetStateMachine: Unknown message: 11
09-07 11:37:42.748  2587  6385 D HeadsetStateMachine: Disconnected process message: 19, size: 0
09-07 11:37:42.748  2587  6385 E HeadsetStateMachine: Unknown message: 19
09-07 11:37:42.758  2587  2587 V BluetoothAdapterState: isTurningOff()=false
09-07 11:37:42.758  2587  2587 V BluetoothAdapterState: isTurningOn()=true
09-07 11:37:42.758  2587  2587 V BluetoothAdapterState: isBleTurningOn()=false
09-07 11:37:42.758  2587  2587 V BluetoothAdapterState: isBleTurningOff()=false
09-07 11:37:42.758  2587  2587 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
09-07 11:37:42.758  2587  2587 E BluetoothAdapterService: handleMessage() - Message: 1
09-07 11:37:42.758  2587  2587 E BluetoothAdapterService: processProfileServiceStateChanged() serviceName=com.android.bluetooth.a2dp.A2dpService, state=12, Before synchronized
09-07 11:37:42.758  2587  6385 D HeadsetStateMachine: Disconnected process message: 10, size: 0
09-07 11:37:42.758  2587  6385 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
09-07 11:37:42.758  2587  6385 D HeadsetStateMachine: Disconnected process message: 11, size: 0
09-07 11:37:42.758  2587  6385 E HeadsetStateMachine: Unknown message: 11
09-07 11:37:42.758  2587  2587 V BluetoothAdapterState: isTurningOff()=false
09-07 11:37:42.758  2587  2587 V BluetoothAdapterState: isTurningOn()=true
09-07 11:37:42.758  2587  2587 V BluetoothAdapterState: isBleTurningOn()=false
09-07 11:37:42.758  2587  2587 V BluetoothAdapterState: isBleTurningOff()=false
09-07 11:37:42.758  2587  2587 E BluetoothAdapterService: handleMessage() - Message: 1
09-07 11:37:42.758  2587  2587 E BluetoothAdapterService: processProfileServiceStateChanged() serviceName=com.android.bluetooth.hid.HidService, state=12, Before synchronized
,09-07 11:37:42.758  2587  2587 V BluetoothAdapterState: isTurningOff()=false
09-07 11:37:42.758  2587  2587 V BluetoothAdapterState: isTurningOn()=true
09-07 11:37:42.758  2587  2587 V BluetoothAdapterState: isBleTurningOn()=false
09-07 11:37:42.758  2587  2587 V BluetoothAdapterState: isBleTurningOff()=false
09-07 11:37:42.758  2587  2587 D BluetoothAdapterService: HID Host service started
,09-07 11:37:42.758  2587  2587 D BluetoothUtils: getBtEnabledContainers(): btContainers = []
09-07 11:37:42.758  2587  2587 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
09-07 11:37:42.758  1694  2100 V BluetoothEventManager: onReceive :: android.bluetooth.device.action.CONNECTION_HID_HOST
09-07 11:37:42.758  2587  2587 D HeadsetPhoneState: sendDeviceDataStateChanged
09-07 11:37:42.758  1694  2100 W LocalBluetoothProfileManager: updateLocalProfiles :: A2DP profile was previously added but the UUID is now missing.
09-07 11:37:42.758  1694  2100 W LocalBluetoothProfileManager: updateLocalProfiles :: HEADSET profile was previously added but the UUID is now missing.
09-07 11:37:42.758  1694  2100 W LocalBluetoothProfileManager: updateLocalProfiles :: MAP profile was previously added but the UUID is now missing.
09-07 11:37:42.758  1694  2100 W LocalBluetoothProfileManager: updateLocalProfiles :: PBAP profile was previously added but the UUID is now missing.
09-07 11:37:42.758  1694  2100 W LocalBluetoothProfileManager: updateLocalProfiles :: SAP profile was previously added but the UUID is now missing.
09-07 11:37:42.758  1694  2100 D HidProfile: mService is null. need to get proxy again!!
09-07 11:37:42.758  2587  2587 D HeadsetPhoneState: Signal level : previous=0 curr=0
09-07 11:37:42.758  2587  2587 E BluetoothAdapterService: handleMessage() - Message: 1
09-07 11:37:42.758  2587  2587 E BluetoothAdapterService: processProfileServiceStateChanged() serviceName=com.android.bluetooth.hdp.HealthService, state=12, Before synchronized
09-07 11:37:42.758  2587  6385 D HeadsetStateMachine: Disconnected process message: 11, size: 0
09-07 11:37:42.758  2587  6385 E HeadsetStateMachine: Unknown message: 11
09-07 11:37:42.758  2587  6385 D HeadsetStateMachine: Disconnected process message: 19, size: 0
09-07 11:37:42.758  2587  6385 E HeadsetStateMachine: Unknown message: 19
09-07 11:37:42.758  2587  2587 V BluetoothAdapterState: isTurningOff()=false
09-07 11:37:42.758  2587  2587 V BluetoothAdapterState: isTurningOn()=true
09-07 11:37:42.758  2587  2587 V BluetoothAdapterState: isBleTurningOn()=false
09-07 11:37:42.758  2587  2587 V BluetoothAdapterState: isBleTurningOff()=false
09-07 11:37:42.758  2587  2587 E BluetoothAdapterService: handleMessage() - Message: 1
09-07 11:37:42.758  2587  2587 E BluetoothAdapterService: processProfileServiceStateChanged() serviceName=com.android.bluetooth.pan.PanService, state=12, Before synchronized
09-07 11:37:42.758  2587  2587 V BluetoothAdapterState: isTurningOff()=false
09-07 11:37:42.758  2587  2587 V BluetoothAdapterState: isTurningOn()=true
09-07 11:37:42.758  2587  2587 V BluetoothAdapterState: isBleTurningOn()=false
09-07 11:37:42.758  2587  2587 V BluetoothAdapterState: isBleTurningOff()=false
09-07 11:37:42.758  2587  2587 E BluetoothAdapterService: handleMessage() - Message: 1
09-07 11:37:42.758  2587  2587 E BluetoothAdapterService: processProfileServiceStateChanged() serviceName=com.android.bluetooth.map.BluetoothMapService, state=12, Before synchronized
,09-07 11:37:42.758  2587  2587 V BluetoothAdapterState: isTurningOff()=false
09-07 11:37:42.758  2587  2587 V BluetoothAdapterState: isTurningOn()=true
09-07 11:37:42.758  2587  2587 V BluetoothAdapterState: isBleTurningOn()=false
09-07 11:37:42.758  2587  2587 V BluetoothAdapterState: isBleTurningOff()=false
09-07 11:37:42.758  2587  2587 E BluetoothAdapterService: handleMessage() - Message: 1
09-07 11:37:42.758  2587  2587 E BluetoothAdapterService: processProfileServiceStateChanged() serviceName=com.android.bluetooth.sap.SapService, state=12, Before synchronized
09-07 11:37:42.758  5843  5843 V BluetoothEventManager: onReceive :: android.bluetooth.device.action.CONNECTION_HID_HOST
09-07 11:37:42.758  2587  2587 V BluetoothAdapterState: isTurningOff()=false
09-07 11:37:42.758  2587  2587 V BluetoothAdapterState: isTurningOn()=true
09-07 11:37:42.758  2587  2587 V BluetoothAdapterState: isBleTurningOn()=false
09-07 11:37:42.758  2587  2587 V BluetoothAdapterState: isBleTurningOff()=false
09-07 11:37:42.758  2587  2751 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: BREDR_STARTED
,09-07 11:37:42.758  5843  5843 D BluetoothMap: Create BluetoothMap proxy object
,09-07 11:37:42.758  2587  2751 E BluetoothServiceJni: enableBrEdrNative:
09-07 11:37:42.758  2587  2751 I bt_bluedroid: enable_bredr
,09-07 11:37:42.768  1694  1694 D BluetoothInputDevice: Proxy object connected
09-07 11:37:42.768  1694  1694 D HidProfile: Bluetooth service connected
09-07 11:37:42.768  2587  2756 I bt_bta_hh: BTA_HhEnable sec_mask:0x24 p_cback:0xf39a0ca9
09-07 11:37:42.768  2587  2756 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x100048
09-07 11:37:42.768  2587  2756 D BluetoothAdapterProperties: Address is:44:78:3E:EB:95:EE
09-07 11:37:42.768  2587  2756 E BluetoothServiceJni: populateRssiValuesNative
09-07 11:37:42.768  2587  2756 I bt_bluedroid: getModelRssiValues
09-07 11:37:42.768  2587  2756 E BluetoothServiceJni: model_rssi_values_callback: low = -70, mid = -60, high = 127
09-07 11:37:42.768  2587  2756 D BluetoothAdapterProperties: modelRssiValuesCallback, low, mid, high = -70,-60,127
09-07 11:37:42.768  2587  3057 D CODEC_IF: codec_if_open: opening libbt-codec_aptx.so...
09-07 11:37:42.768  2587  3057 D CODEC_IF_MOD: codec_open: codec_open
09-07 11:37:42.768  2587  3057 D CODEC_IF_MOD: codec_open: apt-x encoder initialized successfully
09-07 11:37:42.768  2587  3057 D CODEC_IF_MOD: codec_open:    version : 1.0.1.0
09-07 11:37:42.768  2587  3057 D CODEC_IF_MOD: codec_open:    build : Android_JB_4.2.2
09-07 11:37:42.768  2587  3057 D CODEC_IF: codec_if_open: codec module opened (v0.1
09-07 11:37:42.768  2587  3057 D CODEC_IF: codec_if_close: codec_if_close hdl -284184572
09-07 11:37:42.768  2587  3057 D CODEC_IF_MOD: codec_close: codec_close
09-07 11:37:42.768  2587  3057 D CODEC_IF_MOD: codec_close: freed apt-x encoder
09-07 11:37:42.768  2587  3057 D         : Codec ==> check 44.1kHz mode : check_sshd_encoder_available:356
09-07 11:37:42.768  2587  3057 D CODEC_IF: codec_if_open: opening libbt-codec_sshd.so...
09-07 11:37:42.768  2587  3057 D CODEC_IF_SSHD: codec_open: codec_open
09-07 11:37:42.768  2587  3057 D CODEC_IF_SSHD: Codec ==> pcm_info.sampling_freq : 44100
09-07 11:37:42.768  2587  3057 D CODEC_IF_SSHD: codec_open: SSHD encoder initialized successfully
09-07 11:37:42.768  2587  3057 D CODEC_IF: codec_if_open: codec module opened (v0.1
09-07 11:37:42.768  2587  3057 D CODEC_IF: codec_if_close: codec_if_close hdl -568828544
09-07 11:37:42.768  2587  3057 D CODEC_IF_SSHD: codec_close: codec_close
09-07 11:37:42.768  2587  3057 D         : Codec ==> check 44.1kHz mode : check_sshd_encoder_available:356
09-07 11:37:42.768  2587  3057 D CODEC_IF: codec_if_open: opening libbt-codec_sshd.so...
09-07 11:37:42.768  2587  3057 D CODEC_IF_SSHD: codec_open: codec_open
09-07 11:37:42.768  2587  3057 D CODEC_IF_SSHD: Codec ==> pcm_info.sampling_freq : 44100
09-07 11:37:42.768  2587  3057 D CODEC_IF_SSHD: codec_open: SSHD encoder initialized successfully
09-07 11:37:42.768  2587  3057 D CODEC_IF: codec_if_open: codec module opened (v0.1
09-07 11:37:42.768  2587  3057 D CODEC_IF: codec_if_close: codec_if_close hdl -568828544
09-07 11:37:42.768  2587  3057 D CODEC_IF_SSHD: codec_close: codec_close
09-07 11:37:42.768  2587  3057 D         : Codec ==> copy capability info [bta_av_co_audio_init:646]
09-07 11:37:42.768  2587  2756 D BluetoothAdapterProperties: Name is: Galaxy Tab S2
,09-07 11:37:42.768  1250  1250 D SettingsProvider: isChangeAllowed() : name = bluetooth_name
09-07 11:37:42.778  5843  5843 W LocalBluetoothProfileManager: updateLocalProfiles :: SAP profile was previously added but the UUID is now missing.
09-07 11:37:42.778  3003  3007 I WCNSS_FILTER: Direction(0): bytes: 245 : bytes_written: 245
09-07 11:37:42.778  1250  1986 V AlarmManager:  remove PendingIntent] PendingIntent{eaf1a1f: PendingIntentRecord{45887f2 com.android.bluetooth broadcastIntent}}
,09-07 11:37:42.778  3003  3003 I WCNSS_FILTER: do_write: IBS write: fc
09-07 11:37:42.778  2587  2756 D BluetoothUtils: getBtEnabledContainers(): btContainers = []
09-07 11:37:42.778  2587  2756 D BluetoothAdapterProperties: Scan Mode:20
09-07 11:37:42.778  2587  2756 D BluetoothAdapterProperties: Discoverable Timeout:120
09-07 11:37:42.778  2587  2756 E bt_btif : btif_handle_bluetooth_enable_evt
09-07 11:37:42.778  2587  2756 E bt_btif : JVenable fails
,09-07 11:37:42.778  2587  2756 D IOP_DB_BT: db_open: file /etc/bluetooth/iop_bt.db
09-07 11:37:42.778  2587  2756 D IOP_DB_BT: db_open: db_open : handle 4086550544l, read 18559 bytes onto local cache
09-07 11:37:42.778  2587  2756 D IOP_DB_BT: db_query: id __IOPFLAGS :: key __KEY_ENABLE_VERBOSE, value 1
,09-07 11:37:42.778  2587  2756 D IOP_DB_BT: db_query: result 1
09-07 11:37:42.778  2587  2756 I         : iop_db_open: iop_db_open status 0
09-07 11:37:42.778  2587  2756 E BluetoothAdapterState: stateChangeCallback : 17
09-07 11:37:42.778  2587  2756 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
09-07 11:37:42.778  5989  5989 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-07 11:37:42.778  2587  2751 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: BREDR_NATIVE_STARTED
,09-07 11:37:42.778  2587  2751 D BluetoothAdapterProperties: ScanMode =  20
09-07 11:37:42.778  2587  2751 D BluetoothAdapterProperties: State =  11
09-07 11:37:42.778  3003  3003 I WCNSS_FILTER: Direction(1): bytes: 7 : bytes_written: 7
,09-07 11:37:42.778  1250  2010 D SecContentProvider: query(), uri = 3 selection = isDiscoverableEnabled
,09-07 11:37:42.788  3003  3007 I WCNSS_FILTER: Direction(0): bytes: 7 : bytes_written: 7
09-07 11:37:42.788  1250  2674 D SecContentProvider: insert(), uri = 2
,09-07 11:37:42.788  3003  3003 I WCNSS_FILTER: Direction(1): bytes: 7 : bytes_written: 7
09-07 11:37:42.788  3003  3007 I WCNSS_FILTER: Direction(0): bytes: 245 : bytes_written: 245
,09-07 11:37:42.788  3003  3003 I WCNSS_FILTER: Direction(1): bytes: 7 : bytes_written: 7
,09-07 11:37:42.788  2587  2751 D BluetoothAdapterProperties: Setting state to 12
09-07 11:37:42.788  2587  2751 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
09-07 11:37:42.788  2587  2751 D BluetoothAdapterService: Bluetooth PBAP supproted is true
09-07 11:37:42.788  2587  2751 D BluetoothAdapterService: updateAdapterState state is 12
09-07 11:37:42.788  3003  3007 I WCNSS_FILTER: Direction(0): bytes: 6 : bytes_written: 6
,09-07 11:37:42.788  3003  3003 I WCNSS_FILTER: Direction(1): bytes: 7 : bytes_written: 7
,09-07 11:37:42.788  3003  3007 I WCNSS_FILTER: Direction(0): bytes: 245 : bytes_written: 245
,09-07 11:37:42.788  2587  2751 V BluetoothAdapterService: start opp service
09-07 11:37:42.788  5989  5989 D BluetoothAdapter: STATE_ON
09-07 11:37:42.788  3003  3003 I WCNSS_FILTER: Direction(1): bytes: 7 : bytes_written: 7
,09-07 11:37:42.798  2587  2756 D BluetoothUtils: getBtEnabledContainers(): btContainers = []
09-07 11:37:42.798  2587  2756 D BluetoothAdapterProperties: Scan Mode:21
09-07 11:37:42.798  2587  2756 D BluetoothAdapterProperties: Discoverable Timeout:120
,09-07 11:37:42.798  3003  3007 I WCNSS_FILTER: Direction(0): bytes: 245 : bytes_written: 245
09-07 11:37:42.798  5989  5989 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-07 11:37:42.798  5989  5989 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-07 11:37:42.798  5989  5989 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-07 11:37:42.798  5989  5989 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-07 11:37:42.798  5989  5989 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-07 11:37:42.798  5989  5989 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-07 11:37:42.798  5989  5989 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-07 11:37:42.798  5989  5989 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-07 11:37:42.798  5989  5989 D BluetoothAdapter: STATE_ON
09-07 11:37:42.798  3003  3003 I WCNSS_FILTER: Direction(1): bytes: 7 : bytes_written: 7
09-07 11:37:42.798  2587  2751 D BluetoothAdapterService: Autoconnection is available 
09-07 11:37:42.798  5843  5854 D BluetoothAdapter: onBluetoothStateChange: up=true
09-07 11:37:42.798  1250  1310 V AlarmManager:  remove PendingIntent] PendingIntent{afbf296: PendingIntentRecord{45887f2 com.android.bluetooth broadcastIntent}}
09-07 11:37:42.798  5843  5854 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
09-07 11:37:42.798  2587  2751 D BluetoothAdapterService: updateAdapterState prevState = 11newState = 12
09-07 11:37:42.798  5843  5843 D BluetoothMap: Proxy object connected
09-07 11:37:42.798  2587  2751 D BluetoothAdapterService: starting service from this receiver
09-07 11:37:42.798  3003  3007 I WCNSS_FILTER: Direction(0): bytes: 8 : bytes_written: 8
,09-07 11:37:42.798  3003  3003 I WCNSS_FILTER: Direction(1): bytes: 7 : bytes_written: 7
,09-07 11:37:42.798  1250  1416 D BluetoothPan: onBluetoothStateChange on: true
09-07 11:37:42.798  1250  1416 D BluetoothPan: onBluetoothStateChange calling doBind()
09-07 11:37:42.808  3003  3007 I WCNSS_FILTER: Direction(0): bytes: 5 : bytes_written: 5
,09-07 11:37:42.808  5989  5989 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-07 11:37:42.808  2587  2587 I BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED, state: 12
09-07 11:37:42.808  2587  2751 D BluetoothAdapterService: BT on, init HID DEV count : 0
09-07 11:37:42.808  2587  2751 I BluetoothAdapterState: Entering OnState
09-07 11:37:42.808  3003  3003 I WCNSS_FILTER: Direction(1): bytes: 7 : bytes_written: 7
09-07 11:37:42.808  5843  5843 D MapProfile: Bluetooth service connected
09-07 11:37:42.808  5843  5843 D BluetoothMap: getConnectedDevices()
09-07 11:37:42.808  2587  2587 V QC40_FileShareUiAdapter: isSupportedCommonUi [enabled]true
09-07 11:37:42.808  1250  1416 D BluetoothA2dp: onBluetoothStateChange: up=true
09-07 11:37:42.808  1250  1416 D BluetoothA2dp: Binding service...
09-07 11:37:42.808  2587  2751 D BluetoothAdapterState: Current state: ON, message: USER_TURN_OFF
09-07 11:37:42.808  1250  2327 V AlarmManager:  remove PendingIntent] PendingIntent{b870a70: PendingIntentRecord{45887f2 com.android.bluetooth broadcastIntent}}
09-07 11:37:42.808  1250  1416 D BluetoothA2dp: doBind(): CallingUid(myUserHandle) = 0
09-07 11:37:42.808  5843  5853 D BluetoothSap: onBluetoothStateChange: up=true
09-07 11:37:42.808  5843  5853 D BluetoothSap: Binding service...
09-07 11:37:42.808  2587  2587 D QC40_FileShareUiAdapter: isSupportedCommonUi [appState]0
,09-07 11:37:42.808  5989  5989 D BluetoothAdapter: STATE_ON
09-07 11:37:42.808  2587  2587 V BtOppService: isOwner == true
09-07 11:37:42.808  3003  3007 I WCNSS_FILTER: Direction(0): bytes: 5 : bytes_written: 5
,09-07 11:37:42.808  3003  3003 I WCNSS_FILTER: Direction(1): bytes: 7 : bytes_written: 7
,09-07 11:37:42.808  5989  5989 D BluetoothAdapter: STATE_ON
,09-07 11:37:42.818  3003  3007 I WCNSS_FILTER: Direction(0): bytes: 5 : bytes_written: 5
,09-07 11:37:42.818  1866  1881 D BluetoothAdapter: onBluetoothStateChange: up=true
09-07 11:37:42.818  1250  2010 V AlarmManager:  remove PendingIntent] PendingIntent{1d8c90f: PendingIntentRecord{45887f2 com.android.bluetooth broadcastIntent}}
09-07 11:37:42.818  1866  1881 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
09-07 11:37:42.818  3003  3003 I WCNSS_FILTER: Direction(1): bytes: 7 : bytes_written: 7
09-07 11:37:42.818  5843  5854 D BluetoothPbap: onBluetoothStateChange: up=true
09-07 11:37:42.818  5843  5854 D BluetoothPbap: Binding service...
,09-07 11:37:42.818  5989  5989 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded scan batching: Storing the value (SUPPORTED) in persistent storage
,09-07 11:37:42.818  3003  3007 I WCNSS_FILTER: Direction(0): bytes: 5 : bytes_written: 5
09-07 11:37:42.818  2587  2587 I BluetoothPbapService: Handler(): got msg=1
09-07 11:37:42.818  1250  1721 V AlarmManager:  remove PendingIntent] PendingIntent{e4db788: PendingIntentRecord{45887f2 com.android.bluetooth broadcastIntent}}
09-07 11:37:42.818  1694  2998 D BluetoothA2dp: onBluetoothStateChange: up=true
09-07 11:37:42.818  1694  2998 D BluetoothA2dp: Binding service...
09-07 11:37:42.818  3003  3003 I WCNSS_FILTER: Direction(1): bytes: 7 : bytes_written: 7
09-07 11:37:42.818  1694  2998 D BluetoothA2dp: doBind(): CallingUid(myUserHandle) = 0
09-07 11:37:42.818  1250  2674 D SecContentProvider: query(), uri = 4 selection = isProfileAuthorizedBySecurityPolicy
09-07 11:37:42.818  5989  5989 D BluetoothAdapter: STATE_ON
,09-07 11:37:42.818  3003  3007 I WCNSS_FILTER: Direction(0): bytes: 245 : bytes_written: 245
09-07 11:37:42.818  5989  5989 D BluetoothAdapter: STATE_ON
09-07 11:37:42.818  2587  3109 D BluetoothAdapter: onBluetoothStateChange: up=true
09-07 11:37:42.818  2587  3109 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,09-07 11:37:42.818  1694  2371 D BluetoothPbap: onBluetoothStateChange: up=true
09-07 11:37:42.818  1694  2371 D BluetoothPbap: Binding service...
09-07 11:37:42.818  1250  1986 V AlarmManager:  remove PendingIntent] PendingIntent{426cb07: PendingIntentRecord{45887f2 com.android.bluetooth broadcastIntent}}
09-07 11:37:42.818  5989  5989 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded filtering: Storing the value (SUPPORTED) in persistent storage
09-07 11:37:42.818  3003  3003 I WCNSS_FILTER: Direction(1): bytes: 7 : bytes_written: 7
,09-07 11:37:42.818  5843  5843 D BluetoothInputDevice: Proxy object connected
,09-07 11:37:42.818  5843  5843 D HidProfile: Bluetooth service connected
09-07 11:37:42.828  3003  3007 I WCNSS_FILTER: Direction(0): bytes: 245 : bytes_written: 245
09-07 11:37:42.828  2587  6409 V BluetoothPbapService: PBAP Service initSocket try: 0
09-07 11:37:42.828  1694  1694 D BluetoothPbap: Proxy object connected
09-07 11:37:42.828  1694  1694 D PbapServerProfile: Bluetooth service connected
09-07 11:37:42.828  3003  3003 I WCNSS_FILTER: Direction(1): bytes: 7 : bytes_written: 7
,09-07 11:37:42.828  3003  3007 I WCNSS_FILTER: Direction(0): bytes: 245 : bytes_written: 245
,09-07 11:37:42.828  1250  2010 V AlarmManager:  remove PendingIntent] PendingIntent{9ddf759: PendingIntentRecord{45887f2 com.android.bluetooth broadcastIntent}}
09-07 11:37:42.828  2587  6409 D BluetoothSocket: bindListen(): myUserId = 0
09-07 11:37:42.828  2587  6409 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-07 11:37:42.828  3003  3003 I WCNSS_FILTER: Direction(1): bytes: 7 : bytes_written: 7
09-07 11:37:42.828  3003  3007 I WCNSS_FILTER: Direction(0): bytes: 245 : bytes_written: 245
09-07 11:37:42.828  5989  5989 D BluetoothAdapter: STATE_ON
,09-07 11:37:42.828  2587  6409 D BluetoothPbapService: PBAP Socket is BluetoothServerSocket
,09-07 11:37:42.828  5989  5989 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-07 11:37:42.828  5989  5989 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-07 11:37:42.828  5989  5989 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-07 11:37:42.828  5989  5989 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-07 11:37:42.828  5989  5989 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-07 11:37:42.828  5989  5989 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-07 11:37:42.828  5989  5989 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-07 11:37:42.828  5989  5989 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-07 11:37:42.828  3003  3003 I WCNSS_FILTER: Direction(1): bytes: 7 : bytes_written: 7
,09-07 11:37:42.828  3003  3007 I WCNSS_FILTER: Direction(0): bytes: 245 : bytes_written: 245
,09-07 11:37:42.838  5843  5853 D BluetoothPan: onBluetoothStateChange on: true
09-07 11:37:42.838  5843  5853 D BluetoothPan: onBluetoothStateChange calling doBind()
09-07 11:37:42.838  3003  3003 I WCNSS_FILTER: Direction(1): bytes: 7 : bytes_written: 7
,09-07 11:37:42.838  3003  3007 I WCNSS_FILTER: Direction(0): bytes: 5 : bytes_written: 5
09-07 11:37:42.838  5989  5989 D BluetoothAdapter: STATE_ON
,09-07 11:37:42.838  3003  3003 I WCNSS_FILTER: Direction(1): bytes: 7 : bytes_written: 7
,09-07 11:37:42.838  3003  3007 I WCNSS_FILTER: Direction(0): bytes: 5 : bytes_written: 5
,09-07 11:37:42.838  5989  5989 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-07 11:37:42.838  5843  5843 D BluetoothPbap: Proxy object connected
09-07 11:37:42.838  3003  3003 I WCNSS_FILTER: Direction(1): bytes: 7 : bytes_written: 7
09-07 11:37:42.838  5843  5843 D PbapServerProfile: Bluetooth service connected
09-07 11:37:42.838  3003  3007 I WCNSS_FILTER: Direction(0): bytes: 245 : bytes_written: 245
09-07 11:37:42.838  1694  1705 D BluetoothInputDevice: onBluetoothStateChange: up=true
09-07 11:37:42.838  1694  1705 D BluetoothInputDevice: Binding service...
09-07 11:37:42.838  5989  5989 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-07 11:37:42.838  3003  3003 I WCNSS_FILTER: Direction(1): bytes: 7 : bytes_written: 7
,09-07 11:37:42.848  1694  1694 D BluetoothInputDevice: Proxy object connected
09-07 11:37:42.848  1694  1694 D HidProfile: Bluetooth service connected
09-07 11:37:42.848  5843  5843 D BluetoothPan: BluetoothPAN Proxy object connected
09-07 11:37:42.848  1250  1250 D BluetoothPan: BluetoothPAN Proxy object connected
09-07 11:37:42.848  5843  5843 D PanProfile: Bluetooth service connected
,09-07 11:37:42.848  1694  1706 D BluetoothMap: onBluetoothStateChange: up=true
09-07 11:37:42.848  1694  1706 D BluetoothMap: Binding service...
09-07 11:37:42.848  1250  1250 D BluetoothA2dp: Proxy object connected
,09-07 11:37:42.848  1694  1694 D BluetoothA2dp: Proxy object connected
09-07 11:37:42.848  1694  1694 D A2dpProfile: Bluetooth service connected
,09-07 11:37:42.848  5843  5843 D BluetoothSap: Proxy object connected
09-07 11:37:42.848  5843  5843 D SapProfile: Bluetooth service connected
,09-07 11:37:42.848  1694  1705 D BluetoothPan: onBluetoothStateChange on: true
09-07 11:37:42.848  1694  1705 D BluetoothPan: onBluetoothStateChange calling doBind()
09-07 11:37:42.848  2587  2604 D A2dpStateMachine: getConnectedDevices : size=0
09-07 11:37:42.848  1250  2010 D SecContentProvider: query(), uri = 4 selection = isProfileAuthorizedBySecurityPolicy
09-07 11:37:42.848  2587  2614 D A2dpStateMachine: getConnectedDevices : size=0
09-07 11:37:42.848  1694  1694 D BluetoothMap: Proxy object connected
09-07 11:37:42.848  1694  1694 D MapProfile: Bluetooth service connected
09-07 11:37:42.848  1694  1694 D BluetoothMap: getConnectedDevices()
,09-07 11:37:42.858  1250  1416 D BluetoothAdapter: onBluetoothStateChange: up=true
09-07 11:37:42.858  1694  1694 D BluetoothPan: BluetoothPAN Proxy object connected
09-07 11:37:42.858  1250  1416 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
09-07 11:37:42.858  1694  1694 D PanProfile: Bluetooth service connected
,09-07 11:37:42.858  1694  1705 D BluetoothAdapter: onBluetoothStateChange: up=true
09-07 11:37:42.858  1694  1705 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,09-07 11:37:42.858  1694  2998 D BluetoothInputDevice: onBluetoothStateChange: up=true
09-07 11:37:42.858  5843  5853 D BluetoothMap: onBluetoothStateChange: up=true
,09-07 11:37:42.858  2626  2649 D BluetoothAdapter: onBluetoothStateChange: up=true
09-07 11:37:42.858  2626  2649 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
09-07 11:37:42.858  5989  5999 D BluetoothAdapter: onBluetoothStateChange: up=true
09-07 11:37:42.858  5989  5999 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,09-07 11:37:42.858  1694  1706 D BluetoothSap: onBluetoothStateChange: up=true
09-07 11:37:42.858  1694  1706 D BluetoothSap: Binding service...
,09-07 11:37:42.858  2587  6412 D BluetoothSocket: bindListen(): myUserId = 0
09-07 11:37:42.858  2587  6412 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-07 11:37:42.858  1694  1694 D BluetoothSap: Proxy object connected
09-07 11:37:42.858  1694  1694 D SapProfile: Bluetooth service connected
,09-07 11:37:42.858  1944  2744 D BluetoothAdapter: onBluetoothStateChange: up=true
09-07 11:37:42.858  1944  2744 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
09-07 11:37:42.868  5843  5854 D BluetoothInputDevice: onBluetoothStateChange: up=true
,09-07 11:37:42.868  2626  2663 D BluetoothA2dp: onBluetoothStateChange: up=true
09-07 11:37:42.868  2587  6412 I BtOppRfcommListener: Accept thread started.
09-07 11:37:42.868  2626  2663 D BluetoothA2dp: Binding service...
,09-07 11:37:42.868  3003  3007 I WCNSS_FILTER: Direction(0): bytes: 245 : bytes_written: 245
,09-07 11:37:42.868  2626  2663 D BluetoothA2dp: doBind(): CallingUid(myUserHandle) = 0
,09-07 11:37:42.868  3003  3003 I WCNSS_FILTER: Direction(1): bytes: 7 : bytes_written: 7
,09-07 11:37:42.868  2626  2626 D BluetoothA2dp: Proxy object connected
,09-07 11:37:42.868  1250  1250 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
09-07 11:37:42.868  1250  1250 I InputMethodManagerService: [BT Setting State] State =12
09-07 11:37:42.868  1250  1250 I InputMethodManagerService: [BT Setting off -> on] mBTKeyboardCount =0, KEYBOARD_BT(0)
,09-07 11:37:42.868  2040  2040 D ucsBai_ConnectionManager: BluetoothReceiver Action android.bluetooth.adapter.action.STATE_CHANGED
,09-07 11:37:42.868  1250  1250 D BluetoothPhoneService: Bluetooth Adapter state : 12
09-07 11:37:42.868  1250  1250 I BluetoothPhoneService: queryPhoneState
09-07 11:37:42.868  1250  1250 I BluetoothPhoneService: updateHeadsetWithCallState : true
,09-07 11:37:42.878  1694  2100 V BluetoothEventManager: onReceive :: android.bluetooth.adapter.action.STATE_CHANGED
09-07 11:37:42.878  1694  2100 D BluetoothEventManager: AdapterStateChangedHandler :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 12
,09-07 11:37:42.878  1250  1250 D KnoxKeyguardUpdateMonitor: BroadcastReceiver onReceive
09-07 11:37:42.878  1250  1250 D KnoxKeyguardUpdateMonitor: BroadcastReceiver onReceive action: android.bluetooth.adapter.action.STATE_CHANGED
09-07 11:37:42.878  1250  1250 D KnoxKeyguardUpdateMonitor: BroadcastReceiver onReceive BT state is changed
,09-07 11:37:42.878  5843  5843 V BluetoothEventManager: onReceive :: android.bluetooth.adapter.action.STATE_CHANGED
,09-07 11:37:42.878  5843  5843 D BluetoothEventManager: AdapterStateChangedHandler :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 12
,09-07 11:37:42.878  5989  5989 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-07 11:37:42.888  1694  2100 W LocalBluetoothProfileManager: updateLocalProfiles :: MAP profile was previously added but the UUID is now missing.
09-07 11:37:42.888  1694  2100 W LocalBluetoothProfileManager: updateLocalProfiles :: PBAP profile was previously added but the UUID is now missing.
09-07 11:37:42.888  1694  2100 W LocalBluetoothProfileManager: updateLocalProfiles :: SAP profile was previously added but the UUID is now missing.
09-07 11:37:42.888  1694  2100 W LocalBluetoothProfileManager: updateLocalProfiles :: HID profile was previously added but the UUID is now missing.
,09-07 11:37:42.888  5843  5843 D LocalBluetoothProfileManager: Adding local A2DP profile
09-07 11:37:42.888  5989  5989 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-07 11:37:42.888  5843  5843 D BluetoothA2dp: doBind(): CallingUid(myUserHandle) = 0
,09-07 11:37:42.898  6416  6416 E Zygote  : v2
09-07 11:37:42.898  6416  6416 I libpersona: KNOX_SDCARD checking this for 10034
09-07 11:37:42.898  6416  6416 E Zygote  : isSdpEnabledProcess - SDP enabled
09-07 11:37:42.898  6416  6416 I libpersona: KNOX_SDCARD not a persona
,09-07 11:37:42.898  6416  6416 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0013
,09-07 11:37:42.898  6416  6416 E Zygote  : accessInfo : 64
09-07 11:37:42.898  6416  6416 E Zygote  : isSdpEnabledProcess - SDP enabled
09-07 11:37:42.898  6416  6416 E Zygote  : setSDPgroupsIntarray[pid]: 0 / [gid]: 10034 / [uid]: 10034
,09-07 11:37:42.898  1250  1721 I ActivityManager: Start proc 6416:com.samsung.android.email.provider/u0a34 for content provider com.samsung.android.email.provider/.provider.database.EmailProvider
09-07 11:37:42.898  6416  6416 W SELinux : SELinux: seapp_context_lookup: seinfo=platform, level=s0:c512,c768, pkgname=com.samsung.android.email.provider 
,09-07 11:37:42.898  5843  5843 D LocalBluetoothProfileManager: Adding local HEADSET profile
,09-07 11:37:42.908  5843  5843 E BluetoothHeadset: BTStateChangeCB is registed
,09-07 11:37:42.908  1694  2126 D BluetoothTile: handleUpdateState :  supported = true, enabled = true, enabling = false, connected = false, connecting = false, mController.getLastDeviceName() = null
09-07 11:37:42.908  1250  2333 D StatusBarManagerService: setIcon slot=bluetooth index=18 icon=StatusBarIcon(icon=Icon(typ=RESOURCE pkg=com.android.systemui id=0x7f0204c1) visible user=0 )
09-07 11:37:42.908  5843  5843 W LocalBluetoothProfileManager: updateLocalProfiles :: MAP profile was previously added but the UUID is now missing.
09-07 11:37:42.908  5843  5843 W LocalBluetoothProfileManager: updateLocalProfiles :: PBAP profile was previously added but the UUID is now missing.
,09-07 11:37:42.908  5843  5843 W LocalBluetoothProfileManager: updateLocalProfiles :: SAP profile was previously added but the UUID is now missing.
09-07 11:37:42.908  5843  5843 W LocalBluetoothProfileManager: updateLocalProfiles :: HID profile was previously added but the UUID is now missing.
09-07 11:37:42.908  1250  1986 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=true
,09-07 11:37:42.908  5843  5843 D BluetoothA2dp: Proxy object connected
,09-07 11:37:42.908  5843  5843 D A2dpProfile: Bluetooth service connected
,09-07 11:37:42.918  2587  2604 D A2dpStateMachine: getConnectedDevices : size=0
,09-07 11:37:42.928  6416  6416 D TimaKeyStoreProvider: TimaSignature is unavailable
09-07 11:37:42.928  6416  6416 D ActivityThread: Added TimaKeyStore provider
,09-07 11:37:42.958  6416  6416 W System  : ClassLoader referenced unknown path: /system/priv-app/SecEmail_M/lib/arm64
09-07 11:37:42.958  1250  1310 I ActivityManager: Killing 5855:com.samsung.android.provider.shootingmodeprovider/u0a41 (adj 15): DHA:empty #31
,09-07 11:37:42.958  1250  1310 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{d259c83 u0 com.samsung.android.providers.context.log.action.USE_APP_FEATURE_SURVEY qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{573bf46 2626:com.samsung.android.providers.context/u0a5}
,09-07 11:37:42.968  1250  1310 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{f05be00 u0 com.samsung.android.providers.context.log.action.USE_APP_FEATURE_SURVEY qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{573bf46 2626:com.samsung.android.providers.context/u0a5}
,09-07 11:37:42.968  1250  1310 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{9561639 u-1 android.bluetooth.adapter.action.STATE_CHANGED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{60a5ff2 5843:com.android.settings/1000}
,09-07 11:37:42.978  5843  5843 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1311 android.content.ContextWrapper.startService:606 android.content.ContextWrapper.startService:606 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,09-07 11:37:42.978  1250  2396 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{9561639 u-1 android.bluetooth.adapter.action.STATE_CHANGED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{573bf46 2626:com.samsung.android.providers.context/u0a5}
,09-07 11:37:42.978  1250  2674 D RCPManagerService: exchangeData() failure , invalid userId
,09-07 11:37:42.978  6373  6392 W com.google.a.a.b.d.a: Application name is not set. Call Builder#setApplicationName.
,09-07 11:37:42.988  1250  2010 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{9561639 u-1 android.bluetooth.adapter.action.STATE_CHANGED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{ef1b27 1866:com.google.android.gms.persistent/u0a10}
,09-07 11:37:42.988  1866  1866 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver bqHint=4 VirtualScreenParam=Params{mDisplayId=-1, null, mFlags=0x00000000)} (has extras) }.
,09-07 11:37:42.988  5843  5843 D DockEventReceiver: finishStartingService: stopping service
09-07 11:37:42.988  1250  2327 D RCPManagerService: exchangeData() failure , invalid userId
,09-07 11:37:42.988  1250  1310 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{9561639 u-1 android.bluetooth.adapter.action.STATE_CHANGED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{60a5ff2 5843:com.android.settings/1000}
,09-07 11:37:42.988  5843  5843 D BluetoothStatusReceiver: Received :: android.bluetooth.adapter.action.STATE_CHANGED
09-07 11:37:42.988  1250  1310 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{9561639 u-1 android.bluetooth.adapter.action.STATE_CHANGED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{3aa8374 6360:com.samsung.android.intelligenceservice2/5010}
09-07 11:37:42.988  5843  5843 D BluetoothStatusReceiver: AdapterStateChanged :: state = 10
,09-07 11:37:42.998  1250  1310 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{9561639 u-1 android.bluetooth.adapter.action.STATE_CHANGED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{32a7988 2587:com.android.bluetooth/1002}
,09-07 11:37:43.018  1250  1720 D RCPManagerService: exchangeData() failure , invalid userId
,09-07 11:37:43.048  5843  5843 D HeadsetProfile: Bluetooth service connected
,09-07 11:37:43.058  1694  1694 D HeadsetProfile: Bluetooth service connected
,09-07 11:37:43.058  1250  1721 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{9561639 u-1 android.bluetooth.adapter.action.STATE_CHANGED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{35f809d 6373:com.google.android.apps.maps/u0a89}
,09-07 11:37:43.058  1250  1721 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{76622c4 u-1 android.bluetooth.adapter.action.STATE_CHANGED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{60a5ff2 5843:com.android.settings/1000}
,09-07 11:37:43.068  1250  1720 D ActivityManager: removeProcessNameLocked mProcessNames.remove pid=5855 ,hash=47367747 ,name=com.samsung.android.provider.shootingmodeprovider
09-07 11:37:43.068  1250  1720 D ActivityManager: isAutoRunBlockedApp:: com.samsung.android.provider.shootingmodeprovider, Auto Run ON
,09-07 11:37:43.068  2587  2587 D ObexServerSockets: create(rfcomm = -2, l2capPsm = -2) for masId0
,09-07 11:37:43.078  6443  6443 E Zygote  : v2
09-07 11:37:43.078  6443  6443 I libpersona: KNOX_SDCARD checking this for 10001
09-07 11:37:43.078  6443  6443 I libpersona: KNOX_SDCARD not a persona
,09-07 11:37:43.078  1250  1990 I ActivityManager: Start proc 6443:com.sec.android.provider.badge/u0a1 for content provider com.sec.android.provider.badge/.BadgeProvider
09-07 11:37:43.078  6443  6443 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0013
,09-07 11:37:43.078  6443  6443 E Zygote  : accessInfo : 0
09-07 11:37:43.078  6443  6443 W SELinux : SELinux: seapp_context_lookup: seinfo=platform, level=s0:c512,c768, pkgname=com.sec.android.provider.badge 
,09-07 11:37:43.078  2587  2587 D BluetoothSocket: bindListen(): myUserId = 0
09-07 11:37:43.078  2587  2587 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-07 11:37:43.078  1250  1250 D BluetoothHeadset: registerListener : 11, listenercom.android.server.telecom.wearable.BluetoothMessageListener@5b240e2
09-07 11:37:43.078  1250  1250 D BluetoothHeadset: registerMessageListener
,09-07 11:37:43.088  1250  1313 I ActivityManager: Killing 5756:com.samsung.android.sm.devicesecurity/5012 (adj 15): DHA:empty #31
09-07 11:37:43.088  1250  1313 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{76622c4 u-1 android.bluetooth.adapter.action.STATE_CHANGED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{573bf46 2626:com.samsung.android.providers.context/u0a5}
,09-07 11:37:43.088  2587  2614 D HeadsetService: registerMessageListener
,09-07 11:37:43.088  2587  2614 D HeadsetService: registerMessageListener
09-07 11:37:43.088  1250  1250 I Telecom : CallAudioManager: onBluetoothStateChange: no focus
09-07 11:37:43.088  1250  1250 I Telecom : BluetoothManager : register MessageListener
09-07 11:37:43.088  2587  6385 D HeadsetStateMachine: Disconnected process message: 70, size: 0
09-07 11:37:43.088  2587  6385 D HeadsetStateMachine: processRegisterMessageListener : 11, com.samsung.bt.hfp.IMessageListener$Stub$Proxy@ca01988
09-07 11:37:43.088  2587  3153 D A2dpStateMachine: getConnectedDevices : size=0
,09-07 11:37:43.088  2587  2587 D BluetoothSocket: bindListen(): myUserId = 0
09-07 11:37:43.088  2587  2587 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-07 11:37:43.088  1250  2674 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{76622c4 u-1 android.bluetooth.adapter.action.STATE_CHANGED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{ef1b27 1866:com.google.android.gms.persistent/u0a10}
,09-07 11:37:43.098  1866  1866 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver bqHint=4 VirtualScreenParam=Params{mDisplayId=-1, null, mFlags=0x00000000)} (has extras) }.
,09-07 11:37:43.098  1250  2674 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{76622c4 u-1 android.bluetooth.adapter.action.STATE_CHANGED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{60a5ff2 5843:com.android.settings/1000}
,09-07 11:37:43.098  5843  5843 D BluetoothStatusReceiver: Received :: android.bluetooth.adapter.action.STATE_CHANGED
09-07 11:37:43.098  5843  5843 D BluetoothStatusReceiver: AdapterStateChanged :: state = 11
,09-07 11:37:43.098  2587  2587 D ObexServerSockets: Succeed to create listening sockets 
09-07 11:37:43.098  2587  2587 D ObexServerSockets: startAccept()
,09-07 11:37:43.098  2587  6455 D ObexServerSockets: Accepting socket connection for masId0
,09-07 11:37:43.098  2587  2587 D BluetoothSdpJni: sdpCreateMapMasRecordNative:
09-07 11:37:43.098  2587  2587 D BluetoothSdpJni: SDP Create record success - handle: 0
09-07 11:37:43.098  2587  6456 D ObexServerSockets: Accepting socket connection for masId0
,09-07 11:37:43.098  3003  3007 I WCNSS_FILTER: Direction(0): bytes: 245 : bytes_written: 245
09-07 11:37:43.098  1250  2674 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{76622c4 u-1 android.bluetooth.adapter.action.STATE_CHANGED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{3aa8374 6360:com.samsung.android.intelligenceservice2/5010}
,09-07 11:37:43.108  3003  3003 I WCNSS_FILTER: do_write: IBS write: fc
09-07 11:37:43.108  6443  6443 D TimaKeyStoreProvider: TimaSignature is unavailable
09-07 11:37:43.108  6443  6443 D ActivityThread: Added TimaKeyStore provider
,09-07 11:37:43.108  3003  3003 I WCNSS_FILTER: Direction(1): bytes: 7 : bytes_written: 7
,09-07 11:37:43.108  1250  2674 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{76622c4 u-1 android.bluetooth.adapter.action.STATE_CHANGED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{32a7988 2587:com.android.bluetooth/1002}
,09-07 11:37:43.108  1250  1313 I ActivityManager: Killing 5869:com.samsung.android.bbc.bbcagent/1000 (adj 15): DHA:empty #31
,09-07 11:37:43.118  1250  2674 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{76622c4 u-1 android.bluetooth.adapter.action.STATE_CHANGED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{35f809d 6373:com.google.android.apps.maps/u0a89}
,09-07 11:37:43.118  1250  2674 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{d76ac73 u-1 android.bluetooth.adapter.action.STATE_CHANGED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{60a5ff2 5843:com.android.settings/1000}
,09-07 11:37:43.118  5843  5843 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1311 android.content.ContextWrapper.startService:606 android.content.ContextWrapper.startService:606 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,09-07 11:37:43.128  6443  6443 W System  : ClassLoader referenced unknown path: /system/priv-app/BadgeProvider_M/lib/arm64
,09-07 11:37:43.128  1250  2333 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{d76ac73 u-1 android.bluetooth.adapter.action.STATE_CHANGED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{573bf46 2626:com.samsung.android.providers.context/u0a5}
,09-07 11:37:43.128  6443  6443 D BadgeProvider: onCreate
09-07 11:37:43.128  1250  2333 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{d76ac73 u-1 android.bluetooth.adapter.action.STATE_CHANGED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{ef1b27 1866:com.google.android.gms.persistent/u0a10}
09-07 11:37:43.128  6443  6443 D BadgeProvider: DatabaseHelper
09-07 11:37:43.128  1866  1866 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver bqHint=4 VirtualScreenParam=Params{mDisplayId=-1, null, mFlags=0x00000000)} (has extras) }.
,09-07 11:37:43.128  5843  5843 D DockEventReceiver: finishStartingService: stopping service
,09-07 11:37:43.138  1250  1990 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{d76ac73 u-1 android.bluetooth.adapter.action.STATE_CHANGED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{60a5ff2 5843:com.android.settings/1000}
,09-07 11:37:43.138  5843  5843 D BluetoothStatusReceiver: Received :: android.bluetooth.adapter.action.STATE_CHANGED
09-07 11:37:43.138  5843  5843 D BluetoothStatusReceiver: AdapterStateChanged :: state = 12
,09-07 11:37:43.138  1250  1310 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{d76ac73 u-1 android.bluetooth.adapter.action.STATE_CHANGED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{3aa8374 6360:com.samsung.android.intelligenceservice2/5010}
,09-07 11:37:43.138  1250  1313 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{d76ac73 u-1 android.bluetooth.adapter.action.STATE_CHANGED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{32a7988 2587:com.android.bluetooth/1002}
,09-07 11:37:43.148  2587  2587 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@c11cc52
09-07 11:37:43.148  2587  2587 D BtConfig.SecureMode: isSecureModeOn:false
,09-07 11:37:43.148  6443  6453 D BaseReflect: null getOwnClass TEST
,09-07 11:37:43.148  6443  6453 D MethodReflector: android.content.ContentResolver getClass TEST
,09-07 11:37:43.148  6443  6453 D BaseReflect: class android.content.ContentResolver isSupportClass TEST
09-07 11:37:43.148  6443  6453 D BaseReflect: class android.content.ContentResolver getOwnClass TEST
,09-07 11:37:43.148  1250  1313 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{d76ac73 u-1 android.bluetooth.adapter.action.STATE_CHANGED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{35f809d 6373:com.google.android.apps.maps/u0a89}
,09-07 11:37:43.148  6443  6453 D MethodReflector: notifyChange is called
09-07 11:37:43.148  1971  1971 D Launcher.Model: reloadBadges entered.
,09-07 11:37:43.148  6443  6453 D BadgeProvider: sendNotify entered. [uri] : content://com.sec.badge/apps
09-07 11:37:43.148  6443  6453 D BadgeProvider: sendNotify, [notify] : null
09-07 11:37:43.148  1971  1971 D Launcher.Model: reloadBadges entered.
09-07 11:37:43.148  6443  6453 D BadgeProvider: update, getCallingPackage() : com.samsung.android.email.provider
09-07 11:37:43.148  6443  6453 D BadgeProvider: update, [uri] : content://com.sec.badge/apps
09-07 11:37:43.148  6443  6453 D BadgeProvider: update, [uri.query] : null
09-07 11:37:43.148  6443  6453 D BadgeProvider: update, [BadgeCount] : badgecount=0
,09-07 11:37:43.148  6443  6453 D BadgeProvider: update, [UpdateCount] : 1
,09-07 11:37:43.158  6443  6453 D BadgeProvider: query, [selection] : null
,09-07 11:37:43.158  1971  2128 D BadgeCache: 1. updateBadgeCounts: com.samsung.android.email.provider = 0
09-07 11:37:43.158  1971  2128 D BadgeCache: 1. updateBadgeCounts: com.android.mms = 0
09-07 11:37:43.158  1971  2128 D BadgeCache: 1. updateBadgeCounts: com.android.settings = 0
09-07 11:37:43.158  1971  2128 D BadgeCache: 1. updateBadgeCounts: com.android.settings = 0
,09-07 11:37:43.168  6443  6453 D BadgeProvider: query, [selection] : null
,09-07 11:37:43.168  1250  1964 D ActivityManager: removeProcessNameLocked mProcessNames.remove pid=5756 ,hash=160360918 ,name=com.samsung.android.sm.devicesecurity
09-07 11:37:43.168  1250  1964 D ActivityManager: isAutoRunBlockedApp:: com.samsung.android.sm.devicesecurity, Auto Run ON
,09-07 11:37:43.168  1971  2128 D BadgeCache: 1. updateBadgeCounts: com.samsung.android.email.provider = 0
09-07 11:37:43.168  1971  2128 D BadgeCache: 1. updateBadgeCounts: com.android.mms = 0
09-07 11:37:43.168  1971  2128 D BadgeCache: 1. updateBadgeCounts: com.android.settings = 0
09-07 11:37:43.168  1971  2128 D BadgeCache: 1. updateBadgeCounts: com.android.settings = 0
,09-07 11:37:43.228  1250  2396 D ActivityManager: isAutoRunBlockedApp:: com.samsung.android.bbc.bbcagent, Auto Run ON
09-07 11:37:43.228  1250  2396 D ActivityManager: removeProcessNameLocked mProcessNames.remove pid=5869 ,hash=240814398 ,name=com.samsung.android.bbc.bbcagent
,09-07 11:37:44.108  3003  3066 I WCNSS_FILTER: do_write: IBS write: fe
09-07 11:37:44.108  3003  3066 I WCNSS_FILTER: ibs_msm_serial_clock_vote: vote UART CLK OFF using UART driver's ioctl()
,09-07 11:37:44.898  1250  3553 D SSRM:s  : SIOP:: AP = 300, PST = 330 (W:12), CP = 37, LCD = 0
09-07 11:37:44.898  1250  3553 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
,09-07 11:37:45.338   707   707 I MSM-irqbalance: Decided to move IRQ327 from CPU3 to CPU1
,09-07 11:37:45.448  5989  6040 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-07 11:37:45.458  1250  1720 D SecContentProvider: query(), uri = 18 selection = isWifiEnabled
09-07 11:37:45.458  1250  1720 D WifiService: setWifiEnabled: false pid=5989, uid=10136
09-07 11:37:45.458  1250  1720 D SecContentProvider2: query(), uri = 20 selection = isWifiStateChangeAllowed
09-07 11:37:45.458  1250  1720 D SettingsProvider: isChangeAllowed() : name = wifi_on
,09-07 11:37:45.458  1250  1623 D WifiBigDataLog: getJsonFormat() - feature : ONOF
,09-07 11:37:45.458  1250  1623 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:836 com.android.server.wifi.WifiStateMachine.insertLog:18843 com.android.server.wifi.WifiStateMachine.access$4300:293 com.android.server.wifi.WifiStateMachine$DefaultState.processMessage:8707 com.android.internal.util.StateMachine$SmHandler.processMsg:968 
09-07 11:37:45.458  1250  1623 D WifiBigDataLog: init : 
09-07 11:37:45.458  1250  1624 D WifiController: [FCC]setFccChannel() is called !!!
09-07 11:37:45.458  1250  1624 D WifiStateMachine: setFccChannel: channel = 0
09-07 11:37:45.458  1250  1624 D WifiController: [FCC]Airplane on, setFccChannel(0)!!!
,09-07 11:37:45.468  1250  1378 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{40bffa9 u0 com.samsung.android.providers.context.log.action.USE_APP_FEATURE_SURVEY qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{573bf46 2626:com.samsung.android.providers.context/u0a5}
09-07 11:37:45.468  5989  6040 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-07 11:37:45.468  5989  6040 I WifiManager: isAllowWifiWarning() -> isCscWifiEnableWarning : false ChinaNalSecurityType : 
,09-07 11:37:45.468  1250  1310 D SecContentProvider: query(), uri = 18 selection = isWifiEnabled
09-07 11:37:45.468  1250  1310 D SecContentProvider2: query(), uri = 20 selection = isWifiStateChangeAllowed
,09-07 11:37:45.468  1250  1310 D WifiService: System do NOT have com.sec.feature.sensorhub feature
09-07 11:37:45.468  1250  1310 D WifiService: Wi-Fi on and Screen on , checkSensorStatus !!
09-07 11:37:45.478  1250  1310 W WifiService: Failed getting userId using ActivityManagerNative
09-07 11:37:45.478  1250  1310 W WifiService: java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=5989, uid=10136 requires android.permission.INTERACT_ACROSS_USERS
09-07 11:37:45.478  1250  1310 W WifiService: 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:28130)
09-07 11:37:45.478  1250  1310 W WifiService: 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2542)
09-07 11:37:45.478  1250  1310 W WifiService: 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2530)
09-07 11:37:45.478  1250  1310 W WifiService: 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:257)
09-07 11:37:45.478  1250  1310 W WifiService: 	at android.os.Binder.execTransact(Binder.java:453)
09-07 11:37:45.468  1250  1310 D WifiService: setWifiEnabled: true pid=5989, uid=10136
09-07 11:37:45.478  1250  1623 D WifiBigDataLog: getJsonFormat() - feature : ONOF
09-07 11:37:45.468  1250  1310 W ActivityManager: Permission Denial: getCurrentUser() from pid=5989, uid=10136 requires android.permission.INTERACT_ACROSS_USERS
09-07 11:37:45.478  1250  1310 D SettingsProvider: isChangeAllowed() : name = wifi_on
09-07 11:37:45.478  1250  1623 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:836 com.android.server.wifi.WifiStateMachine.insertLog:18843 com.android.server.wifi.WifiStateMachine.access$4300:293 com.android.server.wifi.WifiStateMachine$DefaultState.processMessage:8707 com.android.internal.util.StateMachine$SmHandler.processMsg:968 
,09-07 11:37:45.478  1250  1623 D WifiBigDataLog: init : 
09-07 11:37:45.478  1250  2127 E OsAgent :  Wifi Scan Always Available: 0
09-07 11:37:45.478  1250  1624 D WifiController: [FCC]setFccChannel() is called !!!
09-07 11:37:45.478  1250  2127 E IzatSvc_OSObserver: I/LocTech-Label :: OSOBSERVER :: Data Items In
09-07 11:37:45.478  1250  1624 D WifiController: [FCC]Airplane on, setFccChannel(0)!!!
09-07 11:37:45.478  1250  2127 E IzatSvc_OSObserver: I/LocTech-Value :: Data Item Value: IS_WIFI_HARDWARE_ON: true
09-07 11:37:45.478  1250  1624 D WifiStateMachine: setFccChannel: channel = 0
09-07 11:37:45.478  1250  1624 D SecContentProvider: insert(), uri = 2
09-07 11:37:45.478  1250  2152 E LocSvc_libulp: I/int ulp_msg_process_phone_setting_update(const UlpPhoneContextSettings*), context type: 0x4
09-07 11:37:45.478  1250  2152 E LocSvc_libulp:   gps enabled: 0
09-07 11:37:45.478  1250  2152 E LocSvc_libulp:  network position available 0
09-07 11:37:45.478  1250  2152 E LocSvc_libulp:  wifi setting enabled 1
09-07 11:37:45.478  1250  2152 E LocSvc_libulp:  battery charging 0, agps enabled 0, enh_location_services_enabled 0is_pip_user_setting_enabled 0
09-07 11:37:45.478  1250  2152 E LocSvc_libulp: I/int ulp_msg_process_system_update(UlpSystemEvent): systemEvent:4 
,09-07 11:37:45.478  1250  2132 E LocSvc_LBSApiV02: E/virtual int lbs_core::LBSApiV02::wifiEnabledStatusInject(int):677]: Error : st = 2, ind.status = 1310827456
09-07 11:37:45.478  1250  2127 E OsAgent :  Wifi Scan Always Available: 0
09-07 11:37:45.478  1250  2127 E IzatSvc_OSObserver: I/LocTech-Label :: OSOBSERVER :: Data Items In
09-07 11:37:45.478  1250  2127 E IzatSvc_OSObserver: I/LocTech-Value :: Data Item Value: IS_WIFI_HARDWARE_ON: true
,09-07 11:37:45.478  1250  2127 E OsAgent :  Wifi Scan Always Available: 0
09-07 11:37:45.478  1250  2127 E IzatSvc_OSObserver: I/LocTech-Label :: OSOBSERVER :: Data Items In
09-07 11:37:45.478  1250  2127 E IzatSvc_OSObserver: I/LocTech-Value :: Data Item Value: IS_WIFI_HARDWARE_ON: true
,09-07 11:37:45.478  1250  1378 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{6b7892e u0 com.samsung.android.providers.context.log.action.USE_APP_FEATURE_SURVEY qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{573bf46 2626:com.samsung.android.providers.context/u0a5}
,09-07 11:37:45.488  1250  1623 E WifiHW  : ##################### set firmware type 0 #####################
,09-07 11:37:45.798  1250  2327 V AlarmManager:  remove PendingIntent] PendingIntent{f859ccf: PendingIntentRecord{45887f2 com.android.bluetooth broadcastIntent}}
,09-07 11:37:46.478  1250  1384 E EthernetNetworkFactory: maybeTrackInterface : not matched eth0/usb0 iface is wlan0
,09-07 11:37:46.478  1250  1416 D Tethering: enter TetherInterfaceSM  and send tetherstatechangebroadcast
09-07 11:37:46.478  1250  1416 D Tethering: NAP Supported and not Wifi Model
,09-07 11:37:46.478   766  1446 I QC-NETMGR-LIB: Received nl msg, recvmsg returned 1088
09-07 11:37:46.478   766  1446 I QC-NETMGR-LIB: Received command: ID=NETMGR_KIF_MSG_CMD, link=0
09-07 11:37:46.478   554  1406 D Netd    : Iface wlan0 link down
09-07 11:37:46.478   766  1442 I QC-NETMGR-LIB: Process command: ID=NETMGR_KIF_MSG_CMD, link=0, state=1
09-07 11:37:46.478   766  1442 I QC-NETMGR-LIB: Processing RTM_NEWLINK
09-07 11:37:46.478   766  1442 I QC-NETMGR-LIB: Metainfo:  Index=17 Family=0 Type=0x1 Change=[0xffffffff]UP BROADCAST DEBUG LOOPBACK POINTOPOINT NOTRAILERS RUNNING NOARP PROMISC ALLMULTI MASTER SLAVE MULTICAST PORTSEL AUTOMEDIA DYNAMIC LOWER_UP DORMANT  Flags=[0x1002]BROADCAST MULTICAST 
09-07 11:37:46.478   766  1442 I QC-NETMGR-LIB: Rcvd Netlink msg type [16]
09-07 11:37:46.478   766  1442 I QC-NETMGR-LIB: Received RTM_NEWLINK
09-07 11:37:46.478   766  1442 E QC-NETMGR-LIB: unrecognized ifindex 17, disable link
,09-07 11:37:46.478  1250  1416 E Tethering: No numeric data
,09-07 11:37:46.488   766  1446 I QC-NETMGR-LIB: Received nl msg, recvmsg returned 1088
09-07 11:37:46.488   766  1446 I QC-NETMGR-LIB: Received command: ID=NETMGR_KIF_MSG_CMD, link=0
09-07 11:37:46.488   554  1406 D Netd    : Iface p2p0 link down
09-07 11:37:46.488   766  1442 I QC-NETMGR-LIB: Process command: ID=NETMGR_KIF_MSG_CMD, link=0, state=1
,09-07 11:37:46.488   766  1442 I QC-NETMGR-LIB: Processing RTM_NEWLINK
09-07 11:37:46.488   766  1442 I QC-NETMGR-LIB: Metainfo:  Index=18 Family=0 Type=0x1 Change=[0xffffffff]UP BROADCAST DEBUG LOOPBACK POINTOPOINT NOTRAILERS RUNNING NOARP PROMISC ALLMULTI MASTER SLAVE MULTICAST PORTSEL AUTOMEDIA DYNAMIC LOWER_UP DORMANT  Flags=[0x1002]BROADCAST MULTICAST 
09-07 11:37:46.488   766  1442 I QC-NETMGR-LIB: Rcvd Netlink msg type [16]
09-07 11:37:46.488   766  1442 I QC-NETMGR-LIB: Received RTM_NEWLINK
09-07 11:37:46.488   766  1442 E QC-NETMGR-LIB: unrecognized ifindex 18, disable link
09-07 11:37:46.488  1250  1416 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
09-07 11:37:46.488  1250  1416 D Tethering: InitialState.processMessage what=4
09-07 11:37:46.488  1250  1384 E EthernetNetworkFactory: maybeTrackInterface : not matched eth0/usb0 iface is p2p0
,09-07 11:37:46.488  1250  1416 D Tethering: NAP Supported and not Wifi Model,
,09-07 11:37:46.488  1250  1620 D NtpTrustedTime: currentTimeMillis() cache hit
09-07 11:37:46.488  1250  1620 V NetworkStats: performPollLocked(flags=0x1),
09-07 11:37:46.488  1694  1694 D HotspotTile: onReceive : android.net.conn.TETHER_STATE_CHANGED
,09-07 11:37:46.488  1694  1694 D HotspotTile: updateTetherState():false, false
,09-07 11:37:46.498   554  1414 I WifiHW  : wifi_change_fw_path(): fwpath = sta
,09-07 11:37:46.498   554  1414 D SoftapController: Softap fwReload - Ok
09-07 11:37:46.498  1250  1378 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{9fb9006 u-1 android.net.conn.TETHER_STATE_CHANGED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{667d8b1 1250:system/1000}
09-07 11:37:46.498  1250  1620 D NtpTrustedTime: currentTimeMillis() cache hit
09-07 11:37:46.498  1250  1620 D NetworkStatsRecorder: entry.iface is null
09-07 11:37:46.498  1250  1620 D NetworkStatsRecorder: entry.iface is null
09-07 11:37:46.498  1250  1620 D NetworkStatsRecorder: entry.iface is null
09-07 11:37:46.498  1250  1620 D NetworkStatsRecorder: entry.iface is null
09-07 11:37:46.498  1250  1620 V NetworkStats: performPollLocked() took 7ms
,09-07 11:37:46.498   554  1414 D CommandListener: Setting iface cfg
,09-07 11:37:46.498   554  1414 D CommandListener: Trying to bring down wlan0
09-07 11:37:46.498  1250  1416 E Tethering: No numeric data
,09-07 11:37:46.498   554  1414 D CommandListener: Clearing all IP addresses on wlan0
,09-07 11:37:46.508  1250  1621 D NtpTrustedTime: currentTimeMillis() cache hit
09-07 11:37:46.508  1250  1621 D NtpTrustedTime: currentTimeMillis() cache hit
09-07 11:37:46.508  1250  1416 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
,09-07 11:37:46.508  1250  1623 E WifiMonitor: killSupplicant p2ptrue init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
09-07 11:37:46.508  1250  1620 V NetworkStats: performPollLocked(flags=0x1)
09-07 11:37:46.508  1250  1620 D NtpTrustedTime: currentTimeMillis() cache hit
09-07 11:37:46.508  1694  1694 D HotspotTile: onReceive : android.net.conn.TETHER_STATE_CHANGED
09-07 11:37:46.508  1694  1694 D HotspotTile: updateTetherState():false, false
09-07 11:37:46.508  1250  1623 D wifi    : Can not initialize the vendor function pointer table
09-07 11:37:46.508  1250  1623 E WifiNative-HAL: Could not start hal
09-07 11:37:46.508  1250  1623 E WifiStateMachine: Failed to start HAL
09-07 11:37:46.508  1250  1623 E WifiHW  : supplicant_name : p2p_supplicant
,09-07 11:37:46.518  1250  1378 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{a256c7 u-1 android.net.conn.TETHER_STATE_CHANGED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{667d8b1 1250:system/1000}
,09-07 11:37:46.518  1250  1620 D NetworkStatsRecorder: entry.iface is null
09-07 11:37:46.518  1250  1620 D NetworkStatsRecorder: entry.iface is null
09-07 11:37:46.518  1250  1620 D NetworkStatsRecorder: entry.iface is null
09-07 11:37:46.518  1250  1620 D NtpTrustedTime: currentTimeMillis() cache hit
09-07 11:37:46.518  1250  1620 D NetworkStatsRecorder: entry.iface is null
09-07 11:37:46.518  1250  1620 V NetworkStats: performPollLocked() took 9ms
,09-07 11:37:46.518  1250  1621 D NtpTrustedTime: currentTimeMillis() cache hit
09-07 11:37:46.518  1250  1621 D NtpTrustedTime: currentTimeMillis() cache hit
,09-07 11:37:46.558  6474  6474 I wpa_supplicant: [wpa_supplicant_init]: use SECRIL
09-07 11:37:46.558  6474  6474 I wpa_supplicant: Successfully initialized wpa_supplicant
09-07 11:37:46.558  6474  6474 I wpa_supplicant: set_csc_config : ifname(wlan0), certi_flags(0x0), autoconnect_flags(0x0), opbranding_flags(0x0), boolean_flags(0x20000), vendorssid_list()
,09-07 11:37:46.558  6474  6474 I SecureStorage: [INFO]: SPID(0x00000000)Checking if this device supports Secure Storage
,09-07 11:37:46.588  6474  6474 I SecureStorage: [INFO]: SPID(0x00000000)This device supports Secure Storage
09-07 11:37:46.588   458   458 I SecureStorage: [INFO]: SPID(0x00000005)Credentials: uid 1010, gid 1010, pid 6474
09-07 11:37:46.588   458   458 I SecureStorage: [INFO]: SPID(0x00000005)Received function mask & code: 0x0000010C
,09-07 11:37:46.588  6474  6474 I SecureStorage: [INFO]: SPID(0x00000000)SS Daemon is running
09-07 11:37:46.588  6474  6474 I wpa_supplicant: ssSupport state is = 1
09-07 11:37:46.588  6474  6474 I wpa_supplicant: >>>>> GET KEY, IV <<<<<
09-07 11:37:46.588  6474  6474 I SecureStorage: [INFO]: SPID(0x00000000)Processing data
,09-07 11:37:46.588   458   458 I SecureStorage: [INFO]: SPID(0x00000005)Credentials: uid 1010, gid 1010, pid 6474
09-07 11:37:46.588   458   458 I SecureStorage: [INFO]: SPID(0x00000005)Received function mask & code: 0x00000106
,09-07 11:37:46.598  6474  6474 I SecureStorage: [INFO]: SPID(0x00000006)ss_id will be loaded by secure_storage_daemon: /system/bin/wpa_supplicant
,09-07 11:37:46.608  1250  1623 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
,09-07 11:37:46.608  1250  1250 D HS20StateMachine: Broadcast Received: android.net.wifi.WIFI_STATE_CHANGED
,09-07 11:37:46.608  1250  1250 I WifiHs20Service: Broadcast received:android.net.wifi.WIFI_STATE_CHANGED
09-07 11:37:46.608  1250  1628 I WifiHs20Service: Message received 5011
,09-07 11:37:46.608  1250  1631 D ConnectivityManager: getMobileDataEnabled()+ subId=2147483643
,09-07 11:37:46.618  1944  2290 D PhoneInterfaceManager: [PhoneIntfMgr] getDataEnabled: subId=2147483643 phoneId=0
,09-07 11:37:46.618  1944  2290 D PhoneInterfaceManager: [PhoneIntfMgr] getDataEnabled: subId=2147483643 retVal=true
09-07 11:37:46.618  1694  2100 D NetworkController: onReceive: intent=Intent { act=android.net.wifi.WIFI_STATE_CHANGED flg=0x4000010 bqHint=4 VirtualScreenParam=Params{mDisplayId=-1, null, mFlags=0x00000000)} (has extras) }
09-07 11:37:46.618  1694  1694 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
09-07 11:37:46.618  1250  1631 D ConnectivityManager: getMobileDataEnabled()- subId=2147483643 retVal=true
09-07 11:37:46.618  1694  1694 D HotspotTile: onReceive : 2, 0
,09-07 11:37:46.618  5989  5989 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-07 11:37:46.618  1250  1378 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{79c4f4 u-1 android.net.wifi.WIFI_STATE_CHANGED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{9925d68 5989:com.test.thalitest/u0a136}
09-07 11:37:46.618  5989  5989 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-07 11:37:46.618  1250  2327 D ConnectivityService: returning getNetworkInfo for network type 0 : [type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
09-07 11:37:46.618  1250  2327 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
09-07 11:37:46.618  1250  2327 D ConnectivityService: returning getNetworkInfo for network type 2 : [type: MOBILE_MMS[] - MOBILE_MMS, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
09-07 11:37:46.618  1250  2327 D ConnectivityService: returning getNetworkInfo for network type 3 : [type: MOBILE_SUPL[] - MOBILE_SUPL, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
09-07 11:37:46.618  1250  2327 D ConnectivityService: returning getNetworkInfo for network type 4 : [type: MOBILE_DUN[] - MOBILE_DUN, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
09-07 11:37:46.618  1250  2327 D ConnectivityService: returning getNetworkInfo for network type 5 : [type: MOBILE_HIPRI[] - MOBILE_HIPRI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
09-07 11:37:46.618  1250  2327 D ConnectivityService: returning getNetworkInfo for network type 7 : [type: BLUETOOTH[] - BLUETOOTH, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
09-07 11:37:46.618  1250  2327 D ConnectivityService: returning getNetworkInfo for network type 9 : [type: ETHERNET[] - ETHERNET, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
09-07 11:37:46.618  1250  2327 D ConnectivityService: returning getNetworkInfo for network type 10 : [type: MOBILE_FOTA[] - MOBILE_FOTA, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
09-07 11:37:46.618  1250  2327 D ConnectivityService: returning getNetworkInfo for network type 11 : [type: MOBILE_IMS[] - MOBILE_IMS, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
09-07 11:37:46.618  1250  2327 D ConnectivityService: returning getNetworkInfo for network type 12 : [type: MOBILE_CBS[] - MOBILE_CBS, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
09-07 11:37:46.618  1250  2327 D ConnectivityService: returning getNetworkInfo for network type 13 : [type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: false]
09-07 11:37:46.618  1250  2327 D ConnectivityService: returning getNetworkInfo for network type 14 : [type: MOBILE_IA[] - MOBILE_IA, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
09-07 11:37:46.618  1250  2327 D ConnectivityService: returning getNetworkInfo for network type 15 : [type: MOBILE_EMERGENCY[] - MOBILE_EMERGENCY, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
09-07 11:37:46.618  1250  2327 D ConnectivityService: returning getNetworkInfo for network type 17 : [type: VPN[] - VPN, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
,09-07 11:37:46.628  1250  1994 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{79c4f4 u-1 android.net.wifi.WIFI_STATE_CHANGED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{6f787ab 6209:com.samsung.android.securitylogagent/1000}
,09-07 11:37:46.808   458   458 I SecureStorage: [INFO]: SPID(0x00000006)Secure Storage Daemon finished processing with result: 0
09-07 11:37:46.808  6474  6474 I SecureStorage: [INFO]: SPID(0x00000006)Processing data has been completed
,09-07 11:37:46.838  6474  6474 I wpa_supplicant: Loading default cred
09-07 11:37:46.838  6474  6474 I SecureStorage: [INFO]: SPID(0x00000006)Checking if this device supports Secure Storage
,09-07 11:37:46.868  6474  6474 I SecureStorage: [INFO]: SPID(0x00000006)This device supports Secure Storage
,09-07 11:37:46.868   458   458 I SecureStorage: [INFO]: SPID(0x00000006)Credentials: uid 1010, gid 1010, pid 6474
09-07 11:37:46.868   458   458 I SecureStorage: [INFO]: SPID(0x00000006)Received function mask & code: 0x0000010C
,09-07 11:37:46.868  6474  6474 I SecureStorage: [INFO]: SPID(0x00000006)SS Daemon is running
09-07 11:37:46.868  6474  6474 I wpa_supplicant: ssSupport state is = 1
09-07 11:37:46.868  6474  6474 W wpa_supplicant: Loading system cred
09-07 11:37:46.868  6474  6474 I SecureStorage: [INFO]: SPID(0x00000006)Checking if this device supports Secure Storage
,09-07 11:37:46.898  6474  6474 I SecureStorage: [INFO]: SPID(0x00000006)This device supports Secure Storage
,09-07 11:37:46.898   458   458 I SecureStorage: [INFO]: SPID(0x00000006)Credentials: uid 1010, gid 1010, pid 6474
09-07 11:37:46.898   458   458 I SecureStorage: [INFO]: SPID(0x00000006)Received function mask & code: 0x0000010C
09-07 11:37:46.898  6474  6474 I SecureStorage: [INFO]: SPID(0x00000006)SS Daemon is running
09-07 11:37:46.898  6474  6474 I wpa_supplicant: ssSupport state is = 1
09-07 11:37:46.898  6474  6474 I wpa_supplicant: Blacklist: Clear (all) 
,09-07 11:37:46.898  6474  6474 E wpa_supplicant: getSavedIMSI cannot open /data/misc/radio/kmem: No such file or directory
09-07 11:37:46.898  6474  6474 I wpa_supplicant: [getIMSI]: sim_num 0
,09-07 11:37:46.898  6474  6474 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,09-07 11:37:46.908   766  1446 I QC-NETMGR-LIB: Received nl msg, recvmsg returned 1084
09-07 11:37:46.908   766  1446 I QC-NETMGR-LIB: Received command: ID=NETMGR_KIF_MSG_CMD, link=0
09-07 11:37:46.908   766  1442 I QC-NETMGR-LIB: Process command: ID=NETMGR_KIF_MSG_CMD, link=0, state=1
09-07 11:37:46.908   766  1442 I QC-NETMGR-LIB: Processing RTM_NEWLINK
09-07 11:37:46.908   554  1406 D Netd    : Iface wlan0 link down
09-07 11:37:46.908   766  1442 I QC-NETMGR-LIB: Metainfo:  Index=17 Family=0 Type=0x1 Change=[0x1]UP  Flags=[0x1003]UP BROADCAST MULTICAST 
09-07 11:37:46.908   766  1442 I QC-NETMGR-LIB: Rcvd Netlink msg type [16]
09-07 11:37:46.908   766  1442 I QC-NETMGR-LIB: Received RTM_NEWLINK
09-07 11:37:46.908   766  1442 E QC-NETMGR-LIB: unrecognized ifindex 17, disable link
,09-07 11:37:47.218  6474  6474 I wpa_supplicant: set_csc_config : ifname(p2p0), certi_flags(0x0), autoconnect_flags(0x0), opbranding_flags(0x0), boolean_flags(0x0), vendorssid_list()
,09-07 11:37:47.218  6474  6474 I SecureStorage: [INFO]: SPID(0x00000006)Checking if this device supports Secure Storage
,09-07 11:37:47.258  6474  6474 I SecureStorage: [INFO]: SPID(0x00000006)This device supports Secure Storage
,09-07 11:37:47.258   458   458 I SecureStorage: [INFO]: SPID(0x00000006)Credentials: uid 1010, gid 1010, pid 6474
09-07 11:37:47.258   458   458 I SecureStorage: [INFO]: SPID(0x00000006)Received function mask & code: 0x0000010C
,09-07 11:37:47.258  6474  6474 I SecureStorage: [INFO]: SPID(0x00000006)SS Daemon is running
09-07 11:37:47.258  6474  6474 I wpa_supplicant: ssSupport state is = 1
,09-07 11:37:47.258  6474  6474 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,09-07 11:37:47.258   766  1446 I QC-NETMGR-LIB: Received nl msg, recvmsg returned 1084
09-07 11:37:47.258   766  1446 I QC-NETMGR-LIB: Received command: ID=NETMGR_KIF_MSG_CMD, link=0
09-07 11:37:47.258   554  1406 D Netd    : Iface p2p0 link down
09-07 11:37:47.258   766  1442 I QC-NETMGR-LIB: Process command: ID=NETMGR_KIF_MSG_CMD, link=0, state=1
09-07 11:37:47.258   766  1442 I QC-NETMGR-LIB: Processing RTM_NEWLINK
09-07 11:37:47.258   766  1442 I QC-NETMGR-LIB: Metainfo:  Index=18 Family=0 Type=0x1 Change=[0x1]UP  Flags=[0x1043]UP BROADCAST RUNNING MULTICAST 
09-07 11:37:47.258   766  1442 I QC-NETMGR-LIB: Rcvd Netlink msg type [16]
09-07 11:37:47.258   766  1442 I QC-NETMGR-LIB: Received RTM_NEWLINK
09-07 11:37:47.258   766  1442 E QC-NETMGR-LIB: unrecognized ifindex 18, disable link
,09-07 11:37:47.268   554  1406 D Netd    : Iface p2p0 link down
09-07 11:37:47.268   766  1446 I QC-NETMGR-LIB: Received nl msg, recvmsg returned 1084
09-07 11:37:47.268   766  1446 I QC-NETMGR-LIB: Received command: ID=NETMGR_KIF_MSG_CMD, link=0
09-07 11:37:47.268   766  1442 I QC-NETMGR-LIB: Process command: ID=NETMGR_KIF_MSG_CMD, link=0, state=1
09-07 11:37:47.268   766  1442 I QC-NETMGR-LIB: Processing RTM_NEWLINK
09-07 11:37:47.268   766  1442 I QC-NETMGR-LIB: Metainfo:  Index=18 Family=0 Type=0x1 Change=[0x0] Flags=[0x1003]UP BROADCAST MULTICAST 
09-07 11:37:47.268   766  1442 I QC-NETMGR-LIB: Rcvd Netlink msg type [16]
09-07 11:37:47.268   766  1442 I QC-NETMGR-LIB: Received RTM_NEWLINK
09-07 11:37:47.268   766  1442 E QC-NETMGR-LIB: unrecognized ifindex 18, disable link
,09-07 11:37:47.458  6474  6474 I wpa_supplicant: P2P: Set prekey state (NONE -> NONE)
,09-07 11:37:47.468  1250  1623 D WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:2
,09-07 11:37:47.468  1250  1623 E WifiStateMachine: Deffering msg in Supplicant Starting State131085
,09-07 11:37:47.468  1250  1623 D WifiNative-wlan0: callSECApiBoolean - ID [301]
09-07 11:37:47.468  6474  6474 I wpa_supplicant: HOTSPOT20_ENABLE called ON
09-07 11:37:47.468  6474  6474 I wpa_supplicant: Blacklist: Clear (all) 
,09-07 11:37:47.478   766  1446 I QC-NETMGR-LIB: Received nl msg, recvmsg returned 1084
09-07 11:37:47.478   554  1406 D Netd    : Iface p2p0 link down
09-07 11:37:47.478   766  1446 I QC-NETMGR-LIB: Received command: ID=NETMGR_KIF_MSG_CMD, link=0
09-07 11:37:47.478   766  1442 I QC-NETMGR-LIB: Process command: ID=NETMGR_KIF_MSG_CMD, link=0, state=1
09-07 11:37:47.478   766  1442 I QC-NETMGR-LIB: Processing RTM_NEWLINK
09-07 11:37:47.478   766  1442 I QC-NETMGR-LIB: Metainfo:  Index=18 Family=0 Type=0x1 Change=[0x0] Flags=[0x1003]UP BROADCAST MULTICAST 
09-07 11:37:47.478   766  1442 I QC-NETMGR-LIB: Rcvd Netlink msg type [16]
09-07 11:37:47.478   766  1442 I QC-NETMGR-LIB: Received RTM_NEWLINK
09-07 11:37:47.478   766  1442 E QC-NETMGR-LIB: unrecognized ifindex 18, disable link
,09-07 11:37:47.488  6474  6474 I wpa_supplicant: wlan0: Setting scan request: 0 sec 0 usec
,09-07 11:37:47.488  6474  6474 I wpa_supplicant: wlan0: Skip scan - bUseNetwork false
,09-07 11:37:47.498  1250  1623 D WifiNative-wlan0: callSECApiInt - ID [210]
,09-07 11:37:47.498  1250  1250 D HS20StateMachine: Broadcast Received: android.net.wifi.WIFI_STATE_CHANGED
09-07 11:37:47.498  1250  1625 D HS20StateMachine: WIFI_STATE_ENABLED
09-07 11:37:47.498  1250  1625 D HS20StateMachine: reloadCredentialsToSupplicant
09-07 11:37:47.498  1250  1625 D HotspotDBHandler: getCredentialIds
09-07 11:37:47.498  1250  1250 I WifiHs20Service: Broadcast received:android.net.wifi.WIFI_STATE_CHANGED
,09-07 11:37:47.498  1250  1628 I WifiHs20Service: Message received 5011
,09-07 11:37:47.498  1250  1631 D ConnectivityManager: getMobileDataEnabled()+ subId=2147483643
09-07 11:37:47.498  1694  2100 D NetworkController: onReceive: intent=Intent { act=android.net.wifi.WIFI_STATE_CHANGED flg=0x4000010 bqHint=4 VirtualScreenParam=Params{mDisplayId=-1, null, mFlags=0x00000000)} (has extras) }
09-07 11:37:47.498  1694  1694 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
09-07 11:37:47.498  1944  1966 D PhoneInterfaceManager: [PhoneIntfMgr] getDataEnabled: subId=2147483643 phoneId=0
09-07 11:37:47.498  1694  1694 D HotspotTile: onReceive : 3, 0
09-07 11:37:47.498  1944  1966 D PhoneInterfaceManager: [PhoneIntfMgr] getDataEnabled: subId=2147483643 retVal=true
09-07 11:37:47.498  1250  1631 D ConnectivityManager: getMobileDataEnabled()- subId=2147483643 retVal=true
09-07 11:37:47.498  1250  1623 D WifiConfigStore: Loading config and enabling all networks 
,09-07 11:37:47.508  1250  1378 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{693641d u-1 android.net.wifi.WIFI_STATE_CHANGED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{9925d68 5989:com.test.thalitest/u0a136}
,09-07 11:37:47.508  1694  2126 D QSTile.WifiTile: handleUpdateState  cb.changed 5 wifiEnabled : ON 
09-07 11:37:47.508  5989  5989 D BluetoothAdapter: STATE_ON
,09-07 11:37:47.508  6337  6347 D HotspotProvider: inside  query methodcontent://com.samsung.passpoint/hotspot_credentials
09-07 11:37:47.508  6337  6347 D HotspotProvider: CREDENTIAL
09-07 11:37:47.508  6337  6347 D HotspotProvider: No prepend tags
,09-07 11:37:47.518  1694  1694 D QSTileView: handleLabelStateChanged() label = Wi-Fi cellWidth 148
09-07 11:37:47.518  5989  5989 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-07 11:37:47.518  5989  5989 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-07 11:37:47.518  5989  5989 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-07 11:37:47.518  5989  5989 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-07 11:37:47.518  5989  5989 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-07 11:37:47.518  5989  5989 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-07 11:37:47.518  5989  5989 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-07 11:37:47.518  5989  5989 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-07 11:37:47.518  1250  1625 D HS20StateMachine: CMD_HOTSPOT20_ENABLE : 
09-07 11:37:47.518  1250  1625 D HS20StateMachine: enter : DiscoveringState
,09-07 11:37:47.518  5989  5989 D BluetoothAdapter: STATE_ON
,09-07 11:37:47.518  1250  1623 I WifiConfigStore: "NG700" is a verified password AP: true
09-07 11:37:47.518  5989  5989 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-07 11:37:47.518  1250  1623 E WifiConfigStore: Not a HS20
,09-07 11:37:47.528  1250  1623 D WifiConfigStore: loaded 0 passpoint configs
,09-07 11:37:47.528  1250  1623 E WifiConfigStore: Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
09-07 11:37:47.528  1250  1623 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000
,09-07 11:37:47.528  1250  1623 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 1
09-07 11:37:47.528  1250  1623 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK
09-07 11:37:47.528  1250  1623 D WifiConfigStore: setNetworkPriorityDefault: networkId = 0, priority = 1
,09-07 11:37:47.528  1250  1250 I WifiHs20Service: Broadcast received:android.net.wifi.CONFIGURED_NETWORKS_CHANGE
09-07 11:37:47.528  1250  1250 D WifiHs20Service: reason: 2
09-07 11:37:47.528  1250  1623 D WifiNative-wlan0: callSECApiInt - ID [65]
09-07 11:37:47.528  5989  5989 D BluetoothAdapter: STATE_ON
09-07 11:37:47.528  1250  1628 I WifiHs20Service: Message received 5014
09-07 11:37:47.528  1250  1628 E WifiHs20Service: received HS20_UTILITY_ACTION_TYPE_HS20_CONFIGURATION_CHANGED
09-07 11:37:47.528  1250  1628 E WifiHs20Service: The changed config is NULL
,09-07 11:37:47.528  5989  5989 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-07 11:37:47.528  5989  5989 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-07 11:37:47.528  5989  5989 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-07 11:37:47.528  5989  5989 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-07 11:37:47.528  5989  5989 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-07 11:37:47.528  5989  5989 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-07 11:37:47.528  5989  5989 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-07 11:37:47.528  5989  5989 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-07 11:37:47.528  1250  1623 D WifiNative-wlan0: callSECApiBoolean - ID [13]
09-07 11:37:47.528  5989  5989 D BluetoothAdapter: STATE_ON
09-07 11:37:47.528  6474  6474 I wpa_supplicant: USE_NETWORK : USE_NETWORK ON
09-07 11:37:47.528  6474  6474 I wpa_supplicant: resume autoscan
09-07 11:37:47.528  6474  6474 I wpa_supplicant: autoscan_samsung_exponential_notify_scan : scan_interval = 8
09-07 11:37:47.528  6474  6474 I wpa_supplicant: autoscan: autoscan_notify_scan, scan_interval = 8
09-07 11:37:47.528  6474  6474 I wpa_supplicant: wlan0: Setting scan request: 8 sec 0 usec
09-07 11:37:47.528  6474  6474 I wpa_supplicant: reset timer : RESET_TIMER 0
09-07 11:37:47.528  6474  6474 I wpa_supplicant: P2P: Current p2p state = IDLE
09-07 11:37:47.528  6474  6474 I wpa_supplicant: First Scan Start
09-07 11:37:47.528  6474  6474 I wpa_supplicant: Scan requested (ret=0) - scan timeout 30 seconds
09-07 11:37:47.528  1250  1623 D WifiNative-wlan0: Setting external_sim to 1
09-07 11:37:47.538  1250  1623 D WifiStateMachine: [setCountryCode()] Airplane mode return !!!
09-07 11:37:47.538  1250  1623 D WifiStateMachine: Setting OUI to DA-A1-19
,09-07 11:37:47.538  5989  5989 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-07 11:37:47.538  6474  6474 I wpa_supplicant: bt_status is set be DISCONNECTED
09-07 11:37:47.538  1250  1994 D ConnectivityService: returning getNetworkInfo for network type 0 : [type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
09-07 11:37:47.538  1250  1994 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
09-07 11:37:47.538  1250  1994 D ConnectivityService: returning getNetworkInfo for network type 2 : [type: MOBILE_MMS[] - MOBILE_MMS, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
09-07 11:37:47.538  1250  1994 D ConnectivityService: returning getNetworkInfo for network type 3 : [type: MOBILE_SUPL[] - MOBILE_SUPL, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
09-07 11:37:47.538  1250  1994 D ConnectivityService: returning getNetworkInfo for network type 4 : [type: MOBILE_DUN[] - MOBILE_DUN, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
09-07 11:37:47.538  1250  1994 D ConnectivityService: returning getNetworkInfo for network type 5 : [type: MOBILE_HIPRI[] - MOBILE_HIPRI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
09-07 11:37:47.538  1250  1994 D ConnectivityService: returning getNetworkInfo for network type 7 : [type: BLUETOOTH[] - BLUETOOTH, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
09-07 11:37:47.538  1250  1994 D ConnectivityService: returning getNetworkInfo for network type 9 : [type: ETHERNET[] - ETHERNET, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
09-07 11:37:47.538  1250  1994 D ConnectivityService: returning getNetworkInfo for network type 10 : [type: MOBILE_FOTA[] - MOBILE_FOTA, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
09-07 11:37:47.538  1250  1994 D ConnectivityService: returning getNetworkInfo for network type 11 : [type: MOBILE_IMS[] - MOBILE_IMS, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
09-07 11:37:47.538  1250  1994 D ConnectivityService: returning getNetworkInfo for network type 12 : [type: MOBILE_CBS[] - MOBILE_CBS, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
09-07 11:37:47.538  1250  1994 D ConnectivityService: returning getNetworkInfo for network type 13 : [type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: false]
09-07 11:37:47.538  1250  1994 D ConnectivityService: returning getNetworkInfo for network type 14 : [type: MOBILE_IA[] - MOBILE_IA, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
09-07 11:37:47.538  1250  1994 D ConnectivityService: returning getNetworkInfo for network type 15 : [type: MOBILE_EMERGENCY[] - MOBILE_EMERGENCY, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
09-07 11:37:47.538  1250  1994 D ConnectivityService: returning getNetworkInfo for network type 17 : [type: VPN[] - VPN, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isA,vailable: true]
09-07 11:37:47.538  1250  1623 E WifiNative-wlan0: do suspend true
09-07 11:37:47.538  1250  1964 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{693641d u-1 android.net.wifi.WIFI_STATE_CHANGED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{6f787ab 6209:com.samsung.android.securitylogagent/1000}
09-07 11:37:47.538  1250  1622 D WifiP2pService: P2pDisabledState{ what=131203 }
,09-07 11:37:47.538  1250  1623 D WifiNative-HAL: Failing getSupportedFeatureset because HAL isn't started
09-07 11:37:47.538  1250  1623 D WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:3
,09-07 11:37:47.538  1250  1649 E WifiScanningService: could not start HAL
09-07 11:37:47.538  1250  1623 D WifiStateMachine: [FCC]Airplane on, setFccChannel(0)!!!
09-07 11:37:47.538  1250  1623 D WifiStateMachine: setFccChannelNative: channel = 0
09-07 11:37:47.538  1250  1623 D WifiNative-wlan0: callSECApiInt - ID [230]
09-07 11:37:47.538  1250  1250 D RttService: SCAN_AVAILABLE : 3
09-07 11:37:47.538  1250  1650 D RttService: DefaultState got{ when=0 what=160512 target=com.android.internal.util.StateMachine$SmHandler }
09-07 11:37:47.548   554  1414 D CommandListener: Setting iface cfg
09-07 11:37:47.548   554  1414 D CommandListener: Trying to bring up p2p0
,09-07 11:37:47.548  1250  1622 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
09-07 11:37:47.548  1250  1622 D SecContentProvider: insert(), uri = 2
,09-07 11:37:47.548  1250  1622 D WifiP2pService: P2pEnablingState
09-07 11:37:47.548  1250  1622 D WifiP2pService: P2pEnablingState{ what=147457 }
,09-07 11:37:47.548  1250  1622 D SecContentProvider: insert(), uri = 2
09-07 11:37:47.548  1250  1622 D WifiP2pService: P2p socket connection successful
09-07 11:37:47.548  1250  1622 D WifiP2pService: P2pEnabledState
09-07 11:37:47.548  1250  1622 D WifiP2pService: sending p2p connection changed broadcast: DISCONNECTED
09-07 11:37:47.548  1250  1630 E ConnectivityService: updateNetworkInfo()
09-07 11:37:47.548  1250  1630 D ConnectivityService: ignoring duplicate network state non-change. WIFI_P2P, state = DISCONNECTED
09-07 11:37:47.548  1250  1250 E WifiStateMachine: BroadcastReceiver : WIFI_P2P_STATE_CHANGED_ACTION is : android.net.wifi.p2p.STATE_CHANGED
09-07 11:37:47.548  1250  1417 D WifiDisplayController: Received WIFI_P2P_STATE_CHANGED_ACTION: enabled=true
09-07 11:37:47.548  1250  1417 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false, mScanRequestedInConnected = false
09-07 11:37:47.548  1250  1417 D WifiDisplayController: disconnect
09-07 11:37:47.548  1250  1417 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,09-07 11:37:47.558  1250  1623 D SecContentProvider2: query(), uri = 20 selection = getPromptCredentialsEnabled
,09-07 11:37:47.558  1694  1694 D SoundPathController: onReceive - android.hardware.display.action.WIFI_DISPLAY_STATUS_CHANGED
,09-07 11:37:47.558  1694  1694 D ApMirroringController: onReceive android.hardware.display.action.WIFI_DISPLAY_STATUS_CHANGED
,09-07 11:37:47.558  1250  1310 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
09-07 11:37:47.558  1694  1694 D AllShareCastTile: onReceive : android.hardware.display.action.WIFI_DISPLAY_STATUS_CHANGED
,09-07 11:37:47.558  1694  1694 D AllShareCastTile: wifi display status changed! scanstate : 0, ActiveDisplayState : 0
,09-07 11:37:47.558  6474  6474 I wpa_supplicant: P2P: Set Samsung Discovery Icon = 512
09-07 11:37:47.558  1250  1417 D WifiDisplayController: Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
09-07 11:37:47.558  1250  1417 I WifiDisplayAdapter: onP2pDisconnected
09-07 11:37:47.558  1250  1417 D IpRemoteDisplayController: disconnectWfdBridgeServer
09-07 11:37:47.558  1250  1417 D IpRemoteDisplayController: WfdBridgeServer is already null
,09-07 11:37:47.568  1694  1694 D WifiP2pController: onReceive android.net.wifi.p2p.CONNECTION_STATE_CHANGE
,09-07 11:37:47.568  6474  6474 I wpa_supplicant: P2P: Set Samsung Discovery name = 
,09-07 11:37:47.568  1250  1990 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{b0a692 u-1 android.net.wifi.p2p.CONNECTION_STATE_CHANGE qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{a3d25fa 6197:com.samsung.android.app.FileShareClient/5005}
09-07 11:37:47.568  6197  6197 D FileShare-Client: ClientBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,09-07 11:37:47.568  1250  1623 D SecContentProvider2: query(), uri = 20 selection = getPromptCredentialsEnabled
,09-07 11:37:47.568  6197  6197 D FileShare-Client: ClientBroadcastReceiver.onReceive - disconnected
,09-07 11:37:47.568  6197  6197 D FileShare-Client: Outbound.stopDelayTimer - 
09-07 11:37:47.568  1250  2127 E IzatSvc_OSObserver: I/LocTech-Label :: OSOBSERVER :: Data Items In
09-07 11:37:47.568  1250  2127 E IzatSvc_OSObserver: I/LocTech-Value :: Data Item Value: Attach state: 3, Mac address valid: false, AP MAC address: [00:00:00:00:00:00], Wifi-Ap SSID Valid: false, SSID: 
,09-07 11:37:47.568  1944  1963 E PhoneInterfaceManager: [PhoneIntfMgr] getIccId: ICC ID is null or empty.
,09-07 11:37:47.578  1250  1990 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{b0a692 u-1 android.net.wifi.p2p.CONNECTION_STATE_CHANGE qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{cdffcb4 5678:com.samsung.android.app.FileShareServer/5005}
,09-07 11:37:47.578  5678  5678 D FileShare-Server: ServerBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,09-07 11:37:47.578  1250  2127 E IzatSvc_OSObserver: I/LocTech-Label :: OSOBSERVER :: Data Items In
09-07 11:37:47.578  1250  2127 E IzatSvc_OSObserver: I/LocTech-Value :: Data Item Value: Attach state: 3, Mac address valid: false, AP MAC address: [00:00:00:00:00:00], Wifi-Ap SSID Valid: false, SSID: 
,09-07 11:37:47.578  5678  5678 V QC40_FileShareUiAdapter: isSupportedCommonUi [enabled]true
,09-07 11:37:47.578  5678  5678 D QC40_FileShareUiAdapter: isSupportedCommonUi [appState]0
,09-07 11:37:47.588  1250  1622 E WifiP2pService: Failed to set my phone number info into probe response
,09-07 11:37:47.588  1250  1622 D WifiNative-p2p0: p2pGetDeviceAddress
,09-07 11:37:47.588  1250  1622 D WifiNative-p2p0: p2pGetDeviceAddress returning 46:78:3e:eb:95:ef
,09-07 11:37:47.588  1250  1622 D WifiP2pService: DeviceAddress: 46:95:ef
09-07 11:37:47.588  1250  1417 D WifiDisplayController: Received WIFI_P2P_THIS_DEVICE_CHANGED_ACTION: mThisDevice= Device: [Tablet] Galaxy Tab S2
09-07 11:37:47.588  1250  1417 D WifiDisplayController:  deviceAddress: 46:78:3e:eb:95:ef
09-07 11:37:47.588  1250  1417 D WifiDisplayController:  primary type: 1-0050F204-9
09-07 11:37:47.588  1250  1417 D WifiDisplayController:  secondary type: null
09-07 11:37:47.588  1250  1417 D WifiDisplayController:  wps: 0
09-07 11:37:47.588  1250  1417 D WifiDisplayController:  grpcapab: 0
09-07 11:37:47.588  1250  1417 D WifiDisplayController:  devcapab: 0
09-07 11:37:47.588  1250  1417 D WifiDisplayController:  status: 3
09-07 11:37:47.588  1250  1417 D WifiDisplayController:  wfdInfo: null
09-07 11:37:47.588  1250  1417 D WifiDisplayController:  groupownerAddress: null
09-07 11:37:47.588  1250  1417 D WifiDisplayController:  GOdeviceName: null
09-07 11:37:47.588  1250  1417 D WifiDisplayController:  interfaceAddress: 
09-07 11:37:47.588  1250  1417 D WifiDisplayController:  SConnectInfo : null
09-07 11:37:47.588  1250  1417 D WifiDisplayController:  contactInfoHash : null
09-07 11:37:47.588  1250  1417 D WifiDisplayController:  ssDevInfo : 0
09-07 11:37:47.588  1250  1417 D WifiDisplayController:  iconIdx : 0
,09-07 11:37:47.598  1250  1263 I art     : Background sticky concurrent mark sweep GC freed 175131(11MB) AllocSpace objects, 95(2028KB) LOS objects, 26% free, 37MB/51MB, paused 3.550ms total 131.913ms
,09-07 11:37:47.608  1250  1622 D WifiP2pService: sending p2p persistent groups changed broadcast
,09-07 11:37:47.608  1250  1622 D WifiP2pService: InactiveState
,09-07 11:37:47.608  1250  1622 D WifiP2pService: InactiveState{ what=143376 }
09-07 11:37:47.608  1250  1622 D WifiP2pService: P2pEnabledState{ what=143376 }
09-07 11:37:47.608  1250  1622 E WifiP2pService: Airplane mode : skipped SET_COUNTRY_CODE
,09-07 11:37:47.738  1250  3581 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:836 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,09-07 11:37:48.488  5989  6040 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-07 11:37:48.488  5989  6482 D io.jxcore.node.OutgoingSocketThread: Server socket local port: 47775
09-07 11:37:48.488  5989  6482 I io.jxcore.node.OutgoingSocketThread: Now accepting connections...
,09-07 11:37:48.608  6474  6474 I wpa_supplicant: nl80211: Received scan results (27 BSSes)
09-07 11:37:48.608  6474  6474 I wpa_supplicant: autoscan_samsung_exponential_notify_scan : scan_interval = 8
09-07 11:37:48.608  6474  6474 I wpa_supplicant: autoscan: autoscan_notify_scan, scan_interval = 8
09-07 11:37:48.608  6474  6474 I wpa_supplicant: wlan0: Setting scan request: 8 sec 0 usec
09-07 11:37:48.608  6474  6474 I wpa_supplicant:    allow  - level is under -85dBm [-45] or selected nid [-1] [0]
,09-07 11:37:48.618  6474  6474 I wpa_supplicant:  selected from pick network BSS F4.99.3E ssid='NG700' et= 090,gp=03,cu=987654321,sc=987654321
,09-07 11:37:48.618  6474  6474 I wpa_supplicant:    allow  - level is under -85dBm [-45] or selected nid [-1] [0]
,09-07 11:37:48.618  6474  6474 I wpa_supplicant: wlan0: Trying to associate with SSID 'NG700'
,09-07 11:37:48.618  1250  6479 D WifiMonitor: didn't find BSSID Trying to associate with SSID 'NG700'
,09-07 11:37:48.648  1250  1623 D SecContentProvider2: query(), uri = 20 selection = getPromptCredentialsEnabled
,09-07 11:37:48.648  1250  1378 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{4e39863 u-1 android.net.wifi.SCAN_RESULTS qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{743a74c 1694:com.android.systemui/u0a46}
,09-07 11:37:48.648  1250  2127 E IzatSvc_OSObserver: I/LocTech-Label :: OSOBSERVER :: Data Items In
09-07 11:37:48.648  1250  2127 E IzatSvc_OSObserver: I/LocTech-Value :: Data Item Value: Attach state: 5, Mac address valid: false, AP MAC address: [00:00:00:00:00:00], Wifi-Ap SSID Valid: false, SSID: 
,09-07 11:37:48.708   766  1446 I QC-NETMGR-LIB: Received nl msg, recvmsg returned 320
09-07 11:37:48.708   766  1446 I QC-NETMGR-LIB: Received command: ID=NETMGR_KIF_MSG_CMD, link=0
09-07 11:37:48.708  6474  6474 E wpa_supplicant: Cmd 35605 not handled
09-07 11:37:48.708   766  1446 I QC-NETMGR-LIB: Received nl msg, recvmsg returned 188
09-07 11:37:48.708   766  1446 I QC-NETMGR-LIB: Received command: ID=NETMGR_KIF_MSG_CMD, link=0
09-07 11:37:48.708   766  1446 I QC-NETMGR-LIB: Received nl msg, recvmsg returned 72
09-07 11:37:48.708   766  1442 I QC-NETMGR-LIB: Process command: ID=NETMGR_KIF_MSG_CMD, link=0, state=1
09-07 11:37:48.708   766  1442 I QC-NETMGR-LIB: Processing RTM_NEWLINK
09-07 11:37:48.708   766  1446 I QC-NETMGR-LIB: Received command: ID=NETMGR_KIF_MSG_CMD, link=0
09-07 11:37:48.708   766  1446 I QC-NETMGR-LIB: Received nl msg, recvmsg returned 1084
09-07 11:37:48.708   766  1442 I QC-NETMGR-LIB: Metainfo:  Index=17 Family=0 Type=0x1 Change=[0x0] Flags=[0x1003]UP BROADCAST MULTICAST 
09-07 11:37:48.708   766  1442 I QC-NETMGR-LIB: Rcvd Netlink msg type [16]
09-07 11:37:48.708   766  1442 I QC-NETMGR-LIB: Received RTM_NEWLINK
09-07 11:37:48.708   766  1442 E QC-NETMGR-LIB: unrecognized ifindex 17, disable link
09-07 11:37:48.708   766  1446 I QC-NETMGR-LIB: Received command: ID=NETMGR_KIF_MSG_CMD, link=0
09-07 11:37:48.708   766  1442 I QC-NETMGR-LIB: Process command: ID=NETMGR_KIF_MSG_CMD, link=0, state=1
09-07 11:37:48.708   766  1442 I QC-NETMGR-LIB: Processing RTM_NEWLINK
09-07 11:37:48.708   766  1442 I QC-NETMGR-LIB: Metainfo:  Index=17 Family=0 Type=0x1 Change=[0x0] Flags=[0x1003]UP BROADCAST MULTICAST 
09-07 11:37:48.708   766  1442 I QC-NETMGR-LIB: Rcvd Netlink msg type [16]
09-07 11:37:48.708   766  1442 I QC-NETMGR-LIB: Received RTM_NEWLINK
09-07 11:37:48.708   766  1442 E QC-NETMGR-LIB: unrecognized ifindex 17, disable link
09-07 11:37:48.708   554  1406 D Netd    : Iface wlan0 link down
09-07 11:37:48.708   554  1406 D Netd    : Iface wlan0 link down
09-07 11:37:48.708   554  1406 D Netd    : Iface wlan0 link down
09-07 11:37:48.708   554  1406 D Netd    : Iface wlan0 link up
09-07 11:37:48.708   766  1442 I QC-NETMGR-LIB: Process command: ID=NETMGR_KIF_MSG_CMD, link=0, state=1
09-07 11:37:48.708   766  1442 I QC-NETMGR-LIB: Processing RTM_NEWLINK
09-07 11:37:48.708   766  1442 I QC-NETMGR-LIB: Metainfo:  Index=17 Family=0 Type=0x1 Change=[0x0] Flags=[0x1003]UP BROADCAST MULTICAST 
09-07 11:37:48.708   766  1442 I QC-NETMGR-LIB: Rcvd Netlink msg type [16]
09-07 11:37:48.708   766  1442 I QC-NETMGR-LIB: Received RTM_NEWLINK
09-07 11:37:48.708   766  1442 E QC-NETMGR-LIB: unrecognized ifindex 17, disable link
09-07 11:37:48.708   766  1442 I QC-NETMGR-LIB: Process command: ID=NETMGR_KIF_MSG_CMD, link=0, state=1
09-07 11:37:48.708   766  1442 I QC-NETMGR-LIB: Processing RTM_NEWLINK
09-07 11:37:48.708   766  1442 I QC-NETMGR-LIB: Metainfo:  Index=17 Family=0 Type=0x1 Change=[0x0] Flags=[0x11003]UP BROADCAST MULTICAST LOWER_UP 
09-07 11:37:48.708   766  1442 I QC-NETMGR-LIB: Rcvd Netlink msg type [16]
09-07 11:37:48.708   766  1442 I QC-NETMGR-LIB: Received RTM_NEWLINK
09-07 11:37:48.708   766  1442 E QC-NETMGR-LIB: unrecognized ifindex 17, disable link
,09-07 11:37:48.708  6474  6474 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
09-07 11:37:48.708  1250  1416 D Tethering: enter TetherInterfaceSM  and send tetherstatechangebroadcast
09-07 11:37:48.708  1250  1416 D Tethering: NAP Supported and not Wifi Model
,09-07 11:37:48.708  1250  1416 E Tethering: No numeric data,
,09-07 11:37:48.718  1250  1416 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
,09-07 11:37:48.718  1250  1620 D NtpTrustedTime: currentTimeMillis() cache hit
09-07 11:37:48.718  1250  1620 V NetworkStats: performPollLocked(flags=0x1)
,09-07 11:37:48.718  1250  1623 D SecContentProvider2: query(), uri = 20 selection = getPromptCredentialsEnabled
09-07 11:37:48.718  1694  1694 D HotspotTile: onReceive : android.net.conn.TETHER_STATE_CHANGED
,09-07 11:37:48.718  1694  1694 D HotspotTile: updateTetherState():false, false
,09-07 11:37:48.718  1250  1620 D NetworkStatsRecorder: entry.iface is null
09-07 11:37:48.718  1250  1620 D NtpTrustedTime: currentTimeMillis() cache hit
09-07 11:37:48.718  1250  1620 D NetworkStatsRecorder: entry.iface is null
09-07 11:37:48.718  1250  1620 D NetworkStatsRecorder: entry.iface is null
09-07 11:37:48.718  1250  1620 D NetworkStatsRecorder: entry.iface is null
,09-07 11:37:48.718  1250  1620 V NetworkStats: performPollLocked() took 5ms
09-07 11:37:48.718  1250  1378 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{f0675ea u-1 android.net.conn.TETHER_STATE_CHANGED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{667d8b1 1250:system/1000}
,09-07 11:37:48.728  1250  2127 E IzatSvc_OSObserver: I/LocTech-Label :: OSOBSERVER :: Data Items In
,09-07 11:37:48.728  1250  2127 E IzatSvc_OSObserver: I/LocTech-Value :: Data Item Value: Attach state: 6, Mac address valid: false, AP MAC address: [00:00:00:00:00:00], Wifi-Ap SSID Valid: false, SSID: 
,09-07 11:37:48.728  1250  1621 D NtpTrustedTime: currentTimeMillis() cache hit,
09-07 11:37:48.728  1250  1621 D NtpTrustedTime: currentTimeMillis() cache hit
,09-07 11:37:49.708  6474  6474 I wpa_supplicant: wlan0: WPA: RX message 1 of 4-Way Handshake from F4.99.3E (ver=2)
,09-07 11:37:49.708  6474  6474 I wpa_supplicant: wlan0: WPA: Sending EAPOL-Key 2/4
,09-07 11:37:49.708  1250  1623 D SecContentProvider2: query(), uri = 20 selection = getPromptCredentialsEnabled
,09-07 11:37:49.718  1250  2127 E IzatSvc_OSObserver: I/LocTech-Label :: OSOBSERVER :: Data Items In
09-07 11:37:49.718  1250  2127 E IzatSvc_OSObserver: I/LocTech-Value :: Data Item Value: Attach state: 7, Mac address valid: false, AP MAC address: [00:00:00:00:00:00], Wifi-Ap SSID Valid: false, SSID: 
,09-07 11:37:49.728  6474  6474 I wpa_supplicant: wlan0: WPA: RX message 3 of 4-Way Handshake from F4.99.3E (ver=2)
,09-07 11:37:49.728  6474  6474 I wpa_supplicant: wlan0: WPA: Sending EAPOL-Key 4/4
,09-07 11:37:49.728  6474  6474 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
09-07 11:37:49.728  6474  6474 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
09-07 11:37:49.728  6474  6474 I wpa_supplicant: Blacklist: Clear (temp) 
,09-07 11:37:49.728   766  1446 I QC-NETMGR-LIB: Received nl msg, recvmsg returned 1084
09-07 11:37:49.728   766  1446 I QC-NETMGR-LIB: Received command: ID=NETMGR_KIF_MSG_CMD, link=0
09-07 11:37:49.728   766  1442 I QC-NETMGR-LIB: Process command: ID=NETMGR_KIF_MSG_CMD, link=0, state=1
09-07 11:37:49.728   766  1442 I QC-NETMGR-LIB: Processing RTM_NEWLINK
09-07 11:37:49.728   766  1442 I QC-NETMGR-LIB: Metainfo:  Index=17 Family=0 Type=0x1 Change=[0x0] Flags=[0x11043]UP BROADCAST RUNNING MULTICAST LOWER_UP 
09-07 11:37:49.728   554  1406 D Netd    : Iface wlan0 link up
09-07 11:37:49.728   766  1442 I QC-NETMGR-LIB: Rcvd Netlink msg type [16]
09-07 11:37:49.728   766  1442 I QC-NETMGR-LIB: Received RTM_NEWLINK
09-07 11:37:49.728   766  1442 E QC-NETMGR-LIB: unrecognized ifindex 17, disable link
,09-07 11:37:49.738  1250  1623 D WifiNative-wlan0: callSECApiVoid - ID [50]
,09-07 11:37:49.748  1250  1623 V AlarmManager:  remove PendingIntent] PendingIntent{a985477: PendingIntentRecord{7a268e4 android broadcastIntent}}
09-07 11:37:49.748  1250  1623 D WifiNetworkAgent: NetworkAgent: Registering NetworkAgent
,09-07 11:37:49.748  1250  1250 D HS20StateMachine: Broadcast Received: android.net.wifi.STATE_CHANGE,
09-07 11:37:49.748  1250  1250 D HS20StateMachine: [type: WIFI[] - WIFI, state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
09-07 11:37:49.748  1250  1250 I WifiHs20Service: Broadcast received:android.net.wifi.STATE_CHANGE
09-07 11:37:49.748  1250  1628 I WifiHs20Service: Message received 5007
09-07 11:37:49.748  1250  1623 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{503}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,1048576,524288,1048576,4194240}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,09-07 11:37:49.748  1250  1630 E ConnectivityService: updateNetworkInfo()
09-07 11:37:49.748  1250  1630 D ConnectivityService: Got NetworkAgent Messenger
09-07 11:37:49.758  1250  1630 D ConnectivityService: NetworkAgentInfo [WIFI () - 503] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
09-07 11:37:49.758  1250  1630 D ConnectivityService: NetworkAgent connected
,09-07 11:37:49.758  1694  2100 D NetworkController: onReceive: intent=Intent { act=android.net.wifi.STATE_CHANGE flg=0x4000010 bqHint=4 VirtualScreenParam=Params{mDisplayId=-1, null, mFlags=0x00000000)} (has extras) },
,09-07 11:37:49.758  1944  1944 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.net.wifi.STATE_CHANGE
,09-07 11:37:49.758   554  1414 D CommandListener: Setting iface cfg
,09-07 11:37:49.758  1250  1378 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{da3368e u-1 android.net.wifi.STATE_CHANGE qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{e03cd16 6153:com.sec.android.diagmonagent/1000}
,09-07 11:37:49.758  6153  6153 I DIAGMON_AGENT: [lllIIIIIIlllIlIIIIII(51/llIIIIlllllIIllIIllI)] Receive broadcast: android.net.wifi.STATE_CHANGE
,09-07 11:37:49.758  6153  6153 I DIAGMON_AGENT: [lllIIIIIIlllIlIIIIII(52/llIIIIlllllIIllIIllI)] Receive broadcast:
09-07 11:37:49.758  6153  6153 I DIAGMON_AGENT: ./bssid: f4:f2:6d:22:99:3e
09-07 11:37:49.758  1250  1623 D WifiStateMachine: Start Dhcp Watchdog 2
09-07 11:37:49.768  6153  6153 W DIAGMON_AGENT: [lllIIIIIIlllIlIIIIII(31/llIIIIlllllIIllIIllI)] Network is changed and not available now, so don't do anything
,09-07 11:37:49.768  1250  1623 D SecContentProvider2: query(), uri = 20 selection = getPromptCredentialsEnabled
,09-07 11:37:49.768  1250  1990 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{da3368e u-1 android.net.wifi.STATE_CHANGE qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{7cc8669 6173:com.sec.app.RilErrorNotifier/1000}
,09-07 11:37:49.768  6173  6173 I PhoneErrorReceiver: onReceive
09-07 11:37:49.768  1250  1720 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
09-07 11:37:49.768  6173  6173 I MIPErrReceiver: isWiFiConnected
,09-07 11:37:49.768  1250  2127 E IzatSvc_OSObserver: I/LocTech-Label :: OSOBSERVER :: Data Items In
09-07 11:37:49.768  1250  2127 E IzatSvc_OSObserver: I/LocTech-Value :: Data Item Value: Attach state: 8, Mac address valid: false, AP MAC address: [00:00:00:00:00:00], Wifi-Ap SSID Valid: false, SSID: 
,09-07 11:37:49.778  1250  1986 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{da3368e u-1 android.net.wifi.STATE_CHANGE qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{195a0dd 5691:com.enhance.gameservice/u0a79}
,09-07 11:37:49.778  1694  2100 D NetworkController: onReceive: intent=Intent { act=android.net.wifi.RSSI_CHANGED flg=0x4000010 bqHint=4 VirtualScreenParam=Params{mDisplayId=-1, null, mFlags=0x00000000)} (has extras) }
,09-07 11:37:49.788  1250  1313 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{da3368e u-1 android.net.wifi.STATE_CHANGE qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{61e2025 6185:com.sec.knox.switcher/1000}
,09-07 11:37:49.788  6185  6185 I usagelog: received in receiver
09-07 11:37:49.788  6185  6185 I KnoxUsageLogPro: KnoxUsageReceiver onReceive :android.net.wifi.STATE_CHANGE myUserId=0
09-07 11:37:49.788  6185  6185 I KnoxUsageLogPro: premStatus:2
,09-07 11:37:49.788  1250  1623 D WifiNetworkAgent: NetworkAgent: NetworkAgent fully connected
09-07 11:37:49.788  6185  6185 I KnoxUsageLogPro: isEulaShown : false
09-07 11:37:49.788  1250  1630 D ConnectivityService: updateCapabilities: oldCap = [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps], newCap = [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -40]
09-07 11:37:49.788  6185  6185 I KnoxUsageLogPro: KnoxUsageReceiver onReceive : not Processible, just return
09-07 11:37:49.788  1250  1630 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 503]
09-07 11:37:49.788  1250  1630 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 503]; created=false
,09-07 11:37:49.788  1250  1623 E WifiNative-wlan0: do suspend false
,09-07 11:37:49.788  1250  1623 D SecContentProvider2: query(), uri = 20 selection = getPromptCredentialsEnabled
,09-07 11:37:49.788  1250  1622 D WifiP2pService: InactiveState{ what=143375 }
09-07 11:37:49.788  1250  1622 D WifiP2pService: P2pEnabledState{ what=143375 }
,09-07 11:37:49.798  1250  2127 E IzatSvc_OSObserver: I/LocTech-Label :: OSOBSERVER :: Data Items In
09-07 11:37:49.798  1250  2127 E IzatSvc_OSObserver: I/LocTech-Value :: Data Item Value: Attach state: 9, Mac address valid: true, AP MAC address: [f4:f2:6d:22:99:3e], Wifi-Ap SSID Valid: true, SSID: NG700
,09-07 11:37:49.798  1250  2146 E LocSvc_ApiV02: I/<--- void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*) line 131 QMI_LOC_NOTIFY_WIFI_ATTACHMENT_STATUS_REQ_V02
,09-07 11:37:49.808  6486  6486 E dhcpcd  : fopen `/system/etc/dhcpcd/dhcpcd.conf': No such file or directory
,09-07 11:37:49.818  6486  6486 I dhcpcd  : version 5.5.6 starting
,09-07 11:37:49.818  6486  6486 E dhcpcd  : fopen `/system/etc/dhcpcd/dhcpcd.conf': No such file or directory,
,09-07 11:37:49.898  6486  6486 I dhcpcd  : wlan0: sending IPv6 Router Solicitation,
09-07 11:37:49.898  6486  6486 I dhcpcd  : if(wlan0) info get Success. (MAC : F4.99.3E)
09-07 11:37:49.898  6486  6486 I dhcpcd  : bssid match
09-07 11:37:49.898  6486  6486 I dhcpcd  : wlan0: rebinding lease of 192.168.1.106
,09-07 11:37:50.068  6486  6486 I dhcpcd  : wlan0: acknowledged 192.168.1.106 from 192.168.1.1
,09-07 11:37:50.128  6486  6486 I dhcpcd  : wlan0: leased 192.168.1.106 for 172800 seconds
09-07 11:37:50.128   766  1446 I QC-NETMGR-LIB: Received nl msg, recvmsg returned 80
09-07 11:37:50.128   766  1446 I QC-NETMGR-LIB: Received command: ID=NETMGR_KIF_MSG_CMD, link=0
09-07 11:37:50.128   766  1442 I QC-NETMGR-LIB: Process command: ID=NETMGR_KIF_MSG_CMD, link=0, state=1
09-07 11:37:50.128   766  1442 I QC-NETMGR-LIB: Processing RTM_NEWADDR
09-07 11:37:50.128   766  1442 I QC-NETMGR-LIB: Metainfo:  Family=2 PrefixLen=24 Scope=0x0 Index=17 Flags=[0x80]PERMANENT 
09-07 11:37:50.128   766  1442 I QC-NETMGR-LIB: Attribute: PrefixIPv4 addr [192.168.1.106]
09-07 11:37:50.128   766  1442 I QC-NETMGR-LIB: Attribute: LocalIPv4 addr [192.168.1.106]
09-07 11:37:50.128   766  1442 I QC-NETMGR-LIB: Attribute: BroadcastIPv4 addr [192.168.1.255]
09-07 11:37:50.128   766  1442 I QC-NETMGR-LIB: Attribute: Label name wlan0
09-07 11:37:50.128   766  1442 I QC-NETMGR-LIB: Attribute: Address Cache Info - prefered=-1 valid=-1 cstamp=0x3fe3 tstamp=0x3fe3
09-07 11:37:50.128   766  1442 I QC-NETMGR-LIB: Rcvd Netlink msg type [20]
09-07 11:37:50.128   766  1442 E QC-NETMGR-LIB: unrecognized ifindex 17
,09-07 11:37:50.138  1250  1630 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 503]; created=false
,09-07 11:37:50.338   707   707 I MSM-irqbalance: Decided to move IRQ155 from CPU1 to CPU0
,09-07 11:37:50.598  1250  1623 E WifiNative-wlan0: do suspend true
,09-07 11:37:50.598  1250  1622 D WifiP2pService: InactiveState{ what=143375 }
09-07 11:37:50.598  1250  1622 D WifiP2pService: P2pEnabledState{ what=143375 }
,09-07 11:37:50.598  1250  1630 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 503]; created=false
09-07 11:37:50.598  1250  1623 D WifiStateMachine: WifiStateMachine: handleSuccessfulIpConfiguration and no scan results"NG700"WPA_PSK
09-07 11:37:50.598  1250  1623 D WifiStateMachine: VerifyingLinkState enter
09-07 11:37:50.598  1250  1630 D ConnectivityService: updateCapabilities: oldCap = [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -40], newCap = [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -40]
,09-07 11:37:50.608  1694  2100 D NetworkController: onReceive: intent=Intent { act=android.net.wifi.RSSI_CHANGED flg=0x4000010 bqHint=4 VirtualScreenParam=Params{mDisplayId=-1, null, mFlags=0x00000000)} (has extras) }
,09-07 11:37:50.608  1250  1630 E ConnectivityService: updateNetworkInfo()
09-07 11:37:50.608  1250  1250 D WifiNotificationController: SHOW_NOTI_MESSAGE : 9, visible : false, ssid : "NG700", targetSSID : null, netId : -1, titleType : -1
,09-07 11:37:50.608  1250  1630 D ConnectivityService: updateLinkProperties: newLp = {InterfaceName: wlan0 LinkAddresses: [192.168.1.106/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains:  MTU: 0 TcpBufferSizes: 524288,1048576,1048576,524288,1048576,4194240}, oldLp = null
09-07 11:37:50.608  1250  1630 D ConnectivityService: Adding iface wlan0 to network 503
,09-07 11:37:50.608  1250  1250 D HS20StateMachine: Broadcast Received: android.net.wifi.STATE_CHANGE
09-07 11:37:50.608  1250  1250 D HS20StateMachine: [type: WIFI[] - WIFI, state: CONNECTING/VERIFYING_POOR_LINK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
,09-07 11:37:50.608  1250  1250 I WifiHs20Service: Broadcast received:android.net.wifi.STATE_CHANGE
09-07 11:37:50.608  1250  1628 I WifiHs20Service: Message received 5007
09-07 11:37:50.618  1250  1642 D WifiWatchdogStateMachine: updateDnsLinkProperty: enter
09-07 11:37:50.618  1250  1642 D WifiWatchdogStateMachine.DnsPinger: setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.106/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains:  MTU: 0 TcpBufferSizes: 524288,1048576,1048576,524288,1048576,4194240}
09-07 11:37:50.618  1250  1642 D WifiWatchdogStateMachine.DnsResolver: setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.106/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains:  MTU: 0 TcpBufferSizes: 524288,1048576,1048576,524288,1048576,4194240}
09-07 11:37:50.618  1250  1642 D WifiWatchdogStateMachine.SingDnsChecker: setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.106/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains:  MTU: 0 TcpBufferSizes: 524288,1048576,1048576,524288,1048576,4194240}
09-07 11:37:50.618  1250  1642 D WifiWatchdogStateMachine.CaptivePortalDnsResolver: setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.106/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains:  MTU: 0 TcpBufferSizes: 524288,1048576,1048576,524288,1048576,4194240}
09-07 11:37:50.618  1694  2100 D NetworkController: onReceive: intent=Intent { act=android.net.wifi.STATE_CHANGE flg=0x4000010 bqHint=4 VirtualScreenParam=Params{mDisplayId=-1, null, mFlags=0x00000000)} (has extras) }
,09-07 11:37:50.618  1944  1944 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.net.wifi.STATE_CHANGE
,09-07 11:37:50.618  1250  1378 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{47934fd u-1 android.net.wifi.STATE_CHANGE qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{e03cd16 6153:com.sec.android.diagmonagent/1000}
09-07 11:37:50.618  1250  1642 I WifiManager: isCaptivePortalException
,09-07 11:37:50.618  1250  1642 D WifiStateMachine: isPackageRunning - top:com.test.thalitest.MainActivity
09-07 11:37:50.618  1250  1642 D WifiStateMachine: isPackageRunning - top:com.test.thalitest.MainActivity
09-07 11:37:50.618  1250  1642 D WifiWatchdogStateMachine: 3Captive portal check should be processed whether SNS option is on or off.
09-07 11:37:50.618  1250  1642 D WifiWatchdogStateMachine.CaptivePortalHandler: [checkCaptivePortal] - callbackHandler=Handler (com.android.server.wifi.WifiWatchdogStateMachine$CaptivePortalHandler) {ccbe81a}
09-07 11:37:50.618  1250  1642 I WifiManager: isCaptivePortalException
09-07 11:37:50.618  1250  1642 D WifiStateMachine: isPackageRunning - top:com.test.thalitest.MainActivity
09-07 11:37:50.618  1250  1642 D WifiStateMachine: isPackageRunning - top:com.test.thalitest.MainActivity
,09-07 11:37:50.618  6153  6153 I DIAGMON_AGENT: [lllIIIIIIlllIlIIIIII(51/llIIIIlllllIIllIIllI)] Receive broadcast: android.net.wifi.STATE_CHANGE
,09-07 11:37:50.618  6153  6153 I DIAGMON_AGENT: [lllIIIIIIlllIlIIIIII(52/llIIIIlllllIIllIIllI)] Receive broadcast:
09-07 11:37:50.618  6153  6153 I DIAGMON_AGENT: ./bssid: f4:f2:6d:22:99:3e
09-07 11:37:50.618  1250  1623 D WifiStateMachine: VerifyingLinkState GOOD_LINK_DETECTED: transition to CONNECTED
,09-07 11:37:50.618  6153  6153 W DIAGMON_AGENT: [lllIIIIIIlllIlIIIIII(31/llIIIIlllllIIllIIllI)] Network is changed and not available now, so don't do anything
,09-07 11:37:50.628  1250  2396 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{47934fd u-1 android.net.wifi.STATE_CHANGE qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{7cc8669 6173:com.sec.app.RilErrorNotifier/1000}
,09-07 11:37:50.628  6173  6173 I PhoneErrorReceiver: onReceive
09-07 11:37:50.628  6173  6173 I MIPErrReceiver: isWiFiConnected
,09-07 11:37:50.628  1250  1310 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
,09-07 11:37:50.628  1250  2327 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{47934fd u-1 android.net.wifi.STATE_CHANGE qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{195a0dd 5691:com.enhance.gameservice/u0a79}
,09-07 11:37:50.638  1250  1720 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{47934fd u-1 android.net.wifi.STATE_CHANGE qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{61e2025 6185:com.sec.knox.switcher/1000}
,09-07 11:37:50.638  6185  6185 I usagelog: received in receiver
09-07 11:37:50.638  6185  6185 I KnoxUsageLogPro: KnoxUsageReceiver onReceive :android.net.wifi.STATE_CHANGE myUserId=0
09-07 11:37:50.638  6185  6185 I KnoxUsageLogPro: premStatus:2
,09-07 11:37:50.638  6185  6185 I KnoxUsageLogPro: isEulaShown : false
,09-07 11:37:50.638  6185  6185 I KnoxUsageLogPro: KnoxUsageReceiver onReceive : not Processible, just return
09-07 11:37:50.638  1250  1630 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 503
09-07 11:37:50.638  1250  1250 D WifiNotificationController: SHOW_NOTI_MESSAGE : 9, visible : false, ssid : "NG700", targetSSID : null, netId : -1, titleType : -1
,09-07 11:37:50.638  1250  1630 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 503
,09-07 11:37:50.638  1250  1630 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network. 503
09-07 11:37:50.638  1250  1623 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,09-07 11:37:50.638  1250  1250 I WifiTrafficPoller: evaluateTrafficStatsPolling
09-07 11:37:50.638  1250  1623 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
09-07 11:37:50.638  1250  1250 I WifiTrafficPoller: mBoosterFLAG : 0
09-07 11:37:50.638  1250  1250 I WifiTrafficPoller: current booster mode : FullMode
09-07 11:37:50.638  1250  1250 I Wifi-SensorMonitor: enable sensor monitoring : true
09-07 11:37:50.638  1250  1630 E ConnectivityService: Unexpected mtu value: 0, wlan0
09-07 11:37:50.638  1250  1250 D SensorService: SensorEventConnection::SocketBufferSize, SystemSocketBufferSize - 4096, 8388608
09-07 11:37:50.638  1250  1630 D ConnectivityService: Setting Dns servers for network 503 to [/192.168.1.1]
,09-07 11:37:50.638  1250  1250 D SensorHAL: GRIP_WIFI  set_enable 
,09-07 11:37:50.648  1694  2100 D NetworkController: onReceive: intent=Intent { act=android.net.wifi.STATE_CHANGE flg=0x4000010 bqHint=4 VirtualScreenParam=Params{mDisplayId=-1, null, mFlags=0x00000000)} (has extras) }
,09-07 11:37:50.648  1944  1944 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.net.wifi.STATE_CHANGE
,09-07 11:37:50.648  1250  1994 D WifiStateMachine: SEC_COMMAND_ID_GET_FWS_OPEN_AP_CHECK : 0
09-07 11:37:50.648  1250  1964 D SecContentProvider2: query(), uri = 15 selection = getToastGravityEnabledState
09-07 11:37:50.648  1250  1378 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{e6ed5f2 u-1 android.net.wifi.STATE_CHANGE qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{e03cd16 6153:com.sec.android.diagmonagent/1000}
09-07 11:37:50.648  1250  1630 D NtpTrustedTime: currentTimeMillis() cache hit
09-07 11:37:50.648  1250  1630 V NetworkStats: updateIfacesLocked()
09-07 11:37:50.648  1250  1630 V NetworkStats: performPollLocked(flags=0x1)
09-07 11:37:50.658  6153  6153 I DIAGMON_AGENT: [lllIIIIIIlllIlIIIIII(51/llIIIIlllllIIllIIllI)] Receive broadcast: android.net.wifi.STATE_CHANGE
09-07 11:37:50.658  1250  1630 D NetworkStatsRecorder: entry.iface is null
09-07 11:37:50.658  1250  1630 D NetworkStatsRecorder: entry.iface is null
09-07 11:37:50.658  1250  1630 D NetworkStatsRecorder: entry.iface is null
09-07 11:37:50.658  1250  1630 D NetworkStatsRecorder: entry.iface is null
09-07 11:37:50.658  1250  1630 V NetworkStats: performPollLocked() took 5ms
09-07 11:37:50.658  1250  1630 D NtpTrustedTime: currentTimeMillis() cache hit
09-07 11:37:50.658  1250  2674 D SecContentProvider2: query(), uri = 15 selection = getToastEnabledState
09-07 11:37:50.658  1250  1630 D ConnectivityService: getAllNetworkState networkCapability  = [ Transports: WIFI Capabilities: WIFI_P2P&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
09-07 11:37:50.658  6153  6153 I DIAGMON_AGENT: [lllIIIIIIlllIlIIIIII(52/llIIIIlllllIIllIIllI)] Receive broadcast:
09-07 11:37:50.658  6153  6153 I DIAGMON_AGENT: ./bssid: f4:f2:6d:22:99:3e
09-07 11:37:50.658  1250  1630 D ConnectivityService: getAllNetworkState networkCapability  = [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -40]
09-07 11:37:50.658  1250  1630 D ConnectivityService: Not required to send intent.
09-07 11:37:50.658  1250  1630 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 503]
09-07 11:37:50.658  1250  1630 E ConnectivityService: updateNetworkInfo()
09-07 11:37:50.658  1250  1630 D ConnectivityService: ignoring duplicate network state non-change. WIFI, state = CONNECTING
09-07 11:37:50.658  1250  1630 D ConnectivityService: NetworkAgentInfo [WIFI () - 503] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -40]
09-07 11:37:50.658  1250  1621 D NtpTrustedTime: currentTimeMillis() cache hit
09-07 11:37:50.658  1250  1630 V NetworkStats: updateIfacesLocked()
09-07 11:37:50.658  1250  1621 D NtpTrustedTime: currentTimeMillis() cache hit
09-07 11:37:50.658  1250  1630 V NetworkStats: performPollLocked(flags=0x1)
09-07 11:37:50.658  1250  1630 D NtpTrustedTime: currentTimeMillis() cache hit
09-07 11:37:50.658  1250  1313 D SecContentProvider2: query(), uri = 15 selection = getToastShowPackageNameState
09-07 11:37:50.658  6153  6153 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:836 android.content.ContextWrapper.sendBroadcast:410 android.content.ContextWrapper.sendBroadcast:410 com.sec.android.diagmonagent.DiagMonConnectivityChangeReciever.onReceive:19 android.app.ActivityThread.handleReceiver:3637 
09-07 11:37:50.658  1250  1630 D NetworkStatsRecorder: entry.iface is null
09-07 11:37:50.658  1250  1630 D NetworkStatsRecorder: entry.iface is null
09-07 11:37:50.658  1250  1630 D NtpTrustedTime: currentTimeMillis() cache hit
09-07 11:37:50.658  1250  1630 D NetworkStatsRecorder: entry.iface is null
09-07 11:37:50.658  1250  1630 D NetworkStatsRecorder: entry.iface is null
09-07 11:37:50.658  1250  1630 V NetworkStats: performPollLocked() took 3ms
09-07 11:37:50.658  1250  1630 D ConnectivityService: getAllNetworkState networkCapability  = [ Transports: WIFI Capabilities: WIFI_P2P&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
09-07 11:37:50.658  1250  1630 D ConnectivityService: getAllNetworkState networkCapability  = [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -40]
09-07 11:37:50.658  1250  1630 D ConnectivityService: scheduleUnvalidatedPrompt 503
09-07 11:37:50.658  1250  6484 D NetworkMonitor/NetworkAgentInfo [WIFI () - 503]: DefaultState{ when=0 what=532481 target=com.android.internal.util.StateMachine$SmHandler }
09-07 11:37:50.658  1250  1630 D ConnectivityService: updateSignalStrengthThresholds: CONNECT, sending [] to NetworkAgentInfo [WIFI () - 503]
09-07 11:37:50.658  1250  6484 D NetworkMonitor/NetworkAgentInfo [WIFI () - 503]: Connected
09-07 11:37:50.658  1250  1630 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 503]
09-07 11:37:50.658  1250  6484 D NetworkMonitor: registerReceiver Captive portal receiver
09-07 11:37:50.658  1250  1630 D ConnectivityService:  network has: NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{503}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.106/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains:  MTU: 0 TcpBufferSizes: 524288,1048576,1048576,524288,1048576,4194240}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -40]}  Score{20}  everValidated{false}  lastValidated{false}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
09-07 11:37:50.658  1250  1630 D ConnectivityService:   checking if request is: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] satisfies: true nri.isRequest: true
09-07 11:37:50.658  1250  1623 D WifiNetworkAgent: NetworkAgent: Received signal strength thresholds: []
09-07 11:37:50.658  1250  1623 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
09-07 11:37:50.658  1250  1630 D ConnectivityManager: getMobileDataEnabled()+ subId=2147483643
09-07 11:37:50.668  1250  1621 D NtpTrustedTime: currentTimeMillis() cache hit
09-07 11:37:50.668  1250  1621 D NtpTrustedTime: currentTimeMillis() cache hit
09-07 11:37:50.668  1694  2100 D ViewRootImpl: #1 mView = android.widget.LinearLayout{b8e5145 V.E...... ......I. 0,0-0,0 #102039d android:id/toast_layout_root}
09-07 11:37:50.668  1694  2126 D QSTile.WifiTile: handleUpdateState  cb.changed 14 wifiEnabled : ON cb.enabledDesc NG700
09-07 11:37:50.668  1944  2290 D PhoneInterfaceManager: [PhoneIntfMgr] getDataEnabled: subId=2147483643 phoneId=0
09-07 11:37:50.668  1250  1310 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{e6ed5f2 u-1 android.net.wifi.STATE_CHANGE qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{7cc8669 6173:com.sec.app.RilErrorNotifier/1000}
09-07 11:37:50.668  1944  2290 D PhoneInterfaceManager: [PhoneIntfMgr] getDataEnabled: subId=2147483643 retVal=true
09-07 11:37:50.668  1250  1630 D ConnectivityManager: getMobileDataEnabled()- subId=2147483643 retVal=true
09-07 11:37:50.668  1250  1630 D ConnectivityService: currentScore = 0, newScore = 20
09-07 11:37:50.668  1250  1630 D ConnectivityService: rematch for NetworkAgentInfo [WIFI () - 503]
09-07 11:37:50.668  1250  1630 D ConnectivityService:    accepting network in place of null
09-07 11:37:50.668  1250  1630 D ConnectivityService: sending new Min Network Score(20): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-07 11:37:50.668  1250  1622 D WIFI_P2P: new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-07 11:37:50.668  1250  1622 D WIFI_P2P:   my score=60, my filter=[ Transports: WIFI Capabilities: WIFI_P2P&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
09-07 11:37:50.668  1250  1630 D ConnectivityService:   checking if request is: NetworkRequest [ id=4, legacyType=-1, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] satisfies: true nri.isRequest: false
09-07 11:37:50.668  1250  1622 D WIFI_P2P: evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= false
09-07 11:37:50.668  1250  1630 D ConnectivityService:   checking if request is: NetworkRequest [ id=7, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] satisfies: true nri.isRequest: false
09-07 11:37:50.668  1250  1622 D WIFI_P2P: evalRequest
09-07 11:37:50.668  1250  1630 D ConnectivityService:   checking if request is: NetworkRequest [ id=3, legacyType=-1, [ Transports: CELLULAR Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] satisfies: false nri.isRequest: false
09-07 11:37:50.668  1250  1622 D WIFI_P2P:   done
09-07 11:37:50.668  1250  1630 D ConnectivityService:   checking if request is: NetworkRequest [ id=6, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] satisfies: true nri.isRequest: false
09-07 11:37:50.668  1250  1630 D ConnectivityService:   checking if request is: NetworkRequest [ id=5, legacyType=-1, [] ] satisfies: true nri.isRequest: false
09-07 11:37:50.668  1250  1623 D WIFI    : new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-07 11:37:50.668  1250  1623 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
09-07 11:37:50.668  1250  1623 D WIFI    : evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= true
09-07 11:37:50.668  1250  1630 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{503}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.106/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains:  MTU: 0 TcpBufferSizes: 524288,1048576,1048576,524288,1048576,4194240}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -40]}  Score{20}  everValidated{false}  lastValidated{false}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
09-07 11:37:50.668  1250  1623 D WIFI    : evalRequest
09-07 11:37:50.668  1250  2396 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
09-07 11:37:50.668  1250  1623 D WIFI    :   done
09-07 11:37:50.668  1250  1623 D WIFI    : new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-07 11:37:50.668  1250  1623 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
09-07 11:37:50.668  6173  6173 I PhoneErrorReceiver: onReceive
09-07 11:37:50.668  6173  6173 I MIPErrReceiver: isWiFiConnected
09-07 11:37:50.668  1250  1623 D WIFI    : evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= true
09-07 11:37:50.668  1250  1623 D WIFI    : evalRequest
09-07 11:37:50.668  1250  1623 D WIFI    :   done
09-07 11:37:50.668  1250  1623 D WIFI_UT : new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-07 11:37:50.668  1250  1623 D WIFI_UT :   my score=2147483647, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
09-07 11:37:50.668  1250  1623 D WIFI_UT : evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= true
09-07 11:37:50.668  1250  1623 D WIFI_UT : evalRequest
09-07 11:37:50.668  1250  1623 D WIFI_UT :   done
09-07 11:37:50.668  1250  1651 D Ethernet: new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-07 11:37:50.668  1250  1651 D Ethernet:   my score=-1, my filter=[ Transports: ETHERNET Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=100000Kbps LinkDnBandwidth>=100000Kbps]
09-07 11:37:50.668  1250  1651 D Ethernet: evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= false
09-07 11:37:50.668  1250  1651 D Ethernet: evalRequest
09-07 11:37:50.668  1250  1651 D Ethernet:   done
09-07 11:37:50.668  1250  6484 D NetworkMonitor/NetworkAgentInfo [WIFI () - 503]: EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
09-07 11:37:50.668  1250  6484 D NetworkMonitor/NetworkAgentInfo [WIFI () - 503]: Validated
09-07 11:37:50.668  1250  2327 V MARsPolicyManager: handelAlertToastWindowStarted pkgName = com.android.systemui
09-07 11:37:50.668  1250  1720 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{e6ed5f2 u-1 android.net.wifi.STATE_CHANGE qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{195a0dd 5691:com.enhance.gameservice/u0a79}
09-07 11:37:50.678  1250  1250 D SensorHAL: sx9310_grip_wifi: power-on.
09-07 11:37:50.678  1250  1250 D SensorManager: registerListener :: 17, SX9310 Grip Sensor wifi, 200000, 0,  
09-07 11:37:50.678  1250  1250 I Wifi-SensorMonitor: disable powerbackoff
09-07 11:37:50.678  1250  1250 D WifiNative-wlan0: callSECApiInt - ID [70]
09-07 11:37:50.678  1250  1250 D WifiNative-wlan0: callSECApiVoid - ID [212]
09-07 11:37:50.678  1250  1964 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{e6ed5f2 u-1 android.net.wifi.STATE_CHANGE qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{61e2025 6185:com.sec.knox.switcher/1000}
09-07 11:37:50.678  6474  6474 I wpa_supplicant: wlan0: Setting scan request: 0 sec 0 usec
09-07 11:37:50.678  6474  6474 I wpa_supplicant: P2P: Current p2p state = IDLE
09-07 11:37:50.678  6474  6474 I wpa_supplicant: Scan requested (ret=0) - scan timeout 30 seconds
09-07 11:37:50.678  1250  1250 D HS20StateMachine: Broadcast Received: android.net.wifi.STATE_CHANGE
09-07 11:37:50.678  1250  1250 D HS20StateMachine: [type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
09-07 11:37:50.678  1250  1250 D HS20StateMachine: SSID : "NG700"
09-07 11:37:50.678  1250  1250 D HS20StateMachine: NetId : 0
09-07 11:37:50.678  1250  1250 D HS20StateMachine: checkifOSUAP  null
09-07 11:37:50.678  1250  1250 I WifiHs20Service: Broadcast received:android.net.wifi.STATE_CHANGE
09-07 11:37:50.678  1250  1628 I WifiHs20Service: Message received 5007
09-07 11:37:50.678  6185  6185 I usagelog: received in receiver
09-07 11:37:50.678  6185  6185 I KnoxUsageLogPro: KnoxUsageReceiver onReceive :android.net.wifi.STATE_CHANGE myUserId=0
09-07 11:37:50.678  6185  6185 I KnoxUsageLogPro: premStatus:2
09-07 11:37:50.678  6185  6185 I KnoxUsageLogPro: isEulaShown : false
09-07 11:37:50.678  6185  6185 I KnoxUsageLogPro: KnoxUsageReceiver onReceive : not Processible, just return
09-07 11:37:50.688  1250  1986 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{5d8b8bb u0 com.sec.android.diagmonagent.intent.NETWORK_CHANGED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{e03cd16 6153:com.sec.android.diagmonagent/1000}
09-07 11:37:50.688  6153  6153 I DIAGMON_AGENT: [lllIIIIIIlllIlIIIIII(51/llIIIIlllllIIllIIllI)] Receive broadcast: com.sec.android.diagmonagent.intent.NETWORK_CHANGED
09-07 11:37:50.688   554  1414 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -A idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
09-07 11:37:50.688   445   445 I SurfaceFlinger: id=20 createSurf (1x1),1 flag=4, Uoast
09-07 11:37:50.688  6153  6153 I DIAGMON_AGENT: [lllIIIIIIlllIlIIIIII(52/llIIIIlllllIIllIIllI)] Receive broadcast:
09-07 11:37:50.688  6153  6153 I DIAGMON_AGENT: [lllIIIIIIlllIlIIIIII(67/llIIIIlllllIIllIIllI)] Running with RegistrationReceiver
09-07 11:37:50.688  1694  1694 D QSTileView: handleLabelStateChanged() label = Wi-Fi cellWidth 148
09-07 11:37:50.698  1250  1986 D PowerManagerService: [api] acquire WakeLock flags=0x2000000a tag=WindowManager uid=1000 pid=1250
,09-07 11:37:50.708   554  1414 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -A idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
09-07 11:37:50.708  1694  2100 D ViewRootImpl: MSG_RESIZED_REPORT: ci=Rect(0, 0 - 0, 0) vi=Rect(0, 0 - 0, 0) or=1
09-07 11:37:50.708  1250  1630 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=4, legacyType=-1, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-07 11:37:50.708  1250  1416 D EntConnectivity: Not allowed due to - mEnabled false
09-07 11:37:50.708  1250  1630 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=7, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-07 11:37:50.708  1250  1630 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=6, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-07 11:37:50.708  1250  1630 E CSLegacyTypeTracker: add() : Adding agent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{503}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.106/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains:  MTU: 0 TcpBufferSizes: 524288,1048576,1048576,524288,1048576,4194240}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -40]}  Score{20}  everValidated{false}  lastValidated{false}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} } for legacy network type 1
09-07 11:37:50.708  1250  1630 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=5, legacyType=-1, [] ]
09-07 11:37:50.708  1250  1630 D CSLegacyTypeTracker: Sending CONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 503] isDefaultNetwork=true
09-07 11:37:50.708  1250  1630 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
09-07 11:37:50.718  1250  2010 D ConnectivityService: getVpnConfig > userId : 0
09-07 11:37:50.718  1250  1416 D EntConnectivity: Not allowed due to - mEnabled false
09-07 11:37:50.718  1250  1630 D ConnectivityService: unneeded: NetworkAgentInfo{ ni{[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]}  network{501}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,1048576,524288,1048576,4194240}}  nc{[ Transports: WIFI Capabilities: WIFI_P2P&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
09-07 11:37:50.718  1250  1630 D ConnectivityService: unneeded: NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{503}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.106/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains:  MTU: 0 TcpBufferSizes: 524288,1048576,1048576,524288,1048576,4194240}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -40]}  Score{20}  everValidated{false}  lastValidated{false}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
09-07 11:37:50.718  1250  1630 D ConnectivityService: unneeded: NetworkRequestInfo for = Request from uid/pid:1000/1250 for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-07 11:37:50.718  1250  1630 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 503]
09-07 11:37:50.718  1250  1630 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-07 11:37:50.718  1250  1630 D ConnectivityService:  sending notification for NetworkRequest [ id=4, legacyType=-1, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-07 11:37:50.718  1250  1630 D ConnectivityService: sending notification PRECHECK for NetworkRequest [ id=4, legacyType=-1, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-07 11:37:50.718  1250  1416 D Tethering: MasterInitialState.processMessage what=3
09-07 11:37:50.718  1250  1630 D ConnectivityService:  sending notification for NetworkRequest [ id=5, legacyType=-1, [] ]
09-07 11:37:50.718  1250  1630 D ConnectivityService: sending notification PRECHECK for NetworkRequest [ id=5, legacyType=-1, [] ]
09-07 11:37:50.718  1250  1630 D ConnectivityService:  sending notification for NetworkRequest [ id=6, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-07 11:37:50.718  1250  1630 D ConnectivityService: sending notification PRECHECK for NetworkRequest [ id=6, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-07 11:37:50.718  1250  1250 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
09-07 11:37:50.718  1250  1630 D ConnectivityService:  sending notification for NetworkRequest [ id=7, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-07 11:37:50.718  1250  1630 D ConnectivityService: sending notification PRECHECK for NetworkRequest [ id=7, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-07 11:37:50.718  1250  1630 D ConnectivityService: EVENT_PROVISIONING_NOTIFICATION is sent for TYPE_MOBILE.
09-07 11:37:50.718  1250  1630 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
09-07 11:37:50.718  1250  1630 D ConnectivityService: NetworkAgentInfo [WIFI () - 503] validation  passed
09-07 11:37:50.718  1250  1630 D ConnectivityService: updateCapabilities: oldCap = [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -40], newCap = [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -40]
09-07 11:37:50.718  1250  1630 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 503]
09-07 11:37:50.718  1250  1631 D ConnectivityManager: getMobileDataEnabled()+ subId=2147483643
09-07 11:37:50.718  1250  1630 D ConnectivityService:  network has: NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{503}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.106/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains:  MTU: 0 TcpBufferSizes: 524288,1048576,1048576,524288,1048576,4194240}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN&VALIDATED LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -40]}  Score{60}  everValidated{true}  lastValidated{true}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
09-07 11:37:50.718  1944  2744 D PhoneInterfaceManager: [PhoneIntfMgr] getDataEnabled: subId=2147483643 phoneId=0
09-07 11:37:50.718  1250  1630 D ConnectivityService: Network NetworkAgentInfo [WIFI () - 503] was already satisfying request 1. No change.
09-07 11:37:50.718  1250  1630 D ConnectivityService:   checking if request is: NetworkRequest [ id=4, legacyType=-1, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] satisfies: true nri.isRequest: false
09-07 11:37:50.718  1250  1630 D ConnectivityService:   checking if request is: NetworkRequest [ id=7, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] satisfies: true nri.isRequest: false
09-07 11:37:50.718  1250  1630 D ConnectivityService:   checking if request is: NetworkRequest [ id=3, legacyType=-1, [ Transports: CELLULAR Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] satisfies: false nri.isRequest: false
09-07 11:37:50.718  1250  1630 D ConnectivityService:   checking if request is: NetworkRequest [ id=6, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] satisfies: true nri.isRequest: false
09-07 11:37:50.718  1250  1630 D ConnectivityService:   checking if request is: NetworkRequest [ id=5, legacyType=-1, [] ] satisfies: true nri.isRequest: false
09-07 11:37:50.718  1944  2744 D PhoneInterfaceManager: [PhoneIntfMgr] getDataEnabled: subId=2147483643 retVal=true
09-07 11:37:50.718  1250  1630 D ConnectivityService: unneeded: NetworkAgentInfo{ ni{[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]}  network{501}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,1048576,524288,1048576,4194240}}  nc{[ Transports: WIFI Capabilities: WIFI_P2P&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
09-07 11:37:50.718  1250  1631 D ConnectivityManager: getMobileDataEnabled()- subId=2147483643 retVal=true
09-07 11:37:50.718  1250  1630 D ConnectivityService: unneeded: NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{503}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.106/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains:  MTU: 0 TcpBufferSizes: 524288,1048576,1048576,524288,1048576,4194240}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN&VALIDATED LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -40]}  Score{60}  everValidated{true}  lastValidated{true}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
09-07 11:37:50.718  1250  1630 D ConnectivityService: unneeded: NetworkRequestInfo for = Request from uid/pid:1000/1250 for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-07 11:37:50.718  1250  1630 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 503]
09-07 11:37:50.718  1250  1630 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-07 11:37:50.718  1250  1630 D ConnectivityService:  sending notification for NetworkRequest [ id=4, legacyType=-1, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-07 11:37:50.718  1250  1630 D ConnectivityService: sending notification CAP_CHANGED for NetworkRequest [ id=4, legacyType=-1, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-07 11:37:50.718  1250  1630 D ConnectivityService:  sending notification for NetworkRequest [ id=5, legacyType=-1, [] ]
09-07 11:37:50.718  1250  1630 D ConnectivityService: sending notification CAP_CHANGED for NetworkRequest [ id=5, legacyType=-1, [] ]
09-07 11:37:50.718  1250  1630 D ConnectivityService:  sending notification for NetworkRequest [ id=6, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-07 11:37:50.718  1250  1630 D ConnectivityService: sending notification CAP_CHANGED for NetworkRequest [ id=6, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-07 11:37:50.718  1250  1630 D ConnectivityService:  sending notification for NetworkRequest [ id=7, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-07 11:37:50.718  1250  1371 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
09-07 11:37:50.718  1250  1630 D ConnectivityService: sending notification CAP_CHANGED for NetworkRequest [ id=7, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-07 11:37:50.718  1250  1630 D ConnectivityService: sending new Min Network Score(60): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-07 11:37:50.728  1250  1623 D WIFI    : new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-07 11:37:50.728  1250  1622 D WIFI_P2P: new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-07 11:37:50.728  1250  1622 D WIFI_P2P:   my score=60, my filter=[ Transports: WIFI Capabilities: WIFI_P2P&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
09-07 11:37:50.728  1250  1623 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
09-07 11:37:50.728  1250  1622 D WIFI_P2P: evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= false
09-07 11:37:50.728  1250  1623 D WIFI    : evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= true
09-07 11:37:50.728  1250  1622 D WIFI_P2P: evalRequest
09-07 11:37:50.728  1250  1623 D WIFI    : evalRequest
09-07 11:37:50.728  1250  1622 D WIFI_P2P:   done
09-07 11:37:50.728  1250  1623 D WIFI    :   done
09-07 11:37:50.728  1250  1371 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
09-07 11:37:50.728  1250  1371 D GpsLocationProvider: handleMessage msg = 4
09-07 11:37:50.728  1250  1878 V AlarmManager:  remove PendingIntent] PendingIntent{f20b05d: PendingIntentRecord{b959dd2 android broadcastIntent}}
09-07 11:37:50.728  1250  1651 D Ethernet: new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-07 11:37:50.728  1250  1651 D Ethernet:   my score=-1, my filter=[ Transports: ETHERNET Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=100000Kbps LinkDnBandwidth>=100000Kbps]
09-07 11:37:50.728  1250  1651 D Ethernet: evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= false
09-07 11:37:50.728  1250  1651 D Ethernet: evalRequest
09-07 11:37:50.728  1250  1651 D Ethernet:   done
09-07 11:37:50.728  1250  1623 D WIFI    : new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-07 11:37:50.728  1250  1630 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
09-07 11:37:50.728  1250  1623 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
09-07 11:37:50.728  1250  1623 D WIFI    : evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= true
09-07 11:37:50.728  1250  1623 D WIFI    : evalRequest
09-07 11:37:50.728  1250  1623 D WIFI    :   done
09-07 11:37:50.728  1250  1623 D WIFI_UT : new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-07 11:37:50.728  1250  1623 D WIFI_UT :   my score=2147483647, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
09-07 11:37:50.728  1250  1623 D WIFI_UT : evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= true
09-07 11:37:50.728  1250  1623 D WIFI_UT : evalRequest
09-07 11:37:50.728  1250  1623 D WIFI_UT :   done
09-07 11:37:50.728  1250  1250 D LocSvc_java: onReceive
09-07 11:37:50.728  1250  1250 D LocSvc_java: got connectivity action
09-07 11:37:50.728  1250  1250 D LocSvc_java: Connectivity status : mWifiConnectivity - true; mWwanConnectivity - false
09-07 11:37:50.728  1250  1250 D LocSvc_java: Sending msg: 4 arg1:1 arg2:1
09-07 11:37:50.728  1250  1250 D LocSvc_java: handleMessage msg = 4
09-07 11:37:50.728  1250  1250 D LocSvc_java: getAGpsConnectionInfo connType - 4
09-07 11:37:50.728  1250  1250 D LocSvc_java: updateNetworkState connTyp: 4 available info: [type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true] info.getType():1
09-07 11:37:50.738  1250  1250 V MARsPolicyManager: DataConnection: true
09-07 11:37:50.748  3113  3113 D MusicLifecycle: com.google.android.music.net.NetworkMonitor$2 generated event: Broadcast received with context com.google.android.music.net.NetworkMonitor@23104e0 and intent Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 bqHint=4 VirtualScreenParam=Params{mDisplayId=-1, null, mFlags=0x00000000)} (has extras) }
09-07 11:37:50.748  1944  2744 D PhoneInterfaceManager: [PhoneIntfMgr] getDataEnabled: subId=2147483643 phoneId=0
,09-07 11:37:50.748  1250  1994 V WindowStateAnimator: Finishing drawing window Window{74f06b5 u0 d0 Toast}: mDrawState=DRAW_PENDING
09-07 11:37:50.748  1250  1621 D NtpTrustedTime: currentTimeMillis() cache hit
09-07 11:37:50.748  1250  1621 D ConnectivityService: getAllNetworkState networkCapability  = [ Transports: WIFI Capabilities: WIFI_P2P&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
09-07 11:37:50.748  1250  1621 D ConnectivityService: getAllNetworkState networkCapability  = [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN&VALIDATED LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -40]
09-07 11:37:50.748  1250  1621 D NtpTrustedTime: currentTimeMillis() cache hit
09-07 11:37:50.748  1250  1621 D NtpTrustedTime: currentTimeMillis() cache hit
09-07 11:37:50.748  1250  1621 V NetworkStats: advisePersistThreshold() given 9223372036854775, clamped to 2097152
09-07 11:37:50.748  1250  1621 D NtpTrustedTime: currentTimeMillis() cache hit
09-07 11:37:50.748  1694  2100 D NetworkController: onReceive: intent=Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 bqHint=4 VirtualScreenParam=Params{mDisplayId=-1, null, mFlags=0x00000000)} (has extras) }
09-07 11:37:50.748  3113  3113 I NetworkMonitor: type=WIFI subType= reason=null isConnected=true
09-07 11:37:50.748  1250  1313 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
09-07 11:37:50.758  1250  1623 D WifiNetworkAgent: NetworkAgent: CMD_REPORT_NETWORK_STATUS(VALID)
09-07 11:37:50.758  1250  1623 D WifiNetworkAgent: NetworkAgent: CMD_REPORT_NETWORK_STATUS(1)
09-07 11:37:50.758  1944  2744 D PhoneInterfaceManager: [PhoneIntfMgr] getDataEnabled: subId=2147483643 retVal=true
09-07 11:37:50.758  1250  1371 D TelephonyManager: getDataEnabled: retVal=true
09-07 11:37:50.758  1694  2100 D NetworkController: onReceive: intent=Intent { act=android.net.conn.INET_CONDITION_ACTION flg=0x4000010 bqHint=4 VirtualScreenParam=Params{mDisplayId=-1, null, mFlags=0x00000000)} (has extras) }
09-07 11:37:50.758  2140  4187 W System  : ClassLoader referenced unknown path: /system/priv-app/Velvet/lib/arm64
09-07 11:37:50.768   766  1446 I QC-NETMGR-LIB: Received nl msg, recvmsg returned 64
09-07 11:37:50.768   766  1446 I QC-NETMGR-LIB: Received command: ID=NETMGR_KIF_MSG_CMD, link=0
09-07 11:37:50.768   766  1442 I QC-NETMGR-LIB: Process command: ID=NETMGR_KIF_MSG_CMD, link=0, state=1
09-07 11:37:50.768   766  1442 I QC-NETMGR-LIB: Processing RTM_NEWADDR
09-07 11:37:50.768   766  1442 I QC-NETMGR-LIB: Metainfo:  Family=10 PrefixLen=64 Scope=0xfd Index=17 Flags=[0x80]PERMANENT 
09-07 11:37:50.768   766  1442 I QC-NETMGR-LIB: Attribute: PrefixIPv6 addr [fe80:0000:0000:0000:4678:3eff:feeb:95ef]
09-07 11:37:50.768   766  1442 I QC-NETMGR-LIB: Attribute: Address Cache Info - prefered=-1 valid=-1 cstamp=0x3fbe tstamp=0x3fbe
09-07 11:37:50.768   766  1442 I QC-NETMGR-LIB: Rcvd Netlink msg type [20]
09-07 11:37:50.768   766  1442 E QC-NETMGR-LIB: unrecognized ifindex 17
09-07 11:37:50.768  5989  5989 D NetworkChangeNotifierAutoDetect: Network connectivity changed, type is: 2
09-07 11:37:50.768  1250  1623 D WifiStateMachine: isPackageRunning - top:com.test.thalitest.MainActivity
09-07 11:37:50.768  1250  1623 D WifiStateMachine: isPackageRunning - top:com.test.thalitest.MainActivity
09-07 11:37:50.768  1250  1623 D WifiStateMachine: sendBroadcastForCaptivePortalNotLoginIcon : false
09-07 11:37:50.768  1944  2295 D TelephonyProvider: query: url=content://telephony/carriers/preferapn, projectionIn=[Ljava.lang.String;@e5e1507, selection=nullselectionArgs=null, sort=name ASC
09-07 11:37:50.768  1250  1623 D WifiStateMachine: isPackageRunning - top:com.test.thalitest.MainActivity
09-07 11:37:50.768  1250  1623 D WifiStateMachine: isPackageRunning - top:com.test.thalitest.MainActivity
09-07 11:37:50.768  1694  2100 D NetworkController: onReceive: intent=Intent { act=com.samsung.intent.action.WIFI_CAPTIVE_NOT_LOGIN flg=0x10 bqHint=4 VirtualScreenParam=Params{mDisplayId=-1, null, mFlags=0x00000000)} (has extras) }
09-07 11:37:50.768  1694  2100 D NetworkController.WifiSignalController: updateWifiState : mCurrentState.wifiCaptiveNotLogin = false
09-07 11:37:50.768  1250  1964 V AlarmManager:  remove PendingIntent] PendingIntent{5365931: PendingIntentRecord{e4edab6 com.google.android.gms broadcastIntent}}
09-07 11:37:50.768  1250  1630 D ConnectivityService: updateLinkProperties: newLp = {InterfaceName: wlan0 LinkAddresses: [192.168.1.106/24,fe80::4678:3eff:feeb:95ef/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains:  MTU: 0 TcpBufferSizes: 524288,1048576,1048576,524288,1048576,4194240}, oldLp = {InterfaceName: wlan0 LinkAddresses: [192.168.1.106/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains:  MTU: 0 TcpBufferSizes: 524288,1048576,1048576,524288,1048576,4194240}
09-07 11:37:50.768  1250  1630 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 503]; created=true
09-07 11:37:50.778  1944  2295 D TelephonyProvider: query: match = 5
09-07 11:37:50.778  1250  1630 D ConnectivityService: identical MTU - not setting
09-07 11:37:50.778  1944  2295 D TelephonyProvider: getPreferredApnId(subId = 2147483643),return -1
09-07 11:37:50.778  1250  1630 V NetworkStats: updateIfacesLocked()
09-07 11:37:50.778  1250  1630 D NtpTrustedTime: currentTimeMillis() cache hit
09-07 11:37:50.778  1250  1630 V NetworkStats: performPollLocked(flags=0x1)
09-07 11:37:50.778  1250  1250 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
09-07 11:37:50.778  1944  2295 D TelephonyProvider: query: selection modified to edited!=2 and edited!=3 and edited!=5 and edited!=6
09-07 11:37:50.778  5989  5989 D BluetoothAdapter: STATE_ON
09-07 11:37:50.778  1250  1630 D NetworkStatsRecorder: entry.iface is null
09-07 11:37:50.778  1250  1630 D NtpTrustedTime: currentTimeMillis() cache hit
09-07 11:37:50.778  1250  1630 D NetworkStatsRecorder: entry.iface is null
09-07 11:37:50.778  1250  1630 D NetworkStatsRecorder: entry.iface is null
09-07 11:37:50.778  1250  1630 D NetworkStatsRecorder: entry.iface is null
09-07 11:37:50.778  1250  1630 V NetworkStats: performPollLocked() took 3ms
09-07 11:37:50.778  1250  1630 D ConnectivityService: getAllNetworkState networkCapability  = [ Transports: WIFI Capabilities: WIFI_P2P&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
09-07 11:37:50.778  1250  1630 D ConnectivityService: getAllNetworkState networkCapability  = [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN&VALIDATED LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -40]
09-07 11:37:50.778  5989  5989 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-07 11:37:50.778  5989  5989 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-07 11:37:50.778  5989  5989 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-07 11:37:50.778  5989  5989 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-07 11:37:50.778  5989  5989 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-07 11:37:50.778  5989  5989 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-07 11:37:50.778  5989  5989 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-07 11:37:50.778  5989  5989 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-07 11:37:50.778  1250  1630 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 503]
09-07 11:37:50.778  1250  1621 D NtpTrustedTime: currentTimeMillis() cache hit
09-07 11:37:50.778  1250  1630 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-07 11:37:50.778  1250  1621 D NtpTrustedTime: currentTimeMillis() cache hit
09-07 11:37:50.778  1250  1630 D ConnectivityService:  sending notification for NetworkRequest [ id=4, legacyType=-1, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-07 11:37:50.778  1250  1630 D ConnectivityService: sending notification IP_CHANGED for NetworkRequest [ id=4, legacyType=-1, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-07 11:37:50.778  1250  1630 D ConnectivityService:  sending notification for NetworkRequest [ id=5, legacyType=-1, [] ]
09-07 11:37:50.778  1250  1630 D ConnectivityService: sending notification IP_CHANGED for NetworkRequest [ id=5, legacyType=-1, [] ]
09-07 11:37:50.778  1250  1630 D ConnectivityService:  sending notification for NetworkRequest [ id=6, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-07 11:37:50.778  1250  1630 D ConnectivityService: sending notification IP_CHANGED for NetworkRequest [ id=6, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-07 11:37:50.778  1250  1630 D ConnectivityService:  sending notification for NetworkRequest [ id=7, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-07 11:37:50.778  1250  1630 D ConnectivityService: sending notification IP_CHANGED for NetworkRequest [ id=7, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-07 11:37:50.778  1250  1630 D ConnectivityService: Not required to send intent.
09-07 11:37:50.778  1250  1630 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 503]
09-07 11:37:50.778  5989  5989 D BluetoothAdapter: STATE_ON
09-07 11:37:50.778  1250  1630 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-07 11:37:50.778  1250  1630 D ConnectivityService:  sending notification for NetworkRequest [ id=4, legacyType=-1, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-07 11:37:50.778  1250  1630 D ConnectivityService: sending notification IP_CHANGED for NetworkRequest [ id=4, legacyType=-1, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-07 11:37:50.778  1250  1630 D ConnectivityService:  sending notification for NetworkRequest [ id=5, legacyType=-1, [] ]
09-07 11:37:50.778  1250  1630 D ConnectivityService: sending notification IP_CHANGED for NetworkRequest [ id=5, legacyType=-1, [] ]
09-07 11:37:50.778  2140  2140 D NetworkChangeNotifierAutoDetect: Network connectivity changed, type is: 2
09-07 11:37:50.778  1250  1630 D ConnectivityService:  sending notification for NetworkRequest [ id=6, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-07 11:37:50.788  1250  1630 D ConnectivityService: sending notification IP_CHANGED for NetworkRequest [ id=6, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-07 11:37:50.788  1250  1630 D ConnectivityService:  sending notification for NetworkRequest [ id=7, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-07 11:37:50.788  1250  1630 D ConnectivityService: sending notification IP_CHANGED for NetworkRequest [ id=7, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-07 11:37:50.788  5989  5989 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-07 11:37:50.788  6221  6232 I DBG_POLICYDM: [com.sec.android.policyagent.db.llllIIIllIlIIIIllllI(47/llIIIIlllllIIllIIllI)] get SalesCode from FotaFeature
,09-07 11:37:50.788  5989  5989 D BluetoothAdapter: STATE_ON
09-07 11:37:50.788  6221  6232 I DBG_POLICYDM: [com.sec.android.policyagent.db.llllIIIllIlIIIIllllI(47/llIIIIlllllIIllIIllI)] get SalesCode from FotaFeature
,09-07 11:37:50.788  5989  5989 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-07 11:37:50.788  5989  5989 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-07 11:37:50.788  5989  5989 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-07 11:37:50.788  5989  5989 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-07 11:37:50.788  5989  5989 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-07 11:37:50.788  5989  5989 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-07 11:37:50.788  5989  5989 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-07 11:37:50.788  5989  5989 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-07 11:37:50.788  1250  1371 E GpsLocationProvider: No APN found to select.
,09-07 11:37:50.798  5989  5989 D BluetoothAdapter: STATE_ON
,09-07 11:37:50.798  5989  5989 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-07 11:37:50.798  6221  6232 I DBG_POLICYDM: [com.sec.android.policyagent.db.IIIIllIlIIlIIIIlllIl(43/llIIIIlllllIIllIIllI)] already Eula Agree
,09-07 11:37:50.798  6221  6231 I DBG_POLICYDM: [com.sec.android.policyagent.db.llllIIIllIlIIIIllllI(47/llIIIIlllllIIllIIllI)] get SalesCode from FotaFeature
,09-07 11:37:50.798  6221  6231 I DBG_POLICYDM: [com.sec.android.policyagent.db.llllIIIllIlIIIIllllI(47/llIIIIlllllIIllIIllI)] get SalesCode from FotaFeature
,09-07 11:37:50.808  6221  6231 I DBG_POLICYDM: [com.sec.android.policyagent.db.IIIIllIlIIlIIIIlllIl(43/llIIIIlllllIIllIIllI)] already Eula Agree
,09-07 11:37:50.808  2596  2596 E audit   : type=1400 msg=audit(1473241070.808:287): avc:  denied  { ioctl } for  pid=4032 comm="ChromiumNet" path="socket:[50294]" dev="sockfs" ino=50294 ioctlcmd=8b1b scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:untrusted_app:s0:c512,c768 tclass=udp_socket permissive=0
09-07 11:37:50.808  2596  2596 E audit   :  SEPF_SECMOBILE_6.0.1_0013
09-07 11:37:50.808  2596  2596 E audit   : type=1300 msg=audit(1473241070.808:287): arch=c00000b7 syscall=29 success=no exit=-13 a0=15 a1=8b1b a2=7f5edbecc8 a3=7f5edbec90 items=0 ppid=595 pid=4032 auid=4294967295 uid=10049 gid=10049 euid=10049 suid=10049 fsuid=10049 egid=10049 sgid=10049 fsgid=10049 ses=4294967295 tty=(none) comm="ChromiumNet" exe="/system/bin/app_process64" subj=u:r:untrusted_app:s0:c512,c768 key=(null)
09-07 11:37:50.808  2596  2596 E audit   : type=1327 msg=audit(1473241070.808:287): proctitle="com.google.android.googlequicksearchbox:search"
09-07 11:37:50.808  2596  2596 E audit   : type=1320 msg=audit(1473241070.808:287): 
09-07 11:37:50.808  2596  2596 E audit   : type=1400 msg=audit(1473241070.808:288): avc:  denied  { ioctl } for  pid=4032 comm="ChromiumNet" path="socket:[50295]" dev="sockfs" ino=50295 ioctlcmd=8b1b scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:untrusted_app:s0:c512,c768 tclass=udp_socket permissive=0
09-07 11:37:50.808  2596  2596 E audit   :  SEPF_SECMOBILE_6.0.1_0013
09-07 11:37:50.808  2596  2596 E audit   : type=1300 msg=audit(1473241070.808:288): arch=c00000b7 syscall=29 success=no exit=-13 a0=15 a1=8b1b a2=7f5edbecc8 a3=7f5edbec90 items=0 ppid=595 pid=4032 auid=4294967295 uid=10049 gid=10049 euid=10049 suid=10049 fsuid=10049 egid=10049 sgid=10049 fsgid=10049 ses=4294967295 tty=(none) comm="ChromiumNet" exe="/system/bin/app_process64" subj=u:r:untrusted_app:s0:c512,c768 key=(null)
09-07 11:37:50.808  2596  2596 E audit   : type=1327 msg=audit(1473241070.808:288): proctitle="com.google.android.googlequicksearchbox:search"
09-07 11:37:50.808  2596  2596 E audit   : type=1320 msg=audit(1473241070.808:288): 
,09-07 11:37:50.818  6530  6530 E Zygote  : v2
09-07 11:37:50.818  6530  6530 I libpersona: KNOX_SDCARD checking this for 1000
09-07 11:37:50.818  6530  6530 I libpersona: KNOX_SDCARD not a persona
,09-07 11:37:50.818  1250  2010 I ActivityManager: Start proc 6530:com.sec.android.soagent/1000 for content provider com.sec.android.soagent/.log.MasterLogProvider
,09-07 11:37:50.818  6530  6530 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0013
,09-07 11:37:50.828  6530  6530 E Zygote  : accessInfo : 0
,09-07 11:37:50.848  6530  6530 D TimaKeyStoreProvider: TimaSignature is unavailable
09-07 11:37:50.848  6530  6530 D ActivityThread: Added TimaKeyStore provider
,09-07 11:37:50.868  6530  6530 W System  : ClassLoader referenced unknown path: /system/priv-app/SOAgent/lib/arm64
,09-07 11:37:50.898  1250  2010 I ActivityManager: Killing 5882:com.google.android.apps.docs/u0a71 (adj 15): DHA:empty #31
,09-07 11:37:50.898  1250  1313 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{bd02597 u-1 android.net.conn.CONNECTIVITY_CHANGE qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{9925d68 5989:com.test.thalitest/u0a136}
,09-07 11:37:50.908  1250  1994 D ConnectivityService: returning getNetworkInfo for network type 0 : [type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
09-07 11:37:50.908  1250  1994 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
09-07 11:37:50.908  1250  1994 D ConnectivityService: returning getNetworkInfo for network type 2 : [type: MOBILE_MMS[] - MOBILE_MMS, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
09-07 11:37:50.908  1250  1994 D ConnectivityService: returning getNetworkInfo for network type 3 : [type: MOBILE_SUPL[] - MOBILE_SUPL, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
09-07 11:37:50.908  1250  1994 D ConnectivityService: returning getNetworkInfo for network type 4 : [type: MOBILE_DUN[] - MOBILE_DUN, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
09-07 11:37:50.908  1250  1994 D ConnectivityService: returning getNetworkInfo for network type 5 : [type: MOBILE_HIPRI[] - MOBILE_HIPRI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
09-07 11:37:50.908  1250  1994 D ConnectivityService: returning getNetworkInfo for network type 7 : [type: BLUETOOTH[] - BLUETOOTH, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
09-07 11:37:50.908  1250  1994 D ConnectivityService: returning getNetworkInfo for network type 9 : [type: ETHERNET[] - ETHERNET, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
09-07 11:37:50.908  1250  1994 D ConnectivityService: returning getNetworkInfo for network type 10 : [type: MOBILE_FOTA[] - MOBILE_FOTA, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
09-07 11:37:50.908  1250  1994 D ConnectivityService: returning getNetworkInfo for network type 11 : [type: MOBILE_IMS[] - MOBILE_IMS, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
09-07 11:37:50.908  1250  1994 D ConnectivityService: returning getNetworkInfo for network type 12 : [type: MOBILE_CBS[] - MOBILE_CBS, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
09-07 11:37:50.908  1250  1994 D ConnectivityService: returning getNetworkInfo for network type 13 : [type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
09-07 11:37:50.908  1250  1994 D ConnectivityService: returning getNetworkInfo for network type 14 : [type: MOBILE_IA[] - MOBILE_IA, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
09-07 11:37:50.908  1250  1994 D ConnectivityService: returning getNetworkInfo for network type 15 : [type: MOBILE_EMERGENCY[] - MOBILE_EMERGENCY, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
09-07 11:37:50.908  1250  1994 D ConnectivityService: returning getNetworkInfo for network type 17 : [type: VPN[] - VPN, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
,09-07 11:37:50.908  1250  1720 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{bd02597 u-1 android.net.conn.CONNECTIVITY_CHANGE qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{667d8b1 1250:system/1000}
,09-07 11:37:50.908  1250  1250 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{bd02597 u-1 android.net.conn.CONNECTIVITY_CHANGE qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{7a2c63a 2207:com.google.android.gms/u0a10}
,09-07 11:37:50.918  2207  2207 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,09-07 11:37:50.918  2207  3201 I iu.UploadsManager: num queued entries: 0
09-07 11:37:50.918  1250  2674 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{bd02597 u-1 android.net.conn.CONNECTIVITY_CHANGE qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{7a2c63a 2207:com.google.android.gms/u0a10}
09-07 11:37:50.918  2207  3201 I iu.UploadsManager: num updated entries: 0
09-07 11:37:50.918  2207  3201 I iu.SyncManager: NEXT; no task
,09-07 11:37:50.918  1250  2396 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{bd02597 u-1 android.net.conn.CONNECTIVITY_CHANGE qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{ef1b27 1866:com.google.android.gms.persistent/u0a10}
,09-07 11:37:50.928  1250  1646 D WifiWatchdogStateMachine.CaptivePortalHandler: start check captive portal 
09-07 11:37:50.928  1250  1986 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{bd02597 u-1 android.net.conn.CONNECTIVITY_CHANGE qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{bfd0e08 6221:com.policydm/1000}
,09-07 11:37:50.928   554  1410 D EnterpriseController: netId is 0
09-07 11:37:50.928   554  1410 D Netd    : getNetworkForDns: using netid 503 for uid 10010
,09-07 11:37:50.938  6221  6221 I DBG_POLICYDM: [com.policydm.db.IIIIllIlIIlIIIIlllIl(574/IlIIIllllIIlIIIIIlII)] Initiated Type: 0
,09-07 11:37:50.948  6221  6221 I DBG_POLICYDM: [com.policydm.db.IIIIllIlIIlIIIIlllIl(442/IIIlIIllIlIIllIlllII)] xdbGetFUMOStatus : 0
,09-07 11:37:50.948  6221  6221 I DBG_POLICYDM: [com.policydm.XDMService(574/llIlIllllllllllllllI)] get NotibarState : 0
,09-07 11:37:50.948  1250  1378 V BroadcastQueue: [deferred] Process cur broadcast BroadcastRecord{bd02597 u-1 android.net.conn.CONNECTIVITY_CHANGE qIdx=3}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{bfd0e08 6221:com.policydm/1000}
,09-07 11:37:50.958  6221  6221 I DBG_POLICYDM: [com.sec.android.policyagent.RegistrationReceiver(51/onReceive)] RegistrationReceiver onReceive! action = android.net.conn.CONNECTIVITY_CHANGE
,09-07 11:37:50.968  6221  6221 I DBG_POLICYDM: [com.sec.android.policyagent.db.IIIIllIlIIlIIIIlllIl(87/llllIIIllIlIIIIllllI)] device register flag at setting DB : true
,09-07 11:37:50.968  6221  6221 I DBG_POLICYDM: [com.sec.android.policyagent.RegistrationReceiver(96/onReceive)] Already device registered...
,09-07 11:37:50.978  6221  6221 I DBG_POLICYDM: [com.sec.android.policyagent.db.IIIIllIlIIlIIIIlllIl(87/llllIIIllIlIIIIllllI)] device register flag at setting DB : true
,09-07 11:37:50.978  6221  6221 I DBG_POLICYDM: [com.sec.android.policyagent.RegistrationReceiver(337/lllIlIlIIIllIIlIllIl)] OMC not Supported model
,09-07 11:37:50.988  6221  6221 I DBG_POLICYDM: [IIIIlllIIIlIlllllIll(110/llIlIIIIlIIIIIlIlIII)] Polling time is vaild
,09-07 11:37:50.988  6221  6221 I DBG_POLICYDM: [com.sec.android.policyagent.RegistrationReceiver(277/llIIIIlllllIIllIIllI)] Heartbeat settings is activated.
,09-07 11:37:50.988  6221  6221 I DBG_POLICYDM: [IIlllIIllIllIllIIlll(49/llllIIIllIlIIIIllllI)] Next heartbeat time:2016/09/17/23:24:10
,09-07 11:37:50.988  6221  6221 I DBG_POLICYDM: [IIlllIIllIllIllIIlll(52/llllIIIllIlIIIIllllI)] heartbeat time is vaild
,09-07 11:37:50.988  1250  1646 D WifiWatchdogStateMachine.CaptivePortalHandler: result = 0, mCaptivePortalCheckMode = 11, mCouldNotIdentifyCaptivePortalState = true
,09-07 11:37:50.998  1250  1994 V BroadcastQueue: [deferred] Process cur broadcast BroadcastRecord{bd02597 u-1 android.net.conn.CONNECTIVITY_CHANGE qIdx=3}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{1e67a52 6247:com.osp.app.signin/u0a27}
,09-07 11:37:50.998  6247  6247 I SA      : [OR] onReceive log=[SA = 2.2.01-51 V = 23 HWD = 2048X1536 2.0 dpi = 320  SIZE = 4 LOCALE = pl_PL CSC = XEO MCC = 0 MNC 0 T = user DEVICE = gts28velte P = gts28veltexx I = MMB29M M = SM-T719 OKLEFT false DIS MMB29M.T719XXU1APF6 PSS = 8.00525302084415  ]
,09-07 11:37:50.998  6247  6247 I SA      : [OR] onReceive Intent=[ conn.CONNECTIVITY_CHANGE. networkInfo:[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true] networkType:1 inetCondition:0 extraInfo:? isDefault:true ]
09-07 11:37:50.998  6247  6247 I SA      : [OR] == ACTION_CONNECTIVITY_CHANGE ==
,09-07 11:37:50.998  1250  2333 D ActivityManager: removeProcessNameLocked mProcessNames.remove pid=5882 ,hash=106005407 ,name=com.google.android.apps.docs
09-07 11:37:50.998  1250  2333 D ActivityManager: isAutoRunBlockedApp:: com.google.android.apps.docs, Auto Run ON
,09-07 11:37:50.998  6247  6247 I SA      : [TPMU]  strSIMState 	:SIM_STATE_ABSENT
09-07 11:37:50.998  6247  6247 I SA      : [OR] == isSIMCardReady false ==
09-07 11:37:51.008  6247  6247 I SA      : [SCU] == networkStateCheck == true
,09-07 11:37:51.008  6247  6247 I SA      : [DM] getCountryCodeFromCSC : PL
09-07 11:37:51.008  6247  6247 I SA      : isChinaCountryCode : false
09-07 11:37:51.008  6247  6247 I SA      : [SCU] is ChinestModel Data Restricted   : false
09-07 11:37:51.008  6247  6247 I SA      : [OR] == networkStateCheck true ==
,09-07 11:37:51.008  6247  6247 I SA      : [OR] GetMyCountryZoneTask
,09-07 11:37:51.008  6247  6247 I SA      : [OR] onReceive END
,09-07 11:37:51.008  6247  6546 I SA      : [SRS] prepareGetMyCountryZone
,09-07 11:37:51.008  1250  2327 V BroadcastQueue: [deferred] Process cur broadcast BroadcastRecord{bd02597 u-1 android.net.conn.CONNECTIVITY_CHANGE qIdx=3}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{a0c9664 5242:com.wssyncmldm/1000}
,09-07 11:37:51.018  6247  6546 I SA      : [TPMU]  strSIMState 	:SIM_STATE_ABSENT
,09-07 11:37:51.018  6247  6546 I SA      : [SSP] query invoked
09-07 11:37:51.018  1250  2674 V BroadcastQueue: [deferred] Process cur broadcast BroadcastRecord{bd02597 u-1 android.net.conn.CONNECTIVITY_CHANGE qIdx=3}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{7cc8669 6173:com.sec.app.RilErrorNotifier/1000}
09-07 11:37:51.018  5242  6548 I FOTA_AGENT: [com.samsung.android.app.fotaclient.llIlIIIIlIIIIIlIlIII(87/llIIIIlllllIIllIIllI)] Nothing to do action: android.net.conn.CONNECTIVITY_CHANGE
09-07 11:37:51.018  6173  6173 I PhoneErrorReceiver: onReceive
09-07 11:37:51.018  6173  6173 V PhoneErrorReceiver: beginStartingService
,09-07 11:37:51.028  6173  6173 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1311 android.content.ContextWrapper.startService:606 android.content.ContextWrapper.startService:606 com.sec.app.RilErrorNotifier.PhoneErrorReceiver.beginStartingService:194 com.sec.app.RilErrorNotifier.PhoneErrorReceiver.onReceiveWithPrivilege:171 
,09-07 11:37:51.028  6247  6546 I SA      : [TPMU] GetMccFromDB : null
09-07 11:37:51.028  6247  6546 I SA      : [SCU] getMccFromPreferece mcc = 260
09-07 11:37:51.028  6247  6546 I SA      : [LBE] isSupportCheckDomainRegion : true
09-07 11:37:51.028  6247  6546 I SA      : [TPM] isNoProxy(default) : true
,09-07 11:37:51.028  6173  6173 V PhoneErrService: Creating SmsReceiverService
09-07 11:37:51.028  6173  6173 V MIP_PhoneErrService: mTelephonyManager is not null
,09-07 11:37:51.028  1250  1310 V BroadcastQueue: [deferred] Process cur broadcast BroadcastRecord{bd02597 u-1 android.net.conn.CONNECTIVITY_CHANGE qIdx=3}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{af855d3 4453:com.sec.spp.push/u0a26}
09-07 11:37:51.028  4453  4453 E SPPClientService: [SystemStateMoniter] Action Name : android.net.conn.CONNECTIVITY_CHANGE
,09-07 11:37:51.028  4453  4453 E SPPClientService: [SystemStateMoniter] Current Time : 164448
,09-07 11:37:51.028  4453  4453 E SPPClientService: [SystemStateMoniter] No Connect : false
,09-07 11:37:51.038  1250  1994 V BroadcastQueue: [deferred] Process cur broadcast BroadcastRecord{bd02597 u-1 android.net.conn.CONNECTIVITY_CHANGE qIdx=3}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{dfe46f9 2433:android.process.media/u0a33}
,09-07 11:37:51.038  6247  6546 I System.out: (HTTPLog)-Static: Hongbao
,09-07 11:37:51.038  2433  2433 V DownloadManager: onReceive intent + android.net.conn.CONNECTIVITY_CHANGE
,09-07 11:37:51.038  6173  6173 V PhoneErrService: Starting #1: Bundle[mParcelledData.dataSize=388]
,09-07 11:37:51.038  6173  6173 I PhoneErrService: mResultCode: 0
09-07 11:37:51.038  6173  6173 V MIP_PhoneErrService: onDataConnectionState : -1
,09-07 11:37:51.038  6173  6549 V PhoneErrService: Handling incoming message: { when=-1ms what=0 arg1=1 obj=Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.sec.app.RilErrorNotifier/.PhoneErrService bqHint=3 VirtualScreenParam=Params{mDisplayId=-1, null, mFlags=0x00000000)} (has extras) } target=com.sec.app.RilErrorNotifier.PhoneErrService$ServiceHandler }
09-07 11:37:51.038  6173  6549 V PhoneErrorReceiver: finishStartingService
,09-07 11:37:51.048  1250  1964 V BroadcastQueue: [deferred] Process cur broadcast BroadcastRecord{bd02597 u-1 android.net.conn.CONNECTIVITY_CHANGE qIdx=3}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{ad6dbd9 6265:com.samsung.android.SettingsReceiver/1000}
,09-07 11:37:51.048  6173  6173 V PhoneErrService: Destroying PhoneErrorReceiverService
,09-07 11:37:51.048  1250  1986 D SecContentProvider2: query(), uri = 15 selection = getAppBlockDownloadState
,09-07 11:37:51.048  1250  1964 V BroadcastQueue: [deferred] Process cur broadcast BroadcastRecord{bd02597 u-1 android.net.conn.CONNECTIVITY_CHANGE qIdx=3}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{6c29e29 2494:com.microsoft.skydrive/u0a93}
,09-07 11:37:51.058  1250  1720 W IntentResolver: resolveIntent failed: found match, but none with CATEGORY_DEFAULT
,09-07 11:37:51.058  1250  1720 D PackageManager: findPreferredActivity: No PreferredActivities set
09-07 11:37:51.058  1250  1720 I PackageManager: No preferred activity: intent should not be shown
,09-07 11:37:51.068  1250  1994 V BroadcastQueue: [deferred] Process cur broadcast BroadcastRecord{bd02597 u-1 android.net.conn.CONNECTIVITY_CHANGE qIdx=3}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{78ecc7f 6290:com.google.android.apps.photos/u0a97}
,09-07 11:37:51.068  1250  1378 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{5678433 u0 com.google.android.apps.photos.actionqueue.INTERNAL_ACTION qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{78ecc7f 6290:com.google.android.apps.photos/u0a97}
,09-07 11:37:51.078  1250  2333 V BroadcastQueue: [deferred] Process cur broadcast BroadcastRecord{bd02597 u-1 android.net.conn.CONNECTIVITY_CHANGE qIdx=3}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{78ecc7f 6290:com.google.android.apps.photos/u0a97}
,09-07 11:37:51.078  1250  1378 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{f1dfd69 u0 com.google.android.apps.photos.jobqueue.EXECUTE_JOBS qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{78ecc7f 6290:com.google.android.apps.photos/u0a97}
,09-07 11:37:51.088  1250  1720 V BroadcastQueue: [deferred] Process cur broadcast BroadcastRecord{bd02597 u-1 android.net.conn.CONNECTIVITY_CHANGE qIdx=3}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{82191cf 4782:com.sec.android.daemonapp/u0a127}
,09-07 11:37:51.088  4782  4782 D [WeatherWidget(1210)]  ConnectivityReceiver: {[8E9CEEBB4FA5730BE17E1F2CB9E366CFAAE09BFCA326403459399C53A4EE79DAC193CEB26509F8FF7498BE5251A746097407E81C28CD811D388C49D613C81F395B356AA489D29CB4C3BE983CCC84BA76AF507AA66A943348DF162DECA2A5A7DD]}
,09-07 11:37:51.088  4782  4782 D [WeatherWidget(1210)]  ConnectivityReceiver: {[8E9CEEBB4FA5730BE17E1F2CB9E366CFE2E89F45594D9820F24D88E9AF210A78152C254DDD0027D207FA50AD616546E30965FECE0D7B834EEF4B0E211833EA2B]}
,09-07 11:37:51.088  1250  1720 V BroadcastQueue: [deferred] Process cur broadcast BroadcastRecord{bd02597 u-1 android.net.conn.CONNECTIVITY_CHANGE qIdx=3}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{26de453 5382:com.sec.android.app.samsungapps/u0a9}
,09-07 11:37:51.098  5382  5382 D WaitQueueForNetworkActivate: notifyNetworkActivated
,09-07 11:37:51.098  1250  1994 V AlarmManager:  remove PendingIntent] PendingIntent{91e80fa: PendingIntentRecord{e4edab6 com.google.android.gms broadcastIntent}}
,09-07 11:37:51.098  5382  5382 D hcjo    : AutoUpdateManager:IDLE:execute
,09-07 11:37:51.098  5382  5382 D InitializeManagerStateMachine: execute::IDLE:EXECUTE
09-07 11:37:51.098  5382  5382 D InitializeManagerStateMachine: exit::IDLE
09-07 11:37:51.098  5382  5382 D InitializeManagerStateMachine: entry::NETWORK_CHECK
,09-07 11:37:51.098  1250  2396 D ConnectivityService: returning getNetworkInfo for network type 0 : [type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
,09-07 11:37:51.098  5382  5382 D InitializeManagerStateMachine: execute::NETWORK_CHECK:NETWORK_STATE_OK
09-07 11:37:51.098  1250  1720 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
09-07 11:37:51.098  5382  5382 D InitializeManagerStateMachine: exit::NETWORK_CHECK
09-07 11:37:51.098  5382  5382 D InitializeManagerStateMachine: entry::CHECK_COUNTRY_INFO
09-07 11:37:51.098  5382  5382 D InitializeManagerStateMachine: execute::CHECK_COUNTRY_INFO:COUNTRY_INFO_OK
09-07 11:37:51.098  5382  5382 D InitializeManagerStateMachine: exit::CHECK_COUNTRY_INFO
09-07 11:37:51.098  5382  5382 D InitializeManagerStateMachine: entry::SUCCESS
09-07 11:37:51.098  5382  5382 D hcjo    : AutoUpdateManager:INITCHECK:onInitializeSuccess
,09-07 11:37:51.108  5382  5382 D hcjo    : AutoUpdateTriggerManager:IDLE:notifyNextTime
09-07 11:37:51.108  5382  5382 D hcjo    : AutoUpdateManager:UPD_CHECK_TIMING:onNoUpdateTime
,09-07 11:37:51.108  1250  1720 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
,09-07 11:37:51.108  5382  5382 D InitializeManagerStateMachine: exit::SUCCESS
09-07 11:37:51.108  5382  5382 D InitializeManagerStateMachine: entry::IDLE
,09-07 11:37:51.228  1866  6557 I PhenotypeConfigurator: Scheduling Phenotype for one-off execution 10497 seconds from now (1473241071236)
,09-07 11:37:51.238  1250  1378 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{a383552 u0 com.google.android.gms.gcm.ACTION_SCHEDULE qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{ef1b27 1866:com.google.android.gms.persistent/u0a10}
,09-07 11:37:51.248  6247  6546 I SA_HTTPURLCONNECTION: [RC New] Execute method=[GET] start
,09-07 11:37:51.248  6247  6546 I System.out: (HTTPLog)-Static: Hongbao
,09-07 11:37:51.248  6247  6546 I SA_HTTPURLCONNECTION: [RC New] Security=[true]
,09-07 11:37:51.258  6247  6546 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
09-07 11:37:51.258  6247  6546 I System.out: (HTTPLog)-Static: Hongbao
09-07 11:37:51.258  6247  6546 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,09-07 11:37:51.258   554  1410 D EnterpriseController: netId is 0
09-07 11:37:51.258   554  1410 D Netd    : getNetworkForDns: using netid 503 for uid 10027
,09-07 11:37:51.278  1866  6555 I PhenotypeFlagCommitter: Experiment Configs successfully retrieved for com.google.android.gms.playlog.uploader
,09-07 11:37:51.278  1866  6555 I GoogleURLConnFactory: Using platform SSLCertificateSocketFactory
,09-07 11:37:51.298  1250  2674 D LocationManagerService: getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,09-07 11:37:51.348  1250  1378 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{aa05b7f u0 com.google.android.gcm.CONNECTED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{3a76423 5481:com.google.android.talk/u0a84}
,09-07 11:37:51.358  1250  1721 V AlarmManager:  remove PendingIntent] PendingIntent{561d74c: PendingIntentRecord{e1d8317 com.google.android.gms broadcastIntent}}
,09-07 11:37:51.368  1866  6555 I System.out: (HTTPLog)-Static: Hongbao
,09-07 11:37:51.378  1866  6555 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
09-07 11:37:51.378  1866  6555 I System.out: (HTTPLog)-Static: Hongbao
09-07 11:37:51.378  1866  6555 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,09-07 11:37:51.378   554  1410 D EnterpriseController: netId is 0
09-07 11:37:51.378   554  1410 D Netd    : getNetworkForDns: using netid 503 for uid 10010
,09-07 11:37:51.498   554  1410 D EnterpriseController: netId is 0
09-07 11:37:51.498   554  1410 D Netd    : getNetworkForDns: using netid 503 for uid 10136
,09-07 11:37:51.498  5989  6565 I io.jxcore.node.IncomingSocketThread: Local host address: localhost/127.0.0.1, port: 47775
09-07 11:37:51.498  5989  6482 I io.jxcore.node.OutgoingSocketThread: Incoming data from address: /127.0.0.1, port: 47775
,09-07 11:37:51.498  5989  6482 D io.jxcore.node.OutgoingSocketThread: Setting local streams and starting stream copying threads...
09-07 11:37:51.498  5989  6565 D io.jxcore.node.IncomingSocketThread: Setting local streams and starting stream copying threads...
09-07 11:37:51.498  5989  6565 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
09-07 11:37:51.498  5989  6482 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
09-07 11:37:51.498  5989  6565 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
09-07 11:37:51.498  5989  6482 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
,09-07 11:37:51.498  5989  6482 I io.jxcore.node.OutgoingSocketThread: startStreamCopyingThreads: OK (thread ID: 1234)
09-07 11:37:51.498  5989  6565 I io.jxcore.node.IncomingSocketThread: startStreamCopyingThreads: OK (thread ID: 4321)
,09-07 11:37:51.498  5989  6568 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 276, name: IncomingSocketThread/Sender)
09-07 11:37:51.498  5989  6569 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 275, name: OutgoingSocketThread/Sender)
,09-07 11:37:51.498  5989  6571 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 277, name: IncomingSocketThread/Receiver)
09-07 11:37:51.498  5989  6570 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 278, name: OutgoingSocketThread/Receiver)
09-07 11:37:51.498  5989  6571 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 277, thread name: IncomingSocketThread/Receiver)
09-07 11:37:51.498  5989  6571 I io.jxcore.node.IncomingSocketThread: The receiving thread is done
09-07 11:37:51.498  5989  6570 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 278, thread name: OutgoingSocketThread/Receiver)
09-07 11:37:51.498  5989  6571 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 277, name: IncomingSocketThread/Receiver), during the lifetime of the thread the total number of bytes read was 207 and the total number of bytes written 207
09-07 11:37:51.498  5989  6570 I io.jxcore.node.OutgoingSocketThread: The receiving thread is done
09-07 11:37:51.498  5989  6570 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 278, name: OutgoingSocketThread/Receiver), during the lifetime of the thread the total number of bytes read was 192 and the total number of bytes written 192
,09-07 11:37:51.708  1250  1630 D ConnectivityService: NetTransition Wakelock (NetworkAgentInfo [WIFI () - 502] cleared because we found a replacement network
,09-07 11:37:51.728  1866  1875 E DataBuffer: Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@f6db175)
,09-07 11:37:51.968  1250  2674 D LocationManagerService: getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,09-07 11:37:51.978  1866  6555 I System.out: (HTTPLog)-Static: Hongbao
,09-07 11:37:51.978  1866  6555 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
09-07 11:37:51.978  1866  6555 I System.out: (HTTPLog)-Static: Hongbao
09-07 11:37:51.978  1866  6555 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,09-07 11:37:52.188  6247  6546 I SA_HTTPURLCONNECTION: [RC New] [v2liruge] api execute + 938
,09-07 11:37:52.198  6247  6546 I SA      : [ODM] saveOpenData( GEO_IP, PL )
,09-07 11:37:52.208  6247  6546 I SA      : [OCP] update openData : PL
,09-07 11:37:52.208  6247  6546 I SA      : [TPMU] getNetworkMcc : 
,09-07 11:37:52.218  6247  6546 I SA      : [SCU] saveMccToPreferece Start
09-07 11:37:52.218  6247  6546 I SA      : [SCU] RegionMCC : 260
09-07 11:37:52.218  6247  6546 I SA      : [SSP] query invoked
,09-07 11:37:52.228  6247  6546 I SA      : [TPMU] GetMccFromDB : null
09-07 11:37:52.228  6247  6546 I SA      : [SCU] getMccFromPreferece mcc = 260
09-07 11:37:52.228  6247  6546 I SA      : [SCU] saveMccToPreferece End
09-07 11:37:52.228  6247  6546 I SA_HTTPURLCONNECTION: [RC New] executeRequest [v2liruge] end. 982
09-07 11:37:52.228  6247  6546 I SA_HTTPURLCONNECTION: [RC New] Execute end
,09-07 11:37:52.228  6247  6247 I SA      : [OR] GetMyCountryZoneTask mcc = 260
09-07 11:37:52.228  6247  6247 I SA      : [OR] GetMyCountryZoneTask Success
,09-07 11:37:52.248  1250  2327 D LocationManagerService: getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,09-07 11:37:52.258  1866  6555 I System.out: (HTTPLog)-Static: Hongbao
09-07 11:37:52.258  1866  6555 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
09-07 11:37:52.258  1866  6555 I System.out: (HTTPLog)-Static: Hongbao
09-07 11:37:52.258  1866  6555 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,09-07 11:37:52.388  1250  2674 V AlarmManager:  remove PendingIntent] PendingIntent{f69309b: PendingIntentRecord{e4edab6 com.google.android.gms broadcastIntent}}
,09-07 11:37:52.668  1694  2100 D ViewRootImpl: #3 mView = null
,09-07 11:37:52.668   445   468 I SurfaceFlinger: id=20 Removed Uoast (9/12)
09-07 11:37:52.668   445   468 I SurfaceFlinger: id=20 Removed Uoast (-2/12)
,09-07 11:37:52.668  1250  2333 D PowerManagerService: [api] release WakeLock flags=0x2000000a tag=WindowManager uid=1000 pid=1250 (0x0)
,09-07 11:37:52.668  1250  2333 D PowerManagerService: [api] applyWakeLockFlagsOnReleaseLocked : userActivityNoUpdateLocked is called : SCREEN_BRIGHT_WAKE_LOCK        'WindowManager' ON_AFTER_RELEASE (uid=1000, pid=1250, ws=WorkSource{10046}) (elapsedTime=1970)
,09-07 11:37:54.308  6486  6486 I dhcpcd  : wlan0: sending IPv6 Router Solicitation
,09-07 11:37:54.408  1250  1834 E Watchdog: !@Sync 5 [09-07 11:37:54.417]
,09-07 11:37:54.498  5989  6040 D io.jxcore.node.LifeCycleMonitor: onActivityCreated: Bundle[{}]
09-07 11:37:54.498  5989  6040 D io.jxcore.node.LifeCycleMonitor: onActivityResumed
09-07 11:37:54.498  5989  6040 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@6dd3681 Bundle[{}]
09-07 11:37:54.498  5989  6040 I io.jxcore.node.LifeCycleMonitor: start: OK
09-07 11:37:54.498  5989  6040 I io.jxcore.node.LifeCycleMonitor: stop: OK
09-07 11:37:54.498  5989  6040 D io.jxcore.node.LifeCycleMonitor: onActivityStarted
09-07 11:37:54.498  5989  6040 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
09-07 11:37:54.498  5989  6040 D io.jxcore.node.LifeCycleMonitor: onActivityDestroyed
09-07 11:37:54.498  5989  6040 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
,09-07 11:37:54.508  5989  6578 D io.jxcore.node.OutgoingSocketThread: Server socket local port: 57775
09-07 11:37:54.508  5989  6578 I io.jxcore.node.OutgoingSocketThread: Now accepting connections...
,09-07 11:37:54.928  1250  3553 D SSRM:s  : SIOP:: AP = 300, PST = 323 (W:12), CP = 37, LCD = 0
,09-07 11:37:54.928  1250  3553 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
,09-07 11:37:55.338   707   707 I MSM-irqbalance: Decided to move IRQ65 from CPU3 to CPU0
,09-07 11:37:57.518   554  1410 D EnterpriseController: netId is 0
09-07 11:37:57.518   554  1410 D Netd    : getNetworkForDns: using netid 503 for uid 10136
,09-07 11:37:57.518  5989  6580 I io.jxcore.node.IncomingSocketThread: Local host address: localhost/127.0.0.1, port: 57775
09-07 11:37:57.518  5989  6580 D io.jxcore.node.IncomingSocketThread: Setting local streams and starting stream copying threads...
09-07 11:37:57.518  5989  6578 I io.jxcore.node.OutgoingSocketThread: Incoming data from address: /127.0.0.1, port: 57775
09-07 11:37:57.518  5989  6578 D io.jxcore.node.OutgoingSocketThread: Setting local streams and starting stream copying threads...
09-07 11:37:57.518  5989  6580 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
09-07 11:37:57.518  5989  6578 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
09-07 11:37:57.518  5989  6580 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
,09-07 11:37:57.518  5989  6580 I io.jxcore.node.IncomingSocketThread: startStreamCopyingThreads: OK (thread ID: 4321)
09-07 11:37:57.518  5989  6578 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
09-07 11:37:57.518  5989  6578 I io.jxcore.node.OutgoingSocketThread: startStreamCopyingThreads: OK (thread ID: 1234)
,09-07 11:37:57.518  5989  6584 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 291, name: IncomingSocketThread/Receiver)
,09-07 11:37:57.518  5989  6585 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 290, name: OutgoingSocketThread/Sender)
09-07 11:37:57.518  5989  6584 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 291, thread name: IncomingSocketThread/Receiver)
09-07 11:37:57.518  5989  6584 I io.jxcore.node.IncomingSocketThread: The receiving thread is done
09-07 11:37:57.518  5989  6584 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 291, name: IncomingSocketThread/Receiver), during the lifetime of the thread the total number of bytes read was 192 and the total number of bytes written 192
09-07 11:37:57.518  5989  6583 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 289, name: IncomingSocketThread/Sender)
09-07 11:37:57.518  5989  6586 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 292, name: OutgoingSocketThread/Receiver)
,09-07 11:37:57.518  5989  6586 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 292, thread name: OutgoingSocketThread/Receiver)
09-07 11:37:57.518  5989  6586 I io.jxcore.node.OutgoingSocketThread: The receiving thread is done
09-07 11:37:57.518  5989  6586 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 292, name: OutgoingSocketThread/Receiver), during the lifetime of the thread the total number of bytes read was 207 and the total number of bytes written 207
,09-07 11:37:58.308  6486  6486 I dhcpcd  : wlan0: sending IPv6 Router Solicitation
,09-07 11:37:58.668  1250  1630 D ConnectivityService: handlePromptUnvalidated 503
,09-07 11:38:00.168  6474  6474 I wpa_supplicant: nl80211: Received scan results (46 BSSes)
,09-07 11:38:00.178  1250  1622 D WifiP2pService: InactiveState{ what=147461 }
09-07 11:38:00.178  1250  1622 D WifiP2pService: P2pEnabledState{ what=147461 }
09-07 11:38:00.178  1250  1622 D WifiP2pService: DefaultState{ what=147461 }
,09-07 11:38:00.218  1250  1378 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{5544411 u-1 android.net.wifi.SCAN_RESULTS qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{743a74c 1694:com.android.systemui/u0a46}
,09-07 11:38:00.338   707   707 I MSM-irqbalance: Decided to move IRQ200 from CPU1 to CPU0
,09-07 11:38:00.518  5989  6040 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 301)
09-07 11:38:00.518  5989  6040 V io.jxcore.node.SocketThreadBase: close: Closing the localhost socket...
09-07 11:38:00.518  5989  6040 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 302)
09-07 11:38:00.518  5989  6040 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-07 11:38:00.518  5989  6040 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@da2634f added. We now have 3 listener(s)
09-07 11:38:00.528  5989  6040 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "44:78:3E:EB:95:EE"
09-07 11:38:00.528  5989  6040 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-07 11:38:00.528  5989  6040 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-07 11:38:00.528  5989  6040 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-07 11:38:00.528  5989  6040 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6808adc added. We now have 3 listener(s)
09-07 11:38:00.528  5989  6040 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-07 11:38:00.528  5989  6040 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-07 11:38:00.528  5989  6040 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-07 11:38:00.538  5989  6040 D BluetoothAdapter: STATE_ON
,09-07 11:38:00.538  5989  6040 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-07 11:38:00.538  5989  6040 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-07 11:38:00.538  5989  6040 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-07 11:38:00.538  5989  6040 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-07 11:38:00.538  5989  6040 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-07 11:38:00.538  5989  6040 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-07 11:38:00.538  5989  6040 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-07 11:38:00.538  5989  6040 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-07 11:38:00.538  5989  6040 D BluetoothAdapter: STATE_ON
,09-07 11:38:00.548  5989  6040 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-07 11:38:00.548  5989  6040 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-07 11:38:00.548  5989  6040 D BluetoothAdapter: STATE_ON
,09-07 11:38:00.548  5989  5989 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-07 11:38:00.548  5989  6040 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-07 11:38:00.548  5989  6040 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 11:38:00.548  5989  6040 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-07 11:38:00.548  5989  6040 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-07 11:38:00.548  5989  6040 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@da2634f removed from the list
09-07 11:38:00.548  5989  6040 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-07 11:38:00.548  5989  6040 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6808adc removed from the list
,09-07 11:38:00.548  5989  5989 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-07 11:38:00.548  5989  6040 D io.jxcore.node.ConnectivityMonitor: stop
09-07 11:38:00.548  5989  6040 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-07 11:38:00.558  5989  6040 I io.jxcore.node.StartStopOperationHandler: updateBeaconAdExtraInformation: New value: 5
09-07 11:38:00.558  5989  6040 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBeaconAdExtraInformation: 4 -> 5
09-07 11:38:00.558  5989  6040 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
09-07 11:38:00.558  5989  6040 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should start/stop everything
09-07 11:38:00.558  5989  6040 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
09-07 11:38:00.558  5989  6040 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-07 11:38:00.558  5989  6040 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
,09-07 11:38:00.558  5989  6040 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
09-07 11:38:00.558  5989  6040 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
09-07 11:38:00.558  5989  6040 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
09-07 11:38:00.558  5989  6040 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: true
09-07 11:38:00.558  5989  6040 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-07 11:38:00.558  5989  5989 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
09-07 11:38:00.558  5989  6040 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,09-07 11:38:00.558  5989  6587 D BluetoothSocket: bindListen(): myUserId = 0
09-07 11:38:00.558  5989  6587 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-07 11:38:00.558  5989  6040 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,09-07 11:38:00.558  5989  6040 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
09-07 11:38:00.568  5989  6587 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
,09-07 11:38:00.568  5989  6040 D BluetoothAdapter: STATE_ON,
,09-07 11:38:00.568  5989  6040 D BluetoothAdapter: STATE_ON
09-07 11:38:00.568  5989  6040 D BluetoothAdapter: STATE_ON,
,09-07 11:38:00.568  5989  6040 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false,
,09-07 11:38:00.568  5989  6040 D BluetoothAdapter: STATE_ON
,09-07 11:38:00.568  5989  6040 D BluetoothAdapter: STATE_ON,
09-07 11:38:00.568  5989  6040 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
09-07 11:38:00.568  5989  6040 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,09-07 11:38:00.578  5989  6040 D BluetoothAdapter: STATE_ON
,09-07 11:38:00.578  5989  6040 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
09-07 11:38:00.578  5989  6040 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "44:78:3E:EB:95:EE"
09-07 11:38:00.578  5989  6040 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 05 44 78 3E EB 95 EE
09-07 11:38:00.578  5989  6040 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[5, 68, 120, 62, -21, -107, -18]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
,09-07 11:38:00.578  5989  6040 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[5, 68, 120, 62, -21, -107, -18]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
09-07 11:38:00.578  5989  6040 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting...
09-07 11:38:00.578  5989  6040 D BluetoothAdapter: STATE_ON
,09-07 11:38:00.578  5989  6040 D BluetoothAdapter: STATE_ON
09-07 11:38:00.578  5989  6040 D BluetoothLeAdvertiser: start advertising
,09-07 11:38:00.578  5989  6040 D BluetoothAdapter: STATE_ON
,09-07 11:38:00.588  2587  3153 D BtGatt.GattService: registerClient() - UUID=708ed6ee-9d67-40b5-930c-99cc4bcca020
,09-07 11:38:00.628  2587  2756 D BtGatt.GattService: onClientRegistered() - UUID=708ed6ee-9d67-40b5-930c-99cc4bcca020, clientIf=6
,09-07 11:38:00.628  5989  6000 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=6
,09-07 11:38:00.628  2587  6414 D BtGatt.GattService: [GSIM LOG]: startMultiAdvertising: 2
,09-07 11:38:00.628  2587  6414 D BtGatt.GattService: [GSIM LOG]: getCallingProcessName: com.test.thalitest
09-07 11:38:00.628  2587  6414 D BtGatt.GattService: [GSIM LOG]: getCallingProcessName: com.test.thalitest
09-07 11:38:00.628  2587  2780 E BtGatt.GattService: [GSIM LOG]: gsimLogHandler: com.test.thalitest, msg: MESSAGE_START_ADV
09-07 11:38:00.628  2587  2780 D BtGatt.GattService: [GSIM LOG]: gsimLogHandler: prevDate: 7, currDate: 7
,09-07 11:38:00.628  2587  2765 D BtGatt.AdvertiseManager: message : 0
,09-07 11:38:00.638  2587  2765 D BtGatt.AdvertiseManager: number of adv instance running = 0
,09-07 11:38:00.638  2587  2765 D BtGatt.AdvertiseManager: size of list is =0
,09-07 11:38:00.638  2587  2765 D BtGatt.AdvertiseManager: starting advertising
,09-07 11:38:00.638  2587  2765 D BtGatt.AdvertiseManager: isStandardAdv = false
,09-07 11:38:00.638  3003  3007 I WCNSS_FILTER: ibs_msm_serial_clock_vote: vote UART CLK ON using UART driver's ioctl(),
09-07 11:38:00.638  1250  1990 V AlarmManager:  remove PendingIntent] PendingIntent{de93a50: PendingIntentRecord{45887f2 com.android.bluetooth broadcastIntent}}
,09-07 11:38:00.638  2587  2780 D BtGatt.GattService: [GSIM LOG]: increaseAdvCount : com.test.thalitest : 23
,09-07 11:38:00.648  3003  3007 I WCNSS_FILTER: do_write: IBS write: fd,
,09-07 11:38:00.648  3003  3007 I WCNSS_FILTER: Direction(0): bytes: 28 : bytes_written: 28
09-07 11:38:00.648  3003  3003 I WCNSS_FILTER: do_write: IBS write: fc
,09-07 11:38:00.648  3003  3003 I WCNSS_FILTER: Direction(1): bytes: 8 : bytes_written: 8
,09-07 11:38:00.648  1250  1310 V AlarmManager:  remove PendingIntent] PendingIntent{5f26449: PendingIntentRecord{45887f2 com.android.bluetooth broadcastIntent}}
09-07 11:38:00.648  3003  3007 I WCNSS_FILTER: Direction(0): bytes: 7 : bytes_written: 7
09-07 11:38:00.648  3003  3003 I WCNSS_FILTER: Direction(1): bytes: 8 : bytes_written: 8
09-07 11:38:00.648  2587  2756 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=6, status=0
09-07 11:38:00.648  2587  2765 D BtGatt.AdvertiseManager: starting multi advertising
09-07 11:38:00.648  2587  2780 D BtGatt.GattService: [GSIM LOG]: setAdvTime : com.test.thalitest@LowLatency : 24554018
09-07 11:38:00.658  2587  2780 D BtGatt.GattService: [GSIM LOG]: setAdvType : com.test.thalitest@LowLatency : 2
09-07 11:38:00.658  2587  2780 D BtGatt.GattService: [GSIM LOG]: updateAdvTime
,09-07 11:38:00.658  2587  2780 D BtGatt.GattService: [GSIM LOG]: com.test.thalitest@LowLatency, R time : 2 => 2
09-07 11:38:00.658  3003  3007 I WCNSS_FILTER: Direction(0): bytes: 38 : bytes_written: 38
09-07 11:38:00.658  3003  3003 I WCNSS_FILTER: Direction(1): bytes: 8 : bytes_written: 8
09-07 11:38:00.658  1250  1720 V AlarmManager:  remove PendingIntent] PendingIntent{c39214e: PendingIntentRecord{45887f2 com.android.bluetooth broadcastIntent}}
09-07 11:38:00.658  2587  2756 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=6, status=0
,09-07 11:38:00.658  2587  2765 D BtGatt.AdvertiseManager: logClientsSet() - status: 0
09-07 11:38:00.658  2587  2765 D BtGatt.AdvertiseManager: clientIf: 6, Mode: 2, TxPowerLevel: 3, isConnectable: false, Timeout: 0
09-07 11:38:00.658  2587  2765 D BtGatt.AdvertiseManager: postCallback clientIf = 6 status = 0
09-07 11:38:00.658  2587  2765 D BtGatt.GattService: onMultipleAdvertiseCallback() clientIf=6, status=0, isStart=true
09-07 11:38:00.658  5989  5999 D BluetoothLeAdvertiser: onMultiAdvertiseCallback status = 0 isStart = true
09-07 11:38:00.658  5989  6040 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
09-07 11:38:00.658  5989  6040 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,09-07 11:38:00.658  5989  6040 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,09-07 11:38:00.658  1250  1990 V AlarmManager:  remove PendingIntent] PendingIntent{ccd226f: PendingIntentRecord{45887f2 com.android.bluetooth broadcastIntent}}
,09-07 11:38:00.658  5989  5989 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
09-07 11:38:00.658  5989  5989 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess
09-07 11:38:00.658  5989  5989 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
09-07 11:38:00.658  5989  5989 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: true
09-07 11:38:00.658  5989  5989 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [ADVERTISING]
09-07 11:38:00.658  5989  5989 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [ADVERTISING]
,09-07 11:38:00.668  1250  1313 V AlarmManager:  remove PendingIntent] PendingIntent{4afab7c: PendingIntentRecord{45887f2 com.android.bluetooth broadcastIntent}}
09-07 11:38:00.668  5989  5989 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: true
09-07 11:38:00.668  5989  5989 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: true
,09-07 11:38:00.668  1250  1994 V AlarmManager:  remove PendingIntent] PendingIntent{2f3fc05: PendingIntentRecord{45887f2 com.android.bluetooth broadcastIntent}}
,09-07 11:38:01.118  5382  5382 D PreloadUpdateManagerStateMachine: execute::IDLE:EXECUTE
,09-07 11:38:01.118  5382  5382 D PreloadUpdateManagerStateMachine: exit::IDLE
09-07 11:38:01.118  5382  5382 D PreloadUpdateManagerStateMachine: entry::CHECK_TIMEOUT_FOR_UPDATE
,09-07 11:38:01.118  5382  5382 D hcjo    : AutoUpdateTriggerManager:IDLE:notifyNextTime
,09-07 11:38:01.128  5382  5382 D PreloadUpdateManagerStateMachine: execute::CHECK_TIMEOUT_FOR_UPDATE:NO_TIMED_OUT
,09-07 11:38:01.128  5382  5382 D PreloadUpdateManagerStateMachine: exit::CHECK_TIMEOUT_FOR_UPDATE
,09-07 11:38:01.128  5382  5382 D PreloadUpdateManagerStateMachine: entry::IDLE
,09-07 11:38:01.168  5989  5989 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: true
09-07 11:38:01.168  5989  5989 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
09-07 11:38:01.168  5989  5989 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,09-07 11:38:01.658  3003  3066 I WCNSS_FILTER: do_write: IBS write: fe
09-07 11:38:01.658  3003  3066 I WCNSS_FILTER: ibs_msm_serial_clock_vote: vote UART CLK OFF using UART driver's ioctl()
,09-07 11:38:02.318  6486  6486 I dhcpcd  : wlan0: sending IPv6 Router Solicitation
09-07 11:38:02.318  6486  6486 I dhcpcd  : wlan0: no IPv6 Routers available
,09-07 11:38:04.948  1250  3553 D SSRM:s  : SIOP:: AP = 300, PST = 319 (W:14), CP = 36, LCD = 0
,09-07 11:38:04.948  1250  3553 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
,09-07 11:38:05.338   707   707 I MSM-irqbalance: Decided to move IRQ327 from CPU1 to CPU0
,09-07 11:38:05.488  1250  1994 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
09-07 11:38:05.488  1250  1994 D BatteryService: level:100, scale:100, status:3, health:2, present:true, voltage: 4375, temperature: 298, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303407, invalid charger:0, maxChargingCurrent:0
09-07 11:38:05.488  1250  1994 D BatteryService: online:4, current avg:-1, charge type:0, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:-3
09-07 11:38:05.488  1250  1250 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,09-07 11:38:05.498  1694  1694 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
09-07 11:38:05.498  1694  1694 D KeyguardUpdateMonitor: handleBatteryUpdate
,09-07 11:38:05.498  1694  1694 D PowerUI : priorPlugType = 2 mPlugType =  2
,09-07 11:38:05.498  1694  1694 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:3 health:2
09-07 11:38:05.498  1694  1694 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:3 health:2
,09-07 11:38:05.508  2587  2587 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
09-07 11:38:05.508  2587  6385 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,09-07 11:38:05.528  1694  1694 D CoverUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,09-07 11:38:06.658  5989  6040 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Stop operation: Should start/stop everything
09-07 11:38:06.658  5989  6040 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
09-07 11:38:06.658  5989  6040 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
09-07 11:38:06.658  5989  6040 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
09-07 11:38:06.658  5989  6040 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
09-07 11:38:06.658  5989  6040 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-07 11:38:06.668  5989  6040 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
09-07 11:38:06.668  5989  6040 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
09-07 11:38:06.668  5989  6040 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...,
09-07 11:38:06.668  5989  6040 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-07 11:38:06.668  5989  6040 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-07 11:38:06.668  5989  6040 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-07 11:38:06.668  5989  6587 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
09-07 11:38:06.668  5989  6587 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
09-07 11:38:06.668  5989  6587 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
09-07 11:38:06.668  5989  5989 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
09-07 11:38:06.668  5989  6040 D BluetoothAdapter: STATE_ON
,09-07 11:38:06.668  5989  6040 D BluetoothAdapter: STATE_ON
09-07 11:38:06.668  5989  6040 D BluetoothLeScanner: could not find callback wrapper
09-07 11:38:06.668  5989  6040 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-07 11:38:06.668  5989  6040 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
09-07 11:38:06.668  5989  6040 D BluetoothAdapter: STATE_ON
,09-07 11:38:06.668  5989  6040 D BluetoothAdapter: STATE_ON
,09-07 11:38:06.668  5989  6040 D BluetoothLeAdvertiser: stop advertising
,09-07 11:38:06.678  2587  3109 D BtGatt.GattService: [GSIM LOG]: getCallingProcessName: com.test.thalitest
09-07 11:38:06.678  2587  3109 D BtGatt.GattService: [GSIM LOG]: getCallingProcessName: com.test.thalitest
09-07 11:38:06.678  2587  2780 E BtGatt.GattService: [GSIM LOG]: gsimLogHandler: com.test.thalitest, msg: MESSAGE_STOP_ADV
09-07 11:38:06.678  2587  2780 D BtGatt.GattService: [GSIM LOG]: gsimLogHandler: prevDate: 7, currDate: 7
09-07 11:38:06.678  2587  2780 D BtGatt.GattService: [GSIM LOG]: updateAdvTime
09-07 11:38:06.678  2587  2780 D BtGatt.GattService: [GSIM LOG]: com.test.thalitest@LowLatency, R time : 2 => 2
09-07 11:38:06.678  2587  2780 D BtGatt.GattService: [GSIM LOG]: remove : com.test.thalitest@LowLatency at  BLE_ADV_REQUESTED_DB
09-07 11:38:06.678  2587  2765 D BtGatt.AdvertiseManager: message : 1
09-07 11:38:06.678  2587  2765 D BtGatt.AdvertiseManager: stop advertise for client =  6
09-07 11:38:06.678  2587  2765 D BtGatt.AdvertiseManager: stop advertising, standardAdvClientIf = 0 client.clientIf = 6
,09-07 11:38:06.678  2587  2765 D BtGatt.AdvertiseManager: logClientsSet() - status: -1
,09-07 11:38:06.678  1250  1720 V AlarmManager:  remove PendingIntent] PendingIntent{4b3768b: PendingIntentRecord{45887f2 com.android.bluetooth broadcastIntent}}
09-07 11:38:06.678  3003  3007 I WCNSS_FILTER: ibs_msm_serial_clock_vote: vote UART CLK ON using UART driver's ioctl(),
,09-07 11:38:06.688  3003  3007 I WCNSS_FILTER: do_write: IBS write: fd,
,09-07 11:38:06.688  3003  3007 I WCNSS_FILTER: Direction(0): bytes: 7 : bytes_written: 7,
,09-07 11:38:06.688  3003  3003 I WCNSS_FILTER: do_write: IBS write: fc,
09-07 11:38:06.688  3003  3003 I WCNSS_FILTER: Direction(1): bytes: 8 : bytes_written: 8
09-07 11:38:06.688  2587  2756 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=6, status=0,
09-07 11:38:06.688  2587  2756 D BtGatt.GattService: Client app is not null!
09-07 11:38:06.688  3003  3007 E WCNSS_FILTER: do_read: read returned 0, err = Success, read bytes: 0, expected: 0
09-07 11:38:06.688  1250  1964 V AlarmManager:  remove PendingIntent] PendingIntent{90a0368: PendingIntentRecord{45887f2 com.android.bluetooth broadcastIntent}}
09-07 11:38:06.688  3003  3007 I WCNSS_FILTER: Direction(0): bytes: 4 : bytes_written: 4
09-07 11:38:06.688  5989  6000 D BluetoothLeAdvertiser: onMultiAdvertiseCallback status = 0 isStart = false
,09-07 11:38:06.698  2587  6415 D BtGatt.GattService: unregisterClient() - clientIf=6
09-07 11:38:06.698  5989  6040 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-07 11:38:06.698  5989  6040 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
09-07 11:38:06.698  5989  6040 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: false
09-07 11:38:06.698  5989  6040 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [ADVERTISING] to [NOT_STARTED]
09-07 11:38:06.698  5989  6040 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [ADVERTISING] -> [NOT_STARTED]
,09-07 11:38:06.698  5989  6040 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
09-07 11:38:06.698  5989  6040 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-07 11:38:06.698  5989  6040 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-07 11:38:06.698  1250  1313 V AlarmManager:  remove PendingIntent] PendingIntent{bd5381: PendingIntentRecord{45887f2 com.android.bluetooth broadcastIntent}}
09-07 11:38:06.698  5989  6040 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-07 11:38:06.698  5989  5989 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-07 11:38:06.698  5989  5989 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
09-07 11:38:06.698  5989  5989 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,09-07 11:38:06.698  5989  5989 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-07 11:38:06.698  5989  5989 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
09-07 11:38:06.698  5989  5989 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,09-07 11:38:06.708  3003  3003 I WCNSS_FILTER: Direction(1): bytes: 15 : bytes_written: 15
,09-07 11:38:06.708  3003  3007 I WCNSS_FILTER: Direction(0): bytes: 12 : bytes_written: 12
09-07 11:38:06.708  1250  2396 V AlarmManager:  remove PendingIntent] PendingIntent{6d40c26: PendingIntentRecord{45887f2 com.android.bluetooth broadcastIntent}}
,09-07 11:38:06.708  3003  3003 I WCNSS_FILTER: Direction(1): bytes: 8 : bytes_written: 8
,09-07 11:38:06.708  1250  1310 V AlarmManager:  remove PendingIntent] PendingIntent{f60f067: PendingIntentRecord{45887f2 com.android.bluetooth broadcastIntent}}
,09-07 11:38:06.718  1250  1313 V AlarmManager:  remove PendingIntent] PendingIntent{c2fee14: PendingIntentRecord{45887f2 com.android.bluetooth broadcastIntent}}
,09-07 11:38:07.208  5989  5989 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,09-07 11:38:07.628  1250  3554 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:836 b.J.a:-1 b.J.a:-1 b.N.run:-1 android.os.Handler.handleCallback:739 
,09-07 11:38:07.628  1250  1378 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{927d780 u0 com.samsung.android.sm.lowpowercontext.START_ANALYSIS qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{d4d60da 5782:com.samsung.android.sm.provider/1000}
,09-07 11:38:07.678  1250  3554 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:836 b.J.a:-1 b.J.a:-1 b.L.run:-1 android.os.Handler.handleCallback:739 
,09-07 11:38:07.678  1250  1378 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{bd679fe u0 com.samsung.android.sm.lowpowercontext.START_ANALYSIS qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{d4d60da 5782:com.samsung.android.sm.provider/1000}
,09-07 11:38:07.708  3003  3066 I WCNSS_FILTER: do_write: IBS write: fe
09-07 11:38:07.708  3003  3066 I WCNSS_FILTER: ibs_msm_serial_clock_vote: vote UART CLK OFF using UART driver's ioctl()
,09-07 11:38:07.738  1250  3581 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:836 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,09-07 11:38:09.708  5989  6040 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-07 11:38:09.708  5989  6040 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 11:38:09.708  5989  6040 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-07 11:38:09.708  5989  6040 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@da2634f not in the list
09-07 11:38:09.708  5989  6040 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-07 11:38:09.708  5989  6040 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6808adc not in the list
09-07 11:38:09.708  5989  6040 D io.jxcore.node.ConnectivityMonitor: stop
09-07 11:38:09.708  5989  6040 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 11:38:09.708  5989  6040 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-07 11:38:09.708  5989  6040 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-07 11:38:09.708  5989  6040 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-07 11:38:09.708  5989  6040 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-07 11:38:09.708  5989  6040 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-07 11:38:09.708  5989  6040 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-07 11:38:09.708  5989  6040 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,09-07 11:38:09.708  5989  6040 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
09-07 11:38:09.708  5989  6040 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,09-07 11:38:09.708  5989  6040 D BluetoothAdapter: STATE_ON
,09-07 11:38:09.718  5989  6040 D BluetoothAdapter: STATE_ON
09-07 11:38:09.718  5989  6040 D BluetoothAdapter: STATE_ON
,09-07 11:38:09.718  5989  6040 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,09-07 11:38:09.718  5989  6040 D BluetoothAdapter: STATE_ON
,09-07 11:38:09.718  5989  6040 D BluetoothAdapter: STATE_ON
09-07 11:38:09.718  5989  6040 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
,09-07 11:38:09.718  5989  6040 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,09-07 11:38:09.728  5989  6040 D BluetoothAdapter: STATE_ON
,09-07 11:38:09.728  5989  6040 D BluetoothAdapter: STATE_ON
,09-07 11:38:09.728  5989  6040 D BluetoothAdapter: STATE_ON
,09-07 11:38:09.728  5989  6040 D BluetoothAdapter: STATE_ON
,09-07 11:38:09.728  5989  6040 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
09-07 11:38:09.728  5989  6040 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
,09-07 11:38:09.728  5989  6040 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
09-07 11:38:09.728  5989  6040 D BluetoothLeScanner: Start Scan
,09-07 11:38:09.738  5989  6040 D BluetoothAdapter: STATE_ON
,09-07 11:38:09.738  5989  6040 D BluetoothAdapter: STATE_ON
,09-07 11:38:09.738  5989  6040 D BluetoothAdapter: STATE_ON,
,09-07 11:38:09.738  5989  6040 D BluetoothAdapter: STATE_ON
,09-07 11:38:09.738  2587  6415 D BtGatt.GattService: registerClient() - UUID=0637da98-da5e-4557-b04c-92f42330f3fe
,09-07 11:38:09.778  2587  2756 D BtGatt.GattService: onClientRegistered() - UUID=0637da98-da5e-4557-b04c-92f42330f3fe, clientIf=6,
09-07 11:38:09.778  5989  6000 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=6
,09-07 11:38:09.788  2587  2604 D BtGatt.GattService: start scan with filters
,09-07 11:38:09.788  2587  2604 D BtGatt.GattService: getScanSettings,
,09-07 11:38:09.798  2587  2604 D BtGatt.GattService: Is it foreground application = true
,09-07 11:38:09.798  2587  2604 D BtGatt.GattService: not a background application
,09-07 11:38:09.798  2587  2604 D BtGatt.GattService: [GSIM LOG]: getActualScanMode (2/100 vs -2147483648/0),
,09-07 11:38:09.798  2587  2604 D BtGatt.GattService: [GSIM LOG]: getCallingProcessName: com.test.thalitest
09-07 11:38:09.798  2587  2604 D BtGatt.GattService: [GSIM LOG]: getCallingProcessName: com.test.thalitest
09-07 11:38:09.798  2587  2780 E BtGatt.GattService: [GSIM LOG]: gsimLogHandler: com.test.thalitest, msg: MESSAGE_START_SCAN
09-07 11:38:09.798  2587  2780 D BtGatt.GattService: [GSIM LOG]: gsimLogHandler: prevDate: 7, currDate: 7
,09-07 11:38:09.798  5989  6040 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
09-07 11:38:09.808  5989  6040 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
09-07 11:38:09.808  5989  6040 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
09-07 11:38:09.808  5989  6040 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,09-07 11:38:09.808  2587  2767 D BtGatt.ScanManager: handling starting scan
09-07 11:38:09.808  2587  2767 D BtGatt.ScanManager: isFilteringSupported
,09-07 11:38:09.808  2587  2767 D BluetoothAdapter: enableStandAloneBleMode=
09-07 11:38:09.808  2587  2767 D BluetoothAdapter: STATE_ON
09-07 11:38:09.808  2587  2767 D BluetoothAdapter: STATE_ON
09-07 11:38:09.808  5989  6040 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
09-07 11:38:09.808  5989  6040 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
09-07 11:38:09.808  5989  5989 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
09-07 11:38:09.808  2587  2767 D BluetoothAdapter: STATE_ON
09-07 11:38:09.808  2587  2767 D BluetoothAdapter: STATE_ON
,09-07 11:38:09.808  5989  6040 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
09-07 11:38:09.808  1250  2396 V AlarmManager:  remove PendingIntent] PendingIntent{4d3187b: PendingIntentRecord{45887f2 com.android.bluetooth broadcastIntent}}
,09-07 11:38:09.808  2587  2767 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@c11cc52
09-07 11:38:09.808  2587  2780 D BtGatt.GattService: [GSIM LOG]: increaseScanCount : com.test.thalitest : 10
09-07 11:38:09.808  2587  2780 D BtGatt.GattService: [GSIM LOG]: increaseScanCount : com.test.thalitest, com.test.thalitest
09-07 11:38:09.808  3003  3007 I WCNSS_FILTER: ibs_msm_serial_clock_vote: vote UART CLK ON using UART driver's ioctl()
,09-07 11:38:09.818  3003  3007 I WCNSS_FILTER: do_write: IBS write: fd
,09-07 11:38:09.818  3003  3007 I WCNSS_FILTER: Direction(0): bytes: 6 : bytes_written: 6
09-07 11:38:09.818  3003  3003 I WCNSS_FILTER: do_write: IBS write: fc
09-07 11:38:09.818  2587  2780 D BtGatt.GattService: [GSIM LOG]: increaseScanCount 4 Battery : com.test.thalitest : 328
09-07 11:38:09.818  3003  3003 I WCNSS_FILTER: Direction(1): bytes: 9 : bytes_written: 9
09-07 11:38:09.818  2587  2756 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=6, status=0, action=1
09-07 11:38:09.818  2587  2756 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,09-07 11:38:09.818  1250  1310 V AlarmManager:  remove PendingIntent] PendingIntent{9791698: PendingIntentRecord{45887f2 com.android.bluetooth broadcastIntent}}
09-07 11:38:09.818  2587  2767 D BtGatt.ScanManager: set filter index= 3 for clientIf= 6
09-07 11:38:09.818  2587  2767 D BtGatt.ScanManager: High Rssi Filter value is = -128
09-07 11:38:09.818  2587  2767 D BtGatt.ScanManager: Low Rssi Filter value is = -128
09-07 11:38:09.818  2587  2767 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0highRssiThreshold = -128lowRssiThreshold = -128matchmode is =2
,09-07 11:38:09.828  3003  3007 I WCNSS_FILTER: Direction(0): bytes: 22 : bytes_written: 22
09-07 11:38:09.828  3003  3003 I WCNSS_FILTER: Direction(1): bytes: 10 : bytes_written: 10
,09-07 11:38:09.828  2587  2756 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=0, availableSpace=15
09-07 11:38:09.828  2587  2756 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,09-07 11:38:09.828  2587  2767 D BtGatt.ScanManager: Starting BLE batch scan
09-07 11:38:09.828  2587  2767 D BtGatt.ScanManager: configuring batch scan storage, appIf 6
09-07 11:38:09.828  3003  3007 I WCNSS_FILTER: Direction(0): bytes: 6 : bytes_written: 6
09-07 11:38:09.828  1250  1313 V AlarmManager:  remove PendingIntent] PendingIntent{f011ef1: PendingIntentRecord{45887f2 com.android.bluetooth broadcastIntent}}
09-07 11:38:09.828  3003  3003 I WCNSS_FILTER: Direction(1): bytes: 8 : bytes_written: 8
09-07 11:38:09.828  3003  3007 I WCNSS_FILTER: Direction(0): bytes: 8 : bytes_written: 8
,09-07 11:38:09.828  3003  3003 I WCNSS_FILTER: Direction(1): bytes: 8 : bytes_written: 8
,09-07 11:38:09.828  2587  2756 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=6, status=0
09-07 11:38:09.828  2587  2756 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
09-07 11:38:09.828  3003  3007 I WCNSS_FILTER: Direction(0): bytes: 16 : bytes_written: 16
09-07 11:38:09.828  1250  2333 V AlarmManager:  remove PendingIntent] PendingIntent{a4dcad6: PendingIntentRecord{45887f2 com.android.bluetooth broadcastIntent}}
09-07 11:38:09.828  3003  3003 I WCNSS_FILTER: Direction(1): bytes: 8 : bytes_written: 8
,09-07 11:38:09.828  1250  2327 V AlarmManager:  remove PendingIntent] PendingIntent{e70c157: PendingIntentRecord{1350444 com.android.bluetooth broadcastIntent}}
09-07 11:38:09.828  2587  2756 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=1
09-07 11:38:09.828  2587  2756 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
09-07 11:38:09.828  2587  2780 D BtGatt.GattService: [GSIM LOG]: setScanTime : com.test.thalitest : 24554018
09-07 11:38:09.828  2587  2780 D BtGatt.GattService: [GSIM LOG]: setRequestedScanType : com.test.thalitest : 2
09-07 11:38:09.828  2587  2780 D BtGatt.GattService: [GSIM LOG]: setActualScanType : com.test.thalitest : 2
09-07 11:38:09.828  2587  2780 D BtGatt.GattService: [GSIM LOG]: updateScanTime: 0
09-07 11:38:09.828  2587  2780 D BtGatt.GattService: [GSIM LOG]: com.test.thalitest@LowLatency, R time : 0 => 0
09-07 11:38:09.828  2587  2780 D BtGatt.GattService: [GSIM LOG]: com.test.thalitest@LowLatency, A time : 0 => 0
09-07 11:38:09.828  2587  2780 D BtGatt.GattService: [GSIM LOG]: updateScanTime: 0
09-07 11:38:09.838  2587  2780 D BtGatt.GattService: [GSIM LOG]: com.test.thalitest@LowLatency, R time : 0 => 0
09-07 11:38:09.838  2587  2780 D BtGatt.GattService: [GSIM LOG]: com.test.thalitest@LowLatency, A time : 0 => 0
09-07 11:38:09.838  2587  2780 D BtGatt.GattService: [GSIM LOG]: setActualScanType : com.test.thalitest : 2
09-07 11:38:09.838  2587  2780 D BtGatt.GattService: [GSIM LOG]: updateScanTime: 0
09-07 11:38:09.838  2587  2780 D BtGatt.GattService: [GSIM LOG]: com.test.thalitest@LowLatency, R time : 0 => 0
,09-07 11:38:09.838  2587  2780 D BtGatt.GattService: [GSIM LOG]: com.test.thalitest@LowLatency, A time : 0 => 0
09-07 11:38:09.838  2587  2780 D BtGatt.GattService: [GSIM LOG]: setScanTime : com.test.thalitest : 24554018
,09-07 11:38:09.838  1250  1721 V AlarmManager:  remove PendingIntent] PendingIntent{b77b92d: PendingIntentRecord{45887f2 com.android.bluetooth broadcastIntent}}
,09-07 11:38:09.838  1250  1986 V AlarmManager:  remove PendingIntent] PendingIntent{233be62: PendingIntentRecord{45887f2 com.android.bluetooth broadcastIntent}}
,09-07 11:38:09.838  1250  2674 V AlarmManager:  remove PendingIntent] PendingIntent{5d61bf3: PendingIntentRecord{45887f2 com.android.bluetooth broadcastIntent}}
,09-07 11:38:09.848  1250  2327 V AlarmManager:  remove PendingIntent] PendingIntent{9a020b0: PendingIntentRecord{45887f2 com.android.bluetooth broadcastIntent}}
,09-07 11:38:09.848  1250  1964 V AlarmManager:  remove PendingIntent] PendingIntent{b43bb29: PendingIntentRecord{45887f2 com.android.bluetooth broadcastIntent}}
,09-07 11:38:09.848  1250  1310 V AlarmManager:  remove PendingIntent] PendingIntent{9935eae: PendingIntentRecord{45887f2 com.android.bluetooth broadcastIntent}}
,09-07 11:38:10.308  5989  5989 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: true, is advertising: false
09-07 11:38:10.308  5989  5989 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
09-07 11:38:10.308  5989  5989 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,09-07 11:38:10.338   707   707 I MSM-irqbalance: Decided to move IRQ270 from CPU1 to CPU0
,09-07 11:38:10.828  3003  3066 I WCNSS_FILTER: do_write: IBS write: fe
09-07 11:38:10.828  3003  3066 I WCNSS_FILTER: ibs_msm_serial_clock_vote: vote UART CLK OFF using UART driver's ioctl()
,09-07 11:38:10.828  1250  1590 V AlarmManager: Expired Alarm result :4
,09-07 11:38:10.838  2587  2587 D BtGatt.ScanManager: awakened up at time 184252
09-07 11:38:10.838  1250  1250 V AlarmManager: ___SyncScheduler (v3) ACTIVATED___
09-07 11:38:10.838  1250  1250 V AlarmManagerEXT: <AppSync3 Whitelist>
09-07 11:38:10.838  1250  1250 V AlarmManagerEXT: (AppSync) ### 0 added ###
09-07 11:38:10.838  2587  2767 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
,09-07 11:38:10.838  3003  3007 I WCNSS_FILTER: ibs_msm_serial_clock_vote: vote UART CLK ON using UART driver's ioctl()
09-07 11:38:10.838  3003  3007 I WCNSS_FILTER: do_write: IBS write: fd
09-07 11:38:10.838  1694  1694 D KeyguardUpdateMonitor: received broadcast android.intent.action.TIME_TICK
09-07 11:38:10.838  1694  1694 D KeyguardUpdateMonitor: handleTimeUpdate
,09-07 11:38:10.838  3003  3007 I WCNSS_FILTER: Direction(0): bytes: 6 : bytes_written: 6,
09-07 11:38:10.838  3003  3003 I WCNSS_FILTER: do_write: IBS write: fc
09-07 11:38:10.838  3003  3003 I WCNSS_FILTER: Direction(1): bytes: 52 : bytes_written: 52
09-07 11:38:10.838  1250  2333 V AlarmManager:  remove PendingIntent] PendingIntent{b3e0e5: PendingIntentRecord{45887f2 com.android.bluetooth broadcastIntent}}
09-07 11:38:10.848  3003  3007 I WCNSS_FILTER: Direction(0): bytes: 6 : bytes_written: 6
,09-07 11:38:10.848  1694  1694 D Clock   : received broadcast android.intent.action.TIME_TICK,
09-07 11:38:10.848  3003  3003 I WCNSS_FILTER: Direction(1): bytes: 78 : bytes_written: 78
,09-07 11:38:10.848  3003  3007 I WCNSS_FILTER: Direction(0): bytes: 6 : bytes_written: 6
,09-07 11:38:10.848  3003  3003 I WCNSS_FILTER: Direction(1): bytes: 53 : bytes_written: 53
,09-07 11:38:10.848  3003  3007 I WCNSS_FILTER: Direction(0): bytes: 6 : bytes_written: 6
09-07 11:38:10.848  3003  3003 I WCNSS_FILTER: Direction(1): bytes: 78 : bytes_written: 78
09-07 11:38:10.848  3003  3007 I WCNSS_FILTER: Direction(0): bytes: 6 : bytes_written: 6
,09-07 11:38:10.848  3003  3003 I WCNSS_FILTER: Direction(1): bytes: 78 : bytes_written: 78
09-07 11:38:10.848  3003  3007 I WCNSS_FILTER: Direction(0): bytes: 6 : bytes_written: 6
09-07 11:38:10.848  3003  3003 I WCNSS_FILTER: Direction(1): bytes: 78 : bytes_written: 78
,09-07 11:38:10.848  3003  3007 I WCNSS_FILTER: Direction(0): bytes: 6 : bytes_written: 6
,09-07 11:38:10.848  3003  3003 I WCNSS_FILTER: Direction(1): bytes: 10 : bytes_written: 10
,09-07 11:38:10.848  2587  2756 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=6
09-07 11:38:10.848  2587  2756 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
09-07 11:38:10.858  1250  1720 V AlarmManager:  remove PendingIntent] PendingIntent{13ab7ba: PendingIntentRecord{1350444 com.android.bluetooth broadcastIntent}}
09-07 11:38:10.848  2587  2756 D BtGatt.GattService: current time is 184269733678
09-07 11:38:10.858  2587  2756 D BtGatt.GattService: Batch record : [114, -26, -120, -14, -77, 77, 1, -128, -49, 19, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 6, -88, -127, -107, -23, 95, 111, 0, 35, 97, 126, -92, 22, -56, 1, -128, -62, 1, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92, 107, 58, 19, -9, 93, -60, 1, -128, -83, 2, 0, 30, 14, 9, 66, 114, 97, 99, 101, 108, 105, 53, 45, 52, 57, 53, 53, 2, 1, 5, 11, -1, -25, -2, 0, 1, -60, 93, -9, 19, 58, 107, 0, 81, 34, 97, 112, -14, -5, 1, -128, -78, 3, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112, 37, -47, 14, -113, 116, -46, 1, -128, -81, 11, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113, -46, -4, -117, 6, 105, -37, 1, -128, -64, 15, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
09-07 11:38:10.858  2587  2756 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 6, -88, -127, -107, -23, 95, 111]
,09-07 11:38:10.858  2587  2756 D ScanRecord: parseFromBytes
09-07 11:38:10.858  2587  2756 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
09-07 11:38:10.858  2587  2756 D ScanRecord: parseFromBytes
09-07 11:38:10.858  1250  2674 V AlarmManager:  remove PendingIntent] PendingIntent{dd7166b: PendingIntentRecord{45887f2 com.android.bluetooth broadcastIntent}}
09-07 11:38:10.858  2587  2756 D ScanRecord: first manudata for manu ID
09-07 11:38:10.858  2587  2756 D BtGatt.GattService: ScanRecord : [14, 9, 66, 114, 97, 99, 101, 108, 105, 53, 45, 52, 57, 53, 53, 2, 1, 5, 11, -1, -25, -2, 0, 1, -60, 93, -9, 19, 58, 107]
,09-07 11:38:10.858  2587  2756 D ScanRecord: parseFromBytes
09-07 11:38:10.858  2587  2756 D ScanRecord: first manudata for manu ID
09-07 11:38:10.858  2587  2756 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
09-07 11:38:10.858  2587  2756 D ScanRecord: parseFromBytes
09-07 11:38:10.858  2587  2756 D ScanRecord: first manudata for manu ID
09-07 11:38:10.858  2587  2756 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
,09-07 11:38:10.858  2587  2756 D ScanRecord: parseFromBytes
09-07 11:38:10.858  2587  2756 D ScanRecord: first manudata for manu ID
09-07 11:38:10.858  2587  2756 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
09-07 11:38:10.858  2587  2756 D ScanRecord: parseFromBytes
09-07 11:38:10.858  2587  2756 D ScanRecord: first manudata for manu ID
09-07 11:38:10.858  5989  5999 D ScanRecord: parseFromBytes
09-07 11:38:10.858  5989  5999 D ScanRecord: first manudata for manu ID
09-07 11:38:10.858  5989  5999 D ScanRecord: parseFromBytes
,09-07 11:38:10.858  5989  5999 D ScanRecord: parseFromBytes
09-07 11:38:10.858  5989  5999 D ScanRecord: first manudata for manu ID
09-07 11:38:10.858  5989  5999 D ScanRecord: parseFromBytes
09-07 11:38:10.858  5989  5999 D ScanRecord: first manudata for manu ID
09-07 11:38:10.858  5989  5999 D ScanRecord: parseFromBytes
09-07 11:38:10.858  5989  5999 D ScanRecord: first manudata for manu ID
09-07 11:38:10.858  5989  5999 D ScanRecord: parseFromBytes
09-07 11:38:10.858  5989  5999 D ScanRecord: first manudata for manu ID
,09-07 11:38:10.858  1250  1990 V AlarmManager:  remove PendingIntent] PendingIntent{f2b55c8: PendingIntentRecord{45887f2 com.android.bluetooth broadcastIntent}}
,09-07 11:38:10.868  5989  5989 V org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addOrUpdateDiscoveredPeer: New peer, [<no peer name> A8:81:95:E9:5F:6F 6], added - the peer count is 1
09-07 11:38:10.868  5989  5989 I io.jxcore.node.ConnectionHelper: onPeerDiscovered: [<no peer name> A8:81:95:E9:5F:6F 6], Bluetooth address: A8:81:95:E9:5F:6F, device name: '', device address: ''
,09-07 11:38:10.868  1250  1310 V AlarmManager:  remove PendingIntent] PendingIntent{a46a661: PendingIntentRecord{45887f2 com.android.bluetooth broadcastIntent}}
,09-07 11:38:10.868  1250  2333 V AlarmManager:  remove PendingIntent] PendingIntent{6cc9586: PendingIntentRecord{45887f2 com.android.bluetooth broadcastIntent}}
,09-07 11:38:10.878  1250  2327 V AlarmManager:  remove PendingIntent] PendingIntent{64eae47: PendingIntentRecord{45887f2 com.android.bluetooth broadcastIntent}}
,09-07 11:38:10.878  1250  1721 V AlarmManager:  remove PendingIntent] PendingIntent{a840674: PendingIntentRecord{45887f2 com.android.bluetooth broadcastIntent}}
,09-07 11:38:10.878  1250  1720 V AlarmManager:  remove PendingIntent] PendingIntent{5e6479d: PendingIntentRecord{45887f2 com.android.bluetooth broadcastIntent}}
,09-07 11:38:10.888  1250  2674 V AlarmManager:  remove PendingIntent] PendingIntent{d4c8412: PendingIntentRecord{45887f2 com.android.bluetooth broadcastIntent}}
,09-07 11:38:10.888  1694  1694 D DateView: received broadcast android.intent.action.TIME_TICK
09-07 11:38:10.888  1250  1964 V AlarmManager:  remove PendingIntent] PendingIntent{1bde7e3: PendingIntentRecord{45887f2 com.android.bluetooth broadcastIntent}}
,09-07 11:38:10.898  1250  1990 V AlarmManager:  remove PendingIntent] PendingIntent{71515e0: PendingIntentRecord{45887f2 com.android.bluetooth broadcastIntent}},
,09-07 11:38:10.908  1250  1721 V AlarmManager:  remove PendingIntent] PendingIntent{be4c099: PendingIntentRecord{45887f2 com.android.bluetooth broadcastIntent}}
,09-07 11:38:10.918  1250  1990 V AlarmManager:  remove PendingIntent] PendingIntent{26acf5e: PendingIntentRecord{45887f2 com.android.bluetooth broadcastIntent}}
,09-07 11:38:10.918  1250  1721 V AlarmManager:  remove PendingIntent] PendingIntent{35d1f3f: PendingIntentRecord{45887f2 com.android.bluetooth broadcastIntent}},
09-07 11:38:10.918  4782  4782 D [WeatherWidget(1210)]  WeatherService: {[EC3334F14841398C8B464A72D0E61AB74266231DDCB0F9D898ABD6AE7EAFE9924B51C1628AB73EB6B27EF850A160BD15DCFDBE96F420541C45EF3419D3AD67E2]}
,09-07 11:38:10.928  4782  4782 D [WeatherWidget(1210)]  : {[15C09394A4E9AFE55A5C62F22AB3FC5902EB2A2150B6646A86F2B3102D669614]}
,09-07 11:38:11.848  3003  3066 I WCNSS_FILTER: do_write: IBS write: fe
09-07 11:38:11.848  3003  3066 I WCNSS_FILTER: ibs_msm_serial_clock_vote: vote UART CLK OFF using UART driver's ioctl()
,09-07 11:38:11.858  1250  1590 V AlarmManager: Expired Alarm result :4
,09-07 11:38:11.858  2587  2587 D BtGatt.ScanManager: awakened up at time 185276
,09-07 11:38:11.858  2587  2767 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
,09-07 11:38:11.868  3003  3007 I WCNSS_FILTER: ibs_msm_serial_clock_vote: vote UART CLK ON using UART driver's ioctl()
09-07 11:38:11.868  3003  3007 I WCNSS_FILTER: do_write: IBS write: fd
09-07 11:38:11.868  1250  1994 V AlarmManager:  remove PendingIntent] PendingIntent{db7cd55: PendingIntentRecord{45887f2 com.android.bluetooth broadcastIntent}}
,09-07 11:38:11.868  3003  3007 I WCNSS_FILTER: Direction(0): bytes: 6 : bytes_written: 6
09-07 11:38:11.868  3003  3003 I WCNSS_FILTER: do_write: IBS write: fc
09-07 11:38:11.868  3003  3003 I WCNSS_FILTER: Direction(1): bytes: 53 : bytes_written: 53
,09-07 11:38:11.868  3003  3007 I WCNSS_FILTER: Direction(0): bytes: 6 : bytes_written: 6
09-07 11:38:11.868  1250  1313 V AlarmManager:  remove PendingIntent] PendingIntent{c90836a: PendingIntentRecord{45887f2 com.android.bluetooth broadcastIntent}}
09-07 11:38:11.868  3003  3003 I WCNSS_FILTER: Direction(1): bytes: 53 : bytes_written: 53
09-07 11:38:11.868  3003  3007 I WCNSS_FILTER: Direction(0): bytes: 6 : bytes_written: 6
09-07 11:38:11.868  3003  3003 I WCNSS_FILTER: Direction(1): bytes: 52 : bytes_written: 52
,09-07 11:38:11.868  3003  3007 I WCNSS_FILTER: Direction(0): bytes: 6 : bytes_written: 6
09-07 11:38:11.878  3003  3003 I WCNSS_FILTER: Direction(1): bytes: 52 : bytes_written: 52
,09-07 11:38:11.878  3003  3007 I WCNSS_FILTER: Direction(0): bytes: 6 : bytes_written: 6
09-07 11:38:11.878  3003  3003 I WCNSS_FILTER: Direction(1): bytes: 10 : bytes_written: 10
,09-07 11:38:11.878  2587  2756 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=4
09-07 11:38:11.878  2587  2756 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
09-07 11:38:11.878  2587  2756 D BtGatt.GattService: current time is 185292120761
09-07 11:38:11.878  1250  1310 V AlarmManager:  remove PendingIntent] PendingIntent{f8e705b: PendingIntentRecord{1350444 com.android.bluetooth broadcastIntent}}
09-07 11:38:11.878  2587  2756 D BtGatt.GattService: Batch record : [107, 58, 19, -9, 93, -60, 1, -128, -82, 19, 0, 30, 14, 9, 66, 114, 97, 99, 101, 108, 105, 53, 45, 52, 57, 53, 53, 2, 1, 5, 11, -1, -25, -2, 0, 1, -60, 93, -9, 19, 58, 107, 0, -46, -4, -117, 6, 105, -37, 1, -128, -65, 16, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 0, 78, -20, -96, 83, -39, -56, 1, -128, -50, 18, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 5, 8, -20, -87, 80, 118, 39, 0, 114, -26, -120, -14, -77, 77, 1, -128, -48, 18, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 6, -88, -127, -107, -23, 95, 111, 0]
09-07 11:38:11.878  2587  2756 D BtGatt.GattService: ScanRecord : [14, 9, 66, 114, 97, 99, 101, 108, 105, 53, 45, 52, 57, 53, 53, 2, 1, 5, 11, -1, -25, -2, 0, 1, -60, 93, -9, 19, 58, 107]
09-07 11:38:11.878  1250  1990 V AlarmManager:  remove PendingIntent] PendingIntent{743c0f8: PendingIntentRecord{45887f2 com.android.bluetooth broadcastIntent}}
,09-07 11:38:11.878  2587  2756 D ScanRecord: parseFromBytes
09-07 11:38:11.878  2587  2756 D ScanRecord: first manudata for manu ID
09-07 11:38:11.878  2587  2756 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74]
09-07 11:38:11.878  2587  2756 D ScanRecord: parseFromBytes
09-07 11:38:11.878  2587  2756 D ScanRecord: first manudata for manu ID
09-07 11:38:11.878  2587  2756 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 5, 8, -20, -87, 80, 118, 39]
09-07 11:38:11.878  2587  2756 D ScanRecord: parseFromBytes
,09-07 11:38:11.878  2587  2756 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 6, -88, -127, -107, -23, 95, 111]
09-07 11:38:11.878  2587  2756 D ScanRecord: parseFromBytes
09-07 11:38:11.878  5989  6000 D ScanRecord: parseFromBytes
09-07 11:38:11.878  5989  6000 D ScanRecord: parseFromBytes
09-07 11:38:11.878  5989  6000 D ScanRecord: parseFromBytes
09-07 11:38:11.878  5989  6000 D ScanRecord: first manudata for manu ID
09-07 11:38:11.878  5989  6000 D ScanRecord: parseFromBytes
09-07 11:38:11.878  5989  6000 D ScanRecord: first manudata for manu ID
09-07 11:38:11.878  5989  5989 V org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addOrUpdateDiscoveredPeer: New peer, [<no peer name> 08:EC:A9:50:76:27 5], added - the peer count is 2
09-07 11:38:11.878  5989  5989 V org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addOrUpdateDiscoveredPeer: Timestamp of peer [<no peer name> A8:81:95:E9:5F:6F 6] updated - the peer count is 2
09-07 11:38:11.878  5989  5989 I io.jxcore.node.ConnectionHelper: onPeerDiscovered: [<no peer name> 08:EC:A9:50:76:27 5], Bluetooth address: 08:EC:A9:50:76:27, device name: '', device address: ''
,09-07 11:38:11.888  1250  2010 V AlarmManager:  remove PendingIntent] PendingIntent{474e9d1: PendingIntentRecord{45887f2 com.android.bluetooth broadcastIntent}}
,09-07 11:38:11.888  1250  2327 V AlarmManager:  remove PendingIntent] PendingIntent{dab6c36: PendingIntentRecord{45887f2 com.android.bluetooth broadcastIntent}}
,09-07 11:38:11.888  1250  2396 V AlarmManager:  remove PendingIntent] PendingIntent{4b9b737: PendingIntentRecord{45887f2 com.android.bluetooth broadcastIntent}}
,09-07 11:38:11.898  1250  1990 V AlarmManager:  remove PendingIntent] PendingIntent{46ff4a4: PendingIntentRecord{45887f2 com.android.bluetooth broadcastIntent}}
,09-07 11:38:11.898  1250  1986 V AlarmManager:  remove PendingIntent] PendingIntent{b0d520d: PendingIntentRecord{45887f2 com.android.bluetooth broadcastIntent}}
,09-07 11:38:11.898  1250  1964 V AlarmManager:  remove PendingIntent] PendingIntent{6ba15c2: PendingIntentRecord{45887f2 com.android.bluetooth broadcastIntent}}
,09-07 11:38:11.908  1250  1721 V AlarmManager:  remove PendingIntent] PendingIntent{5e88fd3: PendingIntentRecord{45887f2 com.android.bluetooth broadcastIntent}}
,09-07 11:38:12.818  5989  6040 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-07 11:38:12.818  5989  6040 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 11:38:12.818  5989  6040 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-07 11:38:12.818  5989  6040 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@da2634f not in the list
09-07 11:38:12.818  5989  6040 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-07 11:38:12.818  5989  6040 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-07 11:38:12.818  5989  6040 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-07 11:38:12.818  5989  6040 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-07 11:38:12.818  5989  6040 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-07 11:38:12.818  5989  6040 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,09-07 11:38:12.818  5989  6040 D BluetoothAdapter: STATE_ON
,09-07 11:38:12.818  5989  6040 D BluetoothAdapter: STATE_ON
09-07 11:38:12.818  5989  6040 D BluetoothLeScanner: Stop Scan
,09-07 11:38:12.828  2587  3153 D BtGatt.GattService: [GSIM LOG]: getCallingProcessName: com.test.thalitest
09-07 11:38:12.828  2587  3153 D BtGatt.GattService: [GSIM LOG]: getCallingProcessName: com.test.thalitest
09-07 11:38:12.828  2587  3153 D BtGatt.GattService: stopScan() - queue size =1
,09-07 11:38:12.828  2587  2780 E BtGatt.GattService: [GSIM LOG]: gsimLogHandler: com.test.thalitest, msg: MESSAGE_STOP_SCAN
09-07 11:38:12.828  2587  2780 D BtGatt.GattService: [GSIM LOG]: gsimLogHandler: prevDate: 7, currDate: 7
09-07 11:38:12.828  2587  2780 D BtGatt.GattService: [GSIM LOG]: updateScanTime: 0
09-07 11:38:12.828  2587  2767 D BtGatt.ScanManager: filter size is 1
09-07 11:38:12.828  2587  2780 D BtGatt.GattService: [GSIM LOG]: com.test.thalitest@LowLatency, R time : 0 => 0
09-07 11:38:12.828  2587  2780 D BtGatt.GattService: [GSIM LOG]: com.test.thalitest@LowLatency, A time : 0 => 0
09-07 11:38:12.828  2587  2767 D BtGatt.ScanManager: delete FilterIndex - 3
09-07 11:38:12.828  2587  2780 D BtGatt.GattService: [GSIM LOG]: remove : com.test.thalitest at  BLE_SCAN_ACTUAL_DB
09-07 11:38:12.828  2587  2780 D BtGatt.GattService: [GSIM LOG]: remove : com.test.thalitest at  BLE_SCAN_REQUESTED_DB
09-07 11:38:12.828  2587  6414 D BtGatt.GattService: unregisterClient() - clientIf=6
09-07 11:38:12.828  3003  3007 I WCNSS_FILTER: Direction(0): bytes: 7 : bytes_written: 7
09-07 11:38:12.828  5989  6040 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-07 11:38:12.828  5989  6040 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
09-07 11:38:12.828  1250  1964 V AlarmManager:  remove PendingIntent] PendingIntent{9b710: PendingIntentRecord{45887f2 com.android.bluetooth broadcastIntent}}
09-07 11:38:12.828  5989  6040 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
09-07 11:38:12.828  5989  6040 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
09-07 11:38:12.828  5989  6040 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
09-07 11:38:12.828  3003  3003 I WCNSS_FILTER: do_write: IBS write: fc
,09-07 11:38:12.828  3003  3003 I WCNSS_FILTER: Direction(1): bytes: 10 : bytes_written: 10,
09-07 11:38:12.828  5989  6040 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
09-07 11:38:12.828  2587  2756 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=1, availableSpace=16
09-07 11:38:12.828  2587  2756 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,09-07 11:38:12.828  2587  2767 D BtGatt.ScanManager: stopping BLe Batch
09-07 11:38:12.828  5989  6040 D BluetoothAdapter: STATE_ON
,09-07 11:38:12.828  3003  3007 I WCNSS_FILTER: Direction(0): bytes: 16 : bytes_written: 16
09-07 11:38:12.828  1250  1986 V AlarmManager:  remove PendingIntent] PendingIntent{4a0209: PendingIntentRecord{45887f2 com.android.bluetooth broadcastIntent}}
09-07 11:38:12.828  3003  3003 I WCNSS_FILTER: Direction(1): bytes: 8 : bytes_written: 8
09-07 11:38:12.828  5989  6040 D BluetoothAdapter: STATE_ON
,09-07 11:38:12.828  5989  6040 D BluetoothLeAdvertiser: stop advertising
09-07 11:38:12.828  5989  6040 D BluetoothLeAdvertiser: wrapper is null
09-07 11:38:12.828  5989  6040 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-07 11:38:12.828  5989  6040 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-07 11:38:12.828  5989  6040 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-07 11:38:12.828  2587  2756 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=0
09-07 11:38:12.828  2587  2756 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,09-07 11:38:12.828  2587  2767 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
09-07 11:38:12.838  5989  6040 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-07 11:38:12.838  5989  6040 I org.thaliproject.p2p.btconnectorlib.utils.PeerModel: clear
09-07 11:38:12.838  3003  3007 I WCNSS_FILTER: Direction(0): bytes: 6 : bytes_written: 6
,09-07 11:38:12.838  3003  3003 I WCNSS_FILTER: Direction(1): bytes: 10 : bytes_written: 10
09-07 11:38:12.838  1250  1721 V AlarmManager:  remove PendingIntent] PendingIntent{817cc0e: PendingIntentRecord{45887f2 com.android.bluetooth broadcastIntent}}
,09-07 11:38:12.838  2587  2756 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=0
09-07 11:38:12.838  1250  1964 V AlarmManager:  remove PendingIntent] PendingIntent{322562f: PendingIntentRecord{1350444 com.android.bluetooth broadcastIntent}}
09-07 11:38:12.838  2587  2756 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
09-07 11:38:12.838  5989  6040 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6808adc not in the list
09-07 11:38:12.838  5989  6040 D io.jxcore.node.ConnectivityMonitor: stop
09-07 11:38:12.838  5989  6040 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 11:38:12.838  5989  6040 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-07 11:38:12.838  5989  5989 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-07 11:38:12.838  5989  5989 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-07 11:38:12.838  1250  2396 V AlarmManager:  remove PendingIntent] PendingIntent{33b343c: PendingIntentRecord{1350444 com.android.bluetooth broadcastIntent}}
09-07 11:38:12.838  5989  5989 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,09-07 11:38:12.838  5989  6040 I io.jxcore.node.StartStopOperationHandler: updateBeaconAdExtraInformation: New value: 6
09-07 11:38:12.838  5989  6040 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBeaconAdExtraInformation: 5 -> 6
09-07 11:38:12.838  5989  6040 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
09-07 11:38:12.838  5989  6040 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should start/stop everything
09-07 11:38:12.838  5989  6040 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
09-07 11:38:12.838  5989  6040 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-07 11:38:12.838  5989  6040 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
09-07 11:38:12.838  5989  6040 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
09-07 11:38:12.838  5989  6040 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
09-07 11:38:12.838  5989  6040 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
09-07 11:38:12.838  5989  6040 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: true
09-07 11:38:12.838  5989  6040 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-07 11:38:12.838  5989  6040 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-07 11:38:12.838  5989  5989 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
,09-07 11:38:12.848  5989  6593 D BluetoothSocket: bindListen(): myUserId = 0
09-07 11:38:12.848  1250  2010 V AlarmManager:  remove PendingIntent] PendingIntent{da55828: PendingIntentRecord{45887f2 com.android.bluetooth broadcastIntent}}
09-07 11:38:12.848  5989  6593 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-07 11:38:12.848  5989  6040 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,09-07 11:38:12.848  5989  6040 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,09-07 11:38:12.848  5989  6593 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
09-07 11:38:12.848  1250  1721 V AlarmManager:  remove PendingIntent] PendingIntent{732e941: PendingIntentRecord{45887f2 com.android.bluetooth broadcastIntent}}
,09-07 11:38:12.848  5989  6040 D BluetoothAdapter: STATE_ON
,09-07 11:38:12.858  5989  6040 D BluetoothAdapter: STATE_ON
,09-07 11:38:12.858  5989  6040 D BluetoothAdapter: STATE_ON
,09-07 11:38:12.858  1250  1721 V AlarmManager:  remove PendingIntent] PendingIntent{d054ee6: PendingIntentRecord{45887f2 com.android.bluetooth broadcastIntent}}
09-07 11:38:12.858  5989  6040 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,09-07 11:38:12.858  5989  6040 D BluetoothAdapter: STATE_ON
,09-07 11:38:12.858  5989  6040 D BluetoothAdapter: STATE_ON
,09-07 11:38:12.858  5989  6040 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
09-07 11:38:12.858  5989  6040 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
09-07 11:38:12.858  5989  6040 D BluetoothAdapter: STATE_ON
,09-07 11:38:12.858  5989  6040 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
,09-07 11:38:12.858  5989  6040 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "44:78:3E:EB:95:EE"
09-07 11:38:12.858  5989  6040 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 06 44 78 3E EB 95 EE
09-07 11:38:12.858  5989  6040 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[6, 68, 120, 62, -21, -107, -18]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
09-07 11:38:12.858  5989  6040 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[6, 68, 120, 62, -21, -107, -18]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
09-07 11:38:12.858  5989  6040 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting...
,09-07 11:38:12.868  5989  6040 D BluetoothAdapter: STATE_ON
,09-07 11:38:12.868  5989  6040 D BluetoothAdapter: STATE_ON
09-07 11:38:12.868  5989  6040 D BluetoothLeAdvertiser: start advertising
,09-07 11:38:12.868  5989  6040 D BluetoothAdapter: STATE_ON
,09-07 11:38:12.868  2587  6414 D BtGatt.GattService: registerClient() - UUID=4577869d-00cf-4799-887c-edccffc8daf6
,09-07 11:38:12.918  2587  2756 D BtGatt.GattService: onClientRegistered() - UUID=4577869d-00cf-4799-887c-edccffc8daf6, clientIf=6
09-07 11:38:12.918  5989  6000 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=6
,09-07 11:38:12.918  2587  6415 D BtGatt.GattService: [GSIM LOG]: startMultiAdvertising: 2
,09-07 11:38:12.918  2587  6415 D BtGatt.GattService: [GSIM LOG]: getCallingProcessName: com.test.thalitest
09-07 11:38:12.918  2587  6415 D BtGatt.GattService: [GSIM LOG]: getCallingProcessName: com.test.thalitest
09-07 11:38:12.918  2587  2765 D BtGatt.AdvertiseManager: message : 0
,09-07 11:38:12.918  2587  2765 D BtGatt.AdvertiseManager: number of adv instance running = 0
09-07 11:38:12.918  2587  2780 E BtGatt.GattService: [GSIM LOG]: gsimLogHandler: com.test.thalitest, msg: MESSAGE_START_ADV
09-07 11:38:12.918  2587  2780 D BtGatt.GattService: [GSIM LOG]: gsimLogHandler: prevDate: 7, currDate: 7
09-07 11:38:12.918  2587  2765 D BtGatt.AdvertiseManager: size of list is =0
,09-07 11:38:12.918  2587  2765 D BtGatt.AdvertiseManager: starting advertising
,09-07 11:38:12.918  2587  2765 D BtGatt.AdvertiseManager: isStandardAdv = false
,09-07 11:38:12.918  3003  3007 I WCNSS_FILTER: Direction(0): bytes: 28 : bytes_written: 28
,09-07 11:38:12.918  3003  3003 I WCNSS_FILTER: do_write: IBS write: fc
09-07 11:38:12.918  1250  2333 V AlarmManager:  remove PendingIntent] PendingIntent{530dc27: PendingIntentRecord{45887f2 com.android.bluetooth broadcastIntent}}
,09-07 11:38:12.918  3003  3003 I WCNSS_FILTER: Direction(1): bytes: 8 : bytes_written: 8
,09-07 11:38:12.918  3003  3007 I WCNSS_FILTER: Direction(0): bytes: 7 : bytes_written: 7
,09-07 11:38:12.918  3003  3003 I WCNSS_FILTER: Direction(1): bytes: 8 : bytes_written: 8
09-07 11:38:12.928  2587  2756 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=6, status=0
,09-07 11:38:12.928  1250  1990 V AlarmManager:  remove PendingIntent] PendingIntent{60bced4: PendingIntentRecord{45887f2 com.android.bluetooth broadcastIntent}}
,09-07 11:38:12.928  2587  2765 D BtGatt.AdvertiseManager: starting multi advertising
09-07 11:38:12.928  3003  3007 I WCNSS_FILTER: Direction(0): bytes: 38 : bytes_written: 38
09-07 11:38:12.928  2587  2780 D BtGatt.GattService: [GSIM LOG]: increaseAdvCount : com.test.thalitest : 24
09-07 11:38:12.928  2587  2780 D BtGatt.GattService: [GSIM LOG]: setAdvTime : com.test.thalitest@LowLatency : 24554018
09-07 11:38:12.928  2587  2780 D BtGatt.GattService: [GSIM LOG]: setAdvType : com.test.thalitest@LowLatency : 2
09-07 11:38:12.928  2587  2780 D BtGatt.GattService: [GSIM LOG]: updateAdvTime
,09-07 11:38:12.928  1250  2327 V AlarmManager:  remove PendingIntent] PendingIntent{803d87d: PendingIntentRecord{45887f2 com.android.bluetooth broadcastIntent}}
09-07 11:38:12.928  2587  2780 D BtGatt.GattService: [GSIM LOG]: com.test.thalitest@LowLatency, R time : 2 => 2
09-07 11:38:12.928  3003  3003 I WCNSS_FILTER: Direction(1): bytes: 8 : bytes_written: 8
09-07 11:38:12.928  2587  2756 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=6, status=0
09-07 11:38:12.928  2587  2765 D BtGatt.AdvertiseManager: logClientsSet() - status: 0
09-07 11:38:12.928  2587  2765 D BtGatt.AdvertiseManager: clientIf: 6, Mode: 2, TxPowerLevel: 3, isConnectable: false, Timeout: 0
09-07 11:38:12.928  2587  2765 D BtGatt.AdvertiseManager: postCallback clientIf = 6 status = 0
09-07 11:38:12.928  2587  2765 D BtGatt.GattService: onMultipleAdvertiseCallback() clientIf=6, status=0, isStart=true
09-07 11:38:12.928  5989  5999 D BluetoothLeAdvertiser: onMultiAdvertiseCallback status = 0 isStart = true
09-07 11:38:12.928  5989  6040 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
09-07 11:38:12.928  5989  6040 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,09-07 11:38:12.928  5989  6040 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,09-07 11:38:12.928  1250  1310 V AlarmManager:  remove PendingIntent] PendingIntent{3477372: PendingIntentRecord{45887f2 com.android.bluetooth broadcastIntent}}
,09-07 11:38:12.928  5989  5989 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
,09-07 11:38:12.928  5989  5989 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess
09-07 11:38:12.928  5989  5989 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
09-07 11:38:12.928  5989  5989 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: true
09-07 11:38:12.928  5989  5989 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [ADVERTISING]
09-07 11:38:12.928  5989  5989 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [ADVERTISING]
,09-07 11:38:12.938  1250  1964 V AlarmManager:  remove PendingIntent] PendingIntent{6c513c3: PendingIntentRecord{45887f2 com.android.bluetooth broadcastIntent}}
,09-07 11:38:12.938  5989  5989 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: true
09-07 11:38:12.938  5989  5989 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: true
,09-07 11:38:12.938  1250  2333 V AlarmManager:  remove PendingIntent] PendingIntent{9c10440: PendingIntentRecord{45887f2 com.android.bluetooth broadcastIntent}}
,09-07 11:38:13.438  5989  5989 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: true
,09-07 11:38:13.438  5989  5989 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
09-07 11:38:13.438  5989  5989 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,09-07 11:38:13.928  3003  3066 I WCNSS_FILTER: do_write: IBS write: fe,
09-07 11:38:13.928  3003  3066 I WCNSS_FILTER: ibs_msm_serial_clock_vote: vote UART CLK OFF using UART driver's ioctl()
,09-07 11:38:14.978  1250  3553 D SSRM:s  : SIOP:: AP = 290, PST = 313 (W:14), CP = 35, LCD = 0
,09-07 11:38:14.978  1250  3553 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
,09-07 11:38:18.938  5989  6040 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-07 11:38:18.938  5989  6040 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
09-07 11:38:18.938  5989  6040 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
09-07 11:38:18.938  5989  6040 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
09-07 11:38:18.938  5989  6040 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-07 11:38:18.938  5989  6040 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
09-07 11:38:18.938  5989  6040 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@da2634f not in the list
09-07 11:38:18.938  5989  6040 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-07 11:38:18.938  5989  6040 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-07 11:38:18.938  5989  6040 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-07 11:38:18.938  5989  6040 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-07 11:38:18.938  5989  6040 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-07 11:38:18.938  5989  5989 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
09-07 11:38:18.938  5989  6593 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
09-07 11:38:18.938  5989  6593 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
09-07 11:38:18.938  5989  6593 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
,09-07 11:38:18.938  5989  6040 D BluetoothAdapter: STATE_ON
,09-07 11:38:18.938  5989  6040 D BluetoothAdapter: STATE_ON
09-07 11:38:18.938  5989  6040 D BluetoothLeScanner: could not find callback wrapper
09-07 11:38:18.938  5989  6040 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-07 11:38:18.938  5989  6040 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
09-07 11:38:18.938  5989  6040 D BluetoothAdapter: STATE_ON
,09-07 11:38:18.938  5989  6040 D BluetoothAdapter: STATE_ON
09-07 11:38:18.938  5989  6040 D BluetoothLeAdvertiser: stop advertising
,09-07 11:38:18.948  2587  3109 D BtGatt.GattService: [GSIM LOG]: getCallingProcessName: com.test.thalitest
09-07 11:38:18.948  2587  3109 D BtGatt.GattService: [GSIM LOG]: getCallingProcessName: com.test.thalitest
09-07 11:38:18.948  2587  2765 D BtGatt.AdvertiseManager: message : 1
09-07 11:38:18.948  2587  2780 E BtGatt.GattService: [GSIM LOG]: gsimLogHandler: com.test.thalitest, msg: MESSAGE_STOP_ADV
09-07 11:38:18.948  2587  2780 D BtGatt.GattService: [GSIM LOG]: gsimLogHandler: prevDate: 7, currDate: 7,
09-07 11:38:18.948  2587  2780 D BtGatt.GattService: [GSIM LOG]: updateAdvTime
09-07 11:38:18.948  2587  2780 D BtGatt.GattService: [GSIM LOG]: com.test.thalitest@LowLatency, R time : 2 => 2
09-07 11:38:18.948  2587  2780 D BtGatt.GattService: [GSIM LOG]: remove : com.test.thalitest@LowLatency at  BLE_ADV_REQUESTED_DB
09-07 11:38:18.948  2587  2765 D BtGatt.AdvertiseManager: stop advertise for client =  6
09-07 11:38:18.948  2587  2765 D BtGatt.AdvertiseManager: stop advertising, standardAdvClientIf = 0 client.clientIf = 6
09-07 11:38:18.948  2587  2765 D BtGatt.AdvertiseManager: logClientsSet() - status: -1
09-07 11:38:18.948  1250  2674 V AlarmManager:  remove PendingIntent] PendingIntent{ffa7f79: PendingIntentRecord{45887f2 com.android.bluetooth broadcastIntent}}
09-07 11:38:18.948  3003  3007 I WCNSS_FILTER: ibs_msm_serial_clock_vote: vote UART CLK ON using UART driver's ioctl()
,09-07 11:38:18.948  3003  3007 I WCNSS_FILTER: do_write: IBS write: fd
,09-07 11:38:18.948  3003  3007 I WCNSS_FILTER: Direction(0): bytes: 7 : bytes_written: 7
09-07 11:38:18.958  3003  3003 I WCNSS_FILTER: do_write: IBS write: fc
,09-07 11:38:18.958  3003  3003 I WCNSS_FILTER: Direction(1): bytes: 8 : bytes_written: 8
09-07 11:38:18.958  2587  2756 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=6, status=0
,09-07 11:38:18.958  3003  3007 E WCNSS_FILTER: do_read: read returned 0, err = Success, read bytes: 0, expected: 0
09-07 11:38:18.958  2587  2756 D BtGatt.GattService: Client app is not null!
09-07 11:38:18.958  3003  3007 I WCNSS_FILTER: Direction(0): bytes: 4 : bytes_written: 4
09-07 11:38:18.958  5989  6000 D BluetoothLeAdvertiser: onMultiAdvertiseCallback status = 0 isStart = false
09-07 11:38:18.958  1250  1721 V AlarmManager:  remove PendingIntent] PendingIntent{11554be: PendingIntentRecord{45887f2 com.android.bluetooth broadcastIntent}}
09-07 11:38:18.958  2587  2604 D BtGatt.GattService: unregisterClient() - clientIf=6
09-07 11:38:18.958  5989  6040 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-07 11:38:18.958  5989  6040 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
09-07 11:38:18.958  5989  6040 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: false
09-07 11:38:18.958  5989  6040 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [ADVERTISING] to [NOT_STARTED]
09-07 11:38:18.958  5989  6040 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [ADVERTISING] -> [NOT_STARTED]
09-07 11:38:18.958  5989  6040 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
09-07 11:38:18.958  5989  6040 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-07 11:38:18.958  5989  6040 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,09-07 11:38:18.958  5989  6040 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-07 11:38:18.958  1250  2674 V AlarmManager:  remove PendingIntent] PendingIntent{edb291f: PendingIntentRecord{45887f2 com.android.bluetooth broadcastIntent}}
09-07 11:38:18.958  5989  6040 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6808adc not in the list
09-07 11:38:18.958  5989  6040 D io.jxcore.node.ConnectivityMonitor: stop
09-07 11:38:18.958  5989  6040 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-07 11:38:18.958  5989  6040 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-07 11:38:18.958  5989  6040 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-07 11:38:18.958  5989  6040 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 11:38:18.958  5989  6040 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-07 11:38:18.958  5989  6040 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@da2634f not in the list
09-07 11:38:18.958  5989  6040 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-07 11:38:18.958  5989  6040 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6808adc not in the list
09-07 11:38:18.958  5989  6040 D io.jxcore.node.ConnectivityMonitor: stop
09-07 11:38:18.958  5989  6040 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 11:38:18.958  5989  6040 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-07 11:38:18.958  5989  6040 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: true, is advertising: true - Start operation: Should start/stop everything
09-07 11:38:18.958  5989  6040 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
09-07 11:38:18.958  5989  6040 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
09-07 11:38:18.958  5989  6040 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-07 11:38:18.958  5989  6040 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should affect listening to advertisements only
,09-07 11:38:18.968  5989  6040 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
09-07 11:38:18.968  5989  5989 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-07 11:38:18.968  5989  5989 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-07 11:38:18.968  5989  5989 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
09-07 11:38:18.968  5989  5989 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,09-07 11:38:18.968  3003  3003 I WCNSS_FILTER: Direction(1): bytes: 15 : bytes_written: 15
,09-07 11:38:18.968  3003  3007 I WCNSS_FILTER: Direction(0): bytes: 12 : bytes_written: 12
09-07 11:38:18.968  1250  1964 V AlarmManager:  remove PendingIntent] PendingIntent{6d2246c: PendingIntentRecord{45887f2 com.android.bluetooth broadcastIntent}}
,09-07 11:38:18.968  3003  3003 I WCNSS_FILTER: Direction(1): bytes: 8 : bytes_written: 8
09-07 11:38:18.968  5989  6596 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 322, name: My test thread name)
,09-07 11:38:18.968  1250  1720 V AlarmManager:  remove PendingIntent] PendingIntent{61a9a35: PendingIntentRecord{45887f2 com.android.bluetooth broadcastIntent}}
,09-07 11:38:18.978  1250  1310 V AlarmManager:  remove PendingIntent] PendingIntent{e4dfeca: PendingIntentRecord{45887f2 com.android.bluetooth broadcastIntent}}
,09-07 11:38:19.468  5989  5989 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false,
,09-07 11:38:19.968  3003  3066 I WCNSS_FILTER: do_write: IBS write: fe,
09-07 11:38:19.968  3003  3066 I WCNSS_FILTER: ibs_msm_serial_clock_vote: vote UART CLK OFF using UART driver's ioctl()
,09-07 11:38:20.338   707   707 I MSM-irqbalance: Decided to move IRQ166 from CPU3 to CPU0,
,09-07 11:38:20.968  5989  6040 I io.jxcore.node.StreamCopyingThread: close: Thread ID: 322
09-07 11:38:20.968  5989  6040 D io.jxcore.node.StreamCopyingThread: closeStreams: Streams closed (thread ID: 322, name: My test thread name)
,09-07 11:38:20.978  5989  6597 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 323, name: My test thread name)
09-07 11:38:20.978  5989  6597 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 323, thread name: My test thread name)
09-07 11:38:20.978  5989  6597 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 323, name: My test thread name), during the lifetime of the thread the total number of bytes read was 22 and the total number of bytes written 22
,09-07 11:38:20.978  5989  6040 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
,09-07 11:38:20.978  5989  6598 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 327, name: My test thread name)
,09-07 11:38:20.978  5989  6598 E io.jxcore.node.StreamCopyingThread: Failed to write to the output stream (thread ID: 327, thread name: My test thread name): Test exception.
09-07 11:38:20.978  5989  6598 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 327, name: My test thread name), during the lifetime of the thread the total number of bytes read was 22 and the total number of bytes written 0
,09-07 11:38:20.978  5989  6040 E com.test.thalitest.ThaliTestRunner: Proper state of BT is set when switched on
09-07 11:38:20.978  5989  6040 E com.test.thalitest.ThaliTestRunner: Expected: is <false>
09-07 11:38:20.978  5989  6040 E com.test.thalitest.ThaliTestRunner:      but: was <true>
09-07 11:38:20.978  5989  6040 D com.test.thalitest.ThaliTestRunner: Total number of executed tests: 82
09-07 11:38:20.978  5989  6040 D com.test.thalitest.ThaliTestRunner: Number of passed tests: 81
09-07 11:38:20.978  5989  6040 D com.test.thalitest.ThaliTestRunner: Number of failed tests:  1
09-07 11:38:20.978  5989  6040 D com.test.thalitest.ThaliTestRunner: Number of ignored tests: 0
09-07 11:38:20.978  5989  6040 D com.test.thalitest.ThaliTestRunner: Total duration: 84514 ms
,09-07 11:38:20.988  5989  6040 I jxcore-log: Total number of executed tests:  82
09-07 11:38:20.988  5989  6040 I jxcore-log: 
09-07 11:38:20.988  5989  6040 I jxcore-log: Number of passed tests:  81
09-07 11:38:20.988  5989  6040 I jxcore-log: 
09-07 11:38:20.988  5989  6040 I jxcore-log: Number of failed tests:  1
09-07 11:38:20.988  5989  6040 I jxcore-log: 
,09-07 11:38:20.988  5989  6040 I jxcore-log: Number of ignored tests:  0
09-07 11:38:20.988  5989  6040 I jxcore-log: 
09-07 11:38:20.988  5989  6040 I jxcore-log: Total duration:  84514
09-07 11:38:20.988  5989  6040 I jxcore-log: 
,09-07 11:38:20.988  5989  6040 I jxcore-log: Failed to execute UT.,
09-07 11:38:20.988  5989  6040 I jxcore-log: 
,09-07 11:38:20.988  5989  6040 I jxcore-log: ****TEST_LOGGER:[PROCESS_ON_EXIT_FAILED]****
09-07 11:38:20.988  5989  6040 I jxcore-log: 
,09-07 11:38:20.998  5989  6040 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-07 11:38:20.998  5989  6040 I jxcore-log: 
09-07 11:38:20.998  5989  6040 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-07 11:38:20.998  5989  6040 I jxcore-log: 
09-07 11:38:20.998  5989  6040 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}
09-07 11:38:20.998  5989  6040 I jxcore-log: 
09-07 11:38:20.998  5989  6040 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
09-07 11:38:20.998  5989  6040 I jxcore-log: 
09-07 11:38:20.998  5989  6040 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}
09-07 11:38:20.998  5989  6040 I jxcore-log: 
09-07 11:38:21.008  5989  6040 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-07 11:38:21.008  5989  6040 I jxcore-log: 
09-07 11:38:21.008  5989  6040 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}
09-07 11:38:21.008  5989  6040 I jxcore-log: 
09-07 11:38:21.008  5989  6040 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
09-07 11:38:21.008  5989  6040 I jxcore-log: 
,09-07 11:38:21.008  5989  6040 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-07 11:38:21.008  5989  6040 I jxcore-log: 
,09-07 11:38:21.008  5989  6040 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}
09-07 11:38:21.008  5989  6040 I jxcore-log: 
,09-07 11:38:21.008  5989  6040 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
09-07 11:38:21.008  5989  6040 I jxcore-log: 
,09-07 11:38:21.008  5989  6040 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-07 11:38:21.008  5989  6040 I jxcore-log: 
,09-07 11:38:21.018  5989  6040 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
09-07 11:38:21.018  5989  6040 I jxcore-log: 
,09-07 11:38:21.018  5989  6040 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
09-07 11:38:21.018  5989  6040 I jxcore-log: 
09-07 11:38:21.018  5989  6040 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
09-07 11:38:21.018  5989  6040 I jxcore-log: 
09-07 11:38:21.018  5989  6040 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-07 11:38:21.018  5989  6040 I jxcore-log: 
,09-07 11:38:21.018  5989  6040 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-07 11:38:21.018  5989  6040 I jxcore-log: 
09-07 11:38:21.018  5989  6040 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
09-07 11:38:21.018  5989  6040 I jxcore-log: 
,09-07 11:38:21.018  5989  6040 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
09-07 11:38:21.018  5989  6040 I jxcore-log: 
09-07 11:38:21.018  5989  6040 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-07 11:38:21.018  5989  6040 I jxcore-log: 
09-07 11:38:21.018  5989  6040 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-07 11:38:21.018  5989  6040 I jxcore-log: 
09-07 11:38:21.018  5989  6040 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
09-07 11:38:21.018  5989  6040 I jxcore-log: 
,09-07 11:38:21.018  5989  6040 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
09-07 11:38:21.018  5989  6040 I jxcore-log: 
,09-07 11:38:21.028  5989  6040 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-07 11:38:21.028  5989  6040 I jxcore-log: 
,09-07 11:38:21.028  5989  6040 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-07 11:38:21.028  5989  6040 I jxcore-log: 
09-07 11:38:21.028  5989  6040 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-07 11:38:21.028  5989  6040 I jxcore-log: 
,09-07 11:38:21.028  5989  6040 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-07 11:38:21.028  5989  6040 I jxcore-log: 
,09-07 11:38:21.028  5989  6040 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-07 11:38:21.028  5989  6040 I jxcore-log: 
,09-07 11:38:21.028  5989  6040 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}
09-07 11:38:21.028  5989  6040 I jxcore-log: 
,09-07 11:38:21.028  5989  6040 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
09-07 11:38:21.028  5989  6040 I jxcore-log: 
,09-07 11:38:21.028  5989  6040 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
09-07 11:38:21.028  5989  6040 I jxcore-log: 
,09-07 11:38:21.028  5989  6040 I jxcore-log: DEBUG thaliMobileNativeWrapper: Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state
09-07 11:38:21.028  5989  6040 I jxcore-log: 
,09-07 11:38:21.028  5989  6040 I jxcore-log: DEBUG thaliMobileNativeWrapper: Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state
09-07 11:38:21.028  5989  6040 I jxcore-log: 
,09-07 11:38:21.028  5989  6040 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}
09-07 11:38:21.028  5989  6040 I jxcore-log: 
,09-07 11:38:21.028  5989  6040 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false},
09-07 11:38:21.028  5989  6040 I jxcore-log: 
,09-07 11:38:21.188  5989  6596 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 322, name: My test thread name), during the lifetime of the thread the total number of bytes read was 165 and the total number of bytes written 165
,09-07 11:38:21.488  6599  6599 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<,
,09-07 11:38:21.498  6599  6599 D AndroidRuntime: CheckJNI is OFF,
09-07 11:38:21.498  6599  6599 D AndroidRuntime: readGMSProperty: start
09-07 11:38:21.498  6599  6599 D AndroidRuntime: readGMSProperty: already setted!!
,09-07 11:38:21.498  6599  6599 D AndroidRuntime: propertySet: couldn't set property (it is from app)
09-07 11:38:21.498  6599  6599 D AndroidRuntime: readGMSProperty: could not set the property(default)!!
,09-07 11:38:21.498  6599  6599 D AndroidRuntime: readGMSProperty: end
09-07 11:38:21.498  6599  6599 D AndroidRuntime: addProductProperty: start
,09-07 11:38:21.548  6599  6599 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat,
,09-07 11:38:21.588  6599  6599 I Radio-JNI: register_android_hardware_Radio DONE
,09-07 11:38:21.588  6599  6599 E AffinityControl: AffinityControl: registerfunction enter
,09-07 11:38:21.608  6599  6599 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
,09-07 11:38:21.638  1250  1990 D PackageManager: START PACKAGE DELETE: observer{85145659}
09-07 11:38:21.638  1250  1990 D PackageManager: pkg{<packageName>}
09-07 11:38:21.638  1250  1990 D PackageManager: user{0}
09-07 11:38:21.638  1250  1990 D PackageManager: caller{2000}
09-07 11:38:21.638  1250  1990 D PackageManager: flags{2}
09-07 11:38:21.638  1250  1990 D PersonaManagerService: isFromApprovedUnInstaller: uid, userId, appid : 2000 0 2000
09-07 11:38:21.638  1250  1990 D PersonaManagerService: isFromApprovedUnInstaller: isApproved : true
09-07 11:38:21.638  1250  1990 D PersonaManagerService: isFromApprovedUnInstaller: isApproved before exit: true
09-07 11:38:21.638  1250  1990 D PackageManager: deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag2
09-07 11:38:21.638  1250  1990 D PackageManager: deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag2
09-07 11:38:21.638  1250  1425 D PackageManager: [MSG] DELETE_PACKAGE_AS_USER
09-07 11:38:21.638  1250  1425 D PackageManagerService: deletePackage- pkg:com.test.thalitest, edmuserId:0
09-07 11:38:21.638  1250  1425 D PackageManagerService: deletePackage- pkg:com.test.thalitest, edmuserId:-1
09-07 11:38:21.638  1250  1425 D ApplicationPolicy: getApplicationUninstallationEnabled
09-07 11:38:21.638  1250  1425 D ApplicationPolicy: getApplicationUninstallationEnabled :  enabled true
,09-07 11:38:21.638  1250  1425 I PackageManager: !@  calling am.removeDeletedPkgsFromLru from PMS
09-07 11:38:21.638  1250  1425 D ActivityManager: removeDeletedPkgsFromLruStats called in AMS...com.test.thalitest
,09-07 11:38:21.638  1250  1425 D PackageManager: !@killApplicatoin: 10136, uninstall pkg
,09-07 11:38:21.638  1250  1425 I PackageManager: !@  calling am.removeDeletedPkgsFromLru from PMS
09-07 11:38:21.638  1250  1425 D ActivityManager: removeDeletedPkgsFromLruStats called in AMS...com.test.thalitest
09-07 11:38:21.638  1250  1378 I ActivityManager: Force stopping com.test.thalitest appid=10136 user=-1: uninstall pkg
09-07 11:38:21.638  1250  1378 D ActivityManager: removeProcessNameLocked mProcessNames.remove pid=5989 ,hash=160587112 ,name=com.test.thalitest
09-07 11:38:21.638  1250  1378 I ActivityManager: Killing 5989:com.test.thalitest/u0a136 (adj 0): stop com.test.thalitest cause uninstall pkg
09-07 11:38:21.638  1250  1378 D ActivityManager: isAutoRunBlockedApp:: com.test.thalitest, Auto Run ON
,09-07 11:38:21.658  1250  1378 D ActivityManager: mDVFSHelper.acquire()
,09-07 11:38:21.658  1250  1425 D AASAinstall: there is not AASApackages.xml file
,09-07 11:38:21.768  1250  1994 D GraphicsStats: Buffer count: 5
09-07 11:38:21.768  1250  1986 I WindowState: WIN DEATH: Window{6e8afc8 u0 d0 com.test.thalitest/com.test.thalitest.MainActivity}
09-07 11:38:21.768   445   468 I SurfaceFlinger: id=19 Removed NainActivit (6/11)
09-07 11:38:21.768  1250  2674 D ConnectivityService: ConnectivityService NetworkRequestInfo binderDied(NetworkRequest [ id=7, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ], android.os.BinderProxy@cf31b58)
09-07 11:38:21.768   445   468 E         : BitTube(): close sendFd (52)
09-07 11:38:21.768  1250  1630 D ConnectivityService: releasing NetworkRequest NetworkRequest [ id=7, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-07 11:38:21.768   445   468 E         : BitTube(): close sendFd (60)
09-07 11:38:21.768  1250  1630 D ConnectivityService: sending notification RELEASED for NetworkRequest [ id=7, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-07 11:38:21.768  1250  1630 E ConnectivityService: RemoteException caught trying to send a callback msg for NetworkRequest [ id=7, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,09-07 11:38:21.768   445   468 I SurfaceFlinger: id=19 Removed NainActivit (-2/11)
09-07 11:38:21.768   445   466 I SurfaceFlinger: id=19 Removed NainActivit (-2/11)
,09-07 11:38:21.918  1250  1425 W System.err: remove failed: ENOENT (No such file or directory) : /data/system/packages.xml.bak
,09-07 11:38:21.988  1250  1425 W System.err: remove failed: ENOENT (No such file or directory) : /data/system/users/0/package-restrictions.xml.bak
,09-07 11:38:21.988  1250  1378 W ActivityManager: Failed trying to unstop package com.test.thalitest: java.lang.IllegalArgumentException: Unknown package: com.test.thalitest
09-07 11:38:21.988  1250  1378 W PackageManager: Package com.test.thalitest is missing; assuming frozen
,09-07 11:38:21.988  1250  1378 E ActivityManager: Failure starting process com.test.thalitest
09-07 11:38:21.988  1250  1378 E ActivityManager: java.lang.RuntimeException: Package com.test.thalitest is frozen!
09-07 11:38:21.988  1250  1378 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:5290)
09-07 11:38:21.988  1250  1378 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:5206)
09-07 11:38:21.988  1250  1378 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:5042)
09-07 11:38:21.988  1250  1378 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.startSpecificActivityLocked(ActivityStackSupervisor.java:2674)
09-07 11:38:21.988  1250  1378 E ActivityManager: 	at com.android.server.am.ActivityStack.resumeTopActivityInnerLocked(ActivityStack.java:3504)
09-07 11:38:21.988  1250  1378 E ActivityManager: 	at com.android.server.am.ActivityStack.resumeTopActivityLocked(ActivityStack.java:2624)
09-07 11:38:21.988  1250  1378 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.resumeTopActivitiesLocked(ActivityStackSupervisor.java:5060)
09-07 11:38:21.988  1250  1378 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.resumeTopActivitiesLocked(ActivityStackSupervisor.java:5021)
09-07 11:38:21.988  1250  1378 E ActivityManager: 	at com.android.server.am.ActivityManagerService.handleAppDiedLocked(ActivityManagerService.java:7410)
09-07 11:38:21.988  1250  1378 E ActivityManager: 	at com.android.server.am.ActivityManagerService.removeProcessLocked(ActivityManagerService.java:9248)
09-07 11:38:21.988  1250  1378 E ActivityManager: 	at com.android.server.am.ActivityManagerService.killPackageProcessesLocked(ActivityManagerService.java:8870)
09-07 11:38:21.988  1250  1378 E ActivityManager: 	at com.android.server.am.ActivityManagerService.forceStopPackageLocked(ActivityManagerService.java:9025)
09-07 11:38:21.988  1250  1378 E ActivityManager: 	at com.android.server.am.ActivityManagerService.access$900(ActivityManagerService.java:467)
09-07 11:38:21.988  1250  1378 E ActivityManager: 	at com.android.server.am.ActivityManagerService$MainHandler.handleMessage(ActivityManagerService.java:2573)
09-07 11:38:21.988  1250  1378 E ActivityManager: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-07 11:38:21.988  1250  1378 E ActivityManager: 	at android.os.Looper.loop(Looper.java:158)
09-07 11:38:21.988  1250  1378 E ActivityManager: 	at android.os.HandlerThread.run(HandlerThread.java:61)
09-07 11:38:21.988  1250  1378 E ActivityManager: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
,09-07 11:38:21.988  1250  1378 W VirtualScreenManagerService: moveTaskBackToDisplayIfNeeded(): top activity or app is null
09-07 11:38:21.988  1250  1378 I ActivityManager:   Force finishing activity ActivityRecord{1935d77 u0 com.test.thalitest/.MainActivity t19}
,09-07 11:38:21.988   567   567 W keystore: ENTER clear_uid from uid 1000 for 10136
,09-07 11:38:21.988  1250  1425 I art     : Starting a blocking GC Explicit
,09-07 11:38:22.008  1250  1250 D GameManagerService: NotifyRunnable. pkg: com.samsung.android.MtpApplication, type: 4, isMinimized: false, isTunableApp: false
,09-07 11:38:22.008  1250  1378 V MARsPolicyManager: updatePackagesScore PackageInfo name -- com.samsung.android.MtpApplication
,09-07 11:38:22.008  1250  1378 D InputDispatcher: Focused application released
,09-07 11:38:22.028  1250  1417 W System.err: android.content.pm.PackageManager$NameNotFoundException: com.test.thalitest
,09-07 11:38:22.028  1250  1417 W System.err: 	at android.app.ApplicationPackageManager.getApplicationInfo(ApplicationPackageManager.java:390)
09-07 11:38:22.028  1250  1417 D SecWifiDisplayUtil: Metadata value : SecSettings2
09-07 11:38:22.028  1250  1417 W System.err: 	at com.android.internal.policy.PhoneWindow.installDecor(PhoneWindow.java:4721)
09-07 11:38:22.028  1250  1417 W System.err: 	at com.android.internal.policy.PhoneWindow.getDecorView(PhoneWindow.java:2248)
09-07 11:38:22.028  1250  1417 W System.err: 	at com.android.server.policy.PhoneWindowManager.addStartingWindow(PhoneWindowManager.java:4429)
09-07 11:38:22.028  1250  1417 W System.err: 	at com.android.server.wm.WindowManagerService$H.handleMessage(WindowManagerService.java:13541)
09-07 11:38:22.028  1250  1417 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-07 11:38:22.028  1250  1417 W System.err: 	at android.os.Looper.loop(Looper.java:158)
09-07 11:38:22.028  1250  1417 W System.err: 	at android.os.HandlerThread.run(HandlerThread.java:61)
09-07 11:38:22.028  1250  1417 W System.err: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
09-07 11:38:22.028  1250  1417 D ViewRootImpl: #1 mView = com.android.internal.policy.PhoneWindow$DecorView{3dfd70 V.E...... R.....ID 0,0-0,0}
09-07 11:38:22.028   445   445 I SurfaceFlinger: id=21 createSurf (1120x1269),1 flag=4, VSBConnecti
,09-07 11:38:22.028  1971  1971 D Launcher: onRestart, Launcher: 62537846
,09-07 11:38:22.028  1250  1417 D ViewRootImpl: #3 mView = null
09-07 11:38:22.028  1250  1417 W WindowManager: Attempted to add application window with unknown token Token{3433de4 ActivityRecord{1935d77 u0 com.test.thalitest/.MainActivity t19 f}}.  Aborting.
09-07 11:38:22.028  1250  1417 W WindowManager: Token{3433de4 ActivityRecord{1935d77 u0 com.test.thalitest/.MainActivity t19 f}} already running, starting window not displayed. Unable to add window -- token Token{3433de4 ActivityRecord{1935d77 u0 com.test.thalitest/.MainActivity t19 f}} is not valid; is your activity running?
09-07 11:38:22.028  1250  3553 D GameManagerService: identifyGamePackage. com.samsung.android.MtpApplication
09-07 11:38:22.028  1250  1417 W WindowManager: view not successfully added to wm, removing view
09-07 11:38:22.038  1971  1971 D Launcher: onStart, Launcher: 62537846
09-07 11:38:22.038  1971  1971 D Launcher.HomeView: onStart
09-07 11:38:22.038  1971  1971 D Launcher.MenuAppsGrid: updateGridSize:GRID_4x4 cellWidth:250  cellHeight:286
,09-07 11:38:22.038  1250  1417 W WindowManager: Exception when adding starting window
09-07 11:38:22.038  1250  1417 W WindowManager: java.lang.IllegalArgumentException: View=com.android.internal.policy.PhoneWindow$DecorView{3dfd70 V.E...... R.....ID 0,0-0,0} not attached to window manager
09-07 11:38:22.038  1250  1417 W WindowManager: 	at android.view.WindowManagerGlobal.findViewLocked(WindowManagerGlobal.java:454)
09-07 11:38:22.038  1250  1417 W WindowManager: 	at android.view.WindowManagerGlobal.removeView(WindowManagerGlobal.java:380)
09-07 11:38:22.038  1250  1417 W WindowManager: 	at android.view.WindowManagerImpl.removeViewImmediate(WindowManagerImpl.java:140)
09-07 11:38:22.038  1250  1417 W WindowManager: 	at com.android.server.policy.PhoneWindowManager.addStartingWindow(PhoneWindowManager.java:4486)
09-07 11:38:22.038  1250  1417 W WindowManager: 	at com.android.server.wm.WindowManagerService$H.handleMessage(WindowManagerService.java:13541)
09-07 11:38:22.038  1250  1417 W WindowManager: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-07 11:38:22.038  1250  1417 W WindowManager: 	at android.os.Looper.loop(Looper.java:158)
09-07 11:38:22.038  1250  1417 W WindowManager: 	at android.os.HandlerThread.run(HandlerThread.java:61)
09-07 11:38:22.038  1250  1417 W WindowManager: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
,09-07 11:38:22.038  1250  1990 D ActivityManager: post active user change for 0 fullscreen false isFloatingActivity() false isHomeActivity() false
09-07 11:38:22.038  1250  1990 D KnoxTimeoutHandler: postActiveUserChange [MsgParam] userId: 0 fullscreen is false showWhenlocked is false
09-07 11:38:22.038  1250  1250 D KnoxTimeoutHandler: handleActiveUserChange [MsgParam] userId: 0 fullscreen is false showWhenlocked is false
,09-07 11:38:22.038  1250  1250 I KnoxTimeoutHandler: Shared devices show user statefalse
09-07 11:38:22.038  1250  1250 I KnoxTimeoutHandler: Target Activity is not fullscreen. We will not show this activity0
,09-07 11:38:22.038  1971  6608 D WallpaperManager: 2048 / 2048 / 0
,09-07 11:38:22.048  1971  1971 V ActivityThread: updateVisibility : ActivityRecord{f4a80e6 token=android.os.BinderProxy@aa8634d {com.sec.android.app.launcher/com.sec.android.app.launcher.activities.LauncherActivity}} show : true
,09-07 11:38:22.058  1971  1971 V LauncherAppWidgetHostView: calculateWidgetSize: (target widgetsize)  using w/h 1480 636 span 6 2 (widgetid 2) [current Gridsize : GRID_4x4]
09-07 11:38:22.058  1971  1971 D LauncherAppWidgetHostView: calculateWidgetSize() widget = Pogoda i zegar(widget id = 2) result hostview size = 1480 x 636
09-07 11:38:22.058  1971  1971 D LauncherAppWidgetHostView: setResizeScaleResult() 1480/ 636 scaleToResize = 1.0(widget id = 2)
,09-07 11:38:22.068  1971  1971 V LauncherAppWidgetHostView: calculateWidgetSize: (target widgetsize)  using w/h 1480 308 span 6 1 (widgetid 3) [current Gridsize : GRID_4x4]
09-07 11:38:22.068  1971  1971 D LauncherAppWidgetHostView: calculateWidgetSize() widget = Aplikacja Google(widget id = 3) result hostview size = 1480 x 308
09-07 11:38:22.068  1971  1971 D LauncherAppWidgetHostView: setResizeScaleResult() 1480/ 308 scaleToResize = 1.0(widget id = 3)
,09-07 11:38:22.068  1971  1971 V LauncherAppWidgetHostView: calculateWidgetSize: (target widgetsize)  using w/h 1480 308 span 6 1 (widgetid 4) [current Gridsize : GRID_4x4]
09-07 11:38:22.068  1971  1971 D LauncherAppWidgetHostView: calculateWidgetSize() widget = Galaxy Apps(widget id = 4) result hostview size = 1480 x 308
09-07 11:38:22.068  1971  1971 D LauncherAppWidgetHostView: setResizeScaleResult() 1480/ 308 scaleToResize = 1.0(widget id = 4)
,09-07 11:38:22.068  1250  1994 V WindowStateAnimator: Finishing drawing window Window{7d8f638 u0 d0 com.samsung.android.MtpApplication/com.samsung.android.MtpApplication.USBConnection}: mDrawState=DRAW_PENDING
,09-07 11:38:22.078  1250  1417 D KnoxTimeoutHandler: notifyActivityDrawn [MsgParam] userId: 0 fullscreen is false showWhenlocked is false
,09-07 11:38:22.078   445   445 I SurfaceFlinger: id=22 createSurf (1152x192),1 flag=4, VSBConnecti
,09-07 11:38:22.078  1250  1250 D KnoxTimeoutHandler: activityDrawn [MsgParam] userId: 0 fullscreen is false showWhenlocked is false
09-07 11:38:22.078   445   445 I SurfaceFlinger: id=23 createSurf (1536x2048),1 flag=4, MauncherAct
09-07 11:38:22.078  1250  1250 I KnoxTimeoutHandler: SD activityfalse
,09-07 11:38:22.088  3774  3774 V ActivityThread: updateVisibility : ActivityRecord{8f25f46 token=android.os.BinderProxy@65eeb38 {com.samsung.android.MtpApplication/com.samsung.android.MtpApplication.USBConnection}} show : true
,09-07 11:38:22.088  1250  1417 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{260bf52 u0 com.samsung.android.MtpApplication/.USBConnection t18} time:195501
09-07 11:38:22.088  1250  1417 D ActivityManager: mDVFSHelper.release()
,09-07 11:38:22.098  1971  1971 D Launcher.HomeView: onStop
09-07 11:38:22.098  1971  1971 D capture : ----destroy
,09-07 11:38:22.108  1250  1721 V WindowStateAnimator: Finishing drawing window Window{f66c376 u0 d0 com.samsung.android.MtpApplication/com.samsung.android.MtpApplication.USBConnection}: mDrawState=DRAW_PENDING
,09-07 11:38:22.108  3774  3774 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@65eeb38 time:195524
,09-07 11:38:22.108  1250  1417 D KnoxTimeoutHandler: notifyActivityDrawn [MsgParam] userId: 0 fullscreen is false showWhenlocked is false
09-07 11:38:22.108  1250  1250 D KnoxTimeoutHandler: activityDrawn [MsgParam] userId: 0 fullscreen is false showWhenlocked is false
,09-07 11:38:22.108  1250  1250 I KnoxTimeoutHandler: SD activityfalse
,09-07 11:38:22.138  1971  2267 V RenderScript: 0x7f5ed34000 Launching thread(s), CPUs 8
,09-07 11:38:22.148  1250  1994 V WindowStateAnimator: Finishing drawing window Window{eab1d4e u0 d0 com.sec.android.app.launcher/com.sec.android.app.launcher.activities.LauncherActivity}: mDrawState=DRAW_PENDING
,09-07 11:38:22.158  1250  1417 D KnoxTimeoutHandler: notifyActivityDrawn [MsgParam] userId: 0 fullscreen is true showWhenlocked is false
09-07 11:38:22.158  1250  1417 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{3d778c4 u0 com.sec.android.app.launcher/.activities.LauncherActivity t15} time:195575
,09-07 11:38:22.158  1250  1250 D KnoxTimeoutHandler: activityDrawn [MsgParam] userId: 0 fullscreen is true showWhenlocked is false
09-07 11:38:22.158  1250  1250 I KnoxTimeoutHandler: SD activityfalse
09-07 11:38:22.158  1250  1250 I KnoxTimeoutHandler: Fullscreen and mCurrent is not KNOX user. Hence hide keyguard
,09-07 11:38:22.218  1250  1425 I art     : Explicit concurrent mark sweep GC freed 251023(15MB) AllocSpace objects, 40(2MB) LOS objects, 33% free, 29MB/43MB, paused 3.061ms total 225.726ms
,09-07 11:38:22.238  1250  1425 W PackageManager: Couldn't remove dex file for package:  at location /data/app/com.test.thalitest-1/base.apk, retcode=-1
,09-07 11:38:22.238  1250  1425 D AASAuninstall: userId = 0, info.removedAppID = 10136, info.uid = 10136, packageName = com.test.thalitest
09-07 11:38:22.238  1250  1425 D AASAinstall: there is not AASApackages.xml file
09-07 11:38:22.238  1250  1425 D PackageManager: result of delete: 1{85145659}
,09-07 11:38:22.238  6599  6599 I art     : System.exit called, status: 0
09-07 11:38:22.238  6599  6599 I AndroidRuntime: VM exiting with result code 0.
,09-07 11:38:22.248  1250  1425 D PackageManager: [MSG] START_CLEANING_PACKAGE packageName{com.test.thalitest}
09-07 11:38:22.248  1250  1425 D PackageManager: userId{-1}
09-07 11:38:22.248  1250  1425 D PackageManager: andCode{true}
,09-07 11:38:22.258  6619  6619 E Zygote  : v2
09-07 11:38:22.258  6619  6619 I libpersona: KNOX_SDCARD checking this for 10006
09-07 11:38:22.258  6619  6619 I libpersona: KNOX_SDCARD not a persona
09-07 11:38:22.258  6619  6619 E libpersona: scanKnoxPersonas
09-07 11:38:22.258  6619  6619 E libpersona: Couldn't open the File - /data/system/users/0/personalist.xml - No such file or directory
,09-07 11:38:22.258  6619  6619 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0013
,09-07 11:38:22.268  6619  6619 E Zygote  : accessInfo : 0
09-07 11:38:22.268  6619  6619 E libpersona: scanKnoxPersonas
09-07 11:38:22.268  6619  6619 E libpersona: Couldn't open the File - /data/system/users/0/personalist.xml - No such file or directory
,09-07 11:38:22.268  1250  1425 I ActivityManager: Start proc 6619:com.android.defcontainer/u0a6 for service com.android.defcontainer/.DefaultContainerService
,09-07 11:38:22.268  1250  1425 I ActivityManager: Force stopping com.test.thalitest appid=10136 user=0: pkg removed
09-07 11:38:22.268  1250  1425 D ActivityManager: removeProcessNameLocked mProcessNames.remove pid=0 ,hash=254245541 ,name=com.test.thalitest
,09-07 11:38:22.278  1250  1378 I ActivityManager: Exiting empty application process com.test.thalitest (null)
,09-07 11:38:22.278  1250  1378 D ActivityManager: isAutoRunBlockedApp:: com.test.thalitest, Auto Run ON
,09-07 11:38:22.288  1694  1694 D ShortcutManager: onReceive : android.intent.action.PACKAGE_REMOVED
09-07 11:38:22.288  1694  1694 D ShortcutManager: onReceive : Intent.EXTRA_REPLACING false,com.test.thalitest
,09-07 11:38:22.298  1694  1694 D CoverUpdateMonitor: received broadcast android.intent.action.PACKAGE_REMOVED
,09-07 11:38:22.298  1250  1592 I InputReader: Reconfiguring input devices.  changes=0x00000010
,09-07 11:38:22.308  1866  2402 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
,09-07 11:38:22.318  6619  6619 D TimaKeyStoreProvider: TimaSignature is unavailable
09-07 11:38:22.318  6619  6619 D ActivityThread: Added TimaKeyStore provider
,09-07 11:38:22.318  1250  1378 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{a433ef6 u0 android.intent.action.PACKAGE_REMOVED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{c22ba1d 3919:com.samsung.klmsagent/u0a16}
,09-07 11:38:22.318  1796  1796 I Recents_MultiWindowAppListInfo: android.intent.action.PACKAGE_REMOVE
,09-07 11:38:22.318  3919  3919 I KLMS-2.6.094: : KLMSAbstractReciever(): onReceive(): Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.samsung.klmsagent/.listner.MainReciver bqHint=4 VirtualScreenParam=Params{mDisplayId=-1, null, mFlags=0x00000000)} (has extras) } | timestamp: Wed Sep 07 11:38:22 GMT+02:00 2016
09-07 11:38:22.318  1250  1721 W ActivityManager: Permission Denial: Accessing service ComponentInfo{com.google.android.music/com.google.android.music.dial.DialMediaRouteProviderService} from pid=2494, uid=10093 that is not exported from uid 10091
,09-07 11:38:22.328  3919  3919 I KLMS-2.6.094: : KLMSAbstractReciever(): onReceive().END.
,09-07 11:38:22.328  1944  1944 D CarrierServiceBindHelper: Receive action: android.intent.action.PACKAGE_REMOVED
09-07 11:38:22.328  3919  3919 I KLMS-2.6.094: : KLMSIntentService(): onCreate()
,09-07 11:38:22.328  3919  3919 I KLMS-2.6.094: : KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,09-07 11:38:22.338  1250  1310 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{a433ef6 u0 android.intent.action.PACKAGE_REMOVED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{667d8b1 1250:system/1000}
,09-07 11:38:22.348  1250  1620 D NtpTrustedTime: currentTimeMillis() cache hit
09-07 11:38:22.348  1250  1620 V NetworkStats: removeUidsLocked() for UIDs [10136]
09-07 11:38:22.348  1250  1620 V NetworkStats: performPollLocked(flags=0x3)
,09-07 11:38:22.348  1250  1620 D NetworkStatsRecorder: entry.iface is null
09-07 11:38:22.348  1250  1620 D NetworkStatsRecorder: entry.iface is null
09-07 11:38:22.348  1250  1620 D NetworkStatsRecorder: entry.iface is null
09-07 11:38:22.348  1250  1620 D NetworkStatsRecorder: entry.iface is null
,09-07 11:38:22.348  1250  1620 V NetworkStats: performPollLocked() took 6ms
09-07 11:38:22.358  1250  1620 D NtpTrustedTime: currentTimeMillis() cache hit
,09-07 11:38:22.358  3919  3919 I KLMS-2.6.094: : KLMSUtility(): isTestMode(): product_ship: true | testApk: false
,09-07 11:38:22.358  1250  1250 V AlarmManager: Remove alarm for next reason : android.intent.action.PACKAGE_REMOVED : package: com.test.thalitest
09-07 11:38:22.358  1250  1250 I HarmonyEASService: onReceive : android.intent.action.PACKAGE_REMOVED for 0
,09-07 11:38:22.358  3919  6634 I KLMS-2.6.094: : KLMSIntentService(): onHandleIntent().START: Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.samsung.klmsagent/.service.KLMSIntentService bqHint=4 VirtualScreenParam=Params{mDisplayId=-1, null, mFlags=0x00000000)} (has extras) }
09-07 11:38:22.358  3919  6634 D KLMS-2.6.094: : KLMSIntentService(): PACKAGE_REMOVED
09-07 11:38:22.358  3919  6634 I KLMS-2.6.094: : Systemprocess(): listeningToPackageRemoved().START
09-07 11:38:22.358  3919  6634 I KLMS-2.6.094: : Systemprocess(): listeningToPackageRemoved().packageName: com.test.thalitest
09-07 11:38:22.358  3919  6634 I KLMS-2.6.094: : Systemprocess(): listeningToPackageRemovedforELM().START - com.test.thalitest
09-07 11:38:22.358  3919  6634 I KLMS-2.6.094: : MDMBridge(): getAllLicenseInfoFromSDK()
,09-07 11:38:22.358  1250  1250 D UniversalCredentialManagerService: inside mPkgReciever onReceive : android.intent.action.PACKAGE_REMOVED
09-07 11:38:22.358  1250  1250 D UniversalCredentialManagerService: ACTION_PACKAGE_REMOVED is called....
09-07 11:38:22.358  1250  1250 D KnoxMUMContainerPolicy: mPackageReceiver : action - android.intent.action.PACKAGE_REMOVED
09-07 11:38:22.358  1250  1250 I OTPFW   : PackageRemovalReceiver::onReceive Enter
09-07 11:38:22.358  1250  1250 D OTPFW   : PackageRemovalReceiver::onReceive deleting token for Pkg = com.test.thalitest uid = 10136 container id = 0
,09-07 11:38:22.358  1250  1621 D NtpTrustedTime: currentTimeMillis() cache hit
09-07 11:38:22.358  1250  1621 D NtpTrustedTime: currentTimeMillis() cache hit
09-07 11:38:22.358  1250  1250 I OTPFW   : ProvisionData::getAllEntries Enter
,09-07 11:38:22.358  1250  1250 E OTPFW   : ProvisionData::getAllEntries Table is empty
09-07 11:38:22.358  1250  1250 E SDAgentPackageStateReceiver: Not going to handle 'com.test.thalitest'!
09-07 11:38:22.358  3919  6634 I KLMS-2.6.094: : KLMSSystemProperties(): getBoolean(): ro.product_ship = true
09-07 11:38:22.368  3919  6634 I KLMS-2.6.094: : KLMSUtility(): isTestMode(): product_ship: true | testApk: false
,09-07 11:38:22.368  1250  1250 D UcmService: onReceive android.intent.action.PACKAGE_REMOVED
,09-07 11:38:22.368  1250  1250 D UcmService: Package update in userId-0 and uid-10136
,09-07 11:38:22.368  3919  6634 I KLMS-2.6.094: : MDMBridge(): getAllLicenseInfoFromSDK()
,09-07 11:38:22.368  1250  1250 D GameManager.DatabaseHelper: removeGame(), packageName: com.test.thalitest, ret: 0
09-07 11:38:22.368  1250  1250 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
09-07 11:38:22.368  1250  1250 V EnterpriseBillingAsyncHandler: packageModificationReceiver - onreceive - start - android.intent.action.PACKAGE_REMOVED
,09-07 11:38:22.368  1250  1655 V EnterpriseBillingPolicyInternal: packageModification -  start - android.intent.action.PACKAGE_REMOVED
09-07 11:38:22.368  1250  1655 V EnterpriseBillingPolicyInternal: uID is 10136
09-07 11:38:22.368  1250  1655 V EnterpriseBillingPolicyInternal: Removed Packageuid is0
09-07 11:38:22.368  1250  1655 V EnterpriseBillingPolicyStorage: getProfileForApplication - enter
09-07 11:38:22.368  6619  6637 W System.err: remove failed: ENOENT (No such file or directory) : /storage/emulated/0/Android/data/com.test.thalitest
09-07 11:38:22.368  3919  6634 D KLMS-2.6.094: : Systemprocess(): arrayLicenseInfo is null
09-07 11:38:22.368  1250  1655 V EnterpriseBillingPolicyStorage: getProfileForApplication - exit null : containerId = 0
09-07 11:38:22.368  1250  1655 V EnterpriseBillingPolicyInternal: packageModificationReceiver - onreceive - personal application - profile null
,09-07 11:38:22.368  6619  6637 W System.err: remove failed: ENOENT (No such file or directory) : /storage/emulated/0/Android/media/com.test.thalitest
,09-07 11:38:22.378  1250  1250 D SdpManagerService:  ActionReceiver::onReceive() Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 bqHint=4 VirtualScreenParam=Params{mDisplayId=-1, null, mFlags=0x00000000)} (has extras) }
,09-07 11:38:22.378  1250  1250 D SdpManagerService: ACTION_PACKAGE_REMOVED Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 bqHint=4 VirtualScreenParam=Params{mDisplayId=-1, null, mFlags=0x00000000)} (has extras) } DATA= package:com.test.thalitest UID 1000 userId 0
09-07 11:38:22.378  1250  1250 D SdpManagerService: ACTION_PACKAGE_REMOVED packageName:: com.test.thalitest
09-07 11:38:22.378  1250  1250 D EnterprisePartitionManager: SND -> {secure_fs remove_enc_dir}
,09-07 11:38:22.378  6619  6637 W System.err: remove failed: ENOENT (No such file or directory) : /storage/emulated/0/Android/obb/com.test.thalitest
,09-07 11:38:22.378   384   438 D epmd    : Partition obj created
09-07 11:38:22.378   384   438 D epmd    : Partition::dump============== 0
09-07 11:38:22.378  1250  1427 D EnterprisePartitionManager: RCV <-
09-07 11:38:22.378   384   438 D epmd    : Partition::mType > INTERNAL-SDCARD mSrcPath > /data/knox/secure_fs/enc_user mMntPath > /data/enc_user
09-07 11:38:22.378   384   438 D epmd    : Partition::SDP > not supported
09-07 11:38:22.378   384   438 E epmd    : removeEncPkgDir ERROR
09-07 11:38:22.378  1250  1250 D EnterprisePartitionManager: RMV <-
09-07 11:38:22.378   384   438 D epmd    : deleting Partition object.
09-07 11:38:22.378  1250  1250 D EnterprisePartitionManager: event : 281 3 remove_enc_dir failed
09-07 11:38:22.378   384   438 W FrameworkListener: Handler 'secure_fs' error (No such file or directory)
09-07 11:38:22.378  1250  1250 D SdpManagerService: start document   : 
,09-07 11:38:22.378  1250  1250 D SdpManagerService: start element    : engine_list
09-07 11:38:22.378  1250  1250 D SdpManagerService: start characters : 
09-07 11:38:22.378  3919  6634 D KLMS-2.6.094: : DataSource(): Fetched Data from data base count : 0
09-07 11:38:22.378  1250  1250 D SdpManagerService: start element    : engine
09-07 11:38:22.378  1250  1250 D SdpManagerService:  attribte alias: android_0
09-07 11:38:22.378  1250  1250 D SdpManagerService:  attribte id: 0
09-07 11:38:22.378  1250  1250 D SdpManagerService: end element      : engine
09-07 11:38:22.378  1250  1250 D SdpManagerService: start characters : 
09-07 11:38:22.378  1250  1250 D SdpManagerService: end element      : engine_list
09-07 11:38:22.378  1250  1250 D SdpManagerService: end document     : 
09-07 11:38:22.378  1250  1250 W System.err: mkdir failed: EEXIST (File exists) : /data/system/users/0
09-07 11:38:22.378  1250  1250 E SdpManagerService: cant make directory /data/system/users/0
09-07 11:38:22.378  1250  1250 D SdpManagerService: start document   : 
,09-07 11:38:22.378  1250  1250 D SdpManagerService: start element    : user
09-07 11:38:22.378  1250  1250 D SdpManagerService: end element      : user
09-07 11:38:22.378  1250  1250 D SdpUtil : num:0 index-0
09-07 11:38:22.378  1250  1250 D SdpUtil : detecected userId : 0
09-07 11:38:22.378  1250  1250 D SdpManagerService: end document     : 
09-07 11:38:22.378  1250  1250 E SdpManagerService: Can't find engine info [android_0]
09-07 11:38:22.378  1250  1250 V EnterpriseBillingAsyncHandler: packageModificationReceiver - onreceive - start - android.intent.action.PACKAGE_FULLY_REMOVED
,09-07 11:38:22.378  1250  1655 V EnterpriseBillingPolicyInternal: packageModification -  start - android.intent.action.PACKAGE_FULLY_REMOVED
09-07 11:38:22.378  1250  1655 V EnterpriseBillingPolicyInternal: uID is 10136
09-07 11:38:22.378  1250  1655 V EnterpriseBillingPolicyInternal: Removed Packageuid is0
09-07 11:38:22.378  1250  1655 V EnterpriseBillingPolicyStorage: getProfileForApplication - enter
,09-07 11:38:22.378  1250  1655 V EnterpriseBillingPolicyStorage: getProfileForApplication - exit null : containerId = 0
09-07 11:38:22.378  1250  3553 D SSRM:bb : MSG_TYPE_APP_REMOVED::
09-07 11:38:22.378  1250  1655 V EnterpriseBillingPolicyInternal: packageModificationReceiver - onreceive - personal application - profile null
09-07 11:38:22.388  1250  1990 D SettingsProvider: isChangeAllowed() : name = klm_eula_shown
09-07 11:38:22.388  1250  1990 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
09-07 11:38:22.388  1250  1990 D SecContentProvider: query(), uri = 17 selection = isSettingsChangesAllowed
09-07 11:38:22.388  1250  1990 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
09-07 11:38:22.388  1250  1990 D SettingsProvider: selectionArgs: false
09-07 11:38:22.388  1250  1990 D SettingsProvider: selectionArgs: 10016
,09-07 11:38:22.388  1250  1250 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{a433ef6 u0 android.intent.action.PACKAGE_REMOVED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{ef1b27 1866:com.google.android.gms.persistent/u0a10}
09-07 11:38:22.388  1250  1990 D SettingsProvider: ret = -1
09-07 11:38:22.388  1250  1250 V AlarmManagerEXT: com.test.thalitest(10136) is removed.
,09-07 11:38:22.388  1250  1415 D MARsDBManager: onChange - mSmartManagerObserver! Uri = content://com.samsung.android.sm/AppFreezer
09-07 11:38:22.388  1250  1415 V MARsDBManager: getManagedPackagesFromDB!
,09-07 11:38:22.398  1250  1986 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{a433ef6 u0 android.intent.action.PACKAGE_REMOVED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{7a2c63a 2207:com.google.android.gms/u0a10}
,09-07 11:38:22.398  2207  6639 D PkgBroadcastIntentOp: Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
09-07 11:38:22.398  1250  1310 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{a433ef6 u0 android.intent.action.PACKAGE_REMOVED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{7a2c63a 2207:com.google.android.gms/u0a10}
09-07 11:38:22.398  2207  6639 D AccountUtils: Clearing selected account for com.test.thalitest
,09-07 11:38:22.408  1250  1986 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{a433ef6 u0 android.intent.action.PACKAGE_REMOVED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{ef1b27 1866:com.google.android.gms.persistent/u0a10}
,09-07 11:38:22.408  1250  1250 W System.err: rename failed: EROFS (Read-only file system) : /data/system/harmony_third_party_apps.xml.tmp -> /data/system/harmony_third_party_apps.xml
,09-07 11:38:22.408  1250  1250 W System.err: remove failed: EROFS (Read-only file system) : /data/system/harmony_third_party_apps.xml.tmp
09-07 11:38:22.408  1250  1250 W System.err: java.io.FileNotFoundException: /data/system/harmony_third_party_apps.xml.tmp: open failed: EROFS (Read-only file system)
,09-07 11:38:22.408  1250  1250 W System.err: 	at libcore.io.IoBridge.open(IoBridge.java:452)
09-07 11:38:22.408  1866  1866 D GCM-PT  : Populating db of packages that use GCM
09-07 11:38:22.408  1250  1250 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
09-07 11:38:22.408  1250  1250 W System.err: 	at com.android.server.HarmonyEASService.saveHash(HarmonyEASService.java:303)
09-07 11:38:22.408  1250  1250 W System.err: 	at com.android.server.HarmonyEASService.access$000(HarmonyEASService.java:60)
09-07 11:38:22.408  1250  1250 W System.err: 	at com.android.server.HarmonyEASService$PackageHandler.handleMessage(HarmonyEASService.java:100)
09-07 11:38:22.408  1250  1250 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-07 11:38:22.408  1250  1250 W System.err: 	at android.os.Looper.loop(Looper.java:158)
09-07 11:38:22.408  1250  1250 W System.err: 	at com.android.server.SystemServer.run(SystemServer.java:515)
09-07 11:38:22.408  1250  1250 W System.err: 	at com.android.server.SystemServer.main(SystemServer.java:364)
09-07 11:38:22.408  1250  1250 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
09-07 11:38:22.408  1250  1250 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1230)
09-07 11:38:22.408  1250  1250 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1120)
09-07 11:38:22.408  1250  1250 W System.err: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
09-07 11:38:22.408  1250  1250 W System.err: 	at libcore.io.Posix.open(Native Method)
09-07 11:38:22.408  1250  1250 W System.err: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
09-07 11:38:22.408  1250  1250 W System.err: 	at libcore.io.IoBridge.open(IoBridge.java:438)
09-07 11:38:22.408  1250  1250 W System.err: 	... 11 more
09-07 11:38:22.408  1250  1250 W System.err: remove failed: EROFS (Read-only file system) : /data/system/harmony_third_party_apps.xml.tmp
09-07 11:38:22.408  1250  1250 D UniversalCredentialManagerService: ****MSG_CLEAN_INFO block started****
09-07 11:38:22.408  1250  1250 D UniversalCredentialManagerService: uid - 10136, userId-0
09-07 11:38:22.408  1250  1250 D UniversalCredentialManagerService: notifyChangeToPlugin is called for package uninstalled...
09-07 11:38:22.408  1250  1250 D UcmService: notifyChangeToPlugin event 12
09-07 11:38:22.408  1250  1250 D UcmService: checkCallerPermissionFor is called for method-notifyChangeToPlugin
09-07 11:38:22.408  1250  1250 I UcmService: checkIfNotify for cs Name = com.sec.smartcard.manager:com.samsung.ucs.agent.baiMobile Package name = com.sec.smartcard.manager
09-07 11:38:22.408  1250  1250 D UcmService: notifying to unmanaged plugin
09-07 11:38:22.408  2040  2062 E ucsBai_agentService: notifyChange NOT SUPPORTED
09-07 11:38:22.408  1250  1250 D UcmService: agentService com.sec.smartcard.manager:com.samsung.ucs.agent.baiMobile notify status - 0
09-07 11:38:22.408  1250  1250 D UcmService: agentService status-0
09-07 11:38:22.408  1250  1250 I UcmService: checkIfNotify for cs Name = com.samsung.ucs.agent.boot:com.samsung.ucs.agent.boot Package name = com.samsung.ucs.agent.boot
09-07 11:38:22.408  1250  1250 D UcmService: notifying to unmanaged plugin
09-07 11:38:22.408  2049  2068 D BootAgentService: notifyChange eventId-12
09-07 11:38:22.408  1250  1250 D UcmService: agentService com.samsung.ucs.agent.boot:com.samsung.ucs.agent.boot notify status - -1
09-07 11:38:22.408  1250  1250 D UcmService: agentService status--1
09-07 11:38:22.408  1250  1250 D UniversalCredentialManagerService: ****MSG_CLEAN_INFO block ended****
09-07 11:38:22.408  1250  1250 D UcmService: *****refreshAgentList userId-0 is called***
09-07 11:38:22.408  1250  1250 D UcmService: resolveAllowedAgents for user 0
09-07 11:38:22.408  1250  1250 D UcmService: found com.sec.smartcard.manager
09-07 11:38:22.408  1250  1250 D UcmService: found com.samsung.ucs.agent.boot
09-07 11:38:22.408  1250  1250 D UcmService: mPersisten,tServices size is 2
09-07 11:38:22.408  1250  1250 D UcmService: -------Processing started for agentPackageName----- -com.sec.smartcard.manager
09-07 11:38:22.408  1250  1250 D UcmService:   agentPackageName -com.sec.smartcard.manager is an active plugin
09-07 11:38:22.408  1250  1250 D UcmService:   Check if caller has UCS Plugin permission...
09-07 11:38:22.408  1250  1250 D UcmService:   Agent has UCS PLUGIN permission. Processing further...
09-07 11:38:22.408  1250  1250 D UcmService: -------Processing started for agentPackageName----- -com.samsung.ucs.agent.boot
09-07 11:38:22.408  1250  1250 D UcmService:   agentPackageName -com.samsung.ucs.agent.boot is an active plugin
09-07 11:38:22.408  1250  1250 D UcmService:   Check if caller has UCS Plugin permission...
09-07 11:38:22.408  1250  1250 D UcmService:   Agent has UCS PLUGIN permission. Processing further...
09-07 11:38:22.408  1250  1250 D UcmService:   agentPackageName com.samsung.ucs.agent.boot is system storage. Checking system signature
09-07 11:38:22.408  1250  1250 D UcmService:   Signature match
09-07 11:38:22.408  1250  1250 D UcmService:   Valid system storage found is com.samsung.ucs.agent.boot
09-07 11:38:22.408  1250  1250 W System.err: rename failed: EROFS (Read-only file system) : /data/system/registered_ucm_services/com.samsung.ucm.agent.xml -> /data/system/registered_ucm_services/com.samsung.ucm.agent.xml.bak
09-07 11:38:22.408  1250  1250 W AtomicFile: Couldn't rename file /data/system/registered_ucm_services/com.samsung.ucm.agent.xml to backup file /data/system/registered_ucm_services/com.samsung.ucm.agent.xml.bak
09-07 11:38:22.408  1250  1250 W UcmService: Error writing accounts
09-07 11:38:22.408  1250  1250 W UcmService: java.io.IOException: Couldn't create directory /data/system/registered_ucm_services/com.samsung.ucm.agent.xml
09-07 11:38:22.408  1250  1250 W UcmService: 	at android.util.AtomicFile.startWrite(AtomicFile.java:124)
09-07 11:38:22.408  1250  1250 W UcmService: 	at android.util.AtomicFile.startWrite(AtomicFile.java:100)
09-07 11:38:22.408  1250  1250 W UcmService: 	at com.samsung.ucm.ucmservice.CredentialManagerService.writePersistentServicesLocked(CredentialManagerService.java:810)
09-07 11:38:22.408  1250  1250 W UcmService: 	at com.samsung.ucm.ucmservice.CredentialManagerService.refreshAgentList(CredentialManagerService.java:573)
09-07 11:38:22.408  1250  1250 W UcmService: 	at com.samsung.ucm.ucmservice.CredentialManagerService.access$300(CredentialManagerService.java:95)
09-07 11:38:22.408  1250  1250 W UcmService: 	at com.samsung.ucm.ucmservice.CredentialManagerService$1.handleMessage(CredentialManagerService.java:188)
09-07 11:38:22.408  1250  1250 W UcmService: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-07 11:38:22.408  1250  1250 W UcmService: 	at android.os.Looper.loop(Looper.java:158)
09-07 11:38:22.408  1250  1250 W UcmService: 	at com.android.server.SystemServer.run(SystemServer.java:515)
09-07 11:38:22.408  1250  1250 W UcmService: 	at com.android.server.SystemServer.main(SystemServer.java:364)
09-07 11:38:22.408  1250  1250 W UcmService: 	at java.lang.reflect.Method.invoke(Native Method)
09-07 11:38:22.408  1250  1250 W UcmService: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1230)
09-07 11:38:22.408  1250  1250 W UcmService: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1120)
09-07 11:38:22.408  1250  1250 D UcmService: readPersistentServicesLocked is called...
09-07 11:38:22.408  1250  1250 D UcmService: PersistentServices  key-com.samsung.ucs.agent.boot:com.samsung.ucs.agent.boot
09-07 11:38:22.408  1250  1250 D UcmService: PersistentServices  value-1000
09-07 11:38:22.408  1250  1250 D UcmService: PersistentServices  key-com.sec.smartcard.manager:com.samsung.ucs.agent.baiMobile
09-07 11:38:22.408  1250  1250 D UcmService: PersistentServices  value-10043
09-07 11:38:22.418  1250  3553 D SSRM:bb : MSG_TYPE_UID_REMOVED::
09-07 11:38:22.418  2207  6639 I LocationSettingsChecker: Removing dialog suppression flag ,for package com.test.thalitest
09-07 11:38:22.418  1250  1250 I ActivityManager: Killing 5920:com.samsung.android.app.filterinstaller/1000 (adj 15): DHA:empty #31
09-07 11:38:22.418  1866  1866 W SQLiteLog: (28) failed to open "/data/user/0/com.google.android.gms/databases/gcm_registrar.db-journal" with flag (131138) and mode_t (1b0) due to error (30)
09-07 11:38:22.418  1866  1866 E SQLiteLog: (10) unixWrite() File Descriptor : 32 gets errno : 9
09-07 11:38:22.418  1866  1866 E SQLiteLog: (778) statement aborts at 16: [INSERT INTO packages(uid,package_name) VALUES (?,?)] 
09-07 11:38:22.418  1250  1371 W System.err: rename failed: EROFS (Read-only file system) : /data/system/users/0/runtime-permissions.xml -> /data/system/users/0/runtime-permissions.xml.bak
09-07 11:38:22.418  1250  1371 W AtomicFile: Couldn't rename file /data/system/users/0/runtime-permissions.xml to backup file /data/system/users/0/runtime-permissions.xml.bak
09-07 11:38:22.428  1866  1866 E SQLiteDatabase: Error inserting uid=0 package_name=com.wssyncmldm
09-07 11:38:22.428  1866  1866 E SQLiteDatabase: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 778)
09-07 11:38:22.428  1866  1866 E SQLiteDatabase: #################################################################
09-07 11:38:22.428  1866  1866 E SQLiteDatabase: Error Code : 778 (SQLITE_IOERR_WRITE)
09-07 11:38:22.428  1866  1866 E SQLiteDatabase: Caused By : Disk I/O error occurred during 'write' operation.
09-07 11:38:22.428  1866  1866 E SQLiteDatabase: 	(disk I/O error (code 778))
09-07 11:38:22.428  1866  1866 E SQLiteDatabase: #################################################################
09-07 11:38:22.428  1866  1866 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForLastInsertedRowId(Native Method)
09-07 11:38:22.428  1866  1866 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.executeForLastInsertedRowId(SQLiteConnection.java:915)
09-07 11:38:22.428  1866  1866 E SQLiteDatabase: 	at android.database.sqlite.SQLiteSession.executeForLastInsertedRowId(SQLiteSession.java:788)
09-07 11:38:22.428  1866  1866 E SQLiteDatabase: 	at android.database.sqlite.SQLiteStatement.executeInsert(SQLiteStatement.java:86)
09-07 11:38:22.428  1866  1866 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.insertWithOnConflict(SQLiteDatabase.java:1609)
09-07 11:38:22.428  1866  1866 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.insert(SQLiteDatabase.java:1479)
09-07 11:38:22.428  1866  1866 E SQLiteDatabase: 	at com.google.android.gms.gcm.GcmPackageTracker.c(:com.google.android.gms:292)
09-07 11:38:22.428  1866  1866 E SQLiteDatabase: 	at com.google.android.gms.gcm.GcmPackageTracker.a(:com.google.android.gms:219)
09-07 11:38:22.428  1866  1866 E SQLiteDatabase: 	at com.google.android.gms.gcm.GcmPackageTracker.a(:com.google.android.gms:124)
09-07 11:38:22.428  1866  1866 E SQLiteDatabase: 	at com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver.onReceive(:com.google.android.gms:332)
09-07 11:38:22.428  1866  1866 E SQLiteDatabase: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:3637)
09-07 11:38:22.428  1866  1866 E SQLiteDatabase: 	at android.app.ActivityThread.access$2000(ActivityThread.java:223)
09-07 11:38:22.428  1866  1866 E SQLiteDatabase: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1879)
09-07 11:38:22.428  1866  1866 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-07 11:38:22.428  1866  1866 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:158)
09-07 11:38:22.428  1866  1866 E SQLiteDatabase: 	at android.app.ActivityThread.main(ActivityThread.java:7231)
09-07 11:38:22.428  1866  1866 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Native Method)
09-07 11:38:22.428  1866  1866 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1230)
09-07 11:38:22.428  1866  1866 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1120)
09-07 11:38:22.428  1866  1866 W GCM-PT  : Unable to add package to the database
09-07 11:38:22.428  2207  6639 W SQLiteLog: (28) failed to open "/data/user/0/com.google.android.gms/databases/phenotype.db" with flag (131138) and mode_t (0) due to error (30)
09-07 11:38:22.428  1250  1986 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{a433ef6 u0 android.intent.action.PACKAGE_REMOVED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{ef1b27 1866:com.google.android.gms.persistent/u0a10}
09-07 11:38:22.428  1866  2223 W System.err: mkdir failed: EEXIST (File exists) : /data/user/0/com.google.android.gms/shared_prefs
09-07 11:38:22.428  1866  2223 E SharedPreferencesImpl: Couldn't create directory for SharedPreferences file /data/user/0/com.google.android.gms/shared_prefs/nlp-prefs.xml
09-07 11:38:22.428  1866  1866 E NetworkScheduler.SchedulerReceiver: Invalid parameter app
09-07 11:38:22.428  1866  1866 E NetworkScheduler.SchedulerReceiver: Invalid package name : Perhaps you didn't include a PendingIntent in the extras?
09-07 11:38:22.438  2207  6639 E SQLiteDatabase: Failed to open database '/data/user/0/com.google.android.gms/databases/phenotype.db'.
09-07 11:38:22.438  2207  6639 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-07 11:38:22.438  2207  6639 E SQLiteDatabase: #################################################################
09-07 11:38:22.438  2207  6639 E SQLiteDatabase: Error Code : 0 (SQLITE_OK)
09-07 11:38:22.438  2207  6639 E SQLiteDatabase: Caused By : not an error (code 0): Could not open the database in read/write mode.
09-07 11:38:22.438  2207  6639 E SQLiteDatabase: #################################################################
09-07 11:38:22.438  2207  6639 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
09-07 11:38:22.438  2207  6639 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:283)
09-07 11:38:22.438  2207  6639 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:210)
09-07 11:38:22.438  2207  6639 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
09-07 11:38:22.438  2207  6639 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
09-07 11:38:22.438  2207  6639 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
09-07 11:38:22.438  2207  6639 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
09-07 11:38:22.438  2207  6639 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
09-07 11:38:22.438  2207  6639 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
09-07 11:38:22.438  2207  6639 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:639)
09-07 11:38:22.438  2207  6639 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:283)
09-07 11:38:22.438  2207  6639 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:283)
09-07 11:38:22.438  2207  6639 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
09-07 11:38:22.438  2207  6639 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
09-07 11:38:22.438  2207  6639 E SQLiteDatabase: 	at com.google.android.gms.app.service.PackageBroadcastIntentOperation.onHandleIntent(:com.google.android.gms:51)
09-07 11:38:22.438  2207  6639 E SQLiteDatabase: 	at com.google.android.chimera.IntentOperation.onHandleIntent(:com.google.android.gms:76)
09-07 11:38:22.438  2207  6639 E SQLiteDatabase: 	at com.google.android.chimera.container.l.run(:com.google.android.gms:801)
09-07 11:38:22.438  2207  6639 E SQLiteDatabase: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
09-07 11:38:22.438  2207  6639 E SQLiteDatabase: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
09-07 11:38:22.438  2207  6639 E SQLiteDatabase: 	at java.lang.Thread.run(Thread.java:818)
09-07 11:38:22.438  2207  6639 E PhenotypeInitializer: Could not unregister android package com.test.thalitest
09-07 11:38:22.438  2207  6639 E PhenotypeInitializer: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-07 11:38:22.438  2207  6639 E PhenotypeInitializer: #################################################################
09-07 11:38:22.438  2207  6639 E PhenotypeInitializer: Error Code : 0 (SQLITE_OK)
09-07 11:38:22.438  2207  6639 E PhenotypeInitializer: Caused By : not an error (code 0): Could not open the database in read/write mode.
09-07 11:38:22.438  2207  6639 E PhenotypeInitializer: #################################################################
09-07 11:38:22.438  2207  6639 E PhenotypeInitializer: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
09-07 11:38:22.438  2207  6639 E PhenotypeInitializer: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:283)
09-07 11:38:22.438  2207  6639 E PhenotypeInitializer: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:210)
09-07 11:38:22.438  2207  6639 E PhenotypeInitializer: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
09-07 11:38:22.438  2207  6639 E PhenotypeInitializer: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
09-07 11:38:22.438  2207  6639 E PhenotypeInitializer: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
09-07 11:38:22.438  2207  6639 E PhenotypeInitializer: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
09-07 11:38:22.438  2207  6639 E PhenotypeInitializer: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
09-07 11:38:22.438  2207  6639 E PhenotypeInitializer: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
09-07 11:38:22.438  2207  6639 E PhenotypeInitializer: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:639)
09-07 11:38:22.438  2207  6639 E PhenotypeInitializer: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:283)
09-07 11:38:22.438  2207  6639 E PhenotypeInitializer: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:283)
09-07 11:38:22.438  2207  6639 E PhenotypeInitializer: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
09-07 11:38:22.438  2207  6639 E PhenotypeInitializer: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
09-07 11:38:22.438  2207  6639 E PhenotypeInitializer: 	at com.google.android.gms.app.service.PackageBroadcastIntentOperation.onHandleIntent(:com.google.android.gms:51)
09-07 11:38:22.438  2207  6639 E PhenotypeInitializer: 	at com.google.android.chimera.IntentOperation.onHandleIntent(:com.google.android.gms:76)
09-07 11:38:22.438  2207  6639 E PhenotypeInitializer: 	at com.google.android.chimera.container.l.run(:com.google.android.gms:801)
09-07 11:38:22.438  2207  6639 E PhenotypeInitializer: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
09-07 11:38:22.438  2207  6639 E PhenotypeInitializer: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
09-07 11:38:22.438  2207  6639 E PhenotypeInitializer: 	at java.lang.Thread.run(Thread.java:818)
09-07 11:38:22.438  1250  1994 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{a433ef6 u0 android.intent.action.PACKAGE_REMOVED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{44a50df 5627:com.android.vending/u0a19}
09-07 11:38:22.438  1250  2333 V AlarmManager:  remove PendingIntent] PendingIntent{d2cef60: PendingIntentRecord{e4edab6 com.google.android.gms broadcastIntent}}
09-07 11:38:22.448  5627  5627 W Finsky  : [1] com.google.android.finsky.FinskyApp.i(1379): No account configured on this device.
09-07 11:38:22.448  5627  5627 I Finsky  : [1] com.google.android.finsky.wear.WearSupportService.a(274): Wear auto uninstall disabled for package com.test.thalitest
,09-07 11:38:22.448  1250  1994 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{a433ef6 u0 android.intent.action.PACKAGE_REMOVED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{af855d3 4453:com.sec.spp.push/u0a26}

```
